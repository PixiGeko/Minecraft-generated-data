## Comparison with [18w20a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w20a)

- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Misc](#misc)

<hr/>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ glistering_melon_slice.json
- melon_block.json
+ melon.json
- speckled_melon.json
```

</details>
</details>
<details><summary>Translations</summary>
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

```
selectWorld.versionJoinButton: UseLoad Anyway
createWorld.customize.buffet.generatortype: World generator :
multiplayer.disconnect.banned: You are banned from this server.
multiplayer.disconnect.ip_banned: You have been IP banned. from this server
multiplayer.disconnect.kicked: Kicked by an operator.
multiplayer.disconnect.name_taken: That name is already taken.
demo.day.6: You have passed your fifth day, use F2{} to save a screenshot of your creation
disconnect.loginFailed: Failed to log in
disconnect.loginFailedInfo: Failed to log in: %s
options.narrator.off: OffFF
entity.minecraft.ender_crystal: Ender Crystal
entity.minecraft.tnt: Block ofPrimed TNT
death.attack.hotFloor: %1$s discovered the floor was lava
death.attack.mob.item: %1$s was slaimn by %2$s using %3$s
stat.minecraft.play_record: RecordMusic Discs Played
subtitles.entity.generic.small_fall: Something trippeds
subtitles.entity.llama.angry: Llama bleats angrily
subtitles.turtle.ambient_land: Turtle chirps
subtitles.item.armor.equip: Gear equippeds
subtitles.item.armor.equip_elytra: Elytra rustles
debug.crash.message: FC3 + C is held down. This will crash the game unless released.
advancements.adventure.sleep_in_bed.title: Sweet dDreams
advancements.adventure.sniper_duel.title: Sniper dDuel
advancements.adventure.sniper_duel.description: Kill a sSkeleton with an arrow from more than 50 meters
advancements.end.elytra.description: Find an Elytra
advancements.end.respawn_dragon.description: Respawn the eEnder dDragon
advancements.nether.get_wither_skull.description: Obtain a wWither sSkeleton's skull
advancements.nether.fast_travel.description: Use the Nether to travel 7 km in the Overworld
advancements.nether.uneasy_alliance.description: Rescue a Ghast from the Nether, bring it safely home to the Overworld... and then kill it.
advancements.story.cure_zombie_villager.description: Weaken and then cure a zZombie vVillager
advancements.story.follow_ender_eye.description: Follow an Eye of Ender Eye
argument.entity.options.dx.description: Entities between x and x + dx
argument.entity.options.dy.description: Entities between y and y + dy
argument.entity.options.dz.description: Entities between z and z + dz
commands.whitelist.enabled: Whitelist is now turned on.
commands.whitelist.disabled: Whitelist is now turned off.
```

</details>
</details>
<details><summary>File structure</summary>
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
<details><summary>Misc</summary>
<details>
<summary>
splashes
</summary>

```diff
+ All rumors are true!
```

</details>
</details>