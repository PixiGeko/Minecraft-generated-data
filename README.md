<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.13-pre8 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.13-pre8</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2018-07-13T11:45:00+00:00</td></tr>
<tr><th>SHA1</th><td>28369586c81d7db81d6aea81a6464d2bb1765da8</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/28369586c81d7db81d6aea81a6464d2bb1765da8/1.13-pre8.json">https://piston-meta.mojang.com/v1/packages/28369586c81d7db81d6aea81a6464d2bb1765da8/1.13-pre8.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/b04f82ae0f3018c4c22a153184b385012c4d0814/server.jar">https://piston-data.mojang.com/v1/objects/b04f82ae0f3018c4c22a153184b385012c4d0814/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/fbece4a24e47af57c3ee75e331f9390309f92ae5/client.jar">https://piston-data.mojang.com/v1/objects/fbece4a24e47af57c3ee75e331f9390309f92ae5/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre7">1.13-pre7</a>

# Folder structure

<details><summary>data/</summary>

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


<details><summary>assets/</summary>

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


# Commands

<details><summary>scoreboard.txt</summary>

```diff
+ scoreboard objectives add <objective: string> <criteria: objective_criteria> <displayName: component>
- scoreboard objectives add <objective: string> <criteria: objective_criteria> <displayName: string>
+ scoreboard objectives modify <objective: objective> displayname <displayName: component>
- scoreboard objectives modify <objective: objective> displayname <displayName: string>
+ scoreboard objectives modify <objective: objective> rendertype hearts
+ scoreboard objectives modify <objective: objective> rendertype integer
```

</details>


<details><summary>team.txt</summary>

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


# Tags

<details><summary>List</summary>

```diff
- blocks/coral_fans.json
- blocks/dead_coral_blocks.json
+ blocks/impermeable.json
- blocks/live_coral_blocks.json
+ blocks/wall_corals.json
- items/coral_blocks.json
- items/coral_fans.json
- items/corals.json
- items/dead_coral_blocks.json
- items/live_coral_blocks.json
```

</details>


<details><summary>blocks/corals.json</summary>

```diff
+ minecraft:brain_coral_fan
+ minecraft:bubble_coral_fan
+ minecraft:fire_coral_fan
+ minecraft:horn_coral_fan
+ minecraft:tube_coral_fan
```

</details>


<details><summary>blocks/coral_blocks.json</summary>

```diff
- #minecraft:dead_coral_blocks
- #minecraft:live_coral_blocks
+ minecraft:brain_coral_block
+ minecraft:bubble_coral_block
+ minecraft:fire_coral_block
+ minecraft:horn_coral_block
+ minecraft:tube_coral_block
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ block.minecraft.brain_coral_wall_fan
+ block.minecraft.bubble_coral_wall_fan
+ block.minecraft.dead_brain_coral_fan
+ block.minecraft.dead_brain_coral_wall_fan
+ block.minecraft.dead_bubble_coral_fan
+ block.minecraft.dead_bubble_coral_wall_fan
+ block.minecraft.dead_fire_coral_fan
+ block.minecraft.dead_fire_coral_wall_fan
+ block.minecraft.dead_horn_coral_fan
+ block.minecraft.dead_horn_coral_wall_fan
+ block.minecraft.dead_tube_coral_fan
+ block.minecraft.dead_tube_coral_wall_fan
+ block.minecraft.fire_coral_wall_fan
+ block.minecraft.horn_coral_wall_fan
+ block.minecraft.tube_coral_wall_fan
- commands.scoreboard.objectives.add.longDisplayName
+ commands.scoreboard.objectives.modify.rendertype
- commands.team.add.longDisplayName
+ commands.team.option.name.success
+ commands.team.option.name.unchanged
+ gui.ok
+ gui.proceed
+ options.forceUnicodeFont
+ selectWorld.backupQuestion.customized
+ selectWorld.backupWarning.customized
+ selectWorld.futureworld.error.text
+ selectWorld.futureworld.error.title
+ selectWorld.recreate.customized.text
+ selectWorld.recreate.customized.title
+ selectWorld.recreate.error.text
+ selectWorld.recreate.error.title
- selectWorld.unsupported.customized.text
- selectWorld.unsupported.customized.title
+ subtitles.entity.parrot.imitate.phantom
+ subtitles.entity.phantom.ambient
+ subtitles.entity.phantom.bite
+ subtitles.entity.phantom.death
+ subtitles.entity.phantom.flap
+ subtitles.entity.phantom.hurt
+ subtitles.entity.phantom.swoop
+ subtitles.entity.turtle.ambient_land
+ subtitles.entity.turtle.death
+ subtitles.entity.turtle.death_baby
+ subtitles.entity.turtle.egg_break
+ subtitles.entity.turtle.egg_crack
+ subtitles.entity.turtle.egg_hatch
+ subtitles.entity.turtle.hurt
+ subtitles.entity.turtle.hurt_baby
+ subtitles.entity.turtle.lay_egg
+ subtitles.entity.turtle.shamble
+ subtitles.entity.turtle.shamble_baby
+ subtitles.entity.turtle.swim
- subtitles.turtle.ambient_land
- subtitles.turtle.death
- subtitles.turtle.death_baby
- subtitles.turtle.egg_break
- subtitles.turtle.egg_crack
- subtitles.turtle.egg_hatch
- subtitles.turtle.hurt
- subtitles.turtle.hurt_baby
- subtitles.turtle.lay_egg
- subtitles.turtle.shamble
- subtitles.turtle.shamble_baby
- subtitles.turtle.swim
```

</details>


# Misc

<details><summary>tags.txt</summary>

```diff
- blocks/coral_fans.json
- blocks/dead_coral_blocks.json
+ blocks/impermeable.json
- blocks/live_coral_blocks.json
+ blocks/wall_corals.json
- items/coral_blocks.json
- items/coral_fans.json
- items/corals.json
- items/dead_coral_blocks.json
- items/live_coral_blocks.json
```

</details>


<details><summary>textures.txt</summary>

```diff
+ block/dead_brain_coral_fan.png
+ block/dead_bubble_coral_fan.png
+ block/dead_fire_coral_fan.png
+ block/dead_horn_coral_fan.png
+ block/dead_tube_coral_fan.png
```

</details>
