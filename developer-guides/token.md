---
title: Creating an MRC721 Token
description: 
published: true
date: 2023-05-16T04:44:55.599Z
tags: 
editor: markdown
dateCreated: 2023-05-14T07:57:16.126Z
---

## Instructions
### Single Token Creation
#### Setup Token Info
Select a Token Contract from the dropdown of collections you own.

The next ID in the collection will automatically be filled into the `Token ID` field, this can be changed to either any decimal or hexadecimal number which is not already present in this collection.

If your token will contain potentially age sensitive or NSFW material, you should mark it as NSFW.

Click `Check Validate` to proceed with token creation. In the case that vaildations or checks fail, a reason will be provided which can be modified before attempting again.

![select_contract.png](/developer-guides/select_contract.png)


#### Setup Token Details
Once the token has passed validation checks token details need to be added.

Set the desired name and description for the token.

Upload a token image and/or animation. If using an animation, it's highly recommended to also include an image to be displayed when the animation is not active.

Add any optional attributes. Attributes are abitrary key value pairs.
![token_details.png](/developer-guides/token_details.png)

#### Finalize Creation
Certify that the token provided in the form abides by and adheares to the MetriVerse Terms and Conditions and submit the request.

Token creation requires minting the token on chain, complete the transaction in MetriMask and await it's confirmation.

Token status can be seen on the [token management page](https://metriverse.exchange/app/manage/token)

![submit_create_token.png](/developer-guides/submit_create_token.png)

### Bulk Token Creation

**Coming Soon**

