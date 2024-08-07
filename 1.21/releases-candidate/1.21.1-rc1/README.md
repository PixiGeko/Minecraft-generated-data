<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.21.1-rc1 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.21.1-rc1</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2024-08-07T14:29:18+00:00</td></tr>
<tr><th>SHA1</th><td>4b60e080ee60e12408ea248cc494a37f6996d766</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/4b60e080ee60e12408ea248cc494a37f6996d766/1.21.1-rc1.json">https://piston-meta.mojang.com/v1/packages/4b60e080ee60e12408ea248cc494a37f6996d766/1.21.1-rc1.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/46546e154a2a6b3d51efc2b9bdb05fc24fb96347/17.json">https://piston-meta.mojang.com/v1/packages/46546e154a2a6b3d51efc2b9bdb05fc24fb96347/17.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/e56720aba46f7f07238c4c054a160fc942da9f78/server.jar">https://piston-data.mojang.com/v1/objects/e56720aba46f7f07238c4c054a160fc942da9f78/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/cb4cd0c731c91a37c7e3051945bd4f3f18791134/server.txt">https://piston-data.mojang.com/v1/objects/cb4cd0c731c91a37c7e3051945bd4f3f18791134/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/ef1af29241ac595ddb545a98964e59643a5449d5/client.jar">https://piston-data.mojang.com/v1/objects/ef1af29241ac595ddb545a98964e59643a5449d5/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/48849b49e6e41b387b6244e04b0b42be1bcfdbf1/client.txt">https://piston-data.mojang.com/v1/objects/48849b49e6e41b387b6244e04b0b42be1bcfdbf1/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21">1.21</a>

# Mappings

### Client




<details><summary>net.minecraft.commands.arguments.EntityArgument</summary>

```diff
+ EntitySelector parse(StringReader,boolean)
+ EntitySelector parse(StringReader,Object)
+ Object parse(StringReader,Object)
```

</details>


<details><summary>net.minecraft.commands.arguments.GameProfileArgument</summary>

```diff
+ GameProfileArgument$Result parse(StringReader,boolean)
+ GameProfileArgument$Result parse(StringReader,Object)
+ Object parse(StringReader,Object)
- void lambda$listSuggestions$1(CommandContext,SuggestionsBuilder)
+ void lambda$listSuggestions$1(SharedSuggestionProvider,SuggestionsBuilder)
```

</details>


<details><summary>net.minecraft.commands.arguments.MessageArgument</summary>

```diff
+ MessageArgument$Message parse(StringReader,Object)
+ Object parse(StringReader,Object)
```

</details>


<details><summary>net.minecraft.world.level.block.entity.BlockEntity</summary>

```diff
+ boolean isValidBlockState(BlockState)
+ String getNameForReporting()
- String lambda$fillCrashReportCategory$7()
+ void validateBlockState(BlockState)
```

</details>


### Server




<details><summary>net.minecraft.commands.arguments.EntityArgument</summary>

```diff
+ EntitySelector parse(StringReader,boolean)
+ EntitySelector parse(StringReader,Object)
+ Object parse(StringReader,Object)
```

</details>


<details><summary>net.minecraft.commands.arguments.GameProfileArgument</summary>

```diff
+ GameProfileArgument$Result parse(StringReader,boolean)
+ GameProfileArgument$Result parse(StringReader,Object)
+ Object parse(StringReader,Object)
- void lambda$listSuggestions$1(CommandContext,SuggestionsBuilder)
+ void lambda$listSuggestions$1(SharedSuggestionProvider,SuggestionsBuilder)
```

</details>


<details><summary>net.minecraft.commands.arguments.MessageArgument</summary>

```diff
+ MessageArgument$Message parse(StringReader,Object)
+ Object parse(StringReader,Object)
```

</details>


# Misc

<details><summary>languages.txt</summary>

```diff
+ be_latn.json
+ tzo_mx.json
```

</details>


<details><summary>sounds.txt</summary>

```diff
+ block/spawner/break1.ogg
+ block/spawner/break2.ogg
+ block/spawner/break3.ogg
+ block/spawner/break4.ogg
+ block/spawner/step1.ogg
+ block/spawner/step2.ogg
+ block/spawner/step3.ogg
+ block/spawner/step4.ogg
+ block/spawner/step5.ogg
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:brigadier:1.2.9
+ com.mojang:brigadier:1.3.10
```

</details>
