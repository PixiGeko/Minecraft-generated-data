## Comparison with [18w22a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w22a)

- [Translations](#translations)

<hr/>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ advancement.advancementNotFound: Unknown advancement: %s
+ argument.anchor.invalid: Invalid entity anchor position %s
+ argument.block.id.invalid: Unknown block type '%s'
+ argument.block.property.duplicate: Property '%s' can only be set once for block %s
+ argument.block.property.invalid: Block %s does not accept '%s' for %s property
+ argument.block.property.novalue: Expected value for property '%s' on block %s
+ argument.block.property.unclosed: Expected closing ] for block state properties
+ argument.block.property.unknown: Block %s does not have property '%s'
+ argument.block.tag.disallowed: Tags aren't allowed here, only actual blocks
+ argument.color.invalid: Unknown color '%s'
+ argument.component.invalid: Invalid chat component: %s
+ argument.criteria.invalid: Unknown criteria '%s'
+ argument.double.big: Double must not be more than %s, found %s
+ argument.double.low: Double must not be less than %s, found %s
+ argument.entity.invalid: Invalid name or uuid
+ argument.entity.notfound.entity: No entity was found
+ argument.entity.notfound.player: No player was found
+ argument.entity.options.distance.negative: Distance cannot be negative
+ argument.entity.options.inapplicable: Option '%s' isn't applicable here
+ argument.entity.options.level.negative: Level negative
+ argument.entity.options.limit.toosmall: Limit must be at least 1
+ argument.entity.options.mode.invalid: Invalid or unknown game mode '%s'
+ argument.entity.options.sort.irreversible: Invalid or unknown sort type '%s'
+ argument.entity.options.type.invalid: Invalid or unknown entity type '%s'
+ argument.entity.options.unknown: Unknown option '%s'
+ argument.entity.options.unterminated: Expected end of options
+ argument.entity.options.valueless: Expected value for option '%s'
+ argument.entity.selector.missing: Missing selector type
+ argument.entity.selector.unknown: Unknown selector type '%s'
+ argument.entity.toomany: Only one entity is allowed, but the provided selector allows more than one.
+ argument.float.big: Float must not be more than %s, found %s
+ argument.float.low: Float must not be less than %s, found %s
+ argument.id.invalid: Invalid ID
+ argument.id.unknown: Unknown ID: %s
+ argument.integer.big: Integer must not be more than %s, found %s
+ argument.integer.low: Integer must not be less than %s, found %s
+ argument.item.id.invalid: Unknown item '%s'
+ argument.item.tag.disallowed: Tags aren't allowed here, only actual items
+ argument.literal.incorrect: Expected literal %s
+ argument.nbt.array.invalid: Invalid array type '%s'
+ argument.nbt.array.mixed: Can't insert %s into %s
+ argument.nbt.expected.key: Expected key
+ argument.nbt.expected.value: Expected value
+ argument.nbt.invalid: Invalid NBT: %s
+ argument.nbt.list.mixed: Can't insert %s into list of %s
+ argument.nbt.trailing: Unexpected trailing data
+ argument.player.entities: Only players may be affected by this command, but the provided selector includes entities.
+ argument.player.toomany: Only one player is allowed, but the provided selector allows more than one.
+ argument.player.unknown: That player does not exist
+ argument.pos.incomplete: Incomplete (expected 3 coordinates)
+ argument.pos.missing.double: Expected a coordinate
+ argument.pos.missing.int: Expected a block position
+ argument.pos.mixed: Cannot mix world & local coordinates (everything must either use ^ or not)
+ argument.pos.outofworld: That position is out of this world!
+ argument.pos.unloaded: That position is not loaded
+ argument.range.empty: Expected value or range of values
+ argument.range.ints: Only whole numbers allowed, not decimals
+ argument.range.swapped: Min cannot be bigger than max
+ argument.rotation.incomplete: Incomplete (expected 2 coordinates)
+ argument.scoreboardDisplaySlot.invalid: Unknown display slot '%s'
+ argument.scoreHolder.empty: No relevant score holders could be found
+ argument.vec2.incomplete: Incomplete (expected 2 coordinates)
+ arguments.block.tag.unknown: Unknown block tag '%s'
+ arguments.function.tag.unknown: Unknown function tag '%s'
+ arguments.function.unknown: Unknown function %s
+ arguments.item.overstacked: %s can only stack up to %s
+ arguments.item.tag.unknown: Unknown item tag '%s'
+ arguments.nbtpath.child.invalid: Can't access child '%s', either doesn't exist or parent isn't a compound
+ arguments.nbtpath.element.invalid: Can't access element %s, either doesn't exist or parent isn't a list
+ arguments.nbtpath.node.invalid: Invalid nbt path, expected element name or index
+ arguments.objective.notFound: Unknown scoreboard objective '%s'
+ arguments.objective.readonly: Scoreboard objective '%s' is read-only
+ arguments.operation.div0: Cannot divide by zero
+ arguments.operation.invalid: Invalid operation
+ arguments.swizzle.invalid: Invalid swizzle, expected combination of 'x' 'y' and 'z'
+ clear.failed.multiple: No items were found on %s players
+ clear.failed.single: No items were found on player %s
+ command.context.here: <--[HERE]
+ command.exception: Could not parse command: %s
+ command.expected.separator: Expected whitespace to end one argument, but found trailing data
+ command.unknown.argument: Incorrect argument for command
+ command.unknown.command: Unknown command
+ commands.ban.failed: Nothing changed, the player is already banned
+ commands.banip.failed: Nothing changed, that IP is already banned
+ commands.banip.invalid: Invalid IP address or unknown player
+ commands.bossbar.create.failed: A bossbar already exists with the id '%s'
+ commands.bossbar.set.color.unchanged: Nothing changed, that's already the color of this bossbar
+ commands.bossbar.set.max.unchanged: Nothing changed, that's already the max of this bossbar
+ commands.bossbar.set.name.unchanged: Nothing changed, that's already the name of this bossbar
+ commands.bossbar.set.players.unchanged: Nothing changed, those players are already on the bossbar with nobody to add or remove
+ commands.bossbar.set.style.unchanged: Nothing changed, that's already the style of this bossbar
+ commands.bossbar.set.value.unchanged: Nothing changed, that's already the value of this bossbar
+ commands.bossbar.set.visibility.unchanged.hidden: Nothing changed, the bossbar is already hidden
+ commands.bossbar.set.visibility.unchanged.visible: Nothing changed, the bossbar is already visible
+ commands.bossbar.unknown: No bossbar exists with the id '%s'
+ commands.clone.failed: No blocks were cloned
+ commands.clone.overlap: The source and destination areas cannot overlap
+ commands.clone.toobig: Too many blocks in the specified area (maximum %s, specified %s)
+ commands.data.block.invalid: The target block is not a block entity
+ commands.data.entity.invalid: Unable to modify player data
+ commands.data.get.invalid: Can't get %s, only numeric tags are allowed
+ commands.data.get.unknown: Can't get %s, tag doesn't exist
+ commands.data.merge.failed: Nothing changed!
+ commands.datapack.disable.failed: Pack '%s' is not enabled!
+ commands.datapack.enable.failed: Pack '%s' is already enabled!
+ commands.datapack.unknown: Unknown data pack '%s'
+ commands.debug.alreadyRunning: The debug profiler is already started
+ commands.debug.notRunning: The debug profiler hasn't started
+ commands.deop.failed: Nothing changed, the player is not an operator
+ commands.difficulty.failure: The difficulty did not change, it is already set to %s
+ commands.effect.clear.everything.failed: Target has no effects to remove
+ commands.effect.clear.specific.failed: Target doesn't have the requested effect
+ commands.effect.give.failed: Unable to apply this effect (target is either immune to effects, or has something stronger)
+ commands.enchant.failed: Nothing happened, targets either have no item in their hand or the enchantment could not be applied
+ commands.enchant.failed.entity: %s is not a valid entity for this command
+ commands.enchant.failed.incompatible: %s cannot support that enchantment
+ commands.enchant.failed.itemless: %s is not holding any item
+ commands.enchant.failed.level: %s is higher than the maximum level of %s supported by that enchantment
+ commands.execute.blocks.toobig: Too many blocks in the specified area (maximum %s, specified %s)
+ commands.experience.set.points.invalid: Cannot set experience points above the maximum points for the players current level
+ commands.fill.failed: No blocks were filled
+ commands.fill.toobig: Too many blocks in the specified area (maximum %s, specified %s)
+ commands.help.failed: Unknown command or insufficient permissions
+ commands.locate.failed: Could not find that structure nearby
+ commands.op.failed: Nothing changed, the player is already an operator
+ commands.pardon.failed: Nothing changed, the player isn't banned
+ commands.pardonip.failed: Nothing changed, that ip isn't banned
+ commands.pardonip.invalid: Invalid IP address
+ commands.particle.failed: The particle was not visible for anybody.
+ commands.playsound.failed: The sound is too far away to be heard.
+ commands.publish.alreadyPublished: Multiplayer game is already hosted on port %s
+ commands.recipe.give.failed: No new recipes were learnt
+ commands.recipe.take.failed: No recipes could be forgotten
+ commands.replaceitem.block.failed: The target block is not a container
+ commands.replaceitem.slot.inapplicable: The target does not have the specified slot
+ commands.save.alreadyOff: Saving is already turned off.
+ commands.save.alreadyOn: Saving is already turned on.
+ commands.save.failed: Unable to save the game (is there enough disk space?)
+ commands.scoreboard.objectives.add.duplicate: An objective already exists by that name
+ commands.scoreboard.objectives.add.longDisplayName: Objective display names cannot be longer than %s characters
+ commands.scoreboard.objectives.add.longName: Objective names cannot be longer than %s characters
+ commands.scoreboard.objectives.display.alreadyEmpty: Nothing changed, that display slot is already empty
+ commands.scoreboard.objectives.display.alreadySet: Nothing changed, that display slot is already showing that objective
+ commands.scoreboard.players.enable.failed: Nothing changed, that trigger is already enabled
+ commands.scoreboard.players.enable.invalid: Enable only works on trigger-objectives
+ commands.scoreboard.players.get.null: Can't get value of %s for %s, none is set
+ commands.setblock.failed: Could not set the block
+ commands.spreadplayers.failed.entities: Could not spread %s entities around %s, %s (too many entities for space - try using spread of at most %s)
+ commands.spreadplayers.failed.teams: Could not spread %s teams around %s, %s (too many entities for space - try using spread of at most %s)
+ commands.summon.failed: Unable to summon entity
+ commands.tag.add.failed: Target either already has the tag or has too many tags
+ commands.tag.remove.failed: Target does not have this tag
+ commands.team.add.duplicate: A team already exists by that name
+ commands.team.add.longDisplayName: Team display names cannot be longer than %s characters
+ commands.team.add.longName: Team names cannot be longer than %s characters
+ commands.team.empty.unchanged: Nothing changed, that team is already empty
+ commands.team.option.collisionRule.unchanged: Nothing changed, collision rule is already that value
+ commands.team.option.color.unchanged: Nothing changed, that team already has that color
+ commands.team.option.deathMessageVisibility.unchanged: Nothing changed, death message visibility is already that value
+ commands.team.option.friendlyfire.alreadyDisabled: Nothing changed, friendly fire is already disabled for that team
+ commands.team.option.friendlyfire.alreadyEnabled: Nothing changed, friendly fire is already enabled for that team
+ commands.team.option.nametagVisibility.unchanged: Nothing changed, nametag visibility is already that value
+ commands.team.option.seeFriendlyInvisibles.alreadyDisabled: Nothing changed, that team can already not see invisible teammates
+ commands.team.option.seeFriendlyInvisibles.alreadyEnabled: Nothing changed, that team can already see invisible teammates
+ commands.trigger.failed.invalid: You can only trigger objectives that are 'trigger' type
+ commands.trigger.failed.unprimed: You cannot trigger this objective yet
+ commands.whitelist.add.failed: Player is already whitelisted
+ commands.whitelist.alreadyOff: Whitelist is already turned off
+ commands.whitelist.alreadyOn: Whitelist is already turned on
+ commands.whitelist.remove.failed: Player is not whitelisted
+ commands.worldborder.center.failed: Nothing changed, the world border is already centered there
+ commands.worldborder.damage.amount.failed: Nothing changed, the world border damage is already that amount
+ commands.worldborder.damage.buffer.failed: Nothing changed, the world border damage buffer is already that distance
+ commands.worldborder.set.failed.big.: World border cannot be bigger than 60,000,000 blocks wide
+ commands.worldborder.set.failed.nochange: Nothing changed, the world border is already that size
+ commands.worldborder.set.failed.small.: World border cannot be smaller than 1 blocks wide
+ commands.worldborder.warning.distance.failed: Nothing changed, the world border warning is already that distance
+ commands.worldborder.warning.time.failed: Nothing changed, the world border warning is already that amount of time
+ effect.effectNotFound: Unknown effect: %s
+ enchantment.unknown: Unknown enchantment: %s
+ entity.notFound: Unknown entity: %s
+ parsing.bool.expected: Expected bool
+ parsing.bool.invalid: Invalid bool, expected true or false but found '%s'
+ parsing.double.expected: Expected double
+ parsing.double.invalid: Invalid double '%s'
+ parsing.expected: Expected '%s'
+ parsing.float.expected: Expected float
+ parsing.float.invalid: Invalid float '%s'
+ parsing.int.expected: Expected integer
+ parsing.int.invalid: Invalid integer '%s'
+ parsing.quote.escape: Invalid escape sequence '\%s' in quoted string)
+ parsing.quote.expected.end: Unclosed quoted string
+ parsing.quote.expected.start: Expected quote to start a string
+ particle.notFound: Unknown particle: %s
+ permissions.requires.entity: An entity is required to run this command here
+ permissions.requires.player: A player is required to run this command here
+ recipe.notFound: Unknown recipe: %s
+ slot.unknown: Unknown slot '%s'
+ team.notFound: Unknown team '%s'
```

</details>
</details>