# Tron Full Node Installation

## Open API for lite fullnode (HTTP, GRPC)
```
openHistoryQueryWhenLiteFN = true
```

## Open JSON RPC
```
httpFullNodeEnable = true
httpFullNodePort = 8545
httpSolidityEnable = true
httpSolidityPort = 8555
```

## Open event subscription (transaction)
```
{
    triggerName = "transaction"
    enable = true
    topic = "transaction"
    solidified = true
    ...
},
```

## Enable to estimate energy
```
vm = {
  supportConstant =true
  ...
  # Indicates whether the node support estimate energy API.
  estimateEnergy = true
  ...
}
```