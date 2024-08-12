## Comparison with [22w43a](https://github.com/PixiGeko/Minecraft-generated-data/tree/22w43a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">22w43a</th><th>22w44a</th></tr><tr><td>World version</td><td><code>3206</code></td><td><code>3207</code></td></tr><tr><td>Protocol version</td><td><code>1073741929</code></td><td><code>1073741930</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:ender_dragon_spawn_egg
+ minecraft:iron_golem_spawn_egg
+ minecraft:snow_golem_spawn_egg
+ minecraft:wither_spawn_egg
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:ender_dragon_spawn_egg
+ minecraft:iron_golem_spawn_egg
+ minecraft:snow_golem_spawn_egg
+ minecraft:wither_spawn_egg
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
gamerule
</summary>

```diff
+ gamerule blockExplosionDropDecay <value: bool>
+ gamerule globalSoundEvents <value: bool>
+ gamerule lavaSourceConversion <value: bool>
+ gamerule mobExplosionDropDecay <value: bool>
+ gamerule snowAccumulationHeight <value: integer>
+ gamerule tntExplosionDropDecay <value: bool>
+ gamerule waterSourceConversion <value: bool>
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ block.minecraft.spawner.desc1: Interact with Spawn Egg:
+ block.minecraft.spawner.desc2: Sets Mob Type
+ gamerule.blockExplosionDropDecay: Drops from explosions caused by blocks decay
+ gamerule.blockExplosionDropDecay.description: Some of the drops from blocks destroyed by explosions caused by block interactions are lost in the explosion.
+ gamerule.globalSoundEvents: Global sound events
+ gamerule.globalSoundEvents.description: When certain game events happen, like a boss spawning, the sound is heard everywhere.
+ gamerule.lavaSourceConversion: Lave converts to source
+ gamerule.lavaSourceConversion.description: When flowing lava is surrounded on two sides by lava sources it converts into a source.
+ gamerule.mobExplosionDropDecay: Drops from explosions caused by mobs decay
+ gamerule.mobExplosionDropDecay.description: Some of the drops from blocks destroyed by explosions caused by mobs are lost in the explosion.
+ gamerule.snowAccumulationHeight: Snow accumulation height
+ gamerule.snowAccumulationHeight.description: When it snows, layers of snow form on the ground up to at most this number of layers.
+ gamerule.tntExplosionDropDecay: Drops from explosions caused by TNT decay
+ gamerule.tntExplosionDropDecay.description: Some of the drops from blocks destroyed by explosions caused by TNT are lost in the explosion.
+ gamerule.waterSourceConversion: Water converts to source
+ gamerule.waterSourceConversion.description: When flowing water is surrounded on two sides by water sources it converts into a source.
+ item.minecraft.ender_dragon_spawn_egg: Ender Dragon Spawn Egg
+ item.minecraft.iron_golem_spawn_egg: Iron Golem Spawn Egg
+ item.minecraft.snow_golem_spawn_egg: Snow Golem Spawn Egg
+ item.minecraft.wither_spawn_egg: Wither Spawn Egg
+ mco.selectServer.configureRealm: Configure realm
```

</details>
<details>
<summary>
Changes
</summary>

