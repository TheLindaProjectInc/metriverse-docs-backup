---
title: Managing MRC721 Tokens
description: 
published: true
date: 2023-05-15T19:14:44.453Z
tags: 
editor: markdown
dateCreated: 2023-05-14T07:54:19.738Z
---

While the MRC721 token standard allows for the ability for users to manage their owned tokens in various ways, no Metrix wallets natively support this functionality currently.

MetriVerse solves this dilema by providing users the ability to manage MRC721 tokens they own, which have been added to or created on the platform.

The token management interface, which can be found on the [token management page](https://metriverse.exchange/app/manage/token) while logged into the platform, provides basic MRC721 functionality to users.
 
![manage_token.png](/user-guides/manage_token.png)



|:--------------:|:-----:|:-----------|
| ![transfer.png](/user-guides/transfer.png =64x64) |  **Transfer** | Transfer ownership of the token to the provided Metrix or EVM address. |
| ![set_approval.png](/user-guides/set_approval.png =64x64) |  **Set Approval** | Set approval for an address to manage this token. Only 1 address may be approved at a time. |
| ![set_approval_for_all.png](/user-guides/set_approval_for_all.png =64x64) |  **Set Approval for All** | Set approval for an address for all tokens you own in this collection. |
| ![burn.png](/user-guides/burn.png =64x64) |  **Burn** | Destroy a burnable token, removing it from the circulating supply. |


> **Setting Approval**
> Setting approval of tokens for an address should be used with caution, and only for address which are trusted by the owner.
{.is-warning}

> **Setting Approval for All**
> Setting approval for all for an address gives that address permission to change or move **ALL** tokens of a given collection for your address.
>
> **EXTREME CAUTION is advised when using this function, as it could expose the owner to HIGH RISKS**
{.is-warning}
