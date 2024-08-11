## Comparison with [20w27a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w27a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">20w27a</th><th>20w28a</th></tr><tr><td>World version</td><td><code>2569</code></td><td><code>2570</code></td></tr><tr><td>Protocol version</td><td><code>738</code></td><td><code>740</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
- biome_source.txt
- biome.txt
- block_placer_type.txt
- block_state_provider_type.txt
- carver.txt
- chunk_generator.txt
- decorator.txt
- feature_size_type.txt
- feature.txt
- foliage_placer_type.txt
- structure_feature.txt
- structure_piece.txt
- structure_pool_element.txt
- structure_processor.txt
- surface_builder.txt
- tree_decorator_type.txt
- trunk_placer_type.txt
+ worldgen/biome_source.txt
+ worldgen/block_placer_type.txt
+ worldgen/block_state_provider_type.txt
+ worldgen/carver.txt
+ worldgen/chunk_generator.txt
+ worldgen/decorator.txt
+ worldgen/feature_size_type.txt
+ worldgen/feature.txt
+ worldgen/foliage_placer_type.txt
+ worldgen/structure_feature.txt
+ worldgen/structure_piece.txt
+ worldgen/structure_pool_element.txt
+ worldgen/structure_processor.txt
+ worldgen/surface_builder.txt
+ worldgen/tree_decorator_type.txt
+ worldgen/trunk_placer_type.txt
```

</details>













<details>
<summary>
memory_module_type.txt
</summary>

```diff
+ minecraft:disable_walk_to_admire_item
+ minecraft:time_trying_to_reach_admire_item
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
- universal_tags/biome_source.json
- universal_tags/biome.json
- universal_tags/block_placer_type.json
- universal_tags/block_state_provider_type.json
- universal_tags/carver.json
- universal_tags/chunk_generator.json
- universal_tags/decorator.json
- universal_tags/feature_size_type.json
- universal_tags/feature.json
- universal_tags/foliage_placer_type.json
- universal_tags/structure_feature.json
- universal_tags/structure_piece.json
- universal_tags/structure_pool_element.json
- universal_tags/structure_processor.json
- universal_tags/surface_builder.json
- universal_tags/tree_decorator_type.json
- universal_tags/trunk_placer_type.json
+ universal_tags/worldgen/biome_source.json
+ universal_tags/worldgen/block_placer_type.json
+ universal_tags/worldgen/block_state_provider_type.json
+ universal_tags/worldgen/carver.json
+ universal_tags/worldgen/chunk_generator.json
+ universal_tags/worldgen/decorator.json
+ universal_tags/worldgen/feature_size_type.json
+ universal_tags/worldgen/feature.json
+ universal_tags/worldgen/foliage_placer_type.json
+ universal_tags/worldgen/structure_feature.json
+ universal_tags/worldgen/structure_piece.json
+ universal_tags/worldgen/structure_pool_element.json
+ universal_tags/worldgen/structure_processor.json
+ universal_tags/worldgen/surface_builder.json
+ universal_tags/worldgen/tree_decorator_type.json
+ universal_tags/worldgen/trunk_placer_type.json
```

</details>



















<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:disable_walk_to_admire_item
+ minecraft:time_trying_to_reach_admire_item
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
brewing_stand.json
</summary>

```
A: #stone_crafting_materials
B: blaze_rod
C: cobblestone

Previous pattern:
[  | B |  ]
[C | C | C]

New pattern:
[  | B |  ]
[A | A | A]
```

</details>








































































































































































































<details>
<summary>
furnace.json
</summary>

```
A: #furnace_materials
B: #stone_crafting_materials

Previous pattern:
[A | A | A]
[A |   | A]
[A | A | A]

