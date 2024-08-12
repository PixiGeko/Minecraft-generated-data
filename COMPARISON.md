## Comparison with [1.20.4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20.4)

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
<table><tr><th></th><th align="left">1.20.4</th><th>23w51a</th></tr><tr><td>DataPack version</td><td><code>26</code></td><td><code>27</code></td></tr><tr><td>World version</td><td><code>3700</code></td><td><code>3801</code></td></tr><tr><td>Protocol version</td><td><code>765</code></td><td><code>1073741993</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
attribute.txt
</summary>

```diff
+ minecraft:generic.block_interaction_range
+ minecraft:generic.entity_interaction_range
+ minecraft:generic.scale
+ minecraft:generic.step_height
```

</details>












<details>
<summary>
entity_type.txt
</summary>

```diff
+ minecraft:armadillo
```

</details>







<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:armadillo_scute
+ minecraft:armadillo_spawn_egg
- minecraft:scute
+ minecraft:turtle_scute
+ minecraft:wolf_armor
```

</details>






<details>
<summary>
memory_module_type.txt
</summary>

```diff
+ minecraft:breeze_leaving_water
+ minecraft:danger_detected_recently
```

</details>














<details>
<summary>
sensor_type.txt
</summary>

```diff
+ minecraft:armadillo_scare_detected
+ minecraft:armadillo_temptations
```

</details>
<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:entity.armadillo.ambient
+ minecraft:entity.armadillo.brush
+ minecraft:entity.armadillo.death
+ minecraft:entity.armadillo.eat
+ minecraft:entity.armadillo.hurt
+ minecraft:entity.armadillo.land
+ minecraft:entity.armadillo.roll
+ minecraft:entity.armadillo.scute_drop
+ minecraft:entity.armadillo.step
+ minecraft:entity.armadillo.unroll
+ minecraft:entity.breeze.charge
+ minecraft:entity.breeze.deflect
+ minecraft:entity.breeze.whirl
+ minecraft:item.armor.equip_wolf
+ minecraft:item.armor.unequip_wolf
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:armadillo
```

</details>

<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:armadillo
```

</details>


<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:generic.block_interaction_range
+ minecraft:generic.entity_interaction_range
+ minecraft:generic.scale
+ minecraft:generic.step_height
```

</details>












<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:armadillo
```

</details>







<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:armadillo_scute
+ minecraft:armadillo_spawn_egg
- minecraft:scute
+ minecraft:turtle_scute
+ minecraft:wolf_armor
```

</details>






<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:breeze_leaving_water
+ minecraft:danger_detected_recently
```

</details>














<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:armadillo_scare_detected
+ minecraft:armadillo_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.armadillo.ambient
+ minecraft:entity.armadillo.brush
+ minecraft:entity.armadillo.death
+ minecraft:entity.armadillo.eat
+ minecraft:entity.armadillo.hurt
+ minecraft:entity.armadillo.land
+ minecraft:entity.armadillo.roll
+ minecraft:entity.armadillo.scute_drop
+ minecraft:entity.armadillo.step
+ minecraft:entity.armadillo.unroll
+ minecraft:entity.breeze.charge
+ minecraft:entity.breeze.deflect
+ minecraft:entity.breeze.whirl
+ minecraft:item.armor.equip_wolf
+ minecraft:item.armor.unequip_wolf
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ wolf_armor.json
```

</details>








































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
turtle_helmet.json
</summary>

```
A: scute
B: turtle_scute

Previous pattern:
[A | A | A]
[A |   | A]

New pattern:
[B | B | B]
[B |   | B]
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ attribute.name.generic.block_interaction_range: Block Interaction Range
+ attribute.name.generic.entity_interaction_range: Entity Interaction Range
+ attribute.name.generic.scale: Scale
+ attribute.name.generic.step_height: Step Height
+ entity.minecraft.armadillo: Armadillo
+ item.minecraft.armadillo_scute: Armadillo Scute
+ item.minecraft.armadillo_spawn_egg: Armadillo Spawn Egg
- item.minecraft.scute: Scute
+ item.minecraft.turtle_scute: Turtle Scute
+ item.minecraft.wolf_armor: Wolf Armor
+ subtitles.entity.armadillo.ambient: Armadillo grunts
+ subtitles.entity.armadillo.brush: Armadillo brushes
+ subtitles.entity.armadillo.death: Armadillo dies
+ subtitles.entity.armadillo.eat: Armadillo eats
+ subtitles.entity.armadillo.hurt: Armadillo hurts
+ subtitles.entity.armadillo.land: Armadillo lands
+ subtitles.entity.armadillo.roll: Armadillo rolls up
+ subtitles.entity.armadillo.scute_drop: Scute drops
+ subtitles.entity.armadillo.unroll: Armadillo unrolls
+ subtitles.entity.breeze.charge: Breeze charges
+ subtitles.entity.breeze.deflect: Breeze deflects
+ subtitles.entity.breeze.whirl: Breeze whirls
+ subtitles.item.armor.equip_wolf: Wolf armor straps
+ subtitles.item.armor.unequip_wolf: Wolf armor slips off
```

</details>
<details>
<summary>
Changes
</summary>

