# Uniswap V3 Subgraph

### Subgraph Endpoint

Synced at: <https://thegraph.com/hosted-service/subgraph/ianlapham/uniswap-v3-subgraph?selected=playground>

Pending Changes at same URL

1. login graph studio, connect wallet, create project
2. graph auth
3. graph codegen
4. graph codegen && graph build
4. graph deploy --studio test-swap

# v3-subgraph

local node testing

1. docker-compose up
2. graph codegen
3. graph build
4. graph deploy --node <http://localhost:8020/> --ipfs <http://localhost:5001> novaswap
5. docker-compose logs -f graph-node (log)
