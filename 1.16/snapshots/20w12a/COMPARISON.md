## Comparison with [20w11a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w11a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">20w11a</th><th>20w12a</th></tr><tr><td>World version</td><td><pre>2513</pre></td><td><pre>2515</pre></td></tr><tr><td>Protocol version</td><td><pre>706</pre></td><td><pre>707</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w11a</th><th>20w12a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
+ minecraft:polished_basalt
+ minecraft:respawn_anchor
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:polished_basalt
+ minecraft:respawn_anchor
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:reverse_portal
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.respawn_anchor.ambient
+ minecraft:block.respawn_anchor.charge
+ minecraft:block.respawn_anchor.deplete
+ minecraft:block.respawn_anchor.set_spawn
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ polished_basalt.json
+ respawn_anchor.json
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<br/>
<table>
<tr><th>Name</th><th>20w11a</th><th>20w12a</th></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.sleep_in_bed.description</div></th><td>Change your respawn point</td><td>Sleep in a bed to change your respawn point</td></tr>
<tr><th align="left"><div style="width:290px">commands.spawnpoint.success.single</div></th><td>Set spawn point to %s, %s, %s for %s</td><td>Set spawn point to %s, %s, %s in %s for %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.spawnpoint.success.multiple</div></th><td>Set spawn point to %s, %s, %s for %s players</td><td>Set spawn point to %s, %s, %s in %s for %s players</td></tr>
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
- XXX.advancements.critereon.FishingHookPredicate
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
+ XXX.advancements.critereon.ItemUsedOnBlockTrigger
- XXX.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
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
+ XXX.advancements.critereon.SlideDownBlockTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
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
+ XXX.advancements.critereon.TargetBlockTrigger
- XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.TickTrigger
- XXX.advancements.critereon.TickTrigger$TriggerInstance
+ XXX.advancements.critereon.TradeTrigger
- XXX.advancements.critereon.TradeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.arguments.blocks.BlockInput
- XXX.arguments.blocks.BlockPredicateArgument
+ XXX.arguments.blocks.BlockPredicateArgument$1
- XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ XXX.arguments.blocks.BlockPredicateArgument$Result
- XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
+ XXX.arguments.blocks.BlockStateArgument
- XXX.arguments.blocks.BlockStateParser
+ XXX.arguments.blocks.package-info
- XXX.arguments.coordinates.BlockPosArgument
+ XXX.arguments.coordinates.ColumnPosArgument
- XXX.arguments.coordinates.Coordinates
+ XXX.arguments.coordinates.LocalCoordinates
- XXX.arguments.coordinates.package-info
- XXX.arguments.coordinates.RotationArgument
+ XXX.arguments.coordinates.SwizzleArgument
- XXX.arguments.coordinates.Vec2Argument
+ XXX.arguments.coordinates.Vec3Argument
- XXX.arguments.coordinates.WorldCoordinate
+ XXX.arguments.coordinates.WorldCoordinates
+ XXX.arguments.item.FunctionArgument
- XXX.arguments.item.FunctionArgument$1
+ XXX.arguments.item.FunctionArgument$2
- XXX.arguments.item.FunctionArgument$Result
+ XXX.arguments.item.ItemArgument
- XXX.arguments.item.ItemInput
+ XXX.arguments.item.ItemParser
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$ItemPredicate
- XXX.arguments.item.ItemPredicateArgument$Result
+ XXX.arguments.item.ItemPredicateArgument$TagPredicate
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelectorParser
+ XXX.arguments.selector.package-info
- XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$Properties
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState$1
- XXX.commands.arguments.ColorArgument
+ XXX.commands.arguments.ComponentArgument
- XXX.commands.arguments.CompoundTagArgument
+ XXX.commands.arguments.DimensionTypeArgument
- XXX.commands.arguments.EntityAnchorArgument
+ XXX.commands.arguments.EntityAnchorArgument$Anchor
- XXX.commands.arguments.EntityArgument
+ XXX.commands.arguments.EntityArgument$Serializer
- XXX.commands.arguments.EntitySummonArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.ItemEnchantmentArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.MobEffectArgument
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$ListElementFunction
- XXX.commands.arguments.NbtPathArgument$MatchElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchObjectNode
- XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ XXX.commands.arguments.NbtPathArgument$NbtPath
- XXX.commands.arguments.NbtPathArgument$Node
+ XXX.commands.arguments.NbtTagArgument
- XXX.commands.arguments.ObjectiveArgument
+ XXX.commands.arguments.ObjectiveCriteriaArgument
- XXX.commands.arguments.OperationArgument
+ XXX.commands.arguments.OperationArgument$Operation
- XXX.commands.arguments.OperationArgument$SimpleOperation
+ XXX.commands.arguments.package-info
+ XXX.commands.arguments.ParticleArgument
- XXX.commands.arguments.RangeArgument
+ XXX.commands.arguments.RangeArgument$Floats
- XXX.commands.arguments.RangeArgument$Floats$Serializer
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.RangeArgument$Ints$Serializer
+ XXX.commands.arguments.RangeArgument$Serializer
- XXX.commands.arguments.ResourceLocationArgument
+ XXX.commands.arguments.ScoreboardSlotArgument
+ XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Result
+ XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.ScoreHolderArgument$Serializer
- XXX.commands.arguments.SlotArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
- XXX.commands.exceptions.package-info
- XXX.commands.synchronization.ArgumentSerializer
+ XXX.commands.synchronization.ArgumentTypes
- XXX.commands.synchronization.ArgumentTypes$1
+ XXX.commands.synchronization.ArgumentTypes$Entry
- XXX.commands.synchronization.EmptyArgumentSerializer
+ XXX.commands.synchronization.package-info
+ XXX.commands.synchronization.SuggestionProviders
- XXX.commands.synchronization.SuggestionProviders$Wrapper
+ XXX.core.dispenser.AbstractProjectileDispenseBehavior
- XXX.core.dispenser.BoatDispenseItemBehavior
+ XXX.core.dispenser.DefaultDispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior$1
- XXX.core.dispenser.DispenseItemBehavior$10
+ XXX.core.dispenser.DispenseItemBehavior$11
- XXX.core.dispenser.DispenseItemBehavior$12
+ XXX.core.dispenser.DispenseItemBehavior$13
- XXX.core.dispenser.DispenseItemBehavior$14
+ XXX.core.dispenser.DispenseItemBehavior$15
- XXX.core.dispenser.DispenseItemBehavior$16
+ XXX.core.dispenser.DispenseItemBehavior$17
- XXX.core.dispenser.DispenseItemBehavior$18
+ XXX.core.dispenser.DispenseItemBehavior$19
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$20
- XXX.core.dispenser.DispenseItemBehavior$21
+ XXX.core.dispenser.DispenseItemBehavior$22
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.DustParticleOptions$1
+ XXX.core.particles.ItemParticleOption
- XXX.core.particles.ItemParticleOption$1
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdventureAdvancements
- XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.NetherAdvancements
- XXX.data.advancements.package-info
- XXX.data.advancements.StoryAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLoot
- XXX.data.loot.ChestLoot
+ XXX.data.loot.EntityLoot
- XXX.data.loot.FishingLoot
+ XXX.data.loot.GiftLoot
- XXX.data.loot.LootTableProvider
- XXX.data.loot.package-info
+ XXX.data.loot.PiglinBarterLoot
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ModelProvider
+ XXX.data.models.package-info
+ XXX.data.recipes.FinishedRecipe
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapedRecipeBuilder$Result
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder$Result
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder$Result
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder$Result
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder$1
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BlockTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
- XXX.data.tags.TagsProvider
- XXX.datafix.fixes.AbstractUUIDFix
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
+ XXX.datafix.fixes.EntityProjectileOwnerFix
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
- XXX.datafix.fixes.EntityUUIDFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.PoiTypeRename
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RenameBiomesFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.entity.monster.package-info
+ XXX.entity.monster.Zombie$1
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
- XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
+ XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.VillagerType$1
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Inventory
- XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.Boat$1
- XXX.entity.vehicle.Boat$Status
+ XXX.entity.vehicle.Boat$Type
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
+ XXX.gametest.framework.GameTestSequence
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
+ XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.Potions
+ XXX.item.alchemy.PotionUtils
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.Ingredient$1
+ XXX.item.crafting.Ingredient$ItemValue
- XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleRecipeSerializer
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.SuspiciousStewRecipe
- XXX.item.crafting.TippedArrowRecipe
- XXX.item.enchantment.ArrowDamageEnchantment
+ XXX.item.enchantment.ArrowFireEnchantment
- XXX.item.enchantment.ArrowInfiniteEnchantment
+ XXX.item.enchantment.ArrowKnockbackEnchantment
- XXX.item.enchantment.ArrowPiercingEnchantment
+ XXX.item.enchantment.BindingCurseEnchantment
- XXX.item.enchantment.DamageEnchantment
+ XXX.item.enchantment.DigDurabilityEnchantment
- XXX.item.enchantment.DiggingEnchantment
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$Rarity
+ XXX.item.enchantment.EnchantmentCategory
- XXX.item.enchantment.EnchantmentCategory$1
+ XXX.item.enchantment.EnchantmentCategory$10
- XXX.item.enchantment.EnchantmentCategory$11
+ XXX.item.enchantment.EnchantmentCategory$12
- XXX.item.enchantment.EnchantmentCategory$13
+ XXX.item.enchantment.EnchantmentCategory$14
- XXX.item.enchantment.EnchantmentCategory$2
+ XXX.item.enchantment.EnchantmentCategory$3
- XXX.item.enchantment.EnchantmentCategory$4
+ XXX.item.enchantment.EnchantmentCategory$5
- XXX.item.enchantment.EnchantmentCategory$6
+ XXX.item.enchantment.EnchantmentCategory$7
- XXX.item.enchantment.EnchantmentCategory$8
+ XXX.item.enchantment.EnchantmentCategory$9
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.FireAspectEnchantment
+ XXX.item.enchantment.FishingSpeedEnchantment
- XXX.item.enchantment.FrostWalkerEnchantment
+ XXX.item.enchantment.KnockbackEnchantment
- XXX.item.enchantment.LootBonusEnchantment
+ XXX.item.enchantment.MendingEnchantment
- XXX.item.enchantment.MultiShotEnchantment
+ XXX.item.enchantment.OxygenEnchantment
- XXX.item.enchantment.package-info
- XXX.item.enchantment.ProtectionEnchantment
+ XXX.item.enchantment.ProtectionEnchantment$Type
- XXX.item.enchantment.QuickChargeEnchantment
+ XXX.item.enchantment.SoulSpeedEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.ThornsEnchantment
- XXX.item.enchantment.TridentChannelingEnchantment
+ XXX.item.enchantment.TridentImpalerEnchantment
- XXX.item.enchantment.TridentLoyaltyEnchantment
+ XXX.item.enchantment.TridentRiptideEnchantment
- XXX.item.enchantment.UntouchingEnchantment
+ XXX.item.enchantment.VanishingCurseEnchantment
- XXX.item.enchantment.WaterWalkerEnchantment
+ XXX.item.enchantment.WaterWorkerEnchantment
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$3
+ XXX.level.block.Block$OffsetType
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
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
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
- XXX.level.block.RespawnAnchorBlock
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.minecraft.advancements.package-info
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CommandFunction
- XXX.minecraft.commands.CommandFunction$CacheableFunction
+ XXX.minecraft.commands.CommandFunction$CommandEntry
- XXX.minecraft.commands.CommandFunction$Entry
+ XXX.minecraft.commands.CommandFunction$FunctionEntry
- XXX.minecraft.commands.CommandRuntimeException
- XXX.minecraft.commands.Commands
+ XXX.minecraft.commands.Commands$ParseFunction
+ XXX.minecraft.commands.CommandSource
- XXX.minecraft.commands.CommandSource$1
+ XXX.minecraft.commands.CommandSourceStack
+ XXX.minecraft.commands.package-info
- XXX.minecraft.commands.SharedSuggestionProvider
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.core.AxisCycle
+ XXX.minecraft.core.AxisCycle$1
- XXX.minecraft.core.AxisCycle$2
+ XXX.minecraft.core.AxisCycle$3
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockSource
+ XXX.minecraft.core.BlockSourceImpl
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
+ XXX.minecraft.core.Direction$1
- XXX.minecraft.core.Direction$Axis
+ XXX.minecraft.core.Direction$Axis$1
- XXX.minecraft.core.Direction$Axis$2
+ XXX.minecraft.core.Direction$Axis$3
- XXX.minecraft.core.Direction$AxisDirection
+ XXX.minecraft.core.Direction$Plane
- XXX.minecraft.core.Direction8
+ XXX.minecraft.core.GlobalPos
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.LocatableSource
+ XXX.minecraft.core.Location
- XXX.minecraft.core.MapFiller
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.NonNullList
- XXX.minecraft.core.package-info
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.SerializableBoolean
- XXX.minecraft.core.SerializableLong
+ XXX.minecraft.core.SerializableUUID
- XXX.minecraft.core.Source
+ XXX.minecraft.core.Vec3i
- XXX.minecraft.core.WritableRegistry
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
- XXX.minecraft.data.package-info
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
+ XXX.minecraft.server.package-info
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
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.BlockTags$Wrapper
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.EntityTypeTags$Wrapper
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.FluidTags$Wrapper
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.ItemTags$Wrapper
- XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.SynchronizableTagCollection
- XXX.minecraft.tags.Tag
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.Tag$ValuesEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$Preparations
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$1
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.Deserializer
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InsensitiveStringMap
+ XXX.minecraft.util.IntRange
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LimitedCapacityList
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RewindableStream
- XXX.minecraft.util.RewindableStream$1
+ XXX.minecraft.util.Serializable
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$1
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$1
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$1
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$1
- XXX.models.blockstates.PropertyDispatch$C1
+ XXX.models.blockstates.PropertyDispatch$C2
- XXX.models.blockstates.PropertyDispatch$C3
+ XXX.models.blockstates.PropertyDispatch$C4
- XXX.models.blockstates.PropertyDispatch$C5
+ XXX.models.blockstates.PropertyDispatch$PentaFunction
- XXX.models.blockstates.PropertyDispatch$QuadFunction
+ XXX.models.blockstates.PropertyDispatch$TriFunction
- XXX.models.blockstates.PropertyValue
+ XXX.models.blockstates.Selector
- XXX.models.blockstates.Variant
+ XXX.models.blockstates.VariantProperties
- XXX.models.blockstates.VariantProperties$Rotation
+ XXX.models.blockstates.VariantProperty
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
+ XXX.models.model.ModelLocationUtils
- XXX.models.model.ModelTemplate
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.Piglin$PiglinArmPose
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
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
+ XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackRepository
- XXX.packs.repository.RepositorySource
+ XXX.packs.repository.ServerPacksSource
- XXX.packs.repository.UnopenedPack
+ XXX.packs.repository.UnopenedPack$Position
- XXX.packs.repository.UnopenedPack$UnopenedPackConstructor
- XXX.packs.resources.FallbackResourceManager
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.package-info
- XXX.packs.resources.PreparableReloadListener
+ XXX.packs.resources.PreparableReloadListener$PreparationBarrier
- XXX.packs.resources.ProfiledReloadInstance
+ XXX.packs.resources.ProfiledReloadInstance$1
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadableResourceManager
- XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.packs.resources.SimpleResource
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
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
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
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
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
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.selector.options.EntitySelectorOptions
+ XXX.selector.options.EntitySelectorOptions$1
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
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
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
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
+ XXX.server.commands.LocateBiomeCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LootCommand
- XXX.server.commands.LootCommand$Callback
+ XXX.server.commands.LootCommand$DropConsumer
- XXX.server.commands.LootCommand$TailProvider
+ XXX.server.commands.MsgCommand
- XXX.server.commands.OpCommand
+ XXX.server.commands.package-info
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
+ XXX.server.commands.SpectateCommand
- XXX.server.commands.SpreadPlayersCommand
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
+ XXX.server.commands.TeleportCommand$LookAt
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServer$2
- XXX.server.dedicated.DedicatedServerProperties
+ XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$1
- XXX.server.dedicated.Settings$MutableValue
- XXX.server.gui.MinecraftServerGui
+ XXX.server.gui.MinecraftServerGui$1
- XXX.server.gui.MinecraftServerGui$2
+ XXX.server.gui.package-info
+ XXX.server.gui.PlayerListComponent
- XXX.server.gui.StatsComponent
- XXX.server.level.BlockDestructionProgress
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$1
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure
- XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
+ XXX.server.level.ChunkHolder$FullChunkStatus
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$1
- XXX.server.level.ChunkMap$2
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$1
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DerivedServerLevel
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FeatureSimulator
+ XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$1
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.WorldGenRegion
- XXX.server.level.WorldGenTickList
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.packs.AbstractResourcePack
+ XXX.server.packs.FileResourcePack
- XXX.server.packs.FolderResourcePack
+ XXX.server.packs.Pack
- XXX.server.packs.package-info
- XXX.server.packs.PackType
+ XXX.server.packs.ResourcePackFileNotFoundException
- XXX.server.packs.VanillaPack
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$2
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.GameProfileCache$Serializer
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
+ XXX.synchronization.brigadier.BrigadierArgumentSerializers
- XXX.synchronization.brigadier.DoubleArgumentSerializer
+ XXX.synchronization.brigadier.FloatArgumentSerializer
- XXX.synchronization.brigadier.IntegerArgumentSerializer
+ XXX.synchronization.brigadier.LongArgumentSerializer
- XXX.synchronization.brigadier.package-info
- XXX.synchronization.brigadier.StringArgumentSerializer
+ XXX.synchronization.brigadier.StringArgumentSerializer$1
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.OminousBannerBlockEntityRenameFix
+ XXX.util.datafix.OminousBannerRenameFix
- XXX.world.entity.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$1
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.AnvilMenu$1
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$FuelSlot
+ XXX.world.inventory.BrewingStandMenu$IngredientsSlot
- XXX.world.inventory.BrewingStandMenu$PotionSlot
+ XXX.world.inventory.CartographyTableMenu
- XXX.world.inventory.CartographyTableMenu$1
+ XXX.world.inventory.CartographyTableMenu$2
- XXX.world.inventory.CartographyTableMenu$3
+ XXX.world.inventory.CartographyTableMenu$4
- XXX.world.inventory.CartographyTableMenu$5
+ XXX.world.inventory.ChestMenu
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.CraftingContainer
+ XXX.world.inventory.CraftingMenu
- XXX.world.inventory.DataSlot
+ XXX.world.inventory.DataSlot$1
- XXX.world.inventory.DataSlot$2
+ XXX.world.inventory.DataSlot$3
- XXX.world.inventory.DispenserMenu
+ XXX.world.inventory.EnchantmentMenu
- XXX.world.inventory.EnchantmentMenu$1
+ XXX.world.inventory.EnchantmentMenu$2
- XXX.world.inventory.EnchantmentMenu$3
+ XXX.world.inventory.FurnaceFuelSlot
- XXX.world.inventory.FurnaceMenu
+ XXX.world.inventory.FurnaceResultSlot
- XXX.world.inventory.GrindstoneMenu
+ XXX.world.inventory.GrindstoneMenu$1
- XXX.world.inventory.GrindstoneMenu$2
+ XXX.world.inventory.GrindstoneMenu$3
- XXX.world.inventory.GrindstoneMenu$4
+ XXX.world.inventory.HopperMenu
- XXX.world.inventory.HorseInventoryMenu
+ XXX.world.inventory.HorseInventoryMenu$1
- XXX.world.inventory.HorseInventoryMenu$2
+ XXX.world.inventory.InventoryMenu
- XXX.world.inventory.InventoryMenu$1
+ XXX.world.inventory.InventoryMenu$2
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.LecternMenu
- XXX.world.inventory.LecternMenu$1
+ XXX.world.inventory.LoomMenu
- XXX.world.inventory.LoomMenu$1
+ XXX.world.inventory.LoomMenu$2
- XXX.world.inventory.LoomMenu$3
+ XXX.world.inventory.LoomMenu$4
- XXX.world.inventory.LoomMenu$5
+ XXX.world.inventory.LoomMenu$6
- XXX.world.inventory.MenuConstructor
+ XXX.world.inventory.MenuType
- XXX.world.inventory.MenuType$MenuSupplier
+ XXX.world.inventory.MerchantContainer
- XXX.world.inventory.MerchantMenu
+ XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
- XXX.world.item.AirItem
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorItem$1
+ XXX.world.item.ArmorMaterial
- XXX.world.item.ArmorMaterials
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BannerPatternItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BlockPlaceContext
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
+ XXX.world.item.BucketItem
- XXX.world.item.CarrotOnAStickItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.ClockItem
+ XXX.world.item.ClockItem$1
- XXX.world.item.CompassItem
+ XXX.world.item.CompassItem$1
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$10
- XXX.world.item.CreativeModeTab$11
+ XXX.world.item.CreativeModeTab$12
- XXX.world.item.CreativeModeTab$2
+ XXX.world.item.CreativeModeTab$3
- XXX.world.item.CreativeModeTab$4
+ XXX.world.item.CreativeModeTab$5
- XXX.world.item.CreativeModeTab$6
+ XXX.world.item.CreativeModeTab$7
- XXX.world.item.CreativeModeTab$8
+ XXX.world.item.CreativeModeTab$9
- XXX.world.item.CrossbowItem
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DirectionalPlaceContext
- XXX.world.item.DirectionalPlaceContext$1
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeableArmorItem
+ XXX.world.item.DyeableHorseArmorItem
- XXX.world.item.DyeableLeatherItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.ElytraItem
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EnchantedBookItem
+ XXX.world.item.EnchantedGoldenAppleItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FireworkRocketItem$Shape
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishBucketItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneyBottleItem
+ XXX.world.item.HorseArmorItem
- XXX.world.item.Item
+ XXX.world.item.Item$1
- XXX.world.item.Item$Properties
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$1
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemFrameItem
+ XXX.world.item.ItemNameBlockItem
- XXX.world.item.ItemPropertyFunction
- XXX.world.item.Items
+ XXX.world.item.ItemStack
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MapItem
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
- XXX.world.item.NameTagItem
+ XXX.world.item.package-info
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.ProjectileWeaponItem$Type
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignItem
+ XXX.world.item.SimpleFoiledItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.Tier
+ XXX.world.item.TieredItem
- XXX.world.item.Tiers
+ XXX.world.item.TippedArrowItem
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
- XXX.world.item.UseOnContext
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkTickList
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.CollisionGetter$1
- XXX.world.level.ColorResolver
+ XXX.world.level.CustomSpawner
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EmptyTickList
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$1
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelConflictException
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelType
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NoiseColumn
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- XXX.advancements.critereon.FishingHookPredicate
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
+ XXX.advancements.critereon.ItemUsedOnBlockTrigger
- XXX.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
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
+ XXX.advancements.critereon.SlideDownBlockTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
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
+ XXX.advancements.critereon.TargetBlockTrigger
- XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.TickTrigger
- XXX.advancements.critereon.TickTrigger$TriggerInstance
+ XXX.advancements.critereon.TradeTrigger
- XXX.advancements.critereon.TradeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.arguments.blocks.BlockInput
- XXX.arguments.blocks.BlockPredicateArgument
+ XXX.arguments.blocks.BlockPredicateArgument$1
- XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ XXX.arguments.blocks.BlockPredicateArgument$Result
- XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
+ XXX.arguments.blocks.BlockStateArgument
- XXX.arguments.blocks.BlockStateParser
+ XXX.arguments.blocks.package-info
- XXX.arguments.coordinates.BlockPosArgument
+ XXX.arguments.coordinates.ColumnPosArgument
- XXX.arguments.coordinates.Coordinates
+ XXX.arguments.coordinates.LocalCoordinates
- XXX.arguments.coordinates.package-info
- XXX.arguments.coordinates.RotationArgument
+ XXX.arguments.coordinates.SwizzleArgument
- XXX.arguments.coordinates.Vec2Argument
+ XXX.arguments.coordinates.Vec3Argument
- XXX.arguments.coordinates.WorldCoordinate
+ XXX.arguments.coordinates.WorldCoordinates
+ XXX.arguments.item.FunctionArgument
- XXX.arguments.item.FunctionArgument$1
+ XXX.arguments.item.FunctionArgument$2
- XXX.arguments.item.FunctionArgument$Result
+ XXX.arguments.item.ItemArgument
- XXX.arguments.item.ItemInput
+ XXX.arguments.item.ItemParser
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$ItemPredicate
- XXX.arguments.item.ItemPredicateArgument$Result
+ XXX.arguments.item.ItemPredicateArgument$TagPredicate
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelectorParser
+ XXX.arguments.selector.package-info
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
+ XXX.block.model.ItemOverrides
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.ItemTransforms$TransformType
- XXX.block.model.MultiVariant
+ XXX.block.model.MultiVariant$Deserializer
+ XXX.block.model.package-info
- XXX.block.model.Variant
+ XXX.block.model.Variant$Deserializer
- XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$Properties
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState$1
+ XXX.block.statemap.package-info
- XXX.client.gui.Font
+ XXX.client.gui.Gui
- XXX.client.gui.GuiComponent
+ XXX.client.gui.MapRenderer
- XXX.client.gui.MapRenderer$1
+ XXX.client.gui.MapRenderer$MapInstance
+ XXX.client.gui.package-info
+ XXX.client.main.GameConfig
- XXX.client.main.GameConfig$FolderData
+ XXX.client.main.GameConfig$GameData
- XXX.client.main.GameConfig$ServerData
+ XXX.client.main.GameConfig$UserData
- XXX.client.main.Main
+ XXX.client.main.Main$1
- XXX.client.main.Main$2
+ XXX.client.main.Main$3
+ XXX.client.main.package-info
- XXX.client.main.SilentInitException
- XXX.client.map.Map
+ XXX.client.map.Map$1
- XXX.client.map.Map$2
+ XXX.client.map.Map$3
- XXX.client.map.package-info
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AgeableListModel
+ XXX.client.model.AnimationUtils
- XXX.client.model.ArmedModel
+ XXX.client.model.ArmorStandArmorModel
- XXX.client.model.ArmorStandModel
+ XXX.client.model.BatModel
- XXX.client.model.BeeModel
+ XXX.client.model.BlazeModel
- XXX.client.model.BoatModel
+ XXX.client.model.BookModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestedHorseModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColorableAgeableListModel
+ XXX.client.model.ColorableListModel
- XXX.client.model.CowModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FoxModel
- XXX.client.model.GhastModel
+ XXX.client.model.GiantZombieModel
- XXX.client.model.GuardianModel
+ XXX.client.model.HeadedModel
- XXX.client.model.HoglinModel
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
- XXX.client.model.package-info
+ XXX.client.model.PandaModel
- XXX.client.model.ParrotModel
+ XXX.client.model.ParrotModel$1
- XXX.client.model.ParrotModel$State
+ XXX.client.model.PhantomModel
+ XXX.client.model.PiglinModel
- XXX.client.model.PigModel
- XXX.client.model.PlayerModel
+ XXX.client.model.PolarBearModel
- XXX.client.model.PufferfishBigModel
+ XXX.client.model.PufferfishMidModel
- XXX.client.model.PufferfishSmallModel
+ XXX.client.model.QuadrupedModel
- XXX.client.model.RabbitModel
+ XXX.client.model.RavagerModel
- XXX.client.model.SalmonModel
+ XXX.client.model.SheepFurModel
- XXX.client.model.SheepModel
+ XXX.client.model.ShieldModel
- XXX.client.model.ShulkerBulletModel
+ XXX.client.model.ShulkerModel
- XXX.client.model.SilverfishModel
+ XXX.client.model.SkeletonModel
- XXX.client.model.SkullModel
+ XXX.client.model.SlimeModel
- XXX.client.model.SnowGolemModel
+ XXX.client.model.SpiderModel
- XXX.client.model.SquidModel
+ XXX.client.model.TridentModel
- XXX.client.model.TropicalFishModelA
+ XXX.client.model.TropicalFishModelB
- XXX.client.model.TurtleModel
+ XXX.client.model.VexModel
- XXX.client.model.VillagerHeadModel
+ XXX.client.model.VillagerModel
- XXX.client.model.WitchModel
+ XXX.client.model.WitherBossModel
- XXX.client.model.WolfModel
+ XXX.client.model.ZombieModel
- XXX.client.model.ZombieVillagerModel
+ XXX.client.multiplayer.ClientAdvancements
- XXX.client.multiplayer.ClientAdvancements$Listener
+ XXX.client.multiplayer.ClientChunkCache
- XXX.client.multiplayer.ClientChunkCache$1
+ XXX.client.multiplayer.ClientChunkCache$Storage
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientLevel
- XXX.client.multiplayer.ClientLevel$1
+ XXX.client.multiplayer.ClientPacketListener
- XXX.client.multiplayer.ClientPacketListener$1
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.MultiPlayerGameMode
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
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$1
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BarrierParticle
- XXX.client.particle.BarrierParticle$1
+ XXX.client.particle.BarrierParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BreakingItemParticle
- XXX.client.particle.BreakingItemParticle$1
+ XXX.client.particle.BreakingItemParticle$Provider
- XXX.client.particle.BreakingItemParticle$SlimeProvider
+ XXX.client.particle.BreakingItemParticle$SnowballProvider
- XXX.client.particle.BubbleColumnUpParticle
+ XXX.client.particle.BubbleColumnUpParticle$1
- XXX.client.particle.BubbleColumnUpParticle$Provider
+ XXX.client.particle.BubbleParticle
- XXX.client.particle.BubbleParticle$1
+ XXX.client.particle.BubbleParticle$Provider
- XXX.client.particle.BubblePopParticle
+ XXX.client.particle.BubblePopParticle$1
- XXX.client.particle.BubblePopParticle$Provider
+ XXX.client.particle.CampfireSmokeParticle
- XXX.client.particle.CampfireSmokeParticle$1
+ XXX.client.particle.CampfireSmokeParticle$CosyProvider
- XXX.client.particle.CampfireSmokeParticle$SignalProvider
+ XXX.client.particle.CritParticle
- XXX.client.particle.CritParticle$1
+ XXX.client.particle.CritParticle$DamageIndicatorProvider
- XXX.client.particle.CritParticle$MagicProvider
+ XXX.client.particle.CritParticle$Provider
- XXX.client.particle.DragonBreathParticle
+ XXX.client.particle.DragonBreathParticle$1
- XXX.client.particle.DragonBreathParticle$Provider
+ XXX.client.particle.DripParticle
- XXX.client.particle.DripParticle$1
+ XXX.client.particle.DripParticle$CoolingDripHangParticle
- XXX.client.particle.DripParticle$DripHangParticle
+ XXX.client.particle.DripParticle$DripLandParticle
- XXX.client.particle.DripParticle$FallAndLandParticle
+ XXX.client.particle.DripParticle$FallingParticle
- XXX.client.particle.DripParticle$HoneyFallAndLandParticle
+ XXX.client.particle.DripParticle$HoneyFallProvider
- XXX.client.particle.DripParticle$HoneyHangProvider
+ XXX.client.particle.DripParticle$HoneyLandProvider
- XXX.client.particle.DripParticle$LavaFallProvider
+ XXX.client.particle.DripParticle$LavaHangProvider
- XXX.client.particle.DripParticle$LavaLandProvider
+ XXX.client.particle.DripParticle$NectarFallProvider
- XXX.client.particle.DripParticle$ObsidianTearFallProvider
+ XXX.client.particle.DripParticle$ObsidianTearHangProvider
- XXX.client.particle.DripParticle$ObsidianTearLandProvider
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
- XXX.client.particle.ReversePortalParticle$1
- XXX.client.particle.RisingParticle
+ XXX.client.particle.SimpleAnimatedParticle
- XXX.client.particle.SingleQuadParticle
+ XXX.client.particle.SmokeParticle
- XXX.client.particle.SmokeParticle$Provider
+ XXX.client.particle.SoulParticle
- XXX.client.particle.SoulParticle$1
+ XXX.client.particle.SoulParticle$Provider
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
+ XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
- XXX.client.particle.SuspendedParticle$UnderwaterProvider
+ XXX.client.particle.SuspendedParticle$WarpedSporeProvider
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
- XXX.client.renderer.BlockEntityWithoutLevelRenderer
+ XXX.client.renderer.ChunkBufferBuilderPack
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.EffectInstance
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$1
- XXX.client.renderer.FaceInfo$Constants
+ XXX.client.renderer.FaceInfo$VertexInfo
- XXX.client.renderer.FogRenderer
+ XXX.client.renderer.FogRenderer$FogMode
- XXX.client.renderer.GameRenderer
+ XXX.client.renderer.ItemBlockRenderTypes
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
- XXX.client.renderer.package-info
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$AlphaStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
- XXX.client.renderer.RenderStateShard$CullStateShard
+ XXX.client.renderer.RenderStateShard$DepthTestStateShard
- XXX.client.renderer.RenderStateShard$DiffuseLightingStateShard
+ XXX.client.renderer.RenderStateShard$FogStateShard
- XXX.client.renderer.RenderStateShard$LayeringStateShard
+ XXX.client.renderer.RenderStateShard$LightmapStateShard
- XXX.client.renderer.RenderStateShard$LineStateShard
+ XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
- XXX.client.renderer.RenderStateShard$OutputStateShard
+ XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$PortalTexturingStateShard
+ XXX.client.renderer.RenderStateShard$ShadeModelStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
+ XXX.client.renderer.RenderStateShard$WriteMaskStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$1
- XXX.client.renderer.RenderType$CompositeRenderType
+ XXX.client.renderer.RenderType$CompositeRenderType$EqualsStrategy
- XXX.client.renderer.RenderType$CompositeState
+ XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- XXX.client.renderer.RenderType$OutlineProperty
+ XXX.client.renderer.RunningTrimmedMean
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.client.resources.AssetIndex
+ XXX.client.resources.ClientPackSource
- XXX.client.resources.ClientPackSource$1
+ XXX.client.resources.ClientPackSource$2
- XXX.client.resources.DefaultClientResourcePack
+ XXX.client.resources.DefaultPlayerSkin
- XXX.client.resources.DirectAssetIndex
+ XXX.client.resources.FoliageColorReloadListener
- XXX.client.resources.GrassColorReloadListener
+ XXX.client.resources.LegacyResourcePackAdapter
- XXX.client.resources.LegacyStuffWrapper
+ XXX.client.resources.MobEffectTextureManager
- XXX.client.resources.PackAdapterV4
+ XXX.client.resources.package-info
+ XXX.client.resources.PaintingTextureManager
- XXX.client.resources.SkinManager
+ XXX.client.resources.SkinManager$1
- XXX.client.resources.SkinManager$SkinTextureCallback
+ XXX.client.resources.SplashManager
- XXX.client.resources.TextureAtlasHolder
+ XXX.client.resources.UnopenedResourcePack
+ XXX.client.searchtree.MutableSearchTree
+ XXX.client.searchtree.package-info
- XXX.client.searchtree.ReloadableIdSearchTree
+ XXX.client.searchtree.ReloadableIdSearchTree$IntersectionIterator
- XXX.client.searchtree.ReloadableSearchTree
+ XXX.client.searchtree.ReloadableSearchTree$MergingUniqueIterator
- XXX.client.searchtree.SearchRegistry
+ XXX.client.searchtree.SearchRegistry$Key
- XXX.client.searchtree.SearchTree
+ XXX.client.searchtree.SuffixArray
- XXX.client.searchtree.SuffixArray$1
- XXX.client.server.IntegratedPlayerList
+ XXX.client.server.IntegratedServer
- XXX.client.server.LanServer
+ XXX.client.server.LanServerDetection
- XXX.client.server.LanServerDetection$LanServerDetector
+ XXX.client.server.LanServerDetection$LanServerList
- XXX.client.server.LanServerPinger
+ XXX.client.server.package-info
- XXX.client.skins.package-info
+ XXX.client.sounds.AudioStream
- XXX.client.sounds.ChannelAccess
+ XXX.client.sounds.ChannelAccess$ChannelHandle
- XXX.client.sounds.LoopingAudioStream
+ XXX.client.sounds.LoopingAudioStream$1
- XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
+ XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
- XXX.client.sounds.MusicManager
+ XXX.client.sounds.MusicManager$Music
+ XXX.client.sounds.package-info
- XXX.client.sounds.SoundBufferLibrary
+ XXX.client.sounds.SoundEngine
- XXX.client.sounds.SoundEngineExecutor
+ XXX.client.sounds.SoundEventListener
- XXX.client.sounds.SoundManager
+ XXX.client.sounds.SoundManager$1
- XXX.client.sounds.SoundManager$2
+ XXX.client.sounds.SoundManager$Preparations
- XXX.client.sounds.SoundManager$Preparations$1
+ XXX.client.sounds.WeighedSoundEvents
- XXX.client.sounds.Weighted
- XXX.client.tutorial.CompletedTutorialStepInstance
+ XXX.client.tutorial.CraftPlanksTutorialStep
- XXX.client.tutorial.FindTreeTutorialStepInstance
+ XXX.client.tutorial.MovementTutorialStepInstance
- XXX.client.tutorial.OpenInventoryTutorialStep
+ XXX.client.tutorial.package-info
+ XXX.client.tutorial.PunchTreeTutorialStepInstance
- XXX.client.tutorial.Tutorial
+ XXX.client.tutorial.TutorialStepInstance
- XXX.client.tutorial.TutorialSteps
+ XXX.color.block.BlockColor
- XXX.color.block.BlockColors
+ XXX.color.block.BlockTintCache
- XXX.color.block.BlockTintCache$1
+ XXX.color.block.BlockTintCache$LatestCacheInfo
- XXX.color.block.package-info
+ XXX.color.item.ItemColor
- XXX.color.item.ItemColors
+ XXX.color.item.package-info
- XXX.commands.arguments.ColorArgument
+ XXX.commands.arguments.ComponentArgument
- XXX.commands.arguments.CompoundTagArgument
+ XXX.commands.arguments.DimensionTypeArgument
- XXX.commands.arguments.EntityAnchorArgument
+ XXX.commands.arguments.EntityAnchorArgument$Anchor
- XXX.commands.arguments.EntityArgument
+ XXX.commands.arguments.EntityArgument$Serializer
- XXX.commands.arguments.EntitySummonArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.ItemEnchantmentArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.MobEffectArgument
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$ListElementFunction
- XXX.commands.arguments.NbtPathArgument$MatchElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchObjectNode
- XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ XXX.commands.arguments.NbtPathArgument$NbtPath
- XXX.commands.arguments.NbtPathArgument$Node
+ XXX.commands.arguments.NbtTagArgument
- XXX.commands.arguments.ObjectiveArgument
+ XXX.commands.arguments.ObjectiveCriteriaArgument
- XXX.commands.arguments.OperationArgument
+ XXX.commands.arguments.OperationArgument$Operation
- XXX.commands.arguments.OperationArgument$SimpleOperation
+ XXX.commands.arguments.package-info
+ XXX.commands.arguments.ParticleArgument
- XXX.commands.arguments.RangeArgument
+ XXX.commands.arguments.RangeArgument$Floats
- XXX.commands.arguments.RangeArgument$Floats$Serializer
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.RangeArgument$Ints$Serializer
+ XXX.commands.arguments.RangeArgument$Serializer
- XXX.commands.arguments.ResourceLocationArgument
+ XXX.commands.arguments.ScoreboardSlotArgument
+ XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Result
+ XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.ScoreHolderArgument$Serializer
- XXX.commands.arguments.SlotArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
- XXX.commands.exceptions.package-info
- XXX.commands.synchronization.ArgumentSerializer
+ XXX.commands.synchronization.ArgumentTypes
- XXX.commands.synchronization.ArgumentTypes$1
+ XXX.commands.synchronization.ArgumentTypes$Entry
- XXX.commands.synchronization.EmptyArgumentSerializer
+ XXX.commands.synchronization.package-info
+ XXX.commands.synchronization.SuggestionProviders
- XXX.commands.synchronization.SuggestionProviders$Wrapper
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.toasts.AdvancementToast
- XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastIds
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$1
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
+ XXX.core.dispenser.AbstractProjectileDispenseBehavior
- XXX.core.dispenser.BoatDispenseItemBehavior
+ XXX.core.dispenser.DefaultDispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior$1
- XXX.core.dispenser.DispenseItemBehavior$10
+ XXX.core.dispenser.DispenseItemBehavior$11
- XXX.core.dispenser.DispenseItemBehavior$12
+ XXX.core.dispenser.DispenseItemBehavior$13
- XXX.core.dispenser.DispenseItemBehavior$14
+ XXX.core.dispenser.DispenseItemBehavior$15
- XXX.core.dispenser.DispenseItemBehavior$16
+ XXX.core.dispenser.DispenseItemBehavior$17
- XXX.core.dispenser.DispenseItemBehavior$18
+ XXX.core.dispenser.DispenseItemBehavior$19
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$20
- XXX.core.dispenser.DispenseItemBehavior$21
+ XXX.core.dispenser.DispenseItemBehavior$22
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.DustParticleOptions$1
+ XXX.core.particles.ItemParticleOption
- XXX.core.particles.ItemParticleOption$1
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdventureAdvancements
- XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.NetherAdvancements
- XXX.data.advancements.package-info
- XXX.data.advancements.StoryAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLoot
- XXX.data.loot.ChestLoot
+ XXX.data.loot.EntityLoot
- XXX.data.loot.FishingLoot
+ XXX.data.loot.GiftLoot
- XXX.data.loot.LootTableProvider
- XXX.data.loot.package-info
+ XXX.data.loot.PiglinBarterLoot
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ModelProvider
+ XXX.data.models.package-info
+ XXX.data.recipes.FinishedRecipe
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapedRecipeBuilder$Result
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder$Result
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder$Result
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder$Result
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder$1
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BlockTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
- XXX.data.tags.TagsProvider
- XXX.datafix.fixes.AbstractUUIDFix
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
+ XXX.datafix.fixes.EntityProjectileOwnerFix
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
- XXX.datafix.fixes.EntityUUIDFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.PoiTypeRename
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RenameBiomesFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.ReorganizePoi
- XXX.entity.layers.AbstractArmorLayer
+ XXX.entity.layers.ArrowLayer
- XXX.entity.layers.BeeStingerLayer
+ XXX.entity.layers.CapeLayer
- XXX.entity.layers.CarriedBlockLayer
+ XXX.entity.layers.CatCollarLayer
- XXX.entity.layers.CreeperPowerLayer
+ XXX.entity.layers.CrossedArmsItemLayer
- XXX.entity.layers.CustomHeadLayer
+ XXX.entity.layers.Deadmau5EarsLayer
- XXX.entity.layers.DolphinCarryingItemLayer
+ XXX.entity.layers.DrownedOuterLayer
- XXX.entity.layers.ElytraLayer
+ XXX.entity.layers.EnderEyesLayer
- XXX.entity.layers.EnergySwirlLayer
+ XXX.entity.layers.EyesLayer
- XXX.entity.layers.FoxHeldItemLayer
+ XXX.entity.layers.HorseArmorLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
- XXX.entity.layers.package-info
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PiglinArmorLayer
- XXX.entity.layers.PigSaddleLayer
- XXX.entity.layers.RenderLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StrayClothingLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfCollarLayer
+ XXX.entity.monster.package-info
+ XXX.entity.monster.Zombie$1
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
- XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
+ XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.VillagerType$1
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Inventory
+ XXX.entity.player.package-info
- XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.PlayerRenderer
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.Boat$1
- XXX.entity.vehicle.Boat$Status
+ XXX.entity.vehicle.Boat$Type
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$Effect
- XXX.font.glyphs.EmptyGlyph
+ XXX.font.glyphs.MissingGlyph
+ XXX.font.glyphs.package-info
- XXX.font.glyphs.WhiteGlyph
+ XXX.font.providers.BitmapProvider
- XXX.font.providers.BitmapProvider$1
+ XXX.font.providers.BitmapProvider$Builder
- XXX.font.providers.BitmapProvider$Glyph
+ XXX.font.providers.GlyphProviderBuilder
- XXX.font.providers.GlyphProviderBuilderType
+ XXX.font.providers.LegacyUnicodeBitmapsProvider
- XXX.font.providers.LegacyUnicodeBitmapsProvider$1
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- XXX.font.providers.package-info
+ XXX.font.providers.TrueTypeGlyphProviderBuilder
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
+ XXX.gametest.framework.GameTestSequence
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
- XXX.gui.chat.ChatListener
+ XXX.gui.chat.NarratorChatListener
- XXX.gui.chat.OverlayChatListener
- XXX.gui.chat.package-info
+ XXX.gui.chat.StandardChatListener
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractSelectionList
- XXX.gui.components.AbstractSelectionList$1
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$TrackedList
+ XXX.gui.components.AbstractSliderButton
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.Button
+ XXX.gui.components.Button$OnPress
- XXX.gui.components.ChatComponent
+ XXX.gui.components.Checkbox
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$1
- XXX.gui.components.CommandSuggestions$SuggestionsList
+ XXX.gui.components.ComponentRenderUtils
- XXX.gui.components.ContainerObjectSelectionList
+ XXX.gui.components.ContainerObjectSelectionList$Entry
- XXX.gui.components.DebugScreenOverlay
+ XXX.gui.components.DebugScreenOverlay$1
- XXX.gui.components.EditBox
+ XXX.gui.components.ImageButton
- XXX.gui.components.LerpingBossEvent
+ XXX.gui.components.LerpingBossEvent$1
- XXX.gui.components.LockIconButton
+ XXX.gui.components.LockIconButton$Icon
- XXX.gui.components.ObjectSelectionList
+ XXX.gui.components.ObjectSelectionList$Entry
- XXX.gui.components.OptionButton
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
- XXX.gui.components.package-info
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$1
+ XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
- XXX.gui.components.ScrolledSelectionList
+ XXX.gui.components.SliderButton
- XXX.gui.components.StateSwitchingButton
+ XXX.gui.components.SubtitleOverlay
- XXX.gui.components.SubtitleOverlay$Subtitle
+ XXX.gui.components.TickableWidget
- XXX.gui.components.VolumeSlider
+ XXX.gui.components.Widget
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$1
- XXX.gui.font.FontManager$2
+ XXX.gui.font.FontSet
- XXX.gui.font.FontTexture
+ XXX.gui.font.FontTexture$1
- XXX.gui.font.FontTexture$Node
- XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.screens.AccessibilityOptionsScreen
+ XXX.gui.screens.AlertScreen
- XXX.gui.screens.BackupConfirmScreen
+ XXX.gui.screens.BackupConfirmScreen$Listener
- XXX.gui.screens.ChatOptionsScreen
+ XXX.gui.screens.ChatScreen
- XXX.gui.screens.ChatScreen$1
+ XXX.gui.screens.ConfirmLinkScreen
- XXX.gui.screens.ConfirmScreen
+ XXX.gui.screens.ConnectScreen
- XXX.gui.screens.ConnectScreen$1
+ XXX.gui.screens.CreateBuffetWorldScreen
- XXX.gui.screens.CreateBuffetWorldScreen$1
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ XXX.gui.screens.CreateFlatWorldScreen
- XXX.gui.screens.CreateFlatWorldScreen$1
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ XXX.gui.screens.DeathScreen
- XXX.gui.screens.DemoIntroScreen
+ XXX.gui.screens.DirectJoinServerScreen
- XXX.gui.screens.DisconnectedScreen
+ XXX.gui.screens.EditServerScreen
- XXX.gui.screens.ErrorScreen
+ XXX.gui.screens.GenericDirtMessageScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingOverlay
- XXX.gui.screens.LoadingOverlay$LogoTexture
+ XXX.gui.screens.MenuScreens
- XXX.gui.screens.MenuScreens$ScreenConstructor
+ XXX.gui.screens.MouseSettingsScreen
- XXX.gui.screens.OptionsScreen
+ XXX.gui.screens.OptionsSubScreen
- XXX.gui.screens.OutOfMemoryScreen
+ XXX.gui.screens.Overlay
+ XXX.gui.screens.package-info
- XXX.gui.screens.PauseScreen
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetInfo
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.Screen
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SkinCustomizationScreen
- XXX.gui.screens.SoundOptionsScreen
+ XXX.gui.screens.TitleScreen
- XXX.gui.screens.VideoSettingsScreen
+ XXX.gui.screens.WinScreen
- XXX.gui.spectator.package-info
- XXX.gui.spectator.PlayerMenuItem
+ XXX.gui.spectator.RootSpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenu
+ XXX.gui.spectator.SpectatorMenu$1
- XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
+ XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
- XXX.gui.spectator.SpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenuItem
- XXX.gui.spectator.SpectatorMenuListener
+ XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.Potions
+ XXX.item.alchemy.PotionUtils
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.Ingredient$1
+ XXX.item.crafting.Ingredient$ItemValue
- XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleRecipeSerializer
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.SuspiciousStewRecipe
- XXX.item.crafting.TippedArrowRecipe
- XXX.item.enchantment.ArrowDamageEnchantment
+ XXX.item.enchantment.ArrowFireEnchantment
- XXX.item.enchantment.ArrowInfiniteEnchantment
+ XXX.item.enchantment.ArrowKnockbackEnchantment
- XXX.item.enchantment.ArrowPiercingEnchantment
+ XXX.item.enchantment.BindingCurseEnchantment
- XXX.item.enchantment.DamageEnchantment
+ XXX.item.enchantment.DigDurabilityEnchantment
- XXX.item.enchantment.DiggingEnchantment
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$Rarity
+ XXX.item.enchantment.EnchantmentCategory
- XXX.item.enchantment.EnchantmentCategory$1
+ XXX.item.enchantment.EnchantmentCategory$10
- XXX.item.enchantment.EnchantmentCategory$11
+ XXX.item.enchantment.EnchantmentCategory$12
- XXX.item.enchantment.EnchantmentCategory$13
+ XXX.item.enchantment.EnchantmentCategory$14
- XXX.item.enchantment.EnchantmentCategory$2
+ XXX.item.enchantment.EnchantmentCategory$3
- XXX.item.enchantment.EnchantmentCategory$4
+ XXX.item.enchantment.EnchantmentCategory$5
- XXX.item.enchantment.EnchantmentCategory$6
+ XXX.item.enchantment.EnchantmentCategory$7
- XXX.item.enchantment.EnchantmentCategory$8
+ XXX.item.enchantment.EnchantmentCategory$9
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.FireAspectEnchantment
+ XXX.item.enchantment.FishingSpeedEnchantment
- XXX.item.enchantment.FrostWalkerEnchantment
+ XXX.item.enchantment.KnockbackEnchantment
- XXX.item.enchantment.LootBonusEnchantment
+ XXX.item.enchantment.MendingEnchantment
- XXX.item.enchantment.MultiShotEnchantment
+ XXX.item.enchantment.OxygenEnchantment
- XXX.item.enchantment.package-info
- XXX.item.enchantment.ProtectionEnchantment
+ XXX.item.enchantment.ProtectionEnchantment$Type
- XXX.item.enchantment.QuickChargeEnchantment
+ XXX.item.enchantment.SoulSpeedEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.ThornsEnchantment
- XXX.item.enchantment.TridentChannelingEnchantment
+ XXX.item.enchantment.TridentImpalerEnchantment
- XXX.item.enchantment.TridentLoyaltyEnchantment
+ XXX.item.enchantment.TridentRiptideEnchantment
- XXX.item.enchantment.UntouchingEnchantment
+ XXX.item.enchantment.VanishingCurseEnchantment
- XXX.item.enchantment.WaterWalkerEnchantment
+ XXX.item.enchantment.WaterWorkerEnchantment
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$3
+ XXX.level.block.Block$OffsetType
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
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
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
- XXX.level.block.RespawnAnchorBlock
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
+ XXX.metadata.animation.AnimationFrame
- XXX.metadata.animation.AnimationMetadataSection
+ XXX.metadata.animation.AnimationMetadataSection$1
- XXX.metadata.animation.AnimationMetadataSectionSerializer
- XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetaDataSection
- XXX.metadata.animation.VillagerMetaDataSection$Hat
+ XXX.metadata.animation.VillagerMetadataSectionSerializer
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.LanguageMetadataSectionSerializer
+ XXX.metadata.language.package-info
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.metadata.texture.package-info
+ XXX.metadata.texture.TextureMetadataSection
- XXX.metadata.texture.TextureMetadataSectionSerializer
+ XXX.minecraft.advancements.package-info
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
+ XXX.minecraft.client.User
- XXX.minecraft.client.User$Type
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CommandFunction
- XXX.minecraft.commands.CommandFunction$CacheableFunction
+ XXX.minecraft.commands.CommandFunction$CommandEntry
- XXX.minecraft.commands.CommandFunction$Entry
+ XXX.minecraft.commands.CommandFunction$FunctionEntry
- XXX.minecraft.commands.CommandRuntimeException
- XXX.minecraft.commands.Commands
+ XXX.minecraft.commands.Commands$ParseFunction
+ XXX.minecraft.commands.CommandSource
- XXX.minecraft.commands.CommandSource$1
+ XXX.minecraft.commands.CommandSourceStack
+ XXX.minecraft.commands.package-info
- XXX.minecraft.commands.SharedSuggestionProvider
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.core.AxisCycle
+ XXX.minecraft.core.AxisCycle$1
- XXX.minecraft.core.AxisCycle$2
+ XXX.minecraft.core.AxisCycle$3
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockSource
+ XXX.minecraft.core.BlockSourceImpl
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
+ XXX.minecraft.core.Direction$1
- XXX.minecraft.core.Direction$Axis
+ XXX.minecraft.core.Direction$Axis$1
- XXX.minecraft.core.Direction$Axis$2
+ XXX.minecraft.core.Direction$Axis$3
- XXX.minecraft.core.Direction$AxisDirection
+ XXX.minecraft.core.Direction$Plane
- XXX.minecraft.core.Direction8
+ XXX.minecraft.core.GlobalPos
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.LocatableSource
+ XXX.minecraft.core.Location
- XXX.minecraft.core.MapFiller
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.NonNullList
- XXX.minecraft.core.package-info
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.SerializableBoolean
- XXX.minecraft.core.SerializableLong
+ XXX.minecraft.core.SerializableUUID
- XXX.minecraft.core.Source
+ XXX.minecraft.core.Vec3i
- XXX.minecraft.core.WritableRegistry
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
- XXX.minecraft.data.package-info
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
- XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.NarrationHelper
+ XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsBridge
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RealmsServerAddress
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
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
+ XXX.minecraft.server.package-info
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
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.BlockTags$Wrapper
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.EntityTypeTags$Wrapper
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.FluidTags$Wrapper
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.ItemTags$Wrapper
- XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.SynchronizableTagCollection
- XXX.minecraft.tags.Tag
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.Tag$ValuesEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$Preparations
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$1
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.Deserializer
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InsensitiveStringMap
+ XXX.minecraft.util.IntRange
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LimitedCapacityList
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RewindableStream
- XXX.minecraft.util.RewindableStream$1
+ XXX.minecraft.util.Serializable
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$1
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.model.dragon.DragonHeadModel
- XXX.model.dragon.package-info
+ XXX.model.geom.ModelPart
- XXX.model.geom.ModelPart$Cube
+ XXX.model.geom.ModelPart$Polygon
- XXX.model.geom.ModelPart$Vertex
+ XXX.model.geom.package-info
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$1
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$1
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$1
- XXX.models.blockstates.PropertyDispatch$C1
+ XXX.models.blockstates.PropertyDispatch$C2
- XXX.models.blockstates.PropertyDispatch$C3
+ XXX.models.blockstates.PropertyDispatch$C4
- XXX.models.blockstates.PropertyDispatch$C5
+ XXX.models.blockstates.PropertyDispatch$PentaFunction
- XXX.models.blockstates.PropertyDispatch$QuadFunction
+ XXX.models.blockstates.PropertyDispatch$TriFunction
- XXX.models.blockstates.PropertyValue
+ XXX.models.blockstates.Selector
- XXX.models.blockstates.Variant
+ XXX.models.blockstates.VariantProperties
- XXX.models.blockstates.VariantProperties$Rotation
+ XXX.models.blockstates.VariantProperty
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
+ XXX.models.model.ModelLocationUtils
- XXX.models.model.ModelTemplate
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.Piglin$PiglinArmPose
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
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
+ XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackRepository
- XXX.packs.repository.RepositorySource
+ XXX.packs.repository.ServerPacksSource
- XXX.packs.repository.UnopenedPack
+ XXX.packs.repository.UnopenedPack$Position
- XXX.packs.repository.UnopenedPack$UnopenedPackConstructor
- XXX.packs.resources.FallbackResourceManager
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.package-info
- XXX.packs.resources.PreparableReloadListener
+ XXX.packs.resources.PreparableReloadListener$PreparationBarrier
- XXX.packs.resources.ProfiledReloadInstance
+ XXX.packs.resources.ProfiledReloadInstance$1
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadableResourceManager
- XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.packs.resources.SimpleResource
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
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
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
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
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
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.renderer.banner.package-info
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
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
- XXX.renderer.blockentity.BannerRenderer
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
- XXX.renderer.blockentity.BrightnessCombiner
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
+ XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.package-info
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.SignRenderer
+ XXX.renderer.blockentity.SignRenderer$SignModel
- XXX.renderer.blockentity.SkullBlockRenderer
+ XXX.renderer.blockentity.SkullBlockRenderer$1
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
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
- XXX.renderer.chunk.package-info
- XXX.renderer.chunk.RenderChunkRegion
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
+ XXX.renderer.debug.CaveDebugRenderer
- XXX.renderer.debug.ChunkBorderRenderer
+ XXX.renderer.debug.ChunkDebugRenderer
- XXX.renderer.debug.ChunkDebugRenderer$1
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer
- XXX.renderer.debug.GameTestDebugRenderer$Marker
+ XXX.renderer.debug.GoalSelectorDebugRenderer
- XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ XXX.renderer.debug.HeightMapRenderer
- XXX.renderer.debug.LightDebugRenderer
+ XXX.renderer.debug.NeighborsUpdateRenderer
+ XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.SolidFaceRenderer
+ XXX.renderer.debug.StructureRenderer
- XXX.renderer.debug.VillageSectionsDebugRenderer
+ XXX.renderer.debug.WaterDebugRenderer
- XXX.renderer.debug.WorldGenAttemptRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.AreaEffectCloudRenderer
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.BatRenderer
- XXX.renderer.entity.BeeRenderer
+ XXX.renderer.entity.BlazeRenderer
- XXX.renderer.entity.BoatRenderer
+ XXX.renderer.entity.CatRenderer
- XXX.renderer.entity.CaveSpiderRenderer
+ XXX.renderer.entity.ChestedHorseRenderer
- XXX.renderer.entity.ChickenRenderer
+ XXX.renderer.entity.CodRenderer
- XXX.renderer.entity.CowRenderer
+ XXX.renderer.entity.CreeperRenderer
- XXX.renderer.entity.DolphinRenderer
+ XXX.renderer.entity.DragonFireballRenderer
- XXX.renderer.entity.DrownedRenderer
+ XXX.renderer.entity.ElderGuardianRenderer
- XXX.renderer.entity.EndCrystalRenderer
+ XXX.renderer.entity.EnderDragonRenderer
- XXX.renderer.entity.EnderDragonRenderer$DragonModel
+ XXX.renderer.entity.EndermanRenderer
- XXX.renderer.entity.EndermiteRenderer
+ XXX.renderer.entity.EntityRenderDispatcher
- XXX.renderer.entity.EntityRenderer
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.GhastRenderer
- XXX.renderer.entity.GiantMobRenderer
+ XXX.renderer.entity.GuardianRenderer
- XXX.renderer.entity.HoglinRenderer
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
+ XXX.renderer.entity.package-info
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
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
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.AtlasSet
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.LayeredTexture
- XXX.renderer.texture.MipmapGenerator
+ XXX.renderer.texture.MissingTextureAtlasSprite
- XXX.renderer.texture.OverlayTexture
+ XXX.renderer.texture.package-info
+ XXX.renderer.texture.PreloadedTexture
- XXX.renderer.texture.SimpleTexture
+ XXX.renderer.texture.SimpleTexture$TextureImage
- XXX.renderer.texture.Stitcher
+ XXX.renderer.texture.Stitcher$Holder
- XXX.renderer.texture.Stitcher$Region
+ XXX.renderer.texture.Stitcher$SpriteLoader
- XXX.renderer.texture.StitcherException
+ XXX.renderer.texture.TextureAtlas
- XXX.renderer.texture.TextureAtlas$Preparations
+ XXX.renderer.texture.TextureAtlasSprite
- XXX.renderer.texture.TextureAtlasSprite$1
+ XXX.renderer.texture.TextureAtlasSprite$Info
- XXX.renderer.texture.TextureAtlasSprite$InterpolationData
+ XXX.renderer.texture.TextureManager
- XXX.renderer.texture.Tickable
+ XXX.resourcepacks.entries.package-info
- XXX.resourcepacks.lists.AvailableResourcePackList
- XXX.resourcepacks.lists.package-info
+ XXX.resourcepacks.lists.ResourcePackList
- XXX.resourcepacks.lists.ResourcePackList$ResourcePackEntry
+ XXX.resourcepacks.lists.SelectedResourcePackList
- XXX.resources.language.I18n
+ XXX.resources.language.Language
- XXX.resources.language.LanguageManager
+ XXX.resources.language.Locale
- XXX.resources.language.package-info
- XXX.resources.metadata.package-info
- XXX.resources.model.BakedModel
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BuiltInModel
+ XXX.resources.model.Material
- XXX.resources.model.ModelBakery
+ XXX.resources.model.ModelBakery$BlockStateDefinitionException
- XXX.resources.model.ModelBakery$ModelGroupKey
+ XXX.resources.model.ModelManager
- XXX.resources.model.ModelResourceLocation
+ XXX.resources.model.ModelState
- XXX.resources.model.MultiPartBakedModel
+ XXX.resources.model.MultiPartBakedModel$Builder
- XXX.resources.model.package-info
- XXX.resources.model.SimpleBakedModel
+ XXX.resources.model.SimpleBakedModel$Builder
- XXX.resources.model.UnbakedModel
+ XXX.resources.model.WeightedBakedModel
- XXX.resources.model.WeightedBakedModel$Builder
+ XXX.resources.model.WeightedBakedModel$WeightedModel
- XXX.resources.sounds.AbstractSoundInstance
+ XXX.resources.sounds.AbstractTickableSoundInstance
- XXX.resources.sounds.AmbientSoundHandler
+ XXX.resources.sounds.BeeAggressiveSoundInstance
- XXX.resources.sounds.BeeFlyingSoundInstance
+ XXX.resources.sounds.BeeSoundInstance
- XXX.resources.sounds.BiomeAmbientSoundsHandler
+ XXX.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
- XXX.resources.sounds.BubbleColumnAmbientSoundHandler
+ XXX.resources.sounds.ElytraOnPlayerSoundInstance
- XXX.resources.sounds.EntityBoundSoundInstance
+ XXX.resources.sounds.GuardianAttackSoundInstance
- XXX.resources.sounds.MinecartSoundInstance
- XXX.resources.sounds.package-info
+ XXX.resources.sounds.RidingMinecartSoundInstance
- XXX.resources.sounds.SimpleSoundInstance
+ XXX.resources.sounds.Sound
- XXX.resources.sounds.Sound$Type
+ XXX.resources.sounds.SoundEventRegistration
- XXX.resources.sounds.SoundEventRegistrationSerializer
+ XXX.resources.sounds.SoundInstance
- XXX.resources.sounds.SoundInstance$Attenuation
+ XXX.resources.sounds.TickableSoundInstance
- XXX.resources.sounds.UnderwaterAmbientSoundHandler
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances
- XXX.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
- XXX.screens.achievement.package-info
- XXX.screens.achievement.StatsScreen
+ XXX.screens.achievement.StatsScreen$1
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- XXX.screens.achievement.StatsScreen$ItemStatisticsList
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList
- XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ XXX.screens.achievement.StatsUpdateListener
- XXX.screens.advancements.AdvancementsScreen
+ XXX.screens.advancements.AdvancementTab
- XXX.screens.advancements.AdvancementTabType
+ XXX.screens.advancements.AdvancementTabType$1
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
+ XXX.screens.advancements.package-info
- XXX.screens.controls.ControlList
+ XXX.screens.controls.ControlList$1
- XXX.screens.controls.ControlList$CategoryEntry
+ XXX.screens.controls.ControlList$Entry
- XXX.screens.controls.ControlList$KeyEntry
+ XXX.screens.controls.ControlList$KeyEntry$1
- XXX.screens.controls.ControlList$KeyEntry$2
+ XXX.screens.controls.ControlsScreen
- XXX.screens.controls.package-info
+ XXX.screens.inventory.AbstractCommandBlockEditScreen
- XXX.screens.inventory.AbstractCommandBlockEditScreen$1
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
+ XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.JigsawBlockEditScreen
+ XXX.screens.inventory.LecternScreen
- XXX.screens.inventory.LecternScreen$1
+ XXX.screens.inventory.LoomScreen
- XXX.screens.inventory.MenuAccess
+ XXX.screens.inventory.MerchantScreen
- XXX.screens.inventory.MerchantScreen$TradeOfferButton
+ XXX.screens.inventory.MinecartCommandBlockEditScreen
+ XXX.screens.inventory.package-info
- XXX.screens.inventory.PageButton
+ XXX.screens.inventory.ShulkerBoxScreen
- XXX.screens.inventory.SignEditScreen
+ XXX.screens.inventory.SmithingScreen
- XXX.screens.inventory.SmokerScreen
+ XXX.screens.inventory.StonecutterScreen
- XXX.screens.inventory.StructureBlockEditScreen
+ XXX.screens.inventory.StructureBlockEditScreen$1
- XXX.screens.inventory.StructureBlockEditScreen$2
- XXX.screens.mco.package-info
+ XXX.screens.multiplayer.JoinMultiplayerScreen
- XXX.screens.multiplayer.package-info
- XXX.screens.multiplayer.SafetyScreen
+ XXX.screens.multiplayer.ServerSelectionList
- XXX.screens.multiplayer.ServerSelectionList$Entry
+ XXX.screens.multiplayer.ServerSelectionList$LANHeader
- XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
+ XXX.screens.recipebook.BlastingRecipeBookComponent
- XXX.screens.recipebook.GhostRecipe
+ XXX.screens.recipebook.GhostRecipe$GhostIngredient
- XXX.screens.recipebook.OverlayRecipeComponent
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
+ XXX.screens.recipebook.package-info
- XXX.screens.recipebook.RecipeBookComponent
+ XXX.screens.recipebook.RecipeBookPage
- XXX.screens.recipebook.RecipeBookTabButton
+ XXX.screens.recipebook.RecipeButton
- XXX.screens.recipebook.RecipeCollection
+ XXX.screens.recipebook.RecipeShownListener
- XXX.screens.recipebook.RecipeUpdateListener
+ XXX.screens.recipebook.SmeltingRecipeBookComponent
- XXX.screens.recipebook.SmokingRecipeBookComponent
+ XXX.screens.resourcepacks.package-info
- XXX.screens.resourcepacks.ResourcePackSelectScreen
- XXX.screens.stream.package-info
+ XXX.screens.worldselection.CreateWorldScreen
- XXX.screens.worldselection.CreateWorldScreen$1
+ XXX.screens.worldselection.CreateWorldScreen$2
- XXX.screens.worldselection.CreateWorldScreen$3
+ XXX.screens.worldselection.CreateWorldScreen$4
- XXX.screens.worldselection.CreateWorldScreen$5
+ XXX.screens.worldselection.CreateWorldScreen$6
- XXX.screens.worldselection.CreateWorldScreen$7
+ XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode
- XXX.screens.worldselection.EditWorldScreen
+ XXX.screens.worldselection.OptimizeWorldScreen
+ XXX.screens.worldselection.package-info
- XXX.screens.worldselection.SelectWorldScreen
+ XXX.screens.worldselection.WorldSelectionList
- XXX.screens.worldselection.WorldSelectionList$WorldListEntry
- XXX.selector.options.EntitySelectorOptions
+ XXX.selector.options.EntitySelectorOptions$1
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
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
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
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
+ XXX.server.commands.LocateBiomeCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LootCommand
- XXX.server.commands.LootCommand$Callback
+ XXX.server.commands.LootCommand$DropConsumer
- XXX.server.commands.LootCommand$TailProvider
+ XXX.server.commands.MsgCommand
- XXX.server.commands.OpCommand
+ XXX.server.commands.package-info
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
+ XXX.server.commands.SpectateCommand
- XXX.server.commands.SpreadPlayersCommand
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
+ XXX.server.commands.TeleportCommand$LookAt
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServer$2
- XXX.server.dedicated.DedicatedServerProperties
+ XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$1
- XXX.server.dedicated.Settings$MutableValue
- XXX.server.gui.MinecraftServerGui
+ XXX.server.gui.MinecraftServerGui$1
- XXX.server.gui.MinecraftServerGui$2
+ XXX.server.gui.package-info
+ XXX.server.gui.PlayerListComponent
- XXX.server.gui.StatsComponent
- XXX.server.level.BlockDestructionProgress
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$1
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure
- XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
+ XXX.server.level.ChunkHolder$FullChunkStatus
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$1
- XXX.server.level.ChunkMap$2
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$1
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DerivedServerLevel
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FeatureSimulator
+ XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$1
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.WorldGenRegion
- XXX.server.level.WorldGenTickList
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.packs.AbstractResourcePack
+ XXX.server.packs.FileResourcePack
- XXX.server.packs.FolderResourcePack
+ XXX.server.packs.Pack
- XXX.server.packs.package-info
- XXX.server.packs.PackType
+ XXX.server.packs.ResourcePackFileNotFoundException
- XXX.server.packs.VanillaPack
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$2
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.GameProfileCache$Serializer
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
+ XXX.spectator.categories.package-info
+ XXX.spectator.categories.SpectatorPage
- XXX.spectator.categories.TeleportToPlayerMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ XXX.synchronization.brigadier.BrigadierArgumentSerializers
- XXX.synchronization.brigadier.DoubleArgumentSerializer
+ XXX.synchronization.brigadier.FloatArgumentSerializer
- XXX.synchronization.brigadier.IntegerArgumentSerializer
+ XXX.synchronization.brigadier.LongArgumentSerializer
- XXX.synchronization.brigadier.package-info
- XXX.synchronization.brigadier.StringArgumentSerializer
+ XXX.synchronization.brigadier.StringArgumentSerializer$1
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.OminousBannerBlockEntityRenameFix
+ XXX.util.datafix.OminousBannerRenameFix
- XXX.world.entity.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$1
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.AnvilMenu$1
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$FuelSlot
+ XXX.world.inventory.BrewingStandMenu$IngredientsSlot
- XXX.world.inventory.BrewingStandMenu$PotionSlot
+ XXX.world.inventory.CartographyTableMenu
- XXX.world.inventory.CartographyTableMenu$1
+ XXX.world.inventory.CartographyTableMenu$2
- XXX.world.inventory.CartographyTableMenu$3
+ XXX.world.inventory.CartographyTableMenu$4
- XXX.world.inventory.CartographyTableMenu$5
+ XXX.world.inventory.ChestMenu
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.CraftingContainer
+ XXX.world.inventory.CraftingMenu
- XXX.world.inventory.DataSlot
+ XXX.world.inventory.DataSlot$1
- XXX.world.inventory.DataSlot$2
+ XXX.world.inventory.DataSlot$3
- XXX.world.inventory.DispenserMenu
+ XXX.world.inventory.EnchantmentMenu
- XXX.world.inventory.EnchantmentMenu$1
+ XXX.world.inventory.EnchantmentMenu$2
- XXX.world.inventory.EnchantmentMenu$3
+ XXX.world.inventory.FurnaceFuelSlot
- XXX.world.inventory.FurnaceMenu
+ XXX.world.inventory.FurnaceResultSlot
- XXX.world.inventory.GrindstoneMenu
+ XXX.world.inventory.GrindstoneMenu$1
- XXX.world.inventory.GrindstoneMenu$2
+ XXX.world.inventory.GrindstoneMenu$3
- XXX.world.inventory.GrindstoneMenu$4
+ XXX.world.inventory.HopperMenu
- XXX.world.inventory.HorseInventoryMenu
+ XXX.world.inventory.HorseInventoryMenu$1
- XXX.world.inventory.HorseInventoryMenu$2
+ XXX.world.inventory.InventoryMenu
- XXX.world.inventory.InventoryMenu$1
+ XXX.world.inventory.InventoryMenu$2
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.LecternMenu
- XXX.world.inventory.LecternMenu$1
+ XXX.world.inventory.LoomMenu
- XXX.world.inventory.LoomMenu$1
+ XXX.world.inventory.LoomMenu$2
- XXX.world.inventory.LoomMenu$3
+ XXX.world.inventory.LoomMenu$4
- XXX.world.inventory.LoomMenu$5
+ XXX.world.inventory.LoomMenu$6
- XXX.world.inventory.MenuConstructor
+ XXX.world.inventory.MenuType
- XXX.world.inventory.MenuType$MenuSupplier
+ XXX.world.inventory.MerchantContainer
- XXX.world.inventory.MerchantMenu
+ XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
- XXX.world.item.AirItem
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorItem$1
+ XXX.world.item.ArmorMaterial
- XXX.world.item.ArmorMaterials
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BannerPatternItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BlockPlaceContext
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
+ XXX.world.item.BucketItem
- XXX.world.item.CarrotOnAStickItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.ClockItem
+ XXX.world.item.ClockItem$1
- XXX.world.item.CompassItem
+ XXX.world.item.CompassItem$1
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$10
- XXX.world.item.CreativeModeTab$11
+ XXX.world.item.CreativeModeTab$12
- XXX.world.item.CreativeModeTab$2
+ XXX.world.item.CreativeModeTab$3
- XXX.world.item.CreativeModeTab$4
+ XXX.world.item.CreativeModeTab$5
- XXX.world.item.CreativeModeTab$6
+ XXX.world.item.CreativeModeTab$7
- XXX.world.item.CreativeModeTab$8
+ XXX.world.item.CreativeModeTab$9
- XXX.world.item.CrossbowItem
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DirectionalPlaceContext
- XXX.world.item.DirectionalPlaceContext$1
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeableArmorItem
+ XXX.world.item.DyeableHorseArmorItem
- XXX.world.item.DyeableLeatherItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.ElytraItem
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EnchantedBookItem
+ XXX.world.item.EnchantedGoldenAppleItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FireworkRocketItem$Shape
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishBucketItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneyBottleItem
+ XXX.world.item.HorseArmorItem
- XXX.world.item.Item
+ XXX.world.item.Item$1
- XXX.world.item.Item$Properties
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$1
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemFrameItem
+ XXX.world.item.ItemNameBlockItem
- XXX.world.item.ItemPropertyFunction
- XXX.world.item.Items
+ XXX.world.item.ItemStack
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MapItem
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
- XXX.world.item.NameTagItem
+ XXX.world.item.package-info
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.ProjectileWeaponItem$Type
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignItem
+ XXX.world.item.SimpleFoiledItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.Tier
+ XXX.world.item.TieredItem
- XXX.world.item.Tiers
+ XXX.world.item.TippedArrowItem
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
- XXX.world.item.UseOnContext
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkTickList
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.CollisionGetter$1
- XXX.world.level.ColorResolver
+ XXX.world.level.CustomSpawner
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EmptyTickList
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$1
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelConflictException
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelType
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NoiseColumn
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
<hr/>