```
subtitles.block.respawn_anchor.ambient: PortalRespawn Anchor whooshes
subtitles.block.trial_spawner.spawn_mob: MobTrial Spawner spawns a mob
subtitles.entity.glow_item_frame.break: Glow Item Frame breaksoken
subtitles.entity.item_frame.break: Item Frame breaksoken
subtitles.entity.leash_knot.break: Leash Knot breaksoken
subtitles.entity.painting.break: Painting breaksoken
subtitles.entity.polar_bear.ambient_baby: Baby Polar Bear hums
subtitles.entity.turtle.death_baby: Baby Turtle baby dies
subtitles.entity.turtle.hurt_baby: Baby Turtle baby hurts
subtitles.entity.turtle.shamble_baby: Baby Turtle baby shambles
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/combat/wolf_armor.json
+ minecraft/damage_type/spit.json
+ minecraft/datapacks/update_1_21/data/minecraft/damage_type/wind_charge.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/damage_type/always_kills_armor_stands.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/damage_type/is_projectile.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/doors.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/trapdoors.json
+ minecraft/loot_tables/entities/armadillo.json
+ minecraft/recipes/wolf_armor.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/models/item/armadillo_scute.json
+ minecraft/models/item/armadillo_spawn_egg.json
- minecraft/models/item/scute.json
+ minecraft/models/item/turtle_scute.json
+ minecraft/models/item/wolf_armor.json
+ minecraft/textures/entity/armadillo.png
+ minecraft/textures/entity/breeze/breeze_eyes.png
+ minecraft/textures/entity/wolf/wolf_armor.png
+ minecraft/textures/item/armadillo_scute.png
- minecraft/textures/item/scute.png
+ minecraft/textures/item/turtle_scute.png
+ minecraft/textures/item/wolf_armor.png
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
- net.minecraft.core.dispenser.DispenseItemBehavior$28
+ net.minecraft.core.dispenser.DispenseItemBehavior$3
- net.minecraft.core.dispenser.DispenseItemBehavior$4
+ net.minecraft.core.dispenser.DispenseItemBehavior$5
- net.minecraft.core.dispenser.DispenseItemBehavior$6
+ net.minecraft.core.dispenser.DispenseItemBehavior$7
- net.minecraft.core.dispenser.DispenseItemBehavior$7$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$8
- net.minecraft.core.dispenser.DispenseItemBehavior$8$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$9
- net.minecraft.core.dispenser.OptionalDispenseItemBehavior
+ net.minecraft.core.dispenser.package-info
+ net.minecraft.core.dispenser.ShearsDispenseItemBehavior
- net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.package-info
+ net.minecraft.core.particles.BlockParticleOption
- net.minecraft.core.particles.BlockParticleOption$1
+ net.minecraft.core.particles.DustColorTransitionOptions
- net.minecraft.core.particles.DustColorTransitionOptions$1
+ net.minecraft.core.particles.DustParticleOptions
- net.minecraft.core.particles.DustParticleOptions$1
+ net.minecraft.core.particles.DustParticleOptionsBase
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleGroup
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SculkChargeParticleOptions
+ net.minecraft.core.particles.SculkChargeParticleOptions$1
- net.minecraft.core.particles.ShriekParticleOption
+ net.minecraft.core.particles.ShriekParticleOption$1
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption
+ net.minecraft.core.particles.VibrationParticleOption$1
+ net.minecraft.core.registries.BuiltInRegistries
- net.minecraft.core.registries.BuiltInRegistries$RegistryBootstrap
- net.minecraft.core.registries.package-info
+ net.minecraft.core.registries.Registries
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdvancementSubProvider
- net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.packs.package-info
+ net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdvancementProvider
- net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
+ net.minecraft.data.advancements.packs.VanillaAdvancementProvider
- net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
+ net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
- net.minecraft.data.advancements.packs.VanillaNetherAdvancements
+ net.minecraft.data.advancements.packs.VanillaStoryAdvancements
- net.minecraft.data.advancements.packs.VanillaTheEndAdvancements
+ net.minecraft.data.BlockFamilies
- net.minecraft.data.BlockFamily
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.CachedOutput
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataGenerator$PackGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.DataProvider$Factory
- net.minecraft.data.HashCache
+ net.minecraft.data.HashCache$CacheUpdater
- net.minecraft.data.HashCache$ProviderCache
+ net.minecraft.data.HashCache$ProviderCacheBuilder
- net.minecraft.data.HashCache$UpdateFunction
+ net.minecraft.data.HashCache$UpdateResult
- net.minecraft.data.info.BiomeParametersDumpReport
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLootSubProvider
- net.minecraft.data.loot.EntityLootSubProvider
+ net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.LootTableProvider$1
+ net.minecraft.data.loot.LootTableProvider$SubProviderEntry
- net.minecraft.data.loot.LootTableSubProvider
+ net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.packs.package-info
- net.minecraft.data.loot.packs.TradeRebalanceChestLoot
+ net.minecraft.data.loot.packs.TradeRebalanceLootTableProvider
- net.minecraft.data.loot.packs.UpdateOneTwentyOneBlockLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneChestLoot
- net.minecraft.data.loot.packs.UpdateOneTwentyOneLootTableProvider
+ net.minecraft.data.loot.packs.VanillaArchaeologyLoot
- net.minecraft.data.loot.packs.VanillaBlockLoot
+ net.minecraft.data.loot.packs.VanillaChestLoot
- net.minecraft.data.loot.packs.VanillaEntityLoot
+ net.minecraft.data.loot.packs.VanillaFishingLoot
- net.minecraft.data.loot.packs.VanillaGiftLoot
+ net.minecraft.data.loot.packs.VanillaLootTableProvider
- net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
- net.minecraft.data.Main
+ net.minecraft.data.metadata.package-info
- net.minecraft.data.metadata.PackMetadataGenerator
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ net.minecraft.data.models.BlockModelGenerators$BookSlotModelCacheKey
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
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
+ net.minecraft.data.models.ItemModelGenerators$TrimModelData
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplate$JsonFactory
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
+ net.minecraft.data.PackOutput
- net.minecraft.data.PackOutput$PathProvider
+ net.minecraft.data.PackOutput$Target
+ net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.packs.BundleRecipeProvider
- net.minecraft.data.recipes.packs.package-info
+ net.minecraft.data.recipes.packs.UpdateOneTwentyOneRecipeProvider
- net.minecraft.data.recipes.packs.VanillaRecipeProvider
+ net.minecraft.data.recipes.packs.VanillaRecipeProvider$TrimTemplate
- net.minecraft.data.recipes.RecipeBuilder
+ net.minecraft.data.recipes.RecipeBuilder$1
- net.minecraft.data.recipes.RecipeCategory
+ net.minecraft.data.recipes.RecipeOutput
- net.minecraft.data.recipes.RecipeProvider
+ net.minecraft.data.recipes.RecipeProvider$1
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder
- net.minecraft.data.recipes.SmithingTransformRecipeBuilder
+ net.minecraft.data.recipes.SmithingTrimRecipeBuilder
- net.minecraft.data.recipes.SpecialRecipeBuilder
+ net.minecraft.data.registries.package-info
+ net.minecraft.data.registries.RegistriesDatapackGenerator
- net.minecraft.data.registries.RegistryPatchGenerator
+ net.minecraft.data.registries.UpdateOneTwentyOneRegistries
- net.minecraft.data.registries.VanillaRegistries
- net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtDatafixer
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$StructureConversionException
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BannerPatternTagsProvider
+ net.minecraft.data.tags.BiomeTagsProvider
- net.minecraft.data.tags.CatVariantTagsProvider
+ net.minecraft.data.tags.DamageTypeTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.data.tags.InstrumentTagsProvider
+ net.minecraft.data.tags.IntrinsicHolderTagsProvider
- net.minecraft.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.PaintingVariantTagsProvider
+ net.minecraft.data.tags.PoiTypeTagsProvider
- net.minecraft.data.tags.StructureTagsProvider
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1CombinedData
+ net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.tags.TagsProvider$TagLookup
+ net.minecraft.data.tags.TradeRebalanceStructureTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneBiomeTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneBlockTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneDamageTypeTagsProvider
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V3799
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
- net.minecraft.util.eventlog.EventLogDirectory
+ net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
- net.minecraft.util.eventlog.EventLogDirectory$File
+ net.minecraft.util.eventlog.EventLogDirectory$FileId
- net.minecraft.util.eventlog.EventLogDirectory$FileList
+ net.minecraft.util.eventlog.EventLogDirectory$RawFile
- net.minecraft.util.eventlog.JsonEventLog
+ net.minecraft.util.eventlog.JsonEventLog$1
- net.minecraft.util.eventlog.JsonEventLogReader
+ net.minecraft.util.eventlog.JsonEventLogReader$1
- net.minecraft.util.eventlog.package-info
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.jfr.callback.package-info
+ net.minecraft.util.profiling.jfr.callback.ProfiledDuration
- net.minecraft.util.profiling.jfr.Environment
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
+ net.minecraft.util.profiling.jfr.event.package-info
- net.minecraft.util.profiling.jfr.event.PacketEvent
+ net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
- net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
+ net.minecraft.util.profiling.jfr.event.PacketSentEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
- net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
+ net.minecraft.util.profiling.jfr.JfrProfiler
- net.minecraft.util.profiling.jfr.JfrProfiler$1
+ net.minecraft.util.profiling.jfr.JvmProfiler
- net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
- net.minecraft.util.profiling.jfr.package-info
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
- net.minecraft.util.profiling.jfr.parse.JfrStatsResult
+ net.minecraft.util.profiling.jfr.parse.package-info
+ net.minecraft.util.profiling.jfr.Percentiles
- net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
+ net.minecraft.util.profiling.jfr.serialize.package-info
- net.minecraft.util.profiling.jfr.stats.ChunkGenStat
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketCountAndSize
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketIdentification
+ net.minecraft.util.profiling.jfr.stats.package-info
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
- net.minecraft.util.profiling.jfr.SummaryReporter
- net.minecraft.util.profiling.metrics.MetricCategory
+ net.minecraft.util.profiling.metrics.MetricSampler
- net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
- net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
+ net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- net.minecraft.util.profiling.metrics.MetricsRegistry
+ net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- net.minecraft.util.profiling.metrics.MetricsSamplerProvider
- net.minecraft.util.profiling.metrics.package-info
+ net.minecraft.util.profiling.metrics.ProfilerMeasured
+ net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.package-info
- net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ net.minecraft.util.profiling.metrics.storage.MetricsPersister
+ net.minecraft.util.profiling.metrics.storage.package-info
- net.minecraft.util.profiling.metrics.storage.RecordedDeviation
- net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
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
+ net.minecraft.util.valueproviders.BiasedToBottomInt
- net.minecraft.util.valueproviders.ClampedInt
+ net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ClampedNormalInt
+ net.minecraft.util.valueproviders.ConstantFloat
- net.minecraft.util.valueproviders.ConstantInt
+ net.minecraft.util.valueproviders.FloatProvider
- net.minecraft.util.valueproviders.FloatProviderType
+ net.minecraft.util.valueproviders.IntProvider
- net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.MultipliedFloats
+ net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.SampledFloat
+ net.minecraft.util.valueproviders.TrapezoidFloat
- net.minecraft.util.valueproviders.UniformFloat
+ net.minecraft.util.valueproviders.UniformInt
- net.minecraft.util.valueproviders.WeightedListInt
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
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageEffects
- net.minecraft.world.damagesource.DamageScaling
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.DamageSource$1
+ net.minecraft.world.damagesource.DamageSources
- net.minecraft.world.damagesource.DamageType
+ net.minecraft.world.damagesource.DamageTypes
- net.minecraft.world.damagesource.DeathMessageType
+ net.minecraft.world.damagesource.FallLocation
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsorptionMobEffect
- net.minecraft.world.effect.MobEffectInstance$BlendState
+ net.minecraft.world.effect.MobEffectInstance$FactorData
- net.minecraft.world.entity.ai.sensing.MobSensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.sensing.WardenEntitySensor
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
+ net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.poi.PoiTypes
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.allay.Allay
+ net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
- net.minecraft.world.entity.animal.allay.Allay$VibrationUser
+ net.minecraft.world.entity.animal.allay.AllayAi
- net.minecraft.world.entity.animal.allay.package-info
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.armadillo.Armadillo$1
- net.minecraft.world.entity.animal.armadillo.Armadillo$ArmadilloState
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi$1
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi$ArmadilloPanic
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
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.CatVariant
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
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
+ net.minecraft.world.entity.animal.FrogVariant
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
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
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Parrot$Variant
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Rabbit$Variant
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$Base
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.TropicalFish$Variant
- net.minecraft.world.entity.animal.Turtle
+ net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
- net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
- net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
+ net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
- net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
- net.minecraft.world.entity.EntityAttachment$Fallback
- net.minecraft.world.entity.EntityAttachments$Builder
- net.minecraft.world.entity.monster.breeze.BreezeUtil
+ net.minecraft.world.entity.monster.breeze.LongJump
+ net.minecraft.world.entity.monster.breeze.package-info
- net.minecraft.world.entity.monster.breeze.Shoot
+ net.minecraft.world.entity.monster.breeze.ShootWhenStuck
- net.minecraft.world.entity.monster.breeze.Slide
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.hoglin.package-info
- net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.piglin.AbstractPiglin
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.PiglinAi
- net.minecraft.world.entity.monster.piglin.PiglinArmPose
+ net.minecraft.world.entity.monster.piglin.PiglinBrute
- net.minecraft.world.entity.monster.piglin.PiglinBruteAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- net.minecraft.world.entity.monster.warden.AngerLevel
+ net.minecraft.world.entity.monster.warden.AngerManagement
- net.minecraft.world.entity.monster.warden.AngerManagement$1
+ net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
+ net.minecraft.world.entity.monster.warden.package-info
- net.minecraft.world.entity.monster.warden.Warden
+ net.minecraft.world.entity.monster.warden.Warden$1
- net.minecraft.world.entity.monster.warden.Warden$1$1
+ net.minecraft.world.entity.monster.warden.Warden$2
- net.minecraft.world.entity.monster.warden.Warden$VibrationUser
+ net.minecraft.world.entity.monster.warden.WardenAi
- net.minecraft.world.entity.monster.warden.WardenSpawnTracker
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
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
+ net.minecraft.world.entity.npc.VillagerTrades$FailureItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TypeSpecificTrade
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
- net.minecraft.world.item.AnimalArmorItem
- net.minecraft.world.item.BoneMealItem$1
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BrushItem
- net.minecraft.world.item.BrushItem$1
+ net.minecraft.world.item.BrushItem$DustParticlesDelta
- net.minecraft.world.item.BucketItem
+ net.minecraft.world.item.BundleItem
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$Builder
- net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
- net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
+ net.minecraft.world.item.CreativeModeTab$Output
- net.minecraft.world.item.CreativeModeTab$Row
+ net.minecraft.world.item.CreativeModeTab$TabVisibility
- net.minecraft.world.item.CreativeModeTab$Type
+ net.minecraft.world.item.CreativeModeTabs
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.DebugStickItem
- net.minecraft.world.item.DiggerItem
+ net.minecraft.world.item.DiscFragmentItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableAnimalArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.Equipable
- net.minecraft.world.item.ExperienceBottleItem
+ net.minecraft.world.item.FireChargeItem
- net.minecraft.world.item.FireworkRocketItem
+ net.minecraft.world.item.FireworkRocketItem$Shape
- net.minecraft.world.item.FireworkStarItem
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.FoodOnAStickItem
- net.minecraft.world.item.GameMasterBlockItem
+ net.minecraft.world.item.GlowInkSacItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HangingSignItem
- net.minecraft.world.item.HoeItem
+ net.minecraft.world.item.HoneyBottleItem
- net.minecraft.world.item.HoneycombItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.ItemInteractionResult
- net.minecraft.world.level.block.BonemealableBlock$1
+ net.minecraft.world.level.gameevent.GameEventListener$Holder
- net.minecraft.world.level.gameevent.GameEventListener$Provider
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelDataAndDimensions
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
- net.minecraft.world.level.storage.LevelSummary$CorruptedLevelSummary
+ net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Path
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead
+ net.minecraft.world.level.storage.loot.functions.FunctionReference
- net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
+ net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
+ net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SequenceFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction
- net.minecraft.world.level.storage.loot.functions.SetPotionFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootDataId
+ net.minecraft.world.level.storage.loot.LootDataManager
- net.minecraft.world.level.storage.loot.LootDataManager$1
+ net.minecraft.world.level.storage.loot.LootDataResolver
- net.minecraft.world.level.storage.loot.LootDataType
+ net.minecraft.world.level.storage.loot.LootDataType$Validator
- net.minecraft.world.level.storage.loot.LootParams
+ net.minecraft.world.level.storage.loot.LootParams$Builder
- net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
+ net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
+ net.minecraft.world.level.storage.loot.providers.score.package-info
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.ValidationContext
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
+ net.minecraft.world.level.validation.ContentValidationException
- net.minecraft.world.level.validation.DirectoryValidator
+ net.minecraft.world.level.validation.DirectoryValidator$1
- net.minecraft.world.level.validation.ForbiddenSymlinkInfo
- net.minecraft.world.level.validation.package-info
+ net.minecraft.world.level.validation.PathAllowList
- net.minecraft.world.level.validation.PathAllowList$ConfigEntry
+ net.minecraft.world.level.validation.PathAllowList$EntryType
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
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
- net.minecraft.world.RandomizableContainer
+ net.minecraft.world.RandomSequence
- net.minecraft.world.RandomSequences
+ net.minecraft.world.RandomSequences$DirtyMarkingRandomSource
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
+ net.minecraft.world.scores.DisplaySlot
- net.minecraft.world.scores.DisplaySlot$1
+ net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
- net.minecraft.world.scores.PlayerScoreEntry
+ net.minecraft.world.scores.PlayerScores
- net.minecraft.world.scores.PlayerTeam
+ net.minecraft.world.scores.ReadOnlyScoreInfo
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.ScoreAccess
- net.minecraft.world.scores.Scoreboard
+ net.minecraft.world.scores.Scoreboard$1
- net.minecraft.world.scores.ScoreboardSaveData
- net.minecraft.world.scores.ScoreHolder
+ net.minecraft.world.scores.ScoreHolder$1
- net.minecraft.world.scores.ScoreHolder$2
+ net.minecraft.world.scores.ScoreHolder$3
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.TickRateManager
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
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.ItemPredicate$Builder +1M -1M
```
```
XXX.commands.functions.FunctionBuilder +1M -1M
```
```
XXX.commands.functions.MacroFunction +2M -3M
```
```
XXX.commands.functions.MacroFunction$MacroEntry +2M -3M | +1P
```
```
XXX.commands.functions.PlainTextFunction +1M -1M
```
```
XXX.minecraft.core.Holder$Direct +1M
```
```
XXX.minecraft.core.Holder$Reference +1M
```
```
XXX.minecraft.core.MappedRegistry +1M
```
```
XXX.minecraft.core.Registry +1P
```
```
XXX.core.cauldron.CauldronInteraction +15M -15M | +1P -1P
```
```
XXX.protocol.game.ClientboundRemoveMobEffectPacket +6M -2M | +1P -1P
```
```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +3M -5M | +2P -2P
```
```
XXX.protocol.game.DebugPackets +2M -1M
```
```
XXX.protocol.game.ServerboundSetBeaconPacket +9M -6M
```
```
XXX.network.syncher.EntityDataSerializers +1P
```
```
XXX.server.level.WorldGenRegion +1M -1M
```
```
XXX.minecraft.sounds.SoundEvents +15P
```
```
XXX.minecraft.util.TimeUtil +1P
```
```
XXX.datafix.fixes.BlockRenameFix$1 +1M -1M | +1P -1P
```
```
XXX.world.effect.BadOmenMobEffect +1M -1M
```
```
XXX.world.effect.HungerMobEffect +1M -1M
```
```
XXX.world.effect.MobEffect +6M -7M | +1P -2P
```
```
XXX.world.effect.MobEffects +2M -2M | +33P -33P
```
```
XXX.world.effect.RegenerationMobEffect +1M -1M
```
```
XXX.world.effect.WitherMobEffect +1M -1M
```
```
XXX.world.entity.Entity +7M -9M | +1P -2P
```
```
XXX.world.entity.LivingEntity +8M -11M | +2P -1P
```
```
XXX.world.entity.Mob +1M
```
```
XXX.world.entity.PathfinderMob -1M
```
```
XXX.ai.attributes.AttributeInstance +4M -2M | +1P -1P
```
```
XXX.ai.attributes.AttributeSupplier +7M -7M
```
```
XXX.ai.attributes.Attributes +2M -1M | +18P -14P
```
```
XXX.ai.goal.GoalSelector +1M -3M | -3P
```
```
XXX.ai.memory.MemoryModuleType +2P
```
```
XXX.animal.axolotl.Axolotl -1M
```
```
XXX.animal.goat.Goat +1M -2M
```
```
XXX.animal.horse.Horse +1M | +1P
```
```
XXX.animal.horse.Llama +2M -1M | +1P
```
```
XXX.animal.horse.ZombieHorse +2M -1M | +1P
```
```
XXX.boss.enderdragon.EnderDragon -1M
```
```
XXX.entity.decoration.ItemFrame -1M
```
```
XXX.entity.item.PrimedTnt -1M
```
```
XXX.entity.monster.AbstractIllager -2M
```
```
XXX.entity.monster.Drowned +1M
```
```
XXX.entity.monster.EnderMan -2M
```
```
XXX.entity.monster.Ghast -3M
```
```
XXX.entity.monster.Guardian -2M
```
```
XXX.entity.monster.Husk -1M
```
```
XXX.entity.monster.Phantom +1M -4M
```
```
XXX.entity.monster.Ravager -1M
```
```
XXX.entity.monster.Silverfish -2M
```
```
XXX.entity.monster.Slime +2M -3M
```
```
XXX.entity.monster.Spider +1M -3M
```
```
XXX.entity.monster.Spider$SpiderEffectsGroupData +1P -1P
```
```
XXX.entity.monster.Vex -3M
```
```
XXX.entity.monster.Witch -2M
```
```
XXX.entity.monster.Zoglin -1M
```
```
XXX.entity.monster.ZombieVillager -1M
```
```
XXX.monster.breeze.Breeze +2M -2M | +4P
```
```
XXX.monster.breeze.BreezeAi +3M -1M
```
```
XXX.entity.projectile.AbstractArrow +1M -2M
```
```
XXX.entity.projectile.Arrow +1P -1P
```
```
XXX.entity.projectile.ThrownPotion +1M -1M
```
```
XXX.entity.projectile.WindCharge -1M
```
```
XXX.entity.vehicle.AbstractMinecart +1M -1M | +1P -2P
```
```
XXX.entity.vehicle.Boat +1M -2M
```
```
XXX.world.item.Items +4P -1P
```
```
XXX.world.item.LeadItem +1M
```
```
XXX.world.item.WritableBookItem -1M
```
```
XXX.item.alchemy.Potion +2M -3M | +1P -2P
```
```
XXX.item.alchemy.PotionBrewing$Mix +7M -1M | +2P -2P
```
```
XXX.item.alchemy.Potions +3M -2M | +43P -43P
```
```
XXX.level.block.BeaconBlock +1M -1M
```
```
XXX.level.block.BrewingStandBlock +1M -1M
```
```
XXX.level.block.ButtonBlock +1M -1M
```
```
XXX.level.block.CandleBlock +1M -1M
```
```
XXX.level.block.CartographyTableBlock +1M -1M
```
```
XXX.level.block.CaveVinesBlock +1M -1M
```
```
XXX.level.block.CeilingHangingSignBlock +1M -1M
```
```
XXX.level.block.CommandBlock +1M -1M
```
```
XXX.level.block.ComposterBlock +2M -1M
```
```
XXX.level.block.DaylightDetectorBlock +1M -1M
```
```
XXX.level.block.DecoratedPotBlock +2M -1M
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.DragonEggBlock +1M -1M
```
```
XXX.level.block.EnderChestBlock +2M -2M
```
```
XXX.level.block.FenceBlock +2M -1M
```
```
XXX.level.block.FletchingTableBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock +5M -1M
```
```
XXX.level.block.GrassBlock +1M
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.LecternBlock +2M -1M
```
```
XXX.level.block.LevelEvent +2P -1P
```
```
XXX.level.block.MossBlock +1M
```
```
XXX.level.block.NoteBlock +2M -1M
```
```
XXX.level.block.RedStoneOreBlock +1M -1M
```
```
XXX.level.block.RepeaterBlock +1M -1M
```
```
XXX.level.block.SmithingTableBlock +1M -1M
```
```
XXX.level.block.StructureBlock +1M -1M
```
```
XXX.level.block.SweetBerryBushBlock +2M -1M
```
```
XXX.level.block.TntBlock +2M -2M
```
```
XXX.level.block.TrapDoorBlock +1M -1M
```
```
XXX.level.block.WallHangingSignBlock +1M -1M
```
```
XXX.block.entity.BeaconBlockEntity +5M -4M | +3P -3P
```
```
XXX.block.entity.SculkCatalystBlockEntity$CatalystListener +1M -1M
```
```
XXX.block.entity.SculkSensorBlockEntity$VibrationUser +2M -2M
```
```
XXX.block.entity.SculkShriekerBlockEntity$VibrationUser +2M -2M
```
```
XXX.block.state.BlockBehaviour +2M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M -1M
```
```
XXX.level.gameevent.EuclideanGameEventListenerRegistry +1M -1M
```
```
XXX.level.gameevent.GameEvent +6M -5M | +60P -61P
```
```
XXX.level.gameevent.GameEvent$ListenerInfo +2M -2M | +1P -1P
```
```
XXX.level.gameevent.GameEventListener +1P -1P
```
```
XXX.level.gameevent.GameEventListenerRegistry$1 +1M -1M
```

</details>

































































<details>
<summary>
net.minecraft.advancements.critereon.ItemPredicate$Builder
</summary>

```diff
- ItemPredicate$Builder isPotion(Holder)
+ ItemPredicate$Builder isPotion(Potion)
```

</details>






























































































































<details>
<summary>
net.minecraft.commands.functions.FunctionBuilder
</summary>

```diff
- void addMacro(String,int,ExecutionCommandSource)
+ void addMacro(String,int)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.MacroFunction
</summary>

```diff
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,ExecutionCommandSource)
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,Object)
- InstantiatedFunction instantiate(CompoundTag,CommandDispatcher)
+ InstantiatedFunction substituteAndParse(List,List,CommandDispatcher,ExecutionCommandSource)
- InstantiatedFunction substituteAndParse(List,List,CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.MacroFunction$MacroEntry
</summary>

```diff
+ UnboundEntryAction instantiate(List,CommandDispatcher,ExecutionCommandSource,ResourceLocation)
+ UnboundEntryAction instantiate(List,CommandDispatcher,Object,ResourceLocation)
- UnboundEntryAction instantiate(List,CommandDispatcher,ResourceLocation)
- void <init>(StringTemplate,IntList,ExecutionCommandSource)
+ void <init>(StringTemplate,IntList)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.PlainTextFunction
</summary>

```diff
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,Object)
- InstantiatedFunction instantiate(CompoundTag,CommandDispatcher)
```

</details>


























<details>
<summary>
net.minecraft.core.Holder$Direct
</summary>

```diff
- boolean is(Holder)
```

</details>
<details>
<summary>
net.minecraft.core.Holder$Reference
</summary>

```diff
- boolean is(Holder)
```

</details>









<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
- Optional getHolder(ResourceLocation)
```

