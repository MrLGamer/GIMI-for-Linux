# GIMI-for-Linux
A modified release for Genshin-Impact-Model-Importer (GIMI) to work on Linux with the  "An Anime Game Launcher"  
Special Thanks to [SilentNightSound](https://github.com/SilentNightSound) for creating the original version of [GIMI](https://github.com/SilentNightSound/GI-Model-Importer).

**DISCLAIMER:**  
**I do not condone the use of these programs on official servers and take no responsibility for the consequences if you do.**

## Installation Instructions (3DMigoto - An Anime Game Launcher)

1. Download a 3dmigoto .tar.gz from [releases](https://github.com/MrLGamer/GIMI-for-Linux/releases) and extract it. There are two versions:  

   - "linux-3dmigoto-GIMI-development.tar.gz" a development version intended for creating mods which has all features turned on (including the green text at the top and bottom of the screen) but is slower
   - "linux-3dmigoto-GIMI-playing.tar.gz" a version of the program indended for playing mods which has development features turned off (no green text) but is faster

2. Once extracted open up your Anime Game Launcher and go to settings:
![1](https://user-images.githubusercontent.com/54450456/213886896-8043efe5-c6ed-4098-bc4f-34826cad3c77.png)

Once in settings click on "game folder" which should open up your game where your GenshinImpact.exe is located:
![2](https://user-images.githubusercontent.com/54450456/213888273-1f216c62-3d7d-479e-ba55-483b6d45694f.png)

Now copy the files from the download and paste them into this directory like shown below:
![3](https://user-images.githubusercontent.com/54450456/213888558-705c638b-1e25-404e-b4c5-4c7fa0426bb3.png)
![4](https://user-images.githubusercontent.com/54450456/213888810-698a88b5-0c76-4d4f-86ab-23dec1cdab26.png)

Go back to launcher settings then click on "Wine version" and download/select the "Lutris 7.2-2" release:
![5](https://user-images.githubusercontent.com/54450456/213889090-5e561636-4404-4ed5-bbfe-9e1ad0395f06.png)

3. Close settings and launch the game . If everything is correct so far, 3DMigoto should be injected into the game and you should see a green text overlay (only if using the "development" version, the "playing" version does not show the green text):

![6](https://user-images.githubusercontent.com/54450456/213923373-5990254a-bed2-4f27-96e9-f3112f127c88.png)



4. Installation complete! You should now be able to load custom resources and override textures and shaders with 3DMigoto. To add mods, place them in the Mods folder (one mod per character at a time) and press F10 to load them in game:  

![Bildschirmfoto vom 2023-01-21 23-32-36](https://user-images.githubusercontent.com/54450456/213889573-97a8f3a9-23a4-4e64-a7f2-5738629d7c0a.png)  



## Troubleshooting  

[Fix 3dmigoto green text/mod not loading](Guides/3dmigotoNotLoading.md)  
  
[Fix broken Mods](Guides/BrokenMods.md)

[Fix broken Shadows](Guides/FixBrokenShadows.md)
