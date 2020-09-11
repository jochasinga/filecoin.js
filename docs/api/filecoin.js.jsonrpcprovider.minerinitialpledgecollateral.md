---
id: filecoin.js.jsonrpcprovider.minerinitialpledgecollateral
title: JsonRpcProvider.minerInitialPledgeCollateral() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[filecoin.js](./filecoin.js.md) &gt; [JsonRpcProvider](./filecoin.js.jsonrpcprovider.md) &gt; [minerInitialPledgeCollateral](./filecoin.js.jsonrpcprovider.minerinitialpledgecollateral.md)

## JsonRpcProvider.minerInitialPledgeCollateral() method

returns the initial pledge collateral for the specified miner's sector

<b>Signature:</b>

```typescript
minerInitialPledgeCollateral(address: string, sectorPreCommitInfo: SectorPreCommitInfo, tipSetKey?: TipSetKey): Promise<string>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  address | string |  |
|  sectorPreCommitInfo | SectorPreCommitInfo |  |
|  tipSetKey | TipSetKey |  |

<b>Returns:</b>

Promise&lt;string&gt;