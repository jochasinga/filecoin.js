---
id: filecoin.js.jsonrpcprovider.getreceipt
title: JsonRpcProvider.getReceipt() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[filecoin.js](./filecoin.js.md) &gt; [JsonRpcProvider](./filecoin.js.jsonrpcprovider.md) &gt; [getReceipt](./filecoin.js.jsonrpcprovider.getreceipt.md)

## JsonRpcProvider.getReceipt() method

returns the message receipt for the given message

<b>Signature:</b>

```typescript
getReceipt(cid: Cid, tipSetKey?: TipSetKey): Promise<MessageReceipt>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  cid | Cid |  |
|  tipSetKey | TipSetKey |  |

<b>Returns:</b>

Promise&lt;MessageReceipt&gt;