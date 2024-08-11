## Comparison with [21w18a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w18a)

- [Version data](#version-data)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Misc](#misc)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">21w18a</th><th>21w19a</th></tr><tr><td>World version</td><td><code>2713</code></td><td><code>2714</code></td></tr><tr><td>Protocol version</td><td><code>1073741850</code></td><td><code>1073741851</code></td></tr></table>
</details>
<details><summary>Commands</summary>
<details>
<summary>
item
</summary>

```diff
- item block <pos: block_pos> <slot: item_slot> copy block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
- item block <pos: block_pos> <slot: item_slot> copy entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
- item block <pos: block_pos> <slot: item_slot> modify <modifier: resource_location>
- item block <pos: block_pos> <slot: item_slot> replace <item: item_stack> <count: integer>
- item entity <targets: entity> <slot: item_slot> copy block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
- item entity <targets: entity> <slot: item_slot> copy entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
- item entity <targets: entity> <slot: item_slot> modify <modifier: resource_location>
- item entity <targets: entity> <slot: item_slot> replace <item: item_stack> <count: integer>
+ item modify block <pos: block_pos> <slot: item_slot> <modifier: resource_location>
+ item modify entity <targets: entity> <slot: item_slot> <modifier: resource_location>
+ item replace block <pos: block_pos> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace block <pos: block_pos> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace block <pos: block_pos> <slot: item_slot> with <item: item_stack> <count: integer>
+ item replace entity <targets: entity> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace entity <targets: entity> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace entity <targets: entity> <slot: item_slot> with <item: item_stack> <count: integer>
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
- black_candle.json
- blue_candle.json
- brown_candle.json
- bundle.json
- candle.json
- cyan_candle.json
- gray_candle.json
- green_candle.json
- light_blue_candle.json
- light_gray_candle.json
- lime_candle.json
- magenta_candle.json
- orange_candle.json
- pink_candle.json
- purple_candle.json
- red_candle.json
- white_candle.json
- yellow_candle.json
```

</details>



























































































































































































<details>
<summary>
copper_ingot.json
</summary>

```
Group: none -> copper_ingot
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ disconnect.unknownHost: Unknown host
```

</details>
<details>
<summary>
Changes
</summary>

```
block.minecraft.white_candle_cake: Cake with White Candle Cake
block.minecraft.orange_candle_cake: Cake with Orange Candle Cake
block.minecraft.magenta_candle_cake: Cake with Magenta Candle Cake
block.minecraft.light_blue_candle_cake: Cake with Light Blue Candle Cake
block.minecraft.yellow_candle_cake: Cake with Yellow Candle Cake
block.minecraft.lime_candle_cake: Cake with Lime Candle Cake
block.minecraft.pink_candle_cake: Cake with Pink Candle Cake
block.minecraft.gray_candle_cake: Cake with Gray Candle Cake
block.minecraft.light_gray_candle_cake: Cake with Light Gray Candle Cake
block.minecraft.cyan_candle_cake: Cake with Cyan Candle Cake
block.minecraft.purple_candle_cake: Cake with Purple Candle Cake
block.minecraft.blue_candle_cake: Cake with Blue Candle Cake
block.minecraft.brown_candle_cake: Cake with Brown Candle Cake
block.minecraft.green_candle_cake: Cake with Green Candle Cake
block.minecraft.red_candle_cake: Cake with Red Candle Cake
block.minecraft.black_candle_cake: Cake with Black Candle Cake
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
- minecraft/advancements/recipes/decorations/black_candle.json
- minecraft/advancements/recipes/decorations/blue_candle.json
- minecraft/advancements/recipes/decorations/brown_candle.json
- minecraft/advancements/recipes/decorations/candle.json
- minecraft/advancements/recipes/decorations/cyan_candle.json
- minecraft/advancements/recipes/decorations/gray_candle.json
- minecraft/advancements/recipes/decorations/green_candle.json
- minecraft/advancements/recipes/decorations/light_blue_candle.json
- minecraft/advancements/recipes/decorations/light_gray_candle.json
- minecraft/advancements/recipes/decorations/lime_candle.json
- minecraft/advancements/recipes/decorations/magenta_candle.json
- minecraft/advancements/recipes/decorations/orange_candle.json
- minecraft/advancements/recipes/decorations/pink_candle.json
- minecraft/advancements/recipes/decorations/purple_candle.json
- minecraft/advancements/recipes/decorations/red_candle.json
- minecraft/advancements/recipes/decorations/white_candle.json
- minecraft/advancements/recipes/decorations/yellow_candle.json
- minecraft/advancements/recipes/tools/bundle.json
- minecraft/recipes/black_candle.json
- minecraft/recipes/blue_candle.json
- minecraft/recipes/brown_candle.json
- minecraft/recipes/bundle.json
- minecraft/recipes/candle.json
- minecraft/recipes/cyan_candle.json
- minecraft/recipes/gray_candle.json
- minecraft/recipes/green_candle.json
- minecraft/recipes/light_blue_candle.json
- minecraft/recipes/light_gray_candle.json
- minecraft/recipes/lime_candle.json
- minecraft/recipes/magenta_candle.json
- minecraft/recipes/orange_candle.json
- minecraft/recipes/pink_candle.json
- minecraft/recipes/purple_candle.json
- minecraft/recipes/red_candle.json
- minecraft/recipes/white_candle.json
- minecraft/recipes/yellow_candle.json
+ minecraft/tags/blocks/mineable/axe.json
+ minecraft/tags/blocks/mineable/hoe.json
+ minecraft/tags/blocks/mineable/pickaxe.json
+ minecraft/tags/blocks/mineable/shovel.json
+ minecraft/tags/blocks/needs_diamond_tool.json
+ minecraft/tags/blocks/needs_iron_tool.json
+ minecraft/tags/blocks/needs_stone_tool.json
```

</details>
</details>
<details><summary>Misc</summary>
<details>
<summary>
splashes
</summary>

```diff
+ Now Java 16!
- Now Java 8!
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
+ net.minecraft.advancements.Advancement$1
- net.minecraft.advancements.Advancement$Builder
+ net.minecraft.advancements.AdvancementList
- net.minecraft.advancements.AdvancementList$Listener
+ net.minecraft.advancements.AdvancementProgress
- net.minecraft.advancements.AdvancementProgress$Serializer
+ net.minecraft.advancements.AdvancementRewards
- net.minecraft.advancements.AdvancementRewards$Builder
+ net.minecraft.advancements.critereon.AbstractCriterionTriggerInstance
- net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
+ net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.BlockPredicate
+ net.minecraft.advancements.critereon.BlockPredicate$Builder
- net.minecraft.advancements.critereon.BredAnimalsTrigger
+ net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
- net.minecraft.advancements.critereon.BrewedPotionTrigger
+ net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ChangeDimensionTrigger
+ net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ChanneledLightningTrigger
+ net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ConstructBeaconTrigger
+ net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ConsumeItemTrigger
+ net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.DamagePredicate
+ net.minecraft.advancements.critereon.DamagePredicate$Builder
- net.minecraft.advancements.critereon.DamageSourcePredicate
+ net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
- net.minecraft.advancements.critereon.DeserializationContext
+ net.minecraft.advancements.critereon.DistancePredicate
- net.minecraft.advancements.critereon.EffectsChangedTrigger
+ net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantedItemTrigger
+ net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantmentPredicate
+ net.minecraft.advancements.critereon.EnterBlockTrigger
- net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityEquipmentPredicate
- net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
+ net.minecraft.advancements.critereon.EntityFlagsPredicate
- net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
+ net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
- net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityPredicate
+ net.minecraft.advancements.critereon.LightPredicate$1
- net.minecraft.advancements.critereon.LightPredicate$Builder
+ net.minecraft.advancements.critereon.LocationPredicate
- net.minecraft.advancements.critereon.LocationPredicate$Builder
+ net.minecraft.advancements.critereon.LocationTrigger
- net.minecraft.advancements.critereon.LocationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LootTableTrigger
- net.minecraft.advancements.critereon.LootTableTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.MinMaxBounds
- net.minecraft.advancements.critereon.MinMaxBounds$BoundsFactory
+ net.minecraft.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- net.minecraft.advancements.critereon.MinMaxBounds$Floats
+ net.minecraft.advancements.critereon.MinMaxBounds$Ints
- net.minecraft.advancements.critereon.MobEffectsPredicate
+ net.minecraft.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- net.minecraft.advancements.critereon.NbtPredicate
+ net.minecraft.advancements.critereon.NetherTravelTrigger
- net.minecraft.advancements.critereon.NetherTravelTrigger$TriggerInstance
- net.minecraft.advancements.critereon.package-info
+ net.minecraft.advancements.critereon.PlacedBlockTrigger
- net.minecraft.advancements.critereon.PlacedBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.PlayerInteractTrigger
- net.minecraft.advancements.critereon.PlayerInteractTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.PlayerPredicate
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
+ net.minecraft.advancements.CriteriaTriggers
- net.minecraft.advancements.Criterion
+ net.minecraft.advancements.CriterionProgress
- net.minecraft.advancements.CriterionTrigger
+ net.minecraft.advancements.CriterionTrigger$Listener
- net.minecraft.advancements.CriterionTriggerInstance
+ net.minecraft.advancements.DisplayInfo
- net.minecraft.advancements.FrameType
+ net.minecraft.advancements.package-info
+ net.minecraft.advancements.RequirementsStrategy
- net.minecraft.advancements.TreeNodePosition
+ net.minecraft.commands.arguments.AngleArgument
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
- net.minecraft.commands.arguments.package-info
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
+ net.minecraft.commands.arguments.selector.EntitySelectorParser
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
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
- net.minecraft.core.cauldron.CauldronInteraction
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
- net.minecraft.core.dispenser.DispenseItemBehavior$23
+ net.minecraft.core.dispenser.DispenseItemBehavior$24
- net.minecraft.core.dispenser.DispenseItemBehavior$25
+ net.minecraft.core.dispenser.DispenseItemBehavior$26
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
- net.minecraft.core.dispenser.package-info
- net.minecraft.core.dispenser.ShearsDispenseItemBehavior
+ net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.FrontAndTop
+ net.minecraft.core.GlobalPos
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.MappedRegistry$RegistryEntry
- net.minecraft.core.NonNullList
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
- net.minecraft.core.particles.DustColorTransitionOptions
+ net.minecraft.core.particles.DustColorTransitionOptions$1
- net.minecraft.core.particles.DustParticleOptions
+ net.minecraft.core.particles.DustParticleOptions$1
- net.minecraft.core.particles.DustParticleOptionsBase
+ net.minecraft.core.particles.ItemParticleOption
- net.minecraft.core.particles.ItemParticleOption$1
+ net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleGroup
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.particles.VibrationParticleOption$1
+ net.minecraft.core.Position
- net.minecraft.core.PositionImpl
+ net.minecraft.core.QuartPos
- net.minecraft.core.Registry
+ net.minecraft.core.RegistryAccess
- net.minecraft.core.RegistryAccess$RegistryData
+ net.minecraft.core.RegistryAccess$RegistryHolder
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.SerializableUUID
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
- net.minecraft.data.BlockFamilies
+ net.minecraft.data.BlockFamily
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$1
+ net.minecraft.data.models.blockstates.package-info
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
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.package-info
- net.minecraft.data.package-info
+ net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.RecipeBuilder
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
+ net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.network.chat.BaseComponent
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.ContextAwareComponent
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.NbtComponent
+ net.minecraft.network.chat.NbtComponent$BlockNbtComponent
- net.minecraft.network.chat.NbtComponent$EntityNbtComponent
+ net.minecraft.network.chat.NbtComponent$StorageNbtComponent
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.ScoreComponent
+ net.minecraft.network.chat.SelectorComponent
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.SubStringSource
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.TextComponent
- net.minecraft.network.chat.TranslatableComponent
+ net.minecraft.network.chat.TranslatableFormatException
+ net.minecraft.network.ConnectionProtocol$1
- net.minecraft.network.ConnectionProtocol$PacketSet
+ net.minecraft.network.ConnectionProtocol$ProtocolBuilder
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.package-info
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAddMobPacket
+ net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
- net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
+ net.minecraft.network.protocol.game.ClientboundAddVibrationSignalPacket
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChatPacket
+ net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundPingPacket
+ net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
- net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
+ net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.game.package-info
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
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
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
+ net.minecraft.network.SkipPacketException
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
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.RegistryDataPackCodec
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryLookupCodec
- net.minecraft.resources.RegistryReadOps
+ net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.server.ChainedJsonException$Entry
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
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.package-info
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
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.Eula
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
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
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
+ net.minecraft.server.packs.resources.package-info
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
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
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
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$1
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
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
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
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
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
+ net.minecraft.util.datafix.schemas.package-info
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
+ net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
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
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.ExtraCodecs
- net.minecraft.util.ExtraCodecs$XorCodec
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FormattedCharSequence
- net.minecraft.util.FormattedCharSink
+ net.minecraft.util.FrameTimer
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HeapDumper
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
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
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.valueproviders.BiasedToBottomInt
- net.minecraft.util.valueproviders.ClampedInt
+ net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
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
- net.minecraft.world.damagesource.BadRespawnPointDamage
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.EntityDamageSource
- net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
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
+ net.minecraft.world.entity.ai.behavior.AnimalPanic
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
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
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
- net.minecraft.world.entity.ai.behavior.TryFindWater
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
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
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
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.goat.Goat
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
- net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
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
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.boss.enderdragon.EndCrystal
+ net.minecraft.world.entity.boss.enderdragon.EnderDragon
- net.minecraft.world.entity.boss.enderdragon.package-info
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
+ net.minecraft.world.entity.boss.enderdragon.phases.package-info
+ net.minecraft.world.entity.boss.EnderDragonPart
- net.minecraft.world.entity.boss.package-info
+ net.minecraft.world.entity.boss.wither.package-info
+ net.minecraft.world.entity.boss.wither.WitherBoss
- net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
- net.minecraft.world.entity.decoration.ArmorStand
+ net.minecraft.world.entity.decoration.ArmorStand$1
- net.minecraft.world.entity.decoration.GlowItemFrame
+ net.minecraft.world.entity.decoration.HangingEntity
- net.minecraft.world.entity.decoration.HangingEntity$1
+ net.minecraft.world.entity.decoration.ItemFrame
- net.minecraft.world.entity.decoration.ItemFrame$1
+ net.minecraft.world.entity.decoration.ItemFrame$2
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
+ net.minecraft.world.entity.decoration.Motive
+ net.minecraft.world.entity.decoration.package-info
- net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
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
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.item.FallingBlockEntity
+ net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.Marker
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.CaveSpider
- net.minecraft.world.entity.monster.Creeper
+ net.minecraft.world.entity.monster.CrossbowAttackMob
- net.minecraft.world.entity.monster.Drowned
+ net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
- net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
+ net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
- net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
+ net.minecraft.world.entity.monster.ElderGuardian
- net.minecraft.world.entity.monster.EnderMan
+ net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
+ net.minecraft.world.entity.monster.Endermite
- net.minecraft.world.entity.monster.Enemy
+ net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Illusioner$1
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
+ net.minecraft.world.entity.monster.Phantom$1
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
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.Ravager$RavagerNavigation
+ net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
- net.minecraft.world.entity.monster.Shulker
+ net.minecraft.world.entity.monster.Shulker$1
+ net.minecraft.world.entity.monster.Strider$1
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
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
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
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
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
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
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
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
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
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
+ net.minecraft.world.item.ItemCooldowns$1
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlayerHeadItem
- net.minecraft.world.item.PotionItem
+ net.minecraft.world.item.ProjectileWeaponItem
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
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.MobSpawnSettings$1
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
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
- net.minecraft.world.level.block.grower.AzaleaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.package-info
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
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$1
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.border.package-info
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
+ net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.ChunkTickList$ScheduledTick
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.CollisionSpliterator
+ net.minecraft.world.level.ColorResolver
- net.minecraft.world.level.CommonLevelAccessor
+ net.minecraft.world.level.CustomSpawner
- net.minecraft.world.level.DataPackConfig
+ net.minecraft.world.level.EmptyBlockGetter
- net.minecraft.world.level.EmptyTickList
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$1
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager
+ net.minecraft.world.level.entity.TransientEntitySectionManager$1
+ net.minecraft.world.level.EntityBasedExplosionDamageCalculator
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.ExplosionDamageCalculator
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.GameRules
+ net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NoiseEffect
- net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.RootSystemFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SmallDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$1
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
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
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
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
+ net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
+ net.minecraft.world.level.levelgen.heightproviders.HeightProvider
- net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.package-info
+ net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
- net.minecraft.world.level.levelgen.heightproviders.UniformHeight
+ net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.CaveDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.CaveSurface
- net.minecraft.world.level.levelgen.placement.CaveSurfaceDecorator
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
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.HeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
- net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
- net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.RangeDecorator
- net.minecraft.world.level.levelgen.placement.RepeatingDecorator
+ net.minecraft.world.level.levelgen.placement.Spread32Decorator
- net.minecraft.world.level.levelgen.placement.SquareDecorator
+ net.minecraft.world.level.levelgen.placement.VerticalDecorator
- net.minecraft.world.level.levelgen.placement.WaterDepthThresholdConfiguration
+ net.minecraft.world.level.levelgen.placement.WaterDepthThresholdDecorator
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
+ net.minecraft.world.level.levelgen.structure.package-info
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
- net.minecraft.world.level.levelgen.synth.BlendedNoise
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NoiseUtils
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
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.SavedData
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
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$1
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootItem$1
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$1
- net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
- net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$1
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$1
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$1
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$1
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.IntRange$Serializer
- net.minecraft.world.level.storage.loot.ItemModifierManager
+ net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$1
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.PredicateManager$1
- net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$1
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$1
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$1
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$1
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$InlineSerializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$1
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$1
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
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
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
XXX.mojang.math.SymmetricGroup3 +2M -1M
```
```
net.minecraft.ChatFormatting +1M
```
```
net.minecraft.Util +3M -4M
```
```
net.minecraft.Util$OS +1M -1M
```
```
XXX.advancements.critereon.FilledBucketTrigger -1M
```
```
XXX.advancements.critereon.RecipeUnlockedTrigger -1M
```
```
XXX.advancements.critereon.SlideDownBlockTrigger -1M
```
```
XXX.advancements.critereon.StatePropertiesPredicate -1M
```
```
XXX.commands.arguments.AngleArgument$SingleAngle -1M
```
```
XXX.commands.arguments.EntityAnchorArgument$Anchor +1M -1M
```
```
XXX.commands.arguments.NbtPathArgument -1M
```
```
XXX.commands.arguments.ScoreHolderArgument +1M -2M
```
```
XXX.arguments.blocks.BlockPredicateArgument +1M -1M
```
```
XXX.selector.options.EntitySelectorOptions$Option -1M
```
```
XXX.data.models.BlockModelGenerators +40M -66M
```
```
XXX.models.blockstates.MultiPartGenerator$Entry -1M
```
```
XXX.data.tags.TagsProvider$TagAppender -1M
```
```
XXX.gametest.framework.GameTestBatchRunner +1M -3M
```
```
XXX.gametest.framework.GameTestSequence -1M
```
```
XXX.gametest.framework.TestCommand -1M
```
```
XXX.minecraft.nbt.ListTag -1M
```
```
XXX.minecraft.nbt.LongTag -1M
```
```
XXX.minecraft.nbt.NbtOps +1M -1M
```
```
XXX.minecraft.network.Connection$PacketHolder -2M
```
```
XXX.protocol.game.ClientboundCommandsPacket$Entry -2M
```
```
XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument +1M
```
```
XXX.protocol.game.ClientboundRecipePacket$State +1M
```
```
XXX.protocol.game.ClientboundUpdateAttributesPacket +2M -2M
```
```
XXX.protocol.game.DebugPackets +1M -1M
```
```
XXX.protocol.game.ServerboundInteractPacket -1M
```
```
XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction -2M
```
```
XXX.minecraft.server.ServerFunctionManager$QueuedCommand -1M
```
```
XXX.server.commands.DebugCommand$Tracer -1M
```
```
XXX.server.commands.EmoteCommands +2M -2M
```
```
XXX.server.commands.ExecuteCommand +20M -20M
```
```
XXX.server.commands.ExperienceCommand$Type +1M -1M
```
```
XXX.server.commands.FillCommand$Mode +1M
```
```
XXX.server.commands.GameRuleCommand -2M
```
```
XXX.server.commands.LootCommand +10M -10M
```
```
XXX.server.commands.SeedCommand +1M -1M
```
```
XXX.server.dedicated.Settings$MutableValue -1M
```
```
XXX.server.gui.MinecraftServerGui -2M
```
```
XXX.server.level.ChunkHolder$FullChunkStatus +1M
```
```
XXX.server.level.ChunkTaskPriorityQueue +1M -1M
```
```
XXX.server.level.ServerChunkCache$MainThreadExecutor -1M
```
```
XXX.server.level.ServerLevel +2M -6M
```
```
XXX.server.network.TextFilterClient$RequestFailedException -1M
```
```
XXX.packs.repository.Pack$Position +1M
```
```
XXX.minecraft.tags.StaticTagHelper$Wrapper -1M
```
```
XXX.minecraft.tags.Tag +2M -2M
```
```
XXX.minecraft.tags.TagManager$LoaderInfo -2M
```
```
XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory -1M
```
```
XXX.minecraft.util.SortedArraySet -3M
```
```
XXX.util.profiling.ActiveProfiler$PathEntry -5M
```
```
XXX.profiling.registry.MeasurementCategory +1M
```
```
XXX.ai.behavior.GateBehavior$RunningPolicy +1M -1M
```
```
XXX.ai.behavior.PoiCompetitorScan +1M -1M
```
```
XXX.ai.behavior.PrepareRamNearestTarget +1M -1M
```
```
XXX.ai.behavior.ShufflingList -1M
```
```
XXX.ai.sensing.NearestVisibleLivingEntitySensor +1M -1M
```
```
XXX.ai.targeting.TargetingConditions +4M -5M | +2P -4P
```
```
XXX.ai.util.HoverRandomPos +1M -1M
```
```
XXX.village.poi.PoiRecord +3M -3M
```
```
XXX.entity.animal.Bee +23M -43M
```
```
XXX.entity.animal.Bee$BaseBeeGoal -1M
```
```
XXX.entity.animal.Bee$BeeGoToHiveGoal -4M
```
```
XXX.entity.animal.Bee$BeeGrowCropGoal -1M
```
```
XXX.entity.animal.Bee$BeeLocateHiveGoal +1M -3M
```
```
XXX.entity.animal.Bee$BeePollinateGoal -2M
```
```
XXX.entity.animal.Dolphin +1M -2M
```
```
XXX.entity.animal.Ocelot -1M
```
```
XXX.entity.animal.Panda$Gene +1M -1M
```
```
XXX.entity.animal.Parrot -1M
```
```
XXX.entity.animal.Pufferfish -3M | +1P -1P
```
```
XXX.entity.animal.Rabbit -2M
```
```
XXX.entity.animal.Squid +2M -1M
```
```
XXX.entity.animal.TropicalFish$Pattern +1M
```
```
XXX.entity.animal.Turtle +2M -13M
```
```
XXX.animal.goat.Goat$GoatNodeEvaluator -1M
```
```
XXX.entity.monster.Evoker$EvokerAttackSpellGoal -1M
```
```
XXX.entity.monster.Evoker$EvokerSummonSpellGoal -1M
```
```
XXX.entity.monster.Guardian -2M
```
```
XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal -1M
```
```
XXX.entity.monster.Ravager +1M -1M
```
```
XXX.entity.monster.Slime +1M -2M
```
```
XXX.entity.monster.SpellcasterIllager +1M -1M
```
```
XXX.world.inventory.ClickAction +1M
```
```
XXX.world.inventory.GrindstoneMenu -1M
```
```
XXX.world.inventory.RecipeBookType +1M
```
```
XXX.world.item.ArmorMaterials +1M
```
```
XXX.world.item.DiggerItem +2M -1M | +1P -1P
```
```
XXX.world.item.HoeItem -1P
```
```
XXX.world.item.Item$Properties -7M
```
```
XXX.item.crafting.Ingredient$ItemValue -1M
```
```
XXX.item.crafting.RecipeManager +1M -1M
```
```
XXX.item.crafting.UpgradeRecipe -3M
```
```
XXX.item.enchantment.EnchantmentCategory +1M -1M
```
```
XXX.item.enchantment.ProtectionEnchantment$Type +1M
```
```
XXX.world.level.GameRules$Category +1M
```
```
XXX.world.level.GameRules$IntegerValue -1M
```
```
XXX.world.level.GameRules$Type -2M
```
```
XXX.world.level.LightLayer +1M
```
```
XXX.world.level.NaturalSpawner$SpawnState -4M
```
```
XXX.world.level.StructureFeatureManager +1M -1M
```
```
XXX.level.biome.AmbientMoodSettings +4M -4M
```
```
XXX.level.biome.Biome +14M -16M
```
```
XXX.level.biome.Biome$ClimateParameters +5M -5M
```
```
XXX.level.biome.Biome$Precipitation +1M
```
```
XXX.level.biome.BiomeGenerationSettings +4M -5M
```
```
XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer +1M
```
```
XXX.level.biome.MultiNoiseBiomeSource$PresetInstance +3M -4M
```
```
XXX.level.biome.OverworldBiomeSource +5M -5M
```
```
XXX.level.block.ComposterBlock -2M
```
```
XXX.level.block.DoubleBlockCombiner$BlockType +1M
```
```
XXX.level.block.LightBlock +1P
```
```
XXX.level.block.PowderSnowBlock -1M | +1P -1P
```
```
XXX.level.block.PressurePlateBlock$Sensitivity +1M
```
```
XXX.block.entity.BannerPattern +1M -1M
```
```
XXX.block.entity.BarrelBlockEntity -2M
```
```
XXX.state.properties.RailShape +1M
```
```
XXX.state.properties.SculkSensorPhase +1M
```
```
XXX.state.properties.StairsShape +1M
```
```
XXX.state.properties.Tilt +1M
```
```
XXX.level.border.BorderStatus +1M
```
```
XXX.chunk.storage.IOWorker$PendingStore -3M
```
```
XXX.chunk.storage.RegionFile -1M
```
```
XXX.chunk.storage.SectionStorage +1M -1M
```
```
XXX.level.entity.Visibility +1M
```
```
XXX.level.gameevent.BlockPositionSource +1M -2M
```
```
XXX.level.gameevent.EntityPositionSource +1M -2M
```
```
XXX.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus -2M
```
```
XXX.level.levelgen.Cavifier$QuantizedSpaghettiRarity -2M
```
```
XXX.level.levelgen.Column$Line -1M
```
```
XXX.level.levelgen.GenerationStep$Carving +1M
```
```
XXX.level.levelgen.GeodeBlockSettings +6M -6M
```
```
XXX.level.levelgen.GeodeLayerSettings +4M -4M
```
```
XXX.level.levelgen.Heightmap$Types +1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +3M -8M
```
```
XXX.level.levelgen.WorldGenSettings +1M -1M
```
```
XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration +6M -6M
```
```
XXX.levelgen.carver.CarverConfiguration +6M -6M
```
```
XXX.levelgen.feature.FossilFeatureConfiguration +5M -5M
```
```
XXX.levelgen.feature.HugeFungusConfiguration +5M -5M
```
```
XXX.levelgen.feature.JigsawFeature -3M
```
```
XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader -1M
```
```
XXX.levelgen.feature.WeightedConfiguredFeature +2M -2M
```
```
XXX.feature.configurations.DiskConfiguration +4M -4M
```
```
XXX.feature.configurations.EndGatewayConfiguration +2M -2M
```
```
XXX.feature.configurations.GeodeConfiguration +13M -13M
```
```
XXX.feature.configurations.GrowingPlantConfiguration +5M -5M
```
```
XXX.feature.configurations.HugeMushroomFeatureConfiguration +3M -3M
```
```
XXX.feature.configurations.LargeDripstoneConfiguration +9M -9M
```
```
XXX.feature.configurations.MineshaftConfiguration +2M -2M
```
```
XXX.feature.configurations.OceanRuinConfiguration +3M -3M
```
```
XXX.feature.configurations.ReplaceBlockConfiguration +1M -1M
```
```
XXX.feature.configurations.RootSystemConfiguration +12M -12M
```
```
XXX.feature.configurations.SpikeConfiguration +3M -3M
```
```
XXX.feature.configurations.TreeConfiguration +9M -9M
```
```
XXX.feature.configurations.UnderwaterMagmaConfiguration +3M -3M
```
```
XXX.feature.featuresize.TwoLayersFeatureSize +3M -3M
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +1M -1M
```
```
XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector -1M
```
```
XXX.levelgen.structure.MineShaftPieces -2M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition -6M
```
```
XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement +1M
```
```
XXX.levelgen.structure.ShipwreckPieces -1M
```
```
XXX.levelgen.structure.StrongholdPieces -3M
```
```
XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector -1M
```
```
XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType +1M
```
```
XXX.saveddata.maps.MapItemSavedData$HoldingPlayer -4M
```
```
XXX.storage.loot.IntRange -3M
```
```
XXX.storage.loot.LootPool -6M
```
```
XXX.loot.entries.EmptyLootItem -1M
```
```
XXX.loot.entries.LootPoolSingletonContainer -1M
```
```
XXX.loot.functions.ApplyExplosionDecay -1M
```
```
XXX.loot.functions.CopyNbtFunction$CopyOperation -1M
```
```
XXX.loot.functions.CopyNbtFunction$MergeStrategy$3 +1M -1M
```
```
XXX.loot.functions.EnchantRandomlyFunction -2M
```
```
XXX.loot.functions.ExplorationMapFunction -7M
```
```
XXX.loot.functions.LootingEnchantFunction -4M
```
```
XXX.loot.functions.SetBannerPatternFunction$Builder -1M
```
```
XXX.loot.functions.SetContainerContents +1M -3M
```
```
XXX.loot.functions.SetItemDamageFunction -3M
```
```
XXX.loot.functions.SmeltItemFunction -1M
```
```
XXX.loot.predicates.AlternativeLootItemCondition -2M
```
```
XXX.loot.predicates.EntityHasScoreCondition -3M
```
```
XXX.loot.predicates.LootItemEntityPropertyCondition -3M
```
```
XXX.loot.predicates.LootItemRandomChanceWithLootingCondition -3M
```
```
XXX.providers.nbt.StorageNbtProvider -2M
```
```
XXX.level.timers.TimerQueue$Event -1M
```
```
XXX.phys.shapes.Shapes +2M -2M
```
```
XXX.world.scores.Team$CollisionRule +1M
```

</details>




<details>
<summary>
com.mojang.math.SymmetricGroup3
</summary>

```diff
+ boolean lambda$null$0(int[],SymmetricGroup3)
- boolean lambda$static$0(int[],SymmetricGroup3)
- SymmetricGroup3[] $values()
```

</details>




<details>
<summary>
net.minecraft.ChatFormatting
</summary>

```diff
- ChatFormatting[] $values()
```

</details>






<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ List lambda$null$4(Object,List)
+ List lambda$null$6(List,List)
- List lambda$sequence$4(Object,List)
- List lambda$sequence$6(List,List)
+ Logger access$100()
+ void lambda$null$8(CompletableFuture,List,int,Object,Throwable)
- void lambda$sequenceFailFast$8(CompletableFuture,List,int,Object,Throwable)
```

</details>




<details>
<summary>
net.minecraft.Util$OS
</summary>

```diff
- Util$OS[] $values()
+ void <init>(String,int,Util$1)
```

</details>




<details>
<summary>
net.minecraft.advancements.critereon.FilledBucketTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>














<details>
<summary>
net.minecraft.advancements.critereon.RecipeUnlockedTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>


<details>
<summary>
net.minecraft.advancements.critereon.SlideDownBlockTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.StatePropertiesPredicate
</summary>

```diff
+ void <init>(List,StatePropertiesPredicate$1)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.AngleArgument$SingleAngle
</summary>

```diff
+ void <init>(float,boolean,AngleArgument$1)
```

</details>


<details>
<summary>
net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
</summary>

```diff
- EntityAnchorArgument$Anchor[] $values()
+ Map access$000()
```

</details>





<details>
<summary>
net.minecraft.commands.arguments.NbtPathArgument
</summary>

```diff
+ Predicate access$000(CompoundTag)
```

</details>









<details>
<summary>
net.minecraft.commands.arguments.ScoreHolderArgument
</summary>

```diff
+ boolean access$000(ScoreHolderArgument)
+ void lambda$null$0(CommandContext,SuggestionsBuilder)
- void lambda$static$0(CommandContext,SuggestionsBuilder)
```

</details>




<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockPredicateArgument
</summary>

```diff
+ CommandSyntaxException lambda$null$2(ResourceLocation)
- CommandSyntaxException lambda$parse$2(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
</summary>

```diff
+ void <init>(EntitySelectorOptions$Modifier,Predicate,Component,EntitySelectorOptions$1)
```

</details>















<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
+ BiConsumer access$000(BlockModelGenerators)
+ BlockStateGenerator access$1200(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$1300(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$2000(Block,ResourceLocation)
+ BlockStateGenerator access$2100(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$500(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$600(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$700(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$800(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$900(Block,ResourceLocation,ResourceLocation)
+ Consumer access$200(BlockModelGenerators)
+ List access$1600(BlockModelGenerators)
- List lambda$createTurtleEgg$35(Integer,Integer)
+ List lambda$createTurtleEgg$39(Integer,Integer)
+ Map access$100(BlockModelGenerators)
+ Map access$1400(BlockModelGenerators)
+ Map access$1900()
+ MultiVariantGenerator access$300(Block,ResourceLocation)
- ResourceLocation lambda$createCropBlock$11(Block,int,int)
+ ResourceLocation lambda$null$15(Block,int,int)
- TextureMapping lambda$createChorusFlower$14(TextureMapping,ResourceLocation)
+ TextureMapping lambda$createChorusFlower$18(TextureMapping,ResourceLocation)
+ TextureMapping lambda$createCommandBlock$11(TextureMapping,ResourceLocation)
- TextureMapping lambda$createCommandBlock$7(TextureMapping,ResourceLocation)
+ Variant lambda$createActiveRail$10(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,RailShape)
- Variant lambda$createActiveRail$6(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,RailShape)
+ Variant lambda$createBambooModels$12(String,int)
- Variant lambda$createBambooModels$8(String,int)
- Variant lambda$createCropBlock$12(int[],Int2ObjectMap,Block,Integer)
+ Variant lambda$createCropBlock$16(int[],Int2ObjectMap,Block,Integer)
- Variant lambda$createEmptyOrFullDispatch$10(Comparable,Variant,Variant,Comparable)
+ Variant lambda$createEmptyOrFullDispatch$14(Comparable,Variant,Variant,Comparable)
- Variant lambda$createFire$16(Variant)
- Variant lambda$createFire$17(Variant)
- Variant lambda$createFire$18(Variant)
- Variant lambda$createFire$19(Variant)
+ Variant lambda$createFire$22(Variant)
+ Variant lambda$createFire$23(Variant)
+ Variant lambda$createFire$24(Variant)
+ Variant lambda$createFire$25(Variant)
- Variant lambda$createJigsaw$45(FrontAndTop)
+ Variant lambda$createJigsaw$49(FrontAndTop)
- Variant lambda$createRepeater$30(Integer,Boolean,Boolean)
+ Variant lambda$createRepeater$34(Integer,Boolean,Boolean)
- Variant lambda$createRespawnAnchor$44(ResourceLocation[],Integer)
+ Variant lambda$createRespawnAnchor$48(ResourceLocation[],Integer)
- Variant lambda$createSculkSensor$29(ResourceLocation,ResourceLocation,SculkSensorPhase)
+ Variant lambda$createSculkSensor$33(ResourceLocation,ResourceLocation,SculkSensorPhase)
- Variant lambda$createSnowBlocks$31(ResourceLocation,Integer)
+ Variant lambda$createSnowBlocks$35(ResourceLocation,Integer)
- Variant lambda$createSoulFire$22(Variant)
- Variant lambda$createSoulFire$23(Variant)
- Variant lambda$createSoulFire$24(Variant)
- Variant lambda$createSoulFire$25(Variant)
+ Variant lambda$createSoulFire$27(Variant)
+ Variant lambda$createSoulFire$28(Variant)
+ Variant lambda$createSoulFire$29(Variant)
+ Variant lambda$createSoulFire$30(Variant)
- Variant lambda$createStems$5(Block,TextureMapping,Integer)
+ Variant lambda$createStems$9(Block,TextureMapping,Integer)
- Variant lambda$createStructureBlock$32(StructureMode)
+ Variant lambda$createStructureBlock$36(StructureMode)
- Variant lambda$createSweetBerryBush$33(Integer)
+ Variant lambda$createSweetBerryBush$37(Integer)
- Variant lambda$createTripwireHook$34(Boolean,Boolean)
+ Variant lambda$createTripwireHook$38(Boolean,Boolean)
+ Variant lambda$null$40(ResourceLocation)
+ Variant lambda$null$41(ResourceLocation)
+ Variant lambda$null$42(ResourceLocation)
+ Variant lambda$null$43(ResourceLocation)
+ Variant lambda$null$44(ResourceLocation)
+ Variant lambda$null$45(ResourceLocation)
- Variant lambda$static$36(ResourceLocation)
- Variant lambda$static$37(ResourceLocation)
- Variant lambda$static$38(ResourceLocation)
- Variant lambda$static$39(ResourceLocation)
- Variant lambda$static$40(ResourceLocation)
- Variant lambda$static$41(ResourceLocation)
- Variant lambda$wrapModels$15(ResourceLocation)
+ Variant lambda$wrapModels$19(ResourceLocation)
+ void access$1000(BlockModelGenerators,Item)
+ void access$1100(BlockModelGenerators,Block)
+ void access$1500(BlockModelGenerators,Block)
+ void access$1700(BlockModelGenerators,Block)
+ void access$1800(BlockModelGenerators,Block)
+ void access$400(BlockModelGenerators,Block,ResourceLocation)
+ void lambda$createBarrel$13(ResourceLocation,TextureMapping)
- void lambda$createBarrel$9(ResourceLocation,TextureMapping)
- void lambda$createFurnace$13(ResourceLocation,TextureMapping)
+ void lambda$createFurnace$17(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$27(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$28(ResourceLocation,TextureMapping)
+ void lambda$createGrassBlocks$31(ResourceLocation,TextureMapping)
+ void lambda$createGrassBlocks$32(ResourceLocation,TextureMapping)
- void lambda$createMultiface$43(Block,MultiPartGenerator,ResourceLocation,BooleanProperty,Function)
+ void lambda$createMultiface$47(Block,MultiPartGenerator,ResourceLocation,BooleanProperty,Function)
- void lambda$run$46(BlockFamily)
- void lambda$run$47(SpawnEggItem)
+ void lambda$run$50(BlockFamily)
+ void lambda$run$51(SpawnEggItem)
- void lambda$static$42(HashMap)
+ void lambda$static$46(HashMap)
+ void lambda$static$5(Object,Block)
+ void lambda$static$6(Object,Block)
+ void lambda$static$7(Object,Block)
+ void lambda$static$8(Object,Block)
```

</details>





<details>
<summary>
net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
</summary>

```diff
+ void <init>(List,MultiPartGenerator$1)
```

</details>

<details>
<summary>
net.minecraft.data.tags.TagsProvider$TagAppender
</summary>

```diff
+ void <init>(Tag$Builder,Registry,String,TagsProvider$1)
```

</details>

















<details>
<summary>
net.minecraft.gametest.framework.GameTestBatchRunner
</summary>

```diff
- GameTestInfo lambda$new$0(Rotation,ServerLevel,TestFunction)
+ GameTestInfo lambda$null$0(Rotation,ServerLevel,TestFunction)
+ ServerLevel access$000(GameTestBatchRunner)
+ void access$100(GameTestBatchRunner,int)
```

</details>




<details>
<summary>
net.minecraft.gametest.framework.GameTestSequence
</summary>

```diff
+ GameTestInfo access$000(GameTestSequence)
```

</details>







<details>
<summary>
net.minecraft.gametest.framework.TestCommand
</summary>

```diff
+ void access$000(ServerLevel,MultipleTestTracker)
```

</details>













<details>
<summary>
net.minecraft.nbt.ListTag
</summary>

```diff
+ void <init>(List,byte,ListTag$1)
```

</details>

<details>
<summary>
net.minecraft.nbt.LongTag
</summary>

```diff
+ void <init>(long,LongTag$1)
```

</details>


<details>
<summary>
net.minecraft.nbt.NbtOps
</summary>

```diff
- void lambda$getMapEntries$7(BiConsumer,CompoundTag,String)
+ void lambda$null$7(BiConsumer,CompoundTag,String)
```

</details>













<details>
<summary>
net.minecraft.network.Connection$PacketHolder
</summary>

```diff
+ GenericFutureListener access$100(Connection$PacketHolder)
+ Packet access$000(Connection$PacketHolder)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
</summary>

```diff
+ CommandNode access$000(ClientboundCommandsPacket$Entry)
+ void <init>(ArgumentBuilder,byte,int,int[],ClientboundCommandsPacket$1)
```

</details>



















<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
</summary>

```diff
- ClientboundPlayerPositionPacket$RelativeArgument[] $values()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRecipePacket$State
</summary>

```diff
- ClientboundRecipePacket$State[] $values()
```

</details>





















<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
</summary>

```diff
- AttributeModifier lambda$new$0(FriendlyByteBuf)
+ AttributeModifier lambda$null$0(FriendlyByteBuf)
+ void lambda$null$2(FriendlyByteBuf,AttributeModifier)
- void lambda$write$2(FriendlyByteBuf,AttributeModifier)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.DebugPackets
</summary>

```diff
+ void lambda$null$6(List,String,GossipType,Integer)
- void lambda$writeBrain$6(List,String,GossipType,Integer)
```

</details>







<details>
<summary>
net.minecraft.network.protocol.game.ServerboundInteractPacket
</summary>

```diff
+ ServerboundInteractPacket$Action access$400()
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
</summary>

```diff
+ void <init>(FriendlyByteBuf,ServerboundInteractPacket$1)
+ void <init>(InteractionHand,Vec3,ServerboundInteractPacket$1)
```

</details>















<details>
<summary>
net.minecraft.server.ServerFunctionManager$QueuedCommand
</summary>

```diff
+ int access$400(ServerFunctionManager$QueuedCommand)
```

</details>





<details>
<summary>
net.minecraft.server.commands.DebugCommand$Tracer
</summary>

```diff
+ void <init>(PrintWriter,DebugCommand$1)
```

</details>


<details>
<summary>
net.minecraft.server.commands.EmoteCommands
</summary>

```diff
+ Component lambda$null$0(ServerPlayer,Component,Component,ServerPlayer)
- Component lambda$register$0(ServerPlayer,Component,Component,ServerPlayer)
+ void lambda$null$1(CommandContext,MinecraftServer,ServerPlayer,Entity,TextFilter$FilteredText)
- void lambda$register$1(CommandContext,MinecraftServer,ServerPlayer,Entity,TextFilter$FilteredText)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ExecuteCommand
</summary>

```diff
- boolean lambda$addConditionals$40(Integer,Integer)
- boolean lambda$addConditionals$42(Integer,Integer)
- boolean lambda$addConditionals$44(Integer,Integer)
- boolean lambda$addConditionals$46(Integer,Integer)
+ boolean lambda$null$40(Integer,Integer)
+ boolean lambda$null$42(Integer,Integer)
+ boolean lambda$null$44(Integer,Integer)
+ boolean lambda$null$46(Integer,Integer)
- Collection lambda$addConditionals$52(boolean,DataCommands$DataProvider,CommandContext)
+ Collection lambda$null$52(boolean,DataCommands$DataProvider,CommandContext)
+ CommandSourceStack lambda$null$22(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$24(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$26(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$28(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$30(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$32(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$22(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$24(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$26(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$28(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$30(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$32(DataCommands$DataProvider,boolean,CommandContext)
- int lambda$addConditionals$53(DataCommands$DataProvider,CommandContext)
+ int lambda$null$53(DataCommands$DataProvider,CommandContext)
+ Tag lambda$null$21(CommandContext,int)
+ Tag lambda$null$23(CommandContext,int)
+ Tag lambda$null$25(CommandContext,int)
+ Tag lambda$null$27(CommandContext,int)
+ Tag lambda$null$29(CommandContext,int)
+ Tag lambda$null$31(CommandContext,int)
+ Tag lambda$null$36(IntFunction,int)
- Tag lambda$storeData$36(IntFunction,int)
- Tag lambda$wrapStores$21(CommandContext,int)
- Tag lambda$wrapStores$23(CommandContext,int)
- Tag lambda$wrapStores$25(CommandContext,int)
- Tag lambda$wrapStores$27(CommandContext,int)
- Tag lambda$wrapStores$29(CommandContext,int)
- Tag lambda$wrapStores$31(CommandContext,int)
+ void lambda$null$2(ResultConsumer,ResultConsumer,CommandContext,boolean,int)
- void lambda$static$2(ResultConsumer,ResultConsumer,CommandContext,boolean,int)
```

</details>

<details>
<summary>
net.minecraft.server.commands.ExperienceCommand$Type
</summary>

```diff
- ExperienceCommand$Type[] $values()
+ ToIntFunction access$000(ExperienceCommand$Type)
```

</details>
<details>
<summary>
net.minecraft.server.commands.FillCommand$Mode
</summary>

```diff
- FillCommand$Mode[] $values()
```

</details>

<details>
<summary>
net.minecraft.server.commands.GameRuleCommand
</summary>

```diff
+ int access$000(CommandContext,GameRules$Key)
+ int access$100(CommandSourceStack,GameRules$Key)
```

</details>




<details>
<summary>
net.minecraft.server.commands.LootCommand
</summary>

```diff
+ int lambda$null$10(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$11(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$12(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$13(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$4(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$5(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$6(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$7(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$8(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$9(LootCommand$DropConsumer,CommandContext)
- int lambda$register$10(LootCommand$DropConsumer,CommandContext)
- int lambda$register$11(LootCommand$DropConsumer,CommandContext)
- int lambda$register$12(LootCommand$DropConsumer,CommandContext)
- int lambda$register$13(LootCommand$DropConsumer,CommandContext)
- int lambda$register$4(LootCommand$DropConsumer,CommandContext)
- int lambda$register$5(LootCommand$DropConsumer,CommandContext)
- int lambda$register$6(LootCommand$DropConsumer,CommandContext)
- int lambda$register$7(LootCommand$DropConsumer,CommandContext)
- int lambda$register$8(LootCommand$DropConsumer,CommandContext)
- int lambda$register$9(LootCommand$DropConsumer,CommandContext)
```

</details>









<details>
<summary>
net.minecraft.server.commands.SeedCommand
</summary>

```diff
+ Style lambda$null$1(long,Style)
- Style lambda$register$1(long,Style)
```

</details>




<details>
<summary>
net.minecraft.server.dedicated.Settings$MutableValue
</summary>

```diff
+ void <init>(Settings,String,Object,Function,Settings$1)
```

</details>
<details>
<summary>
net.minecraft.server.gui.MinecraftServerGui
</summary>

```diff
+ AtomicBoolean access$000(MinecraftServerGui)
+ void access$100(MinecraftServerGui)
```

</details>





<details>
<summary>
net.minecraft.server.level.ChunkHolder$FullChunkStatus
</summary>

```diff
- ChunkHolder$FullChunkStatus[] $values()
```

</details>



<details>
<summary>
net.minecraft.server.level.ChunkTaskPriorityQueue
</summary>

```diff
+ Either lambda$null$5(long)
- Either lambda$pop$5(long)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
</summary>

```diff
+ void <init>(ServerChunkCache,Level,ServerChunkCache$1)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ EntityTickList access$100(ServerLevel)
+ Int2ObjectMap access$400(ServerLevel)
+ List access$200(ServerLevel)
+ Set access$300(ServerLevel)
+ void lambda$null$16(BlockPos)
+ void lambda$null$18(BlockPos,PoiType)
- void lambda$onBlockStateChange$16(BlockPos)
- void lambda$onBlockStateChange$18(BlockPos,PoiType)
```

</details>

<details>
<summary>
net.minecraft.server.network.TextFilterClient$RequestFailedException
</summary>

```diff
+ void <init>(String,TextFilterClient$1)
```

</details>









<details>
<summary>
net.minecraft.server.packs.repository.Pack$Position
</summary>

```diff
- Pack$Position[] $values()
```

</details>





<details>
<summary>
net.minecraft.tags.StaticTagHelper$Wrapper
</summary>

```diff
+ void <init>(ResourceLocation,StaticTagHelper$1)
```

</details>
<details>
<summary>
net.minecraft.tags.Tag
</summary>

```diff
- DataResult lambda$codec$0(ResourceLocation)
- DataResult lambda$codec$2(Tag)
+ DataResult lambda$null$0(ResourceLocation)
+ DataResult lambda$null$2(Tag)
```

</details>
<details>
<summary>
net.minecraft.tags.TagManager$LoaderInfo
</summary>

```diff
+ CompletableFuture access$100(TagManager$LoaderInfo)
+ void <init>(StaticTagHelper,CompletableFuture,TagManager$1)
```

</details>




<details>
<summary>
net.minecraft.util.LowerCaseEnumTypeAdapterFactory
</summary>

```diff
+ String access$000(LowerCaseEnumTypeAdapterFactory,Object)
```

</details>



<details>
<summary>
net.minecraft.util.SortedArraySet
</summary>

```diff
+ int access$000(SortedArraySet)
+ Object[] access$100(SortedArraySet)
+ void access$200(SortedArraySet,int)
```

</details>

<details>
<summary>
net.minecraft.util.profiling.ActiveProfiler$PathEntry
</summary>

```diff
+ long access$000(ActiveProfiler$PathEntry)
+ long access$002(ActiveProfiler$PathEntry,long)
+ long access$100(ActiveProfiler$PathEntry)
+ long access$102(ActiveProfiler$PathEntry,long)
+ Object2LongOpenHashMap access$200(ActiveProfiler$PathEntry)
```

</details>







<details>
<summary>
net.minecraft.util.profiling.registry.MeasurementCategory
</summary>

```diff
- MeasurementCategory[] $values()
```

</details>




<details>
<summary>
net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
</summary>

```diff
- GateBehavior$RunningPolicy[] $values()
+ void <init>(String,int,GateBehavior$1)
```

</details>












<details>
<summary>
net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
</summary>

```diff
+ boolean lambda$null$0(GlobalPos,PoiType,Villager)
- boolean lambda$start$0(GlobalPos,PoiType,Villager)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
</summary>

```diff
+ boolean lambda$null$0(PathfinderMob,LivingEntity)
- boolean lambda$start$0(PathfinderMob,LivingEntity)
```

</details>










<details>
<summary>
net.minecraft.world.entity.ai.behavior.ShufflingList
</summary>

```diff
+ double lambda$shuffle$2(Object)
```

</details>












<details>
<summary>
net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
</summary>

```diff
- boolean lambda$getNearestEntity$0(LivingEntity,LivingEntity)
+ boolean lambda$null$0(LivingEntity,LivingEntity)
```

</details>





<details>
<summary>
net.minecraft.world.entity.ai.targeting.TargetingConditions
</summary>

```diff
+ TargetingConditions allowInvulnerable()
+ TargetingConditions allowNonAttackable()
+ TargetingConditions allowSameTeam()
+ TargetingConditions allowUnseeable()
- TargetingConditions forCombat()
- TargetingConditions forNonCombat()
- TargetingConditions ignoreLineOfSight()
+ void <init>()
- void <init>(boolean)
```

</details>


<details>
<summary>
net.minecraft.world.entity.ai.util.HoverRandomPos
</summary>

```diff
- boolean lambda$getPos$0(PathfinderMob,BlockPos)
+ boolean lambda$null$0(PathfinderMob,BlockPos)
```

</details>





<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiRecord
</summary>

```diff
- BlockPos lambda$codec$0(PoiRecord)
+ BlockPos lambda$null$0(PoiRecord)
- Integer lambda$codec$2(PoiRecord)
+ Integer lambda$null$2(PoiRecord)
- PoiType lambda$codec$1(PoiRecord)
+ PoiType lambda$null$1(PoiRecord)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
+ Bee$BeeGoToHiveGoal access$4800(Bee)
+ Bee$BeePollinateGoal access$700(Bee)
+ BlockPos access$1500(Bee)
+ BlockPos access$1502(Bee,BlockPos)
+ BlockPos access$3200(Bee)
+ BlockPos access$3202(Bee,BlockPos)
+ boolean access$1400(Bee)
+ boolean access$1600(Bee,BlockPos,int)
+ boolean access$1800(Bee)
+ boolean access$2400(Bee,BlockPos)
+ boolean access$3300(Bee,BlockPos)
+ boolean access$5100(Bee,BlockPos)
+ int access$3000(Bee)
+ int access$3002(Bee,int)
+ int access$3700(Bee)
+ int access$3800(Bee)
+ int access$3802(Bee,int)
+ int access$5200(Bee)
- PathNavigation access$000(Bee)
- PathNavigation access$1000(Bee)
- PathNavigation access$1400(Bee)
- PathNavigation access$1500(Bee)
- PathNavigation access$1600(Bee)
- PathNavigation access$1700(Bee)
- PathNavigation access$1800(Bee)
+ PathNavigation access$1900(Bee)
- PathNavigation access$200(Bee)
+ PathNavigation access$2000(Bee)
+ PathNavigation access$2200(Bee)
+ PathNavigation access$2600(Bee)
+ PathNavigation access$2700(Bee)
+ PathNavigation access$2800(Bee)
+ PathNavigation access$2900(Bee)
- PathNavigation access$300(Bee)
+ PathNavigation access$3100(Bee)
+ PathNavigation access$3400(Bee)
+ PathNavigation access$3500(Bee)
+ PathNavigation access$3600(Bee)
+ PathNavigation access$3900(Bee)
- PathNavigation access$400(Bee)
+ PathNavigation access$4300(Bee)
+ PathNavigation access$4500(Bee)
- PathNavigation access$500(Bee)
- PathNavigation access$600(Bee)
- PathNavigation access$700(Bee)
- PathNavigation access$800(Bee)
- Random access$100(Bee)
+ Random access$1000(Bee)
- Random access$1900(Bee)
- Random access$2000(Bee)
- Random access$2200(Bee)
- Random access$2400(Bee)
- Random access$2500(Bee)
- Random access$2600(Bee)
- Random access$2700(Bee)
- Random access$2800(Bee)
+ Random access$4000(Bee)
+ Random access$4100(Bee)
+ Random access$4400(Bee)
+ Random access$4600(Bee)
+ Random access$4700(Bee)
+ Random access$5300(Bee)
+ Random access$5400(Bee)
+ void access$2500(Bee,BlockPos)
+ void access$4200(Bee,boolean)
+ void access$5500(Bee)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BaseBeeGoal
</summary>

```diff
+ void <init>(Bee,Bee$1)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
</summary>

```diff
+ boolean access$4900(Bee$BeeGoToHiveGoal,BlockPos)
+ int access$300(Bee$BeeGoToHiveGoal)
+ List access$500(Bee$BeeGoToHiveGoal)
+ void access$5000(Bee$BeeGoToHiveGoal)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
</summary>

```diff
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
</summary>

```diff
+ boolean lambda$findNearbyHivesWithSpace$1(Bee,BlockPos)
- double lambda$findNearbyHivesWithSpace$1(BlockPos,BlockPos)
+ double lambda$findNearbyHivesWithSpace$2(BlockPos,BlockPos)
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeePollinateGoal
</summary>

```diff
+ boolean access$600(Bee$BeePollinateGoal)
+ void access$800(Bee$BeePollinateGoal)
```

</details>




<details>
<summary>
net.minecraft.world.entity.animal.Dolphin
</summary>

```diff
- Random access$000(Dolphin)
+ Random access$300(Dolphin)
+ TargetingConditions access$400()
```

</details>













<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
+ boolean access$000(Ocelot)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Panda$Gene
</summary>

```diff
+ Panda$Gene access$000(Panda$Gene,Panda$Gene)
- Panda$Gene[] $values()
```

</details>





<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
+ Map access$000()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Pufferfish
</summary>

```diff
+ int access$002(Pufferfish,int)
+ int access$102(Pufferfish,int)
+ TargetingConditions access$200()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
+ boolean access$300(Rabbit)
+ int access$402(Rabbit,int)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
- boolean access$000(Squid)
+ boolean access$100(Squid)
- boolean canBeLeashed(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.TropicalFish$Pattern
</summary>

```diff
- TropicalFish$Pattern[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
+ BlockPos access$600(Turtle)
+ BlockPos access$700(Turtle)
+ boolean access$1300(Turtle)
+ boolean access$1400(Turtle)
+ int access$1000(Turtle)
+ int access$1008(Turtle)
- Random access$000(Turtle)
- Random access$100(Turtle)
+ Random access$1200(Turtle)
+ Random access$300(Turtle)
+ void access$1100(Turtle,boolean)
+ void access$400(Turtle,BlockPos)
+ void access$500(Turtle,boolean)
+ void access$800(Turtle,boolean)
+ void access$900(Turtle,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
</summary>

```diff
+ void <init>(Goat$1)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
</summary>

```diff
+ void <init>(Evoker,Evoker$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
</summary>

```diff
+ void <init>(Evoker,Evoker$1)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Guardian
</summary>

```diff
+ void access$000(Guardian,int)
+ void access$100(Guardian,boolean)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
</summary>

```diff
+ void <init>(Phantom,Phantom$1)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Ravager
</summary>

```diff
+ boolean canSee(Entity)
- boolean hasLineOfSight(Entity)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
- boolean access$000(Slime)
+ boolean access$100(Slime)
+ float access$000(Slime)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.SpellcasterIllager
</summary>

```diff
- PathNavigation access$000(SpellcasterIllager)
+ PathNavigation access$200(SpellcasterIllager)
```

</details>















<details>
<summary>
net.minecraft.world.inventory.ClickAction
</summary>

```diff
- ClickAction[] $values()
```

</details>










<details>
<summary>
net.minecraft.world.inventory.GrindstoneMenu
</summary>

```diff
+ Container access$000(GrindstoneMenu)
```

</details>















<details>
<summary>
net.minecraft.world.inventory.RecipeBookType
</summary>

```diff
- RecipeBookType[] $values()
```

</details>










<details>
<summary>
net.minecraft.world.item.ArmorMaterials
</summary>

```diff
- ArmorMaterials[] $values()
```

</details>
















<details>
<summary>
net.minecraft.world.item.DiggerItem
</summary>

```diff
- boolean isCorrectToolForDrops(BlockState)
+ void <init>(float,float,Tier,Set,Item$Properties)
- void <init>(float,float,Tier,Tag,Item$Properties)
```

</details>















<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
+ boolean access$600(Item$Properties)
+ CreativeModeTab access$000(Item$Properties)
+ FoodProperties access$500(Item$Properties)
+ int access$300(Item$Properties)
+ int access$400(Item$Properties)
+ Item access$200(Item$Properties)
+ Rarity access$100(Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.Ingredient$ItemValue
</summary>

```diff
+ void <init>(ItemStack,Ingredient$1)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.RecipeManager
</summary>

```diff
+ Map lambda$null$10(RecipeType)
- Map lambda$replaceRecipes$10(RecipeType)
```

</details>










<details>
<summary>
net.minecraft.world.item.crafting.UpgradeRecipe
</summary>

```diff
+ Ingredient access$000(UpgradeRecipe)
+ Ingredient access$100(UpgradeRecipe)
+ ItemStack access$200(UpgradeRecipe)
```

</details>






<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentCategory
</summary>

```diff
- EnchantmentCategory[] $values()
+ void <init>(String,int,EnchantmentCategory$1)
```

</details>













<details>
<summary>
net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
</summary>

```diff
- ProtectionEnchantment$Type[] $values()
```

</details>













<details>
<summary>
net.minecraft.world.level.GameRules$Category
</summary>

```diff
- GameRules$Category[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$IntegerValue
</summary>

```diff
+ GameRules$Type access$100(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$Type
</summary>

```diff
+ BiConsumer access$300(GameRules$Type)
+ void <init>(Supplier,Function,BiConsumer,GameRules$VisitorCaller,GameRules$1)
```

</details>







<details>
<summary>
net.minecraft.world.level.LightLayer
</summary>

```diff
- LightLayer[] $values()
```

</details>


<details>
<summary>
net.minecraft.world.level.NaturalSpawner$SpawnState
</summary>

```diff
+ boolean access$300(NaturalSpawner$SpawnState,MobCategory)
+ boolean access$500(NaturalSpawner$SpawnState,EntityType,BlockPos,ChunkAccess)
+ void <init>(int,Object2IntOpenHashMap,PotentialCalculator,NaturalSpawner$1)
+ void access$400(NaturalSpawner$SpawnState,Mob,ChunkAccess)
```

</details>



<details>
<summary>
net.minecraft.world.level.StructureFeatureManager
</summary>

```diff
- boolean lambda$getStructureAt$3(BlockPos,StructurePiece)
+ boolean lambda$null$3(BlockPos,StructurePiece)
```

</details>


<details>
<summary>
net.minecraft.world.level.biome.AmbientMoodSettings
</summary>

```diff
+ Double lambda$null$3(AmbientMoodSettings)
- Double lambda$static$3(AmbientMoodSettings)
+ Integer lambda$null$1(AmbientMoodSettings)
+ Integer lambda$null$2(AmbientMoodSettings)
- Integer lambda$static$1(AmbientMoodSettings)
- Integer lambda$static$2(AmbientMoodSettings)
+ SoundEvent lambda$null$0(AmbientMoodSettings)
- SoundEvent lambda$static$0(AmbientMoodSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ Biome lambda$null$13(Biome$ClimateSettings,Biome$BiomeCategory,Float,Float,BiomeSpecialEffects)
- Biome lambda$static$13(Biome$ClimateSettings,Biome$BiomeCategory,Float,Float,BiomeSpecialEffects)
+ Biome$BiomeCategory lambda$null$1(Biome)
+ Biome$BiomeCategory lambda$null$9(Biome)
- Biome$BiomeCategory lambda$static$1(Biome)
- Biome$BiomeCategory lambda$static$9(Biome)
+ Biome$ClimateSettings lambda$null$0(Biome)
+ Biome$ClimateSettings lambda$null$8(Biome)
- Biome$ClimateSettings lambda$static$0(Biome)
- Biome$ClimateSettings lambda$static$8(Biome)
+ BiomeGenerationSettings lambda$null$5(Biome)
- BiomeGenerationSettings lambda$static$5(Biome)
+ BiomeSpecialEffects lambda$null$12(Biome)
+ BiomeSpecialEffects lambda$null$4(Biome)
- BiomeSpecialEffects lambda$static$12(Biome)
- BiomeSpecialEffects lambda$static$4(Biome)
+ Float lambda$null$10(Biome)
+ Float lambda$null$11(Biome)
+ Float lambda$null$2(Biome)
+ Float lambda$null$3(Biome)
- Float lambda$static$10(Biome)
- Float lambda$static$11(Biome)
- Float lambda$static$2(Biome)
- Float lambda$static$3(Biome)
- Long2FloatLinkedOpenHashMap lambda$new$16()
+ Long2FloatLinkedOpenHashMap lambda$null$16()
+ MobSpawnSettings lambda$null$6(Biome)
- MobSpawnSettings lambda$static$6(Biome)
+ PerlinSimplexNoise access$100()
+ void <init>(Biome$ClimateSettings,Biome$BiomeCategory,float,float,BiomeSpecialEffects,BiomeGenerationSettings,MobSpawnSettings,Biome$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.biome.Biome$ClimateParameters
</summary>

```diff
+ Float lambda$null$0(Biome$ClimateParameters)
+ Float lambda$null$1(Biome$ClimateParameters)
+ Float lambda$null$2(Biome$ClimateParameters)
+ Float lambda$null$3(Biome$ClimateParameters)
+ Float lambda$null$4(Biome$ClimateParameters)
- Float lambda$static$0(Biome$ClimateParameters)
- Float lambda$static$1(Biome$ClimateParameters)
- Float lambda$static$2(Biome$ClimateParameters)
- Float lambda$static$3(Biome$ClimateParameters)
- Float lambda$static$4(Biome$ClimateParameters)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome$Precipitation
</summary>

```diff
- Biome$Precipitation[] $values()
```

</details>

<details>
<summary>
net.minecraft.world.level.biome.BiomeGenerationSettings
</summary>

```diff
+ List lambda$null$3(BiomeGenerationSettings)
+ List lambda$null$4(BiomeGenerationSettings)
- List lambda$static$3(BiomeGenerationSettings)
- List lambda$static$4(BiomeGenerationSettings)
+ Map lambda$null$2(BiomeGenerationSettings)
- Map lambda$static$2(BiomeGenerationSettings)
+ Supplier lambda$null$1(BiomeGenerationSettings)
- Supplier lambda$static$1(BiomeGenerationSettings)
+ void <init>(Supplier,Map,List,List,BiomeGenerationSettings$1)
```

</details>





<details>
<summary>
net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
</summary>

```diff
- FuzzyOffsetConstantColumnBiomeZoomer[] $values()
```

</details>

<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
</summary>

```diff
+ DataResult lambda$null$0(ResourceLocation)
+ DataResult lambda$null$1(ResourceLocation)
+ DataResult lambda$null$2(MultiNoiseBiomeSource$Preset)
- DataResult lambda$static$0(ResourceLocation)
- DataResult lambda$static$1(ResourceLocation)
- DataResult lambda$static$2(MultiNoiseBiomeSource$Preset)
+ void <init>(MultiNoiseBiomeSource$Preset,Registry,long,MultiNoiseBiomeSource$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.OverworldBiomeSource
</summary>

```diff
- Biome lambda$new$5(Registry,ResourceKey)
+ Biome lambda$null$5(Registry,ResourceKey)
+ Boolean lambda$null$1(OverworldBiomeSource)
+ Boolean lambda$null$2(OverworldBiomeSource)
- Boolean lambda$static$1(OverworldBiomeSource)
- Boolean lambda$static$2(OverworldBiomeSource)
+ Long lambda$null$0(OverworldBiomeSource)
- Long lambda$static$0(OverworldBiomeSource)
+ Registry lambda$null$3(OverworldBiomeSource)
- Registry lambda$static$3(OverworldBiomeSource)
```

</details>









































<details>
<summary>
net.minecraft.world.level.block.ComposterBlock
</summary>

```diff
+ BlockState access$000(BlockState,LevelAccessor,BlockPos)
+ BlockState access$100(BlockState,LevelAccessor,BlockPos,ItemStack)
```

</details>












<details>
<summary>
net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
</summary>

```diff
- DoubleBlockCombiner$BlockType[] $values()
```

</details>















































<details>
<summary>
net.minecraft.world.level.block.PowderSnowBlock
</summary>

```diff
+ void spawnPowderSnowParticles(Level,Vec3)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
</summary>

```diff
- PressurePlateBlock$Sensitivity[] $values()
```

</details>

























































<details>
<summary>
net.minecraft.world.level.block.entity.BannerPattern
</summary>

```diff
- BannerPattern[] $values()
+ String access$000(BannerPattern)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BarrelBlockEntity
</summary>

```diff
+ void access$000(BarrelBlockEntity,BlockState,SoundEvent)
+ void access$100(BarrelBlockEntity,BlockState,boolean)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.state.properties.RailShape
</summary>

```diff
- RailShape[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.SculkSensorPhase
</summary>

```diff
- SculkSensorPhase[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.StairsShape
</summary>

```diff
- StairsShape[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.Tilt
</summary>

```diff
- Tilt[] $values()
```

</details>


<details>
<summary>
net.minecraft.world.level.border.BorderStatus
</summary>

```diff
- BorderStatus[] $values()
```

</details>






<details>
<summary>
net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
</summary>

```diff
+ CompletableFuture access$100(IOWorker$PendingStore)
+ CompoundTag access$000(IOWorker$PendingStore)
+ CompoundTag access$002(IOWorker$PendingStore,CompoundTag)
```

</details>


<details>
<summary>
net.minecraft.world.level.chunk.storage.RegionFile
</summary>

```diff
+ RegionFileVersion access$000(RegionFile)
```

</details>


<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
+ void lambda$null$1(long)
- void lambda$readColumn$1(long)
```

</details>














<details>
<summary>
net.minecraft.world.level.entity.Visibility
</summary>

```diff
- Visibility[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.BlockPositionSource
</summary>

```diff
+ Optional access$000(BlockPositionSource)
+ Optional lambda$null$0(BlockPositionSource)
- Optional lambda$static$0(BlockPositionSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.EntityPositionSource
</summary>

```diff
+ int access$000(EntityPositionSource)
+ Integer lambda$null$0(EntityPositionSource)
- Integer lambda$static$0(EntityPositionSource)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus
</summary>

```diff
+ BlockState access$100(Aquifer$NoiseBasedAquifer$AquiferStatus)
+ int access$000(Aquifer$NoiseBasedAquifer$AquiferStatus)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.Cavifier$QuantizedSpaghettiRarity
</summary>

```diff
+ double access$000(double)
+ double access$100(double)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Column$Line
</summary>

```diff
+ Column$Line access$000()
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Carving
</summary>

```diff
- GenerationStep$Carving[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GeodeBlockSettings
</summary>

```diff
+ BlockStateProvider lambda$null$0(GeodeBlockSettings)
+ BlockStateProvider lambda$null$1(GeodeBlockSettings)
+ BlockStateProvider lambda$null$2(GeodeBlockSettings)
+ BlockStateProvider lambda$null$3(GeodeBlockSettings)
+ BlockStateProvider lambda$null$4(GeodeBlockSettings)
- BlockStateProvider lambda$static$0(GeodeBlockSettings)
- BlockStateProvider lambda$static$1(GeodeBlockSettings)
- BlockStateProvider lambda$static$2(GeodeBlockSettings)
- BlockStateProvider lambda$static$3(GeodeBlockSettings)
- BlockStateProvider lambda$static$4(GeodeBlockSettings)
+ List lambda$null$5(GeodeBlockSettings)
- List lambda$static$5(GeodeBlockSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GeodeLayerSettings
</summary>

```diff
+ Double lambda$null$0(GeodeLayerSettings)
+ Double lambda$null$1(GeodeLayerSettings)
+ Double lambda$null$2(GeodeLayerSettings)
+ Double lambda$null$3(GeodeLayerSettings)
- Double lambda$static$0(GeodeLayerSettings)
- Double lambda$static$1(GeodeLayerSettings)
- Double lambda$static$2(GeodeLayerSettings)
- Double lambda$static$3(GeodeLayerSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Heightmap$Types
</summary>

```diff
- Heightmap$Types[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ BiomeSource lambda$null$0(NoiseBasedChunkGenerator)
- BiomeSource lambda$static$0(NoiseBasedChunkGenerator)
+ int access$000(NoiseBasedChunkGenerator)
+ int access$100(NoiseBasedChunkGenerator)
+ int access$200(NoiseBasedChunkGenerator)
+ Long lambda$null$1(NoiseBasedChunkGenerator)
- Long lambda$static$1(NoiseBasedChunkGenerator)
+ NoodleCavifier access$400(NoiseBasedChunkGenerator)
+ OreVeinifier access$300(NoiseBasedChunkGenerator)
+ Supplier lambda$null$2(NoiseBasedChunkGenerator)
- Supplier lambda$static$2(NoiseBasedChunkGenerator)
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.WorldGenSettings
</summary>

```diff
+ Optional lambda$null$0(WorldGenSettings)
- Optional lambda$static$0(WorldGenSettings)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
</summary>

```diff
+ Float lambda$null$4(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ Float lambda$null$5(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Float lambda$static$4(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Float lambda$static$5(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$0(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$1(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$3(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$0(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$1(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$3(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ Integer lambda$null$2(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Integer lambda$static$2(CanyonCarverConfiguration$CanyonShapeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarverConfiguration
</summary>

```diff
+ Boolean lambda$null$4(CarverConfiguration)
- Boolean lambda$static$4(CarverConfiguration)
+ CarverDebugSettings lambda$null$5(CarverConfiguration)
- CarverDebugSettings lambda$static$5(CarverConfiguration)
+ Float lambda$null$0(CarverConfiguration)
- Float lambda$static$0(CarverConfiguration)
+ FloatProvider lambda$null$2(CarverConfiguration)
- FloatProvider lambda$static$2(CarverConfiguration)
+ HeightProvider lambda$null$1(CarverConfiguration)
- HeightProvider lambda$static$1(CarverConfiguration)
+ VerticalAnchor lambda$null$3(CarverConfiguration)
- VerticalAnchor lambda$static$3(CarverConfiguration)
```

</details>
























<details>
<summary>
net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
</summary>

```diff
+ Integer lambda$null$4(FossilFeatureConfiguration)
- Integer lambda$static$4(FossilFeatureConfiguration)
+ List lambda$null$0(FossilFeatureConfiguration)
+ List lambda$null$1(FossilFeatureConfiguration)
- List lambda$static$0(FossilFeatureConfiguration)
- List lambda$static$1(FossilFeatureConfiguration)
+ Supplier lambda$null$2(FossilFeatureConfiguration)
+ Supplier lambda$null$3(FossilFeatureConfiguration)
- Supplier lambda$static$2(FossilFeatureConfiguration)
- Supplier lambda$static$3(FossilFeatureConfiguration)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
</summary>

```diff
+ BlockState lambda$null$0(HugeFungusConfiguration)
+ BlockState lambda$null$1(HugeFungusConfiguration)
+ BlockState lambda$null$2(HugeFungusConfiguration)
+ BlockState lambda$null$3(HugeFungusConfiguration)
- BlockState lambda$static$0(HugeFungusConfiguration)
- BlockState lambda$static$1(HugeFungusConfiguration)
- BlockState lambda$static$2(HugeFungusConfiguration)
- BlockState lambda$static$3(HugeFungusConfiguration)
+ Boolean lambda$null$4(HugeFungusConfiguration)
- Boolean lambda$static$4(HugeFungusConfiguration)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature
</summary>

```diff
+ boolean access$100(JigsawFeature)
+ boolean access$200(JigsawFeature)
+ int access$000(JigsawFeature)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
</summary>

```diff
+ void <init>(SpikeFeature$1)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
</summary>

```diff
+ Float lambda$null$1(WeightedConfiguredFeature)
- Float lambda$static$1(WeightedConfiguredFeature)
+ Supplier lambda$null$0(WeightedConfiguredFeature)
- Supplier lambda$static$0(WeightedConfiguredFeature)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
</summary>

```diff
+ BlockState lambda$null$0(DiskConfiguration)
- BlockState lambda$static$0(DiskConfiguration)
+ Integer lambda$null$2(DiskConfiguration)
- Integer lambda$static$2(DiskConfiguration)
+ IntProvider lambda$null$1(DiskConfiguration)
- IntProvider lambda$static$1(DiskConfiguration)
+ List lambda$null$3(DiskConfiguration)
- List lambda$static$3(DiskConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
</summary>

```diff
+ Boolean lambda$null$1(EndGatewayConfiguration)
- Boolean lambda$static$1(EndGatewayConfiguration)
+ Optional lambda$null$0(EndGatewayConfiguration)
- Optional lambda$static$0(EndGatewayConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
</summary>

```diff
+ Boolean lambda$null$5(GeodeConfiguration)
- Boolean lambda$static$5(GeodeConfiguration)
+ Double lambda$null$11(GeodeConfiguration)
+ Double lambda$null$3(GeodeConfiguration)
+ Double lambda$null$4(GeodeConfiguration)
- Double lambda$static$11(GeodeConfiguration)
- Double lambda$static$3(GeodeConfiguration)
- Double lambda$static$4(GeodeConfiguration)
+ GeodeBlockSettings lambda$null$0(GeodeConfiguration)
- GeodeBlockSettings lambda$static$0(GeodeConfiguration)
+ GeodeCrackSettings lambda$null$2(GeodeConfiguration)
- GeodeCrackSettings lambda$static$2(GeodeConfiguration)
+ GeodeLayerSettings lambda$null$1(GeodeConfiguration)
- GeodeLayerSettings lambda$static$1(GeodeConfiguration)
+ Integer lambda$null$10(GeodeConfiguration)
+ Integer lambda$null$12(GeodeConfiguration)
+ Integer lambda$null$9(GeodeConfiguration)
- Integer lambda$static$10(GeodeConfiguration)
- Integer lambda$static$12(GeodeConfiguration)
- Integer lambda$static$9(GeodeConfiguration)
+ IntProvider lambda$null$6(GeodeConfiguration)
+ IntProvider lambda$null$7(GeodeConfiguration)
+ IntProvider lambda$null$8(GeodeConfiguration)
- IntProvider lambda$static$6(GeodeConfiguration)
- IntProvider lambda$static$7(GeodeConfiguration)
- IntProvider lambda$static$8(GeodeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GrowingPlantConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$2(GrowingPlantConfiguration)
+ BlockStateProvider lambda$null$3(GrowingPlantConfiguration)
- BlockStateProvider lambda$static$2(GrowingPlantConfiguration)
- BlockStateProvider lambda$static$3(GrowingPlantConfiguration)
+ Boolean lambda$null$4(GrowingPlantConfiguration)
- Boolean lambda$static$4(GrowingPlantConfiguration)
+ Direction lambda$null$1(GrowingPlantConfiguration)
- Direction lambda$static$1(GrowingPlantConfiguration)
+ SimpleWeightedRandomList lambda$null$0(GrowingPlantConfiguration)
- SimpleWeightedRandomList lambda$static$0(GrowingPlantConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$0(HugeMushroomFeatureConfiguration)
+ BlockStateProvider lambda$null$1(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$static$0(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$static$1(HugeMushroomFeatureConfiguration)
+ Integer lambda$null$2(HugeMushroomFeatureConfiguration)
- Integer lambda$static$2(HugeMushroomFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
</summary>

```diff
+ Float lambda$null$3(LargeDripstoneConfiguration)
+ Float lambda$null$8(LargeDripstoneConfiguration)
- Float lambda$static$3(LargeDripstoneConfiguration)
- Float lambda$static$8(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$2(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$4(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$5(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- FloatProvider lambda$static$2(LargeDripstoneConfiguration)
- FloatProvider lambda$static$4(LargeDripstoneConfiguration)
- FloatProvider lambda$static$5(LargeDripstoneConfiguration)
- FloatProvider lambda$static$6(LargeDripstoneConfiguration)
+ Integer lambda$null$0(LargeDripstoneConfiguration)
+ Integer lambda$null$7(LargeDripstoneConfiguration)
- Integer lambda$static$0(LargeDripstoneConfiguration)
- Integer lambda$static$7(LargeDripstoneConfiguration)
+ IntProvider lambda$null$1(LargeDripstoneConfiguration)
- IntProvider lambda$static$1(LargeDripstoneConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
</summary>

```diff
+ Float lambda$null$0(MineshaftConfiguration)
- Float lambda$static$0(MineshaftConfiguration)
+ MineshaftFeature$Type lambda$null$1(MineshaftConfiguration)
- MineshaftFeature$Type lambda$static$1(MineshaftConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
</summary>

```diff
+ Float lambda$null$1(OceanRuinConfiguration)
+ Float lambda$null$2(OceanRuinConfiguration)
- Float lambda$static$1(OceanRuinConfiguration)
- Float lambda$static$2(OceanRuinConfiguration)
+ OceanRuinFeature$Type lambda$null$0(OceanRuinConfiguration)
- OceanRuinFeature$Type lambda$static$0(OceanRuinConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
</summary>

```diff
+ List lambda$null$0(ReplaceBlockConfiguration)
- List lambda$static$0(ReplaceBlockConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$4(RootSystemConfiguration)
+ BlockStateProvider lambda$null$9(RootSystemConfiguration)
- BlockStateProvider lambda$static$4(RootSystemConfiguration)
- BlockStateProvider lambda$static$9(RootSystemConfiguration)
+ Integer lambda$null$1(RootSystemConfiguration)
+ Integer lambda$null$10(RootSystemConfiguration)
+ Integer lambda$null$11(RootSystemConfiguration)
+ Integer lambda$null$2(RootSystemConfiguration)
+ Integer lambda$null$5(RootSystemConfiguration)
+ Integer lambda$null$6(RootSystemConfiguration)
+ Integer lambda$null$7(RootSystemConfiguration)
+ Integer lambda$null$8(RootSystemConfiguration)
- Integer lambda$static$1(RootSystemConfiguration)
- Integer lambda$static$10(RootSystemConfiguration)
- Integer lambda$static$11(RootSystemConfiguration)
- Integer lambda$static$2(RootSystemConfiguration)
- Integer lambda$static$5(RootSystemConfiguration)
- Integer lambda$static$6(RootSystemConfiguration)
- Integer lambda$static$7(RootSystemConfiguration)
- Integer lambda$static$8(RootSystemConfiguration)
+ ResourceLocation lambda$null$3(RootSystemConfiguration)
- ResourceLocation lambda$static$3(RootSystemConfiguration)
+ Supplier lambda$null$0(RootSystemConfiguration)
- Supplier lambda$static$0(RootSystemConfiguration)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
</summary>

```diff
+ Boolean lambda$null$0(SpikeConfiguration)
- Boolean lambda$static$0(SpikeConfiguration)
+ List lambda$null$1(SpikeConfiguration)
- List lambda$static$1(SpikeConfiguration)
+ Optional lambda$null$2(SpikeConfiguration)
- Optional lambda$static$2(SpikeConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$0(TreeConfiguration)
+ BlockStateProvider lambda$null$2(TreeConfiguration)
+ BlockStateProvider lambda$null$4(TreeConfiguration)
- BlockStateProvider lambda$static$0(TreeConfiguration)
- BlockStateProvider lambda$static$2(TreeConfiguration)
- BlockStateProvider lambda$static$4(TreeConfiguration)
+ Boolean lambda$null$7(TreeConfiguration)
+ Boolean lambda$null$8(TreeConfiguration)
- Boolean lambda$static$7(TreeConfiguration)
- Boolean lambda$static$8(TreeConfiguration)
+ FeatureSize lambda$null$5(TreeConfiguration)
- FeatureSize lambda$static$5(TreeConfiguration)
+ FoliagePlacer lambda$null$3(TreeConfiguration)
- FoliagePlacer lambda$static$3(TreeConfiguration)
+ List lambda$null$6(TreeConfiguration)
- List lambda$static$6(TreeConfiguration)
+ TrunkPlacer lambda$null$1(TreeConfiguration)
- TrunkPlacer lambda$static$1(TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
</summary>

```diff
+ Float lambda$null$2(UnderwaterMagmaConfiguration)
- Float lambda$static$2(UnderwaterMagmaConfiguration)
+ Integer lambda$null$0(UnderwaterMagmaConfiguration)
+ Integer lambda$null$1(UnderwaterMagmaConfiguration)
- Integer lambda$static$0(UnderwaterMagmaConfiguration)
- Integer lambda$static$1(UnderwaterMagmaConfiguration)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
</summary>

```diff
+ Integer lambda$null$0(TwoLayersFeatureSize)
+ Integer lambda$null$1(TwoLayersFeatureSize)
+ Integer lambda$null$2(TwoLayersFeatureSize)
- Integer lambda$static$0(TwoLayersFeatureSize)
- Integer lambda$static$1(TwoLayersFeatureSize)
- Integer lambda$static$2(TwoLayersFeatureSize)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
</summary>

```diff
+ Integer lambda$null$0(MegaJungleFoliagePlacer)
- Integer lambda$static$0(MegaJungleFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
</summary>

```diff
+ IntProvider lambda$null$0(PineFoliagePlacer)
- IntProvider lambda$static$0(PineFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
</summary>

```diff
+ IntProvider lambda$null$0(SpruceFoliagePlacer)
- IntProvider lambda$static$0(SpruceFoliagePlacer)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
</summary>

```diff
+ void <init>(JunglePyramidPiece$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces
</summary>

```diff
+ Logger access$000()
+ MineShaftPieces$MineShaftPiece access$100(StructurePiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
















<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
</summary>

```diff
+ boolean access$100(OceanMonumentPieces$RoomDefinition)
+ boolean access$102(OceanMonumentPieces$RoomDefinition,boolean)
+ boolean access$902(OceanMonumentPieces$RoomDefinition,boolean)
+ boolean[] access$1100(OceanMonumentPieces$RoomDefinition)
+ int access$000(OceanMonumentPieces$RoomDefinition)
+ OceanMonumentPieces$RoomDefinition[] access$1000(OceanMonumentPieces$RoomDefinition)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
</summary>

```diff
- RuinedPortalPiece$VerticalPlacement[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.ShipwreckPieces
</summary>

```diff
+ BlockPos access$000()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces
</summary>

```diff
+ Class access$102(Class)
+ StrongholdPieces$SmoothStoneSelector access$200()
+ StructurePiece access$000(StrongholdPieces$StartPiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
</summary>

```diff
+ void <init>(StrongholdPieces$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
</summary>

```diff
- StrongholdPieces$StrongholdPiece$SmallDoorType[] $values()
```

</details>





<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
</summary>

```diff
+ Packet access$200(MapItemSavedData$HoldingPlayer,int)
+ void <init>(MapItemSavedData,Player,MapItemSavedData$1)
+ void access$300(MapItemSavedData$HoldingPlayer,int,int)
+ void access$400(MapItemSavedData$HoldingPlayer)
```

</details>



<details>
<summary>
net.minecraft.world.level.storage.loot.IntRange
</summary>

```diff
+ NumberProvider access$100(IntRange)
+ NumberProvider access$200(IntRange)
+ void <init>(NumberProvider,NumberProvider,IntRange$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.LootPool
</summary>

```diff
+ LootItemCondition[] access$400(LootPool)
+ LootItemFunction[] access$500(LootPool)
+ LootPoolEntryContainer[] access$300(LootPool)
+ NumberProvider access$100(LootPool)
+ NumberProvider access$200(LootPool)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],NumberProvider,NumberProvider,LootPool$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.entries.EmptyLootItem
</summary>

```diff
+ void <init>(int,int,LootItemCondition[],LootItemFunction[],EmptyLootItem$1)
```

</details>



<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
</summary>

```diff
+ BiFunction access$000(LootPoolSingletonContainer)
```

</details>






<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
</summary>

```diff
+ void <init>(LootItemCondition[],ApplyExplosionDecay$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
</summary>

```diff
+ void <init>(String,String,CopyNbtFunction$MergeStrategy,CopyNbtFunction$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
</summary>

```diff
- void lambda$merge$0(Tag,Tag)
+ void lambda$null$0(Tag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
</summary>

```diff
+ List access$100(EnchantRandomlyFunction)
+ void <init>(LootItemCondition[],Collection,EnchantRandomlyFunction$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
</summary>

```diff
+ boolean access$500(ExplorationMapFunction)
+ byte access$300(ExplorationMapFunction)
+ int access$400(ExplorationMapFunction)
+ Logger access$600()
+ MapDecoration$Type access$200(ExplorationMapFunction)
+ StructureFeature access$100(ExplorationMapFunction)
+ void <init>(LootItemCondition[],StructureFeature,MapDecoration$Type,byte,int,boolean,ExplorationMapFunction$1)
```

</details>




<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
</summary>

```diff
+ boolean access$200(LootingEnchantFunction)
+ int access$300(LootingEnchantFunction)
+ NumberProvider access$100(LootingEnchantFunction)
+ void <init>(LootItemCondition[],NumberProvider,int,LootingEnchantFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
</summary>

```diff
+ void <init>(boolean,SetBannerPatternFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetContainerContents
</summary>

```diff
+ List access$100(SetContainerContents)
+ void <init>(LootItemCondition[],List,SetContainerContents$1)
+ void lambda$null$0(NonNullList,LootContext,LootPoolEntry)
- void lambda$run$0(NonNullList,LootContext,LootPoolEntry)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
</summary>

```diff
+ boolean access$100(SetItemDamageFunction)
+ NumberProvider access$000(SetItemDamageFunction)
+ void <init>(LootItemCondition[],NumberProvider,boolean,SetItemDamageFunction$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
</summary>

```diff
+ void <init>(LootItemCondition[],SmeltItemFunction$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
</summary>

```diff
+ LootItemCondition[] access$100(AlternativeLootItemCondition)
+ void <init>(LootItemCondition[],AlternativeLootItemCondition$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
</summary>

```diff
+ LootContext$EntityTarget access$200(EntityHasScoreCondition)
+ Map access$100(EntityHasScoreCondition)
+ void <init>(Map,LootContext$EntityTarget,EntityHasScoreCondition$1)
```

</details>




<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
</summary>

```diff
+ EntityPredicate access$000(LootItemEntityPropertyCondition)
+ LootContext$EntityTarget access$100(LootItemEntityPropertyCondition)
+ void <init>(EntityPredicate,LootContext$EntityTarget,LootItemEntityPropertyCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
</summary>

```diff
+ float access$000(LootItemRandomChanceWithLootingCondition)
+ float access$100(LootItemRandomChanceWithLootingCondition)
+ void <init>(float,float,LootItemRandomChanceWithLootingCondition$1)
```

</details>







<details>
<summary>
net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
</summary>

```diff
+ ResourceLocation access$000(StorageNbtProvider)
+ void <init>(ResourceLocation,StorageNbtProvider$1)
```

</details>



<details>
<summary>
net.minecraft.world.level.timers.TimerQueue$Event
</summary>

```diff
+ void <init>(long,UnsignedLong,String,TimerCallback,TimerQueue$1)
```

</details>














<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
- boolean lambda$joinIsNotEmpty$1(BooleanOp,DiscreteVoxelShape,int,int,DiscreteVoxelShape,int,int,int,int,int)
- boolean lambda$joinIsNotEmpty$2(IndexMerger,BooleanOp,DiscreteVoxelShape,int,DiscreteVoxelShape,int,int,int,int)
+ boolean lambda$null$1(BooleanOp,DiscreteVoxelShape,int,int,DiscreteVoxelShape,int,int,int,int,int)
+ boolean lambda$null$2(IndexMerger,BooleanOp,DiscreteVoxelShape,int,DiscreteVoxelShape,int,int,int,int)
```

</details>





<details>
<summary>
net.minecraft.world.scores.Team$CollisionRule
</summary>

```diff
- Team$CollisionRule[] $values()
```

</details>


<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ com.mojang.blaze3d.font.package-info
+ com.mojang.blaze3d.font.TrueTypeGlyphProvider$1
- com.mojang.blaze3d.font.TrueTypeGlyphProvider$Glyph
- com.mojang.blaze3d.package-info
- com.mojang.blaze3d.pipeline.MainTarget$AttachmentState
- com.mojang.blaze3d.pipeline.package-info
+ com.mojang.blaze3d.platform.ClipboardManager
- com.mojang.blaze3d.platform.DebugMemoryUntracker
+ com.mojang.blaze3d.platform.DisplayData
+ com.mojang.blaze3d.platform.GlConst
- com.mojang.blaze3d.platform.GlDebug
+ com.mojang.blaze3d.platform.GlDebug$1
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
+ com.mojang.blaze3d.platform.InputConstants
+ com.mojang.blaze3d.platform.NativeImage$Format
- com.mojang.blaze3d.platform.NativeImage$InternalGlFormat
+ com.mojang.blaze3d.platform.NativeImage$WriteCallback
+ com.mojang.blaze3d.platform.package-info
- com.mojang.blaze3d.platform.PngInfo
+ com.mojang.blaze3d.platform.PngInfo$1
+ com.mojang.blaze3d.platform.Window$WindowInitFailed
- com.mojang.blaze3d.platform.WindowEventHandler
- com.mojang.blaze3d.preprocessor.GlslPreprocessor
+ com.mojang.blaze3d.preprocessor.GlslPreprocessor$1
+ com.mojang.blaze3d.vertex.package-info
+ com.mojang.blaze3d.vertex.PoseStack$1
- com.mojang.blaze3d.vertex.PoseStack$Pose
+ com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
- com.mojang.blaze3d.vertex.Tesselator
+ com.mojang.blaze3d.vertex.VertexBuffer
- com.mojang.blaze3d.vertex.VertexConsumer
+ com.mojang.blaze3d.vertex.VertexFormat
- com.mojang.blaze3d.vertex.VertexFormat$1
+ com.mojang.blaze3d.vertex.VertexFormat$IndexType
- com.mojang.blaze3d.vertex.VertexFormat$Mode
+ com.mojang.blaze3d.vertex.VertexFormatElement
- com.mojang.blaze3d.vertex.VertexFormatElement$Type
+ com.mojang.blaze3d.vertex.VertexFormatElement$Usage
- com.mojang.blaze3d.vertex.VertexFormatElement$Usage$ClearState
+ com.mojang.blaze3d.vertex.VertexFormatElement$Usage$SetupState
- com.mojang.blaze3d.vertex.VertexMultiConsumer
+ com.mojang.blaze3d.vertex.VertexMultiConsumer$Double
- com.mojang.blaze3d.vertex.VertexMultiConsumer$Multiple
- com.mojang.math.Constants
+ com.mojang.math.FieldsAreNonnullByDefault
- com.mojang.math.Matrix3f
+ com.mojang.math.Matrix4f
- com.mojang.math.MethodsReturnNonnullByDefault
+ com.mojang.math.OctahedralGroup
- com.mojang.math.OctahedralGroup$1
+ com.mojang.math.package-info
+ com.mojang.math.Quaternion
- com.mojang.math.SymmetricGroup3
+ com.mojang.math.Transformation
- com.mojang.math.Vector3d
+ com.mojang.math.Vector3f
- com.mojang.math.Vector4f
+ com.mojang.realmsclient.client.FileDownload
+ com.mojang.realmsclient.gui.screens.package-info
+ com.mojang.realmsclient.gui.screens.UploadResult$1
- com.mojang.realmsclient.gui.screens.UploadResult$Builder
- com.mojang.realmsclient.gui.task.IntervalBasedStartupDelay
+ com.mojang.realmsclient.gui.task.NoStartupDelay
- com.mojang.realmsclient.gui.task.package-info
- com.mojang.realmsclient.gui.task.RepeatableTask
+ com.mojang.realmsclient.gui.task.RestartDelayCalculator
- com.mojang.realmsclient.KeyCombo
+ com.mojang.realmsclient.package-info
+ com.mojang.realmsclient.RealmsMainScreen
- com.mojang.realmsclient.RealmsMainScreen$1
+ com.mojang.realmsclient.RealmsMainScreen$2
- com.mojang.realmsclient.RealmsMainScreen$3
+ com.mojang.realmsclient.RealmsMainScreen$4
- com.mojang.realmsclient.RealmsMainScreen$5
+ com.mojang.realmsclient.RealmsMainScreen$CloseButton
- com.mojang.realmsclient.RealmsMainScreen$Entry
+ com.mojang.realmsclient.RealmsMainScreen$HoveredElement
- com.mojang.realmsclient.RealmsMainScreen$NewsButton
+ com.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ com.mojang.realmsclient.RealmsMainScreen$ServerEntry
- com.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
+ com.mojang.realmsclient.RealmsMainScreen$TrialEntry
- com.mojang.realmsclient.Unit
- com.mojang.realmsclient.util.JsonUtils
+ com.mojang.realmsclient.util.LevelType
+ com.mojang.realmsclient.util.package-info
- com.mojang.realmsclient.util.RealmsPersistence
+ com.mojang.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- com.mojang.realmsclient.util.RealmsTextureManager
+ com.mojang.realmsclient.util.RealmsTextureManager$1
- com.mojang.realmsclient.util.RealmsTextureManager$RealmsTexture
+ com.mojang.realmsclient.util.RealmsUtil
- com.mojang.realmsclient.util.RealmsUtil$1
+ com.mojang.realmsclient.util.SkinProcessor
- com.mojang.realmsclient.util.task.CloseServerTask
+ com.mojang.realmsclient.util.task.ConnectTask
- com.mojang.realmsclient.util.task.DownloadTask
+ com.mojang.realmsclient.util.task.GetServerDetailsTask
- com.mojang.realmsclient.util.task.LongRunningTask
+ com.mojang.realmsclient.util.task.OpenServerTask
+ com.mojang.realmsclient.util.task.package-info
- com.mojang.realmsclient.util.task.ResettingGeneratedWorldTask
+ com.mojang.realmsclient.util.task.ResettingTemplateWorldTask
- com.mojang.realmsclient.util.task.ResettingWorldTask
+ com.mojang.realmsclient.util.task.RestoreTask
- com.mojang.realmsclient.util.task.SwitchMinigameTask
+ com.mojang.realmsclient.util.task.SwitchSlotTask
- com.mojang.realmsclient.util.task.WorldCreationTask
- com.mojang.realmsclient.util.TextRenderingUtils
+ com.mojang.realmsclient.util.TextRenderingUtils$Line
- com.mojang.realmsclient.util.TextRenderingUtils$LineSegment
+ com.mojang.realmsclient.util.UploadTokenCache
- com.mojang.realmsclient.util.WorldGenerationInfo
+ net.minecraft.advancements.Advancement
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
- net.minecraft.BlockUtil
+ net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.CharPredicate
- net.minecraft.ChatFormatting
+ net.minecraft.client.Camera$NearPlane
- net.minecraft.client.CameraType
+ net.minecraft.client.ClientBrandRetriever
- net.minecraft.client.ClientRecipeBook
+ net.minecraft.client.CloudStatus
+ net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
- net.minecraft.client.color.block.package-info
+ net.minecraft.client.color.item.ItemColor
- net.minecraft.client.color.item.ItemColors
+ net.minecraft.client.color.item.package-info
- net.minecraft.client.ComponentCollector
+ net.minecraft.client.CycleOption
- net.minecraft.client.CycleOption$OptionSetter
+ net.minecraft.client.DebugQueryHandler
- net.minecraft.client.FullscreenResolutionProgressOption
+ net.minecraft.client.Game
- net.minecraft.client.Game$Metrics
+ net.minecraft.client.GraphicsStatus
- net.minecraft.client.GraphicsStatus$1
+ net.minecraft.client.gui.components.AbstractSelectionList$1
- net.minecraft.client.gui.components.AbstractSelectionList$Entry
+ net.minecraft.client.gui.components.AbstractSelectionList$SelectionDirection
- net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
+ net.minecraft.client.gui.components.AbstractSliderButton
- net.minecraft.client.gui.components.AbstractWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.BossHealthOverlay$1
+ net.minecraft.client.gui.components.Button
- net.minecraft.client.gui.components.Button$OnPress
+ net.minecraft.client.gui.components.Button$OnTooltip
- net.minecraft.client.gui.components.ChatComponent
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$1
+ net.minecraft.client.gui.components.CycleButton$1
- net.minecraft.client.gui.components.CycleButton$Builder
+ net.minecraft.client.gui.components.CycleButton$OnValueChange
- net.minecraft.client.gui.components.CycleButton$TooltipSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
- net.minecraft.client.gui.components.DebugScreenOverlay
+ net.minecraft.client.gui.components.DebugScreenOverlay$1
- net.minecraft.client.gui.components.EditBox
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.LerpingBossEvent
+ net.minecraft.client.gui.components.LockIconButton
- net.minecraft.client.gui.components.LockIconButton$Icon
+ net.minecraft.client.gui.components.MultiLineLabel
- net.minecraft.client.gui.components.MultiLineLabel$1
+ net.minecraft.client.gui.components.MultiLineLabel$2
- net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
+ net.minecraft.client.gui.components.ObjectSelectionList
- net.minecraft.client.gui.components.ObjectSelectionList$Entry
+ net.minecraft.client.gui.components.OptionsList
- net.minecraft.client.gui.components.OptionsList$Entry
+ net.minecraft.client.gui.components.PlayerTabOverlay
- net.minecraft.client.gui.components.toasts.package-info
+ net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
- net.minecraft.client.gui.components.toasts.TutorialToast
+ net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.Font
+ net.minecraft.client.gui.font.AllMissingGlyphProvider
- net.minecraft.client.gui.font.FontManager
+ net.minecraft.client.gui.font.FontManager$1
- net.minecraft.client.gui.font.FontSet
+ net.minecraft.client.gui.font.FontTexture
+ net.minecraft.client.gui.font.providers.BitmapProvider$1
- net.minecraft.client.gui.font.providers.BitmapProvider$Builder
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
- net.minecraft.client.gui.font.providers.GlyphProviderBuilder
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$1
+ net.minecraft.client.gui.Font$StringRenderOutput
- net.minecraft.client.gui.Gui
+ net.minecraft.client.gui.GuiComponent
- net.minecraft.client.gui.MapRenderer
+ net.minecraft.client.gui.MapRenderer$1
+ net.minecraft.client.gui.screens.achievement.package-info
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- net.minecraft.client.gui.screens.achievement.StatsUpdateListener
+ net.minecraft.client.gui.screens.advancements.AdvancementsScreen
- net.minecraft.client.gui.screens.advancements.AdvancementTab
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType
- net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
+ net.minecraft.client.gui.screens.advancements.AdvancementWidget
- net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
- net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.controls.ControlList
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$1
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- net.minecraft.client.gui.screens.CreateFlatWorldScreen
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$1
+ net.minecraft.client.GuiMessage
- net.minecraft.client.HotbarManager
- net.minecraft.client.KeyboardHandler
+ net.minecraft.client.KeyboardHandler$1
+ net.minecraft.client.KeyMapping
- net.minecraft.client.LogaritmicProgressOption
+ net.minecraft.client.Minecraft
- net.minecraft.client.Minecraft$1
+ net.minecraft.client.Minecraft$ChatStatus
- net.minecraft.client.Minecraft$ChatStatus$1
+ net.minecraft.client.Minecraft$ChatStatus$2
- net.minecraft.client.Minecraft$ChatStatus$3
+ net.minecraft.client.Minecraft$ChatStatus$4
- net.minecraft.client.Minecraft$ExperimentalDialogType
+ net.minecraft.client.Minecraft$ServerStem
- net.minecraft.client.MouseHandler
+ net.minecraft.client.multiplayer.ClientChunkCache$Storage
- net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
+ net.minecraft.client.multiplayer.ClientLevel
- net.minecraft.client.multiplayer.ClientLevel$1
+ net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
- net.minecraft.client.multiplayer.ClientLevel$EntityCallbacks
+ net.minecraft.client.multiplayer.ClientLevel$MarkerParticleStatus
- net.minecraft.client.multiplayer.ClientPacketListener
+ net.minecraft.client.multiplayer.ClientPacketListener$1
- net.minecraft.client.multiplayer.ClientSuggestionProvider
+ net.minecraft.client.multiplayer.MultiPlayerGameMode
- net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.resolver.ResolvedServerAddress$1
- net.minecraft.client.multiplayer.resolver.ServerAddressResolver
- net.minecraft.client.multiplayer.resolver.ServerRedirectHandler
+ net.minecraft.client.multiplayer.ServerAddress
+ net.minecraft.client.NarratorStatus
- net.minecraft.client.Option
+ net.minecraft.client.Option$1
- net.minecraft.client.Options
+ net.minecraft.client.Options$1
- net.minecraft.client.Options$2
+ net.minecraft.client.Options$3
- net.minecraft.client.Options$4
+ net.minecraft.client.Options$FieldAccess
- net.minecraft.client.package-info
+ net.minecraft.client.particle.AshParticle
- net.minecraft.client.particle.AshParticle$Provider
+ net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.BreakingItemParticle$Provider
- net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
+ net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
- net.minecraft.client.particle.BubbleColumnUpParticle
+ net.minecraft.client.particle.BubbleColumnUpParticle$1
+ net.minecraft.client.particle.BubbleParticle$Provider
- net.minecraft.client.particle.BubblePopParticle
+ net.minecraft.client.particle.BubblePopParticle$1
+ net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
- net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
+ net.minecraft.client.particle.CritParticle
+ net.minecraft.client.particle.DragonBreathParticle$1
- net.minecraft.client.particle.DragonBreathParticle$Provider
+ net.minecraft.client.particle.DripParticle
+ net.minecraft.client.particle.EnchantmentTableParticle$1
- net.minecraft.client.particle.EnchantmentTableParticle$NautilusProvider
+ net.minecraft.client.particle.EnchantmentTableParticle$Provider
- net.minecraft.client.particle.EndRodParticle
+ net.minecraft.client.particle.EndRodParticle$1
+ net.minecraft.client.particle.FallingDustParticle$Provider
- net.minecraft.client.particle.FireworkParticles
+ net.minecraft.client.particle.FireworkParticles$1
- net.minecraft.client.particle.FireworkParticles$FlashProvider
+ net.minecraft.client.particle.FireworkParticles$OverlayParticle
- net.minecraft.client.particle.FireworkParticles$SparkParticle
+ net.minecraft.client.particle.FireworkParticles$SparkProvider
- net.minecraft.client.particle.FireworkParticles$Starter
+ net.minecraft.client.particle.FlameParticle
+ net.minecraft.client.particle.GlowParticle$ElectricSparkProvider
- net.minecraft.client.particle.GlowParticle$GlowSquidProvider
+ net.minecraft.client.particle.GlowParticle$ScrapeProvider
- net.minecraft.client.particle.GlowParticle$WaxOffProvider
+ net.minecraft.client.particle.GlowParticle$WaxOnProvider
- net.minecraft.client.particle.HeartParticle
+ net.minecraft.client.particle.HeartParticle$1
+ net.minecraft.client.particle.HugeExplosionParticle$1
- net.minecraft.client.particle.HugeExplosionParticle$Provider
+ net.minecraft.client.particle.HugeExplosionSeedParticle
+ net.minecraft.client.particle.LavaParticle$Provider
- net.minecraft.client.particle.MobAppearanceParticle
+ net.minecraft.client.particle.MobAppearanceParticle$1
+ net.minecraft.client.particle.NoteParticle$1
- net.minecraft.client.particle.NoteParticle$Provider
+ net.minecraft.client.particle.Particle
- net.minecraft.client.particle.ParticleDescription
+ net.minecraft.client.particle.ParticleEngine
+ net.minecraft.client.particle.PlayerCloudParticle$Provider
- net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
+ net.minecraft.client.particle.PortalParticle
- net.minecraft.client.particle.PortalParticle$Provider
+ net.minecraft.client.particle.ReversePortalParticle
+ net.minecraft.client.particle.SoulParticle$Provider
- net.minecraft.client.particle.SpellParticle
+ net.minecraft.client.particle.SpellParticle$1
+ net.minecraft.client.particle.SpitParticle$Provider
- net.minecraft.client.particle.SplashParticle
+ net.minecraft.client.particle.SplashParticle$1
+ net.minecraft.client.particle.SquidInkParticle$1
- net.minecraft.client.particle.SquidInkParticle$GlowInkProvider
+ net.minecraft.client.particle.SquidInkParticle$Provider
- net.minecraft.client.particle.StationaryItemParticle
+ net.minecraft.client.particle.StationaryItemParticle$1
+ net.minecraft.client.particle.SuspendedParticle$1
- net.minecraft.client.particle.SuspendedParticle$CrimsonSporeProvider
+ net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider
- net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
+ net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
- net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
+ net.minecraft.client.particle.SuspendedTownParticle
+ net.minecraft.client.particle.TotemParticle$1
- net.minecraft.client.particle.TotemParticle$Provider
+ net.minecraft.client.particle.TrackingEmitter
- net.minecraft.client.particle.VibrationSignalParticle
+ net.minecraft.client.particle.VibrationSignalParticle$1
+ net.minecraft.client.particle.WakeParticle$Provider
- net.minecraft.client.particle.WaterCurrentDownParticle
+ net.minecraft.client.particle.WaterCurrentDownParticle$1
- net.minecraft.client.ParticleStatus
+ net.minecraft.client.profiling.metric.MetricSampler$MetricSamplerBuilder
- net.minecraft.client.profiling.metric.MetricSampler$ThresholdAlerter
+ net.minecraft.client.profiling.metric.MetricSampler$ValueIncreased
- net.minecraft.client.profiling.metric.package-info
- net.minecraft.client.profiling.metric.SamplerCategory
+ net.minecraft.client.profiling.metric.TaskSamplerBuilder
+ net.minecraft.client.profiling.package-info
- net.minecraft.client.profiling.storage.MetricsPersister
+ net.minecraft.client.profiling.storage.package-info
+ net.minecraft.client.ProgressOption
- net.minecraft.client.RecipeBookCategories
+ net.minecraft.client.RecipeBookCategories$1
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
+ net.minecraft.client.renderer.block.model.ItemOverride$Predicate
- net.minecraft.client.renderer.block.model.ItemOverrides
+ net.minecraft.client.renderer.block.model.ItemOverrides$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer
- net.minecraft.client.renderer.block.ModelBlockRenderer$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
+ net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
+ net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
- net.minecraft.client.renderer.ChunkBufferBuilderPack
+ net.minecraft.client.renderer.CubeMap
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
+ net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
+ net.minecraft.client.renderer.debug.package-info
- net.minecraft.client.renderer.debug.PathfindingRenderer
+ net.minecraft.client.renderer.debug.RaidDebugRenderer
- net.minecraft.client.renderer.debug.SolidFaceRenderer
+ net.minecraft.client.renderer.debug.StructureRenderer
- net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
+ net.minecraft.client.renderer.debug.WaterDebugRenderer
- net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
- net.minecraft.client.renderer.DimensionSpecialEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
+ net.minecraft.client.renderer.EffectInstance
- net.minecraft.client.renderer.entity.AbstractHorseRenderer
+ net.minecraft.client.renderer.entity.AbstractZombieRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
- net.minecraft.client.renderer.entity.AxolotlRenderer
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
+ net.minecraft.client.renderer.entity.EntityRendererProvider
- net.minecraft.client.renderer.entity.EntityRendererProvider$Context
+ net.minecraft.client.renderer.entity.EntityRenderers
- net.minecraft.client.renderer.entity.EvokerFangsRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer$1
+ net.minecraft.client.renderer.entity.ExperienceOrbRenderer
- net.minecraft.client.renderer.entity.FallingBlockRenderer
+ net.minecraft.client.renderer.entity.FireworkEntityRenderer
- net.minecraft.client.renderer.entity.FishingHookRenderer
+ net.minecraft.client.renderer.entity.FoxRenderer
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
- net.minecraft.client.renderer.entity.LeashKnotRenderer
+ net.minecraft.client.renderer.entity.LightningBoltRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer$1
- net.minecraft.client.renderer.entity.LlamaRenderer
+ net.minecraft.client.renderer.entity.LlamaSpitRenderer
- net.minecraft.client.renderer.entity.MagmaCubeRenderer
+ net.minecraft.client.renderer.entity.MinecartRenderer
- net.minecraft.client.renderer.entity.MobRenderer
+ net.minecraft.client.renderer.entity.MushroomCowRenderer
- net.minecraft.client.renderer.entity.NoopRenderer
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
- net.minecraft.client.renderer.FaceInfo
+ net.minecraft.client.renderer.FaceInfo$1
+ net.minecraft.client.renderer.GpuWarnlistManager$Preparations
- net.minecraft.client.renderer.item.ItemProperties
+ net.minecraft.client.renderer.item.ItemProperties$1
- net.minecraft.client.renderer.item.ItemProperties$2
+ net.minecraft.client.renderer.item.ItemProperties$CompassWobble
- net.minecraft.client.renderer.item.ItemPropertyFunction
+ net.minecraft.client.renderer.item.package-info
- net.minecraft.client.renderer.ItemBlockRenderTypes
+ net.minecraft.client.renderer.ItemInHandRenderer
- net.minecraft.client.renderer.ItemInHandRenderer$1
+ net.minecraft.client.renderer.ItemInHandRenderer$HandRenderSelection
- net.minecraft.client.renderer.ItemModelShaper
+ net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.package-info
- net.minecraft.client.renderer.PanoramaRenderer
+ net.minecraft.client.renderer.PostChain
- net.minecraft.client.renderer.PostPass
+ net.minecraft.client.renderer.Rect2i
- net.minecraft.client.renderer.RenderBuffers
+ net.minecraft.client.renderer.RenderStateShard
+ net.minecraft.client.renderer.RenderType$1
- net.minecraft.client.renderer.RenderType$CompositeRenderType
+ net.minecraft.client.renderer.RenderType$CompositeState
- net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ net.minecraft.client.renderer.RenderType$OutlineProperty
- net.minecraft.client.renderer.RunningTrimmedMean
+ net.minecraft.client.renderer.ScreenEffectRenderer
- net.minecraft.client.renderer.ShaderInstance
+ net.minecraft.client.renderer.ShaderInstance$1
- net.minecraft.client.renderer.Sheets
+ net.minecraft.client.renderer.Sheets$1
- net.minecraft.client.renderer.SpriteCoordinateExpander
+ net.minecraft.client.renderer.texture.AbstractTexture
- net.minecraft.client.renderer.texture.AtlasSet
+ net.minecraft.client.renderer.texture.DynamicTexture
- net.minecraft.client.renderer.texture.HttpTexture
+ net.minecraft.client.renderer.texture.MipmapGenerator
- net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
+ net.minecraft.client.renderer.texture.OverlayTexture
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
+ net.minecraft.client.renderer.ViewArea
- net.minecraft.client.renderer.VirtualScreen
- net.minecraft.client.ResourceLoadStateTracker
+ net.minecraft.client.ResourceLoadStateTracker$1
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
+ net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
- net.minecraft.client.tutorial.Tutorial
+ net.minecraft.client.tutorial.Tutorial$1
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
+ net.minecraft.commands.arguments.DimensionArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Serializer
- net.minecraft.commands.arguments.EntitySummonArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
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
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
- net.minecraft.commands.arguments.selector.options.package-info
+ net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.SlotArgument
+ net.minecraft.commands.arguments.TeamArgument
- net.minecraft.commands.arguments.TimeArgument
+ net.minecraft.commands.arguments.UuidArgument
- net.minecraft.commands.package-info
+ net.minecraft.commands.synchronization.ArgumentSerializer
- net.minecraft.commands.synchronization.ArgumentTypes
+ net.minecraft.commands.synchronization.ArgumentTypes$1
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
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
+ net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.MultiPartGenerator$1
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.PropertyDispatch
- net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.ModelProvider
- net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.data.worldgen.BastionBridgePools
- net.minecraft.data.worldgen.BastionHoglinStablePools
+ net.minecraft.data.worldgen.BastionHousingUnitsPools
- net.minecraft.data.worldgen.BastionPieces
+ net.minecraft.data.worldgen.BastionSharedPools
- net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.biome.BiomeReport
+ net.minecraft.data.worldgen.biome.Biomes
+ net.minecraft.data.worldgen.biome.package-info
- net.minecraft.data.worldgen.biome.VanillaBiomes
+ net.minecraft.data.worldgen.BiomeDefaultFeatures
- net.minecraft.data.worldgen.Carvers
+ net.minecraft.data.worldgen.DesertVillagePools
- net.minecraft.data.worldgen.Features
+ net.minecraft.data.worldgen.Features$Configs
- net.minecraft.data.worldgen.Features$Decorators
+ net.minecraft.data.worldgen.Features$States
- net.minecraft.data.worldgen.PillagerOutpostPools
+ net.minecraft.data.worldgen.PlainVillagePools
- net.minecraft.data.worldgen.Pools
+ net.minecraft.data.worldgen.ProcessorLists
- net.minecraft.data.worldgen.SavannaVillagePools
+ net.minecraft.data.worldgen.SnowyVillagePools
- net.minecraft.data.worldgen.StructureFeatures
+ net.minecraft.data.worldgen.SurfaceBuilders
- net.minecraft.data.worldgen.TaigaVillagePools
+ net.minecraft.data.worldgen.VillagePools
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.FieldsAreNonnullByDefault
+ net.minecraft.FileUtil
- net.minecraft.gametest.framework.AfterBatch
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.ExhaustedAttemptsException
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestHelper$1
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
+ net.minecraft.gametest.framework.GlobalTestReporter
- net.minecraft.gametest.framework.JUnitLikeTestReporter
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.gametest.framework.package-info
- net.minecraft.gametest.framework.ReportGameListener
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
- net.minecraft.MethodsReturnNonnullByDefault
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
+ net.minecraft.nbt.SnbtPrinterTagVisitor
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.StringTagVisitor
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagTypes
- net.minecraft.nbt.TagVisitor
+ net.minecraft.nbt.TextComponentTagVisitor
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
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
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
- net.minecraft.network.protocol.game.ClientboundInitializeBorderPacket
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
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$2
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$3
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$4
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$5
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundResourcePackPacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
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
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
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
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundClientInformationPacket
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
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
- net.minecraft.network.protocol.game.ServerboundPongPacket
- net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.realms.package-info
+ net.minecraft.realms.RealmsServerAddress
- net.minecraft.realms.RepeatedNarrator
+ net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
- net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.RegistryDataPackCodec
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryLookupCodec
- net.minecraft.resources.RegistryReadOps
+ net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.server.ChainedJsonException$Entry
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
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.package-info
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
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.Eula
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
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
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
+ net.minecraft.server.packs.resources.package-info
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
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
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
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$1
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
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
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
- net.minecraft.Util
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
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
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
+ net.minecraft.util.datafix.schemas.package-info
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
+ net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
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
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.ExtraCodecs
- net.minecraft.util.ExtraCodecs$XorCodec
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FormattedCharSequence
- net.minecraft.util.FormattedCharSink
+ net.minecraft.util.FrameTimer
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HeapDumper
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
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
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.valueproviders.BiasedToBottomInt
- net.minecraft.util.valueproviders.ClampedInt
+ net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
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
- net.minecraft.world.BossEvent
+ net.minecraft.world.BossEvent$BossBarColor
- net.minecraft.world.BossEvent$BossBarOverlay
+ net.minecraft.world.Clearable
- net.minecraft.world.CompoundContainer
+ net.minecraft.world.Container
- net.minecraft.world.ContainerHelper
+ net.minecraft.world.ContainerListener
- net.minecraft.world.Containers
- net.minecraft.world.damagesource.BadRespawnPointDamage
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.EntityDamageSource
- net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
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
+ net.minecraft.world.entity.ai.behavior.AnimalPanic
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
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
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
- net.minecraft.world.entity.ai.behavior.TryFindWater
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
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
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
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.goat.Goat
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
- net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
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
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.boss.enderdragon.EndCrystal
+ net.minecraft.world.entity.boss.enderdragon.EnderDragon
- net.minecraft.world.entity.boss.enderdragon.package-info
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
+ net.minecraft.world.entity.boss.enderdragon.phases.package-info
+ net.minecraft.world.entity.boss.EnderDragonPart
- net.minecraft.world.entity.boss.package-info
+ net.minecraft.world.entity.boss.wither.package-info
+ net.minecraft.world.entity.boss.wither.WitherBoss
- net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
- net.minecraft.world.entity.decoration.ArmorStand
+ net.minecraft.world.entity.decoration.ArmorStand$1
- net.minecraft.world.entity.decoration.GlowItemFrame
+ net.minecraft.world.entity.decoration.HangingEntity
- net.minecraft.world.entity.decoration.HangingEntity$1
+ net.minecraft.world.entity.decoration.ItemFrame
- net.minecraft.world.entity.decoration.ItemFrame$1
+ net.minecraft.world.entity.decoration.ItemFrame$2
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
+ net.minecraft.world.entity.decoration.Motive
+ net.minecraft.world.entity.decoration.package-info
- net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
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
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.item.FallingBlockEntity
+ net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.Marker
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.CaveSpider
- net.minecraft.world.entity.monster.Creeper
+ net.minecraft.world.entity.monster.CrossbowAttackMob
- net.minecraft.world.entity.monster.Drowned
+ net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
- net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
+ net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
- net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
+ net.minecraft.world.entity.monster.ElderGuardian
- net.minecraft.world.entity.monster.EnderMan
+ net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
+ net.minecraft.world.entity.monster.Endermite
- net.minecraft.world.entity.monster.Enemy
+ net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Illusioner$1
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
+ net.minecraft.world.entity.monster.Phantom$1
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
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.Ravager$RavagerNavigation
+ net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
- net.minecraft.world.entity.monster.Shulker
+ net.minecraft.world.entity.monster.Shulker$1
+ net.minecraft.world.entity.monster.Strider$1
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
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
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
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
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
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
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
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
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
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
+ net.minecraft.world.item.ItemCooldowns$1
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlayerHeadItem
- net.minecraft.world.item.PotionItem
+ net.minecraft.world.item.ProjectileWeaponItem
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
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.MobSpawnSettings$1
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
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
- net.minecraft.world.level.block.grower.AzaleaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.package-info
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
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$1
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.border.package-info
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
+ net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.ChunkTickList$ScheduledTick
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.CollisionSpliterator
+ net.minecraft.world.level.ColorResolver
- net.minecraft.world.level.CommonLevelAccessor
+ net.minecraft.world.level.CustomSpawner
- net.minecraft.world.level.DataPackConfig
+ net.minecraft.world.level.EmptyBlockGetter
- net.minecraft.world.level.EmptyTickList
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$1
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager
+ net.minecraft.world.level.entity.TransientEntitySectionManager$1
+ net.minecraft.world.level.EntityBasedExplosionDamageCalculator
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.ExplosionDamageCalculator
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.GameRules
+ net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NoiseEffect
- net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.RootSystemFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SmallDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$1
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
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
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
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
+ net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
+ net.minecraft.world.level.levelgen.heightproviders.HeightProvider
- net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.package-info
+ net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
- net.minecraft.world.level.levelgen.heightproviders.UniformHeight
+ net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.CaveDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.CaveSurface
- net.minecraft.world.level.levelgen.placement.CaveSurfaceDecorator
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
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.HeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
- net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
- net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.RangeDecorator
- net.minecraft.world.level.levelgen.placement.RepeatingDecorator
+ net.minecraft.world.level.levelgen.placement.Spread32Decorator
- net.minecraft.world.level.levelgen.placement.SquareDecorator
+ net.minecraft.world.level.levelgen.placement.VerticalDecorator
- net.minecraft.world.level.levelgen.placement.WaterDepthThresholdConfiguration
+ net.minecraft.world.level.levelgen.placement.WaterDepthThresholdDecorator
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
+ net.minecraft.world.level.levelgen.structure.package-info
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
- net.minecraft.world.level.levelgen.synth.BlendedNoise
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NoiseUtils
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
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.SavedData
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
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$1
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootItem$1
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$1
- net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
- net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$1
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$1
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$1
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$1
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.IntRange$Serializer
- net.minecraft.world.level.storage.loot.ItemModifierManager
+ net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$1
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.PredicateManager$1
- net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$1
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$1
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$1
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$1
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$InlineSerializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$1
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$1
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
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
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
XXX.blaze3d.audio.OggAudioStream$OutputConcat -1M
```
```
XXX.blaze3d.pipeline.RenderTarget +6M -5M
```
```
XXX.blaze3d.platform.InputConstants$Key -2M
```
```
XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel -1M
```
```
XXX.blaze3d.platform.Window +1M
```
```
XXX.blaze3d.systems.RenderSystem -1M
```
```
XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer -2M
```
```
XXX.blaze3d.vertex.BufferBuilder$SortState -7M
```
```
XXX.realmsclient.client.FileDownload$ResourcePackProgressListener -1M
```
```
XXX.realmsclient.client.Ping$Region +1M -2M
```
```
XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse +1M
```
```
XXX.realmsclient.dto.RealmsServer$WorldType +1M
```
```
XXX.realmsclient.dto.WorldTemplate$WorldTemplateType +1M
```
```
XXX.realmsclient.gui.RealmsDataFetcher$Task +1M
```
```
XXX.realmsclient.gui.RealmsWorldSlotButton$Action +1M
```
```
XXX.gui.screens.RealmsBackupInfoScreen -2M
```
```
XXX.gui.screens.RealmsLongConfirmationScreen$Type +1M
```
```
XXX.gui.screens.RealmsNotificationsScreen -2M
```
```
XXX.gui.screens.RealmsPlayerScreen$UserAction +1M
```
```
XXX.gui.screens.RealmsResetWorldScreen -6M
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen +8M -26M
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry -1M
```
```
XXX.gui.screens.RealmsSettingsScreen +1M -1M
```
```
XXX.gui.screens.RealmsUploadScreen +1M -1M
```
```
XXX.minecraft.advancements.Advancement$Builder -1M
```
```
XXX.minecraft.advancements.FrameType +1M
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger -1M
```
```
XXX.advancements.critereon.BredAnimalsTrigger -1M
```
```
XXX.advancements.critereon.BrewedPotionTrigger -1M
```
```
XXX.advancements.critereon.ChangeDimensionTrigger -1M
```
```
XXX.advancements.critereon.ChanneledLightningTrigger -1M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger -1M
```
```
XXX.advancements.critereon.ConsumeItemTrigger -1M
```
```
XXX.advancements.critereon.CuredZombieVillagerTrigger -1M
```
```
XXX.advancements.critereon.EffectsChangedTrigger -1M
```
```
XXX.advancements.critereon.EnchantedItemTrigger -1M
```
```
XXX.minecraft.client.AmbientOcclusionStatus +1M
```
```
XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason +1M -1M
```
```
XXX.minecraft.client.Screenshot +1M -1M
```
```
XXX.minecraft.client.StringSplitter -1M
```
```
XXX.minecraft.client.StringSplitter$FlatComponents -1M
```
```
XXX.minecraft.client.StringSplitter$LineComponent -2M
```
```
XXX.color.block.BlockTintCache -1M
```
```
XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator -1M
```
```
XXX.components.toasts.ToastComponent -1M
```
```
XXX.gui.font.FontTexture$Node -3M
```
```
XXX.font.glyphs.WhiteGlyph +1M
```
```
XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph -1M
```
```
XXX.gui.screens.AccessibilityOptionsScreen +1M -1M
```
```
XXX.gui.screens.ConnectScreen$1 +3M -4M | +2P -2P
```
```
XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry -1M
```
```
XXX.gui.screens.LanguageSelectScreen -1M
```
```
XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry -1M
```
```
XXX.gui.screens.LoadingOverlay -1M
```
```
XXX.gui.screens.PresetFlatWorldScreen +1M -7M
```
```
XXX.screens.achievement.StatsScreen +8M -14M
```
```
XXX.screens.controls.ControlList$KeyEntry -1M
```
```
XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot -1M
```
```
XXX.screens.inventory.BeaconScreen +5M -11M
```
```
XXX.screens.inventory.BookEditScreen -1M
```
```
XXX.screens.inventory.BookEditScreen$LineInfo -5M
```
```
XXX.screens.inventory.BookViewScreen -1M
```
```
XXX.screens.inventory.CreativeModeInventoryScreen -1M
```
```
XXX.screens.inventory.JigsawBlockEditScreen -2M
```
```
XXX.screens.inventory.LecternScreen -2M
```
```
XXX.screens.inventory.MerchantScreen +1M -2M
```
```
XXX.inventory.tooltip.ClientBundleTooltip$Texture +1M
```
```
XXX.screens.packs.PackSelectionModel -4M
```
```
XXX.screens.recipebook.GhostRecipe -1M
```
```
XXX.screens.recipebook.OverlayRecipeComponent -4M | +1P
```
```
XXX.screens.social.PlayerEntry +2M -3M
```
```
XXX.screens.social.SocialInteractionsScreen$Page +1M
```
```
XXX.screens.worldselection.CreateWorldScreen +5M -6M
```
```
XXX.screens.worldselection.EditGameRulesScreen +2M -5M
```
```
XXX.screens.worldselection.EditGameRulesScreen$RuleEntry -1M
```
```
XXX.screens.worldselection.WorldGenSettingsComponent +2M -2M
```
```
XXX.screens.worldselection.WorldSelectionList$WorldListEntry +2M -3M
```
```
XXX.gui.spectator.SpectatorMenu -5M
```
```
XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem -1M
```
```
XXX.client.main.Main -1M
```
```
XXX.client.model.HumanoidModel$ArmPose +1M
```
```
XXX.client.multiplayer.ClientChunkCache -3M
```
```
XXX.client.multiplayer.ServerData$ServerPackStatus +1M
```
```
XXX.client.multiplayer.ServerStatusPinger +2M -5M | +1P
```
```
XXX.client.multiplayer.ServerStatusPinger$2 +1M -1M | +1P -1P
```
```
XXX.client.particle.BreakingItemParticle -1M
```
```
XXX.client.particle.BubbleParticle -1M
```
```
XXX.client.particle.CampfireSmokeParticle -1M
```
```
XXX.client.particle.DripParticle$CoolingDripHangParticle -1M
```
```
XXX.client.particle.DripParticle$DripLandParticle -1M
```
```
XXX.client.particle.DripParticle$FallAndLandParticle -1M
```
```
XXX.client.particle.DripParticle$HoneyFallAndLandParticle -1M
```
```
XXX.client.particle.FallingDustParticle -1M
```
```
XXX.client.particle.GlowParticle -2M
```
```
XXX.client.particle.LavaParticle -1M
```
```
XXX.client.particle.ParticleEngine$MutableSpriteSet -1M
```
```
XXX.client.particle.PlayerCloudParticle -1M
```
```
XXX.client.particle.SoulParticle -1M
```
```
XXX.client.particle.SpitParticle -1M
```
```
XXX.client.particle.WakeParticle -1M
```
```
XXX.profiling.metric.MetricSampler -1M
```
```
XXX.client.renderer.FaceInfo$VertexInfo -1M
```
```
XXX.client.renderer.FogRenderer$FogMode +1M
```
```
XXX.client.renderer.LevelRenderer$RenderChunkInfo -4M
```
```
XXX.client.renderer.RenderStateShard$ShaderStateShard +1M -1M
```
```
XXX.block.model.ItemOverrides$PropertyMatcher -1M
```
```
XXX.block.model.ItemTransforms$TransformType +1M
```
```
XXX.model.multipart.Condition +2M -2M
```
```
XXX.model.multipart.OrCondition +1M -1M
```
```
XXX.renderer.chunk.ChunkRenderDispatcher +1M -4M
```
```
XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk -7M
```
```
XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk -3M
```
```
XXX.renderer.debug.ChunkDebugRenderer -1M
```
```
XXX.renderer.texture.TextureAtlasSprite$FrameInfo -3M
```
```
XXX.renderer.texture.TextureAtlasSprite$InterpolationData -2M
```
```
XXX.client.resources.SkinManager +3M -3M
```
```
XXX.resources.model.BlockModelRotation +1M
```
```
XXX.resources.sounds.BiomeAmbientSoundsHandler +1M -1M
```
```
XXX.resources.sounds.Sound$Type +1M
```
```
XXX.resources.sounds.SoundInstance$Attenuation +1M
```
```
XXX.client.sounds.ChannelAccess$ChannelHandle -1M
```
```
XXX.minecraft.commands.CommandFunction -1M
```
```
XXX.minecraft.commands.Commands$CommandSelection +1M -2M
```
```
XXX.arguments.blocks.BlockPredicateArgument$TagPredicate -1M
```
```
XXX.arguments.item.ItemPredicateArgument +1M -1M
```
```
XXX.arguments.selector.EntitySelectorParser +2M -2M
```
```
XXX.commands.synchronization.SuggestionProviders$Wrapper -1M
```
```
XXX.minecraft.core.AxisCycle +1M -1M
```
```
XXX.minecraft.core.Direction +1M
```
```
XXX.minecraft.core.Direction$Axis +1M -1M
```
```
XXX.minecraft.core.Direction$AxisDirection +1M
```
```
XXX.minecraft.core.Direction8 +1M
```
```
XXX.minecraft.core.RegistryAccess +2M -3M
```
```
XXX.minecraft.core.RegistryAccess$RegistryHolder +2M -2M
```
```
XXX.minecraft.core.SectionPos -1M
```
```
XXX.core.particles.VibrationParticleOption +1M -1M
```
```
XXX.minecraft.data.BlockFamily -6M
```
```
XXX.models.blockstates.Condition$CompositeCondition -1M
```
```
XXX.models.blockstates.PropertyDispatch$C1 -1M
```
```
XXX.models.blockstates.PropertyDispatch$C3 +4M -5M
```
```
XXX.models.blockstates.PropertyDispatch$C5 +8M -9M
```
```
XXX.models.blockstates.VariantProperty -2M
```
```
XXX.data.recipes.RecipeProvider +2M -2M
```
```
XXX.data.structures.SnbtToNbt$TaskResult -4M
```
```
XXX.data.tags.TagsProvider +1M -1M
```
```
XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder -2M
```
```
XXX.network.chat.ChatType +1M
```
```
XXX.network.chat.ClickEvent$Action +1M
```
```
XXX.network.chat.HoverEvent$Action +1M -5M
```
```
XXX.network.chat.HoverEvent$ItemStackInfo -3M
```
```
XXX.network.chat.SubStringSource +1M -1M
```
```
XXX.network.protocol.PacketFlow +1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P
```
```
XXX.protocol.game.ClientboundBossEventPacket -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$AddOperation -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation -2M
```
```
XXX.minecraft.realms.RealmsConnect$1 -1M
```
```
XXX.minecraft.server.ServerFunctionManager$QueuedCommand -1M
```
```
XXX.server.commands.DebugCommand$Tracer -1M
```
```
XXX.server.commands.EmoteCommands +2M -2M
```
```
XXX.server.commands.ExecuteCommand +20M -20M
```
```
XXX.server.commands.ExperienceCommand$Type +1M -1M
```
```
XXX.server.commands.FillCommand$Mode +1M
```
```
XXX.server.commands.GameRuleCommand -2M
```
```
XXX.server.commands.LootCommand +10M -10M
```
```
XXX.server.commands.SeedCommand +1M -1M
```
```
XXX.server.dedicated.Settings$MutableValue -1M
```
```
XXX.server.gui.MinecraftServerGui -2M
```
```
XXX.server.level.ChunkHolder$FullChunkStatus +1M
```
```
XXX.server.level.ChunkTaskPriorityQueue +1M -1M
```
```
XXX.server.level.ServerChunkCache$MainThreadExecutor -1M
```
```
XXX.server.level.ServerLevel +2M -6M
```
```
XXX.server.network.TextFilterClient$RequestFailedException -1M
```
```
XXX.packs.repository.Pack$Position +1M
```
```
XXX.minecraft.tags.StaticTagHelper$Wrapper -1M
```
```
XXX.minecraft.tags.Tag +2M -2M
```
```
XXX.minecraft.tags.TagManager$LoaderInfo -2M
```
```
XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory -1M
```
```
XXX.minecraft.util.SortedArraySet -3M
```
```
XXX.util.profiling.ActiveProfiler$PathEntry -5M
```
```
XXX.profiling.registry.MeasurementCategory +1M
```
```
XXX.ai.behavior.GateBehavior$RunningPolicy +1M -1M
```
```
XXX.ai.behavior.PoiCompetitorScan +1M -1M
```
```
XXX.ai.behavior.PrepareRamNearestTarget +1M -1M
```
```
XXX.ai.behavior.ShufflingList -1M
```
```
XXX.ai.sensing.NearestVisibleLivingEntitySensor +1M -1M
```
```
XXX.ai.targeting.TargetingConditions +4M -5M | +2P -4P
```
```
XXX.ai.util.HoverRandomPos +1M -1M
```
```
XXX.village.poi.PoiRecord +3M -3M
```
```
XXX.entity.animal.Bee +23M -43M
```
```
XXX.entity.animal.Bee$BaseBeeGoal -1M
```
```
XXX.entity.animal.Bee$BeeGoToHiveGoal -4M
```
```
XXX.entity.animal.Bee$BeeGrowCropGoal -1M
```
```
XXX.entity.animal.Bee$BeeLocateHiveGoal +1M -3M
```
```
XXX.entity.animal.Bee$BeePollinateGoal -2M
```
```
XXX.entity.animal.Dolphin +1M -2M
```
```
XXX.entity.animal.Ocelot -1M
```
```
XXX.entity.animal.Panda$Gene +1M -1M
```
```
XXX.entity.animal.Parrot -1M
```
```
XXX.entity.animal.Pufferfish -3M | +1P -1P
```
```
XXX.entity.animal.Rabbit -2M
```
```
XXX.entity.animal.Squid +2M -1M
```
```
XXX.entity.animal.TropicalFish$Pattern +1M
```
```
XXX.entity.animal.Turtle +2M -13M
```
```
XXX.animal.goat.Goat$GoatNodeEvaluator -1M
```
```
XXX.entity.monster.Evoker$EvokerAttackSpellGoal -1M
```
```
XXX.entity.monster.Evoker$EvokerSummonSpellGoal -1M
```
```
XXX.entity.monster.Guardian -2M
```
```
XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal -1M
```
```
XXX.entity.monster.Ravager +1M -1M
```
```
XXX.entity.monster.Slime +1M -2M
```
```
XXX.entity.monster.SpellcasterIllager +1M -1M
```
```
XXX.world.inventory.ClickAction +1M
```
```
XXX.world.inventory.GrindstoneMenu -1M
```
```
XXX.world.inventory.RecipeBookType +1M
```
```
XXX.world.item.ArmorMaterials +1M
```
```
XXX.world.item.DiggerItem +2M -1M | +1P -1P
```
```
XXX.world.item.HoeItem -1P
```
```
XXX.world.item.Item$Properties -7M
```
```
XXX.item.crafting.Ingredient$ItemValue -1M
```
```
XXX.item.crafting.RecipeManager +1M -1M
```
```
XXX.item.crafting.UpgradeRecipe -3M
```
```
XXX.item.enchantment.EnchantmentCategory +1M -1M
```
```
XXX.item.enchantment.ProtectionEnchantment$Type +1M
```
```
XXX.world.level.GameRules$Category +1M
```
```
XXX.world.level.GameRules$IntegerValue -1M
```
```
XXX.world.level.GameRules$Type -2M
```
```
XXX.world.level.LightLayer +1M
```
```
XXX.world.level.NaturalSpawner$SpawnState -4M
```
```
XXX.world.level.StructureFeatureManager +1M -1M
```
```
XXX.level.biome.AmbientMoodSettings +4M -4M
```
```
XXX.level.biome.Biome +14M -16M
```
```
XXX.level.biome.Biome$ClimateParameters +5M -5M
```
```
XXX.level.biome.Biome$Precipitation +1M
```
```
XXX.level.biome.BiomeGenerationSettings +4M -5M
```
```
XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer +1M
```
```
XXX.level.biome.MultiNoiseBiomeSource$PresetInstance +3M -4M
```
```
XXX.level.biome.OverworldBiomeSource +5M -5M
```
```
XXX.level.block.ComposterBlock -2M
```
```
XXX.level.block.DoubleBlockCombiner$BlockType +1M
```
```
XXX.level.block.LightBlock +1P
```
```
XXX.level.block.PowderSnowBlock -1M | +1P -1P
```
```
XXX.level.block.PressurePlateBlock$Sensitivity +1M
```
```
XXX.block.entity.BannerPattern +1M -1M
```
```
XXX.block.entity.BarrelBlockEntity -2M
```
```
XXX.state.properties.RailShape +1M
```
```
XXX.state.properties.SculkSensorPhase +1M
```
```
XXX.state.properties.StairsShape +1M
```
```
XXX.state.properties.Tilt +1M
```
```
XXX.level.border.BorderStatus +1M
```
```
XXX.chunk.storage.IOWorker$PendingStore -3M
```
```
XXX.chunk.storage.RegionFile -1M
```
```
XXX.chunk.storage.SectionStorage +1M -1M
```
```
XXX.level.entity.Visibility +1M
```
```
XXX.level.gameevent.BlockPositionSource +1M -2M
```
```
XXX.level.gameevent.EntityPositionSource +1M -2M
```
```
XXX.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus -2M
```
```
XXX.level.levelgen.Cavifier$QuantizedSpaghettiRarity -2M
```
```
XXX.level.levelgen.Column$Line -1M
```
```
XXX.level.levelgen.GenerationStep$Carving +1M
```
```
XXX.level.levelgen.GeodeBlockSettings +6M -6M
```
```
XXX.level.levelgen.GeodeLayerSettings +4M -4M
```
```
XXX.level.levelgen.Heightmap$Types +1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +3M -8M
```
```
XXX.level.levelgen.WorldGenSettings +1M -1M
```
```
XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration +6M -6M
```
```
XXX.levelgen.carver.CarverConfiguration +6M -6M
```
```
XXX.levelgen.feature.FossilFeatureConfiguration +5M -5M
```
```
XXX.levelgen.feature.HugeFungusConfiguration +5M -5M
```
```
XXX.levelgen.feature.JigsawFeature -3M
```
```
XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader -1M
```
```
XXX.levelgen.feature.WeightedConfiguredFeature +2M -2M
```
```
XXX.feature.configurations.DiskConfiguration +4M -4M
```
```
XXX.feature.configurations.EndGatewayConfiguration +2M -2M
```
```
XXX.feature.configurations.GeodeConfiguration +13M -13M
```
```
XXX.feature.configurations.GrowingPlantConfiguration +5M -5M
```
```
XXX.feature.configurations.HugeMushroomFeatureConfiguration +3M -3M
```
```
XXX.feature.configurations.LargeDripstoneConfiguration +9M -9M
```
```
XXX.feature.configurations.MineshaftConfiguration +2M -2M
```
```
XXX.feature.configurations.OceanRuinConfiguration +3M -3M
```
```
XXX.feature.configurations.ReplaceBlockConfiguration +1M -1M
```
```
XXX.feature.configurations.RootSystemConfiguration +12M -12M
```
```
XXX.feature.configurations.SpikeConfiguration +3M -3M
```
```
XXX.feature.configurations.TreeConfiguration +9M -9M
```
```
XXX.feature.configurations.UnderwaterMagmaConfiguration +3M -3M
```
```
XXX.feature.featuresize.TwoLayersFeatureSize +3M -3M
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +1M -1M
```
```
XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector -1M
```
```
XXX.levelgen.structure.MineShaftPieces -2M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition -6M
```
```
XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement +1M
```
```
XXX.levelgen.structure.ShipwreckPieces -1M
```
```
XXX.levelgen.structure.StrongholdPieces -3M
```
```
XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector -1M
```
```
XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType +1M
```
```
XXX.saveddata.maps.MapItemSavedData$HoldingPlayer -4M
```
```
XXX.storage.loot.IntRange -3M
```
```
XXX.storage.loot.LootPool -6M
```
```
XXX.loot.entries.EmptyLootItem -1M
```
```
XXX.loot.entries.LootPoolSingletonContainer -1M
```
```
XXX.loot.functions.ApplyExplosionDecay -1M
```
```
XXX.loot.functions.CopyNbtFunction$CopyOperation -1M
```
```
XXX.loot.functions.CopyNbtFunction$MergeStrategy$3 +1M -1M
```
```
XXX.loot.functions.EnchantRandomlyFunction -2M
```
```
XXX.loot.functions.ExplorationMapFunction -7M
```
```
XXX.loot.functions.LootingEnchantFunction -4M
```
```
XXX.loot.functions.SetBannerPatternFunction$Builder -1M
```
```
XXX.loot.functions.SetContainerContents +1M -3M
```
```
XXX.loot.functions.SetItemDamageFunction -3M
```
```
XXX.loot.functions.SmeltItemFunction -1M
```
```
XXX.loot.predicates.AlternativeLootItemCondition -2M
```
```
XXX.loot.predicates.EntityHasScoreCondition -3M
```
```
XXX.loot.predicates.LootItemEntityPropertyCondition -3M
```
```
XXX.loot.predicates.LootItemRandomChanceWithLootingCondition -3M
```
```
XXX.providers.nbt.StorageNbtProvider -2M
```
```
XXX.level.timers.TimerQueue$Event -1M
```
```
XXX.phys.shapes.Shapes +2M -2M
```
```
XXX.world.scores.Team$CollisionRule +1M
```

</details>






<details>
<summary>
com.mojang.blaze3d.audio.OggAudioStream$OutputConcat
</summary>

```diff
+ int access$000(OggAudioStream$OutputConcat)
```

</details>




<details>
<summary>
com.mojang.blaze3d.pipeline.RenderTarget
</summary>

```diff
- float[] lambda$new$0()
- void <init>(boolean)
+ void <init>(int,int,boolean,boolean)
+ void lambda$bindWrite$1(boolean)
- void lambda$bindWrite$2(boolean)
+ void lambda$blitToScreen$3(int,int,boolean)
- void lambda$blitToScreen$4(int,int,boolean)
+ void lambda$resize$0(int,int,boolean)
- void lambda$resize$1(int,int,boolean)
+ void lambda$unbindWrite$2()
- void lambda$unbindWrite$3()
```

</details>

<details>
<summary>
com.mojang.blaze3d.platform.InputConstants$Key
</summary>

```diff
+ Map access$200()
+ void <init>(String,InputConstants$Type,int,InputConstants$1)
```

</details>



<details>
<summary>
com.mojang.blaze3d.platform.PngInfo$StbReaderBufferedChannel
</summary>

```diff
+ void <init>(ReadableByteChannel,PngInfo$1)
```

</details>


<details>
<summary>
com.mojang.blaze3d.platform.Window
</summary>

```diff
- void setWindowed(int,int)
```

</details>






<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
+ Logger access$200()
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
</summary>

```diff
+ void <init>(int,int,RenderSystem$AutoStorageIndexBuffer$IndexGenerator,RenderSystem$1)
+ void access$100(RenderSystem$AutoStorageIndexBuffer,int)
```

</details>


<details>
<summary>
com.mojang.blaze3d.vertex.BufferBuilder$SortState
</summary>

```diff
+ float access$400(BufferBuilder$SortState)
+ float access$500(BufferBuilder$SortState)
+ float access$600(BufferBuilder$SortState)
+ int access$200(BufferBuilder$SortState)
+ Vector3f[] access$300(BufferBuilder$SortState)
+ VertexFormat$Mode access$100(BufferBuilder$SortState)
+ void <init>(VertexFormat$Mode,int,Vector3f[],float,float,float,BufferBuilder$1)
```

</details>



<details>
<summary>
com.mojang.realmsclient.client.FileDownload$ResourcePackProgressListener
</summary>

```diff
+ void <init>(FileDownload,File,RealmsDownloadLatestWorldScreen$DownloadStatus,WorldDownload,FileDownload$1)
```

</details>

<details>
<summary>
com.mojang.realmsclient.client.Ping$Region
</summary>

```diff
- Ping$Region[] $values()
+ String access$000(Ping$Region)
+ String access$100(Ping$Region)
```

</details>
<details>
<summary>
com.mojang.realmsclient.client.RealmsClient$CompatibleVersionResponse
</summary>

```diff
- RealmsClient$CompatibleVersionResponse[] $values()
```

</details>











<details>
<summary>
com.mojang.realmsclient.dto.RealmsServer$WorldType
</summary>

```diff
- RealmsServer$WorldType[] $values()
```

</details>








<details>
<summary>
com.mojang.realmsclient.dto.WorldTemplate$WorldTemplateType
</summary>

```diff
- WorldTemplate$WorldTemplateType[] $values()
```

</details>




<details>
<summary>
com.mojang.realmsclient.gui.RealmsDataFetcher$Task
</summary>

```diff
- RealmsDataFetcher$Task[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.RealmsWorldSlotButton$Action
</summary>

```diff
- RealmsWorldSlotButton$Action[] $values()
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
</summary>

```diff
+ Backup access$200(RealmsBackupInfoScreen)
+ Component access$100(RealmsBackupInfoScreen,String,String)
```

</details>








<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$Type
</summary>

```diff
- RealmsLongConfirmationScreen$Type[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
</summary>

```diff
+ boolean access$002(boolean)
+ boolean access$102(boolean)
```

</details>






<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$UserAction
</summary>

```diff
- RealmsPlayerScreen$UserAction[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
</summary>

```diff
+ Logger access$100()
+ void access$600(RealmsResetWorldScreen,PoseStack,int,int,Component,ResourceLocation,boolean,boolean)
+ WorldTemplatePaginatedList access$202(RealmsResetWorldScreen,WorldTemplatePaginatedList)
+ WorldTemplatePaginatedList access$302(RealmsResetWorldScreen,WorldTemplatePaginatedList)
+ WorldTemplatePaginatedList access$402(RealmsResetWorldScreen,WorldTemplatePaginatedList)
+ WorldTemplatePaginatedList access$502(RealmsResetWorldScreen,WorldTemplatePaginatedList)
```

</details>


<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
</summary>

```diff
+ boolean access$500(RealmsSelectWorldTemplateScreen)
+ Component access$2202(RealmsSelectWorldTemplateScreen,Component)
+ Component access$2300()
+ Component access$2400()
+ Either access$000(RealmsSelectWorldTemplateScreen,WorldTemplatePaginatedList,RealmsClient)
+ Font access$1300(RealmsSelectWorldTemplateScreen)
+ Font access$1400(RealmsSelectWorldTemplateScreen)
+ Font access$1500(RealmsSelectWorldTemplateScreen)
+ Font access$1600(RealmsSelectWorldTemplateScreen)
+ Font access$1800(RealmsSelectWorldTemplateScreen)
+ Font access$1900(RealmsSelectWorldTemplateScreen)
- Font access$200(RealmsSelectWorldTemplateScreen)
- Font access$300(RealmsSelectWorldTemplateScreen)
- Font access$400(RealmsSelectWorldTemplateScreen)
- Font access$500(RealmsSelectWorldTemplateScreen)
- Font access$600(RealmsSelectWorldTemplateScreen)
- Font access$700(RealmsSelectWorldTemplateScreen)
- int access$100(int)
+ int access$1002(RealmsSelectWorldTemplateScreen,int)
+ int access$600(int)
+ int access$800(RealmsSelectWorldTemplateScreen)
+ int access$802(RealmsSelectWorldTemplateScreen,int)
+ List access$402(RealmsSelectWorldTemplateScreen,List)
+ Logger access$200()
- Minecraft access$000(RealmsSelectWorldTemplateScreen)
+ Minecraft access$100(RealmsSelectWorldTemplateScreen)
+ RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList access$300(RealmsSelectWorldTemplateScreen)
+ ResourceLocation access$1700()
+ ResourceLocation access$2000()
+ ResourceLocation access$2100()
+ String access$700(RealmsSelectWorldTemplateScreen)
+ String access$702(RealmsSelectWorldTemplateScreen,String)
+ void access$1100(RealmsSelectWorldTemplateScreen)
+ void access$900(RealmsSelectWorldTemplateScreen)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$Entry
</summary>

```diff
+ WorldTemplate access$1200(RealmsSelectWorldTemplateScreen$Entry)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSettingsScreen
</summary>

```diff
- void lambda$init$2(boolean)
+ void lambda$null$2(boolean)
```

</details>


<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsUploadScreen
</summary>

```diff
+ void lambda$null$3(long,UploadResult)
- void lambda$upload$3(long,UploadResult)
```

</details>
<details>
<summary>
net.minecraft.advancements.Advancement$Builder
</summary>

```diff
+ void <init>(ResourceLocation,DisplayInfo,AdvancementRewards,Map,String[][],Advancement$1)
```

</details>






<details>
<summary>
net.minecraft.advancements.FrameType
</summary>

```diff
- FrameType[] $values()
```

</details>

<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>

<details>
<summary>
net.minecraft.advancements.critereon.BredAnimalsTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BrewedPotionTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChanneledLightningTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConsumeItemTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>



<details>
<summary>
net.minecraft.advancements.critereon.EffectsChangedTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EnchantedItemTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>



























<details>
<summary>
net.minecraft.client.AmbientOcclusionStatus
</summary>

```diff
- AmbientOcclusionStatus[] $values()
```

</details>

<details>
<summary>
net.minecraft.client.ResourceLoadStateTracker$ReloadReason
</summary>

```diff
- ResourceLoadStateTracker$ReloadReason[] $values()
+ String access$400(ResourceLoadStateTracker$ReloadReason)
```

</details>
<details>
<summary>
net.minecraft.client.Screenshot
</summary>

```diff
- Style lambda$_grab$1(File,Style)
+ Style lambda$null$1(File,Style)
```

</details>
<details>
<summary>
net.minecraft.client.StringSplitter
</summary>

```diff
+ StringSplitter$WidthProvider access$000(StringSplitter)
```

</details>
<details>
<summary>
net.minecraft.client.StringSplitter$FlatComponents
</summary>

```diff
+ List access$300(StringSplitter$FlatComponents)
```

</details>
<details>
<summary>
net.minecraft.client.StringSplitter$LineComponent
</summary>

```diff
+ String access$100(StringSplitter$LineComponent)
+ Style access$200(StringSplitter$LineComponent)
```

</details>




<details>
<summary>
net.minecraft.client.color.block.BlockTintCache
</summary>

```diff
+ BlockTintCache$LatestCacheInfo lambda$new$0()
```

</details>






<details>
<summary>
net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
</summary>

```diff
+ void <init>(PlayerTabOverlay$1)
```

</details>










<details>
<summary>
net.minecraft.client.gui.components.toasts.ToastComponent
</summary>

```diff
+ Minecraft access$100(ToastComponent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.FontTexture$Node
</summary>

```diff
+ int access$100(FontTexture$Node)
+ int access$200(FontTexture$Node)
+ void <init>(int,int,int,int,FontTexture$1)
```

</details>


<details>
<summary>
net.minecraft.client.gui.font.glyphs.WhiteGlyph
</summary>

```diff
- WhiteGlyph[] $values()
```

</details>

<details>
<summary>
net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
</summary>

```diff
+ void <init>(int,int,int,int,NativeImage,LegacyUnicodeBitmapsProvider$1)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.AccessibilityOptionsScreen
</summary>

```diff
- void lambda$createFooter$0(boolean)
+ void lambda$null$0(boolean)
```

</details>




<details>
<summary>
net.minecraft.client.gui.screens.ConnectScreen$1
</summary>

```diff
- void <init>(ConnectScreen,String,ServerAddress,Minecraft)
+ void <init>(ConnectScreen,String,String,int)
+ void lambda$run$0(ConnectScreen,Component)
- void lambda$run$0(Minecraft)
+ void lambda$run$1()
- void lambda$run$1(Minecraft,String)
+ void lambda$run$2(String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
</summary>

```diff
+ void <init>(CreateFlatWorldScreen$DetailsList,CreateFlatWorldScreen$1)
```

</details>




<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen
</summary>

```diff
+ LanguageManager access$000(LanguageSelectScreen)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
</summary>

```diff
+ LanguageInfo access$100(LanguageSelectScreen$LanguageSelectionList$Entry)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LoadingOverlay
</summary>

```diff
+ ResourceLocation access$000()
```

</details>





<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen
</summary>

```diff
+ Biome lambda$null$4(Registry,ResourceKey)
- Biome lambda$preset$4(Registry,ResourceKey)
+ CreateFlatWorldScreen access$200(PresetFlatWorldScreen)
+ EditBox access$500(PresetFlatWorldScreen)
+ FlatLevelGeneratorSettings access$300(PresetFlatWorldScreen)
+ FlatLevelGeneratorSettings access$302(PresetFlatWorldScreen,FlatLevelGeneratorSettings)
+ List access$000()
+ String access$400(Registry,FlatLevelGeneratorSettings)
```

</details>






<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen
</summary>

```diff
- Font access$000(StatsScreen)
- Font access$100(StatsScreen)
- Font access$1200(StatsScreen)
+ Font access$1400(StatsScreen)
+ Font access$1500(StatsScreen)
+ Font access$1600(StatsScreen)
+ Font access$1700(StatsScreen)
+ Font access$1800(StatsScreen)
+ Font access$1900(StatsScreen)
+ Font access$2000(StatsScreen)
+ Font access$2100(StatsScreen)
- Font access$300(StatsScreen)
- Font access$600(StatsScreen)
- Font access$700(StatsScreen)
- Font access$800(StatsScreen)
- Font access$900(StatsScreen)
+ int access$800(StatsScreen,int)
+ StatsCounter access$300(StatsScreen)
+ StatsScreen$ItemStatisticsList access$1200(StatsScreen)
+ String access$100(Stat)
+ void access$1300(StatsScreen,PoseStack,int,int,Item)
+ void access$900(StatsScreen,PoseStack,int,int,int,int)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
</summary>

```diff
+ void <init>(ControlList,KeyMapping,Component,ControlList$1)
```

</details>



<details>
<summary>
net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
</summary>

```diff
+ GameModeSwitcherScreen$GameModeIcon access$100(GameModeSwitcherScreen$GameModeSlot)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.inventory.BeaconScreen
</summary>

```diff
+ boolean access$202(BeaconScreen,boolean)
- List access$000(BeaconScreen)
- List access$100(BeaconScreen)
+ List access$400(BeaconScreen)
+ List access$500(BeaconScreen)
- Minecraft access$200(BeaconScreen)
- Minecraft access$300(BeaconScreen)
- Minecraft access$400(BeaconScreen)
+ Minecraft access$600(BeaconScreen)
+ Minecraft access$700(BeaconScreen)
+ Minecraft access$800(BeaconScreen)
+ MobEffect access$000(BeaconScreen)
+ MobEffect access$002(BeaconScreen,MobEffect)
+ MobEffect access$100(BeaconScreen)
+ MobEffect access$102(BeaconScreen,MobEffect)
+ ResourceLocation access$300()
```

</details>



<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookEditScreen
</summary>

```diff
+ int access$1000(int[],int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
</summary>

```diff
+ Component access$200(BookEditScreen$LineInfo)
+ int access$300(BookEditScreen$LineInfo)
+ int access$400(BookEditScreen$LineInfo)
+ String access$800(BookEditScreen$LineInfo)
+ Style access$900(BookEditScreen$LineInfo)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookViewScreen
</summary>

```diff
+ List access$000(CompoundTag)
```

</details>





<details>
<summary>
net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
</summary>

```diff
+ SimpleContainer access$000()
```

</details>






<details>
<summary>
net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
</summary>

```diff
+ int access$000(JigsawBlockEditScreen)
+ int access$002(JigsawBlockEditScreen,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.LecternScreen
</summary>

```diff
+ void access$000(LecternScreen)
+ void access$100(LecternScreen)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.inventory.MerchantScreen
</summary>

```diff
+ int access$000(MerchantScreen)
- void access$000(MerchantScreen,PoseStack,ItemStack,int,int)
+ void access$300(MerchantScreen,PoseStack,ItemStack,int,int)
```

</details>






<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
</summary>

```diff
- ClientBundleTooltip$Texture[] $values()
```

</details>





<details>
<summary>
net.minecraft.client.gui.screens.packs.PackSelectionModel
</summary>

```diff
+ Function access$000(PackSelectionModel)
+ List access$200(PackSelectionModel)
+ List access$300(PackSelectionModel)
+ Runnable access$100(PackSelectionModel)
```

</details>





<details>
<summary>
net.minecraft.client.gui.screens.recipebook.GhostRecipe
</summary>

```diff
+ float access$000(GhostRecipe)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
</summary>

```diff
+ boolean access$200(OverlayRecipeComponent)
+ float access$300(OverlayRecipeComponent)
+ Minecraft access$400(OverlayRecipeComponent)
+ ResourceLocation access$100()
```

</details>






<details>
<summary>
net.minecraft.client.gui.screens.social.PlayerEntry
</summary>

```diff
+ MutableComponent access$000(PlayerEntry,MutableComponent)
- void lambda$new$1(SocialInteractionsScreen,PoseStack,int,int)
- void lambda$new$4(SocialInteractionsScreen,PoseStack,int,int)
+ void lambda$null$1(SocialInteractionsScreen,PoseStack,int,int)
+ void lambda$null$4(SocialInteractionsScreen,PoseStack,int,int)
```

</details>



<details>
<summary>
net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
</summary>

```diff
- SocialInteractionsScreen$Page[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
</summary>

```diff
+ String access$000(CreateWorldScreen)
- void lambda$init$7(GameRules)
- void lambda$init$8(Optional)
+ void lambda$null$15(boolean)
+ void lambda$null$16()
+ void lambda$null$17(DataPackConfig,ServerResources)
+ void lambda$null$7(GameRules)
+ void lambda$null$8(Optional)
- void lambda$tryApplyNewDataPacks$15(boolean)
- void lambda$tryApplyNewDataPacks$16()
- void lambda$tryApplyNewDataPacks$17(DataPackConfig,ServerResources)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen
</summary>

```diff
- Font access$700(EditGameRulesScreen)
+ Font access$900(EditGameRulesScreen)
- Minecraft access$600(EditGameRulesScreen)
+ Minecraft access$800(EditGameRulesScreen)
+ void access$1100(EditGameRulesScreen,List)
+ void access$600(EditGameRulesScreen,EditGameRulesScreen$RuleEntry)
+ void access$700(EditGameRulesScreen,EditGameRulesScreen$RuleEntry)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
</summary>

```diff
+ List access$1000(EditGameRulesScreen$RuleEntry)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
</summary>

```diff
- void lambda$init$8(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,WorldGenSettings,boolean)
- void lambda$init$9(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,Lifecycle,WorldGenSettings)
+ void lambda$null$8(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,WorldGenSettings,boolean)
+ void lambda$null$9(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,Lifecycle,WorldGenSettings)
```

</details>





<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
</summary>

```diff
+ LevelSummary access$000(WorldSelectionList$WorldListEntry)
- String lambda$editWorld$5()
+ String lambda$null$5()
- void lambda$joinWorld$1()
+ void lambda$null$1()
```

</details>

<details>
<summary>
net.minecraft.client.gui.spectator.SpectatorMenu
</summary>

```diff
+ Component access$100()
+ Component access$300()
+ Component access$400()
+ int access$200(SpectatorMenu)
+ int access$202(SpectatorMenu,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
</summary>

```diff
+ void <init>(SpectatorMenu$1)
```

</details>







<details>
<summary>
net.minecraft.client.main.Main
</summary>

```diff
+ Logger access$000()
```

</details>





















<details>
<summary>
net.minecraft.client.model.HumanoidModel$ArmPose
</summary>

```diff
- HumanoidModel$ArmPose[] $values()
```

</details>







































<details>
<summary>
net.minecraft.client.multiplayer.ClientChunkCache
</summary>

```diff
+ ClientChunkCache$Storage access$900(ClientChunkCache)
+ ClientLevel access$800(ClientChunkCache)
+ Logger access$1000()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ServerData$ServerPackStatus
</summary>

```diff
- ServerData$ServerPackStatus[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ServerStatusPinger
</summary>

```diff
+ Component access$000(int,int)
+ Logger access$100()
+ Splitter access$300()
+ void access$200(ServerStatusPinger,ServerData)
- void onPingFailed(Component,ServerData)
- void pingLegacyServer(InetSocketAddress,ServerData)
+ void pingLegacyServer(ServerData)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ServerStatusPinger$2
</summary>

```diff
- void <init>(ServerStatusPinger,InetSocketAddress,ServerData)
+ void <init>(ServerStatusPinger,ServerAddress,ServerData)
```

</details>


<details>
<summary>
net.minecraft.client.particle.BreakingItemParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,ItemStack,BreakingItemParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BubbleParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,BubbleParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.CampfireSmokeParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,boolean,CampfireSmokeParticle$1)
```

</details>


<details>
<summary>
net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions,DripParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$DripLandParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,Fluid,DripParticle$1)
```

</details>


<details>
<summary>
net.minecraft.client.particle.DripParticle$FallAndLandParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions,DripParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions,DripParticle$1)
```

</details>










<details>
<summary>
net.minecraft.client.particle.FallingDustParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,float,float,float,SpriteSet,FallingDustParticle$1)
```

</details>

<details>
<summary>
net.minecraft.client.particle.GlowParticle
</summary>

```diff
+ Random access$000()
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,GlowParticle$1)
```

</details>



<details>
<summary>
net.minecraft.client.particle.LavaParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,LavaParticle$1)
```

</details>

<details>
<summary>
net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
</summary>

```diff
+ void <init>(ParticleEngine,ParticleEngine$1)
```

</details>




<details>
<summary>
net.minecraft.client.particle.PlayerCloudParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,PlayerCloudParticle$1)
```

</details>




<details>
<summary>
net.minecraft.client.particle.SoulParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,SoulParticle$1)
```

</details>


<details>
<summary>
net.minecraft.client.particle.SpitParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,SpitParticle$1)
```

</details>






<details>
<summary>
net.minecraft.client.particle.WakeParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,WakeParticle$1)
```

</details>









<details>
<summary>
net.minecraft.client.profiling.metric.MetricSampler
</summary>

```diff
+ void <init>(Metric,DoubleSupplier,Runnable,MetricSampler$ThresholdAlerter,MetricSampler$1)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FaceInfo$VertexInfo
</summary>

```diff
+ void <init>(int,int,int,FaceInfo$1)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FogRenderer$FogMode
</summary>

```diff
- FogRenderer$FogMode[] $values()
```

</details>

<details>
<summary>
net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
</summary>

```diff
+ byte access$500(LevelRenderer$RenderChunkInfo)
+ ChunkRenderDispatcher$RenderChunk access$100(LevelRenderer$RenderChunkInfo)
+ int access$400(LevelRenderer$RenderChunkInfo)
+ void <init>(ChunkRenderDispatcher$RenderChunk,Direction,int,LevelRenderer$1)
```

</details>









<details>
<summary>
net.minecraft.client.renderer.RenderStateShard$ShaderStateShard
</summary>

```diff
- ShaderInstance lambda$new$2()
+ ShaderInstance lambda$null$2()
```

</details>


<details>
<summary>
net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
</summary>

```diff
+ void <init>(int,float,ItemOverrides$1)
```

</details>


<details>
<summary>
net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
</summary>

```diff
- ItemTransforms$TransformType[] $values()
```

</details>


<details>
<summary>
net.minecraft.client.renderer.block.model.multipart.Condition
</summary>

```diff
+ boolean lambda$null$0(BlockState)
+ boolean lambda$null$2(BlockState)
- boolean lambda$static$0(BlockState)
- boolean lambda$static$2(BlockState)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.block.model.multipart.OrCondition
</summary>

```diff
- boolean lambda$getPredicate$1(BlockState,Predicate)
+ boolean lambda$null$1(BlockState,Predicate)
```

</details>















<details>
<summary>
net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
</summary>

```diff
+ ChunkBufferBuilderPack access$300(ChunkRenderDispatcher)
+ Level access$000(ChunkRenderDispatcher)
+ LevelRenderer access$200(ChunkRenderDispatcher)
+ void lambda$null$2(ChunkRenderDispatcher$ChunkTaskResult,ChunkBufferBuilderPack)
- void lambda$runTask$2(ChunkRenderDispatcher$ChunkTaskResult,ChunkBufferBuilderPack)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
</summary>

```diff
+ boolean access$702(ChunkRenderDispatcher$CompiledChunk,boolean)
+ BufferBuilder$SortState access$900(ChunkRenderDispatcher$CompiledChunk)
+ BufferBuilder$SortState access$902(ChunkRenderDispatcher$CompiledChunk,BufferBuilder$SortState)
+ List access$1100(ChunkRenderDispatcher$CompiledChunk)
+ Set access$100(ChunkRenderDispatcher$CompiledChunk)
+ Set access$800(ChunkRenderDispatcher$CompiledChunk)
+ VisibilitySet access$1002(ChunkRenderDispatcher$CompiledChunk,VisibilitySet)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
</summary>

```diff
+ BlockPos$MutableBlockPos access$500(ChunkRenderDispatcher$RenderChunk)
+ void access$400(ChunkRenderDispatcher$RenderChunk,Set)
+ void access$600(ChunkRenderDispatcher$RenderChunk,BufferBuilder)
```

</details>








<details>
<summary>
net.minecraft.client.renderer.debug.ChunkDebugRenderer
</summary>

```diff
+ Minecraft access$300(ChunkDebugRenderer)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureAtlasSprite$FrameInfo
</summary>

```diff
+ int access$600(TextureAtlasSprite$FrameInfo)
+ int access$700(TextureAtlasSprite$FrameInfo)
+ void <init>(int,int,TextureAtlasSprite$1)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureAtlasSprite$InterpolationData
</summary>

```diff
+ void <init>(TextureAtlasSprite,TextureAtlasSprite$Info,int,TextureAtlasSprite$1)
+ void access$1700(TextureAtlasSprite$InterpolationData,TextureAtlasSprite$AnimatedTexture)
```

</details>








<details>
<summary>
net.minecraft.client.resources.SkinManager
</summary>

```diff
+ void lambda$null$1(Map,SkinManager$SkinTextureCallback,MinecraftProfileTexture$Type)
+ void lambda$null$2(Map,SkinManager$SkinTextureCallback)
+ void lambda$null$3(Map,SkinManager$SkinTextureCallback)
- void lambda$registerSkins$1(Map,SkinManager$SkinTextureCallback,MinecraftProfileTexture$Type)
- void lambda$registerSkins$2(Map,SkinManager$SkinTextureCallback)
- void lambda$registerSkins$3(Map,SkinManager$SkinTextureCallback)
```

</details>













<details>
<summary>
net.minecraft.client.resources.model.BlockModelRotation
</summary>

```diff
- BlockModelRotation[] $values()
```

</details>











<details>
<summary>
net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
</summary>

```diff
+ BiomeAmbientSoundsHandler$LoopSoundInstance lambda$null$0(SoundEvent,Biome,BiomeAmbientSoundsHandler$LoopSoundInstance)
- BiomeAmbientSoundsHandler$LoopSoundInstance lambda$tick$0(SoundEvent,Biome,BiomeAmbientSoundsHandler$LoopSoundInstance)
```

</details>




<details>
<summary>
net.minecraft.client.resources.sounds.Sound$Type
</summary>

```diff
- Sound$Type[] $values()
```

</details>

<details>
<summary>
net.minecraft.client.resources.sounds.SoundInstance$Attenuation
</summary>

```diff
- SoundInstance$Attenuation[] $values()
```

</details>













<details>
<summary>
net.minecraft.client.sounds.ChannelAccess$ChannelHandle
</summary>

```diff
+ Channel access$200(ChannelAccess$ChannelHandle)
```

</details>


<details>
<summary>
net.minecraft.commands.CommandFunction
</summary>

```diff
+ ResourceLocation access$000(CommandFunction)
```

</details>




<details>
<summary>
net.minecraft.commands.Commands$CommandSelection
</summary>

```diff
+ boolean access$000(Commands$CommandSelection)
+ boolean access$100(Commands$CommandSelection)
- Commands$CommandSelection[] $values()
```

</details>



<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
</summary>

```diff
+ void <init>(Tag,Map,CompoundTag,BlockPredicateArgument$1)
```

</details>










<details>
<summary>
net.minecraft.commands.arguments.item.ItemPredicateArgument
</summary>

```diff
+ CommandSyntaxException lambda$null$2(ResourceLocation)
- CommandSyntaxException lambda$parse$2(ResourceLocation)
```

</details>



<details>
<summary>
net.minecraft.commands.arguments.selector.EntitySelectorParser
</summary>

```diff
+ int lambda$null$3(Vec3,Entity,Entity)
+ int lambda$null$5(Vec3,Entity,Entity)
- int lambda$static$3(Vec3,Entity,Entity)
- int lambda$static$5(Vec3,Entity,Entity)
```

</details>

<details>
<summary>
net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
</summary>

```diff
+ ResourceLocation access$000(SuggestionProviders$Wrapper)
```

</details>




<details>
<summary>
net.minecraft.core.AxisCycle
</summary>

```diff
- AxisCycle[] $values()
+ void <init>(String,int,AxisCycle$1)
```

</details>







<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
- Direction[] $values()
```

</details>
<details>
<summary>
net.minecraft.core.Direction$Axis
</summary>

```diff
- Direction$Axis[] $values()
+ void <init>(String,int,String,Direction$1)
```

</details>

<details>
<summary>
net.minecraft.core.Direction$AxisDirection
</summary>

```diff
- Direction$AxisDirection[] $values()
```

</details>
<details>
<summary>
net.minecraft.core.Direction8
</summary>

```diff
- Direction8[] $values()
```

</details>





<details>
<summary>
net.minecraft.core.RegistryAccess
</summary>

```diff
+ boolean lambda$null$3(ResourceKey)
- boolean lambda$static$3(ResourceKey)
+ Map access$000()
+ void lambda$null$4(RegistryAccess$RegistryHolder,ResourceKey)
- void lambda$static$4(RegistryAccess$RegistryHolder,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess$RegistryHolder
</summary>

```diff
- boolean lambda$captureMap$3(Map$Entry)
+ boolean lambda$null$3(Map$Entry)
- Codec lambda$makeNetworkCodec$1(ResourceKey,Codec)
+ Codec lambda$null$1(ResourceKey,Codec)
```

</details>
<details>
<summary>
net.minecraft.core.SectionPos
</summary>

```diff
+ void <init>(int,int,int,SectionPos$1)
```

</details>





























<details>
<summary>
net.minecraft.core.particles.VibrationParticleOption
</summary>

```diff
+ VibrationPath lambda$null$0(VibrationParticleOption)
- VibrationPath lambda$static$0(VibrationParticleOption)
```

</details>

<details>
<summary>
net.minecraft.data.BlockFamily
</summary>

```diff
+ boolean access$202(BlockFamily,boolean)
+ boolean access$302(BlockFamily,boolean)
+ Map access$100(BlockFamily)
+ String access$402(BlockFamily,String)
+ String access$502(BlockFamily,String)
+ void <init>(Block,BlockFamily$1)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.Condition$CompositeCondition
</summary>

```diff
+ void <init>(Condition$Operation,List,Condition$1)
```

</details>

<details>
<summary>
net.minecraft.data.models.blockstates.PropertyDispatch$C1
</summary>

```diff
+ void <init>(Property,PropertyDispatch$1)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.PropertyDispatch$C3
</summary>

```diff
+ void <init>(Property,Property,Property,PropertyDispatch$1)
- void lambda$generate$0(Comparable,Comparable,PropertyDispatch$TriFunction,Comparable)
- void lambda$generate$1(Comparable,PropertyDispatch$TriFunction,Comparable)
- void lambda$generateList$3(Comparable,Comparable,PropertyDispatch$TriFunction,Comparable)
- void lambda$generateList$4(Comparable,PropertyDispatch$TriFunction,Comparable)
+ void lambda$null$0(Comparable,Comparable,PropertyDispatch$TriFunction,Comparable)
+ void lambda$null$1(Comparable,PropertyDispatch$TriFunction,Comparable)
+ void lambda$null$3(Comparable,Comparable,PropertyDispatch$TriFunction,Comparable)
+ void lambda$null$4(Comparable,PropertyDispatch$TriFunction,Comparable)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.PropertyDispatch$C5
</summary>

```diff
+ void <init>(Property,Property,Property,Property,Property,PropertyDispatch$1)
- void lambda$generate$0(Comparable,Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generate$1(Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generate$2(Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generate$3(Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generateList$5(Comparable,Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generateList$6(Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generateList$7(Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generateList$8(Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$0(Comparable,Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$1(Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$2(Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$3(Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$5(Comparable,Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$6(Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$7(Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$8(Comparable,PropertyDispatch$PentaFunction,Comparable)
```

</details>



<details>
<summary>
net.minecraft.data.models.blockstates.VariantProperty
</summary>

```diff
+ Function access$100(VariantProperty)
+ String access$000(VariantProperty)
```

</details>







<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- String lambda$generateRecipes$4(ItemLike)
+ String lambda$null$4(ItemLike)
- void lambda$generateRecipes$3(RecipeBuilder,BlockFamily$Variant,String)
+ void lambda$null$3(RecipeBuilder,BlockFamily$Variant,String)
```

</details>








<details>
<summary>
net.minecraft.data.structures.SnbtToNbt$TaskResult
</summary>

```diff
+ byte[] access$300(SnbtToNbt$TaskResult)
+ String access$000(SnbtToNbt$TaskResult)
+ String access$100(SnbtToNbt$TaskResult)
+ String access$200(SnbtToNbt$TaskResult)
```

</details>



<details>
<summary>
net.minecraft.data.tags.TagsProvider
</summary>

```diff
+ boolean lambda$null$0(Tag$BuilderEntry)
- boolean lambda$run$0(Tag$BuilderEntry)
```

</details>
<details>
<summary>
net.minecraft.network.ConnectionProtocol$ProtocolBuilder
</summary>

```diff
+ Map access$200(ConnectionProtocol$ProtocolBuilder)
+ void <init>(ConnectionProtocol$1)
```

</details>




<details>
<summary>
net.minecraft.network.chat.ChatType
</summary>

```diff
- ChatType[] $values()
```

</details>
<details>
<summary>
net.minecraft.network.chat.ClickEvent$Action
</summary>

```diff
- ClickEvent$Action[] $values()
```

</details>






<details>
<summary>
net.minecraft.network.chat.HoverEvent$Action
</summary>

```diff
- HoverEvent$Action lambda$static$0(HoverEvent$Action)
+ HoverEvent$Action lambda$static$3(HoverEvent$Action)
+ HoverEvent$ItemStackInfo lambda$static$0(JsonElement)
+ HoverEvent$ItemStackInfo lambda$static$2(Component)
+ JsonElement lambda$static$1(Object)
+ Object access$000(HoverEvent$Action,Object)
```

</details>
<details>
<summary>
net.minecraft.network.chat.HoverEvent$ItemStackInfo
</summary>

```diff
+ HoverEvent$ItemStackInfo access$200(Component)
+ HoverEvent$ItemStackInfo access$400(JsonElement)
+ JsonElement access$300(HoverEvent$ItemStackInfo)
```

</details>





<details>
<summary>
net.minecraft.network.chat.SubStringSource
</summary>

```diff
- boolean lambda$create$2(StringBuilder,List,int,Style,int)
+ boolean lambda$null$2(StringBuilder,List,int,Style,int)
```

</details>



<details>
<summary>
net.minecraft.network.protocol.PacketFlow
</summary>

```diff
- PacketFlow[] $values()
```

</details>







<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket
</summary>

```diff
+ ClientboundBossEventPacket$Operation access$1000()
+ int access$1200(boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
</summary>

```diff
+ void <init>(BossEvent,ClientboundBossEventPacket$1)
+ void <init>(FriendlyByteBuf,ClientboundBossEventPacket$1)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
</summary>

```diff
+ void <init>(Component,ClientboundBossEventPacket$1)
+ void <init>(FriendlyByteBuf,ClientboundBossEventPacket$1)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
</summary>

```diff
+ void <init>(boolean,boolean,boolean,ClientboundBossEventPacket$1)
+ void <init>(FriendlyByteBuf,ClientboundBossEventPacket$1)
```

</details>














































<details>
<summary>
net.minecraft.realms.RealmsConnect$1
</summary>

```diff
+ void lambda$run$2(Minecraft,DisconnectedRealmsScreen)
```

</details>







<details>
<summary>
net.minecraft.server.ServerFunctionManager$QueuedCommand
</summary>

```diff
+ int access$400(ServerFunctionManager$QueuedCommand)
```

</details>





<details>
<summary>
net.minecraft.server.commands.DebugCommand$Tracer
</summary>

```diff
+ void <init>(PrintWriter,DebugCommand$1)
```

</details>


<details>
<summary>
net.minecraft.server.commands.EmoteCommands
</summary>

```diff
+ Component lambda$null$0(ServerPlayer,Component,Component,ServerPlayer)
- Component lambda$register$0(ServerPlayer,Component,Component,ServerPlayer)
+ void lambda$null$1(CommandContext,MinecraftServer,ServerPlayer,Entity,TextFilter$FilteredText)
- void lambda$register$1(CommandContext,MinecraftServer,ServerPlayer,Entity,TextFilter$FilteredText)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ExecuteCommand
</summary>

```diff
- boolean lambda$addConditionals$40(Integer,Integer)
- boolean lambda$addConditionals$42(Integer,Integer)
- boolean lambda$addConditionals$44(Integer,Integer)
- boolean lambda$addConditionals$46(Integer,Integer)
+ boolean lambda$null$40(Integer,Integer)
+ boolean lambda$null$42(Integer,Integer)
+ boolean lambda$null$44(Integer,Integer)
+ boolean lambda$null$46(Integer,Integer)
- Collection lambda$addConditionals$52(boolean,DataCommands$DataProvider,CommandContext)
+ Collection lambda$null$52(boolean,DataCommands$DataProvider,CommandContext)
+ CommandSourceStack lambda$null$22(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$24(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$26(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$28(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$30(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$32(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$22(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$24(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$26(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$28(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$30(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$32(DataCommands$DataProvider,boolean,CommandContext)
- int lambda$addConditionals$53(DataCommands$DataProvider,CommandContext)
+ int lambda$null$53(DataCommands$DataProvider,CommandContext)
+ Tag lambda$null$21(CommandContext,int)
+ Tag lambda$null$23(CommandContext,int)
+ Tag lambda$null$25(CommandContext,int)
+ Tag lambda$null$27(CommandContext,int)
+ Tag lambda$null$29(CommandContext,int)
+ Tag lambda$null$31(CommandContext,int)
+ Tag lambda$null$36(IntFunction,int)
- Tag lambda$storeData$36(IntFunction,int)
- Tag lambda$wrapStores$21(CommandContext,int)
- Tag lambda$wrapStores$23(CommandContext,int)
- Tag lambda$wrapStores$25(CommandContext,int)
- Tag lambda$wrapStores$27(CommandContext,int)
- Tag lambda$wrapStores$29(CommandContext,int)
- Tag lambda$wrapStores$31(CommandContext,int)
+ void lambda$null$2(ResultConsumer,ResultConsumer,CommandContext,boolean,int)
- void lambda$static$2(ResultConsumer,ResultConsumer,CommandContext,boolean,int)
```

</details>

<details>
<summary>
net.minecraft.server.commands.ExperienceCommand$Type
</summary>

```diff
- ExperienceCommand$Type[] $values()
+ ToIntFunction access$000(ExperienceCommand$Type)
```

</details>
<details>
<summary>
net.minecraft.server.commands.FillCommand$Mode
</summary>

```diff
- FillCommand$Mode[] $values()
```

</details>

<details>
<summary>
net.minecraft.server.commands.GameRuleCommand
</summary>

```diff
+ int access$000(CommandContext,GameRules$Key)
+ int access$100(CommandSourceStack,GameRules$Key)
```

</details>




<details>
<summary>
net.minecraft.server.commands.LootCommand
</summary>

```diff
+ int lambda$null$10(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$11(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$12(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$13(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$4(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$5(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$6(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$7(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$8(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$9(LootCommand$DropConsumer,CommandContext)
- int lambda$register$10(LootCommand$DropConsumer,CommandContext)
- int lambda$register$11(LootCommand$DropConsumer,CommandContext)
- int lambda$register$12(LootCommand$DropConsumer,CommandContext)
- int lambda$register$13(LootCommand$DropConsumer,CommandContext)
- int lambda$register$4(LootCommand$DropConsumer,CommandContext)
- int lambda$register$5(LootCommand$DropConsumer,CommandContext)
- int lambda$register$6(LootCommand$DropConsumer,CommandContext)
- int lambda$register$7(LootCommand$DropConsumer,CommandContext)
- int lambda$register$8(LootCommand$DropConsumer,CommandContext)
- int lambda$register$9(LootCommand$DropConsumer,CommandContext)
```

</details>









<details>
<summary>
net.minecraft.server.commands.SeedCommand
</summary>

```diff
+ Style lambda$null$1(long,Style)
- Style lambda$register$1(long,Style)
```

</details>




<details>
<summary>
net.minecraft.server.dedicated.Settings$MutableValue
</summary>

```diff
+ void <init>(Settings,String,Object,Function,Settings$1)
```

</details>
<details>
<summary>
net.minecraft.server.gui.MinecraftServerGui
</summary>

```diff
+ AtomicBoolean access$000(MinecraftServerGui)
+ void access$100(MinecraftServerGui)
```

</details>





<details>
<summary>
net.minecraft.server.level.ChunkHolder$FullChunkStatus
</summary>

```diff
- ChunkHolder$FullChunkStatus[] $values()
```

</details>



<details>
<summary>
net.minecraft.server.level.ChunkTaskPriorityQueue
</summary>

```diff
+ Either lambda$null$5(long)
- Either lambda$pop$5(long)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
</summary>

```diff
+ void <init>(ServerChunkCache,Level,ServerChunkCache$1)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ EntityTickList access$100(ServerLevel)
+ Int2ObjectMap access$400(ServerLevel)
+ List access$200(ServerLevel)
+ Set access$300(ServerLevel)
+ void lambda$null$16(BlockPos)
+ void lambda$null$18(BlockPos,PoiType)
- void lambda$onBlockStateChange$16(BlockPos)
- void lambda$onBlockStateChange$18(BlockPos,PoiType)
```

</details>

<details>
<summary>
net.minecraft.server.network.TextFilterClient$RequestFailedException
</summary>

```diff
+ void <init>(String,TextFilterClient$1)
```

</details>









<details>
<summary>
net.minecraft.server.packs.repository.Pack$Position
</summary>

```diff
- Pack$Position[] $values()
```

</details>





<details>
<summary>
net.minecraft.tags.StaticTagHelper$Wrapper
</summary>

```diff
+ void <init>(ResourceLocation,StaticTagHelper$1)
```

</details>
<details>
<summary>
net.minecraft.tags.Tag
</summary>

```diff
- DataResult lambda$codec$0(ResourceLocation)
- DataResult lambda$codec$2(Tag)
+ DataResult lambda$null$0(ResourceLocation)
+ DataResult lambda$null$2(Tag)
```

</details>
<details>
<summary>
net.minecraft.tags.TagManager$LoaderInfo
</summary>

```diff
+ CompletableFuture access$100(TagManager$LoaderInfo)
+ void <init>(StaticTagHelper,CompletableFuture,TagManager$1)
```

</details>




<details>
<summary>
net.minecraft.util.LowerCaseEnumTypeAdapterFactory
</summary>

```diff
+ String access$000(LowerCaseEnumTypeAdapterFactory,Object)
```

</details>



<details>
<summary>
net.minecraft.util.SortedArraySet
</summary>

```diff
+ int access$000(SortedArraySet)
+ Object[] access$100(SortedArraySet)
+ void access$200(SortedArraySet,int)
```

</details>

<details>
<summary>
net.minecraft.util.profiling.ActiveProfiler$PathEntry
</summary>

```diff
+ long access$000(ActiveProfiler$PathEntry)
+ long access$002(ActiveProfiler$PathEntry,long)
+ long access$100(ActiveProfiler$PathEntry)
+ long access$102(ActiveProfiler$PathEntry,long)
+ Object2LongOpenHashMap access$200(ActiveProfiler$PathEntry)
```

</details>







<details>
<summary>
net.minecraft.util.profiling.registry.MeasurementCategory
</summary>

```diff
- MeasurementCategory[] $values()
```

</details>




<details>
<summary>
net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
</summary>

```diff
- GateBehavior$RunningPolicy[] $values()
+ void <init>(String,int,GateBehavior$1)
```

</details>












<details>
<summary>
net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
</summary>

```diff
+ boolean lambda$null$0(GlobalPos,PoiType,Villager)
- boolean lambda$start$0(GlobalPos,PoiType,Villager)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
</summary>

```diff
+ boolean lambda$null$0(PathfinderMob,LivingEntity)
- boolean lambda$start$0(PathfinderMob,LivingEntity)
```

</details>










<details>
<summary>
net.minecraft.world.entity.ai.behavior.ShufflingList
</summary>

```diff
+ double lambda$shuffle$2(Object)
```

</details>












<details>
<summary>
net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
</summary>

```diff
- boolean lambda$getNearestEntity$0(LivingEntity,LivingEntity)
+ boolean lambda$null$0(LivingEntity,LivingEntity)
```

</details>





<details>
<summary>
net.minecraft.world.entity.ai.targeting.TargetingConditions
</summary>

```diff
+ TargetingConditions allowInvulnerable()
+ TargetingConditions allowNonAttackable()
+ TargetingConditions allowSameTeam()
+ TargetingConditions allowUnseeable()
- TargetingConditions forCombat()
- TargetingConditions forNonCombat()
- TargetingConditions ignoreLineOfSight()
+ void <init>()
- void <init>(boolean)
```

</details>


<details>
<summary>
net.minecraft.world.entity.ai.util.HoverRandomPos
</summary>

```diff
- boolean lambda$getPos$0(PathfinderMob,BlockPos)
+ boolean lambda$null$0(PathfinderMob,BlockPos)
```

</details>





<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiRecord
</summary>

```diff
- BlockPos lambda$codec$0(PoiRecord)
+ BlockPos lambda$null$0(PoiRecord)
- Integer lambda$codec$2(PoiRecord)
+ Integer lambda$null$2(PoiRecord)
- PoiType lambda$codec$1(PoiRecord)
+ PoiType lambda$null$1(PoiRecord)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
+ Bee$BeeGoToHiveGoal access$4800(Bee)
+ Bee$BeePollinateGoal access$700(Bee)
+ BlockPos access$1500(Bee)
+ BlockPos access$1502(Bee,BlockPos)
+ BlockPos access$3200(Bee)
+ BlockPos access$3202(Bee,BlockPos)
+ boolean access$1400(Bee)
+ boolean access$1600(Bee,BlockPos,int)
+ boolean access$1800(Bee)
+ boolean access$2400(Bee,BlockPos)
+ boolean access$3300(Bee,BlockPos)
+ boolean access$5100(Bee,BlockPos)
+ int access$3000(Bee)
+ int access$3002(Bee,int)
+ int access$3700(Bee)
+ int access$3800(Bee)
+ int access$3802(Bee,int)
+ int access$5200(Bee)
- PathNavigation access$000(Bee)
- PathNavigation access$1000(Bee)
- PathNavigation access$1400(Bee)
- PathNavigation access$1500(Bee)
- PathNavigation access$1600(Bee)
- PathNavigation access$1700(Bee)
- PathNavigation access$1800(Bee)
+ PathNavigation access$1900(Bee)
- PathNavigation access$200(Bee)
+ PathNavigation access$2000(Bee)
+ PathNavigation access$2200(Bee)
+ PathNavigation access$2600(Bee)
+ PathNavigation access$2700(Bee)
+ PathNavigation access$2800(Bee)
+ PathNavigation access$2900(Bee)
- PathNavigation access$300(Bee)
+ PathNavigation access$3100(Bee)
+ PathNavigation access$3400(Bee)
+ PathNavigation access$3500(Bee)
+ PathNavigation access$3600(Bee)
+ PathNavigation access$3900(Bee)
- PathNavigation access$400(Bee)
+ PathNavigation access$4300(Bee)
+ PathNavigation access$4500(Bee)
- PathNavigation access$500(Bee)
- PathNavigation access$600(Bee)
- PathNavigation access$700(Bee)
- PathNavigation access$800(Bee)
- Random access$100(Bee)
+ Random access$1000(Bee)
- Random access$1900(Bee)
- Random access$2000(Bee)
- Random access$2200(Bee)
- Random access$2400(Bee)
- Random access$2500(Bee)
- Random access$2600(Bee)
- Random access$2700(Bee)
- Random access$2800(Bee)
+ Random access$4000(Bee)
+ Random access$4100(Bee)
+ Random access$4400(Bee)
+ Random access$4600(Bee)
+ Random access$4700(Bee)
+ Random access$5300(Bee)
+ Random access$5400(Bee)
+ void access$2500(Bee,BlockPos)
+ void access$4200(Bee,boolean)
+ void access$5500(Bee)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BaseBeeGoal
</summary>

```diff
+ void <init>(Bee,Bee$1)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
</summary>

```diff
+ boolean access$4900(Bee$BeeGoToHiveGoal,BlockPos)
+ int access$300(Bee$BeeGoToHiveGoal)
+ List access$500(Bee$BeeGoToHiveGoal)
+ void access$5000(Bee$BeeGoToHiveGoal)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
</summary>

```diff
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
</summary>

```diff
+ boolean lambda$findNearbyHivesWithSpace$1(Bee,BlockPos)
- double lambda$findNearbyHivesWithSpace$1(BlockPos,BlockPos)
+ double lambda$findNearbyHivesWithSpace$2(BlockPos,BlockPos)
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeePollinateGoal
</summary>

```diff
+ boolean access$600(Bee$BeePollinateGoal)
+ void access$800(Bee$BeePollinateGoal)
```

</details>




<details>
<summary>
net.minecraft.world.entity.animal.Dolphin
</summary>

```diff
- Random access$000(Dolphin)
+ Random access$300(Dolphin)
+ TargetingConditions access$400()
```

</details>













<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
+ boolean access$000(Ocelot)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Panda$Gene
</summary>

```diff
+ Panda$Gene access$000(Panda$Gene,Panda$Gene)
- Panda$Gene[] $values()
```

</details>





<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
+ Map access$000()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Pufferfish
</summary>

```diff
+ int access$002(Pufferfish,int)
+ int access$102(Pufferfish,int)
+ TargetingConditions access$200()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
+ boolean access$300(Rabbit)
+ int access$402(Rabbit,int)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
- boolean access$000(Squid)
+ boolean access$100(Squid)
- boolean canBeLeashed(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.TropicalFish$Pattern
</summary>

```diff
- TropicalFish$Pattern[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
+ BlockPos access$600(Turtle)
+ BlockPos access$700(Turtle)
+ boolean access$1300(Turtle)
+ boolean access$1400(Turtle)
+ int access$1000(Turtle)
+ int access$1008(Turtle)
- Random access$000(Turtle)
- Random access$100(Turtle)
+ Random access$1200(Turtle)
+ Random access$300(Turtle)
+ void access$1100(Turtle,boolean)
+ void access$400(Turtle,BlockPos)
+ void access$500(Turtle,boolean)
+ void access$800(Turtle,boolean)
+ void access$900(Turtle,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
</summary>

```diff
+ void <init>(Goat$1)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
</summary>

```diff
+ void <init>(Evoker,Evoker$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
</summary>

```diff
+ void <init>(Evoker,Evoker$1)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Guardian
</summary>

```diff
+ void access$000(Guardian,int)
+ void access$100(Guardian,boolean)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
</summary>

```diff
+ void <init>(Phantom,Phantom$1)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Ravager
</summary>

```diff
+ boolean canSee(Entity)
- boolean hasLineOfSight(Entity)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
- boolean access$000(Slime)
+ boolean access$100(Slime)
+ float access$000(Slime)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.SpellcasterIllager
</summary>

```diff
- PathNavigation access$000(SpellcasterIllager)
+ PathNavigation access$200(SpellcasterIllager)
```

</details>















<details>
<summary>
net.minecraft.world.inventory.ClickAction
</summary>

```diff
- ClickAction[] $values()
```

</details>










<details>
<summary>
net.minecraft.world.inventory.GrindstoneMenu
</summary>

```diff
+ Container access$000(GrindstoneMenu)
```

</details>















<details>
<summary>
net.minecraft.world.inventory.RecipeBookType
</summary>

```diff
- RecipeBookType[] $values()
```

</details>










<details>
<summary>
net.minecraft.world.item.ArmorMaterials
</summary>

```diff
- ArmorMaterials[] $values()
```

</details>
















<details>
<summary>
net.minecraft.world.item.DiggerItem
</summary>

```diff
- boolean isCorrectToolForDrops(BlockState)
+ void <init>(float,float,Tier,Set,Item$Properties)
- void <init>(float,float,Tier,Tag,Item$Properties)
```

</details>















<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
+ boolean access$600(Item$Properties)
+ CreativeModeTab access$000(Item$Properties)
+ FoodProperties access$500(Item$Properties)
+ int access$300(Item$Properties)
+ int access$400(Item$Properties)
+ Item access$200(Item$Properties)
+ Rarity access$100(Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.Ingredient$ItemValue
</summary>

```diff
+ void <init>(ItemStack,Ingredient$1)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.RecipeManager
</summary>

```diff
+ Map lambda$null$10(RecipeType)
- Map lambda$replaceRecipes$10(RecipeType)
```

</details>










<details>
<summary>
net.minecraft.world.item.crafting.UpgradeRecipe
</summary>

```diff
+ Ingredient access$000(UpgradeRecipe)
+ Ingredient access$100(UpgradeRecipe)
+ ItemStack access$200(UpgradeRecipe)
```

</details>






<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentCategory
</summary>

```diff
- EnchantmentCategory[] $values()
+ void <init>(String,int,EnchantmentCategory$1)
```

</details>













<details>
<summary>
net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
</summary>

```diff
- ProtectionEnchantment$Type[] $values()
```

</details>













<details>
<summary>
net.minecraft.world.level.GameRules$Category
</summary>

```diff
- GameRules$Category[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$IntegerValue
</summary>

```diff
+ GameRules$Type access$100(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$Type
</summary>

```diff
+ BiConsumer access$300(GameRules$Type)
+ void <init>(Supplier,Function,BiConsumer,GameRules$VisitorCaller,GameRules$1)
```

</details>







<details>
<summary>
net.minecraft.world.level.LightLayer
</summary>

```diff
- LightLayer[] $values()
```

</details>


<details>
<summary>
net.minecraft.world.level.NaturalSpawner$SpawnState
</summary>

```diff
+ boolean access$300(NaturalSpawner$SpawnState,MobCategory)
+ boolean access$500(NaturalSpawner$SpawnState,EntityType,BlockPos,ChunkAccess)
+ void <init>(int,Object2IntOpenHashMap,PotentialCalculator,NaturalSpawner$1)
+ void access$400(NaturalSpawner$SpawnState,Mob,ChunkAccess)
```

</details>



<details>
<summary>
net.minecraft.world.level.StructureFeatureManager
</summary>

```diff
- boolean lambda$getStructureAt$3(BlockPos,StructurePiece)
+ boolean lambda$null$3(BlockPos,StructurePiece)
```

</details>


<details>
<summary>
net.minecraft.world.level.biome.AmbientMoodSettings
</summary>

```diff
+ Double lambda$null$3(AmbientMoodSettings)
- Double lambda$static$3(AmbientMoodSettings)
+ Integer lambda$null$1(AmbientMoodSettings)
+ Integer lambda$null$2(AmbientMoodSettings)
- Integer lambda$static$1(AmbientMoodSettings)
- Integer lambda$static$2(AmbientMoodSettings)
+ SoundEvent lambda$null$0(AmbientMoodSettings)
- SoundEvent lambda$static$0(AmbientMoodSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ Biome lambda$null$13(Biome$ClimateSettings,Biome$BiomeCategory,Float,Float,BiomeSpecialEffects)
- Biome lambda$static$13(Biome$ClimateSettings,Biome$BiomeCategory,Float,Float,BiomeSpecialEffects)
+ Biome$BiomeCategory lambda$null$1(Biome)
+ Biome$BiomeCategory lambda$null$9(Biome)
- Biome$BiomeCategory lambda$static$1(Biome)
- Biome$BiomeCategory lambda$static$9(Biome)
+ Biome$ClimateSettings lambda$null$0(Biome)
+ Biome$ClimateSettings lambda$null$8(Biome)
- Biome$ClimateSettings lambda$static$0(Biome)
- Biome$ClimateSettings lambda$static$8(Biome)
+ BiomeGenerationSettings lambda$null$5(Biome)
- BiomeGenerationSettings lambda$static$5(Biome)
+ BiomeSpecialEffects lambda$null$12(Biome)
+ BiomeSpecialEffects lambda$null$4(Biome)
- BiomeSpecialEffects lambda$static$12(Biome)
- BiomeSpecialEffects lambda$static$4(Biome)
+ Float lambda$null$10(Biome)
+ Float lambda$null$11(Biome)
+ Float lambda$null$2(Biome)
+ Float lambda$null$3(Biome)
- Float lambda$static$10(Biome)
- Float lambda$static$11(Biome)
- Float lambda$static$2(Biome)
- Float lambda$static$3(Biome)
- Long2FloatLinkedOpenHashMap lambda$new$16()
+ Long2FloatLinkedOpenHashMap lambda$null$16()
+ MobSpawnSettings lambda$null$6(Biome)
- MobSpawnSettings lambda$static$6(Biome)
+ PerlinSimplexNoise access$100()
+ void <init>(Biome$ClimateSettings,Biome$BiomeCategory,float,float,BiomeSpecialEffects,BiomeGenerationSettings,MobSpawnSettings,Biome$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.biome.Biome$ClimateParameters
</summary>

```diff
+ Float lambda$null$0(Biome$ClimateParameters)
+ Float lambda$null$1(Biome$ClimateParameters)
+ Float lambda$null$2(Biome$ClimateParameters)
+ Float lambda$null$3(Biome$ClimateParameters)
+ Float lambda$null$4(Biome$ClimateParameters)
- Float lambda$static$0(Biome$ClimateParameters)
- Float lambda$static$1(Biome$ClimateParameters)
- Float lambda$static$2(Biome$ClimateParameters)
- Float lambda$static$3(Biome$ClimateParameters)
- Float lambda$static$4(Biome$ClimateParameters)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome$Precipitation
</summary>

```diff
- Biome$Precipitation[] $values()
```

</details>

<details>
<summary>
net.minecraft.world.level.biome.BiomeGenerationSettings
</summary>

```diff
+ List lambda$null$3(BiomeGenerationSettings)
+ List lambda$null$4(BiomeGenerationSettings)
- List lambda$static$3(BiomeGenerationSettings)
- List lambda$static$4(BiomeGenerationSettings)
+ Map lambda$null$2(BiomeGenerationSettings)
- Map lambda$static$2(BiomeGenerationSettings)
+ Supplier lambda$null$1(BiomeGenerationSettings)
- Supplier lambda$static$1(BiomeGenerationSettings)
+ void <init>(Supplier,Map,List,List,BiomeGenerationSettings$1)
```

</details>





<details>
<summary>
net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
</summary>

```diff
- FuzzyOffsetConstantColumnBiomeZoomer[] $values()
```

</details>

<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
</summary>

```diff
+ DataResult lambda$null$0(ResourceLocation)
+ DataResult lambda$null$1(ResourceLocation)
+ DataResult lambda$null$2(MultiNoiseBiomeSource$Preset)
- DataResult lambda$static$0(ResourceLocation)
- DataResult lambda$static$1(ResourceLocation)
- DataResult lambda$static$2(MultiNoiseBiomeSource$Preset)
+ void <init>(MultiNoiseBiomeSource$Preset,Registry,long,MultiNoiseBiomeSource$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.OverworldBiomeSource
</summary>

```diff
- Biome lambda$new$5(Registry,ResourceKey)
+ Biome lambda$null$5(Registry,ResourceKey)
+ Boolean lambda$null$1(OverworldBiomeSource)
+ Boolean lambda$null$2(OverworldBiomeSource)
- Boolean lambda$static$1(OverworldBiomeSource)
- Boolean lambda$static$2(OverworldBiomeSource)
+ Long lambda$null$0(OverworldBiomeSource)
- Long lambda$static$0(OverworldBiomeSource)
+ Registry lambda$null$3(OverworldBiomeSource)
- Registry lambda$static$3(OverworldBiomeSource)
```

</details>









































<details>
<summary>
net.minecraft.world.level.block.ComposterBlock
</summary>

```diff
+ BlockState access$000(BlockState,LevelAccessor,BlockPos)
+ BlockState access$100(BlockState,LevelAccessor,BlockPos,ItemStack)
```

</details>












<details>
<summary>
net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
</summary>

```diff
- DoubleBlockCombiner$BlockType[] $values()
```

</details>















































<details>
<summary>
net.minecraft.world.level.block.PowderSnowBlock
</summary>

```diff
+ void spawnPowderSnowParticles(Level,Vec3)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
</summary>

```diff
- PressurePlateBlock$Sensitivity[] $values()
```

</details>

























































<details>
<summary>
net.minecraft.world.level.block.entity.BannerPattern
</summary>

```diff
- BannerPattern[] $values()
+ String access$000(BannerPattern)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BarrelBlockEntity
</summary>

```diff
+ void access$000(BarrelBlockEntity,BlockState,SoundEvent)
+ void access$100(BarrelBlockEntity,BlockState,boolean)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.state.properties.RailShape
</summary>

```diff
- RailShape[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.SculkSensorPhase
</summary>

```diff
- SculkSensorPhase[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.StairsShape
</summary>

```diff
- StairsShape[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.Tilt
</summary>

```diff
- Tilt[] $values()
```

</details>


<details>
<summary>
net.minecraft.world.level.border.BorderStatus
</summary>

```diff
- BorderStatus[] $values()
```

</details>






<details>
<summary>
net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
</summary>

```diff
+ CompletableFuture access$100(IOWorker$PendingStore)
+ CompoundTag access$000(IOWorker$PendingStore)
+ CompoundTag access$002(IOWorker$PendingStore,CompoundTag)
```

</details>


<details>
<summary>
net.minecraft.world.level.chunk.storage.RegionFile
</summary>

```diff
+ RegionFileVersion access$000(RegionFile)
```

</details>


<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
+ void lambda$null$1(long)
- void lambda$readColumn$1(long)
```

</details>














<details>
<summary>
net.minecraft.world.level.entity.Visibility
</summary>

```diff
- Visibility[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.BlockPositionSource
</summary>

```diff
+ Optional access$000(BlockPositionSource)
+ Optional lambda$null$0(BlockPositionSource)
- Optional lambda$static$0(BlockPositionSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.EntityPositionSource
</summary>

```diff
+ int access$000(EntityPositionSource)
+ Integer lambda$null$0(EntityPositionSource)
- Integer lambda$static$0(EntityPositionSource)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus
</summary>

```diff
+ BlockState access$100(Aquifer$NoiseBasedAquifer$AquiferStatus)
+ int access$000(Aquifer$NoiseBasedAquifer$AquiferStatus)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.Cavifier$QuantizedSpaghettiRarity
</summary>

```diff
+ double access$000(double)
+ double access$100(double)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Column$Line
</summary>

```diff
+ Column$Line access$000()
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Carving
</summary>

```diff
- GenerationStep$Carving[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GeodeBlockSettings
</summary>

```diff
+ BlockStateProvider lambda$null$0(GeodeBlockSettings)
+ BlockStateProvider lambda$null$1(GeodeBlockSettings)
+ BlockStateProvider lambda$null$2(GeodeBlockSettings)
+ BlockStateProvider lambda$null$3(GeodeBlockSettings)
+ BlockStateProvider lambda$null$4(GeodeBlockSettings)
- BlockStateProvider lambda$static$0(GeodeBlockSettings)
- BlockStateProvider lambda$static$1(GeodeBlockSettings)
- BlockStateProvider lambda$static$2(GeodeBlockSettings)
- BlockStateProvider lambda$static$3(GeodeBlockSettings)
- BlockStateProvider lambda$static$4(GeodeBlockSettings)
+ List lambda$null$5(GeodeBlockSettings)
- List lambda$static$5(GeodeBlockSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GeodeLayerSettings
</summary>

```diff
+ Double lambda$null$0(GeodeLayerSettings)
+ Double lambda$null$1(GeodeLayerSettings)
+ Double lambda$null$2(GeodeLayerSettings)
+ Double lambda$null$3(GeodeLayerSettings)
- Double lambda$static$0(GeodeLayerSettings)
- Double lambda$static$1(GeodeLayerSettings)
- Double lambda$static$2(GeodeLayerSettings)
- Double lambda$static$3(GeodeLayerSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Heightmap$Types
</summary>

```diff
- Heightmap$Types[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ BiomeSource lambda$null$0(NoiseBasedChunkGenerator)
- BiomeSource lambda$static$0(NoiseBasedChunkGenerator)
+ int access$000(NoiseBasedChunkGenerator)
+ int access$100(NoiseBasedChunkGenerator)
+ int access$200(NoiseBasedChunkGenerator)
+ Long lambda$null$1(NoiseBasedChunkGenerator)
- Long lambda$static$1(NoiseBasedChunkGenerator)
+ NoodleCavifier access$400(NoiseBasedChunkGenerator)
+ OreVeinifier access$300(NoiseBasedChunkGenerator)
+ Supplier lambda$null$2(NoiseBasedChunkGenerator)
- Supplier lambda$static$2(NoiseBasedChunkGenerator)
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.WorldGenSettings
</summary>

```diff
+ Optional lambda$null$0(WorldGenSettings)
- Optional lambda$static$0(WorldGenSettings)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
</summary>

```diff
+ Float lambda$null$4(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ Float lambda$null$5(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Float lambda$static$4(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Float lambda$static$5(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$0(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$1(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$3(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$0(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$1(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$3(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ Integer lambda$null$2(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Integer lambda$static$2(CanyonCarverConfiguration$CanyonShapeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarverConfiguration
</summary>

```diff
+ Boolean lambda$null$4(CarverConfiguration)
- Boolean lambda$static$4(CarverConfiguration)
+ CarverDebugSettings lambda$null$5(CarverConfiguration)
- CarverDebugSettings lambda$static$5(CarverConfiguration)
+ Float lambda$null$0(CarverConfiguration)
- Float lambda$static$0(CarverConfiguration)
+ FloatProvider lambda$null$2(CarverConfiguration)
- FloatProvider lambda$static$2(CarverConfiguration)
+ HeightProvider lambda$null$1(CarverConfiguration)
- HeightProvider lambda$static$1(CarverConfiguration)
+ VerticalAnchor lambda$null$3(CarverConfiguration)
- VerticalAnchor lambda$static$3(CarverConfiguration)
```

</details>
























<details>
<summary>
net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
</summary>

```diff
+ Integer lambda$null$4(FossilFeatureConfiguration)
- Integer lambda$static$4(FossilFeatureConfiguration)
+ List lambda$null$0(FossilFeatureConfiguration)
+ List lambda$null$1(FossilFeatureConfiguration)
- List lambda$static$0(FossilFeatureConfiguration)
- List lambda$static$1(FossilFeatureConfiguration)
+ Supplier lambda$null$2(FossilFeatureConfiguration)
+ Supplier lambda$null$3(FossilFeatureConfiguration)
- Supplier lambda$static$2(FossilFeatureConfiguration)
- Supplier lambda$static$3(FossilFeatureConfiguration)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
</summary>

```diff
+ BlockState lambda$null$0(HugeFungusConfiguration)
+ BlockState lambda$null$1(HugeFungusConfiguration)
+ BlockState lambda$null$2(HugeFungusConfiguration)
+ BlockState lambda$null$3(HugeFungusConfiguration)
- BlockState lambda$static$0(HugeFungusConfiguration)
- BlockState lambda$static$1(HugeFungusConfiguration)
- BlockState lambda$static$2(HugeFungusConfiguration)
- BlockState lambda$static$3(HugeFungusConfiguration)
+ Boolean lambda$null$4(HugeFungusConfiguration)
- Boolean lambda$static$4(HugeFungusConfiguration)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature
</summary>

```diff
+ boolean access$100(JigsawFeature)
+ boolean access$200(JigsawFeature)
+ int access$000(JigsawFeature)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
</summary>

```diff
+ void <init>(SpikeFeature$1)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
</summary>

```diff
+ Float lambda$null$1(WeightedConfiguredFeature)
- Float lambda$static$1(WeightedConfiguredFeature)
+ Supplier lambda$null$0(WeightedConfiguredFeature)
- Supplier lambda$static$0(WeightedConfiguredFeature)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
</summary>

```diff
+ BlockState lambda$null$0(DiskConfiguration)
- BlockState lambda$static$0(DiskConfiguration)
+ Integer lambda$null$2(DiskConfiguration)
- Integer lambda$static$2(DiskConfiguration)
+ IntProvider lambda$null$1(DiskConfiguration)
- IntProvider lambda$static$1(DiskConfiguration)
+ List lambda$null$3(DiskConfiguration)
- List lambda$static$3(DiskConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
</summary>

```diff
+ Boolean lambda$null$1(EndGatewayConfiguration)
- Boolean lambda$static$1(EndGatewayConfiguration)
+ Optional lambda$null$0(EndGatewayConfiguration)
- Optional lambda$static$0(EndGatewayConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
</summary>

```diff
+ Boolean lambda$null$5(GeodeConfiguration)
- Boolean lambda$static$5(GeodeConfiguration)
+ Double lambda$null$11(GeodeConfiguration)
+ Double lambda$null$3(GeodeConfiguration)
+ Double lambda$null$4(GeodeConfiguration)
- Double lambda$static$11(GeodeConfiguration)
- Double lambda$static$3(GeodeConfiguration)
- Double lambda$static$4(GeodeConfiguration)
+ GeodeBlockSettings lambda$null$0(GeodeConfiguration)
- GeodeBlockSettings lambda$static$0(GeodeConfiguration)
+ GeodeCrackSettings lambda$null$2(GeodeConfiguration)
- GeodeCrackSettings lambda$static$2(GeodeConfiguration)
+ GeodeLayerSettings lambda$null$1(GeodeConfiguration)
- GeodeLayerSettings lambda$static$1(GeodeConfiguration)
+ Integer lambda$null$10(GeodeConfiguration)
+ Integer lambda$null$12(GeodeConfiguration)
+ Integer lambda$null$9(GeodeConfiguration)
- Integer lambda$static$10(GeodeConfiguration)
- Integer lambda$static$12(GeodeConfiguration)
- Integer lambda$static$9(GeodeConfiguration)
+ IntProvider lambda$null$6(GeodeConfiguration)
+ IntProvider lambda$null$7(GeodeConfiguration)
+ IntProvider lambda$null$8(GeodeConfiguration)
- IntProvider lambda$static$6(GeodeConfiguration)
- IntProvider lambda$static$7(GeodeConfiguration)
- IntProvider lambda$static$8(GeodeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GrowingPlantConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$2(GrowingPlantConfiguration)
+ BlockStateProvider lambda$null$3(GrowingPlantConfiguration)
- BlockStateProvider lambda$static$2(GrowingPlantConfiguration)
- BlockStateProvider lambda$static$3(GrowingPlantConfiguration)
+ Boolean lambda$null$4(GrowingPlantConfiguration)
- Boolean lambda$static$4(GrowingPlantConfiguration)
+ Direction lambda$null$1(GrowingPlantConfiguration)
- Direction lambda$static$1(GrowingPlantConfiguration)
+ SimpleWeightedRandomList lambda$null$0(GrowingPlantConfiguration)
- SimpleWeightedRandomList lambda$static$0(GrowingPlantConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$0(HugeMushroomFeatureConfiguration)
+ BlockStateProvider lambda$null$1(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$static$0(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$static$1(HugeMushroomFeatureConfiguration)
+ Integer lambda$null$2(HugeMushroomFeatureConfiguration)
- Integer lambda$static$2(HugeMushroomFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
</summary>

```diff
+ Float lambda$null$3(LargeDripstoneConfiguration)
+ Float lambda$null$8(LargeDripstoneConfiguration)
- Float lambda$static$3(LargeDripstoneConfiguration)
- Float lambda$static$8(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$2(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$4(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$5(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- FloatProvider lambda$static$2(LargeDripstoneConfiguration)
- FloatProvider lambda$static$4(LargeDripstoneConfiguration)
- FloatProvider lambda$static$5(LargeDripstoneConfiguration)
- FloatProvider lambda$static$6(LargeDripstoneConfiguration)
+ Integer lambda$null$0(LargeDripstoneConfiguration)
+ Integer lambda$null$7(LargeDripstoneConfiguration)
- Integer lambda$static$0(LargeDripstoneConfiguration)
- Integer lambda$static$7(LargeDripstoneConfiguration)
+ IntProvider lambda$null$1(LargeDripstoneConfiguration)
- IntProvider lambda$static$1(LargeDripstoneConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
</summary>

```diff
+ Float lambda$null$0(MineshaftConfiguration)
- Float lambda$static$0(MineshaftConfiguration)
+ MineshaftFeature$Type lambda$null$1(MineshaftConfiguration)
- MineshaftFeature$Type lambda$static$1(MineshaftConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
</summary>

```diff
+ Float lambda$null$1(OceanRuinConfiguration)
+ Float lambda$null$2(OceanRuinConfiguration)
- Float lambda$static$1(OceanRuinConfiguration)
- Float lambda$static$2(OceanRuinConfiguration)
+ OceanRuinFeature$Type lambda$null$0(OceanRuinConfiguration)
- OceanRuinFeature$Type lambda$static$0(OceanRuinConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
</summary>

```diff
+ List lambda$null$0(ReplaceBlockConfiguration)
- List lambda$static$0(ReplaceBlockConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$4(RootSystemConfiguration)
+ BlockStateProvider lambda$null$9(RootSystemConfiguration)
- BlockStateProvider lambda$static$4(RootSystemConfiguration)
- BlockStateProvider lambda$static$9(RootSystemConfiguration)
+ Integer lambda$null$1(RootSystemConfiguration)
+ Integer lambda$null$10(RootSystemConfiguration)
+ Integer lambda$null$11(RootSystemConfiguration)
+ Integer lambda$null$2(RootSystemConfiguration)
+ Integer lambda$null$5(RootSystemConfiguration)
+ Integer lambda$null$6(RootSystemConfiguration)
+ Integer lambda$null$7(RootSystemConfiguration)
+ Integer lambda$null$8(RootSystemConfiguration)
- Integer lambda$static$1(RootSystemConfiguration)
- Integer lambda$static$10(RootSystemConfiguration)
- Integer lambda$static$11(RootSystemConfiguration)
- Integer lambda$static$2(RootSystemConfiguration)
- Integer lambda$static$5(RootSystemConfiguration)
- Integer lambda$static$6(RootSystemConfiguration)
- Integer lambda$static$7(RootSystemConfiguration)
- Integer lambda$static$8(RootSystemConfiguration)
+ ResourceLocation lambda$null$3(RootSystemConfiguration)
- ResourceLocation lambda$static$3(RootSystemConfiguration)
+ Supplier lambda$null$0(RootSystemConfiguration)
- Supplier lambda$static$0(RootSystemConfiguration)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
</summary>

```diff
+ Boolean lambda$null$0(SpikeConfiguration)
- Boolean lambda$static$0(SpikeConfiguration)
+ List lambda$null$1(SpikeConfiguration)
- List lambda$static$1(SpikeConfiguration)
+ Optional lambda$null$2(SpikeConfiguration)
- Optional lambda$static$2(SpikeConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$0(TreeConfiguration)
+ BlockStateProvider lambda$null$2(TreeConfiguration)
+ BlockStateProvider lambda$null$4(TreeConfiguration)
- BlockStateProvider lambda$static$0(TreeConfiguration)
- BlockStateProvider lambda$static$2(TreeConfiguration)
- BlockStateProvider lambda$static$4(TreeConfiguration)
+ Boolean lambda$null$7(TreeConfiguration)
+ Boolean lambda$null$8(TreeConfiguration)
- Boolean lambda$static$7(TreeConfiguration)
- Boolean lambda$static$8(TreeConfiguration)
+ FeatureSize lambda$null$5(TreeConfiguration)
- FeatureSize lambda$static$5(TreeConfiguration)
+ FoliagePlacer lambda$null$3(TreeConfiguration)
- FoliagePlacer lambda$static$3(TreeConfiguration)
+ List lambda$null$6(TreeConfiguration)
- List lambda$static$6(TreeConfiguration)
+ TrunkPlacer lambda$null$1(TreeConfiguration)
- TrunkPlacer lambda$static$1(TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
</summary>

```diff
+ Float lambda$null$2(UnderwaterMagmaConfiguration)
- Float lambda$static$2(UnderwaterMagmaConfiguration)
+ Integer lambda$null$0(UnderwaterMagmaConfiguration)
+ Integer lambda$null$1(UnderwaterMagmaConfiguration)
- Integer lambda$static$0(UnderwaterMagmaConfiguration)
- Integer lambda$static$1(UnderwaterMagmaConfiguration)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
</summary>

```diff
+ Integer lambda$null$0(TwoLayersFeatureSize)
+ Integer lambda$null$1(TwoLayersFeatureSize)
+ Integer lambda$null$2(TwoLayersFeatureSize)
- Integer lambda$static$0(TwoLayersFeatureSize)
- Integer lambda$static$1(TwoLayersFeatureSize)
- Integer lambda$static$2(TwoLayersFeatureSize)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
</summary>

```diff
+ Integer lambda$null$0(MegaJungleFoliagePlacer)
- Integer lambda$static$0(MegaJungleFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
</summary>

```diff
+ IntProvider lambda$null$0(PineFoliagePlacer)
- IntProvider lambda$static$0(PineFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
</summary>

```diff
+ IntProvider lambda$null$0(SpruceFoliagePlacer)
- IntProvider lambda$static$0(SpruceFoliagePlacer)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
</summary>

```diff
+ void <init>(JunglePyramidPiece$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces
</summary>

```diff
+ Logger access$000()
+ MineShaftPieces$MineShaftPiece access$100(StructurePiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
















<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
</summary>

```diff
+ boolean access$100(OceanMonumentPieces$RoomDefinition)
+ boolean access$102(OceanMonumentPieces$RoomDefinition,boolean)
+ boolean access$902(OceanMonumentPieces$RoomDefinition,boolean)
+ boolean[] access$1100(OceanMonumentPieces$RoomDefinition)
+ int access$000(OceanMonumentPieces$RoomDefinition)
+ OceanMonumentPieces$RoomDefinition[] access$1000(OceanMonumentPieces$RoomDefinition)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
</summary>

```diff
- RuinedPortalPiece$VerticalPlacement[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.ShipwreckPieces
</summary>

```diff
+ BlockPos access$000()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces
</summary>

```diff
+ Class access$102(Class)
+ StrongholdPieces$SmoothStoneSelector access$200()
+ StructurePiece access$000(StrongholdPieces$StartPiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
</summary>

```diff
+ void <init>(StrongholdPieces$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
</summary>

```diff
- StrongholdPieces$StrongholdPiece$SmallDoorType[] $values()
```

</details>





<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
</summary>

```diff
+ Packet access$200(MapItemSavedData$HoldingPlayer,int)
+ void <init>(MapItemSavedData,Player,MapItemSavedData$1)
+ void access$300(MapItemSavedData$HoldingPlayer,int,int)
+ void access$400(MapItemSavedData$HoldingPlayer)
```

</details>



<details>
<summary>
net.minecraft.world.level.storage.loot.IntRange
</summary>

```diff
+ NumberProvider access$100(IntRange)
+ NumberProvider access$200(IntRange)
+ void <init>(NumberProvider,NumberProvider,IntRange$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.LootPool
</summary>

```diff
+ LootItemCondition[] access$400(LootPool)
+ LootItemFunction[] access$500(LootPool)
+ LootPoolEntryContainer[] access$300(LootPool)
+ NumberProvider access$100(LootPool)
+ NumberProvider access$200(LootPool)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],NumberProvider,NumberProvider,LootPool$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.entries.EmptyLootItem
</summary>

```diff
+ void <init>(int,int,LootItemCondition[],LootItemFunction[],EmptyLootItem$1)
```

</details>



<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
</summary>

```diff
+ BiFunction access$000(LootPoolSingletonContainer)
```

</details>






<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
</summary>

```diff
+ void <init>(LootItemCondition[],ApplyExplosionDecay$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
</summary>

```diff
+ void <init>(String,String,CopyNbtFunction$MergeStrategy,CopyNbtFunction$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
</summary>

```diff
- void lambda$merge$0(Tag,Tag)
+ void lambda$null$0(Tag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
</summary>

```diff
+ List access$100(EnchantRandomlyFunction)
+ void <init>(LootItemCondition[],Collection,EnchantRandomlyFunction$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
</summary>

```diff
+ boolean access$500(ExplorationMapFunction)
+ byte access$300(ExplorationMapFunction)
+ int access$400(ExplorationMapFunction)
+ Logger access$600()
+ MapDecoration$Type access$200(ExplorationMapFunction)
+ StructureFeature access$100(ExplorationMapFunction)
+ void <init>(LootItemCondition[],StructureFeature,MapDecoration$Type,byte,int,boolean,ExplorationMapFunction$1)
```

</details>




<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
</summary>

```diff
+ boolean access$200(LootingEnchantFunction)
+ int access$300(LootingEnchantFunction)
+ NumberProvider access$100(LootingEnchantFunction)
+ void <init>(LootItemCondition[],NumberProvider,int,LootingEnchantFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
</summary>

```diff
+ void <init>(boolean,SetBannerPatternFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetContainerContents
</summary>

```diff
+ List access$100(SetContainerContents)
+ void <init>(LootItemCondition[],List,SetContainerContents$1)
+ void lambda$null$0(NonNullList,LootContext,LootPoolEntry)
- void lambda$run$0(NonNullList,LootContext,LootPoolEntry)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
</summary>

```diff
+ boolean access$100(SetItemDamageFunction)
+ NumberProvider access$000(SetItemDamageFunction)
+ void <init>(LootItemCondition[],NumberProvider,boolean,SetItemDamageFunction$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
</summary>

```diff
+ void <init>(LootItemCondition[],SmeltItemFunction$1)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
</summary>

```diff
+ LootItemCondition[] access$100(AlternativeLootItemCondition)
+ void <init>(LootItemCondition[],AlternativeLootItemCondition$1)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
</summary>

```diff
+ LootContext$EntityTarget access$200(EntityHasScoreCondition)
+ Map access$100(EntityHasScoreCondition)
+ void <init>(Map,LootContext$EntityTarget,EntityHasScoreCondition$1)
```

</details>




<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
</summary>

```diff
+ EntityPredicate access$000(LootItemEntityPropertyCondition)
+ LootContext$EntityTarget access$100(LootItemEntityPropertyCondition)
+ void <init>(EntityPredicate,LootContext$EntityTarget,LootItemEntityPropertyCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
</summary>

```diff
+ float access$000(LootItemRandomChanceWithLootingCondition)
+ float access$100(LootItemRandomChanceWithLootingCondition)
+ void <init>(float,float,LootItemRandomChanceWithLootingCondition$1)
```

</details>







<details>
<summary>
net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
</summary>

```diff
+ ResourceLocation access$000(StorageNbtProvider)
+ void <init>(ResourceLocation,StorageNbtProvider$1)
```

</details>



<details>
<summary>
net.minecraft.world.level.timers.TimerQueue$Event
</summary>

```diff
+ void <init>(long,UnsignedLong,String,TimerCallback,TimerQueue$1)
```

</details>














<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
- boolean lambda$joinIsNotEmpty$1(BooleanOp,DiscreteVoxelShape,int,int,DiscreteVoxelShape,int,int,int,int,int)
- boolean lambda$joinIsNotEmpty$2(IndexMerger,BooleanOp,DiscreteVoxelShape,int,DiscreteVoxelShape,int,int,int,int)
+ boolean lambda$null$1(BooleanOp,DiscreteVoxelShape,int,int,DiscreteVoxelShape,int,int,int,int,int)
+ boolean lambda$null$2(IndexMerger,BooleanOp,DiscreteVoxelShape,int,DiscreteVoxelShape,int,int,int,int)
```

</details>





<details>
<summary>
net.minecraft.world.scores.Team$CollisionRule
</summary>

```diff
- Team$CollisionRule[] $values()
```

</details>
</details>