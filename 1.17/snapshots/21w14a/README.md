<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 21w14a ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>21w14a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2021-04-07T14:04:09+00:00</td></tr>
<tr><th>SHA1</th><td>7a67f727cc7847efc3753de26a32d051348b5fba</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/7a67f727cc7847efc3753de26a32d051348b5fba/21w14a.json">https://piston-meta.mojang.com/v1/packages/7a67f727cc7847efc3753de26a32d051348b5fba/21w14a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json">https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/0cb279c49ea3afda25c9d7257bef650e8dc17429/server.jar">https://piston-data.mojang.com/v1/objects/0cb279c49ea3afda25c9d7257bef650e8dc17429/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/339fc034e315b00cc524ba9f9d08ab8e71f831ad/server.txt">https://piston-data.mojang.com/v1/objects/339fc034e315b00cc524ba9f9d08ab8e71f831ad/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/4af7eb4770d3e708d287db3bf023d4bbc60465b0/client.jar">https://piston-data.mojang.com/v1/objects/4af7eb4770d3e708d287db3bf023d4bbc60465b0/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/559d6456faf79734c7663513d5d27368a5288daf/client.txt">https://piston-data.mojang.com/v1/objects/559d6456faf79734c7663513d5d27368a5288daf/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/21w13a">21w13a</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
+ net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
```

</details>


<details><summary>net.minecraft.SharedConstants</summary>

```diff
+ void tryDetectVersion()
```

</details>


<details><summary>net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen</summary>

```diff
- void onClose()
```

</details>


<details><summary>net.minecraft.core.Registry</summary>

```diff
- DataResult lambda$decode$56(Number)
+ DataResult lambda$decode$57(Number)
- DataResult lambda$decode$58(Pair)
+ DataResult lambda$decode$59(Pair)
- Object lambda$keys$59(DynamicOps,ResourceLocation)
+ Object lambda$keys$60(DynamicOps,ResourceLocation)
- Pair lambda$decode$57(DynamicOps,Object)
+ Pair lambda$decode$58(DynamicOps,Object)
+ String lambda$new$56(ResourceKey)
```

</details>


<details><summary>net.minecraft.world.entity.Entity</summary>

```diff
+ void onClientRemoval()
```

</details>


<details><summary>net.minecraft.world.level.biome.Biome</summary>

```diff
+ void buildSurfaceAt(Random,ChunkAccess,int,int,int,double,BlockState,BlockState,int,int,long)
- void buildSurfaceAt(Random,ChunkAccess,int,int,int,double,BlockState,BlockState,int,long)
```

</details>


<details><summary>net.minecraft.world.level.chunk.BulkSectionAccess</summary>

```diff
+ LevelChunkSection lambda$getSection$0(BlockPos,int,long)
- LevelChunkSection lambda$getSection$0(BlockPos,long)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseGeneratorSettings</summary>

