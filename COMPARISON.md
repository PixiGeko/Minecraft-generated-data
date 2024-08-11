## Comparison with [1.13-pre1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre1)

- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ packed_ice.json
```

</details>
</details>
<details><summary>Translations</summary>
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

```
selectWorld.backupWarning: This world was last played in version %s,; you are on snapshot %s. Please make a backup in case you experience world corruptions!
options.fullscreen.resolution: FS Rullscreen resolution
block.minecraft.bed.no_sleep: You can only sleep only at night and during thunderstorms
block.minecraft.bed.too_far_away: You may not rest now,; the bed is too far away
block.minecraft.bed.not_safe: You may not rest now,; there are monsters nearby
structure_block.size_failure: Unable to detect structure size, a. Add corners with matching structure names
advancements.adventure.sniper_duel.description: Kill a Skeleton from more thanat least 50 meters away
commands.scoreboard.objectives.list.empty: There are no tracked objectives
argument.entity.toomany: Only one entity is allowed, but the provided selector allows more than one.
argument.player.toomany: Only one player is allowed, but the provided selector allows more than one.
argument.player.entities: Only players may be affected by this command, but the provided selector includes entities.
arguments.nbtpath.node.invalid: Invalid nbtNBT path, expected element name or index
arguments.swizzle.invalid: Invalid swizzle, expected combination of 'x', 'y' and 'z'
argument.entity.invalid: Invalid name or uuidUUID
argument.entity.options.level.negative: Level shouldn't be negative
commands.banip.failed: Nothing changed, t. That IP is already banned
commands.ban.failed: Nothing changed, t. The player is already banned
commands.bossbar.set.players.unchanged: Nothing changed, t. Those players are already on the bossbar with nobody to add or remove
commands.bossbar.set.name.unchanged: Nothing changed, t. That's already the name of this bossbar
commands.bossbar.set.color.unchanged: Nothing changed, t. That's already the color of this bossbar
commands.bossbar.set.style.unchanged: Nothing changed, t. That's already the style of this bossbar
commands.bossbar.set.value.unchanged: Nothing changed, t. That's already the value of this bossbar
commands.bossbar.set.max.unchanged: Nothing changed, t. That's already the max of this bossbar
commands.bossbar.set.visibility.unchanged.hidden: Nothing changed, t. The bossbar is already hidden
commands.bossbar.set.visibility.unchanged.visible: Nothing changed, t. The bossbar is already visible
commands.deop.failed: Nothing changed, t. The player is not an operator
commands.enchant.failed: Nothing chappened, tnged. Targets either have no item in their hands or the enchantment could not be applied
commands.experience.set.points.invalid: Cannot set experience points above the maximum points for the player's current level
commands.op.failed: Nothing changed, t. The player is already is an operator
commands.pardon.failed: Nothing changed, t. The player isn't banned
commands.pardonip.failed: Nothing changed, t. That ipIP isn't banned
commands.particle.failed: The particle was not visible for anybody.
commands.playsound.failed: The sound is too far away to be heard.
commands.recipe.give.failed: No new recipes were learnted
commands.save.alreadyOff: Saving is already turned off.
commands.save.alreadyOn: Saving is already turned on.
commands.scoreboard.objectives.display.alreadyEmpty: Nothing changed, t. That display slot is already empty
commands.scoreboard.objectives.display.alreadySet: Nothing changed, t. That display slot is already showing that objective
commands.scoreboard.players.enable.failed: Nothing changed, t. That trigger is already enabled
commands.team.empty.unchanged: Nothing changed, t. That team is already empty
commands.team.option.color.unchanged: Nothing changed, t. That team already has that color
commands.team.option.friendlyfire.alreadyEnabled: Nothing changed, f. Friendly fire is already enabled for that team
commands.team.option.friendlyfire.alreadyDisabled: Nothing changed, f. Friendly fire is already disabled for that team
commands.team.option.seeFriendlyInvisibles.alreadyEnabled: Nothing changed, t. That team can already see invisible teammates
commands.team.option.seeFriendlyInvisibles.alreadyDisabled: Nothing changed, t. That team can already nocan't see invisible teammates
commands.team.option.nametagVisibility.unchanged: Nothing changed, n. Nametag visibility is already that value
commands.team.option.deathMessageVisibility.unchanged: Nothing changed, d. Death message visibility is already that value
commands.team.option.collisionRule.unchanged: Nothing changed, c. Collision rule is already that value
commands.worldborder.center.failed: Nothing changed, t. The world border is already centered there
commands.worldborder.set.failed.nochange: Nothing changed, t. The world border is already that size
commands.worldborder.set.failed.small.: World border cannot be smaller than 1 blocks wide
commands.worldborder.warning.time.failed: Nothing changed, t. The world border warning is already that amount of time
commands.worldborder.warning.distance.failed: Nothing changed, t. The world border warning is already that distance
commands.worldborder.damage.buffer.failed: Nothing changed, t. The world border damage buffer is already that distance
commands.worldborder.damage.amount.failed: Nothing changed, t. The world border damage is already that amount
commands.data.merge.failed: Nothing changed!, the specified properties already have these values
commands.bossbar.create.failed: A bossbar already exists with the idID '%s'
commands.bossbar.unknown: No bossbar exists with the idID '%s'
commands.difficulty.failure: The difficulty did not change,; it is already set to %s
commands.scoreboard.players.get.null: Can't get value of %s for %s,; none is set
commands.data.get.invalid: Can't get %s,; only numeric tags are allowed
commands.data.get.unknown: Can't get %s,; tag doesn't exist
parsing.quote.escape: Invalid escape sequence '\%s' in quoted string)
parsing.bool.invalid: Invalid boolean, expected 'true' or 'false' but found '%s'
parsing.bool.expected: Expected boolean
```

</details>
</details>
<details><summary>File structure</summary>
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