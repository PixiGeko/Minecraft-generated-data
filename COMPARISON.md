## Comparison with [21w11a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w11a)

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
<table><tr><th></th><th align="left">21w11a</th><th>21w13a</th></tr><tr><td>World version</td><td><code>2703</code></td><td><code>2705</code></td></tr><tr><td>Protocol version</td><td><code>1073741843</code></td><td><code>1073741844</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ float_provider_type.txt
+ height_provider_type.txt
+ int_provider_type.txt
- worldgen/float_provider_type.txt
```

</details>
<details>
<summary>
activity.txt
</summary>

```diff
+ minecraft:long_jump
```

</details>

<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:light
```

</details>




<details>
<summary>
entity_type.txt
</summary>

```diff
+ minecraft:goat
```

</details>


<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:goat_spawn_egg
+ minecraft:light
```

</details>






<details>
<summary>
memory_module_type.txt
</summary>

```diff
+ minecraft:has_hunting_cooldown
+ minecraft:long_jump_cooling_down
+ minecraft:long_jump_mid_jump
+ minecraft:nearest_attackable
```

</details>



<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:light
```

</details>








<details>
<summary>
sensor_type.txt
</summary>

```diff
+ minecraft:axolotl_attackables
- minecraft:axolotl_hostiles
+ minecraft:goat_temptations
```

</details>
<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:entity.goat.ambient
+ minecraft:entity.goat.death
+ minecraft:entity.goat.hurt
+ minecraft:entity.goat.milk
+ minecraft:entity.goat.prepare_ram
+ minecraft:entity.goat.screaming.ambient
+ minecraft:entity.goat.screaming.death
+ minecraft:entity.goat.screaming.hurt
+ minecraft:entity.goat.screaming.milk
+ minecraft:entity.goat.screaming.ram
+ minecraft:entity.goat.step
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/float_provider_type.json
+ universal_tags/height_provider_type.json
+ universal_tags/int_provider_type.json
- universal_tags/worldgen/float_provider_type.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:light
```

</details>

<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:goat
```

</details>

<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:goat
```

</details>

<details>
<summary>
universal_tags/activity.json
</summary>

```diff
+ minecraft:long_jump
```

</details>

<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:light
```

</details>




<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:goat
```

</details>


<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:goat_spawn_egg
+ minecraft:light
```

</details>






<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:has_hunting_cooldown
+ minecraft:long_jump_cooling_down
+ minecraft:long_jump_mid_jump
+ minecraft:nearest_attackable
```

</details>



<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:light
```

</details>








