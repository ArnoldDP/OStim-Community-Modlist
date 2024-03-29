# Ostim Community Modlist

Hello and thank you for reading this messy page. I'm currently in the process of cleaning it but there is a [discord server for people who need a little bit of support](https://discord.gg/vYkTp86CcZ).

<details>
 <summary>Description</summary>

OCM is meant to expand on Skyrim with more modern RPG elements while simultaneously making it feel more lifelike and immersive. It does not include any new lands (e.g. Bruma) or large quests (e.g. LoTD) and the adult themed content is entirely optional.

This is ***not*** pornrim with skimpy armor, public masturebation, and sexually aggressive wolves. While OStim is a sex mod framework, that doesn't mean that it has to be a $5 Steam hentai game. There are several lists that will cater to you if you prefer that type of content.

</details>

<details>
 <summary>Pre-installation and Requirements</summary>
 
 ### Pre-installation
 
 You are required to start with a clean, unmodified, and up to date installation of Skyrim SE/AE through the Steam store. If you are unsure of how to do this, I recommend following GamerPoets guide [here](https://www.youtube.com/watch?v=zQ5uNCKOKmI)

 If you fail to start with a clean installation, the list will most likely not install. 

 The game language also needs to be set to English. I'd assume you can change the localization afterwards but I honestly don't know due to being an ignorant English speaking American. My appologies.
 
 ### Requirements
 
 The only hard requirements to run the modlist are a CPU with AVX2 support and ~450 gigs of storage available.
 
> Recommended min specs for 1080p (CS - Low):
> 
> CPU: Ryzen 5 5600/intel i5 11600S
>  
> GPU: RTX 3060 8gb/RX 6600 8gb
>  
> RAM: 16gb ddr4 @2666 mhz
> 
> ~~Basically just generic gaming pc built after 2020~~

 With the above specs, you can expect an average of 60 fps in most places.

 I'm honestly not entirely sure what the minimum specs are for 1080p on the ENB - High profile but fwiw I have a 5600x, an RTX 4070ti, 32gbs of ram, and I play at 2560x1080 ultrawide.

 </details>
 
 
<details>
  <summary>Known issues</summary>
 
Shared quarters are missing in a few Inn's. If you would like shared accomodations for you and your followers, check to see if theres a hatch anywhere on the floor first.

Please do not hesitate to report any other bugs in the [OCM Support discord](https://discord.gg/MgDsHfmCEF)
 
 </details>
 
<details>
  <summary>A general overview</summary>

Seeing as the list is, for the most part, an expansion of vanilla content (Skyrim, Dawnguard, Dragonborn, and Hearthfire), it is a very vanilla+ list. 

Simonrim's suite of mods cover just about everything from cooking to combat. 

Sunhelm, Camping Lite, and Horizon Zero Dawn Fast Travel are used to make survival mode feel the way I think it should. 

Magic overhauls aren't particularly common relative to the other systems in Skyrim but I tried to make it feel a little bit more interactive with hundreds of new spells, Spellsiphon, and a fairly simple and gameplay friendly [Lichdom mod](https://www.nexusmods.com/skyrimspecialedition/mods/25654?tab=description).

With Seasons of Skyrim, a multitude of overhauls locational overhauls, and several new interesting places you can visit, it just felt fitting to add the paraglider and SkyClimb mods to make exploration feel just a little bit more modern.

Several of the quests, including the main story, have been overhauled by AYOP and JaySerpas various quest expansion mods. You also gain experience from exploration and completing quests as opposed to grinding your way through Bethesdas rather lackluster dungeons.
 
 </details>
 
  <details>
  <summary>OStim</summary>

  Obviously this list does have a fair amount of OStim integration. While most of it can be completely ignored if you want to, there are a few things to watch out for.

  * Brothels

    Theres two of them. The Rift's Rest (Riften) and The Naked Dragon (Markarth) are exactly what they sound like, whorehouses where you can go to do various things with various people.

  * A few of the followers

    Several of the followers, namely Auri, Caesia, Nessa, Kaidan, and M'rissi have OStim integration in their romance quests.

  * General Dialogue

    OStim Romance adds a fairly simple and straightforward dialogue based way to get people in bed with you.
  
 </details>
 
<details>
 <summary>Audio</summary>

 While this list isn't built to be an auditory experience, everyone likes good audio. 
 
 Every vanilla sound has been improved or changed. Most of this comes from Audio Overhaul for Skyrim, Immersive Sounds Compendium, several SFX replacers by Satafinix, and Unofficial HD Audio Project. These mods cannot be safely disabled without running your own synthesis patch.
 
 Just like SFX, the vanilla OST has improved clarity and songs from the mods Nyghtfall, Around the Fire, and Still have been added. The additions can be incredibly subjective, so you can easily disable it by disabling "big old music mod" in the **Audio** separator.
 
 </details>

<details>
 <summary>FAQ</summary>

*Can I make a suggestion?*


Absolutely, ⁠[suggestions](https://discord.gg/D6jTAatVT6) is open to the public. Bonus points to anything that's lore friendly.

*Can I add "x mod"?*

I can't stop you, nor do I intend to. Just remember that I am not liable for any issues that arise because of mods added post-installation. I suggest that you familiarize yourself with the list before you make changes.

*My map is broken!*

You have a mod loading after flat world map framework. Properly sort any mods that you add post installation otherwise a lot of things will be broken, not just the map.

*I want to change the replacer for "x character". How can I do that?*

The simple way is to overwrite the "npcmerg2" mod found in the gen files separator near the bottom. Make sure you overwrite both the mod and the plugins
The more difficult way to do it is to generate a new Easy NPC output. Refer to the mod page for a more detailed explanation on how to use the tool.

*How do I fast travel?*

Innkeepers and some general stores will sell an item called a Travel Pack. Left click this item in your inventory and it will allow you to fast travel

*Is Serana Dialogue Add-on included?*

No

*Will you add Serana Dialogue Add-on?*

No, but you can

*Why not?*

Unlike other voiced followers, you do not have the option to forego using her if you want to progress through the game (being forced to use something is bad). She also forces you to give up on using vanilla Serana (subjective) if you had her installed at any point in your save.

*My game crashed! What do I do?*

There will most likely be a crash log that can be found in C:\Users\user\Documents\My Games\Skyrim Special Edition\SKSE, it will be called something like "crash-bunch of numbers". Feel free to drop it in the [general-support section of the discord](https://discord.gg/aSKsAJQhtr)

</details>
<details>
  <summary>Root Builder</summary>
 
 ### Root builder
 
 This is a MO2 plugin that I use to manage things like ENBs, ReShade, and SKSE.

 Chooey has made an amazing four minute guide on what it is and how to use it.

 https://youtu.be/m3QjdslU_6w?si=dykjTXWlBI-KmH8G&t=108
 
 </details>

# Links

>[Consistently up-to-date modlist (C.U.M.)](https://loadorderlibrary.com/lists/ocm)

# Discords

>[OCM Support discord](https://discord.gg/MgDsHfmCEF)

>[OStim Standalone Official](https://discord.gg/qEhSpvUc5Z)
 
>[OStim Community](https://discord.gg/ostim)
 
# Patreon/Ko-Fi for various authors featured in the list
 
>Ace [patreon](https://www.patreon.com/skyrimaceanimations)

>Ace [ko-fi](https://ko-fi.com/skyrimaceanimations)
 
>Aietos [ko-fi](https://ko-fi.com/aietos)
 
>Baka [patreon](https://www.patreon.com/BaboFactory)

>Doodle [ko-fi](https://ko-fi.com/doodlez)

>Doodle [patreon](https://www.patreon.com/Doodlezoid)

>Drago [patreon](https://www.patreon.com/DragoAnimations)
 
>Kreiste [patreon](https://www.patreon.com/kreiste)

>Moon [ko-fi](https://ko-fi.com/callmemoon)

>Silver [ko-fi](https://ko-fi.com/silvermilfactory)

>Sswaye [ko-fi](https://ko-fi.com/katsusswaye)
 
>Urbon [ko-fi](https://ko-fi.com/urbon)

>Vaenia [patreon](https://www.patreon.com/Vaenia121)
 
>VersuchDrei [patreon](https://www.patreon.com/VersuchDrei)

If one of your mods are featured in the list, feel free to dm me on discord @arnoldp. I'll add you whenever I get the chance.
 
 <Details>
  <summary>donations</summary>
 
I will not personally accept donations, I simply compiled a list. If one of your mods are featured in the list, just dm me a link to your page and I'll add it. 
  
  </details>
