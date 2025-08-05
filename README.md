# miner
zeroth blockchain miner

2025.07.01 : We have replaced the Ethereum-based miner with a dedicated miner program.


# How to CPU mining
~~./ethminer -R --display-interval 30 --cpu --cl-local-work 64 -P stratum2+tcp://{WALLET}@zeroth.ace1pool.com:8008 -v3~~

# Zeroth Miner v0.1.0 사용법 (2025.08.05 기준)

```bash
./zeroth_miner_0.1.0 [OPTIONS]

| Options                      | Desc                                                           |
| `      --server <SERVER>      API server address [default: http://169.211.197.186:8556]
| `      --username <USERNAME>  Username [default: park]
| `      --password <PASSWORD>  Password [default: park5647]
| `      --address <ADDRESS>    Wallet address [default: 0xaeF43B6d55Beb12aF50E190EbF60e7DDC88A94Ae]
| `      --new                  Create new user account
| `  -h, --help                 Print help
| `  -V, --version              Print version

./zeroth_miner_0.1.0 --username alice --password secret --address 0x123...