```diff
+ int getMinSurfaceLevel()
- void <init>(StructureSettings,NoiseSettings,BlockState,BlockState,int,int,int,boolean,boolean,boolean,boolean)
+ void <init>(StructureSettings,NoiseSettings,BlockState,BlockState,int,int,int,int,boolean,boolean,boolean,boolean)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart</summary>

```diff
+ void generatePieces(ChunkPos)
+ void placeInChunk(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NoiseAffectingStructureStart</summary>

```diff
+ BoundingBox createBoundingBox()
- BoundingBox getBoundingBox()
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


### Server




<details><summary>Classes</summary>

```diff
+ net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
```

</details>


<details><summary>net.minecraft.data.loot.BlockLoot</summary>

```diff
+ LootTable$Builder lambda$accept$78(Block)
+ LootTable$Builder lambda$accept$79(Block)
+ LootTable$Builder lambda$accept$80(Block)
+ LootTable$Builder lambda$accept$81(Block)
+ LootTable$Builder lambda$accept$82(Block)
+ LootTable$Builder lambda$accept$83(Block)
- LootTable$Builder lambda$dropPottedContents$78(Block)
+ LootTable$Builder lambda$dropPottedContents$84(Block)
```

</details>


<details><summary>net.minecraft.data.recipes.RecipeProvider</summary>

```diff
+ void oreBlasting(Consumer,List,ItemLike,float,int)
+ void oreCooking(Consumer,SimpleCookingSerializer,List,ItemLike,float,int,String)
+ void oreSmelting(Consumer,List,ItemLike,float,int)
- void stair(Consumer,ItemLike,ItemLike)
```

</details>


<details><summary>net.minecraft.server.Bootstrap</summary>

```diff
+ RuntimeException createBootstrapException(Supplier)
+ String lambda$validate$2()
+ void checkBootstrapCalled(Supplier)
- void lambda$validate$2(String)
+ void lambda$validate$3(String)
```

</details>


<details><summary>net.minecraft.world.entity.projectile.FishingHook</summary>

```diff
- void bringInHookedEntity()
+ void onClientRemoval()
+ void pullEntity(Entity)
- void setHookedEntity()
+ void setHookedEntity(Entity)
+ void updateOwnerInfo(FishingHook)
```

</details>


<details><summary>net.minecraft.world.entity.projectile.ThrownPotion</summary>

```diff
- void dowseFire(BlockPos,Direction)
+ void dowseFire(BlockPos)
```

</details>


<details><summary>net.minecraft.world.inventory.InventoryMenu</summary>

```diff
+ boolean isHotbarSlot(int)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.Aquifer</summary>

```diff
+ void <init>(int,int,NormalNoise,NormalNoise,NoiseGeneratorSettings,NoiseSampler,int,int)
- void <init>(int,int,NormalNoise,NormalNoise,NoiseGeneratorSettings,NoiseSampler,int)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.StructureStart</summary>

```diff
+ BoundingBox createBoundingBox()
+ IllegalStateException lambda$createBoundingBox$0()
- IllegalStateException lambda$getBoundingBox$0()
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,BlockState,BlockState,BlockState,int,int)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,BlockState,BlockState,BlockState,int)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder</summary>

```diff
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,int,long,SurfaceBuilderConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
- void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
```

</details>


# Folder structure

