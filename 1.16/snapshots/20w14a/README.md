<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 20w14a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>20w14a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2020-04-02T14:28:06+00:00</td></tr>
<tr><th>SHA1</th><td>1e548dbfeb7cb9aa76888b7308112c1a03cf0cc0</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/1e548dbfeb7cb9aa76888b7308112c1a03cf0cc0/20w14a.json">https://piston-meta.mojang.com/v1/packages/1e548dbfeb7cb9aa76888b7308112c1a03cf0cc0/20w14a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json">https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/affcf966ca903156070aa90b63417793a78b2165/server.jar">https://piston-data.mojang.com/v1/objects/affcf966ca903156070aa90b63417793a78b2165/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/1b2c98f855ef0f690e9d499d363fe5ee5969de62/server.txt">https://piston-data.mojang.com/v1/objects/1b2c98f855ef0f690e9d499d363fe5ee5969de62/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/cb36abdee528372522f52ae41ccc0609fd9c4038/client.jar">https://piston-data.mojang.com/v1/objects/cb36abdee528372522f52ae41ccc0609fd9c4038/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/6316a9aa6af559b8f2c8760ebd2c55cf3d34277a/client.txt">https://piston-data.mojang.com/v1/objects/6316a9aa6af559b8f2c8760ebd2c55cf3d34277a/client.txt</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/20w13b">20w13b</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/loot_tables/entities/zoglin.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/models/item/zoglin_spawn_egg.json
+  minecraft/textures/entity/hoglin/zoglin.png
```

</details>

<details><summary>minecraft-generated/</summary>

```diff
+  tmp/world
```

</details>

## Registries

<details><summary>list</summary>

```diff
+ attributes.txt
+ trunk_placer_type.txt
```

</details>

<details><summary>entity_type.txt</summary>

```diff
+ minecraft:zoglin
```

</details>

<details><summary>feature.txt</summary>

```diff
- minecraft:acacia_tree
```

</details>

<details><summary>item.txt</summary>

```diff
+ minecraft:zoglin_spawn_egg
```

</details>

<details><summary>memory_module_type.txt</summary>

```diff
- minecraft:nearest_visible_adult_hoglin
- minecraft:nearest_visible_zombified_piglin
+ minecraft:nearest_visible_huntable_hoglin
+ minecraft:nearest_visible_zombified
```

</details>

<details><summary>sound_event.txt</summary>

```diff
+ minecraft:entity.hoglin.converted_to_zombified
+ minecraft:entity.zoglin.ambient
+ minecraft:entity.zoglin.angry
+ minecraft:entity.zoglin.attack
+ minecraft:entity.zoglin.death
+ minecraft:entity.zoglin.hurt
+ minecraft:entity.zoglin.step
```

</details>

## Tags

<details><summary>blocks/hoglin_repellents.json</summary>

```diff
+ minecraft:nether_portal
+ minecraft:respawn_anchor
```

</details>

## Misc

<details><summary>loot_tables.txt</summary>

```diff
+ entities/zoglin.json
```

</details>

<details><summary>textures.txt</summary>

```diff
+ entity/hoglin/zoglin.png
```

</details>

## Mappings



























































































































































































<details><summary>net.minecraft.advancements.critereon.FishingRodHookedTrigger</summary>

```diff
+ boolean lambda$trigger$0(FishingRodHookedTrigger$TriggerInstance)
+ void trigger(Collection)
- boolean lambda$trigger$0(FishingRodHookedTrigger$TriggerInstance)
- void trigger(Collection)
```

</details>
















































<details><summary>net.minecraft.client.Minecraft</summary>

```diff
+ boolean shouldEntityAppearGlowing(Entity)
```

</details>













































<details><summary>net.minecraft.client.gui.components.toasts.SystemToast</summary>

```diff
+ void add(Component)
+ void onWorldAccessFailure(String)
+ void onWorldDeleteFailure(String)
```

</details>













































<details><summary>net.minecraft.client.gui.screens.TitleScreen</summary>

```diff
+ Logger LOGGER
```

</details>




































































<details><summary>net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen</summary>

```diff
+ OptimizeWorldScreen create(LevelStorageSource$LevelStorageAccess,boolean)
+ void <init>(LevelData,boolean)
+ void onClose()
- void <init>(LevelStorageSource,boolean)
```

</details>



































































































































































































































































<details><summary>net.minecraft.client.renderer.debug.CollisionBoxRenderer</summary>

```diff
+ boolean lambda$render$0(Entity)
```

</details>



























































































<details><summary>net.minecraft.client.server.IntegratedServer</summary>

```diff
+ void <init>(ChunkProgressListenerFactory)
+ void loadLevel(ChunkGeneratorProvider)
- void <init>(ChunkProgressListenerFactory)
- void loadLevel(ChunkGeneratorProvider)
```

</details>





























































<details><summary>net.minecraft.commands.arguments.item.FunctionArgument</summary>

```diff
+ Pair getFunctionOrTag(String)
- Either getFunctionOrTag(String)
```

</details>

<details><summary>net.minecraft.commands.arguments.item.FunctionArgument$2</summary>

```diff
+ Pair unwrap(CommandContext)
- Either unwrap(CommandContext)
```

</details>










































<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior</summary>

```diff
+ void setEntityPokingOutOfBlock(Direction)
```

</details>






















































<details><summary>net.minecraft.data.models.model.TextureSlot</summary>

```diff
- TextureSlot[] $VALUES
+ String toString()
+ TextureSlot create(String)
+ TextureSlot create(TextureSlot)
+ void <init>(TextureSlot)
- TextureSlot valueOf(String)
- TextureSlot[] values()
- void <init>(String)
- void <init>(TextureSlot)
```

</details>













<details><summary>net.minecraft.data.tags.EntityTypeTagsProvider</summary>

```diff
- void useTags(TagCollection)
```

</details>

<details><summary>net.minecraft.data.tags.ItemTagsProvider</summary>

```diff
+ Function blockTags
- Logger LOGGER
+ void <init>(BlockTagsProvider)
+ void copy(Tag$Named)
- Tag$Entry copy(Tag$Entry)
- void <clinit>()
- void <init>(DataGenerator)
- void copy(Tag)
- void useTags(TagCollection)
```

</details>










<details><summary>net.minecraft.gametest.framework.GameTestServer</summary>

```diff
+ void <init>(BlockPos)
- void <init>(BlockPos)
```

</details>

















































































































































































































































<details><summary>net.minecraft.server.dedicated.DedicatedServer</summary>

```diff
+ boolean forceSynchronousWrites()
+ String getLevelIdName()
+ void <init>(ChunkProgressListenerFactory)
- void <init>(String)
```

</details>





























<details><summary>net.minecraft.server.level.WorldGenRegion</summary>

```diff
+ ChunkPos firstPos
+ ChunkPos lastPos
```

</details>





















































<details><summary>net.minecraft.sounds.SoundEvents</summary>

```diff
+ SoundEvent HOGLIN_CONVERTED_TO_ZOMBIFIED
+ SoundEvent ZOGLIN_AMBIENT
+ SoundEvent ZOGLIN_ANGRY
+ SoundEvent ZOGLIN_ATTACK
+ SoundEvent ZOGLIN_DEATH
+ SoundEvent ZOGLIN_HURT
+ SoundEvent ZOGLIN_STEP
```

</details>






<details><summary>net.minecraft.tags.BlockTags</summary>

```diff
+ StaticTagHelper HELPER
+ Tag$Named ACACIA_LOGS
+ Tag$Named ANVIL
+ Tag$Named BAMBOO_PLANTABLE_ON
+ Tag$Named BANNERS
+ Tag$Named BEACON_BASE_BLOCKS
+ Tag$Named BEDS
+ Tag$Named BEE_GROWABLES
+ Tag$Named BEEHIVES
+ Tag$Named BIRCH_LOGS
+ Tag$Named BUTTONS
+ Tag$Named CARPETS
+ Tag$Named CLIMBABLE
+ Tag$Named CORAL_BLOCKS
+ Tag$Named CORAL_PLANTS
+ Tag$Named CORALS
+ Tag$Named CRIMSON_STEMS
+ Tag$Named CROPS
+ Tag$Named DARK_OAK_LOGS
+ Tag$Named DOORS
+ Tag$Named DRAGON_IMMUNE
+ Tag$Named ENDERMAN_HOLDABLE
+ Tag$Named FENCES
+ Tag$Named FIRE
+ Tag$Named FLOWER_POTS
+ Tag$Named FLOWERS
+ Tag$Named GOLD_ORES
+ Tag$Named HOGLIN_REPELLENTS
+ Tag$Named ICE
+ Tag$Named IMPERMEABLE
+ Tag$Named JUNGLE_LOGS
+ Tag$Named LEAVES
+ Tag$Named LOGS
+ Tag$Named LOGS_THAT_BURN
+ Tag$Named NON_FLAMMABLE_WOOD
+ Tag$Named NYLIUM
+ Tag$Named OAK_LOGS
+ Tag$Named PIGLIN_REPELLENTS
+ Tag$Named PLANKS
+ Tag$Named PORTALS
+ Tag$Named RAILS
+ Tag$Named SAND
+ Tag$Named SAPLINGS
+ Tag$Named SHULKER_BOXES
+ Tag$Named SIGNS
+ Tag$Named SLABS
+ Tag$Named SMALL_FLOWERS
+ Tag$Named SOUL_FIRE_BASE_BLOCKS
+ Tag$Named SOUL_SPEED_BLOCKS
+ Tag$Named SPRUCE_LOGS
+ Tag$Named STAIRS
+ Tag$Named STANDING_SIGNS
+ Tag$Named STONE_BRICKS
+ Tag$Named STRIDER_WARM_BLOCKS
+ Tag$Named TALL_FLOWERS
+ Tag$Named TRAPDOORS
+ Tag$Named UNDERWATER_BONEMEALS
+ Tag$Named VALID_SPAWN
+ Tag$Named WALL_CORALS
+ Tag$Named WALL_POST_OVERRIDE
+ Tag$Named WALL_SIGNS
+ Tag$Named WALLS
+ Tag$Named WARPED_STEMS
+ Tag$Named WART_BLOCKS
+ Tag$Named WITHER_IMMUNE
+ Tag$Named WITHER_SUMMON_BASE_BLOCKS
+ Tag$Named WOODEN_BUTTONS
+ Tag$Named WOODEN_DOORS
+ Tag$Named WOODEN_FENCES
+ Tag$Named WOODEN_PRESSURE_PLATES
+ Tag$Named WOODEN_SLABS
+ Tag$Named WOODEN_STAIRS
+ Tag$Named WOODEN_TRAPDOORS
+ Tag$Named WOOL
- int resetCount
- Tag ACACIA_LOGS
- Tag ANVIL
- Tag BAMBOO_PLANTABLE_ON
- Tag BANNERS
- Tag BEACON_BASE_BLOCKS
- Tag BEDS
- Tag BEE_GROWABLES
- Tag BEEHIVES
- Tag BIRCH_LOGS
- Tag BUTTONS
- Tag CARPETS
- Tag CLIMBABLE
- Tag CORAL_BLOCKS
- Tag CORAL_PLANTS
- Tag CORALS
- Tag CRIMSON_STEMS
- Tag CROPS
- Tag DARK_OAK_LOGS
- Tag DOORS
- Tag DRAGON_IMMUNE
- Tag ENDERMAN_HOLDABLE
- Tag FENCES
- Tag FIRE
- Tag FLOWER_POTS
- Tag FLOWERS
- Tag GOLD_ORES
- Tag HOGLIN_REPELLENTS
- Tag ICE
- Tag IMPERMEABLE
- Tag JUNGLE_LOGS
- Tag LEAVES
- Tag LOGS
- Tag LOGS_THAT_BURN
- Tag NON_FLAMMABLE_WOOD
- Tag NYLIUM
- Tag OAK_LOGS
- Tag PIGLIN_REPELLENTS
- Tag PLANKS
- Tag PORTALS
- Tag RAILS
- Tag SAND
- Tag SAPLINGS
- Tag SHULKER_BOXES
- Tag SIGNS
- Tag SLABS
- Tag SMALL_FLOWERS
- Tag SOUL_FIRE_BASE_BLOCKS
- Tag SOUL_SPEED_BLOCKS
- Tag SPRUCE_LOGS
- Tag STAIRS
- Tag STANDING_SIGNS
- Tag STONE_BRICKS
- Tag STRIDER_WARM_BLOCKS
- Tag TALL_FLOWERS
- Tag TRAPDOORS
- Tag UNDERWATER_BONEMEALS
- Tag VALID_SPAWN
- Tag WALL_CORALS
- Tag WALL_POST_OVERRIDE
- Tag WALL_SIGNS
- Tag WALLS
- Tag WARPED_STEMS
- Tag WART_BLOCKS
- Tag WITHER_IMMUNE
- Tag WITHER_SUMMON_BASE_BLOCKS
- Tag WOODEN_BUTTONS
- Tag WOODEN_DOORS
- Tag WOODEN_FENCES
- Tag WOODEN_PRESSURE_PLATES
- Tag WOODEN_SLABS
- Tag WOODEN_STAIRS
- Tag WOODEN_TRAPDOORS
- Tag WOOL
- TagCollection source
+ Tag$Named bind(String)
- int access$000()
- Optional lambda$static$0(ResourceLocation)
- Tag bind(String)
- TagCollection access$100()
```

</details>

<details><summary>net.minecraft.tags.FluidTags</summary>

```diff
+ StaticTagHelper HELPER
+ Tag$Named LAVA
+ Tag$Named WATER
- int resetCount
- Tag LAVA
- Tag WATER
- TagCollection source
+ Tag$Named bind(String)
- int access$000()
- Optional lambda$static$0(ResourceLocation)
- Tag bind(String)
- TagCollection access$100()
```

</details>

<details><summary>net.minecraft.tags.Tag$Builder</summary>

```diff
+ Set entries
- boolean ordered
- Set values
+ boolean lambda$getUnresolvedEntries$1(Tag$Entry)
+ JsonObject serializeToJson()
+ Optional build(Function)
+ Stream getEntries()
+ Stream getUnresolvedEntries(Function)
+ Tag$Builder addElement(ResourceLocation)
+ Tag$Builder addFromJson(JsonObject)
+ void lambda$null$0(Object)
- boolean canBuild(Function)
- JsonParseException lambda$addFromJson$0(ResourceLocation)
- Tag build(ResourceLocation)
- Tag$Builder add(Collection)
- Tag$Builder add(Object)
- Tag$Builder add(Object[])
- Tag$Builder addFromJson(JsonObject)
- Tag$Builder addTag(Tag)
- Tag$Builder keepOrder(boolean)
```

</details>

<details><summary>net.minecraft.tags.Tag$TagEntry</summary>

```diff
- Tag tag
+ boolean build(Consumer)
+ String toString()
+ void serializeTo(JsonArray)
- boolean canBuild(Function)
- ResourceLocation getId()
- void <init>(Tag)
- void build(Collection)
- void serializeTo(Function)
```

</details>

<details><summary>net.minecraft.tags.TagCollection</summary>

```diff
+ BiMap tags
+ Tag empty
- boolean ordered
- Map tags
+ Map lambda$prepare$2(ResourceManager)
+ Object lambda$load$3(ResourceLocation)
+ ResourceLocation getId(Tag)
+ ResourceLocation getId(Tag$Named)
+ ResourceLocation getIdOrThrow(Tag)
+ Tag$Builder lambda$null$1(ResourceLocation)
+ void <init>(String)
+ void lambda$load$4(Tag$Builder)
- Map lambda$prepare$3(ResourceManager)
- Tag$Builder lambda$null$2(ResourceLocation)
- void <init>(String)
- void lambda$load$4(Tag$Builder)
- void lambda$load$5(Tag$Builder)
- void lambda$null$1(Tag$Builder)
```

</details>






<details><summary>net.minecraft.util.Mth</summary>

```diff
+ double inverseLerp(double,double,double)
- double pct(double,double,double)
```

</details>


























































































<details><summary>net.minecraft.world.entity.ai.attributes.AttributeModifier</summary>

```diff
+ Logger LOGGER
- boolean serialize
+ AttributeModifier load(CompoundTag)
+ CompoundTag save()
+ void <clinit>()
- AttributeModifier setSerialize(boolean)
- boolean isSerializable()
```

</details>

<details><summary>net.minecraft.world.entity.ai.attributes.RangedAttribute</summary>

```diff
- String importLegacyName
+ void <init>(String,double,double,double)
- RangedAttribute importLegacyName(String)
- String getImportLegacyName()
- void <init>(String,double,double,double)
```

</details>


















<details><summary>net.minecraft.world.entity.ai.behavior.LookAtTargetSink</summary>

```diff
+ boolean lambda$canStillUse$0(PositionTracker)
+ void lambda$tick$1(PositionTracker)
- boolean lambda$canStillUse$0(PositionWrapper)
- void lambda$tick$1(PositionWrapper)
```

</details>







































































<details><summary>net.minecraft.world.entity.ai.memory.MemoryModuleType</summary>

```diff
+ MemoryModuleType NEAREST_VISIBLE_HUNTABLE_HOGLIN
+ MemoryModuleType NEAREST_VISIBLE_ZOMBIFIED
- MemoryModuleType NEAREST_VISIBLE_ADULT_HOGLIN
- MemoryModuleType NEAREST_VISIBLE_ZOMBIFIED_PIGLIN
```

</details>

<details><summary>net.minecraft.world.entity.ai.memory.WalkTarget</summary>

```diff
+ PositionTracker target
- PositionWrapper target
+ PositionTracker getTarget()
+ void <init>(PositionTracker,float,int)
- PositionWrapper getTarget()
- void <init>(PositionWrapper,float,int)
```

</details>


<details><summary>net.minecraft.world.entity.ai.navigation.PathNavigation</summary>

```diff
- AttributeInstance followRange
```

</details>
























<details><summary>net.minecraft.world.entity.animal.Bee</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>







<details><summary>net.minecraft.world.entity.animal.Cat</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.animal.Chicken</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>

<details><summary>net.minecraft.world.entity.animal.Cow</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>




<details><summary>net.minecraft.world.entity.animal.Fox</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>












<details><summary>net.minecraft.world.entity.animal.IronGolem</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.animal.Ocelot</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>








<details><summary>net.minecraft.world.entity.animal.Parrot</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>

<details><summary>net.minecraft.world.entity.animal.Pig</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>




<details><summary>net.minecraft.world.entity.animal.Rabbit</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>







<details><summary>net.minecraft.world.entity.animal.Squid</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>




<details><summary>net.minecraft.world.entity.animal.Turtle</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>








<details><summary>net.minecraft.world.entity.animal.horse.AbstractHorse</summary>

```diff
- Attribute JUMP_STRENGTH
+ AttributeSupplier$Builder createBaseHorseAttributes()
+ void randomizeAttributes()
- boolean hurt(DamageSource,float)
- void registerAttributes()
```

</details>

<details><summary>net.minecraft.world.entity.animal.horse.Horse</summary>

```diff
+ void randomizeAttributes()
- void registerAttributes()
```

</details>

<details><summary>net.minecraft.world.entity.animal.horse.Llama</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>



<details><summary>net.minecraft.world.entity.animal.horse.SkeletonHorse</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
+ void randomizeAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.animal.horse.ZombieHorse</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
+ void randomizeAttributes()
- void registerAttributes()
```

