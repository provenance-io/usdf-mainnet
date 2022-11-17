# USDF private network
Mainnet configurations for usdf private zone.  

 validate genesis file by 
```bash
provenanced  validate-genesis <PATH_TO_GENESIS_FILE>/genesis.json
```

start provenance with
```bash
provenanced -t start --custom-denom=vspn --minimum-gas-prices=0vspn --msgfee-floor-price=0
```

| Upgrade Name | Software Version | Wasm Version.   | Block Height         |
|--------------|------------------|-----------------|----------------------|
| Genesis      | v1.13.0-rc1      | v0.29.0-pio-1   | 0                    |




### pio-usdf-mainnet-1

chsin id for all transactions is `pio-usdf-mainnet-1`
