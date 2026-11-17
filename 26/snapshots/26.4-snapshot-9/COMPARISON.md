## Comparison with [26.4-snapshot-8](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.4-snapshot-8)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.4-snapshot-8</th><th>26.4-snapshot-9</th></tr><tr><td>DataPack version</td><td><pre>127.0</pre></td><td><pre>128.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>103.0</pre></td><td><pre>104.0</pre></td></tr><tr><td>World version</td><td><pre>5128</pre></td><td><pre>5129</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742170</pre></td><td><pre>1073742171</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.4-snapshot-8</th><th>26.4-snapshot-9</th></tr><tr><td>com.mojang:authlib</td><td><pre>12.0.81</pre></td><td><pre>12.0.82</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ dispense_behavior_type.txt
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
+ minecraft:greedy_string
+ minecraft:quoted_string
- minecraft:string
+ minecraft:word
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:dispense_behavior
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ universal_tags/dispense_behavior_type.json
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:greedy_string
+ minecraft:quoted_string
- minecraft:string
+ minecraft:word
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:dispense_behavior
```

</details>
</details>
<hr/>
<details><summary><b><ins>DATAPACKS</ins></b><a name="datapacks"></a></summary>
<br/>
<details>
<summary>
[registries] List
</summary>

```diff
+ minecraft:dispense_behavior
+ minecraft:dispense_behavior_type
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
+ container.creative_inventory: Creative Inventory
+ gui.recipebook.filter: Recipe filter
+ gui.recipebook.moreRecipes.keyboard: Control + Enter for More
+ gui.recipebook.search_box: Search recipes
+ gui.recipebook.tab.all: All Recipes
+ key.repeatRecipeOrTrade: Repeat Recipe/Trade
+ menu.custom_screen_info.input.tooltip: Warning: It looks like you might be entering personal information like account information. Never enter login details into an in-game form.
+ narration.creative_item: %s, %s
+ narration.creative_item.located: %s, %s, %s
+ narration.recipe_book.current_page: Current page %1$s of %2$s
+ narration.recipe.usage.close: Press Escape to close
+ narration.recipe.usage.more.keyboard: Press Control + Enter to show more recipes
+ narration.slot.usage.focused.destroy: Press Enter to destroy %s
+ narration.slot.usage.hovered.destroy: Left-click to destroy %s
+ narration.tab_navigation.bottom: bottom row
+ narration.tab_navigation.top: top row
+ narrator.position.tab.index: %s out of %s
+ narrator.position.tab.named: Selected %1$s tab %2$s
+ options.improvedFog: Improved Fog
+ options.improvedFog.tooltip: Blends the sky background with render distance-based fog to make the boundary between the terrain and the sky less visible. When disabled, the fog is a solid color.
If Improved Transparency is also enabled, the clouds will be blended with the fog as well.
+ options.improvedTransparency.oitWithCloudsInFog.tooltip: An experimental approach that uses an order-independent transparency algorithm to avoid graphical issues normally present when looking through multiple layers of translucent objects.
If Improved Fog is also enabled, the clouds will be blended with render distance-based fog as well.
This will impact performance.
+ recipe_book_category.minecraft.blast_furnace_blocks: Blocks
+ recipe_book_category.minecraft.blast_furnace_misc: Miscellaneous
+ recipe_book_category.minecraft.crafting_building_blocks: Building Blocks
+ recipe_book_category.minecraft.crafting_equipment: Equipment
+ recipe_book_category.minecraft.crafting_misc: Miscellaneous
+ recipe_book_category.minecraft.crafting_redstone: Redstone
+ recipe_book_category.minecraft.furnace_blocks: Blocks
+ recipe_book_category.minecraft.furnace_food: Food
+ recipe_book_category.minecraft.furnace_misc: Miscellaneous
+ recipe_book_category.minecraft.smoker_food: Food
- upgradeWorld.progress.type.region: Upgrading regions
+ upgradeWorld.progress.type.regions: Upgrading regions
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.4-snapshot-8</th><th>26.4-snapshot-9</th></tr>
<tr><th align="left"><div style="width:290px">chat.queue.tooltip</div></th><td>Click to display next message</td><td>Click to display the next message</td></tr>
<tr><th align="left"><div style="width:290px">command.trailing_data</div></th><td>Trailing data found: %s</td><td>Trailing data found '%s'</td></tr>
<tr><th align="left"><div style="width:290px">commands.data.modify.invalid_substring</div></th><td>Invalid substring indices: %s to %s</td><td>Invalid substring indices '%s' to '%s'</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.objectives.modify.objectiveFormat.clear</div></th><td>Cleared default number format of objective %s</td><td>Cleared the default number format of objective %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.objectives.modify.objectiveFormat.set</div></th><td>Changed default number format of objective %s</td><td>Changed the default number format of objective %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.display.name.clear.success.multiple</div></th><td>Cleared display name for %s entities in %s</td><td>Cleared the display name for %s entities in %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.display.name.clear.success.single</div></th><td>Cleared display name for %s in %s</td><td>Cleared the display name for %s in %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.display.name.set.success.multiple</div></th><td>Changed display name to %s for %s entities in %s</td><td>Changed the display name to %s for %s entities in %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.display.name.set.success.single</div></th><td>Changed display name to %s for %s in %s</td><td>Changed the display name to %s for %s in %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.display.numberFormat.clear.success.multiple</div></th><td>Cleared number format for %s entities in %s</td><td>Cleared the number format for %s entities in %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.display.numberFormat.clear.success.single</div></th><td>Cleared number format for %s in %s</td><td>Cleared the number format for %s in %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.display.numberFormat.set.success.multiple</div></th><td>Changed number format for %s entities in %s</td><td>Changed the number format for %s entities in %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.display.numberFormat.set.success.single</div></th><td>Changed number format for %s in %s</td><td>Changed the number format for %s in %s</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.send.json_error</div></th><td>Encountered malformed payload while sending your report.</td><td>Encountered a malformed payload while sending your report.</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.empty_nickname</div></th><td>Enter a valid profile name before sending a friend request</td><td>Enter a valid profile name before sending a friend request.</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.error.failed.message</div></th><td>Unable to send your friend request right now</td><td>Unable to send your friend request right now.</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.error.user_may_lack_active_profile</div></th><td>There is no player with this profile name</td><td>There is no player with this profile name.</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.narration.button.accept</div></th><td>Press enter to accept friend request from %s</td><td>Press enter to accept the friend request from %s</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.narration.button.cancel_request</div></th><td>Press enter to cancel friend request to %s</td><td>Press enter to cancel the friend request to %s</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.narration.button.decline</div></th><td>Press enter to decline friend request from %s</td><td>Press enter to decline the friend request from %s</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.narration.button.unfriend</div></th><td>Press enter to remove %s from Friends List</td><td>Press enter to remove %s from your Friends List</td></tr>
<tr><th align="left"><div style="width:290px">jigsaw_block.placement_priority.tooltip</div></th><td>When this Jigsaw block connects to a piece, this is the order in which that piece is processed for connections in the wider structure.



