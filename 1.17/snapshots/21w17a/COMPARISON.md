## Comparison with [21w16a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w16a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">21w16a</th><th>21w17a</th></tr><tr><td>World version</td><td><pre>2711</pre></td><td><pre>2712</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741847</pre></td><td><pre>1073741849</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">21w16a</th><th>21w17a</th></tr><tr><td>com.mojang:authlib</td><td><pre>2.1.28</pre></td><td><pre>2.1.29</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
worldborder
</summary>

```diff
+ worldborder add <distance: double> <time: integer>
- worldborder add <distance: float> <time: integer>
+ worldborder set <distance: double> <time: integer>
- worldborder set <distance: float> <time: integer>
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
- copper_ingot_from_copper_block.json
+ copper_ingot.json
```

</details>
<details>
<summary>
black_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
blue_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
brown_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
coal_from_blasting_coal_ore.json
</summary>

```
Group: none -> coal
```

</details>
<details>
<summary>
coal_from_blasting_deepslate_coal_ore.json
</summary>

```
Group: none -> coal
```

</details>
<details>
<summary>
coal_from_smelting_coal_ore.json
</summary>

```
Group: none -> coal
```

</details>
<details>
<summary>
coal_from_smelting_deepslate_coal_ore.json
</summary>

```
Group: none -> coal
```

</details>
<details>
<summary>
copper_block.json
</summary>

```
A: copper_ingot

Previous pattern:
[A | A]
[A | A]

New pattern:
[A | A | A]
[A | A | A]
[A | A | A]
```

</details>
<details>
<summary>
copper_ingot_from_blasting_copper_ore.json
</summary>

```
Group: none -> copper_ingot
```

</details>
<details>
<summary>
copper_ingot_from_blasting_deepslate_copper_ore.json
</summary>

```
Group: none -> copper_ingot
```

</details>
<details>
<summary>
copper_ingot_from_blasting_raw_copper.json
</summary>

```
Group: none -> copper_ingot
```

</details>
<details>
<summary>
copper_ingot_from_smelting_copper_ore.json
</summary>

```
Group: none -> copper_ingot
```

</details>
<details>
<summary>
copper_ingot_from_smelting_deepslate_copper_ore.json
</summary>

```
Group: none -> copper_ingot
```

</details>
<details>
<summary>
copper_ingot_from_smelting_raw_copper.json
</summary>

```
Group: none -> copper_ingot
```

</details>
<details>
<summary>
copper_ingot_from_waxed_copper_block.json
</summary>

```
Result: copper_ingot x4 -> copper_ingot x9
```

</details>
<details>
<summary>
cyan_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
diamond_from_blasting_deepslate_diamond_ore.json
</summary>

```
Group: none -> diamond
```

</details>
<details>
<summary>
diamond_from_blasting_diamond_ore.json
</summary>

```
Group: none -> diamond
```

</details>
<details>
<summary>
diamond_from_smelting_deepslate_diamond_ore.json
</summary>

```
Group: none -> diamond
```

</details>
<details>
<summary>
diamond_from_smelting_diamond_ore.json
</summary>

```
Group: none -> diamond
```

</details>
<details>
<summary>
emerald_from_blasting_deepslate_emerald_ore.json
</summary>

```
Group: none -> emerald
```

</details>
<details>
<summary>
emerald_from_blasting_emerald_ore.json
</summary>

```
Group: none -> emerald
```

</details>
<details>
<summary>
emerald_from_smelting_deepslate_emerald_ore.json
</summary>

```
Group: none -> emerald
```

</details>
<details>
<summary>
emerald_from_smelting_emerald_ore.json
</summary>

```
Group: none -> emerald
```

</details>
<details>
<summary>
gold_ingot_from_blasting_deepslate_gold_ore.json
</summary>

```
Group: none -> gold_ingot
```

</details>
<details>
<summary>
gold_ingot_from_blasting_gold_ore.json
</summary>

```
Group: none -> gold_ingot
```

</details>
<details>
<summary>
gold_ingot_from_blasting_nether_gold_ore.json
</summary>

```
Group: none -> gold_ingot
```

</details>
<details>
<summary>
gold_ingot_from_blasting_raw_gold.json
</summary>

```
Group: none -> gold_ingot
```

</details>
<details>
<summary>
gold_ingot_from_smelting_deepslate_gold_ore.json
</summary>

```
Group: none -> gold_ingot
```

</details>
<details>
<summary>
gold_ingot_from_smelting_gold_ore.json
</summary>

```
Group: none -> gold_ingot
```

</details>
<details>
<summary>
gold_ingot_from_smelting_nether_gold_ore.json
</summary>

```
Group: none -> gold_ingot
```

</details>
<details>
<summary>
gold_ingot_from_smelting_raw_gold.json
</summary>

```
Group: none -> gold_ingot
```

</details>
<details>
<summary>
gray_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
green_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
iron_ingot_from_blasting_deepslate_iron_ore.json
</summary>

```
Group: none -> iron_ingot
```

</details>
<details>
<summary>
iron_ingot_from_blasting_iron_ore.json
</summary>

```
Group: none -> iron_ingot
```

</details>
<details>
<summary>
iron_ingot_from_blasting_raw_iron.json
</summary>

```
Group: none -> iron_ingot
```

</details>
<details>
<summary>
iron_ingot_from_smelting_deepslate_iron_ore.json
</summary>

```
Group: none -> iron_ingot
```

</details>
<details>
<summary>
iron_ingot_from_smelting_iron_ore.json
</summary>

```
Group: none -> iron_ingot
```

</details>
<details>
<summary>
iron_ingot_from_smelting_raw_iron.json
</summary>

```
Group: none -> iron_ingot
```

</details>
<details>
<summary>
lapis_lazuli_from_blasting_deepslate_lapis_ore.json
</summary>

```
Group: none -> lapus_lazuli
```

</details>
<details>
<summary>
lapis_lazuli_from_blasting_lapis_ore.json
</summary>

```
Group: none -> lapus_lazuli
```

</details>
<details>
<summary>
lapis_lazuli_from_smelting_deepslate_lapis_ore.json
</summary>

```
Group: none -> lapus_lazuli
```

</details>
<details>
<summary>
lapis_lazuli_from_smelting_lapis_ore.json
</summary>

```
Group: none -> lapus_lazuli
```