```
selectWorld.backupEraseCache: Erase cCached dData
block.minecraft.spawner: Monster Spawner
structure_block.mode_info.load: Load mMode - Load from File
structure_block.mode_info.data: Data mMode - Game Logic Marker
entity.minecraft.spawner_minecart: Minecart with Monster Spawner
mco.selectServer.configure: Configure realm
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/fence_gates.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/non_flammable_wood.json
- minecraft/tags/blocks/non_flammable_wood.json
+ minecraft/tags/items/fence_gates.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/models/item/ender_dragon_spawn_egg.json
+ minecraft/models/item/iron_golem_spawn_egg.json
+ minecraft/models/item/snow_golem_spawn_egg.json
+ minecraft/models/item/wither_spawn_egg.json
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
+ net.minecraft.commands.arguments.AngleArgument
- net.minecraft.commands.arguments.AngleArgument$SingleAngle
+ net.minecraft.commands.arguments.ArgumentSignatures
- net.minecraft.commands.arguments.ArgumentSignatures$Entry
+ net.minecraft.commands.arguments.ArgumentSignatures$Signer
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.blocks.BlockStateArgument
+ net.minecraft.commands.arguments.blocks.BlockStateParser
- net.minecraft.commands.arguments.blocks.BlockStateParser$BlockResult
+ net.minecraft.commands.arguments.blocks.BlockStateParser$TagResult
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
+ net.minecraft.commands.arguments.EntityArgument$Info
- net.minecraft.commands.arguments.EntityArgument$Info$Template
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
+ net.minecraft.commands.arguments.item.ItemParser$ItemResult
- net.minecraft.commands.arguments.item.ItemParser$TagResult
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
+ net.minecraft.commands.arguments.item.package-info
- net.minecraft.commands.arguments.MessageArgument
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
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
- net.minecraft.commands.arguments.ResourceArgument
+ net.minecraft.commands.arguments.ResourceArgument$Info
- net.minecraft.commands.arguments.ResourceArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceKeyArgument
- net.minecraft.commands.arguments.ResourceKeyArgument$Info
+ net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ResourceOrTagArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
- net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Info
+ net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
+ net.minecraft.commands.arguments.selector.EntitySelectorParser
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
+ net.minecraft.commands.arguments.selector.options.package-info
- net.minecraft.commands.arguments.selector.package-info
+ net.minecraft.commands.arguments.SignedArgument
- net.minecraft.commands.arguments.SlotArgument
+ net.minecraft.commands.arguments.StringRepresentableArgument
- net.minecraft.commands.arguments.TeamArgument
+ net.minecraft.commands.arguments.TemplateMirrorArgument
- net.minecraft.commands.arguments.TemplateRotationArgument
+ net.minecraft.commands.arguments.TimeArgument
- net.minecraft.commands.arguments.UuidArgument
- net.minecraft.commands.CommandBuildContext$3
- net.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
+ net.minecraft.commands.CommandFunction
- net.minecraft.commands.CommandFunction$CacheableFunction
+ net.minecraft.commands.CommandFunction$CommandEntry
- net.minecraft.commands.CommandFunction$Entry
+ net.minecraft.commands.CommandFunction$FunctionEntry
- net.minecraft.commands.CommandRuntimeException
+ net.minecraft.commands.Commands
- net.minecraft.commands.Commands$1
- net.minecraft.commands.Commands$CommandSelection
+ net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSigningContext
- net.minecraft.commands.CommandSigningContext$1
+ net.minecraft.commands.CommandSigningContext$SignedArguments
- net.minecraft.commands.CommandSource
+ net.minecraft.commands.CommandSource$1
- net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.package-info
- net.minecraft.commands.SharedSuggestionProvider
+ net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
- net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- net.minecraft.commands.synchronization.ArgumentTypeInfo
+ net.minecraft.commands.synchronization.ArgumentTypeInfo$Template
- net.minecraft.commands.synchronization.ArgumentTypeInfos
+ net.minecraft.commands.synchronization.ArgumentUtils
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.LongArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.LongArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.package-info
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$Template
- net.minecraft.commands.synchronization.package-info
- net.minecraft.commands.synchronization.SingletonArgumentInfo
+ net.minecraft.commands.synchronization.SingletonArgumentInfo$Template
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
+ net.minecraft.core.cauldron.CauldronInteraction
- net.minecraft.core.cauldron.package-info
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
- net.minecraft.core.dispenser.DispenseItemBehavior$27
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
- net.minecraft.core.FrontAndTop
+ net.minecraft.core.GlobalPos
- net.minecraft.core.Holder
+ net.minecraft.core.Holder$Direct
- net.minecraft.core.Holder$Kind
+ net.minecraft.core.Holder$Reference
- net.minecraft.core.Holder$Reference$Type
- net.minecraft.core.HolderGetter$Provider
+ net.minecraft.core.HolderLookup
- net.minecraft.core.HolderLookup$1
- net.minecraft.core.HolderLookup$Provider
- net.minecraft.core.HolderLookup$Provider$2
+ net.minecraft.core.HolderLookup$RegistryLookup$1
- net.minecraft.core.HolderLookup$RegistryLookup$Delegate
- net.minecraft.core.HolderSet
+ net.minecraft.core.HolderSet$Direct
- net.minecraft.core.HolderSet$ListBacked
+ net.minecraft.core.HolderSet$Named
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.LayeredRegistryAccess
+ net.minecraft.core.MappedRegistry
- net.minecraft.core.MappedRegistry$1
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
- net.minecraft.core.Registry$3
- net.minecraft.core.RegistrySetBuilder
- net.minecraft.core.RegistrySetBuilder$BuildState
- net.minecraft.core.RegistrySetBuilder$CompositeOwner
- net.minecraft.core.RegistrySetBuilder$RegisteredValue
- net.minecraft.core.RegistrySetBuilder$RegistryContents
- net.minecraft.core.RegistrySetBuilder$RegistryStub
- net.minecraft.core.RegistrySetBuilder$ValueAndHolder
+ net.minecraft.core.RegistrySynchronization
- net.minecraft.core.RegistrySynchronization$NetworkedRegistryData
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.UUIDUtil
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdvancementSubProvider
- net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.packs.package-info
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
+ net.minecraft.data.BuiltinRegistries
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
- net.minecraft.data.loot.LootTableProvider$SubProviderEntry
+ net.minecraft.data.loot.LootTableSubProvider
- net.minecraft.data.loot.package-info
- net.minecraft.data.loot.packs.package-info
+ net.minecraft.data.loot.packs.UpdateOneTwentyBlockLoot
- net.minecraft.data.loot.packs.UpdateOneTwentyLootTableProvider
+ net.minecraft.data.loot.packs.VanillaBlockLoot
- net.minecraft.data.loot.packs.VanillaChestLoot
+ net.minecraft.data.loot.packs.VanillaEntityLoot
- net.minecraft.data.loot.packs.VanillaFishingLoot
+ net.minecraft.data.loot.packs.VanillaGiftLoot
- net.minecraft.data.loot.packs.VanillaLootTableProvider
+ net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
- net.minecraft.data.Main
- net.minecraft.data.metadata.package-info
+ net.minecraft.data.metadata.PackMetadataGenerator
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
+ net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
- net.minecraft.data.models.blockstates.Condition$CompositeCondition
+ net.minecraft.data.models.blockstates.Condition$Operation
- net.minecraft.data.models.blockstates.Condition$TerminalCondition
+ net.minecraft.data.models.blockstates.MultiPartGenerator
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
- net.minecraft.data.models.blockstates.package-info
+ net.minecraft.data.models.blockstates.PropertyDispatch
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
- net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.model.DelegatedModel
- net.minecraft.data.models.model.ModelLocationUtils
+ net.minecraft.data.models.model.ModelTemplate
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
+ net.minecraft.data.PackOutput
- net.minecraft.data.PackOutput$PathProvider
+ net.minecraft.data.PackOutput$Target
- net.minecraft.data.recipes.CraftingRecipeBuilder
+ net.minecraft.data.recipes.CraftingRecipeBuilder$1
- net.minecraft.data.recipes.CraftingRecipeBuilder$CraftingResult
+ net.minecraft.data.recipes.FinishedRecipe
+ net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.packs.BundleRecipeProvider
+ net.minecraft.data.recipes.packs.package-info
+ net.minecraft.data.recipes.packs.UpdateOneTwentyRecipeProvider
- net.minecraft.data.recipes.packs.VanillaRecipeProvider
- net.minecraft.data.recipes.RecipeBuilder
+ net.minecraft.data.recipes.RecipeCategory
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
- net.minecraft.data.registries.package-info
- net.minecraft.data.registries.RegistriesDatapackGenerator
- net.minecraft.data.tags.IntrinsicHolderTagsProvider
- net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader$1
+ net.minecraft.resources.RegistryDataLoader$Loader
- net.minecraft.resources.RegistryDataLoader$RegistryData
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryOps
- net.minecraft.resources.RegistryOps$1
- net.minecraft.resources.RegistryOps$RegistryInfo
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Dummy
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.chase.ChaseClient
+ net.minecraft.server.chase.ChaseClient$TeleportTarget
- net.minecraft.server.chase.ChaseServer
+ net.minecraft.server.chase.ChaseServer$PlayerPosition
- net.minecraft.server.chase.package-info
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.AttributeCommand
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ChaseCommand
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
- net.minecraft.server.commands.DebugCommand$Tracer
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
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
+ net.minecraft.server.commands.JfrCommand
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaceCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ResetChunksCommand
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
+ net.minecraft.server.commands.WardenSpawnTrackerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
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
+ net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerLevel$EntityCallbacks
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayer$1
- net.minecraft.server.level.ServerPlayer$2
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.TickingTracker
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$ReloadableResources
- net.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ net.minecraft.server.MinecraftServer$TimeProfiler
- net.minecraft.server.MinecraftServer$TimeProfiler$1
+ net.minecraft.server.network.FilteredText
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
- net.minecraft.server.network.TextFilterClient
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
- net.minecraft.server.network.TextFilterClient$JoinOrLeaveEncoder
+ net.minecraft.server.network.TextFilterClient$MessageEncoder
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.BuiltInMetadata
- net.minecraft.server.packs.FeatureFlagsMetadataSection
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.linkfs.DummyFileAttributes
+ net.minecraft.server.packs.linkfs.LinkFileSystem
- net.minecraft.server.packs.linkfs.LinkFileSystem$Builder
+ net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
+ net.minecraft.server.packs.linkfs.LinkFSFileStore
- net.minecraft.server.packs.linkfs.LinkFSPath
+ net.minecraft.server.packs.linkfs.LinkFSPath$1
- net.minecraft.server.packs.linkfs.LinkFSPath$2
+ net.minecraft.server.packs.linkfs.LinkFSPath$3
- net.minecraft.server.packs.linkfs.LinkFSProvider
+ net.minecraft.server.packs.linkfs.LinkFSProvider$1
- net.minecraft.server.packs.linkfs.LinkFSProvider$2
+ net.minecraft.server.packs.linkfs.package-info
- net.minecraft.server.packs.linkfs.PathContents
+ net.minecraft.server.packs.linkfs.PathContents$1
- net.minecraft.server.packs.linkfs.PathContents$2
+ net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
- net.minecraft.server.packs.linkfs.PathContents$FileContents
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.MetadataSectionType
- net.minecraft.server.packs.metadata.MetadataSectionType$1
+ net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
- net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackResources$ResourceOutput
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.PathPackResources
- net.minecraft.server.packs.repository.BuiltInPackSource
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$Info
- net.minecraft.server.packs.repository.Pack$Position
+ net.minecraft.server.packs.repository.Pack$ResourcesSupplier
- net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.PackSource
+ net.minecraft.server.packs.repository.PackSource$1
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.resources.CloseableResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
- net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
+ net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
- net.minecraft.server.packs.resources.IoSupplier
+ net.minecraft.server.packs.resources.MultiPackResourceManager
+ net.minecraft.server.packs.resources.package-info
- net.minecraft.server.packs.resources.PreparableReloadListener
+ net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
- net.minecraft.server.packs.resources.ProfiledReloadInstance
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceFilterSection
- net.minecraft.server.packs.resources.ResourceFilterSection$ResourceLocationPattern
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.ResourceMetadata
+ net.minecraft.server.packs.resources.ResourceMetadata$1
- net.minecraft.server.packs.resources.ResourceMetadata$2
+ net.minecraft.server.packs.resources.ResourceProvider
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.VanillaPackResources
+ net.minecraft.server.packs.VanillaPackResourcesBuilder
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
+ net.minecraft.server.RegistryLayer
- net.minecraft.server.ReloadableServerResources
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$ExecutionContext
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerFunctionManager$TraceCallbacks
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.Services
- net.minecraft.server.TickTask
+ net.minecraft.server.WorldLoader
- net.minecraft.server.WorldLoader$DataLoadContext
+ net.minecraft.server.WorldLoader$DataLoadOutput
- net.minecraft.server.WorldLoader$InitConfig
+ net.minecraft.server.WorldLoader$PackConfig
- net.minecraft.server.WorldLoader$ResultFactory
+ net.minecraft.server.WorldLoader$WorldDataSupplier
- net.minecraft.server.WorldStem
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
- net.minecraft.tags.BannerPatternTags
+ net.minecraft.tags.BiomeTags
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.CatVariantTags
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FlatLevelGeneratorPresetTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.InstrumentTags
+ net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
- net.minecraft.tags.PaintingVariantTags
+ net.minecraft.tags.PoiTypeTags
- net.minecraft.tags.StructureTags
+ net.minecraft.tags.TagBuilder
- net.minecraft.tags.TagEntry
+ net.minecraft.tags.TagEntry$Lookup
- net.minecraft.tags.TagFile
+ net.minecraft.tags.TagKey
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagLoader$1
- net.minecraft.tags.TagLoader$EntryWithSource
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$LoadResult
+ net.minecraft.tags.TagNetworkSerialization
- net.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ net.minecraft.tags.TagNetworkSerialization$TagOutput
- net.minecraft.tags.WorldPresetTags
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.Crypt$ByteArrayToKeyFunction
+ net.minecraft.util.Crypt$SaltSignaturePair
- net.minecraft.util.Crypt$SaltSupplier
+ net.minecraft.util.CryptException
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.CubicSpline
+ net.minecraft.util.CubicSpline$1Point
- net.minecraft.util.CubicSpline$Builder
+ net.minecraft.util.CubicSpline$Constant
- net.minecraft.util.CubicSpline$CoordinateVisitor
+ net.minecraft.util.CubicSpline$Multipoint
+ net.minecraft.util.datafix.DataFixerOptimizationOption
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixers$3
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
- net.minecraft.util.datafix.fixes.AbstractPoiSectionFix
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlendingDataFix
+ net.minecraft.util.datafix.fixes.BlendingDataRemoveFromNetherEndFix
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
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkDeleteIgnoredLightDataFix
+ net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ net.minecraft.util.datafix.fixes.ChunkRenamesFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.CriteriaRenameFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityGoatMissingStateFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingFieldsRenameFix
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
+ net.minecraft.util.datafix.fixes.EntityVariantFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.FilteredBooksFix
+ net.minecraft.util.datafix.fixes.FilteredSignsFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GoatHornIdFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTagFix
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
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
+ net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
- net.minecraft.util.datafix.fixes.PoiTypeRenameFix
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
+ net.minecraft.util.datafix.fixes.SimpleRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VariantRenameFix
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
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
- net.minecraft.util.datafix.schemas.V1451_6$1
+ net.minecraft.util.datafix.schemas.V1451_6$2
- net.minecraft.util.datafix.schemas.V1451_7
+ net.minecraft.util.datafix.schemas.V1460
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
+ net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2686
+ net.minecraft.util.datafix.schemas.V2688
- net.minecraft.util.datafix.schemas.V2704
+ net.minecraft.util.datafix.schemas.V2707
- net.minecraft.util.datafix.schemas.V2831
+ net.minecraft.util.datafix.schemas.V2832
- net.minecraft.util.datafix.schemas.V2842
+ net.minecraft.util.datafix.schemas.V3076
- net.minecraft.util.datafix.schemas.V3078
+ net.minecraft.util.datafix.schemas.V3081
- net.minecraft.util.datafix.schemas.V3082
+ net.minecraft.util.datafix.schemas.V3083
- net.minecraft.util.datafix.schemas.V3202
+ net.minecraft.util.datafix.schemas.V3203
- net.minecraft.util.datafix.schemas.V3204
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
- net.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ net.minecraft.util.ExtraCodecs$2
- net.minecraft.util.ExtraCodecs$3
+ net.minecraft.util.ExtraCodecs$4
- net.minecraft.util.ExtraCodecs$EitherCodec
+ net.minecraft.util.ExtraCodecs$LazyInitializedCodec
- net.minecraft.util.ExtraCodecs$TagOrElementLocation
+ net.minecraft.util.ExtraCodecs$XorCodec
- net.minecraft.util.FastBufferedInputStream
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FileZipper
- net.minecraft.util.FormattedCharSequence
+ net.minecraft.util.FormattedCharSink
- net.minecraft.util.FrameTimer
+ net.minecraft.util.FutureChain
- net.minecraft.util.Graph
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InclusiveRange
- net.minecraft.util.KeyDispatchDataCodec
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.MemoryReserve
- net.minecraft.util.ModCheck
+ net.minecraft.util.ModCheck$Confidence
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.Mth
+ net.minecraft.util.NativeModuleLister
- net.minecraft.util.NativeModuleLister$NativeModuleInfo
+ net.minecraft.util.NativeModuleLister$NativeModuleVersion
- net.minecraft.util.OptionEnum
+ net.minecraft.util.package-info
+ net.minecraft.util.ParticleUtils
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
+ net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
+ net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
- net.minecraft.util.profiling.jfr.stats.TimeStamped
+ net.minecraft.util.profiling.jfr.SummaryReporter
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
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.ProgressListener
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
+ net.minecraft.util.RandomSource
- net.minecraft.util.SignatureUpdater
+ net.minecraft.util.SignatureUpdater$Output
- net.minecraft.util.SignatureValidator
+ net.minecraft.util.Signer
- net.minecraft.util.SimpleBitStorage
+ net.minecraft.util.SimpleBitStorage$InitializationException
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.SpawnUtil
- net.minecraft.util.SpawnUtil$Strategy
+ net.minecraft.util.StringDecomposer
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringRepresentable$1
- net.minecraft.util.StringRepresentable$EnumCodec
+ net.minecraft.util.StringUtil
- net.minecraft.util.TaskChainer
+ net.minecraft.util.TaskChainer$DelayedTask
- net.minecraft.util.TelemetryConstants
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
- net.minecraft.util.TimeSource
+ net.minecraft.util.TimeSource$NanoTimeSource
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.ToFloatFunction$1
+ net.minecraft.util.ToFloatFunction$2
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
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
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.ZeroBitStorage
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
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.damagesource.PointDamageSource
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$FactorData
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
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
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.Croak
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FlyingRandomStroll
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToTargetLocation
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomLookAround
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.RandomSwim
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
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StayCloseToTarget
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TryFindLand
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
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
+ net.minecraft.world.entity.ai.behavior.warden.Digging
- net.minecraft.world.entity.ai.behavior.warden.Emerging
+ net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
- net.minecraft.world.entity.ai.behavior.warden.package-info
- net.minecraft.world.entity.ai.behavior.warden.Roar
+ net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
- net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
+ net.minecraft.world.entity.ai.behavior.warden.Sniffing
- net.minecraft.world.entity.ai.behavior.warden.SonicBoom
+ net.minecraft.world.entity.ai.behavior.warden.TryToSniff
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
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
+ net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
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
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStandGoal
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
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
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
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
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
+ net.minecraft.world.entity.animal.allay.Allay
- net.minecraft.world.entity.animal.allay.Allay$AllayVibrationListenerConfig
+ net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
- net.minecraft.world.entity.animal.allay.AllayAi
+ net.minecraft.world.entity.animal.allay.package-info
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
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
+ net.minecraft.world.entity.animal.camel.Camel
- net.minecraft.world.entity.animal.camel.Camel$1
+ net.minecraft.world.entity.animal.camel.Camel$CamelBodyRotationControl
- net.minecraft.world.entity.animal.camel.CamelAi
+ net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
- net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
+ net.minecraft.world.entity.animal.camel.package-info
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
- net.minecraft.world.entity.animal.frog.Frog
+ net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
- net.minecraft.world.entity.animal.frog.Frog$FrogNodeEvaluator
+ net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
- net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
+ net.minecraft.world.entity.animal.frog.ShootTongue
- net.minecraft.world.entity.animal.frog.ShootTongue$1
+ net.minecraft.world.entity.animal.frog.ShootTongue$State
- net.minecraft.world.entity.animal.frog.Tadpole
+ net.minecraft.world.entity.animal.frog.TadpoleAi
+ net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.GoatAi
+ net.minecraft.world.entity.animal.goat.package-info
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
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
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
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
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
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
- net.minecraft.world.entity.AnimationState
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
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.decoration.PaintingVariant
+ net.minecraft.world.entity.decoration.PaintingVariants
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
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
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
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
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
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.WardenAi
- net.minecraft.world.entity.monster.warden.WardenAi$1
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
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
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.ProfileKeyPair
- net.minecraft.world.entity.player.ProfilePublicKey
+ net.minecraft.world.entity.player.ProfilePublicKey$Data
- net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
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
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
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
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
- net.minecraft.world.entity.vehicle.ChestBoat
+ net.minecraft.world.entity.vehicle.ChestBoat$1
- net.minecraft.world.entity.vehicle.ContainerEntity
+ net.minecraft.world.entity.vehicle.ContainerEntity$1
- net.minecraft.world.entity.vehicle.DismountHelper
+ net.minecraft.world.entity.vehicle.Minecart
- net.minecraft.world.entity.vehicle.MinecartChest
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock
- net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ net.minecraft.world.entity.vehicle.MinecartFurnace
- net.minecraft.world.entity.vehicle.MinecartHopper
+ net.minecraft.world.entity.vehicle.MinecartSpawner
- net.minecraft.world.entity.vehicle.MinecartSpawner$1
+ net.minecraft.world.entity.vehicle.MinecartTNT
- net.minecraft.world.entity.vehicle.package-info
+ net.minecraft.world.flag.FeatureElement
- net.minecraft.world.flag.FeatureFlag
+ net.minecraft.world.flag.FeatureFlagRegistry
- net.minecraft.world.flag.FeatureFlagRegistry$Builder
+ net.minecraft.world.flag.FeatureFlags
+ net.minecraft.world.flag.FeatureFlagSet
- net.minecraft.world.flag.FeatureFlagUniverse
- net.minecraft.world.flag.package-info
+ net.minecraft.world.food.FoodConstants
- net.minecraft.world.food.FoodData
+ net.minecraft.world.food.FoodProperties
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractContainerMenu$1
+ net.minecraft.world.inventory.AbstractFurnaceMenu
- net.minecraft.world.inventory.AnvilMenu
+ net.minecraft.world.inventory.AnvilMenu$1
- net.minecraft.world.inventory.BeaconMenu
+ net.minecraft.world.inventory.BeaconMenu$1
- net.minecraft.world.inventory.BeaconMenu$PaymentSlot
+ net.minecraft.world.inventory.BlastFurnaceMenu
- net.minecraft.world.inventory.BrewingStandMenu
+ net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
- net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
+ net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
- net.minecraft.world.inventory.CartographyTableMenu
+ net.minecraft.world.inventory.CartographyTableMenu$1
- net.minecraft.world.inventory.CartographyTableMenu$2
+ net.minecraft.world.inventory.CartographyTableMenu$3
- net.minecraft.world.inventory.CartographyTableMenu$4
+ net.minecraft.world.inventory.CartographyTableMenu$5
- net.minecraft.world.inventory.ChestMenu
+ net.minecraft.world.inventory.ClickAction
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
- net.minecraft.world.inventory.ContainerSynchronizer
+ net.minecraft.world.inventory.CraftingContainer
- net.minecraft.world.inventory.CraftingMenu
+ net.minecraft.world.inventory.DataSlot
- net.minecraft.world.inventory.DataSlot$1
+ net.minecraft.world.inventory.DataSlot$2
- net.minecraft.world.inventory.DataSlot$3
+ net.minecraft.world.inventory.DispenserMenu
- net.minecraft.world.inventory.EnchantmentMenu
+ net.minecraft.world.inventory.EnchantmentMenu$1
- net.minecraft.world.inventory.EnchantmentMenu$2
+ net.minecraft.world.inventory.EnchantmentMenu$3
- net.minecraft.world.inventory.FurnaceFuelSlot
+ net.minecraft.world.inventory.FurnaceMenu
- net.minecraft.world.inventory.FurnaceResultSlot
+ net.minecraft.world.inventory.GrindstoneMenu
- net.minecraft.world.inventory.GrindstoneMenu$1
+ net.minecraft.world.inventory.GrindstoneMenu$2
- net.minecraft.world.inventory.GrindstoneMenu$3
+ net.minecraft.world.inventory.GrindstoneMenu$4
- net.minecraft.world.inventory.HopperMenu
+ net.minecraft.world.inventory.HorseInventoryMenu
- net.minecraft.world.inventory.HorseInventoryMenu$1
+ net.minecraft.world.inventory.HorseInventoryMenu$2
- net.minecraft.world.inventory.InventoryMenu
+ net.minecraft.world.inventory.InventoryMenu$1
- net.minecraft.world.inventory.InventoryMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu
- net.minecraft.world.inventory.ItemCombinerMenu$1
+ net.minecraft.world.inventory.ItemCombinerMenu$2
- net.minecraft.world.inventory.LecternMenu
+ net.minecraft.world.inventory.LecternMenu$1
- net.minecraft.world.inventory.LoomMenu
+ net.minecraft.world.inventory.LoomMenu$1
- net.minecraft.world.inventory.LoomMenu$2
+ net.minecraft.world.inventory.LoomMenu$3
- net.minecraft.world.inventory.LoomMenu$4
+ net.minecraft.world.inventory.LoomMenu$5
- net.minecraft.world.inventory.LoomMenu$6
+ net.minecraft.world.inventory.MenuConstructor
- net.minecraft.world.inventory.MenuType
+ net.minecraft.world.inventory.MenuType$MenuSupplier
- net.minecraft.world.inventory.MerchantContainer
+ net.minecraft.world.inventory.MerchantMenu
- net.minecraft.world.inventory.MerchantResultSlot
+ net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
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
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.item.AdventureModeCheck
- net.minecraft.world.item.AirItem
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
- net.minecraft.world.item.BoatItem
+ net.minecraft.world.item.BoneMealItem
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BucketItem
+ net.minecraft.world.item.BundleItem
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
- net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
- net.minecraft.world.item.StackInventory
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSources
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$SpawnFinder
- net.minecraft.world.level.biome.Climate$SpawnFinder$Result
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FeatureSorter
+ net.minecraft.world.level.biome.FeatureSorter$1FeatureData
- net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
+ net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
+ net.minecraft.world.level.block.AnvilBlock
- net.minecraft.world.level.block.AttachedStemBlock
+ net.minecraft.world.level.block.AzaleaBlock
- net.minecraft.world.level.block.BambooBlock
+ net.minecraft.world.level.block.BambooSaplingBlock
- net.minecraft.world.level.block.BannerBlock
+ net.minecraft.world.level.block.BarrelBlock
- net.minecraft.world.level.block.BarrierBlock
+ net.minecraft.world.level.block.BaseCoralFanBlock
- net.minecraft.world.level.block.BaseCoralPlantBlock
+ net.minecraft.world.level.block.BaseCoralPlantTypeBlock
- net.minecraft.world.level.block.BaseCoralWallFanBlock
+ net.minecraft.world.level.block.BaseEntityBlock
- net.minecraft.world.level.block.BaseFireBlock
+ net.minecraft.world.level.block.BasePressurePlateBlock
- net.minecraft.world.level.block.BaseRailBlock
+ net.minecraft.world.level.block.BaseRailBlock$1
- net.minecraft.world.level.block.BeaconBeamBlock
+ net.minecraft.world.level.block.BeaconBlock
- net.minecraft.world.level.block.BedBlock
+ net.minecraft.world.level.block.BedBlock$1
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BigDripleafBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock
- net.minecraft.world.level.block.BigDripleafStemBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BrewingStandBlock
+ net.minecraft.world.level.block.BubbleColumnBlock
- net.minecraft.world.level.block.BucketPickup
+ net.minecraft.world.level.block.BuddingAmethystBlock
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
+ net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleBlock
+ net.minecraft.world.level.block.CandleCakeBlock
- net.minecraft.world.level.block.CarpetBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.CaveVines
- net.minecraft.world.level.block.CaveVinesBlock
+ net.minecraft.world.level.block.CaveVinesPlantBlock
- net.minecraft.world.level.block.CeilingHangingSignBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChiseledBookShelfBlock
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DirtPathBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropExperienceBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BannerPatterns
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
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
+ net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
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
+ net.minecraft.world.level.block.entity.HangingSignBlockEntity
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
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
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
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ net.minecraft.world.level.block.Fallable
- net.minecraft.world.level.block.FallingBlock
+ net.minecraft.world.level.block.FarmBlock
- net.minecraft.world.level.block.FenceBlock
+ net.minecraft.world.level.block.FenceGateBlock
- net.minecraft.world.level.block.FenceGateBlock$1
+ net.minecraft.world.level.block.FireBlock
- net.minecraft.world.level.block.FletchingTableBlock
+ net.minecraft.world.level.block.FlowerBlock
- net.minecraft.world.level.block.FlowerPotBlock
+ net.minecraft.world.level.block.FrogspawnBlock
- net.minecraft.world.level.block.FrostedIceBlock
+ net.minecraft.world.level.block.FungusBlock
- net.minecraft.world.level.block.FurnaceBlock
+ net.minecraft.world.level.block.GameMasterBlock
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GlowLichenBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GravelBlock
+ net.minecraft.world.level.block.GrindstoneBlock
- net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.AzaleaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.MangroveTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.GrowingPlantBlock
- net.minecraft.world.level.block.GrowingPlantBodyBlock
+ net.minecraft.world.level.block.GrowingPlantHeadBlock
- net.minecraft.world.level.block.HalfTransparentBlock
+ net.minecraft.world.level.block.HangingRootsBlock
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HoneyBlock
- net.minecraft.world.level.block.HopperBlock
+ net.minecraft.world.level.block.HopperBlock$1
- net.minecraft.world.level.block.HorizontalDirectionalBlock
+ net.minecraft.world.level.block.HugeMushroomBlock
- net.minecraft.world.level.block.IceBlock
+ net.minecraft.world.level.block.InfestedBlock
- net.minecraft.world.level.block.InfestedRotatedPillarBlock
+ net.minecraft.world.level.block.IronBarsBlock
- net.minecraft.world.level.block.JigsawBlock
+ net.minecraft.world.level.block.JukeboxBlock
- net.minecraft.world.level.block.KelpBlock
+ net.minecraft.world.level.block.KelpPlantBlock
- net.minecraft.world.level.block.LadderBlock
+ net.minecraft.world.level.block.LadderBlock$1
- net.minecraft.world.level.block.LanternBlock
+ net.minecraft.world.level.block.LavaCauldronBlock
- net.minecraft.world.level.block.LayeredCauldronBlock
+ net.minecraft.world.level.block.LeavesBlock
- net.minecraft.world.level.block.LecternBlock
+ net.minecraft.world.level.block.LecternBlock$1
- net.minecraft.world.level.block.LevelEvent
+ net.minecraft.world.level.block.LeverBlock
- net.minecraft.world.level.block.LeverBlock$1
+ net.minecraft.world.level.block.LightBlock
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MangroveLeavesBlock
- net.minecraft.world.level.block.MangrovePropaguleBlock
+ net.minecraft.world.level.block.MangroveRootsBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MudBlock
+ net.minecraft.world.level.block.MultifaceBlock
- net.minecraft.world.level.block.MultifaceSpreader
+ net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadConfig
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPredicate
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$1
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$3
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
+ net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PipeBlock
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
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PowderSnowCauldronBlock
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
+ net.minecraft.world.level.block.SculkBehaviour
- net.minecraft.world.level.block.SculkBehaviour$1
+ net.minecraft.world.level.block.SculkBlock
- net.minecraft.world.level.block.SculkCatalystBlock
+ net.minecraft.world.level.block.SculkSensorBlock
- net.minecraft.world.level.block.SculkShriekerBlock
+ net.minecraft.world.level.block.SculkSpreader
- net.minecraft.world.level.block.SculkSpreader$ChargeCursor
+ net.minecraft.world.level.block.SculkVeinBlock
- net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
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
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.RotationSegment
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
+ net.minecraft.world.level.block.WallHangingSignBlock
- net.minecraft.world.level.block.WallHangingSignBlock$1
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
- net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BlockColumn
+ net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.chunk.CarvingMask
+ net.minecraft.world.level.chunk.CarvingMask$Mask
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
- net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.Level$2
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.commands.CommandBuildContext +2M -3M | +1P -3P
```
```
XXX.minecraft.commands.CommandBuildContext$2 +3M -1M | +3P -1P
```
```
XXX.minecraft.core.Registry$1 +6M -7M
```
```
XXX.minecraft.core.RegistryAccess +1M
```
```
XXX.data.tags.BannerPatternTagsProvider +2M -2M
```
```
XXX.data.tags.CatVariantTagsProvider +2M -2M
```
```
XXX.data.tags.FlatLevelGeneratorPresetTagsProvider +2M -2M
```
```
XXX.data.tags.GameEventTagsProvider +3M -2M
```
```
XXX.data.tags.ItemTagsProvider +2M -1M
```
```
XXX.data.tags.PoiTypeTagsProvider +2M -2M
```
```
XXX.data.tags.TagsProvider +7M -5M | +3P -2P
```
```
XXX.data.tags.UpdateOneTwentyBlockTagsProvider +3M -2M
```
```
XXX.data.tags.VanillaBlockTagsProvider +3M -2M
```
```
XXX.data.tags.WorldPresetTagsProvider +2M -2M
```
```
XXX.data.worldgen.AncientCityStructurePieces +1M -1M | +1P -1P
```
```
XXX.data.worldgen.BastionBridgePools +1M -2M
```
```
XXX.data.worldgen.BastionHousingUnitsPools +1M -2M
```
```
XXX.data.worldgen.BastionSharedPools +1M -2M
```
```
XXX.data.worldgen.Carvers +2M -1M | +4P -4P
```
```
XXX.data.worldgen.DimensionTypes +1M -1M
```
```
XXX.data.worldgen.PillagerOutpostPools +1M -1M | +1P -1P
```
```
XXX.data.worldgen.Pools +3M -3M | -1P
```
```
XXX.data.worldgen.SavannaVillagePools +1M -1M | +3P -1P
```
```
XXX.data.worldgen.StructureSets +1M -4M | -18P
```
```
XXX.worldgen.biome.Biomes +1M -1M
```
```
XXX.worldgen.biome.NetherBiomes +5M -5M
```
```
XXX.worldgen.features.CaveFeatures +1M | +24P -30P
```
```
XXX.worldgen.features.FeatureUtils +4M -3M
```
```
XXX.worldgen.features.NetherFeatures +1M | +22P -24P
```
```
XXX.worldgen.features.PileFeatures +1M | +5P -5P
```
```
XXX.worldgen.features.VegetationFeatures +1M | +43P -43P
```
```
XXX.worldgen.placement.CavePlacements +1M | +20P -20P
```
```
XXX.worldgen.placement.MiscOverworldPlacements +1M | +18P -18P
```
```
XXX.worldgen.placement.OrePlacements +1M | +39P -39P
```
```
XXX.worldgen.placement.TreePlacements +1M | +27P -29P
```
```
XXX.worldgen.placement.VillagePlacements +1M | +13P -13P
```
```
XXX.protocol.game.ClientboundAddEntityPacket -2M
```
```
XXX.minecraft.resources.HolderSetCodec +2M -2M
```
```
XXX.world.item.CreativeModeTabs$1 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$11 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$2 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$4 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$6 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$8 +1M -1M
```
```
XXX.world.item.ItemStack +1M
```
```
XXX.world.level.Explosion$BlockInteraction +2P -2P
```
```
XXX.world.level.GameRules +7P
```
```
XXX.world.level.Level +6M -4M
```
```
XXX.level.biome.BiomeGenerationSettings$Builder +3M -8M | +2P -2P
```
```
XXX.level.levelgen.DebugLevelSource +3M -5M | -1P
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +16M -17M | -1P
```
```
XXX.level.levelgen.Noises +1M -1M
```
```
XXX.level.levelgen.RandomState +3M -4M | +1P -2P
```
```
XXX.level.levelgen.WorldOptions +3M -2M
```
```
XXX.levelgen.flat.FlatLevelGeneratorPresets +1M -1M
```
```
XXX.levelgen.flat.FlatLevelGeneratorSettings +12M -11M | +1P -1P
```
```
XXX.levelgen.presets.WorldPresets$Bootstrap +3M -3M | +5P -10P
```
```
XXX.structure.placement.RandomSpreadStructurePlacement +1M -1M
```
```
XXX.structure.placement.StructurePlacement$ExclusionZone +1M -1M
```
```
XXX.structure.pools.JigsawPlacement$Placer +6M -4M
```
```
XXX.structure.pools.StructurePoolElement +1P
```
```
XXX.structure.pools.StructureTemplatePool +3M -4M | +2P -3P
```
```
XXX.structure.templatesystem.StructureTemplate +2M -2M
```
```
XXX.structure.templatesystem.StructureTemplateManager +1M -1M | +1P -1P
```
```
XXX.level.material.FlowingFluid +6M -6M | +1P -1P
```
```
XXX.level.material.LavaFluid +1M -1M
```
```
XXX.level.material.WaterFluid +1M -1M
```
```
XXX.level.pathfinder.NodeEvaluator +2M | +1P
```
```
XXX.level.pathfinder.WalkNodeEvaluator +1M | +1P
```

