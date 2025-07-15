## Comparison with [1.21.2-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.2-pre3)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.2-pre3</th><th>1.21.2-pre4</th></tr><tr><td>World version</td><td><pre>4075</pre></td><td><pre>4076</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742039</pre></td><td><pre>1073742040</pre></td></tr></table>
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
XXX.level.block.HoneyBlock +2M
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HoneyBlock
</summary>

```diff
- double getNewDeltaY(double)
- double getOldDeltaY(double)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.screens.recipebook.RecipeBookComponent +5M -5M
```
```
XXX.renderer.entity.WanderingTraderRenderer -2M
```
```
XXX.level.block.HoneyBlock +2M
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
</summary>

```diff
- boolean lambda$updateCollections$2(RecipeCollection)
- boolean lambda$updateCollections$3(ObjectSet,RecipeCollection)
+ boolean lambda$updateCollections$3(RecipeCollection)
+ boolean lambda$updateCollections$4(ObjectSet,RecipeCollection)
- boolean lambda$updateCollections$4(RecipeCollection)
+ boolean lambda$updateCollections$5(RecipeCollection)
+ void lambda$updateCollections$2(RecipeCollection)
- void lambda$updateNarration$5(List,AbstractWidget)
+ void lambda$updateNarration$6(List,AbstractWidget)
- void selectMatchingRecipes()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.WanderingTraderRenderer
</summary>

```diff
+ void scale(LivingEntityRenderState,PoseStack)
+ void scale(VillagerRenderState,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HoneyBlock
</summary>

```diff
- double getNewDeltaY(double)
- double getOldDeltaY(double)
```

</details>
</details>
<hr/>