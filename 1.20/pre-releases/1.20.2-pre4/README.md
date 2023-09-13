<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.20.2-pre4 ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.20.2-pre4</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2023-09-13T15:06:51+00:00</td></tr>
<tr><th>SHA1</th><td>cbc05b36ba4bcb662a808912dffb06eba2dceb91</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/cbc05b36ba4bcb662a808912dffb06eba2dceb91/1.20.2-pre4.json">https://piston-meta.mojang.com/v1/packages/cbc05b36ba4bcb662a808912dffb06eba2dceb91/1.20.2-pre4.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/4ee9890576bdce4aff21e52d9e07949ceb9adba0/8.json">https://piston-meta.mojang.com/v1/packages/4ee9890576bdce4aff21e52d9e07949ceb9adba0/8.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/9f1b8f9918d5d8d59781886f33e5b7b2053d0486/server.jar">https://piston-data.mojang.com/v1/objects/9f1b8f9918d5d8d59781886f33e5b7b2053d0486/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/54d00b40a74232f6606f43828dfaddbebb27592a/server.txt">https://piston-data.mojang.com/v1/objects/54d00b40a74232f6606f43828dfaddbebb27592a/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/dd8a62739ca11bec02cb991797f636227315ae3d/client.jar">https://piston-data.mojang.com/v1/objects/dd8a62739ca11bec02cb991797f636227315ae3d/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/7fb796593419e447038193393aa700a83f6a7244/client.txt">https://piston-data.mojang.com/v1/objects/7fb796593419e447038193393aa700a83f6a7244/client.txt</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20.2-pre3">1.20.2-pre3</a>
## Mappings
### Client
<details><summary>net.minecraft.core.dispenser.BoatDispenseItemBehavior</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- ItemStack execute(BlockSource,ItemStack)
- void playSound(BlockSource)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior</summary>

```diff
+ ItemStack dispense(net.minecraft.core.dispenser.BlockSource,net.minecraft.world.item.ItemStack)
- ItemStack dispense(net.minecraft.core.BlockSource,net.minecraft.world.item.ItemStack)
+ ItemStack lambda$static$0(BlockSource,ItemStack)
+ Vec3 getEntityPokingOutOfBlockPos(BlockSource,EntityType,Direction)
- ItemStack lambda$static$0(BlockSource,ItemStack)
- void setEntityPokingOutOfBlock(BlockSource,Entity,Direction)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$10</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$12</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$14</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- ItemStack execute(BlockSource,ItemStack)
- void playSound(BlockSource)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$16</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$18</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$21</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$23</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$25</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$27</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.OptionalDispenseItemBehavior</summary>

```diff
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>

<details><summary>net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.tags.DamageTypeTags</summary>

```diff
+ TagKey ALWAYS_KILLS_ARMOR_STANDS
```

</details>

<details><summary>net.minecraft.world.item.ArmorItem$1</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.world.item.MinecartItem$1</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- ItemStack execute(BlockSource,ItemStack)
- void playSound(BlockSource)
```

</details>

<details><summary>Added and removed classes</summary>

```diff
- net.minecraft.core.BlockSourceImpl
+ net.minecraft.core.cauldron.CauldronInteraction
- net.minecraft.core.cauldron.package-info
+ net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
- net.minecraft.core.QuartPos
+ net.minecraft.core.Registry
- net.minecraft.core.Registry$1
+ net.minecraft.core.Registry$2
- net.minecraft.core.RegistryAccess
+ net.minecraft.core.RegistryAccess$1
- net.minecraft.core.RegistryAccess$1FrozenAccess
+ net.minecraft.core.RegistryAccess$Frozen
- net.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ net.minecraft.core.RegistryAccess$RegistryEntry
- net.minecraft.core.RegistryCodecs
+ net.minecraft.core.RegistryCodecs$RegistryEntry
- net.minecraft.core.RegistrySetBuilder
+ net.minecraft.core.RegistrySetBuilder$1
- net.minecraft.core.RegistrySetBuilder$BuildState
+ net.minecraft.core.RegistrySetBuilder$BuildState$1
- net.minecraft.core.RegistrySetBuilder$CompositeOwner
+ net.minecraft.core.RegistrySetBuilder$EmptyTagLookup
- net.minecraft.core.RegistrySetBuilder$RegisteredValue
+ net.minecraft.core.RegistrySetBuilder$RegistryBootstrap
- net.minecraft.core.RegistrySetBuilder$RegistryContents
+ net.minecraft.core.RegistrySetBuilder$RegistryContents$1
- net.minecraft.core.RegistrySetBuilder$RegistryStub
+ net.minecraft.core.RegistrySetBuilder$UniversalLookup
- net.minecraft.core.RegistrySetBuilder$ValueAndHolder
+ net.minecraft.core.RegistrySynchronization
- net.minecraft.core.RegistrySynchronization$NetworkedRegistryData
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.UUIDUtil
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
```

</details>

### Server
<details><summary>net.minecraft.core.dispenser.BoatDispenseItemBehavior</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- ItemStack execute(BlockSource,ItemStack)
- void playSound(BlockSource)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior</summary>

```diff
+ ItemStack dispense(net.minecraft.core.dispenser.BlockSource,net.minecraft.world.item.ItemStack)
- ItemStack dispense(net.minecraft.core.BlockSource,net.minecraft.world.item.ItemStack)
+ ItemStack lambda$static$0(BlockSource,ItemStack)
+ Vec3 getEntityPokingOutOfBlockPos(BlockSource,EntityType,Direction)
- ItemStack lambda$static$0(BlockSource,ItemStack)
- void setEntityPokingOutOfBlock(BlockSource,Entity,Direction)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$10</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$12</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$14</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- ItemStack execute(BlockSource,ItemStack)
- void playSound(BlockSource)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$16</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$18</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$21</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$23</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$25</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior$27</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.core.dispenser.OptionalDispenseItemBehavior</summary>

