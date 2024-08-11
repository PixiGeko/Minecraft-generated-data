## Comparison with [20w16a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w16a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
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
<table><tr><th></th><th align="left">20w16a</th><th>20w17a</th></tr><tr><td>World version</td><td><code>2526</code></td><td><code>2529</code></td></tr><tr><td>Protocol version</td><td><code>712</code></td><td><code>713</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ feature_size_type.txt
```

</details>




<details>
<summary>
block.txt
</summary>

```diff
- minecraft:soul_fire_lantern
- minecraft:soul_fire_torch
- minecraft:soul_fire_wall_torch
+ minecraft:soul_lantern
+ minecraft:soul_torch
+ minecraft:soul_wall_torch
```

</details>











<details>
<summary>
feature.txt
</summary>

```diff
- minecraft:dark_oak_tree
- minecraft:fancy_tree
- minecraft:jungle_ground_bush
- minecraft:mega_jungle_tree
- minecraft:mega_spruce_tree
- minecraft:normal_tree
+ minecraft:tree
```

</details>

<details>
<summary>
foliage_placer_type.txt
</summary>

```diff
+ minecraft:bush_foliage_placer
+ minecraft:dark_oak_foliage_placer
+ minecraft:fancy_foliage_placer
+ minecraft:jungle_foliage_placer
+ minecraft:mega_pine_foliage_placer
```

</details>
<details>
<summary>
item.txt
</summary>

```diff
- minecraft:soul_fire_lantern
- minecraft:soul_fire_torch
+ minecraft:soul_lantern
+ minecraft:soul_torch
```

</details>













<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.chain.break
+ minecraft:block.chain.fall
+ minecraft:block.chain.hit
+ minecraft:block.chain.place
+ minecraft:block.chain.step
+ minecraft:block.gilded_blackstone.break
+ minecraft:block.gilded_blackstone.fall
+ minecraft:block.gilded_blackstone.hit
+ minecraft:block.gilded_blackstone.place
+ minecraft:block.gilded_blackstone.step
+ minecraft:block.nether_gold_ore.break
+ minecraft:block.nether_gold_ore.fall
+ minecraft:block.nether_gold_ore.hit
+ minecraft:block.nether_gold_ore.place
+ minecraft:block.nether_gold_ore.step
```

</details>







<details>
<summary>
trunk_placer_type.txt
</summary>

```diff
+ minecraft:dark_oak_trunk_placer
+ minecraft:fancy_trunk_placer
+ minecraft:giant_trunk_placer
+ minecraft:mega_jungle_trunk_placer
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/feature_size_type.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
- minecraft:soul_fire_wall_torch
+ minecraft:soul_wall_torch
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
- minecraft:soul_fire_lantern
- minecraft:soul_fire_torch
+ minecraft:soul_lantern
+ minecraft:soul_torch
```

</details>








<details>
<summary>
universal_tags/block.json
</summary>

```diff
- minecraft:soul_fire_lantern
- minecraft:soul_fire_torch
- minecraft:soul_fire_wall_torch
+ minecraft:soul_lantern
+ minecraft:soul_torch
+ minecraft:soul_wall_torch
```

</details>











<details>
<summary>
universal_tags/feature.json
</summary>

```diff
- minecraft:dark_oak_tree
- minecraft:fancy_tree
- minecraft:jungle_ground_bush
- minecraft:mega_jungle_tree
- minecraft:mega_spruce_tree
- minecraft:normal_tree
+ minecraft:tree
```

</details>

<details>
<summary>
universal_tags/foliage_placer_type.json
</summary>

```diff
+ minecraft:bush_foliage_placer
+ minecraft:dark_oak_foliage_placer
+ minecraft:fancy_foliage_placer
+ minecraft:jungle_foliage_placer
+ minecraft:mega_pine_foliage_placer
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:soul_fire_lantern
- minecraft:soul_fire_torch
+ minecraft:soul_lantern
+ minecraft:soul_torch
```

</details>













