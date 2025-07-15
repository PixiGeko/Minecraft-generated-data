## Comparison with [1.16.4-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.4-pre2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.16.4-pre2</th><th>1.16.4-rc1</th></tr><tr><td>World version</td><td><pre>2582</pre></td><td><pre>2583</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741826</pre></td><td><pre>1073741827</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.16.4-pre2</th><th>1.16.4-rc1</th></tr><tr><td>com.mojang:authlib</td><td><pre>2.0.26</pre></td><td><pre>2.0.27</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ disconnect.loginFailedInfo.insufficientPrivileges: Multiplayer is disabled. Please check your Microsoft account settings.
+ options.hideMatchedNames: Hide Matched Names
+ options.hideMatchedNames.tooltip: 3rd-party Servers may send chat messages in non-standard formats.
With this option on: hidden players will be matched based on chat sender names.
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
XXX.minecraft.util.StringDecomposer +2M
```

</details>
<details>
<summary>
net.minecraft.util.StringDecomposer
</summary>

```diff
- boolean lambda$getPlainText$2(StringBuilder,int,Style,int)
- String getPlainText(FormattedText)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.realmsclient.dto.RealmsServer +1M
```
```
XXX.util.task.ConnectTask +1M -1M | +1P
```
```
XXX.screens.social.PlayerSocialManager +1M | +1P
```
```
XXX.minecraft.realms.RealmsConnect$1 +1M -1M | +1P
```

</details>
<details>
<summary>
com.mojang.realmsclient.dto.RealmsServer
</summary>

```diff
- ServerData toServerData(String)
```

</details>
<details>
<summary>
com.mojang.realmsclient.util.task.ConnectTask
</summary>

```diff
- void <init>(Screen,RealmsServer,RealmsServerAddress)
+ void <init>(Screen,RealmsServerAddress)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.social.PlayerSocialManager
</summary>

```diff
- UUID getDiscoveredUUID(String)
```

</details>
<details>
<summary>
net.minecraft.realms.RealmsConnect$1
</summary>

```diff
- void <init>(RealmsConnect,String,String,int,Minecraft,RealmsServer)
+ void <init>(RealmsConnect,String,String,int,Minecraft)
```

</details>
</details>
<hr/>