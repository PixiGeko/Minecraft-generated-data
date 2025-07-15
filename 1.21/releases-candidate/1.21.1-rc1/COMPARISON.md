## Comparison with [1.21](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21</th><th>1.21.1-rc1</th></tr><tr><td>World version</td><td><pre>3953</pre></td><td><pre>3954</pre></td></tr><tr><td>Protocol version</td><td><pre>767</pre></td><td><pre>1073742028</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.21</th><th>1.21.1-rc1</th></tr><tr><td>com.mojang:brigadier</td><td><pre>1.2.9</pre></td><td><pre>1.3.10</pre></td></tr></table>
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
XXX.commands.arguments.EntityArgument +3M
```
```
XXX.commands.arguments.GameProfileArgument +4M -1M
```
```
XXX.commands.arguments.MessageArgument +2M
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.EntityArgument
</summary>

```diff
- EntitySelector parse(StringReader,boolean)
- EntitySelector parse(StringReader,Object)
- Object parse(StringReader,Object)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.GameProfileArgument
</summary>

```diff
- GameProfileArgument$Result parse(StringReader,boolean)
- GameProfileArgument$Result parse(StringReader,Object)
- Object parse(StringReader,Object)
+ void lambda$listSuggestions$1(CommandContext,SuggestionsBuilder)
- void lambda$listSuggestions$1(SharedSuggestionProvider,SuggestionsBuilder)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.MessageArgument
</summary>

```diff
- MessageArgument$Message parse(StringReader,Object)
- Object parse(StringReader,Object)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.commands.arguments.EntityArgument +3M
```
```
XXX.commands.arguments.GameProfileArgument +4M -1M
```
```
XXX.commands.arguments.MessageArgument +2M
```
```
XXX.block.entity.BlockEntity +3M -1M
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.EntityArgument
</summary>

```diff
- EntitySelector parse(StringReader,boolean)
- EntitySelector parse(StringReader,Object)
- Object parse(StringReader,Object)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.GameProfileArgument
</summary>

```diff
- GameProfileArgument$Result parse(StringReader,boolean)
- GameProfileArgument$Result parse(StringReader,Object)
- Object parse(StringReader,Object)
+ void lambda$listSuggestions$1(CommandContext,SuggestionsBuilder)
- void lambda$listSuggestions$1(SharedSuggestionProvider,SuggestionsBuilder)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.MessageArgument
</summary>

```diff
- MessageArgument$Message parse(StringReader,Object)
- Object parse(StringReader,Object)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BlockEntity
</summary>

```diff
- boolean isValidBlockState(BlockState)
- String getNameForReporting()
+ String lambda$fillCrashReportCategory$7()
- void validateBlockState(BlockState)
```

</details>
</details>
<hr/>