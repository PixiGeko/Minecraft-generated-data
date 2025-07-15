## Comparison with [1.20.4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20.4)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.20.4</th><th>23w51a</th></tr><tr><td>DataPack version</td><td><pre>26</pre></td><td><pre>27</pre></td></tr><tr><td>World version</td><td><pre>3700</pre></td><td><pre>3801</pre></td></tr><tr><td>Protocol version</td><td><pre>765</pre></td><td><pre>1073741993</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:generic.block_interaction_range
+ minecraft:generic.entity_interaction_range
+ minecraft:generic.scale
+ minecraft:generic.step_height
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:armadillo
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:armadillo_scute
+ minecraft:armadillo_spawn_egg
- minecraft:scute
+ minecraft:turtle_scute
+ minecraft:wolf_armor
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:breeze_leaving_water
+ minecraft:danger_detected_recently
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
+ minecraft:armadillo_scare_detected
+ minecraft:armadillo_temptations
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.armadillo.ambient
+ minecraft:entity.armadillo.brush
+ minecraft:entity.armadillo.death
+ minecraft:entity.armadillo.eat
+ minecraft:entity.armadillo.hurt
+ minecraft:entity.armadillo.land
+ minecraft:entity.armadillo.roll
+ minecraft:entity.armadillo.scute_drop
+ minecraft:entity.armadillo.step
+ minecraft:entity.armadillo.unroll
+ minecraft:entity.breeze.charge
+ minecraft:entity.breeze.deflect
+ minecraft:entity.breeze.whirl
+ minecraft:item.armor.equip_wolf
+ minecraft:item.armor.unequip_wolf
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:armadillo
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:armadillo
```

</details>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:generic.block_interaction_range
+ minecraft:generic.entity_interaction_range
+ minecraft:generic.scale
+ minecraft:generic.step_height
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:armadillo
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:armadillo_scute
+ minecraft:armadillo_spawn_egg
- minecraft:scute
+ minecraft:turtle_scute
+ minecraft:wolf_armor
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:breeze_leaving_water
+ minecraft:danger_detected_recently
```

</details>
<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:armadillo_scare_detected
+ minecraft:armadillo_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.armadillo.ambient
+ minecraft:entity.armadillo.brush
+ minecraft:entity.armadillo.death
+ minecraft:entity.armadillo.eat
+ minecraft:entity.armadillo.hurt
+ minecraft:entity.armadillo.land
+ minecraft:entity.armadillo.roll
+ minecraft:entity.armadillo.scute_drop
+ minecraft:entity.armadillo.step
+ minecraft:entity.armadillo.unroll
+ minecraft:entity.breeze.charge
+ minecraft:entity.breeze.deflect
+ minecraft:entity.breeze.whirl
+ minecraft:item.armor.equip_wolf
+ minecraft:item.armor.unequip_wolf
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ wolf_armor.json
```

</details>
<details>
<summary>
turtle_helmet.json
</summary>

```
A: scute
B: turtle_scute

Previous pattern:
[A | A | A]
[A |   | A]

