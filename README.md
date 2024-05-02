<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w05a ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w05a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-01-30T15:16:49+00:00</td></tr>
<tr><th>SHA1</th><td>87712b3fed60308203939e9ac846470f4b9672d3</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/87712b3fed60308203939e9ac846470f4b9672d3/19w05a.json">https://piston-meta.mojang.com/v1/packages/87712b3fed60308203939e9ac846470f4b9672d3/19w05a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/521021450baf9b9b98b0a6d0cb60e97f306f4f57/server.jar">https://piston-data.mojang.com/v1/objects/521021450baf9b9b98b0a6d0cb60e97f306f4f57/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/26f8cdc6354884a4564a6d4e9dceb4e4440dfb54/client.jar">https://piston-data.mojang.com/v1/objects/26f8cdc6354884a4564a6d4e9dceb4e4440dfb54/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w04b">19w04b</a>

# Folder structure

<details><summary>data/</summary>

```diff
- minecraft/loot_tables/entities/illager_beast.json
+ minecraft/loot_tables/entities/ravager.json
+ minecraft/loot_tables/entities/trader_llama.json
+ minecraft/loot_tables/entities/wandering_trader.json
+ minecraft/tags/blocks/dragon_immune.json
+ minecraft/tags/blocks/wither_immune.json
```

</details>


<details><summary>assets/</summary>

```diff
- minecraft/models/item/illager_beast_spawn_egg.json
+ minecraft/models/item/ravager_spawn_egg.json
+ minecraft/models/item/trader_llama_spawn_egg.json
+ minecraft/models/item/wandering_trader_spawn_egg.json
- minecraft/textures/entity/illager/beast.png
+ minecraft/textures/entity/illager/ravager.png
+ minecraft/textures/entity/llama/decor/trader_llama.png
+ minecraft/textures/entity/wandering_trader.png
```

</details>


# Registries

<details><summary>entity_type.txt</summary>

```diff
- minecraft:illager_beast
+ minecraft:ravager
+ minecraft:trader_llama
+ minecraft:wandering_trader
```

</details>


<details><summary>item.txt</summary>

```diff
- minecraft:illager_beast_spawn_egg
+ minecraft:ravager_spawn_egg
+ minecraft:trader_llama_spawn_egg
+ minecraft:wandering_trader_spawn_egg
```

</details>


<details><summary>particle_type.txt</summary>

```diff
+ minecraft:composter
```

</details>


<details><summary>sound_event.txt</summary>

```diff
+ minecraft:block.lantern.break
+ minecraft:block.lantern.fall
+ minecraft:block.lantern.hit
+ minecraft:block.lantern.place
+ minecraft:block.lantern.step
- minecraft:entity.illager_beast.ambient
- minecraft:entity.illager_beast.attack
- minecraft:entity.illager_beast.death
- minecraft:entity.illager_beast.hurt
- minecraft:entity.illager_beast.roar
- minecraft:entity.illager_beast.step
- minecraft:entity.illager_beast.stunned
+ minecraft:entity.ravager.ambient
+ minecraft:entity.ravager.attack
+ minecraft:entity.ravager.death
+ minecraft:entity.ravager.hurt
+ minecraft:entity.ravager.roar
+ minecraft:entity.ravager.step
+ minecraft:entity.ravager.stunned
+ minecraft:entity.wandering_trader.ambient
+ minecraft:entity.wandering_trader.death
+ minecraft:entity.wandering_trader.hurt
+ minecraft:entity.wandering_trader.no
+ minecraft:entity.wandering_trader.trade
+ minecraft:entity.wandering_trader.yes
```

</details>


# Tags

<details><summary>List</summary>

```diff
+ blocks/dragon_immune.json
+ blocks/wither_immune.json
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
- entity.minecraft.illager_beast
+ entity.minecraft.ravager
+ entity.minecraft.trader_llama
+ entity.minecraft.wandering_trader
- item.minecraft.illager_beast_spawn_egg
+ item.minecraft.ravager_spawn_egg
+ item.minecraft.trader_llama_spawn_egg
+ item.minecraft.wandering_trader_spawn_egg
- subtitles.entity.illager_beast.ambient
- subtitles.entity.illager_beast.attack
- subtitles.entity.illager_beast.death
- subtitles.entity.illager_beast.hurt
- subtitles.entity.illager_beast.roar
- subtitles.entity.illager_beast.step
- subtitles.entity.illager_beast.stunned
+ subtitles.entity.ravager.ambient
+ subtitles.entity.ravager.attack
+ subtitles.entity.ravager.death
+ subtitles.entity.ravager.hurt
+ subtitles.entity.ravager.roar
+ subtitles.entity.ravager.step
+ subtitles.entity.ravager.stunned
```

</details>


# Misc

<details><summary>loot_tables.txt</summary>

```diff
- entities/illager_beast.json
+ entities/ravager.json
+ entities/trader_llama.json
+ entities/wandering_trader.json
```

</details>


<details><summary>tags.txt</summary>

```diff
+ blocks/dragon_immune.json
+ blocks/wither_immune.json
```

</details>


<details><summary>textures.txt</summary>

```diff
- entity/illager/beast.png
+ entity/illager/ravager.png
+ entity/llama/decor/trader_llama.png
+ entity/wandering_trader.png
```

</details>
