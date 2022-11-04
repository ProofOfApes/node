# Steps to Run a Full Node

## Download Required Files
Download apechain and apechain.json from https://github.com/ProofOfApes/node

```bash
wget https://raw.githubusercontent.com/ProofOfApes/node/master/apechain
wget https://raw.githubusercontent.com/ProofOfApes/node/master/apechain.json
```

## Set node permissions

```bash
chmod +x ./apechain
```

## Run the Nodes
```bash
./apechain server --data-dir=./data/ --chain=./apechain.json
```

# Connect to the node
The node will put up a webservice and json rpc on 0.0.0.0:8545 by default

```
http://127.0.0.1:8545
ws://127.0.0.1:8545/ws
```

Please refer to polygon edge doucmentation for more options https://wiki.polygon.technology/docs/edge/get-started/cli-commands#server-flags