</details>







































































































<details>
<summary>
net.minecraft.commands.CommandBuildContext
</summary>

```diff
- CommandBuildContext simple(HolderLookup$Provider,FeatureFlagSet)
- CommandBuildContext$Configurable configurable(RegistryAccess,FeatureFlagSet)
+ HolderLookup holderLookup(ResourceKey)
+ void <init>(RegistryAccess,FeatureFlagSet)
+ void missingTagAccessPolicy(CommandBuildContext$MissingTagAccessPolicy)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandBuildContext$2
</summary>

```diff
- HolderLookup holderLookup(ResourceKey)
+ void <clinit>()
- void <init>(RegistryAccess,FeatureFlagSet)
- void missingTagAccessPolicy(CommandBuildContext$MissingTagAccessPolicy)
```

</details>


<details>
<summary>
net.minecraft.core.Registry$1
</summary>

```diff
+ Holder byId(int)
+ Holder lambda$iterator$0(Holder$Reference)
+ int getId(Holder)
+ int getId(Object)
+ int size()
+ Iterator iterator()
- Lifecycle elementsLifecycle()
+ Object byId(int)
- Optional get(ResourceKey)
- Optional get(TagKey)
- ResourceKey key()
- Stream listElements()
- Stream listTags()
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess
</summary>

```diff
- Optional lookup(ResourceKey)
```

</details>






<details>
<summary>
net.minecraft.data.tags.BannerPatternTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.CatVariantTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.GameEventTagsProvider
</summary>

