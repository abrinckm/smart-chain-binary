# Binance Smart Chain Fullnode Binary


Step1: generate the genesis state: `./geth  --datadir node  init genesis.json`

Step2: start fullnode: `./geth --config ./config.toml  --datadir ./node`

Step3: start a validator: ` ./geth account new --datadir ./node`, `./geth --config ./config.toml  --datadir ./node -unlock {{validatorAddr}}  --mine`, validatorAddr is the newly created account.
