<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.16.2-rc1 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.16.2-rc1</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2020-08-07T14:35:39+00:00</td></tr>
<tr><th>SHA1</th><td>541ad2a92d12e6d36fb6c2b29b5d69ae4b97ab23</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/541ad2a92d12e6d36fb6c2b29b5d69ae4b97ab23/1.16.2-rc1.json">https://piston-meta.mojang.com/v1/packages/541ad2a92d12e6d36fb6c2b29b5d69ae4b97ab23/1.16.2-rc1.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json">https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/203e18d79201b5e8c46019074b07e1c3b4c75f57/server.jar">https://piston-data.mojang.com/v1/objects/203e18d79201b5e8c46019074b07e1c3b4c75f57/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/40337a76c8486473e5990f7bb44b13bc08b69e7a/server.txt">https://piston-data.mojang.com/v1/objects/40337a76c8486473e5990f7bb44b13bc08b69e7a/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/dd4982bb447c1d2c7c03419b90dbe8f017c47311/client.jar">https://piston-data.mojang.com/v1/objects/dd4982bb447c1d2c7c03419b90dbe8f017c47311/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/04a5a4eed85acef3fd6a43236564ef79f5b4d0c9/client.txt">https://piston-data.mojang.com/v1/objects/04a5a4eed85acef3fd6a43236564ef79f5b4d0c9/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.2-pre3">1.16.2-pre3</a>

# Mappings

### Client




<details><summary>net.minecraft.client.Minecraft</summary>

```diff
+ void clearResourcePacksOnError(Throwable,Component)
+ void lambda$clearResourcePacksOnError$3(Component)
- void lambda$rollbackResourcePacks$3(Component)
```

</details>


<details><summary>net.minecraft.client.gui.screens.PresetFlatWorldScreen</summary>

```diff
+ Biome lambda$fromString$1(Registry,ResourceKey)
+ Biome lambda$null$4(Registry,ResourceKey)
- FlatLevelGeneratorSettings lambda$preset$3(List,boolean,boolean,boolean,FlatLayerInfo[],ResourceKey,Registry)
+ FlatLevelGeneratorSettings lambda$preset$5(List,boolean,boolean,boolean,FlatLayerInfo[],ResourceKey,Registry)
- void lambda$init$1(Registry,Button)
- void lambda$init$2(Button)
+ void lambda$init$2(Registry,Button)
+ void lambda$init$3(Button)
```

</details>


### Server


