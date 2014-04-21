## MakerBot Custom Profiles

The MakerBot 3d prints below use [custom profiles](http://www.makerbot.com/support/makerware/documentation/advanced/) to render variations of the same object. You can access custom profiles in MakerWare by clicking Make -> Create Profile. Selecting a base profile will launch a text editor which will display tons of [Slicer Options](http://www.makerbot.com/support/makerware/documentation/slicer/) you can tweak.

If you remove the roof and floor entirely, you can have fun with different interior patterns by simply adjusting the 'numberOfShells' and 'infillDensity'. See the settings below for examples. I used [Wood PLA](http://www.makergeeks.com/wo3dprfild3.html) to emphasize the 'grain' effects you get when playing with the numberOfShells.

To install, copy the profiles from the 'Profiles' folder to your 'Things/Profiles' folder.

#### Sketchup file

The original 3d file was exported from Sketchup as an .stl file for MakerWare.

* outer diameter: 60mm
* inner diameter: 20mm
* height: 3mm

![Digital file](http://raw.githubusercontent.com/vinceallenvince/MakerBotCustomProfiles/master/images/torus30rad_10hole.png "Digital file")

#### Crop Circle

* doRaft: false
* layerHeight: 0.3 (0.3 = Low; 0.2 = Standard; 0.1 = High)
* roofThickness: 0
* floorThickness: 0
* numberOfShells: 2
* infillDensity: 0

![Crop Circle](http://raw.githubusercontent.com/vinceallenvince/MakerBotCustomProfiles/master/images/cropcircle-woodPLA.jpg "Crop Circle")

#### Waffle Iron

* doRaft: false
* layerHeight: 0.3 (0.3 = Low; 0.2 = Standard; 0.1 = High)
* roofThickness: 0
* floorThickness: 0
* numberOfShells: 4
* infillDensity: 0.5

![Waffle Iron](http://raw.githubusercontent.com/vinceallenvince/MakerBotCustomProfiles/master/images/waffleiron-woodPLA.jpg "Waffle Iron")

#### Dream Catcher

* doRaft: false
* layerHeight: 0.3 (0.3 = Low; 0.2 = Standard; 0.1 = High)
* roofThickness: 0
* floorThickness: 0
* numberOfShells: 8
* infillDensity: 0.1

![Dream Catcher](http://raw.githubusercontent.com/vinceallenvince/MakerBotCustomProfiles/master/images/dreamcatcher-woodPLA.jpg "Dream Catcher")

#### Spiral Cut

* doRaft: false
* layerHeight: 0.2 (0.3 = Low; 0.2 = Standard; 0.1 = High)
* roofThickness: 0
* floorThickness: 0
* numberOfShells: 100
* infillDensity: 0

![Spiral Cut](http://raw.githubusercontent.com/vinceallenvince/MakerBotCustomProfiles/master/images/spiralcut-woodPLA.jpg "Spiral Cut")
