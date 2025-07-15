## Comparison with [18w30b](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w30b)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">18w30b</th><th>18w31a</th></tr><tr><td>it.unimi.dsi:fastutil</td><td><pre>7.1.0</pre></td><td><pre>8.2.1</pre></td></tr></table>
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
+ chunk.txt
```

</details>
<details>
<summary>
execute
</summary>

```diff
+ execute in <dimension>
- execute in overworld
- execute in the_end
- execute in the_nether
```

</details>
<details>
<summary>
worldborder
</summary>

```diff
+ worldborder add <distance: float> <time: integer>
- worldborder add <distance: integer> <time: integer>
+ worldborder set <distance: float> <time: integer>
- worldborder set <distance: integer> <time: integer>
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
+ argument.dimension.invalid: Unknown dimension '%s'
+ commands.chunk.forced: Marked chunk (%s, %s) as force loaded
+ commands.chunk.not.forced: Could not mark chunk (%s, %s) as force loaded, already so
+ commands.chunk.not.unforced: Could not mark chunk (%s, %s) as not force loaded, already so
+ commands.chunk.unforced: Marked chunk (%s, %s) as not force loaded
+ death.attack.even_more_magic: %1$s was killed by even more magic
+ death.attack.message_too_long: Actually, message was too long to deliver fully. Sorry! Here's stripped version: %s
+ menu.loadingForcedChunks: Loading forced chunks for dimension %s
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>18w30b</th><th>18w31a</th></tr>
<tr><th align="left"><div style="width:290px">multiplayer.message_not_delivered</div></th><td>Can't deliver chat message, check server logs</td><td>Can't deliver chat message starting with %s, check server logs</td></tr>
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
+ minecraft/tags/blocks/coral_plants.json
+ minecraft/tags/blocks/underwater_bonemeals.json
```

</details>
</details>
<hr/>