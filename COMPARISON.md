## Comparison with [23w17a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w17a)

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
<table><tr><th></th><th align="left">23w17a</th><th>23w18a</th></tr><tr><td>DataPack version</td><td><code>14</code></td><td><code>15</code></td></tr><tr><td>World version</td><td><code>3452</code></td><td><code>3453</code></td></tr><tr><td>Protocol version</td><td><code>1073741956</code></td><td><code>1073741957</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
loot_condition_type.txt
</summary>

```diff
+ minecraft:all_of
- minecraft:alternative
+ minecraft:any_of
```

</details>
</details>
<details><summary>Tags</summary>
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
<details><summary>Translations</summary>
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

```
advancements.adventure.craft_decorated_pot_using_only_sherds.title: Careful rRestoration
advancements.adventure.trim_with_any_armor_pattern.title: Crafting a nNew lLook
advancements.adventure.salvage_sherd.title: Respecting the rRemnants
advancements.adventure.trim_with_all_exclusive_armor_patterns.title: Smithing with sStyle
advancements.husbandry.feed_snifflet.title: Little sSniffs
advancements.husbandry.obtain_sniffer_egg.title: Smells iInteresting
advancements.husbandry.plant_any_sniffer_seed.title: Planting the pPast
```

</details>
</details>
<details><summary>File structure</summary>
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
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.advancements.critereon.ContextAwarePredicate
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.DamagePredicate
- net.minecraft.advancements.critereon.DamagePredicate$Builder
+ net.minecraft.advancements.critereon.DamageSourcePredicate
- net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
+ net.minecraft.advancements.critereon.DeserializationContext
- net.minecraft.advancements.critereon.DistancePredicate
+ net.minecraft.advancements.critereon.DistanceTrigger
- net.minecraft.advancements.critereon.DistanceTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EffectsChangedTrigger
- net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EnchantedItemTrigger
- net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EnchantmentPredicate
- net.minecraft.advancements.critereon.EnterBlockTrigger
+ net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EntityEquipmentPredicate
+ net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
- net.minecraft.advancements.critereon.EntityFlagsPredicate
+ net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
- net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
+ net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EntityPredicate
+ net.minecraft.advancements.critereon.EntityPredicate$Builder
+ net.minecraft.advancements.critereon.ItemInteractWithBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.PlacedBlockTrigger
+ net.minecraft.world.level.lighting.LightEngine$1
- net.minecraft.world.level.lighting.LightEngine$QueueEntry
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightEngine$1
- net.minecraft.world.level.lighting.SkyLightSectionStorage
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
+ net.minecraft.world.level.material.MapColor
- net.minecraft.world.level.material.MapColor$Brightness
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
- net.minecraft.world.level.storage.loot.functions.FunctionReference
+ net.minecraft.world.level.storage.loot.functions.FunctionReference$Serializer
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
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
- net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootDataId
+ net.minecraft.world.level.storage.loot.LootDataManager
- net.minecraft.world.level.storage.loot.LootDataManager$1
+ net.minecraft.world.level.storage.loot.LootDataManager$CompositePredicate
- net.minecraft.world.level.storage.loot.LootDataManager$FunctionSequence
+ net.minecraft.world.level.storage.loot.LootDataResolver
- net.minecraft.world.level.storage.loot.LootDataType
+ net.minecraft.world.level.storage.loot.LootDataType$Validator
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.LootTable$Serializer
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
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















































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ com.mojang.blaze3d.font.package-info
- com.mojang.blaze3d.font.TrueTypeGlyphProvider
+ com.mojang.blaze3d.font.TrueTypeGlyphProvider$Glyph
- com.mojang.blaze3d.font.TrueTypeGlyphProvider$Glyph$1
- com.mojang.blaze3d.package-info
+ com.mojang.blaze3d.pipeline.MainTarget
- com.mojang.blaze3d.pipeline.MainTarget$AttachmentState
+ com.mojang.blaze3d.pipeline.MainTarget$Dimension
- com.mojang.blaze3d.pipeline.package-info
- com.mojang.blaze3d.pipeline.RenderCall
+ com.mojang.blaze3d.pipeline.RenderPipeline
- com.mojang.blaze3d.pipeline.RenderTarget
+ com.mojang.blaze3d.pipeline.TextureTarget
+ com.mojang.blaze3d.platform.ClipboardManager
- com.mojang.blaze3d.platform.DebugMemoryUntracker
+ com.mojang.blaze3d.platform.DisplayData
+ com.mojang.blaze3d.platform.GlConst
- com.mojang.blaze3d.platform.GlDebug
+ com.mojang.blaze3d.platform.GlDebug$LogEntry
- com.mojang.blaze3d.platform.GlStateManager
+ com.mojang.blaze3d.platform.GlStateManager$BlendState
- com.mojang.blaze3d.platform.GlStateManager$BooleanState
+ com.mojang.blaze3d.platform.GlStateManager$ColorLogicState
- com.mojang.blaze3d.platform.GlStateManager$ColorMask
+ com.mojang.blaze3d.platform.GlStateManager$CullState
- com.mojang.blaze3d.platform.GlStateManager$DepthState
+ com.mojang.blaze3d.platform.GlStateManager$DestFactor
- com.mojang.blaze3d.platform.GlStateManager$LogicOp
+ com.mojang.blaze3d.platform.GlStateManager$PolygonOffsetState
- com.mojang.blaze3d.platform.GlStateManager$ScissorState
+ com.mojang.blaze3d.platform.GlStateManager$SourceFactor
- com.mojang.blaze3d.platform.GlStateManager$StencilFunc
+ com.mojang.blaze3d.platform.GlStateManager$StencilState
- com.mojang.blaze3d.platform.GlStateManager$TextureState
+ com.mojang.blaze3d.platform.GlStateManager$Viewport
- com.mojang.blaze3d.platform.GlUtil
- com.mojang.blaze3d.platform.GLX
+ com.mojang.blaze3d.platform.IconSet
- com.mojang.blaze3d.platform.InputConstants
+ com.mojang.blaze3d.platform.InputConstants$Key
- com.mojang.blaze3d.platform.InputConstants$Type
+ com.mojang.blaze3d.platform.Lighting
- com.mojang.blaze3d.platform.MacosUtil
+ com.mojang.blaze3d.platform.MemoryTracker
- com.mojang.blaze3d.platform.Monitor
+ com.mojang.blaze3d.platform.MonitorCreator
- com.mojang.blaze3d.platform.NativeImage
+ com.mojang.blaze3d.platform.NativeImage$Format
- com.mojang.blaze3d.platform.NativeImage$InternalGlFormat
+ com.mojang.blaze3d.platform.NativeImage$WriteCallback
- com.mojang.blaze3d.platform.package-info
- com.mojang.blaze3d.platform.ScreenManager
+ com.mojang.blaze3d.platform.TextureUtil
- com.mojang.blaze3d.platform.VideoMode
+ com.mojang.blaze3d.platform.Window
- com.mojang.blaze3d.platform.Window$WindowInitFailed
+ com.mojang.blaze3d.platform.WindowEventHandler
+ com.mojang.blaze3d.preprocessor.GlslPreprocessor
- com.mojang.blaze3d.preprocessor.GlslPreprocessor$Context
+ com.mojang.blaze3d.preprocessor.package-info
- com.mojang.blaze3d.shaders.AbstractUniform
+ com.mojang.blaze3d.shaders.BlendMode
- com.mojang.blaze3d.shaders.Effect
+ com.mojang.blaze3d.shaders.EffectProgram
- com.mojang.blaze3d.shaders.EffectProgram$1
+ com.mojang.blaze3d.shaders.FogShape
+ com.mojang.blaze3d.shaders.package-info
- com.mojang.blaze3d.shaders.Program
+ com.mojang.blaze3d.shaders.Program$Type
- com.mojang.blaze3d.shaders.ProgramManager
+ com.mojang.blaze3d.shaders.Shader
- com.mojang.blaze3d.shaders.Uniform
+ com.mojang.blaze3d.systems.package-info
- com.mojang.blaze3d.systems.RenderSystem
+ com.mojang.blaze3d.systems.RenderSystem$1
- com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
+ com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
- com.mojang.blaze3d.systems.TimerQuery
+ com.mojang.blaze3d.systems.TimerQuery$FrameProfile
- com.mojang.blaze3d.systems.TimerQuery$TimerQueryLazyLoader
- com.mojang.blaze3d.vertex.BufferBuilder
+ com.mojang.blaze3d.vertex.BufferBuilder$1
- com.mojang.blaze3d.vertex.BufferBuilder$DrawState
+ com.mojang.blaze3d.vertex.BufferBuilder$RenderedBuffer
- com.mojang.blaze3d.vertex.BufferBuilder$SortState
+ com.mojang.blaze3d.vertex.BufferUploader
- com.mojang.blaze3d.vertex.BufferVertexConsumer
- com.mojang.blaze3d.vertex.DefaultedVertexConsumer
+ com.mojang.blaze3d.vertex.DefaultVertexFormat
+ com.mojang.blaze3d.vertex.PoseStack
- com.mojang.blaze3d.vertex.PoseStack$Pose
+ com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
- com.mojang.blaze3d.vertex.Tesselator
+ com.mojang.blaze3d.vertex.VertexBuffer
- com.mojang.blaze3d.vertex.VertexBuffer$Usage
- net.minecraft.advancements.critereon.ContextAwarePredicate
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.DamagePredicate
- net.minecraft.advancements.critereon.DamagePredicate$Builder
+ net.minecraft.advancements.critereon.DamageSourcePredicate
- net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
+ net.minecraft.advancements.critereon.DeserializationContext
- net.minecraft.advancements.critereon.DistancePredicate
+ net.minecraft.advancements.critereon.DistanceTrigger
- net.minecraft.advancements.critereon.DistanceTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EffectsChangedTrigger
- net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EnchantedItemTrigger
- net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EnchantmentPredicate
- net.minecraft.advancements.critereon.EnterBlockTrigger
+ net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EntityEquipmentPredicate
+ net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
- net.minecraft.advancements.critereon.EntityFlagsPredicate
+ net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
- net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
+ net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EntityPredicate
+ net.minecraft.advancements.critereon.EntityPredicate$Builder
+ net.minecraft.advancements.critereon.ItemInteractWithBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.PlacedBlockTrigger
- net.minecraft.client.gui.font.FontManager$FontDefinitionFile
+ net.minecraft.client.gui.font.FontManager$Preparation
- net.minecraft.client.gui.font.FontManager$UnresolvedBuilderBundle
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontSet$GlyphInfoFilter
+ net.minecraft.client.gui.font.FontTexture
- net.minecraft.client.gui.font.FontTexture$Node
+ net.minecraft.client.gui.font.GlyphRenderTypes
- net.minecraft.client.gui.font.GlyphRenderTypes$1
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
- net.minecraft.client.gui.font.glyphs.EmptyGlyph
- net.minecraft.client.gui.font.glyphs.package-info
+ net.minecraft.client.gui.font.glyphs.SpecialGlyphs
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs$1
+ net.minecraft.client.gui.font.glyphs.SpecialGlyphs$PixelProvider
+ net.minecraft.client.gui.font.package-info
- net.minecraft.client.gui.font.providers.BitmapProvider
+ net.minecraft.client.gui.font.providers.BitmapProvider$Builder
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph$1
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilder$Loader
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Reference
- net.minecraft.client.gui.font.providers.ProviderReferenceDefinition
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition$Shift
+ net.minecraft.client.gui.font.providers.UnihexProvider$Builder
- net.minecraft.client.gui.font.providers.UnihexProvider$ByteContents
+ net.minecraft.client.gui.font.TextFieldHelper
- net.minecraft.client.gui.font.TextFieldHelper$1
+ net.minecraft.client.gui.font.TextFieldHelper$CursorStep
- net.minecraft.client.renderer.block.BlockModelShaper
+ net.minecraft.client.renderer.block.BlockRenderDispatcher
- net.minecraft.client.renderer.block.BlockRenderDispatcher$1
+ net.minecraft.client.renderer.block.LiquidBlockRenderer
- net.minecraft.client.renderer.block.LiquidBlockRenderer$1
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
+ net.minecraft.client.renderer.block.model.ItemOverride$Predicate
- net.minecraft.client.renderer.block.model.ItemOverrides
+ net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
- net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
+ net.minecraft.client.renderer.block.model.ItemTransform
- net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms
- net.minecraft.client.renderer.block.model.ItemTransforms$1
+ net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
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
+ net.minecraft.client.renderer.blockentity.BannerRenderer
- net.minecraft.client.renderer.blockentity.BeaconRenderer
+ net.minecraft.client.renderer.blockentity.BedRenderer
- net.minecraft.client.renderer.blockentity.BellRenderer
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
- net.minecraft.client.renderer.blockentity.BlockEntityRenderer
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderers
- net.minecraft.client.renderer.blockentity.BrightnessCombiner
+ net.minecraft.client.renderer.blockentity.BrushableBlockRenderer
- net.minecraft.client.renderer.blockentity.BrushableBlockRenderer$1
+ net.minecraft.client.renderer.blockentity.CampfireRenderer
- net.minecraft.client.renderer.blockentity.ChestRenderer
+ net.minecraft.client.renderer.blockentity.ConduitRenderer
- net.minecraft.client.renderer.blockentity.DecoratedPotRenderer
+ net.minecraft.client.renderer.blockentity.EnchantTableRenderer
- net.minecraft.client.renderer.blockentity.HangingSignRenderer
+ net.minecraft.client.renderer.blockentity.HangingSignRenderer$HangingSignModel
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
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
- net.minecraft.client.renderer.chunk.package-info
+ net.minecraft.client.renderer.chunk.RenderChunk
- net.minecraft.client.renderer.chunk.RenderChunkRegion
+ net.minecraft.client.renderer.chunk.RenderRegionCache
- net.minecraft.client.renderer.chunk.RenderRegionCache$ChunkInfo
+ net.minecraft.client.renderer.chunk.VisGraph
- net.minecraft.client.renderer.chunk.VisGraph$1
+ net.minecraft.client.renderer.chunk.VisibilitySet
+ net.minecraft.client.renderer.culling.Frustum
- net.minecraft.client.renderer.culling.package-info
+ net.minecraft.client.renderer.debug.BeeDebugRenderer
- net.minecraft.client.renderer.debug.BeeDebugRenderer$BeeInfo
+ net.minecraft.client.renderer.debug.BeeDebugRenderer$HiveInfo
- net.minecraft.client.renderer.debug.BrainDebugRenderer
+ net.minecraft.client.renderer.debug.BrainDebugRenderer$BrainDump
- net.minecraft.client.renderer.debug.BrainDebugRenderer$PoiInfo
+ net.minecraft.client.renderer.debug.ChunkBorderRenderer
- net.minecraft.client.renderer.debug.ChunkDebugRenderer
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer$ChunkData
- net.minecraft.client.renderer.debug.CollisionBoxRenderer
+ net.minecraft.client.renderer.debug.DebugRenderer
- net.minecraft.client.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedListener
- net.minecraft.client.renderer.debug.GameTestDebugRenderer
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- net.minecraft.client.renderer.debug.HeightMapRenderer
+ net.minecraft.client.renderer.debug.HeightMapRenderer$1
- net.minecraft.client.renderer.debug.LightDebugRenderer
+ net.minecraft.client.renderer.debug.LightSectionDebugRenderer
- net.minecraft.client.renderer.debug.LightSectionDebugRenderer$1
+ net.minecraft.client.renderer.debug.LightSectionDebugRenderer$SectionData
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
- net.minecraft.client.renderer.RenderStateShard$CullStateShard
+ net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
- net.minecraft.client.renderer.RenderStateShard$EmptyTextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
- net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
+ net.minecraft.client.renderer.RenderStateShard$LineStateShard
- net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
- net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$OutputStateShard
- net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
+ net.minecraft.client.renderer.RenderStateShard$ShaderStateShard
- net.minecraft.client.renderer.RenderStateShard$TextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
+ net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
- net.minecraft.client.renderer.RenderType
+ net.minecraft.client.renderer.RenderType$CompositeRenderType
- net.minecraft.client.renderer.RenderType$CompositeState
+ net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- net.minecraft.client.renderer.RenderType$OutlineProperty
+ net.minecraft.client.renderer.RunningTrimmedMean
- net.minecraft.client.renderer.ScreenEffectRenderer
+ net.minecraft.client.renderer.ShaderInstance
- net.minecraft.client.renderer.ShaderInstance$1
+ net.minecraft.client.renderer.Sheets
- net.minecraft.client.renderer.Sheets$1
+ net.minecraft.client.renderer.SpriteCoordinateExpander
- net.minecraft.client.renderer.ViewArea
+ net.minecraft.client.renderer.VirtualScreen
- net.minecraft.client.telemetry.events.GameLoadTimesEvent
+ net.minecraft.world.level.lighting.LightEngine$QueueEntry
- net.minecraft.world.level.lighting.LightEventListener
+ net.minecraft.world.level.lighting.package-info
+ net.minecraft.world.level.lighting.SkyLightEngine
- net.minecraft.world.level.lighting.SkyLightEngine$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
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
- net.minecraft.world.level.material.MapColor
+ net.minecraft.world.level.material.MapColor$Brightness
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
+ net.minecraft.world.level.storage.loot.functions.FunctionReference
- net.minecraft.world.level.storage.loot.functions.FunctionReference$Serializer
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
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
+ net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootDataId
- net.minecraft.world.level.storage.loot.LootDataManager
+ net.minecraft.world.level.storage.loot.LootDataManager$1
- net.minecraft.world.level.storage.loot.LootDataManager$CompositePredicate
+ net.minecraft.world.level.storage.loot.LootDataManager$FunctionSequence
- net.minecraft.world.level.storage.loot.LootDataResolver
+ net.minecraft.world.level.storage.loot.LootDataType
- net.minecraft.world.level.storage.loot.LootDataType$Validator
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootPool$Serializer
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.LootTable$Serializer
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Serializer
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