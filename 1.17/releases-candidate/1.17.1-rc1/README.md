<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.17.1-rc1 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.17.1-rc1</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2021-07-01T15:23:37+00:00</td></tr>
<tr><th>SHA1</th><td>27d7a88469c5a59420d7b060f2a253802164185f</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/27d7a88469c5a59420d7b060f2a253802164185f/1.17.1-rc1.json">https://piston-meta.mojang.com/v1/packages/27d7a88469c5a59420d7b060f2a253802164185f/1.17.1-rc1.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json">https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/b93cbcf6c65b92621d67b735e8610f7682f54694/server.jar">https://piston-data.mojang.com/v1/objects/b93cbcf6c65b92621d67b735e8610f7682f54694/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/6839be84674e31281fa4539741e7eaab7723524a/server.txt">https://piston-data.mojang.com/v1/objects/6839be84674e31281fa4539741e7eaab7723524a/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/40595d7eeeebc212f6e2b8b5a3dbfc5377cfef9b/client.jar">https://piston-data.mojang.com/v1/objects/40595d7eeeebc212f6e2b8b5a3dbfc5377cfef9b/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/13cad5bd600c9ebc8ebe1038b432053e4c81fb9e/client.txt">https://piston-data.mojang.com/v1/objects/13cad5bd600c9ebc8ebe1038b432053e4c81fb9e/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17.1-pre3">1.17.1-pre3</a>

# Mappings

### Client




<details><summary>net.minecraft.client.gui.screens.worldselection.EditWorldScreen</summary>

```diff
+ boolean lambda$init$12(Path)
- DataResult lambda$init$6(JsonElement)
+ DataResult lambda$init$7(JsonElement)
- void lambda$init$0(Button)
+ void lambda$init$0(Path)
+ void lambda$init$11(Button)
- void lambda$init$11(String)
+ void lambda$init$13(String)
- void lambda$init$4(boolean,boolean)
+ void lambda$init$4(Button)
+ void lambda$init$5(boolean,boolean)
- void lambda$init$5(Button)
+ void lambda$init$6(Button)
- void lambda$init$7(DataResult$PartialResult)
- void lambda$init$8(Button)
+ void lambda$init$8(DataResult$PartialResult)
```

</details>


<details><summary>net.minecraft.server.MinecraftServer</summary>

```diff
- boolean hasWorldScreenshot()
- boolean lambda$getSelectedPacks$13(Collection,String)
+ boolean lambda$getSelectedPacks$14(Collection,String)
- CompletionStage lambda$reloadResources$11(ImmutableList)
+ CompletionStage lambda$reloadResources$12(ImmutableList)
- File getWorldScreenshotFile()
- ImmutableList lambda$reloadResources$10(Collection)
+ ImmutableList lambda$reloadResources$11(Collection)
+ Optional getWorldScreenshotFile()
+ String lambda$fillSystemReport$10()
- String lambda$fillSystemReport$7()
- String lambda$tickChildren$6(ServerLevel)
+ String lambda$tickChildren$7(ServerLevel)
- void lambda$reloadResources$12(Collection,ServerResources)
+ void lambda$reloadResources$13(Collection,ServerResources)
- void lambda$startMetricsRecordingTick$14(Path)
+ void lambda$startMetricsRecordingTick$16(Path)
- void lambda$startRecordingMetrics$16(Consumer,ProfileResults)
+ void lambda$startRecordingMetrics$17(Consumer,ProfileResults)
+ void lambda$updateStatusIcon$6(ServerStatus,File)
```

</details>


<details><summary>net.minecraft.server.players.GameProfileCache</summary>

```diff
- GameProfile get(String)
- GameProfile get(UUID)
- GameProfile lambda$getAsync$1(String)
- GameProfile lookupGameProfile(GameProfileRepository,String)
- GameProfileCache$GameProfileInfo readGameProfile(JsonElement,DateFormat)
+ Optional get(String)
+ Optional get(UUID)
+ Optional lambda$getAsync$1(String)
+ Optional lookupGameProfile(GameProfileRepository,String)
+ Optional readGameProfile(JsonElement,DateFormat)
- void lambda$getAsync$0(Consumer,GameProfile,Throwable)
+ void lambda$getAsync$0(Consumer,Optional,Throwable)
- void lambda$getAsync$2(String,GameProfile,Throwable)
+ void lambda$getAsync$2(String,Optional,Throwable)
- void lambda$getAsync$3(Consumer,GameProfile,Throwable)
+ void lambda$getAsync$3(Consumer,Optional,Throwable)
```

</details>


### Server




<details><summary>net.minecraft.world.level.block.entity.SkullBlockEntity</summary>

```diff
+ void lambda$updateGameprofile$2(Consumer,GameProfile)
- void lambda$updateGameprofile$2(GameProfile,Consumer)
+ void lambda$updateGameprofile$4(Consumer,GameProfile)
+ void lambda$updateGameprofile$5(Optional,Consumer,GameProfile)
+ void lambda$updateGameprofile$6(Consumer,GameProfile,Optional)
```

</details>


<details><summary>net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess</summary>

```diff
- File getIconFile()
+ Optional getIconFile()
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ death.attack.dryout
+ death.attack.dryout.player
```

</details>
