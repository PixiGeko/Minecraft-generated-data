## Comparison with [26.1.1](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1.1)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (models)](#items-(models))
> - [Blocks](#blocks)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.1.1</th><th>26w14a</th></tr><tr><td>World version</td><td><pre>4788</pre></td><td><pre>5000</pre></td></tr><tr><td>Protocol version</td><td><pre>775</pre></td><td><pre>1073742129</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
+ minecraft:copper_trap
+ minecraft:exposed_copper_trap
+ minecraft:iron_trap
+ minecraft:oxidized_copper_trap
+ minecraft:waxed_copper_trap
+ minecraft:waxed_exposed_copper_trap
+ minecraft:waxed_oxidized_copper_trap
+ minecraft:waxed_weathered_copper_trap
+ minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:follow
```

</details>
<details>
<summary>
entity_sub_predicate_type
</summary>

```diff
+ minecraft:living_block
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:crafting_grid
+ minecraft:hovering_item
- minecraft:item
+ minecraft:living_block
+ minecraft:living_block_command
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:attack_action
+ minecraft:build_action
+ minecraft:copper_trap
+ minecraft:crafting_action
+ minecraft:exposed_copper_trap
+ minecraft:follow_action
+ minecraft:group_action
+ minecraft:highlight_action
+ minecraft:iron_trap
+ minecraft:move_action
+ minecraft:oxidized_copper_trap
+ minecraft:punch_action
+ minecraft:waxed_copper_trap
+ minecraft:waxed_exposed_copper_trap
+ minecraft:waxed_oxidized_copper_trap
+ minecraft:waxed_weathered_copper_trap
+ minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
trigger_type
</summary>

```diff
+ minecraft:barrel_roll
+ minecraft:built_house
+ minecraft:built_trap
+ minecraft:end_portal_crafted
+ minecraft:eye_frame_combination
+ minecraft:nether_portal_crafted
+ minecraft:use_item
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:leaf_litter
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:copper_trap
+ minecraft:exposed_copper_trap
+ minecraft:iron_trap
- minecraft:leaf_litter
+ minecraft:oxidized_copper_trap
+ minecraft:waxed_copper_trap
+ minecraft:waxed_exposed_copper_trap
+ minecraft:waxed_oxidized_copper_trap
+ minecraft:waxed_weathered_copper_trap
+ minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:crafting_grid
+ minecraft:hovering_item
- minecraft:item
+ minecraft:living_block
+ minecraft:living_block_command
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:leaf_litter
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:copper_trap
+ minecraft:exposed_copper_trap
+ minecraft:iron_trap
+ minecraft:oxidized_copper_trap
+ minecraft:waxed_copper_trap
+ minecraft:waxed_exposed_copper_trap
+ minecraft:waxed_oxidized_copper_trap
+ minecraft:waxed_weathered_copper_trap
+ minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:follow
```

</details>
<details>
<summary>
universal_tags/entity_sub_predicate_type.json
</summary>

```diff
+ minecraft:living_block
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:crafting_grid
+ minecraft:hovering_item
- minecraft:item
+ minecraft:living_block
+ minecraft:living_block_command
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:attack_action
+ minecraft:build_action
+ minecraft:copper_trap
+ minecraft:crafting_action
+ minecraft:exposed_copper_trap
+ minecraft:follow_action
+ minecraft:group_action
+ minecraft:highlight_action
+ minecraft:iron_trap
+ minecraft:move_action
+ minecraft:oxidized_copper_trap
+ minecraft:punch_action
+ minecraft:waxed_copper_trap
+ minecraft:waxed_exposed_copper_trap
+ minecraft:waxed_oxidized_copper_trap
+ minecraft:waxed_weathered_copper_trap
+ minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
universal_tags/trigger_type.json
</summary>

```diff
+ minecraft:barrel_roll
+ minecraft:built_house
+ minecraft:built_trap
+ minecraft:end_portal_crafted
+ minecraft:eye_frame_combination
+ minecraft:nether_portal_crafted
+ minecraft:use_item
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (MODELS)</ins></b><a name="items-(models)"></a></summary>
<br/>
<details>
<summary>
Model types
</summary>

```diff
- minecraft:composite
```

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
+ copper_trap.json
+ exposed_copper_trap.json
+ iron_trap.json
+ oxidized_copper_trap.json
+ waxed_copper_trap.json
+ waxed_exposed_copper_trap.json
+ waxed_oxidized_copper_trap.json
+ waxed_weathered_copper_trap.json
+ weathered_copper_trap.json
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
+ advancements.adventure.barrel_roll.description: Make a barrel roll
+ advancements.adventure.barrel_roll.title: Do a Barrel Roll!
+ advancements.adventure.build_house.description: Watch 23 blocks and a door combine into a tiny house
+ advancements.adventure.build_house.title: Tiny House, Assemble!
+ advancements.adventure.build_trap.description: Watch out for 8 iron (or copper) bars, they're dangerous in groups. When you least expect it!
+ advancements.adventure.build_trap.title: You Played Yourself
+ advancements.adventure.craft_chest.description: Craft a Chest to keep track of your blocks
+ advancements.adventure.craft_chest.title: Random Access Materials
+ advancements.adventure.craft_sword.description: Craft a Sword
+ advancements.adventure.craft_sword.title: Time to Fight!
+ advancements.adventure.crafter.description: Automate your crafting with a Crafter
+ advancements.adventure.crafter.title: Large Living Blocks Model
+ advancements.adventure.crafting_table.description: Craft a Crafting Table
+ advancements.adventure.crafting_table.title: Integrated Crafting Environment
+ advancements.adventure.door.description: Craft a Door
+ advancements.adventure.door.title: Seek Shelter
+ advancements.adventure.end_portal.description: Watch twelve End Portal Frames with Eyes of Ender inserted combine into an End Portal
+ advancements.adventure.end_portal.title: End of Line
+ advancements.adventure.eye_frame_combination.description: Move an Eye of Ender close enough to an End Portal Frame for them to combine
+ advancements.adventure.eye_frame_combination.title: Unifying Eye-Frame Interaction
+ advancements.adventure.furnace.description: Make a furnace that can smelt things for you
+ advancements.adventure.furnace.title: You're Cookin'
+ advancements.adventure.iron_ingot.description: Make your way to the iron age
+ advancements.adventure.iron_ingot.title: Ferrocious Ferrous
+ advancements.adventure.mine_a_block.description: Punch a block until it comes alive
+ advancements.adventure.mine_a_block.title: Mine a Block
+ advancements.adventure.nether_portal.description: Watch twelve Obsidian and a Flint and Steel combine into a Nether Portal
+ advancements.adventure.nether_portal.title: Nether-field Crafting
+ advancements.adventure.obsidian.description: Mine some Obsidian
+ advancements.adventure.obsidian.title: You require additional...
+ advancements.adventure.wooden_pickaxe.description: Craft a tool that can mine for you
+ advancements.adventure.wooden_pickaxe.title: Craft a Miner
+ advancements.end.barrel_roll.description: Roll a barrel to the ends of the universe
+ advancements.end.barrel_roll.title: Never Give Up! Trust Your Instincts!
+ advancements.nether.barrel_roll.description: Do it! Do it now!
+ advancements.nether.barrel_roll.title: Do a Barrel Roll! Do it! Do it! Do it in the Nether!
+ block.minecraft.copper_trap: Copper Trap
+ block.minecraft.exposed_copper_trap: Exposed Copper Trap
+ block.minecraft.iron_trap: Iron Trap
+ block.minecraft.oxidized_copper_trap: Oxidized Copper Trap
+ block.minecraft.waxed_copper_trap: Waxed Copper Trap
+ block.minecraft.waxed_exposed_copper_trap: Waxed Exposed Copper Trap
+ block.minecraft.waxed_oxidized_copper_trap: Waxed Oxidized Copper Trap
+ block.minecraft.waxed_weathered_copper_trap: Waxed Weathered Copper Trap
+ block.minecraft.weathered_copper_trap: Weathered Copper Trap
+ crafting.table.unable_to_place: The crafting grid needs a 2x2 block wide level surface
+ entity.minecraft.crafting_action: Craft
+ entity.minecraft.crafting_grid: Crafting Grid
+ entity.minecraft.follow_action: Follow Me
+ entity.minecraft.hovering_item: Crafting Results
+ entity.minecraft.living_block_command: Living Block Command
+ entity.minecraft.living_block: Living Block
+ entity.minecraft.punch_action: Punch
+ inventory.place_grid: Use the Craft action to place a crafting grid
+ item.minecraft.attack_action: Attack / Mine
+ item.minecraft.build_action: Build
+ item.minecraft.crafting_action: Craft
+ item.minecraft.follow_action: Follow Me
+ item.minecraft.group_action: Group / Ungroup
+ item.minecraft.highlight_action: Highlight
+ item.minecraft.move_action: Move
+ item.minecraft.punch_action: Punch
+ item.minecraft.select_action: Select
+ item.minecraft.select_group_action.details: Selected Group: %s
+ living_blocks.group.all: All
+ living_blocks.group.aqua: Aqua
+ living_blocks.group.blue: Blue
+ living_blocks.group.lime: Lime
+ living_blocks.group.none: None
+ living_blocks.group.purple: Purple
+ living_blocks.group.red: Red
+ living_blocks.group.yellow: Yellow
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.1.1</th><th>26w14a</th></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.kill_a_mob.description</div></th><td>Kill any hostile monster</td><td>Have your sword kill any hostile monster</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.kill_a_mob.title</div></th><td>Monster Hunter</td><td>Monster Hunter (With Friends)</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.kill_all_mobs.description</div></th><td>Kill one of every hostile monster</td><td>Command an army of weapons to kill one of every hostile monster</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.ol_betsy.description</div></th><td>Shoot a Crossbow</td><td>Aqcuire a Crossbow</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.root.description</div></th><td>Adventure, exploration and combat</td><td>Herding and crafting your world</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.root.title</div></th><td>Adventure</td><td>HerdCraft</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.enter_the_end.description</div></th><td>Enter the End Portal</td><td>Gather enough Eyes of Ender, find some End Portal Frames and enter the End</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.enter_the_nether.description</div></th><td>Build, light and enter a Nether Portal</td><td>Gather enough Obsidian and a Flint and Steel, then enter the Nether</td></tr>
</table>
<br/>
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
+ reports/minecraft/components/item/attack_action.json
+ reports/minecraft/components/item/build_action.json
+ reports/minecraft/components/item/copper_trap.json
+ reports/minecraft/components/item/crafting_action.json
+ reports/minecraft/components/item/exposed_copper_trap.json
+ reports/minecraft/components/item/follow_action.json
+ reports/minecraft/components/item/group_action.json
+ reports/minecraft/components/item/highlight_action.json
+ reports/minecraft/components/item/iron_trap.json
+ reports/minecraft/components/item/move_action.json
+ reports/minecraft/components/item/oxidized_copper_trap.json
+ reports/minecraft/components/item/punch_action.json
+ reports/minecraft/components/item/waxed_copper_trap.json
+ reports/minecraft/components/item/waxed_exposed_copper_trap.json
+ reports/minecraft/components/item/waxed_oxidized_copper_trap.json
+ reports/minecraft/components/item/waxed_weathered_copper_trap.json
+ reports/minecraft/components/item/weathered_copper_trap.json
```

</details>
<details>
<summary>
data
</summary>

```diff
- minecraft/advancement/adventure/adventuring_time.json
- minecraft/advancement/adventure/arbalistic.json
- minecraft/advancement/adventure/avoid_vibration.json
+ minecraft/advancement/adventure/barrel_roll.json
- minecraft/advancement/adventure/blowback.json
- minecraft/advancement/adventure/brush_armadillo.json
+ minecraft/advancement/adventure/build_house.json
+ minecraft/advancement/adventure/build_trap.json
- minecraft/advancement/adventure/bullseye.json
+ minecraft/advancement/adventure/craft_chest.json
- minecraft/advancement/adventure/craft_decorated_pot_using_only_sherds.json
+ minecraft/advancement/adventure/craft_end_portal.json
+ minecraft/advancement/adventure/craft_nether_portal.json
+ minecraft/advancement/adventure/craft_sword.json
+ minecraft/advancement/adventure/craft_table.json
+ minecraft/advancement/adventure/crafter.json
- minecraft/advancement/adventure/crafters_crafting_crafters.json
+ minecraft/advancement/adventure/door.json
+ minecraft/advancement/adventure/end_barrel_roll.json
+ minecraft/advancement/adventure/enter_the_end.json
+ minecraft/advancement/adventure/eye_frame_combination.json
- minecraft/advancement/adventure/fall_from_world_height.json
+ minecraft/advancement/adventure/find_fortress.json
+ minecraft/advancement/adventure/follow_ender_eye.json
+ minecraft/advancement/adventure/furnace.json
- minecraft/advancement/adventure/heart_transplanter.json
- minecraft/advancement/adventure/hero_of_the_village.json
- minecraft/advancement/adventure/honey_block_slide.json
+ minecraft/advancement/adventure/iron_ingot.json
+ minecraft/advancement/adventure/kill_dragon.json
- minecraft/advancement/adventure/kill_mob_near_sculk_catalyst.json
- minecraft/advancement/adventure/lighten_up.json
- minecraft/advancement/adventure/lightning_rod_with_villager_no_fire.json
+ minecraft/advancement/adventure/mine_a_block.json
- minecraft/advancement/adventure/minecraft_trials_edition.json
+ minecraft/advancement/adventure/nether_barrel_roll.json
+ minecraft/advancement/adventure/obsidian.json
+ minecraft/advancement/adventure/obtain_armor.json
+ minecraft/advancement/adventure/obtain_blaze_rod.json
- minecraft/advancement/adventure/ol_betsy.json
- minecraft/advancement/adventure/overoverkill.json
- minecraft/advancement/adventure/play_jukebox_in_meadows.json
- minecraft/advancement/adventure/read_power_of_chiseled_bookshelf.json
- minecraft/advancement/adventure/revaulting.json
- minecraft/advancement/adventure/salvage_sherd.json
- minecraft/advancement/adventure/shoot_arrow.json
- minecraft/advancement/adventure/sleep_in_bed.json
- minecraft/advancement/adventure/sniper_duel.json
- minecraft/advancement/adventure/spear_many_mobs.json
- minecraft/advancement/adventure/spyglass_at_dragon.json
- minecraft/advancement/adventure/spyglass_at_ghast.json
- minecraft/advancement/adventure/spyglass_at_parrot.json
- minecraft/advancement/adventure/summon_iron_golem.json
- minecraft/advancement/adventure/throw_trident.json
- minecraft/advancement/adventure/totem_of_undying.json
- minecraft/advancement/adventure/trade_at_world_height.json
- minecraft/advancement/adventure/trade.json
- minecraft/advancement/adventure/trim_with_all_exclusive_armor_patterns.json
- minecraft/advancement/adventure/trim_with_any_armor_pattern.json
- minecraft/advancement/adventure/two_birds_one_arrow.json
- minecraft/advancement/adventure/under_lock_and_key.json
- minecraft/advancement/adventure/use_lodestone.json
- minecraft/advancement/adventure/very_very_frightening.json
- minecraft/advancement/adventure/voluntary_exile.json
- minecraft/advancement/adventure/walk_on_powder_snow_with_leather_boots.json
- minecraft/advancement/adventure/who_needs_rockets.json
- minecraft/advancement/adventure/whos_the_pillager_now.json
+ minecraft/advancement/adventure/wooden_pickaxe.json
- minecraft/advancement/end/dragon_breath.json
- minecraft/advancement/end/dragon_egg.json
- minecraft/advancement/end/elytra.json
- minecraft/advancement/end/enter_end_gateway.json
- minecraft/advancement/end/find_end_city.json
- minecraft/advancement/end/kill_dragon.json
- minecraft/advancement/end/levitate.json
- minecraft/advancement/end/respawn_dragon.json
- minecraft/advancement/end/root.json
- minecraft/advancement/husbandry/allay_deliver_cake_to_note_block.json
- minecraft/advancement/husbandry/allay_deliver_item_to_player.json
- minecraft/advancement/husbandry/axolotl_in_a_bucket.json
- minecraft/advancement/husbandry/balanced_diet.json
- minecraft/advancement/husbandry/bred_all_animals.json
- minecraft/advancement/husbandry/breed_an_animal.json
- minecraft/advancement/husbandry/complete_catalogue.json
- minecraft/advancement/husbandry/feed_snifflet.json
- minecraft/advancement/husbandry/fishy_business.json
- minecraft/advancement/husbandry/froglights.json
- minecraft/advancement/husbandry/kill_axolotl_target.json
- minecraft/advancement/husbandry/leash_all_frog_variants.json
- minecraft/advancement/husbandry/make_a_sign_glow.json
- minecraft/advancement/husbandry/obtain_netherite_hoe.json
- minecraft/advancement/husbandry/obtain_sniffer_egg.json
- minecraft/advancement/husbandry/place_dried_ghast_in_water.json
- minecraft/advancement/husbandry/plant_any_sniffer_seed.json
- minecraft/advancement/husbandry/plant_seed.json
- minecraft/advancement/husbandry/remove_wolf_armor.json
- minecraft/advancement/husbandry/repair_wolf_armor.json
- minecraft/advancement/husbandry/ride_a_boat_with_a_goat.json
- minecraft/advancement/husbandry/root.json
- minecraft/advancement/husbandry/safely_harvest_honey.json
- minecraft/advancement/husbandry/silk_touch_nest.json
- minecraft/advancement/husbandry/tactical_fishing.json
- minecraft/advancement/husbandry/tadpole_in_a_bucket.json
- minecraft/advancement/husbandry/tame_an_animal.json
- minecraft/advancement/husbandry/wax_off.json
- minecraft/advancement/husbandry/wax_on.json
- minecraft/advancement/husbandry/whole_pack.json
- minecraft/advancement/nether/all_effects.json
- minecraft/advancement/nether/all_potions.json
- minecraft/advancement/nether/brew_potion.json
- minecraft/advancement/nether/charge_respawn_anchor.json
- minecraft/advancement/nether/create_beacon.json
- minecraft/advancement/nether/create_full_beacon.json
- minecraft/advancement/nether/distract_piglin.json
- minecraft/advancement/nether/explore_nether.json
- minecraft/advancement/nether/fast_travel.json
- minecraft/advancement/nether/find_bastion.json
- minecraft/advancement/nether/find_fortress.json
- minecraft/advancement/nether/get_wither_skull.json
- minecraft/advancement/nether/loot_bastion.json
- minecraft/advancement/nether/netherite_armor.json
- minecraft/advancement/nether/obtain_ancient_debris.json
- minecraft/advancement/nether/obtain_blaze_rod.json
- minecraft/advancement/nether/obtain_crying_obsidian.json
- minecraft/advancement/nether/return_to_sender.json
- minecraft/advancement/nether/ride_strider_in_overworld_lava.json
- minecraft/advancement/nether/ride_strider.json
- minecraft/advancement/nether/root.json
- minecraft/advancement/nether/summon_wither.json
- minecraft/advancement/nether/uneasy_alliance.json
- minecraft/advancement/story/cure_zombie_villager.json
- minecraft/advancement/story/deflect_arrow.json
- minecraft/advancement/story/enchant_item.json
- minecraft/advancement/story/enter_the_end.json
- minecraft/advancement/story/enter_the_nether.json
- minecraft/advancement/story/follow_ender_eye.json
- minecraft/advancement/story/form_obsidian.json
- minecraft/advancement/story/iron_tools.json
- minecraft/advancement/story/lava_bucket.json
- minecraft/advancement/story/mine_diamond.json
- minecraft/advancement/story/mine_stone.json
- minecraft/advancement/story/obtain_armor.json
- minecraft/advancement/story/root.json
- minecraft/advancement/story/shiny_gear.json
- minecraft/advancement/story/smelt_iron.json
- minecraft/advancement/story/upgrade_tools.json
+ minecraft/loot_table/blocks/copper_trap.json
+ minecraft/loot_table/blocks/exposed_copper_trap.json
+ minecraft/loot_table/blocks/iron_trap.json
+ minecraft/loot_table/blocks/oxidized_copper_trap.json
+ minecraft/loot_table/blocks/waxed_copper_trap.json
+ minecraft/loot_table/blocks/waxed_exposed_copper_trap.json
+ minecraft/loot_table/blocks/waxed_oxidized_copper_trap.json
+ minecraft/loot_table/blocks/waxed_weathered_copper_trap.json
+ minecraft/loot_table/blocks/weathered_copper_trap.json
+ minecraft/structure/herding/nine_by_nine_copper_torch.nbt
+ minecraft/structure/herding/nine_by_nine_soul_torch.nbt
+ minecraft/structure/herding/nine_by_nine.nbt
+ minecraft/tags/block/builds_into_house.json
+ minecraft/tags/block/cow_food.json
+ minecraft/tags/block/living_block_takes_fall_damage.json
+ minecraft/tags/block/pig_food.json
+ minecraft/tags/block/sheep_food.json
+ minecraft/tags/item/block_placers.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/copper_trap.json
+ minecraft/blockstates/exposed_copper_trap.json
+ minecraft/blockstates/iron_trap.json
+ minecraft/blockstates/oxidized_copper_trap.json
+ minecraft/blockstates/waxed_copper_trap.json
+ minecraft/blockstates/waxed_exposed_copper_trap.json
+ minecraft/blockstates/waxed_oxidized_copper_trap.json
+ minecraft/blockstates/waxed_weathered_copper_trap.json
+ minecraft/blockstates/weathered_copper_trap.json
+ minecraft/items/attack_action.json
+ minecraft/items/build_action.json
+ minecraft/items/copper_trap.json
+ minecraft/items/crafting_action.json
+ minecraft/items/exposed_copper_trap.json
+ minecraft/items/follow_action.json
+ minecraft/items/group_action.json
+ minecraft/items/highlight_action.json
+ minecraft/items/iron_trap.json
+ minecraft/items/move_action.json
+ minecraft/items/oxidized_copper_trap.json
+ minecraft/items/punch_action.json
+ minecraft/items/waxed_copper_trap.json
+ minecraft/items/waxed_exposed_copper_trap.json
+ minecraft/items/waxed_oxidized_copper_trap.json
+ minecraft/items/waxed_weathered_copper_trap.json
+ minecraft/items/weathered_copper_trap.json
+ minecraft/models/block/copper_trap.json
+ minecraft/models/block/exposed_copper_trap.json
+ minecraft/models/block/iron_trap.json
+ minecraft/models/block/oxidized_copper_trap.json
+ minecraft/models/block/waxed_copper_trap.json
+ minecraft/models/block/waxed_exposed_copper_trap.json
+ minecraft/models/block/waxed_oxidized_copper_trap.json
+ minecraft/models/block/waxed_weathered_copper_trap.json
+ minecraft/models/block/weathered_copper_trap.json
+ minecraft/models/item/attack_action.json
+ minecraft/models/item/attack_signalling_arrow.json
+ minecraft/models/item/build_action.json
+ minecraft/models/item/crafting_action.json
+ minecraft/models/item/follow_action.json
+ minecraft/models/item/group_action.json
+ minecraft/models/item/highlight_action.json
+ minecraft/models/item/move_action.json
+ minecraft/models/item/punch_action.json
+ minecraft/textures/entity/command/attack.png
+ minecraft/textures/entity/command/build.png
+ minecraft/textures/entity/command/follow.png
+ minecraft/textures/entity/command/move.png
+ minecraft/textures/entity/crafting_grid/2x2.png
+ minecraft/textures/entity/crafting_grid/3x3.png
+ minecraft/textures/gui/title/background/af/panorama_0.png
+ minecraft/textures/gui/title/background/af/panorama_1.png
+ minecraft/textures/gui/title/background/af/panorama_2.png
+ minecraft/textures/gui/title/background/af/panorama_3.png
+ minecraft/textures/gui/title/background/af/panorama_4.png
+ minecraft/textures/gui/title/background/af/panorama_5.png
+ minecraft/textures/gui/title/herdcraft.png
+ minecraft/textures/item/attack_action.png
+ minecraft/textures/item/attack_signalling_arrow.png
+ minecraft/textures/item/build_action.png
+ minecraft/textures/item/crafting_action.png
+ minecraft/textures/item/follow_action.png
+ minecraft/textures/item/group_action_overlay.png
+ minecraft/textures/item/group_action.png
+ minecraft/textures/item/highlight_action.png
+ minecraft/textures/item/move_action.png
+ minecraft/textures/item/punch_action.png
+ minecraft/textures/item/signalling_arrow.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
splashes
</summary>

```diff
- ...!
- .party()!
- "Almost never" is an interesting concept!
- "Autological" is!
- [this splash text is now available]
- §1C§2o§3l§4o§5r§6m§7a§8t§9i§ac
- §kFUNKY LOL
- /give @a hugs 64
- #minecraftfarms
- <3 Max & 99 & Ducky!
- 1% sugar!
- 100% pure!
- 12 herbs and spices!
- 12345 is a bad password!
+ 15 minutes 6 seconds!
- 15 years of Mining and Crafting!
- 150 bpm for 400000 minutes!
- 150% hyperbole!
- 20 GOTO 10!
+ 26w14a!
+ 272 Cobblestone!
- 4815162342 lines of code!
- 90% bug free!
- 90210!
+ A blockade.
- A riddle, wrapped in a mystery!
- A skeleton popped out!
- Absolutely fixed relatively broken coordinates
- Absolutely no memes!
- Afraid of the big, black bat!
- Age of Wonders is better!
- Ahhhhhh!
- All inclusive!
- All is full of love!
- All rumors are true!
- Also try Braid!
- Also try Limbo!
- Also try Minecraft Dungeons!
- Also try Mount And Blade!
- Also try Pixeljunk Shooter!
- Also try Project Zomboid!
- Also try Super Meat Boy!
- Also try Terraria!
- Also try VVVVVV!
- Also try World of Goo!
- Amplify and listen to BIPOC voices!
- An illusion! What are you hiding?
- And my pickaxe!
- Any computer is a laptop if you're brave enough!
+ Anything can be an entity if you try hard enough
- As seen on TV!
- Ask your doctor!
+ Auto-Assembling Automata
- Autonomous!
- Awesome community!
- Awesome game design right there!
- Awesome!
- Aww man!
- Be anti-racist!
+ Beautiful Block Balloons
- Bees, bees, bees, bees!
- Bekarton guards the gate!
- Best in class!
- Big Pointy Teeth!
- Bigger than a bread box!
+ Biggest herd in town!
- Black lives matter!
+ Blocked.
- Blue warrior shot the food!
- Board game version also available!
- Boats FTW
- Boots with the fur!
- Bread is pain!
- Bring it on!
- Bring me Ray Cokes!
- Bringing home the bacon!
- BTAF used to be good!
- Buckets of lava!
- Bushy eyebrows!
- Buzzy Bees!
- Call your mother!
- Casual gaming!
- Ceci n'est pas une title screen!
- Check it out!
- Check out the far lands!
- Chicken Jockey!
- Child's play!
- Classy!
- Closed source!
- Cloud computing!
- Cogito ergo sum!
- Collaborate and listen!
- Complex cellular automata!
- Consummate V's!
- Contains infinite genders!
- Contains simulated goats!
- Conventional!
- Cough or sneeze into your elbow!
- Cow Tools!
+ Cozy dirt house!
- Create!
- Croak team!
- Cruising streets for gold!
+ Cute Cuboid Companions
- Cześć Polsko!
- Déjà vu!
- Déjà vu!
- Do it all, everything!
- Do not distribute!
- Do you want to join my server?
- Does barrel rolls!
- Doesn't avoid double negatives!
- Doesn't use the U-word!
- Don't bother with the clones!
- Don't feed avocados to parrots!
- Don't feed chocolate to parrots!
+ Don't let the wool float away
+ Don't let your tools loose!
- Don't look directly at the bugs!
- Don’t touch your face!
- Don't worry, be happy!
- doot doot
- Double buffered!
- DRR! DRR! DRR!
- Dungeon!
- DungeonQuest is unfair!
- Edit is a name!
- Educate your friends on anti-racism!
- Engage!
- Enhanced!
+ Enough balloons make you walk on water
- Envision! Create! Share!
- Eple (original edit)!
- Euclidian!
- Everybody do the Leif!
- Excitement!
- Exclusive!
- Exploding creepers!
- Extra things!
- Fabulous graphics!
- Falling off cliffs!
- Falling with style!
- Fan fiction!
- Fantasy!
- Fat free!
- Feature packed!
+ Fifteen years of ... whatever this is!
- Finally complete!
- Finally with ladders!
- Find your claw!
- Finger-licking!
+ Flashes make so much light
- Flashing letters!
- Flavor with no seasoning!
- Flaxkikare!
- Flint and Steel!
- Flower forest TM perfume
- Fnord!
- Follow the train, CJ!
- Freaky!
- Free dental!
- From free range developers!
- From the streets of Södermalm!
- Full of stars!
- Funk soul brother!
- Gamers unite – separately in your own homes!
- Gargamel plays it!
- Gasp!
- Get to the coppah!
- Ghoughpteighbteau tchoghs!
- Give us Gordon!
- GNU Terry Pratchett
- Go to the dentist!
+ Gooey!
- Google anlyticsed!
- Got your nose!
- GOTY!
- Guaranteed!
- Haha, LOL!
- Haley loves Elan!
- Hampsterdance!
- Han shot first!
- Hang out with your friends online!
- Hard to label!
- Has an ending!
- Has working bookshelves!
- Hat Fridays!
- Haunted!
+ Have you herd the news? The blocks came alive!
- Heaps of hits on YouTube!
- Helo Cymru!
- Herregud!
- Holy cow, man!
- Home-made!
- Homeomorphic to a 3-sphere!
- Honey, I grew the bees!
- Honey, I waxed the copper!
- Hot tamale, hot hot tamale!
- Hotter than the sun!
+ Hungry, hungry chests
- HURNERJSGER?
- I have a suggestion.
- I miss ADOM!
- I need more context.
- I see your vocabulary has improved!
- I'm glad you're here!
- idspispopd!
- if not ok then return end
- In case it isn't obvious, foxes aren't players.
- Indev!
- Indie!
- Information wants to be free!
- Ingots!
- Inspirational!
- Internet enabled!
- It came from space.
- It swings, it jives!
- It's a game!
+ It's alive!
- It's finished!
- It's groundbreaking!
- It's here!
- Jag känner en bot!
- Jason! Jason! Jason!
- Java 16 + 1 + 4 * 2 = 25!
- Javalicious edition
- Jeb has amazing hair!
- Joel is neat!
- Joule is neat too!
- Jump up, jump up, and get down!
- Kaaneeeedaaaa!
- Keyboard compatible!
- Khaaaaaaaaan!
- Kick it root down!
- Kind of dragon free!
- Kinda like Lemmings!
- Kiss the sky!
- l33t!
+ Large block the size of a small block
- Larger than Earth!
- Learn about allyship!
- Legal in Finland!
- Lennart lennart = new Lennart();
- Less addictive than TV Tropes!
- Let our battle's begin!
- Let's danec!
- Leveraging synergy!
+ Lightning for the miners
+ Like sleeping in a tumble dryer
- Limited edition!
- Lives in a pineapple under the sea!
- Livestreamed!
- Look mum, I'm in a splash!
- Lots of truthiness!
- Loved by millions!
- Macroscopic!
- Made by "real" people!
- Made by Jeb!
- Made in Sweden!
- Made with lave!
- Make me a table, a funky table!
- MAP11 has two names!
+ Marching Cubes!
- Matt Damon!
- May contain nuts!
- May contain traces of citrus!
- Meeting expectations!
- Menger sponge!
- Millions of peaches!
- Minecraft Java Edition presents: Disgusting Bugs
- Minecraft!
- Mmmph, mmph!
- Moderately attractive!
- Monster infighting!
- More addictive than lemonade!
- More Digital!
- More polygons!
- More than 500 sold!
+ Moving Block Entities!
- Music by Aaron Cherof!
- Music by Amos Roddy!
- Music by C418!
- Music by Hyper Potions!
- Music by Kumi Tanioka!
- Music by Lena Raine!
- My life for Aiur!
- Never dig down!
- Nice to meet you!
+ Nom nom nom!
- Nooooooooooooo!
- Not as cool as Spock!
- Not linear!
- Not on steam!
- Now contains 32 random daily cats!
- Now in 3D!
- Now on OpenGL 3.3 core profile!
- Now supports åäö!
- Now with additional stuff!
- Now with difficulty!
- Now with extra hugs!
- Now With Multiplayer!
- Now you are thinking with pistons!
- NP is not in P!
- Octagonal!
- Oh man!
- Oh, ok, Pigmen!
- OICU812!
- Omnipotent!
- One day, somewhere in the future, my work will be quoted!
- One does not simply walk to the Far Lands
- One of a kind!
- PC gaming since 1873!
- Peter Griffin!
- Ph1lza had a good run!
- Phobos anomaly!
- Ping the human!
- Pixels!
- Place ALL the blocks!
- Place hanging sign here
- Plant a tree!
- Plant-based light sources!
- Play him off, keyboard cat!
- Play Minecraft, Watch Topgear, Get Pig!
- Played by cowboys!
- pls rt
- Plz reply to my tweet!
- Pneumatic!
+ Pogo Tools
- Polynomial!
- Prepare, but don’t hoard!
- Pretty scary!
- Pretty!
- Pumpakungen!
- Pumpkinhead!
- Punching wood!
- Put a little fence around it!
- Put that cookie down!
- Rainbow turtle?
- Random splash!
- Read more books!
- Reference implementation!
- Regional resources!
- Remember to brush your... ...teeth
- Replaced molten cheese with blood?
- Representing Edsbyn!
- Reticulating splines!
- RIBBIT!
- Ride the pig!
- Rise from your grave!
- Rita is the new top dog!
- Rule #1: it's never my fault
- Run, coward! I hunger!
- Ryan also has amazing hair!
- Save the world – stay inside!
- Scary!
- Scientific!
- See you next Friday or so!
- Seecret Friday update!
- Sensational!
+ Several blocks at a time!
- Shop for your elders!
- Should not be played while driving
- Shriek like a Sculk Shrieker!
- Singleplayer!
+ Slice some blocks into the lime group
- Slow acting portals!
- Sniff sniff...
- So fresh, so clean!
- So sweet, like a nice bon bon!
- Soap and water!
- Something funny!
- Something's not quite right...
- Speak OUT against injustice and UP for equality!
- Spiders everywhere!
- sqrt(-1) love you!
- Stand up for equality in your community!
- Stay a while and listen!
- Stay a while, stay forever!
- Stay home and play games!
- Stay safe!
- Stay strong!
- Stop being reasonable, this is the Internet!
- Stop, hammertime!
- Strange, but not a stranger!
- Sublime!
- Supercalifragilisticexpialidocious!
- Support elderly relatives and friends!
- Support local businesses!
- Support the BIPOC community and creators!
- Survive!
- SWM forever!
- Swords for everyone!
- Synecdoche!
- Take an eggbeater and beat it against a skillet!
- Take frequent breaks!
- Take her pillow!
- Take the elevator to the mezzanine!
- Technically good!
- Technoblade never dies!
- Technologic!
- Teetsuuuuoooo!
- Tell your friends!
- Terrestrial!
- Testificates!
- Thank you for the fish!
- That's no moon!
- That's Numberwang!
- That's super!
- The bee's knees!
- The creeper is a spy!
- The cutest predator you'll ever meet!
- The sky is the limit!
- The sum of its parts!
+ The true meaning of block game
- The true meaning of covfefe
- Thematic!
- There's <<a cat on ,my keyboard!~
- There's no stopping the Trollmaso
+ They see me rolling!
- This is good for Realms.
- This is my true form!
- This message will never appear on the splash screen, isn't that weird?
- This parrot is no more! It has ceased to be!
+ This portal is §mnot§r going to build itself
- This sand is sus
- This text is hard to read if you play the game at the default resolution, but at 1080p it's fine!
- Thousands of colors!
- Throw a blanket over it!
- Throw yourself at the ground and miss
- Tip your waiter!
- Tougher than diamonds, rich like cream!
- Treatment for your rash!
- Truly gone fishing!
- Try it!
- Try the mushroom stew!
- Try the Nether!
- Turing complete!
- Twittered about!
- Tyrion would love it!
- Ultimate edition!
- umop-apisdn!
- Undefeated!
- Une baguette!
- Uninflammable!
- Uses LWJGL!
- Vanilla!
- Verlet integration!
- Very fun!
- Very influential in its circle!
- Vote for net neutrality!
- Warning! A huge battleship "STEVE" is approaching fast!
- Wash your hands!
+ Watch out for traps!
- Water bottle!
- Water proof!
+ We solved the inventory problem!
- Welcome to your Doom!
- What do you expect?
+ What is the collective noun for a group of blocks?
+ What's an item entity?
+ What's that mysterious clicking noise?
- What's the question?
- What's up, Doc?
- Where there is not light, there can spider!
+ Who Let the Blocks Out?
- Who let the frogs out?
- Who put it there?
- Whoa, dude!
+ Why, you stuck-up, half-witted, scruffy-looking block herder!
- Woah.
- Woo, 2pp!
- Woo, facepunch!
- Woo, reddit!
- Woo, somethingawful!
- Woo, tigsource!
- Woo, worldofminecraft!
+ Wool is lighter than air
- Wow!
- Yaaay!
- Yay, puppies for everyone!
- Yes, sir!
- You are valid!
- You are welcome here!
- You can't explain that!
- You're going too fast!
- You've got a brand new key!
- Your gender is valid!
- Zoglin!?
- Γεια σου Ελλάδα!
- 한국 안녕하세요!
- 你好中国！
- 日本ハロー！
```

</details>
</details>
<hr/>