</details>
<details>
<summary>
light_blue_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
light_gray_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
lime_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
magenta_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
mossy_cobblestone_from_moss_block.json
</summary>

```
Group: none -> mossy_cobblestone
```

</details>
<details>
<summary>
mossy_cobblestone_from_vine.json
</summary>

```
Group: none -> mossy_cobblestone
```

</details>
<details>
<summary>
mossy_stone_bricks_from_moss_block.json
</summary>

```
Group: none -> mossy_stone_bricks
```

</details>
<details>
<summary>
mossy_stone_bricks_from_vine.json
</summary>

```
Group: none -> mossy_stone_bricks
```

</details>
<details>
<summary>
orange_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
pink_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
purple_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
redstone_from_blasting_deepslate_redstone_ore.json
</summary>

```
Group: none -> redstone
```

</details>
<details>
<summary>
redstone_from_blasting_redstone_ore.json
</summary>

```
Group: none -> redstone
```

</details>
<details>
<summary>
redstone_from_smelting_deepslate_redstone_ore.json
</summary>

```
Group: none -> redstone
```

</details>
<details>
<summary>
redstone_from_smelting_redstone_ore.json
</summary>

```
Group: none -> redstone
```

</details>
<details>
<summary>
red_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
waxed_copper_block_from_honeycomb.json
</summary>

```
Group: none -> waxed_copper_block
```

</details>
<details>
<summary>
waxed_cut_copper.json
</summary>

```
Group: none -> waxed_cut_copper
```

</details>
<details>
<summary>
waxed_cut_copper_from_honeycomb.json
</summary>

```
Group: none -> waxed_cut_copper
```

</details>
<details>
<summary>
waxed_cut_copper_slab.json
</summary>

```
Group: none -> waxed_cut_copper_slab
```

</details>
<details>
<summary>
waxed_cut_copper_slab_from_honeycomb.json
</summary>

```
Group: none -> waxed_cut_copper_slab
```

</details>
<details>
<summary>
waxed_cut_copper_stairs.json
</summary>

```
Group: none -> waxed_cut_copper_stairs
```

</details>
<details>
<summary>
waxed_cut_copper_stairs_from_honeycomb.json
</summary>

```
Group: none -> waxed_cut_copper_stairs
```

</details>
<details>
<summary>
waxed_exposed_copper_from_honeycomb.json
</summary>

```
Group: none -> waxed_exposed_copper
```

</details>
<details>
<summary>
waxed_exposed_cut_copper.json
</summary>

```
Group: none -> waxed_exposed_cut_copper
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_from_honeycomb.json
</summary>

```
Group: none -> waxed_exposed_cut_copper
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_slab.json
</summary>

```
Group: none -> waxed_exposed_cut_copper_slab
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_slab_from_honeycomb.json
</summary>

```
Group: none -> waxed_exposed_cut_copper_slab
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs.json
</summary>

```
Group: none -> waxed_exposed_cut_copper_stairs
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs_from_honeycomb.json
</summary>

```
Group: none -> waxed_exposed_cut_copper_stairs
```

</details>
<details>
<summary>
waxed_oxidized_copper_from_honeycomb.json
</summary>

```
Group: none -> waxed_oxidized_copper
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper.json
</summary>

```
Group: none -> waxed_oxidized_cut_copper
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_from_honeycomb.json
</summary>

```
Group: none -> waxed_oxidized_cut_copper
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab.json
</summary>

```
Group: none -> waxed_oxidized_cut_copper_slab
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab_from_honeycomb.json
</summary>

```
Group: none -> waxed_oxidized_cut_copper_slab
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs.json
</summary>

```
Group: none -> waxed_oxidized_cut_copper_stairs
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs_from_honeycomb.json
</summary>

```
Group: none -> waxed_oxidized_cut_copper_stairs
```

</details>
<details>
<summary>
waxed_weathered_copper_from_honeycomb.json
</summary>

```
Group: none -> waxed_weathered_copper
```

</details>
<details>
<summary>
waxed_weathered_cut_copper.json
</summary>

```
Group: none -> waxed_weathered_cut_copper
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_from_honeycomb.json
</summary>

```
Group: none -> waxed_weathered_cut_copper
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_slab.json
</summary>

```
Group: none -> waxed_weathered_cut_copper_slab
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_slab_from_honeycomb.json
</summary>

```
Group: none -> waxed_weathered_cut_copper_slab
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs.json
</summary>

```
Group: none -> waxed_weathered_cut_copper_stairs
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs_from_honeycomb.json
</summary>

```
Group: none -> waxed_weathered_cut_copper_stairs
```

</details>
<details>
<summary>
white_candle.json
</summary>

```
Group: none -> dyed_candle
```

</details>
<details>
<summary>
yellow_candle.json
</summary>