</details>



<details><summary>net.minecraft.world.entity.boss.enderdragon.EnderDragon</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>










<details><summary>net.minecraft.world.entity.boss.wither.WitherBoss</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>










<details><summary>net.minecraft.world.entity.monster.Silverfish</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.monster.Slime</summary>

```diff
- void registerAttributes()
```

</details>





<details><summary>net.minecraft.world.entity.monster.Spider</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>







<details><summary>net.minecraft.world.entity.monster.Vindicator</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.monster.Witch</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>

























<details><summary>net.minecraft.world.entity.projectile.AbstractArrow</summary>

```diff
- int flightTime
+ boolean canHitEntity(Entity)
- boolean lambda$findHitEntity$0(Entity)
```

</details>

<details><summary>net.minecraft.world.entity.projectile.AbstractHurtingProjectile</summary>

```diff
- int flightTime
+ boolean canHitEntity(Entity)
```

</details>



<details><summary>net.minecraft.world.entity.projectile.FireworkRocketEntity</summary>

```diff
- boolean lambda$tick$1(Entity)
```

</details>


<details><summary>net.minecraft.world.entity.projectile.Projectile</summary>

```diff
+ boolean leftOwner
+ int ownerNetworkId
+ boolean canHitEntity(Entity)
+ boolean checkLeftOwner()
+ boolean lambda$checkLeftOwner$0(Entity)
+ float lerpRotation(float,float)
+ void tick()
+ void updateRotation()
```

