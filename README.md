<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.19.4-rc1 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.19.4-rc1</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2023-03-09T14:35:50+00:00</td></tr>
<tr><th>SHA1</th><td>35bf3603374700669d53979aae6f985f6153a931</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/35bf3603374700669d53979aae6f985f6153a931/1.19.4-rc1.json">https://piston-meta.mojang.com/v1/packages/35bf3603374700669d53979aae6f985f6153a931/1.19.4-rc1.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/3cb24cc5123384f5edf4698ea16ad8ce3fbbc1ba/3.json">https://piston-meta.mojang.com/v1/packages/3cb24cc5123384f5edf4698ea16ad8ce3fbbc1ba/3.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/c41c9653dc18634f52c010040177deabf9a878f2/server.jar">https://piston-data.mojang.com/v1/objects/c41c9653dc18634f52c010040177deabf9a878f2/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/9aea4cf2285542a205e9fb54562d0cedb0a38fb0/server.txt">https://piston-data.mojang.com/v1/objects/9aea4cf2285542a205e9fb54562d0cedb0a38fb0/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/d516cfa228f59e4b6f829a1742efe36b72065e8c/client.jar">https://piston-data.mojang.com/v1/objects/d516cfa228f59e4b6f829a1742efe36b72065e8c/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/b3937044d212fd2cf0439b6d34fb08726bfeec8b/client.txt">https://piston-data.mojang.com/v1/objects/b3937044d212fd2cf0439b6d34fb08726bfeec8b/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.4-pre4">1.19.4-pre4</a>

# Mappings

### Client




<details><summary>net.minecraft.server.MinecraftServer</summary>

```diff
+ void forceTimeSynchronization()
+ void synchronizeTime(ServerLevel)
```

</details>


<details><summary>net.minecraft.world.entity.Display</summary>

```diff
+ int getInterpolationDelay()
- long getInterpolationStartTick()
+ void setInterpolationDelay(int)
- void setInterpolationStartTick(long)
```

</details>


<details><summary>net.minecraft.world.entity.Display$FloatInterpolator</summary>

```diff
+ Float getGeneric(float)
+ Object getGeneric(float)
- void updateValue(float,Float)
- void updateValue(float,Object)
```

</details>


<details><summary>net.minecraft.world.entity.Display$IntInterpolator</summary>

```diff
+ Integer getGeneric(float)
+ Object getGeneric(float)
- void updateValue(float,Integer)
- void updateValue(float,Object)
```

</details>


<details><summary>net.minecraft.world.entity.Display$Interpolator</summary>

```diff
+ void updateValue(float,Object)
```

</details>


### Server




<details><summary>net.minecraft.network.syncher.SynchedEntityData</summary>

```diff
+ void set(EntityDataAccessor,Object,boolean)
```

</details>


<details><summary>net.minecraft.server.MinecraftServer</summary>

```diff
+ void forceTimeSynchronization()
+ void synchronizeTime(ServerLevel)
```

</details>


<details><summary>net.minecraft.world.entity.Display</summary>

```diff
+ int getInterpolationDelay()
- long getInterpolationStartTick()
+ void setInterpolationDelay(int)
- void setInterpolationStartTick(long)
```

</details>


<details><summary>net.minecraft.world.entity.Display$FloatInterpolator</summary>

```diff
+ Float getGeneric(float)
+ Object getGeneric(float)
- void updateValue(float,Float)
- void updateValue(float,Object)
```

</details>


<details><summary>net.minecraft.world.entity.Display$IntInterpolator</summary>

```diff
+ Integer getGeneric(float)
+ Object getGeneric(float)
- void updateValue(float,Integer)
- void updateValue(float,Object)
```

</details>


<details><summary>net.minecraft.world.entity.Display$Interpolator</summary>

```diff
+ void updateValue(float,Object)
```

</details>
