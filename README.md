***I'm thinking of reworking this hud, so don't expect any updates on this repo, the hud is usable though, you can try it out***

terry's hud
===========

Installation
------------
1. Download the ZIP file using **Code** button on the top of the GitHub page.
2. Place the unzipped folder inside of your **tf/custom** folder.
3. Done!

Uninstallation
--------------
1. Simpy delete the hud folder in your **tf/custom** folder.

Changing crosshairs
-------------------
1. Go to your **terrys-hud-master/scripts** folder and open **hudlayout.res** file with any text editor you have installed.
2. Inside of the file you should see these lines on top:
```vgui
// Broesel's Crosshairs
//#base "../resource/crosshairs/broesel/crosshair.res"
//#base "../resource/crosshairs/broesel/crosshair-blur.res"

// Fog's Crosshairs
//#base "../resource/crosshairs/fog/crosshair.res"
//#base "../resource/crosshairs/fog/crosshair-blur.res"

// Knuckles' Crosshairs
//#base "../resource/crosshairs/knuckles/crosshair.res"
//#base "../resource/crosshairs/knuckles/crosshair-blur.res"

// Toonhud Crosshairs
//#base "../resource/crosshairs/toonhud/crosshair.res"
//#base "../resource/crosshairs/toonhud/crosshair-blur.res"

// Whahay's Crosshairs
//#base "../resource/crosshairs/whahay/crosshair.res"
//#base "../resource/crosshairs/whahay/crosshair-blur.res"
```
  Uncomment any crosshair pack you want to use:
```vgui
// Knuckles' Crosshairs
#base "../resource/crosshairs/knuckles/crosshair.res"
#base "../resource/crosshairs/knuckles/crosshair-blur.res"
```
3. Go to your **terrys-hud-master/resource/crosshairs** folder and open the folder of crosshair pack you picked.
4. Open **crosshair.res**, **crosshair-blur.res** and **crosshair-preview.png** files.
5. Pick any crosshair you want and type the value from the top of it in ``"labelText"		"p"`` line in both **crosshair.res** and **crosshair-blur.res** files.
6. Edit the crosshair properties in ``"font"			"Knuckles, Size:18, Outline:Off, Blur:Off"`` line in both files and you're done.

Links
-----
[**My Steam Profile**](https://steamcommunity.com/id/t3rry4/)

[**My site**](http://terry.ezyro.com/)
