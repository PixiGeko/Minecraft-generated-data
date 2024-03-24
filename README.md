<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.20.1-rc1 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.20.1-rc1</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2023-06-09T14:15:49+00:00</td></tr>
<tr><th>SHA1</th><td>d50e4d227ec555b0264327302929cc2c7d0bac40</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/d50e4d227ec555b0264327302929cc2c7d0bac40/1.20.1-rc1.json">https://piston-meta.mojang.com/v1/packages/d50e4d227ec555b0264327302929cc2c7d0bac40/1.20.1-rc1.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/1b51f68c6f2d8ac4261b4043a6578bd60fd45d5c/5.json">https://piston-meta.mojang.com/v1/packages/1b51f68c6f2d8ac4261b4043a6578bd60fd45d5c/5.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/6890ac51068a05e3fcc4158478247e5a5e47bcac/server.jar">https://piston-data.mojang.com/v1/objects/6890ac51068a05e3fcc4158478247e5a5e47bcac/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/edc6386d1fb5681b82f971877720a7e5914761c3/server.txt">https://piston-data.mojang.com/v1/objects/edc6386d1fb5681b82f971877720a7e5914761c3/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/7daaccba521899b14da6c60ed1ab01805bffeec7/client.jar">https://piston-data.mojang.com/v1/objects/7daaccba521899b14da6c60ed1ab01805bffeec7/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/ec3527c736be91910f7986bd18874ace9884386f/client.txt">https://piston-data.mojang.com/v1/objects/ec3527c736be91910f7986bd18874ace9884386f/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20">1.20</a>

# Mappings

### Client




<details><summary>com.mojang.realmsclient.RealmsMainScreen</summary>

```diff
+ void drawPopup(GuiGraphics,int,int,float)
- void drawPopup(GuiGraphics)
```

</details>


<details><summary>com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen</summary>

```diff
- void drawIcons(GuiGraphics,int,int)
+ void drawIcons(GuiGraphics)
```

</details>


<details><summary>net.minecraft.world.level.chunk.ChunkStatus</summary>

```diff
- Either lambda$generate$20(ChunkAccess,ProfiledDuration,Either)
+ Either lambda$generate$21(ProfiledDuration,Either)
+ void lambda$generate$20(ChunkAccess)
```

</details>


### Server




<details><summary>net.minecraft.network.Connection</summary>

```diff
+ ChannelFuture connect(InetSocketAddress,boolean,Connection)
```

</details>


<details><summary>net.minecraft.world.level.chunk.ChunkStatus</summary>

```diff
- Either lambda$generate$20(ChunkAccess,ProfiledDuration,Either)
+ Either lambda$generate$21(ProfiledDuration,Either)
+ void lambda$generate$20(ChunkAccess)
```

</details>
