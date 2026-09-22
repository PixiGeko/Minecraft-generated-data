## Comparison with [26.3](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.3)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.3</th><th>26.4-snapshot-1</th></tr><tr><td>DataPack version</td><td><pre>121.0</pre></td><td><pre>122.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>97.1</pre></td><td><pre>98.0</pre></td></tr><tr><td>World version</td><td><pre>5023</pre></td><td><pre>5119</pre></td></tr><tr><td>Protocol version</td><td><pre>777</pre></td><td><pre>1073742163</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
chunk_status
</summary>

```diff
+ minecraft:noise_biomes
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/chunk_status.json
</summary>

```diff
+ minecraft:noise_biomes
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
+ multiplayer.disconnect.rejected: Connection rejected by server
+ narration.tab_navigation.mac.usage: Press Command and Tab to switch between tabs
+ options.graphicsApi.vulkanNonExperimental: Prefer Vulkan
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.3</th><th>26.4-snapshot-1</th></tr>
<tr><th align="left"><div style="width:290px">narration.tab_navigation.usage</div></th><td>Press Ctrl and Tab to switch between tabs</td><td>Press Control and Tab to switch between tabs</td></tr>
<tr><th align="left"><div style="width:290px">options.accessibility.narrator_hotkey.mac.tooltip</div></th><td>Allows the Narrator to be toggled on and off with 'Cmd + B'.</td><td>Allows the Narrator to be toggled on and off with 'Command + B'.</td></tr>
<tr><th align="left"><div style="width:290px">options.accessibility.narrator_hotkey.tooltip</div></th><td>Allows the Narrator to be toggled on and off with 'Ctrl + B'.</td><td>Allows the Narrator to be toggled on and off with 'Control + B'.</td></tr>
<tr><th align="left"><div style="width:290px">options.quitShortcuts.tooltip</div></th><td>Whether keyboard shortcuts can close the game. When off, Alt + F4 on Windows and Linux, and Cmd + Q on macOS, will no longer quit the game.</td><td>Whether keyboard shortcuts can close the game. When off, Alt + F4 on Windows and Linux, and Command + Q on macOS, will no longer quit the game.</td></tr>
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
+ minecraft/tags/worldgen/biome/generated_in_below_zero_retrogen.json
+ minecraft/tags/worldgen/biome/is_cave.json
```

</details>
</details>
<hr/>