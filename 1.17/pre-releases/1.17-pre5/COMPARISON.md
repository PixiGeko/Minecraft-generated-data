## Comparison with [1.17-pre4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17-pre4)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.17-pre4</th><th>1.17-pre5</th></tr><tr><td>World version</td><td><pre>2720</pre></td><td><pre>2721</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741856</pre></td><td><pre>1073741857</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.17-pre4</th><th>1.17-pre5</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
- XXX.datafix.schemas.V1451_6$2
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.server.dedicated.DedicatedServerSettings +1M -1M
```
```
XXX.datafix.fixes.ObjectiveRenderTypeFix +1M -2M
```
```
XXX.datafix.schemas.V1451_6 +8M | +3P
```
```
XXX.datafix.schemas.V1460 +4M -3M
```
```
XXX.level.block.PointedDripstoneBlock +1M
```
```
XXX.block.state.BlockBehaviour +1M
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerSettings
</summary>

```diff
- void <init>(Path)
+ void <init>(RegistryAccess,Path)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
</summary>

```diff
+ Function lambda$makeRule$2(DynamicOps)
+ Pair lambda$makeRule$1(Pair)
- Typed lambda$makeRule$1(Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1451_6
</summary>

```diff
- Map createCriterionTypes(Schema)
- TypeTemplate lambda$createCriterionTypes$3(Schema)
- TypeTemplate lambda$createCriterionTypes$4(Schema)
- TypeTemplate lambda$createCriterionTypes$5(Schema)
- TypeTemplate lambda$createCriterionTypes$6()
- TypeTemplate lambda$createCriterionTypes$7()
- TypeTemplate lambda$registerTypes$2(Map)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1460
</summary>

```diff
- TypeTemplate lambda$registerTypes$42(Map)
+ TypeTemplate lambda$registerTypes$42(Schema)
+ TypeTemplate lambda$registerTypes$44()
- TypeTemplate lambda$registerTypes$44(Schema)
- TypeTemplate lambda$registerTypes$46()
+ TypeTemplate lambda$registerTypes$46(Schema)
- TypeTemplate lambda$registerTypes$47(Schema)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PointedDripstoneBlock
</summary>

```diff
- boolean isCollisionShapeFullBlock(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- boolean isCollisionShapeFullBlock(BlockState,BlockGetter,BlockPos)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.datafix.schemas.V1451_6$2
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.gui.screens.RealmsResetWorldScreen +3M -2M
```
```
XXX.server.dedicated.DedicatedServerSettings +1M -1M
```
```
XXX.datafix.fixes.ObjectiveRenderTypeFix +1M -2M
```
```
XXX.datafix.schemas.V1451_6 +8M | +3P
```
```
XXX.datafix.schemas.V1460 +4M -3M
```
```
XXX.level.block.PointedDripstoneBlock +1M
```
```
XXX.block.state.BlockBehaviour +1M
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
</summary>

```diff
+ void lambda$generationSelectionCallback$8(WorldGenerationInfo)
- void lambda$generationSelectionCallback$9(WorldGenerationInfo)
- void lambda$switchSlot$7(Runnable)
+ void lambda$templateSelectionCallback$7(WorldTemplate)
- void lambda$templateSelectionCallback$8(WorldTemplate)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerSettings
</summary>

```diff
- void <init>(Path)
+ void <init>(RegistryAccess,Path)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
</summary>

```diff
+ Function lambda$makeRule$2(DynamicOps)
+ Pair lambda$makeRule$1(Pair)
- Typed lambda$makeRule$1(Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1451_6
</summary>

```diff
- Map createCriterionTypes(Schema)
- TypeTemplate lambda$createCriterionTypes$3(Schema)
- TypeTemplate lambda$createCriterionTypes$4(Schema)
- TypeTemplate lambda$createCriterionTypes$5(Schema)
- TypeTemplate lambda$createCriterionTypes$6()
- TypeTemplate lambda$createCriterionTypes$7()
- TypeTemplate lambda$registerTypes$2(Map)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1460
</summary>

```diff
- TypeTemplate lambda$registerTypes$42(Map)
+ TypeTemplate lambda$registerTypes$42(Schema)
+ TypeTemplate lambda$registerTypes$44()
- TypeTemplate lambda$registerTypes$44(Schema)
- TypeTemplate lambda$registerTypes$46()
+ TypeTemplate lambda$registerTypes$46(Schema)
- TypeTemplate lambda$registerTypes$47(Schema)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PointedDripstoneBlock
</summary>

```diff
- boolean isCollisionShapeFullBlock(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- boolean isCollisionShapeFullBlock(BlockState,BlockGetter,BlockPos)
```

</details>
</details>
<hr/>