New pattern:
[B | B | B]
[B |   | B]
[B | B | B]
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ chat.square_brackets: [%s]
+ command.context.parse_error: %s at position %s: %s
+ commands.list.nameAndId: %s (%s)
+ disconnect.exceeded_packet_rate: Kicked for exceeding packet rate limit
- options.entityDistancePercent: %s%%
+ options.generic_value: %s: %s
+ options.off.composed: %s: OFF
+ options.on.composed: %s: ON
+ options.percent_add_value: %s: +%s%%
+ options.percent_value: %s: %s%%
+ options.pixel_value: %s: %spx
+ potion.withAmplifier: %s %s
+ potion.withDuration: %s (%s)
- selectWorld.hardcoreMode: Hardcore:
- selectWorld.hardcoreMode.info: World is deleted upon death
```

</details>
<details>
<summary>
Changes
</summary>

```
selectWorld.mapFeatures: Generate Structures:
selectWorld.allowCommands: Allow Cheats:
selectWorld.bonusItems: Bonus Chest:
jigsaw_block.keep_jigsaws: Keep Jigsaws: 
gamerule.doDaylightCycle: Advance in-game timetime of day
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/blocks/base_stone_nether.json
+ minecraft/tags/blocks/base_stone_overworld.json
- minecraft/tags/items/furnace_materials.json
+ minecraft/tags/items/stone_crafting_materials.json
```

</details>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.CharPredicate
- net.minecraft.core.BlockPos$5
+ net.minecraft.core.BlockPos$MutableBlockPos
- net.minecraft.core.BlockSource
+ net.minecraft.core.BlockSourceImpl
- net.minecraft.core.Cursor3D
+ net.minecraft.core.DefaultedRegistry
- net.minecraft.core.Direction
+ net.minecraft.core.Direction$1
- net.minecraft.core.Direction$Axis
+ net.minecraft.core.Direction$Axis$1
- net.minecraft.core.Direction$Axis$2
+ net.minecraft.core.Direction$Axis$3
- net.minecraft.core.Direction$AxisDirection
+ net.minecraft.core.Direction$Plane
- net.minecraft.core.Direction8
+ net.minecraft.core.FrontAndTop
- net.minecraft.core.GlobalPos
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.MappedRegistry
- net.minecraft.core.NonNullList
+ net.minecraft.core.Position
- net.minecraft.core.PositionImpl
+ net.minecraft.core.Registry
- net.minecraft.core.RegistryAccess
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.HashCache
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLoot
- net.minecraft.data.loot.ChestLoot
+ net.minecraft.data.loot.EntityLoot
- net.minecraft.data.loot.FishingLoot
+ net.minecraft.data.loot.GiftLoot
- net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.PiglinBarterLoot
+ net.minecraft.data.Main
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
+ net.minecraft.data.models.BlockModelGenerators$TintState
- net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$1
- net.minecraft.data.models.blockstates.Condition$CompositeCondition
+ net.minecraft.data.models.blockstates.Condition$Operation
- net.minecraft.data.models.blockstates.Condition$TerminalCondition
+ net.minecraft.data.models.blockstates.MultiPartGenerator
- net.minecraft.data.models.blockstates.MultiPartGenerator$1
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
- net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
+ net.minecraft.data.models.blockstates.PropertyDispatch$1
- net.minecraft.data.models.blockstates.PropertyDispatch$C1
+ net.minecraft.data.models.blockstates.PropertyDispatch$C2
- net.minecraft.data.models.blockstates.PropertyDispatch$C3
+ net.minecraft.data.models.blockstates.PropertyDispatch$C4
- net.minecraft.data.models.blockstates.PropertyDispatch$C5
+ net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
- net.minecraft.data.models.blockstates.Selector
+ net.minecraft.data.models.blockstates.Variant
- net.minecraft.data.models.blockstates.VariantProperties
+ net.minecraft.data.models.blockstates.VariantProperties$Rotation
- net.minecraft.data.models.blockstates.VariantProperty
+ net.minecraft.data.models.blockstates.VariantProperty$Value
+ net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.model.DelegatedModel
- net.minecraft.data.models.model.ModelLocationUtils
+ net.minecraft.data.models.model.ModelTemplate
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
- net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.package-info
+ net.minecraft.data.recipes.RecipeProvider
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapedRecipeBuilder$Result
- net.minecraft.data.recipes.ShapelessRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
- net.minecraft.data.recipes.SingleItemRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
- net.minecraft.data.recipes.SpecialRecipeBuilder
+ net.minecraft.data.recipes.SpecialRecipeBuilder$1
- net.minecraft.data.recipes.UpgradeRecipeBuilder
+ net.minecraft.data.recipes.UpgradeRecipeBuilder$Result
+ net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1
+ net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.biome.BadlandsBiome
- net.minecraft.data.worldgen.biome.BambooJungleBiome
- net.minecraft.data.worldgen.biome.BasaltDeltasBiome
- net.minecraft.data.worldgen.biome.BirchForestBiome
- net.minecraft.data.worldgen.biome.ColdOceanBiome
- net.minecraft.data.worldgen.biome.DarkForestBiome
- net.minecraft.data.worldgen.biome.DeepColdOceanBiome
- net.minecraft.data.worldgen.biome.DeepLukeWarmOceanBiome
- net.minecraft.data.worldgen.biome.DeepWarmOceanBiome
- net.minecraft.data.worldgen.biome.DesertHillsBiome
- net.minecraft.data.worldgen.biome.EndBarrensBiome
- net.minecraft.data.worldgen.biome.EndMidlandsBiome
- net.minecraft.data.worldgen.biome.ForestBiome
- net.minecraft.data.worldgen.biome.FrozenOceanBiome
- net.minecraft.data.worldgen.biome.GiantSpruceTaigaBiome
- net.minecraft.data.worldgen.biome.GiantTreeTaigaBiome
- net.minecraft.data.worldgen.biome.GravellyMountainsBiome
- net.minecraft.data.worldgen.biome.JungleBiome
- net.minecraft.data.worldgen.biome.JungleHillsBiome
- net.minecraft.data.worldgen.biome.ModifiedBadlandsPlateauBiome
- net.minecraft.data.worldgen.biome.ModifiedJungleBiome
- net.minecraft.data.worldgen.biome.ModifiedWoodedBadlandsPlateauBiome
- net.minecraft.data.worldgen.biome.MountainEdgeBiome
- net.minecraft.data.worldgen.biome.MushroomFieldsShoreBiome
- net.minecraft.data.worldgen.biome.OceanBiome
- net.minecraft.data.worldgen.biome.RiverBiome
- net.minecraft.data.worldgen.biome.SavannaPlateauBiome
- net.minecraft.data.worldgen.biome.ShatteredSavannaPlateauBiome
- net.minecraft.data.worldgen.biome.SnowyBeachBiome
- net.minecraft.data.worldgen.biome.SnowyTaigaBiome
- net.minecraft.data.worldgen.biome.SnowyTaigaMountainsBiome
- net.minecraft.data.worldgen.biome.SoulSandValleyBiome
- net.minecraft.data.worldgen.biome.SunflowerPlainsBiome
- net.minecraft.data.worldgen.biome.SwampHillsBiome
- net.minecraft.data.worldgen.biome.TaigaHillsBiome
- net.minecraft.data.worldgen.biome.TallBirchForestBiome
- net.minecraft.data.worldgen.biome.TheEndBiome
- net.minecraft.data.worldgen.biome.WarmOceanBiome
- net.minecraft.data.worldgen.biome.WoodedBadlandsBiome
- net.minecraft.data.worldgen.biome.WoodedMountainBiome
- net.minecraft.data.worldgen.Carvers
- net.minecraft.data.worldgen.Features
- net.minecraft.data.worldgen.Features$Decorators
- net.minecraft.data.worldgen.PillagerOutpostPools
- net.minecraft.data.worldgen.Pools
- net.minecraft.data.worldgen.SavannaVillagePools
- net.minecraft.data.worldgen.StructureFeatures
- net.minecraft.data.worldgen.TaigaVillagePools
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.GameTest
+ net.minecraft.gametest.framework.GameTestAssertException
- net.minecraft.gametest.framework.GameTestAssertPosException
+ net.minecraft.gametest.framework.GameTestBatch
- net.minecraft.gametest.framework.GameTestBatchRunner
+ net.minecraft.gametest.framework.GameTestBatchRunner$1
- net.minecraft.gametest.framework.GameTestEvent
+ net.minecraft.gametest.framework.GameTestGenerator
- net.minecraft.gametest.framework.GameTestHelper
+ net.minecraft.gametest.framework.GameTestHelper$1
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestRunner$1
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.StructureUtils$1
+ net.minecraft.gametest.framework.TeamcityTestReporter
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
+ net.minecraft.gametest.framework.TestReporter
+ net.minecraft.locale.Language
- net.minecraft.locale.Language$1
+ net.minecraft.locale.package-info
- net.minecraft.nbt.ByteArrayTag
+ net.minecraft.nbt.ByteArrayTag$1
- net.minecraft.nbt.ByteTag
+ net.minecraft.nbt.ByteTag$1
- net.minecraft.nbt.ByteTag$Cache
+ net.minecraft.nbt.CollectionTag
- net.minecraft.nbt.CompoundTag
+ net.minecraft.nbt.CompoundTag$1
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.LongArrayTag
- net.minecraft.nbt.LongArrayTag$1
+ net.minecraft.nbt.LongTag
- net.minecraft.nbt.LongTag$1
+ net.minecraft.nbt.LongTag$Cache
- net.minecraft.nbt.NbtAccounter
+ net.minecraft.nbt.NbtAccounter$1
- net.minecraft.nbt.NbtIo
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
+ net.minecraft.nbt.NbtOps$NbtRecordBuilder
- net.minecraft.nbt.NbtUtils
+ net.minecraft.nbt.NumericTag
- net.minecraft.nbt.package-info
- net.minecraft.nbt.ShortTag
+ net.minecraft.nbt.ShortTag$1
- net.minecraft.nbt.ShortTag$Cache
+ net.minecraft.nbt.StringTag
- net.minecraft.nbt.StringTag$1
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagTypes
+ net.minecraft.network.CipherBase
- net.minecraft.network.CipherDecoder
+ net.minecraft.network.CipherEncoder
- net.minecraft.network.CompressionDecoder
+ net.minecraft.network.CompressionEncoder
- net.minecraft.network.Connection
+ net.minecraft.network.Connection$1
- net.minecraft.network.Connection$2
+ net.minecraft.network.Connection$PacketHolder
- net.minecraft.network.ConnectionProtocol
+ net.minecraft.network.ConnectionProtocol$1
- net.minecraft.network.ConnectionProtocol$PacketSet
+ net.minecraft.network.ConnectionProtocol$ProtocolBuilder
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
+ net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerAckPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.status.ClientboundPongResponsePacket
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$10
- net.minecraft.network.syncher.EntityDataSerializers$11
+ net.minecraft.network.syncher.EntityDataSerializers$12
- net.minecraft.network.syncher.EntityDataSerializers$13
+ net.minecraft.network.syncher.EntityDataSerializers$14
- net.minecraft.network.syncher.EntityDataSerializers$15
+ net.minecraft.network.syncher.EntityDataSerializers$16
- net.minecraft.network.syncher.EntityDataSerializers$17
+ net.minecraft.network.syncher.EntityDataSerializers$18
- net.minecraft.network.syncher.EntityDataSerializers$19
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.EntityDataSerializers$5
+ net.minecraft.network.syncher.EntityDataSerializers$6
- net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.EntityDataSerializers$8
- net.minecraft.network.syncher.EntityDataSerializers$9
+ net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.obfuscate.DontObfuscateOrShrink
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
+ net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.recipebook.ServerPlaceSmeltingRecipe
- net.minecraft.resources.DelegatingOps
- net.minecraft.resources.package-info
+ net.minecraft.resources.RegistryDataPackCodec
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryReadOps
- net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.resources.RegistryReadOps$ReadCache
- net.minecraft.resources.RegistryWriteOps
+ net.minecraft.resources.ResourceKey
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$1
+ net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$1
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.EntityDataAccessor
- net.minecraft.server.commands.data.EntityDataAccessor$1
+ net.minecraft.server.commands.data.package-info
+ net.minecraft.server.commands.data.StorageDataAccessor
- net.minecraft.server.commands.data.StorageDataAccessor$1
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateBiomeCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ReplaceItemCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$Position
+ net.minecraft.server.commands.StopCommand
- net.minecraft.server.commands.StopSoundCommand
+ net.minecraft.server.commands.SummonCommand
- net.minecraft.server.commands.TagCommand
+ net.minecraft.server.commands.TeamCommand
- net.minecraft.server.commands.TeamMsgCommand
+ net.minecraft.server.commands.TeleportCommand
- net.minecraft.server.commands.TeleportCommand$LookAt
+ net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TriggerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.ConsoleInputSource
- net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServerProperties
+ net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
+ net.minecraft.server.dedicated.Settings$1
- net.minecraft.server.dedicated.Settings$MutableValue
+ net.minecraft.server.Eula
- net.minecraft.server.gui.MinecraftServerGui
+ net.minecraft.server.gui.MinecraftServerGui$1
- net.minecraft.server.gui.MinecraftServerGui$2
+ net.minecraft.server.gui.package-info
+ net.minecraft.server.gui.PlayerListComponent
- net.minecraft.server.gui.StatsComponent
- net.minecraft.server.level.BlockDestructionProgress
+ net.minecraft.server.level.ChunkHolder
- net.minecraft.server.level.ChunkHolder$1
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
+ net.minecraft.server.level.ChunkHolder$FullChunkStatus
- net.minecraft.server.level.ChunkHolder$LevelChangeListener
+ net.minecraft.server.level.ChunkHolder$PlayerProvider
- net.minecraft.server.level.ChunkMap
+ net.minecraft.server.level.ChunkMap$1
- net.minecraft.server.level.ChunkMap$2
+ net.minecraft.server.level.ChunkMap$DistanceManager
- net.minecraft.server.level.ChunkMap$TrackedEntity
+ net.minecraft.server.level.ChunkTaskPriorityQueue
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FeatureSimulator
+ net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$1
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayerGameMode
+ net.minecraft.server.level.ThreadedLevelLightEngine
- net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
+ net.minecraft.server.level.Ticket
- net.minecraft.server.level.TicketType
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.level.WorldGenTickList
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$2
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.package-info
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerGamePacketListenerImpl
+ net.minecraft.server.network.ServerGamePacketListenerImpl$1
- net.minecraft.server.network.ServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl$State
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.FolderPackResources
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$PackConstructor
- net.minecraft.server.packs.repository.Pack$Position
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$1
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.resources.SimpleResource
- net.minecraft.server.packs.VanillaPackResources
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.IpBanList
+ net.minecraft.server.players.IpBanListEntry
- net.minecraft.server.players.OldUsersConverter
+ net.minecraft.server.players.OldUsersConverter$1
- net.minecraft.server.players.OldUsersConverter$2
+ net.minecraft.server.players.OldUsersConverter$3
- net.minecraft.server.players.OldUsersConverter$4
+ net.minecraft.server.players.OldUsersConverter$5
- net.minecraft.server.players.OldUsersConverter$ConversionError
+ net.minecraft.server.players.package-info
+ net.minecraft.server.players.PlayerList
- net.minecraft.server.players.PlayerList$1
+ net.minecraft.server.players.ServerOpList
- net.minecraft.server.players.ServerOpListEntry
+ net.minecraft.server.players.StoredUserEntry
- net.minecraft.server.players.StoredUserList
+ net.minecraft.server.players.UserBanList
- net.minecraft.server.players.UserBanListEntry
+ net.minecraft.server.players.UserWhiteList
- net.minecraft.server.players.UserWhiteListEntry
- net.minecraft.server.rcon.NetworkDataOutputStream
+ net.minecraft.server.rcon.package-info
+ net.minecraft.server.rcon.PktUtils
- net.minecraft.server.rcon.RconConsoleSource
- net.minecraft.server.rcon.thread.GenericThread
+ net.minecraft.server.rcon.thread.package-info
+ net.minecraft.server.rcon.thread.QueryThreadGs4
- net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
+ net.minecraft.server.rcon.thread.RconClient
- net.minecraft.server.rcon.thread.RconThread
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerResources
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
- net.minecraft.sounds.Music
+ net.minecraft.sounds.Musics
+ net.minecraft.sounds.package-info
- net.minecraft.sounds.SoundEvent
+ net.minecraft.sounds.SoundEvents
- net.minecraft.sounds.SoundSource
- net.minecraft.stats.package-info
- net.minecraft.stats.RecipeBook
+ net.minecraft.stats.RecipeBookSettings
- net.minecraft.stats.RecipeBookSettings$TypeSettings
+ net.minecraft.stats.ServerRecipeBook
- net.minecraft.stats.ServerStatsCounter
+ net.minecraft.stats.Stat
- net.minecraft.stats.StatFormatter
- net.minecraft.stats.Stats
+ net.minecraft.stats.StatsCounter
+ net.minecraft.stats.StatType
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$1
+ net.minecraft.tags.StaticTagHelper$Wrapper
- net.minecraft.tags.StaticTags
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$1
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$Named
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagCollection$1
+ net.minecraft.tags.TagContainer
- net.minecraft.tags.TagContainer$1
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagManager
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.Codecs$1
+ net.minecraft.util.Codecs$3
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkStatusFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix2
+ net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
- net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
+ net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.MapIdFix
+ net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
- net.minecraft.util.datafix.fixes.MissingDimensionFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRename
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.Util$4
- net.minecraft.Util$6
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Strider$StriderGroupData
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
+ net.minecraft.world.entity.npc.Villager
- net.minecraft.world.entity.npc.VillagerData
+ net.minecraft.world.entity.npc.VillagerDataHolder
- net.minecraft.world.entity.npc.VillagerProfession
+ net.minecraft.world.entity.npc.VillagerTrades
- net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.VillagerType$1
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$Pickup
- net.minecraft.world.entity.projectile.AbstractHurtingProjectile
+ net.minecraft.world.entity.projectile.Arrow
- net.minecraft.world.entity.projectile.DragonFireball
+ net.minecraft.world.entity.projectile.EvokerFangs
- net.minecraft.world.entity.projectile.EyeOfEnder
+ net.minecraft.world.entity.projectile.Fireball
- net.minecraft.world.entity.projectile.FireworkRocketEntity
+ net.minecraft.world.entity.projectile.FishingHook
- net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$FishHookState
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.projectile.ItemSupplier
- net.minecraft.world.entity.projectile.LargeFireball
+ net.minecraft.world.entity.projectile.LlamaSpit
- net.minecraft.world.entity.projectile.package-info
- net.minecraft.world.entity.projectile.Projectile
+ net.minecraft.world.entity.projectile.ProjectileUtil
- net.minecraft.world.entity.projectile.ShulkerBullet
+ net.minecraft.world.entity.projectile.SmallFireball
- net.minecraft.world.entity.projectile.Snowball
+ net.minecraft.world.entity.projectile.SpectralArrow
- net.minecraft.world.entity.projectile.ThrowableItemProjectile
+ net.minecraft.world.entity.projectile.ThrowableProjectile
- net.minecraft.world.entity.projectile.ThrownEgg
+ net.minecraft.world.entity.projectile.ThrownEnderpearl
- net.minecraft.world.entity.projectile.ThrownExperienceBottle
+ net.minecraft.world.entity.projectile.ThrownPotion
- net.minecraft.world.entity.projectile.ThrownTrident
+ net.minecraft.world.entity.projectile.WitherSkull
+ net.minecraft.world.entity.raid.package-info
+ net.minecraft.world.entity.raid.Raid
- net.minecraft.world.entity.raid.Raid$1
- net.minecraft.world.entity.raid.Raid$RaiderType
+ net.minecraft.world.entity.raid.Raid$RaidStatus
+ net.minecraft.world.entity.raid.Raider
- net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
+ net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- net.minecraft.world.entity.raid.Raider$RaiderCelebration
+ net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
- net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.schedule.Activity
+ net.minecraft.world.entity.schedule.Keyframe
- net.minecraft.world.entity.schedule.package-info
- net.minecraft.world.entity.schedule.Schedule
+ net.minecraft.world.entity.schedule.ScheduleBuilder
- net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
+ net.minecraft.world.entity.schedule.Timeline
+ net.minecraft.world.entity.vehicle.AbstractMinecart
- net.minecraft.world.entity.vehicle.AbstractMinecart$1
+ net.minecraft.world.entity.vehicle.AbstractMinecart$Type
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$1
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.item.AirItem
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.DirectionalPlaceContext$1
+ net.minecraft.world.item.UseOnContext
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.biome.BadlandsPlateauBiome
+ net.minecraft.world.level.biome.BambooJungleHillsBiome
+ net.minecraft.world.level.biome.BeachBiome
+ net.minecraft.world.level.biome.BiomeDefaultFeatures
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
- net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.BirchForestHillsBiome
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.ColdOceanBiome
+ net.minecraft.world.level.biome.DarkForestBiome
+ net.minecraft.world.level.biome.DeepColdOceanBiome
+ net.minecraft.world.level.biome.DeepLukeWarmOceanBiome
+ net.minecraft.world.level.biome.DeepWarmOceanBiome
+ net.minecraft.world.level.biome.DesertHillsBiome
+ net.minecraft.world.level.biome.EndBarrensBiome
+ net.minecraft.world.level.biome.EndMidlandsBiome
+ net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.ForestFlowerBiome
+ net.minecraft.world.level.biome.FrozenRiverBiome
- net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
+ net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ net.minecraft.world.level.biome.GiantTreeTaigaHillsBiome
+ net.minecraft.world.level.biome.IceSpikesBiome
+ net.minecraft.world.level.biome.JungleEdgeBiome
+ net.minecraft.world.level.biome.LukeWarmOceanBiome
+ net.minecraft.world.level.biome.ModifiedGravellyMountainsBiome
+ net.minecraft.world.level.biome.ModifiedJungleEdgeBiome
+ net.minecraft.world.level.biome.MountainBiome
+ net.minecraft.world.level.biome.MushroomFieldsBiome
+ net.minecraft.world.level.biome.OceanBiome
+ net.minecraft.world.level.biome.PlainsBiome
+ net.minecraft.world.level.biome.SavannaBiome
+ net.minecraft.world.level.biome.ShatteredSavannaBiome
+ net.minecraft.world.level.biome.SmallEndIslandsBiome
+ net.minecraft.world.level.biome.SnowyMountainsBiome
+ net.minecraft.world.level.biome.SnowyTaigaHillsBiome
+ net.minecraft.world.level.biome.SnowyTundraBiome
+ net.minecraft.world.level.biome.StoneShoreBiome
+ net.minecraft.world.level.biome.SwampBiome
+ net.minecraft.world.level.biome.TaigaBiome
+ net.minecraft.world.level.biome.TaigaMountainsBiome
+ net.minecraft.world.level.biome.TallBirchHillsBiome
+ net.minecraft.world.level.biome.WarmOceanBiome
+ net.minecraft.world.level.biome.WoodedBadlandsBiome
+ net.minecraft.world.level.biome.WoodedMountainBiome
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$RuntimePiece
+ net.minecraft.world.level.block.NetherPortalBlock$PortalShape
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
- net.minecraft.world.level.block.PumpkinBlock
+ net.minecraft.world.level.block.RailBlock
- net.minecraft.world.level.block.RailBlock$1
+ net.minecraft.world.level.block.RailState
- net.minecraft.world.level.block.RailState$1
- net.minecraft.world.level.block.RedstoneLampBlock
+ net.minecraft.world.level.block.RedStoneOreBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock
- net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
+ net.minecraft.world.level.block.RedstoneWallTorchBlock
- net.minecraft.world.level.block.RedStoneWireBlock
+ net.minecraft.world.level.block.RedStoneWireBlock$1
- net.minecraft.world.level.block.RenderShape
+ net.minecraft.world.level.block.RepeaterBlock
- net.minecraft.world.level.block.RespawnAnchorBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.Seagrass
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
+ net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$1
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrass
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVines
- net.minecraft.world.level.block.TwistingVinesPlant
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVines
- net.minecraft.world.level.block.WeepingVinesPlant
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$1
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkBiomeContainer
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.FeatureAccess
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.OldDataLayer
+ net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.ProtoTickList
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.OldChunkStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.DefaultExplosionDamageCalculator
- net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.LevelStem
- net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Decoratable
+ net.minecraft.world.level.levelgen.feature.BastionHoglinStablePools
+ net.minecraft.world.level.levelgen.feature.BastionPieces
+ net.minecraft.world.level.levelgen.feature.BastionSharedPools
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MultiJigsawConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSpheroidConfiguration$Builder
+ net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.StrongholdConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.StructureFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$Factory
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.JigsawFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PlainVillagePools
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaVillagePools
+ net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.ChancePassthroughDecorator
+ net.minecraft.world.level.levelgen.placement.ChorusPlantPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.CountBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.CountDecorator
+ net.minecraft.world.level.levelgen.placement.CountHeighmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.CountHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.CountTopSolidDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
+ net.minecraft.world.level.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecorator
- net.minecraft.world.level.levelgen.placement.DecorationContext
+ net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
- net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.FrequencyChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.HeightmapDecorator
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.ChanceRangeDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
+ net.minecraft.world.level.levelgen.placement.nether.FireDecorator
- net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
+ net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.NoiseHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
- net.minecraft.world.level.levelgen.placement.RangeDecorator
+ net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
- net.minecraft.world.level.levelgen.placement.Spread32Decorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalInfo
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.RegistryAccess$RegistryHolder +14M -4M | +2P -2P
```
```
XXX.minecraft.core.SectionPos +7M
```
```
XXX.network.chat.CommonComponents +1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P -1P
```
```
XXX.protocol.game.ClientboundBlockUpdatePacket +1M
```
```
XXX.protocol.game.ClientboundLevelChunkPacket +1M -1M | +1P -1P
```
```
XXX.ai.behavior.AcquirePoi +5M -4M | +1P
```
```
XXX.ai.memory.MemoryModuleType +2P
```
```
XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal +1M -1M
```
```
XXX.monster.piglin.Piglin -1M | -2P
```
```
XXX.world.item.BoneMealItem +1M -1M
```
```
XXX.world.item.EndCrystalItem +1M -1M
```
```
XXX.world.item.FireChargeItem +1M -1M
```
```
XXX.world.item.FlintAndSteelItem +3M -3M
```
```
XXX.world.item.GameMasterBlockItem +1M -1M
```
```
XXX.world.item.HoeItem +2M -2M
```
```
XXX.world.item.LeadItem +1M -1M
```
```
XXX.world.item.MapItem +2M -2M
```
```
XXX.world.item.MinecartItem +1M -1M
```
```
XXX.world.item.StandingAndWallBlockItem +1M -1M
```
```
XXX.world.level.BlockGetter +3M
```
```
XXX.level.biome.MultiNoiseBiomeSource +6M -3M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +1M -1M
```
```
XXX.level.block.BambooBlock +1M -1M
```
```
XXX.level.block.BannerBlock +1M -1M
```
```
XXX.level.block.BaseCoralWallFanBlock +1M -1M
```
```
XXX.level.block.BaseFireBlock +4M -3M
```
```
XXX.level.block.BaseRailBlock +1M -1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +1M -1M
```
```
XXX.level.block.BellBlock +1M -1M
```
```
XXX.level.block.CarvedPumpkinBlock +1M -1M
```
```
XXX.level.block.ChainBlock +1M -1M
```
```
XXX.level.block.ChorusPlantBlock +1M -1M
```
```
XXX.level.block.ConduitBlock +1M -1M
```
```
XXX.level.block.DiodeBlock +1M -1M
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.EndRodBlock +1M -1M
```
```
XXX.level.block.EnderChestBlock +1M -1M
```
```
XXX.level.block.FaceAttachedHorizontalDirectionalBlock +1M -1M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.GrowingPlantBodyBlock +1M -1M
```
```
XXX.level.block.HugeMushroomBlock +1M -1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.KelpBlock +1M -1M
```
```
XXX.level.block.LadderBlock +1M -1M
```
```
XXX.level.block.Lantern +1M -1M
```
```
XXX.level.block.LecternBlock +1M -1M
```
```
XXX.level.block.NetherPortalBlock -3M
```
```
XXX.block.piston.PistonBaseBlock +1M -1M
```
```
XXX.block.state.BlockBehaviour +1M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M -1M
```
```
XXX.state.pattern.BlockPattern$BlockPatternMatch -1M
```
```
XXX.level.levelgen.GenerationStep$Decoration +1M -5M | -3P
```
```
XXX.levelgen.carver.WorldCarver +1M -2M
```
```
XXX.levelgen.feature.BastionFeature +1M -2M
```
```
XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart +2M -2M
```
```
XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart +2M -2M
```
```
XXX.levelgen.feature.PillagerOutpostFeature +1M -2M
```
```
XXX.levelgen.feature.SeagrassFeature +1M -1M
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +2M -2M
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +6M -6M | +2P -4P
```
```
XXX.feature.configurations.DecoratedFeatureConfiguration +2M -2M | +1P -1P
```
```
XXX.feature.configurations.DeltaFeatureConfiguration +8M -5M | +2P -3P
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart +2M -2M
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +2M -2M
```
```
XXX.levelgen.structure.PoolElementStructurePiece +2M -2M
```
```
XXX.levelgen.structure.StructureStart$1 +2M -2M
```
```
XXX.structure.templatesystem.StructureProcessorType +3P -1P
```
```
XXX.levelgen.surfacebuilders.SurfaceBuilder +1M -2M | -3P
```
```
XXX.level.storage.McRegionUpgrader +2M -2M
```

