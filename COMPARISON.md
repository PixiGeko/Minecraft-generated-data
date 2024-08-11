## Comparison with [20w48a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w48a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">20w48a</th><th>20w49a</th></tr><tr><td>World version</td><td><code>2683</code></td><td><code>2685</code></td></tr><tr><td>Protocol version</td><td><code>1073741831</code></td><td><code>1073741832</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ game_event.txt
+ position_source_type.txt
```

</details>


<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>
<details>
<summary>
block_entity_type.txt
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>





<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>










<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:dust_color_transition
+ minecraft:vibration
```

</details>








<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.sculk_sensor.break
+ minecraft:block.sculk_sensor.clicking
+ minecraft:block.sculk_sensor.clicking_stop
+ minecraft:block.sculk_sensor.fall
+ minecraft:block.sculk_sensor.hit
+ minecraft:block.sculk_sensor.place
+ minecraft:block.sculk_sensor.step
```

</details>









<details>
<summary>
worldgen/feature.txt
</summary>

```diff
+ minecraft:dripstone_cluster
+ minecraft:large_dripstone
+ minecraft:small_dripstone
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/game_event.json
+ universal_tags/position_source_type.json
```

</details>

<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>






<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>





<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>










<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:dust_color_transition
+ minecraft:vibration
```

</details>








<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.sculk_sensor.break
+ minecraft:block.sculk_sensor.clicking
+ minecraft:block.sculk_sensor.clicking_stop
+ minecraft:block.sculk_sensor.fall
+ minecraft:block.sculk_sensor.hit
+ minecraft:block.sculk_sensor.place
+ minecraft:block.sculk_sensor.step
```

</details>









<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
+ minecraft:dripstone_cluster
+ minecraft:large_dripstone
+ minecraft:small_dripstone
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ biome.minecraft.dripstone_caves: Dripstone caves
+ block.minecraft.sculk_sensor: Sculk Sensor
+ death.attack.fallingStalactite: %1$s was skewered by a falling stalactite
+ death.attack.fallingStalactite.player: %1$s was skewered by a falling stalactite whilst fighting %2$s
+ subtitles.block.sculk_sensor.clicking_stop: Sculk Sensor stops clicking
+ subtitles.block.sculk_sensor.clicking: Sculk Sensor starts clicking
```

</details>
<details>
<summary>
Changes
</summary>

