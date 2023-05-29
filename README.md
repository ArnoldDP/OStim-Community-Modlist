# Unofficial Ostim Community Modlist
# DESCRIPTION

This is a modlist focused on refreshing the game to make it feel a bit more modern while adding some spicy roleplay oportunities :)

New textures, updated meshes, a more diverse range of enemies, and an update for nearly every vanilla npc in the game. Oh, and the funny sex mod, can't forget about that. Most, if not all, of the gameplay mods are just simple enhancers to the vanilla Skyrim experience, and a lot of subjective quest mods were avoided because they could cause unnecessary bloat.


# PREINSTALLATION
 
 It is recommended that you start with a clean, unmodified, and up to date installation of Skyrim through the Steam store (no GOG, sorry). A modified version may fail to install properly, if at all.
 If you downgraded, validate your files by going to your library, right clicking "The Elder Scrolls V: Skyrim Special Edition", select properties, local files, and then click verify integrity of game files. Alternatively, you can completely uninstall the game and all related files and then reinstall it. After thats done, you can proceed with the installation.
 
 The only hard requirements to run this modlist are a CPU with AVX2 support and ~230 gigs of storage available.
 
 Recommended min specs for 1080p:
 
  CPU: Ryzen 5 5600/intel 11600k
  
  GPU: RTX 3060 8gb/RX 6600 8gb
  
  RAM: 16gb ddr4 @2666 mhz
 
 ~~Basically just generic gaming pc built after 2020~~
 
 Obviously if your hardware is better, there shouldn't be any issues.
 
 I tried to keep the textures around 1-2k, but female skin textures, a few armors, and mountains are still 4k. These can be downscaled using Cathedral Asset Optimizer if you need that extra bit of performance. 
 
 Need even more? Disable QW's Grass Patch and all but one of the three included grass mods + the associated ENB Complex Grass mod ***WARNING*** This will make grass LODs not match.  
 
 ![image](https://user-images.githubusercontent.com/122011472/224244569-f1a67d98-4e4e-4b3b-9866-47c9e1a47936.png)


# KNOWN ISSUES
 
 This list is usually updated once a month. More bugs can appear and be removed.
 
ENBSeries may fail to install through Wabbajack. More often than not, this is because Boris updated the binaries without a version change. DM me @Arnold#1526 and I'll just give you the files, just drop them in your Wabbajack download folder.

On the off chance that the game doesnt automatically downgrade, you can use the patcher below.

https://www.nexusmods.com/skyrimspecialedition/mods/57618

 If you find any gamebreaking/major bugs (frequent crashing, infinite loading screens, extreme stuttering, etc), please dm me on Discord @Arnold#1526
 
# ENBs, LODs, Parallax, and all the other fun stuff

 Managing ENB presets is easier than ever thanks to Root Builder! Install them through MO2 like any other mod, and let Root Builder take care of it. If it doesn't work the first time, reinstall and select [Manual]
 
 Right click <data>, create directory, and name it "root". Then just drag and drop enbseries.ini, enblocal.ini, and the enbseries folder into the directory you just made. If done properly, it should look like this
 
 ![image](https://user-images.githubusercontent.com/122011472/224231824-0c7f8f4b-c85d-42b3-bd82-0dbfc001d258.png)
 
 Now you can disable or enable it whenever you want just like any other mod :)

Most of the included textures are Complex Parallax compatible. If an ENB preset you installed doesnt have complex parallax enabled by default, open up the enbseries.ini, and change the following settings to look like this

 1. EnableTerrainParallax=false
 2. EnableComplexGrass=true
 3. EnableComplexGrassCollisions=true
 4. EnableTerrainBlending=true
 5. EnableComplexParallax=true
 6. EnableComplexParallaxShadows=true
 7. EnableComplexTerrainParallax=true
 8. EnableComplexTerrainParallaxShadows=true

 
 If any of these lines are missing from the enbseries.ini, you can simply copy and paste the missing lines into the file. It will work just fine.
 
 The list comes with Rudy for NAT 3. Other ENB presets I highly recommend are NAT 3.1, Berserkyr, and Cabbage.

If you want to change the weather to anything other than NAT, Azurite, Vivid Weathers, or Aequinoctium, you should disable ***FWMF for Fantasy Paper Maps Weather and Lighting Fix.esp***

![image](https://user-images.githubusercontent.com/122011472/224233588-68c316a5-8cc2-4849-aa24-9caad041069c.png)
 
 I didnt originally want to include LODs for performance and compatibility reasons, but that was kind of dumb and lazy on my part. If they hurt your performance, just disable lodgen, texgen, and dyndolod outputs.
 
 If you wish to generate your own LODs, make sure you disable Flat World Map Framework and all of its add-ons beforehand. They can be found under the ***Flat World Map Framework*** separator near the bottom of the list. After you're done generating, you can re-enable FWMF, but make sure you keep everything from FWMF *below* DynDOLOD and Occlusions in the plugin load order. Your load order should look like this:

1. DynDOLOD
2. Occlusions
3. FWMF for Fantasy Paper Maps
4. FWMF Patches (evlas, weathers, etc)
4. Additional FWMF Maps

It is highly recommended to read a guide on LOD generation, theres about a quarter million of them for a reason.

>You will need to add an argument like-d:"F:\SteamLibrary\steamapps\common\Skyrim Special Edition\Data". Alternatively, you can temporarily change the game data path to the default skyrim directory in the MO2 Paths settings.

Since I dont personally use ReShade, I cant give a very good guide. Thankfully, the legendary Sswaye himself has written an excellent guide on it. Check out his collection! https://www.nexusmods.com/skyrimspecialedition/mods/67966

# Links

>Mega link for the .wabbajack file: https://mega.nz/file/sbtk1RLC#a3WUe8xcOpp01DaiENv2ygrD1E0voaVOsIIkaEoMSsw

>Join the discord! https://discord.gg/ostim

Patreon, ko-fi, etc for various mod authors featured on this list (@me if i forgot about you, I don't know who does and doesn't have a thing set up)
 
>Baka (BHUNP): https://www.patreon.com/BaboFactory
 
>Kreiste (HIMBO): https://www.patreon.com/kreiste

>Moon (animations): https://ko-fi.com/callmemoon
 
>Ace [Patreon] (various): https://www.patreon.com/skyrimaceanimations

>Ace [ko-fi] (various): https://ko-fi.com/skyrimaceanimations

>Silver (milfactory): https://ko-fi.com/silvermilfactory

>Aietos (various): https://ko-fi.com/aietos

>Sswaye (sswaye): https://ko-fi.com/katsusswaye

>Vaenia (OStim Lovers): https://www.patreon.com/Vaenia121
 
>VersuchDrei (various): https://www.patreon.com/VersuchDrei
