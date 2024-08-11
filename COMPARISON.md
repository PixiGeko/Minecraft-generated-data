## Comparison with [1.13-pre9](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre9)

- [Commands](#commands)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Commands</summary>
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
<details><summary>Translations</summary>
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

```
options.fullscreen.resolution: Fullscreen rResolution
```

</details>
</details>
<details><summary>File structure</summary>
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