## Comparison with [19w04b](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w04b)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w04b</th><th>19w05a</th></tr><tr><td>World version</td><td><pre>1927</pre></td><td><pre>1930</pre></td></tr><tr><td>Protocol version</td><td><pre>457</pre></td><td><pre>458</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
entity_type
</summary>

```diff
- minecraft:illager_beast
+ minecraft:ravager
+ minecraft:trader_llama
+ minecraft:wandering_trader
```

</details>
<details>
<summary>
item
</summary>

```diff
- minecraft:illager_beast_spawn_egg
+ minecraft:ravager_spawn_egg
+ minecraft:trader_llama_spawn_egg
+ minecraft:wandering_trader_spawn_egg
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:composter
```

</details>
<details>
<summary>
sound_event
</summary>

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
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:wandering_trader
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
- minecraft:illager_beast
+ minecraft:ravager
+ minecraft:trader_llama
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:wandering_trader
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
- minecraft:illager_beast
+ minecraft:ravager
+ minecraft:trader_llama
+ minecraft:wandering_trader
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:illager_beast_spawn_egg
+ minecraft:ravager_spawn_egg
+ minecraft:trader_llama_spawn_egg
+ minecraft:wandering_trader_spawn_egg
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:composter
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

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
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
- entity.minecraft.illager_beast: Illager Beast
+ entity.minecraft.ravager: Ravager
+ entity.minecraft.trader_llama: Trader Llama
+ entity.minecraft.wandering_trader: Wandering Trader
- item.minecraft.illager_beast_spawn_egg: Illager Beast Spawn Egg
+ item.minecraft.ravager_spawn_egg: Ravager Spawn Egg
+ item.minecraft.trader_llama_spawn_egg: Trader Llama Spawn Egg
+ item.minecraft.wandering_trader_spawn_egg: Wandering Trader Spawn Egg
- subtitles.entity.illager_beast.ambient: Illager Beast grunts
- subtitles.entity.illager_beast.attack: Illager Beast bites
- subtitles.entity.illager_beast.death: Illager Beast dies
- subtitles.entity.illager_beast.hurt: Illager Beast hurts
- subtitles.entity.illager_beast.roar: Illager Beast roars
- subtitles.entity.illager_beast.step: Illager Beast steps
- subtitles.entity.illager_beast.stunned: Illager Beast stunned
+ subtitles.entity.ravager.ambient: Ravager grunts
+ subtitles.entity.ravager.attack: Ravager bites
+ subtitles.entity.ravager.death: Ravager dies
+ subtitles.entity.ravager.hurt: Ravager hurts
+ subtitles.entity.ravager.roar: Ravager roars
+ subtitles.entity.ravager.step: Ravager steps
+ subtitles.entity.ravager.stunned: Ravager stunned
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
- minecraft/loot_tables/entities/illager_beast.json
+ minecraft/loot_tables/entities/ravager.json
+ minecraft/loot_tables/entities/trader_llama.json
+ minecraft/loot_tables/entities/wandering_trader.json
+ minecraft/tags/blocks/dragon_immune.json
+ minecraft/tags/blocks/wither_immune.json
```

</details>
<details>
<summary>
assets
</summary>

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
</details>
<hr/>