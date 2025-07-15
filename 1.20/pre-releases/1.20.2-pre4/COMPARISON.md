## Comparison with [1.20.2-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20.2-pre3)

> [!TIP]
> - [Version data](#version-data)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.20.2-pre3</th><th>1.20.2-pre4</th></tr><tr><td>World version</td><td><pre>3574</pre></td><td><pre>3575</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741974</pre></td><td><pre>1073741975</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/damage_type/always_kills_armor_stands.json
```

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
- XXX.core.cauldron.CauldronInteraction
+ XXX.core.cauldron.package-info
- XXX.core.dispenser.AbstractProjectileDispenseBehavior
+ XXX.minecraft.core.BlockSourceImpl
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Registry$1
- XXX.minecraft.core.Registry$2
+ XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.RegistryAccess$1
+ XXX.minecraft.core.RegistryAccess$1FrozenAccess
- XXX.minecraft.core.RegistryAccess$Frozen
+ XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryEntry
+ XXX.minecraft.core.RegistryCodecs
- XXX.minecraft.core.RegistryCodecs$RegistryEntry
+ XXX.minecraft.core.RegistrySetBuilder
- XXX.minecraft.core.RegistrySetBuilder$1
+ XXX.minecraft.core.RegistrySetBuilder$BuildState
- XXX.minecraft.core.RegistrySetBuilder$BuildState$1
+ XXX.minecraft.core.RegistrySetBuilder$CompositeOwner
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookup
+ XXX.minecraft.core.RegistrySetBuilder$RegisteredValue
- XXX.minecraft.core.RegistrySetBuilder$RegistryBootstrap
+ XXX.minecraft.core.RegistrySetBuilder$RegistryContents
- XXX.minecraft.core.RegistrySetBuilder$RegistryContents$1
+ XXX.minecraft.core.RegistrySetBuilder$RegistryStub
- XXX.minecraft.core.RegistrySetBuilder$UniversalLookup
+ XXX.minecraft.core.RegistrySetBuilder$ValueAndHolder
- XXX.minecraft.core.RegistrySynchronization
+ XXX.minecraft.core.RegistrySynchronization$NetworkedRegistryData
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.UUIDUtil
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.core.dispenser.BoatDispenseItemBehavior +2M -2M
```
```
XXX.core.dispenser.DispenseItemBehavior +2M -2M | +1P -1P
```
```
XXX.core.dispenser.DispenseItemBehavior$10 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$12 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$14 +2M -2M
```
```
XXX.core.dispenser.DispenseItemBehavior$16 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$18 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$21 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$23 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$25 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$27 +1M -1M
```
```
XXX.core.dispenser.OptionalDispenseItemBehavior +1M -1M
```
```
XXX.core.dispenser.ShulkerBoxDispenseBehavior +1M -1M
```
```
XXX.world.item.ArmorItem +1M -1M
```
```
XXX.level.block.DispenserBlock +2M -2M | +1P
```
```
XXX.level.block.DropperBlock +1M -1M | +1P
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.BoatDispenseItemBehavior
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior
</summary>

```diff
+ ItemStack lambda$static$0(BlockSource,ItemStack)
- ItemStack lambda$static$0(BlockSource,ItemStack)
- Vec3 getEntityPokingOutOfBlockPos(BlockSource,EntityType,Direction)
+ void setEntityPokingOutOfBlock(BlockSource,Entity,Direction)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$10
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$12
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$14
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$16
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$18
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$21
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$23
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$25
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$27
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.OptionalDispenseItemBehavior
</summary>

```diff
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorItem
</summary>

```diff
+ boolean dispenseArmor(BlockSource,ItemStack)
- boolean dispenseArmor(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ Position getDispensePosition(BlockSource)
- Position getDispensePosition(BlockSource)
+ void dispenseFrom(ServerLevel,BlockPos)
- void dispenseFrom(ServerLevel,BlockState,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DropperBlock
</summary>

```diff
+ void dispenseFrom(ServerLevel,BlockPos)
- void dispenseFrom(ServerLevel,BlockState,BlockPos)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.core.cauldron.CauldronInteraction
+ XXX.core.cauldron.package-info
- XXX.core.dispenser.AbstractProjectileDispenseBehavior
+ XXX.minecraft.core.BlockSourceImpl
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Registry$1
- XXX.minecraft.core.Registry$2
+ XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.RegistryAccess$1
+ XXX.minecraft.core.RegistryAccess$1FrozenAccess
- XXX.minecraft.core.RegistryAccess$Frozen
+ XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryEntry
+ XXX.minecraft.core.RegistryCodecs
- XXX.minecraft.core.RegistryCodecs$RegistryEntry
+ XXX.minecraft.core.RegistrySetBuilder
- XXX.minecraft.core.RegistrySetBuilder$1
+ XXX.minecraft.core.RegistrySetBuilder$BuildState
- XXX.minecraft.core.RegistrySetBuilder$BuildState$1
+ XXX.minecraft.core.RegistrySetBuilder$CompositeOwner
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookup
+ XXX.minecraft.core.RegistrySetBuilder$RegisteredValue
- XXX.minecraft.core.RegistrySetBuilder$RegistryBootstrap
+ XXX.minecraft.core.RegistrySetBuilder$RegistryContents
- XXX.minecraft.core.RegistrySetBuilder$RegistryContents$1
+ XXX.minecraft.core.RegistrySetBuilder$RegistryStub
- XXX.minecraft.core.RegistrySetBuilder$UniversalLookup
+ XXX.minecraft.core.RegistrySetBuilder$ValueAndHolder
- XXX.minecraft.core.RegistrySynchronization
+ XXX.minecraft.core.RegistrySynchronization$NetworkedRegistryData
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.UUIDUtil
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.core.dispenser.BoatDispenseItemBehavior +2M -2M
```
```
XXX.core.dispenser.DispenseItemBehavior +2M -2M | +1P -1P
```
```
XXX.core.dispenser.DispenseItemBehavior$10 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$12 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$14 +2M -2M
```
```
XXX.core.dispenser.DispenseItemBehavior$16 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$18 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$21 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$23 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$25 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$27 +1M -1M
```
```
XXX.core.dispenser.OptionalDispenseItemBehavior +1M -1M
```
```
XXX.core.dispenser.ShulkerBoxDispenseBehavior +1M -1M
```
```
XXX.minecraft.tags.DamageTypeTags +1P
```
```
XXX.world.item.ArmorItem$1 +1M -1M
```
```
XXX.world.item.MinecartItem$1 +2M -2M
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.BoatDispenseItemBehavior
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior
</summary>

```diff
+ ItemStack lambda$static$0(BlockSource,ItemStack)
- ItemStack lambda$static$0(BlockSource,ItemStack)
- Vec3 getEntityPokingOutOfBlockPos(BlockSource,EntityType,Direction)
+ void setEntityPokingOutOfBlock(BlockSource,Entity,Direction)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$10
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$12
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$14
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$16
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$18
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$21
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$23
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$25
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$27
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.OptionalDispenseItemBehavior
</summary>

```diff
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorItem$1
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.MinecartItem$1
</summary>

```diff
+ ItemStack execute(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
+ void playSound(BlockSource)
- void playSound(BlockSource)
```

</details>
</details>
<hr/>