```
subtitles.block.pointed_dripstone.land: Pointed DripstonStalactite crashes down
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
generated
</summary>

```diff
+ reports/biomes/dripstone_caves.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/loot_tables/blocks/sculk_sensor.json
+ minecraft/tags/blocks/dripstone_replaceable_blocks.json
+ minecraft/tags/blocks/occludes_vibration_signals.json
+ minecraft/tags/game_events/ignore_vibrations_stepping_carefully.json
+ minecraft/tags/game_events/vibrations.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/sculk_sensor.json
+ minecraft/models/block/sculk_sensor_active.json
+ minecraft/models/block/sculk_sensor_inactive.json
+ minecraft/models/block/sculk_sensor.json
+ minecraft/models/item/sculk_sensor.json
+ minecraft/particles/dust_color_transition.json
+ minecraft/particles/vibration.json
+ minecraft/textures/block/calibrated_sculk_sensor_side.png
+ minecraft/textures/block/calibrated_sculk_sensor_top.png
+ minecraft/textures/block/sculk_sensor_bottom.png
+ minecraft/textures/block/sculk_sensor_side.png
+ minecraft/textures/block/sculk_sensor_tendril_active.png
+ minecraft/textures/block/sculk_sensor_tendril_active.png.mcmeta
+ minecraft/textures/block/sculk_sensor_tendril_inactive.png
+ minecraft/textures/block/sculk_sensor_tendril_inactive.png.mcmeta
+ minecraft/textures/block/sculk_sensor_top.png
+ minecraft/textures/particle/vibration.png
+ minecraft/textures/particle/vibration.png.mcmeta
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
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.blocks.BlockStateArgument
+ net.minecraft.commands.arguments.blocks.BlockStateParser
- net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.coordinates.BlockPosArgument
- net.minecraft.commands.arguments.coordinates.ColumnPosArgument
+ net.minecraft.commands.arguments.coordinates.Coordinates
- net.minecraft.commands.arguments.coordinates.LocalCoordinates
+ net.minecraft.commands.arguments.coordinates.package-info
+ net.minecraft.commands.arguments.coordinates.RotationArgument
- net.minecraft.commands.arguments.coordinates.SwizzleArgument
+ net.minecraft.commands.arguments.coordinates.Vec2Argument
- net.minecraft.commands.arguments.coordinates.Vec3Argument
+ net.minecraft.commands.arguments.coordinates.WorldCoordinate
- net.minecraft.commands.arguments.coordinates.WorldCoordinates
- net.minecraft.commands.arguments.item.FunctionArgument
+ net.minecraft.commands.arguments.item.FunctionArgument$1
- net.minecraft.commands.arguments.item.FunctionArgument$2
+ net.minecraft.commands.arguments.item.FunctionArgument$Result
- net.minecraft.commands.arguments.item.ItemArgument
+ net.minecraft.commands.arguments.item.ItemInput
- net.minecraft.commands.arguments.item.ItemParser
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$NbtPath
+ net.minecraft.commands.arguments.NbtPathArgument$Node
- net.minecraft.commands.arguments.NbtTagArgument
+ net.minecraft.commands.arguments.ObjectiveArgument
- net.minecraft.commands.arguments.ObjectiveCriteriaArgument
+ net.minecraft.commands.arguments.OperationArgument
- net.minecraft.commands.arguments.OperationArgument$Operation
+ net.minecraft.commands.arguments.OperationArgument$SimpleOperation
- net.minecraft.commands.arguments.package-info
- net.minecraft.commands.arguments.ParticleArgument
+ net.minecraft.commands.arguments.RangeArgument
- net.minecraft.commands.arguments.RangeArgument$Floats
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
+ net.minecraft.commands.arguments.selector.EntitySelectorParser
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
- net.minecraft.commands.arguments.selector.options.package-info
+ net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.SlotArgument
+ net.minecraft.commands.arguments.TeamArgument
- net.minecraft.commands.arguments.TimeArgument
+ net.minecraft.commands.arguments.UuidArgument
- net.minecraft.commands.exceptions.package-info
+ net.minecraft.commands.package-info
- net.minecraft.commands.synchronization.ArgumentSerializer
+ net.minecraft.commands.synchronization.ArgumentTypes
- net.minecraft.commands.synchronization.ArgumentTypes$1
+ net.minecraft.commands.synchronization.ArgumentTypes$Entry
+ net.minecraft.commands.synchronization.brigadier.BrigadierArgumentSerializers
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.FloatArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.LongArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.package-info
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
- net.minecraft.commands.synchronization.EmptyArgumentSerializer
+ net.minecraft.commands.synchronization.package-info
+ net.minecraft.commands.synchronization.SuggestionProviders
- net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
- net.minecraft.core.AxisCycle
+ net.minecraft.core.AxisCycle$1
- net.minecraft.core.AxisCycle$2
+ net.minecraft.core.AxisCycle$3
- net.minecraft.core.BlockMath
+ net.minecraft.core.BlockPos
- net.minecraft.core.BlockPos$1
+ net.minecraft.core.BlockPos$2
- net.minecraft.core.BlockPos$3
+ net.minecraft.core.BlockPos$4
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
- net.minecraft.core.MappedRegistry$RegistryEntry
+ net.minecraft.core.NonNullList
- net.minecraft.core.particles.DustColorTransitionOptions
- net.minecraft.core.particles.DustParticleOptionsBase
+ net.minecraft.core.particles.ItemParticleOption
- net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.Position
+ net.minecraft.core.PositionImpl
- net.minecraft.core.QuartPos
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
+ net.minecraft.data.BuiltinRegistries
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
+ net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$StructureConversionException
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BlockTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundChatPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$1
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerAckPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
- net.minecraft.network.protocol.game.ClientboundDisconnectPacket
+ net.minecraft.network.protocol.game.ClientboundEntityEventPacket
- net.minecraft.network.protocol.game.ClientboundExplodePacket
+ net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
- net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
+ net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundLevelEventPacket
- net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
- net.minecraft.network.protocol.game.ClientboundLoginPacket
+ net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
- net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
+ net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ClientboundOpenBookPacket
+ net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
- net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
+ net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
- net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$Event
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ net.minecraft.network.protocol.game.ClientboundRecipePacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket$State
+ net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
- net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundResourcePackPacket
- net.minecraft.network.protocol.game.ClientboundRespawnPacket
+ net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
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
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataPackCodec
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryLookupCodec
+ net.minecraft.resources.RegistryReadOps
- net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.resources.RegistryReadOps$ReadCache
- net.minecraft.resources.RegistryReadOps$ResourceAccess
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$1
- net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
+ net.minecraft.resources.RegistryWriteOps
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
+ net.minecraft.server.Bootstrap$1
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$1
- net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.commands.data.BlockDataAccessor
- net.minecraft.server.commands.data.BlockDataAccessor$1
+ net.minecraft.server.commands.data.DataAccessor
- net.minecraft.server.commands.data.DataCommands
+ net.minecraft.server.commands.data.DataCommands$DataManipulator
- net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
+ net.minecraft.server.commands.data.DataCommands$DataProvider
- net.minecraft.server.commands.data.EntityDataAccessor
+ net.minecraft.server.commands.data.EntityDataAccessor$1
- net.minecraft.server.commands.data.package-info
- net.minecraft.server.commands.data.StorageDataAccessor
+ net.minecraft.server.commands.data.StorageDataAccessor$1
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.SpreadPlayersCommand$1
+ net.minecraft.server.commands.SpreadPlayersCommand$Position
- net.minecraft.server.commands.StopCommand
+ net.minecraft.server.commands.StopSoundCommand
- net.minecraft.server.commands.SummonCommand
+ net.minecraft.server.commands.TagCommand
- net.minecraft.server.commands.TeamCommand
+ net.minecraft.server.commands.TeamMsgCommand
- net.minecraft.server.commands.TeleportCommand
+ net.minecraft.server.commands.TeleportCommand$LookAt
- net.minecraft.server.commands.TellRawCommand
+ net.minecraft.server.commands.TimeCommand
- net.minecraft.server.commands.TitleCommand
+ net.minecraft.server.commands.TriggerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.dedicated.Settings$1
+ net.minecraft.server.dedicated.Settings$MutableValue
+ net.minecraft.server.gui.MinecraftServerGui
- net.minecraft.server.gui.MinecraftServerGui$1
+ net.minecraft.server.gui.MinecraftServerGui$2
- net.minecraft.server.gui.package-info
- net.minecraft.server.gui.PlayerListComponent
+ net.minecraft.server.gui.StatsComponent
+ net.minecraft.server.level.BlockDestructionProgress
- net.minecraft.server.level.ChunkHolder
+ net.minecraft.server.level.ChunkHolder$1
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
- net.minecraft.server.level.ChunkHolder$FullChunkStatus
+ net.minecraft.server.level.ChunkHolder$LevelChangeListener
- net.minecraft.server.level.ChunkHolder$PlayerProvider
+ net.minecraft.server.level.ChunkMap
- net.minecraft.server.level.ChunkMap$1
+ net.minecraft.server.level.ChunkMap$2
- net.minecraft.server.level.ChunkMap$DistanceManager
+ net.minecraft.server.level.ChunkMap$TrackedEntity
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
+ net.minecraft.server.level.ChunkTracker
- net.minecraft.server.level.ColumnPos
+ net.minecraft.server.level.DemoMode
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.tags.GameEventTags
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
- net.minecraft.tags.SerializationTags
+ net.minecraft.tags.SetTag
- net.minecraft.tags.StaticTagHelper
+ net.minecraft.tags.StaticTagHelper$1
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.StaticTags
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$1
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$BuilderEntry
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$Named
+ net.minecraft.tags.Tag$OptionalElementEntry
- net.minecraft.tags.Tag$OptionalTagEntry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.TagCollection
+ net.minecraft.tags.TagCollection$1
- net.minecraft.tags.TagContainer
+ net.minecraft.tags.TagContainer$1
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagManager
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CryptException
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$1
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V501
- net.minecraft.util.datafix.schemas.V700
+ net.minecraft.util.datafix.schemas.V701
- net.minecraft.util.datafix.schemas.V702
+ net.minecraft.util.datafix.schemas.V703
- net.minecraft.util.datafix.schemas.V704
+ net.minecraft.util.datafix.schemas.V704$1
- net.minecraft.util.datafix.schemas.V705
+ net.minecraft.util.datafix.schemas.V705$1
- net.minecraft.util.datafix.schemas.V808
+ net.minecraft.util.datafix.schemas.V99
- net.minecraft.util.datafix.schemas.V99$1
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.ExtraCodecs
- net.minecraft.util.FastColor
+ net.minecraft.util.FastColor$ARGB32
- net.minecraft.util.FormattedCharSequence
+ net.minecraft.util.FormattedCharSink
- net.minecraft.util.FrameTimer
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HeapDumper
+ net.minecraft.util.HttpUtil
+ net.minecraft.util.LimitedCapacityList
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.Mth
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$1
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.ProgressListener
+ net.minecraft.util.RewindableStream
- net.minecraft.util.RewindableStream$1
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$1
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.StringDecomposer
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringRepresentable$1
- net.minecraft.util.StringRepresentable$2
+ net.minecraft.util.StringUtil
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.UniformFloat
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.world.BossEvent
+ net.minecraft.world.BossEvent$BossBarColor
- net.minecraft.world.BossEvent$BossBarOverlay
+ net.minecraft.world.Clearable
- net.minecraft.world.CompoundContainer
+ net.minecraft.world.Container
- net.minecraft.world.ContainerHelper
+ net.minecraft.world.ContainerListener
- net.minecraft.world.Containers
+ net.minecraft.world.damagesource.BadRespawnPointDamage
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.EntityDamageSource
+ net.minecraft.world.damagesource.IndirectEntityDamageSource
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsoptionMobEffect
- net.minecraft.world.effect.AttackDamageMobEffect
+ net.minecraft.world.effect.HealthBoostMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.AttributeMap
- net.minecraft.world.entity.ai.attributes.AttributeModifier
+ net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
+ net.minecraft.world.entity.ai.attributes.DefaultAttributes
+ net.minecraft.world.entity.ai.attributes.package-info
- net.minecraft.world.entity.ai.attributes.RangedAttribute
- net.minecraft.world.entity.ai.behavior.AcquirePoi
+ net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
- net.minecraft.world.entity.ai.behavior.AnimalMakeLove
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunIf
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.RunSometimes
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WeightedList
+ net.minecraft.world.entity.ai.behavior.WeightedList$1
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.DolphinLookControl
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.goal.AvoidEntityGoal
- net.minecraft.world.entity.ai.goal.BegGoal
+ net.minecraft.world.entity.ai.goal.BoatGoals
- net.minecraft.world.entity.ai.goal.BreakDoorGoal
+ net.minecraft.world.entity.ai.goal.BreathAirGoal
- net.minecraft.world.entity.ai.goal.BreedGoal
+ net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
- net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
+ net.minecraft.world.entity.ai.goal.DolphinJumpGoal
- net.minecraft.world.entity.ai.goal.DoorInteractGoal
+ net.minecraft.world.entity.ai.goal.EatBlockGoal
- net.minecraft.world.entity.ai.goal.FleeSunGoal
+ net.minecraft.world.entity.ai.goal.FloatGoal
- net.minecraft.world.entity.ai.goal.FollowBoatGoal
+ net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
- net.minecraft.world.entity.ai.goal.FollowMobGoal
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
- net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.PlayGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
- net.minecraft.world.entity.ai.goal.TakeFlowerGoal
- net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
+ net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
- net.minecraft.world.entity.ai.goal.target.package-info
- net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
+ net.minecraft.world.entity.ai.goal.target.TargetGoal
+ net.minecraft.world.entity.ai.goal.TemptGoal
- net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
+ net.minecraft.world.entity.ai.goal.TryFindWaterGoal
- net.minecraft.world.entity.ai.goal.UseItemGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
+ net.minecraft.world.entity.ai.goal.WrappedGoal
- net.minecraft.world.entity.ai.goal.ZombieAttackGoal
+ net.minecraft.world.entity.ai.gossip.GossipContainer
- net.minecraft.world.entity.ai.gossip.GossipContainer$1
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
+ net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.AirRandomPos
+ net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
+ net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
- net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.Bee
- net.minecraft.world.entity.animal.Bee$1
+ net.minecraft.world.entity.animal.Bee$BaseBeeGoal
- net.minecraft.world.entity.animal.Bee$BeeAttackGoal
+ net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
- net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
- net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
+ net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeLookControl
+ net.minecraft.world.entity.animal.Bee$BeePollinateGoal
- net.minecraft.world.entity.animal.Bee$BeeWanderGoal
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$1
- net.minecraft.world.entity.animal.Dolphin$DolphinMoveControl
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$1
+ net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
- net.minecraft.world.entity.animal.Fox$FaceplantGoal
+ net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
- net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
+ net.minecraft.world.entity.animal.Fox$FoxBreedGoal
- net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
+ net.minecraft.world.entity.animal.Fox$FoxFloatGoal
- net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
+ net.minecraft.world.entity.animal.Fox$FoxGroupData
- net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Fox$FoxLookControl
- net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
+ net.minecraft.world.entity.animal.Fox$FoxMoveControl
- net.minecraft.world.entity.animal.Fox$FoxPanicGoal
+ net.minecraft.world.entity.animal.Fox$FoxPounceGoal
- net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
+ net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
- net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
+ net.minecraft.world.entity.animal.Fox$SeekShelterGoal
- net.minecraft.world.entity.animal.Fox$SleepGoal
+ net.minecraft.world.entity.animal.Fox$StalkPreyGoal
- net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
- net.minecraft.world.entity.animal.horse.Llama$1
+ net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
- net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
+ net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
- net.minecraft.world.entity.animal.horse.Markings
+ net.minecraft.world.entity.animal.horse.Mule
- net.minecraft.world.entity.animal.horse.package-info
- net.minecraft.world.entity.animal.horse.SkeletonHorse
+ net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
- net.minecraft.world.entity.animal.horse.TraderLlama
+ net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.animal.horse.Variant
+ net.minecraft.world.entity.animal.horse.ZombieHorse
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.IronGolem$Crackiness
+ net.minecraft.world.entity.animal.MushroomCow
- net.minecraft.world.entity.animal.MushroomCow$MushroomType
+ net.minecraft.world.entity.animal.Ocelot
- net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.package-info
- net.minecraft.world.entity.animal.Panda
+ net.minecraft.world.entity.animal.Panda$Gene
- net.minecraft.world.entity.animal.Panda$PandaAttackGoal
+ net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
- net.minecraft.world.entity.animal.Panda$PandaBreedGoal
+ net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
- net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
+ net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
- net.minecraft.world.entity.animal.Panda$PandaMoveControl
+ net.minecraft.world.entity.animal.Panda$PandaPanicGoal
- net.minecraft.world.entity.animal.Panda$PandaRollGoal
+ net.minecraft.world.entity.animal.Panda$PandaSitGoal
- net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
+ net.minecraft.world.entity.animal.Parrot
- net.minecraft.world.entity.animal.Parrot$1
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$1
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$1
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$1
+ net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
- net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
- net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
+ net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
- net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTemptGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$1
+ net.minecraft.world.entity.EntityType$Builder
- net.minecraft.world.entity.EntityType$EntityFactory
+ net.minecraft.world.entity.EquipmentSlot
- net.minecraft.world.entity.EquipmentSlot$Type
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacements$Type
- net.minecraft.world.entity.TamableAnimal
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
+ net.minecraft.world.item.context.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext$1
+ net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.UseOnContext
- net.minecraft.world.item.crafting.AbstractCookingRecipe
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.FireworkRocketRecipe
+ net.minecraft.world.item.crafting.FireworkStarFadeRecipe
- net.minecraft.world.item.crafting.FireworkStarRecipe
+ net.minecraft.world.item.crafting.Ingredient
- net.minecraft.world.item.crafting.Ingredient$1
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
- net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.ProjectileWeaponItem$Type
- net.minecraft.world.item.Rarity
+ net.minecraft.world.item.RecordItem
- net.minecraft.world.item.SaddleItem
+ net.minecraft.world.item.ScaffoldingBlockItem
- net.minecraft.world.item.ServerItemCooldowns
+ net.minecraft.world.item.ShearsItem
- net.minecraft.world.item.ShieldItem
+ net.minecraft.world.item.ShovelItem
- net.minecraft.world.item.SignItem
+ net.minecraft.world.item.SimpleFoiledItem
- net.minecraft.world.item.SnowballItem
+ net.minecraft.world.item.SolidBucketItem
- net.minecraft.world.item.SpawnEggItem
+ net.minecraft.world.item.SpectralArrowItem
- net.minecraft.world.item.SplashPotionItem
+ net.minecraft.world.item.SpyglassItem
- net.minecraft.world.item.StandingAndWallBlockItem
+ net.minecraft.world.item.SuspiciousStewItem
- net.minecraft.world.item.SwordItem
+ net.minecraft.world.item.ThrowablePotionItem
- net.minecraft.world.item.Tier
+ net.minecraft.world.item.TieredItem
- net.minecraft.world.item.Tiers
+ net.minecraft.world.item.TippedArrowItem
- net.minecraft.world.item.TooltipFlag
+ net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BellBlockEntity
+ net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
+ net.minecraft.world.level.block.entity.BlockEntityType
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.SculkSensorBlock
- net.minecraft.world.level.block.SeagrassBlock
+ net.minecraft.world.level.block.SeaPickleBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock
- net.minecraft.world.level.block.ShulkerBoxBlock$1
+ net.minecraft.world.level.block.SignBlock
- net.minecraft.world.level.block.SimpleWaterloggedBlock
+ net.minecraft.world.level.block.SkullBlock
- net.minecraft.world.level.block.SkullBlock$Type
+ net.minecraft.world.level.block.SkullBlock$Types
- net.minecraft.world.level.block.SlabBlock
+ net.minecraft.world.level.block.SlabBlock$1
- net.minecraft.world.level.block.SlimeBlock
+ net.minecraft.world.level.block.SmithingTableBlock
- net.minecraft.world.level.block.SmokerBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
+ net.minecraft.world.level.block.SpreadingSnowyDirtBlock
- net.minecraft.world.level.block.StainedGlassBlock
+ net.minecraft.world.level.block.StainedGlassPaneBlock
- net.minecraft.world.level.block.StairBlock
+ net.minecraft.world.level.block.StairBlock$1
- net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StemGrownBlock
+ net.minecraft.world.level.block.StoneButtonBlock
- net.minecraft.world.level.block.StonecutterBlock
+ net.minecraft.world.level.block.StructureBlock
- net.minecraft.world.level.block.StructureBlock$1
+ net.minecraft.world.level.block.StructureVoidBlock
- net.minecraft.world.level.block.SugarCaneBlock
+ net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$1
+ net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SupportType$3
+ net.minecraft.world.level.block.SweetBerryBushBlock
- net.minecraft.world.level.block.TallFlowerBlock
+ net.minecraft.world.level.block.TallGrassBlock
- net.minecraft.world.level.block.TallSeagrassBlock
+ net.minecraft.world.level.block.TargetBlock
- net.minecraft.world.level.block.TintedGlassBlock
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
+ net.minecraft.world.level.block.TwistingVinesBlock
- net.minecraft.world.level.block.TwistingVinesPlantBlock
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
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
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
- net.minecraft.world.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
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
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ChunkTickList
- net.minecraft.world.level.ChunkTickList$1
+ net.minecraft.world.level.ChunkTickList$ScheduledTick
- net.minecraft.world.level.ClipBlockStateContext
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
+ net.minecraft.world.level.entity.ChunkEntities
- net.minecraft.world.level.entity.ChunkStatusUpdateListener
+ net.minecraft.world.level.entity.EntityAccess
- net.minecraft.world.level.entity.EntityInLevelCallback
+ net.minecraft.world.level.entity.EntityInLevelCallback$1
- net.minecraft.world.level.entity.EntityLookup
+ net.minecraft.world.level.entity.EntityPersistentStorage
- net.minecraft.world.level.entity.EntitySection
+ net.minecraft.world.level.entity.EntitySectionStorage
- net.minecraft.world.level.entity.EntityTickList
+ net.minecraft.world.level.entity.EntityTypeTest
- net.minecraft.world.level.entity.EntityTypeTest$1
+ net.minecraft.world.level.entity.LevelCallback
- net.minecraft.world.level.entity.LevelEntityGetter
+ net.minecraft.world.level.entity.LevelEntityGetterAdapter
- net.minecraft.world.level.entity.package-info
- net.minecraft.world.level.entity.PersistentEntitySectionManager
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$1
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager
+ net.minecraft.world.level.entity.TransientEntitySectionManager$1
- net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
+ net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.gameevent.BlockPositionSource$Type
- net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEventDispatcher$1
- net.minecraft.world.level.gameevent.GameEventListenerRegistrar
- net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.VibrationListener
- net.minecraft.world.level.gameevent.vibrations.VibrationPath
- net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.DripstoneUtils
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.placement.BaseHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceDecorator
- net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
- net.minecraft.world.level.levelgen.placement.CountDecorator
+ net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.DecorationContext
+ net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
- net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
+ net.minecraft.world.level.levelgen.placement.EdgeDecorator
- net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.FeatureDecorator
- net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.HeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.HeightMapWorldSurfaceDecorator
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
+ net.minecraft.world.level.levelgen.placement.nether.FireDecorator
- net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
+ net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
- net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.RangeDecorator
+ net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
- net.minecraft.world.level.levelgen.placement.Spread32Decorator
+ net.minecraft.world.level.levelgen.placement.SquareDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
+ net.minecraft.world.level.levelgen.placement.VeryBiasedRangeDecorator
- net.minecraft.world.level.levelgen.structure.BeardedStructureStart
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces
- net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureStart$1
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.package-info
+ net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.synth.SurfaceNoise
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
+ net.minecraft.world.level.lighting.FlatDataLayer
- net.minecraft.world.level.lighting.LayerLightEngine
+ net.minecraft.world.level.lighting.LayerLightEventListener
- net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ net.minecraft.world.level.lighting.LayerLightSectionStorage
- net.minecraft.world.level.lighting.LayerLightSectionStorage$1
+ net.minecraft.world.level.lighting.LevelLightEngine
- net.minecraft.world.level.lighting.LightEventListener
+ net.minecraft.world.level.lighting.package-info
+ net.minecraft.world.level.lighting.SkyLightEngine
- net.minecraft.world.level.lighting.SkyLightSectionStorage
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$1
- net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ net.minecraft.world.level.lighting.SpatialLongSet
- net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
- net.minecraft.world.level.material.EmptyFluid
+ net.minecraft.world.level.material.FlowingFluid
- net.minecraft.world.level.material.FlowingFluid$1
+ net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FogType
+ net.minecraft.world.level.material.LavaFluid
- net.minecraft.world.level.material.LavaFluid$Flowing
+ net.minecraft.world.level.material.LavaFluid$Source
- net.minecraft.world.level.material.Material
+ net.minecraft.world.level.material.Material$Builder
- net.minecraft.world.level.material.MaterialColor
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.newbiome.area.Area
+ net.minecraft.world.level.newbiome.area.AreaFactory
- net.minecraft.world.level.newbiome.area.LazyArea
+ net.minecraft.world.level.newbiome.area.package-info
- net.minecraft.world.level.newbiome.context.BigContext
+ net.minecraft.world.level.newbiome.context.Context
- net.minecraft.world.level.newbiome.context.LazyAreaContext
+ net.minecraft.world.level.newbiome.context.package-info
- net.minecraft.world.level.newbiome.layer.AddDeepOceanLayer
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer$CoolWarm
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer$HeatIce
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer$IntroduceSpecial
+ net.minecraft.world.level.newbiome.layer.AddIslandLayer
- net.minecraft.world.level.newbiome.layer.AddMushroomIslandLayer
+ net.minecraft.world.level.newbiome.layer.AddSnowLayer
- net.minecraft.world.level.newbiome.layer.BiomeEdgeLayer
+ net.minecraft.world.level.newbiome.layer.BiomeInitLayer
- net.minecraft.world.level.newbiome.layer.IslandLayer
+ net.minecraft.world.level.newbiome.layer.Layer
- net.minecraft.world.level.newbiome.layer.LayerBiomes
+ net.minecraft.world.level.newbiome.layer.Layers
- net.minecraft.world.level.newbiome.layer.Layers$Category
+ net.minecraft.world.level.newbiome.layer.OceanLayer
- net.minecraft.world.level.newbiome.layer.OceanMixerLayer
- net.minecraft.world.level.newbiome.layer.package-info
+ net.minecraft.world.level.newbiome.layer.RareBiomeLargeLayer
- net.minecraft.world.level.newbiome.layer.RareBiomeSpotLayer
+ net.minecraft.world.level.newbiome.layer.RegionHillsLayer
- net.minecraft.world.level.newbiome.layer.RemoveTooMuchOceanLayer
+ net.minecraft.world.level.newbiome.layer.RiverInitLayer
- net.minecraft.world.level.newbiome.layer.RiverLayer
+ net.minecraft.world.level.newbiome.layer.RiverMixerLayer
- net.minecraft.world.level.newbiome.layer.ShoreLayer
+ net.minecraft.world.level.newbiome.layer.SmoothLayer
+ net.minecraft.world.level.newbiome.layer.traits.AreaTransformer0
- net.minecraft.world.level.newbiome.layer.traits.AreaTransformer1
+ net.minecraft.world.level.newbiome.layer.traits.AreaTransformer2
- net.minecraft.world.level.newbiome.layer.traits.BishopTransformer
+ net.minecraft.world.level.newbiome.layer.traits.C0Transformer
- net.minecraft.world.level.newbiome.layer.traits.C1Transformer
+ net.minecraft.world.level.newbiome.layer.traits.CastleTransformer
- net.minecraft.world.level.newbiome.layer.traits.DimensionOffset0Transformer
+ net.minecraft.world.level.newbiome.layer.traits.DimensionOffset1Transformer
- net.minecraft.world.level.newbiome.layer.traits.DimensionTransformer
- net.minecraft.world.level.newbiome.layer.traits.package-info
+ net.minecraft.world.level.newbiome.layer.traits.PixelTransformer
- net.minecraft.world.level.newbiome.layer.ZoomLayer
+ net.minecraft.world.level.newbiome.layer.ZoomLayer$1
+ net.minecraft.world.level.package-info
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
- net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.TurtleNodeEvaluator
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.portal.package-info
+ net.minecraft.world.level.portal.PortalForcer
- net.minecraft.world.level.portal.PortalInfo
+ net.minecraft.world.level.portal.PortalShape
- net.minecraft.world.level.redstone.package-info
+ net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$1
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$1
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelResource
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.LevelVersion
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.Deserializers
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$1
- net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem$1
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootItem$1
- net.minecraft.world.level.storage.loot.entries.LootItem$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Serializer
- net.minecraft.world.level.storage.loot.entries.LootTableReference
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$1
- net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
- net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$1
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$1
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$1
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$1
- net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$1
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$1
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$1
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$DefaultSerializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
+ net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$1
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.IntRange$Serializer
- net.minecraft.world.level.storage.loot.ItemModifierManager
+ net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$1
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$1
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$1
+ net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.LootTable$Serializer
+ net.minecraft.world.level.storage.loot.LootTables
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.PredicateManager
+ net.minecraft.world.level.storage.loot.PredicateManager$1
- net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$1
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$1
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$1
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
+ net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$1
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$DefaultSerializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$1
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$1
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$DefaultSerializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$1
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$1
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$1
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$DefaultSerializer
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$1
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.Serializer
- net.minecraft.world.level.storage.loot.SerializerType
+ net.minecraft.world.level.storage.loot.ValidationContext
- net.minecraft.world.level.storage.McRegionUpgrader
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.threaded.package-info
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.timers.FunctionCallback
- net.minecraft.world.level.timers.FunctionCallback$Serializer
+ net.minecraft.world.level.timers.FunctionTagCallback
- net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
+ net.minecraft.world.level.timers.TimerCallback
- net.minecraft.world.level.timers.TimerCallback$Serializer
+ net.minecraft.world.level.timers.TimerCallbacks
- net.minecraft.world.level.timers.TimerQueue
+ net.minecraft.world.level.timers.TimerQueue$1
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
+ net.minecraft.world.ShulkerSharedHelper
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.Snooper
+ net.minecraft.world.Snooper$1
- net.minecraft.world.SnooperPopulator
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.core.particles.DustParticleOptions +3M -11M | +1P -4P
```
```
XXX.data.worldgen.Features +3P
```
```
XXX.worldgen.biome.VanillaBiomes +1M
```
```
XXX.minecraft.nbt.CompoundTag -2M | -1P
```
```
XXX.minecraft.nbt.StringTag -1M
```
```
XXX.server.level.ServerChunkCache -1M
```
```
XXX.server.level.ServerLevel +13M -9M
```
```
XXX.rcon.thread.GenericThread -1P
```
```
XXX.minecraft.sounds.SoundSource -2M | -1P
```
```
XXX.entity.item.FallingBlockEntity +2M -1M | +1P -1P
```
```
XXX.entity.monster.Phantom -1M
```
```
XXX.entity.monster.Shulker -1M
```
```
XXX.entity.projectile.AbstractArrow -1M
```
```
XXX.world.inventory.AbstractContainerMenu -2M
```
```
XXX.world.inventory.CraftingContainer -1M
```
```
XXX.world.inventory.HorseInventoryMenu -1M
```
```
XXX.world.level.GameRules -1M
```
```
XXX.world.level.LevelHeightAccessor +2M -2M | +2P -2P
```
```
XXX.world.level.NoiseColumn +1M -5M | +1P
```
```
XXX.level.biome.BiomeManager +2M | +1P
```
```
XXX.level.block.AbstractFurnaceBlock -1P
```
```
XXX.level.block.BasePressurePlateBlock +1M -1M
```
```
XXX.level.block.Block -2M
```
```
XXX.level.block.Blocks +2M | +1P
```
```
XXX.level.block.EntityBlock +1M
```
```
XXX.level.block.PointedDripstoneBlock +8M -3M
```
```
XXX.level.block.RedStoneWireBlock +2M -2M | +1P -1P
```
```
XXX.block.entity.StructureBlockEntity -1M
```
```
XXX.block.state.BlockBehaviour +1M
```
```
XXX.state.predicate.BlockStatePredicate -1M
```
```
XXX.state.properties.BlockStateProperties +1P
```
```
XXX.level.chunk.ImposterProtoChunk -1M
```
```
XXX.level.chunk.ProtoChunk +2M -3M
```
```
XXX.chunk.storage.OldChunkStorage +1M | +1P
```
```
XXX.level.levelgen.DebugLevelSource +1M -1M
```
```
XXX.level.levelgen.FlatLevelSource +1M -1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +1M -1M
```
```
XXX.levelgen.feature.Feature +3P
```
```
XXX.levelgen.feature.RuinedPortalFeature +1M -1M
```

</details>











































































































































<details>
<summary>
net.minecraft.core.particles.DustParticleOptions
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ float getB()
+ float getG()
+ float getR()
+ float getScale()
+ Float lambda$null$0(DustParticleOptions)
+ Float lambda$null$2(DustParticleOptions)
+ Float lambda$null$3(DustParticleOptions)
+ String writeToString()
- Vec3 lambda$null$0(DustParticleOptions)
+ void <init>(float,float,float,float)
- void <init>(Vec3,float)
+ void writeToNetwork(FriendlyByteBuf)
```

