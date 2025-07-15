## Comparison with [1.17.1-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17.1-pre3)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.17.1-pre3</th><th>1.17.1-rc1</th></tr><tr><td>World version</td><td><pre>2727</pre></td><td><pre>2728</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741862</pre></td><td><pre>1073741863</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.17.1-pre3</th><th>1.17.1-rc1</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ death.attack.dryout: %1$s died from dehydration
+ death.attack.dryout.player: %1$s died from dehydration whilst trying to escape %2$s
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
XXX.block.entity.SkullBlockEntity +4M -1M
```
```
XXX.level.storage.LevelStorageSource$LevelStorageAccess +1M -1M
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SkullBlockEntity
</summary>

```diff
- void lambda$updateGameprofile$2(Consumer,GameProfile)
+ void lambda$updateGameprofile$2(GameProfile,Consumer)
- void lambda$updateGameprofile$4(Consumer,GameProfile)
- void lambda$updateGameprofile$5(Optional,Consumer,GameProfile)
- void lambda$updateGameprofile$6(Consumer,GameProfile,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
</summary>

```diff
+ File getIconFile()
- Optional getIconFile()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.screens.worldselection.EditWorldScreen +9M -7M
```
```
XXX.minecraft.server.MinecraftServer +10M -10M | -1P
```
```
XXX.server.players.GameProfileCache +8M -8M
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditWorldScreen
</summary>

```diff
- boolean lambda$init$12(Path)
+ DataResult lambda$init$6(JsonElement)
- DataResult lambda$init$7(JsonElement)
+ void lambda$init$0(Button)
- void lambda$init$0(Path)
- void lambda$init$11(Button)
+ void lambda$init$11(String)
- void lambda$init$13(String)
+ void lambda$init$4(boolean,boolean)
- void lambda$init$4(Button)
- void lambda$init$5(boolean,boolean)
+ void lambda$init$5(Button)
- void lambda$init$6(Button)
+ void lambda$init$7(DataResult$PartialResult)
+ void lambda$init$8(Button)
- void lambda$init$8(DataResult$PartialResult)
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
+ boolean hasWorldScreenshot()
+ boolean lambda$getSelectedPacks$13(Collection,String)
- boolean lambda$getSelectedPacks$14(Collection,String)
+ CompletionStage lambda$reloadResources$11(ImmutableList)
- CompletionStage lambda$reloadResources$12(ImmutableList)
+ File getWorldScreenshotFile()
+ ImmutableList lambda$reloadResources$10(Collection)
- ImmutableList lambda$reloadResources$11(Collection)
- Optional getWorldScreenshotFile()
- String lambda$fillSystemReport$10()
+ String lambda$fillSystemReport$7()
+ String lambda$tickChildren$6(ServerLevel)
- String lambda$tickChildren$7(ServerLevel)
+ void lambda$reloadResources$12(Collection,ServerResources)
- void lambda$reloadResources$13(Collection,ServerResources)
+ void lambda$startMetricsRecordingTick$14(Path)
- void lambda$startMetricsRecordingTick$16(Path)
+ void lambda$startRecordingMetrics$16(Consumer,ProfileResults)
- void lambda$startRecordingMetrics$17(Consumer,ProfileResults)
- void lambda$updateStatusIcon$6(ServerStatus,File)
```

</details>
<details>
<summary>
net.minecraft.server.players.GameProfileCache
</summary>

```diff
+ GameProfile get(String)
+ GameProfile get(UUID)
+ GameProfile lambda$getAsync$1(String)
+ GameProfile lookupGameProfile(GameProfileRepository,String)
+ GameProfileCache$GameProfileInfo readGameProfile(JsonElement,DateFormat)
- Optional get(String)
- Optional get(UUID)
- Optional lambda$getAsync$1(String)
- Optional lookupGameProfile(GameProfileRepository,String)
- Optional readGameProfile(JsonElement,DateFormat)
+ void lambda$getAsync$0(Consumer,GameProfile,Throwable)
- void lambda$getAsync$0(Consumer,Optional,Throwable)
+ void lambda$getAsync$2(String,GameProfile,Throwable)
- void lambda$getAsync$2(String,Optional,Throwable)
+ void lambda$getAsync$3(Consumer,GameProfile,Throwable)
- void lambda$getAsync$3(Consumer,Optional,Throwable)
```

</details>
</details>
<hr/>