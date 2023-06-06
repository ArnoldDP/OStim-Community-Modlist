# Unofficial Ostim Community Modlist

<details>
 <summary>Description</summary>

 ### Description
 
 
* What this isnt

This is not pornrim with barely clothed women, public masturebation, and sexually aggressive wolves, nor it is a hyperrealistic soulslike with a grueling survival mode and a map size that rivals Daggerfall. It's also not an Elysium Remastered clone (no disrespect to the original author) with the small addition of OStim.

* What this is

 It's an aesthetically pleasing and immersive overhaul for nearly every aspect of the game that stays true to The Elder Scrolls style, while adding plenty of spicy roleplay opportunities :^)

The gameplay mods are just simple enhancers to the vanilla Skyrim experience. A lot of subjective quest mods were avoided because they could cause unnecessary bloat.

</details>

<details>
 <summary>Preinstallation and Requirements</summary>
 
 ### Preinstallation
 
 It is recommended that you start with a clean, unmodified, and up to date installation of Skyrim through the Steam store (no GOG, sorry). A modified version may fail to install properly, if at all.
 If you downgraded, validate your files by going to your library, right clicking "The Elder Scrolls V: Skyrim Special Edition", select properties, local files, and then click verify integrity of game files. Alternatively, you can completely uninstall the game and all related files and then reinstall it. After thats done, you can proceed with the installation.
 
 ### Requirements
 
 The only hard requirements to run this modlist are a CPU with AVX2 support and ~260 gigs of storage available.
 
> Recommended specs for 1080p:
> 
> CPU: Ryzen 5 5600/intel i5 11600k
>  
> GPU: RTX 3060 8gb/RX 6600 8gb
>  
> RAM: 16gb ddr4 @2666 mhz
> 
> ~~Basically just generic gaming pc built after 2020~~
> 
> Obviously if your hardware is better, there shouldn't be any issues.
 
 I tried to keep the textures around 1-2k, but female skin textures and a few misc items are 4k. These can be downscaled using Cathedral Asset Optimizer if you need that extra bit of performance. 
 
 </details>
 
<details>
  <summary>Known issues</summary>
 
 ### Bugs and Installation Failures
 
 This list only really gets updated whenever any of the major mods it utilizes are updated or if I see something that should be added to it. If you find any major/gamebreaking bugs, please report them to me on discord @Arnold#1526
 
ENBSeries may fail to install through Wabbajack. More often than not, this is because Boris updated the binaries without a version change. DM me and I'll give you the files, just drop them in your Wabbajack download folder.

On the off chance that the game doesnt automatically downgrade, you can use the patcher below.

https://www.nexusmods.com/skyrimspecialedition/mods/57618
 
 </details>
 
<details>
  <summary>A Brief explanation of the "major" gameplay changes</summary>
 
 ### Gameplay overhauls and rebalancing
 
 
 * Melee
 
Melee combat is handled by by ADXP + One Click Power Attack NG, as well as Valvalis Combat - Visceral Tactics. This is a patch that allows the mods Precision, Valhalla Combat, and Valravyn to work together in a cohesive way. Dodge - MCO is also provided. You can adjust these mods and their keybinds in their respective MCMs.

Chemmings Nordic animations for ADXP/MCO were chosen because I just felt like it would fit the best, but you are free to swap it out with any ADXP/MCO compatible moveset you'd like.
 
 * Magic
 
Magic has had dozens of new spells added to the game including Hemomancy, Mysticicsm, Abyss, Lunaris, and Natura. I also included Spellsiphon, an incredibly unique gameplay mod that can automatically integrate both vanilla and modded spells into its system should you choose to use it, the book can be found in High Hrothgar.

 * Races
 
Racial abilities are covered by Evolution - Skyrim Races Rejuvenated. It makes several small changes to make races feel more unique, and not just reskins with a minor power that youll rarely use.

 * Perks
 
Perks are handled by Vokrii. This is an extremely lightweight and minimalistic approach to perk overhauls. You can enjoy the small quality of life improvements it makes without being overwhelmed by an absurd number of changes.

 * Vampires and Werewolves
 
Lycanthropy and Vampirism are handled by Growl and Sacrilege. These two mods, like Vokrii, make small adjustments to the balance of these "diseases" that allows for more diverse and fun playstyles.

 * Stealth
 
Stealth had a few changes to make the vanilla thief more interesting. Book of Shadows adds several new systems such as takedowns, smokebombs, and more. Take a Peak is also included, and allows you to simply look through keyholes, maybe you'll see something fun? :^)
 
 * Survival
 
 Survival is handled by Sunhelm Survival and Camping Lite. These two mods are lightweight, customizable, and entirely optional. You can enable or disable survival through the MCM.
 
 Almost all of these gameplay mods can be completely ignored, or fully embraced. The choice is yours.
 
 </details>
 
<details>
  <summary>ENBs, ReShade and Root Builder</summary>
 
 ### ENB

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
 
 The list comes pre-installed with Rudy for NAT 3. Other ENB presets I highly recommend are NAT 3.1, Berserkyr, and Cabbage.

If you want to change the weather to anything other than NAT, Azurite, Vivid Weathers, or Aequinoctium, you should disable ***FWMF for Fantasy Paper Maps Weather and Lighting Fix.esp***

![image](https://user-images.githubusercontent.com/122011472/224233588-68c316a5-8cc2-4849-aa24-9caad041069c.png)
 
### ReShade
 
Since I dont personally use ReShade, I unfortunately cannot write a very good guide on it. Thankfully, the legendary Sswaye himself has written an excellent guide. Checck out his collection! https://www.nexusmods.com/skyrimspecialedition/mods/67966
 
 </details>

# Links

>Mega link for the .wabbajack file: https://mega.nz/file/sbtk1RLC#a3WUe8xcOpp01DaiENv2ygrD1E0voaVOsIIkaEoMSsw

>VersuchDrei's discord https://discord.gg/qEhSpvUc5Z
 
>Ace's Discord https://discord.gg/ostim
 
 <details>
  <summary>Community note</summary>
  
  ### There are two discords

  Since there can't technically be an "official" OStim discord (to my knowledge), both of the servers listed are "official". Feel free to join both.
  
 </details>
 
Patreon, ko-fi, etc for various mod authors featured on this list (@me if I forgot about you)
 
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
