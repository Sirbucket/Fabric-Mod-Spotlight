# Fabric-Mod-Spotlight
List of mods that either improve the games performance, fix a bug without a large impact to gameplay, makes the game visually look better, or provide a QOL/mod compatability, mods that do what one mod does but better or has more features will override previous mods unless one has a feature that another does not have.

To test a mod for their performance impact, first download https://www.curseforge.com/minecraft/mc-mods/spark by lucko and profile the tickrate, framerate, memory usage change between vanilla minecraft (spark with fabric API) and that mod included.

This takes up a similar style to ReperakPro's list as I liked the style but did not like how mods were handled on the list, seemed slow and too restrictive for a showoff list.

Fabric API should be installed for support for mods and provides some minor fixes itself.

| Mod Name | Description | Credits (Link to credit page or main dev name) | Stable Mod (Non Experimental, Yes, No, Kind of, Mostly) | "Dangerous" (Impacts game behavior heavily or causes the game to simply not load or corrupt a world file.) | Incompatabilities (Mods on this page or off) | Mod Page (Curseforge, Modrinth, Github, Gitlab) |
|---|---|---|---|---|---|---|

## Graphics (Has to do with game rendering)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Sodium | GREATLY improves how minecraft is rendered on an optimization level | CaffieneMC/Jellysquid | Mostly | No | Any mod that uses the fabric rendering API | https://www.curseforge.com/minecraft/mc-mods/sodium |
| Canvas | A mod centered around improving how the game is rendered visually, not as focused on optimization as sodium but has features. | grondagthebarbarian | No | No | Sodium | https://www.curseforge.com/minecraft/mc-mods/canvas-renderer |
| Entity Culling | Performs entity culling at a rate greater than sodium providing greater performance. | tr9zw | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/entityculling |
| Sodium Extra | Sodium extras like disabling animations. | FlashyReese | Yes | No | Lack of sodium | https://www.curseforge.com/minecraft/mc-mods/sodium-extra |
| Cull Leaves | Smart leaves for fabric. | Motschen | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/cull-leaves |
| Better Beds | Uses the new item render system for beds rather than the old one. | Motschen | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/better-beds |


## Lighting (Lighting optimizations)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Phosphor | Computes light rendering faster than default. | CaffieneMC/Jellysquid | Yes | No | Starlight | https://www.curseforge.com/minecraft/mc-mods/phosphor |
| Starlight | Complete rewrite of minecraft lighting engine | Spottedleaf | No | No | Phosphor | https://github.com/Spottedleaf/Starlight

## Math (Computations)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Lithium | Improves the way minecraft is computed. | CaffieneMC/Jellysquid | Yes | No | Other computation mods that interact with the same code. | https://www.curseforge.com/minecraft/mc-mods/lithium |
| Hydrogen | Basically Lithium on steroids that sometimes breaks but is mostly stable, but just not to the same standard as lithium, works with lithium. | CaffieneMC/Jellysquid | Kind of | No | None | https://github.com/CaffeineMC/hydrogen-fabric |

