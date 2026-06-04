## Comparison with [26.2-pre-3](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.2-pre-3)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.2-pre-3</th><th>26.2-pre-4</th></tr><tr><td>DataPack version</td><td><pre>107.0</pre></td><td><pre>107.1</pre></td></tr><tr><td>World version</td><td><pre>4896</pre></td><td><pre>4897</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742141</pre></td><td><pre>1073742142</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.2-pre-3</th><th>26.2-pre-4</th></tr><tr><td>com.mojang:authlib</td><td><pre>8.0.73</pre></td><td><pre>9.0.75</pre></td></tr></table>
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
+ gui.friends.error.unauthorized: Invalid token supplied, restart your game and launcher and try again
+ menu.multiplayerOptions.lan: LAN
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.2-pre-3</th><th>26.2-pre-4</th></tr>
<tr><th align="left"><div style="width:290px">gui.friends.presence.status.playing_hosted_server</div></th><td>Online (World)</td><td>Online (LAN)</td></tr>
<tr><th align="left"><div style="width:290px">menu.multiplayerOptions.button</div></th><td>Multiplayer...</td><td>Open to LAN</td></tr>
<tr><th align="left"><div style="width:290px">menu.multiplayerOptions.otherPlayers.header</div></th><td>Other Players</td><td>Settings for Other Players</td></tr>
<tr><th align="left"><div style="width:290px">menu.multiplayerOptions.title</div></th><td>Multiplayer Options</td><td>LAN Options</td></tr>
<tr><th align="left"><div style="width:290px">options.multiplayer.title</div></th><td>Multiplayer Options...</td><td>Open to LAN</td></tr>
<tr><th align="left"><div style="width:290px">options.sharePresence</div></th><td>Presence</td><td>Visibility</td></tr>
<tr><th align="left"><div style="width:290px">options.sharePresence.all</div></th><td>All</td><td>Full</td></tr>
<tr><th align="left"><div style="width:290px">options.sharePresence.all.tooltip</div></th><td>Presence is shared with your friends. Appearing as online and sharing what you are doing.</td><td>Friends can see what you're playing.</td></tr>
<tr><th align="left"><div style="width:290px">options.sharePresence.limited.tooltip</div></th><td>Sharing limited presence. Appearing as online, but not sharing what you are doing.</td><td>Friends can see when you're online, but not what you're playing.</td></tr>
<tr><th align="left"><div style="width:290px">options.sharePresence.none</div></th><td>None</td><td>Hidden</td></tr>
<tr><th align="left"><div style="width:290px">options.sharePresence.none.tooltip</div></th><td>Not sharing any presence. Appearing as offline.</td><td>Friends will always see you as offline.</td></tr>
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
+ minecraft/tags/entity_type/not_affected_by_geysers.json
```

</details>
</details>
<hr/>