```
Group: none -> dyed_candle
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
+ commands.worldborder.set.failed.big: World border cannot be bigger than %s blocks wide
- commands.worldborder.set.failed.big.: World border cannot be bigger than 60,000,000 blocks wide
+ commands.worldborder.set.failed.small: World border cannot be smaller than 1 block wide
- commands.worldborder.set.failed.small.: World border cannot be smaller than 1 block wide
+ multiplayer.disconnect.invalid_packet: Server sent an invalid packet
+ multiplayer.disconnect.invalid_player_data: Invalid player data
```

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
- minecraft/advancements/recipes/misc/copper_ingot_from_copper_block.json
+ minecraft/advancements/recipes/misc/copper_ingot.json
- minecraft/recipes/copper_ingot_from_copper_block.json
+ minecraft/recipes/copper_ingot.json
+ minecraft/tags/blocks/small_dripleaf_placeable.json
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
+ XXX.feature.blockplacers.BlockPlacer
- XXX.feature.blockplacers.BlockPlacerType
+ XXX.feature.blockplacers.ColumnPlacer
- XXX.feature.blockplacers.DoublePlantPlacer
- XXX.feature.blockplacers.package-info
+ XXX.feature.blockplacers.SimpleBlockPlacer
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration
- XXX.feature.configurations.CountConfiguration
+ XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DecoratorConfiguration
+ XXX.feature.configurations.DeltaFeatureConfiguration
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.DripstoneClusterConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.GeodeConfiguration
+ XXX.feature.configurations.GlowLichenConfiguration
- XXX.feature.configurations.GrowingPlantConfiguration
+ XXX.feature.configurations.HeightmapConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.JigsawConfiguration
- XXX.feature.configurations.LargeDripstoneConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MineshaftConfiguration
+ XXX.feature.configurations.NoiseDependantDecoratorConfiguration
- XXX.feature.configurations.NoneDecoratorConfiguration
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OceanRuinConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$1
+ XXX.feature.configurations.OreConfiguration$Predicates
- XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.package-info
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration$1
- XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ XXX.feature.configurations.RangeDecoratorConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.ReplaceSphereConfiguration
- XXX.feature.configurations.RootSystemConfiguration
+ XXX.feature.configurations.RuinedPortalConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SmallDripstoneConfiguration
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.StrongholdConfiguration
+ XXX.feature.configurations.StructureFeatureConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.UnderwaterMagmaConfiguration
+ XXX.feature.configurations.VegetationPatchConfiguration
+ XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.FeatureSizeType
+ XXX.feature.featuresize.package-info
+ XXX.feature.featuresize.ThreeLayersFeatureSize
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
+ XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.PlainFlowerProvider
+ XXX.feature.stateproviders.RandomizedIntStateProvider
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
+ XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.BendingTrunkPlacer
+ XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.ForkingTrunkPlacer
+ XXX.feature.trunkplacers.GiantTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
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
- XXX.level.levelgen.NoiseBasedChunkGenerator$OreVeinNoiseSource
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseInterpolator
+ XXX.level.levelgen.NoiseInterpolator$NoiseColumnFiller
- XXX.level.levelgen.NoiseModifier
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
- XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.RandomSource
+ XXX.level.levelgen.SimpleRandomSource
- XXX.level.levelgen.SingleBaseStoneSource
+ XXX.level.levelgen.StructureSettings
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
+ XXX.level.levelgen.WorldGenerationContext
- XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldGenSettings
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
+ XXX.level.material.Fluids
- XXX.level.material.FluidState
- XXX.level.material.FogType
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
- XXX.level.pathfinder.AmphibiousNodeEvaluator
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalInfo
+ XXX.level.portal.PortalShape
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$1
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
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelVersion
+ XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
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
+ XXX.levelgen.carver.CanyonCarverConfiguration
- XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CarverDebugSettings
- XXX.levelgen.carver.CarvingContext
+ XXX.levelgen.carver.CaveCarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
- XXX.levelgen.carver.WorldCarver$CarveSkipChecker
- XXX.levelgen.feature.AbstractFlowerFeature
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BaseDiskFeature
- XXX.levelgen.feature.BastionFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureFeature
- XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.ConfiguredStructureFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DecoratedFeature
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertPyramidFeature
- XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.DripstoneClusterFeature
- XXX.levelgen.feature.DripstoneUtils
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeaturePlaceContext
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.FossilFeatureConfiguration
+ XXX.levelgen.feature.GeodeFeature
- XXX.levelgen.feature.GlowLichenFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.GrowingPlantFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IcePatchFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JigsawFeature
+ XXX.levelgen.feature.JigsawFeature$FeatureStart
- XXX.levelgen.feature.JunglePyramidFeature
+ XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.LargeDripstoneFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$1
- XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- XXX.levelgen.feature.MineshaftFeature
+ XXX.levelgen.feature.MineshaftFeature$MineShaftStart
- XXX.levelgen.feature.MineshaftFeature$Type
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NetherFortressFeature
- XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- XXX.levelgen.feature.NoiseEffect
+ XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OceanMonumentFeature
- XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PillagerOutpostFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.RuinedPortalFeature
- XXX.levelgen.feature.RuinedPortalFeature$FeatureStart
+ XXX.levelgen.feature.RuinedPortalFeature$Type
- XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.ShipwreckFeature
- XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SmallDripstoneFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$1
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.StrongholdFeature
+ XXX.levelgen.feature.StrongholdFeature$StrongholdStart
- XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.StructureFeature$StructureStartFactory
- XXX.levelgen.feature.StructurePieceType
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.UnderwaterMagmaFeature
- XXX.levelgen.feature.VegetationPatchFeature
+ XXX.levelgen.feature.VillageFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedConfiguredFeature
+ XXX.levelgen.feature.WoodlandMansionFeature
- XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
- XXX.levelgen.heightproviders.BiasedToBottomHeight
+ XXX.levelgen.heightproviders.ConstantHeight
- XXX.levelgen.heightproviders.HeightProvider
+ XXX.levelgen.heightproviders.HeightProviderType
+ XXX.levelgen.heightproviders.package-info
- XXX.levelgen.heightproviders.TrapezoidHeight
+ XXX.levelgen.heightproviders.UniformHeight
- XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
+ XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
+ XXX.levelgen.placement.CaveDecoratorConfiguration
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CaveSurfaceDecorator
- XXX.levelgen.placement.ChanceDecorator
+ XXX.levelgen.placement.ChanceDecoratorConfiguration
- XXX.levelgen.placement.ConfiguredDecorator
+ XXX.levelgen.placement.CountDecorator
- XXX.levelgen.placement.CountNoiseDecorator
+ XXX.levelgen.placement.CountWithExtraChanceDecorator
- XXX.levelgen.placement.DarkOakTreePlacementDecorator
+ XXX.levelgen.placement.DecoratedDecorator
- XXX.levelgen.placement.DecoratedDecoratorConfiguration
+ XXX.levelgen.placement.DecorationContext
- XXX.levelgen.placement.EndGatewayPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
- XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ XXX.levelgen.placement.HeightmapDecorator
- XXX.levelgen.placement.HeightmapDoubleDecorator
+ XXX.levelgen.placement.IcebergPlacementDecorator
- XXX.levelgen.placement.LakeLavaPlacementDecorator
+ XXX.levelgen.placement.NoiseBasedDecorator
- XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ XXX.levelgen.placement.NopePlacementDecorator
+ XXX.levelgen.placement.package-info
- XXX.levelgen.placement.RangeDecorator
+ XXX.levelgen.placement.RepeatingDecorator
- XXX.levelgen.placement.Spread32Decorator
+ XXX.levelgen.placement.SquareDecorator
- XXX.levelgen.placement.VerticalDecorator
+ XXX.levelgen.placement.WaterDepthThresholdConfiguration
- XXX.levelgen.placement.WaterDepthThresholdDecorator
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuriedTreasurePieces
+ XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.levelgen.structure.DesertPyramidPiece
+ XXX.levelgen.structure.EndCityPieces
- XXX.levelgen.structure.EndCityPieces$1
+ XXX.levelgen.structure.EndCityPieces$2
- XXX.levelgen.structure.EndCityPieces$3
+ XXX.levelgen.structure.EndCityPieces$4
- XXX.levelgen.structure.EndCityPieces$EndCityPiece
+ XXX.levelgen.structure.EndCityPieces$SectionGenerator
- XXX.levelgen.structure.IglooPieces
+ XXX.levelgen.structure.IglooPieces$IglooPiece
- XXX.levelgen.structure.JunglePyramidPiece
+ XXX.levelgen.structure.JunglePyramidPiece$1
- XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.MineShaftPieces
+ XXX.levelgen.structure.MineShaftPieces$1
- XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
- XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
+ XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
- XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
+ XXX.levelgen.structure.NetherBridgePieces
- XXX.levelgen.structure.NetherBridgePieces$1
+ XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
- XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
+ XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- XXX.levelgen.structure.NetherBridgePieces$PieceWeight
+ XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
- XXX.levelgen.structure.NetherBridgePieces$StairsRoom
+ XXX.levelgen.structure.NetherBridgePieces$StartPiece
- XXX.levelgen.structure.NetherFossilFeature
+ XXX.levelgen.structure.NetherFossilFeature$FeatureStart
- XXX.levelgen.structure.NetherFossilPieces
+ XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- XXX.levelgen.structure.NoiseAffectingStructureStart
+ XXX.levelgen.structure.OceanMonumentPieces
- XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature
- XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ XXX.levelgen.structure.OceanRuinFeature$Type
- XXX.levelgen.structure.OceanRuinPieces
+ XXX.levelgen.structure.OceanRuinPieces$1
- XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.RuinedPortalPiece
+ XXX.levelgen.structure.RuinedPortalPiece$Properties
- XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.ShipwreckPieces
+ XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$1
- XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$3
- XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FillerCorridor
- XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$LeftTurn
- XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PieceWeight
- XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$PrisonHall
- XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$RoomCrossing
- XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StairsDown
- XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$Straight
- XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.levelgen.structure.StrongholdPieces$Turn
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructurePieceAccessor
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureStart$1
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
- XXX.levelgen.structure.WoodlandMansionPieces$1
+ XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
- XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
- XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
- XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
- XXX.levelgen.surfacebuilders.package-info
+ XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
+ XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
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
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolEntryType
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
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$1
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
- XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$1
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBannerPatternFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$1
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$1
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$1
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetEnchantmentsFunction$Serializer
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
- XXX.loot.predicates.ConditionReference$1
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
- XXX.loot.predicates.LocationCheck$1
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
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
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$1
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.ValueCheckCondition$1
+ XXX.loot.predicates.ValueCheckCondition$Serializer
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$1
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
- XXX.minecraft.world.package-info
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
- XXX.newbiome.layer.LayerBiomes
+ XXX.newbiome.layer.Layers
- XXX.newbiome.layer.Layers$Category
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
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.placement.nether.CountMultiLayerDecorator
- XXX.placement.nether.package-info
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.ContextNbtProvider$InlineSerializer
- XXX.providers.nbt.ContextNbtProvider$Serializer
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.nbt.StorageNbtProvider$1
- XXX.providers.nbt.StorageNbtProvider$Serializer
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.BinomialDistributionGenerator$1
- XXX.providers.number.BinomialDistributionGenerator$Serializer
+ XXX.providers.number.ConstantValue
- XXX.providers.number.ConstantValue$1
+ XXX.providers.number.ConstantValue$InlineSerializer
- XXX.providers.number.ConstantValue$Serializer
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.ScoreboardValue$1
- XXX.providers.number.ScoreboardValue$Serializer
+ XXX.providers.number.UniformGenerator
- XXX.providers.number.UniformGenerator$1
+ XXX.providers.number.UniformGenerator$Serializer
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.ContextScoreboardNameProvider$1
+ XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
- XXX.providers.score.ContextScoreboardNameProvider$Serializer
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider$1
+ XXX.providers.score.FixedScoreboardNameProvider$Serializer
- XXX.providers.score.LootScoreProviderType
+ XXX.providers.score.package-info
+ XXX.providers.score.ScoreboardNameProvider
- XXX.providers.score.ScoreboardNameProviders
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$1
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.Deserializers
+ XXX.storage.loot.GsonAdapterFactory
- XXX.storage.loot.GsonAdapterFactory$1
+ XXX.storage.loot.GsonAdapterFactory$Builder
- XXX.storage.loot.GsonAdapterFactory$InlineSerializer
+ XXX.storage.loot.GsonAdapterFactory$JsonAdapter
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$1
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.IntRange$Serializer
+ XXX.storage.loot.ItemModifierManager
- XXX.storage.loot.ItemModifierManager$FunctionSequence
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
- XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager
- XXX.storage.loot.PredicateManager$1
+ XXX.storage.loot.PredicateManager$CompositePredicate
- XXX.storage.loot.Serializer
+ XXX.storage.loot.SerializerType
- XXX.storage.loot.ValidationContext
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LavaSubmergedBlockProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructureManager
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorList
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.TagMatchTest
+ XXX.world.level.package-info
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
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
XXX.arguments.selector.EntitySelectorParser +2M -4M
```
```
XXX.core.dispenser.ShulkerBoxDispenseBehavior +1M | +1P
```
```
XXX.minecraft.data.BlockFamily$Builder +1M
```
```
XXX.data.loot.BlockLoot +2M -3M
```
```
XXX.data.recipes.RecipeProvider +5M -3M
```
```
XXX.protocol.game.ClientGamePacketListener +1P -1P
```
```
XXX.level.block.AmethystClusterBlock -1P
```
```
XXX.level.block.HangingRootsBlock +3M | +1P
```
```
XXX.level.block.HoneyBlock +1M -1M
```
```
XXX.level.block.PointedDripstoneBlock +1M -1M
```
```
XXX.level.block.RedStoneOreBlock +1M -1M
```
```
XXX.level.block.SlimeBlock +2M -2M
```
```
XXX.level.block.StairBlock +1M -1M
```
```
XXX.level.block.TurtleEggBlock +3M -3M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +8M -4M | +1P
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.EntitySelectorParser
</summary>

