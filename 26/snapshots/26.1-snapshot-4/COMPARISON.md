## Comparison with [26.1-snapshot-3](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1-snapshot-3)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.1-snapshot-3</th><th>26.1-snapshot-4</th></tr><tr><td>DataPack version</td><td><pre>97.0</pre></td><td><pre>97.1</pre></td></tr><tr><td>ResourcePack version</td><td><pre>78.0</pre></td><td><pre>78.1</pre></td></tr><tr><td>World version</td><td><pre>4767</pre></td><td><pre>4768</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742113</pre></td><td><pre>1073742114</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.baby_horse.ambient
+ minecraft:entity.baby_horse.angry
+ minecraft:entity.baby_horse.breathe
+ minecraft:entity.baby_horse.death
+ minecraft:entity.baby_horse.eat
+ minecraft:entity.baby_horse.hurt
+ minecraft:entity.baby_horse.land
+ minecraft:entity.baby_horse.step
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.baby_horse.ambient
+ minecraft:entity.baby_horse.angry
+ minecraft:entity.baby_horse.breathe
+ minecraft:entity.baby_horse.death
+ minecraft:entity.baby_horse.eat
+ minecraft:entity.baby_horse.hurt
+ minecraft:entity.baby_horse.land
+ minecraft:entity.baby_horse.step
```

</details>
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
melon_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.1-snapshot-3</th><th>26.1-snapshot-4</th></tr><tr><td>fruit_support_blocks</td><td><pre>/</pre></td><td><pre>minecraft:supports_melon_stem_fruit</pre></td></tr><tr><td>stem_support_blocks</td><td><pre>/</pre></td><td><pre>minecraft:supports_melon_stem</pre></td></tr><tr><td>support_blocks</td><td><pre>minecraft:supports_melon_stem</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.1-snapshot-3</th><th>26.1-snapshot-4</th></tr><tr><td>fruit_support_blocks</td><td><pre>/</pre></td><td><pre>minecraft:supports_pumpkin_stem_fruit</pre></td></tr><tr><td>stem_support_blocks</td><td><pre>/</pre></td><td><pre>minecraft:supports_pumpkin_stem</pre></td></tr><tr><td>support_blocks</td><td><pre>minecraft:supports_pumpkin_stem</pre></td><td><pre>/</pre></td></tr></table>
<br/>
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
+ test.error.sequence.minimum_tick: Succeeded before expected tick: expected to wait %s
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
generated
</summary>

```diff
+ reports/minecraft/components/sound_event/entity.baby_horse.ambient.json
+ reports/minecraft/components/sound_event/entity.baby_horse.angry.json
+ reports/minecraft/components/sound_event/entity.baby_horse.breathe.json
+ reports/minecraft/components/sound_event/entity.baby_horse.death.json
+ reports/minecraft/components/sound_event/entity.baby_horse.eat.json
+ reports/minecraft/components/sound_event/entity.baby_horse.hurt.json
+ reports/minecraft/components/sound_event/entity.baby_horse.land.json
+ reports/minecraft/components/sound_event/entity.baby_horse.step.json
+ reports/minecraft/components/world_clock/the_end.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_chainmail_boots_group_2.json
+ minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_chainmail_chainmail_group_2.json
+ minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_chainmail_helmet_group_2.json
+ minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_chainmail_leggings_group_2.json
- minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_enchanted_chainmail_boots_group_2.json
- minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_enchanted_chainmail_chainmail_group_2.json
- minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_enchanted_chainmail_helmet_group_2.json
- minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_enchanted_chainmail_leggings_group_2.json
- minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_enchanted_iron_boots_group_1.json
- minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_enchanted_iron_chestplate_group_1.json
- minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_enchanted_iron_helmet_group_1.json
- minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_enchanted_iron_leggings_group_1.json
+ minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_iron_boots_group_1.json
+ minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_iron_chestplate_group_1.json
+ minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_iron_helmet_group_1.json
+ minecraft/datapacks/trade_rebalance/data/minecraft/villager_trade/armorer/2/emerald_iron_leggings_group_1.json
+ minecraft/tags/block/supports_melon_stem_fruit.json
+ minecraft/tags/block/supports_pumpkin_stem_fruit.json
+ minecraft/tags/block/supports_stem_fruit.json
+ minecraft/world_clock/the_end.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/entity/horse/donkey_baby.png
+ minecraft/textures/entity/horse/horse_black_baby.png
+ minecraft/textures/entity/horse/horse_brown_baby.png
+ minecraft/textures/entity/horse/horse_chestnut_baby.png
+ minecraft/textures/entity/horse/horse_creamy_baby.png
+ minecraft/textures/entity/horse/horse_darkbrown_baby.png
+ minecraft/textures/entity/horse/horse_gray_baby.png
+ minecraft/textures/entity/horse/horse_markings_blackdots_baby.png
+ minecraft/textures/entity/horse/horse_markings_white_baby.png
+ minecraft/textures/entity/horse/horse_markings_whitedots_baby.png
+ minecraft/textures/entity/horse/horse_markings_whitefield_baby.png
+ minecraft/textures/entity/horse/horse_skeleton_baby.png
+ minecraft/textures/entity/horse/horse_white_baby.png
+ minecraft/textures/entity/horse/horse_zombie_baby.png
+ minecraft/textures/entity/horse/mule_baby.png
```

</details>
</details>
<hr/>