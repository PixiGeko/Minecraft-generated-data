## Comparison with [1.21.9-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.9-pre3)

> [!TIP]
> - [Version data](#version-data)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.9-pre3</th><th>1.21.9-pre4</th></tr><tr><td>DataPack version</td><td><pre>{
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
}</pre></td></tr><tr><td>World version</td><td><pre>4551</pre></td><td><pre>4552</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742095</pre></td><td><pre>1073742096</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.21.9-pre3</th><th>1.21.9-pre4</th></tr>
<tr><th align="left"><div style="width:290px">debug.options.help</div></th><td>F3 + F5 = Edit debug options</td><td>F3 + F6 = Edit debug options</td></tr>
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
Changes
</summary>

```
XXX.jsonrpc.methods.PlayerService$KickDto +2M -2M | +2P -2P
```

</details>
<details>
<summary>
net.minecraft.server.jsonrpc.methods.PlayerService$KickDto
</summary>

```diff
+ List players()
- PlayerDto player()
+ void <init>(List,Optional)
- void <init>(PlayerDto,Optional)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.client.renderer.OrderedSubmitNodeCollector +1P -1P
```
```
XXX.renderer.blockentity.BannerRenderer +3M -3M
```
```
XXX.renderer.blockentity.BedRenderer +2M -2M
```
```
XXX.renderer.blockentity.DecoratedPotRenderer +1M -1M
```
```
XXX.renderer.blockentity.ShulkerBoxRenderer +1M -1M
```
```
XXX.renderer.feature.ModelPartFeatureRenderer +1M -1M
```
```
XXX.renderer.special.PlayerHeadSpecialRenderer +2M -2M
```
```
XXX.renderer.special.ShieldSpecialRenderer +2M -2M
```
```
XXX.renderer.special.ShulkerBoxSpecialRenderer +1M -1M
```
```
XXX.renderer.special.SkullSpecialRenderer +1M -1M
```
```
XXX.renderer.special.SpecialModelRenderer +1P -1P
```
```
XXX.jsonrpc.methods.PlayerService +1M -1M
```
```
XXX.entity.projectile.Projectile +3M -2M | +1P
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BannerRenderer
</summary>

```diff
- void submitBanner(MaterialSet,PoseStack,SubmitNodeCollector,int,int,float,BannerModel,BannerFlagModel,float,DyeColor,BannerPatternLayers,ModelFeatureRenderer$CrumblingOverlay,int)
+ void submitBanner(MaterialSet,PoseStack,SubmitNodeCollector,int,int,float,BannerModel,BannerFlagModel,float,DyeColor,BannerPatternLayers,ModelFeatureRenderer$CrumblingOverlay)
- void submitPatterns(MaterialSet,PoseStack,SubmitNodeCollector,int,int,Model,Object,Material,boolean,DyeColor,BannerPatternLayers,boolean,ModelFeatureRenderer$CrumblingOverlay,int)
+ void submitPatterns(MaterialSet,PoseStack,SubmitNodeCollector,int,int,Model,Object,Material,boolean,DyeColor,BannerPatternLayers,ModelFeatureRenderer$CrumblingOverlay)
- void submitSpecial(PoseStack,SubmitNodeCollector,int,int,DyeColor,BannerPatternLayers,int)
+ void submitSpecial(PoseStack,SubmitNodeCollector,int,int,DyeColor,BannerPatternLayers)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BedRenderer
</summary>

```diff
- void submitPiece(PoseStack,SubmitNodeCollector,Model$Simple,Direction,Material,int,int,boolean,ModelFeatureRenderer$CrumblingOverlay,int)
+ void submitPiece(PoseStack,SubmitNodeCollector,Model$Simple,Direction,Material,int,int,boolean,ModelFeatureRenderer$CrumblingOverlay)
- void submitSpecial(PoseStack,SubmitNodeCollector,int,int,Material,int)
+ void submitSpecial(PoseStack,SubmitNodeCollector,int,int,Material)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.DecoratedPotRenderer
</summary>

```diff
- void submit(PoseStack,SubmitNodeCollector,int,int,PotDecorations,int)
+ void submit(PoseStack,SubmitNodeCollector,int,int,PotDecorations)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
</summary>

```diff
- void submit(PoseStack,SubmitNodeCollector,int,int,Direction,float,ModelFeatureRenderer$CrumblingOverlay,Material,int)
+ void submit(PoseStack,SubmitNodeCollector,int,int,Direction,float,ModelFeatureRenderer$CrumblingOverlay,Material)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.feature.ModelPartFeatureRenderer
</summary>

```diff
+ void render(SubmitNodeCollection,MultiBufferSource$BufferSource,MultiBufferSource$BufferSource)
- void render(SubmitNodeCollection,MultiBufferSource$BufferSource,OutlineBufferSource,MultiBufferSource$BufferSource)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.PlayerHeadSpecialRenderer
</summary>

```diff
- void submit(Object,ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean,int)
+ void submit(Object,ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean)
- void submit(PlayerSkinRenderCache$RenderInfo,ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean,int)
+ void submit(PlayerSkinRenderCache$RenderInfo,ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.ShieldSpecialRenderer
</summary>

```diff
- void submit(DataComponentMap,ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean,int)
+ void submit(DataComponentMap,ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean)
- void submit(Object,ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean,int)
+ void submit(Object,ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.ShulkerBoxSpecialRenderer
</summary>

```diff
- void submit(ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean,int)
+ void submit(ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.SkullSpecialRenderer
</summary>

```diff
- void submit(ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean,int)
+ void submit(ItemDisplayContext,PoseStack,SubmitNodeCollector,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.jsonrpc.methods.PlayerService
</summary>

```diff
- List kick(MinecraftApi,List,ClientInfo)
+ List kick(MinecraftApi,PlayerService$KickDto,ClientInfo)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.Projectile
</summary>

```diff
+ boolean checkLeftOwner()
- boolean isOutsideOwnerCollisionRange()
+ boolean lambda$checkLeftOwner$0(AABB,Entity)
- boolean lambda$isOutsideOwnerCollisionRange$0(AABB,Entity)
- void checkLeftOwner()
```

</details>
</details>
<hr/>