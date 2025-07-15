## Comparison with [18w03b](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w03b)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Commands](#commands)
> - [Translations](#translations)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">18w03b</th><th>18w05a</th></tr><tr><td>com.mojang:brigadier</td><td><pre>0.1.20</pre></td><td><pre>0.1.23</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ bossbar.txt
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<br/>
<table>
<tr><th>Name</th><th>18w03b</th><th>18w05a</th></tr>
<tr><th align="left"><div style="width:290px">commands.setidletimeout.success</div></th><td>The player idle timeout is now %s seconds</td><td>The player idle timeout is now %s minutes</td></tr>
</table>
<br/>
</details>
</details>
<hr/>