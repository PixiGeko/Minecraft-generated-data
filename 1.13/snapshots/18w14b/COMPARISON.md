## Comparison with [18w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w14a)

> [!TIP]
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- blue_coral_fan.json
- blue_coral_plant.json
- blue_coral.json
- blue_dead_coral.json
+ brain_coral_block.json
+ brain_coral_fan.json
+ brain_coral.json
+ bubble_coral_block.json
+ bubble_coral_fan.json
+ bubble_coral.json
+ dead_brain_coral_block.json
+ dead_bubble_coral_block.json
+ dead_fire_coral_block.json
+ dead_horn_coral_block.json
+ dead_tube_coral_block.json
+ fire_coral_block.json
+ fire_coral_fan.json
+ fire_coral.json
+ horn_coral_block.json
+ horn_coral_fan.json
+ horn_coral.json
- pink_coral_fan.json
- pink_coral_plant.json
- pink_coral.json
- pink_dead_coral.json
- purple_coral_fan.json
- purple_coral_plant.json
- purple_coral.json
- purple_dead_coral.json
- red_coral_fan.json
- red_coral_plant.json
- red_coral.json
- red_dead_coral.json
+ sea_pickle.json
+ tube_coral_block.json
+ tube_coral_fan.json
+ tube_coral.json
- yellow_coral_fan.json
- yellow_coral_plant.json
- yellow_coral.json
- yellow_dead_coral.json
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
+ cactus_green.json
+ lime_dye_from_smelting.json
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
- block.minecraft.blue_coral_fan: Blue Coral Fan
- block.minecraft.blue_coral_plant: Blue Coral Plant
- block.minecraft.blue_coral: Blue Coral
- block.minecraft.blue_dead_coral: Dead Blue Coral
+ block.minecraft.brain_coral_block: Brain Coral Block
+ block.minecraft.brain_coral_fan: Brain Coral Fan
+ block.minecraft.brain_coral: Brain Coral
+ block.minecraft.bubble_coral_block: Bubble Coral Block
+ block.minecraft.bubble_coral_fan: Bubble Coral Fan
+ block.minecraft.bubble_coral: Bubble Coral
+ block.minecraft.dead_brain_coral_block: Dead Brain Coral Block
+ block.minecraft.dead_bubble_coral_block: Dead Bubble Coral Block
+ block.minecraft.dead_fire_coral_block: Dead Fire Coral Block
+ block.minecraft.dead_horn_coral_block: Dead Horn Coral Block
+ block.minecraft.dead_tube_coral_block: Dead Tube Coral Block
+ block.minecraft.fire_coral_block: Fire Coral Block
+ block.minecraft.fire_coral_fan: Fire Coral Fan
+ block.minecraft.fire_coral: Fire Coral
+ block.minecraft.horn_coral_block: Horn Coral Block
+ block.minecraft.horn_coral_fan: Horn Coral Fan
+ block.minecraft.horn_coral: Horn Coral
- block.minecraft.pink_coral_fan: Pink Coral Fan
- block.minecraft.pink_coral_plant: Pink Coral Plant
- block.minecraft.pink_coral: Pink Coral
- block.minecraft.pink_dead_coral: Dead Pink Coral
- block.minecraft.purple_coral_fan: Purple Coral Fan
- block.minecraft.purple_coral_plant: Purple Coral Plant
- block.minecraft.purple_coral: Purple Coral
- block.minecraft.purple_dead_coral: Dead Purple Coral
- block.minecraft.red_coral_fan: Red Coral Fan
- block.minecraft.red_coral_plant: Red Coral Plant
- block.minecraft.red_coral: Red Coral
- block.minecraft.red_dead_coral: Dead Red Coral
+ block.minecraft.sea_pickle: Sea Pickle
+ block.minecraft.tube_coral_block: Tube Coral Block
+ block.minecraft.tube_coral_fan: Tube Coral Fan
+ block.minecraft.tube_coral: Tube Coral
- block.minecraft.yellow_coral_fan: Yellow Coral Fan
- block.minecraft.yellow_coral_plant: Yellow Coral Plant
- block.minecraft.yellow_coral: Yellow Coral
- block.minecraft.yellow_dead_coral: Dead Yellow Coral
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>18w14a</th><th>18w14b</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.allowCommands.info</div></th><td>Commands like /gamemode, /xp</td><td>Commands like /gamemode, /experience</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.throw_trident.description</div></th><td>Throw a trident at something.

Note: throwing away your only weapon is not a good idea.</td><td>Throw a trident at something.