```diff
- ResourceKey lambda$new$0(GameEvent)
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.ItemTagsProvider
</summary>

```diff
- ResourceKey lambda$new$0(Item)
- void <init>(PackOutput,CompletableFuture,TagsProvider)
+ void <init>(PackOutput,TagsProvider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.PoiTypeTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.TagsProvider
</summary>

```diff
- boolean lambda$run$0(HolderLookup$RegistryLookup,ResourceLocation)
+ boolean lambda$run$0(TagEntry)
- boolean lambda$run$1(Predicate,TagEntry)
+ CompletableFuture lambda$run$1(CachedOutput,Map$Entry)
- CompletableFuture lambda$run$2(Predicate,CachedOutput,Map$Entry)
+ CompletableFuture[] lambda$run$2(int)
- CompletableFuture[] lambda$run$3(int)
- CompletionStage lambda$run$4(CachedOutput,HolderLookup$Provider)
+ TagBuilder lambda$getOrCreateRawBuilder$3(ResourceLocation)
- TagBuilder lambda$getOrCreateRawBuilder$5(ResourceLocation)
+ void <init>(PackOutput,Registry)
- void <init>(PackOutput,ResourceKey,CompletableFuture)
```

</details>
<details>
<summary>
net.minecraft.data.tags.UpdateOneTwentyBlockTagsProvider
</summary>

```diff
- ResourceKey lambda$new$0(Block)
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.VanillaBlockTagsProvider
</summary>

```diff
- ResourceKey lambda$new$0(Block)
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.WorldPresetTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.AncientCityStructurePieces
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.BastionBridgePools
</summary>

```diff
+ void <clinit>()
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.BastionHousingUnitsPools
</summary>

```diff
+ void <clinit>()
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.BastionSharedPools
</summary>

```diff
+ void <clinit>()
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>

<details>
<summary>
net.minecraft.data.worldgen.Carvers
</summary>

```diff
+ Holder register(String,ConfiguredWorldCarver)
- ResourceKey createKey(String)
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.DimensionTypes
</summary>

```diff
+ Holder bootstrap(Registry)
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.PillagerOutpostPools
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.Pools
</summary>

```diff
+ Holder bootstrap(Registry)
+ Holder register(StructureTemplatePool)
- ResourceKey createKey(String)
- void bootstrap(BootstapContext)
+ void forceBootstrap()
- void register(BootstapContext,String,StructureTemplatePool)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.SavannaVillagePools
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.StructureSets
</summary>

```diff
+ Holder bootstrap(Registry)
+ Holder register(ResourceKey,Holder,StructurePlacement)
+ Holder register(ResourceKey,StructureSet)
+ void <clinit>()
- void bootstrap(BootstapContext)
```

</details>


<details>
<summary>
net.minecraft.data.worldgen.biome.Biomes
</summary>

```diff
+ Holder bootstrap(Registry)
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.biome.NetherBiomes
</summary>

```diff
+ Biome basaltDeltas()
- Biome basaltDeltas(HolderGetter,HolderGetter)
+ Biome crimsonForest()
- Biome crimsonForest(HolderGetter,HolderGetter)
+ Biome netherWastes()
- Biome netherWastes(HolderGetter,HolderGetter)
+ Biome soulSandValley()
- Biome soulSandValley(HolderGetter,HolderGetter)
+ Biome warpedForest()
- Biome warpedForest(HolderGetter,HolderGetter)
```

</details>

<details>
<summary>
net.minecraft.data.worldgen.features.CaveFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.FeatureUtils
</summary>

```diff
+ Holder bootstrap(Registry)
+ Holder register(String,Feature,FeatureConfiguration)
+ Holder register(String,Feature)
- ResourceKey createKey(String)
- void bootstrap(BootstapContext)
- void register(BootstapContext,ResourceKey,Feature,FeatureConfiguration)
- void register(BootstapContext,ResourceKey,Feature)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.NetherFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.PileFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.VegetationFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>

<details>
<summary>
net.minecraft.data.worldgen.placement.CavePlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.MiscOverworldPlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.OrePlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.TreePlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.VillagePlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>

















































































































<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAddEntityPacket
</summary>

```diff
+ void <init>(LivingEntity,int)
+ void <init>(LivingEntity)
```

</details>

































































































































<details>
<summary>
net.minecraft.resources.HolderSetCodec
</summary>

```diff
- HolderSet lambda$decode$3(HolderGetter,Either)
+ HolderSet lambda$decode$3(Registry,Either)
- Pair lambda$decode$4(HolderGetter,Pair)
+ Pair lambda$decode$4(Registry,Pair)
```

</details>

<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$1
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$11
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$2
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$4
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$6
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$8
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>






















<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- ItemStack copyWithCount(int)
```

</details>







































































































<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Explosion$BlockInteraction)
- Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Level$ExplosionInteraction,boolean)
- Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Level$ExplosionInteraction)
+ Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,Vec3,float,boolean,Explosion$BlockInteraction)
- Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,Vec3,float,boolean,Level$ExplosionInteraction)
+ Explosion explode(Entity,double,double,double,float,boolean,Explosion$BlockInteraction)
- Explosion explode(Entity,double,double,double,float,boolean,Level$ExplosionInteraction)
+ Explosion explode(Entity,double,double,double,float,Explosion$BlockInteraction)
- Explosion explode(Entity,double,double,double,float,Level$ExplosionInteraction)
- Explosion$BlockInteraction getDestroyType(GameRules$Key)
```

</details>




















<details>
<summary>
net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
</summary>

```diff
+ BiomeGenerationSettings build()
+ BiomeGenerationSettings$Builder addCarver(GenerationStep$Carving,Holder)
- BiomeGenerationSettings$Builder addCarver(GenerationStep$Carving,ResourceKey)
+ BiomeGenerationSettings$Builder addFeature(GenerationStep$Decoration,Holder)
- BiomeGenerationSettings$Builder addFeature(GenerationStep$Decoration,ResourceKey)
+ BiomeGenerationSettings$Builder addFeature(int,Holder)
+ HolderSet lambda$build$1(Map$Entry)
+ List lambda$addCarver$0(GenerationStep$Carving)
+ void <init>()
- void <init>(HolderGetter,HolderGetter)
+ void addFeatureStepsUpTo(int)
```

</details>





































































<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ App lambda$static$1(RecordCodecBuilder$Instance)
+ Registry biomes()
+ Registry lambda$static$0(DebugLevelSource)
- Stream lambda$static$1(Block)
+ Stream lambda$static$2(Block)
- void <init>(Holder$Reference)
+ void <init>(Registry,Registry)
```

</details>




























<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$3(RecordCodecBuilder$Instance)
- Aquifer$FluidPicker lambda$new$3(Holder)
+ Aquifer$FluidPicker lambda$new$4(Holder)
- Aquifer$FluidStatus lambda$createFluidPicker$4(Aquifer$FluidStatus,int,Aquifer$FluidStatus,Aquifer$FluidStatus,int,int,int)
+ Aquifer$FluidStatus lambda$createFluidPicker$5(Aquifer$FluidStatus,int,Aquifer$FluidStatus,Aquifer$FluidStatus,int,int,int)
- BiomeGenerationSettings lambda$applyCarvers$10(ChunkPos,RandomState)
+ BiomeGenerationSettings lambda$applyCarvers$11(ChunkPos,RandomState)
- BiomeSource lambda$static$0(NoiseBasedChunkGenerator)
+ BiomeSource lambda$static$1(NoiseBasedChunkGenerator)
- ChunkAccess lambda$createBiomes$5(Blender,RandomState,StructureManager,ChunkAccess)
+ ChunkAccess lambda$createBiomes$6(Blender,RandomState,StructureManager,ChunkAccess)
- ChunkAccess lambda$fillFromNoise$11(Blender,StructureManager,RandomState,ChunkAccess,int,int)
+ ChunkAccess lambda$fillFromNoise$12(Blender,StructureManager,RandomState,ChunkAccess,int,int)
- CompletableFuture createBiomes(Executor,RandomState,Blender,StructureManager,ChunkAccess)
+ CompletableFuture createBiomes(Registry,Executor,RandomState,Blender,StructureManager,ChunkAccess)
- Holder lambda$applyCarvers$8(RandomState,int,int,int)
+ Holder lambda$applyCarvers$9(RandomState,int,int,int)
- Holder lambda$static$1(NoiseBasedChunkGenerator)
+ Holder lambda$static$2(NoiseBasedChunkGenerator)
+ NoiseChunk lambda$applyCarvers$10(StructureManager,WorldGenRegion,RandomState,ChunkAccess)
- NoiseChunk lambda$applyCarvers$9(StructureManager,WorldGenRegion,RandomState,ChunkAccess)
- NoiseChunk lambda$buildSurface$7(StructureManager,Blender,RandomState,ChunkAccess)
+ NoiseChunk lambda$buildSurface$8(StructureManager,Blender,RandomState,ChunkAccess)
- NoiseChunk lambda$doCreateBiomes$6(StructureManager,Blender,RandomState,ChunkAccess)
+ NoiseChunk lambda$doCreateBiomes$7(StructureManager,Blender,RandomState,ChunkAccess)
- NoiseChunk lambda$doFill$13(StructureManager,Blender,RandomState,ChunkAccess)
+ NoiseChunk lambda$doFill$14(StructureManager,Blender,RandomState,ChunkAccess)
+ Registry lambda$static$0(NoiseBasedChunkGenerator)
- void <init>(BiomeSource,Holder)
+ void <init>(Registry,Registry,BiomeSource,Holder)
- void lambda$fillFromNoise$12(Set,ChunkAccess,Throwable)
+ void lambda$fillFromNoise$13(Set,ChunkAccess,Throwable)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.Noises
</summary>

```diff
- NormalNoise instantiate(HolderGetter,PositionalRandomFactory,ResourceKey)
+ NormalNoise instantiate(Registry,PositionalRandomFactory,ResourceKey)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.RandomState
</summary>

```diff
+ long legacyLevelSeed()
- RandomState create(HolderGetter$Provider,ResourceKey,long)
- RandomState create(NoiseGeneratorSettings,HolderGetter,long)
+ RandomState create(NoiseGeneratorSettings,Registry,long)
+ RandomState create(RegistryAccess,ResourceKey,long)
- void <init>(NoiseGeneratorSettings,HolderGetter,long)
+ void <init>(NoiseGeneratorSettings,Registry,long)
```

</details>



























<details>
<summary>
net.minecraft.world.level.levelgen.WorldOptions
</summary>

```diff
- long parseSeedOrElseRandom(String)
- long randomSeed()
+ OptionalLong parseSeed(String)
- WorldOptions withSeed(long)
+ WorldOptions withSeed(OptionalLong)
```

</details>
















































































































<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
</summary>

```diff
+ Holder bootstrap(Registry)
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ App lambda$static$5(RecordCodecBuilder$Instance)
- Boolean lambda$static$1(FlatLevelGeneratorSettings)
+ Boolean lambda$static$3(FlatLevelGeneratorSettings)
- boolean lambda$updateLayers$5(BlockState)
+ boolean lambda$updateLayers$6(BlockState)
- FlatLevelGeneratorSettings getDefault(HolderGetter,HolderGetter,HolderGetter)
+ FlatLevelGeneratorSettings getDefault(Registry,Registry)
- FlatLevelGeneratorSettings withBiomeAndLayers(List,Optional,Holder)
+ FlatLevelGeneratorSettings withLayers(List,Optional)
- Holder getBiome(Optional,Holder)
- Holder getDefaultBiome(HolderGetter)
- List createLakesList(HolderGetter)
- Optional lambda$static$0(FlatLevelGeneratorSettings)
+ Optional lambda$static$1(FlatLevelGeneratorSettings)
- Optional lambda$static$3(FlatLevelGeneratorSettings)
+ Optional lambda$static$4(FlatLevelGeneratorSettings)
+ Registry lambda$static$0(FlatLevelGeneratorSettings)
- void <init>(Optional,Holder,List)
- void <init>(Optional,List,boolean,boolean,Optional,Holder$Reference,Holder,Holder)
+ void <init>(Optional,Registry)
+ void <init>(Registry,Optional,List,boolean,boolean,Optional)
+ void setBiome(Holder)
```

</details>



















<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
</summary>

```diff
+ Holder registerCustomOverworldPreset(ResourceKey,LevelStem)
+ Holder run()
- void <init>(BootstapContext)
+ void <init>(Registry)
- void registerCustomOverworldPreset(ResourceKey,LevelStem)
- void run()
```

</details>





















<details>
<summary>
net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
</summary>

```diff
+ boolean isPlacementChunk(ChunkGenerator,RandomState,long,int,int)
- boolean isPlacementChunk(ChunkGeneratorStructureState,int,int)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
</summary>

```diff
+ boolean isPlacementForbidden(ChunkGenerator,RandomState,long,int,int)
- boolean isPlacementForbidden(ChunkGeneratorStructureState,int,int)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
</summary>

```diff
- Holder lambda$tryPlacingChildren$1(Holder)
+ int lambda$tryPlacingChildren$3(BoundingBox,StructureTemplate$StructureBlockInfo)
- int lambda$tryPlacingChildren$4(BoundingBox,StructureTemplate$StructureBlockInfo)
+ Integer lambda$tryPlacingChildren$1(StructureTemplatePool)
- Integer lambda$tryPlacingChildren$2(Holder)
+ Integer lambda$tryPlacingChildren$2(StructureTemplatePool)
- Integer lambda$tryPlacingChildren$3(Holder)
+ Optional lambda$tryPlacingChildren$0(StructureTemplatePool)
- ResourceKey readPoolName(StructureTemplate$StructureBlockInfo)
- String lambda$tryPlacingChildren$0(ResourceKey)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
</summary>

```diff
- Holder getFallback()
+ ResourceLocation getFallback()
+ ResourceLocation getName()
- void <init>(Holder,List,StructureTemplatePool$Projection)
- void <init>(Holder,List)
+ void <init>(ResourceLocation,ResourceLocation,List,StructureTemplatePool$Projection)
+ void <init>(ResourceLocation,ResourceLocation,List)
```

</details>














































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
</summary>

```diff
- void load(HolderGetter,CompoundTag)
+ void load(HolderLookup,CompoundTag)
- void loadPalette(HolderGetter,ListTag,ListTag)
+ void loadPalette(HolderLookup,ListTag,ListTag)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
</summary>

```diff
- void <init>(ResourceManager,LevelStorageSource$LevelStorageAccess,DataFixer,HolderGetter)
+ void <init>(ResourceManager,LevelStorageSource$LevelStorageAccess,DataFixer,HolderLookup)
```

</details>

















<details>
<summary>
net.minecraft.world.level.material.FlowingFluid
</summary>

```diff
- boolean lambda$getSpread$4(Level,BlockPos,BlockPos,BlockState,short)
+ boolean lambda$getSpread$4(LevelReader,BlockPos,BlockPos,BlockState,short)
- FluidState getNewLiquid(Level,BlockPos,BlockState)
+ FluidState getNewLiquid(LevelReader,BlockPos,BlockState)
- Map getSpread(Level,BlockPos,BlockState)
+ Map getSpread(LevelReader,BlockPos,BlockState)
- Pair lambda$getSpread$3(Level,BlockPos,short)
+ Pair lambda$getSpread$3(LevelReader,BlockPos,short)
- void spread(Level,BlockPos,FluidState)
+ void spread(LevelAccessor,BlockPos,FluidState)
- void spreadToSides(Level,BlockPos,FluidState,BlockState)
+ void spreadToSides(LevelAccessor,BlockPos,FluidState,BlockState)
```

</details>


<details>
<summary>
net.minecraft.world.level.material.LavaFluid
</summary>

```diff
+ boolean canConvertToSource()
- boolean canConvertToSource(Level)
```

</details>



<details>
<summary>
net.minecraft.world.level.material.WaterFluid
</summary>

```diff
+ boolean canConvertToSource()
- boolean canConvertToSource(Level)
```

</details>




<details>
<summary>
net.minecraft.world.level.pathfinder.NodeEvaluator
</summary>

```diff
- boolean canWalkOverFences()
- void setCanWalkOverFences(boolean)
```

</details>


<details>
<summary>
net.minecraft.world.level.pathfinder.WalkNodeEvaluator
</summary>

```diff
- double getMobJumpHeight()
```

</details>





















































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.commands.arguments.AngleArgument
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.ArgumentSignatures
+ net.minecraft.commands.arguments.ArgumentSignatures$Entry
- net.minecraft.commands.arguments.ArgumentSignatures$Signer
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.BlockStateParser$BlockResult
- net.minecraft.commands.arguments.blocks.BlockStateParser$TagResult
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
- net.minecraft.commands.arguments.EntityArgument$Info
+ net.minecraft.commands.arguments.EntityArgument$Info$Template
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
- net.minecraft.commands.arguments.item.ItemParser$ItemResult
+ net.minecraft.commands.arguments.item.ItemParser$TagResult
- net.minecraft.commands.arguments.item.ItemPredicateArgument
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
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
+ net.minecraft.commands.arguments.ResourceArgument
- net.minecraft.commands.arguments.ResourceArgument$Info
+ net.minecraft.commands.arguments.ResourceArgument$Info$Template
- net.minecraft.commands.arguments.ResourceKeyArgument
+ net.minecraft.commands.arguments.ResourceKeyArgument$Info
- net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
- net.minecraft.commands.arguments.ScoreHolderArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument$Info
- net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.arguments.selector.EntitySelector
+ net.minecraft.commands.arguments.selector.EntitySelector$1
- net.minecraft.commands.arguments.selector.EntitySelectorParser
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
- net.minecraft.commands.arguments.selector.options.package-info
+ net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.SignedArgument
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.StringRepresentableArgument
+ net.minecraft.commands.arguments.TeamArgument
- net.minecraft.commands.arguments.TemplateMirrorArgument
+ net.minecraft.commands.arguments.TemplateRotationArgument
- net.minecraft.commands.arguments.TimeArgument
+ net.minecraft.commands.arguments.UuidArgument
- net.minecraft.commands.CommandBuildContext$2$1
- net.minecraft.commands.CommandBuildContext$Configurable
+ net.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
- net.minecraft.commands.CommandFunction
+ net.minecraft.commands.CommandFunction$CacheableFunction
- net.minecraft.commands.CommandFunction$CommandEntry
+ net.minecraft.commands.CommandFunction$Entry
- net.minecraft.commands.CommandFunction$FunctionEntry
+ net.minecraft.commands.CommandRuntimeException
- net.minecraft.commands.Commands
- net.minecraft.commands.Commands$1$1
+ net.minecraft.commands.Commands$CommandSelection
- net.minecraft.commands.Commands$ParseFunction
- net.minecraft.commands.CommandSigningContext
+ net.minecraft.commands.CommandSigningContext$1
- net.minecraft.commands.CommandSigningContext$SignedArguments
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
- net.minecraft.commands.package-info
+ net.minecraft.commands.SharedSuggestionProvider
- net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ net.minecraft.commands.synchronization.ArgumentTypeInfo
- net.minecraft.commands.synchronization.ArgumentTypeInfo$Template
+ net.minecraft.commands.synchronization.ArgumentTypeInfos
- net.minecraft.commands.synchronization.ArgumentUtils
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo
- net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.LongArgumentInfo
- net.minecraft.commands.synchronization.brigadier.LongArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.package-info
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$Template
+ net.minecraft.commands.synchronization.package-info
+ net.minecraft.commands.synchronization.SingletonArgumentInfo
- net.minecraft.commands.synchronization.SingletonArgumentInfo$Template
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
- net.minecraft.core.cauldron.CauldronInteraction
+ net.minecraft.core.cauldron.package-info
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
- net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
+ net.minecraft.core.dispenser.BoatDispenseItemBehavior
- net.minecraft.core.dispenser.DefaultDispenseItemBehavior
+ net.minecraft.core.dispenser.DispenseItemBehavior
- net.minecraft.core.dispenser.DispenseItemBehavior$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$10
- net.minecraft.core.dispenser.DispenseItemBehavior$11
+ net.minecraft.core.dispenser.DispenseItemBehavior$12
- net.minecraft.core.dispenser.DispenseItemBehavior$13
+ net.minecraft.core.dispenser.DispenseItemBehavior$14
- net.minecraft.core.dispenser.DispenseItemBehavior$15
+ net.minecraft.core.dispenser.DispenseItemBehavior$16
- net.minecraft.core.dispenser.DispenseItemBehavior$17
+ net.minecraft.core.dispenser.DispenseItemBehavior$18
- net.minecraft.core.dispenser.DispenseItemBehavior$19
+ net.minecraft.core.dispenser.DispenseItemBehavior$2
- net.minecraft.core.dispenser.DispenseItemBehavior$20
+ net.minecraft.core.dispenser.DispenseItemBehavior$21
- net.minecraft.core.dispenser.DispenseItemBehavior$22
+ net.minecraft.core.dispenser.DispenseItemBehavior$23
- net.minecraft.core.dispenser.DispenseItemBehavior$24
+ net.minecraft.core.dispenser.DispenseItemBehavior$25
- net.minecraft.core.dispenser.DispenseItemBehavior$26
+ net.minecraft.core.dispenser.DispenseItemBehavior$27
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
+ net.minecraft.core.FrontAndTop
- net.minecraft.core.GlobalPos
+ net.minecraft.core.Holder
- net.minecraft.core.Holder$Direct
+ net.minecraft.core.Holder$Kind
- net.minecraft.core.Holder$Reference
+ net.minecraft.core.Holder$Reference$Type
- net.minecraft.core.HolderGetter
- net.minecraft.core.HolderLookup
- net.minecraft.core.HolderLookup$Delegate
- net.minecraft.core.HolderLookup$Provider$1
- net.minecraft.core.HolderOwner
+ net.minecraft.core.HolderSet
- net.minecraft.core.HolderSet$Direct
+ net.minecraft.core.HolderSet$ListBacked
- net.minecraft.core.HolderSet$Named
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.LayeredRegistryAccess
- net.minecraft.core.MappedRegistry
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
+ net.minecraft.core.particles.SculkChargeParticleOptions
- net.minecraft.core.particles.SculkChargeParticleOptions$1
+ net.minecraft.core.particles.ShriekParticleOption
- net.minecraft.core.particles.ShriekParticleOption$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.particles.VibrationParticleOption$1
- net.minecraft.core.Registry$2
- net.minecraft.core.RegistrySetBuilder$1
- net.minecraft.core.RegistrySetBuilder$BuildState$1
- net.minecraft.core.RegistrySetBuilder$EmptyTagLookup
- net.minecraft.core.RegistrySetBuilder$RegistryBootstrap
- net.minecraft.core.RegistrySetBuilder$RegistryContents$1
- net.minecraft.core.RegistrySetBuilder$UniversalLookup
- net.minecraft.core.RegistrySynchronization
+ net.minecraft.core.RegistrySynchronization$NetworkedRegistryData
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.UUIDUtil
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdvancementSubProvider
+ net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.packs.package-info
- net.minecraft.data.advancements.packs.VanillaAdvancementProvider
+ net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
- net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
+ net.minecraft.data.advancements.packs.VanillaNetherAdvancements
- net.minecraft.data.advancements.packs.VanillaStoryAdvancements
+ net.minecraft.data.advancements.packs.VanillaTheEndAdvancements
- net.minecraft.data.BlockFamilies
+ net.minecraft.data.BlockFamily
- net.minecraft.data.BlockFamily$Builder
+ net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.BuiltinRegistries$RegistryBootstrap
- net.minecraft.data.CachedOutput
+ net.minecraft.data.DataGenerator
- net.minecraft.data.DataGenerator$PackGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.DataProvider$Factory
+ net.minecraft.data.HashCache
- net.minecraft.data.HashCache$CacheUpdater
+ net.minecraft.data.HashCache$ProviderCache
- net.minecraft.data.HashCache$ProviderCacheBuilder
+ net.minecraft.data.HashCache$UpdateFunction
- net.minecraft.data.HashCache$UpdateResult
+ net.minecraft.data.info.BiomeParametersDumpReport
- net.minecraft.data.info.BlockListReport
+ net.minecraft.data.info.CommandsReport
+ net.minecraft.data.info.package-info
- net.minecraft.data.info.RegistryDumpReport
- net.minecraft.data.loot.BlockLootSubProvider
+ net.minecraft.data.loot.EntityLootSubProvider
- net.minecraft.data.loot.LootTableProvider
+ net.minecraft.data.loot.LootTableProvider$SubProviderEntry
- net.minecraft.data.loot.LootTableSubProvider
+ net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.packs.package-info
- net.minecraft.data.loot.packs.UpdateOneTwentyBlockLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyLootTableProvider
- net.minecraft.data.loot.packs.VanillaBlockLoot
+ net.minecraft.data.loot.packs.VanillaChestLoot
- net.minecraft.data.loot.packs.VanillaEntityLoot
+ net.minecraft.data.loot.packs.VanillaFishingLoot
- net.minecraft.data.loot.packs.VanillaGiftLoot
+ net.minecraft.data.loot.packs.VanillaLootTableProvider
- net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
+ net.minecraft.data.Main
+ net.minecraft.data.metadata.package-info
- net.minecraft.data.metadata.PackMetadataGenerator
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ net.minecraft.data.models.BlockModelGenerators$TintState
- net.minecraft.data.models.BlockModelGenerators$WoodProvider
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
- net.minecraft.data.PackOutput
+ net.minecraft.data.PackOutput$PathProvider
- net.minecraft.data.PackOutput$Target
+ net.minecraft.data.recipes.CraftingRecipeBuilder
- net.minecraft.data.recipes.CraftingRecipeBuilder$1
+ net.minecraft.data.recipes.CraftingRecipeBuilder$CraftingResult
- net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.package-info
+ net.minecraft.data.recipes.packs.BundleRecipeProvider
- net.minecraft.data.recipes.packs.package-info
- net.minecraft.data.recipes.packs.UpdateOneTwentyRecipeProvider
+ net.minecraft.data.recipes.packs.VanillaRecipeProvider
+ net.minecraft.data.recipes.RecipeBuilder
- net.minecraft.data.recipes.RecipeCategory
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
- net.minecraft.data.registries.VanillaRegistries
- net.minecraft.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
- net.minecraft.data.worldgen.BootstapContext
+ net.minecraft.data.worldgen.BuiltinRegistriesDatapackGenerator
- net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader$1
+ net.minecraft.resources.RegistryDataLoader$Loader
- net.minecraft.resources.RegistryDataLoader$RegistryData
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryOps
- net.minecraft.resources.RegistryOps$1
- net.minecraft.resources.RegistryOps$RegistryInfo
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Dummy
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.chase.ChaseClient
+ net.minecraft.server.chase.ChaseClient$TeleportTarget
- net.minecraft.server.chase.ChaseServer
+ net.minecraft.server.chase.ChaseServer$PlayerPosition
- net.minecraft.server.chase.package-info
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.AttributeCommand
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ChaseCommand
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
- net.minecraft.server.commands.DebugCommand$Tracer
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
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
+ net.minecraft.server.commands.JfrCommand
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaceCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ResetChunksCommand
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
+ net.minecraft.server.commands.WardenSpawnTrackerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
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
+ net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerLevel$EntityCallbacks
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayer$1
- net.minecraft.server.level.ServerPlayer$2
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.TickingTracker
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$ReloadableResources
- net.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ net.minecraft.server.MinecraftServer$TimeProfiler
- net.minecraft.server.MinecraftServer$TimeProfiler$1
+ net.minecraft.server.network.FilteredText
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
- net.minecraft.server.network.TextFilterClient
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
- net.minecraft.server.network.TextFilterClient$JoinOrLeaveEncoder
+ net.minecraft.server.network.TextFilterClient$MessageEncoder
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.BuiltInMetadata
- net.minecraft.server.packs.FeatureFlagsMetadataSection
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.linkfs.DummyFileAttributes
+ net.minecraft.server.packs.linkfs.LinkFileSystem
- net.minecraft.server.packs.linkfs.LinkFileSystem$Builder
+ net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
+ net.minecraft.server.packs.linkfs.LinkFSFileStore
- net.minecraft.server.packs.linkfs.LinkFSPath
+ net.minecraft.server.packs.linkfs.LinkFSPath$1
- net.minecraft.server.packs.linkfs.LinkFSPath$2
+ net.minecraft.server.packs.linkfs.LinkFSPath$3
- net.minecraft.server.packs.linkfs.LinkFSProvider
+ net.minecraft.server.packs.linkfs.LinkFSProvider$1
- net.minecraft.server.packs.linkfs.LinkFSProvider$2
+ net.minecraft.server.packs.linkfs.package-info
- net.minecraft.server.packs.linkfs.PathContents
+ net.minecraft.server.packs.linkfs.PathContents$1
- net.minecraft.server.packs.linkfs.PathContents$2
+ net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
- net.minecraft.server.packs.linkfs.PathContents$FileContents
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.MetadataSectionType
- net.minecraft.server.packs.metadata.MetadataSectionType$1
+ net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
- net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackResources$ResourceOutput
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.PathPackResources
- net.minecraft.server.packs.repository.BuiltInPackSource
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$Info
- net.minecraft.server.packs.repository.Pack$Position
+ net.minecraft.server.packs.repository.Pack$ResourcesSupplier
- net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.PackSource
+ net.minecraft.server.packs.repository.PackSource$1
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.resources.CloseableResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
- net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
+ net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
- net.minecraft.server.packs.resources.IoSupplier
+ net.minecraft.server.packs.resources.MultiPackResourceManager
+ net.minecraft.server.packs.resources.package-info
- net.minecraft.server.packs.resources.PreparableReloadListener
+ net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
- net.minecraft.server.packs.resources.ProfiledReloadInstance
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceFilterSection
- net.minecraft.server.packs.resources.ResourceFilterSection$ResourceLocationPattern
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.ResourceMetadata
+ net.minecraft.server.packs.resources.ResourceMetadata$1
- net.minecraft.server.packs.resources.ResourceMetadata$2
+ net.minecraft.server.packs.resources.ResourceProvider
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.VanillaPackResources
+ net.minecraft.server.packs.VanillaPackResourcesBuilder
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
+ net.minecraft.server.RegistryLayer
- net.minecraft.server.ReloadableServerResources
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$ExecutionContext
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerFunctionManager$TraceCallbacks
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.Services
- net.minecraft.server.TickTask
+ net.minecraft.server.WorldLoader
- net.minecraft.server.WorldLoader$DataLoadContext
+ net.minecraft.server.WorldLoader$DataLoadOutput
- net.minecraft.server.WorldLoader$InitConfig
+ net.minecraft.server.WorldLoader$PackConfig
- net.minecraft.server.WorldLoader$ResultFactory
+ net.minecraft.server.WorldLoader$WorldDataSupplier
- net.minecraft.server.WorldStem
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
- net.minecraft.tags.BannerPatternTags
+ net.minecraft.tags.BiomeTags
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.CatVariantTags
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FlatLevelGeneratorPresetTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.InstrumentTags
+ net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
- net.minecraft.tags.PaintingVariantTags
+ net.minecraft.tags.PoiTypeTags
- net.minecraft.tags.StructureTags
+ net.minecraft.tags.TagBuilder
- net.minecraft.tags.TagEntry
+ net.minecraft.tags.TagEntry$Lookup
- net.minecraft.tags.TagFile
+ net.minecraft.tags.TagKey
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagLoader$1
- net.minecraft.tags.TagLoader$EntryWithSource
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$LoadResult
+ net.minecraft.tags.TagNetworkSerialization
- net.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ net.minecraft.tags.TagNetworkSerialization$TagOutput
- net.minecraft.tags.WorldPresetTags
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.Crypt$ByteArrayToKeyFunction
+ net.minecraft.util.Crypt$SaltSignaturePair
- net.minecraft.util.Crypt$SaltSupplier
+ net.minecraft.util.CryptException
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.CubicSpline
+ net.minecraft.util.CubicSpline$1Point
- net.minecraft.util.CubicSpline$Builder
+ net.minecraft.util.CubicSpline$Constant
- net.minecraft.util.CubicSpline$CoordinateVisitor
+ net.minecraft.util.CubicSpline$Multipoint
+ net.minecraft.util.datafix.DataFixerOptimizationOption
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixers$3
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
- net.minecraft.util.datafix.fixes.AbstractPoiSectionFix
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlendingDataFix
+ net.minecraft.util.datafix.fixes.BlendingDataRemoveFromNetherEndFix
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
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkDeleteIgnoredLightDataFix
+ net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ net.minecraft.util.datafix.fixes.ChunkRenamesFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.CriteriaRenameFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityGoatMissingStateFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingFieldsRenameFix
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
+ net.minecraft.util.datafix.fixes.EntityVariantFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.FilteredBooksFix
+ net.minecraft.util.datafix.fixes.FilteredSignsFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GoatHornIdFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTagFix
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
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
+ net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
- net.minecraft.util.datafix.fixes.PoiTypeRenameFix
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
+ net.minecraft.util.datafix.fixes.SimpleRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VariantRenameFix
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
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
- net.minecraft.util.datafix.schemas.V1451_6$1
+ net.minecraft.util.datafix.schemas.V1451_6$2
- net.minecraft.util.datafix.schemas.V1451_7
+ net.minecraft.util.datafix.schemas.V1460
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
+ net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2686
+ net.minecraft.util.datafix.schemas.V2688
- net.minecraft.util.datafix.schemas.V2704
+ net.minecraft.util.datafix.schemas.V2707
- net.minecraft.util.datafix.schemas.V2831
+ net.minecraft.util.datafix.schemas.V2832
- net.minecraft.util.datafix.schemas.V2842
+ net.minecraft.util.datafix.schemas.V3076
- net.minecraft.util.datafix.schemas.V3078
+ net.minecraft.util.datafix.schemas.V3081
- net.minecraft.util.datafix.schemas.V3082
+ net.minecraft.util.datafix.schemas.V3083
- net.minecraft.util.datafix.schemas.V3202
+ net.minecraft.util.datafix.schemas.V3203
- net.minecraft.util.datafix.schemas.V3204
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
- net.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ net.minecraft.util.ExtraCodecs$2
- net.minecraft.util.ExtraCodecs$3
+ net.minecraft.util.ExtraCodecs$4
- net.minecraft.util.ExtraCodecs$EitherCodec
+ net.minecraft.util.ExtraCodecs$LazyInitializedCodec
- net.minecraft.util.ExtraCodecs$TagOrElementLocation
+ net.minecraft.util.ExtraCodecs$XorCodec
- net.minecraft.util.FastBufferedInputStream
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FileZipper
- net.minecraft.util.FormattedCharSequence
+ net.minecraft.util.FormattedCharSink
- net.minecraft.util.FrameTimer
+ net.minecraft.util.FutureChain
- net.minecraft.util.Graph
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InclusiveRange
- net.minecraft.util.KeyDispatchDataCodec
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.MemoryReserve
- net.minecraft.util.ModCheck
+ net.minecraft.util.ModCheck$Confidence
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.Mth
+ net.minecraft.util.NativeModuleLister
- net.minecraft.util.NativeModuleLister$NativeModuleInfo
+ net.minecraft.util.NativeModuleLister$NativeModuleVersion
- net.minecraft.util.OptionEnum
+ net.minecraft.util.package-info
+ net.minecraft.util.ParticleUtils
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
+ net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
+ net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
- net.minecraft.util.profiling.jfr.stats.TimeStamped
+ net.minecraft.util.profiling.jfr.SummaryReporter
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
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.ProgressListener
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
+ net.minecraft.util.RandomSource
- net.minecraft.util.SignatureUpdater
+ net.minecraft.util.SignatureUpdater$Output
- net.minecraft.util.SignatureValidator
+ net.minecraft.util.Signer
- net.minecraft.util.SimpleBitStorage
+ net.minecraft.util.SimpleBitStorage$InitializationException
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.SpawnUtil
- net.minecraft.util.SpawnUtil$Strategy
+ net.minecraft.util.StringDecomposer
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringRepresentable$1
- net.minecraft.util.StringRepresentable$EnumCodec
+ net.minecraft.util.StringUtil
- net.minecraft.util.TaskChainer
+ net.minecraft.util.TaskChainer$DelayedTask
- net.minecraft.util.TelemetryConstants
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
- net.minecraft.util.TimeSource
+ net.minecraft.util.TimeSource$NanoTimeSource
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.ToFloatFunction$1
+ net.minecraft.util.ToFloatFunction$2
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
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
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.ZeroBitStorage
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
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.damagesource.PointDamageSource
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$FactorData
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
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
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.Croak
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FlyingRandomStroll
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToTargetLocation
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomLookAround
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.RandomSwim
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
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StayCloseToTarget
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TryFindLand
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
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
+ net.minecraft.world.entity.ai.behavior.warden.Digging
- net.minecraft.world.entity.ai.behavior.warden.Emerging
+ net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
- net.minecraft.world.entity.ai.behavior.warden.package-info
- net.minecraft.world.entity.ai.behavior.warden.Roar
+ net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
- net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
+ net.minecraft.world.entity.ai.behavior.warden.Sniffing
- net.minecraft.world.entity.ai.behavior.warden.SonicBoom
+ net.minecraft.world.entity.ai.behavior.warden.TryToSniff
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
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
+ net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
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
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStandGoal
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
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
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
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
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
+ net.minecraft.world.entity.animal.allay.Allay
- net.minecraft.world.entity.animal.allay.Allay$AllayVibrationListenerConfig
+ net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
- net.minecraft.world.entity.animal.allay.AllayAi
+ net.minecraft.world.entity.animal.allay.package-info
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
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
+ net.minecraft.world.entity.animal.camel.Camel
- net.minecraft.world.entity.animal.camel.Camel$1
+ net.minecraft.world.entity.animal.camel.Camel$CamelBodyRotationControl
- net.minecraft.world.entity.animal.camel.CamelAi
+ net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
- net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
+ net.minecraft.world.entity.animal.camel.package-info
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
- net.minecraft.world.entity.animal.frog.Frog
+ net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
- net.minecraft.world.entity.animal.frog.Frog$FrogNodeEvaluator
+ net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
- net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
+ net.minecraft.world.entity.animal.frog.ShootTongue
- net.minecraft.world.entity.animal.frog.ShootTongue$1
+ net.minecraft.world.entity.animal.frog.ShootTongue$State
- net.minecraft.world.entity.animal.frog.Tadpole
+ net.minecraft.world.entity.animal.frog.TadpoleAi
+ net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.GoatAi
+ net.minecraft.world.entity.animal.goat.package-info
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
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
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
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
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
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
- net.minecraft.world.entity.AnimationState
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
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.decoration.PaintingVariant
+ net.minecraft.world.entity.decoration.PaintingVariants
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
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
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
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
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
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.WardenAi
- net.minecraft.world.entity.monster.warden.WardenAi$1
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
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
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.ProfileKeyPair
- net.minecraft.world.entity.player.ProfilePublicKey
+ net.minecraft.world.entity.player.ProfilePublicKey$Data
- net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
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
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
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
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
- net.minecraft.world.entity.vehicle.ChestBoat
+ net.minecraft.world.entity.vehicle.ChestBoat$1
- net.minecraft.world.entity.vehicle.ContainerEntity
+ net.minecraft.world.entity.vehicle.ContainerEntity$1
- net.minecraft.world.entity.vehicle.DismountHelper
+ net.minecraft.world.entity.vehicle.Minecart
- net.minecraft.world.entity.vehicle.MinecartChest
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock
- net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ net.minecraft.world.entity.vehicle.MinecartFurnace
- net.minecraft.world.entity.vehicle.MinecartHopper
+ net.minecraft.world.entity.vehicle.MinecartSpawner
- net.minecraft.world.entity.vehicle.MinecartSpawner$1
+ net.minecraft.world.entity.vehicle.MinecartTNT
- net.minecraft.world.entity.vehicle.package-info
+ net.minecraft.world.flag.FeatureElement
- net.minecraft.world.flag.FeatureFlag
+ net.minecraft.world.flag.FeatureFlagRegistry
- net.minecraft.world.flag.FeatureFlagRegistry$Builder
+ net.minecraft.world.flag.FeatureFlags
+ net.minecraft.world.flag.FeatureFlagSet
- net.minecraft.world.flag.FeatureFlagUniverse
- net.minecraft.world.flag.package-info
+ net.minecraft.world.food.FoodConstants
- net.minecraft.world.food.FoodData
+ net.minecraft.world.food.FoodProperties
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractContainerMenu$1
+ net.minecraft.world.inventory.AbstractFurnaceMenu
- net.minecraft.world.inventory.AnvilMenu
+ net.minecraft.world.inventory.AnvilMenu$1
- net.minecraft.world.inventory.BeaconMenu
+ net.minecraft.world.inventory.BeaconMenu$1
- net.minecraft.world.inventory.BeaconMenu$PaymentSlot
+ net.minecraft.world.inventory.BlastFurnaceMenu
- net.minecraft.world.inventory.BrewingStandMenu
+ net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
- net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
+ net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
- net.minecraft.world.inventory.CartographyTableMenu
+ net.minecraft.world.inventory.CartographyTableMenu$1
- net.minecraft.world.inventory.CartographyTableMenu$2
+ net.minecraft.world.inventory.CartographyTableMenu$3
- net.minecraft.world.inventory.CartographyTableMenu$4
+ net.minecraft.world.inventory.CartographyTableMenu$5
- net.minecraft.world.inventory.ChestMenu
+ net.minecraft.world.inventory.ClickAction
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
- net.minecraft.world.inventory.ContainerSynchronizer
+ net.minecraft.world.inventory.CraftingContainer
- net.minecraft.world.inventory.CraftingMenu
+ net.minecraft.world.inventory.DataSlot
- net.minecraft.world.inventory.DataSlot$1
+ net.minecraft.world.inventory.DataSlot$2
- net.minecraft.world.inventory.DataSlot$3
+ net.minecraft.world.inventory.DispenserMenu
- net.minecraft.world.inventory.EnchantmentMenu
+ net.minecraft.world.inventory.EnchantmentMenu$1
- net.minecraft.world.inventory.EnchantmentMenu$2
+ net.minecraft.world.inventory.EnchantmentMenu$3
- net.minecraft.world.inventory.FurnaceFuelSlot
+ net.minecraft.world.inventory.FurnaceMenu
- net.minecraft.world.inventory.FurnaceResultSlot
+ net.minecraft.world.inventory.GrindstoneMenu
- net.minecraft.world.inventory.GrindstoneMenu$1
+ net.minecraft.world.inventory.GrindstoneMenu$2
- net.minecraft.world.inventory.GrindstoneMenu$3
+ net.minecraft.world.inventory.GrindstoneMenu$4
- net.minecraft.world.inventory.HopperMenu
+ net.minecraft.world.inventory.HorseInventoryMenu
- net.minecraft.world.inventory.HorseInventoryMenu$1
+ net.minecraft.world.inventory.HorseInventoryMenu$2
- net.minecraft.world.inventory.InventoryMenu
+ net.minecraft.world.inventory.InventoryMenu$1
- net.minecraft.world.inventory.InventoryMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu
- net.minecraft.world.inventory.ItemCombinerMenu$1
+ net.minecraft.world.inventory.ItemCombinerMenu$2
- net.minecraft.world.inventory.LecternMenu
+ net.minecraft.world.inventory.LecternMenu$1
- net.minecraft.world.inventory.LoomMenu
+ net.minecraft.world.inventory.LoomMenu$1
- net.minecraft.world.inventory.LoomMenu$2
+ net.minecraft.world.inventory.LoomMenu$3
- net.minecraft.world.inventory.LoomMenu$4
+ net.minecraft.world.inventory.LoomMenu$5
- net.minecraft.world.inventory.LoomMenu$6
+ net.minecraft.world.inventory.MenuConstructor
- net.minecraft.world.inventory.MenuType
+ net.minecraft.world.inventory.MenuType$MenuSupplier
- net.minecraft.world.inventory.MerchantContainer
+ net.minecraft.world.inventory.MerchantMenu
- net.minecraft.world.inventory.MerchantResultSlot
+ net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
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
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.item.AdventureModeCheck
- net.minecraft.world.item.AirItem
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
- net.minecraft.world.item.BoatItem
+ net.minecraft.world.item.BoneMealItem
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BucketItem
+ net.minecraft.world.item.BundleItem
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
- net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
- net.minecraft.world.item.StackInventory
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSources
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$SpawnFinder
- net.minecraft.world.level.biome.Climate$SpawnFinder$Result
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FeatureSorter
+ net.minecraft.world.level.biome.FeatureSorter$1FeatureData
- net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
+ net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
+ net.minecraft.world.level.block.AnvilBlock
- net.minecraft.world.level.block.AttachedStemBlock
+ net.minecraft.world.level.block.AzaleaBlock
- net.minecraft.world.level.block.BambooBlock
+ net.minecraft.world.level.block.BambooSaplingBlock
- net.minecraft.world.level.block.BannerBlock
+ net.minecraft.world.level.block.BarrelBlock
- net.minecraft.world.level.block.BarrierBlock
+ net.minecraft.world.level.block.BaseCoralFanBlock
- net.minecraft.world.level.block.BaseCoralPlantBlock
+ net.minecraft.world.level.block.BaseCoralPlantTypeBlock
- net.minecraft.world.level.block.BaseCoralWallFanBlock
+ net.minecraft.world.level.block.BaseEntityBlock
- net.minecraft.world.level.block.BaseFireBlock
+ net.minecraft.world.level.block.BasePressurePlateBlock
- net.minecraft.world.level.block.BaseRailBlock
+ net.minecraft.world.level.block.BaseRailBlock$1
- net.minecraft.world.level.block.BeaconBeamBlock
+ net.minecraft.world.level.block.BeaconBlock
- net.minecraft.world.level.block.BedBlock
+ net.minecraft.world.level.block.BedBlock$1
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BigDripleafBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock
- net.minecraft.world.level.block.BigDripleafStemBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BrewingStandBlock
+ net.minecraft.world.level.block.BubbleColumnBlock
- net.minecraft.world.level.block.BucketPickup
+ net.minecraft.world.level.block.BuddingAmethystBlock
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
+ net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleBlock
+ net.minecraft.world.level.block.CandleCakeBlock
- net.minecraft.world.level.block.CarpetBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.CaveVines
- net.minecraft.world.level.block.CaveVinesBlock
+ net.minecraft.world.level.block.CaveVinesPlantBlock
- net.minecraft.world.level.block.CeilingHangingSignBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChiseledBookShelfBlock
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DirtPathBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropExperienceBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BannerPatterns
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
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
+ net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
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
+ net.minecraft.world.level.block.entity.HangingSignBlockEntity
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
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
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
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ net.minecraft.world.level.block.Fallable
- net.minecraft.world.level.block.FallingBlock
+ net.minecraft.world.level.block.FarmBlock
- net.minecraft.world.level.block.FenceBlock
+ net.minecraft.world.level.block.FenceGateBlock
- net.minecraft.world.level.block.FenceGateBlock$1
+ net.minecraft.world.level.block.FireBlock
- net.minecraft.world.level.block.FletchingTableBlock
+ net.minecraft.world.level.block.FlowerBlock
- net.minecraft.world.level.block.FlowerPotBlock
+ net.minecraft.world.level.block.FrogspawnBlock
- net.minecraft.world.level.block.FrostedIceBlock
+ net.minecraft.world.level.block.FungusBlock
- net.minecraft.world.level.block.FurnaceBlock
+ net.minecraft.world.level.block.GameMasterBlock
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GlowLichenBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GravelBlock
+ net.minecraft.world.level.block.GrindstoneBlock
- net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.AzaleaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.MangroveTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.GrowingPlantBlock
- net.minecraft.world.level.block.GrowingPlantBodyBlock
+ net.minecraft.world.level.block.GrowingPlantHeadBlock
- net.minecraft.world.level.block.HalfTransparentBlock
+ net.minecraft.world.level.block.HangingRootsBlock
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HoneyBlock
- net.minecraft.world.level.block.HopperBlock
+ net.minecraft.world.level.block.HopperBlock$1
- net.minecraft.world.level.block.HorizontalDirectionalBlock
+ net.minecraft.world.level.block.HugeMushroomBlock
- net.minecraft.world.level.block.IceBlock
+ net.minecraft.world.level.block.InfestedBlock
- net.minecraft.world.level.block.InfestedRotatedPillarBlock
+ net.minecraft.world.level.block.IronBarsBlock
- net.minecraft.world.level.block.JigsawBlock
+ net.minecraft.world.level.block.JukeboxBlock
- net.minecraft.world.level.block.KelpBlock
+ net.minecraft.world.level.block.KelpPlantBlock
- net.minecraft.world.level.block.LadderBlock
+ net.minecraft.world.level.block.LadderBlock$1
- net.minecraft.world.level.block.LanternBlock
+ net.minecraft.world.level.block.LavaCauldronBlock
- net.minecraft.world.level.block.LayeredCauldronBlock
+ net.minecraft.world.level.block.LeavesBlock
- net.minecraft.world.level.block.LecternBlock
+ net.minecraft.world.level.block.LecternBlock$1
- net.minecraft.world.level.block.LevelEvent
+ net.minecraft.world.level.block.LeverBlock
- net.minecraft.world.level.block.LeverBlock$1
+ net.minecraft.world.level.block.LightBlock
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MangroveLeavesBlock
- net.minecraft.world.level.block.MangrovePropaguleBlock
+ net.minecraft.world.level.block.MangroveRootsBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MudBlock
+ net.minecraft.world.level.block.MultifaceBlock
- net.minecraft.world.level.block.MultifaceSpreader
+ net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadConfig
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPredicate
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$1
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$3
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
+ net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PipeBlock
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
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PowderSnowCauldronBlock
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
+ net.minecraft.world.level.block.SculkBehaviour
- net.minecraft.world.level.block.SculkBehaviour$1
+ net.minecraft.world.level.block.SculkBlock
- net.minecraft.world.level.block.SculkCatalystBlock
+ net.minecraft.world.level.block.SculkSensorBlock
- net.minecraft.world.level.block.SculkShriekerBlock
+ net.minecraft.world.level.block.SculkSpreader
- net.minecraft.world.level.block.SculkSpreader$ChargeCursor
+ net.minecraft.world.level.block.SculkVeinBlock
- net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
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
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.RotationSegment
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
+ net.minecraft.world.level.block.WallHangingSignBlock
- net.minecraft.world.level.block.WallHangingSignBlock$1
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
- net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BlockColumn
+ net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.chunk.CarvingMask
+ net.minecraft.world.level.chunk.CarvingMask$Mask
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
- net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.Level$2
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.client.Minecraft +34M -33M
```
```
XXX.gui.screens.PresetFlatWorldScreen +6M -5M
```
```
XXX.screens.worldselection.WorldGenSettingsComponent +2M -2M | +1P -1P
```
```
XXX.minecraft.commands.CommandBuildContext$1 +2M -3M | +2P -1P
```
```
XXX.minecraft.core.HolderLookup$RegistryLookup -6M | +2P -1P
```
```
XXX.minecraft.core.Registry +17M -15M | +1P -2P
```
```
XXX.data.tags.BiomeTagsProvider +2M -4M
```
```
XXX.data.tags.EntityTypeTagsProvider +3M -2M
```
```
XXX.data.tags.FluidTagsProvider +3M -2M
```
```
XXX.data.tags.InstrumentTagsProvider +2M -2M
```
```
XXX.data.tags.PaintingVariantTagsProvider +2M -2M
```
```
XXX.data.tags.StructureTagsProvider +2M -2M
```
```
XXX.data.tags.TagsProvider$TagAppender +2M -4M | -1P
```
```
XXX.data.tags.UpdateOneTwentyItemTagsProvider +2M -2M
```
```
XXX.data.tags.VanillaItemTagsProvider +2M -2M
```
```
XXX.data.worldgen.AncientCityStructurePools +1M -2M
```
```
XXX.data.worldgen.BastionHoglinStablePools +1M -2M
```
```
XXX.data.worldgen.BastionPieces +1M -1M | +1P -1P
```
```
XXX.data.worldgen.BastionTreasureRoomPools +1M -2M
```
```
XXX.data.worldgen.DesertVillagePools +1M -1M | +3P -1P
```
```
XXX.data.worldgen.NoiseData +4M -3M | +1P
```
```
XXX.data.worldgen.PlainVillagePools +1M -1M | +2P -1P
```
```
XXX.data.worldgen.ProcessorLists +3M -1M | +36P -38P
```
```
XXX.data.worldgen.SnowyVillagePools +1M -1M | +2P -1P
```
```
XXX.data.worldgen.Structures +6M -9M | -32P
```
```
XXX.data.worldgen.TaigaVillagePools +1M -1M | +2P -1P
```
```
XXX.data.worldgen.VillagePools +1M -1M
```
```
XXX.worldgen.biome.EndBiomes +5M -5M
```
```
XXX.worldgen.biome.OverworldBiomes +34M -34M
```
```
XXX.worldgen.features.AquaticFeatures +1M | +8P -8P
```
```
XXX.worldgen.features.EndFeatures +1M | +5P -5P
```
```
XXX.worldgen.features.MiscOverworldFeatures +1M | +18P -18P
```
```
XXX.worldgen.features.OreFeatures +1M | +31P -42P
```
```
XXX.worldgen.features.TreeFeatures +1M | +35P -40P
```
```
XXX.worldgen.placement.AquaticPlacements +1M | +13P -13P
```
```
XXX.worldgen.placement.EndPlacements +1M | +4P -4P
```
```
XXX.worldgen.placement.NetherPlacements +1M | +20P -21P
```
```
XXX.worldgen.placement.PlacementUtils +4M -3M
```
```
XXX.worldgen.placement.VegetationPlacements +1M | +73P -73P
```
```
XXX.minecraft.nbt.NbtUtils +1M -1M
```
```
XXX.network.chat.ChatType +1M -1M
```
```
XXX.minecraft.resources.HolderSetCodec +2M -2M
```
```
XXX.world.item.CreativeModeTabs$1 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$11 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$2 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$4 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$6 +1M -1M
```
```
XXX.world.item.CreativeModeTabs$8 +1M -1M
```
```
XXX.world.item.ItemStack +1M
```
```
XXX.world.level.Explosion$BlockInteraction +2P -2P
```
```
XXX.world.level.GameRules +7P
```
```
XXX.world.level.Level +6M -4M
```
```
XXX.level.biome.BiomeGenerationSettings$Builder +3M -8M | +2P -2P
```
```
XXX.level.levelgen.DebugLevelSource +3M -5M | -1P
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +16M -17M | -1P
```
```
XXX.level.levelgen.Noises +1M -1M
```
```
XXX.level.levelgen.RandomState +3M -4M | +1P -2P
```
```
XXX.level.levelgen.WorldOptions +3M -2M
```
```
XXX.levelgen.flat.FlatLevelGeneratorPresets +1M -1M
```
```
XXX.levelgen.flat.FlatLevelGeneratorSettings +12M -11M | +1P -1P
```
```
XXX.levelgen.presets.WorldPresets$Bootstrap +3M -3M | +5P -10P
```
```
XXX.structure.placement.RandomSpreadStructurePlacement +1M -1M
```
```
XXX.structure.placement.StructurePlacement$ExclusionZone +1M -1M
```
```
XXX.structure.pools.JigsawPlacement$Placer +6M -4M
```
```
XXX.structure.pools.StructurePoolElement +1P
```
```
XXX.structure.pools.StructureTemplatePool +3M -4M | +2P -3P
```
```
XXX.structure.templatesystem.StructureTemplate +2M -2M
```
```
XXX.structure.templatesystem.StructureTemplateManager +1M -1M | +1P -1P
```
```
XXX.level.material.FlowingFluid +6M -6M | +1P -1P
```
```
XXX.level.material.LavaFluid +1M -1M
```
```
XXX.level.material.WaterFluid +1M -1M
```
```
XXX.level.pathfinder.NodeEvaluator +2M | +1P
```
```
XXX.level.pathfinder.WalkNodeEvaluator +1M | +1P
```

</details>















































































































































































































































































<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
+ boolean lambda$tick$38()
- boolean lambda$tick$39()
+ ChunkProgressListener lambda$doWorldLoad$39(int)
- ChunkProgressListener lambda$doWorldLoad$40(int)
+ CompletionStage lambda$delayTextureReload$50(CompletableFuture)
- CompletionStage lambda$delayTextureReload$51(CompletableFuture)
+ CrashReport lambda$delayCrash$20(CrashReport)
- CrashReport lambda$delayCrash$21(CrashReport)
+ CrashReport lambda$delayCrashRaw$21(CrashReport)
- CrashReport lambda$delayCrashRaw$22(CrashReport)
+ IntegratedServer lambda$doWorldLoad$40(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
- IntegratedServer lambda$doWorldLoad$41(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
+ String lambda$doWorldLoad$41(WorldStem)
- String lambda$doWorldLoad$42(WorldStem)
+ String lambda$fillSystemReport$43(String)
+ String lambda$fillSystemReport$44(Minecraft)
- String lambda$fillSystemReport$44(String)
+ String lambda$fillSystemReport$45()
- String lambda$fillSystemReport$45(Minecraft)
- String lambda$fillSystemReport$48()
+ String lambda$fillSystemReport$48(Options)
+ String lambda$fillSystemReport$49(LanguageManager)
- String lambda$fillSystemReport$49(Options)
- String lambda$fillSystemReport$50(LanguageManager)
+ Style lambda$debugClientMetricsStart$29(Path,Style)
- Style lambda$debugClientMetricsStart$30(Path,Style)
+ Style lambda$grabHugeScreenshot$53(File,Style)
- Style lambda$grabHugeScreenshot$54(File,Style)
+ Style lambda$grabPanoramixScreenshot$52(File,Style)
- Style lambda$grabPanoramixScreenshot$53(File,Style)
- void lambda$createSearchTrees$20(List)
+ void lambda$debugClientMetricsStart$27(Consumer,double,int)
- void lambda$debugClientMetricsStart$28(Consumer,double,int)
+ void lambda$debugClientMetricsStart$28(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$29(Consumer,ProfileResults)
+ void lambda$debugClientMetricsStart$30(Consumer,Component)
- void lambda$debugClientMetricsStart$31(Consumer,Component)
+ void lambda$debugClientMetricsStart$31(Consumer,Path)
- void lambda$debugClientMetricsStart$32(Consumer,Path)
+ void lambda$debugClientMetricsStart$32(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$33(Consumer,Path)
- void lambda$debugClientMetricsStart$33(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$34(Consumer,CompletableFuture,CompletableFuture)
- void lambda$debugClientMetricsStart$34(Consumer,Path)
- void lambda$debugClientMetricsStart$35(Consumer,CompletableFuture,CompletableFuture)
+ void lambda$debugClientMetricsStart$35(ProfileResults)
+ void lambda$debugClientMetricsStart$36(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$36(ProfileResults)
- void lambda$debugClientMetricsStart$37(Consumer,ProfileResults)
+ void lambda$doWorldLoad$42(Component)
- void lambda$doWorldLoad$43(Component)
+ void lambda$grabPanoramixScreenshot$51(Component)
- void lambda$grabPanoramixScreenshot$52(Component)
- void lambda$new$3(ServerAddress)
+ void lambda$new$3(String,int)
+ void lambda$openChatScreen$24(boolean)
- void lambda$openChatScreen$25(boolean)
+ void lambda$reloadResourcePacks$22(CompletableFuture)
+ void lambda$reloadResourcePacks$23(CompletableFuture,Optional)
- void lambda$reloadResourcePacks$23(CompletableFuture)
- void lambda$reloadResourcePacks$24(CompletableFuture,Optional)
+ void lambda$runTick$25(CompletableFuture)
- void lambda$runTick$26(CompletableFuture)
+ void lambda$runTick$26(TimerQuery)
- void lambda$runTick$27(TimerQuery)
+ void lambda$tick$37()
- void lambda$tick$38()
```

</details>








































































































































<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen
</summary>

```diff
- FlatLevelGeneratorSettings fromString(HolderGetter,HolderGetter,HolderGetter,String,FlatLevelGeneratorSettings)
+ FlatLevelGeneratorSettings fromString(Registry,Registry,String,FlatLevelGeneratorSettings)
- Holder$Reference lambda$fromString$1(String,Holder$Reference)
+ IllegalArgumentException lambda$fromString$0(ResourceLocation)
+ IllegalStateException lambda$save$1()
- IllegalStateException lambda$save$2()
- ResourceKey lambda$fromString$0(ResourceLocation)
+ void lambda$init$2(Registry,Registry,Button)
+ void lambda$init$3(Button)
- void lambda$init$3(HolderGetter,HolderGetter,HolderGetter,Button)
- void lambda$init$4(Button)
```

</details>










































































































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
</summary>

```diff
+ String toString(OptionalLong)
- void <init>(WorldCreationContext,Optional,long)
+ void <init>(WorldCreationContext,Optional,OptionalLong)
- void <init>(WorldCreationContext,Optional)
```

</details>
















































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.commands.CommandBuildContext$1
</summary>

```diff
- HolderLookup holderLookup(ResourceKey)
+ HolderSet$Named lambda$get$0(TagKey)
+ Optional get(TagKey)
+ void <init>(CommandBuildContext,Registry)
- void <init>(HolderLookup$Provider,FeatureFlagSet)
```

</details>
<details>
<summary>
net.minecraft.core.HolderLookup$RegistryLookup
</summary>

```diff
+ HolderLookup filterElements(Predicate)
+ Optional get(ResourceKey)
+ Optional get(TagKey)
+ Stream listElements()
+ Stream listTags()
+ void <init>(Registry)
```

</details>


<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ CatVariant lambda$static$51(Registry)
- DataResult lambda$byNameCodec$56(ResourceLocation)
- DataResult lambda$byNameCodec$58(Object)
+ DataResult lambda$byNameCodec$58(ResourceLocation)
+ DataResult lambda$byNameCodec$60(Object)
- DataResult lambda$holderByNameCodec$62(ResourceLocation)
- DataResult lambda$holderByNameCodec$64(Holder)
+ DataResult lambda$holderByNameCodec$64(ResourceLocation)
+ DataResult lambda$holderByNameCodec$66(Holder)
- FrogVariant lambda$static$51(Registry)
+ FrogVariant lambda$static$52(Registry)
- HolderLookup$RegistryLookup asLookup()
- HolderLookup$RegistryLookup asTagAddingLookup()
- HolderOwner holderOwner()
- IllegalStateException lambda$getHolderOrThrow$69(ResourceKey)
+ IllegalStateException lambda$getHolderOrThrow$70(ResourceKey)
- int lambda$byNameCodec$60(Object)
+ int lambda$byNameCodec$61(Object)
- Lifecycle lambda$byNameCodec$61(Object)
+ Lifecycle lambda$byNameCodec$62(Object)
- Lifecycle lambda$holderByNameCodec$66(Holder)
+ Lifecycle lambda$holderByNameCodec$68(Holder)
- Object lambda$internalRegister$54(Registry$RegistryBootstrap,WritableRegistry)
+ Object lambda$internalRegister$55(Registry$RegistryBootstrap,WritableRegistry)
- Object lambda$keys$68(DynamicOps,ResourceLocation)
+ Object lambda$keys$69(DynamicOps,ResourceLocation)
- String lambda$new$55(ResourceKey)
+ String lambda$new$56(ResourceKey)
- void lambda$checkRegistry$53(Registry,Registry)
+ void lambda$checkRegistry$54(Registry,Registry)
- void lambda$static$52(ResourceLocation,Supplier)
+ void lambda$static$53(ResourceLocation,Supplier)
```

</details>









<details>
<summary>
net.minecraft.data.tags.BiomeTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
+ void lambda$addTags$0(TagsProvider$TagAppender,ResourceKey)
+ void lambda$addTags$1(TagsProvider$TagAppender,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.data.tags.EntityTypeTagsProvider
</summary>

```diff
- ResourceKey lambda$new$0(EntityType)
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.FluidTagsProvider
</summary>

```diff
- ResourceKey lambda$new$0(Fluid)
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.InstrumentTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.PaintingVariantTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.StructureTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.TagsProvider$TagAppender
</summary>

```diff
+ TagsProvider$TagAppender add(Object)
+ TagsProvider$TagAppender add(Object[])
- TagsProvider$TagAppender add(ResourceKey)
+ void <init>(TagBuilder,Registry)
- void <init>(TagBuilder)
+ void lambda$add$0(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.data.tags.UpdateOneTwentyItemTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture,TagsProvider)
+ void <init>(PackOutput,TagsProvider)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.VanillaItemTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture,TagsProvider)
+ void <init>(PackOutput,TagsProvider)
+ void addTags()
- void addTags(HolderLookup$Provider)
```

</details>

<details>
<summary>
net.minecraft.data.worldgen.AncientCityStructurePools
</summary>

```diff
+ void <clinit>()
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.BastionHoglinStablePools
</summary>

