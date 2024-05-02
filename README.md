<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.18.1-rc3 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.18.1-rc3</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2021-12-10T03:36:38+00:00</td></tr>
<tr><th>SHA1</th><td>027ff0f43a3589b3ea16771ec11d052fc0fdf45e</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/027ff0f43a3589b3ea16771ec11d052fc0fdf45e/1.18.1-rc3.json">https://piston-meta.mojang.com/v1/packages/027ff0f43a3589b3ea16771ec11d052fc0fdf45e/1.18.1-rc3.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json">https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/29c43f3af18e66f8368a16ec89f8e54ecda71d85/server.jar">https://piston-data.mojang.com/v1/objects/29c43f3af18e66f8368a16ec89f8e54ecda71d85/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/456f9cdf0ac35c4cc8475e5a285d4ae9ec122138/server.txt">https://piston-data.mojang.com/v1/objects/456f9cdf0ac35c4cc8475e5a285d4ae9ec122138/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/26550a328fd4fbf705cffd3703d8ee63163810e3/client.jar">https://piston-data.mojang.com/v1/objects/26550a328fd4fbf705cffd3703d8ee63163810e3/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/391e64b5fab23ca972fd53eb6597fbc7fed3aed1/client.txt">https://piston-data.mojang.com/v1/objects/391e64b5fab23ca972fd53eb6597fbc7fed3aed1/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18.1-rc2">1.18.1-rc2</a>

# Mappings

### Client




<details><summary>net.minecraft.Util</summary>

```diff
- boolean lambda$getVmArguments$7(String)
+ boolean lambda$getVmArguments$8(String)
- boolean lambda$static$0(FileSystemProvider)
+ boolean lambda$static$1(FileSystemProvider)
+ CompletableFuture lambda$sequence$10(CompletableFuture,CompletableFuture)
- CompletableFuture lambda$sequence$11(CompletableFuture,CompletableFuture)
+ CompletableFuture lambda$sequence$12(CompletableFuture,CompletableFuture)
- CompletableFuture lambda$sequence$9(CompletableFuture,CompletableFuture)
- ForkJoinWorkerThread lambda$makeExecutor$3(String,ForkJoinPool)
+ ForkJoinWorkerThread lambda$makeExecutor$4(String,ForkJoinPool)
- IllegalStateException lambda$static$1()
+ IllegalStateException lambda$static$2()
- List lambda$sequence$10(List,List)
+ List lambda$sequence$11(List,List)
- List lambda$sequence$8(Object,List)
+ List lambda$sequence$9(Object,List)
- List lambda$sequenceFailFast$14(List,Void)
+ List lambda$sequenceFailFast$15(List,Void)
- Object lambda$wrapThreadWithTaskName$6(String,Supplier)
+ Object lambda$wrapThreadWithTaskName$7(String,Supplier)
- String lambda$sanitizeName$16(CharPredicate,int)
+ String lambda$sanitizeName$17(CharPredicate,int)
- Thread lambda$makeIoExecutor$4(Runnable)
+ Thread lambda$makeIoExecutor$5(Runnable)
- void lambda$prefix$15(Consumer,String,String)
+ void lambda$prefix$16(Consumer,String,String)
- void lambda$sequenceFailFast$12(CompletableFuture,List,int,Object,Throwable)
+ void lambda$sequenceFailFast$13(CompletableFuture,List,int,Object,Throwable)
- void lambda$sequenceFailFast$13(List,CompletableFuture[],CompletableFuture,CompletableFuture)
+ void lambda$sequenceFailFast$14(List,CompletableFuture[],CompletableFuture,CompletableFuture)
+ void lambda$static$0(LoggerContext,PropertyChangeEvent)
- void lambda$static$2(String)
+ void lambda$static$3(String)
- void lambda$wrapThreadWithTaskName$5(String,Runnable)
+ void lambda$wrapThreadWithTaskName$6(String,Runnable)
+ void preInitLog4j()
```

</details>


### Server


