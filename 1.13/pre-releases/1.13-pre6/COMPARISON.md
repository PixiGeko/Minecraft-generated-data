## Comparison with [1.13-pre5](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre5)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
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
<table><tr><th></th><th align="left">1.13-pre5</th><th>1.13-pre6</th></tr><tr><td>com.mojang:datafixerupper</td><td><pre>1.0.3</pre></td><td><pre>1.0.12</pre></td></tr></table>
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
+ commands.replaceitem.entity.failed: Could not put %s in slot %s
+ connect.aborted: Aborted
+ debug.inspect.block: Copied block data to clipboard
+ debug.inspect.entity: Copied entity data to clipboard
+ debug.inspect.help: F3 + I = Copy entity or block data to clipboard
+ menu.preparingSpawn: Preparing spawn area
+ menu.savingChunks: Saving chunks
+ menu.working: Working...
+ multiplayer.message_not_delivered: Can't deliver chat message, check server logs
+ multiplayer.status.finished: Finished
+ multiplayer.status.quitting: Quitting
+ multiplayer.status.request_handled: Status requst has been handled
- options.forceUnicodeFont: Force Unicode Font
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.13-pre5</th><th>1.13-pre6</th></tr>
<tr><th align="left"><div style="width:290px">commands.replaceitem.slot.inapplicable</div></th><td>The target does not have the specified slot</td><td>The target does not have slot %s</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/font/ascii.png
```

</details>
</details>
<hr/>