<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.chain.break
+ minecraft:block.chain.fall
+ minecraft:block.chain.hit
+ minecraft:block.chain.place
+ minecraft:block.chain.step
+ minecraft:block.gilded_blackstone.break
+ minecraft:block.gilded_blackstone.fall
+ minecraft:block.gilded_blackstone.hit
+ minecraft:block.gilded_blackstone.place
+ minecraft:block.gilded_blackstone.step
+ minecraft:block.nether_gold_ore.break
+ minecraft:block.nether_gold_ore.fall
+ minecraft:block.nether_gold_ore.hit
+ minecraft:block.nether_gold_ore.place
+ minecraft:block.nether_gold_ore.step
```

</details>







<details>
<summary>
universal_tags/trunk_placer_type.json
</summary>

```diff
+ minecraft:dark_oak_trunk_placer
+ minecraft:fancy_trunk_placer
+ minecraft:giant_trunk_placer
+ minecraft:mega_jungle_trunk_placer
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ attribute.json
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
- soul_fire_lantern.json
- soul_fire_torch.json
+ soul_lantern.json
+ soul_torch.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ argument.uuid.invalid: Invalid UUID
+ attribute.unknown: Unknown attribute
- block.minecraft.soul_fire_lantern: Soul Fire Lantern
- block.minecraft.soul_fire_torch: Soul Fire Torch
- block.minecraft.soul_fire_wall_torch: Soul Fire Wall Torch
+ block.minecraft.soul_lantern: Soul Lantern
+ block.minecraft.soul_torch: Soul Torch
+ block.minecraft.soul_wall_torch: Soul Wall Torch
+ commands.attribute.base_value.get.success: Base value of attribute %s for entity %s is %s
+ commands.attribute.base_value.set.success: Base value for attribute %s for entity %s set to %s
+ commands.attribute.failed.entity: %s is not a valid entity for this command
+ commands.attribute.failed.modifier_already_present: Modifier %s is already present on attribute %s for entity %s
+ commands.attribute.failed.no_attribute: Entity %s has no attribute %s
+ commands.attribute.failed.no_modifier: Attribute %s for entity %s has no modifier %s
+ commands.attribute.modifier.add.success: Added modifier %s to attribute %s for entity %s
+ commands.attribute.modifier.remove.success: Removed modifier %s from attribute %s for entity %s
+ commands.attribute.modifier.value.get.success: Value of modifier %s on attribute %s for entity %s is %s
+ commands.attribute.value.get.success: Value of attribute %s for entity %s is %s
+ editGamerule.default: Default: %s
+ editGamerule.title: Edit game rules
+ gamerule.announceAdvancements: Announce advancements
+ gamerule.category.chat: Chat
+ gamerule.category.drops: Drops
+ gamerule.category.misc: Miscellaneous
+ gamerule.category.mobs: Mobs
+ gamerule.category.player: Player
+ gamerule.category.spawning: Spawning
+ gamerule.category.updates: World updates
+ gamerule.commandBlockOutput: Broadcast command block output
+ gamerule.disableElytraMovementCheck: Disable Elytra movement check
+ gamerule.disableRaids: Disable raids
+ gamerule.doDaylightCycle: Advance in-game time
+ gamerule.doEntityDrops: Drop entity equipment
+ gamerule.doEntityDrops.description: Controls drops from minecarts (including inventories), item frames, boats, etc.
+ gamerule.doFireTick: Update fire
+ gamerule.doImmediateRespawn: Respawn immediately
+ gamerule.doInsomnia: Spawn phantoms
+ gamerule.doLimitedCrafting: Require recipe for crafting
+ gamerule.doLimitedCrafting.description: If enabled, players will be able to craft only unlocked recipes
+ gamerule.doMobLoot: Drop mob loot
+ gamerule.doMobLoot.description: Controls resource drops, including experience orbs
+ gamerule.doMobSpawning: Spawn mobs
+ gamerule.doMobSpawning.description: Some entities might have separate rules
+ gamerule.doPatrolSpawning: Spawn pillager patrols
+ gamerule.doTileDrops: Drop blocks
+ gamerule.doTileDrops.description: Controls resource drops, including experience orbs
+ gamerule.doTraderSpawning: Spawn wandering traders
+ gamerule.doWeatherCycle: Update weather
+ gamerule.drowningDamage: Deal drowning damage
+ gamerule.fallDamage: Deal fall damage
+ gamerule.fireDamage: Deal fire damage
+ gamerule.keepInventory: Keep inventory after death
+ gamerule.logAdminCommands: Broadcast admin commands
+ gamerule.maxCommandChainLength: Command chain size limit
+ gamerule.maxCommandChainLength.description: Applies to command block chains and functions
+ gamerule.maxEntityCramming: Entity cramming threshold
+ gamerule.mobGriefing: Allow destructive mob actions
+ gamerule.naturalRegeneration: Regenerate health
+ gamerule.randomTickSpeed: Random tick speed rate
+ gamerule.reducedDebugInfo: Reduce debug info
+ gamerule.reducedDebugInfo.description: Limits contents of debug screen
+ gamerule.sendCommandFeedback: Send command feedback
+ gamerule.showDeathMessages: Show death messages
+ gamerule.spawnRadius: Respawn location radius
+ gamerule.spectatorsGenerateChunks: Allow spectators to generate terrain
+ gui.entity_tooltip.type: Type: %s
+ multiplayer.status.ping: %s ms
+ options.entityDistancePercent: %s%%
+ options.entityDistanceScaling: Entity Distance
+ selectWorld.gameRules: Game rules
```

</details>
<details>
<summary>
Changes
</summary>

```
container.upgrade: Upgrade gear
jigsaw_block.levels: Levels: %s
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
- minecraft/advancements/recipes/building_blocks/blackstone_wall_from_blackstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/blackstone_wall.json
- minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_wall_from_blackstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_wall_from_polished_blackstone_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_wall_from_polished_blackstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_wall.json
- minecraft/advancements/recipes/building_blocks/polished_blackstone_wall_from_blackstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/polished_blackstone_wall_from_polished_blackstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/polished_blackstone_wall.json
+ minecraft/advancements/recipes/decorations/blackstone_wall_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/decorations/blackstone_wall.json
+ minecraft/advancements/recipes/decorations/polished_blackstone_brick_wall_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/decorations/polished_blackstone_brick_wall_from_polished_blackstone_bricks_stonecutting.json
+ minecraft/advancements/recipes/decorations/polished_blackstone_brick_wall_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/decorations/polished_blackstone_brick_wall.json
+ minecraft/advancements/recipes/decorations/polished_blackstone_wall_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/decorations/polished_blackstone_wall_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/decorations/polished_blackstone_wall.json
- minecraft/advancements/recipes/decorations/soul_fire_lantern.json
- minecraft/advancements/recipes/decorations/soul_fire_torch.json
+ minecraft/advancements/recipes/decorations/soul_lantern.json
+ minecraft/advancements/recipes/decorations/soul_torch.json
- minecraft/loot_tables/blocks/soul_fire_lantern.json
- minecraft/loot_tables/blocks/soul_fire_torch.json
+ minecraft/loot_tables/blocks/soul_lantern.json
+ minecraft/loot_tables/blocks/soul_torch.json
- minecraft/recipes/soul_fire_lantern.json
- minecraft/recipes/soul_fire_torch.json
+ minecraft/recipes/soul_lantern.json
+ minecraft/recipes/soul_torch.json
+ minecraft/tags/blocks/pressure_plates.json
+ minecraft/tags/blocks/stone_pressure_plates.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/soul_fire_lantern.json
- minecraft/blockstates/soul_fire_torch.json
- minecraft/blockstates/soul_fire_wall_torch.json
+ minecraft/blockstates/soul_lantern.json
+ minecraft/blockstates/soul_torch.json
+ minecraft/blockstates/soul_wall_torch.json
+ minecraft/font/uniform.json
- minecraft/models/block/soul_fire_lantern_hanging.json
- minecraft/models/block/soul_fire_lantern.json
- minecraft/models/block/soul_fire_torch.json
- minecraft/models/block/soul_fire_wall_torch.json
+ minecraft/models/block/soul_lantern_hanging.json
+ minecraft/models/block/soul_lantern.json
+ minecraft/models/block/soul_torch.json
+ minecraft/models/block/soul_wall_torch.json
- minecraft/models/item/soul_fire_lantern.json
- minecraft/models/item/soul_fire_torch.json
+ minecraft/models/item/soul_lantern.json
+ minecraft/models/item/soul_torch.json
- minecraft/textures/block/soul_fire_lantern.png
- minecraft/textures/block/soul_fire_lantern.png.mcmeta
- minecraft/textures/block/soul_fire_torch.png
+ minecraft/textures/block/soul_lantern.png
+ minecraft/textures/block/soul_lantern.png.mcmeta
+ minecraft/textures/block/soul_torch.png
- minecraft/textures/item/soul_fire_lantern.png
+ minecraft/textures/item/soul_lantern.png
```

</details>
</details>
<details><summary>Misc</summary>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:uuid
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
+ net.minecraft.commands.arguments.package-info
- net.minecraft.commands.arguments.selector.EntitySelector
+ net.minecraft.commands.arguments.selector.EntitySelectorParser
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
- net.minecraft.commands.arguments.selector.options.package-info
+ net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.UuidArgument
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
+ net.minecraft.data.tags.TagsProvider$1
- net.minecraft.data.tags.TagsProvider$TagAppender
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
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.ContextAwareComponent
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.package-info
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
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquippedItemPacket
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
- net.minecraft.network.protocol.game.ClientGamePacketListener
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
+ net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
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
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
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
- net.minecraft.network.SkipPacketException
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
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
+ net.minecraft.obfuscate.DontObfuscateOrShrink
- net.minecraft.obfuscate.KeepAfterObfuscation
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
- net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ net.minecraft.resources.package-info
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$Mode
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
- net.minecraft.server.commands.ReplaceItemCommand
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
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServer$2
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
- net.minecraft.server.level.DerivedServerLevel
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FeatureSimulator
- net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$1
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.WorldGenRegion
+ net.minecraft.server.level.WorldGenTickList
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
+ net.minecraft.server.network.ServerConnectionListener
- net.minecraft.server.network.ServerConnectionListener$1
+ net.minecraft.server.network.ServerConnectionListener$2
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractResourcePack
- net.minecraft.server.packs.FileResourcePack
+ net.minecraft.server.packs.FolderResourcePack
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
- net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.Pack
+ net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackType
- net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.RepositorySource
- net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.repository.UnopenedPack
- net.minecraft.server.packs.repository.UnopenedPack$Position
+ net.minecraft.server.packs.repository.UnopenedPack$UnopenedPackConstructor
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
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
- net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
+ net.minecraft.server.packs.resources.SimpleReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadInstance$1
+ net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
+ net.minecraft.server.packs.resources.SimpleResource
+ net.minecraft.server.packs.VanillaPack
+ net.minecraft.server.players.BanListEntry
- net.minecraft.server.players.GameProfileCache
+ net.minecraft.server.players.GameProfileCache$1
- net.minecraft.server.players.GameProfileCache$2
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.GameProfileCache$Serializer
+ net.minecraft.server.players.IpBanList
- net.minecraft.server.players.IpBanListEntry
+ net.minecraft.server.players.OldUsersConverter
- net.minecraft.server.players.OldUsersConverter$1
+ net.minecraft.server.players.OldUsersConverter$2
- net.minecraft.server.players.OldUsersConverter$3
+ net.minecraft.server.players.OldUsersConverter$4
- net.minecraft.server.players.OldUsersConverter$5
+ net.minecraft.server.players.OldUsersConverter$ConversionError
- net.minecraft.server.players.package-info
- net.minecraft.server.players.PlayerList
+ net.minecraft.server.players.PlayerList$1
- net.minecraft.server.players.ServerOpList
+ net.minecraft.server.players.ServerOpListEntry
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
- net.minecraft.sounds.Musics
- net.minecraft.sounds.package-info
+ net.minecraft.sounds.SoundEvent
- net.minecraft.sounds.SoundEvents
+ net.minecraft.sounds.SoundSource
+ net.minecraft.stats.package-info
+ net.minecraft.stats.RecipeBook
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
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
- net.minecraft.tags.StaticTagHelper
+ net.minecraft.tags.StaticTagHelper$1
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.SynchronizableTagCollection
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$1
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$BuilderEntry
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$Named
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.TagCollection
+ net.minecraft.tags.TagManager
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
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.OminousBannerRenameFix
- net.minecraft.util.Deserializer
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.FrameTimer
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InsensitiveStringMap
- net.minecraft.util.IntRange
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LimitedCapacityList
+ net.minecraft.util.LinearCongruentialGenerator
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- net.minecraft.util.Mth
+ net.minecraft.util.ProgressListener
- net.minecraft.util.RewindableStream
+ net.minecraft.util.RewindableStream$1
- net.minecraft.util.Serializable
+ net.minecraft.util.Serializer
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
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkBiomeContainer
- net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkGeneratorFactory
- net.minecraft.world.level.chunk.ChunkGeneratorType
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.ChunkStatus
+ net.minecraft.world.level.chunk.ChunkStatus$ChunkType
- net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
+ net.minecraft.world.level.chunk.FeatureAccess
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
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
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$1
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.OldChunkStorage
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
+ net.minecraft.world.level.dimension.Dimension
- net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.end.TheEndDimension
+ net.minecraft.world.level.dimension.NetherDimension
- net.minecraft.world.level.dimension.NetherDimension$1
+ net.minecraft.world.level.dimension.NormalDimension
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.ChunkGeneratorProvider
+ net.minecraft.world.level.levelgen.ChunkGeneratorSettings
- net.minecraft.world.level.levelgen.DebugGeneratorSettings
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.AbstractTreeFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BastionBridgePools
- net.minecraft.world.level.levelgen.feature.BastionFeature
+ net.minecraft.world.level.levelgen.feature.BastionFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.BastionHoglinStablePools
+ net.minecraft.world.level.levelgen.feature.BastionHousingUnitsPools
- net.minecraft.world.level.levelgen.feature.BastionPieces
+ net.minecraft.world.level.levelgen.feature.BastionPieces$BastionPiece
- net.minecraft.world.level.levelgen.feature.BastionSharedPools
+ net.minecraft.world.level.levelgen.feature.BastionTreasureRoomPools
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.FancyTreeFeature
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.GroundBushFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IcePatchFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
+ net.minecraft.world.level.levelgen.feature.MegaTreeFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
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
- net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.FlatLevelSource
+ net.minecraft.world.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- net.minecraft.world.level.levelgen.GenerationStep
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.NetherGeneratorSettings
+ net.minecraft.world.level.levelgen.NetherLevelSource
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.OverworldGeneratorSettings
- net.minecraft.world.level.levelgen.OverworldLevelSource
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.synth.SurfaceNoise
+ net.minecraft.world.level.levelgen.TheEndGeneratorSettings
- net.minecraft.world.level.levelgen.TheEndLevelSource
+ net.minecraft.world.level.levelgen.WorldgenRandom
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
+ net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FluidStateImpl
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
+ net.minecraft.world.level.newbiome.layer.Layers
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
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SaveDataDirtyRunnable
+ net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelStorage
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.ConstantIntValue
- net.minecraft.world.level.storage.loot.ConstantIntValue$Serializer
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$Serializer
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
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
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
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$DataSource
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
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions$Serializer
+ net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
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
+ net.minecraft.world.level.storage.loot.IntLimiter
- net.minecraft.world.level.storage.loot.IntLimiter$1
+ net.minecraft.world.level.storage.loot.IntLimiter$Serializer
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
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.PredicateManager
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
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
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions$Serializer
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
- net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
+ net.minecraft.world.level.storage.loot.RandomIntGenerator
- net.minecraft.world.level.storage.loot.RandomIntGenerators
+ net.minecraft.world.level.storage.loot.RandomValueBounds
- net.minecraft.world.level.storage.loot.RandomValueBounds$Serializer
+ net.minecraft.world.level.storage.loot.ValidationContext
- net.minecraft.world.level.storage.McRegionUpgrader
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerIO
- net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.storage.threaded.package-info
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
+ net.minecraft.world.phys.package-info
- net.minecraft.world.phys.PosAndRot
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
+ net.minecraft.world.phys.shapes.IntPointRange
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
- net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.phys.shapes.WorldRegionIndirectVoxelShape
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
net.minecraft.SharedConstants -1M
```
```
XXX.network.chat.Component +9M -10M | +3P -4P
```
```
XXX.network.chat.Component$Serializer +5M -5M
```
```
XXX.network.chat.NbtComponent +2M -3M
```
```
XXX.network.chat.NbtComponent$EntityNbtComponent +3M -1M
```
```
XXX.network.chat.ScoreComponent +8M -7M | -1P
```
```
XXX.network.chat.Style +26M -31M | +4P -3P
```
```
XXX.network.chat.Style$Serializer +6M
```
```
XXX.minecraft.server.MinecraftServer +26M -27M | +3P -11P
```
```
XXX.server.bossevents.CustomBossEvent +1M -1M
```
```
XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1 +1M -1M
```
```
XXX.minecraft.world.Difficulty +1M
```
```
XXX.world.damagesource.BadRespawnPointDamage +1M -1M
```
```
XXX.world.entity.Entity +5M -5M
```
```
XXX.world.entity.EntityType$Builder +2M | +2P
```
```
XXX.world.entity.HumanoidArm +1M
```
```
XXX.ai.attributes.AttributeInstance +1M
```
```
XXX.ai.attributes.AttributeSupplier +3M
```
```
XXX.entity.animal.Rabbit +1M -1M
```
```
XXX.entity.item.ItemEntity +2M
```
```
XXX.world.item.BannerPatternItem +1M -1M
```
```
XXX.world.item.CompassItem +4M -4M
```
```
XXX.world.item.CompassItem$CompassWobble +5M -6M
```
```
XXX.world.item.FireworkStarItem +1M -1M
```
```
XXX.world.item.Items +2P -2P
```
```
XXX.world.level.LevelType +2M -2M | +2P
```
```
XXX.level.biome.Biome$ClimateParameters +1P -1P
```
```
XXX.level.biome.BiomeManager +1M
```
```
XXX.level.biome.MultiNoiseBiomeSourceSettings +7M -2M | +2P -1P
```
```
XXX.level.block.BedBlock +1M
```
```
XXX.level.block.ChainBlock +1M
```
```
XXX.level.block.EndRodBlock +1M
```
```
XXX.level.block.FlowerPotBlock +1M
```
```
XXX.level.block.SeaPickleBlock +1M
```
```
XXX.level.block.SoundType +3P
```
```
XXX.block.entity.SignBlockEntity +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.Feature +3M | +1P -6P
```
```
XXX.feature.configurations.TreeConfiguration +2M -1M | +6P -1P
```
```
XXX.feature.trunkplacers.ForkingTrunkPlacer +1M -1M
```
```
XXX.feature.trunkplacers.TrunkPlacer +7M -2M | +1P -1P
```

</details>











<details>
<summary>
net.minecraft.SharedConstants
</summary>

```diff
+ String filterUnicodeSupplementary(String)
```

</details>










































































































<details>
<summary>
net.minecraft.network.chat.Component
</summary>

```diff
+ Component append(String)
+ Component deepCopy()
+ Component flattenStyle(Component)
+ Component withStyle(ChatFormatting)
+ Component withStyle(ChatFormatting[])
+ Component withStyle(Consumer)
+ Iterator iterator()
- List toFlatList(Style)
- Optional lambda$getString$0(StringBuilder,String)
- Optional lambda$getString$1(int,StringBuilder,String)
- Optional lambda$toFlatList$2(List,Style,String)
- Optional visit(Component$ContentConsumer)
- Optional visit(Component$StyledContentConsumer,Style)
- Optional visitSelf(Component$ContentConsumer)
- Optional visitSelf(Component$StyledContentConsumer,Style)
+ Stream flatStream()
+ String getColoredString()
- void <clinit>()
+ void lambda$getString$0(StringBuilder,Component)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Component$Serializer
</summary>

```diff
+ Component deserialize(JsonElement,Type,JsonDeserializationContext)
+ Component fromJson(JsonElement)
+ Component fromJson(String)
+ Component fromJson(StringReader)
+ Component fromJsonLenient(String)
- MutableComponent deserialize(JsonElement,Type,JsonDeserializationContext)
- MutableComponent fromJson(JsonElement)
- MutableComponent fromJson(String)
- MutableComponent fromJson(StringReader)
- MutableComponent fromJsonLenient(String)
```

</details>
<details>
<summary>
net.minecraft.network.chat.NbtComponent
</summary>

```diff
+ Component lambda$resolve$2(Component,Component)
+ Component resolve(CommandSourceStack,Entity,int)
- MutableComponent lambda$resolve$2(MutableComponent,MutableComponent)
- MutableComponent resolve(CommandSourceStack,Entity,int)
+ String getContents()
```

</details>
<details>
<summary>
net.minecraft.network.chat.NbtComponent$EntityNbtComponent
</summary>

```diff
- BaseComponent toMutable()
+ Component copy()
- MutableComponent toMutable()
- NbtComponent$EntityNbtComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.ScoreComponent
</summary>

