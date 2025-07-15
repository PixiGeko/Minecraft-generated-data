## Comparison with [22w16a](https://github.com/PixiGeko/Minecraft-generated-data/tree/22w16a)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">22w16a</th><th>22w16b</th></tr><tr><td>World version</td><td><pre>3091</pre></td><td><pre>3092</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741904</pre></td><td><pre>1073741905</pre></td></tr></table>
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
XXX.level.storage.LevelStorageSource +3M -2M
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource
</summary>

```diff
+ LevelSummary lambda$levelSummaryReader$5(LevelStorageSource$LevelDirectory,boolean,Path,DataFixer)
- LevelSummary lambda$levelSummaryReader$6(LevelStorageSource$LevelDirectory,boolean,Path,DataFixer)
- List lambda$loadLevelSummaries$4(List)
+ PrimaryLevelData lambda$getLevelData$4(DynamicOps,DataPackConfig,Lifecycle,Path,DataFixer)
- PrimaryLevelData lambda$getLevelData$5(DynamicOps,DataPackConfig,Lifecycle,Path,DataFixer)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.level.storage.LevelStorageSource +3M -2M
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource
</summary>

```diff
+ LevelSummary lambda$levelSummaryReader$5(LevelStorageSource$LevelDirectory,boolean,Path,DataFixer)
- LevelSummary lambda$levelSummaryReader$6(LevelStorageSource$LevelDirectory,boolean,Path,DataFixer)
- List lambda$loadLevelSummaries$4(List)
+ PrimaryLevelData lambda$getLevelData$4(DynamicOps,DataPackConfig,Lifecycle,Path,DataFixer)
- PrimaryLevelData lambda$getLevelData$5(DynamicOps,DataPackConfig,Lifecycle,Path,DataFixer)
```

</details>
</details>
<hr/>