New pattern:
[B | B | B]
[B |   | B]
```

</details>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ attribute.name.generic.block_interaction_range: Block Interaction Range
+ attribute.name.generic.entity_interaction_range: Entity Interaction Range
+ attribute.name.generic.scale: Scale
+ attribute.name.generic.step_height: Step Height
+ entity.minecraft.armadillo: Armadillo
+ item.minecraft.armadillo_scute: Armadillo Scute
+ item.minecraft.armadillo_spawn_egg: Armadillo Spawn Egg
- item.minecraft.scute: Scute
+ item.minecraft.turtle_scute: Turtle Scute
+ item.minecraft.wolf_armor: Wolf Armor
+ subtitles.entity.armadillo.ambient: Armadillo grunts
+ subtitles.entity.armadillo.brush: Armadillo brushes
+ subtitles.entity.armadillo.death: Armadillo dies
+ subtitles.entity.armadillo.eat: Armadillo eats
+ subtitles.entity.armadillo.hurt: Armadillo hurts
+ subtitles.entity.armadillo.land: Armadillo lands
+ subtitles.entity.armadillo.roll: Armadillo rolls up
+ subtitles.entity.armadillo.scute_drop: Scute drops
+ subtitles.entity.armadillo.unroll: Armadillo unrolls
+ subtitles.entity.breeze.charge: Breeze charges
+ subtitles.entity.breeze.deflect: Breeze deflects
+ subtitles.entity.breeze.whirl: Breeze whirls
+ subtitles.item.armor.equip_wolf: Wolf armor straps
+ subtitles.item.armor.unequip_wolf: Wolf armor slips off
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.20.4</th><th>23w51a</th></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.respawn_anchor.ambient</div></th><td>Portal whooshes</td><td>Respawn Anchor whooshes</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.trial_spawner.spawn_mob</div></th><td>Mob spawns</td><td>Trial Spawner spawns a mob</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.glow_item_frame.break</div></th><td>Glow Item Frame breaks</td><td>Glow Item Frame broken</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.item_frame.break</div></th><td>Item Frame breaks</td><td>Item Frame broken</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.leash_knot.break</div></th><td>Leash Knot breaks</td><td>Leash Knot broken</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.painting.break</div></th><td>Painting breaks</td><td>Painting broken</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.polar_bear.ambient_baby</div></th><td>Polar Bear hums</td><td>Baby Polar Bear hums</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.turtle.death_baby</div></th><td>Turtle baby dies</td><td>Baby Turtle dies</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.turtle.hurt_baby</div></th><td>Turtle baby hurts</td><td>Baby Turtle hurts</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.turtle.shamble_baby</div></th><td>Turtle baby shambles</td><td>Baby Turtle shambles</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/combat/wolf_armor.json
+ minecraft/damage_type/spit.json
+ minecraft/datapacks/update_1_21/data/minecraft/damage_type/wind_charge.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/damage_type/always_kills_armor_stands.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/damage_type/is_projectile.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/doors.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/trapdoors.json
+ minecraft/loot_tables/entities/armadillo.json
+ minecraft/recipes/wolf_armor.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/models/item/armadillo_scute.json
+ minecraft/models/item/armadillo_spawn_egg.json
- minecraft/models/item/scute.json
+ minecraft/models/item/turtle_scute.json
+ minecraft/models/item/wolf_armor.json
+ minecraft/textures/entity/armadillo.png
+ minecraft/textures/entity/breeze/breeze_eyes.png
+ minecraft/textures/entity/wolf/wolf_armor.png
+ minecraft/textures/item/armadillo_scute.png
- minecraft/textures/item/scute.png
+ minecraft/textures/item/turtle_scute.png
+ minecraft/textures/item/wolf_armor.png
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
+ XXX.advancements.packs.package-info
+ XXX.advancements.packs.UpdateOneTwentyOneAdvancementProvider
- XXX.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaAdventureAdvancements
+ XXX.advancements.packs.VanillaHusbandryAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
+ XXX.advancements.packs.VanillaStoryAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
- XXX.ai.sensing.MobSensor
+ XXX.ai.sensing.NearestBedSensor
- XXX.ai.sensing.NearestItemSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
- XXX.ai.sensing.NearestVisibleLivingEntitySensor
- XXX.ai.sensing.package-info
+ XXX.ai.sensing.PiglinBruteSpecificSensor
- XXX.ai.sensing.PiglinSpecificSensor
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
- XXX.ai.sensing.TemptingSensor
+ XXX.ai.sensing.VillagerBabiesSensor
- XXX.ai.sensing.VillagerHostilesSensor
+ XXX.ai.sensing.WardenEntitySensor
- XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
+ XXX.ai.util.AirAndWaterRandomPos
- XXX.ai.util.AirRandomPos
+ XXX.ai.util.DefaultRandomPos
- XXX.ai.util.GoalUtils
+ XXX.ai.util.HoverRandomPos
- XXX.ai.util.LandRandomPos
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
- XXX.animal.allay.Allay
+ XXX.animal.allay.Allay$JukeboxListener
- XXX.animal.allay.Allay$VibrationUser
+ XXX.animal.allay.AllayAi
- XXX.animal.allay.package-info
- XXX.animal.armadillo.Armadillo$1
- XXX.animal.armadillo.Armadillo$ArmadilloState
- XXX.animal.armadillo.ArmadilloAi$1
- XXX.animal.armadillo.ArmadilloAi$ArmadilloPanic
- XXX.core.dispenser.DispenseItemBehavior$28
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$7$1
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$8$1
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.DustColorTransitionOptions
- XXX.core.particles.DustColorTransitionOptions$1
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.DustParticleOptions$1
+ XXX.core.particles.DustParticleOptionsBase
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
- XXX.core.particles.ParticleGroup
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SculkChargeParticleOptions
+ XXX.core.particles.SculkChargeParticleOptions$1
- XXX.core.particles.ShriekParticleOption
+ XXX.core.particles.ShriekParticleOption$1
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
- XXX.core.particles.VibrationParticleOption
+ XXX.core.particles.VibrationParticleOption$1
+ XXX.core.registries.BuiltInRegistries
- XXX.core.registries.BuiltInRegistries$RegistryBootstrap
- XXX.core.registries.package-info
+ XXX.core.registries.Registries
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdvancementSubProvider
- XXX.data.advancements.package-info
- XXX.data.info.BiomeParametersDumpReport
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLootSubProvider
- XXX.data.loot.EntityLootSubProvider
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableProvider$1
+ XXX.data.loot.LootTableProvider$SubProviderEntry
- XXX.data.loot.LootTableSubProvider
+ XXX.data.loot.package-info
+ XXX.data.metadata.package-info
- XXX.data.metadata.PackMetadataGenerator
- XXX.data.models.BlockModelGenerators
+ XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ItemModelGenerators$TrimModelData
- XXX.data.models.ModelProvider
- XXX.data.models.package-info
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeBuilder$1
- XXX.data.recipes.RecipeCategory
+ XXX.data.recipes.RecipeOutput
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.RecipeProvider$1
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SmithingTransformRecipeBuilder
+ XXX.data.recipes.SmithingTrimRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.registries.package-info
+ XXX.data.registries.RegistriesDatapackGenerator
- XXX.data.registries.RegistryPatchGenerator
+ XXX.data.registries.UpdateOneTwentyOneRegistries
- XXX.data.registries.VanillaRegistries
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtDatafixer
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BannerPatternTagsProvider
+ XXX.data.tags.BiomeTagsProvider
- XXX.data.tags.CatVariantTagsProvider
+ XXX.data.tags.DamageTypeTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.InstrumentTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ XXX.data.tags.ItemTagsProvider
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1CombinedData
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.TagsProvider$TagLookup
+ XXX.data.tags.TradeRebalanceStructureTagsProvider
- XXX.data.tags.UpdateOneTwentyOneBiomeTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneBlockTagsProvider
- XXX.data.tags.UpdateOneTwentyOneDamageTypeTagsProvider
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V3799
+ XXX.datafix.schemas.V501
- XXX.datafix.schemas.V700
+ XXX.datafix.schemas.V701
- XXX.datafix.schemas.V702
+ XXX.datafix.schemas.V703
- XXX.datafix.schemas.V704
+ XXX.datafix.schemas.V704$1
- XXX.datafix.schemas.V705
+ XXX.datafix.schemas.V705$1
- XXX.datafix.schemas.V808
+ XXX.datafix.schemas.V99
- XXX.datafix.schemas.V99$1
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractFish
- XXX.entity.animal.AbstractFish$FishMoveControl
+ XXX.entity.animal.AbstractFish$FishSwimGoal
- XXX.entity.animal.AbstractGolem
+ XXX.entity.animal.AbstractSchoolingFish
- XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ XXX.entity.animal.Animal
- XXX.entity.animal.Bee
+ XXX.entity.animal.Bee$1
- XXX.entity.animal.Bee$BaseBeeGoal
+ XXX.entity.animal.Bee$BeeAttackGoal
- XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ XXX.entity.animal.Bee$BeeEnterHiveGoal
- XXX.entity.animal.Bee$BeeGoToHiveGoal
+ XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
- XXX.entity.animal.Bee$BeeGrowCropGoal
+ XXX.entity.animal.Bee$BeeHurtByOtherGoal
- XXX.entity.animal.Bee$BeeLocateHiveGoal
+ XXX.entity.animal.Bee$BeeLookControl
- XXX.entity.animal.Bee$BeePollinateGoal
+ XXX.entity.animal.Bee$BeeWanderGoal
- XXX.entity.animal.Bucketable
+ XXX.entity.animal.Cat
- XXX.entity.animal.Cat$CatAvoidEntityGoal
+ XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
- XXX.entity.animal.Cat$CatTemptGoal
+ XXX.entity.animal.CatVariant
- XXX.entity.animal.Chicken
+ XXX.entity.animal.Cod
- XXX.entity.animal.Cow
+ XXX.entity.animal.Dolphin
- XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- XXX.entity.animal.Dolphin$PlayWithItemsGoal
+ XXX.entity.animal.FlyingAnimal
- XXX.entity.animal.Fox
+ XXX.entity.animal.Fox$DefendTrustedTargetGoal
- XXX.entity.animal.Fox$FaceplantGoal
+ XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
- XXX.entity.animal.Fox$FoxBehaviorGoal
+ XXX.entity.animal.Fox$FoxBreedGoal
- XXX.entity.animal.Fox$FoxEatBerriesGoal
+ XXX.entity.animal.Fox$FoxFloatGoal
- XXX.entity.animal.Fox$FoxFollowParentGoal
+ XXX.entity.animal.Fox$FoxGroupData
- XXX.entity.animal.Fox$FoxLookAtPlayerGoal
+ XXX.entity.animal.Fox$FoxLookControl
- XXX.entity.animal.Fox$FoxMeleeAttackGoal
+ XXX.entity.animal.Fox$FoxMoveControl
- XXX.entity.animal.Fox$FoxPanicGoal
+ XXX.entity.animal.Fox$FoxPounceGoal
- XXX.entity.animal.Fox$FoxSearchForItemsGoal
+ XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
- XXX.entity.animal.Fox$PerchAndSearchGoal
+ XXX.entity.animal.Fox$SeekShelterGoal
- XXX.entity.animal.Fox$SleepGoal
+ XXX.entity.animal.Fox$StalkPreyGoal
- XXX.entity.animal.Fox$Type
+ XXX.entity.animal.FrogVariant
- XXX.entity.animal.IronGolem
+ XXX.entity.animal.IronGolem$Crackiness
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$MushroomType
- XXX.entity.animal.Ocelot
+ XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
- XXX.entity.animal.Ocelot$OcelotTemptGoal
+ XXX.entity.animal.Panda
- XXX.entity.animal.Panda$Gene
+ XXX.entity.animal.Panda$PandaAttackGoal
- XXX.entity.animal.Panda$PandaAvoidGoal
+ XXX.entity.animal.Panda$PandaBreedGoal
- XXX.entity.animal.Panda$PandaHurtByTargetGoal
+ XXX.entity.animal.Panda$PandaLieOnBackGoal
- XXX.entity.animal.Panda$PandaLookAtPlayerGoal
+ XXX.entity.animal.Panda$PandaMoveControl
- XXX.entity.animal.Panda$PandaPanicGoal
+ XXX.entity.animal.Panda$PandaRollGoal
- XXX.entity.animal.Panda$PandaSitGoal
+ XXX.entity.animal.Panda$PandaSneezeGoal
- XXX.entity.animal.Parrot
+ XXX.entity.animal.Parrot$1
- XXX.entity.animal.Parrot$ParrotWanderGoal
+ XXX.entity.animal.Parrot$Variant
- XXX.entity.animal.Pig
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.animal.PolarBear$PolarBearPanicGoal
- XXX.entity.animal.Pufferfish
+ XXX.entity.animal.Pufferfish$PufferfishPuffGoal
- XXX.entity.animal.Rabbit
+ XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
- XXX.entity.animal.Rabbit$RabbitGroupData
+ XXX.entity.animal.Rabbit$RabbitJumpControl
- XXX.entity.animal.Rabbit$RabbitMoveControl
+ XXX.entity.animal.Rabbit$RabbitPanicGoal
- XXX.entity.animal.Rabbit$RaidGardenGoal
+ XXX.entity.animal.Rabbit$Variant
- XXX.entity.animal.Salmon
+ XXX.entity.animal.Sheep
- XXX.entity.animal.Sheep$1
+ XXX.entity.animal.Sheep$2
- XXX.entity.animal.ShoulderRidingEntity
+ XXX.entity.animal.SnowGolem
- XXX.entity.animal.Squid
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
+ XXX.entity.animal.TropicalFish
- XXX.entity.animal.TropicalFish$Base
+ XXX.entity.animal.TropicalFish$Pattern
- XXX.entity.animal.TropicalFish$TropicalFishGroupData
+ XXX.entity.animal.TropicalFish$Variant
- XXX.entity.animal.Turtle
+ XXX.entity.animal.Turtle$TurtleBreedGoal
- XXX.entity.animal.Turtle$TurtleGoHomeGoal
+ XXX.entity.animal.Turtle$TurtleGoToWaterGoal
- XXX.entity.animal.Turtle$TurtleLayEggGoal
+ XXX.entity.animal.Turtle$TurtleMoveControl
- XXX.entity.animal.Turtle$TurtlePanicGoal
+ XXX.entity.animal.Turtle$TurtlePathNavigation
- XXX.entity.animal.Turtle$TurtleRandomStrollGoal
+ XXX.entity.animal.Turtle$TurtleTravelGoal
- XXX.entity.animal.WaterAnimal
+ XXX.entity.animal.Wolf
- XXX.entity.animal.Wolf$WolfAvoidEntityGoal
+ XXX.entity.animal.Wolf$WolfPanicGoal
- XXX.entity.monster.package-info
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
- XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$FailureItemListing
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerTrades$TypeSpecificTrade
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Inventory
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.jfr.callback.package-info
+ XXX.jfr.callback.ProfiledDuration
+ XXX.jfr.event.ChunkGenerationEvent
- XXX.jfr.event.ChunkGenerationEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent
- XXX.jfr.event.NetworkSummaryEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent$SumAggregation
+ XXX.jfr.event.package-info
- XXX.jfr.event.PacketEvent
+ XXX.jfr.event.PacketEvent$Fields
- XXX.jfr.event.PacketReceivedEvent
+ XXX.jfr.event.PacketSentEvent
- XXX.jfr.event.ServerTickTimeEvent
+ XXX.jfr.event.ServerTickTimeEvent$Fields
- XXX.jfr.event.WorldLoadFinishedEvent
+ XXX.jfr.parse.JfrStatsParser
- XXX.jfr.parse.JfrStatsParser$1
+ XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
- XXX.jfr.parse.JfrStatsResult
+ XXX.jfr.parse.package-info
- XXX.jfr.serialize.JfrResultJsonSerializer
+ XXX.jfr.serialize.package-info
- XXX.jfr.stats.ChunkGenStat
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.NetworkPacketSummary
- XXX.jfr.stats.NetworkPacketSummary$PacketCountAndSize
+ XXX.jfr.stats.NetworkPacketSummary$PacketIdentification
+ XXX.jfr.stats.package-info
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
- XXX.level.block.BonemealableBlock$1
+ XXX.level.gameevent.GameEventListener$Holder
- XXX.level.gameevent.GameEventListener$Provider
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelDataAndDimensions
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelSummary$CorruptedLevelSummary
+ XXX.level.storage.LevelSummary$SymlinkLevelSummary
- XXX.level.storage.LevelVersion
- XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$Event
+ XXX.level.validation.ContentValidationException
- XXX.level.validation.DirectoryValidator
+ XXX.level.validation.DirectoryValidator$1
- XXX.level.validation.ForbiddenSymlinkInfo
- XXX.level.validation.package-info
+ XXX.level.validation.PathAllowList
- XXX.level.validation.PathAllowList$ConfigEntry
+ XXX.level.validation.PathAllowList$EntryType
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaType
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Path
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FunctionReference
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.package-info
+ XXX.loot.functions.SequenceFunction
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetInstrumentFunction
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetPotionFunction
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$EffectEntry
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.packs.package-info
- XXX.loot.packs.TradeRebalanceChestLoot
+ XXX.loot.packs.TradeRebalanceLootTableProvider
- XXX.loot.packs.UpdateOneTwentyOneBlockLoot
+ XXX.loot.packs.UpdateOneTwentyOneChestLoot
- XXX.loot.packs.UpdateOneTwentyOneLootTableProvider
+ XXX.loot.packs.VanillaArchaeologyLoot
- XXX.loot.packs.VanillaBlockLoot
+ XXX.loot.packs.VanillaChestLoot
- XXX.loot.packs.VanillaEntityLoot
+ XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaGiftLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
+ XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AllOfCondition
- XXX.loot.predicates.AllOfCondition$Builder
+ XXX.loot.predicates.AnyOfCondition
- XXX.loot.predicates.AnyOfCondition$Builder
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.CompositeLootItemCondition
+ XXX.loot.predicates.CompositeLootItemCondition$Builder
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.MatchTool
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
+ XXX.metrics.profiling.ActiveMetricsRecorder
- XXX.metrics.profiling.InactiveMetricsRecorder
+ XXX.metrics.profiling.MetricsRecorder
- XXX.metrics.profiling.package-info
- XXX.metrics.profiling.ProfilerSamplerAdapter
+ XXX.metrics.profiling.ServerMetricsSamplersProvider
- XXX.metrics.profiling.ServerMetricsSamplersProvider$1
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ XXX.metrics.storage.MetricsPersister
+ XXX.metrics.storage.package-info
- XXX.metrics.storage.RecordedDeviation
- XXX.minecraft.core.package-info
+ XXX.minecraft.data.BlockFamilies
- XXX.minecraft.data.BlockFamily
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.CachedOutput
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataGenerator$PackGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.DataProvider$Factory
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.HashCache$CacheUpdater
- XXX.minecraft.data.HashCache$ProviderCache
+ XXX.minecraft.data.HashCache$ProviderCacheBuilder
- XXX.minecraft.data.HashCache$UpdateFunction
+ XXX.minecraft.data.HashCache$UpdateResult
- XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
+ XXX.minecraft.data.PackOutput
- XXX.minecraft.data.PackOutput$PathProvider
+ XXX.minecraft.data.PackOutput$Target
- XXX.minecraft.util.package-info
- XXX.minecraft.world.BossEvent
+ XXX.minecraft.world.BossEvent$BossBarColor
- XXX.minecraft.world.BossEvent$BossBarOverlay
+ XXX.minecraft.world.Clearable
- XXX.minecraft.world.CompoundContainer
+ XXX.minecraft.world.Container
- XXX.minecraft.world.ContainerHelper
+ XXX.minecraft.world.ContainerListener
- XXX.minecraft.world.Containers
+ XXX.minecraft.world.Difficulty
- XXX.minecraft.world.DifficultyInstance
+ XXX.minecraft.world.InteractionHand
- XXX.minecraft.world.InteractionResult
+ XXX.minecraft.world.InteractionResultHolder
- XXX.minecraft.world.ItemInteractionResult
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
+ XXX.minecraft.world.package-info
- XXX.minecraft.world.RandomizableContainer
+ XXX.minecraft.world.RandomSequence
- XXX.minecraft.world.RandomSequences
+ XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.TickRateManager
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$Operation
+ XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C2
+ XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C4
+ XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyDispatch$PentaFunction
+ XXX.models.blockstates.PropertyDispatch$QuadFunction
- XXX.models.blockstates.PropertyDispatch$TriFunction
+ XXX.models.blockstates.Selector
- XXX.models.blockstates.Variant
+ XXX.models.blockstates.VariantProperties
- XXX.models.blockstates.VariantProperties$Rotation
+ XXX.models.blockstates.VariantProperty
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
+ XXX.models.model.ModelLocationUtils
- XXX.models.model.ModelTemplate
+ XXX.models.model.ModelTemplate$JsonFactory
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
- XXX.monster.breeze.BreezeUtil
+ XXX.monster.breeze.LongJump
+ XXX.monster.breeze.package-info
- XXX.monster.breeze.Shoot
+ XXX.monster.breeze.ShootWhenStuck
- XXX.monster.breeze.Slide
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.AbstractPiglin
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.PiglinArmPose
+ XXX.monster.piglin.PiglinBrute
- XXX.monster.piglin.PiglinBruteAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- XXX.monster.warden.AngerLevel
+ XXX.monster.warden.AngerManagement
- XXX.monster.warden.AngerManagement$1
+ XXX.monster.warden.AngerManagement$Sorter
+ XXX.monster.warden.package-info
- XXX.monster.warden.Warden
+ XXX.monster.warden.Warden$1
- XXX.monster.warden.Warden$1$1
+ XXX.monster.warden.Warden$2
- XXX.monster.warden.Warden$VibrationUser
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenSpawnTracker
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$1
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.profiling.jfr.Environment
+ XXX.profiling.jfr.JfrProfiler
- XXX.profiling.jfr.JfrProfiler$1
+ XXX.profiling.jfr.JvmProfiler
- XXX.profiling.jfr.JvmProfiler$NoOpProfiler
- XXX.profiling.jfr.package-info
+ XXX.profiling.jfr.Percentiles
- XXX.profiling.jfr.SummaryReporter
- XXX.profiling.metrics.MetricCategory
+ XXX.profiling.metrics.MetricSampler
- XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ XXX.profiling.metrics.MetricSampler$SamplerResult
- XXX.profiling.metrics.MetricSampler$ThresholdTest
+ XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- XXX.profiling.metrics.MetricsRegistry
+ XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- XXX.profiling.metrics.MetricsSamplerProvider
- XXX.profiling.metrics.package-info
+ XXX.profiling.metrics.ProfilerMeasured
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.ConstantValue
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.UniformGenerator
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.providers.score.LootScoreProviderType
+ XXX.providers.score.package-info
+ XXX.providers.score.ScoreboardNameProvider
- XXX.providers.score.ScoreboardNameProviders
- XXX.recipes.packs.BundleRecipeProvider
- XXX.recipes.packs.package-info
+ XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$VisitedEntry
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootDataId
+ XXX.storage.loot.LootDataManager
- XXX.storage.loot.LootDataManager$1
+ XXX.storage.loot.LootDataResolver
- XXX.storage.loot.LootDataType
+ XXX.storage.loot.LootDataType$Validator
- XXX.storage.loot.LootParams
+ XXX.storage.loot.LootParams$Builder
- XXX.storage.loot.LootParams$DynamicDrop
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.package-info
+ XXX.storage.loot.ValidationContext
- XXX.util.eventlog.EventLogDirectory
+ XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$File
+ XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$FileList
+ XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog
+ XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader
+ XXX.util.eventlog.JsonEventLogReader$1
- XXX.util.eventlog.package-info
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$PathEntry
+ XXX.util.profiling.ContinuousProfiler
- XXX.util.profiling.EmptyProfileResults
+ XXX.util.profiling.FilledProfileResults
- XXX.util.profiling.FilledProfileResults$1
+ XXX.util.profiling.FilledProfileResults$CounterCollector
- XXX.util.profiling.InactiveProfiler
- XXX.util.profiling.package-info
+ XXX.util.profiling.ProfileCollector
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$1
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
+ XXX.util.random.package-info
+ XXX.util.random.SimpleWeightedRandomList
- XXX.util.random.SimpleWeightedRandomList$Builder
+ XXX.util.random.Weight
- XXX.util.random.WeightedEntry
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedEntry$Wrapper
+ XXX.util.random.WeightedRandom
- XXX.util.random.WeightedRandomList
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
- XXX.util.thread.ProcessorHandle
+ XXX.util.thread.ProcessorHandle$1
- XXX.util.thread.ProcessorMailbox
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$IntRunnable
+ XXX.util.thread.StrictQueue$QueueStrictQueue
+ XXX.util.valueproviders.BiasedToBottomInt
- XXX.util.valueproviders.ClampedInt
+ XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ClampedNormalInt
+ XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.ConstantInt
+ XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.FloatProviderType
+ XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.MultipliedFloats
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.SampledFloat
+ XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformFloat
+ XXX.util.valueproviders.UniformInt
- XXX.util.valueproviders.WeightedListInt
+ XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
- XXX.village.poi.PoiTypes
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageEffects
- XXX.world.damagesource.DamageScaling
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.DamageSource$1
+ XXX.world.damagesource.DamageSources
- XXX.world.damagesource.DamageType
+ XXX.world.damagesource.DamageTypes
- XXX.world.damagesource.DeathMessageType
+ XXX.world.damagesource.FallLocation
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsorptionMobEffect
- XXX.world.effect.MobEffectInstance$BlendState
+ XXX.world.effect.MobEffectInstance$FactorData
- XXX.world.entity.EntityAttachment$Fallback
- XXX.world.entity.EntityAttachments$Builder
- XXX.world.entity.package-info
- XXX.world.item.AnimalArmorItem
- XXX.world.item.BoneMealItem$1
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$Builder
- XXX.world.item.CreativeModeTab$DisplayItemsGenerator
+ XXX.world.item.CreativeModeTab$ItemDisplayBuilder
- XXX.world.item.CreativeModeTab$ItemDisplayParameters
+ XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTab$Row
+ XXX.world.item.CreativeModeTab$TabVisibility
- XXX.world.item.CreativeModeTab$Type
+ XXX.world.item.CreativeModeTabs
- XXX.world.item.CrossbowItem
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeableAnimalArmorItem
+ XXX.world.item.DyeableHorseArmorItem
- XXX.world.item.DyeableLeatherItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.ElytraItem
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EnchantedBookItem
+ XXX.world.item.EnchantedGoldenAppleItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.Equipable
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.HorseArmorItem
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.scores.DisplaySlot
- XXX.world.scores.DisplaySlot$1
+ XXX.world.scores.Objective
+ XXX.world.scores.package-info
- XXX.world.scores.PlayerScoreEntry
+ XXX.world.scores.PlayerScores
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.ReadOnlyScoreInfo
- XXX.world.scores.Score
+ XXX.world.scores.ScoreAccess
- XXX.world.scores.Scoreboard
+ XXX.world.scores.Scoreboard$1
- XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.ScoreHolder
+ XXX.world.scores.ScoreHolder$1
- XXX.world.scores.ScoreHolder$2
+ XXX.world.scores.ScoreHolder$3
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
- XXX.world.ticks.BlackholeTickAccess
+ XXX.world.ticks.BlackholeTickAccess$1
- XXX.world.ticks.BlackholeTickAccess$2
+ XXX.world.ticks.ContainerSingleItem
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.ItemPredicate$Builder +1M -1M
```
```
XXX.commands.functions.FunctionBuilder +1M -1M
```
```
XXX.commands.functions.MacroFunction +2M -3M
```
```
XXX.commands.functions.MacroFunction$MacroEntry +2M -3M | +1P
```
```
XXX.commands.functions.PlainTextFunction +1M -1M
```
```
XXX.minecraft.core.Holder$Direct +1M
```
```
XXX.minecraft.core.Holder$Reference +1M
```
```
XXX.minecraft.core.MappedRegistry +1M
```
```
XXX.minecraft.core.Registry +1P
```
```
XXX.core.cauldron.CauldronInteraction +15M -15M | +1P -1P
```
```
XXX.protocol.game.ClientboundRemoveMobEffectPacket +6M -2M | +1P -1P
```
```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +3M -5M | +2P -2P
```
```
XXX.protocol.game.DebugPackets +2M -1M
```
```
XXX.protocol.game.ServerboundSetBeaconPacket +9M -6M
```
```
XXX.network.syncher.EntityDataSerializers +1P
```
```
XXX.server.level.WorldGenRegion +1M -1M
```
```
XXX.minecraft.sounds.SoundEvents +15P
```
```
XXX.minecraft.util.TimeUtil +1P
```
```
XXX.datafix.fixes.BlockRenameFix$1 +1M -1M | +1P -1P
```
```
XXX.world.effect.BadOmenMobEffect +1M -1M
```
```
XXX.world.effect.HungerMobEffect +1M -1M
```
```
XXX.world.effect.MobEffect +6M -7M | +1P -2P
```
```
XXX.world.effect.MobEffects +2M -2M | +33P -33P
```
```
XXX.world.effect.RegenerationMobEffect +1M -1M
```
```
XXX.world.effect.WitherMobEffect +1M -1M
```
```
XXX.world.entity.Entity +7M -9M | +1P -2P
```
```
XXX.world.entity.LivingEntity +8M -11M | +2P -1P
```
```
XXX.world.entity.Mob +1M
```
```
XXX.world.entity.PathfinderMob -1M
```
```
XXX.ai.attributes.AttributeInstance +4M -2M | +1P -1P
```
```
XXX.ai.attributes.AttributeSupplier +7M -7M
```
```
XXX.ai.attributes.Attributes +2M -1M | +18P -14P
```
```
XXX.ai.goal.GoalSelector +1M -3M | -3P
```
```
XXX.ai.memory.MemoryModuleType +2P
```
```
XXX.animal.axolotl.Axolotl -1M
```
```
XXX.animal.goat.Goat +1M -2M
```
```
XXX.animal.horse.Horse +1M | +1P
```
```
XXX.animal.horse.Llama +2M -1M | +1P
```
```
XXX.animal.horse.ZombieHorse +2M -1M | +1P
```
```
XXX.boss.enderdragon.EnderDragon -1M
```
```
XXX.entity.decoration.ItemFrame -1M
```
```
XXX.entity.item.PrimedTnt -1M
```
```
XXX.entity.monster.AbstractIllager -2M
```
```
XXX.entity.monster.Drowned +1M
```
```
XXX.entity.monster.EnderMan -2M
```
```
XXX.entity.monster.Ghast -3M
```
```
XXX.entity.monster.Guardian -2M
```
```
XXX.entity.monster.Husk -1M
```
```
XXX.entity.monster.Phantom +1M -4M
```
```
XXX.entity.monster.Ravager -1M
```
```
XXX.entity.monster.Silverfish -2M
```
```
XXX.entity.monster.Slime +2M -3M
```
```
XXX.entity.monster.Spider +1M -3M
```
```
XXX.entity.monster.Spider$SpiderEffectsGroupData +1P -1P
```
```
XXX.entity.monster.Vex -3M
```
```
XXX.entity.monster.Witch -2M
```
```
XXX.entity.monster.Zoglin -1M
```
```
XXX.entity.monster.ZombieVillager -1M
```
```
XXX.monster.breeze.Breeze +2M -2M | +4P
```
```
XXX.monster.breeze.BreezeAi +3M -1M
```
```
XXX.entity.projectile.AbstractArrow +1M -2M
```
```
XXX.entity.projectile.Arrow +1P -1P
```
```
XXX.entity.projectile.ThrownPotion +1M -1M
```
```
XXX.entity.projectile.WindCharge -1M
```
```
XXX.entity.vehicle.AbstractMinecart +1M -1M | +1P -2P
```
```
XXX.entity.vehicle.Boat +1M -2M
```
```
XXX.world.item.Items +4P -1P
```
```
XXX.world.item.LeadItem +1M
```
```
XXX.world.item.WritableBookItem -1M
```
```
XXX.item.alchemy.Potion +2M -3M | +1P -2P
```
```
XXX.item.alchemy.PotionBrewing$Mix +7M -1M | +2P -2P
```
```
XXX.item.alchemy.Potions +3M -2M | +43P -43P
```
```
XXX.level.block.BeaconBlock +1M -1M
```
```
XXX.level.block.BrewingStandBlock +1M -1M
```
```
XXX.level.block.ButtonBlock +1M -1M
```
```
XXX.level.block.CandleBlock +1M -1M
```
```
XXX.level.block.CartographyTableBlock +1M -1M
```
```
XXX.level.block.CaveVinesBlock +1M -1M
```
```
XXX.level.block.CeilingHangingSignBlock +1M -1M
```
```
XXX.level.block.CommandBlock +1M -1M
```
```
XXX.level.block.ComposterBlock +2M -1M
```
```
XXX.level.block.DaylightDetectorBlock +1M -1M
```
```
XXX.level.block.DecoratedPotBlock +2M -1M
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.DragonEggBlock +1M -1M
```
```
XXX.level.block.EnderChestBlock +2M -2M
```
```
XXX.level.block.FenceBlock +2M -1M
```
```
XXX.level.block.FletchingTableBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock +5M -1M
```
```
XXX.level.block.GrassBlock +1M
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.LecternBlock +2M -1M
```
```
XXX.level.block.LevelEvent +2P -1P
```
```
XXX.level.block.MossBlock +1M
```
```
XXX.level.block.NoteBlock +2M -1M
```
```
XXX.level.block.RedStoneOreBlock +1M -1M
```
```
XXX.level.block.RepeaterBlock +1M -1M
```
```
XXX.level.block.SmithingTableBlock +1M -1M
```
```
XXX.level.block.StructureBlock +1M -1M
```
```
XXX.level.block.SweetBerryBushBlock +2M -1M
```
```
XXX.level.block.TntBlock +2M -2M
```
```
XXX.level.block.TrapDoorBlock +1M -1M
```
```
XXX.level.block.WallHangingSignBlock +1M -1M
```
```
XXX.block.entity.BeaconBlockEntity +5M -4M | +3P -3P
```
```
XXX.block.entity.SculkCatalystBlockEntity$CatalystListener +1M -1M
```
```
XXX.block.entity.SculkSensorBlockEntity$VibrationUser +2M -2M
```
```
XXX.block.entity.SculkShriekerBlockEntity$VibrationUser +2M -2M
```
```
XXX.block.state.BlockBehaviour +2M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M -1M
```
```
XXX.level.gameevent.EuclideanGameEventListenerRegistry +1M -1M
```
```
XXX.level.gameevent.GameEvent +6M -5M | +60P -61P
```
```
XXX.level.gameevent.GameEvent$ListenerInfo +2M -2M | +1P -1P
```
```
XXX.level.gameevent.GameEventListener +1P -1P
```
```
XXX.level.gameevent.GameEventListenerRegistry$1 +1M -1M
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemPredicate$Builder
</summary>

```diff
- ItemPredicate$Builder isPotion(Holder)
+ ItemPredicate$Builder isPotion(Potion)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.FunctionBuilder
</summary>

