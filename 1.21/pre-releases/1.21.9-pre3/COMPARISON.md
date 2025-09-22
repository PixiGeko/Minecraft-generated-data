## Comparison with [1.21.9-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.9-pre2)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.9-pre2</th><th>1.21.9-pre3</th></tr><tr><td>DataPack version</td><td><pre>{
  "major": 88,
  "minor": 0
}</pre></td><td><pre>{
  "major": 88,
  "minor": 0
}</pre></td></tr><tr><td>ResourcePack version</td><td><pre>{
  "major": 69,
  "minor": 0
}</pre></td><td><pre>{
  "major": 69,
  "minor": 0
}</pre></td></tr><tr><td>World version</td><td><pre>4550</pre></td><td><pre>4551</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742094</pre></td><td><pre>1073742095</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.ai.behavior.TransportItemsBetweenContainers +2M -1M
```
```
XXX.level.block.CopperGolemStatueBlock +1M
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.TransportItemsBetweenContainers
</summary>

```diff
- boolean hasValidTravellingPath(Level,TransportItemsBetweenContainers$TransportItemTarget,PathfinderMob)
+ List getConnectedTargets(TransportItemsBetweenContainers$TransportItemTarget,Level)
- Stream getConnectedTargets(TransportItemsBetweenContainers$TransportItemTarget,Level)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CopperGolemStatueBlock
</summary>

```diff
- VoxelShape getOcclusionShape(BlockState)
```

</details>
</details>
<hr/>