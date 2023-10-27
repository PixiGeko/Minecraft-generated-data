<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.19.1-rc2 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.19.1-rc2</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2022-07-21T16:25:50+00:00</td></tr>
<tr><th>SHA1</th><td>be8528e20ead28832f20e4278f45519d1e28022a</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/be8528e20ead28832f20e4278f45519d1e28022a/1.19.1-rc2.json">https://piston-meta.mojang.com/v1/packages/be8528e20ead28832f20e4278f45519d1e28022a/1.19.1-rc2.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/a9c8b05a8082a65678beda6dfa2b8f21fa627bce/1.19.json">https://piston-meta.mojang.com/v1/packages/a9c8b05a8082a65678beda6dfa2b8f21fa627bce/1.19.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/5ec09b2700e5e83380a23cb18e66cfdaa931640b/server.jar">https://piston-data.mojang.com/v1/objects/5ec09b2700e5e83380a23cb18e66cfdaa931640b/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/004f2193e73d8c9500116162237b8b95f5d6f33b/server.txt">https://piston-data.mojang.com/v1/objects/004f2193e73d8c9500116162237b8b95f5d6f33b/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/f8291ce57a856c0e4ca6f02af3eded3148d3e70c/client.jar">https://piston-data.mojang.com/v1/objects/f8291ce57a856c0e4ca6f02af3eded3148d3e70c/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/2294071d96e59cf77fe8193576e97a8133e2c47b/client.txt">https://piston-data.mojang.com/v1/objects/2294071d96e59cf77fe8193576e97a8133e2c47b/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.1-pre6">1.19.1-pre6</a>

# Mappings

### Client




<details><summary>net.minecraft.client.gui.components.ChatComponent</summary>

```diff
- void addMessage(Component,GuiMessageTag)
```

</details>


<details><summary>net.minecraft.network.chat.SignedMessageValidator$1</summary>

```diff
- void <init>()
+ void <init>(SignedMessageValidator$State)
```

</details>


### Server




<details><summary>net.minecraft.network.chat.SignedMessageValidator</summary>

```diff
+ SignedMessageValidator alwaysReturn(SignedMessageValidator$State)
+ SignedMessageValidator create(ProfilePublicKey,boolean)
- SignedMessageValidator create(ProfilePublicKey)
- void <clinit>()
```

</details>


<details><summary>net.minecraft.network.protocol.game.ClientboundServerDataPacket</summary>

```diff
+ boolean enforcesSecureChat()
+ void <init>(Component,String,boolean,boolean)
- void <init>(Component,String,boolean)
```

</details>


<details><summary>net.minecraft.network.protocol.status.ServerStatus</summary>

```diff
+ boolean enforcesSecureChat()
+ void setEnforcesSecureChat(boolean)
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ gui.chatReport.send.comments_too_long
+ gui.chatReport.send.too_many_messages
+ multiplayer.unsecureserver.toast
+ multiplayer.unsecureserver.toast.title
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:authlib:3.10.48
+ com.mojang:authlib:3.11.49
```

</details>