</details>



















<details>
<summary>
net.minecraft.core.cauldron.CauldronInteraction
</summary>

```diff
+ InteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
+ InteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
+ InteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
- ItemInteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
- ItemInteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
```

</details>


























































































































































































































































<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
</summary>

```diff
- boolean equals(Object)
- Holder effect()
- int entityId()
- int hashCode()
+ MobEffect getEffect()
- String toString()
- void <init>(int,Holder)
+ void <init>(int,MobEffect)
```

</details>
























<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
</summary>

```diff
- boolean shouldBlend()
- Holder getEffect()
+ MobEffect getEffect()
+ MobEffectInstance$FactorData getFactorData()
+ MobEffectInstance$FactorData lambda$new$0(FriendlyByteBuf)
- void <init>(int,MobEffectInstance,boolean)
+ void <init>(int,MobEffectInstance)
+ void lambda$write$1(FriendlyByteBuf,MobEffectInstance$FactorData)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.DebugPackets
</summary>

```diff
- void lambda$sendGameEventInfo$7(ServerLevel,Vec3,ResourceKey)
+ void sendGameEventInfo(Level,GameEvent,Vec3)
- void sendGameEventInfo(Level,Holder,Vec3)
```

</details>

























<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
</summary>

```diff
- boolean equals(Object)
- Holder lambda$new$0(FriendlyByteBuf)
- Holder lambda$new$1(FriendlyByteBuf)
- int hashCode()
+ MobEffect lambda$new$0(FriendlyByteBuf)
+ MobEffect lambda$new$1(FriendlyByteBuf)
+ Optional getPrimary()
+ Optional getSecondary()
- Optional primary()
- Optional secondary()
- String toString()
- void lambda$write$2(FriendlyByteBuf,Holder)
+ void lambda$write$2(FriendlyByteBuf,MobEffect)
- void lambda$write$3(FriendlyByteBuf,Holder)
+ void lambda$write$3(FriendlyByteBuf,MobEffect)
```

</details>













































































































































































<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
+ void gameEvent(GameEvent,Vec3,GameEvent$Context)
- void gameEvent(Holder,Vec3,GameEvent$Context)
```

</details>






























































































































































































<details>
<summary>
net.minecraft.util.datafix.fixes.BlockRenameFix$1
</summary>

```diff
+ String fixBlock(String)
- String renameBlock(String)
```

</details>



























































































































<details>
<summary>
net.minecraft.world.effect.BadOmenMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.HungerMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ Holder$Reference builtInRegistryHolder()
- int getBlendDurationTicks()
+ Map getAttributeModifiers()
+ MobEffect addAttributeModifier(Attribute,String,double,AttributeModifier$Operation)
- MobEffect addAttributeModifier(Holder,String,double,AttributeModifier$Operation)
- MobEffect setBlendDuration(int)
+ MobEffect setFactorDataFactory(Supplier)
+ MobEffectInstance$FactorData lambda$new$0()
+ Optional createFactorData()
+ void applyEffectTick(LivingEntity,int)
- void createModifiers(int,BiConsumer)
- void lambda$createModifiers$0(BiConsumer,int,Holder,MobEffect$AttributeTemplate)
```

</details>

<details>
<summary>
net.minecraft.world.effect.MobEffects
</summary>

```diff
- Holder bootstrap(Registry)
- Holder register(String,MobEffect)
+ MobEffect register(String,MobEffect)
+ MobEffectInstance$FactorData lambda$static$0()
```

</details>
<details>
<summary>
net.minecraft.world.effect.RegenerationMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.WitherMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>














<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ BlockState getFeetBlockState()
- BlockState getInBlockState()
+ float getEyeHeight(Pose,EntityDimensions)
+ float getMyRidingOffset(Entity)
+ float getNameTagOffsetY()
+ float ridingOffset(Entity)
- Vec3 getDefaultPassengerAttachmentPoint(Entity,Entity,EntityAttachments)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
- Vec3 getVehicleAttachmentPoint(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ void gameEvent(GameEvent,Entity)
+ void gameEvent(GameEvent)
- void gameEvent(Holder,Entity)
- void gameEvent(Holder)
- void playProjectileDeflectionSound(Projectile)
+ void setMaxUpStep(float)
```

</details>












<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ AttributeInstance getAttribute(Attribute)
- AttributeInstance getAttribute(Holder)
- boolean hasEffect(Holder)
+ boolean hasEffect(MobEffect)
- boolean removeEffect(Holder)
+ boolean removeEffect(MobEffect)
+ double getAttributeBaseValue(Attribute)
+ double getAttributeValue(Attribute)
- EntityDimensions getDefaultDimensions(Pose)
- float getAgeScale()
+ float getEyeHeight(Pose,EntityDimensions)
+ float getMyRidingOffset(Entity)
+ float getStandingEyeHeight(Pose,EntityDimensions)
- MobEffectInstance getEffect(Holder)
+ MobEffectInstance getEffect(MobEffect)
- MobEffectInstance removeEffectNoUpdate(Holder)
+ MobEffectInstance removeEffectNoUpdate(MobEffect)
+ void onAttributeUpdated(Attribute)
- void onAttributeUpdated(Holder)
```

</details>

<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- void stopInPlace()
```

</details>



<details>
<summary>
net.minecraft.world.entity.PathfinderMob
</summary>

```diff
+ boolean lambda$isPanicking$0(WrappedGoal)
```

</details>













<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeInstance
</summary>

```diff
+ Attribute getAttribute()
- Holder getAttribute()
- IllegalStateException lambda$save$2()
+ void <init>(Attribute,Consumer)
- void <init>(Holder,Consumer)
- void addOrUpdateTransientModifier(AttributeModifier)
```

</details>

<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeSupplier
</summary>

```diff
+ AttributeInstance createInstance(Consumer,Attribute)
- AttributeInstance createInstance(Consumer,Holder)
+ AttributeInstance getAttributeInstance(Attribute)
- AttributeInstance getAttributeInstance(Holder)
+ boolean hasAttribute(Attribute)
- boolean hasAttribute(Holder)
+ boolean hasModifier(Attribute,UUID)
- boolean hasModifier(Holder,UUID)
+ double getBaseValue(Attribute)
- double getBaseValue(Holder)
+ double getModifierValue(Attribute,UUID)
- double getModifierValue(Holder,UUID)
+ double getValue(Attribute)
- double getValue(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.Attributes
</summary>

```diff
+ Attribute register(String,Attribute)
- Holder bootstrap(Registry)
- Holder register(String,Attribute)
```

</details>

























































































<details>
<summary>
net.minecraft.world.entity.ai.goal.GoalSelector
</summary>

```diff
+ boolean lambda$removeGoal$2(Goal,WrappedGoal)
- boolean lambda$tick$2(Map$Entry)
+ Stream getRunningGoals()
+ void setNewGoalRate(int)
```

</details>









































<details>
<summary>
net.minecraft.world.entity.animal.axolotl.Axolotl
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
```

</details>













<details>
<summary>
net.minecraft.world.entity.animal.goat.Goat
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>





<details>
<summary>
net.minecraft.world.entity.animal.horse.ZombieHorse
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ float getPassengersRidingOffsetY(EntityDimensions,float)
- void <clinit>()
```

</details>








<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>













<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
```

</details>




<details>
<summary>
net.minecraft.world.entity.item.PrimedTnt
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.AbstractIllager
</summary>

```diff
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Drowned
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.EnderMan
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.Ghast
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.Guardian
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.Husk
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.Ravager
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Silverfish
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Spider
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
- Vec3 getVehicleAttachmentPoint(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Vex
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Witch
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.ZombieVillager
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.breeze.Breeze
</summary>

```diff
+ boolean withinMiddleCircleRange(Vec3)
+ boolean withinOuterCircleRange(Vec3)
- void playProjectileDeflectionSound(Projectile)
- void playWhirlSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.breeze.BreezeAi
</summary>

```diff
+ Optional lambda$initFightActivity$0(Breeze)
- Optional lambda$initIdleActivity$0(Breeze)
- void initIdleActivity(Brain)
- void updateActivity(Breeze)
```

</details>




<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
+ void deflect()
- void deflect(Entity)
```

</details>













<details>
<summary>
net.minecraft.world.entity.projectile.ThrownPotion
</summary>

```diff
- void makeAreaOfEffectCloud(ItemStack,Holder)
+ void makeAreaOfEffectCloud(ItemStack,Potion)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.WindCharge
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
```

</details>










<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecart
</summary>

```diff
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.vehicle.Boat
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>



















































































<details>
<summary>
net.minecraft.world.item.LeadItem
</summary>

```diff
- boolean lambda$bindPlayerMobs$0(Player,Mob)
```

</details>





















<details>
<summary>
net.minecraft.world.item.WritableBookItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.Potion
</summary>

```diff
- Holder byName(String)
+ Holder$Reference builtInRegistryHolder()
+ Potion byName(String)
- String getName(Holder,String)
+ String getName(String)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.PotionBrewing$Mix
</summary>

```diff
- boolean equals(Object)
- Holder from()
- Holder to()
- Ingredient ingredient()
- int hashCode()
- String toString()
- void <init>(Holder,Ingredient,Holder)
+ void <init>(Object,Ingredient,Object)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.Potions
</summary>

```diff
- Holder bootstrap(Registry)
- Holder register(ResourceKey,Potion)
- Holder register(String,Potion)
+ Potion register(ResourceKey,Potion)
+ Potion register(String,Potion)
```

</details>















































































































































<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.CandleBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.CartographyTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.CaveVinesBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CeilingHangingSignBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.CommandBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ComposterBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.DaylightDetectorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DecoratedPotBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.DragonEggBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ AbstractContainerMenu lambda$use$1(PlayerEnderChestContainer,int,Inventory,Player)
- AbstractContainerMenu lambda$useWithoutItem$1(PlayerEnderChestContainer,int,Inventory,Player)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.FletchingTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
- boolean lambda$useWithoutItem$2(Player,InteractionHand)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- void lambda$useWithoutItem$3(Player,ItemStack,InteractionHand)
- void lambda$useWithoutItem$4(Player,ItemStack)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.GrassBlock
</summary>

```diff
- BonemealableBlock$Type getType()
```

</details>




<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.MossBlock
</summary>

```diff
- BonemealableBlock$Type getType()
```

</details>









<details>
<summary>
net.minecraft.world.level.block.NoteBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>











<details>
<summary>
net.minecraft.world.level.block.RedStoneOreBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.RepeaterBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>

















<details>
<summary>
net.minecraft.world.level.block.SmithingTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.SweetBerryBushBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.TntBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ void lambda$use$0(InteractionHand,Player)
- void lambda$useItemOn$0(InteractionHand,Player)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.TrapDoorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.WallHangingSignBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
















<details>
<summary>
net.minecraft.world.level.block.entity.BeaconBlockEntity
</summary>

```diff
- Holder filterEffect(Holder)
- Holder loadEffect(CompoundTag,String)
+ MobEffect filterEffect(MobEffect)
+ MobEffect loadEffect(CompoundTag,String)
- void applyEffects(Level,BlockPos,int,Holder,Holder)
+ void applyEffects(Level,BlockPos,int,MobEffect,MobEffect)
- void lambda$storeEffect$0(CompoundTag,String,ResourceKey)
- void storeEffect(CompoundTag,String,Holder)
+ void storeEffect(CompoundTag,String,MobEffect)
```

</details>



























<details>
<summary>
net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
</summary>