<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:axolotl_attackables
- minecraft:axolotl_hostiles
+ minecraft:goat_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.goat.ambient
+ minecraft:entity.goat.death
+ minecraft:entity.goat.hurt
+ minecraft:entity.goat.milk
+ minecraft:entity.goat.prepare_ram
+ minecraft:entity.goat.screaming.ambient
+ minecraft:entity.goat.screaming.death
+ minecraft:entity.goat.screaming.hurt
+ minecraft:entity.goat.screaming.milk
+ minecraft:entity.goat.screaming.ram
+ minecraft:entity.goat.step
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ block.minecraft.light: Light
+ entity.minecraft.goat: Goat
+ item.minecraft.goat_spawn_egg: Goat Spawn Egg
+ options.darkMojangStudiosBackgroundColor: Monochrome Logo
+ options.darkMojangStudiosBackgroundColor.tooltip: Changes the Mojang Studios loading screen background color to black.
```

</details>
<details>
<summary>
Changes
</summary>

```
build.tooHigh: Height limit for building is %s blocks
advancements.story.shiny_gear.title: Cover Me Wwith Diamonds
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/loot_tables/entities/goat.json
+ minecraft/tags/blocks/dirt.json
+ minecraft/tags/blocks/snow.json
+ minecraft/tags/entity_types/axolotl_hunt_targets.json
- minecraft/tags/entity_types/axolotl_tempted_hostiles.json
+ minecraft/tags/entity_types/freeze_hurts_extra_types.json
+ minecraft/tags/entity_types/freeze_immune_entity_types.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/light.json
+ minecraft/models/block/light.json
+ minecraft/models/item/goat_spawn_egg.json
+ minecraft/models/item/light_00.json
+ minecraft/models/item/light_01.json
+ minecraft/models/item/light_02.json
+ minecraft/models/item/light_03.json
+ minecraft/models/item/light_04.json
+ minecraft/models/item/light_05.json
+ minecraft/models/item/light_06.json
+ minecraft/models/item/light_07.json
+ minecraft/models/item/light_08.json
+ minecraft/models/item/light_09.json
+ minecraft/models/item/light_10.json
+ minecraft/models/item/light_11.json
+ minecraft/models/item/light_12.json
+ minecraft/models/item/light_13.json
+ minecraft/models/item/light_14.json
+ minecraft/models/item/light_15.json
+ minecraft/models/item/light.json
+ minecraft/particles/light.json
- minecraft/textures/block/calibrated_sculk_sensor_side.png
- minecraft/textures/block/calibrated_sculk_sensor_top.png
- minecraft/textures/entity/arrow.png
+ minecraft/textures/entity/goat/goat.png
- minecraft/textures/entity/zombie/zombie_villager.png
+ minecraft/textures/item/light_00.png
+ minecraft/textures/item/light_01.png
+ minecraft/textures/item/light_02.png
+ minecraft/textures/item/light_03.png
+ minecraft/textures/item/light_04.png
+ minecraft/textures/item/light_05.png
+ minecraft/textures/item/light_06.png
+ minecraft/textures/item/light_07.png
+ minecraft/textures/item/light_08.png
+ minecraft/textures/item/light_09.png
+ minecraft/textures/item/light_10.png
+ minecraft/textures/item/light_11.png
+ minecraft/textures/item/light_12.png
+ minecraft/textures/item/light_13.png
+ minecraft/textures/item/light_14.png
+ minecraft/textures/item/light_15.png
+ minecraft/textures/item/light.png
- minecraft/textures/item/ruby.png
- minecraft/textures/models/armor/piglin_leather_layer_1_overlay.png
- minecraft/textures/models/armor/piglin_leather_layer_1.png
- minecraft/textures/particle/footprint.png
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
- com.mojang.math.Constants
- com.mojang.math.MethodsReturnNonnullByDefault
+ com.mojang.math.OctahedralGroup
- com.mojang.math.OctahedralGroup$1
+ com.mojang.math.Quaternion
- com.mojang.math.SymmetricGroup3
+ com.mojang.math.Transformation
- com.mojang.math.Vector3d
+ net.minecraft.advancements.Advancement
- net.minecraft.advancements.Advancement$1
+ net.minecraft.advancements.Advancement$Builder
- net.minecraft.advancements.AdvancementList
+ net.minecraft.advancements.AdvancementList$Listener
- net.minecraft.advancements.AdvancementProgress
+ net.minecraft.advancements.AdvancementProgress$Serializer
- net.minecraft.advancements.AdvancementRewards
+ net.minecraft.advancements.AdvancementRewards$Builder
- net.minecraft.advancements.critereon.AbstractCriterionTriggerInstance
+ net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
- net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BlockPredicate
- net.minecraft.advancements.critereon.BlockPredicate$Builder
+ net.minecraft.advancements.critereon.BredAnimalsTrigger
- net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BrewedPotionTrigger
- net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChangeDimensionTrigger
- net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChanneledLightningTrigger
- net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConstructBeaconTrigger
- net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConsumeItemTrigger
- net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.DamagePredicate
- net.minecraft.advancements.critereon.DamagePredicate$Builder
+ net.minecraft.advancements.critereon.DamageSourcePredicate
- net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
+ net.minecraft.advancements.critereon.DeserializationContext
- net.minecraft.advancements.critereon.DistancePredicate
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
+ net.minecraft.advancements.critereon.EntityPredicate$1
- net.minecraft.advancements.critereon.EntityPredicate$Builder
+ net.minecraft.advancements.critereon.EntityPredicate$Composite
- net.minecraft.advancements.critereon.EntityTypePredicate
+ net.minecraft.advancements.critereon.EntityTypePredicate$1
- net.minecraft.advancements.critereon.EntityTypePredicate$TagPredicate
+ net.minecraft.advancements.critereon.EntityTypePredicate$TypePredicate
- net.minecraft.advancements.critereon.FilledBucketTrigger
+ net.minecraft.advancements.critereon.FilledBucketTrigger$TriggerInstance
- net.minecraft.advancements.critereon.FishingHookPredicate
+ net.minecraft.advancements.critereon.FishingRodHookedTrigger
- net.minecraft.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.FluidPredicate
- net.minecraft.advancements.critereon.FluidPredicate$Builder
+ net.minecraft.advancements.critereon.ImpossibleTrigger
- net.minecraft.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.InventoryChangeTrigger
- net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemDurabilityTrigger
- net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemPickedUpByEntityTrigger
- net.minecraft.advancements.critereon.ItemPickedUpByEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemPredicate
- net.minecraft.advancements.critereon.ItemPredicate$Builder
+ net.minecraft.advancements.critereon.ItemUsedOnBlockTrigger
- net.minecraft.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.KilledByCrossbowTrigger
- net.minecraft.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.KilledTrigger
- net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LevitationTrigger
- net.minecraft.advancements.critereon.LevitationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LightPredicate
- net.minecraft.advancements.critereon.LightPredicate$1
+ net.minecraft.advancements.critereon.LightPredicate$Builder
- net.minecraft.advancements.critereon.LocationPredicate
+ net.minecraft.advancements.critereon.LocationPredicate$Builder
- net.minecraft.advancements.critereon.LocationTrigger
+ net.minecraft.advancements.critereon.LocationTrigger$TriggerInstance
- net.minecraft.advancements.critereon.LootTableTrigger
+ net.minecraft.advancements.critereon.LootTableTrigger$TriggerInstance
- net.minecraft.advancements.critereon.MinMaxBounds
+ net.minecraft.advancements.critereon.MinMaxBounds$BoundsFactory
- net.minecraft.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
+ net.minecraft.advancements.critereon.MinMaxBounds$Floats
- net.minecraft.advancements.critereon.MinMaxBounds$Ints
+ net.minecraft.advancements.critereon.MobEffectsPredicate
- net.minecraft.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ net.minecraft.advancements.critereon.NbtPredicate
- net.minecraft.advancements.critereon.NetherTravelTrigger
+ net.minecraft.advancements.critereon.NetherTravelTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.PlacedBlockTrigger
+ net.minecraft.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerInteractTrigger
+ net.minecraft.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$1
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$Builder
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SerializationContext
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger
- net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.SimpleCriterionTrigger
- net.minecraft.advancements.critereon.SlideDownBlockTrigger
+ net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.StatePropertiesPredicate
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$1
- net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
- net.minecraft.advancements.critereon.SummonedEntityTrigger
+ net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TameAnimalTrigger
+ net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TargetBlockTrigger
+ net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TickTrigger
+ net.minecraft.advancements.critereon.TickTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TradeTrigger
+ net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsedTotemTrigger
+ net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.WrappedMinMaxBounds
- net.minecraft.advancements.CriteriaTriggers
+ net.minecraft.advancements.Criterion
- net.minecraft.advancements.CriterionProgress
+ net.minecraft.advancements.CriterionTrigger
- net.minecraft.advancements.CriterionTrigger$Listener
+ net.minecraft.advancements.CriterionTriggerInstance
- net.minecraft.advancements.DisplayInfo
+ net.minecraft.advancements.FrameType
- net.minecraft.advancements.package-info
- net.minecraft.advancements.RequirementsStrategy
+ net.minecraft.advancements.TreeNodePosition
- net.minecraft.BlockUtil
+ net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.CharPredicate
- net.minecraft.ChatFormatting
- net.minecraft.commands.arguments.AngleArgument
+ net.minecraft.commands.arguments.AngleArgument$1
- net.minecraft.commands.arguments.AngleArgument$SingleAngle
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.ColorArgument
- net.minecraft.commands.arguments.ComponentArgument
+ net.minecraft.commands.arguments.CompoundTagArgument
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
- net.minecraft.commands.arguments.DimensionArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument
- net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
+ net.minecraft.commands.arguments.EntityArgument
- net.minecraft.commands.arguments.EntityArgument$Serializer
+ net.minecraft.commands.arguments.EntitySummonArgument
- net.minecraft.commands.arguments.GameProfileArgument
+ net.minecraft.commands.arguments.GameProfileArgument$Result
- net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
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
+ net.minecraft.commands.arguments.ItemEnchantmentArgument
- net.minecraft.commands.arguments.MessageArgument
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
+ net.minecraft.commands.arguments.MobEffectArgument
- net.minecraft.commands.arguments.NbtPathArgument
+ net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
- net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
+ net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
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
+ net.minecraft.commands.BrigadierExceptions
- net.minecraft.commands.CommandFunction
+ net.minecraft.commands.CommandFunction$CacheableFunction
- net.minecraft.commands.CommandFunction$CommandEntry
+ net.minecraft.commands.CommandFunction$Entry
- net.minecraft.commands.CommandFunction$FunctionEntry
+ net.minecraft.commands.CommandRuntimeException
+ net.minecraft.commands.Commands
- net.minecraft.commands.Commands$CommandSelection
+ net.minecraft.commands.Commands$ParseFunction
- net.minecraft.commands.CommandSource
+ net.minecraft.commands.CommandSource$1
- net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.exceptions.package-info
- net.minecraft.commands.SharedSuggestionProvider
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.FieldsAreNonnullByDefault
+ net.minecraft.FileUtil
- net.minecraft.MethodsReturnNonnullByDefault
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
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
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$1
- net.minecraft.server.ChainedJsonException$Entry
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
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateBiomeCommand
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
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
- net.minecraft.server.DebugLoggedPrintStream
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
+ net.minecraft.server.Eula
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
- net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
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
+ net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$1
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$1
+ net.minecraft.server.level.ServerLevel$EntityCallbacks
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayer$1
- net.minecraft.server.level.ServerPlayer$2
+ net.minecraft.server.level.ServerPlayer$3
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
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerGamePacketListenerImpl$2
- net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerPlayerConnection
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.network.TextFilter
+ net.minecraft.server.network.TextFilter$1
- net.minecraft.server.network.TextFilter$FilteredText
+ net.minecraft.server.network.TextFilterClient
- net.minecraft.server.network.TextFilterClient$1
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.FolderPackResources
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
- net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackType
- net.minecraft.server.packs.repository.FolderRepositorySource
+ net.minecraft.server.packs.repository.Pack
- net.minecraft.server.packs.repository.Pack$PackConstructor
+ net.minecraft.server.packs.repository.Pack$Position
+ net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.PackSource
+ net.minecraft.server.packs.repository.RepositorySource
- net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.ResourcePackFileNotFoundException
- net.minecraft.server.packs.resources.FallbackResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.package-info
- net.minecraft.server.packs.resources.PreparableReloadListener
+ net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
- net.minecraft.server.packs.resources.ProfiledReloadInstance
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$1
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceManager
+ net.minecraft.server.packs.resources.ResourceManager$Empty
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.ResourceProvider
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
+ net.minecraft.server.packs.VanillaPackResources$1
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
- net.minecraft.server.players.package-info
+ net.minecraft.server.players.PlayerList
- net.minecraft.server.players.PlayerList$1
+ net.minecraft.server.players.ServerOpList
- net.minecraft.server.players.ServerOpListEntry
+ net.minecraft.server.players.SleepStatus
- net.minecraft.server.players.StoredUserEntry
+ net.minecraft.server.players.StoredUserList
- net.minecraft.server.players.UserBanList
+ net.minecraft.server.players.UserBanListEntry
- net.minecraft.server.players.UserWhiteList
+ net.minecraft.server.players.UserWhiteListEntry
+ net.minecraft.server.rcon.NetworkDataOutputStream
- net.minecraft.server.rcon.package-info
- net.minecraft.server.rcon.PktUtils
+ net.minecraft.server.rcon.RconConsoleSource
+ net.minecraft.server.rcon.thread.GenericThread
- net.minecraft.server.rcon.thread.package-info
- net.minecraft.server.rcon.thread.QueryThreadGs4
+ net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
- net.minecraft.server.rcon.thread.RconClient
+ net.minecraft.server.rcon.thread.RconThread
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
+ net.minecraft.SharedConstants
+ net.minecraft.sounds.Music
- net.minecraft.sounds.Musics
- net.minecraft.sounds.package-info
+ net.minecraft.sounds.SoundEvent
- net.minecraft.sounds.SoundEvents
+ net.minecraft.sounds.SoundSource
+ net.minecraft.stats.package-info
+ net.minecraft.stats.RecipeBook
- net.minecraft.stats.RecipeBookSettings
+ net.minecraft.stats.RecipeBookSettings$TypeSettings
- net.minecraft.stats.ServerRecipeBook
+ net.minecraft.stats.ServerStatsCounter
- net.minecraft.stats.Stat
+ net.minecraft.stats.StatFormatter
+ net.minecraft.stats.Stats
- net.minecraft.stats.StatsCounter
- net.minecraft.stats.StatType
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
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
+ net.minecraft.tags.TagCollection$NetworkPayload
- net.minecraft.tags.TagContainer
+ net.minecraft.tags.TagContainer$1
- net.minecraft.tags.TagContainer$Builder
+ net.minecraft.tags.TagContainer$CollectionConsumer
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$1
+ net.minecraft.tags.TagManager$LoaderInfo
- net.minecraft.Util
+ net.minecraft.util.BitStorage
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CryptException
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$1
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
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
+ net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRename
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
- net.minecraft.util.datafix.fixes.RenameBiomesFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.SwimStatsRenameFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
+ net.minecraft.util.datafix.schemas.V100
- net.minecraft.util.datafix.schemas.V102
+ net.minecraft.util.datafix.schemas.V1022
- net.minecraft.util.datafix.schemas.V106
+ net.minecraft.util.datafix.schemas.V107
- net.minecraft.util.datafix.schemas.V1125
+ net.minecraft.util.datafix.schemas.V135
- net.minecraft.util.datafix.schemas.V143
+ net.minecraft.util.datafix.schemas.V1451
- net.minecraft.util.datafix.schemas.V1451_1
+ net.minecraft.util.datafix.schemas.V1451_2
- net.minecraft.util.datafix.schemas.V1451_3
+ net.minecraft.util.datafix.schemas.V1451_4
- net.minecraft.util.datafix.schemas.V1451_5
+ net.minecraft.util.datafix.schemas.V1451_6
- net.minecraft.util.datafix.schemas.V1451_7
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1460$1
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
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
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.ExtraCodecs
+ net.minecraft.util.FloatProviderType
+ net.minecraft.util.GlslPreprocessor
+ net.minecraft.util.GlslPreprocessor$Context
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HeapDumper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.IntRange
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
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
+ net.minecraft.util.profiling.registry.MeasuredMetric
- net.minecraft.util.profiling.registry.MeasurementCategory
+ net.minecraft.util.profiling.registry.MeasurementRegistry
- net.minecraft.util.profiling.registry.Metric
- net.minecraft.util.profiling.registry.package-info
+ net.minecraft.util.profiling.registry.ProfilerMeasured
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.random.package-info
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
- net.minecraft.util.random.WeightedEntry
- net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedRandom
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
+ net.minecraft.util.Tuple
+ net.minecraft.util.UniformInt
- net.minecraft.util.Unit
- net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProviderType
- net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.UniformFloat
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.Util$1
- net.minecraft.Util$3
+ net.minecraft.Util$4
- net.minecraft.Util$5
+ net.minecraft.Util$6
- net.minecraft.Util$7
+ net.minecraft.Util$8
- net.minecraft.Util$9
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
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
- net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
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
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
- net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.WeightedList
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
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
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
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
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
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
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$1
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
- net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.package-info
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
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
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
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.LightBlock
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
- net.minecraft.world.level.block.NetherrackBlock
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
+ net.minecraft.world.level.block.NetherWartBlock
+ net.minecraft.world.level.block.NoteBlock
- net.minecraft.world.level.block.NyliumBlock
+ net.minecraft.world.level.block.ObserverBlock
- net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.piston.MovingPistonBlock
- net.minecraft.world.level.block.piston.package-info
+ net.minecraft.world.level.block.piston.PistonBaseBlock
- net.minecraft.world.level.block.piston.PistonBaseBlock$1
+ net.minecraft.world.level.block.piston.PistonHeadBlock
- net.minecraft.world.level.block.piston.PistonHeadBlock$1
+ net.minecraft.world.level.block.piston.PistonMath
- net.minecraft.world.level.block.piston.PistonMath$1
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
+ net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RespawnAnchorBlock$1
+ net.minecraft.world.level.block.RodBlock
- net.minecraft.world.level.block.RodBlock$1
+ net.minecraft.world.level.block.RootedDirtBlock
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
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
+ net.minecraft.world.level.block.SmallDripleafBlock
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
- net.minecraft.world.level.block.SporeBlossomBlock
+ net.minecraft.world.level.block.SpreadingSnowyDirtBlock
- net.minecraft.world.level.block.StainedGlassBlock
+ net.minecraft.world.level.block.StainedGlassPaneBlock
- net.minecraft.world.level.block.StairBlock
+ net.minecraft.world.level.block.StairBlock$1
- net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
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
+ net.minecraft.world.level.block.state.properties.SculkSensorPhase
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.Tilt
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
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
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperFullBlock
+ net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WeatheringCopperStairBlock
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
+ net.minecraft.world.level.chunk.BulkSectionAccess
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
+ net.minecraft.world.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
- net.minecraft.world.level.chunk.FeatureAccess
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$1
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.OldDataLayer
- net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.OldChunkStorage
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
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CarverDebugSettings
+ net.minecraft.world.level.levelgen.carver.CarvingContext
- net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
- net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
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
+ net.minecraft.world.level.storage.threaded.package-info
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
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.math.Matrix3f +17M | +1P
```
```
XXX.mojang.math.Vector4f +11M
```
```
XXX.minecraft.core.Cursor3D +4P
```
```
XXX.minecraft.core.IdMapper +1P
```
```
XXX.minecraft.core.QuartPos +3P
```
```
XXX.minecraft.core.SectionPos +17P
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.data.models.BlockModelGenerators +1M
```
```
XXX.data.worldgen.BiomeDefaultFeatures +2M -1M
```
```
XXX.data.worldgen.Features$States +1P
```
```
XXX.gametest.framework.GameTestServer +1P
```
```
XXX.gametest.framework.StructureUtils +2P
```
```
XXX.gametest.framework.TestCommand +9P
```
```
XXX.minecraft.locale.Language +1P
```
```
XXX.minecraft.nbt.ListTag +1P
```
```
XXX.minecraft.nbt.LongArrayTag +1P
```
```
XXX.minecraft.nbt.LongTag +1P
```
```
XXX.minecraft.nbt.LongTag$Cache +2P
```
```
XXX.minecraft.nbt.SnbtPrinterTagVisitor +7P
```
```
XXX.minecraft.nbt.Tag +19P
```
```
XXX.minecraft.nbt.TextComponentTagVisitor +8P
```
```
XXX.minecraft.network.Varint21LengthFieldPrepender +1P
```
```
XXX.protocol.game.ClientboundBossEventPacket +3P
```
```
XXX.protocol.game.ClientboundCommandsPacket +7P
```
```
XXX.protocol.game.ClientboundContainerSetSlotPacket +2P
```
```
XXX.protocol.game.ClientboundCustomPayloadPacket +1P
```
```
XXX.protocol.game.ClientboundGameEventPacket +5P
```
```
XXX.protocol.game.ClientboundMoveEntityPacket +1P
```
```
XXX.protocol.game.ClientboundSectionBlocksUpdatePacket +1P
```
```
XXX.protocol.game.ClientboundSetObjectivePacket +3P
```
```
XXX.protocol.game.ClientboundSetPlayerTeamPacket +7P
```
```
XXX.protocol.game.ClientboundStopSoundPacket +2P
```
```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +3P
```
```
XXX.protocol.game.ServerboundClientInformationPacket +1P
```
```
XXX.protocol.game.ServerboundPlayerInputPacket +2P
```
```
XXX.protocol.game.ServerboundSignUpdatePacket +1P
```
```
XXX.protocol.handshake.ClientIntentionPacket +1P
```
```
XXX.protocol.login.ClientboundCustomQueryPacket +1P
```
```
XXX.protocol.login.ServerboundCustomQueryPacket +1P
```
```
XXX.protocol.status.ServerStatus +2P
```
```
XXX.network.syncher.SynchedEntityData +2P
```
```
XXX.minecraft.util.LinearCongruentialGenerator +2P
```
```
XXX.minecraft.util.ParticleUtils +2M -2M
```
```
XXX.minecraft.util.StringDecomposer +1P
```
```
XXX.minecraft.util.TimeUtil +1M -1M
```
```
XXX.minecraft.world.Container +1P
```
```
XXX.minecraft.world.Snooper +3P
```
```
XXX.world.damagesource.CombatTracker +2P
```
```
XXX.world.entity.AgeableMob +2P
```
```
XXX.world.entity.AreaEffectCloud +2P
```
```
XXX.world.entity.EntityType +3P
```
```
XXX.world.entity.ExperienceOrb +1M | +5P
```
```
XXX.world.entity.ItemBasedSteering +2P
```
```
XXX.world.entity.LightningBolt +1P
```
```
XXX.world.entity.Pose +1P
```
```
XXX.ai.behavior.AcquirePoi +3P
```
```
XXX.ai.behavior.AnimalMakeLove +3P
```
```
XXX.ai.behavior.PlayTagWithOtherKids +6P
```
```
XXX.ai.behavior.RingBell +2P
```
```
XXX.ai.behavior.SetClosestHomeAsWalkTarget +4P
```
```
XXX.ai.behavior.SetHiddenState +1P
```
```
XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach +1P
```
```
XXX.ai.behavior.SleepInBed +1P
```
```
XXX.ai.behavior.StopAttackingIfTargetInvalid +6M -1M | +2P
```
```
XXX.ai.behavior.StrollAroundPoi +3P
```
```
XXX.ai.behavior.TradeWithVillager +2P
```
```
XXX.ai.behavior.ValidateNearbyPoi +1P
```
```
XXX.ai.behavior.VillageBoundRandomStroll +2P
```
```
XXX.ai.behavior.VillagerGoalPackages +1P
```
```
XXX.ai.control.BodyRotationControl +3P
```
```
XXX.ai.goal.EatBlockGoal +1P
```
```
XXX.ai.goal.FollowFlockLeaderGoal +1P
```
```
XXX.ai.goal.FollowOwnerGoal +4P
```
```
XXX.ai.goal.GoalSelector +1P
```
```
XXX.ai.goal.LlamaFollowCaravanGoal +1P
```
```
XXX.ai.goal.MoveBackToVillageGoal +2P
```
```
XXX.ai.sensing.NearestItemSensor +3P
```
```
XXX.animal.horse.Llama +2P
```
```
XXX.enderdragon.phases.DragonSittingAttackingPhase +1P
```
```
XXX.enderdragon.phases.DragonSittingScanningPhase +4P
```
```
XXX.entity.decoration.ArmorStand +12P
```
```
XXX.entity.decoration.LeashFenceKnotEntity +1P
```
```
XXX.entity.item.PrimedTnt +1P
```
```
XXX.entity.monster.Drowned +1P
```
```
XXX.entity.monster.EnderMan +3P -1P
```
```
XXX.entity.monster.Enemy +6P
```
```
XXX.entity.monster.Illusioner +3P
```
```
XXX.entity.monster.Phantom +1P
```
```
XXX.entity.monster.Shulker +2M | +8P
```
```
XXX.entity.monster.Skeleton +1M | +1P
```
```
XXX.entity.monster.Strider +3P
```
```
XXX.entity.monster.Vex +2P
```
```
XXX.entity.monster.Zombie +5P
```
```
XXX.entity.monster.ZombifiedPiglin +4P -3P
```
```
XXX.monster.hoglin.HoglinAi +15P -2P
```
```
XXX.monster.piglin.AbstractPiglin +1P
```
```
XXX.monster.piglin.PiglinAi +35P -6P
```
```
XXX.monster.piglin.PiglinBrute +3P
```
```
XXX.entity.npc.CatSpawner +1P
```
```
XXX.entity.npc.Villager +10P
```
```
XXX.entity.npc.VillagerTrades +14P
```
```
XXX.entity.player.Inventory +5P
```
```
XXX.entity.projectile.AbstractArrow +4P
```
```
XXX.entity.projectile.Arrow +3P
```
```
XXX.entity.projectile.EvokerFangs +3P
```
```
XXX.entity.projectile.FishingHook +1P
```
```
XXX.entity.projectile.ThrownPotion +2P
```
```
XXX.entity.raid.Raid +21P
```
```
XXX.entity.vehicle.AbstractMinecart +1P
```
```
XXX.entity.vehicle.MinecartCommandBlock +1P
```
```
XXX.entity.vehicle.MinecartTNT +1P
```
```
XXX.world.food.FoodConstants +26P
```
```
XXX.world.inventory.AnvilMenu +9P
```
```
XXX.world.inventory.BeaconMenu +7P
```
```
XXX.world.inventory.BrewingStandMenu +10P
```
```
XXX.world.inventory.CartographyTableMenu +7P
```
```
XXX.world.inventory.ChestMenu +1P
```
```
XXX.world.inventory.CraftingMenu +7P
```
```
XXX.world.inventory.HopperMenu +1P
```
```
XXX.world.inventory.InventoryMenu +11P
```
```
XXX.world.inventory.LecternMenu +6P
```
```
XXX.world.inventory.LoomMenu +4P
```
```
XXX.world.inventory.StonecutterMenu +6P
```
```
XXX.world.item.BlockItem +2P
```
```
XXX.world.item.BoneMealItem +3P
```
```
XXX.world.item.BundleItem +3P
```
```
XXX.world.item.CompassItem +3P
```
```
XXX.world.item.DyeableLeatherItem +3P
```
```
XXX.world.item.EnchantedBookItem +1P
```
```
XXX.world.item.HoneyBottleItem +1P
```
```
XXX.world.item.HorseArmorItem +1P
```
```
XXX.world.item.Items +1M | +2P
```
```
XXX.world.item.MapItem +4P
```
```
XXX.world.item.PickaxeItem +1P
```
```
XXX.world.item.PotionItem +1P
```
```
XXX.world.item.ShieldItem +3P
```
```
XXX.world.item.TridentItem +3P
```
```
XXX.world.item.WrittenBookItem +13P
```
```
XXX.item.alchemy.PotionBrewing +1P
```
```
XXX.item.alchemy.PotionUtils +4P
```
```
XXX.item.crafting.ShapedRecipe +2M -1M
```
```
XXX.item.enchantment.DamageEnchantment +3P
```
```
XXX.world.level.BlockGetter +1M
```
```
XXX.world.level.CommonLevelAccessor +1M
```
```
XXX.world.level.GameRules +1P
```
```
XXX.world.level.GameType +1P
```
```
XXX.world.level.LevelSimulatedReader +1P
```
```
XXX.world.level.NaturalSpawner +1M -1M | +3P
```
```
XXX.world.level.SpawnData +2P
```
```
XXX.level.biome.FuzzyOffsetBiomeZoomer +3P
```
```
XXX.level.biome.MobSpawnSettings +2M -2M | +2P
```
```
XXX.level.biome.MobSpawnSettings$Builder +1M -1M
```
```
XXX.level.biome.MobSpawnSettings$SpawnerData +2M -2M
```
```
XXX.level.biome.TheEndBiomeSource +3P
```
```
XXX.level.block.AbstractCauldronBlock +5P
```
```
XXX.level.block.AttachedStemBlock +1P
```
```
XXX.level.block.BambooBlock +8P
```
```
XXX.level.block.BaseCoralPlantBlock +1P
```
```
XXX.level.block.BaseFireBlock +2P
```
```
XXX.level.block.BedBlock +2P
```
```
XXX.level.block.BeehiveBlock +2P
```
```
XXX.level.block.BellBlock +1P
```
```
XXX.level.block.BigDripleafBlock -2M | +6P
```
```
XXX.level.block.Block +15P
```
```
XXX.level.block.Blocks +1P
```
```
XXX.level.block.CakeBlock +3P
```
```
XXX.level.block.CandleBlock +1M | +2P
```
```
XXX.level.block.CaveVinesBlock +1P
```
```
XXX.level.block.ChainBlock +2P
```
```
XXX.level.block.ChangeOverTimeBlock +1P
```
```
XXX.level.block.ConduitBlock +1P
```
```
XXX.level.block.CropBlock +1P
```
```
XXX.level.block.DetectorRailBlock +1P
```
```
XXX.level.block.DoorBlock +1P
```
```
XXX.level.block.FarmBlock +1P
```
```
XXX.level.block.FireBlock +9P
```
```
XXX.level.block.FlowerBlock +1P
```
```
XXX.level.block.FrostedIceBlock +3P
```
```
XXX.level.block.LeavesBlock +2P
```
```
XXX.level.block.LeverBlock +3P
```
```
XXX.level.dimension.DimensionType +1P
```
```
XXX.dimension.end.EndDragonFight +8P
```
```
XXX.level.gameevent.GameEvent +1P
```
```
XXX.level.levelgen.Aquifer +1M | +11P
```
```
XXX.level.levelgen.Beardifier +2P
```
```
XXX.level.levelgen.Decoratable +1M -1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +1M -1M
```
```
XXX.level.levelgen.NoiseSampler +1P
```
```
XXX.level.levelgen.VerticalAnchor$AboveBottom +1M
```
```
XXX.level.levelgen.VerticalAnchor$BelowTop +1M
```
```
XXX.levelgen.carver.CanyonCarverConfiguration +6M -13M | +2P -10P
```
```
XXX.levelgen.feature.BasaltColumnsFeature +4P
```
```
XXX.levelgen.feature.BuriedTreasureFeature +1P
```
```
XXX.levelgen.feature.EndCityFeature +1P
```
```
XXX.levelgen.feature.EndPodiumFeature +4P
```
```
XXX.levelgen.feature.HugeFungusFeature +1P
```
```
XXX.levelgen.feature.IglooFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.JigsawFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.JunglePyramidFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter +2M -2M
```
```
XXX.levelgen.feature.MineshaftFeature$MineShaftStart +1M -1M
```
```
XXX.levelgen.feature.NetherFortressFeature +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.OceanMonumentFeature +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.RuinedPortalFeature +7P
```
```
XXX.levelgen.feature.SpikeFeature +2P
```
```
XXX.levelgen.feature.StrongholdFeature$StrongholdStart +1M -1M
```
```
XXX.levelgen.feature.StructureFeature$StructureStartFactory +1P -1P
```
```
XXX.levelgen.feature.SwamplandHutFeature +2M -2M | +2P -2P
```
```
XXX.levelgen.feature.TreeFeature +7M -3M | +1P
```
```
XXX.levelgen.feature.VoidStartPlatformFeature +2P
```
```
XXX.feature.configurations.CountConfiguration +2M -2M | +1P -1P
```
```
XXX.feature.configurations.DiskConfiguration +2M -2M | +1P -1P
```
```
XXX.feature.configurations.GrowingPlantConfiguration +2M -3M | +1P -1P
```
```
XXX.feature.configurations.LargeDripstoneConfiguration +6M -6M | +5P -5P
```
```
XXX.feature.foliageplacers.AcaciaFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.BushFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.FancyFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment +1M -1M | +1P -1P
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +3M -3M | +1P -1P
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +3M -3M | +1P -1P
```
```
XXX.feature.stateproviders.WeightedStateProvider +4M -5M | +1P -1P
```
```
XXX.feature.treedecorators.AlterGroundDecorator +4M -4M
```
```
XXX.feature.treedecorators.CocoaDecorator +2M -2M
```
```
XXX.feature.treedecorators.TreeDecorator +1M -2M | +1P -1P
```
```
XXX.feature.treedecorators.TrunkVineDecorator +2M -2M
```
```
XXX.feature.trunkplacers.BendingTrunkPlacer +3M -3M | +1P -1P
```
```
XXX.feature.trunkplacers.FancyTrunkPlacer +4M -3M | +4P
```
```
XXX.feature.trunkplacers.ForkingTrunkPlacer +1M -1M
```
```
XXX.feature.trunkplacers.MegaJungleTrunkPlacer +1M -1M
```
```
XXX.feature.trunkplacers.TrunkPlacer +4M -4M | +4P -1P
```
```
XXX.levelgen.structure.EndCityPieces +8M -10M | +1P -2P
```
```
XXX.levelgen.structure.IglooPieces$IglooPiece +3M -1M | -2P
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing +2M -2M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftRoom +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces +2M -2M | +2P
```
```
XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing +3M -3M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$BridgeStraight +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece +6M -6M
```
```
XXX.levelgen.structure.NetherBridgePieces$RoomCrossing +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece +2M -1M | -2P
```
```
XXX.levelgen.structure.StructureStart +10M -3M | +2P -1P
```
```
XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid +16P
```
```
XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece +4M -1M | -3P
```
```
XXX.structure.templatesystem.StructureManager +3P
```
```
XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder +1P
```
```
XXX.levelgen.synth.PerlinNoise +1P
```
```
XXX.level.lighting.DataLayerStorageMap +1P
```
```
XXX.level.lighting.FlatDataLayer +1P
```
```
XXX.level.lighting.LayerLightSectionStorage +3P
```
```
XXX.level.lighting.LevelLightEngine +2P
```
```
XXX.level.material.FlowingFluid +1P
```
```
XXX.level.material.LavaFluid +1P
```
```
XXX.newbiome.layer.Layers +6P
```
```
XXX.level.pathfinder.WalkNodeEvaluator +1P
```
```
XXX.level.portal.PortalForcer +13P
```
```
XXX.level.portal.PortalShape +4P
```
```
XXX.level.redstone.Redstone +3P
```
```
XXX.saveddata.maps.MapIndex +1P
```
```
XXX.level.storage.McRegionUpgrader +1P
```
```
XXX.level.storage.PrimaryLevelData +1P
```
```
XXX.level.storage.WorldData +2P
```
```
XXX.providers.nbt.ContextNbtProvider +1P
```

</details>
<details>
<summary>
com.mojang.math.Matrix3f
</summary>

```diff
- boolean invert()
- float adjugateAndDet()
- float determinant()
- float trace()
- int bufferIndex(int,int)
- Matrix3f createScaleMatrix(float,float,float)
- void add(Matrix3f)
- void load(FloatBuffer,boolean)
- void load(FloatBuffer)
- void loadTransposed(FloatBuffer)
- void mul(float)
- void mul(Quaternion)
- void sortSingularValues(Matrix3f,Quaternion)
- void store(FloatBuffer,boolean)
- void store(FloatBuffer)
- void storeTransposed(FloatBuffer)
- void sub(Matrix3f)
```

</details>
<details>
<summary>
com.mojang.math.Vector4f
</summary>

```diff
- boolean normalize()
- float dot(Vector4f)
- float w()
- void <init>(Vector3f)
- void add(float,float,float,float)
- void lerp(Vector4f,float)
- void mul(float)
- void mul(Vector3f)
- void perspectiveDivide()
- void set(float,float,float,float)
- void transform(Quaternion)
```

</details>










































































<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- void createLightBlockItems()
```

