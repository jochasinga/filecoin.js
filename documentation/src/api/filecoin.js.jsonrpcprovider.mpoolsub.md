---
id: filecoin.js.jsonrpcprovider.mpoolsub
title: JsonRpcProvider.mpoolSub() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[filecoin.js](./filecoin.js.md) &gt; [JsonRpcProvider](./filecoin.js.jsonrpcprovider.md) &gt; [mpoolSub](./filecoin.js.jsonrpcprovider.mpoolsub.md)

## JsonRpcProvider.mpoolSub() method

returns a list of pending messages for inclusion in the next block

<b>Signature:</b>

```typescript
mpoolSub(cb: (data: MpoolUpdate) => void): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  cb | (data: MpoolUpdate) =&gt; void |  |

<b>Returns:</b>

Promise&lt;void&gt;