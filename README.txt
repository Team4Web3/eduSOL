https://raw.githubusercontent.com/Team4Web3/eduSOL/refs/heads/main/eduSolLST.json

Creating and initializing reserve stake account 4tfBYsyK3DTn4g3Sr5qLex9B248THyZGq8Wo1gFYDvaY
Signature: hT6hukEZpdRj6DR5GXoBxAyotvNADTztuoS9EDWGKkUQaZnUkvWCtj8EUfHnS6WoL6UB1VqfRzzHdQFAL3ENJgy
Creating and initializing mint account 5exCyccutnoDscJkJxe1EN17mi5kyfLzcng7k9vTmTP7
Signature: cMxqcFRmEiyFi9YkvKUA7pZ83SpVYuUhfX9Fd33TcWNhniUCFiv7Q4s4nW3tKDw8NgRvgans9d32SJaLes3yp3N
Creating associated token account AyQzWyxdKcuFx5AXueKxccwuVLH3XA3MQyMpuLWVpbpm to receive stake pool tokens of mint 5exCyccutnoDscJkJxe1EN17mi5kyfLzcng7k9vTmTP7, owned by HWo9bf8tp9Xk2fUwA94op7aRLqpU1ps5XTP127WsDZ55
Creating pool fee collection account AyQzWyxdKcuFx5AXueKxccwuVLH3XA3MQyMpuLWVpbpm
Signature: 2tEPBStQi1pg3tqonEBN6qWgSRStcJ1Urn8xp87KtX9EGqk2vSr7s72sUbuRFSBH8TBSTSFaQho3ZsERiAQks9dg
Setting up and initializing stake pool account 4xTWdaweUsJx3y3U1GEQTnS5mCswPxMZACoSyLPyt4oU with validator list Drk1axqdBuPJUrpepLrMyTygZVkdyCouw56qZf1daGq
Signature: s2E6Cy1oGng66Vdm9QQDw3ZJwzJL2B6Bp2XC6DgMgFHW2Eeo6osS7Z3MDRda3uGwJ4kapMvB4Ur2WeSstjSqLZC

# Criação metadata
spl-stake-pool create-token-metadata 4xTWdaweUsJx3y3U1GEQTnS5mCswPxMZACoSyLPyt4oU "Education Staked SOL" "eduSOL" "https://raw.githubusercontent.com/Team4Web3/eduSOL/main/eduSolLST.json"

# Atualização
spl-stake-pool update-token-metadata 4xTWdaweUsJx3y3U1GEQTnS5mCswPxMZACoSyLPyt4oU "Education Staked SOL" "eduSOL" "https://raw.githubusercontent.com/Team4Web3/eduSOL/main/eduSolLST.json"

# Adicionar Validador
# spl-stake-pool add-validator <STAKE_POOL_ADDRESS> <VALIDATOR_VOTE_ADDRESS>
spl-stake-pool add-validator 4xTWdaweUsJx3y3U1GEQTnS5mCswPxMZACoSyLPyt4oU 3gmaQjGs89288xNNr4hHbgAME8cGv4fKi6iH7dDg15va

# Incrementar Stake no Validador
# spl-stake-pool increase-validator-stake <STAKE_POOL_ADDRESS> <VALIDATOR_VOTE_ADDRESS> <QTD>
$ spl-stake-pool increase-validator-stake 4xTWdaweUsJx3y3U1GEQTnS5mCswPxMZACoSyLPyt4oU 3gmaQjGs89288xNNr4hHbgAME8cGv4fKi6iH7dDg15va 10

# Remover
# spl-stake-pool remove-validator <STAKE_POOL_ADDRESS> <VALIDATOR_VOTE_ADDRESS>
$ spl-stake-pool remove-validator 4xTWdaweUsJx3y3U1GEQTnS5mCswPxMZACoSyLPyt4oU 3gmaQjGs89288xNNr4hHbgAME8cGv4fKi6iH7dDg15va

# Detalhes da Pool
# spl-stake-pool list <STAKE_POOL_ADDRESS>
$ spl-stake-pool list 4xTWdaweUsJx3y3U1GEQTnS5mCswPxMZACoSyLPyt4oU