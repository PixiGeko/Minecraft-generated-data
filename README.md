<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.19.3-rc3 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.19.3-rc3</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2022-12-06T10:24:01+00:00</td></tr>
<tr><th>SHA1</th><td>cf1a923e92ab12bf3daebf91d05a3dbbd1d147e6</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/cf1a923e92ab12bf3daebf91d05a3dbbd1d147e6/1.19.3-rc3.json">https://piston-meta.mojang.com/v1/packages/cf1a923e92ab12bf3daebf91d05a3dbbd1d147e6/1.19.3-rc3.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/74d3793f18d13d323c17240cc1d7962af605bd88/2.json">https://piston-meta.mojang.com/v1/packages/74d3793f18d13d323c17240cc1d7962af605bd88/2.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/5f459ba58558d797229c819c0314bec84e774ecb/server.jar">https://piston-data.mojang.com/v1/objects/5f459ba58558d797229c819c0314bec84e774ecb/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/48f573d570db6fa7ab99e62ce2bf4a00abcc6166/server.txt">https://piston-data.mojang.com/v1/objects/48f573d570db6fa7ab99e62ce2bf4a00abcc6166/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/df83f55790fadb7aba06e84605531d421c6f8fe2/client.jar">https://piston-data.mojang.com/v1/objects/df83f55790fadb7aba06e84605531d421c6f8fe2/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/81e3f0b8287c0b7faaae21031446526cb615465a/client.txt">https://piston-data.mojang.com/v1/objects/81e3f0b8287c0b7faaae21031446526cb615465a/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.3-rc2">1.19.3-rc2</a>

# Mappings

### Client




### Server




<details><summary>net.minecraft.network.protocol.game.ClientboundRespawnPacket</summary>

```diff
+ boolean shouldKeep(byte)
- boolean shouldKeepAllPlayerData()
- void <init>(ResourceKey,ResourceKey,long,GameType,GameType,boolean,boolean,boolean,Optional)
+ void <init>(ResourceKey,ResourceKey,long,GameType,GameType,boolean,boolean,byte,Optional)
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:text2speech:1.13.9
- com.mojang:text2speech:1.13.9:natives-linux
- com.mojang:text2speech:1.13.9:natives-windows
+ com.mojang:text2speech:1.16.7
+ org.lwjgl:lwjgl-glfw:3.3.1:natives-windows-arm64
+ org.lwjgl:lwjgl-jemalloc:3.3.1:natives-windows-arm64
+ org.lwjgl:lwjgl-openal:3.3.1:natives-windows-arm64
+ org.lwjgl:lwjgl-opengl:3.3.1:natives-windows-arm64
+ org.lwjgl:lwjgl-stb:3.3.1:natives-windows-arm64
+ org.lwjgl:lwjgl-tinyfd:3.3.1:natives-windows-arm64
+ org.lwjgl:lwjgl:3.3.1:natives-windows-arm64
```

</details>
