## Comparison with [20w16a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w16a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">20w16a</th><th>20w17a</th></tr><tr><td>World version</td><td><pre>2526</pre></td><td><pre>2529</pre></td></tr><tr><td>Protocol version</td><td><pre>712</pre></td><td><pre>713</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ com.ibm.icu:icu4j V66.1
- com.ibm.icu:icu4j-core-mojang V51.2
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w16a</th><th>20w17a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ feature_size_type.txt
```

</details>
<details>
<summary>
block
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
feature
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
foliage_placer_type
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
item
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
sound_event
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
trunk_placer_type
</summary>

```diff
+ minecraft:dark_oak_trunk_placer
+ minecraft:fancy_trunk_placer
+ minecraft:giant_trunk_placer
+ minecraft:mega_jungle_trunk_placer
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
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
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- soul_fire_lantern.json
- soul_fire_torch.json
- soul_fire_wall_torch.json
+ soul_lantern.json
+ soul_torch.json
+ soul_wall_torch.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ attribute.txt
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
- soul_fire_lantern.json
- soul_fire_torch.json
+ soul_lantern.json
+ soul_torch.json
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
<br/>
<table>
<tr><th>Name</th><th>20w16a</th><th>20w17a</th></tr>
<tr><th align="left"><div style="width:290px">container.upgrade</div></th><td>Upgrade</td><td>Upgrade gear</td></tr>
<tr><th align="left"><div style="width:290px">jigsaw_block.levels</div></th><td>Levels: </td><td>Levels: %s</td></tr>
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
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:uuid
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
- net.minecraft.package-info
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
+ XXX.chunk.storage.ChunkSerializer
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$1
+ XXX.chunk.storage.IOWorker$PendingStore
- XXX.chunk.storage.OldChunkStorage
+ XXX.chunk.storage.OldChunkStorage$OldLevelChunk
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
+ XXX.commands.arguments.package-info
- XXX.commands.arguments.UuidArgument
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.EntityDataAccessor
- XXX.commands.data.EntityDataAccessor$1
+ XXX.commands.data.package-info
+ XXX.commands.data.StorageDataAccessor
- XXX.commands.data.StorageDataAccessor$1
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
- XXX.core.dispenser.DispenseItemBehavior$23
+ XXX.core.dispenser.DispenseItemBehavior$24
- XXX.core.dispenser.DispenseItemBehavior$25
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$7$1
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$8$1
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
+ XXX.core.dispenser.ShearsDispenseItemBehavior
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
+ XXX.data.tags.TagsProvider$1
- XXX.data.tags.TagsProvider$TagAppender
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.fixes.BedBlockEntityInjecter
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehivePoiRenameFix
- XXX.datafix.fixes.BiomeFix
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
- XXX.dimension.end.package-info
+ XXX.dimension.end.TheEndDimension
+ XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ XXX.feature.configurations.SmallTreeConfiguration
- XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.LegacySinglePoolElement
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
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
- XXX.layer.traits.AreaTransformer0
+ XXX.layer.traits.AreaTransformer1
- XXX.layer.traits.AreaTransformer2
+ XXX.layer.traits.BishopTransformer
- XXX.layer.traits.C0Transformer
+ XXX.layer.traits.C1Transformer
- XXX.layer.traits.CastleTransformer
+ XXX.layer.traits.DimensionOffset0Transformer
- XXX.layer.traits.DimensionOffset1Transformer
+ XXX.layer.traits.DimensionTransformer
+ XXX.layer.traits.package-info
- XXX.layer.traits.PixelTransformer
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkBiomeContainer
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGeneratorFactory
- XXX.level.chunk.ChunkGeneratorType
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.FeatureAccess
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.OldDataLayer
- XXX.level.chunk.package-info
+ XXX.level.chunk.Palette
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.ProtoTickList
+ XXX.level.chunk.UpgradeData
- XXX.level.chunk.UpgradeData$1
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
+ XXX.level.dimension.Dimension
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.NetherDimension
- XXX.level.dimension.NetherDimension$1
+ XXX.level.dimension.NormalDimension
+ XXX.level.dimension.package-info
- XXX.level.levelgen.ChunkGeneratorProvider
+ XXX.level.levelgen.ChunkGeneratorSettings
- XXX.level.levelgen.DebugGeneratorSettings
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.NetherGeneratorSettings
+ XXX.level.levelgen.NetherLevelSource
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.OverworldGeneratorSettings
- XXX.level.levelgen.OverworldLevelSource
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.TheEndGeneratorSettings
- XXX.level.levelgen.TheEndLevelSource
+ XXX.level.levelgen.WorldgenRandom
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.FlatDataLayer
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
+ XXX.level.material.Fluids
+ XXX.level.material.FluidState
- XXX.level.material.FluidStateImpl
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.TurtleNodeEvaluator
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SaveDataDirtyRunnable
+ XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelStorage
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerIO
- XXX.level.storage.PrimaryLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$1
- XXX.level.timers.TimerQueue$Event
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.NoneCarverConfiguration
+ XXX.levelgen.carver.package-info
- XXX.levelgen.carver.UnderwaterCanyonWorldCarver
+ XXX.levelgen.carver.UnderwaterCaveWorldCarver
- XXX.levelgen.carver.WorldCarver
- XXX.levelgen.feature.AbstractFlowerFeature
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.AbstractTreeFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BastionBridgePools
- XXX.levelgen.feature.BastionFeature
+ XXX.levelgen.feature.BastionFeature$FeatureStart
- XXX.levelgen.feature.BastionHoglinStablePools
+ XXX.levelgen.feature.BastionHousingUnitsPools
- XXX.levelgen.feature.BastionPieces
+ XXX.levelgen.feature.BastionPieces$BastionPiece
- XXX.levelgen.feature.BastionSharedPools
+ XXX.levelgen.feature.BastionTreasureRoomPools
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.FancyTreeFeature
+ XXX.levelgen.feature.GroundBushFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IcePatchFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.IglooFeature
- XXX.levelgen.feature.IglooFeature$FeatureStart
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.MegaJungleTreeFeature
+ XXX.levelgen.feature.MegaTreeFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.levelgen.synth.SurfaceNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.CompositeEntryBase$Serializer
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.DynamicLoot$1
+ XXX.loot.entries.DynamicLoot$Serializer
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EmptyLootItem$1
- XXX.loot.entries.EmptyLootItem$Serializer
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootItem$1
+ XXX.loot.entries.LootItem$Serializer
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntries$Serializer
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.LootTableReference$1
+ XXX.loot.entries.LootTableReference$Serializer
+ XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
- XXX.loot.entries.TagEntry$Serializer
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$1
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.ApplyExplosionDecay$1
- XXX.loot.functions.ApplyExplosionDecay$Serializer
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$1
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$1
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.CopyNameFunction$Serializer
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$1
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$DataSource
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Serializer
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$1
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$1
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$1
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$1
- XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$1
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunction$Serializer
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctions$Serializer
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$1
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$1
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemCountFunction$1
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$1
- XXX.loot.functions.SetItemDamageFunction$Serializer
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$1
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$1
+ XXX.loot.functions.SetNbtFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$1
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$1
- XXX.loot.functions.SmeltItemFunction$Serializer
+ XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$1
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$1
- XXX.loot.predicates.AlternativeLootItemCondition$Builder
+ XXX.loot.predicates.AlternativeLootItemCondition$Serializer
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.BonusLevelTableCondition$1
- XXX.loot.predicates.BonusLevelTableCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$1
- XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$1
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$1
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemCondition$Serializer
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditions$Serializer
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemEntityPropertyCondition$1
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$1
- XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$1
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$1
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
+ XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
- XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.minecraft.commands.package-info
- XXX.minecraft.core.AxisCycle
+ XXX.minecraft.core.AxisCycle$1
- XXX.minecraft.core.AxisCycle$2
+ XXX.minecraft.core.AxisCycle$3
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$4
- XXX.minecraft.core.BlockPos$MutableBlockPos
+ XXX.minecraft.core.BlockSource
- XXX.minecraft.core.BlockSourceImpl
+ XXX.minecraft.core.Cursor3D
- XXX.minecraft.core.DefaultedRegistry
+ XXX.minecraft.core.Direction
- XXX.minecraft.core.Direction$1
+ XXX.minecraft.core.Direction$Axis
- XXX.minecraft.core.Direction$Axis$1
+ XXX.minecraft.core.Direction$Axis$2
- XXX.minecraft.core.Direction$Axis$3
+ XXX.minecraft.core.Direction$AxisDirection
- XXX.minecraft.core.Direction$Plane
+ XXX.minecraft.core.Direction8
- XXX.minecraft.core.FrontAndTop
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
+ XXX.minecraft.obfuscate.DontObfuscateOrShrink
- XXX.minecraft.obfuscate.KeepAfterObfuscation
+ XXX.minecraft.obfuscate.package-info
- XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.package-info
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
- XXX.minecraft.tags.StaticTagHelper
+ XXX.minecraft.tags.StaticTagHelper$1
- XXX.minecraft.tags.StaticTagHelper$Wrapper
+ XXX.minecraft.tags.SynchronizableTagCollection
- XXX.minecraft.tags.Tag
+ XXX.minecraft.tags.Tag$1
- XXX.minecraft.tags.Tag$Builder
+ XXX.minecraft.tags.Tag$BuilderEntry
- XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$Entry
- XXX.minecraft.tags.Tag$Named
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.TagCollection
+ XXX.minecraft.tags.TagManager
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
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.FrameTimer
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.InsensitiveStringMap
- XXX.minecraft.util.IntRange
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LimitedCapacityList
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RewindableStream
+ XXX.minecraft.util.RewindableStream$1
- XXX.minecraft.util.Serializable
+ XXX.minecraft.util.Serializer
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
- XXX.minecraft.world.package-info
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
+ XXX.network.chat.BaseComponent
- XXX.network.chat.ChatType
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.ContextAwareComponent
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.KeybindComponent
+ XXX.network.chat.package-info
- XXX.network.chat.TextComponent
+ XXX.network.chat.TranslatableComponent
- XXX.network.chat.TranslatableFormatException
- XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$10
+ XXX.network.syncher.EntityDataSerializers$11
- XXX.network.syncher.EntityDataSerializers$12
+ XXX.network.syncher.EntityDataSerializers$13
- XXX.network.syncher.EntityDataSerializers$14
+ XXX.network.syncher.EntityDataSerializers$15
- XXX.network.syncher.EntityDataSerializers$16
+ XXX.network.syncher.EntityDataSerializers$17
- XXX.network.syncher.EntityDataSerializers$18
+ XXX.network.syncher.EntityDataSerializers$19
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.EntityDataSerializers$8
+ XXX.network.syncher.EntityDataSerializers$9
- XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.newbiome.area.Area
- XXX.newbiome.area.AreaFactory
+ XXX.newbiome.area.LazyArea
- XXX.newbiome.area.package-info
+ XXX.newbiome.context.BigContext
- XXX.newbiome.context.Context
+ XXX.newbiome.context.LazyAreaContext
- XXX.newbiome.context.package-info
+ XXX.newbiome.layer.AddDeepOceanLayer
- XXX.newbiome.layer.AddEdgeLayer
+ XXX.newbiome.layer.AddEdgeLayer$CoolWarm
- XXX.newbiome.layer.AddEdgeLayer$HeatIce
+ XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- XXX.newbiome.layer.AddIslandLayer
+ XXX.newbiome.layer.AddMushroomIslandLayer
- XXX.newbiome.layer.AddSnowLayer
+ XXX.newbiome.layer.BiomeEdgeLayer
- XXX.newbiome.layer.BiomeInitLayer
+ XXX.newbiome.layer.IslandLayer
- XXX.newbiome.layer.Layer
+ XXX.newbiome.layer.Layers
- XXX.newbiome.layer.OceanLayer
+ XXX.newbiome.layer.OceanMixerLayer
+ XXX.newbiome.layer.package-info
- XXX.newbiome.layer.RareBiomeLargeLayer
+ XXX.newbiome.layer.RareBiomeSpotLayer
- XXX.newbiome.layer.RegionHillsLayer
+ XXX.newbiome.layer.RemoveTooMuchOceanLayer
- XXX.newbiome.layer.RiverInitLayer
+ XXX.newbiome.layer.RiverLayer
- XXX.newbiome.layer.RiverMixerLayer
+ XXX.newbiome.layer.ShoreLayer
- XXX.newbiome.layer.SmoothLayer
+ XXX.newbiome.layer.ZoomLayer
- XXX.newbiome.layer.ZoomLayer$1
- XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.package-info
- XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
+ XXX.packs.repository.UnopenedPack
- XXX.packs.repository.UnopenedPack$Position
+ XXX.packs.repository.UnopenedPack$UnopenedPackConstructor
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$1
+ XXX.packs.resources.ProfiledReloadInstance$State
+ XXX.packs.resources.ReloadableResourceManager
- XXX.packs.resources.ReloadInstance
- XXX.packs.resources.Resource
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadableResourceManager
+ XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
- XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
+ XXX.packs.resources.SimpleResource
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
+ XXX.phys.shapes.IntPointRange
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.phys.shapes.WorldRegionIndirectVoxelShape
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
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquippedItemPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket
+ XXX.protocol.game.ClientboundSetScorePacket
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
+ XXX.protocol.game.package-info
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
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundRecipeBookUpdatePacket
- XXX.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
+ XXX.protocol.game.ServerboundRenameItemPacket
- XXX.protocol.game.ServerboundResourcePackPacket
+ XXX.protocol.game.ServerboundResourcePackPacket$Action
- XXX.protocol.game.ServerboundSeenAdvancementsPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSignUpdatePacket
+ XXX.protocol.game.ServerboundSwingPacket
- XXX.protocol.game.ServerboundTeleportToEntityPacket
+ XXX.protocol.game.ServerboundUseItemOnPacket
- XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.protocol.status.ServerStatusPacketListener
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.selector.options.EntitySelectorOptions
+ XXX.selector.options.EntitySelectorOptions$1
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DebugMobSpawningCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
- XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
- XXX.server.commands.GameModeCommand
+ XXX.server.commands.GameRuleCommand
- XXX.server.commands.GameRuleCommand$1
+ XXX.server.commands.GiveCommand
- XXX.server.commands.HelpCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateBiomeCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.package-info
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ReplaceItemCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.SeedCommand
- XXX.server.commands.SetBlockCommand
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpectateCommand
+ XXX.server.commands.SpreadPlayersCommand
- XXX.server.commands.SpreadPlayersCommand$Position
+ XXX.server.commands.StopCommand
- XXX.server.commands.StopSoundCommand
+ XXX.server.commands.SummonCommand
- XXX.server.commands.TagCommand
+ XXX.server.commands.TeamCommand
- XXX.server.commands.TeamMsgCommand
+ XXX.server.commands.TeleportCommand
- XXX.server.commands.TeleportCommand$LookAt
+ XXX.server.commands.TellRawCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TriggerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
+ XXX.server.dedicated.DedicatedPlayerList
- XXX.server.dedicated.DedicatedServer
+ XXX.server.dedicated.DedicatedServer$1
- XXX.server.dedicated.DedicatedServer$2
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
+ XXX.server.dedicated.ServerWatchdog
- XXX.server.dedicated.ServerWatchdog$1
+ XXX.server.dedicated.Settings
- XXX.server.dedicated.Settings$1
+ XXX.server.dedicated.Settings$MutableValue
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$1
- XXX.server.level.ChunkHolder$ChunkLoadingFailure
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
- XXX.server.level.ChunkHolder$FullChunkStatus
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$1
+ XXX.server.level.ChunkMap$2
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$1
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Message
- XXX.server.level.ChunkTaskPriorityQueueSorter$Release
+ XXX.server.level.ChunkTracker
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DerivedServerLevel
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FeatureSimulator
- XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$1
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.WorldGenRegion
+ XXX.server.level.WorldGenTickList
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
+ XXX.server.network.ServerConnectionListener
- XXX.server.network.ServerConnectionListener$1
+ XXX.server.network.ServerConnectionListener$2
- XXX.server.network.ServerConnectionListener$LatencySimulator
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.packs.AbstractResourcePack
- XXX.server.packs.FileResourcePack
+ XXX.server.packs.FolderResourcePack
- XXX.server.packs.Pack
+ XXX.server.packs.package-info
+ XXX.server.packs.PackType
- XXX.server.packs.ResourcePackFileNotFoundException
+ XXX.server.packs.VanillaPack
+ XXX.server.players.BanListEntry
- XXX.server.players.GameProfileCache
+ XXX.server.players.GameProfileCache$1
- XXX.server.players.GameProfileCache$2
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.GameProfileCache$Serializer
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.storage.loot.BinomialDistributionGenerator
+ XXX.storage.loot.BinomialDistributionGenerator$Serializer
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ConstantIntValue
- XXX.storage.loot.ConstantIntValue$Serializer
+ XXX.storage.loot.IntLimiter
- XXX.storage.loot.IntLimiter$1
+ XXX.storage.loot.IntLimiter$Serializer
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$1
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$DynamicDrop
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$EntityTarget$Serializer
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$1
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$1
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.LootTable$Serializer
+ XXX.storage.loot.LootTables
- XXX.storage.loot.package-info
- XXX.storage.loot.PredicateManager
+ XXX.storage.loot.RandomIntGenerator
- XXX.storage.loot.RandomIntGenerators
+ XXX.storage.loot.RandomValueBounds
- XXX.storage.loot.RandomValueBounds$Serializer
+ XXX.storage.loot.ValidationContext
- XXX.storage.threaded.package-info
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
- XXX.world.level.GameRules$Category
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameRules$VisitorCaller
- XXX.world.level.package-info
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.PosAndRot
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- XXX.arguments.blocks.BlockInput
+ XXX.arguments.blocks.BlockPredicateArgument
- XXX.arguments.blocks.BlockPredicateArgument$1
+ XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
- XXX.arguments.blocks.BlockPredicateArgument$Result
+ XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
- XXX.arguments.blocks.BlockStateArgument
+ XXX.arguments.blocks.BlockStateParser
- XXX.arguments.blocks.package-info
+ XXX.arguments.coordinates.BlockPosArgument
- XXX.arguments.coordinates.ColumnPosArgument
+ XXX.arguments.coordinates.Coordinates
- XXX.arguments.coordinates.LocalCoordinates
+ XXX.arguments.coordinates.package-info
+ XXX.arguments.coordinates.RotationArgument
- XXX.arguments.coordinates.SwizzleArgument
+ XXX.arguments.coordinates.Vec2Argument
- XXX.arguments.coordinates.Vec3Argument
+ XXX.arguments.coordinates.WorldCoordinate
- XXX.arguments.coordinates.WorldCoordinates
- XXX.arguments.item.FunctionArgument
+ XXX.arguments.item.FunctionArgument$1
- XXX.arguments.item.FunctionArgument$2
+ XXX.arguments.item.FunctionArgument$Result
- XXX.arguments.item.ItemArgument
+ XXX.arguments.item.ItemInput
- XXX.arguments.item.ItemParser
+ XXX.arguments.item.ItemPredicateArgument
- XXX.arguments.item.ItemPredicateArgument$ItemPredicate
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.ItemPredicateArgument$TagPredicate
+ XXX.arguments.item.package-info
+ XXX.arguments.selector.EntitySelector
- XXX.arguments.selector.EntitySelectorParser
- XXX.arguments.selector.package-info
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
+ XXX.block.statemap.package-info
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$1
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.OldChunkStorage
- XXX.chunk.storage.OldChunkStorage$OldLevelChunk
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.SectionStorage
- XXX.client.gui.Font$StringRenderOutput
+ XXX.client.gui.Gui
- XXX.client.gui.GuiComponent
+ XXX.client.gui.MapRenderer
- XXX.client.gui.MapRenderer$1
+ XXX.client.gui.MapRenderer$MapInstance
- XXX.client.map.Map$4
+ XXX.client.map.package-info
- XXX.client.model.AbstractZombieModel
+ XXX.client.model.AgeableListModel
- XXX.client.model.AnimationUtils
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.BatModel
+ XXX.client.model.BeeModel
- XXX.client.model.BlazeModel
+ XXX.client.model.BoatModel
- XXX.client.model.BookModel
+ XXX.client.model.CatModel
- XXX.client.model.ChestedHorseModel
+ XXX.client.model.ChickenModel
- XXX.client.model.CodModel
+ XXX.client.model.ColorableAgeableListModel
- XXX.client.model.ColorableListModel
+ XXX.client.model.CowModel
- XXX.client.model.CreeperModel
+ XXX.client.model.DolphinModel
- XXX.client.model.DrownedModel
+ XXX.client.model.ElytraModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FoxModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GuardianModel
- XXX.client.model.HeadedModel
+ XXX.client.model.HoglinModel
- XXX.client.model.HorseModel
+ XXX.client.model.HumanoidHeadModel
- XXX.client.model.HumanoidModel
+ XXX.client.model.HumanoidModel$1
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.ListModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
- XXX.client.model.MinecartModel
+ XXX.client.model.Model
- XXX.client.model.ModelUtils
+ XXX.client.model.OcelotModel
- XXX.client.model.package-info
- XXX.client.model.PandaModel
+ XXX.client.model.ParrotModel
- XXX.client.model.ParrotModel$1
+ XXX.client.model.ParrotModel$State
- XXX.client.model.PhantomModel
- XXX.client.model.PiglinModel
+ XXX.client.model.PigModel
+ XXX.client.model.PlayerModel
- XXX.client.model.PolarBearModel
+ XXX.client.model.PufferfishBigModel
- XXX.client.model.PufferfishMidModel
+ XXX.client.model.PufferfishSmallModel
- XXX.client.model.QuadrupedModel
+ XXX.client.model.RabbitModel
- XXX.client.model.RavagerModel
+ XXX.client.model.SalmonModel
- XXX.client.model.SheepFurModel
+ XXX.client.model.SheepModel
- XXX.client.model.ShieldModel
+ XXX.client.model.ShulkerBulletModel
- XXX.client.model.ShulkerModel
+ XXX.client.model.SilverfishModel
- XXX.client.model.SkeletonModel
+ XXX.client.model.SkullModel
- XXX.client.model.SlimeModel
+ XXX.client.model.SnowGolemModel
- XXX.client.model.SpiderModel
+ XXX.client.model.SquidModel
- XXX.client.model.StriderModel
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
- XXX.client.particle.PortalParticle$Provider
+ XXX.client.particle.ReversePortalParticle
- XXX.client.particle.ReversePortalParticle$1
+ XXX.client.particle.ReversePortalParticle$ReversePortalProvider
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
+ XXX.client.particle.WhiteAshParticle
- XXX.client.particle.WhiteAshParticle$Provider
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
+ XXX.client.resources.AssetIndex
- XXX.client.resources.ClientPackSource
+ XXX.client.resources.ClientPackSource$1
- XXX.client.resources.ClientPackSource$2
+ XXX.client.resources.DefaultClientResourcePack
- XXX.client.resources.DefaultPlayerSkin
+ XXX.client.resources.DirectAssetIndex
- XXX.client.resources.FoliageColorReloadListener
+ XXX.client.resources.GrassColorReloadListener
- XXX.client.resources.LegacyResourcePackAdapter
+ XXX.client.resources.LegacyStuffWrapper
- XXX.client.resources.MobEffectTextureManager
+ XXX.client.resources.PackAdapterV4
- XXX.client.resources.package-info
- XXX.client.resources.PaintingTextureManager
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$SkinTextureCallback
- XXX.client.resources.SplashManager
+ XXX.client.resources.TextureAtlasHolder
- XXX.client.resources.UnopenedResourcePack
- XXX.client.searchtree.MutableSearchTree
- XXX.client.searchtree.package-info
+ XXX.client.searchtree.ReloadableIdSearchTree
- XXX.client.searchtree.ReloadableIdSearchTree$IntersectionIterator
+ XXX.client.searchtree.ReloadableSearchTree
- XXX.client.searchtree.ReloadableSearchTree$MergingUniqueIterator
+ XXX.client.searchtree.SearchRegistry
- XXX.client.searchtree.SearchRegistry$Key
+ XXX.client.searchtree.SearchTree
- XXX.client.searchtree.SuffixArray
+ XXX.client.searchtree.SuffixArray$1
+ XXX.client.server.IntegratedPlayerList
- XXX.client.server.IntegratedServer
+ XXX.client.server.LanServer
- XXX.client.server.LanServerDetection
+ XXX.client.server.LanServerDetection$LanServerDetector
- XXX.client.server.LanServerDetection$LanServerList
+ XXX.client.server.LanServerPinger
- XXX.client.server.package-info
+ XXX.client.skins.package-info
- XXX.client.sounds.AudioStream
+ XXX.client.sounds.ChannelAccess
- XXX.client.sounds.ChannelAccess$ChannelHandle
+ XXX.client.sounds.LoopingAudioStream
- XXX.client.sounds.LoopingAudioStream$1
+ XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
- XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
+ XXX.client.sounds.MusicManager
- XXX.commands.arguments.package-info
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
+ XXX.commands.exceptions.package-info
+ XXX.commands.synchronization.ArgumentSerializer
- XXX.commands.synchronization.ArgumentTypes
+ XXX.commands.synchronization.ArgumentTypes$1
- XXX.commands.synchronization.ArgumentTypes$Entry
+ XXX.commands.synchronization.EmptyArgumentSerializer
- XXX.commands.synchronization.package-info
- XXX.commands.synchronization.SuggestionProviders
+ XXX.commands.synchronization.SuggestionProviders$Wrapper
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
- XXX.core.dispenser.AbstractProjectileDispenseBehavior
+ XXX.core.dispenser.BoatDispenseItemBehavior
- XXX.core.dispenser.DefaultDispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior$1
+ XXX.core.dispenser.DispenseItemBehavior$10
- XXX.core.dispenser.DispenseItemBehavior$11
+ XXX.core.dispenser.DispenseItemBehavior$12
- XXX.core.dispenser.DispenseItemBehavior$13
+ XXX.core.dispenser.DispenseItemBehavior$14
- XXX.core.dispenser.DispenseItemBehavior$15
+ XXX.core.dispenser.DispenseItemBehavior$16
- XXX.core.dispenser.DispenseItemBehavior$17
+ XXX.core.dispenser.DispenseItemBehavior$18
- XXX.core.dispenser.DispenseItemBehavior$19
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$20
+ XXX.core.dispenser.DispenseItemBehavior$21
- XXX.core.dispenser.DispenseItemBehavior$22
+ XXX.core.dispenser.DispenseItemBehavior$23
- XXX.core.dispenser.DispenseItemBehavior$24
+ XXX.core.dispenser.DispenseItemBehavior$25
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
- XXX.core.dispenser.package-info
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.BlockParticleOption$1
- XXX.core.particles.DustParticleOptions
+ XXX.core.particles.DustParticleOptions$1
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleOptions$Deserializer
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdventureAdvancements
+ XXX.data.advancements.HusbandryAdvancements
- XXX.data.advancements.NetherAdvancements
+ XXX.data.advancements.package-info
+ XXX.data.advancements.StoryAdvancements
- XXX.data.advancements.TheEndAdvancements
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
+ XXX.data.info.package-info
- XXX.data.info.RegistryDumpReport
- XXX.data.loot.BlockLoot
+ XXX.data.loot.ChestLoot
- XXX.data.loot.EntityLoot
+ XXX.data.loot.FishingLoot
- XXX.data.loot.GiftLoot
+ XXX.data.loot.LootTableProvider
+ XXX.data.loot.package-info
- XXX.data.loot.PiglinBarterLoot
- XXX.data.models.BlockModelGenerators
+ XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ModelProvider
- XXX.data.models.package-info
- XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapedRecipeBuilder$Result
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder$Result
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder$Result
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder$Result
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder$1
+ XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$TaskResult
+ XXX.data.structures.StructureUpdater
+ XXX.data.tags.BlockTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1
+ XXX.data.tags.TagsProvider$TagAppender
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedBlockEntityInjecter
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BeehivePoiRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
- XXX.dimension.end.TheEndDimension
+ XXX.entity.layers.AbstractArmorLayer
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseArmorLayer
+ XXX.entity.layers.HorseMarkingLayer
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
- XXX.entity.layers.PiglinArmorLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.SaddleLayer
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
+ XXX.entity.player.package-info
- XXX.entity.player.PlayerRenderer
+ XXX.feature.configurations.MegaTreeConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.ForestFlowerProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.PlainFlowerProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.structures.EmptyPoolElement
- XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawJunction
- XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.LegacySinglePoolElement
- XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchRunner
+ XXX.gametest.framework.GameTestBatchRunner$1
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestRunner$1
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.package-info
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
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
+ XXX.layer.traits.AreaTransformer0
- XXX.layer.traits.AreaTransformer1
+ XXX.layer.traits.AreaTransformer2
- XXX.layer.traits.BishopTransformer
+ XXX.layer.traits.C0Transformer
- XXX.layer.traits.C1Transformer
+ XXX.layer.traits.CastleTransformer
- XXX.layer.traits.DimensionOffset0Transformer
+ XXX.layer.traits.DimensionOffset1Transformer
- XXX.layer.traits.DimensionTransformer
- XXX.layer.traits.package-info
+ XXX.layer.traits.PixelTransformer
- XXX.level.border.package-info
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkBiomeContainer
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGeneratorFactory
+ XXX.level.chunk.ChunkGeneratorType
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.package-info
- XXX.level.chunk.Palette
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.ProtoTickList
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$1
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.Dimension
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.NetherDimension
+ XXX.level.dimension.NetherDimension$1
- XXX.level.dimension.NormalDimension
- XXX.level.dimension.package-info
+ XXX.level.levelgen.ChunkGeneratorProvider
- XXX.level.levelgen.ChunkGeneratorSettings
+ XXX.level.levelgen.DebugGeneratorSettings
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.NetherGeneratorSettings
- XXX.level.levelgen.NetherLevelSource
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.OverworldGeneratorSettings
+ XXX.level.levelgen.OverworldLevelSource
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.TheEndGeneratorSettings
+ XXX.level.levelgen.TheEndLevelSource
- XXX.level.levelgen.WorldgenRandom
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.FlatDataLayer
- XXX.level.lighting.LayerLightEngine
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$1
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.Fluid
- XXX.level.material.Fluids
- XXX.level.material.FluidState
+ XXX.level.material.FluidStateImpl
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.Material
+ XXX.level.material.Material$Builder
- XXX.level.material.MaterialColor
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.TurtleNodeEvaluator
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SaveDataDirtyRunnable
- XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
- XXX.level.storage.WorldData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$1
+ XXX.level.timers.TimerQueue$Event
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.NoneCarverConfiguration
- XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.feature.AbstractFlowerFeature
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.AbstractSmallTreeFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BastionBridgePools
+ XXX.levelgen.feature.BastionFeature
- XXX.levelgen.feature.BastionFeature$FeatureStart
+ XXX.levelgen.feature.BastionHoglinStablePools
- XXX.levelgen.feature.BastionHousingUnitsPools
+ XXX.levelgen.feature.BastionPieces
- XXX.levelgen.feature.BastionPieces$BastionPiece
+ XXX.levelgen.feature.BastionSharedPools
- XXX.levelgen.feature.BastionTreasureRoomPools
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureFeature
- XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DarkOakFeature
+ XXX.levelgen.feature.FancyTreeFeature$FoliageCoords
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IcePatchFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JunglePyramidFeature
+ XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.MegaPineTreeFeature
- XXX.levelgen.feature.package-info
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.levelgen.synth.SurfaceNoise
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.CompositeEntryBase$Serializer
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$1
- XXX.loot.entries.DynamicLoot$Serializer
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EmptyLootItem$1
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$1
- XXX.loot.entries.LootItem$Serializer
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntries$Serializer
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootPoolSingletonContainer$Serializer
- XXX.loot.entries.LootTableReference
+ XXX.loot.entries.LootTableReference$1
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$1
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$Serializer
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.ApplyExplosionDecay$1
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$1
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyBlockState$Serializer
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$1
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$1
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$DataSource
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$1
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$1
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$1
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.LimitCount$1
+ XXX.loot.functions.LimitCount$Serializer
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunction$Serializer
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctions$Serializer
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$1
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$1
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$1
- XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemDamageFunction$1
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$1
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$1
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$1
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$Serializer
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.SmeltItemFunction$1
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$1
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AlternativeLootItemCondition
- XXX.loot.predicates.AlternativeLootItemCondition$1
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.BonusLevelTableCondition$1
+ XXX.loot.predicates.BonusLevelTableCondition$Serializer
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.DamageSourceCondition$1
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$1
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.InvertedLootItemCondition$1
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemCondition$Serializer
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditions$Serializer
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$1
- XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceCondition$1
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ XXX.loot.predicates.MatchTool
- XXX.loot.predicates.MatchTool$Serializer
+ XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$1
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$1
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.loot.predicates.WeatherCheck$Serializer
- XXX.metadata.animation.AnimationFrame
+ XXX.metadata.animation.AnimationMetadataSection
- XXX.metadata.animation.AnimationMetadataSection$1
+ XXX.metadata.animation.AnimationMetadataSectionSerializer
+ XXX.metadata.animation.package-info
- XXX.metadata.animation.VillagerMetaDataSection
+ XXX.metadata.animation.VillagerMetaDataSection$Hat
- XXX.metadata.animation.VillagerMetadataSectionSerializer
- XXX.metadata.language.LanguageMetadataSection
+ XXX.metadata.language.LanguageMetadataSectionSerializer
- XXX.metadata.language.package-info
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
- XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
+ XXX.metadata.texture.TextureMetadataSectionSerializer
- XXX.minecraft.client.ComponentCollector
+ XXX.minecraft.client.CycleOption
- XXX.minecraft.client.DebugQueryHandler
+ XXX.minecraft.client.FullscreenResolutionProgressOption
- XXX.minecraft.client.Game
+ XXX.minecraft.client.Game$Metrics
- XXX.minecraft.client.GuiMessage
+ XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.KeyMapping$1
+ XXX.minecraft.client.package-info
- XXX.minecraft.client.StringDecomposer
- XXX.minecraft.client.StringSplitter
- XXX.minecraft.client.StringSplitter$FlatComponents
- XXX.minecraft.client.StringSplitter$LineComponent
- XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
- XXX.minecraft.commands.package-info
+ XXX.minecraft.core.AxisCycle
- XXX.minecraft.core.AxisCycle$1
+ XXX.minecraft.core.AxisCycle$2
- XXX.minecraft.core.AxisCycle$3
+ XXX.minecraft.core.BlockMath
- XXX.minecraft.core.BlockPos
+ XXX.minecraft.core.BlockPos$1
- XXX.minecraft.core.BlockPos$2
+ XXX.minecraft.core.BlockPos$3
- XXX.minecraft.core.BlockPos$4
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
+ XXX.minecraft.core.FrontAndTop
- XXX.minecraft.core.GlobalPos
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.LocatableSource
- XXX.minecraft.core.Location
+ XXX.minecraft.core.MapFiller
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.package-info
- XXX.minecraft.core.Position
+ XXX.minecraft.core.PositionImpl
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.SerializableBoolean
+ XXX.minecraft.core.SerializableLong
- XXX.minecraft.core.SerializableUUID
+ XXX.minecraft.core.Source
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
+ XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.DoubleTag$1
+ XXX.minecraft.nbt.EndTag
- XXX.minecraft.nbt.EndTag$1
+ XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.FloatTag$1
+ XXX.minecraft.nbt.IntArrayTag
- XXX.minecraft.nbt.IntArrayTag$1
+ XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$1
+ XXX.minecraft.nbt.IntTag$Cache
- XXX.minecraft.nbt.ListTag
+ XXX.minecraft.nbt.ListTag$1
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagTypes
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$PacketHolder
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.ConnectionProtocol$1
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
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
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.package-info
- XXX.minecraft.sounds.Music
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
- XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.StaticTagHelper
- XXX.minecraft.tags.StaticTagHelper$1
+ XXX.minecraft.tags.StaticTagHelper$Wrapper
- XXX.minecraft.tags.SynchronizableTagCollection
+ XXX.minecraft.tags.Tag
- XXX.minecraft.tags.Tag$1
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$BuilderEntry
+ XXX.minecraft.tags.Tag$ElementEntry
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$Named
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagManager
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.ClassInstanceMultiMap
- XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ XXX.minecraft.util.Crypt
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$1
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.Deserializer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
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
- XXX.minecraft.util.Serializer
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$1
- XXX.minecraft.util.SortedArraySet$ArrayIterator
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.WeighedRandom
- XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.minecraft.world.package-info
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
- XXX.models.blockstates.BlockStateGenerator
+ XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$1
+ XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$Operation
+ XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$1
- XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
+ XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$1
+ XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C2
+ XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C4
+ XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyDispatch$PentaFunction
+ XXX.models.blockstates.PropertyDispatch$QuadFunction
- XXX.models.blockstates.PropertyDispatch$TriFunction
+ XXX.models.blockstates.PropertyValue
- XXX.models.blockstates.Selector
+ XXX.models.blockstates.Variant
- XXX.models.blockstates.VariantProperties
+ XXX.models.blockstates.VariantProperties$Rotation
- XXX.models.blockstates.VariantProperty
+ XXX.models.blockstates.VariantProperty$Value
+ XXX.models.model.DelegatedModel
- XXX.models.model.ModelLocationUtils
+ XXX.models.model.ModelTemplate
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
- XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
+ XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
- XXX.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
+ XXX.mojang.realmsclient.RealmsMainScreen$TrialEntry
- XXX.mojang.realmsclient.Unit
- XXX.network.chat.BaseComponent
+ XXX.network.chat.ChatType
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component$1
- XXX.network.chat.Component$ContentConsumer
- XXX.network.chat.Component$StyledContentConsumer
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.ContextAwareComponent
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$ItemStackInfo
+ XXX.network.chat.KeybindComponent
- XXX.network.chat.MutableComponent
- XXX.network.chat.package-info
- XXX.network.chat.TextColor
+ XXX.network.chat.TextComponent
- XXX.network.chat.TranslatableComponent
+ XXX.network.chat.TranslatableFormatException
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
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
- XXX.newbiome.area.Area
+ XXX.newbiome.area.AreaFactory
- XXX.newbiome.area.LazyArea
+ XXX.newbiome.area.package-info
- XXX.newbiome.context.BigContext
+ XXX.newbiome.context.Context
- XXX.newbiome.context.LazyAreaContext
+ XXX.newbiome.context.package-info
- XXX.newbiome.layer.AddDeepOceanLayer
+ XXX.newbiome.layer.AddEdgeLayer
- XXX.newbiome.layer.AddEdgeLayer$CoolWarm
+ XXX.newbiome.layer.AddEdgeLayer$HeatIce
- XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
+ XXX.newbiome.layer.AddIslandLayer
- XXX.newbiome.layer.AddMushroomIslandLayer
+ XXX.newbiome.layer.AddSnowLayer
- XXX.newbiome.layer.BiomeEdgeLayer
+ XXX.newbiome.layer.BiomeInitLayer
- XXX.newbiome.layer.IslandLayer
+ XXX.newbiome.layer.Layer
- XXX.newbiome.layer.Layers
+ XXX.newbiome.layer.OceanLayer
- XXX.newbiome.layer.OceanMixerLayer
- XXX.newbiome.layer.package-info
+ XXX.newbiome.layer.RareBiomeLargeLayer
- XXX.newbiome.layer.RareBiomeSpotLayer
+ XXX.newbiome.layer.RegionHillsLayer
- XXX.newbiome.layer.RemoveTooMuchOceanLayer
+ XXX.newbiome.layer.RiverInitLayer
- XXX.newbiome.layer.RiverLayer
+ XXX.newbiome.layer.RiverMixerLayer
- XXX.newbiome.layer.ShoreLayer
+ XXX.newbiome.layer.SmoothLayer
- XXX.newbiome.layer.ZoomLayer
+ XXX.newbiome.layer.ZoomLayer$1
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
- XXX.phys.shapes.IntPointRange
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.phys.shapes.WorldRegionIndirectVoxelShape
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddGlobalEntityPacket
+ XXX.protocol.game.ClientboundAddMobPacket
- XXX.protocol.game.ClientboundAddPaintingPacket
+ XXX.protocol.game.ClientboundAddPlayerPacket
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockBreakAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChatPacket
- XXX.protocol.game.ClientboundChunkBlocksUpdatePacket
+ XXX.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$1
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundContainerAckPacket
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomPayloadPacket
+ XXX.protocol.game.ClientboundCustomSoundPacket
- XXX.protocol.game.ClientboundDisconnectPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundKeepAlivePacket
+ XXX.protocol.game.ClientboundLevelChunkPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLoginPacket
- XXX.protocol.game.ClientboundMapItemDataPacket
+ XXX.protocol.game.ClientboundMerchantOffersPacket
- XXX.protocol.game.ClientboundMoveEntityPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket$Pos
- XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
+ XXX.protocol.game.ClientboundMoveEntityPacket$Rot
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerCombatPacket
+ XXX.protocol.game.ClientboundPlayerCombatPacket$1
- XXX.protocol.game.ClientboundPlayerCombatPacket$Event
+ XXX.protocol.game.ClientboundPlayerInfoPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket$1
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action
- XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResourcePackPacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundSetBorderPacket
+ XXX.protocol.game.ClientboundSetBorderPacket$1
- XXX.protocol.game.ClientboundSetBorderPacket$Type
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquippedItemPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesPacket
+ XXX.protocol.game.ClientboundSetTitlesPacket$Type
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerAckPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
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
+ XXX.protocol.game.ServerGamePacketListener
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
+ XXX.realmsclient.client.FileDownload
- XXX.realmsclient.client.FileDownload$1
+ XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
- XXX.realmsclient.client.FileDownload$ProgressListener
+ XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
- XXX.realmsclient.client.FileUpload
+ XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
- XXX.realmsclient.client.Ping
+ XXX.realmsclient.client.Ping$Region
- XXX.realmsclient.client.RealmsClient
+ XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
- XXX.realmsclient.client.RealmsClient$Environment
+ XXX.realmsclient.client.RealmsClientConfig
- XXX.realmsclient.client.RealmsError
+ XXX.realmsclient.client.Request
- XXX.realmsclient.client.Request$Delete
+ XXX.realmsclient.client.Request$Get
- XXX.realmsclient.client.Request$Post
+ XXX.realmsclient.client.Request$Put
- XXX.realmsclient.client.UploadStatus
+ XXX.realmsclient.dto.Backup
- XXX.realmsclient.dto.BackupList
+ XXX.realmsclient.dto.GuardedSerializer
- XXX.realmsclient.dto.Ops
+ XXX.realmsclient.dto.PendingInvite
- XXX.realmsclient.dto.PendingInvitesList
+ XXX.realmsclient.dto.PingResult
- XXX.realmsclient.dto.PlayerInfo
+ XXX.realmsclient.dto.RealmsDescriptionDto
- XXX.realmsclient.dto.RealmsNews
+ XXX.realmsclient.dto.RealmsServer
- XXX.realmsclient.dto.RealmsServer$McoServerComparator
+ XXX.realmsclient.dto.RealmsServer$State
- XXX.realmsclient.dto.RealmsServer$WorldType
+ XXX.realmsclient.dto.RealmsServerAddress
- XXX.realmsclient.dto.RealmsServerList
+ XXX.realmsclient.dto.RealmsServerPing
- XXX.realmsclient.dto.RealmsServerPlayerList
+ XXX.realmsclient.dto.RealmsServerPlayerLists
- XXX.realmsclient.dto.RealmsWorldOptions
+ XXX.realmsclient.dto.RealmsWorldResetDto
- XXX.realmsclient.dto.ReflectionBasedSerialization
+ XXX.realmsclient.dto.RegionPingResult
- XXX.realmsclient.dto.Subscription
+ XXX.realmsclient.dto.Subscription$SubscriptionType
- XXX.realmsclient.dto.UploadInfo
+ XXX.realmsclient.dto.ValueObject
- XXX.realmsclient.dto.WorldDownload
+ XXX.realmsclient.dto.WorldTemplate
- XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
+ XXX.realmsclient.dto.WorldTemplatePaginatedList
- XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
+ XXX.realmsclient.exception.RealmsHttpException
- XXX.realmsclient.exception.RealmsServiceException
+ XXX.realmsclient.exception.RetryCallException
- XXX.realmsclient.gui.ErrorCallback
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
- XXX.renderer.debug.HeightMapRenderer$1
+ XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.package-info
+ XXX.renderer.debug.PathfindingRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
+ XXX.renderer.debug.VillageSectionsDebugRenderer
- XXX.renderer.debug.WaterDebugRenderer
+ XXX.renderer.debug.WorldGenAttemptRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractZombieRenderer
+ XXX.renderer.entity.AreaEffectCloudRenderer
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.CatRenderer
+ XXX.renderer.entity.CaveSpiderRenderer
- XXX.renderer.entity.ChestedHorseRenderer
+ XXX.renderer.entity.ChickenRenderer
- XXX.renderer.entity.CodRenderer
+ XXX.renderer.entity.CowRenderer
- XXX.renderer.entity.CreeperRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EnderDragonRenderer$DragonModel
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EvokerFangsRenderer
+ XXX.renderer.entity.EvokerRenderer
- XXX.renderer.entity.EvokerRenderer$1
+ XXX.renderer.entity.ExperienceOrbRenderer
- XXX.renderer.entity.FallingBlockRenderer
+ XXX.renderer.entity.FireworkEntityRenderer
- XXX.renderer.entity.FishingHookRenderer
+ XXX.renderer.entity.FoxRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GuardianRenderer
+ XXX.renderer.entity.HoglinRenderer
- XXX.renderer.entity.HorseRenderer
+ XXX.renderer.entity.HumanoidMobRenderer
- XXX.renderer.entity.HuskRenderer
+ XXX.renderer.entity.IllagerRenderer
- XXX.renderer.entity.IllusionerRenderer
+ XXX.renderer.entity.IllusionerRenderer$1
- XXX.renderer.entity.IronGolemRenderer
+ XXX.renderer.entity.ItemEntityRenderer
- XXX.renderer.entity.ItemFrameRenderer
+ XXX.renderer.entity.ItemRenderer
- XXX.renderer.entity.LeashKnotRenderer
+ XXX.renderer.entity.LightningBoltRenderer
- XXX.renderer.entity.LivingEntityRenderer
+ XXX.renderer.entity.LivingEntityRenderer$1
- XXX.renderer.entity.LlamaRenderer
+ XXX.renderer.entity.LlamaSpitRenderer
- XXX.renderer.entity.MagmaCubeRenderer
+ XXX.renderer.entity.MinecartRenderer
- XXX.renderer.entity.MobRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.OcelotRenderer
+ XXX.renderer.entity.package-info
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PandaRenderer
+ XXX.renderer.entity.ParrotRenderer
- XXX.renderer.entity.PhantomRenderer
- XXX.renderer.entity.PiglinRenderer
+ XXX.renderer.entity.PigRenderer
+ XXX.renderer.entity.PillagerRenderer
- XXX.renderer.entity.PolarBearRenderer
+ XXX.renderer.entity.PufferfishRenderer
- XXX.renderer.entity.RabbitRenderer
+ XXX.renderer.entity.RavagerRenderer
- XXX.renderer.entity.RenderLayerParent
+ XXX.renderer.entity.SalmonRenderer
- XXX.renderer.entity.SheepRenderer
+ XXX.renderer.entity.ShulkerBulletRenderer
- XXX.renderer.entity.ShulkerRenderer
+ XXX.renderer.entity.SilverfishRenderer
- XXX.renderer.entity.SkeletonRenderer
+ XXX.renderer.entity.SlimeRenderer
- XXX.renderer.entity.SnowGolemRenderer
+ XXX.renderer.entity.SpectralArrowRenderer
- XXX.renderer.entity.SpiderRenderer
+ XXX.renderer.entity.SquidRenderer
- XXX.renderer.entity.StrayRenderer
+ XXX.renderer.entity.StriderRenderer
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
- XXX.renderer.entity.ZoglinRenderer
+ XXX.renderer.entity.ZombieRenderer
- XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.AtlasSet
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
- XXX.renderer.texture.package-info
- XXX.renderer.texture.PreloadedTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SimpleTexture$TextureImage
+ XXX.renderer.texture.Stitcher
- XXX.renderer.texture.Stitcher$Holder
+ XXX.renderer.texture.Stitcher$Region
- XXX.renderer.texture.Stitcher$SpriteLoader
+ XXX.renderer.texture.StitcherException
- XXX.renderer.texture.TextureAtlas
+ XXX.renderer.texture.TextureAtlas$Preparations
- XXX.renderer.texture.TextureAtlasSprite
+ XXX.renderer.texture.TextureAtlasSprite$1
- XXX.renderer.texture.TextureAtlasSprite$Info
+ XXX.renderer.texture.TextureAtlasSprite$InterpolationData
- XXX.renderer.texture.TextureManager
+ XXX.renderer.texture.Tickable
+ XXX.resources.language.I18n
- XXX.resources.language.Language
+ XXX.resources.language.LanguageManager
- XXX.resources.language.Locale
+ XXX.resources.language.package-info
+ XXX.resources.metadata.package-info
+ XXX.resources.model.BakedModel
- XXX.resources.model.BlockModelRotation
+ XXX.resources.model.BuiltInModel
- XXX.resources.model.Material
+ XXX.resources.model.ModelBakery
- XXX.resources.model.ModelBakery$BlockStateDefinitionException
+ XXX.resources.model.ModelBakery$ModelGroupKey
- XXX.resources.model.ModelManager
+ XXX.resources.model.ModelResourceLocation
- XXX.resources.model.ModelState
+ XXX.resources.model.MultiPartBakedModel
- XXX.resources.model.MultiPartBakedModel$Builder
+ XXX.resources.model.package-info
+ XXX.resources.model.SimpleBakedModel
- XXX.resources.model.SimpleBakedModel$Builder
+ XXX.resources.model.UnbakedModel
- XXX.resources.model.WeightedBakedModel
+ XXX.resources.model.WeightedBakedModel$Builder
- XXX.resources.model.WeightedBakedModel$WeightedModel
+ XXX.resources.sounds.AbstractSoundInstance
- XXX.resources.sounds.AbstractTickableSoundInstance
+ XXX.resources.sounds.AmbientSoundHandler
- XXX.resources.sounds.BeeAggressiveSoundInstance
+ XXX.resources.sounds.BeeFlyingSoundInstance
- XXX.resources.sounds.BeeSoundInstance
+ XXX.resources.sounds.BiomeAmbientSoundsHandler
- XXX.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
+ XXX.resources.sounds.BubbleColumnAmbientSoundHandler
- XXX.resources.sounds.ElytraOnPlayerSoundInstance
+ XXX.resources.sounds.EntityBoundSoundInstance
- XXX.resources.sounds.GuardianAttackSoundInstance
+ XXX.resources.sounds.MinecartSoundInstance
+ XXX.resources.sounds.package-info
- XXX.resources.sounds.RidingMinecartSoundInstance
+ XXX.resources.sounds.SimpleSoundInstance
- XXX.resources.sounds.Sound
+ XXX.resources.sounds.Sound$Type
- XXX.resources.sounds.SoundEventRegistration
+ XXX.resources.sounds.SoundEventRegistrationSerializer
- XXX.resources.sounds.SoundInstance
+ XXX.resources.sounds.SoundInstance$Attenuation
- XXX.resources.sounds.TickableSoundInstance
+ XXX.resources.sounds.UnderwaterAmbientSoundHandler
- XXX.resources.sounds.UnderwaterAmbientSoundInstances
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.screens.inventory.BookEditScreen$DisplayCache
- XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode
- XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleList
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$1
+ XXX.selector.options.EntitySelectorOptions$Modifier
- XXX.selector.options.EntitySelectorOptions$Option
+ XXX.selector.options.package-info
- XXX.server.commands.AttributeCommand
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
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
- XXX.storage.loot.IntLimiter
+ XXX.storage.loot.IntLimiter$1
- XXX.storage.loot.IntLimiter$Serializer
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$1
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$DynamicDrop
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$1
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootPool$Serializer
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$1
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
- XXX.storage.loot.LootTables
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager
- XXX.storage.loot.RandomIntGenerator
+ XXX.storage.loot.RandomIntGenerators
- XXX.storage.loot.RandomValueBounds
+ XXX.storage.loot.RandomValueBounds$Serializer
- XXX.storage.loot.ValidationContext
+ XXX.storage.threaded.package-info
- XXX.synchronization.brigadier.BrigadierArgumentSerializers
+ XXX.synchronization.brigadier.DoubleArgumentSerializer
- XXX.synchronization.brigadier.FloatArgumentSerializer
+ XXX.synchronization.brigadier.IntegerArgumentSerializer
- XXX.synchronization.brigadier.LongArgumentSerializer
+ XXX.synchronization.brigadier.package-info
+ XXX.synchronization.brigadier.StringArgumentSerializer
- XXX.synchronization.brigadier.StringArgumentSerializer$1
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.OminousBannerBlockEntityRenameFix
- XXX.util.datafix.OminousBannerRenameFix
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.package-info
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
+ XXX.world.phys.PosAndRot
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
<hr/>