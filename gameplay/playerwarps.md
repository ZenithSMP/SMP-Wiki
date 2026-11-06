---
description: Set public warps so other players can visit your base, shop or farm.
icon: transporter-3
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Player Warps

Player warps let anyone teleport to your base, shop or farm. Type `/pw` to open the warp menu and browse every warp on the server.

## Visiting warps

* `/pw` opens the menu. Sort warps by visits, rating, name or age, or pick a category: **Houses**, **Shops**, **Farms**, **PvP** or **Other**.
* `/pw <warp>` teleports you straight to a warp.
* Teleporting is free. You wait **3 seconds** and must stand still.
* When you visit a warp, the whole server sees a message saying where you went.
* `/pw rate <warp> <1-5> <comment>` rates a warp.
* `/pw favourite <warp>` adds a warp to your favourites.

## Making a warp

Stand where you want the warp and type `/pw set <name>`.

* A warp costs **$500** to make. You get the money back if you remove it.
* Names can be up to **10 characters**.
* Warps can be set in the Overworld but **not in the Nether**.

How many warps you can have depends on your rank:

| Rank | Warps |
| --- | --: |
| Guest | 0 |
| Member | 1 |
| Novice, Adept | 2 |
| Squire, Hermit | 3 |
| Denizen, Elite | 4 |
| Duke, Baron | 5 |
| Lord, Ardent | 6 |
| VIP | 8 |
| MVP | 11 |
| Apex, Celestial | 14 |

See [Ranks](ranks.md) for how to rank up. Use `/pw amount` to see how many you have.

## Managing your warps

Open `/pw`, go to your warps and click one to manage it, or use these commands:

| Command | What it does |
| --- | --- |
| `/pw desc set <warp> <text>` | Sets the description (up to 50 characters) |
| `/pw icon set <warp>` | Sets the icon to the item in your hand |
| `/pw category set <warp> <category>` | Puts the warp in a category |
| `/pw rename <warp> <name>` | Renames the warp |
| `/pw reset <warp>` | Moves the warp to where you are standing |
| `/pw managers set <warp> <player>` | Lets another player manage the warp |
| `/pw setowner <warp> <player>` | Gives the warp to another player |
| `/pw info <warp>` | Shows info about a warp |
| `/pw remove <warp>` | Deletes the warp and refunds the $500 |

VIP and above can use colour codes in warp descriptions.

{% hint style="info" %}
Player warps are always open to everyone. They can't be locked, passworded or have players banned, and a land with a warp in it can't stop visitors walking in. Visitors still can't build or open anything in your land (see [Land Claiming](land-claiming.md)).
{% endhint %}
