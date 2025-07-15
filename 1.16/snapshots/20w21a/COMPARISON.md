## Comparison with [20w20b](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w20b)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">20w20b</th><th>20w21a</th></tr><tr><td>World version</td><td><pre>2537</pre></td><td><pre>2554</pre></td></tr><tr><td>Protocol version</td><td><pre>717</pre></td><td><pre>718</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w20b</th><th>20w21a</th></tr><tr><td>com.mojang:datafixerupper</td><td><pre>2.0.24</pre></td><td><pre>3.0.25</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- biome_source_type.txt
+ biome_source.txt
+ chunk_generator.txt
- dimension_type.txt
```

</details>
<details>
<summary>
block_state_provider_type
</summary>

```diff
+ minecraft:rotated_block_provider
```

</details>
<details>
<summary>
feature
</summary>

```diff
- minecraft:bastion_remnant
- minecraft:buried_treasure
- minecraft:desert_pyramid
- minecraft:end_city
- minecraft:igloo
- minecraft:jungle_temple
- minecraft:mineshaft
- minecraft:nether_bridge
- minecraft:nether_fossil
- minecraft:ocean_monument
- minecraft:ocean_ruin
- minecraft:pillager_outpost
- minecraft:ruined_portal
- minecraft:shipwreck
- minecraft:stronghold
- minecraft:swamp_hut
- minecraft:village
- minecraft:woodland_mansion
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.donkey.eat
+ minecraft:entity.fox.teleport
+ minecraft:entity.mule.angry
+ minecraft:entity.mule.eat
+ minecraft:entity.parrot.imitate.hoglin
+ minecraft:entity.parrot.imitate.piglin
+ minecraft:entity.parrot.imitate.zoglin
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- universal_tags/biome_source_type.json
+ universal_tags/biome_source.json
+ universal_tags/chunk_generator.json
- universal_tags/dimension_type.json
```

</details>
<details>
<summary>
universal_tags/block_state_provider_type.json
</summary>

```diff
+ minecraft:rotated_block_provider
```

</details>
<details>
<summary>
universal_tags/feature.json
</summary>

```diff
- minecraft:bastion_remnant
- minecraft:buried_treasure
- minecraft:desert_pyramid
- minecraft:end_city
- minecraft:igloo
- minecraft:jungle_temple
- minecraft:mineshaft
- minecraft:nether_bridge
- minecraft:nether_fossil
- minecraft:ocean_monument
- minecraft:ocean_ruin
- minecraft:pillager_outpost
- minecraft:ruined_portal
- minecraft:shipwreck
- minecraft:stronghold
- minecraft:swamp_hut
- minecraft:village
- minecraft:woodland_mansion
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.donkey.eat
+ minecraft:entity.fox.teleport
+ minecraft:entity.mule.angry
+ minecraft:entity.mule.eat
+ minecraft:entity.parrot.imitate.hoglin
+ minecraft:entity.parrot.imitate.piglin
+ minecraft:entity.parrot.imitate.zoglin
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
locate
</summary>

```diff
+ locate bastion_remnant
- locate Bastion_Remnant
+ locate buried_treasure
- locate Buried_Treasure
+ locate desert_pyramid
- locate Desert_Pyramid
+ locate endcity
- locate EndCity
+ locate fortress
- locate Fortress
+ locate igloo
- locate Igloo
+ locate jungle_pyramid
- locate Jungle_Pyramid
+ locate mansion
- locate Mansion
+ locate mineshaft
- locate Mineshaft
+ locate monument
- locate Monument
+ locate nether_fossil
- locate Nether_Fossil
+ locate ocean_ruin
- locate Ocean_Ruin
+ locate pillager_outpost
- locate Pillager_Outpost
+ locate ruined_portal
- locate Ruined_Portal
+ locate shipwreck
- locate Shipwreck
+ locate stronghold
- locate Stronghold
+ locate swamp_hut
- locate Swamp_Hut
+ locate village
- locate Village
```

</details>
<details>
<summary>
spreadplayers
</summary>

```diff
+ spreadplayers <center: vec2> <spreadDistance: float> <maxRange: float> under <maxHeight: integer> <respectTeams: bool> <targets: entity>
```

