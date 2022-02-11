# P-QoL
P-QoL, or in details, **Performance Quality-Of-Life** (yeah it's a weird name), is a simple modpack for people who have the curiousity of pushing the boundary of **Minecraft optimization** but also keeping the Quality-Of-Life vibes throughout the gameplay, as well as a starting point for any new Fabric users who are willing to see what equivalents Fabric has to offer to them (or somehow change their view about using Optifine and shift to Sodium)

> Simple definition for this modpack is making your gameplay more ideal, have the fancy view while still having the performance you want.
# Before installing the modpack
This modpack were made just for my personal use only, it might break some functions in Minecraft, I won't guarantee this mod **100% stable**, so any problems you have while running the modpack, please make [a new issue](https://github.com/Scarlaid/P-QoL/issues) and I try to response as soon as possible :D
### Suggested by [this dude](https://discord.com/users/437854007181049866) to make a GitHub Repo lol
![image](https://user-images.githubusercontent.com/90851437/153533331-5ae0d7c2-481a-427d-8759-23b22a5b24b0.png)
# How to install this modpack?
Simple enough, here are some steps to install my modpack:
- Install Minecraft first, if you dont't have Minecraft installed then why are you here?
- Download [Fabric Mod Loader](https://fabricmc.net) then install `Fabric v0.13.1` using [the universal jar](https://fabricmc.net/use/installer/) 
- Open your Minecraft launcher to check if there is Fabric Mod Loader installed
- Type `%appdata` in your File Explorer/search `%apppdata`/Windows + R then type `%appdata%` then Enter
- Find your `.minecraft` folder, that will be where you Minecraft versions/data stored
- Download the ZIP file from [here](https://github.com/Scarlaid/P-QoL/releases/tag/v1.0.0), extract it and you will recieve a folder with the name **mods**
- Run the game with Fabric Mod Loader you just installed
- Gratz you made it, now enjoy the ~~lag~~ smooth-like-butter gameplay with QoL vibes
### Optional steps
- Download [Zulu JDK 17](https://www.azul.com/downloads/?package=jdk)
- Go to your Minecraft version/installation/setting, find `Java Executable` then follow the path to find `javaw.exe` from Zulu JDK (example for mine is always in `C:\Program Files\Zulu\zulu-17\bin\javaw.exe`)
- Fine `JVM Arguments`, paste [this](https://pastebin.com/4piKwgCy) in
- Run the game with the mods, JVM arg and the JavaExe you just installed
# Included mods
This modpack was inspired from this [list of Optifine alternatives](lambdaurora.dev/optifine_alternatives/),  but it's doesn't mean it will stop there.
Here you can find the mods with any little detail about each of them, keep in mind that I only make this modpack for **only 1.18.1** so if you came for modpacks that supports lower than 1.18, this is not the place.
### Performance
| Name | Author | Description | Note |
| ------------- | ------------- | ------------ | ------------| 
| [Sodium](https://github.com/CaffeineMC/sodium-fabric/releases) | [CaffeinMC](https://github.com/CaffeineMC) | Optimization mod for the Minecraft client that improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft, as well as adds some graphics options | Doesn't have **all** the settings like Optifine |
| [Lithium](https://github.com/CaffeineMC/lithium-fabric) | [CaffeinMC](https://github.com/CaffeineMC) | A mod which works to optimize many areas of the game in order to provide better overall performance | Works good for both for **client** and (or) **server**
| [Hydrogen](https://github.com/CaffeineMC/hydrogen-fabric) | [CaffeinMC](https://github.com/CaffeineMC) | Reduce the game's memory requirements by implementing more memory-efficient data structures and logic | Works good for both for **client** and (or) **server**, might break some mods that you willing to have in Singleplayer
| [FerritCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric) | [malte0811](https://github.com/malte0811) | Reduce the game's memory requirements | [Here is the detailed decription](https://github.com/malte0811/FerriteCore/blob/1.18/summary.md)
| [Starlight](https://github.com/PaperMC/Starlight) | [PaperMC](https://github.com/PaperMC) | Fabric mod for completely rewriting the Vanilla light engine | Incompatible with [Phosphor](https://github.com/CaffeineMC/phosphor-fabric), but a payback, better performance
| [C2ME](https://github.com/RelativityMC/C2ME-fabric) | [RelativityMC](https://github.com/RelativityMC) | C^2M-Engine, or C2ME for short, is a Fabric mod designed to improve the performance of chunk generation, I/O, and loading. This is done by taking advantage of multiple CPU cores in parallel | Might be unstable for most Onboard GPU because of the intensive this mod offers
| [LazyDFU](https://github.com/astei/lazydfu) | [astei](https://github.com/astei) | Optimization mod that makes the initialization of DataFixerUpper "more lazy" - that is, it will not immediately create the rules required to migrate data from older versions of Minecraft to newer versions until it actually needs to do so | "Ah, lazy just like me making this repo" |
| [Smooth Boot](https://github.com/UltimateBoomer/mc-smoothboot) | [UltimateBoomer](https://github.com/UltimateBoomer) | Improve and tweak Minecraft CPU scheduling | The config file is in `config.json` so you might need [this](https://code.visualstudio.com)
| [Krypton](https://github.com/astei/krypton) | [astei](https://github.com/astei) | Fabric mod that attempts to optimize the Minecraft networking stack | No little performance notice in multiplayer but you might see them more in Singleplayer while opening a LAN server
| [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader) | [QuantumFusion](https://github.com/QuantumFusionMC) | This mod improves Minecraft client asset loading times about 6x by caching all of the game's content | **100% Multi-threaded** but incompatible with [Enhanced Blocks Entities](https://www.curseforge.com/minecraft/mc-mods/enhanced-block-entities), kinda unstable for rendering texture that you might encounter [this](https://github.com/QuantumFusionMC/DashLoader-Definitions/issues/1)
__________
### Smooth-*ish* (?)
| Name | Author | Description | Note |
| --- | ---- | ------------ | ----| 
| [NoFade](https://github.com/UltimateBoomer/mc-no-fade) | [UltimateBoomer](https://github.com/UltimateBoomer) | Removes all the *annoying* fade-out animations in Minecraft | :poggers:
| [Language Reload](https://github.com/Jerozgen/LanguageReload) | [Jerozgen](https://github.com/Jerozgen) | Fabric mod that reloads languages without resource pack reloading using F3 + J | Might break with [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader), at least for me, once
| [FastOpenL&F](https://github.com/altrisi/FastOpenLinksAndFolders) | [astei](https://github.com/astei) | A lightweight mod to make the game not freeze when opening a chat link, a screenshot or either the resourcepacks or datapacks folder | *Opening links/folders at the speed of my dad buying milk after hearing me won the lottery* |
| [NoChatLag](https://github.com/NoahvdAa/NoChatLag) | [NoahvdAa](https://github.com/NoahvdAa) | Rendering the ingame chat in another thread to improve the gameplay by not rendering the chat on the same thread Minecraft running | I'm not sure [v1.1.0](https://github.com/NoahvdAa/NoChatLag/releases/tag/1.1.0) changed anything, but for now the modpack still sticking with [v1.0.0](https://github.com/NoahvdAa/NoChatLag/releases/tag/1.0.0) because it's stable enough
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | [jaredlll08](https://github.com/jaredlll08) |  Groups XP orbs together into a single entity to reduce lag when there are many in a small area, also giving the player collecting all the orbs immediately | *Yoinking all the exp from the Ender Dragon* |
| [FastChest](https://www.curseforge.com/minecraft/mc-mods/fastchest) | [FakeDomi](https://github.com/FakeDomi) | Removing dynamic models from chests and making them render as static chunk geometry, make chest rendering less **intense** in a wide area with a lot of filled chests | This mod will make the chest no more have the opening/closing animation, which might annoy you. [For troubleshooting the chests (any chest) textures being invisisble](https://github.com/FakeDomi/FastChest/issues/10)
| [Enhanced Blocks Entities](https://www.curseforge.com/minecraft/mc-mods/enhanced-block-entities) | [FoundationGames](https://github.com/FoundationGames) | A Fabric mod which aims to increase the performance of block entity rendering, as well as offer customizability via resource packs | Incompatible with [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader) at the moment with double chest texture being [*cursed*](https://github.com/FoundationGames/EnhancedBlockEntities/issues/71)
| [Better Beds](https://www.curseforge.com/minecraft/mc-mods/better-beds) | [TeamMidnightDust](https://github.com/TeamMidnightDust) | Removes the BlockEntityRenderer from the bed and replaces it with the default minecraft model renderer | You might facing very little **half-of-a-bed** issue when placing down a bed
| [TimeOut Out](https://github.com/houby-studio/TimeOutOut) | [houby-studio](https://github.com/houby-studio) | Connection timeout configuration | [RandomPatches](https://github.com/TheRandomLabs/RandomPatches) ~~skid~~ standalone mod, read [this](https://cdn.discordapp.com/attachments/810700087054434358/941635979679244298/unknown.png) for more information
______
### Fixes/Patches/Additions
| Name | Author | Description | Note |
| --- | ---- | ------------ | ----| 
| [TieFix](https://github.com/j-tai/TieFix) | [j-tai](https://github.com/j-tai) | A Fabric mod that fixes some annoying bugs in the Minecraft client | Toggable if you feel like those **patches** was intentional for the game to function
| [Item Model Fix](https://github.com/PepperCode1/Item-Model-Fix) | [PepperCode1](https://github.com/PepperCode1/Item-Model-Fix) | A Fabric mod that fixes gaps in generated item models, noticable in high resolution texture packs | "You know that moment when you randomly looking at your sword and see those white lines? Yeah me neither"
| [ToolTipFix](https://www.curseforge.com/minecraft/mc-mods/tooltipfix) | [kyrptonaught](https://github.com/kyrptonaught) | A mod to stops tooltips that are too large to fit on the screen from running off the screen | ***Every Hypixel Skyblock Custom Item be like***
| [ClientTweaks](https://www.curseforge.com/minecraft/mc-mods/client-tweaks-fabric) | [Modding For Blockheads](https://github.com/ModdingForBlockheads) | Adds a bunch of optional tweaks to improve the Quality of Life during gameplay, such as hiding offhand hold items in specific situation | Replacement for [No Potion Offset](https://www.curseforge.com/minecraft/mc-mods/no-potion-offset) since no announements for 1.18.1 update
| [Axolotl Bucket Fix](https://www.curseforge.com/minecraft/mc-mods/axolotl-bucket-fix) | [CoolLavaLamp](https://github.com/ColdLavaLamp/axolotl-bucket-fix) | Fixes the item texture of holding a bucket of axolotl shows you what's actually inside it | This mod has both textures for the baby forms and the grown forms, will also show the color variant of which axolotl in your bucket!
| [Better Mount HUD](https://www.curseforge.com/minecraft/mc-mods/better-mount-hud) | [Lortseam](https://gitlab.com/Lortseam) | Improves the ingame HUD while riding any ridable mount | Shows all the hunger bar, the health bar and the experience bar [like this](https://www.youtube.com/watch?v=NMLm6rk_p9Q). Works well and clean with [this](https://github.com/LegoRaft/simple-armor-hud)
| [Your Options Shall Be Respected](https://www.curseforge.com/minecraft/mc-mods/yosbr) | [shedaniel](https://github.com/shedaniel) | Keeps your ingame settings whenever loading a new modpack | "Okay, Whenever I switch to Lunar Client to play some bedwars, then back to using Fabric with modpack, I have to go through my settings all from the start to finish, and this mod is a savior, honestly" - Me, probably
| [Not Enough Crashes](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes) | [natanfudge](https://github.com/natanfudge/not-enough-crashes) | Keeping the game open while also giving a `crash-report` as a website (optional) whenever the game crashed | Easy issue tracking and convenient, cool stuff 👍
| [More Chat History](https://www.curseforge.com/minecraft/mc-mods/more-chat-history) | [JackFred2](https://github.com/JackFred2) | Capping the chat history to, of course, more than 100 messages that Mojang don't even bother extending it | "Now I think of it, this mod might be ported into both Lunar and Badlion, but you know, it's just a theory, **a game theory**" - Matt Patt, maybe 👀
| [Fabrishot](https://www.curseforge.com/minecraft/mc-mods/fabrishot) | [ramidzkh](https://github.com/ramidzkh) | F2 in better resolution and auto-align your HUD to fit with the resoulution | Can overwrite vanilla screenshot or a seperated hotkey is all you, who doesn't want a 4k screenshot?
| [Screenshot to Clipboard](https://www.curseforge.com/minecraft/mc-mods/screenshot-to-clipboard-fabric) | [comp500](https://github.com/comp500) | After taking a screenshot ingame, the image data is copied to the clipboard | Why Mojang didn't think of this? Would be cool if they add an option to open the screenshot folder or a GUI like [Nicephore](https://github.com/LotuxPunk/Nicephore-Fabric)
| [CleanCut](https://www.curseforge.com/minecraft/mc-mods/cleancut) | [Rongmario](https://github.com/Rongmario) | Attack enemies through obstructions (Block has no collision OR the block having 0.0 hardness) | "Noooo you can't just smite me with a sword through grasses/sunflowers/canes" - "Haha lawnmowing mobs goes brrrrr"
| [Clear Skies](https://www.curseforge.com/minecraft/mc-mods/clear-skies) | [grondag](https://github.com/grondag) | Makes horizon and fog colors match the sky | Mojang legit went with [this one](https://cdn.discordapp.com/attachments/810700087054434358/941623610911641621/without-day.png) instead of [this one](https://cdn.discordapp.com/attachments/810700087054434358/941623667585069086/with-day.png)...
| [Horse Stats Vanilla](https://github.com/d4rkm0nkey/HorseStatsVanilla) | [d4rkm0nkey](https://github.com/d4rkm0nkey) | Show horse stats in its Inventory HUD | [Fast as frige boi](https://www.youtube.com/watch?v=bEhwGWmO58A)
| [Chime](https://github.com/emilyploszaj/chime) | [emilyploszaj](https://github.com/emilyploszaj/chime) | A Fabric mod that adds a predicate system for more dynamic and interesting item model variation | I have no idea what this does, but assuming it's recommneded from Lamb, I'm not complaining lol
| [EntityCulling](https://github.com/tr7zw/EntityCulling)| [tr7zw](https://github.com/tr7zw) | Using async path-tracing to skip rendering Tiles/Entities that are not visible |  Imagine a world, rendering a whole mobfarm and what you got with Optifine is 30fps smh (More information can be found in their repo)
| [More Block Predicates](https://modrinth.com/mod/mbp/versions) | [omoflop](https://modrinth.com/mod/mbp) | Adds more predicates to block models, e.g biome, posistion and light level | This thing, right here, saves my *not-so-OCD* moment I had in Minecraft, like some blocks is pixels aways from others and I'm just-
| [Sodium Extra](https://github.com/FlashyReese/sodium-extra-fabric) | [FlashyReese](https://github.com/FlashyReese) | Add some features that **Sodium should not have** | Wdym ["shouldn't have"](https://cdn.discordapp.com/attachments/810700087054434358/941636669986205756/unknown.png), this is literally Optifine settings but better
| [Reese's Sodium Options](https://github.com/FlashyReese/reeses-sodium-options) | [FlashyReese](https://github.com/FlashyReese) | Makes Sodium settings GUI in **vertical** line instead of **horizonal** | As a 720p screen user, I found this relatable when the GUI just slide off the screen...
_______
### Optifine Alternatives
| Name | Author | Description | Note |
| --- | ---- | ------------ | ----| 
| [Ok Zoomer](https://www.curseforge.com/minecraft/mc-mods/ok-zoomer) | [EnnuiL](https://github.com/EnnuiL) | Zoom function, configurable and scrollable | [Bummer do be Zummer not clickbate 😱](https://youtu.be/n3Vteogicxs)
| [Cull Leaves](https://github.com/TeamMidnightDust/CullLeaves) | [TeamMidnightDust](https://github.com/TeamMidnightDust) | Adds "Smart Leaves" setting, *somehow* providng a *thicc* performance boost over vanilla | Smart Leaves > Fancy Leaves, fight me
| [Continuity](https://github.com/PepperCode1/Continuity) | [PepperCode1](https://github.com/PepperCode1) | Connected Blocks Textures support to work with Sodium | A replacement for [this ~~dead~~ unmaintained project](https://www.curseforge.com/minecraft/mc-mods/connected-block-textures)
| [Custom Entity Model](https://github.com/dorianpb/cem) | [dorianpb](https://github.com/dorianpb) | Supports loading custom models into the game, defined as `.jem` and .`jpm` in a resource pack | Straightforward, Hololive/Anime models as mobs/animals in Minecraft, y'all damn weebs
| [CITResewn](https://www.curseforge.com/minecraft/mc-mods/cit-resewn) | [SHsuperCM](https://github.com/SHsuperCM) | MCPatcher's CIT re-written outside of optifine as a standalone mod for Fabric | Minato Aqua 3D Totem Model do be looking cuteee aaaaa
| [Capes](https://github.com/CaelTheColher/Capes) | [CaelTheColher](https://github.com/CaelTheColher) | Loading any kind of capes ~~*including illegal ones*~~ for Fabric mod loader | "Ew Migrator cape, Optifine cape on the star" - Me using both capes smh
| [Animatica](https://github.com/FoundationGames/Animatica) | [FoundationGames](https://github.com/FoundationGames) | A Fabric mod intended to load the MCPatcher/OptiFine [animated texture format](https://github.com/sp614x/optifine/blob/master/OptiFineDoc/doc/custom_animations.txt) | Soooo, is this how that one dude made the S-Mod to come alive?
| [Lamb Dynamic Light](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights) | [LambdAurora](https://github.com/LambdAurora) | "Dynamic Light" settings to work with Sodium | What can this do? Holding an item will make the surroundings litted up, only for certain blocks/entity (on fire). Also sorry Lamb because I have done the [thing](https://cdn.discordapp.com/attachments/810700087054434358/941633402145214464/unknown.png) 😂
| [Lambda Better Grass](https://modrinth.com/mod/lambdabettergrass) | [LambdAurora](https://github.com/LambdAurora) | "Better Grass" option, cuzynot? | I found out that this mod only renders **Vanilla grass**, any custom grass textures will break the mod, even VanillaTweaks grass textures, to work like [this](https://github.com/LambdAurora/LambdaBetterGrass/issues/15)
| [Iris](https://github.com/IrisShaders/Iris) | [IrisShaders](https://github.com/IrisShaders) | Adds shaders support for Sodium and shader settings | ~~Canvas is no more relevant~~
____________
### Quality Of Life
| Name | Author | Description | Note |
| --- | ---- | ------------ | ----| 
| [Simple Armor HUD](https://github.com/LegoRaft/simple-armor-hud) | [LegoRaft](https://github.com/LegoRaft) | Adds a smol Armor HUD above your hunger bar, not configurable sadly | I'm sorry [Giselbaer](https://github.com/gbl) but your [DurabilityViewer](https://github.com/gbl/DurabilityViewer) decreased my FPS **by half**, maybe just your mod is badly optimized with too much unneccessary features. This replacement is actually somehow better, also works well and clean with [this](https://www.curseforge.com/minecraft/mc-mods/better-mount-hud)
| [Mouse Wheelie](https://github.com/Siphalor/mouse-wheelie) | [Siphalor](https://github.com/Siphalor) | Fancy inventory sorting stuff with your scroll wheel (Adds several mouse wheel related actions in gui menus like item scrolling and scrolling through tabs/pages) | The "refill" function might flags yourself as **Bad Packet** if you aren't careful so make sure to turn it off
| [MiniHUD](https://www.curseforge.com/minecraft/mc-mods/minihud) | [maruohon](https://github.com/maruohon) | Configurable *Mini-F3* with lots of cool features | Basically you have this, and you can preview a what-inside-a-shulker or a map (hold Shift while hovering a map) with this mod, cool right?
| [Hide Armor](https://www.curseforge.com/minecraft/mc-mods/hide-armor) | [Furgl](https://github.com/Furgl) | Hide your armor and/or other player's armor (in perspective) | Good for taking a group screenshot without have to take off the armor. [Funnier if you turn off the Chestplate while wearing an Elytra](https://cdn.discordapp.com/attachments/810700087054434358/941643112063860787/5nJWYjmlR.gif)
| [Autofish](https://www.curseforge.com/minecraft/mc-mods/autofish) | [MrTroot](https://github.com/MrTroot) | Let the game do the fishing for you while ~~jerking~~ chilling | Even the fishing is nerfed, you still can be really OP if you AFK Fishing for like 1-3 hours, unbalanced mod xD
*Updating more soon, im just busy and lazy rn sorry*
