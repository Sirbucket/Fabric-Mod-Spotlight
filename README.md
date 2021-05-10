# Fabric-Mod-Spotlight
List of mods that either improve the games performance, fix a bug without a large impact to gameplay, makes the game visually look better, or provide a QOL/mod compatability, mods that do what one mod does but better or has more features will override previous mods unless one has a feature that another does not have.

To test a mod for their performance impact, first download https://www.curseforge.com/minecraft/mc-mods/spark by lucko and profile the tickrate, framerate, memory usage change between vanilla minecraft (spark with fabric API) and that mod included.

This takes up a similar style to ReperakPro's list as I liked the style but did not like how mods were handled on the list, seemed slow and too restrictive for a showoff list.

Fabric API should be installed for support for mods and provides some minor fixes itself.

| Mod Name | Description | Credits (Link to credit page or main dev name) | Stable Mod (Non Experimental, Yes, No, Kind of, Mostly) | "Dangerous" (Impacts game behavior heavily or causes the game to simply not load or corrupt a world file.) | Incompatabilities (Mods on this page or off) | Mod Page (Curseforge, Github, Gitlab) |
|---|---|---|---|---|---|---|

## Graphics (Has to do with game rendering)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Sodium | GREATLY improves how minecraft is rendered on an optimization level | CaffieneMC/Jellysquid | Mostly | No | Any mod that uses the fabric rendering API | https://www.curseforge.com/minecraft/mc-mods/sodium |
| Canvas | A mod centered around improving how the game is rendered visually, not as focused on optimization as sodium but has features. | grondagthebarbarian | No | No | Sodium | https://www.curseforge.com/minecraft/mc-mods/canvas-renderer |

## Lighting and Animation (Lighting/Animation optimizations)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Phosphor | Computes light rendering faster than default. | CaffieneMC/Jellysquid | Yes | No | Starlight | https://www.curseforge.com/minecraft/mc-mods/phosphor |
| Starlight | Complete rewrite of minecraft lighting engine | Spottedleaf | No | No | Phosphor | https://github.com/Spottedleaf/Starlight

## Math (Computations)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Lithium | Improves the way minecraft is computed. | CaffieneMC/Jellysquid | Yes | No | Other computation mods that interact with the same code. | https://www.curseforge.com/minecraft/mc-mods/lithium |

## Network (Network stack improvement mods)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|

## Cache (Caching for things)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|

## Boot (Loading)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Pling | Plays a little noise to let you know the game is ready | haykam | Yes | No | Other mods with the same function I assume | https://www.curseforge.com/minecraft/mc-mods/pling |

## Particles (Reduces or optimizes particles)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Fat Experience Orbs | Combines smaller experience orbs into one big orb for easier collection and performance savings | NinjaPhenix | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/fat-experience-orbs |

## Visual improvement (Visual improvement mods, note some of these mods are taxing on your system and are marked with a ! for a bit taxing and a !!! for very taxing|
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

## Bugfix (Bug fix mods)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Auth Me | Fixes the minecraft error that forces you to restart your game due to an account verification failure | Axieum | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/auth-me |
| Dimension FIx | Fixes data pack dimensions being deleted causing the nether and end to be deleted as well. | shedaniel | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/dimension-fix-some-forge-patches-ported |
| Save My Stronghold | Fixes ravines and caves intersecting the stronghold and destroying part of it. | YUNGNICKYOUNG | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/save-my-stronghold-fabric |
| RandomPatches | Includes many bugfixes and optional additional features. | TheRandomLabs | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/randompatches-fabric |
| DamageTilt | Returns the damage tilt feature from 1.2.5 that got broken in 1.3.1, only works on singleplayer or servers with the mod. | Charles445 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/damage-tilt |

## Libraries (Libraries required by other mods on this list.)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|


## Extra (Doesn't fit into a specific category but does have one of the core functions)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
| Dynamic FPS | When minecraft is not the primary window, it stops rendering or renders at 1FPS | juliand665 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/dynamic-fps |
| Chunk Pregenerator | Pregenerates chunks in a radius around the player | SuperCoder79 | Yes | No | None | https://www.curseforge.com/minecraft/mc-mods/chunk-pregenerator-fabric |

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


## Compatability (Provides mod compatability and or development as well as it's own improvements.)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|

## QOL (Support for controllers, better sound changing etc.)
| Mod Name | Description | Credits | Stable Mod | "Dangerous" | Incompatabilities | Mod Page |
|---|---|---|---|---|---|---|
