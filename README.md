# Taiko
Tutorial Deploy Contract Taiko use Linux or VPS

curl -L https://foundry.paradigm.xyz | bash

source /root/.bashrc

foundryup

curl https://sh.rustup.rs -sSf | sh

Pilih 1) Proceed with installation (default)

docker pull ghcr.io/foundry-rs/foundry:latest

forge init hello_foundry

forge init --template https://github.com/foundry-rs/forge-template hello_template

cd hello_foundry

forge build

forge test

forge create --legacy --rpc-url https://l2rpc.a1.taiko.xyz --private-key <your_private_key> src/Counter.sol:Counter

Copy hashnya terus paste di ➡️ https://l2explorer.a1.taiko.xyz/