</details>

<details><summary>net.minecraft.world.entity.projectile.ShulkerBullet</summary>

```diff
+ boolean canHitEntity(Entity)
```

</details>







































































<details><summary>net.minecraft.world.item.ArmorItem</summary>

```diff
+ Multimap defaultModifiers
```

</details>




















<details><summary>net.minecraft.world.item.DiggerItem</summary>

```diff
+ Multimap defaultModifiers
- float attackSpeedBaseline
```

</details>




















<details><summary>net.minecraft.world.item.ItemStack</summary>

```diff
+ Component lambda$expandBlockState$2(Component)
+ void addAttributeModifier(EquipmentSlot)
+ void lambda$appendEnchantmentNames$1(Enchantment)
+ void lambda$static$0(DecimalFormat)
- Component lambda$expandBlockState$1(Component)
- DecimalFormat getAttributeDecimalFormat()
- void addAttributeModifier(EquipmentSlot)
- void lambda$appendEnchantmentNames$0(Enchantment)
- void lambda$getAttributeModifiers$2(AttributeModifier)
```

</details>































<details><summary>net.minecraft.world.item.crafting.Ingredient</summary>

```diff
- Predicate NON_ALL_EMPTY
+ boolean lambda$of$3(ItemStack)
+ Ingredient of(Stream)
+ Ingredient$ItemValue lambda$fromNetwork$5(FriendlyByteBuf)
+ Ingredient$ItemValue lambda$of$4(ItemStack)
+ Ingredient$Value lambda$fromJson$6(JsonElement)
+ Ingredient$Value[] lambda$new$0(int)
+ ItemStack[] lambda$dissolve$2(int)
+ JsonSyntaxException lambda$valueFromJson$7(ResourceLocation)
+ Stream lambda$dissolve$1(Ingredient$Value)
- boolean lambda$static$0(Ingredient$Value)
- Ingredient$ItemValue lambda$fromNetwork$6(FriendlyByteBuf)
- Ingredient$ItemValue lambda$of$4(ItemLike)
- Ingredient$ItemValue lambda$of$5(ItemStack)
- Ingredient$Value lambda$fromJson$7(JsonElement)
- Ingredient$Value[] lambda$new$1(int)
- ItemStack[] lambda$dissolve$3(int)
- JsonSyntaxException lambda$valueFromJson$8(ResourceLocation)
- Stream lambda$dissolve$2(Ingredient$Value)
```

</details>





















<details><summary>net.minecraft.world.item.enchantment.EnchantmentCategory</summary>

```diff
+ EnchantmentCategory VANISHABLE
- EnchantmentCategory ALL
```

</details>



<details><summary>net.minecraft.world.item.enchantment.EnchantmentCategory$14</summary>

```diff
+ boolean lambda$canEnchant$0(EnchantmentCategory)
+ boolean lambda$canEnchant$1(EnchantmentCategory)
```

</details>







































<details><summary>net.minecraft.world.level.LevelAccessor</summary>

```diff
+ Stream getEntityCollisions(Predicate)
- Stream getEntityCollisions(Set)
```

</details>








































































<details><summary>net.minecraft.world.level.block.BeehiveBlock</summary>

```diff
+ Direction getRandomOffset(Random)
```

</details>




























































































































































<details><summary>net.minecraft.world.level.block.grower.AbstractMegaTreeGrower</summary>

```diff
+ boolean growTree(Random)
+ boolean placeMega(Random,int,int)
- boolean growTree(Random)
- boolean placeMega(Random,int,int)
```

</details>











































<details><summary>net.minecraft.world.level.chunk.ChunkGenerator</summary>

