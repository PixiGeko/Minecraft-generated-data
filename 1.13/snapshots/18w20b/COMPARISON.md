## Comparison with [18w20a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w20a)

> [!TIP]
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- melon_block.json
+ melon.json
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
+ glistering_melon_slice.json
- melon_block.json
+ melon.json
- speckled_melon.json
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
- block.minecraft.melon_block: Melon
+ block.minecraft.melon: Melon
+ block.minecraft.potted_acacia_sapling: Potted Acacia Sapling
+ block.minecraft.potted_allium: Potted Allium
+ block.minecraft.potted_azure_bluet: Potted Azure Bluet
+ block.minecraft.potted_birch_sapling: Potted Birch Sapling
+ block.minecraft.potted_blue_orchid: Potted Blue Orchid
+ block.minecraft.potted_brown_mushroom: Potted Brown Mushroom
+ block.minecraft.potted_cactus: Potted Cactus
+ block.minecraft.potted_dandelion: Potted Dandelion
+ block.minecraft.potted_dark_oak_sapling: Potted Dark Oak Sapling
+ block.minecraft.potted_dead_bush: Potted Dead Bush
+ block.minecraft.potted_fern: Potted Fern
+ block.minecraft.potted_jungle_sapling: Potted Jungle Sapling
+ block.minecraft.potted_oak_sapling: Potted Oak Sapling
+ block.minecraft.potted_orange_tulip: Potted Orange Tulip
+ block.minecraft.potted_oxeye_daisy: Potted Oxeye Daisy
+ block.minecraft.potted_pink_tulip: Potted Pink Tulip
+ block.minecraft.potted_poppy: Potted Poppy
+ block.minecraft.potted_red_mushroom: Potted Red Mushroom
+ block.minecraft.potted_red_tulip: Potted Red Tulip
+ block.minecraft.potted_spruce_sapling: Potted Spruce Sapling
+ block.minecraft.potted_white_tulip: Potted White Tulip
+ item.minecraft.glistering_melon_slice: Glistering Melon Slice
+ item.minecraft.melon_slice: Melon Slice
- item.minecraft.melon: Melon Slice
- item.minecraft.speckled_melon: Glistering Melon
+ realms.missing.module.error.text: Realms could not be opened right now, please try again later
+ realms.missing.snapshot.error.text: Realms is currently not supported in snapshots
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>18w20a</th><th>18w20b</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.versionJoinButton</div></th><td>Use Anyway</td><td>Load Anyway</td></tr>
<tr><th align="left"><div style="width:290px">createWorld.customize.buffet.generatortype</div></th><td>World generator :</td><td>World generator:</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.banned</div></th><td>You are banned from this server.</td><td>You are banned from this server</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.ip_banned</div></th><td>You have been IP banned.</td><td>You have been IP banned from this server</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.kicked</div></th><td>Kicked by an operator.</td><td>Kicked by an operator</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.name_taken</div></th><td>That name is already taken.</td><td>That name is already taken</td></tr>
<tr><th align="left"><div style="width:290px">demo.day.6</div></th><td>You have passed your fifth day, use F2 to save a screenshot of your creation</td><td>You have passed your fifth day, use {} to save a screenshot of your creation</td></tr>
<tr><th align="left"><div style="width:290px">disconnect.loginFailed</div></th><td>Failed to login</td><td>Failed to log in</td></tr>
<tr><th align="left"><div style="width:290px">disconnect.loginFailedInfo</div></th><td>Failed to login: %s</td><td>Failed to log in: %s</td></tr>
<tr><th align="left"><div style="width:290px">options.narrator.off</div></th><td>Off</td><td>OFF</td></tr>
<tr><th align="left"><div style="width:290px">entity.minecraft.ender_crystal</div></th><td>Ender Crystal</td><td>End Crystal</td></tr>
<tr><th align="left"><div style="width:290px">entity.minecraft.tnt</div></th><td>Block of TNT</td><td>Primed TNT</td></tr>
<tr><th align="left"><div style="width:290px">death.attack.hotFloor</div></th><td>%1$s discovered floor was lava</td><td>%1$s discovered the floor was lava</td></tr>
<tr><th align="left"><div style="width:290px">death.attack.mob.item</div></th><td>%1$s was slaim by %2$s using %3$s</td><td>%1$s was slain by %2$s using %3$s</td></tr>
<tr><th align="left"><div style="width:290px">stat.minecraft.play_record</div></th><td>Records Played</td><td>Music Discs Played</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.small_fall</div></th><td>Something tripped</td><td>Something trips</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.llama.angry</div></th><td>Llama bleats angry</td><td>Llama bleats angrily</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.turtle.ambient_land</div></th><td>Turtle chirp</td><td>Turtle chirps</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.armor.equip</div></th><td>Gear equipped</td><td>Gear equips</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.armor.equip_elytra</div></th><td>Elytra rustles</td><td>Elytra rustle</td></tr>
<tr><th align="left"><div style="width:290px">debug.crash.message</div></th><td>FC + C is held down. This will crash the game unless released.</td><td>F3 + C is held down. This will crash the game unless released.</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.sleep_in_bed.title</div></th><td>Sweet dreams</td><td>Sweet Dreams</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.sniper_duel.title</div></th><td>Sniper duel</td><td>Sniper Duel</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.sniper_duel.description</div></th><td>Kill a skeleton with an arrow from more than 50 meters</td><td>Kill a Skeleton with an arrow from more than 50 meters</td></tr>
<tr><th align="left"><div style="width:290px">advancements.end.elytra.description</div></th><td>Find an Elytra</td><td>Find Elytra</td></tr>
<tr><th align="left"><div style="width:290px">advancements.end.respawn_dragon.description</div></th><td>Respawn the ender dragon</td><td>Respawn the Ender Dragon</td></tr>
<tr><th align="left"><div style="width:290px">advancements.nether.get_wither_skull.description</div></th><td>Obtain a wither skeleton's skull</td><td>Obtain a Wither Skeleton's skull</td></tr>
<tr><th align="left"><div style="width:290px">advancements.nether.fast_travel.description</div></th><td>Use the Nether to travel 7km in the Overworld</td><td>Use the Nether to travel 7 km in the Overworld</td></tr>
<tr><th align="left"><div style="width:290px">advancements.nether.uneasy_alliance.description</div></th><td>Rescue a Ghast from the Nether, bring it safely home to the Overworld... and then kill it.</td><td>Rescue a Ghast from the Nether, bring it safely home to the Overworld... and then kill it</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.cure_zombie_villager.description</div></th><td>Weaken and then cure a zombie villager</td><td>Weaken and then cure a Zombie Villager</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.follow_ender_eye.description</div></th><td>Follow an Ender Eye</td><td>Follow an Eye of Ender</td></tr>
<tr><th align="left"><div style="width:290px">argument.entity.options.dx.description</div></th><td>Entities between x and dx</td><td>Entities between x and x + dx</td></tr>
<tr><th align="left"><div style="width:290px">argument.entity.options.dy.description</div></th><td>Entities between y and dy</td><td>Entities between y and y + dy</td></tr>
<tr><th align="left"><div style="width:290px">argument.entity.options.dz.description</div></th><td>Entities between z and dz</td><td>Entities between z and z + dz</td></tr>
<tr><th align="left"><div style="width:290px">commands.whitelist.enabled</div></th><td>Whitelist is now turned on.</td><td>Whitelist is now turned on</td></tr>
<tr><th align="left"><div style="width:290px">commands.whitelist.disabled</div></th><td>Whitelist is now turned off.</td><td>Whitelist is now turned off</td></tr>
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
+ minecraft/advancements/recipes/brewing/glistering_melon_slice.json
- minecraft/advancements/recipes/brewing/speckled_melon.json
- minecraft/advancements/recipes/building_blocks/melon_block.json
+ minecraft/advancements/recipes/building_blocks/melon.json
+ minecraft/recipes/glistering_melon_slice.json
- minecraft/recipes/melon_block.json
+ minecraft/recipes/melon.json
- minecraft/recipes/speckled_melon.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/melon_block.json
+ minecraft/blockstates/melon.json
- minecraft/models/block/melon_block.json
+ minecraft/models/block/melon.json
+ minecraft/models/item/glistering_melon_slice.json
- minecraft/models/item/melon_block.json
+ minecraft/models/item/melon_slice.json
- minecraft/models/item/speckled_melon.json
+ minecraft/textures/entity/conduit/closed_eye.png
- minecraft/textures/entity/conduit/entity_core.png
+ minecraft/textures/entity/conduit/open_eye.png
+ minecraft/textures/items/glistering_melon_slice.png
+ minecraft/textures/items/melon_slice.png
- minecraft/textures/items/melon.png
- minecraft/textures/items/speckled_melon.png
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
+ All rumors are true!
```

</details>
</details>
<hr/>