</details>






























































































































































<details>
<summary>
net.minecraft.core.RegistryAccess$RegistryHolder
</summary>

```diff
- boolean lambda$null$3(Map$Entry)
- Codec captureMap(UnboundedMapCodec)
- Codec lambda$null$1(ResourceKey,MapCodec)
- Codec makeDirectCodec()
- DataResult getCodec(ResourceKey)
- DataResult lambda$getCodec$5(RegistryAccess$RegistryData)
- DataResult lambda$getCodec$6(ResourceKey)
- DataResult lambda$makeDirectCodec$0(MappedRegistry)
- DataResult lambda$makeDirectCodec$2(ResourceKey)
- Map access$000(RegistryAccess$RegistryHolder)
- Map lambda$captureMap$4(RegistryAccess$RegistryHolder)
- MappedRegistry createRegistry(ResourceKey)
+ MappedRegistry lambda$static$0(RegistryAccess$RegistryHolder)
+ Registry dimensionTypes()
- void <init>(Map)
+ void <init>(MappedRegistry)
+ void registerDimension(ResourceKey,DimensionType)
- WritableRegistry lambda$registry$7(MappedRegistry)
```

</details>
<details>
<summary>
net.minecraft.core.SectionPos
</summary>

```diff
- BlockPos relativeToBlockPos(short)
- int relativeToBlockX(short)
- int relativeToBlockY(short)
- int relativeToBlockZ(short)
- int sectionRelativeX(short)
- int sectionRelativeY(short)
- int sectionRelativeZ(short)
```