```diff
- BaseComponent toMutable()
+ Component copy()
+ Component resolve(CommandSourceStack,Entity,int)
- EntitySelector parseSelector(String)
- MutableComponent resolve(CommandSourceStack,Entity,int)
- MutableComponent toMutable()
+ ScoreComponent copy()
- ScoreComponent toMutable()
- String findTargetName(CommandSourceStack)
+ String getContents()
+ String getEntityName(CommandSourceStack)
- String getScore(String,CommandSourceStack)
- void <init>(String,EntitySelector,String)
+ void resolve(CommandSourceStack)
+ void setValue(String)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Style
</summary>

```diff
+ Boolean access$000(Style)
+ Boolean access$002(Style,Boolean)
+ Boolean access$102(Style,Boolean)
+ Boolean access$202(Style,Boolean)
+ Boolean access$302(Style,Boolean)
+ Boolean access$402(Style,Boolean)
- Boolean access$500(Style)
+ ChatFormatting access$500(Style)
+ ChatFormatting access$502(Style,ChatFormatting)
+ ChatFormatting getColor()
+ ClickEvent access$700(Style)
+ ClickEvent access$702(Style,ClickEvent)
- ClickEvent access$800(Style)
+ HoverEvent access$800(Style)
+ HoverEvent access$802(Style,HoverEvent)
- HoverEvent access$900(Style)
- ResourceLocation access$1000(Style)
- ResourceLocation getFont()
+ String access$600(Style)
+ String access$602(Style,String)
- String access$700(Style)
+ String getLegacyFormatCodes()
+ String toStringResolved()
- Style applyFormat(ChatFormatting)
- Style applyFormats(ChatFormatting[])
- Style applyLegacyFormat(ChatFormatting)
- Style applyTo(Style)
+ Style copy()
+ Style flatCopy()
+ Style getParent()
+ Style inheritFrom(Style)
+ Style setBold(Boolean)
+ Style setClickEvent(ClickEvent)
+ Style setColor(ChatFormatting)
+ Style setHoverEvent(HoverEvent)
+ Style setInsertion(String)
+ Style setItalic(Boolean)
+ Style setObfuscated(Boolean)
+ Style setStrikethrough(Boolean)
+ Style setUnderlined(Boolean)
- Style withBold(Boolean)
- Style withClickEvent(ClickEvent)
- Style withColor(ChatFormatting)
- Style withColor(int)
- Style withColor(TextColor)
- Style withFont(ResourceLocation)
- Style withHoverEvent(HoverEvent)
- Style withInsertion(String)
- Style withItalic(Boolean)
- Style withObfuscated(Boolean)
- Style withStrikethrough(Boolean)
- Style withUnderlined(Boolean)
- TextColor access$600(Style)
- TextColor getColor()
+ void <init>()
- void <init>(TextColor,Boolean,Boolean,Boolean,Boolean,Boolean,ClickEvent,HoverEvent,String,ResourceLocation,Style$1)
- void <init>(TextColor,Boolean,Boolean,Boolean,Boolean,Boolean,ClickEvent,HoverEvent,String,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Style$Serializer
</summary>

```diff
- Boolean getOptionalFlag(JsonObject,String)
- ClickEvent getClickEvent(JsonObject)
- HoverEvent getHoverEvent(JsonObject)
- ResourceLocation getFont(JsonObject)
- String getInsertion(JsonObject)
- TextColor getTextColor(JsonObject)
```

</details>




<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- boolean areNpcsEnabled()
+ boolean getSpawnMonsters()
+ boolean isAnimals()
- boolean isHardcore()
+ boolean isNpcsEnabled()
- boolean isSpawningAnimals()
- boolean isSpawningMonsters()
- boolean lambda$main$4()
+ Component getStartupState()
- GameType getDefaultGameType()
- LevelSettings createLevelSettings(DedicatedServerProperties)
+ Path getWorldPath()
- Path getWorldPath(LevelResource)
+ String getLevelName()
+ String lambda$fillReport$4()
- String lambda$fillReport$7()
- StructureManager getStructureManager()
+ UnopenedPack lambda$updateSelectedPacks$7(UnopenedPack)
- UnopenedPack lambda$updateSelectedPacks$8(UnopenedPack)
+ void <init>(LevelStorageSource$LevelStorageAccess,Proxy,DataFixer,Commands,MinecraftSessionService,GameProfileRepository,GameProfileCache,ChunkProgressListenerFactory)
- void <init>(LevelStorageSource$LevelStorageAccess,WorldData,Proxy,DataFixer,Commands,MinecraftSessionService,GameProfileRepository,GameProfileCache,ChunkProgressListenerFactory)
- void createLevels(ChunkProgressListener)
+ void createLevels(LevelStorage,LevelData,LevelSettings,ChunkProgressListener)
- void detectBundledResources()
+ void detectBundledResources(String,LevelStorage)
+ void ensureLevelConversion()
- void ensureLevelConversion(LevelStorageSource$LevelStorageAccess,DataFixer,boolean,boolean,BooleanSupplier)
+ void eraseCache(boolean)
- void forceDifficulty()
+ void forceUpgrade(boolean)
+ void lambda$updateSelectedPacks$10(LevelData,UnopenedPack)
- void lambda$updateSelectedPacks$10(UnopenedPack)
- void lambda$updateSelectedPacks$11(UnopenedPack)
+ void lambda$updateSelectedPacks$8(List,UnopenedPack)
+ void lambda$updateSelectedPacks$9(LevelData,UnopenedPack)
- void lambda$updateSelectedPacks$9(List,UnopenedPack)
- void loadDataPacks()
+ void loadDataPacks(File,LevelData)
- void loadLevel()
+ void loadLevel(String,long,ChunkGeneratorProvider)
+ void setAnimals(boolean)
+ void setBonusChest(boolean)
+ void setDefaultGameMode(GameType)
- void setDefaultGameType(GameType)
+ void setLevelName(String)
+ void setNpcsEnabled(boolean)
+ void setServerStartupState(Component)
+ void setupDebugLevel(LevelData)
- void setupDebugLevel(WorldData)
- void updateMobSpawningFlags()
- void updateSelectedPacks()
+ void updateSelectedPacks(LevelData)
- WorldData getWorldData()
```

</details>






<details>
<summary>
net.minecraft.server.bossevents.CustomBossEvent
</summary>

```diff
- Style lambda$getDisplayName$0(Style)
+ void lambda$getDisplayName$0(Style)
```

</details>








<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
</summary>

```diff
+ Component deserialize(JsonElement,Type,JsonDeserializationContext)
- MutableComponent deserialize(JsonElement,Type,JsonDeserializationContext)
```

</details>














































































































<details>
<summary>
net.minecraft.world.Difficulty
</summary>

```diff
- Difficulty nextById()
```

</details>







<details>
<summary>
net.minecraft.world.damagesource.BadRespawnPointDamage
</summary>

```diff
- Style lambda$getLocalizedDeathMessage$0(Style)
+ void lambda$getLocalizedDeathMessage$0(Style)
```

</details>










<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean canSpawnSprintParticle()
- Component removeAction(Component)
- Style lambda$getDisplayName$6(Style)
- Style lambda$removeAction$1(Style)
+ void doSprintParticleEffect()
+ void lambda$getDisplayName$6(Style)
+ void lambda$removeAction$1(Style)
+ void removeAction(Component)
- void spawnSprintParticle()
+ void updateSprintingState()
```

</details>



<details>
<summary>
net.minecraft.world.entity.EntityType$Builder
</summary>

```diff
- EntityType$Builder clientTrackingRange(int)
- EntityType$Builder updateInterval(int)
```

</details>


<details>
<summary>
net.minecraft.world.entity.HumanoidArm
</summary>

```diff
- Component getName()
```

</details>













<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeInstance
</summary>

```diff
- boolean removePermanentModifier(UUID)
```

</details>

<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeSupplier
</summary>

```diff
- boolean hasAttribute(Attribute)
- boolean hasModifier(Attribute,UUID)
- double getModifierValue(Attribute,UUID)
```

</details>
































































































































































<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
- boolean canSpawnSprintParticle()
+ void updateSprintingState()
```

</details>















































<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
- float getSpin(float)
- void onSyncedDataUpdated(EntityDataAccessor)
```

</details>









































































































































































<details>
<summary>
net.minecraft.world.item.BannerPatternItem
</summary>

```diff
+ Component getDisplayName()
- MutableComponent getDisplayName()
```

</details>






<details>
<summary>
net.minecraft.world.item.CompassItem
</summary>

```diff
+ boolean access$100(CompoundTag)
- boolean access$100(ItemStack)
+ boolean hasLodestoneData(CompoundTag)
+ double access$400(ItemFrame)
+ double access$500(Vec3,Entity)
- double access$700(ItemFrame)
- double access$800(Vec3,Entity)
- void addLodestoneTags(Dimension,BlockPos,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.item.CompassItem$CompassWobble
</summary>

```diff
- boolean access$400(CompassItem$CompassWobble,long)
- boolean shouldUpdate(long)
- double access$600(CompassItem$CompassWobble)
+ double getDeltaRotation()
+ double getRotation()
- void access$500(CompassItem$CompassWobble,long,double)
+ void access$600(CompassItem$CompassWobble,Level,double)
+ void setDeltaRotation(double)
+ void setRotation(double)
+ void update(Level,double)
- void update(long,double)
```

</details>


















<details>
<summary>
net.minecraft.world.item.FireworkStarItem
</summary>

```diff
+ Component appendColors(Component,int[])
- Component appendColors(MutableComponent,int[])
```

</details>







































































































<details>
<summary>
net.minecraft.world.level.LevelType
</summary>

```diff
- Component getDescription()
- Component getHelpText()
+ String getDescriptionId()
+ String getHelpTextId()
```

</details>















<details>
<summary>
net.minecraft.world.level.biome.BiomeManager
</summary>

```diff
- Biome getNoiseBiomeAtPosition(BlockPos)
```

</details>



























<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSourceSettings
</summary>

```diff
- boolean useY()
- List getParameters()
- MultiNoiseBiomeSourceSettings setBiomes(List)
+ MultiNoiseBiomeSourceSettings setBiomes(Set)
- MultiNoiseBiomeSourceSettings setParameters(List)
- Pair lambda$null$0(Biome,Biome$ClimateParameters)
+ Set getBiomes()
- Stream lambda$setBiomes$1(Biome)
- void setUseY(boolean)
```

</details>































<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
- boolean canSetSpawn(Level,BlockPos)
```

</details>












<details>
<summary>
net.minecraft.world.level.block.ChainBlock
</summary>

```diff
- boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
```

</details>
























<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
- boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
- boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
```

</details>












































<details>
<summary>
net.minecraft.world.level.block.SeaPickleBlock
</summary>

```diff
- boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
```

</details>




























































<details>
<summary>
net.minecraft.world.level.block.entity.SignBlockEntity
</summary>

```diff
- Component getRenderMessage(int,UnaryOperator)
+ String getRenderMessage(int,Function)
```

</details>






















































<details>
<summary>
net.minecraft.world.level.levelgen.feature.Feature
</summary>

```diff
- boolean isAir(LevelSimulatedReader,BlockPos)
- boolean isGrassOrDirt(LevelSimulatedReader,BlockPos)
- boolean lambda$isGrassOrDirt$1(BlockState)
```

</details>
























































<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
</summary>

```diff
- TreeConfiguration withDecorators(List)
- void <init>(BlockStateProvider,BlockStateProvider,FoliagePlacer,TrunkPlacer,FeatureSize,List,int,boolean,Heightmap$Types)
+ void <init>(BlockStateProvider,BlockStateProvider,List,int)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
+ Map placeTrunk(LevelSimulatedRW,Random,int,BlockPos,int,Set,BoundingBox,SmallTreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
</summary>

```diff
- boolean isDirt(LevelSimulatedReader,BlockPos)
- boolean lambda$isDirt$0(BlockState)
- boolean placeLog(LevelSimulatedRW,Random,BlockPos,Set,BoundingBox,TreeConfiguration)
+ int getBaseHeight()
+ int getTreeHeight(Random,SmallTreeConfiguration)
- int getTreeHeight(Random)
- void placeLogIfFree(LevelSimulatedRW,Random,BlockPos$MutableBlockPos,Set,BoundingBox,TreeConfiguration)
- void setBlock(LevelWriter,BlockPos,BlockState,BoundingBox)
- void setDirtAt(LevelSimulatedRW,BlockPos)
```

</details>

























































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ com.mojang.realmsclient.client.FileDownload
- com.mojang.realmsclient.client.FileDownload$1
+ com.mojang.realmsclient.client.FileDownload$DownloadCountingOutputStream
- com.mojang.realmsclient.client.FileDownload$ProgressListener
+ com.mojang.realmsclient.client.FileDownload$ResourcePackProgressListener
- com.mojang.realmsclient.client.FileUpload
+ com.mojang.realmsclient.client.FileUpload$CustomInputStreamEntity
- com.mojang.realmsclient.client.Ping
+ com.mojang.realmsclient.client.Ping$Region
- com.mojang.realmsclient.client.RealmsClient
+ com.mojang.realmsclient.client.RealmsClient$CompatibleVersionResponse
- com.mojang.realmsclient.client.RealmsClient$Environment
+ com.mojang.realmsclient.client.RealmsClientConfig
- com.mojang.realmsclient.client.RealmsError
+ com.mojang.realmsclient.client.Request
- com.mojang.realmsclient.client.Request$Delete
+ com.mojang.realmsclient.client.Request$Get
- com.mojang.realmsclient.client.Request$Post
+ com.mojang.realmsclient.client.Request$Put
- com.mojang.realmsclient.client.UploadStatus
+ com.mojang.realmsclient.dto.Backup
- com.mojang.realmsclient.dto.BackupList
+ com.mojang.realmsclient.dto.GuardedSerializer
- com.mojang.realmsclient.dto.Ops
+ com.mojang.realmsclient.dto.PendingInvite
- com.mojang.realmsclient.dto.PendingInvitesList
+ com.mojang.realmsclient.dto.PingResult
- com.mojang.realmsclient.dto.PlayerInfo
+ com.mojang.realmsclient.dto.RealmsDescriptionDto
- com.mojang.realmsclient.dto.RealmsNews
+ com.mojang.realmsclient.dto.RealmsServer
- com.mojang.realmsclient.dto.RealmsServer$McoServerComparator
+ com.mojang.realmsclient.dto.RealmsServer$State
- com.mojang.realmsclient.dto.RealmsServer$WorldType
+ com.mojang.realmsclient.dto.RealmsServerAddress
- com.mojang.realmsclient.dto.RealmsServerList
+ com.mojang.realmsclient.dto.RealmsServerPing
- com.mojang.realmsclient.dto.RealmsServerPlayerList
+ com.mojang.realmsclient.dto.RealmsServerPlayerLists
- com.mojang.realmsclient.dto.RealmsWorldOptions
+ com.mojang.realmsclient.dto.RealmsWorldResetDto
- com.mojang.realmsclient.dto.ReflectionBasedSerialization
+ com.mojang.realmsclient.dto.RegionPingResult
- com.mojang.realmsclient.dto.Subscription
+ com.mojang.realmsclient.dto.Subscription$SubscriptionType
- com.mojang.realmsclient.dto.UploadInfo
+ com.mojang.realmsclient.dto.ValueObject
- com.mojang.realmsclient.dto.WorldDownload
+ com.mojang.realmsclient.dto.WorldTemplate
- com.mojang.realmsclient.dto.WorldTemplate$WorldTemplateType
+ com.mojang.realmsclient.dto.WorldTemplatePaginatedList
- com.mojang.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
+ com.mojang.realmsclient.exception.RealmsHttpException
- com.mojang.realmsclient.exception.RealmsServiceException
+ com.mojang.realmsclient.exception.RetryCallException
- com.mojang.realmsclient.gui.ErrorCallback
- com.mojang.realmsclient.RealmsMainScreen$NewsButton
+ com.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ com.mojang.realmsclient.RealmsMainScreen$ServerEntry
- com.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
+ com.mojang.realmsclient.RealmsMainScreen$TrialEntry
- com.mojang.realmsclient.Unit
- net.minecraft.client.ComponentCollector
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
+ net.minecraft.client.gui.font.AllMissingGlyphProvider
- net.minecraft.client.gui.font.FontManager
+ net.minecraft.client.gui.font.FontManager$1
- net.minecraft.client.gui.Font$StringRenderOutput
+ net.minecraft.client.gui.Gui
- net.minecraft.client.gui.GuiComponent
+ net.minecraft.client.gui.MapRenderer
- net.minecraft.client.gui.MapRenderer$1
+ net.minecraft.client.gui.MapRenderer$MapInstance
- net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$SelectedGameMode
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList
- net.minecraft.client.GuiMessage
+ net.minecraft.client.HotbarManager
- net.minecraft.client.KeyMapping
+ net.minecraft.client.KeyMapping$1
- net.minecraft.client.map.Map$4
+ net.minecraft.client.map.package-info
- net.minecraft.client.model.AbstractZombieModel
+ net.minecraft.client.model.AgeableListModel
- net.minecraft.client.model.AnimationUtils
+ net.minecraft.client.model.ArmedModel
- net.minecraft.client.model.ArmorStandArmorModel
+ net.minecraft.client.model.ArmorStandModel
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
- net.minecraft.client.model.ColorableListModel
+ net.minecraft.client.model.CowModel
- net.minecraft.client.model.CreeperModel
+ net.minecraft.client.model.DolphinModel
+ net.minecraft.client.model.dragon.DragonHeadModel
- net.minecraft.client.model.dragon.package-info
- net.minecraft.client.model.DrownedModel
+ net.minecraft.client.model.ElytraModel
- net.minecraft.client.model.EndermanModel
+ net.minecraft.client.model.EndermiteModel
- net.minecraft.client.model.EntityModel
+ net.minecraft.client.model.EvokerFangsModel
- net.minecraft.client.model.FoxModel
+ net.minecraft.client.model.geom.ModelPart
- net.minecraft.client.model.geom.ModelPart$Cube
+ net.minecraft.client.model.geom.ModelPart$Polygon
- net.minecraft.client.model.geom.ModelPart$Vertex
+ net.minecraft.client.model.geom.package-info
+ net.minecraft.client.model.GhastModel
- net.minecraft.client.model.GiantZombieModel
+ net.minecraft.client.model.GuardianModel
- net.minecraft.client.model.HeadedModel
+ net.minecraft.client.model.HoglinModel
- net.minecraft.client.model.HorseModel
+ net.minecraft.client.model.HumanoidHeadModel
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
- net.minecraft.client.model.PiglinModel
+ net.minecraft.client.model.PigModel
+ net.minecraft.client.model.PlayerModel
- net.minecraft.client.model.PolarBearModel
+ net.minecraft.client.model.PufferfishBigModel
- net.minecraft.client.model.PufferfishMidModel
+ net.minecraft.client.model.PufferfishSmallModel
- net.minecraft.client.model.QuadrupedModel
+ net.minecraft.client.model.RabbitModel
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
- net.minecraft.client.model.SlimeModel
+ net.minecraft.client.model.SnowGolemModel
- net.minecraft.client.model.SpiderModel
+ net.minecraft.client.model.SquidModel
- net.minecraft.client.model.StriderModel
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
- net.minecraft.client.particle.PortalParticle$Provider
+ net.minecraft.client.particle.ReversePortalParticle
- net.minecraft.client.particle.ReversePortalParticle$1
+ net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
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
+ net.minecraft.client.particle.WhiteAshParticle
- net.minecraft.client.particle.WhiteAshParticle$Provider
- net.minecraft.client.player.AbstractClientPlayer
+ net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
- net.minecraft.client.player.KeyboardInput
+ net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.LocalPlayer$1
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
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
- net.minecraft.client.renderer.debug.HeightMapRenderer$1
+ net.minecraft.client.renderer.debug.LightDebugRenderer
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
- net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
- net.minecraft.client.renderer.debug.WaterDebugRenderer
+ net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.EffectInstance
+ net.minecraft.client.renderer.entity.AbstractHorseRenderer
- net.minecraft.client.renderer.entity.AbstractZombieRenderer
+ net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
- net.minecraft.client.renderer.entity.BatRenderer
+ net.minecraft.client.renderer.entity.BeeRenderer
- net.minecraft.client.renderer.entity.BlazeRenderer
+ net.minecraft.client.renderer.entity.BoatRenderer
- net.minecraft.client.renderer.entity.CatRenderer
+ net.minecraft.client.renderer.entity.CaveSpiderRenderer
- net.minecraft.client.renderer.entity.ChestedHorseRenderer
+ net.minecraft.client.renderer.entity.ChickenRenderer
- net.minecraft.client.renderer.entity.CodRenderer
+ net.minecraft.client.renderer.entity.CowRenderer
- net.minecraft.client.renderer.entity.CreeperRenderer
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
+ net.minecraft.client.renderer.entity.layers.AbstractArmorLayer
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
- net.minecraft.client.renderer.entity.layers.PiglinArmorLayer
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
- net.minecraft.client.renderer.entity.OcelotRenderer
+ net.minecraft.client.renderer.entity.package-info
+ net.minecraft.client.renderer.entity.PaintingRenderer
- net.minecraft.client.renderer.entity.PandaRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.player.package-info
- net.minecraft.client.renderer.entity.player.PlayerRenderer
- net.minecraft.client.renderer.entity.PolarBearRenderer
+ net.minecraft.client.renderer.entity.PufferfishRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer
+ net.minecraft.client.renderer.entity.RavagerRenderer
- net.minecraft.client.renderer.entity.RenderLayerParent
+ net.minecraft.client.renderer.entity.SalmonRenderer
- net.minecraft.client.renderer.entity.SheepRenderer
+ net.minecraft.client.renderer.entity.ShulkerBulletRenderer
- net.minecraft.client.renderer.entity.ShulkerRenderer
+ net.minecraft.client.renderer.entity.SilverfishRenderer
- net.minecraft.client.renderer.entity.SkeletonRenderer
+ net.minecraft.client.renderer.entity.SlimeRenderer
- net.minecraft.client.renderer.entity.SnowGolemRenderer
+ net.minecraft.client.renderer.entity.SpectralArrowRenderer
- net.minecraft.client.renderer.entity.SpiderRenderer
+ net.minecraft.client.renderer.entity.SquidRenderer
- net.minecraft.client.renderer.entity.StrayRenderer
+ net.minecraft.client.renderer.entity.StriderRenderer
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
- net.minecraft.client.renderer.entity.ZoglinRenderer
+ net.minecraft.client.renderer.entity.ZombieRenderer
- net.minecraft.client.renderer.entity.ZombieVillagerRenderer
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
- net.minecraft.client.renderer.texture.TextureAtlasSprite$Info
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$InterpolationData
- net.minecraft.client.renderer.texture.TextureManager
+ net.minecraft.client.renderer.texture.Tickable
- net.minecraft.client.renderer.ViewArea
+ net.minecraft.client.renderer.VirtualScreen
+ net.minecraft.client.resources.AssetIndex
- net.minecraft.client.resources.ClientPackSource
+ net.minecraft.client.resources.ClientPackSource$1
- net.minecraft.client.resources.ClientPackSource$2
+ net.minecraft.client.resources.DefaultClientResourcePack
- net.minecraft.client.resources.DefaultPlayerSkin
+ net.minecraft.client.resources.DirectAssetIndex
- net.minecraft.client.resources.FoliageColorReloadListener
+ net.minecraft.client.resources.GrassColorReloadListener
+ net.minecraft.client.resources.language.I18n
- net.minecraft.client.resources.language.Language
+ net.minecraft.client.resources.language.LanguageManager
- net.minecraft.client.resources.language.Locale
+ net.minecraft.client.resources.language.package-info
- net.minecraft.client.resources.LegacyResourcePackAdapter
+ net.minecraft.client.resources.LegacyStuffWrapper
- net.minecraft.client.resources.metadata.animation.AnimationFrame
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.animation.package-info
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
- net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
- net.minecraft.client.resources.metadata.language.LanguageMetadataSection
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSectionSerializer
- net.minecraft.client.resources.metadata.language.package-info
+ net.minecraft.client.resources.metadata.package-info
- net.minecraft.client.resources.metadata.texture.package-info
- net.minecraft.client.resources.metadata.texture.TextureMetadataSection
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
- net.minecraft.client.resources.MobEffectTextureManager
+ net.minecraft.client.resources.model.BakedModel
- net.minecraft.client.resources.model.BlockModelRotation
+ net.minecraft.client.resources.model.BuiltInModel
- net.minecraft.client.resources.model.Material
+ net.minecraft.client.resources.model.ModelBakery
- net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
+ net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
- net.minecraft.client.resources.model.ModelManager
+ net.minecraft.client.resources.model.ModelResourceLocation
- net.minecraft.client.resources.model.ModelState
+ net.minecraft.client.resources.model.MultiPartBakedModel
- net.minecraft.client.resources.model.MultiPartBakedModel$Builder
+ net.minecraft.client.resources.model.package-info
+ net.minecraft.client.resources.model.SimpleBakedModel
- net.minecraft.client.resources.model.SimpleBakedModel$Builder
+ net.minecraft.client.resources.model.UnbakedModel
- net.minecraft.client.resources.model.WeightedBakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel$Builder
- net.minecraft.client.resources.model.WeightedBakedModel$WeightedModel
+ net.minecraft.client.resources.PackAdapterV4
- net.minecraft.client.resources.package-info
- net.minecraft.client.resources.PaintingTextureManager
+ net.minecraft.client.resources.SkinManager
- net.minecraft.client.resources.SkinManager$1
+ net.minecraft.client.resources.SkinManager$SkinTextureCallback
+ net.minecraft.client.resources.sounds.AbstractSoundInstance
- net.minecraft.client.resources.sounds.AbstractTickableSoundInstance
+ net.minecraft.client.resources.sounds.AmbientSoundHandler
- net.minecraft.client.resources.sounds.BeeAggressiveSoundInstance
+ net.minecraft.client.resources.sounds.BeeFlyingSoundInstance
- net.minecraft.client.resources.sounds.BeeSoundInstance
+ net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
- net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
+ net.minecraft.client.resources.sounds.BubbleColumnAmbientSoundHandler
- net.minecraft.client.resources.sounds.ElytraOnPlayerSoundInstance
+ net.minecraft.client.resources.sounds.EntityBoundSoundInstance
- net.minecraft.client.resources.sounds.GuardianAttackSoundInstance
+ net.minecraft.client.resources.sounds.MinecartSoundInstance
+ net.minecraft.client.resources.sounds.package-info
- net.minecraft.client.resources.sounds.RidingMinecartSoundInstance
+ net.minecraft.client.resources.sounds.SimpleSoundInstance
- net.minecraft.client.resources.sounds.Sound
+ net.minecraft.client.resources.sounds.Sound$Type
- net.minecraft.client.resources.sounds.SoundEventRegistration
+ net.minecraft.client.resources.sounds.SoundEventRegistrationSerializer
- net.minecraft.client.resources.sounds.SoundInstance
+ net.minecraft.client.resources.sounds.SoundInstance$Attenuation
- net.minecraft.client.resources.sounds.TickableSoundInstance
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundHandler
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
- net.minecraft.client.resources.SplashManager
+ net.minecraft.client.resources.TextureAtlasHolder
- net.minecraft.client.resources.UnopenedResourcePack
- net.minecraft.client.searchtree.MutableSearchTree
- net.minecraft.client.searchtree.package-info
+ net.minecraft.client.searchtree.ReloadableIdSearchTree
- net.minecraft.client.searchtree.ReloadableIdSearchTree$IntersectionIterator
+ net.minecraft.client.searchtree.ReloadableSearchTree
- net.minecraft.client.searchtree.ReloadableSearchTree$MergingUniqueIterator
+ net.minecraft.client.searchtree.SearchRegistry
- net.minecraft.client.searchtree.SearchRegistry$Key
+ net.minecraft.client.searchtree.SearchTree
- net.minecraft.client.searchtree.SuffixArray
+ net.minecraft.client.searchtree.SuffixArray$1
+ net.minecraft.client.server.IntegratedPlayerList
- net.minecraft.client.server.IntegratedServer
+ net.minecraft.client.server.LanServer
- net.minecraft.client.server.LanServerDetection
+ net.minecraft.client.server.LanServerDetection$LanServerDetector
- net.minecraft.client.server.LanServerDetection$LanServerList
+ net.minecraft.client.server.LanServerPinger
- net.minecraft.client.server.package-info
+ net.minecraft.client.skins.package-info
- net.minecraft.client.sounds.AudioStream
+ net.minecraft.client.sounds.ChannelAccess
- net.minecraft.client.sounds.ChannelAccess$ChannelHandle
+ net.minecraft.client.sounds.LoopingAudioStream
- net.minecraft.client.sounds.LoopingAudioStream$1
+ net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
- net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
+ net.minecraft.client.sounds.MusicManager
- net.minecraft.client.StringDecomposer
- net.minecraft.client.StringSplitter
- net.minecraft.client.StringSplitter$FlatComponents
- net.minecraft.client.StringSplitter$LineComponent
- net.minecraft.client.StringSplitter$WidthLimitedCharSink
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
- net.minecraft.commands.arguments.package-info
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelectorParser
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
+ net.minecraft.commands.arguments.selector.options.package-info
- net.minecraft.commands.arguments.selector.package-info
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
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.LocatableSource
- net.minecraft.core.Location
+ net.minecraft.core.MapFiller
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.NonNullList
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
- net.minecraft.core.particles.DustParticleOptions
+ net.minecraft.core.particles.DustParticleOptions$1
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.Position
+ net.minecraft.core.PositionImpl
- net.minecraft.core.Registry
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.SerializableBoolean
+ net.minecraft.core.SerializableLong
- net.minecraft.core.SerializableUUID
+ net.minecraft.core.Source
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdventureAdvancements
+ net.minecraft.data.advancements.HusbandryAdvancements
- net.minecraft.data.advancements.NetherAdvancements
+ net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.StoryAdvancements
- net.minecraft.data.advancements.TheEndAdvancements
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
- net.minecraft.data.models.blockstates.package-info
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
+ net.minecraft.data.models.blockstates.PropertyValue
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
+ net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1
+ net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.GameTest
+ net.minecraft.gametest.framework.GameTestAssertException
- net.minecraft.gametest.framework.GameTestAssertPosException
+ net.minecraft.gametest.framework.GameTestBatch
- net.minecraft.gametest.framework.GameTestBatchRunner
+ net.minecraft.gametest.framework.GameTestBatchRunner$1
- net.minecraft.gametest.framework.GameTestEvent
+ net.minecraft.gametest.framework.GameTestGenerator
- net.minecraft.gametest.framework.GameTestHelper
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestRunner$1
- net.minecraft.gametest.framework.GameTestSequence
+ net.minecraft.gametest.framework.GameTestSequence$Condition
- net.minecraft.gametest.framework.GameTestServer
+ net.minecraft.gametest.framework.GameTestServer$1
- net.minecraft.gametest.framework.GameTestTicker
+ net.minecraft.gametest.framework.GameTestTimeoutException
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.package-info
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.TeamcityTestReporter
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
+ net.minecraft.gametest.framework.TestReporter
+ net.minecraft.locale.Language
- net.minecraft.locale.package-info
+ net.minecraft.nbt.ByteArrayTag
- net.minecraft.nbt.ByteArrayTag$1
+ net.minecraft.nbt.ByteTag
- net.minecraft.nbt.ByteTag$1
+ net.minecraft.nbt.ByteTag$Cache
- net.minecraft.nbt.CollectionTag
+ net.minecraft.nbt.CompoundTag
- net.minecraft.nbt.CompoundTag$1
+ net.minecraft.nbt.DoubleTag
- net.minecraft.nbt.DoubleTag$1
+ net.minecraft.nbt.EndTag
- net.minecraft.nbt.EndTag$1
+ net.minecraft.nbt.FloatTag
- net.minecraft.nbt.FloatTag$1
+ net.minecraft.nbt.IntArrayTag
- net.minecraft.nbt.IntArrayTag$1
+ net.minecraft.nbt.IntTag
- net.minecraft.nbt.IntTag$1
+ net.minecraft.nbt.IntTag$Cache
- net.minecraft.nbt.ListTag
+ net.minecraft.nbt.ListTag$1
- net.minecraft.nbt.LongArrayTag
+ net.minecraft.nbt.LongArrayTag$1
- net.minecraft.nbt.LongTag
+ net.minecraft.nbt.LongTag$1
- net.minecraft.nbt.LongTag$Cache
+ net.minecraft.nbt.NbtAccounter
- net.minecraft.nbt.NbtAccounter$1
+ net.minecraft.nbt.NbtIo
- net.minecraft.nbt.NbtOps
+ net.minecraft.nbt.NbtUtils
- net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.Tag
+ net.minecraft.nbt.TagParser
- net.minecraft.nbt.TagType
+ net.minecraft.nbt.TagType$1
- net.minecraft.nbt.TagTypes
- net.minecraft.network.chat.BaseComponent
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component$1
- net.minecraft.network.chat.Component$ContentConsumer
- net.minecraft.network.chat.Component$StyledContentConsumer
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.ContextAwareComponent
+ net.minecraft.network.chat.HoverEvent
- net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$ItemStackInfo
+ net.minecraft.network.chat.KeybindComponent
- net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.TextComponent
- net.minecraft.network.chat.TranslatableComponent
+ net.minecraft.network.chat.TranslatableFormatException
- net.minecraft.network.CipherBase
+ net.minecraft.network.CipherDecoder
- net.minecraft.network.CipherEncoder
+ net.minecraft.network.CompressionDecoder
- net.minecraft.network.CompressionEncoder
+ net.minecraft.network.Connection
- net.minecraft.network.Connection$1
+ net.minecraft.network.Connection$2
- net.minecraft.network.Connection$PacketHolder
+ net.minecraft.network.ConnectionProtocol
- net.minecraft.network.ConnectionProtocol$1
+ net.minecraft.network.ConnectionProtocol$PacketSet
- net.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.package-info
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAddGlobalEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddMobPacket
- net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
+ net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
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
- net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
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
- net.minecraft.network.protocol.game.ClientboundSetEquippedItemPacket
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
+ net.minecraft.network.protocol.game.ClientGamePacketListener
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
- net.minecraft.server.Bootstrap$1
- net.minecraft.server.commands.AttributeCommand
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
- net.minecraft.sounds.Music
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
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$1
+ net.minecraft.tags.StaticTagHelper$Wrapper
- net.minecraft.tags.SynchronizableTagCollection
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$1
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$Named
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagManager
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$1
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
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
+ net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.OminousBannerRenameFix
+ net.minecraft.util.Deserializer
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
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
- net.minecraft.util.Serializer
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$1
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringUtil
+ net.minecraft.util.TimeUtil
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkBiomeContainer
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkGeneratorFactory
+ net.minecraft.world.level.chunk.ChunkGeneratorType
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.FeatureAccess
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
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
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$1
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.OldChunkStorage
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
- net.minecraft.world.level.dimension.Dimension
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.end.TheEndDimension
- net.minecraft.world.level.dimension.NetherDimension
+ net.minecraft.world.level.dimension.NetherDimension$1
- net.minecraft.world.level.dimension.NormalDimension
- net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CaveWorldCarver
- net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
+ net.minecraft.world.level.levelgen.carver.NetherWorldCarver
- net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
- net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.WorldCarver
+ net.minecraft.world.level.levelgen.ChunkGeneratorProvider
- net.minecraft.world.level.levelgen.ChunkGeneratorSettings
+ net.minecraft.world.level.levelgen.DebugGeneratorSettings
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.AbstractSmallTreeFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BastionBridgePools
+ net.minecraft.world.level.levelgen.feature.BastionFeature
- net.minecraft.world.level.levelgen.feature.BastionFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.BastionHoglinStablePools
- net.minecraft.world.level.levelgen.feature.BastionHousingUnitsPools
+ net.minecraft.world.level.levelgen.feature.BastionPieces
- net.minecraft.world.level.levelgen.feature.BastionPieces$BastionPiece
+ net.minecraft.world.level.levelgen.feature.BastionSharedPools
- net.minecraft.world.level.levelgen.feature.BastionTreasureRoomPools
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DarkOakFeature
+ net.minecraft.world.level.levelgen.feature.FancyTreeFeature$FoliageCoords
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
- net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
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
+ net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.FlatLevelSource
- net.minecraft.world.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
+ net.minecraft.world.level.levelgen.GenerationStep
- net.minecraft.world.level.levelgen.GenerationStep$Carving
+ net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.NetherGeneratorSettings
- net.minecraft.world.level.levelgen.NetherLevelSource
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.OverworldGeneratorSettings
+ net.minecraft.world.level.levelgen.OverworldLevelSource
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.synth.SurfaceNoise
- net.minecraft.world.level.levelgen.TheEndGeneratorSettings
+ net.minecraft.world.level.levelgen.TheEndLevelSource
- net.minecraft.world.level.levelgen.WorldgenRandom
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
- net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.material.FluidStateImpl
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
- net.minecraft.world.level.newbiome.layer.Layers
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
- net.minecraft.world.level.redstone.package-info
+ net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SaveDataDirtyRunnable
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.storage.CommandStorage
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
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.ConstantIntValue
+ net.minecraft.world.level.storage.loot.ConstantIntValue$Serializer
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$Serializer
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
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
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
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$DataSource
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
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions$Serializer
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
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
- net.minecraft.world.level.storage.loot.IntLimiter
+ net.minecraft.world.level.storage.loot.IntLimiter$1
- net.minecraft.world.level.storage.loot.IntLimiter$Serializer
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
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.PredicateManager
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
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
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions$Serializer
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
+ net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
- net.minecraft.world.level.storage.loot.RandomIntGenerator
+ net.minecraft.world.level.storage.loot.RandomIntGenerators
- net.minecraft.world.level.storage.loot.RandomValueBounds
+ net.minecraft.world.level.storage.loot.RandomValueBounds$Serializer
- net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.McRegionUpgrader
- net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.storage.PlayerDataStorage
+ net.minecraft.world.level.storage.threaded.package-info
- net.minecraft.world.level.storage.WorldData
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
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.PosAndRot
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
- net.minecraft.world.phys.shapes.IntPointRange
+ net.minecraft.world.phys.shapes.NonOverlappingMerger
- net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
+ net.minecraft.world.phys.shapes.Shapes
- net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
+ net.minecraft.world.phys.shapes.SliceShape
- net.minecraft.world.phys.shapes.SubShape
+ net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.shapes.WorldRegionIndirectVoxelShape
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
XXX.blaze3d.platform.InputConstants -2M
```
```
XXX.blaze3d.platform.InputConstants$Key +3M -1M | +1P
```
```
XXX.realmsclient.gui.RowButton +2M -2M | +1P -1P
```
```
XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoList +2M -2M
```
```
XXX.gui.screens.RealmsBackupScreen$Entry +4M -4M
```
```
XXX.gui.screens.RealmsClientOutdatedScreen +1M -1M
```
```
XXX.gui.screens.RealmsCreateRealmScreen +1M -1M
```
```
XXX.gui.screens.RealmsInviteScreen +1M -1M
```
```
XXX.gui.screens.RealmsNotificationsScreen +2M -2M
```
```
XXX.gui.screens.RealmsParentalConsentScreen +1M -1M
```
```
XXX.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton +1M -1M
```
```
XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList +1M -1M
```
```
XXX.gui.screens.RealmsPlayerScreen$Entry +3M -3M
```
```
XXX.gui.screens.RealmsResetNormalWorldScreen +4M -4M | +2P -2P
```
```
XXX.gui.screens.RealmsResetWorldScreen$FrameButton +2M -2M
```
```
XXX.gui.screens.RealmsSelectFileToUploadScreen +1M -1M
```
```
XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList +1M -1M
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList +1M -1M
```
```
XXX.gui.screens.RealmsSlotOptionsScreen +10M -10M | +4P -2P
```
```
XXX.gui.screens.RealmsSubscriptionInfoScreen +1M -1M
```
```
XXX.gui.screens.RealmsTermsScreen +1M -1M
```
```
XXX.util.task.LongRunningTask +1M -1M
```
```
net.minecraft.SharedConstants -1M
```
```
XXX.minecraft.client.Minecraft +6M -6M | +1P
```
```
XXX.minecraft.client.NarratorStatus +1M -1M | +1P -1P
```
```
XXX.minecraft.client.Options +1P
```
```
XXX.minecraft.client.ProgressOption +1M -1M
```
```
XXX.minecraft.client.Screenshot +1M -1M
```
```
XXX.gui.font.FontSet +7M -6M | +2P -3P
```
```
XXX.gui.font.TextFieldHelper +28M -3M | +3P -3P
```
```
XXX.font.providers.BitmapProvider +4M -2M | +1P -1P
```
```
XXX.font.providers.LegacyUnicodeBitmapsProvider +3M -2M
```
```
XXX.gui.screens.AlertScreen +2M -2M | +1P -1P
```
```
XXX.gui.screens.ChatScreen +1M -1M
```
```
XXX.gui.screens.ConfirmLinkScreen +1M -1M | +2P -2P
```
```
XXX.gui.screens.ConnectScreen +1M -1M
```
```
XXX.gui.screens.CreateBuffetWorldScreen +2M -1M
```
```
XXX.gui.screens.CreateFlatWorldScreen +1M -1M | +2P -2P
```
```
XXX.gui.screens.DeathScreen +1M -1M
```
```
XXX.gui.screens.DirectJoinServerScreen +1M -1M
```
```
XXX.gui.screens.EditServerScreen +2M -1M
```
```
XXX.gui.screens.GenericDirtMessageScreen +1M -1M
```
```
XXX.gui.screens.LanguageSelectScreen +1M -1M
```
```
XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry +1M -1M
```
```
XXX.gui.screens.LoadingOverlay +2M -2M
```
```
XXX.gui.screens.MouseSettingsScreen +1M -1M
```
```
XXX.gui.screens.PresetFlatWorldScreen +2M -2M | +2P -2P
```
```
XXX.gui.screens.ProgressScreen +1M -1M | +2P -2P
```
```
XXX.gui.screens.Screen +7M -7M
```
```
XXX.gui.screens.SkinCustomizationScreen +2M -2M
```
```
XXX.gui.screens.TitleScreen +1M -1M
```
```
XXX.gui.screens.WinScreen +1M -1M | +2P
```
```
XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry +1M -1M
```
```
XXX.screens.achievement.StatsScreen$MobsStatisticsList +1M -1M
```
```
XXX.screens.advancements.AdvancementTab +4M -4M | +1P -1P
```
```
XXX.screens.controls.ControlList$KeyEntry$1 +2M -2M | +1P
```
```
XXX.screens.controls.ControlsScreen +1M -1M
```
```
XXX.screens.inventory.AbstractCommandBlockEditScreen +1M -1M
```
```
XXX.screens.inventory.AbstractContainerScreen +4M -4M | +1P -1P
```
```
XXX.screens.inventory.AnvilScreen +2M -2M
```
```
XXX.screens.inventory.BeaconScreen$BeaconConfirmButton +1M -1M
```
```
XXX.screens.inventory.BeaconScreen$BeaconScreenButton +1M -1M | +1P -1P
```
```
XXX.screens.inventory.BookEditScreen$Pos2i +1M -6M | -1P
```
```
XXX.screens.inventory.BrewingStandScreen +3M -3M
```
```
XXX.screens.inventory.ContainerScreen +3M -3M
```
```
XXX.screens.inventory.EffectRenderingInventoryScreen +5M -5M
```
```
XXX.screens.inventory.EnchantmentScreen +3M -3M
```
```
XXX.screens.inventory.GrindstoneScreen +3M -3M
```
```
XXX.screens.inventory.HorseInventoryScreen +3M -3M
```
```
XXX.screens.inventory.ItemCombinerScreen +3M -3M
```
```
XXX.screens.inventory.JigsawBlockEditScreen$1 +1M -1M
```
```
XXX.screens.inventory.MerchantScreen$TradeOfferButton +1M -1M
```
```
XXX.screens.inventory.PageButton +1M -1M
```
```
XXX.screens.inventory.SignEditScreen +6M -5M | +1P
```
```
XXX.screens.inventory.StructureBlockEditScreen +1M -1M
```
```
XXX.screens.multiplayer.SafetyScreen +2M -1M | +4P -5P
```
```
XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry +1M -1M
```
```
XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent +2M -2M | +1P -1P
```
```
XXX.screens.recipebook.GhostRecipe +1M -1M
```
```
XXX.screens.recipebook.OverlayRecipeComponent +2M -2M
```
```
XXX.screens.recipebook.RecipeBookComponent +5M -5M
```
```
XXX.screens.recipebook.RecipeBookTabButton +1M -1M
```
```
XXX.screens.recipebook.SmokingRecipeBookComponent +1M -1M
```
```
XXX.screens.resourcepacks.ResourcePackSelectScreen +1M -1M
```
```
XXX.resourcepacks.lists.ResourcePackList$ResourcePackEntry +1M -3M
```
```
XXX.screens.worldselection.CreateWorldScreen$1 +2M -2M
```
```
XXX.screens.worldselection.CreateWorldScreen$3 +2M -3M
```
```
XXX.screens.worldselection.CreateWorldScreen$5 +3M -3M
```
```
XXX.screens.worldselection.CreateWorldScreen$7 +2M -1M | +1P -1P
```
```
XXX.screens.worldselection.EditWorldScreen +1M -1M
```
```
XXX.screens.worldselection.SelectWorldScreen +2M -2M | +1P -1P
```
```
XXX.screens.worldselection.WorldSelectionList$WorldListEntry +1M -1M
```
```
XXX.gui.spectator.PlayerMenuItem +1M -1M
```
```
XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem +1M -1M
```
```
XXX.spectator.categories.TeleportToPlayerMenuCategory +1M -1M
```
```
XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem +1M -1M
```
```
XXX.client.map.Map +13M -10M | +5P -2P
```
```
XXX.client.map.Map$2 +1M -2M
```
```
XXX.minecraft.commands.Commands +2M -2M
```
```
XXX.minecraft.commands.SharedSuggestionProvider +1M -1M
```
```
XXX.commands.arguments.ResourceLocationArgument +4M -1M | +1P
```
```
XXX.network.chat.NbtComponent$BlockNbtComponent +3M -1M
```
```
XXX.network.chat.NbtComponent$StorageNbtComponent +3M -1M
```
```
XXX.network.chat.SelectorComponent +4M -3M
```
```
XXX.network.chat.Style$1 +1M -23M | +1P
```
```
XXX.minecraft.server.MinecraftServer$1 +1M -1M | -1P
```
```
XXX.util.worldupdate.WorldUpgrader +1M -1M | +2P -2P
```
```
XXX.world.entity.EntityType +2M -2M | +2P
```
```
XXX.world.entity.LivingEntity +3M -2M
```
```
XXX.ai.attributes.AttributeMap +3M
```
```
XXX.entity.player.Player +3M -2M
```
```
XXX.world.inventory.RecipeHolder +1M -1M
```
```
XXX.world.item.ItemStack +4M -3M | +2P -1P
```
```
XXX.world.item.RecordItem +1M -1M
```
```
XXX.world.level.GameRules +9M -3M
```
```
XXX.world.level.GameRules$BooleanValue +4M
```
```
XXX.world.level.LevelSettings +6M -3M | +3P
```
```
XXX.level.biome.Biome +8M -8M
```
```
XXX.level.biome.BiomeDefaultFeatures +26P -23P
```
```
XXX.level.biome.BiomeSpecialEffects +3M -2M | +1P
```
```
XXX.level.biome.BiomeSpecialEffects$Builder +1M | +1P
```
```
XXX.level.biome.MultiNoiseBiomeSource +1M -1M | +6P -4P
```
```
XXX.level.block.AbstractSkullBlock +1M
```
```
XXX.level.block.Block +1M -1M
```
```
XXX.level.block.Blocks +3P -3P
```
```
XXX.level.block.CocoaBlock +1M
```
```
XXX.level.block.RespawnAnchorBlock +1M
```
```
XXX.block.entity.AbstractFurnaceBlockEntity +5M -4M
```
```
XXX.level.border.WorldBorder +3M -2M | +1P
```
```
XXX.levelgen.feature.DeltaFeature +1P
```
```
XXX.levelgen.feature.TreeFeature +22M -2M
```
```
XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder +4M -2M | +6P -1P
```
```
XXX.feature.foliageplacers.FoliagePlacer +5M -2M | +3P -5P
```
```
XXX.feature.trunkplacers.StraightTrunkPlacer +1M -1M
```
```
XXX.feature.trunkplacers.TrunkPlacerType +4P
```
```
XXX.structure.templatesystem.StructureManager +1M -1M
```

</details>



























<details>
<summary>
com.mojang.blaze3d.platform.InputConstants
</summary>

```diff
+ String translateKeyCode(int)
+ String translateScanCode(int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.InputConstants$Key
</summary>

```diff
- Component getDisplayName()
- Component lambda$new$0(InputConstants$Type,int,String)
+ Map access$100()
- Map access$200()
```

</details>









































<details>
<summary>
com.mojang.realmsclient.gui.RowButton
</summary>

```diff
+ void drawButtonsInRow(List,RealmsObjectSelectionList,int,int,int,int)
- void drawButtonsInRow(PoseStack,List,RealmsObjectSelectionList,int,int,int,int)
+ void drawForRowAt(int,int,int,int)
- void drawForRowAt(PoseStack,int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoList
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderItem(int,int,int,int,int,int,float)
- void renderItem(PoseStack,int,int,int,int,int,int,float)
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupScreen$Entry
</summary>

```diff
+ void drawInfo(int,int,int,int)
- void drawInfo(PoseStack,int,int,int,int)
+ void drawRestore(int,int,int,int)
- void drawRestore(PoseStack,int,int,int,int)
+ void render(int,int,int,int,int,int,int,boolean,float)
- void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
+ void renderBackupItem(Backup,int,int,int,int)
- void renderBackupItem(PoseStack,Backup,int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsClientOutdatedScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsCreateRealmScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsInviteScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
</summary>

```diff
+ void drawIcons(int,int)
- void drawIcons(PoseStack,int,int)
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>


<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
</summary>

```diff
+ void draw(int,int,boolean)
- void draw(PoseStack,int,int,boolean)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
</summary>

```diff
+ void renderBackground()
- void renderBackground(PoseStack)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$Entry
</summary>

```diff
+ void lambda$renderInvitedItem$0(int)
- void lambda$renderInvitedItem$0(PoseStack,int)
+ void render(int,int,int,int,int,int,int,boolean,float)
- void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
+ void renderInvitedItem(PlayerInfo,int,int,int,int)
- void renderInvitedItem(PoseStack,PlayerInfo,int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen
</summary>

```diff
- Component generateStructuresTitle()
- Component levelTypeTitle()
+ String generateStructuresTitle()
+ String levelTypeTitle()
- void <init>(RealmsResetWorldScreen,Component)
+ void <init>(RealmsResetWorldScreen,String)
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$FrameButton
</summary>

```diff
- void <init>(RealmsResetWorldScreen,int,int,Component,ResourceLocation,Button$OnPress)
+ void <init>(RealmsResetWorldScreen,int,int,String,ResourceLocation,Button$OnPress)
+ void renderButton(int,int,float)
- void renderButton(PoseStack,int,int,float)
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
</summary>

```diff
+ void renderBackground()
- void renderBackground(PoseStack)
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
</summary>

```diff
+ void renderBackground()
- void renderBackground(PoseStack)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen
</summary>

```diff
- Component commandBlocksTitle()
- Component difficultyTitle()
- Component forceGameModeTitle()
- Component gameModeTitle()
- Component getOnOff(boolean)
- Component pvpTitle()
- Component spawnAnimalsTitle()
- Component spawnMonstersTitle()
- Component spawnNPCsTitle()
+ String commandBlocksTitle()
+ String difficultyTitle()
+ String forceGameModeTitle()
+ String gameModeTitle()
+ String getOnOff(boolean)
+ String pvpTitle()
+ String spawnAnimalsTitle()
+ String spawnMonstersTitle()
+ String spawnNPCsTitle()
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsTermsScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>










<details>
<summary>
com.mojang.realmsclient.util.task.LongRunningTask
</summary>

```diff
- void error(Component)
+ void error(String)
```

</details>









<details>
<summary>
net.minecraft.SharedConstants
</summary>

```diff
+ String filterUnicodeSupplementary(String)
```

</details>















































































<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
+ FontManager getFontManager()
- Music getSituationalMusic()
+ MusicManager$Music getSituationalMusic()
- Style lambda$grabHugeScreenshot$31(File,Style)
- Style lambda$grabPanoramixScreenshot$30(File,Style)
+ void lambda$grabHugeScreenshot$31(File,Style)
+ void lambda$grabPanoramixScreenshot$30(File,Style)
- void renderFpsMeter(PoseStack,ProfileResults)
+ void renderFpsMeter(ProfileResults)
- void selectLevel(String,LevelSettings)
+ void selectLevel(String,String,LevelSettings)
- void selectMainFont(boolean)
```

</details>

<details>
<summary>
net.minecraft.client.NarratorStatus
</summary>

```diff
- Component getName()
+ String getKey()
```

</details>


<details>
<summary>
net.minecraft.client.ProgressOption
</summary>

```diff
- Component getMessage(Options)
+ String getMessage(Options)
```

</details>
<details>
<summary>
net.minecraft.client.Screenshot
</summary>

```diff
- Style lambda$null$1(File,Style)
+ void lambda$null$1(File,Style)
```

</details>







<details>
<summary>
net.minecraft.client.gui.font.FontSet
</summary>

```diff
+ BakedGlyph getGlyph(char)
- BakedGlyph getGlyph(int)
+ BakedGlyph lambda$getGlyph$3(int)
- BakedGlyph lambda$getGlyph$4(int)
+ CharList lambda$reload$1(int)
+ GlyphInfo getGlyphInfo(char)
- GlyphInfo getGlyphInfo(int)
+ GlyphInfo lambda$getGlyphInfo$2(int)
- GlyphInfo lambda$getGlyphInfo$3(int)
- IntList lambda$null$1(int)
+ RawGlyph getRaw(char)
- RawGlyph getRaw(int)
- void lambda$reload$2(List,Set,int)
```

</details>

<details>
<summary>
net.minecraft.client.gui.font.TextFieldHelper
</summary>

```diff
- boolean isSelecting()
- Consumer createClipboardSetter(Minecraft)
- int clampToMsgLength(int)
- String deleteSelection(String)
- String getClipboardContents(Minecraft)
+ String getSelected()
- String getSelected(String)
- String lambda$createClipboardGetter$0(Minecraft)
- Supplier createClipboardGetter(Minecraft)
+ void <init>(Minecraft,Supplier,Consumer,int)
- void <init>(Supplier,Consumer,Supplier,Consumer,Predicate)
- void copy()
- void cut()
+ void deleteSelection()
- void insertText(String,String)
- void lambda$createClipboardSetter$1(Minecraft,String)
- void moveByChars(int,boolean)
- void moveByChars(int)
- void moveByWords(int,boolean)
- void moveByWords(int)
- void paste()
- void removeCharsFromCursor(int)
- void resetSelectionIfNeeded(boolean)
- void selectAll()
- void setClipboardContents(Minecraft,String)
- void setCursorPos(int,boolean)
- void setCursorPos(int)
- void setEnd(boolean)
- void setSelectionPos(int)
- void setSelectionRange(int,int)
- void setStart(boolean)
```

</details>



<details>
<summary>
net.minecraft.client.gui.font.providers.BitmapProvider
</summary>

```diff
- IntSet getSupportedGlyphs()
+ RawGlyph getGlyph(char)
- RawGlyph getGlyph(int)
+ void <init>(NativeImage,Char2ObjectMap)
- void <init>(NativeImage,Int2ObjectMap,BitmapProvider$1)
- void <init>(NativeImage,Int2ObjectMap)
```

</details>


<details>
<summary>
net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
</summary>

```diff
- IntSet getSupportedGlyphs()
+ RawGlyph getGlyph(char)
- RawGlyph getGlyph(int)
+ ResourceLocation getSheetLocation(char)
- ResourceLocation getSheetLocation(int)
```

</details>



<details>
<summary>
net.minecraft.client.gui.screens.AlertScreen
</summary>

```diff
- void <init>(Runnable,Component,Component,Component)
+ void <init>(Runnable,Component,Component,String)
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.ChatScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ConfirmLinkScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ConnectScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen
</summary>

```diff
- Component createGeneratorString(int)
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.DeathScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.DirectJoinServerScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.EditServerScreen
</summary>

```diff
- Component createServerButtonText(ServerData$ServerPackStatus)
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.GenericDirtMessageScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
</summary>

```diff
+ void render(int,int,int,int,int,int,int,boolean,float)
- void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LoadingOverlay
</summary>

```diff
+ void drawProgressBar(int,int,int,int,float)
- void drawProgressBar(PoseStack,int,int,int,int,float)
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.MouseSettingsScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen
</summary>

```diff
- void preset(Component,ItemLike,Biome,List,FlatLayerInfo[])
+ void preset(String,ItemLike,Biome,List,FlatLayerInfo[])
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.ProgressScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.Screen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderBackground()
+ void renderBackground(int)
- void renderBackground(PoseStack,int)
- void renderBackground(PoseStack)
+ void renderComponentHoverEffect(Component,int,int)
- void renderComponentHoverEffect(PoseStack,Component,int,int)
+ void renderTooltip(ItemStack,int,int)
+ void renderTooltip(List,int,int)
- void renderTooltip(PoseStack,Component,int,int)
- void renderTooltip(PoseStack,ItemStack,int,int)
- void renderTooltip(PoseStack,List,int,int)
+ void renderTooltip(String,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.SkinCustomizationScreen
</summary>

```diff
- Component getMessage(PlayerModelPart)
+ String getMessage(PlayerModelPart)
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.TitleScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.WinScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
</summary>

```diff
+ void render(int,int,int,int,int,int,int,boolean,float)
- void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
</summary>

```diff
+ void renderBackground()
- void renderBackground(PoseStack)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementTab
</summary>

```diff
- Component getTitle()
+ String getTitle()
+ void drawContents()
- void drawContents(PoseStack)
+ void drawTab(int,int,boolean)
- void drawTab(PoseStack,int,int,boolean)
+ void drawTooltips(int,int,int,int)
- void drawTooltips(PoseStack,int,int,int,int)
```

</details>





<details>
<summary>
net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
</summary>

```diff
- MutableComponent createNarrationMessage()
+ String getNarrationMessage()
- void <init>(ControlList$KeyEntry,int,int,int,int,Component,Button$OnPress,ControlList,KeyMapping,Component)
+ void <init>(ControlList$KeyEntry,int,int,int,int,String,Button$OnPress,ControlList,KeyMapping)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.controls.ControlsScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderLabels(int,int)
- void renderLabels(PoseStack,int,int)
- void renderSlot(PoseStack,Slot)
+ void renderSlot(Slot)
+ void renderTooltip(int,int)
- void renderTooltip(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AnvilScreen
</summary>

```diff
+ void renderFg(int,int,float)
- void renderFg(PoseStack,int,int,float)
+ void renderLabels(int,int)
- void renderLabels(PoseStack,int,int)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
</summary>

```diff
+ void renderToolTip(int,int)
- void renderToolTip(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
</summary>

```diff
+ void renderButton(int,int,float)
- void renderButton(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
</summary>

```diff
+ int access$000(BookEditScreen$Pos2i)
+ int access$002(BookEditScreen$Pos2i,int)
+ int access$100(BookEditScreen$Pos2i)
+ int access$102(BookEditScreen$Pos2i,int)
+ void <init>(BookEditScreen,int,int)
+ void <init>(BookEditScreen)
- void <init>(int,int)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.inventory.BrewingStandScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderBg(float,int,int)
- void renderBg(PoseStack,float,int,int)
+ void renderLabels(int,int)
- void renderLabels(PoseStack,int,int)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.inventory.ContainerScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderBg(float,int,int)
- void renderBg(PoseStack,float,int,int)
+ void renderLabels(int,int)
- void renderLabels(PoseStack,int,int)
```

</details>



<details>
<summary>
net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderBackgrounds(int,int,Iterable)
- void renderBackgrounds(PoseStack,int,int,Iterable)
+ void renderEffects()
- void renderEffects(PoseStack)
+ void renderIcons(int,int,Iterable)
- void renderIcons(PoseStack,int,int,Iterable)
+ void renderLabels(int,int,Iterable)
- void renderLabels(PoseStack,int,int,Iterable)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.EnchantmentScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderBg(float,int,int)
- void renderBg(PoseStack,float,int,int)
+ void renderLabels(int,int)
- void renderLabels(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.GrindstoneScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderBg(float,int,int)
- void renderBg(PoseStack,float,int,int)
+ void renderLabels(int,int)
- void renderLabels(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderBg(float,int,int)
- void renderBg(PoseStack,float,int,int)
+ void renderLabels(int,int)
- void renderLabels(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderBg(float,int,int)
- void renderBg(PoseStack,float,int,int)
+ void renderFg(int,int,float)
- void renderFg(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
</summary>

```diff
- void <init>(JigsawBlockEditScreen,int,int,int,int,Component,double)
+ void <init>(JigsawBlockEditScreen,int,int,int,int,String,double)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
</summary>

```diff
+ void renderToolTip(int,int)
- void renderToolTip(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.PageButton
</summary>

```diff
+ void renderButton(int,int,float)
- void renderButton(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.SignEditScreen
</summary>

```diff
- boolean lambda$init$4(String)
+ String lambda$init$1()
- String lambda$init$2()
+ String lambda$render$3(Component)
+ void lambda$init$0(Button)
- void lambda$init$1(Button)
+ void lambda$init$2(String)
- void lambda$init$3(String)
- void lambda$new$0(String[])
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.SafetyScreen
</summary>

```diff
- void <clinit>()
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
</summary>

```diff
+ void render(int,int,int,int,int,int,int,boolean,float)
- void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
</summary>

```diff
- Component getFilterButtonTooltip()
+ String getFilterButtonTooltip()
+ void renderGhostRecipe(int,int,boolean,float)
- void renderGhostRecipe(PoseStack,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.GhostRecipe
</summary>

```diff
+ void render(Minecraft,int,int,boolean,float)
- void render(PoseStack,Minecraft,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
</summary>

```diff
+ void nineInchSprite(int,int,int,int,int,int)
- void nineInchSprite(PoseStack,int,int,int,int,int,int)
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
</summary>

```diff
- Component getFilterButtonTooltip()
+ String getFilterButtonTooltip()
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
+ void renderGhostRecipe(int,int,boolean,float)
- void renderGhostRecipe(PoseStack,int,int,boolean,float)
+ void renderGhostRecipeTooltip(int,int,int,int)
- void renderGhostRecipeTooltip(PoseStack,int,int,int,int)
+ void renderTooltip(int,int,int,int)
- void renderTooltip(PoseStack,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
</summary>

```diff
+ void renderButton(int,int,float)
- void renderButton(PoseStack,int,int,float)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
</summary>

```diff
- Component getRecipeFilterName()
+ String getRecipeFilterName()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.resourcepacks.ResourcePackSelectScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.resourcepacks.lists.ResourcePackList$ResourcePackEntry
</summary>

```diff
+ String getDescription()
+ String getName()
+ void render(int,int,int,int,int,int,int,boolean,float)
- void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>


<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$1
</summary>

```diff
- MutableComponent createNarrationMessage()
+ String getNarrationMessage()
- void <init>(CreateWorldScreen,Font,int,int,int,int,Component)
+ void <init>(CreateWorldScreen,Font,int,int,int,int,String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$3
</summary>

```diff
- Component getMessage()
+ String getMessage()
+ String getNarrationMessage()
- void <init>(CreateWorldScreen,int,int,int,int,Component,Button$OnPress)
+ void <init>(CreateWorldScreen,int,int,int,int,String,Button$OnPress)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$5
</summary>

```diff
- Component getMessage()
- MutableComponent createNarrationMessage()
+ String getMessage()
+ String getNarrationMessage()
- void <init>(CreateWorldScreen,int,int,int,int,Component,Button$OnPress)
+ void <init>(CreateWorldScreen,int,int,int,int,String,Button$OnPress)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$7
</summary>

```diff
- Component getMessage()
+ void <clinit>()
- void <init>(CreateWorldScreen,int,int,int,int,Component,Button$OnPress)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditWorldScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
</summary>

```diff
+ void render(int,int,float)
- void render(PoseStack,int,int,float)
- void setToolTip(List)
+ void setToolTip(String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
</summary>

```diff
+ void render(int,int,int,int,int,int,int,boolean,float)
- void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.spectator.PlayerMenuItem
</summary>

```diff
+ void renderIcon(float,int)
- void renderIcon(PoseStack,float,int)
```

</details>

<details>
<summary>
net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
</summary>

```diff
+ void renderIcon(float,int)
- void renderIcon(PoseStack,float,int)
```

</details>


<details>
<summary>
net.minecraft.client.gui.spectator.categories.TeleportToPlayerMenuCategory
</summary>

```diff
+ void renderIcon(float,int)
- void renderIcon(PoseStack,float,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
</summary>

```diff
+ void renderIcon(float,int)
- void renderIcon(PoseStack,float,int)
```

</details>






<details>
<summary>
net.minecraft.client.map.Map
</summary>

```diff
- boolean access$302(Map,boolean)
+ boolean access$402(Map,boolean)
- boolean access$802(Map,boolean)
- double access$400(Map)
- double access$402(Map,double)
- double access$500(Map)
- double access$502(Map,double)
- double getNewScale()
+ int access$100(Map)
+ int access$102(Map,int)
+ int access$200(Map)
+ int access$300(Map)
+ int access$302(Map,int)
- int access$602(Map,int)
- int access$702(Map,int)
+ Layer access$500(Map)
- OptionalLong access$202(Map,OptionalLong)
+ String access$002(Map,String)
- String access$102(Map,String)
+ String access$802(Map,String)
- void <init>(int,int,double)
+ void <init>(int,int,int)
- void updateIndicators()
```

</details>
<details>
<summary>
net.minecraft.client.map.Map$2
</summary>

```diff
+ void mouseDragged(MouseEvent)
+ void mouseMoved(MouseEvent)
- void mouseWheelMoved(MouseWheelEvent)
```

</details>
















<details>
<summary>
net.minecraft.commands.Commands
</summary>

```diff
- Style lambda$performCommand$2(String,Style)
- Style lambda$performCommand$3(MutableComponent,Style)
+ void lambda$performCommand$2(String,Style)
+ void lambda$performCommand$3(Component,Style)
```

</details>
<details>
<summary>
net.minecraft.commands.SharedSuggestionProvider
</summary>

```diff
+ boolean matches(String,String)
- boolean matchesSubStr(String,String)
```

</details>




















<details>
<summary>
net.minecraft.commands.arguments.ResourceLocationArgument
</summary>

```diff
- Attribute getAttribute(CommandContext,String)
- CommandSyntaxException lambda$getAttribute$5(ResourceLocation)
+ CommandSyntaxException lambda$getRecipe$3(ResourceLocation)
- CommandSyntaxException lambda$getRecipe$4(ResourceLocation)
- Message lambda$static$3(Object)
```

</details>




<details>
<summary>
net.minecraft.network.chat.NbtComponent$BlockNbtComponent
</summary>

```diff
- BaseComponent toMutable()
+ Component copy()
- MutableComponent toMutable()
- NbtComponent$BlockNbtComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.NbtComponent$StorageNbtComponent
</summary>

```diff
- BaseComponent toMutable()
+ Component copy()
- MutableComponent toMutable()
- NbtComponent$StorageNbtComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.SelectorComponent
</summary>

```diff
- BaseComponent toMutable()
+ Component copy()
+ Component resolve(CommandSourceStack,Entity,int)
- MutableComponent resolve(CommandSourceStack,Entity,int)
- MutableComponent toMutable()
+ SelectorComponent copy()
- SelectorComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.Style$1
</summary>

```diff
+ boolean isBold()
+ boolean isItalic()
+ boolean isObfuscated()
+ boolean isStrikethrough()
+ boolean isUnderlined()
+ ChatFormatting getColor()
+ ClickEvent getClickEvent()
+ HoverEvent getHoverEvent()
+ String getInsertion()
+ String getLegacyFormatCodes()
+ String toString()
+ Style copy()
+ Style flatCopy()
+ Style inheritFrom(Style)
+ Style setBold(Boolean)
+ Style setClickEvent(ClickEvent)
+ Style setColor(ChatFormatting)
+ Style setHoverEvent(HoverEvent)
+ Style setItalic(Boolean)
+ Style setObfuscated(Boolean)
+ Style setStrikethrough(Boolean)
+ Style setUnderlined(Boolean)
- void <clinit>()
+ void <init>()
```

</details>




<details>
<summary>
net.minecraft.server.MinecraftServer$1
</summary>

```diff
- void <init>()
+ void <init>(MinecraftServer)
```

</details>























































































































<details>
<summary>
net.minecraft.util.worldupdate.WorldUpgrader
</summary>

```diff
- void <init>(LevelStorageSource$LevelStorageAccess,DataFixer,WorldData,boolean)
+ void <init>(LevelStorageSource$LevelStorageAccess,LevelData,boolean)
```

</details>



























<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
+ int chunkRange()
- int clientTrackingRange()
- void <init>(EntityType$EntityFactory,MobCategory,boolean,boolean,boolean,boolean,int,int,EntityDimensions,int,int)
+ void <init>(EntityType$EntityFactory,MobCategory,boolean,boolean,boolean,boolean,int,int,EntityDimensions)
```

</details>




<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean canSpawnSoulSpeedParticle()
- boolean onSoulSpeedBlock()
+ void doSoulSpeedParticles()
- void spawnSoulSpeedParticle()
+ void updateSprintingState()
```

</details>












<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeMap
</summary>

```diff
- boolean hasAttribute(Attribute)
- boolean hasModifier(Attribute,UUID)
- double getModifierValue(Attribute,UUID)
```

</details>




































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean onSoulSpeedBlock()
+ Component decorateDisplayNameComponent(Component)
- MutableComponent decorateDisplayNameComponent(MutableComponent)
- Style lambda$decorateDisplayNameComponent$4(String,Style)
+ void lambda$decorateDisplayNameComponent$4(String,Style)
```

</details>











































































<details>
<summary>
net.minecraft.world.inventory.RecipeHolder
</summary>

```diff
+ void awardAndReset(Player)
- void awardUsedRecipes(Player)
```

</details>















































<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
+ Component lambda$expandBlockState$2(Component)
- Entity getEntityRepresentation()
- MutableComponent lambda$expandBlockState$2(MutableComponent)
- Style lambda$getDisplayName$3(Style)
+ void lambda$getDisplayName$3(CompoundTag,Style)
- void setEntityRepresentation(Entity)
+ void setFramed(ItemFrame)
```

</details>







<details>
<summary>
net.minecraft.world.item.RecordItem
</summary>

```diff
+ Component getDisplayName()
- MutableComponent getDisplayName()
```

</details>
















































































<details>
<summary>
net.minecraft.world.level.GameRules
</summary>

```diff
- GameRules copy()
- GameRules$Key register(String,GameRules$Category,GameRules$Type)
+ GameRules$Key register(String,GameRules$Type)
- GameRules$Value lambda$copy$6(Map$Entry)
- void <init>(Map)
- void assignCap(GameRules$Key,GameRules,MinecraftServer)
- void assignFrom(GameRules,MinecraftServer)
- void callVisitorCap(GameRules$GameRuleTypeVisitor,GameRules$Key,GameRules$Type)
+ void cap(GameRules$GameRuleTypeVisitor,GameRules$Key,GameRules$Type)
- void lambda$assignFrom$8(GameRules,MinecraftServer,GameRules$Key)
+ void lambda$visitGameRuleTypes$6(GameRules$GameRuleTypeVisitor,GameRules$Key,GameRules$Type)
- void lambda$visitGameRuleTypes$7(GameRules$GameRuleTypeVisitor,GameRules$Key,GameRules$Type)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$BooleanValue
</summary>

```diff
- GameRules$BooleanValue copy()
- GameRules$Value copy()
- void setFrom(GameRules$BooleanValue,MinecraftServer)
- void setFrom(GameRules$Value,MinecraftServer)
```

</details>



<details>
<summary>
net.minecraft.world.level.LevelSettings
</summary>

```diff
+ boolean isGenerateMapFeatures()
- boolean shouldGenerateMapFeatures()
- Difficulty getDifficulty()
- GameRules getGameRules()
- String getLevelName()
+ void <init>(LevelData)
+ void <init>(long,GameType,boolean,boolean,ChunkGeneratorProvider)
- void <init>(String,long,GameType,boolean,boolean,Difficulty,ChunkGeneratorProvider,GameRules)
- void <init>(String,long,GameType,boolean,boolean,Difficulty,ChunkGeneratorProvider)
```

</details>












<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ float getFitness(Biome$ClimateParameters)
+ Float lambda$getFitness$5(Biome$ClimateParameters,Biome$ClimateParameters)
- Object lambda$null$10(DynamicOps,Biome$SpawnerData)
+ Object lambda$null$11(DynamicOps,Biome$SpawnerData)
- Object lambda$null$5(DynamicOps,ConfiguredWorldCarver)
+ Object lambda$null$6(DynamicOps,ConfiguredWorldCarver)
- Object lambda$null$7(DynamicOps,ConfiguredFeature)
+ Object lambda$null$8(DynamicOps,ConfiguredFeature)
- Optional getBackgroundMusic()
+ Pair lambda$serialize$10(DynamicOps,Map$Entry)
- Pair lambda$serialize$11(DynamicOps,Map$Entry)
+ Pair lambda$serialize$12(DynamicOps,Map$Entry)
- Pair lambda$serialize$6(DynamicOps,Map$Entry)
+ Pair lambda$serialize$7(DynamicOps,Map$Entry)
- Pair lambda$serialize$8(DynamicOps,Map$Entry)
- Stream optimalParameters()
```

</details>






<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects
</summary>

```diff
- Optional getBackgroundMusic()
+ void <init>(int,int,int,Optional,Optional,Optional,Optional,BiomeSpecialEffects$1)
- void <init>(int,int,int,Optional,Optional,Optional,Optional,Optional,BiomeSpecialEffects$1)
- void <init>(int,int,int,Optional,Optional,Optional,Optional,Optional)
+ void <init>(int,int,int,Optional,Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
</summary>

```diff
- BiomeSpecialEffects$Builder backgroundMusic(Music)
```

</details>























<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
+ Float lambda$getNoiseBiome$0(Biome$ClimateParameters,Biome)
- Float lambda$getNoiseBiome$0(Biome$ClimateParameters,Pair)
```

</details>






















<details>
<summary>
net.minecraft.world.level.block.AbstractSkullBlock
</summary>

```diff
- boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
```

</details>












<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ Component getName()
- MutableComponent getName()
```

</details>













<details>
<summary>
net.minecraft.world.level.block.CocoaBlock
</summary>

```diff
- boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
```

</details>



































































<details>
<summary>
net.minecraft.world.level.block.RespawnAnchorBlock
</summary>

```diff
- boolean canSetSpawn(Level)
```

</details>








































<details>
<summary>
net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
</summary>

```diff
- List getRecipesToAwardAndPopExperience(Level,Vec3)
+ void awardAndReset(Player)
+ void awardResetAndExperience(Player)
- void awardUsedRecipes(Player)
- void awardUsedRecipesAndPopExperience(Player)
- void createExperience(Level,Vec3,int,float)
+ void createExperience(Player,int,float)
+ void lambda$awardResetAndExperience$1(List,Player,Object2IntMap$Entry,Recipe)
- void lambda$getRecipesToAwardAndPopExperience$1(List,Level,Vec3,Object2IntMap$Entry,Recipe)
```

</details>





































































<details>
<summary>
net.minecraft.world.level.border.WorldBorder
</summary>

```diff
- void <clinit>()
- void applySettings(WorldBorder$Settings)
+ void readBorderData(LevelData)
+ void saveWorldBorderData(LevelData)
- WorldBorder$Settings createSettings()
```

</details>


































<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
+ boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,SmallTreeConfiguration)
- boolean isAirOrLeaves(LevelSimulatedReader,BlockPos)
- boolean isBlockWater(LevelSimulatedReader,BlockPos)
- boolean isFree(LevelSimulatedReader,BlockPos)
- boolean isGrassOrDirtOrFarmland(LevelSimulatedReader,BlockPos)
- boolean isReplaceablePlant(LevelSimulatedReader,BlockPos)
- boolean isVine(LevelSimulatedReader,BlockPos)
- boolean lambda$isAirOrLeaves$3(BlockState)
- boolean lambda$isBlockWater$2(BlockState)
- boolean lambda$isFree$0(BlockState)
- boolean lambda$isGrassOrDirtOrFarmland$4(BlockState)
- boolean lambda$isReplaceablePlant$5(BlockState)
- boolean lambda$isVine$1(BlockState)
- boolean place(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BlockPos,TreeConfiguration)
- boolean validTreePos(LevelSimulatedRW,BlockPos)
- DiscreteVoxelShape updateLeaves(LevelAccessor,BoundingBox,Set,Set)
+ void lambda$doPlace$0(SmallTreeConfiguration,LevelSimulatedRW,Random,int,int,Set,BlockPos,Integer)
- void lambda$doPlace$6(TreeConfiguration,LevelSimulatedRW,Random,int,int,int,Set,FoliagePlacer$FoliageAttachment)
- void lambda$place$7(LevelAccessor,Random,List,List,Set,BoundingBox,TreeDecorator)
- void setBlock(LevelWriter,BlockPos,BlockState)
- void setBlockKnownShape(LevelWriter,BlockPos,BlockState)
- void simulate(FeatureSimulator,Random,BlockPos,FeatureConfiguration)
- void simulate(FeatureSimulator,Random,BlockPos,TreeConfiguration)
```

</details>































<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
</summary>

```diff
+ TreeConfiguration$TreeConfigurationBuilder baseHeight(int)
- TreeConfiguration$TreeConfigurationBuilder heightmap(Heightmap$Types)
- TreeConfiguration$TreeConfigurationBuilder ignoreVines()
- TreeConfiguration$TreeConfigurationBuilder maxWaterDepth(int)
- void <init>(BlockStateProvider,BlockStateProvider,FoliagePlacer,TrunkPlacer,FeatureSize)
+ void <init>(BlockStateProvider,BlockStateProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
</summary>

```diff
- boolean shouldSkipLocationSigned(Random,int,int,int,int,boolean)
- int foliageRadius(Random,int)
- int offset(Random)
- void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set)
+ void placeLeaf(LevelSimulatedRW,Random,BlockPos,SmallTreeConfiguration,Set)
+ void placeLeavesRow(LevelSimulatedRW,Random,SmallTreeConfiguration,BlockPos,int,int,int,Set)
- void placeLeavesRow(LevelSimulatedRW,Random,TreeConfiguration,BlockPos,int,Set,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
+ Map placeTrunk(LevelSimulatedRW,Random,int,BlockPos,int,Set,BoundingBox,SmallTreeConfiguration)
```

</details>








































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
</summary>

```diff
+ void <init>(MinecraftServer,File,DataFixer)
- void <init>(MinecraftServer,LevelStorageSource$LevelStorageAccess,DataFixer)
```

</details>
</details>