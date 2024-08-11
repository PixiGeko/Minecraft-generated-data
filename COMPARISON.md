## Comparison with [19w07a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w07a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">19w07a</th><th>19w08a</th></tr><tr><td>World version</td><td><code>1932</code></td><td><code>1933</code></td></tr><tr><td>Protocol version</td><td><code>460</code></td><td><code>461</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:leather_horse_armor
```

</details>








<details>
<summary>
sound_event.txt
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
<details><summary>Tags</summary>
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
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ leather_horse_armor.json
```

</details>
</details>
<details><summary>Translations</summary>
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
<details><summary>File structure</summary>
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