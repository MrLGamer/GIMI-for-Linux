# Fix broken 3dmigoto mods

Sometimes the d3dcompiler_47.dll refuses to load too, so in this step we will try to force it to load. 

Example of a broken mod:
![12](https://user-images.githubusercontent.com/54450456/213921934-bb4a2259-40b4-4acf-8525-826be8ac576c.png)

1. Go into your Launcher settings and open "winecfg":  
![7](https://user-images.githubusercontent.com/54450456/213914320-2ecf8bdf-1bfb-475a-9225-9c9b26370edf.png)

2. A small window should appear. Go to the "Libraries" tab.  

![8](https://user-images.githubusercontent.com/54450456/213914582-70e79040-9eff-4be5-978b-93cb468b53b7.png)

3. Type for new dll library "d3dcompiler_47" and click on "Add"  

![13](https://user-images.githubusercontent.com/54450456/213922676-c2b797ff-1da9-4335-9988-1fb99ac09979.png)

4. In the menu you should now see "d3dcompiler_47 (Native, Builtin)".  
   If this is the case click on "Apply" and then on "ok".
   
![14](https://user-images.githubusercontent.com/54450456/213922860-6fb433ab-01b8-40e5-b570-de0333db3534.png)

5. That's it. The dll should now load properly.