</details>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
- createWorld.customize.buffet.generator: Please select a generator type
- createWorld.customize.buffet.generatortype: World generator:
- generator.buffet: Buffet
+ generator.custom: Custom
+ generator.large_biomes: Large Biomes
- generator.largeBiomes: Large Biomes
- generator.minecraft.caves: Caves
- generator.minecraft.floating_islands: Floating Islands
- generator.minecraft.surface: Surface
+ generator.single_biome_caves: Caves
+ generator.single_biome_floating_islands: Floating islands
+ generator.single_biome_surface: Single Biome
+ selectWorld.backupQuestion.experimental: Worlds using Experimental Settings are not supported
+ selectWorld.backupWarning.experimental: This world uses experimental settings that could stop working at any time. We cannot guarantee it will load or work. Here be dragons!
+ selectWorld.edit.export_worldgen_settings: Export World Generation Settings
+ selectWorld.edit.export_worldgen_settings.failure: Export failed
+ selectWorld.edit.export_worldgen_settings.success: Exported
+ selectWorld.import_worldgen_settings: Import settings
+ selectWorld.import_worldgen_settings.deprecated.question: Some features used are deprecated and will stop working in the future. Do you wish to proceed?
+ selectWorld.import_worldgen_settings.deprecated.title: Warning! These settings are using deprecated features
+ selectWorld.import_worldgen_settings.experimental.question: These settings are experimental and could one day stop working. Do you wish to proceed?
+ selectWorld.import_worldgen_settings.experimental.title: Warning! These settings are using experimental features
+ selectWorld.import_worldgen_settings.failure: Error importing settings
+ selectWorld.import_worldgen_settings.select_file: Select settings file (.json)
+ selectWorld.tooltip.experimental: This world is using experimental settings
+ subtitles.block.portal.travel: Portal noise fades
+ subtitles.block.portal.trigger: Portal noise intensifies
+ subtitles.entity.cat.purr: Cat purrs
+ subtitles.entity.donkey.eat: Donkey eats
+ subtitles.entity.fox.teleport: Fox teleports
- subtitles.entity.horse.land: Horse lands
+ subtitles.entity.mule.angry: Mule neighs
+ subtitles.entity.mule.eat: Mule eats
+ subtitles.entity.parrot.imitate.hoglin: Parrot growls
+ subtitles.entity.parrot.imitate.piglin: Parrot snorts
+ subtitles.entity.parrot.imitate.zoglin: Parrot growls
+ subtitles.entity.zombie.attack_wooden_door: Door shakes
+ subtitles.entity.zombie.break_wooden_door: Door breaks
+ subtitles.ui.cartography_table.take_result: Map drawn
+ subtitles.ui.loom.take_result: Loom used
+ subtitles.ui.stonecutter.take_result: Stonecutter used
+ title.multiplayer.disabled: Multiplayer is disabled, please check your launcher settings.
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>20w20b</th><th>20w21a</th></tr>
<tr><th align="left"><div style="width:290px">generator.customized</div></th><td>Customized</td><td>Old Customized</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.blastfurnace.fire_crackle</div></th><td>Blast furnace crackles</td><td>Blast Furnace crackles</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.enchantment_table.use</div></th><td>Enchanting table used</td><td>Enchanting Table used</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.respawn_anchor.charge</div></th><td>Respawn anchor is charged</td><td>Respawn Anchor is charged</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.respawn_anchor.deplete</div></th><td>Respawn anchor depletes</td><td>Respawn Anchor depletes</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.respawn_anchor.set_spawn</div></th><td>Respawn anchor sets spawn</td><td>Respawn Anchor sets spawn</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.turtle.egg_break</div></th><td>Turtle egg breaks</td><td>Turtle Egg breaks</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.turtle.egg_crack</div></th><td>Turtle egg cracks</td><td>Turtle Egg cracks</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.turtle.egg_hatch</div></th><td>Turtle egg hatches</td><td>Turtle Egg hatches</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombie_villager.converted</div></th><td>Zombie vociferates</td><td>Zombie Villager vociferates</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombie_villager.cure</div></th><td>Zombie snuffles</td><td>Zombie Villager snuffles</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/gui/title/mojang.png
+ minecraft/textures/gui/title/mojangstudios.png
+ minecraft/textures/item/nether_sprouts.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.package-info
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeMap
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.attributes.Attributes
+ XXX.ai.attributes.AttributeSupplier
- XXX.ai.attributes.AttributeSupplier$Builder
- XXX.ai.attributes.DefaultAttributes
- XXX.ai.attributes.package-info
+ XXX.ai.attributes.RangedAttribute
+ XXX.ai.behavior.AcquirePoi
- XXX.ai.behavior.AnimalMakeLove
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.BackUpIfTooClose
+ XXX.ai.behavior.BecomePassiveIfMemoryPresent
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosTracker
- XXX.ai.behavior.CelebrateVillagersSurvivedRaid
+ XXX.ai.behavior.CopyMemoryWithExpiry
- XXX.ai.behavior.CrossbowAttack
+ XXX.ai.behavior.CrossbowAttack$CrossbowState
- XXX.ai.behavior.DismountOrSkipMounting
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityTracker
+ XXX.ai.behavior.EraseMemoryIf
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$1
- XXX.ai.behavior.GateBehavior$OrderPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy$1
+ XXX.ai.behavior.GateBehavior$RunningPolicy$2
- XXX.ai.behavior.GiveGiftToHero
+ XXX.ai.behavior.GoOutsideToCelebrate
- XXX.ai.behavior.GoToCelebrateLocation
+ XXX.ai.behavior.GoToClosestVillage
- XXX.ai.behavior.GoToWantedItem
+ XXX.ai.behavior.HarvestFarmland
- XXX.ai.behavior.InsideBrownianWalk
+ XXX.ai.behavior.InteractWith
- XXX.ai.behavior.InteractWithDoor
+ XXX.ai.behavior.JumpOnBed
- XXX.ai.behavior.LocateHidingPlace
+ XXX.ai.behavior.LocateHidingPlaceDuringRaid
- XXX.ai.behavior.LookAndFollowTradingPlayerSink
+ XXX.ai.behavior.LookAtTargetSink
- XXX.ai.behavior.MeleeAttack
+ XXX.ai.behavior.Mount
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.PlayTagWithOtherKids
+ XXX.ai.behavior.PositionTracker
- XXX.ai.behavior.RandomStroll
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunIf
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.RunSometimes
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFrom
- XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ XXX.ai.behavior.SetWalkTargetFromBlockMemory
- XXX.ai.behavior.SetWalkTargetFromLookTarget
+ XXX.ai.behavior.ShowTradesToPlayer
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerMakeLove
+ XXX.ai.behavior.VillagerPanicTrigger
- XXX.ai.behavior.WakeUp
+ XXX.ai.behavior.WeightedList
- XXX.ai.behavior.WeightedList$1
+ XXX.ai.behavior.WeightedList$WeightedEntry
- XXX.ai.behavior.WeightedList$WeightedEntry$1
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$1
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JigsawBlockEntity$RuntimePiece
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickableBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
+ XXX.block.state.AbstractStateHolder$1
- XXX.block.state.BlockBehaviour
+ XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase
+ XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$OffsetType
+ XXX.block.state.BlockBehaviour$Properties
- XXX.block.state.BlockBehaviour$StateArgumentPredicate
+ XXX.block.state.BlockBehaviour$StatePredicate
- XXX.block.state.BlockState
+ XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateDefinition$PropertiesCodec
- XXX.block.state.StateHolder$1
- XXX.core.particles.package-info
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdventureAdvancements
+ XXX.data.advancements.HusbandryAdvancements
- XXX.data.advancements.NetherAdvancements
+ XXX.data.advancements.package-info
+ XXX.data.advancements.StoryAdvancements
- XXX.data.advancements.TheEndAdvancements
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
+ XXX.data.info.package-info
- XXX.data.info.RegistryDumpReport
- XXX.data.loot.BlockLoot
+ XXX.data.loot.ChestLoot
- XXX.data.loot.EntityLoot
+ XXX.data.loot.FishingLoot
- XXX.data.loot.GiftLoot
+ XXX.data.loot.LootTableProvider
+ XXX.data.loot.package-info
- XXX.data.loot.PiglinBarterLoot
- XXX.data.models.BlockModelGenerators
+ XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ModelProvider
- XXX.data.models.package-info
- XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapedRecipeBuilder$Result
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder$Result
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder$Result
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder$Result
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder$1
+ XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$TaskResult
+ XXX.data.structures.StructureUpdater
+ XXX.data.tags.BlockTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.schemas.V100
+ XXX.datafix.schemas.V102
- XXX.datafix.schemas.V1022
+ XXX.datafix.schemas.V106
- XXX.datafix.schemas.V107
+ XXX.datafix.schemas.V1125
- XXX.datafix.schemas.V135
+ XXX.datafix.schemas.V143
- XXX.datafix.schemas.V1451
+ XXX.datafix.schemas.V1451_1
- XXX.datafix.schemas.V1451_2
+ XXX.datafix.schemas.V1451_3
- XXX.datafix.schemas.V1451_4
+ XXX.datafix.schemas.V1451_5
- XXX.datafix.schemas.V1451_6
+ XXX.datafix.schemas.V1451_7
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
- XXX.dimension.end.package-info
+ XXX.dimension.end.TheEndDimension
- XXX.entity.ai.Brain$MemoryValue
- XXX.feature.configurations.StrongholdConfiguration
- XXX.feature.foliageplacers.FoliagePlacer$Factory
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.ForestFlowerProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.PlainFlowerProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.structures.EmptyPoolElement
- XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawJunction
- XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.LegacySinglePoolElement
- XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchRunner
+ XXX.gametest.framework.GameTestBatchRunner$1
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestRunner$1
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.biome.AmbientMoodSettings
- XXX.level.biome.AmbientParticleSettings
+ XXX.level.biome.BadlandsBiome
- XXX.level.biome.BadlandsPlateauBiome
+ XXX.level.biome.BambooJungleBiome
- XXX.level.biome.BambooJungleHillsBiome
+ XXX.level.biome.BasaltDeltasBiome
- XXX.level.biome.BeachBiome
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$BiomeCategory
+ XXX.level.biome.Biome$BiomeTempCategory
- XXX.level.biome.Biome$ClimateParameters
+ XXX.level.biome.Biome$MobSpawnCost
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$SpawnerData
- XXX.level.biome.BiomeDefaultFeatures
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.BiomeSource
- XXX.level.biome.MushroomFieldsBiome
+ XXX.level.biome.MushroomFieldsShoreBiome
- XXX.level.biome.NearestNeighborBiomeZoomer
+ XXX.level.biome.NetherWastesBiome
- XXX.level.biome.OceanBiome
+ XXX.level.biome.OverworldBiomeSource
+ XXX.level.biome.package-info
- XXX.level.biome.PlainsBiome
+ XXX.level.biome.RiverBiome
- XXX.level.biome.SavannaBiome
+ XXX.level.biome.SavannaPlateauBiome
- XXX.level.biome.ShatteredSavannaBiome
+ XXX.level.biome.ShatteredSavannaPlateauBiome
- XXX.level.biome.SmallEndIslandsBiome
+ XXX.level.biome.SnowyBeachBiome
- XXX.level.biome.SnowyMountainsBiome
+ XXX.level.biome.SnowyTaigaBiome
- XXX.level.biome.SnowyTaigaHillsBiome
+ XXX.level.biome.SnowyTaigaMountainsBiome
- XXX.level.biome.SnowyTundraBiome
+ XXX.level.biome.SoulSandValleyBiome
- XXX.level.biome.StoneShoreBiome
+ XXX.level.biome.SunflowerPlainsBiome
- XXX.level.biome.SwampBiome
+ XXX.level.biome.SwampHillsBiome
- XXX.level.biome.TaigaBiome
+ XXX.level.biome.TaigaHillsBiome
- XXX.level.biome.TaigaMountainsBiome
+ XXX.level.biome.TallBirchForestBiome
- XXX.level.biome.TallBirchHillsBiome
+ XXX.level.biome.TheEndBiome
- XXX.level.biome.TheEndBiomeSource
+ XXX.level.biome.TheVoidBiome
- XXX.level.biome.WarmOceanBiome
+ XXX.level.biome.WarpedForestBiome
- XXX.level.biome.WoodedBadlandsBiome
+ XXX.level.biome.WoodedHillsBiome
- XXX.level.biome.WoodedMountainBiome
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AnvilBlock
+ XXX.level.block.AttachedStemBlock
- XXX.level.block.BambooBlock
+ XXX.level.block.BambooSaplingBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BaseFireBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BaseRailBlock$1
- XXX.level.block.BeaconBeamBlock
+ XXX.level.block.BeaconBlock
- XXX.level.block.BedBlock
+ XXX.level.block.BedBlock$1
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$BlockStatePairKey
+ XXX.level.block.Blocks
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BubbleColumnBlock
+ XXX.level.block.BucketPickup
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CampfireBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.ChainBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.CocoaBlock$1
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DispenserBlock
+ XXX.level.block.DoorBlock
- XXX.level.block.DoorBlock$1
+ XXX.level.block.DoubleBlockCombiner
- XXX.level.block.DoubleBlockCombiner$BlockType
+ XXX.level.block.DoubleBlockCombiner$Combiner
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ XXX.level.block.DoublePlantBlock
- XXX.level.block.DragonEggBlock
+ XXX.level.block.DropperBlock
- XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
+ XXX.level.block.EndRodBlock$1
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FletchingTableBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GlassBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GrassPathBlock
- XXX.level.block.GravelBlock
+ XXX.level.block.GrindstoneBlock
- XXX.level.block.GrindstoneBlock$1
+ XXX.level.block.GrowingPlantBlock
- XXX.level.block.GrowingPlantBodyBlock
+ XXX.level.block.GrowingPlantHeadBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.IronBarsBlock
- XXX.level.block.JigsawBlock
+ XXX.level.block.JukeboxBlock
- XXX.level.block.KelpBlock
+ XXX.level.block.KelpPlantBlock
- XXX.level.block.LadderBlock
+ XXX.level.block.LadderBlock$1
- XXX.level.block.Lantern
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LeverBlock$1
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LoomBlock
- XXX.level.block.MagmaBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MushroomBlock
+ XXX.level.block.MyceliumBlock
- XXX.level.block.NetherPortalBlock
+ XXX.level.block.NetherPortalBlock$1
- XXX.level.block.NetherPortalBlock$PortalShape
- XXX.level.block.NetherrackBlock
+ XXX.level.block.NetherSproutsBlock
- XXX.level.block.NetherVines
+ XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.NyliumBlock
+ XXX.level.block.ObserverBlock
- XXX.level.block.OreBlock
- XXX.level.block.package-info
+ XXX.level.block.PipeBlock
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PotatoBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PressurePlateBlock$Sensitivity
+ XXX.level.block.PumpkinBlock
- XXX.level.block.RailBlock
+ XXX.level.block.RailBlock$1
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
- XXX.level.block.Rotation$1
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
+ XXX.level.block.Seagrass
- XXX.level.block.SeaPickleBlock
- XXX.level.block.ShearableDoublePlantBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SignBlock
- XXX.level.block.SimpleWaterloggedBlock
+ XXX.level.block.SkullBlock
- XXX.level.block.SkullBlock$Type
+ XXX.level.block.SkullBlock$Types
- XXX.level.block.SlabBlock
+ XXX.level.block.SlabBlock$1
- XXX.level.block.SlimeBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnowLayerBlock
- XXX.level.block.SnowLayerBlock$1
+ XXX.level.block.SnowyDirtBlock
- XXX.level.block.SoulFireBlock
+ XXX.level.block.SoulSandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SpreadingSnowyDirtBlock
- XXX.level.block.StainedGlassBlock
+ XXX.level.block.StainedGlassPaneBlock
- XXX.level.block.StairBlock
+ XXX.level.block.StairBlock$1
- XXX.level.block.StandingSignBlock
+ XXX.level.block.StemBlock
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrass
+ XXX.level.block.TargetBlock
- XXX.level.block.TntBlock
+ XXX.level.block.TorchBlock
- XXX.level.block.TrapDoorBlock
+ XXX.level.block.TrapDoorBlock$1
- XXX.level.block.TrappedChestBlock
+ XXX.level.block.TripWireBlock
- XXX.level.block.TripWireBlock$1
+ XXX.level.block.TripWireHookBlock
- XXX.level.block.TripWireHookBlock$1
+ XXX.level.block.TurtleEggBlock
- XXX.level.block.TwistingVines
+ XXX.level.block.TwistingVinesPlant
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVines
+ XXX.level.block.WeepingVinesPlant
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
+ XXX.level.dimension.Dimension
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.NetherDimension
+ XXX.level.dimension.NormalDimension
+ XXX.level.dimension.package-info
+ XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.NetherLevelSource
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseGeneratorSettings$1
- XXX.level.levelgen.NoiseSamplingSettings
- XXX.level.levelgen.NoiseSlideSettings
+ XXX.level.levelgen.OverworldLevelSource
+ XXX.level.levelgen.WorldGenSettings$BuffetGeneratorType
+ XXX.level.levelgen.WorldGenSettings$Preset
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.FlatDataLayer
- XXX.level.lighting.LayerLightEngine
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$1
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.Fluid
- XXX.level.material.FluidState
+ XXX.level.material.FluidStateImpl
- XXX.level.storage.LevelVersion
+ XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$1
- XXX.level.timers.TimerQueue$Event
- XXX.levelgen.feature.ConfiguredStructureFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DecoratedFlowerFeature
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertPyramidFeature
- XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
+ XXX.levelgen.feature.DesertVillagePools
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskReplaceFeature
- XXX.levelgen.feature.EndCityFeature
+ XXX.levelgen.feature.EndCityFeature$EndCityStart
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.GlowstoneFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IcePatchFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JunglePyramidFeature
+ XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.MineshaftFeature
+ XXX.levelgen.feature.MineshaftFeature$MineShaftStart
- XXX.levelgen.feature.MineshaftFeature$Type
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NetherFortressFeature
- XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.NoSurfaceOreFeature
+ XXX.levelgen.feature.OceanMonumentFeature
- XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PillagerOutpostFeature
+ XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
- XXX.levelgen.feature.PlainVillagePools
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomRandomFeature
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.FlatLevelGeneratorSettings$1
- XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureStart$1
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
- XXX.levelgen.structure.WoodlandMansionPieces$1
+ XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
- XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
- XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
- XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
- XXX.levelgen.surfacebuilders.package-info
+ XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
+ XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.levelgen.synth.SurfaceNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.CompositeEntryBase$Serializer
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.DynamicLoot$1
+ XXX.loot.entries.DynamicLoot$Serializer
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EmptyLootItem$1
- XXX.loot.entries.EmptyLootItem$Serializer
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootItem$1
+ XXX.loot.entries.LootItem$Serializer
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntries$Serializer
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.LootTableReference$1
+ XXX.loot.entries.LootTableReference$Serializer
+ XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
- XXX.loot.entries.TagEntry$Serializer
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$1
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.ApplyExplosionDecay$1
- XXX.loot.functions.ApplyExplosionDecay$Serializer
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$1
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$1
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.CopyNameFunction$Serializer
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$1
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$DataSource
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Serializer
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$1
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$1
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$1
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$1
- XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$1
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunction$Serializer
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctions$Serializer
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$1
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$1
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemCountFunction$1
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$1
- XXX.loot.functions.SetItemDamageFunction$Serializer
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$1
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$1
+ XXX.loot.functions.SetNbtFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$1
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$1
- XXX.loot.functions.SmeltItemFunction$Serializer
+ XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$1
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$1
- XXX.loot.predicates.AlternativeLootItemCondition$Builder
+ XXX.loot.predicates.AlternativeLootItemCondition$Serializer
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.BonusLevelTableCondition$1
- XXX.loot.predicates.BonusLevelTableCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$1
- XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$1
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$1
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemCondition$Serializer
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditions$Serializer
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemEntityPropertyCondition$1
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$1
- XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$1
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$1
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
+ XXX.minecraft.core.MapFiller
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.NonNullList
- XXX.minecraft.core.Position
+ XXX.minecraft.core.PositionImpl
- XXX.minecraft.core.Registry
- XXX.minecraft.core.RegistryAccess$RegistryHolder
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CompoundTag
+ XXX.minecraft.nbt.CompoundTag$1
- XXX.minecraft.nbt.DoubleTag
+ XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag
+ XXX.minecraft.nbt.EndTag$1
- XXX.minecraft.nbt.FloatTag
+ XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag
+ XXX.minecraft.nbt.IntArrayTag$1
- XXX.minecraft.nbt.IntTag
+ XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
+ XXX.minecraft.nbt.LongArrayTag
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
+ XXX.minecraft.nbt.LongTag$Cache
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagTypes
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$PacketHolder
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.ConnectionProtocol$1
- XXX.minecraft.network.ConnectionProtocol$PacketSet
+ XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
- XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.obfuscate.DontObfuscateOrShrink
- XXX.minecraft.obfuscate.KeepAfterObfuscation
+ XXX.minecraft.obfuscate.package-info
- XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ XXX.minecraft.util.Deserializer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.FastColor
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InsensitiveStringMap
+ XXX.minecraft.util.IntRange
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LimitedCapacityList
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RewindableStream
- XXX.minecraft.util.RewindableStream$1
+ XXX.minecraft.util.Serializable
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$1
- XXX.minecraft.util.SortedArraySet$ArrayIterator
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.WeighedRandom
- XXX.minecraft.util.WeighedRandom$WeighedRandomItem
- XXX.minecraft.world.package-info
- XXX.models.blockstates.BlockStateGenerator
+ XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$1
+ XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$Operation
+ XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$1
- XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
+ XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$1
+ XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C2
+ XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C4
+ XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyDispatch$PentaFunction
+ XXX.models.blockstates.PropertyDispatch$QuadFunction
- XXX.models.blockstates.PropertyDispatch$TriFunction
+ XXX.models.blockstates.PropertyValue
- XXX.models.blockstates.Selector
+ XXX.models.blockstates.Variant
- XXX.models.blockstates.VariantProperties
+ XXX.models.blockstates.VariantProperties$Rotation
- XXX.models.blockstates.VariantProperty
+ XXX.models.blockstates.VariantProperty$Value
+ XXX.models.model.DelegatedModel
- XXX.models.model.ModelLocationUtils
+ XXX.models.model.ModelTemplate
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
+ XXX.network.chat.BaseComponent
- XXX.network.chat.ChatType
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.Component$ContentConsumer
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.Component$StyledContentConsumer
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.ContextAwareComponent
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.KeybindComponent
+ XXX.network.chat.MutableComponent
- XXX.network.chat.NbtComponent
+ XXX.network.chat.NbtComponent$BlockNbtComponent
- XXX.network.chat.NbtComponent$EntityNbtComponent
+ XXX.network.chat.NbtComponent$StorageNbtComponent
+ XXX.network.chat.package-info
- XXX.network.chat.ScoreComponent
+ XXX.network.chat.SelectorComponent
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$Serializer
+ XXX.network.chat.TextColor
- XXX.network.chat.TextComponent
+ XXX.network.chat.TranslatableComponent
- XXX.network.chat.TranslatableFormatException
- XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$10
+ XXX.network.syncher.EntityDataSerializers$11
- XXX.network.syncher.EntityDataSerializers$12
+ XXX.network.syncher.EntityDataSerializers$13
- XXX.network.syncher.EntityDataSerializers$14
+ XXX.network.syncher.EntityDataSerializers$15
- XXX.network.syncher.EntityDataSerializers$16
+ XXX.network.syncher.EntityDataSerializers$17
- XXX.network.syncher.EntityDataSerializers$18
+ XXX.network.syncher.EntityDataSerializers$19
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.EntityDataSerializers$8
+ XXX.network.syncher.EntityDataSerializers$9
- XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$1
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.IntPointRange
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.phys.shapes.WorldRegionIndirectVoxelShape
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundAddGlobalEntityPacket
- XXX.protocol.game.ClientboundAddMobPacket
+ XXX.protocol.game.ClientboundAddPaintingPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockBreakAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChatPacket
+ XXX.protocol.game.ClientboundChunkBlocksUpdatePacket
- XXX.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$1
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundContainerAckPacket
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
- XXX.protocol.game.ClientboundLevelChunkPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
+ XXX.protocol.game.ClientboundPlaceGhostRecipePacket
- XXX.protocol.game.ClientboundPlayerAbilitiesPacket
+ XXX.protocol.game.ClientboundPlayerCombatPacket
- XXX.protocol.game.ClientboundPlayerCombatPacket$1
+ XXX.protocol.game.ClientboundPlayerCombatPacket$Event
- XXX.protocol.game.ClientboundPlayerInfoPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$1
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- XXX.protocol.game.ClientboundPlayerLookAtPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResourcePackPacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundSetBorderPacket
- XXX.protocol.game.ClientboundSetBorderPacket$1
+ XXX.protocol.game.ClientboundSetBorderPacket$Type
- XXX.protocol.game.ClientboundSetCameraPacket
+ XXX.protocol.game.ClientboundSetCarriedItemPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquippedItemPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket
+ XXX.protocol.game.ClientboundSetScorePacket
- XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesPacket
- XXX.protocol.game.ClientboundSetTitlesPacket$Type
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerAckPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundRecipeBookUpdatePacket
- XXX.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
+ XXX.protocol.game.ServerboundRenameItemPacket
- XXX.protocol.game.ServerboundResourcePackPacket
+ XXX.protocol.game.ServerboundResourcePackPacket$Action
- XXX.protocol.game.ServerboundSeenAdvancementsPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSignUpdatePacket
+ XXX.protocol.game.ServerboundSwingPacket
- XXX.protocol.game.ServerboundTeleportToEntityPacket
+ XXX.protocol.game.ServerboundUseItemOnPacket
- XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.protocol.status.ServerStatusPacketListener
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.server.level.DerivedServerLevel
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FeatureSimulator
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPattern$PortalInfo
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate
- XXX.state.predicate.BlockMaterialPredicate$1
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
- XXX.storage.loot.Deserializers
+ XXX.storage.loot.IntLimiter
- XXX.storage.loot.IntLimiter$1
+ XXX.storage.loot.IntLimiter$Serializer
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$1
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$DynamicDrop
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$EntityTarget$Serializer
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$1
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$1
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.LootTable$Serializer
+ XXX.storage.loot.LootTables
- XXX.storage.loot.package-info
- XXX.storage.loot.PredicateManager
+ XXX.storage.loot.RandomIntGenerator
- XXX.storage.loot.RandomIntGenerators
+ XXX.storage.loot.RandomValueBounds
- XXX.storage.loot.RandomValueBounds$Serializer
+ XXX.storage.loot.ValidationContext
- XXX.storage.threaded.package-info
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.OminousBannerBlockEntityRenameFix
- XXX.world.level.Level$1
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PortalForcer
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ServerTickList
- XXX.world.level.SpawnData
+ XXX.world.level.StructureFeatureManager
- XXX.world.level.TickList
+ XXX.world.level.TickNextTickData
- XXX.world.level.TickPriority
+ XXX.world.level.WorldGenLevel
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.PosAndRot
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.scores.Objective
- XXX.world.scores.package-info
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.Score
- XXX.world.scores.Scoreboard
+ XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +1P
```
```
XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance +5M -5M | +2P -2P
```
```
XXX.advancements.critereon.LocationPredicate +5M -3M | +2P -1P
```
```
XXX.minecraft.commands.CommandSource +1P -1P
```
```
XXX.minecraft.commands.CommandSourceStack +1M
```
```
XXX.commands.arguments.DimensionTypeArgument +3M -4M
```
```
XXX.minecraft.core.DefaultedRegistry +2M -2M
```
```
XXX.minecraft.core.SerializableLong +2M -2M | +1P
```
```
XXX.minecraft.core.WritableRegistry +2M -1M | +2P -2P
```
```
XXX.core.particles.ParticleTypes +2M -1M | +1P
```
```
XXX.minecraft.resources.ResourceLocation +4M -2M | +1P
```
```
XXX.server.commands.SpreadPlayersCommand$Position +2M -2M
```
```
XXX.server.level.ServerPlayer +13M -12M | +1P -1P
```
```
XXX.server.level.WorldGenRegion -1M | +1P -1P
```
```
XXX.server.players.PlayerList +4M -5M | +1P
```
```
XXX.minecraft.sounds.SoundEvents +7P
```
```
XXX.minecraft.tags.Tag +5M
```
```
XXX.datafix.fixes.AbstractUUIDFix +11M -11M
```
```
XXX.datafix.fixes.AttributesRename +7M -7M
```
```
XXX.datafix.fixes.BlockEntityBannerColorFix +5M -5M
```
```
XXX.datafix.fixes.BlockEntityCustomNameToComponentFix +1M -1M
```
```
XXX.datafix.fixes.BlockEntityShulkerBoxColorFix +1M -1M
```
```
XXX.datafix.fixes.BlockNameFlatteningFix +1M -1M
```
```
XXX.datafix.fixes.ChunkBiomeFix +1M -1M
```
```
XXX.datafix.fixes.ChunkPalettedStorageFix +15M -15M | +11P -11P
```
```
XXX.datafix.fixes.ChunkPalettedStorageFix$Section +4M -4M | +2P -2P
```
```
XXX.datafix.fixes.ChunkStructuresTemplateRenameFix +2M -2M
```
```
XXX.datafix.fixes.ColorlessShulkerEntityFix +1M -1M
```
```
XXX.datafix.fixes.EntityArmorStandSilentFix +1M -1M
```
```
XXX.datafix.fixes.EntityCatSplitFix +1M -1M
```
```
XXX.datafix.fixes.EntityCustomNameToComponentFix +2M -2M
```
```
XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix +1M -1M
```
```
XXX.datafix.fixes.EntityIdFix +1M -1M
```
```
XXX.datafix.fixes.EntityMinecartIdentifiersFix +4M -3M
```
```
XXX.datafix.fixes.EntityPaintingMotiveFix +1M -1M
```
```
XXX.datafix.fixes.EntityRedundantChanceTagsFix +3M -3M
```
```
XXX.datafix.fixes.EntityRidingToPassengersFix +3M -3M
```
```
XXX.datafix.fixes.EntityShulkerRotationFix +2M -2M
```
```
XXX.datafix.fixes.EntityStringUuidFix +1M -1M
```
```
XXX.datafix.fixes.EntityWolfColorFix +2M -2M
```
```
XXX.datafix.fixes.EntityZombieVillagerTypeFix +1M -1M
```
```
XXX.datafix.fixes.ForcePoiRebuild +4M -4M
```
```
XXX.datafix.fixes.GossipUUIDFix +3M -3M
```
```
XXX.datafix.fixes.IglooMetadataRemovalFix +4M -4M
```
```
XXX.datafix.fixes.ItemCustomNameToComponentFix +1M -1M
```
```
XXX.datafix.fixes.ItemLoreFix +4M -4M
```
```
XXX.datafix.fixes.ItemRenameFix +1M -1M
```
```
XXX.datafix.fixes.ItemStackEnchantmentNamesFix +4M -4M
```
```
XXX.datafix.fixes.ItemStackUUIDFix +6M -6M
```
```
XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix +3M -3M
```
```
XXX.datafix.fixes.JigsawRotationFix +2M -2M
```
```
XXX.datafix.fixes.LeavesFix$LeavesSection +1M -1M
```
```
XXX.datafix.fixes.LevelDataGeneratorOptionsFix +7M -6M
```
```
XXX.datafix.fixes.LevelUUIDFix +12M -12M
```
```
XXX.datafix.fixes.MemoryExpiryDataFix +4M -4M
```
```
XXX.datafix.fixes.ObjectiveDisplayNameFix +3M -3M
```
```
XXX.datafix.fixes.OptionsAddTextBackgroundFix +2M -2M
```
```
XXX.datafix.fixes.OptionsKeyLwjgl3Fix +2M -2M
```
```
XXX.datafix.fixes.OptionsLowerCaseLanguageFix +1M -1M
```
```
XXX.datafix.fixes.PoiTypeRename +9M -9M
```
```
XXX.datafix.fixes.RecipesRenameFix +1M -1M
```
```
XXX.datafix.fixes.RedstoneWireConnectionsFix +6M -10M
```
```
XXX.datafix.fixes.RenameBiomesFix +1M -1M
```
```
XXX.datafix.fixes.SavedDataUUIDFix +6M -6M
```
```
XXX.datafix.fixes.SimpleEntityRenameFix +1P -1P
```
```
XXX.datafix.fixes.StatsCounterFix +1M -1M
```
```
XXX.datafix.fixes.StructureReferenceCountFix +2M -2M
```
```
XXX.datafix.fixes.TeamDisplayNameFix +3M -3M
```
```
XXX.datafix.fixes.VillagerFollowRangeFix +3M -3M
```
```
XXX.datafix.schemas.NamespacedSchema +2M | +2P
```
```
XXX.datafix.schemas.V704$1 +1M -1M
```
```
XXX.datafix.schemas.V705$1 +1M -1M
```
```
XXX.datafix.schemas.V99 +4M -4M
```
```
XXX.world.entity.Entity +2M -2M | -1P
```
```
XXX.entity.ai.Brain +13M -6M | +2P
```
```
XXX.ai.goal.MeleeAttackGoal +4M | +4P -4P
```
```
XXX.ai.gossip.GossipContainer +5M -4M
```
```
XXX.ai.memory.ExpirableValue +5M -3M
```
```
XXX.village.poi.PoiSection +13M -11M
```
```
XXX.entity.animal.AbstractFish +1M
```
```
XXX.animal.horse.AbstractChestedHorse -1M
```
```
XXX.animal.horse.Donkey +2M
```
```
XXX.monster.hoglin.HoglinAi +1M -1M
```
```
XXX.monster.piglin.Piglin +2M -1M
```
```
XXX.monster.piglin.PiglinAi +1M -2M | -1P
```
```
XXX.entity.npc.Villager +10M -8M
```
```
XXX.entity.npc.WanderingTraderSpawner +5M -5M | -1P
```
```
XXX.entity.projectile.ThrownEnderpearl +1M -1M
```
```
XXX.world.item.CompassItem +3M -1M | +1P
```
```
XXX.world.item.ItemStack +9M -4M | +1P
```
```
XXX.world.level.GameRules +4M -2M
```
```
XXX.level.biome.BiomeSpecialEffects +10M | +1P
```
```
XXX.level.biome.FixedBiomeSource +3M | +1P
```
```
XXX.level.biome.MultiNoiseBiomeSource +18M -4M | +4P
```
```
XXX.state.properties.Property +12M | +4P -2P
```
```
XXX.level.border.WorldBorder$Settings +1M -1M
```
```
XXX.level.chunk.ProtoChunk +2M -1M
```
```
XXX.chunk.storage.SectionStorage +7M -5M | +1P -2P
```
```
XXX.level.levelgen.DebugLevelSource +3M -1M | +2P -1P
```
```
XXX.level.levelgen.WorldGenSettings +11M -24M | +3P -8P
```
```
XXX.levelgen.carver.CanyonWorldCarver +1M -1M
```
```
XXX.levelgen.carver.CaveWorldCarver +1M -1M
```
```
XXX.levelgen.carver.NetherWorldCarver +1M -1M
```
```
XXX.levelgen.carver.UnderwaterCanyonWorldCarver +1M -1M
```
```
XXX.levelgen.carver.WorldCarver +4M -2M | +1P -1P
```
```
XXX.levelgen.feature.AbstractFlowerFeature +1M -1M
```
```
XXX.levelgen.feature.BambooFeature +1M -1M
```
```
XXX.levelgen.feature.BasaltPillarFeature +1M -1M
```
```
XXX.levelgen.feature.BastionFeature +3M -8M
```
```
XXX.levelgen.feature.BlockBlobFeature +1M -1M
```
```
XXX.levelgen.feature.BlueIceFeature +1M -1M
```
```
XXX.levelgen.feature.BuriedTreasureFeature +3M -4M
```
```
XXX.levelgen.feature.ChorusPlantFeature +1M -1M
```
```
XXX.levelgen.feature.RandomSelectorFeature +1M -1M
```
```
XXX.levelgen.feature.ReplaceBlockFeature +1M -1M
```
```
XXX.levelgen.feature.RuinedPortalFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.SeagrassFeature +1M -1M
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.SimpleRandomSelectorFeature +1M -1M
```
```
XXX.levelgen.feature.SnowAndFreezeFeature +1M -1M
```
```
XXX.levelgen.feature.SpikeFeature +1M -1M
```
```
XXX.levelgen.feature.SpikeFeature$EndSpike +7M -2M | +1P
```
```
XXX.levelgen.feature.SpringFeature +1M -1M
```
```
XXX.levelgen.feature.StrongholdFeature$StrongholdStart +2M -1M
```
```
XXX.levelgen.feature.SwamplandHutFeature +1M -5M
```
```
XXX.levelgen.feature.TwistingVinesFeature +1M -1M
```
```
XXX.levelgen.feature.VillageFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.VoidStartPlatformFeature +1M -1M
```
```
XXX.levelgen.feature.WeightedConfiguredFeature +4M -2M | +1P
```
```
XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart +3M -2M
```
```
XXX.feature.blockplacers.BlockPlacerType +3M -3M | +1P -1P
```
```
XXX.feature.blockplacers.DoublePlantPlacer +3M -2M | +2P
```
```
XXX.feature.configurations.BlockPileConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.BuriedTreasureConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +6M -2M | +1P
```
```
XXX.feature.configurations.CountFeatureConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.DecoratedFeatureConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.DeltaFeatureConfiguration +7M -2M | +1P
```
```
XXX.feature.configurations.DiskConfiguration +6M -3M | +1P
```
```
XXX.feature.configurations.FeatureConfiguration -1P
```
```
XXX.feature.configurations.HugeMushroomFeatureConfiguration +5M -2M | +1P
```
```
XXX.feature.configurations.LayerConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.MultiJigsawConfiguration +4M -4M | +1P
```
```
XXX.feature.configurations.NoneDecoratorConfiguration +2M -2M | +2P
```
```
XXX.feature.configurations.OceanRuinConfiguration +5M -2M | +1P
```
```
XXX.feature.configurations.OreConfiguration$Predicates +3M -1M | +2P
```
```
XXX.feature.configurations.RandomBooleanFeatureConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.RandomPatchConfiguration +14M -4M | +1P
```
```
XXX.feature.configurations.ReplaceBlockConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.SeagrassFeatureConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.SimpleBlockConfiguration +6M -6M | +1P
```
```
XXX.feature.configurations.SpikeConfiguration +6M -4M | +1P
```
```
XXX.feature.configurations.TreeConfiguration +11M -4M | +1P
```
```
XXX.feature.featuresize.FeatureSizeType +3M -3M | +1P -1P
```
```
XXX.feature.featuresize.TwoLayersFeatureSize +6M -3M | +1P
```
```
XXX.feature.foliageplacers.AcaciaFoliagePlacer +3M -1M | +1P
```
```
XXX.feature.foliageplacers.BushFoliagePlacer +3M -1M | +1P
```
```
XXX.feature.foliageplacers.FancyFoliagePlacer +2M -1M | +1P
```
```
XXX.levelgen.placement.CarvingMaskDecoratorConfiguration +4M -2M | +1P
```
```
XXX.levelgen.placement.ChanceHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.ChancePassthroughDecorator +1M -1M
```
```
XXX.levelgen.placement.ChorusPlantPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.CountBiasedRangeDecorator +1M -1M
```
```
XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator +1M -1M
```
```
XXX.levelgen.placement.CountHeighmapDoubleDecorator +1M -1M
```
```
XXX.levelgen.placement.CountHeightmap32Decorator +1M -1M
```
```
XXX.levelgen.placement.CountTopSolidDecorator +1M -1M
```
```
XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.DepthAverageConfigation +5M -2M | +1P
```
```
XXX.levelgen.placement.EndGatewayPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.FeatureDecorator +5M -3M | +1P -1P
```
```
XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration +4M -2M | +1P
```
```
XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration +5M -2M | +1P
```
```
XXX.levelgen.placement.LakeLavaPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.MonsterRoomPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.NoiseHeightmap32Decorator +1M -1M
```
```
XXX.levelgen.placement.NopePlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.SimpleFeatureDecorator +1M -1M
```
```
XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator +1M -1M
```
```
XXX.placement.nether.ChanceRangeDecorator +1M -1M
```
```
XXX.placement.nether.FireDecorator +1M -1M
```
```
XXX.placement.nether.MagmaDecorator +1M -1M
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +2M -1M
```
```
XXX.levelgen.structure.PoolElementStructurePiece +2M | +1P
```
```
XXX.levelgen.structure.RuinedPortalPiece$Properties +9M -2M | +1P
```
```
XXX.saveddata.maps.MapItemSavedData +4M -1M | +2P -1P
```
```
XXX.level.storage.DerivedLevelData -2M
```
```
XXX.level.storage.LevelStorageSource$LevelStorageAccess +4M -1M
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
</summary>