```diff
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>

<details><summary>net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.world.item.ArmorItem</summary>

```diff
+ boolean dispenseArmor(BlockSource,ItemStack)
- boolean dispenseArmor(BlockSource,ItemStack)
```

</details>

<details><summary>net.minecraft.world.level.block.DispenserBlock</summary>

```diff
+ Logger LOGGER
+ Position getDispensePosition(BlockSource)
+ void dispenseFrom(ServerLevel,BlockState,BlockPos)
- Position getDispensePosition(BlockSource)
- void dispenseFrom(ServerLevel,BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.block.DropperBlock</summary>

```diff
+ Logger LOGGER
+ void dispenseFrom(ServerLevel,BlockState,BlockPos)
- void dispenseFrom(ServerLevel,BlockPos)
```

</details>

<details><summary>Added and removed classes</summary>

```diff
- net.minecraft.core.BlockSourceImpl
+ net.minecraft.core.cauldron.CauldronInteraction
- net.minecraft.core.cauldron.package-info
+ net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
- net.minecraft.core.QuartPos
+ net.minecraft.core.Registry
- net.minecraft.core.Registry$1
+ net.minecraft.core.Registry$2
- net.minecraft.core.RegistryAccess
+ net.minecraft.core.RegistryAccess$1
- net.minecraft.core.RegistryAccess$1FrozenAccess
+ net.minecraft.core.RegistryAccess$Frozen
- net.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ net.minecraft.core.RegistryAccess$RegistryEntry
- net.minecraft.core.RegistryCodecs
+ net.minecraft.core.RegistryCodecs$RegistryEntry
- net.minecraft.core.RegistrySetBuilder
+ net.minecraft.core.RegistrySetBuilder$1
- net.minecraft.core.RegistrySetBuilder$BuildState
+ net.minecraft.core.RegistrySetBuilder$BuildState$1
- net.minecraft.core.RegistrySetBuilder$CompositeOwner
+ net.minecraft.core.RegistrySetBuilder$EmptyTagLookup
- net.minecraft.core.RegistrySetBuilder$RegisteredValue
+ net.minecraft.core.RegistrySetBuilder$RegistryBootstrap
- net.minecraft.core.RegistrySetBuilder$RegistryContents
+ net.minecraft.core.RegistrySetBuilder$RegistryContents$1
- net.minecraft.core.RegistrySetBuilder$RegistryStub
+ net.minecraft.core.RegistrySetBuilder$UniversalLookup
- net.minecraft.core.RegistrySetBuilder$ValueAndHolder
+ net.minecraft.core.RegistrySynchronization
- net.minecraft.core.RegistrySynchronization$NetworkedRegistryData
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.UUIDUtil
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
```

</details>

## File structure
<details><summary>data/</summary>

```diff
+  minecraft/tags/damage_type/always_kills_armor_stands.json
```

</details>

## Tags
<details><summary>list</summary>

```diff
+ damage_type/always_kills_armor_stands.json
```

</details>

## Misc
<details><summary>tags.txt</summary>

```diff
+ damage_type/always_kills_armor_stands.json
```

</details>

<br/>
<html><table>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
<a href="https://github.com/PixiGeko/Minecraft-generated-data">Minecraft-generated-data</a>
<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
</table></html>
<br/>