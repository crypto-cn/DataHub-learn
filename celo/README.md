Datahub Link: https://datahub.figment.io/services/celo



1

node connect.js



2

node create_account.js

copy result into .env

```
ADDRESS=<ADDRESS FROM CONSOLE LOG>

PRIVATE_KEY=<PRIVATE KEY FROM CONSOLE LOG>
```





3

node query.js   3 times

Query account balances ,note other

Query node info,note other

again 



4

Get free testnet tokens: https://celo.org/developers/faucet

node transfers.js

node exchange.js



5

npm install -g truffle

cd contracts

truffle compile

truffle migrate --network alfajores

cd ..

node interactions.js