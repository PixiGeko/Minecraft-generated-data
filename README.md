<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 24w05b ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>24w05b</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2024-02-01T12:55:14+00:00</td></tr>
<tr><th>SHA1</th><td>0e4dc4668ee5f58fb46ef2781db229f284aa8dd9</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/0e4dc4668ee5f58fb46ef2781db229f284aa8dd9/24w05b.json">https://piston-meta.mojang.com/v1/packages/0e4dc4668ee5f58fb46ef2781db229f284aa8dd9/24w05b.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/c5938a1ede1ee4cb5d9105500e3decf06e5ec55f/12.json">https://piston-meta.mojang.com/v1/packages/c5938a1ede1ee4cb5d9105500e3decf06e5ec55f/12.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/189526bf25c06f7c0071aa637bc5f3668a6457d4/server.jar">https://piston-data.mojang.com/v1/objects/189526bf25c06f7c0071aa637bc5f3668a6457d4/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/68fab90ead90da057ffb7f6cd188b613327073fb/server.txt">https://piston-data.mojang.com/v1/objects/68fab90ead90da057ffb7f6cd188b613327073fb/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/9c02be7e088e9af9f6fedf4e86e86b4fe8a9bdfe/client.jar">https://piston-data.mojang.com/v1/objects/9c02be7e088e9af9f6fedf4e86e86b4fe8a9bdfe/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/722acd6fbe9de67c767f5895b2e0de824a4884cf/client.txt">https://piston-data.mojang.com/v1/objects/722acd6fbe9de67c767f5895b2e0de824a4884cf/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/24w05a">24w05a</a>

# Mappings

### Client




<details><summary>net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket</summary>

```diff
- byte getEffectAmplifier()
+ int getEffectAmplifier()
```

</details>


### Server




<details><summary>net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket</summary>

```diff
- byte getEffectAmplifier()
+ int getEffectAmplifier()
```

</details>


<details><summary>net.minecraft.util.ExtraCodecs</summary>

