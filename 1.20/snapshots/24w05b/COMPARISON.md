## Comparison with [24w05a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w05a)

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
<table><tr><th></th><th align="left">24w05a</th><th>24w05b</th></tr><tr><td>World version</td><td><pre>3809</pre></td><td><pre>3811</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741997</pre></td><td><pre>1073741999</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
armor_material
</summary>

```diff
- minecraft:chain
+ minecraft:chainmail
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/armor_material.json
</summary>

```diff
- minecraft:chain
+ minecraft:chainmail
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
XXX.protocol.game.ClientboundUpdateMobEffectPacket +1M -1M | +1P -1P
```
```
XXX.minecraft.util.ExtraCodecs +77M -75M | +1P
```
```
XXX.minecraft.util.ExtraCodecs$RecursiveMapCodec +1M -1M | +1P
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
</summary>

```diff
+ byte getEffectAmplifier()
- int getEffectAmplifier()
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
+ App lambda$intervalCodec$19(Codec,String,String,RecordCodecBuilder$Instance)
- App lambda$intervalCodec$21(Codec,String,String,RecordCodecBuilder$Instance)
+ App lambda$static$69(RecordCodecBuilder$Instance)
- App lambda$static$71(RecordCodecBuilder$Instance)
+ App lambda$static$75(RecordCodecBuilder$Instance)
- App lambda$static$77(RecordCodecBuilder$Instance)
+ App lambda$static$78(RecordCodecBuilder$Instance)
- App lambda$static$80(RecordCodecBuilder$Instance)
+ BitSet lambda$static$65(LongStream)
- BitSet lambda$static$67(LongStream)
+ Codec lambda$lazyInitializedCodec$48(Supplier,Codec)
- Codec lambda$lazyInitializedCodec$50(Supplier,Codec)
+ DataResult lambda$ensureHomogenous$52(Function,Collection)
- DataResult lambda$ensureHomogenous$54(Function,Collection)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$42(float,float,Function,Float)
- DataResult lambda$floatRangeMinExclusiveWithMessage$44(float,float,Function,Float)
+ DataResult lambda$idResolverCodec$26(Integer)
+ DataResult lambda$idResolverCodec$27(IntFunction,Integer)
- DataResult lambda$idResolverCodec$28(Integer)
- DataResult lambda$idResolverCodec$29(IntFunction,Integer)
+ DataResult lambda$idResolverCodec$29(ToIntFunction,int,Object)
- DataResult lambda$idResolverCodec$31(ToIntFunction,int,Object)
+ DataResult lambda$intervalCodec$16(BiFunction,List)
+ DataResult lambda$intervalCodec$17(BiFunction,List)
- DataResult lambda$intervalCodec$18(BiFunction,List)
- DataResult lambda$intervalCodec$19(BiFunction,List)
+ DataResult lambda$intervalCodec$20(BiFunction,Pair)
+ DataResult lambda$intervalCodec$22(BiFunction,Object)
- DataResult lambda$intervalCodec$22(BiFunction,Pair)
+ DataResult lambda$intervalCodec$23(BiFunction,Either)
- DataResult lambda$intervalCodec$24(BiFunction,Object)
- DataResult lambda$intervalCodec$25(BiFunction,Either)
+ DataResult lambda$intRangeWithMessage$37(int,int,Function,Integer)
- DataResult lambda$intRangeWithMessage$39(int,int,Function,Integer)
+ DataResult lambda$nonEmptyHolderSet$47(HolderSet)
- DataResult lambda$nonEmptyHolderSet$49(HolderSet)
+ DataResult lambda$nonEmptyList$45(List)
- DataResult lambda$nonEmptyList$47(List)
+ DataResult lambda$sizeLimitedString$85(int,int,String)
- DataResult lambda$sizeLimitedString$87(int,int,String)
- DataResult lambda$static$17(Integer)
+ DataResult lambda$static$54(String)
- DataResult lambda$static$56(String)
+ DataResult lambda$static$57(String)
- DataResult lambda$static$61(String)
+ DataResult lambda$static$62(String)
- DataResult lambda$static$64(String)
+ DataResult lambda$static$80(String)
- DataResult lambda$static$84(String)
+ DataResult lambda$static$87(String)
- DataResult lambda$static$89(String)
+ DataResult lambda$stringResolverCodec$31(String)
+ DataResult lambda$stringResolverCodec$32(Function,String)
- DataResult lambda$stringResolverCodec$33(String)
- DataResult lambda$stringResolverCodec$34(Function,String)
+ DataResult lambda$stringResolverCodec$34(Object)
+ DataResult lambda$stringResolverCodec$35(Function,Object)
- DataResult lambda$stringResolverCodec$36(Object)
- DataResult lambda$stringResolverCodec$37(Function,Object)
+ DataResult lambda$temporalCodec$55(DateTimeFormatter,String)
- DataResult lambda$temporalCodec$57(DateTimeFormatter,String)
+ Either lambda$intervalCodec$24(Function,Function,Object)
- Either lambda$intervalCodec$26(Function,Function,Object)
+ Either lambda$static$74(PropertyMap)
- Either lambda$static$76(PropertyMap)
+ ExtraCodecs$TagOrElementLocation lambda$static$60(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$61(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$62(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$63(ResourceLocation)
+ GameProfile lambda$static$77(GameProfile,PropertyMap)
- GameProfile lambda$static$79(GameProfile,PropertyMap)
+ List lambda$intervalCodec$18(Function,Function,Object)
- List lambda$intervalCodec$20(Function,Function,Object)
+ LongStream lambda$static$66(BitSet)
- LongStream lambda$static$68(BitSet)
+ MapCodec recursiveMap(Function)
- MapCodec recursiveMap(String,Function)
+ Object lambda$strictOptionalField$49(Object,Optional)
- Object lambda$strictOptionalField$51(Object,Optional)
+ Object lambda$withAlternative$88(Object)
+ Object lambda$withAlternative$89(Object)
+ Object lambda$withAlternative$90(Either)
- Object lambda$withAlternative$90(Object)
- Object lambda$withAlternative$92(Either)
+ Object lambda$withAlternative$92(Function,Either)
- Object lambda$withAlternative$93(Object)
- Object lambda$withAlternative$94(Function,Either)
+ Optional lambda$static$64(OptionalLong)
- Optional lambda$static$66(OptionalLong)
+ Optional lambda$static$67(Property)
- Optional lambda$static$69(Property)
+ Optional lambda$strictOptionalField$50(Object,Object)
- Optional lambda$strictOptionalField$52(Object,Object)
+ OptionalLong lambda$static$63(Optional)
- OptionalLong lambda$static$65(Optional)
+ Pair lambda$intervalCodec$21(Function,Function,Object)
- Pair lambda$intervalCodec$23(Function,Function,Object)
+ Property lambda$static$68(String,String,Optional)
- Property lambda$static$70(String,String,Optional)
+ PropertyMap lambda$static$73(Either)
- PropertyMap lambda$static$75(Either)
+ String lambda$ensureHomogenous$51(Object,Object,Object)
- String lambda$ensureHomogenous$53(Object,Object,Object)
+ String lambda$floatRangeMinExclusiveWithMessage$41(Function,Float)
- String lambda$floatRangeMinExclusiveWithMessage$43(Function,Float)
+ String lambda$idResolverCodec$25(Integer)
- String lambda$idResolverCodec$27(Integer)
+ String lambda$idResolverCodec$28(Object)
- String lambda$idResolverCodec$30(Object)
+ String lambda$intRange$40(int,int,Integer)
- String lambda$intRange$42(int,int,Integer)
+ String lambda$intRangeWithMessage$36(Function,Integer)
- String lambda$intRangeWithMessage$38(Function,Integer)
+ String lambda$nonEmptyHolderSet$46()
- String lambda$nonEmptyHolderSet$48()
+ String lambda$nonEmptyList$44()
- String lambda$nonEmptyList$46()
+ String lambda$sizeLimitedString$83(String,int,int,int)
+ String lambda$sizeLimitedString$84(String,int,int,int)
- String lambda$sizeLimitedString$85(String,int,int,int)
- String lambda$sizeLimitedString$86(String,int,int,int)
- String lambda$static$16(Integer)
+ String lambda$static$38(Integer)
+ String lambda$static$39(Integer)
- String lambda$static$40(Integer)
- String lambda$static$41(Integer)
+ String lambda$static$43(Float)
- String lambda$static$45(Float)
+ String lambda$static$53(String,PatternSyntaxException)
- String lambda$static$55(String,PatternSyntaxException)
+ String lambda$static$56()
- String lambda$static$58()
+ String lambda$static$58(byte[])
- String lambda$static$60(byte[])
+ String lambda$static$79()
- String lambda$static$81()
+ String lambda$static$81(String)
- String lambda$static$83(String)
+ String lambda$static$86(String)
- String lambda$static$88(String)
+ String lambda$stringResolverCodec$30(String)
- String lambda$stringResolverCodec$32(String)
+ String lambda$stringResolverCodec$33(Object)
- String lambda$stringResolverCodec$35(Object)
+ void lambda$static$70(PropertyMap,String,List)
+ void lambda$static$71(PropertyMap,Map)
+ void lambda$static$72(PropertyMap,List)
- void lambda$static$72(PropertyMap,String,List)
- void lambda$static$73(PropertyMap,Map)
- void lambda$static$74(PropertyMap,List)
+ void lambda$static$76(GameProfile,String,Property)
- void lambda$static$78(GameProfile,String,Property)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs$RecursiveMapCodec
</summary>

```diff
+ void <init>(Function)
- void <init>(String,Function)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +1M -1M | +1P -1P
```
```
XXX.world.effect.MobEffectInstance +2P
```
```
XXX.world.effect.MobEffectInstance$Details -1P
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
</summary>

```diff
+ byte getEffectAmplifier()
- int getEffectAmplifier()
```

</details>
</details>
<hr/>