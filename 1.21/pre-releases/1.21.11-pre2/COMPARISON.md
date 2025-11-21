## Comparison with [1.21.11-pre1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.11-pre1)

> [!TIP]
> - [Version data](#version-data)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.11-pre1</th><th>1.21.11-pre2</th></tr><tr><td>DataPack version</td><td><pre>{
  "major": 94,
  "minor": 0
}</pre></td><td><pre>{
  "major": 94,
  "minor": 0
}</pre></td></tr><tr><td>ResourcePack version</td><td><pre>{
  "major": 75,
  "minor": 0
}</pre></td><td><pre>{
  "major": 75,
  "minor": 0
}</pre></td></tr><tr><td>World version</td><td><pre>4663</pre></td><td><pre>4664</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742103</pre></td><td><pre>1073742104</pre></td></tr></table>
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
<tr><th>Name</th><th>1.21.11-pre1</th><th>1.21.11-pre2</th></tr>
<tr><th align="left"><div style="width:290px">options.cutoutLeaves.tooltip</div></th><td>Allows to see through gaps in leaves. Disabling may improve performance.</td><td>Allows you to see through gaps in leaves. Disabling improves performance.</td></tr>
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
XXX.server.level.ServerPlayer -1M
```
```
XXX.minecraft.world.LockCode +1M
```
```
XXX.level.block.LeavesBlock +2M | +1P
```
```
XXX.block.entity.BaseContainerBlockEntity +1M -1M
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ void playNotifySound(SoundEvent,SoundSource,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.LockCode
</summary>

```diff
- boolean canUnlock(Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LeavesBlock
</summary>

```diff
- boolean skipRendering(BlockState,BlockState,Direction)
- void setCutoutLeaves(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BaseContainerBlockEntity
</summary>

```diff
+ boolean canUnlock(Player,LockCode,Component)
- void sendChestLockedNotifications(Vec3,Player,Component)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.client.Options +1M -1M
```
```
XXX.client.player.LocalPlayer -1M
```
```
XXX.entity.player.Player -1M
```
```
XXX.entity.projectile.ProjectileUtil +1M -1M
```
```
XXX.levelgen.structure.LegacyStructureDataHandler +2P
```

</details>
<details>
<summary>
net.minecraft.client.Options
</summary>

```diff
+ void lambda$new$127(Integer)
- void lambda$new$127(Minecraft,Integer)
```

</details>
<details>
<summary>
net.minecraft.client.player.LocalPlayer
</summary>

```diff
+ void playNotifySound(SoundEvent,SoundSource,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
+ void playNotifySound(SoundEvent,SoundSource,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ProjectileUtil
</summary>

```diff
- Either getHitEntitiesAlong(Entity,AttackRange,Predicate,ClipContext$Block)
+ Either getHitEntitiesAlong(Entity,AttackRange,Predicate)
```

</details>
</details>
<hr/>