```diff
- App lambda$intervalCodec$19(Codec,String,String,RecordCodecBuilder$Instance)
+ App lambda$intervalCodec$21(Codec,String,String,RecordCodecBuilder$Instance)
- App lambda$static$69(RecordCodecBuilder$Instance)
+ App lambda$static$71(RecordCodecBuilder$Instance)
- App lambda$static$75(RecordCodecBuilder$Instance)
+ App lambda$static$77(RecordCodecBuilder$Instance)
- App lambda$static$78(RecordCodecBuilder$Instance)
+ App lambda$static$80(RecordCodecBuilder$Instance)
- BitSet lambda$static$65(LongStream)
+ BitSet lambda$static$67(LongStream)
- Codec lambda$lazyInitializedCodec$48(Supplier,Codec)
+ Codec lambda$lazyInitializedCodec$50(Supplier,Codec)
- DataResult lambda$ensureHomogenous$52(Function,Collection)
+ DataResult lambda$ensureHomogenous$54(Function,Collection)
- DataResult lambda$floatRangeMinExclusiveWithMessage$42(float,float,Function,Float)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$44(float,float,Function,Float)
- DataResult lambda$idResolverCodec$26(Integer)
- DataResult lambda$idResolverCodec$27(IntFunction,Integer)
+ DataResult lambda$idResolverCodec$28(Integer)
+ DataResult lambda$idResolverCodec$29(IntFunction,Integer)
- DataResult lambda$idResolverCodec$29(ToIntFunction,int,Object)
+ DataResult lambda$idResolverCodec$31(ToIntFunction,int,Object)
- DataResult lambda$intervalCodec$16(BiFunction,List)
- DataResult lambda$intervalCodec$17(BiFunction,List)
+ DataResult lambda$intervalCodec$18(BiFunction,List)
+ DataResult lambda$intervalCodec$19(BiFunction,List)
- DataResult lambda$intervalCodec$20(BiFunction,Pair)
- DataResult lambda$intervalCodec$22(BiFunction,Object)
+ DataResult lambda$intervalCodec$22(BiFunction,Pair)
- DataResult lambda$intervalCodec$23(BiFunction,Either)
+ DataResult lambda$intervalCodec$24(BiFunction,Object)
+ DataResult lambda$intervalCodec$25(BiFunction,Either)
- DataResult lambda$intRangeWithMessage$37(int,int,Function,Integer)
+ DataResult lambda$intRangeWithMessage$39(int,int,Function,Integer)
- DataResult lambda$nonEmptyHolderSet$47(HolderSet)
+ DataResult lambda$nonEmptyHolderSet$49(HolderSet)
- DataResult lambda$nonEmptyList$45(List)
+ DataResult lambda$nonEmptyList$47(List)
- DataResult lambda$sizeLimitedString$85(int,int,String)
+ DataResult lambda$sizeLimitedString$87(int,int,String)
+ DataResult lambda$static$17(Integer)
- DataResult lambda$static$54(String)
+ DataResult lambda$static$56(String)
- DataResult lambda$static$57(String)
+ DataResult lambda$static$61(String)
- DataResult lambda$static$62(String)
+ DataResult lambda$static$64(String)
- DataResult lambda$static$80(String)
+ DataResult lambda$static$84(String)
- DataResult lambda$static$87(String)
+ DataResult lambda$static$89(String)
- DataResult lambda$stringResolverCodec$31(String)
- DataResult lambda$stringResolverCodec$32(Function,String)
+ DataResult lambda$stringResolverCodec$33(String)
+ DataResult lambda$stringResolverCodec$34(Function,String)
- DataResult lambda$stringResolverCodec$34(Object)
- DataResult lambda$stringResolverCodec$35(Function,Object)
+ DataResult lambda$stringResolverCodec$36(Object)
+ DataResult lambda$stringResolverCodec$37(Function,Object)
- DataResult lambda$temporalCodec$55(DateTimeFormatter,String)
+ DataResult lambda$temporalCodec$57(DateTimeFormatter,String)
- Either lambda$intervalCodec$24(Function,Function,Object)
+ Either lambda$intervalCodec$26(Function,Function,Object)
- Either lambda$static$74(PropertyMap)
+ Either lambda$static$76(PropertyMap)
- ExtraCodecs$TagOrElementLocation lambda$static$60(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$61(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$62(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$63(ResourceLocation)
- GameProfile lambda$static$77(GameProfile,PropertyMap)
+ GameProfile lambda$static$79(GameProfile,PropertyMap)
- List lambda$intervalCodec$18(Function,Function,Object)
+ List lambda$intervalCodec$20(Function,Function,Object)
- LongStream lambda$static$66(BitSet)
+ LongStream lambda$static$68(BitSet)
- MapCodec recursiveMap(Function)
+ MapCodec recursiveMap(String,Function)
- Object lambda$strictOptionalField$49(Object,Optional)
+ Object lambda$strictOptionalField$51(Object,Optional)
- Object lambda$withAlternative$88(Object)
- Object lambda$withAlternative$89(Object)
- Object lambda$withAlternative$90(Either)
+ Object lambda$withAlternative$90(Object)
+ Object lambda$withAlternative$92(Either)
- Object lambda$withAlternative$92(Function,Either)
+ Object lambda$withAlternative$93(Object)
+ Object lambda$withAlternative$94(Function,Either)
- Optional lambda$static$64(OptionalLong)
+ Optional lambda$static$66(OptionalLong)
- Optional lambda$static$67(Property)
+ Optional lambda$static$69(Property)
- Optional lambda$strictOptionalField$50(Object,Object)
+ Optional lambda$strictOptionalField$52(Object,Object)
- OptionalLong lambda$static$63(Optional)
+ OptionalLong lambda$static$65(Optional)
- Pair lambda$intervalCodec$21(Function,Function,Object)
+ Pair lambda$intervalCodec$23(Function,Function,Object)
- Property lambda$static$68(String,String,Optional)
+ Property lambda$static$70(String,String,Optional)
- PropertyMap lambda$static$73(Either)
+ PropertyMap lambda$static$75(Either)
- String lambda$ensureHomogenous$51(Object,Object,Object)
+ String lambda$ensureHomogenous$53(Object,Object,Object)
- String lambda$floatRangeMinExclusiveWithMessage$41(Function,Float)
+ String lambda$floatRangeMinExclusiveWithMessage$43(Function,Float)
- String lambda$idResolverCodec$25(Integer)
+ String lambda$idResolverCodec$27(Integer)
- String lambda$idResolverCodec$28(Object)
+ String lambda$idResolverCodec$30(Object)
- String lambda$intRange$40(int,int,Integer)
+ String lambda$intRange$42(int,int,Integer)
- String lambda$intRangeWithMessage$36(Function,Integer)
+ String lambda$intRangeWithMessage$38(Function,Integer)
- String lambda$nonEmptyHolderSet$46()
+ String lambda$nonEmptyHolderSet$48()
- String lambda$nonEmptyList$44()
+ String lambda$nonEmptyList$46()
- String lambda$sizeLimitedString$83(String,int,int,int)
- String lambda$sizeLimitedString$84(String,int,int,int)
+ String lambda$sizeLimitedString$85(String,int,int,int)
+ String lambda$sizeLimitedString$86(String,int,int,int)
+ String lambda$static$16(Integer)
- String lambda$static$38(Integer)
- String lambda$static$39(Integer)
+ String lambda$static$40(Integer)
+ String lambda$static$41(Integer)
- String lambda$static$43(Float)
+ String lambda$static$45(Float)
- String lambda$static$53(String,PatternSyntaxException)
+ String lambda$static$55(String,PatternSyntaxException)
- String lambda$static$56()
+ String lambda$static$58()
- String lambda$static$58(byte[])
+ String lambda$static$60(byte[])
- String lambda$static$79()
+ String lambda$static$81()
- String lambda$static$81(String)
+ String lambda$static$83(String)
- String lambda$static$86(String)
+ String lambda$static$88(String)
- String lambda$stringResolverCodec$30(String)
+ String lambda$stringResolverCodec$32(String)
- String lambda$stringResolverCodec$33(Object)
+ String lambda$stringResolverCodec$35(Object)
- void lambda$static$70(PropertyMap,String,List)
- void lambda$static$71(PropertyMap,Map)
- void lambda$static$72(PropertyMap,List)
+ void lambda$static$72(PropertyMap,String,List)
+ void lambda$static$73(PropertyMap,Map)
+ void lambda$static$74(PropertyMap,List)
- void lambda$static$76(GameProfile,String,Property)
+ void lambda$static$78(GameProfile,String,Property)
```

</details>


<details><summary>net.minecraft.util.ExtraCodecs$RecursiveMapCodec</summary>

```diff
- void <init>(Function)
+ void <init>(String,Function)
```

</details>


# Registries

<details><summary>armor_material.txt</summary>

```diff
- minecraft:chain
+ minecraft:chainmail
```

</details>
