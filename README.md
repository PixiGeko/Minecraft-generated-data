<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w08a ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w08a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-02-20T14:56:58+00:00</td></tr>
<tr><th>SHA1</th><td>b21d6ece2b83e7ec488a4536dbe9f9228b744b34</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/b21d6ece2b83e7ec488a4536dbe9f9228b744b34/19w08a.json">https://piston-meta.mojang.com/v1/packages/b21d6ece2b83e7ec488a4536dbe9f9228b744b34/19w08a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/f337f8dfb765f152388d5038a6e0e8830782e5ed/server.jar">https://piston-data.mojang.com/v1/objects/f337f8dfb765f152388d5038a6e0e8830782e5ed/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/8107282674163f5bb025548fef3ec26d6c5cd6ba/client.jar">https://piston-data.mojang.com/v1/objects/8107282674163f5bb025548fef3ec26d6c5cd6ba/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w07a">19w07a</a>

# Folder structure

<details><summary>data/</summary>

```diff
+ minecraft/advancements/recipes/misc/leather_horse_armor.json
+ minecraft/recipes/leather_horse_armor.json
+ minecraft/structures/village/common/iron_golem.nbt
```

</details>


<details><summary>assets/</summary>

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


# Registries

<details><summary>item.txt</summary>

```diff
+ minecraft:leather_horse_armor
```

</details>


<details><summary>sound_event.txt</summary>

```diff
- minecraft:entity.fox.bark
+ minecraft:entity.fox.screech
+ minecraft:entity.mooshroom.convert
+ minecraft:entity.mooshroom.eat
+ minecraft:entity.mooshroom.milk
+ minecraft:entity.mooshroom.suspicious_milk
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ argument.long.big
+ argument.long.low
+ item.minecraft.leather_horse_armor
- options.saturation
+ parsing.long.expected
+ parsing.long.invalid
- subtitles.entity.fox.bark
+ subtitles.entity.fox.screech
+ subtitles.entity.mooshroom.convert
+ subtitles.entity.mooshroom.eat
+ subtitles.entity.mooshroom.milk
+ subtitles.entity.mooshroom.suspicious_milk
```

</details>


# Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/misc/leather_horse_armor.json
```

</details>


<details><summary>recipes.txt</summary>

```diff
+ leather_horse_armor.json
```

</details>


<details><summary>structures.txt</summary>

```diff
+ village/common/iron_golem.nbt
```

</details>


<details><summary>textures.txt</summary>

```diff
+ entity/cow/brown_mooshroom.png
- entity/cow/mooshroom.png
+ entity/cow/red_mooshroom.png
+ entity/horse/armor/horse_armor_leather.png
+ item/leather_horse_armor.png
+ mob_effect/absorption.png
+ mob_effect/bad_omen.png
+ mob_effect/blindness.png
+ mob_effect/conduit_power.png
+ mob_effect/dolphins_grace.png
+ mob_effect/fire_resistance.png
+ mob_effect/glowing.png
+ mob_effect/harm.png
+ mob_effect/haste.png
+ mob_effect/heal.png
+ mob_effect/health_boost.png
+ mob_effect/hunger.png
+ mob_effect/invisibility.png
+ mob_effect/jump_boost.png
+ mob_effect/levitation.png
+ mob_effect/luck.png
+ mob_effect/mining_fatigue.png
+ mob_effect/nausea.png
+ mob_effect/night_vision.png
+ mob_effect/poison.png
+ mob_effect/regeneration.png
+ mob_effect/resistance.png
+ mob_effect/saturation.png
+ mob_effect/slow_falling.png
+ mob_effect/slowness.png
+ mob_effect/speed.png
+ mob_effect/strength.png
+ mob_effect/unluck.png
+ mob_effect/water_breathing.png
+ mob_effect/weakness.png
+ mob_effect/wither.png
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:brigadier:1.0.14
+ com.mojang:brigadier:1.0.17
```

</details>
