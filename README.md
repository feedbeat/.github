# feedbeats - Web3 feed for all gamers -

## Background 
### Hackathon

![](https://i.imgur.com/TdGnkK6.jpg)

**Network State Stack**
Web3 is a rewired internet backend that enables the true ownership of assets, data and identity, and composability stands at the centre of the Web3 user experience, especially in the context of social, gaming, and creator economy. There should be a complete technology stack which backs the Web3 UGCs, but it is yet to be built

We aim to build a comprehensive stack which enables the formation of a Network State that includes Social, On-chain Games, User-Generated Content, and Creator Economy tools.

* website: https://ntwstate.org/
* Notion(more info): https://ash-tricorne-09b.notion.site/MatchboxDAO-and-Mask-Virtual-Hackathon-3-34eefedacdc34b588397cfb8c3e60b0f
* doc: https://docs.google.com/document/d/178bMO-g6SwDY73t_Y9RAQkANXwQ6M6feCDQOo5vOWHQ/edit#


### Theme
A player's feed (potentially on cartridge) that shows who just played what via RSS3 the feed protocol


## Overview
You can view the history of gameplay and NFT purchases of people you follow on social. Thus, you can see what games your friends are playing and play those games yourself.


- What's good for users

Users can understand the games played by people they follow on social. They can gain access to the latest trends by knowing what games are being played by progressive people in alpha communities.

- What's good for projects

As a project, they can spread the game to various users without doing their own PR just by having a game played by alpha users. Therefore, they can focus on making a good game.

## How it works
* Wallet connect - Log in with Metamask and connect multiple wallets (including Startnet Wallet).
* Connecting Wallet id and Mask id.
* List Wallet addresses of users you follow on Twitter, Instagram and Lens
    * Lens: Lists wallet addresses linked to Lens accounts that users follow in their Lens accounts.
    * Twitter: List wallet addresses of users you follow on Twitter via Mask Network.
* Retrieve and distribute specific actions on the relevant wallet address via RSS3 and on-chain info

## Tech stack
* Wallet
    * Rainbot kits: https://www.rainbowkit.com/
    * Argent: https://www.argent.xyz/
* Social 
    * Mask network: https://mask.io/
    * Next.ID: https://next.id/
    * Lens protocol: https://www.lens.xyz/
* RSS & data
    * RSS3: https://rss3.io/ 
        * It's not available on Starknet 
    * KNN3
        * https://www.knn3.xyz/ 
* RPC
    * Infura: https://www.infura.io/networks
    * Alchemy: https://www.alchemy.com/supernode
    * Quicknode(API): https://www.quicknode.com/
* Game
    * EVM
        * Dark Forest: https://zkga.me/
        * Phi: https://philand.xyz/
        * Hyperloot: https://hyperlootproject.com/
    * Stark
        * Topology: https://www.topology.gg/
        * Loot Realms: https://realmseternum.com/
        * Briq: https://briq.construction/

## Reference
### Sample project
* hoot.it: https://hoot.it/

![](https://i.imgur.com/OmR8n1m.png)

### On-chain gaming
Engine for on-chain gaming

**Curio**
* web: https://www.curio.gg/
* blog: https://blog.curio.gg/
* twitter: https://twitter.com/0xcurio

**Matchbox DAO**
* web: https://www.matchboxdao.com/
* Mirror: https://mirror.xyz/matchboxdao.eth
* twitter: https://twitter.com/matchbox_dao

**MUD**
* web: https://mud.dev/
* github: https://github.com/latticexyz/mud
* twitter: https://twitter.com/latticexyz
