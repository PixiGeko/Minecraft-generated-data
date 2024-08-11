## Comparison with [18w43c](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w43c)

- [Commands](#commands)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Commands</summary>
<details>
<summary>
drop
</summary>

```diff
- drop block <targetPos: block_pos> distribute award <loot_table: resource_location>
- drop block <targetPos: block_pos> insert <slot: item_slot> <count: integer> award <loot_table: resource_location>
- drop block <targetPos: block_pos> insert <slot: item_slot> <count: integer> replace award <loot_table: resource_location>
- drop block <targetPos: block_pos> insert <slot: item_slot> award <loot_table: resource_location>
- drop block <targetPos: block_pos> insert <slot: item_slot> replace award <loot_table: resource_location>
- drop entity <entities: entity> <slot: item_slot> <count: integer> award <loot_table: resource_location>
- drop entity <entities: entity> <slot: item_slot> award <loot_table: resource_location>
- drop player <players: entity> award <loot_table: resource_location>
- drop world <targetPos: vec3> award <loot_table: resource_location>
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.husbandry.complete_catalogue.description: Tame all cat variants!
+ advancements.husbandry.complete_catalogue.title: A Complete Catalogue
+ block.minecraft.barrel: Barrel
+ block.minecraft.bell: Bell
+ block.minecraft.blast_furnace: Blast Furnace
+ block.minecraft.cartography_table: Cartography Table
+ block.minecraft.fletching_table: Fletching Table
+ block.minecraft.grindstone: Grindstone
+ block.minecraft.lectern: Lectern
+ block.minecraft.smithing_table: Smithing Table
+ block.minecraft.smoker: Smoker
+ block.minecraft.stonecutter: Stonecutter
+ container.barrel: Barrel
+ container.blast_furnace: blast_furnace
+ container.smoker: Smoker
+ item.minecraft.cat_spawn_egg: Cat Spawn Egg
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/husbandry/complete_catalogue.json
+ minecraft/loot_tables/blocks/barrel.json
+ minecraft/loot_tables/blocks/bell.json
+ minecraft/loot_tables/blocks/blast_furnace.json
+ minecraft/loot_tables/blocks/cartography_table.json
+ minecraft/loot_tables/blocks/fletching_table.json
+ minecraft/loot_tables/blocks/grindstone.json
+ minecraft/loot_tables/blocks/lectern.json
+ minecraft/loot_tables/blocks/smithing_table.json
+ minecraft/loot_tables/blocks/smoker.json
+ minecraft/loot_tables/blocks/stonecutter.json
+ minecraft/loot_tables/entities/armor_stand.json
+ minecraft/loot_tables/entities/cat_morning_gift.json
+ minecraft/loot_tables/entities/cat.json
+ minecraft/loot_tables/entities/player.json
+ minecraft/loot_tables/entities/wither.json
+ minecraft/tags/blocks/beds.json
+ minecraft/tags/items/beds.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/barrel.json
+ minecraft/blockstates/bell.json
+ minecraft/blockstates/blast_furnace.json
+ minecraft/blockstates/cartography_table.json
+ minecraft/blockstates/fletching_table.json
+ minecraft/blockstates/grindstone.json
+ minecraft/blockstates/lectern.json
+ minecraft/blockstates/smithing_table.json
+ minecraft/blockstates/smoker.json
+ minecraft/blockstates/stonecutter.json
+ minecraft/models/block/barrel.json
+ minecraft/models/block/bell_ceiling.json
+ minecraft/models/block/bell_floor.json
+ minecraft/models/block/blast_furnace_on.json
+ minecraft/models/block/blast_furnace.json
+ minecraft/models/block/cartography_table.json
+ minecraft/models/block/fletching_table.json
+ minecraft/models/block/grindstone_inventory.json
+ minecraft/models/block/grindstone.json
+ minecraft/models/block/lectern.json
+ minecraft/models/block/smithing_table.json
+ minecraft/models/block/smoker_on.json
+ minecraft/models/block/smoker.json
+ minecraft/models/block/stonecutter.json
+ minecraft/models/item/barrel.json
+ minecraft/models/item/bell.json
+ minecraft/models/item/blast_furnace.json
+ minecraft/models/item/cartography_table.json
+ minecraft/models/item/cat_spawn_egg.json
+ minecraft/models/item/fletching_table.json
+ minecraft/models/item/grindstone.json
+ minecraft/models/item/lectern.json
+ minecraft/models/item/smithing_table.json
+ minecraft/models/item/smoker.json
+ minecraft/models/item/stonecutter.json
+ minecraft/textures/block/barrel_bottom.png
+ minecraft/textures/block/barrel_side.png
+ minecraft/textures/block/barrel_top.png
+ minecraft/textures/block/bell_bottom.png
+ minecraft/textures/block/bell_side.png
+ minecraft/textures/block/bell_top.png
+ minecraft/textures/block/blast_furnace_front_on.png
+ minecraft/textures/block/blast_furnace_front_on.png.mcmeta
+ minecraft/textures/block/blast_furnace_front.png
+ minecraft/textures/block/blast_furnace_side.png
+ minecraft/textures/block/blast_furnace_top.png
+ minecraft/textures/block/cartography_table_front.png
+ minecraft/textures/block/cartography_table_side.png
+ minecraft/textures/block/cartography_table_top.png
+ minecraft/textures/block/fletching_table_front.png
+ minecraft/textures/block/fletching_table_side.png
+ minecraft/textures/block/fletching_table_top.png
+ minecraft/textures/block/grindstone_pivot.png
+ minecraft/textures/block/grindstone_round.png
+ minecraft/textures/block/grindstone_side.png
+ minecraft/textures/block/lectern_base_sides.png
+ minecraft/textures/block/lectern_base_top.png
+ minecraft/textures/block/lectern_bottom.png
+ minecraft/textures/block/lectern_front.png
+ minecraft/textures/block/lectern_sides.png
+ minecraft/textures/block/lectern_top_sides.png
+ minecraft/textures/block/lectern_top.png
+ minecraft/textures/block/lectern.png
+ minecraft/textures/block/smithing_table_front.png
+ minecraft/textures/block/smithing_table_side.png
+ minecraft/textures/block/smithing_table_top.png
+ minecraft/textures/block/smoker_bottom.png
+ minecraft/textures/block/smoker_front_on.png
+ minecraft/textures/block/smoker_front_on.png.mcmeta
+ minecraft/textures/block/smoker_front.png
+ minecraft/textures/block/smoker_side.png
+ minecraft/textures/block/smoker_top.png
+ minecraft/textures/block/stonecutter_bottom.png
+ minecraft/textures/block/stonecutter_saw.png
+ minecraft/textures/block/stonecutter_side.png
+ minecraft/textures/block/stonecutter_top.png
+ minecraft/textures/entity/cat/all_black.png
+ minecraft/textures/entity/cat/british_shorthair.png
+ minecraft/textures/entity/cat/calico.png
+ minecraft/textures/entity/cat/cat_collar.png
+ minecraft/textures/entity/cat/persian.png
+ minecraft/textures/entity/cat/ragdoll.png
+ minecraft/textures/entity/cat/tabby.png
+ minecraft/textures/entity/cat/white.png
+ minecraft/textures/item/bell.png
```

</details>
</details>