## Cache (Caching for things)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Recipe Cache | Basically combines fast furnace and fast bench into one mod. | biom4st3r1 | Yes | No | Fast Furnace Fast Bench| https://www.curseforge.com/minecraft/mc-mods/recipe-cache |
| EBE | Bakes chest animation reducing lag from chests significantly and provides support to do the same thing with other animations. | FoundationGames | Yes | No | Sodium (Patched version available on mod page | https://www.curseforge.com/minecraft/mc-mods/enhanced-block-entities |
| DashLoader | Caches block data on the first launch of the game and saves it for the next time the game boots. | notequalalpha | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/dashloader |

## Boot (Loading)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Pling | Plays a little noise to let you know the game is ready | haykam | Yes | No | Other mods with the same function I assume | https://www.curseforge.com/minecraft/mc-mods/pling |
| Lazy DFU | Delays DFU being handled causing reduced CPU usage and nullifying the usefulness of smooth boot | tuxed | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/lazydfu |
| No Fade | Removes the fade animations allowing you to get into the action faster or just remove an annoying animation. | UltimateBoomer | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/no-fade |


## Particles (Reduces or optimizes particles)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Fat Experience Orbs | Combines smaller experience orbs into one big orb for easier collection and performance savings | NinjaPhenix | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/fat-experience-orbs |
| No Weather Effects | Removes the weather effects from the game without stopping their functionality, providing a performance boost. | Lortseam_ | Yes | No | Mods that change the particles in weather. | https://www.curseforge.com/minecraft/mc-mods/no-weather-effects |
| Smoke Suppression | Makes blocks common in farms block camp fires from producing smoke, saving performance. | muteone2 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/smoke-suppression |
| No Beacon Beams | Removes beacon beams, saving performance, functions the same. | colderlavalamp | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/no-beacon-beams |

## Visual improvement (Visual improvement mods, note some of these mods are taxing on your system and are marked with a ! for a bit taxing and a !!! for very taxing.
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| !!!Immersive Portals | Removes the loading screen between going through the nether and removes the actual portal, making it a walkthrough experience. | qouteall | Yes | No | Sodium by default (Patched version on mod page.) | https://www.curseforge.com/minecraft/mc-mods/immersive-portals-mod|
| Better Biome Blend | Optimizes the biome blending algorithm and allows up to 29x29 | FionaTheMortal | Yes | No | Sodium | https://www.curseforge.com/minecraft/mc-mods/better-biome-blend |
| !!!Physics Mod | Adds Physics to minecraft in the form of ragdolls and ground left after destroying a block | haubna | Mostly | No | None (Doesn't work on modded mobs and blocks unless coded) | https://www.curseforge.com/minecraft/mc-mods/physics-mod |
| Better Third Person | Gives greater control of the third person camera | Socolio & DreenDexTwitch | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/better-third-person |
| !Better Dropped Items | Makes dropped items have physics | Draylar1 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/better-dropped-items |
| !Illuminations | Adds particles that make the world feel more alive, pairs excellently with Canvas providing bloom. | doctor4t | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/illuminations |
| !LambDynamicLights| Adds dynamic lighting to minecraft, lags a bit with Canvas but looks good. | LambdAurora | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights |
| Not Enough Animations | Adds first person animations to the third person viewport, pairs well with Better Third Person and First-person Model. | tr9zw | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/not-enough-animations |
| First-person Model | Adds the third person model to the first person. | tr9zw | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/first-person-model |
| Blur | Adds a gaussian blur to menus. | Motschen & PyrofabTheModsmith | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/blur-fabric |
| Dynamic Sound Filters | Adds sound filters depending on position in the world | andre111_ | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/dynamic-sound-filters |
| Clear Skies | Changes fog color to match the sky (unrealistic) | grondagthebarbarian | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/clear-skies |
| !Falling Leaves | Adds falling leaf particles come from leaf blocks. | RandomMcSomethin | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/falling-leaves-fabric |
| LambdaBetterGrass | Better grass for fabric | LambdAurora | Yes | No | Sodium | https://www.curseforge.com/minecraft/mc-mods/lambdabettergrass |
| !Visual Overhaul | Adds animations to some blocks. | Motschen | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/visual-overhaul |
| Clear Despawn | Adds a despawning flash to alert you when items are close to despawning | Giselbaer | Yes | No | Better Dropped Items | https://www.curseforge.com/minecraft/mc-mods/clear-despawn-fabric |
| Damage Tint | Adds a red vignette to you when low on HP or upon being damaged | DeadlyMC_ | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/damage-tint |
| !Particle Rain | Replaces default rain with a particle effect and makes the desert cause a sandstorm effect when raining. | PigCart | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/particle-rain |
| Fade In Chunks | Adds bedrock style chunk fade in. | Johni0702 | Yes | No | Requires sodium | https://www.curseforge.com/minecraft/mc-mods/fade-in-chunks |
| Custom Selection Box | Customize the selection box around blocks | shedaniel | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/custom-selection-box-port |
| Low Fire | Lowers fire for better visibility | UltimateBoomer | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/low-fire |
| BedrockWaters | Adds bedrock water variety. | 2retr0 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/bedrockwaters |
| FabricSkyboxes | Adds custom skybox support. | AMereBagatelle | Yes | No | None | https://modrinth.com/mod/fabricskyboxes |
| Time Changer | Allows you to change the time for yourself and not the server. | Motschen | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/time-changer |
| Boring Tweaks | Adds a bunch of random tweaks that mostly don't effect gameplay in a meaningful way (clientside). | boredomh1 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/boring-tweaks |
| ResolutionControl+ | Allows for anti aliasing or reducing graphics for greater performance and allows you to configure screenshot size. | UltimateBoomer | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/resolutioncontrol |
| !Smoke Extender | Makes smoke go higher into the air. | AfterRebelion | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/smoke-extender |
| Sneak Tweak | Makes sneak smooth animation duration configurable or disables it. | Lortseam_ | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/sneak-tweak |
| Drip Sounds | Adds water drip sounds to rain that falls. | PieKing1215 | Yes | No | Maybe particle rain. | https://www.curseforge.com/minecraft/mc-mods/dripsounds-fabric |

## Bugfix (Bug fix mods)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Auth Me | Fixes the minecraft error that forces you to restart your game due to an account verification failure | Axieum | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/auth-me |
| Dimension FIx | Fixes data pack dimensions being deleted causing the nether and end to be deleted as well. | shedaniel | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/dimension-fix-some-forge-patches-ported |
| Save My Stronghold | Fixes ravines and caves intersecting the stronghold and destroying part of it. | YUNGNICKYOUNG | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/save-my-stronghold-fabric |
| RandomPatches | Includes many bugfixes and optional additional features. | TheRandomLabs | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/randompatches-fabric |
| DamageTilt | Returns the damage tilt feature from 1.2.5 that got broken in 1.3.1, only works on singleplayer or servers with the mod. | Charles445 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/damage-tilt |
| AntiGhost | Adds a command and keybind to remove ghost blocks around the player | Giselbaer | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/antighost |
| Fabrication | Adds a lot of bug fixes and optionally extra game content that's vanilla friendly. | unascribed | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/fabrication | 
| Item Model Fix | Removes the weird seams on some items with a performance friendly method. | Pepper_Bell | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/item-model-fix |
| Colormatic | Removes hard coded colors so resource packs can change things beyond textures. | kwertiTheCats | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/colormatic |
| ToolTipFix | Fixes long tooltips going off screen. | Kyrptonaught | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/tooltipfix |
| Giant AI | Adds an AI to the giants (I assume this is a bug so I'm adding this here.) and adds them into the spawn pool on a rare occurence. (Can be disabled.) | Flytre7 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/giant-ai |
| Why Am I on Fire? | Removes the fire overlay with fire res and in creative mode. | Ellivers | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/why-am-i-on-fire |
| Dispenser Portal Fix | Fixes the bug that causes face down dispensers lighting a nether portal to crash your game. | haykam | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/dispenser-portal-fix |

## Libraries (Libraries required by other mods on this list.)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| TRansliterationLib | Library for tr9zws mods. | tr9zw | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/transliterationlib |
| Fabric Language Kotlin | Adds Kotlin to minecraft. | modmuss50 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin |
| Fabric API | Fabric API | https://www.curseforge.com/minecraft/mc-mods/fabric-api |

## Extra (Doesn't fit into a specific category but does have one of the core functions)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Dynamic FPS | When minecraft is not the primary window, it stops rendering or renders at 1FPS | juliand665 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/dynamic-fps |
| Chunk Pregenerator | Pregenerates chunks in a radius around the player | SuperCoder79 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/chunk-pregenerator-fabric |
| Not Enough Crashes | Lets you keep playing if the game were to crash. | NatanFudge | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes |
| Carpet |Adds some functionality from bedrock (Moveable tile entities) and more. | gnembon | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/carpet |
| Borderless Mining | Converts fullscreen to borderless window for improved alt tab functionality. | comp500 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/borderless-mining |

## GUI (UI Mods)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Appleskin | Shows food saturation and food data on tooltip. | squeek502 | Yes | No | None (actually supports a large variety of texture packs) | https://www.curseforge.com/minecraft/mc-mods/appleskin
| Hwyla | Shows block data and status on a seperate tooltip. | TehNut | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/hwyla |
| Light Overlay | Shows light level on blocks around the player. | shedaniel | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/light-overlay |
| Mod Menu | Puts the mod configs into a in game UI center similar to forge. | Terraformers (ProspectorDev)| Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/modmenu |
| ToroHealth Damage Indicators | Shows a damage number when you injure a mob. | Torocraft | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/torohealth-damage-indicators |
| REI | Creative inventory view+ for survival to view crafting recipes without the wiki or in game inventory view and to be a creative inventory/give simplifier to give items with cheats on. | shedaniel | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items |
| Name Pain | Customizable Nametags | naqaden | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/name-pain |
| ShulkerBoxTooltip | Shows the contents of your shulkerbox in a tooltip | MisterPeModder | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/shulkerboxtooltip |
| 'Slight' Gui Modifications | Improves the default game UI and adds customization | shedaniel | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/slight-gui-modifications |
| BetterF3 | Improves the debug menu | cominixo | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/betterf3 |
| Health Overlay | Causes hearts over 10 to change the color of the bar rather than add a new row | Terrails | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/health-overlay-fabric |
| Giselbaer's Durability Viewer | Durability Bar for items in your inventory. | Giselbaer | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/giselbaers-durability-viewer |
| Notes | In game notepad on a by world basis. | reeve567 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/notes-fabric |
| No Angled Brackets | Removes brackets from player names in chat | Flytre7 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/no-angled-brackets |
| Chat Heads | Adds the players front face on their skin to chat, looks appealing. | dzwdz | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/chat-heads |
| FancyMenu | Lets you add animations to the loading screen and a background. | Keksuccino | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/fancymenu-fabric |
| Ugly Scoreboard Fix | Removes numbers on the side of the scoreboard. | Lortseam_ | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/ugly-scoreboard-fix |
| Better World List | Adds a grid layout for world select. | YanisBft | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/better-world-list |
| Better Mount HUD | Properly displays all elements of the HUD while on a mount. | Lortseam_ | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/better-mount-hud |
| Splash | Uses hexcode to color loading screen. | LoganDark | Yes | No | Requires Kotlin | https://www.curseforge.com/minecraft/mc-mods/splash |
| Clear Hitboxes | Cleans up F3 + B | splzhh | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/clear-hitboxes |

## QOL (Support for controllers, better sound changing etc.)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Convenient mobGreifing | Splits the mobGriefing gamerule into 4, one for hostiles, one for passive mobs, one for the wither, and one for the ender dragon. | Neecko5b84 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/convenient-mobgriefing |
| Audio Output | Adds the option to swap the audio output from a menu. | Maximumgame | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/audio-output | Music Duration Reducer | Makes dynamic music changes that don't immediately interupt music and reduces time betwee songs. | LudoCrypt | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/music-duration-reducer |
| LambdaControls | Adds improved controller support and experimental touchscreen support to java. | LambdAurora | Mostly | No | None | https://www.curseforge.com/minecraft/mc-mods/lambdacontrols |
| Command Macros | Bind a command to a keybind. | Kyrptonaught | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/command-macros |
| AutoReconnect | Reconnects automatically upon being kicked or a server crashes. | bstn02 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/autoreconnect |
| Continue Button | Adds a continue button for the last world you were on on the main menu | umollu | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/continue-button |
| Better Local Server | Adds similar functionality to bedrock local servers. | rederpz | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/better-local-server |
| Disable Custom Worlds Advice | Removes the annoying experimental settings label when using mods. | rdvdev2 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/fabric-disable-custom-worlds-advice |
| Helpful Hitboxes | Adds similar placement strategies scaffolding uses to other blocks. | abigailfails | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/helpful-hitboxes-fabric |
| Steelseries Gamesense | Steelseries lights support. | JayJay1989BE | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/steelseries-gamesense-fabric |

## Networking (Net stack improvements )
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Krypton | Networking improvements | tuxed | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/krypton |
| Client Side Noteblocks | Makes sounds played by noteblocks clientside, greatly reducing lag generated for the end user of this mod (can even help on singleplayer). | DaCubeKing | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/client-side-noteblocks |

## Up and Coming (1.17 mods or unfinished but incoming mods )
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Underground Ambient Light | Improves visibility underground without nulifying the use of torches. | andantet | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/undergroundambientlighting |
| !!!WorldHeightBooster | 512 world blocks from up and down, even larger. | soapyxm | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/worldheightbooster |
| All Dimension Height Increase | Increases the build limit within the end and nether as well, does not effect terrain generation. | colderlavalamp | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/all-dimension-height-increase |
