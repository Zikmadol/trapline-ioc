# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1675 attackers** · **361,128 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 116 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 117 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 703 |
| `ssh-bruteforce` | 401 |
| `redis-exploit` | 313 |
| `mcp-abuse` | 105 |
| `llamacpp-abuse` | 30 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1135 |
| `redis` | 322 |
| `mcp` | 148 |
| `llamacpp` | 94 |
| `vllm` | 58 |
| `jupyter` | 52 |
| `litellm` | 52 |
| `hfhub` | 46 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 669 |
| `345gs5662d34` | 560 |
| `admin` | 359 |
| `ubuntu` | 160 |
| `test` | 83 |
| `administrator` | 81 |
| `user` | 79 |
| `ftpuser` | 72 |
| `admin1` | 59 |
| `AdminGPON` | 56 |
| `a` | 55 |
| `Asalem` | 52 |
| `Caps` | 51 |
| `aaa` | 50 |
| `admin2` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 561 |
| `345gs5662d34` | 559 |
| `123456` | 399 |
| `123` | 233 |
| `1234` | 204 |
| `12345678` | 131 |
| `admin` | 125 |
| `1` | 107 |
| `12345` | 97 |
| `password` | 95 |
| `000000` | 83 |
| `P@ssw0rd` | 69 |
| `!QAZ2wsx` | 68 |
| `123456789` | 67 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 748 |
| `echo` | 653 |
| `lscpu` | 640 |
| `crontab` | 639 |
| `cd` | 635 |
| `cat` | 635 |
| `ls` | 579 |
| `top` | 578 |
| `df` | 577 |
| `free` | 577 |
| `whoami` | 576 |
| `w` | 575 |
| `INFO` | 207 |
| `canary_env` | 133 |
| `PING` | 133 |


_Generated from first-party honeypot capture. CC BY 4.0._
