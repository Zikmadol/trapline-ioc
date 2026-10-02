# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1467 attackers** · **332,040 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 102 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 102 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 620 |
| `ssh-bruteforce` | 348 |
| `redis-exploit` | 282 |
| `mcp-abuse` | 93 |
| `llamacpp-abuse` | 26 |
| `litellm-key-replay` | 23 |
| `docker-abuse` | 16 |
| `ollama-abuse` | 12 |
| `canary-aws-key` | 10 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 995 |
| `redis` | 290 |
| `mcp` | 132 |
| `llamacpp` | 83 |
| `vllm` | 52 |
| `jupyter` | 45 |
| `litellm` | 44 |
| `hfhub` | 41 |
| `docker` | 33 |
| `ollama` | 21 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 586 |
| `345gs5662d34` | 500 |
| `admin` | 305 |
| `ubuntu` | 137 |
| `administrator` | 84 |
| `test` | 68 |
| `user` | 64 |
| `admin1` | 63 |
| `AdminGPON` | 55 |
| `ftpuser` | 54 |
| `a` | 54 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `ai` | 53 |
| `aaa` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 501 |
| `345gs5662d34` | 499 |
| `123456` | 327 |
| `123` | 198 |
| `1234` | 172 |
| `12345678` | 104 |
| `admin` | 96 |
| `password` | 79 |
| `1` | 76 |
| `000000` | 76 |
| `12345` | 75 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `123456789` | 58 |
| `0000` | 57 |

### Top commands run

| command | times |
|---|---|
| `uname` | 653 |
| `echo` | 582 |
| `lscpu` | 569 |
| `crontab` | 568 |
| `cat` | 558 |
| `cd` | 557 |
| `ls` | 515 |
| `top` | 515 |
| `df` | 514 |
| `free` | 514 |
| `whoami` | 513 |
| `w` | 512 |
| `INFO` | 186 |
| `PING` | 119 |
| `canary_env` | 118 |


_Generated from first-party honeypot capture. CC BY 4.0._
