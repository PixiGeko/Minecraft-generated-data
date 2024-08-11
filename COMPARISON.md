## Comparison with [20w11a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w11a)

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
<table><tr><th></th><th align="left">20w11a</th><th>20w12a</th></tr><tr><td>World version</td><td><code>2513</code></td><td><code>2515</code></td></tr><tr><td>Protocol version</td><td><code>706</code></td><td><code>707</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:polished_basalt
+ minecraft:respawn_anchor
```

</details>














<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:polished_basalt
+ minecraft:respawn_anchor
```

</details>




<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:reverse_portal
```

</details>







<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.respawn_anchor.ambient
+ minecraft:block.respawn_anchor.charge
+ minecraft:block.respawn_anchor.deplete
+ minecraft:block.respawn_anchor.set_spawn
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:polished_basalt
+ minecraft:respawn_anchor
```

</details>







<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:polished_basalt
+ minecraft:respawn_anchor
```

</details>














<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:polished_basalt
+ minecraft:respawn_anchor
```

</details>




<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:reverse_portal
```

</details>







<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.respawn_anchor.ambient
+ minecraft:block.respawn_anchor.charge
+ minecraft:block.respawn_anchor.deplete
+ minecraft:block.respawn_anchor.set_spawn
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ polished_basalt.json
+ respawn_anchor.json
```

</details>







<details>
<summary>
acacia_sign.json
</summary>

```
Group: none -> sign
```

</details>































<details>
<summary>
birch_sign.json
</summary>

```
Group: none -> sign
```

</details>





































































































































<details>
<summary>
crimson_sign.json
</summary>

```
Group: none -> sign
```

</details>


































<details>
<summary>
dark_oak_sign.json
</summary>

```
Group: none -> sign
```

</details>





































































































































































<details>
<summary>
jungle_sign.json
</summary>

```
Group: none -> sign
```

</details>












































































































<details>
<summary>
netherite_ingot.json
</summary>

```
Group: none -> netherite_ingot
```

</details>





















<details>
<summary>
oak_sign.json
</summary>

```
Group: none -> sign
```

</details>






































































































































































































<details>
<summary>
spruce_sign.json
</summary>

```
Group: none -> sign
```

</details>


























































<details>
<summary>
warped_sign.json
</summary>

```
Group: none -> sign
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
- block.minecraft.bed.not_valid: Your home bed was missing or obstructed
- block.minecraft.bed.set_spawn: Respawn point set
+ block.minecraft.polished_basalt: Polished Basalt
+ block.minecraft.respawn_anchor: Respawn Anchor
+ block.minecraft.set_spawn: Respawn point set
+ block.minecraft.spawn.not_valid: Your have no home bed or respawn anchor, or it was obstructed
- death.fell.accident.water: %1$s fell out of the water
+ subtitles.block.respawn_anchor.ambient: Portal whooshes
+ subtitles.block.respawn_anchor.charge: Respawn anchor is charged
+ subtitles.block.respawn_anchor.deplete: Respawn anchor depletes
+ subtitles.block.respawn_anchor.set_spawn: Respawn anchor sets spawn
```

</details>
<details>
<summary>
Changes
</summary>

```
advancements.adventure.sleep_in_bed.description: CSleep in a bed to change your respawn point
commands.spawnpoint.success.single: Set spawn point to %s, %s, %s in %s for %s
commands.spawnpoint.success.multiple: Set spawn point to %s, %s, %s in %s for %s players
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/polished_basalt.json
+ minecraft/advancements/recipes/decorations/respawn_anchor.json
+ minecraft/loot_tables/blocks/polished_basalt.json
+ minecraft/loot_tables/blocks/respawn_anchor.json
+ minecraft/recipes/polished_basalt.json
+ minecraft/recipes/respawn_anchor.json
+ minecraft/tags/blocks/soul_fire_base_blocks.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/polished_basalt.json
+ minecraft/blockstates/respawn_anchor.json
+ minecraft/models/block/polished_basalt.json
+ minecraft/models/block/respawn_anchor_0.json
+ minecraft/models/block/respawn_anchor_1.json
+ minecraft/models/block/respawn_anchor_2.json
+ minecraft/models/block/respawn_anchor_3.json
+ minecraft/models/block/respawn_anchor_4.json
+ minecraft/models/item/polished_basalt.json
+ minecraft/models/item/respawn_anchor.json
+ minecraft/particles/reverse_portal.json
+ minecraft/textures/block/polished_basalt_side.png
+ minecraft/textures/block/polished_basalt_top.png
+ minecraft/textures/block/respawn_anchor_bottom.png
+ minecraft/textures/block/respawn_anchor_side0.png
+ minecraft/textures/block/respawn_anchor_side1.png
+ minecraft/textures/block/respawn_anchor_side2.png
+ minecraft/textures/block/respawn_anchor_side3.png
+ minecraft/textures/block/respawn_anchor_side4.png
+ minecraft/textures/block/respawn_anchor_top_off.png
+ minecraft/textures/block/respawn_anchor_top.png
+ minecraft/textures/block/respawn_anchor_top.png.mcmeta
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
- net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.PlacedBlockTrigger
+ net.minecraft.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$1
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$Builder
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ShotCrossbowTrigger
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SimpleCriterionTrigger
+ net.minecraft.advancements.critereon.SlideDownBlockTrigger
- net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.StatePropertiesPredicate
- net.minecraft.advancements.critereon.StatePropertiesPredicate$1
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
+ net.minecraft.advancements.critereon.SummonedEntityTrigger
- net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TameAnimalTrigger
- net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TargetBlockTrigger
- net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TickTrigger
- net.minecraft.advancements.critereon.TickTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TradeTrigger
- net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedTotemTrigger
- net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.package-info
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.package-info
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
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
+ net.minecraft.commands.arguments.DimensionTypeArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Serializer
- net.minecraft.commands.arguments.EntitySummonArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
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
- net.minecraft.commands.arguments.ItemEnchantmentArgument
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
- net.minecraft.commands.arguments.MobEffectArgument
+ net.minecraft.commands.arguments.NbtPathArgument
- net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
+ net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
- net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
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
- net.minecraft.commands.arguments.RangeArgument$Floats$Serializer
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.RangeArgument$Ints$Serializer
+ net.minecraft.commands.arguments.RangeArgument$Serializer
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
- net.minecraft.commands.arguments.selector.EntitySelector
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
- net.minecraft.commands.BrigadierExceptions
+ net.minecraft.commands.CommandFunction
- net.minecraft.commands.CommandFunction$CacheableFunction
+ net.minecraft.commands.CommandFunction$CommandEntry
- net.minecraft.commands.CommandFunction$Entry
+ net.minecraft.commands.CommandFunction$FunctionEntry
- net.minecraft.commands.CommandRuntimeException
- net.minecraft.commands.Commands
+ net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
- net.minecraft.commands.exceptions.package-info
+ net.minecraft.commands.package-info
- net.minecraft.commands.SharedSuggestionProvider
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
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
+ net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
- net.minecraft.core.dispenser.BoatDispenseItemBehavior
+ net.minecraft.core.dispenser.DefaultDispenseItemBehavior
- net.minecraft.core.dispenser.DispenseItemBehavior
+ net.minecraft.core.dispenser.DispenseItemBehavior$1
- net.minecraft.core.dispenser.DispenseItemBehavior$10
+ net.minecraft.core.dispenser.DispenseItemBehavior$11
- net.minecraft.core.dispenser.DispenseItemBehavior$12
+ net.minecraft.core.dispenser.DispenseItemBehavior$13
- net.minecraft.core.dispenser.DispenseItemBehavior$14
+ net.minecraft.core.dispenser.DispenseItemBehavior$15
- net.minecraft.core.dispenser.DispenseItemBehavior$16
+ net.minecraft.core.dispenser.DispenseItemBehavior$17
- net.minecraft.core.dispenser.DispenseItemBehavior$18
+ net.minecraft.core.dispenser.DispenseItemBehavior$19
- net.minecraft.core.dispenser.DispenseItemBehavior$2
+ net.minecraft.core.dispenser.DispenseItemBehavior$20
- net.minecraft.core.dispenser.DispenseItemBehavior$21
+ net.minecraft.core.dispenser.DispenseItemBehavior$22
- net.minecraft.core.dispenser.DispenseItemBehavior$3
+ net.minecraft.core.dispenser.DispenseItemBehavior$4
- net.minecraft.core.dispenser.DispenseItemBehavior$5
+ net.minecraft.core.dispenser.DispenseItemBehavior$6
- net.minecraft.core.dispenser.DispenseItemBehavior$7
+ net.minecraft.core.dispenser.DispenseItemBehavior$7$1
- net.minecraft.core.dispenser.DispenseItemBehavior$8
+ net.minecraft.core.dispenser.DispenseItemBehavior$8$1
- net.minecraft.core.dispenser.DispenseItemBehavior$9
+ net.minecraft.core.dispenser.OptionalDispenseItemBehavior
+ net.minecraft.core.dispenser.package-info
- net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
+ net.minecraft.core.GlobalPos
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.LocatableSource
+ net.minecraft.core.Location
- net.minecraft.core.MapFiller
+ net.minecraft.core.MappedRegistry
- net.minecraft.core.NonNullList
- net.minecraft.core.package-info
+ net.minecraft.core.particles.BlockParticleOption
- net.minecraft.core.particles.BlockParticleOption$1
+ net.minecraft.core.particles.DustParticleOptions
- net.minecraft.core.particles.DustParticleOptions$1
+ net.minecraft.core.particles.ItemParticleOption
- net.minecraft.core.particles.ItemParticleOption$1
+ net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.Position
- net.minecraft.core.PositionImpl
+ net.minecraft.core.Registry
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.SerializableBoolean
- net.minecraft.core.SerializableLong
+ net.minecraft.core.SerializableUUID
- net.minecraft.core.Source
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
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
+ net.minecraft.data.models.blockstates.package-info
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
- net.minecraft.data.models.blockstates.PropertyValue
+ net.minecraft.data.models.blockstates.Selector
- net.minecraft.data.models.blockstates.Variant
+ net.minecraft.data.models.blockstates.VariantProperties
- net.minecraft.data.models.blockstates.VariantProperties$Rotation
+ net.minecraft.data.models.blockstates.VariantProperty
- net.minecraft.data.models.blockstates.VariantProperty$Value
+ net.minecraft.data.models.ItemModelGenerators
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
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
- net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BlockTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
- net.minecraft.data.tags.TagsProvider
- net.minecraft.gametest.framework.BeforeBatch
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
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
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.TeamcityTestReporter
+ net.minecraft.gametest.framework.TestClassNameArgument
- net.minecraft.gametest.framework.TestCommand
+ net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
- net.minecraft.gametest.framework.TestFunction
+ net.minecraft.gametest.framework.TestFunctionArgument
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
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
+ net.minecraft.network.chat.BaseComponent
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ClickEvent
- net.minecraft.network.chat.ClickEvent$Action
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$1
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.ContextAwareComponent
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.NbtComponent
- net.minecraft.network.chat.NbtComponent$BlockNbtComponent
+ net.minecraft.network.chat.NbtComponent$EntityNbtComponent
- net.minecraft.network.chat.NbtComponent$StorageNbtComponent
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.ScoreComponent
- net.minecraft.network.chat.SelectorComponent
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.TextComponent
+ net.minecraft.network.chat.TranslatableComponent
- net.minecraft.network.chat.TranslatableFormatException
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
- net.minecraft.network.package-info
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAddGlobalEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddMobPacket
+ net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
- net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
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
+ net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
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
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetSpawnPositionPacket
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
- net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
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
- net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
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
- net.minecraft.network.protocol.game.ServerGamePacketListener
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
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
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
- net.minecraft.network.SkipPacketException
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
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.obfuscate.DontObfuscateOrShrink
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
+ net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.recipebook.ServerPlaceSmeltingRecipe
- net.minecraft.resources.package-info
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
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
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$Mode
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
+ net.minecraft.server.commands.ReplaceItemCommand
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
- net.minecraft.server.ConsoleInputSource
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServer$2
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
+ net.minecraft.server.level.DerivedServerLevel
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.FeatureSimulator
+ net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
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
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
+ net.minecraft.server.MinecraftServer$3
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
- net.minecraft.server.packs.AbstractResourcePack
+ net.minecraft.server.packs.FileResourcePack
- net.minecraft.server.packs.FolderResourcePack
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.Pack
- net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
+ net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.repository.UnopenedPack
+ net.minecraft.server.packs.repository.UnopenedPack$Position
- net.minecraft.server.packs.repository.UnopenedPack$UnopenedPackConstructor
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
- net.minecraft.server.packs.VanillaPack
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$2
- net.minecraft.server.players.GameProfileCache$GameProfileInfo
+ net.minecraft.server.players.GameProfileCache$Serializer
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
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
+ net.minecraft.sounds.package-info
- net.minecraft.sounds.SoundEvent
+ net.minecraft.sounds.SoundEvents
- net.minecraft.sounds.SoundSource
- net.minecraft.stats.package-info
- net.minecraft.stats.RecipeBook
+ net.minecraft.stats.ServerRecipeBook
- net.minecraft.stats.ServerStatsCounter
+ net.minecraft.stats.Stat
- net.minecraft.stats.StatFormatter
- net.minecraft.stats.Stats
+ net.minecraft.stats.StatsCounter
+ net.minecraft.stats.StatType
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.BlockTags$Wrapper
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.EntityTypeTags$Wrapper
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.FluidTags$Wrapper
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.ItemTags$Wrapper
- net.minecraft.tags.package-info
+ net.minecraft.tags.SynchronizableTagCollection
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.Tag$ValuesEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$Preparations
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
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
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RenameBiomesFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.OminousBannerRenameFix
- net.minecraft.util.Deserializer
+ net.minecraft.util.FrameTimer
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.InsensitiveStringMap
+ net.minecraft.util.IntRange
- net.minecraft.util.LazyLoadedValue
+ net.minecraft.util.LimitedCapacityList
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.Mth
- net.minecraft.util.ProgressListener
+ net.minecraft.util.RewindableStream
- net.minecraft.util.RewindableStream$1
+ net.minecraft.util.Serializable
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$1
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringUtil
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.Piglin$PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Zombie$1
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
+ net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
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
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.VillagerType$1
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.projectile.AbstractArrow
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
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
+ net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
+ net.minecraft.world.item.ArmorItem
- net.minecraft.world.item.ArmorItem$1
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterials
+ net.minecraft.world.item.ArmorStandItem
- net.minecraft.world.item.ArrowItem
+ net.minecraft.world.item.AxeItem
- net.minecraft.world.item.BannerItem
+ net.minecraft.world.item.BannerPatternItem
- net.minecraft.world.item.BedItem
+ net.minecraft.world.item.BlockItem
- net.minecraft.world.item.BlockPlaceContext
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.CarrotOnAStickItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.ClockItem
+ net.minecraft.world.item.ClockItem$1
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.CompassItem$1
- net.minecraft.world.item.ComplexItem
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
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$10
- net.minecraft.world.item.CreativeModeTab$11
+ net.minecraft.world.item.CreativeModeTab$12
- net.minecraft.world.item.CreativeModeTab$2
+ net.minecraft.world.item.CreativeModeTab$3
- net.minecraft.world.item.CreativeModeTab$4
+ net.minecraft.world.item.CreativeModeTab$5
- net.minecraft.world.item.CreativeModeTab$6
+ net.minecraft.world.item.CreativeModeTab$7
- net.minecraft.world.item.CreativeModeTab$8
+ net.minecraft.world.item.CreativeModeTab$9
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.DebugStickItem
- net.minecraft.world.item.DiggerItem
+ net.minecraft.world.item.DirectionalPlaceContext
- net.minecraft.world.item.DirectionalPlaceContext$1
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
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
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishBucketItem
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$1
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.ItemPropertyFunction
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
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
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
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
- net.minecraft.world.item.UseOnContext
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$3
+ net.minecraft.world.level.block.Block$OffsetType
+ net.minecraft.world.level.block.LogBlock
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
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
- net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState$1
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ChunkTickList
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.CollisionGetter$1
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CustomSpawner
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.LevelConflictException
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelType
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NoiseColumn
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.world.entity.Entity -1M | -1P
```
```
XXX.ai.behavior.AnimalMakeLove +1M -1M | +1P
```
```
XXX.ai.behavior.BehaviorUtils +5M -5M
```
```
XXX.ai.behavior.GoToCelebrateLocation +1M -1M | +1P
```
```
XXX.ai.behavior.GoToWantedItem +2M -2M | +1P
```
```
XXX.ai.behavior.InsideBrownianWalk +1P -1P
```
```
XXX.ai.behavior.LocateHidingPlace +1P -1P
```
```
XXX.ai.behavior.LookAndFollowTradingPlayerSink +1P -1P
```
```
XXX.ai.behavior.MoveToSkySeeingSpot +1P -1P
```
```
XXX.ai.behavior.RandomStroll +1P -1P
```
```
XXX.ai.behavior.SetClosestHomeAsWalkTarget +1P -1P
```
```
XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach +1P -1P
```
```
XXX.ai.behavior.SetWalkTargetFromLookTarget +1P -1P
```
```
XXX.ai.behavior.StrollToPoiList +1P -1P
```
```
XXX.ai.behavior.VillageBoundRandomStroll +1P -1P
```
```
XXX.entity.fishing.FishingHook +3M | +1P
```
```
XXX.level.biome.Biome +3M -3M
```
```
XXX.level.biome.BiomeSpecialEffects +2M -2M | +2P -2P
```
```
XXX.level.biome.BiomeSpecialEffects$Builder +2M -2M | +2P -2P
```
```
XXX.level.block.AbstractBannerBlock +1M -1M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -2M
```
```
XXX.level.block.AbstractSkullBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +4M -4M
```
```
XXX.level.block.BambooBlock +4M -2M
```
```
XXX.level.block.BannerBlock +1M -1M
```
```
XXX.level.block.BarrierBlock +1M -2M
```
```
XXX.level.block.BaseCoralPlantBlock +1M -1M
```
```
XXX.level.block.BaseCoralWallFanBlock +1M -1M
```
```
XXX.level.block.BaseFireBlock +1M -1M
```
```
XXX.level.block.BaseRailBlock +1M -1M
```
```
XXX.level.block.BeaconBlock +1M -2M
```
```
XXX.level.block.Blocks +52M -3M | +2P
```
```
XXX.level.block.BrewingStandBlock +1M -1M
```
```
XXX.level.block.ButtonBlock +2M -2M
```
```
XXX.level.block.CactusBlock +2M -1M
```
```
XXX.level.block.CampfireBlock +1M -2M
```
```
XXX.level.block.CartographyTableBlock +1M -1M
```
```
XXX.level.block.CauldronBlock +1M -1M
```
```
XXX.level.block.ChorusPlantBlock +1M -1M
```
```
XXX.level.block.ComparatorBlock +1M -1M
```
```
XXX.level.block.ConduitBlock +1M -1M
```
```
XXX.level.block.CoralFanBlock +1M -1M
```
```
XXX.level.block.CoralWallFanBlock +1M -1M
```
```
XXX.level.block.CropBlock +3M -2M
```
```
XXX.level.block.DaylightDetectorBlock +1M -1M
```
```
XXX.level.block.DetectorRailBlock +1M -2M
```
```
XXX.level.block.DiodeBlock +1M -1M
```
```
XXX.level.block.DispenserBlock +1M -2M
```
```
XXX.level.block.DragonEggBlock +2M -2M
```
```
XXX.level.block.EnchantmentTableBlock +1M -1M
```
```
XXX.level.block.EndPortalBlock +1M -1M
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
XXX.level.block.FallingBlock +5M -5M
```
```
XXX.level.block.FenceBlock +2M -1M
```
```
XXX.level.block.FletchingTableBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock +1M -1M
```
```
XXX.level.block.FungusBlock +1M -1M
```
```
XXX.level.block.GlassBlock +1M -1M
```
```
XXX.level.block.GoldBlock +1M -1M
```
```
XXX.level.block.GrassPathBlock +1M -2M
```
```
XXX.level.block.GrindstoneBlock +1M -1M
```
```
XXX.level.block.GrowingPlantBlock +1M -1M
```
```
XXX.level.block.GrowingPlantHeadBlock +3M -1M
```
```
XXX.level.block.HayBlock +1M -1M
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.HorizontalDirectionalBlock +1M -1M
```
```
XXX.level.block.IceBlock +2M -3M
```
```
XXX.level.block.IronBarsBlock +2M -1M
```
```
XXX.level.block.JukeboxBlock +1M -1M
```
```
XXX.level.block.KelpPlantBlock +1M -1M
```
```
XXX.level.block.LeavesBlock +1M -3M
```
```
XXX.level.block.LeverBlock +1M -1M
```
```
XXX.level.block.LiquidBlock +2M -2M
```
```
XXX.level.block.RotatedPillarBlock +1M -1M
```
```
XXX.level.block.SandBlock +2M -2M
```
```
XXX.level.block.ScaffoldingBlock +1M -1M
```
```
XXX.level.block.Seagrass +1M -1M
```
```
XXX.level.block.ShulkerBoxBlock +1M -2M
```
```
XXX.level.block.SignBlock +1M -1M
```
```
XXX.level.block.SkullBlock +1M -1M
```
```
XXX.level.block.SmithingTableBlock +1M -1M
```
```
XXX.level.block.SnowLayerBlock +3M -2M
```
```
XXX.level.block.SnowyDirtBlock +1M -1M
```
```
XXX.level.block.SoulSandBlock +3M -6M
```
```
XXX.level.block.SpawnerBlock +1M -1M
```
```
XXX.level.block.SpreadingSnowyDirtBlock +2M -2M
```
```
XXX.level.block.StainedGlassPaneBlock +1M -1M
```
```
XXX.level.block.StemBlock +2M -2M
```
```
XXX.level.block.StoneButtonBlock +1M -1M
```
```
XXX.level.block.StructureBlock +1M -1M
```
```
XXX.level.block.StructureVoidBlock +1M -1M
```
```
XXX.level.block.SweetBerryBushBlock +3M -2M
```
```
XXX.level.block.TallGrassBlock +2M -2M
```
```
XXX.level.block.TargetBlock +1M -1M
```
```
XXX.level.block.TorchBlock +1M -1M
```
```
XXX.level.block.TripWireBlock +1M -1M
```
```
XXX.level.block.TripWireHookBlock +1M -1M
```
```
XXX.level.block.TurtleEggBlock +2M -2M
```
```
XXX.level.block.TwistingVinesPlant +1M -1M
```
```
XXX.level.block.WallBlock +1M -1M
```
```
XXX.level.block.WallSignBlock +1M -1M
```
```
XXX.level.block.WallTorchBlock +1M -1M
```
```
XXX.level.block.WebBlock +1M -1M
```
```
XXX.level.block.WeepingVinesPlant +1M -1M
```
```
XXX.level.block.WetSpongeBlock +1M -1M
```
```
XXX.level.block.WitherSkullBlock +1M -1M
```
```
XXX.level.block.WoodButtonBlock +1M -1M
```
```
XXX.block.piston.MovingPistonBlock +1M -3M
```
```
XXX.state.properties.BlockStateProperties +1P
```
```
XXX.level.chunk.ChunkGenerator +1P
```
```
XXX.level.levelgen.FlatLevelSource +1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +3M
```
```
XXX.levelgen.feature.NetherForestVegetationFeature +1M
```
```
XXX.loot.functions.EnchantRandomlyFunction +3M -1M
```