<details><summary>data/</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_slab_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_slab_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_slab_from_waxed_oxidized_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_stairs_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_cut_copper.json
+ minecraft/advancements/recipes/misc/coal_from_blasting_coal_ore.json
+ minecraft/advancements/recipes/misc/coal_from_blasting_deepslate_coal_ore.json
- minecraft/advancements/recipes/misc/coal_from_blasting.json
+ minecraft/advancements/recipes/misc/coal_from_smelting_coal_ore.json
+ minecraft/advancements/recipes/misc/coal_from_smelting_deepslate_coal_ore.json
- minecraft/advancements/recipes/misc/coal_from_smelting.json
+ minecraft/advancements/recipes/misc/copper_ingot_from_blasting_copper_ore.json
+ minecraft/advancements/recipes/misc/copper_ingot_from_blasting_deepslate_copper_ore.json
+ minecraft/advancements/recipes/misc/copper_ingot_from_blasting_raw_copper.json
- minecraft/advancements/recipes/misc/copper_ingot_from_blasting.json
+ minecraft/advancements/recipes/misc/copper_ingot_from_smelting_copper_ore.json
+ minecraft/advancements/recipes/misc/copper_ingot_from_smelting_deepslate_copper_ore.json
+ minecraft/advancements/recipes/misc/copper_ingot_from_smelting_raw_copper.json
- minecraft/advancements/recipes/misc/copper_ingot.json
+ minecraft/advancements/recipes/misc/diamond_from_blasting_deepslate_diamond_ore.json
+ minecraft/advancements/recipes/misc/diamond_from_blasting_diamond_ore.json
- minecraft/advancements/recipes/misc/diamond_from_blasting.json
+ minecraft/advancements/recipes/misc/diamond_from_smelting_deepslate_diamond_ore.json
+ minecraft/advancements/recipes/misc/diamond_from_smelting_diamond_ore.json
- minecraft/advancements/recipes/misc/diamond_from_smelting.json
+ minecraft/advancements/recipes/misc/emerald_from_blasting_deepslate_emerald_ore.json
+ minecraft/advancements/recipes/misc/emerald_from_blasting_emerald_ore.json
- minecraft/advancements/recipes/misc/emerald_from_blasting.json
+ minecraft/advancements/recipes/misc/emerald_from_smelting_deepslate_emerald_ore.json
+ minecraft/advancements/recipes/misc/emerald_from_smelting_emerald_ore.json
- minecraft/advancements/recipes/misc/emerald_from_smelting.json
+ minecraft/advancements/recipes/misc/gold_ingot_from_blasting_deepslate_gold_ore.json
+ minecraft/advancements/recipes/misc/gold_ingot_from_blasting_gold_ore.json
+ minecraft/advancements/recipes/misc/gold_ingot_from_blasting_raw_gold.json
- minecraft/advancements/recipes/misc/gold_ingot_from_blasting.json
+ minecraft/advancements/recipes/misc/gold_ingot_from_smelting_deepslate_gold_ore.json
+ minecraft/advancements/recipes/misc/gold_ingot_from_smelting_gold_ore.json
+ minecraft/advancements/recipes/misc/gold_ingot_from_smelting_raw_gold.json
- minecraft/advancements/recipes/misc/gold_ingot.json
+ minecraft/advancements/recipes/misc/iron_ingot_from_blasting_deepslate_iron_ore.json
+ minecraft/advancements/recipes/misc/iron_ingot_from_blasting_iron_ore.json
+ minecraft/advancements/recipes/misc/iron_ingot_from_blasting_raw_iron.json
- minecraft/advancements/recipes/misc/iron_ingot_from_blasting.json
+ minecraft/advancements/recipes/misc/iron_ingot_from_smelting_deepslate_iron_ore.json
+ minecraft/advancements/recipes/misc/iron_ingot_from_smelting_iron_ore.json
+ minecraft/advancements/recipes/misc/iron_ingot_from_smelting_raw_iron.json
- minecraft/advancements/recipes/misc/iron_ingot.json
- minecraft/advancements/recipes/misc/lapis_from_blasting.json
- minecraft/advancements/recipes/misc/lapis_from_smelting.json
+ minecraft/advancements/recipes/misc/lapis_lazuli_from_blasting_deepslate_lapis_ore.json
+ minecraft/advancements/recipes/misc/lapis_lazuli_from_blasting_lapis_ore.json
+ minecraft/advancements/recipes/misc/lapis_lazuli_from_smelting_deepslate_lapis_ore.json
+ minecraft/advancements/recipes/misc/lapis_lazuli_from_smelting_lapis_ore.json
+ minecraft/advancements/recipes/redstone/redstone_from_blasting_deepslate_redstone_ore.json
+ minecraft/advancements/recipes/redstone/redstone_from_blasting_redstone_ore.json
- minecraft/advancements/recipes/redstone/redstone_from_blasting.json
+ minecraft/advancements/recipes/redstone/redstone_from_smelting_deepslate_redstone_ore.json
+ minecraft/advancements/recipes/redstone/redstone_from_smelting_redstone_ore.json
- minecraft/advancements/recipes/redstone/redstone_from_smelting.json
+ minecraft/loot_tables/blocks/waxed_oxidized_copper.json
+ minecraft/loot_tables/blocks/waxed_oxidized_cut_copper_slab.json
+ minecraft/loot_tables/blocks/waxed_oxidized_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/waxed_oxidized_cut_copper.json
+ minecraft/recipes/coal_from_blasting_coal_ore.json
+ minecraft/recipes/coal_from_blasting_deepslate_coal_ore.json
- minecraft/recipes/coal_from_blasting.json
+ minecraft/recipes/coal_from_smelting_coal_ore.json
+ minecraft/recipes/coal_from_smelting_deepslate_coal_ore.json
- minecraft/recipes/coal_from_smelting.json
+ minecraft/recipes/copper_ingot_from_blasting_copper_ore.json
+ minecraft/recipes/copper_ingot_from_blasting_deepslate_copper_ore.json
+ minecraft/recipes/copper_ingot_from_blasting_raw_copper.json
- minecraft/recipes/copper_ingot_from_blasting.json
+ minecraft/recipes/copper_ingot_from_smelting_copper_ore.json
+ minecraft/recipes/copper_ingot_from_smelting_deepslate_copper_ore.json
+ minecraft/recipes/copper_ingot_from_smelting_raw_copper.json
- minecraft/recipes/copper_ingot.json
+ minecraft/recipes/diamond_from_blasting_deepslate_diamond_ore.json
+ minecraft/recipes/diamond_from_blasting_diamond_ore.json
- minecraft/recipes/diamond_from_blasting.json
+ minecraft/recipes/diamond_from_smelting_deepslate_diamond_ore.json
+ minecraft/recipes/diamond_from_smelting_diamond_ore.json
- minecraft/recipes/diamond_from_smelting.json
+ minecraft/recipes/emerald_from_blasting_deepslate_emerald_ore.json
+ minecraft/recipes/emerald_from_blasting_emerald_ore.json
- minecraft/recipes/emerald_from_blasting.json
+ minecraft/recipes/emerald_from_smelting_deepslate_emerald_ore.json
+ minecraft/recipes/emerald_from_smelting_emerald_ore.json
- minecraft/recipes/emerald_from_smelting.json
+ minecraft/recipes/gold_ingot_from_blasting_deepslate_gold_ore.json
+ minecraft/recipes/gold_ingot_from_blasting_gold_ore.json
+ minecraft/recipes/gold_ingot_from_blasting_raw_gold.json
- minecraft/recipes/gold_ingot_from_blasting.json
+ minecraft/recipes/gold_ingot_from_smelting_deepslate_gold_ore.json
+ minecraft/recipes/gold_ingot_from_smelting_gold_ore.json
+ minecraft/recipes/gold_ingot_from_smelting_raw_gold.json
- minecraft/recipes/gold_ingot.json
+ minecraft/recipes/iron_ingot_from_blasting_deepslate_iron_ore.json
+ minecraft/recipes/iron_ingot_from_blasting_iron_ore.json
+ minecraft/recipes/iron_ingot_from_blasting_raw_iron.json
- minecraft/recipes/iron_ingot_from_blasting.json
+ minecraft/recipes/iron_ingot_from_smelting_deepslate_iron_ore.json
+ minecraft/recipes/iron_ingot_from_smelting_iron_ore.json
+ minecraft/recipes/iron_ingot_from_smelting_raw_iron.json
- minecraft/recipes/iron_ingot.json
- minecraft/recipes/lapis_from_blasting.json
- minecraft/recipes/lapis_from_smelting.json
+ minecraft/recipes/lapis_lazuli_from_blasting_deepslate_lapis_ore.json
+ minecraft/recipes/lapis_lazuli_from_blasting_lapis_ore.json
+ minecraft/recipes/lapis_lazuli_from_smelting_deepslate_lapis_ore.json
+ minecraft/recipes/lapis_lazuli_from_smelting_lapis_ore.json
+ minecraft/recipes/redstone_from_blasting_deepslate_redstone_ore.json
+ minecraft/recipes/redstone_from_blasting_redstone_ore.json
- minecraft/recipes/redstone_from_blasting.json
+ minecraft/recipes/redstone_from_smelting_deepslate_redstone_ore.json
+ minecraft/recipes/redstone_from_smelting_redstone_ore.json
- minecraft/recipes/redstone_from_smelting.json
+ minecraft/recipes/waxed_oxidized_copper_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_cut_copper_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_cut_copper_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/recipes/waxed_oxidized_cut_copper_slab_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_cut_copper_slab_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/recipes/waxed_oxidized_cut_copper_slab_from_waxed_oxidized_cut_copper_stonecutting.json
+ minecraft/recipes/waxed_oxidized_cut_copper_slab.json
+ minecraft/recipes/waxed_oxidized_cut_copper_stairs_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/recipes/waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_cut_copper_stonecutting.json
+ minecraft/recipes/waxed_oxidized_cut_copper_stairs.json
+ minecraft/recipes/waxed_oxidized_cut_copper.json
```

</details>


<details><summary>assets/</summary>

```diff
+ minecraft/blockstates/waxed_oxidized_copper.json
+ minecraft/blockstates/waxed_oxidized_cut_copper_slab.json
+ minecraft/blockstates/waxed_oxidized_cut_copper_stairs.json
+ minecraft/blockstates/waxed_oxidized_cut_copper.json
+ minecraft/models/item/raw_copper.json
+ minecraft/models/item/raw_gold.json
+ minecraft/models/item/raw_iron.json
+ minecraft/models/item/waxed_oxidized_copper.json
+ minecraft/models/item/waxed_oxidized_cut_copper_slab.json
+ minecraft/models/item/waxed_oxidized_cut_copper_stairs.json
+ minecraft/models/item/waxed_oxidized_cut_copper.json
+ minecraft/textures/item/raw_copper.png
+ minecraft/textures/item/raw_gold.png
+ minecraft/textures/item/raw_iron.png
```

</details>


# Registries

<details><summary>block.txt</summary>

```diff
+ minecraft:waxed_oxidized_copper
+ minecraft:waxed_oxidized_cut_copper
+ minecraft:waxed_oxidized_cut_copper_slab
+ minecraft:waxed_oxidized_cut_copper_stairs
```

</details>


<details><summary>item.txt</summary>

```diff
+ minecraft:raw_copper
+ minecraft:raw_gold
+ minecraft:raw_iron
+ minecraft:waxed_oxidized_copper
+ minecraft:waxed_oxidized_cut_copper
+ minecraft:waxed_oxidized_cut_copper_slab
+ minecraft:waxed_oxidized_cut_copper_stairs
```

</details>


<details><summary>worldgen/carver.txt</summary>

```diff
+ minecraft:underwater_canyon
+ minecraft:underwater_cave
```

</details>


# Tags

<details><summary>blocks/slabs.json</summary>

```diff
+ minecraft:waxed_oxidized_cut_copper_slab
```

</details>


<details><summary>blocks/stairs.json</summary>

```diff
+ minecraft:waxed_oxidized_cut_copper_stairs
```

</details>


<details><summary>items/piglin_loved.json</summary>

```diff
+ minecraft:raw_gold
```

</details>


<details><summary>items/slabs.json</summary>

```diff
+ minecraft:waxed_oxidized_cut_copper_slab
```

</details>


<details><summary>items/stairs.json</summary>

```diff
+ minecraft:waxed_oxidized_cut_copper_stairs
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ block.minecraft.waxed_oxidized_copper
+ block.minecraft.waxed_oxidized_cut_copper
+ block.minecraft.waxed_oxidized_cut_copper_slab
+ block.minecraft.waxed_oxidized_cut_copper_stairs
+ item.minecraft.raw_copper
+ item.minecraft.raw_gold
+ item.minecraft.raw_iron
```

</details>


# Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/building_blocks/waxed_oxidized_copper_from_honeycomb.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_from_honeycomb.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_from_waxed_oxidized_copper_stonecutting.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_slab_from_honeycomb.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_slab_from_waxed_oxidized_copper_stonecutting.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_slab_from_waxed_oxidized_cut_copper_stonecutting.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_slab.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_stairs_from_honeycomb.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_copper_stonecutting.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_cut_copper_stonecutting.json
+ recipes/building_blocks/waxed_oxidized_cut_copper_stairs.json
+ recipes/building_blocks/waxed_oxidized_cut_copper.json
+ recipes/misc/coal_from_blasting_coal_ore.json
+ recipes/misc/coal_from_blasting_deepslate_coal_ore.json
- recipes/misc/coal_from_blasting.json
+ recipes/misc/coal_from_smelting_coal_ore.json
+ recipes/misc/coal_from_smelting_deepslate_coal_ore.json
- recipes/misc/coal_from_smelting.json
+ recipes/misc/copper_ingot_from_blasting_copper_ore.json
+ recipes/misc/copper_ingot_from_blasting_deepslate_copper_ore.json
+ recipes/misc/copper_ingot_from_blasting_raw_copper.json
- recipes/misc/copper_ingot_from_blasting.json
+ recipes/misc/copper_ingot_from_smelting_copper_ore.json
+ recipes/misc/copper_ingot_from_smelting_deepslate_copper_ore.json
+ recipes/misc/copper_ingot_from_smelting_raw_copper.json
- recipes/misc/copper_ingot.json
+ recipes/misc/diamond_from_blasting_deepslate_diamond_ore.json
+ recipes/misc/diamond_from_blasting_diamond_ore.json
- recipes/misc/diamond_from_blasting.json
+ recipes/misc/diamond_from_smelting_deepslate_diamond_ore.json
+ recipes/misc/diamond_from_smelting_diamond_ore.json
- recipes/misc/diamond_from_smelting.json
+ recipes/misc/emerald_from_blasting_deepslate_emerald_ore.json
+ recipes/misc/emerald_from_blasting_emerald_ore.json
- recipes/misc/emerald_from_blasting.json
+ recipes/misc/emerald_from_smelting_deepslate_emerald_ore.json
+ recipes/misc/emerald_from_smelting_emerald_ore.json
- recipes/misc/emerald_from_smelting.json
+ recipes/misc/gold_ingot_from_blasting_deepslate_gold_ore.json
+ recipes/misc/gold_ingot_from_blasting_gold_ore.json
+ recipes/misc/gold_ingot_from_blasting_raw_gold.json
- recipes/misc/gold_ingot_from_blasting.json
+ recipes/misc/gold_ingot_from_smelting_deepslate_gold_ore.json
+ recipes/misc/gold_ingot_from_smelting_gold_ore.json
+ recipes/misc/gold_ingot_from_smelting_raw_gold.json
- recipes/misc/gold_ingot.json
+ recipes/misc/iron_ingot_from_blasting_deepslate_iron_ore.json
+ recipes/misc/iron_ingot_from_blasting_iron_ore.json
+ recipes/misc/iron_ingot_from_blasting_raw_iron.json
- recipes/misc/iron_ingot_from_blasting.json
+ recipes/misc/iron_ingot_from_smelting_deepslate_iron_ore.json
+ recipes/misc/iron_ingot_from_smelting_iron_ore.json
+ recipes/misc/iron_ingot_from_smelting_raw_iron.json
- recipes/misc/iron_ingot.json
- recipes/misc/lapis_from_blasting.json
- recipes/misc/lapis_from_smelting.json
+ recipes/misc/lapis_lazuli_from_blasting_deepslate_lapis_ore.json
+ recipes/misc/lapis_lazuli_from_blasting_lapis_ore.json
+ recipes/misc/lapis_lazuli_from_smelting_deepslate_lapis_ore.json
+ recipes/misc/lapis_lazuli_from_smelting_lapis_ore.json
+ recipes/redstone/redstone_from_blasting_deepslate_redstone_ore.json
+ recipes/redstone/redstone_from_blasting_redstone_ore.json
- recipes/redstone/redstone_from_blasting.json
+ recipes/redstone/redstone_from_smelting_deepslate_redstone_ore.json
+ recipes/redstone/redstone_from_smelting_redstone_ore.json
- recipes/redstone/redstone_from_smelting.json
```

