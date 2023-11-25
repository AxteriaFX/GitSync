---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# ⚙ Configuration

### Velocity MOTD

***

The part you edit in `Heroic Velocity [EN]\plugins\minimotd-velocity\main.conf;`



<pre><code>motds=[
    {
        # Set the icon to use with this MOTD
        #  Either use 'random' to randomly choose an icon, or use the name
        #  of a file in the icons folder (excluding the '.png' extension)
        #    ex: icon="myIconFile"
        icon=random
        line1="                    &#x3C;gradient:#f24c17:#ff00e0><a data-footnote-ref href="#user-content-fn-1">✡ Heroic Velocity ✡</a>&#x3C;/gradient>"
        line2="              &#x3C;#FFA800>ɴᴇᴡs ▪ &#x3C;gradient:#DCDCDC:#8D8D8D>New adventure begins! &#x3C;/gradient>"
    }
]
</code></pre>

### Velocity Lang

***

The part you edit in Heroic Velocity \[EN]\lang\messages.properties`;`

```json
velocity.error.already-connected=\n§4§l§nᴇʀʀᴏʀ!\n§7\n§f You are already connected to the server, \n§fwait a bit and try again!\n§7Website §f► §4www.hivenephive.com\n§7Discord §f► §4discord.hivenephive.com
velocity.error.already-connected-proxy=\n§4§l§nᴇʀʀᴏʀ!\n§7\n§f You are already connected to the server, \n§fwait a bit and try again!\n§7\n§7Website §f► §4www.hivenephive.com\n§7Discord §f► §4discord.hivenephive.com
velocity.error.already-connecting=\n§4§l§nᴇʀʀᴏʀ!\n§7\n§f You are already trying to connect to the server. \n§fwait a bit and try again!\n§7\n§7Website §f► §4www.hivenephive.com\n§7Discord §f► §4discord.hivenephive.com
velocity.error.cant-connect={0}\:{1} unable to establish a connection with
velocity.error.connecting-server-error=\n§4§l§nᴇʀʀᴏʀ!\n§7\n§f We couldn't connect you to §c{0}§f. §fIf you think there is a problem,\n§f report it to the authorized person.\n§7\n§7Website §f► §4www.hivenephive.com\n§7Discord §f► §4discord.hivenephive.com
velocity.error.connected-server-error={0} there's been a problem with your connection.
velocity.error.internal-server-connection-error=An error occurred in the internal server connection.
velocity.error.logging-in-too-fast=\n§4§l§nᴇʀʀᴏʀ!\n§7\n§f You're trying to connect too fast.\n§f Wait a bit and try again!\n§7\n§7Website §f► §4www.hivenephive.com\n§7Discord §f► §4discord.hivenephive.com
velocity.error.online-mode-only=You are not connected to your Minecraft account. If you are connected to your Minecraft account, close and restart your Minecraft client.
velocity.error.player-connection-error=An internal error occurred in your connection.
velocity.error.modern-forwarding-needs-new-client=You can only log in to this server with Minecraft version 1.13 and above.
velocity.error.modern-forwarding-failed=Your server did not request a redirect to Velocity. Make sure the server is set in Velocity's settings.
velocity.error.moved-to-new-server={0}\:{1} you've been kicked off the server
velocity.error.no-available-servers=\n§4§l§nᴇʀʀᴏʀ!\n§7\n§f We couldn't find any server that we can connect you to.\n§fIf you think there is a problem\n§freport it to the authority.\n§7\n§7Website §f► §4www.hivenephive.com\n§7Discord §f► §4discord.hivenephive.com
```

###

[^1]: 
