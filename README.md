# Nathan's FriendPack

A lightweight quilt based modpack used by Nathan and his friends.

# How to Install

## PolyMC

You will want to use
[`packwiz-installer`](https://packwiz.infra.link/tutorials/installing/packwiz-installer/), I have
had too many issues with `.mrpack`, so I have stopped making it.

To setup this pack in PolyMC with auto-updating enable, do the following:

1. Create a new instance

   Press the "Add Instance" button, choose "Vanilla" in the left sidebar, then select "Quilt" in the
   Mod Loader menu. Use the latest quilt launcher available, `0.17.1-beta.2` at time of writing.

2. Install `packwiz-installer-bootstrap` in the instance minecraft folder

    Right click on the instance you just created and select "Minecraft Folder" to be taken to the
    instance minecraft folder. Download the latest
    [`packwiz-installer-bootstrap`](https://github.com/packwiz/packwiz-installer-bootstrap/releases)
    jar from its releases page, and then copy it into this directory.
    
3. Configure auto-updates

    Right Click on the instance -> Edit Instance, and select the "Settings" view.
    
    From there select the "Custom commands" tab, ensure the "Custom Commands" checkbock is selected,
    and type/paste the following into the "Pre-launch command" box:
    
    `"$INST_JAVA" -jar packwiz-installer-bootstrap.jar -server
    https://pack.forward-progress.net/0.3/pack.toml`
    
At this point, when you start the instance, it should automatically download the modpack, and it
will check for updates every time you start up the instance. You may need to restart minecraft once
after initial install for the mods to pick up.

If for some reason this does not work after a single restart, navigate to the instance minecraft
folder in a terminal, and run the above command manually in the direct, after deleting the `mods`
folder.


# Mods

## Libraries

  * [Quilt Standard Libraries](https://modrinth.com/mod/qsl) 
  * [Cloth Config API](https://modrinth.com/mod/cloth-config)
  * [Feature NBT Deadlock Be Gone](https://modrinth.com/mod/feature-nbt-deadlock-be-gone)
  * [Architectury](https://modrinth.com/mod/architectury-api)
  * [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin)
  * [Patchouli](https://modrinth.com/mod/patchouli)
  * [Dawn API](https://modrinth.com/mod/dawn)
  * [Meal API](https://modrinth.com/mod/mealapi)
  * [GeckoLib](https://www.curseforge.com/minecraft/mc-mods/geckolib)
  * [Trinkets](https://modrinth.com/mod/trinkets)
  * [Polymer](https://modrinth.com/mod/polymer)
  * [FTB Library](https://www.curseforge.com/minecraft/mc-mods/ftb-library-fabric)
  * [MidnightLib](https://www.curseforge.com/minecraft/mc-mods/midnightlib)
  * [PACUAL](https://www.curseforge.com/minecraft/mc-mods/paucal)
  * [Cardinal Components](https://www.curseforge.com/minecraft/mc-mods/cardinal-components)

## Optimization and Graphics

  * [Sodium](https://modrinth.com/mod/sodium)
  * [Sodium Extra](https://modrinth.com/mod/sodium-extra)
  * [Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options)
  * [Indium](https://modrinth.com/mod/indium)
  * [Lithium](https://modrinth.com/mod/lithium)
  * [Starlight](https://modrinth.com/mod/starlight)
  * [Iris Shaders](https://modrinth.com/mod/iris)
  * [FerriteCore](https://modrinth.com/mod/ferrite-core)
  * [DashLoader](https://modrinth.com/mod/dashloader)
  * [Concurrent Chunk Managment Engine](https://modrinth.com/mod/c2me-fabric)
  * [Alternate Current](https://modrinth.com/mod/alternate-current)
  * [ServerCore](https://modrinth.com/mod/servercore)
  * [Cull Less Leaves](https://modrinth.com/mod/cull-less-leaves)
  * [Debugify](https://modrinth.com/mod/debugify)
  
## World gen

  *  [Ecotones](https://github.com/SuperCoder7979/ecotones/tree/0.9.0)
  *  [Repurposed Structures](https://modrinth.com/mod/repurposed-structures-fabric)
  *  [Mo' Structures](https://modrinth.com/mod/mo-structures)
  *  [This Rocks!](https://modrinth.com/mod/this-rocks)
  *  [Universal Ores](https://modrinth.com/mod/universal_ores)
  *  [More Geodes](https://modrinth.com/mod/more-geodes)
  *  [Stoneholm](https://modrinth.com/mod/stoneholm)
  *  [Terralith](https://www.curseforge.com/minecraft/mc-mods/terralith)
  
## Building

  * [Oxidized](https://www.curseforge.com/minecraft/mc-mods/oxidized)
  * [Decorative](https://modrinth.com/mod/decorative)
  * [Dark Paintings](https://www.curseforge.com/minecraft/mc-mods/dark-paintings)
  * [Auroras Decorations](https://github.com/LambdAurora/AurorasDecorations)
  * [Bits And Chisels](https://modrinth.com/mod/bits-and-chisels)
  * [Architecture Extensions](https://modrinth.com/mod/arch-ex)
  * [Adorn](https://modrinth.com/mod/adorn)
  * [Campanion](https://modrinth.com/mod/campanion)
  * [MultiSlab](https://modrinth.com/mod/multislab)
  * [Armor Stand Editor](https://www.curseforge.com/minecraft/mc-mods/armor-stand-editor)
  * [PictureSign](https://modrinth.com/mod/picturesign)
  * [Half Doors](https://modrinth.com/mod/half-doors)
  * [Consistency+](https://modrinth.com/mod/consistencyplus)
  * [Soul Ice](https://modrinth.com/mod/soulice)
  * [ColoredWater](https://github.com/VictorKoenders/ColoredWaterMC)
  
## Food/Farming

  * [Culinaire](https://modrinth.com/mod/culinaire)
  * [Chocolate Bar](https://modrinth.com/mod/chocolate-bar)
  * [Milk+](https://modrinth.com/mod/milk_plus)
  * [Reaping](https://www.curseforge.com/minecraft/mc-mods/reaping)
  * [Overweight Farming](https://www.curseforge.com/minecraft/mc-mods/overweight-farming)
  * [Jamtastic](https://www.curseforge.com/minecraft/mc-mods/jamtastic)
  * [Bagel's Baking](https://modrinth.com/mod/bagels-baking)
  * [Sandwichable](https://modrinth.com/mod/sandwichable)
  * [Right-Click Harvest](https://modrinth.com/mod/right-click-harvest)
  * [Farmers Delight](https://www.curseforge.com/minecraft/mc-mods/farmers-delight-fabric)
  * [Expanded Delight](https://modrinth.com/mod/expanded-delight)
  
## Storage and Automation
  
  * [AE2](https://modrinth.com/mod/ae2)
  * [AE2 Things](https://modrinth.com/mod/ae2things)
  * [Simple Crates](https://modrinth.com/mod/simple-crates)
  * [Nether Chest](https://modrinth.com/mod/nether-chest)
  * [Modern Dynamics](https://modrinth.com/mod/modern-dynamics)
  * [cyperanner's Iron Chests](https://modrinth.com/mod/cyberanner-ironchest)
  * [Dank Storage](https://www.curseforge.com/minecraft/mc-mods/dank-storage-fabric)

## Technology

  *  [Purpeille](https://modrinth.com/mod/purpeille)
  *  [Tech Reborn](https://www.curseforge.com/minecraft/mc-mods/techreborn)
  *  [Botania](https://modrinth.com/mod/botania)
  *  [CC: Restitched](https://modrinth.com/mod/cc-restitched)
  *  [Create](https://modrinth.com/mod/create-fabric)
  *  [TaterCart](https://modrinth.com/mod/tatercart)
  *  [Extra Generators](https://modrinth.com/mod/extra-generators)
  *  [Experience Bottler](https://modrinth.com/mod/experience-bottler)
  *  [Logic Gates](https://modrinth.com/mod/logic-gates-fabric)
  *  [Mining Gadgets](https://modrinth.com/mod/mining-gadgets-fabric)
  *  [Scooters](https://modrinth.com/mod/scooters)
  *  [Wired Redstone](https://modrinth.com/mod/wiredredstone)
  
## Magic
  * [Malum](https://modrinth.com/mod/malum-quilt)
  * [Refined Magic](https://modrinth.com/mod/refmagic)
  * [Archon](https://www.curseforge.com/minecraft/mc-mods/archon)
  * [Hex Casting](https://www.curseforge.com/minecraft/mc-mods/hexcasting)
  
## Dimensions

  * [Mining Dimensions](https://www.curseforge.com/minecraft/mc-mods/mining-dimensions-fabric)
  
## Utility Items/Blocks

  * [Chalk](https://modrinth.com/mod/chalk)
  * [Additional Additions](https://modrinth.com/mod/addadd)
  * [Matchbox](https://modrinth.com/mod/matchbox)
  * [Soulbound](https://modrinth.com/mod/soulbound)
  
## Fun

  *  [Automobility](https://github.com/FoundationGames/Automobility)
  *  [Mbembe](https://www.curseforge.com/minecraft/mc-mods/mbembe)
  *  [Polaroid Camera](https://www.curseforge.com/minecraft/mc-mods/polaroid-camera)
  *  [Phonos](https://www.curseforge.com/minecraft/mc-mods/phonos)
  *  [Lovely Snails](https://modrinth.com/mod/lovely_snails)
  *  [Pettable Bees](https://modrinth.com/mod/pettable-bees-fabric)
  
## Utility

  * [Autokey](https://modrinth.com/mod/autokey)
  * [Chunky Pregenerator](https://modrinth.com/mod/chunky)
  * [EMI](https://modrinth.com/mod/emi)
  * [Ok Zoomer](https://modrinth.com/mod/ok-zoomer)
  * [AppleSkin](https://modrinth.com/mod/appleskin)
  * [WorldTime](https://modrinth.com/mod/worldtime)
  * [Xaero's Minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap)
  * [Xaero's World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map)
  * [Spark](https://modrinth.com/mod/spark)
  * [Jade](https://www.curseforge.com/minecraft/mc-mods/jade)
  * [Inspecio](https://modrinth.com/mod/inspecio)
  * [Mod Menu](https://modrinth.com/mod/modmenu)
  * [Easy Magic](https://www.curseforge.com/minecraft/mc-mods/easy-magic-fabric)
  * [ClickThrough](https://modrinth.com/mod/clickthrough)
  * [Mouse Wheelie](https://modrinth.com/mod/mouse-wheelie)
  * [Sort](https://modrinth.com/mod/sort)
  * [FTB Chunks](https://www.curseforge.com/minecraft/mc-mods/ftb-chunks-fabric)
  * [FTB Teams](https://www.curseforge.com/minecraft/mc-mods/ftb-teams-fabric)
  * [Litematica](https://www.curseforge.com/minecraft/mc-mods/litematica)
  * [Simple Veinminer](https://www.curseforge.com/minecraft/mc-mods/simple-veinminer)
  * [Universal Graves](https://modrinth.com/mod/universal-graves)
  
## Tweaks, Hacks, and Pure Cosmetics

  * [Bobby](https://modrinth.com/mod/bobby)
  * [Continuity](https://modrinth.com/mod/continuity)
  * [LambdaBetterGrass](https://modrinth.com/mod/lambdabettergrass)
  * [Quilt Loading Screen](https://modrinth.com/mod/quilt-loading-screen)
  * [AntiGhost](https://modrinth.com/mod/antighost)
  * [Falling Leaves](https://modrinth.com/mod/fallingleaves)
  * [Textile Backup](https://modrinth.com/mod/textile_backup)
  
