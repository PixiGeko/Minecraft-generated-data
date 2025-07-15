## Comparison with [1.21-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21-pre2)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21-pre2</th><th>1.21-pre3</th></tr><tr><td>DataPack version</td><td><pre>47</pre></td><td><pre>48</pre></td></tr><tr><td>World version</td><td><pre>3949</pre></td><td><pre>3950</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742024</pre></td><td><pre>1073742025</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
enchantment_entity_effect_type
</summary>

```diff
- minecraft:replace_disc
+ minecraft:replace_disk
```

</details>
<details>
<summary>
enchantment_location_based_effect_type
</summary>

```diff
- minecraft:replace_disc
+ minecraft:replace_disk
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/enchantment_entity_effect_type.json
</summary>

```diff
- minecraft:replace_disc
+ minecraft:replace_disk
```

</details>
<details>
<summary>
universal_tags/enchantment_location_based_effect_type.json
</summary>

```diff
- minecraft:replace_disc
+ minecraft:replace_disk
```

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
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.minecraft.util.CommonColors +2P
```
```
XXX.entity.decoration.ItemFrame +1M -1M
```
```
XXX.entity.projectile.ThrownEnderpearl +1M
```
```
XXX.world.item.LeadItem +3M -1M
```
```
XXX.world.item.TridentItem +1M
```
```
XXX.saveddata.maps.MapItemSavedData +1M | +1P
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void assertEntityPosition(Entity,AABB,String)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
+ MapId getFramedMapId()
- MapId getFramedMapId(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEnderpearl
</summary>

```diff
- void onInsideBlock(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.item.LeadItem
</summary>

```diff
+ boolean lambda$bindPlayerMobs$0(Player,Entity)
- boolean lambda$bindPlayerMobs$0(Player,Leashable)
- boolean lambda$leashableInArea$1(Predicate,Entity)
- List leashableInArea(Level,BlockPos,Predicate)
```

</details>
<details>
<summary>
net.minecraft.world.item.TridentItem
</summary>

```diff
- boolean isTooDamagedToUse(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- String getFrameKey(int)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.enchantment.effects.ReplaceDisc
- XXX.enchantment.effects.ReplaceDisk
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +1P
```
```
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.server.level.ServerEntity +4P -4P
```
```
XXX.world.entity.Leashable +2M | +2P
```
```
XXX.ai.attributes.AttributeInstance +1M
```
```
XXX.entity.decoration.LeashFenceKnotEntity +1M
```
```
XXX.entity.player.Player +1M
```
```
XXX.entity.vehicle.Boat +1M
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void assertEntityPosition(Entity,AABB,String)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Leashable
</summary>

```diff
- void elasticRangeLeashBehaviour(Entity,float)
- void legacyElasticRangeLeashBehaviour(Entity,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeInstance
</summary>

```diff
- void addOrReplacePermanentModifier(AttributeModifier)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.LeashFenceKnotEntity
</summary>

```diff
- boolean lambda$interact$0(Player,Leashable)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean isIgnoringFallDamageFromCurrentImpulse()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.Boat
</summary>

```diff
- void elasticRangeLeashBehaviour(Entity,float)
```

</details>
</details>
<hr/>