```diff
+ void fillFromNoise(net.minecraft.world.level.LevelAccessor,net.minecraft.world.level.StructureFeatureManager,net.minecraft.world.level.chunk.ChunkAccess)
- void fillFromNoise(net.minecraft.world.level.LevelAccessor,net.minecraft.world.level.chunk.ChunkAccess)
+ BlockPos findNearestMapFeature(BlockPos,int,boolean)
+ List getMobsAt(BlockPos)
+ void applyBiomeDecoration(StructureFeatureManager)
+ void createReferences(ChunkAccess)
+ void createStructures(StructureManager)
- BlockPos findNearestMapFeature(BlockPos,int,boolean)
- List getMobsAt(BlockPos)
- void applyBiomeDecoration(WorldGenRegion)
- void createReferences(ChunkAccess)
- void createStructures(StructureManager)
```

</details>



















<details><summary>net.minecraft.world.level.chunk.storage.ChunkStorage</summary>

```diff
+ void <init>(DataFixer,boolean)
- void <init>(DataFixer)
```

</details>





<details><summary>net.minecraft.world.level.chunk.storage.RegionFileStorage</summary>

```diff
+ boolean sync
+ void <init>(File,boolean)
+ void flush()
- void <init>(File)
```

</details>












<details><summary>net.minecraft.world.level.levelgen.FlatLevelSource</summary>

```diff
+ BlockPos findNearestMapFeature(BlockPos,int,boolean)
+ void fillFromNoise(ChunkAccess)
- BlockPos findNearestMapFeature(BlockPos,int,boolean)
- void fillFromNoise(ChunkAccess)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator</summary>

```diff
+ void fillFromNoise(ChunkAccess)
+ void lambda$fillFromNoise$1(StructureStart)
- void fillFromNoise(ChunkAccess)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.OverworldLevelSource</summary>

```diff
+ List getMobsAt(BlockPos)
- List getMobsAt(BlockPos)
```

</details>








<details><summary>net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature</summary>