</details>










































<details>
<summary>
net.minecraft.data.worldgen.BiomeDefaultFeatures
</summary>

```diff
+ void ambientSpawns(MobSpawnSettings$Builder)
- void caveSpawns(MobSpawnSettings$Builder)
- void caveWaterSpawns(MobSpawnSettings$Builder)
```

</details>























































































































































































































<details>
<summary>
net.minecraft.util.ParticleUtils
</summary>

```diff
+ void spawnParticlesAlongAxis(Direction$Axis,Level,BlockPos,double,ParticleOptions,IntRange)
- void spawnParticlesAlongAxis(Direction$Axis,Level,BlockPos,double,ParticleOptions,UniformInt)
+ void spawnParticlesOnBlockFaces(Level,BlockPos,ParticleOptions,IntRange)
- void spawnParticlesOnBlockFaces(Level,BlockPos,ParticleOptions,UniformInt)
```

</details>






<details>
<summary>
net.minecraft.util.TimeUtil
</summary>

```diff
+ IntRange rangeOfSeconds(int,int)
- UniformInt rangeOfSeconds(int,int)
```

</details>

































<details>
<summary>
net.minecraft.world.entity.ExperienceOrb
</summary>

```diff
- int repairPlayerItems(Player,int)
```

</details>










































<details>
<summary>
net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
</summary>

```diff
+ boolean lambda$new$0(LivingEntity)
- boolean lambda$new$1(LivingEntity)
- boolean lambda$new$2(LivingEntity)
- void <init>(Consumer)
- void <init>(Predicate,Consumer)
- void lambda$new$0(Mob)
- void lambda$new$3(Mob)
```

</details>










































































































<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
- void onSyncedDataUpdated(EntityDataAccessor)
- void setAttachFace(Direction)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Skeleton
</summary>

```diff
- boolean isShaking()
```

</details>









































































































































































<details>
<summary>
net.minecraft.world.item.Items
</summary>

```diff
- Item registerBlock(Block,CreativeModeTab,Block[])
```

</details>








































<details>
<summary>
net.minecraft.world.item.crafting.ShapedRecipe
</summary>

```diff
- Item itemFromJson(JsonObject)
+ ItemStack itemFromJson(JsonObject)
- ItemStack itemStackFromJson(JsonObject)
```

</details>








































<details>
<summary>
net.minecraft.world.level.BlockGetter
</summary>

```diff
- Optional getBlockEntity(BlockPos,BlockEntityType)
```

</details>






<details>
<summary>
net.minecraft.world.level.CommonLevelAccessor
</summary>

```diff
- Optional getBlockEntity(BlockPos,BlockEntityType)
```

</details>

















<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
+ List mobsAt(ServerLevel,StructureFeatureManager,ChunkGenerator,MobCategory,BlockPos,Biome)
- WeightedRandomList mobsAt(ServerLevel,StructureFeatureManager,ChunkGenerator,MobCategory,BlockPos,Biome)
```

</details>
























<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings
</summary>

```diff
+ List getMobs(MobCategory)
+ List lambda$static$1(MobCategory)
- WeightedRandomList getMobs(MobCategory)
- WeightedRandomList lambda$static$1(MobCategory)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$Builder
</summary>

```diff
+ List lambda$build$2(Map$Entry)
- WeightedRandomList lambda$build$2(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ Integer lambda$null$3(MobSpawnSettings$SpawnerData)
- void <init>(EntityType,Weight,int,int)
```

</details>






















<details>
<summary>
net.minecraft.world.level.block.BigDripleafBlock
</summary>

```diff
+ VoxelShape getLeafShape(BlockState)
+ VoxelShape getStemShape(BlockState)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.CandleBlock
</summary>

```diff
- boolean canBeLit(BlockState)
```

</details>




















































































<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer
</summary>

```diff
- boolean isLavaLevel(int)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.Decoratable
</summary>

```diff
- Object count(IntProvider)
+ Object count(UniformInt)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ List getMobsAt(Biome,StructureFeatureManager,MobCategory,BlockPos)
- WeightedRandomList getMobsAt(Biome,StructureFeatureManager,MobCategory,BlockPos)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
</summary>

```diff
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
</summary>

