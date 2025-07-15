## Comparison with [1.19.1-pre6](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.1-pre6)

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
<table><tr><th></th><th align="left">1.19.1-pre6</th><th>1.19.1-rc2</th></tr><tr><td>World version</td><td><pre>3114</pre></td><td><pre>3115</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741923</pre></td><td><pre>1073741924</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.19.1-pre6</th><th>1.19.1-rc2</th></tr><tr><td>com.mojang:authlib</td><td><pre>3.10.48</pre></td><td><pre>3.11.49</pre></td></tr></table>
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
+ gui.chatReport.send.comments_too_long: Please shorten the comment
+ gui.chatReport.send.too_many_messages: Trying to include too many messages in the report
+ multiplayer.unsecureserver.toast: Messages sent on this server may be modified and might not reflect the original message
+ multiplayer.unsecureserver.toast.title: Chat messages can't be verified
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.19.1-pre6</th><th>1.19.1-rc2</th></tr>
<tr><th align="left"><div style="width:290px">options.chatPreview.live</div></th><td>On Modified</td><td>While Typing</td></tr>
<tr><th align="left"><div style="width:290px">options.chatPreview.confirm</div></th><td>On Send</td><td>When Sending</td></tr>
</table>
<br/>
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
XXX.network.chat.SignedMessageValidator +2M -2M | -1P
```
```
XXX.protocol.game.ClientboundServerDataPacket +2M -1M | +1P
```
```
XXX.protocol.status.ServerStatus +2M | +1P
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageValidator
</summary>

```diff
- SignedMessageValidator alwaysReturn(SignedMessageValidator$State)
- SignedMessageValidator create(ProfilePublicKey,boolean)
+ SignedMessageValidator create(ProfilePublicKey)
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundServerDataPacket
</summary>

```diff
- boolean enforcesSecureChat()
- void <init>(Component,String,boolean,boolean)
+ void <init>(Component,String,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.status.ServerStatus
</summary>

```diff
- boolean enforcesSecureChat()
- void setEnforcesSecureChat(boolean)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.gui.components.ChatComponent -1M
```
```
XXX.components.toasts.SystemToast$SystemToastIds +1P
```
```
XXX.client.multiplayer.ClientPacketListener +2P
```
```
XXX.network.chat.SignedMessageValidator$1 +1M -1M | +1P
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.ChatComponent
</summary>

```diff
+ void addMessage(Component,GuiMessageTag)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageValidator$1
</summary>

```diff
+ void <init>()
- void <init>(SignedMessageValidator$State)
```

</details>
</details>
<hr/>