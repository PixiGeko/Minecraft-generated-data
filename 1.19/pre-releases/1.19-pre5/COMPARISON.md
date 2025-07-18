## Comparison with [1.19-pre4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19-pre4)

> [!TIP]
> - [Version data](#version-data)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.19-pre4</th><th>1.19-pre5</th></tr><tr><td>World version</td><td><pre>3101</pre></td><td><pre>3102</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741912</pre></td><td><pre>1073741913</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ chat.disabled.profile.moreInfo: Chat not allowed by account settings. Cannot send or view messages.
+ subtitles.block.sculk.charge: Sculk bubbles
+ subtitles.block.sculk.spread: Sculk spreads
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.19-pre4</th><th>1.19-pre5</th></tr>
<tr><th align="left"><div style="width:290px">chat.disabled.profile</div></th><td>Chat not allowed by account settings. Cannot send message</td><td>Chat not allowed by account settings. Press '%s' again for more information</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.level.chunk.PalettedContainer$Strategy
- XXX.level.chunk.PalettedContainer$Strategy$1
+ XXX.level.chunk.PalettedContainer$Strategy$2
- XXX.level.chunk.PalettedContainerRO
- XXX.level.chunk.PalettedContainerRO$Unpacker
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.animal.allay.Allay +1M
```
```
XXX.levelgen.presets.WorldPreset +1M
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.allay.Allay
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPreset
</summary>

```diff
- DataResult requireOverworld(WorldPreset)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.level.chunk.PalettedContainer$Strategy
- XXX.level.chunk.PalettedContainer$Strategy$1
+ XXX.level.chunk.PalettedContainer$Strategy$2
- XXX.level.chunk.PalettedContainerRO
- XXX.level.chunk.PalettedContainerRO$Unpacker
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.client.Minecraft +30M -29M
```
```
XXX.minecraft.client.Minecraft$ChatStatus +2P
```
```
XXX.client.gui.Gui +2M | +1P
```
```
XXX.gui.screens.ConfirmLinkScreen +1M
```
```
XXX.minecraft.nbt.StringTag -1P
```
```
XXX.animal.allay.Allay +1M
```
```
XXX.levelgen.presets.WorldPreset +1M
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
+ boolean lambda$tick$35()
- boolean lambda$tick$36()
+ ChunkProgressListener lambda$doWorldLoad$36(int)
- ChunkProgressListener lambda$doWorldLoad$37(int)
+ CompletionStage lambda$delayTextureReload$47(CompletableFuture)
- CompletionStage lambda$delayTextureReload$48(CompletableFuture)
+ IntegratedServer lambda$doWorldLoad$37(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
- IntegratedServer lambda$doWorldLoad$38(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
+ PackResources lambda$adaptV3$51(Supplier)
- PackResources lambda$adaptV3$52(Supplier)
+ PackResources lambda$adaptV4$52(Supplier)
- PackResources lambda$adaptV4$53(Supplier)
+ String lambda$doWorldLoad$38(WorldStem)
- String lambda$doWorldLoad$39(WorldStem)
+ String lambda$fillSystemReport$40(String)
+ String lambda$fillSystemReport$41(Minecraft)
- String lambda$fillSystemReport$41(String)
+ String lambda$fillSystemReport$42()
- String lambda$fillSystemReport$42(Minecraft)
- String lambda$fillSystemReport$45()
+ String lambda$fillSystemReport$45(Options)
+ String lambda$fillSystemReport$46(LanguageManager)
- String lambda$fillSystemReport$46(Options)
- String lambda$fillSystemReport$47(LanguageManager)
+ Style lambda$debugClientMetricsStart$26(Path,Style)
- Style lambda$debugClientMetricsStart$27(Path,Style)
+ Style lambda$grabHugeScreenshot$50(File,Style)
- Style lambda$grabHugeScreenshot$51(File,Style)
+ Style lambda$grabPanoramixScreenshot$49(File,Style)
- Style lambda$grabPanoramixScreenshot$50(File,Style)
+ void lambda$debugClientMetricsStart$24(Consumer,double,int)
- void lambda$debugClientMetricsStart$25(Consumer,double,int)
+ void lambda$debugClientMetricsStart$25(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$26(Consumer,ProfileResults)
+ void lambda$debugClientMetricsStart$27(Consumer,Component)
- void lambda$debugClientMetricsStart$28(Consumer,Component)
+ void lambda$debugClientMetricsStart$28(Consumer,Path)
- void lambda$debugClientMetricsStart$29(Consumer,Path)
+ void lambda$debugClientMetricsStart$29(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$30(Consumer,Path)
- void lambda$debugClientMetricsStart$30(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$31(Consumer,CompletableFuture,CompletableFuture)
- void lambda$debugClientMetricsStart$31(Consumer,Path)
- void lambda$debugClientMetricsStart$32(Consumer,CompletableFuture,CompletableFuture)
+ void lambda$debugClientMetricsStart$32(ProfileResults)
+ void lambda$debugClientMetricsStart$33(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$33(ProfileResults)
- void lambda$debugClientMetricsStart$34(Consumer,ProfileResults)
+ void lambda$doWorldLoad$39(Component)
- void lambda$doWorldLoad$40(Component)
+ void lambda$grabPanoramixScreenshot$48(Component)
- void lambda$grabPanoramixScreenshot$49(Component)
- void lambda$openChatScreen$22(boolean)
+ void lambda$runTick$22(CompletableFuture)
- void lambda$runTick$23(CompletableFuture)
+ void lambda$runTick$23(TimerQuery)
- void lambda$runTick$24(TimerQuery)
+ void lambda$tick$34()
- void lambda$tick$35()
```

</details>
<details>
<summary>
net.minecraft.client.gui.Gui
</summary>

```diff
- boolean isShowingChatDisabledByPlayer()
- void setChatDisabledByPlayerShown(boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ConfirmLinkScreen
</summary>

```diff
- void <init>(BooleanConsumer,Component,String,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.allay.Allay
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPreset
</summary>

```diff
- DataResult requireOverworld(WorldPreset)
```

</details>
</details>
<hr/>