</details>




















































































































































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ double getDismountTargetFloorHeight(Level,BlockPos,CollisionContext)
```

</details>























<details>
<summary>
net.minecraft.world.entity.ai.behavior.AnimalMakeLove
</summary>

```diff
- void <init>(EntityType,float)
+ void <init>(EntityType)
```

</details>


<details>
<summary>
net.minecraft.world.entity.ai.behavior.BehaviorUtils
</summary>

```diff
- void lockGazeAndWalkToEachOther(LivingEntity,LivingEntity,float)
+ void lockGazeAndWalkToEachOther(LivingEntity,LivingEntity)
- void setWalkAndLookTargetMemories(LivingEntity,BlockPos,float,int)
+ void setWalkAndLookTargetMemories(LivingEntity,BlockPos,int)
- void setWalkAndLookTargetMemories(LivingEntity,Entity,float,int)
+ void setWalkAndLookTargetMemories(LivingEntity,Entity,int)
- void setWalkAndLookTargetMemories(LivingEntity,PositionWrapper,float,int)
+ void setWalkAndLookTargetMemories(LivingEntity,PositionWrapper,int)
- void setWalkAndLookTargetMemoriesToEachOther(LivingEntity,LivingEntity,float)
+ void setWalkAndLookTargetMemoriesToEachOther(LivingEntity,LivingEntity)
```

</details>








<details>
<summary>
net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
</summary>

```diff
- void <init>(int,float)
+ void <init>(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.GoToWantedItem
</summary>

```diff
- void <init>(float,boolean,int)
+ void <init>(int,boolean)
- void <init>(Predicate,float,boolean,int)
+ void <init>(Predicate,int,boolean)
```

</details>




























































































































































































<details>
<summary>
net.minecraft.world.entity.fishing.FishingHook
</summary>

```diff
- boolean calculateOpenWater(BlockPos)
- boolean isOpenWaterFishing()
- boolean validOpenWaterBlockAt(BlockPos)
```

</details>































































<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
- Optional getAmbientAdditions()
+ Optional getAmbientAdditionsSoundEvent()
- Optional getAmbientLoop()
+ Optional getAmbientLoopSoundEvent()
- Optional getAmbientMood()
+ Optional getAmbientMoodSoundEvent()
```

</details>






<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects
</summary>

```diff
- Optional getAmbientAdditionsSettings()
+ Optional getAmbientAdditionsSoundEvent()
- Optional getAmbientMoodSettings()
+ Optional getAmbientMoodSoundEvent()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
</summary>

```diff
- BiomeSpecialEffects$Builder ambientAdditionsSound(AmbientAdditionsSettings)
+ BiomeSpecialEffects$Builder ambientAdditionsSound(SoundEvent)
- BiomeSpecialEffects$Builder ambientMoodSound(AmbientMoodSettings)
+ BiomeSpecialEffects$Builder ambientMoodSound(SoundEvent)
```

</details>












































<details>
<summary>
net.minecraft.world.level.block.AbstractBannerBlock
</summary>

```diff
+ void <init>(DyeColor,Block$Properties)
- void <init>(DyeColor,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ int getLightEmission(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractSkullBlock
</summary>

```diff
+ void <init>(SkullBlock$Type,Block$Properties)
- void <init>(SkullBlock$Type,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
- int getDustColor(BlockState,BlockGetter,BlockPos)
+ int getDustColor(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void onBroken(Level,BlockPos,FallingBlockEntity)
+ void onBroken(Level,BlockPos)
- void onLand(Level,BlockPos,BlockState,BlockState,FallingBlockEntity)
+ void onLand(Level,BlockPos,BlockState,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooBlock
</summary>

```diff
+ Block$OffsetType getOffsetType()
- BlockBehaviour$OffsetType getOffsetType()
- boolean isRandomlyTicking(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
+ void <init>(DyeColor,Block$Properties)
- void <init>(DyeColor,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BarrierBlock
</summary>

```diff
+ boolean isValidSpawn(BlockState,BlockGetter,BlockPos,EntityType)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralPlantBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralWallFanBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
+ void <init>(Block$Properties,float)
- void <init>(BlockBehaviour$Properties,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
+ void <init>(boolean,Block$Properties)
- void <init>(boolean,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
+ boolean isRedstoneConductor(BlockState,BlockGetter,BlockPos)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
- BedBlock bed(DyeColor)
- Block stem(MaterialColor)
+ BlockEntityType lambda$static$0()
- BlockEntityType lambda$static$11()
- Boolean always(BlockState,BlockGetter,BlockPos,EntityType)
- boolean always(BlockState,BlockGetter,BlockPos)
- boolean lambda$pistonBase$4(BlockState,BlockGetter,BlockPos)
- boolean lambda$static$12(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$27(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$29(BlockState,BlockGetter,BlockPos,EntityType)
- Boolean never(BlockState,BlockGetter,BlockPos,EntityType)
- boolean never(BlockState,BlockGetter,BlockPos)
- Boolean ocelotOrParrot(BlockState,BlockGetter,BlockPos,EntityType)
+ ConfiguredFeature lambda$static$1()
+ ConfiguredFeature lambda$static$2()
- ConfiguredFeature lambda$static$34()
- ConfiguredFeature lambda$static$35()
- int lambda$litBlockEmission$0(int,BlockState)
- int lambda$static$10(BlockState)
- int lambda$static$13(BlockState)
- int lambda$static$14(BlockState)
- int lambda$static$15(BlockState)
- int lambda$static$16(BlockState)
- int lambda$static$17(BlockState)
- int lambda$static$18(BlockState)
- int lambda$static$19(BlockState)
- int lambda$static$20(BlockState)
- int lambda$static$21(BlockState)
- int lambda$static$22(BlockState)
- int lambda$static$23(BlockState)
- int lambda$static$24(BlockState)
- int lambda$static$25(BlockState)
- int lambda$static$26(BlockState)
- int lambda$static$28(BlockState)
- int lambda$static$30(BlockState)
- int lambda$static$31(BlockState)
- int lambda$static$32(BlockState)
- int lambda$static$33(BlockState)
- int lambda$static$36(BlockState)
- int lambda$static$37(BlockState)
- int lambda$static$38(BlockState)
- int lambda$static$5(BlockState)
- int lambda$static$6(BlockState)
- int lambda$static$7(BlockState)
- int lambda$static$8(BlockState)
- int lambda$static$9(BlockState)
- LeavesBlock leaves()
- MaterialColor lambda$bed$1(DyeColor,BlockState)
- MaterialColor lambda$log$2(MaterialColor,MaterialColor,BlockState)
- MaterialColor lambda$stem$3(MaterialColor,BlockState)
- PistonBaseBlock pistonBase(boolean)
- RotatedPillarBlock log(MaterialColor,MaterialColor)
- ShulkerBoxBlock shulkerBox(DyeColor,BlockBehaviour$Properties)
- StainedGlassBlock stainedGlass(DyeColor)
- ToIntFunction litBlockEmission(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
- int getPressDuration()
+ int getTickDelay(LevelReader)
+ void <init>(boolean,Block$Properties)
- void <init>(boolean,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CactusBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
+ int getLightEmission(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CartographyTableBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CauldronBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.ComparatorBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ConduitBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CoralFanBlock
</summary>

```diff
+ void <init>(Block,Block$Properties)
- void <init>(Block,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CoralWallFanBlock
</summary>

```diff
+ void <init>(Block,Block$Properties)
- void <init>(Block,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CropBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.DaylightDetectorBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DetectorRailBlock
</summary>

```diff
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DiodeBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.DragonEggBlock
</summary>

```diff
- int getDelayAfterPlace()
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnchantmentTableBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndPortalBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FallingBlock
</summary>

```diff
- int getDelayAfterPlace()
- int getDustColor(BlockState,BlockGetter,BlockPos)
+ int getDustColor(BlockState)
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void onBroken(Level,BlockPos,FallingBlockEntity)
+ void onBroken(Level,BlockPos)
- void onLand(Level,BlockPos,BlockState,BlockState,FallingBlockEntity)
+ void onLand(Level,BlockPos,BlockState,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- VoxelShape getVisualShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.FletchingTableBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
+ void <init>(Block,Block$Properties)
- void <init>(Block,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FungusBlock
</summary>

```diff
+ void <init>(Block$Properties,Supplier)
- void <init>(BlockBehaviour$Properties,Supplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GlassBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GoldBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrassPathBlock
</summary>

```diff
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrindstoneBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBlock
</summary>

```diff
+ void <init>(Block$Properties,Direction,VoxelShape,boolean)
- void <init>(BlockBehaviour$Properties,Direction,VoxelShape,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrowingPlantHeadBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
+ void <init>(Block$Properties,Direction,VoxelShape,boolean,double)
- void <init>(BlockBehaviour$Properties,Direction,VoxelShape,boolean,double)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HayBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HorizontalDirectionalBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.IceBlock
</summary>

```diff
+ boolean isValidSpawn(BlockState,BlockGetter,BlockPos,EntityType)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.IronBarsBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- VoxelShape getVisualShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JukeboxBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpPlantBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.LeavesBlock
</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ boolean isValidSpawn(BlockState,BlockGetter,BlockPos,EntityType)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LiquidBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
+ int getTickDelay(LevelReader)
+ void <init>(FlowingFluid,Block$Properties)
- void <init>(FlowingFluid,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RotatedPillarBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SandBlock
</summary>

```diff
- int getDustColor(BlockState,BlockGetter,BlockPos)
+ int getDustColor(BlockState)
+ void <init>(int,Block$Properties)
- void <init>(int,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ScaffoldingBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Seagrass
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ void <init>(DyeColor,Block$Properties)
- void <init>(DyeColor,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SignBlock
</summary>

```diff
+ void <init>(Block$Properties,WoodType)
- void <init>(BlockBehaviour$Properties,WoodType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SkullBlock
</summary>

```diff
+ void <init>(SkullBlock$Type,Block$Properties)
- void <init>(SkullBlock$Type,BlockBehaviour$Properties)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.SmithingTableBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SnowLayerBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
- VoxelShape getVisualShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SnowyDirtBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SoulSandBlock
</summary>

```diff
- BlockState updateShape(BlockState,Direction,BlockState,LevelAccessor,BlockPos,BlockPos)
+ boolean isRedstoneConductor(BlockState,BlockGetter,BlockPos)
+ boolean isValidSpawn(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- VoxelShape getVisualShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SpawnerBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SpreadingSnowyDirtBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StainedGlassPaneBlock
</summary>

```diff
+ void <init>(DyeColor,Block$Properties)
- void <init>(DyeColor,BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.StemBlock
</summary>

```diff
+ void <init>(StemGrownBlock,Block$Properties)
- void <init>(StemGrownBlock,BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StoneButtonBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StructureVoidBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SweetBerryBushBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TallGrassBlock
</summary>

```diff
+ Block$OffsetType getOffsetType()
- BlockBehaviour$OffsetType getOffsetType()
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TargetBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TorchBlock
</summary>

```diff
+ void <init>(Block$Properties,ParticleOptions)
- void <init>(BlockBehaviour$Properties,ParticleOptions)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.TripWireBlock
</summary>

```diff
+ void <init>(TripWireHookBlock,Block$Properties)
- void <init>(TripWireHookBlock,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TripWireHookBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TurtleEggBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TwistingVinesPlant
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.WallBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WallSignBlock
</summary>

```diff
+ void <init>(Block$Properties,WoodType)
- void <init>(BlockBehaviour$Properties,WoodType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WallTorchBlock
</summary>

```diff
+ void <init>(Block$Properties,ParticleOptions)
- void <init>(BlockBehaviour$Properties,ParticleOptions)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WebBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WeepingVinesPlant
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WetSpongeBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WitherSkullBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WoodButtonBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>



































<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ boolean isRedstoneConductor(BlockState,BlockGetter,BlockPos)
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>





































































<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
- BlockGetter getBaseColumn(int,int)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
- BlockGetter getBaseColumn(int,int)
- BlockState generateBaseState(double,int)
- int iterateNoiseColumn(int,int,BlockState[],Predicate)
```

</details>






































<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
</summary>

```diff
- boolean place(LevelAccessor,Random,BlockPos,BlockPileConfiguration,int,int)
```

</details>











































































































































































































































































































<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
</summary>

```diff
- boolean lambda$run$0(boolean,ItemStack,Enchantment)
- ItemStack enchantItem(ItemStack,Enchantment,Random)
+ LootItemFunction lambda$randomApplicableEnchantment$0(LootItemCondition[])
- LootItemFunction lambda$randomApplicableEnchantment$1(LootItemCondition[])
```

</details>































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
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
- net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.PlacedBlockTrigger
+ net.minecraft.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$1
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$Builder
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ShotCrossbowTrigger
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SimpleCriterionTrigger
+ net.minecraft.advancements.critereon.SlideDownBlockTrigger
- net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.StatePropertiesPredicate
- net.minecraft.advancements.critereon.StatePropertiesPredicate$1
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
+ net.minecraft.advancements.critereon.SummonedEntityTrigger
- net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TameAnimalTrigger
- net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TargetBlockTrigger
- net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TickTrigger
- net.minecraft.advancements.critereon.TickTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TradeTrigger
- net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedTotemTrigger
- net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.package-info
- net.minecraft.client.AmbientOcclusionStatus
+ net.minecraft.client.AttackIndicatorStatus
- net.minecraft.client.BooleanOption
+ net.minecraft.client.Camera
- net.minecraft.client.ClientBrandRetriever
+ net.minecraft.client.ClientRecipeBook
- net.minecraft.client.CloudStatus
+ net.minecraft.client.color.block.BlockColor
- net.minecraft.client.color.block.BlockColors
+ net.minecraft.client.color.block.BlockTintCache
- net.minecraft.client.color.block.BlockTintCache$1
+ net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
- net.minecraft.client.color.block.package-info
+ net.minecraft.client.color.item.ItemColor
- net.minecraft.client.color.item.ItemColors
+ net.minecraft.client.color.item.package-info
+ net.minecraft.client.CycleOption
- net.minecraft.client.DebugQueryHandler
+ net.minecraft.client.FullscreenResolutionProgressOption
- net.minecraft.client.Game
+ net.minecraft.client.Game$Metrics
- net.minecraft.client.gui.chat.ChatListener
+ net.minecraft.client.gui.chat.NarratorChatListener
- net.minecraft.client.gui.chat.OverlayChatListener
- net.minecraft.client.gui.chat.package-info
+ net.minecraft.client.gui.chat.StandardChatListener
+ net.minecraft.client.gui.components.AbstractButton
- net.minecraft.client.gui.components.AbstractOptionSliderButton
+ net.minecraft.client.gui.components.AbstractSelectionList
- net.minecraft.client.gui.components.AbstractSelectionList$1
+ net.minecraft.client.gui.components.AbstractSelectionList$Entry
- net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
+ net.minecraft.client.gui.components.AbstractSliderButton
- net.minecraft.client.gui.components.AbstractWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.Button
+ net.minecraft.client.gui.components.Button$OnPress
- net.minecraft.client.gui.components.ChatComponent
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$1
- net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
+ net.minecraft.client.gui.components.ComponentRenderUtils
- net.minecraft.client.gui.components.ContainerObjectSelectionList
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
- net.minecraft.client.gui.components.DebugScreenOverlay
+ net.minecraft.client.gui.components.DebugScreenOverlay$1
- net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.events.AbstractContainerEventHandler
+ net.minecraft.client.gui.components.events.ContainerEventHandler
- net.minecraft.client.gui.components.events.GuiEventListener
+ net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.LerpingBossEvent
+ net.minecraft.client.gui.components.LerpingBossEvent$1
- net.minecraft.client.gui.components.LockIconButton
+ net.minecraft.client.gui.components.LockIconButton$Icon
- net.minecraft.client.gui.components.ObjectSelectionList
+ net.minecraft.client.gui.components.ObjectSelectionList$Entry
- net.minecraft.client.gui.components.OptionButton
+ net.minecraft.client.gui.components.OptionsList
- net.minecraft.client.gui.components.OptionsList$Entry
- net.minecraft.client.gui.components.package-info
+ net.minecraft.client.gui.components.PlayerTabOverlay
- net.minecraft.client.gui.components.PlayerTabOverlay$1
+ net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
- net.minecraft.client.gui.components.ScrolledSelectionList
+ net.minecraft.client.gui.components.SliderButton
- net.minecraft.client.gui.components.spectator.package-info
+ net.minecraft.client.gui.components.spectator.SpectatorGui
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.SubtitleOverlay
- net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
+ net.minecraft.client.gui.components.TickableWidget
+ net.minecraft.client.gui.components.toasts.AdvancementToast
- net.minecraft.client.gui.components.toasts.package-info
- net.minecraft.client.gui.components.toasts.RecipeToast
+ net.minecraft.client.gui.components.toasts.SystemToast
- net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
+ net.minecraft.client.gui.components.toasts.Toast
- net.minecraft.client.gui.components.toasts.Toast$Visibility
+ net.minecraft.client.gui.components.toasts.ToastComponent
- net.minecraft.client.gui.components.toasts.ToastComponent$1
+ net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
- net.minecraft.client.gui.components.toasts.TutorialToast
+ net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.VolumeSlider
+ net.minecraft.client.gui.components.Widget
- net.minecraft.client.gui.Font
+ net.minecraft.client.gui.font.AllMissingGlyphProvider
- net.minecraft.client.gui.font.FontManager
+ net.minecraft.client.gui.font.FontManager$1
- net.minecraft.client.gui.font.FontManager$2
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontTexture
+ net.minecraft.client.gui.font.FontTexture$1
- net.minecraft.client.gui.font.FontTexture$Node
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
- net.minecraft.client.gui.font.glyphs.EmptyGlyph
+ net.minecraft.client.gui.font.glyphs.MissingGlyph
+ net.minecraft.client.gui.font.glyphs.package-info
- net.minecraft.client.gui.font.glyphs.WhiteGlyph
- net.minecraft.client.gui.font.package-info
+ net.minecraft.client.gui.font.providers.BitmapProvider
- net.minecraft.client.gui.font.providers.BitmapProvider$1
+ net.minecraft.client.gui.font.providers.BitmapProvider$Builder
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilder
- net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$1
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Builder
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- net.minecraft.client.gui.font.providers.package-info
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
+ net.minecraft.client.gui.font.TextFieldHelper
+ net.minecraft.client.gui.Gui
- net.minecraft.client.gui.GuiComponent
+ net.minecraft.client.gui.MapRenderer
- net.minecraft.client.gui.MapRenderer$1
+ net.minecraft.client.gui.MapRenderer$MapInstance
+ net.minecraft.client.gui.package-info
- net.minecraft.client.gui.screens.AccessibilityOptionsScreen
- net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$1
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ net.minecraft.client.gui.screens.achievement.StatsUpdateListener
- net.minecraft.client.gui.screens.advancements.AdvancementsScreen
+ net.minecraft.client.gui.screens.advancements.AdvancementTab
- net.minecraft.client.gui.screens.advancements.AdvancementTabType
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
- net.minecraft.client.gui.screens.advancements.AdvancementWidget
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
+ net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.AlertScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
- net.minecraft.client.gui.screens.ChatOptionsScreen
+ net.minecraft.client.gui.screens.ChatScreen
- net.minecraft.client.gui.screens.ChatScreen$1
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
- net.minecraft.client.gui.screens.controls.ControlList
+ net.minecraft.client.gui.screens.controls.ControlList$1
- net.minecraft.client.gui.screens.controls.ControlList$CategoryEntry
+ net.minecraft.client.gui.screens.controls.ControlList$Entry
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$2
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$1
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$1
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.DeathScreen
- net.minecraft.client.gui.screens.DemoIntroScreen
+ net.minecraft.client.gui.screens.DirectJoinServerScreen
- net.minecraft.client.gui.screens.DisconnectedScreen
+ net.minecraft.client.gui.screens.EditServerScreen
- net.minecraft.client.gui.screens.ErrorScreen
+ net.minecraft.client.gui.screens.GenericDirtMessageScreen
- net.minecraft.client.gui.screens.InBedChatScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
- net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.AnvilScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$1
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen
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
- net.minecraft.client.gui.screens.inventory.CraftingScreen
+ net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- net.minecraft.client.gui.screens.inventory.DispenserScreen
+ net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
- net.minecraft.client.gui.screens.inventory.EnchantmentNames
+ net.minecraft.client.gui.screens.inventory.EnchantmentScreen
- net.minecraft.client.gui.screens.inventory.FurnaceScreen
+ net.minecraft.client.gui.screens.inventory.GrindstoneScreen
- net.minecraft.client.gui.screens.inventory.HopperScreen
+ net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
- net.minecraft.client.gui.screens.inventory.InventoryScreen
+ net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.LecternScreen
- net.minecraft.client.gui.screens.inventory.LecternScreen$1
+ net.minecraft.client.gui.screens.inventory.LoomScreen
- net.minecraft.client.gui.screens.inventory.MenuAccess
+ net.minecraft.client.gui.screens.inventory.MerchantScreen
- net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
+ net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.package-info
- net.minecraft.client.gui.screens.inventory.PageButton
+ net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
- net.minecraft.client.gui.screens.inventory.SignEditScreen
+ net.minecraft.client.gui.screens.inventory.SmithingScreen
- net.minecraft.client.gui.screens.inventory.SmokerScreen
+ net.minecraft.client.gui.screens.inventory.StonecutterScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
+ net.minecraft.client.gui.screens.LanguageSelectScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingOverlay
- net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.mco.package-info
+ net.minecraft.client.gui.screens.MenuScreens
- net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
+ net.minecraft.client.gui.screens.MouseSettingsScreen
+ net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
- net.minecraft.client.gui.screens.multiplayer.package-info
- net.minecraft.client.gui.screens.multiplayer.SafetyScreen
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- net.minecraft.client.gui.screens.OptionsScreen
+ net.minecraft.client.gui.screens.OptionsSubScreen
- net.minecraft.client.gui.screens.OutOfMemoryScreen
+ net.minecraft.client.gui.screens.Overlay
+ net.minecraft.client.gui.screens.package-info
- net.minecraft.client.gui.screens.PauseScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ net.minecraft.client.gui.screens.ProgressScreen
- net.minecraft.client.gui.screens.ReceivingLevelScreen
- net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.BlastingRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.GhostRecipe
+ net.minecraft.client.gui.screens.recipebook.GhostRecipe$GhostIngredient
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
+ net.minecraft.client.gui.screens.recipebook.package-info
- net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.RecipeBookPage
- net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
+ net.minecraft.client.gui.screens.recipebook.RecipeButton
- net.minecraft.client.gui.screens.recipebook.RecipeCollection
+ net.minecraft.client.gui.screens.recipebook.RecipeShownListener
- net.minecraft.client.gui.screens.recipebook.RecipeUpdateListener
+ net.minecraft.client.gui.screens.recipebook.SmeltingRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
+ net.minecraft.client.gui.screens.resourcepacks.entries.package-info
- net.minecraft.client.gui.screens.resourcepacks.lists.AvailableResourcePackList
- net.minecraft.client.gui.screens.resourcepacks.lists.package-info
+ net.minecraft.client.gui.screens.resourcepacks.lists.ResourcePackList
- net.minecraft.client.gui.screens.resourcepacks.lists.ResourcePackList$ResourcePackEntry
+ net.minecraft.client.gui.screens.resourcepacks.lists.SelectedResourcePackList
+ net.minecraft.client.gui.screens.resourcepacks.package-info
- net.minecraft.client.gui.screens.resourcepacks.ResourcePackSelectScreen
+ net.minecraft.client.gui.screens.Screen
- net.minecraft.client.gui.screens.ShareToLanScreen
+ net.minecraft.client.gui.screens.SkinCustomizationScreen
- net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.stream.package-info
+ net.minecraft.client.gui.screens.TitleScreen
- net.minecraft.client.gui.screens.VideoSettingsScreen
+ net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$1
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$2
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$3
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$4
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$5
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$6
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$7
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$SelectedGameMode
- net.minecraft.client.gui.screens.worldselection.EditWorldScreen
+ net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
+ net.minecraft.client.gui.screens.worldselection.package-info
- net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
+ net.minecraft.client.gui.spectator.categories.package-info
+ net.minecraft.client.gui.spectator.categories.SpectatorPage
- net.minecraft.client.gui.spectator.categories.TeleportToPlayerMenuCategory
+ net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory
- net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
- net.minecraft.client.gui.spectator.package-info
- net.minecraft.client.gui.spectator.PlayerMenuItem
+ net.minecraft.client.gui.spectator.RootSpectatorMenuCategory
- net.minecraft.client.gui.spectator.SpectatorMenu
+ net.minecraft.client.gui.spectator.SpectatorMenu$1
- net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
+ net.minecraft.client.gui.spectator.SpectatorMenu$ScrollMenuItem
- net.minecraft.client.gui.spectator.SpectatorMenuCategory
+ net.minecraft.client.gui.spectator.SpectatorMenuItem
- net.minecraft.client.gui.spectator.SpectatorMenuListener
- net.minecraft.client.GuiMessage
+ net.minecraft.client.HotbarManager
- net.minecraft.client.KeyboardHandler
+ net.minecraft.client.KeyboardHandler$1
- net.minecraft.client.KeyMapping
+ net.minecraft.client.KeyMapping$1
- net.minecraft.client.LogaritmicProgressOption
+ net.minecraft.client.main.GameConfig
- net.minecraft.client.main.GameConfig$FolderData
+ net.minecraft.client.main.GameConfig$GameData
- net.minecraft.client.main.GameConfig$ServerData
+ net.minecraft.client.main.GameConfig$UserData
- net.minecraft.client.main.Main
+ net.minecraft.client.main.Main$1
- net.minecraft.client.main.Main$2
+ net.minecraft.client.main.Main$3
+ net.minecraft.client.main.package-info
- net.minecraft.client.main.SilentInitException
- net.minecraft.client.map.Map
+ net.minecraft.client.map.Map$1
- net.minecraft.client.map.Map$2
+ net.minecraft.client.map.Map$3
- net.minecraft.client.map.package-info
+ net.minecraft.client.Minecraft
- net.minecraft.client.Minecraft$1
+ net.minecraft.client.Minecraft$2
+ net.minecraft.client.model.AbstractZombieModel
- net.minecraft.client.model.AgeableListModel
+ net.minecraft.client.model.AnimationUtils
- net.minecraft.client.model.ArmedModel
+ net.minecraft.client.model.ArmorStandArmorModel
- net.minecraft.client.model.ArmorStandModel
+ net.minecraft.client.model.BatModel
- net.minecraft.client.model.BeeModel
+ net.minecraft.client.model.BlazeModel
- net.minecraft.client.model.BoatModel
+ net.minecraft.client.model.BookModel
- net.minecraft.client.model.CatModel
+ net.minecraft.client.model.ChestedHorseModel
- net.minecraft.client.model.ChickenModel
+ net.minecraft.client.model.CodModel
- net.minecraft.client.model.ColorableAgeableListModel
+ net.minecraft.client.model.ColorableListModel
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
+ net.minecraft.client.model.geom.ModelPart
- net.minecraft.client.model.geom.ModelPart$Cube
+ net.minecraft.client.model.geom.ModelPart$Polygon
- net.minecraft.client.model.geom.ModelPart$Vertex
+ net.minecraft.client.model.geom.package-info
- net.minecraft.client.model.GhastModel
+ net.minecraft.client.model.GiantZombieModel
- net.minecraft.client.model.GuardianModel
+ net.minecraft.client.model.HeadedModel
- net.minecraft.client.model.HoglinModel
+ net.minecraft.client.model.HorseModel
- net.minecraft.client.model.HumanoidHeadModel
+ net.minecraft.client.model.HumanoidModel
- net.minecraft.client.model.HumanoidModel$1
+ net.minecraft.client.model.HumanoidModel$ArmPose
- net.minecraft.client.model.IllagerModel
+ net.minecraft.client.model.IronGolemModel
- net.minecraft.client.model.LavaSlimeModel
+ net.minecraft.client.model.LeashKnotModel
- net.minecraft.client.model.ListModel
+ net.minecraft.client.model.LlamaModel
- net.minecraft.client.model.LlamaSpitModel
+ net.minecraft.client.model.MinecartModel
- net.minecraft.client.model.Model
+ net.minecraft.client.model.ModelUtils
- net.minecraft.client.model.OcelotModel
- net.minecraft.client.model.package-info
+ net.minecraft.client.model.PandaModel
- net.minecraft.client.model.ParrotModel
+ net.minecraft.client.model.ParrotModel$1
- net.minecraft.client.model.ParrotModel$State
+ net.minecraft.client.model.PhantomModel
+ net.minecraft.client.model.PiglinModel
- net.minecraft.client.model.PigModel
- net.minecraft.client.model.PlayerModel
+ net.minecraft.client.model.PolarBearModel
- net.minecraft.client.model.PufferfishBigModel
+ net.minecraft.client.model.PufferfishMidModel
- net.minecraft.client.model.PufferfishSmallModel
+ net.minecraft.client.model.QuadrupedModel
- net.minecraft.client.model.RabbitModel
+ net.minecraft.client.model.RavagerModel
- net.minecraft.client.model.SalmonModel
+ net.minecraft.client.model.SheepFurModel
- net.minecraft.client.model.SheepModel
+ net.minecraft.client.model.ShieldModel
- net.minecraft.client.model.ShulkerBulletModel
+ net.minecraft.client.model.ShulkerModel
- net.minecraft.client.model.SilverfishModel
+ net.minecraft.client.model.SkeletonModel
- net.minecraft.client.model.SkullModel
+ net.minecraft.client.model.SlimeModel
- net.minecraft.client.model.SnowGolemModel
+ net.minecraft.client.model.SpiderModel
- net.minecraft.client.model.SquidModel
+ net.minecraft.client.model.TridentModel
- net.minecraft.client.model.TropicalFishModelA
+ net.minecraft.client.model.TropicalFishModelB
- net.minecraft.client.model.TurtleModel
+ net.minecraft.client.model.VexModel
- net.minecraft.client.model.VillagerHeadModel
+ net.minecraft.client.model.VillagerModel
- net.minecraft.client.model.WitchModel
+ net.minecraft.client.model.WitherBossModel
- net.minecraft.client.model.WolfModel
+ net.minecraft.client.model.ZombieModel
- net.minecraft.client.model.ZombieVillagerModel
- net.minecraft.client.MouseHandler
+ net.minecraft.client.multiplayer.ClientAdvancements
- net.minecraft.client.multiplayer.ClientAdvancements$Listener
+ net.minecraft.client.multiplayer.ClientChunkCache
- net.minecraft.client.multiplayer.ClientChunkCache$1
+ net.minecraft.client.multiplayer.ClientChunkCache$Storage
- net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
+ net.minecraft.client.multiplayer.ClientLevel
- net.minecraft.client.multiplayer.ClientLevel$1
+ net.minecraft.client.multiplayer.ClientPacketListener
- net.minecraft.client.multiplayer.ClientPacketListener$1
+ net.minecraft.client.multiplayer.ClientSuggestionProvider
- net.minecraft.client.multiplayer.MultiPlayerGameMode
- net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.ServerAddress
+ net.minecraft.client.multiplayer.ServerData
- net.minecraft.client.multiplayer.ServerData$ServerPackStatus
+ net.minecraft.client.multiplayer.ServerList
- net.minecraft.client.multiplayer.ServerStatusPinger
+ net.minecraft.client.multiplayer.ServerStatusPinger$1
- net.minecraft.client.multiplayer.ServerStatusPinger$2
+ net.minecraft.client.multiplayer.ServerStatusPinger$2$1
+ net.minecraft.client.NarratorStatus
- net.minecraft.client.Option
+ net.minecraft.client.Options
- net.minecraft.client.Options$1
+ net.minecraft.client.Options$2
+ net.minecraft.client.package-info
- net.minecraft.client.particle.AshParticle
+ net.minecraft.client.particle.AshParticle$Provider
- net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.AttackSweepParticle$1
- net.minecraft.client.particle.AttackSweepParticle$Provider
+ net.minecraft.client.particle.BarrierParticle
- net.minecraft.client.particle.BarrierParticle$1
+ net.minecraft.client.particle.BarrierParticle$Provider
- net.minecraft.client.particle.BaseAshSmokeParticle
+ net.minecraft.client.particle.BreakingItemParticle
- net.minecraft.client.particle.BreakingItemParticle$1
+ net.minecraft.client.particle.BreakingItemParticle$Provider
- net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
+ net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
- net.minecraft.client.particle.BubbleColumnUpParticle
+ net.minecraft.client.particle.BubbleColumnUpParticle$1
- net.minecraft.client.particle.BubbleColumnUpParticle$Provider
+ net.minecraft.client.particle.BubbleParticle
- net.minecraft.client.particle.BubbleParticle$1
+ net.minecraft.client.particle.BubbleParticle$Provider
- net.minecraft.client.particle.BubblePopParticle
+ net.minecraft.client.particle.BubblePopParticle$1
- net.minecraft.client.particle.BubblePopParticle$Provider
+ net.minecraft.client.particle.CampfireSmokeParticle
- net.minecraft.client.particle.CampfireSmokeParticle$1
+ net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
- net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
+ net.minecraft.client.particle.CritParticle
- net.minecraft.client.particle.CritParticle$1
+ net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
- net.minecraft.client.particle.CritParticle$MagicProvider
+ net.minecraft.client.particle.CritParticle$Provider
- net.minecraft.client.particle.DragonBreathParticle
+ net.minecraft.client.particle.DragonBreathParticle$1
- net.minecraft.client.particle.DragonBreathParticle$Provider
+ net.minecraft.client.particle.DripParticle
- net.minecraft.client.particle.DripParticle$1
+ net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
- net.minecraft.client.particle.DripParticle$DripHangParticle
+ net.minecraft.client.particle.DripParticle$DripLandParticle
- net.minecraft.client.particle.DripParticle$FallAndLandParticle
+ net.minecraft.client.particle.DripParticle$FallingParticle
- net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
+ net.minecraft.client.particle.DripParticle$HoneyFallProvider
- net.minecraft.client.particle.DripParticle$HoneyHangProvider
+ net.minecraft.client.particle.DripParticle$HoneyLandProvider
- net.minecraft.client.particle.DripParticle$LavaFallProvider
+ net.minecraft.client.particle.DripParticle$LavaHangProvider
- net.minecraft.client.particle.DripParticle$LavaLandProvider
+ net.minecraft.client.particle.DripParticle$NectarFallProvider
- net.minecraft.client.particle.DripParticle$ObsidianTearFallProvider
+ net.minecraft.client.particle.DripParticle$ObsidianTearHangProvider
- net.minecraft.client.particle.DripParticle$ObsidianTearLandProvider
+ net.minecraft.client.particle.DripParticle$WaterFallProvider
- net.minecraft.client.particle.DripParticle$WaterHangProvider
+ net.minecraft.client.particle.DustParticle
- net.minecraft.client.particle.DustParticle$1
+ net.minecraft.client.particle.DustParticle$Provider
- net.minecraft.client.particle.EnchantmentTableParticle
+ net.minecraft.client.particle.EnchantmentTableParticle$1
- net.minecraft.client.particle.EnchantmentTableParticle$NautilusProvider
+ net.minecraft.client.particle.EnchantmentTableParticle$Provider
- net.minecraft.client.particle.EndRodParticle
+ net.minecraft.client.particle.EndRodParticle$1
- net.minecraft.client.particle.EndRodParticle$Provider
+ net.minecraft.client.particle.ExplodeParticle
- net.minecraft.client.particle.ExplodeParticle$Provider
+ net.minecraft.client.particle.FallingDustParticle
- net.minecraft.client.particle.FallingDustParticle$1
+ net.minecraft.client.particle.FallingDustParticle$Provider
- net.minecraft.client.particle.FireworkParticles
+ net.minecraft.client.particle.FireworkParticles$1
- net.minecraft.client.particle.FireworkParticles$FlashProvider
+ net.minecraft.client.particle.FireworkParticles$OverlayParticle
- net.minecraft.client.particle.FireworkParticles$SparkParticle
+ net.minecraft.client.particle.FireworkParticles$SparkProvider
- net.minecraft.client.particle.FireworkParticles$Starter
+ net.minecraft.client.particle.FlameParticle
- net.minecraft.client.particle.FlameParticle$1
+ net.minecraft.client.particle.FlameParticle$Provider
- net.minecraft.client.particle.HeartParticle
+ net.minecraft.client.particle.HeartParticle$1
- net.minecraft.client.particle.HeartParticle$AngryVillagerProvider
+ net.minecraft.client.particle.HeartParticle$Provider
- net.minecraft.client.particle.HugeExplosionParticle
+ net.minecraft.client.particle.HugeExplosionParticle$1
- net.minecraft.client.particle.HugeExplosionParticle$Provider
+ net.minecraft.client.particle.HugeExplosionSeedParticle
- net.minecraft.client.particle.HugeExplosionSeedParticle$1
+ net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
- net.minecraft.client.particle.ItemPickupParticle
+ net.minecraft.client.particle.LargeSmokeParticle
- net.minecraft.client.particle.LargeSmokeParticle$Provider
+ net.minecraft.client.particle.LavaParticle
- net.minecraft.client.particle.LavaParticle$1
+ net.minecraft.client.particle.LavaParticle$Provider
- net.minecraft.client.particle.MobAppearanceParticle
+ net.minecraft.client.particle.MobAppearanceParticle$1
- net.minecraft.client.particle.MobAppearanceParticle$Provider
+ net.minecraft.client.particle.NoRenderParticle
- net.minecraft.client.particle.NoteParticle
+ net.minecraft.client.particle.NoteParticle$1
- net.minecraft.client.particle.NoteParticle$Provider
+ net.minecraft.client.particle.package-info
+ net.minecraft.client.particle.Particle
- net.minecraft.client.particle.ParticleDescription
+ net.minecraft.client.particle.ParticleEngine
- net.minecraft.client.particle.ParticleEngine$1
+ net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
- net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
+ net.minecraft.client.particle.ParticleProvider
- net.minecraft.client.particle.ParticleRenderType
+ net.minecraft.client.particle.ParticleRenderType$1
- net.minecraft.client.particle.ParticleRenderType$2
+ net.minecraft.client.particle.ParticleRenderType$3
- net.minecraft.client.particle.ParticleRenderType$4
+ net.minecraft.client.particle.ParticleRenderType$5
- net.minecraft.client.particle.ParticleRenderType$6
+ net.minecraft.client.particle.PlayerCloudParticle
- net.minecraft.client.particle.PlayerCloudParticle$1
+ net.minecraft.client.particle.PlayerCloudParticle$Provider
- net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
+ net.minecraft.client.particle.PortalParticle
- net.minecraft.client.particle.ReversePortalParticle$1
- net.minecraft.client.particle.RisingParticle
+ net.minecraft.client.particle.SimpleAnimatedParticle
- net.minecraft.client.particle.SingleQuadParticle
+ net.minecraft.client.particle.SmokeParticle
- net.minecraft.client.particle.SmokeParticle$Provider
+ net.minecraft.client.particle.SoulParticle
- net.minecraft.client.particle.SoulParticle$1
+ net.minecraft.client.particle.SoulParticle$Provider
- net.minecraft.client.particle.SpellParticle
+ net.minecraft.client.particle.SpellParticle$1
- net.minecraft.client.particle.SpellParticle$AmbientMobProvider
+ net.minecraft.client.particle.SpellParticle$InstantProvider
- net.minecraft.client.particle.SpellParticle$MobProvider
+ net.minecraft.client.particle.SpellParticle$Provider
- net.minecraft.client.particle.SpellParticle$WitchProvider
+ net.minecraft.client.particle.SpitParticle
- net.minecraft.client.particle.SpitParticle$1
+ net.minecraft.client.particle.SpitParticle$Provider
- net.minecraft.client.particle.SplashParticle
+ net.minecraft.client.particle.SplashParticle$1
- net.minecraft.client.particle.SplashParticle$Provider
+ net.minecraft.client.particle.SpriteSet
- net.minecraft.client.particle.SquidInkParticle
+ net.minecraft.client.particle.SquidInkParticle$1
- net.minecraft.client.particle.SquidInkParticle$Provider
+ net.minecraft.client.particle.SuspendedParticle
- net.minecraft.client.particle.SuspendedParticle$1
+ net.minecraft.client.particle.SuspendedParticle$CrimsonSporeProvider
- net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
+ net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
- net.minecraft.client.particle.SuspendedTownParticle
+ net.minecraft.client.particle.SuspendedTownParticle$1
- net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
+ net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ net.minecraft.client.particle.SuspendedTownParticle$Provider
- net.minecraft.client.particle.TerrainParticle
+ net.minecraft.client.particle.TerrainParticle$Provider
- net.minecraft.client.particle.TextureSheetParticle
+ net.minecraft.client.particle.TotemParticle
- net.minecraft.client.particle.TotemParticle$1
+ net.minecraft.client.particle.TotemParticle$Provider
- net.minecraft.client.particle.TrackingEmitter
+ net.minecraft.client.particle.WakeParticle
- net.minecraft.client.particle.WakeParticle$1
+ net.minecraft.client.particle.WakeParticle$Provider
- net.minecraft.client.particle.WaterCurrentDownParticle
+ net.minecraft.client.particle.WaterCurrentDownParticle$1
- net.minecraft.client.particle.WaterCurrentDownParticle$Provider
+ net.minecraft.client.particle.WaterDropParticle
- net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.ParticleStatus
- net.minecraft.client.player.AbstractClientPlayer
+ net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
- net.minecraft.client.player.KeyboardInput
+ net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.LocalPlayer$1
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
+ net.minecraft.client.ProgressOption
- net.minecraft.client.RecipeBookCategories
- net.minecraft.client.renderer.banner.package-info
+ net.minecraft.client.renderer.BiomeColors
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
- net.minecraft.client.renderer.blockentity.BrightnessCombiner
+ net.minecraft.client.renderer.blockentity.CampfireRenderer
- net.minecraft.client.renderer.blockentity.ChestRenderer
+ net.minecraft.client.renderer.blockentity.ConduitRenderer
- net.minecraft.client.renderer.blockentity.EnchantTableRenderer
+ net.minecraft.client.renderer.blockentity.LecternRenderer
+ net.minecraft.client.renderer.blockentity.package-info
- net.minecraft.client.renderer.blockentity.PistonHeadRenderer
+ net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
- net.minecraft.client.renderer.blockentity.SkullBlockRenderer
+ net.minecraft.client.renderer.blockentity.SkullBlockRenderer$1
- net.minecraft.client.renderer.blockentity.SpawnerRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
+ net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
- net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
- net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
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
+ net.minecraft.client.renderer.ChunkBufferBuilderPack
- net.minecraft.client.renderer.CubeMap
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
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer
- net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ net.minecraft.client.renderer.debug.HeightMapRenderer
- net.minecraft.client.renderer.debug.LightDebugRenderer
+ net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
+ net.minecraft.client.renderer.debug.package-info
- net.minecraft.client.renderer.debug.PathfindingRenderer
+ net.minecraft.client.renderer.debug.RaidDebugRenderer
- net.minecraft.client.renderer.debug.SolidFaceRenderer
+ net.minecraft.client.renderer.debug.StructureRenderer
- net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
+ net.minecraft.client.renderer.debug.WaterDebugRenderer
- net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.EffectInstance
- net.minecraft.client.renderer.entity.AbstractHorseRenderer
+ net.minecraft.client.renderer.entity.AbstractZombieRenderer
- net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
+ net.minecraft.client.renderer.entity.ArmorStandRenderer
- net.minecraft.client.renderer.entity.ArrowRenderer
+ net.minecraft.client.renderer.entity.BatRenderer
- net.minecraft.client.renderer.entity.BeeRenderer
+ net.minecraft.client.renderer.entity.BlazeRenderer
- net.minecraft.client.renderer.entity.BoatRenderer
+ net.minecraft.client.renderer.entity.CatRenderer
- net.minecraft.client.renderer.entity.CaveSpiderRenderer
+ net.minecraft.client.renderer.entity.ChestedHorseRenderer
- net.minecraft.client.renderer.entity.ChickenRenderer
+ net.minecraft.client.renderer.entity.CodRenderer
- net.minecraft.client.renderer.entity.CowRenderer
+ net.minecraft.client.renderer.entity.CreeperRenderer
- net.minecraft.client.renderer.entity.DolphinRenderer
+ net.minecraft.client.renderer.entity.DragonFireballRenderer
- net.minecraft.client.renderer.entity.DrownedRenderer
+ net.minecraft.client.renderer.entity.ElderGuardianRenderer
- net.minecraft.client.renderer.entity.EndCrystalRenderer
+ net.minecraft.client.renderer.entity.EnderDragonRenderer
- net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
+ net.minecraft.client.renderer.entity.EndermanRenderer
- net.minecraft.client.renderer.entity.EndermiteRenderer
+ net.minecraft.client.renderer.entity.EntityRenderDispatcher
- net.minecraft.client.renderer.entity.EntityRenderer
+ net.minecraft.client.renderer.entity.EvokerFangsRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer$1
- net.minecraft.client.renderer.entity.ExperienceOrbRenderer
+ net.minecraft.client.renderer.entity.FallingBlockRenderer
- net.minecraft.client.renderer.entity.FireworkEntityRenderer
+ net.minecraft.client.renderer.entity.FishingHookRenderer
- net.minecraft.client.renderer.entity.FoxRenderer
+ net.minecraft.client.renderer.entity.GhastRenderer
- net.minecraft.client.renderer.entity.GiantMobRenderer
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
- net.minecraft.client.renderer.entity.layers.AbstractArmorLayer
+ net.minecraft.client.renderer.entity.layers.ArrowLayer
- net.minecraft.client.renderer.entity.layers.BeeStingerLayer
+ net.minecraft.client.renderer.entity.layers.CapeLayer
- net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
+ net.minecraft.client.renderer.entity.layers.CatCollarLayer
- net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
+ net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
- net.minecraft.client.renderer.entity.layers.CustomHeadLayer
+ net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
- net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
+ net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
- net.minecraft.client.renderer.entity.layers.ElytraLayer
+ net.minecraft.client.renderer.entity.layers.EnderEyesLayer
- net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
+ net.minecraft.client.renderer.entity.layers.EyesLayer
- net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
+ net.minecraft.client.renderer.entity.layers.HorseArmorLayer
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
+ net.minecraft.client.renderer.entity.layers.PiglinArmorLayer
- net.minecraft.client.renderer.entity.layers.PigSaddleLayer
- net.minecraft.client.renderer.entity.layers.RenderLayer
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
- net.minecraft.client.renderer.entity.ThrownItemRenderer
+ net.minecraft.client.renderer.entity.ThrownTridentRenderer
- net.minecraft.client.renderer.entity.TippableArrowRenderer
+ net.minecraft.client.renderer.entity.TntMinecartRenderer
- net.minecraft.client.renderer.entity.TntRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer
- net.minecraft.client.renderer.entity.TurtleRenderer
+ net.minecraft.client.renderer.entity.UndeadHorseRenderer
- net.minecraft.client.renderer.entity.VexRenderer
+ net.minecraft.client.renderer.entity.VillagerRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer$1
- net.minecraft.client.renderer.entity.WanderingTraderRenderer
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZombieRenderer
+ net.minecraft.client.renderer.entity.ZombieVillagerRenderer
- net.minecraft.client.renderer.FaceInfo
+ net.minecraft.client.renderer.FaceInfo$1
- net.minecraft.client.renderer.FaceInfo$Constants
+ net.minecraft.client.renderer.FaceInfo$VertexInfo
- net.minecraft.client.renderer.FogRenderer
+ net.minecraft.client.renderer.FogRenderer$FogMode
- net.minecraft.client.renderer.GameRenderer
+ net.minecraft.client.renderer.ItemBlockRenderTypes
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
- net.minecraft.client.renderer.ItemModelShaper
+ net.minecraft.client.renderer.LevelRenderer
- net.minecraft.client.renderer.LevelRenderer$1
+ net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
- net.minecraft.client.renderer.LightTexture
+ net.minecraft.client.renderer.MultiBufferSource
- net.minecraft.client.renderer.MultiBufferSource$BufferSource
+ net.minecraft.client.renderer.OutlineBufferSource
- net.minecraft.client.renderer.OutlineBufferSource$1
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.package-info
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
+ net.minecraft.client.renderer.texture.AbstractTexture
- net.minecraft.client.renderer.texture.AtlasSet
+ net.minecraft.client.renderer.texture.DynamicTexture
- net.minecraft.client.renderer.texture.HttpTexture
+ net.minecraft.client.renderer.texture.LayeredTexture
- net.minecraft.client.renderer.texture.MipmapGenerator
+ net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
- net.minecraft.client.renderer.texture.OverlayTexture
+ net.minecraft.client.renderer.texture.package-info
+ net.minecraft.client.renderer.texture.PreloadedTexture
- net.minecraft.client.renderer.texture.SimpleTexture
+ net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
- net.minecraft.client.renderer.texture.Stitcher
+ net.minecraft.client.renderer.texture.Stitcher$Holder
- net.minecraft.client.renderer.texture.Stitcher$Region
+ net.minecraft.client.renderer.texture.Stitcher$SpriteLoader
- net.minecraft.client.renderer.texture.StitcherException
+ net.minecraft.client.renderer.texture.TextureAtlas
- net.minecraft.client.renderer.texture.TextureAtlas$Preparations
+ net.minecraft.client.renderer.texture.TextureAtlasSprite
- net.minecraft.client.renderer.texture.TextureAtlasSprite$1
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$Info
- net.minecraft.client.renderer.texture.TextureAtlasSprite$InterpolationData
+ net.minecraft.client.renderer.texture.TextureManager
- net.minecraft.client.renderer.texture.Tickable
- net.minecraft.client.renderer.ViewArea
+ net.minecraft.client.renderer.VirtualScreen
- net.minecraft.client.resources.AssetIndex
+ net.minecraft.client.resources.ClientPackSource
- net.minecraft.client.resources.ClientPackSource$1
+ net.minecraft.client.resources.ClientPackSource$2
- net.minecraft.client.resources.DefaultClientResourcePack
+ net.minecraft.client.resources.DefaultPlayerSkin
- net.minecraft.client.resources.DirectAssetIndex
+ net.minecraft.client.resources.FoliageColorReloadListener
- net.minecraft.client.resources.GrassColorReloadListener
- net.minecraft.client.resources.language.I18n
+ net.minecraft.client.resources.language.Language
- net.minecraft.client.resources.language.LanguageManager
+ net.minecraft.client.resources.language.Locale
- net.minecraft.client.resources.language.package-info
+ net.minecraft.client.resources.LegacyResourcePackAdapter
- net.minecraft.client.resources.LegacyStuffWrapper
+ net.minecraft.client.resources.metadata.animation.AnimationFrame
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
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
+ net.minecraft.client.resources.MobEffectTextureManager
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
- net.minecraft.client.resources.model.package-info
- net.minecraft.client.resources.model.SimpleBakedModel
+ net.minecraft.client.resources.model.SimpleBakedModel$Builder
- net.minecraft.client.resources.model.UnbakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel
- net.minecraft.client.resources.model.WeightedBakedModel$Builder
+ net.minecraft.client.resources.model.WeightedBakedModel$WeightedModel
- net.minecraft.client.resources.PackAdapterV4
+ net.minecraft.client.resources.package-info
+ net.minecraft.client.resources.PaintingTextureManager
- net.minecraft.client.resources.SkinManager
+ net.minecraft.client.resources.SkinManager$1
- net.minecraft.client.resources.SkinManager$SkinTextureCallback
- net.minecraft.client.resources.sounds.AbstractSoundInstance
+ net.minecraft.client.resources.sounds.AbstractTickableSoundInstance
- net.minecraft.client.resources.sounds.AmbientSoundHandler
+ net.minecraft.client.resources.sounds.BeeAggressiveSoundInstance
- net.minecraft.client.resources.sounds.BeeFlyingSoundInstance
+ net.minecraft.client.resources.sounds.BeeSoundInstance
- net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
+ net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
- net.minecraft.client.resources.sounds.BubbleColumnAmbientSoundHandler
+ net.minecraft.client.resources.sounds.ElytraOnPlayerSoundInstance
- net.minecraft.client.resources.sounds.EntityBoundSoundInstance
+ net.minecraft.client.resources.sounds.GuardianAttackSoundInstance
- net.minecraft.client.resources.sounds.MinecartSoundInstance
- net.minecraft.client.resources.sounds.package-info
+ net.minecraft.client.resources.sounds.RidingMinecartSoundInstance
- net.minecraft.client.resources.sounds.SimpleSoundInstance
+ net.minecraft.client.resources.sounds.Sound
- net.minecraft.client.resources.sounds.Sound$Type
+ net.minecraft.client.resources.sounds.SoundEventRegistration
- net.minecraft.client.resources.sounds.SoundEventRegistrationSerializer
+ net.minecraft.client.resources.sounds.SoundInstance
- net.minecraft.client.resources.sounds.SoundInstance$Attenuation
+ net.minecraft.client.resources.sounds.TickableSoundInstance
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundHandler
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
+ net.minecraft.client.resources.SplashManager
- net.minecraft.client.resources.TextureAtlasHolder
+ net.minecraft.client.resources.UnopenedResourcePack
+ net.minecraft.client.Screenshot
+ net.minecraft.client.searchtree.MutableSearchTree
+ net.minecraft.client.searchtree.package-info
- net.minecraft.client.searchtree.ReloadableIdSearchTree
+ net.minecraft.client.searchtree.ReloadableIdSearchTree$IntersectionIterator
- net.minecraft.client.searchtree.ReloadableSearchTree
+ net.minecraft.client.searchtree.ReloadableSearchTree$MergingUniqueIterator
- net.minecraft.client.searchtree.SearchRegistry
+ net.minecraft.client.searchtree.SearchRegistry$Key
- net.minecraft.client.searchtree.SearchTree
+ net.minecraft.client.searchtree.SuffixArray
- net.minecraft.client.searchtree.SuffixArray$1
- net.minecraft.client.server.IntegratedPlayerList
+ net.minecraft.client.server.IntegratedServer
- net.minecraft.client.server.LanServer
+ net.minecraft.client.server.LanServerDetection
- net.minecraft.client.server.LanServerDetection$LanServerDetector
+ net.minecraft.client.server.LanServerDetection$LanServerList
- net.minecraft.client.server.LanServerPinger
+ net.minecraft.client.server.package-info
- net.minecraft.client.Session
- net.minecraft.client.skins.package-info
+ net.minecraft.client.sounds.AudioStream
- net.minecraft.client.sounds.ChannelAccess
+ net.minecraft.client.sounds.ChannelAccess$ChannelHandle
- net.minecraft.client.sounds.LoopingAudioStream
+ net.minecraft.client.sounds.LoopingAudioStream$1
- net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
+ net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
- net.minecraft.client.sounds.MusicManager
+ net.minecraft.client.sounds.MusicManager$Music
+ net.minecraft.client.sounds.package-info
- net.minecraft.client.sounds.SoundBufferLibrary
+ net.minecraft.client.sounds.SoundEngine
- net.minecraft.client.sounds.SoundEngineExecutor
+ net.minecraft.client.sounds.SoundEventListener
- net.minecraft.client.sounds.SoundManager
+ net.minecraft.client.sounds.SoundManager$1
- net.minecraft.client.sounds.SoundManager$2
+ net.minecraft.client.sounds.SoundManager$Preparations
- net.minecraft.client.sounds.SoundManager$Preparations$1
+ net.minecraft.client.sounds.WeighedSoundEvents
- net.minecraft.client.sounds.Weighted
+ net.minecraft.client.Timer
- net.minecraft.client.ToggleKeyMapping
- net.minecraft.client.tutorial.CompletedTutorialStepInstance
+ net.minecraft.client.tutorial.CraftPlanksTutorialStep
- net.minecraft.client.tutorial.FindTreeTutorialStepInstance
+ net.minecraft.client.tutorial.MovementTutorialStepInstance
- net.minecraft.client.tutorial.OpenInventoryTutorialStep
+ net.minecraft.client.tutorial.package-info
+ net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
- net.minecraft.client.tutorial.Tutorial
+ net.minecraft.client.tutorial.TutorialStepInstance
- net.minecraft.client.tutorial.TutorialSteps
+ net.minecraft.client.User
- net.minecraft.client.User$Type
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.package-info
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
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
+ net.minecraft.commands.arguments.DimensionTypeArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Serializer
- net.minecraft.commands.arguments.EntitySummonArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
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
- net.minecraft.commands.arguments.ItemEnchantmentArgument
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
- net.minecraft.commands.arguments.MobEffectArgument
+ net.minecraft.commands.arguments.NbtPathArgument
- net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
+ net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
- net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
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
- net.minecraft.commands.arguments.RangeArgument$Floats$Serializer
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.RangeArgument$Ints$Serializer
+ net.minecraft.commands.arguments.RangeArgument$Serializer
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
- net.minecraft.commands.arguments.selector.EntitySelector
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
- net.minecraft.commands.BrigadierExceptions
+ net.minecraft.commands.CommandFunction
- net.minecraft.commands.CommandFunction$CacheableFunction
+ net.minecraft.commands.CommandFunction$CommandEntry
- net.minecraft.commands.CommandFunction$Entry
+ net.minecraft.commands.CommandFunction$FunctionEntry
- net.minecraft.commands.CommandRuntimeException
- net.minecraft.commands.Commands
+ net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
- net.minecraft.commands.exceptions.package-info
+ net.minecraft.commands.package-info
- net.minecraft.commands.SharedSuggestionProvider
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
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
+ net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
- net.minecraft.core.dispenser.BoatDispenseItemBehavior
+ net.minecraft.core.dispenser.DefaultDispenseItemBehavior
- net.minecraft.core.dispenser.DispenseItemBehavior
+ net.minecraft.core.dispenser.DispenseItemBehavior$1
- net.minecraft.core.dispenser.DispenseItemBehavior$10
+ net.minecraft.core.dispenser.DispenseItemBehavior$11
- net.minecraft.core.dispenser.DispenseItemBehavior$12
+ net.minecraft.core.dispenser.DispenseItemBehavior$13
- net.minecraft.core.dispenser.DispenseItemBehavior$14
+ net.minecraft.core.dispenser.DispenseItemBehavior$15
- net.minecraft.core.dispenser.DispenseItemBehavior$16
+ net.minecraft.core.dispenser.DispenseItemBehavior$17
- net.minecraft.core.dispenser.DispenseItemBehavior$18
+ net.minecraft.core.dispenser.DispenseItemBehavior$19
- net.minecraft.core.dispenser.DispenseItemBehavior$2
+ net.minecraft.core.dispenser.DispenseItemBehavior$20
- net.minecraft.core.dispenser.DispenseItemBehavior$21
+ net.minecraft.core.dispenser.DispenseItemBehavior$22
- net.minecraft.core.dispenser.DispenseItemBehavior$3
+ net.minecraft.core.dispenser.DispenseItemBehavior$4
- net.minecraft.core.dispenser.DispenseItemBehavior$5
+ net.minecraft.core.dispenser.DispenseItemBehavior$6
- net.minecraft.core.dispenser.DispenseItemBehavior$7
+ net.minecraft.core.dispenser.DispenseItemBehavior$7$1
- net.minecraft.core.dispenser.DispenseItemBehavior$8
+ net.minecraft.core.dispenser.DispenseItemBehavior$8$1
- net.minecraft.core.dispenser.DispenseItemBehavior$9
+ net.minecraft.core.dispenser.OptionalDispenseItemBehavior
+ net.minecraft.core.dispenser.package-info
- net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
+ net.minecraft.core.GlobalPos
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.LocatableSource
+ net.minecraft.core.Location
- net.minecraft.core.MapFiller
+ net.minecraft.core.MappedRegistry
- net.minecraft.core.NonNullList
- net.minecraft.core.package-info
+ net.minecraft.core.particles.BlockParticleOption
- net.minecraft.core.particles.BlockParticleOption$1
+ net.minecraft.core.particles.DustParticleOptions
- net.minecraft.core.particles.DustParticleOptions$1
+ net.minecraft.core.particles.ItemParticleOption
- net.minecraft.core.particles.ItemParticleOption$1
+ net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.Position
- net.minecraft.core.PositionImpl
+ net.minecraft.core.Registry
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.SerializableBoolean
- net.minecraft.core.SerializableLong
+ net.minecraft.core.SerializableUUID
- net.minecraft.core.Source
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
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
+ net.minecraft.data.models.blockstates.package-info
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
- net.minecraft.data.models.blockstates.PropertyValue
+ net.minecraft.data.models.blockstates.Selector
- net.minecraft.data.models.blockstates.Variant
+ net.minecraft.data.models.blockstates.VariantProperties
- net.minecraft.data.models.blockstates.VariantProperties$Rotation
+ net.minecraft.data.models.blockstates.VariantProperty
- net.minecraft.data.models.blockstates.VariantProperty$Value
+ net.minecraft.data.models.ItemModelGenerators
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
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
- net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BlockTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
- net.minecraft.data.tags.TagsProvider
- net.minecraft.gametest.framework.BeforeBatch
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
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
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.TeamcityTestReporter
+ net.minecraft.gametest.framework.TestClassNameArgument
- net.minecraft.gametest.framework.TestCommand
+ net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
- net.minecraft.gametest.framework.TestFunction
+ net.minecraft.gametest.framework.TestFunctionArgument
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
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
+ net.minecraft.network.chat.BaseComponent
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ClickEvent
- net.minecraft.network.chat.ClickEvent$Action
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$1
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.ContextAwareComponent
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.NbtComponent
- net.minecraft.network.chat.NbtComponent$BlockNbtComponent
+ net.minecraft.network.chat.NbtComponent$EntityNbtComponent
- net.minecraft.network.chat.NbtComponent$StorageNbtComponent
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.ScoreComponent
- net.minecraft.network.chat.SelectorComponent
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.TextComponent
+ net.minecraft.network.chat.TranslatableComponent
- net.minecraft.network.chat.TranslatableFormatException
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
- net.minecraft.network.package-info
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAddGlobalEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddMobPacket
+ net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
- net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
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
+ net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
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
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetSpawnPositionPacket
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
- net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
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
- net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
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
- net.minecraft.network.protocol.game.ServerGamePacketListener
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
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
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
- net.minecraft.network.SkipPacketException
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
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
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
- net.minecraft.resources.package-info
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
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
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$Mode
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
+ net.minecraft.server.commands.ReplaceItemCommand
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
- net.minecraft.server.ConsoleInputSource
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServer$2
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
+ net.minecraft.server.level.DerivedServerLevel
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.FeatureSimulator
+ net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
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
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
+ net.minecraft.server.MinecraftServer$3
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
- net.minecraft.server.packs.AbstractResourcePack
+ net.minecraft.server.packs.FileResourcePack
- net.minecraft.server.packs.FolderResourcePack
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.Pack
- net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
+ net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.repository.UnopenedPack
+ net.minecraft.server.packs.repository.UnopenedPack$Position
- net.minecraft.server.packs.repository.UnopenedPack$UnopenedPackConstructor
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
- net.minecraft.server.packs.VanillaPack
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$2
- net.minecraft.server.players.GameProfileCache$GameProfileInfo
+ net.minecraft.server.players.GameProfileCache$Serializer
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
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
+ net.minecraft.sounds.package-info
- net.minecraft.sounds.SoundEvent
+ net.minecraft.sounds.SoundEvents
- net.minecraft.sounds.SoundSource
- net.minecraft.stats.package-info
- net.minecraft.stats.RecipeBook
+ net.minecraft.stats.ServerRecipeBook
- net.minecraft.stats.ServerStatsCounter
+ net.minecraft.stats.Stat
- net.minecraft.stats.StatFormatter
- net.minecraft.stats.Stats
+ net.minecraft.stats.StatsCounter
+ net.minecraft.stats.StatType
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.BlockTags$Wrapper
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.EntityTypeTags$Wrapper
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.FluidTags$Wrapper
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.ItemTags$Wrapper
- net.minecraft.tags.package-info
+ net.minecraft.tags.SynchronizableTagCollection
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.Tag$ValuesEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$Preparations
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
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
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RenameBiomesFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.OminousBannerRenameFix
- net.minecraft.util.Deserializer
+ net.minecraft.util.FrameTimer
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.InsensitiveStringMap
+ net.minecraft.util.IntRange
- net.minecraft.util.LazyLoadedValue
+ net.minecraft.util.LimitedCapacityList
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.Mth
- net.minecraft.util.ProgressListener
+ net.minecraft.util.RewindableStream
- net.minecraft.util.RewindableStream$1
+ net.minecraft.util.Serializable
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$1
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringUtil
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.Piglin$PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Zombie$1
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
+ net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
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
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.VillagerType$1
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.projectile.AbstractArrow
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
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
+ net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
+ net.minecraft.world.item.ArmorItem
- net.minecraft.world.item.ArmorItem$1
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterials
+ net.minecraft.world.item.ArmorStandItem
- net.minecraft.world.item.ArrowItem
+ net.minecraft.world.item.AxeItem
- net.minecraft.world.item.BannerItem
+ net.minecraft.world.item.BannerPatternItem
- net.minecraft.world.item.BedItem
+ net.minecraft.world.item.BlockItem
- net.minecraft.world.item.BlockPlaceContext
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.CarrotOnAStickItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.ClockItem
+ net.minecraft.world.item.ClockItem$1
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.CompassItem$1
- net.minecraft.world.item.ComplexItem
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
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$10
- net.minecraft.world.item.CreativeModeTab$11
+ net.minecraft.world.item.CreativeModeTab$12
- net.minecraft.world.item.CreativeModeTab$2
+ net.minecraft.world.item.CreativeModeTab$3
- net.minecraft.world.item.CreativeModeTab$4
+ net.minecraft.world.item.CreativeModeTab$5
- net.minecraft.world.item.CreativeModeTab$6
+ net.minecraft.world.item.CreativeModeTab$7
- net.minecraft.world.item.CreativeModeTab$8
+ net.minecraft.world.item.CreativeModeTab$9
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.DebugStickItem
- net.minecraft.world.item.DiggerItem
+ net.minecraft.world.item.DirectionalPlaceContext
- net.minecraft.world.item.DirectionalPlaceContext$1
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
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
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishBucketItem
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$1
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.ItemPropertyFunction
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
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
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
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
- net.minecraft.world.item.UseOnContext
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$3
+ net.minecraft.world.level.block.Block$OffsetType
+ net.minecraft.world.level.block.LogBlock
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
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
- net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState$1
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ChunkTickList
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.CollisionGetter$1
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CustomSpawner
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.LevelConflictException
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelType
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NoiseColumn
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.world.entity.Entity -1M | -1P
```
```
XXX.ai.behavior.AnimalMakeLove +1M -1M | +1P
```
```
XXX.ai.behavior.BehaviorUtils +5M -5M
```
```
XXX.ai.behavior.GoToCelebrateLocation +1M -1M | +1P
```
```
XXX.ai.behavior.GoToWantedItem +2M -2M | +1P
```
```
XXX.ai.behavior.InsideBrownianWalk +1P -1P
```
```
XXX.ai.behavior.LocateHidingPlace +1P -1P
```
```
XXX.ai.behavior.LookAndFollowTradingPlayerSink +1P -1P
```
```
XXX.ai.behavior.MoveToSkySeeingSpot +1P -1P
```
```
XXX.ai.behavior.RandomStroll +1P -1P
```
```
XXX.ai.behavior.SetClosestHomeAsWalkTarget +1P -1P
```
```
XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach +1P -1P
```
```
XXX.ai.behavior.SetWalkTargetFromLookTarget +1P -1P
```
```
XXX.ai.behavior.StrollToPoiList +1P -1P
```
```
XXX.ai.behavior.VillageBoundRandomStroll +1P -1P
```
```
XXX.entity.fishing.FishingHook +3M | +1P
```
```
XXX.level.biome.Biome +3M -3M
```
```
XXX.level.biome.BiomeSpecialEffects +2M -2M | +2P -2P
```
```
XXX.level.biome.BiomeSpecialEffects$Builder +2M -2M | +2P -2P
```
```
XXX.level.block.AbstractBannerBlock +1M -1M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -2M
```
```
XXX.level.block.AbstractSkullBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +4M -4M
```
```
XXX.level.block.BambooBlock +4M -2M
```
```
XXX.level.block.BannerBlock +1M -1M
```
```
XXX.level.block.BarrierBlock +1M -2M
```
```
XXX.level.block.BaseCoralPlantBlock +1M -1M
```
```
XXX.level.block.BaseCoralWallFanBlock +1M -1M
```
```
XXX.level.block.BaseFireBlock +1M -1M
```
```
XXX.level.block.BaseRailBlock +1M -1M
```
```
XXX.level.block.BeaconBlock +1M -2M
```
```
XXX.level.block.Blocks +52M -3M | +2P
```
```
XXX.level.block.BrewingStandBlock +1M -1M
```
```
XXX.level.block.ButtonBlock +2M -2M
```
```
XXX.level.block.CactusBlock +2M -1M
```
```
XXX.level.block.CampfireBlock +1M -2M
```
```
XXX.level.block.CartographyTableBlock +1M -1M
```
```
XXX.level.block.CauldronBlock +1M -1M
```
```
XXX.level.block.ChorusPlantBlock +1M -1M
```
```
XXX.level.block.ComparatorBlock +1M -1M
```
```
XXX.level.block.ConduitBlock +1M -1M
```
```
XXX.level.block.CoralFanBlock +1M -1M
```
```
XXX.level.block.CoralWallFanBlock +1M -1M
```
```
XXX.level.block.CropBlock +3M -2M
```
```
XXX.level.block.DaylightDetectorBlock +1M -1M
```
```
XXX.level.block.DetectorRailBlock +1M -2M
```
```
XXX.level.block.DiodeBlock +1M -1M
```
```
XXX.level.block.DispenserBlock +1M -2M
```
```
XXX.level.block.DragonEggBlock +2M -2M
```
```
XXX.level.block.EnchantmentTableBlock +1M -1M
```
```
XXX.level.block.EndPortalBlock +1M -1M
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
XXX.level.block.FallingBlock +5M -5M
```
```
XXX.level.block.FenceBlock +2M -1M
```
```
XXX.level.block.FletchingTableBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock +1M -1M
```
```
XXX.level.block.FungusBlock +1M -1M
```
```
XXX.level.block.GlassBlock +1M -1M
```
```
XXX.level.block.GoldBlock +1M -1M
```
```
XXX.level.block.GrassPathBlock +1M -2M
```
```
XXX.level.block.GrindstoneBlock +1M -1M
```
```
XXX.level.block.GrowingPlantBlock +1M -1M
```
```
XXX.level.block.GrowingPlantHeadBlock +3M -1M
```
```
XXX.level.block.HayBlock +1M -1M
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.HorizontalDirectionalBlock +1M -1M
```
```
XXX.level.block.IceBlock +2M -3M
```
```
XXX.level.block.IronBarsBlock +2M -1M
```
```
XXX.level.block.JukeboxBlock +1M -1M
```
```
XXX.level.block.KelpPlantBlock +1M -1M
```
```
XXX.level.block.LeavesBlock +1M -3M
```
```
XXX.level.block.LeverBlock +1M -1M
```
```
XXX.level.block.LiquidBlock +2M -2M
```
```
XXX.level.block.RotatedPillarBlock +1M -1M
```
```
XXX.level.block.SandBlock +2M -2M
```
```
XXX.level.block.ScaffoldingBlock +1M -1M
```
```
XXX.level.block.Seagrass +1M -1M
```
```
XXX.level.block.ShulkerBoxBlock +1M -2M
```
```
XXX.level.block.SignBlock +1M -1M
```
```
XXX.level.block.SkullBlock +1M -1M
```
```
XXX.level.block.SmithingTableBlock +1M -1M
```
```
XXX.level.block.SnowLayerBlock +3M -2M
```
```
XXX.level.block.SnowyDirtBlock +1M -1M
```
```
XXX.level.block.SoulSandBlock +3M -6M
```
```
XXX.level.block.SpawnerBlock +1M -1M
```
```
XXX.level.block.SpreadingSnowyDirtBlock +2M -2M
```
```
XXX.level.block.StainedGlassPaneBlock +1M -1M
```
```
XXX.level.block.StemBlock +2M -2M
```
```
XXX.level.block.StoneButtonBlock +1M -1M
```
```
XXX.level.block.StructureBlock +1M -1M
```
```
XXX.level.block.StructureVoidBlock +1M -1M
```
```
XXX.level.block.SweetBerryBushBlock +3M -2M
```
```
XXX.level.block.TallGrassBlock +2M -2M
```
```
XXX.level.block.TargetBlock +1M -1M
```
```
XXX.level.block.TorchBlock +1M -1M
```
```
XXX.level.block.TripWireBlock +1M -1M
```
```
XXX.level.block.TripWireHookBlock +1M -1M
```
```
XXX.level.block.TurtleEggBlock +2M -2M
```
```
XXX.level.block.TwistingVinesPlant +1M -1M
```
```
XXX.level.block.WallBlock +1M -1M
```
```
XXX.level.block.WallSignBlock +1M -1M
```
```
XXX.level.block.WallTorchBlock +1M -1M
```
```
XXX.level.block.WebBlock +1M -1M
```
```
XXX.level.block.WeepingVinesPlant +1M -1M
```
```
XXX.level.block.WetSpongeBlock +1M -1M
```
```
XXX.level.block.WitherSkullBlock +1M -1M
```
```
XXX.level.block.WoodButtonBlock +1M -1M
```
```
XXX.block.piston.MovingPistonBlock +1M -3M
```
```
XXX.state.properties.BlockStateProperties +1P
```
```
XXX.level.chunk.ChunkGenerator +1P
```
```
XXX.level.levelgen.FlatLevelSource +1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +3M
```
```
XXX.levelgen.feature.NetherForestVegetationFeature +1M
```
```
XXX.loot.functions.EnchantRandomlyFunction +3M -1M
```

</details>































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ double getDismountTargetFloorHeight(Level,BlockPos,CollisionContext)
```

</details>























<details>
<summary>
net.minecraft.world.entity.ai.behavior.AnimalMakeLove
</summary>

```diff
- void <init>(EntityType,float)
+ void <init>(EntityType)
```

</details>


<details>
<summary>
net.minecraft.world.entity.ai.behavior.BehaviorUtils
</summary>

```diff
- void lockGazeAndWalkToEachOther(LivingEntity,LivingEntity,float)
+ void lockGazeAndWalkToEachOther(LivingEntity,LivingEntity)
- void setWalkAndLookTargetMemories(LivingEntity,BlockPos,float,int)
+ void setWalkAndLookTargetMemories(LivingEntity,BlockPos,int)
- void setWalkAndLookTargetMemories(LivingEntity,Entity,float,int)
+ void setWalkAndLookTargetMemories(LivingEntity,Entity,int)
- void setWalkAndLookTargetMemories(LivingEntity,PositionWrapper,float,int)
+ void setWalkAndLookTargetMemories(LivingEntity,PositionWrapper,int)
- void setWalkAndLookTargetMemoriesToEachOther(LivingEntity,LivingEntity,float)
+ void setWalkAndLookTargetMemoriesToEachOther(LivingEntity,LivingEntity)
```

</details>








<details>
<summary>
net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
</summary>

```diff
- void <init>(int,float)
+ void <init>(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.GoToWantedItem
</summary>

```diff
- void <init>(float,boolean,int)
+ void <init>(int,boolean)
- void <init>(Predicate,float,boolean,int)
+ void <init>(Predicate,int,boolean)
```

</details>




























































































































































































<details>
<summary>
net.minecraft.world.entity.fishing.FishingHook
</summary>

```diff
- boolean calculateOpenWater(BlockPos)
- boolean isOpenWaterFishing()
- boolean validOpenWaterBlockAt(BlockPos)
```

</details>































































<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
- Optional getAmbientAdditions()
+ Optional getAmbientAdditionsSoundEvent()
- Optional getAmbientLoop()
+ Optional getAmbientLoopSoundEvent()
- Optional getAmbientMood()
+ Optional getAmbientMoodSoundEvent()
```

</details>






<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects
</summary>

```diff
- Optional getAmbientAdditionsSettings()
+ Optional getAmbientAdditionsSoundEvent()
- Optional getAmbientMoodSettings()
+ Optional getAmbientMoodSoundEvent()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
</summary>

```diff
- BiomeSpecialEffects$Builder ambientAdditionsSound(AmbientAdditionsSettings)
+ BiomeSpecialEffects$Builder ambientAdditionsSound(SoundEvent)
- BiomeSpecialEffects$Builder ambientMoodSound(AmbientMoodSettings)
+ BiomeSpecialEffects$Builder ambientMoodSound(SoundEvent)
```

</details>












































<details>
<summary>
net.minecraft.world.level.block.AbstractBannerBlock
</summary>

```diff
+ void <init>(DyeColor,Block$Properties)
- void <init>(DyeColor,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ int getLightEmission(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractSkullBlock
</summary>

```diff
+ void <init>(SkullBlock$Type,Block$Properties)
- void <init>(SkullBlock$Type,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
- int getDustColor(BlockState,BlockGetter,BlockPos)
+ int getDustColor(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void onBroken(Level,BlockPos,FallingBlockEntity)
+ void onBroken(Level,BlockPos)
- void onLand(Level,BlockPos,BlockState,BlockState,FallingBlockEntity)
+ void onLand(Level,BlockPos,BlockState,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooBlock
</summary>

```diff
+ Block$OffsetType getOffsetType()
- BlockBehaviour$OffsetType getOffsetType()
- boolean isRandomlyTicking(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
+ void <init>(DyeColor,Block$Properties)
- void <init>(DyeColor,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BarrierBlock
</summary>

```diff
+ boolean isValidSpawn(BlockState,BlockGetter,BlockPos,EntityType)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralPlantBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralWallFanBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
+ void <init>(Block$Properties,float)
- void <init>(BlockBehaviour$Properties,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
+ void <init>(boolean,Block$Properties)
- void <init>(boolean,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
+ boolean isRedstoneConductor(BlockState,BlockGetter,BlockPos)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
- BedBlock bed(DyeColor)
- Block stem(MaterialColor)
+ BlockEntityType lambda$static$0()
- BlockEntityType lambda$static$11()
- Boolean always(BlockState,BlockGetter,BlockPos,EntityType)
- boolean always(BlockState,BlockGetter,BlockPos)
- boolean lambda$pistonBase$4(BlockState,BlockGetter,BlockPos)
- boolean lambda$static$12(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$27(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$29(BlockState,BlockGetter,BlockPos,EntityType)
- Boolean never(BlockState,BlockGetter,BlockPos,EntityType)
- boolean never(BlockState,BlockGetter,BlockPos)
- Boolean ocelotOrParrot(BlockState,BlockGetter,BlockPos,EntityType)
+ ConfiguredFeature lambda$static$1()
+ ConfiguredFeature lambda$static$2()
- ConfiguredFeature lambda$static$34()
- ConfiguredFeature lambda$static$35()
- int lambda$litBlockEmission$0(int,BlockState)
- int lambda$static$10(BlockState)
- int lambda$static$13(BlockState)
- int lambda$static$14(BlockState)
- int lambda$static$15(BlockState)
- int lambda$static$16(BlockState)
- int lambda$static$17(BlockState)
- int lambda$static$18(BlockState)
- int lambda$static$19(BlockState)
- int lambda$static$20(BlockState)
- int lambda$static$21(BlockState)
- int lambda$static$22(BlockState)
- int lambda$static$23(BlockState)
- int lambda$static$24(BlockState)
- int lambda$static$25(BlockState)
- int lambda$static$26(BlockState)
- int lambda$static$28(BlockState)
- int lambda$static$30(BlockState)
- int lambda$static$31(BlockState)
- int lambda$static$32(BlockState)
- int lambda$static$33(BlockState)
- int lambda$static$36(BlockState)
- int lambda$static$37(BlockState)
- int lambda$static$38(BlockState)
- int lambda$static$5(BlockState)
- int lambda$static$6(BlockState)
- int lambda$static$7(BlockState)
- int lambda$static$8(BlockState)
- int lambda$static$9(BlockState)
- LeavesBlock leaves()
- MaterialColor lambda$bed$1(DyeColor,BlockState)
- MaterialColor lambda$log$2(MaterialColor,MaterialColor,BlockState)
- MaterialColor lambda$stem$3(MaterialColor,BlockState)
- PistonBaseBlock pistonBase(boolean)
- RotatedPillarBlock log(MaterialColor,MaterialColor)
- ShulkerBoxBlock shulkerBox(DyeColor,BlockBehaviour$Properties)
- StainedGlassBlock stainedGlass(DyeColor)
- ToIntFunction litBlockEmission(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
- int getPressDuration()
+ int getTickDelay(LevelReader)
+ void <init>(boolean,Block$Properties)
- void <init>(boolean,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CactusBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
+ int getLightEmission(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CartographyTableBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CauldronBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.ComparatorBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ConduitBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CoralFanBlock
</summary>

```diff
+ void <init>(Block,Block$Properties)
- void <init>(Block,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CoralWallFanBlock
</summary>

```diff
+ void <init>(Block,Block$Properties)
- void <init>(Block,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CropBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.DaylightDetectorBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DetectorRailBlock
</summary>

```diff
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DiodeBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.DragonEggBlock
</summary>

```diff
- int getDelayAfterPlace()
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnchantmentTableBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndPortalBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FallingBlock
</summary>

```diff
- int getDelayAfterPlace()
- int getDustColor(BlockState,BlockGetter,BlockPos)
+ int getDustColor(BlockState)
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void onBroken(Level,BlockPos,FallingBlockEntity)
+ void onBroken(Level,BlockPos)
- void onLand(Level,BlockPos,BlockState,BlockState,FallingBlockEntity)
+ void onLand(Level,BlockPos,BlockState,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- VoxelShape getVisualShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.FletchingTableBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
+ void <init>(Block,Block$Properties)
- void <init>(Block,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FungusBlock
</summary>

```diff
+ void <init>(Block$Properties,Supplier)
- void <init>(BlockBehaviour$Properties,Supplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GlassBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GoldBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrassPathBlock
</summary>

```diff
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrindstoneBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBlock
</summary>

```diff
+ void <init>(Block$Properties,Direction,VoxelShape,boolean)
- void <init>(BlockBehaviour$Properties,Direction,VoxelShape,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrowingPlantHeadBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
+ void <init>(Block$Properties,Direction,VoxelShape,boolean,double)
- void <init>(BlockBehaviour$Properties,Direction,VoxelShape,boolean,double)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HayBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HorizontalDirectionalBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.IceBlock
</summary>

```diff
+ boolean isValidSpawn(BlockState,BlockGetter,BlockPos,EntityType)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.IronBarsBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- VoxelShape getVisualShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JukeboxBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpPlantBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.LeavesBlock
</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ boolean isValidSpawn(BlockState,BlockGetter,BlockPos,EntityType)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LiquidBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
+ int getTickDelay(LevelReader)
+ void <init>(FlowingFluid,Block$Properties)
- void <init>(FlowingFluid,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RotatedPillarBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SandBlock
</summary>

```diff
- int getDustColor(BlockState,BlockGetter,BlockPos)
+ int getDustColor(BlockState)
+ void <init>(int,Block$Properties)
- void <init>(int,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ScaffoldingBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Seagrass
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ void <init>(DyeColor,Block$Properties)
- void <init>(DyeColor,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SignBlock
</summary>

```diff
+ void <init>(Block$Properties,WoodType)
- void <init>(BlockBehaviour$Properties,WoodType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SkullBlock
</summary>

```diff
+ void <init>(SkullBlock$Type,Block$Properties)
- void <init>(SkullBlock$Type,BlockBehaviour$Properties)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.SmithingTableBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SnowLayerBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
- VoxelShape getVisualShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SnowyDirtBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SoulSandBlock
</summary>

```diff
- BlockState updateShape(BlockState,Direction,BlockState,LevelAccessor,BlockPos,BlockPos)
+ boolean isRedstoneConductor(BlockState,BlockGetter,BlockPos)
+ boolean isValidSpawn(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
+ int getTickDelay(LevelReader)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- VoxelShape getVisualShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SpawnerBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SpreadingSnowyDirtBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StainedGlassPaneBlock
</summary>

```diff
+ void <init>(DyeColor,Block$Properties)
- void <init>(DyeColor,BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.StemBlock
</summary>

```diff
+ void <init>(StemGrownBlock,Block$Properties)
- void <init>(StemGrownBlock,BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StoneButtonBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StructureVoidBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SweetBerryBushBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TallGrassBlock
</summary>

```diff
+ Block$OffsetType getOffsetType()
- BlockBehaviour$OffsetType getOffsetType()
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TargetBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TorchBlock
</summary>

```diff
+ void <init>(Block$Properties,ParticleOptions)
- void <init>(BlockBehaviour$Properties,ParticleOptions)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.TripWireBlock
</summary>

```diff
+ void <init>(TripWireHookBlock,Block$Properties)
- void <init>(TripWireHookBlock,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TripWireHookBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TurtleEggBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
- void randomTick(BlockState,ServerLevel,BlockPos,Random)
+ void tick(BlockState,ServerLevel,BlockPos,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TwistingVinesPlant
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.WallBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WallSignBlock
</summary>

```diff
+ void <init>(Block$Properties,WoodType)
- void <init>(BlockBehaviour$Properties,WoodType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WallTorchBlock
</summary>

```diff
+ void <init>(Block$Properties,ParticleOptions)
- void <init>(BlockBehaviour$Properties,ParticleOptions)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WebBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WeepingVinesPlant
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WetSpongeBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WitherSkullBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WoodButtonBlock
</summary>

```diff
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>



































<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ boolean isRedstoneConductor(BlockState,BlockGetter,BlockPos)
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ void <init>(Block$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>





































































<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
- BlockGetter getBaseColumn(int,int)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
- BlockGetter getBaseColumn(int,int)
- BlockState generateBaseState(double,int)
- int iterateNoiseColumn(int,int,BlockState[],Predicate)
```

</details>






































<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
</summary>

```diff
- boolean place(LevelAccessor,Random,BlockPos,BlockPileConfiguration,int,int)
```

</details>











































































































































































































































































































<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
</summary>

```diff
- boolean lambda$run$0(boolean,ItemStack,Enchantment)
- ItemStack enchantItem(ItemStack,Enchantment,Random)
+ LootItemFunction lambda$randomApplicableEnchantment$0(LootItemCondition[])
- LootItemFunction lambda$randomApplicableEnchantment$1(LootItemCondition[])
```

</details>
</details>