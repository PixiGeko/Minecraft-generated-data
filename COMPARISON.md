## Comparison with [18w16a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w16a)

- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Translations</summary>
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

```
item.minecraft.pufferfish_bucket: Puffer Ffish Bucket
item.minecraft.clownfish: ClownfTropical Fish
debug.copy_location.help: F3 + C = Copy location as /tp command, hold F3 + C to crash the game
biome.minecraft.cold_beach: ColdSnowy Beach
biome.minecraft.extreme_hills: Extreme HillMountains
biome.minecraft.extreme_hills_with_trees: Extreme Hills+Wooded Mountains
biome.minecraft.forest_hills: ForestWooded Hills
biome.minecraft.ice_flats: Ice PlainsSnowy Tundra
biome.minecraft.ice_mountains: IceSnowy Mountains
biome.minecraft.mesa_clear_rock: MesaBadlands Plateau
biome.minecraft.mesa: MesaBadlands
biome.minecraft.mesa_rock: Mesa ForestWooded Badlands Plateau
biome.minecraft.mushroom_island: Mushroom IslandFields
biome.minecraft.mushroom_island_shore: Mushroom IslanField Shore
biome.minecraft.mutated_birch_forest_hills: Mutated Birch ForestTall Birch Hills
biome.minecraft.mutated_birch_forest: MutatedTall Birch Forest
biome.minecraft.mutated_desert: Mutated Desert Lakes
biome.minecraft.mutated_extreme_hills: Mutated Extreme HillGravelly Mountains
biome.minecraft.mutated_extreme_hills_with_trees: Mutated Extreme HillGravelly Mountains+
biome.minecraft.mutated_ice_flats: Ice Plains Spikes
biome.minecraft.mutated_jungle_edge: Mutatodified Jungle Edge
biome.minecraft.mutated_jungle: Mutatodified Jungle
biome.minecraft.mutated_mesa_clear_rock: Mutated Mesaodified Badlands Plateau
biome.minecraft.mutated_mesa: Mesa (Bryce)Eroded Badlands
biome.minecraft.mutated_mesa_rock: Mutated Mesa Forestodified Wooded Badlands Plateau
biome.minecraft.mutated_redwood_taiga_hills: Mutated RedwoodGiant Spruce Taiga Hills
biome.minecraft.mutated_redwood_taiga: MegaGiant Spruce Taiga
biome.minecraft.mutated_roofed_forest: Mutated RoofedDark Forest Hills
biome.minecraft.mutated_savanna: MutatShattered Savanna
biome.minecraft.mutated_savanna_rock: MutatShattered Savanna Plateau
biome.minecraft.mutated_swampland: Mutated SwamplandSwamp Hills
biome.minecraft.mutated_taiga_cold: Mutated Cold TaigaSnowy Taiga Mountains
biome.minecraft.mutated_taiga: Mutated TaigaTaiga Mountains
biome.minecraft.redwood_taiga_hills: MegaGiant Tree Taiga Hills
biome.minecraft.redwood_taiga: MegaGiant Tree Taiga
biome.minecraft.roofed_forest: RoofedDark Forest
biome.minecraft.sky_island_barren: The End - Barren islands
biome.minecraft.sky_island_high: The End - High islands
biome.minecraft.sky_island_low: The End - Floating iSmall End Islands
biome.minecraft.sky_island_medium: The End - Medium isEnd Midlands
biome.minecraft.smaller_extreme_hills: Extreme HillsMountain Edge
biome.minecraft.stone_beach: Stone BeachShore
biome.minecraft.swampland: Swampland
biome.minecraft.taiga_cold: ColdSnowy Taiga
biome.minecraft.taiga_cold_hills: ColdSnowy Taiga Hills
```

</details>
</details>
<details><summary>File structure</summary>
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