</details>















<details>
<summary>
net.minecraft.data.worldgen.biome.VanillaBiomes
</summary>

```diff
- Biome dripstoneCaves()
```

</details>
























<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
+ String handleEscape(String)
+ void stripEmptyChildren()
```

</details>















<details>
<summary>
net.minecraft.nbt.StringTag
</summary>

```diff
+ boolean isEmpty()
```

</details>


























































































<details>
<summary>
net.minecraft.server.level.ServerChunkCache
</summary>

```diff
+ boolean isEntityTickingChunk(Entity)
```

</details>

<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ boolean lambda$clearBlockEvents$18(BoundingBox,BlockEventData)
- boolean lambda$clearBlockEvents$19(BoundingBox,BlockEventData)
+ boolean lambda$findNearestBiome$13(Biome,Biome)
- boolean lambda$findNearestBiome$14(Biome,Biome)
- int getLogicalHeight()
+ String lambda$getTypeCount$20(Object2IntMap$Entry)
- String lambda$getTypeCount$21(Object2IntMap$Entry)
+ String lambda$getWatchdogStats$19(Entity)
- String lambda$getWatchdogStats$20(Entity)
- void gameEvent(Entity,GameEvent,BlockPos)
+ void lambda$makeObsidianPlatform$21(ServerLevel,BlockPos)
- void lambda$makeObsidianPlatform$23(ServerLevel,BlockPos)
+ void lambda$null$14(BlockPos)
- void lambda$null$15(BlockPos)
+ void lambda$null$16(BlockPos,PoiType)
- void lambda$null$17(BlockPos,PoiType)
+ void lambda$onBlockStateChange$15(BlockPos,PoiType)
- void lambda$onBlockStateChange$16(BlockPos,PoiType)
+ void lambda$onBlockStateChange$17(BlockPos,PoiType)
- void lambda$onBlockStateChange$18(BlockPos,PoiType)
- void lambda$sendVibrationParticle$13(BlockPos,ClientboundAddVibrationSignalPacket,ServerPlayer)
- void sendVibrationParticle(VibrationPath)
```

