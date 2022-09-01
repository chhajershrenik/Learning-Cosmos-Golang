# Learning-Cosmos-Golang

## Set Up Environment
- Install Docker
- Install Go
- Install Node.js
- Install Rust

## Run a Node, API, and CLI


### Build and Compile simapp from cosmos-sdk

- mkdir cosmos
- cd cosmos
- git clone https://github.com/cosmos/cosmos-sdk
- cd cosmos-sdk
- make build

#### SimApp Setup

Initialize SimApp application. The initialization creates the genesis block and an initial chain state:
- ./simd init demo

##### Prepare Accounts

To list keys:
- ./simd keys list
To Add keys
- ./simd keys add [keyname]

List of keys:
- Validator
  - ./simd keys add validator
- Accounts
  - ./simd keys add account1
  - ./simd keys add account2
  - ./simd keys add account3
  - ./simd keys add account4
  - ./simd keys add account5
