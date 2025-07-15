## Comparison with [1.13-pre7](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre7)

> [!TIP]
> - [Blocks](#blocks)
> - [Commands](#commands)
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
+ brain_coral_wall_fan.json
+ bubble_coral_wall_fan.json
+ dead_brain_coral_fan.json
+ dead_brain_coral_wall_fan.json
+ dead_bubble_coral_fan.json
+ dead_bubble_coral_wall_fan.json
+ dead_fire_coral_fan.json
+ dead_fire_coral_wall_fan.json
+ dead_horn_coral_fan.json
+ dead_horn_coral_wall_fan.json
+ dead_tube_coral_fan.json
+ dead_tube_coral_wall_fan.json
+ fire_coral_wall_fan.json
+ horn_coral_wall_fan.json
+ tube_coral_wall_fan.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
scoreboard
</summary>

```diff
+ scoreboard objectives add <objective: string> <criteria: objective_criteria> <displayName: component>
- scoreboard objectives add <objective: string> <criteria: objective_criteria> <displayName: string>
+ scoreboard objectives modify <objective: objective> displayname <displayName: component>
- scoreboard objectives modify <objective: objective> displayname <displayName: string>
+ scoreboard objectives modify <objective: objective> rendertype hearts
+ scoreboard objectives modify <objective: objective> rendertype integer
```

</details>
<details>
<summary>
team
</summary>

```diff
+ team add <team: string> <displayName: component>
- team add <team: string> <displayName: string>
+ team modify <team: team> collisionRule always
+ team modify <team: team> collisionRule never
+ team modify <team: team> collisionRule pushOtherTeams
+ team modify <team: team> collisionRule pushOwnTeam
+ team modify <team: team> color <value: color>
+ team modify <team: team> deathMessageVisibility always
+ team modify <team: team> deathMessageVisibility hideForOtherTeams
+ team modify <team: team> deathMessageVisibility hideForOwnTeam
+ team modify <team: team> deathMessageVisibility never
+ team modify <team: team> displayName <displayName: component>
+ team modify <team: team> friendlyfire <allowed: bool>
+ team modify <team: team> nametagVisibility always
+ team modify <team: team> nametagVisibility hideForOtherTeams
+ team modify <team: team> nametagVisibility hideForOwnTeam
+ team modify <team: team> nametagVisibility never
+ team modify <team: team> prefix <prefix: component>
+ team modify <team: team> seeFriendlyInvisibles <allowed: bool>
+ team modify <team: team> suffix <suffix: component>
- team option <team: team> collisionRule always
- team option <team: team> collisionRule never
- team option <team: team> collisionRule pushOtherTeams
- team option <team: team> collisionRule pushOwnTeam
- team option <team: team> color <value: color>
- team option <team: team> deathMessageVisibility always
- team option <team: team> deathMessageVisibility hideForOtherTeams
- team option <team: team> deathMessageVisibility hideForOwnTeam
- team option <team: team> deathMessageVisibility never
- team option <team: team> friendlyfire <allowed: bool>
- team option <team: team> nametagVisibility always
- team option <team: team> nametagVisibility hideForOtherTeams
- team option <team: team> nametagVisibility hideForOwnTeam
- team option <team: team> nametagVisibility never
- team option <team: team> prefix <prefix: component>
- team option <team: team> seeFriendlyInvisibles <allowed: bool>
- team option <team: team> suffix <suffix: component>
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
+ block.minecraft.brain_coral_wall_fan: Brain Coral Wall Fan
+ block.minecraft.bubble_coral_wall_fan: Bubble Coral Wall Fan
+ block.minecraft.dead_brain_coral_fan: Dead Brain Coral Fan
+ block.minecraft.dead_brain_coral_wall_fan: Dead Brain Coral Wall Fan
+ block.minecraft.dead_bubble_coral_fan: Dead Bubble Coral Fan
+ block.minecraft.dead_bubble_coral_wall_fan: Dead Bubble Coral Wall Fan
+ block.minecraft.dead_fire_coral_fan: Dead Fire Coral Fan
+ block.minecraft.dead_fire_coral_wall_fan: Dead Fire Coral Wall Fan
+ block.minecraft.dead_horn_coral_fan: Dead Horn Coral Fan
+ block.minecraft.dead_horn_coral_wall_fan: Dead Horn Coral Wall Fan
+ block.minecraft.dead_tube_coral_fan: Dead Tube Coral Fan
+ block.minecraft.dead_tube_coral_wall_fan: Dead Tube Coral Wall Fan
+ block.minecraft.fire_coral_wall_fan: Fire Coral Wall Fan
+ block.minecraft.horn_coral_wall_fan: Horn Coral Wall Fan
+ block.minecraft.tube_coral_wall_fan: Tube Coral Wall Fan
- commands.scoreboard.objectives.add.longDisplayName: Objective display names cannot be longer than %s characters
+ commands.scoreboard.objectives.modify.rendertype: Changed objective %s render type
- commands.team.add.longDisplayName: Team display names cannot be longer than %s characters
+ commands.team.option.name.success: Updated team %s name
+ commands.team.option.name.unchanged: Nothing changed. That team already has that name
+ gui.ok: Ok
+ gui.proceed: Proceed
+ options.forceUnicodeFont: Force Unicode Font
+ selectWorld.backupQuestion.customized: Customized worlds are no longer supported
+ selectWorld.backupWarning.customized: Unfortunately, we do not support customized worlds in this version of Minecraft. We can still load this world and keep everything the way it was, but any newly generated terrain will no longer be customized. We're sorry for the inconvenience!
+ selectWorld.futureworld.error.text: Something went wrong while trying to load a world from a future version. This was a risky operation to begin with, sorry it didn't work.
+ selectWorld.futureworld.error.title: An error occured!
+ selectWorld.recreate.customized.text: Customized worlds are no longer supported in this version of Minecraft. We can try to recreate it with the same seed and properties, but any terrain customizations will be lost. We're sorry for the inconvenience!
+ selectWorld.recreate.customized.title: Customized worlds are no longer supported
+ selectWorld.recreate.error.text: Something went wrong while trying to recreate a world.
+ selectWorld.recreate.error.title: An error occured!
- selectWorld.unsupported.customized.text: Unfortunately, we cannot support Customized Worlds in this version of Minecraft. Please downgrade to %s to play this world. We are sorry for the inconvenience.
- selectWorld.unsupported.customized.title: Unsupported world!
+ subtitles.entity.parrot.imitate.phantom: Parrot screeches
+ subtitles.entity.phantom.ambient: Phantom screeches
+ subtitles.entity.phantom.bite: Phantom bites
+ subtitles.entity.phantom.death: Phantom dies
+ subtitles.entity.phantom.flap: Phantom flaps
+ subtitles.entity.phantom.hurt: Phantom hurts
+ subtitles.entity.phantom.swoop: Phantom swoops
+ subtitles.entity.turtle.ambient_land: Turtle chirps
+ subtitles.entity.turtle.death_baby: Turtle baby dies
+ subtitles.entity.turtle.death: Turtle dies
+ subtitles.entity.turtle.egg_break: Turtle egg breaks
+ subtitles.entity.turtle.egg_crack: Turtle egg cracks
+ subtitles.entity.turtle.egg_hatch: Turtle egg hatches
+ subtitles.entity.turtle.hurt_baby: Turtle baby hurts
+ subtitles.entity.turtle.hurt: Turtle hurts
+ subtitles.entity.turtle.lay_egg: Turtle lays egg
+ subtitles.entity.turtle.shamble_baby: Turtle baby shambles
+ subtitles.entity.turtle.shamble: Turtle shambles
+ subtitles.entity.turtle.swim: Turtle swims
- subtitles.turtle.ambient_land: Turtle chirps
- subtitles.turtle.death_baby: Turtle baby dies
- subtitles.turtle.death: Turtle dies
- subtitles.turtle.egg_break: Turtle egg breaks
- subtitles.turtle.egg_crack: Turtle egg cracks
- subtitles.turtle.egg_hatch: Turtle egg hatches
- subtitles.turtle.hurt_baby: Turtle baby hurts
- subtitles.turtle.hurt: Turtle hurts
- subtitles.turtle.lay_egg: Turtle lays egg
- subtitles.turtle.shamble_baby: Turtle baby shambles
- subtitles.turtle.shamble: Turtle shambles
- subtitles.turtle.swim: Turtle swims
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.13-pre7</th><th>1.13-pre8</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.deleteWarning</div></th><td>will be lost forever! (A long time!)</td><td>'%s' will be lost forever! (A long time!)</td></tr>
<tr><th align="left"><div style="width:290px">selectServer.deleteWarning</div></th><td>will be lost forever! (A long time!)</td><td>'%s' will be lost forever! (A long time!)</td></tr>
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
- minecraft/tags/blocks/coral_fans.json
- minecraft/tags/blocks/dead_coral_blocks.json
+ minecraft/tags/blocks/impermeable.json
- minecraft/tags/blocks/live_coral_blocks.json
+ minecraft/tags/blocks/wall_corals.json
- minecraft/tags/items/coral_blocks.json
- minecraft/tags/items/coral_fans.json
- minecraft/tags/items/corals.json
- minecraft/tags/items/dead_coral_blocks.json
- minecraft/tags/items/live_coral_blocks.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/brain_coral_wall_fan.json
+ minecraft/blockstates/bubble_coral_wall_fan.json
+ minecraft/blockstates/dead_brain_coral_fan.json
+ minecraft/blockstates/dead_brain_coral_wall_fan.json
+ minecraft/blockstates/dead_bubble_coral_fan.json
+ minecraft/blockstates/dead_bubble_coral_wall_fan.json
+ minecraft/blockstates/dead_fire_coral_fan.json
+ minecraft/blockstates/dead_fire_coral_wall_fan.json
+ minecraft/blockstates/dead_horn_coral_fan.json
+ minecraft/blockstates/dead_horn_coral_wall_fan.json
+ minecraft/blockstates/dead_tube_coral_fan.json
+ minecraft/blockstates/dead_tube_coral_wall_fan.json
+ minecraft/blockstates/fire_coral_wall_fan.json
+ minecraft/blockstates/horn_coral_wall_fan.json
+ minecraft/blockstates/tube_coral_wall_fan.json
+ minecraft/models/block/brain_coral_wall_fan.json
+ minecraft/models/block/bubble_coral_wall_fan.json
+ minecraft/models/block/coral_wall_fan.json
+ minecraft/models/block/dead_brain_coral_fan.json
+ minecraft/models/block/dead_brain_coral_wall_fan.json
+ minecraft/models/block/dead_bubble_coral_fan.json
+ minecraft/models/block/dead_bubble_coral_wall_fan.json
+ minecraft/models/block/dead_fire_coral_fan.json
+ minecraft/models/block/dead_fire_coral_wall_fan.json
+ minecraft/models/block/dead_horn_coral_fan.json
+ minecraft/models/block/dead_horn_coral_wall_fan.json
+ minecraft/models/block/dead_tube_coral_fan.json
+ minecraft/models/block/dead_tube_coral_wall_fan.json
+ minecraft/models/block/fire_coral_wall_fan.json
+ minecraft/models/block/horn_coral_wall_fan.json
+ minecraft/models/block/tube_coral_wall_fan.json
+ minecraft/models/item/brain_coral_wall_fan.json
+ minecraft/models/item/bubble_coral_wall_fan.json
+ minecraft/models/item/dead_brain_coral_fan.json
+ minecraft/models/item/dead_brain_coral_wall_fan.json
+ minecraft/models/item/dead_bubble_coral_fan.json
+ minecraft/models/item/dead_bubble_coral_wall_fan.json
+ minecraft/models/item/dead_fire_coral_fan.json
+ minecraft/models/item/dead_fire_coral_wall_fan.json
+ minecraft/models/item/dead_horn_coral_fan.json
+ minecraft/models/item/dead_horn_coral_wall_fan.json
+ minecraft/models/item/dead_tube_coral_fan.json
+ minecraft/models/item/dead_tube_coral_wall_fan.json
+ minecraft/models/item/fire_coral_wall_fan.json
+ minecraft/models/item/horn_coral_wall_fan.json
+ minecraft/models/item/tube_coral_wall_fan.json
+ minecraft/textures/block/dead_brain_coral_fan.png
+ minecraft/textures/block/dead_bubble_coral_fan.png
+ minecraft/textures/block/dead_fire_coral_fan.png
+ minecraft/textures/block/dead_horn_coral_fan.png
+ minecraft/textures/block/dead_tube_coral_fan.png
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
+ Truly gone fishing!
```

</details>
</details>
<hr/>