</details>






























<details>
<summary>
net.minecraft.network.chat.CommonComponents
</summary>

```diff
- MutableComponent optionStatus(Component,boolean)
```

</details>























<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
</summary>

```diff
- void <init>(BlockPos,BlockState)
```

</details>












<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
</summary>

```diff
+ ChunkBiomeContainer getBiomes()
- int[] getBiomes()
```

</details>

















































































































































<details>
<summary>
net.minecraft.world.entity.ai.behavior.AcquirePoi
</summary>

```diff
+ AcquirePoi$JitteredLinearRetry lambda$start$4(PathfinderMob,long,long)
- AcquirePoi$JitteredLinearRetry lambda$start$5(PathfinderMob,long,long)
- void <init>(PoiType,MemoryModuleType,boolean,Optional)
+ void <init>(PoiType,MemoryModuleType,boolean)
- void <init>(PoiType,MemoryModuleType,MemoryModuleType,boolean,Optional)
+ void <init>(PoiType,MemoryModuleType,MemoryModuleType,boolean)
- void lambda$null$3(ServerLevel,PathfinderMob,Byte)
+ void lambda$start$3(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
- void lambda$start$4(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
```

</details>





























































































































































































































<details>
<summary>
net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
</summary>

```diff
- void <init>(EnderMan,Predicate)
+ void <init>(EnderMan)
```

</details>
















































<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
+ void sendDebugPackets()
```

</details>




<details>
<summary>
net.minecraft.world.item.BoneMealItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>

















<details>
<summary>
net.minecraft.world.item.EndCrystalItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>

<details>
<summary>
net.minecraft.world.item.FireChargeItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>


<details>
<summary>
net.minecraft.world.item.FlintAndSteelItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ void lambda$useOn$0(UseOnContext,Player)
- void lambda$useOn$0(UseOnContext,Player)
+ void lambda$useOn$1(UseOnContext,Player)
- void lambda$useOn$1(UseOnContext,Player)
```

</details>
<details>
<summary>
net.minecraft.world.item.GameMasterBlockItem
</summary>

```diff
+ BlockState getPlacementState(BlockPlaceContext)
- BlockState getPlacementState(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoeItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ void lambda$useOn$0(UseOnContext,Player)
- void lambda$useOn$0(UseOnContext,Player)
```

</details>