Pieces will be processed in descending priority with insertion order breaking ties.</td><td>When this Jigsaw Block connects to a piece, this is the order in which that piece is processed for connections in the wider structure.



Pieces will be processed in descending priority with insertion order breaking ties.</td></tr>
<tr><th align="left"><div style="width:290px">jigsaw_block.selection_priority.tooltip</div></th><td>When the parent piece is being processed for connections, this is the order in which this Jigsaw block attempts to connect to its target piece.



Jigsaws will be processed in descending priority with random ordering breaking ties.</td><td>When the parent piece is being processed for connections, this is the order in which this Jigsaw Block attempts to connect to its target piece.



Jigsaws will be processed in descending priority with random ordering breaking ties.</td></tr>
<tr><th align="left"><div style="width:290px">menu.playerReporting.no_players</div></th><td>There are no players to report in this world</td><td>There are no players to report in this world.</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.status.unrequested</div></th><td>Received unrequested status</td><td>Received an unrequested status</td></tr>
<tr><th align="left"><div style="width:290px">snbt.parser.invalid_codepoint</div></th><td>Invalid Unicode character value: %s</td><td>Invalid Unicode character value '%s'</td></tr>
<tr><th align="left"><div style="width:290px">snbt.parser.no_such_operation</div></th><td>No such operation: %s</td><td>No such operation '%s'</td></tr>
<tr><th align="left"><div style="width:290px">snbt.parser.number_parse_failure</div></th><td>Failed to parse number: %s</td><td>Failed to parse number '%s'</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.burn</div></th><td>Burning</td><td>Something burns</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.death</div></th><td>Dying</td><td>Something dies</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.drink</div></th><td>Sipping</td><td>Something sips</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.eat</div></th><td>Eating</td><td>Something eats</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.explode</div></th><td>Explosion</td><td>Something explodes</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.splash</div></th><td>Splashing</td><td>Something splashes</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.swim</div></th><td>Swimming</td><td>Something swims</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.lead.tied</div></th><td>Lead tied</td><td>Lead is tied</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.lead.untied</div></th><td>Lead untied</td><td>Lead is untied</td></tr>
<tr><th align="left"><div style="width:290px">test.error.invalid_block_type</div></th><td>Unexpected block type found: %s</td><td>Unexpected block type found '%s'</td></tr>
<tr><th align="left"><div style="width:290px">test.error.wrong_block_entity</div></th><td>Wrong block entity type: %s</td><td>Wrong block entity type '%s'</td></tr>
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
+ minecraft/block_sound_set/fire.json
+ minecraft/block_transformer/honeycomb.json
+ minecraft/dispense_behavior/armor_stand.json
+ minecraft/dispense_behavior/boat.json
+ minecraft/dispense_behavior/bone_meal.json
+ minecraft/dispense_behavior/brush.json
+ minecraft/dispense_behavior/carved_pumpkin.json
+ minecraft/dispense_behavior/chest.json
+ minecraft/dispense_behavior/default_projectile.json
+ minecraft/dispense_behavior/default.json
+ minecraft/dispense_behavior/dropper.json
+ minecraft/dispense_behavior/empty_bucket.json
+ minecraft/dispense_behavior/equipment.json
+ minecraft/dispense_behavior/filled_bucket.json
+ minecraft/dispense_behavior/fire_charge.json
+ minecraft/dispense_behavior/firework_rocket.json
+ minecraft/dispense_behavior/flint_and_steel.json
+ minecraft/dispense_behavior/glass_bottle.json
+ minecraft/dispense_behavior/glowstone.json
+ minecraft/dispense_behavior/honeycomb.json
+ minecraft/dispense_behavior/minecart.json
+ minecraft/dispense_behavior/potion.json
+ minecraft/dispense_behavior/shears.json
+ minecraft/dispense_behavior/shulker_box.json
+ minecraft/dispense_behavior/spawn_egg.json
+ minecraft/dispense_behavior/thrown_potion.json
+ minecraft/dispense_behavior/tnt.json
+ minecraft/dispense_behavior/wind_charge.json
+ minecraft/dispense_behavior/wither_skeleton_skull.json
+ minecraft/tags/damage_type/cannot_hurt_perching_ender_dragon.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/block/ice_crystal.png.mcmeta
+ minecraft/textures/gui/sprites/recipe_book/slot_highlight_back.png
+ minecraft/textures/gui/sprites/recipe_book/slot_highlight_front.png
+ minecraft/textures/gui/title/mojangstudios.png.mcmeta
```

</details>
</details>
<hr/>