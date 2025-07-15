## Comparison with [21w18a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w18a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">21w18a</th><th>21w19a</th></tr><tr><td>World version</td><td><pre>2713</pre></td><td><pre>2714</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741850</pre></td><td><pre>1073741851</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ com.mojang:blocklist V1.0.5
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">21w18a</th><th>21w19a</th></tr><tr><td>com.mojang:patchy</td><td><pre>1.3.9</pre></td><td><pre>2.0.5</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
item
</summary>

```diff
- item block <pos: block_pos> <slot: item_slot> copy block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
- item block <pos: block_pos> <slot: item_slot> copy entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
- item block <pos: block_pos> <slot: item_slot> modify <modifier: resource_location>
- item block <pos: block_pos> <slot: item_slot> replace <item: item_stack> <count: integer>
- item entity <targets: entity> <slot: item_slot> copy block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
- item entity <targets: entity> <slot: item_slot> copy entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
- item entity <targets: entity> <slot: item_slot> modify <modifier: resource_location>
- item entity <targets: entity> <slot: item_slot> replace <item: item_stack> <count: integer>
+ item modify block <pos: block_pos> <slot: item_slot> <modifier: resource_location>
+ item modify entity <targets: entity> <slot: item_slot> <modifier: resource_location>
+ item replace block <pos: block_pos> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace block <pos: block_pos> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace block <pos: block_pos> <slot: item_slot> with <item: item_stack> <count: integer>
+ item replace entity <targets: entity> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace entity <targets: entity> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace entity <targets: entity> <slot: item_slot> with <item: item_stack> <count: integer>
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
- black_candle.json
- blue_candle.json
- brown_candle.json
- bundle.json
- candle.json
- cyan_candle.json
- gray_candle.json
- green_candle.json
- light_blue_candle.json
- light_gray_candle.json
- lime_candle.json
- magenta_candle.json
- orange_candle.json
- pink_candle.json
- purple_candle.json
- red_candle.json
- white_candle.json
- yellow_candle.json
```

</details>
<details>
<summary>
copper_ingot.json
</summary>

```
Group: none -> copper_ingot
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
+ disconnect.unknownHost: Unknown host
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>21w18a</th><th>21w19a</th></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.white_candle_cake</div></th><td>White Candle Cake</td><td>Cake with White Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.orange_candle_cake</div></th><td>Orange Candle Cake</td><td>Cake with Orange Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.magenta_candle_cake</div></th><td>Magenta Candle Cake</td><td>Cake with Magenta Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.light_blue_candle_cake</div></th><td>Light Blue Candle Cake</td><td>Cake with Light Blue Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.yellow_candle_cake</div></th><td>Yellow Candle Cake</td><td>Cake with Yellow Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.lime_candle_cake</div></th><td>Lime Candle Cake</td><td>Cake with Lime Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.pink_candle_cake</div></th><td>Pink Candle Cake</td><td>Cake with Pink Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.gray_candle_cake</div></th><td>Gray Candle Cake</td><td>Cake with Gray Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.light_gray_candle_cake</div></th><td>Light Gray Candle Cake</td><td>Cake with Light Gray Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.cyan_candle_cake</div></th><td>Cyan Candle Cake</td><td>Cake with Cyan Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.purple_candle_cake</div></th><td>Purple Candle Cake</td><td>Cake with Purple Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.blue_candle_cake</div></th><td>Blue Candle Cake</td><td>Cake with Blue Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.brown_candle_cake</div></th><td>Brown Candle Cake</td><td>Cake with Brown Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.green_candle_cake</div></th><td>Green Candle Cake</td><td>Cake with Green Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.red_candle_cake</div></th><td>Red Candle Cake</td><td>Cake with Red Candle</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.black_candle_cake</div></th><td>Black Candle Cake</td><td>Cake with Black Candle</td></tr>
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
- minecraft/advancements/recipes/decorations/black_candle.json
- minecraft/advancements/recipes/decorations/blue_candle.json
- minecraft/advancements/recipes/decorations/brown_candle.json
- minecraft/advancements/recipes/decorations/candle.json
- minecraft/advancements/recipes/decorations/cyan_candle.json
- minecraft/advancements/recipes/decorations/gray_candle.json
- minecraft/advancements/recipes/decorations/green_candle.json
- minecraft/advancements/recipes/decorations/light_blue_candle.json
- minecraft/advancements/recipes/decorations/light_gray_candle.json
- minecraft/advancements/recipes/decorations/lime_candle.json
- minecraft/advancements/recipes/decorations/magenta_candle.json
- minecraft/advancements/recipes/decorations/orange_candle.json
- minecraft/advancements/recipes/decorations/pink_candle.json
- minecraft/advancements/recipes/decorations/purple_candle.json
- minecraft/advancements/recipes/decorations/red_candle.json
- minecraft/advancements/recipes/decorations/white_candle.json
- minecraft/advancements/recipes/decorations/yellow_candle.json
- minecraft/advancements/recipes/tools/bundle.json
- minecraft/recipes/black_candle.json
- minecraft/recipes/blue_candle.json
- minecraft/recipes/brown_candle.json
- minecraft/recipes/bundle.json
- minecraft/recipes/candle.json
- minecraft/recipes/cyan_candle.json
- minecraft/recipes/gray_candle.json
- minecraft/recipes/green_candle.json
- minecraft/recipes/light_blue_candle.json
- minecraft/recipes/light_gray_candle.json
- minecraft/recipes/lime_candle.json
- minecraft/recipes/magenta_candle.json
- minecraft/recipes/orange_candle.json
- minecraft/recipes/pink_candle.json
- minecraft/recipes/purple_candle.json
- minecraft/recipes/red_candle.json
- minecraft/recipes/white_candle.json
- minecraft/recipes/yellow_candle.json
+ minecraft/tags/blocks/mineable/axe.json
+ minecraft/tags/blocks/mineable/hoe.json
+ minecraft/tags/blocks/mineable/pickaxe.json
+ minecraft/tags/blocks/mineable/shovel.json
+ minecraft/tags/blocks/needs_diamond_tool.json
+ minecraft/tags/blocks/needs_iron_tool.json
+ minecraft/tags/blocks/needs_stone_tool.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
splashes
</summary>

```diff
+ Now Java 16!
- Now Java 8!
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
- net.minecraft.package-info
+ XXX.advancements.critereon.AbstractCriterionTriggerInstance
- XXX.advancements.critereon.BeeNestDestroyedTrigger
+ XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
- XXX.advancements.critereon.BlockPredicate
+ XXX.advancements.critereon.BlockPredicate$Builder
- XXX.advancements.critereon.BredAnimalsTrigger
+ XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
- XXX.advancements.critereon.BrewedPotionTrigger
+ XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
- XXX.advancements.critereon.ChangeDimensionTrigger
+ XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
- XXX.advancements.critereon.ChanneledLightningTrigger
+ XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
- XXX.advancements.critereon.ConstructBeaconTrigger
+ XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
- XXX.advancements.critereon.ConsumeItemTrigger
+ XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
- XXX.advancements.critereon.CuredZombieVillagerTrigger
+ XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- XXX.advancements.critereon.DamagePredicate
+ XXX.advancements.critereon.DamagePredicate$Builder
- XXX.advancements.critereon.DamageSourcePredicate
+ XXX.advancements.critereon.DamageSourcePredicate$Builder
- XXX.advancements.critereon.DeserializationContext
+ XXX.advancements.critereon.DistancePredicate
- XXX.advancements.critereon.EffectsChangedTrigger
+ XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantedItemTrigger
+ XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantmentPredicate
+ XXX.advancements.critereon.EnterBlockTrigger
- XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityEquipmentPredicate
- XXX.advancements.critereon.EntityEquipmentPredicate$Builder
+ XXX.advancements.critereon.EntityFlagsPredicate
- XXX.advancements.critereon.EntityFlagsPredicate$Builder
+ XXX.advancements.critereon.EntityHurtPlayerTrigger
- XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityPredicate
+ XXX.advancements.critereon.LightPredicate$1
- XXX.advancements.critereon.LightPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate
- XXX.advancements.critereon.LocationPredicate$Builder
+ XXX.advancements.critereon.LocationTrigger
- XXX.advancements.critereon.LocationTrigger$TriggerInstance
+ XXX.advancements.critereon.LootTableTrigger
- XXX.advancements.critereon.LootTableTrigger$TriggerInstance
+ XXX.advancements.critereon.MinMaxBounds
- XXX.advancements.critereon.MinMaxBounds$BoundsFactory
+ XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- XXX.advancements.critereon.MinMaxBounds$Floats
+ XXX.advancements.critereon.MinMaxBounds$Ints
- XXX.advancements.critereon.MobEffectsPredicate
+ XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.critereon.NbtPredicate
+ XXX.advancements.critereon.NetherTravelTrigger
- XXX.advancements.critereon.NetherTravelTrigger$TriggerInstance
- XXX.advancements.critereon.package-info
+ XXX.advancements.critereon.PlacedBlockTrigger
- XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerHurtEntityTrigger
- XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerInteractTrigger
- XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$Builder
- XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
+ XXX.advancements.critereon.SummonedEntityTrigger
- XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.TameAnimalTrigger
- XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ XXX.advancements.critereon.TargetBlockTrigger
- XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.TickTrigger
- XXX.advancements.critereon.TickTrigger$TriggerInstance
+ XXX.advancements.critereon.TradeTrigger
- XXX.advancements.critereon.TradeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.AttributeSupplier$Builder
+ XXX.ai.attributes.DefaultAttributes
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
- XXX.ai.behavior.AnimalMakeLove
+ XXX.ai.behavior.AnimalPanic
- XXX.ai.behavior.AssignProfessionFromJobSite
+ XXX.ai.behavior.BabyFollowAdult
- XXX.ai.behavior.BackUpIfTooClose
+ XXX.ai.behavior.BecomePassiveIfMemoryPresent
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosTracker
- XXX.ai.behavior.CelebrateVillagersSurvivedRaid
+ XXX.ai.behavior.CopyMemoryWithExpiry
- XXX.ai.behavior.CountDownCooldownTicks
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.FollowTemptation
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$1
- XXX.ai.behavior.package-info
+ XXX.ai.behavior.ShufflingList$WeightedEntry
- XXX.ai.behavior.ShufflingList$WeightedEntry$1
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TryFindWater
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerMakeLove
+ XXX.ai.behavior.VillagerPanicTrigger
- XXX.ai.behavior.WakeUp
+ XXX.ai.behavior.WorkAtComposter
- XXX.ai.behavior.WorkAtPoi
+ XXX.ai.behavior.YieldJobSite
+ XXX.ai.control.BodyRotationControl
- XXX.ai.control.Control
+ XXX.ai.control.FlyingMoveControl
- XXX.ai.control.JumpControl
+ XXX.ai.control.LookControl
- XXX.ai.control.MoveControl
+ XXX.ai.control.MoveControl$Operation
- XXX.ai.control.package-info
- XXX.ai.control.SmoothSwimmingLookControl
+ XXX.ai.control.SmoothSwimmingMoveControl
+ XXX.ai.goal.AvoidEntityGoal
- XXX.ai.goal.BegGoal
+ XXX.ai.goal.BoatGoals
- XXX.ai.goal.BreakDoorGoal
+ XXX.ai.goal.BreathAirGoal
- XXX.ai.goal.BreedGoal
+ XXX.ai.goal.CatLieOnBedGoal
- XXX.ai.goal.CatSitOnBlockGoal
+ XXX.ai.goal.DolphinJumpGoal
- XXX.ai.goal.DoorInteractGoal
+ XXX.ai.goal.EatBlockGoal
- XXX.ai.goal.FleeSunGoal
+ XXX.ai.goal.FloatGoal
- XXX.ai.goal.FollowBoatGoal
+ XXX.ai.goal.FollowFlockLeaderGoal
- XXX.ai.goal.FollowMobGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.GolemRandomStrollInVillageGoal
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillageGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.package-info
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
+ XXX.ai.goal.RandomLookAroundGoal
- XXX.ai.goal.RandomStrollGoal
+ XXX.ai.goal.RandomSwimmingGoal
- XXX.ai.goal.RangedAttackGoal
+ XXX.ai.goal.RangedBowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- XXX.ai.goal.RemoveBlockGoal
+ XXX.ai.goal.RestrictSunGoal
- XXX.ai.goal.RunAroundLikeCrazyGoal
+ XXX.ai.goal.SitWhenOrderedToGoal
- XXX.ai.goal.StrollThroughVillageGoal
+ XXX.ai.goal.SwellGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$1
+ XXX.animal.axolotl.Axolotl
- XXX.animal.axolotl.Axolotl$AxolotlGroupData
+ XXX.animal.axolotl.Axolotl$AxolotlLookControl
- XXX.animal.axolotl.Axolotl$AxolotlMoveControl
+ XXX.animal.axolotl.Axolotl$AxolotlPathNavigation
- XXX.animal.axolotl.Axolotl$Variant
+ XXX.animal.axolotl.AxolotlAi
- XXX.animal.axolotl.package-info
- XXX.animal.axolotl.PlayDead
+ XXX.animal.axolotl.ValidatePlayDead
+ XXX.animal.goat.Goat
+ XXX.animal.horse.Llama$1
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Markings
- XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.Variant
- XXX.animal.horse.ZombieHorse
+ XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
- XXX.arguments.blocks.BlockPredicateArgument$Result
+ XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
- XXX.arguments.blocks.BlockStateArgument
+ XXX.arguments.blocks.BlockStateParser
- XXX.arguments.blocks.package-info
+ XXX.arguments.coordinates.BlockPosArgument
- XXX.arguments.coordinates.ColumnPosArgument
+ XXX.arguments.coordinates.Coordinates
- XXX.arguments.coordinates.LocalCoordinates
+ XXX.arguments.coordinates.package-info
+ XXX.arguments.coordinates.RotationArgument
- XXX.arguments.coordinates.SwizzleArgument
+ XXX.arguments.coordinates.Vec2Argument
- XXX.arguments.coordinates.Vec3Argument
+ XXX.arguments.coordinates.WorldCoordinate
- XXX.arguments.coordinates.WorldCoordinates
- XXX.arguments.item.FunctionArgument
+ XXX.arguments.item.FunctionArgument$1
- XXX.arguments.item.FunctionArgument$2
+ XXX.arguments.item.FunctionArgument$Result
- XXX.arguments.item.ItemArgument
+ XXX.arguments.item.ItemInput
- XXX.arguments.item.ItemParser
+ XXX.arguments.item.ItemPredicateArgument
- XXX.arguments.item.ItemPredicateArgument$ItemPredicate
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.ItemPredicateArgument$TagPredicate
+ XXX.arguments.item.package-info
+ XXX.arguments.selector.EntitySelector
- XXX.arguments.selector.EntitySelector$1
+ XXX.arguments.selector.EntitySelectorParser
+ XXX.block.entity.BeehiveBlockEntity$1
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.AzaleaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
+ XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.block.state.StateHolder$1
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.commands.arguments.AngleArgument
- XXX.commands.arguments.package-info
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
+ XXX.commands.synchronization.ArgumentTypes$1
- XXX.commands.synchronization.ArgumentTypes$Entry
+ XXX.commands.synchronization.EmptyArgumentSerializer
- XXX.commands.synchronization.package-info
- XXX.commands.synchronization.SuggestionProviders
+ XXX.commands.synchronization.SuggestionProviders$Wrapper
- XXX.core.cauldron.CauldronInteraction
+ XXX.core.dispenser.AbstractProjectileDispenseBehavior
- XXX.core.dispenser.BoatDispenseItemBehavior
+ XXX.core.dispenser.DefaultDispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior$1
- XXX.core.dispenser.DispenseItemBehavior$10
+ XXX.core.dispenser.DispenseItemBehavior$11
- XXX.core.dispenser.DispenseItemBehavior$12
+ XXX.core.dispenser.DispenseItemBehavior$13
- XXX.core.dispenser.DispenseItemBehavior$14
+ XXX.core.dispenser.DispenseItemBehavior$15
- XXX.core.dispenser.DispenseItemBehavior$16
+ XXX.core.dispenser.DispenseItemBehavior$17
- XXX.core.dispenser.DispenseItemBehavior$18
+ XXX.core.dispenser.DispenseItemBehavior$19
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$20
- XXX.core.dispenser.DispenseItemBehavior$21
+ XXX.core.dispenser.DispenseItemBehavior$22
- XXX.core.dispenser.DispenseItemBehavior$23
+ XXX.core.dispenser.DispenseItemBehavior$24
- XXX.core.dispenser.DispenseItemBehavior$25
+ XXX.core.dispenser.DispenseItemBehavior$26
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.package-info
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.BlockParticleOption$1
- XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustColorTransitionOptions$1
- XXX.core.particles.DustParticleOptions
+ XXX.core.particles.DustParticleOptions$1
- XXX.core.particles.DustParticleOptionsBase
+ XXX.core.particles.ItemParticleOption
- XXX.core.particles.ItemParticleOption$1
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleGroup
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleOptions$Deserializer
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
+ XXX.core.particles.VibrationParticleOption
- XXX.core.particles.VibrationParticleOption$1
+ XXX.data.models.package-info
+ XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapedRecipeBuilder$Result
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder$Result
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder$Result
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder$Result
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder$1
- XXX.data.recipes.UpgradeRecipeBuilder
+ XXX.data.recipes.UpgradeRecipeBuilder$Result
+ XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BlockTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.TagsProvider
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.fixes.BedBlockEntityInjecter
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehivePoiRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$1
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.package-info
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRename
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenameBiomesFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.SavedDataVillageCropFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
- XXX.datafix.schemas.NamespacedSchema$1
+ XXX.datafix.schemas.package-info
+ XXX.datafix.schemas.V100
- XXX.datafix.schemas.V102
+ XXX.datafix.schemas.V1022
- XXX.datafix.schemas.V106
+ XXX.datafix.schemas.V107
- XXX.datafix.schemas.V1125
+ XXX.datafix.schemas.V135
- XXX.datafix.schemas.V143
+ XXX.datafix.schemas.V1451
- XXX.datafix.schemas.V1451_1
+ XXX.datafix.schemas.V1451_2
- XXX.datafix.schemas.V1451_3
+ XXX.datafix.schemas.V1451_4
- XXX.datafix.schemas.V1451_5
+ XXX.datafix.schemas.V1451_6
- XXX.datafix.schemas.V1451_7
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1460$1
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
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
+ XXX.enderdragon.phases.AbstractDragonPhaseInstance
- XXX.enderdragon.phases.AbstractDragonSittingPhase
+ XXX.enderdragon.phases.DragonChargePlayerPhase
- XXX.enderdragon.phases.DragonDeathPhase
+ XXX.enderdragon.phases.DragonHoldingPatternPhase
- XXX.enderdragon.phases.DragonHoverPhase
+ XXX.enderdragon.phases.DragonLandingApproachPhase
- XXX.enderdragon.phases.DragonLandingPhase
+ XXX.enderdragon.phases.DragonPhaseInstance
- XXX.enderdragon.phases.DragonSittingAttackingPhase
+ XXX.enderdragon.phases.DragonSittingFlamingPhase
- XXX.enderdragon.phases.DragonSittingScanningPhase
+ XXX.enderdragon.phases.DragonStrafePlayerPhase
- XXX.enderdragon.phases.DragonTakeoffPhase
+ XXX.enderdragon.phases.EnderDragonPhase
- XXX.enderdragon.phases.EnderDragonPhaseManager
+ XXX.enderdragon.phases.package-info
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.package-info
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
+ XXX.entity.animal.TropicalFish
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
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$1
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.ItemFrame$1
+ XXX.entity.decoration.ItemFrame$2
- XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.Motive
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
+ XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
+ XXX.entity.monster.Illusioner$1
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
+ XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$1
+ XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
- XXX.entity.monster.Ravager$RavagerNavigation
+ XXX.entity.monster.Ravager$RavagerNodeEvaluator
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$1
+ XXX.entity.monster.Strider$1
- XXX.entity.monster.Strider$StriderGoToLavaGoal
+ XXX.entity.monster.Strider$StriderPathNavigation
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zoglin
- XXX.entity.monster.Zombie
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
- XXX.entity.monster.ZombifiedPiglin
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
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$1
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.AbstractMinecartContainer$1
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.Boat$1
+ XXX.entity.vehicle.Boat$Status
- XXX.entity.vehicle.Boat$Type
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
+ XXX.feature.configurations.OreConfiguration$1
- XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.LegacySinglePoolElement
- XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
+ XXX.goal.target.package-info
+ XXX.goal.target.ResetUniversalAngerTargetGoal
- XXX.goal.target.TargetGoal
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.layer.traits.AreaTransformer0
+ XXX.layer.traits.AreaTransformer1
- XXX.layer.traits.AreaTransformer2
+ XXX.layer.traits.BishopTransformer
- XXX.layer.traits.C0Transformer
+ XXX.layer.traits.C1Transformer
- XXX.layer.traits.CastleTransformer
+ XXX.layer.traits.DimensionOffset0Transformer
- XXX.layer.traits.DimensionOffset1Transformer
+ XXX.layer.traits.DimensionTransformer
+ XXX.layer.traits.package-info
- XXX.layer.traits.PixelTransformer
+ XXX.level.biome.BiomeGenerationSettings$Builder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.MobSpawnSettings$1
- XXX.level.biome.MobSpawnSettings$Builder
+ XXX.level.biome.MobSpawnSettings$MobSpawnCost
- XXX.level.biome.MobSpawnSettings$SpawnerData
+ XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.block.package-info
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkBiomeContainer
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$1
- XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.Palette
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.ProtoTickList
+ XXX.level.chunk.UpgradeData
+ XXX.level.entity.PersistentEntitySectionManager$1
- XXX.level.entity.PersistentEntitySectionManager$Callback
+ XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- XXX.level.entity.TransientEntitySectionManager
+ XXX.level.entity.TransientEntitySectionManager$1
+ XXX.level.levelgen.package-info
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.FlatDataLayer
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
- XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelVersion
- XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.NoiseEffect
- XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.RuinedPortalFeature
+ XXX.levelgen.feature.RuinedPortalFeature$FeatureStart
- XXX.levelgen.feature.RuinedPortalFeature$Type
+ XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.ShipwreckFeature
+ XXX.levelgen.feature.ShipwreckFeature$FeatureStart
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SmallDripstoneFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
- XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.placement.CarvingMaskDecorator
+ XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
- XXX.levelgen.placement.CaveDecoratorConfiguration
+ XXX.levelgen.placement.CaveSurface
- XXX.levelgen.placement.CaveSurfaceDecorator
+ XXX.levelgen.placement.ChanceDecorator
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountDecorator
+ XXX.levelgen.placement.CountNoiseDecorator
- XXX.levelgen.placement.CountWithExtraChanceDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DecoratedDecorator
+ XXX.levelgen.placement.DecoratedDecoratorConfiguration
- XXX.levelgen.placement.DecorationContext
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- XXX.levelgen.placement.HeightmapDecorator
+ XXX.levelgen.placement.HeightmapDoubleDecorator
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.NoiseBasedDecorator
+ XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.RangeDecorator
- XXX.levelgen.placement.RepeatingDecorator
+ XXX.levelgen.placement.Spread32Decorator
- XXX.levelgen.placement.SquareDecorator
+ XXX.levelgen.placement.VerticalDecorator
- XXX.levelgen.placement.WaterDepthThresholdConfiguration
+ XXX.levelgen.placement.WaterDepthThresholdDecorator
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.WoodlandMansionPieces$1
- XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.levelgen.synth.SurfaceNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$1
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$1
+ XXX.loot.entries.LootTableReference$1
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$1
+ XXX.loot.functions.CopyNameFunction$1
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$1
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetEnchantmentsFunction$1
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$1
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNbtFunction$1
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParamSet
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.ConditionReference$1
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$1
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck$1
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$1
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$1
+ XXX.loot.predicates.ValueCheckCondition$1
- XXX.loot.predicates.ValueCheckCondition$Serializer
+ XXX.loot.predicates.WeatherCheck
+ XXX.minecraft.advancements.Advancement$1
- XXX.minecraft.advancements.Advancement$Builder
+ XXX.minecraft.advancements.AdvancementList
- XXX.minecraft.advancements.AdvancementList$Listener
+ XXX.minecraft.advancements.AdvancementProgress
- XXX.minecraft.advancements.AdvancementProgress$Serializer
+ XXX.minecraft.advancements.AdvancementRewards
- XXX.minecraft.advancements.AdvancementRewards$Builder
+ XXX.minecraft.advancements.CriteriaTriggers
- XXX.minecraft.advancements.Criterion
+ XXX.minecraft.advancements.CriterionProgress
- XXX.minecraft.advancements.CriterionTrigger
+ XXX.minecraft.advancements.CriterionTrigger$Listener
- XXX.minecraft.advancements.CriterionTriggerInstance
+ XXX.minecraft.advancements.DisplayInfo
- XXX.minecraft.advancements.FrameType
+ XXX.minecraft.advancements.package-info
+ XXX.minecraft.advancements.RequirementsStrategy
- XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CommandFunction
- XXX.minecraft.commands.CommandFunction$CacheableFunction
+ XXX.minecraft.commands.CommandFunction$CommandEntry
- XXX.minecraft.commands.CommandFunction$Entry
+ XXX.minecraft.commands.CommandFunction$FunctionEntry
- XXX.minecraft.commands.CommandRuntimeException
- XXX.minecraft.commands.Commands
+ XXX.minecraft.commands.Commands$CommandSelection
- XXX.minecraft.commands.Commands$ParseFunction
+ XXX.minecraft.commands.CommandSource
- XXX.minecraft.commands.CommandSource$1
+ XXX.minecraft.commands.CommandSourceStack
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ XXX.minecraft.core.AxisCycle
- XXX.minecraft.core.AxisCycle$1
+ XXX.minecraft.core.AxisCycle$2
- XXX.minecraft.core.AxisCycle$3
+ XXX.minecraft.core.BlockMath
- XXX.minecraft.core.BlockPos
+ XXX.minecraft.core.BlockPos$1
- XXX.minecraft.core.BlockPos$2
+ XXX.minecraft.core.BlockPos$3
- XXX.minecraft.core.BlockPos$4
+ XXX.minecraft.core.BlockPos$5
- XXX.minecraft.core.BlockPos$MutableBlockPos
+ XXX.minecraft.core.BlockSource
- XXX.minecraft.core.BlockSourceImpl
+ XXX.minecraft.core.Cursor3D
- XXX.minecraft.core.DefaultedRegistry
+ XXX.minecraft.core.Direction
- XXX.minecraft.core.Direction$1
+ XXX.minecraft.core.Direction$Axis
- XXX.minecraft.core.Direction$Axis$1
+ XXX.minecraft.core.Direction$Axis$2
- XXX.minecraft.core.Direction$Axis$3
+ XXX.minecraft.core.Direction$AxisDirection
- XXX.minecraft.core.Direction$Plane
+ XXX.minecraft.core.Direction8
- XXX.minecraft.core.FrontAndTop
+ XXX.minecraft.core.GlobalPos
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.MappedRegistry$RegistryEntry
- XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.package-info
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryData
+ XXX.minecraft.core.RegistryAccess$RegistryHolder
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.SerializableUUID
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
- XXX.minecraft.data.BlockFamilies
+ XXX.minecraft.data.BlockFamily
- XXX.minecraft.data.package-info
+ XXX.minecraft.network.ConnectionProtocol$1
- XXX.minecraft.network.ConnectionProtocol$PacketSet
+ XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.RegistryDataPackCodec
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryLookupCodec
- XXX.minecraft.resources.RegistryReadOps
+ XXX.minecraft.resources.RegistryReadOps$1
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$1
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$1
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.SerializationTags
- XXX.minecraft.tags.SetTag
+ XXX.minecraft.tags.StaticTagHelper
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$BuilderEntry
+ XXX.minecraft.tags.Tag$ElementEntry
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$Named
- XXX.minecraft.tags.Tag$OptionalElementEntry
+ XXX.minecraft.tags.Tag$OptionalTagEntry
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagCollection$1
+ XXX.minecraft.tags.TagCollection$NetworkPayload
- XXX.minecraft.tags.TagContainer
+ XXX.minecraft.tags.TagContainer$1
- XXX.minecraft.tags.TagContainer$Builder
+ XXX.minecraft.tags.TagContainer$CollectionConsumer
- XXX.minecraft.tags.TagLoader
+ XXX.minecraft.tags.TagManager
+ XXX.minecraft.util.CsvOutput$1
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$XorCodec
+ XXX.minecraft.util.FastColor
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HeapDumper
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$2
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
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
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.Snooper
- XXX.minecraft.world.Snooper$1
+ XXX.minecraft.world.SnooperPopulator
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
+ XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$Operation
+ XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$1
+ XXX.models.blockstates.package-info
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
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$1
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
- XXX.network.chat.BaseComponent
+ XXX.network.chat.ChatType
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.ContextAwareComponent
+ XXX.network.chat.FormattedText
- XXX.network.chat.FormattedText$1
+ XXX.network.chat.FormattedText$2
- XXX.network.chat.FormattedText$3
+ XXX.network.chat.FormattedText$4
- XXX.network.chat.FormattedText$ContentConsumer
+ XXX.network.chat.FormattedText$StyledContentConsumer
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.KeybindComponent
+ XXX.network.chat.MutableComponent
- XXX.network.chat.NbtComponent
+ XXX.network.chat.NbtComponent$BlockNbtComponent
- XXX.network.chat.NbtComponent$EntityNbtComponent
+ XXX.network.chat.NbtComponent$StorageNbtComponent
- XXX.network.chat.package-info
- XXX.network.chat.ScoreComponent
+ XXX.network.chat.SelectorComponent
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$Serializer
+ XXX.network.chat.SubStringSource
- XXX.network.chat.TextColor
+ XXX.network.chat.TextComponent
- XXX.network.chat.TranslatableComponent
+ XXX.network.chat.TranslatableFormatException
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$10
- XXX.network.syncher.EntityDataSerializers$11
+ XXX.network.syncher.EntityDataSerializers$12
- XXX.network.syncher.EntityDataSerializers$13
+ XXX.network.syncher.EntityDataSerializers$14
- XXX.network.syncher.EntityDataSerializers$15
+ XXX.network.syncher.EntityDataSerializers$16
- XXX.network.syncher.EntityDataSerializers$17
+ XXX.network.syncher.EntityDataSerializers$18
- XXX.network.syncher.EntityDataSerializers$19
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.EntityDataSerializers$8
- XXX.network.syncher.EntityDataSerializers$9
+ XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.newbiome.area.Area
- XXX.newbiome.area.AreaFactory
+ XXX.newbiome.area.LazyArea
- XXX.newbiome.area.package-info
+ XXX.newbiome.context.BigContext
- XXX.newbiome.context.Context
+ XXX.newbiome.context.LazyAreaContext
- XXX.newbiome.context.package-info
+ XXX.newbiome.layer.AddDeepOceanLayer
- XXX.newbiome.layer.AddEdgeLayer
+ XXX.newbiome.layer.AddEdgeLayer$CoolWarm
- XXX.newbiome.layer.AddEdgeLayer$HeatIce
+ XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- XXX.newbiome.layer.AddIslandLayer
+ XXX.newbiome.layer.AddMushroomIslandLayer
- XXX.newbiome.layer.AddSnowLayer
+ XXX.newbiome.layer.BiomeEdgeLayer
- XXX.newbiome.layer.BiomeInitLayer
+ XXX.newbiome.layer.IslandLayer
- XXX.newbiome.layer.Layer
+ XXX.newbiome.layer.LayerBiomes
- XXX.newbiome.layer.Layers
+ XXX.newbiome.layer.Layers$Category
- XXX.newbiome.layer.OceanLayer
+ XXX.newbiome.layer.OceanMixerLayer
+ XXX.newbiome.layer.package-info
- XXX.newbiome.layer.RareBiomeLargeLayer
+ XXX.newbiome.layer.RareBiomeSpotLayer
- XXX.newbiome.layer.RegionHillsLayer
+ XXX.newbiome.layer.RemoveTooMuchOceanLayer
- XXX.newbiome.layer.RiverInitLayer
+ XXX.newbiome.layer.RiverLayer
- XXX.newbiome.layer.RiverMixerLayer
+ XXX.newbiome.layer.ShoreLayer
- XXX.newbiome.layer.SmoothLayer
+ XXX.newbiome.layer.ZoomLayer
- XXX.newbiome.layer.ZoomLayer$1
+ XXX.packs.resources.package-info
+ XXX.packs.resources.ProfiledReloadInstance$1
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManager$Empty
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadableResourceManager
- XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.packs.resources.SimpleResource
- XXX.placement.nether.CountMultiLayerDecorator
+ XXX.placement.nether.package-info
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddMobPacket
+ XXX.protocol.game.ClientboundAddPaintingPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
+ XXX.protocol.game.ClientboundAddVibrationSignalPacket
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockBreakAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$AddOperation
- XXX.protocol.game.ClientboundBossEventPacket$Handler
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundBossEventPacket$OperationType
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChatPacket
+ XXX.protocol.game.ClientboundClearTitlesPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundPingPacket
+ XXX.protocol.game.ClientboundPlaceGhostRecipePacket
- XXX.protocol.game.ClientboundPlayerAbilitiesPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$1
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.status.ClientboundPongResponsePacket
- XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundPingRequestPacket
+ XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Players$Serializer
- XXX.protocol.status.ServerStatus$Serializer
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatus$Version$Serializer
+ XXX.protocol.status.ServerStatusPacketListener
- XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.ConstantValue$1
- XXX.providers.number.ConstantValue$InlineSerializer
+ XXX.providers.number.ConstantValue$Serializer
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
+ XXX.providers.number.UniformGenerator$1
- XXX.providers.number.UniformGenerator$Serializer
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$1
+ XXX.providers.score.FixedScoreboardNameProvider$1
- XXX.providers.score.FixedScoreboardNameProvider$Serializer
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.selector.options.EntitySelectorOptions
+ XXX.selector.options.EntitySelectorOptions$1
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DeOpCommands
+ XXX.server.commands.package-info
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
+ XXX.server.commands.TeleportCommand$LookAt
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.ServerWatchdog
- XXX.server.dedicated.ServerWatchdog$1
+ XXX.server.dedicated.Settings
+ XXX.server.level.ChunkTaskPriorityQueueSorter$1
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$3
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.WorldGenRegion
- XXX.server.level.WorldGenTickList
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerGamePacketListenerImpl$2
- XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerPlayerConnection
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.network.TextFilter
+ XXX.server.network.TextFilter$1
- XXX.server.network.TextFilter$FilteredText
+ XXX.server.network.TextFilterClient
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$1
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$1
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.IntRange$Serializer
- XXX.storage.loot.ItemModifierManager
+ XXX.storage.loot.ItemModifierManager$FunctionSequence
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$1
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager$1
- XXX.storage.loot.PredicateManager$CompositePredicate
+ XXX.storage.loot.Serializer
- XXX.storage.loot.SerializerType
+ XXX.storage.loot.ValidationContext
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
- XXX.synchronization.brigadier.BrigadierArgumentSerializers
+ XXX.synchronization.brigadier.DoubleArgumentSerializer
- XXX.synchronization.brigadier.FloatArgumentSerializer
+ XXX.synchronization.brigadier.IntegerArgumentSerializer
- XXX.synchronization.brigadier.LongArgumentSerializer
+ XXX.synchronization.brigadier.package-info
+ XXX.synchronization.brigadier.StringArgumentSerializer
- XXX.synchronization.brigadier.StringArgumentSerializer$1
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.package-info
- XXX.util.datafix.PackedBitStorage
+ XXX.util.random.package-info
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
- XXX.util.valueproviders.ConstantFloat
+ XXX.util.valueproviders.ConstantInt
- XXX.util.valueproviders.FloatProvider
+ XXX.util.valueproviders.FloatProviderType
- XXX.util.valueproviders.IntProvider
+ XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.TrapezoidFloat
+ XXX.util.valueproviders.UniformFloat
- XXX.util.valueproviders.UniformInt
+ XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
- XXX.world.damagesource.BadRespawnPointDamage
+ XXX.world.damagesource.CombatEntry
- XXX.world.damagesource.CombatRules
+ XXX.world.damagesource.CombatTracker
- XXX.world.damagesource.DamageSource
+ XXX.world.damagesource.EntityDamageSource
- XXX.world.damagesource.IndirectEntityDamageSource
+ XXX.world.damagesource.package-info
- XXX.world.effect.AbsoptionMobEffect
+ XXX.world.effect.AttackDamageMobEffect
- XXX.world.effect.HealthBoostMobEffect
+ XXX.world.effect.InstantenousMobEffect
- XXX.world.effect.MobEffect
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveFunction
+ XXX.world.entity.Entity$MovementEmission
- XXX.world.entity.Entity$RemovalReason
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$1
+ XXX.world.entity.EntityType$Builder
- XXX.world.entity.EntityType$EntityFactory
+ XXX.world.entity.EquipmentSlot
- XXX.world.entity.EquipmentSlot$Type
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.FlyingMob
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.Marker
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.package-info
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.Pose
+ XXX.world.entity.PowerableMob
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacements$Type
- XXX.world.entity.TamableAnimal
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$1
+ XXX.world.item.ItemCooldowns$1
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$TooltipPart
+ XXX.world.item.ItemUtils
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MapItem
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignItem
+ XXX.world.item.SimpleFoiledItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.Tier
+ XXX.world.item.TieredItem
- XXX.world.item.Tiers
+ XXX.world.item.TippedArrowItem
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
- XXX.world.item.Vanishable
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.Wearable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.ChunkTickList$ScheduledTick
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.CollisionSpliterator
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EmptyTickList
+ XXX.world.level.EntityBasedExplosionDamageCalculator
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.ExplosionDamageCalculator
- XXX.world.level.FoliageColor
+ XXX.world.level.ForcedChunksSavedData
- XXX.world.level.GameRules
+ XXX.world.level.GameRules$1
- XXX.world.level.package-info
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.math.SymmetricGroup3 +2M -1M
```
```
net.minecraft.ChatFormatting +1M
```
```
net.minecraft.Util +3M -4M
```
```
net.minecraft.Util$OS +1M -1M
```
```
XXX.advancements.critereon.FilledBucketTrigger -1M
```
```
XXX.advancements.critereon.RecipeUnlockedTrigger -1M
```
```
XXX.advancements.critereon.SlideDownBlockTrigger -1M
```
```
XXX.advancements.critereon.StatePropertiesPredicate -1M
```
```
XXX.commands.arguments.AngleArgument$SingleAngle -1M
```
```
XXX.commands.arguments.EntityAnchorArgument$Anchor +1M -1M
```
```
XXX.commands.arguments.NbtPathArgument -1M
```
```
XXX.commands.arguments.ScoreHolderArgument +1M -2M
```
```
XXX.arguments.blocks.BlockPredicateArgument +1M -1M
```
```
XXX.selector.options.EntitySelectorOptions$Option -1M
```
```
XXX.data.models.BlockModelGenerators +40M -66M
```
```
XXX.models.blockstates.MultiPartGenerator$Entry -1M
```
```
XXX.data.tags.TagsProvider$TagAppender -1M
```
```
XXX.gametest.framework.GameTestBatchRunner +1M -3M
```
```
XXX.gametest.framework.GameTestSequence -1M
```
```
XXX.gametest.framework.TestCommand -1M
```
```
XXX.minecraft.nbt.ListTag -1M
```
```
XXX.minecraft.nbt.LongTag -1M
```
```
XXX.minecraft.nbt.NbtOps +1M -1M
```
```
XXX.minecraft.network.Connection$PacketHolder -2M
```
```
XXX.protocol.game.ClientboundCommandsPacket$Entry -2M
```
```
XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument +1M
```
```
XXX.protocol.game.ClientboundRecipePacket$State +1M
```
```
XXX.protocol.game.ClientboundUpdateAttributesPacket +2M -2M
```
```
XXX.protocol.game.DebugPackets +1M -1M
```
```
XXX.protocol.game.ServerboundInteractPacket -1M
```
```
XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction -2M
```
```
XXX.minecraft.server.ServerFunctionManager$QueuedCommand -1M
```
```
XXX.server.commands.DebugCommand$Tracer -1M
```
```
XXX.server.commands.EmoteCommands +2M -2M
```
```
XXX.server.commands.ExecuteCommand +20M -20M
```
```
XXX.server.commands.ExperienceCommand$Type +1M -1M
```
```
XXX.server.commands.FillCommand$Mode +1M
```
```
XXX.server.commands.GameRuleCommand -2M
```
```
XXX.server.commands.LootCommand +10M -10M
```
```
XXX.server.commands.SeedCommand +1M -1M
```
```
XXX.server.dedicated.Settings$MutableValue -1M
```
```
XXX.server.gui.MinecraftServerGui -2M
```
```
XXX.server.level.ChunkHolder$FullChunkStatus +1M
```
```
XXX.server.level.ChunkTaskPriorityQueue +1M -1M
```
```
XXX.server.level.ServerChunkCache$MainThreadExecutor -1M
```
```
XXX.server.level.ServerLevel +2M -6M
```
```
XXX.server.network.TextFilterClient$RequestFailedException -1M
```
```
XXX.packs.repository.Pack$Position +1M
```
```
XXX.minecraft.tags.StaticTagHelper$Wrapper -1M
```
```
XXX.minecraft.tags.Tag +2M -2M
```
```
XXX.minecraft.tags.TagManager$LoaderInfo -2M
```
```
XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory -1M
```
```
XXX.minecraft.util.SortedArraySet -3M
```
```
XXX.util.profiling.ActiveProfiler$PathEntry -5M
```
```
XXX.profiling.registry.MeasurementCategory +1M
```
```
XXX.ai.behavior.GateBehavior$RunningPolicy +1M -1M
```
```
XXX.ai.behavior.PoiCompetitorScan +1M -1M
```
```
XXX.ai.behavior.PrepareRamNearestTarget +1M -1M
```
```
XXX.ai.behavior.ShufflingList -1M
```
```
XXX.ai.sensing.NearestVisibleLivingEntitySensor +1M -1M
```
```
XXX.ai.targeting.TargetingConditions +4M -5M | +2P -4P
```
```
XXX.ai.util.HoverRandomPos +1M -1M
```
```
XXX.village.poi.PoiRecord +3M -3M
```
```
XXX.entity.animal.Bee +23M -43M
```
```
XXX.entity.animal.Bee$BaseBeeGoal -1M
```
```
XXX.entity.animal.Bee$BeeGoToHiveGoal -4M
```
```
XXX.entity.animal.Bee$BeeGrowCropGoal -1M
```
```
XXX.entity.animal.Bee$BeeLocateHiveGoal +1M -3M
```
```
XXX.entity.animal.Bee$BeePollinateGoal -2M
```
```
XXX.entity.animal.Dolphin +1M -2M
```
```
XXX.entity.animal.Ocelot -1M
```
```
XXX.entity.animal.Panda$Gene +1M -1M
```
```
XXX.entity.animal.Parrot -1M
```
```
XXX.entity.animal.Pufferfish -3M | +1P -1P
```
```
XXX.entity.animal.Rabbit -2M
```
```
XXX.entity.animal.Squid +2M -1M
```
```
XXX.entity.animal.TropicalFish$Pattern +1M
```
```
XXX.entity.animal.Turtle +2M -13M
```
```
XXX.animal.goat.Goat$GoatNodeEvaluator -1M
```
```
XXX.entity.monster.Evoker$EvokerAttackSpellGoal -1M
```
```
XXX.entity.monster.Evoker$EvokerSummonSpellGoal -1M
```
```
XXX.entity.monster.Guardian -2M
```
```
XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal -1M
```
```
XXX.entity.monster.Ravager +1M -1M
```
```
XXX.entity.monster.Slime +1M -2M
```
```
XXX.entity.monster.SpellcasterIllager +1M -1M
```
```
XXX.world.inventory.ClickAction +1M
```
```
XXX.world.inventory.GrindstoneMenu -1M
```
```
XXX.world.inventory.RecipeBookType +1M
```
```
XXX.world.item.ArmorMaterials +1M
```
```
XXX.world.item.DiggerItem +2M -1M | +1P -1P
```
```
XXX.world.item.HoeItem -1P
```
```
XXX.world.item.Item$Properties -7M
```
```
XXX.item.crafting.Ingredient$ItemValue -1M
```
```
XXX.item.crafting.RecipeManager +1M -1M
```
```
XXX.item.crafting.UpgradeRecipe -3M
```
```
XXX.item.enchantment.EnchantmentCategory +1M -1M
```
```
XXX.item.enchantment.ProtectionEnchantment$Type +1M
```
```
XXX.world.level.GameRules$Category +1M
```
```
XXX.world.level.GameRules$IntegerValue -1M
```
```
XXX.world.level.GameRules$Type -2M
```
```
XXX.world.level.LightLayer +1M
```
```
XXX.world.level.NaturalSpawner$SpawnState -4M
```
```
XXX.world.level.StructureFeatureManager +1M -1M
```
```
XXX.level.biome.AmbientMoodSettings +4M -4M
```
```
XXX.level.biome.Biome +14M -16M
```
```
XXX.level.biome.Biome$ClimateParameters +5M -5M
```
```
XXX.level.biome.Biome$Precipitation +1M
```
```
XXX.level.biome.BiomeGenerationSettings +4M -5M
```
```
XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer +1M
```
```
XXX.level.biome.MultiNoiseBiomeSource$PresetInstance +3M -4M
```
```
XXX.level.biome.OverworldBiomeSource +5M -5M
```
```
XXX.level.block.ComposterBlock -2M
```
```
XXX.level.block.DoubleBlockCombiner$BlockType +1M
```
```
XXX.level.block.LightBlock +1P
```
```
XXX.level.block.PowderSnowBlock -1M | +1P -1P
```
```
XXX.level.block.PressurePlateBlock$Sensitivity +1M
```
```
XXX.block.entity.BannerPattern +1M -1M
```
```
XXX.block.entity.BarrelBlockEntity -2M
```
```
XXX.state.properties.RailShape +1M
```
```
XXX.state.properties.SculkSensorPhase +1M
```
```
XXX.state.properties.StairsShape +1M
```
```
XXX.state.properties.Tilt +1M
```
```
XXX.level.border.BorderStatus +1M
```
```
XXX.chunk.storage.IOWorker$PendingStore -3M
```
```
XXX.chunk.storage.RegionFile -1M
```
```
XXX.chunk.storage.SectionStorage +1M -1M
```
```
XXX.level.entity.Visibility +1M
```
```
XXX.level.gameevent.BlockPositionSource +1M -2M
```
```
XXX.level.gameevent.EntityPositionSource +1M -2M
```
```
XXX.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus -2M
```
```
XXX.level.levelgen.Cavifier$QuantizedSpaghettiRarity -2M
```
```
XXX.level.levelgen.Column$Line -1M
```
```
XXX.level.levelgen.GenerationStep$Carving +1M
```
```
XXX.level.levelgen.GeodeBlockSettings +6M -6M
```
```
XXX.level.levelgen.GeodeLayerSettings +4M -4M
```
```
XXX.level.levelgen.Heightmap$Types +1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +3M -8M
```
```
XXX.level.levelgen.WorldGenSettings +1M -1M
```
```
XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration +6M -6M
```
```
XXX.levelgen.carver.CarverConfiguration +6M -6M
```
```
XXX.levelgen.feature.FossilFeatureConfiguration +5M -5M
```
```
XXX.levelgen.feature.HugeFungusConfiguration +5M -5M
```
```
XXX.levelgen.feature.JigsawFeature -3M
```
```
XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader -1M
```
```
XXX.levelgen.feature.WeightedConfiguredFeature +2M -2M
```
```
XXX.feature.configurations.DiskConfiguration +4M -4M
```
```
XXX.feature.configurations.EndGatewayConfiguration +2M -2M
```
```
XXX.feature.configurations.GeodeConfiguration +13M -13M
```
```
XXX.feature.configurations.GrowingPlantConfiguration +5M -5M
```
```
XXX.feature.configurations.HugeMushroomFeatureConfiguration +3M -3M
```
```
XXX.feature.configurations.LargeDripstoneConfiguration +9M -9M
```
```
XXX.feature.configurations.MineshaftConfiguration +2M -2M
```
```
XXX.feature.configurations.OceanRuinConfiguration +3M -3M
```
```
XXX.feature.configurations.ReplaceBlockConfiguration +1M -1M
```
```
XXX.feature.configurations.RootSystemConfiguration +12M -12M
```
```
XXX.feature.configurations.SpikeConfiguration +3M -3M
```
```
XXX.feature.configurations.TreeConfiguration +9M -9M
```
```
XXX.feature.configurations.UnderwaterMagmaConfiguration +3M -3M
```
```
XXX.feature.featuresize.TwoLayersFeatureSize +3M -3M
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +1M -1M
```
```
XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector -1M
```
```
XXX.levelgen.structure.MineShaftPieces -2M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition -6M
```
```
XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement +1M
```
```
XXX.levelgen.structure.ShipwreckPieces -1M
```
```
XXX.levelgen.structure.StrongholdPieces -3M
```
```
XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector -1M
```
```
XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType +1M
```
```
XXX.saveddata.maps.MapItemSavedData$HoldingPlayer -4M
```
```
XXX.storage.loot.IntRange -3M
```
```
XXX.storage.loot.LootPool -6M
```
```
XXX.loot.entries.EmptyLootItem -1M
```
```
XXX.loot.entries.LootPoolSingletonContainer -1M
```
```
XXX.loot.functions.ApplyExplosionDecay -1M
```
```
XXX.loot.functions.CopyNbtFunction$CopyOperation -1M
```
```
XXX.loot.functions.CopyNbtFunction$MergeStrategy$3 +1M -1M
```
```
XXX.loot.functions.EnchantRandomlyFunction -2M
```
```
XXX.loot.functions.ExplorationMapFunction -7M
```
```
XXX.loot.functions.LootingEnchantFunction -4M
```
```
XXX.loot.functions.SetBannerPatternFunction$Builder -1M
```
```
XXX.loot.functions.SetContainerContents +1M -3M
```
```
XXX.loot.functions.SetItemDamageFunction -3M
```
```
XXX.loot.functions.SmeltItemFunction -1M
```
```
XXX.loot.predicates.AlternativeLootItemCondition -2M
```
```
XXX.loot.predicates.EntityHasScoreCondition -3M
```
```
XXX.loot.predicates.LootItemEntityPropertyCondition -3M
```
```
XXX.loot.predicates.LootItemRandomChanceWithLootingCondition -3M
```
```
XXX.providers.nbt.StorageNbtProvider -2M
```
```
XXX.level.timers.TimerQueue$Event -1M
```
```
XXX.phys.shapes.Shapes +2M -2M
```
```
XXX.world.scores.Team$CollisionRule +1M
```

</details>
<details>
<summary>
com.mojang.math.SymmetricGroup3
</summary>

```diff
+ boolean lambda$null$0(int[],SymmetricGroup3)
- boolean lambda$static$0(int[],SymmetricGroup3)
- SymmetricGroup3[] $values()
```

</details>
<details>
<summary>
net.minecraft.ChatFormatting
</summary>

```diff
- ChatFormatting[] $values()
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ List lambda$null$4(Object,List)
+ List lambda$null$6(List,List)
- List lambda$sequence$4(Object,List)
- List lambda$sequence$6(List,List)
+ Logger access$100()
+ void lambda$null$8(CompletableFuture,List,int,Object,Throwable)
- void lambda$sequenceFailFast$8(CompletableFuture,List,int,Object,Throwable)
```

</details>
<details>
<summary>
net.minecraft.Util$OS
</summary>

```diff
- Util$OS[] $values()
+ void <init>(String,int,Util$1)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.FilledBucketTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeUnlockedTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.SlideDownBlockTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.StatePropertiesPredicate
</summary>

