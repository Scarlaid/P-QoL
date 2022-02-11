# P-QoL
P-QoL, or in details, **Performance Quality-Of-Life** (yeah it's a weird name), is a simple modpack for people who have the curiousity of pushing the boundary of **Minecraft optimization** but also keeping the Quality-Of-Life vibes throughout the gameplay, as well as a starting point for any new Fabric users who are willing to see what equivalents Fabric has to offer to them (or somehow change their view about using Optifine and shift to Sodium)

> Simple definition for this modpack is making your gameplay more ideal, have the fancy view while still having the performance you want.
# Before installing the modpack
This modpack were made just for my personal use only, it might break some functions in Minecraft, I won't guarantee this mod **100% stable**, so any problems you have while running the modpack, please make [a new issue](https://github.com/Scarlaid/P-QoL/issues) and I try to response as soon as possible :D
### Suggested by [this dude](https://discord.com/users/437854007181049866) to make a GitHub Repo lol
![image](https://user-images.githubusercontent.com/90851437/153533331-5ae0d7c2-481a-427d-8759-23b22a5b24b0.png)
# Included mods
This modpack was inspired from this [list of Optifine alternatives](lambdaurora.dev/optifine_alternatives/),  but it's doesn't mean it will stop there.
Here you can find the mods with any little detail about each of them, keep in mind that I only make this modpack for **only 1.18.1** so if you came for modpacks that supports lower than 1.18, this is not the place.
### Perfromance
| Name | Author | Description | Note |
| ------------- | ------------- | ------------ | ------------| 
| [Sodium](https://github.com/CaffeineMC/sodium-fabric/releases) | [CaffeinMC](https://github.com/CaffeineMC) | Optimization mod for the Minecraft client that improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft, as well as adds some graphics options | Doesn't have **all** the settings like Optifine |
| [Lithium](https://github.com/CaffeineMC/lithium-fabric) | [CaffeinMC](https://github.com/CaffeineMC) | A mod which works to optimize many areas of the game in order to provide better overall performance | Works good for both for **client** and (or) **server**
| [Hydrogen](https://github.com/CaffeineMC/hydrogen-fabric) | [CaffeinMC](https://github.com/CaffeineMC) | Reduce the game's memory requirements by implementing more memory-efficient data structures and logic | Works good for both for **client** and (or) **server**, might break some mods that you willing to have in Singleplayer
| [FerritCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric) | [malte0811](https://github.com/malte0811) | Reduce the game's memory requirements | [Here is the detailed decription](https://github.com/malte0811/FerriteCore/blob/1.18/summary.md)
| [Starlight](https://github.com/PaperMC/Starlight) | [PaperMC](https://github.com/PaperMC) | Fabric mod for completely rewriting the Vanilla light engine | Incompatible with [Phosphor](https://github.com/CaffeineMC/phosphor-fabric), but a payback, better performance
| [C2ME](https://github.com/RelativityMC/C2ME-fabric) | [RelativityMC](https://github.com/RelativityMC) | C^2M-Engine, or C2ME for short, is a Fabric mod designed to improve the performance of chunk generation, I/O, and loading. This is done by taking advantage of multiple CPU cores in parallel | Might be unstable for most Onboard GPU because of the intensive this mod offers
| [LazyDFU](https://github.com/astei/lazydfu) | [astei](https://github.com/astei) | Optimization mod that makes the initialization of DataFixerUpper "more lazy" - that is, it will not immediately create the rules required to migrate data from older versions of Minecraft to newer versions until it actually needs to do so | |
| [Smooth Boot](https://github.com/UltimateBoomer/mc-smoothboot) | [UltimateBoomer](https://github.com/UltimateBoomer) | Improve and tweak Minecraft CPU scheduling | The config file is in `config.json` so you might need [this](https://code.visualstudio.com)
| [Krypton](https://github.com/astei/krypton) | [astei](https://github.com/astei) | Fabric mod that attempts to optimize the Minecraft networking stack | No little performance notice in multiplayer but you might see them more in Singleplayer while opening a LAN server
| [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader) | [QuantumFusion](https://github.com/QuantumFusionMC) | This mod improves Minecraft client asset loading times about 6x by caching all of the game's content | **100% Multi-threaded**, kinda unstable for rendering texture that you might encounter [this](https://github.com/QuantumFusionMC/DashLoader-Definitions/issues/1)
__________
### Smooth-*ish* (?)
| Name | Author | Description | Note |
| --- | ---- | ------------ | ----| 
| [NoFade](https://github.com/UltimateBoomer/mc-no-fade) | [UltimateBoomer](https://github.com/UltimateBoomer) | Removes all the *annoying* fade-out animations in Minecraft | :poggers:
| [Language Reload](https://github.com/Jerozgen/LanguageReload) | [Jerozgen](https://github.com/Jerozgen) | Fabric mod that reloads languages without resource pack reloading using F3 + J | Might break with [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader), at least for me, once
| [FastOpenL&F](https://github.com/altrisi/FastOpenLinksAndFolders) | [astei](https://github.com/astei) | A lightweight mod to make the game not freeze when opening a chat link, a screenshot or either the resourcepacks or datapacks folder | |
| [NoChatLag](https://github.com/NoahvdAa/NoChatLag) | [NoahvdAa](https://github.com/NoahvdAa) | Rendering the ingame chat in another thread to improve the gameplay by not rendering the chat on the same thread Minecraft running | I'm not sure [v1.1.0](https://github.com/NoahvdAa/NoChatLag/releases/tag/1.1.0) changed anything, but for now the modpack still sticking with [v1.0.0](https://github.com/NoahvdAa/NoChatLag/releases/tag/1.0.0) because it's stable enough
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | [jaredlll08](https://github.com/jaredlll08) |  Groups XP orbs together into a single entity to reduce lag when there are many in a small area, also giving the player collecting all the orbs immediately | |
| [FastChest](https://www.curseforge.com/minecraft/mc-mods/fastchest) | [FakeDomi](https://github.com/FakeDomi) | Removing dynamic models from chests and making them render as static chunk geometry, make chest rendering less **intense** in a wide area with a lot of filled chests | This mod will make the chest no more have the opening/closing animation, which might annoy you. [For troubleshooting the chests (any chest) textures being invisisble](https://github.com/FakeDomi/FastChest/issues/10)
| [Enhanced Blocks Entities](https://www.curseforge.com/minecraft/mc-mods/enhanced-block-entities) | [FoundationGames](https://github.com/FoundationGames) | A Fabric mod which aims to increase the performance of block entity rendering, as well as offer customizability via resource packs | Incompatible with DashLoader at the moment with double chest texture being [*cursed*](https://github.com/FoundationGames/EnhancedBlockEntities/issues/71)
| [Better Beds](https://www.curseforge.com/minecraft/mc-mods/better-beds) | [TeamMidnightDust](https://github.com/TeamMidnightDust) | Removes the BlockEntityRenderer from the bed and replaces it with the default minecraft model renderer | You might facing very little **half-of-a-bed** issue when placing down a bed
______
### Fixes/Patches
| Name | Author | Description | Note |
| --- | ---- | ------------ | ----| 
| [TieFix](https://github.com/j-tai/TieFix) | [j-tai](https://github.com/j-tai) | A Fabric mod that fixes some annoying bugs in the Minecraft client | Toggable if you feel like those **patches** was intentional for the game to function
_______
### Optifine Alternatives
| Name | Author | Description | Note |
| --- | ---- | ------------ | ----| 
| 
*Updating more soon, im just lazy right now lol*
