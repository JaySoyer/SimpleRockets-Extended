# SimpleRockets-Extended

This mod is a simple "extension" to SimpleRockets which was designed to enhance various aspects of the game. It's still under development though perfectly stable to be used. Provides the following:
- Adds more celestrial objects.
- Attempts to standarize atmospheric heights
- Update existing planetary parameters

### Celestrial Objects
If the object is large enough to be spherical, it'll be in the game.  This includes Spluto and many more moons. Currently the following have been added.
- Titania Jr, Oberon Jr
- Proteus Jr, Triton Jr
- Spluto, Charon Jr

### Atmospheric Heights
Not entirely sure how the original atmospheric heights were determined. Looks like it was a mix of real life data that was changed for gameplay reasons.  While many atmospheric heights are quite variable, this mod attempts to "standarize" height determination as best as possible and forego gameplay considerations.  Specifically atmospheric heights are now based on real life scale heights and the air density where areocapture is generally possible (~10^-3.9).  Of course this is all rough estimates, but the goal is to get some form of consistency.

### Correcting Planetary Parameters
More like updating all Smolar System parameters from the same sources. While many of the real world values are not pinpoint exact, via standarizing where the info is pulled from, my hope is to come up with a more "common" realistic portrayal. It works as such:

- First, pull all information from [NASA factsheet](http://nssdc.gsfc.nasa.gov/planetary/factsheet/index.html).
- Any missing information, pull from Wikipedia
- If still missing information, pull from Wolfgram Alpha
- Finally, if STILL missing information, pull from any legit source.

Most NASA factsheet data was the same as the games...however a couple were very different. Eg, Smoon's semi-major axis.

# Installation
The following are the two ways to install for Windows.

### Via Cloning
1. Clone this repo into the directory `C:\Users\{UserName}\Documents\Jundroo\SimpleRockets\mods`
1. When loading SimpleRockets, you'll now of a mod section at the very bottom of the screen.
1. Within the mod section, you'll have the ability to (de)activate this mod...and any others.

### Via Downloading
1. Click the download button on the right hand side of the screen...or [click here](https://github.com/JaySoyer/SimpleRockets-Extended/archive/master.zip).
1. Extract the downloaded zip into the directory `C:\Users\{UserName}\Documents\Jundroo\SimpleRockets\mods`
1. When loading SimpleRockets, you'll now of a mod section at the very bottom of the screen.
1. Within the mod section, you'll have the ability to (de)activate this mod...and any others.
