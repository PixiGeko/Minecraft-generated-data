## Comparison with [1.16-rc1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16-rc1)

- [Version data](#version-data)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.16-rc1</th><th>1.16</th></tr><tr><td>World version</td><td><code>2565</code></td><td><code>2566</code></td></tr><tr><td>Protocol version</td><td><code>734</code></td><td><code>735</code></td></tr></table>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>

<details>
<summary>
Changes
</summary>

```
XXX.network.chat.Component +1M
```

</details>
















































































































































































































































































































<details>
<summary>
net.minecraft.network.chat.Component
</summary>

```diff
- Component nullToEmpty(String)
```

</details>










































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<h2>Client</h2>

<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList +2M | +1P
```
```
XXX.realmsclient.client.RealmsError +2M -1M
```

</details>


































































<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
</summary>

```diff
- int addMessageEntry(RealmsMainScreen$Entry)
- void clear()
```

</details>








<details>
<summary>
com.mojang.realmsclient.client.RealmsError
</summary>

```diff
- RealmsError create(String)
- void <init>(String,int)
+ void <init>(String)
```

</details>
</details>