<details>
<summary>
net.minecraft.world.item.LeadItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ ItemStack lockMap(Level,ItemStack)
- void lockMap(Level,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.MinecartItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>










<details>
<summary>
net.minecraft.world.item.StandingAndWallBlockItem
</summary>

```diff
+ BlockState getPlacementState(BlockPlaceContext)
- BlockState getPlacementState(BlockPlaceContext)
```

</details>


























































<details>
<summary>
net.minecraft.world.level.BlockGetter
</summary>

```diff
- double getBlockFloorHeight(BlockPos)
- double getBlockFloorHeight(VoxelShape,Supplier)
- VoxelShape lambda$getBlockFloorHeight$2(BlockPos)
```

</details>


















<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
- Biome lambda$defaultNether$10()
- Biome lambda$defaultNether$11()
- Biome lambda$defaultNether$12()
- Biome lambda$defaultNether$13()
- Biome lambda$defaultNether$9()
+ Float lambda$getNoiseBiome$11(Biome$ClimateParameters,Pair)
- Float lambda$getNoiseBiome$14(Biome$ClimateParameters,Pair)
+ Pair lambda$null$9(Biome,Biome$ClimateParameters)
+ Stream lambda$defaultNether$10(Biome)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.BaseCoralWallFanBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
- boolean canBePlacedAt(Level,BlockPos,Direction)
+ boolean canBePlacedAt(LevelAccessor,BlockPos)
- boolean inPortalDimension(Level)
- boolean isPortal(Level,BlockPos,Direction)
+ boolean isPortal(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.CarvedPumpkinBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChainBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.ConduitBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.DiodeBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBodyBlock
</summary>

```diff
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
- boolean canBeReplaced(BlockState,BlockPlaceContext)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.HugeMushroomBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LadderBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Lantern
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.NetherPortalBlock
</summary>

```diff
+ BlockPattern$BlockPatternMatch getPortalShape(LevelAccessor,BlockPos)
+ boolean trySpawnPortal(LevelAccessor,BlockPos)
+ NetherPortalBlock$PortalShape isPortal(LevelAccessor,BlockPos)
```

</details>
















<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
- boolean canBeReplaced(BlockState,BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
+ boolean canBeReplaced(BlockPlaceContext)
- boolean canBeReplaced(BlockPlaceContext)
- boolean isFaceSturdy(BlockGetter,BlockPos,Direction,SupportType)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
</summary>

```diff
+ BlockPattern$PortalInfo getPortalOutput(Direction,BlockPos,double,Vec3,double)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Decoration
</summary>

```diff
+ GenerationStep$Decoration byName(String)
+ GenerationStep$Decoration lambda$static$0(GenerationStep$Decoration)
+ String getName()
+ String getSerializedName()
+ void <init>(String,int,String)
- void <init>(String,int)
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
+ CarverConfiguration lambda$new$1(ConfiguredWorldCarver)
- ConfiguredWorldCarver configured(CarverConfiguration)
+ ConfiguredWorldCarver lambda$new$0(CarverConfiguration)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,MultiJigsawConfiguration)
+ StructureFeature$StructureStartFactory getStartFactory()
```

</details>















<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
+ StructureFeature$StructureStartFactory getStartFactory()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SeagrassFeature
</summary>

```diff
- boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,ProbabilityFeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,SeagrassFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ Integer lambda$null$0(ColumnFeatureConfiguration)
+ Integer lambda$null$1(ColumnFeatureConfiguration)
+ Integer lambda$null$2(ColumnFeatureConfiguration)
+ Integer lambda$null$3(ColumnFeatureConfiguration)
- UniformInt height()
- UniformInt lambda$null$0(ColumnFeatureConfiguration)
- UniformInt lambda$null$1(ColumnFeatureConfiguration)
- UniformInt reach()
+ void <init>(int,int,int,int)
- void <init>(UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
</summary>

```diff
+ ConfiguredFeature lambda$null$0(DecoratedFeatureConfiguration)
- Supplier lambda$null$0(DecoratedFeatureConfiguration)
+ void <init>(ConfiguredFeature,ConfiguredDecorator)
- void <init>(Supplier,ConfiguredDecorator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ App lambda$static$5(RecordCodecBuilder$Instance)
- BlockState contents()
- BlockState rim()
+ Integer lambda$null$2(DeltaFeatureConfiguration)
+ Integer lambda$null$3(DeltaFeatureConfiguration)
+ Integer lambda$null$4(DeltaFeatureConfiguration)
- UniformInt lambda$null$2(DeltaFeatureConfiguration)
- UniformInt lambda$null$3(DeltaFeatureConfiguration)
- UniformInt rimSize()
- UniformInt size()
+ void <init>(BlockState,BlockState,int,int,int)
- void <init>(BlockState,BlockState,UniformInt,UniformInt)
```

</details>








































<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>













<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
</summary>

```diff
+ void <init>(StructureManager,CompoundTag,StructurePieceType)
- void <init>(StructureManager,CompoundTag)
- void <init>(StructureManager,StructurePoolElement,BlockPos,int,Rotation,BoundingBox)
+ void <init>(StructurePieceType,StructureManager,StructurePoolElement,BlockPos,int,Rotation,BoundingBox)
```

</details>
















<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart$1
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration)
```

</details>































<details>
<summary>
net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
</summary>

```diff
- ConfiguredSurfaceBuilder configured(SurfaceBuilderConfiguration)
+ ConfiguredSurfaceBuilder lambda$new$0(SurfaceBuilderConfiguration)
+ SurfaceBuilderConfiguration lambda$new$1(ConfiguredSurfaceBuilder)
```

</details>





































































<details>
<summary>
net.minecraft.world.level.storage.McRegionUpgrader
</summary>

```diff
+ void convertRegion(File,File,BiomeSource,int,int,ProgressListener)
- void convertRegion(RegistryAccess$RegistryHolder,File,File,BiomeSource,int,int,ProgressListener)
+ void convertRegions(File,Iterable,BiomeSource,int,int,ProgressListener)
- void convertRegions(RegistryAccess$RegistryHolder,File,Iterable,BiomeSource,int,int,ProgressListener)
```

</details>
























































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.BlockUtil
- net.minecraft.BlockUtil$IntBounds
- net.minecraft.core.BlockPos$5
+ net.minecraft.core.BlockPos$MutableBlockPos
- net.minecraft.core.BlockSource
+ net.minecraft.core.BlockSourceImpl
- net.minecraft.core.Cursor3D
+ net.minecraft.core.DefaultedRegistry
- net.minecraft.core.Direction
+ net.minecraft.core.Direction$1
- net.minecraft.core.Direction$Axis
+ net.minecraft.core.Direction$Axis$1
- net.minecraft.core.Direction$Axis$2
+ net.minecraft.core.Direction$Axis$3
- net.minecraft.core.Direction$AxisDirection
+ net.minecraft.core.Direction$Plane
- net.minecraft.core.Direction8
+ net.minecraft.core.FrontAndTop
- net.minecraft.core.GlobalPos
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.MappedRegistry
- net.minecraft.core.NonNullList
+ net.minecraft.core.Position
- net.minecraft.core.PositionImpl
+ net.minecraft.core.Registry
- net.minecraft.core.RegistryAccess
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.HashCache
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLoot
- net.minecraft.data.loot.ChestLoot
+ net.minecraft.data.loot.EntityLoot
- net.minecraft.data.loot.FishingLoot
+ net.minecraft.data.loot.GiftLoot
- net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.PiglinBarterLoot
+ net.minecraft.data.Main
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
+ net.minecraft.data.models.BlockModelGenerators$TintState
- net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$1
- net.minecraft.data.models.blockstates.Condition$CompositeCondition
+ net.minecraft.data.models.blockstates.Condition$Operation
- net.minecraft.data.models.blockstates.Condition$TerminalCondition
+ net.minecraft.data.models.blockstates.MultiPartGenerator
- net.minecraft.data.models.blockstates.MultiPartGenerator$1
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
- net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
+ net.minecraft.data.models.blockstates.PropertyDispatch$1
- net.minecraft.data.models.blockstates.PropertyDispatch$C1
+ net.minecraft.data.models.blockstates.PropertyDispatch$C2
- net.minecraft.data.models.blockstates.PropertyDispatch$C3
+ net.minecraft.data.models.blockstates.PropertyDispatch$C4
- net.minecraft.data.models.blockstates.PropertyDispatch$C5
+ net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
- net.minecraft.data.models.blockstates.Selector
+ net.minecraft.data.models.blockstates.Variant
- net.minecraft.data.models.blockstates.VariantProperties
+ net.minecraft.data.models.blockstates.VariantProperties$Rotation
- net.minecraft.data.models.blockstates.VariantProperty
+ net.minecraft.data.models.blockstates.VariantProperty$Value
+ net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.model.DelegatedModel
- net.minecraft.data.models.model.ModelLocationUtils
+ net.minecraft.data.models.model.ModelTemplate
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
- net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.package-info
+ net.minecraft.data.recipes.RecipeProvider
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapedRecipeBuilder$Result
- net.minecraft.data.recipes.ShapelessRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
- net.minecraft.data.recipes.SingleItemRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
- net.minecraft.data.recipes.SpecialRecipeBuilder
+ net.minecraft.data.recipes.SpecialRecipeBuilder$1
- net.minecraft.data.recipes.UpgradeRecipeBuilder
+ net.minecraft.data.recipes.UpgradeRecipeBuilder$Result
+ net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1
+ net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.biome.BadlandsBiome
- net.minecraft.data.worldgen.biome.BambooJungleBiome
- net.minecraft.data.worldgen.biome.BasaltDeltasBiome
- net.minecraft.data.worldgen.biome.BirchForestBiome
- net.minecraft.data.worldgen.biome.ColdOceanBiome
- net.minecraft.data.worldgen.biome.DarkForestBiome
- net.minecraft.data.worldgen.biome.DeepColdOceanBiome
- net.minecraft.data.worldgen.biome.DeepLukeWarmOceanBiome
- net.minecraft.data.worldgen.biome.DeepWarmOceanBiome
- net.minecraft.data.worldgen.biome.DesertHillsBiome
- net.minecraft.data.worldgen.biome.EndBarrensBiome
- net.minecraft.data.worldgen.biome.EndMidlandsBiome
- net.minecraft.data.worldgen.biome.ForestBiome
- net.minecraft.data.worldgen.biome.FrozenOceanBiome
- net.minecraft.data.worldgen.biome.GiantSpruceTaigaBiome
- net.minecraft.data.worldgen.biome.GiantTreeTaigaBiome
- net.minecraft.data.worldgen.biome.GravellyMountainsBiome
- net.minecraft.data.worldgen.biome.JungleBiome
- net.minecraft.data.worldgen.biome.JungleHillsBiome
- net.minecraft.data.worldgen.biome.ModifiedBadlandsPlateauBiome
- net.minecraft.data.worldgen.biome.ModifiedJungleBiome
- net.minecraft.data.worldgen.biome.ModifiedWoodedBadlandsPlateauBiome
- net.minecraft.data.worldgen.biome.MountainEdgeBiome
- net.minecraft.data.worldgen.biome.MushroomFieldsShoreBiome
- net.minecraft.data.worldgen.biome.OceanBiome
- net.minecraft.data.worldgen.biome.RiverBiome
- net.minecraft.data.worldgen.biome.SavannaPlateauBiome
- net.minecraft.data.worldgen.biome.ShatteredSavannaPlateauBiome
- net.minecraft.data.worldgen.biome.SnowyBeachBiome
- net.minecraft.data.worldgen.biome.SnowyTaigaBiome
- net.minecraft.data.worldgen.biome.SnowyTaigaMountainsBiome
- net.minecraft.data.worldgen.biome.SoulSandValleyBiome
- net.minecraft.data.worldgen.biome.SunflowerPlainsBiome
- net.minecraft.data.worldgen.biome.SwampHillsBiome
- net.minecraft.data.worldgen.biome.TaigaHillsBiome
- net.minecraft.data.worldgen.biome.TallBirchForestBiome
- net.minecraft.data.worldgen.biome.TheEndBiome
- net.minecraft.data.worldgen.biome.WarmOceanBiome
- net.minecraft.data.worldgen.biome.WoodedBadlandsBiome
- net.minecraft.data.worldgen.biome.WoodedMountainBiome
- net.minecraft.data.worldgen.Carvers
- net.minecraft.data.worldgen.Features
- net.minecraft.data.worldgen.Features$Decorators
- net.minecraft.data.worldgen.PillagerOutpostPools
- net.minecraft.data.worldgen.Pools
- net.minecraft.data.worldgen.SavannaVillagePools
- net.minecraft.data.worldgen.StructureFeatures
- net.minecraft.data.worldgen.TaigaVillagePools
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.GameTest
+ net.minecraft.gametest.framework.GameTestAssertException
- net.minecraft.gametest.framework.GameTestAssertPosException
+ net.minecraft.gametest.framework.GameTestBatch
- net.minecraft.gametest.framework.GameTestBatchRunner
+ net.minecraft.gametest.framework.GameTestBatchRunner$1
- net.minecraft.gametest.framework.GameTestEvent
+ net.minecraft.gametest.framework.GameTestGenerator
- net.minecraft.gametest.framework.GameTestHelper
+ net.minecraft.gametest.framework.GameTestHelper$1
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestRunner$1
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.StructureUtils$1
+ net.minecraft.gametest.framework.TeamcityTestReporter
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
+ net.minecraft.gametest.framework.TestReporter
+ net.minecraft.locale.Language
- net.minecraft.locale.Language$1
+ net.minecraft.locale.package-info
- net.minecraft.nbt.ByteArrayTag
+ net.minecraft.nbt.ByteArrayTag$1
- net.minecraft.nbt.ByteTag
+ net.minecraft.nbt.ByteTag$1
- net.minecraft.nbt.ByteTag$Cache
+ net.minecraft.nbt.CollectionTag
- net.minecraft.nbt.CompoundTag
+ net.minecraft.nbt.CompoundTag$1
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.LongArrayTag
- net.minecraft.nbt.LongArrayTag$1
+ net.minecraft.nbt.LongTag
- net.minecraft.nbt.LongTag$1
+ net.minecraft.nbt.LongTag$Cache
- net.minecraft.nbt.NbtAccounter
+ net.minecraft.nbt.NbtAccounter$1
- net.minecraft.nbt.NbtIo
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
+ net.minecraft.nbt.NbtOps$NbtRecordBuilder
- net.minecraft.nbt.NbtUtils
+ net.minecraft.nbt.NumericTag
- net.minecraft.nbt.package-info
- net.minecraft.nbt.ShortTag
+ net.minecraft.nbt.ShortTag$1
- net.minecraft.nbt.ShortTag$Cache
+ net.minecraft.nbt.StringTag
- net.minecraft.nbt.StringTag$1
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagTypes
+ net.minecraft.network.CipherBase
- net.minecraft.network.CipherDecoder
+ net.minecraft.network.CipherEncoder
- net.minecraft.network.CompressionDecoder
+ net.minecraft.network.CompressionEncoder
- net.minecraft.network.Connection
+ net.minecraft.network.Connection$1
- net.minecraft.network.Connection$2
+ net.minecraft.network.Connection$PacketHolder
- net.minecraft.network.ConnectionProtocol
+ net.minecraft.network.ConnectionProtocol$1
- net.minecraft.network.ConnectionProtocol$PacketSet
+ net.minecraft.network.ConnectionProtocol$ProtocolBuilder
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
+ net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerAckPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.status.ClientboundPongResponsePacket
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$10
- net.minecraft.network.syncher.EntityDataSerializers$11
+ net.minecraft.network.syncher.EntityDataSerializers$12
- net.minecraft.network.syncher.EntityDataSerializers$13
+ net.minecraft.network.syncher.EntityDataSerializers$14
- net.minecraft.network.syncher.EntityDataSerializers$15
+ net.minecraft.network.syncher.EntityDataSerializers$16
- net.minecraft.network.syncher.EntityDataSerializers$17
+ net.minecraft.network.syncher.EntityDataSerializers$18
- net.minecraft.network.syncher.EntityDataSerializers$19
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.EntityDataSerializers$5
+ net.minecraft.network.syncher.EntityDataSerializers$6
- net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.EntityDataSerializers$8
- net.minecraft.network.syncher.EntityDataSerializers$9
+ net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.obfuscate.DontObfuscateOrShrink
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.NarrationHelper
+ net.minecraft.realms.package-info
- net.minecraft.realms.RealmsBridge
+ net.minecraft.realms.RealmsConnect
- net.minecraft.realms.RealmsConnect$1
+ net.minecraft.realms.RealmsLabel
- net.minecraft.realms.RealmsObjectSelectionList
+ net.minecraft.realms.RealmsScreen
- net.minecraft.realms.RealmsServerAddress
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.recipebook.ServerPlaceSmeltingRecipe
- net.minecraft.resources.DelegatingOps
- net.minecraft.resources.package-info
+ net.minecraft.resources.RegistryDataPackCodec
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryReadOps
- net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.resources.RegistryReadOps$ReadCache
- net.minecraft.resources.RegistryWriteOps
+ net.minecraft.resources.ResourceKey
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$1
+ net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$1
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.EntityDataAccessor
- net.minecraft.server.commands.data.EntityDataAccessor$1
+ net.minecraft.server.commands.data.package-info
+ net.minecraft.server.commands.data.StorageDataAccessor
- net.minecraft.server.commands.data.StorageDataAccessor$1
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateBiomeCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ReplaceItemCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$Position
+ net.minecraft.server.commands.StopCommand
- net.minecraft.server.commands.StopSoundCommand
+ net.minecraft.server.commands.SummonCommand
- net.minecraft.server.commands.TagCommand
+ net.minecraft.server.commands.TeamCommand
- net.minecraft.server.commands.TeamMsgCommand
+ net.minecraft.server.commands.TeleportCommand
- net.minecraft.server.commands.TeleportCommand$LookAt
+ net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TriggerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.ConsoleInputSource
- net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServerProperties
+ net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
+ net.minecraft.server.dedicated.Settings$1
- net.minecraft.server.dedicated.Settings$MutableValue
+ net.minecraft.server.Eula
- net.minecraft.server.gui.MinecraftServerGui
+ net.minecraft.server.gui.MinecraftServerGui$1
- net.minecraft.server.gui.MinecraftServerGui$2
+ net.minecraft.server.gui.package-info
+ net.minecraft.server.gui.PlayerListComponent
- net.minecraft.server.gui.StatsComponent
- net.minecraft.server.level.BlockDestructionProgress
+ net.minecraft.server.level.ChunkHolder
- net.minecraft.server.level.ChunkHolder$1
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
+ net.minecraft.server.level.ChunkHolder$FullChunkStatus
- net.minecraft.server.level.ChunkHolder$LevelChangeListener
+ net.minecraft.server.level.ChunkHolder$PlayerProvider
- net.minecraft.server.level.ChunkMap
+ net.minecraft.server.level.ChunkMap$1
- net.minecraft.server.level.ChunkMap$2
+ net.minecraft.server.level.ChunkMap$DistanceManager
- net.minecraft.server.level.ChunkMap$TrackedEntity
+ net.minecraft.server.level.ChunkTaskPriorityQueue
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FeatureSimulator
+ net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$1
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayerGameMode
+ net.minecraft.server.level.ThreadedLevelLightEngine
- net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
+ net.minecraft.server.level.Ticket
- net.minecraft.server.level.TicketType
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.level.WorldGenTickList
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$2
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.package-info
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerGamePacketListenerImpl
+ net.minecraft.server.network.ServerGamePacketListenerImpl$1
- net.minecraft.server.network.ServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl$State
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.FolderPackResources
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$PackConstructor
- net.minecraft.server.packs.repository.Pack$Position
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$1
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.resources.SimpleResource
- net.minecraft.server.packs.VanillaPackResources
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.IpBanList
+ net.minecraft.server.players.IpBanListEntry
- net.minecraft.server.players.OldUsersConverter
+ net.minecraft.server.players.OldUsersConverter$1
- net.minecraft.server.players.OldUsersConverter$2
+ net.minecraft.server.players.OldUsersConverter$3
- net.minecraft.server.players.OldUsersConverter$4
+ net.minecraft.server.players.OldUsersConverter$5
- net.minecraft.server.players.OldUsersConverter$ConversionError
+ net.minecraft.server.players.package-info
+ net.minecraft.server.players.PlayerList
- net.minecraft.server.players.PlayerList$1
+ net.minecraft.server.players.ServerOpList
- net.minecraft.server.players.ServerOpListEntry
+ net.minecraft.server.players.StoredUserEntry
- net.minecraft.server.players.StoredUserList
+ net.minecraft.server.players.UserBanList
- net.minecraft.server.players.UserBanListEntry
+ net.minecraft.server.players.UserWhiteList
- net.minecraft.server.players.UserWhiteListEntry
- net.minecraft.server.rcon.NetworkDataOutputStream
+ net.minecraft.server.rcon.package-info
+ net.minecraft.server.rcon.PktUtils
- net.minecraft.server.rcon.RconConsoleSource
- net.minecraft.server.rcon.thread.GenericThread
+ net.minecraft.server.rcon.thread.package-info
+ net.minecraft.server.rcon.thread.QueryThreadGs4
- net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
+ net.minecraft.server.rcon.thread.RconClient
- net.minecraft.server.rcon.thread.RconThread
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerResources
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
- net.minecraft.sounds.Music
+ net.minecraft.sounds.Musics
+ net.minecraft.sounds.package-info
- net.minecraft.sounds.SoundEvent
+ net.minecraft.sounds.SoundEvents
- net.minecraft.sounds.SoundSource
- net.minecraft.stats.package-info
- net.minecraft.stats.RecipeBook
+ net.minecraft.stats.RecipeBookSettings
- net.minecraft.stats.RecipeBookSettings$TypeSettings
+ net.minecraft.stats.ServerRecipeBook
- net.minecraft.stats.ServerStatsCounter
+ net.minecraft.stats.Stat
- net.minecraft.stats.StatFormatter
- net.minecraft.stats.Stats
+ net.minecraft.stats.StatsCounter
+ net.minecraft.stats.StatType
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$1
+ net.minecraft.tags.StaticTagHelper$Wrapper
- net.minecraft.tags.StaticTags
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$1
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$Named
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagCollection$1
+ net.minecraft.tags.TagContainer
- net.minecraft.tags.TagContainer$1
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagManager
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.Codecs$1
+ net.minecraft.util.Codecs$3
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkStatusFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix2
+ net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
- net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
+ net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.MapIdFix
+ net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
- net.minecraft.util.datafix.fixes.MissingDimensionFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRename
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.Util$5
- net.minecraft.Util$7
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Strider$StriderGroupData
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
+ net.minecraft.world.entity.npc.Villager
- net.minecraft.world.entity.npc.VillagerData
+ net.minecraft.world.entity.npc.VillagerDataHolder
- net.minecraft.world.entity.npc.VillagerProfession
+ net.minecraft.world.entity.npc.VillagerTrades
- net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.VillagerType$1
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$Pickup
- net.minecraft.world.entity.projectile.AbstractHurtingProjectile
+ net.minecraft.world.entity.projectile.Arrow
- net.minecraft.world.entity.projectile.DragonFireball
+ net.minecraft.world.entity.projectile.EvokerFangs
- net.minecraft.world.entity.projectile.EyeOfEnder
+ net.minecraft.world.entity.projectile.Fireball
- net.minecraft.world.entity.projectile.FireworkRocketEntity
+ net.minecraft.world.entity.projectile.FishingHook
- net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$FishHookState
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.projectile.ItemSupplier
- net.minecraft.world.entity.projectile.LargeFireball
+ net.minecraft.world.entity.projectile.LlamaSpit
- net.minecraft.world.entity.projectile.package-info
- net.minecraft.world.entity.projectile.Projectile
+ net.minecraft.world.entity.projectile.ProjectileUtil
- net.minecraft.world.entity.projectile.ShulkerBullet
+ net.minecraft.world.entity.projectile.SmallFireball
- net.minecraft.world.entity.projectile.Snowball
+ net.minecraft.world.entity.projectile.SpectralArrow
- net.minecraft.world.entity.projectile.ThrowableItemProjectile
+ net.minecraft.world.entity.projectile.ThrowableProjectile
- net.minecraft.world.entity.projectile.ThrownEgg
+ net.minecraft.world.entity.projectile.ThrownEnderpearl
- net.minecraft.world.entity.projectile.ThrownExperienceBottle
+ net.minecraft.world.entity.projectile.ThrownPotion
- net.minecraft.world.entity.projectile.ThrownTrident
+ net.minecraft.world.entity.projectile.WitherSkull
+ net.minecraft.world.entity.raid.package-info
+ net.minecraft.world.entity.raid.Raid
- net.minecraft.world.entity.raid.Raid$1
- net.minecraft.world.entity.raid.Raid$RaiderType
+ net.minecraft.world.entity.raid.Raid$RaidStatus
+ net.minecraft.world.entity.raid.Raider
- net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
+ net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- net.minecraft.world.entity.raid.Raider$RaiderCelebration
+ net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
- net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.schedule.Activity
+ net.minecraft.world.entity.schedule.Keyframe
- net.minecraft.world.entity.schedule.package-info
- net.minecraft.world.entity.schedule.Schedule
+ net.minecraft.world.entity.schedule.ScheduleBuilder
- net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
+ net.minecraft.world.entity.schedule.Timeline
+ net.minecraft.world.entity.vehicle.AbstractMinecart
- net.minecraft.world.entity.vehicle.AbstractMinecart$1
+ net.minecraft.world.entity.vehicle.AbstractMinecart$Type
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$1
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.item.AirItem
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.DirectionalPlaceContext$1
+ net.minecraft.world.item.UseOnContext
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.biome.BadlandsPlateauBiome
+ net.minecraft.world.level.biome.BambooJungleHillsBiome
+ net.minecraft.world.level.biome.BeachBiome
+ net.minecraft.world.level.biome.BiomeDefaultFeatures
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
- net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.BirchForestHillsBiome
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.ColdOceanBiome
+ net.minecraft.world.level.biome.DarkForestBiome
+ net.minecraft.world.level.biome.DeepColdOceanBiome
+ net.minecraft.world.level.biome.DeepLukeWarmOceanBiome
+ net.minecraft.world.level.biome.DeepWarmOceanBiome
+ net.minecraft.world.level.biome.DesertHillsBiome
+ net.minecraft.world.level.biome.EndBarrensBiome
+ net.minecraft.world.level.biome.EndMidlandsBiome
+ net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.ForestFlowerBiome
+ net.minecraft.world.level.biome.FrozenRiverBiome
- net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
+ net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ net.minecraft.world.level.biome.GiantTreeTaigaHillsBiome
+ net.minecraft.world.level.biome.IceSpikesBiome
+ net.minecraft.world.level.biome.JungleEdgeBiome
+ net.minecraft.world.level.biome.LukeWarmOceanBiome
+ net.minecraft.world.level.biome.ModifiedGravellyMountainsBiome
+ net.minecraft.world.level.biome.ModifiedJungleEdgeBiome
+ net.minecraft.world.level.biome.MountainBiome
+ net.minecraft.world.level.biome.MushroomFieldsBiome
+ net.minecraft.world.level.biome.OceanBiome
+ net.minecraft.world.level.biome.PlainsBiome
+ net.minecraft.world.level.biome.SavannaBiome
+ net.minecraft.world.level.biome.ShatteredSavannaBiome
+ net.minecraft.world.level.biome.SmallEndIslandsBiome
+ net.minecraft.world.level.biome.SnowyMountainsBiome
+ net.minecraft.world.level.biome.SnowyTaigaHillsBiome
+ net.minecraft.world.level.biome.SnowyTundraBiome
+ net.minecraft.world.level.biome.StoneShoreBiome
+ net.minecraft.world.level.biome.SwampBiome
+ net.minecraft.world.level.biome.TaigaBiome
+ net.minecraft.world.level.biome.TaigaMountainsBiome
+ net.minecraft.world.level.biome.TallBirchHillsBiome
+ net.minecraft.world.level.biome.WarmOceanBiome
+ net.minecraft.world.level.biome.WoodedBadlandsBiome
+ net.minecraft.world.level.biome.WoodedMountainBiome
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$RuntimePiece
+ net.minecraft.world.level.block.NetherPortalBlock$PortalShape
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
- net.minecraft.world.level.block.PumpkinBlock
+ net.minecraft.world.level.block.RailBlock
- net.minecraft.world.level.block.RailBlock$1
+ net.minecraft.world.level.block.RailState
- net.minecraft.world.level.block.RailState$1
- net.minecraft.world.level.block.RedstoneLampBlock
+ net.minecraft.world.level.block.RedStoneOreBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock
- net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
+ net.minecraft.world.level.block.RedstoneWallTorchBlock
- net.minecraft.world.level.block.RedStoneWireBlock
+ net.minecraft.world.level.block.RedStoneWireBlock$1
- net.minecraft.world.level.block.RenderShape
+ net.minecraft.world.level.block.RepeaterBlock
- net.minecraft.world.level.block.RespawnAnchorBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.Seagrass
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
+ net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$1
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrass
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVines
- net.minecraft.world.level.block.TwistingVinesPlant
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVines
- net.minecraft.world.level.block.WeepingVinesPlant
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$1
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkBiomeContainer
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.FeatureAccess
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.OldDataLayer
+ net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.ProtoTickList
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.OldChunkStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.DefaultExplosionDamageCalculator
- net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.LevelStem
- net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Decoratable
+ net.minecraft.world.level.levelgen.feature.BastionHoglinStablePools
+ net.minecraft.world.level.levelgen.feature.BastionPieces
+ net.minecraft.world.level.levelgen.feature.BastionSharedPools
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MultiJigsawConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSpheroidConfiguration$Builder
+ net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.StrongholdConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.StructureFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$Factory
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.JigsawFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PlainVillagePools
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaVillagePools
+ net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.ChancePassthroughDecorator
+ net.minecraft.world.level.levelgen.placement.ChorusPlantPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.CountBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.CountDecorator
+ net.minecraft.world.level.levelgen.placement.CountHeighmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.CountHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.CountTopSolidDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
+ net.minecraft.world.level.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecorator
- net.minecraft.world.level.levelgen.placement.DecorationContext
+ net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
- net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.FrequencyChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.HeightmapDecorator
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.ChanceRangeDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
+ net.minecraft.world.level.levelgen.placement.nether.FireDecorator
- net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
+ net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.NoiseHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
- net.minecraft.world.level.levelgen.placement.RangeDecorator
+ net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
- net.minecraft.world.level.levelgen.placement.Spread32Decorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalInfo
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +9M -2M
```
```
net.minecraft.Util$3 +3M -2M | +2P
```
```
XXX.minecraft.client.Option +6M -1M | +1P -1P
```
```
XXX.gui.screens.CreateBuffetWorldScreen +4M -3M | +1P
```
```
XXX.gui.screens.CreateBuffetWorldScreen$BiomeList +2M -2M
```
```
XXX.gui.screens.CreateFlatWorldScreen +1M -1M | +1P -1P
```
```
XXX.gui.screens.ShareToLanScreen +1M | +2P
```
```
XXX.screens.inventory.BookEditScreen +1M -1M | +6P
```
```
XXX.screens.inventory.BookViewScreen -1M | +1P
```
```
XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode +2M -2M
```
```
XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry -2M
```
```
XXX.screens.worldselection.EditGameRulesScreen$RuleEntry +1M -1M
```
```
XXX.screens.worldselection.WorldGenSettingsComponent +4M -2M | +1P -1P
```
```
XXX.client.multiplayer.ClientPacketListener +1M -1M
```
```
XXX.client.server.IntegratedServer +1M
```
```
XXX.minecraft.core.RegistryAccess$RegistryHolder +14M -4M | +2P -2P
```
```
XXX.minecraft.core.SectionPos +7M
```
```
XXX.network.chat.CommonComponents +1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P -1P
```
```
XXX.protocol.game.ClientboundBlockUpdatePacket +1M
```
```
XXX.protocol.game.ClientboundLevelChunkPacket +1M -1M | +1P -1P
```
```
XXX.ai.behavior.AcquirePoi +5M -4M | +1P
```
```
XXX.ai.memory.MemoryModuleType +2P
```
```
XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal +1M -1M
```
```
XXX.monster.piglin.Piglin -1M | -2P
```
```
XXX.world.item.BoneMealItem +1M -1M
```
```
XXX.world.item.EndCrystalItem +1M -1M
```
```
XXX.world.item.FireChargeItem +1M -1M
```
```
XXX.world.item.FlintAndSteelItem +3M -3M
```
```
XXX.world.item.GameMasterBlockItem +1M -1M
```
```
XXX.world.item.HoeItem +2M -2M
```
```
XXX.world.item.LeadItem +1M -1M
```
```
XXX.world.item.MapItem +2M -2M
```
```
XXX.world.item.MinecartItem +1M -1M
```
```
XXX.world.item.StandingAndWallBlockItem +1M -1M
```
```
XXX.world.level.BlockGetter +3M
```
```
XXX.level.biome.MultiNoiseBiomeSource +6M -3M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +1M -1M
```
```
XXX.level.block.BambooBlock +1M -1M
```
```
XXX.level.block.BannerBlock +1M -1M
```
```
XXX.level.block.BaseCoralWallFanBlock +1M -1M
```
```
XXX.level.block.BaseFireBlock +4M -3M
```
```
XXX.level.block.BaseRailBlock +1M -1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +1M -1M
```
```
XXX.level.block.BellBlock +1M -1M
```
```
XXX.level.block.CarvedPumpkinBlock +1M -1M
```
```
XXX.level.block.ChainBlock +1M -1M
```
```
XXX.level.block.ChorusPlantBlock +1M -1M
```
```
XXX.level.block.ConduitBlock +1M -1M
```
```
XXX.level.block.DiodeBlock +1M -1M
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.EndRodBlock +1M -1M
```
```
XXX.level.block.EnderChestBlock +1M -1M
```
```
XXX.level.block.FaceAttachedHorizontalDirectionalBlock +1M -1M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.GrowingPlantBodyBlock +1M -1M
```
```
XXX.level.block.HugeMushroomBlock +1M -1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.KelpBlock +1M -1M
```
```
XXX.level.block.LadderBlock +1M -1M
```
```
XXX.level.block.Lantern +1M -1M
```
```
XXX.level.block.LecternBlock +1M -1M
```
```
XXX.level.block.NetherPortalBlock -3M
```
```
XXX.block.piston.PistonBaseBlock +1M -1M
```
```
XXX.block.state.BlockBehaviour +1M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M -1M
```
```
XXX.state.pattern.BlockPattern$BlockPatternMatch -1M
```
```
XXX.level.levelgen.GenerationStep$Decoration +1M -5M | -3P
```
```
XXX.levelgen.carver.WorldCarver +1M -2M
```
```
XXX.levelgen.feature.BastionFeature +1M -2M
```
```
XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart +2M -2M
```
```
XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart +2M -2M
```
```
XXX.levelgen.feature.PillagerOutpostFeature +1M -2M
```
```
XXX.levelgen.feature.SeagrassFeature +1M -1M
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +2M -2M
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +6M -6M | +2P -4P
```
```
XXX.feature.configurations.DecoratedFeatureConfiguration +2M -2M | +1P -1P
```
```
XXX.feature.configurations.DeltaFeatureConfiguration +8M -5M | +2P -3P
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart +2M -2M
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +2M -2M
```
```
XXX.levelgen.structure.PoolElementStructurePiece +2M -2M
```
```
XXX.levelgen.structure.StructureStart$1 +2M -2M
```
```
XXX.structure.templatesystem.StructureProcessorType +3P -1P
```
```
XXX.levelgen.surfacebuilders.SurfaceBuilder +1M -2M | -3P
```
```
XXX.level.storage.McRegionUpgrader +2M -2M
```

</details>























































































































































<details>
<summary>
net.minecraft.Util
</summary>

```diff
- boolean executeInSequence(BooleanSupplier[])
- boolean runWithRetries(int,String,BooleanSupplier[])
- BooleanSupplier createDeleter(Path)
- BooleanSupplier createFileCreatedCheck(Path)
- BooleanSupplier createFileDeletedCheck(Path)
- BooleanSupplier createRenamer(Path,Path)
- String lambda$sanitizeName$7(CharPredicate,int)
+ String lambda$sanitizeResourceName$7(int)
- String sanitizeName(String,CharPredicate)
+ String sanitizeResourceName(String)
- void safeReplaceFile(Path,Path,Path)
```

</details>
<details>
<summary>
net.minecraft.Util$3
</summary>

```diff
- boolean getAsBoolean()
- String toString()
- void <init>(Path,Path)
+ void <init>(String)
+ void run()
```

</details>



























































































<details>
<summary>
net.minecraft.client.Option
</summary>

```diff
- Component genericValueLabel(Component)
- Component genericValueLabel(int)
- Component getCaption()
- Component percentAddValueLabel(int)
- Component percentValueLabel(double)
- Component pixelValueLabel(int)
+ MutableComponent createCaption()
```

</details>









































































<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen
</summary>

```diff
+ Biome access$102(CreateBuffetWorldScreen,Biome)
- Biome access$202(CreateBuffetWorldScreen,Biome)
+ void <init>(Screen,Consumer,Biome)
- void <init>(Screen,RegistryAccess,Consumer,Biome)
+ void access$300(CreateBuffetWorldScreen)
- void access$400(CreateBuffetWorldScreen)
- WritableRegistry access$100(CreateBuffetWorldScreen)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
</summary>

```diff
+ String lambda$new$0(Biome)
- String lambda$new$0(Map$Entry)
+ void lambda$new$1(Biome)
- void lambda$new$1(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen
</summary>

```diff
- void <init>(CreateWorldScreen,Consumer,FlatLevelGeneratorSettings)
+ void <init>(Screen,Consumer,FlatLevelGeneratorSettings)
```

</details>

















<details>
<summary>
net.minecraft.client.gui.screens.ShareToLanScreen
</summary>

```diff
- void <clinit>()
```

</details>
























<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookEditScreen
</summary>

```diff
+ int strWidth(String)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookViewScreen
</summary>

```diff
+ int strWidth(String)
```

</details>













































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$SelectedGameMode
</summary>

```diff
+ GameType access$700(CreateWorldScreen$SelectedGameMode)
- GameType access$800(CreateWorldScreen$SelectedGameMode)
+ String access$200(CreateWorldScreen$SelectedGameMode)
- String access$300(CreateWorldScreen$SelectedGameMode)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
</summary>

```diff
+ MutableComponent access$500(EditGameRulesScreen$BooleanRuleEntry,Component,boolean)
+ MutableComponent createFullMessage(Component,boolean)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
</summary>

```diff
- List access$1000(EditGameRulesScreen$RuleEntry)
+ List access$1100(EditGameRulesScreen$RuleEntry)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
</summary>

```diff
- OptionalLong parseSeed()
- String toString(OptionalLong)
+ void <init>()
- void <init>(RegistryAccess$RegistryHolder,WorldGenSettings,Optional,OptionalLong)
+ void <init>(RegistryAccess$RegistryHolder,WorldGenSettings)
- void setRegistryHolder(RegistryAccess$RegistryHolder)
```

</details>












































































<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
+ void handleChunkBlocksUpdate(ClientboundChunkBlocksUpdatePacket)
- void handleChunkBlocksUpdate(ClientboundSectionBlocksUpdatePacket)
```

</details>























































































































































































































































































































































<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
- int getRateLimitPacketsPerSecond()
```

</details>





















































































<details>
<summary>
net.minecraft.core.RegistryAccess$RegistryHolder
</summary>

```diff
- boolean lambda$null$3(Map$Entry)
- Codec captureMap(UnboundedMapCodec)
- Codec lambda$null$1(ResourceKey,MapCodec)
- Codec makeDirectCodec()
- DataResult getCodec(ResourceKey)
- DataResult lambda$getCodec$5(RegistryAccess$RegistryData)
- DataResult lambda$getCodec$6(ResourceKey)
- DataResult lambda$makeDirectCodec$0(MappedRegistry)
- DataResult lambda$makeDirectCodec$2(ResourceKey)
- Map access$000(RegistryAccess$RegistryHolder)
- Map lambda$captureMap$4(RegistryAccess$RegistryHolder)
- MappedRegistry createRegistry(ResourceKey)
+ MappedRegistry lambda$static$0(RegistryAccess$RegistryHolder)
+ Registry dimensionTypes()
- void <init>(Map)
+ void <init>(MappedRegistry)
+ void registerDimension(ResourceKey,DimensionType)
- WritableRegistry lambda$registry$7(MappedRegistry)
```

</details>
<details>
<summary>
net.minecraft.core.SectionPos
</summary>

```diff
- BlockPos relativeToBlockPos(short)
- int relativeToBlockX(short)
- int relativeToBlockY(short)
- int relativeToBlockZ(short)
- int sectionRelativeX(short)
- int sectionRelativeY(short)
- int sectionRelativeZ(short)
```

</details>






























<details>
<summary>
net.minecraft.network.chat.CommonComponents
</summary>

```diff
- MutableComponent optionStatus(Component,boolean)
```

</details>























<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
</summary>

```diff
- void <init>(BlockPos,BlockState)
```

</details>












<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
</summary>

```diff
+ ChunkBiomeContainer getBiomes()
- int[] getBiomes()
```

</details>

















































































































































<details>
<summary>
net.minecraft.world.entity.ai.behavior.AcquirePoi
</summary>

```diff
+ AcquirePoi$JitteredLinearRetry lambda$start$4(PathfinderMob,long,long)
- AcquirePoi$JitteredLinearRetry lambda$start$5(PathfinderMob,long,long)
- void <init>(PoiType,MemoryModuleType,boolean,Optional)
+ void <init>(PoiType,MemoryModuleType,boolean)
- void <init>(PoiType,MemoryModuleType,MemoryModuleType,boolean,Optional)
+ void <init>(PoiType,MemoryModuleType,MemoryModuleType,boolean)
- void lambda$null$3(ServerLevel,PathfinderMob,Byte)
+ void lambda$start$3(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
- void lambda$start$4(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
```

</details>





























































































































































































































<details>
<summary>
net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
</summary>

```diff
- void <init>(EnderMan,Predicate)
+ void <init>(EnderMan)
```

</details>
















































<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
+ void sendDebugPackets()
```

</details>




<details>
<summary>
net.minecraft.world.item.BoneMealItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>

















<details>
<summary>
net.minecraft.world.item.EndCrystalItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>

<details>
<summary>
net.minecraft.world.item.FireChargeItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>


<details>
<summary>
net.minecraft.world.item.FlintAndSteelItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ void lambda$useOn$0(UseOnContext,Player)
- void lambda$useOn$0(UseOnContext,Player)
+ void lambda$useOn$1(UseOnContext,Player)
- void lambda$useOn$1(UseOnContext,Player)
```

</details>
<details>
<summary>
net.minecraft.world.item.GameMasterBlockItem
</summary>

```diff
+ BlockState getPlacementState(BlockPlaceContext)
- BlockState getPlacementState(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoeItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ void lambda$useOn$0(UseOnContext,Player)
- void lambda$useOn$0(UseOnContext,Player)
```

</details>







<details>
<summary>
net.minecraft.world.item.LeadItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ ItemStack lockMap(Level,ItemStack)
- void lockMap(Level,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.MinecartItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>










<details>
<summary>
net.minecraft.world.item.StandingAndWallBlockItem
</summary>

```diff
+ BlockState getPlacementState(BlockPlaceContext)
- BlockState getPlacementState(BlockPlaceContext)
```

</details>


























































<details>
<summary>
net.minecraft.world.level.BlockGetter
</summary>

```diff
- double getBlockFloorHeight(BlockPos)
- double getBlockFloorHeight(VoxelShape,Supplier)
- VoxelShape lambda$getBlockFloorHeight$2(BlockPos)
```

</details>


















<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
- Biome lambda$defaultNether$10()
- Biome lambda$defaultNether$11()
- Biome lambda$defaultNether$12()
- Biome lambda$defaultNether$13()
- Biome lambda$defaultNether$9()
+ Float lambda$getNoiseBiome$11(Biome$ClimateParameters,Pair)
- Float lambda$getNoiseBiome$14(Biome$ClimateParameters,Pair)
+ Pair lambda$null$9(Biome,Biome$ClimateParameters)
+ Stream lambda$defaultNether$10(Biome)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.BaseCoralWallFanBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
- boolean canBePlacedAt(Level,BlockPos,Direction)
+ boolean canBePlacedAt(LevelAccessor,BlockPos)
- boolean inPortalDimension(Level)
- boolean isPortal(Level,BlockPos,Direction)
+ boolean isPortal(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.CarvedPumpkinBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChainBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.ConduitBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.DiodeBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBodyBlock
</summary>

```diff
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
- boolean canBeReplaced(BlockState,BlockPlaceContext)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.HugeMushroomBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LadderBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Lantern
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.NetherPortalBlock
</summary>

```diff
+ BlockPattern$BlockPatternMatch getPortalShape(LevelAccessor,BlockPos)
+ boolean trySpawnPortal(LevelAccessor,BlockPos)
+ NetherPortalBlock$PortalShape isPortal(LevelAccessor,BlockPos)
```

</details>
















<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
- boolean canBeReplaced(BlockState,BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
+ boolean canBeReplaced(BlockPlaceContext)
- boolean canBeReplaced(BlockPlaceContext)
- boolean isFaceSturdy(BlockGetter,BlockPos,Direction,SupportType)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
</summary>

```diff
+ BlockPattern$PortalInfo getPortalOutput(Direction,BlockPos,double,Vec3,double)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Decoration
</summary>

```diff
+ GenerationStep$Decoration byName(String)
+ GenerationStep$Decoration lambda$static$0(GenerationStep$Decoration)
+ String getName()
+ String getSerializedName()
+ void <init>(String,int,String)
- void <init>(String,int)
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
+ CarverConfiguration lambda$new$1(ConfiguredWorldCarver)
- ConfiguredWorldCarver configured(CarverConfiguration)
+ ConfiguredWorldCarver lambda$new$0(CarverConfiguration)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,MultiJigsawConfiguration)
+ StructureFeature$StructureStartFactory getStartFactory()
```

</details>















<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
+ StructureFeature$StructureStartFactory getStartFactory()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SeagrassFeature
</summary>

```diff
- boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,ProbabilityFeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,SeagrassFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ Integer lambda$null$0(ColumnFeatureConfiguration)
+ Integer lambda$null$1(ColumnFeatureConfiguration)
+ Integer lambda$null$2(ColumnFeatureConfiguration)
+ Integer lambda$null$3(ColumnFeatureConfiguration)
- UniformInt height()
- UniformInt lambda$null$0(ColumnFeatureConfiguration)
- UniformInt lambda$null$1(ColumnFeatureConfiguration)
- UniformInt reach()
+ void <init>(int,int,int,int)
- void <init>(UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
</summary>

```diff
+ ConfiguredFeature lambda$null$0(DecoratedFeatureConfiguration)
- Supplier lambda$null$0(DecoratedFeatureConfiguration)
+ void <init>(ConfiguredFeature,ConfiguredDecorator)
- void <init>(Supplier,ConfiguredDecorator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ App lambda$static$5(RecordCodecBuilder$Instance)
- BlockState contents()
- BlockState rim()
+ Integer lambda$null$2(DeltaFeatureConfiguration)
+ Integer lambda$null$3(DeltaFeatureConfiguration)
+ Integer lambda$null$4(DeltaFeatureConfiguration)
- UniformInt lambda$null$2(DeltaFeatureConfiguration)
- UniformInt lambda$null$3(DeltaFeatureConfiguration)
- UniformInt rimSize()
- UniformInt size()
+ void <init>(BlockState,BlockState,int,int,int)
- void <init>(BlockState,BlockState,UniformInt,UniformInt)
```

</details>








































<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>













<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
</summary>

```diff
+ void <init>(StructureManager,CompoundTag,StructurePieceType)
- void <init>(StructureManager,CompoundTag)
- void <init>(StructureManager,StructurePoolElement,BlockPos,int,Rotation,BoundingBox)
+ void <init>(StructurePieceType,StructureManager,StructurePoolElement,BlockPos,int,Rotation,BoundingBox)
```

</details>
















<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart$1
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration)
```

</details>































<details>
<summary>
net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
</summary>

```diff
- ConfiguredSurfaceBuilder configured(SurfaceBuilderConfiguration)
+ ConfiguredSurfaceBuilder lambda$new$0(SurfaceBuilderConfiguration)
+ SurfaceBuilderConfiguration lambda$new$1(ConfiguredSurfaceBuilder)
```

</details>





































































<details>
<summary>
net.minecraft.world.level.storage.McRegionUpgrader
</summary>

```diff
+ void convertRegion(File,File,BiomeSource,int,int,ProgressListener)
- void convertRegion(RegistryAccess$RegistryHolder,File,File,BiomeSource,int,int,ProgressListener)
+ void convertRegions(File,Iterable,BiomeSource,int,int,ProgressListener)
- void convertRegions(RegistryAccess$RegistryHolder,File,Iterable,BiomeSource,int,int,ProgressListener)
```

</details>
</details>