```diff
- boolean lambda$createRotationPredicate$13(ToDoubleFunction,double,double,Entity)
+ boolean lambda$createRotationPredicate$15(ToDoubleFunction,double,double,Entity)
- boolean lambda$finalizePredicates$12(Entity)
+ boolean lambda$finalizePredicates$14(Entity)
+ double lambda$finalizePredicates$12(Entity)
+ double lambda$finalizePredicates$13(Entity)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.data.BlockFamily$Builder
</summary>

```diff
- BlockFamily$Builder cut(Block)
```

</details>
<details>
<summary>
net.minecraft.data.loot.BlockLoot
</summary>

```diff
- LootTable$Builder createCopperOreDrops(Block)
+ LootTable$Builder lambda$accept$82(Block)
+ LootTable$Builder lambda$accept$83(Block)
- LootTable$Builder lambda$dropPottedContents$82(Block)
+ LootTable$Builder lambda$dropPottedContents$84(Block)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- RecipeBuilder lambda$static$18(ItemLike,ItemLike)
- ShapedRecipeBuilder cutBuilder(ItemLike,Ingredient)
- void oreBlasting(Consumer,List,ItemLike,float,int,String)
+ void oreBlasting(Consumer,List,ItemLike,float,int)
- void oreCooking(Consumer,SimpleCookingSerializer,List,ItemLike,float,int,String,String)
+ void oreCooking(Consumer,SimpleCookingSerializer,List,ItemLike,float,int,String)
- void oreSmelting(Consumer,List,ItemLike,float,int,String)
+ void oreSmelting(Consumer,List,ItemLike,float,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HangingRootsBlock
</summary>

```diff
- BlockState getStateForPlacement(BlockPlaceContext)
- FluidState getFluidState(BlockState)
- void createBlockStateDefinition(StateDefinition$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HoneyBlock
</summary>

```diff
+ void fallOn(Level,BlockPos,Entity,float)
- void fallOn(Level,BlockState,BlockPos,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PointedDripstoneBlock
</summary>

```diff
+ void fallOn(Level,BlockPos,Entity,float)
- void fallOn(Level,BlockState,BlockPos,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RedStoneOreBlock
</summary>

```diff
- void stepOn(Level,BlockPos,BlockState,Entity)
+ void stepOn(Level,BlockPos,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlimeBlock
</summary>

```diff
+ void fallOn(Level,BlockPos,Entity,float)
- void fallOn(Level,BlockState,BlockPos,Entity,float)
- void stepOn(Level,BlockPos,BlockState,Entity)
+ void stepOn(Level,BlockPos,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StairBlock
</summary>

```diff
- void stepOn(Level,BlockPos,BlockState,Entity)
+ void stepOn(Level,BlockPos,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TurtleEggBlock
</summary>

```diff
+ void destroyEgg(Level,BlockPos,Entity,int)
- void destroyEgg(Level,BlockState,BlockPos,Entity,int)
+ void fallOn(Level,BlockPos,Entity,float)
- void fallOn(Level,BlockState,BlockPos,Entity,float)
- void stepOn(Level,BlockPos,BlockState,Entity)
+ void stepOn(Level,BlockPos,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
- BaseStoneSource lambda$createBaseStoneSource$11(double)
- BaseStoneSource lambda$createBaseStoneSource$13(NoiseBasedChunkGenerator$OreVeinNoiseSource,BaseStoneSource,double)
+ BlockState lambda$createBaseStoneSource$11(NoiseBasedChunkGenerator$OreVeinNoiseSource,int,int,int)
- BlockState lambda$createBaseStoneSource$12(NoiseBasedChunkGenerator$OreVeinNoiseSource,int,int,int)
+ BlockState updateNoiseAndGenerateBaseState(Beardifier,Aquifer,BaseStoneSource,int,int,int,double)
- BlockState updateNoiseAndGenerateBaseState(Beardifier,Aquifer,BaseStoneSource,NoiseModifier,int,int,int,double)
- DoubleFunction createBaseStoneSource(int,ChunkPos,Consumer)
- DoubleFunction createCaveNoiseModifier(int,ChunkPos,Consumer)
- NoiseModifier lambda$createCaveNoiseModifier$10(double)
- NoodleCavifier access$400(NoiseBasedChunkGenerator)
+ Pair createBaseStoneSource(int,ChunkPos,Consumer)
+ void lambda$createBaseStoneSource$10(double)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.blaze3d.platform.GlDebug$1
- XXX.feature.blockplacers.BlockPlacer
+ XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.ColumnPlacer
+ XXX.feature.blockplacers.DoublePlantPlacer
+ XXX.feature.blockplacers.package-info
- XXX.feature.blockplacers.SimpleBlockPlacer
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.CountConfiguration
- XXX.feature.configurations.DecoratedFeatureConfiguration
+ XXX.feature.configurations.DecoratorConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.DripstoneClusterConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.GeodeConfiguration
- XXX.feature.configurations.GlowLichenConfiguration
+ XXX.feature.configurations.GrowingPlantConfiguration
- XXX.feature.configurations.HeightmapConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.JigsawConfiguration
+ XXX.feature.configurations.LargeDripstoneConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.NoiseDependantDecoratorConfiguration
+ XXX.feature.configurations.NoneDecoratorConfiguration
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$1
- XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
+ XXX.feature.configurations.package-info
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$1
+ XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- XXX.feature.configurations.RangeDecoratorConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.RootSystemConfiguration
- XXX.feature.configurations.RuinedPortalConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SmallDripstoneConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.StrongholdConfiguration
- XXX.feature.configurations.StructureFeatureConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.UnderwaterMagmaConfiguration
- XXX.feature.configurations.VegetationPatchConfiguration
- XXX.feature.featuresize.FeatureSize
+ XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.featuresize.TwoLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
- XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RandomizedIntStateProvider
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
- XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
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
- XXX.level.levelgen.NoiseBasedChunkGenerator$NoodleCaveNoiseModifier
+ XXX.level.levelgen.NoiseBasedChunkGenerator$OreVeinNoiseSource
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.NoiseInterpolator
- XXX.level.levelgen.NoiseInterpolator$NoiseColumnFiller
- XXX.level.levelgen.NoodleCavifier
+ XXX.level.levelgen.OreVeinifier
- XXX.level.levelgen.OreVeinifier$VeinType
+ XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.RandomSource
- XXX.level.levelgen.SimpleRandomSource
+ XXX.level.levelgen.SingleBaseStoneSource
- XXX.level.levelgen.StructureSettings
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldGenSettings
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
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
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
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$1
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelVersion
- XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
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
- XXX.levelgen.carver.CanyonCarverConfiguration
+ XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CarverDebugSettings
+ XXX.levelgen.carver.CarvingContext
- XXX.levelgen.carver.CaveCarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.package-info
- XXX.levelgen.carver.UnderwaterCanyonWorldCarver
+ XXX.levelgen.carver.UnderwaterCaveWorldCarver
- XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.carver.WorldCarver$CarveSkipChecker
+ XXX.levelgen.feature.AbstractFlowerFeature
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BaseDiskFeature
+ XXX.levelgen.feature.BastionFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.ConfiguredStructureFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskReplaceFeature
- XXX.levelgen.feature.DripstoneClusterFeature
+ XXX.levelgen.feature.DripstoneUtils
- XXX.levelgen.feature.EndCityFeature
+ XXX.levelgen.feature.EndCityFeature$EndCityStart
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FeaturePlaceContext
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.FossilFeatureConfiguration
- XXX.levelgen.feature.GeodeFeature
+ XXX.levelgen.feature.GlowLichenFeature
- XXX.levelgen.feature.GlowstoneFeature
+ XXX.levelgen.feature.GrowingPlantFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IcePatchFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.IglooFeature
- XXX.levelgen.feature.IglooFeature$FeatureStart
+ XXX.levelgen.feature.JigsawFeature
- XXX.levelgen.feature.JigsawFeature$FeatureStart
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LargeDripstoneFeature
- XXX.levelgen.feature.LargeDripstoneFeature$1
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.NoiseEffect
- XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.RuinedPortalFeature
+ XXX.levelgen.feature.RuinedPortalFeature$FeatureStart
- XXX.levelgen.feature.RuinedPortalFeature$Type
+ XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.ShipwreckFeature
+ XXX.levelgen.feature.ShipwreckFeature$FeatureStart
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SmallDripstoneFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.StrongholdFeature
- XXX.levelgen.feature.StrongholdFeature$StrongholdStart
+ XXX.levelgen.feature.StructureFeature
- XXX.levelgen.feature.StructureFeature$StructureStartFactory
+ XXX.levelgen.feature.StructurePieceType
- XXX.levelgen.feature.SwamplandHutFeature
+ XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
- XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.placement.CarvingMaskDecorator
+ XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
- XXX.levelgen.placement.CaveDecoratorConfiguration
+ XXX.levelgen.placement.CaveSurface
- XXX.levelgen.placement.CaveSurfaceDecorator
+ XXX.levelgen.placement.ChanceDecorator
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountDecorator
+ XXX.levelgen.placement.CountNoiseDecorator
- XXX.levelgen.placement.CountWithExtraChanceDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DecoratedDecorator
+ XXX.levelgen.placement.DecoratedDecoratorConfiguration
- XXX.levelgen.placement.DecorationContext
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- XXX.levelgen.placement.HeightmapDecorator
+ XXX.levelgen.placement.HeightmapDoubleDecorator
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.NoiseBasedDecorator
+ XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.RangeDecorator
- XXX.levelgen.placement.RepeatingDecorator
+ XXX.levelgen.placement.Spread32Decorator
- XXX.levelgen.placement.SquareDecorator
+ XXX.levelgen.placement.VerticalDecorator
- XXX.levelgen.placement.WaterDepthThresholdConfiguration
+ XXX.levelgen.placement.WaterDepthThresholdDecorator
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
- XXX.levelgen.structure.JunglePyramidPiece$1
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
- XXX.levelgen.structure.MineShaftPieces$1
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
- XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
- XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
- XXX.levelgen.structure.NetherBridgePieces
+ XXX.levelgen.structure.NetherBridgePieces$1
- XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
- XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
- XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
- XXX.levelgen.structure.NetherBridgePieces$StartPiece
+ XXX.levelgen.structure.NetherFossilFeature
- XXX.levelgen.structure.NetherFossilFeature$FeatureStart
+ XXX.levelgen.structure.NetherFossilPieces
- XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ XXX.levelgen.structure.NoiseAffectingStructureStart
- XXX.levelgen.structure.OceanMonumentPieces
+ XXX.levelgen.structure.OceanMonumentPieces$1
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
- XXX.levelgen.structure.OceanRuinFeature
+ XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
- XXX.levelgen.structure.OceanRuinFeature$Type
+ XXX.levelgen.structure.OceanRuinPieces
- XXX.levelgen.structure.OceanRuinPieces$1
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.RuinedPortalPiece
- XXX.levelgen.structure.RuinedPortalPiece$Properties
+ XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.ShipwreckPieces
- XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ XXX.levelgen.structure.StrongholdPieces
- XXX.levelgen.structure.StrongholdPieces$1
+ XXX.levelgen.structure.StrongholdPieces$2
- XXX.levelgen.structure.StrongholdPieces$3
+ XXX.levelgen.structure.StrongholdPieces$ChestCorridor
- XXX.levelgen.structure.StrongholdPieces$FillerCorridor
+ XXX.levelgen.structure.StrongholdPieces$FiveCrossing
- XXX.levelgen.structure.StrongholdPieces$LeftTurn
+ XXX.levelgen.structure.StrongholdPieces$Library
- XXX.levelgen.structure.StrongholdPieces$PieceWeight
+ XXX.levelgen.structure.StrongholdPieces$PortalRoom
- XXX.levelgen.structure.StrongholdPieces$PrisonHall
+ XXX.levelgen.structure.StrongholdPieces$RightTurn
- XXX.levelgen.structure.StrongholdPieces$RoomCrossing
+ XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- XXX.levelgen.structure.StrongholdPieces$StairsDown
+ XXX.levelgen.structure.StrongholdPieces$StartPiece
- XXX.levelgen.structure.StrongholdPieces$Straight
+ XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructurePieceAccessor
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureStart$1
- XXX.levelgen.structure.SwamplandHutPiece
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.WoodlandMansionPieces
+ XXX.levelgen.structure.WoodlandMansionPieces$1
- XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
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
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolEntryType
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
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$1
+ XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetBannerPatternFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$1
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$1
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$1
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
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
+ XXX.loot.predicates.ConditionReference$1
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
+ XXX.loot.predicates.LocationCheck$1
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
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
+ XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$1
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.ValueCheckCondition$1
- XXX.loot.predicates.ValueCheckCondition$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$1
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.loot.predicates.WeatherCheck$Serializer
+ XXX.minecraft.world.package-info
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
+ XXX.newbiome.layer.LayerBiomes
- XXX.newbiome.layer.Layers
+ XXX.newbiome.layer.Layers$Category
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
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.placement.nether.CountMultiLayerDecorator
+ XXX.placement.nether.package-info
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveEntityPacket
- XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$1
- XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
- XXX.providers.nbt.ContextNbtProvider$InlineSerializer
+ XXX.providers.nbt.ContextNbtProvider$Serializer
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
- XXX.providers.nbt.StorageNbtProvider$1
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.BinomialDistributionGenerator$1
+ XXX.providers.number.BinomialDistributionGenerator$Serializer
- XXX.providers.number.ConstantValue
+ XXX.providers.number.ConstantValue$1
- XXX.providers.number.ConstantValue$InlineSerializer
+ XXX.providers.number.ConstantValue$Serializer
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.ScoreboardValue$1
+ XXX.providers.number.ScoreboardValue$Serializer
- XXX.providers.number.UniformGenerator
+ XXX.providers.number.UniformGenerator$1
- XXX.providers.number.UniformGenerator$Serializer
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$1
- XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
+ XXX.providers.score.ContextScoreboardNameProvider$Serializer
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider$1
- XXX.providers.score.FixedScoreboardNameProvider$Serializer
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$1
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$1
- XXX.storage.loot.GsonAdapterFactory$Builder
+ XXX.storage.loot.GsonAdapterFactory$InlineSerializer
- XXX.storage.loot.GsonAdapterFactory$JsonAdapter
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$1
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.IntRange$Serializer
- XXX.storage.loot.ItemModifierManager
+ XXX.storage.loot.ItemModifierManager$FunctionSequence
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
+ XXX.storage.loot.package-info
- XXX.storage.loot.PredicateManager
+ XXX.storage.loot.PredicateManager$1
- XXX.storage.loot.PredicateManager$CompositePredicate
+ XXX.storage.loot.Serializer
- XXX.storage.loot.SerializerType
+ XXX.storage.loot.ValidationContext
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
- XXX.world.level.package-info
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
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
net.minecraft.SharedConstants +1P
```
```
XXX.minecraft.client.Minecraft +9M -8M
```
```
XXX.client.multiplayer.ClientPacketListener +13M -14M
```
```
XXX.client.renderer.GameRenderer +62M -6M
```
```
XXX.minecraft.data.BlockFamilies +8P
```
```
XXX.minecraft.data.BlockFamily$Variant +1P
```
```
XXX.server.level.ServerPlayer -2M | -1P
```
```
XXX.minecraft.tags.BlockTags +1P
```
```
XXX.world.entity.Entity +4M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.Block +2M -2M
```
```
XXX.level.block.Blocks +5M -1M
```
```
XXX.level.block.FarmBlock +1M -1M
```
```
XXX.level.block.HayBlock +1M -1M
```
```
XXX.level.block.MagmaBlock +1M -1M
```
```
XXX.level.border.WorldBorder +1P
```
```
XXX.level.levelgen.Cavifier +1M -1M
```
```
XXX.level.levelgen.NoiseSampler +1M -2M | +1P -1P
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
+ CompletionStage lambda$delayTextureReload$37(CompletableFuture)
- CompletionStage lambda$delayTextureReload$38(CompletableFuture)
+ PackResources lambda$adaptV3$41(Supplier)
- PackResources lambda$adaptV3$42(Supplier)
+ PackResources lambda$adaptV4$42(Supplier)
- PackResources lambda$adaptV4$43(Supplier)
- String lambda$fillReport$35()
+ String lambda$fillReport$35(Options)
+ String lambda$fillReport$36(LanguageManager)
- String lambda$fillReport$36(Options)
- String lambda$fillReport$37(LanguageManager)
+ Style lambda$grabHugeScreenshot$40(File,Style)
- Style lambda$grabHugeScreenshot$41(File,Style)
+ Style lambda$grabPanoramixScreenshot$39(File,Style)
- Style lambda$grabPanoramixScreenshot$40(File,Style)
+ void lambda$grabPanoramixScreenshot$38(Component)
- void lambda$grabPanoramixScreenshot$39(Component)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
+ IllegalArgumentException lambda$handleCustomPayload$10(ResourceLocation)
- IllegalArgumentException lambda$handleCustomPayload$9(ResourceLocation)
+ void handleRemoveEntity(ClientboundRemoveEntitiesPacket)
- void handleRemoveEntity(ClientboundRemoveEntityPacket)
- void lambda$downloadCallback$7()
+ void lambda$downloadCallback$8()
- Void lambda$downloadCallback$8(Throwable)
+ Void lambda$downloadCallback$9(Throwable)
- void lambda$handleAddOrRemoveRecipes$3(ClientRecipeBook,Recipe)
+ void lambda$handleAddOrRemoveRecipes$4(ClientRecipeBook,Recipe)
- void lambda$handleAddOrRemoveRecipes$4(ClientRecipeBook,RecipeCollection)
+ void lambda$handleAddOrRemoveRecipes$5(ClientRecipeBook,RecipeCollection)
- void lambda$handleChunkBlocksUpdate$0(int,BlockPos,BlockState)
+ void lambda$handleChunkBlocksUpdate$1(int,BlockPos,BlockState)
- void lambda$handleGameEvent$2()
+ void lambda$handleGameEvent$3()
- void lambda$handlePlaceRecipe$11(AbstractContainerMenu,Recipe)
+ void lambda$handlePlaceRecipe$12(AbstractContainerMenu,Recipe)
+ void lambda$handleRemoveEntity$0(int)
- void lambda$handleResourcePack$6(String,String,boolean,ClientboundResourcePackPacket)
+ void lambda$handleResourcePack$7(String,String,boolean,ClientboundResourcePackPacket)
- void lambda$handleSetEquipment$1(Entity,Pair)
+ void lambda$handleSetEquipment$2(Entity,Pair)
- void lambda$handleSetPlayerTeamPacket$10(PlayerTeam,ClientboundSetPlayerTeamPacket$Parameters)
+ void lambda$handleSetPlayerTeamPacket$11(PlayerTeam,ClientboundSetPlayerTeamPacket$Parameters)
- void lambda$null$5(String,String,boolean,boolean)
+ void lambda$null$6(String,String,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.GameRenderer
</summary>

```diff
+ boolean lambda$pick$0(Entity)
- boolean lambda$pick$56(Entity)
+ String lambda$render$1()
+ String lambda$render$2()
+ String lambda$render$3(int,int)
+ String lambda$render$4()
- String lambda$render$57()
- String lambda$render$58()
- String lambda$render$59(int,int)
- String lambda$render$60()
- void lambda$reloadShaders$0(ShaderInstance)
- void lambda$reloadShaders$1(ShaderInstance)
- void lambda$reloadShaders$10(ShaderInstance)
- void lambda$reloadShaders$11(ShaderInstance)
- void lambda$reloadShaders$12(ShaderInstance)
- void lambda$reloadShaders$13(ShaderInstance)
- void lambda$reloadShaders$14(ShaderInstance)
- void lambda$reloadShaders$15(ShaderInstance)
- void lambda$reloadShaders$16(ShaderInstance)
- void lambda$reloadShaders$17(ShaderInstance)
- void lambda$reloadShaders$18(ShaderInstance)
- void lambda$reloadShaders$19(ShaderInstance)
- void lambda$reloadShaders$2(ShaderInstance)
- void lambda$reloadShaders$20(ShaderInstance)
- void lambda$reloadShaders$21(ShaderInstance)
- void lambda$reloadShaders$22(ShaderInstance)
- void lambda$reloadShaders$23(ShaderInstance)
- void lambda$reloadShaders$24(ShaderInstance)
- void lambda$reloadShaders$25(ShaderInstance)
- void lambda$reloadShaders$26(ShaderInstance)
- void lambda$reloadShaders$27(ShaderInstance)
- void lambda$reloadShaders$28(ShaderInstance)
- void lambda$reloadShaders$29(ShaderInstance)
- void lambda$reloadShaders$3(ShaderInstance)
- void lambda$reloadShaders$30(ShaderInstance)
- void lambda$reloadShaders$31(ShaderInstance)
- void lambda$reloadShaders$32(ShaderInstance)
- void lambda$reloadShaders$33(ShaderInstance)
- void lambda$reloadShaders$34(ShaderInstance)
- void lambda$reloadShaders$35(ShaderInstance)
- void lambda$reloadShaders$36(ShaderInstance)
- void lambda$reloadShaders$37(ShaderInstance)
- void lambda$reloadShaders$38(ShaderInstance)
- void lambda$reloadShaders$39(ShaderInstance)
- void lambda$reloadShaders$4(ShaderInstance)
- void lambda$reloadShaders$40(ShaderInstance)
- void lambda$reloadShaders$41(ShaderInstance)
- void lambda$reloadShaders$42(ShaderInstance)
- void lambda$reloadShaders$43(ShaderInstance)
- void lambda$reloadShaders$44(ShaderInstance)
- void lambda$reloadShaders$45(ShaderInstance)
- void lambda$reloadShaders$46(ShaderInstance)
- void lambda$reloadShaders$47(ShaderInstance)
- void lambda$reloadShaders$48(ShaderInstance)
- void lambda$reloadShaders$49(ShaderInstance)
- void lambda$reloadShaders$5(ShaderInstance)
- void lambda$reloadShaders$50(ShaderInstance)
- void lambda$reloadShaders$51(ShaderInstance)
- void lambda$reloadShaders$52(ShaderInstance)
- void lambda$reloadShaders$53(ShaderInstance)
- void lambda$reloadShaders$54(Pair)
- void lambda$reloadShaders$55(Pair)
- void lambda$reloadShaders$6(ShaderInstance)
- void lambda$reloadShaders$7(ShaderInstance)
- void lambda$reloadShaders$8(ShaderInstance)
- void lambda$reloadShaders$9(ShaderInstance)
+ void lambda$takeAutoScreenshot$5(NativeImage)
- void lambda$takeAutoScreenshot$61(NativeImage)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ void cancelRemoveEntity(Entity)
+ void sendRemoveEntity(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- float getXRot()
- float getYRot()
- void setXRot(float)
- void setYRot(float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ void fallOn(Level,BlockPos,Entity,float)
- void fallOn(Level,BlockState,BlockPos,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ void fallOn(Level,BlockPos,Entity,float)
- void fallOn(Level,BlockState,BlockPos,Entity,float)
- void stepOn(Level,BlockPos,BlockState,Entity)
+ void stepOn(Level,BlockPos,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
+ boolean lambda$static$50(BlockState,BlockGetter,BlockPos)
- boolean lambda$static$54(BlockState,BlockGetter,BlockPos)
- int lambda$static$50(BlockState)
- int lambda$static$51(BlockState)
- int lambda$static$52(BlockState)
- int lambda$static$53(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FarmBlock
</summary>

```diff
+ void fallOn(Level,BlockPos,Entity,float)
- void fallOn(Level,BlockState,BlockPos,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HayBlock
</summary>

```diff
+ void fallOn(Level,BlockPos,Entity,float)
- void fallOn(Level,BlockState,BlockPos,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.MagmaBlock
</summary>

```diff
- void stepOn(Level,BlockPos,BlockState,Entity)
+ void stepOn(Level,BlockPos,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Cavifier
</summary>

```diff
+ double cavify(int,int,int,double)
- double modifyNoise(double,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseSampler
</summary>

```diff
+ double cavify(int,int,int,double)
+ void <init>(BiomeSource,int,int,int,NoiseSettings,BlendedNoise,SimplexNoise,PerlinNoise,Cavifier)
- void <init>(BiomeSource,int,int,int,NoiseSettings,BlendedNoise,SimplexNoise,PerlinNoise,NoiseModifier)
```

</details>
</details>
<hr/>