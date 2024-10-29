---
id: guides-example
title: Guides example
hide_title: true
---

# Guides example

Before getting into coding, you are going to have to start a [Lotus](https://lotus.filecoin.io/lotus/install/prerequisites/) node. To get started quickly, you can use a [hosted node by Glif](https://api.node.glif.io/). In this example, we can use a RPC endpoint for calibration net:

```
https://api.calibration.node.glif.io/rpc/v0
```

Node JavaScript/TypeScript:

```javascript
import { HttpJsonRpcConnector, LotusClient } from 'filecoin.js';

(async() => {
  const httpConnector = new HttpJsonRpcConnector('https://api.calibration.node.glif.io/rpc/v0');
  const lotusClient = new LotusClient(httpConnector);
  const version = await lotusClient.common.version();
  console.log(`Hello, Filecoin.js v${version}`);
})();
```

Browser:

```html
<script type="text/javascript" src="https://unpkg.com/filecoin.js"></script>
<script type="text/javascript">
(async () => {
  const httpConnector = new FilecoinJs.HttpJsonRpcConnector('https://api.calibration.node.glif.io/rpc/v0');

  const lotusClient = new FilecoinJs.LotusClient(httpConnector);
  const version = await lotusClient.common.version();
  console.log(version);
})();
</script>
```

If you run your own node, you will have to provide an argument of type `JsonRpcConnectionOptions` to `HttpJsonRpcConnector` constructor.

```js
const httpConnector = new HttpJsonRpcConnector({
  url: __LOTUS_HTTP_RPC_ENDPOINT__,
  token: __LOTUS_AUTH_TOKEN__,
});
```