</details>






























































<details>
<summary>
net.minecraft.sounds.SoundSource
</summary>

```diff
+ Set getNames()
+ SoundSource byName(String)
```

</details>


































































































































<details>
<summary>
net.minecraft.world.entity.item.FallingBlockEntity
</summary>

```diff
- void lambda$causeFallDamage$0(DamageSource,float,Entity)
+ void setHurtsEntities(boolean)
- void setHurtsEntities(float,int)
```

</details>


























<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
+ Vec3 getMovementTarget()
```

</details>








<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
+ void setDefaultColor()
```

</details>


















































<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
+ boolean isInGround()
```

</details>





































<details>
<summary>
net.minecraft.world.inventory.AbstractContainerMenu
</summary>

```diff
+ Slot getSlotFor(Container,int)
+ void addItem(int,ItemStack)
```

</details>












<details>
<summary>
net.minecraft.world.inventory.CraftingContainer
</summary>

```diff
+ ItemStack getItem(int,int)
```

</details>









<details>
<summary>
net.minecraft.world.inventory.HorseInventoryMenu
</summary>

```diff
+ Container getContainer()
```

</details>












































































<details>
<summary>
net.minecraft.world.level.GameRules
</summary>

```diff
+ void <init>(GameRules,MinecraftServer)
```

</details>







<details>
<summary>
net.minecraft.world.level.LevelHeightAccessor
</summary>

```diff
+ int getHeight()
+ int getMinBuildHeight()
- int getMinSection()
- int getSectionsCount()
```

</details>






<details>
<summary>
net.minecraft.world.level.NoiseColumn
</summary>

```diff
+ BlockEntity getBlockEntity(BlockPos)
+ FluidState getFluidState(BlockPos)
+ int getMinSection()
+ int getSectionsCount()
+ void <init>(BlockState[])
- void <init>(int,BlockState[])
```

</details>













<details>
<summary>
net.minecraft.world.level.biome.BiomeManager
</summary>

```diff
- int access$000()
- void <clinit>()
```

</details>


























<details>
<summary>
net.minecraft.world.level.block.BasePressurePlateBlock
</summary>

```diff
- void checkPressed(Entity,Level,BlockPos,BlockState,int)
+ void checkPressed(Level,BlockPos,BlockState,int)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ void handleRain(BlockState,Level,BlockPos)
+ void prepareRender(BlockGetter,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
- boolean lambda$static$48(BlockState,BlockGetter,BlockPos)
- int lambda$static$47(BlockState)
```

</details>





































<details>
<summary>
net.minecraft.world.level.block.EntityBlock
</summary>

```diff
- GameEventListener getListener(Level,BlockEntity)
```

</details>




































<details>
<summary>
net.minecraft.world.level.block.PointedDripstoneBlock
</summary>

```diff
- BlockPos findRootBlock(Level,BlockPos,BlockState,int)
+ BlockPos findRootBlock(Level,BlockPos,BlockState)
- BlockPos findTip(BlockState,LevelAccessor,BlockPos,int)
+ BlockPos findTip(BlockState,LevelAccessor,BlockPos)
- BlockState getAirOrWater(BlockState)
+ boolean isUnderLiquidSource(Level,BlockPos)
- DamageSource getFallDamageSource()
- float getMaxHorizontalOffset()
- int getStalactiteSizeFromTip(ServerLevel,BlockPos,int)
- Predicate getHurtsEntitySelector()
- void spawnDripParticle(Level,BlockPos,BlockState,PointedDripstoneBlock$DripType)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.RedStoneWireBlock
</summary>

```diff
- void lambda$static$0(Vec3[])
+ void lambda$static$0(Vector3f[])
- void spawnParticlesAlongLine(Level,Random,BlockPos,Vec3,Direction,Direction,float,float)
+ void spawnParticlesAlongLine(Level,Random,BlockPos,Vector3f,Direction,Direction,float,float)
```

</details>













<details>
<summary>
net.minecraft.world.level.block.entity.StructureBlockEntity
</summary>

```diff
+ Component getDisplayName()
```

</details>













<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- float getMaxHorizontalOffset()
```

</details>











<details>
<summary>
net.minecraft.world.level.block.state.predicate.BlockStatePredicate
</summary>

```diff
+ BlockStatePredicate forDefinition(StateDefinition)
```

</details>












<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
+ LevelLightEngine getLightEngine()
```

</details>






<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
- int getHeight()
- int getMinBuildHeight()
+ int getMinSection()
+ int getSectionsCount()
+ LevelLightEngine getLightEngine()
```

</details>








<details>
<summary>
net.minecraft.world.level.chunk.storage.OldChunkStorage
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
+ BlockGetter getBaseColumn(int,int)
- NoiseColumn getBaseColumn(int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ BlockGetter getBaseColumn(int,int)
- NoiseColumn getBaseColumn(int,int)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ BlockGetter getBaseColumn(int,int)
- NoiseColumn getBaseColumn(int,int)
```

</details>












































<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
</summary>

```diff
+ BlockGetter lambda$findSuitableY$0(ChunkGenerator,BlockPos)
- NoiseColumn lambda$findSuitableY$0(ChunkGenerator,BlockPos)
```

</details>















<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.particle.DustColorTransitionParticle$Provider
+ net.minecraft.client.particle.DustParticle$1
- net.minecraft.client.particle.DustParticle$Provider
+ net.minecraft.client.particle.package-info
- net.minecraft.client.particle.VibrationSignalParticle
- net.minecraft.client.particle.VibrationSignalParticle$Provider
+ net.minecraft.client.particle.WakeParticle
- net.minecraft.client.particle.WakeParticle$1
+ net.minecraft.client.particle.WakeParticle$Provider
- net.minecraft.client.particle.WaterCurrentDownParticle
+ net.minecraft.client.particle.WaterCurrentDownParticle$1
- net.minecraft.client.particle.WaterCurrentDownParticle$Provider
+ net.minecraft.client.particle.WaterDropParticle
- net.minecraft.client.particle.WaterDropParticle$Provider
+ net.minecraft.client.particle.WhiteAshParticle
- net.minecraft.client.particle.WhiteAshParticle$Provider
- net.minecraft.client.player.AbstractClientPlayer
+ net.minecraft.client.player.Input
+ net.minecraft.client.player.inventory.Hotbar
- net.minecraft.client.player.inventory.package-info
- net.minecraft.client.player.KeyboardInput
+ net.minecraft.client.player.LocalPlayer
+ net.minecraft.client.player.package-info
- net.minecraft.client.player.RemotePlayer
- net.minecraft.client.renderer.banner.package-info
- net.minecraft.client.renderer.BiomeColors
+ net.minecraft.client.renderer.block.BlockModelShaper
- net.minecraft.client.renderer.block.BlockRenderDispatcher
+ net.minecraft.client.renderer.block.BlockRenderDispatcher$1
- net.minecraft.client.renderer.block.LiquidBlockRenderer
- net.minecraft.client.renderer.block.model.BakedQuad
+ net.minecraft.client.renderer.block.model.BlockElement
- net.minecraft.client.renderer.block.model.BlockElement$1
+ net.minecraft.client.renderer.block.model.BlockElement$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementFace
+ net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementRotation
+ net.minecraft.client.renderer.block.model.BlockFaceUV
- net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel
- net.minecraft.client.renderer.block.model.BlockModel$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel$GuiLight
- net.minecraft.client.renderer.block.model.BlockModel$LoopException
+ net.minecraft.client.renderer.block.model.BlockModelDefinition
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
- net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
+ net.minecraft.client.renderer.block.model.FaceBakery
- net.minecraft.client.renderer.block.model.FaceBakery$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator
- net.minecraft.client.renderer.block.model.ItemModelGenerator$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
- net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
+ net.minecraft.client.renderer.block.model.ItemOverride
- net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
+ net.minecraft.client.renderer.block.model.ItemOverrides
- net.minecraft.client.renderer.block.model.ItemTransform
+ net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms
+ net.minecraft.client.renderer.block.model.ItemTransforms$1
- net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
- net.minecraft.client.renderer.block.model.multipart.AndCondition
+ net.minecraft.client.renderer.block.model.multipart.Condition
- net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
+ net.minecraft.client.renderer.block.model.multipart.MultiPart
- net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
+ net.minecraft.client.renderer.block.model.multipart.OrCondition
- net.minecraft.client.renderer.block.model.multipart.package-info
- net.minecraft.client.renderer.block.model.multipart.Selector
+ net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
- net.minecraft.client.renderer.block.model.MultiVariant
+ net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
+ net.minecraft.client.renderer.block.model.package-info
- net.minecraft.client.renderer.block.model.Variant
+ net.minecraft.client.renderer.block.model.Variant$Deserializer
+ net.minecraft.client.renderer.block.ModelBlockRenderer
- net.minecraft.client.renderer.block.ModelBlockRenderer$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
+ net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
- net.minecraft.client.renderer.block.package-info
+ net.minecraft.client.renderer.block.statemap.package-info
- net.minecraft.client.renderer.blockentity.BannerRenderer
+ net.minecraft.client.renderer.blockentity.BeaconRenderer
- net.minecraft.client.renderer.blockentity.BedRenderer
+ net.minecraft.client.renderer.blockentity.BellRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
- net.minecraft.client.renderer.blockentity.BlockEntityRenderers
+ net.minecraft.client.renderer.blockentity.BrightnessCombiner
- net.minecraft.client.renderer.blockentity.CampfireRenderer
+ net.minecraft.client.renderer.blockentity.ChestRenderer
- net.minecraft.client.renderer.blockentity.ConduitRenderer
+ net.minecraft.client.renderer.blockentity.EnchantTableRenderer
- net.minecraft.client.renderer.blockentity.LecternRenderer
+ net.minecraft.client.renderer.blockentity.package-info
+ net.minecraft.client.renderer.blockentity.PistonHeadRenderer
- net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
+ net.minecraft.client.renderer.blockentity.SkullBlockRenderer
- net.minecraft.client.renderer.blockentity.SpawnerRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
+ net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
- net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
+ net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
- net.minecraft.client.renderer.chunk.package-info
- net.minecraft.client.renderer.chunk.RenderChunkRegion
+ net.minecraft.client.renderer.chunk.VisGraph
- net.minecraft.client.renderer.chunk.VisGraph$1
+ net.minecraft.client.renderer.chunk.VisibilitySet
- net.minecraft.client.renderer.ChunkBufferBuilderPack
+ net.minecraft.client.renderer.CubeMap
+ net.minecraft.client.renderer.culling.Frustum
- net.minecraft.client.renderer.culling.package-info
+ net.minecraft.client.renderer.debug.BeeDebugRenderer
- net.minecraft.client.renderer.debug.BeeDebugRenderer$BeeInfo
+ net.minecraft.client.renderer.debug.BeeDebugRenderer$HiveInfo
- net.minecraft.client.renderer.debug.BrainDebugRenderer
+ net.minecraft.client.renderer.debug.BrainDebugRenderer$BrainDump
- net.minecraft.client.renderer.debug.BrainDebugRenderer$PoiInfo
+ net.minecraft.client.renderer.debug.CaveDebugRenderer
- net.minecraft.client.renderer.debug.ChunkBorderRenderer
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer
- net.minecraft.client.renderer.debug.ChunkDebugRenderer$1
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer$ChunkData
- net.minecraft.client.renderer.debug.CollisionBoxRenderer
+ net.minecraft.client.renderer.debug.DebugRenderer
- net.minecraft.client.renderer.debug.DebugRenderer$SimpleDebugRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
- net.minecraft.client.renderer.DimensionSpecialEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
+ net.minecraft.client.renderer.EffectInstance
- net.minecraft.client.renderer.FaceInfo
+ net.minecraft.client.renderer.FaceInfo$1
- net.minecraft.client.renderer.FaceInfo$Constants
+ net.minecraft.client.renderer.FaceInfo$VertexInfo
- net.minecraft.client.renderer.FogRenderer
+ net.minecraft.client.renderer.FogRenderer$FogMode
- net.minecraft.client.renderer.GameRenderer
+ net.minecraft.client.renderer.GpuWarnlistManager
- net.minecraft.client.renderer.GpuWarnlistManager$1
+ net.minecraft.client.renderer.GpuWarnlistManager$Preparations
- net.minecraft.client.renderer.ItemBlockRenderTypes
+ net.minecraft.client.renderer.ItemInHandRenderer
- net.minecraft.client.renderer.ItemInHandRenderer$1
+ net.minecraft.client.renderer.ItemModelShaper
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$1
- net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
+ net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
- net.minecraft.client.renderer.LightTexture
+ net.minecraft.client.renderer.MultiBufferSource
- net.minecraft.client.renderer.MultiBufferSource$BufferSource
+ net.minecraft.client.renderer.OutlineBufferSource
- net.minecraft.client.renderer.OutlineBufferSource$1
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.PanoramaRenderer
+ net.minecraft.client.renderer.PostChain
- net.minecraft.client.renderer.PostPass
+ net.minecraft.client.renderer.Rect2i
- net.minecraft.client.renderer.RenderBuffers
+ net.minecraft.client.renderer.RenderStateShard
- net.minecraft.client.renderer.RenderStateShard$AlphaStateShard
+ net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
- net.minecraft.client.renderer.RenderStateShard$CullStateShard
+ net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
- net.minecraft.client.renderer.RenderStateShard$DiffuseLightingStateShard
+ net.minecraft.client.renderer.RenderStateShard$FogStateShard
- net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
+ net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
- net.minecraft.client.renderer.RenderStateShard$LineStateShard
+ net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$OutputStateShard
+ net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
- net.minecraft.client.renderer.RenderStateShard$PortalTexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$ShadeModelStateShard
- net.minecraft.client.renderer.RenderStateShard$TextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
+ net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
- net.minecraft.client.renderer.RenderType
+ net.minecraft.client.renderer.RenderType$1
- net.minecraft.client.renderer.RenderType$CompositeRenderType
+ net.minecraft.client.renderer.RenderType$CompositeRenderType$EqualsStrategy
- net.minecraft.client.renderer.RenderType$CompositeState
+ net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- net.minecraft.client.renderer.RenderType$OutlineProperty
+ net.minecraft.client.renderer.RunningTrimmedMean
- net.minecraft.client.renderer.ScreenEffectRenderer
+ net.minecraft.client.renderer.Sheets
- net.minecraft.client.renderer.Sheets$1
+ net.minecraft.client.renderer.SpriteCoordinateExpander
- net.minecraft.client.renderer.ViewArea
+ net.minecraft.client.renderer.VirtualScreen
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.package-info
- net.minecraft.commands.arguments.coordinates.BlockPosArgument
+ net.minecraft.commands.arguments.coordinates.ColumnPosArgument
- net.minecraft.commands.arguments.coordinates.Coordinates
+ net.minecraft.commands.arguments.coordinates.LocalCoordinates
- net.minecraft.commands.arguments.coordinates.package-info
- net.minecraft.commands.arguments.coordinates.RotationArgument
+ net.minecraft.commands.arguments.coordinates.SwizzleArgument
- net.minecraft.commands.arguments.coordinates.Vec2Argument
+ net.minecraft.commands.arguments.coordinates.Vec3Argument
- net.minecraft.commands.arguments.coordinates.WorldCoordinate
+ net.minecraft.commands.arguments.coordinates.WorldCoordinates
+ net.minecraft.commands.arguments.item.FunctionArgument
- net.minecraft.commands.arguments.item.FunctionArgument$1
+ net.minecraft.commands.arguments.item.FunctionArgument$2
- net.minecraft.commands.arguments.item.FunctionArgument$Result
+ net.minecraft.commands.arguments.item.ItemArgument
- net.minecraft.commands.arguments.item.ItemInput
+ net.minecraft.commands.arguments.item.ItemParser
- net.minecraft.commands.arguments.item.ItemPredicateArgument
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.NbtPathArgument$ListElementFunction
- net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$NbtPath
- net.minecraft.commands.arguments.NbtPathArgument$Node
+ net.minecraft.commands.arguments.NbtTagArgument
- net.minecraft.commands.arguments.ObjectiveArgument
+ net.minecraft.commands.arguments.ObjectiveCriteriaArgument
- net.minecraft.commands.arguments.OperationArgument
+ net.minecraft.commands.arguments.OperationArgument$Operation
- net.minecraft.commands.arguments.OperationArgument$SimpleOperation
+ net.minecraft.commands.arguments.package-info
+ net.minecraft.commands.arguments.ParticleArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ScoreboardSlotArgument
- net.minecraft.commands.arguments.ScoreHolderArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
- net.minecraft.commands.arguments.selector.EntitySelector
+ net.minecraft.commands.arguments.selector.EntitySelector$1
- net.minecraft.commands.arguments.selector.EntitySelectorParser
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
+ net.minecraft.commands.arguments.selector.options.package-info
- net.minecraft.commands.arguments.selector.package-info
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.TeamArgument
+ net.minecraft.commands.arguments.TimeArgument
- net.minecraft.commands.arguments.UuidArgument
+ net.minecraft.commands.exceptions.package-info
- net.minecraft.commands.package-info
+ net.minecraft.commands.synchronization.ArgumentSerializer
- net.minecraft.commands.synchronization.ArgumentTypes
+ net.minecraft.commands.synchronization.ArgumentTypes$1
- net.minecraft.commands.synchronization.ArgumentTypes$Entry
- net.minecraft.commands.synchronization.brigadier.BrigadierArgumentSerializers
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.FloatArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.LongArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.package-info
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
+ net.minecraft.commands.synchronization.EmptyArgumentSerializer
- net.minecraft.commands.synchronization.package-info
- net.minecraft.commands.synchronization.SuggestionProviders
+ net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
+ net.minecraft.core.AxisCycle
- net.minecraft.core.AxisCycle$1
+ net.minecraft.core.AxisCycle$2
- net.minecraft.core.AxisCycle$3
+ net.minecraft.core.BlockMath
- net.minecraft.core.BlockPos
+ net.minecraft.core.BlockPos$1
- net.minecraft.core.BlockPos$2
+ net.minecraft.core.BlockPos$3
- net.minecraft.core.BlockPos$4
+ net.minecraft.core.BlockPos$5
- net.minecraft.core.BlockPos$MutableBlockPos
+ net.minecraft.core.BlockSource
- net.minecraft.core.BlockSourceImpl
+ net.minecraft.core.Cursor3D
- net.minecraft.core.DefaultedRegistry
+ net.minecraft.core.Direction
- net.minecraft.core.Direction$1
+ net.minecraft.core.Direction$Axis
- net.minecraft.core.Direction$Axis$1
+ net.minecraft.core.Direction$Axis$2
- net.minecraft.core.Direction$Axis$3
+ net.minecraft.core.Direction$AxisDirection
- net.minecraft.core.Direction$Plane
+ net.minecraft.core.Direction8
- net.minecraft.core.FrontAndTop
+ net.minecraft.core.GlobalPos
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.MappedRegistry$RegistryEntry
- net.minecraft.core.NonNullList
- net.minecraft.core.particles.DustColorTransitionOptions$1
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
+ net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption$1
+ net.minecraft.core.Position
- net.minecraft.core.PositionImpl
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdventureAdvancements
+ net.minecraft.data.advancements.HusbandryAdvancements
- net.minecraft.data.advancements.NetherAdvancements
+ net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.StoryAdvancements
- net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.BuiltinRegistries
+ net.minecraft.data.DataGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.HashCache
- net.minecraft.data.info.BlockListReport
+ net.minecraft.data.info.CommandsReport
+ net.minecraft.data.info.package-info
- net.minecraft.data.info.RegistryDumpReport
- net.minecraft.data.loot.BlockLoot
+ net.minecraft.data.loot.ChestLoot
- net.minecraft.data.loot.EntityLoot
+ net.minecraft.data.loot.FishingLoot
- net.minecraft.data.loot.GiftLoot
+ net.minecraft.data.loot.LootTableProvider
+ net.minecraft.data.loot.package-info
- net.minecraft.data.loot.PiglinBarterLoot
- net.minecraft.data.Main
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
- net.minecraft.data.models.blockstates.Condition$1
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$1
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
+ net.minecraft.data.models.blockstates.PropertyDispatch
- net.minecraft.data.models.blockstates.PropertyDispatch$1
+ net.minecraft.data.models.blockstates.PropertyDispatch$C1
- net.minecraft.data.models.blockstates.PropertyDispatch$C2
+ net.minecraft.data.models.blockstates.PropertyDispatch$C3
- net.minecraft.data.models.blockstates.PropertyDispatch$C4
+ net.minecraft.data.models.blockstates.PropertyDispatch$C5
- net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
+ net.minecraft.data.models.blockstates.Selector
- net.minecraft.data.models.blockstates.Variant
+ net.minecraft.data.models.blockstates.VariantProperties
- net.minecraft.data.models.blockstates.VariantProperties$Rotation
+ net.minecraft.data.models.blockstates.VariantProperty
- net.minecraft.data.models.blockstates.VariantProperty$Value
- net.minecraft.data.models.ItemModelGenerators
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.ModelProvider
+ net.minecraft.data.models.package-info
- net.minecraft.data.package-info
+ net.minecraft.data.recipes.FinishedRecipe
+ net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.RecipeProvider
+ net.minecraft.data.recipes.ShapedRecipeBuilder
- net.minecraft.data.recipes.ShapedRecipeBuilder$Result
+ net.minecraft.data.recipes.ShapelessRecipeBuilder
- net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
+ net.minecraft.data.recipes.SingleItemRecipeBuilder
- net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
+ net.minecraft.data.recipes.SpecialRecipeBuilder
- net.minecraft.data.recipes.SpecialRecipeBuilder$1
+ net.minecraft.data.recipes.UpgradeRecipeBuilder
- net.minecraft.data.recipes.UpgradeRecipeBuilder$Result
- net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
+ net.minecraft.data.structures.SnbtToNbt$StructureConversionException
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.network.protocol.game.ClientboundAddVibrationSignalPacket
+ net.minecraft.network.protocol.game.ClientboundAnimatePacket
- net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
+ net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
- net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundBlockEventPacket
+ net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChatPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$1
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerAckPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
+ net.minecraft.network.protocol.game.ClientboundDisconnectPacket
- net.minecraft.network.protocol.game.ClientboundEntityEventPacket
+ net.minecraft.network.protocol.game.ClientboundExplodePacket
- net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
+ net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
- net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLoginPacket
- net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
+ net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
- net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ClientboundOpenBookPacket
- net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
+ net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
- net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$Event
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundResourcePackPacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
- net.minecraft.network.protocol.game.ClientboundSoundPacket
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundClientInformationPacket
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundContainerAckPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
+ net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
+ net.minecraft.network.protocol.game.ServerboundPickItemPacket
- net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
+ net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ net.minecraft.network.protocol.game.ServerboundRenameItemPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
- net.minecraft.network.protocol.game.ServerboundSelectTradePacket
+ net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
- net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
+ net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
- net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
- net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundSwingPacket
- net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
- net.minecraft.network.protocol.game.ServerboundUseItemPacket
- net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$10
+ net.minecraft.network.syncher.EntityDataSerializers$11
- net.minecraft.network.syncher.EntityDataSerializers$12
+ net.minecraft.network.syncher.EntityDataSerializers$13
- net.minecraft.network.syncher.EntityDataSerializers$14
+ net.minecraft.network.syncher.EntityDataSerializers$15
- net.minecraft.network.syncher.EntityDataSerializers$16
+ net.minecraft.network.syncher.EntityDataSerializers$17
- net.minecraft.network.syncher.EntityDataSerializers$18
+ net.minecraft.network.syncher.EntityDataSerializers$19
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
- net.minecraft.network.syncher.EntityDataSerializers$8
+ net.minecraft.network.syncher.EntityDataSerializers$9
- net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.obfuscate.DontObfuscateOrShrink
- net.minecraft.obfuscate.KeepAfterObfuscation
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
- net.minecraft.realms.NarrationHelper
- net.minecraft.realms.package-info
+ net.minecraft.realms.RealmsBridge
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RealmsServerAddress
- net.minecraft.realms.RepeatedNarrator
+ net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.resources.DelegatingOps
- net.minecraft.resources.package-info
+ net.minecraft.resources.RegistryDataPackCodec
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryLookupCodec
- net.minecraft.resources.RegistryReadOps
+ net.minecraft.resources.RegistryReadOps$1
- net.minecraft.resources.RegistryReadOps$ReadCache
+ net.minecraft.resources.RegistryReadOps$ResourceAccess
- net.minecraft.resources.RegistryReadOps$ResourceAccess$1
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
- net.minecraft.resources.RegistryWriteOps
+ net.minecraft.resources.ResourceKey
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$1
+ net.minecraft.server.ChainedJsonException$Entry
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
- net.minecraft.server.commands.package-info
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
- net.minecraft.tags.Tag$OptionalElementEntry
+ net.minecraft.tags.Tag$OptionalTagEntry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagCollection$1
+ net.minecraft.tags.TagContainer
- net.minecraft.tags.TagContainer$1
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagManager
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CryptException
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
- net.minecraft.util.ExtraCodecs$1
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FormattedCharSequence
- net.minecraft.util.FormattedCharSink
+ net.minecraft.util.FrameTimer
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HeapDumper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InsensitiveStringMap
+ net.minecraft.util.LinearCongruentialGenerator
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.Mth
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$1
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.ProgressListener
- net.minecraft.util.RewindableStream
+ net.minecraft.util.RewindableStream$1
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$1
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringDecomposer
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
+ net.minecraft.util.StringRepresentable$2
- net.minecraft.util.StringUtil
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.TimeUtil
- net.minecraft.util.Tuple
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
- net.minecraft.world.damagesource.BadRespawnPointDamage
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.EntityDamageSource
- net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffects$1
+ net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BabyFollowAdult
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
- net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
+ net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
- net.minecraft.world.entity.ai.behavior.LookAtTargetSink
+ net.minecraft.world.entity.ai.behavior.MeleeAttack
- net.minecraft.world.entity.ai.behavior.Mount
+ net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
- net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunIf
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.RunSometimes
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VictoryStroll
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.WeightedList
- net.minecraft.world.entity.ai.behavior.WeightedList$1
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.DolphinLookControl
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.PlayGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.TakeFlowerGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$1
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$1
+ net.minecraft.world.entity.animal.Dolphin$DolphinMoveControl
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.Fox$1
- net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
+ net.minecraft.world.entity.animal.Fox$FaceplantGoal
- net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
+ net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
- net.minecraft.world.entity.animal.Fox$FoxBreedGoal
+ net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
- net.minecraft.world.entity.animal.Fox$FoxFloatGoal
+ net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
- net.minecraft.world.entity.animal.Fox$FoxGroupData
+ net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
- net.minecraft.world.entity.animal.Fox$FoxLookControl
+ net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
- net.minecraft.world.entity.animal.Fox$FoxMoveControl
+ net.minecraft.world.entity.animal.Fox$FoxPanicGoal
- net.minecraft.world.entity.animal.Fox$FoxPounceGoal
+ net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
- net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
+ net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
- net.minecraft.world.entity.animal.Fox$SeekShelterGoal
+ net.minecraft.world.entity.animal.Fox$SleepGoal
- net.minecraft.world.entity.animal.Fox$StalkPreyGoal
+ net.minecraft.world.entity.animal.Fox$Type
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$1
- net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
+ net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
- net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
+ net.minecraft.world.entity.animal.horse.Markings
- net.minecraft.world.entity.animal.horse.Mule
+ net.minecraft.world.entity.animal.horse.package-info
+ net.minecraft.world.entity.animal.horse.SkeletonHorse
- net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
+ net.minecraft.world.entity.animal.horse.TraderLlama
- net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ net.minecraft.world.entity.animal.horse.Variant
- net.minecraft.world.entity.animal.horse.ZombieHorse
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
- net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$1
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$1
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
- net.minecraft.world.entity.animal.Turtle
+ net.minecraft.world.entity.animal.Turtle$1
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTemptGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.boss.BossMob
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$RemovalReason
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$1
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
- net.minecraft.world.item.crafting.package-info
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
+ net.minecraft.world.item.crafting.SimpleRecipeSerializer
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmokingRecipe
+ net.minecraft.world.item.crafting.StonecutterRecipe
- net.minecraft.world.item.crafting.SuspiciousStewRecipe
+ net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
+ net.minecraft.world.item.enchantment.ArrowDamageEnchantment
- net.minecraft.world.item.enchantment.ArrowFireEnchantment
+ net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
- net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
+ net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
- net.minecraft.world.item.enchantment.BindingCurseEnchantment
+ net.minecraft.world.item.enchantment.DamageEnchantment
- net.minecraft.world.item.enchantment.DigDurabilityEnchantment
+ net.minecraft.world.item.enchantment.DiggingEnchantment
- net.minecraft.world.item.enchantment.Enchantment
+ net.minecraft.world.item.enchantment.Enchantment$Rarity
- net.minecraft.world.item.enchantment.EnchantmentCategory
+ net.minecraft.world.item.enchantment.EnchantmentCategory$1
- net.minecraft.world.item.enchantment.EnchantmentCategory$10
+ net.minecraft.world.item.enchantment.EnchantmentCategory$11
- net.minecraft.world.item.enchantment.EnchantmentCategory$12
+ net.minecraft.world.item.enchantment.EnchantmentCategory$13
- net.minecraft.world.item.enchantment.EnchantmentCategory$14
+ net.minecraft.world.item.enchantment.EnchantmentCategory$2
- net.minecraft.world.item.enchantment.EnchantmentCategory$3
+ net.minecraft.world.item.enchantment.EnchantmentCategory$4
- net.minecraft.world.item.enchantment.EnchantmentCategory$5
+ net.minecraft.world.item.enchantment.EnchantmentCategory$6
- net.minecraft.world.item.enchantment.EnchantmentCategory$7
+ net.minecraft.world.item.enchantment.EnchantmentCategory$8
- net.minecraft.world.item.enchantment.EnchantmentCategory$9
+ net.minecraft.world.item.enchantment.EnchantmentHelper
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
- net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
- net.minecraft.world.item.enchantment.FishingSpeedEnchantment
+ net.minecraft.world.item.enchantment.FrostWalkerEnchantment
- net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
- net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
+ net.minecraft.world.item.enchantment.ProtectionEnchantment
- net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.package-info
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BarrelBlockEntity
+ net.minecraft.world.level.block.entity.BarrelBlockEntity$1
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
- net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
+ net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.SeagrassBlock
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
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$1
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkBiomeContainer
- net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.ChunkStatus
+ net.minecraft.world.level.chunk.ChunkStatus$ChunkType
- net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.storage.OldChunkStorage$1
+ net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ChunkTickList
+ net.minecraft.world.level.ChunkTickList$1
- net.minecraft.world.level.ChunkTickList$ScheduledTick
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.entity.ChunkEntities
+ net.minecraft.world.level.entity.ChunkStatusUpdateListener
- net.minecraft.world.level.entity.EntityAccess
+ net.minecraft.world.level.entity.EntityInLevelCallback
- net.minecraft.world.level.entity.EntityInLevelCallback$1
+ net.minecraft.world.level.entity.EntityLookup
- net.minecraft.world.level.entity.EntityPersistentStorage
+ net.minecraft.world.level.entity.EntitySection
- net.minecraft.world.level.entity.EntitySectionStorage
+ net.minecraft.world.level.entity.EntityTickList
- net.minecraft.world.level.entity.EntityTypeTest
+ net.minecraft.world.level.entity.EntityTypeTest$1
- net.minecraft.world.level.entity.LevelCallback
+ net.minecraft.world.level.entity.LevelEntityGetter
- net.minecraft.world.level.entity.LevelEntityGetterAdapter
+ net.minecraft.world.level.entity.package-info
+ net.minecraft.world.level.entity.PersistentEntitySectionManager
- net.minecraft.world.level.entity.PersistentEntitySectionManager$1
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
- net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ net.minecraft.world.level.entity.TransientEntitySectionManager
- net.minecraft.world.level.entity.TransientEntitySectionManager$1
+ net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
- net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.gameevent.BlockPositionSource
- net.minecraft.world.level.gameevent.EntityPositionSource
- net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
- net.minecraft.world.level.gameevent.vibrations.package-info
- net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
- net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
+ net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.package-info
+ net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$Factory
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$1
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.SmallDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$1
- net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
- net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature
- net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
+ net.minecraft.world.level.levelgen.feature.StructureFeature
- net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
+ net.minecraft.world.level.levelgen.feature.StructurePieceType
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
+ net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.placement.BaseHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ChanceDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
+ net.minecraft.world.level.levelgen.placement.CountDecorator
- net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
+ net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
- net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.DecorationContext
- net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
+ net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.EdgeDecorator
+ net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.HeightmapDecorator
- net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.HeightMapWorldSurfaceDecorator
+ net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
- net.minecraft.world.level.levelgen.placement.nether.FireDecorator
+ net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
- net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
- net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
- net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.RangeDecorator
- net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
+ net.minecraft.world.level.levelgen.placement.Spread32Decorator
- net.minecraft.world.level.levelgen.placement.SquareDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
- net.minecraft.world.level.levelgen.placement.VeryBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.structure.BeardedStructureStart
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces
- net.minecraft.world.level.levelgen.structure.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.IglooPieces
+ net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
- net.minecraft.world.level.levelgen.structure.MineShaftPieces
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureStart$1
- net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.package-info
- net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.synth.SurfaceNoise
+ net.minecraft.world.level.lighting.BlockLightEngine
- net.minecraft.world.level.lighting.BlockLightSectionStorage
+ net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- net.minecraft.world.level.lighting.DataLayerStorageMap
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
- net.minecraft.world.level.lighting.FlatDataLayer
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.material.FogType
- net.minecraft.world.level.material.LavaFluid
+ net.minecraft.world.level.material.LavaFluid$Flowing
- net.minecraft.world.level.material.LavaFluid$Source
+ net.minecraft.world.level.material.Material
- net.minecraft.world.level.material.Material$Builder
+ net.minecraft.world.level.material.MaterialColor
- net.minecraft.world.level.material.package-info
- net.minecraft.world.level.material.PushReaction
+ net.minecraft.world.level.material.WaterFluid
- net.minecraft.world.level.material.WaterFluid$Flowing
+ net.minecraft.world.level.material.WaterFluid$Source
+ net.minecraft.world.level.newbiome.area.Area
- net.minecraft.world.level.newbiome.area.AreaFactory
+ net.minecraft.world.level.newbiome.area.LazyArea
- net.minecraft.world.level.newbiome.area.package-info
+ net.minecraft.world.level.newbiome.context.BigContext
- net.minecraft.world.level.newbiome.context.Context
+ net.minecraft.world.level.newbiome.context.LazyAreaContext
- net.minecraft.world.level.newbiome.context.package-info
+ net.minecraft.world.level.newbiome.layer.AddDeepOceanLayer
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer$CoolWarm
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer$HeatIce
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- net.minecraft.world.level.newbiome.layer.AddIslandLayer
+ net.minecraft.world.level.newbiome.layer.AddMushroomIslandLayer
- net.minecraft.world.level.newbiome.layer.AddSnowLayer
+ net.minecraft.world.level.newbiome.layer.BiomeEdgeLayer
- net.minecraft.world.level.newbiome.layer.BiomeInitLayer
+ net.minecraft.world.level.newbiome.layer.IslandLayer
- net.minecraft.world.level.newbiome.layer.Layer
+ net.minecraft.world.level.newbiome.layer.LayerBiomes
- net.minecraft.world.level.newbiome.layer.Layers
+ net.minecraft.world.level.newbiome.layer.Layers$Category
- net.minecraft.world.level.newbiome.layer.OceanLayer
+ net.minecraft.world.level.newbiome.layer.OceanMixerLayer
+ net.minecraft.world.level.newbiome.layer.package-info
- net.minecraft.world.level.newbiome.layer.RareBiomeLargeLayer
+ net.minecraft.world.level.newbiome.layer.RareBiomeSpotLayer
- net.minecraft.world.level.newbiome.layer.RegionHillsLayer
+ net.minecraft.world.level.newbiome.layer.RemoveTooMuchOceanLayer
- net.minecraft.world.level.newbiome.layer.RiverInitLayer
+ net.minecraft.world.level.newbiome.layer.RiverLayer
- net.minecraft.world.level.newbiome.layer.RiverMixerLayer
+ net.minecraft.world.level.newbiome.layer.ShoreLayer
- net.minecraft.world.level.newbiome.layer.SmoothLayer
- net.minecraft.world.level.newbiome.layer.traits.AreaTransformer0
+ net.minecraft.world.level.newbiome.layer.traits.AreaTransformer1
- net.minecraft.world.level.newbiome.layer.traits.AreaTransformer2
+ net.minecraft.world.level.newbiome.layer.traits.BishopTransformer
- net.minecraft.world.level.newbiome.layer.traits.C0Transformer
+ net.minecraft.world.level.newbiome.layer.traits.C1Transformer
- net.minecraft.world.level.newbiome.layer.traits.CastleTransformer
+ net.minecraft.world.level.newbiome.layer.traits.DimensionOffset0Transformer
- net.minecraft.world.level.newbiome.layer.traits.DimensionOffset1Transformer
+ net.minecraft.world.level.newbiome.layer.traits.DimensionTransformer
+ net.minecraft.world.level.newbiome.layer.traits.package-info
- net.minecraft.world.level.newbiome.layer.traits.PixelTransformer
+ net.minecraft.world.level.newbiome.layer.ZoomLayer
- net.minecraft.world.level.newbiome.layer.ZoomLayer$1
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.TurtleNodeEvaluator
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$1
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$1
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelResource
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.Deserializers
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot
- net.minecraft.world.level.storage.loot.entries.DynamicLoot$1
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$1
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
- net.minecraft.world.level.storage.loot.entries.LootItem$1
+ net.minecraft.world.level.storage.loot.entries.LootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.LootTableReference$1
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
+ net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$1
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$1
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$1
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$1
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$1
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$1
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
- net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
+ net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LimitCount$1
+ net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
+ net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$1
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$1
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$1
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$1
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$1
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$DefaultSerializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$1
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
+ net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.IntRange$Serializer
+ net.minecraft.world.level.storage.loot.ItemModifierManager
- net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$1
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$1
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootPool$Serializer
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$1
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.LootTable$Serializer
- net.minecraft.world.level.storage.loot.LootTables
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.PredicateManager
- net.minecraft.world.level.storage.loot.PredicateManager$1
+ net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$1
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$1
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$1
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$1
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$1
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$DefaultSerializer
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
+ net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$1
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$1
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$DefaultSerializer
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$1
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$1
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$1
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$DefaultSerializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$1
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
+ net.minecraft.world.level.storage.loot.providers.score.package-info
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
- net.minecraft.world.level.storage.loot.Serializer
+ net.minecraft.world.level.storage.loot.SerializerType
- net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.McRegionUpgrader
- net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.storage.PlayerDataStorage
+ net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.threaded.package-info
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$1
+ net.minecraft.world.level.timers.TimerQueue$Event
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
+ net.minecraft.world.package-info
- net.minecraft.world.phys.AABB
+ net.minecraft.world.phys.BlockHitResult
- net.minecraft.world.phys.EntityHitResult
+ net.minecraft.world.phys.HitResult
- net.minecraft.world.phys.HitResult$Type
+ net.minecraft.world.phys.package-info
- net.minecraft.world.phys.shapes.ArrayVoxelShape
+ net.minecraft.world.phys.shapes.ArrayVoxelShape$1
- net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
+ net.minecraft.world.phys.shapes.BooleanOp
- net.minecraft.world.phys.shapes.CollisionContext
+ net.minecraft.world.phys.shapes.CubePointRange
- net.minecraft.world.phys.shapes.CubeVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteCubeMerger
- net.minecraft.world.phys.shapes.DiscreteVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ net.minecraft.world.phys.shapes.EntityCollisionContext
- net.minecraft.world.phys.shapes.EntityCollisionContext$1
+ net.minecraft.world.phys.shapes.IdenticalMerger
- net.minecraft.world.phys.shapes.IndexMerger
+ net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
- net.minecraft.world.phys.shapes.IndirectMerger
+ net.minecraft.world.phys.shapes.NonOverlappingMerger
- net.minecraft.world.phys.shapes.OffsetDoubleList
- net.minecraft.world.phys.shapes.package-info
+ net.minecraft.world.phys.shapes.Shapes
- net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
+ net.minecraft.world.phys.shapes.SliceShape
- net.minecraft.world.phys.shapes.SubShape
+ net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.phys.Vec2
- net.minecraft.world.phys.Vec3
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
+ net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
- net.minecraft.world.scores.PlayerTeam
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.Scoreboard
+ net.minecraft.world.scores.ScoreboardSaveData
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
- net.minecraft.world.ShulkerSharedHelper
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.Snooper
- net.minecraft.world.Snooper$1
+ net.minecraft.world.SnooperPopulator
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +1M
```
```
XXX.gui.components.BossHealthOverlay -1M
```
```
XXX.gui.screens.EditServerScreen -1M
```
```
XXX.gui.screens.Screen -1M
```
```
XXX.spectator.categories.SpectatorPage +1M -2M | -1P
```
```
XXX.client.multiplayer.ClientAdvancements -1M
```
```
XXX.client.multiplayer.ClientChunkCache -1M
```
```
XXX.client.multiplayer.ClientLevel +1M
```
```
XXX.client.multiplayer.ClientPacketListener +4M -2M
```
```
XXX.metadata.animation.AnimationMetadataSection -1M
```
```
XXX.resources.sounds.AbstractSoundInstance -1M | -1P
```
```
XXX.client.server.LanServer -1M
```
```
XXX.minecraft.core.Registry +57M -55M | +4P
```
```
XXX.minecraft.core.Vec3i +4M -3M
```
```
XXX.data.tags.TagsProvider +3M -4M
```
```
XXX.data.worldgen.BiomeDefaultFeatures +1M
```
```
XXX.gametest.framework.GameTestHelper +4M
```
```
XXX.minecraft.nbt.ListTag -1M
```
```
XXX.minecraft.nbt.Tag -2M
```
```
XXX.protocol.game.ClientGamePacketListener +1P
```
```
XXX.minecraft.server.MinecraftServer -3M | -1P
```
```
XXX.minecraft.server.ServerFunctionManager -1M
```
```
XXX.minecraft.server.ServerScoreboard -1M
```
```
XXX.server.level.WorldGenRegion +3M -2M
```
```
XXX.server.network.ServerGamePacketListenerImpl -2M
```
```
XXX.packs.resources.ReloadableResourceManager +1P -2P
```
```
XXX.packs.resources.SimpleReloadableResourceManager +2M -4M | -1P
```
```
XXX.server.players.PlayerList -2M
```
```
XXX.server.players.ServerOpList +1M -2M
```
```
XXX.server.players.UserBanList +1M -1M
```
```
XXX.server.players.UserWhiteList +1M -1M
```
```
XXX.minecraft.sounds.SoundEvents +7P
```
```
XXX.minecraft.stats.StatType -1M
```
```
XXX.minecraft.tags.BlockTags +2P
```
```
XXX.minecraft.util.UniformInt +3M
```
```
XXX.entity.item.ItemEntity -1M
```
```
XXX.entity.monster.Pillager +1M -1M
```
```
XXX.monster.hoglin.Hoglin -1M
```
```
XXX.entity.npc.ClientSideMerchant -1M | -1P
```
```
XXX.world.inventory.HopperMenu -1M
```
```
XXX.world.inventory.Slot -2M
```
```
XXX.world.item.DyeColor -1M | -2P
```
```
XXX.world.item.Items +1P
```
```
XXX.world.level.EmptyBlockGetter +2M -2M
```
```
XXX.world.level.Level +1M -4M
```
```
XXX.world.level.LevelAccessor +3M | +1P
```
```
XXX.world.level.LevelReader +2M
```
```
XXX.world.level.PathNavigationRegion +2M -2M
```
```
XXX.level.biome.Biome +1M -1M
```
```
XXX.level.biome.Biomes +1P
```
```
XXX.level.block.AnvilBlock +1M
```
```
XXX.level.block.DoorBlock +1M -1M
```
```
XXX.level.block.Fallable +2M
```
```
XXX.level.block.PointedDripstoneBlock$DripType +1M -1M | +1P
```
```
XXX.state.pattern.BlockInWorld -2M
```
```
XXX.level.chunk.LevelChunk +17M -13M | +1P
```
```
XXX.level.chunk.OldDataLayer -3M
```
```
XXX.level.levelgen.NoiseSettings +5M -1M | +1P
```
```
XXX.level.levelgen.WorldgenRandom -2M | -1P
```

</details>





























































































































































<details>
<summary>
net.minecraft.Util
</summary>

```diff
- DataResult fixedSize(DoubleStream,int)
```

</details>

























































































































<details>
<summary>
net.minecraft.client.gui.components.BossHealthOverlay
</summary>

```diff
+ boolean hasBoss()
```

</details>


























































<details>
<summary>
net.minecraft.client.gui.screens.EditServerScreen
</summary>

```diff
+ Component createServerButtonText(ServerData$ServerPackStatus)
```

</details>












<details>
<summary>
net.minecraft.client.gui.screens.Screen
</summary>

```diff
+ void setSize(int,int)
```

</details>































































































<details>
<summary>
net.minecraft.client.gui.spectator.categories.SpectatorPage
</summary>

```diff
+ SpectatorMenuCategory getCategory()
- void <init>(List,int)
+ void <init>(SpectatorMenuCategory,List,int)
```

</details>



































































<details>
<summary>
net.minecraft.client.multiplayer.ClientAdvancements
</summary>

```diff
+ Map getProgress()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientChunkCache
</summary>

```diff
+ boolean isEntityTickingChunk(Entity)
```

</details>

<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
- void gameEvent(Entity,GameEvent,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
- IllegalArgumentException lambda$handleCustomPayload$9(ResourceLocation)
- void handleAddVibrationSignal(ClientboundAddVibrationSignalPacket)
- void lambda$handlePlaceRecipe$10(AbstractContainerMenu,Recipe)
+ void lambda$handlePlaceRecipe$9(AbstractContainerMenu,Recipe)
- void readSectionList(int,int,LevelLightEngine,LightLayer,BitSet,BitSet,Iterator,boolean)
+ void readSectionList(int,int,LevelLightEngine,LightLayer,long,long,Iterator,boolean)
```

</details>

















































































































































































































<details>
<summary>
net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
</summary>

```diff
+ boolean hasCustomFrameTime(int)
```

</details>
















<details>
<summary>
net.minecraft.client.resources.sounds.AbstractSoundInstance
</summary>

```diff
+ boolean hasPriority()
```

</details>



















<details>
<summary>
net.minecraft.client.server.LanServer
</summary>

```diff
+ boolean isUpToDate()
```

</details>






































<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ Activity lambda$static$26()
- Activity lambda$static$28()
+ Attribute lambda$static$18()
- Attribute lambda$static$19()
+ Block lambda$static$3()
- Block lambda$static$4()
- BlockEntityType lambda$static$10()
+ BlockEntityType lambda$static$9()
+ BlockPlacerType lambda$static$40()
- BlockPlacerType lambda$static$42()
+ BlockStateProviderType lambda$static$39()
- BlockStateProviderType lambda$static$41()
+ ChunkStatus lambda$static$12()
- ChunkStatus lambda$static$13()
+ Codec lambda$static$45()
+ Codec lambda$static$46()
- Codec lambda$static$47()
- Codec lambda$static$48()
+ DataResult lambda$decode$51(Number)
- DataResult lambda$decode$53(Number)
+ DataResult lambda$decode$53(Pair)
- DataResult lambda$decode$55(Pair)
+ Enchantment lambda$static$4()
- Enchantment lambda$static$5()
+ EntityType lambda$static$5()
- EntityType lambda$static$6()
+ Feature lambda$static$35()
- Feature lambda$static$37()
+ FeatureDecorator lambda$static$38()
- FeatureDecorator lambda$static$40()
+ FeatureSizeType lambda$static$44()
- FeatureSizeType lambda$static$46()
+ Fluid lambda$static$1()
- Fluid lambda$static$2()
+ FoliagePlacerType lambda$static$41()
- FoliagePlacerType lambda$static$43()
- GameEvent lambda$static$0()
+ Item lambda$static$6()
- Item lambda$static$7()
+ LootItemConditionType lambda$static$29()
- LootItemConditionType lambda$static$31()
+ LootItemFunctionType lambda$static$28()
- LootItemFunctionType lambda$static$30()
+ LootNbtProviderType lambda$static$31()
- LootNbtProviderType lambda$static$33()
+ LootNumberProviderType lambda$static$30()
- LootNumberProviderType lambda$static$32()
+ LootPoolEntryType lambda$static$27()
- LootPoolEntryType lambda$static$29()
+ LootScoreProviderType lambda$static$32()
- LootScoreProviderType lambda$static$34()
+ MemoryModuleType lambda$static$23()
- MemoryModuleType lambda$static$25()
+ MenuType lambda$static$15()
- MenuType lambda$static$16()
+ MobEffect lambda$static$2()
- MobEffect lambda$static$3()
+ Motive lambda$static$10()
- Motive lambda$static$11()
+ Object lambda$keys$54(DynamicOps,ResourceLocation)
- Object lambda$keys$56(DynamicOps,ResourceLocation)
+ Pair lambda$decode$52(DynamicOps,Object)
- Pair lambda$decode$54(DynamicOps,Object)
+ ParticleType lambda$static$8()
- ParticleType lambda$static$9()
+ PoiType lambda$static$22()
- PoiType lambda$static$24()
- PositionSourceType lambda$static$20()
+ PosRuleTestType lambda$static$14()
- PosRuleTestType lambda$static$15()
+ Potion lambda$static$7()
- Potion lambda$static$8()
+ RecipeSerializer lambda$static$17()
- RecipeSerializer lambda$static$18()
+ RecipeType lambda$static$16()
- RecipeType lambda$static$17()
+ ResourceLocation lambda$static$11()
- ResourceLocation lambda$static$12()
+ RuleTestType lambda$static$13()
- RuleTestType lambda$static$14()
+ Schedule lambda$static$25()
- Schedule lambda$static$27()
+ SensorType lambda$static$24()
- SensorType lambda$static$26()
+ SoundEvent lambda$static$0()
- SoundEvent lambda$static$1()
+ StatType lambda$static$19()
- StatType lambda$static$21()
+ StructureFeature lambda$static$36()
- StructureFeature lambda$static$38()
+ StructurePieceType lambda$static$37()
- StructurePieceType lambda$static$39()
+ StructurePoolElementType lambda$static$48()
- StructurePoolElementType lambda$static$50()
+ StructureProcessorType lambda$static$47()
- StructureProcessorType lambda$static$49()
+ SurfaceBuilder lambda$static$33()
- SurfaceBuilder lambda$static$35()
+ TreeDecoratorType lambda$static$43()
- TreeDecoratorType lambda$static$45()
+ TrunkPlacerType lambda$static$42()
- TrunkPlacerType lambda$static$44()
+ VillagerProfession lambda$static$21()
- VillagerProfession lambda$static$23()
+ VillagerType lambda$static$20()
- VillagerType lambda$static$22()
+ void lambda$checkRegistry$50(WritableRegistry,WritableRegistry)
- void lambda$checkRegistry$52(WritableRegistry,WritableRegistry)
+ void lambda$static$49(ResourceLocation,Supplier)
- void lambda$static$51(ResourceLocation,Supplier)
+ WorldCarver lambda$static$34()
- WorldCarver lambda$static$36()
```

</details>



<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
- double distSqr(Vec3i,boolean)
- Vec3i setX(int)
- Vec3i setY(int)
- Vec3i setZ(int)
+ void setX(int)
+ void setY(int)
+ void setZ(int)
```

</details>





















<details>
<summary>
net.minecraft.data.tags.TagsProvider
</summary>

```diff
- boolean lambda$null$0(Tag$BuilderEntry)
+ Object lambda$run$1(ResourceLocation)
+ Tag lambda$run$0(Tag,ResourceLocation)
- Tag$Builder lambda$getOrCreateRawBuilder$2(ResourceLocation)
+ Tag$Builder lambda$getOrCreateRawBuilder$3(ResourceLocation)
- void lambda$run$1(HashCache,ResourceLocation,Tag$Builder)
+ void lambda$run$2(Function,Function,HashCache,ResourceLocation,Tag$Builder)
```

</details>




<details>
<summary>
net.minecraft.data.worldgen.BiomeDefaultFeatures
</summary>

```diff
- void addDripstone(BiomeGenerationSettings$Builder)
```

</details>















<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- AABB getRelativeBounds()
- BlockEntity getBlockEntity(BlockPos)
- void destroyBlock(BlockPos)
- void forEveryBlockInStructure(Consumer)
```

</details>
























<details>
<summary>
net.minecraft.nbt.ListTag
</summary>

```diff
+ void stripEmptyChildren()
```

</details>










<details>
<summary>
net.minecraft.nbt.Tag
</summary>

```diff
+ boolean isEmpty()
+ void stripEmptyChildren()
```

</details>







































<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
+ Executor getBackgroundTaskExecutor()
+ int getMaxBuildHeight()
+ void setMaxBuildHeight(int)
```

</details>



<details>
<summary>
net.minecraft.server.ServerFunctionManager
</summary>

```diff
+ MinecraftServer getServer()
```

</details>

<details>
<summary>
net.minecraft.server.ServerScoreboard
</summary>

```diff
+ MinecraftServer getServer()
```

</details>
















































<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
- int getHeight()
- int getMinBuildHeight()
+ int getMinSection()
+ int getSectionsCount()
- void gameEvent(Entity,GameEvent,BlockPos)
```

</details>







<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
+ void info(String)
+ void warn(String)
```

</details>




























<details>
<summary>
net.minecraft.server.packs.resources.SimpleReloadableResourceManager
</summary>

```diff
+ Object lambda$createFullReload$0(List)
- Object lambda$createReload$0(List)
+ ReloadInstance createFullReload(Executor,Executor,CompletableFuture,List)
+ ReloadInstance createQueuedReload(Executor,Executor,CompletableFuture)
- ReloadInstance createReload(Executor,Executor,CompletableFuture,List)
+ ReloadInstance createReload(Executor,Executor,List,CompletableFuture)
```

</details>








<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ void blackList(GameProfile)
+ void whiteList(GameProfile)
```

</details>
<details>
<summary>
net.minecraft.server.players.ServerOpList
</summary>

```diff
+ GameProfile find(String)
+ int getOpLevel(GameProfile)
- String[] lambda$getUserList$0(int)
```

</details>

<details>
<summary>
net.minecraft.server.players.UserBanList
</summary>

```diff
+ GameProfile find(String)
- String[] lambda$getUserList$0(int)
```

</details>
<details>
<summary>
net.minecraft.server.players.UserWhiteList
</summary>

```diff
+ GameProfile find(String)
- String[] lambda$getUserList$0(int)
```

</details>












<details>
<summary>
net.minecraft.stats.StatType
</summary>

```diff
+ int size()
```

</details>




<details>
<summary>
net.minecraft.util.UniformInt
</summary>

```diff
- int getBaseValue()
- int getMaxValue()
- int getSpread()
```

</details>


























































































































<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
+ void burn(int)
```

</details>































<details>
<summary>
net.minecraft.world.entity.monster.Pillager
</summary>

```diff
- Container getInventory()
+ SimpleContainer getInventory()
```

</details>


























<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
+ float getMovementSpeed()
```

</details>









<details>
<summary>
net.minecraft.world.entity.npc.ClientSideMerchant
</summary>

```diff
+ Container getContainer()
```

</details>













































































<details>
<summary>
net.minecraft.world.inventory.HopperMenu
</summary>

```diff
+ Container getContainer()
```

</details>
















<details>
<summary>
net.minecraft.world.inventory.Slot
</summary>

```diff
+ boolean isAt(Container,int)
+ void swap(Slot)
```

</details>

























<details>
<summary>
net.minecraft.world.item.DyeColor
</summary>

```diff
+ int getTextureDiffuseColorBGR()
```

</details>






























<details>
<summary>
net.minecraft.world.level.EmptyBlockGetter
</summary>

```diff
- int getHeight()
- int getMinBuildHeight()
+ int getMinSection()
+ int getSectionsCount()
```

</details>










<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ BlockState getTopBlockState(BlockPos)
+ int getMinSection()
+ int getSectionsCount()
+ void onBlockEntityAdd(BlockEntity)
- void postGameEventInRadius(Entity,GameEvent,BlockPos,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
- void gameEvent(Entity,GameEvent,Entity)
- void gameEvent(GameEvent,BlockPos)
- void gameEvent(GameEvent,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelReader
</summary>

```diff
- int getHeight()
- int getMinBuildHeight()
```

</details>






<details>
<summary>
net.minecraft.world.level.PathNavigationRegion
</summary>

```diff
- int getHeight()
- int getMinBuildHeight()
+ int getMinSection()
+ int getSectionsCount()
```

</details>






<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
- void lambda$generate$18(WorldGenRegion,StructureFeatureManager,ChunkGenerator,WorldgenRandom,int,int,int,int,int,StructureStart)
+ void lambda$generate$18(WorldGenRegion,StructureFeatureManager,ChunkGenerator,WorldgenRandom,int,int,int,int,StructureStart)
```

</details>


























<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
- DamageSource getFallDamageSource()
```

</details>











































<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
- void setOpen(Entity,Level,BlockState,BlockPos,boolean)
+ void setOpen(Level,BlockState,BlockPos,boolean)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.Fallable
</summary>

```diff
- DamageSource getFallDamageSource()
- Predicate getHurtsEntitySelector()
```

</details>



































<details>
<summary>
net.minecraft.world.level.block.PointedDripstoneBlock$DripType
</summary>

```diff
- void <init>(Fluid,DimensionType)
+ void <init>(Fluid)
```

</details>










































<details>
<summary>
net.minecraft.world.level.block.state.pattern.BlockInWorld
</summary>

```diff
+ boolean lambda$hasState$1(BlockState,BlockInWorld)
+ Predicate hasState(BlockState)
```

</details>


















<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
+ Block lambda$unpackTicks$7(BlockPos)
- Block lambda$unpackTicks$8(BlockPos)
+ boolean lambda$getLights$4(BlockPos)
- boolean lambda$getLights$5(BlockPos)
+ boolean lambda$replaceWithPacketData$3(int,BlockEntity)
- boolean lambda$replaceWithPacketData$4(int,BlockEntity)
+ Fluid lambda$unpackTicks$8(BlockPos)
- Fluid lambda$unpackTicks$9(BlockPos)
- GameEventDispatcher getEventDispatcher(int)
- GameEventDispatcher lambda$getEventDispatcher$0(int)
+ Heightmap lambda$getOrCreateHeightmapUnprimed$0(Heightmap$Types)
- Heightmap lambda$getOrCreateHeightmapUnprimed$1(Heightmap$Types)
- int getHeight()
- int getMinBuildHeight()
+ int getMinSection()
+ int getSectionsCount()
- LevelChunk$RebindableTickingBlockEntityWrapper lambda$updateBlockEntityTicker$11(BlockEntity,BlockEntityTicker,BlockPos,LevelChunk$RebindableTickingBlockEntityWrapper)
+ LevelChunk$RebindableTickingBlockEntityWrapper lambda$updateBlockEntityTicker$9(BlockEntity,BlockEntityTicker,BlockPos,LevelChunk$RebindableTickingBlockEntityWrapper)
+ LevelLightEngine getLightEngine()
+ LongSet lambda$addReferenceForFeature$6(StructureFeature)
- LongSet lambda$addReferenceForFeature$7(StructureFeature)
+ LongSet lambda$getReferencesForFeature$5(StructureFeature)
- LongSet lambda$getReferencesForFeature$6(StructureFeature)
+ String lambda$getBlockState$1(int,int,int)
- String lambda$getBlockState$2(int,int,int)
+ String lambda$getFluidState$2(int,int,int)
- String lambda$getFluidState$3(int,int,int)
- void addGameEventListener(BlockEntity)
- void lambda$registerAllBlockEntitiesAfterLevelLoad$10(BlockEntity)
- void removeGameEventListener(BlockEntity)
```

</details>



<details>
<summary>
net.minecraft.world.level.chunk.OldDataLayer
</summary>

```diff
+ boolean isValid()
+ void set(int,int,int,int)
+ void setAll(int)
```

</details>


















<details>
<summary>
net.minecraft.world.level.levelgen.NoiseSettings
</summary>

```diff
- DataResult guardY(NoiseSettings)
- int minY()
- NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlideSettings,NoiseSlideSettings,int,int,double,double,boolean,boolean,boolean,boolean)
- void <init>(int,int,NoiseSamplingSettings,NoiseSlideSettings,NoiseSlideSettings,int,int,double,double,boolean,boolean,boolean,boolean)
+ void <init>(int,NoiseSamplingSettings,NoiseSlideSettings,NoiseSlideSettings,int,int,double,double,boolean,boolean,boolean,boolean)
- void lambda$create$1(DataResult$PartialResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.WorldgenRandom
</summary>

```diff
+ int getCount()
+ int next(int)
```

</details>
</details>