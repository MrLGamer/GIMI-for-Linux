# Fix 3dmigoto mods or (green text on dev version) not loading

Sometimes the d3d11.dll refuses to load, so in this step we will try to force it to load.  

1. Go into your Launcher settings and open "winecfg":  
![7](https://user-images.githubusercontent.com/54450456/213914320-2ecf8bdf-1bfb-475a-9225-9c9b26370edf.png)

2. A small window should appear. Go to the "Libraries" tab.  

![8](https://user-images.githubusercontent.com/54450456/213914582-70e79040-9eff-4be5-978b-93cb468b53b7.png)
  
3. Search for "d3d11" in the menu and click on it.
   Then press the "edit" button  

![9](https://user-images.githubusercontent.com/54450456/213915044-e08fc0e9-73bb-429a-8dd2-5e315b13ca82.png)
  
4. Another menu should appear. Change the Load order from "Native" to "Native then Builtin" and press ok  
  
![10](https://user-images.githubusercontent.com/54450456/213915365-d0ffb97a-52f9-4d3b-a905-689488f85ba7.png)

5. In the menu you should now see "d3d11 (Native, Builtin)".  
   If this is the case click on "Apply" and then on "ok".

![11](https://user-images.githubusercontent.com/54450456/213915757-2ac65162-7da0-4147-9d02-1d0b7c97b811.png)

6. That's it. The dll should now load properly.
