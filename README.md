# miner
zeroth blockchain miner

2025.07.01 : We have replaced the Ethereum-based miner with a dedicated miner program.


# How to CPU mining
~~./ethminer -R --display-interval 30 --cpu --cl-local-work 64 -P stratum2+tcp://{WALLET}@zeroth.ace1pool.com:8008 -v3~~

# Zeroth Miner v0.1.0 사용법 (2025.08.05 기준)

```bash
./zeroth_miner_0.1.0 [OPTIONS]

| 옵션                      | 설명                                                             |
| ----------------------- | -------------------------------------------------------------- |
| `--server <SERVER>`     | API 서버 주소<br>**기본값:** `http://169.211.197.186:8556`            |
| `--username <USERNAME>` | 사용자 이름<br>**기본값:** `park`                                      |
| `--password <PASSWORD>` | 비밀번호<br>**기본값:** `park5647`                                    |
| `--address <ADDRESS>`   | 지갑 주소<br>**기본값:** `0xaeF43B6d55Beb12aF50E190EbF60e7DDC88A94Ae` |
| `--new`                 | 새 사용자 계정 생성                                                    |
| `-h`, `--help`          | 도움말 출력                                                         |
| `-V`, `--version`       | 버전 정보 출력                                                       |

./zeroth_miner_0.1.0 --username alice --password secret --address 0x123...
