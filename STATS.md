# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1658 attackers** · **358,283 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 114 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 116 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 698 |
| `ssh-bruteforce` | 392 |
| `redis-exploit` | 311 |
| `mcp-abuse` | 104 |
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
| `ssh` | 1121 |
| `redis` | 320 |
| `mcp` | 146 |
| `llamacpp` | 94 |
| `vllm` | 58 |
| `litellm` | 52 |
| `jupyter` | 51 |
| `hfhub` | 46 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 660 |
| `345gs5662d34` | 555 |
| `admin` | 353 |
| `ubuntu` | 156 |
| `test` | 80 |
| `user` | 80 |
| `administrator` | 80 |
| `ftpuser` | 70 |
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
| `3245gs5662d34` | 556 |
| `345gs5662d34` | 554 |
| `123456` | 394 |
| `123` | 232 |
| `1234` | 198 |
| `12345678` | 129 |
| `admin` | 123 |
| `1` | 105 |
| `12345` | 96 |
| `password` | 93 |
| `000000` | 81 |
| `123456789` | 67 |
| `P@ssw0rd` | 67 |
| `!QAZ2wsx` | 67 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 740 |
| `echo` | 645 |
| `lscpu` | 632 |
| `crontab` | 631 |
| `cd` | 629 |
| `cat` | 629 |
| `ls` | 573 |
| `top` | 572 |
| `df` | 571 |
| `free` | 571 |
| `whoami` | 570 |
| `w` | 569 |
| `INFO` | 205 |
| `PING` | 133 |
| `canary_env` | 132 |


_Generated from first-party honeypot capture. CC BY 4.0._
