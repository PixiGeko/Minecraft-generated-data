## Comparison with [26.2-snapshot-7](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.2-snapshot-7)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.2-snapshot-7</th><th>26.2-snapshot-8</th></tr><tr><td>DataPack version</td><td><pre>105.1</pre></td><td><pre>106.0</pre></td></tr><tr><td>World version</td><td><pre>4891</pre></td><td><pre>4893</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742137</pre></td><td><pre>1073742138</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.2-snapshot-7</th><th>26.2-snapshot-8</th></tr><tr><td>com.google.code.gson:gson</td><td><pre>2.13.2</pre></td><td><pre>2.14.0</pre></td></tr><tr><td>com.google.guava:guava</td><td><pre>33.5.0-jre</pre></td><td><pre>33.6.0-jre</pre></td></tr><tr><td>com.ibm.icu:icu4j</td><td><pre>77.1</pre></td><td><pre>78.3</pre></td></tr><tr><td>com.microsoft.azure:msal4j</td><td><pre>1.23.1</pre></td><td><pre>1.24.1</pre></td></tr><tr><td>com.mojang:logging</td><td><pre>1.6.11</pre></td><td><pre>1.7.12</pre></td></tr><tr><td>commons-codec:commons-codec</td><td><pre>1.19.0</pre></td><td><pre>1.22.0</pre></td></tr><tr><td>io.netty:netty-buffer</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-codec-base</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-codec-compression</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-codec-http</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-common</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-handler</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-resolver</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-transport-classes-epoll</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-transport-classes-kqueue</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-epoll (linux-aarch_64)</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-epoll (linux-x86_64)</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-kqueue (osx-aarch_64)</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-kqueue (osx-x86_64)</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-unix-common</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>io.netty:netty-transport</td><td><pre>4.2.7.Final</pre></td><td><pre>4.2.13.Final</pre></td></tr><tr><td>org.apache.commons:commons-lang3</td><td><pre>3.19.0</pre></td><td><pre>3.20.0</pre></td></tr><tr><td>org.apache.logging.log4j:log4j-api</td><td><pre>2.25.2</pre></td><td><pre>2.26.0</pre></td></tr><tr><td>org.apache.logging.log4j:log4j-core</td><td><pre>2.25.2</pre></td><td><pre>2.26.0</pre></td></tr><tr><td>org.apache.logging.log4j:log4j-slf4j2-impl</td><td><pre>2.25.2</pre></td><td><pre>2.26.0</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ unpublish.txt
```

</details>
<details>
<summary>
publish
</summary>

```diff
- publish <allowCommands: bool> <gamemode: gamemode> <port: integer>
+ publish <online: bool> <allowCommands: bool> <gamemode: gamemode> <port: integer>
```

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
+ commands.publish.alreadyPublished.lan: Local game is already hosted on port %s
+ commands.publish.alreadyPublished.online: Online game is already hosted
+ commands.publish.started.lan: Local game hosted on port %s
+ commands.publish.started.online: Online game hosted
+ commands.unpublish.notPublished: No multiplayer game published
+ commands.unpublish.success: Multiplayer game is now unpublished
+ death.attack.sulfurCubeHot: %1$s died because not just the floor is lava
+ death.attack.sulfurCubeHot.player: %2$s showed %1$s that not just the floor is lava
+ gui.friends.button.loading.invite_request_pending: Waiting for confirmation
+ narration.link.usage.focused: Press Enter to follow the link
+ narration.link.usage.hovered: Left click to follow the link
+ options.friendsList.confirm.message.link: Microsoft account
+ options.graphicsApi.tooltip.vulkan: Experimental. Might reduce performance or cause instability on some systems.
+ options.online.servers.header: Servers
+ options.realmsNotifications.button: News & Invites
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.2-snapshot-7</th><th>26.2-snapshot-8</th></tr>
<tr><th align="left"><div style="width:290px">gui.friends.button.loading.join_request_pending</div></th><td>Waiting on confirmation from %s</td><td>Waiting for confirmation</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.multiplayer.invite</div></th><td>Invite to world</td><td>Invite</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.multiplayer.invite_accept</div></th><td>Accept invite to join world</td><td>Accept</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.multiplayer.invite_reject</div></th><td>Reject invite to join world</td><td>Decline</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.multiplayer.join_request</div></th><td>Request to join world</td><td>Ask to join</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.multiplayer.join_request_accept</div></th><td>Accept request to join world</td><td>Accept</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.multiplayer.join_request_reject</div></th><td>Reject request to join world</td><td>Decline</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.presence.status.playing_hosted_server</div></th><td>In a joinable world</td><td>Online (World)</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.presence.status.playing_offline</div></th><td>In a world</td><td>Online (World)</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.presence.status.playing_realms</div></th><td>In a Realm</td><td>Online (Realm)</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.presence.status.playing_server</div></th><td>On a server</td><td>Online (Server)</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.toast.join_request.message</div></th><td>%s has requested to join your world. Open the friends list by pressing "%s" or access it through the game menu.</td><td>%s wants to join your world. Open the Friends list with "%s" or from the game menu.</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.toast.request_to_join_friend.message</div></th><td>Request to join world has been sent to %s</td><td>You asked to join %s's world</td></tr>
<tr><th align="left"><div style="width:290px">menu.multiplayerOptions.publish.started.online</div></th><td>This world is now open to multiplayer. The port number is %s</td><td>This world is now open to Online multiplayer.</td></tr>
<tr><th align="left"><div style="width:290px">options.friendsList.confirm.message</div></th><td>The Friends List controls who you can chat with when "Can communicate outside Xbox" is set to "Friends".



Manage this setting on your Microsoft account.



When Friends List is ON, other players can send you friend requests. You can turn OFF friend invitations or the Friends List at any time.</td><td>Use your Friends List to send and receive friend requests.



Manage online safety settings with your %s.</td></tr>
<tr><th align="left"><div style="width:290px">options.friendsList.confirm.title</div></th><td>Turn ON Friends List?</td><td>Friends List</td></tr>
<tr><th align="left"><div style="width:290px">options.graphicsApi.vulkan</div></th><td>Prefer Vulkan</td><td>Prefer Vulkan (Experimental)</td></tr>
<tr><th align="left"><div style="width:290px">options.inGameNotification</div></th><td>In-game Notification</td><td>In-Game Notification</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ minecraft/damage_type/sulfur_cube_hot.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/gui/sprites/friends/background_dark.png
+ minecraft/textures/gui/sprites/friends/background_dark.png.mcmeta
- minecraft/textures/gui/sprites/friends/toast.png
- minecraft/textures/gui/sprites/friends/toast.png.mcmeta
```

</details>
</details>
<hr/>