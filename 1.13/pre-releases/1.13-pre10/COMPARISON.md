## Comparison with [1.13-pre9](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre9)

> [!TIP]
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
team
</summary>

```diff
- team modify <team: team> friendlyfire <allowed: bool>
+ team modify <team: team> friendlyFire <allowed: bool>
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
+ optimizeWorld.confirm.description: This will attempt to optimize your world by making sure all data is stored in the most recent game format. This can take a very long time, depending on your world. Once done, your world may play faster but will no longer be compatible with older versions of the game. Are you sure you wish to proceed?
+ optimizeWorld.confirm.title: Optimize world
+ optimizeWorld.stage.upgrading: Upgrading all chunks...
+ optimizeWorld.title: Optimizing World '%s'
+ selectWorld.edit.optimize: Optimize World
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.13-pre9</th><th>1.13-pre10</th></tr>
<tr><th align="left"><div style="width:290px">options.fullscreen.resolution</div></th><td>Fullscreen resolution</td><td>Fullscreen Resolution</td></tr>
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
+ minecraft/tags/blocks/trapdoors.json
+ minecraft/tags/blocks/wooden_trapdoors.json
+ minecraft/tags/items/trapdoors.json
+ minecraft/tags/items/wooden_trapdoors.json
```

</details>
</details>
<hr/>