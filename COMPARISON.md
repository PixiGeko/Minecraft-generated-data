## Comparison with [18w30b](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w30b)

- [Commands](#commands)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ chunk.json
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
<details><summary>Translations</summary>
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

```
multiplayer.message_not_delivered: Can't deliver chat message starting with %s, check server logs
```

</details>
</details>
<details><summary>File structure</summary>
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