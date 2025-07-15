## Comparison with [1.13-pre1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre1)

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
+ stripped_acacia_bark.json
+ stripped_birch_bark.json
+ stripped_dark_oak_bark.json
+ stripped_jungle_bark.json
+ stripped_oak_bark.json
+ stripped_spruce_bark.json
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
+ packed_ice.json
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
+ block.minecraft.stripped_acacia_bark: Stripped Acacia Bark
+ block.minecraft.stripped_birch_bark: Stripped Birch Bark
+ block.minecraft.stripped_dark_oak_bark: Stripped Dark Oak Bark
+ block.minecraft.stripped_jungle_bark: Stripped Jungle Bark
+ block.minecraft.stripped_oak_bark: Stripped Oak Bark
+ block.minecraft.stripped_spruce_bark: Stripped Spruce Bark
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.13-pre1</th><th>1.13-pre2</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.backupWarning</div></th><td>This world was last played in version %s, you are on snapshot %s. Please make a backup in case you experience world corruptions!</td><td>This world was last played in version %s; you are on snapshot %s. Please make a backup in case you experience world corruptions!</td></tr>
<tr><th align="left"><div style="width:290px">options.fullscreen.resolution</div></th><td>FS Resolution</td><td>Fullscreen resolution</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.bed.no_sleep</div></th><td>You can only sleep at night</td><td>You can sleep only at night and during thunderstorms</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.bed.too_far_away</div></th><td>You may not rest now, the bed is too far away</td><td>You may not rest now; the bed is too far away</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.bed.not_safe</div></th><td>You may not rest now, there are monsters nearby</td><td>You may not rest now; there are monsters nearby</td></tr>
<tr><th align="left"><div style="width:290px">structure_block.size_failure</div></th><td>Unable to detect structure size, add corners with matching structure names</td><td>Unable to detect structure size. Add corners with matching structure names</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.sniper_duel.description</div></th><td>Kill a Skeleton from more than 50 meters away</td><td>Kill a Skeleton from at least 50 meters away</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.objectives.list.empty</div></th><td>There are no tracked objectives</td><td>There are no objectives</td></tr>
<tr><th align="left"><div style="width:290px">argument.entity.toomany</div></th><td>Only one entity is allowed, but the provided selector allows more than one.</td><td>Only one entity is allowed, but the provided selector allows more than one</td></tr>
<tr><th align="left"><div style="width:290px">argument.player.toomany</div></th><td>Only one player is allowed, but the provided selector allows more than one.</td><td>Only one player is allowed, but the provided selector allows more than one</td></tr>
<tr><th align="left"><div style="width:290px">argument.player.entities</div></th><td>Only players may be affected by this command, but the provided selector includes entities.</td><td>Only players may be affected by this command, but the provided selector includes entities</td></tr>
<tr><th align="left"><div style="width:290px">arguments.nbtpath.node.invalid</div></th><td>Invalid nbt path, expected element name or index</td><td>Invalid NBT path, expected element name or index</td></tr>
<tr><th align="left"><div style="width:290px">arguments.swizzle.invalid</div></th><td>Invalid swizzle, expected combination of 'x' 'y' and 'z'</td><td>Invalid swizzle, expected combination of 'x', 'y' and 'z'</td></tr>
<tr><th align="left"><div style="width:290px">argument.entity.invalid</div></th><td>Invalid name or uuid</td><td>Invalid name or UUID</td></tr>
<tr><th align="left"><div style="width:290px">argument.entity.options.level.negative</div></th><td>Level negative</td><td>Level shouldn't be negative</td></tr>
<tr><th align="left"><div style="width:290px">commands.banip.failed</div></th><td>Nothing changed, that IP is already banned</td><td>Nothing changed. That IP is already banned</td></tr>
<tr><th align="left"><div style="width:290px">commands.ban.failed</div></th><td>Nothing changed, the player is already banned</td><td>Nothing changed. The player is already banned</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.set.players.unchanged</div></th><td>Nothing changed, those players are already on the bossbar with nobody to add or remove</td><td>Nothing changed. Those players are already on the bossbar with nobody to add or remove</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.set.name.unchanged</div></th><td>Nothing changed, that's already the name of this bossbar</td><td>Nothing changed. That's already the name of this bossbar</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.set.color.unchanged</div></th><td>Nothing changed, that's already the color of this bossbar</td><td>Nothing changed. That's already the color of this bossbar</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.set.style.unchanged</div></th><td>Nothing changed, that's already the style of this bossbar</td><td>Nothing changed. That's already the style of this bossbar</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.set.value.unchanged</div></th><td>Nothing changed, that's already the value of this bossbar</td><td>Nothing changed. That's already the value of this bossbar</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.set.max.unchanged</div></th><td>Nothing changed, that's already the max of this bossbar</td><td>Nothing changed. That's already the max of this bossbar</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.set.visibility.unchanged.hidden</div></th><td>Nothing changed, the bossbar is already hidden</td><td>Nothing changed. The bossbar is already hidden</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.set.visibility.unchanged.visible</div></th><td>Nothing changed, the bossbar is already visible</td><td>Nothing changed. The bossbar is already visible</td></tr>
<tr><th align="left"><div style="width:290px">commands.deop.failed</div></th><td>Nothing changed, the player is not an operator</td><td>Nothing changed. The player is not an operator</td></tr>
<tr><th align="left"><div style="width:290px">commands.enchant.failed</div></th><td>Nothing happened, targets either have no item in their hand or the enchantment could not be applied</td><td>Nothing changed. Targets either have no item in their hands or the enchantment could not be applied</td></tr>
<tr><th align="left"><div style="width:290px">commands.experience.set.points.invalid</div></th><td>Cannot set experience points above the maximum points for the players current level</td><td>Cannot set experience points above the maximum points for the player's current level</td></tr>
<tr><th align="left"><div style="width:290px">commands.op.failed</div></th><td>Nothing changed, the player is already an operator</td><td>Nothing changed. The player already is an operator</td></tr>
<tr><th align="left"><div style="width:290px">commands.pardon.failed</div></th><td>Nothing changed, the player isn't banned</td><td>Nothing changed. The player isn't banned</td></tr>
<tr><th align="left"><div style="width:290px">commands.pardonip.failed</div></th><td>Nothing changed, that ip isn't banned</td><td>Nothing changed. That IP isn't banned</td></tr>
<tr><th align="left"><div style="width:290px">commands.particle.failed</div></th><td>The particle was not visible for anybody.</td><td>The particle was not visible for anybody</td></tr>
<tr><th align="left"><div style="width:290px">commands.playsound.failed</div></th><td>The sound is too far away to be heard.</td><td>The sound is too far away to be heard</td></tr>
<tr><th align="left"><div style="width:290px">commands.recipe.give.failed</div></th><td>No new recipes were learnt</td><td>No new recipes were learned</td></tr>
<tr><th align="left"><div style="width:290px">commands.save.alreadyOff</div></th><td>Saving is already turned off.</td><td>Saving is already turned off</td></tr>
<tr><th align="left"><div style="width:290px">commands.save.alreadyOn</div></th><td>Saving is already turned on.</td><td>Saving is already turned on</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.objectives.display.alreadyEmpty</div></th><td>Nothing changed, that display slot is already empty</td><td>Nothing changed. That display slot is already empty</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.objectives.display.alreadySet</div></th><td>Nothing changed, that display slot is already showing that objective</td><td>Nothing changed. That display slot is already showing that objective</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.enable.failed</div></th><td>Nothing changed, that trigger is already enabled</td><td>Nothing changed. That trigger is already enabled</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.empty.unchanged</div></th><td>Nothing changed, that team is already empty</td><td>Nothing changed. That team is already empty</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.option.color.unchanged</div></th><td>Nothing changed, that team already has that color</td><td>Nothing changed. That team already has that color</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.option.friendlyfire.alreadyEnabled</div></th><td>Nothing changed, friendly fire is already enabled for that team</td><td>Nothing changed. Friendly fire is already enabled for that team</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.option.friendlyfire.alreadyDisabled</div></th><td>Nothing changed, friendly fire is already disabled for that team</td><td>Nothing changed. Friendly fire is already disabled for that team</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.option.seeFriendlyInvisibles.alreadyEnabled</div></th><td>Nothing changed, that team can already see invisible teammates</td><td>Nothing changed. That team can already see invisible teammates</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.option.seeFriendlyInvisibles.alreadyDisabled</div></th><td>Nothing changed, that team can already not see invisible teammates</td><td>Nothing changed. That team already can't see invisible teammates</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.option.nametagVisibility.unchanged</div></th><td>Nothing changed, nametag visibility is already that value</td><td>Nothing changed. Nametag visibility is already that value</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.option.deathMessageVisibility.unchanged</div></th><td>Nothing changed, death message visibility is already that value</td><td>Nothing changed. Death message visibility is already that value</td></tr>
<tr><th align="left"><div style="width:290px">commands.team.option.collisionRule.unchanged</div></th><td>Nothing changed, collision rule is already that value</td><td>Nothing changed. Collision rule is already that value</td></tr>
<tr><th align="left"><div style="width:290px">commands.worldborder.center.failed</div></th><td>Nothing changed, the world border is already centered there</td><td>Nothing changed. The world border is already centered there</td></tr>
<tr><th align="left"><div style="width:290px">commands.worldborder.set.failed.nochange</div></th><td>Nothing changed, the world border is already that size</td><td>Nothing changed. The world border is already that size</td></tr>
<tr><th align="left"><div style="width:290px">commands.worldborder.set.failed.small.</div></th><td>World border cannot be smaller than 1 blocks wide</td><td>World border cannot be smaller than 1 block wide</td></tr>
<tr><th align="left"><div style="width:290px">commands.worldborder.warning.time.failed</div></th><td>Nothing changed, the world border warning is already that amount of time</td><td>Nothing changed. The world border warning is already that amount of time</td></tr>
<tr><th align="left"><div style="width:290px">commands.worldborder.warning.distance.failed</div></th><td>Nothing changed, the world border warning is already that distance</td><td>Nothing changed. The world border warning is already that distance</td></tr>
<tr><th align="left"><div style="width:290px">commands.worldborder.damage.buffer.failed</div></th><td>Nothing changed, the world border damage buffer is already that distance</td><td>Nothing changed. The world border damage buffer is already that distance</td></tr>
<tr><th align="left"><div style="width:290px">commands.worldborder.damage.amount.failed</div></th><td>Nothing changed, the world border damage is already that amount</td><td>Nothing changed. The world border damage is already that amount</td></tr>
<tr><th align="left"><div style="width:290px">commands.data.merge.failed</div></th><td>Nothing changed!</td><td>Nothing changed, the specified properties already have these values</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.create.failed</div></th><td>A bossbar already exists with the id '%s'</td><td>A bossbar already exists with the ID '%s'</td></tr>
<tr><th align="left"><div style="width:290px">commands.bossbar.unknown</div></th><td>No bossbar exists with the id '%s'</td><td>No bossbar exists with the ID '%s'</td></tr>
<tr><th align="left"><div style="width:290px">commands.difficulty.failure</div></th><td>The difficulty did not change, it is already set to %s</td><td>The difficulty did not change; it is already set to %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.scoreboard.players.get.null</div></th><td>Can't get value of %s for %s, none is set</td><td>Can't get value of %s for %s; none is set</td></tr>
<tr><th align="left"><div style="width:290px">commands.data.get.invalid</div></th><td>Can't get %s, only numeric tags are allowed</td><td>Can't get %s; only numeric tags are allowed</td></tr>
<tr><th align="left"><div style="width:290px">commands.data.get.unknown</div></th><td>Can't get %s, tag doesn't exist</td><td>Can't get %s; tag doesn't exist</td></tr>
<tr><th align="left"><div style="width:290px">parsing.quote.escape</div></th><td>Invalid escape sequence '\%s' in quoted string)</td><td>Invalid escape sequence '\%s' in quoted string</td></tr>
<tr><th align="left"><div style="width:290px">parsing.bool.invalid</div></th><td>Invalid bool, expected true or false but found '%s'</td><td>Invalid boolean, expected 'true' or 'false' but found '%s'</td></tr>
<tr><th align="left"><div style="width:290px">parsing.bool.expected</div></th><td>Expected bool</td><td>Expected boolean</td></tr>
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
+ minecraft/advancements/recipes/building_blocks/packed_ice.json
+ minecraft/recipes/packed_ice.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/stripped_acacia_bark.json
+ minecraft/blockstates/stripped_birch_bark.json
+ minecraft/blockstates/stripped_dark_oak_bark.json
+ minecraft/blockstates/stripped_jungle_bark.json
+ minecraft/blockstates/stripped_oak_bark.json
+ minecraft/blockstates/stripped_spruce_bark.json
+ minecraft/models/block/stripped_acacia_bark.json
+ minecraft/models/block/stripped_birch_bark.json
+ minecraft/models/block/stripped_dark_oak_bark.json
+ minecraft/models/block/stripped_jungle_bark.json
+ minecraft/models/block/stripped_oak_bark.json
+ minecraft/models/block/stripped_spruce_bark.json
+ minecraft/models/item/stripped_acacia_bark.json
+ minecraft/models/item/stripped_birch_bark.json
+ minecraft/models/item/stripped_dark_oak_bark.json
+ minecraft/models/item/stripped_jungle_bark.json
+ minecraft/models/item/stripped_oak_bark.json
+ minecraft/models/item/stripped_spruce_bark.json
- minecraft/textures/blocks/acacia_bark_top.png
- minecraft/textures/blocks/birch_bark_top.png
- minecraft/textures/blocks/dark_oak_bark_top.png
- minecraft/textures/blocks/jungle_bark_top.png
- minecraft/textures/blocks/oak_bark_top.png
- minecraft/textures/blocks/spruce_bark_top.png
```

</details>
</details>
<hr/>