<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.15.1-pre1 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.15.1-pre1</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2019-12-12T14:02:30+00:00</td></tr>
<tr><th>SHA1</th><td>1b5aee0865f805a44ecdbed04c964352e86534f2</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/1b5aee0865f805a44ecdbed04c964352e86534f2/1.15.1-pre1.json">https://piston-meta.mojang.com/v1/packages/1b5aee0865f805a44ecdbed04c964352e86534f2/1.15.1-pre1.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/58c12b1e2878e0a78719778acb803746450b3f1c/1.15.json">https://piston-meta.mojang.com/v1/packages/58c12b1e2878e0a78719778acb803746450b3f1c/1.15.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/289a247dd42928880769398b049d3890513f2917/server.jar">https://piston-data.mojang.com/v1/objects/289a247dd42928880769398b049d3890513f2917/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/3a818e8d2f85b4a1ca6a35bac57be84e81d907a7/server.txt">https://piston-data.mojang.com/v1/objects/3a818e8d2f85b4a1ca6a35bac57be84e81d907a7/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/70e27f84a178951b0df7c42c7b9313782cb9925e/client.jar">https://piston-data.mojang.com/v1/objects/70e27f84a178951b0df7c42c7b9313782cb9925e/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/054ee5085ec49b6d037d10d43c04fd4c9c3b9f4b/client.txt">https://piston-data.mojang.com/v1/objects/054ee5085ec49b6d037d10d43c04fd4c9c3b9f4b/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.15">1.15</a>

# Mappings

### Client




<details><summary>com.mojang.realmsclient.RealmsMainScreen</summary>

```diff
- int access$1900(RealmsMainScreen)
- int access$1902(RealmsMainScreen,int)
+ int access$2000(RealmsMainScreen)
+ int access$2002(RealmsMainScreen,int)
- RealmsButton access$1700(RealmsMainScreen)
+ RealmsButton access$1900(RealmsMainScreen)
+ RealmsMainScreen$RealmSelectionList access$1700(RealmsMainScreen)
- RealmsMainScreen$RealmSelectionList access$1800(RealmsMainScreen)
+ void access$1800(RealmsMainScreen,RealmsServer)
- void access$2000(RealmsMainScreen,RealmsServer)
```

</details>


<details><summary>com.mojang.realmsclient.RealmsMainScreen$12</summary>

```diff
+ boolean lambda$run$0(RealmListEntry)
```

</details>


### Server




<details><summary>net.minecraft.world.level.block.Block$2</summary>

```diff
+ void <init>(int,float)
- void <init>(int)
```

</details>


<details><summary>net.minecraft.world.level.block.state.AbstractStateHolder</summary>

```diff
- boolean equals(Object)
- int hashCode()
```

</details>