```diff
+ void <clinit>()
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.BastionPieces
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.BastionTreasureRoomPools
</summary>

```diff
+ void <clinit>()
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.DesertVillagePools
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.NoiseData
</summary>

```diff
+ Holder bootstrap(Registry)
+ Holder register(Registry,ResourceKey,int,double,double[])
- void <clinit>()
- void bootstrap(BootstapContext)
- void register(BootstapContext,ResourceKey,int,double,double[])
- void registerBiomeNoises(BootstapContext,int,ResourceKey,ResourceKey,ResourceKey,ResourceKey)
+ void registerBiomeNoises(Registry,int,ResourceKey,ResourceKey,ResourceKey,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.PlainVillagePools
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.ProcessorLists
</summary>

```diff
+ Holder register(String,ImmutableList)
- ResourceKey createKey(String)
- void bootstrap(BootstapContext)
- void register(BootstapContext,ResourceKey,List)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.SnowyVillagePools
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.Structures
</summary>

```diff
+ Holder bootstrap(Registry)
+ Holder register(ResourceKey,Structure)
+ HolderSet biomes(TagKey)
- MobCategory lambda$bootstrap$0(MobCategory)
+ MobCategory lambda$static$0(MobCategory)
- Structure$StructureSettings structure(HolderSet,GenerationStep$Decoration,TerrainAdjustment)
- Structure$StructureSettings structure(HolderSet,Map,GenerationStep$Decoration,TerrainAdjustment)
- Structure$StructureSettings structure(HolderSet,TerrainAdjustment)
+ Structure$StructureSettings structure(TagKey,GenerationStep$Decoration,TerrainAdjustment)
+ Structure$StructureSettings structure(TagKey,Map,GenerationStep$Decoration,TerrainAdjustment)
+ Structure$StructureSettings structure(TagKey,TerrainAdjustment)
- StructureSpawnOverride lambda$bootstrap$1(MobCategory)
+ StructureSpawnOverride lambda$static$1(MobCategory)
+ void <clinit>()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.TaigaVillagePools
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.VillagePools
</summary>

```diff
+ void bootstrap()
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.biome.EndBiomes
</summary>