```diff
+ boolean matches(DimensionType,DimensionType)
- boolean matches(ResourceKey,ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimension(DimensionType,DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimension(ResourceKey,ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimensionFrom(DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimensionFrom(ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimensionTo(DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimensionTo(ResourceKey)
+ void <init>(EntityPredicate$Composite,DimensionType,DimensionType)
- void <init>(EntityPredicate$Composite,ResourceKey,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate
</summary>

```diff
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
- JsonSyntaxException lambda$fromJson$2(ResourceLocation)
+ LocationPredicate inDimension(DimensionType)
- LocationPredicate inDimension(ResourceKey)
- ResourceKey lambda$fromJson$1(ResourceLocation)
+ void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,DimensionType,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
- void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,ResourceKey,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
- void lambda$serializeToJson$0(JsonObject,JsonElement)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
- RegistryAccess registryAccess()
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.DimensionTypeArgument
</summary>

```diff
+ CommandSyntaxException lambda$parse$2(ResourceLocation)
+ DimensionType getDimension(CommandContext,String)
+ DimensionType parse(StringReader)
- ResourceKey getDimension(CommandContext,String)
- ResourceLocation parse(StringReader)
+ String lambda$static$0(DimensionType)
- String lambda$static$0(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.core.DefaultedRegistry
</summary>

```diff
- Object registerMapping(int,ResourceKey,Object)
+ Object registerMapping(int,ResourceLocation,Object)
- void <init>(String,ResourceKey,Lifecycle)
+ void <init>(String)
```

</details>
<details>
<summary>
net.minecraft.core.SerializableLong
</summary>

```diff
- Long lambda$static$0(SerializableLong)
+ Object serialize(DynamicOps)
+ SerializableLong of(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.core.WritableRegistry
</summary>

```diff
- String toString()
+ void <init>()
- void <init>(ResourceKey,Lifecycle)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ParticleTypes
</summary>

```diff
- Codec lambda$static$0(ParticleType)
- ParticleType register(String,ParticleOptions$Deserializer,Function)
+ ParticleType register(String,ParticleOptions$Deserializer)
```

</details>
<details>
<summary>
net.minecraft.resources.ResourceLocation
</summary>

```diff
+ boolean lambda$isValidNamespace$1(int)
+ boolean lambda$isValidPath$0(int)
- boolean validNamespaceChar(char)
- boolean validPathChar(char)
- DataResult read(String)
- String toDebugFileName()
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpreadPlayersCommand$Position
</summary>

```diff
- boolean isSafe(BlockGetter,int)
+ boolean isSafe(BlockGetter)
- int getSpawnY(BlockGetter,int)
+ int getSpawnY(BlockGetter)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean lambda$startSleepInBed$3(Monster)
- boolean lambda$startSleepInBed$4(Monster)
+ DimensionType getRespawnDimension()
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
- ResourceKey getRespawnDimension()
+ Style lambda$null$1(Component,Style)
- Style lambda$null$2(Component,Style)
- void lambda$addAdditionalSaveData$0(CompoundTag,Tag)
+ void lambda$awardStat$5(int,Score)
- void lambda$awardStat$6(int,Score)
+ void lambda$die$2(Component,Future)
- void lambda$die$3(Component,Future)
+ void lambda$sendMessage$6(ChatType,Component,Future)
- void lambda$sendMessage$7(ChatType,Component,UUID,Future)
+ void lambda$startSleepInBed$4(Unit)
- void lambda$startSleepInBed$5(Unit)
+ void lambda$updateScoreForCriteria$0(int,Score)
- void lambda$updateScoreForCriteria$1(int,Score)
- void sendMessage(Component,ChatType,UUID)
+ void sendMessage(Component,ChatType)
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
+ void setRespawnPosition(DimensionType,BlockPos,boolean,boolean)
- void setRespawnPosition(ResourceKey,BlockPos,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
+ Dimension getDimension()
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ void <init>(MinecraftServer,PlayerDataStorage,int)
- void <init>(MinecraftServer,RegistryAccess$RegistryHolder,PlayerDataStorage,int)
+ void broadcast(Player,double,double,double,double,DimensionType,Packet)
- void broadcast(Player,double,double,double,double,ResourceKey,Packet)
+ void broadcastAll(Packet,DimensionType)
- void broadcastAll(Packet,ResourceKey)
+ void broadcastMessage(Component,boolean)
- void broadcastMessage(Component,ChatType,UUID)
+ void broadcastMessage(Component)
```

</details>
<details>
<summary>
net.minecraft.tags.Tag
</summary>

```diff
- Codec codec(Supplier)
- DataResult lambda$codec$1(Supplier,ResourceLocation)
- DataResult lambda$codec$3(Supplier,Tag)
- DataResult lambda$null$0(ResourceLocation)
- DataResult lambda$null$2(Tag)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.AbstractUUIDFix
</summary>

```diff
+ Dynamic lambda$replaceUUIDLeastMost$3(Dynamic,String,String,String,Dynamic)
- Dynamic lambda$replaceUUIDLeastMost$3(Dynamic,String,String,String,Dynamic)
+ Dynamic lambda$replaceUUIDMLTag$2(Dynamic,String,String,Dynamic)
- Dynamic lambda$replaceUUIDMLTag$2(Dynamic,String,String,Dynamic)
+ Dynamic lambda$replaceUUIDString$1(Dynamic,String,String,Dynamic)
- Dynamic lambda$replaceUUIDString$1(Dynamic,String,String,Dynamic)
+ Optional createUUIDFromLongs(Dynamic,String,String)
- Optional createUUIDFromLongs(Dynamic,String,String)
+ Optional createUUIDFromML(Dynamic)
- Optional createUUIDFromML(Dynamic)
+ Optional createUUIDFromString(Dynamic,String)
- Optional createUUIDFromString(Dynamic,String)
+ Optional createUUIDTag(Dynamic,long,long)
- Optional createUUIDTag(Dynamic,long,long)
+ Optional lambda$createUUIDFromString$4(Dynamic,Dynamic)
- Optional lambda$createUUIDFromString$4(Dynamic,Dynamic)
+ Optional replaceUUIDLeastMost(Dynamic,String,String)
- Optional replaceUUIDLeastMost(Dynamic,String,String)
+ Optional replaceUUIDMLTag(Dynamic,String,String)
- Optional replaceUUIDMLTag(Dynamic,String,String)
+ Optional replaceUUIDString(Dynamic,String,String)
- Optional replaceUUIDString(Dynamic,String,String)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.AttributesRename
</summary>

```diff
+ Dynamic fixName(Dynamic)
- Dynamic fixName(Dynamic)
+ Dynamic lambda$fixEntity$9(Dynamic)
- Dynamic lambda$fixEntity$9(Dynamic)
+ Dynamic lambda$fixItemStackTag$5(Dynamic)
- Dynamic lambda$fixItemStackTag$5(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Dynamic lambda$null$4(Dynamic)
- Dynamic lambda$null$4(Dynamic)
+ Dynamic lambda$null$6(Dynamic)
- Dynamic lambda$null$6(Dynamic)
+ Dynamic lambda$null$8(Dynamic)
- Dynamic lambda$null$8(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$fixTag$0(Dynamic)
- Dynamic lambda$fixTag$0(Dynamic)
+ Dynamic lambda$fixTag$4(Dynamic)
- Dynamic lambda$fixTag$4(Dynamic)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
</summary>

```diff
+ Dynamic lambda$null$0(Typed,OpticFinder,Dynamic)
- Dynamic lambda$null$0(Typed,OpticFinder,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
</summary>

```diff
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
</summary>

```diff
+ Function lambda$makeRule$3(DynamicOps)
- Function lambda$makeRule$3(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkBiomeFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
</summary>

```diff
+ Dynamic access$000()
- Dynamic access$000()
+ Dynamic access$1000()
- Dynamic access$1000()
+ Dynamic access$1400()
- Dynamic access$1400()
+ Dynamic access$1500()
- Dynamic access$1500()
+ Dynamic access$1600()
- Dynamic access$1600()
+ Dynamic access$1700()
- Dynamic access$1700()
+ Dynamic access$1800()
- Dynamic access$1800()
+ Dynamic access$1900()
- Dynamic access$1900()
+ Dynamic access$400()
- Dynamic access$400()
+ Dynamic access$500()
- Dynamic access$500()
+ Dynamic access$600()
- Dynamic access$600()
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
+ int idFor(CrudeIncrementalIntIdentityHashBiMap,Dynamic)
- int idFor(CrudeIncrementalIntIdentityHashBiMap,Dynamic)
+ String getName(Dynamic)
- String getName(Dynamic)
+ String getProperty(Dynamic,String)
- String getProperty(Dynamic,String)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
</summary>

```diff
+ Dynamic getBlock(int)
- Dynamic getBlock(int)
+ Dynamic write()
- Dynamic write()
+ void <init>(Dynamic)
- void <init>(Dynamic)
+ void setBlock(int,Dynamic)
- void setBlock(int,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
</summary>

```diff
+ Dynamic fixTag(Dynamic,Dynamic)
- Dynamic fixTag(Dynamic,Dynamic)
+ Dynamic lambda$null$0(Typed,Dynamic)
- Dynamic lambda$null$0(Typed,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
</summary>

```diff
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityCatSplitFix
</summary>

```diff
+ Pair getNewNameAndTag(String,Dynamic)
- Pair getNewNameAndTag(String,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
</summary>

```diff
+ Dynamic fixTagCustomName(Dynamic)
- Dynamic fixTagCustomName(Dynamic)
+ Dynamic lambda$null$0(Typed,OpticFinder,Dynamic)
- Dynamic lambda$null$0(Typed,OpticFinder,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityIdFix
</summary>

```diff
+ Function lambda$makeRule$3(DynamicOps)
- Function lambda$makeRule$3(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
</summary>

```diff
- DataResult lambda$null$0(TaggedChoice$TaggedChoiceType,String,Dynamic)
+ Function lambda$makeRule$2(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$makeRule$3(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
+ IllegalStateException lambda$null$0()
- IllegalStateException lambda$null$1()
+ Pair lambda$null$1(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
- Pair lambda$null$2(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
</summary>

```diff
+ Either lambda$null$2(Type,DynamicOps,OpticFinder,OpticFinder,Pair)
- Either lambda$null$2(Type,DynamicOps,OpticFinder,OpticFinder,Pair)
+ Function lambda$cap$6(Type,OpticFinder,OpticFinder,Type,OpticFinder,DynamicOps)
- Function lambda$cap$6(Type,OpticFinder,OpticFinder,Type,OpticFinder,DynamicOps)
+ Pair lambda$null$5(Type,DynamicOps,OpticFinder,OpticFinder,Type,OpticFinder,Pair)
- Pair lambda$null$5(Type,DynamicOps,OpticFinder,OpticFinder,Type,OpticFinder,Pair)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
</summary>

```diff
+ Double lambda$fixTag$0(Dynamic)
- Double lambda$fixTag$0(Dynamic)
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityStringUuidFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityWolfColorFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$fixTag$0(Dynamic)
- Dynamic lambda$fixTag$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ForcePoiRebuild
</summary>

```diff
+ Dynamic cap(Dynamic)
- Dynamic cap(Dynamic)
+ Dynamic lambda$cap$4(Dynamic)
- Dynamic lambda$cap$4(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.GossipUUIDFix
</summary>

```diff
+ Dynamic lambda$fix$3(Dynamic)
- Dynamic lambda$fix$3(Dynamic)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
</summary>

```diff
+ boolean isIglooPiece(Dynamic)
- boolean isIglooPiece(Dynamic)
+ boolean lambda$null$1(Dynamic)
- boolean lambda$null$1(Dynamic)
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic removeIglooPieces(Dynamic)
- Dynamic removeIglooPieces(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemLoreFix
</summary>

```diff
+ Dynamic lambda$fixLoreList$5(Dynamic)
- Dynamic lambda$fixLoreList$5(Dynamic)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemRenameFix
</summary>

```diff
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$fixTag$7(Dynamic)
- Dynamic lambda$fixTag$7(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$5(Dynamic)
- Dynamic lambda$null$5(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemStackUUIDFix
</summary>

```diff
+ Dynamic lambda$null$1(Typed,OpticFinder,Dynamic)
- Dynamic lambda$null$1(Typed,OpticFinder,Dynamic)
+ Dynamic lambda$null$4(Dynamic)
- Dynamic lambda$null$4(Dynamic)
+ Dynamic lambda$updateAttributeModifiers$5(Dynamic,Dynamic)
- Dynamic lambda$updateAttributeModifiers$5(Dynamic,Dynamic)
+ Dynamic lambda$updateSkullOwner$6(Dynamic)
- Dynamic lambda$updateSkullOwner$6(Dynamic)
+ Dynamic updateAttributeModifiers(Dynamic)
- Dynamic updateAttributeModifiers(Dynamic)
+ Dynamic updateSkullOwner(Dynamic)
- Dynamic updateSkullOwner(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$fixTag$2(Dynamic,Dynamic)
- Dynamic lambda$fixTag$2(Dynamic,Dynamic)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.JigsawRotationFix
</summary>

```diff
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
</summary>

```diff
+ Dynamic makeLeafTag(Dynamic,String,boolean,int)
- Dynamic makeLeafTag(Dynamic,String,boolean,int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
</summary>

```diff
- DataResult lambda$null$1(Type,Dynamic)
+ Dynamic convert(String,DynamicOps)
- Dynamic convert(String,DynamicOps)
+ IllegalStateException lambda$null$1()
- IllegalStateException lambda$null$2()
+ Object lambda$convert$3(DynamicOps,Pair)
- Object lambda$convert$4(DynamicOps,Pair)
+ Pair lambda$convert$5(DynamicOps,Map$Entry)
- Pair lambda$convert$6(DynamicOps,Map$Entry)
+ Pair lambda$null$4(DynamicOps,Map$Entry)
- Pair lambda$null$5(DynamicOps,Map$Entry)
+ Typed lambda$makeRule$2(Type,Typed)
- Typed lambda$makeRule$3(Type,Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LevelUUIDFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$10(Dynamic)
- Dynamic lambda$null$10(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$4(Dynamic)
- Dynamic lambda$null$4(Dynamic)
+ Dynamic lambda$null$7(Dynamic)
- Dynamic lambda$null$7(Dynamic)
+ Dynamic lambda$null$8(Dynamic)
- Dynamic lambda$null$8(Dynamic)
+ Dynamic lambda$null$9(Dynamic,Dynamic)
- Dynamic lambda$null$9(Dynamic,Dynamic)
+ Dynamic lambda$updateCustomBossEvents$12(Dynamic)
- Dynamic lambda$updateCustomBossEvents$12(Dynamic)
+ Dynamic lambda$updateDragonFight$6(Dynamic)
- Dynamic lambda$updateDragonFight$6(Dynamic)
+ Dynamic updateCustomBossEvents(Dynamic)
- Dynamic updateCustomBossEvents(Dynamic)
+ Dynamic updateDragonFight(Dynamic)
- Dynamic updateDragonFight(Dynamic)
+ Dynamic updateWanderingTrader(Dynamic)
- Dynamic updateWanderingTrader(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic updateBrain(Dynamic)
- Dynamic updateBrain(Dynamic)
+ Dynamic updateMemories(Dynamic)
- Dynamic updateMemories(Dynamic)
+ Dynamic wrapMemoryValue(Dynamic)
- Dynamic wrapMemoryValue(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic,Dynamic)
- Dynamic lambda$null$1(Dynamic,Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Function lambda$makeRule$4(DynamicOps)
- Function lambda$makeRule$4(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic,String)
- Dynamic lambda$null$0(Dynamic,String)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
</summary>

```diff
+ Dynamic lambda$null$2(Dynamic,Map)
- Dynamic lambda$null$2(Dynamic,Map)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.PoiTypeRename
</summary>

```diff
+ Dynamic cap(Dynamic)
- Dynamic cap(Dynamic)
+ Dynamic lambda$cap$5(Dynamic)
- Dynamic lambda$cap$5(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$6(Dynamic)
- Dynamic lambda$null$6(Dynamic)
+ Dynamic lambda$null$7(Dynamic)
- Dynamic lambda$null$7(Dynamic)
+ Dynamic lambda$renameRecords$8(Dynamic,Stream)
- Dynamic lambda$renameRecords$8(Dynamic,Stream)
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
+ Optional renameRecords(Dynamic)
- Optional renameRecords(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.RecipesRenameFix
</summary>

```diff
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
</summary>

```diff
- Dynamic lambda$null$1(String,Dynamic)
- Dynamic lambda$null$2(String,Dynamic)
- Dynamic lambda$null$3(String,Dynamic)
- Dynamic lambda$null$4(String,Dynamic)
+ Dynamic lambda$null$5(String,Dynamic)
+ Dynamic lambda$null$6(String,Dynamic)
+ Dynamic lambda$null$7(String,Dynamic)
+ Dynamic lambda$null$8(String,Dynamic)
- Dynamic lambda$updateRedstoneConnections$5(Dynamic)
+ Dynamic lambda$updateRedstoneConnections$9(Dynamic)
+ Dynamic updateRedstoneConnections(Dynamic)
- Dynamic updateRedstoneConnections(Dynamic)
+ String lambda$null$1()
+ String lambda$null$2()
+ String lambda$null$3()
+ String lambda$null$4()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.RenameBiomesFix
</summary>

```diff
+ Function lambda$makeRule$2(DynamicOps)
- Function lambda$makeRule$2(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.SavedDataUUIDFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$4(Dynamic)
- Dynamic lambda$null$4(Dynamic)
+ Dynamic lambda$null$5(Dynamic)
- Dynamic lambda$null$5(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.StatsCounterFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic,Dynamic)
- Dynamic lambda$null$0(Dynamic,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.StructureReferenceCountFix
</summary>

```diff
+ Dynamic lambda$setCountToAtLeastOne$2(Dynamic)
- Dynamic lambda$setCountToAtLeastOne$2(Dynamic)
+ Dynamic setCountToAtLeastOne(Dynamic)
- Dynamic setCountToAtLeastOne(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.TeamDisplayNameFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic,Dynamic)
- Dynamic lambda$null$1(Dynamic,Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Function lambda$makeRule$4(DynamicOps)
- Function lambda$makeRule$4(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
</summary>

```diff
+ Dynamic fixValue(Dynamic)
- Dynamic fixValue(Dynamic)
+ Dynamic lambda$fixValue$1(Dynamic,Dynamic)
- Dynamic lambda$fixValue$1(Dynamic,Dynamic)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.NamespacedSchema
</summary>

```diff
- Type namespacedString()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V704$1
</summary>

```diff
+ Object apply(DynamicOps,Object)
- Object apply(DynamicOps,Object)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V705$1
</summary>

```diff
+ Object apply(DynamicOps,Object)
- Object apply(DynamicOps,Object)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V99
</summary>

```diff
+ Dynamic lambda$addNames$35(Dynamic,Map,String,Dynamic)
- Dynamic lambda$addNames$35(Dynamic,Map,String,Dynamic)
+ Dynamic lambda$null$33(Dynamic,Map,Dynamic)
- Dynamic lambda$null$33(Dynamic,Map,Dynamic)
+ Dynamic lambda$null$34(Dynamic,String,Dynamic)
- Dynamic lambda$null$34(Dynamic,String,Dynamic)
+ Object addNames(Dynamic,Map,String)
- Object addNames(Dynamic,Map,String)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.Brain
</summary>

```diff
+ boolean lambda$isMemoryValue$0(Object,Object)
- boolean lambda$isMemoryValue$1(Object,Object)
- Brain$MemoryValue lambda$memories$0(Map$Entry)
- Brain$Provider provider(Collection,Collection)
- Codec codec(Collection,Collection)
- DataResult serializeStart(DynamicOps)
- Logger access$000()
+ Map lambda$addActivityAndRemoveMemoriesWhenStopped$1(Integer)
- Map lambda$addActivityAndRemoveMemoriesWhenStopped$2(Integer)
+ Object serialize(DynamicOps)
+ Set lambda$addActivityAndRemoveMemoriesWhenStopped$2(Activity)
- Set lambda$addActivityAndRemoveMemoriesWhenStopped$3(Activity)
- Stream access$200(Brain)
- Stream memories()
- void <clinit>()
+ void <init>(Collection,Collection,Dynamic)
- void <init>(Collection,Collection,ImmutableList,Supplier)
- void access$500(Brain,MemoryModuleType,Optional)
+ void readMemory(MemoryModuleType,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.MeleeAttackGoal
</summary>

```diff
- boolean isTimeToAttack()
- int getAttackInterval()
- int getTicksUntilNextAttack()
- void resetAttackCooldown()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.gossip.GossipContainer
</summary>

```diff
+ Dynamic lambda$store$6(DynamicOps,GossipContainer$GossipEntry)
- Dynamic lambda$store$6(DynamicOps,GossipContainer$GossipEntry)
+ Dynamic store(DynamicOps)
- Dynamic store(DynamicOps)
- Stream lambda$update$7(DataResult)
+ void lambda$update$7(GossipContainer$GossipEntry)
- void lambda$update$8(GossipContainer$GossipEntry)
+ void update(Dynamic)
- void update(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.memory.ExpirableValue
</summary>

```diff
- App lambda$codec$3(Codec,RecordCodecBuilder$Instance)
- Codec codec(Codec)
- ExpirableValue lambda$null$2(Object,Optional)
- Object lambda$null$0(ExpirableValue)
+ Object serialize(DynamicOps)
- Optional lambda$null$1(ExpirableValue)
+ void <init>(Function,Dynamic)
+ void <init>(Object)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiSection
</summary>

```diff
- App lambda$codec$2(Runnable,RecordCodecBuilder$Instance)
+ boolean lambda$getRecords$1(Predicate,Map$Entry)
- boolean lambda$getRecords$4(Predicate,Map$Entry)
- Boolean lambda$null$0(PoiSection)
- Codec codec(Runnable)
- List lambda$null$1(PoiSection)
+ Object lambda$add$3(PoiType)
+ Object lambda$add$4(BlockPos)
- Object lambda$add$6(PoiType)
- Object lambda$add$7(BlockPos)
+ Object lambda$serialize$6(DynamicOps,PoiRecord)
+ Object serialize(DynamicOps)
+ PoiRecord lambda$null$7(BlockPos,PoiType,int)
- PoiRecord lambda$null$9(BlockPos,PoiType,int)
- PoiSection lambda$codec$3(Runnable)
+ Set lambda$add$5(PoiType)
- Set lambda$add$8(PoiType)
+ Stream lambda$getRecords$2(Map$Entry)
- Stream lambda$getRecords$5(Map$Entry)
- void <init>(Runnable,boolean,List)
+ void <init>(Runnable,Dynamic)
+ void lambda$new$0(Runnable,Dynamic)
- void lambda$refresh$10(Short2ObjectMap,BlockPos,PoiType)
+ void lambda$refresh$8(Short2ObjectMap,BlockPos,PoiType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.AbstractFish
</summary>

```diff
- void playStepSound(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractChestedHorse
</summary>

```diff
+ SoundEvent getAngrySound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Donkey
</summary>

```diff
- SoundEvent getAngrySound()
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.hoglin.HoglinAi
</summary>

```diff
- Brain makeBrain(Brain)
+ Brain makeBrain(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinAi
</summary>

```diff
+ Behavior admireHeldItem()
- Brain makeBrain(Piglin,Brain)
+ Brain makeBrain(Piglin,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
+ boolean lambda$getPlayerReputation$6(GossipType)
- boolean lambda$getPlayerReputation$7(GossipType)
+ boolean lambda$spawnGolemIfNeeded$8(long,Villager)
- boolean lambda$spawnGolemIfNeeded$9(long,Villager)
+ boolean lambda$tellWitnessesThatIWasMurdered$3(LivingEntity)
- boolean lambda$tellWitnessesThatIWasMurdered$4(LivingEntity)
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
+ int lambda$countFoodPointsInInventory$7(SimpleContainer,Map$Entry)
- int lambda$countFoodPointsInInventory$8(SimpleContainer,Map$Entry)
- void lambda$addAdditionalSaveData$3(CompoundTag,Tag)
+ void lambda$releasePoi$5(MinecraftServer,MemoryModuleType,GlobalPos)
- void lambda$releasePoi$6(MinecraftServer,MemoryModuleType,GlobalPos)
- void lambda$spawnGolemIfNeeded$10(long,Villager)
+ void lambda$spawnGolemIfNeeded$9(long,Villager)
+ void lambda$tellWitnessesThatIWasMurdered$4(ServerLevel,Entity,LivingEntity)
- void lambda$tellWitnessesThatIWasMurdered$5(ServerLevel,Entity,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.WanderingTraderSpawner
</summary>

```diff
+ BlockPos findSpawnPositionNear(BlockPos,int)
- BlockPos findSpawnPositionNear(LevelReader,BlockPos,int)
- boolean hasEnoughSpace(BlockGetter,BlockPos)
+ boolean hasEnoughSpace(BlockPos)
+ boolean spawn()
- boolean spawn(ServerLevel)
- int tick(ServerLevel,boolean,boolean)
+ void <init>(ServerLevel,ServerLevelData)
- void <init>(ServerLevelData)
+ void tick()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEnderpearl
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.item.CompassItem
</summary>

```diff
- void <clinit>()
+ void addLodestoneTags(Dimension,BlockPos,CompoundTag)
- void addLodestoneTags(RegistryAccess,DimensionType,BlockPos,CompoundTag)
- void lambda$addLodestoneTags$0(CompoundTag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Integer lambda$null$1(ItemStack)
- Item lambda$null$0(ItemStack)
+ MutableComponent lambda$expandBlockState$2(MutableComponent)
- MutableComponent lambda$expandBlockState$6(MutableComponent)
- Optional lambda$null$2(ItemStack)
+ Style lambda$getDisplayName$3(Style)
- Style lambda$getDisplayName$7(Style)
- void <init>(ItemLike,int,Optional)
+ void lambda$appendEnchantmentNames$1(List,CompoundTag,Enchantment)
- void lambda$appendEnchantmentNames$5(List,CompoundTag,Enchantment)
+ void lambda$static$0(DecimalFormat)
- void lambda$static$4(DecimalFormat)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules
</summary>

```diff
- void <init>(DynamicLike)
- void <init>(GameRules,MinecraftServer)
+ void lambda$loadFromTag$5(CompoundTag,GameRules$Key,GameRules$Value)
- void lambda$loadFromTag$5(DynamicLike,GameRules$Key,GameRules$Value)
+ void loadFromTag(CompoundTag)
- void loadFromTag(DynamicLike)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects
</summary>

```diff
- App lambda$static$8(RecordCodecBuilder$Instance)
- Integer lambda$null$0(BiomeSpecialEffects)
- Integer lambda$null$1(BiomeSpecialEffects)
- Integer lambda$null$2(BiomeSpecialEffects)
- Optional lambda$null$3(BiomeSpecialEffects)
- Optional lambda$null$4(BiomeSpecialEffects)
- Optional lambda$null$5(BiomeSpecialEffects)
- Optional lambda$null$6(BiomeSpecialEffects)
- Optional lambda$null$7(BiomeSpecialEffects)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.FixedBiomeSource
</summary>

```diff
- Biome lambda$static$0(FixedBiomeSource)
- Codec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
- App lambda$null$1(RecordCodecBuilder$Instance)
- App lambda$static$3(RecordCodecBuilder$Instance)
- boolean stable(long)
- Codec codec()
- Either lambda$null$6(MultiNoiseBiomeSource,MultiNoiseBiomeSource$Preset)
- Either lambda$null$7(MultiNoiseBiomeSource)
- Either lambda$static$8(MultiNoiseBiomeSource)
- Float lambda$getNoiseBiome$11(Biome$ClimateParameters,Pair)
+ Float lambda$getNoiseBiome$2(Biome$ClimateParameters,Pair)
- List lambda$null$2(MultiNoiseBiomeSource)
- Long lambda$null$0(MultiNoiseBiomeSource)
- MultiNoiseBiomeSource access$000(long)
- MultiNoiseBiomeSource defaultNether(long)
- MultiNoiseBiomeSource lambda$null$4(Pair)
- MultiNoiseBiomeSource lambda$static$5(Either)
+ MultiNoiseBiomeSource of(long,List)
+ Pair lambda$null$0(Biome,Biome$ClimateParameters)
- Pair lambda$null$9(Biome,Biome$ClimateParameters)
- Stream lambda$defaultNether$10(Biome)
+ Stream lambda$of$1(Biome)
- void <clinit>()
- void <init>(long,List,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.Property
</summary>

```diff
- boolean equals(Object)
- Class getValueClass()
- Codec codec()
- DataResult lambda$new$1(String)
- DataResult lambda$null$0(String)
- DataResult parseValue(DynamicOps,StateHolder,Object)
- int generateHashCode()
- int hashCode()
- StateHolder lambda$parseValue$2(StateHolder,Comparable)
- String getName()
- String toString()
- void <init>(String,Class)
```

</details>
<details>
<summary>
net.minecraft.world.level.border.WorldBorder$Settings
</summary>

```diff
+ WorldBorder$Settings read(CompoundTag,WorldBorder$Settings)
- WorldBorder$Settings read(DynamicLike,WorldBorder$Settings)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
- BitSet getOrCreateCarvingMask(GenerationStep$Carving)
+ BitSet lambda$getCarvingMask$5(GenerationStep$Carving)
- BitSet lambda$getOrCreateCarvingMask$5(GenerationStep$Carving)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
+ Dynamic writeColumn(ChunkPos,DynamicOps)
- Dynamic writeColumn(ChunkPos,DynamicOps)
+ int getVersion(Dynamic)
- int getVersion(Dynamic)
+ Object lambda$readColumn$2(long,Dynamic)
- Optional lambda$readColumn$2(long,Dynamic)
- void <init>(File,Function,Function,DataFixer,DataFixTypes,boolean)
+ void <init>(File,Serializer,BiFunction,Function,DataFixer,DataFixTypes,boolean)
- void lambda$writeColumn$4(long)
- void lambda$writeColumn$5(Map,DynamicOps,String,Object)
+ void readColumn(ChunkPos,DynamicOps,Object)
- void readColumn(ChunkPos,DynamicOps,Object)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
- Codec codec()
- DebugLevelSource lambda$static$0()
+ Stream lambda$static$0(Block)
- Stream lambda$static$1(Block)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.WorldGenSettings
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
+ Biome lambda$null$1(Dynamic)
+ Biome[] lambda$createBuffetBiomeSource$3(int)
+ BiomeSource createBuffetBiomeSource(DynamicLike,long)
- boolean stable()
+ ChunkGenerator defaultEndGenerator(long)
+ ChunkGenerator defaultNetherGenerator(long)
+ ChunkGenerator make(WorldGenSettings$LevelType,Dynamic,long)
+ CompoundTag serialize()
- DataResult guardExperimental()
+ Dynamic createBuffetSettings(WorldGenSettings$BuffetGeneratorType,Set)
+ FlatLevelGeneratorSettings parseFlatSettings()
- LinkedHashMap dimensions()
- LinkedHashMap withOverworld(LinkedHashMap,ChunkGenerator)
+ Map access$300()
+ Map generators()
- NoiseBasedChunkGenerator makeDefaultOverworld(long)
+ Object getRegistryValue(DynamicLike,Registry,Object)
+ Optional lambda$make$0(String)
- Optional lambda$null$0(WorldGenSettings)
+ Pair parseBuffetSettings()
+ Stream lambda$createBuffetBiomeSource$2(Stream)
- String lambda$create$2(String)
- void <init>(long,boolean,boolean,LinkedHashMap,Optional)
- void <init>(long,boolean,boolean,LinkedHashMap)
+ void <init>(long,boolean,boolean,WorldGenSettings$LevelType,Dynamic,ChunkGenerator,String,boolean)
+ void <init>(long,boolean,boolean,WorldGenSettings$LevelType,Dynamic,ChunkGenerator)
- WorldGenSettings create(Properties)
+ WorldGenSettings fromBuffetSettings(WorldGenSettings$BuffetGeneratorType,Set)
+ WorldGenSettings fromFlatSettings(FlatLevelGeneratorSettings)
+ WorldGenSettings read(Properties)
+ WorldGenSettings readWorldGenSettings(CompoundTag,DataFixer,int)
+ WorldGenSettings withPreset(WorldGenSettings$Preset)
+ WorldGenSettings withProvider(WorldGenSettings$LevelType,Dynamic,ChunkGenerator)
+ WorldGenSettings$Preset preset()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CaveWorldCarver
</summary>

```diff
- void <init>(Codec,int)
+ void <init>(Function,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.NetherWorldCarver
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
+ CarverConfiguration createSettings(Dynamic)
- CarverConfiguration lambda$new$1(ConfiguredWorldCarver)
- Codec configuredCodec()
- ConfiguredWorldCarver lambda$new$0(CarverConfiguration)
- void <init>(Codec,int)
+ void <init>(Function,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BambooFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature
</summary>

```diff
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,MultiJigsawConfiguration)
+ boolean supportsProjection()
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlockBlobFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlueIceFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
</summary>

```diff
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,BuriedTreasureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
+ int getLookupRange()
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,RuinedPortalConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SeagrassFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
- Boolean lambda$null$4(SpikeFeature$EndSpike)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(SpikeFeature$EndSpike)
- Integer lambda$null$1(SpikeFeature$EndSpike)
- Integer lambda$null$2(SpikeFeature$EndSpike)
- Integer lambda$null$3(SpikeFeature$EndSpike)
+ SpikeFeature$EndSpike deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpringFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
</summary>

```diff
+ boolean isSwamphut(StructureFeatureManager,BlockPos)
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,JigsawConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ConfiguredFeature lambda$null$0(WeightedConfiguredFeature)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(WeightedConfiguredFeature)
- void <clinit>()
+ WeightedConfiguredFeature deserialize(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
- void placeInChunk(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
+ void postProcess(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
</summary>

```diff
+ BlockPlacer deserialize(Dynamic)
- BlockPlacerType register(String,Codec)
+ BlockPlacerType register(String,Function)
- Codec codec()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
</summary>

```diff
- BlockPlacerType type()
- DoublePlantPlacer lambda$static$0()
+ Object serialize(DynamicOps)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
</summary>

```diff
+ BlockPileConfiguration deserialize(Dynamic)
- BlockStateProvider lambda$static$0(BlockPileConfiguration)
+ Dynamic serialize(DynamicOps)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
</summary>

```diff
+ BuriedTreasureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Float lambda$static$0(BuriedTreasureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ ColumnFeatureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(ColumnFeatureConfiguration)
- Integer lambda$null$1(ColumnFeatureConfiguration)
- Integer lambda$null$2(ColumnFeatureConfiguration)
- Integer lambda$null$3(ColumnFeatureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
</summary>

```diff
+ CountFeatureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$static$0(CountFeatureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ConfiguredDecorator lambda$null$1(DecoratedFeatureConfiguration)
- ConfiguredFeature lambda$null$0(DecoratedFeatureConfiguration)
+ DecoratedFeatureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(DeltaFeatureConfiguration)
- BlockState lambda$null$1(DeltaFeatureConfiguration)
+ DeltaFeatureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$2(DeltaFeatureConfiguration)
- Integer lambda$null$3(DeltaFeatureConfiguration)
- Integer lambda$null$4(DeltaFeatureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(DiskConfiguration)
+ DiskConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$1(DiskConfiguration)
- Integer lambda$null$2(DiskConfiguration)
- List lambda$null$3(DiskConfiguration)
+ Object lambda$serialize$0(DynamicOps,BlockState)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- BlockStateProvider lambda$null$0(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$null$1(HugeMushroomFeatureConfiguration)
+ Dynamic serialize(DynamicOps)
+ HugeMushroomFeatureConfiguration deserialize(Dynamic)
- Integer lambda$null$2(HugeMushroomFeatureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockState lambda$null$1(LayerConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(LayerConfiguration)
+ LayerConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.MultiJigsawConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ JigsawConfiguration lambda$new$0(Map$Entry)
- JigsawConfiguration lambda$new$1(Map$Entry)
- List lambda$static$0(MultiJigsawConfiguration)
+ MultiJigsawConfiguration deserialize(Dynamic)
+ Object lambda$serialize$1(DynamicOps,JigsawConfiguration)
- void <clinit>()
- void <init>(List)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ NoneDecoratorConfiguration deserialize(Dynamic)
- NoneDecoratorConfiguration lambda$static$0()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(OceanRuinConfiguration)
- Float lambda$null$2(OceanRuinConfiguration)
+ OceanRuinConfiguration deserialize(Dynamic)
- OceanRuinFeature$Type lambda$null$0(OceanRuinConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
</summary>

```diff
- boolean lambda$static$1(BlockState)
+ OreConfiguration$Predicates lambda$static$1(OreConfiguration$Predicates)
- OreConfiguration$Predicates lambda$static$2(OreConfiguration$Predicates)
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ConfiguredFeature lambda$null$0(RandomBooleanFeatureConfiguration)
- ConfiguredFeature lambda$null$1(RandomBooleanFeatureConfiguration)
+ Dynamic serialize(DynamicOps)
+ RandomBooleanFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
</summary>

```diff
- App lambda$static$11(RecordCodecBuilder$Instance)
- BlockPlacer lambda$null$1(RandomPatchConfiguration)
- BlockStateProvider lambda$null$0(RandomPatchConfiguration)
- Boolean lambda$null$10(RandomPatchConfiguration)
- Boolean lambda$null$8(RandomPatchConfiguration)
- Boolean lambda$null$9(RandomPatchConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$4(RandomPatchConfiguration)
- Integer lambda$null$5(RandomPatchConfiguration)
- Integer lambda$null$6(RandomPatchConfiguration)
- Integer lambda$null$7(RandomPatchConfiguration)
- List lambda$null$2(RandomPatchConfiguration)
- List lambda$null$3(RandomPatchConfiguration)
+ Object lambda$serialize$0(DynamicOps,Block)
+ Object lambda$serialize$1(DynamicOps,BlockState)
+ RandomPatchConfiguration deserialize(Dynamic)
- void <clinit>()
- void <init>(BlockStateProvider,BlockPlacer,List,List,int,int,int,int,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(ReplaceBlockConfiguration)
- BlockState lambda$null$1(ReplaceBlockConfiguration)
+ Dynamic serialize(DynamicOps)
+ ReplaceBlockConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Double lambda$null$1(SeagrassFeatureConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(SeagrassFeatureConfiguration)
+ SeagrassFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(SimpleBlockConfiguration)
+ Dynamic serialize(DynamicOps)
- List lambda$null$1(SimpleBlockConfiguration)
- List lambda$null$2(SimpleBlockConfiguration)
- List lambda$null$3(SimpleBlockConfiguration)
+ Object lambda$serialize$0(DynamicOps,BlockState)
+ Object lambda$serialize$1(DynamicOps,BlockState)
+ Object lambda$serialize$2(DynamicOps,BlockState)
+ SimpleBlockConfiguration deserialize(Dynamic)
- void <clinit>()
+ void <init>(BlockState,BlockState[],BlockState[],BlockState[])
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Boolean lambda$null$0(SpikeConfiguration)
+ Dynamic serialize(DynamicOps)
+ Integer lambda$deserialize$1(Dynamic)
- List lambda$null$1(SpikeConfiguration)
+ Object lambda$serialize$0(DynamicOps,SpikeFeature$EndSpike)
- Optional lambda$null$2(SpikeConfiguration)
+ SpikeConfiguration deserialize(Dynamic)
- void <clinit>()
- void <init>(boolean,List,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
</summary>

```diff
- App lambda$static$9(RecordCodecBuilder$Instance)
- BlockStateProvider lambda$null$0(TreeConfiguration)
- BlockStateProvider lambda$null$1(TreeConfiguration)
- Boolean lambda$null$7(TreeConfiguration)
+ Dynamic serialize(DynamicOps)
- FeatureSize lambda$null$4(TreeConfiguration)
- FoliagePlacer lambda$null$2(TreeConfiguration)
- Heightmap$Types lambda$null$8(TreeConfiguration)
- Integer lambda$null$6(TreeConfiguration)
- List lambda$null$5(TreeConfiguration)
+ Object lambda$serialize$0(DynamicOps,TreeDecorator)
+ TreeConfiguration deserialize(Dynamic)
+ TreeDecorator lambda$deserialize$1(Dynamic)
- TrunkPlacer lambda$null$3(TreeConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
</summary>

```diff
- Codec codec()
+ FeatureSize deserialize(Dynamic)
- FeatureSizeType register(String,Codec)
+ FeatureSizeType register(String,Function)
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- FeatureSizeType type()
- Integer lambda$null$0(TwoLayersFeatureSize)
- Integer lambda$null$1(TwoLayersFeatureSize)
- Integer lambda$null$2(TwoLayersFeatureSize)
+ Object serialize(DynamicOps)
+ OptionalInt lambda$new$0(Number)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- FoliagePlacerType type()
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- FoliagePlacerType type()
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ CarvingMaskDecoratorConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(CarvingMaskDecoratorConfiguration)
- GenerationStep$Carving lambda$null$0(CarvingMaskDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChanceHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChancePassthroughDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChorusPlantPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountBiasedRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDoubleDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountHeighmapDoubleDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountHeightmap32Decorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountTopSolidDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountWithExtraChanceHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ DepthAverageConfigation deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(DepthAverageConfigation)
- Integer lambda$null$1(DepthAverageConfigation)
- Integer lambda$null$2(DepthAverageConfigation)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FeatureDecorator
</summary>

```diff
- Codec configuredCodec()
- ConfiguredDecorator lambda$new$0(DecoratorConfiguration)
+ DecoratorConfiguration createSettings(Dynamic)
- DecoratorConfiguration lambda$new$1(ConfiguredDecorator)
- void <init>(Codec)
+ void <init>(Function)
+ void lambda$placeFeature$0(ConfiguredFeature,WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,AtomicBoolean,BlockPos)
- void lambda$placeFeature$2(ConfiguredFeature,WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,AtomicBoolean,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FrequencyChanceDecoratorConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(FrequencyChanceDecoratorConfiguration)
+ FrequencyChanceDecoratorConfiguration deserialize(Dynamic)
- Integer lambda$null$0(FrequencyChanceDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(FrequencyWithExtraChanceDecoratorConfiguration)
+ FrequencyWithExtraChanceDecoratorConfiguration deserialize(Dynamic)
- Integer lambda$null$0(FrequencyWithExtraChanceDecoratorConfiguration)
- Integer lambda$null$2(FrequencyWithExtraChanceDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseHeightmap32Decorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.ChanceRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.FireDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
</summary>

```diff
- void <clinit>()
- void lambda$addAdditionalSaveData$1(CompoundTag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
</summary>

```diff
- App lambda$static$6(RecordCodecBuilder$Instance)
- Boolean lambda$null$0(RuinedPortalPiece$Properties)
- Boolean lambda$null$2(RuinedPortalPiece$Properties)
- Boolean lambda$null$3(RuinedPortalPiece$Properties)
- Boolean lambda$null$4(RuinedPortalPiece$Properties)
- Boolean lambda$null$5(RuinedPortalPiece$Properties)
- Float lambda$null$1(RuinedPortalPiece$Properties)
+ Object serialize(DynamicOps)
- void <clinit>()
- void <init>(boolean,float,boolean,boolean,boolean,boolean)
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- IllegalArgumentException lambda$load$0(CompoundTag)
- void <clinit>()
- void lambda$save$1(CompoundTag,Tag)
+ void setProperties(int,int,int,boolean,boolean,DimensionType)
- void setProperties(int,int,int,boolean,boolean,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DerivedLevelData
</summary>

```diff
+ CompoundTag getDimensionData()
+ void setDimensionData(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
</summary>

```diff
- DataResult exportWorldGenSettings()
- DataResult lambda$exportWorldGenSettings$2(JsonElement)
+ File getDimensionPath(DimensionType)
- File getDimensionPath(ResourceKey)
- WorldData lambda$getDataTag$1(File,DataFixer)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.AttributeSupplier$Builder
+ XXX.ai.attributes.DefaultAttributes
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AnimalMakeLove
- XXX.ai.behavior.AssignProfessionFromJobSite
+ XXX.ai.behavior.BackUpIfTooClose
- XXX.ai.behavior.BecomePassiveIfMemoryPresent
+ XXX.ai.behavior.Behavior
- XXX.ai.behavior.Behavior$Status
+ XXX.ai.behavior.BehaviorUtils
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.CelebrateVillagersSurvivedRaid
- XXX.ai.behavior.CopyMemoryWithExpiry
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.GateBehavior
- XXX.ai.behavior.GateBehavior$1
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoOutsideToCelebrate
+ XXX.ai.behavior.GoToCelebrateLocation
- XXX.ai.behavior.GoToClosestVillage
+ XXX.ai.behavior.GoToWantedItem
- XXX.ai.behavior.HarvestFarmland
+ XXX.ai.behavior.InsideBrownianWalk
- XXX.ai.behavior.InteractWith
+ XXX.ai.behavior.InteractWithDoor
- XXX.ai.behavior.JumpOnBed
+ XXX.ai.behavior.LocateHidingPlace
- XXX.ai.behavior.LocateHidingPlaceDuringRaid
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MeleeAttack
- XXX.ai.behavior.Mount
+ XXX.ai.behavior.MoveToSkySeeingSpot
- XXX.ai.behavior.MoveToTargetSink
+ XXX.ai.behavior.PlayTagWithOtherKids
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunIf
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.RunSometimes
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.UpdateActivityFromSchedule
+ XXX.ai.behavior.UseBonemeal
- XXX.ai.behavior.ValidateNearbyPoi
+ XXX.ai.behavior.VictoryStroll
- XXX.ai.behavior.VillageBoundRandomStroll
+ XXX.ai.behavior.VillagerCalmDown
- XXX.ai.behavior.VillagerGoalPackages
+ XXX.ai.behavior.VillagerMakeLove
- XXX.ai.behavior.VillagerPanicTrigger
+ XXX.ai.behavior.WakeUp
- XXX.ai.behavior.WeightedList
+ XXX.ai.behavior.WeightedList$1
- XXX.ai.behavior.WeightedList$WeightedEntry
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BarrelBlockEntity
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$1
+ XXX.block.entity.BeehiveBlockEntity$BeeData
- XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ XXX.block.entity.BellBlockEntity
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JigsawBlockEntity$RuntimePiece
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$1
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickableBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
- XXX.block.grower.AbstractMegaTreeGrower
+ XXX.block.grower.AbstractTreeGrower
- XXX.block.grower.AcaciaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.AbstractStateHolder
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
- XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.client.gui.package-info
+ XXX.components.events.AbstractContainerEventHandler
- XXX.components.events.ContainerEventHandler
+ XXX.components.events.GuiEventListener
- XXX.components.events.package-info
+ XXX.components.spectator.package-info
- XXX.components.spectator.SpectatorGui
- XXX.components.toasts.AdvancementToast
+ XXX.components.toasts.package-info
+ XXX.components.toasts.RecipeToast
- XXX.components.toasts.SystemToast
+ XXX.components.toasts.SystemToast$SystemToastIds
- XXX.components.toasts.Toast
+ XXX.components.toasts.Toast$Visibility
- XXX.components.toasts.ToastComponent
+ XXX.components.toasts.ToastComponent$1
- XXX.components.toasts.ToastComponent$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
+ XXX.core.particles.package-info
- XXX.core.particles.ParticleTypes$1
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdventureAdvancements
- XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.NetherAdvancements
- XXX.data.advancements.package-info
- XXX.data.advancements.StoryAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLoot
- XXX.data.loot.ChestLoot
+ XXX.data.loot.EntityLoot
- XXX.data.loot.FishingLoot
+ XXX.data.loot.GiftLoot
- XXX.data.loot.LootTableProvider
- XXX.data.loot.package-info
+ XXX.data.loot.PiglinBarterLoot
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ModelProvider
+ XXX.data.models.package-info
+ XXX.data.recipes.FinishedRecipe
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapedRecipeBuilder$Result
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder$Result
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder$Result
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder$Result
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder$1
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BlockTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$1
- XXX.data.tags.TagsProvider$TagAppender
- XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- XXX.datafix.schemas.NamespacedSchema$1
+ XXX.datafix.schemas.V100
- XXX.datafix.schemas.V102
+ XXX.datafix.schemas.V1022
- XXX.datafix.schemas.V106
+ XXX.datafix.schemas.V107
- XXX.datafix.schemas.V1125
+ XXX.datafix.schemas.V135
- XXX.datafix.schemas.V143
+ XXX.datafix.schemas.V1451
- XXX.datafix.schemas.V1451_1
+ XXX.datafix.schemas.V1451_2
- XXX.datafix.schemas.V1451_3
+ XXX.datafix.schemas.V1451_4
- XXX.datafix.schemas.V1451_5
+ XXX.datafix.schemas.V1451_6
- XXX.datafix.schemas.V1451_7
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1466
+ XXX.datafix.schemas.V1470
- XXX.datafix.schemas.V1481
+ XXX.datafix.schemas.V1483
- XXX.datafix.schemas.V1486
+ XXX.datafix.schemas.V1510
- XXX.datafix.schemas.V1800
+ XXX.datafix.schemas.V1801
- XXX.datafix.schemas.V1904
+ XXX.datafix.schemas.V1906
- XXX.datafix.schemas.V1909
+ XXX.datafix.schemas.V1920
- XXX.datafix.schemas.V1928
+ XXX.datafix.schemas.V1929
- XXX.datafix.schemas.V1931
+ XXX.datafix.schemas.V2100
- XXX.datafix.schemas.V2501
+ XXX.datafix.schemas.V2502
- XXX.datafix.schemas.V2505
+ XXX.datafix.schemas.V2509
- XXX.datafix.schemas.V2519
+ XXX.datafix.schemas.V2522
- XXX.datafix.schemas.V2551
+ XXX.dimension.end.package-info
- XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$Provider
- XXX.feature.configurations.StructureFeatureConfiguration
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.LegacySinglePoolElement
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.ForkingTrunkPlacer
+ XXX.feature.trunkplacers.GiantTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$Effect
- XXX.font.glyphs.EmptyGlyph
+ XXX.font.glyphs.MissingGlyph
+ XXX.font.glyphs.package-info
- XXX.font.glyphs.WhiteGlyph
+ XXX.font.providers.BitmapProvider
- XXX.font.providers.BitmapProvider$1
+ XXX.font.providers.BitmapProvider$Builder
- XXX.font.providers.BitmapProvider$Glyph
+ XXX.font.providers.GlyphProviderBuilder
- XXX.font.providers.GlyphProviderBuilderType
+ XXX.font.providers.LegacyUnicodeBitmapsProvider
- XXX.font.providers.LegacyUnicodeBitmapsProvider$1
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- XXX.font.providers.package-info
+ XXX.font.providers.TrueTypeGlyphProviderBuilder
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
+ XXX.gametest.framework.GameTestSequence
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.package-info
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
- XXX.gui.components.Button$OnTooltip
+ XXX.gui.components.ChatComponent
- XXX.gui.components.Checkbox
+ XXX.gui.components.CommandSuggestions
- XXX.gui.components.CommandSuggestions$1
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.ComponentRenderUtils
+ XXX.gui.components.ContainerObjectSelectionList
- XXX.gui.components.ContainerObjectSelectionList$Entry
+ XXX.gui.components.DebugScreenOverlay
- XXX.gui.components.DebugScreenOverlay$1
+ XXX.gui.components.EditBox
- XXX.gui.components.ImageButton
+ XXX.gui.components.LerpingBossEvent
- XXX.gui.components.LerpingBossEvent$1
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionButton
- XXX.gui.components.OptionsList
+ XXX.gui.components.OptionsList$Entry
+ XXX.gui.components.package-info
- XXX.gui.components.PlayerTabOverlay
+ XXX.gui.components.PlayerTabOverlay$1
- XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
+ XXX.gui.components.ScrolledSelectionList
- XXX.gui.components.SliderButton
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TickableWidget
+ XXX.gui.components.VolumeSlider
- XXX.gui.components.Widget
- XXX.gui.font.AllMissingGlyphProvider
+ XXX.gui.font.FontManager
- XXX.gui.font.FontManager$1
+ XXX.gui.font.FontSet
- XXX.gui.font.FontTexture
+ XXX.gui.font.FontTexture$1
- XXX.gui.font.FontTexture$Node
- XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.screens.AccessibilityOptionsScreen
+ XXX.gui.screens.AlertScreen
- XXX.gui.screens.BackupConfirmScreen
+ XXX.gui.screens.BackupConfirmScreen$Listener
- XXX.gui.screens.ChatOptionsScreen
+ XXX.gui.screens.ChatScreen
- XXX.gui.screens.ChatScreen$1
+ XXX.gui.screens.ConfirmLinkScreen
- XXX.gui.screens.ConfirmScreen
+ XXX.gui.screens.ConnectScreen
- XXX.gui.screens.ConnectScreen$1
+ XXX.gui.screens.CreateBuffetWorldScreen
- XXX.gui.screens.CreateBuffetWorldScreen$1
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ XXX.gui.screens.CreateFlatWorldScreen
- XXX.gui.screens.CreateFlatWorldScreen$1
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ XXX.gui.screens.DeathScreen
- XXX.gui.screens.DemoIntroScreen
+ XXX.gui.screens.DirectJoinServerScreen
- XXX.gui.screens.DisconnectedScreen
+ XXX.gui.screens.EditServerScreen
- XXX.gui.screens.ErrorScreen
+ XXX.gui.screens.GenericDirtMessageScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingOverlay
- XXX.gui.screens.LoadingOverlay$LogoTexture
+ XXX.gui.screens.MenuScreens
- XXX.gui.screens.MenuScreens$ScreenConstructor
+ XXX.gui.screens.MouseSettingsScreen
- XXX.gui.screens.OptionsScreen
+ XXX.gui.screens.OptionsSubScreen
- XXX.gui.screens.OutOfMemoryScreen
+ XXX.gui.screens.Overlay
- XXX.gui.screens.package-info
- XXX.gui.screens.PauseScreen
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetInfo
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.Screen
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SkinCustomizationScreen
- XXX.gui.screens.SoundOptionsScreen
+ XXX.gui.screens.TitleScreen
- XXX.gui.screens.VideoSettingsScreen
+ XXX.gui.screens.WinScreen
+ XXX.level.biome.AmbientAdditionsSettings
- XXX.level.biome.AmbientMoodSettings
+ XXX.level.biome.AmbientParticleSettings
- XXX.level.biome.BadlandsBiome
+ XXX.level.biome.BadlandsPlateauBiome
- XXX.level.biome.BambooJungleBiome
+ XXX.level.biome.BambooJungleHillsBiome
- XXX.level.biome.BasaltDeltasBiome
+ XXX.level.biome.BeachBiome
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$BiomeCategory
- XXX.level.biome.Biome$BiomeTempCategory
+ XXX.level.biome.Biome$ClimateParameters
- XXX.level.biome.Biome$MobSpawnCost
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$SpawnerData
+ XXX.level.biome.BiomeDefaultFeatures
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSourceType
- XXX.level.biome.MultiNoiseBiomeSource$Preset
+ XXX.level.biome.MushroomFieldsBiome
- XXX.level.biome.MushroomFieldsShoreBiome
+ XXX.level.biome.NearestNeighborBiomeZoomer
- XXX.level.biome.NetherWastesBiome
+ XXX.level.biome.OceanBiome
- XXX.level.biome.OverworldBiomeSource
- XXX.level.biome.package-info
+ XXX.level.biome.PlainsBiome
- XXX.level.biome.RiverBiome
+ XXX.level.biome.SavannaBiome
- XXX.level.biome.SavannaPlateauBiome
+ XXX.level.biome.ShatteredSavannaBiome
- XXX.level.biome.ShatteredSavannaPlateauBiome
+ XXX.level.biome.SmallEndIslandsBiome
- XXX.level.biome.SnowyBeachBiome
+ XXX.level.biome.SnowyMountainsBiome
- XXX.level.biome.SnowyTaigaBiome
+ XXX.level.biome.SnowyTaigaHillsBiome
- XXX.level.biome.SnowyTaigaMountainsBiome
+ XXX.level.biome.SnowyTundraBiome
- XXX.level.biome.SoulSandValleyBiome
+ XXX.level.biome.StoneShoreBiome
- XXX.level.biome.SunflowerPlainsBiome
+ XXX.level.biome.SwampBiome
- XXX.level.biome.SwampHillsBiome
+ XXX.level.biome.TaigaBiome
- XXX.level.biome.TaigaHillsBiome
+ XXX.level.biome.TaigaMountainsBiome
- XXX.level.biome.TallBirchForestBiome
+ XXX.level.biome.TallBirchHillsBiome
- XXX.level.biome.TheEndBiome
+ XXX.level.biome.TheEndBiomeSource
- XXX.level.biome.TheVoidBiome
+ XXX.level.biome.WarmOceanBiome
- XXX.level.biome.WarpedForestBiome
+ XXX.level.biome.WoodedBadlandsBiome
- XXX.level.biome.WoodedHillsBiome
+ XXX.level.biome.WoodedMountainBiome
+ XXX.level.block.AbstractBannerBlock
- XXX.level.block.AbstractChestBlock
+ XXX.level.block.AbstractFurnaceBlock
- XXX.level.block.AbstractGlassBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.BambooBlock
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BannerBlock
- XXX.level.block.BarrelBlock
+ XXX.level.block.BarrierBlock
- XXX.level.block.BaseCoralFanBlock
+ XXX.level.block.BaseCoralPlantBlock
- XXX.level.block.BaseCoralPlantTypeBlock
+ XXX.level.block.BaseCoralWallFanBlock
- XXX.level.block.BaseEntityBlock
+ XXX.level.block.BaseFireBlock
- XXX.level.block.BasePressurePlateBlock
+ XXX.level.block.BaseRailBlock
- XXX.level.block.BaseRailBlock$1
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BedBlock$1
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$BlockStatePairKey
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.ChainBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$4
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.CocoaBlock$1
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.DiodeBlock
- XXX.level.block.DirectionalBlock
+ XXX.level.block.DispenserBlock
- XXX.level.block.DoorBlock
+ XXX.level.block.DoorBlock$1
- XXX.level.block.DoubleBlockCombiner
+ XXX.level.block.DoubleBlockCombiner$BlockType
- XXX.level.block.DoubleBlockCombiner$Combiner
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- XXX.level.block.DoublePlantBlock
+ XXX.level.block.DragonEggBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
+ XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
- XXX.level.block.EndRodBlock$1
- XXX.level.block.EntityBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrostedIceBlock
+ XXX.level.block.FungusBlock
- XXX.level.block.FurnaceBlock
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GrassPathBlock
+ XXX.level.block.GravelBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.GrowingPlantBlock
+ XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.GrowingPlantHeadBlock
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HayBlock
+ XXX.level.block.HoneyBlock
- XXX.level.block.HopperBlock
+ XXX.level.block.HopperBlock$1
- XXX.level.block.HorizontalDirectionalBlock
+ XXX.level.block.HugeMushroomBlock
- XXX.level.block.IceBlock
+ XXX.level.block.InfestedBlock
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LadderBlock$1
+ XXX.level.block.Lantern
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LecternBlock$1
+ XXX.level.block.LevelEvent
- XXX.level.block.LeverBlock
+ XXX.level.block.LeverBlock$1
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MelonBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
+ XXX.level.block.MushroomBlock
- XXX.level.block.MyceliumBlock
+ XXX.level.block.NetherPortalBlock
- XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherPortalBlock$PortalShape
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
+ XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PotatoBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PressurePlateBlock$Sensitivity
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailBlock$1
+ XXX.level.block.RailState
- XXX.level.block.RailState$1
- XXX.level.block.RedstoneLampBlock
+ XXX.level.block.RedStoneOreBlock
+ XXX.level.block.RedstoneTorchBlock
- XXX.level.block.RedstoneTorchBlock$Toggle
+ XXX.level.block.RedstoneWallTorchBlock
- XXX.level.block.RedStoneWireBlock
+ XXX.level.block.RedStoneWireBlock$1
- XXX.level.block.RenderShape
+ XXX.level.block.RepeaterBlock
- XXX.level.block.RespawnAnchorBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
- XXX.level.block.Seagrass
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShearableDoublePlantBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
+ XXX.level.block.SpongeBlock
- XXX.level.block.SpreadingSnowyDirtBlock
+ XXX.level.block.StainedGlassBlock
- XXX.level.block.StainedGlassPaneBlock
+ XXX.level.block.StairBlock
- XXX.level.block.StairBlock$1
+ XXX.level.block.StandingSignBlock
- XXX.level.block.StemBlock
+ XXX.level.block.StemGrownBlock
- XXX.level.block.StoneButtonBlock
+ XXX.level.block.StonecutterBlock
- XXX.level.block.StructureBlock
+ XXX.level.block.StructureBlock$1
- XXX.level.block.StructureVoidBlock
+ XXX.level.block.SugarCaneBlock
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrass
- XXX.level.block.TargetBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVines
- XXX.level.block.TwistingVinesPlant
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVines
- XXX.level.block.WeepingVinesPlant
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoodButtonBlock
+ XXX.level.block.WoolCarpetBlock
+ XXX.level.dimension.DimensionType
+ XXX.level.dimension.NetherDimension$1
- XXX.level.dimension.package-info
+ XXX.level.levelgen.ChunkGeneratorSettings
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.NetherGeneratorSettings
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseGeneratorSettings$Preset
- XXX.level.levelgen.NoiseSettings
+ XXX.level.levelgen.OverworldGeneratorSettings
- XXX.level.levelgen.StructureSettings
+ XXX.level.levelgen.TheEndLevelSource
+ XXX.level.levelgen.WorldGenSettings$1
+ XXX.level.levelgen.WorldGenSettings$LevelType
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.FlatDataLayer
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
+ XXX.level.material.FluidState
- XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$1
+ XXX.level.timers.TimerQueue$Event
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DecoratedFeature
+ XXX.levelgen.feature.DecoratedFlowerFeature
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.DesertVillagePools
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IcePatchFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.IglooFeature
- XXX.levelgen.feature.IglooFeature$FeatureStart
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.NoSurfaceOreFeature
- XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ XXX.levelgen.feature.PlainVillagePools
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomScatteredFeature
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.structure.package-info
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructureFeatureIO
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureStart$1
- XXX.levelgen.structure.SwamplandHutPiece
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.WoodlandMansionPieces
+ XXX.levelgen.structure.WoodlandMansionPieces$1
- XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.levelgen.synth.SurfaceNoise
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.CompositeEntryBase$Serializer
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$1
- XXX.loot.entries.DynamicLoot$Serializer
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EmptyLootItem$1
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$1
- XXX.loot.entries.LootItem$Serializer
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntries$Serializer
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootPoolSingletonContainer$Serializer
- XXX.loot.entries.LootTableReference
+ XXX.loot.entries.LootTableReference$1
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$1
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$Serializer
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.ApplyExplosionDecay$1
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$1
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyBlockState$Serializer
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$1
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$1
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$DataSource
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$1
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$1
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$1
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.LimitCount$1
+ XXX.loot.functions.LimitCount$Serializer
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunction$Serializer
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctions$Serializer
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$1
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$1
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$1
- XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemDamageFunction$1
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$1
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$1
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$1
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$Serializer
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.SmeltItemFunction$1
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$1
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AlternativeLootItemCondition
- XXX.loot.predicates.AlternativeLootItemCondition$1
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.BonusLevelTableCondition$1
+ XXX.loot.predicates.BonusLevelTableCondition$Serializer
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.DamageSourceCondition$1
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$1
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.InvertedLootItemCondition$1
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemCondition$Serializer
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditions$Serializer
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$1
- XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceCondition$1
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ XXX.loot.predicates.MatchTool
- XXX.loot.predicates.MatchTool$Serializer
+ XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$1
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$1
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.loot.predicates.WeatherCheck$Serializer
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.SerializableBoolean
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
- XXX.minecraft.data.package-info
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.DoubleTag$1
+ XXX.minecraft.nbt.EndTag
- XXX.minecraft.nbt.EndTag$1
+ XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.FloatTag$1
+ XXX.minecraft.nbt.IntArrayTag
- XXX.minecraft.nbt.IntArrayTag$1
+ XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$1
+ XXX.minecraft.nbt.IntTag$Cache
- XXX.minecraft.nbt.ListTag
+ XXX.minecraft.nbt.ListTag$1
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagTypes
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$PacketHolder
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.ConnectionProtocol$1
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.NarrationHelper
+ XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsBridge
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RealmsServerAddress
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FrameTimer
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.InsensitiveStringMap
- XXX.minecraft.util.IntRange
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LimitedCapacityList
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RewindableStream
+ XXX.minecraft.util.RewindableStream$1
+ XXX.minecraft.util.Serializer
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$1
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$2
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.minecraft.world.package-info
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$1
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$1
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$1
- XXX.models.blockstates.PropertyDispatch$C1
+ XXX.models.blockstates.PropertyDispatch$C2
- XXX.models.blockstates.PropertyDispatch$C3
+ XXX.models.blockstates.PropertyDispatch$C4
- XXX.models.blockstates.PropertyDispatch$C5
+ XXX.models.blockstates.PropertyDispatch$PentaFunction
- XXX.models.blockstates.PropertyDispatch$QuadFunction
+ XXX.models.blockstates.PropertyDispatch$TriFunction
- XXX.models.blockstates.PropertyValue
+ XXX.models.blockstates.Selector
- XXX.models.blockstates.Variant
+ XXX.models.blockstates.VariantProperties
- XXX.models.blockstates.VariantProperties$Rotation
+ XXX.models.blockstates.VariantProperty
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
+ XXX.models.model.ModelLocationUtils
- XXX.models.model.ModelTemplate
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
- XXX.network.chat.BaseComponent
+ XXX.network.chat.ChatType
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$ContentConsumer
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.Component$StyledContentConsumer
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.ContextAwareComponent
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ItemStackInfo
+ XXX.network.chat.KeybindComponent
- XXX.network.chat.MutableComponent
+ XXX.network.chat.NbtComponent
- XXX.network.chat.NbtComponent$BlockNbtComponent
+ XXX.network.chat.NbtComponent$EntityNbtComponent
- XXX.network.chat.NbtComponent$StorageNbtComponent
- XXX.network.chat.package-info
+ XXX.network.chat.ScoreComponent
- XXX.network.chat.SelectorComponent
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.TextColor
+ XXX.network.chat.TextComponent
- XXX.network.chat.TranslatableComponent
+ XXX.network.chat.TranslatableFormatException
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$10
- XXX.network.syncher.EntityDataSerializers$11
+ XXX.network.syncher.EntityDataSerializers$12
- XXX.network.syncher.EntityDataSerializers$13
+ XXX.network.syncher.EntityDataSerializers$14
- XXX.network.syncher.EntityDataSerializers$15
+ XXX.network.syncher.EntityDataSerializers$16
- XXX.network.syncher.EntityDataSerializers$17
+ XXX.network.syncher.EntityDataSerializers$18
- XXX.network.syncher.EntityDataSerializers$19
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.EntityDataSerializers$8
- XXX.network.syncher.EntityDataSerializers$9
+ XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.phys.shapes.ArrayVoxelShape
- XXX.phys.shapes.ArrayVoxelShape$1
+ XXX.phys.shapes.BitSetDiscreteVoxelShape
- XXX.phys.shapes.BooleanOp
+ XXX.phys.shapes.CollisionContext
- XXX.phys.shapes.CubePointRange
+ XXX.phys.shapes.CubeVoxelShape
- XXX.phys.shapes.DiscreteCubeMerger
+ XXX.phys.shapes.DiscreteVoxelShape
- XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- XXX.phys.shapes.EntityCollisionContext
+ XXX.phys.shapes.EntityCollisionContext$1
- XXX.phys.shapes.IdenticalMerger
+ XXX.phys.shapes.IndexMerger
- XXX.phys.shapes.IndexMerger$IndexConsumer
+ XXX.phys.shapes.IndirectMerger
- XXX.phys.shapes.IntPointRange
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.phys.shapes.WorldRegionIndirectVoxelShape
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddGlobalEntityPacket
+ XXX.protocol.game.ClientboundAddMobPacket
- XXX.protocol.game.ClientboundAddPaintingPacket
+ XXX.protocol.game.ClientboundAddPlayerPacket
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockBreakAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChatPacket
- XXX.protocol.game.ClientboundChunkBlocksUpdatePacket
+ XXX.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$1
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundContainerAckPacket
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomPayloadPacket
+ XXX.protocol.game.ClientboundCustomSoundPacket
- XXX.protocol.game.ClientboundDisconnectPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundKeepAlivePacket
+ XXX.protocol.game.ClientboundLevelChunkPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLoginPacket
- XXX.protocol.game.ClientboundMapItemDataPacket
+ XXX.protocol.game.ClientboundMerchantOffersPacket
- XXX.protocol.game.ClientboundMoveEntityPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket$Pos
- XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
+ XXX.protocol.game.ClientboundMoveEntityPacket$Rot
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerCombatPacket
+ XXX.protocol.game.ClientboundPlayerCombatPacket$1
- XXX.protocol.game.ClientboundPlayerCombatPacket$Event
+ XXX.protocol.game.ClientboundPlayerInfoPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket$1
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action
- XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResourcePackPacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundSetBorderPacket
+ XXX.protocol.game.ClientboundSetBorderPacket$1
- XXX.protocol.game.ClientboundSetBorderPacket$Type
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquippedItemPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesPacket
+ XXX.protocol.game.ClientboundSetTitlesPacket$Type
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerAckPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemPacket
+ XXX.protocol.game.ServerboundPlaceRecipePacket
- XXX.protocol.game.ServerboundPlayerAbilitiesPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket
- XXX.protocol.game.ServerboundPlayerActionPacket$Action
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundRecipeBookUpdatePacket
+ XXX.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.status.ClientboundPongResponsePacket
- XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundPingRequestPacket
+ XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Players$Serializer
- XXX.protocol.status.ServerStatus$Serializer
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatus$Version$Serializer
+ XXX.protocol.status.ServerStatusPacketListener
- XXX.resourcepacks.entries.package-info
+ XXX.resourcepacks.lists.AvailableResourcePackList
+ XXX.resourcepacks.lists.package-info
- XXX.resourcepacks.lists.ResourcePackList
+ XXX.resourcepacks.lists.ResourcePackList$ResourcePackEntry
- XXX.resourcepacks.lists.SelectedResourcePackList
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.screens.achievement.package-info
- XXX.screens.achievement.StatsScreen
+ XXX.screens.achievement.StatsScreen$1
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- XXX.screens.achievement.StatsScreen$ItemStatisticsList
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList
- XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ XXX.screens.achievement.StatsUpdateListener
- XXX.screens.advancements.AdvancementsScreen
+ XXX.screens.advancements.AdvancementTab
- XXX.screens.advancements.AdvancementTabType
+ XXX.screens.advancements.AdvancementTabType$1
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
+ XXX.screens.advancements.package-info
- XXX.screens.controls.ControlList
+ XXX.screens.controls.ControlList$1
- XXX.screens.controls.ControlList$CategoryEntry
+ XXX.screens.controls.ControlList$Entry
- XXX.screens.controls.ControlList$KeyEntry
+ XXX.screens.controls.ControlList$KeyEntry$1
- XXX.screens.controls.ControlList$KeyEntry$2
+ XXX.screens.controls.ControlsScreen
- XXX.screens.controls.package-info
+ XXX.screens.debug.GameModeSwitcherScreen
- XXX.screens.debug.GameModeSwitcherScreen$1
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
- XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ XXX.screens.inventory.AbstractCommandBlockEditScreen
- XXX.screens.inventory.AbstractCommandBlockEditScreen$1
+ XXX.screens.inventory.AbstractContainerScreen
- XXX.screens.inventory.AbstractFurnaceScreen
+ XXX.screens.inventory.AnvilScreen
- XXX.screens.inventory.BeaconScreen
+ XXX.screens.inventory.BeaconScreen$1
- XXX.screens.inventory.BeaconScreen$BeaconCancelButton
+ XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
- XXX.screens.inventory.BeaconScreen$BeaconPowerButton
+ XXX.screens.inventory.BeaconScreen$BeaconScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ XXX.screens.inventory.BlastFurnaceScreen
- XXX.screens.inventory.BookEditScreen
+ XXX.screens.inventory.BookEditScreen$DisplayCache
- XXX.screens.inventory.BookEditScreen$LineInfo
+ XXX.screens.inventory.BookEditScreen$Pos2i
- XXX.screens.inventory.BookViewScreen
+ XXX.screens.inventory.BookViewScreen$1
- XXX.screens.inventory.BookViewScreen$BookAccess
+ XXX.screens.inventory.BookViewScreen$WritableBookAccess
- XXX.screens.inventory.BookViewScreen$WrittenBookAccess
+ XXX.screens.inventory.BrewingStandScreen
- XXX.screens.inventory.CartographyTableScreen
+ XXX.screens.inventory.CommandBlockEditScreen
- XXX.screens.inventory.CommandBlockEditScreen$1
+ XXX.screens.inventory.ContainerScreen
- XXX.screens.inventory.CraftingScreen
+ XXX.screens.inventory.CreativeInventoryListener
- XXX.screens.inventory.CreativeModeInventoryScreen
+ XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- XXX.screens.inventory.DispenserScreen
+ XXX.screens.inventory.EffectRenderingInventoryScreen
- XXX.screens.inventory.EnchantmentNames
+ XXX.screens.inventory.EnchantmentScreen
- XXX.screens.inventory.FurnaceScreen
+ XXX.screens.inventory.GrindstoneScreen
- XXX.screens.inventory.HopperScreen
+ XXX.screens.inventory.HorseInventoryScreen
- XXX.screens.inventory.InventoryScreen
+ XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.JigsawBlockEditScreen
+ XXX.screens.inventory.JigsawBlockEditScreen$1
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.mco.package-info
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.SafetyScreen
- XXX.screens.multiplayer.ServerSelectionList
+ XXX.screens.multiplayer.ServerSelectionList$Entry
- XXX.screens.multiplayer.ServerSelectionList$LANHeader
+ XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
+ XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
- XXX.screens.recipebook.BlastingRecipeBookComponent
+ XXX.screens.recipebook.GhostRecipe
- XXX.screens.recipebook.GhostRecipe$GhostIngredient
+ XXX.screens.recipebook.OverlayRecipeComponent
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- XXX.screens.recipebook.package-info
+ XXX.screens.recipebook.RecipeBookComponent
- XXX.screens.recipebook.RecipeBookPage
+ XXX.screens.recipebook.RecipeBookTabButton
- XXX.screens.recipebook.RecipeButton
+ XXX.screens.recipebook.RecipeCollection
- XXX.screens.recipebook.RecipeShownListener
+ XXX.screens.recipebook.RecipeUpdateListener
- XXX.screens.recipebook.SmeltingRecipeBookComponent
+ XXX.screens.recipebook.SmokingRecipeBookComponent
- XXX.screens.resourcepacks.package-info
+ XXX.screens.resourcepacks.ResourcePackSelectScreen
+ XXX.screens.stream.package-info
- XXX.screens.worldselection.CreateWorldScreen
+ XXX.screens.worldselection.CreateWorldScreen$1
- XXX.screens.worldselection.CreateWorldScreen$2
+ XXX.screens.worldselection.CreateWorldScreen$3
- XXX.screens.worldselection.CreateWorldScreen$4
+ XXX.screens.worldselection.CreateWorldScreen$5
- XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode
+ XXX.screens.worldselection.EditGameRulesScreen
- XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry$1
- XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
- XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleList
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
- XXX.screens.worldselection.EditWorldScreen
+ XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.SelectWorldScreen
+ XXX.screens.worldselection.WorldGenSettingsComponent
- XXX.screens.worldselection.WorldGenSettingsComponent$1
+ XXX.screens.worldselection.WorldGenSettingsComponent$2
- XXX.screens.worldselection.WorldGenSettingsComponent$3
+ XXX.screens.worldselection.WorldGenSettingsComponent$PresetEditor
- XXX.screens.worldselection.WorldPreset$1
- XXX.screens.worldselection.WorldPreset$3
- XXX.screens.worldselection.WorldPreset$5
- XXX.screens.worldselection.WorldPreset$7
- XXX.screens.worldselection.WorldPreset$PresetEditor
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FeatureSimulator
- XXX.server.level.PlayerMap
+ XXX.state.pattern.BlockInWorld
- XXX.state.pattern.BlockPattern
+ XXX.state.pattern.BlockPattern$BlockCacheLoader
- XXX.state.pattern.BlockPattern$BlockPatternMatch
+ XXX.state.pattern.BlockPattern$PortalInfo
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AbstractProperty
- XXX.storage.loot.BinomialDistributionGenerator
+ XXX.storage.loot.BinomialDistributionGenerator$Serializer
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ConstantIntValue
- XXX.storage.loot.ConstantIntValue$Serializer
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.IntLimiter
+ XXX.storage.loot.IntLimiter$1
- XXX.storage.loot.IntLimiter$Serializer
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$1
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$DynamicDrop
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$1
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootPool$Serializer
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$1
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
- XXX.storage.loot.LootTables
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager
- XXX.storage.loot.RandomIntGenerator
+ XXX.storage.loot.RandomIntGenerators
- XXX.storage.loot.RandomValueBounds
+ XXX.storage.loot.RandomValueBounds$Serializer
- XXX.storage.loot.ValidationContext
+ XXX.storage.threaded.package-info
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructureManager
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.OminousBannerRenameFix
- XXX.util.datafix.PackedBitStorage
- XXX.world.level.LevelAccessor
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PortalForcer
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ServerTickList
+ XXX.world.level.SpawnData
- XXX.world.level.StructureFeatureManager
+ XXX.world.level.TickList
- XXX.world.level.TickNextTickData
+ XXX.world.level.TickPriority
- XXX.world.level.WorldGenLevel
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
+ XXX.world.phys.PosAndRot
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.Objective
+ XXX.world.scores.package-info
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.Score
+ XXX.world.scores.Scoreboard
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +1P
```
```
XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance +5M -5M | +2P -2P
```
```
XXX.advancements.critereon.LocationPredicate +5M -3M | +2P -1P
```
```
XXX.minecraft.client.Minecraft +4M | +2P
```
```
XXX.client.gui.GuiComponent +1M -1M
```
```
XXX.gui.chat.ChatListener +1P -1P
```
```
XXX.gui.chat.OverlayChatListener +1M -1M
```
```
XXX.gui.components.Button +5M | +2P
```
```
XXX.client.multiplayer.ClientLevel +3M
```
```
XXX.minecraft.commands.CommandSource$1 +1M -1M
```
```
XXX.minecraft.commands.SharedSuggestionProvider +1P
```
```
XXX.minecraft.core.BlockPos +3M -5M | +1P
```
```
XXX.minecraft.core.Direction$Axis +1P
```
```
XXX.minecraft.core.GlobalPos +5M -8M | +2P -1P
```
```
XXX.minecraft.core.SerializableUUID +6M -4M | +1P
```
```
XXX.minecraft.core.Vec3i +3M | +1P
```
```
XXX.core.particles.BlockParticleOption +3M
```
```
XXX.core.particles.DustParticleOptions +5M | +1P
```
```
XXX.core.particles.ItemParticleOption +3M
```
```
XXX.core.particles.ParticleType +1P
```
```
XXX.minecraft.server.Main +1M
```
```
XXX.minecraft.server.MinecraftServer +5M -4M | +1P
```
```
XXX.server.commands.LocateCommand +3M -20M
```
```
XXX.server.commands.SpreadPlayersCommand +4M -3M
```
```
XXX.server.dedicated.DedicatedPlayerList +1M -1M
```
```
XXX.server.level.ServerLevel +10M -4M | +4P -1P
```
```
XXX.server.rcon.RconConsoleSource +1M -1M
```
```
XXX.minecraft.sounds.Music +6M | +1P
```
```
XXX.minecraft.sounds.SoundEvent +2M | +1P
```
```
XXX.datafix.fixes.AddNewChoices +1M -1M
```
```
XXX.datafix.fixes.AdvancementsRenameFix +3M -3M
```
```
XXX.datafix.fixes.BedBlockEntityInjecter +2M -2M
```
```
XXX.datafix.fixes.BitStorageAlignFix +7M -7M
```
```
XXX.datafix.fixes.BlockEntityIdFix +1M -1M
```
```
XXX.datafix.fixes.BlockEntityKeepPacked +1M -1M
```
```
XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix +2M -2M
```
```
XXX.datafix.fixes.BlockEntityUUIDFix +4M -4M
```
```
XXX.datafix.fixes.BlockRenameFix +2M -2M
```
```
XXX.datafix.fixes.BlockRenameFixWithJigsaw +2M -2M
```
```
XXX.datafix.fixes.BlockStateData +3M -3M | +2P -2P
```
```
XXX.datafix.fixes.CatTypeFix +1M -1M
```
```
XXX.datafix.fixes.ChunkLightRemoveFix +1M -1M
```
```
XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk +8M -8M | +1P -1P
```
```
XXX.datafix.fixes.ChunkToProtochunkFix +8M -5M
```
```
XXX.datafix.fixes.EntityBlockStateFix +4M -4M
```
```
XXX.datafix.fixes.EntityElderGuardianSplitFix +1M -1M
```
```
XXX.datafix.fixes.EntityHealthFix +1M -1M
```
```
XXX.datafix.fixes.EntityItemFrameDirectionFix +1M -1M
```
```
XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix +3M -3M
```
```
XXX.datafix.fixes.EntityProjectileOwnerFix +5M -5M
```
```
XXX.datafix.fixes.EntityRenameFix +3M -3M
```
```
XXX.datafix.fixes.EntityShulkerColorFix +1M -1M
```
```
XXX.datafix.fixes.EntitySkeletonSplitFix +1M -1M
```
```
XXX.datafix.fixes.EntityUUIDFix +28M -28M
```
```
XXX.datafix.fixes.EntityZombieSplitFix +1M -1M
```
```
XXX.datafix.fixes.FurnaceRecipeFix +2M -2M
```
```
XXX.datafix.fixes.HeightmapRenamingFix +1M -1M
```
```
XXX.datafix.fixes.ItemSpawnEggFix +3M -2M
```
```
XXX.datafix.fixes.JigsawPropertiesFix +1M -1M
```
```
XXX.datafix.fixes.LeavesFix +1M -1M
```
```
XXX.datafix.fixes.LeavesFix$Section +3M -3M | +1P -1P
```
```
XXX.datafix.fixes.LevelFlatGeneratorInfoFix +2M -2M
```
```
XXX.datafix.fixes.MapIdFix +1M -1M
```
```
XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix +2M -2M
```
```
XXX.datafix.fixes.NewVillageFix +5M -5M
```
```
XXX.datafix.fixes.ObjectiveRenderTypeFix +2M -2M
```
```
XXX.datafix.fixes.OptionsForceVBOFix +1M -1M
```
```
XXX.datafix.fixes.OptionsKeyTranslationFix +3M -3M
```
```
XXX.datafix.fixes.PlayerUUIDFix +2M -2M
```
```
XXX.datafix.fixes.References +1P -1P
```
```
XXX.datafix.fixes.ReorganizePoi +2M -2M
```
```
XXX.datafix.fixes.SavedDataVillageCropFix +6M -6M
```
```
XXX.datafix.fixes.SimplestEntityRenameFix +2M -2M
```
```
XXX.datafix.fixes.StriderGravityFix +1M -1M
```
```
XXX.datafix.fixes.VillagerRebuildLevelAndXpFix +3M -3M
```
```
XXX.datafix.fixes.WallPropertyFix +4M -4M
```
```
XXX.datafix.fixes.ZombieVillagerRebuildXpFix +1M -1M
```
```
XXX.datafix.schemas.V99$1 +1M -1M
```
```
XXX.util.worldupdate.WorldUpgrader +6M -4M | +1P
```
```
XXX.world.entity.EntityType -1M
```
```
XXX.world.entity.LivingEntity +10M -8M
```
```
XXX.world.entity.MobCategory +1M | +1P
```
```
XXX.ai.gossip.GossipContainer$GossipEntry +3M -5M | +1P -1P
```
```
XXX.ai.memory.MemoryModuleType +2M -2M | +1P -1P
```
```
XXX.village.poi.PoiRecord +5M -2M
```
```
XXX.animal.horse.AbstractHorse +1M
```
```
XXX.animal.horse.Horse +1M
```
```
XXX.animal.horse.Llama +1M
```
```
XXX.animal.horse.Mule +2M
```
```
XXX.entity.item.ItemEntity +1M -1M
```
```
XXX.entity.monster.Zoglin +2M -1M
```
```
XXX.entity.monster.ZombieVillager +1M
```
```
XXX.monster.hoglin.Hoglin +2M -1M
```
```
XXX.entity.npc.AbstractVillager +1M -1M
```
```
XXX.entity.npc.VillagerData +4M -2M | +1P
```
```
XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds +1M -1M | +1P -1P
```
```
XXX.entity.vehicle.AbstractMinecartContainer +1M -1M
```
```
XXX.world.item.MapItem +1M -1M
```
```
XXX.world.level.BaseCommandBlock +1M -1M
```
```
XXX.world.level.Level +1M -4M | +2P -1P
```
```
XXX.level.biome.CheckerboardColumnBiomeSource +6M -1M | +3P -1P
```
```
XXX.level.biome.CrimsonForestBiome -3M
```
```
XXX.block.state.StateHolder +15M -2M | +5P -8P
```
```
XXX.level.chunk.ChunkAccess -1M
```
```
XXX.level.chunk.ChunkGenerator +9M -10M | +6P -1P
```
```
XXX.level.chunk.ImposterProtoChunk +1M
```
```
XXX.level.levelgen.FlatLevelSource +3M -7M | +1P -3P
```
```
XXX.levelgen.carver.CarverConfiguration -1P
```
```
XXX.levelgen.carver.ConfiguredWorldCarver +2M -3M | +1P
```
```
XXX.levelgen.carver.NoneCarverConfiguration +2M -2M | +2P
```
```
XXX.levelgen.carver.UnderwaterCaveWorldCarver +1M -1M
```
```
XXX.levelgen.feature.AbstractHugeMushroomFeature +1M -1M
```
```
XXX.levelgen.feature.BasaltColumnsFeature +1M -1M
```
```
XXX.levelgen.feature.BastionFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.BlockPileFeature +1M -1M
```
```
XXX.levelgen.feature.BonusChestFeature +1M -1M
```
```
XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart +2M -1M
```
```
XXX.levelgen.feature.ConfiguredFeature +1M -3M | +2P
```
```
XXX.levelgen.feature.ReplaceBlobsFeature +1M -1M
```
```
XXX.levelgen.feature.RuinedPortalFeature +1M -6M
```
```
XXX.levelgen.feature.RuinedPortalFeature$Type +1M | +1P
```
```
XXX.levelgen.feature.SeaPickleFeature +1M -1M
```
```
XXX.levelgen.feature.ShipwreckFeature +1M -6M
```
```
XXX.levelgen.feature.SimpleBlockFeature +1M -1M
```
```
XXX.levelgen.feature.StrongholdFeature +3M -9M | -4P
```
```
XXX.levelgen.feature.StructureFeature +17M -18M | +22P -2P
```
```
XXX.levelgen.feature.SwamplandHutFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.TreeFeature +1M -1M
```
```
XXX.levelgen.feature.VillageFeature +1M -7M
```
```
XXX.levelgen.feature.VinesFeature +1M -1M
```
```
XXX.levelgen.feature.WeepingVinesFeature +1M -1M
```
```
XXX.levelgen.feature.WoodlandMansionFeature +3M -7M
```
```
XXX.feature.blockplacers.BlockPlacer +2M -1M | +2P -1P
```
```
XXX.feature.blockplacers.ColumnPlacer +5M -2M | +1P
```
```
XXX.feature.blockplacers.SimpleBlockPlacer +3M -2M | +2P
```
```
XXX.feature.configurations.BlockBlobConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.BlockStateConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.ChanceRangeDecoratorConfiguration +6M -2M | +1P
```
```
XXX.feature.configurations.CountRangeDecoratorConfiguration +6M -2M | +1P
```
```
XXX.feature.configurations.DecoratorConfiguration -1P
```
```
XXX.feature.configurations.EndGatewayConfiguration +4M -6M | +1P
```
```
XXX.feature.configurations.FeatureRadiusConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.JigsawConfiguration +4M -4M | +1P
```
```
XXX.feature.configurations.MineshaftConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.NoiseDependantDecoratorConfiguration +5M -2M | +1P
```
```
XXX.feature.configurations.NoneFeatureConfiguration +2M -2M | +2P
```
```
XXX.feature.configurations.OreConfiguration +5M -2M | +1P
```
```
XXX.feature.configurations.ProbabilityFeatureConfiguration +3M -2M | +1P
```
```
XXX.feature.configurations.RandomFeatureConfiguration +4M -3M | +1P
```
```
XXX.feature.configurations.RandomRandomFeatureConfiguration +4M -3M | +1P
```
```
XXX.feature.configurations.ReplaceSpheroidConfiguration +6M -2M | +1P
```
```
XXX.feature.configurations.RuinedPortalConfiguration +2M -3M | +1P
```
```
XXX.feature.configurations.ShipwreckConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.SimpleRandomFeatureConfiguration +2M -3M | +1P
```
```
XXX.feature.configurations.SpringConfiguration +7M -3M | +1P
```
```
XXX.feature.featuresize.FeatureSize +6M -3M | +2P -1P
```
```
XXX.feature.featuresize.ThreeLayersFeatureSize +8M -3M | +1P
```
```
XXX.feature.foliageplacers.BlobFoliagePlacer +5M -2M | +1P
```
```
XXX.feature.foliageplacers.DarkOakFoliagePlacer +3M -2M | +1P
```
```
XXX.feature.foliageplacers.FoliagePlacer +7M -2M | +2P -1P
```
```
XXX.levelgen.placement.CarvingMaskDecorator +1M -1M
```
```
XXX.levelgen.placement.ChanceDecoratorConfiguration +2M -2M | +1P
```
```
XXX.levelgen.placement.ChanceHeightmapDoubleDecorator +1M -1M
```
```
XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.ConfiguredDecorator +2M -3M | +1P
```
```
XXX.levelgen.placement.CountChanceHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.CountDepthAverageDecorator +1M -1M
```
```
XXX.levelgen.placement.CountHeight64Decorator +1M -1M
```
```
XXX.levelgen.placement.CountHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.CountVeryBiasedRangeDecorator +1M -1M
```
```
XXX.levelgen.placement.DarkOakTreePlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.EmeraldPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.EndIslandPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.ForestRockPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.FrequencyDecoratorConfiguration +2M -2M | +1P
```
```
XXX.levelgen.placement.IcebergPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.LakeWaterPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration +6M -2M | +2P
```
```
XXX.levelgen.placement.NoiseHeightmapDoubleDecorator +1M -1M
```
```
XXX.levelgen.placement.RangeDecoratorConfiguration +4M -2M | +1P
```
```
XXX.levelgen.placement.TopSolidHeightMapDecorator +1M -1M
```
```
XXX.levelgen.placement.TopSolidHeightMapRangeDecorator +1M -1M
```
```
XXX.placement.nether.CountRangeDecorator +1M -1M
```
```
XXX.placement.nether.LightGemChanceDecorator +1M -1M
```
```
XXX.placement.nether.RandomCountRangeDecorator +1M -1M
```
```
XXX.levelgen.structure.IglooPieces +1M -1M
```
```
XXX.levelgen.structure.NetherFossilFeature +1M -6M
```
```
XXX.levelgen.structure.OceanRuinFeature +1M -6M
```
```
XXX.levelgen.structure.OceanRuinFeature$Type +1M | +1P
```
```
XXX.levelgen.structure.RuinedPortalPiece +3M -1M | +1P
```
```
XXX.level.storage.LevelStorageSource +8M -2M | +2P
```
```
XXX.level.storage.LevelSummary +3M -2M | +3P -10P
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
</summary>

```diff
+ boolean matches(DimensionType,DimensionType)
- boolean matches(ResourceKey,ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimension(DimensionType,DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimension(ResourceKey,ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimensionFrom(DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimensionFrom(ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimensionTo(DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimensionTo(ResourceKey)
+ void <init>(EntityPredicate$Composite,DimensionType,DimensionType)
- void <init>(EntityPredicate$Composite,ResourceKey,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate
</summary>

```diff
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
- JsonSyntaxException lambda$fromJson$2(ResourceLocation)
+ LocationPredicate inDimension(DimensionType)
- LocationPredicate inDimension(ResourceKey)
- ResourceKey lambda$fromJson$1(ResourceLocation)
+ void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,DimensionType,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
- void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,ResourceKey,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
- void lambda$serializeToJson$0(JsonObject,JsonElement)
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- boolean allowsChat()
- boolean allowsMultiplayer()
- boolean isBlocked(UUID)
- void openChatScreen(String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.GuiComponent
</summary>

```diff
- void fillGradient(Matrix4f,BufferBuilder,int,int,int,int,int,int,int)
+ void fillGradient(Matrix4f,int,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.chat.OverlayChatListener
</summary>

```diff
- void handle(ChatType,Component,UUID)
+ void handle(ChatType,Component)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.Button
</summary>

```diff
- void <clinit>()
- void <init>(int,int,int,int,Component,Button$OnPress,Button$OnTooltip)
- void lambda$static$0(Button,PoseStack,int,int)
- void renderButton(PoseStack,int,int,float)
- void renderToolTip(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
- RegistryAccess registryAccess()
- void setGameTime(long)
- void tickTime()
```

</details>
<details>
<summary>
net.minecraft.commands.CommandSource$1
</summary>

```diff
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
+ BlockPos deserialize(Dynamic)
- BlockPos lambda$null$0(int[])
- DataResult lambda$static$1(IntStream)
- IntStream lambda$static$2(BlockPos)
+ Object serialize(DynamicOps)
+ void lambda$deserialize$0(int[],int)
+ void lambda$deserialize$1(int[],int)
+ void lambda$deserialize$2(int[],int)
```

</details>
<details>
<summary>
net.minecraft.core.GlobalPos
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ DimensionType dimension()
+ GlobalPos lambda$null$0(DimensionType,BlockPos)
+ GlobalPos of(DimensionType,BlockPos)
+ GlobalPos of(Dynamic)
- GlobalPos of(ResourceKey,BlockPos)
+ IllegalArgumentException lambda$of$2()
+ Object serialize(DynamicOps)
+ Optional lambda$of$1(Dynamic,DimensionType)
- ResourceKey dimension()
- void <clinit>()
+ void <init>(DimensionType,BlockPos)
- void <init>(ResourceKey,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.core.SerializableUUID
</summary>

```diff
- DataResult lambda$static$1(IntStream)
- IntStream lambda$static$2(SerializableUUID)
+ Object serialize(DynamicOps,UUID)
+ Object serialize(DynamicOps)
- SerializableUUID lambda$null$0(int[])
+ SerializableUUID of(Dynamic)
- SerializableUUID of(Dynamic)
+ UUID readUUID(Dynamic)
- UUID readUUID(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
- DataResult lambda$static$1(IntStream)
- IntStream lambda$static$2(Vec3i)
- Vec3i lambda$null$0(int[])
```

</details>
<details>
<summary>
net.minecraft.core.particles.BlockParticleOption
</summary>

```diff
- BlockParticleOption lambda$codec$0(ParticleType,BlockState)
- BlockState lambda$codec$1(BlockParticleOption)
- Codec codec(ParticleType)
```

</details>
<details>
<summary>
net.minecraft.core.particles.DustParticleOptions
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- Float lambda$null$0(DustParticleOptions)
- Float lambda$null$1(DustParticleOptions)
- Float lambda$null$2(DustParticleOptions)
- Float lambda$null$3(DustParticleOptions)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ItemParticleOption
</summary>

```diff
- Codec codec(ParticleType)
- ItemParticleOption lambda$codec$0(ParticleType,ItemStack)
- ItemStack lambda$codec$1(ItemParticleOption)
```

</details>
<details>
<summary>
net.minecraft.server.Main
</summary>

```diff
- void forceUpgrade(LevelStorageSource$LevelStorageAccess,DataFixer,boolean,BooleanSupplier)
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- RegistryAccess registryAccess()
+ ServerLevel getLevel(DimensionType)
- ServerLevel getLevel(ResourceKey)
- void convertFromRegionFormatIfNeeded(LevelStorageSource$LevelStorageAccess)
+ void ensureLevelConversion(LevelStorageSource$LevelStorageAccess,DataFixer,boolean,boolean,BooleanSupplier)
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
+ void setInitialSpawn(ServerLevel,Dimension,ServerLevelData,boolean,boolean)
- void setInitialSpawn(ServerLevel,ServerLevelData,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.commands.LocateCommand
</summary>

```diff
+ int lambda$register$1(CommandContext)
- int lambda$register$1(Map$Entry,CommandContext)
+ int lambda$register$10(CommandContext)
+ int lambda$register$11(CommandContext)
+ int lambda$register$12(CommandContext)
+ int lambda$register$13(CommandContext)
+ int lambda$register$14(CommandContext)
+ int lambda$register$15(CommandContext)
+ int lambda$register$16(CommandContext)
+ int lambda$register$17(CommandContext)
+ int lambda$register$18(CommandContext)
+ int lambda$register$2(CommandContext)
+ int lambda$register$3(CommandContext)
+ int lambda$register$4(CommandContext)
+ int lambda$register$5(CommandContext)
+ int lambda$register$6(CommandContext)
+ int lambda$register$7(CommandContext)
+ int lambda$register$8(CommandContext)
+ int lambda$register$9(CommandContext)
+ int locate(CommandSourceStack,String)
- int locate(CommandSourceStack,StructureFeature)
+ Style lambda$showLocateResult$19(BlockPos,Style)
- Style lambda$showLocateResult$2(BlockPos,Style)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpreadPlayersCommand
</summary>

```diff
+ double setPlayerPositions(Collection,ServerLevel,SpreadPlayersCommand$Position[],boolean)
- double setPlayerPositions(Collection,ServerLevel,SpreadPlayersCommand$Position[],int,boolean)
- int lambda$register$4(CommandContext)
+ int spreadPlayers(CommandSourceStack,Vec2,float,float,boolean,Collection)
- int spreadPlayers(CommandSourceStack,Vec2,float,float,int,boolean,Collection)
- void spreadPositions(Vec2,double,ServerLevel,Random,double,double,double,double,int,SpreadPlayersCommand$Position[],boolean)
+ void spreadPositions(Vec2,double,ServerLevel,Random,double,double,double,double,SpreadPlayersCommand$Position[],boolean)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedPlayerList
</summary>

```diff
+ void <init>(DedicatedServer,PlayerDataStorage)
- void <init>(DedicatedServer,RegistryAccess$RegistryHolder,PlayerDataStorage)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ BlockPos findNearestMapFeature(String,BlockPos,int,boolean)
- BlockPos findNearestMapFeature(StructureFeature,BlockPos,int,boolean)
+ BlockPos getDimensionSpecificSpawn()
- EndDragonFight dragonFight()
- RegistryAccess registryAccess()
- void <init>(MinecraftServer,Executor,LevelStorageSource$LevelStorageAccess,ServerLevelData,DimensionType,ChunkProgressListener,ChunkGenerator,boolean,long,List,boolean)
+ void <init>(MinecraftServer,Executor,LevelStorageSource$LevelStorageAccess,ServerLevelData,DimensionType,ChunkProgressListener,ChunkGenerator,boolean,long)
- void lambda$makeObsidianPlatform$16(ServerLevel,BlockPos)
- void lambda$makeObsidianPlatform$17(ServerLevel,BlockPos)
- void makeObsidianPlatform(ServerLevel)
- void setDayTime(long)
+ void setGameTime(long)
- void tickCustomSpawners(boolean,boolean)
- void tickTime()
```

</details>
<details>
<summary>
net.minecraft.server.rcon.RconConsoleSource
</summary>

```diff
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
```

</details>
<details>
<summary>
net.minecraft.sounds.Music
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- Boolean lambda$null$3(Music)
- Integer lambda$null$1(Music)
- Integer lambda$null$2(Music)
- SoundEvent lambda$null$0(Music)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.sounds.SoundEvent
</summary>

```diff
- ResourceLocation lambda$static$0(SoundEvent)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.AddNewChoices
</summary>

```diff
+ Function lambda$cap$1(TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$cap$1(TaggedChoice$TaggedChoiceType,DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.AdvancementsRenameFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic,String,Dynamic)
- Dynamic lambda$null$0(Dynamic,String,Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Pair lambda$null$1(Dynamic,Pair)
- Pair lambda$null$1(Dynamic,Pair)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
</summary>

```diff
+ Function lambda$cap$1(DynamicOps)
- Function lambda$cap$1(DynamicOps)
+ Integer lambda$null$2(Dynamic)
- Integer lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BitStorageAlignFix
</summary>

```diff
+ Dynamic lambda$null$2(Dynamic,Dynamic)
- Dynamic lambda$null$2(Dynamic,Dynamic)
+ Dynamic lambda$null$4(Dynamic,Dynamic)
- Dynamic lambda$null$4(Dynamic,Dynamic)
+ Dynamic lambda$null$7(Dynamic,int,Dynamic)
- Dynamic lambda$null$7(Dynamic,int,Dynamic)
+ Dynamic lambda$null$8(int,Dynamic)
- Dynamic lambda$null$8(int,Dynamic)
+ Dynamic lambda$updateHeightmaps$5(Dynamic)
- Dynamic lambda$updateHeightmaps$5(Dynamic)
+ Dynamic updateBitStorage(Dynamic,Dynamic,int,int)
- Dynamic updateBitStorage(Dynamic,Dynamic,int,int)
+ Pair lambda$null$3(Dynamic,Pair)
- Pair lambda$null$3(Dynamic,Pair)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityIdFix
</summary>

```diff
+ Function lambda$makeRule$3(DynamicOps)
- Function lambda$makeRule$3(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
</summary>

```diff
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
+ Dynamic updateLine(Dynamic,String)
- Dynamic updateLine(Dynamic,String)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
</summary>

```diff
+ Dynamic lambda$updateSkull$1(Dynamic)
- Dynamic lambda$updateSkull$1(Dynamic)
+ Dynamic lambda$updateSkull$2(Dynamic,Dynamic)
- Dynamic lambda$updateSkull$2(Dynamic,Dynamic)
+ Dynamic updateConduit(Dynamic)
- Dynamic updateConduit(Dynamic)
+ Dynamic updateSkull(Dynamic)
- Dynamic updateSkull(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockRenameFix
</summary>

```diff
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic,Dynamic)
- Dynamic lambda$null$1(Dynamic,Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockStateData
</summary>

```diff
+ Dynamic getTag(int)
- Dynamic getTag(int)
+ Dynamic parse(String)
- Dynamic parse(String)
+ Dynamic upgradeBlockStateTag(Dynamic)
- Dynamic upgradeBlockStateTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.CatTypeFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
</summary>

```diff
+ Dynamic getBlock(int)
- Dynamic getBlock(int)
+ Dynamic getBlockEntity(int)
- Dynamic getBlockEntity(int)
+ Dynamic removeBlockEntity(int)
- Dynamic removeBlockEntity(int)
+ Dynamic write()
- Dynamic write()
+ void <init>(Dynamic)
- void <init>(Dynamic)
+ void lambda$null$0(Dynamic)
- void lambda$null$0(Dynamic)
+ void lambda$null$2(Dynamic)
- void lambda$null$2(Dynamic)
+ void setBlock(int,Dynamic)
- void setBlock(int,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic,int)
- Dynamic lambda$null$4(Dynamic,ShortList)
+ IllegalStateException lambda$null$2()
- IllegalStateException lambda$null$5()
- Optional lambda$null$0(Typed)
- Optional lambda$null$1(Dynamic)
- ShortArrayList lambda$null$2(int)
+ Typed lambda$makeRule$4(OpticFinder,Type,OpticFinder,Typed)
- Typed lambda$makeRule$7(OpticFinder,Type,OpticFinder,Typed)
+ Typed lambda$null$3(OpticFinder,Type,Typed)
- Typed lambda$null$6(OpticFinder,Type,Typed)
+ void lambda$null$1(List,Dynamic,Dynamic)
- void lambda$null$3(List,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityBlockStateFix
</summary>

```diff
+ Either lambda$updateFallingBlock$10(Dynamic,Either)
- Either lambda$updateFallingBlock$10(Dynamic,Either)
+ Integer lambda$null$8(Dynamic)
- Integer lambda$null$8(Dynamic)
+ Integer lambda$null$9(Dynamic,Unit)
- Integer lambda$null$9(Dynamic,Unit)
+ Pair lambda$updateBlockToBlockState$12(Dynamic,String,Pair)
- Pair lambda$updateBlockToBlockState$12(Dynamic,String,Pair)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
</summary>

```diff
+ Pair getNewNameAndTag(String,Dynamic)
- Pair getNewNameAndTag(String,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityHealthFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
</summary>

```diff
+ Dynamic doFix(Dynamic,boolean,boolean)
- Dynamic doFix(Dynamic,boolean,boolean)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
</summary>

```diff
+ Dynamic setUUID(Dynamic,long,long)
- Dynamic setUUID(Dynamic,long,long)
+ Dynamic updateItemPotion(Dynamic)
- Dynamic updateItemPotion(Dynamic)
+ Dynamic updateOwnerArrow(Dynamic)
- Dynamic updateOwnerArrow(Dynamic)
+ Dynamic updateOwnerLlamaSpit(Dynamic)
- Dynamic updateOwnerLlamaSpit(Dynamic)
+ Dynamic updateOwnerThrowable(Dynamic)
- Dynamic updateOwnerThrowable(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityRenameFix
</summary>

```diff
+ Function lambda$makeRule$1(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$makeRule$1(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
+ Pair lambda$null$0(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
- Pair lambda$null$0(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
+ Typed getEntity(Object,DynamicOps,Type)
- Typed getEntity(Object,DynamicOps,Type)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityShulkerColorFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
</summary>

```diff
+ Pair getNewNameAndTag(String,Dynamic)
- Pair getNewNameAndTag(String,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityUUIDFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$10(Dynamic)
- Dynamic lambda$null$10(Dynamic)
+ Dynamic lambda$null$11(Dynamic,Dynamic)
- Dynamic lambda$null$11(Dynamic,Dynamic)
+ Dynamic lambda$null$12(Dynamic)
- Dynamic lambda$null$12(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$5(Dynamic)
- Dynamic lambda$null$5(Dynamic)
+ Dynamic lambda$null$6(Dynamic)
- Dynamic lambda$null$6(Dynamic)
+ Dynamic lambda$updateFox$7(Dynamic,Dynamic)
- Dynamic lambda$updateFox$7(Dynamic,Dynamic)
+ Dynamic lambda$updateFox$8(Dynamic,Dynamic)
- Dynamic lambda$updateFox$8(Dynamic,Dynamic)
+ Dynamic lambda$updateLivingEntity$13(Dynamic,Dynamic)
- Dynamic lambda$updateLivingEntity$13(Dynamic,Dynamic)
+ Dynamic lambda$updateMob$9(Dynamic)
- Dynamic lambda$updateMob$9(Dynamic)
+ Dynamic lambda$updatePiglin$4(Dynamic)
- Dynamic lambda$updatePiglin$4(Dynamic)
+ Dynamic lambda$updateProjectile$14(Dynamic,Dynamic)
- Dynamic lambda$updateProjectile$14(Dynamic,Dynamic)
+ Dynamic updateAnimal(Dynamic)
- Dynamic updateAnimal(Dynamic)
+ Dynamic updateAnimalOwner(Dynamic)
- Dynamic updateAnimalOwner(Dynamic)
+ Dynamic updateAreaEffectCloud(Dynamic)
- Dynamic updateAreaEffectCloud(Dynamic)
+ Dynamic updateEntityUUID(Dynamic)
- Dynamic updateEntityUUID(Dynamic)
+ Dynamic updateEvokerFangs(Dynamic)
- Dynamic updateEvokerFangs(Dynamic)
+ Dynamic updateFox(Dynamic)
- Dynamic updateFox(Dynamic)
+ Dynamic updateHurtBy(Dynamic)
- Dynamic updateHurtBy(Dynamic)
+ Dynamic updateItem(Dynamic)
- Dynamic updateItem(Dynamic)
+ Dynamic updateLivingEntity(Dynamic)
- Dynamic updateLivingEntity(Dynamic)
+ Dynamic updateMob(Dynamic)
- Dynamic updateMob(Dynamic)
+ Dynamic updatePiglin(Dynamic)
- Dynamic updatePiglin(Dynamic)
+ Dynamic updateProjectile(Dynamic)
- Dynamic updateProjectile(Dynamic)
+ Dynamic updateShulkerBullet(Dynamic)
- Dynamic updateShulkerBullet(Dynamic)
+ Dynamic updateZombieVillager(Dynamic)
- Dynamic updateZombieVillager(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityZombieSplitFix
</summary>

```diff
+ Pair getNewNameAndTag(String,Dynamic)
- Pair getNewNameAndTag(String,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.FurnaceRecipeFix
</summary>

```diff
+ void lambda$null$4(List,int,Object)
- void lambda$null$4(List,int,Pair)
+ void lambda$updateFurnaceContents$5(Type,List,int,Dynamic)
- void lambda$updateFurnaceContents$5(Type,List,int,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.HeightmapRenamingFix
</summary>

```diff
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemSpawnEggFix
</summary>

```diff
- DataResult lambda$null$4(Type,Dynamic,String,Dynamic)
+ IllegalStateException lambda$null$4()
- IllegalStateException lambda$null$5()
+ Typed lambda$makeRule$5(OpticFinder,OpticFinder,OpticFinder,OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$6(OpticFinder,OpticFinder,OpticFinder,OpticFinder,OpticFinder,Type,Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.JigsawPropertiesFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LeavesFix
</summary>

```diff
+ Dynamic lambda$null$5(int[],Dynamic)
- Dynamic lambda$null$5(int[],Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LeavesFix$Section
</summary>

```diff
+ Dynamic lambda$write$1(Dynamic)
- Dynamic lambda$write$1(Dynamic)
+ Pair lambda$write$2(Dynamic)
- Pair lambda$write$2(Dynamic)
+ void readStorage(Dynamic)
- void readStorage(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
</summary>

```diff
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
+ Dynamic lambda$fix$1(Dynamic)
- Dynamic lambda$fix$1(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.MapIdFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
</summary>

```diff
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.NewVillageFix
</summary>

```diff
+ Dynamic lambda$null$11(Dynamic)
- Dynamic lambda$null$11(Dynamic)
+ Dynamic lambda$null$12(Dynamic)
- Dynamic lambda$null$12(Dynamic)
+ Dynamic lambda$null$5(Dynamic,Dynamic)
- Dynamic lambda$null$5(Dynamic,Dynamic)
+ Dynamic lambda$null$6(Dynamic)
- Dynamic lambda$null$6(Dynamic)
+ Dynamic lambda$null$7(Dynamic)
- Dynamic lambda$null$7(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Function lambda$makeRule$2(DynamicOps)
- Function lambda$makeRule$2(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsForceVBOFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic,Map)
- Dynamic lambda$null$1(Dynamic,Map)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Pair lambda$null$0(Dynamic,Map$Entry)
- Pair lambda$null$0(Dynamic,Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.PlayerUUIDFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ReorganizePoi
</summary>

```diff
+ Dynamic cap(Dynamic)
- Dynamic cap(Dynamic)
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$updateChildren$0(Dynamic)
- Dynamic lambda$updateChildren$0(Dynamic)
+ Dynamic updateChildren(Dynamic)
- Dynamic updateChildren(Dynamic)
+ Dynamic updateCrop(Dynamic,String)
- Dynamic updateCrop(Dynamic,String)
+ Dynamic updateDoubleField(Dynamic)
- Dynamic updateDoubleField(Dynamic)
+ Dynamic updateSingleField(Dynamic)
- Dynamic updateSingleField(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
</summary>

```diff
+ Function lambda$makeRule$2(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$makeRule$2(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
+ Function lambda$makeRule$4(DynamicOps)
- Function lambda$makeRule$4(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.StriderGravityFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
</summary>

```diff
+ Dynamic lambda$addLevel$5(int,Dynamic)
- Dynamic lambda$addLevel$5(int,Dynamic)
+ Dynamic lambda$addXpFromLevel$6(int,Dynamic)
- Dynamic lambda$addXpFromLevel$6(int,Dynamic)
+ Dynamic lambda$null$4(int,Dynamic)
- Dynamic lambda$null$4(int,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.WallPropertyFix
</summary>

```diff
+ Dynamic fixWallProperty(Dynamic,String)
- Dynamic fixWallProperty(Dynamic,String)
+ Dynamic lambda$fixWallProperty$1(Dynamic)
- Dynamic lambda$fixWallProperty$1(Dynamic)
+ Dynamic lambda$upgradeBlockStateTag$2(Dynamic)
- Dynamic lambda$upgradeBlockStateTag$2(Dynamic)
+ Dynamic upgradeBlockStateTag(Dynamic)
- Dynamic upgradeBlockStateTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
</summary>

```diff
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V99$1
</summary>

```diff
+ Object apply(DynamicOps,Object)
- Object apply(DynamicOps,Object)
```

</details>
<details>
<summary>
net.minecraft.util.worldupdate.WorldUpgrader
</summary>

```diff
+ boolean lambda$getAllChunkPos$2(File,String)
- boolean lambda$getAllChunkPos$3(File,String)
+ DimensionDataStorage lambda$work$1()
- DimensionDataStorage lambda$work$2()
- DimensionType lambda$new$0(Map$Entry)
- ImmutableMap dimensionTypes()
+ List getAllChunkPos(DimensionType)
- List getAllChunkPos(ResourceKey)
+ void lambda$new$0(Thread,Throwable)
- void lambda$new$1(Thread,Throwable)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
+ Logger access$000()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ Boolean lambda$checkBedExists$6(BlockPos)
- Boolean lambda$checkBedExists$7(BlockPos)
+ boolean lambda$isHolding$4(Item,Item)
- boolean lambda$isHolding$5(Item,Item)
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
+ Vec3 lambda$null$7(BlockPos)
- Vec3 lambda$null$8(BlockPos)
- void lambda$addAdditionalSaveData$2(CompoundTag,Tag)
+ void lambda$hurt$3(LivingEntity)
- void lambda$hurt$4(LivingEntity)
+ void lambda$stopSleeping$8(BlockPos)
- void lambda$stopSleeping$9(BlockPos)
+ void lambda$tickEffects$2(MobEffectInstance)
- void lambda$tickEffects$3(MobEffectInstance)
+ void lambda$updateFallFlying$5(LivingEntity)
- void lambda$updateFallFlying$6(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.MobCategory
</summary>

```diff
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
</summary>

```diff
- DataResult load(Dynamic)
+ Dynamic store(DynamicOps)
- Dynamic store(DynamicOps)
+ GossipContainer$GossipEntry lambda$null$0(UUID,GossipType,Number)
+ Optional lambda$load$2(Dynamic,GossipType)
+ Optional lambda$null$1(Dynamic,GossipType,UUID)
+ Optional load(Dynamic)
- void <init>(SerializableUUID,GossipType,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.memory.MemoryModuleType
</summary>

```diff
- MemoryModuleType register(String,Codec)
+ MemoryModuleType register(String,Optional)
- Optional getCodec()
+ Optional getDeserializer()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiRecord
</summary>

```diff
- App lambda$codec$3(Runnable,RecordCodecBuilder$Instance)
- BlockPos lambda$null$0(PoiRecord)
- Codec codec(Runnable)
- Integer lambda$null$2(PoiRecord)
+ Object serialize(DynamicOps)
- PoiType lambda$null$1(PoiRecord)
+ void <init>(Dynamic,Runnable)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Mule
</summary>

```diff
- SoundEvent getAngrySound()
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.ZombieVillager
</summary>

```diff
- void lambda$addAdditionalSaveData$0(CompoundTag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.AbstractVillager
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerData
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Integer lambda$null$2(VillagerData)
+ Object serialize(DynamicOps)
- VillagerProfession lambda$null$1(VillagerData)
- VillagerType lambda$null$0(VillagerData)
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
</summary>

```diff
+ void <init>(int,String,MapDecoration$Type,int,int)
- void <init>(int,StructureFeature,MapDecoration$Type,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecartContainer
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ MapItemSavedData createAndStoreSavedData(ItemStack,Level,int,int,int,boolean,boolean,DimensionType)
- MapItemSavedData createAndStoreSavedData(ItemStack,Level,int,int,int,boolean,boolean,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.level.BaseCommandBlock
</summary>

```diff
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ Dimension getDimension()
- ResourceKey dimension()
+ void setDayTime(long)
+ void setGameTime(long)
+ void tickTime()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Codec codec()
- Integer lambda$null$1(CheckerboardColumnBiomeSource)
- List lambda$null$0(CheckerboardColumnBiomeSource)
- void <clinit>()
+ void <init>(Biome[],int)
- void <init>(List,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.CrimsonForestBiome
</summary>

```diff
+ Double lambda$new$0(Random)
+ Double lambda$new$1(Random)
+ Double lambda$new$2(Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.StateHolder
</summary>

```diff
- boolean hasProperty(Property)
- Codec codec(Codec,Function)
- Codec lambda$codec$1(Function,Object)
- Collection getProperties()
- Comparable getValue(Property)
- ImmutableMap getValues()
- Map makeNeighbourValues(Property,Comparable)
- Object cycle(Property)
- Object findNextInCollection(Collection,Object)
- Object lambda$codec$0(StateHolder)
- Object setValue(Property,Comparable)
- Optional getOptionalValue(Property)
+ StateHolder setValueHelper(StateHolder,Property,String,String,String)
+ String getName(Property,Comparable)
- String toString()
- void <init>(Object,ImmutableMap,MapCodec)
- void populateNeighbours(Map)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
+ BitSet getCarvingMask(GenerationStep$Carving)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
+ Biome getCarvingOrDecorationBiome(BiomeManager,BlockPos)
+ Biome lambda$applyCarvers$0(BiomeManager,BlockPos)
+ BlockPos findNearestMapFeature(ServerLevel,String,BlockPos,int,boolean)
- BlockPos findNearestMapFeature(ServerLevel,StructureFeature,BlockPos,int,boolean)
+ boolean canGenerateStructure(StructureFeature)
- boolean hasStronghold(ChunkPos)
+ boolean isBiomeValidStartForStructure(Biome,StructureFeature)
+ ChunkGeneratorSettings getSettings()
+ FeatureConfiguration getStructureConfiguration(Biome,StructureFeature)
- StructureSettings getSettings()
- void <clinit>()
- void <init>(BiomeSource,BiomeSource,StructureSettings,long)
+ void <init>(BiomeSource,ChunkGeneratorSettings)
- void <init>(BiomeSource,StructureSettings)
- void createStructure(ConfiguredStructureFeature,StructureFeatureManager,ChunkAccess,StructureManager,long,ChunkPos,Biome)
+ void createStructures(StructureFeatureManager,BiomeManager,ChunkAccess,ChunkGenerator,StructureManager,long)
- void createStructures(StructureFeatureManager,ChunkAccess,StructureManager,long)
- void generateStrongholds()
+ void tickCustomSpawners(ServerLevel,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
- BitSet getOrCreateCarvingMask(GenerationStep$Carving)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ Biome getBiomeFromSettings()
+ Biome getCarvingOrDecorationBiome(BiomeManager,BlockPos)
+ BlockPos findNearestMapFeature(ServerLevel,String,BlockPos,int,boolean)
+ boolean canGenerateStructure(StructureFeature)
+ boolean isBiomeValidStartForStructure(Biome,StructureFeature)
- Codec codec()
+ FeatureConfiguration getStructureConfiguration(Biome,StructureFeature)
- FlatLevelGeneratorSettings settings()
- void <clinit>()
+ void tickCustomSpawners(ServerLevel,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
</summary>

```diff
+ ConfiguredWorldCarver deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- void <clinit>()
+ void <init>(WorldCarver,Dynamic)
- WorldCarver lambda$static$0(ConfiguredWorldCarver)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ NoneCarverConfiguration deserialize(Dynamic)
- NoneCarverConfiguration lambda$static$0()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,MultiJigsawConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlockPileFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BonusChestFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,BuriedTreasureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredFeature
</summary>

```diff
+ ConfiguredFeature deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Feature lambda$static$0(ConfiguredFeature)
+ void <init>(Feature,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
</summary>

```diff
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
</summary>

```diff
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SeaPickleFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature
</summary>

```diff
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature
</summary>

```diff
+ BlockPos getNearestGeneratedFeature(ServerLevel,ChunkGenerator,BlockPos,int,boolean)
+ boolean featureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome)
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
+ int getLookupRange()
+ List access$000(StrongholdFeature)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
+ void generatePositions(ChunkGenerator,long)
+ void reset()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- BlockPos getNearestGeneratedFeature(LevelReader,StructureFeatureManager,BlockPos,int,boolean,long,StructureFeatureConfiguration)
+ BlockPos getNearestGeneratedFeature(ServerLevel,ChunkGenerator,BlockPos,int,boolean)
+ boolean featureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome)
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
+ boolean isInsideBoundingFeature(StructureFeatureManager,BlockPos)
+ boolean isInsideFeature(StructureFeatureManager,BlockPos)
+ boolean lambda$getStructureAt$1(BlockPos,StructureStart)
+ boolean lambda$getStructureAt$3(boolean,BlockPos,StructureStart)
+ boolean lambda$null$2(BlockPos,StructurePiece)
+ boolean place(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean supportsProjection()
+ ChunkPos getPotentialFeatureChunk(ChunkGeneratorSettings,long,WorldgenRandom,int,int)
- ChunkPos getPotentialFeatureChunk(StructureFeatureConfiguration,long,WorldgenRandom,int,int)
- Codec configuredStructureCodec()
+ ConfiguredFeature configured(FeatureConfiguration)
- ConfiguredStructureFeature configured(FeatureConfiguration)
- ConfiguredStructureFeature lambda$new$0(FeatureConfiguration)
- FeatureConfiguration lambda$new$1(ConfiguredStructureFeature)
- GenerationStep$Decoration step()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
- List getSpecialAnimals()
- List getSpecialEnemies()
+ Object lambda$place$0(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,int,int,int,int,StructureStart)
- String getFeatureName()
- StructureFeature register(String,StructureFeature,GenerationStep$Decoration)
- StructureStart createStart(int,int,BoundingBox,int,long)
- StructureStart generate(ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,Biome,int,WorldgenRandom,StructureFeatureConfiguration,FeatureConfiguration)
+ StructureStart getStructureAt(StructureFeatureManager,BlockPos,boolean)
- StructureStart loadStaticStart(StructureManager,CompoundTag,long)
- void <init>(Codec)
+ void <init>(Function)
- void bootstrap()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.VillageFeature
</summary>

```diff
+ boolean supportsProjection()
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.VinesFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
</summary>

```diff
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
</summary>

```diff
- void <clinit>()
- void <init>()
+ void <init>(BlockPlacerType)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockPlacerType type()
- Integer lambda$null$0(ColumnPlacer)
- Integer lambda$null$1(ColumnPlacer)
+ Object serialize(DynamicOps)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
</summary>

```diff
- BlockPlacerType type()
+ Object serialize(DynamicOps)
- SimpleBlockPlacer lambda$static$0()
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ BlockBlobConfiguration deserialize(Dynamic)
- BlockState lambda$null$0(BlockBlobConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$1(BlockBlobConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
</summary>

```diff
- BlockState lambda$static$0(BlockStateConfiguration)
+ BlockStateConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ ChanceRangeDecoratorConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$0(ChanceRangeDecoratorConfiguration)
- Integer lambda$null$1(ChanceRangeDecoratorConfiguration)
- Integer lambda$null$2(ChanceRangeDecoratorConfiguration)
- Integer lambda$null$3(ChanceRangeDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ CountRangeDecoratorConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(CountRangeDecoratorConfiguration)
- Integer lambda$null$1(CountRangeDecoratorConfiguration)
- Integer lambda$null$2(CountRangeDecoratorConfiguration)
- Integer lambda$null$3(CountRangeDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ BlockPos lambda$null$1(Number,Number,Number)
- Boolean lambda$null$1(EndGatewayConfiguration)
+ Dynamic serialize(DynamicOps)
+ EndGatewayConfiguration deserialize(Dynamic)
+ Object lambda$serialize$0(DynamicOps,BlockPos)
+ Optional lambda$deserialize$3(Dynamic,Number)
- Optional lambda$null$0(EndGatewayConfiguration)
+ Optional lambda$null$2(Dynamic,Number,Number)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ FeatureRadiusConfiguration deserialize(Dynamic)
- Integer lambda$static$0(FeatureRadiusConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
+ JigsawConfiguration deserialize(Dynamic)
- ResourceLocation getStartPool()
+ String getStartPool()
- void <clinit>()
- void <init>(ResourceLocation,int)
+ void <init>(String,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Double lambda$null$0(MineshaftConfiguration)
+ Dynamic serialize(DynamicOps)
+ MineshaftConfiguration deserialize(Dynamic)
- MineshaftFeature$Type lambda$null$1(MineshaftConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Double lambda$null$0(NoiseDependantDecoratorConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$1(NoiseDependantDecoratorConfiguration)
- Integer lambda$null$2(NoiseDependantDecoratorConfiguration)
+ NoiseDependantDecoratorConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ NoneFeatureConfiguration deserialize(Dynamic)
- NoneFeatureConfiguration lambda$static$0()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- BlockState lambda$null$1(OreConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$2(OreConfiguration)
+ OreConfiguration deserialize(Dynamic)
- OreConfiguration$Predicates lambda$null$0(OreConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$0(ProbabilityFeatureConfiguration)
+ ProbabilityFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ConfiguredFeature lambda$null$1(RandomFeatureConfiguration)
+ Dynamic serialize(DynamicOps)
- List lambda$null$0(RandomFeatureConfiguration)
+ Object lambda$serialize$0(DynamicOps,WeightedConfiguredFeature)
+ RandomFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$1(RandomRandomFeatureConfiguration)
- List lambda$null$0(RandomRandomFeatureConfiguration)
+ Object lambda$serialize$0(DynamicOps,ConfiguredFeature)
+ RandomRandomFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceSpheroidConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(ReplaceSpheroidConfiguration)
- BlockState lambda$null$1(ReplaceSpheroidConfiguration)
+ Dynamic serialize(DynamicOps)
+ ReplaceSpheroidConfiguration deserialize(Dynamic)
- Vec3i lambda$null$2(ReplaceSpheroidConfiguration)
- Vec3i lambda$null$3(ReplaceSpheroidConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ RuinedPortalConfiguration deserialize(Dynamic)
- RuinedPortalFeature$Type lambda$static$0(RuinedPortalConfiguration)
- void <clinit>()
+ void <init>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
</summary>

```diff
- Boolean lambda$static$0(ShipwreckConfiguration)
+ Dynamic serialize(DynamicOps)
+ ShipwreckConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
- List lambda$static$0(SimpleRandomFeatureConfiguration)
+ Object lambda$serialize$0(DynamicOps,ConfiguredFeature)
+ SimpleRandomFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
+ Block lambda$deserialize$0(Dynamic)
- Boolean lambda$null$1(SpringConfiguration)
+ Dynamic serialize(DynamicOps)
- FluidState lambda$null$0(SpringConfiguration)
- Integer lambda$null$2(SpringConfiguration)
- Integer lambda$null$3(SpringConfiguration)
- Set lambda$null$4(SpringConfiguration)
+ SpringConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
</summary>

```diff
+ Object serialize(DynamicOps)
- Optional lambda$minClippedHeightCodec$1(OptionalInt)
- OptionalInt lambda$minClippedHeightCodec$0(Optional)
- OptionalInt lambda$minClippedHeightCodec$2(FeatureSize)
- RecordCodecBuilder minClippedHeightCodec()
- void <clinit>()
+ void <init>(FeatureSizeType,OptionalInt)
- void <init>(OptionalInt)
+ void lambda$serialize$0(ImmutableMap$Builder,DynamicOps,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
- FeatureSizeType type()
- Integer lambda$null$0(ThreeLayersFeatureSize)
- Integer lambda$null$1(ThreeLayersFeatureSize)
- Integer lambda$null$2(ThreeLayersFeatureSize)
- Integer lambda$null$3(ThreeLayersFeatureSize)
- Integer lambda$null$4(ThreeLayersFeatureSize)
+ Object serialize(DynamicOps)
+ OptionalInt lambda$new$0(Number)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- FoliagePlacerType type()
- Integer lambda$blobParts$1(BlobFoliagePlacer)
+ Object serialize(DynamicOps)
- Products$P5 blobParts(RecordCodecBuilder$Instance)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- FoliagePlacerType type()
+ Object serialize(DynamicOps)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
</summary>

```diff
- Integer lambda$foliagePlacerParts$0(FoliagePlacer)
- Integer lambda$foliagePlacerParts$1(FoliagePlacer)
- Integer lambda$foliagePlacerParts$2(FoliagePlacer)
- Integer lambda$foliagePlacerParts$3(FoliagePlacer)
+ Object serialize(DynamicOps)
- Products$P4 foliagePlacerParts(RecordCodecBuilder$Instance)
- void <clinit>()
+ void <init>(int,int,int,int,FoliagePlacerType)
- void <init>(int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
</summary>

```diff
+ ChanceDecoratorConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$static$0(ChanceDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChanceHeightmapDoubleDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChanceTopSolidHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
</summary>

```diff
+ ConfiguredDecorator deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- FeatureDecorator lambda$static$0(ConfiguredDecorator)
- void <clinit>()
+ void <init>(FeatureDecorator,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountDepthAverageDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountHeight64Decorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountVeryBiasedRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ForestRockPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FrequencyDecoratorConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ FrequencyDecoratorConfiguration deserialize(Dynamic)
- Integer lambda$static$0(FrequencyDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- Double lambda$null$1(NoiseCountFactorDecoratorConfiguration)
- Double lambda$null$2(NoiseCountFactorDecoratorConfiguration)
+ Dynamic serialize(DynamicOps)
- Heightmap$Types lambda$null$3(NoiseCountFactorDecoratorConfiguration)
- Integer lambda$null$0(NoiseCountFactorDecoratorConfiguration)
+ NoiseCountFactorDecoratorConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseHeightmapDoubleDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.RangeDecoratorConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(RangeDecoratorConfiguration)
- Integer lambda$null$1(RangeDecoratorConfiguration)
+ RangeDecoratorConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.TopSolidHeightMapRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.CountRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.LightGemChanceDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.RandomCountRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.IglooPieces
</summary>

```diff
+ void addPieces(StructureManager,BlockPos,Rotation,List,Random,NoneFeatureConfiguration)
- void addPieces(StructureManager,BlockPos,Rotation,List,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature
</summary>

```diff
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature
</summary>

```diff
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
</summary>

```diff
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
</summary>

```diff
- void <clinit>()
- void lambda$addAdditionalSaveData$0(CompoundTag,Tag)
+ void lambda$postProcess$0(Random,WorldGenLevel,BlockPos)
- void lambda$postProcess$1(Random,WorldGenLevel,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource
</summary>

```diff
- BiFunction access$800(LevelStorageSource,File,boolean)
- BiFunction levelSummaryReader(File,boolean)
- Gson access$900()
- LevelSummary lambda$levelSummaryReader$0(File,boolean,File,DataFixer)
- Object access$300(LevelStorageSource,File,BiFunction)
- Object readLevelData(File,BiFunction)
- Pair readWorldGenSettings(Dynamic,DataFixer,int)
- WorldData access$1000(File,DataFixer)
+ WorldData access$300(LevelStorageSource,File)
+ WorldData getLevelData(File)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelSummary
</summary>

```diff
- boolean experimental()
+ long getSizeOnDisk()
- void <init>(LevelSettings,LevelVersion,String,boolean,boolean,File,Lifecycle)
+ void <init>(WorldData,String,String,long,boolean,boolean,File)
- WorldGenSettings worldGenSettings()
```

</details>
</details>
<hr/>