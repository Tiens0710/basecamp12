
---

## 🔍 Details

### `session2_3/starknet_counter`

This directory contains:

- Cairo 1 smart contracts developed during Sessions 2 & 3.
- Tests written using the Starknet testing framework.
- Structured as a Scarb project for compilation and testing.
- **Note**: This part does not include or use any frontend. The frontend code is located separately in the frontend/ folder. 

### `frontend/hello-xyz/`

- A frontend dApp built using [Scaffold-Stark](https://github.com/OnlyDustXYZ/scaffold-stark).
- Only interacts with the Carlos contract.
- Does not include nor interact with the smart contracts or tests from Sessions 2 & 3.
---

## 🚀 Getting Started

### Compile and Test Contracts

- cd session2_3/starknet_counter
- yarn compile
- yarn test


### Frontend

- cd frontend/hello-xyz
- yarn compile
- yarn chain
- yarn deploy
- yarn start
