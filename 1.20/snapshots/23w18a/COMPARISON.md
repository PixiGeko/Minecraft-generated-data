## Comparison with [23w17a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w17a)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">23w17a</th><th>23w18a</th></tr><tr><td>DataPack version</td><td><pre>14</pre></td><td><pre>15</pre></td></tr><tr><td>World version</td><td><pre>3452</pre></td><td><pre>3453</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741956</pre></td><td><pre>1073741957</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
loot_condition_type
</summary>

```diff
+ minecraft:all_of
- minecraft:alternative
+ minecraft:any_of
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/loot_condition_type.json
</summary>

```diff
+ minecraft:all_of
- minecraft:alternative
+ minecraft:any_of
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
+ advancements.adventure.read_power_from_chiseled_bookshelf.description: Read the power signal of a Chiseled Bookshelf using a Comparator
+ advancements.adventure.read_power_from_chiseled_bookshelf.title: The Power of Books
+ telemetry.event.advancement_made.description: Understanding the context behind receiving an advancement can help us better understand and improve the progression of the game
+ telemetry.event.advancement_made.title: Advancement Made
+ telemetry.event.game_load_times.description: This event can help us figure out where improvements to startup performance are needed by measuring execution times of the startup phases
+ telemetry.event.game_load_times.title: Game Load Times
+ telemetry.property.advancement_game_time.title: Game Time (Ticks)
+ telemetry.property.advancement_id.title: Advancement ID
+ telemetry.property.launcher_name.title: Launcher Name
+ telemetry.property.load_time_bootstrap_ms.title: Bootstrap Time (Milliseconds)
+ telemetry.property.load_time_loading_overlay_ms.title: Time in Loading Screen (Milliseconds)
+ telemetry.property.load_time_pre_window_ms.title: Time Before Window Opens (Milliseconds)
+ telemetry.property.load_time_total_time_ms.title: Total Load Time (Milliseconds)
+ telemetry.property.realms_map_content.title: Realms Map Content (Minigame Name)
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>23w17a</th><th>23w18a</th></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.craft_decorated_pot_using_only_sherds.title</div></th><td>Careful restoration</td><td>Careful Restoration</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.trim_with_any_armor_pattern.title</div></th><td>Crafting a new look</td><td>Crafting a New Look</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.salvage_sherd.title</div></th><td>Respecting the remnants</td><td>Respecting the Remnants</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.trim_with_all_exclusive_armor_patterns.title</div></th><td>Smithing with style</td><td>Smithing with Style</td></tr>
<tr><th align="left"><div style="width:290px">advancements.husbandry.feed_snifflet.title</div></th><td>Little sniffs</td><td>Little Sniffs</td></tr>
<tr><th align="left"><div style="width:290px">advancements.husbandry.obtain_sniffer_egg.title</div></th><td>Smells interesting</td><td>Smells Interesting</td></tr>
<tr><th align="left"><div style="width:290px">advancements.husbandry.plant_any_sniffer_seed.title</div></th><td>Planting the past</td><td>Planting the Past</td></tr>
</table>
<br/>
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
+ minecraft/advancements/adventure/read_power_of_chiseled_bookshelf.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/shaders/core/block.fsh
- minecraft/shaders/core/block.json
- minecraft/shaders/core/block.vsh
- minecraft/shaders/core/new_entity.fsh
- minecraft/shaders/core/new_entity.json
- minecraft/shaders/core/new_entity.vsh
+ minecraft/shaders/core/rendertype_gui_ghost_recipe_overlay.fsh
+ minecraft/shaders/core/rendertype_gui_ghost_recipe_overlay.json
+ minecraft/shaders/core/rendertype_gui_ghost_recipe_overlay.vsh
+ minecraft/shaders/core/rendertype_gui_overlay.fsh
+ minecraft/shaders/core/rendertype_gui_overlay.json
+ minecraft/shaders/core/rendertype_gui_overlay.vsh
+ minecraft/shaders/core/rendertype_gui_text_highlight.fsh
+ minecraft/shaders/core/rendertype_gui_text_highlight.json
+ minecraft/shaders/core/rendertype_gui_text_highlight.vsh
+ minecraft/shaders/core/rendertype_gui.fsh
+ minecraft/shaders/core/rendertype_gui.json
+ minecraft/shaders/core/rendertype_gui.vsh
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
- XXX.advancements.critereon.ContextAwarePredicate
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DeserializationContext
- XXX.advancements.critereon.DistancePredicate
+ XXX.advancements.critereon.DistanceTrigger
- XXX.advancements.critereon.DistanceTrigger$TriggerInstance
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
+ XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.ItemInteractWithBlockTrigger$TriggerInstance
- XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ XXX.advancements.critereon.PlacedBlockTrigger
+ XXX.level.lighting.LightEngine$1
- XXX.level.lighting.LightEngine$QueueEntry
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightEngine$1
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.MapColor
- XXX.level.material.MapColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
- XXX.level.redstone.CollectingNeighborUpdater
+ XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelVersion
- XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$Event
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.DynamicLoot$Serializer
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EmptyLootItem$Serializer
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootItem$Serializer
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootPoolSingletonContainer$Serializer
- XXX.loot.entries.LootTableReference
+ XXX.loot.entries.LootTableReference$Serializer
+ XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
- XXX.loot.entries.TagEntry$Serializer
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$Serializer
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.ApplyExplosionDecay$Serializer
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyBlockState$Serializer
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.CopyNameFunction$Serializer
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Serializer
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionReference
+ XXX.loot.functions.FunctionReference$Serializer
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.LimitCount$Serializer
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
- XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetBannerPatternFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetEnchantmentsFunction$Serializer
+ XXX.loot.functions.SetInstrumentFunction
- XXX.loot.functions.SetInstrumentFunction$Serializer
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemDamageFunction$Serializer
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$Serializer
- XXX.loot.functions.SetPotionFunction
+ XXX.loot.functions.SetPotionFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$Serializer
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.SmeltItemFunction$Serializer
+ XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
- XXX.loot.predicates.AllOfCondition$Builder
+ XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$Serializer
- XXX.loot.predicates.AnyOfCondition
- XXX.loot.predicates.AnyOfCondition$Serializer
- XXX.loot.predicates.CompositeLootItemCondition$Builder
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ XXX.loot.predicates.MatchTool
- XXX.loot.predicates.MatchTool$Serializer
+ XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.ValueCheckCondition$Serializer
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.loot.predicates.WeatherCheck$Serializer
+ XXX.minecraft.world.package-info
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
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$1
- XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
- XXX.providers.nbt.ContextNbtProvider$InlineSerializer
+ XXX.providers.nbt.ContextNbtProvider$Serializer
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
- XXX.providers.nbt.StorageNbtProvider$Serializer
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.BinomialDistributionGenerator$Serializer
- XXX.providers.number.ConstantValue
+ XXX.providers.number.ConstantValue$InlineSerializer
- XXX.providers.number.ConstantValue$Serializer
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.ScoreboardValue$Serializer
- XXX.providers.number.UniformGenerator
+ XXX.providers.number.UniformGenerator$Serializer
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
+ XXX.providers.score.ContextScoreboardNameProvider$Serializer
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider$Serializer
- XXX.providers.score.LootScoreProviderType
+ XXX.providers.score.package-info
+ XXX.providers.score.ScoreboardNameProvider
- XXX.providers.score.ScoreboardNameProviders
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.Deserializers
+ XXX.storage.loot.GsonAdapterFactory
- XXX.storage.loot.GsonAdapterFactory$Builder
+ XXX.storage.loot.GsonAdapterFactory$InlineSerializer
- XXX.storage.loot.GsonAdapterFactory$JsonAdapter
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.IntRange$Serializer
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$DynamicDrop
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$EntityTarget$Serializer
- XXX.storage.loot.LootContext$VisitedEntry
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootDataId
+ XXX.storage.loot.LootDataManager
- XXX.storage.loot.LootDataManager$1
+ XXX.storage.loot.LootDataManager$CompositePredicate
- XXX.storage.loot.LootDataManager$FunctionSequence
+ XXX.storage.loot.LootDataResolver
- XXX.storage.loot.LootDataType
+ XXX.storage.loot.LootDataType$Validator
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
- XXX.storage.loot.package-info
- XXX.storage.loot.Serializer
+ XXX.storage.loot.SerializerType
- XXX.storage.loot.ValidationContext
- XXX.world.level.package-info
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
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
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.LevelChunkTicks
- XXX.world.ticks.LevelTickAccess
+ XXX.world.ticks.LevelTicks
- XXX.world.ticks.LevelTicks$PosAndContainerConsumer
+ XXX.world.ticks.package-info
+ XXX.world.ticks.ProtoChunkTicks
- XXX.world.ticks.SavedTick
+ XXX.world.ticks.SavedTick$1
- XXX.world.ticks.ScheduledTick
+ XXX.world.ticks.ScheduledTick$1
- XXX.world.ticks.SerializableTickContainer
+ XXX.world.ticks.TickAccess
- XXX.world.ticks.TickContainerAccess
+ XXX.world.ticks.TickPriority
- XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +2P
```
```
XXX.minecraft.advancements.Advancement$Builder +3M -2M | +1P
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger +2M -2M
```
```
XXX.advancements.critereon.BredAnimalsTrigger +2M -2M
```
```
XXX.advancements.critereon.BrewedPotionTrigger +2M -2M
```
```
XXX.advancements.critereon.ChangeDimensionTrigger +2M -2M
```
```
XXX.advancements.critereon.ChanneledLightningTrigger +2M -2M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger +2M -2M
```
```
XXX.advancements.critereon.ConsumeItemTrigger +2M -2M
```
```
XXX.advancements.critereon.FilledBucketTrigger +2M -2M
```
```
XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.KilledTrigger$TriggerInstance +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.LevitationTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.LightningStrikeTrigger +2M -2M
```
```
XXX.advancements.critereon.LootTableTrigger +2M -2M
```
```
XXX.advancements.critereon.PickedUpItemTrigger +2M -2M
```
```
XXX.advancements.critereon.PlayerHurtEntityTrigger +2M -2M
```
```
XXX.advancements.critereon.PlayerInteractTrigger +2M -2M
```
```
XXX.advancements.critereon.PlayerTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.ShotCrossbowTrigger +2M -2M
```
```
XXX.advancements.critereon.SimpleCriterionTrigger +1P -1P
```
```
XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.StartRidingTrigger +2M -2M
```
```
XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.TameAnimalTrigger +2M -2M
```
```
XXX.advancements.critereon.TargetBlockTrigger +2M -2M
```
```
XXX.advancements.critereon.TradeTrigger +2M -2M
```
```
XXX.advancements.critereon.UsedEnderEyeTrigger +2M -2M
```
```
XXX.advancements.critereon.UsedTotemTrigger +2M -2M
```
```
XXX.advancements.critereon.UsingItemTrigger +2M -2M
```
```
XXX.advancements.packs.VanillaAdventureAdvancements +8M -2M
```
```
XXX.advancements.packs.VanillaNetherAdvancements +1P -1P
```
```
XXX.network.syncher.SynchedEntityData +1M
```
```
XXX.minecraft.server.Bootstrap +1P
```
```
XXX.minecraft.util.ExtraCodecs +1M
```
```
XXX.world.entity.Entity +16M -13M | +1P
```
```
XXX.world.entity.LivingEntity +1M -1M
```
```
XXX.animal.sniffer.Sniffer +1M | +2P
```
```
XXX.world.level.BlockCollisions +1M -3M | +1P
```
```
XXX.world.level.CollisionGetter +8M -4M
```
```
XXX.world.level.SpawnData$CustomSpawnRules +1M
```
```
XXX.structure.placement.RandomSpreadStructurePlacement +2M -2M
```

</details>
<details>
<summary>
net.minecraft.advancements.Advancement$Builder
</summary>

```diff
- Advancement$Builder recipeAdvancement()
+ void <init>()
- void <init>(boolean)
- void <init>(ResourceLocation,DisplayInfo,AdvancementRewards,Map,String[][],boolean)
+ void <init>(ResourceLocation,DisplayInfo,AdvancementRewards,Map,String[][])
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- BeeNestDestroyedTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ BeeNestDestroyedTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BredAnimalsTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- BredAnimalsTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ BredAnimalsTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BrewedPotionTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- BrewedPotionTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ BrewedPotionTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ChangeDimensionTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ChangeDimensionTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChanneledLightningTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ChanneledLightningTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ChanneledLightningTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ConstructBeaconTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ConstructBeaconTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConsumeItemTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ConsumeItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ConsumeItemTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.FilledBucketTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- FilledBucketTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ FilledBucketTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ItemPredicate,ContextAwarePredicate,ItemPredicate)
+ void <init>(EntityPredicate$Composite,ItemPredicate,EntityPredicate$Composite,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,MinMaxBounds$Ints,MinMaxBounds$Ints,MinMaxBounds$Ints,ItemPredicate[])
+ void <init>(EntityPredicate$Composite,MinMaxBounds$Ints,MinMaxBounds$Ints,MinMaxBounds$Ints,ItemPredicate[])
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
</summary>