```diff
+ Biome endBarrens()
- Biome endBarrens(HolderGetter,HolderGetter)
+ Biome endHighlands()
- Biome endHighlands(HolderGetter,HolderGetter)
+ Biome endMidlands()
- Biome endMidlands(HolderGetter,HolderGetter)
+ Biome smallEndIslands()
- Biome smallEndIslands(HolderGetter,HolderGetter)
+ Biome theEnd()
- Biome theEnd(HolderGetter,HolderGetter)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.biome.OverworldBiomes
</summary>

```diff
+ Biome badlands(boolean)
- Biome badlands(HolderGetter,HolderGetter,boolean)
+ Biome bambooJungle()
- Biome bambooJungle(HolderGetter,HolderGetter)
+ Biome baseJungle(float,boolean,boolean,boolean,MobSpawnSettings$Builder)
- Biome baseJungle(HolderGetter,HolderGetter,float,boolean,boolean,boolean,MobSpawnSettings$Builder)
+ Biome beach(boolean,boolean)
- Biome beach(HolderGetter,HolderGetter,boolean,boolean)
+ Biome coldOcean(boolean)
- Biome coldOcean(HolderGetter,HolderGetter,boolean)
+ Biome darkForest()
- Biome darkForest(HolderGetter,HolderGetter)
+ Biome deepDark()
- Biome deepDark(HolderGetter,HolderGetter)
+ Biome desert()
- Biome desert(HolderGetter,HolderGetter)
+ Biome dripstoneCaves()
- Biome dripstoneCaves(HolderGetter,HolderGetter)
+ Biome forest(boolean,boolean,boolean)
- Biome forest(HolderGetter,HolderGetter,boolean,boolean,boolean)
+ Biome frozenOcean(boolean)
- Biome frozenOcean(HolderGetter,HolderGetter,boolean)
+ Biome frozenPeaks()
- Biome frozenPeaks(HolderGetter,HolderGetter)
+ Biome grove()
- Biome grove(HolderGetter,HolderGetter)
+ Biome jaggedPeaks()
- Biome jaggedPeaks(HolderGetter,HolderGetter)
+ Biome jungle()
- Biome jungle(HolderGetter,HolderGetter)
+ Biome lukeWarmOcean(boolean)
- Biome lukeWarmOcean(HolderGetter,HolderGetter,boolean)
+ Biome lushCaves()
- Biome lushCaves(HolderGetter,HolderGetter)
+ Biome mangroveSwamp()
- Biome mangroveSwamp(HolderGetter,HolderGetter)
+ Biome meadow()
- Biome meadow(HolderGetter,HolderGetter)
+ Biome mushroomFields()
- Biome mushroomFields(HolderGetter,HolderGetter)
+ Biome ocean(boolean)
- Biome ocean(HolderGetter,HolderGetter,boolean)
+ Biome oldGrowthTaiga(boolean)
- Biome oldGrowthTaiga(HolderGetter,HolderGetter,boolean)
+ Biome plains(boolean,boolean,boolean)
- Biome plains(HolderGetter,HolderGetter,boolean,boolean,boolean)
+ Biome river(boolean)
- Biome river(HolderGetter,HolderGetter,boolean)
+ Biome savanna(boolean,boolean)
- Biome savanna(HolderGetter,HolderGetter,boolean,boolean)
+ Biome snowySlopes()
- Biome snowySlopes(HolderGetter,HolderGetter)
+ Biome sparseJungle()
- Biome sparseJungle(HolderGetter,HolderGetter)
+ Biome stonyPeaks()
- Biome stonyPeaks(HolderGetter,HolderGetter)
+ Biome swamp()
- Biome swamp(HolderGetter,HolderGetter)
+ Biome taiga(boolean)
- Biome taiga(HolderGetter,HolderGetter,boolean)
+ Biome theVoid()
- Biome theVoid(HolderGetter,HolderGetter)
+ Biome warmOcean()
- Biome warmOcean(HolderGetter,HolderGetter)
+ Biome windsweptHills(boolean)
- Biome windsweptHills(HolderGetter,HolderGetter,boolean)
+ BiomeGenerationSettings$Builder baseOceanGeneration()
- BiomeGenerationSettings$Builder baseOceanGeneration(HolderGetter,HolderGetter)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.AquaticFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.EndFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.MiscOverworldFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.OreFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.TreeFeatures
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>

