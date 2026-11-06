---
description: Protect your builds with Lands, team up with friends and form nations.
icon: house-lock
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

# Land Claiming

Zenith uses **Lands** to protect builds. A land is a group of claimed chunks that only you and the players you trust can build in. Claims work in the **Overworld** and the **Nether**. The End can't be claimed.

{% hint style="success" %}
Most things can be done from the menu. Type `/lands` to open it.
{% endhint %}

## Getting started

1. Stand where you want to build and type `/lands create <name>`. This claims the chunk you are standing in.
2. Walk to the next chunk and type `/lands claim` to add it.
3. Type `/lands map` to see claimed chunks around you, or `/lands info` to see your land.

Creating a land and claiming chunks is **free**. Chunks come out of your claim allowance (see below). You can own **one land**, but it can be in as many separate pieces as you like, so you can claim an outpost far away from your base and it still counts as the same land.

### Useful commands

| Command | What it does |
| --- | --- |
| `/lands` | Opens the Lands menu |
| `/lands create <name>` | Creates your land |
| `/lands claim` | Claims the chunk you are in |
| `/lands unclaim` | Unclaims the chunk you are in |
| `/lands map` | Shows a map of claims around you |
| `/lands info [land]` | Shows info about a land |
| `/lands trust <player>` | Invites a player to your land |
| `/lands untrust <player>` | Removes a player from your land |
| `/lands accept <land>` | Accepts an invite to a land |
| `/lands leave <land>` | Leaves a land you are in |
| `/lands setspawn` | Sets your land's spawn point |
| `/lands spawn [land]` | Teleports to a land's spawn |
| `/lands deposit <amount>` | Puts money in the land bank |
| `/lands withdraw <amount>` | Takes money out of the land bank |
| `/lands rename <name>` | Renames your land |
| `/lands delete` | Deletes your land |

## How many chunks you can claim

| Where chunks come from | How many |
| --- | --- |
| Starting allowance | 8 chunks |
| Playtime | 1 chunk for every 1 hour 42 minutes you play, up to 310 chunks |
| `/shop`, Claims section | $7,500 per chunk, in packs of 1, 5, 10 or 25 |
| Claim chunk vouchers | From crates, voting and events |

This means you can earn up to **318 chunks** just by playing, and buy as many more as you want.

{% hint style="info" %}
Every chunk you claim uses **your own** allowance, even when you claim it for someone else's land. If a friend runs out, you can claim chunks for their land with yours.
{% endhint %}

### Claiming rules

* Lands must be at least **4 chunks** away from other players' lands.
* You can't claim chunks that would box in someone else's land.
* Unclaiming a chunk gives it back to your allowance.

## Trusting players and roles

Use `/lands trust <player>` to invite someone. Once they accept, they become a **Member** of your land. A land can have up to **20 members**.

Every player in your land has a **role**, and each role has its own permissions. Change them in `/lands` under **Roles**.

| Role | Who it is for | What they can do by default |
| --- | --- | --- |
| **Owner** | You | Everything |
| **Admin** | People who help run your land | Build, use everything, and manage the land |
| **Member** | Trusted players | Build, break, farm and use doors, chests and machines |
| **Tenant** | Players renting an area | Build and use things in the area they rent |
| **Nation** | Players from other lands in your nation | Use doors, buttons and villagers, but not build or open chests |
| **Ally** | Players from allied lands | Walk in, pick up items and kill monsters |
| **Untrusted** | Everyone else | Walk in, pick up items and kill monsters |

{% hint style="warning" %}
You can't ban players from your land or stop them walking in. Untrusted players can always enter, but they can't build, break or open anything.
{% endhint %}

## PvP

PvP is **off** in every land by default. A land owner can turn it on for a role from the Roles menu if they want PvP in their land.

## Land bank

Each land has a bank shared by its members. Put money in with `/lands deposit <amount>` and take it out with `/lands withdraw <amount>`. There are no taxes or upkeep, so you never pay to keep your land.

## Areas

An **area** is a part of your land with its own permissions. Use areas to give a friend their own house in your town, or to make a public farm that untrusted players can use. Each land can have up to **20 areas**. Create them in `/lands` under **Areas**.

You can also **rent out** or **sell** an area to another player. The renter becomes a **Tenant** of that area.

## Allies and enemies

Lands can ally with up to 10 other lands. Allies get the **Ally** role in your land. Wars are turned off on Zenith.

## Nations

A nation is a group of lands working together, with one land as the **capital**.

* Creating a nation costs **$50,000**, and your land must be at the highest land level.
* A nation can hold up to **10 lands**.
* Players from member lands get the **Nation** role in each other's lands.
* The nation owner can't change the permissions of the lands in the nation.

Nation commands start with `/nations` (or `/n`).
