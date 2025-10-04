## Comparison with [1.21.9](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.9)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.9</th><th>1.21.10-rc1</th></tr><tr><td>DataPack version</td><td><pre>{
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
}</pre></td></tr><tr><td>World version</td><td><pre>4554</pre></td><td><pre>4555</pre></td></tr><tr><td>Protocol version</td><td><pre>773</pre></td><td><pre>1073742098</pre></td></tr></table>
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
XXX.entity.decoration.HangingEntity +1M
```
```
XXX.entity.decoration.ItemFrame +2M
```
```
XXX.level.block.BasePressurePlateBlock +1M -1M
```
```
XXX.level.block.CactusBlock +1M -1M
```
```
XXX.level.block.CampfireBlock +1M -1M
```
```
XXX.level.block.EndPortalBlock +1M -1M
```
```
XXX.level.block.FrogspawnBlock +1M -1M
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.LayeredCauldronBlock +1M -1M
```
```
XXX.level.block.NetherPortalBlock +1M -1M
```
```
XXX.level.block.PowderSnowBlock +1M -1M
```
```
XXX.level.block.WitherRoseBlock +1M -1M
```
```
XXX.block.state.BlockBehaviour +1M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +1M -1M
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.HangingEntity
</summary>

```diff
- AABB getPopBox()
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
- AABB createBoundingBox(BlockPos,Direction,boolean)
- AABB getPopBox()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BasePressurePlateBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CactusBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndPortalBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FrogspawnBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LayeredCauldronBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NetherPortalBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PowderSnowBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WitherRoseBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- void entityInside(Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.world.entity.Entity +1M -1M
```
```
XXX.level.block.BaseFireBlock +1M -1M
```
```
XXX.level.block.BigDripleafBlock +1M -1M
```
```
XXX.level.block.BubbleColumnBlock +1M -1M
```
```
XXX.level.block.ButtonBlock +1M -1M
```
```
XXX.level.block.CropBlock +1M -1M
```
```
XXX.level.block.DetectorRailBlock +1M -1M
```
```
XXX.level.block.EndGatewayBlock +1M -1M
```
```
XXX.level.block.EyeblossomBlock +1M -1M
```
```
XXX.level.block.HoneyBlock +1M -1M
```
```
XXX.level.block.LavaCauldronBlock +1M -1M
```
```
XXX.level.block.PitcherCropBlock +1M -1M
```
```
XXX.level.block.SweetBerryBushBlock +1M -1M
```
```
XXX.level.block.TripWireBlock +1M -1M
```
```
XXX.level.block.WaterlilyBlock +1M -1M
```
```
XXX.level.block.WebBlock +1M -1M
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean lambda$checkInsideBlocks$0(int,AtomicInteger,boolean,Vec3,Vec3,LongSet,boolean,AABB,InsideBlockEffectApplier$StepBasedCollector,BlockPos,int)
+ boolean lambda$checkInsideBlocks$0(int,AtomicInteger,boolean,Vec3,Vec3,LongSet,InsideBlockEffectApplier$StepBasedCollector,BlockPos,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BigDripleafBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BubbleColumnBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CropBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DetectorRailBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndGatewayBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EyeblossomBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HoneyBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LavaCauldronBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PitcherCropBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SweetBerryBushBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TripWireBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WaterlilyBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WebBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier,boolean)
+ void entityInside(BlockState,Level,BlockPos,Entity,InsideBlockEffectApplier)
```

</details>
</details>
<hr/>