## Comparison with [1.19.4-pre4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.4-pre4)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.19.4-pre4</th><th>1.19.4-rc1</th></tr><tr><td>World version</td><td><pre>3333</pre></td><td><pre>3334</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741947</pre></td><td><pre>1073741948</pre></td></tr></table>
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
XXX.network.syncher.SynchedEntityData +1M
```
```
XXX.minecraft.server.MinecraftServer +2M
```
```
XXX.world.entity.Display +2M -2M | +5P -3P
```
```
XXX.world.entity.Display$FloatInterpolator +2M -2M
```
```
XXX.world.entity.Display$IntInterpolator +2M -2M
```
```
XXX.world.entity.Display$Interpolator +1M | +1P -1P
```

</details>
<details>
<summary>
net.minecraft.network.syncher.SynchedEntityData
</summary>

```diff
- void set(EntityDataAccessor,Object,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- void forceTimeSynchronization()
- void synchronizeTime(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display
</summary>

```diff
- int getInterpolationDelay()
+ long getInterpolationStartTick()
- void setInterpolationDelay(int)
+ void setInterpolationStartTick(long)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display$FloatInterpolator
</summary>

```diff
- Float getGeneric(float)
- Object getGeneric(float)
+ void updateValue(float,Float)
+ void updateValue(float,Object)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display$IntInterpolator
</summary>

```diff
- Integer getGeneric(float)
- Object getGeneric(float)
+ void updateValue(float,Integer)
+ void updateValue(float,Object)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display$Interpolator
</summary>

```diff
- void updateValue(float,Object)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.server.MinecraftServer +2M
```
```
XXX.world.entity.Display +2M -2M | +5P -3P
```
```
XXX.world.entity.Display$FloatInterpolator +2M -2M
```
```
XXX.world.entity.Display$IntInterpolator +2M -2M
```
```
XXX.world.entity.Display$Interpolator +1M | +1P -1P
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- void forceTimeSynchronization()
- void synchronizeTime(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display
</summary>

```diff
- int getInterpolationDelay()
+ long getInterpolationStartTick()
- void setInterpolationDelay(int)
+ void setInterpolationStartTick(long)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display$FloatInterpolator
</summary>

```diff
- Float getGeneric(float)
- Object getGeneric(float)
+ void updateValue(float,Float)
+ void updateValue(float,Object)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display$IntInterpolator
</summary>

```diff
- Integer getGeneric(float)
- Object getGeneric(float)
+ void updateValue(float,Integer)
+ void updateValue(float,Object)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display$Interpolator
</summary>

```diff
- void updateValue(float,Object)
```

</details>
</details>
<hr/>