```diff
+ boolean place(FeatureConfiguration)
- boolean place(FeatureConfiguration)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.AbstractSmallTreeFeature</summary>

```diff
+ Optional getProjectedOrigin(SmallTreeConfiguration)
- Optional getProjectedOrigin(SmallTreeConfiguration)
- void placeTrunk(SmallTreeConfiguration)
```

</details>







<details><summary>net.minecraft.world.level.levelgen.placement.ConfiguredDecorator</summary>

```diff
+ boolean place(ConfiguredFeature)
- boolean place(ConfiguredFeature)
```

</details>
























<details><summary>net.minecraft.world.level.levelgen.structure.DesertPyramidPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.structure.JunglePyramidPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>









<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.structure.StructureStart</summary>

```diff
+ void postProcess(ChunkPos)
- void postProcess(ChunkPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.SwamplandHutPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>
































































































<details><summary>net.minecraft.world.level.storage.McRegionUpgrader</summary>

```diff
+ boolean convertLevel(ProgressListener)
+ void makeMcrLevelDatBackup(File)
- boolean convertLevel(ProgressListener)
- void makeMcrLevelDatBackup(String)
```

</details>


































































<details><summary>net.minecraft.world.level.storage.loot.functions.SetAttributesFunction</summary>

```diff
+ SetAttributesFunction$ModifierBuilder modifier(RandomValueBounds)
- SetAttributesFunction$ModifierBuilder modifier(RandomValueBounds)
```

</details>


<details><summary>net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder</summary>

```diff
+ Attribute attribute
- String attribute
+ void <init>(RandomValueBounds)
- void <init>(RandomValueBounds)
```

</details>















































































<details><summary>Added and removed classes</summary>

```diff
+ net.minecraft.client.renderer.debug.HeightMapRenderer$1
- net.minecraft.client.renderer.debug.LightDebugRenderer
+ net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
+ net.minecraft.client.renderer.debug.package-info
- net.minecraft.client.renderer.debug.PathfindingRenderer
+ net.minecraft.client.renderer.debug.RaidDebugRenderer
- net.minecraft.client.renderer.debug.SolidFaceRenderer
+ net.minecraft.client.renderer.debug.StructureRenderer
- net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
+ net.minecraft.client.renderer.debug.WaterDebugRenderer
- net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
- net.minecraft.client.renderer.entity.AbstractHorseRenderer
+ net.minecraft.client.renderer.entity.AbstractZombieRenderer
- net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
+ net.minecraft.client.renderer.entity.ArmorStandRenderer
- net.minecraft.client.renderer.entity.ArrowRenderer
+ net.minecraft.client.renderer.entity.BatRenderer
- net.minecraft.client.renderer.entity.BeeRenderer
+ net.minecraft.client.renderer.entity.BlazeRenderer
- net.minecraft.client.renderer.entity.BoatRenderer
+ net.minecraft.client.renderer.entity.CatRenderer
- net.minecraft.client.renderer.entity.CaveSpiderRenderer
+ net.minecraft.client.renderer.entity.ChestedHorseRenderer
- net.minecraft.client.renderer.entity.ChickenRenderer
+ net.minecraft.client.renderer.entity.CodRenderer
- net.minecraft.client.renderer.entity.CowRenderer
+ net.minecraft.client.renderer.entity.CreeperRenderer
- net.minecraft.client.renderer.entity.DolphinRenderer
+ net.minecraft.client.renderer.entity.DragonFireballRenderer
- net.minecraft.client.renderer.entity.DrownedRenderer
+ net.minecraft.client.renderer.entity.ElderGuardianRenderer
- net.minecraft.client.renderer.entity.EndCrystalRenderer
+ net.minecraft.client.renderer.entity.EnderDragonRenderer
- net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
+ net.minecraft.client.renderer.entity.EndermanRenderer
- net.minecraft.client.renderer.entity.EndermiteRenderer
+ net.minecraft.client.renderer.entity.EntityRenderDispatcher
- net.minecraft.client.renderer.entity.EntityRenderer
+ net.minecraft.client.renderer.entity.EvokerFangsRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer$1
- net.minecraft.client.renderer.entity.ExperienceOrbRenderer
+ net.minecraft.client.renderer.entity.FallingBlockRenderer
- net.minecraft.client.renderer.entity.FireworkEntityRenderer
+ net.minecraft.client.renderer.entity.FishingHookRenderer
- net.minecraft.client.renderer.entity.FoxRenderer
+ net.minecraft.client.renderer.entity.GhastRenderer
- net.minecraft.client.renderer.entity.GiantMobRenderer
+ net.minecraft.client.renderer.entity.GuardianRenderer
- net.minecraft.client.renderer.entity.HoglinRenderer
+ net.minecraft.client.renderer.entity.HorseRenderer
- net.minecraft.client.renderer.entity.HumanoidMobRenderer
+ net.minecraft.client.renderer.entity.HuskRenderer
- net.minecraft.client.renderer.entity.IllagerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer$1
+ net.minecraft.client.renderer.entity.IronGolemRenderer
- net.minecraft.client.renderer.entity.ItemEntityRenderer
+ net.minecraft.client.renderer.entity.ItemFrameRenderer
- net.minecraft.client.renderer.entity.ItemRenderer
+ net.minecraft.client.renderer.entity.LeashKnotRenderer
- net.minecraft.client.renderer.entity.LightningBoltRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer$1
+ net.minecraft.client.renderer.entity.LlamaRenderer
- net.minecraft.client.renderer.entity.LlamaSpitRenderer
+ net.minecraft.client.renderer.entity.MagmaCubeRenderer
- net.minecraft.client.renderer.entity.MinecartRenderer
+ net.minecraft.client.renderer.entity.MobRenderer
- net.minecraft.client.renderer.entity.MushroomCowRenderer
+ net.minecraft.client.renderer.entity.OcelotRenderer
- net.minecraft.client.renderer.entity.PaintingRenderer
+ net.minecraft.client.renderer.entity.PandaRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer
+ net.minecraft.client.renderer.entity.PhantomRenderer
+ net.minecraft.client.renderer.entity.PiglinRenderer
- net.minecraft.client.renderer.entity.PigRenderer
- net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.PolarBearRenderer
- net.minecraft.client.renderer.entity.PufferfishRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer
- net.minecraft.client.renderer.entity.RavagerRenderer
+ net.minecraft.client.renderer.entity.RenderLayerParent
- net.minecraft.client.renderer.entity.SalmonRenderer
+ net.minecraft.client.renderer.entity.SheepRenderer
- net.minecraft.client.renderer.entity.ShulkerBulletRenderer
+ net.minecraft.client.renderer.entity.ShulkerRenderer
- net.minecraft.client.renderer.entity.SilverfishRenderer
+ net.minecraft.client.renderer.entity.SkeletonRenderer
- net.minecraft.client.renderer.entity.SlimeRenderer
+ net.minecraft.client.renderer.entity.SnowGolemRenderer
- net.minecraft.client.renderer.entity.SpectralArrowRenderer
+ net.minecraft.client.renderer.entity.SpiderRenderer
- net.minecraft.client.renderer.entity.SquidRenderer
+ net.minecraft.client.renderer.entity.StrayRenderer
- net.minecraft.client.renderer.entity.StriderRenderer
+ net.minecraft.client.renderer.entity.ThrownItemRenderer
- net.minecraft.client.renderer.entity.ThrownTridentRenderer
+ net.minecraft.client.renderer.entity.TippableArrowRenderer
- net.minecraft.client.renderer.entity.TntMinecartRenderer
+ net.minecraft.client.renderer.entity.TntRenderer
- net.minecraft.client.renderer.entity.TropicalFishRenderer
+ net.minecraft.client.renderer.entity.TurtleRenderer
- net.minecraft.client.renderer.entity.UndeadHorseRenderer
+ net.minecraft.client.renderer.entity.VexRenderer
- net.minecraft.client.renderer.entity.VillagerRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer$1
+ net.minecraft.client.renderer.entity.WanderingTraderRenderer
- net.minecraft.client.renderer.entity.WitchRenderer
+ net.minecraft.client.renderer.entity.WitherBossRenderer
- net.minecraft.client.renderer.entity.WitherSkeletonRenderer
+ net.minecraft.client.renderer.entity.WitherSkullRenderer
- net.minecraft.client.renderer.entity.WolfRenderer
+ net.minecraft.client.renderer.entity.ZoglinRenderer
- net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.StaticTagHelper
+ net.minecraft.tags.StaticTagHelper$Wrapper
- net.minecraft.tags.SynchronizableTagCollection
+ net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.TagManager$Preparations
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$1
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.OminousBannerRenameFix
- net.minecraft.util.datafix.schemas.package-info
+ net.minecraft.util.datafix.schemas.V2522
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
+ net.minecraft.util.Deserializer
+ net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$1
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$1
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringUtil
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.TimeUtil
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.world.BossEvent
+ net.minecraft.world.BossEvent$BossBarColor
- net.minecraft.world.BossEvent$BossBarOverlay
+ net.minecraft.world.Clearable
- net.minecraft.world.CompoundContainer
+ net.minecraft.world.Container
- net.minecraft.world.ContainerHelper
+ net.minecraft.world.ContainerListener
- net.minecraft.world.Containers
+ net.minecraft.world.damagesource.BadRespawnPointDamage
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.EntityDamageSource
+ net.minecraft.world.damagesource.IndirectEntityDamageSource
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsoptionMobEffect
- net.minecraft.world.effect.AttackDamageMobEffect
+ net.minecraft.world.effect.HealthBoostMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgableMob
+ net.minecraft.world.entity.AgableMob$AgableMobGroupData
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.BaseAttribute
- net.minecraft.world.entity.ai.attributes.ModifiableAttributeInstance
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.BlockPosWrapper
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.PositionWrapper
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveCallback
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmourEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$Builder
- net.minecraft.world.entity.EntityType$EntityFactory
+ net.minecraft.world.entity.EquipmentSlot
- net.minecraft.world.entity.EquipmentSlot$Type
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.fishing.FishingHook$1
- net.minecraft.world.entity.fishing.FishingHook$OpenWaterType
- net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.global.LightningBolt
+ net.minecraft.world.entity.global.package-info
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.item.FallingBlockEntity
+ net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerableMount
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.CaveSpider
- net.minecraft.world.entity.monster.Creeper
+ net.minecraft.world.entity.monster.CrossbowAttackMob
- net.minecraft.world.entity.monster.Drowned
+ net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
- net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
+ net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
- net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
+ net.minecraft.world.entity.monster.ElderGuardian
- net.minecraft.world.entity.monster.EnderMan
+ net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
+ net.minecraft.world.entity.monster.Endermite
- net.minecraft.world.entity.monster.Enemy
+ net.minecraft.world.entity.monster.Evoker
- net.minecraft.world.entity.monster.Evoker$1
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$1
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
+ net.minecraft.world.entity.monster.Phantom$1
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$1
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.Ravager$RavagerNavigation
+ net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
- net.minecraft.world.entity.monster.SharedMonsterAttributes
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
- net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacements$Type
- net.minecraft.world.entity.TamableAnimal
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
- net.minecraft.world.level.levelgen.feature.AcaciaFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.VillageConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DarkOakFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.DesertVillagePools
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.FancyTreeFeature
- net.minecraft.world.level.levelgen.feature.FancyTreeFeature$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.GroundBushFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IcePatchFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
- net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
+ net.minecraft.world.level.levelgen.feature.MegaTreeFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.NoSurfaceOreFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.PlainVillagePools
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomRandomFeature
- net.minecraft.world.level.levelgen.feature.RandomScatteredFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SimulatedFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SnowyVillagePools
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaVillagePools
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.VillagePieces
+ net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelType
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PortalForcer
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.storage.LevelStorageSource$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
+ net.minecraft.world.ShulkerSharedHelper
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.Snooper
+ net.minecraft.world.Snooper$1
- net.minecraft.world.SnooperPopulator
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>

















































<details><summary>net.minecraft.advancements.critereon.FishingRodHookedTrigger</summary>

```diff
+ boolean lambda$trigger$0(FishingRodHookedTrigger$TriggerInstance)
+ void trigger(Collection)
- boolean lambda$trigger$0(FishingRodHookedTrigger$TriggerInstance)
- void trigger(Collection)
```

</details>
















































































<details><summary>net.minecraft.commands.arguments.item.FunctionArgument</summary>

```diff
+ Pair getFunctionOrTag(String)
- Either getFunctionOrTag(String)
```

</details>

<details><summary>net.minecraft.commands.arguments.item.FunctionArgument$2</summary>

```diff
+ Pair unwrap(CommandContext)
- Either unwrap(CommandContext)
```

</details>










































<details><summary>net.minecraft.core.dispenser.DispenseItemBehavior</summary>

```diff
+ void setEntityPokingOutOfBlock(Direction)
```

</details>






















































<details><summary>net.minecraft.data.models.model.TextureSlot</summary>

```diff
- TextureSlot[] $VALUES
+ String toString()
+ TextureSlot create(String)
+ TextureSlot create(TextureSlot)
+ void <init>(TextureSlot)
- TextureSlot valueOf(String)
- TextureSlot[] values()
- void <init>(String)
- void <init>(TextureSlot)
```

</details>













<details><summary>net.minecraft.data.tags.EntityTypeTagsProvider</summary>

```diff
- void useTags(TagCollection)
```

</details>

<details><summary>net.minecraft.data.tags.ItemTagsProvider</summary>

```diff
+ Function blockTags
- Logger LOGGER
+ void <init>(BlockTagsProvider)
+ void copy(Tag$Named)
- Tag$Entry copy(Tag$Entry)
- void <clinit>()
- void <init>(DataGenerator)
- void copy(Tag)
- void useTags(TagCollection)
```

</details>










<details><summary>net.minecraft.gametest.framework.GameTestServer</summary>

```diff
+ void <init>(BlockPos)
- void <init>(BlockPos)
```

</details>











































































































































































































































<details><summary>net.minecraft.server.dedicated.DedicatedServer</summary>

```diff
+ boolean forceSynchronousWrites()
+ String getLevelIdName()
+ void <init>(ChunkProgressListenerFactory)
- void <init>(String)
```

</details>





























<details><summary>net.minecraft.server.level.WorldGenRegion</summary>

```diff
+ ChunkPos firstPos
+ ChunkPos lastPos
```

</details>





















































<details><summary>net.minecraft.sounds.SoundEvents</summary>

```diff
+ SoundEvent HOGLIN_CONVERTED_TO_ZOMBIFIED
+ SoundEvent ZOGLIN_AMBIENT
+ SoundEvent ZOGLIN_ANGRY
+ SoundEvent ZOGLIN_ATTACK
+ SoundEvent ZOGLIN_DEATH
+ SoundEvent ZOGLIN_HURT
+ SoundEvent ZOGLIN_STEP
```

</details>






<details><summary>net.minecraft.tags.BlockTags</summary>

```diff
+ StaticTagHelper HELPER
+ Tag$Named ACACIA_LOGS
+ Tag$Named ANVIL
+ Tag$Named BAMBOO_PLANTABLE_ON
+ Tag$Named BANNERS
+ Tag$Named BEACON_BASE_BLOCKS
+ Tag$Named BEDS
+ Tag$Named BEE_GROWABLES
+ Tag$Named BEEHIVES
+ Tag$Named BIRCH_LOGS
+ Tag$Named BUTTONS
+ Tag$Named CARPETS
+ Tag$Named CLIMBABLE
+ Tag$Named CORAL_BLOCKS
+ Tag$Named CORAL_PLANTS
+ Tag$Named CORALS
+ Tag$Named CRIMSON_STEMS
+ Tag$Named CROPS
+ Tag$Named DARK_OAK_LOGS
+ Tag$Named DOORS
+ Tag$Named DRAGON_IMMUNE
+ Tag$Named ENDERMAN_HOLDABLE
+ Tag$Named FENCES
+ Tag$Named FIRE
+ Tag$Named FLOWER_POTS
+ Tag$Named FLOWERS
+ Tag$Named GOLD_ORES
+ Tag$Named HOGLIN_REPELLENTS
+ Tag$Named ICE
+ Tag$Named IMPERMEABLE
+ Tag$Named JUNGLE_LOGS
+ Tag$Named LEAVES
+ Tag$Named LOGS
+ Tag$Named LOGS_THAT_BURN
+ Tag$Named NON_FLAMMABLE_WOOD
+ Tag$Named NYLIUM
+ Tag$Named OAK_LOGS
+ Tag$Named PIGLIN_REPELLENTS
+ Tag$Named PLANKS
+ Tag$Named PORTALS
+ Tag$Named RAILS
+ Tag$Named SAND
+ Tag$Named SAPLINGS
+ Tag$Named SHULKER_BOXES
+ Tag$Named SIGNS
+ Tag$Named SLABS
+ Tag$Named SMALL_FLOWERS
+ Tag$Named SOUL_FIRE_BASE_BLOCKS
+ Tag$Named SOUL_SPEED_BLOCKS
+ Tag$Named SPRUCE_LOGS
+ Tag$Named STAIRS
+ Tag$Named STANDING_SIGNS
+ Tag$Named STONE_BRICKS
+ Tag$Named STRIDER_WARM_BLOCKS
+ Tag$Named TALL_FLOWERS
+ Tag$Named TRAPDOORS
+ Tag$Named UNDERWATER_BONEMEALS
+ Tag$Named VALID_SPAWN
+ Tag$Named WALL_CORALS
+ Tag$Named WALL_POST_OVERRIDE
+ Tag$Named WALL_SIGNS
+ Tag$Named WALLS
+ Tag$Named WARPED_STEMS
+ Tag$Named WART_BLOCKS
+ Tag$Named WITHER_IMMUNE
+ Tag$Named WITHER_SUMMON_BASE_BLOCKS
+ Tag$Named WOODEN_BUTTONS
+ Tag$Named WOODEN_DOORS
+ Tag$Named WOODEN_FENCES
+ Tag$Named WOODEN_PRESSURE_PLATES
+ Tag$Named WOODEN_SLABS
+ Tag$Named WOODEN_STAIRS
+ Tag$Named WOODEN_TRAPDOORS
+ Tag$Named WOOL
- int resetCount
- Tag ACACIA_LOGS
- Tag ANVIL
- Tag BAMBOO_PLANTABLE_ON
- Tag BANNERS
- Tag BEACON_BASE_BLOCKS
- Tag BEDS
- Tag BEE_GROWABLES
- Tag BEEHIVES
- Tag BIRCH_LOGS
- Tag BUTTONS
- Tag CARPETS
- Tag CLIMBABLE
- Tag CORAL_BLOCKS
- Tag CORAL_PLANTS
- Tag CORALS
- Tag CRIMSON_STEMS
- Tag CROPS
- Tag DARK_OAK_LOGS
- Tag DOORS
- Tag DRAGON_IMMUNE
- Tag ENDERMAN_HOLDABLE
- Tag FENCES
- Tag FIRE
- Tag FLOWER_POTS
- Tag FLOWERS
- Tag GOLD_ORES
- Tag HOGLIN_REPELLENTS
- Tag ICE
- Tag IMPERMEABLE
- Tag JUNGLE_LOGS
- Tag LEAVES
- Tag LOGS
- Tag LOGS_THAT_BURN
- Tag NON_FLAMMABLE_WOOD
- Tag NYLIUM
- Tag OAK_LOGS
- Tag PIGLIN_REPELLENTS
- Tag PLANKS
- Tag PORTALS
- Tag RAILS
- Tag SAND
- Tag SAPLINGS
- Tag SHULKER_BOXES
- Tag SIGNS
- Tag SLABS
- Tag SMALL_FLOWERS
- Tag SOUL_FIRE_BASE_BLOCKS
- Tag SOUL_SPEED_BLOCKS
- Tag SPRUCE_LOGS
- Tag STAIRS
- Tag STANDING_SIGNS
- Tag STONE_BRICKS
- Tag STRIDER_WARM_BLOCKS
- Tag TALL_FLOWERS
- Tag TRAPDOORS
- Tag UNDERWATER_BONEMEALS
- Tag VALID_SPAWN
- Tag WALL_CORALS
- Tag WALL_POST_OVERRIDE
- Tag WALL_SIGNS
- Tag WALLS
- Tag WARPED_STEMS
- Tag WART_BLOCKS
- Tag WITHER_IMMUNE
- Tag WITHER_SUMMON_BASE_BLOCKS
- Tag WOODEN_BUTTONS
- Tag WOODEN_DOORS
- Tag WOODEN_FENCES
- Tag WOODEN_PRESSURE_PLATES
- Tag WOODEN_SLABS
- Tag WOODEN_STAIRS
- Tag WOODEN_TRAPDOORS
- Tag WOOL
- TagCollection source
+ Tag$Named bind(String)
- int access$000()
- Optional lambda$static$0(ResourceLocation)
- Tag bind(String)
- TagCollection access$100()
```

</details>

<details><summary>net.minecraft.tags.FluidTags</summary>

```diff
+ StaticTagHelper HELPER
+ Tag$Named LAVA
+ Tag$Named WATER
- int resetCount
- Tag LAVA
- Tag WATER
- TagCollection source
+ Tag$Named bind(String)
- int access$000()
- Optional lambda$static$0(ResourceLocation)
- Tag bind(String)
- TagCollection access$100()
```

</details>

<details><summary>net.minecraft.tags.Tag$Builder</summary>

```diff
+ Set entries
- boolean ordered
- Set values
+ boolean lambda$getUnresolvedEntries$1(Tag$Entry)
+ JsonObject serializeToJson()
+ Optional build(Function)
+ Stream getEntries()
+ Stream getUnresolvedEntries(Function)
+ Tag$Builder addElement(ResourceLocation)
+ Tag$Builder addFromJson(JsonObject)
+ void lambda$null$0(Object)
- boolean canBuild(Function)
- JsonParseException lambda$addFromJson$0(ResourceLocation)
- Tag build(ResourceLocation)
- Tag$Builder add(Collection)
- Tag$Builder add(Object)
- Tag$Builder add(Object[])
- Tag$Builder addFromJson(JsonObject)
- Tag$Builder addTag(Tag)
- Tag$Builder keepOrder(boolean)
```

</details>

<details><summary>net.minecraft.tags.Tag$TagEntry</summary>

```diff
- Tag tag
+ boolean build(Consumer)
+ String toString()
+ void serializeTo(JsonArray)
- boolean canBuild(Function)
- ResourceLocation getId()
- void <init>(Tag)
- void build(Collection)
- void serializeTo(Function)
```

</details>

<details><summary>net.minecraft.tags.TagCollection</summary>

```diff
+ BiMap tags
+ Tag empty
- boolean ordered
- Map tags
+ Map lambda$prepare$2(ResourceManager)
+ Object lambda$load$3(ResourceLocation)
+ ResourceLocation getId(Tag)
+ ResourceLocation getId(Tag$Named)
+ ResourceLocation getIdOrThrow(Tag)
+ Tag$Builder lambda$null$1(ResourceLocation)
+ void <init>(String)
+ void lambda$load$4(Tag$Builder)
- Map lambda$prepare$3(ResourceManager)
- Tag$Builder lambda$null$2(ResourceLocation)
- void <init>(String)
- void lambda$load$4(Tag$Builder)
- void lambda$load$5(Tag$Builder)
- void lambda$null$1(Tag$Builder)
```

</details>






<details><summary>net.minecraft.util.Mth</summary>

```diff
+ double inverseLerp(double,double,double)
- double pct(double,double,double)
```

</details>


























































































<details><summary>net.minecraft.world.entity.ai.attributes.AttributeModifier</summary>

```diff
+ Logger LOGGER
- boolean serialize
+ AttributeModifier load(CompoundTag)
+ CompoundTag save()
+ void <clinit>()
- AttributeModifier setSerialize(boolean)
- boolean isSerializable()
```

</details>

<details><summary>net.minecraft.world.entity.ai.attributes.RangedAttribute</summary>

```diff
- String importLegacyName
+ void <init>(String,double,double,double)
- RangedAttribute importLegacyName(String)
- String getImportLegacyName()
- void <init>(String,double,double,double)
```

</details>


















<details><summary>net.minecraft.world.entity.ai.behavior.LookAtTargetSink</summary>

```diff
+ boolean lambda$canStillUse$0(PositionTracker)
+ void lambda$tick$1(PositionTracker)
- boolean lambda$canStillUse$0(PositionWrapper)
- void lambda$tick$1(PositionWrapper)
```

</details>







































































<details><summary>net.minecraft.world.entity.ai.memory.MemoryModuleType</summary>

```diff
+ MemoryModuleType NEAREST_VISIBLE_HUNTABLE_HOGLIN
+ MemoryModuleType NEAREST_VISIBLE_ZOMBIFIED
- MemoryModuleType NEAREST_VISIBLE_ADULT_HOGLIN
- MemoryModuleType NEAREST_VISIBLE_ZOMBIFIED_PIGLIN
```

</details>

<details><summary>net.minecraft.world.entity.ai.memory.WalkTarget</summary>

```diff
+ PositionTracker target
- PositionWrapper target
+ PositionTracker getTarget()
+ void <init>(PositionTracker,float,int)
- PositionWrapper getTarget()
- void <init>(PositionWrapper,float,int)
```

</details>


<details><summary>net.minecraft.world.entity.ai.navigation.PathNavigation</summary>

```diff
- AttributeInstance followRange
```

</details>
























<details><summary>net.minecraft.world.entity.animal.Bee</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>







<details><summary>net.minecraft.world.entity.animal.Cat</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.animal.Chicken</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>

<details><summary>net.minecraft.world.entity.animal.Cow</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>




<details><summary>net.minecraft.world.entity.animal.Fox</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>












<details><summary>net.minecraft.world.entity.animal.IronGolem</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.animal.Ocelot</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>








<details><summary>net.minecraft.world.entity.animal.Parrot</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>

<details><summary>net.minecraft.world.entity.animal.Pig</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>




<details><summary>net.minecraft.world.entity.animal.Rabbit</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>







<details><summary>net.minecraft.world.entity.animal.Squid</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>




<details><summary>net.minecraft.world.entity.animal.Turtle</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>








<details><summary>net.minecraft.world.entity.animal.horse.AbstractHorse</summary>

```diff
- Attribute JUMP_STRENGTH
+ AttributeSupplier$Builder createBaseHorseAttributes()
+ void randomizeAttributes()
- boolean hurt(DamageSource,float)
- void registerAttributes()
```

</details>

<details><summary>net.minecraft.world.entity.animal.horse.Horse</summary>

```diff
+ void randomizeAttributes()
- void registerAttributes()
```

</details>

<details><summary>net.minecraft.world.entity.animal.horse.Llama</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>



<details><summary>net.minecraft.world.entity.animal.horse.SkeletonHorse</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
+ void randomizeAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.animal.horse.ZombieHorse</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
+ void randomizeAttributes()
- void registerAttributes()
```

</details>



<details><summary>net.minecraft.world.entity.boss.enderdragon.EnderDragon</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>










<details><summary>net.minecraft.world.entity.boss.wither.WitherBoss</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>










<details><summary>net.minecraft.world.entity.monster.Silverfish</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.monster.Slime</summary>

```diff
- void registerAttributes()
```

</details>





<details><summary>net.minecraft.world.entity.monster.Spider</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>







<details><summary>net.minecraft.world.entity.monster.Vindicator</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>


<details><summary>net.minecraft.world.entity.monster.Witch</summary>

```diff
+ AttributeSupplier$Builder createAttributes()
- void registerAttributes()
```

</details>

























<details><summary>net.minecraft.world.entity.projectile.AbstractArrow</summary>

```diff
- int flightTime
+ boolean canHitEntity(Entity)
- boolean lambda$findHitEntity$0(Entity)
```

</details>

<details><summary>net.minecraft.world.entity.projectile.AbstractHurtingProjectile</summary>

```diff
- int flightTime
+ boolean canHitEntity(Entity)
```

</details>



<details><summary>net.minecraft.world.entity.projectile.FireworkRocketEntity</summary>

```diff
- boolean lambda$tick$1(Entity)
```

</details>


<details><summary>net.minecraft.world.entity.projectile.Projectile</summary>

```diff
+ boolean leftOwner
+ int ownerNetworkId
+ boolean canHitEntity(Entity)
+ boolean checkLeftOwner()
+ boolean lambda$checkLeftOwner$0(Entity)
+ float lerpRotation(float,float)
+ void tick()
+ void updateRotation()
```

</details>

<details><summary>net.minecraft.world.entity.projectile.ShulkerBullet</summary>

```diff
+ boolean canHitEntity(Entity)
```

</details>







































































<details><summary>net.minecraft.world.item.ArmorItem</summary>

```diff
+ Multimap defaultModifiers
```

</details>




















<details><summary>net.minecraft.world.item.DiggerItem</summary>

```diff
+ Multimap defaultModifiers
- float attackSpeedBaseline
```

</details>




















<details><summary>net.minecraft.world.item.ItemStack</summary>

```diff
+ Component lambda$expandBlockState$2(Component)
+ void addAttributeModifier(EquipmentSlot)
+ void lambda$appendEnchantmentNames$1(Enchantment)
+ void lambda$static$0(DecimalFormat)
- Component lambda$expandBlockState$1(Component)
- DecimalFormat getAttributeDecimalFormat()
- void addAttributeModifier(EquipmentSlot)
- void lambda$appendEnchantmentNames$0(Enchantment)
- void lambda$getAttributeModifiers$2(AttributeModifier)
```

</details>































<details><summary>net.minecraft.world.item.crafting.Ingredient</summary>

```diff
- Predicate NON_ALL_EMPTY
+ boolean lambda$of$3(ItemStack)
+ Ingredient of(Stream)
+ Ingredient$ItemValue lambda$fromNetwork$5(FriendlyByteBuf)
+ Ingredient$ItemValue lambda$of$4(ItemStack)
+ Ingredient$Value lambda$fromJson$6(JsonElement)
+ Ingredient$Value[] lambda$new$0(int)
+ ItemStack[] lambda$dissolve$2(int)
+ JsonSyntaxException lambda$valueFromJson$7(ResourceLocation)
+ Stream lambda$dissolve$1(Ingredient$Value)
- boolean lambda$static$0(Ingredient$Value)
- Ingredient$ItemValue lambda$fromNetwork$6(FriendlyByteBuf)
- Ingredient$ItemValue lambda$of$4(ItemLike)
- Ingredient$ItemValue lambda$of$5(ItemStack)
- Ingredient$Value lambda$fromJson$7(JsonElement)
- Ingredient$Value[] lambda$new$1(int)
- ItemStack[] lambda$dissolve$3(int)
- JsonSyntaxException lambda$valueFromJson$8(ResourceLocation)
- Stream lambda$dissolve$2(Ingredient$Value)
```

</details>





















<details><summary>net.minecraft.world.item.enchantment.EnchantmentCategory</summary>

```diff
+ EnchantmentCategory VANISHABLE
- EnchantmentCategory ALL
```

</details>



<details><summary>net.minecraft.world.item.enchantment.EnchantmentCategory$14</summary>

```diff
+ boolean lambda$canEnchant$0(EnchantmentCategory)
+ boolean lambda$canEnchant$1(EnchantmentCategory)
```

</details>







































<details><summary>net.minecraft.world.level.LevelAccessor</summary>

```diff
+ Stream getEntityCollisions(Predicate)
- Stream getEntityCollisions(Set)
```

</details>








































































<details><summary>net.minecraft.world.level.block.BeehiveBlock</summary>

```diff
+ Direction getRandomOffset(Random)
```

</details>




























































































































































<details><summary>net.minecraft.world.level.block.grower.AbstractMegaTreeGrower</summary>

```diff
+ boolean growTree(Random)
+ boolean placeMega(Random,int,int)
- boolean growTree(Random)
- boolean placeMega(Random,int,int)
```

</details>











































<details><summary>net.minecraft.world.level.chunk.ChunkGenerator</summary>

```diff
+ void fillFromNoise(net.minecraft.world.level.LevelAccessor,net.minecraft.world.level.StructureFeatureManager,net.minecraft.world.level.chunk.ChunkAccess)
- void fillFromNoise(net.minecraft.world.level.LevelAccessor,net.minecraft.world.level.chunk.ChunkAccess)
+ BlockPos findNearestMapFeature(BlockPos,int,boolean)
+ List getMobsAt(BlockPos)
+ void applyBiomeDecoration(StructureFeatureManager)
+ void createReferences(ChunkAccess)
+ void createStructures(StructureManager)
- BlockPos findNearestMapFeature(BlockPos,int,boolean)
- List getMobsAt(BlockPos)
- void applyBiomeDecoration(WorldGenRegion)
- void createReferences(ChunkAccess)
- void createStructures(StructureManager)
```

</details>



















<details><summary>net.minecraft.world.level.chunk.storage.ChunkStorage</summary>

```diff
+ void <init>(DataFixer,boolean)
- void <init>(DataFixer)
```

</details>





<details><summary>net.minecraft.world.level.chunk.storage.RegionFileStorage</summary>

```diff
+ boolean sync
+ void <init>(File,boolean)
+ void flush()
- void <init>(File)
```

</details>












<details><summary>net.minecraft.world.level.levelgen.FlatLevelSource</summary>

```diff
+ BlockPos findNearestMapFeature(BlockPos,int,boolean)
+ void fillFromNoise(ChunkAccess)
- BlockPos findNearestMapFeature(BlockPos,int,boolean)
- void fillFromNoise(ChunkAccess)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator</summary>

```diff
+ void fillFromNoise(ChunkAccess)
+ void lambda$fillFromNoise$1(StructureStart)
- void fillFromNoise(ChunkAccess)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.OverworldLevelSource</summary>

```diff
+ List getMobsAt(BlockPos)
- List getMobsAt(BlockPos)
```

</details>








<details><summary>net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature</summary>

```diff
+ boolean place(FeatureConfiguration)
- boolean place(FeatureConfiguration)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.AbstractSmallTreeFeature</summary>

```diff
+ Optional getProjectedOrigin(SmallTreeConfiguration)
- Optional getProjectedOrigin(SmallTreeConfiguration)
- void placeTrunk(SmallTreeConfiguration)
```

</details>







<details><summary>net.minecraft.world.level.levelgen.placement.ConfiguredDecorator</summary>

```diff
+ boolean place(ConfiguredFeature)
- boolean place(ConfiguredFeature)
```

</details>
























<details><summary>net.minecraft.world.level.levelgen.structure.DesertPyramidPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.structure.JunglePyramidPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>









<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.structure.StructureStart</summary>

```diff
+ void postProcess(ChunkPos)
- void postProcess(ChunkPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.SwamplandHutPiece</summary>

```diff
+ boolean postProcess(BlockPos)
- boolean postProcess(BlockPos)
```

</details>
































































































<details><summary>net.minecraft.world.level.storage.McRegionUpgrader</summary>

```diff
+ boolean convertLevel(ProgressListener)
+ void makeMcrLevelDatBackup(File)
- boolean convertLevel(ProgressListener)
- void makeMcrLevelDatBackup(String)
```

</details>


































































<details><summary>net.minecraft.world.level.storage.loot.functions.SetAttributesFunction</summary>

```diff
+ SetAttributesFunction$ModifierBuilder modifier(RandomValueBounds)
- SetAttributesFunction$ModifierBuilder modifier(RandomValueBounds)
```

</details>


<details><summary>net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder</summary>

```diff
+ Attribute attribute
- String attribute
+ void <init>(RandomValueBounds)
- void <init>(RandomValueBounds)
```

</details>















































































<details><summary>Added and removed classes</summary>

```diff
- net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.StaticTagHelper
+ net.minecraft.tags.StaticTagHelper$Wrapper
- net.minecraft.tags.SynchronizableTagCollection
+ net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.TagManager$Preparations
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$1
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.OminousBannerRenameFix
- net.minecraft.util.datafix.schemas.package-info
+ net.minecraft.util.datafix.schemas.V2522
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
+ net.minecraft.util.Deserializer
+ net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$1
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$1
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringUtil
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.TimeUtil
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.world.BossEvent
+ net.minecraft.world.BossEvent$BossBarColor
- net.minecraft.world.BossEvent$BossBarOverlay
+ net.minecraft.world.Clearable
- net.minecraft.world.CompoundContainer
+ net.minecraft.world.Container
- net.minecraft.world.ContainerHelper
+ net.minecraft.world.ContainerListener
- net.minecraft.world.Containers
+ net.minecraft.world.damagesource.BadRespawnPointDamage
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.EntityDamageSource
+ net.minecraft.world.damagesource.IndirectEntityDamageSource
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsoptionMobEffect
- net.minecraft.world.effect.AttackDamageMobEffect
+ net.minecraft.world.effect.HealthBoostMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgableMob
+ net.minecraft.world.entity.AgableMob$AgableMobGroupData
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.BaseAttribute
- net.minecraft.world.entity.ai.attributes.ModifiableAttributeInstance
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.BlockPosWrapper
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.PositionWrapper
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveCallback
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmourEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$Builder
- net.minecraft.world.entity.EntityType$EntityFactory
+ net.minecraft.world.entity.EquipmentSlot
- net.minecraft.world.entity.EquipmentSlot$Type
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.fishing.FishingHook$1
- net.minecraft.world.entity.fishing.FishingHook$OpenWaterType
- net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.global.LightningBolt
+ net.minecraft.world.entity.global.package-info
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.item.FallingBlockEntity
+ net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerableMount
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.CaveSpider
- net.minecraft.world.entity.monster.Creeper
+ net.minecraft.world.entity.monster.CrossbowAttackMob
- net.minecraft.world.entity.monster.Drowned
+ net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
- net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
+ net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
- net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
+ net.minecraft.world.entity.monster.ElderGuardian
- net.minecraft.world.entity.monster.EnderMan
+ net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
+ net.minecraft.world.entity.monster.Endermite
- net.minecraft.world.entity.monster.Enemy
+ net.minecraft.world.entity.monster.Evoker
- net.minecraft.world.entity.monster.Evoker$1
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$1
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
+ net.minecraft.world.entity.monster.Phantom$1
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$1
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.Ravager$RavagerNavigation
+ net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
- net.minecraft.world.entity.monster.SharedMonsterAttributes
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
- net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacements$Type
- net.minecraft.world.entity.TamableAnimal
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
- net.minecraft.world.level.levelgen.feature.AcaciaFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.VillageConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DarkOakFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.DesertVillagePools
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.FancyTreeFeature
- net.minecraft.world.level.levelgen.feature.FancyTreeFeature$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.GroundBushFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IcePatchFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
- net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
+ net.minecraft.world.level.levelgen.feature.MegaTreeFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.NoSurfaceOreFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.PlainVillagePools
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomRandomFeature
- net.minecraft.world.level.levelgen.feature.RandomScatteredFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SimulatedFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SnowyVillagePools
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaVillagePools
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.VillagePieces
+ net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelType
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PortalForcer
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.storage.LevelStorageSource$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
+ net.minecraft.world.ShulkerSharedHelper
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.Snooper
+ net.minecraft.world.Snooper$1
- net.minecraft.world.SnooperPopulator
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
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