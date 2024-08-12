## Comparison with [23w12a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w12a)

- [Version data](#version-data)
- [Tags](#tags)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">23w12a</th><th>23w13a</th></tr><tr><td>World version</td><td><code>3442</code></td><td><code>3443</code></td></tr><tr><td>Protocol version</td><td><code>1073741951</code></td><td><code>1073741952</code></td></tr></table>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:sniffer
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
- minecraft:sniffer
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:sniffer
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Changes
</summary>

```
item.minecraft.smithing_template.netherite_upgrade.base_slot_description: Add diamond armor, weapon, or tool
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
assets
</summary>

```diff
- minecraft/models/block/torchflower_crop_stage2.json
+ minecraft/textures/block/sniffer_egg_not_cracked_bottom.png
+ minecraft/textures/block/sniffer_egg_not_cracked_east.png
+ minecraft/textures/block/sniffer_egg_not_cracked_north.png
+ minecraft/textures/block/sniffer_egg_not_cracked_south.png
+ minecraft/textures/block/sniffer_egg_not_cracked_top.png
+ minecraft/textures/block/sniffer_egg_not_cracked_west.png
- minecraft/textures/block/sniffer_egg_not_cracked.png
+ minecraft/textures/block/sniffer_egg_slightly_cracked_bottom.png
+ minecraft/textures/block/sniffer_egg_slightly_cracked_east.png
+ minecraft/textures/block/sniffer_egg_slightly_cracked_north.png
+ minecraft/textures/block/sniffer_egg_slightly_cracked_south.png
+ minecraft/textures/block/sniffer_egg_slightly_cracked_top.png
+ minecraft/textures/block/sniffer_egg_slightly_cracked_west.png
- minecraft/textures/block/sniffer_egg_slightly_cracked.png
+ minecraft/textures/block/sniffer_egg_very_cracked_bottom.png
+ minecraft/textures/block/sniffer_egg_very_cracked_east.png
+ minecraft/textures/block/sniffer_egg_very_cracked_north.png
+ minecraft/textures/block/sniffer_egg_very_cracked_south.png
+ minecraft/textures/block/sniffer_egg_very_cracked_top.png
+ minecraft/textures/block/sniffer_egg_very_cracked_west.png
- minecraft/textures/block/sniffer_egg_very_cracked.png
- minecraft/textures/block/torchflower_crop_stage2.png
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
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
- net.minecraft.world.level.lighting.LayerLightEngine
+ net.minecraft.world.level.lighting.LayerLightEventListener
- net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ net.minecraft.world.level.lighting.LayerLightSectionStorage
- net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LeveledPriorityQueue
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
+ net.minecraft.world.level.material.MaterialColor$Brightness
- net.minecraft.world.level.material.package-info
- net.minecraft.world.level.material.PushReaction
+ net.minecraft.world.level.material.WaterFluid
- net.minecraft.world.level.material.WaterFluid$Flowing
+ net.minecraft.world.level.material.WaterFluid$Source
+ net.minecraft.world.level.package-info
- net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
- net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.portal.package-info
+ net.minecraft.world.level.portal.PortalForcer
- net.minecraft.world.level.portal.PortalInfo
+ net.minecraft.world.level.portal.PortalShape
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ net.minecraft.world.level.redstone.InstantNeighborUpdater
- net.minecraft.world.level.redstone.NeighborUpdater
- net.minecraft.world.level.redstone.package-info
+ net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DataVersion
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelResource
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
+ net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.LevelSummary$BackupStatus
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
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
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
- net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
- net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
+ net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetPotionFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$InlineSerializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.IntRange$Serializer
- net.minecraft.world.level.storage.loot.ItemModifierManager
+ net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.LootTable$Serializer
- net.minecraft.world.level.storage.loot.LootTables
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.PredicateManager
- net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$InlineSerializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.Serializer
- net.minecraft.world.level.storage.loot.SerializerType
+ net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.storage.PlayerDataStorage
+ net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
+ net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$Event
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
- net.minecraft.world.ticks.BlackholeTickAccess
+ net.minecraft.world.ticks.BlackholeTickAccess$1
- net.minecraft.world.ticks.BlackholeTickAccess$2
+ net.minecraft.world.ticks.ContainerSingleItem
- net.minecraft.world.ticks.LevelChunkTicks
+ net.minecraft.world.ticks.LevelTickAccess
- net.minecraft.world.ticks.LevelTicks
+ net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
- net.minecraft.world.ticks.package-info
- net.minecraft.world.ticks.ProtoChunkTicks
+ net.minecraft.world.ticks.SavedTick
- net.minecraft.world.ticks.SavedTick$1
+ net.minecraft.world.ticks.ScheduledTick
- net.minecraft.world.ticks.ScheduledTick$1
+ net.minecraft.world.ticks.SerializableTickContainer
- net.minecraft.world.ticks.TickAccess
+ net.minecraft.world.ticks.TickContainerAccess
- net.minecraft.world.ticks.TickPriority
+ net.minecraft.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.Direction +2M -6M | -1P
```
```
XXX.models.model.ModelTemplates +1P
```
```
XXX.gametest.framework.GameTestHelper -1M
```
```
XXX.server.level.SectionTracker -1M
```
```
XXX.world.entity.LivingEntity +4M -4M
```
```
XXX.entity.animal.Pig +3M -3M
```
```
XXX.animal.horse.AbstractHorse +4M -3M
```
```
XXX.animal.sniffer.Sniffer +1M -3M | +1P -1P
```
```
XXX.world.item.BrushItem +2M -1M | +1P -1P
```
```
XXX.level.block.AmethystClusterBlock -1M
```
```
XXX.level.block.BasePressurePlateBlock -1M
```
```
XXX.level.block.BrushableBlock -1M
```
```
XXX.level.block.DoorBlock -1M
```
```
XXX.level.block.EndRodBlock -1M
```
```
XXX.level.block.IceBlock -1M
```
```
XXX.level.block.LanternBlock -1M
```
```
XXX.level.block.PointedDripstoneBlock -1M
```
```
XXX.level.block.SculkVeinBlock -1M
```
```
XXX.level.block.ShulkerBoxBlock -1M
```
```
XXX.level.block.SignBlock +1M
```
```
XXX.level.block.StructureVoidBlock -1M
```
```
XXX.block.entity.SignBlockEntity +5M
```
```
XXX.structure.templatesystem.StructureProcessor +1M -1M
```
```
XXX.level.lighting.BlockLightEngine +1M
```
```
XXX.level.lighting.DynamicGraphMinFixedPoint +2M -4M | +2P -3P
```

</details>




































































































































































































<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
- Direction fromDelta(int,int,int)
+ Direction fromNormal(BlockPos)
+ Direction fromNormal(int,int,int)
+ Direction lambda$static$6(Direction)
+ Direction lambda$static$7(Direction,Direction)
+ Long lambda$static$5(Direction)
- String lambda$verifyVertical$5()
+ String lambda$verifyVertical$8()
```

</details>





















































































































































































<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
+ void continuouslyUse(BlockPos,Player,BlockHitResult)
```

</details>





































































































































































































































































































































































<details>
<summary>
net.minecraft.server.level.SectionTracker
</summary>

```diff
+ boolean isSource(long)
```

</details>





























































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ float getRiddenSpeed(LivingEntity)
- float getRiddenSpeed(Player)
+ Vec3 getRiddenInput(LivingEntity,Vec3)
- Vec3 getRiddenInput(Player,Vec3)
+ void tickRidden(LivingEntity,Vec3)
- void tickRidden(Player,Vec3)
+ void travelRidden(LivingEntity,Vec3)
- void travelRidden(Player,Vec3)
```

</details>
























































































































































































































<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
+ float getRiddenSpeed(LivingEntity)
- float getRiddenSpeed(Player)
+ Vec3 getRiddenInput(LivingEntity,Vec3)
- Vec3 getRiddenInput(Player,Vec3)
+ void tickRidden(LivingEntity,Vec3)
- void tickRidden(Player,Vec3)
```

</details>








































<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- boolean isWoodSoundType(SoundType)
+ float getRiddenSpeed(LivingEntity)
- float getRiddenSpeed(Player)
+ Vec3 getRiddenInput(LivingEntity,Vec3)
- Vec3 getRiddenInput(Player,Vec3)
+ void tickRidden(LivingEntity,Vec3)
- void tickRidden(Player,Vec3)
```

</details>









<details>
<summary>
net.minecraft.world.entity.animal.sniffer.Sniffer
</summary>

```diff
+ boolean isMoving()
+ boolean isMovingInWater()
+ boolean isMovingOnLand()
- double getPassengersRidingOffset()
```

</details>
























































































































































































































<details>
<summary>
net.minecraft.world.item.BrushItem
</summary>

```diff
- HitResult calculateUseHit(LivingEntity)
- void spawnDustParticles(Level,BlockHitResult,BlockState,Vec3,boolean)
+ void spawnDustParticles(Level,BlockHitResult,BlockState,Vec3)
```

</details>
































































































































































































<details>
<summary>
net.minecraft.world.level.block.AmethystClusterBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.BasePressurePlateBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>










<details>
<summary>
net.minecraft.world.level.block.BrushableBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>































<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>


















<details>
<summary>
net.minecraft.world.level.block.IceBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.LanternBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>
























<details>
<summary>
net.minecraft.world.level.block.PointedDripstoneBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>






















<details>
<summary>
net.minecraft.world.level.block.SculkVeinBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SignBlock
</summary>

```diff
- Vec3 getSignHitboxCenterPosition(BlockState)
```

</details>















<details>
<summary>
net.minecraft.world.level.block.StructureVoidBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>


























































<details>
<summary>
net.minecraft.world.level.block.entity.SignBlockEntity
</summary>

```diff
- boolean canExecuteClickCommands(boolean,Player)
- boolean executeClickCommandsIfPresent(ServerPlayer,ServerLevel,BlockPos,boolean)
- CommandSourceStack createCommandSourceStack(ServerPlayer,ServerLevel,BlockPos)
- Component loadLine(Component)
- SignText loadLines(SignText)
```

</details>
























































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
</summary>

```diff
+ List finalizeProcessing(LevelAccessor,BlockPos,BlockPos,List,List,StructurePlaceSettings)
- List finalizeProcessing(ServerLevelAccessor,BlockPos,BlockPos,List,List,StructurePlaceSettings)
```

</details>














<details>
<summary>
net.minecraft.world.level.lighting.BlockLightEngine
</summary>

```diff
- void <init>(LightChunkGetter,BlockLightSectionStorage)
```

</details>

<details>
<summary>
net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
</summary>

```diff
- boolean isSource(long)
- int calculatePriority(int,int)
+ int getKey(int,int)
+ void checkFirstQueuedLevel(int)
+ void dequeue(long,int,int,boolean)
+ void enqueue(long,int,int)
```

</details>
<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LeveledPriorityQueue$1
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
- net.minecraft.world.level.material.MaterialColor$Brightness
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
- net.minecraft.world.level.redstone.CollectingNeighborUpdater
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- net.minecraft.world.level.redstone.InstantNeighborUpdater
+ net.minecraft.world.level.redstone.NeighborUpdater
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DataVersion
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelResource
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
- net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.LevelSummary$BackupStatus
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
- net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
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
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
+ net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
- net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
+ net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
+ net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetPotionFunction
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$InlineSerializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
+ net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
+ net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.IntRange$Serializer
+ net.minecraft.world.level.storage.loot.ItemModifierManager
- net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootPool$Serializer
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.LootTable$Serializer
+ net.minecraft.world.level.storage.loot.LootTables
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.PredicateManager
+ net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
+ net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$InlineSerializer
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
+ net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$InlineSerializer
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
+ net.minecraft.world.level.storage.loot.providers.score.package-info
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
- net.minecraft.world.level.storage.loot.Serializer
+ net.minecraft.world.level.storage.loot.SerializerType
- net.minecraft.world.level.storage.loot.ValidationContext
- net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
- net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.timers.FunctionCallback
- net.minecraft.world.level.timers.FunctionCallback$Serializer
+ net.minecraft.world.level.timers.FunctionTagCallback
- net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.package-info
+ net.minecraft.world.level.timers.TimerCallback
- net.minecraft.world.level.timers.TimerCallback$Serializer
+ net.minecraft.world.level.timers.TimerCallbacks
- net.minecraft.world.level.timers.TimerQueue
+ net.minecraft.world.level.timers.TimerQueue$Event
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
+ net.minecraft.world.ticks.BlackholeTickAccess
- net.minecraft.world.ticks.BlackholeTickAccess$1
+ net.minecraft.world.ticks.BlackholeTickAccess$2
- net.minecraft.world.ticks.ContainerSingleItem
+ net.minecraft.world.ticks.LevelChunkTicks
- net.minecraft.world.ticks.LevelTickAccess
+ net.minecraft.world.ticks.LevelTicks
- net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
+ net.minecraft.world.ticks.package-info
+ net.minecraft.world.ticks.ProtoChunkTicks
- net.minecraft.world.ticks.SavedTick
+ net.minecraft.world.ticks.SavedTick$1
- net.minecraft.world.ticks.ScheduledTick
+ net.minecraft.world.ticks.ScheduledTick$1
- net.minecraft.world.ticks.SerializableTickContainer
+ net.minecraft.world.ticks.TickAccess
- net.minecraft.world.ticks.TickContainerAccess
+ net.minecraft.world.ticks.TickPriority
- net.minecraft.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.client.Options +1P
```
```
XXX.animation.definitions.SnifferAnimation +1P
```
```
XXX.gui.screens.VideoSettingsScreen +1M
```
```
XXX.minecraft.core.Direction +2M -6M | -1P
```
```
XXX.models.model.ModelTemplates +1P
```
```
XXX.gametest.framework.GameTestHelper -1M
```
```
XXX.animal.camel.Camel +4M -4M | +1P
```
```
XXX.entity.monster.Strider +3M -3M
```
```
XXX.entity.projectile.ProjectileUtil +3M -1M
```
```
XXX.world.level.LightLayer +1M -1M | -1P
```
```
XXX.level.block.BaseRailBlock -1M
```
```
XXX.level.block.BedBlock -1M
```
```
XXX.level.block.BellBlock -1M
```
```
XXX.level.block.Blocks +4M -2M
```
```
XXX.level.block.BuddingAmethystBlock -1M
```
```
XXX.level.block.CeilingHangingSignBlock +1M
```
```
XXX.level.block.GlazedTerracottaBlock -1M
```
```
XXX.level.block.PitcherCropBlock +1P -2P
```
```
XXX.level.block.WallHangingSignBlock +2M
```
```
XXX.level.block.WallSignBlock +1M
```
```
XXX.block.entity.SignText -2M
```
```
XXX.block.state.BlockBehaviour -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +1M | +2P
```
```
XXX.block.state.BlockBehaviour$Properties +2M | +2P
```
```
XXX.structure.templatesystem.CappedProcessor +1M -1M
```
```
XXX.structure.templatesystem.StructureTemplate +1M -1M
```
```
XXX.level.lighting.DynamicGraphMinFixedPoint$1 +1P -1P
```

</details>






















































































































































































































































































































































































































































<details>
<summary>
net.minecraft.client.gui.screens.VideoSettingsScreen
</summary>

```diff
- boolean mouseScrolled(double,double,double)
```

</details>

















































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
- Direction fromDelta(int,int,int)
+ Direction fromNormal(BlockPos)
+ Direction fromNormal(int,int,int)
+ Direction lambda$static$6(Direction)
+ Direction lambda$static$7(Direction,Direction)
+ Long lambda$static$5(Direction)
- String lambda$verifyVertical$5()
+ String lambda$verifyVertical$8()
```

</details>





















































































































































































<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
+ void continuouslyUse(BlockPos,Player,BlockHitResult)
```

</details>






























































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.animal.camel.Camel
</summary>

```diff
+ float getRiddenSpeed(LivingEntity)
- float getRiddenSpeed(Player)
+ Vec3 getRiddenInput(LivingEntity,Vec3)
- Vec3 getRiddenInput(Player,Vec3)
- void standUpInstantly()
+ void standUpPanic()
+ void tickRidden(LivingEntity,Vec3)
- void tickRidden(Player,Vec3)
```

</details>



























































































<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
+ float getRiddenSpeed(LivingEntity)
- float getRiddenSpeed(Player)
+ Vec3 getRiddenInput(LivingEntity,Vec3)
- Vec3 getRiddenInput(Player,Vec3)
+ void tickRidden(LivingEntity,Vec3)
- void tickRidden(Player,Vec3)
```

</details>





















































<details>
<summary>
net.minecraft.world.entity.projectile.ProjectileUtil
</summary>

```diff
+ HitResult getHitResult(Entity,Predicate)
- HitResult getHitResult(Vec3,Entity,Predicate,Vec3,Level)
- HitResult getHitResultOnMoveVector(Entity,Predicate)
- HitResult getHitResultOnViewVector(Entity,Predicate,double)
```

</details>

















































































































































































































































<details>
<summary>
net.minecraft.world.level.LightLayer
</summary>

```diff
+ void <init>(String,int,int)
- void <init>(String,int)
```

</details>



















































<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
- ButtonBlock woodenButton(BlockSetType,FeatureFlag[])
+ ButtonBlock woodenButton(BlockSetType)
- CandleBlock candle(MaterialColor)
- FlowerPotBlock flowerPot(Block,FeatureFlag[])
+ RotatedPillarBlock log(MaterialColor,MaterialColor,SoundType,FeatureFlag[])
- RotatedPillarBlock log(MaterialColor,MaterialColor,SoundType)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.BuddingAmethystBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.CeilingHangingSignBlock
</summary>

```diff
- boolean shouldTryToChainAnotherHangingSign(Player,BlockHitResult,SignBlockEntity,ItemStack)
```

</details>







































<details>
<summary>
net.minecraft.world.level.block.GlazedTerracottaBlock
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>































































































<details>
<summary>
net.minecraft.world.level.block.WallHangingSignBlock
</summary>

```diff
- boolean isHittingEditableSide(BlockHitResult,BlockState)
- boolean shouldTryToChainAnotherHangingSign(BlockState,Player,BlockHitResult,SignBlockEntity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WallSignBlock
</summary>

```diff
- Vec3 getSignHitboxCenterPosition(BlockState)
```

</details>










































<details>
<summary>
net.minecraft.world.level.block.entity.SignText
</summary>

```diff
+ boolean executeClickCommandsIfPresent(ServerPlayer,ServerLevel,BlockPos)
+ CommandSourceStack createCommandSourceStack(ServerPlayer,ServerLevel,BlockPos)
```

</details>

















<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ PushReaction getPistonPushReaction(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- boolean ignitedByLava()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$Properties
</summary>

```diff
- BlockBehaviour$Properties ignitedByLava()
- BlockBehaviour$Properties pushReaction(PushReaction)
```

</details>


























































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.CappedProcessor
</summary>

```diff
+ List finalizeProcessing(LevelAccessor,BlockPos,BlockPos,List,List,StructurePlaceSettings)
- List finalizeProcessing(ServerLevelAccessor,BlockPos,BlockPos,List,List,StructurePlaceSettings)
```

</details>









<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
</summary>

```diff
+ List processBlockInfos(LevelAccessor,BlockPos,BlockPos,StructurePlaceSettings,List)
- List processBlockInfos(ServerLevelAccessor,BlockPos,BlockPos,StructurePlaceSettings,List)
```

</details>
</details>