```diff
- void addMacro(String,int,ExecutionCommandSource)
+ void addMacro(String,int)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.MacroFunction
</summary>

```diff
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,ExecutionCommandSource)
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,Object)
- InstantiatedFunction instantiate(CompoundTag,CommandDispatcher)
+ InstantiatedFunction substituteAndParse(List,List,CommandDispatcher,ExecutionCommandSource)
- InstantiatedFunction substituteAndParse(List,List,CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.MacroFunction$MacroEntry
</summary>

```diff
+ UnboundEntryAction instantiate(List,CommandDispatcher,ExecutionCommandSource,ResourceLocation)
+ UnboundEntryAction instantiate(List,CommandDispatcher,Object,ResourceLocation)
- UnboundEntryAction instantiate(List,CommandDispatcher,ResourceLocation)
- void <init>(StringTemplate,IntList,ExecutionCommandSource)
+ void <init>(StringTemplate,IntList)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.PlainTextFunction
</summary>

```diff
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,Object)
- InstantiatedFunction instantiate(CompoundTag,CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.core.Holder$Direct
</summary>

```diff
- boolean is(Holder)
```

</details>
<details>
<summary>
net.minecraft.core.Holder$Reference
</summary>

```diff
- boolean is(Holder)
```

</details>
<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
- Optional getHolder(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.core.cauldron.CauldronInteraction
</summary>

```diff
+ InteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
+ InteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
+ InteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
- ItemInteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
- ItemInteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
</summary>

```diff
- boolean equals(Object)
- Holder effect()
- int entityId()
- int hashCode()
+ MobEffect getEffect()
- String toString()
- void <init>(int,Holder)
+ void <init>(int,MobEffect)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
</summary>

```diff
- boolean shouldBlend()
- Holder getEffect()
+ MobEffect getEffect()
+ MobEffectInstance$FactorData getFactorData()
+ MobEffectInstance$FactorData lambda$new$0(FriendlyByteBuf)
- void <init>(int,MobEffectInstance,boolean)
+ void <init>(int,MobEffectInstance)
+ void lambda$write$1(FriendlyByteBuf,MobEffectInstance$FactorData)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.DebugPackets
</summary>

```diff
- void lambda$sendGameEventInfo$7(ServerLevel,Vec3,ResourceKey)
+ void sendGameEventInfo(Level,GameEvent,Vec3)
- void sendGameEventInfo(Level,Holder,Vec3)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
</summary>

```diff
- boolean equals(Object)
- Holder lambda$new$0(FriendlyByteBuf)
- Holder lambda$new$1(FriendlyByteBuf)
- int hashCode()
+ MobEffect lambda$new$0(FriendlyByteBuf)
+ MobEffect lambda$new$1(FriendlyByteBuf)
+ Optional getPrimary()
+ Optional getSecondary()
- Optional primary()
- Optional secondary()
- String toString()
- void lambda$write$2(FriendlyByteBuf,Holder)
+ void lambda$write$2(FriendlyByteBuf,MobEffect)
- void lambda$write$3(FriendlyByteBuf,Holder)
+ void lambda$write$3(FriendlyByteBuf,MobEffect)
```

</details>
<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
+ void gameEvent(GameEvent,Vec3,GameEvent$Context)
- void gameEvent(Holder,Vec3,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockRenameFix$1
</summary>

```diff
+ String fixBlock(String)
- String renameBlock(String)
```

</details>
<details>
<summary>
net.minecraft.world.effect.BadOmenMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.HungerMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ Holder$Reference builtInRegistryHolder()
- int getBlendDurationTicks()
+ Map getAttributeModifiers()
+ MobEffect addAttributeModifier(Attribute,String,double,AttributeModifier$Operation)
- MobEffect addAttributeModifier(Holder,String,double,AttributeModifier$Operation)
- MobEffect setBlendDuration(int)
+ MobEffect setFactorDataFactory(Supplier)
+ MobEffectInstance$FactorData lambda$new$0()
+ Optional createFactorData()
+ void applyEffectTick(LivingEntity,int)
- void createModifiers(int,BiConsumer)
- void lambda$createModifiers$0(BiConsumer,int,Holder,MobEffect$AttributeTemplate)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffects
</summary>

```diff
- Holder bootstrap(Registry)
- Holder register(String,MobEffect)
+ MobEffect register(String,MobEffect)
+ MobEffectInstance$FactorData lambda$static$0()
```

</details>
<details>
<summary>
net.minecraft.world.effect.RegenerationMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.WitherMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ BlockState getFeetBlockState()
- BlockState getInBlockState()
+ float getEyeHeight(Pose,EntityDimensions)
+ float getMyRidingOffset(Entity)
+ float getNameTagOffsetY()
+ float ridingOffset(Entity)
- Vec3 getDefaultPassengerAttachmentPoint(Entity,Entity,EntityAttachments)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
- Vec3 getVehicleAttachmentPoint(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ void gameEvent(GameEvent,Entity)
+ void gameEvent(GameEvent)
- void gameEvent(Holder,Entity)
- void gameEvent(Holder)
- void playProjectileDeflectionSound(Projectile)
+ void setMaxUpStep(float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ AttributeInstance getAttribute(Attribute)
- AttributeInstance getAttribute(Holder)
- boolean hasEffect(Holder)
+ boolean hasEffect(MobEffect)
- boolean removeEffect(Holder)
+ boolean removeEffect(MobEffect)
+ double getAttributeBaseValue(Attribute)
+ double getAttributeValue(Attribute)
- EntityDimensions getDefaultDimensions(Pose)
- float getAgeScale()
+ float getEyeHeight(Pose,EntityDimensions)
+ float getMyRidingOffset(Entity)
+ float getStandingEyeHeight(Pose,EntityDimensions)
- MobEffectInstance getEffect(Holder)
+ MobEffectInstance getEffect(MobEffect)
- MobEffectInstance removeEffectNoUpdate(Holder)
+ MobEffectInstance removeEffectNoUpdate(MobEffect)
+ void onAttributeUpdated(Attribute)
- void onAttributeUpdated(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- void stopInPlace()
```

</details>
<details>
<summary>
net.minecraft.world.entity.PathfinderMob
</summary>

```diff
+ boolean lambda$isPanicking$0(WrappedGoal)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeInstance
</summary>

```diff
+ Attribute getAttribute()
- Holder getAttribute()
- IllegalStateException lambda$save$2()
+ void <init>(Attribute,Consumer)
- void <init>(Holder,Consumer)
- void addOrUpdateTransientModifier(AttributeModifier)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeSupplier
</summary>

```diff
+ AttributeInstance createInstance(Consumer,Attribute)
- AttributeInstance createInstance(Consumer,Holder)
+ AttributeInstance getAttributeInstance(Attribute)
- AttributeInstance getAttributeInstance(Holder)
+ boolean hasAttribute(Attribute)
- boolean hasAttribute(Holder)
+ boolean hasModifier(Attribute,UUID)
- boolean hasModifier(Holder,UUID)
+ double getBaseValue(Attribute)
- double getBaseValue(Holder)
+ double getModifierValue(Attribute,UUID)
- double getModifierValue(Holder,UUID)
+ double getValue(Attribute)
- double getValue(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.Attributes
</summary>

```diff
+ Attribute register(String,Attribute)
- Holder bootstrap(Registry)
- Holder register(String,Attribute)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.GoalSelector
</summary>

```diff
+ boolean lambda$removeGoal$2(Goal,WrappedGoal)
- boolean lambda$tick$2(Map$Entry)
+ Stream getRunningGoals()
+ void setNewGoalRate(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.axolotl.Axolotl
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.goat.Goat
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.ZombieHorse
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ float getPassengersRidingOffsetY(EntityDimensions,float)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
```

</details>
<details>
<summary>
net.minecraft.world.entity.item.PrimedTnt
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.AbstractIllager
</summary>

```diff
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Drowned
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.EnderMan
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ghast
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Guardian
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Husk
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ravager
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Silverfish
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Spider
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
- Vec3 getVehicleAttachmentPoint(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Vex
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Witch
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.ZombieVillager
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.breeze.Breeze
</summary>

```diff
+ boolean withinMiddleCircleRange(Vec3)
+ boolean withinOuterCircleRange(Vec3)
- void playProjectileDeflectionSound(Projectile)
- void playWhirlSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.breeze.BreezeAi
</summary>

```diff
+ Optional lambda$initFightActivity$0(Breeze)
- Optional lambda$initIdleActivity$0(Breeze)
- void initIdleActivity(Brain)
- void updateActivity(Breeze)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
+ void deflect()
- void deflect(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownPotion
</summary>

```diff
- void makeAreaOfEffectCloud(ItemStack,Holder)
+ void makeAreaOfEffectCloud(ItemStack,Potion)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.WindCharge
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecart
</summary>

```diff
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.Boat
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.item.LeadItem
</summary>

```diff
- boolean lambda$bindPlayerMobs$0(Player,Mob)
```

</details>
<details>
<summary>
net.minecraft.world.item.WritableBookItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.Potion
</summary>

```diff
- Holder byName(String)
+ Holder$Reference builtInRegistryHolder()
+ Potion byName(String)
- String getName(Holder,String)
+ String getName(String)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.PotionBrewing$Mix
</summary>

```diff
- boolean equals(Object)
- Holder from()
- Holder to()
- Ingredient ingredient()
- int hashCode()
- String toString()
- void <init>(Holder,Ingredient,Holder)
+ void <init>(Object,Ingredient,Object)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.Potions
</summary>

```diff
- Holder bootstrap(Registry)
- Holder register(ResourceKey,Potion)
- Holder register(String,Potion)
+ Potion register(ResourceKey,Potion)
+ Potion register(String,Potion)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CartographyTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CaveVinesBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CeilingHangingSignBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CommandBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ComposterBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DaylightDetectorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DecoratedPotBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DragonEggBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ AbstractContainerMenu lambda$use$1(PlayerEnderChestContainer,int,Inventory,Player)
- AbstractContainerMenu lambda$useWithoutItem$1(PlayerEnderChestContainer,int,Inventory,Player)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FletchingTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
- boolean lambda$useWithoutItem$2(Player,InteractionHand)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- void lambda$useWithoutItem$3(Player,ItemStack,InteractionHand)
- void lambda$useWithoutItem$4(Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrassBlock
</summary>

```diff
- BonemealableBlock$Type getType()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.MossBlock
</summary>

```diff
- BonemealableBlock$Type getType()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NoteBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RedStoneOreBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RepeaterBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SmithingTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SweetBerryBushBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TntBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ void lambda$use$0(InteractionHand,Player)
- void lambda$useItemOn$0(InteractionHand,Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TrapDoorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WallHangingSignBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BeaconBlockEntity
</summary>

```diff
- Holder filterEffect(Holder)
- Holder loadEffect(CompoundTag,String)
+ MobEffect filterEffect(MobEffect)
+ MobEffect loadEffect(CompoundTag,String)
- void applyEffects(Level,BlockPos,int,Holder,Holder)
+ void applyEffects(Level,BlockPos,int,MobEffect,MobEffect)
- void lambda$storeEffect$0(CompoundTag,String,ResourceKey)
- void storeEffect(CompoundTag,String,Holder)
+ void storeEffect(CompoundTag,String,MobEffect)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
</summary>

```diff
+ boolean handleGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- boolean handleGameEvent(ServerLevel,Holder,GameEvent$Context,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
</summary>

```diff
+ boolean canReceiveVibration(ServerLevel,BlockPos,GameEvent,GameEvent$Context)
- boolean canReceiveVibration(ServerLevel,BlockPos,Holder,GameEvent$Context)
+ void onReceiveVibration(ServerLevel,BlockPos,GameEvent,Entity,Entity,float)
- void onReceiveVibration(ServerLevel,BlockPos,Holder,Entity,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
</summary>

```diff
+ boolean canReceiveVibration(ServerLevel,BlockPos,GameEvent,GameEvent$Context)
- boolean canReceiveVibration(ServerLevel,BlockPos,Holder,GameEvent$Context)
+ void onReceiveVibration(ServerLevel,BlockPos,GameEvent,Entity,Entity,float)
- void onReceiveVibration(ServerLevel,BlockPos,Holder,Entity,Entity,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
+ InteractionResult use(Level,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(Level,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,Level,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
</summary>

```diff
+ boolean visitInRangeListeners(GameEvent,Vec3,GameEvent$Context,GameEventListenerRegistry$ListenerVisitor)
- boolean visitInRangeListeners(Holder,Vec3,GameEvent$Context,GameEventListenerRegistry$ListenerVisitor)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.GameEvent
</summary>

```diff
- boolean equals(Object)
+ boolean is(TagKey)
+ GameEvent register(String,int)
+ GameEvent register(String)
- Holder bootstrap(Registry)
+ Holder$Reference builtInRegistryHolder()
- Holder$Reference register(String,int)
- Holder$Reference register(String)
+ int getNotificationRadius()
- int hashCode()
- int notificationRadius()
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
</summary>

```diff
+ GameEvent gameEvent()
- Holder gameEvent()
+ void <init>(GameEvent,Vec3,GameEvent$Context,GameEventListener,Vec3)
- void <init>(Holder,Vec3,GameEvent$Context,GameEventListener,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
</summary>

```diff
+ boolean visitInRangeListeners(GameEvent,Vec3,GameEvent$Context,GameEventListenerRegistry$ListenerVisitor)
- boolean visitInRangeListeners(Holder,Vec3,GameEvent$Context,GameEventListenerRegistry$ListenerVisitor)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.advancements.packs.package-info
+ XXX.advancements.packs.UpdateOneTwentyOneAdvancementProvider
- XXX.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaAdventureAdvancements
+ XXX.advancements.packs.VanillaHusbandryAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
+ XXX.advancements.packs.VanillaStoryAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestItemSensor
- XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.NearestVisibleLivingEntitySensor
+ XXX.ai.sensing.package-info
- XXX.ai.sensing.PiglinBruteSpecificSensor
+ XXX.ai.sensing.PiglinSpecificSensor
- XXX.ai.sensing.PlayerSensor
+ XXX.ai.sensing.SecondaryPoiSensor
- XXX.ai.sensing.Sensing
+ XXX.ai.sensing.Sensor
- XXX.ai.sensing.SensorType
+ XXX.ai.sensing.TemptingSensor
- XXX.ai.sensing.VillagerBabiesSensor
+ XXX.ai.sensing.VillagerHostilesSensor
- XXX.ai.sensing.WardenEntitySensor
+ XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
- XXX.ai.util.AirAndWaterRandomPos
+ XXX.ai.util.AirRandomPos
- XXX.ai.util.DefaultRandomPos
+ XXX.ai.util.GoalUtils
- XXX.ai.util.HoverRandomPos
+ XXX.ai.util.LandRandomPos
+ XXX.ai.util.package-info
- XXX.ai.util.RandomPos
- XXX.ai.village.package-info
- XXX.ai.village.ReputationEventType
+ XXX.ai.village.ReputationEventType$1
- XXX.ai.village.VillageSiege
+ XXX.ai.village.VillageSiege$State
+ XXX.animal.allay.Allay
- XXX.animal.allay.Allay$JukeboxListener
+ XXX.animal.allay.Allay$VibrationUser
- XXX.animal.allay.AllayAi
+ XXX.animal.allay.package-info
- XXX.animal.armadillo.Armadillo
- XXX.animal.armadillo.Armadillo$2
- XXX.animal.armadillo.ArmadilloAi
- XXX.animal.armadillo.ArmadilloAi$ArmadilloBallUp
- XXX.animal.armadillo.package-info
- XXX.animation.definitions.ArmadilloAnimation
+ XXX.animation.definitions.BatAnimation
- XXX.animation.definitions.BreezeAnimation
+ XXX.animation.definitions.CamelAnimation
- XXX.animation.definitions.FrogAnimation
+ XXX.animation.definitions.package-info
+ XXX.animation.definitions.SnifferAnimation
- XXX.animation.definitions.WardenAnimation
- XXX.client.animation.package-info
- XXX.client.gui.ComponentPath
+ XXX.client.gui.ComponentPath$Leaf
- XXX.client.gui.ComponentPath$Path
+ XXX.client.gui.Font
- XXX.client.gui.Font$DisplayMode
+ XXX.client.gui.Font$StringRenderOutput
- XXX.client.gui.Gui
+ XXX.client.gui.Gui$1DisplayEntry
- XXX.client.gui.Gui$HeartType
+ XXX.client.gui.GuiGraphics
- XXX.client.gui.GuiGraphics$ScissorStack
+ XXX.client.gui.GuiSpriteManager
- XXX.client.gui.LayeredDraw
- XXX.client.gui.MapRenderer
+ XXX.client.gui.MapRenderer$MapInstance
+ XXX.client.gui.package-info
- XXX.client.model.ArmadilloModel
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.AxolotlModel
+ XXX.client.model.BatModel
- XXX.client.model.BeeModel
+ XXX.client.model.BlazeModel
- XXX.client.model.BoatModel
+ XXX.client.model.BookModel
- XXX.client.model.BreezeModel
+ XXX.client.model.CamelModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestBoatModel
+ XXX.client.model.ChestedHorseModel
- XXX.client.model.ChestRaftModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColorableAgeableListModel
+ XXX.client.model.ColorableHierarchicalModel
- XXX.client.model.CowModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FoxModel
- XXX.client.model.FrogModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GoatModel
- XXX.client.model.GuardianModel
+ XXX.client.model.HeadedModel
- XXX.client.model.HierarchicalModel
+ XXX.client.model.HoglinModel
- XXX.client.model.HorseModel
+ XXX.client.model.HumanoidArmorModel
- XXX.client.model.HumanoidModel
+ XXX.client.model.HumanoidModel$1
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.ListModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
- XXX.client.model.MinecartModel
+ XXX.client.model.Model
- XXX.client.model.ModelUtils
+ XXX.client.model.OcelotModel
- XXX.client.model.package-info
- XXX.client.model.PandaModel
+ XXX.client.model.ParrotModel
- XXX.client.model.ParrotModel$1
+ XXX.client.model.ParrotModel$State
- XXX.client.model.PhantomModel
- XXX.client.model.PiglinHeadModel
+ XXX.client.model.PiglinModel
+ XXX.client.model.PigModel
- XXX.client.model.PlayerModel
+ XXX.client.model.PolarBearModel
- XXX.client.model.PufferfishBigModel
+ XXX.client.model.PufferfishMidModel
- XXX.client.model.PufferfishSmallModel
+ XXX.client.model.QuadrupedModel
- XXX.client.model.RabbitModel
+ XXX.client.model.RaftModel
- XXX.client.model.RavagerModel
+ XXX.client.model.SalmonModel
- XXX.client.model.SheepFurModel
+ XXX.client.model.SheepModel
- XXX.client.model.ShieldModel
+ XXX.client.model.ShulkerBulletModel
- XXX.client.model.ShulkerModel
+ XXX.client.model.SilverfishModel
- XXX.client.model.SkeletonModel
+ XXX.client.model.SkullModel
- XXX.client.model.SkullModelBase
+ XXX.client.model.SlimeModel
- XXX.client.model.SnifferModel
+ XXX.client.model.SnowGolemModel
- XXX.client.model.SpiderModel
+ XXX.client.model.SquidModel
- XXX.client.model.StriderModel
+ XXX.client.model.TadpoleModel
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerHeadModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WardenModel
- XXX.client.model.WaterPatchModel
+ XXX.client.model.WindChargeModel
- XXX.client.model.WitchModel
+ XXX.client.model.WitherBossModel
- XXX.client.model.WolfModel
+ XXX.client.model.ZombieModel
- XXX.client.model.ZombieVillagerModel
+ XXX.client.multiplayer.AccountProfileKeyPairManager
- XXX.client.multiplayer.ChunkBatchSizeCalculator
+ XXX.client.multiplayer.ClientAdvancements
- XXX.client.multiplayer.ClientAdvancements$Listener
+ XXX.client.multiplayer.ClientChunkCache
- XXX.client.multiplayer.ClientChunkCache$Storage
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl
- XXX.client.multiplayer.ClientCommonPacketListenerImpl$DeferredPacket
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen
- XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen$PendingRequest
+ XXX.client.multiplayer.ClientConfigurationPacketListenerImpl
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl$State
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientLevel$1
- XXX.client.multiplayer.ClientLevel$ClientLevelData
+ XXX.client.multiplayer.ClientLevel$EntityCallbacks
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientRegistryLayer
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.ClientSuggestionProvider$1
+ XXX.client.multiplayer.CommonListenerCookie
- XXX.client.multiplayer.LegacyServerPinger
+ XXX.client.multiplayer.LegacyServerPinger$Output
- XXX.client.multiplayer.LevelLoadStatusManager
+ XXX.client.multiplayer.LevelLoadStatusManager$1
- XXX.client.multiplayer.LevelLoadStatusManager$Status
+ XXX.client.multiplayer.MultiPlayerGameMode
- XXX.client.multiplayer.PingDebugMonitor
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ProfileKeyPairManager
+ XXX.client.multiplayer.ProfileKeyPairManager$1
- XXX.client.multiplayer.ServerData
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerData$State
+ XXX.color.block.BlockColor
- XXX.color.block.BlockColors
+ XXX.color.block.BlockTintCache
- XXX.color.block.BlockTintCache$CacheData
+ XXX.color.block.BlockTintCache$LatestCacheInfo
- XXX.color.block.package-info
+ XXX.color.item.ItemColor
- XXX.color.item.ItemColors
+ XXX.color.item.package-info
+ XXX.components.debugchart.AbstractDebugChart
- XXX.components.debugchart.BandwidthDebugChart
+ XXX.components.debugchart.FpsDebugChart
- XXX.components.debugchart.PingDebugChart
+ XXX.components.debugchart.TpsDebugChart
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.tabs.GridLayoutTab
- XXX.components.tabs.package-info
- XXX.components.tabs.Tab
+ XXX.components.tabs.TabManager
- XXX.components.tabs.TabNavigationBar
+ XXX.components.tabs.TabNavigationBar$Builder
+ XXX.components.toasts.AdvancementToast
+ XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastId
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
- XXX.core.dispenser.DispenseItemBehavior$28
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$7$1
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$8$1
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.DustColorTransitionOptions
- XXX.core.particles.DustColorTransitionOptions$1
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.DustParticleOptions$1
+ XXX.core.particles.DustParticleOptionsBase
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
- XXX.core.particles.ParticleGroup
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SculkChargeParticleOptions
+ XXX.core.particles.SculkChargeParticleOptions$1
- XXX.core.particles.ShriekParticleOption
+ XXX.core.particles.ShriekParticleOption$1
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
- XXX.core.particles.VibrationParticleOption
+ XXX.core.particles.VibrationParticleOption$1
+ XXX.core.registries.BuiltInRegistries
- XXX.core.registries.BuiltInRegistries$RegistryBootstrap
- XXX.core.registries.package-info
+ XXX.core.registries.Registries
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdvancementSubProvider
- XXX.data.advancements.package-info
- XXX.data.info.BiomeParametersDumpReport
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLootSubProvider
- XXX.data.loot.EntityLootSubProvider
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableProvider$1
+ XXX.data.loot.LootTableProvider$SubProviderEntry
- XXX.data.loot.LootTableSubProvider
+ XXX.data.loot.package-info
+ XXX.data.metadata.package-info
- XXX.data.metadata.PackMetadataGenerator
- XXX.data.models.BlockModelGenerators
+ XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ItemModelGenerators$TrimModelData
- XXX.data.models.ModelProvider
- XXX.data.models.package-info
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeBuilder$1
- XXX.data.recipes.RecipeCategory
+ XXX.data.recipes.RecipeOutput
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.RecipeProvider$1
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SmithingTransformRecipeBuilder
+ XXX.data.recipes.SmithingTrimRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.registries.package-info
+ XXX.data.registries.RegistriesDatapackGenerator
- XXX.data.registries.RegistryPatchGenerator
+ XXX.data.registries.UpdateOneTwentyOneRegistries
- XXX.data.registries.VanillaRegistries
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtDatafixer
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BannerPatternTagsProvider
+ XXX.data.tags.BiomeTagsProvider
- XXX.data.tags.CatVariantTagsProvider
+ XXX.data.tags.DamageTypeTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.InstrumentTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ XXX.data.tags.ItemTagsProvider
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1CombinedData
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.TagsProvider$TagLookup
+ XXX.data.tags.TradeRebalanceStructureTagsProvider
- XXX.data.tags.UpdateOneTwentyOneBiomeTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneBlockTagsProvider
- XXX.data.tags.UpdateOneTwentyOneDamageTypeTagsProvider
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V501
+ XXX.datafix.schemas.V700
- XXX.datafix.schemas.V701
+ XXX.datafix.schemas.V702
- XXX.datafix.schemas.V703
+ XXX.datafix.schemas.V704
- XXX.datafix.schemas.V704$1
+ XXX.datafix.schemas.V705
- XXX.datafix.schemas.V705$1
+ XXX.datafix.schemas.V808
- XXX.datafix.schemas.V99
+ XXX.datafix.schemas.V99$1
+ XXX.entity.ambient.AmbientCreature
- XXX.entity.ambient.Bat
+ XXX.entity.ambient.package-info
- XXX.entity.animal.AbstractFish
+ XXX.entity.animal.AbstractFish$FishMoveControl
- XXX.entity.animal.AbstractFish$FishSwimGoal
+ XXX.entity.animal.AbstractGolem
- XXX.entity.animal.AbstractSchoolingFish
+ XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- XXX.entity.animal.Animal
+ XXX.entity.animal.Bee
- XXX.entity.animal.Bee$1
+ XXX.entity.animal.Bee$BaseBeeGoal
- XXX.entity.animal.Bee$BeeAttackGoal
+ XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
- XXX.entity.animal.Bee$BeeEnterHiveGoal
+ XXX.entity.animal.Bee$BeeGoToHiveGoal
- XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ XXX.entity.animal.Bee$BeeGrowCropGoal
- XXX.entity.animal.Bee$BeeHurtByOtherGoal
+ XXX.entity.animal.Bee$BeeLocateHiveGoal
- XXX.entity.animal.Bee$BeeLookControl
+ XXX.entity.animal.Bee$BeePollinateGoal
- XXX.entity.animal.Bee$BeeWanderGoal
+ XXX.entity.animal.Bucketable
- XXX.entity.animal.Cat
+ XXX.entity.animal.Cat$CatAvoidEntityGoal
- XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
+ XXX.entity.animal.Cat$CatTemptGoal
- XXX.entity.animal.CatVariant
+ XXX.entity.animal.Chicken
- XXX.entity.animal.Cod
+ XXX.entity.animal.Cow
- XXX.entity.animal.Dolphin
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.Fox$DefendTrustedTargetGoal
+ XXX.entity.animal.Fox$FaceplantGoal
- XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
+ XXX.entity.animal.Fox$FoxBehaviorGoal
- XXX.entity.animal.Fox$FoxBreedGoal
+ XXX.entity.animal.Fox$FoxEatBerriesGoal
- XXX.entity.animal.Fox$FoxFloatGoal
+ XXX.entity.animal.Fox$FoxFollowParentGoal
- XXX.entity.animal.Fox$FoxGroupData
+ XXX.entity.animal.Fox$FoxLookAtPlayerGoal
- XXX.entity.animal.Fox$FoxLookControl
+ XXX.entity.animal.Fox$FoxMeleeAttackGoal
- XXX.entity.animal.Fox$FoxMoveControl
+ XXX.entity.animal.Fox$FoxPanicGoal
- XXX.entity.animal.Fox$FoxPounceGoal
+ XXX.entity.animal.Fox$FoxSearchForItemsGoal
- XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
+ XXX.entity.animal.Fox$PerchAndSearchGoal
- XXX.entity.animal.Fox$SeekShelterGoal
+ XXX.entity.animal.Fox$SleepGoal
- XXX.entity.animal.Fox$StalkPreyGoal
+ XXX.entity.animal.Fox$Type
- XXX.entity.animal.FrogVariant
+ XXX.entity.animal.IronGolem
- XXX.entity.animal.IronGolem$Crackiness
+ XXX.entity.animal.MushroomCow
- XXX.entity.animal.MushroomCow$MushroomType
+ XXX.entity.animal.Ocelot
- XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ XXX.entity.animal.Ocelot$OcelotTemptGoal
- XXX.entity.animal.Panda
+ XXX.entity.animal.Panda$Gene
- XXX.entity.animal.Panda$PandaAttackGoal
+ XXX.entity.animal.Panda$PandaAvoidGoal
- XXX.entity.animal.Panda$PandaBreedGoal
+ XXX.entity.animal.Panda$PandaHurtByTargetGoal
- XXX.entity.animal.Panda$PandaLieOnBackGoal
+ XXX.entity.animal.Panda$PandaLookAtPlayerGoal
- XXX.entity.animal.Panda$PandaMoveControl
+ XXX.entity.animal.Panda$PandaPanicGoal
- XXX.entity.animal.Panda$PandaRollGoal
+ XXX.entity.animal.Panda$PandaSitGoal
- XXX.entity.animal.Panda$PandaSneezeGoal
+ XXX.entity.animal.Parrot
- XXX.entity.animal.Parrot$1
+ XXX.entity.animal.Parrot$ParrotWanderGoal
- XXX.entity.animal.Parrot$Variant
+ XXX.entity.animal.Pig
- XXX.entity.animal.PolarBear
+ XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- XXX.entity.animal.PolarBear$PolarBearPanicGoal
+ XXX.entity.animal.Pufferfish
- XXX.entity.animal.Pufferfish$PufferfishPuffGoal
+ XXX.entity.animal.Rabbit
- XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ XXX.entity.animal.Rabbit$RabbitGroupData
- XXX.entity.animal.Rabbit$RabbitJumpControl
+ XXX.entity.animal.Rabbit$RabbitMoveControl
- XXX.entity.animal.Rabbit$RabbitPanicGoal
+ XXX.entity.animal.Rabbit$RaidGardenGoal
- XXX.entity.animal.Rabbit$Variant
+ XXX.entity.animal.Salmon
- XXX.entity.animal.Sheep
+ XXX.entity.animal.Sheep$1
- XXX.entity.animal.Sheep$2
+ XXX.entity.animal.ShoulderRidingEntity
- XXX.entity.animal.SnowGolem
+ XXX.entity.animal.Squid
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TropicalFish
+ XXX.entity.animal.TropicalFish$Base
- XXX.entity.animal.TropicalFish$Pattern
+ XXX.entity.animal.TropicalFish$TropicalFishGroupData
- XXX.entity.animal.TropicalFish$Variant
+ XXX.entity.animal.Turtle
- XXX.entity.animal.Turtle$TurtleBreedGoal
+ XXX.entity.animal.Turtle$TurtleGoHomeGoal
- XXX.entity.animal.Turtle$TurtleGoToWaterGoal
+ XXX.entity.animal.Turtle$TurtleLayEggGoal
- XXX.entity.animal.Turtle$TurtleMoveControl
+ XXX.entity.animal.Turtle$TurtlePanicGoal
- XXX.entity.animal.Turtle$TurtlePathNavigation
+ XXX.entity.animal.Turtle$TurtleRandomStrollGoal
- XXX.entity.animal.Turtle$TurtleTravelGoal
+ XXX.entity.animal.WaterAnimal
- XXX.entity.animal.Wolf
+ XXX.entity.animal.Wolf$WolfAvoidEntityGoal
- XXX.entity.animal.Wolf$WolfPanicGoal
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
- XXX.entity.layers.BreezeEyesLayer
+ XXX.entity.layers.BreezeWindLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseArmorLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.layers.PlayerItemInHandLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.SaddleLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StrayClothingLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.TropicalFishPatternLayer$1
+ XXX.entity.layers.VillagerProfessionLayer
- XXX.entity.layers.WardenEmissiveLayer
+ XXX.entity.layers.WardenEmissiveLayer$AlphaFunction
- XXX.entity.layers.WardenEmissiveLayer$DrawSelector
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.monster.package-info
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$FailureItemListing
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerTrades$TypeSpecificTrade
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.Player
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$Effect
- XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.SpecialGlyphs
- XXX.font.glyphs.SpecialGlyphs$1
+ XXX.font.glyphs.SpecialGlyphs$PixelProvider
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$Definition
- XXX.font.providers.BitmapProvider$Glyph
+ XXX.font.providers.BitmapProvider$Glyph$1
- XXX.font.providers.GlyphProviderDefinition
+ XXX.font.providers.GlyphProviderDefinition$Loader
- XXX.font.providers.GlyphProviderDefinition$Reference
+ XXX.font.providers.GlyphProviderType
- XXX.font.providers.package-info
- XXX.font.providers.ProviderReferenceDefinition
+ XXX.font.providers.TrueTypeGlyphProviderDefinition
- XXX.font.providers.TrueTypeGlyphProviderDefinition$Shift
+ XXX.font.providers.UnihexProvider
- XXX.font.providers.UnihexProvider$ByteContents
+ XXX.font.providers.UnihexProvider$Definition
- XXX.font.providers.UnihexProvider$Dimensions
+ XXX.font.providers.UnihexProvider$Glyph
- XXX.font.providers.UnihexProvider$Glyph$1
+ XXX.font.providers.UnihexProvider$IntContents
- XXX.font.providers.UnihexProvider$LineData
+ XXX.font.providers.UnihexProvider$OverrideRange
- XXX.font.providers.UnihexProvider$ReaderOutput
+ XXX.font.providers.UnihexProvider$ShortContents
- XXX.geom.builders.CubeDefinition
+ XXX.geom.builders.CubeDeformation
- XXX.geom.builders.CubeListBuilder
+ XXX.geom.builders.LayerDefinition
- XXX.geom.builders.MaterialDefinition
+ XXX.geom.builders.MeshDefinition
- XXX.geom.builders.package-info
- XXX.geom.builders.PartDefinition
+ XXX.geom.builders.UVPair
- XXX.gui.components.AbstractButton
+ XXX.gui.components.AbstractContainerWidget
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractScrollWidget
- XXX.gui.components.AbstractSelectionList
+ XXX.gui.components.AbstractSelectionList$1
- XXX.gui.components.AbstractSelectionList$Entry
+ XXX.gui.components.AbstractSelectionList$TrackedList
- XXX.gui.components.AbstractSliderButton
+ XXX.gui.components.AbstractStringWidget
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.BossHealthOverlay$1
+ XXX.gui.components.Button
- XXX.gui.components.Button$Builder
+ XXX.gui.components.Button$CreateNarration
- XXX.gui.components.Button$OnPress
+ XXX.gui.components.ChatComponent
- XXX.gui.components.ChatComponent$DelayedMessageDeletion
+ XXX.gui.components.Checkbox
- XXX.gui.components.Checkbox$Builder
+ XXX.gui.components.Checkbox$OnValueChange
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.CommonButtons
+ XXX.gui.components.ComponentRenderUtils
- XXX.gui.components.ContainerObjectSelectionList
+ XXX.gui.components.ContainerObjectSelectionList$1
- XXX.gui.components.ContainerObjectSelectionList$Entry
+ XXX.gui.components.CycleButton
- XXX.gui.components.CycleButton$Builder
+ XXX.gui.components.CycleButton$OnValueChange
- XXX.gui.components.CycleButton$ValueListSupplier
+ XXX.gui.components.CycleButton$ValueListSupplier$1
- XXX.gui.components.CycleButton$ValueListSupplier$2
+ XXX.gui.components.DebugScreenOverlay
- XXX.gui.components.DebugScreenOverlay$1
+ XXX.gui.components.DebugScreenOverlay$AllocationRateCalculator
- XXX.gui.components.EditBox
+ XXX.gui.components.FittingMultiLineTextWidget
- XXX.gui.components.FocusableTextWidget
+ XXX.gui.components.ImageButton
- XXX.gui.components.ImageWidget
+ XXX.gui.components.ImageWidget$Sprite
- XXX.gui.components.ImageWidget$Texture
+ XXX.gui.components.LerpingBossEvent
- XXX.gui.components.LoadingDotsWidget
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.LogoRenderer
- XXX.gui.components.MultiLineEditBox
+ XXX.gui.components.MultiLineLabel
- XXX.gui.components.MultiLineLabel$1
+ XXX.gui.components.MultiLineLabel$2
- XXX.gui.components.MultiLineLabel$TextWithWidth
+ XXX.gui.components.MultilineTextField
- XXX.gui.components.MultilineTextField$1
+ XXX.gui.components.MultilineTextField$StringView
+ XXX.gui.components.MultiLineTextWidget
- XXX.gui.components.MultiLineTextWidget$CacheKey
- XXX.gui.components.ObjectSelectionList
+ XXX.gui.components.ObjectSelectionList$Entry
- XXX.gui.components.OptionsList
+ XXX.gui.components.OptionsList$Entry
- XXX.gui.components.package-info
- XXX.gui.components.PlainTextButton
+ XXX.gui.components.PlayerFaceRenderer
- XXX.gui.components.PlayerSkinWidget
+ XXX.gui.components.PlayerSkinWidget$Model
- XXX.gui.components.PlayerTabOverlay
+ XXX.gui.components.PlayerTabOverlay$HealthState
- XXX.gui.components.PlayerTabOverlay$ScoreDisplayEntry
+ XXX.gui.components.PopupScreen
- XXX.gui.components.PopupScreen$Builder
+ XXX.gui.components.PopupScreen$ButtonOption
- XXX.gui.components.Renderable
+ XXX.gui.components.SplashRenderer
- XXX.gui.components.SpriteIconButton
+ XXX.gui.components.SpriteIconButton$Builder
- XXX.gui.components.SpriteIconButton$CenteredIcon
+ XXX.gui.components.SpriteIconButton$TextAndIcon
- XXX.gui.components.StateSwitchingButton
+ XXX.gui.components.StringWidget
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TabButton
+ XXX.gui.components.TabOrderedElement
- XXX.gui.components.Tooltip
+ XXX.gui.components.Whence
- XXX.gui.components.WidgetSprites
- XXX.gui.font.AllMissingGlyphProvider
+ XXX.gui.font.CodepointMap
- XXX.gui.font.CodepointMap$Output
+ XXX.gui.font.FontManager
- XXX.gui.font.FontManager$BuilderId
+ XXX.gui.font.FontManager$BuilderResult
- XXX.gui.font.FontManager$FontDefinitionFile
+ XXX.gui.font.FontManager$Preparation
- XXX.gui.font.FontManager$UnresolvedBuilderBundle
+ XXX.gui.font.FontSet
- XXX.gui.font.FontSet$GlyphInfoFilter
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$Node
+ XXX.gui.font.GlyphRenderTypes
- XXX.gui.font.GlyphRenderTypes$1
+ XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$1
+ XXX.gui.font.TextFieldHelper$CursorStep
+ XXX.gui.layouts.AbstractLayout
- XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
+ XXX.gui.layouts.CommonLayouts
- XXX.gui.layouts.EqualSpacingLayout
+ XXX.gui.layouts.EqualSpacingLayout$1
- XXX.gui.layouts.EqualSpacingLayout$ChildContainer
+ XXX.gui.layouts.EqualSpacingLayout$Orientation
- XXX.gui.layouts.FrameLayout
+ XXX.gui.layouts.FrameLayout$ChildContainer
- XXX.gui.layouts.GridLayout
+ XXX.gui.layouts.GridLayout$CellInhabitant
- XXX.gui.layouts.GridLayout$RowHelper
+ XXX.gui.layouts.HeaderAndFooterLayout
- XXX.gui.layouts.Layout
+ XXX.gui.layouts.LayoutElement
- XXX.gui.layouts.LayoutSettings
+ XXX.gui.layouts.LayoutSettings$LayoutSettingsImpl
- XXX.gui.layouts.LinearLayout
+ XXX.gui.layouts.LinearLayout$1
- XXX.gui.layouts.LinearLayout$Orientation
- XXX.gui.layouts.package-info
+ XXX.gui.layouts.SpacerElement
+ XXX.gui.narration.NarratableEntry
- XXX.gui.narration.NarratableEntry$NarrationPriority
+ XXX.gui.narration.NarratedElementType
- XXX.gui.narration.NarrationElementOutput
+ XXX.gui.narration.NarrationSupplier
- XXX.gui.narration.NarrationThunk
- XXX.gui.narration.package-info
+ XXX.gui.narration.ScreenNarrationCollector
- XXX.gui.narration.ScreenNarrationCollector$1
+ XXX.gui.narration.ScreenNarrationCollector$EntryKey
- XXX.gui.narration.ScreenNarrationCollector$NarrationEntry
+ XXX.gui.narration.ScreenNarrationCollector$Output
+ XXX.gui.navigation.CommonInputs
- XXX.gui.navigation.FocusNavigationEvent
+ XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
- XXX.gui.navigation.FocusNavigationEvent$InitialFocus
+ XXX.gui.navigation.FocusNavigationEvent$TabNavigation
- XXX.gui.navigation.package-info
- XXX.gui.navigation.ScreenAxis
+ XXX.gui.navigation.ScreenAxis$1
- XXX.gui.navigation.ScreenDirection
+ XXX.gui.navigation.ScreenDirection$1
- XXX.gui.navigation.ScreenPosition
+ XXX.gui.navigation.ScreenPosition$1
- XXX.gui.navigation.ScreenRectangle
+ XXX.gui.navigation.ScreenRectangle$1
- XXX.gui.screens.AccessibilityOnboardingScreen
+ XXX.gui.screens.AccessibilityOptionsScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.BanNoticeScreens
- XXX.gui.screens.ChatOptionsScreen
+ XXX.gui.screens.ChatScreen
- XXX.gui.screens.ChatScreen$1
+ XXX.gui.screens.ConfirmLinkScreen
- XXX.gui.screens.ConfirmScreen
+ XXX.gui.screens.ConnectScreen
- XXX.gui.screens.ConnectScreen$1
+ XXX.gui.screens.ConnectScreen$2
- XXX.gui.screens.CreateBuffetWorldScreen
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ XXX.gui.screens.CreateFlatWorldScreen
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- XXX.gui.screens.CreditsAndAttributionScreen
+ XXX.gui.screens.DatapackLoadFailureScreen
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DeathScreen$TitleConfirmScreen
- XXX.gui.screens.DemoIntroScreen
+ XXX.gui.screens.DirectJoinServerScreen
- XXX.gui.screens.DisconnectedScreen
+ XXX.gui.screens.EditServerScreen
- XXX.gui.screens.ErrorScreen
+ XXX.gui.screens.FaviconTexture
- XXX.gui.screens.GenericDirtMessageScreen
+ XXX.gui.screens.GenericWaitingScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingDotsText
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.MouseSettingsScreen
+ XXX.gui.screens.NoticeWithLinkScreen
- XXX.gui.screens.OnlineOptionsScreen
+ XXX.gui.screens.OptionsScreen
- XXX.gui.screens.OptionsSubScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PresetFlatWorldScreen
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.RecoverWorldDataScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$DeferredTooltipRendering
- XXX.gui.screens.Screen$NarratableSearchResult
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.SimpleOptionsSubScreen
+ XXX.gui.screens.SkinCustomizationScreen
- XXX.gui.screens.SoundOptionsScreen
+ XXX.gui.screens.TitleScreen
- XXX.gui.screens.TitleScreen$WarningLabel
+ XXX.gui.screens.UnsupportedGraphicsWarningScreen
- XXX.gui.screens.UnsupportedGraphicsWarningScreen$ButtonOption
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
+ XXX.gui.screens.WinScreen$CreditsReader
+ XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
- XXX.inventory.tooltip.ClientBundleTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip$Texture
- XXX.inventory.tooltip.ClientTextTooltip
+ XXX.inventory.tooltip.ClientTooltipComponent
- XXX.inventory.tooltip.ClientTooltipPositioner
+ XXX.inventory.tooltip.DefaultTooltipPositioner
- XXX.inventory.tooltip.MenuTooltipPositioner
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipRenderUtil
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent
+ XXX.jfr.event.NetworkSummaryEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent$SumAggregation
- XXX.jfr.event.package-info
+ XXX.jfr.event.PacketEvent
- XXX.jfr.event.PacketEvent$Fields
+ XXX.jfr.event.PacketReceivedEvent
- XXX.jfr.event.PacketSentEvent
+ XXX.jfr.event.ServerTickTimeEvent
- XXX.jfr.event.ServerTickTimeEvent$Fields
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.CpuLoadStat
+ XXX.jfr.stats.FileIOStat
- XXX.jfr.stats.FileIOStat$Summary
+ XXX.jfr.stats.GcHeapStat
- XXX.jfr.stats.GcHeapStat$Summary
+ XXX.jfr.stats.GcHeapStat$Timing
- XXX.jfr.stats.NetworkPacketSummary
+ XXX.jfr.stats.NetworkPacketSummary$PacketCountAndSize
- XXX.jfr.stats.NetworkPacketSummary$PacketIdentification
- XXX.jfr.stats.package-info
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
- XXX.jfr.stats.TimedStat
+ XXX.jfr.stats.TimedStatSummary
- XXX.level.block.BonemealableBlock$Type
- XXX.level.storage.FileNameDateFormatter
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelDataAndDimensions
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelCandidates
+ XXX.level.storage.LevelStorageSource$LevelDirectory
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelSummary$CorruptedLevelSummary
- XXX.level.storage.LevelSummary$SymlinkLevelSummary
+ XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$Event
- XXX.level.validation.ContentValidationException
+ XXX.level.validation.DirectoryValidator
- XXX.level.validation.DirectoryValidator$1
+ XXX.level.validation.ForbiddenSymlinkInfo
+ XXX.level.validation.package-info
- XXX.level.validation.PathAllowList
+ XXX.level.validation.PathAllowList$ConfigEntry
- XXX.level.validation.PathAllowList$EntryType
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootTableReference
+ XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaType
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Path
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FunctionReference
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.package-info
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetInstrumentFunction
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SmeltItemFunction
+ XXX.loot.packs.package-info
- XXX.loot.packs.TradeRebalanceChestLoot
+ XXX.loot.packs.TradeRebalanceLootTableProvider
- XXX.loot.packs.UpdateOneTwentyOneBlockLoot
+ XXX.loot.packs.UpdateOneTwentyOneChestLoot
- XXX.loot.packs.UpdateOneTwentyOneLootTableProvider
+ XXX.loot.packs.VanillaArchaeologyLoot
- XXX.loot.packs.VanillaBlockLoot
+ XXX.loot.packs.VanillaChestLoot
- XXX.loot.packs.VanillaEntityLoot
+ XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaGiftLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AllOfCondition
+ XXX.loot.predicates.AllOfCondition$Builder
- XXX.loot.predicates.AnyOfCondition
+ XXX.loot.predicates.AnyOfCondition$Builder
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.CompositeLootItemCondition
- XXX.loot.predicates.CompositeLootItemCondition$Builder
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
- XXX.metrics.profiling.ActiveMetricsRecorder
+ XXX.metrics.profiling.InactiveMetricsRecorder
- XXX.metrics.profiling.MetricsRecorder
+ XXX.metrics.profiling.package-info
+ XXX.metrics.profiling.ProfilerSamplerAdapter
- XXX.metrics.profiling.ServerMetricsSamplersProvider
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$1
- XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- XXX.metrics.storage.MetricsPersister
- XXX.metrics.storage.package-info
+ XXX.metrics.storage.RecordedDeviation
- XXX.minecraft.core.package-info
+ XXX.minecraft.data.BlockFamilies
- XXX.minecraft.data.BlockFamily
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.CachedOutput
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataGenerator$PackGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.DataProvider$Factory
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.HashCache$CacheUpdater
- XXX.minecraft.data.HashCache$ProviderCache
+ XXX.minecraft.data.HashCache$ProviderCacheBuilder
- XXX.minecraft.data.HashCache$UpdateFunction
+ XXX.minecraft.data.HashCache$UpdateResult
- XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
+ XXX.minecraft.data.PackOutput
- XXX.minecraft.data.PackOutput$PathProvider
+ XXX.minecraft.data.PackOutput$Target
+ XXX.minecraft.util.package-info
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.ContainerHelper
- XXX.minecraft.world.ContainerListener
+ XXX.minecraft.world.Containers
- XXX.minecraft.world.Difficulty
+ XXX.minecraft.world.DifficultyInstance
- XXX.minecraft.world.InteractionHand
+ XXX.minecraft.world.InteractionResult
- XXX.minecraft.world.InteractionResultHolder
- XXX.minecraft.world.ItemInteractionResult$1
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
- XXX.minecraft.world.package-info
+ XXX.minecraft.world.RandomizableContainer
- XXX.minecraft.world.RandomSequence
+ XXX.minecraft.world.RandomSequences
- XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
- XXX.minecraft.world.SimpleContainer
+ XXX.minecraft.world.SimpleMenuProvider
- XXX.minecraft.world.TickRateManager
+ XXX.minecraft.world.WorldlyContainer
- XXX.minecraft.world.WorldlyContainerHolder
+ XXX.model.dragon.DragonHeadModel
- XXX.model.dragon.package-info
+ XXX.model.geom.EntityModelSet
- XXX.model.geom.LayerDefinitions
+ XXX.model.geom.ModelLayerLocation
- XXX.model.geom.ModelLayers
+ XXX.model.geom.ModelPart
- XXX.model.geom.ModelPart$Cube
+ XXX.model.geom.ModelPart$Polygon
- XXX.model.geom.ModelPart$Vertex
+ XXX.model.geom.ModelPart$Visitor
+ XXX.model.geom.package-info
- XXX.model.geom.PartNames
+ XXX.model.geom.PartPose
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$Operation
+ XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C2
+ XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C4
+ XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyDispatch$PentaFunction
+ XXX.models.blockstates.PropertyDispatch$QuadFunction
- XXX.models.blockstates.PropertyDispatch$TriFunction
+ XXX.models.blockstates.Selector
- XXX.models.blockstates.Variant
+ XXX.models.blockstates.VariantProperties
- XXX.models.blockstates.VariantProperties$Rotation
+ XXX.models.blockstates.VariantProperty
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
+ XXX.models.model.ModelLocationUtils
- XXX.models.model.ModelTemplate
+ XXX.models.model.ModelTemplate$JsonFactory
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
- XXX.monster.breeze.LongJump
- XXX.monster.breeze.package-info
+ XXX.monster.breeze.Shoot
- XXX.monster.breeze.ShootWhenStuck
+ XXX.monster.breeze.Slide
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.HoglinBase
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.AbstractPiglin
- XXX.monster.piglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.PiglinArmPose
- XXX.monster.piglin.PiglinBrute
+ XXX.monster.piglin.PiglinBruteAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
+ XXX.monster.piglin.StartAdmiringItemIfSeen
- XXX.monster.piglin.StartHuntingHoglin
+ XXX.monster.piglin.StopAdmiringIfItemTooFarAway
- XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ XXX.monster.warden.AngerLevel
- XXX.monster.warden.AngerManagement
+ XXX.monster.warden.AngerManagement$1
- XXX.monster.warden.AngerManagement$Sorter
- XXX.monster.warden.package-info
+ XXX.monster.warden.Warden
- XXX.monster.warden.Warden$1
+ XXX.monster.warden.Warden$1$1
- XXX.monster.warden.Warden$2
+ XXX.monster.warden.Warden$VibrationUser
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
+ XXX.phys.shapes.ArrayVoxelShape
- XXX.phys.shapes.ArrayVoxelShape$1
+ XXX.phys.shapes.BitSetDiscreteVoxelShape
- XXX.phys.shapes.BooleanOp
+ XXX.phys.shapes.CollisionContext
- XXX.phys.shapes.CubePointRange
+ XXX.phys.shapes.CubeVoxelShape
- XXX.phys.shapes.DiscreteCubeMerger
+ XXX.phys.shapes.DiscreteVoxelShape
- XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- XXX.phys.shapes.EntityCollisionContext
+ XXX.phys.shapes.EntityCollisionContext$1
- XXX.phys.shapes.IdenticalMerger
+ XXX.phys.shapes.IndexMerger
- XXX.phys.shapes.IndexMerger$IndexConsumer
+ XXX.phys.shapes.IndirectMerger
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
+ XXX.profiling.metrics.MetricCategory
- XXX.profiling.metrics.MetricSampler
+ XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
- XXX.profiling.metrics.MetricSampler$SamplerResult
+ XXX.profiling.metrics.MetricSampler$ThresholdTest
- XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ XXX.profiling.metrics.MetricsRegistry
- XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ XXX.profiling.metrics.MetricsSamplerProvider
+ XXX.profiling.metrics.package-info
- XXX.profiling.metrics.ProfilerMeasured
- XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$1
- XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.ConstantValue
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
- XXX.recipes.packs.BundleRecipeProvider
- XXX.recipes.packs.package-info
+ XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.AxolotlRenderer
+ XXX.renderer.entity.BatRenderer
- XXX.renderer.entity.BeeRenderer
+ XXX.renderer.entity.BlazeRenderer
- XXX.renderer.entity.BoatRenderer
+ XXX.renderer.entity.BreezeRenderer
- XXX.renderer.entity.CamelRenderer
+ XXX.renderer.entity.CatRenderer
- XXX.renderer.entity.CaveSpiderRenderer
+ XXX.renderer.entity.ChestedHorseRenderer
- XXX.renderer.entity.ChickenRenderer
+ XXX.renderer.entity.CodRenderer
- XXX.renderer.entity.CowRenderer
+ XXX.renderer.entity.CreeperRenderer
- XXX.renderer.entity.DisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$1
- XXX.renderer.entity.DisplayRenderer$BlockDisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EnderDragonRenderer$DragonModel
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EntityRendererProvider
+ XXX.renderer.entity.EntityRendererProvider$Context
- XXX.renderer.entity.EntityRenderers
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.FrogRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GlowSquidRenderer
+ XXX.renderer.entity.GoatRenderer
- XXX.renderer.entity.GuardianRenderer
+ XXX.renderer.entity.HoglinRenderer
- XXX.renderer.entity.HorseRenderer
+ XXX.renderer.entity.HumanoidMobRenderer
- XXX.renderer.entity.HuskRenderer
+ XXX.renderer.entity.IllagerRenderer
- XXX.renderer.entity.IllusionerRenderer
+ XXX.renderer.entity.IllusionerRenderer$1
- XXX.renderer.entity.IronGolemRenderer
+ XXX.renderer.entity.ItemEntityRenderer
- XXX.renderer.entity.ItemFrameRenderer
+ XXX.renderer.entity.ItemRenderer
- XXX.renderer.entity.LeashKnotRenderer
+ XXX.renderer.entity.LightningBoltRenderer
- XXX.renderer.entity.LivingEntityRenderer
+ XXX.renderer.entity.LivingEntityRenderer$1
- XXX.renderer.entity.LlamaRenderer
+ XXX.renderer.entity.LlamaRenderer$1
- XXX.renderer.entity.LlamaSpitRenderer
+ XXX.renderer.entity.MagmaCubeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.NoopRenderer
- XXX.renderer.entity.OcelotRenderer
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PandaRenderer
+ XXX.renderer.entity.ParrotRenderer
- XXX.renderer.entity.ParrotRenderer$1
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RabbitRenderer$1
+ XXX.renderer.entity.RavagerRenderer
- XXX.renderer.entity.RenderLayerParent
+ XXX.renderer.entity.SalmonRenderer
- XXX.renderer.entity.SheepRenderer
+ XXX.renderer.entity.ShulkerBulletRenderer
- XXX.renderer.entity.ShulkerRenderer
+ XXX.renderer.entity.SilverfishRenderer
- XXX.renderer.entity.SkeletonRenderer
+ XXX.renderer.entity.SlimeRenderer
- XXX.renderer.entity.SnifferRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.StriderRenderer
+ XXX.renderer.entity.TadpoleRenderer
- XXX.renderer.entity.ThrownItemRenderer
+ XXX.renderer.entity.ThrownTridentRenderer
- XXX.renderer.entity.TippableArrowRenderer
+ XXX.renderer.entity.TntMinecartRenderer
- XXX.renderer.entity.TntRenderer
+ XXX.renderer.entity.TropicalFishRenderer
- XXX.renderer.entity.TropicalFishRenderer$1
+ XXX.renderer.entity.TurtleRenderer
- XXX.renderer.entity.UndeadHorseRenderer
+ XXX.renderer.entity.VexRenderer
- XXX.renderer.entity.VillagerRenderer
+ XXX.renderer.entity.VindicatorRenderer
- XXX.renderer.entity.VindicatorRenderer$1
+ XXX.renderer.entity.WanderingTraderRenderer
- XXX.renderer.entity.WardenRenderer
+ XXX.renderer.entity.WindChargeRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.screens.achievement.package-info
- XXX.screens.achievement.StatsScreen
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementTabType$Sprites
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.AdvancementWidgetType$1
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlsScreen
- XXX.screens.controls.KeyBindsList
+ XXX.screens.controls.KeyBindsList$CategoryEntry
- XXX.screens.controls.KeyBindsList$CategoryEntry$1
+ XXX.screens.controls.KeyBindsList$Entry
- XXX.screens.controls.KeyBindsList$KeyEntry
+ XXX.screens.controls.KeyBindsScreen
- XXX.screens.controls.package-info
+ XXX.screens.debug.GameModeSwitcherScreen
- XXX.screens.debug.GameModeSwitcherScreen$1
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
- XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ XXX.screens.debug.package-info
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractFurnaceScreen
- XXX.screens.inventory.AbstractSignEditScreen
+ XXX.screens.inventory.AnvilScreen
- XXX.screens.inventory.BeaconScreen
+ XXX.screens.inventory.BeaconScreen$1
- XXX.screens.inventory.BeaconScreen$BeaconButton
+ XXX.screens.inventory.BeaconScreen$BeaconCancelButton
- XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
+ XXX.screens.inventory.BeaconScreen$BeaconPowerButton
- XXX.screens.inventory.BeaconScreen$BeaconScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
+ XXX.screens.inventory.BlastFurnaceScreen
- XXX.screens.inventory.BookEditScreen
+ XXX.screens.inventory.BookEditScreen$DisplayCache
- XXX.screens.inventory.BookEditScreen$LineInfo
+ XXX.screens.inventory.BookEditScreen$Pos2i
- XXX.screens.inventory.BookViewScreen
+ XXX.screens.inventory.BookViewScreen$1
- XXX.screens.inventory.BookViewScreen$BookAccess
+ XXX.screens.inventory.BookViewScreen$WritableBookAccess
- XXX.screens.inventory.BookViewScreen$WrittenBookAccess
+ XXX.screens.inventory.BrewingStandScreen
- XXX.screens.inventory.CartographyTableScreen
+ XXX.screens.inventory.CommandBlockEditScreen
- XXX.screens.inventory.CommandBlockEditScreen$1
+ XXX.screens.inventory.ContainerScreen
- XXX.screens.inventory.CrafterScreen
+ XXX.screens.inventory.CrafterScreen$1
- XXX.screens.inventory.CraftingScreen
+ XXX.screens.inventory.CreativeInventoryListener
- XXX.screens.inventory.CreativeModeInventoryScreen
+ XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- XXX.screens.inventory.CyclingSlotBackground
+ XXX.screens.inventory.DispenserScreen
- XXX.screens.inventory.EffectRenderingInventoryScreen
+ XXX.screens.inventory.EnchantmentNames
- XXX.screens.inventory.EnchantmentScreen
+ XXX.screens.inventory.FurnaceScreen
- XXX.screens.inventory.GrindstoneScreen
+ XXX.screens.inventory.HangingSignEditScreen
- XXX.screens.inventory.HopperScreen
+ XXX.screens.inventory.HorseInventoryScreen
- XXX.screens.inventory.InventoryScreen
+ XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.JigsawBlockEditScreen
+ XXX.screens.inventory.JigsawBlockEditScreen$1
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.multiplayer.JoinMultiplayerScreen
- XXX.screens.multiplayer.Realms32bitWarningScreen
+ XXX.screens.multiplayer.SafetyScreen
- XXX.screens.multiplayer.ServerReconfigScreen
+ XXX.screens.multiplayer.ServerSelectionList
- XXX.screens.multiplayer.ServerSelectionList$1
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootDataId
- XXX.storage.loot.LootDataManager
+ XXX.storage.loot.LootDataManager$1
- XXX.storage.loot.LootDataResolver
+ XXX.storage.loot.LootDataType
- XXX.storage.loot.LootDataType$Validator
+ XXX.storage.loot.LootParams
- XXX.storage.loot.LootParams$Builder
+ XXX.storage.loot.LootParams$DynamicDrop
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.package-info
- XXX.storage.loot.ValidationContext
+ XXX.util.eventlog.EventLogDirectory
- XXX.util.eventlog.EventLogDirectory$CompressedFile
+ XXX.util.eventlog.EventLogDirectory$File
- XXX.util.eventlog.EventLogDirectory$FileId
+ XXX.util.eventlog.EventLogDirectory$FileList
- XXX.util.eventlog.EventLogDirectory$RawFile
+ XXX.util.eventlog.JsonEventLog
- XXX.util.eventlog.JsonEventLog$1
+ XXX.util.eventlog.JsonEventLogReader
- XXX.util.eventlog.JsonEventLogReader$1
+ XXX.util.eventlog.package-info
- XXX.util.profiling.ActiveProfiler
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
+ XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
- XXX.util.random.package-info
- XXX.util.random.SimpleWeightedRandomList
+ XXX.util.random.SimpleWeightedRandomList$Builder
- XXX.util.random.Weight
+ XXX.util.random.WeightedEntry
- XXX.util.random.WeightedEntry$IntrusiveBase
+ XXX.util.random.WeightedEntry$Wrapper
- XXX.util.random.WeightedRandom
+ XXX.util.random.WeightedRandomList
+ XXX.util.thread.BlockableEventLoop
- XXX.util.thread.NamedThreadFactory
+ XXX.util.thread.package-info
+ XXX.util.thread.ProcessorHandle
- XXX.util.thread.ProcessorHandle$1
+ XXX.util.thread.ProcessorMailbox
- XXX.util.thread.ReentrantBlockableEventLoop
+ XXX.util.thread.StrictQueue
- XXX.util.thread.StrictQueue$FixedPriorityQueue
+ XXX.util.thread.StrictQueue$IntRunnable
- XXX.util.thread.StrictQueue$QueueStrictQueue
- XXX.util.valueproviders.BiasedToBottomInt
+ XXX.util.valueproviders.ClampedInt
- XXX.util.valueproviders.ClampedNormalFloat
+ XXX.util.valueproviders.ClampedNormalInt
- XXX.util.valueproviders.ConstantFloat
+ XXX.util.valueproviders.ConstantInt
- XXX.util.valueproviders.FloatProvider
+ XXX.util.valueproviders.FloatProviderType
- XXX.util.valueproviders.IntProvider
+ XXX.util.valueproviders.IntProviderType
- XXX.util.valueproviders.MultipliedFloats
- XXX.util.valueproviders.package-info
+ XXX.util.valueproviders.SampledFloat
- XXX.util.valueproviders.TrapezoidFloat
+ XXX.util.valueproviders.UniformFloat
- XXX.util.valueproviders.UniformInt
+ XXX.util.valueproviders.WeightedListInt
- XXX.util.worldupdate.package-info
+ XXX.util.worldupdate.WorldUpgrader
- XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
+ XXX.village.poi.PoiTypes
+ XXX.world.damagesource.CombatEntry
- XXX.world.damagesource.CombatRules
+ XXX.world.damagesource.CombatTracker
- XXX.world.damagesource.DamageEffects
+ XXX.world.damagesource.DamageScaling
- XXX.world.damagesource.DamageSource
+ XXX.world.damagesource.DamageSource$1
- XXX.world.damagesource.DamageSources
+ XXX.world.damagesource.DamageType
- XXX.world.damagesource.DamageTypes
+ XXX.world.damagesource.DeathMessageType
- XXX.world.damagesource.FallLocation
+ XXX.world.damagesource.package-info
- XXX.world.effect.AbsorptionMobEffect
+ XXX.world.effect.AttributeModifierTemplate
- XXX.world.effect.MobEffect$AttributeTemplate
+ XXX.world.effect.MobEffect$MobEffectAttributeModifierTemplate
- XXX.world.entity.EntityAttachment
- XXX.world.entity.EntityAttachments
+ XXX.world.entity.package-info
- XXX.world.item.AnimalArmorItem$Type
- XXX.world.item.BookItem
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BowlFoodItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.CompassItem
+ XXX.world.item.ComplexItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$1
- XXX.world.item.CreativeModeTab$Builder
+ XXX.world.item.CreativeModeTab$DisplayItemsGenerator
- XXX.world.item.CreativeModeTab$ItemDisplayBuilder
+ XXX.world.item.CreativeModeTab$ItemDisplayParameters
- XXX.world.item.CreativeModeTab$Output
+ XXX.world.item.CreativeModeTab$Row
- XXX.world.item.CreativeModeTab$TabVisibility
+ XXX.world.item.CreativeModeTab$Type
- XXX.world.item.CreativeModeTabs
+ XXX.world.item.CrossbowItem
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeableLeatherItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.ElytraItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
- XXX.world.item.EnchantedGoldenAppleItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.Equipable
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FireworkRocketItem$Shape
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneyBottleItem
+ XXX.world.item.HoneycombItem
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.DisplaySlot
+ XXX.world.scores.DisplaySlot$1
- XXX.world.scores.Objective
- XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.ReadOnlyScoreInfo
+ XXX.world.scores.Score
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.ScoreHolder
- XXX.world.scores.ScoreHolder$1
+ XXX.world.scores.ScoreHolder$2
- XXX.world.scores.ScoreHolder$3
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.LevelChunkTicks
- XXX.world.ticks.LevelTickAccess
+ XXX.world.ticks.LevelTicks
- XXX.world.ticks.LevelTicks$PosAndContainerConsumer
+ XXX.world.ticks.package-info
+ XXX.world.ticks.ProtoChunkTicks
- XXX.world.ticks.SavedTick
+ XXX.world.ticks.SavedTick$1
- XXX.world.ticks.ScheduledTick
+ XXX.world.ticks.ScheduledTick$1
- XXX.world.ticks.SerializableTickContainer
+ XXX.world.ticks.TickAccess
- XXX.world.ticks.TickContainerAccess
+ XXX.world.ticks.TickPriority
- XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen +5M -5M
```
```
XXX.gui.screens.RealmsGenericErrorScreen +1M
```
```
XXX.advancements.critereon.MobEffectsPredicate$Builder +2M -2M
```
```
XXX.minecraft.client.MouseHandler +4M -3M | +1P -1P
```
```
XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry +2M -2M | +6P -1P
```
```
XXX.client.multiplayer.ServerStatusPinger$1 +1M -1M | +1P
```
```
XXX.client.renderer.FogRenderer$BlindnessFogFunction +1M -1M
```
```
XXX.client.renderer.FogRenderer$MobEffectFogFunction +1P -1P
```
```
XXX.client.resources.MobEffectTextureManager +1M -1M
```
```
XXX.commands.functions.FunctionBuilder +1M -1M
```
```
XXX.commands.functions.MacroFunction +2M -3M
```
```
XXX.commands.functions.MacroFunction$MacroEntry +2M -3M | +1P
```
```
XXX.commands.functions.PlainTextFunction +1M -1M
```
```
XXX.minecraft.core.Holder$Direct +1M
```
```
XXX.minecraft.core.Holder$Reference +1M
```
```
XXX.minecraft.core.MappedRegistry +1M
```
```
XXX.minecraft.core.Registry +1P
```
```
XXX.core.cauldron.CauldronInteraction +15M -15M | +1P -1P
```
```
XXX.protocol.game.ClientboundRemoveMobEffectPacket +6M -2M | +1P -1P
```
```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +3M -5M | +2P -2P
```
```
XXX.protocol.game.DebugPackets +2M -1M
```
```
XXX.protocol.game.ServerboundSetBeaconPacket +9M -6M
```
```
XXX.network.syncher.EntityDataSerializers +1P
```
```
XXX.server.commands.LocateCommand +6M -8M
```
```
XXX.server.level.ServerLevel +1M -1M
```
```
XXX.server.level.ServerPlayer +3M | +3P
```
```
XXX.server.network.ServerGamePacketListenerImpl -1P
```
```
XXX.server.players.PlayerList +5M -4M
```
```
XXX.minecraft.tags.TagManager +1M -2M
```
```
XXX.minecraft.util.ParticleUtils +2M
```
```
XXX.datafix.fixes.BlockRenameFix +5M -2M | +1P -1P
```
```
XXX.datafix.fixes.References +1M | +1P
```
```
XXX.datafix.schemas.V1909 +1M
```
```
XXX.world.effect.HealOrHarmMobEffect +1M -1M
```
```
XXX.world.effect.MobEffectInstance +14M -13M | +2P -3P
```
```
XXX.world.effect.MobEffectUtil +1M -1M
```
```
XXX.world.effect.PoisonMobEffect +1M -1M
```
```
XXX.world.effect.SaturationMobEffect +1M -1M
```
```
XXX.world.entity.AreaEffectCloud +2M -2M | +1P -1P
```
```
XXX.world.entity.EntityDimensions +11M | +2P
```
```
XXX.world.entity.EntityType +1P
```
```
XXX.world.entity.EntityType$Builder +6M | +1P
```
```
XXX.ai.attributes.AttributeMap +7M -11M
```
```
XXX.ai.attributes.AttributeSupplier$Builder +4M -4M | +1P -1P
```
```
XXX.ai.behavior.Swim +1M
```
```
XXX.animal.camel.Camel +3M -4M
```
```
XXX.animal.frog.Frog -1M
```
```
XXX.animal.horse.AbstractChestedHorse +1M -1M | +1P
```
```
XXX.animal.horse.AbstractHorse +2M -4M
```
```
XXX.animal.horse.SkeletonHorse +2M -1M | +1P
```
```
XXX.animal.sniffer.Sniffer +1M -4M
```
```
XXX.entity.decoration.ArmorStand +2M -2M
```
```
XXX.entity.decoration.LeashFenceKnotEntity -1M
```
```
XXX.entity.monster.AbstractSkeleton -2M
```
```
XXX.entity.monster.CaveSpider +1M -3M
```
```
XXX.entity.monster.ElderGuardian -1M
```
```
XXX.entity.monster.Endermite -2M
```
```
XXX.entity.monster.Giant -2M
```
```
XXX.entity.monster.Shulker -1M
```
```
XXX.entity.monster.Strider +1M -1M
```
```
XXX.entity.monster.WitherSkeleton -2M
```
```
XXX.entity.monster.Zombie +1M -3M | +1P -1P
```
```
XXX.entity.monster.ZombifiedPiglin +1M -2M | +1P -2P
```
```
XXX.world.inventory.BeaconMenu +4M -4M
```
```
XXX.world.item.ItemStack +3M -2M
```
```
XXX.world.item.WrittenBookItem -1M
```
```
XXX.item.alchemy.PotionBrewing +2M -2M
```
```
XXX.item.alchemy.PotionUtils +6M -5M
```
```
XXX.world.level.LevelAccessor +4M -3M | +1P -1P
```
```
XXX.level.block.AbstractCauldronBlock +1M -1M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +1M -1M
```
```
XXX.level.block.BarrelBlock +1M -1M
```
```
XXX.level.block.BedBlock +2M -2M
```
```
XXX.level.block.BeehiveBlock +2M -2M
```
```
XXX.level.block.BellBlock +1M -1M
```
```
XXX.level.block.BonemealableBlock +2M
```
```
XXX.level.block.CakeBlock +2M -1M
```
```
XXX.level.block.CampfireBlock +1M -1M
```
```
XXX.level.block.CandleCakeBlock +3M -2M | +1P -1P
```
```
XXX.level.block.CaveVinesPlantBlock +1M -1M
```
```
XXX.level.block.ChestBlock +1M -1M
```
```
XXX.level.block.ChiseledBookShelfBlock +5M -3M
```
```
XXX.level.block.ComparatorBlock +1M -1M
```
```
XXX.level.block.CrafterBlock +1M -1M
```
```
XXX.level.block.CraftingTableBlock +1M -1M
```
```
XXX.level.block.DoorBlock +1M -1M
```
```
XXX.level.block.EnchantmentTableBlock +1M -1M
```
```
XXX.level.block.FenceGateBlock +1M -1M
```
```
XXX.level.block.FlowerBlock +2M -2M
```
```
XXX.level.block.GrindstoneBlock +1M -1M
```
```
XXX.level.block.JukeboxBlock +1M -1M
```
```
XXX.level.block.LeverBlock +1M -1M
```
```
XXX.level.block.LightBlock +1M -1M
```
```
XXX.level.block.LoomBlock +1M -1M
```
```
XXX.level.block.MangroveLeavesBlock +1M
```
```
XXX.level.block.NetherrackBlock +1M
```
```
XXX.level.block.NyliumBlock +1M
```
```
XXX.level.block.PumpkinBlock +2M -2M
```
```
XXX.level.block.RedStoneWireBlock +1M -1M
```
```
XXX.level.block.RespawnAnchorBlock +2M -1M
```
```
XXX.level.block.RootedDirtBlock +1M
```
```
XXX.level.block.ShulkerBoxBlock +1M -1M
```
```
XXX.level.block.SignBlock +2M -2M
```
```
XXX.level.block.StonecutterBlock +1M -1M
```
```
XXX.level.block.SuspiciousEffectHolder$EffectEntry +2M -2M | +1P -1P
```
```
XXX.level.block.WitherRoseBlock +1M -1M
```
```
XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser +1M -1M
```
```
XXX.block.piston.MovingPistonBlock +1M -1M
```
```
XXX.level.gameevent.GameEventDispatcher +2M -2M
```
```
XXX.level.gameevent.GameEventListenerRegistry +1P -1P
```
```
XXX.gameevent.vibrations.VibrationInfo +5M -5M | +1P -1P
```
```
XXX.gameevent.vibrations.VibrationSystem +4M -3M | +2P -1P
```
```
XXX.gameevent.vibrations.VibrationSystem$Listener +4M -4M
```
```
XXX.gameevent.vibrations.VibrationSystem$User +1M -1M | +2P -2P
```
```
XXX.saveddata.maps.MapItemSavedData +2M
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
+ Font access$1700(RealmsMainScreen)
- Font access$2000(RealmsMainScreen)
+ Font access$2700(RealmsMainScreen)
- Font access$300(RealmsMainScreen)
- Minecraft access$1700(RealmsMainScreen)
+ Minecraft access$2000(RealmsMainScreen)
- Minecraft access$2700(RealmsMainScreen)
+ Minecraft access$3000(RealmsMainScreen)
+ void access$300(RealmsMainScreen,Component)
- void onClose()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen
</summary>

```diff
- void onClose()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.MobEffectsPredicate$Builder
</summary>

```diff
- MobEffectsPredicate$Builder and(Holder,MobEffectsPredicate$MobEffectInstancePredicate)
- MobEffectsPredicate$Builder and(Holder)
+ MobEffectsPredicate$Builder and(MobEffect,MobEffectsPredicate$MobEffectInstancePredicate)
+ MobEffectsPredicate$Builder and(MobEffect)
```

</details>
<details>
<summary>
net.minecraft.client.MouseHandler
</summary>

```diff
- void handleAccumulatedMovement()
- void lambda$handleAccumulatedMovement$10(Screen,double,double)
- void lambda$handleAccumulatedMovement$11(Screen,double,double,double,double)
+ void lambda$onMove$10(Screen,double,double)
+ void lambda$onMove$11(Screen,double,double,double,double)
+ void turnPlayer()
- void turnPlayer(double)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
</summary>

```diff
+ boolean isCompatible()
+ boolean pingCompleted()
- void lambda$render$2()
- void refreshStatus()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ServerStatusPinger$1
</summary>

```diff
+ void <init>(ServerStatusPinger,Connection,ServerData,Runnable,InetSocketAddress,ServerAddress)
- void <init>(ServerStatusPinger,Connection,ServerData,Runnable,Runnable,InetSocketAddress,ServerAddress)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FogRenderer$BlindnessFogFunction
</summary>

```diff
- Holder getMobEffect()
+ MobEffect getMobEffect()
```

</details>
<details>
<summary>
net.minecraft.client.resources.MobEffectTextureManager
</summary>

```diff
- TextureAtlasSprite get(Holder)
+ TextureAtlasSprite get(MobEffect)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.FunctionBuilder
</summary>

```diff
- void addMacro(String,int,ExecutionCommandSource)
+ void addMacro(String,int)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.MacroFunction
</summary>

```diff
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,ExecutionCommandSource)
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,Object)
- InstantiatedFunction instantiate(CompoundTag,CommandDispatcher)
+ InstantiatedFunction substituteAndParse(List,List,CommandDispatcher,ExecutionCommandSource)
- InstantiatedFunction substituteAndParse(List,List,CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.MacroFunction$MacroEntry
</summary>

```diff
+ UnboundEntryAction instantiate(List,CommandDispatcher,ExecutionCommandSource,ResourceLocation)
+ UnboundEntryAction instantiate(List,CommandDispatcher,Object,ResourceLocation)
- UnboundEntryAction instantiate(List,CommandDispatcher,ResourceLocation)
- void <init>(StringTemplate,IntList,ExecutionCommandSource)
+ void <init>(StringTemplate,IntList)
```

</details>
<details>
<summary>
net.minecraft.commands.functions.PlainTextFunction
</summary>

```diff
+ InstantiatedFunction instantiate(CompoundTag,CommandDispatcher,Object)
- InstantiatedFunction instantiate(CompoundTag,CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.core.Holder$Direct
</summary>

```diff
- boolean is(Holder)
```

</details>
<details>
<summary>
net.minecraft.core.Holder$Reference
</summary>

```diff
- boolean is(Holder)
```

</details>
<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
- Optional getHolder(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.core.cauldron.CauldronInteraction
</summary>

```diff
+ InteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
+ InteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
+ InteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ InteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
- ItemInteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
- ItemInteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- ItemInteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
</summary>

```diff
- boolean equals(Object)
- Holder effect()
- int entityId()
- int hashCode()
+ MobEffect getEffect()
- String toString()
- void <init>(int,Holder)
+ void <init>(int,MobEffect)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
</summary>

```diff
- boolean shouldBlend()
- Holder getEffect()
+ MobEffect getEffect()
+ MobEffectInstance$FactorData getFactorData()
+ MobEffectInstance$FactorData lambda$new$0(FriendlyByteBuf)
- void <init>(int,MobEffectInstance,boolean)
+ void <init>(int,MobEffectInstance)
+ void lambda$write$1(FriendlyByteBuf,MobEffectInstance$FactorData)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.DebugPackets
</summary>

```diff
- void lambda$sendGameEventInfo$7(ServerLevel,Vec3,ResourceKey)
+ void sendGameEventInfo(Level,GameEvent,Vec3)
- void sendGameEventInfo(Level,Holder,Vec3)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
</summary>

```diff
- boolean equals(Object)
- Holder lambda$new$0(FriendlyByteBuf)
- Holder lambda$new$1(FriendlyByteBuf)
- int hashCode()
+ MobEffect lambda$new$0(FriendlyByteBuf)
+ MobEffect lambda$new$1(FriendlyByteBuf)
+ Optional getPrimary()
+ Optional getSecondary()
- Optional primary()
- Optional secondary()
- String toString()
- void lambda$write$2(FriendlyByteBuf,Holder)
+ void lambda$write$2(FriendlyByteBuf,MobEffect)
- void lambda$write$3(FriendlyByteBuf,Holder)
+ void lambda$write$3(FriendlyByteBuf,MobEffect)
```

</details>
<details>
<summary>
net.minecraft.server.commands.LocateCommand
</summary>

```diff
- Component lambda$showLocateResult$16(String,String,Component,int)
+ Component lambda$showLocateResult$17(String,String,Component,int)
+ String getElementName(Pair)
+ String lambda$getElementName$11(ResourceKey)
- String lambda$showLocateResult$11(ResourceOrTagArgument$Result,Holder$Reference)
+ String lambda$showLocateResult$12(ResourceOrTagArgument$Result,Holder$Reference)
- String lambda$showLocateResult$12(ResourceOrTagArgument$Result,Pair,HolderSet$Named)
- String lambda$showLocateResult$13(ResourceKey)
+ String lambda$showLocateResult$13(ResourceOrTagArgument$Result,Pair,HolderSet$Named)
- String lambda$showLocateResult$14(Pair,TagKey)
+ String lambda$showLocateResult$14(ResourceKey)
+ String lambda$showLocateResult$15(Pair,TagKey)
- Style lambda$showLocateResult$15(BlockPos,String,Style)
+ Style lambda$showLocateResult$16(BlockPos,String,Style)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ void gameEvent(GameEvent,Vec3,GameEvent$Context)
- void gameEvent(Holder,Vec3,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- boolean canInteractWithBlock(BlockPos)
- boolean canInteractWithEntity(AABB)
- void updatePlayerAttributes()
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ Component lambda$broadcastSystemMessage$2(Component,ServerPlayer)
- Component lambda$broadcastSystemMessage$3(Component,ServerPlayer)
+ CompoundTag load(ServerPlayer)
+ Entity lambda$placeNewPlayer$0(ServerLevel,Entity)
- Entity lambda$placeNewPlayer$1(ServerLevel,Entity)
- Optional lambda$placeNewPlayer$0(CompoundTag)
- Optional load(ServerPlayer)
+ void lambda$remove$1(Entity)
- void lambda$remove$2(Entity)
```

</details>
<details>
<summary>
net.minecraft.tags.TagManager
</summary>

```diff
+ Optional lambda$createLoader$3(Registry,ResourceKey,ResourceLocation)
- TagManager$LoadResult lambda$createLoader$3(ResourceKey,TagLoader,ResourceManager)
+ TagManager$LoadResult lambda$createLoader$4(ResourceKey,TagLoader,ResourceManager)
```

</details>
<details>
<summary>
net.minecraft.util.ParticleUtils
</summary>

```diff
- void spawnParticleInBlock(LevelAccessor,BlockPos,int,ParticleOptions)
- void spawnParticles(LevelAccessor,BlockPos,int,double,double,boolean,ParticleOptions)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockRenameFix
</summary>

```diff
- Dynamic fixBlockState(Dynamic)
+ Dynamic lambda$makeRule$2(Dynamic)
- Dynamic lambda$makeRule$3(Dynamic)
- String fixFlatBlockState(String)
- Typed lambda$makeRule$2(Typed)
+ Typed lambda$makeRule$3(Typed)
- Typed lambda$makeRule$4(Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.References
</summary>

```diff
- String lambda$static$35()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1909
</summary>

```diff
- TypeTemplate lambda$registerBlockEntities$0(Schema)
```

</details>
<details>
<summary>
net.minecraft.world.effect.HealOrHarmMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
- boolean is(Holder)
- float getBlendFactor(LivingEntity,float)
- Holder getEffect()
- int lambda$tickDownDuration$0(int)
+ int lambda$tickDownDuration$1(int)
+ MobEffect getEffect()
- MobEffectInstance lambda$load$1(CompoundTag,Holder$Reference)
- MobEffectInstance loadSpecifiedEffect(Holder,CompoundTag)
+ MobEffectInstance loadSpecifiedEffect(MobEffect,CompoundTag)
+ Optional getFactorData()
- void <init>(Holder,int,int,boolean,boolean,boolean,MobEffectInstance)
- void <init>(Holder,int,int,boolean,boolean,boolean)
- void <init>(Holder,int,int,boolean,boolean)
- void <init>(Holder,int,int)
- void <init>(Holder,int)
- void <init>(Holder)
+ void <init>(MobEffect,int,int,boolean,boolean,boolean,MobEffectInstance,Optional)
+ void <init>(MobEffect,int,int,boolean,boolean,boolean)
+ void <init>(MobEffect,int,int,boolean,boolean)
+ void <init>(MobEffect,int,int)
+ void <init>(MobEffect,int)
+ void <init>(MobEffect)
- void copyBlendState(MobEffectInstance)
+ void lambda$tick$0(MobEffectInstance$FactorData)
+ void lambda$writeDetailsTo$2(CompoundTag,Tag)
+ void lambda$writeDetailsTo$3(CompoundTag,MobEffectInstance$FactorData)
- void skipBlending()
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectUtil
</summary>

```diff
- boolean lambda$addEffectToPlayersAround$0(Entity,Vec3,double,Holder,MobEffectInstance,int,ServerPlayer)
+ boolean lambda$addEffectToPlayersAround$0(Entity,Vec3,double,MobEffect,MobEffectInstance,int,ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.world.effect.PoisonMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.SaturationMobEffect
</summary>

```diff
- boolean applyEffectTick(LivingEntity,int)
+ void applyEffectTick(LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
- Holder getPotion()
+ Potion getPotion()
- void setPotion(Holder)
+ void setPotion(Potion)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityDimensions
</summary>

```diff
- boolean equals(Object)
- boolean fixed()
- EntityAttachments attachments()
- EntityDimensions withAttachments(EntityAttachments$Builder)
- EntityDimensions withEyeHeight(float)
- float defaultEyeHeight(float)
- float eyeHeight()
- float height()
- float width()
- int hashCode()
- void <init>(float,float,float,EntityAttachments,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityType$Builder
</summary>

```diff
- EntityType$Builder eyeHeight(float)
- EntityType$Builder nameTagOffset(float)
- EntityType$Builder passengerAttachments(float[])
- EntityType$Builder passengerAttachments(Vec3[])
- EntityType$Builder ridingOffset(float)
- EntityType$Builder vehicleAttachment(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeMap
</summary>

```diff
+ AttributeInstance getInstance(Attribute)
+ AttributeInstance lambda$getInstance$1(Attribute)
- AttributeInstance lambda$getInstance$1(Holder)
+ boolean hasAttribute(Attribute)
+ boolean hasModifier(Attribute,UUID)
+ double getBaseValue(Attribute)
- double getBaseValue(Holder)
+ double getModifierValue(Attribute,UUID)
+ double getValue(Attribute)
- double getValue(Holder)
+ void lambda$addTransientAttributeModifiers$4(Attribute,AttributeModifier)
- void lambda$addTransientAttributeModifiers$4(Holder,AttributeModifier)
+ void lambda$load$6(CompoundTag,Attribute)
- void lambda$load$6(CompoundTag,Holder$Reference)
- void lambda$load$7(ResourceLocation)
+ void lambda$load$7(String)
+ void lambda$removeAttributeModifiers$3(Attribute,Collection)
- void lambda$removeAttributeModifiers$3(Holder,Collection)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
</summary>

```diff
+ AttributeInstance create(Attribute)
- AttributeInstance create(Holder)
+ AttributeSupplier$Builder add(Attribute,double)
+ AttributeSupplier$Builder add(Attribute)
- AttributeSupplier$Builder add(Holder,double)
- AttributeSupplier$Builder add(Holder)
+ void lambda$create$0(Attribute,AttributeInstance)
- void lambda$create$0(Holder,AttributeInstance)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.Swim
</summary>

```diff
- boolean shouldSwim(Mob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.camel.Camel
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
- float getAgeScale()
+ float getScale()
+ float getStandingEyeHeight(Pose,EntityDimensions)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.frog.Frog
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractChestedHorse
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ float getPassengersRidingOffsetY(EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ float getPassengersRidingOffsetY(EntityDimensions,float)
+ float getStandingEyeHeight(Pose,EntityDimensions)
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ void setOffspringAttribute(AgeableMob,AbstractHorse,Attribute,double,double)
- void setOffspringAttribute(AgeableMob,AbstractHorse,Holder,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.SkeletonHorse
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.sniffer.Sniffer
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ float getNameTagOffsetY()
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ArmorStand
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
- EntityDimensions getDefaultDimensions(Pose)
+ EntityDimensions getDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.LeashFenceKnotEntity
</summary>

```diff
+ float getEyeHeight(Pose,EntityDimensions)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.CaveSpider
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
- Vec3 getVehicleAttachmentPoint(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.ElderGuardian
</summary>

```diff
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Endermite
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Giant
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
- Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.WitherSkeleton
</summary>

```diff
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zombie
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ float ridingOffset(Entity)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.ZombifiedPiglin
</summary>

```diff
- EntityDimensions getDefaultDimensions(Pose)
+ float getStandingEyeHeight(Pose,EntityDimensions)
+ Vector3f getPassengerAttachmentPoint(Entity,EntityDimensions,float)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.BeaconMenu
</summary>

```diff
- Holder decodeEffect(int)
- Holder getPrimaryEffect()
- Holder getSecondaryEffect()
- int encodeEffect(Holder)
+ int encodeEffect(MobEffect)
+ MobEffect decodeEffect(int)
+ MobEffect getPrimaryEffect()
+ MobEffect getSecondaryEffect()
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- IllegalArgumentException lambda$addAttributeModifier$14()
+ Style lambda$getDisplayName$14(Style)
- Style lambda$getDisplayName$15(Style)
+ void addAttributeModifier(Attribute,AttributeModifier,EquipmentSlot)
- void addAttributeModifier(Holder,AttributeModifier,EquipmentSlot)
```

</details>
<details>
<summary>
net.minecraft.world.item.WrittenBookItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.PotionBrewing
</summary>

```diff
- boolean isBrewablePotion(Holder)
+ boolean isBrewablePotion(Potion)
- void addMix(Holder,Item,Holder)
+ void addMix(Potion,Item,Potion)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.PotionUtils
</summary>

```diff
- Holder getPotion(CompoundTag)
- Holder getPotion(ItemStack)
- int getColor(Holder)
+ int getColor(Potion)
- ItemStack setPotion(ItemStack,Holder)
+ ItemStack setPotion(ItemStack,Potion)
- List getAllEffects(Holder,Collection)
+ List getAllEffects(Potion,Collection)
+ Potion getPotion(CompoundTag)
+ Potion getPotion(ItemStack)
- void lambda$addPotionTooltip$0(List,Holder,AttributeModifier)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
+ void gameEvent(Entity,GameEvent,BlockPos)
+ void gameEvent(Entity,GameEvent,Vec3)
- void gameEvent(Entity,Holder,BlockPos)
- void gameEvent(Entity,Holder,Vec3)
+ void gameEvent(GameEvent,BlockPos,GameEvent$Context)
- void gameEvent(Holder,BlockPos,GameEvent$Context)
- void gameEvent(ResourceKey,BlockPos,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractCauldronBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BarrelBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
+ void lambda$use$1(Player,Player$BedSleepingProblem)
- void lambda$useWithoutItem$1(Player,Player$BedSleepingProblem)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ void lambda$use$0(InteractionHand,Player)
- void lambda$useItemOn$0(InteractionHand,Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BonemealableBlock
</summary>

```diff
- BlockPos getParticlePos(BlockPos)
- BonemealableBlock$Type getType()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CakeBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleCakeBlock
</summary>

```diff
+ BlockState byCandle(Block)
- BlockState byCandle(CandleBlock)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CaveVinesPlantBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChestBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChiseledBookShelfBlock
</summary>

```diff
+ int getHitSlot(Vec2)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- OptionalInt getHitSlot(BlockHitResult,BlockState)
- OptionalInt lambda$getHitSlot$0(Vec2)
+ void lambda$createBlockStateDefinition$0(StateDefinition$Builder,Property)
- void lambda$createBlockStateDefinition$1(StateDefinition$Builder,Property)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ComparatorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CraftingTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnchantmentTableBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceGateBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerBlock
</summary>

```diff
- List makeEffectList(Holder,int)
+ List makeEffectList(MobEffect,int)
- void <init>(Holder,int,BlockBehaviour$Properties)
+ void <init>(MobEffect,int,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrindstoneBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JukeboxBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LightBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LoomBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.MangroveLeavesBlock
</summary>

```diff
- BlockPos getParticlePos(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NetherrackBlock
</summary>

```diff
- BonemealableBlock$Type getType()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NyliumBlock
</summary>

```diff
- BonemealableBlock$Type getType()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PumpkinBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ void lambda$use$0(InteractionHand,Player)
- void lambda$useItemOn$0(InteractionHand,Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RedStoneWireBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RespawnAnchorBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RootedDirtBlock
</summary>

```diff
- BlockPos getParticlePos(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SignBlock
</summary>

```diff
+ InteractionResult getInteractionResult(boolean)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
- ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StonecutterBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SuspiciousEffectHolder$EffectEntry
</summary>

```diff
- Holder effect()
+ MobEffect effect()
- void <init>(Holder,int)
+ void <init>(MobEffect,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WitherRoseBlock
</summary>

```diff
- void <init>(Holder,int,BlockBehaviour$Properties)
+ void <init>(MobEffect,int,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
</summary>

```diff
+ boolean canReceiveVibration(ServerLevel,BlockPos,GameEvent,GameEvent$Context)
- boolean canReceiveVibration(ServerLevel,BlockPos,Holder,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult useWithoutItem(BlockState,Level,BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.GameEventDispatcher
</summary>

```diff
+ void lambda$post$0(List,GameEvent,Vec3,GameEvent$Context,GameEventListener,Vec3)
- void lambda$post$0(List,Holder,Vec3,GameEvent$Context,GameEventListener,Vec3)
+ void post(GameEvent,Vec3,GameEvent$Context)
- void post(Holder,Vec3,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationInfo
</summary>

```diff
+ GameEvent gameEvent()
- Holder gameEvent()
+ VibrationInfo lambda$static$2(GameEvent,Float,Vec3,Optional,Optional)
- VibrationInfo lambda$static$2(Holder,Float,Vec3,Optional,Optional)
+ void <init>(GameEvent,float,Vec3,Entity)
+ void <init>(GameEvent,float,Vec3,UUID,UUID,Entity)
+ void <init>(GameEvent,float,Vec3,UUID,UUID)
- void <init>(Holder,float,Vec3,Entity)
- void <init>(Holder,float,Vec3,UUID,UUID,Entity)
- void <init>(Holder,float,Vec3,UUID,UUID)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationSystem
</summary>

```diff
+ GameEvent getResonanceEventByFrequency(int)
+ int getGameEventFrequency(GameEvent)
- int getGameEventFrequency(Holder)
- int getGameEventFrequency(ResourceKey)
- ResourceKey getResonanceEventByFrequency(int)
+ void lambda$static$0(Object2IntOpenHashMap)
- void lambda$static$0(Reference2IntOpenHashMap)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
</summary>

```diff
+ boolean handleGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- boolean handleGameEvent(ServerLevel,Holder,GameEvent$Context,Vec3)
+ void forceScheduleVibration(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- void forceScheduleVibration(ServerLevel,Holder,GameEvent$Context,Vec3)
+ void lambda$forceScheduleVibration$0(ServerLevel,GameEvent,GameEvent$Context,Vec3,Vec3)
- void lambda$forceScheduleVibration$0(ServerLevel,Holder,GameEvent$Context,Vec3,Vec3)
+ void scheduleVibration(ServerLevel,VibrationSystem$Data,GameEvent,GameEvent$Context,Vec3,Vec3)
- void scheduleVibration(ServerLevel,VibrationSystem$Data,Holder,GameEvent$Context,Vec3,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
</summary>

```diff
+ boolean isValidVibration(GameEvent,GameEvent$Context)
- boolean isValidVibration(Holder,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- boolean lambda$mapMatcher$3(ItemStack,Integer,ItemStack)
- Predicate mapMatcher(ItemStack)
```

</details>
</details>
<hr/>