```diff
- String toString()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
</summary>

```diff
+ App lambda$static$1(RecordCodecBuilder$Instance)
- App lambda$static$3(RecordCodecBuilder$Instance)
- CanyonCarverConfiguration$CanyonShapeConfiguration lambda$null$2(CanyonCarverConfiguration)
- CarverConfiguration lambda$null$0(CanyonCarverConfiguration)
+ float getVerticalRadiusCenterFactor()
+ float getVerticalRadiusDefaultFactor()
+ Float lambda$null$0(CanyonCarverConfiguration)
+ FloatProvider getDistanceFactor()
+ FloatProvider getHorizontalRadiusFactor()
+ FloatProvider getThickness()
+ FloatProvider getVerticalRotation()
- FloatProvider lambda$null$1(CanyonCarverConfiguration)
+ int getWidthSmoothness()
+ UniformInt getYScale()
+ VerticalAnchor getBottomInclusive()
+ VerticalAnchor getTopInclusive()
- void <init>(CarverConfiguration,FloatProvider,CanyonCarverConfiguration$CanyonShapeConfiguration)
+ void <init>(float,CarverDebugSettings,VerticalAnchor,VerticalAnchor,UniformInt,FloatProvider,FloatProvider,FloatProvider,int,FloatProvider,float,float)
- void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,CarverDebugSettings,FloatProvider,CanyonCarverConfiguration$CanyonShapeConfiguration)
```

</details>




























<details>
<summary>
net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart
</summary>

```diff
+ void <init>(JigsawFeature,ChunkPos,BoundingBox,int,long)
- void <init>(JigsawFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
</summary>

```diff
+ void <init>(int,Random,FloatProvider,LargeDripstoneFeature$1)
- void <init>(int,Random,FloatProvider,LargeDripstoneFeature$1)
+ void <init>(int,Random,FloatProvider)
- void <init>(int,Random,FloatProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature
</summary>

```diff
+ List getSpecialEnemies()
- WeightedRandomList getSpecialEnemies()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
</summary>

```diff
+ List getSpecialEnemies()
- WeightedRandomList getSpecialEnemies()
```

</details>













<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
</summary>

```diff
+ List getSpecialAnimals()
+ List getSpecialEnemies()
- WeightedRandomList getSpecialAnimals()
- WeightedRandomList getSpecialEnemies()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- boolean doPlace(WorldGenLevel,Random,BlockPos,BiConsumer,BiConsumer,TreeConfiguration)
+ boolean doPlace(WorldGenLevel,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
- Boolean lambda$place$11(WorldGenLevel,Set,Set,BoundingBox)
- void lambda$doPlace$6(TreeConfiguration,WorldGenLevel,BiConsumer,Random,int,int,int,FoliagePlacer$FoliageAttachment)
+ void lambda$doPlace$6(TreeConfiguration,WorldGenLevel,Random,int,int,int,Set,BoundingBox,FoliagePlacer$FoliageAttachment)
- void lambda$place$10(WorldGenLevel,BiConsumer,Random,List,List,TreeDecorator)
- void lambda$place$7(Set,WorldGenLevel,BlockPos,BlockState)
+ void lambda$place$7(WorldGenLevel,Random,List,List,Set,BoundingBox,TreeDecorator)
- void lambda$place$8(Set,WorldGenLevel,BlockPos,BlockState)
- void lambda$place$9(Set,WorldGenLevel,BlockPos,BlockState)
```

</details>










<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
</summary>

```diff
- IntProvider count()
+ UniformInt count()
- void <init>(IntProvider)
+ void <init>(UniformInt)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
</summary>

```diff
- IntProvider lambda$null$1(DiskConfiguration)
+ UniformInt lambda$null$1(DiskConfiguration)
- void <init>(BlockState,IntProvider,int,List)
+ void <init>(BlockState,UniformInt,int,List)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GrowingPlantConfiguration
</summary>

```diff
- SimpleWeightedRandomList lambda$null$0(GrowingPlantConfiguration)
- void <init>(SimpleWeightedRandomList,Direction,BlockStateProvider,BlockStateProvider,boolean)
+ void <init>(UniformInt,Direction,BlockStateProvider,BlockStateProvider,boolean)
+ void <init>(WeightedList,Direction,BlockStateProvider,BlockStateProvider,boolean)
+ WeightedList lambda$null$0(GrowingPlantConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
</summary>

```diff
+ FloatProvider lambda$null$2(LargeDripstoneConfiguration)
- FloatProvider lambda$null$2(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$4(LargeDripstoneConfiguration)
- FloatProvider lambda$null$4(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$5(LargeDripstoneConfiguration)
- FloatProvider lambda$null$5(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- IntProvider lambda$null$1(LargeDripstoneConfiguration)
+ UniformInt lambda$null$1(LargeDripstoneConfiguration)
- void <init>(int,IntProvider,FloatProvider,float,FloatProvider,FloatProvider,FloatProvider,int,float)
+ void <init>(int,UniformInt,FloatProvider,float,FloatProvider,FloatProvider,FloatProvider,int,float)
```

</details>



















<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
</summary>

```diff
+ BlockPos foliagePos()
- BlockPos pos()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
</summary>

```diff
- IntProvider lambda$null$0(PineFoliagePlacer)
+ UniformInt lambda$null$0(PineFoliagePlacer)
- void <init>(IntProvider,IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
</summary>

```diff
- IntProvider lambda$null$0(SpruceFoliagePlacer)
+ UniformInt lambda$null$0(SpruceFoliagePlacer)
- void <init>(IntProvider,IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
</summary>

```diff
- DataResult create(SimpleWeightedRandomList)
+ DataResult create(WeightedList)
- SimpleWeightedRandomList lambda$static$0(WeightedStateProvider)
+ void <init>()
- void <init>(SimpleWeightedRandomList)
- void <init>(SimpleWeightedRandomList$Builder)
+ void <init>(WeightedList)
+ WeightedList lambda$static$0(WeightedStateProvider)
+ WeightedStateProvider add(BlockState,int)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
</summary>

```diff
- void lambda$place$2(LevelSimulatedReader,BiConsumer,Random,BlockPos)
+ void lambda$place$2(WorldGenLevel,Random,BlockPos)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
- void placeBlockAt(LevelSimulatedReader,BiConsumer,Random,BlockPos)
+ void placeBlockAt(LevelSimulatedRW,Random,BlockPos)
- void placeCircle(LevelSimulatedReader,BiConsumer,Random,BlockPos)
+ void placeCircle(LevelSimulatedRW,Random,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
</summary>

```diff
- void lambda$place$2(Random,LevelSimulatedReader,BiConsumer,BlockPos)
+ void lambda$place$2(Random,WorldGenLevel,Set,BoundingBox,BlockPos)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
</summary>

```diff
- void placeVine(BiConsumer,BlockPos,BooleanProperty)
+ void placeVine(LevelWriter,BlockPos,BooleanProperty,Set,BoundingBox)
+ void setBlock(LevelWriter,BlockPos,BlockState,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
</summary>

```diff
- void lambda$place$1(Random,LevelSimulatedReader,BiConsumer,BlockPos)
+ void lambda$place$1(Random,WorldGenLevel,Set,BoundingBox,BlockPos)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
</summary>

```diff
- IntProvider lambda$null$1(BendingTrunkPlacer)
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
+ UniformInt lambda$null$1(BendingTrunkPlacer)
- void <init>(int,int,int,int,IntProvider)
+ void <init>(int,int,int,int,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
</summary>

```diff
- BlockState lambda$makeLimb$1(BlockPos,BlockPos,BlockState)
- boolean makeLimb(LevelSimulatedReader,BiConsumer,Random,BlockPos,BlockPos,boolean,TreeConfiguration)
+ boolean makeLimb(LevelSimulatedRW,Random,BlockPos,BlockPos,boolean,Set,BoundingBox,TreeConfiguration)
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
- void makeBranches(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,List,TreeConfiguration)
+ void makeBranches(LevelSimulatedRW,Random,int,BlockPos,List,Set,BoundingBox,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
</summary>

```diff
- boolean placeLog(LevelSimulatedReader,BiConsumer,Random,BlockPos,TreeConfiguration,Function)
- boolean placeLog(LevelSimulatedReader,BiConsumer,Random,BlockPos,TreeConfiguration)
+ boolean placeLog(LevelSimulatedRW,Random,BlockPos,Set,BoundingBox,TreeConfiguration)
- void placeLogIfFree(LevelSimulatedReader,BiConsumer,Random,BlockPos$MutableBlockPos,TreeConfiguration)
+ void placeLogIfFree(LevelSimulatedRW,Random,BlockPos$MutableBlockPos,Set,BoundingBox,TreeConfiguration)
+ void setBlock(LevelWriter,BlockPos,BlockState,BoundingBox)
- void setDirtAt(LevelSimulatedReader,BiConsumer,Random,BlockPos,TreeConfiguration)
+ void setDirtAt(LevelSimulatedRW,Random,BlockPos,TreeConfiguration)
```

</details>


























<details>
<summary>
net.minecraft.world.level.levelgen.structure.EndCityPieces
</summary>

```diff
- boolean access$300(StructureManager,EndCityPieces$SectionGenerator,int,EndCityPieces$EndCityPiece,BlockPos,List,Random)
+ boolean access$500(StructureManager,EndCityPieces$SectionGenerator,int,EndCityPieces$EndCityPiece,BlockPos,List,Random)
- EndCityPieces$EndCityPiece access$000(StructureManager,EndCityPieces$EndCityPiece,BlockPos,String,Rotation,boolean)
- EndCityPieces$EndCityPiece access$100(List,EndCityPieces$EndCityPiece)
+ EndCityPieces$EndCityPiece access$200(StructureManager,EndCityPieces$EndCityPiece,BlockPos,String,Rotation,boolean)
+ EndCityPieces$EndCityPiece access$300(List,EndCityPieces$EndCityPiece)
- EndCityPieces$SectionGenerator access$200()
+ EndCityPieces$SectionGenerator access$400()
- EndCityPieces$SectionGenerator access$500()
- EndCityPieces$SectionGenerator access$600()
+ EndCityPieces$SectionGenerator access$800()
+ EndCityPieces$SectionGenerator access$900()
+ List access$1000()
- List access$400()
+ List access$600()
- List access$800()
+ StructurePlaceSettings access$000()
+ StructurePlaceSettings access$100()
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
</summary>

```diff
- BlockPos makePosition(ResourceLocation,BlockPos,int)
- StructurePlaceSettings lambda$new$0(CompoundTag,ResourceLocation)
- StructurePlaceSettings makeSettings(Rotation,ResourceLocation)
+ void loadTemplate(StructureManager)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
</summary>

```diff
+ BoundingBox findCrossing(List,Random,int,int,int,Direction)
- BoundingBox findCrossing(StructurePieceAccessor,Random,int,int,int,Direction)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
</summary>

```diff
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces
</summary>

```diff
+ NetherBridgePieces$NetherBridgePiece access$000(NetherBridgePieces$PieceWeight,List,Random,int,int,int,Direction,int)
- NetherBridgePieces$NetherBridgePiece access$000(NetherBridgePieces$PieceWeight,StructurePieceAccessor,Random,int,int,int,Direction,int)
+ NetherBridgePieces$NetherBridgePiece findAndCreateBridgePieceFactory(NetherBridgePieces$PieceWeight,List,Random,int,int,int,Direction,int)
- NetherBridgePieces$NetherBridgePiece findAndCreateBridgePieceFactory(NetherBridgePieces$PieceWeight,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
</summary>

```diff
+ NetherBridgePieces$BridgeCrossing createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$BridgeCrossing createPiece(StructurePieceAccessor,int,int,int,Direction,int)
- void <init>(int,int,Direction)
+ void <init>(Random,int,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
</summary>

```diff
+ NetherBridgePieces$BridgeStraight createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$BridgeStraight createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
</summary>

```diff
+ NetherBridgePieces$CastleCorridorTBalconyPiece createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleCorridorTBalconyPiece createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
</summary>

```diff
+ NetherBridgePieces$CastleSmallCorridorCrossingPiece createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleSmallCorridorCrossingPiece createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
</summary>

```diff
+ NetherBridgePieces$CastleSmallCorridorPiece createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleSmallCorridorPiece createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
</summary>

```diff
+ NetherBridgePieces$CastleStalkRoom createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleStalkRoom createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
</summary>

```diff
+ NetherBridgePieces$NetherBridgePiece generatePiece(NetherBridgePieces$StartPiece,List,List,Random,int,int,int,Direction,int)
- NetherBridgePieces$NetherBridgePiece generatePiece(NetherBridgePieces$StartPiece,List,StructurePieceAccessor,Random,int,int,int,Direction,int)
+ StructurePiece generateAndAddPiece(NetherBridgePieces$StartPiece,List,Random,int,int,int,Direction,int,boolean)
- StructurePiece generateAndAddPiece(NetherBridgePieces$StartPiece,StructurePieceAccessor,Random,int,int,int,Direction,int,boolean)
+ StructurePiece generateChildForward(NetherBridgePieces$StartPiece,List,Random,int,int,boolean)
- StructurePiece generateChildForward(NetherBridgePieces$StartPiece,StructurePieceAccessor,Random,int,int,boolean)
+ StructurePiece generateChildLeft(NetherBridgePieces$StartPiece,List,Random,int,int,boolean)
- StructurePiece generateChildLeft(NetherBridgePieces$StartPiece,StructurePieceAccessor,Random,int,int,boolean)
+ StructurePiece generateChildRight(NetherBridgePieces$StartPiece,List,Random,int,int,boolean)
- StructurePiece generateChildRight(NetherBridgePieces$StartPiece,StructurePieceAccessor,Random,int,int,boolean)
- void <init>(StructurePieceType,int,BoundingBox)
+ void <init>(StructurePieceType,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
</summary>

```diff
+ NetherBridgePieces$RoomCrossing createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$RoomCrossing createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
</summary>

```diff
- StructurePlaceSettings lambda$new$0(CompoundTag,ResourceLocation)
- StructurePlaceSettings makeSettings(Rotation)
+ void loadTemplate(StructureManager)
```

</details>














<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart
</summary>

```diff
- boolean hasNoPieces()
- boolean isInsidePiece(BlockPos)
- IllegalStateException lambda$getBoundingBox$0()
- StructurePiece findCollisionPiece(BoundingBox)
- StructurePiece findCollisionPiece(List,BoundingBox)
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
- void addPiece(StructurePiece)
+ void calculateBoundingBox()
- void clearPieces()
- void invalidateCache()
+ void lambda$createTag$0(CompoundTag,Tag)
- void offsetPiecesVertically(int)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
</summary>

```diff
- ResourceLocation makeLocation(String)
- ResourceLocation makeTemplateLocation()
- StructurePlaceSettings lambda$new$0(CompoundTag,ResourceLocation)
- StructurePlaceSettings makeSettings(Mirror,Rotation)
+ void loadTemplate(StructureManager)
```

</details>























































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- com.mojang.blaze3d.audio.Channel
+ com.mojang.blaze3d.audio.Library
- com.mojang.blaze3d.audio.Library$1
+ com.mojang.blaze3d.audio.Library$ChannelPool
- com.mojang.blaze3d.audio.Library$CountingChannelPool
+ com.mojang.blaze3d.audio.Library$Pool
- com.mojang.blaze3d.audio.Listener
+ com.mojang.blaze3d.audio.OggAudioStream
- com.mojang.blaze3d.audio.OggAudioStream$OutputConcat
+ com.mojang.blaze3d.audio.OpenAlUtil
- com.mojang.blaze3d.audio.SoundBuffer
- com.mojang.blaze3d.FieldsAreNonnullByDefault
- com.mojang.blaze3d.font.package-info
- com.mojang.blaze3d.platform.ClipboardManager
+ com.mojang.blaze3d.platform.DebugMemoryUntracker
- com.mojang.blaze3d.platform.DisplayData
- com.mojang.blaze3d.platform.GlConst
+ com.mojang.blaze3d.platform.GLX
- com.mojang.blaze3d.platform.package-info
- com.mojang.blaze3d.preprocessor.GlslPreprocessor$1
- com.mojang.blaze3d.preprocessor.package-info
+ com.mojang.blaze3d.shaders.AbstractUniform
- com.mojang.blaze3d.shaders.BlendMode
+ com.mojang.blaze3d.shaders.Effect
- com.mojang.blaze3d.shaders.EffectProgram
+ com.mojang.blaze3d.shaders.EffectProgram$1
- com.mojang.blaze3d.shaders.Program
+ com.mojang.blaze3d.shaders.Program$Type
- com.mojang.blaze3d.shaders.ProgramManager
+ com.mojang.blaze3d.shaders.Shader
- com.mojang.blaze3d.shaders.Uniform
- com.mojang.blaze3d.systems.package-info
+ com.mojang.blaze3d.vertex.BufferBuilder
- com.mojang.blaze3d.vertex.BufferBuilder$1
+ com.mojang.blaze3d.vertex.BufferBuilder$DrawState
- com.mojang.blaze3d.vertex.BufferBuilder$SortState
+ com.mojang.blaze3d.vertex.BufferUploader
- com.mojang.blaze3d.vertex.BufferVertexConsumer
- com.mojang.blaze3d.vertex.DefaultedVertexConsumer
+ com.mojang.blaze3d.vertex.DefaultVertexFormat
- com.mojang.blaze3d.vertex.package-info
+ com.mojang.blaze3d.vertex.PoseStack
- com.mojang.blaze3d.vertex.PoseStack$1
+ com.mojang.blaze3d.vertex.PoseStack$Pose
- com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
+ com.mojang.blaze3d.vertex.Tesselator
- com.mojang.blaze3d.vertex.VertexBuffer
+ com.mojang.blaze3d.vertex.VertexConsumer
- com.mojang.blaze3d.vertex.VertexFormat
+ com.mojang.blaze3d.vertex.VertexFormat$1
- com.mojang.blaze3d.vertex.VertexFormat$IndexType
+ com.mojang.blaze3d.vertex.VertexFormat$Mode
- com.mojang.blaze3d.vertex.VertexFormatElement
+ com.mojang.blaze3d.vertex.VertexFormatElement$Type
- com.mojang.blaze3d.vertex.VertexFormatElement$Usage
+ com.mojang.blaze3d.vertex.VertexFormatElement$Usage$ClearState
- com.mojang.blaze3d.vertex.VertexFormatElement$Usage$SetupState
+ com.mojang.blaze3d.vertex.VertexMultiConsumer
- com.mojang.blaze3d.vertex.VertexMultiConsumer$Double
- com.mojang.math.FieldsAreNonnullByDefault
+ com.mojang.math.Matrix3f
- com.mojang.math.Matrix4f
- com.mojang.math.package-info
- com.mojang.realmsclient.client.FileDownload
+ com.mojang.realmsclient.client.FileDownload$1
- com.mojang.realmsclient.client.FileDownload$DownloadCountingOutputStream
+ com.mojang.realmsclient.client.FileDownload$ProgressListener
- com.mojang.realmsclient.client.FileDownload$ResourcePackProgressListener
+ com.mojang.realmsclient.client.FileUpload
- com.mojang.realmsclient.client.FileUpload$CustomInputStreamEntity
- com.mojang.realmsclient.client.package-info
+ com.mojang.realmsclient.client.Ping
- com.mojang.realmsclient.client.Ping$Region
+ com.mojang.realmsclient.client.RealmsClient
- com.mojang.realmsclient.client.RealmsClient$CompatibleVersionResponse
+ com.mojang.realmsclient.client.RealmsClient$Environment
- com.mojang.realmsclient.client.RealmsClientConfig
+ com.mojang.realmsclient.client.RealmsError
- com.mojang.realmsclient.client.Request
+ com.mojang.realmsclient.client.Request$Delete
- com.mojang.realmsclient.client.Request$Get
+ com.mojang.realmsclient.client.Request$Post
- com.mojang.realmsclient.client.Request$Put
+ com.mojang.realmsclient.client.UploadStatus
- com.mojang.realmsclient.dto.package-info
- com.mojang.realmsclient.dto.ServerActivity
+ com.mojang.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
- com.mojang.realmsclient.exception.RealmsHttpException
+ com.mojang.realmsclient.exception.RealmsServiceException
- com.mojang.realmsclient.exception.RetryCallException
- com.mojang.realmsclient.gui.screens.package-info
- com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
+ com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoList
- com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsClientOutdatedScreen
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsConfirmScreen
- com.mojang.realmsclient.gui.screens.RealmsCreateRealmScreen
+ com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen
- com.mojang.realmsclient.gui.screens.RealmsInviteScreen
+ com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen
- com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$Type
+ com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTaskScreen
- com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
+ com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen$1
- com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$2
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$3
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$UserAction
+ com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$1
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$FrameButton
+ com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$1
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
- com.mojang.realmsclient.gui.screens.RealmsSettingsScreen
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen
- com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsTermsScreen
- com.mojang.realmsclient.gui.screens.RealmsUploadScreen
+ com.mojang.realmsclient.gui.screens.UploadResult
- com.mojang.realmsclient.gui.screens.UploadResult$1
+ com.mojang.realmsclient.gui.screens.UploadResult$Builder
+ com.mojang.realmsclient.KeyCombo
- com.mojang.realmsclient.package-info
- com.mojang.realmsclient.RealmsMainScreen
+ com.mojang.realmsclient.RealmsMainScreen$1
- com.mojang.realmsclient.RealmsMainScreen$2
+ com.mojang.realmsclient.RealmsMainScreen$3
- com.mojang.realmsclient.RealmsMainScreen$4
+ com.mojang.realmsclient.RealmsMainScreen$5
- com.mojang.realmsclient.RealmsMainScreen$CloseButton
+ com.mojang.realmsclient.RealmsMainScreen$Entry
- com.mojang.realmsclient.RealmsMainScreen$HoveredElement
+ com.mojang.realmsclient.RealmsMainScreen$NewsButton
- com.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
+ com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
- com.mojang.realmsclient.RealmsMainScreen$ServerEntry
+ com.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
- com.mojang.realmsclient.RealmsMainScreen$TrialEntry
+ com.mojang.realmsclient.Unit
- com.mojang.realmsclient.util.package-info
+ com.mojang.realmsclient.util.task.CloseServerTask
- com.mojang.realmsclient.util.task.ConnectTask
+ com.mojang.realmsclient.util.task.DownloadTask
- com.mojang.realmsclient.util.task.GetServerDetailsTask
+ com.mojang.realmsclient.util.task.LongRunningTask
- com.mojang.realmsclient.util.task.OpenServerTask
- com.mojang.realmsclient.util.task.package-info
+ com.mojang.realmsclient.util.task.ResettingGeneratedWorldTask
- com.mojang.realmsclient.util.task.ResettingTemplateWorldTask
+ com.mojang.realmsclient.util.task.ResettingWorldTask
- com.mojang.realmsclient.util.task.RestoreTask
+ com.mojang.realmsclient.util.task.SwitchMinigameTask
- com.mojang.realmsclient.util.task.SwitchSlotTask
+ com.mojang.realmsclient.util.task.WorldCreationTask
+ net.minecraft.client.gui.screens.mco.package-info
- net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
+ net.minecraft.client.gui.screens.multiplayer.package-info
+ net.minecraft.client.gui.screens.multiplayer.SafetyScreen
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- net.minecraft.client.gui.screens.package-info
- net.minecraft.client.gui.screens.packs.package-info
+ net.minecraft.client.gui.screens.packs.PackSelectionModel
- net.minecraft.client.gui.screens.packs.PackSelectionModel$Entry
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$EntryBase
- net.minecraft.client.gui.screens.packs.PackSelectionModel$SelectedPackEntry
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$UnselectedPackEntry
- net.minecraft.client.gui.screens.packs.PackSelectionScreen
+ net.minecraft.client.gui.screens.packs.PackSelectionScreen$Watcher
- net.minecraft.client.gui.screens.packs.TransferableSelectionList
+ net.minecraft.client.gui.screens.packs.TransferableSelectionList$PackEntry
+ net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.BlastingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.GhostRecipe
- net.minecraft.client.gui.screens.recipebook.GhostRecipe$GhostIngredient
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- net.minecraft.client.gui.screens.recipebook.package-info
+ net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.RecipeBookPage
+ net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
- net.minecraft.client.gui.screens.recipebook.RecipeButton
+ net.minecraft.client.gui.screens.recipebook.RecipeCollection
- net.minecraft.client.gui.screens.recipebook.RecipeShownListener
+ net.minecraft.client.gui.screens.recipebook.RecipeUpdateListener
- net.minecraft.client.gui.screens.recipebook.SmeltingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
- net.minecraft.client.gui.screens.social.package-info
+ net.minecraft.client.gui.screens.social.PlayerEntry
- net.minecraft.client.gui.screens.social.PlayerEntry$1
+ net.minecraft.client.gui.screens.social.PlayerEntry$2
- net.minecraft.client.gui.screens.social.PlayerSocialManager
+ net.minecraft.client.gui.screens.social.SocialInteractionsPlayerList
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$1
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$2
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
+ net.minecraft.client.gui.screens.stream.package-info
+ net.minecraft.client.map.Map$1
+ net.minecraft.client.map.Map$3
+ net.minecraft.client.model.AbstractZombieModel
- net.minecraft.client.model.AgeableListModel
+ net.minecraft.client.model.AnimationUtils
- net.minecraft.client.model.ArmedModel
+ net.minecraft.client.model.ArmorStandArmorModel
- net.minecraft.client.model.ArmorStandModel
+ net.minecraft.client.model.AxolotlModel
- net.minecraft.client.model.BatModel
+ net.minecraft.client.model.BeeModel
- net.minecraft.client.model.BlazeModel
+ net.minecraft.client.model.BoatModel
- net.minecraft.client.model.BookModel
+ net.minecraft.client.model.CatModel
- net.minecraft.client.model.ChestedHorseModel
+ net.minecraft.client.model.ChickenModel
- net.minecraft.client.model.CodModel
+ net.minecraft.client.model.ColorableAgeableListModel
- net.minecraft.client.model.ColorableHierarchicalModel
+ net.minecraft.client.model.CowModel
- net.minecraft.client.model.CreeperModel
+ net.minecraft.client.model.DolphinModel
- net.minecraft.client.model.DrownedModel
+ net.minecraft.client.model.ElytraModel
- net.minecraft.client.model.EndermanModel
+ net.minecraft.client.model.EndermiteModel
- net.minecraft.client.model.EntityModel
+ net.minecraft.client.model.EvokerFangsModel
- net.minecraft.client.model.FoxModel
+ net.minecraft.client.model.GhastModel
- net.minecraft.client.model.GiantZombieModel
- net.minecraft.client.multiplayer.ClientPacketListener
+ net.minecraft.client.multiplayer.ClientPacketListener$1
- net.minecraft.client.multiplayer.ClientSuggestionProvider
+ net.minecraft.client.multiplayer.MultiPlayerGameMode
+ net.minecraft.client.multiplayer.package-info
- net.minecraft.client.multiplayer.PlayerInfo
+ net.minecraft.client.multiplayer.ServerAddress
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.multiplayer.ServerStatusPinger$2$1
- net.minecraft.client.package-info
+ net.minecraft.client.particle.AshParticle
- net.minecraft.client.particle.AshParticle$Provider
+ net.minecraft.client.particle.AttackSweepParticle
- net.minecraft.client.particle.AttackSweepParticle$1
+ net.minecraft.client.particle.AttackSweepParticle$Provider
+ net.minecraft.client.particle.BarrierParticle$1
- net.minecraft.client.particle.StationaryItemParticle
- net.minecraft.client.particle.StationaryItemParticle$BarrierProvider
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
+ net.minecraft.client.renderer.block.model.ItemOverride$Predicate
- net.minecraft.client.renderer.block.model.ItemOverrides
+ net.minecraft.client.renderer.block.model.ItemOverrides$1
- net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
+ net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
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
- net.minecraft.client.renderer.entity.GoatRenderer
+ net.minecraft.client.renderer.entity.GuardianRenderer
- net.minecraft.client.renderer.entity.HoglinRenderer
+ net.minecraft.client.renderer.entity.HorseRenderer
- net.minecraft.client.renderer.entity.HumanoidMobRenderer
+ net.minecraft.client.renderer.entity.HuskRenderer
- net.minecraft.client.renderer.entity.IllagerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer$1
+ net.minecraft.client.renderer.entity.IronGolemRenderer
- net.minecraft.client.renderer.entity.ItemEntityRenderer
+ net.minecraft.client.renderer.entity.ItemFrameRenderer
- net.minecraft.client.renderer.entity.ItemRenderer
- net.minecraft.client.renderer.entity.layers.ArrowLayer
+ net.minecraft.client.renderer.entity.layers.BeeStingerLayer
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
- net.minecraft.client.renderer.entity.layers.package-info
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
- net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
+ net.minecraft.client.renderer.entity.layers.WitchItemLayer
- net.minecraft.client.renderer.entity.layers.WitherArmorLayer
+ net.minecraft.client.renderer.entity.layers.WolfCollarLayer
+ net.minecraft.client.renderer.entity.LeashKnotRenderer
- net.minecraft.client.renderer.entity.LightningBoltRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer$1
+ net.minecraft.client.renderer.entity.LlamaRenderer
- net.minecraft.client.renderer.entity.LlamaSpitRenderer
+ net.minecraft.client.renderer.entity.MagmaCubeRenderer
- net.minecraft.client.renderer.entity.MinecartRenderer
+ net.minecraft.client.renderer.entity.MobRenderer
- net.minecraft.client.renderer.entity.MushroomCowRenderer
+ net.minecraft.client.renderer.entity.OcelotRenderer
+ net.minecraft.client.renderer.entity.package-info
- net.minecraft.client.renderer.entity.PaintingRenderer
+ net.minecraft.client.renderer.entity.PandaRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer
+ net.minecraft.client.renderer.entity.PhantomRenderer
+ net.minecraft.client.renderer.entity.PiglinRenderer
- net.minecraft.client.renderer.entity.PigRenderer
- net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.player.package-info
- net.minecraft.client.renderer.entity.player.PlayerRenderer
+ net.minecraft.client.renderer.entity.PolarBearRenderer
- net.minecraft.client.renderer.entity.PufferfishRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer
- net.minecraft.client.renderer.entity.RavagerRenderer
+ net.minecraft.client.renderer.entity.RenderLayerParent
- net.minecraft.client.renderer.entity.SalmonRenderer
+ net.minecraft.client.renderer.entity.SheepRenderer
- net.minecraft.client.renderer.entity.ShulkerBulletRenderer
+ net.minecraft.client.renderer.entity.ShulkerRenderer
- net.minecraft.client.renderer.entity.SilverfishRenderer
+ net.minecraft.client.renderer.entity.SkeletonRenderer
- net.minecraft.client.renderer.entity.SlimeRenderer
+ net.minecraft.client.renderer.entity.SnowGolemRenderer
- net.minecraft.client.renderer.entity.SpectralArrowRenderer
+ net.minecraft.client.renderer.entity.SpiderRenderer
- net.minecraft.client.renderer.entity.SquidRenderer
+ net.minecraft.client.renderer.entity.StrayRenderer
- net.minecraft.client.renderer.entity.StriderRenderer
+ net.minecraft.client.renderer.entity.ThrownItemRenderer
- net.minecraft.client.renderer.entity.ThrownTridentRenderer
+ net.minecraft.client.renderer.entity.TippableArrowRenderer
- net.minecraft.client.renderer.entity.TntMinecartRenderer
+ net.minecraft.client.renderer.entity.TntRenderer
- net.minecraft.client.renderer.entity.TropicalFishRenderer
+ net.minecraft.client.renderer.entity.TurtleRenderer
- net.minecraft.client.renderer.entity.UndeadHorseRenderer
+ net.minecraft.client.renderer.entity.VexRenderer
- net.minecraft.client.renderer.entity.VillagerRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer$1
+ net.minecraft.client.renderer.entity.WanderingTraderRenderer
- net.minecraft.client.renderer.entity.WitchRenderer
+ net.minecraft.client.renderer.entity.WitherBossRenderer
- net.minecraft.client.renderer.entity.WitherSkeletonRenderer
+ net.minecraft.client.renderer.entity.WitherSkullRenderer
- net.minecraft.client.renderer.entity.WolfRenderer
+ net.minecraft.client.renderer.entity.ZoglinRenderer
- net.minecraft.client.renderer.entity.ZombieRenderer
+ net.minecraft.client.renderer.entity.ZombieVillagerRenderer
- net.minecraft.client.renderer.item.ItemProperties
+ net.minecraft.client.renderer.item.ItemProperties$1
- net.minecraft.client.renderer.item.ItemProperties$2
+ net.minecraft.client.renderer.item.ItemProperties$CompassWobble
- net.minecraft.client.renderer.item.ItemPropertyFunction
+ net.minecraft.client.renderer.item.package-info
- net.minecraft.client.renderer.package-info
+ net.minecraft.client.renderer.texture.AbstractTexture
- net.minecraft.client.renderer.texture.AtlasSet
+ net.minecraft.client.renderer.texture.DynamicTexture
- net.minecraft.client.renderer.texture.HttpTexture
+ net.minecraft.client.renderer.texture.MipmapGenerator
- net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
+ net.minecraft.client.renderer.texture.OverlayTexture
- net.minecraft.client.renderer.texture.package-info
- net.minecraft.client.renderer.texture.PreloadedTexture
+ net.minecraft.client.renderer.texture.SimpleTexture
- net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
+ net.minecraft.client.renderer.texture.Stitcher
- net.minecraft.client.renderer.texture.Stitcher$Holder
+ net.minecraft.client.renderer.texture.Stitcher$Region
- net.minecraft.client.renderer.texture.Stitcher$SpriteLoader
+ net.minecraft.client.renderer.texture.StitcherException
- net.minecraft.client.renderer.texture.TextureAtlas
+ net.minecraft.client.renderer.texture.TextureAtlas$Preparations
- net.minecraft.client.renderer.texture.TextureAtlasSprite
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$1
- net.minecraft.client.renderer.texture.TextureAtlasSprite$AnimatedTexture
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$FrameInfo
- net.minecraft.client.renderer.texture.TextureAtlasSprite$Info
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$InterpolationData
- net.minecraft.client.renderer.texture.TextureManager
+ net.minecraft.client.renderer.texture.Tickable
+ net.minecraft.client.resources.AssetIndex
- net.minecraft.client.resources.ClientPackSource
+ net.minecraft.client.resources.ClientPackSource$1
- net.minecraft.client.resources.ClientPackSource$2
+ net.minecraft.client.resources.DefaultClientPackResources
- net.minecraft.client.resources.DefaultPlayerSkin
+ net.minecraft.client.resources.DirectAssetIndex
- net.minecraft.client.resources.FoliageColorReloadListener
+ net.minecraft.client.resources.GrassColorReloadListener
- net.minecraft.client.resources.language.ClientLanguage
+ net.minecraft.client.resources.language.FormattedBidiReorder
- net.minecraft.client.resources.language.I18n
+ net.minecraft.client.resources.language.LanguageInfo
- net.minecraft.client.resources.language.LanguageManager
+ net.minecraft.client.resources.language.package-info
- net.minecraft.client.resources.LegacyPackResourcesAdapter
+ net.minecraft.client.resources.LegacyStuffWrapper
- net.minecraft.client.resources.metadata.animation.AnimationFrame
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$FrameOutput
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
- net.minecraft.client.resources.metadata.animation.package-info
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
+ net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSection
- net.minecraft.client.resources.metadata.language.LanguageMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.language.package-info
- net.minecraft.client.resources.metadata.package-info
+ net.minecraft.client.resources.metadata.texture.package-info
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSection
- net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
- net.minecraft.client.resources.MobEffectTextureManager
- net.minecraft.client.resources.model.BakedModel
+ net.minecraft.client.resources.model.BlockModelRotation
- net.minecraft.client.resources.model.BuiltInModel
+ net.minecraft.client.resources.model.Material
- net.minecraft.client.resources.model.ModelBakery
+ net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
- net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
+ net.minecraft.client.resources.model.ModelManager
- net.minecraft.client.resources.model.ModelResourceLocation
+ net.minecraft.client.resources.model.ModelState
- net.minecraft.client.resources.model.MultiPartBakedModel
+ net.minecraft.client.resources.model.MultiPartBakedModel$Builder
- net.minecraft.client.resources.model.SimpleBakedModel
+ net.minecraft.client.resources.model.SimpleBakedModel$Builder
- net.minecraft.client.resources.model.UnbakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel
- net.minecraft.client.resources.model.WeightedBakedModel$Builder
+ net.minecraft.client.resources.model.WeightedBakedModel$WeightedModel
+ net.minecraft.client.resources.PackResourcesAdapterV4
- net.minecraft.client.resources.PaintingTextureManager
+ net.minecraft.client.resources.SkinManager
- net.minecraft.client.resources.SkinManager$1
+ net.minecraft.client.resources.SkinManager$SkinTextureCallback
- net.minecraft.client.resources.SplashManager
+ net.minecraft.client.resources.TextureAtlasHolder
+ net.minecraft.client.sounds.AudioStream
- net.minecraft.client.sounds.ChannelAccess
+ net.minecraft.client.sounds.ChannelAccess$ChannelHandle
- net.minecraft.client.sounds.LoopingAudioStream
+ net.minecraft.client.sounds.LoopingAudioStream$1
- net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
+ net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
- net.minecraft.client.sounds.MusicManager
- net.minecraft.client.sounds.package-info
+ net.minecraft.client.sounds.SoundBufferLibrary
- net.minecraft.client.sounds.SoundEngine
+ net.minecraft.client.sounds.SoundEngineExecutor
- net.minecraft.client.sounds.SoundEventListener
+ net.minecraft.client.sounds.SoundManager
- net.minecraft.client.sounds.SoundManager$1
+ net.minecraft.client.sounds.SoundManager$2
- net.minecraft.client.sounds.SoundManager$Preparations
+ net.minecraft.client.sounds.SoundManager$Preparations$1
- net.minecraft.client.sounds.WeighedSoundEvents
+ net.minecraft.client.sounds.Weighted
+ net.minecraft.client.tutorial.BundleTutorial
- net.minecraft.client.tutorial.CompletedTutorialStepInstance
+ net.minecraft.client.tutorial.CraftPlanksTutorialStep
- net.minecraft.client.tutorial.FindTreeTutorialStepInstance
+ net.minecraft.client.tutorial.MovementTutorialStepInstance
- net.minecraft.client.tutorial.OpenInventoryTutorialStep
+ net.minecraft.client.tutorial.package-info
+ net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
- net.minecraft.client.tutorial.Tutorial
+ net.minecraft.client.tutorial.Tutorial$1
- net.minecraft.client.tutorial.Tutorial$TimedToast
+ net.minecraft.client.tutorial.TutorialStepInstance
- net.minecraft.client.tutorial.TutorialSteps
+ net.minecraft.commands.arguments.AngleArgument
- net.minecraft.commands.arguments.AngleArgument$1
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.blocks.BlockStateArgument
+ net.minecraft.commands.arguments.blocks.BlockStateParser
- net.minecraft.commands.arguments.blocks.package-info
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
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
+ net.minecraft.commands.arguments.DimensionArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Serializer
- net.minecraft.commands.arguments.EntitySummonArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
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
- net.minecraft.commands.arguments.ItemEnchantmentArgument
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
- net.minecraft.commands.arguments.MobEffectArgument
+ net.minecraft.commands.arguments.NbtPathArgument
- net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
+ net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
- net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
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
- net.minecraft.commands.BrigadierExceptions
+ net.minecraft.commands.CommandFunction
- net.minecraft.commands.CommandFunction$CacheableFunction
+ net.minecraft.commands.CommandFunction$CommandEntry
- net.minecraft.commands.CommandFunction$Entry
+ net.minecraft.commands.CommandFunction$FunctionEntry
- net.minecraft.commands.CommandRuntimeException
- net.minecraft.commands.Commands
+ net.minecraft.commands.Commands$CommandSelection
- net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.SharedSuggestionProvider
- net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.DontObfuscateOrShrink
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
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$1
+ net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$1
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.AttributeCommand
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$Mode
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
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
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
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.SetBlockCommand
- net.minecraft.server.commands.SetBlockCommand$Filter
+ net.minecraft.server.commands.SetBlockCommand$Mode
- net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
+ net.minecraft.server.commands.SetSpawnCommand
- net.minecraft.server.commands.SetWorldSpawnCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.commands.SpreadPlayersCommand$1
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
+ net.minecraft.server.DebugLoggedPrintStream
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
- net.minecraft.server.Eula
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
+ net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
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
- net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$1
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerLevel$1
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayer$1
+ net.minecraft.server.level.ServerPlayer$2
- net.minecraft.server.level.ServerPlayer$3
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.WorldGenRegion
+ net.minecraft.server.level.WorldGenTickList
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
+ net.minecraft.server.network.ServerConnectionListener
- net.minecraft.server.network.ServerConnectionListener$1
+ net.minecraft.server.network.ServerConnectionListener$2
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- net.minecraft.server.network.ServerGamePacketListenerImpl
+ net.minecraft.server.network.ServerGamePacketListenerImpl$1
- net.minecraft.server.network.ServerGamePacketListenerImpl$2
+ net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
- net.minecraft.server.network.ServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl$State
+ net.minecraft.server.network.ServerPlayerConnection
- net.minecraft.server.network.ServerStatusPacketListenerImpl
+ net.minecraft.server.network.TextFilter
- net.minecraft.server.network.TextFilter$1
+ net.minecraft.server.network.TextFilter$FilteredText
- net.minecraft.server.network.TextFilterClient
+ net.minecraft.server.network.TextFilterClient$1
- net.minecraft.server.network.TextFilterClient$IgnoreStrategy
+ net.minecraft.server.network.TextFilterClient$PlayerContext
- net.minecraft.server.network.TextFilterClient$RequestFailedException
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractPackResources
- net.minecraft.server.packs.FilePackResources
+ net.minecraft.server.packs.FolderPackResources
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackType
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
- net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.package-info
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
- net.minecraft.server.packs.resources.ResourceProvider
+ net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
- net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
+ net.minecraft.server.packs.resources.SimpleReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadInstance$1
+ net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
+ net.minecraft.server.packs.resources.SimpleResource
+ net.minecraft.server.packs.VanillaPackResources
- net.minecraft.server.packs.VanillaPackResources$1
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
+ net.minecraft.server.players.BanListEntry
- net.minecraft.server.players.GameProfileCache
+ net.minecraft.server.players.GameProfileCache$1
- net.minecraft.server.players.GameProfileCache$GameProfileInfo
+ net.minecraft.server.players.IpBanList
- net.minecraft.server.players.IpBanListEntry
+ net.minecraft.server.players.OldUsersConverter
- net.minecraft.server.players.OldUsersConverter$1
+ net.minecraft.server.players.OldUsersConverter$2
- net.minecraft.server.players.OldUsersConverter$3
+ net.minecraft.server.players.OldUsersConverter$4
- net.minecraft.server.players.OldUsersConverter$5
+ net.minecraft.server.players.OldUsersConverter$ConversionError
+ net.minecraft.server.players.package-info
- net.minecraft.server.players.PlayerList
+ net.minecraft.server.players.PlayerList$1
- net.minecraft.server.players.ServerOpList
+ net.minecraft.server.players.ServerOpListEntry
- net.minecraft.server.players.SleepStatus
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
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerResources
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.TickTask
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
- net.minecraft.tags.GameEventTags
+ net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
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
- net.minecraft.tags.TagCollection$NetworkPayload
+ net.minecraft.tags.TagContainer
- net.minecraft.tags.TagContainer$1
+ net.minecraft.tags.TagContainer$Builder
- net.minecraft.tags.TagContainer$CollectionConsumer
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$1
- net.minecraft.tags.TagManager$LoaderInfo
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClampedNormalFloat
+ net.minecraft.util.ConstantFloat
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CryptException
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
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
+ net.minecraft.util.datafix.fixes.CauldronRenameFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.DyeItemRenameFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ net.minecraft.util.datafix.fixes.NamedEntityFix
- net.minecraft.util.datafix.fixes.NewVillageFix
+ net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
- net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
+ net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenameBiomesFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
- net.minecraft.util.datafix.fixes.SavedDataUUIDFix
+ net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
- net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.SwimStatsRenameFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
+ net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_7
- net.minecraft.util.datafix.schemas.V1460
+ net.minecraft.util.datafix.schemas.V1460$1
- net.minecraft.util.datafix.schemas.V1466
+ net.minecraft.util.datafix.schemas.V1470
- net.minecraft.util.datafix.schemas.V1481
+ net.minecraft.util.datafix.schemas.V1483
- net.minecraft.util.datafix.schemas.V1486
+ net.minecraft.util.datafix.schemas.V1510
- net.minecraft.util.datafix.schemas.V1800
+ net.minecraft.util.datafix.schemas.V1801
- net.minecraft.util.datafix.schemas.V1904
+ net.minecraft.util.datafix.schemas.V1906
- net.minecraft.util.datafix.schemas.V1909
+ net.minecraft.util.datafix.schemas.V1920
- net.minecraft.util.datafix.schemas.V1928
+ net.minecraft.util.datafix.schemas.V1929
- net.minecraft.util.datafix.schemas.V1931
+ net.minecraft.util.datafix.schemas.V2100
- net.minecraft.util.datafix.schemas.V2501
+ net.minecraft.util.datafix.schemas.V2502
- net.minecraft.util.datafix.schemas.V2505
+ net.minecraft.util.datafix.schemas.V2509
- net.minecraft.util.datafix.schemas.V2519
+ net.minecraft.util.datafix.schemas.V2522
- net.minecraft.util.datafix.schemas.V2551
+ net.minecraft.util.datafix.schemas.V2568
- net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2704
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
- net.minecraft.util.DebugBuffer
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.ExtraCodecs
+ net.minecraft.util.ExtraCodecs$1
+ net.minecraft.util.FloatProvider
+ net.minecraft.util.GlslPreprocessor$1
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HeapDumper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
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
- net.minecraft.util.profiling.registry.MeasuredMetric
+ net.minecraft.util.profiling.registry.MeasurementCategory
- net.minecraft.util.profiling.registry.MeasurementRegistry
+ net.minecraft.util.profiling.registry.Metric
+ net.minecraft.util.profiling.registry.package-info
- net.minecraft.util.profiling.registry.ProfilerMeasured
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry$1
- net.minecraft.util.random.WeightedEntry$Wrapper
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
+ net.minecraft.util.TrapezoidFloat
- net.minecraft.util.Tuple
+ net.minecraft.util.UniformFloat
+ net.minecraft.util.Unit
- net.minecraft.util.valueproviders.ConstantFloat
- net.minecraft.util.valueproviders.FloatProvider
- net.minecraft.util.valueproviders.IntProvider
- net.minecraft.util.valueproviders.TrapezoidFloat
- net.minecraft.util.valueproviders.UniformInt
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.world.entity.ai.behavior.AnimalPanic
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
+ net.minecraft.world.entity.ai.behavior.CountDownTemptationTicks
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
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
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.ShufflingList$1
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.WeightedList$1
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
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
+ net.minecraft.world.entity.ai.sensing.AxolotlHostileSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HostilesSensor
- net.minecraft.world.entity.ai.sensing.package-info
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
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
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
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$1
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
- net.minecraft.world.entity.animal.goat.GoatAi
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
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
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
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
+ net.minecraft.world.level.block.MultifaceBlock
- net.minecraft.world.level.block.MushroomBlock
+ net.minecraft.world.level.block.MyceliumBlock
- net.minecraft.world.level.block.NetherPortalBlock
+ net.minecraft.world.level.block.NetherPortalBlock$1
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
+ net.minecraft.world.level.block.piston.PistonMath$1
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PotatoBlock
+ net.minecraft.world.level.block.PowderSnowBlock
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
- net.minecraft.world.level.block.RodBlock
+ net.minecraft.world.level.block.RodBlock$1
- net.minecraft.world.level.block.RootedDirtBlock
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkSensorBlock
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
- net.minecraft.world.level.block.SmallDripleafBlock
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
+ net.minecraft.world.level.block.SporeBlossomBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
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
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$1
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
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
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
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
- net.minecraft.world.level.chunk.BulkSectionAccess
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
+ net.minecraft.world.level.chunk.FeatureAccess
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
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
- net.minecraft.world.level.chunk.storage.EntityStorage
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.IOWorker$Priority
- net.minecraft.world.level.chunk.storage.OldChunkStorage
+ net.minecraft.world.level.chunk.storage.OldChunkStorage$1
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
- net.minecraft.world.level.dimension.DimensionDefaults
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CarverDebugSettings
- net.minecraft.world.level.levelgen.carver.CarvingContext
- net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.package-info
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
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
- net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
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
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.blaze3d.Blaze3D +3M
```
```
XXX.blaze3d.font.GlyphInfo +1M
```
```
XXX.blaze3d.pipeline.RenderTarget +1M | +4P
```
```
XXX.blaze3d.platform.GlStateManager +10M | +1P
```
```
XXX.blaze3d.platform.GlStateManager$Viewport +4M
```
```
XXX.blaze3d.platform.InputConstants +1M | +125P
```
```
XXX.blaze3d.platform.Lighting +1M
```
```
XXX.blaze3d.platform.NativeImage +8M | +4P
```
```
XXX.blaze3d.platform.NativeImage$Format +14M
```
```
XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel +1P
```
```
XXX.blaze3d.platform.TextureUtil +2M | +2P
```
```
XXX.mojang.math.OctahedralGroup +2M
```
```
XXX.mojang.math.Quaternion +9M
```
```
XXX.mojang.math.Transformation +4M
```
```
XXX.mojang.math.Vector3f +5M -3M
```
```
XXX.realmsclient.dto.RealmsWorldOptions +11P
```
```
XXX.realmsclient.dto.UploadInfo +2P
```
```
XXX.realmsclient.util.RealmsUtil +1M | +3P
```
```
XXX.realmsclient.util.TextRenderingUtils$Line +1M
```
```
XXX.realmsclient.util.UploadTokenCache +1M
```
```
net.minecraft.FileUtil +1P
```
```
net.minecraft.SharedConstants +81P
```
```
XXX.minecraft.client.Camera +1P
```
```
XXX.minecraft.client.ClientBrandRetriever +1P
```
```
XXX.minecraft.client.KeyMapping +7P
```
```
XXX.minecraft.client.Minecraft +1P
```
```
XXX.color.block.BlockColors +1P
```
```
XXX.color.item.ItemColors +1P
```
```
XXX.client.gui.Font +1P
```
```
XXX.client.gui.Gui +6P
```
```
XXX.client.gui.MapRenderer +2M -3M | +2P
```
```
XXX.client.gui.MapRenderer$MapInstance -1M
```
```
XXX.gui.components.AbstractWidget +2P
```
```
XXX.gui.components.ChatComponent +1P
```
```
XXX.gui.components.DebugScreenOverlay +7P
```
```
XXX.gui.components.EditBox +10P
```
```
XXX.gui.components.LerpingBossEvent +1P
```
```
XXX.gui.components.SubtitleOverlay +1P
```
```
XXX.components.toasts.RecipeToast +1P
```
```
XXX.components.toasts.TutorialToast +4P
```
```
XXX.gui.font.FontManager +1P
```
```
XXX.font.glyphs.MissingGlyph +2P
```
```
XXX.font.providers.LegacyUnicodeBitmapsProvider +3P
```
```
XXX.gui.screens.ChatScreen +1P
```
```
XXX.gui.screens.ConnectScreen +1P
```
```
XXX.gui.screens.CreateFlatWorldScreen +7P
```
```
XXX.gui.screens.LevelLoadingScreen +1P
```
```
XXX.gui.screens.PauseScreen +3P
```
```
XXX.gui.screens.TitleScreen +2P
```
```
XXX.gui.screens.WinScreen +1P
```
```
XXX.screens.debug.GameModeSwitcherScreen +6P
```
```
XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon +2P
```
```
XXX.screens.inventory.AbstractContainerScreen +5P
```
```
XXX.inventory.tooltip.ClientBundleTooltip +5P
```
```
XXX.spectator.categories.SpectatorPage +1P
```
```
XXX.client.model.GuardianModel +4P
```
```
XXX.client.model.HorseModel +17P
```
```
XXX.client.model.LavaSlimeModel +1P
```
```
XXX.client.model.LlamaSpitModel +1P
```
```
XXX.client.model.OcelotModel +21P
```
```
XXX.client.model.ParrotModel +1P
```
```
XXX.client.model.PlayerModel +6P
```
```
XXX.client.model.RabbitModel +5P
```
```
XXX.client.model.SalmonModel +2P
```
```
XXX.client.model.ShulkerBulletModel +1P
```
```
XXX.client.model.SilverfishModel +1P
```
```
XXX.client.model.SpiderModel +6P
```
```
XXX.client.model.StriderModel +6P
```
```
XXX.client.model.TurtleModel +1P
```
```
XXX.client.model.WolfModel +4P
```
```
XXX.model.geom.ModelLayers +2P
```
```
XXX.model.geom.PartNames +57P
```
```
XXX.client.particle.DragonBreathParticle +8P
```
```
XXX.client.particle.ItemPickupParticle +1P
```
```
XXX.client.player.AbstractClientPlayer +11P
```
```
XXX.client.player.KeyboardInput +1P
```
```
XXX.client.profiling.ActiveClientMetricsLogger +1P
```
```
XXX.profiling.storage.MetricsPersister +3P
```
```
XXX.client.renderer.FogRenderer +2P
```
```
XXX.client.renderer.GameRenderer +1M | +3P
```
```
XXX.client.renderer.LightTexture +3P
```
```
XXX.client.renderer.RenderType +6P
```
```
XXX.client.renderer.ShaderInstance +3P
```
```
XXX.renderer.blockentity.BeaconRenderer +1P
```
```
XXX.renderer.blockentity.BellRenderer +1P
```
```
XXX.renderer.blockentity.ChestRenderer +3P
```
```
XXX.renderer.blockentity.SignRenderer +3P
```
```
XXX.renderer.blockentity.TheEndGatewayRenderer +2M -1M
```
```
XXX.renderer.chunk.VisGraph +8P
```
```
XXX.renderer.debug.BeeDebugRenderer +26P
```
```
XXX.renderer.debug.GameTestDebugRenderer +1P
```
```
XXX.renderer.debug.GoalSelectorDebugRenderer +1P
```
```
XXX.renderer.debug.HeightMapRenderer +2P
```
```
XXX.renderer.debug.LightDebugRenderer +1P
```
```
XXX.renderer.debug.PathfindingRenderer +8P
```
```
XXX.renderer.debug.VillageSectionsDebugRenderer +1P
```
```
XXX.renderer.entity.EntityRenderers +1P
```
```
XXX.resources.sounds.BeeSoundInstance +3P
```
```
XXX.resources.sounds.ElytraOnPlayerSoundInstance +1P
```
```
XXX.resources.sounds.GuardianAttackSoundInstance +4P
```
```
XXX.resources.sounds.RidingMinecartSoundInstance +2P
```
```
XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance +1P
```
```
XXX.client.searchtree.SuffixArray +2P
```
```
XXX.client.server.IntegratedServer +1P
```
```
XXX.synchronization.brigadier.BrigadierArgumentSerializers +2P
```
```
XXX.minecraft.core.BlockPos +1P
```
```
XXX.minecraft.core.FrontAndTop +1M
```
```
XXX.minecraft.core.Registry +25M -23M | +4P
```
```
XXX.core.particles.DustParticleOptionsBase +2P
```
```
XXX.minecraft.data.BlockFamilies +2P
```
```
XXX.data.worldgen.Carvers +3P
```
```
XXX.data.worldgen.Features +2M | +22P
```
```
XXX.gametest.framework.GameTestBatch +1P
```
```
XXX.gametest.framework.GameTestRunner +5P
```
```
XXX.gametest.framework.GameTestSequence$Condition +1P
```
```
XXX.gametest.framework.MultipleTestTracker +5P
```
```
XXX.minecraft.nbt.ByteArrayTag +1P
```
```
XXX.minecraft.nbt.ByteTag +1P
```
```
XXX.minecraft.nbt.CompoundTag +2P
```
```
XXX.minecraft.nbt.DoubleTag +1P
```
```
XXX.minecraft.nbt.EndTag +1P
```
```
XXX.minecraft.nbt.FloatTag +1P
```
```
XXX.minecraft.nbt.IntArrayTag +1P
```
```
XXX.minecraft.nbt.IntTag +1P
```
```
XXX.minecraft.nbt.IntTag$Cache +2P
```
```
XXX.minecraft.nbt.NbtUtils +7P
```
```
XXX.minecraft.nbt.ShortTag +1P
```
```
XXX.minecraft.nbt.ShortTag$Cache +2P
```
```
XXX.minecraft.nbt.StringTag +5P
```
```
XXX.minecraft.nbt.TagParser +6P
```
```
XXX.minecraft.network.CompressionDecoder +1P
```
```
XXX.minecraft.network.Connection +1P
```
```
XXX.minecraft.network.ConnectionProtocol +2P
```
```
XXX.minecraft.network.FriendlyByteBuf +5P
```
```
XXX.network.chat.NbtComponent +1P
```
```
XXX.network.chat.ScoreComponent +1P
```
```
XXX.network.chat.TextColor +1P
```
```
XXX.protocol.game.ClientboundAddEntityPacket +2P
```
```
XXX.protocol.game.ClientboundAnimatePacket +6P
```
```
XXX.protocol.game.ClientboundBlockEntityDataPacket +13P
```
```
XXX.protocol.game.ClientboundCustomSoundPacket +1P
```
```
XXX.protocol.game.ClientboundLevelChunkPacket +1P
```
```
XXX.protocol.game.ClientboundLoginPacket +1P
```
```
XXX.protocol.game.ClientboundPlayerAbilitiesPacket +4P
```
```
XXX.protocol.game.ClientboundResourcePackPacket +1P
```
```
XXX.protocol.game.ClientboundSetEquipmentPacket +1P
```
```
XXX.protocol.game.ClientboundSoundPacket +1P
```
```
XXX.protocol.game.ServerboundChatPacket +1P
```
```
XXX.protocol.game.ServerboundCustomPayloadPacket +1P
```
```
XXX.protocol.game.ServerboundPlayerAbilitiesPacket +1P
```
```
XXX.protocol.game.ServerboundSetCommandBlockPacket +3P
```
```
XXX.protocol.game.ServerboundSetStructureBlockPacket +3P
```
```
XXX.minecraft.util.FrameTimer +1P
```
```
XXX.minecraft.util.Mth +16P
```
```
XXX.minecraft.util.SortedArraySet +1P
```
```
XXX.minecraft.world.DifficultyInstance +3P
```
```
XXX.minecraft.world.LockCode +1P
```
```
XXX.world.damagesource.CombatRules +5P
```
```
XXX.world.entity.Entity +22P
```
```
XXX.world.entity.EntityEvent +57P
```
```
XXX.world.entity.LivingEntity +2M | +20P
```
```
XXX.world.entity.Mob +9P
```
```
XXX.world.entity.MobCategory +1P
```
```
XXX.world.entity.NeutralMob +2P
```
```
XXX.entity.ai.Brain +1P
```
```
XXX.ai.attributes.Attribute +1P
```
```
XXX.ai.behavior.AcquirePoi$JitteredLinearRetry +3P
```
```
XXX.ai.behavior.Mount +1P
```
```
XXX.ai.behavior.MoveToTargetSink +1P
```
```
XXX.ai.behavior.RandomStroll +2P
```
```
XXX.ai.behavior.RunSometimes +2M -2M | +1P -1P
```
```
XXX.ai.behavior.ShowTradesToPlayer +2P
```
```
XXX.ai.behavior.SocializeAtBell +1P
```
```
XXX.ai.behavior.UseBonemeal +1P
```
```
XXX.ai.behavior.VillagerCalmDown +1P
```
```
XXX.ai.behavior.VillagerMakeLove +2P
```
```
XXX.ai.behavior.WorkAtPoi +2P
```
```
XXX.ai.control.MoveControl +3P
```
```
XXX.ai.control.SmoothSwimmingLookControl +2P
```
```
XXX.ai.goal.BreakDoorGoal +1P
```
```
XXX.ai.goal.FollowParentGoal +3P
```
```
XXX.ai.goal.GolemRandomStrollInVillageGoal +4P
```
```
XXX.ai.goal.MeleeAttackGoal +1P
```
```
XXX.ai.goal.RandomStrollGoal +1P
```
```
XXX.ai.goal.RangedCrossbowAttackGoal +1P -1P
```
```
XXX.ai.goal.RemoveBlockGoal +1P
```
```
XXX.ai.goal.StrollThroughVillageGoal +1P
```
```
XXX.ai.sensing.NearestBedSensor +3P
```
```
XXX.animal.horse.AbstractChestedHorse +1P
```
```
XXX.animal.horse.AbstractHorse +12P
```
```
XXX.animal.horse.SkeletonHorse +1P
```
```
XXX.boss.enderdragon.EnderDragon +3P
```
```
XXX.enderdragon.phases.DragonChargePlayerPhase +1P
```
```
XXX.enderdragon.phases.DragonSittingFlamingPhase +3P
```
```
XXX.enderdragon.phases.DragonStrafePlayerPhase +1P
```
```
XXX.boss.wither.WitherBoss +1P
```
```
XXX.entity.decoration.ItemFrame +1P
```
```
XXX.entity.item.ItemEntity +3P
```
```
XXX.entity.monster.AbstractSkeleton +1M
```
```
XXX.entity.monster.Endermite +1P
```
```
XXX.entity.monster.Guardian +1P
```
```
XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal +1P
```
```
XXX.entity.monster.Pillager +3P
```
```
XXX.entity.monster.Ravager +8P
```
```
XXX.entity.monster.Slime +2P
```
```
XXX.entity.monster.Spider +1P
```
```
XXX.entity.monster.Vindicator +1P
```
```
XXX.entity.monster.Zoglin +10P
```
```
XXX.entity.monster.ZombieVillager +4P
```
```
XXX.monster.hoglin.Hoglin +8P
```
```
XXX.monster.hoglin.HoglinBase +1P
```
```
XXX.monster.piglin.Piglin +9P
```
```
XXX.monster.piglin.PiglinBruteAi +10P
```
```
XXX.entity.npc.AbstractVillager +2P
```
```
XXX.entity.npc.VillagerData +2P
```
```
XXX.entity.npc.WanderingTrader +1P
```
```
XXX.entity.npc.WanderingTraderSpawner +7P
```
```
XXX.entity.player.Player +11P
```
```
XXX.entity.player.StackedContents +1P
```
```
XXX.entity.projectile.DragonFireball +1P
```
```
XXX.entity.projectile.ShulkerBullet +1P
```
```
XXX.entity.raid.Raids +1P
```
```
XXX.entity.schedule.Activity +1P
```
```
XXX.entity.schedule.Schedule +2P
```
```
XXX.entity.vehicle.Boat +6P
```
```
XXX.entity.vehicle.MinecartHopper +1P
```
```
XXX.world.food.Foods +1M -1M
```
```
XXX.world.inventory.AbstractContainerMenu +8P
```
```
XXX.world.inventory.AbstractFurnaceMenu +9P
```
```
XXX.world.inventory.DispenserMenu +5P
```
```
XXX.world.inventory.GrindstoneMenu +8P
```
```
XXX.world.inventory.ItemCombinerMenu +7P
```
```
XXX.world.inventory.MerchantMenu +11P
```
```
XXX.world.inventory.ShulkerBoxMenu +1P
```
```
XXX.world.item.BannerItem +1P
```
```
XXX.world.item.BowItem +2P
```
```
XXX.world.item.CrossbowItem +8P
```
```
XXX.world.item.FireworkRocketItem +10P
```
```
XXX.world.item.Item +3P
```
```
XXX.world.item.ItemStack +14P
```
```
XXX.world.item.ItemUtils -1M
```
```
XXX.world.item.KnowledgeBookItem +1P
```
```
XXX.world.item.MilkBucketItem +1P
```
```
XXX.world.item.PlayerHeadItem +1P
```
```
XXX.world.item.SpyglassItem +2P
```
```
XXX.world.item.SuspiciousStewItem +3P
```
```
XXX.item.crafting.Ingredient -1M
```
```
XXX.item.enchantment.ThornsEnchantment +1P
```
```
XXX.world.level.BaseSpawner +3P -1P
```
```
XXX.world.level.ChunkPos +7P
```
```
XXX.world.level.Explosion +1P
```
```
XXX.world.level.ForcedChunksSavedData +2P
```
```
XXX.world.level.Level +7P
```
```
XXX.world.level.ServerTickList +1P
```
```
XXX.world.level.StructureFeatureManager +2M -3M
```
```
XXX.level.biome.Biome +1P
```
```
XXX.level.block.AbstractCandleBlock +3M | +1P
```
```
XXX.level.block.AnvilBlock +2P
```
```
XXX.level.block.AzaleaBlock +2M | +1P
```
```
XXX.level.block.BambooSaplingBlock +1P
```
```
XXX.level.block.BeetrootBlock +1P
```
```
XXX.level.block.BigDripleafStemBlock +1M | +1P
```
```
XXX.level.block.BubbleColumnBlock +1P
```
```
XXX.level.block.BuddingAmethystBlock +1P
```
```
XXX.level.block.ButtonBlock +4P
```
```
XXX.level.block.CactusBlock +2P
```
```
XXX.level.block.CampfireBlock +1P
```
```
XXX.level.block.CandleCakeBlock +1P
```
```
XXX.level.block.ChestBlock +3P
```
```
XXX.level.block.ChorusFlowerBlock +1P
```
```
XXX.level.block.CocoaBlock +10P
```
```
XXX.level.block.ComposterBlock +4P
```
```
XXX.level.block.CoralPlantBlock +1P
```
```
XXX.level.block.DeadBushBlock +1P
```
```
XXX.level.block.DispenserBlock +1P
```
```
XXX.level.block.FlowerPotBlock +1P
```
```
XXX.level.block.FungusBlock +1P
```
```
XXX.level.block.GrowingPlantHeadBlock +1P
```
```
XXX.level.block.HoneyBlock +4P
```
```
XXX.level.block.KelpBlock +1P
```
```
XXX.level.block.LadderBlock +1P
```
```
XXX.level.block.LayeredCauldronBlock +4P
```
```
XXX.level.block.LecternBlock +1P
```
```
XXX.level.block.LevelEvent +70P
```
```
XXX.level.levelgen.Cavifier +2P
```
```
XXX.level.levelgen.DebugLevelSource +3P
```
```
XXX.level.levelgen.DepthBasedReplacingBaseStoneSource +2P
```
```
XXX.level.levelgen.SimpleRandomSource +6P
```
```
XXX.level.levelgen.VerticalAnchor$Absolute +1M
```
```
XXX.levelgen.carver.CaveWorldCarver +4M -3M
```
```
XXX.levelgen.carver.NetherWorldCarver +1M -1M
```
```
XXX.levelgen.feature.BastionFeature +1P
```
```
XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart +1M -1M
```
```
XXX.levelgen.feature.DeltaFeature +1P
```
```
XXX.levelgen.feature.DesertPyramidFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.EndCityFeature$EndCityStart +1M -1M
```
```
XXX.levelgen.feature.JigsawFeature +1M -1M
```
```
XXX.levelgen.feature.LargeDripstoneFeature +1M -1M
```
```
XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart +1M -1M
```
```
XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart +1M -3M | -1P
```
```
XXX.levelgen.feature.PillagerOutpostFeature +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.RuinedPortalFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.ScatteredOreFeature +1P
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.StructureFeature +3M -3M | +1P
```
```
XXX.levelgen.feature.SwamplandHutFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart +1M -1M
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +5M -5M | +2P -2P
```
```
XXX.feature.configurations.DeltaFeatureConfiguration +5M -5M | +2P -2P
```
```
XXX.feature.configurations.DripstoneClusterConfiguration +6M -6M | +5P -5P
```
```
XXX.feature.configurations.ReplaceSphereConfiguration +3M -3M | +1P -1P
```
```
XXX.feature.configurations.VegetationPatchConfiguration +3M -3M | +2P -2P
```
```
XXX.feature.featuresize.FeatureSize +1P
```
```
XXX.feature.foliageplacers.BlobFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.DarkOakFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.FoliagePlacer +6M -6M | +3P -3P
```
```
XXX.feature.foliageplacers.MegaPineFoliagePlacer +3M -3M | +1P -1P
```
```
XXX.feature.foliageplacers.RandomSpreadFoliagePlacer +3M -3M | +1P -1P
```
```
XXX.feature.stateproviders.RandomizedIntStateProvider +3M -3M | +1P -1P
```
```
XXX.feature.structures.JigsawPlacement +1M -1M
```
```
XXX.feature.structures.ListPoolElement +4M -1M
```
```
XXX.feature.structures.StructureTemplatePool +2M -1M | +1P
```
```
XXX.feature.treedecorators.BeehiveDecorator +2M -1M
```
```
XXX.feature.treedecorators.LeaveVineDecorator +3M -3M
```
```
XXX.feature.trunkplacers.DarkOakTrunkPlacer +1M -1M
```
```
XXX.feature.trunkplacers.GiantTrunkPlacer +2M -2M
```
```
XXX.feature.trunkplacers.StraightTrunkPlacer +1M -1M
```
```
XXX.levelgen.structure.BoundingBox +11M -4M | +7P -6P
```
```
XXX.levelgen.structure.EndCityPieces$EndCityPiece +4M -1M | -3P
```
```
XXX.levelgen.structure.IglooPieces +1M -1M | +1P
```
```
XXX.levelgen.structure.MineShaftPieces +3M -3M | +6P
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor +2M -2M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftPiece +1M -1M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftStairs +2M -2M
```
```
XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller +1M -1M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleEntrance +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$MonsterThrone +1M -1M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$StairsRoom +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherFossilPieces +1M -1M
```
```
XXX.levelgen.structure.NoiseAffectingStructureStart +2M -2M
```
```
XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding +5P
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece +2M -2M | +12P
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +1M -1M
```
```
XXX.levelgen.structure.OceanRuinPieces +4M -4M
```
```
XXX.levelgen.structure.StructureStart$1 +2M -1M
```
```
XXX.levelgen.structure.TemplateStructurePiece +3M -3M | +1P
```
```
XXX.structure.templatesystem.BlockAgeProcessor +3P
```
```
XXX.structure.templatesystem.StructureTemplate +12P
```
```
XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder +1P
```
```
XXX.levelgen.synth.ImprovedNoise +1P
```
```
XXX.levelgen.synth.NormalNoise +2P
```
```
XXX.level.lighting.DynamicGraphMinFixedPoint +1P
```
```
XXX.level.lighting.LayerLightEngine +2P
```
```
XXX.level.lighting.SpatialLongSet$InternalMap +1P
```
```
XXX.level.material.FluidState +2P
```
```
XXX.level.material.Material +1P -1P
```
```
XXX.newbiome.context.LazyAreaContext +1P
```
```
XXX.newbiome.layer.LayerBiomes +68P
```
```
XXX.newbiome.layer.ZoomLayer +2P
```
```
XXX.level.pathfinder.PathFinder +2P
```
```
XXX.saveddata.maps.MapItemSavedData +3P
```
```
XXX.level.storage.CommandStorage +1P
```
```
XXX.level.storage.CommandStorage$Container +1P
```
```
XXX.level.storage.LevelStorageSource +1P
```
```
XXX.loot.entries.LootPoolSingletonContainer +2P
```
```
XXX.loot.functions.ExplorationMapFunction +4P
```
```
XXX.loot.functions.LootingEnchantFunction +1P
```

</details>
<details>
<summary>
com.mojang.blaze3d.Blaze3D
</summary>

```diff
- void <init>()
- void process(RenderPipeline,float)
- void render(RenderPipeline,float)
```

</details>
<details>
<summary>
com.mojang.blaze3d.font.GlyphInfo
</summary>

```diff
- float getBearingY()
```

</details>



<details>
<summary>
com.mojang.blaze3d.pipeline.RenderTarget
</summary>

```diff
- void bindRead()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.GlStateManager
</summary>

```diff
- int getBoundFramebuffer()
- int glGenRenderbuffers()
- void _glBindRenderbuffer(int,int)
- void _glCopyTexSubImage2D(int,int,int,int,int,int,int,int)
- void _glDeleteRenderbuffers(int)
- void _glDrawPixels(int,int,int,int,long)
- void _glFramebufferRenderbuffer(int,int,int,int)
- void _glRenderbufferStorage(int,int,int,int)
- void _readPixels(int,int,int,int,int,int,long)
- void <init>()
```

</details>







<details>
<summary>
com.mojang.blaze3d.platform.GlStateManager$Viewport
</summary>

```diff
- int height()
- int width()
- int x()
- int y()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.InputConstants
</summary>

```diff
- void <init>()
```

</details>

<details>
<summary>
com.mojang.blaze3d.platform.Lighting
</summary>

```diff
- void <init>()
```

</details>

<details>
<summary>
com.mojang.blaze3d.platform.NativeImage
</summary>

```diff
- byte getBlueOrLuminance(int,int)
- byte getGreenOrLuminance(int,int)
- byte getRedOrLuminance(int,int)
- void blendPixel(int,int,int)
- void downloadDepthBuffer(float)
- void drawPixels()
- void setPixelLuminance(int,int,byte)
- void writeToFile(String)
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.NativeImage$Format
</summary>

```diff
- boolean hasBlue()
- boolean hasGreen()
- boolean hasLuminance()
- boolean hasLuminanceOrBlue()
- boolean hasLuminanceOrGreen()
- boolean hasLuminanceOrRed()
- boolean hasRed()
- int blueOffset()
- int greenOffset()
- int luminanceOffset()
- int luminanceOrBlueOffset()
- int luminanceOrGreenOffset()
- int luminanceOrRedOffset()
- int redOffset()
```

</details>




<details>
<summary>
com.mojang.blaze3d.platform.TextureUtil
</summary>

```diff
- void <init>()
- void writeAsPNG(String,int,int,int,int)
```

</details>




<details>
<summary>
com.mojang.math.OctahedralGroup
</summary>

```diff
- Matrix3f transformation()
- OctahedralGroup inverse()
```

</details>
<details>
<summary>
com.mojang.math.Quaternion
</summary>

```diff
- Quaternion fromXYZ(float,float,float)
- Quaternion fromXYZ(Vector3f)
- Quaternion fromXYZDegrees(Vector3f)
- Quaternion fromYXZ(float,float,float)
- Vector3f toXYZ()
- Vector3f toXYZDegrees()
- Vector3f toYXZ()
- Vector3f toYXZDegrees()
- void slerp(Quaternion,float)
```

</details>
<details>
<summary>
com.mojang.math.Transformation
</summary>

```diff
- Quaternion getRightRotation()
- Transformation slerp(Transformation,float)
- Vector3f getScale()
- Vector3f getTranslation()
```

</details>
<details>
<summary>
com.mojang.math.Vector3f
</summary>

```diff
+ DataResult lambda$static$1(DoubleStream)
- DataResult lambda$static$1(List)
+ DoubleStream lambda$static$2(Vector3f)
- List lambda$static$2(Vector3f)
+ Vector3f lambda$null$0(double[])
- Vector3f lambda$null$0(List)
- void clamp(Vector3f,Vector3f)
- void load(Vector3f)
```

</details>
























<details>
<summary>
com.mojang.realmsclient.util.RealmsUtil
</summary>

```diff
- void <init>()
```

</details>

<details>
<summary>
com.mojang.realmsclient.util.TextRenderingUtils$Line
</summary>

```diff
- void <init>(TextRenderingUtils$LineSegment[])
```

</details>
<details>
<summary>
com.mojang.realmsclient.util.UploadTokenCache
</summary>

```diff
- void <init>()
```

</details>































































































































<details>
<summary>
net.minecraft.client.gui.MapRenderer
</summary>

```diff
+ MapItemSavedData retrieveMapFromRenderer(int)
- RenderType access$300()
+ RenderType access$400()
- TextureManager access$200(MapRenderer)
+ TextureManager access$300(MapRenderer)
```

</details>
<details>
<summary>
net.minecraft.client.gui.MapRenderer$MapInstance
</summary>

```diff
+ MapItemSavedData access$200(MapRenderer$MapInstance)
```

</details>





































































































































































































































































































































<details>
<summary>
net.minecraft.client.renderer.GameRenderer
</summary>

```diff
- boolean isPanoramicMode()
```

</details>








































<details>
<summary>
net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
</summary>

```diff
+ float getOffset()
- float getOffsetDown()
- float getOffsetUp()
```

</details>


























































































<details>
<summary>
net.minecraft.core.FrontAndTop
</summary>

```diff
- void lambda$static$0(Int2ObjectOpenHashMap)
```

</details>




<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ BlockPlacerType lambda$static$43()
- BlockPlacerType lambda$static$45()
+ BlockStateProviderType lambda$static$42()
- BlockStateProviderType lambda$static$44()
+ Codec lambda$static$48()
+ Codec lambda$static$49()
- Codec lambda$static$50()
- Codec lambda$static$51()
+ DataResult lambda$decode$54(Number)
- DataResult lambda$decode$56(Number)
+ DataResult lambda$decode$56(Pair)
- DataResult lambda$decode$58(Pair)
+ Feature lambda$static$38()
- Feature lambda$static$40()
+ FeatureDecorator lambda$static$41()
- FeatureDecorator lambda$static$43()
+ FeatureSizeType lambda$static$47()
- FeatureSizeType lambda$static$49()
- FloatProviderType lambda$static$35()
+ FloatProviderType lambda$static$36()
+ FoliagePlacerType lambda$static$44()
- FoliagePlacerType lambda$static$46()
- HeightProviderType lambda$static$37()
- IntProviderType lambda$static$36()
+ Object lambda$keys$57(DynamicOps,ResourceLocation)
- Object lambda$keys$59(DynamicOps,ResourceLocation)
+ Pair lambda$decode$55(DynamicOps,Object)
- Pair lambda$decode$57(DynamicOps,Object)
+ StructureFeature lambda$static$39()
- StructureFeature lambda$static$41()
+ StructurePieceType lambda$static$40()
- StructurePieceType lambda$static$42()
+ StructurePoolElementType lambda$static$51()
- StructurePoolElementType lambda$static$53()
+ StructureProcessorType lambda$static$50()
- StructureProcessorType lambda$static$52()
+ SurfaceBuilder lambda$static$35()
- SurfaceBuilder lambda$static$38()
+ TreeDecoratorType lambda$static$46()
- TreeDecoratorType lambda$static$48()
+ TrunkPlacerType lambda$static$45()
- TrunkPlacerType lambda$static$47()
+ void lambda$checkRegistry$53(WritableRegistry,WritableRegistry)
- void lambda$checkRegistry$55(WritableRegistry,WritableRegistry)
+ void lambda$static$52(ResourceLocation,Supplier)
- void lambda$static$54(ResourceLocation,Supplier)
+ WorldCarver lambda$static$37()
- WorldCarver lambda$static$39()
```

</details>




























































































<details>
<summary>
net.minecraft.data.worldgen.Features
</summary>

```diff
- SimpleWeightedRandomList$Builder access$000()
- SimpleWeightedRandomList$Builder weightedBlockStateBuilder()
```

</details>
































































































































































































































































<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean shouldDiscardFriction()
- void setDiscardFriction(boolean)
```

</details>






























<details>
<summary>
net.minecraft.world.entity.ai.behavior.RunSometimes
</summary>

```diff
+ void <init>(Behavior,boolean,IntRange)
- void <init>(Behavior,boolean,UniformInt)
+ void <init>(Behavior,IntRange)
- void <init>(Behavior,UniformInt)
```

</details>
















































































<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
- boolean isShaking()
```

</details>
























































































































<details>
<summary>
net.minecraft.world.food.Foods
</summary>

```diff
+ FoodProperties stew(int)
- FoodProperties$Builder stew(int)
```

</details>





















































































<details>
<summary>
net.minecraft.world.item.ItemUtils
</summary>

```diff
+ Optional bucketMobPickup(Player,InteractionHand,LivingEntity,SoundEvent,Supplier)
```

</details>


































<details>
<summary>
net.minecraft.world.item.crafting.Ingredient
</summary>

```diff
+ JsonSyntaxException lambda$valueFromJson$8(ResourceLocation)
```

</details>














































































<details>
<summary>
net.minecraft.world.level.StructureFeatureManager
</summary>

```diff
+ boolean lambda$getStructureAt$3(BlockPos,StructureStart)
- boolean lambda$getStructureAt$4(boolean,BlockPos,StructureStart)
+ boolean lambda$getStructureAt$5(boolean,BlockPos,StructureStart)
- boolean lambda$null$3(BlockPos,StructurePiece)
+ boolean lambda$null$4(BlockPos,StructurePiece)
```

</details>

























<details>
<summary>
net.minecraft.world.level.block.AbstractCandleBlock
</summary>

```diff
- boolean canBeLit(BlockState)
- boolean isLit(BlockState)
- void lambda$extinguish$1(LevelAccessor,BlockPos,Vec3)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.AzaleaBlock
</summary>

```diff
- void <clinit>()
- VoxelShape getBlockSupportShape(BlockState,BlockGetter,BlockPos)
```

</details>











<details>
<summary>
net.minecraft.world.level.block.BigDripleafStemBlock
</summary>

```diff
- ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
```

</details>
















































































































<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
</summary>

```diff
- String toString()
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.carver.CaveWorldCarver
</summary>

```diff
- boolean carve(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
- boolean isStartChunk(CaveCarverConfiguration,Random)
+ int getCaveY(CarvingContext,Random)
+ void createRoom(CarvingContext,CarverConfiguration,ChunkAccess,Function,long,int,double,double,double,float,double,BitSet,WorldCarver$CarveSkipChecker)
- void createRoom(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,long,int,double,double,double,float,double,BitSet,WorldCarver$CarveSkipChecker)
+ void createTunnel(CarvingContext,CarverConfiguration,ChunkAccess,Function,long,int,double,double,double,double,double,float,float,float,int,int,double,BitSet,WorldCarver$CarveSkipChecker)
- void createTunnel(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,long,int,double,double,double,double,double,float,float,float,int,int,double,BitSet,WorldCarver$CarveSkipChecker)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.NetherWorldCarver
</summary>

```diff
- boolean carveBlock(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
+ int getCaveY(CarvingContext,Random)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>










<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature
</summary>

```diff
+ StructureStart lambda$getStartFactory$0(StructureFeature,ChunkPos,BoundingBox,int,long)
- StructureStart lambda$getStartFactory$0(StructureFeature,ChunkPos,int,long)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
</summary>

```diff
+ LargeDripstoneFeature$LargeDripstone makeDripstone(BlockPos,boolean,Random,int,FloatProvider,FloatProvider)
- LargeDripstoneFeature$LargeDripstone makeDripstone(BlockPos,boolean,Random,int,FloatProvider,FloatProvider)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
+ void generatePieces(ChunkPos)
+ void placeInChunk(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
+ List getSpecialEnemies()
- WeightedRandomList getSpecialEnemies()
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
+ List getSpecialAnimals()
+ List getSpecialEnemies()
+ StructureStart createStart(ChunkPos,BoundingBox,int,long)
- StructureStart createStart(ChunkPos,int,long)
- WeightedRandomList getSpecialAnimals()
- WeightedRandomList getSpecialEnemies()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- IntProvider height()
- IntProvider lambda$null$0(ColumnFeatureConfiguration)
- IntProvider lambda$null$1(ColumnFeatureConfiguration)
- IntProvider reach()
+ UniformInt height()
+ UniformInt lambda$null$0(ColumnFeatureConfiguration)
+ UniformInt lambda$null$1(ColumnFeatureConfiguration)
+ UniformInt reach()
- void <init>(IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
</summary>

```diff
- IntProvider lambda$null$2(DeltaFeatureConfiguration)
- IntProvider lambda$null$3(DeltaFeatureConfiguration)
- IntProvider rimSize()
- IntProvider size()
+ UniformInt lambda$null$2(DeltaFeatureConfiguration)
+ UniformInt lambda$null$3(DeltaFeatureConfiguration)
+ UniformInt rimSize()
+ UniformInt size()
- void <init>(BlockState,BlockState,IntProvider,IntProvider)
+ void <init>(BlockState,BlockState,UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
</summary>

```diff
+ FloatProvider lambda$null$6(DripstoneClusterConfiguration)
- FloatProvider lambda$null$6(DripstoneClusterConfiguration)
+ FloatProvider lambda$null$7(DripstoneClusterConfiguration)
- FloatProvider lambda$null$7(DripstoneClusterConfiguration)
- IntProvider lambda$null$1(DripstoneClusterConfiguration)
- IntProvider lambda$null$2(DripstoneClusterConfiguration)
- IntProvider lambda$null$5(DripstoneClusterConfiguration)
+ UniformInt lambda$null$1(DripstoneClusterConfiguration)
+ UniformInt lambda$null$2(DripstoneClusterConfiguration)
+ UniformInt lambda$null$5(DripstoneClusterConfiguration)
- void <init>(int,IntProvider,IntProvider,int,int,IntProvider,FloatProvider,FloatProvider,float,int,int)
+ void <init>(int,UniformInt,UniformInt,int,int,UniformInt,FloatProvider,FloatProvider,float,int,int)
```

</details>













<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
</summary>

```diff
- IntProvider lambda$null$2(ReplaceSphereConfiguration)
- IntProvider radius()
+ UniformInt lambda$null$2(ReplaceSphereConfiguration)
+ UniformInt radius()
- void <init>(BlockState,BlockState,IntProvider)
+ void <init>(BlockState,BlockState,UniformInt)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
</summary>

```diff
- IntProvider lambda$null$4(VegetationPatchConfiguration)
- IntProvider lambda$null$8(VegetationPatchConfiguration)
+ UniformInt lambda$null$4(VegetationPatchConfiguration)
+ UniformInt lambda$null$8(VegetationPatchConfiguration)
- void <init>(ResourceLocation,BlockStateProvider,Supplier,CaveSurface,IntProvider,float,int,float,IntProvider,float)
+ void <init>(ResourceLocation,BlockStateProvider,Supplier,CaveSurface,UniformInt,float,int,float,UniformInt,float)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
</summary>

```diff
- IntProvider lambda$foliagePlacerParts$0(FoliagePlacer)
- IntProvider lambda$foliagePlacerParts$1(FoliagePlacer)
+ UniformInt lambda$foliagePlacerParts$0(FoliagePlacer)
+ UniformInt lambda$foliagePlacerParts$1(FoliagePlacer)
- void <init>(IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,BoundingBox)
- void placeLeavesRow(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,BlockPos,int,int,boolean)
+ void placeLeavesRow(LevelSimulatedRW,Random,TreeConfiguration,BlockPos,int,Set,int,boolean,BoundingBox)
- void tryPlaceLeaf(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,BlockPos)
+ void tryPlaceLeaf(LevelSimulatedRW,Random,TreeConfiguration,Set,BoundingBox,BlockPos$MutableBlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
</summary>

```diff
- IntProvider lambda$null$0(MegaPineFoliagePlacer)
+ UniformInt lambda$null$0(MegaPineFoliagePlacer)
- void <init>(IntProvider,IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
</summary>

```diff
- IntProvider lambda$null$0(RandomSpreadFoliagePlacer)
+ UniformInt lambda$null$0(RandomSpreadFoliagePlacer)
- void <init>(IntProvider,IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
</summary>

```diff
- IntProvider lambda$null$2(RandomizedIntStateProvider)
+ UniformInt lambda$null$2(RandomizedIntStateProvider)
- void <init>(BlockStateProvider,IntegerProperty,IntProvider)
+ void <init>(BlockStateProvider,IntegerProperty,UniformInt)
- void <init>(BlockStateProvider,String,IntProvider)
+ void <init>(BlockStateProvider,String,UniformInt)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
</summary>

```diff
+ void addPieces(RegistryAccess,JigsawConfiguration,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,BlockPos,List,Random,boolean,boolean,LevelHeightAccessor)
- void addPieces(RegistryAccess,JigsawConfiguration,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,BlockPos,StructurePieceAccessor,Random,boolean,boolean,LevelHeightAccessor)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
</summary>

```diff
- boolean lambda$getBoundingBox$2(StructurePoolElement)
- BoundingBox lambda$getBoundingBox$3(StructureManager,BlockPos,Rotation,StructurePoolElement)
- IllegalStateException lambda$getBoundingBox$4()
+ void lambda$setProjectionOnEachElement$2(StructureTemplatePool$Projection,StructurePoolElement)
- void lambda$setProjectionOnEachElement$5(StructureTemplatePool$Projection,StructurePoolElement)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
</summary>

```diff
- boolean lambda$getMaxSize$2(StructurePoolElement)
+ int lambda$getMaxSize$2(StructureManager,StructurePoolElement)
- int lambda$getMaxSize$3(StructureManager,StructurePoolElement)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
</summary>

```diff
- void lambda$place$2(Random,BeehiveBlockEntity)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
</summary>

```diff
- void addHangingVine(LevelSimulatedReader,BlockPos,BooleanProperty,BiConsumer)
+ void addHangingVine(LevelSimulatedRW,BlockPos,BooleanProperty,Set,BoundingBox)
- void lambda$place$1(Random,LevelSimulatedReader,BiConsumer,BlockPos)
+ void lambda$place$1(Random,WorldGenLevel,Set,BoundingBox,BlockPos)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
- void placeLogIfFreeWithOffset(LevelSimulatedReader,BiConsumer,Random,BlockPos$MutableBlockPos,TreeConfiguration,BlockPos,int,int,int)
+ void placeLogIfFreeWithOffset(LevelSimulatedRW,Random,BlockPos$MutableBlockPos,Set,BoundingBox,TreeConfiguration,BlockPos,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
```

</details>
























<details>
<summary>
net.minecraft.world.level.levelgen.structure.BoundingBox
</summary>

```diff
+ BoundingBox createProper(int,int,int,int,int,int)
+ BoundingBox createProper(Vec3i,Vec3i)
- BoundingBox encapsulate(BoundingBox)
- BoundingBox fromCorners(Vec3i,Vec3i)
+ BoundingBox getUnknownBox()
- BoundingBox inflate(int)
- int maxX()
- int maxY()
- int maxZ()
- int minX()
- int minY()
- int minZ()
- Optional encapsulatingBoxes(Iterable)
- Optional encapsulatingPositions(Iterable)
+ void expand(BoundingBox)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
</summary>

```diff
- ResourceLocation makeResourceLocation(String)
- ResourceLocation makeTemplateLocation()
- StructurePlaceSettings lambda$new$0(CompoundTag,ResourceLocation)
- StructurePlaceSettings makeSettings(boolean,Rotation)
+ void loadTemplate(StructureManager)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.IglooPieces
</summary>

```diff
+ void addPieces(StructureManager,BlockPos,Rotation,List,Random)
- void addPieces(StructureManager,BlockPos,Rotation,StructurePieceAccessor,Random)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces
</summary>

```diff
+ MineShaftPieces$MineShaftPiece access$100(StructurePiece,List,Random,int,int,int,Direction,int)
- MineShaftPieces$MineShaftPiece access$100(StructurePiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
+ MineShaftPieces$MineShaftPiece createRandomShaftPiece(List,Random,int,int,int,Direction,int,MineshaftFeature$Type)
- MineShaftPieces$MineShaftPiece createRandomShaftPiece(StructurePieceAccessor,Random,int,int,int,Direction,int,MineshaftFeature$Type)
+ MineShaftPieces$MineShaftPiece generateAndAddPiece(StructurePiece,List,Random,int,int,int,Direction,int)
- MineShaftPieces$MineShaftPiece generateAndAddPiece(StructurePiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
</summary>

```diff
+ BoundingBox findCorridorSize(List,Random,int,int,int,Direction)
- BoundingBox findCorridorSize(StructurePieceAccessor,Random,int,int,int,Direction)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
</summary>

```diff
- void <init>(StructurePieceType,int,MineshaftFeature$Type,BoundingBox)
+ void <init>(StructurePieceType,int,MineshaftFeature$Type)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
</summary>

```diff
+ BoundingBox findStairs(List,Random,int,int,int,Direction)
- BoundingBox findStairs(StructurePieceAccessor,Random,int,int,int,Direction)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
</summary>

```diff
+ NetherBridgePieces$BridgeEndFiller createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$BridgeEndFiller createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
</summary>

```diff
+ NetherBridgePieces$CastleCorridorStairsPiece createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleCorridorStairsPiece createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
</summary>

```diff
+ NetherBridgePieces$CastleEntrance createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$CastleEntrance createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
</summary>

```diff
+ NetherBridgePieces$CastleSmallCorridorLeftTurnPiece createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$CastleSmallCorridorLeftTurnPiece createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
</summary>

```diff
+ NetherBridgePieces$CastleSmallCorridorRightTurnPiece createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$CastleSmallCorridorRightTurnPiece createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
</summary>

```diff
+ NetherBridgePieces$MonsterThrone createPiece(List,int,int,int,int,Direction)
- NetherBridgePieces$MonsterThrone createPiece(StructurePieceAccessor,int,int,int,int,Direction)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
</summary>

```diff
+ NetherBridgePieces$StairsRoom createPiece(List,int,int,int,int,Direction)
- NetherBridgePieces$StairsRoom createPiece(StructurePieceAccessor,int,int,int,int,Direction)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilPieces
</summary>

```diff
+ void addPieces(StructureManager,List,Random,BlockPos)
- void addPieces(StructureManager,StructurePieceAccessor,Random,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NoiseAffectingStructureStart
</summary>

```diff
- BoundingBox getBoundingBox()
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
+ void calculateBoundingBox()
```

</details>









<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
</summary>

```diff
- BoundingBox makeBoundingBox(Direction,OceanMonumentPieces$RoomDefinition,int,int,int)
+ void <init>(StructurePieceType,Direction,BoundingBox)
- void <init>(StructurePieceType,Direction,int,BoundingBox)
+ void <init>(StructurePieceType,int)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinPieces
</summary>

```diff
- List allPositions(Random,BlockPos)
+ List allPositions(Random,int,int)
+ void addClusterRuins(StructureManager,Random,Rotation,BlockPos,OceanRuinConfiguration,List)
- void addClusterRuins(StructureManager,Random,Rotation,BlockPos,OceanRuinConfiguration,StructurePieceAccessor)
+ void addPiece(StructureManager,BlockPos,Rotation,List,Random,OceanRuinConfiguration,boolean,float)
- void addPiece(StructureManager,BlockPos,Rotation,StructurePieceAccessor,Random,OceanRuinConfiguration,boolean,float)
+ void addPieces(StructureManager,BlockPos,Rotation,List,Random,OceanRuinConfiguration)
- void addPieces(StructureManager,BlockPos,Rotation,StructurePieceAccessor,Random,OceanRuinConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart$1
</summary>

```diff
- boolean isValid()
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
</summary>

```diff
- ResourceLocation makeTemplateLocation()
- void <init>(StructurePieceType,CompoundTag,ServerLevel,Function)
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,int,StructureManager,ResourceLocation,String,StructurePlaceSettings,BlockPos)
+ void <init>(StructurePieceType,int)
+ void setup(StructureTemplate,BlockPos,StructurePlaceSettings)
```

</details>
</details>