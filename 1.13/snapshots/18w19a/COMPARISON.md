## Comparison with [18w16a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w16a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Blocks](#blocks)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">18w16a</th><th>18w19a</th></tr><tr><td>com.mojang:brigadier</td><td><pre>0.1.24</pre></td><td><pre>0.1.25</pre></td></tr></table>
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
- sea_grass.json
+ seagrass.json
- tall_sea_grass.json
+ tall_seagrass.json
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
- biome.minecraft.cold_deep_ocean: Deep Cold Ocean
+ biome.minecraft.deep_cold_ocean: Deep Cold Ocean
+ biome.minecraft.deep_frozen_ocean: Deep Frozen Ocean
+ biome.minecraft.deep_lukewarm_ocean: Deep Lukewarm Ocean
+ biome.minecraft.deep_warm_ocean: Deep Warm Ocean
- biome.minecraft.frozen_deep_ocean: Deep Frozen Ocean
- biome.minecraft.lukewarm_deep_ocean: Deep Lukewarm Ocean
- biome.minecraft.warm_deep_ocean: Warm Deep Ocean
- block.minecraft.sea_grass: Sea Grass
+ block.minecraft.seagrass: Seagrass
- block.minecraft.tall_sea_grass: Tall Sea Grass
+ block.minecraft.tall_seagrass: Tall Seagrass
+ effect.dolphins_grace: Dolphin's Grace
+ entity.minecraft.pufferfish: Pufferfish
+ generator.minecraft.caves: Caves
+ generator.minecraft.floating_islands: Floating Islands
- generator.minecraft.nether: Nether
- generator.minecraft.overworld: Overworld
+ generator.minecraft.surface: Surface
- generator.minecraft.the_end: The End
+ gui.recipebook.toggleRecipes.smeltable: Showing smeltable
- item.minecraft.puffer_fish_spawn_egg: Spawn Puffer Fish
+ item.minecraft.pufferfish_spawn_egg: Spawn Pufferfish
+ multiplayer.disconnect.banned_ip.expiration: 
Your ban will be removed on %s
+ multiplayer.disconnect.banned_ip.reason: Your IP address is banned from this server.
Reason: %s
+ multiplayer.disconnect.banned.expiration: 
Your ban will be removed on %s
+ multiplayer.disconnect.banned.reason: You are banned from this server.
Reason: %s
+ multiplayer.disconnect.name_taken: That name is already taken.
+ multiplayer.disconnect.not_whitelisted: You are not white-listed on this server!
+ multiplayer.disconnect.server_full: The server is full!
+ subtitles.entity.parrot.imitate.drowned: Parrot gurgles
+ subtitles.entity.skeleton_horse.swim: Skeleton Horse swims
+ subtitles.entity.skeleton_horse.water_ambient: Skeleton Horse cries
+ subtitles.entity.skeleton_horse.water_gallop: Skeleton Horse gallops
+ subtitles.entity.skeleton_horse.water_jump: Skeleton Horse jumps
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>18w16a</th><th>18w19a</th></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.pufferfish_bucket</div></th><td>Puffer Fish Bucket</td><td>Pufferfish Bucket</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.clownfish</div></th><td>Clownfish</td><td>Tropical Fish</td></tr>
<tr><th align="left"><div style="width:290px">debug.copy_location.help</div></th><td>F3 + C = Copy location as /tp command</td><td>F3 + C = Copy location as /tp command, hold F3 + C to crash the game</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.cold_beach</div></th><td>Cold Beach</td><td>Snowy Beach</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.extreme_hills</div></th><td>Extreme Hills</td><td>Mountains</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.extreme_hills_with_trees</div></th><td>Extreme Hills+</td><td>Wooded Mountains</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.forest_hills</div></th><td>Forest Hills</td><td>Wooded Hills</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.ice_flats</div></th><td>Ice Plains</td><td>Snowy Tundra</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.ice_mountains</div></th><td>Ice Mountains</td><td>Snowy Mountains</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mesa_clear_rock</div></th><td>Mesa Plateau</td><td>Badlands Plateau</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mesa</div></th><td>Mesa</td><td>Badlands</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mesa_rock</div></th><td>Mesa Forest Plateau</td><td>Wooded Badlands Plateau</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mushroom_island</div></th><td>Mushroom Island</td><td>Mushroom Fields</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mushroom_island_shore</div></th><td>Mushroom Island Shore</td><td>Mushroom Field Shore</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_birch_forest_hills</div></th><td>Mutated Birch Forest Hills</td><td>Tall Birch Hills</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_birch_forest</div></th><td>Mutated Birch Forest</td><td>Tall Birch Forest</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_desert</div></th><td>Mutated Desert</td><td>Desert Lakes</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_extreme_hills</div></th><td>Mutated Extreme Hills</td><td>Gravelly Mountains</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_extreme_hills_with_trees</div></th><td>Mutated Extreme Hills+</td><td>Gravelly Mountains+</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_ice_flats</div></th><td>Ice Plains Spikes</td><td>Ice Spikes</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_jungle_edge</div></th><td>Mutated Jungle Edge</td><td>Modified Jungle Edge</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_jungle</div></th><td>Mutated Jungle</td><td>Modified Jungle</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_mesa_clear_rock</div></th><td>Mutated Mesa Plateau</td><td>Modified Badlands Plateau</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_mesa</div></th><td>Mesa (Bryce)</td><td>Eroded Badlands</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_mesa_rock</div></th><td>Mutated Mesa Forest Plateau</td><td>Modified Wooded Badlands Plateau</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_redwood_taiga_hills</div></th><td>Mutated Redwood Taiga Hills</td><td>Giant Spruce Taiga Hills</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_redwood_taiga</div></th><td>Mega Spruce Taiga</td><td>Giant Spruce Taiga</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_roofed_forest</div></th><td>Mutated Roofed Forest</td><td>Dark Forest Hills</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_savanna</div></th><td>Mutated Savanna</td><td>Shattered Savanna</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_savanna_rock</div></th><td>Mutated Savanna Plateau</td><td>Shattered Savanna Plateau</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_swampland</div></th><td>Mutated Swampland</td><td>Swamp Hills</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_taiga_cold</div></th><td>Mutated Cold Taiga</td><td>Snowy Taiga Mountains</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.mutated_taiga</div></th><td>Mutated Taiga</td><td>Taiga Mountains</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.redwood_taiga_hills</div></th><td>Mega Taiga Hills</td><td>Giant Tree Taiga Hills</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.redwood_taiga</div></th><td>Mega Taiga</td><td>Giant Tree Taiga</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.roofed_forest</div></th><td>Roofed Forest</td><td>Dark Forest</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.sky_island_barren</div></th><td>The End - Barren island</td><td>End Barrens</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.sky_island_high</div></th><td>The End - High island</td><td>End Highlands</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.sky_island_low</div></th><td>The End - Floating islands</td><td>Small End Islands</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.sky_island_medium</div></th><td>The End - Medium island</td><td>End Midlands</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.smaller_extreme_hills</div></th><td>Extreme Hills Edge</td><td>Mountain Edge</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.stone_beach</div></th><td>Stone Beach</td><td>Stone Shore</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.swampland</div></th><td>Swampland</td><td>Swamp</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.taiga_cold</div></th><td>Cold Taiga</td><td>Snowy Taiga</td></tr>
<tr><th align="left"><div style="width:290px">biome.minecraft.taiga_cold_hills</div></th><td>Cold Taiga Hills</td><td>Snowy Taiga Hills</td></tr>
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
- minecraft/loot_tables/entities/puffer_fish.json
+ minecraft/loot_tables/entities/pufferfish.json
+ minecraft/tags/blocks/leaves.json
+ minecraft/tags/fluids/lava.json
+ minecraft/tags/fluids/water.json
+ minecraft/tags/items/fishes.json
+ minecraft/tags/items/leaves.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/sea_grass.json
+ minecraft/blockstates/seagrass.json
- minecraft/blockstates/tall_sea_grass.json
+ minecraft/blockstates/tall_seagrass.json
- minecraft/models/block/sea_grass.json
+ minecraft/models/block/seagrass.json
- minecraft/models/block/tall_sea_grass_bottom.json
- minecraft/models/block/tall_sea_grass_top.json
+ minecraft/models/block/tall_seagrass_bottom.json
+ minecraft/models/block/tall_seagrass_top.json
- minecraft/models/item/puffer_fish_spawn_egg.json
+ minecraft/models/item/pufferfish_spawn_egg.json
- minecraft/models/item/sea_grass.json
+ minecraft/models/item/seagrass.json
- minecraft/textures/blocks/sea_grass.png
- minecraft/textures/blocks/sea_grass.png.mcmeta
+ minecraft/textures/blocks/seagrass.png
+ minecraft/textures/blocks/seagrass.png.mcmeta
- minecraft/textures/blocks/tall_sea_grass_bottom.png
- minecraft/textures/blocks/tall_sea_grass_bottom.png.mcmeta
- minecraft/textures/blocks/tall_sea_grass_top.png
- minecraft/textures/blocks/tall_sea_grass_top.png.mcmeta
+ minecraft/textures/blocks/tall_seagrass_bottom.png
+ minecraft/textures/blocks/tall_seagrass_bottom.png.mcmeta
+ minecraft/textures/blocks/tall_seagrass_top.png
+ minecraft/textures/blocks/tall_seagrass_top.png.mcmeta
- minecraft/textures/items/sea_grass.png
+ minecraft/textures/items/seagrass.png
+ minecraft/textures/items/turtle_egg.png
```

</details>
</details>
<hr/>