</details>


<details><summary>loot_tables.txt</summary>

```diff
+ blocks/waxed_oxidized_copper.json
+ blocks/waxed_oxidized_cut_copper_slab.json
+ blocks/waxed_oxidized_cut_copper_stairs.json
+ blocks/waxed_oxidized_cut_copper.json
```

</details>


<details><summary>recipes.txt</summary>

```diff
+ coal_from_blasting_coal_ore.json
+ coal_from_blasting_deepslate_coal_ore.json
- coal_from_blasting.json
+ coal_from_smelting_coal_ore.json
+ coal_from_smelting_deepslate_coal_ore.json
- coal_from_smelting.json
+ copper_ingot_from_blasting_copper_ore.json
+ copper_ingot_from_blasting_deepslate_copper_ore.json
+ copper_ingot_from_blasting_raw_copper.json
- copper_ingot_from_blasting.json
+ copper_ingot_from_smelting_copper_ore.json
+ copper_ingot_from_smelting_deepslate_copper_ore.json
+ copper_ingot_from_smelting_raw_copper.json
- copper_ingot.json
+ diamond_from_blasting_deepslate_diamond_ore.json
+ diamond_from_blasting_diamond_ore.json
- diamond_from_blasting.json
+ diamond_from_smelting_deepslate_diamond_ore.json
+ diamond_from_smelting_diamond_ore.json
- diamond_from_smelting.json
+ emerald_from_blasting_deepslate_emerald_ore.json
+ emerald_from_blasting_emerald_ore.json
- emerald_from_blasting.json
+ emerald_from_smelting_deepslate_emerald_ore.json
+ emerald_from_smelting_emerald_ore.json
- emerald_from_smelting.json
+ gold_ingot_from_blasting_deepslate_gold_ore.json
+ gold_ingot_from_blasting_gold_ore.json
+ gold_ingot_from_blasting_raw_gold.json
- gold_ingot_from_blasting.json
+ gold_ingot_from_smelting_deepslate_gold_ore.json
+ gold_ingot_from_smelting_gold_ore.json
+ gold_ingot_from_smelting_raw_gold.json
- gold_ingot.json
+ iron_ingot_from_blasting_deepslate_iron_ore.json
+ iron_ingot_from_blasting_iron_ore.json
+ iron_ingot_from_blasting_raw_iron.json
- iron_ingot_from_blasting.json
+ iron_ingot_from_smelting_deepslate_iron_ore.json
+ iron_ingot_from_smelting_iron_ore.json
+ iron_ingot_from_smelting_raw_iron.json
- iron_ingot.json
- lapis_from_blasting.json
- lapis_from_smelting.json
+ lapis_lazuli_from_blasting_deepslate_lapis_ore.json
+ lapis_lazuli_from_blasting_lapis_ore.json
+ lapis_lazuli_from_smelting_deepslate_lapis_ore.json
+ lapis_lazuli_from_smelting_lapis_ore.json
+ redstone_from_blasting_deepslate_redstone_ore.json
+ redstone_from_blasting_redstone_ore.json
- redstone_from_blasting.json
+ redstone_from_smelting_deepslate_redstone_ore.json
+ redstone_from_smelting_redstone_ore.json
- redstone_from_smelting.json
+ waxed_oxidized_copper_from_honeycomb.json
+ waxed_oxidized_cut_copper_from_honeycomb.json
+ waxed_oxidized_cut_copper_from_waxed_oxidized_copper_stonecutting.json
+ waxed_oxidized_cut_copper_slab_from_honeycomb.json
+ waxed_oxidized_cut_copper_slab_from_waxed_oxidized_copper_stonecutting.json
+ waxed_oxidized_cut_copper_slab_from_waxed_oxidized_cut_copper_stonecutting.json
+ waxed_oxidized_cut_copper_slab.json
+ waxed_oxidized_cut_copper_stairs_from_honeycomb.json
+ waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_copper_stonecutting.json
+ waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_cut_copper_stonecutting.json
+ waxed_oxidized_cut_copper_stairs.json
+ waxed_oxidized_cut_copper.json
```

</details>


<details><summary>textures.txt</summary>

```diff
+ item/raw_copper.png
+ item/raw_gold.png
+ item/raw_iron.png
```

</details>