<details>
<summary>
net.minecraft.data.worldgen.placement.AquaticPlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.EndPlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.NetherPlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.PlacementUtils
</summary>

```diff
+ Holder bootstrap(Registry)
+ Holder register(String,Holder,List)
+ Holder register(String,Holder,PlacementModifier[])
- ResourceKey createKey(String)
- void bootstrap(BootstapContext)
- void register(BootstapContext,ResourceKey,Holder,List)
- void register(BootstapContext,ResourceKey,Holder,PlacementModifier[])
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.VegetationPlacements
</summary>

```diff
- void bootstrap(BootstapContext)
```

</details>











































<details>
<summary>
net.minecraft.nbt.NbtUtils
</summary>

```diff
- BlockState readBlockState(HolderGetter,CompoundTag)
+ BlockState readBlockState(HolderLookup,CompoundTag)
```

</details>




























<details>
<summary>
net.minecraft.network.chat.ChatType
</summary>

```diff
+ Holder bootstrap(Registry)
- void bootstrap(BootstapContext)
```

</details>















































































































































































<details>
<summary>
net.minecraft.resources.HolderSetCodec
</summary>

```diff
- HolderSet lambda$decode$3(HolderGetter,Either)
+ HolderSet lambda$decode$3(Registry,Either)
- Pair lambda$decode$4(HolderGetter,Pair)
+ Pair lambda$decode$4(Registry,Pair)
```

</details>

<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$1
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$11
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$2
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$4
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$6
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs$8
</summary>

```diff
- void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output,boolean)
+ void generateDisplayItems(FeatureFlagSet,CreativeModeTab$Output)
```

</details>






















<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- ItemStack copyWithCount(int)
```

