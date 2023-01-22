# Fix broken shadows on mods

some mods use a ShadowRamp texture, which is broken on Linux for some reason. I haven't found a good solution for this yet, so here is a small workaround

![Bildschirmfoto vom 2023-01-22 17-16-25](https://user-images.githubusercontent.com/54450456/213926592-22ab5b82-691f-4bb1-976b-457c778531dc.png)

Every mod has a .ini file. You can edit it and remove the ShadowRamp entries under "Overrides"


![Bildschirmfoto vom 2023-01-22 17-24-32](https://user-images.githubusercontent.com/54450456/213926943-792c4652-5ca2-4672-b22a-4d9c2c3aa8d9.png)

After removing the marked entries and saving the file, the shadows should be fixed. 
