## Comparison with [19w07a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w07a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w07a</th><th>19w08a</th></tr><tr><td>World version</td><td><pre>1932</pre></td><td><pre>1933</pre></td></tr><tr><td>Protocol version</td><td><pre>460</pre></td><td><pre>461</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">19w07a</th><th>19w08a</th></tr><tr><td>com.mojang:brigadier</td><td><pre>1.0.14</pre></td><td><pre>1.0.17</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
item
</summary>

```diff
+ minecraft:leather_horse_armor
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
- minecraft:entity.fox.bark
+ minecraft:entity.fox.screech
+ minecraft:entity.mooshroom.convert
+ minecraft:entity.mooshroom.eat
+ minecraft:entity.mooshroom.milk
+ minecraft:entity.mooshroom.suspicious_milk
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:leather_horse_armor
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
- minecraft:entity.fox.bark
+ minecraft:entity.fox.screech
+ minecraft:entity.mooshroom.convert
+ minecraft:entity.mooshroom.eat
+ minecraft:entity.mooshroom.milk
+ minecraft:entity.mooshroom.suspicious_milk
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
+ leather_horse_armor.json
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
+ argument.long.big: Long must not be more than %s, found %s
+ argument.long.low: Long must not be less than %s, found %s
+ item.minecraft.leather_horse_armor: Leather Horse Armor
- options.saturation: Saturation
+ parsing.long.expected: Expected long
+ parsing.long.invalid: Invalid long '%s'
- subtitles.entity.fox.bark: Fox barks
+ subtitles.entity.fox.screech: Fox screeches
+ subtitles.entity.mooshroom.convert: Mooshroom transforms
+ subtitles.entity.mooshroom.eat: Mooshroom eats
+ subtitles.entity.mooshroom.milk: Mooshroom gets milked
+ subtitles.entity.mooshroom.suspicious_milk: Mooshroom gets milked suspiciously
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
+ minecraft/advancements/recipes/misc/leather_horse_armor.json
+ minecraft/recipes/leather_horse_armor.json
+ minecraft/structures/village/common/iron_golem.nbt
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/models/item/leather_horse_armor.json
+ minecraft/textures/entity/cow/brown_mooshroom.png
- minecraft/textures/entity/cow/mooshroom.png
+ minecraft/textures/entity/cow/red_mooshroom.png
+ minecraft/textures/entity/horse/armor/horse_armor_leather.png
+ minecraft/textures/item/leather_horse_armor.png
+ minecraft/textures/mob_effect/absorption.png
+ minecraft/textures/mob_effect/bad_omen.png
+ minecraft/textures/mob_effect/blindness.png
+ minecraft/textures/mob_effect/conduit_power.png
+ minecraft/textures/mob_effect/dolphins_grace.png
+ minecraft/textures/mob_effect/fire_resistance.png
+ minecraft/textures/mob_effect/glowing.png
+ minecraft/textures/mob_effect/harm.png
+ minecraft/textures/mob_effect/haste.png
+ minecraft/textures/mob_effect/heal.png
+ minecraft/textures/mob_effect/health_boost.png
+ minecraft/textures/mob_effect/hunger.png
+ minecraft/textures/mob_effect/invisibility.png
+ minecraft/textures/mob_effect/jump_boost.png
+ minecraft/textures/mob_effect/levitation.png
+ minecraft/textures/mob_effect/luck.png
+ minecraft/textures/mob_effect/mining_fatigue.png
+ minecraft/textures/mob_effect/nausea.png
+ minecraft/textures/mob_effect/night_vision.png
+ minecraft/textures/mob_effect/poison.png
+ minecraft/textures/mob_effect/regeneration.png
+ minecraft/textures/mob_effect/resistance.png
+ minecraft/textures/mob_effect/saturation.png
+ minecraft/textures/mob_effect/slow_falling.png
+ minecraft/textures/mob_effect/slowness.png
+ minecraft/textures/mob_effect/speed.png
+ minecraft/textures/mob_effect/strength.png
+ minecraft/textures/mob_effect/unluck.png
+ minecraft/textures/mob_effect/water_breathing.png
+ minecraft/textures/mob_effect/weakness.png
+ minecraft/textures/mob_effect/wither.png
```

</details>
</details>
<hr/>