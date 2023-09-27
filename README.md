# W3C-Noir-Backend

This is a simple backend project implementing basic services of the Privacy-Preserving W3C Verifiable Credentials protocol.

## Run our code

### Prerequisite

- Node version >= 16

### Installation

- Install dependencies:

```
npm i
```

- Config environmental variable:

In the .env file, you need to reconfigure PROVIDER (RPC URL for the blockchain network, in my case, it's the RPC of the local Hardhat network), WALLET (private key for the wallet to deploy contracts and perform services), and optional configurations (PORT for the server's port, ISSUER_KEY and HOLDER_KEY are the initial private keys).
```
PORT=8000
PROVIDER = "http://127.0.0.1:8545"
WALLET = "0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80"
ISSUER_KEY = "123456789"
HOLDER_KEY = "987654321"
```


- Start server:

```
npm run start
```