</details>







































































































<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Explosion$BlockInteraction)
- Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Level$ExplosionInteraction,boolean)
- Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Level$ExplosionInteraction)
+ Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,Vec3,float,boolean,Explosion$BlockInteraction)
- Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,Vec3,float,boolean,Level$ExplosionInteraction)
+ Explosion explode(Entity,double,double,double,float,boolean,Explosion$BlockInteraction)
- Explosion explode(Entity,double,double,double,float,boolean,Level$ExplosionInteraction)
+ Explosion explode(Entity,double,double,double,float,Explosion$BlockInteraction)
- Explosion explode(Entity,double,double,double,float,Level$ExplosionInteraction)
- Explosion$BlockInteraction getDestroyType(GameRules$Key)
```

</details>




















<details>
<summary>
net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
</summary>

```diff
+ BiomeGenerationSettings build()
+ BiomeGenerationSettings$Builder addCarver(GenerationStep$Carving,Holder)
- BiomeGenerationSettings$Builder addCarver(GenerationStep$Carving,ResourceKey)
+ BiomeGenerationSettings$Builder addFeature(GenerationStep$Decoration,Holder)
- BiomeGenerationSettings$Builder addFeature(GenerationStep$Decoration,ResourceKey)
+ BiomeGenerationSettings$Builder addFeature(int,Holder)
+ HolderSet lambda$build$1(Map$Entry)
+ List lambda$addCarver$0(GenerationStep$Carving)
+ void <init>()
- void <init>(HolderGetter,HolderGetter)
+ void addFeatureStepsUpTo(int)
```

</details>





































































<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ App lambda$static$1(RecordCodecBuilder$Instance)
+ Registry biomes()
+ Registry lambda$static$0(DebugLevelSource)
- Stream lambda$static$1(Block)
+ Stream lambda$static$2(Block)
- void <init>(Holder$Reference)
+ void <init>(Registry,Registry)
```

</details>




























<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$3(RecordCodecBuilder$Instance)
- Aquifer$FluidPicker lambda$new$3(Holder)
+ Aquifer$FluidPicker lambda$new$4(Holder)
- Aquifer$FluidStatus lambda$createFluidPicker$4(Aquifer$FluidStatus,int,Aquifer$FluidStatus,Aquifer$FluidStatus,int,int,int)
+ Aquifer$FluidStatus lambda$createFluidPicker$5(Aquifer$FluidStatus,int,Aquifer$FluidStatus,Aquifer$FluidStatus,int,int,int)
- BiomeGenerationSettings lambda$applyCarvers$10(ChunkPos,RandomState)
+ BiomeGenerationSettings lambda$applyCarvers$11(ChunkPos,RandomState)
- BiomeSource lambda$static$0(NoiseBasedChunkGenerator)
+ BiomeSource lambda$static$1(NoiseBasedChunkGenerator)
- ChunkAccess lambda$createBiomes$5(Blender,RandomState,StructureManager,ChunkAccess)
+ ChunkAccess lambda$createBiomes$6(Blender,RandomState,StructureManager,ChunkAccess)
- ChunkAccess lambda$fillFromNoise$11(Blender,StructureManager,RandomState,ChunkAccess,int,int)
+ ChunkAccess lambda$fillFromNoise$12(Blender,StructureManager,RandomState,ChunkAccess,int,int)
- CompletableFuture createBiomes(Executor,RandomState,Blender,StructureManager,ChunkAccess)
+ CompletableFuture createBiomes(Registry,Executor,RandomState,Blender,StructureManager,ChunkAccess)
- Holder lambda$applyCarvers$8(RandomState,int,int,int)
+ Holder lambda$applyCarvers$9(RandomState,int,int,int)
- Holder lambda$static$1(NoiseBasedChunkGenerator)
+ Holder lambda$static$2(NoiseBasedChunkGenerator)
+ NoiseChunk lambda$applyCarvers$10(StructureManager,WorldGenRegion,RandomState,ChunkAccess)
- NoiseChunk lambda$applyCarvers$9(StructureManager,WorldGenRegion,RandomState,ChunkAccess)
- NoiseChunk lambda$buildSurface$7(StructureManager,Blender,RandomState,ChunkAccess)
+ NoiseChunk lambda$buildSurface$8(StructureManager,Blender,RandomState,ChunkAccess)
- NoiseChunk lambda$doCreateBiomes$6(StructureManager,Blender,RandomState,ChunkAccess)
+ NoiseChunk lambda$doCreateBiomes$7(StructureManager,Blender,RandomState,ChunkAccess)
- NoiseChunk lambda$doFill$13(StructureManager,Blender,RandomState,ChunkAccess)
+ NoiseChunk lambda$doFill$14(StructureManager,Blender,RandomState,ChunkAccess)
+ Registry lambda$static$0(NoiseBasedChunkGenerator)
- void <init>(BiomeSource,Holder)
+ void <init>(Registry,Registry,BiomeSource,Holder)
- void lambda$fillFromNoise$12(Set,ChunkAccess,Throwable)
+ void lambda$fillFromNoise$13(Set,ChunkAccess,Throwable)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.Noises
</summary>

```diff
- NormalNoise instantiate(HolderGetter,PositionalRandomFactory,ResourceKey)
+ NormalNoise instantiate(Registry,PositionalRandomFactory,ResourceKey)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.RandomState
</summary>

```diff
+ long legacyLevelSeed()
- RandomState create(HolderGetter$Provider,ResourceKey,long)
- RandomState create(NoiseGeneratorSettings,HolderGetter,long)
+ RandomState create(NoiseGeneratorSettings,Registry,long)
+ RandomState create(RegistryAccess,ResourceKey,long)
- void <init>(NoiseGeneratorSettings,HolderGetter,long)
+ void <init>(NoiseGeneratorSettings,Registry,long)
```

</details>



























<details>
<summary>
net.minecraft.world.level.levelgen.WorldOptions
</summary>

```diff
- long parseSeedOrElseRandom(String)
- long randomSeed()
+ OptionalLong parseSeed(String)
- WorldOptions withSeed(long)
+ WorldOptions withSeed(OptionalLong)
```

</details>
















































































































<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
</summary>

```diff
+ Holder bootstrap(Registry)
- void bootstrap(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ App lambda$static$5(RecordCodecBuilder$Instance)
- Boolean lambda$static$1(FlatLevelGeneratorSettings)
+ Boolean lambda$static$3(FlatLevelGeneratorSettings)
- boolean lambda$updateLayers$5(BlockState)
+ boolean lambda$updateLayers$6(BlockState)
- FlatLevelGeneratorSettings getDefault(HolderGetter,HolderGetter,HolderGetter)
+ FlatLevelGeneratorSettings getDefault(Registry,Registry)
- FlatLevelGeneratorSettings withBiomeAndLayers(List,Optional,Holder)
+ FlatLevelGeneratorSettings withLayers(List,Optional)
- Holder getBiome(Optional,Holder)
- Holder getDefaultBiome(HolderGetter)
- List createLakesList(HolderGetter)
- Optional lambda$static$0(FlatLevelGeneratorSettings)
+ Optional lambda$static$1(FlatLevelGeneratorSettings)
- Optional lambda$static$3(FlatLevelGeneratorSettings)
+ Optional lambda$static$4(FlatLevelGeneratorSettings)
+ Registry lambda$static$0(FlatLevelGeneratorSettings)
- void <init>(Optional,Holder,List)
- void <init>(Optional,List,boolean,boolean,Optional,Holder$Reference,Holder,Holder)
+ void <init>(Optional,Registry)
+ void <init>(Registry,Optional,List,boolean,boolean,Optional)
+ void setBiome(Holder)
```

</details>



















<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
</summary>

```diff
+ Holder registerCustomOverworldPreset(ResourceKey,LevelStem)
+ Holder run()
- void <init>(BootstapContext)
+ void <init>(Registry)
- void registerCustomOverworldPreset(ResourceKey,LevelStem)
- void run()
```

</details>





















<details>
<summary>
net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
</summary>

```diff
+ boolean isPlacementChunk(ChunkGenerator,RandomState,long,int,int)
- boolean isPlacementChunk(ChunkGeneratorStructureState,int,int)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
</summary>

```diff
+ boolean isPlacementForbidden(ChunkGenerator,RandomState,long,int,int)
- boolean isPlacementForbidden(ChunkGeneratorStructureState,int,int)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
</summary>

```diff
- Holder lambda$tryPlacingChildren$1(Holder)
+ int lambda$tryPlacingChildren$3(BoundingBox,StructureTemplate$StructureBlockInfo)
- int lambda$tryPlacingChildren$4(BoundingBox,StructureTemplate$StructureBlockInfo)
+ Integer lambda$tryPlacingChildren$1(StructureTemplatePool)
- Integer lambda$tryPlacingChildren$2(Holder)
+ Integer lambda$tryPlacingChildren$2(StructureTemplatePool)
- Integer lambda$tryPlacingChildren$3(Holder)
+ Optional lambda$tryPlacingChildren$0(StructureTemplatePool)
- ResourceKey readPoolName(StructureTemplate$StructureBlockInfo)
- String lambda$tryPlacingChildren$0(ResourceKey)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
</summary>

```diff
- Holder getFallback()
+ ResourceLocation getFallback()
+ ResourceLocation getName()
- void <init>(Holder,List,StructureTemplatePool$Projection)
- void <init>(Holder,List)
+ void <init>(ResourceLocation,ResourceLocation,List,StructureTemplatePool$Projection)
+ void <init>(ResourceLocation,ResourceLocation,List)
```

</details>














































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
</summary>

```diff
- void load(HolderGetter,CompoundTag)
+ void load(HolderLookup,CompoundTag)
- void loadPalette(HolderGetter,ListTag,ListTag)
+ void loadPalette(HolderLookup,ListTag,ListTag)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
</summary>

```diff
- void <init>(ResourceManager,LevelStorageSource$LevelStorageAccess,DataFixer,HolderGetter)
+ void <init>(ResourceManager,LevelStorageSource$LevelStorageAccess,DataFixer,HolderLookup)
```

</details>

















<details>
<summary>
net.minecraft.world.level.material.FlowingFluid
</summary>

```diff
- boolean lambda$getSpread$4(Level,BlockPos,BlockPos,BlockState,short)
+ boolean lambda$getSpread$4(LevelReader,BlockPos,BlockPos,BlockState,short)
- FluidState getNewLiquid(Level,BlockPos,BlockState)
+ FluidState getNewLiquid(LevelReader,BlockPos,BlockState)
- Map getSpread(Level,BlockPos,BlockState)
+ Map getSpread(LevelReader,BlockPos,BlockState)
- Pair lambda$getSpread$3(Level,BlockPos,short)
+ Pair lambda$getSpread$3(LevelReader,BlockPos,short)
- void spread(Level,BlockPos,FluidState)
+ void spread(LevelAccessor,BlockPos,FluidState)
- void spreadToSides(Level,BlockPos,FluidState,BlockState)
+ void spreadToSides(LevelAccessor,BlockPos,FluidState,BlockState)
```

</details>


<details>
<summary>
net.minecraft.world.level.material.LavaFluid
</summary>

```diff
+ boolean canConvertToSource()
- boolean canConvertToSource(Level)
```

</details>



<details>
<summary>
net.minecraft.world.level.material.WaterFluid
</summary>

```diff
+ boolean canConvertToSource()
- boolean canConvertToSource(Level)
```

</details>




<details>
<summary>
net.minecraft.world.level.pathfinder.NodeEvaluator
</summary>

```diff
- boolean canWalkOverFences()
- void setCanWalkOverFences(boolean)
```

</details>


<details>
<summary>
net.minecraft.world.level.pathfinder.WalkNodeEvaluator
</summary>

```diff
- double getMobJumpHeight()
```

</details>
</details>