---
title: Managing an MRC721 Collection
description: 
published: true
date: 2023-05-16T20:45:51.151Z
tags: 
editor: markdown
dateCreated: 2023-05-14T07:58:37.361Z
---

MetriVerse provides developers the ability to manage MRC721 collections they own, which have been added to or created on the platform.

The [collection management interface](https://metriverse.exchange/app/manage/collection), which can be found on the token management page while logged into the platform, provides basic MRC721 collection management functionality to developers.
<br/>

|:--------------:|:-----:|:-----------|
| ![transfer.png](/user-guides/transfer.png =64x64) |  **Transfer** | Transfer ownership of the collection to the provided Metrix or EVM address. |
| ![set_controller.png](/developer-guides/set_controller.png =64x64) |  **Set Controller** | Set approval for an address to manage this collection as a controller. Controllers are allowed to mint tokens in a collection. |
| ![set_royalty.png](/developer-guides/set_royalty.png =64x64) |  **Set Royalty** | Set the [ERC2981](https://eips.ethereum.org/EIPS/eip-2981) royalty for this collection. |
| ![set_base_uri.png](/developer-guides/set_base_uri.png =64x64) |  **Set Base URI** | Set the `base uri` for the collection. This could be used in case that a developer wants to host the token metadata off MetriVerse or if the metadata is otherwise hosted elsewhere, like IPFS. |
| ![set_mns_name.png](/developer-guides/set_mns_name.png =64x64) |  **Set MNS Name** | Set the reverse address lookup for this collection's contract address. |
| ![renounce_ownership.png](/developer-guides/renounce_ownership.png =64x64) |  **Renounce Ownership** | Renounce ownership of this collection to the Zero address.<br/>**THIS IS A PERMANENT ACTION USE WITH CAUTION!** |

> **Setting Base URI**
> Setting the Base URI to a location that does not respond with JSON metadata will render tokens essentially broken. Make sure to check that the new Base URI is working properly before setting it in the collection.
{.is-warning}

> **Renouncing Ownership**
> Renouncing ownership without any controllers will disable all minting from this collection and cannot be undone. 
>
> **THIS IS A PERMANENT ACTION USE WITH CAUTION**
{.is-warning}