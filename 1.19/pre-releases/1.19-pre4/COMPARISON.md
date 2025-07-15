## Comparison with [1.19-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19-pre3)

> [!TIP]
> - [Version data](#version-data)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.19-pre3</th><th>1.19-pre4</th></tr><tr><td>World version</td><td><pre>3100</pre></td><td><pre>3101</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741911</pre></td><td><pre>1073741912</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ multiplayer.disconnect.out_of_order_chat: Out-of-order chat packet received. Did your system time change?
```

</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.level.chunk.PalettedContainer$Data +1M
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer$Data
</summary>

```diff
- PalettedContainer$Data copy()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.screens.inventory.AbstractContainerScreen +1M
```
```
XXX.minecraft.nbt.StringTag +1P
```
```
XXX.level.chunk.PalettedContainer$Data +1M
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
</summary>

```diff
- void clearDraggingState()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer$Data
</summary>

```diff
- PalettedContainer$Data copy()
```

</details>
</details>
<hr/>