```diff
+ void <init>(List,StatePropertiesPredicate$1)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.AngleArgument$SingleAngle
</summary>

```diff
+ void <init>(float,boolean,AngleArgument$1)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
</summary>

```diff
- EntityAnchorArgument$Anchor[] $values()
+ Map access$000()
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.NbtPathArgument
</summary>

```diff
+ Predicate access$000(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.ScoreHolderArgument
</summary>

```diff
+ boolean access$000(ScoreHolderArgument)
+ void lambda$null$0(CommandContext,SuggestionsBuilder)
- void lambda$static$0(CommandContext,SuggestionsBuilder)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockPredicateArgument
</summary>

```diff
+ CommandSyntaxException lambda$null$2(ResourceLocation)
- CommandSyntaxException lambda$parse$2(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
</summary>

```diff
+ void <init>(EntitySelectorOptions$Modifier,Predicate,Component,EntitySelectorOptions$1)
```

</details>
<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
+ BiConsumer access$000(BlockModelGenerators)
+ BlockStateGenerator access$1200(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$1300(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$2000(Block,ResourceLocation)
+ BlockStateGenerator access$2100(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$500(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$600(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$700(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$800(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$900(Block,ResourceLocation,ResourceLocation)
+ Consumer access$200(BlockModelGenerators)
+ List access$1600(BlockModelGenerators)
- List lambda$createTurtleEgg$35(Integer,Integer)
+ List lambda$createTurtleEgg$39(Integer,Integer)
+ Map access$100(BlockModelGenerators)
+ Map access$1400(BlockModelGenerators)
+ Map access$1900()
+ MultiVariantGenerator access$300(Block,ResourceLocation)
- ResourceLocation lambda$createCropBlock$11(Block,int,int)
+ ResourceLocation lambda$null$15(Block,int,int)
- TextureMapping lambda$createChorusFlower$14(TextureMapping,ResourceLocation)
+ TextureMapping lambda$createChorusFlower$18(TextureMapping,ResourceLocation)
+ TextureMapping lambda$createCommandBlock$11(TextureMapping,ResourceLocation)
- TextureMapping lambda$createCommandBlock$7(TextureMapping,ResourceLocation)
+ Variant lambda$createActiveRail$10(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,RailShape)
- Variant lambda$createActiveRail$6(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,RailShape)
+ Variant lambda$createBambooModels$12(String,int)
- Variant lambda$createBambooModels$8(String,int)
- Variant lambda$createCropBlock$12(int[],Int2ObjectMap,Block,Integer)
+ Variant lambda$createCropBlock$16(int[],Int2ObjectMap,Block,Integer)
- Variant lambda$createEmptyOrFullDispatch$10(Comparable,Variant,Variant,Comparable)
+ Variant lambda$createEmptyOrFullDispatch$14(Comparable,Variant,Variant,Comparable)
- Variant lambda$createFire$16(Variant)
- Variant lambda$createFire$17(Variant)
- Variant lambda$createFire$18(Variant)
- Variant lambda$createFire$19(Variant)
+ Variant lambda$createFire$22(Variant)
+ Variant lambda$createFire$23(Variant)
+ Variant lambda$createFire$24(Variant)
+ Variant lambda$createFire$25(Variant)
- Variant lambda$createJigsaw$45(FrontAndTop)
+ Variant lambda$createJigsaw$49(FrontAndTop)
- Variant lambda$createRepeater$30(Integer,Boolean,Boolean)
+ Variant lambda$createRepeater$34(Integer,Boolean,Boolean)
- Variant lambda$createRespawnAnchor$44(ResourceLocation[],Integer)
+ Variant lambda$createRespawnAnchor$48(ResourceLocation[],Integer)
- Variant lambda$createSculkSensor$29(ResourceLocation,ResourceLocation,SculkSensorPhase)
+ Variant lambda$createSculkSensor$33(ResourceLocation,ResourceLocation,SculkSensorPhase)
- Variant lambda$createSnowBlocks$31(ResourceLocation,Integer)
+ Variant lambda$createSnowBlocks$35(ResourceLocation,Integer)
- Variant lambda$createSoulFire$22(Variant)
- Variant lambda$createSoulFire$23(Variant)
- Variant lambda$createSoulFire$24(Variant)
- Variant lambda$createSoulFire$25(Variant)
+ Variant lambda$createSoulFire$27(Variant)
+ Variant lambda$createSoulFire$28(Variant)
+ Variant lambda$createSoulFire$29(Variant)
+ Variant lambda$createSoulFire$30(Variant)
- Variant lambda$createStems$5(Block,TextureMapping,Integer)
+ Variant lambda$createStems$9(Block,TextureMapping,Integer)
- Variant lambda$createStructureBlock$32(StructureMode)
+ Variant lambda$createStructureBlock$36(StructureMode)
- Variant lambda$createSweetBerryBush$33(Integer)
+ Variant lambda$createSweetBerryBush$37(Integer)
- Variant lambda$createTripwireHook$34(Boolean,Boolean)
+ Variant lambda$createTripwireHook$38(Boolean,Boolean)
+ Variant lambda$null$40(ResourceLocation)
+ Variant lambda$null$41(ResourceLocation)
+ Variant lambda$null$42(ResourceLocation)
+ Variant lambda$null$43(ResourceLocation)
+ Variant lambda$null$44(ResourceLocation)
+ Variant lambda$null$45(ResourceLocation)
- Variant lambda$static$36(ResourceLocation)
- Variant lambda$static$37(ResourceLocation)
- Variant lambda$static$38(ResourceLocation)
- Variant lambda$static$39(ResourceLocation)
- Variant lambda$static$40(ResourceLocation)
- Variant lambda$static$41(ResourceLocation)
- Variant lambda$wrapModels$15(ResourceLocation)
+ Variant lambda$wrapModels$19(ResourceLocation)
+ void access$1000(BlockModelGenerators,Item)
+ void access$1100(BlockModelGenerators,Block)
+ void access$1500(BlockModelGenerators,Block)
+ void access$1700(BlockModelGenerators,Block)
+ void access$1800(BlockModelGenerators,Block)
+ void access$400(BlockModelGenerators,Block,ResourceLocation)
+ void lambda$createBarrel$13(ResourceLocation,TextureMapping)
- void lambda$createBarrel$9(ResourceLocation,TextureMapping)
- void lambda$createFurnace$13(ResourceLocation,TextureMapping)
+ void lambda$createFurnace$17(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$27(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$28(ResourceLocation,TextureMapping)
+ void lambda$createGrassBlocks$31(ResourceLocation,TextureMapping)
+ void lambda$createGrassBlocks$32(ResourceLocation,TextureMapping)
- void lambda$createMultiface$43(Block,MultiPartGenerator,ResourceLocation,BooleanProperty,Function)
+ void lambda$createMultiface$47(Block,MultiPartGenerator,ResourceLocation,BooleanProperty,Function)
- void lambda$run$46(BlockFamily)
- void lambda$run$47(SpawnEggItem)
+ void lambda$run$50(BlockFamily)
+ void lambda$run$51(SpawnEggItem)
- void lambda$static$42(HashMap)
+ void lambda$static$46(HashMap)
+ void lambda$static$5(Object,Block)
+ void lambda$static$6(Object,Block)
+ void lambda$static$7(Object,Block)
+ void lambda$static$8(Object,Block)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
</summary>

```diff
+ void <init>(List,MultiPartGenerator$1)
```

</details>
<details>
<summary>
net.minecraft.data.tags.TagsProvider$TagAppender
</summary>

```diff
+ void <init>(Tag$Builder,Registry,String,TagsProvider$1)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestBatchRunner
</summary>

```diff
- GameTestInfo lambda$new$0(Rotation,ServerLevel,TestFunction)
+ GameTestInfo lambda$null$0(Rotation,ServerLevel,TestFunction)
+ ServerLevel access$000(GameTestBatchRunner)
+ void access$100(GameTestBatchRunner,int)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestSequence
</summary>

```diff
+ GameTestInfo access$000(GameTestSequence)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.TestCommand
</summary>

```diff
+ void access$000(ServerLevel,MultipleTestTracker)
```

</details>
<details>
<summary>
net.minecraft.nbt.ListTag
</summary>

```diff
+ void <init>(List,byte,ListTag$1)
```

</details>
<details>
<summary>
net.minecraft.nbt.LongTag
</summary>

```diff
+ void <init>(long,LongTag$1)
```

</details>
<details>
<summary>
net.minecraft.nbt.NbtOps
</summary>

```diff
- void lambda$getMapEntries$7(BiConsumer,CompoundTag,String)
+ void lambda$null$7(BiConsumer,CompoundTag,String)
```

</details>
<details>
<summary>
net.minecraft.network.Connection$PacketHolder
</summary>

```diff
+ GenericFutureListener access$100(Connection$PacketHolder)
+ Packet access$000(Connection$PacketHolder)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
</summary>

```diff
+ CommandNode access$000(ClientboundCommandsPacket$Entry)
+ void <init>(ArgumentBuilder,byte,int,int[],ClientboundCommandsPacket$1)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
</summary>

```diff
- ClientboundPlayerPositionPacket$RelativeArgument[] $values()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRecipePacket$State
</summary>

```diff
- ClientboundRecipePacket$State[] $values()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
</summary>

```diff
- AttributeModifier lambda$new$0(FriendlyByteBuf)
+ AttributeModifier lambda$null$0(FriendlyByteBuf)
+ void lambda$null$2(FriendlyByteBuf,AttributeModifier)
- void lambda$write$2(FriendlyByteBuf,AttributeModifier)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.DebugPackets
</summary>

```diff
+ void lambda$null$6(List,String,GossipType,Integer)
- void lambda$writeBrain$6(List,String,GossipType,Integer)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundInteractPacket
</summary>

```diff
+ ServerboundInteractPacket$Action access$400()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
</summary>

```diff
+ void <init>(FriendlyByteBuf,ServerboundInteractPacket$1)
+ void <init>(InteractionHand,Vec3,ServerboundInteractPacket$1)
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionManager$QueuedCommand
</summary>

```diff
+ int access$400(ServerFunctionManager$QueuedCommand)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DebugCommand$Tracer
</summary>

```diff
+ void <init>(PrintWriter,DebugCommand$1)
```

</details>
<details>
<summary>
net.minecraft.server.commands.EmoteCommands
</summary>

```diff
+ Component lambda$null$0(ServerPlayer,Component,Component,ServerPlayer)
- Component lambda$register$0(ServerPlayer,Component,Component,ServerPlayer)
+ void lambda$null$1(CommandContext,MinecraftServer,ServerPlayer,Entity,TextFilter$FilteredText)
- void lambda$register$1(CommandContext,MinecraftServer,ServerPlayer,Entity,TextFilter$FilteredText)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ExecuteCommand
</summary>

```diff
- boolean lambda$addConditionals$40(Integer,Integer)
- boolean lambda$addConditionals$42(Integer,Integer)
- boolean lambda$addConditionals$44(Integer,Integer)
- boolean lambda$addConditionals$46(Integer,Integer)
+ boolean lambda$null$40(Integer,Integer)
+ boolean lambda$null$42(Integer,Integer)
+ boolean lambda$null$44(Integer,Integer)
+ boolean lambda$null$46(Integer,Integer)
- Collection lambda$addConditionals$52(boolean,DataCommands$DataProvider,CommandContext)
+ Collection lambda$null$52(boolean,DataCommands$DataProvider,CommandContext)
+ CommandSourceStack lambda$null$22(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$24(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$26(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$28(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$30(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$32(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$22(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$24(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$26(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$28(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$30(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$32(DataCommands$DataProvider,boolean,CommandContext)
- int lambda$addConditionals$53(DataCommands$DataProvider,CommandContext)
+ int lambda$null$53(DataCommands$DataProvider,CommandContext)
+ Tag lambda$null$21(CommandContext,int)
+ Tag lambda$null$23(CommandContext,int)
+ Tag lambda$null$25(CommandContext,int)
+ Tag lambda$null$27(CommandContext,int)
+ Tag lambda$null$29(CommandContext,int)
+ Tag lambda$null$31(CommandContext,int)
+ Tag lambda$null$36(IntFunction,int)
- Tag lambda$storeData$36(IntFunction,int)
- Tag lambda$wrapStores$21(CommandContext,int)
- Tag lambda$wrapStores$23(CommandContext,int)
- Tag lambda$wrapStores$25(CommandContext,int)
- Tag lambda$wrapStores$27(CommandContext,int)
- Tag lambda$wrapStores$29(CommandContext,int)
- Tag lambda$wrapStores$31(CommandContext,int)
+ void lambda$null$2(ResultConsumer,ResultConsumer,CommandContext,boolean,int)
- void lambda$static$2(ResultConsumer,ResultConsumer,CommandContext,boolean,int)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ExperienceCommand$Type
</summary>

```diff
- ExperienceCommand$Type[] $values()
+ ToIntFunction access$000(ExperienceCommand$Type)
```

</details>
<details>
<summary>
net.minecraft.server.commands.FillCommand$Mode
</summary>

```diff
- FillCommand$Mode[] $values()
```

</details>
<details>
<summary>
net.minecraft.server.commands.GameRuleCommand
</summary>

```diff
+ int access$000(CommandContext,GameRules$Key)
+ int access$100(CommandSourceStack,GameRules$Key)
```

</details>
<details>
<summary>
net.minecraft.server.commands.LootCommand
</summary>

```diff
+ int lambda$null$10(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$11(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$12(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$13(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$4(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$5(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$6(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$7(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$8(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$9(LootCommand$DropConsumer,CommandContext)
- int lambda$register$10(LootCommand$DropConsumer,CommandContext)
- int lambda$register$11(LootCommand$DropConsumer,CommandContext)
- int lambda$register$12(LootCommand$DropConsumer,CommandContext)
- int lambda$register$13(LootCommand$DropConsumer,CommandContext)
- int lambda$register$4(LootCommand$DropConsumer,CommandContext)
- int lambda$register$5(LootCommand$DropConsumer,CommandContext)
- int lambda$register$6(LootCommand$DropConsumer,CommandContext)
- int lambda$register$7(LootCommand$DropConsumer,CommandContext)
- int lambda$register$8(LootCommand$DropConsumer,CommandContext)
- int lambda$register$9(LootCommand$DropConsumer,CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SeedCommand
</summary>

```diff
+ Style lambda$null$1(long,Style)
- Style lambda$register$1(long,Style)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.Settings$MutableValue
</summary>

```diff
+ void <init>(Settings,String,Object,Function,Settings$1)
```

</details>
<details>
<summary>
net.minecraft.server.gui.MinecraftServerGui
</summary>

```diff
+ AtomicBoolean access$000(MinecraftServerGui)
+ void access$100(MinecraftServerGui)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkHolder$FullChunkStatus
</summary>

```diff
- ChunkHolder$FullChunkStatus[] $values()
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkTaskPriorityQueue
</summary>

```diff
+ Either lambda$null$5(long)
- Either lambda$pop$5(long)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
</summary>

```diff
+ void <init>(ServerChunkCache,Level,ServerChunkCache$1)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ EntityTickList access$100(ServerLevel)
+ Int2ObjectMap access$400(ServerLevel)
+ List access$200(ServerLevel)
+ Set access$300(ServerLevel)
+ void lambda$null$16(BlockPos)
+ void lambda$null$18(BlockPos,PoiType)
- void lambda$onBlockStateChange$16(BlockPos)
- void lambda$onBlockStateChange$18(BlockPos,PoiType)
```

</details>
<details>
<summary>
net.minecraft.server.network.TextFilterClient$RequestFailedException
</summary>

```diff
+ void <init>(String,TextFilterClient$1)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.Pack$Position
</summary>

```diff
- Pack$Position[] $values()
```

</details>
<details>
<summary>
net.minecraft.tags.StaticTagHelper$Wrapper
</summary>

```diff
+ void <init>(ResourceLocation,StaticTagHelper$1)
```

</details>
<details>
<summary>
net.minecraft.tags.Tag
</summary>

```diff
- DataResult lambda$codec$0(ResourceLocation)
- DataResult lambda$codec$2(Tag)
+ DataResult lambda$null$0(ResourceLocation)
+ DataResult lambda$null$2(Tag)
```

</details>
<details>
<summary>
net.minecraft.tags.TagManager$LoaderInfo
</summary>

```diff
+ CompletableFuture access$100(TagManager$LoaderInfo)
+ void <init>(StaticTagHelper,CompletableFuture,TagManager$1)
```

</details>
<details>
<summary>
net.minecraft.util.LowerCaseEnumTypeAdapterFactory
</summary>

```diff
+ String access$000(LowerCaseEnumTypeAdapterFactory,Object)
```

</details>
<details>
<summary>
net.minecraft.util.SortedArraySet
</summary>

```diff
+ int access$000(SortedArraySet)
+ Object[] access$100(SortedArraySet)
+ void access$200(SortedArraySet,int)
```

</details>
<details>
<summary>
net.minecraft.util.profiling.ActiveProfiler$PathEntry
</summary>

```diff
+ long access$000(ActiveProfiler$PathEntry)
+ long access$002(ActiveProfiler$PathEntry,long)
+ long access$100(ActiveProfiler$PathEntry)
+ long access$102(ActiveProfiler$PathEntry,long)
+ Object2LongOpenHashMap access$200(ActiveProfiler$PathEntry)
```

</details>
<details>
<summary>
net.minecraft.util.profiling.registry.MeasurementCategory
</summary>

```diff
- MeasurementCategory[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
</summary>

```diff
- GateBehavior$RunningPolicy[] $values()
+ void <init>(String,int,GateBehavior$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
</summary>

```diff
+ boolean lambda$null$0(GlobalPos,PoiType,Villager)
- boolean lambda$start$0(GlobalPos,PoiType,Villager)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
</summary>

```diff
+ boolean lambda$null$0(PathfinderMob,LivingEntity)
- boolean lambda$start$0(PathfinderMob,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.ShufflingList
</summary>

```diff
+ double lambda$shuffle$2(Object)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
</summary>

```diff
- boolean lambda$getNearestEntity$0(LivingEntity,LivingEntity)
+ boolean lambda$null$0(LivingEntity,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.targeting.TargetingConditions
</summary>

```diff
+ TargetingConditions allowInvulnerable()
+ TargetingConditions allowNonAttackable()
+ TargetingConditions allowSameTeam()
+ TargetingConditions allowUnseeable()
- TargetingConditions forCombat()
- TargetingConditions forNonCombat()
- TargetingConditions ignoreLineOfSight()
+ void <init>()
- void <init>(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.util.HoverRandomPos
</summary>

```diff
- boolean lambda$getPos$0(PathfinderMob,BlockPos)
+ boolean lambda$null$0(PathfinderMob,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiRecord
</summary>

```diff
- BlockPos lambda$codec$0(PoiRecord)
+ BlockPos lambda$null$0(PoiRecord)
- Integer lambda$codec$2(PoiRecord)
+ Integer lambda$null$2(PoiRecord)
- PoiType lambda$codec$1(PoiRecord)
+ PoiType lambda$null$1(PoiRecord)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
+ Bee$BeeGoToHiveGoal access$4800(Bee)
+ Bee$BeePollinateGoal access$700(Bee)
+ BlockPos access$1500(Bee)
+ BlockPos access$1502(Bee,BlockPos)
+ BlockPos access$3200(Bee)
+ BlockPos access$3202(Bee,BlockPos)
+ boolean access$1400(Bee)
+ boolean access$1600(Bee,BlockPos,int)
+ boolean access$1800(Bee)
+ boolean access$2400(Bee,BlockPos)
+ boolean access$3300(Bee,BlockPos)
+ boolean access$5100(Bee,BlockPos)
+ int access$3000(Bee)
+ int access$3002(Bee,int)
+ int access$3700(Bee)
+ int access$3800(Bee)
+ int access$3802(Bee,int)
+ int access$5200(Bee)
- PathNavigation access$000(Bee)
- PathNavigation access$1000(Bee)
- PathNavigation access$1400(Bee)
- PathNavigation access$1500(Bee)
- PathNavigation access$1600(Bee)
- PathNavigation access$1700(Bee)
- PathNavigation access$1800(Bee)
+ PathNavigation access$1900(Bee)
- PathNavigation access$200(Bee)
+ PathNavigation access$2000(Bee)
+ PathNavigation access$2200(Bee)
+ PathNavigation access$2600(Bee)
+ PathNavigation access$2700(Bee)
+ PathNavigation access$2800(Bee)
+ PathNavigation access$2900(Bee)
- PathNavigation access$300(Bee)
+ PathNavigation access$3100(Bee)
+ PathNavigation access$3400(Bee)
+ PathNavigation access$3500(Bee)
+ PathNavigation access$3600(Bee)
+ PathNavigation access$3900(Bee)
- PathNavigation access$400(Bee)
+ PathNavigation access$4300(Bee)
+ PathNavigation access$4500(Bee)
- PathNavigation access$500(Bee)
- PathNavigation access$600(Bee)
- PathNavigation access$700(Bee)
- PathNavigation access$800(Bee)
- Random access$100(Bee)
+ Random access$1000(Bee)
- Random access$1900(Bee)
- Random access$2000(Bee)
- Random access$2200(Bee)
- Random access$2400(Bee)
- Random access$2500(Bee)
- Random access$2600(Bee)
- Random access$2700(Bee)
- Random access$2800(Bee)
+ Random access$4000(Bee)
+ Random access$4100(Bee)
+ Random access$4400(Bee)
+ Random access$4600(Bee)
+ Random access$4700(Bee)
+ Random access$5300(Bee)
+ Random access$5400(Bee)
+ void access$2500(Bee,BlockPos)
+ void access$4200(Bee,boolean)
+ void access$5500(Bee)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BaseBeeGoal
</summary>

```diff
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
</summary>

```diff
+ boolean access$4900(Bee$BeeGoToHiveGoal,BlockPos)
+ int access$300(Bee$BeeGoToHiveGoal)
+ List access$500(Bee$BeeGoToHiveGoal)
+ void access$5000(Bee$BeeGoToHiveGoal)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
</summary>

```diff
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
</summary>

```diff
+ boolean lambda$findNearbyHivesWithSpace$1(Bee,BlockPos)
- double lambda$findNearbyHivesWithSpace$1(BlockPos,BlockPos)
+ double lambda$findNearbyHivesWithSpace$2(BlockPos,BlockPos)
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeePollinateGoal
</summary>

```diff
+ boolean access$600(Bee$BeePollinateGoal)
+ void access$800(Bee$BeePollinateGoal)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Dolphin
</summary>

```diff
- Random access$000(Dolphin)
+ Random access$300(Dolphin)
+ TargetingConditions access$400()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
+ boolean access$000(Ocelot)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Panda$Gene
</summary>

```diff
+ Panda$Gene access$000(Panda$Gene,Panda$Gene)
- Panda$Gene[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
+ Map access$000()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Pufferfish
</summary>

```diff
+ int access$002(Pufferfish,int)
+ int access$102(Pufferfish,int)
+ TargetingConditions access$200()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
+ boolean access$300(Rabbit)
+ int access$402(Rabbit,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
- boolean access$000(Squid)
+ boolean access$100(Squid)
- boolean canBeLeashed(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.TropicalFish$Pattern
</summary>

```diff
- TropicalFish$Pattern[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
+ BlockPos access$600(Turtle)
+ BlockPos access$700(Turtle)
+ boolean access$1300(Turtle)
+ boolean access$1400(Turtle)
+ int access$1000(Turtle)
+ int access$1008(Turtle)
- Random access$000(Turtle)
- Random access$100(Turtle)
+ Random access$1200(Turtle)
+ Random access$300(Turtle)
+ void access$1100(Turtle,boolean)
+ void access$400(Turtle,BlockPos)
+ void access$500(Turtle,boolean)
+ void access$800(Turtle,boolean)
+ void access$900(Turtle,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
</summary>

```diff
+ void <init>(Goat$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
</summary>

```diff
+ void <init>(Evoker,Evoker$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
</summary>

```diff
+ void <init>(Evoker,Evoker$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Guardian
</summary>

```diff
+ void access$000(Guardian,int)
+ void access$100(Guardian,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
</summary>

```diff
+ void <init>(Phantom,Phantom$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ravager
</summary>

```diff
+ boolean canSee(Entity)
- boolean hasLineOfSight(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
- boolean access$000(Slime)
+ boolean access$100(Slime)
+ float access$000(Slime)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.SpellcasterIllager
</summary>

```diff
- PathNavigation access$000(SpellcasterIllager)
+ PathNavigation access$200(SpellcasterIllager)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.ClickAction
</summary>

```diff
- ClickAction[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.GrindstoneMenu
</summary>

```diff
+ Container access$000(GrindstoneMenu)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.RecipeBookType
</summary>

```diff
- RecipeBookType[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorMaterials
</summary>

```diff
- ArmorMaterials[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.item.DiggerItem
</summary>

```diff
- boolean isCorrectToolForDrops(BlockState)
+ void <init>(float,float,Tier,Set,Item$Properties)
- void <init>(float,float,Tier,Tag,Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
+ boolean access$600(Item$Properties)
+ CreativeModeTab access$000(Item$Properties)
+ FoodProperties access$500(Item$Properties)
+ int access$300(Item$Properties)
+ int access$400(Item$Properties)
+ Item access$200(Item$Properties)
+ Rarity access$100(Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.Ingredient$ItemValue
</summary>

```diff
+ void <init>(ItemStack,Ingredient$1)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.RecipeManager
</summary>

```diff
+ Map lambda$null$10(RecipeType)
- Map lambda$replaceRecipes$10(RecipeType)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.UpgradeRecipe
</summary>

```diff
+ Ingredient access$000(UpgradeRecipe)
+ Ingredient access$100(UpgradeRecipe)
+ ItemStack access$200(UpgradeRecipe)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentCategory
</summary>

```diff
- EnchantmentCategory[] $values()
+ void <init>(String,int,EnchantmentCategory$1)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
</summary>

```diff
- ProtectionEnchantment$Type[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$Category
</summary>

```diff
- GameRules$Category[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$IntegerValue
</summary>

```diff
+ GameRules$Type access$100(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$Type
</summary>

```diff
+ BiConsumer access$300(GameRules$Type)
+ void <init>(Supplier,Function,BiConsumer,GameRules$VisitorCaller,GameRules$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.LightLayer
</summary>

```diff
- LightLayer[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner$SpawnState
</summary>

```diff
+ boolean access$300(NaturalSpawner$SpawnState,MobCategory)
+ boolean access$500(NaturalSpawner$SpawnState,EntityType,BlockPos,ChunkAccess)
+ void <init>(int,Object2IntOpenHashMap,PotentialCalculator,NaturalSpawner$1)
+ void access$400(NaturalSpawner$SpawnState,Mob,ChunkAccess)
```

</details>
<details>
<summary>
net.minecraft.world.level.StructureFeatureManager
</summary>

```diff
- boolean lambda$getStructureAt$3(BlockPos,StructurePiece)
+ boolean lambda$null$3(BlockPos,StructurePiece)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.AmbientMoodSettings
</summary>

```diff
+ Double lambda$null$3(AmbientMoodSettings)
- Double lambda$static$3(AmbientMoodSettings)
+ Integer lambda$null$1(AmbientMoodSettings)
+ Integer lambda$null$2(AmbientMoodSettings)
- Integer lambda$static$1(AmbientMoodSettings)
- Integer lambda$static$2(AmbientMoodSettings)
+ SoundEvent lambda$null$0(AmbientMoodSettings)
- SoundEvent lambda$static$0(AmbientMoodSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ Biome lambda$null$13(Biome$ClimateSettings,Biome$BiomeCategory,Float,Float,BiomeSpecialEffects)
- Biome lambda$static$13(Biome$ClimateSettings,Biome$BiomeCategory,Float,Float,BiomeSpecialEffects)
+ Biome$BiomeCategory lambda$null$1(Biome)
+ Biome$BiomeCategory lambda$null$9(Biome)
- Biome$BiomeCategory lambda$static$1(Biome)
- Biome$BiomeCategory lambda$static$9(Biome)
+ Biome$ClimateSettings lambda$null$0(Biome)
+ Biome$ClimateSettings lambda$null$8(Biome)
- Biome$ClimateSettings lambda$static$0(Biome)
- Biome$ClimateSettings lambda$static$8(Biome)
+ BiomeGenerationSettings lambda$null$5(Biome)
- BiomeGenerationSettings lambda$static$5(Biome)
+ BiomeSpecialEffects lambda$null$12(Biome)
+ BiomeSpecialEffects lambda$null$4(Biome)
- BiomeSpecialEffects lambda$static$12(Biome)
- BiomeSpecialEffects lambda$static$4(Biome)
+ Float lambda$null$10(Biome)
+ Float lambda$null$11(Biome)
+ Float lambda$null$2(Biome)
+ Float lambda$null$3(Biome)
- Float lambda$static$10(Biome)
- Float lambda$static$11(Biome)
- Float lambda$static$2(Biome)
- Float lambda$static$3(Biome)
- Long2FloatLinkedOpenHashMap lambda$new$16()
+ Long2FloatLinkedOpenHashMap lambda$null$16()
+ MobSpawnSettings lambda$null$6(Biome)
- MobSpawnSettings lambda$static$6(Biome)
+ PerlinSimplexNoise access$100()
+ void <init>(Biome$ClimateSettings,Biome$BiomeCategory,float,float,BiomeSpecialEffects,BiomeGenerationSettings,MobSpawnSettings,Biome$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome$ClimateParameters
</summary>

```diff
+ Float lambda$null$0(Biome$ClimateParameters)
+ Float lambda$null$1(Biome$ClimateParameters)
+ Float lambda$null$2(Biome$ClimateParameters)
+ Float lambda$null$3(Biome$ClimateParameters)
+ Float lambda$null$4(Biome$ClimateParameters)
- Float lambda$static$0(Biome$ClimateParameters)
- Float lambda$static$1(Biome$ClimateParameters)
- Float lambda$static$2(Biome$ClimateParameters)
- Float lambda$static$3(Biome$ClimateParameters)
- Float lambda$static$4(Biome$ClimateParameters)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome$Precipitation
</summary>

```diff
- Biome$Precipitation[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeGenerationSettings
</summary>

```diff
+ List lambda$null$3(BiomeGenerationSettings)
+ List lambda$null$4(BiomeGenerationSettings)
- List lambda$static$3(BiomeGenerationSettings)
- List lambda$static$4(BiomeGenerationSettings)
+ Map lambda$null$2(BiomeGenerationSettings)
- Map lambda$static$2(BiomeGenerationSettings)
+ Supplier lambda$null$1(BiomeGenerationSettings)
- Supplier lambda$static$1(BiomeGenerationSettings)
+ void <init>(Supplier,Map,List,List,BiomeGenerationSettings$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
</summary>

```diff
- FuzzyOffsetConstantColumnBiomeZoomer[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
</summary>

```diff
+ DataResult lambda$null$0(ResourceLocation)
+ DataResult lambda$null$1(ResourceLocation)
+ DataResult lambda$null$2(MultiNoiseBiomeSource$Preset)
- DataResult lambda$static$0(ResourceLocation)
- DataResult lambda$static$1(ResourceLocation)
- DataResult lambda$static$2(MultiNoiseBiomeSource$Preset)
+ void <init>(MultiNoiseBiomeSource$Preset,Registry,long,MultiNoiseBiomeSource$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.OverworldBiomeSource
</summary>

```diff
- Biome lambda$new$5(Registry,ResourceKey)
+ Biome lambda$null$5(Registry,ResourceKey)
+ Boolean lambda$null$1(OverworldBiomeSource)
+ Boolean lambda$null$2(OverworldBiomeSource)
- Boolean lambda$static$1(OverworldBiomeSource)
- Boolean lambda$static$2(OverworldBiomeSource)
+ Long lambda$null$0(OverworldBiomeSource)
- Long lambda$static$0(OverworldBiomeSource)
+ Registry lambda$null$3(OverworldBiomeSource)
- Registry lambda$static$3(OverworldBiomeSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ComposterBlock
</summary>

```diff
+ BlockState access$000(BlockState,LevelAccessor,BlockPos)
+ BlockState access$100(BlockState,LevelAccessor,BlockPos,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
</summary>

```diff
- DoubleBlockCombiner$BlockType[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PowderSnowBlock
</summary>

```diff
+ void spawnPowderSnowParticles(Level,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
</summary>

```diff
- PressurePlateBlock$Sensitivity[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BannerPattern
</summary>

```diff
- BannerPattern[] $values()
+ String access$000(BannerPattern)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BarrelBlockEntity
</summary>

```diff
+ void access$000(BarrelBlockEntity,BlockState,SoundEvent)
+ void access$100(BarrelBlockEntity,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.RailShape
</summary>

```diff
- RailShape[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.SculkSensorPhase
</summary>

```diff
- SculkSensorPhase[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.StairsShape
</summary>

```diff
- StairsShape[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.Tilt
</summary>

```diff
- Tilt[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.border.BorderStatus
</summary>

```diff
- BorderStatus[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
</summary>

```diff
+ CompletableFuture access$100(IOWorker$PendingStore)
+ CompoundTag access$000(IOWorker$PendingStore)
+ CompoundTag access$002(IOWorker$PendingStore,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.RegionFile
</summary>

```diff
+ RegionFileVersion access$000(RegionFile)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
+ void lambda$null$1(long)
- void lambda$readColumn$1(long)
```

</details>
<details>
<summary>
net.minecraft.world.level.entity.Visibility
</summary>

```diff
- Visibility[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.BlockPositionSource
</summary>

```diff
+ Optional access$000(BlockPositionSource)
+ Optional lambda$null$0(BlockPositionSource)
- Optional lambda$static$0(BlockPositionSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.EntityPositionSource
</summary>

```diff
+ int access$000(EntityPositionSource)
+ Integer lambda$null$0(EntityPositionSource)
- Integer lambda$static$0(EntityPositionSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus
</summary>

```diff
+ BlockState access$100(Aquifer$NoiseBasedAquifer$AquiferStatus)
+ int access$000(Aquifer$NoiseBasedAquifer$AquiferStatus)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Cavifier$QuantizedSpaghettiRarity
</summary>

```diff
+ double access$000(double)
+ double access$100(double)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Column$Line
</summary>

```diff
+ Column$Line access$000()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Carving
</summary>

```diff
- GenerationStep$Carving[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GeodeBlockSettings
</summary>

```diff
+ BlockStateProvider lambda$null$0(GeodeBlockSettings)
+ BlockStateProvider lambda$null$1(GeodeBlockSettings)
+ BlockStateProvider lambda$null$2(GeodeBlockSettings)
+ BlockStateProvider lambda$null$3(GeodeBlockSettings)
+ BlockStateProvider lambda$null$4(GeodeBlockSettings)
- BlockStateProvider lambda$static$0(GeodeBlockSettings)
- BlockStateProvider lambda$static$1(GeodeBlockSettings)
- BlockStateProvider lambda$static$2(GeodeBlockSettings)
- BlockStateProvider lambda$static$3(GeodeBlockSettings)
- BlockStateProvider lambda$static$4(GeodeBlockSettings)
+ List lambda$null$5(GeodeBlockSettings)
- List lambda$static$5(GeodeBlockSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GeodeLayerSettings
</summary>

```diff
+ Double lambda$null$0(GeodeLayerSettings)
+ Double lambda$null$1(GeodeLayerSettings)
+ Double lambda$null$2(GeodeLayerSettings)
+ Double lambda$null$3(GeodeLayerSettings)
- Double lambda$static$0(GeodeLayerSettings)
- Double lambda$static$1(GeodeLayerSettings)
- Double lambda$static$2(GeodeLayerSettings)
- Double lambda$static$3(GeodeLayerSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Heightmap$Types
</summary>

```diff
- Heightmap$Types[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ BiomeSource lambda$null$0(NoiseBasedChunkGenerator)
- BiomeSource lambda$static$0(NoiseBasedChunkGenerator)
+ int access$000(NoiseBasedChunkGenerator)
+ int access$100(NoiseBasedChunkGenerator)
+ int access$200(NoiseBasedChunkGenerator)
+ Long lambda$null$1(NoiseBasedChunkGenerator)
- Long lambda$static$1(NoiseBasedChunkGenerator)
+ NoodleCavifier access$400(NoiseBasedChunkGenerator)
+ OreVeinifier access$300(NoiseBasedChunkGenerator)
+ Supplier lambda$null$2(NoiseBasedChunkGenerator)
- Supplier lambda$static$2(NoiseBasedChunkGenerator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.WorldGenSettings
</summary>

```diff
+ Optional lambda$null$0(WorldGenSettings)
- Optional lambda$static$0(WorldGenSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
</summary>

```diff
+ Float lambda$null$4(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ Float lambda$null$5(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Float lambda$static$4(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Float lambda$static$5(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$0(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$1(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$3(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$0(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$1(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$3(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ Integer lambda$null$2(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Integer lambda$static$2(CanyonCarverConfiguration$CanyonShapeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarverConfiguration
</summary>

```diff
+ Boolean lambda$null$4(CarverConfiguration)
- Boolean lambda$static$4(CarverConfiguration)
+ CarverDebugSettings lambda$null$5(CarverConfiguration)
- CarverDebugSettings lambda$static$5(CarverConfiguration)
+ Float lambda$null$0(CarverConfiguration)
- Float lambda$static$0(CarverConfiguration)
+ FloatProvider lambda$null$2(CarverConfiguration)
- FloatProvider lambda$static$2(CarverConfiguration)
+ HeightProvider lambda$null$1(CarverConfiguration)
- HeightProvider lambda$static$1(CarverConfiguration)
+ VerticalAnchor lambda$null$3(CarverConfiguration)
- VerticalAnchor lambda$static$3(CarverConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
</summary>

```diff
+ Integer lambda$null$4(FossilFeatureConfiguration)
- Integer lambda$static$4(FossilFeatureConfiguration)
+ List lambda$null$0(FossilFeatureConfiguration)
+ List lambda$null$1(FossilFeatureConfiguration)
- List lambda$static$0(FossilFeatureConfiguration)
- List lambda$static$1(FossilFeatureConfiguration)
+ Supplier lambda$null$2(FossilFeatureConfiguration)
+ Supplier lambda$null$3(FossilFeatureConfiguration)
- Supplier lambda$static$2(FossilFeatureConfiguration)
- Supplier lambda$static$3(FossilFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
</summary>

```diff
+ BlockState lambda$null$0(HugeFungusConfiguration)
+ BlockState lambda$null$1(HugeFungusConfiguration)
+ BlockState lambda$null$2(HugeFungusConfiguration)
+ BlockState lambda$null$3(HugeFungusConfiguration)
- BlockState lambda$static$0(HugeFungusConfiguration)
- BlockState lambda$static$1(HugeFungusConfiguration)
- BlockState lambda$static$2(HugeFungusConfiguration)
- BlockState lambda$static$3(HugeFungusConfiguration)
+ Boolean lambda$null$4(HugeFungusConfiguration)
- Boolean lambda$static$4(HugeFungusConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature
</summary>

```diff
+ boolean access$100(JigsawFeature)
+ boolean access$200(JigsawFeature)
+ int access$000(JigsawFeature)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
</summary>

```diff
+ void <init>(SpikeFeature$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
</summary>

```diff
+ Float lambda$null$1(WeightedConfiguredFeature)
- Float lambda$static$1(WeightedConfiguredFeature)
+ Supplier lambda$null$0(WeightedConfiguredFeature)
- Supplier lambda$static$0(WeightedConfiguredFeature)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
</summary>

```diff
+ BlockState lambda$null$0(DiskConfiguration)
- BlockState lambda$static$0(DiskConfiguration)
+ Integer lambda$null$2(DiskConfiguration)
- Integer lambda$static$2(DiskConfiguration)
+ IntProvider lambda$null$1(DiskConfiguration)
- IntProvider lambda$static$1(DiskConfiguration)
+ List lambda$null$3(DiskConfiguration)
- List lambda$static$3(DiskConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
</summary>

```diff
+ Boolean lambda$null$1(EndGatewayConfiguration)
- Boolean lambda$static$1(EndGatewayConfiguration)
+ Optional lambda$null$0(EndGatewayConfiguration)
- Optional lambda$static$0(EndGatewayConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
</summary>

```diff
+ Boolean lambda$null$5(GeodeConfiguration)
- Boolean lambda$static$5(GeodeConfiguration)
+ Double lambda$null$11(GeodeConfiguration)
+ Double lambda$null$3(GeodeConfiguration)
+ Double lambda$null$4(GeodeConfiguration)
- Double lambda$static$11(GeodeConfiguration)
- Double lambda$static$3(GeodeConfiguration)
- Double lambda$static$4(GeodeConfiguration)
+ GeodeBlockSettings lambda$null$0(GeodeConfiguration)
- GeodeBlockSettings lambda$static$0(GeodeConfiguration)
+ GeodeCrackSettings lambda$null$2(GeodeConfiguration)
- GeodeCrackSettings lambda$static$2(GeodeConfiguration)
+ GeodeLayerSettings lambda$null$1(GeodeConfiguration)
- GeodeLayerSettings lambda$static$1(GeodeConfiguration)
+ Integer lambda$null$10(GeodeConfiguration)
+ Integer lambda$null$12(GeodeConfiguration)
+ Integer lambda$null$9(GeodeConfiguration)
- Integer lambda$static$10(GeodeConfiguration)
- Integer lambda$static$12(GeodeConfiguration)
- Integer lambda$static$9(GeodeConfiguration)
+ IntProvider lambda$null$6(GeodeConfiguration)
+ IntProvider lambda$null$7(GeodeConfiguration)
+ IntProvider lambda$null$8(GeodeConfiguration)
- IntProvider lambda$static$6(GeodeConfiguration)
- IntProvider lambda$static$7(GeodeConfiguration)
- IntProvider lambda$static$8(GeodeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GrowingPlantConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$2(GrowingPlantConfiguration)
+ BlockStateProvider lambda$null$3(GrowingPlantConfiguration)
- BlockStateProvider lambda$static$2(GrowingPlantConfiguration)
- BlockStateProvider lambda$static$3(GrowingPlantConfiguration)
+ Boolean lambda$null$4(GrowingPlantConfiguration)
- Boolean lambda$static$4(GrowingPlantConfiguration)
+ Direction lambda$null$1(GrowingPlantConfiguration)
- Direction lambda$static$1(GrowingPlantConfiguration)
+ SimpleWeightedRandomList lambda$null$0(GrowingPlantConfiguration)
- SimpleWeightedRandomList lambda$static$0(GrowingPlantConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$0(HugeMushroomFeatureConfiguration)
+ BlockStateProvider lambda$null$1(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$static$0(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$static$1(HugeMushroomFeatureConfiguration)
+ Integer lambda$null$2(HugeMushroomFeatureConfiguration)
- Integer lambda$static$2(HugeMushroomFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
</summary>

```diff
+ Float lambda$null$3(LargeDripstoneConfiguration)
+ Float lambda$null$8(LargeDripstoneConfiguration)
- Float lambda$static$3(LargeDripstoneConfiguration)
- Float lambda$static$8(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$2(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$4(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$5(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- FloatProvider lambda$static$2(LargeDripstoneConfiguration)
- FloatProvider lambda$static$4(LargeDripstoneConfiguration)
- FloatProvider lambda$static$5(LargeDripstoneConfiguration)
- FloatProvider lambda$static$6(LargeDripstoneConfiguration)
+ Integer lambda$null$0(LargeDripstoneConfiguration)
+ Integer lambda$null$7(LargeDripstoneConfiguration)
- Integer lambda$static$0(LargeDripstoneConfiguration)
- Integer lambda$static$7(LargeDripstoneConfiguration)
+ IntProvider lambda$null$1(LargeDripstoneConfiguration)
- IntProvider lambda$static$1(LargeDripstoneConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
</summary>

```diff
+ Float lambda$null$0(MineshaftConfiguration)
- Float lambda$static$0(MineshaftConfiguration)
+ MineshaftFeature$Type lambda$null$1(MineshaftConfiguration)
- MineshaftFeature$Type lambda$static$1(MineshaftConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
</summary>

```diff
+ Float lambda$null$1(OceanRuinConfiguration)
+ Float lambda$null$2(OceanRuinConfiguration)
- Float lambda$static$1(OceanRuinConfiguration)
- Float lambda$static$2(OceanRuinConfiguration)
+ OceanRuinFeature$Type lambda$null$0(OceanRuinConfiguration)
- OceanRuinFeature$Type lambda$static$0(OceanRuinConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
</summary>

```diff
+ List lambda$null$0(ReplaceBlockConfiguration)
- List lambda$static$0(ReplaceBlockConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$4(RootSystemConfiguration)
+ BlockStateProvider lambda$null$9(RootSystemConfiguration)
- BlockStateProvider lambda$static$4(RootSystemConfiguration)
- BlockStateProvider lambda$static$9(RootSystemConfiguration)
+ Integer lambda$null$1(RootSystemConfiguration)
+ Integer lambda$null$10(RootSystemConfiguration)
+ Integer lambda$null$11(RootSystemConfiguration)
+ Integer lambda$null$2(RootSystemConfiguration)
+ Integer lambda$null$5(RootSystemConfiguration)
+ Integer lambda$null$6(RootSystemConfiguration)
+ Integer lambda$null$7(RootSystemConfiguration)
+ Integer lambda$null$8(RootSystemConfiguration)
- Integer lambda$static$1(RootSystemConfiguration)
- Integer lambda$static$10(RootSystemConfiguration)
- Integer lambda$static$11(RootSystemConfiguration)
- Integer lambda$static$2(RootSystemConfiguration)
- Integer lambda$static$5(RootSystemConfiguration)
- Integer lambda$static$6(RootSystemConfiguration)
- Integer lambda$static$7(RootSystemConfiguration)
- Integer lambda$static$8(RootSystemConfiguration)
+ ResourceLocation lambda$null$3(RootSystemConfiguration)
- ResourceLocation lambda$static$3(RootSystemConfiguration)
+ Supplier lambda$null$0(RootSystemConfiguration)
- Supplier lambda$static$0(RootSystemConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
</summary>

```diff
+ Boolean lambda$null$0(SpikeConfiguration)
- Boolean lambda$static$0(SpikeConfiguration)
+ List lambda$null$1(SpikeConfiguration)
- List lambda$static$1(SpikeConfiguration)
+ Optional lambda$null$2(SpikeConfiguration)
- Optional lambda$static$2(SpikeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$0(TreeConfiguration)
+ BlockStateProvider lambda$null$2(TreeConfiguration)
+ BlockStateProvider lambda$null$4(TreeConfiguration)
- BlockStateProvider lambda$static$0(TreeConfiguration)
- BlockStateProvider lambda$static$2(TreeConfiguration)
- BlockStateProvider lambda$static$4(TreeConfiguration)
+ Boolean lambda$null$7(TreeConfiguration)
+ Boolean lambda$null$8(TreeConfiguration)
- Boolean lambda$static$7(TreeConfiguration)
- Boolean lambda$static$8(TreeConfiguration)
+ FeatureSize lambda$null$5(TreeConfiguration)
- FeatureSize lambda$static$5(TreeConfiguration)
+ FoliagePlacer lambda$null$3(TreeConfiguration)
- FoliagePlacer lambda$static$3(TreeConfiguration)
+ List lambda$null$6(TreeConfiguration)
- List lambda$static$6(TreeConfiguration)
+ TrunkPlacer lambda$null$1(TreeConfiguration)
- TrunkPlacer lambda$static$1(TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
</summary>

```diff
+ Float lambda$null$2(UnderwaterMagmaConfiguration)
- Float lambda$static$2(UnderwaterMagmaConfiguration)
+ Integer lambda$null$0(UnderwaterMagmaConfiguration)
+ Integer lambda$null$1(UnderwaterMagmaConfiguration)
- Integer lambda$static$0(UnderwaterMagmaConfiguration)
- Integer lambda$static$1(UnderwaterMagmaConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
</summary>

```diff
+ Integer lambda$null$0(TwoLayersFeatureSize)
+ Integer lambda$null$1(TwoLayersFeatureSize)
+ Integer lambda$null$2(TwoLayersFeatureSize)
- Integer lambda$static$0(TwoLayersFeatureSize)
- Integer lambda$static$1(TwoLayersFeatureSize)
- Integer lambda$static$2(TwoLayersFeatureSize)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
</summary>

```diff
+ Integer lambda$null$0(MegaJungleFoliagePlacer)
- Integer lambda$static$0(MegaJungleFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
</summary>

```diff
+ IntProvider lambda$null$0(PineFoliagePlacer)
- IntProvider lambda$static$0(PineFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
</summary>

```diff
+ IntProvider lambda$null$0(SpruceFoliagePlacer)
- IntProvider lambda$static$0(SpruceFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
</summary>

```diff
+ void <init>(JunglePyramidPiece$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces
</summary>

```diff
+ Logger access$000()
+ MineShaftPieces$MineShaftPiece access$100(StructurePiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
</summary>

```diff
+ boolean access$100(OceanMonumentPieces$RoomDefinition)
+ boolean access$102(OceanMonumentPieces$RoomDefinition,boolean)
+ boolean access$902(OceanMonumentPieces$RoomDefinition,boolean)
+ boolean[] access$1100(OceanMonumentPieces$RoomDefinition)
+ int access$000(OceanMonumentPieces$RoomDefinition)
+ OceanMonumentPieces$RoomDefinition[] access$1000(OceanMonumentPieces$RoomDefinition)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
</summary>

```diff
- RuinedPortalPiece$VerticalPlacement[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.ShipwreckPieces
</summary>

```diff
+ BlockPos access$000()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces
</summary>

```diff
+ Class access$102(Class)
+ StrongholdPieces$SmoothStoneSelector access$200()
+ StructurePiece access$000(StrongholdPieces$StartPiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
</summary>

```diff
+ void <init>(StrongholdPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
</summary>

```diff
- StrongholdPieces$StrongholdPiece$SmallDoorType[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
</summary>

```diff
+ Packet access$200(MapItemSavedData$HoldingPlayer,int)
+ void <init>(MapItemSavedData,Player,MapItemSavedData$1)
+ void access$300(MapItemSavedData$HoldingPlayer,int,int)
+ void access$400(MapItemSavedData$HoldingPlayer)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.IntRange
</summary>

```diff
+ NumberProvider access$100(IntRange)
+ NumberProvider access$200(IntRange)
+ void <init>(NumberProvider,NumberProvider,IntRange$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootPool
</summary>

```diff
+ LootItemCondition[] access$400(LootPool)
+ LootItemFunction[] access$500(LootPool)
+ LootPoolEntryContainer[] access$300(LootPool)
+ NumberProvider access$100(LootPool)
+ NumberProvider access$200(LootPool)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],NumberProvider,NumberProvider,LootPool$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.EmptyLootItem
</summary>

```diff
+ void <init>(int,int,LootItemCondition[],LootItemFunction[],EmptyLootItem$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
</summary>

```diff
+ BiFunction access$000(LootPoolSingletonContainer)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
</summary>

```diff
+ void <init>(LootItemCondition[],ApplyExplosionDecay$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
</summary>

```diff
+ void <init>(String,String,CopyNbtFunction$MergeStrategy,CopyNbtFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
</summary>

```diff
- void lambda$merge$0(Tag,Tag)
+ void lambda$null$0(Tag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
</summary>

```diff
+ List access$100(EnchantRandomlyFunction)
+ void <init>(LootItemCondition[],Collection,EnchantRandomlyFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
</summary>

```diff
+ boolean access$500(ExplorationMapFunction)
+ byte access$300(ExplorationMapFunction)
+ int access$400(ExplorationMapFunction)
+ Logger access$600()
+ MapDecoration$Type access$200(ExplorationMapFunction)
+ StructureFeature access$100(ExplorationMapFunction)
+ void <init>(LootItemCondition[],StructureFeature,MapDecoration$Type,byte,int,boolean,ExplorationMapFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
</summary>

```diff
+ boolean access$200(LootingEnchantFunction)
+ int access$300(LootingEnchantFunction)
+ NumberProvider access$100(LootingEnchantFunction)
+ void <init>(LootItemCondition[],NumberProvider,int,LootingEnchantFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
</summary>

```diff
+ void <init>(boolean,SetBannerPatternFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetContainerContents
</summary>

```diff
+ List access$100(SetContainerContents)
+ void <init>(LootItemCondition[],List,SetContainerContents$1)
+ void lambda$null$0(NonNullList,LootContext,LootPoolEntry)
- void lambda$run$0(NonNullList,LootContext,LootPoolEntry)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
</summary>

```diff
+ boolean access$100(SetItemDamageFunction)
+ NumberProvider access$000(SetItemDamageFunction)
+ void <init>(LootItemCondition[],NumberProvider,boolean,SetItemDamageFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
</summary>

```diff
+ void <init>(LootItemCondition[],SmeltItemFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
</summary>

```diff
+ LootItemCondition[] access$100(AlternativeLootItemCondition)
+ void <init>(LootItemCondition[],AlternativeLootItemCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
</summary>

```diff
+ LootContext$EntityTarget access$200(EntityHasScoreCondition)
+ Map access$100(EntityHasScoreCondition)
+ void <init>(Map,LootContext$EntityTarget,EntityHasScoreCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
</summary>

```diff
+ EntityPredicate access$000(LootItemEntityPropertyCondition)
+ LootContext$EntityTarget access$100(LootItemEntityPropertyCondition)
+ void <init>(EntityPredicate,LootContext$EntityTarget,LootItemEntityPropertyCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
</summary>

```diff
+ float access$000(LootItemRandomChanceWithLootingCondition)
+ float access$100(LootItemRandomChanceWithLootingCondition)
+ void <init>(float,float,LootItemRandomChanceWithLootingCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
</summary>

```diff
+ ResourceLocation access$000(StorageNbtProvider)
+ void <init>(ResourceLocation,StorageNbtProvider$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.timers.TimerQueue$Event
</summary>

```diff
+ void <init>(long,UnsignedLong,String,TimerCallback,TimerQueue$1)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
- boolean lambda$joinIsNotEmpty$1(BooleanOp,DiscreteVoxelShape,int,int,DiscreteVoxelShape,int,int,int,int,int)
- boolean lambda$joinIsNotEmpty$2(IndexMerger,BooleanOp,DiscreteVoxelShape,int,DiscreteVoxelShape,int,int,int,int)
+ boolean lambda$null$1(BooleanOp,DiscreteVoxelShape,int,int,DiscreteVoxelShape,int,int,int,int,int)
+ boolean lambda$null$2(IndexMerger,BooleanOp,DiscreteVoxelShape,int,DiscreteVoxelShape,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.scores.Team$CollisionRule
</summary>

```diff
- Team$CollisionRule[] $values()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.BlockUtil
+ net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.CharPredicate
- net.minecraft.ChatFormatting
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.FieldsAreNonnullByDefault
+ net.minecraft.FileUtil
- net.minecraft.MethodsReturnNonnullByDefault
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
+ net.minecraft.SharedConstants
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$3
+ net.minecraft.Util$4
- net.minecraft.Util$5
+ net.minecraft.Util$6
- net.minecraft.Util$7
+ net.minecraft.Util$8
- net.minecraft.Util$9
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
+ XXX.advancements.critereon.EntityPredicate$1
- XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.EntityPredicate$Composite
- XXX.advancements.critereon.EntityTypePredicate
+ XXX.advancements.critereon.EntityTypePredicate$1
- XXX.advancements.critereon.EntityTypePredicate$TagPredicate
+ XXX.advancements.critereon.EntityTypePredicate$TypePredicate
- XXX.advancements.critereon.FilledBucketTrigger
+ XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
- XXX.advancements.critereon.FishingHookPredicate
+ XXX.advancements.critereon.FishingRodHookedTrigger
- XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ XXX.advancements.critereon.FluidPredicate
- XXX.advancements.critereon.FluidPredicate$Builder
+ XXX.advancements.critereon.ImpossibleTrigger
- XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemDurabilityTrigger
- XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPickedUpByEntityTrigger
- XXX.advancements.critereon.ItemPickedUpByEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.ItemUsedOnBlockTrigger
- XXX.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledByCrossbowTrigger
- XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledTrigger
- XXX.advancements.critereon.KilledTrigger$TriggerInstance
+ XXX.advancements.critereon.LevitationTrigger
- XXX.advancements.critereon.LevitationTrigger$TriggerInstance
+ XXX.advancements.critereon.LightPredicate
+ XXX.advancements.critereon.PlayerPredicate$1
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- XXX.advancements.critereon.SerializationContext
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- XXX.advancements.critereon.StatePropertiesPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$1
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.AttributeSupplier$Builder
+ XXX.ai.attributes.DefaultAttributes
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
- XXX.ai.behavior.AnimalMakeLove
+ XXX.ai.behavior.AnimalPanic
- XXX.ai.behavior.AssignProfessionFromJobSite
+ XXX.ai.behavior.BabyFollowAdult
- XXX.ai.behavior.BackUpIfTooClose
+ XXX.ai.behavior.BecomePassiveIfMemoryPresent
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosTracker
- XXX.ai.behavior.CelebrateVillagersSurvivedRaid
+ XXX.ai.behavior.CopyMemoryWithExpiry
- XXX.ai.behavior.CountDownCooldownTicks
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.FollowTemptation
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$1
- XXX.ai.behavior.package-info
+ XXX.ai.behavior.ShufflingList$WeightedEntry
- XXX.ai.behavior.ShufflingList$WeightedEntry$1
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TryFindWater
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerMakeLove
+ XXX.ai.behavior.VillagerPanicTrigger
- XXX.ai.behavior.WakeUp
+ XXX.ai.behavior.WorkAtComposter
- XXX.ai.behavior.WorkAtPoi
+ XXX.ai.behavior.YieldJobSite
+ XXX.ai.control.BodyRotationControl
- XXX.ai.control.Control
+ XXX.ai.control.FlyingMoveControl
- XXX.ai.control.JumpControl
+ XXX.ai.control.LookControl
- XXX.ai.control.MoveControl
+ XXX.ai.control.MoveControl$Operation
- XXX.ai.control.package-info
- XXX.ai.control.SmoothSwimmingLookControl
+ XXX.ai.control.SmoothSwimmingMoveControl
+ XXX.ai.goal.AvoidEntityGoal
- XXX.ai.goal.BegGoal
+ XXX.ai.goal.BoatGoals
- XXX.ai.goal.BreakDoorGoal
+ XXX.ai.goal.BreathAirGoal
- XXX.ai.goal.BreedGoal
+ XXX.ai.goal.CatLieOnBedGoal
- XXX.ai.goal.CatSitOnBlockGoal
+ XXX.ai.goal.DolphinJumpGoal
- XXX.ai.goal.DoorInteractGoal
+ XXX.ai.goal.EatBlockGoal
- XXX.ai.goal.FleeSunGoal
+ XXX.ai.goal.FloatGoal
- XXX.ai.goal.FollowBoatGoal
+ XXX.ai.goal.FollowFlockLeaderGoal
- XXX.ai.goal.FollowMobGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.GolemRandomStrollInVillageGoal
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillageGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.package-info
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
+ XXX.ai.goal.RandomLookAroundGoal
- XXX.ai.goal.RandomStrollGoal
+ XXX.ai.goal.RandomSwimmingGoal
- XXX.ai.goal.RangedAttackGoal
+ XXX.ai.goal.RangedBowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- XXX.ai.goal.RemoveBlockGoal
+ XXX.ai.goal.RestrictSunGoal
- XXX.ai.goal.RunAroundLikeCrazyGoal
+ XXX.ai.goal.SitWhenOrderedToGoal
- XXX.ai.goal.StrollThroughVillageGoal
+ XXX.ai.goal.SwellGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$1
+ XXX.animal.axolotl.Axolotl
- XXX.animal.axolotl.Axolotl$AxolotlGroupData
+ XXX.animal.axolotl.Axolotl$AxolotlLookControl
- XXX.animal.axolotl.Axolotl$AxolotlMoveControl
+ XXX.animal.axolotl.Axolotl$AxolotlPathNavigation
- XXX.animal.axolotl.Axolotl$Variant
+ XXX.animal.axolotl.AxolotlAi
- XXX.animal.axolotl.package-info
- XXX.animal.axolotl.PlayDead
+ XXX.animal.axolotl.ValidatePlayDead
+ XXX.animal.goat.Goat
+ XXX.animal.horse.Llama$1
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Markings
- XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.Variant
- XXX.animal.horse.ZombieHorse
- XXX.arguments.blocks.BlockInput
+ XXX.arguments.blocks.BlockPredicateArgument
+ XXX.arguments.selector.package-info
+ XXX.blaze3d.font.package-info
+ XXX.blaze3d.font.TrueTypeGlyphProvider$1
- XXX.blaze3d.font.TrueTypeGlyphProvider$Glyph
- XXX.blaze3d.pipeline.MainTarget$AttachmentState
- XXX.blaze3d.pipeline.package-info
+ XXX.blaze3d.platform.ClipboardManager
- XXX.blaze3d.platform.DebugMemoryUntracker
+ XXX.blaze3d.platform.DisplayData
+ XXX.blaze3d.platform.GlConst
- XXX.blaze3d.platform.GlDebug
+ XXX.blaze3d.platform.GlDebug$1
+ XXX.blaze3d.platform.GlStateManager$BlendState
- XXX.blaze3d.platform.GlStateManager$BooleanState
+ XXX.blaze3d.platform.GlStateManager$ColorLogicState
- XXX.blaze3d.platform.GlStateManager$ColorMask
+ XXX.blaze3d.platform.GlStateManager$CullState
- XXX.blaze3d.platform.GlStateManager$DepthState
+ XXX.blaze3d.platform.GlStateManager$DestFactor
- XXX.blaze3d.platform.GlStateManager$LogicOp
+ XXX.blaze3d.platform.GlStateManager$PolygonOffsetState
- XXX.blaze3d.platform.GlStateManager$ScissorState
+ XXX.blaze3d.platform.GlStateManager$SourceFactor
- XXX.blaze3d.platform.GlStateManager$StencilFunc
+ XXX.blaze3d.platform.GlStateManager$StencilState
- XXX.blaze3d.platform.GlStateManager$TextureState
+ XXX.blaze3d.platform.GlStateManager$Viewport
- XXX.blaze3d.platform.GlUtil
- XXX.blaze3d.platform.GLX
+ XXX.blaze3d.platform.InputConstants
+ XXX.blaze3d.platform.NativeImage$Format
- XXX.blaze3d.platform.NativeImage$InternalGlFormat
+ XXX.blaze3d.platform.NativeImage$WriteCallback
+ XXX.blaze3d.platform.package-info
- XXX.blaze3d.platform.PngInfo
+ XXX.blaze3d.platform.PngInfo$1
+ XXX.blaze3d.platform.Window$WindowInitFailed
- XXX.blaze3d.platform.WindowEventHandler
- XXX.blaze3d.preprocessor.GlslPreprocessor
+ XXX.blaze3d.preprocessor.GlslPreprocessor$1
+ XXX.blaze3d.vertex.package-info
+ XXX.blaze3d.vertex.PoseStack$1
- XXX.blaze3d.vertex.PoseStack$Pose
+ XXX.blaze3d.vertex.SheetedDecalTextureGenerator
- XXX.blaze3d.vertex.Tesselator
+ XXX.blaze3d.vertex.VertexBuffer
- XXX.blaze3d.vertex.VertexConsumer
+ XXX.blaze3d.vertex.VertexFormat
- XXX.blaze3d.vertex.VertexFormat$1
+ XXX.blaze3d.vertex.VertexFormat$IndexType
- XXX.blaze3d.vertex.VertexFormat$Mode
+ XXX.blaze3d.vertex.VertexFormatElement
- XXX.blaze3d.vertex.VertexFormatElement$Type
+ XXX.blaze3d.vertex.VertexFormatElement$Usage
- XXX.blaze3d.vertex.VertexFormatElement$Usage$ClearState
+ XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
- XXX.blaze3d.vertex.VertexMultiConsumer
+ XXX.blaze3d.vertex.VertexMultiConsumer$Double
- XXX.blaze3d.vertex.VertexMultiConsumer$Multiple
+ XXX.block.entity.BeehiveBlockEntity$1
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.AzaleaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
- XXX.block.model.BakedQuad
+ XXX.block.model.BlockElement
- XXX.block.model.BlockElement$1
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementRotation
+ XXX.block.model.BlockFaceUV
- XXX.block.model.BlockFaceUV$Deserializer
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModel$GuiLight
- XXX.block.model.BlockModel$LoopException
+ XXX.block.model.BlockModelDefinition
- XXX.block.model.BlockModelDefinition$Context
+ XXX.block.model.BlockModelDefinition$Deserializer
- XXX.block.model.BlockModelDefinition$MissingVariantException
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$1
+ XXX.block.model.ItemModelGenerator$Span
- XXX.block.model.ItemModelGenerator$SpanFacing
+ XXX.block.model.ItemOverride
- XXX.block.model.ItemOverride$Deserializer
+ XXX.block.model.ItemOverride$Predicate
- XXX.block.model.ItemOverrides
+ XXX.block.model.ItemOverrides$1
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
+ XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.block.state.StateHolder$1
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
- XXX.client.gui.Font
+ XXX.client.gui.Font$StringRenderOutput
- XXX.client.gui.Gui
+ XXX.client.gui.GuiComponent
- XXX.client.gui.MapRenderer
+ XXX.client.gui.MapRenderer$1
+ XXX.client.multiplayer.ClientChunkCache$Storage
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientLevel
- XXX.client.multiplayer.ClientLevel$1
+ XXX.client.multiplayer.ClientLevel$ClientLevelData
- XXX.client.multiplayer.ClientLevel$EntityCallbacks
+ XXX.client.multiplayer.ClientLevel$MarkerParticleStatus
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.MultiPlayerGameMode
- XXX.client.multiplayer.PlayerInfo
+ XXX.client.multiplayer.ServerAddress
+ XXX.client.particle.AshParticle
- XXX.client.particle.AshParticle$Provider
+ XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.BreakingItemParticle$Provider
- XXX.client.particle.BreakingItemParticle$SlimeProvider
+ XXX.client.particle.BreakingItemParticle$SnowballProvider
- XXX.client.particle.BubbleColumnUpParticle
+ XXX.client.particle.BubbleColumnUpParticle$1
+ XXX.client.particle.BubbleParticle$Provider
- XXX.client.particle.BubblePopParticle
+ XXX.client.particle.BubblePopParticle$1
+ XXX.client.particle.CampfireSmokeParticle$CosyProvider
- XXX.client.particle.CampfireSmokeParticle$SignalProvider
+ XXX.client.particle.CritParticle
+ XXX.client.particle.DragonBreathParticle$1
- XXX.client.particle.DragonBreathParticle$Provider
+ XXX.client.particle.DripParticle
+ XXX.client.particle.EnchantmentTableParticle$1
- XXX.client.particle.EnchantmentTableParticle$NautilusProvider
+ XXX.client.particle.EnchantmentTableParticle$Provider
- XXX.client.particle.EndRodParticle
+ XXX.client.particle.EndRodParticle$1
+ XXX.client.particle.FallingDustParticle$Provider
- XXX.client.particle.FireworkParticles
+ XXX.client.particle.FireworkParticles$1
- XXX.client.particle.FireworkParticles$FlashProvider
+ XXX.client.particle.FireworkParticles$OverlayParticle
- XXX.client.particle.FireworkParticles$SparkParticle
+ XXX.client.particle.FireworkParticles$SparkProvider
- XXX.client.particle.FireworkParticles$Starter
+ XXX.client.particle.FlameParticle
+ XXX.client.particle.GlowParticle$ElectricSparkProvider
- XXX.client.particle.GlowParticle$GlowSquidProvider
+ XXX.client.particle.GlowParticle$ScrapeProvider
- XXX.client.particle.GlowParticle$WaxOffProvider
+ XXX.client.particle.GlowParticle$WaxOnProvider
- XXX.client.particle.HeartParticle
+ XXX.client.particle.HeartParticle$1
+ XXX.client.particle.HugeExplosionParticle$1
- XXX.client.particle.HugeExplosionParticle$Provider
+ XXX.client.particle.HugeExplosionSeedParticle
+ XXX.client.particle.LavaParticle$Provider
- XXX.client.particle.MobAppearanceParticle
+ XXX.client.particle.MobAppearanceParticle$1
+ XXX.client.particle.NoteParticle$1
- XXX.client.particle.NoteParticle$Provider
+ XXX.client.particle.Particle
- XXX.client.particle.ParticleDescription
+ XXX.client.particle.ParticleEngine
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$Provider
+ XXX.client.particle.ReversePortalParticle
+ XXX.client.particle.SoulParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$1
+ XXX.client.particle.SpitParticle$Provider
- XXX.client.particle.SplashParticle
+ XXX.client.particle.SplashParticle$1
+ XXX.client.particle.SquidInkParticle$1
- XXX.client.particle.SquidInkParticle$GlowInkProvider
+ XXX.client.particle.SquidInkParticle$Provider
- XXX.client.particle.StationaryItemParticle
+ XXX.client.particle.StationaryItemParticle$1
+ XXX.client.particle.SuspendedParticle$1
- XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
+ XXX.client.particle.SuspendedParticle$UnderwaterProvider
- XXX.client.particle.SuspendedParticle$WarpedSporeProvider
+ XXX.client.particle.SuspendedTownParticle
+ XXX.client.particle.TotemParticle$1
- XXX.client.particle.TotemParticle$Provider
+ XXX.client.particle.TrackingEmitter
- XXX.client.particle.VibrationSignalParticle
+ XXX.client.particle.VibrationSignalParticle$1
+ XXX.client.particle.WakeParticle$Provider
- XXX.client.particle.WaterCurrentDownParticle
+ XXX.client.particle.WaterCurrentDownParticle$1
+ XXX.client.profiling.package-info
- XXX.client.renderer.BiomeColors
+ XXX.client.renderer.BlockEntityWithoutLevelRenderer
- XXX.client.renderer.ChunkBufferBuilderPack
+ XXX.client.renderer.CubeMap
- XXX.client.renderer.DimensionSpecialEffects
+ XXX.client.renderer.DimensionSpecialEffects$EndEffects
- XXX.client.renderer.DimensionSpecialEffects$NetherEffects
+ XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
- XXX.client.renderer.DimensionSpecialEffects$SkyType
+ XXX.client.renderer.EffectInstance
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$1
+ XXX.client.renderer.GpuWarnlistManager$Preparations
- XXX.client.renderer.ItemBlockRenderTypes
+ XXX.client.renderer.ItemInHandRenderer
- XXX.client.renderer.ItemInHandRenderer$1
+ XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
- XXX.client.renderer.ItemModelShaper
+ XXX.client.renderer.LevelRenderer
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.package-info
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
+ XXX.client.renderer.RenderType$1
- XXX.client.renderer.RenderType$CompositeRenderType
+ XXX.client.renderer.RenderType$CompositeState
- XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ XXX.client.renderer.RenderType$OutlineProperty
- XXX.client.renderer.RunningTrimmedMean
+ XXX.client.renderer.ScreenEffectRenderer
- XXX.client.renderer.ShaderInstance
+ XXX.client.renderer.ShaderInstance$1
- XXX.client.renderer.Sheets
+ XXX.client.renderer.Sheets$1
- XXX.client.renderer.SpriteCoordinateExpander
+ XXX.client.renderer.ViewArea
- XXX.client.renderer.VirtualScreen
+ XXX.client.sounds.LoopingAudioStream$1
- XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
+ XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
- XXX.client.sounds.MusicManager
- XXX.client.sounds.package-info
+ XXX.client.sounds.SoundBufferLibrary
- XXX.client.sounds.SoundEngine
+ XXX.client.sounds.SoundEngineExecutor
- XXX.client.sounds.SoundEventListener
+ XXX.client.sounds.SoundManager
- XXX.client.sounds.SoundManager$1
+ XXX.client.sounds.SoundManager$2
- XXX.client.sounds.SoundManager$Preparations
+ XXX.client.sounds.SoundManager$Preparations$1
- XXX.client.sounds.WeighedSoundEvents
+ XXX.client.sounds.Weighted
+ XXX.client.tutorial.BundleTutorial
- XXX.client.tutorial.CompletedTutorialStepInstance
+ XXX.client.tutorial.CraftPlanksTutorialStep
- XXX.client.tutorial.FindTreeTutorialStepInstance
+ XXX.client.tutorial.MovementTutorialStepInstance
- XXX.client.tutorial.OpenInventoryTutorialStep
+ XXX.client.tutorial.PunchTreeTutorialStepInstance
- XXX.client.tutorial.Tutorial
+ XXX.client.tutorial.Tutorial$1
+ XXX.color.block.BlockTintCache$LatestCacheInfo
- XXX.color.block.package-info
+ XXX.color.item.ItemColor
- XXX.color.item.ItemColors
+ XXX.color.item.package-info
+ XXX.commands.arguments.AngleArgument$SingleAngle
- XXX.commands.arguments.ColorArgument
+ XXX.commands.arguments.ComponentArgument
- XXX.commands.arguments.CompoundTagArgument
+ XXX.commands.arguments.DimensionArgument
- XXX.commands.arguments.EntityAnchorArgument
+ XXX.commands.arguments.EntityAnchorArgument$Anchor
- XXX.commands.arguments.EntityArgument
+ XXX.commands.arguments.EntityArgument$Serializer
- XXX.commands.arguments.EntitySummonArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.ItemEnchantmentArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.MobEffectArgument
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchElementNode
- XXX.commands.arguments.NbtPathArgument$MatchObjectNode
+ XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
- XXX.commands.arguments.NbtPathArgument$NbtPath
+ XXX.commands.arguments.NbtPathArgument$Node
- XXX.commands.arguments.NbtTagArgument
+ XXX.commands.arguments.ObjectiveArgument
- XXX.commands.arguments.ObjectiveCriteriaArgument
+ XXX.commands.arguments.OperationArgument
- XXX.commands.arguments.OperationArgument$Operation
+ XXX.commands.arguments.OperationArgument$SimpleOperation
- XXX.commands.arguments.ParticleArgument
+ XXX.commands.arguments.RangeArgument
- XXX.commands.arguments.RangeArgument$Floats
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceLocationArgument
+ XXX.commands.arguments.ScoreboardSlotArgument
+ XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Result
+ XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.ScoreHolderArgument$Serializer
- XXX.commands.arguments.SlotArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.arguments.UuidArgument
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
+ XXX.commands.synchronization.ArgumentSerializer
- XXX.commands.synchronization.ArgumentTypes
+ XXX.commands.synchronization.ArgumentTypes$1
- XXX.components.toasts.package-info
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdventureAdvancements
- XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.NetherAdvancements
- XXX.data.advancements.package-info
- XXX.data.advancements.StoryAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLoot
- XXX.data.loot.ChestLoot
+ XXX.data.loot.EntityLoot
- XXX.data.loot.FishingLoot
+ XXX.data.loot.GiftLoot
- XXX.data.loot.LootTableProvider
- XXX.data.loot.package-info
+ XXX.data.loot.PiglinBarterLoot
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ModelProvider
- XXX.data.tags.package-info
+ XXX.data.tags.TagsProvider$TagAppender
+ XXX.data.worldgen.BastionBridgePools
- XXX.data.worldgen.BastionHoglinStablePools
+ XXX.data.worldgen.BastionHousingUnitsPools
- XXX.data.worldgen.BastionPieces
+ XXX.data.worldgen.BastionSharedPools
- XXX.data.worldgen.BastionTreasureRoomPools
+ XXX.data.worldgen.BiomeDefaultFeatures
- XXX.data.worldgen.Carvers
+ XXX.data.worldgen.DesertVillagePools
- XXX.data.worldgen.Features
+ XXX.data.worldgen.Features$Configs
- XXX.data.worldgen.Features$Decorators
+ XXX.data.worldgen.Features$States
- XXX.data.worldgen.PillagerOutpostPools
+ XXX.data.worldgen.PlainVillagePools
- XXX.data.worldgen.Pools
+ XXX.data.worldgen.ProcessorLists
- XXX.data.worldgen.SavannaVillagePools
+ XXX.data.worldgen.SnowyVillagePools
- XXX.data.worldgen.StructureFeatures
+ XXX.data.worldgen.SurfaceBuilders
- XXX.data.worldgen.TaigaVillagePools
+ XXX.data.worldgen.VillagePools
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.fixes.BedBlockEntityInjecter
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehivePoiRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$1
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.package-info
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRename
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenameBiomesFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.SavedDataVillageCropFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
- XXX.datafix.schemas.NamespacedSchema$1
+ XXX.datafix.schemas.package-info
+ XXX.datafix.schemas.V100
- XXX.datafix.schemas.V102
+ XXX.datafix.schemas.V1022
- XXX.datafix.schemas.V106
+ XXX.datafix.schemas.V107
- XXX.datafix.schemas.V1125
+ XXX.datafix.schemas.V135
- XXX.datafix.schemas.V143
+ XXX.datafix.schemas.V1451
- XXX.datafix.schemas.V1451_1
+ XXX.datafix.schemas.V1451_2
- XXX.datafix.schemas.V1451_3
+ XXX.datafix.schemas.V1451_4
- XXX.datafix.schemas.V1451_5
+ XXX.datafix.schemas.V1451_6
- XXX.datafix.schemas.V1451_7
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1460$1
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
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
+ XXX.enderdragon.phases.AbstractDragonPhaseInstance
- XXX.enderdragon.phases.AbstractDragonSittingPhase
+ XXX.enderdragon.phases.DragonChargePlayerPhase
- XXX.enderdragon.phases.DragonDeathPhase
+ XXX.enderdragon.phases.DragonHoldingPatternPhase
- XXX.enderdragon.phases.DragonHoverPhase
+ XXX.enderdragon.phases.DragonLandingApproachPhase
- XXX.enderdragon.phases.DragonLandingPhase
+ XXX.enderdragon.phases.DragonPhaseInstance
- XXX.enderdragon.phases.DragonSittingAttackingPhase
+ XXX.enderdragon.phases.DragonSittingFlamingPhase
- XXX.enderdragon.phases.DragonSittingScanningPhase
+ XXX.enderdragon.phases.DragonStrafePlayerPhase
- XXX.enderdragon.phases.DragonTakeoffPhase
+ XXX.enderdragon.phases.EnderDragonPhase
- XXX.enderdragon.phases.EnderDragonPhaseManager
+ XXX.enderdragon.phases.package-info
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.package-info
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
+ XXX.entity.animal.TropicalFish
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
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$1
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.ItemFrame$1
+ XXX.entity.decoration.ItemFrame$2
- XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.Motive
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
+ XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
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
- XXX.entity.layers.package-info
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
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfCollarLayer
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
+ XXX.entity.monster.Illusioner$1
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
+ XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$1
+ XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
- XXX.entity.monster.Ravager$RavagerNavigation
+ XXX.entity.monster.Ravager$RavagerNodeEvaluator
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$1
+ XXX.entity.monster.Strider$1
- XXX.entity.monster.Strider$StriderGoToLavaGoal
+ XXX.entity.monster.Strider$StriderPathNavigation
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zoglin
- XXX.entity.monster.Zombie
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
- XXX.entity.monster.ZombifiedPiglin
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
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
- XXX.entity.player.PlayerRenderer
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$1
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.AbstractMinecartContainer$1
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.Boat$1
+ XXX.entity.vehicle.Boat$Status
- XXX.entity.vehicle.Boat$Type
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
+ XXX.feature.configurations.OreConfiguration$1
- XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.LegacySinglePoolElement
- XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.font.providers.BitmapProvider$1
- XXX.font.providers.BitmapProvider$Builder
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.GlyphProviderBuilder
+ XXX.font.providers.GlyphProviderBuilderType
- XXX.font.providers.LegacyUnicodeBitmapsProvider
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$1
- XXX.gametest.framework.AfterBatch
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.ExhaustedAttemptsException
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestHelper$1
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestSequence
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.GlobalTestReporter
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.MultipleTestTracker$1
- XXX.gametest.framework.package-info
- XXX.gametest.framework.ReportGameListener
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
+ XXX.goal.target.package-info
+ XXX.goal.target.ResetUniversalAngerTargetGoal
- XXX.goal.target.TargetGoal
+ XXX.gui.components.AbstractSelectionList$1
- XXX.gui.components.AbstractSelectionList$Entry
+ XXX.gui.components.AbstractSelectionList$SelectionDirection
- XXX.gui.components.AbstractSelectionList$TrackedList
+ XXX.gui.components.AbstractSliderButton
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.BossHealthOverlay$1
+ XXX.gui.components.Button
- XXX.gui.components.Button$OnPress
+ XXX.gui.components.Button$OnTooltip
- XXX.gui.components.ChatComponent
+ XXX.gui.components.Checkbox
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$1
+ XXX.gui.components.CycleButton$1
- XXX.gui.components.CycleButton$Builder
+ XXX.gui.components.CycleButton$OnValueChange
- XXX.gui.components.CycleButton$TooltipSupplier
+ XXX.gui.components.CycleButton$ValueListSupplier
- XXX.gui.components.CycleButton$ValueListSupplier$1
+ XXX.gui.components.CycleButton$ValueListSupplier$2
- XXX.gui.components.DebugScreenOverlay
+ XXX.gui.components.DebugScreenOverlay$1
- XXX.gui.components.EditBox
+ XXX.gui.components.ImageButton
- XXX.gui.components.LerpingBossEvent
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.MultiLineLabel
- XXX.gui.components.MultiLineLabel$1
+ XXX.gui.components.MultiLineLabel$2
- XXX.gui.components.MultiLineLabel$TextWithWidth
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
+ XXX.gui.components.PlayerTabOverlay
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$1
- XXX.gui.font.FontSet
+ XXX.gui.font.FontTexture
+ XXX.gui.screens.CreateBuffetWorldScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$1
+ XXX.gui.screens.package-info
+ XXX.gui.screens.UploadResult$1
- XXX.gui.screens.UploadResult$Builder
- XXX.gui.task.IntervalBasedStartupDelay
+ XXX.gui.task.NoStartupDelay
- XXX.gui.task.package-info
- XXX.gui.task.RepeatableTask
+ XXX.gui.task.RestartDelayCalculator
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.layer.traits.AreaTransformer0
+ XXX.layer.traits.AreaTransformer1
- XXX.layer.traits.AreaTransformer2
+ XXX.layer.traits.BishopTransformer
- XXX.layer.traits.C0Transformer
+ XXX.layer.traits.C1Transformer
- XXX.layer.traits.CastleTransformer
+ XXX.layer.traits.DimensionOffset0Transformer
- XXX.layer.traits.DimensionOffset1Transformer
+ XXX.layer.traits.DimensionTransformer
+ XXX.layer.traits.package-info
- XXX.layer.traits.PixelTransformer
+ XXX.level.biome.BiomeGenerationSettings$Builder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.MobSpawnSettings$1
- XXX.level.biome.MobSpawnSettings$Builder
+ XXX.level.biome.MobSpawnSettings$MobSpawnCost
- XXX.level.biome.MobSpawnSettings$SpawnerData
+ XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.block.package-info
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkBiomeContainer
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$1
- XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.Palette
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.ProtoTickList
+ XXX.level.chunk.UpgradeData
+ XXX.level.entity.PersistentEntitySectionManager$1
- XXX.level.entity.PersistentEntitySectionManager$Callback
+ XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- XXX.level.entity.TransientEntitySectionManager
+ XXX.level.entity.TransientEntitySectionManager$1
+ XXX.level.levelgen.package-info
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.FlatDataLayer
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
- XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelVersion
- XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.NoiseEffect
- XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.RuinedPortalFeature
+ XXX.levelgen.feature.RuinedPortalFeature$FeatureStart
- XXX.levelgen.feature.RuinedPortalFeature$Type
+ XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.ShipwreckFeature
+ XXX.levelgen.feature.ShipwreckFeature$FeatureStart
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SmallDripstoneFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
- XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.placement.CarvingMaskDecorator
+ XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
- XXX.levelgen.placement.CaveDecoratorConfiguration
+ XXX.levelgen.placement.CaveSurface
- XXX.levelgen.placement.CaveSurfaceDecorator
+ XXX.levelgen.placement.ChanceDecorator
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountDecorator
+ XXX.levelgen.placement.CountNoiseDecorator
- XXX.levelgen.placement.CountWithExtraChanceDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DecoratedDecorator
+ XXX.levelgen.placement.DecoratedDecoratorConfiguration
- XXX.levelgen.placement.DecorationContext
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- XXX.levelgen.placement.HeightmapDecorator
+ XXX.levelgen.placement.HeightmapDoubleDecorator
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.NoiseBasedDecorator
+ XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.RangeDecorator
- XXX.levelgen.placement.RepeatingDecorator
+ XXX.levelgen.placement.Spread32Decorator
- XXX.levelgen.placement.SquareDecorator
+ XXX.levelgen.placement.VerticalDecorator
- XXX.levelgen.placement.WaterDepthThresholdConfiguration
+ XXX.levelgen.placement.WaterDepthThresholdDecorator
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.WoodlandMansionPieces$1
- XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.levelgen.synth.SurfaceNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$1
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$1
+ XXX.loot.entries.LootTableReference$1
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$1
+ XXX.loot.functions.CopyNameFunction$1
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$1
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetEnchantmentsFunction$1
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$1
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNbtFunction$1
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParamSet
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.ConditionReference$1
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$1
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck$1
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$1
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$1
+ XXX.loot.predicates.ValueCheckCondition$1
- XXX.loot.predicates.ValueCheckCondition$Serializer
+ XXX.loot.predicates.WeatherCheck
+ XXX.minecraft.advancements.Advancement
+ XXX.minecraft.client.Camera$NearPlane
- XXX.minecraft.client.CameraType
+ XXX.minecraft.client.ClientBrandRetriever
- XXX.minecraft.client.ClientRecipeBook
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.ComponentCollector
+ XXX.minecraft.client.CycleOption
- XXX.minecraft.client.CycleOption$OptionSetter
+ XXX.minecraft.client.DebugQueryHandler
- XXX.minecraft.client.FullscreenResolutionProgressOption
+ XXX.minecraft.client.Game
- XXX.minecraft.client.Game$Metrics
+ XXX.minecraft.client.GraphicsStatus
- XXX.minecraft.client.GraphicsStatus$1
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.KeyboardHandler
+ XXX.minecraft.client.KeyboardHandler$1
+ XXX.minecraft.client.KeyMapping
- XXX.minecraft.client.LogaritmicProgressOption
+ XXX.minecraft.client.Minecraft
- XXX.minecraft.client.Minecraft$1
+ XXX.minecraft.client.Minecraft$ChatStatus
- XXX.minecraft.client.Minecraft$ChatStatus$1
+ XXX.minecraft.client.Minecraft$ChatStatus$2
- XXX.minecraft.client.Minecraft$ChatStatus$3
+ XXX.minecraft.client.Minecraft$ChatStatus$4
- XXX.minecraft.client.Minecraft$ExperimentalDialogType
+ XXX.minecraft.client.Minecraft$ServerStem
- XXX.minecraft.client.MouseHandler
+ XXX.minecraft.client.NarratorStatus
- XXX.minecraft.client.Option
+ XXX.minecraft.client.Option$1
- XXX.minecraft.client.Options
+ XXX.minecraft.client.Options$1
- XXX.minecraft.client.Options$2
+ XXX.minecraft.client.Options$3
- XXX.minecraft.client.Options$4
+ XXX.minecraft.client.Options$FieldAccess
- XXX.minecraft.client.package-info
- XXX.minecraft.client.ParticleStatus
+ XXX.minecraft.client.ProgressOption
- XXX.minecraft.client.RecipeBookCategories
+ XXX.minecraft.client.RecipeBookCategories$1
- XXX.minecraft.client.ResourceLoadStateTracker
+ XXX.minecraft.client.ResourceLoadStateTracker$1
- XXX.minecraft.commands.package-info
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.BuiltinRegistries
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.Language$1
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CompoundTag
+ XXX.minecraft.nbt.CompoundTag$1
- XXX.minecraft.nbt.DoubleTag
+ XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag
+ XXX.minecraft.nbt.EndTag$1
- XXX.minecraft.nbt.FloatTag
+ XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag
+ XXX.minecraft.nbt.IntArrayTag$1
- XXX.minecraft.nbt.IntTag
+ XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
+ XXX.minecraft.nbt.LongArrayTag
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
+ XXX.minecraft.nbt.LongTag$Cache
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.StringTagVisitor
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagTypes
- XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.nbt.TextComponentTagVisitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$PacketHolder
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.ConnectionProtocol$1
- XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmsServerAddress
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.RegistryDataPackCodec
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryLookupCodec
- XXX.minecraft.resources.RegistryReadOps
+ XXX.minecraft.resources.RegistryReadOps$1
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$1
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$1
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.SerializationTags
- XXX.minecraft.tags.SetTag
+ XXX.minecraft.tags.StaticTagHelper
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$BuilderEntry
+ XXX.minecraft.tags.Tag$ElementEntry
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$Named
- XXX.minecraft.tags.Tag$OptionalElementEntry
+ XXX.minecraft.tags.Tag$OptionalTagEntry
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagCollection$1
+ XXX.minecraft.tags.TagCollection$NetworkPayload
- XXX.minecraft.tags.TagContainer
+ XXX.minecraft.tags.TagContainer$1
- XXX.minecraft.tags.TagContainer$Builder
+ XXX.minecraft.tags.TagContainer$CollectionConsumer
- XXX.minecraft.tags.TagLoader
+ XXX.minecraft.tags.TagManager
+ XXX.minecraft.util.CsvOutput$1
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$XorCodec
+ XXX.minecraft.util.FastColor
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HeapDumper
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$2
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
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
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.Snooper
- XXX.minecraft.world.Snooper$1
+ XXX.minecraft.world.SnooperPopulator
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
- XXX.models.blockstates.BlockStateGenerator
+ XXX.models.blockstates.Condition
+ XXX.models.blockstates.MultiPartGenerator$1
- XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.PropertyDispatch
- XXX.mojang.blaze3d.package-info
- XXX.mojang.math.Constants
+ XXX.mojang.math.FieldsAreNonnullByDefault
- XXX.mojang.math.Matrix3f
+ XXX.mojang.math.Matrix4f
- XXX.mojang.math.MethodsReturnNonnullByDefault
+ XXX.mojang.math.OctahedralGroup
- XXX.mojang.math.OctahedralGroup$1
+ XXX.mojang.math.package-info
+ XXX.mojang.math.Quaternion
- XXX.mojang.math.SymmetricGroup3
+ XXX.mojang.math.Transformation
- XXX.mojang.math.Vector3d
+ XXX.mojang.math.Vector3f
- XXX.mojang.math.Vector4f
- XXX.mojang.realmsclient.KeyCombo
+ XXX.mojang.realmsclient.package-info
+ XXX.mojang.realmsclient.RealmsMainScreen
- XXX.mojang.realmsclient.RealmsMainScreen$1
+ XXX.mojang.realmsclient.RealmsMainScreen$2
- XXX.mojang.realmsclient.RealmsMainScreen$3
+ XXX.mojang.realmsclient.RealmsMainScreen$4
- XXX.mojang.realmsclient.RealmsMainScreen$5
+ XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
- XXX.mojang.realmsclient.RealmsMainScreen$Entry
+ XXX.mojang.realmsclient.RealmsMainScreen$HoveredElement
- XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
+ XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
- XXX.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
+ XXX.mojang.realmsclient.RealmsMainScreen$TrialEntry
- XXX.mojang.realmsclient.Unit
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$1
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
- XXX.multiplayer.resolver.ResolvedServerAddress$1
- XXX.multiplayer.resolver.ServerAddressResolver
- XXX.multiplayer.resolver.ServerRedirectHandler
+ XXX.newbiome.area.Area
- XXX.newbiome.area.AreaFactory
+ XXX.newbiome.area.LazyArea
- XXX.newbiome.area.package-info
+ XXX.newbiome.context.BigContext
- XXX.newbiome.context.Context
+ XXX.newbiome.context.LazyAreaContext
- XXX.newbiome.context.package-info
+ XXX.newbiome.layer.AddDeepOceanLayer
- XXX.newbiome.layer.AddEdgeLayer
+ XXX.newbiome.layer.AddEdgeLayer$CoolWarm
- XXX.newbiome.layer.AddEdgeLayer$HeatIce
+ XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- XXX.newbiome.layer.AddIslandLayer
+ XXX.newbiome.layer.AddMushroomIslandLayer
- XXX.newbiome.layer.AddSnowLayer
+ XXX.newbiome.layer.BiomeEdgeLayer
- XXX.newbiome.layer.BiomeInitLayer
+ XXX.newbiome.layer.IslandLayer
- XXX.newbiome.layer.Layer
+ XXX.newbiome.layer.LayerBiomes
- XXX.newbiome.layer.Layers
+ XXX.newbiome.layer.Layers$Category
- XXX.newbiome.layer.OceanLayer
+ XXX.newbiome.layer.OceanMixerLayer
+ XXX.newbiome.layer.package-info
- XXX.newbiome.layer.RareBiomeLargeLayer
+ XXX.newbiome.layer.RareBiomeSpotLayer
- XXX.newbiome.layer.RegionHillsLayer
+ XXX.newbiome.layer.RemoveTooMuchOceanLayer
- XXX.newbiome.layer.RiverInitLayer
+ XXX.newbiome.layer.RiverLayer
- XXX.newbiome.layer.RiverMixerLayer
+ XXX.newbiome.layer.ShoreLayer
- XXX.newbiome.layer.SmoothLayer
+ XXX.newbiome.layer.ZoomLayer
- XXX.newbiome.layer.ZoomLayer$1
+ XXX.packs.resources.package-info
+ XXX.packs.resources.ProfiledReloadInstance$1
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManager$Empty
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadableResourceManager
- XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.packs.resources.SimpleResource
- XXX.placement.nether.CountMultiLayerDecorator
+ XXX.placement.nether.package-info
+ XXX.profiling.metric.MetricSampler$MetricSamplerBuilder
- XXX.profiling.metric.MetricSampler$ThresholdAlerter
+ XXX.profiling.metric.MetricSampler$ValueIncreased
- XXX.profiling.metric.package-info
- XXX.profiling.metric.SamplerCategory
+ XXX.profiling.metric.TaskSamplerBuilder
- XXX.profiling.storage.MetricsPersister
+ XXX.profiling.storage.package-info
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
- XXX.protocol.game.ClientboundLevelChunkPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$1
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$1
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$2
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$3
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$4
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$5
- XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntityPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResourcePackPacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundSetActionBarTextPacket
- XXX.protocol.game.ClientboundSetBorderCenterPacket
+ XXX.protocol.game.ClientboundSetBorderLerpSizePacket
- XXX.protocol.game.ClientboundSetBorderSizePacket
+ XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
- XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetSubtitleTextPacket
- XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesAnimationPacket
+ XXX.protocol.game.ClientboundSetTitleTextPacket
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$1
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundInteractPacket$ActionType
+ XXX.protocol.game.ServerboundInteractPacket$Handler
- XXX.protocol.game.ServerboundInteractPacket$InteractionAction
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemPacket
+ XXX.protocol.game.ServerboundPlaceRecipePacket
- XXX.protocol.game.ServerboundPlayerAbilitiesPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket
- XXX.protocol.game.ServerboundPlayerActionPacket$Action
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundPongPacket
- XXX.protocol.game.ServerGamePacketListener
- XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.ConstantValue$1
- XXX.providers.number.ConstantValue$InlineSerializer
+ XXX.providers.number.ConstantValue$Serializer
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
+ XXX.providers.number.UniformGenerator$1
- XXX.providers.number.UniformGenerator$Serializer
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$1
+ XXX.providers.score.FixedScoreboardNameProvider$1
- XXX.providers.score.FixedScoreboardNameProvider$Serializer
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.realmsclient.client.FileDownload
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.LevelType
+ XXX.realmsclient.util.package-info
- XXX.realmsclient.util.RealmsPersistence
+ XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- XXX.realmsclient.util.RealmsTextureManager
+ XXX.realmsclient.util.RealmsTextureManager$1
- XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
+ XXX.realmsclient.util.RealmsUtil
- XXX.realmsclient.util.RealmsUtil$1
+ XXX.realmsclient.util.SkinProcessor
- XXX.realmsclient.util.TextRenderingUtils
+ XXX.realmsclient.util.TextRenderingUtils$Line
- XXX.realmsclient.util.TextRenderingUtils$LineSegment
+ XXX.realmsclient.util.UploadTokenCache
- XXX.realmsclient.util.WorldGenerationInfo
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer
- XXX.renderer.block.ModelBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
- XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- XXX.renderer.block.ModelBlockRenderer$Cache
+ XXX.renderer.block.ModelBlockRenderer$Cache$1
- XXX.renderer.block.ModelBlockRenderer$Cache$2
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.GameEventListenerRenderer
- XXX.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
- XXX.renderer.debug.GameTestDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer$Marker
- XXX.renderer.debug.GoalSelectorDebugRenderer
+ XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- XXX.renderer.debug.HeightMapRenderer
+ XXX.renderer.debug.HeightMapRenderer$1
- XXX.renderer.debug.LightDebugRenderer
+ XXX.renderer.debug.NeighborsUpdateRenderer
+ XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.SolidFaceRenderer
+ XXX.renderer.debug.StructureRenderer
- XXX.renderer.debug.VillageSectionsDebugRenderer
+ XXX.renderer.debug.WaterDebugRenderer
- XXX.renderer.debug.WorldGenAttemptRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.AxolotlRenderer
+ XXX.renderer.entity.BatRenderer
- XXX.renderer.entity.BeeRenderer
+ XXX.renderer.entity.BlazeRenderer
- XXX.renderer.entity.BoatRenderer
+ XXX.renderer.entity.CatRenderer
- XXX.renderer.entity.CaveSpiderRenderer
+ XXX.renderer.entity.ChestedHorseRenderer
- XXX.renderer.entity.ChickenRenderer
+ XXX.renderer.entity.CodRenderer
- XXX.renderer.entity.CowRenderer
+ XXX.renderer.entity.CreeperRenderer
- XXX.renderer.entity.DolphinRenderer
+ XXX.renderer.entity.DragonFireballRenderer
- XXX.renderer.entity.DrownedRenderer
+ XXX.renderer.entity.ElderGuardianRenderer
- XXX.renderer.entity.EndCrystalRenderer
+ XXX.renderer.entity.EnderDragonRenderer
- XXX.renderer.entity.EnderDragonRenderer$DragonModel
+ XXX.renderer.entity.EndermanRenderer
- XXX.renderer.entity.EndermiteRenderer
+ XXX.renderer.entity.EntityRenderDispatcher
- XXX.renderer.entity.EntityRenderer
+ XXX.renderer.entity.EntityRendererProvider
- XXX.renderer.entity.EntityRendererProvider$Context
+ XXX.renderer.entity.EntityRenderers
- XXX.renderer.entity.EvokerFangsRenderer
+ XXX.renderer.entity.EvokerRenderer
- XXX.renderer.entity.EvokerRenderer$1
+ XXX.renderer.entity.ExperienceOrbRenderer
- XXX.renderer.entity.FallingBlockRenderer
+ XXX.renderer.entity.FireworkEntityRenderer
- XXX.renderer.entity.FishingHookRenderer
+ XXX.renderer.entity.FoxRenderer
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
+ XXX.renderer.entity.LlamaSpitRenderer
- XXX.renderer.entity.MagmaCubeRenderer
+ XXX.renderer.entity.MinecartRenderer
- XXX.renderer.entity.MobRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
+ XXX.renderer.entity.package-info
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
+ XXX.renderer.entity.SheepRenderer
- XXX.renderer.entity.ShulkerBulletRenderer
+ XXX.renderer.entity.ShulkerRenderer
- XXX.renderer.entity.SilverfishRenderer
+ XXX.renderer.entity.SkeletonRenderer
- XXX.renderer.entity.SlimeRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.StriderRenderer
+ XXX.renderer.entity.ThrownItemRenderer
- XXX.renderer.entity.ThrownTridentRenderer
+ XXX.renderer.entity.TippableArrowRenderer
- XXX.renderer.entity.TntMinecartRenderer
+ XXX.renderer.entity.TntRenderer
- XXX.renderer.entity.TropicalFishRenderer
+ XXX.renderer.entity.TurtleRenderer
- XXX.renderer.entity.UndeadHorseRenderer
+ XXX.renderer.entity.VexRenderer
- XXX.renderer.entity.VillagerRenderer
+ XXX.renderer.entity.VindicatorRenderer
- XXX.renderer.entity.VindicatorRenderer$1
+ XXX.renderer.entity.WanderingTraderRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
- XXX.renderer.item.ItemProperties
+ XXX.renderer.item.ItemProperties$1
- XXX.renderer.item.ItemProperties$2
+ XXX.renderer.item.ItemProperties$CompassWobble
- XXX.renderer.item.ItemPropertyFunction
+ XXX.renderer.item.package-info
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.AtlasSet
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
- XXX.renderer.texture.PreloadedTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SimpleTexture$TextureImage
+ XXX.renderer.texture.Stitcher
- XXX.renderer.texture.Stitcher$Holder
+ XXX.renderer.texture.Stitcher$Region
- XXX.renderer.texture.Stitcher$SpriteLoader
+ XXX.renderer.texture.StitcherException
- XXX.renderer.texture.TextureAtlas
+ XXX.renderer.texture.TextureAtlas$Preparations
- XXX.renderer.texture.TextureAtlasSprite
+ XXX.renderer.texture.TextureAtlasSprite$1
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
+ XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlList
+ XXX.selector.options.EntitySelectorOptions$1
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DeOpCommands
+ XXX.server.commands.package-info
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
+ XXX.server.commands.TeleportCommand$LookAt
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.ServerWatchdog
- XXX.server.dedicated.ServerWatchdog$1
+ XXX.server.dedicated.Settings
+ XXX.server.level.ChunkTaskPriorityQueueSorter$1
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$3
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.WorldGenRegion
- XXX.server.level.WorldGenTickList
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerGamePacketListenerImpl$2
- XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerPlayerConnection
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.network.TextFilter
+ XXX.server.network.TextFilter$1
- XXX.server.network.TextFilter$FilteredText
+ XXX.server.network.TextFilterClient
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$1
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$1
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.IntRange$Serializer
- XXX.storage.loot.ItemModifierManager
+ XXX.storage.loot.ItemModifierManager$FunctionSequence
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$1
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager$1
- XXX.storage.loot.PredicateManager$CompositePredicate
+ XXX.storage.loot.Serializer
- XXX.storage.loot.SerializerType
+ XXX.storage.loot.ValidationContext
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.package-info
- XXX.util.datafix.PackedBitStorage
+ XXX.util.random.package-info
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedEntry$Wrapper
+ XXX.util.random.WeightedRandom
- XXX.util.random.WeightedRandomList
- XXX.util.task.CloseServerTask
+ XXX.util.task.ConnectTask
- XXX.util.task.DownloadTask
+ XXX.util.task.GetServerDetailsTask
- XXX.util.task.LongRunningTask
+ XXX.util.task.OpenServerTask
+ XXX.util.task.package-info
- XXX.util.task.ResettingGeneratedWorldTask
+ XXX.util.task.ResettingTemplateWorldTask
- XXX.util.task.ResettingWorldTask
+ XXX.util.task.RestoreTask
- XXX.util.task.SwitchMinigameTask
+ XXX.util.task.SwitchSlotTask
- XXX.util.task.WorldCreationTask
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
- XXX.util.valueproviders.ConstantFloat
+ XXX.util.valueproviders.ConstantInt
- XXX.util.valueproviders.FloatProvider
+ XXX.util.valueproviders.FloatProviderType
- XXX.util.valueproviders.IntProvider
+ XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.TrapezoidFloat
+ XXX.util.valueproviders.UniformFloat
- XXX.util.valueproviders.UniformInt
+ XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
- XXX.world.damagesource.BadRespawnPointDamage
+ XXX.world.damagesource.CombatEntry
- XXX.world.damagesource.CombatRules
+ XXX.world.damagesource.CombatTracker
- XXX.world.damagesource.DamageSource
+ XXX.world.damagesource.EntityDamageSource
- XXX.world.damagesource.IndirectEntityDamageSource
+ XXX.world.damagesource.package-info
- XXX.world.effect.AbsoptionMobEffect
+ XXX.world.effect.AttackDamageMobEffect
- XXX.world.effect.HealthBoostMobEffect
+ XXX.world.effect.InstantenousMobEffect
- XXX.world.effect.MobEffect
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveFunction
+ XXX.world.entity.Entity$MovementEmission
- XXX.world.entity.Entity$RemovalReason
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$1
+ XXX.world.entity.EntityType$Builder
- XXX.world.entity.EntityType$EntityFactory
+ XXX.world.entity.EquipmentSlot
- XXX.world.entity.EquipmentSlot$Type
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.FlyingMob
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.Marker
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.package-info
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.Pose
+ XXX.world.entity.PowerableMob
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacements$Type
- XXX.world.entity.TamableAnimal
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$1
+ XXX.world.item.ItemCooldowns$1
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$TooltipPart
+ XXX.world.item.ItemUtils
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MapItem
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignItem
+ XXX.world.item.SimpleFoiledItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.Tier
+ XXX.world.item.TieredItem
- XXX.world.item.Tiers
+ XXX.world.item.TippedArrowItem
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
- XXX.world.item.Vanishable
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.Wearable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.ChunkTickList$ScheduledTick
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.CollisionSpliterator
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EmptyTickList
+ XXX.world.level.EntityBasedExplosionDamageCalculator
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.ExplosionDamageCalculator
- XXX.world.level.FoliageColor
+ XXX.world.level.ForcedChunksSavedData
- XXX.world.level.GameRules
+ XXX.world.level.GameRules$1
- XXX.world.level.package-info
- XXX.worldgen.biome.BiomeReport
+ XXX.worldgen.biome.Biomes
+ XXX.worldgen.biome.package-info
- XXX.worldgen.biome.VanillaBiomes
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.audio.OggAudioStream$OutputConcat -1M
```
```
XXX.blaze3d.pipeline.RenderTarget +6M -5M
```
```
XXX.blaze3d.platform.InputConstants$Key -2M
```
```
XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel -1M
```
```
XXX.blaze3d.platform.Window +1M
```
```
XXX.blaze3d.systems.RenderSystem -1M
```
```
XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer -2M
```
```
XXX.blaze3d.vertex.BufferBuilder$SortState -7M
```
```
XXX.realmsclient.client.FileDownload$ResourcePackProgressListener -1M
```
```
XXX.realmsclient.client.Ping$Region +1M -2M
```
```
XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse +1M
```
```
XXX.realmsclient.dto.RealmsServer$WorldType +1M
```
```
XXX.realmsclient.dto.WorldTemplate$WorldTemplateType +1M
```
```
XXX.realmsclient.gui.RealmsDataFetcher$Task +1M
```
```
XXX.realmsclient.gui.RealmsWorldSlotButton$Action +1M
```
```
XXX.gui.screens.RealmsBackupInfoScreen -2M
```
```
XXX.gui.screens.RealmsLongConfirmationScreen$Type +1M
```
```
XXX.gui.screens.RealmsNotificationsScreen -2M
```
```
XXX.gui.screens.RealmsPlayerScreen$UserAction +1M
```
```
XXX.gui.screens.RealmsResetWorldScreen -6M
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen +8M -26M
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry -1M
```
```
XXX.gui.screens.RealmsSettingsScreen +1M -1M
```
```
XXX.gui.screens.RealmsUploadScreen +1M -1M
```
```
XXX.minecraft.advancements.Advancement$Builder -1M
```
```
XXX.minecraft.advancements.FrameType +1M
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger -1M
```
```
XXX.advancements.critereon.BredAnimalsTrigger -1M
```
```
XXX.advancements.critereon.BrewedPotionTrigger -1M
```
```
XXX.advancements.critereon.ChangeDimensionTrigger -1M
```
```
XXX.advancements.critereon.ChanneledLightningTrigger -1M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger -1M
```
```
XXX.advancements.critereon.ConsumeItemTrigger -1M
```
```
XXX.advancements.critereon.CuredZombieVillagerTrigger -1M
```
```
XXX.advancements.critereon.EffectsChangedTrigger -1M
```
```
XXX.advancements.critereon.EnchantedItemTrigger -1M
```
```
XXX.minecraft.client.AmbientOcclusionStatus +1M
```
```
XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason +1M -1M
```
```
XXX.minecraft.client.Screenshot +1M -1M
```
```
XXX.minecraft.client.StringSplitter -1M
```
```
XXX.minecraft.client.StringSplitter$FlatComponents -1M
```
```
XXX.minecraft.client.StringSplitter$LineComponent -2M
```
```
XXX.color.block.BlockTintCache -1M
```
```
XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator -1M
```
```
XXX.components.toasts.ToastComponent -1M
```
```
XXX.gui.font.FontTexture$Node -3M
```
```
XXX.font.glyphs.WhiteGlyph +1M
```
```
XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph -1M
```
```
XXX.gui.screens.AccessibilityOptionsScreen +1M -1M
```
```
XXX.gui.screens.ConnectScreen$1 +3M -4M | +2P -2P
```
```
XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry -1M
```
```
XXX.gui.screens.LanguageSelectScreen -1M
```
```
XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry -1M
```
```
XXX.gui.screens.LoadingOverlay -1M
```
```
XXX.gui.screens.PresetFlatWorldScreen +1M -7M
```
```
XXX.screens.achievement.StatsScreen +8M -14M
```
```
XXX.screens.controls.ControlList$KeyEntry -1M
```
```
XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot -1M
```
```
XXX.screens.inventory.BeaconScreen +5M -11M
```
```
XXX.screens.inventory.BookEditScreen -1M
```
```
XXX.screens.inventory.BookEditScreen$LineInfo -5M
```
```
XXX.screens.inventory.BookViewScreen -1M
```
```
XXX.screens.inventory.CreativeModeInventoryScreen -1M
```
```
XXX.screens.inventory.JigsawBlockEditScreen -2M
```
```
XXX.screens.inventory.LecternScreen -2M
```
```
XXX.screens.inventory.MerchantScreen +1M -2M
```
```
XXX.inventory.tooltip.ClientBundleTooltip$Texture +1M
```
```
XXX.screens.packs.PackSelectionModel -4M
```
```
XXX.screens.recipebook.GhostRecipe -1M
```
```
XXX.screens.recipebook.OverlayRecipeComponent -4M | +1P
```
```
XXX.screens.social.PlayerEntry +2M -3M
```
```
XXX.screens.social.SocialInteractionsScreen$Page +1M
```
```
XXX.screens.worldselection.CreateWorldScreen +5M -6M
```
```
XXX.screens.worldselection.EditGameRulesScreen +2M -5M
```
```
XXX.screens.worldselection.EditGameRulesScreen$RuleEntry -1M
```
```
XXX.screens.worldselection.WorldGenSettingsComponent +2M -2M
```
```
XXX.screens.worldselection.WorldSelectionList$WorldListEntry +2M -3M
```
```
XXX.gui.spectator.SpectatorMenu -5M
```
```
XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem -1M
```
```
XXX.client.main.Main -1M
```
```
XXX.client.model.HumanoidModel$ArmPose +1M
```
```
XXX.client.multiplayer.ClientChunkCache -3M
```
```
XXX.client.multiplayer.ServerData$ServerPackStatus +1M
```
```
XXX.client.multiplayer.ServerStatusPinger +2M -5M | +1P
```
```
XXX.client.multiplayer.ServerStatusPinger$2 +1M -1M | +1P -1P
```
```
XXX.client.particle.BreakingItemParticle -1M
```
```
XXX.client.particle.BubbleParticle -1M
```
```
XXX.client.particle.CampfireSmokeParticle -1M
```
```
XXX.client.particle.DripParticle$CoolingDripHangParticle -1M
```
```
XXX.client.particle.DripParticle$DripLandParticle -1M
```
```
XXX.client.particle.DripParticle$FallAndLandParticle -1M
```
```
XXX.client.particle.DripParticle$HoneyFallAndLandParticle -1M
```
```
XXX.client.particle.FallingDustParticle -1M
```
```
XXX.client.particle.GlowParticle -2M
```
```
XXX.client.particle.LavaParticle -1M
```
```
XXX.client.particle.ParticleEngine$MutableSpriteSet -1M
```
```
XXX.client.particle.PlayerCloudParticle -1M
```
```
XXX.client.particle.SoulParticle -1M
```
```
XXX.client.particle.SpitParticle -1M
```
```
XXX.client.particle.WakeParticle -1M
```
```
XXX.profiling.metric.MetricSampler -1M
```
```
XXX.client.renderer.FaceInfo$VertexInfo -1M
```
```
XXX.client.renderer.FogRenderer$FogMode +1M
```
```
XXX.client.renderer.LevelRenderer$RenderChunkInfo -4M
```
```
XXX.client.renderer.RenderStateShard$ShaderStateShard +1M -1M
```
```
XXX.block.model.ItemOverrides$PropertyMatcher -1M
```
```
XXX.block.model.ItemTransforms$TransformType +1M
```
```
XXX.model.multipart.Condition +2M -2M
```
```
XXX.model.multipart.OrCondition +1M -1M
```
```
XXX.renderer.chunk.ChunkRenderDispatcher +1M -4M
```
```
XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk -7M
```
```
XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk -3M
```
```
XXX.renderer.debug.ChunkDebugRenderer -1M
```
```
XXX.renderer.texture.TextureAtlasSprite$FrameInfo -3M
```
```
XXX.renderer.texture.TextureAtlasSprite$InterpolationData -2M
```
```
XXX.client.resources.SkinManager +3M -3M
```
```
XXX.resources.model.BlockModelRotation +1M
```
```
XXX.resources.sounds.BiomeAmbientSoundsHandler +1M -1M
```
```
XXX.resources.sounds.Sound$Type +1M
```
```
XXX.resources.sounds.SoundInstance$Attenuation +1M
```
```
XXX.client.sounds.ChannelAccess$ChannelHandle -1M
```
```
XXX.minecraft.commands.CommandFunction -1M
```
```
XXX.minecraft.commands.Commands$CommandSelection +1M -2M
```
```
XXX.arguments.blocks.BlockPredicateArgument$TagPredicate -1M
```
```
XXX.arguments.item.ItemPredicateArgument +1M -1M
```
```
XXX.arguments.selector.EntitySelectorParser +2M -2M
```
```
XXX.commands.synchronization.SuggestionProviders$Wrapper -1M
```
```
XXX.minecraft.core.AxisCycle +1M -1M
```
```
XXX.minecraft.core.Direction +1M
```
```
XXX.minecraft.core.Direction$Axis +1M -1M
```
```
XXX.minecraft.core.Direction$AxisDirection +1M
```
```
XXX.minecraft.core.Direction8 +1M
```
```
XXX.minecraft.core.RegistryAccess +2M -3M
```
```
XXX.minecraft.core.RegistryAccess$RegistryHolder +2M -2M
```
```
XXX.minecraft.core.SectionPos -1M
```
```
XXX.core.particles.VibrationParticleOption +1M -1M
```
```
XXX.minecraft.data.BlockFamily -6M
```
```
XXX.models.blockstates.Condition$CompositeCondition -1M
```
```
XXX.models.blockstates.PropertyDispatch$C1 -1M
```
```
XXX.models.blockstates.PropertyDispatch$C3 +4M -5M
```
```
XXX.models.blockstates.PropertyDispatch$C5 +8M -9M
```
```
XXX.models.blockstates.VariantProperty -2M
```
```
XXX.data.recipes.RecipeProvider +2M -2M
```
```
XXX.data.structures.SnbtToNbt$TaskResult -4M
```
```
XXX.data.tags.TagsProvider +1M -1M
```
```
XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder -2M
```
```
XXX.network.chat.ChatType +1M
```
```
XXX.network.chat.ClickEvent$Action +1M
```
```
XXX.network.chat.HoverEvent$Action +1M -5M
```
```
XXX.network.chat.HoverEvent$ItemStackInfo -3M
```
```
XXX.network.chat.SubStringSource +1M -1M
```
```
XXX.network.protocol.PacketFlow +1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P
```
```
XXX.protocol.game.ClientboundBossEventPacket -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$AddOperation -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation -2M
```
```
XXX.minecraft.realms.RealmsConnect$1 -1M
```
```
XXX.minecraft.server.ServerFunctionManager$QueuedCommand -1M
```
```
XXX.server.commands.DebugCommand$Tracer -1M
```
```
XXX.server.commands.EmoteCommands +2M -2M
```
```
XXX.server.commands.ExecuteCommand +20M -20M
```
```
XXX.server.commands.ExperienceCommand$Type +1M -1M
```
```
XXX.server.commands.FillCommand$Mode +1M
```
```
XXX.server.commands.GameRuleCommand -2M
```
```
XXX.server.commands.LootCommand +10M -10M
```
```
XXX.server.commands.SeedCommand +1M -1M
```
```
XXX.server.dedicated.Settings$MutableValue -1M
```
```
XXX.server.gui.MinecraftServerGui -2M
```
```
XXX.server.level.ChunkHolder$FullChunkStatus +1M
```
```
XXX.server.level.ChunkTaskPriorityQueue +1M -1M
```
```
XXX.server.level.ServerChunkCache$MainThreadExecutor -1M
```
```
XXX.server.level.ServerLevel +2M -6M
```
```
XXX.server.network.TextFilterClient$RequestFailedException -1M
```
```
XXX.packs.repository.Pack$Position +1M
```
```
XXX.minecraft.tags.StaticTagHelper$Wrapper -1M
```
```
XXX.minecraft.tags.Tag +2M -2M
```
```
XXX.minecraft.tags.TagManager$LoaderInfo -2M
```
```
XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory -1M
```
```
XXX.minecraft.util.SortedArraySet -3M
```
```
XXX.util.profiling.ActiveProfiler$PathEntry -5M
```
```
XXX.profiling.registry.MeasurementCategory +1M
```
```
XXX.ai.behavior.GateBehavior$RunningPolicy +1M -1M
```
```
XXX.ai.behavior.PoiCompetitorScan +1M -1M
```
```
XXX.ai.behavior.PrepareRamNearestTarget +1M -1M
```
```
XXX.ai.behavior.ShufflingList -1M
```
```
XXX.ai.sensing.NearestVisibleLivingEntitySensor +1M -1M
```
```
XXX.ai.targeting.TargetingConditions +4M -5M | +2P -4P
```
```
XXX.ai.util.HoverRandomPos +1M -1M
```
```
XXX.village.poi.PoiRecord +3M -3M
```
```
XXX.entity.animal.Bee +23M -43M
```
```
XXX.entity.animal.Bee$BaseBeeGoal -1M
```
```
XXX.entity.animal.Bee$BeeGoToHiveGoal -4M
```
```
XXX.entity.animal.Bee$BeeGrowCropGoal -1M
```
```
XXX.entity.animal.Bee$BeeLocateHiveGoal +1M -3M
```
```
XXX.entity.animal.Bee$BeePollinateGoal -2M
```
```
XXX.entity.animal.Dolphin +1M -2M
```
```
XXX.entity.animal.Ocelot -1M
```
```
XXX.entity.animal.Panda$Gene +1M -1M
```
```
XXX.entity.animal.Parrot -1M
```
```
XXX.entity.animal.Pufferfish -3M | +1P -1P
```
```
XXX.entity.animal.Rabbit -2M
```
```
XXX.entity.animal.Squid +2M -1M
```
```
XXX.entity.animal.TropicalFish$Pattern +1M
```
```
XXX.entity.animal.Turtle +2M -13M
```
```
XXX.animal.goat.Goat$GoatNodeEvaluator -1M
```
```
XXX.entity.monster.Evoker$EvokerAttackSpellGoal -1M
```
```
XXX.entity.monster.Evoker$EvokerSummonSpellGoal -1M
```
```
XXX.entity.monster.Guardian -2M
```
```
XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal -1M
```
```
XXX.entity.monster.Ravager +1M -1M
```
```
XXX.entity.monster.Slime +1M -2M
```
```
XXX.entity.monster.SpellcasterIllager +1M -1M
```
```
XXX.world.inventory.ClickAction +1M
```
```
XXX.world.inventory.GrindstoneMenu -1M
```
```
XXX.world.inventory.RecipeBookType +1M
```
```
XXX.world.item.ArmorMaterials +1M
```
```
XXX.world.item.DiggerItem +2M -1M | +1P -1P
```
```
XXX.world.item.HoeItem -1P
```
```
XXX.world.item.Item$Properties -7M
```
```
XXX.item.crafting.Ingredient$ItemValue -1M
```
```
XXX.item.crafting.RecipeManager +1M -1M
```
```
XXX.item.crafting.UpgradeRecipe -3M
```
```
XXX.item.enchantment.EnchantmentCategory +1M -1M
```
```
XXX.item.enchantment.ProtectionEnchantment$Type +1M
```
```
XXX.world.level.GameRules$Category +1M
```
```
XXX.world.level.GameRules$IntegerValue -1M
```
```
XXX.world.level.GameRules$Type -2M
```
```
XXX.world.level.LightLayer +1M
```
```
XXX.world.level.NaturalSpawner$SpawnState -4M
```
```
XXX.world.level.StructureFeatureManager +1M -1M
```
```
XXX.level.biome.AmbientMoodSettings +4M -4M
```
```
XXX.level.biome.Biome +14M -16M
```
```
XXX.level.biome.Biome$ClimateParameters +5M -5M
```
```
XXX.level.biome.Biome$Precipitation +1M
```
```
XXX.level.biome.BiomeGenerationSettings +4M -5M
```
```
XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer +1M
```
```
XXX.level.biome.MultiNoiseBiomeSource$PresetInstance +3M -4M
```
```
XXX.level.biome.OverworldBiomeSource +5M -5M
```
```
XXX.level.block.ComposterBlock -2M
```
```
XXX.level.block.DoubleBlockCombiner$BlockType +1M
```
```
XXX.level.block.LightBlock +1P
```
```
XXX.level.block.PowderSnowBlock -1M | +1P -1P
```
```
XXX.level.block.PressurePlateBlock$Sensitivity +1M
```
```
XXX.block.entity.BannerPattern +1M -1M
```
```
XXX.block.entity.BarrelBlockEntity -2M
```
```
XXX.state.properties.RailShape +1M
```
```
XXX.state.properties.SculkSensorPhase +1M
```
```
XXX.state.properties.StairsShape +1M
```
```
XXX.state.properties.Tilt +1M
```
```
XXX.level.border.BorderStatus +1M
```
```
XXX.chunk.storage.IOWorker$PendingStore -3M
```
```
XXX.chunk.storage.RegionFile -1M
```
```
XXX.chunk.storage.SectionStorage +1M -1M
```
```
XXX.level.entity.Visibility +1M
```
```
XXX.level.gameevent.BlockPositionSource +1M -2M
```
```
XXX.level.gameevent.EntityPositionSource +1M -2M
```
```
XXX.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus -2M
```
```
XXX.level.levelgen.Cavifier$QuantizedSpaghettiRarity -2M
```
```
XXX.level.levelgen.Column$Line -1M
```
```
XXX.level.levelgen.GenerationStep$Carving +1M
```
```
XXX.level.levelgen.GeodeBlockSettings +6M -6M
```
```
XXX.level.levelgen.GeodeLayerSettings +4M -4M
```
```
XXX.level.levelgen.Heightmap$Types +1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +3M -8M
```
```
XXX.level.levelgen.WorldGenSettings +1M -1M
```
```
XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration +6M -6M
```
```
XXX.levelgen.carver.CarverConfiguration +6M -6M
```
```
XXX.levelgen.feature.FossilFeatureConfiguration +5M -5M
```
```
XXX.levelgen.feature.HugeFungusConfiguration +5M -5M
```
```
XXX.levelgen.feature.JigsawFeature -3M
```
```
XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader -1M
```
```
XXX.levelgen.feature.WeightedConfiguredFeature +2M -2M
```
```
XXX.feature.configurations.DiskConfiguration +4M -4M
```
```
XXX.feature.configurations.EndGatewayConfiguration +2M -2M
```
```
XXX.feature.configurations.GeodeConfiguration +13M -13M
```
```
XXX.feature.configurations.GrowingPlantConfiguration +5M -5M
```
```
XXX.feature.configurations.HugeMushroomFeatureConfiguration +3M -3M
```
```
XXX.feature.configurations.LargeDripstoneConfiguration +9M -9M
```
```
XXX.feature.configurations.MineshaftConfiguration +2M -2M
```
```
XXX.feature.configurations.OceanRuinConfiguration +3M -3M
```
```
XXX.feature.configurations.ReplaceBlockConfiguration +1M -1M
```
```
XXX.feature.configurations.RootSystemConfiguration +12M -12M
```
```
XXX.feature.configurations.SpikeConfiguration +3M -3M
```
```
XXX.feature.configurations.TreeConfiguration +9M -9M
```
```
XXX.feature.configurations.UnderwaterMagmaConfiguration +3M -3M
```
```
XXX.feature.featuresize.TwoLayersFeatureSize +3M -3M
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +1M -1M
```
```
XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector -1M
```
```
XXX.levelgen.structure.MineShaftPieces -2M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition -6M
```
```
XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement +1M
```
```
XXX.levelgen.structure.ShipwreckPieces -1M
```
```
XXX.levelgen.structure.StrongholdPieces -3M
```
```
XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector -1M
```
```
XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType +1M
```
```
XXX.saveddata.maps.MapItemSavedData$HoldingPlayer -4M
```
```
XXX.storage.loot.IntRange -3M
```
```
XXX.storage.loot.LootPool -6M
```
```
XXX.loot.entries.EmptyLootItem -1M
```
```
XXX.loot.entries.LootPoolSingletonContainer -1M
```
```
XXX.loot.functions.ApplyExplosionDecay -1M
```
```
XXX.loot.functions.CopyNbtFunction$CopyOperation -1M
```
```
XXX.loot.functions.CopyNbtFunction$MergeStrategy$3 +1M -1M
```
```
XXX.loot.functions.EnchantRandomlyFunction -2M
```
```
XXX.loot.functions.ExplorationMapFunction -7M
```
```
XXX.loot.functions.LootingEnchantFunction -4M
```
```
XXX.loot.functions.SetBannerPatternFunction$Builder -1M
```
```
XXX.loot.functions.SetContainerContents +1M -3M
```
```
XXX.loot.functions.SetItemDamageFunction -3M
```
```
XXX.loot.functions.SmeltItemFunction -1M
```
```
XXX.loot.predicates.AlternativeLootItemCondition -2M
```
```
XXX.loot.predicates.EntityHasScoreCondition -3M
```
```
XXX.loot.predicates.LootItemEntityPropertyCondition -3M
```
```
XXX.loot.predicates.LootItemRandomChanceWithLootingCondition -3M
```
```
XXX.providers.nbt.StorageNbtProvider -2M
```
```
XXX.level.timers.TimerQueue$Event -1M
```
```
XXX.phys.shapes.Shapes +2M -2M
```
```
XXX.world.scores.Team$CollisionRule +1M
```

</details>
<details>
<summary>
com.mojang.blaze3d.audio.OggAudioStream$OutputConcat
</summary>

```diff
+ int access$000(OggAudioStream$OutputConcat)
```

</details>
<details>
<summary>
com.mojang.blaze3d.pipeline.RenderTarget
</summary>

```diff
- float[] lambda$new$0()
- void <init>(boolean)
+ void <init>(int,int,boolean,boolean)
+ void lambda$bindWrite$1(boolean)
- void lambda$bindWrite$2(boolean)
+ void lambda$blitToScreen$3(int,int,boolean)
- void lambda$blitToScreen$4(int,int,boolean)
+ void lambda$resize$0(int,int,boolean)
- void lambda$resize$1(int,int,boolean)
+ void lambda$unbindWrite$2()
- void lambda$unbindWrite$3()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.InputConstants$Key
</summary>

```diff
+ Map access$200()
+ void <init>(String,InputConstants$Type,int,InputConstants$1)
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.PngInfo$StbReaderBufferedChannel
</summary>

```diff
+ void <init>(ReadableByteChannel,PngInfo$1)
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.Window
</summary>

```diff
- void setWindowed(int,int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
+ Logger access$200()
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
</summary>

```diff
+ void <init>(int,int,RenderSystem$AutoStorageIndexBuffer$IndexGenerator,RenderSystem$1)
+ void access$100(RenderSystem$AutoStorageIndexBuffer,int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.BufferBuilder$SortState
</summary>

```diff
+ float access$400(BufferBuilder$SortState)
+ float access$500(BufferBuilder$SortState)
+ float access$600(BufferBuilder$SortState)
+ int access$200(BufferBuilder$SortState)
+ Vector3f[] access$300(BufferBuilder$SortState)
+ VertexFormat$Mode access$100(BufferBuilder$SortState)
+ void <init>(VertexFormat$Mode,int,Vector3f[],float,float,float,BufferBuilder$1)
```

</details>
<details>
<summary>
com.mojang.realmsclient.client.FileDownload$ResourcePackProgressListener
</summary>

```diff
+ void <init>(FileDownload,File,RealmsDownloadLatestWorldScreen$DownloadStatus,WorldDownload,FileDownload$1)
```

</details>
<details>
<summary>
com.mojang.realmsclient.client.Ping$Region
</summary>

```diff
- Ping$Region[] $values()
+ String access$000(Ping$Region)
+ String access$100(Ping$Region)
```

</details>
<details>
<summary>
com.mojang.realmsclient.client.RealmsClient$CompatibleVersionResponse
</summary>

```diff
- RealmsClient$CompatibleVersionResponse[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.dto.RealmsServer$WorldType
</summary>

```diff
- RealmsServer$WorldType[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.dto.WorldTemplate$WorldTemplateType
</summary>

```diff
- WorldTemplate$WorldTemplateType[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.RealmsDataFetcher$Task
</summary>

```diff
- RealmsDataFetcher$Task[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.RealmsWorldSlotButton$Action
</summary>

```diff
- RealmsWorldSlotButton$Action[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
</summary>

```diff
+ Backup access$200(RealmsBackupInfoScreen)
+ Component access$100(RealmsBackupInfoScreen,String,String)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$Type
</summary>

```diff
- RealmsLongConfirmationScreen$Type[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
</summary>

```diff
+ boolean access$002(boolean)
+ boolean access$102(boolean)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$UserAction
</summary>

```diff
- RealmsPlayerScreen$UserAction[] $values()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
</summary>

```diff
+ Logger access$100()
+ void access$600(RealmsResetWorldScreen,PoseStack,int,int,Component,ResourceLocation,boolean,boolean)
+ WorldTemplatePaginatedList access$202(RealmsResetWorldScreen,WorldTemplatePaginatedList)
+ WorldTemplatePaginatedList access$302(RealmsResetWorldScreen,WorldTemplatePaginatedList)
+ WorldTemplatePaginatedList access$402(RealmsResetWorldScreen,WorldTemplatePaginatedList)
+ WorldTemplatePaginatedList access$502(RealmsResetWorldScreen,WorldTemplatePaginatedList)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
</summary>

```diff
+ boolean access$500(RealmsSelectWorldTemplateScreen)
+ Component access$2202(RealmsSelectWorldTemplateScreen,Component)
+ Component access$2300()
+ Component access$2400()
+ Either access$000(RealmsSelectWorldTemplateScreen,WorldTemplatePaginatedList,RealmsClient)
+ Font access$1300(RealmsSelectWorldTemplateScreen)
+ Font access$1400(RealmsSelectWorldTemplateScreen)
+ Font access$1500(RealmsSelectWorldTemplateScreen)
+ Font access$1600(RealmsSelectWorldTemplateScreen)
+ Font access$1800(RealmsSelectWorldTemplateScreen)
+ Font access$1900(RealmsSelectWorldTemplateScreen)
- Font access$200(RealmsSelectWorldTemplateScreen)
- Font access$300(RealmsSelectWorldTemplateScreen)
- Font access$400(RealmsSelectWorldTemplateScreen)
- Font access$500(RealmsSelectWorldTemplateScreen)
- Font access$600(RealmsSelectWorldTemplateScreen)
- Font access$700(RealmsSelectWorldTemplateScreen)
- int access$100(int)
+ int access$1002(RealmsSelectWorldTemplateScreen,int)
+ int access$600(int)
+ int access$800(RealmsSelectWorldTemplateScreen)
+ int access$802(RealmsSelectWorldTemplateScreen,int)
+ List access$402(RealmsSelectWorldTemplateScreen,List)
+ Logger access$200()
- Minecraft access$000(RealmsSelectWorldTemplateScreen)
+ Minecraft access$100(RealmsSelectWorldTemplateScreen)
+ RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList access$300(RealmsSelectWorldTemplateScreen)
+ ResourceLocation access$1700()
+ ResourceLocation access$2000()
+ ResourceLocation access$2100()
+ String access$700(RealmsSelectWorldTemplateScreen)
+ String access$702(RealmsSelectWorldTemplateScreen,String)
+ void access$1100(RealmsSelectWorldTemplateScreen)
+ void access$900(RealmsSelectWorldTemplateScreen)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$Entry
</summary>

```diff
+ WorldTemplate access$1200(RealmsSelectWorldTemplateScreen$Entry)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSettingsScreen
</summary>

```diff
- void lambda$init$2(boolean)
+ void lambda$null$2(boolean)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsUploadScreen
</summary>

```diff
+ void lambda$null$3(long,UploadResult)
- void lambda$upload$3(long,UploadResult)
```

</details>
<details>
<summary>
net.minecraft.advancements.Advancement$Builder
</summary>

```diff
+ void <init>(ResourceLocation,DisplayInfo,AdvancementRewards,Map,String[][],Advancement$1)
```

</details>
<details>
<summary>
net.minecraft.advancements.FrameType
</summary>

```diff
- FrameType[] $values()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BredAnimalsTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BrewedPotionTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChanneledLightningTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConsumeItemTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EffectsChangedTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EnchantedItemTrigger
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.client.AmbientOcclusionStatus
</summary>

```diff
- AmbientOcclusionStatus[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.ResourceLoadStateTracker$ReloadReason
</summary>

```diff
- ResourceLoadStateTracker$ReloadReason[] $values()
+ String access$400(ResourceLoadStateTracker$ReloadReason)
```

</details>
<details>
<summary>
net.minecraft.client.Screenshot
</summary>

```diff
- Style lambda$_grab$1(File,Style)
+ Style lambda$null$1(File,Style)
```

</details>
<details>
<summary>
net.minecraft.client.StringSplitter
</summary>

```diff
+ StringSplitter$WidthProvider access$000(StringSplitter)
```

</details>
<details>
<summary>
net.minecraft.client.StringSplitter$FlatComponents
</summary>

```diff
+ List access$300(StringSplitter$FlatComponents)
```

</details>
<details>
<summary>
net.minecraft.client.StringSplitter$LineComponent
</summary>

```diff
+ String access$100(StringSplitter$LineComponent)
+ Style access$200(StringSplitter$LineComponent)
```

</details>
<details>
<summary>
net.minecraft.client.color.block.BlockTintCache
</summary>

```diff
+ BlockTintCache$LatestCacheInfo lambda$new$0()
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
</summary>

```diff
+ void <init>(PlayerTabOverlay$1)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.toasts.ToastComponent
</summary>

```diff
+ Minecraft access$100(ToastComponent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.FontTexture$Node
</summary>

```diff
+ int access$100(FontTexture$Node)
+ int access$200(FontTexture$Node)
+ void <init>(int,int,int,int,FontTexture$1)
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.glyphs.WhiteGlyph
</summary>

```diff
- WhiteGlyph[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
</summary>

```diff
+ void <init>(int,int,int,int,NativeImage,LegacyUnicodeBitmapsProvider$1)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.AccessibilityOptionsScreen
</summary>

```diff
- void lambda$createFooter$0(boolean)
+ void lambda$null$0(boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ConnectScreen$1
</summary>

```diff
- void <init>(ConnectScreen,String,ServerAddress,Minecraft)
+ void <init>(ConnectScreen,String,String,int)
+ void lambda$run$0(ConnectScreen,Component)
- void lambda$run$0(Minecraft)
+ void lambda$run$1()
- void lambda$run$1(Minecraft,String)
+ void lambda$run$2(String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
</summary>

```diff
+ void <init>(CreateFlatWorldScreen$DetailsList,CreateFlatWorldScreen$1)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen
</summary>

```diff
+ LanguageManager access$000(LanguageSelectScreen)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
</summary>

```diff
+ LanguageInfo access$100(LanguageSelectScreen$LanguageSelectionList$Entry)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LoadingOverlay
</summary>

```diff
+ ResourceLocation access$000()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen
</summary>

```diff
+ Biome lambda$null$4(Registry,ResourceKey)
- Biome lambda$preset$4(Registry,ResourceKey)
+ CreateFlatWorldScreen access$200(PresetFlatWorldScreen)
+ EditBox access$500(PresetFlatWorldScreen)
+ FlatLevelGeneratorSettings access$300(PresetFlatWorldScreen)
+ FlatLevelGeneratorSettings access$302(PresetFlatWorldScreen,FlatLevelGeneratorSettings)
+ List access$000()
+ String access$400(Registry,FlatLevelGeneratorSettings)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen
</summary>

```diff
- Font access$000(StatsScreen)
- Font access$100(StatsScreen)
- Font access$1200(StatsScreen)
+ Font access$1400(StatsScreen)
+ Font access$1500(StatsScreen)
+ Font access$1600(StatsScreen)
+ Font access$1700(StatsScreen)
+ Font access$1800(StatsScreen)
+ Font access$1900(StatsScreen)
+ Font access$2000(StatsScreen)
+ Font access$2100(StatsScreen)
- Font access$300(StatsScreen)
- Font access$600(StatsScreen)
- Font access$700(StatsScreen)
- Font access$800(StatsScreen)
- Font access$900(StatsScreen)
+ int access$800(StatsScreen,int)
+ StatsCounter access$300(StatsScreen)
+ StatsScreen$ItemStatisticsList access$1200(StatsScreen)
+ String access$100(Stat)
+ void access$1300(StatsScreen,PoseStack,int,int,Item)
+ void access$900(StatsScreen,PoseStack,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
</summary>

```diff
+ void <init>(ControlList,KeyMapping,Component,ControlList$1)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
</summary>

```diff
+ GameModeSwitcherScreen$GameModeIcon access$100(GameModeSwitcherScreen$GameModeSlot)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BeaconScreen
</summary>

```diff
+ boolean access$202(BeaconScreen,boolean)
- List access$000(BeaconScreen)
- List access$100(BeaconScreen)
+ List access$400(BeaconScreen)
+ List access$500(BeaconScreen)
- Minecraft access$200(BeaconScreen)
- Minecraft access$300(BeaconScreen)
- Minecraft access$400(BeaconScreen)
+ Minecraft access$600(BeaconScreen)
+ Minecraft access$700(BeaconScreen)
+ Minecraft access$800(BeaconScreen)
+ MobEffect access$000(BeaconScreen)
+ MobEffect access$002(BeaconScreen,MobEffect)
+ MobEffect access$100(BeaconScreen)
+ MobEffect access$102(BeaconScreen,MobEffect)
+ ResourceLocation access$300()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookEditScreen
</summary>

```diff
+ int access$1000(int[],int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
</summary>

```diff
+ Component access$200(BookEditScreen$LineInfo)
+ int access$300(BookEditScreen$LineInfo)
+ int access$400(BookEditScreen$LineInfo)
+ String access$800(BookEditScreen$LineInfo)
+ Style access$900(BookEditScreen$LineInfo)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookViewScreen
</summary>

```diff
+ List access$000(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
</summary>

```diff
+ SimpleContainer access$000()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
</summary>

```diff
+ int access$000(JigsawBlockEditScreen)
+ int access$002(JigsawBlockEditScreen,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.LecternScreen
</summary>

```diff
+ void access$000(LecternScreen)
+ void access$100(LecternScreen)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.MerchantScreen
</summary>

```diff
+ int access$000(MerchantScreen)
- void access$000(MerchantScreen,PoseStack,ItemStack,int,int)
+ void access$300(MerchantScreen,PoseStack,ItemStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
</summary>

```diff
- ClientBundleTooltip$Texture[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.packs.PackSelectionModel
</summary>

```diff
+ Function access$000(PackSelectionModel)
+ List access$200(PackSelectionModel)
+ List access$300(PackSelectionModel)
+ Runnable access$100(PackSelectionModel)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.GhostRecipe
</summary>

```diff
+ float access$000(GhostRecipe)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
</summary>

```diff
+ boolean access$200(OverlayRecipeComponent)
+ float access$300(OverlayRecipeComponent)
+ Minecraft access$400(OverlayRecipeComponent)
+ ResourceLocation access$100()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.social.PlayerEntry
</summary>

```diff
+ MutableComponent access$000(PlayerEntry,MutableComponent)
- void lambda$new$1(SocialInteractionsScreen,PoseStack,int,int)
- void lambda$new$4(SocialInteractionsScreen,PoseStack,int,int)
+ void lambda$null$1(SocialInteractionsScreen,PoseStack,int,int)
+ void lambda$null$4(SocialInteractionsScreen,PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
</summary>

```diff
- SocialInteractionsScreen$Page[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
</summary>

```diff
+ String access$000(CreateWorldScreen)
- void lambda$init$7(GameRules)
- void lambda$init$8(Optional)
+ void lambda$null$15(boolean)
+ void lambda$null$16()
+ void lambda$null$17(DataPackConfig,ServerResources)
+ void lambda$null$7(GameRules)
+ void lambda$null$8(Optional)
- void lambda$tryApplyNewDataPacks$15(boolean)
- void lambda$tryApplyNewDataPacks$16()
- void lambda$tryApplyNewDataPacks$17(DataPackConfig,ServerResources)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen
</summary>

```diff
- Font access$700(EditGameRulesScreen)
+ Font access$900(EditGameRulesScreen)
- Minecraft access$600(EditGameRulesScreen)
+ Minecraft access$800(EditGameRulesScreen)
+ void access$1100(EditGameRulesScreen,List)
+ void access$600(EditGameRulesScreen,EditGameRulesScreen$RuleEntry)
+ void access$700(EditGameRulesScreen,EditGameRulesScreen$RuleEntry)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
</summary>

```diff
+ List access$1000(EditGameRulesScreen$RuleEntry)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
</summary>

```diff
- void lambda$init$8(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,WorldGenSettings,boolean)
- void lambda$init$9(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,Lifecycle,WorldGenSettings)
+ void lambda$null$8(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,WorldGenSettings,boolean)
+ void lambda$null$9(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,Lifecycle,WorldGenSettings)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
</summary>

```diff
+ LevelSummary access$000(WorldSelectionList$WorldListEntry)
- String lambda$editWorld$5()
+ String lambda$null$5()
- void lambda$joinWorld$1()
+ void lambda$null$1()
```

</details>
<details>
<summary>
net.minecraft.client.gui.spectator.SpectatorMenu
</summary>

```diff
+ Component access$100()
+ Component access$300()
+ Component access$400()
+ int access$200(SpectatorMenu)
+ int access$202(SpectatorMenu,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
</summary>

```diff
+ void <init>(SpectatorMenu$1)
```

</details>
<details>
<summary>
net.minecraft.client.main.Main
</summary>

```diff
+ Logger access$000()
```

</details>
<details>
<summary>
net.minecraft.client.model.HumanoidModel$ArmPose
</summary>

```diff
- HumanoidModel$ArmPose[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientChunkCache
</summary>

```diff
+ ClientChunkCache$Storage access$900(ClientChunkCache)
+ ClientLevel access$800(ClientChunkCache)
+ Logger access$1000()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ServerData$ServerPackStatus
</summary>

```diff
- ServerData$ServerPackStatus[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ServerStatusPinger
</summary>

```diff
+ Component access$000(int,int)
+ Logger access$100()
+ Splitter access$300()
+ void access$200(ServerStatusPinger,ServerData)
- void onPingFailed(Component,ServerData)
- void pingLegacyServer(InetSocketAddress,ServerData)
+ void pingLegacyServer(ServerData)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ServerStatusPinger$2
</summary>

```diff
- void <init>(ServerStatusPinger,InetSocketAddress,ServerData)
+ void <init>(ServerStatusPinger,ServerAddress,ServerData)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BreakingItemParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,ItemStack,BreakingItemParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BubbleParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,BubbleParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.CampfireSmokeParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,boolean,CampfireSmokeParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions,DripParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$DripLandParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,Fluid,DripParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$FallAndLandParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions,DripParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions,DripParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FallingDustParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,float,float,float,SpriteSet,FallingDustParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.GlowParticle
</summary>

```diff
+ Random access$000()
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,GlowParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.LavaParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,LavaParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
</summary>

```diff
+ void <init>(ParticleEngine,ParticleEngine$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.PlayerCloudParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,PlayerCloudParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SoulParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,SoulParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SpitParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,SpitParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.particle.WakeParticle
</summary>

```diff
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,WakeParticle$1)
```

</details>
<details>
<summary>
net.minecraft.client.profiling.metric.MetricSampler
</summary>

```diff
+ void <init>(Metric,DoubleSupplier,Runnable,MetricSampler$ThresholdAlerter,MetricSampler$1)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FaceInfo$VertexInfo
</summary>

```diff
+ void <init>(int,int,int,FaceInfo$1)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FogRenderer$FogMode
</summary>

```diff
- FogRenderer$FogMode[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
</summary>

```diff
+ byte access$500(LevelRenderer$RenderChunkInfo)
+ ChunkRenderDispatcher$RenderChunk access$100(LevelRenderer$RenderChunkInfo)
+ int access$400(LevelRenderer$RenderChunkInfo)
+ void <init>(ChunkRenderDispatcher$RenderChunk,Direction,int,LevelRenderer$1)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderStateShard$ShaderStateShard
</summary>

```diff
- ShaderInstance lambda$new$2()
+ ShaderInstance lambda$null$2()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
</summary>

```diff
+ void <init>(int,float,ItemOverrides$1)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
</summary>

```diff
- ItemTransforms$TransformType[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.multipart.Condition
</summary>

```diff
+ boolean lambda$null$0(BlockState)
+ boolean lambda$null$2(BlockState)
- boolean lambda$static$0(BlockState)
- boolean lambda$static$2(BlockState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.multipart.OrCondition
</summary>

```diff
- boolean lambda$getPredicate$1(BlockState,Predicate)
+ boolean lambda$null$1(BlockState,Predicate)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
</summary>

```diff
+ ChunkBufferBuilderPack access$300(ChunkRenderDispatcher)
+ Level access$000(ChunkRenderDispatcher)
+ LevelRenderer access$200(ChunkRenderDispatcher)
+ void lambda$null$2(ChunkRenderDispatcher$ChunkTaskResult,ChunkBufferBuilderPack)
- void lambda$runTask$2(ChunkRenderDispatcher$ChunkTaskResult,ChunkBufferBuilderPack)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
</summary>

```diff
+ boolean access$702(ChunkRenderDispatcher$CompiledChunk,boolean)
+ BufferBuilder$SortState access$900(ChunkRenderDispatcher$CompiledChunk)
+ BufferBuilder$SortState access$902(ChunkRenderDispatcher$CompiledChunk,BufferBuilder$SortState)
+ List access$1100(ChunkRenderDispatcher$CompiledChunk)
+ Set access$100(ChunkRenderDispatcher$CompiledChunk)
+ Set access$800(ChunkRenderDispatcher$CompiledChunk)
+ VisibilitySet access$1002(ChunkRenderDispatcher$CompiledChunk,VisibilitySet)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
</summary>

```diff
+ BlockPos$MutableBlockPos access$500(ChunkRenderDispatcher$RenderChunk)
+ void access$400(ChunkRenderDispatcher$RenderChunk,Set)
+ void access$600(ChunkRenderDispatcher$RenderChunk,BufferBuilder)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.ChunkDebugRenderer
</summary>

```diff
+ Minecraft access$300(ChunkDebugRenderer)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureAtlasSprite$FrameInfo
</summary>

```diff
+ int access$600(TextureAtlasSprite$FrameInfo)
+ int access$700(TextureAtlasSprite$FrameInfo)
+ void <init>(int,int,TextureAtlasSprite$1)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureAtlasSprite$InterpolationData
</summary>

```diff
+ void <init>(TextureAtlasSprite,TextureAtlasSprite$Info,int,TextureAtlasSprite$1)
+ void access$1700(TextureAtlasSprite$InterpolationData,TextureAtlasSprite$AnimatedTexture)
```

</details>
<details>
<summary>
net.minecraft.client.resources.SkinManager
</summary>

```diff
+ void lambda$null$1(Map,SkinManager$SkinTextureCallback,MinecraftProfileTexture$Type)
+ void lambda$null$2(Map,SkinManager$SkinTextureCallback)
+ void lambda$null$3(Map,SkinManager$SkinTextureCallback)
- void lambda$registerSkins$1(Map,SkinManager$SkinTextureCallback,MinecraftProfileTexture$Type)
- void lambda$registerSkins$2(Map,SkinManager$SkinTextureCallback)
- void lambda$registerSkins$3(Map,SkinManager$SkinTextureCallback)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.BlockModelRotation
</summary>

```diff
- BlockModelRotation[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
</summary>

```diff
+ BiomeAmbientSoundsHandler$LoopSoundInstance lambda$null$0(SoundEvent,Biome,BiomeAmbientSoundsHandler$LoopSoundInstance)
- BiomeAmbientSoundsHandler$LoopSoundInstance lambda$tick$0(SoundEvent,Biome,BiomeAmbientSoundsHandler$LoopSoundInstance)
```

</details>
<details>
<summary>
net.minecraft.client.resources.sounds.Sound$Type
</summary>

```diff
- Sound$Type[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.resources.sounds.SoundInstance$Attenuation
</summary>

```diff
- SoundInstance$Attenuation[] $values()
```

</details>
<details>
<summary>
net.minecraft.client.sounds.ChannelAccess$ChannelHandle
</summary>

```diff
+ Channel access$200(ChannelAccess$ChannelHandle)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandFunction
</summary>

```diff
+ ResourceLocation access$000(CommandFunction)
```

</details>
<details>
<summary>
net.minecraft.commands.Commands$CommandSelection
</summary>

```diff
+ boolean access$000(Commands$CommandSelection)
+ boolean access$100(Commands$CommandSelection)
- Commands$CommandSelection[] $values()
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
</summary>

```diff
+ void <init>(Tag,Map,CompoundTag,BlockPredicateArgument$1)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.ItemPredicateArgument
</summary>

```diff
+ CommandSyntaxException lambda$null$2(ResourceLocation)
- CommandSyntaxException lambda$parse$2(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.EntitySelectorParser
</summary>

```diff
+ int lambda$null$3(Vec3,Entity,Entity)
+ int lambda$null$5(Vec3,Entity,Entity)
- int lambda$static$3(Vec3,Entity,Entity)
- int lambda$static$5(Vec3,Entity,Entity)
```

</details>
<details>
<summary>
net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
</summary>

```diff
+ ResourceLocation access$000(SuggestionProviders$Wrapper)
```

</details>
<details>
<summary>
net.minecraft.core.AxisCycle
</summary>

```diff
- AxisCycle[] $values()
+ void <init>(String,int,AxisCycle$1)
```

</details>
<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
- Direction[] $values()
```

</details>
<details>
<summary>
net.minecraft.core.Direction$Axis
</summary>

```diff
- Direction$Axis[] $values()
+ void <init>(String,int,String,Direction$1)
```

</details>
<details>
<summary>
net.minecraft.core.Direction$AxisDirection
</summary>

```diff
- Direction$AxisDirection[] $values()
```

</details>
<details>
<summary>
net.minecraft.core.Direction8
</summary>

```diff
- Direction8[] $values()
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess
</summary>

```diff
+ boolean lambda$null$3(ResourceKey)
- boolean lambda$static$3(ResourceKey)
+ Map access$000()
+ void lambda$null$4(RegistryAccess$RegistryHolder,ResourceKey)
- void lambda$static$4(RegistryAccess$RegistryHolder,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess$RegistryHolder
</summary>

```diff
- boolean lambda$captureMap$3(Map$Entry)
+ boolean lambda$null$3(Map$Entry)
- Codec lambda$makeNetworkCodec$1(ResourceKey,Codec)
+ Codec lambda$null$1(ResourceKey,Codec)
```

</details>
<details>
<summary>
net.minecraft.core.SectionPos
</summary>

```diff
+ void <init>(int,int,int,SectionPos$1)
```

</details>
<details>
<summary>
net.minecraft.core.particles.VibrationParticleOption
</summary>

```diff
+ VibrationPath lambda$null$0(VibrationParticleOption)
- VibrationPath lambda$static$0(VibrationParticleOption)
```

</details>
<details>
<summary>
net.minecraft.data.BlockFamily
</summary>

```diff
+ boolean access$202(BlockFamily,boolean)
+ boolean access$302(BlockFamily,boolean)
+ Map access$100(BlockFamily)
+ String access$402(BlockFamily,String)
+ String access$502(BlockFamily,String)
+ void <init>(Block,BlockFamily$1)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.Condition$CompositeCondition
</summary>

```diff
+ void <init>(Condition$Operation,List,Condition$1)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.PropertyDispatch$C1
</summary>

```diff
+ void <init>(Property,PropertyDispatch$1)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.PropertyDispatch$C3
</summary>

```diff
+ void <init>(Property,Property,Property,PropertyDispatch$1)
- void lambda$generate$0(Comparable,Comparable,PropertyDispatch$TriFunction,Comparable)
- void lambda$generate$1(Comparable,PropertyDispatch$TriFunction,Comparable)
- void lambda$generateList$3(Comparable,Comparable,PropertyDispatch$TriFunction,Comparable)
- void lambda$generateList$4(Comparable,PropertyDispatch$TriFunction,Comparable)
+ void lambda$null$0(Comparable,Comparable,PropertyDispatch$TriFunction,Comparable)
+ void lambda$null$1(Comparable,PropertyDispatch$TriFunction,Comparable)
+ void lambda$null$3(Comparable,Comparable,PropertyDispatch$TriFunction,Comparable)
+ void lambda$null$4(Comparable,PropertyDispatch$TriFunction,Comparable)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.PropertyDispatch$C5
</summary>

```diff
+ void <init>(Property,Property,Property,Property,Property,PropertyDispatch$1)
- void lambda$generate$0(Comparable,Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generate$1(Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generate$2(Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generate$3(Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generateList$5(Comparable,Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generateList$6(Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generateList$7(Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
- void lambda$generateList$8(Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$0(Comparable,Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$1(Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$2(Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$3(Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$5(Comparable,Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$6(Comparable,Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$7(Comparable,Comparable,PropertyDispatch$PentaFunction,Comparable)
+ void lambda$null$8(Comparable,PropertyDispatch$PentaFunction,Comparable)
```

</details>
<details>
<summary>
net.minecraft.data.models.blockstates.VariantProperty
</summary>

```diff
+ Function access$100(VariantProperty)
+ String access$000(VariantProperty)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- String lambda$generateRecipes$4(ItemLike)
+ String lambda$null$4(ItemLike)
- void lambda$generateRecipes$3(RecipeBuilder,BlockFamily$Variant,String)
+ void lambda$null$3(RecipeBuilder,BlockFamily$Variant,String)
```

</details>
<details>
<summary>
net.minecraft.data.structures.SnbtToNbt$TaskResult
</summary>

```diff
+ byte[] access$300(SnbtToNbt$TaskResult)
+ String access$000(SnbtToNbt$TaskResult)
+ String access$100(SnbtToNbt$TaskResult)
+ String access$200(SnbtToNbt$TaskResult)
```

</details>
<details>
<summary>
net.minecraft.data.tags.TagsProvider
</summary>

```diff
+ boolean lambda$null$0(Tag$BuilderEntry)
- boolean lambda$run$0(Tag$BuilderEntry)
```

</details>
<details>
<summary>
net.minecraft.network.ConnectionProtocol$ProtocolBuilder
</summary>

```diff
+ Map access$200(ConnectionProtocol$ProtocolBuilder)
+ void <init>(ConnectionProtocol$1)
```

</details>
<details>
<summary>
net.minecraft.network.chat.ChatType
</summary>

```diff
- ChatType[] $values()
```

</details>
<details>
<summary>
net.minecraft.network.chat.ClickEvent$Action
</summary>

```diff
- ClickEvent$Action[] $values()
```

</details>
<details>
<summary>
net.minecraft.network.chat.HoverEvent$Action
</summary>

```diff
- HoverEvent$Action lambda$static$0(HoverEvent$Action)
+ HoverEvent$Action lambda$static$3(HoverEvent$Action)
+ HoverEvent$ItemStackInfo lambda$static$0(JsonElement)
+ HoverEvent$ItemStackInfo lambda$static$2(Component)
+ JsonElement lambda$static$1(Object)
+ Object access$000(HoverEvent$Action,Object)
```

</details>
<details>
<summary>
net.minecraft.network.chat.HoverEvent$ItemStackInfo
</summary>

```diff
+ HoverEvent$ItemStackInfo access$200(Component)
+ HoverEvent$ItemStackInfo access$400(JsonElement)
+ JsonElement access$300(HoverEvent$ItemStackInfo)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SubStringSource
</summary>

```diff
- boolean lambda$create$2(StringBuilder,List,int,Style,int)
+ boolean lambda$null$2(StringBuilder,List,int,Style,int)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.PacketFlow
</summary>

```diff
- PacketFlow[] $values()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket
</summary>

```diff
+ ClientboundBossEventPacket$Operation access$1000()
+ int access$1200(boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
</summary>

```diff
+ void <init>(BossEvent,ClientboundBossEventPacket$1)
+ void <init>(FriendlyByteBuf,ClientboundBossEventPacket$1)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
</summary>

```diff
+ void <init>(Component,ClientboundBossEventPacket$1)
+ void <init>(FriendlyByteBuf,ClientboundBossEventPacket$1)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
</summary>

```diff
+ void <init>(boolean,boolean,boolean,ClientboundBossEventPacket$1)
+ void <init>(FriendlyByteBuf,ClientboundBossEventPacket$1)
```

</details>
<details>
<summary>
net.minecraft.realms.RealmsConnect$1
</summary>

```diff
+ void lambda$run$2(Minecraft,DisconnectedRealmsScreen)
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionManager$QueuedCommand
</summary>

```diff
+ int access$400(ServerFunctionManager$QueuedCommand)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DebugCommand$Tracer
</summary>

```diff
+ void <init>(PrintWriter,DebugCommand$1)
```

</details>
<details>
<summary>
net.minecraft.server.commands.EmoteCommands
</summary>

```diff
+ Component lambda$null$0(ServerPlayer,Component,Component,ServerPlayer)
- Component lambda$register$0(ServerPlayer,Component,Component,ServerPlayer)
+ void lambda$null$1(CommandContext,MinecraftServer,ServerPlayer,Entity,TextFilter$FilteredText)
- void lambda$register$1(CommandContext,MinecraftServer,ServerPlayer,Entity,TextFilter$FilteredText)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ExecuteCommand
</summary>

```diff
- boolean lambda$addConditionals$40(Integer,Integer)
- boolean lambda$addConditionals$42(Integer,Integer)
- boolean lambda$addConditionals$44(Integer,Integer)
- boolean lambda$addConditionals$46(Integer,Integer)
+ boolean lambda$null$40(Integer,Integer)
+ boolean lambda$null$42(Integer,Integer)
+ boolean lambda$null$44(Integer,Integer)
+ boolean lambda$null$46(Integer,Integer)
- Collection lambda$addConditionals$52(boolean,DataCommands$DataProvider,CommandContext)
+ Collection lambda$null$52(boolean,DataCommands$DataProvider,CommandContext)
+ CommandSourceStack lambda$null$22(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$24(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$26(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$28(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$30(DataCommands$DataProvider,boolean,CommandContext)
+ CommandSourceStack lambda$null$32(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$22(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$24(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$26(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$28(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$30(DataCommands$DataProvider,boolean,CommandContext)
- CommandSourceStack lambda$wrapStores$32(DataCommands$DataProvider,boolean,CommandContext)
- int lambda$addConditionals$53(DataCommands$DataProvider,CommandContext)
+ int lambda$null$53(DataCommands$DataProvider,CommandContext)
+ Tag lambda$null$21(CommandContext,int)
+ Tag lambda$null$23(CommandContext,int)
+ Tag lambda$null$25(CommandContext,int)
+ Tag lambda$null$27(CommandContext,int)
+ Tag lambda$null$29(CommandContext,int)
+ Tag lambda$null$31(CommandContext,int)
+ Tag lambda$null$36(IntFunction,int)
- Tag lambda$storeData$36(IntFunction,int)
- Tag lambda$wrapStores$21(CommandContext,int)
- Tag lambda$wrapStores$23(CommandContext,int)
- Tag lambda$wrapStores$25(CommandContext,int)
- Tag lambda$wrapStores$27(CommandContext,int)
- Tag lambda$wrapStores$29(CommandContext,int)
- Tag lambda$wrapStores$31(CommandContext,int)
+ void lambda$null$2(ResultConsumer,ResultConsumer,CommandContext,boolean,int)
- void lambda$static$2(ResultConsumer,ResultConsumer,CommandContext,boolean,int)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ExperienceCommand$Type
</summary>

```diff
- ExperienceCommand$Type[] $values()
+ ToIntFunction access$000(ExperienceCommand$Type)
```

</details>
<details>
<summary>
net.minecraft.server.commands.FillCommand$Mode
</summary>

```diff
- FillCommand$Mode[] $values()
```

</details>
<details>
<summary>
net.minecraft.server.commands.GameRuleCommand
</summary>

```diff
+ int access$000(CommandContext,GameRules$Key)
+ int access$100(CommandSourceStack,GameRules$Key)
```

</details>
<details>
<summary>
net.minecraft.server.commands.LootCommand
</summary>

```diff
+ int lambda$null$10(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$11(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$12(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$13(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$4(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$5(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$6(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$7(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$8(LootCommand$DropConsumer,CommandContext)
+ int lambda$null$9(LootCommand$DropConsumer,CommandContext)
- int lambda$register$10(LootCommand$DropConsumer,CommandContext)
- int lambda$register$11(LootCommand$DropConsumer,CommandContext)
- int lambda$register$12(LootCommand$DropConsumer,CommandContext)
- int lambda$register$13(LootCommand$DropConsumer,CommandContext)
- int lambda$register$4(LootCommand$DropConsumer,CommandContext)
- int lambda$register$5(LootCommand$DropConsumer,CommandContext)
- int lambda$register$6(LootCommand$DropConsumer,CommandContext)
- int lambda$register$7(LootCommand$DropConsumer,CommandContext)
- int lambda$register$8(LootCommand$DropConsumer,CommandContext)
- int lambda$register$9(LootCommand$DropConsumer,CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SeedCommand
</summary>

```diff
+ Style lambda$null$1(long,Style)
- Style lambda$register$1(long,Style)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.Settings$MutableValue
</summary>

```diff
+ void <init>(Settings,String,Object,Function,Settings$1)
```

</details>
<details>
<summary>
net.minecraft.server.gui.MinecraftServerGui
</summary>

```diff
+ AtomicBoolean access$000(MinecraftServerGui)
+ void access$100(MinecraftServerGui)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkHolder$FullChunkStatus
</summary>

```diff
- ChunkHolder$FullChunkStatus[] $values()
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkTaskPriorityQueue
</summary>

```diff
+ Either lambda$null$5(long)
- Either lambda$pop$5(long)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
</summary>

```diff
+ void <init>(ServerChunkCache,Level,ServerChunkCache$1)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ EntityTickList access$100(ServerLevel)
+ Int2ObjectMap access$400(ServerLevel)
+ List access$200(ServerLevel)
+ Set access$300(ServerLevel)
+ void lambda$null$16(BlockPos)
+ void lambda$null$18(BlockPos,PoiType)
- void lambda$onBlockStateChange$16(BlockPos)
- void lambda$onBlockStateChange$18(BlockPos,PoiType)
```

</details>
<details>
<summary>
net.minecraft.server.network.TextFilterClient$RequestFailedException
</summary>

```diff
+ void <init>(String,TextFilterClient$1)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.Pack$Position
</summary>

```diff
- Pack$Position[] $values()
```

</details>
<details>
<summary>
net.minecraft.tags.StaticTagHelper$Wrapper
</summary>

```diff
+ void <init>(ResourceLocation,StaticTagHelper$1)
```

</details>
<details>
<summary>
net.minecraft.tags.Tag
</summary>

```diff
- DataResult lambda$codec$0(ResourceLocation)
- DataResult lambda$codec$2(Tag)
+ DataResult lambda$null$0(ResourceLocation)
+ DataResult lambda$null$2(Tag)
```

</details>
<details>
<summary>
net.minecraft.tags.TagManager$LoaderInfo
</summary>

```diff
+ CompletableFuture access$100(TagManager$LoaderInfo)
+ void <init>(StaticTagHelper,CompletableFuture,TagManager$1)
```

</details>
<details>
<summary>
net.minecraft.util.LowerCaseEnumTypeAdapterFactory
</summary>

```diff
+ String access$000(LowerCaseEnumTypeAdapterFactory,Object)
```

</details>
<details>
<summary>
net.minecraft.util.SortedArraySet
</summary>

```diff
+ int access$000(SortedArraySet)
+ Object[] access$100(SortedArraySet)
+ void access$200(SortedArraySet,int)
```

</details>
<details>
<summary>
net.minecraft.util.profiling.ActiveProfiler$PathEntry
</summary>

```diff
+ long access$000(ActiveProfiler$PathEntry)
+ long access$002(ActiveProfiler$PathEntry,long)
+ long access$100(ActiveProfiler$PathEntry)
+ long access$102(ActiveProfiler$PathEntry,long)
+ Object2LongOpenHashMap access$200(ActiveProfiler$PathEntry)
```

</details>
<details>
<summary>
net.minecraft.util.profiling.registry.MeasurementCategory
</summary>

```diff
- MeasurementCategory[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
</summary>

```diff
- GateBehavior$RunningPolicy[] $values()
+ void <init>(String,int,GateBehavior$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
</summary>

```diff
+ boolean lambda$null$0(GlobalPos,PoiType,Villager)
- boolean lambda$start$0(GlobalPos,PoiType,Villager)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
</summary>

```diff
+ boolean lambda$null$0(PathfinderMob,LivingEntity)
- boolean lambda$start$0(PathfinderMob,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.ShufflingList
</summary>

```diff
+ double lambda$shuffle$2(Object)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
</summary>

```diff
- boolean lambda$getNearestEntity$0(LivingEntity,LivingEntity)
+ boolean lambda$null$0(LivingEntity,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.targeting.TargetingConditions
</summary>

```diff
+ TargetingConditions allowInvulnerable()
+ TargetingConditions allowNonAttackable()
+ TargetingConditions allowSameTeam()
+ TargetingConditions allowUnseeable()
- TargetingConditions forCombat()
- TargetingConditions forNonCombat()
- TargetingConditions ignoreLineOfSight()
+ void <init>()
- void <init>(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.util.HoverRandomPos
</summary>

```diff
- boolean lambda$getPos$0(PathfinderMob,BlockPos)
+ boolean lambda$null$0(PathfinderMob,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiRecord
</summary>

```diff
- BlockPos lambda$codec$0(PoiRecord)
+ BlockPos lambda$null$0(PoiRecord)
- Integer lambda$codec$2(PoiRecord)
+ Integer lambda$null$2(PoiRecord)
- PoiType lambda$codec$1(PoiRecord)
+ PoiType lambda$null$1(PoiRecord)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
+ Bee$BeeGoToHiveGoal access$4800(Bee)
+ Bee$BeePollinateGoal access$700(Bee)
+ BlockPos access$1500(Bee)
+ BlockPos access$1502(Bee,BlockPos)
+ BlockPos access$3200(Bee)
+ BlockPos access$3202(Bee,BlockPos)
+ boolean access$1400(Bee)
+ boolean access$1600(Bee,BlockPos,int)
+ boolean access$1800(Bee)
+ boolean access$2400(Bee,BlockPos)
+ boolean access$3300(Bee,BlockPos)
+ boolean access$5100(Bee,BlockPos)
+ int access$3000(Bee)
+ int access$3002(Bee,int)
+ int access$3700(Bee)
+ int access$3800(Bee)
+ int access$3802(Bee,int)
+ int access$5200(Bee)
- PathNavigation access$000(Bee)
- PathNavigation access$1000(Bee)
- PathNavigation access$1400(Bee)
- PathNavigation access$1500(Bee)
- PathNavigation access$1600(Bee)
- PathNavigation access$1700(Bee)
- PathNavigation access$1800(Bee)
+ PathNavigation access$1900(Bee)
- PathNavigation access$200(Bee)
+ PathNavigation access$2000(Bee)
+ PathNavigation access$2200(Bee)
+ PathNavigation access$2600(Bee)
+ PathNavigation access$2700(Bee)
+ PathNavigation access$2800(Bee)
+ PathNavigation access$2900(Bee)
- PathNavigation access$300(Bee)
+ PathNavigation access$3100(Bee)
+ PathNavigation access$3400(Bee)
+ PathNavigation access$3500(Bee)
+ PathNavigation access$3600(Bee)
+ PathNavigation access$3900(Bee)
- PathNavigation access$400(Bee)
+ PathNavigation access$4300(Bee)
+ PathNavigation access$4500(Bee)
- PathNavigation access$500(Bee)
- PathNavigation access$600(Bee)
- PathNavigation access$700(Bee)
- PathNavigation access$800(Bee)
- Random access$100(Bee)
+ Random access$1000(Bee)
- Random access$1900(Bee)
- Random access$2000(Bee)
- Random access$2200(Bee)
- Random access$2400(Bee)
- Random access$2500(Bee)
- Random access$2600(Bee)
- Random access$2700(Bee)
- Random access$2800(Bee)
+ Random access$4000(Bee)
+ Random access$4100(Bee)
+ Random access$4400(Bee)
+ Random access$4600(Bee)
+ Random access$4700(Bee)
+ Random access$5300(Bee)
+ Random access$5400(Bee)
+ void access$2500(Bee,BlockPos)
+ void access$4200(Bee,boolean)
+ void access$5500(Bee)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BaseBeeGoal
</summary>

```diff
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
</summary>

```diff
+ boolean access$4900(Bee$BeeGoToHiveGoal,BlockPos)
+ int access$300(Bee$BeeGoToHiveGoal)
+ List access$500(Bee$BeeGoToHiveGoal)
+ void access$5000(Bee$BeeGoToHiveGoal)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
</summary>

```diff
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
</summary>

```diff
+ boolean lambda$findNearbyHivesWithSpace$1(Bee,BlockPos)
- double lambda$findNearbyHivesWithSpace$1(BlockPos,BlockPos)
+ double lambda$findNearbyHivesWithSpace$2(BlockPos,BlockPos)
+ void <init>(Bee,Bee$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeePollinateGoal
</summary>

```diff
+ boolean access$600(Bee$BeePollinateGoal)
+ void access$800(Bee$BeePollinateGoal)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Dolphin
</summary>

```diff
- Random access$000(Dolphin)
+ Random access$300(Dolphin)
+ TargetingConditions access$400()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
+ boolean access$000(Ocelot)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Panda$Gene
</summary>

```diff
+ Panda$Gene access$000(Panda$Gene,Panda$Gene)
- Panda$Gene[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
+ Map access$000()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Pufferfish
</summary>

```diff
+ int access$002(Pufferfish,int)
+ int access$102(Pufferfish,int)
+ TargetingConditions access$200()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
+ boolean access$300(Rabbit)
+ int access$402(Rabbit,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
- boolean access$000(Squid)
+ boolean access$100(Squid)
- boolean canBeLeashed(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.TropicalFish$Pattern
</summary>

```diff
- TropicalFish$Pattern[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
+ BlockPos access$600(Turtle)
+ BlockPos access$700(Turtle)
+ boolean access$1300(Turtle)
+ boolean access$1400(Turtle)
+ int access$1000(Turtle)
+ int access$1008(Turtle)
- Random access$000(Turtle)
- Random access$100(Turtle)
+ Random access$1200(Turtle)
+ Random access$300(Turtle)
+ void access$1100(Turtle,boolean)
+ void access$400(Turtle,BlockPos)
+ void access$500(Turtle,boolean)
+ void access$800(Turtle,boolean)
+ void access$900(Turtle,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
</summary>

```diff
+ void <init>(Goat$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
</summary>

```diff
+ void <init>(Evoker,Evoker$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
</summary>

```diff
+ void <init>(Evoker,Evoker$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Guardian
</summary>

```diff
+ void access$000(Guardian,int)
+ void access$100(Guardian,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
</summary>

```diff
+ void <init>(Phantom,Phantom$1)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ravager
</summary>

```diff
+ boolean canSee(Entity)
- boolean hasLineOfSight(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
- boolean access$000(Slime)
+ boolean access$100(Slime)
+ float access$000(Slime)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.SpellcasterIllager
</summary>

```diff
- PathNavigation access$000(SpellcasterIllager)
+ PathNavigation access$200(SpellcasterIllager)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.ClickAction
</summary>

```diff
- ClickAction[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.GrindstoneMenu
</summary>

```diff
+ Container access$000(GrindstoneMenu)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.RecipeBookType
</summary>

```diff
- RecipeBookType[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorMaterials
</summary>

```diff
- ArmorMaterials[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.item.DiggerItem
</summary>

```diff
- boolean isCorrectToolForDrops(BlockState)
+ void <init>(float,float,Tier,Set,Item$Properties)
- void <init>(float,float,Tier,Tag,Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
+ boolean access$600(Item$Properties)
+ CreativeModeTab access$000(Item$Properties)
+ FoodProperties access$500(Item$Properties)
+ int access$300(Item$Properties)
+ int access$400(Item$Properties)
+ Item access$200(Item$Properties)
+ Rarity access$100(Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.Ingredient$ItemValue
</summary>

```diff
+ void <init>(ItemStack,Ingredient$1)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.RecipeManager
</summary>

```diff
+ Map lambda$null$10(RecipeType)
- Map lambda$replaceRecipes$10(RecipeType)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.UpgradeRecipe
</summary>

```diff
+ Ingredient access$000(UpgradeRecipe)
+ Ingredient access$100(UpgradeRecipe)
+ ItemStack access$200(UpgradeRecipe)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentCategory
</summary>

```diff
- EnchantmentCategory[] $values()
+ void <init>(String,int,EnchantmentCategory$1)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
</summary>

```diff
- ProtectionEnchantment$Type[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$Category
</summary>

```diff
- GameRules$Category[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$IntegerValue
</summary>

```diff
+ GameRules$Type access$100(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$Type
</summary>

```diff
+ BiConsumer access$300(GameRules$Type)
+ void <init>(Supplier,Function,BiConsumer,GameRules$VisitorCaller,GameRules$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.LightLayer
</summary>

```diff
- LightLayer[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner$SpawnState
</summary>

```diff
+ boolean access$300(NaturalSpawner$SpawnState,MobCategory)
+ boolean access$500(NaturalSpawner$SpawnState,EntityType,BlockPos,ChunkAccess)
+ void <init>(int,Object2IntOpenHashMap,PotentialCalculator,NaturalSpawner$1)
+ void access$400(NaturalSpawner$SpawnState,Mob,ChunkAccess)
```

</details>
<details>
<summary>
net.minecraft.world.level.StructureFeatureManager
</summary>

```diff
- boolean lambda$getStructureAt$3(BlockPos,StructurePiece)
+ boolean lambda$null$3(BlockPos,StructurePiece)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.AmbientMoodSettings
</summary>

```diff
+ Double lambda$null$3(AmbientMoodSettings)
- Double lambda$static$3(AmbientMoodSettings)
+ Integer lambda$null$1(AmbientMoodSettings)
+ Integer lambda$null$2(AmbientMoodSettings)
- Integer lambda$static$1(AmbientMoodSettings)
- Integer lambda$static$2(AmbientMoodSettings)
+ SoundEvent lambda$null$0(AmbientMoodSettings)
- SoundEvent lambda$static$0(AmbientMoodSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ Biome lambda$null$13(Biome$ClimateSettings,Biome$BiomeCategory,Float,Float,BiomeSpecialEffects)
- Biome lambda$static$13(Biome$ClimateSettings,Biome$BiomeCategory,Float,Float,BiomeSpecialEffects)
+ Biome$BiomeCategory lambda$null$1(Biome)
+ Biome$BiomeCategory lambda$null$9(Biome)
- Biome$BiomeCategory lambda$static$1(Biome)
- Biome$BiomeCategory lambda$static$9(Biome)
+ Biome$ClimateSettings lambda$null$0(Biome)
+ Biome$ClimateSettings lambda$null$8(Biome)
- Biome$ClimateSettings lambda$static$0(Biome)
- Biome$ClimateSettings lambda$static$8(Biome)
+ BiomeGenerationSettings lambda$null$5(Biome)
- BiomeGenerationSettings lambda$static$5(Biome)
+ BiomeSpecialEffects lambda$null$12(Biome)
+ BiomeSpecialEffects lambda$null$4(Biome)
- BiomeSpecialEffects lambda$static$12(Biome)
- BiomeSpecialEffects lambda$static$4(Biome)
+ Float lambda$null$10(Biome)
+ Float lambda$null$11(Biome)
+ Float lambda$null$2(Biome)
+ Float lambda$null$3(Biome)
- Float lambda$static$10(Biome)
- Float lambda$static$11(Biome)
- Float lambda$static$2(Biome)
- Float lambda$static$3(Biome)
- Long2FloatLinkedOpenHashMap lambda$new$16()
+ Long2FloatLinkedOpenHashMap lambda$null$16()
+ MobSpawnSettings lambda$null$6(Biome)
- MobSpawnSettings lambda$static$6(Biome)
+ PerlinSimplexNoise access$100()
+ void <init>(Biome$ClimateSettings,Biome$BiomeCategory,float,float,BiomeSpecialEffects,BiomeGenerationSettings,MobSpawnSettings,Biome$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome$ClimateParameters
</summary>

```diff
+ Float lambda$null$0(Biome$ClimateParameters)
+ Float lambda$null$1(Biome$ClimateParameters)
+ Float lambda$null$2(Biome$ClimateParameters)
+ Float lambda$null$3(Biome$ClimateParameters)
+ Float lambda$null$4(Biome$ClimateParameters)
- Float lambda$static$0(Biome$ClimateParameters)
- Float lambda$static$1(Biome$ClimateParameters)
- Float lambda$static$2(Biome$ClimateParameters)
- Float lambda$static$3(Biome$ClimateParameters)
- Float lambda$static$4(Biome$ClimateParameters)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome$Precipitation
</summary>

```diff
- Biome$Precipitation[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeGenerationSettings
</summary>

```diff
+ List lambda$null$3(BiomeGenerationSettings)
+ List lambda$null$4(BiomeGenerationSettings)
- List lambda$static$3(BiomeGenerationSettings)
- List lambda$static$4(BiomeGenerationSettings)
+ Map lambda$null$2(BiomeGenerationSettings)
- Map lambda$static$2(BiomeGenerationSettings)
+ Supplier lambda$null$1(BiomeGenerationSettings)
- Supplier lambda$static$1(BiomeGenerationSettings)
+ void <init>(Supplier,Map,List,List,BiomeGenerationSettings$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
</summary>

```diff
- FuzzyOffsetConstantColumnBiomeZoomer[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
</summary>

```diff
+ DataResult lambda$null$0(ResourceLocation)
+ DataResult lambda$null$1(ResourceLocation)
+ DataResult lambda$null$2(MultiNoiseBiomeSource$Preset)
- DataResult lambda$static$0(ResourceLocation)
- DataResult lambda$static$1(ResourceLocation)
- DataResult lambda$static$2(MultiNoiseBiomeSource$Preset)
+ void <init>(MultiNoiseBiomeSource$Preset,Registry,long,MultiNoiseBiomeSource$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.OverworldBiomeSource
</summary>

```diff
- Biome lambda$new$5(Registry,ResourceKey)
+ Biome lambda$null$5(Registry,ResourceKey)
+ Boolean lambda$null$1(OverworldBiomeSource)
+ Boolean lambda$null$2(OverworldBiomeSource)
- Boolean lambda$static$1(OverworldBiomeSource)
- Boolean lambda$static$2(OverworldBiomeSource)
+ Long lambda$null$0(OverworldBiomeSource)
- Long lambda$static$0(OverworldBiomeSource)
+ Registry lambda$null$3(OverworldBiomeSource)
- Registry lambda$static$3(OverworldBiomeSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ComposterBlock
</summary>

```diff
+ BlockState access$000(BlockState,LevelAccessor,BlockPos)
+ BlockState access$100(BlockState,LevelAccessor,BlockPos,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
</summary>

```diff
- DoubleBlockCombiner$BlockType[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PowderSnowBlock
</summary>

```diff
+ void spawnPowderSnowParticles(Level,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
</summary>

```diff
- PressurePlateBlock$Sensitivity[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BannerPattern
</summary>

```diff
- BannerPattern[] $values()
+ String access$000(BannerPattern)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BarrelBlockEntity
</summary>

```diff
+ void access$000(BarrelBlockEntity,BlockState,SoundEvent)
+ void access$100(BarrelBlockEntity,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.RailShape
</summary>

```diff
- RailShape[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.SculkSensorPhase
</summary>

```diff
- SculkSensorPhase[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.StairsShape
</summary>

```diff
- StairsShape[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.Tilt
</summary>

```diff
- Tilt[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.border.BorderStatus
</summary>

```diff
- BorderStatus[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
</summary>

```diff
+ CompletableFuture access$100(IOWorker$PendingStore)
+ CompoundTag access$000(IOWorker$PendingStore)
+ CompoundTag access$002(IOWorker$PendingStore,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.RegionFile
</summary>

```diff
+ RegionFileVersion access$000(RegionFile)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
+ void lambda$null$1(long)
- void lambda$readColumn$1(long)
```

</details>
<details>
<summary>
net.minecraft.world.level.entity.Visibility
</summary>

```diff
- Visibility[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.BlockPositionSource
</summary>

```diff
+ Optional access$000(BlockPositionSource)
+ Optional lambda$null$0(BlockPositionSource)
- Optional lambda$static$0(BlockPositionSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.EntityPositionSource
</summary>

```diff
+ int access$000(EntityPositionSource)
+ Integer lambda$null$0(EntityPositionSource)
- Integer lambda$static$0(EntityPositionSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus
</summary>

```diff
+ BlockState access$100(Aquifer$NoiseBasedAquifer$AquiferStatus)
+ int access$000(Aquifer$NoiseBasedAquifer$AquiferStatus)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Cavifier$QuantizedSpaghettiRarity
</summary>

```diff
+ double access$000(double)
+ double access$100(double)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Column$Line
</summary>

```diff
+ Column$Line access$000()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Carving
</summary>

```diff
- GenerationStep$Carving[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GeodeBlockSettings
</summary>

```diff
+ BlockStateProvider lambda$null$0(GeodeBlockSettings)
+ BlockStateProvider lambda$null$1(GeodeBlockSettings)
+ BlockStateProvider lambda$null$2(GeodeBlockSettings)
+ BlockStateProvider lambda$null$3(GeodeBlockSettings)
+ BlockStateProvider lambda$null$4(GeodeBlockSettings)
- BlockStateProvider lambda$static$0(GeodeBlockSettings)
- BlockStateProvider lambda$static$1(GeodeBlockSettings)
- BlockStateProvider lambda$static$2(GeodeBlockSettings)
- BlockStateProvider lambda$static$3(GeodeBlockSettings)
- BlockStateProvider lambda$static$4(GeodeBlockSettings)
+ List lambda$null$5(GeodeBlockSettings)
- List lambda$static$5(GeodeBlockSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GeodeLayerSettings
</summary>

```diff
+ Double lambda$null$0(GeodeLayerSettings)
+ Double lambda$null$1(GeodeLayerSettings)
+ Double lambda$null$2(GeodeLayerSettings)
+ Double lambda$null$3(GeodeLayerSettings)
- Double lambda$static$0(GeodeLayerSettings)
- Double lambda$static$1(GeodeLayerSettings)
- Double lambda$static$2(GeodeLayerSettings)
- Double lambda$static$3(GeodeLayerSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Heightmap$Types
</summary>

```diff
- Heightmap$Types[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ BiomeSource lambda$null$0(NoiseBasedChunkGenerator)
- BiomeSource lambda$static$0(NoiseBasedChunkGenerator)
+ int access$000(NoiseBasedChunkGenerator)
+ int access$100(NoiseBasedChunkGenerator)
+ int access$200(NoiseBasedChunkGenerator)
+ Long lambda$null$1(NoiseBasedChunkGenerator)
- Long lambda$static$1(NoiseBasedChunkGenerator)
+ NoodleCavifier access$400(NoiseBasedChunkGenerator)
+ OreVeinifier access$300(NoiseBasedChunkGenerator)
+ Supplier lambda$null$2(NoiseBasedChunkGenerator)
- Supplier lambda$static$2(NoiseBasedChunkGenerator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.WorldGenSettings
</summary>

```diff
+ Optional lambda$null$0(WorldGenSettings)
- Optional lambda$static$0(WorldGenSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
</summary>

```diff
+ Float lambda$null$4(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ Float lambda$null$5(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Float lambda$static$4(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Float lambda$static$5(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$0(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$1(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ FloatProvider lambda$null$3(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$0(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$1(CanyonCarverConfiguration$CanyonShapeConfiguration)
- FloatProvider lambda$static$3(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ Integer lambda$null$2(CanyonCarverConfiguration$CanyonShapeConfiguration)
- Integer lambda$static$2(CanyonCarverConfiguration$CanyonShapeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarverConfiguration
</summary>

```diff
+ Boolean lambda$null$4(CarverConfiguration)
- Boolean lambda$static$4(CarverConfiguration)
+ CarverDebugSettings lambda$null$5(CarverConfiguration)
- CarverDebugSettings lambda$static$5(CarverConfiguration)
+ Float lambda$null$0(CarverConfiguration)
- Float lambda$static$0(CarverConfiguration)
+ FloatProvider lambda$null$2(CarverConfiguration)
- FloatProvider lambda$static$2(CarverConfiguration)
+ HeightProvider lambda$null$1(CarverConfiguration)
- HeightProvider lambda$static$1(CarverConfiguration)
+ VerticalAnchor lambda$null$3(CarverConfiguration)
- VerticalAnchor lambda$static$3(CarverConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
</summary>

```diff
+ Integer lambda$null$4(FossilFeatureConfiguration)
- Integer lambda$static$4(FossilFeatureConfiguration)
+ List lambda$null$0(FossilFeatureConfiguration)
+ List lambda$null$1(FossilFeatureConfiguration)
- List lambda$static$0(FossilFeatureConfiguration)
- List lambda$static$1(FossilFeatureConfiguration)
+ Supplier lambda$null$2(FossilFeatureConfiguration)
+ Supplier lambda$null$3(FossilFeatureConfiguration)
- Supplier lambda$static$2(FossilFeatureConfiguration)
- Supplier lambda$static$3(FossilFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
</summary>

```diff
+ BlockState lambda$null$0(HugeFungusConfiguration)
+ BlockState lambda$null$1(HugeFungusConfiguration)
+ BlockState lambda$null$2(HugeFungusConfiguration)
+ BlockState lambda$null$3(HugeFungusConfiguration)
- BlockState lambda$static$0(HugeFungusConfiguration)
- BlockState lambda$static$1(HugeFungusConfiguration)
- BlockState lambda$static$2(HugeFungusConfiguration)
- BlockState lambda$static$3(HugeFungusConfiguration)
+ Boolean lambda$null$4(HugeFungusConfiguration)
- Boolean lambda$static$4(HugeFungusConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature
</summary>

```diff
+ boolean access$100(JigsawFeature)
+ boolean access$200(JigsawFeature)
+ int access$000(JigsawFeature)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
</summary>

```diff
+ void <init>(SpikeFeature$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
</summary>

```diff
+ Float lambda$null$1(WeightedConfiguredFeature)
- Float lambda$static$1(WeightedConfiguredFeature)
+ Supplier lambda$null$0(WeightedConfiguredFeature)
- Supplier lambda$static$0(WeightedConfiguredFeature)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
</summary>

```diff
+ BlockState lambda$null$0(DiskConfiguration)
- BlockState lambda$static$0(DiskConfiguration)
+ Integer lambda$null$2(DiskConfiguration)
- Integer lambda$static$2(DiskConfiguration)
+ IntProvider lambda$null$1(DiskConfiguration)
- IntProvider lambda$static$1(DiskConfiguration)
+ List lambda$null$3(DiskConfiguration)
- List lambda$static$3(DiskConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
</summary>

```diff
+ Boolean lambda$null$1(EndGatewayConfiguration)
- Boolean lambda$static$1(EndGatewayConfiguration)
+ Optional lambda$null$0(EndGatewayConfiguration)
- Optional lambda$static$0(EndGatewayConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
</summary>

```diff
+ Boolean lambda$null$5(GeodeConfiguration)
- Boolean lambda$static$5(GeodeConfiguration)
+ Double lambda$null$11(GeodeConfiguration)
+ Double lambda$null$3(GeodeConfiguration)
+ Double lambda$null$4(GeodeConfiguration)
- Double lambda$static$11(GeodeConfiguration)
- Double lambda$static$3(GeodeConfiguration)
- Double lambda$static$4(GeodeConfiguration)
+ GeodeBlockSettings lambda$null$0(GeodeConfiguration)
- GeodeBlockSettings lambda$static$0(GeodeConfiguration)
+ GeodeCrackSettings lambda$null$2(GeodeConfiguration)
- GeodeCrackSettings lambda$static$2(GeodeConfiguration)
+ GeodeLayerSettings lambda$null$1(GeodeConfiguration)
- GeodeLayerSettings lambda$static$1(GeodeConfiguration)
+ Integer lambda$null$10(GeodeConfiguration)
+ Integer lambda$null$12(GeodeConfiguration)
+ Integer lambda$null$9(GeodeConfiguration)
- Integer lambda$static$10(GeodeConfiguration)
- Integer lambda$static$12(GeodeConfiguration)
- Integer lambda$static$9(GeodeConfiguration)
+ IntProvider lambda$null$6(GeodeConfiguration)
+ IntProvider lambda$null$7(GeodeConfiguration)
+ IntProvider lambda$null$8(GeodeConfiguration)
- IntProvider lambda$static$6(GeodeConfiguration)
- IntProvider lambda$static$7(GeodeConfiguration)
- IntProvider lambda$static$8(GeodeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GrowingPlantConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$2(GrowingPlantConfiguration)
+ BlockStateProvider lambda$null$3(GrowingPlantConfiguration)
- BlockStateProvider lambda$static$2(GrowingPlantConfiguration)
- BlockStateProvider lambda$static$3(GrowingPlantConfiguration)
+ Boolean lambda$null$4(GrowingPlantConfiguration)
- Boolean lambda$static$4(GrowingPlantConfiguration)
+ Direction lambda$null$1(GrowingPlantConfiguration)
- Direction lambda$static$1(GrowingPlantConfiguration)
+ SimpleWeightedRandomList lambda$null$0(GrowingPlantConfiguration)
- SimpleWeightedRandomList lambda$static$0(GrowingPlantConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$0(HugeMushroomFeatureConfiguration)
+ BlockStateProvider lambda$null$1(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$static$0(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$static$1(HugeMushroomFeatureConfiguration)
+ Integer lambda$null$2(HugeMushroomFeatureConfiguration)
- Integer lambda$static$2(HugeMushroomFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
</summary>

```diff
+ Float lambda$null$3(LargeDripstoneConfiguration)
+ Float lambda$null$8(LargeDripstoneConfiguration)
- Float lambda$static$3(LargeDripstoneConfiguration)
- Float lambda$static$8(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$2(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$4(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$5(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- FloatProvider lambda$static$2(LargeDripstoneConfiguration)
- FloatProvider lambda$static$4(LargeDripstoneConfiguration)
- FloatProvider lambda$static$5(LargeDripstoneConfiguration)
- FloatProvider lambda$static$6(LargeDripstoneConfiguration)
+ Integer lambda$null$0(LargeDripstoneConfiguration)
+ Integer lambda$null$7(LargeDripstoneConfiguration)
- Integer lambda$static$0(LargeDripstoneConfiguration)
- Integer lambda$static$7(LargeDripstoneConfiguration)
+ IntProvider lambda$null$1(LargeDripstoneConfiguration)
- IntProvider lambda$static$1(LargeDripstoneConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
</summary>

```diff
+ Float lambda$null$0(MineshaftConfiguration)
- Float lambda$static$0(MineshaftConfiguration)
+ MineshaftFeature$Type lambda$null$1(MineshaftConfiguration)
- MineshaftFeature$Type lambda$static$1(MineshaftConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
</summary>

```diff
+ Float lambda$null$1(OceanRuinConfiguration)
+ Float lambda$null$2(OceanRuinConfiguration)
- Float lambda$static$1(OceanRuinConfiguration)
- Float lambda$static$2(OceanRuinConfiguration)
+ OceanRuinFeature$Type lambda$null$0(OceanRuinConfiguration)
- OceanRuinFeature$Type lambda$static$0(OceanRuinConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
</summary>

```diff
+ List lambda$null$0(ReplaceBlockConfiguration)
- List lambda$static$0(ReplaceBlockConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$4(RootSystemConfiguration)
+ BlockStateProvider lambda$null$9(RootSystemConfiguration)
- BlockStateProvider lambda$static$4(RootSystemConfiguration)
- BlockStateProvider lambda$static$9(RootSystemConfiguration)
+ Integer lambda$null$1(RootSystemConfiguration)
+ Integer lambda$null$10(RootSystemConfiguration)
+ Integer lambda$null$11(RootSystemConfiguration)
+ Integer lambda$null$2(RootSystemConfiguration)
+ Integer lambda$null$5(RootSystemConfiguration)
+ Integer lambda$null$6(RootSystemConfiguration)
+ Integer lambda$null$7(RootSystemConfiguration)
+ Integer lambda$null$8(RootSystemConfiguration)
- Integer lambda$static$1(RootSystemConfiguration)
- Integer lambda$static$10(RootSystemConfiguration)
- Integer lambda$static$11(RootSystemConfiguration)
- Integer lambda$static$2(RootSystemConfiguration)
- Integer lambda$static$5(RootSystemConfiguration)
- Integer lambda$static$6(RootSystemConfiguration)
- Integer lambda$static$7(RootSystemConfiguration)
- Integer lambda$static$8(RootSystemConfiguration)
+ ResourceLocation lambda$null$3(RootSystemConfiguration)
- ResourceLocation lambda$static$3(RootSystemConfiguration)
+ Supplier lambda$null$0(RootSystemConfiguration)
- Supplier lambda$static$0(RootSystemConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
</summary>

```diff
+ Boolean lambda$null$0(SpikeConfiguration)
- Boolean lambda$static$0(SpikeConfiguration)
+ List lambda$null$1(SpikeConfiguration)
- List lambda$static$1(SpikeConfiguration)
+ Optional lambda$null$2(SpikeConfiguration)
- Optional lambda$static$2(SpikeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
</summary>

```diff
+ BlockStateProvider lambda$null$0(TreeConfiguration)
+ BlockStateProvider lambda$null$2(TreeConfiguration)
+ BlockStateProvider lambda$null$4(TreeConfiguration)
- BlockStateProvider lambda$static$0(TreeConfiguration)
- BlockStateProvider lambda$static$2(TreeConfiguration)
- BlockStateProvider lambda$static$4(TreeConfiguration)
+ Boolean lambda$null$7(TreeConfiguration)
+ Boolean lambda$null$8(TreeConfiguration)
- Boolean lambda$static$7(TreeConfiguration)
- Boolean lambda$static$8(TreeConfiguration)
+ FeatureSize lambda$null$5(TreeConfiguration)
- FeatureSize lambda$static$5(TreeConfiguration)
+ FoliagePlacer lambda$null$3(TreeConfiguration)
- FoliagePlacer lambda$static$3(TreeConfiguration)
+ List lambda$null$6(TreeConfiguration)
- List lambda$static$6(TreeConfiguration)
+ TrunkPlacer lambda$null$1(TreeConfiguration)
- TrunkPlacer lambda$static$1(TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
</summary>

```diff
+ Float lambda$null$2(UnderwaterMagmaConfiguration)
- Float lambda$static$2(UnderwaterMagmaConfiguration)
+ Integer lambda$null$0(UnderwaterMagmaConfiguration)
+ Integer lambda$null$1(UnderwaterMagmaConfiguration)
- Integer lambda$static$0(UnderwaterMagmaConfiguration)
- Integer lambda$static$1(UnderwaterMagmaConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
</summary>

```diff
+ Integer lambda$null$0(TwoLayersFeatureSize)
+ Integer lambda$null$1(TwoLayersFeatureSize)
+ Integer lambda$null$2(TwoLayersFeatureSize)
- Integer lambda$static$0(TwoLayersFeatureSize)
- Integer lambda$static$1(TwoLayersFeatureSize)
- Integer lambda$static$2(TwoLayersFeatureSize)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
</summary>

```diff
+ Integer lambda$null$0(MegaJungleFoliagePlacer)
- Integer lambda$static$0(MegaJungleFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
</summary>

```diff
+ IntProvider lambda$null$0(PineFoliagePlacer)
- IntProvider lambda$static$0(PineFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
</summary>

```diff
+ IntProvider lambda$null$0(SpruceFoliagePlacer)
- IntProvider lambda$static$0(SpruceFoliagePlacer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
</summary>

```diff
+ void <init>(JunglePyramidPiece$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces
</summary>

```diff
+ Logger access$000()
+ MineShaftPieces$MineShaftPiece access$100(StructurePiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
</summary>

```diff
+ void <init>(OceanMonumentPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
</summary>

```diff
+ boolean access$100(OceanMonumentPieces$RoomDefinition)
+ boolean access$102(OceanMonumentPieces$RoomDefinition,boolean)
+ boolean access$902(OceanMonumentPieces$RoomDefinition,boolean)
+ boolean[] access$1100(OceanMonumentPieces$RoomDefinition)
+ int access$000(OceanMonumentPieces$RoomDefinition)
+ OceanMonumentPieces$RoomDefinition[] access$1000(OceanMonumentPieces$RoomDefinition)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
</summary>

```diff
- RuinedPortalPiece$VerticalPlacement[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.ShipwreckPieces
</summary>

```diff
+ BlockPos access$000()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces
</summary>

```diff
+ Class access$102(Class)
+ StrongholdPieces$SmoothStoneSelector access$200()
+ StructurePiece access$000(StrongholdPieces$StartPiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
</summary>

```diff
+ void <init>(StrongholdPieces$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
</summary>

```diff
- StrongholdPieces$StrongholdPiece$SmallDoorType[] $values()
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
</summary>

```diff
+ Packet access$200(MapItemSavedData$HoldingPlayer,int)
+ void <init>(MapItemSavedData,Player,MapItemSavedData$1)
+ void access$300(MapItemSavedData$HoldingPlayer,int,int)
+ void access$400(MapItemSavedData$HoldingPlayer)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.IntRange
</summary>

```diff
+ NumberProvider access$100(IntRange)
+ NumberProvider access$200(IntRange)
+ void <init>(NumberProvider,NumberProvider,IntRange$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootPool
</summary>

```diff
+ LootItemCondition[] access$400(LootPool)
+ LootItemFunction[] access$500(LootPool)
+ LootPoolEntryContainer[] access$300(LootPool)
+ NumberProvider access$100(LootPool)
+ NumberProvider access$200(LootPool)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],NumberProvider,NumberProvider,LootPool$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.EmptyLootItem
</summary>

```diff
+ void <init>(int,int,LootItemCondition[],LootItemFunction[],EmptyLootItem$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
</summary>

```diff
+ BiFunction access$000(LootPoolSingletonContainer)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
</summary>

```diff
+ void <init>(LootItemCondition[],ApplyExplosionDecay$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
</summary>

```diff
+ void <init>(String,String,CopyNbtFunction$MergeStrategy,CopyNbtFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
</summary>

```diff
- void lambda$merge$0(Tag,Tag)
+ void lambda$null$0(Tag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
</summary>

```diff
+ List access$100(EnchantRandomlyFunction)
+ void <init>(LootItemCondition[],Collection,EnchantRandomlyFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
</summary>

```diff
+ boolean access$500(ExplorationMapFunction)
+ byte access$300(ExplorationMapFunction)
+ int access$400(ExplorationMapFunction)
+ Logger access$600()
+ MapDecoration$Type access$200(ExplorationMapFunction)
+ StructureFeature access$100(ExplorationMapFunction)
+ void <init>(LootItemCondition[],StructureFeature,MapDecoration$Type,byte,int,boolean,ExplorationMapFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
</summary>

```diff
+ boolean access$200(LootingEnchantFunction)
+ int access$300(LootingEnchantFunction)
+ NumberProvider access$100(LootingEnchantFunction)
+ void <init>(LootItemCondition[],NumberProvider,int,LootingEnchantFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
</summary>

```diff
+ void <init>(boolean,SetBannerPatternFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetContainerContents
</summary>

```diff
+ List access$100(SetContainerContents)
+ void <init>(LootItemCondition[],List,SetContainerContents$1)
+ void lambda$null$0(NonNullList,LootContext,LootPoolEntry)
- void lambda$run$0(NonNullList,LootContext,LootPoolEntry)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
</summary>

```diff
+ boolean access$100(SetItemDamageFunction)
+ NumberProvider access$000(SetItemDamageFunction)
+ void <init>(LootItemCondition[],NumberProvider,boolean,SetItemDamageFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
</summary>

```diff
+ void <init>(LootItemCondition[],SmeltItemFunction$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
</summary>

```diff
+ LootItemCondition[] access$100(AlternativeLootItemCondition)
+ void <init>(LootItemCondition[],AlternativeLootItemCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
</summary>

```diff
+ LootContext$EntityTarget access$200(EntityHasScoreCondition)
+ Map access$100(EntityHasScoreCondition)
+ void <init>(Map,LootContext$EntityTarget,EntityHasScoreCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
</summary>

```diff
+ EntityPredicate access$000(LootItemEntityPropertyCondition)
+ LootContext$EntityTarget access$100(LootItemEntityPropertyCondition)
+ void <init>(EntityPredicate,LootContext$EntityTarget,LootItemEntityPropertyCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
</summary>

```diff
+ float access$000(LootItemRandomChanceWithLootingCondition)
+ float access$100(LootItemRandomChanceWithLootingCondition)
+ void <init>(float,float,LootItemRandomChanceWithLootingCondition$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
</summary>

```diff
+ ResourceLocation access$000(StorageNbtProvider)
+ void <init>(ResourceLocation,StorageNbtProvider$1)
```

</details>
<details>
<summary>
net.minecraft.world.level.timers.TimerQueue$Event
</summary>

```diff
+ void <init>(long,UnsignedLong,String,TimerCallback,TimerQueue$1)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
- boolean lambda$joinIsNotEmpty$1(BooleanOp,DiscreteVoxelShape,int,int,DiscreteVoxelShape,int,int,int,int,int)
- boolean lambda$joinIsNotEmpty$2(IndexMerger,BooleanOp,DiscreteVoxelShape,int,DiscreteVoxelShape,int,int,int,int)
+ boolean lambda$null$1(BooleanOp,DiscreteVoxelShape,int,int,DiscreteVoxelShape,int,int,int,int,int)
+ boolean lambda$null$2(IndexMerger,BooleanOp,DiscreteVoxelShape,int,DiscreteVoxelShape,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.scores.Team$CollisionRule
</summary>

```diff
- Team$CollisionRule[] $values()
```

</details>
</details>
<hr/>