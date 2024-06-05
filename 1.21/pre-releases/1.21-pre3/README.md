<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.21-pre3 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.21-pre3</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2024-06-05T08:51:44+00:00</td></tr>
<tr><th>SHA1</th><td>dd8d19f8cf2c2fd51e8f9b83bafc9981399c3cff</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/dd8d19f8cf2c2fd51e8f9b83bafc9981399c3cff/1.21-pre3.json">https://piston-meta.mojang.com/v1/packages/dd8d19f8cf2c2fd51e8f9b83bafc9981399c3cff/1.21-pre3.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/aa4e93019e435c7cb54e35229317132267e94a08/17.json">https://piston-meta.mojang.com/v1/packages/aa4e93019e435c7cb54e35229317132267e94a08/17.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/96266e18a95faa1c785ac852315e886d0e8bb174/server.jar">https://piston-data.mojang.com/v1/objects/96266e18a95faa1c785ac852315e886d0e8bb174/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/c9f12b8c90d831b78fcc94cb596e2afe5ccedfb5/server.txt">https://piston-data.mojang.com/v1/objects/c9f12b8c90d831b78fcc94cb596e2afe5ccedfb5/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/4fa198a594444754b3e329a2b2ca9e2ebb80ac82/client.jar">https://piston-data.mojang.com/v1/objects/4fa198a594444754b3e329a2b2ca9e2ebb80ac82/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/68ac68c38320cb5cddefd82f22fe953b44416a33/client.txt">https://piston-data.mojang.com/v1/objects/68ac68c38320cb5cddefd82f22fe953b44416a33/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21-pre2">1.21-pre2</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
- net.minecraft.world.item.enchantment.effects.ReplaceDisc
+ net.minecraft.world.item.enchantment.effects.ReplaceDisk
```

</details>


<details><summary>net.minecraft.gametest.framework.GameTestHelper</summary>

```diff
+ void assertEntityPosition(Entity,AABB,String)
```

</details>


<details><summary>net.minecraft.world.entity.Leashable</summary>

```diff
+ void elasticRangeLeashBehaviour(Entity,float)
+ void legacyElasticRangeLeashBehaviour(Entity,Entity,float)
```

</details>


<details><summary>net.minecraft.world.entity.ai.attributes.AttributeInstance</summary>

```diff
+ void addOrReplacePermanentModifier(AttributeModifier)
```

</details>


<details><summary>net.minecraft.world.entity.decoration.LeashFenceKnotEntity</summary>

```diff
+ boolean lambda$interact$0(Player,Leashable)
```

</details>


<details><summary>net.minecraft.world.entity.player.Player</summary>

```diff
+ boolean isIgnoringFallDamageFromCurrentImpulse()
```

</details>


<details><summary>net.minecraft.world.entity.vehicle.Boat</summary>

```diff
+ void elasticRangeLeashBehaviour(Entity,float)
```

</details>


### Server




<details><summary>net.minecraft.gametest.framework.GameTestHelper</summary>

```diff
+ void assertEntityPosition(Entity,AABB,String)
```

</details>


<details><summary>net.minecraft.world.entity.decoration.ItemFrame</summary>

```diff
- MapId getFramedMapId()
+ MapId getFramedMapId(ItemStack)
```

</details>


<details><summary>net.minecraft.world.entity.projectile.ThrownEnderpearl</summary>

```diff
+ void onInsideBlock(BlockState)
```

</details>


<details><summary>net.minecraft.world.item.LeadItem</summary>

```diff
- boolean lambda$bindPlayerMobs$0(Player,Entity)
+ boolean lambda$bindPlayerMobs$0(Player,Leashable)
+ boolean lambda$leashableInArea$1(Predicate,Entity)
+ List leashableInArea(Level,BlockPos,Predicate)
```

</details>


<details><summary>net.minecraft.world.item.TridentItem</summary>

```diff
+ boolean isTooDamagedToUse(ItemStack)
```

</details>


<details><summary>net.minecraft.world.level.saveddata.maps.MapItemSavedData</summary>

```diff
+ String getFrameKey(int)
```

</details>


# Registries

<details><summary>enchantment_entity_effect_type.txt</summary>

```diff
- minecraft:replace_disc
+ minecraft:replace_disk
```

</details>


<details><summary>enchantment_location_based_effect_type.txt</summary>

```diff
- minecraft:replace_disc
+ minecraft:replace_disk
```

</details>
