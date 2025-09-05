## Comparison with [25w34a](https://github.com/PixiGeko/Minecraft-generated-data/tree/25w34a)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">25w34a</th><th>25w34b</th></tr><tr><td>DataPack version</td><td><pre>{
  "major": 84,
  "minor": 0
}</pre></td><td><pre>{
  "major": 84,
  "minor": 0
}</pre></td></tr><tr><td>ResourcePack version</td><td><pre>{
  "major": 66,
  "minor": 0
}</pre></td><td><pre>{
  "major": 66,
  "minor": 0
}</pre></td></tr><tr><td>World version</td><td><pre>4539</pre></td><td><pre>4540</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742087</pre></td><td><pre>1073742088</pre></td></tr></table>
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
XXX.client.renderer.OrderedSubmitNodeCollector +3P -3P
```
```
XXX.client.renderer.SubmitNodeStorage +3M -3M
```
```
XXX.client.renderer.SubmitNodeStorage$BlockSubmit +2M -1M | +1P
```
```
XXX.client.renderer.SubmitNodeStorage$ItemSubmit +2M -1M | +1P
```
```
XXX.entity.layers.MushroomCowMushroomLayer +1M -1M
```
```
XXX.entity.layers.PlayerItemInHandLayer +1M -1M
```
```
XXX.renderer.feature.BlockFeatureRenderer +1M -1M
```
```
XXX.renderer.item.ItemStackRenderState +1M -1M
```
```
XXX.renderer.item.ItemStackRenderState$LayerRenderState +1M -1M
```

</details>
<details>
<summary>
net.minecraft.client.renderer.SubmitNodeStorage
</summary>

```diff
- void submitBlock(PoseStack,BlockState,int,int,int)
+ void submitBlock(PoseStack,BlockState,int,int)
- void submitBlockModel(PoseStack,RenderType,BlockStateModel,float,float,float,int,int,int)
+ void submitBlockModel(PoseStack,RenderType,BlockStateModel,float,float,float,int,int)
- void submitItem(PoseStack,ItemDisplayContext,int,int,int,int[],List,RenderType,ItemStackRenderState$FoilType)
+ void submitItem(PoseStack,ItemDisplayContext,int,int,int[],List,RenderType,ItemStackRenderState$FoilType)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.SubmitNodeStorage$BlockSubmit
</summary>

```diff
- int outlineColor()
- void <init>(PoseStack$Pose,BlockState,int,int,int)
+ void <init>(PoseStack$Pose,BlockState,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.SubmitNodeStorage$ItemSubmit
</summary>

```diff
- int outlineColor()
- void <init>(PoseStack$Pose,ItemDisplayContext,int,int,int,int[],List,RenderType,ItemStackRenderState$FoilType)
+ void <init>(PoseStack$Pose,ItemDisplayContext,int,int,int[],List,RenderType,ItemStackRenderState$FoilType)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
</summary>

```diff
+ void submitMushroomBlock(PoseStack,SubmitNodeCollector,int,boolean,BlockState,int,BlockStateModel)
- void submitMushroomBlock(PoseStack,SubmitNodeCollector,int,boolean,int,BlockState,int,BlockStateModel)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
</summary>

```diff
+ void renderItemHeldToEye(ItemStackRenderState,HumanoidArm,PoseStack,SubmitNodeCollector,int)
- void renderItemHeldToEye(PlayerRenderState,HumanoidArm,PoseStack,SubmitNodeCollector,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.feature.BlockFeatureRenderer
</summary>

```diff
- void render(SubmitNodeCollection,MultiBufferSource$BufferSource,BlockRenderDispatcher,OutlineBufferSource)
+ void render(SubmitNodeCollection,MultiBufferSource$BufferSource,BlockRenderDispatcher)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.ItemStackRenderState
</summary>

```diff
- void submit(PoseStack,SubmitNodeCollector,int,int,int)
+ void submit(PoseStack,SubmitNodeCollector,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.ItemStackRenderState$LayerRenderState
</summary>

```diff
- void submit(PoseStack,SubmitNodeCollector,int,int,int)
+ void submit(PoseStack,SubmitNodeCollector,int,int)
```

</details>
</details>
<hr/>