Note: Throwing away your only weapon is not a good idea.</td></tr>
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
+ minecraft/advancements/recipes/misc/cactus_green.json
+ minecraft/advancements/recipes/misc/lime_dye_from_smelting.json
+ minecraft/recipes/cactus_green.json
+ minecraft/recipes/lime_dye_from_smelting.json
+ minecraft/tags/blocks/live_coral.json
+ minecraft/tags/items/live_coral.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/blue_coral_fan.json
- minecraft/blockstates/blue_coral_plant.json
- minecraft/blockstates/blue_coral.json
- minecraft/blockstates/blue_dead_coral.json
+ minecraft/blockstates/brain_coral_block.json
+ minecraft/blockstates/brain_coral_fan.json
+ minecraft/blockstates/brain_coral.json
+ minecraft/blockstates/bubble_coral_block.json
+ minecraft/blockstates/bubble_coral_fan.json
+ minecraft/blockstates/bubble_coral.json
+ minecraft/blockstates/dead_brain_coral_block.json
+ minecraft/blockstates/dead_bubble_coral_block.json
+ minecraft/blockstates/dead_fire_coral_block.json
+ minecraft/blockstates/dead_horn_coral_block.json
+ minecraft/blockstates/dead_tube_coral_block.json
+ minecraft/blockstates/fire_coral_block.json
+ minecraft/blockstates/fire_coral_fan.json
+ minecraft/blockstates/fire_coral.json
+ minecraft/blockstates/horn_coral_block.json
+ minecraft/blockstates/horn_coral_fan.json
+ minecraft/blockstates/horn_coral.json
- minecraft/blockstates/pink_coral_fan.json
- minecraft/blockstates/pink_coral_plant.json
- minecraft/blockstates/pink_coral.json
- minecraft/blockstates/pink_dead_coral.json
- minecraft/blockstates/purple_coral_fan.json
- minecraft/blockstates/purple_coral_plant.json
- minecraft/blockstates/purple_coral.json
- minecraft/blockstates/purple_dead_coral.json
- minecraft/blockstates/red_coral_fan.json
- minecraft/blockstates/red_coral_plant.json
- minecraft/blockstates/red_coral.json
- minecraft/blockstates/red_dead_coral.json
+ minecraft/blockstates/sea_pickle.json
+ minecraft/blockstates/tube_coral_block.json
+ minecraft/blockstates/tube_coral_fan.json
+ minecraft/blockstates/tube_coral.json
- minecraft/blockstates/yellow_coral_fan.json
- minecraft/blockstates/yellow_coral_plant.json
- minecraft/blockstates/yellow_coral.json
- minecraft/blockstates/yellow_dead_coral.json
- minecraft/models/block/blue_coral_fan.json
- minecraft/models/block/blue_coral_plant.json
- minecraft/models/block/blue_coral.json
- minecraft/models/block/blue_dead_coral.json
+ minecraft/models/block/brain_coral_block.json
+ minecraft/models/block/brain_coral_fan.json
+ minecraft/models/block/brain_coral.json
+ minecraft/models/block/bubble_coral_block.json
+ minecraft/models/block/bubble_coral_fan.json
+ minecraft/models/block/bubble_coral.json
+ minecraft/models/block/dead_brain_coral_block.json
+ minecraft/models/block/dead_bubble_coral_block.json
+ minecraft/models/block/dead_fire_coral_block.json
+ minecraft/models/block/dead_horn_coral_block.json
+ minecraft/models/block/dead_sea_pickle.json
+ minecraft/models/block/dead_tube_coral_block.json
+ minecraft/models/block/fire_coral_block.json
+ minecraft/models/block/fire_coral_fan.json
+ minecraft/models/block/fire_coral.json
+ minecraft/models/block/four_dead_sea_pickles.json
+ minecraft/models/block/four_sea_pickles.json
+ minecraft/models/block/horn_coral_block.json
+ minecraft/models/block/horn_coral_fan.json
+ minecraft/models/block/horn_coral.json
- minecraft/models/block/pink_coral_fan.json
- minecraft/models/block/pink_coral_plant.json
- minecraft/models/block/pink_coral.json
- minecraft/models/block/pink_dead_coral.json
- minecraft/models/block/purple_coral_fan.json
- minecraft/models/block/purple_coral_plant.json
- minecraft/models/block/purple_coral.json
- minecraft/models/block/purple_dead_coral.json
- minecraft/models/block/red_coral_fan.json
- minecraft/models/block/red_coral_plant.json
- minecraft/models/block/red_coral.json
- minecraft/models/block/red_dead_coral.json
+ minecraft/models/block/sea_pickle.json
+ minecraft/models/block/three_dead_sea_pickles.json
+ minecraft/models/block/three_sea_pickles.json
+ minecraft/models/block/tube_coral_block.json
+ minecraft/models/block/tube_coral_fan.json
+ minecraft/models/block/tube_coral.json
+ minecraft/models/block/two_dead_sea_pickles.json
+ minecraft/models/block/two_sea_pickles.json
- minecraft/models/block/yellow_coral_fan.json
- minecraft/models/block/yellow_coral_plant.json
- minecraft/models/block/yellow_coral.json
- minecraft/models/block/yellow_dead_coral.json
- minecraft/models/item/blue_coral_fan.json
- minecraft/models/item/blue_coral_plant.json
- minecraft/models/item/blue_coral.json
- minecraft/models/item/blue_dead_coral.json
+ minecraft/models/item/brain_coral_block.json
+ minecraft/models/item/brain_coral_fan.json
+ minecraft/models/item/brain_coral.json
+ minecraft/models/item/bubble_coral_block.json
+ minecraft/models/item/bubble_coral_fan.json
+ minecraft/models/item/bubble_coral.json
+ minecraft/models/item/dead_brain_coral_block.json
+ minecraft/models/item/dead_bubble_coral_block.json
+ minecraft/models/item/dead_fire_coral_block.json
+ minecraft/models/item/dead_horn_coral_block.json
+ minecraft/models/item/dead_tube_coral_block.json
+ minecraft/models/item/fire_coral_block.json
+ minecraft/models/item/fire_coral_fan.json
+ minecraft/models/item/fire_coral.json
+ minecraft/models/item/horn_coral_block.json
+ minecraft/models/item/horn_coral_fan.json
+ minecraft/models/item/horn_coral.json
- minecraft/models/item/pink_coral_fan.json
- minecraft/models/item/pink_coral_plant.json
- minecraft/models/item/pink_coral.json
- minecraft/models/item/pink_dead_coral.json
- minecraft/models/item/purple_coral_fan.json
- minecraft/models/item/purple_coral_plant.json
- minecraft/models/item/purple_coral.json
- minecraft/models/item/purple_dead_coral.json
- minecraft/models/item/red_coral_fan.json
- minecraft/models/item/red_coral_plant.json
- minecraft/models/item/red_coral.json
- minecraft/models/item/red_dead_coral.json
+ minecraft/models/item/sea_pickle.json
+ minecraft/models/item/tube_coral_block.json
+ minecraft/models/item/tube_coral_fan.json
+ minecraft/models/item/tube_coral.json
- minecraft/models/item/yellow_coral_fan.json
- minecraft/models/item/yellow_coral_plant.json
- minecraft/models/item/yellow_coral.json
- minecraft/models/item/yellow_dead_coral.json
- minecraft/textures/blocks/blue_coral_fan.png
- minecraft/textures/blocks/blue_coral_plant.png
- minecraft/textures/blocks/blue_coral.png
- minecraft/textures/blocks/blue_dead_coral.png
+ minecraft/textures/blocks/brain_coral_block.png
+ minecraft/textures/blocks/brain_coral_fan.png
+ minecraft/textures/blocks/brain_coral.png
+ minecraft/textures/blocks/bubble_coral_block.png
+ minecraft/textures/blocks/bubble_coral_fan.png
+ minecraft/textures/blocks/bubble_coral.png
+ minecraft/textures/blocks/dead_brain_coral_block.png
+ minecraft/textures/blocks/dead_bubble_coral_block.png
+ minecraft/textures/blocks/dead_fire_coral_block.png
+ minecraft/textures/blocks/dead_horn_coral_block.png
+ minecraft/textures/blocks/dead_tube_coral_block.png
+ minecraft/textures/blocks/fire_coral_block.png
+ minecraft/textures/blocks/fire_coral_fan.png
+ minecraft/textures/blocks/fire_coral.png
+ minecraft/textures/blocks/horn_coral_block.png
+ minecraft/textures/blocks/horn_coral_fan.png
+ minecraft/textures/blocks/horn_coral.png
- minecraft/textures/blocks/pink_coral_fan.png
- minecraft/textures/blocks/pink_coral_plant.png
- minecraft/textures/blocks/pink_coral.png
- minecraft/textures/blocks/pink_dead_coral.png
- minecraft/textures/blocks/purple_coral_fan.png
- minecraft/textures/blocks/purple_coral_plant.png
- minecraft/textures/blocks/purple_coral.png
- minecraft/textures/blocks/purple_dead_coral.png
- minecraft/textures/blocks/red_coral_fan.png
- minecraft/textures/blocks/red_coral_plant.png
- minecraft/textures/blocks/red_coral.png
- minecraft/textures/blocks/red_dead_coral.png
+ minecraft/textures/blocks/sea_pickle.png
+ minecraft/textures/blocks/tube_coral_block.png
+ minecraft/textures/blocks/tube_coral_fan.png
+ minecraft/textures/blocks/tube_coral.png
- minecraft/textures/blocks/yellow_coral_fan.png
- minecraft/textures/blocks/yellow_coral_plant.png
- minecraft/textures/blocks/yellow_coral.png
- minecraft/textures/blocks/yellow_dead_coral.png
+ minecraft/textures/items/sea_pickle.png
```

</details>
</details>
<hr/>