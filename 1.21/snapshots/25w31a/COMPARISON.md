## Comparison with [1.21.8](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.8)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Blocks](#blocks)
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
<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>DataPack version</td><td><pre>81</pre></td><td><pre>/</pre></td></tr><tr><td>ResourcePack version</td><td><pre>64</pre></td><td><pre>/</pre></td></tr><tr><td>World version</td><td><pre>4440</pre></td><td><pre>4534</pre></td></tr><tr><td>Protocol version</td><td><pre>772</pre></td><td><pre>1073742084</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ com.mojang:jtracy (natives-macos-arm64) V1.0.36
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>com.mojang:authlib</td><td><pre>6.0.58</pre></td><td><pre>6.0.59</pre></td></tr><tr><td>com.mojang:jtracy</td><td><pre>1.0.29</pre></td><td><pre>1.0.36</pre></td></tr><tr><td>com.mojang:jtracy (natives-linux)</td><td><pre>1.0.29</pre></td><td><pre>1.0.36</pre></td></tr><tr><td>com.mojang:jtracy (natives-macos)</td><td><pre>1.0.29</pre></td><td><pre>1.0.36</pre></td></tr><tr><td>com.mojang:jtracy (natives-windows)</td><td><pre>1.0.29</pre></td><td><pre>1.0.36</pre></td></tr></table>
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
+ minecraft:acacia_shelf
+ minecraft:bamboo_shelf
+ minecraft:birch_shelf
+ minecraft:cherry_shelf
+ minecraft:copper_chest
+ minecraft:copper_golem_statue
+ minecraft:crimson_shelf
+ minecraft:dark_oak_shelf
+ minecraft:exposed_copper_chest
+ minecraft:exposed_copper_golem_statue
+ minecraft:exposed_lightning_rod
+ minecraft:jungle_shelf
+ minecraft:mangrove_shelf
+ minecraft:oak_shelf
+ minecraft:oxidized_copper_chest
+ minecraft:oxidized_copper_golem_statue
+ minecraft:oxidized_lightning_rod
+ minecraft:pale_oak_shelf
+ minecraft:spruce_shelf
+ minecraft:warped_shelf
+ minecraft:waxed_copper_chest
+ minecraft:waxed_copper_golem_statue
+ minecraft:waxed_exposed_copper_chest
+ minecraft:waxed_exposed_copper_golem_statue
+ minecraft:waxed_exposed_lightning_rod
+ minecraft:waxed_lightning_rod
+ minecraft:waxed_oxidized_copper_chest
+ minecraft:waxed_oxidized_copper_golem_statue
+ minecraft:waxed_oxidized_lightning_rod
+ minecraft:waxed_weathered_copper_chest
+ minecraft:waxed_weathered_copper_golem_statue
+ minecraft:waxed_weathered_lightning_rod
+ minecraft:weathered_copper_chest
+ minecraft:weathered_copper_golem_statue
+ minecraft:weathered_lightning_rod
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
+ minecraft:copper_golem_statue
+ minecraft:shelf
```

</details>
<details>
<summary>
block_type
</summary>

```diff
+ minecraft:copper_chest
+ minecraft:copper_golem_statue
+ minecraft:shelf
+ minecraft:weathering_copper_chest
+ minecraft:weathering_copper_golem_statue
+ minecraft:weathering_lightning_rod
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:copper_golem
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:acacia_shelf
+ minecraft:bamboo_shelf
+ minecraft:birch_shelf
+ minecraft:cherry_shelf
+ minecraft:copper_axe
+ minecraft:copper_boots
+ minecraft:copper_chest
+ minecraft:copper_chestplate
+ minecraft:copper_golem_spawn_egg
+ minecraft:copper_golem_statue
+ minecraft:copper_helmet
+ minecraft:copper_hoe
+ minecraft:copper_horse_armor
+ minecraft:copper_leggings
+ minecraft:copper_nugget
+ minecraft:copper_pickaxe
+ minecraft:copper_shovel
+ minecraft:copper_sword
+ minecraft:crimson_shelf
+ minecraft:dark_oak_shelf
+ minecraft:exposed_copper_chest
+ minecraft:exposed_copper_golem_statue
+ minecraft:exposed_lightning_rod
+ minecraft:jungle_shelf
+ minecraft:mangrove_shelf
+ minecraft:oak_shelf
+ minecraft:oxidized_copper_chest
+ minecraft:oxidized_copper_golem_statue
+ minecraft:oxidized_lightning_rod
+ minecraft:pale_oak_shelf
+ minecraft:spruce_shelf
+ minecraft:warped_shelf
+ minecraft:waxed_copper_chest
+ minecraft:waxed_copper_golem_statue
+ minecraft:waxed_exposed_copper_chest
+ minecraft:waxed_exposed_copper_golem_statue
+ minecraft:waxed_exposed_lightning_rod
+ minecraft:waxed_lightning_rod
+ minecraft:waxed_oxidized_copper_chest
+ minecraft:waxed_oxidized_copper_golem_statue
+ minecraft:waxed_oxidized_lightning_rod
+ minecraft:waxed_weathered_copper_chest
+ minecraft:waxed_weathered_copper_golem_statue
+ minecraft:waxed_weathered_lightning_rod
+ minecraft:weathered_copper_chest
+ minecraft:weathered_copper_golem_statue
+ minecraft:weathered_lightning_rod
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:transport_items_cooldown_ticks
+ minecraft:visited_block_positions
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.copper_chest_oxidized.close
+ minecraft:block.copper_chest_oxidized.open
+ minecraft:block.copper_chest_weathered.close
+ minecraft:block.copper_chest_weathered.open
+ minecraft:block.copper_chest.close
+ minecraft:block.copper_chest.open
+ minecraft:block.copper_golem_statue.break
+ minecraft:block.copper_golem_statue.fall
+ minecraft:block.copper_golem_statue.hit
+ minecraft:block.copper_golem_statue.place
+ minecraft:block.copper_golem_statue.step
+ minecraft:block.shelf.activate
+ minecraft:block.shelf.break
+ minecraft:block.shelf.deactivate
+ minecraft:block.shelf.fall
+ minecraft:block.shelf.hit
+ minecraft:block.shelf.multi_swap
+ minecraft:block.shelf.place
+ minecraft:block.shelf.place_item
+ minecraft:block.shelf.single_swap
+ minecraft:block.shelf.step
+ minecraft:entity.copper_golem_become_statue
+ minecraft:entity.copper_golem_oxidized.death
+ minecraft:entity.copper_golem_oxidized.hurt
+ minecraft:entity.copper_golem_oxidized.spin
+ minecraft:entity.copper_golem_oxidized.step
+ minecraft:entity.copper_golem_weathered.death
+ minecraft:entity.copper_golem_weathered.hurt
+ minecraft:entity.copper_golem_weathered.spin
+ minecraft:entity.copper_golem_weathered.step
+ minecraft:entity.copper_golem.death
+ minecraft:entity.copper_golem.hurt
+ minecraft:entity.copper_golem.item_drop
+ minecraft:entity.copper_golem.item_no_drop
+ minecraft:entity.copper_golem.no_item_get
+ minecraft:entity.copper_golem.no_item_no_get
+ minecraft:entity.copper_golem.spawn
+ minecraft:entity.copper_golem.spin
+ minecraft:entity.copper_golem.step
+ minecraft:item.armor.equip_copper
```

</details>
<details>
<summary>
ticket_type
</summary>

```diff
+ minecraft:player_spawn
+ minecraft:spawn_search
- minecraft:start
```

</details>
<details>
<summary>
worldgen/density_function_type
</summary>

```diff
+ minecraft:find_top_surface
+ minecraft:invert
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
+ minecraft:acacia_shelf
+ minecraft:bamboo_shelf
+ minecraft:birch_shelf
+ minecraft:cherry_shelf
+ minecraft:copper_chest
+ minecraft:copper_golem_statue
+ minecraft:crimson_shelf
+ minecraft:dark_oak_shelf
+ minecraft:exposed_copper_chest
+ minecraft:exposed_copper_golem_statue
+ minecraft:exposed_lightning_rod
+ minecraft:jungle_shelf
+ minecraft:mangrove_shelf
+ minecraft:oak_shelf
+ minecraft:oxidized_copper_chest
+ minecraft:oxidized_copper_golem_statue
+ minecraft:oxidized_lightning_rod
+ minecraft:pale_oak_shelf
+ minecraft:spruce_shelf
+ minecraft:warped_shelf
+ minecraft:waxed_copper_chest
+ minecraft:waxed_copper_golem_statue
+ minecraft:waxed_exposed_copper_chest
+ minecraft:waxed_exposed_copper_golem_statue
+ minecraft:waxed_exposed_lightning_rod
+ minecraft:waxed_lightning_rod
+ minecraft:waxed_oxidized_copper_chest
+ minecraft:waxed_oxidized_copper_golem_statue
+ minecraft:waxed_oxidized_lightning_rod
+ minecraft:waxed_weathered_copper_chest
+ minecraft:waxed_weathered_copper_golem_statue
+ minecraft:waxed_weathered_lightning_rod
+ minecraft:weathered_copper_chest
+ minecraft:weathered_copper_golem_statue
+ minecraft:weathered_lightning_rod
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
+ minecraft:copper_golem
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:acacia_shelf
+ minecraft:bamboo_shelf
+ minecraft:birch_shelf
+ minecraft:cherry_shelf
+ minecraft:copper_chest
+ minecraft:copper_golem_statue
+ minecraft:crimson_shelf
+ minecraft:dark_oak_shelf
+ minecraft:exposed_copper_chest
+ minecraft:exposed_copper_golem_statue
+ minecraft:exposed_lightning_rod
+ minecraft:jungle_shelf
+ minecraft:mangrove_shelf
+ minecraft:oak_shelf
+ minecraft:oxidized_copper_chest
+ minecraft:oxidized_copper_golem_statue
+ minecraft:oxidized_lightning_rod
+ minecraft:pale_oak_shelf
+ minecraft:spruce_shelf
+ minecraft:warped_shelf
+ minecraft:waxed_copper_chest
+ minecraft:waxed_copper_golem_statue
+ minecraft:waxed_exposed_copper_chest
+ minecraft:waxed_exposed_copper_golem_statue
+ minecraft:waxed_exposed_lightning_rod
+ minecraft:waxed_lightning_rod
+ minecraft:waxed_oxidized_copper_chest
+ minecraft:waxed_oxidized_copper_golem_statue
+ minecraft:waxed_oxidized_lightning_rod
+ minecraft:waxed_weathered_copper_chest
+ minecraft:waxed_weathered_copper_golem_statue
+ minecraft:waxed_weathered_lightning_rod
+ minecraft:weathered_copper_chest
+ minecraft:weathered_copper_golem_statue
+ minecraft:weathered_lightning_rod
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:copper_golem_statue
+ minecraft:shelf
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:copper_chest
+ minecraft:copper_golem_statue
+ minecraft:shelf
+ minecraft:weathering_copper_chest
+ minecraft:weathering_copper_golem_statue
+ minecraft:weathering_lightning_rod
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:copper_golem
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:acacia_shelf
+ minecraft:bamboo_shelf
+ minecraft:birch_shelf
+ minecraft:cherry_shelf
+ minecraft:copper_axe
+ minecraft:copper_boots
+ minecraft:copper_chest
+ minecraft:copper_chestplate
+ minecraft:copper_golem_spawn_egg
+ minecraft:copper_golem_statue
+ minecraft:copper_helmet
+ minecraft:copper_hoe
+ minecraft:copper_horse_armor
+ minecraft:copper_leggings
+ minecraft:copper_nugget
+ minecraft:copper_pickaxe
+ minecraft:copper_shovel
+ minecraft:copper_sword
+ minecraft:crimson_shelf
+ minecraft:dark_oak_shelf
+ minecraft:exposed_copper_chest
+ minecraft:exposed_copper_golem_statue
+ minecraft:exposed_lightning_rod
+ minecraft:jungle_shelf
+ minecraft:mangrove_shelf
+ minecraft:oak_shelf
+ minecraft:oxidized_copper_chest
+ minecraft:oxidized_copper_golem_statue
+ minecraft:oxidized_lightning_rod
+ minecraft:pale_oak_shelf
+ minecraft:spruce_shelf
+ minecraft:warped_shelf
+ minecraft:waxed_copper_chest
+ minecraft:waxed_copper_golem_statue
+ minecraft:waxed_exposed_copper_chest
+ minecraft:waxed_exposed_copper_golem_statue
+ minecraft:waxed_exposed_lightning_rod
+ minecraft:waxed_lightning_rod
+ minecraft:waxed_oxidized_copper_chest
+ minecraft:waxed_oxidized_copper_golem_statue
+ minecraft:waxed_oxidized_lightning_rod
+ minecraft:waxed_weathered_copper_chest
+ minecraft:waxed_weathered_copper_golem_statue
+ minecraft:waxed_weathered_lightning_rod
+ minecraft:weathered_copper_chest
+ minecraft:weathered_copper_golem_statue
+ minecraft:weathered_lightning_rod
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:transport_items_cooldown_ticks
+ minecraft:visited_block_positions
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.copper_chest_oxidized.close
+ minecraft:block.copper_chest_oxidized.open
+ minecraft:block.copper_chest_weathered.close
+ minecraft:block.copper_chest_weathered.open
+ minecraft:block.copper_chest.close
+ minecraft:block.copper_chest.open
+ minecraft:block.copper_golem_statue.break
+ minecraft:block.copper_golem_statue.fall
+ minecraft:block.copper_golem_statue.hit
+ minecraft:block.copper_golem_statue.place
+ minecraft:block.copper_golem_statue.step
+ minecraft:block.shelf.activate
+ minecraft:block.shelf.break
+ minecraft:block.shelf.deactivate
+ minecraft:block.shelf.fall
+ minecraft:block.shelf.hit
+ minecraft:block.shelf.multi_swap
+ minecraft:block.shelf.place
+ minecraft:block.shelf.place_item
+ minecraft:block.shelf.single_swap
+ minecraft:block.shelf.step
+ minecraft:entity.copper_golem_become_statue
+ minecraft:entity.copper_golem_oxidized.death
+ minecraft:entity.copper_golem_oxidized.hurt
+ minecraft:entity.copper_golem_oxidized.spin
+ minecraft:entity.copper_golem_oxidized.step
+ minecraft:entity.copper_golem_weathered.death
+ minecraft:entity.copper_golem_weathered.hurt
+ minecraft:entity.copper_golem_weathered.spin
+ minecraft:entity.copper_golem_weathered.step
+ minecraft:entity.copper_golem.death
+ minecraft:entity.copper_golem.hurt
+ minecraft:entity.copper_golem.item_drop
+ minecraft:entity.copper_golem.item_no_drop
+ minecraft:entity.copper_golem.no_item_get
+ minecraft:entity.copper_golem.no_item_no_get
+ minecraft:entity.copper_golem.spawn
+ minecraft:entity.copper_golem.spin
+ minecraft:entity.copper_golem.step
+ minecraft:item.armor.equip_copper
```

</details>
<details>
<summary>
universal_tags/ticket_type.json
</summary>

```diff
+ minecraft:player_spawn
+ minecraft:spawn_search
- minecraft:start
```

</details>
<details>
<summary>
universal_tags/worldgen/density_function_type.json
</summary>

```diff
+ minecraft:find_top_surface
+ minecraft:invert
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (REGISTRY)</ins></b><a name="items-(registry)"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ acacia_shelf.json
+ bamboo_shelf.json
+ birch_shelf.json
+ cherry_shelf.json
+ copper_axe.json
+ copper_boots.json
+ copper_chest.json
+ copper_chestplate.json
+ copper_golem_spawn_egg.json
+ copper_golem_statue.json
+ copper_helmet.json
+ copper_hoe.json
+ copper_horse_armor.json
+ copper_leggings.json
+ copper_nugget.json
+ copper_pickaxe.json
+ copper_shovel.json
+ copper_sword.json
+ crimson_shelf.json
+ dark_oak_shelf.json
+ exposed_copper_chest.json
+ exposed_copper_golem_statue.json
+ exposed_lightning_rod.json
+ jungle_shelf.json
+ mangrove_shelf.json
+ oak_shelf.json
+ oxidized_copper_chest.json
+ oxidized_copper_golem_statue.json
+ oxidized_lightning_rod.json
+ pale_oak_shelf.json
+ spruce_shelf.json
+ warped_shelf.json
+ waxed_copper_chest.json
+ waxed_copper_golem_statue.json
+ waxed_exposed_copper_chest.json
+ waxed_exposed_copper_golem_statue.json
+ waxed_exposed_lightning_rod.json
+ waxed_lightning_rod.json
+ waxed_oxidized_copper_chest.json
+ waxed_oxidized_copper_golem_statue.json
+ waxed_oxidized_lightning_rod.json
+ waxed_weathered_copper_chest.json
+ waxed_weathered_copper_golem_statue.json
+ waxed_weathered_lightning_rod.json
+ weathered_copper_chest.json
+ weathered_copper_golem_statue.json
+ weathered_lightning_rod.json
```

</details>
<details>
<summary>
allay_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:allay"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:armadillo"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:axolotl"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:bat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:bee"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:blaze"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bogged_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:bogged"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:breeze"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
camel_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:camel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:cat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:cave_spider"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:chicken"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:cod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cow_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:cow"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:creaking"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:creeper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dolphin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:dolphin"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
donkey_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:donkey"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
drowned_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:drowned"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elder_guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:elder_guardian"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enderman_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:enderman"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
endermite_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:endermite"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_dragon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:ender_dragon"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
evoker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:evoker"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fox_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:fox"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frog_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:frog"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:ghast"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:glow_squid"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:goat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:guardian"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
happy_ghast_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:happy_ghast"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:hoglin"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:horse"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
husk_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:husk"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:iron_golem"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:llama"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cube_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:magma_cube"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mooshroom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:mooshroom"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mule_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:mule"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ocelot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:ocelot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
panda_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:panda"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
parrot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:parrot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:phantom"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_brute_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:piglin_brute"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:piglin"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pig_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:pig"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pillager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:pillager"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polar_bear_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:polar_bear"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:pufferfish"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:rabbit"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ravager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:ravager"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:salmon"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheep_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:sheep"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:shulker"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silverfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:silverfish"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:skeleton_horse"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:skeleton"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:slime"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:sniffer"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:snow_golem"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:spider"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:squid"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stray_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:stray"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
strider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:strider"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:tadpole"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trader_llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:trader_llama"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:tropical_fish"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:turtle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:vex"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:villager"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vindicator_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:vindicator"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wandering_trader_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:wandering_trader"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warden_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:warden"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
witch_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:witch"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:wither_skeleton"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:wither"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:wolf"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:zoglin"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:zombie_horse"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:zombie"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:zombie_villager"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombified_piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>minecraft:entity_data</td><td><pre>/</pre></td><td><pre>{
  "id": "minecraft:zombified_piglin"
}</pre></td></tr></table>
<br/>
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
+ acacia_shelf.json
+ bamboo_shelf.json
+ birch_shelf.json
+ cherry_shelf.json
+ copper_chest.json
+ copper_golem_statue.json
+ crimson_shelf.json
+ dark_oak_shelf.json
+ exposed_copper_chest.json
+ exposed_copper_golem_statue.json
+ exposed_lightning_rod.json
+ jungle_shelf.json
+ mangrove_shelf.json
+ oak_shelf.json
+ oxidized_copper_chest.json
+ oxidized_copper_golem_statue.json
+ oxidized_lightning_rod.json
+ pale_oak_shelf.json
+ spruce_shelf.json
+ warped_shelf.json
+ waxed_copper_chest.json
+ waxed_copper_golem_statue.json
+ waxed_exposed_copper_chest.json
+ waxed_exposed_copper_golem_statue.json
+ waxed_exposed_lightning_rod.json
+ waxed_lightning_rod.json
+ waxed_oxidized_copper_chest.json
+ waxed_oxidized_copper_golem_statue.json
+ waxed_oxidized_lightning_rod.json
+ waxed_weathered_copper_chest.json
+ waxed_weathered_copper_golem_statue.json
+ waxed_weathered_lightning_rod.json
+ weathered_copper_chest.json
+ weathered_copper_golem_statue.json
+ weathered_lightning_rod.json
```

</details>
<details>
<summary>
chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>close_sound</td><td><pre>/</pre></td><td><pre>minecraft:block.chest.close</pre></td></tr><tr><td>open_sound</td><td><pre>/</pre></td><td><pre>minecraft:block.chest.open</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.8</th><th>25w31a</th></tr><tr><td>type</td><td><pre>minecraft:lightning_rod</pre></td><td><pre>minecraft:weathering_lightning_rod</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
gamerule
</summary>

```diff
- gamerule spawnChunkRadius <value: integer>
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
+ acacia_shelf.json
+ bamboo_shelf.json
+ birch_shelf.json
+ cherry_shelf.json
+ copper_axe.json
+ copper_boots.json
+ copper_chest.json
+ copper_chestplate.json
+ copper_helmet.json
+ copper_hoe.json
+ copper_ingot_from_nuggets.json
+ copper_leggings.json
+ copper_nugget_from_blasting.json
+ copper_nugget_from_smelting.json
+ copper_nugget.json
+ copper_pickaxe.json
+ copper_shovel.json
+ copper_sword.json
+ crimson_shelf.json
+ dark_oak_shelf.json
+ jungle_shelf.json
+ mangrove_shelf.json
+ oak_shelf.json
+ pale_oak_shelf.json
+ spruce_shelf.json
+ warped_shelf.json
+ waxed_copper_chest_from_honeycomb.json
+ waxed_copper_golem_statue_from_honeycomb.json
+ waxed_exposed_copper_chest_from_honeycomb.json
+ waxed_exposed_copper_golem_statue_from_honeycomb.json
+ waxed_exposed_lightning_rod_from_honeycomb.json
+ waxed_lightning_rod_from_honeycomb.json
+ waxed_oxidized_copper_chest_from_honeycomb.json
+ waxed_oxidized_copper_golem_statue_from_honeycomb.json
+ waxed_oxidized_lightning_rod_from_honeycomb.json
+ waxed_weathered_copper_chest_from_honeycomb.json
+ waxed_weathered_copper_golem_statue_from_honeycomb.json
+ waxed_weathered_lightning_rod_from_honeycomb.json
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
+ block.minecraft.acacia_shelf: Acacia Shelf
+ block.minecraft.bamboo_shelf: Bamboo Shelf
+ block.minecraft.birch_shelf: Birch Shelf
+ block.minecraft.cherry_shelf: Cherry Shelf
+ block.minecraft.copper_chest: Copper Chest
+ block.minecraft.copper_golem_statue: Copper Golem Statue
+ block.minecraft.crimson_shelf: Crimson Shelf
+ block.minecraft.dark_oak_shelf: Dark Oak Shelf
+ block.minecraft.exposed_copper_chest: Exposed Copper Chest
+ block.minecraft.exposed_copper_golem_statue: Exposed Copper Golem Statue
+ block.minecraft.exposed_lightning_rod: Exposed Lightning Rod
+ block.minecraft.jungle_shelf: Jungle Shelf
+ block.minecraft.mangrove_shelf: Mangrove Shelf
+ block.minecraft.oak_shelf: Oak Shelf
+ block.minecraft.oxidized_copper_chest: Oxidized Copper Chest
+ block.minecraft.oxidized_copper_golem_statue: Oxidized Copper Golem Statue
+ block.minecraft.oxidized_lightning_rod: Oxidized Lightning Rod
+ block.minecraft.pale_oak_shelf: Pale Oak Shelf
+ block.minecraft.spruce_shelf: Spruce Shelf
+ block.minecraft.warped_shelf: Warped Shelf
+ block.minecraft.waxed_copper_chest: Waxed Copper Chest
+ block.minecraft.waxed_copper_golem_statue: Waxed Copper Golem Statue
+ block.minecraft.waxed_exposed_copper_chest: Waxed Exposed Copper Chest
+ block.minecraft.waxed_exposed_copper_golem_statue: Waxed Exposed Copper Golem Statue
+ block.minecraft.waxed_exposed_lightning_rod: Waxed Exposed Lightning Rod
+ block.minecraft.waxed_lightning_rod: Waxed Lightning Rod
+ block.minecraft.waxed_oxidized_copper_chest: Waxed Oxidized Copper Chest
+ block.minecraft.waxed_oxidized_copper_golem_statue: Waxed Oxidized Copper Golem Statue
+ block.minecraft.waxed_oxidized_lightning_rod: Waxed Oxidized Lightning Rod
+ block.minecraft.waxed_weathered_copper_chest: Waxed Weathered Copper Chest
+ block.minecraft.waxed_weathered_copper_golem_statue: Waxed Weathered Copper Golem Statue
+ block.minecraft.waxed_weathered_lightning_rod: Waxed Weathered Lightning Rod
+ block.minecraft.weathered_copper_chest: Weathered Copper Chest
+ block.minecraft.weathered_copper_golem_statue: Weathered Copper Golem Statue
+ block.minecraft.weathered_lightning_rod: Weathered Lightning Rod
+ commands.summon.failed.peaceful: Monster cannot be summoned in Peaceful difficulty
+ debug.entry.always: Always
+ debug.entry.currently.alwaysOn: %s: Currently always on
+ debug.entry.currently.inF3: %s: Currently only in f3
+ debug.entry.currently.never: %s: Currently off
+ debug.entry.f3: In F3
+ debug.options.category.renderer: Debug Renderers
+ debug.options.category.text: Debug Screen Text
+ debug.options.help: F3 + F5 = Edit Debug Options
+ debug.options.notAllowed.tooltip: Not visible when debug info is reduced
+ debug.options.profile.default: Default profile
+ debug.options.profile.performance: Performance profile
+ debug.options.search: Search for options
+ debug.options.title: Debug Options
+ debug.options.warning: These options are for testing purposes only. They may slow down your computer, crash the game, or eat your pet rock.
+ entity.minecraft.copper_golem: Copper Golem
+ item.minecraft.copper_axe: Copper Axe
+ item.minecraft.copper_boots: Copper Boots
+ item.minecraft.copper_chestplate: Copper Chestplate
+ item.minecraft.copper_golem_spawn_egg: Copper Golem Spawn Egg
+ item.minecraft.copper_helmet: Copper Helmet
+ item.minecraft.copper_hoe: Copper Hoe
+ item.minecraft.copper_horse_armor: Copper Horse Armor
+ item.minecraft.copper_leggings: Copper Leggings
+ item.minecraft.copper_nugget: Copper Nugget
+ item.minecraft.copper_pickaxe: Copper Pickaxe
+ item.minecraft.copper_shovel: Copper Shovel
+ item.minecraft.copper_sword: Copper Sword
+ item.spawn_egg.peaceful: Disabled in Peaceful
+ mco.configure.world.players.invite.duplicate: A player with the provided name has already been invited to the Realm
+ multiplayer.disconnect.configuration_error: Unexpected error during configuration
+ narration.slider.usage.focused.keyboard_cannot_change_value: Press Enter to start changing the slider value
+ options.invertMouseX: Invert Mouse X
+ options.invertMouseY: Invert Mouse Y
+ options.showSubtitles.tooltip: Enables captions for sounds played in the game.
+ options.sprintWindow: Sprint Window
+ options.sprintWindow.tooltip: Time window in ticks where double-tapping the forward key activates sprint.
+ options.value: %s
+ pack.incompatible.confirm.unknown: This pack is broken or made for an unknown version of Minecraft and may not work correctly.
+ pack.incompatible.unknown: (Broken or incompatible)
+ subtitles.block.copper_chest.close: Chest closes
+ subtitles.block.copper_chest.open: Chest opens
+ subtitles.block.shelf.activate: Shelf activates
+ subtitles.block.shelf.deactivate: Shelf deactivates
+ subtitles.block.shelf.multi_swap: Items swap
+ subtitles.block.shelf.place_item: Item placed
+ subtitles.block.shelf.single_swap: Item swaps
+ subtitles.entity.copper_golem_become_statue: Copper Golem is petrified
+ subtitles.entity.copper_golem_oxidized.death: Copper Golem dies
+ subtitles.entity.copper_golem_oxidized.hurt: Copper Golem hurts
+ subtitles.entity.copper_golem_oxidized.spin: Copper Golem's head spins
+ subtitles.entity.copper_golem_weathered.death: Copper Golem dies
+ subtitles.entity.copper_golem_weathered.hurt: Copper Golem hurts
+ subtitles.entity.copper_golem_weathered.spin: Copper Golem's head spins
+ subtitles.entity.copper_golem.death: Copper Golem dies
+ subtitles.entity.copper_golem.hurt: Copper Golem hurts
+ subtitles.entity.copper_golem.item_drop: Copper Golem is placing an item
+ subtitles.entity.copper_golem.item_no_drop: Copper Golem can't place item
+ subtitles.entity.copper_golem.no_item_get: Copper Golem is picking up item
+ subtitles.entity.copper_golem.no_item_no_get: Copper Golem can't pick up item
+ subtitles.entity.copper_golem.spawn: Copper Golem appears
+ subtitles.entity.copper_golem.spin: Copper Golem's head spins
+ subtitles.item.armor.equip_copper: Copper armor clonks
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.21.8</th><th>25w31a</th></tr>
<tr><th align="left"><div style="width:290px">options.showSubtitles</div></th><td>Show Subtitles</td><td>Closed Captions</td></tr>
<tr><th align="left"><div style="width:290px">soundCategory.voice</div></th><td>Voice/Speech</td><td>Narrator/Voice</td></tr>
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
+ minecraft/advancement/recipes/building_blocks/waxed_copper_chest_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_copper_golem_statue_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_exposed_copper_chest_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_exposed_copper_golem_statue_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_exposed_lightning_rod_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_lightning_rod_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_oxidized_copper_chest_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_oxidized_copper_golem_statue_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_oxidized_lightning_rod_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_weathered_copper_chest_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_weathered_copper_golem_statue_from_honeycomb.json
+ minecraft/advancement/recipes/building_blocks/waxed_weathered_lightning_rod_from_honeycomb.json
+ minecraft/advancement/recipes/combat/copper_boots.json
+ minecraft/advancement/recipes/combat/copper_chestplate.json
+ minecraft/advancement/recipes/combat/copper_helmet.json
+ minecraft/advancement/recipes/combat/copper_leggings.json
+ minecraft/advancement/recipes/combat/copper_sword.json
+ minecraft/advancement/recipes/decorations/acacia_shelf.json
+ minecraft/advancement/recipes/decorations/bamboo_shelf.json
+ minecraft/advancement/recipes/decorations/birch_shelf.json
+ minecraft/advancement/recipes/decorations/cherry_shelf.json
+ minecraft/advancement/recipes/decorations/copper_chest.json
+ minecraft/advancement/recipes/decorations/crimson_shelf.json
+ minecraft/advancement/recipes/decorations/dark_oak_shelf.json
+ minecraft/advancement/recipes/decorations/jungle_shelf.json
+ minecraft/advancement/recipes/decorations/mangrove_shelf.json
+ minecraft/advancement/recipes/decorations/oak_shelf.json
+ minecraft/advancement/recipes/decorations/pale_oak_shelf.json
+ minecraft/advancement/recipes/decorations/spruce_shelf.json
+ minecraft/advancement/recipes/decorations/warped_shelf.json
+ minecraft/advancement/recipes/misc/copper_ingot_from_nuggets.json
+ minecraft/advancement/recipes/misc/copper_nugget_from_blasting.json
+ minecraft/advancement/recipes/misc/copper_nugget_from_smelting.json
+ minecraft/advancement/recipes/misc/copper_nugget.json
+ minecraft/advancement/recipes/tools/copper_axe.json
+ minecraft/advancement/recipes/tools/copper_hoe.json
+ minecraft/advancement/recipes/tools/copper_pickaxe.json
+ minecraft/advancement/recipes/tools/copper_shovel.json
+ minecraft/loot_table/blocks/acacia_shelf.json
+ minecraft/loot_table/blocks/bamboo_shelf.json
+ minecraft/loot_table/blocks/birch_shelf.json
+ minecraft/loot_table/blocks/cherry_shelf.json
+ minecraft/loot_table/blocks/copper_chest.json
+ minecraft/loot_table/blocks/copper_golem_statue.json
+ minecraft/loot_table/blocks/crimson_shelf.json
+ minecraft/loot_table/blocks/dark_oak_shelf.json
+ minecraft/loot_table/blocks/exposed_copper_chest.json
+ minecraft/loot_table/blocks/exposed_copper_golem_statue.json
+ minecraft/loot_table/blocks/exposed_lightning_rod.json
+ minecraft/loot_table/blocks/jungle_shelf.json
+ minecraft/loot_table/blocks/mangrove_shelf.json
+ minecraft/loot_table/blocks/oak_shelf.json
+ minecraft/loot_table/blocks/oxidized_copper_chest.json
+ minecraft/loot_table/blocks/oxidized_copper_golem_statue.json
+ minecraft/loot_table/blocks/oxidized_lightning_rod.json
+ minecraft/loot_table/blocks/pale_oak_shelf.json
+ minecraft/loot_table/blocks/spruce_shelf.json
+ minecraft/loot_table/blocks/warped_shelf.json
+ minecraft/loot_table/blocks/waxed_copper_chest.json
+ minecraft/loot_table/blocks/waxed_copper_golem_statue.json
+ minecraft/loot_table/blocks/waxed_exposed_copper_chest.json
+ minecraft/loot_table/blocks/waxed_exposed_copper_golem_statue.json
+ minecraft/loot_table/blocks/waxed_exposed_lightning_rod.json
+ minecraft/loot_table/blocks/waxed_lightning_rod.json
+ minecraft/loot_table/blocks/waxed_oxidized_copper_chest.json
+ minecraft/loot_table/blocks/waxed_oxidized_copper_golem_statue.json
+ minecraft/loot_table/blocks/waxed_oxidized_lightning_rod.json
+ minecraft/loot_table/blocks/waxed_weathered_copper_chest.json
+ minecraft/loot_table/blocks/waxed_weathered_copper_golem_statue.json
+ minecraft/loot_table/blocks/waxed_weathered_lightning_rod.json
+ minecraft/loot_table/blocks/weathered_copper_chest.json
+ minecraft/loot_table/blocks/weathered_copper_golem_statue.json
+ minecraft/loot_table/blocks/weathered_lightning_rod.json
+ minecraft/loot_table/brush/armadillo.json
+ minecraft/loot_table/carve/pumpkin.json
+ minecraft/loot_table/charged_creeper/creeper.json
+ minecraft/loot_table/charged_creeper/piglin.json
+ minecraft/loot_table/charged_creeper/root.json
+ minecraft/loot_table/charged_creeper/skeleton.json
+ minecraft/loot_table/charged_creeper/wither_skeleton.json
+ minecraft/loot_table/charged_creeper/zombie.json
+ minecraft/loot_table/entities/copper_golem.json
+ minecraft/loot_table/gameplay/turtle_grow.json
+ minecraft/loot_table/harvest/beehive.json
+ minecraft/loot_table/harvest/cave_vine.json
+ minecraft/recipe/acacia_shelf.json
+ minecraft/recipe/bamboo_shelf.json
+ minecraft/recipe/birch_shelf.json
+ minecraft/recipe/cherry_shelf.json
+ minecraft/recipe/copper_axe.json
+ minecraft/recipe/copper_boots.json
+ minecraft/recipe/copper_chest.json
+ minecraft/recipe/copper_chestplate.json
+ minecraft/recipe/copper_helmet.json
+ minecraft/recipe/copper_hoe.json
+ minecraft/recipe/copper_ingot_from_nuggets.json
+ minecraft/recipe/copper_leggings.json
+ minecraft/recipe/copper_nugget_from_blasting.json
+ minecraft/recipe/copper_nugget_from_smelting.json
+ minecraft/recipe/copper_nugget.json
+ minecraft/recipe/copper_pickaxe.json
+ minecraft/recipe/copper_shovel.json
+ minecraft/recipe/copper_sword.json
+ minecraft/recipe/crimson_shelf.json
+ minecraft/recipe/dark_oak_shelf.json
+ minecraft/recipe/jungle_shelf.json
+ minecraft/recipe/mangrove_shelf.json
+ minecraft/recipe/oak_shelf.json
+ minecraft/recipe/pale_oak_shelf.json
+ minecraft/recipe/spruce_shelf.json
+ minecraft/recipe/warped_shelf.json
+ minecraft/recipe/waxed_copper_chest_from_honeycomb.json
+ minecraft/recipe/waxed_copper_golem_statue_from_honeycomb.json
+ minecraft/recipe/waxed_exposed_copper_chest_from_honeycomb.json
+ minecraft/recipe/waxed_exposed_copper_golem_statue_from_honeycomb.json
+ minecraft/recipe/waxed_exposed_lightning_rod_from_honeycomb.json
+ minecraft/recipe/waxed_lightning_rod_from_honeycomb.json
+ minecraft/recipe/waxed_oxidized_copper_chest_from_honeycomb.json
+ minecraft/recipe/waxed_oxidized_copper_golem_statue_from_honeycomb.json
+ minecraft/recipe/waxed_oxidized_lightning_rod_from_honeycomb.json
+ minecraft/recipe/waxed_weathered_copper_chest_from_honeycomb.json
+ minecraft/recipe/waxed_weathered_copper_golem_statue_from_honeycomb.json
+ minecraft/recipe/waxed_weathered_lightning_rod_from_honeycomb.json
+ minecraft/tags/block/copper_chests.json
+ minecraft/tags/block/copper_golem_statues.json
+ minecraft/tags/block/copper.json
+ minecraft/tags/block/incorrect_for_copper_tool.json
+ minecraft/tags/block/lightning_rods.json
+ minecraft/tags/block/wooden_shelves.json
+ minecraft/tags/item/copper_chests.json
+ minecraft/tags/item/copper_golem_statues.json
+ minecraft/tags/item/copper_tool_materials.json
+ minecraft/tags/item/copper.json
+ minecraft/tags/item/lightning_rods.json
+ minecraft/tags/item/repairs_copper_armor.json
+ minecraft/tags/item/wooden_shelves.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/acacia_shelf.json
+ minecraft/blockstates/bamboo_shelf.json
+ minecraft/blockstates/birch_shelf.json
+ minecraft/blockstates/cherry_shelf.json
+ minecraft/blockstates/copper_chest.json
+ minecraft/blockstates/copper_golem_statue.json
+ minecraft/blockstates/crimson_shelf.json
+ minecraft/blockstates/dark_oak_shelf.json
+ minecraft/blockstates/exposed_copper_chest.json
+ minecraft/blockstates/exposed_copper_golem_statue.json
+ minecraft/blockstates/exposed_lightning_rod.json
+ minecraft/blockstates/jungle_shelf.json
+ minecraft/blockstates/mangrove_shelf.json
+ minecraft/blockstates/oak_shelf.json
+ minecraft/blockstates/oxidized_copper_chest.json
+ minecraft/blockstates/oxidized_copper_golem_statue.json
+ minecraft/blockstates/oxidized_lightning_rod.json
+ minecraft/blockstates/pale_oak_shelf.json
+ minecraft/blockstates/spruce_shelf.json
+ minecraft/blockstates/warped_shelf.json
+ minecraft/blockstates/waxed_copper_chest.json
+ minecraft/blockstates/waxed_copper_golem_statue.json
+ minecraft/blockstates/waxed_exposed_copper_chest.json
+ minecraft/blockstates/waxed_exposed_copper_golem_statue.json
+ minecraft/blockstates/waxed_exposed_lightning_rod.json
+ minecraft/blockstates/waxed_lightning_rod.json
+ minecraft/blockstates/waxed_oxidized_copper_chest.json
+ minecraft/blockstates/waxed_oxidized_copper_golem_statue.json
+ minecraft/blockstates/waxed_oxidized_lightning_rod.json
+ minecraft/blockstates/waxed_weathered_copper_chest.json
+ minecraft/blockstates/waxed_weathered_copper_golem_statue.json
+ minecraft/blockstates/waxed_weathered_lightning_rod.json
+ minecraft/blockstates/weathered_copper_chest.json
+ minecraft/blockstates/weathered_copper_golem_statue.json
+ minecraft/blockstates/weathered_lightning_rod.json
+ minecraft/equipment/copper.json
+ minecraft/items/acacia_shelf.json
+ minecraft/items/bamboo_shelf.json
+ minecraft/items/birch_shelf.json
+ minecraft/items/cherry_shelf.json
+ minecraft/items/copper_axe.json
+ minecraft/items/copper_boots.json
+ minecraft/items/copper_chest.json
+ minecraft/items/copper_chestplate.json
+ minecraft/items/copper_golem_spawn_egg.json
+ minecraft/items/copper_golem_statue.json
+ minecraft/items/copper_helmet.json
+ minecraft/items/copper_hoe.json
+ minecraft/items/copper_horse_armor.json
+ minecraft/items/copper_leggings.json
+ minecraft/items/copper_nugget.json
+ minecraft/items/copper_pickaxe.json
+ minecraft/items/copper_shovel.json
+ minecraft/items/copper_sword.json
+ minecraft/items/crimson_shelf.json
+ minecraft/items/dark_oak_shelf.json
+ minecraft/items/exposed_copper_chest.json
+ minecraft/items/exposed_copper_golem_statue.json
+ minecraft/items/exposed_lightning_rod.json
+ minecraft/items/jungle_shelf.json
+ minecraft/items/mangrove_shelf.json
+ minecraft/items/oak_shelf.json
+ minecraft/items/oxidized_copper_chest.json
+ minecraft/items/oxidized_copper_golem_statue.json
+ minecraft/items/oxidized_lightning_rod.json
+ minecraft/items/pale_oak_shelf.json
+ minecraft/items/spruce_shelf.json
+ minecraft/items/warped_shelf.json
+ minecraft/items/waxed_copper_chest.json
+ minecraft/items/waxed_copper_golem_statue.json
+ minecraft/items/waxed_exposed_copper_chest.json
+ minecraft/items/waxed_exposed_copper_golem_statue.json
+ minecraft/items/waxed_exposed_lightning_rod.json
+ minecraft/items/waxed_lightning_rod.json
+ minecraft/items/waxed_oxidized_copper_chest.json
+ minecraft/items/waxed_oxidized_copper_golem_statue.json
+ minecraft/items/waxed_oxidized_lightning_rod.json
+ minecraft/items/waxed_weathered_copper_chest.json
+ minecraft/items/waxed_weathered_copper_golem_statue.json
+ minecraft/items/waxed_weathered_lightning_rod.json
+ minecraft/items/weathered_copper_chest.json
+ minecraft/items/weathered_copper_golem_statue.json
+ minecraft/items/weathered_lightning_rod.json
+ minecraft/models/block/acacia_shelf_center.json
+ minecraft/models/block/acacia_shelf_inventory.json
+ minecraft/models/block/acacia_shelf_left.json
+ minecraft/models/block/acacia_shelf_right.json
+ minecraft/models/block/acacia_shelf_unconnected.json
+ minecraft/models/block/acacia_shelf_unpowered.json
+ minecraft/models/block/acacia_shelf.json
+ minecraft/models/block/bamboo_shelf_center.json
+ minecraft/models/block/bamboo_shelf_inventory.json
+ minecraft/models/block/bamboo_shelf_left.json
+ minecraft/models/block/bamboo_shelf_right.json
+ minecraft/models/block/bamboo_shelf_unconnected.json
+ minecraft/models/block/bamboo_shelf_unpowered.json
+ minecraft/models/block/bamboo_shelf.json
+ minecraft/models/block/birch_shelf_center.json
+ minecraft/models/block/birch_shelf_inventory.json
+ minecraft/models/block/birch_shelf_left.json
+ minecraft/models/block/birch_shelf_right.json
+ minecraft/models/block/birch_shelf_unconnected.json
+ minecraft/models/block/birch_shelf_unpowered.json
+ minecraft/models/block/birch_shelf.json
+ minecraft/models/block/cherry_shelf_center.json
+ minecraft/models/block/cherry_shelf_inventory.json
+ minecraft/models/block/cherry_shelf_left.json
+ minecraft/models/block/cherry_shelf_right.json
+ minecraft/models/block/cherry_shelf_unconnected.json
+ minecraft/models/block/cherry_shelf_unpowered.json
+ minecraft/models/block/cherry_shelf.json
+ minecraft/models/block/copper_chest.json
+ minecraft/models/block/copper_golem_statue.json
+ minecraft/models/block/crimson_shelf_center.json
+ minecraft/models/block/crimson_shelf_inventory.json
+ minecraft/models/block/crimson_shelf_left.json
+ minecraft/models/block/crimson_shelf_right.json
+ minecraft/models/block/crimson_shelf_unconnected.json
+ minecraft/models/block/crimson_shelf_unpowered.json
+ minecraft/models/block/crimson_shelf.json
+ minecraft/models/block/dark_oak_shelf_center.json
+ minecraft/models/block/dark_oak_shelf_inventory.json
+ minecraft/models/block/dark_oak_shelf_left.json
+ minecraft/models/block/dark_oak_shelf_right.json
+ minecraft/models/block/dark_oak_shelf_unconnected.json
+ minecraft/models/block/dark_oak_shelf_unpowered.json
+ minecraft/models/block/dark_oak_shelf.json
+ minecraft/models/block/exposed_copper_chest.json
+ minecraft/models/block/exposed_copper_golem_statue.json
+ minecraft/models/block/exposed_lightning_rod.json
+ minecraft/models/block/jungle_shelf_center.json
+ minecraft/models/block/jungle_shelf_inventory.json
+ minecraft/models/block/jungle_shelf_left.json
+ minecraft/models/block/jungle_shelf_right.json
+ minecraft/models/block/jungle_shelf_unconnected.json
+ minecraft/models/block/jungle_shelf_unpowered.json
+ minecraft/models/block/jungle_shelf.json
+ minecraft/models/block/mangrove_shelf_center.json
+ minecraft/models/block/mangrove_shelf_inventory.json
+ minecraft/models/block/mangrove_shelf_left.json
+ minecraft/models/block/mangrove_shelf_right.json
+ minecraft/models/block/mangrove_shelf_unconnected.json
+ minecraft/models/block/mangrove_shelf_unpowered.json
+ minecraft/models/block/mangrove_shelf.json
+ minecraft/models/block/oak_shelf_center.json
+ minecraft/models/block/oak_shelf_inventory.json
+ minecraft/models/block/oak_shelf_left.json
+ minecraft/models/block/oak_shelf_right.json
+ minecraft/models/block/oak_shelf_unconnected.json
+ minecraft/models/block/oak_shelf_unpowered.json
+ minecraft/models/block/oak_shelf.json
+ minecraft/models/block/oxidized_copper_chest.json
+ minecraft/models/block/oxidized_copper_golem_statue.json
+ minecraft/models/block/oxidized_lightning_rod.json
+ minecraft/models/block/pale_oak_shelf_center.json
+ minecraft/models/block/pale_oak_shelf_inventory.json
+ minecraft/models/block/pale_oak_shelf_left.json
+ minecraft/models/block/pale_oak_shelf_right.json
+ minecraft/models/block/pale_oak_shelf_unconnected.json
+ minecraft/models/block/pale_oak_shelf_unpowered.json
+ minecraft/models/block/pale_oak_shelf.json
+ minecraft/models/block/spruce_shelf_center.json
+ minecraft/models/block/spruce_shelf_inventory.json
+ minecraft/models/block/spruce_shelf_left.json
+ minecraft/models/block/spruce_shelf_right.json
+ minecraft/models/block/spruce_shelf_unconnected.json
+ minecraft/models/block/spruce_shelf_unpowered.json
+ minecraft/models/block/spruce_shelf.json
+ minecraft/models/block/template_lightning_rod.json
+ minecraft/models/block/template_shelf_body.json
+ minecraft/models/block/template_shelf_center.json
+ minecraft/models/block/template_shelf_inventory.json
+ minecraft/models/block/template_shelf_left.json
+ minecraft/models/block/template_shelf_right.json
+ minecraft/models/block/template_shelf_unconnected.json
+ minecraft/models/block/template_shelf_unpowered.json
+ minecraft/models/block/warped_shelf_center.json
+ minecraft/models/block/warped_shelf_inventory.json
+ minecraft/models/block/warped_shelf_left.json
+ minecraft/models/block/warped_shelf_right.json
+ minecraft/models/block/warped_shelf_unconnected.json
+ minecraft/models/block/warped_shelf_unpowered.json
+ minecraft/models/block/warped_shelf.json
+ minecraft/models/block/weathered_copper_chest.json
+ minecraft/models/block/weathered_copper_golem_statue.json
+ minecraft/models/block/weathered_lightning_rod.json
+ minecraft/models/item/copper_axe.json
+ minecraft/models/item/copper_boots_amethyst_trim.json
+ minecraft/models/item/copper_boots_copper_trim.json
+ minecraft/models/item/copper_boots_diamond_trim.json
+ minecraft/models/item/copper_boots_emerald_trim.json
+ minecraft/models/item/copper_boots_gold_trim.json
+ minecraft/models/item/copper_boots_iron_trim.json
+ minecraft/models/item/copper_boots_lapis_trim.json
+ minecraft/models/item/copper_boots_netherite_trim.json
+ minecraft/models/item/copper_boots_quartz_trim.json
+ minecraft/models/item/copper_boots_redstone_trim.json
+ minecraft/models/item/copper_boots_resin_trim.json
+ minecraft/models/item/copper_boots.json
+ minecraft/models/item/copper_chest.json
+ minecraft/models/item/copper_chestplate_amethyst_trim.json
+ minecraft/models/item/copper_chestplate_copper_trim.json
+ minecraft/models/item/copper_chestplate_diamond_trim.json
+ minecraft/models/item/copper_chestplate_emerald_trim.json
+ minecraft/models/item/copper_chestplate_gold_trim.json
+ minecraft/models/item/copper_chestplate_iron_trim.json
+ minecraft/models/item/copper_chestplate_lapis_trim.json
+ minecraft/models/item/copper_chestplate_netherite_trim.json
+ minecraft/models/item/copper_chestplate_quartz_trim.json
+ minecraft/models/item/copper_chestplate_redstone_trim.json
+ minecraft/models/item/copper_chestplate_resin_trim.json
+ minecraft/models/item/copper_chestplate.json
+ minecraft/models/item/copper_golem_spawn_egg.json
+ minecraft/models/item/copper_helmet_amethyst_trim.json
+ minecraft/models/item/copper_helmet_copper_trim.json
+ minecraft/models/item/copper_helmet_diamond_trim.json
+ minecraft/models/item/copper_helmet_emerald_trim.json
+ minecraft/models/item/copper_helmet_gold_trim.json
+ minecraft/models/item/copper_helmet_iron_trim.json
+ minecraft/models/item/copper_helmet_lapis_trim.json
+ minecraft/models/item/copper_helmet_netherite_trim.json
+ minecraft/models/item/copper_helmet_quartz_trim.json
+ minecraft/models/item/copper_helmet_redstone_trim.json
+ minecraft/models/item/copper_helmet_resin_trim.json
+ minecraft/models/item/copper_helmet.json
+ minecraft/models/item/copper_hoe.json
+ minecraft/models/item/copper_horse_armor.json
+ minecraft/models/item/copper_leggings_amethyst_trim.json
+ minecraft/models/item/copper_leggings_copper_trim.json
+ minecraft/models/item/copper_leggings_diamond_trim.json
+ minecraft/models/item/copper_leggings_emerald_trim.json
+ minecraft/models/item/copper_leggings_gold_trim.json
+ minecraft/models/item/copper_leggings_iron_trim.json
+ minecraft/models/item/copper_leggings_lapis_trim.json
+ minecraft/models/item/copper_leggings_netherite_trim.json
+ minecraft/models/item/copper_leggings_quartz_trim.json
+ minecraft/models/item/copper_leggings_redstone_trim.json
+ minecraft/models/item/copper_leggings_resin_trim.json
+ minecraft/models/item/copper_leggings.json
+ minecraft/models/item/copper_nugget.json
+ minecraft/models/item/copper_pickaxe.json
+ minecraft/models/item/copper_shovel.json
+ minecraft/models/item/copper_sword.json
+ minecraft/models/item/exposed_copper_chest.json
+ minecraft/models/item/oxidized_copper_chest.json
+ minecraft/models/item/template_copper_golem_statue.json
+ minecraft/models/item/weathered_copper_chest.json
- minecraft/shaders/core/blit_screen.vsh
+ minecraft/shaders/core/screenquad.vsh
- minecraft/shaders/post/blit.vsh
- minecraft/shaders/post/blur.vsh
- minecraft/shaders/post/invert.vsh
- minecraft/shaders/post/screenquad.vsh
- minecraft/shaders/post/sobel.vsh
+ minecraft/textures/block/acacia_shelf.png
+ minecraft/textures/block/bamboo_shelf.png
+ minecraft/textures/block/birch_shelf.png
+ minecraft/textures/block/cherry_shelf.png
+ minecraft/textures/block/crimson_shelf.png
+ minecraft/textures/block/dark_oak_shelf.png
+ minecraft/textures/block/exposed_lightning_rod.png
+ minecraft/textures/block/jungle_shelf.png
+ minecraft/textures/block/mangrove_shelf.png
+ minecraft/textures/block/oak_shelf.png
+ minecraft/textures/block/oxidized_lightning_rod.png
+ minecraft/textures/block/pale_oak_shelf.png
+ minecraft/textures/block/spruce_shelf.png
+ minecraft/textures/block/warped_shelf.png
+ minecraft/textures/block/weathered_lightning_rod.png
+ minecraft/textures/entity/chest/copper_exposed_left.png
+ minecraft/textures/entity/chest/copper_exposed_right.png
+ minecraft/textures/entity/chest/copper_exposed.png
+ minecraft/textures/entity/chest/copper_left.png
+ minecraft/textures/entity/chest/copper_oxidized_left.png
+ minecraft/textures/entity/chest/copper_oxidized_right.png
+ minecraft/textures/entity/chest/copper_oxidized.png
+ minecraft/textures/entity/chest/copper_right.png
+ minecraft/textures/entity/chest/copper_weathered_left.png
+ minecraft/textures/entity/chest/copper_weathered_right.png
+ minecraft/textures/entity/chest/copper_weathered.png
+ minecraft/textures/entity/chest/copper.png
+ minecraft/textures/entity/copper_golem/copper_golem_eyes.png
+ minecraft/textures/entity/copper_golem/copper_golem.png
+ minecraft/textures/entity/copper_golem/exposed_copper_golem_eyes.png
+ minecraft/textures/entity/copper_golem/exposed_copper_golem.png
+ minecraft/textures/entity/copper_golem/oxidized_copper_golem_eyes.png
+ minecraft/textures/entity/copper_golem/oxidized_copper_golem.png
+ minecraft/textures/entity/copper_golem/weathered_copper_golem_eyes.png
+ minecraft/textures/entity/copper_golem/weathered_copper_golem.png
+ minecraft/textures/entity/equipment/horse_body/copper.png
+ minecraft/textures/entity/equipment/humanoid_leggings/copper.png
+ minecraft/textures/entity/equipment/humanoid/copper.png
+ minecraft/textures/item/copper_axe.png
+ minecraft/textures/item/copper_boots.png
+ minecraft/textures/item/copper_chestplate.png
+ minecraft/textures/item/copper_golem_spawn_egg.png
+ minecraft/textures/item/copper_helmet.png
+ minecraft/textures/item/copper_hoe.png
+ minecraft/textures/item/copper_horse_armor.png
+ minecraft/textures/item/copper_leggings.png
+ minecraft/textures/item/copper_nugget.png
+ minecraft/textures/item/copper_pickaxe.png
+ minecraft/textures/item/copper_shovel.png
+ minecraft/textures/item/copper_sword.png
- minecraft/textures/misc/white.png
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
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.Attribute$Sentiment
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeInstance$Packed
- XXX.ai.attributes.AttributeMap
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.attributes.Attributes
+ XXX.ai.attributes.AttributeSupplier
- XXX.ai.attributes.AttributeSupplier$Builder
- XXX.ai.attributes.DefaultAttributes
- XXX.ai.attributes.package-info
+ XXX.ai.attributes.RangedAttribute
+ XXX.ai.behavior.AcquirePoi
- XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
+ XXX.ai.behavior.AnimalMakeLove
- XXX.ai.behavior.AnimalPanic
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.BabyFollowAdult
+ XXX.ai.behavior.BackUpIfTooClose
- XXX.ai.behavior.BecomePassiveIfMemoryPresent
+ XXX.ai.behavior.Behavior
- XXX.ai.behavior.Behavior$Status
+ XXX.ai.behavior.BehaviorControl
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosTracker
- XXX.ai.behavior.CelebrateVillagersSurvivedRaid
+ XXX.ai.behavior.CopyMemoryWithExpiry
- XXX.ai.behavior.CountDownCooldownTicks
+ XXX.ai.behavior.Croak
- XXX.ai.behavior.CrossbowAttack
+ XXX.ai.behavior.CrossbowAttack$CrossbowState
- XXX.ai.behavior.DismountOrSkipMounting
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityTracker
+ XXX.ai.behavior.EraseMemoryIf
- XXX.ai.behavior.FollowTemptation
+ XXX.ai.behavior.GateBehavior
- XXX.ai.behavior.GateBehavior$OrderPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy$1
+ XXX.ai.behavior.GateBehavior$RunningPolicy$2
- XXX.ai.behavior.GiveGiftToHero
+ XXX.ai.behavior.GoAndGiveItemsToTarget
- XXX.ai.behavior.GoToClosestVillage
+ XXX.ai.behavior.GoToPotentialJobSite
- XXX.ai.behavior.GoToTargetLocation
+ XXX.ai.behavior.GoToWantedItem
- XXX.ai.behavior.HarvestFarmland
+ XXX.ai.behavior.InsideBrownianWalk
- XXX.ai.behavior.InteractWith
+ XXX.ai.behavior.InteractWithDoor
- XXX.ai.behavior.JumpOnBed
+ XXX.ai.behavior.LocateHidingPlace
- XXX.ai.behavior.LongJumpMidJump
+ XXX.ai.behavior.LongJumpToPreferredBlock
- XXX.ai.behavior.LongJumpToRandomPos
+ XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
- XXX.ai.behavior.LongJumpUtil
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MeleeAttack
- XXX.ai.behavior.Mount
+ XXX.ai.behavior.MoveToSkySeeingSpot
- XXX.ai.behavior.MoveToTargetSink
+ XXX.ai.behavior.OneShot
- XXX.ai.behavior.PlayTagWithOtherKids
+ XXX.ai.behavior.PoiCompetitorScan
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.PrepareRamNearestTarget
- XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ XXX.ai.behavior.RamTarget
- XXX.ai.behavior.RandomLookAround
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetEntityLookTargetSometimes
- XXX.ai.behavior.SetEntityLookTargetSometimes$Ticker
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.ShufflingList
- XXX.ai.behavior.ShufflingList$WeightedEntry
+ XXX.ai.behavior.ShufflingList$WeightedEntry$1
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartAttacking$StartAttackingCondition
- XXX.ai.behavior.StartAttacking$TargetFinder
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopAttackingIfTargetInvalid$StopAttackCondition
+ XXX.ai.behavior.StopAttackingIfTargetInvalid$TargetErasedCallback
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TransportItemsBetweenContainers
- XXX.ai.behavior.TransportItemsBetweenContainers$OnTargetReachedInteraction
- XXX.ai.behavior.TransportItemsBetweenContainers$TransportItemTarget
- XXX.animal.coppergolem.CopperGolem$1
- XXX.animal.coppergolem.CopperGolemOxidationLevel
- XXX.animal.coppergolem.CopperGolemState
- XXX.animal.frog.Frog
+ XXX.animal.frog.Frog$FrogLookControl
- XXX.animal.frog.Frog$FrogNodeEvaluator
+ XXX.animal.frog.Frog$FrogPathNavigation
- XXX.animal.frog.FrogAi
+ XXX.animal.frog.FrogVariant
- XXX.animal.frog.FrogVariants
+ XXX.animal.frog.package-info
+ XXX.animal.frog.ShootTongue
- XXX.animal.frog.ShootTongue$State
+ XXX.animal.frog.Tadpole
- XXX.animal.frog.TadpoleAi
- XXX.animal.goat.Goat
+ XXX.animal.goat.GoatAi
- XXX.animal.goat.package-info
+ XXX.animal.horse.AbstractChestedHorse
- XXX.animal.horse.AbstractChestedHorse$1
+ XXX.animal.horse.AbstractHorse
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Llama$Variant
- XXX.animal.horse.Markings
+ XXX.animal.horse.Mule
- XXX.animal.horse.package-info
- XXX.animal.horse.SkeletonHorse
+ XXX.animal.horse.SkeletonTrapGoal
- XXX.animal.horse.TraderLlama
+ XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.animal.horse.Variant
+ XXX.animal.horse.ZombieHorse
- XXX.animal.sheep.package-info
- XXX.animal.sheep.Sheep
+ XXX.animal.sheep.SheepColorSpawnRules
- XXX.animal.sheep.SheepColorSpawnRules$SheepColorProvider
+ XXX.animal.sheep.SheepColorSpawnRules$SheepColorSpawnConfiguration
+ XXX.animal.sniffer.package-info
+ XXX.animal.sniffer.Sniffer
- XXX.animal.sniffer.Sniffer$State
+ XXX.animal.sniffer.SnifferAi
- XXX.animal.sniffer.SnifferAi$1
+ XXX.animal.sniffer.SnifferAi$2
- XXX.animal.sniffer.SnifferAi$3
+ XXX.animal.sniffer.SnifferAi$Digging
- XXX.animal.sniffer.SnifferAi$FeelingHappy
+ XXX.animal.sniffer.SnifferAi$FinishedDigging
- XXX.animal.sniffer.SnifferAi$Scenting
+ XXX.animal.sniffer.SnifferAi$Searching
- XXX.animal.sniffer.SnifferAi$Sniffing
+ XXX.animal.wolf.package-info
- XXX.animal.wolf.Wolf
+ XXX.animal.wolf.Wolf$WolfAvoidEntityGoal
- XXX.animal.wolf.Wolf$WolfPackData
+ XXX.animal.wolf.WolfSoundVariant
- XXX.animal.wolf.WolfSoundVariants
+ XXX.animal.wolf.WolfSoundVariants$SoundSet
- XXX.animal.wolf.WolfVariant
+ XXX.animal.wolf.WolfVariant$AssetInfo
- XXX.animal.wolf.WolfVariants
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPatternLayers
+ XXX.block.entity.BannerPatternLayers$Builder
- XXX.block.entity.BannerPatternLayers$Layer
+ XXX.block.entity.BannerPatterns
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBeamOwner
- XXX.block.entity.BeaconBeamOwner$Section
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$BeeData
- XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ XXX.block.entity.BeehiveBlockEntity$Occupant
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntity$1
+ XXX.block.entity.BlockEntity$BlockEntityPathElement
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BoundingBoxRenderable
- XXX.block.entity.BoundingBoxRenderable$Mode
+ XXX.block.entity.BoundingBoxRenderable$RenderableBox
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.BrushableBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
+ XXX.block.entity.ChiseledBookShelfBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.CopperGolemStatueBlockEntity
- XXX.block.entity.PotDecorations
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity$VibrationUser
- XXX.block.entity.SculkShriekerBlockEntity
+ XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
- XXX.block.entity.ShelfBlockEntity
+ XXX.block.entity.SkullBlockEntity$1
+ XXX.boss.enderdragon.DragonFlightHistory
- XXX.boss.enderdragon.DragonFlightHistory$Sample
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.DataSource$Type
- XXX.chat.contents.EntityDataSource
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.NbtContents
- XXX.chat.contents.package-info
- XXX.chat.contents.PlainTextContents
+ XXX.chat.contents.PlainTextContents$1
- XXX.chat.contents.PlainTextContents$LiteralContents
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.StorageDataSource
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
+ XXX.chat.numbers.BlankFormat
- XXX.chat.numbers.BlankFormat$1
+ XXX.chat.numbers.FixedFormat
- XXX.chat.numbers.FixedFormat$1
+ XXX.chat.numbers.NumberFormat
- XXX.chat.numbers.NumberFormatType
+ XXX.chat.numbers.NumberFormatTypes
- XXX.chat.numbers.package-info
- XXX.chat.numbers.StyledFormat
+ XXX.chat.numbers.StyledFormat$1
- XXX.chunk.status.ChunkDependencies
+ XXX.chunk.status.ChunkPyramid
- XXX.chunk.status.ChunkPyramid$Builder
+ XXX.chunk.status.ChunkStatus
- XXX.chunk.status.ChunkStatusTask
+ XXX.chunk.status.ChunkStatusTasks
- XXX.chunk.status.ChunkStep
+ XXX.chunk.status.ChunkStep$Builder
- XXX.chunk.status.ChunkType
- XXX.chunk.status.package-info
+ XXX.chunk.status.WorldGenContext
+ XXX.chunk.storage.ChunkIOErrorReporter
- XXX.chunk.storage.ChunkScanAccess
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.IOWorker$ThrowingSupplier
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RecreatingChunkStorage
- XXX.chunk.storage.RecreatingSimpleRegionStorage
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.RegionStorageInfo
+ XXX.chunk.storage.SectionStorage
- XXX.chunk.storage.SectionStorage$PackedChunk
+ XXX.chunk.storage.SerializableChunkData
- XXX.chunk.storage.SerializableChunkData$ChunkReadException
+ XXX.chunk.storage.SerializableChunkData$SectionData
- XXX.chunk.storage.SimpleRegionStorage
- XXX.common.custom.BeeDebugPayload
+ XXX.common.custom.BeeDebugPayload$BeeInfo
- XXX.common.custom.BrainDebugPayload
+ XXX.common.custom.BrainDebugPayload$BrainDump
- XXX.common.custom.BrandPayload
+ XXX.common.custom.BreezeDebugPayload
- XXX.common.custom.BreezeDebugPayload$BreezeInfo
+ XXX.common.custom.CustomPacketPayload
- XXX.common.custom.CustomPacketPayload$1
+ XXX.common.custom.CustomPacketPayload$FallbackProvider
- XXX.common.custom.CustomPacketPayload$Type
+ XXX.common.custom.CustomPacketPayload$TypeAndCodec
- XXX.common.custom.DiscardedPayload
+ XXX.common.custom.GameEventDebugPayload
- XXX.common.custom.GameEventListenerDebugPayload
+ XXX.common.custom.GameTestAddMarkerDebugPayload
- XXX.common.custom.GameTestClearMarkersDebugPayload
+ XXX.common.custom.GoalDebugPayload
- XXX.common.custom.GoalDebugPayload$DebugGoal
+ XXX.common.custom.HiveDebugPayload
- XXX.common.custom.HiveDebugPayload$HiveInfo
+ XXX.common.custom.NeighborUpdatesDebugPayload
+ XXX.common.custom.package-info
- XXX.common.custom.PathfindingDebugPayload
+ XXX.common.custom.PoiAddedDebugPayload
- XXX.common.custom.PoiRemovedDebugPayload
+ XXX.common.custom.PoiTicketCountDebugPayload
- XXX.common.custom.RaidsDebugPayload
+ XXX.common.custom.RedstoneWireOrientationsDebugPayload
- XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
+ XXX.common.custom.StructuresDebugPayload
- XXX.common.custom.StructuresDebugPayload$PieceInfo
+ XXX.common.custom.VillageSectionsDebugPayload
- XXX.common.custom.WorldGenAttemptDebugPayload
+ XXX.crafting.display.DisplayContentsFactory
- XXX.crafting.display.DisplayContentsFactory$ForRemainders
+ XXX.crafting.display.DisplayContentsFactory$ForStacks
- XXX.crafting.display.FurnaceRecipeDisplay
+ XXX.crafting.display.package-info
+ XXX.crafting.display.RecipeDisplay
- XXX.crafting.display.RecipeDisplay$Type
+ XXX.crafting.display.RecipeDisplayEntry
- XXX.crafting.display.RecipeDisplayId
+ XXX.crafting.display.RecipeDisplays
- XXX.crafting.display.ShapedCraftingRecipeDisplay
+ XXX.crafting.display.ShapelessCraftingRecipeDisplay
- XXX.crafting.display.SlotDisplay
+ XXX.crafting.display.SlotDisplay$AnyFuel
- XXX.crafting.display.SlotDisplay$Composite
+ XXX.crafting.display.SlotDisplay$Empty
- XXX.crafting.display.SlotDisplay$ItemSlotDisplay
+ XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
- XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
+ XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
- XXX.crafting.display.SlotDisplay$TagSlotDisplay
+ XXX.crafting.display.SlotDisplay$Type
- XXX.crafting.display.SlotDisplay$WithRemainder
+ XXX.crafting.display.SlotDisplayContext
- XXX.crafting.display.SlotDisplays
+ XXX.crafting.display.SmithingRecipeDisplay
- XXX.crafting.display.StonecutterRecipeDisplay
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractBlockPropertyFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
- XXX.datafix.fixes.AreaEffectCloudPotionFix
+ XXX.datafix.fixes.AttributeIdPrefixFix
- XXX.datafix.fixes.AttributeModifierIdFix
+ XXX.datafix.fixes.AttributesRenameFix
- XXX.datafix.fixes.AttributesRenameLegacy
+ XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
- XXX.datafix.fixes.BannerPatternFormatFix
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BeehiveFieldRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlendingDataFix
- XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityFurnaceBurnTimeFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityRenameFix
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockPosFormatAndRenamesFix
- XXX.datafix.fixes.BlockPropertyRenameAndFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.BoatSplitFix
- XXX.datafix.fixes.CarvingStepRemoveFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
+ XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.fixes.ChunkDeleteLightFix
+ XXX.datafix.fixes.ChunkHeightAndBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkProtoTickListFix
- XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ XXX.datafix.fixes.ChunkRenamesFix
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkTicketUnpackPosFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.ContainerBlockEntityLockPredicateFix
+ XXX.datafix.fixes.CriteriaRenameFix
- XXX.datafix.fixes.CustomModelDataExpandFix
+ XXX.datafix.fixes.DataComponentRemainderFix
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DropChancesFormatFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityAttributeBaseValueFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityFallDistanceFloatToDoubleFix
+ XXX.datafix.fixes.EntityFieldsRenameFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
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
+ XXX.datafix.fixes.EntitySalmonSizeFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix
- XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix$Fixer
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.EquipmentFormatFix
+ XXX.datafix.fixes.EquippableAssetRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FixWolfHealth
+ XXX.datafix.fixes.FoodToConsumableFix
+ XXX.datafix.fixes.ForcedChunkToTicketFix
- XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.HorseBodyArmorItemFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.InlineBlockPosFormatFix
+ XXX.datafix.fixes.InvalidBlockEntityLockFix
- XXX.datafix.fixes.InvalidLockComponentFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackComponentizationFix
+ XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
+ XXX.datafix.fixes.ItemStackTagRemainderFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LegacyDimensionIdFix
- XXX.datafix.fixes.LegacyDragonFightFix
+ XXX.datafix.fixes.LegacyHoverEventFix
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.LockComponentPredicateFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityConvertUncheckedFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamedEntityWriteReadFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRarityFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsMenuBlurrinessFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
+ XXX.datafix.fixes.package-info
- XXX.datafix.fixes.ParticleUnflatteningFix
+ XXX.datafix.fixes.PlayerEquipmentFix
- XXX.datafix.fixes.PlayerHeadBlockProfileFix
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.PrimedTntBlockStateFixer
+ XXX.datafix.fixes.ProjectileStoredWeaponFix
- XXX.datafix.fixes.RaidRenamesDataFix
+ XXX.datafix.fixes.RandomSequenceSettingsFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.References$1
+ XXX.datafix.fixes.RemapChunkStatusFix
- XXX.datafix.fixes.RemoveBlockEntityTagFix
+ XXX.datafix.fixes.RemoveEmptyItemInBrushableBlockFix
- XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.RenameEnchantmentsFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.datafix.fixes.SaddleEquipmentSlotFix
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.ScoreboardDisplayNameFix
+ XXX.datafix.fixes.ScoreboardDisplaySlotFix
- XXX.datafix.fixes.SignTextStrictJsonFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.SpawnerDataFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StatsCounterFix$StatType
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ XXX.datafix.fixes.StructureSettingsFlattenFix
- XXX.datafix.fixes.TextComponentHoverAndClickEventFix
+ XXX.datafix.fixes.TextComponentStringifiedFlagsFix
- XXX.datafix.fixes.ThrownPotionSplitFix
+ XXX.datafix.fixes.ThrownPotionSplitFix$ItemIdFinder
- XXX.datafix.fixes.TippedArrowPotionToItemFix
+ XXX.datafix.fixes.TooltipDisplayComponentFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.TrialSpawnerConfigFix
+ XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix
- XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix$VanillaTrialChambers
+ XXX.datafix.fixes.UnflattenTextComponentFix
- XXX.datafix.fixes.VariantRenameFix
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerFollowRangeFix
+ XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
- XXX.datafix.fixes.VillagerSetCanPickUpLootFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WeaponSmithChestLootTableFix
- XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- XXX.datafix.fixes.WriteAndReadFix
+ XXX.datafix.fixes.WrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
- XXX.datafix.schemas.NamespacedSchema$1
+ XXX.datafix.schemas.V100
- XXX.datafix.schemas.V102
+ XXX.datafix.schemas.V1022
- XXX.datafix.schemas.V106
+ XXX.datafix.schemas.V107
- XXX.datafix.schemas.V1125
+ XXX.datafix.schemas.V135
- XXX.datafix.schemas.V143
+ XXX.datafix.schemas.V1451
- XXX.datafix.schemas.V1451_1
+ XXX.datafix.schemas.V1451_2
- XXX.datafix.schemas.V1451_3
+ XXX.datafix.schemas.V1451_4
- XXX.datafix.schemas.V1451_5
+ XXX.datafix.schemas.V1451_6
- XXX.datafix.schemas.V1451_6$1
+ XXX.datafix.schemas.V1451_6$2
- XXX.datafix.schemas.V1458
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1466
+ XXX.datafix.schemas.V1470
- XXX.datafix.schemas.V1481
+ XXX.datafix.schemas.V1483
- XXX.datafix.schemas.V1486
+ XXX.datafix.schemas.V1488
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2511_1
- XXX.datafix.schemas.V2519
+ XXX.datafix.schemas.V2522
- XXX.datafix.schemas.V2551
+ XXX.datafix.schemas.V2568
- XXX.datafix.schemas.V2571
+ XXX.datafix.schemas.V2684
- XXX.datafix.schemas.V2686
+ XXX.datafix.schemas.V2688
- XXX.datafix.schemas.V2704
+ XXX.datafix.schemas.V2707
- XXX.datafix.schemas.V2831
+ XXX.datafix.schemas.V2832
- XXX.datafix.schemas.V2842
+ XXX.datafix.schemas.V3076
- XXX.datafix.schemas.V3078
+ XXX.datafix.schemas.V3081
- XXX.datafix.schemas.V3082
+ XXX.datafix.schemas.V3083
- XXX.datafix.schemas.V3202
+ XXX.datafix.schemas.V3203
- XXX.datafix.schemas.V3204
+ XXX.datafix.schemas.V3325
- XXX.datafix.schemas.V3326
+ XXX.datafix.schemas.V3327
- XXX.datafix.schemas.V3328
+ XXX.datafix.schemas.V3438
- XXX.datafix.schemas.V3439
+ XXX.datafix.schemas.V3439_1
- XXX.datafix.schemas.V3448
+ XXX.datafix.schemas.V3682
- XXX.datafix.schemas.V3683
+ XXX.datafix.schemas.V3685
- XXX.datafix.schemas.V3689
+ XXX.datafix.schemas.V3799
- XXX.datafix.schemas.V3807
+ XXX.datafix.schemas.V3808
- XXX.datafix.schemas.V3808_1
+ XXX.datafix.schemas.V3808_2
- XXX.datafix.schemas.V3813
+ XXX.datafix.schemas.V3816
- XXX.datafix.schemas.V3818
+ XXX.datafix.schemas.V3818_3
- XXX.datafix.schemas.V3818_4
+ XXX.datafix.schemas.V3818_5
- XXX.datafix.schemas.V3825
+ XXX.datafix.schemas.V3938
- XXX.datafix.schemas.V4059
+ XXX.datafix.schemas.V4067
- XXX.datafix.schemas.V4070
+ XXX.datafix.schemas.V4071
- XXX.datafix.schemas.V4290
+ XXX.datafix.schemas.V4292
- XXX.datafix.schemas.V4300
+ XXX.datafix.schemas.V4301
- XXX.datafix.schemas.V4302
+ XXX.datafix.schemas.V4306
- XXX.datafix.schemas.V4307
+ XXX.datafix.schemas.V4312
- XXX.datafix.schemas.V4420
+ XXX.datafix.schemas.V4421
- XXX.datafix.schemas.V4531
- XXX.datafix.schemas.V4533
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
- XXX.dimension.end.EndDragonFight$Data
+ XXX.dimension.end.package-info
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyMobEffect
+ XXX.enchantment.effects.ChangeItemDamage
- XXX.enchantment.effects.DamageEntity
+ XXX.enchantment.effects.DamageImmunity
- XXX.enchantment.effects.EnchantmentAttributeEffect
+ XXX.enchantment.effects.EnchantmentEntityEffect
- XXX.enchantment.effects.EnchantmentLocationBasedEffect
+ XXX.enchantment.effects.EnchantmentValueEffect
- XXX.enchantment.effects.ExplodeEffect
+ XXX.enchantment.effects.Ignite
- XXX.enchantment.effects.MultiplyValue
- XXX.enchantment.effects.package-info
+ XXX.enchantment.effects.PlaySoundEffect
- XXX.enchantment.effects.RemoveBinomial
+ XXX.enchantment.effects.ReplaceBlock
- XXX.enchantment.effects.ReplaceDisk
+ XXX.enchantment.effects.RunFunction
- XXX.enchantment.effects.SetBlockProperties
+ XXX.enchantment.effects.SetValue
- XXX.enchantment.effects.SpawnParticlesEffect
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
- XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
+ XXX.enchantment.effects.SummonEntityEffect
- XXX.enchantment.providers.EnchantmentProvider
+ XXX.enchantment.providers.EnchantmentProviderTypes
- XXX.enchantment.providers.EnchantmentsByCost
+ XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
+ XXX.enchantment.providers.package-info
- XXX.enchantment.providers.SingleEnchantment
+ XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
- XXX.enchantment.providers.VanillaEnchantmentProviders
- XXX.enderdragon.phases.AbstractDragonPhaseInstance
+ XXX.enderdragon.phases.AbstractDragonSittingPhase
- XXX.enderdragon.phases.DragonChargePlayerPhase
+ XXX.enderdragon.phases.DragonDeathPhase
- XXX.enderdragon.phases.DragonHoldingPatternPhase
+ XXX.enderdragon.phases.DragonHoverPhase
- XXX.enderdragon.phases.DragonLandingApproachPhase
+ XXX.enderdragon.phases.DragonLandingPhase
- XXX.enderdragon.phases.DragonPhaseInstance
+ XXX.enderdragon.phases.DragonSittingAttackingPhase
- XXX.enderdragon.phases.DragonSittingFlamingPhase
+ XXX.enderdragon.phases.DragonSittingScanningPhase
- XXX.enderdragon.phases.DragonStrafePlayerPhase
+ XXX.enderdragon.phases.DragonTakeoffPhase
- XXX.enderdragon.phases.EnderDragonPhase
+ XXX.enderdragon.phases.EnderDragonPhaseManager
- XXX.enderdragon.phases.package-info
- XXX.entity.ai.Brain
+ XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$MemoryValue
+ XXX.entity.ai.Brain$Provider
+ XXX.entity.animal.package-info
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.ArmorStand$ArmorStandPose
+ XXX.entity.decoration.BlockAttachedEntity
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
- XXX.entity.decoration.PaintingVariant
+ XXX.entity.decoration.PaintingVariants
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
+ XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
- XXX.entity.item.PrimedTnt$1
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.Bogged
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$EvokerAttackSpellGoal
- XXX.entity.monster.Evoker$EvokerCastingSpellGoal
+ XXX.entity.monster.Evoker$EvokerSummonSpellGoal
- XXX.entity.monster.Evoker$EvokerWololoSpellGoal
+ XXX.entity.monster.Ghast
- XXX.entity.monster.Ghast$GhastLookGoal
+ XXX.entity.monster.Ghast$GhastMoveControl
- XXX.entity.monster.Ghast$GhastShootFireballGoal
+ XXX.entity.monster.Ghast$RandomFloatAroundGoal
- XXX.entity.monster.Giant
+ XXX.entity.monster.Guardian
- XXX.entity.monster.Guardian$GuardianAttackGoal
+ XXX.entity.monster.Guardian$GuardianAttackSelector
- XXX.entity.monster.Guardian$GuardianMoveControl
+ XXX.entity.monster.Husk
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
+ XXX.entity.monster.package-info
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$AttackPhase
+ XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
+ XXX.entity.monster.Phantom$PhantomBodyRotationControl
- XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ XXX.entity.monster.Phantom$PhantomLookControl
- XXX.entity.monster.Phantom$PhantomMoveControl
+ XXX.entity.monster.Phantom$PhantomMoveTargetGoal
- XXX.entity.monster.Phantom$PhantomSweepAttackGoal
+ XXX.entity.monster.Pillager
- XXX.entity.monster.RangedAttackMob
+ XXX.entity.monster.Ravager
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$ShulkerAttackGoal
- XXX.entity.monster.Shulker$ShulkerBodyRotationControl
+ XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
- XXX.entity.monster.Shulker$ShulkerLookControl
+ XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
- XXX.entity.monster.Shulker$ShulkerPeekGoal
+ XXX.entity.monster.Silverfish
- XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- XXX.entity.monster.Skeleton
+ XXX.entity.monster.Slime
- XXX.entity.monster.Slime$SlimeAttackGoal
+ XXX.entity.monster.Slime$SlimeFloatGoal
- XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ XXX.entity.monster.Slime$SlimeMoveControl
- XXX.entity.monster.Slime$SlimeRandomDirectionGoal
+ XXX.entity.monster.SpellcasterIllager
- XXX.entity.monster.SpellcasterIllager$IllagerSpell
+ XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ XXX.entity.monster.Spider
- XXX.entity.monster.Spider$SpiderAttackGoal
+ XXX.entity.monster.Spider$SpiderEffectsGroupData
- XXX.entity.monster.Spider$SpiderTargetGoal
+ XXX.entity.monster.Stray
- XXX.entity.monster.Strider
+ XXX.entity.monster.Strider$StriderGoToLavaGoal
- XXX.entity.monster.Strider$StriderPathNavigation
+ XXX.entity.monster.Vex
- XXX.entity.monster.Vex$VexChargeAttackGoal
+ XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
- XXX.entity.monster.Vex$VexMoveControl
+ XXX.entity.monster.Vex$VexRandomMoveGoal
- XXX.entity.monster.Vindicator
+ XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
- XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zoglin
- XXX.entity.monster.Zombie
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
- XXX.entity.monster.ZombifiedPiglin
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
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
- XXX.entity.npc.VillagerTrades$FailureItemListing
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerTrades$TypeSpecificTrade
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.Abilities$Packed
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Input
- XXX.entity.player.Input$1
+ XXX.entity.player.Inventory
+ XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$2
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerEquipment
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$IngredientInfo
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.AbstractThrownPotion
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.Projectile$ProjectileFactory
- XXX.entity.projectile.ProjectileDeflection
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownLingeringPotion
- XXX.entity.projectile.ThrownSplashPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
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
- XXX.entity.raid.Raids$RaidWithId
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.variant.BiomeCheck
- XXX.entity.variant.ModelAndTexture
+ XXX.entity.variant.MoonBrightnessCheck
- XXX.entity.variant.package-info
- XXX.entity.variant.PriorityProvider
+ XXX.entity.variant.PriorityProvider$Selector
- XXX.entity.variant.PriorityProvider$SelectorCondition
+ XXX.entity.variant.PriorityProvider$UnpackedEntry
- XXX.entity.variant.SpawnCondition
+ XXX.entity.variant.SpawnConditions
- XXX.entity.variant.SpawnContext
+ XXX.entity.variant.SpawnPrioritySelectors
- XXX.entity.variant.StructureCheck
+ XXX.entity.variant.VariantUtils
+ XXX.entity.vehicle.AbstractBoat
- XXX.entity.vehicle.AbstractBoat$Status
+ XXX.entity.vehicle.AbstractChestBoat
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestRaft
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartBehavior
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
- XXX.entity.vehicle.NewMinecartBehavior
+ XXX.entity.vehicle.NewMinecartBehavior$1
- XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
+ XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
- XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
+ XXX.entity.vehicle.OldMinecartBehavior
- XXX.entity.vehicle.OldMinecartBehavior$1
+ XXX.entity.vehicle.package-info
+ XXX.entity.vehicle.Raft
- XXX.entity.vehicle.VehicleEntity
+ XXX.equipment.trim.ArmorTrim
- XXX.equipment.trim.MaterialAssetGroup
+ XXX.equipment.trim.MaterialAssetGroup$AssetInfo
- XXX.equipment.trim.package-info
- XXX.equipment.trim.TrimMaterial
+ XXX.equipment.trim.TrimMaterials
- XXX.equipment.trim.TrimPattern
+ XXX.equipment.trim.TrimPatterns
+ XXX.gameevent.vibrations.package-info
- XXX.gameevent.vibrations.VibrationInfo
+ XXX.gameevent.vibrations.VibrationSelector
- XXX.gameevent.vibrations.VibrationSystem
+ XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Listener
+ XXX.gameevent.vibrations.VibrationSystem$Ticker
- XXX.gameevent.vibrations.VibrationSystem$User
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTicker$State
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.GeneratedTest
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.RetryOptions
+ XXX.gametest.framework.StructureGridSpawner
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestBatchSummaryDisplayer
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestData
- XXX.gametest.framework.TestEnvironmentDefinition
+ XXX.gametest.framework.TestEnvironmentDefinition$AllOf
- XXX.gametest.framework.TestEnvironmentDefinition$Functions
+ XXX.gametest.framework.TestEnvironmentDefinition$SetGameRules
- XXX.gametest.framework.TestEnvironmentDefinition$SetGameRules$Entry
+ XXX.gametest.framework.TestEnvironmentDefinition$TimeOfDay
- XXX.gametest.framework.TestEnvironmentDefinition$Weather
+ XXX.gametest.framework.TestEnvironmentDefinition$Weather$Type
- XXX.gametest.framework.TestFinder
+ XXX.gametest.framework.TestFinder$Builder
- XXX.gametest.framework.TestFunctionLoader
+ XXX.gametest.framework.TestInstanceFinder
- XXX.gametest.framework.TestPosFinder
+ XXX.gametest.framework.TestReporter
- XXX.gametest.framework.UnknownGameTestException
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Builder
+ XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.PotionContents
+ XXX.item.alchemy.Potions
+ XXX.item.component.Bees
- XXX.item.component.BlockItemStateProperties
+ XXX.item.component.BlocksAttacks
- XXX.item.component.BlocksAttacks$DamageReduction
+ XXX.item.component.BlocksAttacks$ItemDamageFunction
- XXX.item.component.BookContent
+ XXX.item.component.BundleContents
- XXX.item.component.BundleContents$Mutable
+ XXX.item.component.ChargedProjectiles
- XXX.item.component.Consumable
+ XXX.item.component.Consumable$Builder
- XXX.item.component.Consumable$OverrideConsumeSound
+ XXX.item.component.ConsumableListener
- XXX.item.component.Consumables
+ XXX.item.component.CustomData
- XXX.item.component.CustomModelData
+ XXX.item.component.DamageResistant
- XXX.item.component.DeathProtection
+ XXX.item.component.DebugStickState
- XXX.item.component.DyedItemColor
+ XXX.item.component.FireworkExplosion
- XXX.item.component.FireworkExplosion$Shape
+ XXX.item.component.Fireworks
- XXX.item.component.InstrumentComponent
+ XXX.item.component.ItemAttributeModifiers
- XXX.item.component.ItemAttributeModifiers$1
+ XXX.item.component.ItemAttributeModifiers$Builder
- XXX.item.component.ItemAttributeModifiers$Display
+ XXX.item.component.ItemAttributeModifiers$Display$Default
- XXX.item.component.ItemAttributeModifiers$Display$Hidden
+ XXX.item.component.ItemAttributeModifiers$Display$OverrideText
- XXX.item.component.ItemAttributeModifiers$Display$Type
+ XXX.item.component.ItemAttributeModifiers$Entry
- XXX.item.component.ItemContainerContents
+ XXX.item.component.ItemContainerContents$Slot
- XXX.item.component.ItemLore
+ XXX.item.component.LodestoneTracker
- XXX.item.component.MapDecorations
+ XXX.item.component.MapDecorations$Entry
- XXX.item.component.MapItemColor
+ XXX.item.component.MapPostProcessing
- XXX.item.component.OminousBottleAmplifier
- XXX.item.component.package-info
+ XXX.item.component.ProvidesTrimMaterial
- XXX.item.component.ResolvableProfile
- XXX.item.component.ResolvableProfile$Resolver$1
- XXX.item.component.UseCooldown
+ XXX.item.component.UseRemainder
- XXX.item.component.UseRemainder$OnExtraCreatedRemainder
+ XXX.item.component.Weapon
- XXX.item.component.WritableBookContent
+ XXX.item.component.WrittenBookContent
+ XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
- XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect
- XXX.item.consume_effects.ConsumeEffect$Type
- XXX.item.consume_effects.package-info
+ XXX.item.consume_effects.PlaySoundConsumeEffect
- XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
+ XXX.item.consume_effects.TeleportRandomlyConsumeEffect
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.AbstractCookingRecipe$Factory
- XXX.item.crafting.AbstractCookingRecipe$Serializer
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BlastingRecipe$1
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingBookCategory
+ XXX.item.crafting.CraftingInput
- XXX.item.crafting.CraftingInput$Positioned
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CraftingRecipe$1
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.CustomRecipe$Serializer
+ XXX.item.crafting.CustomRecipe$Serializer$Factory
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.ExtendedRecipeBookCategory
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
- XXX.item.crafting.PlacementInfo
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeAccess
+ XXX.item.crafting.RecipeBookCategories
- XXX.item.crafting.RecipeBookCategory
+ XXX.item.crafting.RecipeCache
- XXX.item.crafting.RecipeCache$Entry
+ XXX.item.crafting.RecipeHolder
- XXX.item.crafting.RecipeInput
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeManager$IngredientCollector
+ XXX.item.crafting.RecipeManager$IngredientExtractor
- XXX.item.crafting.RecipeManager$ServerDisplayInfo
+ XXX.item.crafting.RecipeMap
- XXX.item.crafting.RecipePropertySet
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.SelectableRecipe
- XXX.item.crafting.SelectableRecipe$SingleInputEntry
+ XXX.item.crafting.SelectableRecipe$SingleInputSet
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapedRecipePattern
+ XXX.item.crafting.ShapedRecipePattern$Data
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Factory
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleRecipeInput
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmeltingRecipe$1
+ XXX.item.crafting.SmithingRecipe
- XXX.item.crafting.SmithingRecipeInput
+ XXX.item.crafting.SmithingTransformRecipe
- XXX.item.crafting.SmithingTransformRecipe$Serializer
+ XXX.item.crafting.SmithingTrimRecipe
- XXX.item.crafting.SmithingTrimRecipe$Serializer
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.TippedArrowRecipe
- XXX.item.crafting.TransmuteRecipe
+ XXX.item.crafting.TransmuteRecipe$Serializer
- XXX.item.crafting.TransmuteResult
+ XXX.item.enchantment.ConditionalEffect
- XXX.item.enchantment.Enchantable
+ XXX.item.enchantment.EnchantedItemInUse
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$1
- XXX.item.enchantment.Enchantment$Builder
+ XXX.item.enchantment.Enchantment$Cost
- XXX.item.enchantment.Enchantment$EnchantmentDefinition
+ XXX.item.enchantment.EnchantmentEffectComponents
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.EnchantmentTarget
- XXX.item.enchantment.ItemEnchantments
+ XXX.item.enchantment.ItemEnchantments$Mutable
- XXX.item.enchantment.LevelBasedValue
+ XXX.item.enchantment.LevelBasedValue$Clamped
- XXX.item.enchantment.LevelBasedValue$Constant
+ XXX.item.enchantment.LevelBasedValue$Fraction
- XXX.item.enchantment.LevelBasedValue$LevelsSquared
+ XXX.item.enchantment.LevelBasedValue$Linear
- XXX.item.enchantment.LevelBasedValue$Lookup
+ XXX.item.enchantment.package-info
+ XXX.item.enchantment.Repairable
- XXX.item.enchantment.TargetedConditionalEffect
- XXX.item.equipment.AllowedEntitiesProvider
+ XXX.item.equipment.ArmorMaterial
- XXX.item.equipment.ArmorMaterials
+ XXX.item.equipment.ArmorType
- XXX.item.equipment.EquipmentAsset
+ XXX.item.equipment.EquipmentAssets
- XXX.item.equipment.Equippable
+ XXX.item.equipment.Equippable$Builder
- XXX.item.equipment.package-info
- XXX.item.trading.ItemCost
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
+ XXX.level.block.ChiseledBookShelfBlock$1
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.ColoredFallingBlock
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CopperBulbBlock
- XXX.level.block.CopperGolemStatueBlock
- XXX.level.block.SelectableSlotContainer$1
- XXX.level.block.ShortDryGrassBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SideChainPartBlock$EmptyNeighbor
- XXX.level.block.SideChainPartBlock$Neighbors
- XXX.level.block.WeatheringCopperChestBlock
+ XXX.level.block.WeatheringCopperDoorBlock
- XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringLightningRodBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
+ XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$DistancePerDirection
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BlockColumn
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.CarvingMask
+ XXX.level.chunk.CarvingMask$Mask
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkAccess$ChunkPathElement
- XXX.level.chunk.ChunkAccess$PackedTicks
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$1
- XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunk$PostLoadProcessor
+ XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- XXX.level.chunk.LevelChunk$UnsavedListener
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LevelChunkSection$1BlockCounter
+ XXX.level.chunk.LightChunk
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.MissingPaletteEntryException
+ XXX.level.chunk.package-info
+ XXX.level.chunk.Palette
- XXX.level.chunk.Palette$Factory
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$Configuration
- XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PalettedContainer$Data
- XXX.level.chunk.PalettedContainer$Strategy
+ XXX.level.chunk.PalettedContainer$Strategy$1
- XXX.level.chunk.PalettedContainer$Strategy$2
+ XXX.level.chunk.PalettedContainerRO
- XXX.level.chunk.PalettedContainerRO$PackedData
+ XXX.level.chunk.PalettedContainerRO$Unpacker
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.StructureAccess
+ XXX.level.chunk.UpgradeData
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.BuiltinDimensionTypes
+ XXX.level.dimension.DimensionDefaults
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.DimensionType$MonsterSettings
- XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.entity.ChunkEntities
- XXX.level.entity.ChunkStatusUpdateListener
+ XXX.level.entity.EntityAccess
- XXX.level.entity.EntityInLevelCallback
+ XXX.level.entity.EntityInLevelCallback$1
- XXX.level.entity.EntityLookup
+ XXX.level.entity.EntityPersistentStorage
- XXX.level.entity.EntitySection
+ XXX.level.entity.EntitySectionStorage
- XXX.level.entity.EntityTickList
+ XXX.level.entity.EntityTypeTest
- XXX.level.entity.EntityTypeTest$1
+ XXX.level.entity.EntityTypeTest$2
- XXX.level.entity.LevelCallback
+ XXX.level.entity.LevelEntityGetter
- XXX.level.entity.LevelEntityGetterAdapter
+ XXX.level.entity.package-info
+ XXX.level.entity.PersistentEntitySectionManager
- XXX.level.entity.PersistentEntitySectionManager$Callback
+ XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- XXX.level.entity.TransientEntitySectionManager
+ XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.entity.UniquelyIdentifyable
- XXX.level.entity.UUIDLookup
- XXX.level.entity.Visibility
- XXX.level.gameevent.BlockPositionSource
+ XXX.level.gameevent.BlockPositionSource$Type
- XXX.level.gameevent.DynamicGameEventListener
+ XXX.level.gameevent.EntityPositionSource
- XXX.level.gameevent.EntityPositionSource$Type
+ XXX.level.gameevent.EuclideanGameEventListenerRegistry
- XXX.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
+ XXX.level.gameevent.GameEvent
- XXX.level.gameevent.GameEvent$Context
+ XXX.level.gameevent.GameEvent$ListenerInfo
- XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
+ XXX.level.gameevent.GameEventListener$Provider
- XXX.level.gameevent.GameEventListenerRegistry
+ XXX.level.gameevent.GameEventListenerRegistry$1
- XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
+ XXX.level.gameevent.package-info
+ XXX.level.gameevent.PositionSource
- XXX.level.gameevent.PositionSourceType
- XXX.level.levelgen.Aquifer
+ XXX.level.levelgen.Aquifer$1
- XXX.level.levelgen.Aquifer$FluidPicker
+ XXX.level.levelgen.Aquifer$FluidStatus
- XXX.level.levelgen.Aquifer$NoiseBasedAquifer
+ XXX.level.levelgen.Beardifier
- XXX.level.levelgen.Beardifier$1
+ XXX.level.levelgen.Beardifier$Rigid
- XXX.level.levelgen.BelowZeroRetrogen
+ XXX.level.levelgen.BelowZeroRetrogen$1
- XXX.level.levelgen.BitRandomSource
+ XXX.level.levelgen.Column
- XXX.level.levelgen.Column$Line
+ XXX.level.levelgen.Column$Range
- XXX.level.levelgen.Column$Ray
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.Density
+ XXX.level.levelgen.DensityFunction
- XXX.level.levelgen.DensityFunction$ContextProvider
+ XXX.level.levelgen.DensityFunction$FunctionContext
- XXX.level.levelgen.DensityFunction$NoiseHolder
+ XXX.level.levelgen.DensityFunction$SimpleFunction
- XXX.level.levelgen.DensityFunction$SinglePointContext
+ XXX.level.levelgen.DensityFunction$Visitor
- XXX.level.levelgen.DensityFunctions
+ XXX.level.levelgen.DensityFunctions$Ap2
- XXX.level.levelgen.DensityFunctions$BeardifierMarker
+ XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
- XXX.level.levelgen.DensityFunctions$BlendAlpha
+ XXX.level.levelgen.DensityFunctions$BlendDensity
- XXX.level.levelgen.DensityFunctions$BlendOffset
+ XXX.level.levelgen.DensityFunctions$Clamp
- XXX.level.levelgen.DensityFunctions$Constant
+ XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
- XXX.level.levelgen.DensityFunctions$FindTopSurface
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.ChunkSkyLightSources
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$SectionState
- XXX.level.lighting.LayerLightSectionStorage$SectionType
- XXX.level.lighting.LeveledPriorityQueue
+ XXX.level.lighting.LeveledPriorityQueue$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEngine
+ XXX.level.lighting.LightEngine$QueueEntry
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightEngine$1
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.FlowingFluid$BlockStatePairKey
- XXX.level.material.FlowingFluid$SpreadContext
+ XXX.level.material.Fluid
+ XXX.level.material.Fluids
- XXX.level.material.FluidState
- XXX.level.material.FogType
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.MapColor
+ XXX.level.material.MapColor$Brightness
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.AmphibiousNodeEvaluator
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.Path$DebugData
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.PathfindingContext
+ XXX.level.pathfinder.PathType
- XXX.level.pathfinder.PathTypeCache
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.pathfinder.WalkNodeEvaluator$1
+ XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalShape
+ XXX.level.portal.TeleportTransition
- XXX.level.portal.TeleportTransition$PostTeleportTransition
- XXX.level.progress.ChunkLoadStatusView
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LevelLoadListener$1
- XXX.level.progress.LevelLoadProgressTracker
- XXX.level.progress.LoggingLevelLoadListener
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.redstone.CollectingNeighborUpdater
+ XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.DefaultRedstoneWireEvaluator
+ XXX.level.redstone.ExperimentalRedstoneUtils
- XXX.level.redstone.ExperimentalRedstoneWireEvaluator
+ XXX.level.redstone.InstantNeighborUpdater
- XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.Orientation
- XXX.level.redstone.Orientation$SideBias
+ XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.redstone.RedstoneWireEvaluator
- XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
+ XXX.level.saveddata.SavedData$Context
- XXX.level.saveddata.SavedDataType
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DataVersion
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.FileNameDateFormatter
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelDataAndDimensions
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelCandidates
+ XXX.level.storage.LevelStorageSource$LevelDirectory
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelSummary$CorruptedLevelSummary
- XXX.level.storage.LevelSummary$SymlinkLevelSummary
+ XXX.level.storage.LevelVersion
- XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.TagValueInput
+ XXX.level.storage.TagValueInput$CompoundListWrapper
- XXX.level.storage.TagValueInput$CompoundListWrapper$1
+ XXX.level.storage.TagValueInput$DecodeFromFieldFailedProblem
- XXX.level.storage.TagValueInput$DecodeFromListFailedProblem
+ XXX.level.storage.TagValueInput$DecodeFromMapFailedProblem
- XXX.level.storage.TagValueInput$ListWrapper
+ XXX.level.storage.TagValueInput$ListWrapper$1
- XXX.level.storage.TagValueInput$TypedListWrapper
+ XXX.level.storage.TagValueInput$TypedListWrapper$1
- XXX.level.storage.TagValueInput$UnexpectedListElementTypeProblem
+ XXX.level.storage.TagValueInput$UnexpectedNonNumberProblem
- XXX.level.storage.TagValueInput$UnexpectedTypeProblem
+ XXX.level.storage.TagValueOutput
- XXX.level.storage.TagValueOutput$EncodeToFieldFailedProblem
+ XXX.level.storage.TagValueOutput$EncodeToListFailedProblem
- XXX.level.storage.TagValueOutput$EncodeToMapFailedProblem
+ XXX.level.storage.TagValueOutput$ListWrapper
- XXX.level.storage.TagValueOutput$TypedListWrapper
+ XXX.level.storage.ValueInput
- XXX.level.storage.ValueInput$TypedInputList
+ XXX.level.storage.ValueInput$ValueInputList
- XXX.level.storage.ValueInputContextHelper
+ XXX.level.storage.ValueInputContextHelper$1
- XXX.level.storage.ValueInputContextHelper$2
+ XXX.level.storage.ValueInputContextHelper$3
- XXX.level.storage.ValueOutput
+ XXX.level.storage.ValueOutput$TypedOutputList
- XXX.level.storage.ValueOutput$ValueOutputList
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$Event
- XXX.level.validation.ContentValidationException
+ XXX.level.validation.DirectoryValidator
- XXX.level.validation.DirectoryValidator$1
+ XXX.level.validation.ForbiddenSymlinkInfo
+ XXX.level.validation.package-info
- XXX.level.validation.PathAllowList
+ XXX.level.validation.PathAllowList$ConfigEntry
- XXX.level.validation.PathAllowList$EntryType
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.NormalNoise$NoiseParameters
- XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
+ XXX.login.custom.CustomQueryAnswerPayload
- XXX.login.custom.CustomQueryPayload
+ XXX.login.custom.DiscardedQueryAnswerPayload
- XXX.login.custom.DiscardedQueryPayload
+ XXX.login.custom.package-info
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$1
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.NestedLootTable
+ XXX.loot.entries.NestedLootTable$1
- XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaType
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyComponentsFunction
+ XXX.loot.functions.CopyComponentsFunction$Builder
- XXX.loot.functions.CopyComponentsFunction$Source
+ XXX.loot.functions.CopyCustomDataFunction
- XXX.loot.functions.CopyCustomDataFunction$Builder
+ XXX.loot.functions.CopyCustomDataFunction$CopyOperation
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.EnchantedCountIncreaseFunction
+ XXX.loot.functions.EnchantedCountIncreaseFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FilteredFunction
- XXX.loot.functions.FunctionReference
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.ListOperation
- XXX.loot.functions.ListOperation$Append
+ XXX.loot.functions.ListOperation$Insert
- XXX.loot.functions.ListOperation$ReplaceAll
+ XXX.loot.functions.ListOperation$ReplaceSection
- XXX.loot.functions.ListOperation$StandAlone
+ XXX.loot.functions.ListOperation$Type
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.ModifyContainerContents
+ XXX.loot.functions.package-info
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBookCoverFunction
- XXX.loot.functions.SetComponentsFunction
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetCustomDataFunction
+ XXX.loot.functions.SetCustomModelDataFunction
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetFireworkExplosionFunction
+ XXX.loot.functions.SetFireworksFunction
- XXX.loot.functions.SetInstrumentFunction
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemFunction
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Target
- XXX.loot.functions.SetOminousBottleAmplifierFunction
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SetWritableBookPagesFunction
- XXX.loot.functions.SetWrittenBookPagesFunction
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.ToggleTooltips
- XXX.loot.packs.VanillaBlockInteractLoot
+ XXX.loot.packs.VanillaBlockLoot
- XXX.loot.packs.VanillaChargedCreeperExplosionLoot
- XXX.loot.packs.VanillaChestLoot
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AllOfCondition
+ XXX.loot.predicates.AllOfCondition$Builder
- XXX.loot.predicates.AnyOfCondition
+ XXX.loot.predicates.AnyOfCondition$Builder
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.CompositeLootItemCondition
- XXX.loot.predicates.CompositeLootItemCondition$Builder
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.EnchantmentActiveCheck
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceWithEnchantedBonusCondition
- XXX.loot.predicates.MatchTool
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.metadata.pack.PackFormat$1
- XXX.metadata.pack.PackFormat$IntermediaryFormatHolder
+ XXX.metadata.pack.PackMetadataSection
- XXX.metadata.pack.PackMetadataSection$1
- XXX.minecraft.locale.DeprecatedTranslationsInfo
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.Language$1
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CollectionTag$1
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.CompoundTag$2
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
+ XXX.minecraft.nbt.ListTag$2
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounterException
+ XXX.minecraft.nbt.NbtException
- XXX.minecraft.nbt.NbtFormatException
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
+ XXX.minecraft.nbt.NbtOps$GenericListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.PrimitiveTag
+ XXX.minecraft.nbt.ReportedNbtException
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtGrammar
- XXX.minecraft.nbt.SnbtGrammar$1
+ XXX.minecraft.nbt.SnbtGrammar$2
- XXX.minecraft.nbt.SnbtGrammar$3
+ XXX.minecraft.nbt.SnbtGrammar$4
- XXX.minecraft.nbt.SnbtGrammar$5
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$1
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$2
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$3
+ XXX.minecraft.nbt.SnbtGrammar$Base
- XXX.minecraft.nbt.SnbtGrammar$IntegerLiteral
+ XXX.minecraft.nbt.SnbtGrammar$IntegerSuffix
- XXX.minecraft.nbt.SnbtGrammar$Sign
+ XXX.minecraft.nbt.SnbtGrammar$Signed
- XXX.minecraft.nbt.SnbtGrammar$SignedPrefix
+ XXX.minecraft.nbt.SnbtGrammar$SimpleHexLiteralParseRule
- XXX.minecraft.nbt.SnbtGrammar$TypeSuffix
+ XXX.minecraft.nbt.SnbtOperations
- XXX.minecraft.nbt.SnbtOperations$1
+ XXX.minecraft.nbt.SnbtOperations$2
- XXX.minecraft.nbt.SnbtOperations$3
+ XXX.minecraft.nbt.SnbtOperations$BuiltinKey
- XXX.minecraft.nbt.SnbtOperations$BuiltinOperation
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor$EntryResult
- XXX.minecraft.nbt.StreamTagVisitor$ValueResult
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.StringTagVisitor
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagType$2
+ XXX.minecraft.nbt.TagType$StaticSize
- XXX.minecraft.nbt.TagType$VariableSize
+ XXX.minecraft.nbt.TagTypes
- XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.nbt.TextComponentTagVisitor
+ XXX.minecraft.network.BandwidthDebugMonitor
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.ClientboundPacketListener
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$3
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.DisconnectionDetails
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.HandlerNames
- XXX.minecraft.network.HashedPatchMap
+ XXX.minecraft.network.HashedPatchMap$HashGenerator
- XXX.minecraft.network.HashedStack
+ XXX.minecraft.network.HashedStack$1
- XXX.minecraft.network.HashedStack$ActualItem
+ XXX.minecraft.network.HiddenByteBuf
- XXX.minecraft.network.LocalFrameDecoder
+ XXX.minecraft.network.LocalFrameEncoder
- XXX.minecraft.network.MonitoredLocalFrameDecoder
- XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketBundlePacker
- XXX.minecraft.network.PacketBundleUnpacker
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.PacketSendListener
+ XXX.minecraft.network.ProtocolInfo
- XXX.minecraft.network.ProtocolInfo$Details
+ XXX.minecraft.network.ProtocolInfo$Details$PacketVisitor
- XXX.minecraft.network.ProtocolInfo$DetailsProvider
+ XXX.minecraft.network.ProtocolSwapHandler
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.RegistryFriendlyByteBuf
- XXX.minecraft.network.ServerboundPacketListener
+ XXX.minecraft.network.SkipPacketDecoderException
- XXX.minecraft.network.SkipPacketEncoderException
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.TickablePacketListener
+ XXX.minecraft.network.UnconfiguredPipelineHandler
- XXX.minecraft.network.UnconfiguredPipelineHandler$Inbound
+ XXX.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
- XXX.minecraft.network.UnconfiguredPipelineHandler$Outbound
+ XXX.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
- XXX.minecraft.network.Utf8String
+ XXX.minecraft.network.VarInt
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.network.VarLong
+ XXX.minecraft.obfuscate.DontObfuscate
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipeHelper
+ XXX.minecraft.recipebook.PlaceRecipeHelper$Output
- XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe$CraftingMenuAccess
+ XXX.minecraft.references.Blocks
- XXX.minecraft.references.Items
+ XXX.minecraft.references.package-info
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.DelegatingOps$DelegateListBuilder
- XXX.minecraft.resources.DelegatingOps$DelegateRecordBuilder
+ XXX.minecraft.resources.DependantName
- XXX.minecraft.resources.FileToIdConverter
+ XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryDataLoader
+ XXX.minecraft.resources.RegistryDataLoader$1
- XXX.minecraft.resources.RegistryDataLoader$Loader
+ XXX.minecraft.resources.RegistryDataLoader$LoadingFunction
- XXX.minecraft.resources.RegistryDataLoader$NetworkedRegistryData
+ XXX.minecraft.resources.RegistryDataLoader$RegistryData
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryOps$HolderLookupAdapter
- XXX.minecraft.resources.RegistryOps$RegistryInfo
+ XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceKey$InternKey
- XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
- XXX.minecraft.util.NullOps$NullListBuilder
+ XXX.minecraft.util.NullOps$NullMapBuilder
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PlaceholderLookupProvider
+ XXX.minecraft.util.PlaceholderLookupProvider$1
- XXX.minecraft.util.PlaceholderLookupProvider$2
+ XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$1
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProblemReporter$Collector$Entry
+ XXX.minecraft.util.ProblemReporter$Collector$ProblemTreeNode
- XXX.minecraft.util.ProblemReporter$ElementReferencePathElement
+ XXX.minecraft.util.ProblemReporter$FieldPathElement
- XXX.minecraft.util.ProblemReporter$IndexedFieldPathElement
+ XXX.minecraft.util.ProblemReporter$IndexedPathElement
- XXX.minecraft.util.ProblemReporter$PathElement
+ XXX.minecraft.util.ProblemReporter$Problem
- XXX.minecraft.util.ProblemReporter$RootElementPathElement
+ XXX.minecraft.util.ProblemReporter$RootFieldPathElement
- XXX.minecraft.util.ProblemReporter$ScopedCollector
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.RegistryContextSwapper
- XXX.minecraft.util.ResourceLocationPattern
+ XXX.minecraft.util.SegmentedAnglePrecision
- XXX.minecraft.util.SequencedPriorityIterator
+ XXX.minecraft.util.SignatureUpdater
- XXX.minecraft.util.SignatureUpdater$Output
+ XXX.minecraft.util.SignatureValidator
- XXX.minecraft.util.Signer
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SingleKeyCache
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$ArrayIterator
+ XXX.minecraft.util.SpawnUtil
- XXX.minecraft.util.SpawnUtil$Strategy
+ XXX.minecraft.util.StaticCache2D
- XXX.minecraft.util.StaticCache2D$Initializer
+ XXX.minecraft.util.StrictJsonParser
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TaskChainer
+ XXX.minecraft.util.TaskChainer$1
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TickThrottler
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.ToFloatFunction$1
+ XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.util.TriState
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.ZeroBitStorage
- XXX.minecraft.world.package-info
+ XXX.monster.breeze.Breeze
- XXX.monster.breeze.Breeze$1
+ XXX.monster.breeze.BreezeAi
- XXX.monster.breeze.BreezeAi$SlideToTargetSink
+ XXX.monster.breeze.BreezeUtil
- XXX.monster.breeze.LongJump
- XXX.monster.breeze.package-info
+ XXX.monster.breeze.Shoot
- XXX.monster.breeze.ShootWhenStuck
+ XXX.monster.breeze.Slide
+ XXX.monster.creaking.Creaking
- XXX.monster.creaking.Creaking$CreakingBodyRotationControl
+ XXX.monster.creaking.Creaking$CreakingJumpControl
- XXX.monster.creaking.Creaking$CreakingLookControl
+ XXX.monster.creaking.Creaking$CreakingMoveControl
- XXX.monster.creaking.Creaking$CreakingPathNavigation
+ XXX.monster.creaking.Creaking$HomeNodeEvaluator
- XXX.monster.creaking.CreakingAi
+ XXX.monster.creaking.CreakingAi$1
- XXX.monster.creaking.package-info
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.HoglinBase
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.AbstractPiglin
- XXX.monster.piglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.PiglinArmPose
- XXX.monster.piglin.PiglinBrute
+ XXX.monster.piglin.PiglinBruteAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
+ XXX.monster.piglin.StartAdmiringItemIfSeen
- XXX.monster.piglin.StartHuntingHoglin
+ XXX.monster.piglin.StopAdmiringIfItemTooFarAway
- XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ XXX.monster.warden.AngerLevel
- XXX.monster.warden.AngerManagement
+ XXX.monster.warden.AngerManagement$1
- XXX.monster.warden.AngerManagement$Sorter
- XXX.monster.warden.package-info
+ XXX.monster.warden.Warden
- XXX.monster.warden.Warden$1
+ XXX.monster.warden.Warden$1$1
- XXX.monster.warden.Warden$2
+ XXX.monster.warden.Warden$VibrationUser
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.CollectToTag$CompoundBuilder
- XXX.nbt.visitors.CollectToTag$ContainerBuilder
+ XXX.nbt.visitors.CollectToTag$ListBuilder
- XXX.nbt.visitors.CollectToTag$RootBuilder
+ XXX.nbt.visitors.FieldSelector
- XXX.nbt.visitors.FieldTree
- XXX.nbt.visitors.package-info
+ XXX.nbt.visitors.SkipAll
- XXX.nbt.visitors.SkipAll$1
+ XXX.nbt.visitors.SkipFields
+ XXX.network.chat.ChatDecorator
- XXX.network.chat.ChatType
+ XXX.network.chat.ChatType$Bound
- XXX.network.chat.ChatTypeDecoration
+ XXX.network.chat.ChatTypeDecoration$Parameter
- XXX.network.chat.ChatTypeDecoration$Parameter$Selector
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.ClickEvent$ChangePage
- XXX.network.chat.ClickEvent$CopyToClipboard
+ XXX.network.chat.ClickEvent$Custom
- XXX.network.chat.ClickEvent$OpenFile
+ XXX.network.chat.ClickEvent$OpenUrl
- XXX.network.chat.ClickEvent$RunCommand
+ XXX.network.chat.ClickEvent$ShowDialog
- XXX.network.chat.ClickEvent$SuggestCommand
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.ComponentContents
- XXX.network.chat.ComponentContents$Type
+ XXX.network.chat.ComponentSerialization
- XXX.network.chat.ComponentSerialization$1
+ XXX.network.chat.ComponentSerialization$FuzzyCodec
- XXX.network.chat.ComponentSerialization$StrictEither
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
+ XXX.network.chat.FilterMask$Type
- XXX.network.chat.FormattedText
+ XXX.network.chat.FormattedText$1
- XXX.network.chat.FormattedText$2
+ XXX.network.chat.FormattedText$3
- XXX.network.chat.FormattedText$4
+ XXX.network.chat.FormattedText$ContentConsumer
- XXX.network.chat.FormattedText$StyledContentConsumer
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ShowEntity
+ XXX.network.chat.HoverEvent$ShowItem
- XXX.network.chat.HoverEvent$ShowText
+ XXX.network.chat.LastSeenMessages
- XXX.network.chat.LastSeenMessages$Packed
+ XXX.network.chat.LastSeenMessages$Update
- XXX.network.chat.LastSeenMessagesTracker
+ XXX.network.chat.LastSeenMessagesTracker$Update
- XXX.network.chat.LastSeenMessagesValidator
+ XXX.network.chat.LastSeenMessagesValidator$ValidationException
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
+ XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$1
- XXX.network.chat.SignedMessageChain$DecodeException
+ XXX.network.chat.SignedMessageChain$Decoder
- XXX.network.chat.SignedMessageChain$Encoder
+ XXX.network.chat.SignedMessageLink
- XXX.network.chat.SignedMessageValidator
+ XXX.network.chat.SignedMessageValidator$KeyBased
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$1Collector
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.SubStringSource
+ XXX.network.chat.TextColor
- XXX.network.chat.ThrowingComponent
- XXX.network.codec.ByteBufCodecs
+ XXX.network.codec.ByteBufCodecs$1
- XXX.network.codec.ByteBufCodecs$10
+ XXX.network.codec.ByteBufCodecs$11
- XXX.network.codec.ByteBufCodecs$12
+ XXX.network.codec.ByteBufCodecs$13
- XXX.network.codec.ByteBufCodecs$14
+ XXX.network.codec.ByteBufCodecs$15
- XXX.network.codec.ByteBufCodecs$16
+ XXX.network.codec.ByteBufCodecs$17
- XXX.network.codec.ByteBufCodecs$18
+ XXX.network.codec.ByteBufCodecs$19
- XXX.network.codec.ByteBufCodecs$2
+ XXX.network.codec.ByteBufCodecs$20
- XXX.network.codec.ByteBufCodecs$21
+ XXX.network.codec.ByteBufCodecs$22
- XXX.network.codec.ByteBufCodecs$23
+ XXX.network.codec.ByteBufCodecs$24
- XXX.network.codec.ByteBufCodecs$25
+ XXX.network.codec.ByteBufCodecs$26
- XXX.network.codec.ByteBufCodecs$27
+ XXX.network.codec.ByteBufCodecs$28
- XXX.network.codec.ByteBufCodecs$29
+ XXX.network.codec.ByteBufCodecs$3
- XXX.network.codec.ByteBufCodecs$30
+ XXX.network.codec.ByteBufCodecs$31
- XXX.network.codec.ByteBufCodecs$32
+ XXX.network.codec.ByteBufCodecs$33
- XXX.network.codec.ByteBufCodecs$34
+ XXX.network.codec.ByteBufCodecs$35
- XXX.network.codec.ByteBufCodecs$36
+ XXX.network.codec.ByteBufCodecs$4
- XXX.network.codec.ByteBufCodecs$5
+ XXX.network.codec.ByteBufCodecs$6
- XXX.network.codec.ByteBufCodecs$7
+ XXX.network.codec.ByteBufCodecs$8
- XXX.network.codec.ByteBufCodecs$9
+ XXX.network.codec.IdDispatchCodec
- XXX.network.codec.IdDispatchCodec$Builder
+ XXX.network.codec.IdDispatchCodec$DontDecorateException
- XXX.network.codec.IdDispatchCodec$Entry
+ XXX.network.codec.package-info
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
+ XXX.network.codec.StreamCodec$14
- XXX.network.codec.StreamCodec$15
+ XXX.network.codec.StreamCodec$16
- XXX.network.codec.StreamCodec$17
+ XXX.network.codec.StreamCodec$2
- XXX.network.codec.StreamCodec$3
+ XXX.network.codec.StreamCodec$4
- XXX.network.codec.StreamCodec$5
+ XXX.network.codec.StreamCodec$6
- XXX.network.codec.StreamCodec$7
+ XXX.network.codec.StreamCodec$8
- XXX.network.codec.StreamCodec$9
+ XXX.network.codec.StreamCodec$CodecOperation
- XXX.network.codec.StreamDecoder
+ XXX.network.codec.StreamEncoder
- XXX.network.codec.StreamMemberEncoder
- XXX.network.config.PrepareSpawnTask
- XXX.network.config.PrepareSpawnTask$Ready
+ XXX.network.protocol.BundleDelimiterPacket
- XXX.network.protocol.BundlePacket
+ XXX.network.protocol.BundlerInfo
- XXX.network.protocol.BundlerInfo$1
+ XXX.network.protocol.BundlerInfo$1$1
- XXX.network.protocol.BundlerInfo$Bundler
+ XXX.network.protocol.CodecModifier
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketType
+ XXX.network.protocol.PacketUtils
- XXX.network.protocol.ProtocolCodecBuilder
+ XXX.network.protocol.ProtocolInfoBuilder
- XXX.network.protocol.ProtocolInfoBuilder$1
+ XXX.network.protocol.ProtocolInfoBuilder$2
- XXX.network.protocol.ProtocolInfoBuilder$3
+ XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
- XXX.network.protocol.ProtocolInfoBuilder$Implementation
+ XXX.network.protocol.SimpleUnboundProtocol
- XXX.network.protocol.UnboundProtocol
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.package-info
+ XXX.network.syncher.SyncedDataHolder
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$Builder
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.network.syncher.SynchedEntityData$DataValue
- XXX.packs.metadata.MetadataSectionType$WithValue
- XXX.packs.resources.PreparableReloadListener$SharedState
+ XXX.packs.resources.ResourceMetadata$Builder
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
- XXX.phys.shapes.MinecartCollisionContext
+ XXX.phys.shapes.MinecartCollisionContext$1
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
- XXX.protocol.common.ClientboundClearDialogPacket
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundCustomReportDetailsPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundServerLinksPacket
+ XXX.protocol.common.ClientboundShowDialogPacket
- XXX.protocol.common.ClientboundStoreCookiePacket
+ XXX.protocol.common.ClientboundTransferPacket
- XXX.protocol.common.ClientboundUpdateTagsPacket
+ XXX.protocol.common.ClientCommonPacketListener
+ XXX.protocol.common.CommonPacketTypes
- XXX.protocol.common.package-info
+ XXX.protocol.common.ServerboundClientInformationPacket
- XXX.protocol.common.ServerboundCustomClickActionPacket
+ XXX.protocol.common.ServerboundCustomPayloadPacket
- XXX.protocol.common.ServerboundKeepAlivePacket
+ XXX.protocol.common.ServerboundPongPacket
- XXX.protocol.common.ServerboundResourcePackPacket
+ XXX.protocol.common.ServerboundResourcePackPacket$Action
- XXX.protocol.common.ServerCommonPacketListener
- XXX.protocol.configuration.ClientboundFinishConfigurationPacket
+ XXX.protocol.configuration.ClientboundRegistryDataPacket
- XXX.protocol.configuration.ClientboundResetChatPacket
+ XXX.protocol.configuration.ClientboundSelectKnownPacks
- XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.configuration.ClientConfigurationPacketListener
+ XXX.protocol.configuration.ConfigurationPacketTypes
- XXX.protocol.configuration.ConfigurationProtocols
- XXX.protocol.configuration.package-info
- XXX.protocol.configuration.ServerboundFinishConfigurationPacket
+ XXX.protocol.configuration.ServerboundSelectKnownPacks
+ XXX.protocol.configuration.ServerConfigurationPacketListener
- XXX.protocol.cookie.ClientboundCookieRequestPacket
+ XXX.protocol.cookie.ClientCookiePacketListener
+ XXX.protocol.cookie.CookiePacketTypes
- XXX.protocol.cookie.package-info
+ XXX.protocol.cookie.ServerboundCookieResponsePacket
- XXX.protocol.cookie.ServerCookiePacketListener
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockChangedAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$AddOperation
+ XXX.protocol.game.ClientboundBossEventPacket$Handler
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundBossEventPacket$OperationType
- XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- XXX.protocol.game.ClientboundBundleDelimiterPacket
+ XXX.protocol.game.ClientboundBundlePacket
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChunkBatchFinishedPacket
- XXX.protocol.game.ClientboundChunkBatchStartPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeBuilder
+ XXX.protocol.game.ClientboundCommandsPacket$NodeInspector
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket$Entry
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ XXX.protocol.game.ClientboundDamageEventPacket
- XXX.protocol.game.ClientboundDebugSamplePacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundEntityPositionSyncPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundHurtAnimationPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
- XXX.protocol.game.ClientboundLevelChunkPacketData
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ XXX.protocol.game.ClientboundLevelChunkWithLightPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLightUpdatePacketData
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveMinecartPacket
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerChatPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
- XXX.protocol.game.ClientboundPlayerInfoRemovePacket
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerRotationPacket
- XXX.protocol.game.ClientboundProjectilePowerPacket
+ XXX.protocol.game.ClientboundRecipeBookAddPacket
- XXX.protocol.game.ClientboundRecipeBookAddPacket$Entry
+ XXX.protocol.game.ClientboundRecipeBookRemovePacket
- XXX.protocol.game.ClientboundRecipeBookSettingsPacket
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResetScorePacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundServerDataPacket
+ XXX.protocol.game.ClientboundSetActionBarTextPacket
- XXX.protocol.game.ClientboundSetBorderCenterPacket
+ XXX.protocol.game.ClientboundSetBorderLerpSizePacket
- XXX.protocol.game.ClientboundSetBorderSizePacket
+ XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
- XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetCursorItemPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetHeldSlotPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerInventoryPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetSimulationDistancePacket
- XXX.protocol.game.ClientboundSetSubtitleTextPacket
+ XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesAnimationPacket
- XXX.protocol.game.ClientboundSetTitleTextPacket
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStartConfigurationPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundSystemChatPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundTestInstanceBlockStatus
- XXX.protocol.game.ClientboundTickingStatePacket
+ XXX.protocol.game.ClientboundTickingStepPacket
- XXX.protocol.game.ClientboundTrackedWaypointPacket
+ XXX.protocol.game.ClientboundTrackedWaypointPacket$Operation
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.CommonPlayerSpawnInfo
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
- XXX.protocol.game.GameProtocols$1
+ XXX.protocol.game.GameProtocols$Context
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChangeGameModePacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatCommandSignedPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundChunkBatchReceivedPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientTickEndPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundContainerSlotStateChangedPacket
+ XXX.protocol.game.ServerboundDebugSampleSubscriptionPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQueryPacket
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemFromBlockPacket
+ XXX.protocol.game.ServerboundPickItemFromEntityPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPlayerLoadedPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectBundleItemPacket
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSetTestBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundTestInstanceBlockActionPacket
+ XXX.protocol.game.ServerboundTestInstanceBlockActionPacket$Action
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.HandshakePacketTypes
+ XXX.protocol.handshake.HandshakeProtocols
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientboundLoginFinishedPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.LoginPacketTypes
+ XXX.protocol.login.LoginProtocols
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryAnswerPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerboundLoginAcknowledgedPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.ping.ClientboundPongResponsePacket
- XXX.protocol.ping.ClientPongPacketListener
+ XXX.protocol.ping.package-info
- XXX.protocol.ping.PingPacketTypes
- XXX.protocol.ping.ServerboundPingRequestPacket
+ XXX.protocol.ping.ServerPingPacketListener
+ XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
- XXX.protocol.status.StatusPacketTypes
+ XXX.protocol.status.StatusProtocols
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.ConstantValue
- XXX.providers.number.EnchantmentLevelProvider
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.StorageValue
- XXX.providers.number.UniformGenerator
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.providers.score.LootScoreProviderType
+ XXX.providers.score.package-info
+ XXX.providers.score.ScoreboardNameProvider
- XXX.providers.score.ScoreboardNameProviders
+ XXX.rule.blockentity.AppendLoot
- XXX.rule.blockentity.AppendStatic
+ XXX.rule.blockentity.Clear
+ XXX.rule.blockentity.package-info
- XXX.rule.blockentity.Passthrough
+ XXX.rule.blockentity.RuleBlockEntityModifier
- XXX.rule.blockentity.RuleBlockEntityModifierType
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecorationType
+ XXX.saveddata.maps.MapDecorationTypes
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapId
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkResult
- XXX.server.level.ChunkResult$Fail
+ XXX.server.level.ChunkResult$Success
- XXX.server.level.ChunkTaskDispatcher
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueue$TasksForChunk
+ XXX.server.level.ChunkTracker
- XXX.server.level.ChunkTrackingView
+ XXX.server.level.ChunkTrackingView$1
- XXX.server.level.ChunkTrackingView$Positioned
+ XXX.server.level.ClientInformation
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.GeneratingChunkMap
+ XXX.server.level.GenerationChunkHolder
- XXX.server.level.LoadingChunkTracker
+ XXX.server.level.package-info
+ XXX.server.level.ParticleStatus
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerEntityGetter
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$1
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$1$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$3
- XXX.server.level.ServerPlayer$RespawnConfig
+ XXX.server.level.ServerPlayer$RespawnPosAngle
- XXX.server.level.ServerPlayer$SavedPosition
+ XXX.server.level.TicketType$TicketUse
- XXX.server.level.WorldGenRegion
- XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.players.CachedUserNameToIdResolver
+ XXX.server.players.GameProfileCache
- XXX.server.players.NameAndId
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.state.properties.package-info
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.TestBlockMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ContainerComponentManipulator
+ XXX.storage.loot.ContainerComponentManipulators
- XXX.storage.loot.ContainerComponentManipulators$1
+ XXX.storage.loot.ContainerComponentManipulators$2
- XXX.storage.loot.ContainerComponentManipulators$3
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootDataType
- XXX.storage.loot.LootDataType$Validator
+ XXX.storage.loot.LootParams
- XXX.storage.loot.LootParams$Builder
+ XXX.storage.loot.LootParams$DynamicDrop
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.package-info
- XXX.storage.loot.ValidationContext
+ XXX.storage.loot.ValidationContext$MissingReferenceProblem
- XXX.storage.loot.ValidationContext$ParametersNotProvidedProblem
+ XXX.storage.loot.ValidationContext$RecursiveReferenceProblem
- XXX.storage.loot.ValidationContext$ReferenceNotAllowedProblem
- XXX.structure.structures.JungleTemplePiece
+ XXX.structure.structures.JungleTemplePiece$MossStoneSelector
- XXX.structure.structures.JungleTempleStructure
+ XXX.structure.structures.MineshaftPieces
- XXX.structure.structures.MineshaftPieces$1
+ XXX.structure.structures.MineshaftPieces$MineShaftCorridor
- XXX.structure.structures.MineshaftPieces$MineShaftCrossing
+ XXX.structure.structures.MineshaftPieces$MineShaftPiece
- XXX.structure.structures.MineshaftPieces$MineShaftRoom
+ XXX.structure.structures.MineshaftPieces$MineShaftStairs
- XXX.structure.structures.MineshaftStructure
+ XXX.structure.structures.MineshaftStructure$Type
- XXX.structure.structures.NetherFortressPieces
+ XXX.structure.structures.NetherFortressPieces$1
- XXX.structure.structures.NetherFortressPieces$BridgeCrossing
+ XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
- XXX.structure.structures.NetherFortressPieces$BridgeStraight
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ XXX.structure.structures.NetherFortressPieces$CastleEntrance
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
+ XXX.structure.structures.NetherFortressPieces$MonsterThrone
- XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
+ XXX.structure.structures.NetherFortressPieces$PieceWeight
- XXX.structure.structures.NetherFortressPieces$RoomCrossing
+ XXX.structure.structures.NetherFortressPieces$StairsRoom
- XXX.structure.structures.NetherFortressPieces$StartPiece
+ XXX.structure.structures.NetherFortressStructure
- XXX.structure.structures.NetherFossilPieces
+ XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
- XXX.structure.structures.NetherFossilStructure
+ XXX.structure.structures.OceanMonumentPieces
- XXX.structure.structures.OceanMonumentPieces$1
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
+ XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.structure.structures.OceanMonumentPieces$RoomDefinition
+ XXX.structure.structures.OceanMonumentStructure
- XXX.structure.structures.OceanRuinPieces
+ XXX.structure.structures.OceanRuinPieces$1
- XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
+ XXX.structure.structures.OceanRuinStructure
- XXX.structure.structures.OceanRuinStructure$Type
+ XXX.structure.structures.package-info
+ XXX.structure.structures.RuinedPortalPiece
- XXX.structure.structures.RuinedPortalPiece$Properties
+ XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
- XXX.structure.structures.RuinedPortalStructure
+ XXX.structure.structures.RuinedPortalStructure$Setup
- XXX.structure.structures.ShipwreckPieces
+ XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
- XXX.structure.structures.ShipwreckStructure
+ XXX.structure.structures.StrongholdPieces
- XXX.structure.structures.StrongholdPieces$1
+ XXX.structure.structures.StrongholdPieces$2
- XXX.structure.structures.StrongholdPieces$3
+ XXX.structure.structures.StrongholdPieces$ChestCorridor
- XXX.structure.structures.StrongholdPieces$FillerCorridor
+ XXX.structure.structures.StrongholdPieces$FiveCrossing
- XXX.structure.structures.StrongholdPieces$LeftTurn
+ XXX.structure.structures.StrongholdPieces$Library
- XXX.structure.structures.StrongholdPieces$PieceWeight
+ XXX.structure.structures.StrongholdPieces$PortalRoom
- XXX.structure.structures.StrongholdPieces$PrisonHall
+ XXX.structure.structures.StrongholdPieces$RightTurn
- XXX.structure.structures.StrongholdPieces$RoomCrossing
+ XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
- XXX.structure.structures.StrongholdPieces$StairsDown
+ XXX.structure.structures.StrongholdPieces$StartPiece
- XXX.structure.structures.StrongholdPieces$Straight
+ XXX.structure.structures.StrongholdPieces$StraightStairsDown
- XXX.structure.structures.StrongholdPieces$StrongholdPiece
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.structure.structures.StrongholdPieces$Turn
+ XXX.structure.structures.StrongholdStructure
- XXX.structure.structures.SwampHutPiece
+ XXX.structure.structures.SwampHutStructure
- XXX.structure.structures.WoodlandMansionPieces
+ XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$MansionGrid
- XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.structure.structures.WoodlandMansionPieces$PlacementData
- XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
- XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.structure.structures.WoodlandMansionStructure
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.CappedProcessor
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LavaSubmergedBlockProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.LiquidSettings
- XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.ProtectedBlockProcessor
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$JigsawBlockInfo
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.StructureTemplateManager
+ XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- XXX.structure.templatesystem.StructureTemplateManager$Source
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.context.ContextKey
- XXX.util.context.ContextKeySet
+ XXX.util.context.ContextKeySet$Builder
- XXX.util.context.ContextMap
+ XXX.util.context.ContextMap$Builder
- XXX.util.context.package-info
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
- XXX.util.datafix.DataFixTypes$1
- XXX.util.datafix.ExtraDataFixUtils
+ XXX.util.datafix.LegacyComponentDataFixUtils
- XXX.util.datafix.package-info
- XXX.util.datafix.PackedBitStorage
- XXX.world.entity.ContainerUser
+ XXX.world.entity.ConversionParams
- XXX.world.entity.ConversionParams$AfterConversion
+ XXX.world.entity.ConversionType
- XXX.world.entity.ConversionType$1
+ XXX.world.entity.ConversionType$2
- XXX.world.entity.Crackiness
+ XXX.world.entity.Crackiness$Level
- XXX.world.entity.Display
+ XXX.world.entity.Display$BillboardConstraints
- XXX.world.entity.Display$BlockDisplay
+ XXX.world.entity.Display$BlockDisplay$BlockRenderState
- XXX.world.entity.Display$ColorInterpolator
+ XXX.world.entity.Display$FloatInterpolator
- XXX.world.entity.Display$GenericInterpolator
+ XXX.world.entity.Display$IntInterpolator
- XXX.world.entity.Display$ItemDisplay
+ XXX.world.entity.Display$ItemDisplay$ItemRenderState
- XXX.world.entity.Display$LinearFloatInterpolator
+ XXX.world.entity.Display$LinearIntInterpolator
- XXX.world.entity.Display$RenderState
+ XXX.world.entity.Display$TextDisplay
- XXX.world.entity.Display$TextDisplay$Align
+ XXX.world.entity.Display$TextDisplay$CachedInfo
- XXX.world.entity.Display$TextDisplay$CachedLine
+ XXX.world.entity.Display$TextDisplay$LineSplitter
- XXX.world.entity.Display$TextDisplay$TextRenderState
+ XXX.world.entity.Display$TransformationInterpolator
- XXX.world.entity.DropChances
+ XXX.world.entity.ElytraAnimationState
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$EntityPathElement
+ XXX.world.entity.Entity$MoveFunction
- XXX.world.entity.Entity$Movement
+ XXX.world.entity.Entity$MovementEmission
- XXX.world.entity.Entity$RemovalReason
+ XXX.world.entity.EntityAttachment
- XXX.world.entity.EntityAttachment$Fallback
+ XXX.world.entity.EntityAttachments
- XXX.world.entity.EntityAttachments$Builder
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEquipment
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntityReference
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySpawnReason
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.EquipmentSlotGroup
+ XXX.world.entity.EquipmentSlotGroup$1
- XXX.world.entity.EquipmentTable
+ XXX.world.entity.EquipmentUser
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HasCustomInventoryScreen
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.InsideBlockEffectApplier
+ XXX.world.entity.InsideBlockEffectApplier$1
- XXX.world.entity.InsideBlockEffectApplier$StepBasedCollector
+ XXX.world.entity.InsideBlockEffectType
- XXX.world.entity.Interaction
+ XXX.world.entity.Interaction$PlayerAction
- XXX.world.entity.InterpolationHandler
+ XXX.world.entity.InterpolationHandler$InterpolationData
- XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemOwner$CustomOwner
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.Leashable
+ XXX.world.entity.Leashable$LeashData
- XXX.world.entity.Leashable$Wrench
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.Mob$2
+ XXX.world.entity.MobCategory
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OminousItemSpawner
+ XXX.world.entity.OwnableEntity
+ XXX.world.entity.package-info
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.PortalProcessor
- XXX.world.entity.Pose
+ XXX.world.entity.PositionMoveRotation
- XXX.world.entity.Relative
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SlotAccess$4
- XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacementType
- XXX.world.entity.SpawnPlacementTypes
+ XXX.world.entity.SpawnPlacementTypes$1
+ XXX.world.entity.TamableAnimal
- XXX.world.entity.TamableAnimal$TamableAnimalPanicGoal
+ XXX.world.entity.Targeting
- XXX.world.entity.TraceableEntity
+ XXX.world.entity.WalkAnimationState
- XXX.world.flag.FeatureElement
+ XXX.world.flag.FeatureFlag
- XXX.world.flag.FeatureFlagRegistry
+ XXX.world.flag.FeatureFlagRegistry$Builder
- XXX.world.flag.FeatureFlags
- XXX.world.flag.FeatureFlagSet
+ XXX.world.flag.FeatureFlagUniverse
+ XXX.world.flag.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$Builder
- XXX.world.food.Foods
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractContainerMenu$1
- XXX.world.inventory.AbstractCraftingMenu
+ XXX.world.inventory.AbstractCraftingMenu$1
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AbstractFurnaceMenu$1
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.ArmorSlot
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$FuelSlot
- XXX.world.inventory.BrewingStandMenu$IngredientsSlot
+ XXX.world.inventory.BrewingStandMenu$PotionSlot
- XXX.world.inventory.CartographyTableMenu
+ XXX.world.inventory.CartographyTableMenu$1
- XXX.world.inventory.CartographyTableMenu$2
+ XXX.world.inventory.CartographyTableMenu$3
- XXX.world.inventory.CartographyTableMenu$4
+ XXX.world.inventory.CartographyTableMenu$5
- XXX.world.inventory.ChestMenu
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.ContainerSynchronizer
+ XXX.world.inventory.CrafterMenu
- XXX.world.inventory.CrafterSlot
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DispenserMenu
- XXX.world.inventory.EnchantmentMenu
+ XXX.world.inventory.EnchantmentMenu$1
- XXX.world.inventory.EnchantmentMenu$2
+ XXX.world.inventory.EnchantmentMenu$3
- XXX.world.inventory.FurnaceFuelSlot
+ XXX.world.inventory.FurnaceMenu
- XXX.world.inventory.FurnaceResultSlot
+ XXX.world.inventory.GrindstoneMenu
- XXX.world.inventory.GrindstoneMenu$1
+ XXX.world.inventory.GrindstoneMenu$2
- XXX.world.inventory.GrindstoneMenu$3
+ XXX.world.inventory.GrindstoneMenu$4
- XXX.world.inventory.HopperMenu
+ XXX.world.inventory.HorseInventoryMenu
- XXX.world.inventory.HorseInventoryMenu$1
+ XXX.world.inventory.HorseInventoryMenu$2
- XXX.world.inventory.InventoryMenu
+ XXX.world.inventory.InventoryMenu$1
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.ItemCombinerMenu$3
- XXX.world.inventory.ItemCombinerMenu$4
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
- XXX.world.inventory.LecternMenu
+ XXX.world.inventory.LecternMenu$1
- XXX.world.inventory.LoomMenu
+ XXX.world.inventory.LoomMenu$1
- XXX.world.inventory.LoomMenu$2
+ XXX.world.inventory.LoomMenu$3
- XXX.world.inventory.LoomMenu$4
+ XXX.world.inventory.LoomMenu$5
- XXX.world.inventory.LoomMenu$6
+ XXX.world.inventory.MenuConstructor
- XXX.world.inventory.MenuType
+ XXX.world.inventory.MenuType$MenuSupplier
- XXX.world.inventory.MerchantContainer
+ XXX.world.inventory.MerchantMenu
- XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.NonInteractiveResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookMenu$PostPlaceAction
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeCraftingHolder
+ XXX.world.inventory.RemoteSlot
- XXX.world.inventory.RemoteSlot$1
+ XXX.world.inventory.RemoteSlot$Synchronized
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SlotRange
+ XXX.world.inventory.SlotRange$1
- XXX.world.inventory.SlotRanges
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
+ XXX.world.inventory.TransientCraftingContainer
- XXX.world.item.AdventureModePredicate
+ XXX.world.item.AirItem
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BoneMealItem$1
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.BundleItem$1
+ XXX.world.item.CompassItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$Builder
- XXX.world.item.CreativeModeTab$DisplayItemsGenerator
+ XXX.world.item.CreativeModeTab$ItemDisplayBuilder
- XXX.world.item.CreativeModeTab$ItemDisplayParameters
+ XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTab$Row
+ XXX.world.item.CreativeModeTab$TabVisibility
- XXX.world.item.CreativeModeTab$Type
+ XXX.world.item.CreativeModeTabs
- XXX.world.item.CrossbowItem
+ XXX.world.item.CrossbowItem$ChargeType
- XXX.world.item.CrossbowItem$ChargingSounds
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.EitherHolder
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.InkSacItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$Properties
+ XXX.world.item.Item$TooltipContext
- XXX.world.item.Item$TooltipContext$1
+ XXX.world.item.Item$TooltipContext$2
- XXX.world.item.Item$TooltipContext$3
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStack$4
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUseAnimation
+ XXX.world.item.ItemUtils
+ XXX.world.item.JukeboxPlayable
- XXX.world.item.JukeboxSong
+ XXX.world.item.JukeboxSongPlayer
- XXX.world.item.JukeboxSongPlayer$OnSongChanged
+ XXX.world.item.JukeboxSongs
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MaceItem
- XXX.world.item.MapItem
+ XXX.world.item.MapItem$1
- XXX.world.item.MinecartItem
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
+ XXX.world.item.package-info
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileItem
+ XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$DispenseConfig$Builder
+ XXX.world.item.ProjectileItem$PositionFunction
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignApplicator
- XXX.world.item.SignItem
+ XXX.world.item.SmithingTemplateItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.TippedArrowItem
+ XXX.world.item.ToolMaterial
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.WindChargeItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockCollisions
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.BlockGetter$BlockStepVisitor
- XXX.world.level.ChunkPos
+ XXX.world.level.ChunkPos$1
- XXX.world.level.ChunkPos$2
+ XXX.world.level.ClipBlockStateContext
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.ColorMapColorUtil
- XXX.world.level.ColorResolver
+ XXX.world.level.CommonLevelAccessor
- XXX.world.level.CustomSpawner
+ XXX.world.level.DataPackConfig
- XXX.world.level.DryFoliageColor
+ XXX.world.level.EmptyBlockAndTintGetter
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EntityBasedExplosionDamageCalculator
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.ExplosionDamageCalculator
- XXX.world.level.FoliageColor
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$BooleanValue
+ XXX.world.level.GameRules$Category
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameRules$VisitorCaller
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.Level$1
+ XXX.world.level.Level$ExplosionInteraction
- XXX.world.level.LevelAccessor
+ XXX.world.level.LevelHeightAccessor
- XXX.world.level.LevelHeightAccessor$1
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelTimeAccess
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.LocalMobCapCalculator
+ XXX.world.level.LocalMobCapCalculator$MobCounts
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
+ XXX.world.level.package-info
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ScheduledTickAccess
- XXX.world.level.ServerExplosion
+ XXX.world.level.ServerExplosion$StackCollector
- XXX.world.level.ServerLevelAccessor
+ XXX.world.level.SignalGetter
- XXX.world.level.SimpleExplosionDamageCalculator
+ XXX.world.level.SpawnData
- XXX.world.level.SpawnData$CustomSpawnRules
+ XXX.world.level.Spawner
- XXX.world.level.StructureManager
+ XXX.world.level.TicketStorage
- XXX.world.level.TicketStorage$ChunkUpdated
+ XXX.world.phys.AABB
- XXX.world.phys.AABB$Builder
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.phys.Vec3$1
- XXX.world.scores.DisplaySlot
+ XXX.world.scores.DisplaySlot$1
- XXX.world.scores.Objective
+ XXX.world.scores.Objective$Packed
- XXX.world.scores.package-info
- XXX.world.scores.PlayerScoreEntry
+ XXX.world.scores.PlayerScores
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.PlayerTeam$Packed
- XXX.world.scores.ReadOnlyScoreInfo
+ XXX.world.scores.Score
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.Scoreboard$PackedScore
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.ScoreboardSaveData$Packed
+ XXX.world.scores.ScoreHolder
- XXX.world.scores.ScoreHolder$1
+ XXX.world.scores.ScoreHolder$2
- XXX.world.scores.ScoreHolder$3
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
+ XXX.world.waypoints.TrackedWaypoint
- XXX.world.waypoints.TrackedWaypoint$AzimuthWaypoint
+ XXX.world.waypoints.TrackedWaypoint$Camera
- XXX.world.waypoints.TrackedWaypoint$ChunkWaypoint
+ XXX.world.waypoints.TrackedWaypoint$EmptyWaypoint
- XXX.world.waypoints.TrackedWaypoint$PitchDirection
+ XXX.world.waypoints.TrackedWaypoint$Projector
- XXX.world.waypoints.TrackedWaypoint$Type
+ XXX.world.waypoints.TrackedWaypoint$Vec3iWaypoint
- XXX.world.waypoints.TrackedWaypointManager
+ XXX.world.waypoints.Waypoint
- XXX.world.waypoints.Waypoint$Icon
+ XXX.world.waypoints.WaypointManager
- XXX.world.waypoints.WaypointStyleAsset
+ XXX.world.waypoints.WaypointStyleAssets
- XXX.world.waypoints.WaypointTransmitter
+ XXX.world.waypoints.WaypointTransmitter$BlockConnection
- XXX.world.waypoints.WaypointTransmitter$ChunkConnection
+ XXX.world.waypoints.WaypointTransmitter$Connection
- XXX.world.waypoints.WaypointTransmitter$EntityAzimuthConnection
+ XXX.world.waypoints.WaypointTransmitter$EntityBlockConnection
- XXX.world.waypoints.WaypointTransmitter$EntityChunkConnection
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.DetectedVersion +2M -1M
```
```
net.minecraft.SharedConstants +4P -3P
```
```
XXX.minecraft.core.HolderGetter +2M
```
```
XXX.minecraft.core.Registry -2M
```
```
XXX.core.dispenser.ShearsDispenseItemBehavior +1M -1M
```
```
XXX.gametest.framework.GameTestRunner +4M -3M | +1P
```
```
XXX.gametest.framework.GameTestRunner$Builder +2M -1M | +1P
```
```
XXX.minecraft.server.ServerFunctionLibrary +1M -1M
```
```
XXX.minecraft.server.Services +2M -2M | +1P -1P
```
```
XXX.server.commands.BanPlayerCommands +1M -1M
```
```
XXX.server.commands.OpCommand +1M -1M
```
```
XXX.server.commands.WhitelistCommand +12M -13M
```
```
XXX.server.dedicated.DedicatedPlayerList +4M -4M
```
```
XXX.server.network.ConfigurationTask +1M
```
```
XXX.server.packs.OverlayMetadataSection +5M -3M | +2P -2P
```
```
XXX.packs.resources.PreparableReloadListener +1M | +1P -1P
```
```
XXX.packs.resources.ProfiledReloadInstance +1M -1M
```
```
XXX.packs.resources.ResourceManagerReloadListener +1M -1M
```
```
XXX.packs.resources.SimplePreparableReloadListener +1M -1M
```
```
XXX.server.players.UserWhiteList +2M -2M
```
```
XXX.minecraft.tags.BlockTags +6P
```
```
XXX.minecraft.util.NullOps +2M -11M | +1P
```
```
XXX.util.thread.BlockableEventLoop +1M
```
```
XXX.minecraft.world.Container +3M -2M
```
```
XXX.entity.animal.Animal -1M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +3M -2M | -1P
```
```
XXX.level.block.Blocks +26M -6M | +35P
```
```
XXX.level.block.BrewingStandBlock +1M -1M
```
```
XXX.level.block.CrafterBlock +1M -1M
```
```
XXX.level.block.DetectorRailBlock +1M -1M
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.EndPortalFrameBlock +1M -1M
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.JukeboxBlock +1M -1M
```
```
XXX.level.block.LayeredCauldronBlock +1M -1M
```
```
XXX.level.block.PumpkinBlock +1M
```
```
XXX.level.block.SculkSensorBlock +1M -1M
```
```
XXX.level.block.SoundType +2P
```
```
XXX.level.block.WeatheringCopper$WeatherState +2M | +2P
```
```
XXX.block.entity.EnderChestBlockEntity +2M -2M
```
```
XXX.block.state.BlockBehaviour +2M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M -1M
```
```
XXX.level.levelgen.NoiseChunk$FlatCache +2P -1P
```
```
XXX.level.levelgen.NoiseRouter +1M -1M | +1P -1P
```
```
XXX.levelgen.blending.Blender +1M
```
```
XXX.levelgen.structure.BoundingBox +1M
```

</details>
<details>
<summary>
net.minecraft.DetectedVersion
</summary>

```diff
- WorldVersion createBuiltIn(String,String,boolean)
- WorldVersion createBuiltIn(String,String)
+ WorldVersion createFromConstants()
```

</details>
<details>
<summary>
net.minecraft.core.HolderGetter
</summary>

```diff
- Optional getRandomElementOf(TagKey,RandomSource)
- Optional lambda$getRandomElementOf$2(RandomSource,HolderSet$Named)
```

</details>
<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ Optional getRandomElementOf(TagKey,RandomSource)
+ Optional lambda$getRandomElementOf$9(RandomSource,HolderSet$Named)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.ShearsDispenseItemBehavior
</summary>

```diff
+ boolean tryShearBeehive(ServerLevel,BlockPos)
- boolean tryShearBeehive(ServerLevel,ItemStack,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestRunner
</summary>

```diff
+ String lambda$runScheduledRerunTests$4(GameTestInfo)
- String lambda$runScheduledRerunTests$5(GameTestInfo)
- void <init>(GameTestRunner$GameTestBatcher,Collection,ServerLevel,GameTestTicker,GameTestRunner$StructureSpawner,GameTestRunner$StructureSpawner,boolean,boolean)
+ void <init>(GameTestRunner$GameTestBatcher,Collection,ServerLevel,GameTestTicker,GameTestRunner$StructureSpawner,GameTestRunner$StructureSpawner,boolean)
+ void lambda$runBatch$3(GameTestBatch,GameTestBatchListener)
- void lambda$runBatch$3(GameTestInfo)
- void lambda$runBatch$4(GameTestBatch,GameTestBatchListener)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestRunner$Builder
</summary>

```diff
- GameTestRunner$Builder clearBetweenBatches()
- GameTestRunner$Builder haltOnError()
+ GameTestRunner$Builder haltOnError(boolean)
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionLibrary
</summary>

```diff
+ CompletableFuture reload(PreparableReloadListener$PreparationBarrier,ResourceManager,Executor,Executor)
- CompletableFuture reload(PreparableReloadListener$SharedState,Executor,PreparableReloadListener$PreparationBarrier,Executor)
```

</details>
<details>
<summary>
net.minecraft.server.Services
</summary>

```diff
+ GameProfileCache profileCache()
- UserNameToIdResolver nameToIdCache()
+ void <init>(MinecraftSessionService,ServicesKeySet,GameProfileRepository,GameProfileCache)
- void <init>(MinecraftSessionService,ServicesKeySet,GameProfileRepository,UserNameToIdResolver)
```

</details>
<details>
<summary>
net.minecraft.server.commands.BanPlayerCommands
</summary>

```diff
+ Component lambda$banPlayers$2(GameProfile,UserBanListEntry)
- Component lambda$banPlayers$2(NameAndId,UserBanListEntry)
```

</details>
<details>
<summary>
net.minecraft.server.commands.OpCommand
</summary>

```diff
+ Component lambda$opPlayers$4(GameProfile)
- Component lambda$opPlayers$4(NameAndId)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WhitelistCommand
</summary>

```diff
- boolean lambda$register$3(PlayerList,NameAndId)
+ boolean lambda$register$3(PlayerList,ServerPlayer)
- CompletableFuture lambda$register$4(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$5(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$register$6(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$7(CommandContext,SuggestionsBuilder)
- Component lambda$addPlayers$10(NameAndId)
+ Component lambda$addPlayers$11(GameProfile)
- Component lambda$disableWhitelist$13()
+ Component lambda$disableWhitelist$14()
- Component lambda$enableWhitelist$12()
+ Component lambda$enableWhitelist$13()
+ Component lambda$reload$10()
- Component lambda$reload$9()
- Component lambda$removePlayers$11(NameAndId)
+ Component lambda$removePlayers$12(GameProfile)
- Component lambda$showList$14()
+ Component lambda$showList$15()
- Component lambda$showList$15(String[])
+ Component lambda$showList$16(String[])
- int lambda$register$5(CommandContext)
+ int lambda$register$6(CommandContext)
- int lambda$register$7(CommandContext)
+ int lambda$register$9(CommandContext)
+ String lambda$register$4(ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedPlayerList
</summary>

```diff
+ boolean canBypassPlayerLimit(GameProfile)
- boolean canBypassPlayerLimit(NameAndId)
+ boolean isWhiteListed(GameProfile)
- boolean isWhiteListed(NameAndId)
+ void deop(GameProfile)
- void deop(NameAndId)
+ void op(GameProfile)
- void op(NameAndId)
```

</details>
<details>
<summary>
net.minecraft.server.network.ConfigurationTask
</summary>

```diff
- boolean tick()
```

</details>
<details>
<summary>
net.minecraft.server.packs.OverlayMetadataSection
</summary>

```diff
- App lambda$codecForPackType$1(PackType,RecordCodecBuilder$Instance)
+ App lambda$static$1(RecordCodecBuilder$Instance)
+ boolean lambda$overlaysForVersion$2(int,OverlayMetadataSection$OverlayEntry)
- boolean lambda$overlaysForVersion$2(PackFormat,OverlayMetadataSection$OverlayEntry)
- Codec codecForPackType(PackType)
+ List overlaysForVersion(int)
- List overlaysForVersion(PackFormat)
- MetadataSectionType forPackType(PackType)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.PreparableReloadListener
</summary>

```diff
- void prepareSharedState(PreparableReloadListener$SharedState)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ProfiledReloadInstance
</summary>

```diff
+ CompletableFuture lambda$of$1(Executor,PreparableReloadListener$PreparationBarrier,ResourceManager,PreparableReloadListener,Executor,Executor)
- CompletableFuture lambda$of$1(Executor,PreparableReloadListener$SharedState,PreparableReloadListener$PreparationBarrier,PreparableReloadListener,Executor,Executor)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceManagerReloadListener
</summary>

```diff
+ CompletableFuture reload(PreparableReloadListener$PreparationBarrier,ResourceManager,Executor,Executor)
- CompletableFuture reload(PreparableReloadListener$SharedState,Executor,PreparableReloadListener$PreparationBarrier,Executor)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.SimplePreparableReloadListener
</summary>

```diff
+ CompletableFuture reload(PreparableReloadListener$PreparationBarrier,ResourceManager,Executor,Executor)
- CompletableFuture reload(PreparableReloadListener$SharedState,Executor,PreparableReloadListener$PreparationBarrier,Executor)
```

</details>
<details>
<summary>
net.minecraft.server.players.UserWhiteList
</summary>

```diff
+ boolean isWhiteListed(GameProfile)
- boolean isWhiteListed(NameAndId)
+ String getKeyForUser(GameProfile)
- String getKeyForUser(NameAndId)
```

</details>
<details>
<summary>
net.minecraft.util.NullOps
</summary>

```diff
+ String lambda$getBooleanValue$1()
+ String lambda$getByteBuffer$8()
+ String lambda$getIntStream$9()
+ String lambda$getList$7()
+ String lambda$getLongStream$10()
+ String lambda$getMap$5()
+ String lambda$getMapEntries$4()
+ String lambda$getMapValues$3()
+ String lambda$getNumberValue$0()
+ String lambda$getStream$6()
+ String lambda$getStringValue$2()
- void lambda$getList$1(Consumer)
- void lambda$getMapEntries$0(BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.util.thread.BlockableEventLoop
</summary>

```diff
- boolean shouldRunAllTasks()
```

</details>
<details>
<summary>
net.minecraft.world.Container
</summary>

```diff
- List getEntitiesWithContainerOpen()
- void startOpen(ContainerUser)
+ void startOpen(Player)
- void stopOpen(ContainerUser)
+ void stopOpen(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Animal
</summary>

```diff
+ void usePlayerItem(Player,InteractionHand,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
+ void dropHoneycomb(Level,BlockPos)
- void dropHoneycomb(ServerLevel,ItemStack,BlockState,BlockEntity,Entity,BlockPos)
- void lambda$dropHoneycomb$0(BlockPos,ServerLevel,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
- Block lambda$static$491(BlockBehaviour$Properties)
- Block lambda$static$492(BlockBehaviour$Properties)
- Block lambda$static$493(BlockBehaviour$Properties)
- Block lambda$static$494(BlockBehaviour$Properties)
- Block lambda$static$495(BlockBehaviour$Properties)
- Block lambda$static$501(BlockBehaviour$Properties)
- Block lambda$static$502(BlockBehaviour$Properties)
- Block lambda$static$503(BlockBehaviour$Properties)
- Block lambda$static$504(BlockBehaviour$Properties)
- Block lambda$static$505(BlockBehaviour$Properties)
- Block lambda$static$506(BlockBehaviour$Properties)
- Block lambda$static$507(BlockBehaviour$Properties)
- Block lambda$static$508(BlockBehaviour$Properties)
- Block lambda$static$509(BlockBehaviour$Properties)
- Block lambda$static$510(BlockBehaviour$Properties)
- Block lambda$static$516(BlockBehaviour$Properties)
- Block lambda$static$517(BlockBehaviour$Properties)
- Block lambda$static$518(BlockBehaviour$Properties)
- Block lambda$static$519(BlockBehaviour$Properties)
- Block lambda$static$520(BlockBehaviour$Properties)
+ int lambda$static$491(BlockState)
+ int lambda$static$492(BlockState)
+ int lambda$static$493(BlockState)
+ int lambda$static$494(BlockState)
+ int lambda$static$495(BlockState)
+ int lambda$static$501(BlockState)
- int lambda$static$511(BlockState)
- int lambda$static$512(BlockState)
- int lambda$static$513(BlockState)
- int lambda$static$514(BlockState)
- int lambda$static$515(BlockState)
- int lambda$static$521(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DetectorRailBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndPortalFrameBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JukeboxBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LayeredCauldronBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PumpkinBlock
</summary>

```diff
- void lambda$useItemOn$0(Level,BlockPos,Direction,ServerLevel,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkSensorBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WeatheringCopper$WeatherState
</summary>

```diff
- WeatheringCopper$WeatherState next()
- WeatheringCopper$WeatherState previous()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.EnderChestBlockEntity
</summary>

```diff
- void startOpen(ContainerUser)
+ void startOpen(Player)
- void stopOpen(ContainerUser)
+ void stopOpen(Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- boolean shouldChangedStateKeepBlockEntity(BlockState)
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- boolean shouldChangedStateKeepBlockEntity(BlockState)
- int getAnalogOutputSignal(Level,BlockPos,Direction)
+ int getAnalogOutputSignal(Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseRouter
</summary>

```diff
+ DensityFunction initialDensityWithoutJaggedness()
- DensityFunction preliminarySurfaceLevel()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.blending.Blender
</summary>

```diff
- boolean isEmpty()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.BoundingBox
</summary>

```diff
- BoundingBox encapsulating(BoundingBox,BoundingBox)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.Attribute$Sentiment
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeInstance$Packed
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.AttributeSupplier$Builder
+ XXX.ai.attributes.DefaultAttributes
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
- XXX.ai.behavior.AnimalMakeLove
+ XXX.ai.behavior.AnimalPanic
- XXX.ai.behavior.AssignProfessionFromJobSite
+ XXX.ai.behavior.BabyFollowAdult
- XXX.ai.behavior.BackUpIfTooClose
+ XXX.ai.behavior.BecomePassiveIfMemoryPresent
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorControl
+ XXX.ai.behavior.BehaviorUtils
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.CelebrateVillagersSurvivedRaid
- XXX.ai.behavior.CopyMemoryWithExpiry
+ XXX.ai.behavior.CountDownCooldownTicks
- XXX.ai.behavior.Croak
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.FollowTemptation
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoAndGiveItemsToTarget
+ XXX.ai.behavior.GoToClosestVillage
- XXX.ai.behavior.GoToPotentialJobSite
+ XXX.ai.behavior.GoToTargetLocation
- XXX.ai.behavior.GoToWantedItem
+ XXX.ai.behavior.HarvestFarmland
- XXX.ai.behavior.InsideBrownianWalk
+ XXX.ai.behavior.InteractWith
- XXX.ai.behavior.InteractWithDoor
+ XXX.ai.behavior.JumpOnBed
- XXX.ai.behavior.LocateHidingPlace
+ XXX.ai.behavior.LongJumpMidJump
- XXX.ai.behavior.LongJumpToPreferredBlock
+ XXX.ai.behavior.LongJumpToRandomPos
- XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
+ XXX.ai.behavior.LongJumpUtil
- XXX.ai.behavior.LookAndFollowTradingPlayerSink
+ XXX.ai.behavior.LookAtTargetSink
- XXX.ai.behavior.MeleeAttack
+ XXX.ai.behavior.Mount
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.OneShot
+ XXX.ai.behavior.PlayTagWithOtherKids
- XXX.ai.behavior.PoiCompetitorScan
+ XXX.ai.behavior.PositionTracker
- XXX.ai.behavior.PrepareRamNearestTarget
+ XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
- XXX.ai.behavior.RamTarget
+ XXX.ai.behavior.RandomLookAround
- XXX.ai.behavior.RandomStroll
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetEntityLookTargetSometimes
+ XXX.ai.behavior.SetEntityLookTargetSometimes$Ticker
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFrom
- XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ XXX.ai.behavior.SetWalkTargetFromBlockMemory
- XXX.ai.behavior.SetWalkTargetFromLookTarget
+ XXX.ai.behavior.ShowTradesToPlayer
- XXX.ai.behavior.ShufflingList
+ XXX.ai.behavior.ShufflingList$WeightedEntry
- XXX.ai.behavior.ShufflingList$WeightedEntry$1
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartAttacking$StartAttackingCondition
+ XXX.ai.behavior.StartAttacking$TargetFinder
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StayCloseToTarget
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopAttackingIfTargetInvalid$StopAttackCondition
- XXX.ai.behavior.StopAttackingIfTargetInvalid$TargetErasedCallback
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TransportItemsBetweenContainers$ContainerInteractionState
- XXX.ai.behavior.TransportItemsBetweenContainers$TransportItemState
- XXX.animal.coppergolem.CopperGolem
- XXX.animal.coppergolem.CopperGolemAi
- XXX.animal.coppergolem.CopperGolemOxidationLevels
- XXX.animal.coppergolem.package-info
+ XXX.animal.frog.Frog
- XXX.animal.frog.Frog$FrogLookControl
+ XXX.animal.frog.Frog$FrogNodeEvaluator
- XXX.animal.frog.Frog$FrogPathNavigation
+ XXX.animal.frog.FrogAi
- XXX.animal.frog.FrogVariant
+ XXX.animal.frog.FrogVariants
- XXX.animal.frog.package-info
- XXX.animal.frog.ShootTongue
+ XXX.animal.frog.ShootTongue$State
- XXX.animal.frog.Tadpole
+ XXX.animal.frog.TadpoleAi
+ XXX.animal.goat.Goat
- XXX.animal.goat.GoatAi
+ XXX.animal.goat.package-info
- XXX.animal.horse.AbstractChestedHorse
+ XXX.animal.horse.AbstractChestedHorse$1
- XXX.animal.horse.AbstractHorse
+ XXX.animal.horse.Donkey
- XXX.animal.horse.Horse
+ XXX.animal.horse.Horse$HorseGroupData
- XXX.animal.horse.Llama
+ XXX.animal.horse.Llama$LlamaAttackWolfGoal
- XXX.animal.horse.Llama$LlamaGroupData
+ XXX.animal.horse.Llama$LlamaHurtByTargetGoal
- XXX.animal.horse.Llama$Variant
+ XXX.animal.horse.Markings
- XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.Variant
- XXX.animal.horse.ZombieHorse
+ XXX.animal.sheep.package-info
+ XXX.animal.sheep.Sheep
- XXX.animal.sheep.SheepColorSpawnRules
+ XXX.animal.sheep.SheepColorSpawnRules$SheepColorProvider
- XXX.animal.sheep.SheepColorSpawnRules$SheepColorSpawnConfiguration
- XXX.animal.sniffer.package-info
- XXX.animal.sniffer.Sniffer
+ XXX.animal.sniffer.Sniffer$State
- XXX.animal.sniffer.SnifferAi
+ XXX.animal.sniffer.SnifferAi$1
- XXX.animal.sniffer.SnifferAi$2
+ XXX.animal.sniffer.SnifferAi$3
- XXX.animal.sniffer.SnifferAi$Digging
+ XXX.animal.sniffer.SnifferAi$FeelingHappy
- XXX.animal.sniffer.SnifferAi$FinishedDigging
+ XXX.animal.sniffer.SnifferAi$Scenting
- XXX.animal.sniffer.SnifferAi$Searching
+ XXX.animal.sniffer.SnifferAi$Sniffing
- XXX.animal.wolf.package-info
+ XXX.animal.wolf.Wolf
- XXX.animal.wolf.Wolf$WolfAvoidEntityGoal
+ XXX.animal.wolf.Wolf$WolfPackData
- XXX.animal.wolf.WolfSoundVariant
+ XXX.animal.wolf.WolfSoundVariants
- XXX.animal.wolf.WolfSoundVariants$SoundSet
+ XXX.animal.wolf.WolfVariant
- XXX.animal.wolf.WolfVariant$AssetInfo
+ XXX.animal.wolf.WolfVariants
- XXX.animation.definitions.ArmadilloAnimation
+ XXX.animation.definitions.BatAnimation
- XXX.animation.definitions.BreezeAnimation
+ XXX.animation.definitions.CamelAnimation
- XXX.animation.definitions.CopperGolemAnimation
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPatternLayers
- XXX.block.entity.BannerPatternLayers$Builder
+ XXX.block.entity.BannerPatternLayers$Layer
- XXX.block.entity.BannerPatterns
+ XXX.block.entity.BarrelBlockEntity
- XXX.block.entity.BarrelBlockEntity$1
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBeamOwner
+ XXX.block.entity.BeaconBeamOwner$Section
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BeehiveBlockEntity$Occupant
+ XXX.block.entity.BellBlockEntity
- XXX.block.entity.BellBlockEntity$ResonationEndAction
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntity$1
- XXX.block.entity.BlockEntity$BlockEntityPathElement
+ XXX.block.entity.BlockEntityTicker
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$BlockEntitySupplier
- XXX.block.entity.BoundingBoxRenderable
+ XXX.block.entity.BoundingBoxRenderable$Mode
- XXX.block.entity.BoundingBoxRenderable$RenderableBox
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.BrushableBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.ChiseledBookShelfBlockEntity
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.ListBackedContainer
+ XXX.block.entity.PotDecorations
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.SculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.SculkShriekerBlockEntity
- XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
+ XXX.block.entity.SkullBlockEntity$2
- XXX.boss.enderdragon.DragonFlightHistory
+ XXX.boss.enderdragon.DragonFlightHistory$Sample
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.DataSource$Type
- XXX.chat.contents.EntityDataSource
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.NbtContents
- XXX.chat.contents.package-info
- XXX.chat.contents.PlainTextContents
+ XXX.chat.contents.PlainTextContents$1
- XXX.chat.contents.PlainTextContents$LiteralContents
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.StorageDataSource
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
+ XXX.chat.numbers.BlankFormat
- XXX.chat.numbers.BlankFormat$1
+ XXX.chat.numbers.FixedFormat
- XXX.chat.numbers.FixedFormat$1
+ XXX.chat.numbers.NumberFormat
- XXX.chat.numbers.NumberFormatType
+ XXX.chat.numbers.NumberFormatTypes
- XXX.chat.numbers.package-info
- XXX.chat.numbers.StyledFormat
+ XXX.chat.numbers.StyledFormat$1
+ XXX.chat.report.AbuseReportSender
- XXX.chat.report.AbuseReportSender$1
+ XXX.chat.report.AbuseReportSender$SendException
- XXX.chat.report.AbuseReportSender$Services
+ XXX.chat.report.BanReason
- XXX.chat.report.ChatReport
+ XXX.chat.report.ChatReport$Builder
- XXX.chat.report.ChatReportContextBuilder
+ XXX.chat.report.ChatReportContextBuilder$Collector
- XXX.chat.report.ChatReportContextBuilder$Handler
+ XXX.chat.report.NameReport
- XXX.chat.report.NameReport$Builder
+ XXX.chat.report.package-info
+ XXX.chat.report.Report
- XXX.chat.report.Report$Builder
+ XXX.chat.report.Report$CannotBuildReason
- XXX.chat.report.Report$Result
+ XXX.chat.report.ReportEnvironment
- XXX.chat.report.ReportEnvironment$Server
+ XXX.chat.report.ReportEnvironment$Server$Realm
- XXX.chat.report.ReportEnvironment$Server$ThirdParty
- XXX.chat.report.ReportingContext
+ XXX.chat.report.ReportReason
- XXX.chat.report.ReportReason$1
+ XXX.chat.report.ReportType
+ XXX.chat.report.SkinReport
- XXX.chat.report.SkinReport$Builder
+ XXX.chunk.status.ChunkDependencies
- XXX.chunk.status.ChunkPyramid
+ XXX.chunk.status.ChunkPyramid$Builder
- XXX.chunk.status.ChunkStatus
+ XXX.chunk.status.ChunkStatusTask
- XXX.chunk.status.ChunkStatusTasks
+ XXX.chunk.status.ChunkStep
- XXX.chunk.status.ChunkStep$Builder
+ XXX.chunk.status.ChunkType
+ XXX.chunk.status.package-info
- XXX.chunk.status.WorldGenContext
- XXX.chunk.storage.ChunkIOErrorReporter
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.EntityStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$PendingStore
- XXX.chunk.storage.IOWorker$Priority
+ XXX.chunk.storage.IOWorker$ThrowingSupplier
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RecreatingChunkStorage
+ XXX.chunk.storage.RecreatingSimpleRegionStorage
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.RegionStorageInfo
- XXX.chunk.storage.SectionStorage
+ XXX.chunk.storage.SectionStorage$PackedChunk
- XXX.chunk.storage.SerializableChunkData
+ XXX.chunk.storage.SerializableChunkData$ChunkReadException
- XXX.chunk.storage.SerializableChunkData$SectionData
+ XXX.chunk.storage.SimpleRegionStorage
+ XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolation
+ XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Target
+ XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition
+ XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.Keyframe
+ XXX.client.animation.KeyframeAnimation
- XXX.client.animation.KeyframeAnimation$Entry
+ XXX.client.animation.KeyframeAnimations
- XXX.client.gui.GlyphSource
+ XXX.client.gui.GuiSpriteManager
- XXX.client.gui.ItemSlotMouseAction
- XXX.client.gui.package-info
- XXX.client.model.BellModel$1
- XXX.client.model.BookModel$State
+ XXX.client.model.BreezeModel
- XXX.client.model.CamelModel
+ XXX.client.model.CamelSaddleModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColdChickenModel
+ XXX.client.model.ColdCowModel
- XXX.client.model.ColdPigModel
+ XXX.client.model.HumanoidModel
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.LlamaModel
- XXX.client.model.LlamaSpitModel
+ XXX.client.model.MinecartModel
- XXX.client.model.Model
+ XXX.client.model.Model$Simple
- XXX.client.model.OcelotModel
+ XXX.client.model.PandaModel
- XXX.client.model.ParrotModel
+ XXX.client.model.ParrotModel$Pose
- XXX.client.model.PhantomModel
- XXX.client.model.PiglinHeadModel
+ XXX.client.model.PiglinModel
+ XXX.client.model.PigModel
- XXX.client.model.PlayerCapeModel
+ XXX.client.model.PlayerEarsModel
- XXX.client.model.PlayerModel
+ XXX.client.model.PolarBearModel
- XXX.client.model.PufferfishBigModel
+ XXX.client.model.PufferfishMidModel
- XXX.client.model.PufferfishSmallModel
+ XXX.client.model.QuadrupedModel
- XXX.client.model.RabbitModel
+ XXX.client.model.RaftModel
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
- XXX.client.model.SkullModelBase
+ XXX.client.multiplayer.LevelLoadStatusManager$Status
- XXX.client.multiplayer.LevelLoadTracker$ClientLevelReady
- XXX.client.multiplayer.LevelLoadTracker$WaitingForPlayerChunk
- XXX.client.multiplayer.MultiPlayerGameMode
- XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PingDebugMonitor
- XXX.client.multiplayer.PlayerInfo
+ XXX.client.multiplayer.ProfileKeyPairManager
- XXX.client.multiplayer.ProfileKeyPairManager$1
+ XXX.client.multiplayer.RegistryDataCollector
- XXX.client.multiplayer.RegistryDataCollector$ContentsCollector
+ XXX.client.multiplayer.RegistryDataCollector$TagCollector
- XXX.client.multiplayer.ServerData
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerData$State
+ XXX.client.multiplayer.ServerData$Type
- XXX.client.multiplayer.ServerList
+ XXX.client.multiplayer.ServerStatusPinger
- XXX.client.multiplayer.ServerStatusPinger$1
+ XXX.client.multiplayer.ServerStatusPinger$2
- XXX.client.multiplayer.SessionSearchTrees
+ XXX.client.multiplayer.SessionSearchTrees$Key
- XXX.client.multiplayer.TransferState
+ XXX.client.particle.AshParticle
- XXX.client.particle.AshParticle$Provider
+ XXX.client.particle.AttackSweepParticle
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BaseAshSmokeParticle
- XXX.client.particle.BlockMarker
+ XXX.client.particle.BlockMarker$Provider
- XXX.client.particle.BreakingItemParticle
+ XXX.client.particle.BreakingItemParticle$CobwebProvider
- XXX.client.particle.BreakingItemParticle$ItemParticleProvider
+ XXX.client.particle.BreakingItemParticle$Provider
- XXX.client.particle.BreakingItemParticle$SlimeProvider
+ XXX.client.particle.BreakingItemParticle$SnowballProvider
- XXX.client.particle.BubbleColumnUpParticle
+ XXX.client.particle.BubbleColumnUpParticle$Provider
- XXX.client.particle.BubbleParticle
+ XXX.client.particle.BubbleParticle$Provider
- XXX.client.particle.BubblePopParticle
+ XXX.client.particle.BubblePopParticle$Provider
- XXX.client.particle.CampfireSmokeParticle
+ XXX.client.particle.CampfireSmokeParticle$CosyProvider
- XXX.client.particle.CampfireSmokeParticle$SignalProvider
+ XXX.client.particle.CritParticle
- XXX.client.particle.CritParticle$DamageIndicatorProvider
+ XXX.client.particle.CritParticle$MagicProvider
- XXX.client.particle.CritParticle$Provider
+ XXX.client.particle.DragonBreathParticle
- XXX.client.particle.DragonBreathParticle$Provider
+ XXX.client.particle.DripParticle
- XXX.client.particle.DripParticle$CoolingDripHangParticle
+ XXX.client.particle.DripParticle$DripHangParticle
- XXX.client.particle.DripParticle$DripLandParticle
+ XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
- XXX.client.particle.DripParticle$FallAndLandParticle
+ XXX.client.particle.DripParticle$FallingParticle
- XXX.client.particle.DripParticle$HoneyFallAndLandParticle
+ XXX.client.particle.DustColorTransitionParticle
- XXX.client.particle.DustColorTransitionParticle$Provider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$Provider
+ XXX.client.particle.DustParticleBase
- XXX.client.particle.DustPlumeParticle
+ XXX.client.particle.DustPlumeParticle$Provider
- XXX.client.particle.EndRodParticle
+ XXX.client.particle.EndRodParticle$Provider
- XXX.client.particle.ExplodeParticle
+ XXX.client.particle.ExplodeParticle$Provider
- XXX.client.particle.FallingDustParticle
+ XXX.client.particle.FallingDustParticle$Provider
- XXX.client.particle.FallingLeavesParticle
+ XXX.client.particle.FallingLeavesParticle$CherryProvider
- XXX.client.particle.FallingLeavesParticle$PaleOakProvider
+ XXX.client.particle.FallingLeavesParticle$TintedLeavesProvider
- XXX.client.particle.FireflyParticle
+ XXX.client.particle.FireflyParticle$FireflyProvider
- XXX.client.particle.FireworkParticles
+ XXX.client.particle.FireworkParticles$1
- XXX.client.particle.FireworkParticles$FlashProvider
+ XXX.client.particle.FireworkParticles$OverlayParticle
- XXX.client.particle.FireworkParticles$SparkParticle
+ XXX.client.particle.FireworkParticles$SparkProvider
- XXX.client.particle.FireworkParticles$Starter
+ XXX.client.particle.FlameParticle
- XXX.client.particle.FlameParticle$Provider
+ XXX.client.particle.FlameParticle$SmallFlameProvider
- XXX.client.particle.FlyStraightTowardsParticle
+ XXX.client.particle.FlyStraightTowardsParticle$OminousSpawnProvider
- XXX.client.particle.FlyTowardsPositionParticle
+ XXX.client.particle.FlyTowardsPositionParticle$EnchantProvider
- XXX.client.particle.FlyTowardsPositionParticle$NautilusProvider
+ XXX.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
- XXX.client.particle.GlowParticle
+ XXX.client.particle.GlowParticle$ElectricSparkProvider
- XXX.client.particle.GlowParticle$GlowSquidProvider
+ XXX.client.particle.GlowParticle$ScrapeProvider
- XXX.client.particle.GlowParticle$WaxOffProvider
+ XXX.client.particle.GlowParticle$WaxOnProvider
- XXX.client.particle.GustParticle
+ XXX.client.particle.GustParticle$Provider
- XXX.client.particle.GustParticle$SmallProvider
+ XXX.client.particle.GustSeedParticle
- XXX.client.particle.GustSeedParticle$Provider
+ XXX.client.particle.HeartParticle
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$Provider
- XXX.client.particle.HugeExplosionSeedParticle
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$Provider
+ XXX.client.particle.MobAppearanceParticle
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$Provider
+ XXX.client.particle.package-info
- XXX.client.particle.Particle
+ XXX.client.particle.Particle$LifetimeAlpha
- XXX.client.particle.ParticleDescription
+ XXX.client.particle.ParticleEngine
- XXX.client.particle.ParticleEngine$1ParticleDefinition
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleEngine$SpriteParticleRegistration
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleProvider$Sprite
+ XXX.client.particle.ParticleRenderType
- XXX.client.particle.PlayerCloudParticle
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$Provider
+ XXX.client.particle.ReversePortalParticle
- XXX.client.particle.ReversePortalParticle$ReversePortalProvider
+ XXX.client.particle.RisingParticle
- XXX.client.particle.SculkChargeParticle
+ XXX.client.particle.SculkChargeParticle$Provider
- XXX.client.particle.SculkChargePopParticle
+ XXX.client.particle.SculkChargePopParticle$Provider
- XXX.client.particle.ShriekParticle
+ XXX.client.particle.ShriekParticle$Provider
- XXX.client.particle.SimpleAnimatedParticle
+ XXX.client.particle.SingleQuadParticle
- XXX.client.particle.SingleQuadParticle$FacingCameraMode
+ XXX.client.particle.SmokeParticle
- XXX.client.particle.SmokeParticle$Provider
+ XXX.client.particle.SnowflakeParticle
- XXX.client.particle.SnowflakeParticle$Provider
+ XXX.client.particle.SonicBoomParticle
- XXX.client.particle.SonicBoomParticle$Provider
+ XXX.client.particle.SoulParticle
- XXX.client.particle.SoulParticle$EmissiveProvider
+ XXX.client.particle.SoulParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$InstantProvider
- XXX.client.particle.SpellParticle$MobEffectProvider
+ XXX.client.particle.SpellParticle$Provider
- XXX.client.particle.SpellParticle$WitchProvider
+ XXX.client.particle.SpitParticle
- XXX.client.particle.SpitParticle$Provider
+ XXX.client.particle.SplashParticle
- XXX.client.particle.SplashParticle$Provider
+ XXX.client.particle.SpriteSet
- XXX.client.particle.SquidInkParticle
+ XXX.client.particle.SquidInkParticle$GlowInkProvider
- XXX.client.particle.SquidInkParticle$Provider
+ XXX.client.particle.SuspendedParticle
- XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
+ XXX.client.particle.SuspendedParticle$UnderwaterProvider
- XXX.client.particle.SuspendedParticle$WarpedSporeProvider
+ XXX.client.particle.SuspendedTownParticle
- XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
+ XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- XXX.client.particle.SuspendedTownParticle$EggCrackProvider
+ XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
- XXX.client.particle.SuspendedTownParticle$Provider
+ XXX.client.particle.TerrainParticle
- XXX.client.particle.TerrainParticle$CrumblingProvider
+ XXX.client.particle.TerrainParticle$DustPillarProvider
- XXX.client.particle.TerrainParticle$Provider
+ XXX.client.particle.TextureSheetParticle
- XXX.client.particle.TotemParticle
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
+ XXX.client.particle.TrailParticle
- XXX.client.particle.TrailParticle$Provider
+ XXX.client.particle.TrialSpawnerDetectionParticle
- XXX.client.particle.TrialSpawnerDetectionParticle$Provider
+ XXX.client.particle.VibrationSignalParticle
- XXX.client.particle.VibrationSignalParticle$Provider
+ XXX.client.particle.WakeParticle
- XXX.client.particle.WakeParticle$Provider
+ XXX.client.particle.WaterCurrentDownParticle
- XXX.client.particle.WaterCurrentDownParticle$Provider
+ XXX.client.particle.WaterDropParticle
- XXX.client.particle.WaterDropParticle$Provider
+ XXX.client.particle.WhiteAshParticle
- XXX.client.particle.WhiteAshParticle$Provider
+ XXX.client.particle.WhiteSmokeParticle
- XXX.client.particle.WhiteSmokeParticle$Provider
- XXX.client.player.AbstractClientPlayer
+ XXX.client.player.ClientInput
- XXX.client.player.KeyboardInput
+ XXX.client.player.LocalPlayer
+ XXX.client.player.package-info
- XXX.client.player.RemotePlayer
- XXX.client.profiling.ClientMetricsSamplersProvider
+ XXX.client.profiling.package-info
- XXX.client.quickplay.package-info
- XXX.client.quickplay.QuickPlay
+ XXX.client.quickplay.QuickPlayLog
- XXX.client.quickplay.QuickPlayLog$1
+ XXX.client.quickplay.QuickPlayLog$QuickPlayEntry
- XXX.client.quickplay.QuickPlayLog$QuickPlayWorld
+ XXX.client.quickplay.QuickPlayLog$Type
+ XXX.client.renderer.BiomeColors
- XXX.client.renderer.CachedOrthoProjectionMatrixBuffer
+ XXX.client.renderer.CachedPerspectiveProjectionMatrixBuffer
- XXX.client.renderer.CloudRenderer
+ XXX.client.renderer.CloudRenderer$RelativeCameraPos
- XXX.client.renderer.CloudRenderer$TextureData
+ XXX.client.renderer.CubeMap
- XXX.client.renderer.DimensionSpecialEffects
+ XXX.client.renderer.DimensionSpecialEffects$EndEffects
- XXX.client.renderer.DimensionSpecialEffects$NetherEffects
+ XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
- XXX.client.renderer.DimensionSpecialEffects$SkyType
+ XXX.client.renderer.DynamicUniforms
- XXX.client.renderer.DynamicUniforms$Transform
+ XXX.client.renderer.DynamicUniformStorage
- XXX.client.renderer.DynamicUniformStorage$DynamicUniform
+ XXX.client.renderer.FaceInfo
- XXX.client.renderer.FaceInfo$Constants
+ XXX.client.renderer.FaceInfo$VertexInfo
- XXX.client.renderer.GameRenderer
+ XXX.client.renderer.GlobalSettingsUniform
- XXX.client.renderer.GpuWarnlistManager
+ XXX.client.renderer.GpuWarnlistManager$Preparations
- XXX.client.renderer.ItemBlockRenderTypes
+ XXX.client.renderer.ItemBlockRenderTypes$2
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
+ XXX.client.renderer.LevelEventHandler
- XXX.client.renderer.LevelRenderState
- XXX.client.renderer.SubmitNodeCollector$CustomGeometryRenderer
- XXX.client.renderer.SubmitNodeStorage$BlockModelSubmit
- XXX.client.renderer.SubmitNodeStorage$CustomGeometrySubmit
- XXX.client.renderer.SubmitNodeStorage$FlameSubmit
- XXX.client.renderer.SubmitNodeStorage$ItemSubmit
- XXX.client.renderer.SubmitNodeStorage$ModelSubmit
- XXX.client.renderer.SubmitNodeStorage$NameTagSubmit
- XXX.client.renderer.SubmitNodeStorage$TextSubmit
+ XXX.client.resources.MapDecorationTextureManager
- XXX.client.resources.MapTextureManager
+ XXX.client.resources.MapTextureManager$MapInstance
+ XXX.client.resources.TextureAtlasHolder
- XXX.client.resources.WaypointStyle
+ XXX.client.resources.WaypointStyleManager
- XXX.common.custom.BeeDebugPayload
+ XXX.common.custom.BeeDebugPayload$BeeInfo
- XXX.common.custom.BrainDebugPayload
+ XXX.common.custom.BrainDebugPayload$BrainDump
- XXX.common.custom.BrandPayload
+ XXX.common.custom.BreezeDebugPayload
- XXX.common.custom.BreezeDebugPayload$BreezeInfo
+ XXX.common.custom.CustomPacketPayload
- XXX.common.custom.CustomPacketPayload$1
+ XXX.common.custom.CustomPacketPayload$FallbackProvider
- XXX.common.custom.CustomPacketPayload$Type
+ XXX.common.custom.CustomPacketPayload$TypeAndCodec
- XXX.common.custom.DiscardedPayload
+ XXX.common.custom.GameEventDebugPayload
- XXX.common.custom.GameEventListenerDebugPayload
+ XXX.common.custom.GameTestAddMarkerDebugPayload
- XXX.common.custom.GameTestClearMarkersDebugPayload
+ XXX.common.custom.GoalDebugPayload
- XXX.common.custom.GoalDebugPayload$DebugGoal
+ XXX.common.custom.HiveDebugPayload
- XXX.common.custom.HiveDebugPayload$HiveInfo
+ XXX.common.custom.NeighborUpdatesDebugPayload
+ XXX.common.custom.package-info
- XXX.common.custom.PathfindingDebugPayload
+ XXX.common.custom.PoiAddedDebugPayload
- XXX.common.custom.PoiRemovedDebugPayload
+ XXX.common.custom.PoiTicketCountDebugPayload
- XXX.common.custom.RaidsDebugPayload
+ XXX.common.custom.RedstoneWireOrientationsDebugPayload
- XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
+ XXX.common.custom.StructuresDebugPayload
- XXX.common.custom.StructuresDebugPayload$PieceInfo
+ XXX.common.custom.VillageSectionsDebugPayload
- XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.components.debug.DebugEntryBiome
- XXX.components.debug.DebugEntryChunkGeneration
- XXX.components.debug.DebugEntryChunkSourceStats
- XXX.components.debug.DebugEntryFps
- XXX.components.debug.DebugEntryHeightmap
- XXX.components.debug.DebugEntryLocalDifficulty
- XXX.components.debug.DebugEntryLookingAtEntity
- XXX.components.debug.DebugEntryMemory
- XXX.components.debug.DebugEntryNoop
- XXX.components.debug.DebugEntryPosition
- XXX.components.debug.DebugEntryPostEffect
- XXX.components.debug.DebugEntrySimplePerformanceImpactors
- XXX.components.debug.DebugEntrySpawnCounts
- XXX.components.debug.DebugEntryTps
- XXX.components.debug.DebugScreenDisplayer
- XXX.components.debug.DebugScreenEntry
- XXX.components.debug.DebugScreenEntryList$SerializedOptions
- XXX.components.debug.DebugScreenProfile
- XXX.crafting.display.DisplayContentsFactory
+ XXX.crafting.display.DisplayContentsFactory$ForRemainders
- XXX.crafting.display.DisplayContentsFactory$ForStacks
+ XXX.crafting.display.FurnaceRecipeDisplay
- XXX.crafting.display.package-info
- XXX.crafting.display.RecipeDisplay
+ XXX.crafting.display.RecipeDisplay$Type
- XXX.crafting.display.RecipeDisplayEntry
+ XXX.crafting.display.RecipeDisplayId
- XXX.crafting.display.RecipeDisplays
+ XXX.crafting.display.ShapedCraftingRecipeDisplay
- XXX.crafting.display.ShapelessCraftingRecipeDisplay
+ XXX.crafting.display.SlotDisplay
- XXX.crafting.display.SlotDisplay$AnyFuel
+ XXX.crafting.display.SlotDisplay$Composite
- XXX.crafting.display.SlotDisplay$Empty
+ XXX.crafting.display.SlotDisplay$ItemSlotDisplay
- XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
+ XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
- XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
+ XXX.crafting.display.SlotDisplay$TagSlotDisplay
- XXX.crafting.display.SlotDisplay$Type
+ XXX.crafting.display.SlotDisplay$WithRemainder
- XXX.crafting.display.SlotDisplayContext
+ XXX.crafting.display.SlotDisplays
- XXX.crafting.display.SmithingRecipeDisplay
+ XXX.crafting.display.StonecutterRecipeDisplay
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractBlockPropertyFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
+ XXX.datafix.fixes.AreaEffectCloudPotionFix
- XXX.datafix.fixes.AttributeIdPrefixFix
+ XXX.datafix.fixes.AttributeModifierIdFix
- XXX.datafix.fixes.AttributesRenameFix
+ XXX.datafix.fixes.AttributesRenameLegacy
- XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.BannerPatternFormatFix
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehiveFieldRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlendingDataFix
+ XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityFurnaceBurnTimeFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityRenameFix
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockPosFormatAndRenamesFix
+ XXX.datafix.fixes.BlockPropertyRenameAndFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.BoatSplitFix
+ XXX.datafix.fixes.CarvingStepRemoveFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.CauldronRenameFix
- XXX.datafix.fixes.CavesAndCliffsRenames
+ XXX.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
+ XXX.datafix.fixes.ChunkDeleteLightFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkTicketUnpackPosFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.ContainerBlockEntityLockPredicateFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.CustomModelDataExpandFix
- XXX.datafix.fixes.DataComponentRemainderFix
+ XXX.datafix.fixes.DecoratedPotFieldRenameFix
- XXX.datafix.fixes.DropChancesFormatFix
+ XXX.datafix.fixes.DropInvalidSignDataFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EffectDurationFix
- XXX.datafix.fixes.EmptyItemInHotbarFix
+ XXX.datafix.fixes.EmptyItemInVillagerTradeFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityAttributeBaseValueFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityFallDistanceFloatToDoubleFix
- XXX.datafix.fixes.EntityFieldsRenameFix
+ XXX.datafix.fixes.EntityGoatMissingStateFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntitySalmonSizeFix
+ XXX.datafix.fixes.EntityShulkerColorFix
- XXX.datafix.fixes.EntityShulkerRotationFix
+ XXX.datafix.fixes.EntitySkeletonSplitFix
- XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix
+ XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix$Fixer
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityUUIDFix
- XXX.datafix.fixes.EntityVariantFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.EquipmentFormatFix
- XXX.datafix.fixes.EquippableAssetRenameFix
+ XXX.datafix.fixes.FeatureFlagRemoveFix
- XXX.datafix.fixes.FilteredBooksFix
+ XXX.datafix.fixes.FilteredSignsFix
- XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
+ XXX.datafix.fixes.FixProjectileStoredItem
- XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
+ XXX.datafix.fixes.FixWolfHealth
- XXX.datafix.fixes.FoodToConsumableFix
- XXX.datafix.fixes.ForcedChunkToTicketFix
+ XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.HorseBodyArmorItemFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.InlineBlockPosFormatFix
- XXX.datafix.fixes.InvalidBlockEntityLockFix
+ XXX.datafix.fixes.InvalidLockComponentFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackComponentizationFix
- XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTagFix
- XXX.datafix.fixes.ItemStackTagRemainderFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LegacyDimensionIdFix
+ XXX.datafix.fixes.LegacyDragonFightFix
- XXX.datafix.fixes.LegacyHoverEventFix
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.LockComponentPredicateFix
- XXX.datafix.fixes.LodestoneCompassComponentFix
+ XXX.datafix.fixes.MapBannerBlockPosFormatFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobEffectIdFix
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityConvertUncheckedFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NamedEntityWriteReadFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveRenderTypeFix
+ XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.datafix.fixes.OminousBannerRarityFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAccessibilityOnboardFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsAmbientOcclusionFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsMenuBlurrinessFix
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.ParticleUnflatteningFix
- XXX.datafix.fixes.PlayerEquipmentFix
+ XXX.datafix.fixes.PlayerHeadBlockProfileFix
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRemoveFix
- XXX.datafix.fixes.PoiTypeRenameFix
+ XXX.datafix.fixes.PrimedTntBlockStateFixer
- XXX.datafix.fixes.ProjectileStoredWeaponFix
+ XXX.datafix.fixes.RaidRenamesDataFix
- XXX.datafix.fixes.RandomSequenceSettingsFix
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.References$1
- XXX.datafix.fixes.RemapChunkStatusFix
+ XXX.datafix.fixes.RemoveBlockEntityTagFix
- XXX.datafix.fixes.RemoveEmptyItemInBrushableBlockFix
+ XXX.datafix.fixes.RemoveGolemGossipFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.RenameEnchantmentsFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SaddleEquipmentSlotFix
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
+ XXX.datafix.fixes.ScoreboardDisplayNameFix
- XXX.datafix.fixes.ScoreboardDisplaySlotFix
+ XXX.datafix.fixes.SignTextStrictJsonFix
- XXX.datafix.fixes.SimpleEntityRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsCounterFix$StatType
+ XXX.datafix.fixes.StatsRenameFix
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- XXX.datafix.fixes.StructureSettingsFlattenFix
+ XXX.datafix.fixes.TextComponentHoverAndClickEventFix
- XXX.datafix.fixes.TextComponentStringifiedFlagsFix
+ XXX.datafix.fixes.ThrownPotionSplitFix
- XXX.datafix.fixes.ThrownPotionSplitFix$ItemIdFinder
+ XXX.datafix.fixes.TippedArrowPotionToItemFix
- XXX.datafix.fixes.TooltipDisplayComponentFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.TrialSpawnerConfigFix
- XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix
+ XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix$VanillaTrialChambers
- XXX.datafix.fixes.UnflattenTextComponentFix
+ XXX.datafix.fixes.VariantRenameFix
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerSetCanPickUpLootFix
- XXX.datafix.fixes.VillagerTradeFix
+ XXX.datafix.fixes.WallPropertyFix
- XXX.datafix.fixes.WeaponSmithChestLootTableFix
+ XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- XXX.datafix.fixes.WorldGenSettingsFix
+ XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.WrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.ZombieVillagerRebuildXpFix
- XXX.datafix.schemas.NamespacedSchema
+ XXX.datafix.schemas.NamespacedSchema$1
- XXX.datafix.schemas.V100
+ XXX.datafix.schemas.V102
- XXX.datafix.schemas.V1022
+ XXX.datafix.schemas.V106
- XXX.datafix.schemas.V107
+ XXX.datafix.schemas.V1125
- XXX.datafix.schemas.V135
+ XXX.datafix.schemas.V143
- XXX.datafix.schemas.V1451
+ XXX.datafix.schemas.V1451_1
- XXX.datafix.schemas.V1451_2
+ XXX.datafix.schemas.V1451_3
- XXX.datafix.schemas.V1451_4
+ XXX.datafix.schemas.V1451_5
- XXX.datafix.schemas.V1451_6
+ XXX.datafix.schemas.V1451_6$1
- XXX.datafix.schemas.V1451_6$2
+ XXX.datafix.schemas.V1458
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1488
+ XXX.datafix.schemas.V1510
- XXX.datafix.schemas.V1800
+ XXX.datafix.schemas.V1801
- XXX.datafix.schemas.V1904
+ XXX.datafix.schemas.V1906
- XXX.datafix.schemas.V1909
+ XXX.datafix.schemas.V1920
- XXX.datafix.schemas.V1928
+ XXX.datafix.schemas.V1929
- XXX.datafix.schemas.V1931
+ XXX.datafix.schemas.V2100
- XXX.datafix.schemas.V2501
+ XXX.datafix.schemas.V2502
- XXX.datafix.schemas.V2505
+ XXX.datafix.schemas.V2509
- XXX.datafix.schemas.V2511_1
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
+ XXX.datafix.schemas.V2831
- XXX.datafix.schemas.V2832
+ XXX.datafix.schemas.V2842
- XXX.datafix.schemas.V3076
+ XXX.datafix.schemas.V3078
- XXX.datafix.schemas.V3081
+ XXX.datafix.schemas.V3082
- XXX.datafix.schemas.V3083
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
- XXX.datafix.schemas.V3325
+ XXX.datafix.schemas.V3326
- XXX.datafix.schemas.V3327
+ XXX.datafix.schemas.V3328
- XXX.datafix.schemas.V3438
+ XXX.datafix.schemas.V3439
- XXX.datafix.schemas.V3439_1
+ XXX.datafix.schemas.V3448
- XXX.datafix.schemas.V3682
+ XXX.datafix.schemas.V3683
- XXX.datafix.schemas.V3685
+ XXX.datafix.schemas.V3689
- XXX.datafix.schemas.V3799
+ XXX.datafix.schemas.V3807
- XXX.datafix.schemas.V3808
+ XXX.datafix.schemas.V3808_1
- XXX.datafix.schemas.V3808_2
+ XXX.datafix.schemas.V3813
- XXX.datafix.schemas.V3816
+ XXX.datafix.schemas.V3818
- XXX.datafix.schemas.V3818_3
+ XXX.datafix.schemas.V3818_4
- XXX.datafix.schemas.V3818_5
+ XXX.datafix.schemas.V3825
- XXX.datafix.schemas.V3938
+ XXX.datafix.schemas.V4059
- XXX.datafix.schemas.V4067
+ XXX.datafix.schemas.V4070
- XXX.datafix.schemas.V4071
+ XXX.datafix.schemas.V4290
- XXX.datafix.schemas.V4292
+ XXX.datafix.schemas.V4300
- XXX.datafix.schemas.V4301
+ XXX.datafix.schemas.V4302
- XXX.datafix.schemas.V4306
+ XXX.datafix.schemas.V4307
- XXX.datafix.schemas.V4312
+ XXX.datafix.schemas.V4420
- XXX.datafix.schemas.V4421
- XXX.datafix.schemas.V4532
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.EndDragonFight$Data
- XXX.dimension.end.package-info
- XXX.enchantment.effects.AddValue
+ XXX.enchantment.effects.AllOf
- XXX.enchantment.effects.AllOf$EntityEffects
+ XXX.enchantment.effects.AllOf$LocationBasedEffects
- XXX.enchantment.effects.AllOf$ValueEffects
+ XXX.enchantment.effects.ApplyMobEffect
- XXX.enchantment.effects.ChangeItemDamage
+ XXX.enchantment.effects.DamageEntity
- XXX.enchantment.effects.DamageImmunity
+ XXX.enchantment.effects.EnchantmentAttributeEffect
- XXX.enchantment.effects.EnchantmentEntityEffect
+ XXX.enchantment.effects.EnchantmentLocationBasedEffect
- XXX.enchantment.effects.EnchantmentValueEffect
+ XXX.enchantment.effects.ExplodeEffect
- XXX.enchantment.effects.Ignite
+ XXX.enchantment.effects.MultiplyValue
+ XXX.enchantment.effects.package-info
- XXX.enchantment.effects.PlaySoundEffect
+ XXX.enchantment.effects.RemoveBinomial
- XXX.enchantment.effects.ReplaceBlock
+ XXX.enchantment.effects.ReplaceDisk
- XXX.enchantment.effects.RunFunction
+ XXX.enchantment.effects.SetBlockProperties
- XXX.enchantment.effects.SetValue
+ XXX.enchantment.effects.SpawnParticlesEffect
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
+ XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
- XXX.enchantment.effects.SummonEntityEffect
+ XXX.enchantment.providers.EnchantmentProvider
- XXX.enchantment.providers.EnchantmentProviderTypes
+ XXX.enchantment.providers.EnchantmentsByCost
- XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
- XXX.enchantment.providers.package-info
+ XXX.enchantment.providers.SingleEnchantment
- XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
+ XXX.enchantment.providers.VanillaEnchantmentProviders
+ XXX.enderdragon.phases.AbstractDragonPhaseInstance
- XXX.enderdragon.phases.AbstractDragonSittingPhase
+ XXX.enderdragon.phases.DragonChargePlayerPhase
- XXX.enderdragon.phases.DragonDeathPhase
+ XXX.enderdragon.phases.DragonHoldingPatternPhase
- XXX.enderdragon.phases.DragonHoverPhase
+ XXX.enderdragon.phases.DragonLandingApproachPhase
- XXX.enderdragon.phases.DragonLandingPhase
+ XXX.enderdragon.phases.DragonPhaseInstance
- XXX.enderdragon.phases.DragonSittingAttackingPhase
+ XXX.enderdragon.phases.DragonSittingFlamingPhase
- XXX.enderdragon.phases.DragonSittingScanningPhase
+ XXX.enderdragon.phases.DragonStrafePlayerPhase
- XXX.enderdragon.phases.DragonTakeoffPhase
+ XXX.enderdragon.phases.EnderDragonPhase
- XXX.enderdragon.phases.EnderDragonPhaseManager
+ XXX.enderdragon.phases.package-info
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
- XXX.entity.animal.package-info
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$ArmorStandPose
- XXX.entity.decoration.BlockAttachedEntity
+ XXX.entity.decoration.GlowItemFrame
- XXX.entity.decoration.HangingEntity
+ XXX.entity.decoration.HangingEntity$1
- XXX.entity.decoration.ItemFrame
+ XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
+ XXX.entity.decoration.PaintingVariant
- XXX.entity.decoration.PaintingVariants
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
+ XXX.entity.item.PrimedTnt$1
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LivingEntityEmissiveLayer
- XXX.entity.layers.LivingEntityEmissiveLayer$AlphaFunction
+ XXX.entity.layers.LivingEntityEmissiveLayer$DrawSelector
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.Bogged
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
- XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Shulker
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ XXX.entity.monster.Shulker$ShulkerLookControl
- XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
+ XXX.entity.monster.Shulker$ShulkerPeekGoal
- XXX.entity.monster.Silverfish
+ XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ XXX.entity.monster.Skeleton
- XXX.entity.monster.Slime
+ XXX.entity.monster.Slime$SlimeAttackGoal
- XXX.entity.monster.Slime$SlimeFloatGoal
+ XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
- XXX.entity.monster.Slime$SlimeMoveControl
+ XXX.entity.monster.Slime$SlimeRandomDirectionGoal
- XXX.entity.monster.SpellcasterIllager
+ XXX.entity.monster.SpellcasterIllager$IllagerSpell
- XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- XXX.entity.monster.Spider
+ XXX.entity.monster.Spider$SpiderAttackGoal
- XXX.entity.monster.Spider$SpiderEffectsGroupData
+ XXX.entity.monster.Spider$SpiderTargetGoal
- XXX.entity.monster.Stray
+ XXX.entity.monster.Strider
- XXX.entity.monster.Strider$StriderGoToLavaGoal
+ XXX.entity.monster.Strider$StriderPathNavigation
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Witch
+ XXX.entity.monster.WitherSkeleton
- XXX.entity.monster.Zoglin
+ XXX.entity.monster.Zombie
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
- XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$FailureItemListing
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerTrades$TypeSpecificTrade
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.Abilities$Packed
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Input
+ XXX.entity.player.Input$1
- XXX.entity.player.Inventory
- XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$2
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerEquipment
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.ProfileKeyPair
- XXX.entity.player.ProfilePublicKey
+ XXX.entity.player.ProfilePublicKey$Data
- XXX.entity.player.ProfilePublicKey$ValidationException
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$IngredientInfo
+ XXX.entity.player.StackedContents$Output
- XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.player.StackedItemContents
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.AbstractThrownPotion
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
- XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.Projectile$ProjectileFactory
+ XXX.entity.projectile.ProjectileDeflection
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
- XXX.entity.projectile.ThrownLingeringPotion
+ XXX.entity.projectile.ThrownSplashPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
+ XXX.entity.raid.Raid
- XXX.entity.raid.Raid$1
- XXX.entity.raid.Raid$RaiderType
+ XXX.entity.raid.Raid$RaidStatus
+ XXX.entity.raid.Raider
- XXX.entity.raid.Raider$HoldGroundAttackGoal
+ XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- XXX.entity.raid.Raider$RaiderCelebration
+ XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
- XXX.entity.raid.Raids
+ XXX.entity.raid.Raids$RaidWithId
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.state.CopperGolemRenderState
+ XXX.entity.state.CowRenderState
- XXX.entity.state.CreakingRenderState
+ XXX.entity.state.CreeperRenderState
- XXX.entity.state.DisplayEntityRenderState
+ XXX.entity.state.DolphinRenderState
- XXX.entity.state.DonkeyRenderState
+ XXX.entity.state.EndCrystalRenderState
- XXX.entity.state.EnderDragonRenderState
+ XXX.entity.state.EndermanRenderState
- XXX.entity.state.EntityRenderState
+ XXX.entity.state.EntityRenderState$LeashState
- XXX.entity.state.EntityRenderState$ShadowPiece
- XXX.entity.variant.BiomeCheck
+ XXX.entity.variant.ModelAndTexture
- XXX.entity.variant.MoonBrightnessCheck
+ XXX.entity.variant.package-info
+ XXX.entity.variant.PriorityProvider
- XXX.entity.variant.PriorityProvider$Selector
+ XXX.entity.variant.PriorityProvider$SelectorCondition
- XXX.entity.variant.PriorityProvider$UnpackedEntry
+ XXX.entity.variant.SpawnCondition
- XXX.entity.variant.SpawnConditions
+ XXX.entity.variant.SpawnContext
- XXX.entity.variant.SpawnPrioritySelectors
+ XXX.entity.variant.StructureCheck
- XXX.entity.variant.VariantUtils
- XXX.entity.vehicle.AbstractBoat
+ XXX.entity.vehicle.AbstractBoat$Status
- XXX.entity.vehicle.AbstractChestBoat
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestRaft
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartBehavior
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.NewMinecartBehavior
- XXX.entity.vehicle.NewMinecartBehavior$1
+ XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
- XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
+ XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
- XXX.entity.vehicle.OldMinecartBehavior
+ XXX.entity.vehicle.OldMinecartBehavior$1
- XXX.entity.vehicle.package-info
- XXX.entity.vehicle.Raft
+ XXX.entity.vehicle.VehicleEntity
- XXX.equipment.trim.ArmorTrim
+ XXX.equipment.trim.MaterialAssetGroup
- XXX.equipment.trim.MaterialAssetGroup$AssetInfo
+ XXX.equipment.trim.package-info
+ XXX.equipment.trim.TrimMaterial
- XXX.equipment.trim.TrimMaterials
+ XXX.equipment.trim.TrimPattern
- XXX.equipment.trim.TrimPatterns
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$Effect
- XXX.font.glyphs.BakedGlyph$GlyphInstance
+ XXX.font.glyphs.EmptyGlyph
+ XXX.font.glyphs.package-info
- XXX.font.glyphs.SpecialGlyphs
+ XXX.font.glyphs.SpecialGlyphs$1
- XXX.font.glyphs.SpecialGlyphs$PixelProvider
+ XXX.font.providers.BitmapProvider
- XXX.font.providers.BitmapProvider$Definition
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.BitmapProvider$Glyph$1
+ XXX.font.providers.FreeTypeUtil
- XXX.font.providers.GlyphProviderDefinition
+ XXX.font.providers.GlyphProviderDefinition$Conditional
- XXX.font.providers.GlyphProviderDefinition$Loader
+ XXX.font.providers.GlyphProviderDefinition$Reference
- XXX.font.providers.GlyphProviderType
+ XXX.font.providers.package-info
+ XXX.font.providers.ProviderReferenceDefinition
- XXX.font.providers.TrueTypeGlyphProviderDefinition
+ XXX.font.providers.TrueTypeGlyphProviderDefinition$Shift
- XXX.font.providers.UnihexProvider
+ XXX.font.providers.UnihexProvider$ByteContents
- XXX.font.providers.UnihexProvider$Definition
+ XXX.font.providers.UnihexProvider$Dimensions
- XXX.font.providers.UnihexProvider$Glyph
+ XXX.font.providers.UnihexProvider$Glyph$1
- XXX.font.providers.UnihexProvider$IntContents
+ XXX.font.providers.UnihexProvider$LineData
- XXX.font.providers.UnihexProvider$OverrideRange
+ XXX.font.providers.UnihexProvider$ReaderOutput
- XXX.font.providers.UnihexProvider$ShortContents
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gameevent.vibrations.VibrationSystem
- XXX.gameevent.vibrations.VibrationSystem$Data
+ XXX.gameevent.vibrations.VibrationSystem$Listener
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.gameevent.vibrations.VibrationSystem$User
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTicker$State
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.GeneratedTest
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.RetryOptions
+ XXX.gametest.framework.StructureGridSpawner
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestBatchSummaryDisplayer
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestData
- XXX.gametest.framework.TestEnvironmentDefinition
+ XXX.gametest.framework.TestEnvironmentDefinition$AllOf
- XXX.gametest.framework.TestEnvironmentDefinition$Functions
+ XXX.gametest.framework.TestEnvironmentDefinition$SetGameRules
- XXX.gametest.framework.TestEnvironmentDefinition$SetGameRules$Entry
+ XXX.gametest.framework.TestEnvironmentDefinition$TimeOfDay
- XXX.gametest.framework.TestEnvironmentDefinition$Weather
+ XXX.gametest.framework.TestEnvironmentDefinition$Weather$Type
- XXX.gametest.framework.TestFinder
+ XXX.gametest.framework.TestFinder$Builder
- XXX.gametest.framework.TestFunctionLoader
+ XXX.gametest.framework.TestInstanceFinder
- XXX.gametest.framework.TestPosFinder
+ XXX.gametest.framework.TestReporter
- XXX.gametest.framework.UnknownGameTestException
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractContainerWidget
+ XXX.gui.components.AbstractOptionSliderButton
- XXX.gui.components.AbstractScrollArea
+ XXX.gui.components.AbstractSelectionList
- XXX.gui.components.AbstractSelectionList$1
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$TrackedList
+ XXX.gui.components.AbstractSliderButton
- XXX.gui.components.AbstractStringWidget
+ XXX.gui.components.AbstractTextAreaWidget
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.BossHealthOverlay$1
+ XXX.gui.components.Button
- XXX.gui.components.Button$Builder
+ XXX.gui.components.Button$CreateNarration
- XXX.gui.components.Button$OnPress
+ XXX.gui.components.ChatComponent
- XXX.gui.components.ChatComponent$DelayedMessageDeletion
+ XXX.gui.components.ChatComponent$LineConsumer
- XXX.gui.components.ChatComponent$State
+ XXX.gui.components.Checkbox
- XXX.gui.components.Checkbox$Builder
+ XXX.gui.components.Checkbox$OnValueChange
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.CommonButtons
+ XXX.gui.components.ComponentRenderUtils
- XXX.gui.components.ContainerObjectSelectionList
+ XXX.gui.components.ContainerObjectSelectionList$1
- XXX.gui.components.ContainerObjectSelectionList$Entry
+ XXX.gui.components.CycleButton
- XXX.gui.components.CycleButton$Builder
+ XXX.gui.components.CycleButton$OnValueChange
- XXX.gui.components.CycleButton$ValueListSupplier
+ XXX.gui.components.CycleButton$ValueListSupplier$1
- XXX.gui.components.CycleButton$ValueListSupplier$2
+ XXX.gui.components.DebugScreenOverlay
- XXX.gui.components.DebugScreenOverlay$1
+ XXX.gui.components.DebugScreenOverlay$AllocationRateCalculator
- XXX.gui.font.FontManager$CachedFontProvider
+ XXX.gui.font.FontManager$FontDefinitionFile
- XXX.gui.font.FontManager$Preparation
+ XXX.gui.font.FontManager$UnresolvedBuilderBundle
- XXX.gui.font.FontOption
+ XXX.gui.font.FontOption$Filter
- XXX.gui.font.FontSet
+ XXX.gui.font.FontSet$GlyphInfoFilter
- XXX.gui.font.FontSet$SelectedGlyphs
- XXX.gui.font.FontTexture
+ XXX.gui.font.FontTexture$Node
- XXX.gui.font.GlyphRenderTypes
+ XXX.gui.font.GlyphRenderTypes$1
- XXX.gui.font.GlyphStitcher
- XXX.gui.font.package-info
- XXX.gui.layouts.AbstractLayout
+ XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
- XXX.gui.layouts.CommonLayouts
+ XXX.gui.layouts.EqualSpacingLayout
- XXX.gui.layouts.EqualSpacingLayout$ChildContainer
+ XXX.gui.layouts.EqualSpacingLayout$Orientation
- XXX.gui.layouts.FrameLayout
+ XXX.gui.layouts.FrameLayout$ChildContainer
- XXX.gui.layouts.GridLayout
+ XXX.gui.layouts.GridLayout$CellInhabitant
- XXX.gui.layouts.GridLayout$RowHelper
+ XXX.gui.layouts.HeaderAndFooterLayout
- XXX.gui.layouts.Layout
+ XXX.gui.layouts.LayoutElement
- XXX.gui.layouts.LayoutSettings
+ XXX.gui.layouts.LayoutSettings$LayoutSettingsImpl
- XXX.gui.layouts.LinearLayout
+ XXX.gui.layouts.LinearLayout$Orientation
+ XXX.gui.layouts.package-info
- XXX.gui.layouts.SpacerElement
- XXX.gui.narration.NarratableEntry
+ XXX.gui.narration.NarratableEntry$NarrationPriority
- XXX.gui.narration.NarratedElementType
+ XXX.gui.narration.NarrationElementOutput
- XXX.gui.narration.NarrationSupplier
+ XXX.gui.narration.NarrationThunk
+ XXX.gui.narration.package-info
- XXX.gui.narration.ScreenNarrationCollector
+ XXX.gui.narration.ScreenNarrationCollector$1
- XXX.gui.narration.ScreenNarrationCollector$EntryKey
+ XXX.gui.narration.ScreenNarrationCollector$NarrationEntry
- XXX.gui.narration.ScreenNarrationCollector$Output
- XXX.gui.navigation.CommonInputs
+ XXX.gui.navigation.FocusNavigationEvent
- XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
+ XXX.gui.navigation.FocusNavigationEvent$InitialFocus
- XXX.gui.navigation.FocusNavigationEvent$TabNavigation
+ XXX.gui.navigation.package-info
+ XXX.gui.navigation.ScreenAxis
- XXX.gui.navigation.ScreenDirection
+ XXX.gui.navigation.ScreenPosition
- XXX.gui.navigation.ScreenPosition$1
+ XXX.gui.navigation.ScreenRectangle
- XXX.gui.navigation.ScreenRectangle$1
+ XXX.gui.render.GuiRenderer
- XXX.gui.render.GuiRenderer$1
+ XXX.gui.render.GuiRenderer$AtlasPosition
- XXX.gui.render.GuiRenderer$Draw
+ XXX.gui.render.GuiRenderer$MeshToDraw
+ XXX.gui.render.package-info
- XXX.gui.render.TextureSetup
+ XXX.gui.screens.AccessibilityOnboardingScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.BanNoticeScreens
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.ConnectScreen$2
+ XXX.gui.screens.CreateBuffetWorldScreen
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ XXX.gui.screens.CreditsAndAttributionScreen
- XXX.gui.screens.DatapackLoadFailureScreen
+ XXX.gui.screens.DeathScreen
- XXX.gui.screens.DeathScreen$TitleConfirmScreen
+ XXX.gui.screens.DemoIntroScreen
- XXX.gui.screens.DirectJoinServerScreen
+ XXX.gui.screens.DisconnectedScreen
- XXX.gui.screens.EditServerScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.FaviconTexture
+ XXX.gui.screens.GenericMessageScreen
- XXX.gui.screens.GenericWaitingScreen
+ XXX.gui.screens.InBedChatScreen
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.Bees
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BlocksAttacks
+ XXX.item.component.BlocksAttacks$DamageReduction
- XXX.item.component.BlocksAttacks$ItemDamageFunction
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
+ XXX.item.component.Consumable
- XXX.item.component.Consumable$Builder
+ XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.ConsumableListener
+ XXX.item.component.Consumables
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
- XXX.item.component.DamageResistant
+ XXX.item.component.DeathProtection
- XXX.item.component.DebugStickState
+ XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion
+ XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.Fireworks
+ XXX.item.component.InstrumentComponent
- XXX.item.component.ItemAttributeModifiers
+ XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Builder
+ XXX.item.component.ItemAttributeModifiers$Display
- XXX.item.component.ItemAttributeModifiers$Display$Default
+ XXX.item.component.ItemAttributeModifiers$Display$Hidden
- XXX.item.component.ItemAttributeModifiers$Display$OverrideText
+ XXX.item.component.ItemAttributeModifiers$Display$Type
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
+ XXX.item.component.package-info
- XXX.item.component.ProvidesTrimMaterial
+ XXX.item.component.ResolvableProfile
- XXX.item.component.ResolvableProfile$Resolver
- XXX.item.component.ResolvableProfile$Resolver$2
- XXX.item.component.TypedEntityData
+ XXX.item.component.UseCooldown
- XXX.item.component.UseRemainder
+ XXX.item.component.UseRemainder$OnExtraCreatedRemainder
- XXX.item.component.Weapon
+ XXX.item.component.WritableBookContent
- XXX.item.component.WrittenBookContent
- XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
- XXX.item.consume_effects.ConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect$Type
+ XXX.item.consume_effects.package-info
- XXX.item.consume_effects.PlaySoundConsumeEffect
+ XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
- XXX.item.consume_effects.TeleportRandomlyConsumeEffect
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.AbstractCookingRecipe$Factory
+ XXX.item.crafting.AbstractCookingRecipe$Serializer
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BlastingRecipe$1
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingInput
+ XXX.item.crafting.CraftingInput$Positioned
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CraftingRecipe$1
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.CustomRecipe$Serializer
- XXX.item.crafting.CustomRecipe$Serializer$Factory
+ XXX.item.crafting.DecoratedPotRecipe
- XXX.item.crafting.ExtendedRecipeBookCategory
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
+ XXX.item.crafting.PlacementInfo
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeAccess
- XXX.item.crafting.RecipeBookCategories
+ XXX.item.crafting.RecipeBookCategory
- XXX.item.crafting.RecipeCache
+ XXX.item.crafting.RecipeCache$Entry
- XXX.item.crafting.RecipeHolder
+ XXX.item.crafting.RecipeInput
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeManager$1
- XXX.item.crafting.RecipeManager$CachedCheck
+ XXX.item.crafting.RecipeManager$IngredientCollector
- XXX.item.crafting.RecipeManager$IngredientExtractor
+ XXX.item.crafting.RecipeManager$ServerDisplayInfo
- XXX.item.crafting.RecipeMap
+ XXX.item.crafting.RecipePropertySet
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.SelectableRecipe
+ XXX.item.crafting.SelectableRecipe$SingleInputEntry
- XXX.item.crafting.SelectableRecipe$SingleInputSet
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapedRecipePattern
- XXX.item.crafting.ShapedRecipePattern$Data
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Factory
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleRecipeInput
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmeltingRecipe$1
- XXX.item.crafting.SmithingRecipe
+ XXX.item.crafting.SmithingRecipeInput
- XXX.item.crafting.SmithingTransformRecipe
+ XXX.item.crafting.SmithingTransformRecipe$Serializer
- XXX.item.crafting.SmithingTrimRecipe
+ XXX.item.crafting.SmithingTrimRecipe$Serializer
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.TippedArrowRecipe
+ XXX.item.crafting.TransmuteRecipe
- XXX.item.crafting.TransmuteRecipe$Serializer
+ XXX.item.crafting.TransmuteResult
- XXX.item.enchantment.ConditionalEffect
+ XXX.item.enchantment.Enchantable
- XXX.item.enchantment.EnchantedItemInUse
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$1
+ XXX.item.enchantment.Enchantment$Builder
- XXX.item.enchantment.Enchantment$Cost
+ XXX.item.enchantment.Enchantment$EnchantmentDefinition
- XXX.item.enchantment.EnchantmentEffectComponents
+ XXX.item.enchantment.EnchantmentHelper
- XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
- XXX.item.enchantment.Enchantments
+ XXX.item.enchantment.EnchantmentTarget
+ XXX.item.enchantment.ItemEnchantments
- XXX.item.enchantment.ItemEnchantments$Mutable
+ XXX.item.enchantment.LevelBasedValue
- XXX.item.enchantment.LevelBasedValue$Clamped
+ XXX.item.enchantment.LevelBasedValue$Constant
- XXX.item.enchantment.LevelBasedValue$Fraction
+ XXX.item.enchantment.LevelBasedValue$LevelsSquared
- XXX.item.enchantment.LevelBasedValue$Linear
+ XXX.item.enchantment.LevelBasedValue$Lookup
- XXX.item.enchantment.package-info
- XXX.item.enchantment.Repairable
+ XXX.item.enchantment.TargetedConditionalEffect
+ XXX.item.equipment.AllowedEntitiesProvider
- XXX.item.equipment.ArmorMaterial
+ XXX.item.equipment.ArmorMaterials
- XXX.item.equipment.ArmorType
+ XXX.item.equipment.EquipmentAsset
- XXX.item.equipment.EquipmentAssets
+ XXX.item.equipment.Equippable
- XXX.item.equipment.Equippable$Builder
+ XXX.item.equipment.package-info
+ XXX.item.trading.ItemCost
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.ColoredFallingBlock
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CopperBulbBlock
- XXX.level.block.CopperChestBlock
- XXX.level.block.CopperGolemStatueBlock$Pose
- XXX.level.block.SelectableSlotContainer
- XXX.level.block.ShelfBlock
+ XXX.level.block.ShortDryGrassBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SideChainPartBlock
- XXX.level.block.SideChainPartBlock$Neighbor
- XXX.level.block.SideChainPartBlock$SideChainNeighbor
- XXX.level.block.WeatheringCopperDoorBlock
+ XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringCopperGolemStatueBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVinesBlock
- XXX.level.block.WeepingVinesPlantBlock
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
- XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$DistancePerDirection
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$ChunkPathElement
+ XXX.level.chunk.ChunkAccess$PackedTicks
- XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGenerators
+ XXX.level.chunk.ChunkGeneratorStructureState
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunk$PostLoadProcessor
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunk$UnsavedListener
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LevelChunkSection$1BlockCounter
- XXX.level.chunk.LightChunk
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.MissingPaletteEntryException
- XXX.level.chunk.package-info
- XXX.level.chunk.Palette
+ XXX.level.chunk.Palette$Factory
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$Configuration
+ XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PalettedContainer$Data
+ XXX.level.chunk.PalettedContainer$Strategy
- XXX.level.chunk.PalettedContainer$Strategy$1
+ XXX.level.chunk.PalettedContainer$Strategy$2
- XXX.level.chunk.PalettedContainerRO
+ XXX.level.chunk.PalettedContainerRO$PackedData
- XXX.level.chunk.PalettedContainerRO$Unpacker
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.SingleValuePalette
+ XXX.level.chunk.StructureAccess
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
+ XXX.level.dimension.BuiltinDimensionTypes
- XXX.level.dimension.DimensionDefaults
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.DimensionType$MonsterSettings
+ XXX.level.dimension.LevelStem
+ XXX.level.dimension.package-info
- XXX.level.entity.ChunkEntities
+ XXX.level.entity.ChunkStatusUpdateListener
- XXX.level.entity.EntityAccess
+ XXX.level.entity.EntityInLevelCallback
- XXX.level.entity.EntityInLevelCallback$1
+ XXX.level.entity.EntityLookup
- XXX.level.entity.EntityPersistentStorage
+ XXX.level.entity.EntitySection
- XXX.level.entity.EntitySectionStorage
+ XXX.level.entity.EntityTickList
- XXX.level.entity.EntityTypeTest
+ XXX.level.entity.EntityTypeTest$1
- XXX.level.entity.EntityTypeTest$2
+ XXX.level.entity.LevelCallback
- XXX.level.entity.LevelEntityGetter
+ XXX.level.entity.LevelEntityGetterAdapter
- XXX.level.entity.package-info
- XXX.level.entity.PersistentEntitySectionManager
+ XXX.level.entity.PersistentEntitySectionManager$Callback
- XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ XXX.level.entity.TransientEntitySectionManager
- XXX.level.entity.TransientEntitySectionManager$Callback
- XXX.level.entity.UniquelyIdentifyable
+ XXX.level.entity.UUIDLookup
+ XXX.level.entity.Visibility
+ XXX.level.gameevent.BlockPositionSource
- XXX.level.gameevent.BlockPositionSource$Type
+ XXX.level.gameevent.DynamicGameEventListener
- XXX.level.gameevent.EntityPositionSource
+ XXX.level.gameevent.EntityPositionSource$Type
- XXX.level.gameevent.EuclideanGameEventListenerRegistry
+ XXX.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
- XXX.level.gameevent.GameEvent
+ XXX.level.gameevent.GameEvent$Context
- XXX.level.gameevent.GameEvent$ListenerInfo
+ XXX.level.gameevent.GameEventDispatcher
- XXX.level.gameevent.GameEventListener
+ XXX.level.gameevent.GameEventListener$DeliveryMode
- XXX.level.gameevent.GameEventListener$Provider
+ XXX.level.gameevent.GameEventListenerRegistry
- XXX.level.gameevent.GameEventListenerRegistry$1
+ XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- XXX.level.gameevent.package-info
- XXX.level.gameevent.PositionSource
+ XXX.level.gameevent.PositionSourceType
+ XXX.level.levelgen.Aquifer
- XXX.level.levelgen.Aquifer$1
+ XXX.level.levelgen.Aquifer$FluidPicker
- XXX.level.levelgen.Aquifer$FluidStatus
+ XXX.level.levelgen.Aquifer$NoiseBasedAquifer
- XXX.level.levelgen.Beardifier
+ XXX.level.levelgen.Beardifier$1
- XXX.level.levelgen.Beardifier$Rigid
+ XXX.level.levelgen.BelowZeroRetrogen
- XXX.level.levelgen.BelowZeroRetrogen$1
+ XXX.level.levelgen.BitRandomSource
- XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Line
- XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.Column$Ray
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.Density
- XXX.level.levelgen.DensityFunction
+ XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$FunctionContext
+ XXX.level.levelgen.DensityFunction$NoiseHolder
- XXX.level.levelgen.DensityFunction$SimpleFunction
+ XXX.level.levelgen.DensityFunction$SinglePointContext
- XXX.level.levelgen.DensityFunction$Visitor
+ XXX.level.levelgen.DensityFunctions
- XXX.level.levelgen.DensityFunctions$Ap2
+ XXX.level.levelgen.DensityFunctions$BeardifierMarker
- XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
+ XXX.level.levelgen.DensityFunctions$BlendAlpha
- XXX.level.levelgen.DensityFunctions$BlendDensity
+ XXX.level.levelgen.DensityFunctions$BlendOffset
- XXX.level.levelgen.DensityFunctions$Clamp
+ XXX.level.levelgen.DensityFunctions$Constant
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.ChunkSkyLightSources
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$SectionState
+ XXX.level.lighting.LayerLightSectionStorage$SectionType
+ XXX.level.lighting.LeveledPriorityQueue
- XXX.level.lighting.LeveledPriorityQueue$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEngine
- XXX.level.lighting.LightEngine$QueueEntry
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightEngine$1
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.FlowingFluid$BlockStatePairKey
+ XXX.level.material.FlowingFluid$SpreadContext
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.MapColor
- XXX.level.material.MapColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.Path$DebugData
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.PathfindingContext
- XXX.level.pathfinder.PathType
+ XXX.level.pathfinder.PathTypeCache
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.pathfinder.WalkNodeEvaluator$1
- XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalShape
- XXX.level.portal.TeleportTransition
+ XXX.level.portal.TeleportTransition$PostTeleportTransition
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.LevelLoadListener
- XXX.level.progress.LevelLoadListener$Stage
- XXX.level.progress.LevelLoadProgressTracker$1
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.LoggingLevelLoadListener$1
+ XXX.level.progress.StoringChunkProgressListener
+ XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ XXX.level.redstone.DefaultRedstoneWireEvaluator
- XXX.level.redstone.ExperimentalRedstoneUtils
+ XXX.level.redstone.ExperimentalRedstoneWireEvaluator
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.Orientation
+ XXX.level.redstone.Orientation$SideBias
- XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.redstone.RedstoneWireEvaluator
+ XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedData$Context
+ XXX.level.saveddata.SavedDataType
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.FileNameDateFormatter
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelDataAndDimensions
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelSummary$CorruptedLevelSummary
+ XXX.level.storage.LevelSummary$SymlinkLevelSummary
- XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.TagValueInput
- XXX.level.storage.TagValueInput$CompoundListWrapper
+ XXX.level.storage.TagValueInput$CompoundListWrapper$1
- XXX.level.storage.TagValueInput$DecodeFromFieldFailedProblem
+ XXX.level.storage.TagValueInput$DecodeFromListFailedProblem
- XXX.level.storage.TagValueInput$DecodeFromMapFailedProblem
+ XXX.level.storage.TagValueInput$ListWrapper
- XXX.level.storage.TagValueInput$ListWrapper$1
+ XXX.level.storage.TagValueInput$TypedListWrapper
- XXX.level.storage.TagValueInput$TypedListWrapper$1
+ XXX.level.storage.TagValueInput$UnexpectedListElementTypeProblem
- XXX.level.storage.TagValueInput$UnexpectedNonNumberProblem
+ XXX.level.storage.TagValueInput$UnexpectedTypeProblem
- XXX.level.storage.TagValueOutput
+ XXX.level.storage.TagValueOutput$EncodeToFieldFailedProblem
- XXX.level.storage.TagValueOutput$EncodeToListFailedProblem
+ XXX.level.storage.TagValueOutput$EncodeToMapFailedProblem
- XXX.level.storage.TagValueOutput$ListWrapper
+ XXX.level.storage.TagValueOutput$TypedListWrapper
- XXX.level.storage.ValueInput
+ XXX.level.storage.ValueInput$TypedInputList
- XXX.level.storage.ValueInput$ValueInputList
+ XXX.level.storage.ValueInputContextHelper
- XXX.level.storage.ValueInputContextHelper$1
+ XXX.level.storage.ValueInputContextHelper$2
- XXX.level.storage.ValueInputContextHelper$3
+ XXX.level.storage.ValueOutput
- XXX.level.storage.ValueOutput$TypedOutputList
+ XXX.level.storage.ValueOutput$ValueOutputList
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$Event
+ XXX.level.validation.ContentValidationException
- XXX.level.validation.DirectoryValidator
+ XXX.level.validation.DirectoryValidator$1
- XXX.level.validation.ForbiddenSymlinkInfo
- XXX.level.validation.package-info
+ XXX.level.validation.PathAllowList
- XXX.level.validation.PathAllowList$ConfigEntry
+ XXX.level.validation.PathAllowList$EntryType
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.login.custom.CustomQueryAnswerPayload
- XXX.login.custom.CustomQueryPayload
+ XXX.login.custom.DiscardedQueryAnswerPayload
- XXX.login.custom.DiscardedQueryPayload
+ XXX.login.custom.package-info
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$1
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.NestedLootTable
- XXX.loot.entries.NestedLootTable$1
+ XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaType
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyComponentsFunction
- XXX.loot.functions.CopyComponentsFunction$Builder
+ XXX.loot.functions.CopyComponentsFunction$Source
- XXX.loot.functions.CopyCustomDataFunction
+ XXX.loot.functions.CopyCustomDataFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction$CopyOperation
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.EnchantedCountIncreaseFunction
- XXX.loot.functions.EnchantedCountIncreaseFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FilteredFunction
+ XXX.loot.functions.FunctionReference
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.ListOperation
+ XXX.loot.functions.ListOperation$Append
- XXX.loot.functions.ListOperation$Insert
+ XXX.loot.functions.ListOperation$ReplaceAll
- XXX.loot.functions.ListOperation$ReplaceSection
+ XXX.loot.functions.ListOperation$StandAlone
- XXX.loot.functions.ListOperation$Type
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.ModifyContainerContents
- XXX.loot.functions.package-info
+ XXX.loot.functions.SequenceFunction
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetBookCoverFunction
+ XXX.loot.functions.SetComponentsFunction
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetCustomDataFunction
- XXX.loot.functions.SetCustomModelDataFunction
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetFireworkExplosionFunction
- XXX.loot.functions.SetFireworksFunction
+ XXX.loot.functions.SetInstrumentFunction
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemFunction
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$Target
+ XXX.loot.functions.SetOminousBottleAmplifierFunction
- XXX.loot.functions.SetPotionFunction
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$EffectEntry
- XXX.loot.functions.SetWritableBookPagesFunction
+ XXX.loot.functions.SetWrittenBookPagesFunction
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.ToggleTooltips
- XXX.loot.packs.VanillaBlockInteractLoot
+ XXX.loot.packs.VanillaBlockLoot
- XXX.loot.packs.VanillaChargedCreeperExplosionLoot
- XXX.loot.packs.VanillaChestLoot
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AllOfCondition
- XXX.loot.predicates.AllOfCondition$Builder
+ XXX.loot.predicates.AnyOfCondition
- XXX.loot.predicates.AnyOfCondition$Builder
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.CompositeLootItemCondition
+ XXX.loot.predicates.CompositeLootItemCondition$Builder
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.EnchantmentActiveCheck
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceWithEnchantedBonusCondition
+ XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
- XXX.metadata.animation.AnimationFrame
+ XXX.metadata.animation.AnimationMetadataSection
- XXX.metadata.animation.FrameSize
+ XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetadataSection
- XXX.metadata.animation.VillagerMetadataSection$Hat
- XXX.metadata.gui.GuiMetadataSection
+ XXX.metadata.gui.GuiSpriteScaling
- XXX.metadata.gui.GuiSpriteScaling$NineSlice
+ XXX.metadata.gui.GuiSpriteScaling$NineSlice$Border
- XXX.metadata.gui.GuiSpriteScaling$Stretch
+ XXX.metadata.gui.GuiSpriteScaling$Tile
- XXX.metadata.gui.GuiSpriteScaling$Type
+ XXX.metadata.gui.package-info
- XXX.metadata.language.LanguageMetadataSection
+ XXX.metadata.language.package-info
- XXX.metadata.pack.PackFormat
- XXX.metadata.pack.PackFormat$IntermediaryFormat
- XXX.metadata.pack.PackMetadataSection
- XXX.metadata.texture.package-info
+ XXX.metadata.texture.TextureMetadataSection
- XXX.minecraft.client.package-info
- XXX.minecraft.locale.DeprecatedTranslationsInfo
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.Language$1
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CollectionTag$1
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.CompoundTag$2
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
+ XXX.minecraft.nbt.ListTag$2
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounterException
+ XXX.minecraft.nbt.NbtException
- XXX.minecraft.nbt.NbtFormatException
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
+ XXX.minecraft.nbt.NbtOps$GenericListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.PrimitiveTag
+ XXX.minecraft.nbt.ReportedNbtException
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtGrammar
- XXX.minecraft.nbt.SnbtGrammar$1
+ XXX.minecraft.nbt.SnbtGrammar$2
- XXX.minecraft.nbt.SnbtGrammar$3
+ XXX.minecraft.nbt.SnbtGrammar$4
- XXX.minecraft.nbt.SnbtGrammar$5
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$1
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$2
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$3
+ XXX.minecraft.nbt.SnbtGrammar$Base
- XXX.minecraft.nbt.SnbtGrammar$IntegerLiteral
+ XXX.minecraft.nbt.SnbtGrammar$IntegerSuffix
- XXX.minecraft.nbt.SnbtGrammar$Sign
+ XXX.minecraft.nbt.SnbtGrammar$Signed
- XXX.minecraft.nbt.SnbtGrammar$SignedPrefix
+ XXX.minecraft.nbt.SnbtGrammar$SimpleHexLiteralParseRule
- XXX.minecraft.nbt.SnbtGrammar$TypeSuffix
+ XXX.minecraft.nbt.SnbtOperations
- XXX.minecraft.nbt.SnbtOperations$1
+ XXX.minecraft.nbt.SnbtOperations$2
- XXX.minecraft.nbt.SnbtOperations$3
+ XXX.minecraft.nbt.SnbtOperations$BuiltinKey
- XXX.minecraft.nbt.SnbtOperations$BuiltinOperation
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor$EntryResult
- XXX.minecraft.nbt.StreamTagVisitor$ValueResult
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.StringTagVisitor
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagType$2
+ XXX.minecraft.nbt.TagType$StaticSize
- XXX.minecraft.nbt.TagType$VariableSize
+ XXX.minecraft.nbt.TagTypes
- XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.nbt.TextComponentTagVisitor
+ XXX.minecraft.network.BandwidthDebugMonitor
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.ClientboundPacketListener
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$3
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.DisconnectionDetails
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.HandlerNames
- XXX.minecraft.network.HashedPatchMap
+ XXX.minecraft.network.HashedPatchMap$HashGenerator
- XXX.minecraft.network.HashedStack
+ XXX.minecraft.network.HashedStack$1
- XXX.minecraft.network.HashedStack$ActualItem
+ XXX.minecraft.network.HiddenByteBuf
- XXX.minecraft.network.LocalFrameDecoder
+ XXX.minecraft.network.LocalFrameEncoder
- XXX.minecraft.network.MonitoredLocalFrameDecoder
- XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketBundlePacker
- XXX.minecraft.network.PacketBundleUnpacker
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.PacketSendListener
+ XXX.minecraft.network.ProtocolInfo
- XXX.minecraft.network.ProtocolInfo$Details
+ XXX.minecraft.network.ProtocolInfo$Details$PacketVisitor
- XXX.minecraft.network.ProtocolInfo$DetailsProvider
+ XXX.minecraft.network.ProtocolSwapHandler
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.RegistryFriendlyByteBuf
- XXX.minecraft.network.ServerboundPacketListener
+ XXX.minecraft.network.SkipPacketDecoderException
- XXX.minecraft.network.SkipPacketEncoderException
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.TickablePacketListener
+ XXX.minecraft.network.UnconfiguredPipelineHandler
- XXX.minecraft.network.UnconfiguredPipelineHandler$Inbound
+ XXX.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
- XXX.minecraft.network.UnconfiguredPipelineHandler$Outbound
+ XXX.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
- XXX.minecraft.network.Utf8String
+ XXX.minecraft.network.VarInt
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.network.VarLong
+ XXX.minecraft.obfuscate.DontObfuscate
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsConnect
+ XXX.minecraft.realms.RealmsConnect$1
- XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipeHelper
- XXX.minecraft.recipebook.PlaceRecipeHelper$Output
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe$CraftingMenuAccess
- XXX.minecraft.references.Blocks
+ XXX.minecraft.references.Items
- XXX.minecraft.references.package-info
+ XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.DelegatingOps$DelegateListBuilder
+ XXX.minecraft.resources.DelegatingOps$DelegateRecordBuilder
- XXX.minecraft.resources.DependantName
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
- XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$LoadingFunction
+ XXX.minecraft.resources.RegistryDataLoader$NetworkedRegistryData
- XXX.minecraft.resources.RegistryDataLoader$RegistryData
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryOps
- XXX.minecraft.resources.RegistryOps$HolderLookupAdapter
+ XXX.minecraft.resources.RegistryOps$RegistryInfo
- XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
+ XXX.minecraft.resources.ResourceKey
- XXX.minecraft.resources.ResourceKey$InternKey
+ XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.Main
- XXX.minecraft.server.Main$1
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.util.NullOps$1
+ XXX.minecraft.util.NullOps$NullListBuilder
- XXX.minecraft.util.NullOps$NullMapBuilder
+ XXX.minecraft.util.OptionEnum
- XXX.minecraft.util.ParticleUtils
+ XXX.minecraft.util.PlaceholderLookupProvider
- XXX.minecraft.util.PlaceholderLookupProvider$1
+ XXX.minecraft.util.PlaceholderLookupProvider$2
- XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
+ XXX.minecraft.util.PngInfo
- XXX.minecraft.util.ProblemReporter
+ XXX.minecraft.util.ProblemReporter$1
- XXX.minecraft.util.ProblemReporter$Collector
+ XXX.minecraft.util.ProblemReporter$Collector$Entry
- XXX.minecraft.util.ProblemReporter$Collector$ProblemTreeNode
+ XXX.minecraft.util.ProblemReporter$ElementReferencePathElement
- XXX.minecraft.util.ProblemReporter$FieldPathElement
+ XXX.minecraft.util.ProblemReporter$IndexedFieldPathElement
- XXX.minecraft.util.ProblemReporter$IndexedPathElement
+ XXX.minecraft.util.ProblemReporter$PathElement
- XXX.minecraft.util.ProblemReporter$Problem
+ XXX.minecraft.util.ProblemReporter$RootElementPathElement
- XXX.minecraft.util.ProblemReporter$RootFieldPathElement
+ XXX.minecraft.util.ProblemReporter$ScopedCollector
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RandomSource
- XXX.minecraft.util.RegistryContextSwapper
+ XXX.minecraft.util.ResourceLocationPattern
- XXX.minecraft.util.SegmentedAnglePrecision
+ XXX.minecraft.util.SequencedPriorityIterator
- XXX.minecraft.util.SignatureUpdater
+ XXX.minecraft.util.SignatureUpdater$Output
- XXX.minecraft.util.SignatureValidator
+ XXX.minecraft.util.Signer
- XXX.minecraft.util.SimpleBitStorage
+ XXX.minecraft.util.SimpleBitStorage$InitializationException
- XXX.minecraft.util.SingleKeyCache
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.SpawnUtil
+ XXX.minecraft.util.SpawnUtil$Strategy
- XXX.minecraft.util.StaticCache2D
+ XXX.minecraft.util.StaticCache2D$Initializer
- XXX.minecraft.util.StrictJsonParser
+ XXX.minecraft.util.StringDecomposer
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$EnumCodec
+ XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TaskChainer
- XXX.minecraft.util.TaskChainer$1
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TickThrottler
+ XXX.minecraft.util.TimeSource
- XXX.minecraft.util.TimeSource$NanoTimeSource
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.ToFloatFunction
+ XXX.minecraft.util.ToFloatFunction$1
- XXX.minecraft.util.ToFloatFunction$2
+ XXX.minecraft.util.TriState
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.world.package-info
- XXX.monster.breeze.Breeze
+ XXX.monster.breeze.Breeze$1
- XXX.monster.breeze.BreezeAi
+ XXX.monster.breeze.BreezeAi$SlideToTargetSink
- XXX.monster.breeze.BreezeUtil
+ XXX.monster.breeze.LongJump
+ XXX.monster.breeze.package-info
- XXX.monster.breeze.Shoot
+ XXX.monster.breeze.ShootWhenStuck
- XXX.monster.breeze.Slide
- XXX.monster.creaking.Creaking
+ XXX.monster.creaking.Creaking$CreakingBodyRotationControl
- XXX.monster.creaking.Creaking$CreakingJumpControl
+ XXX.monster.creaking.Creaking$CreakingLookControl
- XXX.monster.creaking.Creaking$CreakingMoveControl
+ XXX.monster.creaking.Creaking$CreakingPathNavigation
- XXX.monster.creaking.Creaking$HomeNodeEvaluator
+ XXX.monster.creaking.CreakingAi
- XXX.monster.creaking.CreakingAi$1
+ XXX.monster.creaking.package-info
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.AbstractPiglin
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.PiglinArmPose
+ XXX.monster.piglin.PiglinBrute
- XXX.monster.piglin.PiglinBruteAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- XXX.monster.warden.AngerLevel
+ XXX.monster.warden.AngerManagement
- XXX.monster.warden.AngerManagement$1
+ XXX.monster.warden.AngerManagement$Sorter
+ XXX.monster.warden.package-info
- XXX.monster.warden.Warden
+ XXX.monster.warden.Warden$1
- XXX.monster.warden.Warden$1$1
+ XXX.monster.warden.Warden$2
- XXX.monster.warden.Warden$VibrationUser
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenSpawnTracker
+ XXX.multiplayer.chat.ChatListener
- XXX.multiplayer.chat.ChatListener$Message
+ XXX.multiplayer.chat.ChatLog
- XXX.multiplayer.chat.ChatTrustLevel
+ XXX.multiplayer.chat.LoggedChatEvent
- XXX.multiplayer.chat.LoggedChatEvent$Type
+ XXX.multiplayer.chat.LoggedChatMessage
- XXX.multiplayer.chat.LoggedChatMessage$Player
+ XXX.multiplayer.chat.LoggedChatMessage$System
- XXX.multiplayer.chat.package-info
+ XXX.multiplayer.prediction.BlockStatePredictionHandler
- XXX.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
- XXX.multiplayer.prediction.package-info
+ XXX.multiplayer.prediction.PredictiveAction
+ XXX.multiplayer.resolver.AddressCheck
- XXX.multiplayer.resolver.AddressCheck$1
+ XXX.multiplayer.resolver.package-info
+ XXX.multiplayer.resolver.ResolvedServerAddress
- XXX.multiplayer.resolver.ResolvedServerAddress$1
+ XXX.multiplayer.resolver.ServerAddress
- XXX.multiplayer.resolver.ServerAddressResolver
+ XXX.multiplayer.resolver.ServerNameResolver
- XXX.multiplayer.resolver.ServerRedirectHandler
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.CollectToTag$CompoundBuilder
- XXX.nbt.visitors.CollectToTag$ContainerBuilder
+ XXX.nbt.visitors.CollectToTag$ListBuilder
- XXX.nbt.visitors.CollectToTag$RootBuilder
+ XXX.nbt.visitors.FieldSelector
- XXX.nbt.visitors.FieldTree
- XXX.nbt.visitors.package-info
+ XXX.nbt.visitors.SkipAll
- XXX.nbt.visitors.SkipAll$1
+ XXX.nbt.visitors.SkipFields
+ XXX.network.chat.ChatDecorator
- XXX.network.chat.ChatType
+ XXX.network.chat.ChatType$Bound
- XXX.network.chat.ChatTypeDecoration
+ XXX.network.chat.ChatTypeDecoration$Parameter
- XXX.network.chat.ChatTypeDecoration$Parameter$Selector
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.ClickEvent$ChangePage
- XXX.network.chat.ClickEvent$CopyToClipboard
+ XXX.network.chat.ClickEvent$Custom
- XXX.network.chat.ClickEvent$OpenFile
+ XXX.network.chat.ClickEvent$OpenUrl
- XXX.network.chat.ClickEvent$RunCommand
+ XXX.network.chat.ClickEvent$ShowDialog
- XXX.network.chat.ClickEvent$SuggestCommand
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.ComponentContents
- XXX.network.chat.ComponentContents$Type
+ XXX.network.chat.ComponentSerialization
- XXX.network.chat.ComponentSerialization$1
+ XXX.network.chat.ComponentSerialization$FuzzyCodec
- XXX.network.chat.ComponentSerialization$StrictEither
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
+ XXX.network.chat.FilterMask$Type
- XXX.network.chat.FormattedText
+ XXX.network.chat.FormattedText$1
- XXX.network.chat.FormattedText$2
+ XXX.network.chat.FormattedText$3
- XXX.network.chat.FormattedText$4
+ XXX.network.chat.FormattedText$ContentConsumer
- XXX.network.chat.FormattedText$StyledContentConsumer
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ShowEntity
+ XXX.network.chat.HoverEvent$ShowItem
- XXX.network.chat.HoverEvent$ShowText
+ XXX.network.chat.LastSeenMessages
- XXX.network.chat.LastSeenMessages$Packed
+ XXX.network.chat.LastSeenMessages$Update
- XXX.network.chat.LastSeenMessagesTracker
+ XXX.network.chat.LastSeenMessagesTracker$Update
- XXX.network.chat.LastSeenMessagesValidator
+ XXX.network.chat.LastSeenMessagesValidator$ValidationException
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
+ XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$1
- XXX.network.chat.SignedMessageChain$DecodeException
+ XXX.network.chat.SignedMessageChain$Decoder
- XXX.network.chat.SignedMessageChain$Encoder
+ XXX.network.chat.SignedMessageLink
- XXX.network.chat.SignedMessageValidator
+ XXX.network.chat.SignedMessageValidator$KeyBased
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$1Collector
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.SubStringSource
+ XXX.network.chat.TextColor
- XXX.network.chat.ThrowingComponent
- XXX.network.codec.ByteBufCodecs
+ XXX.network.codec.ByteBufCodecs$1
- XXX.network.codec.ByteBufCodecs$10
+ XXX.network.codec.ByteBufCodecs$11
- XXX.network.codec.ByteBufCodecs$12
+ XXX.network.codec.ByteBufCodecs$13
- XXX.network.codec.ByteBufCodecs$14
+ XXX.network.codec.ByteBufCodecs$15
- XXX.network.codec.ByteBufCodecs$16
+ XXX.network.codec.ByteBufCodecs$17
- XXX.network.codec.ByteBufCodecs$18
+ XXX.network.codec.ByteBufCodecs$19
- XXX.network.codec.ByteBufCodecs$2
+ XXX.network.codec.ByteBufCodecs$20
- XXX.network.codec.ByteBufCodecs$21
+ XXX.network.codec.ByteBufCodecs$22
- XXX.network.codec.ByteBufCodecs$23
+ XXX.network.codec.ByteBufCodecs$24
- XXX.network.codec.ByteBufCodecs$25
+ XXX.network.codec.ByteBufCodecs$26
- XXX.network.codec.ByteBufCodecs$27
+ XXX.network.codec.ByteBufCodecs$28
- XXX.network.codec.ByteBufCodecs$29
+ XXX.network.codec.ByteBufCodecs$3
- XXX.network.codec.ByteBufCodecs$30
+ XXX.network.codec.ByteBufCodecs$31
- XXX.network.codec.ByteBufCodecs$32
+ XXX.network.codec.ByteBufCodecs$33
- XXX.network.codec.ByteBufCodecs$34
+ XXX.network.codec.ByteBufCodecs$35
- XXX.network.codec.ByteBufCodecs$36
+ XXX.network.codec.ByteBufCodecs$4
- XXX.network.codec.ByteBufCodecs$5
+ XXX.network.codec.ByteBufCodecs$6
- XXX.network.codec.ByteBufCodecs$7
+ XXX.network.codec.ByteBufCodecs$8
- XXX.network.codec.ByteBufCodecs$9
+ XXX.network.codec.IdDispatchCodec
- XXX.network.codec.IdDispatchCodec$Builder
+ XXX.network.codec.IdDispatchCodec$DontDecorateException
- XXX.network.codec.IdDispatchCodec$Entry
+ XXX.network.codec.package-info
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
+ XXX.network.codec.StreamCodec$14
- XXX.network.codec.StreamCodec$15
+ XXX.network.codec.StreamCodec$16
- XXX.network.codec.StreamCodec$17
+ XXX.network.codec.StreamCodec$2
- XXX.network.codec.StreamCodec$3
+ XXX.network.codec.StreamCodec$4
- XXX.network.codec.StreamCodec$5
+ XXX.network.codec.StreamCodec$6
- XXX.network.codec.StreamCodec$7
+ XXX.network.codec.StreamCodec$8
- XXX.network.codec.StreamCodec$9
+ XXX.network.codec.StreamCodec$CodecOperation
- XXX.network.codec.StreamDecoder
+ XXX.network.codec.StreamEncoder
- XXX.network.codec.StreamMemberEncoder
- XXX.network.config.PrepareSpawnTask$Preparing
- XXX.network.config.PrepareSpawnTask$State
+ XXX.network.protocol.BundleDelimiterPacket
- XXX.network.protocol.BundlePacket
+ XXX.network.protocol.BundlerInfo
- XXX.network.protocol.BundlerInfo$1
+ XXX.network.protocol.BundlerInfo$1$1
- XXX.network.protocol.BundlerInfo$Bundler
+ XXX.network.protocol.CodecModifier
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketType
+ XXX.network.protocol.PacketUtils
- XXX.network.protocol.ProtocolCodecBuilder
+ XXX.network.protocol.ProtocolInfoBuilder
- XXX.network.protocol.ProtocolInfoBuilder$1
+ XXX.network.protocol.ProtocolInfoBuilder$2
- XXX.network.protocol.ProtocolInfoBuilder$3
+ XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
- XXX.network.protocol.ProtocolInfoBuilder$Implementation
+ XXX.network.protocol.SimpleUnboundProtocol
- XXX.network.protocol.UnboundProtocol
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.package-info
+ XXX.network.syncher.SyncedDataHolder
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$Builder
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.network.syncher.SynchedEntityData$DataValue
- XXX.packs.resources.PreparableReloadListener$StateKey
+ XXX.packs.resources.ResourceMetadata$Builder$1
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
+ XXX.phys.shapes.MinecartCollisionContext
- XXX.phys.shapes.MinecartCollisionContext$1
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
+ XXX.player.inventory.Hotbar
- XXX.player.inventory.package-info
+ XXX.projectile.windcharge.AbstractWindCharge
- XXX.projectile.windcharge.BreezeWindCharge
- XXX.projectile.windcharge.package-info
+ XXX.projectile.windcharge.WindCharge
- XXX.protocol.common.ClientboundClearDialogPacket
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundCustomReportDetailsPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundServerLinksPacket
+ XXX.protocol.common.ClientboundShowDialogPacket
- XXX.protocol.common.ClientboundStoreCookiePacket
+ XXX.protocol.common.ClientboundTransferPacket
- XXX.protocol.common.ClientboundUpdateTagsPacket
+ XXX.protocol.common.ClientCommonPacketListener
+ XXX.protocol.common.CommonPacketTypes
- XXX.protocol.common.package-info
+ XXX.protocol.common.ServerboundClientInformationPacket
- XXX.protocol.common.ServerboundCustomClickActionPacket
+ XXX.protocol.common.ServerboundCustomPayloadPacket
- XXX.protocol.common.ServerboundKeepAlivePacket
+ XXX.protocol.common.ServerboundPongPacket
- XXX.protocol.common.ServerboundResourcePackPacket
+ XXX.protocol.common.ServerboundResourcePackPacket$Action
- XXX.protocol.common.ServerCommonPacketListener
- XXX.protocol.configuration.ClientboundFinishConfigurationPacket
+ XXX.protocol.configuration.ClientboundRegistryDataPacket
- XXX.protocol.configuration.ClientboundResetChatPacket
+ XXX.protocol.configuration.ClientboundSelectKnownPacks
- XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.configuration.ClientConfigurationPacketListener
+ XXX.protocol.configuration.ConfigurationPacketTypes
- XXX.protocol.configuration.ConfigurationProtocols
- XXX.protocol.configuration.package-info
- XXX.protocol.configuration.ServerboundFinishConfigurationPacket
+ XXX.protocol.configuration.ServerboundSelectKnownPacks
+ XXX.protocol.configuration.ServerConfigurationPacketListener
- XXX.protocol.cookie.ClientboundCookieRequestPacket
+ XXX.protocol.cookie.ClientCookiePacketListener
+ XXX.protocol.cookie.CookiePacketTypes
- XXX.protocol.cookie.package-info
+ XXX.protocol.cookie.ServerboundCookieResponsePacket
- XXX.protocol.cookie.ServerCookiePacketListener
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockChangedAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$AddOperation
+ XXX.protocol.game.ClientboundBossEventPacket$Handler
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundBossEventPacket$OperationType
- XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- XXX.protocol.game.ClientboundBundleDelimiterPacket
+ XXX.protocol.game.ClientboundBundlePacket
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChunkBatchFinishedPacket
- XXX.protocol.game.ClientboundChunkBatchStartPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeBuilder
+ XXX.protocol.game.ClientboundCommandsPacket$NodeInspector
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket$Entry
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ XXX.protocol.game.ClientboundDamageEventPacket
- XXX.protocol.game.ClientboundDebugSamplePacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundEntityPositionSyncPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundHurtAnimationPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
- XXX.protocol.game.ClientboundLevelChunkPacketData
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ XXX.protocol.game.ClientboundLevelChunkWithLightPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLightUpdatePacketData
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveMinecartPacket
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerChatPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
- XXX.protocol.game.ClientboundPlayerInfoRemovePacket
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerRotationPacket
- XXX.protocol.game.ClientboundProjectilePowerPacket
+ XXX.protocol.game.ClientboundRecipeBookAddPacket
- XXX.protocol.game.ClientboundRecipeBookAddPacket$Entry
+ XXX.protocol.game.ClientboundRecipeBookRemovePacket
- XXX.protocol.game.ClientboundRecipeBookSettingsPacket
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResetScorePacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundServerDataPacket
+ XXX.protocol.game.ClientboundSetActionBarTextPacket
- XXX.protocol.game.ClientboundSetBorderCenterPacket
+ XXX.protocol.game.ClientboundSetBorderLerpSizePacket
- XXX.protocol.game.ClientboundSetBorderSizePacket
+ XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
- XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetCursorItemPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetHeldSlotPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerInventoryPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetSimulationDistancePacket
- XXX.protocol.game.ClientboundSetSubtitleTextPacket
+ XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesAnimationPacket
- XXX.protocol.game.ClientboundSetTitleTextPacket
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStartConfigurationPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundSystemChatPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundTestInstanceBlockStatus
- XXX.protocol.game.ClientboundTickingStatePacket
+ XXX.protocol.game.ClientboundTickingStepPacket
- XXX.protocol.game.ClientboundTrackedWaypointPacket
+ XXX.protocol.game.ClientboundTrackedWaypointPacket$Operation
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.CommonPlayerSpawnInfo
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
- XXX.protocol.game.GameProtocols$1
+ XXX.protocol.game.GameProtocols$Context
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChangeGameModePacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatCommandSignedPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundChunkBatchReceivedPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientTickEndPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundContainerSlotStateChangedPacket
+ XXX.protocol.game.ServerboundDebugSampleSubscriptionPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQueryPacket
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemFromBlockPacket
+ XXX.protocol.game.ServerboundPickItemFromEntityPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPlayerLoadedPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectBundleItemPacket
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSetTestBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundTestInstanceBlockActionPacket
+ XXX.protocol.game.ServerboundTestInstanceBlockActionPacket$Action
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.HandshakePacketTypes
+ XXX.protocol.handshake.HandshakeProtocols
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientboundLoginFinishedPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.LoginPacketTypes
+ XXX.protocol.login.LoginProtocols
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryAnswerPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerboundLoginAcknowledgedPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.ping.ClientboundPongResponsePacket
- XXX.protocol.ping.ClientPongPacketListener
+ XXX.protocol.ping.package-info
- XXX.protocol.ping.PingPacketTypes
- XXX.protocol.ping.ServerboundPingRequestPacket
+ XXX.protocol.ping.ServerPingPacketListener
+ XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
- XXX.protocol.status.StatusPacketTypes
+ XXX.protocol.status.StatusProtocols
- XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$1
- XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.ConstantValue
+ XXX.providers.number.EnchantmentLevelProvider
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.StorageValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
- XXX.render.pip.GuiBannerResultRenderer
+ XXX.render.pip.GuiBookModelRenderer
- XXX.render.pip.GuiEntityRenderer
+ XXX.render.pip.GuiProfilerChartRenderer
- XXX.render.pip.GuiSignRenderer
+ XXX.render.pip.GuiSkinRenderer
- XXX.render.pip.OversizedItemRenderer
- XXX.render.pip.package-info
+ XXX.render.pip.PictureInPictureRenderer
+ XXX.render.state.BlitRenderState
- XXX.render.state.ColoredRectangleRenderState
+ XXX.render.state.GlyphEffectRenderState
- XXX.render.state.GlyphRenderState
+ XXX.render.state.GuiElementRenderState
- XXX.render.state.GuiItemRenderState
+ XXX.render.state.GuiRenderState
- XXX.render.state.GuiRenderState$LayeredElementConsumer
+ XXX.render.state.GuiRenderState$Node
- XXX.render.state.GuiRenderState$TraverseRange
+ XXX.render.state.GuiTextRenderState
+ XXX.render.state.package-info
- XXX.render.state.ScreenArea
- XXX.renderer.blockentity.DecoratedPotRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.HangingSignRenderer
+ XXX.renderer.blockentity.HangingSignRenderer$AttachmentType
- XXX.renderer.blockentity.HangingSignRenderer$ModelKey
+ XXX.renderer.blockentity.LecternRenderer
- XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.entity.ArmorModelSet$1
- XXX.renderer.entity.CowRenderer
+ XXX.renderer.entity.CreakingRenderer
- XXX.renderer.entity.CreeperRenderer
+ XXX.renderer.entity.DisplayRenderer
- XXX.renderer.entity.DisplayRenderer$1
+ XXX.renderer.entity.DisplayRenderer$BlockDisplayRenderer
- XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer
- XXX.renderer.entity.DolphinRenderer
+ XXX.renderer.entity.DonkeyRenderer
- XXX.renderer.entity.DonkeyRenderer$Type
+ XXX.renderer.entity.DragonFireballRenderer
- XXX.renderer.entity.DrownedRenderer
+ XXX.renderer.entity.ElderGuardianRenderer
- XXX.renderer.entity.EndCrystalRenderer
+ XXX.renderer.entity.EnderDragonRenderer
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EntityRendererProvider
+ XXX.renderer.entity.EntityRendererProvider$Context
- XXX.renderer.entity.EntityRenderers
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.FrogRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GlowSquidRenderer
+ XXX.renderer.entity.GoatRenderer
- XXX.renderer.entity.GuardianRenderer
+ XXX.renderer.entity.HappyGhastRenderer
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
- XXX.renderer.entity.LlamaRenderer$1
+ XXX.renderer.entity.LlamaSpitRenderer
- XXX.renderer.entity.MagmaCubeRenderer
+ XXX.renderer.entity.MinecartRenderer
- XXX.renderer.entity.MobRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.OminousItemSpawnerRenderer
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PaintingRenderer$1
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.ParrotRenderer$1
- XXX.renderer.entity.PhantomRenderer
- XXX.renderer.entity.PiglinRenderer
+ XXX.renderer.entity.PigRenderer
+ XXX.renderer.entity.PillagerRenderer
- XXX.renderer.entity.PolarBearRenderer
+ XXX.renderer.entity.PufferfishRenderer
- XXX.renderer.entity.RabbitRenderer
+ XXX.renderer.entity.RabbitRenderer$1
- XXX.renderer.entity.RaftRenderer
+ XXX.renderer.entity.RavagerRenderer
- XXX.renderer.entity.RenderLayerParent
+ XXX.renderer.entity.SalmonRenderer
- XXX.renderer.entity.SalmonRenderer$1
- XXX.renderer.feature.BlockFeatureRenderer
- XXX.renderer.feature.EntityModelFeatureRenderer
- XXX.renderer.feature.FlameFeatureRenderer
- XXX.renderer.feature.ItemFeatureRenderer
- XXX.renderer.feature.NameTagFeatureRenderer
- XXX.renderer.feature.TextFeatureRenderer
- XXX.renderer.special.CopperGolemStatueSpecialRenderer$Unbaked
- XXX.renderer.special.SpecialModelRenderer$BakingContext
- XXX.resources.language.ClientLanguage
+ XXX.resources.language.FormattedBidiReorder
- XXX.resources.language.I18n
+ XXX.resources.language.LanguageInfo
- XXX.resources.language.LanguageManager
+ XXX.resources.language.package-info
- XXX.resources.metadata.package-info
+ XXX.resources.model.AtlasIds
- XXX.resources.model.AtlasManager
- XXX.resources.model.AtlasManager$AtlasEntry
- XXX.resources.model.AtlasManager$PendingStitchResults
+ XXX.resources.model.AtlasSet$AtlasEntry
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BlockModelRotation$WithUvLock
+ XXX.resources.model.BlockStateDefinitions
- XXX.resources.model.BlockStateModelLoader
+ XXX.resources.model.BlockStateModelLoader$LoadedBlockModelDefinition
- XXX.resources.model.BlockStateModelLoader$LoadedModels
+ XXX.resources.model.ClientItemInfoLoader
- XXX.resources.model.ClientItemInfoLoader$LoadedClientInfos
+ XXX.resources.model.ClientItemInfoLoader$PendingLoad
- XXX.resources.model.EquipmentAssetManager
+ XXX.resources.model.EquipmentClientInfo
- XXX.resources.model.EquipmentClientInfo$Builder
+ XXX.resources.model.EquipmentClientInfo$Dyeable
- XXX.resources.model.EquipmentClientInfo$Layer
+ XXX.resources.model.EquipmentClientInfo$LayerType
- XXX.resources.model.Material
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecorationType
- XXX.saveddata.maps.MapDecorationTypes
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapId
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.screens.debug.DebugOptionsScreen
- XXX.screens.debug.DebugOptionsScreen$CategoryEntry
- XXX.screens.debug.DebugOptionsScreen$OptionEntry
- XXX.server.level.ChunkLoadCounter
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkResult
+ XXX.server.level.ChunkResult$Fail
- XXX.server.level.ChunkResult$Success
+ XXX.server.level.ChunkTaskDispatcher
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueue$TasksForChunk
- XXX.server.level.ChunkTracker
+ XXX.server.level.ChunkTrackingView
- XXX.server.level.ChunkTrackingView$1
+ XXX.server.level.ChunkTrackingView$Positioned
- XXX.server.level.ClientInformation
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FullChunkStatus
+ XXX.server.level.GeneratingChunkMap
- XXX.server.level.GenerationChunkHolder
+ XXX.server.level.LoadingChunkTracker
- XXX.server.level.package-info
- XXX.server.level.ParticleStatus
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerSpawnFinder
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerEntityGetter
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerLevel$1
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$1$1
+ XXX.server.level.ServerPlayer$2
- XXX.server.level.ServerPlayer$3
+ XXX.server.level.ServerPlayer$RespawnConfig
- XXX.server.level.ServerPlayer$RespawnPosAngle
+ XXX.server.level.WorldGenRegion
- XXX.server.packs.OverlayMetadataSection$1
+ XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.packs.OverlayMetadataSection$OverlayEntry$IntermediateEntry
- XXX.server.players.CachedUserNameToIdResolver$GameProfileInfo
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserNameToIdResolver
- XXX.state.pip.GuiBannerResultRenderState
+ XXX.state.pip.GuiBookModelRenderState
- XXX.state.pip.GuiEntityRenderState
+ XXX.state.pip.GuiProfilerChartRenderState
- XXX.state.pip.GuiSignRenderState
+ XXX.state.pip.GuiSkinRenderState
- XXX.state.pip.OversizedItemRenderState
- XXX.state.pip.package-info
+ XXX.state.pip.PictureInPictureRenderState
- XXX.state.properties.package-info
- XXX.state.properties.SideChainPart
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.TestBlockMode
+ XXX.state.properties.Tilt
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ContainerComponentManipulator
- XXX.storage.loot.ContainerComponentManipulators
+ XXX.storage.loot.ContainerComponentManipulators$1
- XXX.storage.loot.ContainerComponentManipulators$2
+ XXX.storage.loot.ContainerComponentManipulators$3
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$VisitedEntry
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootDataType
+ XXX.storage.loot.LootDataType$Validator
- XXX.storage.loot.LootParams
+ XXX.storage.loot.LootParams$Builder
- XXX.storage.loot.LootParams$DynamicDrop
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.package-info
+ XXX.storage.loot.ValidationContext
- XXX.storage.loot.ValidationContext$MissingReferenceProblem
+ XXX.storage.loot.ValidationContext$ParametersNotProvidedProblem
- XXX.storage.loot.ValidationContext$RecursiveReferenceProblem
+ XXX.storage.loot.ValidationContext$ReferenceNotAllowedProblem
- XXX.structure.structures.JigsawStructure$MaxDistance
+ XXX.structure.structures.JungleTemplePiece
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
+ XXX.structure.structures.JungleTempleStructure
- XXX.structure.structures.MineshaftPieces
+ XXX.structure.structures.MineshaftPieces$1
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
+ XXX.structure.structures.MineshaftPieces$MineShaftCrossing
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
+ XXX.structure.structures.MineshaftPieces$MineShaftRoom
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
+ XXX.structure.structures.MineshaftStructure
- XXX.structure.structures.MineshaftStructure$Type
+ XXX.structure.structures.NetherFortressPieces
- XXX.structure.structures.NetherFortressPieces$1
+ XXX.structure.structures.NetherFortressPieces$BridgeCrossing
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
+ XXX.structure.structures.NetherFortressPieces$BridgeStraight
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
+ XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
- XXX.structure.structures.NetherFortressPieces$PieceWeight
+ XXX.structure.structures.NetherFortressPieces$RoomCrossing
- XXX.structure.structures.NetherFortressPieces$StairsRoom
+ XXX.structure.structures.NetherFortressPieces$StartPiece
- XXX.structure.structures.NetherFortressStructure
+ XXX.structure.structures.NetherFossilPieces
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
+ XXX.structure.structures.NetherFossilStructure
- XXX.structure.structures.OceanMonumentPieces
+ XXX.structure.structures.OceanMonumentPieces$1
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.structure.structures.OceanMonumentPieces$RoomDefinition
- XXX.structure.structures.OceanMonumentStructure
+ XXX.structure.structures.OceanRuinPieces
- XXX.structure.structures.OceanRuinPieces$1
+ XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
- XXX.structure.structures.OceanRuinStructure
+ XXX.structure.structures.OceanRuinStructure$Type
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
+ XXX.structure.structures.RuinedPortalPiece$Properties
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
+ XXX.structure.structures.RuinedPortalStructure
- XXX.structure.structures.RuinedPortalStructure$Setup
+ XXX.structure.structures.ShipwreckPieces
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
+ XXX.structure.structures.ShipwreckStructure
- XXX.structure.structures.StrongholdPieces
+ XXX.structure.structures.StrongholdPieces$1
- XXX.structure.structures.StrongholdPieces$2
+ XXX.structure.structures.StrongholdPieces$3
- XXX.structure.structures.StrongholdPieces$ChestCorridor
+ XXX.structure.structures.StrongholdPieces$FillerCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
+ XXX.structure.structures.StrongholdPieces$LeftTurn
- XXX.structure.structures.StrongholdPieces$Library
+ XXX.structure.structures.StrongholdPieces$PieceWeight
- XXX.structure.structures.StrongholdPieces$PortalRoom
+ XXX.structure.structures.StrongholdPieces$PrisonHall
- XXX.structure.structures.StrongholdPieces$RightTurn
+ XXX.structure.structures.StrongholdPieces$RoomCrossing
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
+ XXX.structure.structures.StrongholdPieces$StairsDown
- XXX.structure.structures.StrongholdPieces$StartPiece
+ XXX.structure.structures.StrongholdPieces$Straight
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.structure.structures.StrongholdPieces$Turn
- XXX.structure.structures.StrongholdStructure
+ XXX.structure.structures.SwampHutPiece
- XXX.structure.structures.SwampHutStructure
+ XXX.structure.structures.WoodlandMansionPieces
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
+ XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
+ XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
+ XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.structures.WoodlandMansionStructure
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.CappedProcessor
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.LiquidSettings
+ XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.ProtectedBlockProcessor
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorList
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$JigsawBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ XXX.structure.templatesystem.StructureTemplateManager$Source
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.context.ContextKey
+ XXX.util.context.ContextKeySet
- XXX.util.context.ContextKeySet$Builder
+ XXX.util.context.ContextMap
- XXX.util.context.ContextMap$Builder
+ XXX.util.context.package-info
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.DataFixTypes$1
+ XXX.util.datafix.ExtraDataFixUtils
- XXX.util.datafix.LegacyComponentDataFixUtils
+ XXX.util.datafix.package-info
+ XXX.util.datafix.PackedBitStorage
- XXX.world.entity.ConversionParams
+ XXX.world.entity.ConversionParams$AfterConversion
- XXX.world.entity.ConversionType
+ XXX.world.entity.ConversionType$1
- XXX.world.entity.ConversionType$2
+ XXX.world.entity.Crackiness
- XXX.world.entity.Crackiness$Level
+ XXX.world.entity.Display
- XXX.world.entity.Display$BillboardConstraints
+ XXX.world.entity.Display$BlockDisplay
- XXX.world.entity.Display$BlockDisplay$BlockRenderState
+ XXX.world.entity.Display$ColorInterpolator
- XXX.world.entity.Display$FloatInterpolator
+ XXX.world.entity.Display$GenericInterpolator
- XXX.world.entity.Display$IntInterpolator
+ XXX.world.entity.Display$ItemDisplay
- XXX.world.entity.Display$ItemDisplay$ItemRenderState
+ XXX.world.entity.Display$LinearFloatInterpolator
- XXX.world.entity.Display$LinearIntInterpolator
+ XXX.world.entity.Display$RenderState
- XXX.world.entity.Display$TextDisplay
+ XXX.world.entity.Display$TextDisplay$Align
- XXX.world.entity.Display$TextDisplay$CachedInfo
+ XXX.world.entity.Display$TextDisplay$CachedLine
- XXX.world.entity.Display$TextDisplay$LineSplitter
+ XXX.world.entity.Display$TextDisplay$TextRenderState
- XXX.world.entity.Display$TransformationInterpolator
+ XXX.world.entity.DropChances
- XXX.world.entity.ElytraAnimationState
+ XXX.world.entity.Entity
- XXX.world.entity.Entity$1
+ XXX.world.entity.Entity$EntityPathElement
- XXX.world.entity.Entity$MoveFunction
+ XXX.world.entity.Entity$Movement
- XXX.world.entity.Entity$MovementEmission
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityAttachment
+ XXX.world.entity.EntityAttachment$Fallback
- XXX.world.entity.EntityAttachments
+ XXX.world.entity.EntityAttachments$Builder
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEquipment
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntityReference
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySpawnReason
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$Builder
- XXX.world.entity.EntityType$EntityFactory
+ XXX.world.entity.EquipmentSlot
- XXX.world.entity.EquipmentSlot$Type
+ XXX.world.entity.EquipmentSlotGroup
- XXX.world.entity.EquipmentSlotGroup$1
+ XXX.world.entity.EquipmentTable
- XXX.world.entity.EquipmentUser
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.InsideBlockEffectApplier
- XXX.world.entity.InsideBlockEffectApplier$1
+ XXX.world.entity.InsideBlockEffectApplier$StepBasedCollector
- XXX.world.entity.InsideBlockEffectType
+ XXX.world.entity.Interaction
- XXX.world.entity.Interaction$PlayerAction
+ XXX.world.entity.InterpolationHandler
- XXX.world.entity.InterpolationHandler$InterpolationData
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemOwner
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.Leashable
- XXX.world.entity.Leashable$LeashData
+ XXX.world.entity.Leashable$Wrench
- XXX.world.entity.LightningBolt
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.LivingEntity$Fallsounds
- XXX.world.entity.Marker
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.Mob$2
- XXX.world.entity.MobCategory
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OminousItemSpawner
- XXX.world.entity.OwnableEntity
- XXX.world.entity.package-info
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.PortalProcessor
+ XXX.world.entity.Pose
- XXX.world.entity.PositionMoveRotation
+ XXX.world.entity.Relative
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Shearable
- XXX.world.entity.SlotAccess
+ XXX.world.entity.SlotAccess$1
- XXX.world.entity.SlotAccess$2
+ XXX.world.entity.SlotAccess$3
- XXX.world.entity.SlotAccess$4
+ XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacementType
+ XXX.world.entity.SpawnPlacementTypes
- XXX.world.entity.SpawnPlacementTypes$1
- XXX.world.entity.TamableAnimal
+ XXX.world.entity.TamableAnimal$TamableAnimalPanicGoal
- XXX.world.entity.Targeting
+ XXX.world.entity.TraceableEntity
- XXX.world.entity.WalkAnimationState
+ XXX.world.flag.FeatureElement
- XXX.world.flag.FeatureFlag
+ XXX.world.flag.FeatureFlagRegistry
- XXX.world.flag.FeatureFlagRegistry$Builder
+ XXX.world.flag.FeatureFlags
+ XXX.world.flag.FeatureFlagSet
- XXX.world.flag.FeatureFlagUniverse
- XXX.world.flag.package-info
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AbstractCraftingMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AbstractFurnaceMenu$1
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.ArmorSlot
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
- XXX.world.inventory.ClickAction
+ XXX.world.inventory.ClickType
- XXX.world.inventory.ContainerData
+ XXX.world.inventory.ContainerLevelAccess
- XXX.world.inventory.ContainerLevelAccess$1
+ XXX.world.inventory.ContainerLevelAccess$2
- XXX.world.inventory.ContainerListener
+ XXX.world.inventory.ContainerSynchronizer
- XXX.world.inventory.CrafterMenu
+ XXX.world.inventory.CrafterSlot
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
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.ItemCombinerMenu$3
+ XXX.world.inventory.ItemCombinerMenu$4
- XXX.world.inventory.ItemCombinerMenuSlotDefinition
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
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
- XXX.world.inventory.NonInteractiveResultSlot
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookMenu$PostPlaceAction
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeCraftingHolder
- XXX.world.inventory.RemoteSlot
+ XXX.world.inventory.RemoteSlot$1
- XXX.world.inventory.RemoteSlot$Synchronized
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SlotRange
- XXX.world.inventory.SlotRange$1
+ XXX.world.inventory.SlotRanges
- XXX.world.inventory.SmithingMenu
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
- XXX.world.inventory.TransientCraftingContainer
+ XXX.world.item.AdventureModePredicate
- XXX.world.item.AirItem
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BoneMealItem$1
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.BundleItem$1
- XXX.world.item.CompassItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$Builder
+ XXX.world.item.CreativeModeTab$DisplayItemsGenerator
- XXX.world.item.CreativeModeTab$ItemDisplayBuilder
+ XXX.world.item.CreativeModeTab$ItemDisplayParameters
- XXX.world.item.CreativeModeTab$Output
+ XXX.world.item.CreativeModeTab$Row
- XXX.world.item.CreativeModeTab$TabVisibility
+ XXX.world.item.CreativeModeTab$Type
- XXX.world.item.CreativeModeTabs
+ XXX.world.item.CrossbowItem
- XXX.world.item.CrossbowItem$ChargeType
+ XXX.world.item.CrossbowItem$ChargingSounds
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.EitherHolder
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneycombItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$Properties
- XXX.world.item.Item$TooltipContext
+ XXX.world.item.Item$TooltipContext$1
- XXX.world.item.Item$TooltipContext$2
+ XXX.world.item.Item$TooltipContext$3
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$1
- XXX.world.item.ItemStack$2
+ XXX.world.item.ItemStack$3
- XXX.world.item.ItemStack$4
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUseAnimation
- XXX.world.item.ItemUtils
- XXX.world.item.JukeboxPlayable
+ XXX.world.item.JukeboxSong
- XXX.world.item.JukeboxSongPlayer
+ XXX.world.item.JukeboxSongPlayer$OnSongChanged
- XXX.world.item.JukeboxSongs
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MaceItem
+ XXX.world.item.MapItem
- XXX.world.item.MapItem$1
+ XXX.world.item.MinecartItem
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
- XXX.world.item.package-info
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileItem
- XXX.world.item.ProjectileItem$DispenseConfig
+ XXX.world.item.ProjectileItem$DispenseConfig$Builder
- XXX.world.item.ProjectileItem$PositionFunction
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignApplicator
+ XXX.world.item.SignItem
- XXX.world.item.SmithingTemplateItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.TippedArrowItem
- XXX.world.item.ToolMaterial
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.BlockGetter$BlockStepVisitor
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkPos$2
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.ColorMapColorUtil
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.DryFoliageColor
- XXX.world.level.EmptyBlockAndTintGetter
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.GameRules
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$Category
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameRules$VisitorCaller
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.Level$1
- XXX.world.level.Level$ExplosionInteraction
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelHeightAccessor
+ XXX.world.level.LevelHeightAccessor$1
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelTimeAccess
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.LocalMobCapCalculator
- XXX.world.level.LocalMobCapCalculator$MobCounts
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
- XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ScheduledTickAccess
+ XXX.world.level.ServerExplosion
- XXX.world.level.ServerExplosion$StackCollector
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SignalGetter
+ XXX.world.level.SimpleExplosionDamageCalculator
- XXX.world.level.SpawnData
+ XXX.world.level.SpawnData$CustomSpawnRules
- XXX.world.level.Spawner
+ XXX.world.level.StructureManager
- XXX.world.level.TicketStorage
+ XXX.world.level.TicketStorage$ChunkUpdated
- XXX.world.level.TicketStorage$TicketPredicate
- XXX.world.phys.AABB
+ XXX.world.phys.AABB$Builder
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.phys.Vec3$1
+ XXX.world.scores.DisplaySlot
- XXX.world.scores.DisplaySlot$1
+ XXX.world.scores.Objective
- XXX.world.scores.Objective$Packed
+ XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.PlayerTeam$Packed
+ XXX.world.scores.ReadOnlyScoreInfo
- XXX.world.scores.Score
+ XXX.world.scores.ScoreAccess
- XXX.world.scores.Scoreboard
+ XXX.world.scores.Scoreboard$1
- XXX.world.scores.Scoreboard$PackedScore
+ XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.ScoreboardSaveData$Packed
- XXX.world.scores.ScoreHolder
+ XXX.world.scores.ScoreHolder$1
- XXX.world.scores.ScoreHolder$2
+ XXX.world.scores.ScoreHolder$3
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
- XXX.world.ticks.BlackholeTickAccess
+ XXX.world.ticks.BlackholeTickAccess$1
- XXX.world.ticks.BlackholeTickAccess$2
+ XXX.world.ticks.ContainerSingleItem
- XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
+ XXX.world.ticks.LevelChunkTicks
- XXX.world.ticks.LevelTickAccess
+ XXX.world.ticks.LevelTicks
- XXX.world.ticks.LevelTicks$PosAndContainerConsumer
+ XXX.world.ticks.package-info
+ XXX.world.ticks.ProtoChunkTicks
- XXX.world.ticks.SavedTick
+ XXX.world.ticks.SavedTick$1
- XXX.world.ticks.ScheduledTick
+ XXX.world.ticks.ScheduledTick$1
- XXX.world.ticks.SerializableTickContainer
+ XXX.world.ticks.TickAccess
- XXX.world.ticks.TickContainerAccess
+ XXX.world.ticks.TickPriority
- XXX.world.ticks.WorldGenTickAccess
- XXX.world.waypoints.TrackedWaypoint
+ XXX.world.waypoints.TrackedWaypoint$AzimuthWaypoint
- XXX.world.waypoints.TrackedWaypoint$Camera
+ XXX.world.waypoints.TrackedWaypoint$ChunkWaypoint
- XXX.world.waypoints.TrackedWaypoint$EmptyWaypoint
+ XXX.world.waypoints.TrackedWaypoint$PitchDirection
- XXX.world.waypoints.TrackedWaypoint$Projector
+ XXX.world.waypoints.TrackedWaypoint$Type
- XXX.world.waypoints.TrackedWaypoint$Vec3iWaypoint
+ XXX.world.waypoints.TrackedWaypointManager
- XXX.world.waypoints.Waypoint
+ XXX.world.waypoints.Waypoint$Icon
- XXX.world.waypoints.WaypointManager
+ XXX.world.waypoints.WaypointStyleAsset
- XXX.world.waypoints.WaypointStyleAssets
+ XXX.world.waypoints.WaypointTransmitter
- XXX.world.waypoints.WaypointTransmitter$BlockConnection
+ XXX.world.waypoints.WaypointTransmitter$ChunkConnection
- XXX.world.waypoints.WaypointTransmitter$Connection
+ XXX.world.waypoints.WaypointTransmitter$EntityAzimuthConnection
- XXX.world.waypoints.WaypointTransmitter$EntityBlockConnection
+ XXX.world.waypoints.WaypointTransmitter$EntityChunkConnection
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.audio.Listener -2M | -1P
```
```
XXX.blaze3d.font.GlyphInfo +1P -1P
```
```
XXX.blaze3d.font.TrueTypeGlyphProvider$Glyph +1M -1M
```
```
XXX.blaze3d.opengl.DirectStateAccess$Core +4M -4M
```
```
XXX.blaze3d.opengl.GlDevice +1M -1M
```
```
XXX.blaze3d.vertex.DefaultVertexFormat -1P
```
```
XXX.blaze3d.vertex.VertexFormat -2M | -2P
```
```
XXX.mojang.realmsclient.RealmsMainScreen$AvailableSnapshotEntry +1M -1M
```
```
XXX.realmsclient.gui.RealmsWorldSlotButton +2M -1M
```
```
XXX.gui.screens.RealmsPendingInvitesScreen$Entry +1M -1M
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList +1M -1M
```
```
XXX.screens.configuration.RealmsInviteScreen +3M -2M | +1P
```
```
XXX.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList$Entry +1M -1M
```
```
net.minecraft.CrashReportCategory +1M
```
```
net.minecraft.WorldVersion +1P -1P
```
```
net.minecraft.WorldVersion$Simple +4M -4M | +2P -2P
```
```
XXX.minecraft.client.Minecraft +16M -20M | +3P -8P
```
```
XXX.minecraft.client.User +1M -2M | -1P
```
```
XXX.data.models.BlockModelGenerators +18M -6M
```
```
XXX.client.gui.Font$PreparedTextBuilder +1M
```
```
XXX.client.gui.GuiGraphics +3M -1M | +2P -1P
```
```
XXX.gui.components.MultiLineEditBox +1M -1M
```
```
XXX.gui.components.MultiLineTextWidget +1M -1M
```
```
XXX.gui.components.MultilineTextField +1M
```
```
XXX.gui.components.ObjectSelectionList$Entry +1M -1M
```
```
XXX.components.events.GuiEventListener +2M -1M | -1P
```
```
XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry +1M -1M
```
```
XXX.gui.screens.Screen$NarratableSearchResult +6M
```
```
XXX.gui.screens.TitleScreen +1M -1M
```
```
XXX.screens.achievement.StatsScreen$ItemStatisticsList +1M -1M
```
```
XXX.screens.advancements.AdvancementsScreen +1M -1M
```
```
XXX.screens.inventory.AbstractCommandBlockEditScreen +1M -1M
```
```
XXX.screens.inventory.AbstractContainerScreen +1M -1M | -2P
```
```
XXX.screens.inventory.BookViewScreen +1M -1M
```
```
XXX.screens.inventory.PageButton +1M
```
```
XXX.screens.inventory.SignEditScreen +1P -1P
```
```
XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry +1M -1M | -1P
```
```
XXX.screens.options.LanguageSelectScreen +1M
```
```
XXX.screens.options.LanguageSelectScreen$LanguageSelectionList$Entry +1M -1M | -1P
```
```
XXX.options.controls.KeyBindsScreen +1M -1M
```
```
XXX.screens.recipebook.RecipeBookComponent +1M -1M
```
```
XXX.screens.recipebook.RecipeBookPage +1M -1M
```
```
XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry +1M -1M
```
```
XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry +1M -1M
```
```
XXX.screens.worldselection.WorldSelectionList$WorldListEntry +1M -1M | -1P
```
```
XXX.client.model.AbstractBoatModel +1M -1M
```
```
XXX.client.model.AbstractPiglinModel +3M -1M
```
```
XXX.client.model.ArmedModel +1P -1P
```
```
XXX.client.model.ArmorStandModel +3M -2M
```
```
XXX.client.model.AxolotlModel +1M -1M
```
```
XXX.client.model.BannerFlagModel +2M -1M
```
```
XXX.client.model.BatModel +1M -1M
```
```
XXX.client.model.BlazeModel +1M -1M
```
```
XXX.client.model.BoggedModel +1M -1M
```
```
XXX.client.model.CreeperModel +1M -1M
```
```
XXX.client.model.DonkeyModel +1M -1M
```
```
XXX.client.model.ElytraModel +1M -1M
```
```
XXX.client.model.EndermanModel +1M -1M
```
```
XXX.client.model.EntityModel -1M
```
```
XXX.client.model.EvokerFangsModel +1M -1M
```
```
XXX.client.model.FoxModel +1M -1M
```
```
XXX.client.model.GhastModel +1M -1M
```
```
XXX.client.model.GoatModel +1M -1M
```
```
XXX.client.model.HappyGhastHarnessModel +1M -1M
```
```
XXX.client.model.SnowGolemModel +1M -1M
```
```
XXX.client.model.SpinAttackEffectModel +1M -1M
```
```
XXX.client.model.StriderModel +1M -1M
```
```
XXX.client.model.TropicalFishModelB +1M -1M
```
```
XXX.client.model.VexModel +3M -2M
```
```
XXX.client.model.VillagerModel +4M -3M | -2P
```
```
XXX.client.model.WitchModel +3M -3M | -2P
```
```
XXX.client.model.WolfModel +1M -1M
```
```
XXX.client.model.ZombieVillagerModel +8M -4M | -1P
```
```
XXX.model.dragon.DragonHeadModel +2M -1M
```
```
XXX.model.geom.LayerDefinitions +11M -2M
```
```
XXX.model.geom.ModelLayers +1M -2M | +37P -44P
```
```
XXX.client.multiplayer.ClientConfigurationPacketListenerImpl +1P
```
```
XXX.client.multiplayer.CommonListenerCookie +2M -1M | +1P
```
```
XXX.client.renderer.MapRenderer +4M -2M | +1P -1P
```
```
XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator -1M
```
```
XXX.client.renderer.RenderPipelines +3P
```
```
XXX.client.renderer.Sheets +1M | +16P
```
```
XXX.renderer.block.BlockRenderDispatcher +1M -1M | +1P
```
```
XXX.renderer.blockentity.AbstractSignRenderer +2M -2M | +2P -1P
```
```
XXX.renderer.blockentity.BellRenderer +2P
```
```
XXX.renderer.blockentity.BlockEntityRendererProvider$Context +12M -8M | +2P -1P
```
```
XXX.renderer.blockentity.ConduitRenderer +1P
```
```
XXX.renderer.blockentity.ShulkerBoxRenderer +2M -1M | +1P
```
```
XXX.renderer.blockentity.SignRenderer +3M -3M
```
```
XXX.renderer.blockentity.SkullBlockRenderer +1M
```
```
XXX.renderer.blockentity.SpawnerRenderer +1M -1M
```
```
XXX.renderer.debug.DebugRenderer -2M | -2P
```
```
XXX.renderer.entity.AbstractBoatRenderer +3M -3M
```
```
XXX.renderer.entity.AbstractSkeletonRenderer +2M -2M
```
```
XXX.renderer.entity.AgeableMobRenderer +2M -2M
```
```
XXX.renderer.entity.ArrowRenderer +2M -2M
```
```
XXX.renderer.entity.ShulkerBulletRenderer +2M -2M
```
```
XXX.renderer.entity.ThrownTridentRenderer +2M -2M
```
```
XXX.renderer.entity.TntMinecartRenderer +3M -3M | -1P
```
```
XXX.renderer.entity.TropicalFishRenderer +3M -3M
```
```
XXX.renderer.entity.VindicatorRenderer$1 +3M -3M
```
```
XXX.renderer.entity.WardenRenderer +8M -3M
```
```
XXX.renderer.entity.ZombieRenderer +1M -1M
```
```
XXX.renderer.entity.ZombifiedPiglinRenderer +1M -1M
```
```
XXX.entity.layers.BreezeWindLayer +3M -3M
```
```
XXX.entity.layers.CarriedBlockLayer +2M -2M
```
```
XXX.entity.layers.CustomHeadLayer +2M -2M
```
```
XXX.entity.layers.Deadmau5EarsLayer +2M -2M
```
```
XXX.entity.layers.DrownedOuterLayer +2M -2M
```
```
XXX.entity.layers.EnergySwirlLayer +1M -1M
```
```
XXX.entity.layers.EyesLayer +1M -1M
```
```
XXX.entity.layers.HorseMarkingLayer +2M -2M
```
```
XXX.entity.layers.MushroomCowMushroomLayer +3M -3M
```
```
XXX.entity.layers.ParrotOnShoulderLayer +3M -3M | -1P
```
```
XXX.entity.layers.PlayerItemInHandLayer +3M -3M
```
```
XXX.entity.layers.RopesLayer +2M -2M
```
```
XXX.entity.layers.SheepWoolUndercoatLayer +2M -2M
```
```
XXX.entity.layers.SkeletonClothingLayer +2M -2M
```
```
XXX.entity.layers.SnowGolemHeadLayer +2M -2M
```
```
XXX.entity.layers.SpinAttackEffectLayer +2M -2M
```
```
XXX.entity.layers.WingsLayer +2M -2M
```
```
XXX.entity.layers.WolfCollarLayer +2M -2M
```
```
XXX.entity.state.WitherSkullRenderState +1P -2P
```
```
XXX.renderer.item.BlockModelWrapper +1M -1M
```
```
XXX.renderer.item.BundleSelectedItemSpecialRenderer +1M -1M
```
```
XXX.renderer.item.CompositeModel +1M -1M
```
```
XXX.renderer.item.ConditionalItemModel +1M -1M
```
```
XXX.renderer.item.EmptyModel +1M -1M
```
```
XXX.renderer.item.ItemModel +1P -1P
```
```
XXX.renderer.item.MissingItemModel +1M -1M
```
```
XXX.renderer.item.RangeSelectItemModel +1M -1M
```
```
XXX.renderer.item.SpecialModelWrapper +1M -1M
```
```
XXX.properties.numeric.CompassAngle +1M -1M
```
```
XXX.properties.numeric.CompassAngleState$CompassTarget +1P -1P
```
```
XXX.properties.numeric.CompassAngleState$CompassTarget$2 +1M -1M
```
```
XXX.properties.numeric.CompassAngleState$CompassTarget$4 +1M -1M
```
```
XXX.properties.numeric.Count +1M -1M
```
```
XXX.properties.numeric.CustomModelDataProperty +1M -1M
```
```
XXX.properties.numeric.NeedleDirectionHelper +1M -1M | +1P -1P
```
```
XXX.properties.numeric.Time +1M -1M
```
```
XXX.properties.numeric.Time$TimeSource$1 +1M -1M
```
```
XXX.properties.numeric.Time$TimeSource$3 +1M -1M
```
```
XXX.properties.numeric.UseDuration +1M -1M
```
```
XXX.renderer.special.BannerSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.BedSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.ChestSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.ConduitSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.DecoratedPotSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.HangingSignSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.PlayerHeadSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.ShieldSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.ShulkerBoxSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.SkullSpecialRenderer$Unbaked +1M -1M
```
```
XXX.renderer.special.SpecialModelRenderer$Unbaked +1P -1P
```
```
XXX.renderer.special.StandingSignSpecialRenderer +1M -1M | +2P -1P
```
```
XXX.renderer.texture.SpriteContents +4M -2M | +1P -1P
```
```
XXX.renderer.texture.SpriteLoader$Preparations +1M -2M
```
```
XXX.renderer.texture.TextureAtlas +1M
```
```
XXX.texture.atlas.SpriteResourceLoader +2M -2M
```
```
XXX.resources.model.ModelManager +21M -28M | +1P -3P
```
```
XXX.resources.model.ModelManager$ReloadState +1M -3M | -2P
```
```
XXX.client.server.IntegratedServer +3M -2M
```
```
XXX.client.sounds.SoundEngine +1M -2M
```
```
XXX.minecraft.core.HolderGetter +2M
```
```
XXX.minecraft.core.Registry -2M
```
```
XXX.core.dispenser.ShearsDispenseItemBehavior +1M -1M
```
```
XXX.gametest.framework.GameTestRunner +4M -3M | +1P
```
```
XXX.gametest.framework.GameTestRunner$Builder +2M -1M | +1P
```
```
XXX.server.commands.PardonCommand +1M -1M
```
```
XXX.server.commands.SummonCommand +1P
```
```
XXX.server.dedicated.DedicatedServer +2M -2M
```
```
XXX.server.level.TicketType +5M -3M | +8P -3P
```
```
XXX.server.network.ServerConfigurationPacketListenerImpl +2P
```
```
XXX.server.packs.AbstractPackResources +2M -2M
```
```
XXX.packs.metadata.MetadataSectionType +1M
```
```
XXX.packs.repository.Pack +1M -2M
```
```
XXX.packs.repository.PackCompatibility +1M -1M | +2P
```
```
XXX.packs.resources.ResourceMetadata +2M -3M
```
```
XXX.packs.resources.SimpleReloadInstance +1M
```
```
XXX.packs.resources.SimpleReloadInstance$StateFactory +1M -1M | +1P -1P
```
```
XXX.server.players.UserWhiteListEntry +1M -2M
```
```
XXX.minecraft.sounds.SoundEvents +40P
```
```
XXX.minecraft.tags.ItemTags +7P
```
```
XXX.minecraft.util.InclusiveRange +1M
```
```
XXX.minecraft.world.CompoundContainer +2M -2M
```
```
XXX.ai.memory.MemoryModuleType +2P
```
```
XXX.village.poi.PoiTypes +2M -1M | +1P
```
```
XXX.entity.animal.HappyGhast +1M
```
```
XXX.animal.armadillo.Armadillo +1M -1M
```
```
XXX.level.block.BarrelBlock +1M -1M
```
```
XXX.level.block.Block +14M -10M
```
```
XXX.level.block.CakeBlock +1M -1M
```
```
XXX.level.block.CandleCakeBlock +1M -1M
```
```
XXX.level.block.CarvedPumpkinBlock +11M -3M | +2P
```
```
XXX.level.block.CaveVines +2M -1M
```
```
XXX.level.block.ChestBlock +9M -4M | +2P
```
```
XXX.level.block.ChiseledBookShelfBlock +4M -6M
```
```
XXX.level.block.CreakingHeartBlock +1M -1M
```
```
XXX.level.block.DecoratedPotBlock +1M -1M
```
```
XXX.level.block.LavaCauldronBlock +1M -1M
```
```
XXX.level.block.LecternBlock +1M -1M
```
```
XXX.level.block.RespawnAnchorBlock +1M -1M
```
```
XXX.block.entity.ShulkerBoxBlockEntity +2M -2M
```
```
XXX.block.entity.SkullBlockEntity +1M -14M | -4P
```
```
XXX.state.properties.BlockStateProperties +2P
```
```
XXX.level.levelgen.DensityFunctions$Mapped$Type +1P
```
```
XXX.level.levelgen.NoiseChunk +1M | +2P -2P
```
```
XXX.level.levelgen.NoiseRouterData +3M | +7P
```
```
XXX.structure.pools.JigsawPlacement +2M -2M
```
```
XXX.structure.structures.JigsawStructure +2M -2M | +1P -1P
```

</details>
<details>
<summary>
com.mojang.blaze3d.audio.Listener
</summary>

```diff
+ float getGain()
+ void setGain(float)
```

</details>
<details>
<summary>
com.mojang.blaze3d.font.TrueTypeGlyphProvider$Glyph
</summary>

```diff
+ BakedGlyph bake(Function)
- BakedGlyph bake(GlyphStitcher)
```

</details>
<details>
<summary>
com.mojang.blaze3d.opengl.DirectStateAccess$Core
</summary>

```diff
- ByteBuffer mapBufferRange(int,int,int,int,int)
+ ByteBuffer mapBufferRange(int,int,int,int)
- void bufferSubData(int,int,ByteBuffer,int)
+ void bufferSubData(int,int,ByteBuffer)
- void flushMappedBufferRange(int,int,int,int)
+ void flushMappedBufferRange(int,int,int)
- void unmapBuffer(int,int)
+ void unmapBuffer(int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.opengl.GlDevice
</summary>

```diff
+ void amdDummyShaderWorkaround()
- void sacrificeShaderToOpenGlAndAmd()
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.VertexFormat
</summary>

```diff
+ GpuBuffer uploadToBufferWithWorkaround(GpuBuffer,ByteBuffer,int,Supplier)
+ void <clinit>()
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$AvailableSnapshotEntry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.RealmsWorldSlotButton
</summary>

```diff
- boolean isActive()
- RealmsWorldSlotButton$Action getAction(boolean,boolean,boolean)
+ RealmsWorldSlotButton$Action getAction(RealmsServer,boolean,boolean)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.configuration.RealmsInviteScreen
</summary>

```diff
+ Boolean lambda$onInvite$3(long,String)
- boolean lambda$onInvite$3(PlayerInfo)
- Boolean lambda$onInvite$4(long,String)
+ void lambda$onInvite$4(Boolean)
- void lambda$onInvite$5(Boolean)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList$Entry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.CrashReportCategory
</summary>

```diff
- String formatLocation(double,double,double)
```

</details>
<details>
<summary>
net.minecraft.WorldVersion$Simple
</summary>

```diff
+ int datapackVersion()
+ int packVersion(PackType)
+ int resourcePackVersion()
- PackFormat datapackVersion()
- PackFormat packVersion(PackType)
- PackFormat resourcePackVersion()
+ void <init>(String,String,DataVersion,int,int,int,Date,boolean)
- void <init>(String,String,DataVersion,int,PackFormat,PackFormat,Date,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- AtlasManager getAtlasManager()
- boolean isOfflineDeveloperMode()
- boolean lambda$doWorldLoad$39(long)
+ boolean lambda$setLevel$41()
+ ChunkProgressListener lambda$doWorldLoad$37(int)
- CompletionStage lambda$delayTextureReload$55(CompletableFuture)
+ CompletionStage lambda$delayTextureReload$56(CompletableFuture)
+ Function getTextureAtlas(ResourceLocation)
+ GuiSpriteManager getGuiSprites()
- IntegratedServer lambda$doWorldLoad$37(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,LevelLoadListener,Thread)
+ IntegratedServer lambda$doWorldLoad$38(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
+ MapDecorationTextureManager getMapDecorationTextures()
+ PaintingTextureManager getPaintingTextures()
+ StoringChunkProgressListener getProgressListener()
- String lambda$doWorldLoad$38(WorldStem)
+ String lambda$doWorldLoad$39(WorldStem)
- String lambda$fillSystemReport$45(String)
- String lambda$fillSystemReport$46(Minecraft)
+ String lambda$fillSystemReport$46(String)
- String lambda$fillSystemReport$47()
+ String lambda$fillSystemReport$47(Minecraft)
+ String lambda$fillSystemReport$50()
- String lambda$fillSystemReport$50(Minecraft)
- String lambda$fillSystemReport$52(LanguageManager)
+ String lambda$fillSystemReport$52(Minecraft)
- String lambda$fillSystemReport$53()
+ String lambda$fillSystemReport$53(LanguageManager)
+ String lambda$fillSystemReport$55()
- String lambda$fillUptime$41()
+ String lambda$fillUptime$45()
- Style lambda$grabPanoramixScreenshot$57(File,Style)
+ Style lambda$grabPanoramixScreenshot$58(File,Style)
- void lambda$grabPanoramixScreenshot$56(Component)
+ void lambda$grabPanoramixScreenshot$57(Component)
+ void setLevel(ClientLevel,ReceivingLevelScreen$Reason)
- void setLevel(ClientLevel)
```

</details>
<details>
<summary>
net.minecraft.client.User
</summary>

```diff
+ User$Type getType()
+ void <init>(String,UUID,String,Optional,Optional,User$Type)
- void <init>(String,UUID,String,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.client.data.models.BlockModelGenerators
</summary>

```diff
- Condition and(ConditionBuilder[])
- Condition shelfCondition(Direction,Boolean,SideChainPart)
- ConditionBuilder condition(BooleanProperty,boolean)
- ConditionBuilder condition(EnumProperty,Enum,Enum[])
+ MultiVariant lambda$createRespawnAnchor$59(ResourceLocation[],Integer)
- MultiVariant lambda$createRespawnAnchor$61(ResourceLocation[],Integer)
+ ResourceLocation lambda$addBookSlotModel$58(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
- ResourceLocation lambda$addBookSlotModel$60(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
- void addShelfPart(Block,TextureMapping,MultiPartGenerator,ModelTemplate,Boolean,SideChainPart)
- void createCopperChests()
- void createCopperGolemStatue(Block,Block,WeatheringCopper$WeatherState)
- void createCopperGolemStatues()
+ void createLightningRod()
- void createLightningRod(Block,Block)
- void createShelf(Block)
- void forEachHorizontalDirection(BiConsumer)
- void lambda$addShelfPart$56(MultiPartGenerator,Boolean,SideChainPart,MultiVariant,Direction,VariantMutator)
+ void lambda$addSlotStateAndRotationVariants$57(MultiPartGenerator,Condition,VariantMutator,Pair)
- void lambda$addSlotStateAndRotationVariants$59(MultiPartGenerator,Condition,VariantMutator,Pair)
+ void lambda$createChiseledBookshelf$56(MultiPartGenerator,MultiVariant,Pair)
- void lambda$createChiseledBookshelf$58(MultiPartGenerator,MultiVariant,Direction,VariantMutator)
- void lambda$forEachHorizontalDirection$57(BiConsumer,Pair)
+ void lambda$run$60(BlockFamily)
- void lambda$run$62(BlockFamily)
```

</details>
<details>
<summary>
net.minecraft.client.gui.Font$PreparedTextBuilder
</summary>

```diff
- boolean accept(int,Style,BakeableGlyph)
```

</details>
<details>
<summary>
net.minecraft.client.gui.GuiGraphics
</summary>

```diff
- GuiSpriteScaling getSpriteScaling(TextureAtlasSprite)
- TextureAtlasSprite getSprite(Material)
+ void submitSignRenderState(Model,float,WoodType,int,int,int,int)
- void submitSignRenderState(Model$Simple,float,WoodType,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.MultiLineEditBox
</summary>

```diff
- void onClick(double,double,boolean)
+ void onClick(double,double)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.MultiLineTextWidget
</summary>

```diff
- void onClick(double,double,boolean)
+ void onClick(double,double)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.MultilineTextField
</summary>

```diff
- void selectWordAtCursor()
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.ObjectSelectionList$Entry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.events.GuiEventListener
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
- boolean shouldTakeFocusAfterInteraction()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.Screen$NarratableSearchResult
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- int index()
- NarratableEntry entry()
- NarratableEntry$NarrationPriority priority()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.TitleScreen
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementsScreen
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookViewScreen
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.PageButton
</summary>

```diff
- boolean shouldTakeFocusAfterInteraction()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.options.LanguageSelectScreen
</summary>

```diff
- boolean panoramaShouldSpin()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.options.LanguageSelectScreen$LanguageSelectionList$Entry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.options.controls.KeyBindsScreen
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookPage
</summary>

```diff
- boolean mouseClicked(double,double,int,int,int,int,int,boolean)
+ boolean mouseClicked(double,double,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
</summary>

```diff
- boolean mouseClicked(double,double,int,boolean)
+ boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.AbstractBoatModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.AbstractPiglinModel
</summary>

```diff
- ArmorModelSet createArmorMeshSet(CubeDeformation,CubeDeformation)
- MeshDefinition lambda$createArmorMeshSet$0(MeshDefinition)
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.ArmorStandModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
- void translateToHand(ArmorStandRenderState,HumanoidArm,PoseStack)
- void translateToHand(EntityRenderState,HumanoidArm,PoseStack)
+ void translateToHand(HumanoidArm,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.model.AxolotlModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.BannerFlagModel
</summary>

```diff
+ void setupAnim(float)
- void setupAnim(Float)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.BatModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.BlazeModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.BoggedModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.CreeperModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.DonkeyModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.ElytraModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.EndermanModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.EntityModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.EvokerFangsModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.FoxModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.GhastModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.GoatModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.HappyGhastHarnessModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.SnowGolemModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.SpinAttackEffectModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.StriderModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.TropicalFishModelB
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.VexModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
- void translateToHand(EntityRenderState,HumanoidArm,PoseStack)
+ void translateToHand(HumanoidArm,PoseStack)
- void translateToHand(VexRenderState,HumanoidArm,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.model.VillagerModel
</summary>

```diff
- MeshDefinition createNoHatModel()
+ void hatVisible(boolean)
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
- void translateToArms(EntityRenderState,PoseStack)
+ void translateToArms(PoseStack)
- void translateToArms(VillagerRenderState,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.model.WitchModel
</summary>

```diff
+ void hatVisible(boolean)
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
- void translateToArms(EntityRenderState,PoseStack)
+ void translateToArms(PoseStack)
- void translateToArms(WitchRenderState,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.model.WolfModel
</summary>

```diff
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.ZombieVillagerModel
</summary>

```diff
- ArmorModelSet createArmorLayerSet(CubeDeformation,CubeDeformation)
+ LayerDefinition createArmorLayer(CubeDeformation)
- LayerDefinition createNoHatLayer()
- LayerDefinition lambda$createArmorLayerSet$1(MeshDefinition)
- MeshDefinition createBaseArmorMesh(CubeDeformation)
- MeshDefinition lambda$createNoHatLayer$0(MeshDefinition)
+ void hatVisible(boolean)
+ void setupAnim(EntityRenderState)
- void setupAnim(Object)
- void translateToArms(EntityRenderState,PoseStack)
+ void translateToArms(PoseStack)
- void translateToArms(ZombieVillagerRenderState,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.model.dragon.DragonHeadModel
</summary>

```diff
+ void setupAnim(float,float,float)
- void setupAnim(Object)
- void setupAnim(SkullModelBase$State)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.LayerDefinitions
</summary>

```diff
+ boolean lambda$createRoots$1(ImmutableMap,ModelLayerLocation)
- boolean lambda$createRoots$10(ImmutableMap,ModelLayerLocation)
- LayerDefinition lambda$createRoots$0(MeshDefinition)
- LayerDefinition lambda$createRoots$1(LayerDefinition)
- LayerDefinition lambda$createRoots$2(MeshDefinition)
- LayerDefinition lambda$createRoots$3(MeshDefinition)
- LayerDefinition lambda$createRoots$4(LayerDefinition)
- LayerDefinition lambda$createRoots$5(LayerDefinition)
- LayerDefinition lambda$createRoots$6(MeshTransformer,LayerDefinition)
- LayerDefinition lambda$createRoots$7(MeshTransformer,LayerDefinition)
- LayerDefinition lambda$createRoots$8(LayerDefinition)
+ void lambda$createRoots$0(ImmutableMap$Builder,LayerDefinition,LayerDefinition,WoodType)
- void lambda$createRoots$9(ImmutableMap$Builder,LayerDefinition,LayerDefinition,WoodType)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.ModelLayers
</summary>

```diff
- ArmorModelSet registerArmorSet(String)
+ ModelLayerLocation registerInnerArmor(String)
+ ModelLayerLocation registerOuterArmor(String)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.CommonListenerCookie
</summary>

```diff
- LevelLoadTracker levelLoadTracker()
+ void <init>(GameProfile,WorldSessionTelemetryManager,RegistryAccess$Frozen,FeatureFlagSet,String,ServerData,Screen,Map,ChatComponent$State,Map,ServerLinks)
- void <init>(LevelLoadTracker,GameProfile,WorldSessionTelemetryManager,RegistryAccess$Frozen,FeatureFlagSet,String,ServerData,Screen,Map,ChatComponent$State,Map,ServerLinks)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.MapRenderer
</summary>

```diff
- void <init>(AtlasManager,MapTextureManager)
+ void <init>(MapDecorationTextureManager,MapTextureManager)
- void lambda$render$0(int,PoseStack$Pose,VertexConsumer)
- void lambda$render$1(float,TextureAtlasSprite,int,PoseStack$Pose,VertexConsumer)
+ void render(MapRenderState,PoseStack,MultiBufferSource,boolean,int)
- void render(MapRenderState,PoseStack,SubmitNodeCollector,boolean,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
</summary>

```diff
+ void <init>(VertexConsumer,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.Sheets
</summary>

```diff
- Material chooseCopperMaterial(ChestType,CopperChestBlock)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.BlockRenderDispatcher
</summary>

```diff
- void <init>(BlockModelShaper,MaterialSet,Supplier,BlockColors)
+ void <init>(BlockModelShaper,Supplier,BlockColors)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.AbstractSignRenderer
</summary>

```diff
+ void renderSign(PoseStack,MultiBufferSource,int,int,WoodType,Model)
- void renderSign(PoseStack,MultiBufferSource,int,int,WoodType,Model$Simple)
+ void renderSignWithText(SignBlockEntity,PoseStack,MultiBufferSource,int,int,BlockState,SignBlock,WoodType,Model)
- void renderSignWithText(SignBlockEntity,PoseStack,MultiBufferSource,int,int,BlockState,SignBlock,WoodType,Model$Simple)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
</summary>

```diff
- BlockEntityRenderDispatcher blockEntityRenderDispatcher()
+ BlockEntityRenderDispatcher getBlockEntityRenderDispatcher()
- BlockRenderDispatcher blockRenderDispatcher()
+ BlockRenderDispatcher getBlockRenderDispatcher()
- boolean equals(Object)
- EntityModelSet entityModelSet()
+ EntityModelSet getModelSet()
- EntityRenderDispatcher entityRenderer()
+ EntityRenderDispatcher getEntityRenderer()
- Font font()
+ Font getFont()
- int hashCode()
+ ItemModelResolver getItemModelResolver()
- ItemModelResolver itemModelResolver()
+ ItemRenderer getItemRenderer()
- ItemRenderer itemRenderer()
- MaterialSet materials()
- String toString()
- void <init>(BlockEntityRenderDispatcher,BlockRenderDispatcher,ItemModelResolver,ItemRenderer,EntityRenderDispatcher,EntityModelSet,Font,MaterialSet)
+ void <init>(BlockEntityRenderDispatcher,BlockRenderDispatcher,ItemModelResolver,ItemRenderer,EntityRenderDispatcher,EntityModelSet,Font)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
</summary>

```diff
- void <init>(EntityModelSet,MaterialSet)
+ void <init>(EntityModelSet)
- void <init>(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SignRenderer
</summary>

```diff
+ Model createSignModel(EntityModelSet,WoodType,boolean)
+ Model getSignModel(BlockState,WoodType)
- Model$Simple createSignModel(EntityModelSet,WoodType,boolean)
- Model$Simple getSignModel(BlockState,WoodType)
- void renderInHand(MaterialSet,PoseStack,MultiBufferSource,int,int,Model$Simple,Material)
+ void renderInHand(PoseStack,MultiBufferSource,int,int,Model,Material)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SkullBlockRenderer
</summary>

```diff
- void submitSkull(float,float,PoseStack,SubmitNodeCollector,int,SkullModelBase,RenderType,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SpawnerRenderer
</summary>

```diff
- void renderEntityInSpawner(float,PoseStack,MultiBufferSource,Entity,EntityRenderDispatcher,double,double)
+ void renderEntityInSpawner(float,PoseStack,MultiBufferSource,int,Entity,EntityRenderDispatcher,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.DebugRenderer
</summary>

```diff
+ boolean switchRenderChunkborder()
+ boolean toggleRenderOctree()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.AbstractBoatRenderer
</summary>

```diff
+ void render(BoatRenderState,PoseStack,MultiBufferSource,int)
+ void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void renderTypeAdditions(BoatRenderState,PoseStack,MultiBufferSource,int)
- void submit(BoatRenderState,PoseStack,SubmitNodeCollector)
- void submit(EntityRenderState,PoseStack,SubmitNodeCollector)
- void submitTypeAdditions(BoatRenderState,PoseStack,SubmitNodeCollector,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.AbstractSkeletonRenderer
</summary>

```diff
- void <init>(EntityRendererProvider$Context,ArmorModelSet,SkeletonModel)
- void <init>(EntityRendererProvider$Context,ModelLayerLocation,ArmorModelSet)
+ void <init>(EntityRendererProvider$Context,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation)
+ void <init>(EntityRendererProvider$Context,ModelLayerLocation,ModelLayerLocation,SkeletonModel)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.AgeableMobRenderer
</summary>

```diff
+ void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(LivingEntityRenderState,PoseStack,MultiBufferSource,int)
- void submit(EntityRenderState,PoseStack,SubmitNodeCollector)
- void submit(LivingEntityRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ArrowRenderer
</summary>

```diff
+ void render(ArrowRenderState,PoseStack,MultiBufferSource,int)
+ void render(EntityRenderState,PoseStack,MultiBufferSource,int)
- void submit(ArrowRenderState,PoseStack,SubmitNodeCollector)
- void submit(EntityRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ShulkerBulletRenderer
</summary>

```diff
+ void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(ShulkerBulletRenderState,PoseStack,MultiBufferSource,int)
- void submit(EntityRenderState,PoseStack,SubmitNodeCollector)
- void submit(ShulkerBulletRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ThrownTridentRenderer
</summary>

```diff
+ void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(ThrownTridentRenderState,PoseStack,MultiBufferSource,int)
- void submit(EntityRenderState,PoseStack,SubmitNodeCollector)
- void submit(ThrownTridentRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.TntMinecartRenderer
</summary>

```diff
+ void renderMinecartContents(MinecartRenderState,BlockState,PoseStack,MultiBufferSource,int)
+ void renderMinecartContents(MinecartTntRenderState,BlockState,PoseStack,MultiBufferSource,int)
+ void renderWhiteSolidBlock(BlockRenderDispatcher,BlockState,PoseStack,MultiBufferSource,int,boolean)
- void submitMinecartContents(MinecartRenderState,BlockState,PoseStack,SubmitNodeCollector,int)
- void submitMinecartContents(MinecartTntRenderState,BlockState,PoseStack,SubmitNodeCollector,int)
- void submitWhiteSolidBlock(BlockState,PoseStack,SubmitNodeCollector,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.TropicalFishRenderer
</summary>

```diff
+ void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(LivingEntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(TropicalFishRenderState,PoseStack,MultiBufferSource,int)
- void submit(EntityRenderState,PoseStack,SubmitNodeCollector)
- void submit(LivingEntityRenderState,PoseStack,SubmitNodeCollector)
- void submit(TropicalFishRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.VindicatorRenderer$1
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,ArmedEntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,IllagerRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,ArmedEntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,IllagerRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.WardenRenderer
</summary>

```diff
+ float lambda$new$0(WardenRenderState,float)
+ float lambda$new$2(WardenRenderState,float)
+ float lambda$new$4(WardenRenderState,float)
- float lambda$new$5(WardenRenderState,float)
- float lambda$new$7(WardenRenderState,float)
- float lambda$new$9(WardenRenderState,float)
- ResourceLocation lambda$new$0(WardenRenderState)
- ResourceLocation lambda$new$2(WardenRenderState)
- ResourceLocation lambda$new$4(WardenRenderState)
- ResourceLocation lambda$new$6(WardenRenderState)
- ResourceLocation lambda$new$8(WardenRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ZombieRenderer
</summary>

```diff
- void <init>(EntityRendererProvider$Context,ModelLayerLocation,ModelLayerLocation,ArmorModelSet,ArmorModelSet)
+ void <init>(EntityRendererProvider$Context,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ZombifiedPiglinRenderer
</summary>

```diff
- void <init>(EntityRendererProvider$Context,ModelLayerLocation,ModelLayerLocation,ArmorModelSet,ArmorModelSet)
+ void <init>(EntityRendererProvider$Context,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.BreezeWindLayer
</summary>

```diff
+ void <init>(EntityRendererProvider$Context,RenderLayerParent)
- void <init>(RenderLayerParent,EntityModelSet)
+ void render(PoseStack,MultiBufferSource,int,BreezeRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,BreezeRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EndermanRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EndermanRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.CustomHeadLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,LivingEntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,LivingEntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,PlayerRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,PlayerRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,ZombieRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,ZombieRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.EyesLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,HorseRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,HorseRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,MushroomCowRenderState,float,float)
+ void renderMushroomBlock(PoseStack,MultiBufferSource,int,boolean,BlockState,int,BlockStateModel)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,MushroomCowRenderState,float,float)
- void submitMushroomBlock(PoseStack,SubmitNodeCollector,int,boolean,BlockState,int,BlockStateModel)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,PlayerRenderState,float,float)
+ void renderOnShoulder(PoseStack,MultiBufferSource,int,PlayerRenderState,Parrot$Variant,float,float,boolean)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,PlayerRenderState,float,float)
- void submitOnShoulder(PoseStack,SubmitNodeCollector,int,PlayerRenderState,Parrot$Variant,float,float,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
</summary>

```diff
+ void renderArmWithItem(ArmedEntityRenderState,ItemStackRenderState,HumanoidArm,PoseStack,MultiBufferSource,int)
+ void renderArmWithItem(PlayerRenderState,ItemStackRenderState,HumanoidArm,PoseStack,MultiBufferSource,int)
+ void renderItemHeldToEye(ItemStackRenderState,HumanoidArm,PoseStack,MultiBufferSource,int)
- void renderItemHeldToEye(ItemStackRenderState,HumanoidArm,PoseStack,SubmitNodeCollector,int)
- void submitArmWithItem(ArmedEntityRenderState,ItemStackRenderState,HumanoidArm,PoseStack,SubmitNodeCollector,int)
- void submitArmWithItem(PlayerRenderState,ItemStackRenderState,HumanoidArm,PoseStack,SubmitNodeCollector,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.RopesLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,HappyGhastRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,HappyGhastRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.SheepWoolUndercoatLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,SheepRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,SheepRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.SkeletonClothingLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,SkeletonRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,SkeletonRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,SnowGolemRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,SnowGolemRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,PlayerRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,PlayerRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.WingsLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,HumanoidRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,HumanoidRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.WolfCollarLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,WolfRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,EntityRenderState,float,float)
- void submit(PoseStack,SubmitNodeCollector,int,WolfRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.BlockModelWrapper
</summary>

```diff
- void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,ItemOwner,int)
+ void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.BundleSelectedItemSpecialRenderer
</summary>

```diff
- void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,ItemOwner,int)
+ void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.CompositeModel
</summary>

```diff
- void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,ItemOwner,int)
+ void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.ConditionalItemModel
</summary>

```diff
- void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,ItemOwner,int)
+ void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.EmptyModel
</summary>

```diff
- void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,ItemOwner,int)
+ void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.MissingItemModel
</summary>

```diff
- void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,ItemOwner,int)
+ void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.RangeSelectItemModel
</summary>

```diff
- void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,ItemOwner,int)
+ void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.SpecialModelWrapper
</summary>

```diff
- void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,ItemOwner,int)
+ void update(ItemStackRenderState,ItemStack,ItemModelResolver,ItemDisplayContext,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.CompassAngle
</summary>

```diff
- float get(ItemStack,ClientLevel,ItemOwner,int)
+ float get(ItemStack,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.CompassAngleState$CompassTarget$2
</summary>

```diff
+ GlobalPos get(ClientLevel,ItemStack,Entity)
- GlobalPos get(ClientLevel,ItemStack,ItemOwner)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.CompassAngleState$CompassTarget$4
</summary>

```diff
+ GlobalPos get(ClientLevel,ItemStack,Entity)
- GlobalPos get(ClientLevel,ItemStack,ItemOwner)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.Count
</summary>

```diff
- float get(ItemStack,ClientLevel,ItemOwner,int)
+ float get(ItemStack,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.CustomModelDataProperty
</summary>

```diff
- float get(ItemStack,ClientLevel,ItemOwner,int)
+ float get(ItemStack,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.NeedleDirectionHelper
</summary>

```diff
- float get(ItemStack,ClientLevel,ItemOwner,int)
+ float get(ItemStack,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.Time
</summary>

```diff
+ float calculate(ItemStack,ClientLevel,int,Entity)
- float calculate(ItemStack,ClientLevel,int,ItemOwner)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.Time$TimeSource$1
</summary>

```diff
+ float get(ClientLevel,ItemStack,Entity,RandomSource)
- float get(ClientLevel,ItemStack,ItemOwner,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.Time$TimeSource$3
</summary>

```diff
+ float get(ClientLevel,ItemStack,Entity,RandomSource)
- float get(ClientLevel,ItemStack,ItemOwner,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.numeric.UseDuration
</summary>

```diff
- float get(ItemStack,ClientLevel,ItemOwner,int)
+ float get(ItemStack,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.BannerSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.BedSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.ChestSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.ConduitSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.DecoratedPotSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.HangingSignSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.PlayerHeadSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.ShieldSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.ShulkerBoxSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.SkullSpecialRenderer$Unbaked
</summary>

```diff
+ SpecialModelRenderer bake(EntityModelSet)
- SpecialModelRenderer bake(SpecialModelRenderer$BakingContext)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.StandingSignSpecialRenderer
</summary>

```diff
- void <init>(MaterialSet,Model$Simple,Material)
+ void <init>(Model,Material)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.SpriteContents
</summary>

```diff
- boolean isAnimated()
- Optional getAdditionalMetadata(MetadataSectionType)
+ ResourceMetadata metadata()
- void <init>(ResourceLocation,FrameSize,NativeImage,Optional,List)
+ void <init>(ResourceLocation,FrameSize,NativeImage,ResourceMetadata)
- void <init>(ResourceLocation,FrameSize,NativeImage)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.SpriteLoader$Preparations
</summary>

```diff
+ CompletableFuture waitForUpload()
+ SpriteLoader$Preparations lambda$waitForUpload$0(Void)
- TextureAtlasSprite getSprite(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureAtlas
</summary>

```diff
- TextureAtlasSprite missingSprite()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.atlas.SpriteResourceLoader
</summary>

```diff
+ SpriteContents lambda$create$0(Collection,ResourceLocation,Resource)
- SpriteContents lambda$create$0(Set,ResourceLocation,Resource)
+ SpriteResourceLoader create(Collection)
- SpriteResourceLoader create(Set)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.ModelManager
</summary>

```diff
+ CompletableFuture loadModels(Map,ModelBakery,Object2IntMap,EntityModelSet,SpecialBlockModelRenderer,Executor)
- CompletableFuture loadModels(SpriteLoader$Preparations,ModelBakery,Object2IntMap,EntityModelSet,SpecialBlockModelRenderer,Executor)
+ CompletableFuture reload(PreparableReloadListener$PreparationBarrier,ResourceManager,Executor,Executor)
- CompletableFuture reload(PreparableReloadListener$SharedState,Executor,PreparableReloadListener$PreparationBarrier,Executor)
+ CompletableFuture[] lambda$loadModels$13(int)
+ CompletableFuture[] lambda$reload$2(int)
+ CompletionStage lambda$loadBlockModels$11(Executor,Map)
- CompletionStage lambda$loadBlockModels$8(Executor,Map)
- CompletionStage lambda$reload$4(CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,Executor,Void)
+ CompletionStage lambda$reload$4(Map,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,Executor,Void)
+ CompletionStage lambda$reload$6(ModelManager$ReloadState)
- EntityModelSet lambda$entityModels$17()
+ EntityModelSet lambda$entityModels$21()
+ Map lambda$loadBlockModels$10(List)
- Map lambda$loadBlockModels$5(ResourceManager)
- Map lambda$loadBlockModels$7(List)
+ Map lambda$loadBlockModels$8(ResourceManager)
- ModelManager$ReloadState lambda$loadModels$14(Multimap,Multimap,Object2IntMap,EntityModelSet,SpecialBlockModelRenderer,ModelBakery$BakingResult)
+ ModelManager$ReloadState lambda$loadModels$18(Multimap,Multimap,Object2IntMap,Map,EntityModelSet,SpecialBlockModelRenderer,CompletableFuture,ModelBakery$BakingResult)
+ ModelManager$ReloadState lambda$reload$5(ModelManager$ReloadState,Void)
+ ModelManager$ResolvedModels lambda$reload$0(CompletableFuture,CompletableFuture,CompletableFuture,Void)
- ModelManager$ResolvedModels lambda$reload$1(CompletableFuture,CompletableFuture,CompletableFuture,Void)
+ Object2IntMap lambda$reload$1(BlockStateModelLoader$LoadedModels)
- Object2IntMap lambda$reload$2(BlockStateModelLoader$LoadedModels)
- Pair lambda$loadBlockModels$6(Map$Entry)
+ Pair lambda$loadBlockModels$9(Map$Entry)
- SpecialBlockModelRenderer lambda$reload$0(EntityModelSet)
- SpecialBlockModelRenderer lambda$specialBlockModelRenderer$16()
+ SpecialBlockModelRenderer lambda$specialBlockModelRenderer$20()
- String lambda$loadModels$10(Material)
- String lambda$loadModels$12(String)
+ String lambda$loadModels$14(Material)
+ String lambda$loadModels$16(String)
+ TextureAtlas getAtlas(ResourceLocation)
- void <init>(BlockColors,AtlasManager)
+ void <init>(TextureManager,BlockColors,int)
+ void apply(ModelManager$ReloadState,ProfilerFiller)
- void apply(ModelManager$ReloadState)
+ void close()
- void lambda$createBlockStateToModelDispatch$15(Map,BlockStateModel,BlockState)
+ void lambda$createBlockStateToModelDispatch$19(Map,BlockStateModel,BlockState)
+ void lambda$discoverModelDependencies$12(ModelDiscovery,ClientItem)
- void lambda$discoverModelDependencies$9(ModelDiscovery,ClientItem)
- void lambda$loadModels$11(String,Collection)
- void lambda$loadModels$13(String,Collection)
+ void lambda$loadModels$15(String,Collection)
+ void lambda$loadModels$17(String,Collection)
+ void lambda$reload$7(ModelManager$ReloadState)
+ void updateMaxMipLevel(int)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.ModelManager$ReloadState
</summary>

```diff
+ CompletableFuture readyForUpload()
+ Map atlasPreparations()
- void <init>(ModelBakery$BakingResult,Object2IntMap,Map,EntityModelSet,SpecialBlockModelRenderer)
+ void <init>(ModelBakery$BakingResult,Object2IntMap,Map,Map,EntityModelSet,SpecialBlockModelRenderer,CompletableFuture)
```

</details>
<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
+ boolean isSingleplayerOwner(GameProfile)
- boolean isSingleplayerOwner(NameAndId)
- GlobalPos selectLevelLoadFocusPos()
+ void <init>(Thread,Minecraft,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,ChunkProgressListenerFactory)
- void <init>(Thread,Minecraft,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,LevelLoadListener)
```

</details>
<details>
<summary>
net.minecraft.client.sounds.SoundEngine
</summary>

```diff
+ float getVolume(SoundSource)
+ void updateCategoryVolume(SoundSource,float)
- void updateCategoryVolume(SoundSource)
```

</details>
<details>
<summary>
net.minecraft.core.HolderGetter
</summary>

```diff
- Optional getRandomElementOf(TagKey,RandomSource)
- Optional lambda$getRandomElementOf$2(RandomSource,HolderSet$Named)
```

</details>
<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ Optional getRandomElementOf(TagKey,RandomSource)
+ Optional lambda$getRandomElementOf$9(RandomSource,HolderSet$Named)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.ShearsDispenseItemBehavior
</summary>

```diff
+ boolean tryShearBeehive(ServerLevel,BlockPos)
- boolean tryShearBeehive(ServerLevel,ItemStack,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestRunner
</summary>

```diff
+ String lambda$runScheduledRerunTests$4(GameTestInfo)
- String lambda$runScheduledRerunTests$5(GameTestInfo)
- void <init>(GameTestRunner$GameTestBatcher,Collection,ServerLevel,GameTestTicker,GameTestRunner$StructureSpawner,GameTestRunner$StructureSpawner,boolean,boolean)
+ void <init>(GameTestRunner$GameTestBatcher,Collection,ServerLevel,GameTestTicker,GameTestRunner$StructureSpawner,GameTestRunner$StructureSpawner,boolean)
+ void lambda$runBatch$3(GameTestBatch,GameTestBatchListener)
- void lambda$runBatch$3(GameTestInfo)
- void lambda$runBatch$4(GameTestBatch,GameTestBatchListener)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestRunner$Builder
</summary>

```diff
- GameTestRunner$Builder clearBetweenBatches()
- GameTestRunner$Builder haltOnError()
+ GameTestRunner$Builder haltOnError(boolean)
```

</details>
<details>
<summary>
net.minecraft.server.commands.PardonCommand
</summary>

```diff
+ Component lambda$pardonPlayers$2(GameProfile)
- Component lambda$pardonPlayers$2(NameAndId)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
+ boolean isSingleplayerOwner(GameProfile)
- boolean isSingleplayerOwner(NameAndId)
+ void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,DedicatedServerSettings,DataFixer,Services,ChunkProgressListenerFactory)
- void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,DedicatedServerSettings,DataFixer,Services)
```

</details>
<details>
<summary>
net.minecraft.server.level.TicketType
</summary>

```diff
- boolean canExpireIfUnloaded()
- boolean shouldKeepDimensionActive()
- int flags()
+ TicketType register(String,long,boolean,TicketType$TicketUse)
- TicketType register(String,long,int)
+ TicketType$TicketUse use()
+ void <init>(long,boolean,TicketType$TicketUse)
- void <init>(long,int)
```

</details>
<details>
<summary>
net.minecraft.server.packs.AbstractPackResources
</summary>

```diff
- Object getMetadataFromStream(MetadataSectionType,InputStream,PackLocationInfo)
+ Object getMetadataFromStream(MetadataSectionType,InputStream)
+ void lambda$getMetadataFromStream$0(MetadataSectionType,DataResult$Error)
- void lambda$getMetadataFromStream$0(PackLocationInfo,MetadataSectionType,DataResult$Error)
```

</details>
<details>
<summary>
net.minecraft.server.packs.metadata.MetadataSectionType
</summary>

```diff
- MetadataSectionType$WithValue withValue(Object)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.Pack
</summary>

```diff
+ InclusiveRange getDeclaredPackVersions(String,PackMetadataSection)
+ Pack$Metadata readPackMetadata(PackLocationInfo,Pack$ResourcesSupplier,int)
- Pack$Metadata readPackMetadata(PackLocationInfo,Pack$ResourcesSupplier,PackFormat,PackType)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.PackCompatibility
</summary>

```diff
+ PackCompatibility forVersion(InclusiveRange,int)
- PackCompatibility forVersion(InclusiveRange,PackFormat)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceMetadata
</summary>

```diff
- List getTypedSections(Collection)
- Optional getTypedSection(MetadataSectionType)
+ ResourceMetadata copySections(Collection)
+ void copySection(ResourceMetadata$Builder,MetadataSectionType)
+ void lambda$copySection$1(ResourceMetadata$Builder,MetadataSectionType,Object)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.SimpleReloadInstance
</summary>

```diff
- void lambda$prepareTasks$4(PreparableReloadListener$SharedState,PreparableReloadListener)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
</summary>

```diff
+ CompletableFuture lambda$static$0(PreparableReloadListener$PreparationBarrier,ResourceManager,PreparableReloadListener,Executor,Executor)
- CompletableFuture lambda$static$0(PreparableReloadListener$SharedState,PreparableReloadListener$PreparationBarrier,PreparableReloadListener,Executor,Executor)
```

</details>
<details>
<summary>
net.minecraft.server.players.UserWhiteListEntry
</summary>

```diff
+ GameProfile createGameProfile(JsonObject)
+ void <init>(GameProfile)
- void <init>(NameAndId)
```

</details>
<details>
<summary>
net.minecraft.util.InclusiveRange
</summary>

```diff
- InclusiveRange map(Function)
```

</details>
<details>
<summary>
net.minecraft.world.CompoundContainer
</summary>

```diff
- void startOpen(ContainerUser)
+ void startOpen(Player)
- void stopOpen(ContainerUser)
+ void stopOpen(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiTypes
</summary>

```diff
- Stream lambda$static$3(Block)
+ void lambda$registerBlockStates$3(Holder,BlockState)
- void lambda$registerBlockStates$4(Holder,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.HappyGhast
</summary>

```diff
- float getSoundVolume()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.armadillo.Armadillo
</summary>

```diff
+ boolean brushOffScute()
- boolean brushOffScute(Entity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BarrelBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
- boolean dropFromBlockInteractLootTable(ServerLevel,ResourceKey,BlockState,BlockEntity,ItemStack,Entity,BiConsumer)
- boolean dropFromLootTable(ServerLevel,ResourceKey,Function,BiConsumer)
+ boolean lambda$getShapeForEachState$10(Map,BlockState)
- boolean lambda$getShapeForEachState$11(BlockState,Map$Entry)
- boolean lambda$getShapeForEachState$12(Map,BlockState)
+ boolean lambda$getShapeForEachState$9(BlockState,Map$Entry)
+ ItemEntity lambda$popResource$5(Level,double,double,double,ItemStack)
- ItemEntity lambda$popResource$7(Level,double,double,double,ItemStack)
+ ItemEntity lambda$popResourceFromFace$6(Level,double,double,double,ItemStack,double,double,double)
- ItemEntity lambda$popResourceFromFace$8(Level,double,double,double,ItemStack,double,double,double)
- LootParams lambda$dropFromBlockInteractLootTable$1(BlockState,BlockEntity,Entity,ItemStack,LootParams$Builder)
- Object lambda$getShapeForEachState$10(Property)
+ Object lambda$getShapeForEachState$8(Property)
+ Object2ByteLinkedOpenHashMap lambda$static$1()
- Object2ByteLinkedOpenHashMap lambda$static$3()
+ Property lambda$getShapeForEachState$7(Property)
- Property lambda$getShapeForEachState$9(Property)
- void lambda$dropFromLootTable$2(BiConsumer,ServerLevel,ItemStack)
+ void lambda$dropResources$2(Level,BlockPos,ItemStack)
+ void lambda$dropResources$3(LevelAccessor,BlockPos,ItemStack)
- void lambda$dropResources$5(LevelAccessor,BlockPos,ItemStack)
- void lambda$dropResources$6(Level,BlockPos,ItemStack)
+ VoxelShape lambda$getShapeForEachState$11(Map,ImmutableMap,BlockState)
- VoxelShape lambda$getShapeForEachState$13(Map,ImmutableMap,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CakeBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleCakeBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CarvedPumpkinBlock
</summary>

```diff
- BlockPattern getOrCreateCopperGolemBase()
- BlockPattern getOrCreateCopperGolemFull()
- boolean lambda$getOrCreateCopperGolemBase$5(BlockState)
- boolean lambda$getOrCreateCopperGolemFull$6(BlockState)
+ boolean lambda$getOrCreateIronGolemBase$1(BlockInWorld)
- boolean lambda$getOrCreateIronGolemBase$3(BlockInWorld)
+ boolean lambda$getOrCreateIronGolemFull$2(BlockInWorld)
- boolean lambda$getOrCreateIronGolemFull$4(BlockInWorld)
- boolean lambda$getWeatherStateFromPattern$0(Block)
+ boolean lambda$static$0(BlockState)
- boolean lambda$static$2(BlockState)
- void replaceCopperBlockWithChest(Level,BlockPattern$BlockPatternMatch)
- WeatheringCopper lambda$getWeatherStateFromPattern$1(Block)
- WeatheringCopper$WeatherState getWeatherStateFromPattern(BlockPattern$BlockPatternMatch)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CaveVines
</summary>

```diff
+ int lambda$emission$0(int,BlockState)
- int lambda$emission$1(int,BlockState)
- void lambda$use$0(BlockPos,ServerLevel,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChestBlock
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockPos getConnectedBlockPos(BlockPos,BlockState)
- boolean chestCanConnectTo(BlockState)
+ boolean lambda$combine$2(LevelAccessor,BlockPos)
- boolean lambda$combine$3(LevelAccessor,BlockPos)
+ ChestBlock lambda$static$1(BlockBehaviour$Properties)
- ChestBlock lambda$static$1(SoundEvent,SoundEvent,BlockBehaviour$Properties)
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
- SoundEvent getCloseChestSound()
- SoundEvent getOpenChestSound()
+ void <init>(Supplier,BlockBehaviour$Properties)
- void <init>(Supplier,SoundEvent,SoundEvent,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChiseledBookShelfBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
- int getColumns()
- int getRows()
+ int getSection(float)
+ Optional getRelativeHitCoordinatesForBlockFace(BlockHitResult,Direction)
+ OptionalInt getHitSlot(BlockHitResult,BlockState)
+ OptionalInt lambda$getHitSlot$0(Vec2)
- void lambda$createBlockStateDefinition$0(StateDefinition$Builder,Property)
+ void lambda$createBlockStateDefinition$1(StateDefinition$Builder,Property)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CreakingHeartBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DecoratedPotBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LavaCauldronBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RespawnAnchorBlock
</summary>

```diff
- int getAnalogOutputSignal(BlockState,Level,BlockPos,Direction)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
</summary>

```diff
- void startOpen(ContainerUser)
+ void startOpen(Player)
- void stopOpen(ContainerUser)
+ void stopOpen(Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SkullBlockEntity
</summary>

```diff
+ boolean lambda$setup$1()
+ CompletableFuture fetchGameProfile(String)
+ CompletableFuture fetchGameProfile(UUID)
+ CompletableFuture fetchProfileById(UUID,Services,BooleanSupplier)
+ CompletableFuture fetchProfileByName(String,Services)
+ CompletionStage lambda$fetchProfileByName$4(Optional)
+ Optional lambda$fetchProfileById$5(BooleanSupplier,Services,UUID)
+ Optional lambda$fetchProfileByName$2(Optional)
+ Optional lambda$fetchProfileByName$3(Optional,Optional)
+ void <clinit>()
+ void clear()
+ void lambda$static$0(Runnable)
- void lambda$updateOwnerProfile$0(ResolvableProfile)
+ void lambda$updateOwnerProfile$6(ResolvableProfile)
+ void setup(Services,Executor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseChunk
</summary>

```diff
- int maxPreliminarySurfaceLevel(int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseRouterData
</summary>

```diff
- DensityFunction offsetToDepth(DensityFunction)
- DensityFunction preliminarySurfaceLevel(DensityFunction,DensityFunction,boolean)
- DensityFunction remap(DensityFunction,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
</summary>

```diff
+ Optional addPieces(Structure$GenerationContext,Holder,Optional,int,BlockPos,boolean,Optional,int,PoolAliasLookup,DimensionPadding,LiquidSettings)
- Optional addPieces(Structure$GenerationContext,Holder,Optional,int,BlockPos,boolean,Optional,JigsawStructure$MaxDistance,PoolAliasLookup,DimensionPadding,LiquidSettings)
+ void lambda$addPieces$2(PoolElementStructurePiece,int,int,int,int,LevelHeightAccessor,DimensionPadding,int,BoundingBox,Structure$GenerationContext,boolean,ChunkGenerator,StructureTemplateManager,WorldgenRandom,Registry,PoolAliasLookup,LiquidSettings,StructurePiecesBuilder)
- void lambda$addPieces$2(PoolElementStructurePiece,int,int,JigsawStructure$MaxDistance,int,LevelHeightAccessor,DimensionPadding,int,BoundingBox,Structure$GenerationContext,boolean,ChunkGenerator,StructureTemplateManager,WorldgenRandom,Registry,PoolAliasLookup,LiquidSettings,StructurePiecesBuilder)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
</summary>

```diff
+ Integer lambda$static$6(JigsawStructure)
- JigsawStructure$MaxDistance lambda$static$6(JigsawStructure)
+ void <init>(Structure$StructureSettings,Holder,Optional,int,HeightProvider,boolean,Optional,int,List,DimensionPadding,LiquidSettings)
- void <init>(Structure$StructureSettings,Holder,Optional,int,HeightProvider,boolean,Optional,JigsawStructure$MaxDistance,List,DimensionPadding,LiquidSettings)
```

</details>
</details>
<hr/>