## Comparison with [19w40a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w40a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w40a</th><th>19w41a</th></tr><tr><td>World version</td><td><pre>2208</pre></td><td><pre>2210</pre></td></tr><tr><td>Protocol version</td><td><pre>557</pre></td><td><pre>558</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">19w40a</th><th>19w41a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ block_placer_type.txt
+ block_state_provider_type.txt
+ foliage_placer_type.txt
+ tree_decorator_type.txt
```

</details>
<details>
<summary>
block
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>
<details>
<summary>
feature
</summary>

```diff
+ minecraft:acacia_tree
- minecraft:birch_tree
+ minecraft:block_pile
- minecraft:bush
- minecraft:cactus
- minecraft:dead_bush
- minecraft:default_flower
- minecraft:double_plant
+ minecraft:flower
- minecraft:forest_flower
- minecraft:general_forest_flower
- minecraft:grass
- minecraft:hay_pile
- minecraft:hell_fire
- minecraft:ice_pile
- minecraft:jungle_grass
- minecraft:jungle_tree
- minecraft:mega_pine_tree
- minecraft:melon
- minecraft:melon_pile
- minecraft:nether_spring
- minecraft:pine_tree
- minecraft:plain_flower
- minecraft:pumpkin
- minecraft:pumpkin_pile
+ minecraft:random_patch
- minecraft:reed
- minecraft:savanna_tree
- minecraft:snow_pile
- minecraft:spruce_tree
- minecraft:super_birch_tree
- minecraft:swamp_flower
- minecraft:swamp_tree
- minecraft:sweet_berry_bush
- minecraft:taiga_grass
- minecraft:waterlily
```

</details>
<details>
<summary>
item
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>
<details>
<summary>
point_of_interest_type
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.honey_block.break
+ minecraft:block.honey_block.fall
+ minecraft:block.honey_block.hit
+ minecraft:block.honey_block.place
+ minecraft:block.honey_block.slide
+ minecraft:block.honey_block.step
+ minecraft:entity.iron_golem.damage
+ minecraft:entity.iron_golem.repair
- minecraft:entity.parrot.imitate.panda
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
+ universal_tags/block_placer_type.json
+ universal_tags/block_state_provider_type.json
+ universal_tags/foliage_placer_type.json
+ universal_tags/tree_decorator_type.json
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>
<details>
<summary>
universal_tags/feature.json
</summary>

```diff
+ minecraft:acacia_tree
- minecraft:birch_tree
+ minecraft:block_pile
- minecraft:bush
- minecraft:cactus
- minecraft:dead_bush
- minecraft:default_flower
- minecraft:double_plant
+ minecraft:flower
- minecraft:forest_flower
- minecraft:general_forest_flower
- minecraft:grass
- minecraft:hay_pile
- minecraft:hell_fire
- minecraft:ice_pile
- minecraft:jungle_grass
- minecraft:jungle_tree
- minecraft:mega_pine_tree
- minecraft:melon
- minecraft:melon_pile
- minecraft:nether_spring
- minecraft:pine_tree
- minecraft:plain_flower
- minecraft:pumpkin
- minecraft:pumpkin_pile
+ minecraft:random_patch
- minecraft:reed
- minecraft:savanna_tree
- minecraft:snow_pile
- minecraft:spruce_tree
- minecraft:super_birch_tree
- minecraft:swamp_flower
- minecraft:swamp_tree
- minecraft:sweet_berry_bush
- minecraft:taiga_grass
- minecraft:waterlily
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>
<details>
<summary>
universal_tags/point_of_interest_type.json
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.honey_block.break
+ minecraft:block.honey_block.fall
+ minecraft:block.honey_block.hit
+ minecraft:block.honey_block.place
+ minecraft:block.honey_block.slide
+ minecraft:block.honey_block.step
+ minecraft:entity.iron_golem.damage
+ minecraft:entity.iron_golem.repair
- minecraft:entity.parrot.imitate.panda
```

</details>
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- bee_hive.json
+ beehive.json
+ honey_block.json
+ honeycomb_block.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ spectate.txt
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- bee_hive.json
+ beehive.json
+ honey_block.json
+ honeycomb_block.json
+ stripped_acacia_wood.json
+ stripped_birch_wood.json
+ stripped_dark_oak_wood.json
+ stripped_jungle_wood.json
+ stripped_oak_wood.json
+ stripped_spruce_wood.json
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
- block.minecraft.bee_hive: Bee hive
+ block.minecraft.beehive: Beehive
+ block.minecraft.honey_block: Honey Block
+ block.minecraft.honeycomb_block: Honeycomb Block
+ commands.spectate.not_spectator: %s is not in spectator mode
+ commands.spectate.self: Cannot spectate yourself
+ commands.spectate.success.started: Now spectating %s
+ commands.spectate.success.stopped: No longer spectating an entity
+ options.key.hold: Hold
+ options.key.toggle: Toggle
+ subtitles.block.honey_block.slide: Sliding down a honey block
+ subtitles.entity.iron_golem.damage: Iron Golem breaks
+ subtitles.entity.iron_golem.repair: Iron Golem repaired
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/stripped_acacia_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_birch_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_dark_oak_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_jungle_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_oak_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_spruce_wood.json
- minecraft/advancements/recipes/decorations/bee_hive.json
+ minecraft/advancements/recipes/decorations/beehive.json
+ minecraft/advancements/recipes/decorations/honey_block.json
+ minecraft/advancements/recipes/decorations/honeycomb_block.json
- minecraft/loot_tables/blocks/bee_hive.json
+ minecraft/loot_tables/blocks/beehive.json
+ minecraft/loot_tables/blocks/honey_block.json
+ minecraft/loot_tables/blocks/honeycomb_block.json
- minecraft/recipes/bee_hive.json
+ minecraft/recipes/beehive.json
+ minecraft/recipes/honey_block.json
+ minecraft/recipes/honeycomb_block.json
+ minecraft/recipes/stripped_acacia_wood.json
+ minecraft/recipes/stripped_birch_wood.json
+ minecraft/recipes/stripped_dark_oak_wood.json
+ minecraft/recipes/stripped_jungle_wood.json
+ minecraft/recipes/stripped_oak_wood.json
+ minecraft/recipes/stripped_spruce_wood.json
- minecraft/tags/blocks/dirt_like.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/bee_hive.json
+ minecraft/blockstates/beehive.json
+ minecraft/blockstates/honey_block.json
+ minecraft/blockstates/honeycomb_block.json
- minecraft/models/block/bee_hive_honey.json
- minecraft/models/block/bee_hive.json
+ minecraft/models/block/beehive_honey.json
+ minecraft/models/block/beehive.json
+ minecraft/models/block/honey_block.json
+ minecraft/models/block/honeycomb_block.json
- minecraft/models/item/bee_hive.json
+ minecraft/models/item/beehive.json
+ minecraft/models/item/honey_block.json
+ minecraft/models/item/honeycomb_block.json
- minecraft/textures/block/bee_hive_end.png
- minecraft/textures/block/bee_hive_front_honey.png
- minecraft/textures/block/bee_hive_front.png
- minecraft/textures/block/bee_hive_side.png
+ minecraft/textures/block/beehive_end.png
+ minecraft/textures/block/beehive_front_honey.png
+ minecraft/textures/block/beehive_front.png
+ minecraft/textures/block/beehive_side.png
+ minecraft/textures/block/honey_block_bottom.png
+ minecraft/textures/block/honey_block_side.png
+ minecraft/textures/block/honey_block_top.png
+ minecraft/textures/block/honeycomb_block.png
- minecraft/textures/entity/iron_golem.png
+ minecraft/textures/entity/iron_golem/iron_golem_crackiness_high.png
+ minecraft/textures/entity/iron_golem/iron_golem_crackiness_low.png
+ minecraft/textures/entity/iron_golem/iron_golem_crackiness_medium.png
+ minecraft/textures/entity/iron_golem/iron_golem.png
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
+ net.minecraft.package-info
+ XXX.ai.goal.FollowOwnerFlyingGoal
- XXX.ai.goal.FollowOwnerGoal
+ XXX.ai.goal.FollowParentGoal
- XXX.ai.goal.Goal
+ XXX.ai.goal.Goal$Flag
- XXX.ai.goal.GoalSelector
+ XXX.ai.goal.GoalSelector$1
- XXX.ai.goal.GoalSelector$2
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillage
- XXX.ai.goal.MoveIndoorsGoal
+ XXX.ai.goal.MoveThroughVillageGoal
- XXX.ai.goal.MoveToBlockGoal
+ XXX.ai.goal.MoveTowardsRestrictionGoal
- XXX.ai.goal.MoveTowardsTargetGoal
+ XXX.ai.goal.OcelotAttackGoal
- XXX.ai.goal.OfferFlowerGoal
+ XXX.ai.goal.OpenDoorGoal
+ XXX.ai.goal.package-info
- XXX.ai.goal.PanicGoal
+ XXX.ai.goal.PathfindToRaidGoal
- XXX.ai.goal.PlayGoal
+ XXX.ai.goal.RandomLookAroundGoal
- XXX.ai.goal.RandomStrollGoal
+ XXX.ai.goal.RandomSwimmingGoal
- XXX.ai.goal.RangedAttackGoal
+ XXX.ai.goal.RangedBowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- XXX.ai.goal.RemoveBlockGoal
+ XXX.ai.goal.RestrictSunGoal
- XXX.ai.goal.RunAroundLikeCrazyGoal
+ XXX.ai.goal.SitGoal
- XXX.ai.goal.StrollThroughVillageGoal
+ XXX.ai.goal.SwellGoal
- XXX.ai.goal.TakeFlowerGoal
+ XXX.ai.goal.TemptGoal
- XXX.ai.goal.TradeWithPlayerGoal
+ XXX.ai.goal.TryFindWaterGoal
- XXX.ai.goal.UseItemGoal
+ XXX.ai.goal.WaterAvoidingRandomFlyingGoal
- XXX.ai.goal.WaterAvoidingRandomStrollGoal
+ XXX.ai.goal.WrappedGoal
- XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$1
- XXX.ai.gossip.GossipContainer$EntityGossips
+ XXX.ai.gossip.GossipContainer$GossipEntry
- XXX.ai.gossip.GossipType
+ XXX.ai.gossip.package-info
- XXX.ai.memory.MemoryModuleType
+ XXX.ai.memory.MemoryStatus
+ XXX.ai.memory.package-info
- XXX.ai.memory.WalkTarget
- XXX.ai.navigation.FlyingPathNavigation
+ XXX.ai.navigation.GroundPathNavigation
+ XXX.ai.navigation.package-info
- XXX.ai.navigation.PathNavigation
+ XXX.ai.navigation.WallClimberNavigation
- XXX.ai.navigation.WaterBoundPathNavigation
+ XXX.ai.sensing.DummySensor
- XXX.ai.sensing.GolemSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.InteractableDoorsSensor
+ XXX.ai.sensing.NearestBedSensor
- XXX.ai.sensing.NearestLivingEntitySensor
- XXX.ai.sensing.package-info
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
- XXX.ai.sensing.VillagerBabiesSensor
+ XXX.ai.sensing.VillagerHostilesSensor
- XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
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
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.AbstractStateHolder
- XXX.block.state.AbstractStateHolder$1
+ XXX.block.state.BlockState
- XXX.block.state.BlockState$1
+ XXX.block.state.BlockState$Cache
- XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
+ XXX.chunk.storage.ChunkSerializer
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.OldChunkStorage
- XXX.chunk.storage.OldChunkStorage$OldLevelChunk
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.SectionStorage
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntitySkeletonSplitFix
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveDisplayNameFix
- XXX.datafix.fixes.ObjectiveRenderTypeFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.PoiTypeRename
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
- XXX.dimension.end.TheEndDimension
- XXX.entity.ai.package-info
+ XXX.entity.ambient.AmbientCreature
- XXX.entity.ambient.Bat
+ XXX.entity.ambient.package-info
- XXX.entity.animal.AbstractFish
+ XXX.entity.animal.AbstractFish$FishMoveControl
- XXX.entity.animal.AbstractFish$FishSwimGoal
+ XXX.entity.animal.AbstractGolem
- XXX.entity.animal.AbstractSchoolingFish
+ XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- XXX.entity.animal.Animal
+ XXX.entity.animal.Bee
- XXX.entity.animal.Bee$1
+ XXX.entity.animal.Bee$BaseBeeGoal
- XXX.entity.animal.Bee$BeeAttackGoal
+ XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
- XXX.entity.animal.Bee$BeeEnterHiveGoal
+ XXX.entity.animal.Bee$BeeGoToBlockGoal
- XXX.entity.animal.Bee$BeeGoToHiveGoal
+ XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
- XXX.entity.animal.Bee$BeeGrowCropGoal
+ XXX.entity.animal.Bee$BeeHurtByOtherGoal
- XXX.entity.animal.Bee$BeeLocateHiveGoal
+ XXX.entity.animal.Bee$BeeLookControl
- XXX.entity.animal.Bee$BeePollinateGoal
+ XXX.entity.animal.Bee$BeeWanderGoal
- XXX.entity.animal.Cat
+ XXX.entity.animal.Cat$CatAvoidEntityGoal
- XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
+ XXX.entity.animal.Cat$CatTemptGoal
- XXX.entity.animal.Chicken
+ XXX.entity.animal.Cod
- XXX.entity.animal.Cow
+ XXX.entity.animal.Dolphin
- XXX.entity.animal.Dolphin$1
+ XXX.entity.animal.Dolphin$DolphinMoveControl
- XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- XXX.entity.animal.Dolphin$PlayWithItemsGoal
+ XXX.entity.animal.FlyingAnimal
- XXX.entity.animal.Fox
+ XXX.entity.animal.Fox$1
- XXX.entity.animal.Fox$DefendTrustedTargetGoal
+ XXX.entity.animal.Fox$FaceplantGoal
- XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
+ XXX.entity.animal.Fox$FoxBehaviorGoal
- XXX.entity.animal.Fox$FoxBreedGoal
+ XXX.entity.animal.Fox$FoxEatBerriesGoal
- XXX.entity.animal.Fox$FoxFloatGoal
+ XXX.entity.animal.Fox$FoxFollowParentGoal
- XXX.entity.animal.Fox$FoxGroupData
+ XXX.entity.animal.Fox$FoxLookAtPlayerGoal
- XXX.entity.animal.Fox$FoxLookControl
+ XXX.entity.animal.Fox$FoxMeleeAttackGoal
- XXX.entity.animal.Fox$FoxMoveControl
+ XXX.entity.animal.Fox$FoxPanicGoal
- XXX.entity.animal.Fox$FoxPounceGoal
+ XXX.entity.animal.Fox$FoxSearchForItemsGoal
- XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
+ XXX.entity.animal.Fox$PerchAndSearchGoal
- XXX.entity.animal.Fox$SeekShelterGoal
+ XXX.entity.animal.Fox$SleepGoal
- XXX.entity.animal.Fox$StalkPreyGoal
+ XXX.entity.animal.Fox$Type
- XXX.entity.animal.IronGolem
- XXX.feature.blockplacers.BlockPlacer
- XXX.feature.blockplacers.ColumnPlacer
- XXX.feature.blockplacers.SimpleBlockPlacer
- XXX.feature.configurations.BlockBlobConfiguration
- XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ChanceRangeDecoratorConfiguration
- XXX.feature.configurations.CountRangeDecoratorConfiguration
- XXX.feature.configurations.DecoratorConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureRadiusConfiguration
- XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
- XXX.feature.configurations.NoiseDependantDecoratorConfiguration
- XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$1
- XXX.feature.configurations.RandomRandomFeatureConfiguration
- XXX.feature.configurations.SeagrassFeatureConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SmallTreeConfiguration
- XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.VillageConfiguration
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.ForestFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
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
- XXX.goal.target.DefendVillageTargetGoal
+ XXX.goal.target.HurtByTargetGoal
- XXX.goal.target.NearestAttackableTargetGoal
+ XXX.goal.target.NearestAttackableWitchTargetGoal
- XXX.goal.target.NearestHealableRaiderTargetGoal
+ XXX.goal.target.NonTameRandomTargetGoal
- XXX.goal.target.OwnerHurtByTargetGoal
+ XXX.goal.target.OwnerHurtTargetGoal
+ XXX.goal.target.package-info
- XXX.goal.target.TargetGoal
+ XXX.layer.traits.AreaTransformer0
- XXX.layer.traits.AreaTransformer1
+ XXX.layer.traits.AreaTransformer2
- XXX.layer.traits.BishopTransformer
+ XXX.layer.traits.C0Transformer
- XXX.layer.traits.C1Transformer
+ XXX.layer.traits.CastleTransformer
- XXX.layer.traits.DimensionOffset0Transformer
+ XXX.layer.traits.DimensionOffset1Transformer
- XXX.layer.traits.DimensionTransformer
- XXX.layer.traits.package-info
+ XXX.layer.traits.PixelTransformer
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
- XXX.level.block.LogBlock
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
+ XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.ObserverBlock
- XXX.level.block.OreBlock
+ XXX.level.block.package-info
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
- XXX.level.block.SoulsandBlock
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
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoodButtonBlock
+ XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkBiomeContainer
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGeneratorFactory
- XXX.level.chunk.ChunkGeneratorType
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.FeatureAccess
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.OldDataLayer
- XXX.level.chunk.package-info
+ XXX.level.chunk.Palette
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.ProtoTickList
+ XXX.level.chunk.UpgradeData
- XXX.level.chunk.UpgradeData$1
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.Dimension
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.NetherDimension
+ XXX.level.dimension.NetherDimension$1
- XXX.level.dimension.NormalDimension
- XXX.level.dimension.package-info
+ XXX.level.levelgen.ChunkGeneratorSettings
- XXX.level.levelgen.DebugGeneratorSettings
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.NetherGeneratorSettings
+ XXX.level.levelgen.NetherLevelSource
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.OverworldGeneratorSettings
- XXX.level.levelgen.OverworldLevelSource
+ XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.TheEndGeneratorSettings
- XXX.level.levelgen.TheEndLevelSource
+ XXX.level.levelgen.WorldgenRandom
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
- XXX.level.material.Fluids
- XXX.level.material.FluidState
+ XXX.level.material.FluidStateImpl
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.Material
+ XXX.level.material.Material$Builder
- XXX.level.material.MaterialColor
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.TurtleNodeEvaluator
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SaveDataDirtyRunnable
- XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelStorage
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$1
- XXX.level.storage.LevelSummary
+ XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
- XXX.level.storage.PlayerIO
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
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.HellCaveWorldCarver
+ XXX.levelgen.carver.NoneCarverConfiguration
+ XXX.levelgen.carver.package-info
- XXX.levelgen.carver.UnderwaterCanyonWorldCarver
+ XXX.levelgen.carver.UnderwaterCaveWorldCarver
- XXX.levelgen.carver.WorldCarver
- XXX.levelgen.feature.AbstractFlowerFeature
- XXX.levelgen.feature.AbstractSmallTreeFeature
- XXX.levelgen.feature.AcaciaFeature
+ XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BigTreeFeature$FoliageCoords
+ XXX.levelgen.feature.BlockBlobConfiguration
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BushConfiguration
+ XXX.levelgen.feature.CactusFeature
+ XXX.levelgen.feature.CountFeatureConfiguration
- XXX.levelgen.feature.DarkOakFeature
+ XXX.levelgen.feature.DeadBushFeature
+ XXX.levelgen.feature.DecoratedFeatureConfiguration
- XXX.levelgen.feature.DecoratedFlowerFeature
+ XXX.levelgen.feature.DecoratorChanceRange
+ XXX.levelgen.feature.DecoratorCountRange
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.DesertVillagePools
+ XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DoublePlantFeature
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.FancyTreeFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeatureConfiguration
+ XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.ForestFlowerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GeneralForestFlowerFeature
+ XXX.levelgen.feature.GrassConfiguration
+ XXX.levelgen.feature.HellFireFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.IcebergConfiguration
+ XXX.levelgen.feature.IcePatchFeature
- XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.JungleGrassFeature
- XXX.levelgen.feature.JunglePyramidFeature
+ XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
+ XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.MelonFeature
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherFortressFeature
- XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.NetherSpringFeature
+ XXX.levelgen.feature.NoneFeatureConfiguration
+ XXX.levelgen.feature.OreConfiguration
+ XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PineFeature
+ XXX.levelgen.feature.PumpkinBlockPileFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.ReedsFeature
+ XXX.levelgen.feature.SavannaVillagePools
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.ShipwreckConfiguration
- XXX.levelgen.feature.ShipwreckFeature
+ XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SimulatedFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$1
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringConfiguration
+ XXX.levelgen.feature.SpruceFeature
- XXX.levelgen.feature.StrongholdFeature
+ XXX.levelgen.feature.StrongholdFeature$StrongholdStart
- XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.StructureFeature$StructureStartFactory
- XXX.levelgen.feature.StructurePieceType
+ XXX.levelgen.feature.SwampFlowerFeature
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.TaigaGrassFeature
+ XXX.levelgen.feature.VillageFeature
- XXX.levelgen.feature.VillageFeature$FeatureStart
+ XXX.levelgen.feature.VillagePieces
- XXX.levelgen.feature.VillagePieces$VillagePiece
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterlilyFeature
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
- XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ChanceHeightmapDecorator
- XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.ChancePassthroughDecorator
- XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
+ XXX.levelgen.placement.ChorusPlantPlacementDecorator
- XXX.levelgen.placement.ConfiguredDecorator
+ XXX.levelgen.placement.CountBiasedRangeDecorator
- XXX.levelgen.placement.CountChanceHeightmapDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.CountDepthAverageDecorator
+ XXX.levelgen.placement.CountHeighmapDoubleDecorator
- XXX.levelgen.placement.CountHeight64Decorator
+ XXX.levelgen.placement.CountHeightmap32Decorator
- XXX.levelgen.placement.CountHeightmapDecorator
+ XXX.levelgen.placement.CountTopSolidDecorator
- XXX.levelgen.placement.CountVeryBiasedRangeDecorator
+ XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- XXX.levelgen.placement.DarkOakTreePlacementDecorator
+ XXX.levelgen.placement.DecoratorCarvingMaskConfig
+ XXX.levelgen.placement.DecoratorFrequency
+ XXX.levelgen.placement.DecoratorFrequencyWithExtraChance
+ XXX.levelgen.placement.DecoratorRange
- XXX.levelgen.placement.FrequencyDecoratorConfiguration
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeChanceDecoratorConfig
+ XXX.levelgen.placement.MonsterRoomPlacementDecorator
- XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.RangeDecoratorConfiguration
+ XXX.levelgen.placement.SimpleFeatureDecorator
- XXX.levelgen.placement.TopSolidHeightMapDecorator
+ XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
- XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
+ XXX.levelgen.structure.BeardedStructureStart
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuriedTreasurePieces
+ XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.levelgen.structure.DesertPyramidPiece
+ XXX.levelgen.structure.EndCityPieces
- XXX.levelgen.structure.EndCityPieces$1
+ XXX.levelgen.structure.EndCityPieces$2
- XXX.levelgen.structure.EndCityPieces$3
+ XXX.levelgen.structure.EndCityPieces$4
- XXX.levelgen.structure.EndCityPieces$EndCityPiece
+ XXX.levelgen.structure.EndCityPieces$SectionGenerator
- XXX.levelgen.structure.IglooPieces
+ XXX.levelgen.structure.IglooPieces$IglooPiece
- XXX.levelgen.structure.JunglePyramidPiece
+ XXX.levelgen.structure.JunglePyramidPiece$1
- XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.MineShaftPieces
+ XXX.levelgen.structure.MineShaftPieces$1
- XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
- XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
+ XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
- XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
+ XXX.levelgen.structure.NetherBridgePieces
- XXX.levelgen.structure.NetherBridgePieces$1
+ XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
- XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
+ XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- XXX.levelgen.structure.NetherBridgePieces$PieceWeight
+ XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
- XXX.levelgen.structure.NetherBridgePieces$StairsRoom
+ XXX.levelgen.structure.NetherBridgePieces$StartPiece
- XXX.levelgen.structure.OceanMonumentPieces
+ XXX.levelgen.structure.OceanMonumentPieces$1
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
- XXX.levelgen.structure.OceanRuinFeature
+ XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
- XXX.levelgen.structure.OceanRuinFeature$Type
+ XXX.levelgen.structure.OceanRuinPieces
- XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PillagerOutpostPieces
- XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.ShipwreckPieces
- XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ XXX.levelgen.structure.StrongholdPieces
- XXX.levelgen.structure.StrongholdPieces$1
+ XXX.levelgen.structure.StrongholdPieces$2
- XXX.levelgen.structure.StrongholdPieces$3
+ XXX.levelgen.structure.StrongholdPieces$ChestCorridor
- XXX.levelgen.structure.StrongholdPieces$FillerCorridor
+ XXX.levelgen.structure.StrongholdPieces$FiveCrossing
- XXX.levelgen.structure.StrongholdPieces$LeftTurn
+ XXX.levelgen.structure.StrongholdPieces$Library
- XXX.levelgen.structure.StrongholdPieces$PieceWeight
+ XXX.levelgen.structure.StrongholdPieces$PortalRoom
- XXX.levelgen.structure.StrongholdPieces$PrisonHall
+ XXX.levelgen.structure.StrongholdPieces$RightTurn
- XXX.levelgen.structure.StrongholdPieces$RoomCrossing
+ XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- XXX.levelgen.structure.StrongholdPieces$StairsDown
+ XXX.levelgen.structure.StrongholdPieces$StartPiece
- XXX.levelgen.structure.StrongholdPieces$Straight
+ XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.levelgen.structure.StrongholdPieces$Turn
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
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
- XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
+ XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.levelgen.synth.SurfaceNoise
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
- XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
- XXX.minecraft.resources.package-info
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$1
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.ConsoleInputSource
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.MinecraftServer$3
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.TickTask
+ XXX.minecraft.world.package-info
+ XXX.network.chat.BaseComponent
- XXX.network.chat.ChatType
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.Component
- XXX.network.chat.Component$1
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.ContextAwareComponent
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.KeybindComponent
+ XXX.network.chat.NbtComponent
- XXX.network.chat.NbtComponent$BlockNbtComponent
+ XXX.network.chat.NbtComponent$EntityNbtComponent
- XXX.network.chat.NbtComponent$StorageNbtComponent
+ XXX.network.chat.package-info
+ XXX.network.chat.ScoreComponent
- XXX.network.chat.SelectorComponent
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.TextComponent
+ XXX.network.chat.TranslatableComponent
- XXX.network.chat.TranslatableFormatException
+ XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
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
- XXX.newbiome.area.Area
+ XXX.newbiome.area.AreaFactory
- XXX.newbiome.area.LazyArea
+ XXX.newbiome.area.package-info
- XXX.newbiome.context.BigContext
+ XXX.newbiome.context.Context
- XXX.newbiome.context.LazyAreaContext
+ XXX.newbiome.context.package-info
- XXX.newbiome.layer.AddDeepOceanLayer
+ XXX.newbiome.layer.AddEdgeLayer
- XXX.newbiome.layer.AddEdgeLayer$CoolWarm
+ XXX.newbiome.layer.AddEdgeLayer$HeatIce
- XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
+ XXX.newbiome.layer.AddIslandLayer
- XXX.newbiome.layer.AddMushroomIslandLayer
+ XXX.newbiome.layer.AddSnowLayer
- XXX.newbiome.layer.BiomeEdgeLayer
+ XXX.newbiome.layer.BiomeInitLayer
- XXX.newbiome.layer.IslandLayer
+ XXX.newbiome.layer.Layer
- XXX.newbiome.layer.Layers
+ XXX.newbiome.layer.OceanLayer
- XXX.newbiome.layer.OceanMixerLayer
- XXX.newbiome.layer.package-info
+ XXX.newbiome.layer.RareBiomeLargeLayer
- XXX.newbiome.layer.RareBiomeSpotLayer
+ XXX.newbiome.layer.RegionHillsLayer
- XXX.newbiome.layer.RemoveTooMuchOceanLayer
+ XXX.newbiome.layer.RiverInitLayer
- XXX.newbiome.layer.RiverLayer
+ XXX.newbiome.layer.RiverMixerLayer
- XXX.newbiome.layer.ShoreLayer
+ XXX.newbiome.layer.SmoothLayer
- XXX.newbiome.layer.ZoomLayer
+ XXX.newbiome.layer.ZoomLayer$1
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
+ XXX.placement.nether.ChanceRangeDecorator
- XXX.placement.nether.CountRangeDecorator
+ XXX.placement.nether.HellFireDecorator
- XXX.placement.nether.LightGemChanceDecorator
+ XXX.placement.nether.MagmaDecorator
+ XXX.placement.nether.package-info
- XXX.placement.nether.RandomCountRangeDecorator
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
+ XXX.protocol.game.ClientboundSetSpawnPositionPacket
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
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.DebugVillagerNameGenerator
- XXX.protocol.game.package-info
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
- XXX.protocol.game.ServerGamePacketListener
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
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$1
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$Mode
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
- XXX.server.commands.GameModeCommand
+ XXX.server.commands.GameRuleCommand
- XXX.server.commands.GameRuleCommand$1
+ XXX.server.commands.GiveCommand
- XXX.server.commands.HelpCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LootCommand
- XXX.server.commands.LootCommand$Callback
+ XXX.server.commands.LootCommand$DropConsumer
- XXX.server.commands.LootCommand$TailProvider
+ XXX.server.commands.MsgCommand
- XXX.server.commands.OpCommand
+ XXX.server.commands.PardonCommand
- XXX.server.commands.PardonIpCommand
+ XXX.server.commands.ParticleCommand
- XXX.server.commands.PlaySoundCommand
+ XXX.server.commands.PublishCommand
- XXX.server.commands.RaidCommand
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ReplaceItemCommand
- XXX.server.commands.SaveAllCommand
+ XXX.server.commands.SaveOffCommand
- XXX.server.commands.SaveOnCommand
+ XXX.server.commands.SayCommand
- XXX.server.commands.ScheduleCommand
+ XXX.server.commands.ScoreboardCommand
- XXX.server.commands.SeedCommand
+ XXX.server.commands.SetBlockCommand
- XXX.server.commands.SetBlockCommand$Filter
+ XXX.server.commands.SetBlockCommand$Mode
- XXX.server.commands.SetPlayerIdleTimeoutCommand
+ XXX.server.commands.SetSpawnCommand
- XXX.server.commands.SetWorldSpawnCommand
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
- XXX.state.properties.AttachFace
+ XXX.state.properties.BambooLeaves
- XXX.state.properties.BedPart
+ XXX.state.properties.BellAttachType
- XXX.state.properties.BlockStateProperties
+ XXX.state.properties.BooleanProperty
- XXX.state.properties.ChestType
+ XXX.state.properties.ComparatorMode
- XXX.state.properties.DirectionProperty
+ XXX.state.properties.DoorHingeSide
- XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
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
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
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
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
- XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
+ XXX.world.level.package-info
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
XXX.mojang.math.Matrix3f +1M
```
```
XXX.mojang.math.Quaternion +1M -1M
```
```
XXX.mojang.math.Vector3f +1M -1M
```
```
XXX.minecraft.core.BlockPos +1M
```
```
XXX.minecraft.core.BlockPos$MutableBlockPos +1M
```
```
XXX.server.level.ServerLevel +5M -2M
```
```
XXX.util.datafix.DataFixers +2M
```
```
XXX.world.entity.Entity +18M -1M
```
```
XXX.world.entity.FlyingMob +1M -1M
```
```
XXX.world.entity.LivingEntity +3M -1M
```
```
XXX.ai.behavior.MoveToSkySeeingSpot +1M -1M
```
```
XXX.ai.behavior.WeightedList +13M -3M
```
```
XXX.ai.behavior.WeightedList$WeightedEntry +3M
```
```
XXX.entity.animal.Ocelot +1M -1M
```
```
XXX.entity.animal.Parrot +1M -1M
```
```
XXX.animal.horse.AbstractHorse +2M -1M
```
```
XXX.animal.horse.Llama +1M -1M
```
```
XXX.boss.wither.WitherBoss +1M -1M
```
```
XXX.entity.item.FallingBlockEntity +1M -1M
```
```
XXX.entity.monster.Creeper +1M -1M
```
```
XXX.entity.monster.MagmaCube +1M -1M
```
```
XXX.level.biome.BiomeDefaultFeatures +1M | +119P
```
```
XXX.level.block.BeehiveBlock +1M -1M
```
```
XXX.level.block.Blocks +3P -1P
```
```
XXX.levelgen.feature.ChorusPlantFeature +2M -2M
```
```
XXX.levelgen.feature.DiskReplaceFeature +2M -2M
```
```
XXX.levelgen.feature.GroundBushFeature +2M -2M | -2P
```
```
XXX.levelgen.feature.HugeRedMushroomFeature +2M -2M
```
```
XXX.levelgen.feature.KelpFeature +2M -2M
```
```
XXX.levelgen.feature.MegaJungleTreeFeature +4M -4M
```
```
XXX.levelgen.feature.MegaTreeFeature +5M -4M | -4P
```
```
XXX.levelgen.feature.ReplaceBlockFeature +2M -2M
```
```
XXX.levelgen.feature.SimpleBlockFeature +2M -2M
```
```
XXX.levelgen.feature.TreeFeature +3M -8M | -6P
```
```
XXX.levelgen.placement.EmeraldPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.EndIslandPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.ForestRockPlacementDecorator +3M -3M
```
```
XXX.levelgen.placement.LakeWaterPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.NoiseHeightmapDoubleDecorator +3M -3M
```