```diff
+ boolean handleGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- boolean handleGameEvent(ServerLevel,Holder,GameEvent$Context,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
</summary>

```diff
+ boolean canReceiveVibration(ServerLevel,BlockPos,GameEvent,GameEvent$Context)
- boolean canReceiveVibration(ServerLevel,BlockPos,Holder,GameEvent$Context)
+ void onReceiveVibration(ServerLevel,BlockPos,GameEvent,Entity,Entity,float)
- void onReceiveVibration(ServerLevel,BlockPos,Holder,Entity,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
</summary>

```diff
+ boolean canReceiveVibration(ServerLevel,BlockPos,GameEvent,GameEvent$Context)
- boolean canReceiveVibration(ServerLevel,BlockPos,Holder,GameEvent$Context)
+ void onReceiveVibration(ServerLevel,BlockPos,GameEvent,Entity,Entity,float)
- void onReceiveVibration(ServerLevel,BlockPos,Holder,Entity,Entity,float)
```

</details>





















<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
+ InteractionResult use(Level,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(Level,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,Level,Player,InteractionHand,BlockHitResult)
```

</details>


























































































<details>
<summary>
net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
</summary>

```diff
+ boolean visitInRangeListeners(GameEvent,Vec3,GameEvent$Context,GameEventListenerRegistry$ListenerVisitor)
- boolean visitInRangeListeners(Holder,Vec3,GameEvent$Context,GameEventListenerRegistry$ListenerVisitor)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.GameEvent
</summary>

```diff
- boolean equals(Object)
+ boolean is(TagKey)
+ GameEvent register(String,int)
+ GameEvent register(String)
- Holder bootstrap(Registry)
+ Holder$Reference builtInRegistryHolder()
- Holder$Reference register(String,int)
- Holder$Reference register(String)
+ int getNotificationRadius()
- int hashCode()
- int notificationRadius()
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
</summary>

```diff
+ GameEvent gameEvent()
- Holder gameEvent()
+ void <init>(GameEvent,Vec3,GameEvent$Context,GameEventListener,Vec3)
- void <init>(Holder,Vec3,GameEvent$Context,GameEventListener,Vec3)
```

</details>

<details>
<summary>
net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
</summary>

```diff
+ boolean visitInRangeListeners(GameEvent,Vec3,GameEvent$Context,GameEventListenerRegistry$ListenerVisitor)
- boolean visitInRangeListeners(Holder,Vec3,GameEvent$Context,GameEventListenerRegistry$ListenerVisitor)
```

</details>








































































































































































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.animation.definitions.ArmadilloAnimation
+ net.minecraft.client.animation.definitions.BatAnimation
- net.minecraft.client.animation.definitions.BreezeAnimation
+ net.minecraft.client.animation.definitions.CamelAnimation
- net.minecraft.client.animation.definitions.FrogAnimation
+ net.minecraft.client.animation.definitions.package-info
+ net.minecraft.client.animation.definitions.SnifferAnimation
- net.minecraft.client.animation.definitions.WardenAnimation
- net.minecraft.client.animation.package-info
+ net.minecraft.client.color.block.BlockColor
- net.minecraft.client.color.block.BlockColors
+ net.minecraft.client.color.block.BlockTintCache
- net.minecraft.client.color.block.BlockTintCache$CacheData
+ net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
- net.minecraft.client.color.block.package-info
+ net.minecraft.client.color.item.ItemColor
- net.minecraft.client.color.item.ItemColors
+ net.minecraft.client.color.item.package-info
- net.minecraft.client.gui.ComponentPath
+ net.minecraft.client.gui.ComponentPath$Leaf
- net.minecraft.client.gui.ComponentPath$Path
- net.minecraft.client.gui.components.AbstractButton
+ net.minecraft.client.gui.components.AbstractContainerWidget
- net.minecraft.client.gui.components.AbstractOptionSliderButton
+ net.minecraft.client.gui.components.AbstractScrollWidget
- net.minecraft.client.gui.components.AbstractSelectionList
+ net.minecraft.client.gui.components.AbstractSelectionList$1
- net.minecraft.client.gui.components.AbstractSelectionList$Entry
+ net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
- net.minecraft.client.gui.components.AbstractSliderButton
+ net.minecraft.client.gui.components.AbstractStringWidget
- net.minecraft.client.gui.components.AbstractWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.BossHealthOverlay$1
+ net.minecraft.client.gui.components.Button
- net.minecraft.client.gui.components.Button$Builder
+ net.minecraft.client.gui.components.Button$CreateNarration
- net.minecraft.client.gui.components.Button$OnPress
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.ChatComponent$DelayedMessageDeletion
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.Checkbox$Builder
+ net.minecraft.client.gui.components.Checkbox$OnValueChange
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.CommonButtons
+ net.minecraft.client.gui.components.ComponentRenderUtils
- net.minecraft.client.gui.components.ContainerObjectSelectionList
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$1
- net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
+ net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$Builder
+ net.minecraft.client.gui.components.CycleButton$OnValueChange
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
+ net.minecraft.client.gui.components.debugchart.AbstractDebugChart
- net.minecraft.client.gui.components.debugchart.BandwidthDebugChart
+ net.minecraft.client.gui.components.debugchart.FpsDebugChart
- net.minecraft.client.gui.components.debugchart.PingDebugChart
+ net.minecraft.client.gui.components.debugchart.TpsDebugChart
+ net.minecraft.client.gui.components.DebugScreenOverlay
- net.minecraft.client.gui.components.DebugScreenOverlay$1
+ net.minecraft.client.gui.components.DebugScreenOverlay$AllocationRateCalculator
- net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.events.AbstractContainerEventHandler
+ net.minecraft.client.gui.components.events.ContainerEventHandler
- net.minecraft.client.gui.components.events.GuiEventListener
+ net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.FittingMultiLineTextWidget
- net.minecraft.client.gui.components.FocusableTextWidget
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.ImageWidget
+ net.minecraft.client.gui.components.ImageWidget$Sprite
- net.minecraft.client.gui.components.ImageWidget$Texture
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.gui.components.LoadingDotsWidget
+ net.minecraft.client.gui.components.LockIconButton
- net.minecraft.client.gui.components.LockIconButton$Icon
+ net.minecraft.client.gui.components.LogoRenderer
- net.minecraft.client.gui.components.MultiLineEditBox
+ net.minecraft.client.gui.components.MultiLineLabel
- net.minecraft.client.gui.components.MultiLineLabel$1
+ net.minecraft.client.gui.components.MultiLineLabel$2
- net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
+ net.minecraft.client.gui.components.MultilineTextField
- net.minecraft.client.gui.components.MultilineTextField$1
+ net.minecraft.client.gui.components.MultilineTextField$StringView
+ net.minecraft.client.gui.components.MultiLineTextWidget
- net.minecraft.client.gui.components.MultiLineTextWidget$CacheKey
- net.minecraft.client.gui.components.ObjectSelectionList
+ net.minecraft.client.gui.components.ObjectSelectionList$Entry
- net.minecraft.client.gui.components.OptionsList
+ net.minecraft.client.gui.components.OptionsList$Entry
- net.minecraft.client.gui.components.package-info
- net.minecraft.client.gui.components.PlainTextButton
+ net.minecraft.client.gui.components.PlayerFaceRenderer
- net.minecraft.client.gui.components.PlayerSkinWidget
+ net.minecraft.client.gui.components.PlayerSkinWidget$Model
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$HealthState
- net.minecraft.client.gui.components.PlayerTabOverlay$ScoreDisplayEntry
+ net.minecraft.client.gui.components.PopupScreen
- net.minecraft.client.gui.components.PopupScreen$Builder
+ net.minecraft.client.gui.components.PopupScreen$ButtonOption
- net.minecraft.client.gui.components.Renderable
- net.minecraft.client.gui.components.spectator.package-info
+ net.minecraft.client.gui.components.spectator.SpectatorGui
+ net.minecraft.client.gui.components.SplashRenderer
- net.minecraft.client.gui.components.SpriteIconButton
+ net.minecraft.client.gui.components.SpriteIconButton$Builder
- net.minecraft.client.gui.components.SpriteIconButton$CenteredIcon
+ net.minecraft.client.gui.components.SpriteIconButton$TextAndIcon
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.StringWidget
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.TabButton
+ net.minecraft.client.gui.components.TabOrderedElement
+ net.minecraft.client.gui.components.tabs.GridLayoutTab
- net.minecraft.client.gui.components.tabs.package-info
- net.minecraft.client.gui.components.tabs.Tab
+ net.minecraft.client.gui.components.tabs.TabManager
- net.minecraft.client.gui.components.tabs.TabNavigationBar
+ net.minecraft.client.gui.components.tabs.TabNavigationBar$Builder
+ net.minecraft.client.gui.components.toasts.AdvancementToast
+ net.minecraft.client.gui.components.toasts.package-info
- net.minecraft.client.gui.components.toasts.RecipeToast
+ net.minecraft.client.gui.components.toasts.SystemToast
- net.minecraft.client.gui.components.toasts.SystemToast$SystemToastId
+ net.minecraft.client.gui.components.toasts.Toast
- net.minecraft.client.gui.components.toasts.Toast$Visibility
+ net.minecraft.client.gui.components.toasts.ToastComponent
- net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
+ net.minecraft.client.gui.components.toasts.TutorialToast
- net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.Tooltip
+ net.minecraft.client.gui.components.Whence
- net.minecraft.client.gui.components.WidgetSprites
+ net.minecraft.client.gui.Font
- net.minecraft.client.gui.font.AllMissingGlyphProvider
+ net.minecraft.client.gui.font.CodepointMap
- net.minecraft.client.gui.font.CodepointMap$Output
+ net.minecraft.client.gui.font.FontManager
- net.minecraft.client.gui.font.FontManager$BuilderId
+ net.minecraft.client.gui.font.FontManager$BuilderResult
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
+ net.minecraft.client.gui.font.providers.BitmapProvider$Definition
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph$1
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition
+ net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Loader
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Reference
+ net.minecraft.client.gui.font.providers.GlyphProviderType
- net.minecraft.client.gui.font.providers.package-info
- net.minecraft.client.gui.font.providers.ProviderReferenceDefinition
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition$Shift
+ net.minecraft.client.gui.font.providers.UnihexProvider
- net.minecraft.client.gui.font.providers.UnihexProvider$ByteContents
+ net.minecraft.client.gui.font.providers.UnihexProvider$Definition
- net.minecraft.client.gui.font.providers.UnihexProvider$Dimensions
+ net.minecraft.client.gui.font.providers.UnihexProvider$Glyph
- net.minecraft.client.gui.font.providers.UnihexProvider$Glyph$1
+ net.minecraft.client.gui.font.providers.UnihexProvider$IntContents
- net.minecraft.client.gui.font.providers.UnihexProvider$LineData
+ net.minecraft.client.gui.font.providers.UnihexProvider$OverrideRange
- net.minecraft.client.gui.font.providers.UnihexProvider$ReaderOutput
+ net.minecraft.client.gui.font.providers.UnihexProvider$ShortContents
+ net.minecraft.client.gui.font.TextFieldHelper
- net.minecraft.client.gui.font.TextFieldHelper$1
+ net.minecraft.client.gui.font.TextFieldHelper$CursorStep
- net.minecraft.client.gui.Font$DisplayMode
+ net.minecraft.client.gui.Font$StringRenderOutput
- net.minecraft.client.gui.Gui
+ net.minecraft.client.gui.Gui$1DisplayEntry
- net.minecraft.client.gui.Gui$HeartType
+ net.minecraft.client.gui.GuiGraphics
- net.minecraft.client.gui.GuiGraphics$ScissorStack
+ net.minecraft.client.gui.GuiSpriteManager
- net.minecraft.client.gui.LayeredDraw
+ net.minecraft.client.gui.layouts.AbstractLayout
- net.minecraft.client.gui.layouts.AbstractLayout$AbstractChildWrapper
+ net.minecraft.client.gui.layouts.CommonLayouts
- net.minecraft.client.gui.layouts.EqualSpacingLayout
+ net.minecraft.client.gui.layouts.EqualSpacingLayout$1
- net.minecraft.client.gui.layouts.EqualSpacingLayout$ChildContainer
+ net.minecraft.client.gui.layouts.EqualSpacingLayout$Orientation
- net.minecraft.client.gui.layouts.FrameLayout
+ net.minecraft.client.gui.layouts.FrameLayout$ChildContainer
- net.minecraft.client.gui.layouts.GridLayout
+ net.minecraft.client.gui.layouts.GridLayout$CellInhabitant
- net.minecraft.client.gui.layouts.GridLayout$RowHelper
+ net.minecraft.client.gui.layouts.HeaderAndFooterLayout
- net.minecraft.client.gui.layouts.Layout
+ net.minecraft.client.gui.layouts.LayoutElement
- net.minecraft.client.gui.layouts.LayoutSettings
+ net.minecraft.client.gui.layouts.LayoutSettings$LayoutSettingsImpl
- net.minecraft.client.gui.layouts.LinearLayout
+ net.minecraft.client.gui.layouts.LinearLayout$1
- net.minecraft.client.gui.layouts.LinearLayout$Orientation
- net.minecraft.client.gui.layouts.package-info
+ net.minecraft.client.gui.layouts.SpacerElement
- net.minecraft.client.gui.MapRenderer
+ net.minecraft.client.gui.MapRenderer$MapInstance
+ net.minecraft.client.gui.narration.NarratableEntry
- net.minecraft.client.gui.narration.NarratableEntry$NarrationPriority
+ net.minecraft.client.gui.narration.NarratedElementType
- net.minecraft.client.gui.narration.NarrationElementOutput
+ net.minecraft.client.gui.narration.NarrationSupplier
- net.minecraft.client.gui.narration.NarrationThunk
- net.minecraft.client.gui.narration.package-info
+ net.minecraft.client.gui.narration.ScreenNarrationCollector
- net.minecraft.client.gui.narration.ScreenNarrationCollector$1
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$EntryKey
- net.minecraft.client.gui.narration.ScreenNarrationCollector$NarrationEntry
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$Output
+ net.minecraft.client.gui.navigation.CommonInputs
- net.minecraft.client.gui.navigation.FocusNavigationEvent
+ net.minecraft.client.gui.navigation.FocusNavigationEvent$ArrowNavigation
- net.minecraft.client.gui.navigation.FocusNavigationEvent$InitialFocus
+ net.minecraft.client.gui.navigation.FocusNavigationEvent$TabNavigation
- net.minecraft.client.gui.navigation.package-info
- net.minecraft.client.gui.navigation.ScreenAxis
+ net.minecraft.client.gui.navigation.ScreenAxis$1
- net.minecraft.client.gui.navigation.ScreenDirection
+ net.minecraft.client.gui.navigation.ScreenDirection$1
- net.minecraft.client.gui.navigation.ScreenPosition
+ net.minecraft.client.gui.navigation.ScreenPosition$1
- net.minecraft.client.gui.navigation.ScreenRectangle
+ net.minecraft.client.gui.navigation.ScreenRectangle$1
+ net.minecraft.client.gui.package-info
- net.minecraft.client.gui.screens.AccessibilityOnboardingScreen
+ net.minecraft.client.gui.screens.AccessibilityOptionsScreen
+ net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- net.minecraft.client.gui.screens.achievement.StatsUpdateListener
+ net.minecraft.client.gui.screens.advancements.AdvancementsScreen
- net.minecraft.client.gui.screens.advancements.AdvancementTab
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType
- net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType$Sprites
- net.minecraft.client.gui.screens.advancements.AdvancementWidget
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
- net.minecraft.client.gui.screens.advancements.AdvancementWidgetType$1
- net.minecraft.client.gui.screens.advancements.package-info
- net.minecraft.client.gui.screens.AlertScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
+ net.minecraft.client.gui.screens.BanNoticeScreens
- net.minecraft.client.gui.screens.ChatOptionsScreen
+ net.minecraft.client.gui.screens.ChatScreen
- net.minecraft.client.gui.screens.ChatScreen$1
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
+ net.minecraft.client.gui.screens.ConnectScreen$2
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.KeyBindsList
+ net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry
- net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry$1
+ net.minecraft.client.gui.screens.controls.KeyBindsList$Entry
- net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry
+ net.minecraft.client.gui.screens.controls.KeyBindsScreen
- net.minecraft.client.gui.screens.controls.package-info
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- net.minecraft.client.gui.screens.CreditsAndAttributionScreen
+ net.minecraft.client.gui.screens.DatapackLoadFailureScreen
- net.minecraft.client.gui.screens.DeathScreen
+ net.minecraft.client.gui.screens.DeathScreen$TitleConfirmScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ net.minecraft.client.gui.screens.debug.package-info
- net.minecraft.client.gui.screens.DemoIntroScreen
+ net.minecraft.client.gui.screens.DirectJoinServerScreen
- net.minecraft.client.gui.screens.DisconnectedScreen
+ net.minecraft.client.gui.screens.EditServerScreen
- net.minecraft.client.gui.screens.ErrorScreen
+ net.minecraft.client.gui.screens.FaviconTexture
- net.minecraft.client.gui.screens.GenericDirtMessageScreen
+ net.minecraft.client.gui.screens.GenericWaitingScreen
- net.minecraft.client.gui.screens.InBedChatScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
+ net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
- net.minecraft.client.gui.screens.inventory.AbstractSignEditScreen
+ net.minecraft.client.gui.screens.inventory.AnvilScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$1
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
+ net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
- net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
- net.minecraft.client.gui.screens.inventory.BookViewScreen
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$1
- net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$WritableBookAccess
- net.minecraft.client.gui.screens.inventory.BookViewScreen$WrittenBookAccess
+ net.minecraft.client.gui.screens.inventory.BrewingStandScreen
- net.minecraft.client.gui.screens.inventory.CartographyTableScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.ContainerScreen
- net.minecraft.client.gui.screens.inventory.CrafterScreen
+ net.minecraft.client.gui.screens.inventory.CrafterScreen$1
- net.minecraft.client.gui.screens.inventory.CraftingScreen
+ net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- net.minecraft.client.gui.screens.inventory.CyclingSlotBackground
+ net.minecraft.client.gui.screens.inventory.DispenserScreen
- net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
+ net.minecraft.client.gui.screens.inventory.EnchantmentNames
- net.minecraft.client.gui.screens.inventory.EnchantmentScreen
+ net.minecraft.client.gui.screens.inventory.FurnaceScreen
- net.minecraft.client.gui.screens.inventory.GrindstoneScreen
+ net.minecraft.client.gui.screens.inventory.HangingSignEditScreen
- net.minecraft.client.gui.screens.inventory.HopperScreen
+ net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
- net.minecraft.client.gui.screens.inventory.InventoryScreen
+ net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.LecternScreen
+ net.minecraft.client.gui.screens.inventory.LecternScreen$1
- net.minecraft.client.gui.screens.inventory.LoomScreen
+ net.minecraft.client.gui.screens.inventory.MenuAccess
- net.minecraft.client.gui.screens.inventory.MerchantScreen
+ net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
- net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.package-info
+ net.minecraft.client.gui.screens.inventory.PageButton
- net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
+ net.minecraft.client.gui.screens.inventory.SignEditScreen
- net.minecraft.client.gui.screens.inventory.SmithingScreen
+ net.minecraft.client.gui.screens.inventory.SmokerScreen
- net.minecraft.client.gui.screens.inventory.StonecutterScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
+ net.minecraft.client.gui.screens.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTextTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipPositioner
+ net.minecraft.client.gui.screens.inventory.tooltip.DefaultTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.MenuTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.package-info
+ net.minecraft.client.gui.screens.inventory.tooltip.TooltipRenderUtil
+ net.minecraft.client.gui.screens.LanguageSelectScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingDotsText
- net.minecraft.client.gui.screens.LoadingOverlay
+ net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.MenuScreens
+ net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
- net.minecraft.client.gui.screens.MouseSettingsScreen
+ net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
- net.minecraft.client.gui.screens.multiplayer.Realms32bitWarningScreen
+ net.minecraft.client.gui.screens.multiplayer.SafetyScreen
- net.minecraft.client.gui.screens.multiplayer.ServerReconfigScreen
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$1
+ net.minecraft.client.gui.screens.NoticeWithLinkScreen
- net.minecraft.client.gui.screens.OnlineOptionsScreen
+ net.minecraft.client.gui.screens.OptionsScreen
- net.minecraft.client.gui.screens.OptionsSubScreen
+ net.minecraft.client.gui.screens.OutOfMemoryScreen
- net.minecraft.client.gui.screens.Overlay
+ net.minecraft.client.gui.screens.PauseScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ net.minecraft.client.gui.screens.ProgressScreen
- net.minecraft.client.gui.screens.ReceivingLevelScreen
+ net.minecraft.client.gui.screens.RecoverWorldDataScreen
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.Screen$DeferredTooltipRendering
- net.minecraft.client.gui.screens.Screen$NarratableSearchResult
+ net.minecraft.client.gui.screens.ShareToLanScreen
- net.minecraft.client.gui.screens.SimpleOptionsSubScreen
+ net.minecraft.client.gui.screens.SkinCustomizationScreen
- net.minecraft.client.gui.screens.SoundOptionsScreen
+ net.minecraft.client.gui.screens.TitleScreen
- net.minecraft.client.gui.screens.TitleScreen$WarningLabel
+ net.minecraft.client.gui.screens.UnsupportedGraphicsWarningScreen
- net.minecraft.client.gui.screens.UnsupportedGraphicsWarningScreen$ButtonOption
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.WinScreen$CreditsReader
- net.minecraft.client.model.ArmadilloModel
+ net.minecraft.client.model.ArmedModel
- net.minecraft.client.model.ArmorStandArmorModel
+ net.minecraft.client.model.ArmorStandModel
- net.minecraft.client.model.AxolotlModel
+ net.minecraft.client.model.BatModel
- net.minecraft.client.model.BeeModel
+ net.minecraft.client.model.BlazeModel
- net.minecraft.client.model.BoatModel
+ net.minecraft.client.model.BookModel
- net.minecraft.client.model.BreezeModel
+ net.minecraft.client.model.CamelModel
- net.minecraft.client.model.CatModel
+ net.minecraft.client.model.ChestBoatModel
+ net.minecraft.client.model.ChestedHorseModel
- net.minecraft.client.model.ChestRaftModel
- net.minecraft.client.model.ChickenModel
+ net.minecraft.client.model.CodModel
- net.minecraft.client.model.ColorableAgeableListModel
+ net.minecraft.client.model.ColorableHierarchicalModel
- net.minecraft.client.model.CowModel
+ net.minecraft.client.model.CreeperModel
- net.minecraft.client.model.DolphinModel
+ net.minecraft.client.model.dragon.DragonHeadModel
- net.minecraft.client.model.dragon.package-info
+ net.minecraft.client.model.DrownedModel
- net.minecraft.client.model.ElytraModel
+ net.minecraft.client.model.EndermanModel
- net.minecraft.client.model.EndermiteModel
+ net.minecraft.client.model.EntityModel
- net.minecraft.client.model.EvokerFangsModel
+ net.minecraft.client.model.FoxModel
- net.minecraft.client.model.FrogModel
- net.minecraft.client.model.geom.builders.CubeDefinition
+ net.minecraft.client.model.geom.builders.CubeDeformation
- net.minecraft.client.model.geom.builders.CubeListBuilder
+ net.minecraft.client.model.geom.builders.LayerDefinition
- net.minecraft.client.model.geom.builders.MaterialDefinition
+ net.minecraft.client.model.geom.builders.MeshDefinition
- net.minecraft.client.model.geom.builders.package-info
- net.minecraft.client.model.geom.builders.PartDefinition
+ net.minecraft.client.model.geom.builders.UVPair
+ net.minecraft.client.model.geom.EntityModelSet
- net.minecraft.client.model.geom.LayerDefinitions
+ net.minecraft.client.model.geom.ModelLayerLocation
- net.minecraft.client.model.geom.ModelLayers
+ net.minecraft.client.model.geom.ModelPart
- net.minecraft.client.model.geom.ModelPart$Cube
+ net.minecraft.client.model.geom.ModelPart$Polygon
- net.minecraft.client.model.geom.ModelPart$Vertex
+ net.minecraft.client.model.geom.ModelPart$Visitor
+ net.minecraft.client.model.geom.package-info
- net.minecraft.client.model.geom.PartNames
+ net.minecraft.client.model.geom.PartPose
+ net.minecraft.client.model.GhastModel
- net.minecraft.client.model.GiantZombieModel
+ net.minecraft.client.model.GoatModel
- net.minecraft.client.model.GuardianModel
+ net.minecraft.client.model.HeadedModel
- net.minecraft.client.model.HierarchicalModel
+ net.minecraft.client.model.HoglinModel
- net.minecraft.client.model.HorseModel
+ net.minecraft.client.model.HumanoidArmorModel
- net.minecraft.client.model.HumanoidModel
+ net.minecraft.client.model.HumanoidModel$1
- net.minecraft.client.model.HumanoidModel$ArmPose
+ net.minecraft.client.model.IllagerModel
- net.minecraft.client.model.IronGolemModel
+ net.minecraft.client.model.LavaSlimeModel
- net.minecraft.client.model.LeashKnotModel
+ net.minecraft.client.model.ListModel
- net.minecraft.client.model.LlamaModel
+ net.minecraft.client.model.LlamaSpitModel
- net.minecraft.client.model.MinecartModel
+ net.minecraft.client.model.Model
- net.minecraft.client.model.ModelUtils
+ net.minecraft.client.model.OcelotModel
- net.minecraft.client.model.package-info
- net.minecraft.client.model.PandaModel
+ net.minecraft.client.model.ParrotModel
- net.minecraft.client.model.ParrotModel$1
+ net.minecraft.client.model.ParrotModel$State
- net.minecraft.client.model.PhantomModel
- net.minecraft.client.model.PiglinHeadModel
+ net.minecraft.client.model.PiglinModel
+ net.minecraft.client.model.PigModel
- net.minecraft.client.model.PlayerModel
+ net.minecraft.client.model.PolarBearModel
- net.minecraft.client.model.PufferfishBigModel
+ net.minecraft.client.model.PufferfishMidModel
- net.minecraft.client.model.PufferfishSmallModel
+ net.minecraft.client.model.QuadrupedModel
- net.minecraft.client.model.RabbitModel
+ net.minecraft.client.model.RaftModel
- net.minecraft.client.model.RavagerModel
+ net.minecraft.client.model.SalmonModel
- net.minecraft.client.model.SheepFurModel
+ net.minecraft.client.model.SheepModel
- net.minecraft.client.model.ShieldModel
+ net.minecraft.client.model.ShulkerBulletModel
- net.minecraft.client.model.ShulkerModel
+ net.minecraft.client.model.SilverfishModel
- net.minecraft.client.model.SkeletonModel
+ net.minecraft.client.model.SkullModel
- net.minecraft.client.model.SkullModelBase
+ net.minecraft.client.model.SlimeModel
- net.minecraft.client.model.SnifferModel
+ net.minecraft.client.model.SnowGolemModel
- net.minecraft.client.model.SpiderModel
+ net.minecraft.client.model.SquidModel
- net.minecraft.client.model.StriderModel
+ net.minecraft.client.model.TadpoleModel
- net.minecraft.client.model.TridentModel
+ net.minecraft.client.model.TropicalFishModelA
- net.minecraft.client.model.TropicalFishModelB
+ net.minecraft.client.model.TurtleModel
- net.minecraft.client.model.VexModel
+ net.minecraft.client.model.VillagerHeadModel
- net.minecraft.client.model.VillagerModel
+ net.minecraft.client.model.WardenModel
- net.minecraft.client.model.WaterPatchModel
+ net.minecraft.client.model.WindChargeModel
- net.minecraft.client.model.WitchModel
+ net.minecraft.client.model.WitherBossModel
- net.minecraft.client.model.WolfModel
+ net.minecraft.client.model.ZombieModel
- net.minecraft.client.model.ZombieVillagerModel
+ net.minecraft.client.multiplayer.AccountProfileKeyPairManager
- net.minecraft.client.multiplayer.ChunkBatchSizeCalculator
+ net.minecraft.client.multiplayer.ClientAdvancements
- net.minecraft.client.multiplayer.ClientAdvancements$Listener
+ net.minecraft.client.multiplayer.ClientChunkCache
- net.minecraft.client.multiplayer.ClientChunkCache$Storage
+ net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl
- net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl$DeferredPacket
+ net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen
- net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen$PendingRequest
+ net.minecraft.client.multiplayer.ClientConfigurationPacketListenerImpl
- net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
+ net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl$State
- net.minecraft.client.multiplayer.ClientLevel
+ net.minecraft.client.multiplayer.ClientLevel$1
- net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
+ net.minecraft.client.multiplayer.ClientLevel$EntityCallbacks
- net.minecraft.client.multiplayer.ClientPacketListener
+ net.minecraft.client.multiplayer.ClientPacketListener$1
- net.minecraft.client.multiplayer.ClientRegistryLayer
+ net.minecraft.client.multiplayer.ClientSuggestionProvider
- net.minecraft.client.multiplayer.ClientSuggestionProvider$1
+ net.minecraft.client.multiplayer.CommonListenerCookie
- net.minecraft.client.multiplayer.LegacyServerPinger
+ net.minecraft.client.multiplayer.LegacyServerPinger$Output
- net.minecraft.client.multiplayer.LevelLoadStatusManager
+ net.minecraft.client.multiplayer.LevelLoadStatusManager$1
- net.minecraft.client.multiplayer.LevelLoadStatusManager$Status
+ net.minecraft.client.multiplayer.MultiPlayerGameMode
- net.minecraft.client.multiplayer.PingDebugMonitor
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.ProfileKeyPairManager
+ net.minecraft.client.multiplayer.ProfileKeyPairManager$1
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerData$State
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
- net.minecraft.client.renderer.entity.AxolotlRenderer
+ net.minecraft.client.renderer.entity.BatRenderer
- net.minecraft.client.renderer.entity.BeeRenderer
+ net.minecraft.client.renderer.entity.BlazeRenderer
- net.minecraft.client.renderer.entity.BoatRenderer
+ net.minecraft.client.renderer.entity.BreezeRenderer
- net.minecraft.client.renderer.entity.CamelRenderer
+ net.minecraft.client.renderer.entity.CatRenderer
- net.minecraft.client.renderer.entity.CaveSpiderRenderer
+ net.minecraft.client.renderer.entity.ChestedHorseRenderer
- net.minecraft.client.renderer.entity.ChickenRenderer
+ net.minecraft.client.renderer.entity.CodRenderer
- net.minecraft.client.renderer.entity.CowRenderer
+ net.minecraft.client.renderer.entity.CreeperRenderer
- net.minecraft.client.renderer.entity.DisplayRenderer
+ net.minecraft.client.renderer.entity.DisplayRenderer$1
- net.minecraft.client.renderer.entity.DisplayRenderer$BlockDisplayRenderer
+ net.minecraft.client.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- net.minecraft.client.renderer.entity.DisplayRenderer$TextDisplayRenderer
+ net.minecraft.client.renderer.entity.DolphinRenderer
- net.minecraft.client.renderer.entity.DragonFireballRenderer
+ net.minecraft.client.renderer.entity.DrownedRenderer
- net.minecraft.client.renderer.entity.ElderGuardianRenderer
+ net.minecraft.client.renderer.entity.EndCrystalRenderer
- net.minecraft.client.renderer.entity.EnderDragonRenderer
+ net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
- net.minecraft.client.renderer.entity.EndermanRenderer
+ net.minecraft.client.renderer.entity.EndermiteRenderer
- net.minecraft.client.renderer.entity.EntityRenderDispatcher
+ net.minecraft.client.renderer.entity.EntityRenderer
- net.minecraft.client.renderer.entity.EntityRendererProvider
+ net.minecraft.client.renderer.entity.EntityRendererProvider$Context
- net.minecraft.client.renderer.entity.EntityRenderers
+ net.minecraft.client.renderer.entity.EvokerFangsRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer$1
- net.minecraft.client.renderer.entity.ExperienceOrbRenderer
+ net.minecraft.client.renderer.entity.FallingBlockRenderer
- net.minecraft.client.renderer.entity.FireworkEntityRenderer
+ net.minecraft.client.renderer.entity.FishingHookRenderer
- net.minecraft.client.renderer.entity.FoxRenderer
+ net.minecraft.client.renderer.entity.FrogRenderer
- net.minecraft.client.renderer.entity.GhastRenderer
+ net.minecraft.client.renderer.entity.GiantMobRenderer
- net.minecraft.client.renderer.entity.GlowSquidRenderer
+ net.minecraft.client.renderer.entity.GoatRenderer
- net.minecraft.client.renderer.entity.GuardianRenderer
+ net.minecraft.client.renderer.entity.HoglinRenderer
- net.minecraft.client.renderer.entity.HorseRenderer
+ net.minecraft.client.renderer.entity.HumanoidMobRenderer
- net.minecraft.client.renderer.entity.HuskRenderer
+ net.minecraft.client.renderer.entity.IllagerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer$1
- net.minecraft.client.renderer.entity.IronGolemRenderer
+ net.minecraft.client.renderer.entity.ItemEntityRenderer
- net.minecraft.client.renderer.entity.ItemFrameRenderer
+ net.minecraft.client.renderer.entity.ItemRenderer
- net.minecraft.client.renderer.entity.layers.ArrowLayer
+ net.minecraft.client.renderer.entity.layers.BeeStingerLayer
- net.minecraft.client.renderer.entity.layers.BreezeEyesLayer
+ net.minecraft.client.renderer.entity.layers.BreezeWindLayer
- net.minecraft.client.renderer.entity.layers.CapeLayer
+ net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
- net.minecraft.client.renderer.entity.layers.CatCollarLayer
+ net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
- net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
+ net.minecraft.client.renderer.entity.layers.CustomHeadLayer
- net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
+ net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
- net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
+ net.minecraft.client.renderer.entity.layers.ElytraLayer
- net.minecraft.client.renderer.entity.layers.EnderEyesLayer
+ net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
- net.minecraft.client.renderer.entity.layers.EyesLayer
+ net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
- net.minecraft.client.renderer.entity.layers.HorseArmorLayer
+ net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
- net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
+ net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
- net.minecraft.client.renderer.entity.layers.ItemInHandLayer
+ net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
- net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
+ net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
- net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
+ net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
- net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
+ net.minecraft.client.renderer.entity.layers.RenderLayer
- net.minecraft.client.renderer.entity.layers.SaddleLayer
+ net.minecraft.client.renderer.entity.layers.SheepFurLayer
- net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
+ net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
- net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
+ net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
- net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
+ net.minecraft.client.renderer.entity.layers.StrayClothingLayer
- net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
+ net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
- net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer$1
+ net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
- net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer
+ net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$AlphaFunction
- net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$DrawSelector
+ net.minecraft.client.renderer.entity.layers.WitchItemLayer
- net.minecraft.client.renderer.entity.layers.WitherArmorLayer
- net.minecraft.client.renderer.entity.LeashKnotRenderer
+ net.minecraft.client.renderer.entity.LightningBoltRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer$1
- net.minecraft.client.renderer.entity.LlamaRenderer
+ net.minecraft.client.renderer.entity.LlamaRenderer$1
- net.minecraft.client.renderer.entity.LlamaSpitRenderer
+ net.minecraft.client.renderer.entity.MagmaCubeRenderer
- net.minecraft.client.renderer.entity.MinecartRenderer
+ net.minecraft.client.renderer.entity.MobRenderer
- net.minecraft.client.renderer.entity.MushroomCowRenderer
+ net.minecraft.client.renderer.entity.NoopRenderer
- net.minecraft.client.renderer.entity.OcelotRenderer
+ net.minecraft.client.renderer.entity.PaintingRenderer
- net.minecraft.client.renderer.entity.PandaRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer$1
+ net.minecraft.client.renderer.entity.PhantomRenderer
+ net.minecraft.client.renderer.entity.PiglinRenderer
- net.minecraft.client.renderer.entity.PigRenderer
- net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.PolarBearRenderer
- net.minecraft.client.renderer.entity.PufferfishRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer$1
+ net.minecraft.client.renderer.entity.RavagerRenderer
- net.minecraft.client.renderer.entity.RenderLayerParent
+ net.minecraft.client.renderer.entity.SalmonRenderer
- net.minecraft.client.renderer.entity.SheepRenderer
+ net.minecraft.client.renderer.entity.ShulkerBulletRenderer
- net.minecraft.client.renderer.entity.ShulkerRenderer
+ net.minecraft.client.renderer.entity.SilverfishRenderer
- net.minecraft.client.renderer.entity.SkeletonRenderer
+ net.minecraft.client.renderer.entity.SlimeRenderer
- net.minecraft.client.renderer.entity.SnifferRenderer
+ net.minecraft.client.renderer.entity.SnowGolemRenderer
- net.minecraft.client.renderer.entity.SpectralArrowRenderer
+ net.minecraft.client.renderer.entity.SpiderRenderer
- net.minecraft.client.renderer.entity.SquidRenderer
+ net.minecraft.client.renderer.entity.StrayRenderer
- net.minecraft.client.renderer.entity.StriderRenderer
+ net.minecraft.client.renderer.entity.TadpoleRenderer
- net.minecraft.client.renderer.entity.ThrownItemRenderer
+ net.minecraft.client.renderer.entity.ThrownTridentRenderer
- net.minecraft.client.renderer.entity.TippableArrowRenderer
+ net.minecraft.client.renderer.entity.TntMinecartRenderer
- net.minecraft.client.renderer.entity.TntRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer
- net.minecraft.client.renderer.entity.TropicalFishRenderer$1
+ net.minecraft.client.renderer.entity.TurtleRenderer
- net.minecraft.client.renderer.entity.UndeadHorseRenderer
+ net.minecraft.client.renderer.entity.VexRenderer
- net.minecraft.client.renderer.entity.VillagerRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer$1
+ net.minecraft.client.renderer.entity.WanderingTraderRenderer
- net.minecraft.client.renderer.entity.WardenRenderer
+ net.minecraft.client.renderer.entity.WindChargeRenderer
- net.minecraft.client.renderer.entity.WitchRenderer
+ net.minecraft.client.renderer.entity.WitherBossRenderer
- net.minecraft.client.renderer.entity.WitherSkeletonRenderer
+ net.minecraft.client.renderer.entity.WitherSkullRenderer
- net.minecraft.client.renderer.entity.WolfRenderer
+ net.minecraft.client.renderer.entity.ZoglinRenderer
- net.minecraft.client.renderer.entity.ZombieRenderer
+ net.minecraft.client.renderer.entity.ZombieVillagerRenderer
- net.minecraft.core.dispenser.DispenseItemBehavior$28
+ net.minecraft.core.dispenser.DispenseItemBehavior$3
- net.minecraft.core.dispenser.DispenseItemBehavior$4
+ net.minecraft.core.dispenser.DispenseItemBehavior$5
- net.minecraft.core.dispenser.DispenseItemBehavior$6
+ net.minecraft.core.dispenser.DispenseItemBehavior$7
- net.minecraft.core.dispenser.DispenseItemBehavior$7$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$8
- net.minecraft.core.dispenser.DispenseItemBehavior$8$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$9
- net.minecraft.core.dispenser.OptionalDispenseItemBehavior
+ net.minecraft.core.dispenser.package-info
+ net.minecraft.core.dispenser.ShearsDispenseItemBehavior
- net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.package-info
+ net.minecraft.core.particles.BlockParticleOption
- net.minecraft.core.particles.BlockParticleOption$1
+ net.minecraft.core.particles.DustColorTransitionOptions
- net.minecraft.core.particles.DustColorTransitionOptions$1
+ net.minecraft.core.particles.DustParticleOptions
- net.minecraft.core.particles.DustParticleOptions$1
+ net.minecraft.core.particles.DustParticleOptionsBase
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleGroup
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SculkChargeParticleOptions
+ net.minecraft.core.particles.SculkChargeParticleOptions$1
- net.minecraft.core.particles.ShriekParticleOption
+ net.minecraft.core.particles.ShriekParticleOption$1
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption
+ net.minecraft.core.particles.VibrationParticleOption$1
+ net.minecraft.core.registries.BuiltInRegistries
- net.minecraft.core.registries.BuiltInRegistries$RegistryBootstrap
- net.minecraft.core.registries.package-info
+ net.minecraft.core.registries.Registries
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdvancementSubProvider
- net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.packs.package-info
+ net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdvancementProvider
- net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
+ net.minecraft.data.advancements.packs.VanillaAdvancementProvider
- net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
+ net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
- net.minecraft.data.advancements.packs.VanillaNetherAdvancements
+ net.minecraft.data.advancements.packs.VanillaStoryAdvancements
- net.minecraft.data.advancements.packs.VanillaTheEndAdvancements
+ net.minecraft.data.BlockFamilies
- net.minecraft.data.BlockFamily
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.CachedOutput
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataGenerator$PackGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.DataProvider$Factory
- net.minecraft.data.HashCache
+ net.minecraft.data.HashCache$CacheUpdater
- net.minecraft.data.HashCache$ProviderCache
+ net.minecraft.data.HashCache$ProviderCacheBuilder
- net.minecraft.data.HashCache$UpdateFunction
+ net.minecraft.data.HashCache$UpdateResult
- net.minecraft.data.info.BiomeParametersDumpReport
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLootSubProvider
- net.minecraft.data.loot.EntityLootSubProvider
+ net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.LootTableProvider$1
+ net.minecraft.data.loot.LootTableProvider$SubProviderEntry
- net.minecraft.data.loot.LootTableSubProvider
+ net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.packs.package-info
- net.minecraft.data.loot.packs.TradeRebalanceChestLoot
+ net.minecraft.data.loot.packs.TradeRebalanceLootTableProvider
- net.minecraft.data.loot.packs.UpdateOneTwentyOneBlockLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneChestLoot
- net.minecraft.data.loot.packs.UpdateOneTwentyOneLootTableProvider
+ net.minecraft.data.loot.packs.VanillaArchaeologyLoot
- net.minecraft.data.loot.packs.VanillaBlockLoot
+ net.minecraft.data.loot.packs.VanillaChestLoot
- net.minecraft.data.loot.packs.VanillaEntityLoot
+ net.minecraft.data.loot.packs.VanillaFishingLoot
- net.minecraft.data.loot.packs.VanillaGiftLoot
+ net.minecraft.data.loot.packs.VanillaLootTableProvider
- net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
- net.minecraft.data.Main
+ net.minecraft.data.metadata.package-info
- net.minecraft.data.metadata.PackMetadataGenerator
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ net.minecraft.data.models.BlockModelGenerators$BookSlotModelCacheKey
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
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
+ net.minecraft.data.models.ItemModelGenerators$TrimModelData
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplate$JsonFactory
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
+ net.minecraft.data.PackOutput
- net.minecraft.data.PackOutput$PathProvider
+ net.minecraft.data.PackOutput$Target
+ net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.packs.BundleRecipeProvider
- net.minecraft.data.recipes.packs.package-info
+ net.minecraft.data.recipes.packs.UpdateOneTwentyOneRecipeProvider
- net.minecraft.data.recipes.packs.VanillaRecipeProvider
+ net.minecraft.data.recipes.packs.VanillaRecipeProvider$TrimTemplate
- net.minecraft.data.recipes.RecipeBuilder
+ net.minecraft.data.recipes.RecipeBuilder$1
- net.minecraft.data.recipes.RecipeCategory
+ net.minecraft.data.recipes.RecipeOutput
- net.minecraft.data.recipes.RecipeProvider
+ net.minecraft.data.recipes.RecipeProvider$1
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder
- net.minecraft.data.recipes.SmithingTransformRecipeBuilder
+ net.minecraft.data.recipes.SmithingTrimRecipeBuilder
- net.minecraft.data.recipes.SpecialRecipeBuilder
+ net.minecraft.data.registries.package-info
+ net.minecraft.data.registries.RegistriesDatapackGenerator
- net.minecraft.data.registries.RegistryPatchGenerator
+ net.minecraft.data.registries.UpdateOneTwentyOneRegistries
- net.minecraft.data.registries.VanillaRegistries
- net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtDatafixer
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$StructureConversionException
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BannerPatternTagsProvider
+ net.minecraft.data.tags.BiomeTagsProvider
- net.minecraft.data.tags.CatVariantTagsProvider
+ net.minecraft.data.tags.DamageTypeTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.data.tags.InstrumentTagsProvider
+ net.minecraft.data.tags.IntrinsicHolderTagsProvider
- net.minecraft.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.PaintingVariantTagsProvider
+ net.minecraft.data.tags.PoiTypeTagsProvider
- net.minecraft.data.tags.StructureTagsProvider
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1CombinedData
+ net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.tags.TagsProvider$TagLookup
+ net.minecraft.data.tags.TradeRebalanceStructureTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneBiomeTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneBlockTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneDamageTypeTagsProvider
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
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
+ net.minecraft.util.eventlog.EventLogDirectory
- net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
+ net.minecraft.util.eventlog.EventLogDirectory$File
- net.minecraft.util.eventlog.EventLogDirectory$FileId
+ net.minecraft.util.eventlog.EventLogDirectory$FileList
- net.minecraft.util.eventlog.EventLogDirectory$RawFile
+ net.minecraft.util.eventlog.JsonEventLog
- net.minecraft.util.eventlog.JsonEventLog$1
+ net.minecraft.util.eventlog.JsonEventLogReader
- net.minecraft.util.eventlog.JsonEventLogReader$1
+ net.minecraft.util.eventlog.package-info
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.monitoring.jmx.package-info
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.jfr.callback.package-info
- net.minecraft.util.profiling.jfr.callback.ProfiledDuration
+ net.minecraft.util.profiling.jfr.Environment
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
- net.minecraft.util.profiling.jfr.event.package-info
+ net.minecraft.util.profiling.jfr.event.PacketEvent
- net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
+ net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
- net.minecraft.util.profiling.jfr.event.PacketSentEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
+ net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
- net.minecraft.util.profiling.jfr.JfrProfiler
+ net.minecraft.util.profiling.jfr.JfrProfiler$1
- net.minecraft.util.profiling.jfr.JvmProfiler
+ net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
+ net.minecraft.util.profiling.jfr.package-info
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
+ net.minecraft.util.profiling.jfr.parse.JfrStatsResult
- net.minecraft.util.profiling.jfr.parse.package-info
- net.minecraft.util.profiling.jfr.Percentiles
+ net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
- net.minecraft.util.profiling.jfr.serialize.package-info
+ net.minecraft.util.profiling.jfr.stats.ChunkGenStat
- net.minecraft.util.profiling.jfr.stats.CpuLoadStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketCountAndSize
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketIdentification
- net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
+ net.minecraft.util.profiling.jfr.stats.TickTimeStat
- net.minecraft.util.profiling.jfr.stats.TimedStat
+ net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.SummaryReporter
+ net.minecraft.util.profiling.metrics.MetricCategory
- net.minecraft.util.profiling.metrics.MetricSampler
+ net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
- net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
+ net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
- net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ net.minecraft.util.profiling.metrics.MetricsRegistry
- net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ net.minecraft.util.profiling.metrics.MetricsSamplerProvider
+ net.minecraft.util.profiling.metrics.package-info
- net.minecraft.util.profiling.metrics.ProfilerMeasured
- net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.package-info
+ net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- net.minecraft.util.profiling.metrics.storage.MetricsPersister
- net.minecraft.util.profiling.metrics.storage.package-info
+ net.minecraft.util.profiling.metrics.storage.RecordedDeviation
+ net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.random.package-info
- net.minecraft.util.random.SimpleWeightedRandomList
+ net.minecraft.util.random.SimpleWeightedRandomList$Builder
- net.minecraft.util.random.Weight
+ net.minecraft.util.random.WeightedEntry
- net.minecraft.util.random.WeightedEntry$IntrusiveBase
+ net.minecraft.util.random.WeightedEntry$Wrapper
- net.minecraft.util.random.WeightedRandom
+ net.minecraft.util.random.WeightedRandomList
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
- net.minecraft.util.valueproviders.BiasedToBottomInt
+ net.minecraft.util.valueproviders.ClampedInt
- net.minecraft.util.valueproviders.ClampedNormalFloat
+ net.minecraft.util.valueproviders.ClampedNormalInt
- net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.IntProviderType
- net.minecraft.util.valueproviders.MultipliedFloats
- net.minecraft.util.valueproviders.package-info
+ net.minecraft.util.valueproviders.SampledFloat
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.valueproviders.WeightedListInt
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
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageEffects
+ net.minecraft.world.damagesource.DamageScaling
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.DamageSource$1
- net.minecraft.world.damagesource.DamageSources
+ net.minecraft.world.damagesource.DamageType
- net.minecraft.world.damagesource.DamageTypes
+ net.minecraft.world.damagesource.DeathMessageType
- net.minecraft.world.damagesource.FallLocation
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsorptionMobEffect
+ net.minecraft.world.effect.AttributeModifierTemplate
- net.minecraft.world.effect.MobEffect$AttributeTemplate
+ net.minecraft.world.effect.MobEffect$MobEffectAttributeModifierTemplate
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.sensing.WardenEntitySensor
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
- net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.poi.PoiTypes
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.allay.Allay
- net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
+ net.minecraft.world.entity.animal.allay.Allay$VibrationUser
- net.minecraft.world.entity.animal.allay.AllayAi
+ net.minecraft.world.entity.animal.allay.package-info
- net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.armadillo.Armadillo
- net.minecraft.world.entity.animal.armadillo.Armadillo$2
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi$ArmadilloBallUp
- net.minecraft.world.entity.animal.armadillo.package-info
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
+ net.minecraft.world.entity.animal.Bucketable
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.CatVariant
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
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
- net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.IronGolem$Crackiness
+ net.minecraft.world.entity.animal.MushroomCow
- net.minecraft.world.entity.animal.MushroomCow$MushroomType
+ net.minecraft.world.entity.animal.Ocelot
- net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
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
+ net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
- net.minecraft.world.entity.animal.Parrot$Variant
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Rabbit$Variant
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Base
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
- net.minecraft.world.entity.animal.TropicalFish$Variant
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
- net.minecraft.world.entity.EntityAttachment
- net.minecraft.world.entity.EntityAttachments
- net.minecraft.world.entity.monster.breeze.LongJump
- net.minecraft.world.entity.monster.breeze.package-info
+ net.minecraft.world.entity.monster.breeze.Shoot
- net.minecraft.world.entity.monster.breeze.ShootWhenStuck
+ net.minecraft.world.entity.monster.breeze.Slide
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.Warden$VibrationUser
- net.minecraft.world.entity.monster.warden.WardenAi
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$FailureItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TypeSpecificTrade
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
- net.minecraft.world.item.AnimalArmorItem$Type
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BrushItem
+ net.minecraft.world.item.BrushItem$1
- net.minecraft.world.item.BrushItem$DustParticlesDelta
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$Builder
+ net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
- net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
- net.minecraft.world.item.CreativeModeTab$Output
+ net.minecraft.world.item.CreativeModeTab$Row
- net.minecraft.world.item.CreativeModeTab$TabVisibility
+ net.minecraft.world.item.CreativeModeTab$Type
- net.minecraft.world.item.CreativeModeTabs
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DiscFragmentItem
+ net.minecraft.world.item.DispensibleContainerItem
- net.minecraft.world.item.DoubleHighBlockItem
+ net.minecraft.world.item.DyeableLeatherItem
+ net.minecraft.world.item.DyeColor
- net.minecraft.world.item.DyeItem
- net.minecraft.world.item.EggItem
+ net.minecraft.world.item.ElytraItem
- net.minecraft.world.item.EmptyMapItem
+ net.minecraft.world.item.EnchantedBookItem
- net.minecraft.world.item.EnchantedGoldenAppleItem
+ net.minecraft.world.item.EndCrystalItem
- net.minecraft.world.item.EnderEyeItem
+ net.minecraft.world.item.EnderpearlItem
- net.minecraft.world.item.Equipable
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.GlowInkSacItem
+ net.minecraft.world.item.HangingEntityItem
- net.minecraft.world.item.HangingSignItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.ItemInteractionResult$1
- net.minecraft.world.level.block.BonemealableBlock$Type
- net.minecraft.world.level.storage.FileNameDateFormatter
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelDataAndDimensions
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
+ net.minecraft.world.level.storage.LevelSummary$CorruptedLevelSummary
- net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
+ net.minecraft.world.level.storage.LevelVersion
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.LootTableReference
+ net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Path
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FunctionReference
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SequenceFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
+ net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootDataId
- net.minecraft.world.level.storage.loot.LootDataManager
+ net.minecraft.world.level.storage.loot.LootDataManager$1
- net.minecraft.world.level.storage.loot.LootDataResolver
+ net.minecraft.world.level.storage.loot.LootDataType
- net.minecraft.world.level.storage.loot.LootDataType$Validator
+ net.minecraft.world.level.storage.loot.LootParams
- net.minecraft.world.level.storage.loot.LootParams$Builder
+ net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
- net.minecraft.world.level.storage.loot.ValidationContext
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
- net.minecraft.world.level.validation.ContentValidationException
+ net.minecraft.world.level.validation.DirectoryValidator
- net.minecraft.world.level.validation.DirectoryValidator$1
+ net.minecraft.world.level.validation.ForbiddenSymlinkInfo
+ net.minecraft.world.level.validation.package-info
- net.minecraft.world.level.validation.PathAllowList
+ net.minecraft.world.level.validation.PathAllowList$ConfigEntry
- net.minecraft.world.level.validation.PathAllowList$EntryType
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
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
+ net.minecraft.world.RandomizableContainer
- net.minecraft.world.RandomSequence
+ net.minecraft.world.RandomSequences
- net.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
- net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerScoreEntry
- net.minecraft.world.scores.PlayerScores
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.ReadOnlyScoreInfo
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.ScoreAccess
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.Scoreboard$1
+ net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.ScoreHolder
- net.minecraft.world.scores.ScoreHolder$1
+ net.minecraft.world.scores.ScoreHolder$2
- net.minecraft.world.scores.ScoreHolder$3
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.TickRateManager
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
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen +5M -5M
```
```
XXX.gui.screens.RealmsGenericErrorScreen +1M
```
```
XXX.advancements.critereon.MobEffectsPredicate$Builder +2M -2M
```
```
XXX.minecraft.client.MouseHandler +4M -3M | +1P -1P
```
```
XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry +2M -2M | +6P -1P
```
```
XXX.client.multiplayer.ServerStatusPinger$1 +1M -1M | +1P
```
```
XXX.client.renderer.FogRenderer$BlindnessFogFunction +1M -1M
```
```
XXX.client.renderer.FogRenderer$MobEffectFogFunction +1P -1P
```
```
XXX.client.resources.MobEffectTextureManager +1M -1M
```
```
XXX.commands.functions.FunctionBuilder +1M -1M
```
```
XXX.commands.functions.MacroFunction +2M -3M
```
```
XXX.commands.functions.MacroFunction$MacroEntry +2M -3M | +1P
```
```
XXX.commands.functions.PlainTextFunction +1M -1M
```
```
XXX.minecraft.core.Holder$Direct +1M
```
```
XXX.minecraft.core.Holder$Reference +1M
```
```
XXX.minecraft.core.MappedRegistry +1M
```
```
XXX.minecraft.core.Registry +1P
```
```
XXX.core.cauldron.CauldronInteraction +15M -15M | +1P -1P
```
```
XXX.protocol.game.ClientboundRemoveMobEffectPacket +6M -2M | +1P -1P
```
```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +3M -5M | +2P -2P
```
```
XXX.protocol.game.DebugPackets +2M -1M
```
```
XXX.protocol.game.ServerboundSetBeaconPacket +9M -6M
```
```
XXX.network.syncher.EntityDataSerializers +1P
```
```
XXX.server.commands.LocateCommand +6M -8M
```
```
XXX.server.level.ServerLevel +1M -1M
```
```
XXX.server.level.ServerPlayer +3M | +3P
```
```
XXX.server.network.ServerGamePacketListenerImpl -1P
```
```
XXX.server.players.PlayerList +5M -4M
```
```
XXX.minecraft.tags.TagManager +1M -2M
```
```
XXX.minecraft.util.ParticleUtils +2M
```
```
XXX.datafix.fixes.BlockRenameFix +5M -2M | +1P -1P
```
```
XXX.datafix.fixes.References +1M | +1P
```
```
XXX.datafix.schemas.V1909 +1M
```
```
XXX.world.effect.HealOrHarmMobEffect +1M -1M
```
```
XXX.world.effect.MobEffectInstance +14M -13M | +2P -3P
```
```
XXX.world.effect.MobEffectUtil +1M -1M
```
```
XXX.world.effect.PoisonMobEffect +1M -1M
```
```
XXX.world.effect.SaturationMobEffect +1M -1M
```
```
XXX.world.entity.AreaEffectCloud +2M -2M | +1P -1P
```
```
XXX.world.entity.EntityDimensions +11M | +2P
```
```
XXX.world.entity.EntityType +1P
```
```
XXX.world.entity.EntityType$Builder +6M | +1P
```
```
XXX.ai.attributes.AttributeMap +7M -11M
```
```
XXX.ai.attributes.AttributeSupplier$Builder +4M -4M | +1P -1P
```
```
XXX.ai.behavior.Swim +1M
```
```
XXX.animal.camel.Camel +3M -4M
```
```
XXX.animal.frog.Frog -1M
```
```
XXX.animal.horse.AbstractChestedHorse +1M -1M | +1P
```
```
XXX.animal.horse.AbstractHorse +2M -4M
```
```
XXX.animal.horse.SkeletonHorse +2M -1M | +1P
```
```
XXX.animal.sniffer.Sniffer +1M -4M
```
```
XXX.entity.decoration.ArmorStand +2M -2M
```
```
XXX.entity.decoration.LeashFenceKnotEntity -1M
```
```
XXX.entity.monster.AbstractSkeleton -2M
```
```
XXX.entity.monster.CaveSpider +1M -3M
```
```
XXX.entity.monster.ElderGuardian -1M
```
```
XXX.entity.monster.Endermite -2M
```
```
XXX.entity.monster.Giant -2M
```
```
XXX.entity.monster.Shulker -1M
```
```
XXX.entity.monster.Strider +1M -1M
```
```
XXX.entity.monster.WitherSkeleton -2M
```
```
XXX.entity.monster.Zombie +1M -3M | +1P -1P
```
```
XXX.entity.monster.ZombifiedPiglin +1M -2M | +1P -2P
```
```
XXX.world.inventory.BeaconMenu +4M -4M
```
```
XXX.world.item.ItemStack +3M -2M
```
```
XXX.world.item.WrittenBookItem -1M
```
```
XXX.item.alchemy.PotionBrewing +2M -2M
```
```
XXX.item.alchemy.PotionUtils +6M -5M
```
```
XXX.world.level.LevelAccessor +4M -3M | +1P -1P
```
```
XXX.level.block.AbstractCauldronBlock +1M -1M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +1M -1M
```
```
XXX.level.block.BarrelBlock +1M -1M
```
```
XXX.level.block.BedBlock +2M -2M
```
```
XXX.level.block.BeehiveBlock +2M -2M
```
```
XXX.level.block.BellBlock +1M -1M
```
```
XXX.level.block.BonemealableBlock +2M
```
```
XXX.level.block.CakeBlock +2M -1M
```
```
XXX.level.block.CampfireBlock +1M -1M
```
```
XXX.level.block.CandleCakeBlock +3M -2M | +1P -1P
```
```
XXX.level.block.CaveVinesPlantBlock +1M -1M
```
```
XXX.level.block.ChestBlock +1M -1M
```
```
XXX.level.block.ChiseledBookShelfBlock +5M -3M
```
```
XXX.level.block.ComparatorBlock +1M -1M
```
```
XXX.level.block.CrafterBlock +1M -1M
```
```
XXX.level.block.CraftingTableBlock +1M -1M
```
```
XXX.level.block.DoorBlock +1M -1M
```
```
XXX.level.block.EnchantmentTableBlock +1M -1M
```
```
XXX.level.block.FenceGateBlock +1M -1M
```
```
XXX.level.block.FlowerBlock +2M -2M
```
```
XXX.level.block.GrindstoneBlock +1M -1M
```
```
XXX.level.block.JukeboxBlock +1M -1M
```
```
XXX.level.block.LeverBlock +1M -1M
```
```
XXX.level.block.LightBlock +1M -1M
```
```
XXX.level.block.LoomBlock +1M -1M
```
```
XXX.level.block.MangroveLeavesBlock +1M
```
```
XXX.level.block.NetherrackBlock +1M
```
```
XXX.level.block.NyliumBlock +1M
```
```
XXX.level.block.PumpkinBlock +2M -2M
```
```
XXX.level.block.RedStoneWireBlock +1M -1M
```
```
XXX.level.block.RespawnAnchorBlock +2M -1M
```
```
XXX.level.block.RootedDirtBlock +1M
```
```
XXX.level.block.ShulkerBoxBlock +1M -1M
```
```
XXX.level.block.SignBlock +2M -2M
```
```
XXX.level.block.StonecutterBlock +1M -1M
```
```
XXX.level.block.SuspiciousEffectHolder$EffectEntry +2M -2M | +1P -1P
```
```
XXX.level.block.WitherRoseBlock +1M -1M
```
```
XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser +1M -1M
```
```
XXX.block.piston.MovingPistonBlock +1M -1M
```
```
XXX.level.gameevent.GameEventDispatcher +2M -2M
```
```
XXX.level.gameevent.GameEventListenerRegistry +1P -1P
```
```
XXX.gameevent.vibrations.VibrationInfo +5M -5M | +1P -1P
```
```
XXX.gameevent.vibrations.VibrationSystem +4M -3M | +2P -1P
```
```
XXX.gameevent.vibrations.VibrationSystem$Listener +4M -4M
```
```
XXX.gameevent.vibrations.VibrationSystem$User +1M -1M | +2P -2P
```
```
XXX.saveddata.maps.MapItemSavedData +2M
```

</details>











































































<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
+ Font access$1700(RealmsMainScreen)
- Font access$2000(RealmsMainScreen)
+ Font access$2700(RealmsMainScreen)
- Font access$300(RealmsMainScreen)
- Minecraft access$1700(RealmsMainScreen)
+ Minecraft access$2000(RealmsMainScreen)
- Minecraft access$2700(RealmsMainScreen)
+ Minecraft access$3000(RealmsMainScreen)
+ void access$300(RealmsMainScreen,Component)
- void onClose()
```

</details>






















































<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen
</summary>

```diff
- void onClose()
```

</details>















































































































<details>
<summary>
net.minecraft.advancements.critereon.MobEffectsPredicate$Builder
</summary>

```diff
- MobEffectsPredicate$Builder and(Holder,MobEffectsPredicate$MobEffectInstancePredicate)
- MobEffectsPredicate$Builder and(Holder)
+ MobEffectsPredicate$Builder and(MobEffect,MobEffectsPredicate$MobEffectInstancePredicate)
+ MobEffectsPredicate$Builder and(MobEffect)
```

</details>










































<details>
<summary>
net.minecraft.client.MouseHandler
</summary>

```diff
- void handleAccumulatedMovement()
- void lambda$handleAccumulatedMovement$10(Screen,double,double)
- void lambda$handleAccumulatedMovement$11(Screen,double,double,double,double)
+ void lambda$onMove$10(Screen,double,double)
+ void lambda$onMove$11(Screen,double,double,double,double)
+ void turnPlayer()
- void turnPlayer(double)
```

</details>






























<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
</summary>

```diff
+ boolean isCompatible()
+ boolean pingCompleted()
- void lambda$render$2()
- void refreshStatus()
```

</details>








































































<details>
<summary>
net.minecraft.client.multiplayer.ServerStatusPinger$1
</summary>

```diff
+ void <init>(ServerStatusPinger,Connection,ServerData,Runnable,InetSocketAddress,ServerAddress)
- void <init>(ServerStatusPinger,Connection,ServerData,Runnable,Runnable,InetSocketAddress,ServerAddress)
```

</details>


































































































































<details>
<summary>
net.minecraft.client.renderer.FogRenderer$BlindnessFogFunction
</summary>

```diff
- Holder getMobEffect()
+ MobEffect getMobEffect()
```

</details>
















































































































































<details>
<summary>
net.minecraft.client.resources.MobEffectTextureManager
</summary>

```diff
- TextureAtlasSprite get(Holder)
+ TextureAtlasSprite get(MobEffect)
```

</details>




























































































































































































<details>
<summary>
net.minecraft.commands.functions.FunctionBuilder
</summary>

```diff
- void addMacro(String,int,ExecutionCommandSource)
+ void addMacro(String,int)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.MacroFunction
</summary>

```diff
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,ExecutionCommandSource)
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,Object)
- InstantiatedFunction instantiate(CompoundTag,CommandDispatcher)
+ InstantiatedFunction substituteAndParse(List,List,CommandDispatcher,ExecutionCommandSource)
- InstantiatedFunction substituteAndParse(List,List,CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.MacroFunction$MacroEntry
</summary>

```diff
+ UnboundEntryAction instantiate(List,CommandDispatcher,ExecutionCommandSource,ResourceLocation)
+ UnboundEntryAction instantiate(List,CommandDispatcher,Object,ResourceLocation)
- UnboundEntryAction instantiate(List,CommandDispatcher,ResourceLocation)
- void <init>(StringTemplate,IntList,ExecutionCommandSource)
+ void <init>(StringTemplate,IntList)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.PlainTextFunction
</summary>

```diff
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,Object)
- InstantiatedFunction instantiate(CompoundTag,CommandDispatcher)
```

</details>


























<details>
<summary>
net.minecraft.core.Holder$Direct
</summary>

```diff
- boolean is(Holder)
```

</details>
<details>
<summary>
net.minecraft.core.Holder$Reference
</summary>

```diff
- boolean is(Holder)
```

</details>









<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
- Optional getHolder(ResourceLocation)
```

</details>



















<details>
<summary>
net.minecraft.core.cauldron.CauldronInteraction
</summary>

```diff
+ InteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
+ InteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
+ InteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
- ItemInteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
- ItemInteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
```

</details>


























































































































































































































































<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
</summary>

```diff
- boolean equals(Object)
- Holder effect()
- int entityId()
- int hashCode()
+ MobEffect getEffect()
- String toString()
- void <init>(int,Holder)
+ void <init>(int,MobEffect)
```

</details>
























<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
</summary>

```diff
- boolean shouldBlend()
- Holder getEffect()
+ MobEffect getEffect()
+ MobEffectInstance$FactorData getFactorData()
+ MobEffectInstance$FactorData lambda$new$0(FriendlyByteBuf)
- void <init>(int,MobEffectInstance,boolean)
+ void <init>(int,MobEffectInstance)
+ void lambda$write$1(FriendlyByteBuf,MobEffectInstance$FactorData)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.DebugPackets
</summary>

```diff
- void lambda$sendGameEventInfo$7(ServerLevel,Vec3,ResourceKey)
+ void sendGameEventInfo(Level,GameEvent,Vec3)
- void sendGameEventInfo(Level,Holder,Vec3)
```

</details>

























<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
</summary>

```diff
- boolean equals(Object)
- Holder lambda$new$0(FriendlyByteBuf)
- Holder lambda$new$1(FriendlyByteBuf)
- int hashCode()
+ MobEffect lambda$new$0(FriendlyByteBuf)
+ MobEffect lambda$new$1(FriendlyByteBuf)
+ Optional getPrimary()
+ Optional getSecondary()
- Optional primary()
- Optional secondary()
- String toString()
- void lambda$write$2(FriendlyByteBuf,Holder)
+ void lambda$write$2(FriendlyByteBuf,MobEffect)
- void lambda$write$3(FriendlyByteBuf,Holder)
+ void lambda$write$3(FriendlyByteBuf,MobEffect)
```

</details>











































































































<details>
<summary>
net.minecraft.server.commands.LocateCommand
</summary>

```diff
- Component lambda$showLocateResult$16(String,String,Component,int)
+ Component lambda$showLocateResult$17(String,String,Component,int)
+ String getElementName(Pair)
+ String lambda$getElementName$11(ResourceKey)
- String lambda$showLocateResult$11(ResourceOrTagArgument$Result,Holder$Reference)
+ String lambda$showLocateResult$12(ResourceOrTagArgument$Result,Holder$Reference)
- String lambda$showLocateResult$12(ResourceOrTagArgument$Result,Pair,HolderSet$Named)
- String lambda$showLocateResult$13(ResourceKey)
+ String lambda$showLocateResult$13(ResourceOrTagArgument$Result,Pair,HolderSet$Named)
- String lambda$showLocateResult$14(Pair,TagKey)
+ String lambda$showLocateResult$14(ResourceKey)
+ String lambda$showLocateResult$15(Pair,TagKey)
- Style lambda$showLocateResult$15(BlockPos,String,Style)
+ Style lambda$showLocateResult$16(BlockPos,String,Style)
```

</details>
































































<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ void gameEvent(GameEvent,Vec3,GameEvent$Context)
- void gameEvent(Holder,Vec3,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- boolean canInteractWithBlock(BlockPos)
- boolean canInteractWithEntity(AABB)
- void updatePlayerAttributes()
```

</details>



















































































<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ Component lambda$broadcastSystemMessage$2(Component,ServerPlayer)
- Component lambda$broadcastSystemMessage$3(Component,ServerPlayer)
+ CompoundTag load(ServerPlayer)
+ Entity lambda$placeNewPlayer$0(ServerLevel,Entity)
- Entity lambda$placeNewPlayer$1(ServerLevel,Entity)
- Optional lambda$placeNewPlayer$0(CompoundTag)
- Optional load(ServerPlayer)
+ void lambda$remove$1(Entity)
- void lambda$remove$2(Entity)
```

</details>






























<details>
<summary>
net.minecraft.tags.TagManager
</summary>

```diff
+ Optional lambda$createLoader$3(Registry,ResourceKey,ResourceLocation)
- TagManager$LoadResult lambda$createLoader$3(ResourceKey,TagLoader,ResourceManager)
+ TagManager$LoadResult lambda$createLoader$4(ResourceKey,TagLoader,ResourceManager)
```

</details>










































<details>
<summary>
net.minecraft.util.ParticleUtils
</summary>

```diff
- void spawnParticleInBlock(LevelAccessor,BlockPos,int,ParticleOptions)
- void spawnParticles(LevelAccessor,BlockPos,int,double,double,boolean,ParticleOptions)
```

</details>




































<details>
<summary>
net.minecraft.util.datafix.fixes.BlockRenameFix
</summary>

```diff
- Dynamic fixBlockState(Dynamic)
+ Dynamic lambda$makeRule$2(Dynamic)
- Dynamic lambda$makeRule$3(Dynamic)
- String fixFlatBlockState(String)
- Typed lambda$makeRule$2(Typed)
+ Typed lambda$makeRule$3(Typed)
- Typed lambda$makeRule$4(Typed)
```

</details>





































































<details>
<summary>
net.minecraft.util.datafix.fixes.References
</summary>

```diff
- String lambda$static$35()
```

</details>

































<details>
<summary>
net.minecraft.util.datafix.schemas.V1909
</summary>

```diff
- TypeTemplate lambda$registerBlockEntities$0(Schema)
```

</details>




















<details>
<summary>
net.minecraft.world.effect.HealOrHarmMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>

<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
- boolean is(Holder)
- float getBlendFactor(LivingEntity,float)
- Holder getEffect()
- int lambda$tickDownDuration$0(int)
+ int lambda$tickDownDuration$1(int)
+ MobEffect getEffect()
- MobEffectInstance lambda$load$1(CompoundTag,Holder$Reference)
- MobEffectInstance loadSpecifiedEffect(Holder,CompoundTag)
+ MobEffectInstance loadSpecifiedEffect(MobEffect,CompoundTag)
+ Optional getFactorData()
- void <init>(Holder,int,int,boolean,boolean,boolean,MobEffectInstance)
- void <init>(Holder,int,int,boolean,boolean,boolean)
- void <init>(Holder,int,int,boolean,boolean)
- void <init>(Holder,int,int)
- void <init>(Holder,int)
- void <init>(Holder)
+ void <init>(MobEffect,int,int,boolean,boolean,boolean,MobEffectInstance,Optional)
+ void <init>(MobEffect,int,int,boolean,boolean,boolean)
+ void <init>(MobEffect,int,int,boolean,boolean)
+ void <init>(MobEffect,int,int)
+ void <init>(MobEffect,int)
+ void <init>(MobEffect)
- void copyBlendState(MobEffectInstance)
+ void lambda$tick$0(MobEffectInstance$FactorData)
+ void lambda$writeDetailsTo$2(CompoundTag,Tag)
+ void lambda$writeDetailsTo$3(CompoundTag,MobEffectInstance$FactorData)
- void skipBlending()
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectUtil
</summary>

```diff
- boolean lambda$addEffectToPlayersAround$0(Entity,Vec3,double,Holder,MobEffectInstance,int,ServerPlayer)
+ boolean lambda$addEffectToPlayersAround$0(Entity,Vec3,double,MobEffect,MobEffectInstance,int,ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.world.effect.PoisonMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.SaturationMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>


<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
- Holder getPotion()
+ Potion getPotion()
- void setPotion(Holder)
+ void setPotion(Potion)
```

</details>














<details>
<summary>
net.minecraft.world.entity.EntityDimensions
</summary>

```diff
- boolean equals(Object)
- boolean fixed()
- EntityAttachments attachments()
- EntityDimensions withAttachments(EntityAttachments$Builder)
- EntityDimensions withEyeHeight(float)
- float defaultEyeHeight(float)
- float eyeHeight()
- float height()
- float width()
- int hashCode()
- void <init>(float,float,float,EntityAttachments,boolean)
```

</details>


<details>
<summary>
net.minecraft.world.entity.EntityType$Builder
</summary>

```diff
- EntityType$Builder eyeHeight(float)
- EntityType$Builder nameTagOffset(float)
- EntityType$Builder passengerAttachments(float[])
- EntityType$Builder passengerAttachments(Vec3[])
- EntityType$Builder ridingOffset(float)
- EntityType$Builder vehicleAttachment(Vec3)
```

</details>



























<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeMap
</summary>

```diff
+ AttributeInstance getInstance(Attribute)
+ AttributeInstance lambda$getInstance$1(Attribute)
- AttributeInstance lambda$getInstance$1(Holder)
+ boolean hasAttribute(Attribute)
+ boolean hasModifier(Attribute,UUID)
+ double getBaseValue(Attribute)
- double getBaseValue(Holder)
+ double getModifierValue(Attribute,UUID)
+ double getValue(Attribute)
- double getValue(Holder)
+ void lambda$addTransientAttributeModifiers$4(Attribute,AttributeModifier)
- void lambda$addTransientAttributeModifiers$4(Holder,AttributeModifier)
+ void lambda$load$6(CompoundTag,Attribute)
- void lambda$load$6(CompoundTag,Holder$Reference)
- void lambda$load$7(ResourceLocation)
+ void lambda$load$7(String)
+ void lambda$removeAttributeModifiers$3(Attribute,Collection)
- void lambda$removeAttributeModifiers$3(Holder,Collection)
```

</details>

<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
</summary>

```diff
+ AttributeInstance create(Attribute)
- AttributeInstance create(Holder)
+ AttributeSupplier$Builder add(Attribute,double)
+ AttributeSupplier$Builder add(Attribute)
- AttributeSupplier$Builder add(Holder,double)
- AttributeSupplier$Builder add(Holder)
+ void lambda$create$0(Attribute,AttributeInstance)
- void lambda$create$0(Holder,AttributeInstance)
```

</details>















































<details>
<summary>
net.minecraft.world.entity.ai.behavior.Swim
</summary>

```diff
- boolean shouldSwim(Mob)
```

</details>
























































































<details>
<summary>
net.minecraft.world.entity.animal.camel.Camel
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
- float getAgeScale()
+ float getScale()
+ float getStandingEyeHeight(Pose,EntityDimensions)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.frog.Frog
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractChestedHorse
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ float getPassengersRidingOffsetY(EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ float getPassengersRidingOffsetY(EntityDimensions,float)
+ float getStandingEyeHeight(Pose,EntityDimensions)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ void setOffspringAttribute(AgeableMob,AbstractHorse,Attribute,double,double)
- void setOffspringAttribute(AgeableMob,AbstractHorse,Holder,double,double)
```

</details>





<details>
<summary>
net.minecraft.world.entity.animal.horse.SkeletonHorse
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
- void <clinit>()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.sniffer.Sniffer
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ float getNameTagOffsetY()
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>


















<details>
<summary>
net.minecraft.world.entity.decoration.ArmorStand
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
```

</details>



<details>
<summary>
net.minecraft.world.entity.decoration.LeashFenceKnotEntity
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.CaveSpider
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
- Vec3 getVehicleAttachmentPoint(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.ElderGuardian
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.Endermite
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.Giant
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
```

</details>












<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
```

</details>












<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.WitherSkeleton
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zombie
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.ZombifiedPiglin
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>






















































<details>
<summary>
net.minecraft.world.inventory.BeaconMenu
</summary>

```diff
- Holder decodeEffect(int)
- Holder getPrimaryEffect()
- Holder getSecondaryEffect()
- int encodeEffect(Holder)
+ int encodeEffect(MobEffect)
+ MobEffect decodeEffect(int)
+ MobEffect getPrimaryEffect()
+ MobEffect getSecondaryEffect()
```

</details>






























































<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- IllegalArgumentException lambda$addAttributeModifier$14()
+ Style lambda$getDisplayName$14(Style)
- Style lambda$getDisplayName$15(Style)
+ void addAttributeModifier(Attribute,AttributeModifier,EquipmentSlot)
- void addAttributeModifier(Holder,AttributeModifier,EquipmentSlot)
```

</details>

























<details>
<summary>
net.minecraft.world.item.WrittenBookItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.PotionBrewing
</summary>

```diff
- boolean isBrewablePotion(Holder)
+ boolean isBrewablePotion(Potion)
- void addMix(Holder,Item,Holder)
+ void addMix(Potion,Item,Potion)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.PotionUtils
</summary>

```diff
- Holder getPotion(CompoundTag)
- Holder getPotion(ItemStack)
- int getColor(Holder)
+ int getColor(Potion)
- ItemStack setPotion(ItemStack,Holder)
+ ItemStack setPotion(ItemStack,Potion)
- List getAllEffects(Holder,Collection)
+ List getAllEffects(Potion,Collection)
+ Potion getPotion(CompoundTag)
+ Potion getPotion(ItemStack)
- void lambda$addPotionTooltip$0(List,Holder,AttributeModifier)
```

</details>





















































































<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
+ void gameEvent(Entity,GameEvent,BlockPos)
+ void gameEvent(Entity,GameEvent,Vec3)
- void gameEvent(Entity,Holder,BlockPos)
- void gameEvent(Entity,Holder,Vec3)
+ void gameEvent(GameEvent,BlockPos,GameEvent$Context)
- void gameEvent(Holder,BlockPos,GameEvent$Context)
- void gameEvent(ResourceKey,BlockPos,GameEvent$Context)
```

</details>












































<details>
<summary>
net.minecraft.world.level.block.AbstractCauldronBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.BarrelBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
+ void lambda$use$1(Player,Player$BedSleepingProblem)
- void lambda$useWithoutItem$1(Player,Player$BedSleepingProblem)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ void lambda$use$0(InteractionHand,Player)
- void lambda$useItemOn$0(InteractionHand,Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.BonemealableBlock
</summary>

```diff
- BlockPos getParticlePos(BlockPos)
- BonemealableBlock$Type getType()
```

</details>




<details>
<summary>
net.minecraft.world.level.block.CakeBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleCakeBlock
</summary>

```diff
+ BlockState byCandle(Block)
- BlockState byCandle(CandleBlock)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.CaveVinesPlantBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ChestBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ChiseledBookShelfBlock
</summary>

```diff
+ int getHitSlot(Vec2)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- OptionalInt getHitSlot(BlockHitResult,BlockState)
- OptionalInt lambda$getHitSlot$0(Vec2)
+ void lambda$createBlockStateDefinition$0(StateDefinition$Builder,Property)
- void lambda$createBlockStateDefinition$1(StateDefinition$Builder,Property)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.ComparatorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CraftingTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.EnchantmentTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.FenceGateBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.FlowerBlock
</summary>

```diff
- List makeEffectList(Holder,int)
+ List makeEffectList(MobEffect,int)
- void <init>(Holder,int,BlockBehaviour$Properties)
+ void <init>(MobEffect,int,BlockBehaviour$Properties)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.GrindstoneBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.JukeboxBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LightBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.LoomBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.MangroveLeavesBlock
</summary>

```diff
- BlockPos getParticlePos(BlockPos)
```

</details>











<details>
<summary>
net.minecraft.world.level.block.NetherrackBlock
</summary>

```diff
- BonemealableBlock$Type getType()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NyliumBlock
</summary>

```diff
- BonemealableBlock$Type getType()
```

</details>








<details>
<summary>
net.minecraft.world.level.block.PumpkinBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ void lambda$use$0(InteractionHand,Player)
- void lambda$useItemOn$0(InteractionHand,Player)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.RedStoneWireBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.RespawnAnchorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.RootedDirtBlock
</summary>

```diff
- BlockPos getParticlePos(BlockPos)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SignBlock
</summary>

```diff
+ InteractionResult getInteractionResult(boolean)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>













<details>
<summary>
net.minecraft.world.level.block.StonecutterBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.SuspiciousEffectHolder$EffectEntry
</summary>

```diff
- Holder effect()
+ MobEffect effect()
- void <init>(Holder,int)
+ void <init>(MobEffect,int)
```

</details>























<details>
<summary>
net.minecraft.world.level.block.WitherRoseBlock
</summary>

```diff
- void <init>(Holder,int,BlockBehaviour$Properties)
+ void <init>(MobEffect,int,BlockBehaviour$Properties)
```

</details>















<details>
<summary>
net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
</summary>

```diff
+ boolean canReceiveVibration(ServerLevel,BlockPos,GameEvent,GameEvent$Context)
- boolean canReceiveVibration(ServerLevel,BlockPos,Holder,GameEvent$Context)
```

</details>




































<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>



































































































<details>
<summary>
net.minecraft.world.level.gameevent.GameEventDispatcher
</summary>

```diff
+ void lambda$post$0(List,GameEvent,Vec3,GameEvent$Context,GameEventListener,Vec3)
- void lambda$post$0(List,Holder,Vec3,GameEvent$Context,GameEventListener,Vec3)
+ void post(GameEvent,Vec3,GameEvent$Context)
- void post(Holder,Vec3,GameEvent$Context)
```

</details>




<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationInfo
</summary>

```diff
+ GameEvent gameEvent()
- Holder gameEvent()
+ VibrationInfo lambda$static$2(GameEvent,Float,Vec3,Optional,Optional)
- VibrationInfo lambda$static$2(Holder,Float,Vec3,Optional,Optional)
+ void <init>(GameEvent,float,Vec3,Entity)
+ void <init>(GameEvent,float,Vec3,UUID,UUID,Entity)
+ void <init>(GameEvent,float,Vec3,UUID,UUID)
- void <init>(Holder,float,Vec3,Entity)
- void <init>(Holder,float,Vec3,UUID,UUID,Entity)
- void <init>(Holder,float,Vec3,UUID,UUID)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationSystem
</summary>

```diff
+ GameEvent getResonanceEventByFrequency(int)
+ int getGameEventFrequency(GameEvent)
- int getGameEventFrequency(Holder)
- int getGameEventFrequency(ResourceKey)
- ResourceKey getResonanceEventByFrequency(int)
+ void lambda$static$0(Object2IntOpenHashMap)
- void lambda$static$0(Reference2IntOpenHashMap)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
</summary>

```diff
+ boolean handleGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- boolean handleGameEvent(ServerLevel,Holder,GameEvent$Context,Vec3)
+ void forceScheduleVibration(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- void forceScheduleVibration(ServerLevel,Holder,GameEvent$Context,Vec3)
+ void lambda$forceScheduleVibration$0(ServerLevel,GameEvent,GameEvent$Context,Vec3,Vec3)
- void lambda$forceScheduleVibration$0(ServerLevel,Holder,GameEvent$Context,Vec3,Vec3)
+ void scheduleVibration(ServerLevel,VibrationSystem$Data,GameEvent,GameEvent$Context,Vec3,Vec3)
- void scheduleVibration(ServerLevel,VibrationSystem$Data,Holder,GameEvent$Context,Vec3,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
</summary>

```diff
+ boolean isValidVibration(GameEvent,GameEvent$Context)
- boolean isValidVibration(Holder,GameEvent$Context)
```

</details>





























































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- boolean lambda$mapMatcher$3(ItemStack,Integer,ItemStack)
- Predicate mapMatcher(ItemStack)
```

</details>
</details>