# impulsetracker-renoise-3-pattern-fonts
ImplseTracker TTF fonts and pattern font configuration file for Renoise 3.2.x
Note: Small, Normal, and Huge obey the originbal ImpulseTracker/SchismTracker spacing and padding with 0px/flush spacing on top and 1x respective px of spacing on the bottom. The "Big" size still needs some tweaking to perfect since multiples of three, rather than doubling like the others will require some extra math to adjust all the TTF parameters.

INSTALL:
Find your Renoise fonts folder.
(save your old PatternConfig.xml in case there are problems)
Add these .TTF fonts and overwrite PatternConfig.xml

A little history: I had originally created custom bitmap fonts to match ImpulseTracker and SchismTracker. I overwrote the PatternFont*.fon fonts rather than editing PatternConfig.xml. Starting in Renoise 3.2 (iirc), the bitmap fonts were no longer supported, and even the original Renoise .fon files stopped working, as the new Renoise font was oddly skinny and anti-aliased, which looked horrible. I'm not sure if that was my fault or Renoise's fault. This may have been when .ttf fonts stared being supported as pattern fonts? To support HiDPI?

If you want to thank me or get some more expeditious support with a custom font, feel free to support me on bandcamp :] https://prot.audio
![image](https://user-images.githubusercontent.com/74881943/191960570-42140957-42c1-43ff-8fa4-2d65c8277f59.png)
