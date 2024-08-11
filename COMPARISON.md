## Comparison with [18w03b](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w03b)

- [Commands](#commands)
- [Translations](#translations)

<hr/>
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ bossbar.json
```

</details>













<details>
<summary>
execute
</summary>

```diff
+ execute store result bossbar <id: resource_location> max
+ execute store result bossbar <id: resource_location> value
+ execute store success bossbar <id: resource_location> max
+ execute store success bossbar <id: resource_location> value
```

</details>





























<details>
<summary>
setidletimeout
</summary>

```diff
+ setidletimeout <minutes: integer>
- setidletimeout <seconds: integer>
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ commands.bossbar.create.success: Created custom bossbar %s
+ commands.bossbar.get.max: Custom bossbar %s has a maximum of %s
+ commands.bossbar.get.players.none: Custom bossbar %s has no players currently online
+ commands.bossbar.get.players.some: Custom bossbar %s has %s players currently online: %s
+ commands.bossbar.get.value: Custom bossbar %s has a value of %s
+ commands.bossbar.get.visible.hidden: Custom bossbar %s is currently hidden
+ commands.bossbar.get.visible.visible: Custom bossbar %s is currently shown
+ commands.bossbar.list.bars.none: There are no custom bossbars active
+ commands.bossbar.list.bars.some: There are %s custom bossbars active: %s
+ commands.bossbar.remove.success: Removed custom bossbar %s
+ commands.bossbar.set.color.success: Custom bossbar %s has changed color
+ commands.bossbar.set.max.success: Custom bossbar %s has changed maximum to %s
+ commands.bossbar.set.name.success: Custom bossbar %s has been renamed
+ commands.bossbar.set.players.success.none: Custom bossbar %s no longer has any players
+ commands.bossbar.set.players.success.some: Custom bossbar %s now has %s players: %s
+ commands.bossbar.set.style.success: Custom bossbar %s has changed style
+ commands.bossbar.set.value.success: Custom bossbar %s has changed value to %s
+ commands.bossbar.set.visible.success.hidden: Custom bossbar %s is now hidden
+ commands.bossbar.set.visible.success.visible: Custom bossbar %s is now visible
+ commands.trigger.add.success: Triggered %s (added %s to value)
+ commands.trigger.set.success: Triggered %s (set value to %s)
+ commands.trigger.simple.success: Triggered %s
```

</details>
<details>
<summary>
Changes
</summary>

```
commands.setidletimeout.success: The player idle timeout is now %s secondminutes
```

</details>
</details>