## Comparison with [1.20](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.20</th><th>1.20.1-rc1</th></tr><tr><td>World version</td><td><pre>3463</pre></td><td><pre>3464</pre></td></tr><tr><td>Protocol version</td><td><pre>763</pre></td><td><pre>1073741966</pre></td></tr></table>
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
XXX.minecraft.network.Connection +1M | +1P
```
```
XXX.level.chunk.ChunkStatus +2M -1M
```

</details>
<details>
<summary>
net.minecraft.network.Connection
</summary>

```diff
- ChannelFuture connect(InetSocketAddress,boolean,Connection)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkStatus
</summary>

```diff
+ Either lambda$generate$20(ChunkAccess,ProfiledDuration,Either)
- Either lambda$generate$21(ProfiledDuration,Either)
- void lambda$generate$20(ChunkAccess)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen +1M -1M
```
```
XXX.gui.screens.RealmsNotificationsScreen +1M -1M
```
```
XXX.gui.screens.ConnectScreen +2P
```
```
XXX.level.chunk.ChunkStatus +2M -1M
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
- void drawPopup(GuiGraphics,int,int,float)
+ void drawPopup(GuiGraphics)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
</summary>

```diff
+ void drawIcons(GuiGraphics,int,int)
- void drawIcons(GuiGraphics)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkStatus
</summary>

```diff
+ Either lambda$generate$20(ChunkAccess,ProfiledDuration,Either)
- Either lambda$generate$21(ProfiledDuration,Either)
- void lambda$generate$20(ChunkAccess)
```

</details>
</details>
<hr/>