</details>
<details>
<summary>
com.mojang.math.Matrix3f
</summary>

```diff
- void <init>(float[])
```

</details>
<details>
<summary>
com.mojang.math.Quaternion
</summary>

```diff
+ void <init>()
- void <init>(float[])
```

</details>
<details>
<summary>
com.mojang.math.Vector3f
</summary>

```diff
+ Quaternion rotation(float,boolean)
- Quaternion rotationDegrees(float)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- Stream betweenClosedStream(BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos$MutableBlockPos
</summary>

```diff
- void <init>(Entity)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- boolean lambda$clearBlockEvents$15(BoundingBox,BlockEventData)
- void clearBlockEvents(BoundingBox)
- void lambda$tick$6(Entity)
+ void lambda$tick$6(ServerPlayer)
+ void lambda$tick$7(Entity)
- void lambda$wakeUpAllPlayers$7(ServerPlayer)
- void wakeUpAllPlayers()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.DataFixers
</summary>

```diff
- String lambda$addFixers$24(String)
- String lambda$addFixers$25(String)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- BlockPos getBlockPosBelowThatAffectsMyMovement()
- BlockPos getOnPos()
- boolean causeFallDamage(float,float)
- Component getTypeName()
- double getEyeY()
- double getRandomX(double)
- double getRandomY()
- double getRandomZ(double)
- double getX()
- double getX(double)
- double getY()
- double getY(double)
- double getZ()
- double getZ(double)
- float getJumpFactor()
- float getSpeedFactor()
+ void causeFallDamage(float,float)
- void refreshBoundingBox()
- void setPosRaw(double,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.FlyingMob
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean causeFallDamage(float,float)
- int calculateFallDamage(float,float)
+ void causeFallDamage(float,float)
- void playBlockFallSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
</summary>

```diff
- boolean hasNoBlocksAbove(ServerLevel,LivingEntity,BlockPos)
+ boolean hasNoBlocksAbove(ServerLevel,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.WeightedList
</summary>

```diff
- double lambda$shuffle$4(Object)
- Object getOne()
- Object getOne(Random)
- Object lambda$serialize$2(DynamicOps,Function,WeightedList$WeightedEntry)
- Object serialize(DynamicOps,Function)
- Stream streamEntries()
- void <init>(Dynamic,Function)
+ void add(Object,int)
- void lambda$new$1(Function,Dynamic)
+ void lambda$shuffle$0(WeightedList$WeightedEntry)
- void lambda$shuffle$3(Random,WeightedList$WeightedEntry)
+ void shuffle()
- WeightedList add(Object,int)
- WeightedList lambda$null$0(Function,Dynamic,Dynamic)
- WeightedList shuffle()
- WeightedList shuffle(Random)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
</summary>

```diff
- double access$100(WeightedList$WeightedEntry)
- int getWeight()
- void access$200(WeightedList$WeightedEntry,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- boolean causeFallDamage(float,float)
- int calculateFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.item.FallingBlockEntity
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Creeper
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.MagmaCube
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeDefaultFeatures
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
- void releaseBeesAndResetState(Level,BlockState,BlockPos,Player,BeehiveBlockEntity$BeeReleaseStatus)
+ void releaseBeesAndResetState(Level,BlockState,BlockPos,Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,DiskConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,DiskConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.GroundBushFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(Set,LevelSimulatedRW,Random,BlockPos,BoundingBox)
+ void <init>(Function,BlockState,BlockState)
- void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,HugeMushroomFeatureConfig)
- int getTreeRadiusForHeight(int,int,int,int)
- void makeCap(LevelAccessor,Random,BlockPos,int,BlockPos$MutableBlockPos,HugeMushroomFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.KelpFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,MegaTreeConfiguration)
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(Set,LevelSimulatedRW,Random,BlockPos,BoundingBox)
+ void <init>(Function,boolean,int,int,BlockState,BlockState)
- void <init>(Function)
+ void createCrown(LevelSimulatedRW,BlockPos,int,BoundingBox,Set)
- void createCrown(LevelSimulatedRW,Random,BlockPos,int,Set,BoundingBox,TreeConfiguration)
+ void placeVine(LevelSimulatedRW,Random,BlockPos,BooleanProperty)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MegaTreeFeature
</summary>

```diff
- int calcTreeHeigth(Random,MegaTreeConfiguration)
+ int calcTreeHeigth(Random)
+ void <init>(Function,boolean,int,int,BlockState,BlockState)
- void <init>(Function)
+ void placeDoubleTrunkLeaves(LevelSimulatedRW,BlockPos,int,BoundingBox,Set)
- void placeDoubleTrunkLeaves(LevelSimulatedRW,Random,BlockPos,int,Set,BoundingBox,TreeConfiguration)
+ void placeSingleTrunkLeaves(LevelSimulatedRW,BlockPos,int,BoundingBox,Set)
- void placeSingleTrunkLeaves(LevelSimulatedRW,Random,BlockPos,int,Set,BoundingBox,TreeConfiguration)
- void placeTrunk(LevelSimulatedRW,Random,BlockPos,int,Set,BoundingBox,MegaTreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,ReplaceBlockConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,ReplaceBlockConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,SimpleBlockConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,SimpleBlockConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,SmallTreeConfiguration)
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(Set,LevelSimulatedRW,Random,BlockPos,BoundingBox)
+ int getTreeHeight(Random)
+ void <clinit>()
+ void <init>(Function,boolean,int,BlockState,BlockState,boolean)
+ void <init>(Function,boolean)
- void <init>(Function)
+ void addHangingVine(LevelSimulatedRW,BlockPos,BooleanProperty)
+ void addVine(LevelWriter,BlockPos,BooleanProperty)
+ void placeCocoa(LevelWriter,int,BlockPos,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
</summary>

```diff
+ Stream place(Random,DecoratorConfiguration,BlockPos)
- Stream place(Random,DecoratorConfiguration,BlockPos)
+ Stream place(Random,NoneDecoratorConfiguration,BlockPos)
- Stream place(Random,NoneDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
</summary>

```diff
+ Stream place(Random,DecoratorConfiguration,BlockPos)
- Stream place(Random,DecoratorConfiguration,BlockPos)
+ Stream place(Random,NoneDecoratorConfiguration,BlockPos)
- Stream place(Random,NoneDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ForestRockPlacementDecorator
</summary>

```diff
- BlockPos lambda$getPositions$0(Random,BlockPos,LevelAccessor,int)
+ BlockPos lambda$getPositions$0(Random,LevelAccessor,BlockPos,int)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorFrequency,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,FrequencyDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
</summary>

```diff
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,ChanceDecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,LakeChanceDecoratorConfig,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseHeightmapDoubleDecorator
</summary>

```diff
- BlockPos lambda$getPositions$0(Random,BlockPos,LevelAccessor,int)
+ BlockPos lambda$getPositions$0(Random,LevelAccessor,BlockPos,int)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorNoiseDependant,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,NoiseDependantDecoratorConfiguration,BlockPos)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.ChatFormatting
- net.minecraft.CrashReport
+ net.minecraft.CrashReportCategory
- net.minecraft.CrashReportCategory$Entry
+ net.minecraft.CrashReportDetail
- net.minecraft.DefaultUncaughtExceptionHandler
+ net.minecraft.DefaultUncaughtExceptionHandlerWithName
- net.minecraft.DetectedVersion
+ net.minecraft.FieldsAreNonnullByDefault
- net.minecraft.FileUtil
+ net.minecraft.MethodsReturnNonnullByDefault
+ net.minecraft.package-info
- net.minecraft.ReportedException
+ net.minecraft.ResourceLocationException
- net.minecraft.SharedConstants
+ net.minecraft.Util
- net.minecraft.Util$1
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
+ XXX.advancements.critereon.AbstractCriterionTriggerInstance
- XXX.advancements.critereon.BlockPredicate
+ XXX.advancements.critereon.BlockPredicate$Builder
- XXX.advancements.critereon.BredAnimalsTrigger
+ XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
- XXX.advancements.critereon.BrewedPotionTrigger
+ XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
- XXX.advancements.critereon.ChangeDimensionTrigger
+ XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
- XXX.advancements.critereon.ChanneledLightningTrigger
+ XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
- XXX.advancements.critereon.ConstructBeaconTrigger
+ XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
- XXX.advancements.critereon.ConsumeItemTrigger
+ XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
- XXX.advancements.critereon.CuredZombieVillagerTrigger
+ XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- XXX.advancements.critereon.DamagePredicate
+ XXX.advancements.critereon.DamagePredicate$Builder
- XXX.advancements.critereon.DamageSourcePredicate
+ XXX.advancements.critereon.DamageSourcePredicate$Builder
- XXX.advancements.critereon.DistancePredicate
+ XXX.advancements.critereon.EffectsChangedTrigger
- XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantedItemTrigger
- XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantmentPredicate
- XXX.advancements.critereon.EnterBlockTrigger
+ XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
- XXX.advancements.critereon.EntityEquipmentPredicate
+ XXX.advancements.critereon.EntityEquipmentPredicate$Builder
- XXX.advancements.critereon.EntityFlagsPredicate
+ XXX.advancements.critereon.EntityFlagsPredicate$Builder
- XXX.advancements.critereon.EntityHurtPlayerTrigger
+ XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
- XXX.advancements.critereon.EntityPredicate
+ XXX.advancements.critereon.EntityPredicate$1
- XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.EntityTypePredicate
- XXX.advancements.critereon.EntityTypePredicate$1
+ XXX.advancements.critereon.EntityTypePredicate$TagPredicate
- XXX.advancements.critereon.EntityTypePredicate$TypePredicate
+ XXX.advancements.critereon.FilledBucketTrigger
- XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ XXX.advancements.critereon.FishingRodHookedTrigger
- XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ XXX.advancements.critereon.FluidPredicate
- XXX.advancements.critereon.FluidPredicate$Builder
+ XXX.advancements.critereon.ImpossibleTrigger
- XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemDurabilityTrigger
- XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.KilledByCrossbowTrigger
- XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledTrigger
- XXX.advancements.critereon.KilledTrigger$TriggerInstance
+ XXX.advancements.critereon.LevitationTrigger
- XXX.advancements.critereon.LevitationTrigger$TriggerInstance
+ XXX.advancements.critereon.LightPredicate
- XXX.advancements.critereon.LightPredicate$1
+ XXX.advancements.critereon.LightPredicate$Builder
- XXX.advancements.critereon.LocationPredicate
+ XXX.advancements.critereon.LocationPredicate$Builder
- XXX.advancements.critereon.LocationTrigger
+ XXX.advancements.critereon.LocationTrigger$TriggerInstance
- XXX.advancements.critereon.MinMaxBounds
+ XXX.advancements.critereon.MinMaxBounds$BoundsFactory
- XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
+ XXX.advancements.critereon.MinMaxBounds$Floats
- XXX.advancements.critereon.MinMaxBounds$Ints
+ XXX.advancements.critereon.MobEffectsPredicate
- XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.NetherTravelTrigger
+ XXX.advancements.critereon.NetherTravelTrigger$TriggerInstance
- XXX.advancements.critereon.package-info
- XXX.advancements.critereon.PlacedBlockTrigger
+ XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerHurtEntityTrigger
+ XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerPredicate
+ XXX.advancements.critereon.PlayerPredicate$1
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- XXX.advancements.critereon.ShotCrossbowTrigger
+ XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.SimpleCriterionTrigger
+ XXX.advancements.critereon.StatePropertiesPredicate
- XXX.advancements.critereon.StatePropertiesPredicate$1
+ XXX.advancements.critereon.StatePropertiesPredicate$Builder
- XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
+ XXX.advancements.critereon.SummonedEntityTrigger
- XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.TameAnimalTrigger
- XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ XXX.advancements.critereon.TickTrigger
- XXX.advancements.critereon.TickTrigger$TriggerInstance
+ XXX.advancements.critereon.TradeTrigger
- XXX.advancements.critereon.TradeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.InteractGoal
+ XXX.ai.goal.JumpGoal
- XXX.ai.goal.LandOnOwnersShoulderGoal
+ XXX.ai.goal.LeapAtTargetGoal
- XXX.ai.goal.LlamaFollowCaravanGoal
+ XXX.ai.goal.LookAtPlayerGoal
- XXX.ai.goal.LookAtTradingPlayerGoal
+ XXX.ai.goal.MeleeAttackGoal
- XXX.ai.goal.MoveBackToVillage
+ XXX.ai.goal.MoveIndoorsGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.package-info
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
+ XXX.ai.goal.PlayGoal
- XXX.ai.goal.RandomLookAroundGoal
+ XXX.ai.goal.RandomStrollGoal
- XXX.ai.goal.RandomSwimmingGoal
+ XXX.ai.goal.RangedAttackGoal
- XXX.ai.goal.RangedBowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ XXX.ai.goal.RemoveBlockGoal
- XXX.ai.goal.RestrictSunGoal
+ XXX.ai.goal.RunAroundLikeCrazyGoal
- XXX.ai.goal.SitGoal
+ XXX.ai.goal.StrollThroughVillageGoal
- XXX.ai.goal.SwellGoal
+ XXX.ai.goal.TakeFlowerGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
+ XXX.ai.gossip.GossipContainer
- XXX.ai.gossip.GossipContainer$1
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.MemoryModuleType
- XXX.ai.memory.MemoryStatus
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.FlyingPathNavigation
- XXX.ai.navigation.GroundPathNavigation
- XXX.ai.navigation.package-info
+ XXX.ai.navigation.PathNavigation
- XXX.ai.navigation.WallClimberNavigation
+ XXX.ai.navigation.WaterBoundPathNavigation
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HurtBySensor
+ XXX.ai.sensing.InteractableDoorsSensor
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.package-info
- XXX.ai.sensing.PlayerSensor
+ XXX.ai.sensing.SecondaryPoiSensor
- XXX.ai.sensing.Sensing
+ XXX.ai.sensing.Sensor
- XXX.ai.sensing.SensorType
+ XXX.ai.sensing.VillagerBabiesSensor
- XXX.ai.sensing.VillagerHostilesSensor
+ XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
+ XXX.ai.util.package-info
- XXX.ai.util.RandomPos
- XXX.ai.village.package-info
- XXX.ai.village.ReputationEventType
+ XXX.ai.village.ReputationEventType$1
- XXX.ai.village.VillageSiege
+ XXX.ai.village.VillageSiege$State
+ XXX.blaze3d.platform.GlStateManager$CullState
- XXX.blaze3d.platform.GlStateManager$DepthState
+ XXX.blaze3d.platform.GlStateManager$DestFactor
- XXX.blaze3d.platform.GlStateManager$FboMode
+ XXX.blaze3d.platform.GlStateManager$FogMode
- XXX.blaze3d.platform.GlStateManager$FogState
+ XXX.blaze3d.platform.GlStateManager$LogicOp
- XXX.blaze3d.platform.GlStateManager$PolygonOffsetState
+ XXX.blaze3d.platform.GlStateManager$SourceFactor
- XXX.blaze3d.platform.GlStateManager$StencilFunc
+ XXX.blaze3d.platform.GlStateManager$StencilState
- XXX.blaze3d.platform.GlStateManager$TexGen
+ XXX.blaze3d.platform.GlStateManager$TexGenCoord
- XXX.blaze3d.platform.GlStateManager$TexGenState
+ XXX.blaze3d.platform.GlStateManager$TextureState
- XXX.blaze3d.platform.GlStateManager$Viewport
+ XXX.blaze3d.platform.GlUtil
- XXX.blaze3d.platform.InputConstants
+ XXX.blaze3d.platform.InputConstants$1
- XXX.blaze3d.platform.InputConstants$Key
+ XXX.blaze3d.platform.InputConstants$Type
- XXX.blaze3d.platform.Lighting
+ XXX.blaze3d.platform.MemoryTracker
- XXX.blaze3d.platform.Monitor
+ XXX.blaze3d.platform.MonitorCreator
- XXX.blaze3d.platform.NativeImage
+ XXX.blaze3d.platform.NativeImage$1
- XXX.blaze3d.platform.NativeImage$Format
+ XXX.blaze3d.platform.NativeImage$InternalGlFormat
- XXX.blaze3d.platform.NativeImage$WriteCallback
+ XXX.blaze3d.platform.PngInfo
- XXX.blaze3d.platform.PngInfo$1
+ XXX.blaze3d.platform.PngInfo$StbReader
- XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel
+ XXX.blaze3d.platform.PngInfo$StbReaderSeekableByteChannel
- XXX.blaze3d.platform.ScreenManager
+ XXX.blaze3d.platform.SnooperAccess
- XXX.blaze3d.platform.TextureUtil
+ XXX.blaze3d.platform.VideoMode
- XXX.blaze3d.platform.Window
+ XXX.blaze3d.platform.WindowEventHandler
- XXX.blaze3d.shaders.AbstractUniform
+ XXX.blaze3d.shaders.BlendMode
- XXX.blaze3d.shaders.Effect
+ XXX.blaze3d.shaders.Program
- XXX.blaze3d.shaders.Program$Type
+ XXX.blaze3d.shaders.ProgramManager
- XXX.blaze3d.shaders.Uniform
+ XXX.blaze3d.systems.RenderSystem
- XXX.blaze3d.vertex.BreakingTextureGenerator
+ XXX.blaze3d.vertex.BreakingTextureGenerator$1
- XXX.blaze3d.vertex.BufferBuilder
+ XXX.blaze3d.vertex.BufferBuilder$1
- XXX.blaze3d.vertex.BufferBuilder$DrawState
+ XXX.blaze3d.vertex.BufferBuilder$State
- XXX.blaze3d.vertex.BufferUploader
+ XXX.blaze3d.vertex.BufferVertexConsumer
+ XXX.blaze3d.vertex.DefaultedVertexConsumer
- XXX.blaze3d.vertex.DefaultVertexFormat
- XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$Pose
+ XXX.blaze3d.vertex.Tesselator
- XXX.blaze3d.vertex.VertexBuffer
+ XXX.blaze3d.vertex.VertexConsumer
- XXX.blaze3d.vertex.VertexFormat
+ XXX.blaze3d.vertex.VertexFormatElement
- XXX.blaze3d.vertex.VertexFormatElement$Type
+ XXX.blaze3d.vertex.VertexFormatElement$Usage
- XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
+ XXX.blaze3d.vertex.VertexMultiConsumer
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
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.AbstractStateHolder
+ XXX.block.state.AbstractStateHolder$1
- XXX.block.state.BlockState
+ XXX.block.state.BlockState$1
- XXX.block.state.BlockState$Cache
+ XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.OldChunkStorage
+ XXX.chunk.storage.OldChunkStorage$OldLevelChunk
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
- XXX.client.main.GameConfig
+ XXX.client.main.GameConfig$FolderData
- XXX.client.main.GameConfig$GameData
+ XXX.client.main.GameConfig$ServerData
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
- XXX.client.main.Main$3
+ XXX.client.main.package-info
- XXX.client.map.BiomeMapToolChunkCache
+ XXX.client.map.Map
- XXX.client.map.Map$1
+ XXX.client.map.Map$2
- XXX.client.map.Map$3
+ XXX.client.map.Map$4
- XXX.client.map.package-info
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AgeableListModel
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.BatModel
+ XXX.client.model.BeeModel
- XXX.client.model.BlazeModel
+ XXX.client.model.BoatModel
- XXX.client.model.BookModel
+ XXX.client.model.CatModel
- XXX.client.model.ChestedHorseModel
+ XXX.client.model.ChickenModel
- XXX.client.model.CodModel
+ XXX.client.model.ColorableAgeableListModel
- XXX.client.model.ColorableListModel
+ XXX.client.model.CowModel
- XXX.client.model.CreeperModel
+ XXX.client.model.DolphinModel
- XXX.client.model.DrownedModel
+ XXX.client.model.ElytraModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FoxModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GuardianModel
- XXX.client.model.HeadedModel
+ XXX.client.model.HorseModel
- XXX.client.model.HumanoidHeadModel
+ XXX.client.model.HumanoidModel
- XXX.client.model.HumanoidModel$1
+ XXX.client.model.HumanoidModel$ArmPose
- XXX.client.model.IllagerModel
+ XXX.client.model.IronGolemModel
- XXX.client.model.LavaSlimeModel
+ XXX.client.model.LeashKnotModel
- XXX.client.model.ListModel
+ XXX.client.model.LlamaModel
- XXX.client.model.LlamaSpitModel
+ XXX.client.model.MinecartModel
- XXX.client.model.Model
+ XXX.client.model.ModelUtils
- XXX.client.model.OcelotModel
+ XXX.client.model.package-info
+ XXX.client.model.PandaModel
- XXX.client.model.ParrotModel
+ XXX.client.model.ParrotModel$1
- XXX.client.model.ParrotModel$State
+ XXX.client.model.PhantomModel
- XXX.client.model.PigModel
+ XXX.client.model.PlayerModel
- XXX.client.model.PolarBearModel
+ XXX.client.model.PufferfishBigModel
- XXX.client.model.PufferfishMidModel
+ XXX.client.model.PufferfishSmallModel
- XXX.client.model.QuadrupedModel
+ XXX.client.model.RabbitModel
- XXX.client.model.RavagerModel
+ XXX.client.model.SalmonModel
- XXX.client.model.SheepFurModel
+ XXX.client.model.SheepModel
- XXX.client.model.ShieldModel
+ XXX.client.model.ShulkerBulletModel
- XXX.client.model.ShulkerModel
+ XXX.client.model.SilverfishModel
- XXX.client.model.SkeletonModel
+ XXX.client.model.SkullModel
- XXX.client.model.SlimeModel
+ XXX.client.model.SnowGolemModel
- XXX.client.model.SpiderModel
+ XXX.client.model.SquidModel
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerHeadModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.multiplayer.ClientAdvancements
+ XXX.client.multiplayer.ClientAdvancements$Listener
- XXX.client.multiplayer.ClientChunkCache
+ XXX.client.multiplayer.ClientChunkCache$1
- XXX.client.multiplayer.ClientChunkCache$Storage
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.MultiPlayerGameMode
- XXX.client.multiplayer.MultiPlayerLevel
- XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ServerAddress
+ XXX.client.multiplayer.ServerData
- XXX.client.multiplayer.ServerData$ServerPackStatus
+ XXX.client.multiplayer.ServerList
- XXX.client.multiplayer.ServerStatusPinger
+ XXX.client.multiplayer.ServerStatusPinger$1
- XXX.client.multiplayer.ServerStatusPinger$2
+ XXX.client.multiplayer.ServerStatusPinger$2$1
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$1
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BarrierParticle
- XXX.client.particle.BarrierParticle$1
+ XXX.client.particle.BarrierParticle$Provider
- XXX.client.particle.BreakingItemParticle
+ XXX.client.particle.BreakingItemParticle$1
- XXX.client.particle.BreakingItemParticle$Provider
+ XXX.client.particle.BreakingItemParticle$SlimeProvider
- XXX.client.particle.BreakingItemParticle$SnowballProvider
+ XXX.client.particle.BubbleColumnUpParticle
- XXX.client.particle.BubbleColumnUpParticle$1
+ XXX.client.particle.BubbleColumnUpParticle$Provider
- XXX.client.particle.BubbleParticle
+ XXX.client.particle.BubbleParticle$1
- XXX.client.particle.BubbleParticle$Provider
+ XXX.client.particle.BubblePopParticle
- XXX.client.particle.BubblePopParticle$1
+ XXX.client.particle.BubblePopParticle$Provider
- XXX.client.particle.CampfireSmokeParticle
+ XXX.client.particle.CampfireSmokeParticle$1
- XXX.client.particle.CampfireSmokeParticle$CosyProvider
+ XXX.client.particle.CampfireSmokeParticle$SignalProvider
- XXX.client.particle.CritParticle
+ XXX.client.particle.CritParticle$1
- XXX.client.particle.CritParticle$DamageIndicatorProvider
+ XXX.client.particle.CritParticle$MagicProvider
- XXX.client.particle.CritParticle$Provider
+ XXX.client.particle.DragonBreathParticle
- XXX.client.particle.DragonBreathParticle$1
+ XXX.client.particle.DragonBreathParticle$Provider
- XXX.client.particle.DripParticle
+ XXX.client.particle.DripParticle$1
- XXX.client.particle.DripParticle$CoolingDripHangParticle
+ XXX.client.particle.DripParticle$DripHangParticle
- XXX.client.particle.DripParticle$DripLandParticle
+ XXX.client.particle.DripParticle$FallAndLandParticle
- XXX.client.particle.DripParticle$FallingParticle
+ XXX.client.particle.DripParticle$HoneyFallAndLandParticle
- XXX.client.particle.DripParticle$HoneyFallProvider
+ XXX.client.particle.DripParticle$HoneyHangProvider
- XXX.client.particle.DripParticle$HoneyLandProvider
+ XXX.client.particle.DripParticle$LavaFallProvider
- XXX.client.particle.DripParticle$LavaHangProvider
+ XXX.client.particle.DripParticle$LavaLandProvider
- XXX.client.particle.DripParticle$NectarFallProvider
+ XXX.client.particle.DripParticle$WaterFallProvider
- XXX.client.particle.DripParticle$WaterHangProvider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$1
+ XXX.client.particle.DustParticle$Provider
- XXX.client.particle.EnchantmentTableParticle
+ XXX.client.particle.EnchantmentTableParticle$1
- XXX.client.particle.EnchantmentTableParticle$NautilusProvider
+ XXX.client.particle.EnchantmentTableParticle$Provider
- XXX.client.particle.EndRodParticle
+ XXX.client.particle.EndRodParticle$1
- XXX.client.particle.EndRodParticle$Provider
+ XXX.client.particle.ExplodeParticle
- XXX.client.particle.ExplodeParticle$Provider
+ XXX.client.particle.FallingDustParticle
- XXX.client.particle.FallingDustParticle$1
+ XXX.client.particle.FallingDustParticle$Provider
- XXX.client.particle.FireworkParticles
+ XXX.client.particle.FireworkParticles$1
- XXX.client.particle.FireworkParticles$FlashProvider
+ XXX.client.particle.FireworkParticles$OverlayParticle
- XXX.client.particle.FireworkParticles$SparkParticle
+ XXX.client.particle.FireworkParticles$SparkProvider
- XXX.client.particle.FireworkParticles$Starter
+ XXX.client.particle.FlameParticle
- XXX.client.particle.FlameParticle$1
+ XXX.client.particle.FlameParticle$Provider
- XXX.client.particle.HeartParticle
+ XXX.client.particle.HeartParticle$1
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$1
- XXX.client.particle.HugeExplosionParticle$Provider
+ XXX.client.particle.HugeExplosionSeedParticle
- XXX.client.particle.HugeExplosionSeedParticle$1
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$1
+ XXX.client.particle.LavaParticle$Provider
- XXX.client.particle.MobAppearanceParticle
+ XXX.client.particle.MobAppearanceParticle$1
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$1
- XXX.client.particle.NoteParticle$Provider
+ XXX.client.particle.package-info
+ XXX.client.particle.Particle
- XXX.client.particle.ParticleDescription
+ XXX.client.particle.ParticleEngine
- XXX.client.particle.ParticleEngine$1
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleEngine$SpriteParticleRegistration
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.ParticleRenderType$1
- XXX.client.particle.ParticleRenderType$2
+ XXX.client.particle.ParticleRenderType$3
- XXX.client.particle.ParticleRenderType$4
+ XXX.client.particle.ParticleRenderType$5
- XXX.client.particle.ParticleRenderType$6
+ XXX.client.particle.PlayerCloudParticle
- XXX.client.particle.PlayerCloudParticle$1
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$1
+ XXX.client.particle.PortalParticle$Provider
- XXX.client.particle.SimpleAnimatedParticle
+ XXX.client.particle.SingleQuadParticle
- XXX.client.particle.SmokeParticle
+ XXX.client.particle.SmokeParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$1
- XXX.client.particle.SpellParticle$AmbientMobProvider
+ XXX.client.particle.SpellParticle$InstantProvider
- XXX.client.particle.SpellParticle$MobProvider
+ XXX.client.particle.SpellParticle$Provider
- XXX.client.particle.SpellParticle$WitchProvider
+ XXX.client.particle.SpitParticle
- XXX.client.particle.SpitParticle$1
+ XXX.client.particle.SpitParticle$Provider
- XXX.client.particle.SplashParticle
+ XXX.client.particle.SplashParticle$1
- XXX.client.particle.SplashParticle$Provider
+ XXX.client.particle.SpriteSet
- XXX.client.particle.SquidInkParticle
+ XXX.client.particle.SquidInkParticle$1
- XXX.client.particle.SquidInkParticle$Provider
+ XXX.client.particle.SuspendedParticle
- XXX.client.particle.SuspendedParticle$1
+ XXX.client.particle.SuspendedParticle$Provider
- XXX.client.particle.SuspendedTownParticle
+ XXX.client.particle.SuspendedTownParticle$1
- XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
+ XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ XXX.client.particle.SuspendedTownParticle$Provider
- XXX.client.particle.TerrainParticle
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$1
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
+ XXX.client.particle.WakeParticle
- XXX.client.particle.WakeParticle$1
+ XXX.client.particle.WakeParticle$Provider
- XXX.client.particle.WaterCurrentDownParticle
+ XXX.client.particle.WaterCurrentDownParticle$1
- XXX.client.particle.WaterCurrentDownParticle$Provider
+ XXX.client.particle.WaterDropParticle
- XXX.client.particle.WaterDropParticle$Provider
- XXX.client.player.AbstractClientPlayer
+ XXX.client.player.Input
- XXX.client.player.KeyboardInput
+ XXX.client.player.LocalPlayer
- XXX.client.player.LocalPlayer$1
- XXX.client.player.package-info
+ XXX.client.player.RemotePlayer
+ XXX.client.renderer.BiomeColors
- XXX.client.renderer.BiomeColors$ColorResolver
+ XXX.client.renderer.ChunkBufferBuilderPack
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.EffectInstance
- XXX.client.renderer.EntityBlockRenderer
+ XXX.client.renderer.FaceInfo
- XXX.client.renderer.FaceInfo$1
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.FogRenderer
- XXX.client.renderer.FogRenderer$FogMode
+ XXX.client.renderer.GameRenderer
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemModelShaper
+ XXX.client.renderer.LevelRenderer
- XXX.client.renderer.LevelRenderer$1
+ XXX.client.renderer.LevelRenderer$RenderChunkInfo
- XXX.client.renderer.LightTexture
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.OutlineBufferSource
- XXX.client.renderer.OutlineBufferSource$1
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
- XXX.client.renderer.RenderStateShard$AlphaStateShard
- XXX.client.renderer.RenderStateShard$CullStateShard
- XXX.client.renderer.RenderStateShard$DiffuseLightingStateShard
- XXX.client.renderer.RenderStateShard$LayeringStateShard
- XXX.client.renderer.RenderStateShard$LineStateShard
- XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$ShadeModelStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
- XXX.client.renderer.RenderType$CompositeRenderType
- XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ XXX.client.renderer.RenderType$EntityState
+ XXX.client.renderer.RenderType$SwirlState
- XXX.datafix.fixes.BeehivePoiRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$1
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntityShulkerColorFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
- XXX.dimension.end.package-info
+ XXX.dimension.end.TheEndDimension
+ XXX.entity.ai.package-info
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractFish
- XXX.entity.animal.AbstractFish$FishMoveControl
+ XXX.entity.animal.AbstractFish$FishSwimGoal
- XXX.entity.animal.AbstractGolem
+ XXX.entity.animal.AbstractSchoolingFish
- XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ XXX.entity.animal.Animal
- XXX.entity.animal.Bee
+ XXX.entity.animal.Bee$1
- XXX.entity.animal.Bee$BaseBeeGoal
+ XXX.entity.animal.Bee$BeeAttackGoal
- XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ XXX.entity.animal.Bee$BeeEnterHiveGoal
- XXX.entity.animal.Bee$BeeGoToBlockGoal
+ XXX.entity.animal.Bee$BeeGoToHiveGoal
- XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ XXX.entity.animal.Bee$BeeGrowCropGoal
- XXX.entity.animal.Bee$BeeHurtByOtherGoal
+ XXX.entity.animal.Bee$BeeLocateHiveGoal
- XXX.entity.animal.Bee$BeeLookControl
+ XXX.entity.animal.Bee$BeePollinateGoal
- XXX.entity.animal.Bee$BeeWanderGoal
+ XXX.entity.animal.Cat
- XXX.entity.animal.Cat$CatAvoidEntityGoal
+ XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
- XXX.entity.animal.Cat$CatTemptGoal
+ XXX.entity.animal.Chicken
- XXX.entity.animal.Cod
+ XXX.entity.animal.Cow
- XXX.entity.animal.Dolphin
+ XXX.entity.animal.Dolphin$1
- XXX.entity.animal.Dolphin$DolphinMoveControl
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.Fox$1
+ XXX.entity.animal.Fox$DefendTrustedTargetGoal
- XXX.entity.animal.Fox$FaceplantGoal
+ XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
- XXX.entity.animal.Fox$FoxBehaviorGoal
+ XXX.entity.animal.Fox$FoxBreedGoal
- XXX.entity.animal.Fox$FoxEatBerriesGoal
+ XXX.entity.animal.Fox$FoxFloatGoal
- XXX.entity.animal.Fox$FoxFollowParentGoal
+ XXX.entity.animal.Fox$FoxGroupData
- XXX.entity.animal.Fox$FoxLookAtPlayerGoal
+ XXX.entity.animal.Fox$FoxLookControl
- XXX.entity.animal.Fox$FoxMeleeAttackGoal
+ XXX.entity.animal.Fox$FoxMoveControl
- XXX.entity.animal.Fox$FoxPanicGoal
+ XXX.entity.animal.Fox$FoxPounceGoal
- XXX.entity.animal.Fox$FoxSearchForItemsGoal
+ XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
- XXX.entity.animal.Fox$PerchAndSearchGoal
+ XXX.entity.animal.Fox$SeekShelterGoal
- XXX.entity.animal.Fox$SleepGoal
+ XXX.entity.animal.Fox$StalkPreyGoal
- XXX.entity.animal.Fox$Type
+ XXX.entity.animal.IronGolem
- XXX.entity.animal.IronGolem$Crackiness
- XXX.entity.layers.AbstractArmorLayer
+ XXX.entity.layers.ArrowLayer
- XXX.entity.layers.BeeStingerLayer
+ XXX.entity.layers.CapeLayer
- XXX.entity.layers.CarriedBlockLayer
+ XXX.entity.layers.CatCollarLayer
- XXX.entity.layers.CreeperPowerLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EyesLayer
- XXX.entity.layers.FoxHeldItemLayer
+ XXX.entity.layers.HorseArmorLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
- XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.DoublePlantPlacer
- XXX.feature.blockplacers.package-info
- XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BuriedTreasureConfiguration
- XXX.feature.configurations.CountFeatureConfiguration
- XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.MegaTreeConfiguration
- XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.NoneDecoratorConfiguration
- XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration$Predicates
- XXX.feature.configurations.package-info
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.structures.EmptyPoolElement
- XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawJunction
- XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecoratorType
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
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
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
- XXX.goal.target.package-info
+ XXX.goal.target.TargetGoal
- XXX.gui.screens.OptionsSubScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
- XXX.gui.screens.package-info
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PresetFlatWorldScreen
+ XXX.gui.screens.PresetFlatWorldScreen$PresetInfo
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.RealmsBackupInfoScreen
- XXX.gui.screens.RealmsBackupInfoScreen$1
+ XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoList
- XXX.gui.screens.RealmsBackupScreen
+ XXX.gui.screens.RealmsBackupScreen$1
- XXX.gui.screens.RealmsBackupScreen$2
+ XXX.gui.screens.RealmsBackupScreen$3
- XXX.gui.screens.RealmsBackupScreen$4
+ XXX.gui.screens.RealmsBackupScreen$5
- XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
+ XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionListEntry
- XXX.gui.screens.RealmsBrokenWorldScreen
+ XXX.gui.screens.RealmsBrokenWorldScreen$1
- XXX.gui.screens.RealmsBrokenWorldScreen$2
+ XXX.gui.screens.RealmsBrokenWorldScreen$DownloadButton
- XXX.gui.screens.RealmsBrokenWorldScreen$PlayButton
+ XXX.gui.screens.RealmsClientOutdatedScreen
- XXX.gui.screens.RealmsClientOutdatedScreen$1
+ XXX.gui.screens.RealmsConfigureWorldScreen
- XXX.gui.screens.RealmsConfigureWorldScreen$1
+ XXX.gui.screens.RealmsConfigureWorldScreen$2
- XXX.gui.screens.RealmsConfigureWorldScreen$3
+ XXX.gui.screens.RealmsConfigureWorldScreen$4
- XXX.gui.screens.RealmsConfigureWorldScreen$5
+ XXX.gui.screens.RealmsConfigureWorldScreen$6
- XXX.gui.screens.RealmsConfigureWorldScreen$7
+ XXX.gui.screens.RealmsConfigureWorldScreen$8
- XXX.gui.screens.RealmsConfigureWorldScreen$9
+ XXX.gui.screens.RealmsConfirmScreen
- XXX.gui.screens.RealmsConfirmScreen$1
+ XXX.gui.screens.RealmsConfirmScreen$2
- XXX.gui.screens.RealmsCreateRealmScreen
+ XXX.gui.screens.RealmsCreateRealmScreen$1
- XXX.gui.screens.RealmsCreateRealmScreen$2
+ XXX.gui.screens.RealmsCreateTrialScreen
- XXX.gui.screens.RealmsCreateTrialScreen$1
+ XXX.gui.screens.RealmsCreateTrialScreen$2
- XXX.gui.screens.RealmsDownloadLatestWorldScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen$1
- XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ XXX.gui.screens.RealmsGenericErrorScreen
- XXX.gui.screens.RealmsGenericErrorScreen$1
+ XXX.gui.screens.RealmsInviteScreen
- XXX.gui.screens.RealmsInviteScreen$1
+ XXX.gui.screens.RealmsInviteScreen$2
- XXX.gui.screens.RealmsLongConfirmationScreen
+ XXX.gui.screens.RealmsLongConfirmationScreen$1
- XXX.gui.screens.RealmsLongConfirmationScreen$2
+ XXX.gui.screens.RealmsLongConfirmationScreen$3
- XXX.gui.screens.RealmsLongConfirmationScreen$Type
+ XXX.gui.screens.RealmsLongRunningMcoTaskScreen
- XXX.gui.screens.RealmsLongRunningMcoTaskScreen$1
+ XXX.gui.screens.RealmsLongRunningMcoTaskScreen$2
- XXX.gui.screens.RealmsNotificationsScreen
+ XXX.gui.screens.RealmsNotificationsScreen$1
- XXX.gui.screens.RealmsParentalConsentScreen
+ XXX.gui.screens.RealmsParentalConsentScreen$1
- XXX.gui.screens.RealmsParentalConsentScreen$2
+ XXX.gui.screens.RealmsParentalConsentScreen$3
- XXX.gui.screens.RealmsPendingInvitesScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen$1
- XXX.gui.screens.RealmsPendingInvitesScreen$2
+ XXX.gui.screens.RealmsPendingInvitesScreen$3
- XXX.gui.screens.RealmsPendingInvitesScreen$4
+ XXX.gui.screens.RealmsPendingInvitesScreen$5
- XXX.gui.screens.RealmsPendingInvitesScreen$6
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry$AcceptRowButton
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry$RejectRowButton
+ XXX.gui.screens.RealmsPlayerScreen
- XXX.gui.screens.RealmsPlayerScreen$1
+ XXX.gui.screens.RealmsPlayerScreen$2
- XXX.gui.screens.RealmsPlayerScreen$3
+ XXX.gui.screens.RealmsPlayerScreen$4
- XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
+ XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionListEntry
- XXX.gui.screens.RealmsResetNormalWorldScreen
+ XXX.gui.screens.RealmsResetNormalWorldScreen$1
- XXX.gui.screens.RealmsResetNormalWorldScreen$2
+ XXX.gui.screens.RealmsResetNormalWorldScreen$3
- XXX.gui.screens.RealmsResetNormalWorldScreen$4
+ XXX.gui.screens.RealmsResetWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen$1
+ XXX.gui.screens.RealmsResetWorldScreen$2
- XXX.gui.screens.RealmsResetWorldScreen$3
+ XXX.gui.screens.RealmsResetWorldScreen$4
- XXX.gui.screens.RealmsResetWorldScreen$5
+ XXX.gui.screens.RealmsResetWorldScreen$6
- XXX.gui.screens.RealmsResetWorldScreen$7
+ XXX.gui.screens.RealmsResetWorldScreen$8
- XXX.gui.screens.RealmsResetWorldScreen$9
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsResetWorldScreen$ResetType
+ XXX.gui.screens.RealmsResetWorldScreen$ResetWorldInfo
- XXX.gui.screens.RealmsResourcePackScreen
+ XXX.gui.screens.RealmsScreenWithCallback
- XXX.gui.screens.RealmsSelectFileToUploadScreen
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$1
- XXX.gui.screens.RealmsSelectFileToUploadScreen$2
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldListEntry
- XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$2
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$3
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$4
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$5
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionListEntry
+ XXX.gui.screens.RealmsSettingsScreen
- XXX.gui.screens.RealmsSettingsScreen$1
+ XXX.gui.screens.RealmsSettingsScreen$2
- XXX.gui.screens.RealmsSettingsScreen$3
+ XXX.gui.screens.RealmsSlotOptionsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen$1
+ XXX.gui.screens.RealmsSlotOptionsScreen$10
- XXX.gui.screens.RealmsSlotOptionsScreen$2
+ XXX.gui.screens.RealmsSlotOptionsScreen$3
- XXX.gui.screens.RealmsSlotOptionsScreen$4
+ XXX.gui.screens.RealmsSlotOptionsScreen$5
- XXX.gui.screens.RealmsSlotOptionsScreen$6
+ XXX.gui.screens.RealmsSlotOptionsScreen$7
- XXX.gui.screens.RealmsSlotOptionsScreen$8
+ XXX.gui.screens.RealmsSlotOptionsScreen$9
- XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ XXX.gui.screens.RealmsSubscriptionInfoScreen
- XXX.gui.screens.RealmsSubscriptionInfoScreen$1
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$2
- XXX.gui.screens.RealmsSubscriptionInfoScreen$3
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$4
- XXX.gui.screens.RealmsTermsScreen
+ XXX.gui.screens.RealmsTermsScreen$1
- XXX.gui.screens.RealmsTermsScreen$2
+ XXX.gui.screens.RealmsUploadScreen
- XXX.gui.screens.RealmsUploadScreen$1
+ XXX.gui.screens.RealmsUploadScreen$2
- XXX.gui.screens.RealmsUploadScreen$Unit
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.UploadResult
- XXX.gui.screens.UploadResult$Builder
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
+ XXX.gui.spectator.package-info
+ XXX.gui.spectator.PlayerMenuItem
- XXX.gui.spectator.RootSpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenu
- XXX.gui.spectator.SpectatorMenu$1
+ XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
- XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
+ XXX.gui.spectator.SpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenuItem
+ XXX.gui.spectator.SpectatorMenuListener
- XXX.layer.traits.AreaTransformer0
+ XXX.layer.traits.AreaTransformer1
- XXX.layer.traits.AreaTransformer2
+ XXX.layer.traits.BishopTransformer
- XXX.layer.traits.C0Transformer
+ XXX.layer.traits.C1Transformer
- XXX.layer.traits.CastleTransformer
+ XXX.layer.traits.DimensionOffset0Transformer
- XXX.layer.traits.DimensionOffset1Transformer
+ XXX.layer.traits.DimensionTransformer
+ XXX.layer.traits.package-info
- XXX.layer.traits.PixelTransformer
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
+ XXX.level.block.LogBlock
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
- XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
- XXX.level.block.package-info
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
+ XXX.level.block.SoulsandBlock
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
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$1
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkBiomeContainer
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGeneratorFactory
+ XXX.level.chunk.ChunkGeneratorType
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.package-info
- XXX.level.chunk.Palette
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.ProtoTickList
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$1
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
+ XXX.level.dimension.Dimension
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.NetherDimension
- XXX.level.dimension.NetherDimension$1
+ XXX.level.dimension.NormalDimension
+ XXX.level.dimension.package-info
- XXX.level.levelgen.ChunkGeneratorSettings
+ XXX.level.levelgen.DebugGeneratorSettings
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.NetherGeneratorSettings
- XXX.level.levelgen.NetherLevelSource
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.OverworldGeneratorSettings
+ XXX.level.levelgen.OverworldLevelSource
- XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.TheEndGeneratorSettings
+ XXX.level.levelgen.TheEndLevelSource
- XXX.level.levelgen.WorldgenRandom
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
+ XXX.level.material.Fluids
+ XXX.level.material.FluidState
- XXX.level.material.FluidStateImpl
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.TurtleNodeEvaluator
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SaveDataDirtyRunnable
+ XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelStorage
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$1
+ XXX.level.storage.LevelSummary
- XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerIO
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
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.HellCaveWorldCarver
- XXX.levelgen.carver.NoneCarverConfiguration
- XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
- XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BigTreeFeature
+ XXX.levelgen.feature.BirchFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureConfiguration
+ XXX.levelgen.feature.BushFeature
+ XXX.levelgen.feature.CentralSpikedFeature
+ XXX.levelgen.feature.DarkOakFeature
+ XXX.levelgen.feature.DecoratedFlowerFeature
+ XXX.levelgen.feature.DecoratorConfiguration
+ XXX.levelgen.feature.DecoratorNoiseDependant
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DesertPyramidFeature
- XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
+ XXX.levelgen.feature.DesertVillagePools
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskConfiguration
+ XXX.levelgen.feature.DoublePlantConfiguration
+ XXX.levelgen.feature.EndGatewayConfiguration
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.FancyTreeFeature$FoliageCoords
+ XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeatureRadius
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FlowerFeature
+ XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GrassFeature
+ XXX.levelgen.feature.HayBlockPileFeature
+ XXX.levelgen.feature.HellSpringConfiguration
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeMushroomFeatureConfig
+ XXX.levelgen.feature.IceBlockPileFeature
- XXX.levelgen.feature.IcePatchFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
+ XXX.levelgen.feature.JungleTreeFeature
+ XXX.levelgen.feature.LakeConfiguration
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LayerConfiguration
+ XXX.levelgen.feature.MelonBlockPileFeature
+ XXX.levelgen.feature.MineshaftConfiguration
- XXX.levelgen.feature.MineshaftFeature
+ XXX.levelgen.feature.MineshaftFeature$MineShaftStart
- XXX.levelgen.feature.MineshaftFeature$Type
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.NoneDecoratorConfiguration
+ XXX.levelgen.feature.OceanRuinConfiguration
+ XXX.levelgen.feature.OreConfiguration$Predicates
- XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostConfiguration
+ XXX.levelgen.feature.PlainFlowerFeature
+ XXX.levelgen.feature.ProbabilityFeatureConfiguration
+ XXX.levelgen.feature.RandomBooleanFeatureConfig
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomFeatureConfig
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomRandomFeatureConfig
+ XXX.levelgen.feature.ReplaceBlockConfiguration
+ XXX.levelgen.feature.SavannaTreeFeature
- XXX.levelgen.feature.SavannaVillagePools
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeagrassFeatureConfiguration
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.ShipwreckFeature
- XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleBlockConfiguration
+ XXX.levelgen.feature.SimpleRandomFeatureConfig
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SimulatedFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SnowBlockPileFeature
+ XXX.levelgen.feature.SpikeConfiguration
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.StrongholdFeature
- XXX.levelgen.feature.StrongholdFeature$StrongholdStart
+ XXX.levelgen.feature.StructureFeature
- XXX.levelgen.feature.StructureFeature$StructureStartFactory
+ XXX.levelgen.feature.StructurePieceType
- XXX.levelgen.feature.SwamplandHutFeature
+ XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.SwampTreeFeature
+ XXX.levelgen.feature.VillageConfiguration
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VillageFeature$FeatureStart
- XXX.levelgen.feature.VillagePieces
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
+ XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
- XXX.levelgen.placement.ChanceHeightmapDecorator
+ XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.ChancePassthroughDecorator
+ XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
- XXX.levelgen.placement.ChorusPlantPlacementDecorator
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountBiasedRangeDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDecorator
- XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.CountDepthAverageDecorator
- XXX.levelgen.placement.CountHeighmapDoubleDecorator
+ XXX.levelgen.placement.CountHeight64Decorator
- XXX.levelgen.placement.CountHeightmap32Decorator
+ XXX.levelgen.placement.CountHeightmapDecorator
- XXX.levelgen.placement.CountTopSolidDecorator
+ XXX.levelgen.placement.CountVeryBiasedRangeDecorator
- XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
+ XXX.levelgen.placement.DecoratorChance
+ XXX.levelgen.placement.DecoratorFrequencyChance
+ XXX.levelgen.placement.DecoratorNoiseCountFactor
- XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
- XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.MonsterRoomPlacementConfiguration
- XXX.levelgen.placement.MonsterRoomPlacementDecorator
+ XXX.levelgen.placement.package-info
- XXX.levelgen.placement.SimpleFeatureDecorator
+ XXX.levelgen.placement.TopSolidHeightMapDecorator
- XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
- XXX.levelgen.structure.BeardedStructureStart
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
- XXX.levelgen.structure.JunglePyramidPiece$1
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
- XXX.levelgen.structure.MineShaftPieces$1
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
- XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
- XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
- XXX.levelgen.structure.NetherBridgePieces
+ XXX.levelgen.structure.NetherBridgePieces$1
- XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
- XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
- XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
- XXX.levelgen.structure.NetherBridgePieces$StartPiece
+ XXX.levelgen.structure.OceanMonumentPieces
- XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature
- XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ XXX.levelgen.structure.OceanRuinFeature$Type
- XXX.levelgen.structure.OceanRuinPieces
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PillagerOutpostPieces
+ XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.ShipwreckPieces
+ XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$1
- XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$3
- XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FillerCorridor
- XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$LeftTurn
- XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PieceWeight
- XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$PrisonHall
- XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$RoomCrossing
- XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StairsDown
- XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$Straight
- XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructureFeatureIO
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
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
- XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
+ XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.levelgen.synth.SurfaceNoise
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
+ XXX.minecraft.advancements.Advancement
- XXX.minecraft.advancements.Advancement$1
+ XXX.minecraft.advancements.Advancement$Builder
- XXX.minecraft.advancements.AdvancementList
+ XXX.minecraft.advancements.AdvancementList$Listener
- XXX.minecraft.advancements.AdvancementProgress
+ XXX.minecraft.advancements.AdvancementProgress$Serializer
- XXX.minecraft.advancements.AdvancementRewards
+ XXX.minecraft.advancements.AdvancementRewards$Builder
- XXX.minecraft.advancements.AdvancementRewards$Deserializer
+ XXX.minecraft.advancements.CriteriaTriggers
- XXX.minecraft.advancements.Criterion
+ XXX.minecraft.advancements.CriterionProgress
- XXX.minecraft.advancements.CriterionTrigger
+ XXX.minecraft.advancements.CriterionTrigger$Listener
- XXX.minecraft.advancements.CriterionTriggerInstance
+ XXX.minecraft.advancements.DisplayInfo
- XXX.minecraft.advancements.FrameType
+ XXX.minecraft.advancements.package-info
+ XXX.minecraft.advancements.RequirementsStrategy
- XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.client.AmbientOcclusionStatus
+ XXX.minecraft.client.AttackIndicatorStatus
- XXX.minecraft.client.BooleanOption
+ XXX.minecraft.client.Camera
- XXX.minecraft.client.ClientBrandRetriever
+ XXX.minecraft.client.ClientRecipeBook
- XXX.minecraft.client.CloudStatus
+ XXX.minecraft.client.CycleOption
- XXX.minecraft.client.DebugQueryHandler
+ XXX.minecraft.client.FullscreenResolutionProgressOption
- XXX.minecraft.client.Game
+ XXX.minecraft.client.Game$Metrics
- XXX.minecraft.client.GuiMessage
+ XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.KeyboardHandler
+ XXX.minecraft.client.KeyboardHandler$1
- XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.KeyMapping$1
- XXX.minecraft.client.LogaritmicProgressOption
+ XXX.minecraft.client.Minecraft
- XXX.minecraft.client.Minecraft$1
+ XXX.minecraft.client.Minecraft$2
- XXX.minecraft.client.MouseHandler
+ XXX.minecraft.client.NarratorStatus
- XXX.minecraft.client.Option
+ XXX.minecraft.client.Options
- XXX.minecraft.client.Options$1
+ XXX.minecraft.client.Options$2
+ XXX.minecraft.client.package-info
- XXX.minecraft.client.ParticleStatus
+ XXX.minecraft.client.ProgressOption
- XXX.minecraft.client.RecipeBookCategories
+ XXX.minecraft.client.Screenshot
- XXX.minecraft.client.Session
+ XXX.minecraft.client.Timer
- XXX.minecraft.client.ToggleKeyMapping
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
- XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.AbstractRealmsButton
+ XXX.minecraft.realms.DisconnectedRealmsScreen
- XXX.minecraft.realms.DisconnectedRealmsScreen$1
+ XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmListEntry
- XXX.minecraft.realms.Realms
+ XXX.minecraft.realms.RealmsAbstractButtonProxy
- XXX.minecraft.realms.RealmsAnvilLevelStorageSource
+ XXX.minecraft.realms.RealmsBridge
- XXX.minecraft.realms.RealmsButton
+ XXX.minecraft.realms.RealmsButtonProxy
- XXX.minecraft.realms.RealmsClickableScrolledSelectionList
+ XXX.minecraft.realms.RealmsClickableScrolledSelectionListProxy
- XXX.minecraft.realms.RealmsConfirmResultListener
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsDefaultVertexFormat
- XXX.minecraft.realms.RealmsEditBox
+ XXX.minecraft.realms.RealmsGuiEventListener
- XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsLabelProxy
- XXX.minecraft.realms.RealmsLevelSummary
+ XXX.minecraft.realms.RealmsMth
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsObjectSelectionListProxy
- XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RealmsScreenProxy
- XXX.minecraft.realms.RealmsScrolledSelectionList
+ XXX.minecraft.realms.RealmsScrolledSelectionListProxy
- XXX.minecraft.realms.RealmsServerAddress
+ XXX.minecraft.realms.RealmsSharedConstants
- XXX.minecraft.realms.RealmsSimpleScrolledSelectionList
+ XXX.minecraft.realms.RealmsSimpleScrolledSelectionListProxy
- XXX.minecraft.realms.RealmsSliderButton
+ XXX.minecraft.realms.RealmsSliderButtonProxy
- XXX.minecraft.realms.RealmsVertexFormat
+ XXX.minecraft.realms.RealmsVertexFormatElement
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
- XXX.minecraft.realms.Tezzelator
- XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$1
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.ConsoleInputSource
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$2
- XXX.minecraft.server.MinecraftServer$3
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$1
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.TickTask
- XXX.minecraft.world.package-info
- XXX.model.dragon.DragonHeadModel
+ XXX.model.dragon.package-info
- XXX.model.geom.ModelPart
+ XXX.model.geom.ModelPart$Cube
- XXX.model.geom.ModelPart$Polygon
+ XXX.model.geom.ModelPart$Vertex
- XXX.model.geom.package-info
- XXX.mojang.math.Matrix3f
+ XXX.mojang.math.Matrix4f
- XXX.mojang.math.Quaternion
+ XXX.mojang.math.Transformation
- XXX.mojang.math.Vector3d
+ XXX.mojang.math.Vector3f
- XXX.mojang.math.Vector4f
+ XXX.mojang.realmsclient.KeyCombo
- XXX.mojang.realmsclient.RealmsMainScreen
+ XXX.mojang.realmsclient.RealmsMainScreen$1
- XXX.mojang.realmsclient.RealmsMainScreen$10
+ XXX.mojang.realmsclient.RealmsMainScreen$11
- XXX.mojang.realmsclient.RealmsMainScreen$12
+ XXX.mojang.realmsclient.RealmsMainScreen$2
- XXX.mojang.realmsclient.RealmsMainScreen$3
+ XXX.mojang.realmsclient.RealmsMainScreen$4
- XXX.mojang.realmsclient.RealmsMainScreen$5
+ XXX.mojang.realmsclient.RealmsMainScreen$6
- XXX.mojang.realmsclient.RealmsMainScreen$7
+ XXX.mojang.realmsclient.RealmsMainScreen$8
- XXX.mojang.realmsclient.RealmsMainScreen$9
+ XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
- XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
+ XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionListEntry
- XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionListTrialEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
+ XXX.network.chat.BaseComponent
- XXX.network.chat.ChatType
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.Component
- XXX.network.chat.Component$1
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.ContextAwareComponent
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.KeybindComponent
+ XXX.network.chat.NbtComponent
- XXX.network.chat.NbtComponent$BlockNbtComponent
+ XXX.network.chat.NbtComponent$EntityNbtComponent
- XXX.network.chat.NbtComponent$StorageNbtComponent
+ XXX.network.chat.package-info
+ XXX.network.chat.ScoreComponent
- XXX.network.chat.SelectorComponent
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.TextComponent
+ XXX.network.chat.TranslatableComponent
- XXX.network.chat.TranslatableFormatException
+ XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
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
+ XXX.newbiome.area.Area
- XXX.newbiome.area.AreaFactory
+ XXX.newbiome.area.LazyArea
- XXX.newbiome.area.package-info
+ XXX.newbiome.context.BigContext
- XXX.newbiome.context.Context
+ XXX.newbiome.context.LazyAreaContext
- XXX.newbiome.context.package-info
+ XXX.newbiome.layer.AddDeepOceanLayer
- XXX.newbiome.layer.AddEdgeLayer
+ XXX.newbiome.layer.AddEdgeLayer$CoolWarm
- XXX.newbiome.layer.AddEdgeLayer$HeatIce
+ XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- XXX.newbiome.layer.AddIslandLayer
+ XXX.newbiome.layer.AddMushroomIslandLayer
- XXX.newbiome.layer.AddSnowLayer
+ XXX.newbiome.layer.BiomeEdgeLayer
- XXX.newbiome.layer.BiomeInitLayer
+ XXX.newbiome.layer.IslandLayer
- XXX.newbiome.layer.Layer
+ XXX.newbiome.layer.Layers
- XXX.newbiome.layer.OceanLayer
+ XXX.newbiome.layer.OceanMixerLayer
+ XXX.newbiome.layer.package-info
- XXX.newbiome.layer.RareBiomeLargeLayer
+ XXX.newbiome.layer.RareBiomeSpotLayer
- XXX.newbiome.layer.RegionHillsLayer
+ XXX.newbiome.layer.RemoveTooMuchOceanLayer
- XXX.newbiome.layer.RiverInitLayer
+ XXX.newbiome.layer.RiverLayer
- XXX.newbiome.layer.RiverMixerLayer
+ XXX.newbiome.layer.ShoreLayer
- XXX.newbiome.layer.SmoothLayer
+ XXX.newbiome.layer.ZoomLayer
- XXX.newbiome.layer.ZoomLayer$1
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
- XXX.placement.nether.ChanceRangeDecorator
+ XXX.placement.nether.CountRangeDecorator
- XXX.placement.nether.HellFireDecorator
+ XXX.placement.nether.LightGemChanceDecorator
- XXX.placement.nether.MagmaDecorator
- XXX.placement.nether.package-info
+ XXX.placement.nether.RandomCountRangeDecorator
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
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
+ XXX.protocol.game.ClientboundSetSpawnPositionPacket
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
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.DebugVillagerNameGenerator
- XXX.protocol.game.package-info
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
- XXX.protocol.game.ServerGamePacketListener
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
- XXX.realms.pluginapi.LoadedRealmsPlugin
- XXX.realms.pluginapi.package-info
+ XXX.realms.pluginapi.RealmsPlugin
- XXX.realmsclient.client.FileDownload
+ XXX.realmsclient.client.FileDownload$1
- XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
+ XXX.realmsclient.client.FileDownload$ProgressListener
- XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
+ XXX.realmsclient.client.FileUpload
- XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
+ XXX.realmsclient.client.Ping
- XXX.realmsclient.client.Ping$Region
+ XXX.realmsclient.client.RealmsClient
- XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
+ XXX.realmsclient.client.RealmsClient$Environment
- XXX.realmsclient.client.RealmsClientConfig
+ XXX.realmsclient.client.RealmsError
- XXX.realmsclient.client.Request
+ XXX.realmsclient.client.Request$Delete
- XXX.realmsclient.client.Request$Get
+ XXX.realmsclient.client.Request$Post
- XXX.realmsclient.client.Request$Put
+ XXX.realmsclient.client.UploadStatus
- XXX.realmsclient.dto.Backup
+ XXX.realmsclient.dto.BackupList
- XXX.realmsclient.dto.Ops
+ XXX.realmsclient.dto.PendingInvite
- XXX.realmsclient.dto.PendingInvitesList
+ XXX.realmsclient.dto.PingResult
- XXX.realmsclient.dto.PlayerInfo
+ XXX.realmsclient.dto.RealmsDescriptionDto
- XXX.realmsclient.dto.RealmsNews
+ XXX.realmsclient.dto.RealmsServer
- XXX.realmsclient.dto.RealmsServer$McoServerComparator
+ XXX.realmsclient.dto.RealmsServer$State
- XXX.realmsclient.dto.RealmsServer$WorldType
+ XXX.realmsclient.dto.RealmsServerAddress
- XXX.realmsclient.dto.RealmsServerList
+ XXX.realmsclient.dto.RealmsServerPing
- XXX.realmsclient.dto.RealmsServerPlayerList
+ XXX.realmsclient.dto.RealmsServerPlayerLists
- XXX.realmsclient.dto.RealmsWorldOptions
+ XXX.realmsclient.dto.RealmsWorldResetDto
- XXX.realmsclient.dto.RegionPingResult
+ XXX.realmsclient.dto.ServerActivity
- XXX.realmsclient.dto.ServerActivityList
+ XXX.realmsclient.dto.Subscription
- XXX.realmsclient.dto.Subscription$SubscriptionType
+ XXX.realmsclient.dto.UploadInfo
- XXX.realmsclient.dto.ValueObject
+ XXX.realmsclient.dto.WorldDownload
- XXX.realmsclient.dto.WorldTemplate
+ XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
- XXX.realmsclient.dto.WorldTemplatePaginatedList
+ XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
- XXX.realmsclient.exception.RealmsHttpException
+ XXX.realmsclient.exception.RealmsServiceException
- XXX.realmsclient.exception.RetryCallException
+ XXX.realmsclient.gui.ChatFormatting
- XXX.realmsclient.gui.LongRunningTask
+ XXX.realmsclient.gui.RealmsConstants
- XXX.realmsclient.gui.RealmsDataFetcher
+ XXX.realmsclient.gui.RealmsDataFetcher$1
- XXX.realmsclient.gui.RealmsDataFetcher$LiveStatsTask
+ XXX.realmsclient.gui.RealmsDataFetcher$PendingInviteUpdateTask
- XXX.realmsclient.gui.RealmsDataFetcher$ServerListUpdateTask
+ XXX.realmsclient.gui.RealmsDataFetcher$Task
- XXX.realmsclient.gui.RealmsDataFetcher$TrialAvailabilityTask
+ XXX.realmsclient.gui.RealmsDataFetcher$UnreadNewsTask
- XXX.realmsclient.gui.RealmsWorldSlotButton
+ XXX.realmsclient.gui.RealmsWorldSlotButton$Action
- XXX.realmsclient.gui.RealmsWorldSlotButton$Listener
+ XXX.realmsclient.gui.RealmsWorldSlotButton$State
- XXX.realmsclient.gui.RowButton
+ XXX.realmsclient.util.JsonUtils
- XXX.realmsclient.util.RealmsPersistence
+ XXX.realmsclient.util.RealmsPersistence$1
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTasks
- XXX.realmsclient.util.RealmsTasks$CloseServerTask
+ XXX.realmsclient.util.RealmsTasks$DownloadTask
- XXX.realmsclient.util.RealmsTasks$OpenServerTask
+ XXX.realmsclient.util.RealmsTasks$RealmsConnectTask
- XXX.realmsclient.util.RealmsTasks$RealmsGetServerDetailsTask
+ XXX.realmsclient.util.RealmsTasks$ResettingWorldTask
- XXX.realmsclient.util.RealmsTasks$RestoreTask
+ XXX.realmsclient.util.RealmsTasks$SwitchMinigameTask
- XXX.realmsclient.util.RealmsTasks$SwitchSlotTask
+ XXX.realmsclient.util.RealmsTasks$TrialCreationTask
- XXX.realmsclient.util.RealmsTasks$WorldCreationTask
+ XXX.realmsclient.util.RealmsTextureManager
- XXX.realmsclient.util.RealmsTextureManager$1
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.RealmsUtil$1
- XXX.realmsclient.util.SkinProcessor
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
- XXX.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
+ XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
- XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
+ XXX.renderer.chunk.package-info
+ XXX.renderer.chunk.RenderChunkRegion
- XXX.renderer.chunk.VisGraph
+ XXX.renderer.chunk.VisGraph$1
- XXX.renderer.chunk.VisibilitySet
- XXX.renderer.culling.Frustum
+ XXX.renderer.culling.package-info
- XXX.renderer.debug.CaveDebugRenderer
+ XXX.renderer.debug.ChunkBorderRenderer
- XXX.renderer.debug.ChunkDebugRenderer
+ XXX.renderer.debug.ChunkDebugRenderer$1
- XXX.renderer.debug.ChunkDebugRenderer$ChunkData
+ XXX.renderer.debug.CollisionBoxRenderer
- XXX.renderer.debug.DebugRenderer
+ XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
- XXX.renderer.debug.GameTestDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer$Marker
- XXX.renderer.debug.GoalSelectorDebugRenderer
+ XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- XXX.renderer.debug.HeightMapRenderer
+ XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.package-info
+ XXX.renderer.debug.PathfindingRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
+ XXX.renderer.debug.VillageDebugRenderer
- XXX.renderer.debug.VillageDebugRenderer$BrainDump
+ XXX.renderer.debug.VillageDebugRenderer$PoiInfo
- XXX.renderer.debug.WaterDebugRenderer
+ XXX.renderer.debug.WorldGenAttemptRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractZombieRenderer
+ XXX.renderer.entity.AreaEffectCloudRenderer
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.CatRenderer
+ XXX.renderer.entity.CaveSpiderRenderer
- XXX.renderer.entity.ChestedHorseRenderer
+ XXX.renderer.entity.ChickenRenderer
- XXX.renderer.entity.CodRenderer
+ XXX.renderer.entity.CowRenderer
- XXX.renderer.entity.CreeperRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EnderDragonRenderer$DragonModel
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EvokerFangsRenderer
+ XXX.renderer.entity.EvokerRenderer
- XXX.renderer.entity.EvokerRenderer$1
+ XXX.renderer.entity.ExperienceOrbRenderer
- XXX.renderer.entity.FallingBlockRenderer
+ XXX.renderer.entity.FireworkEntityRenderer
- XXX.renderer.entity.FishingHookRenderer
+ XXX.renderer.entity.FoxRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GuardianRenderer
+ XXX.renderer.entity.HorseRenderer
- XXX.renderer.entity.HumanoidMobRenderer
+ XXX.renderer.entity.HuskRenderer
- XXX.renderer.entity.IllagerRenderer
+ XXX.renderer.entity.IllusionerRenderer
- XXX.renderer.entity.IllusionerRenderer$1
+ XXX.renderer.entity.IronGolemRenderer
- XXX.renderer.entity.ItemEntityRenderer
+ XXX.renderer.entity.ItemFrameRenderer
- XXX.renderer.entity.ItemRenderer
+ XXX.renderer.entity.LeashKnotRenderer
- XXX.renderer.entity.LightningBoltRenderer
+ XXX.renderer.entity.LivingEntityRenderer
- XXX.renderer.entity.LivingEntityRenderer$1
+ XXX.renderer.entity.LlamaRenderer
- XXX.renderer.entity.LlamaSpitRenderer
+ XXX.renderer.entity.MagmaCubeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.PhantomRenderer
- XXX.renderer.entity.PigRenderer
+ XXX.renderer.entity.PigZombieRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
+ XXX.renderer.entity.SheepRenderer
- XXX.renderer.entity.ShulkerBulletRenderer
+ XXX.renderer.entity.ShulkerRenderer
- XXX.renderer.entity.SilverfishRenderer
+ XXX.renderer.entity.SkeletonRenderer
- XXX.renderer.entity.SlimeRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.ThrownItemRenderer
+ XXX.renderer.entity.ThrownTridentRenderer
- XXX.renderer.entity.TippableArrowRenderer
+ XXX.renderer.entity.TntMinecartRenderer
- XXX.renderer.entity.TntRenderer
+ XXX.renderer.entity.TropicalFishRenderer
- XXX.renderer.entity.TurtleRenderer
+ XXX.renderer.entity.UndeadHorseRenderer
- XXX.renderer.entity.VexRenderer
+ XXX.renderer.entity.VillagerRenderer
- XXX.renderer.entity.VindicatorRenderer
+ XXX.renderer.entity.VindicatorRenderer$1
- XXX.renderer.entity.WanderingTraderRenderer
+ XXX.renderer.entity.WitchRenderer
- XXX.renderer.entity.WitherBossRenderer
+ XXX.renderer.entity.WitherSkeletonRenderer
- XXX.renderer.entity.WitherSkullRenderer
+ XXX.renderer.entity.WolfRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
- XXX.resourcepacks.entries.package-info
+ XXX.resourcepacks.lists.AvailableResourcePackList
+ XXX.resourcepacks.lists.package-info
- XXX.resourcepacks.lists.ResourcePackList
+ XXX.resourcepacks.lists.ResourcePackList$ResourcePackEntry
- XXX.resourcepacks.lists.SelectedResourcePackList
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$1
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlList
- XXX.screens.controls.ControlList$1
+ XXX.screens.controls.ControlList$CategoryEntry
- XXX.screens.controls.ControlList$Entry
+ XXX.screens.controls.ControlList$KeyEntry
- XXX.screens.controls.ControlList$KeyEntry$1
+ XXX.screens.controls.ControlList$KeyEntry$2
- XXX.screens.controls.ControlsScreen
+ XXX.screens.controls.package-info
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractCommandBlockEditScreen$SuggestionsList
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
+ XXX.screens.inventory.JigsawBlockEditScreen
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
+ XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmokerScreen
+ XXX.screens.inventory.StonecutterScreen
- XXX.screens.inventory.StructureBlockEditScreen
+ XXX.screens.inventory.StructureBlockEditScreen$1
- XXX.screens.inventory.StructureBlockEditScreen$2
- XXX.screens.mco.package-info
+ XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
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
- XXX.screens.worldselection.CreateWorldScreen$4
- XXX.screens.worldselection.CreateWorldScreen$6
- XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode
+ XXX.screens.worldselection.EditWorldScreen
- XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.package-info
+ XXX.screens.worldselection.SelectWorldScreen
- XXX.screens.worldselection.WorldSelectionList
+ XXX.screens.worldselection.WorldSelectionList$WorldListEntry
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$1
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
- XXX.server.commands.DeOpCommands
- XXX.server.commands.DifficultyCommand
+ XXX.server.commands.EffectCommands
- XXX.server.commands.EmoteCommands
+ XXX.server.commands.EnchantCommand
- XXX.server.commands.ExecuteCommand
+ XXX.server.commands.ExecuteCommand$CommandNumericPredicate
- XXX.server.commands.ExecuteCommand$CommandPredicate
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.ListPlayersCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ReplaceItemCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.SeedCommand
- XXX.server.commands.SetBlockCommand
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpectateCommand
- XXX.spectator.categories.package-info
- XXX.spectator.categories.SpectatorPage
+ XXX.spectator.categories.TeleportToPlayerMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
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
- XXX.state.properties.AbstractProperty
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
- XXX.storage.loot.BinomialDistributionGenerator
+ XXX.storage.loot.BinomialDistributionGenerator$Serializer
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ConstantIntValue
- XXX.storage.loot.ConstantIntValue$Serializer
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
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
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
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.TagMatchTest
+ XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
- XXX.world.level.package-info
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
XXX.gui.components.AbstractWidget +1M
```
```
XXX.gui.screens.AccessibilityOptionsScreen -1M | -2P
```
```
XXX.gui.screens.ChatOptionsScreen -1M | -2P
```
```
XXX.gui.screens.LanguageSelectScreen -2P
```
```
XXX.gui.screens.LoadingOverlay +1M -1M
```
```
XXX.gui.screens.MouseSettingsScreen +1M -2M | -1P
```
```
XXX.client.renderer.RenderType +34M -58M | +1P -4P
```
```
XXX.renderer.block.BlockRenderDispatcher +1M -1M
```
```
XXX.renderer.blockentity.BeaconRenderer +2M -2M
```
```
XXX.renderer.blockentity.BellRenderer +2M -2M
```
```
XXX.renderer.blockentity.BlockEntityRenderer +1P -1P
```
```
XXX.renderer.blockentity.ChestRenderer +2M -2M
```
```
XXX.renderer.blockentity.EnchantTableRenderer +2M -2M
```
```
XXX.renderer.blockentity.PistonHeadRenderer +3M -3M
```
```
XXX.renderer.blockentity.SignRenderer +2M -2M
```
```
XXX.renderer.blockentity.StructureBlockRenderer +2M -2M
```
```
XXX.renderer.blockentity.TheEndGatewayRenderer +3M -3M
```
```
XXX.minecraft.core.BlockPos +1M
```
```
XXX.minecraft.core.BlockPos$MutableBlockPos +1M
```
```
XXX.minecraft.sounds.SoundEvents +8P -1P
```
```
XXX.minecraft.tags.BlockTags -1P
```
```
XXX.entity.monster.Blaze +1M -1M
```
```
XXX.entity.npc.Villager +4M -6M
```
```
XXX.entity.player.Player +1M -1M
```
```
XXX.entity.vehicle.MinecartTNT +1M -1M
```
```
XXX.world.item.Items +3P -1P
```
```
XXX.world.level.BlockEventData +1M
```
```
XXX.level.biome.Biome +9M -9M
```
```
XXX.level.block.Block +4M -4M | +2P
```
```
XXX.level.block.Block$Properties +6M -2M | +2P
```
```
XXX.levelgen.feature.AbstractTreeFeature +16M -14M | +1P -1P
```
```
XXX.levelgen.feature.ConfiguredFeature +3M -1M | +1P -1P
```
```
XXX.levelgen.feature.CoralFeature +2M -2M
```
```
XXX.levelgen.feature.DecoratedFeature +2M -2M
```
```
XXX.levelgen.feature.GlowstoneFeature +2M -2M
```
```
XXX.levelgen.feature.IcebergFeature +2M -2M
```
```
XXX.levelgen.feature.MegaPineTreeFeature +4M -7M | -4P
```
```
XXX.levelgen.feature.RandomSelectorFeature +2M -2M
```
```
XXX.levelgen.feature.SpringFeature +2M -2M
```
```
XXX.levelgen.feature.WeightedConfiguredFeature +1M -2M | +2P -3P
```
```
XXX.levelgen.placement.EndGatewayPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.FeatureDecorator +3M -2M | +1P -1P
```
```
XXX.levelgen.placement.LakeLavaPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.NoiseHeightmap32Decorator +3M -3M
```
```
XXX.levelgen.placement.NopePlacementDecorator +2M -2M
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.AbstractWidget
</summary>

```diff
- void queueNarration(int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.AccessibilityOptionsScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ChatOptionsScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LoadingOverlay
</summary>

```diff
+ void drawProgressBar(int,int,int,int,float,float)
- void drawProgressBar(int,int,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.MouseSettingsScreen
</summary>

```diff
- void <init>(Screen,Options)
+ void <init>(Screen)
+ void removed()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderType
</summary>

```diff
+ boolean equals(Object)
+ int hashCode()
- RenderType beaconBeam()
- RenderType crumbling(int)
+ RenderType CRUMBLING(int)
- RenderType cutout()
- RenderType cutoutMipped()
- RenderType endPortal(int)
- RenderType entityAlpha(ResourceLocation,float)
- RenderType entityCutout(ResourceLocation)
- RenderType entityCutoutNoCull(ResourceLocation)
- RenderType entityDecal(ResourceLocation)
- RenderType entityForceTranslucent(ResourceLocation)
- RenderType entityGlint()
- RenderType entityNoOutline(ResourceLocation)
- RenderType entitySmoothCutout(ResourceLocation)
- RenderType entitySolid(ResourceLocation)
- RenderType entityTranslucent(ResourceLocation)
- RenderType eyes(ResourceLocation)
+ RenderType EYES(ResourceLocation)
- RenderType getChunkRenderType(BlockState)
+ RenderType getRenderLayer(BlockState)
- RenderType getRenderType(BlockState)
- RenderType getRenderType(ItemStack)
- RenderType glint()
- RenderType leash()
- RenderType lightning()
- RenderType lines()
+ RenderType NEW_ENTITY(ResourceLocation,boolean,boolean,boolean,float,boolean,boolean)
+ RenderType NEW_ENTITY(ResourceLocation,boolean,boolean,boolean)
+ RenderType NEW_ENTITY(ResourceLocation)
- RenderType outline(ResourceLocation)
+ RenderType OUTLINE(ResourceLocation)
+ RenderType PORTAL(int)
+ RenderType POWER_SWIRL(ResourceLocation,float,float)
- RenderType powerSwirl(ResourceLocation,float,float)
- RenderType solid()
+ RenderType TEXT_SEE_THROUGH(ResourceLocation)
- RenderType text(ResourceLocation)
+ RenderType TEXT(ResourceLocation)
- RenderType textSeeThrough(ResourceLocation)
- RenderType translucent()
- RenderType translucentNoCrumbling()
- RenderType waterMask()
- void <init>(String,VertexFormat,int,int,boolean,boolean,Runnable,Runnable)
+ void <init>(String,VertexFormat,int,int,boolean,Runnable,Runnable)
+ void clearGlint()
+ void clearRenderState()
+ void lambda$CRUMBLING$24(Integer)
+ void lambda$CRUMBLING$25(Integer)
+ void lambda$EYES$10(ResourceLocation)
+ void lambda$EYES$11(ResourceLocation)
+ void lambda$NEW_ENTITY$8(RenderType$EntityState)
+ void lambda$NEW_ENTITY$9(RenderType$EntityState)
+ void lambda$OUTLINE$18(ResourceLocation)
+ void lambda$OUTLINE$19(ResourceLocation)
+ void lambda$PORTAL$34(Integer)
+ void lambda$PORTAL$35(Integer)
+ void lambda$POWER_SWIRL$12(RenderType,RenderType$SwirlState)
+ void lambda$POWER_SWIRL$13(RenderType,RenderType$SwirlState)
+ void lambda$static$0()
- void lambda$static$0(HashMap)
+ void lambda$static$1()
- void lambda$static$1(HashMap)
+ void lambda$static$14()
+ void lambda$static$15()
+ void lambda$static$16()
+ void lambda$static$17()
+ void lambda$static$2()
+ void lambda$static$20()
+ void lambda$static$21()
+ void lambda$static$22()
+ void lambda$static$23()
+ void lambda$static$3()
+ void lambda$static$30()
+ void lambda$static$31()
+ void lambda$static$32()
+ void lambda$static$33()
+ void lambda$static$36()
+ void lambda$static$37()
+ void lambda$static$38(HashMap)
+ void lambda$static$39(HashMap)
+ void lambda$static$4()
+ void lambda$static$5()
+ void lambda$static$6()
+ void lambda$static$7()
+ void lambda$TEXT_SEE_THROUGH$28(RenderType,ResourceLocation)
+ void lambda$TEXT_SEE_THROUGH$29(RenderType,ResourceLocation)
+ void lambda$TEXT$26(ResourceLocation)
+ void lambda$TEXT$27(ResourceLocation)
+ void setupGlint(float)
+ void setupRenderState()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.BlockRenderDispatcher
</summary>

```diff
+ void renderSingleBlock(BlockState,PoseStack,MultiBufferSource,int,int,int)
- void renderSingleBlock(BlockState,PoseStack,MultiBufferSource,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BeaconRenderer
</summary>

```diff
- void render(BeaconBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BeaconBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BellRenderer
</summary>

```diff
- void render(BellBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BellBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.ChestRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(PoseStack,VertexConsumer,ModelPart,ModelPart,ModelPart,float,int,int,TextureAtlasSprite)
+ void render(PoseStack,VertexConsumer,ModelPart,ModelPart,ModelPart,float,int,TextureAtlasSprite)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.EnchantTableRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(EnchantmentTableBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(EnchantmentTableBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.PistonHeadRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(PistonMovingBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(PistonMovingBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void renderBlock(BlockPos,BlockState,PoseStack,MultiBufferSource,Level,boolean,int)
+ void renderBlock(BlockPos,BlockState,PoseStack,MultiBufferSource,Level,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SignRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(SignBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(SignBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.StructureBlockRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(StructureBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(StructureBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(TheEndGatewayBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(TheEndGatewayBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(TheEndPortalBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(TheEndPortalBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- Stream betweenClosedStream(BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos$MutableBlockPos
</summary>

```diff
- void <init>(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Blaze
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
+ boolean lambda$spawnGolemIfNeeded$10(long,Villager)
- boolean lambda$spawnGolemIfNeeded$8(long,Villager)
+ Component getDisplayName()
- Component getTypeName()
- int lambda$countFoodPointsInInventory$7(SimpleContainer,Map$Entry)
+ int lambda$countFoodPointsInInventory$9(SimpleContainer,Map$Entry)
+ void lambda$getDisplayName$7(Style)
+ void lambda$getDisplayName$8(Style)
+ void lambda$spawnGolemIfNeeded$11(long,Villager)
- void lambda$spawnGolemIfNeeded$9(long,Villager)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartTNT
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.BlockEventData
</summary>

```diff
- int hashCode()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ ConfiguredFeature makeComposite(Feature,FeatureConfiguration,FeatureDecorator,DecoratorConfiguration)
+ FeatureConfiguration getStructureConfiguration(StructureFeature)
- FeatureConfiguration getStructureConfiguration(StructureFeature)
- Object lambda$null$10(DynamicOps,Biome$SpawnerData)
+ Object lambda$null$4(DynamicOps,ConfiguredWorldCarver)
- Object lambda$null$5(DynamicOps,ConfiguredWorldCarver)
+ Object lambda$null$6(DynamicOps,ConfiguredFeature)
- Object lambda$null$7(DynamicOps,ConfiguredFeature)
+ Object lambda$null$9(DynamicOps,Biome$SpawnerData)
+ Pair lambda$serialize$10(DynamicOps,Map$Entry)
- Pair lambda$serialize$11(DynamicOps,Map$Entry)
+ Pair lambda$serialize$5(DynamicOps,Map$Entry)
- Pair lambda$serialize$6(DynamicOps,Map$Entry)
+ Pair lambda$serialize$7(DynamicOps,Map$Entry)
- Pair lambda$serialize$9(DynamicOps,Map$Entry)
- String lambda$generate$4(ConfiguredFeature)
- void addStructureStart(ConfiguredFeature)
+ void addStructureStart(StructureFeature,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ boolean access$1200(Block)
+ boolean access$1300(Block)
- boolean access$1400(Block)
- boolean access$1500(Block)
+ boolean equalsDirt(Block)
+ boolean equalsStone(Block)
- float getJumpFactor()
- float getSpeedFactor()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block$Properties
</summary>

```diff
- Block$Properties jumpFactor(float)
- Block$Properties speedFactor(float)
- boolean access$1300(Block$Properties)
+ boolean access$900(Block$Properties)
- float access$1000(Block$Properties)
- float access$900(Block$Properties)
+ ResourceLocation access$1000(Block$Properties)
- ResourceLocation access$1200(Block$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractTreeFeature
</summary>

```diff
+ boolean isFluidWater(LevelSimulatedReader,BlockPos)
+ boolean isLeaves(LevelSimulatedReader,BlockPos)
- boolean isVine(LevelSimulatedReader,BlockPos)
- boolean lambda$isAirOrLeaves$4(BlockState)
+ boolean lambda$isAirOrLeaves$5(BlockState)
+ boolean lambda$isFluidWater$2(FluidState)
- boolean lambda$isGrassOrDirt$5(BlockState)
+ boolean lambda$isGrassOrDirt$6(BlockState)
- boolean lambda$isGrassOrDirtOrFarmland$6(BlockState)
+ boolean lambda$isGrassOrDirtOrFarmland$7(BlockState)
+ boolean lambda$isLeaves$4(BlockState)
- boolean lambda$isReplaceablePlant$7(BlockState)
+ boolean lambda$isReplaceablePlant$8(BlockState)
- boolean lambda$isVine$2(BlockState)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration,boolean)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,TreeConfiguration)
- boolean placeLeaf(LevelSimulatedRW,Random,BlockPos,Set,BoundingBox,TreeConfiguration)
- boolean placeLog(LevelSimulatedRW,Random,BlockPos,Set,BoundingBox,TreeConfiguration)
- DiscreteVoxelShape updateLeaves(LevelAccessor,BoundingBox,Set,Set)
+ void <init>(Function,boolean)
- void <init>(Function)
- void lambda$place$8(LevelAccessor,Random,List,List,Set,BoundingBox,TreeDecorator)
- void setBlock(LevelWriter,BlockPos,BlockState,BoundingBox)
+ void setBlock(Set,LevelWriter,BlockPos,BlockState,BoundingBox)
+ void simulate(FeatureSimulator,Random,BlockPos,FeatureConfiguration)
- void simulate(FeatureSimulator,Random,BlockPos,FeatureConfiguration)
- void simulate(FeatureSimulator,Random,BlockPos,TreeConfiguration)
+ void spawnBeehive(LevelAccessor,Random,BlockPos,BoundingBox,List,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredFeature
</summary>

```diff
- ConfiguredFeature decorated(ConfiguredDecorator)
+ void <init>(Feature,FeatureConfiguration)
- void <init>(Feature,FeatureConfiguration)
- WeightedConfiguredFeature weighted(float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.CoralFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.DecoratedFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,DecoratedFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,DecoratedFeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.GlowstoneFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.IcebergFeature
</summary>

```diff
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,BlockStateConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,IcebergConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,MegaTreeConfiguration)
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(Set,LevelSimulatedRW,Random,BlockPos,BoundingBox)
+ void <clinit>()
+ void <init>(Function,boolean,boolean)
- void <init>(Function)
+ void createCrown(LevelSimulatedRW,int,int,int,int,Random,BoundingBox,Set)
- void createCrown(LevelSimulatedRW,Random,int,int,int,int,Set,BoundingBox,MegaTreeConfiguration)
+ void placePodzolAt(LevelSimulatedRW,BlockPos)
+ void placePodzolCircle(LevelSimulatedRW,BlockPos)
+ void postPlaceTree(LevelSimulatedRW,Random,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,RandomFeatureConfig)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,RandomFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpringFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,SpringConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,SpringConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
</summary>

```diff
- void <init>(ConfiguredFeature,float)
+ void <init>(Feature,Dynamic,float)
+ void <init>(Feature,FeatureConfiguration,Float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
</summary>

```diff
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,NoneDecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,NoneDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FeatureDecorator
</summary>

```diff
+ boolean placeFeature(LevelAccessor,ChunkGenerator,Random,BlockPos,DecoratorConfiguration,ConfiguredFeature)
- boolean placeFeature(LevelAccessor,ChunkGenerator,Random,BlockPos,DecoratorConfiguration,ConfiguredFeature)
- ConfiguredDecorator configured(DecoratorConfiguration)
+ DecoratorConfiguration createSettings(Dynamic)
- DecoratorConfiguration createSettings(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
</summary>

```diff
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,ChanceDecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,LakeChanceDecoratorConfig,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseHeightmap32Decorator
</summary>

```diff
- BlockPos lambda$getPositions$0(Random,BlockPos,LevelAccessor,int)
+ BlockPos lambda$getPositions$0(Random,LevelAccessor,BlockPos,int)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorNoiseDependant,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,NoiseDependantDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
</summary>

```diff
+ Stream place(Random,DecoratorConfiguration,BlockPos)
- Stream place(Random,DecoratorConfiguration,BlockPos)
+ Stream place(Random,NoneDecoratorConfiguration,BlockPos)
- Stream place(Random,NoneDecoratorConfiguration,BlockPos)
```

</details>
</details>
<hr/>