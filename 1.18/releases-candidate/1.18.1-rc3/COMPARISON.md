## Comparison with [1.18.1-rc2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18.1-rc2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.18.1-rc2</th><th>1.18.1-rc3</th></tr><tr><td>World version</td><td><pre>2863</pre></td><td><pre>2864</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741887</pre></td><td><pre>1073741888</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.18.1-rc2</th><th>1.18.1-rc3</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +19M -17M
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ boolean lambda$getVmArguments$7(String)
- boolean lambda$getVmArguments$8(String)
+ boolean lambda$static$0(FileSystemProvider)
- boolean lambda$static$1(FileSystemProvider)
- CompletableFuture lambda$sequence$10(CompletableFuture,CompletableFuture)
+ CompletableFuture lambda$sequence$11(CompletableFuture,CompletableFuture)
- CompletableFuture lambda$sequence$12(CompletableFuture,CompletableFuture)
+ CompletableFuture lambda$sequence$9(CompletableFuture,CompletableFuture)
+ ForkJoinWorkerThread lambda$makeExecutor$3(String,ForkJoinPool)
- ForkJoinWorkerThread lambda$makeExecutor$4(String,ForkJoinPool)
+ IllegalStateException lambda$static$1()
- IllegalStateException lambda$static$2()
+ List lambda$sequence$10(List,List)
- List lambda$sequence$11(List,List)
+ List lambda$sequence$8(Object,List)
- List lambda$sequence$9(Object,List)
+ List lambda$sequenceFailFast$14(List,Void)
- List lambda$sequenceFailFast$15(List,Void)
+ Object lambda$wrapThreadWithTaskName$6(String,Supplier)
- Object lambda$wrapThreadWithTaskName$7(String,Supplier)
+ String lambda$sanitizeName$16(CharPredicate,int)
- String lambda$sanitizeName$17(CharPredicate,int)
+ Thread lambda$makeIoExecutor$4(Runnable)
- Thread lambda$makeIoExecutor$5(Runnable)
+ void lambda$prefix$15(Consumer,String,String)
- void lambda$prefix$16(Consumer,String,String)
+ void lambda$sequenceFailFast$12(CompletableFuture,List,int,Object,Throwable)
- void lambda$sequenceFailFast$13(CompletableFuture,List,int,Object,Throwable)
+ void lambda$sequenceFailFast$13(List,CompletableFuture[],CompletableFuture,CompletableFuture)
- void lambda$sequenceFailFast$14(List,CompletableFuture[],CompletableFuture,CompletableFuture)
- void lambda$static$0(LoggerContext,PropertyChangeEvent)
+ void lambda$static$2(String)
- void lambda$static$3(String)
+ void lambda$wrapThreadWithTaskName$5(String,Runnable)
- void lambda$wrapThreadWithTaskName$6(String,Runnable)
- void preInitLog4j()
```

</details>
</details>
<hr/>