```diff
- ItemDurabilityTrigger$TriggerInstance changedDurability(ContextAwarePredicate,ItemPredicate,MinMaxBounds$Ints)
+ ItemDurabilityTrigger$TriggerInstance changedDurability(EntityPredicate$Composite,ItemPredicate,MinMaxBounds$Ints)
- void <init>(ContextAwarePredicate,ItemPredicate,MinMaxBounds$Ints,MinMaxBounds$Ints)
+ void <init>(EntityPredicate$Composite,ItemPredicate,MinMaxBounds$Ints,MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ContextAwarePredicate[],MinMaxBounds$Ints)
+ void <init>(EntityPredicate$Composite,EntityPredicate$Composite[],MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
</summary>

```diff
- void <init>(ResourceLocation,ContextAwarePredicate,ContextAwarePredicate,DamageSourcePredicate)
+ void <init>(ResourceLocation,EntityPredicate$Composite,EntityPredicate$Composite,DamageSourcePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LevitationTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,DistancePredicate,MinMaxBounds$Ints)
+ void <init>(EntityPredicate$Composite,DistancePredicate,MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LightningStrikeTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- LightningStrikeTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ LightningStrikeTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LootTableTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- LootTableTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ LootTableTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PickedUpItemTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- PickedUpItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ PickedUpItemTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- PlayerHurtEntityTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ PlayerHurtEntityTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerInteractTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- PlayerInteractTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ PlayerInteractTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
</summary>

```diff
- void <init>(ResourceLocation,ContextAwarePredicate)
+ void <init>(ResourceLocation,EntityPredicate$Composite)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ResourceLocation,List)
+ void <init>(EntityPredicate$Composite,ResourceLocation,List)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ResourceLocation)
+ void <init>(EntityPredicate$Composite,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ShotCrossbowTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ShotCrossbowTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ShotCrossbowTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,Block,StatePropertiesPredicate)
+ void <init>(EntityPredicate$Composite,Block,StatePropertiesPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.StartRidingTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- StartRidingTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ StartRidingTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ContextAwarePredicate)
+ void <init>(EntityPredicate$Composite,EntityPredicate$Composite)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TameAnimalTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- TameAnimalTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ TameAnimalTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TargetBlockTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- TargetBlockTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ TargetBlockTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TradeTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- TradeTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ TradeTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsedEnderEyeTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- UsedEnderEyeTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ UsedEnderEyeTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsedTotemTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- UsedTotemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ UsedTotemTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsingItemTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- UsingItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ UsingItemTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
</summary>

```diff
- AllOfCondition$Builder lambda$placedComparatorReadingBlock$2(Block,Direction)
- CriterionTriggerInstance placedBlockReadByComparator(Block)
- CriterionTriggerInstance placedComparatorReadingBlock(Block)
- LootItemCondition$Builder lambda$placedBlockReadByComparator$0(Direction)
- LootItemCondition$Builder[] lambda$placedBlockReadByComparator$1(int)
- LootItemCondition$Builder[] lambda$placedComparatorReadingBlock$3(int)
+ String[] lambda$respectingTheRemnantsCriterions$1(int)
- String[] lambda$respectingTheRemnantsCriterions$5(int)
+ void lambda$smithingWithStyle$0(Map,Advancement$Builder,Item)
- void lambda$smithingWithStyle$4(Map,Advancement$Builder,Item)
```

</details>
<details>
<summary>
net.minecraft.network.syncher.SynchedEntityData
</summary>

```diff
- boolean hasItem(EntityDataAccessor)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
- MapCodec validate(MapCodec,Function)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- BlockState lambda$checkFallDamage$1(BlockPos)
- boolean isStateClimbable(BlockState)
+ boolean lambda$findDimensionEntryPoint$5(BlockState,BlockPos)
- boolean lambda$findDimensionEntryPoint$6(BlockState,BlockPos)
+ boolean lambda$hasExactlyOnePlayerPassenger$15(Entity)
- boolean lambda$hasExactlyOnePlayerPassenger$16(Entity)
+ boolean lambda$isInWall$1(AABB,BlockPos)
- boolean lambda$isInWall$2(AABB,BlockPos)
+ boolean lambda$removePassenger$4(Entity,Entity)
- boolean lambda$removePassenger$5(Entity,Entity)
+ boolean lambda$startRiding$2(Entity)
- boolean lambda$startRiding$3(Entity)
- boolean vibrationAndSoundEffectsFromBlock(BlockPos,BlockState,boolean,boolean,Vec3)
+ boolean walkingOnBlock(boolean,Vec3)
+ Iterator lambda$getIndirectPassengers$14()
- Iterator lambda$getIndirectPassengers$15()
+ PortalInfo lambda$findDimensionEntryPoint$6(ServerLevel,BlockUtil$FoundRectangle)
- PortalInfo lambda$findDimensionEntryPoint$7(ServerLevel,BlockUtil$FoundRectangle)
- String lambda$fillCrashReportCategory$11()
+ String lambda$fillCrashReportCategory$7()
+ Style lambda$getDisplayName$11(Style)
- Style lambda$getDisplayName$12(Style)
- void checkSupportingBlock(boolean)
+ void lambda$refreshDimensions$13(EntityDimensions,Vec3)
- void lambda$refreshDimensions$14(EntityDimensions,Vec3)
+ void lambda$startRiding$3(Entity)
- void lambda$startRiding$4(Entity)
+ void lambda$teleportPassengers$12(Entity)
- void lambda$teleportPassengers$13(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ double getJumpBoostPower()
- float getJumpBoostPower()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.sniffer.Sniffer
</summary>

```diff
- EntityDimensions getDimensions(Pose)
```

</details>
<details>
<summary>
net.minecraft.world.level.BlockCollisions
</summary>

```diff
- void <init>(CollisionGetter,Entity,AABB,boolean,BiFunction)
+ void <init>(CollisionGetter,Entity,AABB,boolean)
+ void <init>(CollisionGetter,Entity,AABB)
+ VoxelShape computeNext()
```

</details>
<details>
<summary>
net.minecraft.world.level.CollisionGetter
</summary>

```diff
+ AABB lambda$findFreePosition$3(double,double,double,AABB)
- AABB lambda$findFreePosition$6(double,double,double,AABB)
- BlockPos lambda$findSupportingBlock$3(BlockPos$MutableBlockPos,VoxelShape)
+ boolean lambda$findFreePosition$1(VoxelShape)
- boolean lambda$findFreePosition$4(VoxelShape)
+ Iterator lambda$getBlockCollisions$0(Entity,AABB)
- Iterator lambda$getBlockCollisions$1(Entity,AABB)
- Optional findSupportingBlock(Entity,AABB)
+ Stream lambda$findFreePosition$2(VoxelShape)
- Stream lambda$findFreePosition$5(VoxelShape)
- VoxelShape lambda$collidesWithSuffocatingBlock$2(BlockPos$MutableBlockPos,VoxelShape)
- VoxelShape lambda$getBlockCollisions$0(BlockPos$MutableBlockPos,VoxelShape)
```

</details>
<details>
<summary>
net.minecraft.world.level.SpawnData$CustomSpawnRules
</summary>

```diff
- MapCodec lightLimit(String)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
</summary>

```diff
+ DataResult lambda$static$2(RandomSpreadStructurePlacement)
- DataResult validate(RandomSpreadStructurePlacement)
+ String lambda$static$1()
- String lambda$validate$1()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.advancements.critereon.ContextAwarePredicate
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DeserializationContext
- XXX.advancements.critereon.DistancePredicate
+ XXX.advancements.critereon.DistanceTrigger
- XXX.advancements.critereon.DistanceTrigger$TriggerInstance
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
+ XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.ItemInteractWithBlockTrigger$TriggerInstance
- XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ XXX.advancements.critereon.PlacedBlockTrigger
+ XXX.blaze3d.font.package-info
- XXX.blaze3d.font.TrueTypeGlyphProvider
+ XXX.blaze3d.font.TrueTypeGlyphProvider$Glyph
- XXX.blaze3d.font.TrueTypeGlyphProvider$Glyph$1
+ XXX.blaze3d.pipeline.MainTarget
- XXX.blaze3d.pipeline.MainTarget$AttachmentState
+ XXX.blaze3d.pipeline.MainTarget$Dimension
- XXX.blaze3d.pipeline.package-info
- XXX.blaze3d.pipeline.RenderCall
+ XXX.blaze3d.pipeline.RenderPipeline
- XXX.blaze3d.pipeline.RenderTarget
+ XXX.blaze3d.pipeline.TextureTarget
+ XXX.blaze3d.platform.ClipboardManager
- XXX.blaze3d.platform.DebugMemoryUntracker
+ XXX.blaze3d.platform.DisplayData
+ XXX.blaze3d.platform.GlConst
- XXX.blaze3d.platform.GlDebug
+ XXX.blaze3d.platform.GlDebug$LogEntry
- XXX.blaze3d.platform.GlStateManager
+ XXX.blaze3d.platform.GlStateManager$BlendState
- XXX.blaze3d.platform.GlStateManager$BooleanState
+ XXX.blaze3d.platform.GlStateManager$ColorLogicState
- XXX.blaze3d.platform.GlStateManager$ColorMask
+ XXX.blaze3d.platform.GlStateManager$CullState
- XXX.blaze3d.platform.GlStateManager$DepthState
+ XXX.blaze3d.platform.GlStateManager$DestFactor
- XXX.blaze3d.platform.GlStateManager$LogicOp
+ XXX.blaze3d.platform.GlStateManager$PolygonOffsetState
- XXX.blaze3d.platform.GlStateManager$ScissorState
+ XXX.blaze3d.platform.GlStateManager$SourceFactor
- XXX.blaze3d.platform.GlStateManager$StencilFunc
+ XXX.blaze3d.platform.GlStateManager$StencilState
- XXX.blaze3d.platform.GlStateManager$TextureState
+ XXX.blaze3d.platform.GlStateManager$Viewport
- XXX.blaze3d.platform.GlUtil
- XXX.blaze3d.platform.GLX
+ XXX.blaze3d.platform.IconSet
- XXX.blaze3d.platform.InputConstants
+ XXX.blaze3d.platform.InputConstants$Key
- XXX.blaze3d.platform.InputConstants$Type
+ XXX.blaze3d.platform.Lighting
- XXX.blaze3d.platform.MacosUtil
+ XXX.blaze3d.platform.MemoryTracker
- XXX.blaze3d.platform.Monitor
+ XXX.blaze3d.platform.MonitorCreator
- XXX.blaze3d.platform.NativeImage
+ XXX.blaze3d.platform.NativeImage$Format
- XXX.blaze3d.platform.NativeImage$InternalGlFormat
+ XXX.blaze3d.platform.NativeImage$WriteCallback
- XXX.blaze3d.platform.package-info
- XXX.blaze3d.platform.ScreenManager
+ XXX.blaze3d.platform.TextureUtil
- XXX.blaze3d.platform.VideoMode
+ XXX.blaze3d.platform.Window
- XXX.blaze3d.platform.Window$WindowInitFailed
+ XXX.blaze3d.platform.WindowEventHandler
+ XXX.blaze3d.preprocessor.GlslPreprocessor
- XXX.blaze3d.preprocessor.GlslPreprocessor$Context
+ XXX.blaze3d.preprocessor.package-info
- XXX.blaze3d.shaders.AbstractUniform
+ XXX.blaze3d.shaders.BlendMode
- XXX.blaze3d.shaders.Effect
+ XXX.blaze3d.shaders.EffectProgram
- XXX.blaze3d.shaders.EffectProgram$1
+ XXX.blaze3d.shaders.FogShape
+ XXX.blaze3d.shaders.package-info
- XXX.blaze3d.shaders.Program
+ XXX.blaze3d.shaders.Program$Type
- XXX.blaze3d.shaders.ProgramManager
+ XXX.blaze3d.shaders.Shader
- XXX.blaze3d.shaders.Uniform
+ XXX.blaze3d.systems.package-info
- XXX.blaze3d.systems.RenderSystem
+ XXX.blaze3d.systems.RenderSystem$1
- XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
+ XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
- XXX.blaze3d.systems.TimerQuery
+ XXX.blaze3d.systems.TimerQuery$FrameProfile
- XXX.blaze3d.systems.TimerQuery$TimerQueryLazyLoader
- XXX.blaze3d.vertex.BufferBuilder
+ XXX.blaze3d.vertex.BufferBuilder$1
- XXX.blaze3d.vertex.BufferBuilder$DrawState
+ XXX.blaze3d.vertex.BufferBuilder$RenderedBuffer
- XXX.blaze3d.vertex.BufferBuilder$SortState
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.BufferVertexConsumer
- XXX.blaze3d.vertex.DefaultedVertexConsumer
+ XXX.blaze3d.vertex.DefaultVertexFormat
+ XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$Pose
+ XXX.blaze3d.vertex.SheetedDecalTextureGenerator
- XXX.blaze3d.vertex.Tesselator
+ XXX.blaze3d.vertex.VertexBuffer
- XXX.blaze3d.vertex.VertexBuffer$Usage
- XXX.block.model.BakedQuad
+ XXX.block.model.BlockElement
- XXX.block.model.BlockElement$1
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementRotation
+ XXX.block.model.BlockFaceUV
- XXX.block.model.BlockFaceUV$Deserializer
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModel$GuiLight
- XXX.block.model.BlockModel$LoopException
+ XXX.block.model.BlockModelDefinition
- XXX.block.model.BlockModelDefinition$Context
+ XXX.block.model.BlockModelDefinition$Deserializer
- XXX.block.model.BlockModelDefinition$MissingVariantException
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$1
+ XXX.block.model.ItemModelGenerator$Span
- XXX.block.model.ItemModelGenerator$SpanFacing
+ XXX.block.model.ItemOverride
- XXX.block.model.ItemOverride$Deserializer
+ XXX.block.model.ItemOverride$Predicate
- XXX.block.model.ItemOverrides
+ XXX.block.model.ItemOverrides$BakedOverride
- XXX.block.model.ItemOverrides$PropertyMatcher
+ XXX.block.model.ItemTransform
- XXX.block.model.ItemTransform$Deserializer
+ XXX.block.model.ItemTransforms
- XXX.block.model.ItemTransforms$1
+ XXX.block.model.ItemTransforms$Deserializer
- XXX.block.model.MultiVariant
+ XXX.block.model.MultiVariant$Deserializer
+ XXX.block.model.package-info
- XXX.block.model.Variant
+ XXX.block.model.Variant$Deserializer
- XXX.client.renderer.RenderStateShard$CullStateShard
+ XXX.client.renderer.RenderStateShard$DepthTestStateShard
- XXX.client.renderer.RenderStateShard$EmptyTextureStateShard
+ XXX.client.renderer.RenderStateShard$LayeringStateShard
- XXX.client.renderer.RenderStateShard$LightmapStateShard
+ XXX.client.renderer.RenderStateShard$LineStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
- XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ XXX.client.renderer.RenderStateShard$OutputStateShard
- XXX.client.renderer.RenderStateShard$OverlayStateShard
+ XXX.client.renderer.RenderStateShard$ShaderStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
+ XXX.client.renderer.RenderStateShard$WriteMaskStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$CompositeRenderType
- XXX.client.renderer.RenderType$CompositeState
+ XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- XXX.client.renderer.RenderType$OutlineProperty
+ XXX.client.renderer.RunningTrimmedMean
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.ShaderInstance
- XXX.client.renderer.ShaderInstance$1
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$Effect
- XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.SpecialGlyphs
- XXX.font.glyphs.SpecialGlyphs$1
+ XXX.font.glyphs.SpecialGlyphs$PixelProvider
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$Builder
- XXX.font.providers.BitmapProvider$Glyph
+ XXX.font.providers.BitmapProvider$Glyph$1
+ XXX.font.providers.GlyphProviderBuilder$Loader
+ XXX.font.providers.GlyphProviderBuilderType
- XXX.font.providers.GlyphProviderDefinition
- XXX.font.providers.GlyphProviderDefinition$Reference
- XXX.font.providers.ProviderReferenceDefinition
+ XXX.font.providers.TrueTypeGlyphProviderBuilder
- XXX.font.providers.TrueTypeGlyphProviderDefinition$Shift
+ XXX.font.providers.UnihexProvider$Builder
- XXX.font.providers.UnihexProvider$ByteContents
- XXX.gui.font.FontManager$FontDefinitionFile
+ XXX.gui.font.FontManager$Preparation
- XXX.gui.font.FontManager$UnresolvedBuilderBundle
+ XXX.gui.font.FontSet
- XXX.gui.font.FontSet$GlyphInfoFilter
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$Node
+ XXX.gui.font.GlyphRenderTypes
- XXX.gui.font.GlyphRenderTypes$1
+ XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$1
+ XXX.gui.font.TextFieldHelper$CursorStep
+ XXX.level.lighting.LightEngine$QueueEntry
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightEngine$1
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.Fluid
+ XXX.level.material.Fluids
- XXX.level.material.FluidState
- XXX.level.material.FogType
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.MapColor
+ XXX.level.material.MapColor$Brightness
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.AmphibiousNodeEvaluator
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalInfo
+ XXX.level.portal.PortalShape
+ XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ XXX.level.redstone.InstantNeighborUpdater
- XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DataVersion
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelCandidates
+ XXX.level.storage.LevelStorageSource$LevelDirectory
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$Event
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$Serializer
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$Serializer
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionReference
- XXX.loot.functions.FunctionReference$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBannerPatternFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
- XXX.loot.functions.SetInstrumentFunction
+ XXX.loot.functions.SetInstrumentFunction$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetPotionFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AllOfCondition
- XXX.loot.predicates.AllOfCondition$Serializer
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AnyOfCondition$Builder
- XXX.loot.predicates.CompositeLootItemCondition
- XXX.loot.predicates.CompositeLootItemCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.ValueCheckCondition$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
- XXX.minecraft.world.package-info
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
- XXX.mojang.blaze3d.package-info
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
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.ContextNbtProvider$InlineSerializer
- XXX.providers.nbt.ContextNbtProvider$Serializer
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.BinomialDistributionGenerator$Serializer
+ XXX.providers.number.ConstantValue
- XXX.providers.number.ConstantValue$InlineSerializer
+ XXX.providers.number.ConstantValue$Serializer
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.ScoreboardValue$Serializer
+ XXX.providers.number.UniformGenerator
- XXX.providers.number.UniformGenerator$Serializer
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
- XXX.providers.score.ContextScoreboardNameProvider$Serializer
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider$Serializer
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
- XXX.renderer.block.BlockModelShaper
+ XXX.renderer.block.BlockRenderDispatcher
- XXX.renderer.block.BlockRenderDispatcher$1
+ XXX.renderer.block.LiquidBlockRenderer
- XXX.renderer.block.LiquidBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer
- XXX.renderer.block.ModelBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
- XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- XXX.renderer.block.ModelBlockRenderer$Cache
+ XXX.renderer.block.ModelBlockRenderer$Cache$1
- XXX.renderer.block.ModelBlockRenderer$Cache$2
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
- XXX.renderer.block.package-info
+ XXX.renderer.blockentity.BannerRenderer
- XXX.renderer.blockentity.BeaconRenderer
+ XXX.renderer.blockentity.BedRenderer
- XXX.renderer.blockentity.BellRenderer
+ XXX.renderer.blockentity.BlockEntityRenderDispatcher
- XXX.renderer.blockentity.BlockEntityRenderer
+ XXX.renderer.blockentity.BlockEntityRendererProvider
- XXX.renderer.blockentity.BlockEntityRendererProvider$Context
+ XXX.renderer.blockentity.BlockEntityRenderers
- XXX.renderer.blockentity.BrightnessCombiner
+ XXX.renderer.blockentity.BrushableBlockRenderer
- XXX.renderer.blockentity.BrushableBlockRenderer$1
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.DecoratedPotRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.HangingSignRenderer
+ XXX.renderer.blockentity.HangingSignRenderer$HangingSignModel
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.package-info
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.SignRenderer
- XXX.renderer.blockentity.SignRenderer$SignModel
+ XXX.renderer.blockentity.SkullBlockRenderer
- XXX.renderer.blockentity.SpawnerRenderer
+ XXX.renderer.blockentity.StructureBlockRenderer
- XXX.renderer.blockentity.StructureBlockRenderer$1
+ XXX.renderer.blockentity.TheEndGatewayRenderer
- XXX.renderer.blockentity.TheEndPortalRenderer
- XXX.renderer.chunk.ChunkRenderDispatcher
+ XXX.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
- XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
+ XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
- XXX.renderer.chunk.package-info
+ XXX.renderer.chunk.RenderChunk
- XXX.renderer.chunk.RenderChunkRegion
+ XXX.renderer.chunk.RenderRegionCache
- XXX.renderer.chunk.RenderRegionCache$ChunkInfo
+ XXX.renderer.chunk.VisGraph
- XXX.renderer.chunk.VisGraph$1
+ XXX.renderer.chunk.VisibilitySet
+ XXX.renderer.culling.Frustum
- XXX.renderer.culling.package-info
+ XXX.renderer.debug.BeeDebugRenderer
- XXX.renderer.debug.BeeDebugRenderer$BeeInfo
+ XXX.renderer.debug.BeeDebugRenderer$HiveInfo
- XXX.renderer.debug.BrainDebugRenderer
+ XXX.renderer.debug.BrainDebugRenderer$BrainDump
- XXX.renderer.debug.BrainDebugRenderer$PoiInfo
+ XXX.renderer.debug.ChunkBorderRenderer
- XXX.renderer.debug.ChunkDebugRenderer
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.GameEventListenerRenderer
- XXX.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
- XXX.renderer.debug.GameTestDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer$Marker
- XXX.renderer.debug.GoalSelectorDebugRenderer
+ XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- XXX.renderer.debug.HeightMapRenderer
+ XXX.renderer.debug.HeightMapRenderer$1
- XXX.renderer.debug.LightDebugRenderer
+ XXX.renderer.debug.LightSectionDebugRenderer
- XXX.renderer.debug.LightSectionDebugRenderer$1
+ XXX.renderer.debug.LightSectionDebugRenderer$SectionData
- XXX.renderer.debug.NeighborsUpdateRenderer
+ XXX.renderer.debug.PathfindingRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$Builder
- XXX.storage.loot.GsonAdapterFactory$InlineSerializer
+ XXX.storage.loot.GsonAdapterFactory$JsonAdapter
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.IntRange$Serializer
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$DynamicDrop
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootDataId
- XXX.storage.loot.LootDataManager
+ XXX.storage.loot.LootDataManager$1
- XXX.storage.loot.LootDataManager$CompositePredicate
+ XXX.storage.loot.LootDataManager$FunctionSequence
- XXX.storage.loot.LootDataResolver
+ XXX.storage.loot.LootDataType
- XXX.storage.loot.LootDataType$Validator
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootPool$Serializer
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.LootTable$Serializer
+ XXX.storage.loot.package-info
+ XXX.storage.loot.Serializer
- XXX.storage.loot.SerializerType
+ XXX.storage.loot.ValidationContext
- XXX.telemetry.events.GameLoadTimesEvent
+ XXX.world.level.package-info
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
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
- XXX.world.ticks.BlackholeTickAccess
+ XXX.world.ticks.BlackholeTickAccess$1
- XXX.world.ticks.BlackholeTickAccess$2
+ XXX.world.ticks.ContainerSingleItem
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.font.SpaceProvider +3M -6M
```
```
net.minecraft.SharedConstants +2P
```
```
XXX.minecraft.advancements.Advancement$Builder +3M -2M | +1P
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger +2M -2M
```
```
XXX.advancements.critereon.BredAnimalsTrigger +2M -2M
```
```
XXX.advancements.critereon.BrewedPotionTrigger +2M -2M
```
```
XXX.advancements.critereon.ChangeDimensionTrigger +2M -2M
```
```
XXX.advancements.critereon.ChanneledLightningTrigger +2M -2M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger +2M -2M
```
```
XXX.advancements.critereon.ConsumeItemTrigger +2M -2M
```
```
XXX.advancements.critereon.FilledBucketTrigger +2M -2M
```
```
XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.KilledTrigger$TriggerInstance +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.LevitationTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.LightningStrikeTrigger +2M -2M
```
```
XXX.advancements.critereon.LootTableTrigger +2M -2M
```
```
XXX.advancements.critereon.PickedUpItemTrigger +2M -2M
```
```
XXX.advancements.critereon.PlayerHurtEntityTrigger +2M -2M
```
```
XXX.advancements.critereon.PlayerInteractTrigger +2M -2M
```
```
XXX.advancements.critereon.PlayerTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.ShotCrossbowTrigger +2M -2M
```
```
XXX.advancements.critereon.SimpleCriterionTrigger +1P -1P
```
```
XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.StartRidingTrigger +2M -2M
```
```
XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.TameAnimalTrigger +2M -2M
```
```
XXX.advancements.critereon.TargetBlockTrigger +2M -2M
```
```
XXX.advancements.critereon.TradeTrigger +2M -2M
```
```
XXX.advancements.critereon.UsedEnderEyeTrigger +2M -2M
```
```
XXX.advancements.critereon.UsedTotemTrigger +2M -2M
```
```
XXX.advancements.critereon.UsingItemTrigger +2M -2M
```
```
XXX.gui.components.DebugScreenOverlay +10M -8M
```
```
XXX.gui.screens.LevelLoadingScreen +2M -1M
```
```
XXX.client.multiplayer.ClientAdvancements +1M -1M | +1P
```
```
XXX.client.multiplayer.ClientHandshakePacketListenerImpl +1M | +1P
```
```
XXX.client.renderer.GameRenderer +15M -11M | +4P -2P
```
```
XXX.client.renderer.LevelRenderer +3M -1M
```
```
XXX.client.telemetry.TelemetryEventType +2P
```
```
XXX.client.telemetry.WorldSessionTelemetryManager +3M -1M
```
```
XXX.advancements.packs.VanillaAdventureAdvancements +8M -2M
```
```
XXX.advancements.packs.VanillaNetherAdvancements +1P -1P
```
```
XXX.network.syncher.SynchedEntityData +1M
```
```
XXX.structure.structures.JigsawStructure +1M -2M
```
```
XXX.level.lighting.LightEngine -2M | +1P -1P
```

</details>
<details>
<summary>
com.mojang.blaze3d.font.SpaceProvider
</summary>

```diff
+ Either lambda$builderFromJson$3(GlyphProviderBuilder$Loader)
+ float lambda$new$0(float)
- float lambda$new$0(Float)
+ GlyphProvider lambda$builderFromJson$2(Int2FloatMap,ResourceManager)
+ GlyphProviderBuilder builderFromJson(JsonObject)
+ void <init>(Int2FloatMap)
- void <init>(Map)
+ void lambda$new$1(Int2FloatMap$Entry)
- void lambda$new$1(Integer,Float)
```

</details>
<details>
<summary>
net.minecraft.advancements.Advancement$Builder
</summary>

```diff
- Advancement$Builder recipeAdvancement()
+ void <init>()
- void <init>(boolean)
- void <init>(ResourceLocation,DisplayInfo,AdvancementRewards,Map,String[][],boolean)
+ void <init>(ResourceLocation,DisplayInfo,AdvancementRewards,Map,String[][])
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- BeeNestDestroyedTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ BeeNestDestroyedTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BredAnimalsTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- BredAnimalsTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ BredAnimalsTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BrewedPotionTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- BrewedPotionTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ BrewedPotionTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ChangeDimensionTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ChangeDimensionTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChanneledLightningTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ChanneledLightningTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ChanneledLightningTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ConstructBeaconTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ConstructBeaconTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConsumeItemTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ConsumeItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ConsumeItemTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.FilledBucketTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- FilledBucketTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ FilledBucketTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ItemPredicate,ContextAwarePredicate,ItemPredicate)
+ void <init>(EntityPredicate$Composite,ItemPredicate,EntityPredicate$Composite,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,MinMaxBounds$Ints,MinMaxBounds$Ints,MinMaxBounds$Ints,ItemPredicate[])
+ void <init>(EntityPredicate$Composite,MinMaxBounds$Ints,MinMaxBounds$Ints,MinMaxBounds$Ints,ItemPredicate[])
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
</summary>

```diff
- ItemDurabilityTrigger$TriggerInstance changedDurability(ContextAwarePredicate,ItemPredicate,MinMaxBounds$Ints)
+ ItemDurabilityTrigger$TriggerInstance changedDurability(EntityPredicate$Composite,ItemPredicate,MinMaxBounds$Ints)
- void <init>(ContextAwarePredicate,ItemPredicate,MinMaxBounds$Ints,MinMaxBounds$Ints)
+ void <init>(EntityPredicate$Composite,ItemPredicate,MinMaxBounds$Ints,MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ContextAwarePredicate[],MinMaxBounds$Ints)
+ void <init>(EntityPredicate$Composite,EntityPredicate$Composite[],MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
</summary>

```diff
- void <init>(ResourceLocation,ContextAwarePredicate,ContextAwarePredicate,DamageSourcePredicate)
+ void <init>(ResourceLocation,EntityPredicate$Composite,EntityPredicate$Composite,DamageSourcePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LevitationTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,DistancePredicate,MinMaxBounds$Ints)
+ void <init>(EntityPredicate$Composite,DistancePredicate,MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LightningStrikeTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- LightningStrikeTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ LightningStrikeTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LootTableTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- LootTableTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ LootTableTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PickedUpItemTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- PickedUpItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ PickedUpItemTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- PlayerHurtEntityTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ PlayerHurtEntityTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerInteractTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- PlayerInteractTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ PlayerInteractTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
</summary>

```diff
- void <init>(ResourceLocation,ContextAwarePredicate)
+ void <init>(ResourceLocation,EntityPredicate$Composite)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ResourceLocation,List)
+ void <init>(EntityPredicate$Composite,ResourceLocation,List)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ResourceLocation)
+ void <init>(EntityPredicate$Composite,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ShotCrossbowTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- ShotCrossbowTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ ShotCrossbowTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,Block,StatePropertiesPredicate)
+ void <init>(EntityPredicate$Composite,Block,StatePropertiesPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.StartRidingTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- StartRidingTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ StartRidingTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
</summary>

```diff
- void <init>(ContextAwarePredicate,ContextAwarePredicate)
+ void <init>(EntityPredicate$Composite,EntityPredicate$Composite)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TameAnimalTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- TameAnimalTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ TameAnimalTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TargetBlockTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- TargetBlockTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ TargetBlockTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TradeTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- TradeTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ TradeTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsedEnderEyeTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- UsedEnderEyeTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ UsedEnderEyeTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsedTotemTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- UsedTotemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ UsedTotemTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsingItemTrigger
</summary>

```diff
- AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ AbstractCriterionTriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
- UsingItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
+ UsingItemTrigger$TriggerInstance createInstance(JsonObject,EntityPredicate$Composite,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.DebugScreenOverlay
</summary>

```diff
+ LevelChunk lambda$getServerChunk$5(ChunkAccess)
- LevelChunk lambda$getServerChunk$6(ChunkAccess)
+ LevelChunk lambda$getServerChunk$6(ChunkHolder$ChunkLoadingFailure)
- LevelChunk lambda$getServerChunk$7(ChunkHolder$ChunkLoadingFailure)
+ LevelChunk lambda$getServerChunk$7(Either)
- LevelChunk lambda$getServerChunk$8(Either)
+ Optional lambda$getLevel$4(IntegratedServer)
- Optional lambda$getLevel$5(IntegratedServer)
+ String lambda$getGameInformation$1(Object2IntMap,MobCategory)
- String lambda$getGameInformation$2(Object2IntMap,MobCategory)
- String lambda$getSystemInformation$10(TagKey)
+ String lambda$getSystemInformation$8(TagKey)
+ String lambda$printBiome$2(ResourceKey)
+ String lambda$printBiome$3(Biome)
- String lambda$printBiome$3(ResourceKey)
- String lambda$printBiome$4(Biome)
- void lambda$render$1(GuiGraphics)
- void renderLines(GuiGraphics,List,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LevelLoadingScreen
</summary>

```diff
- void lambda$renderChunks$0(int,GuiGraphics,int,int,int,int,int,StoringChunkProgressListener,int,int,int)
+ void lambda$static$0(Object2IntOpenHashMap)
- void lambda$static$1(Object2IntOpenHashMap)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientAdvancements
</summary>

```diff
- void <init>(Minecraft,WorldSessionTelemetryManager)
+ void <init>(Minecraft)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
</summary>

```diff
- void setMinigameName(String)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.GameRenderer
</summary>

```diff
+ boolean lambda$pick$59(Entity)
- boolean lambda$pick$61(Entity)
+ ShaderInstance getBlockShader()
+ ShaderInstance getNewEntityShader()
- ShaderInstance getRendertypeGuiGhostRecipeOverlayShader()
- ShaderInstance getRendertypeGuiOverlayShader()
- ShaderInstance getRendertypeGuiShader()
- ShaderInstance getRendertypeGuiTextHighlightShader()
+ String lambda$render$60()
+ String lambda$render$61()
- String lambda$render$62()
+ String lambda$render$62(int,int)
+ String lambda$render$64()
- String lambda$render$64(int,int)
- String lambda$render$65()
- String lambda$render$66()
+ void lambda$reloadShaders$57(Pair)
- void lambda$reloadShaders$57(ShaderInstance)
+ void lambda$reloadShaders$58(Pair)
- void lambda$reloadShaders$58(ShaderInstance)
- void lambda$reloadShaders$59(Pair)
- void lambda$reloadShaders$60(Pair)
+ void lambda$takeAutoScreenshot$66(NativeImage,Path)
- void lambda$takeAutoScreenshot$68(NativeImage,Path)
+ void lambda$tryTakeScreenshotIfNeeded$65(Path)
- void lambda$tryTakeScreenshotIfNeeded$67(Path)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.LevelRenderer
</summary>

```diff
- Vec3 mixColor(float)
- Vec3 shiftHue(float,float,float,float)
- void renderVoxelShape(PoseStack,VertexConsumer,VoxelShape,double,double,double,float,float,float,float,boolean)
+ void renderVoxelShape(PoseStack,VertexConsumer,VoxelShape,double,double,double,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.telemetry.WorldSessionTelemetryManager
</summary>

```diff
- void <init>(TelemetryEventSender,boolean,Duration,String)
+ void <init>(TelemetryEventSender,boolean,Duration)
- void lambda$onAdvancementDone$1(ResourceLocation,long,TelemetryPropertyMap$Builder)
- void onAdvancementDone(Level,Advancement)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
</summary>

```diff
- AllOfCondition$Builder lambda$placedComparatorReadingBlock$2(Block,Direction)
- CriterionTriggerInstance placedBlockReadByComparator(Block)
- CriterionTriggerInstance placedComparatorReadingBlock(Block)
- LootItemCondition$Builder lambda$placedBlockReadByComparator$0(Direction)
- LootItemCondition$Builder[] lambda$placedBlockReadByComparator$1(int)
- LootItemCondition$Builder[] lambda$placedComparatorReadingBlock$3(int)
+ String[] lambda$respectingTheRemnantsCriterions$1(int)
- String[] lambda$respectingTheRemnantsCriterions$5(int)
+ void lambda$smithingWithStyle$0(Map,Advancement$Builder,Item)
- void lambda$smithingWithStyle$4(Map,Advancement$Builder,Item)
```

</details>
<details>
<summary>
net.minecraft.network.syncher.SynchedEntityData
</summary>

```diff
- boolean hasItem(EntityDataAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
</summary>

```diff
+ DataResult lambda$verifyRange$9(JigsawStructure)
- DataResult verifyRange(JigsawStructure)
+ Function verifyRange()
```

</details>
<details>
<summary>
net.minecraft.world.level.lighting.LightEngine
</summary>

```diff
+ boolean lambda$clearQueuedSectionBlocks$0(long,long)
+ void clearQueuedSectionBlocks(long)
```

</details>
</details>
<hr/>