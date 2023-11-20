# okx-wallet-solana-adapter

usage:

```js
import { SolanaWallet } from "@xlabs-libs/wallet-aggregator-solana";
import { OKXWalletAdapter } from "okx-wallet-solana-adapter";

const okx = new SolanaWallet(
  new OKXWalletAdapter(),
  new Connection("https://api.mainnet.solana.com")
);
```
