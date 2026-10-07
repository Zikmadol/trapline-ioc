# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1863 attackers** · **384,967 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 131 |
| Used a planted canary credential | 6 |
| Seen on more than one sensor | 127 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 765 |
| `ssh-bruteforce` | 452 |
| `redis-exploit` | 348 |
| `mcp-abuse` | 123 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 5 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1251 |
| `redis` | 359 |
| `mcp` | 172 |
| `llamacpp` | 107 |
| `vllm` | 63 |
| `jupyter` | 62 |
| `litellm` | 58 |
| `hfhub` | 50 |
| `docker` | 41 |
| `ollama` | 37 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 726 |
| `345gs5662d34` | 614 |
| `admin` | 395 |
| `ubuntu` | 181 |
| `user` | 94 |
| `test` | 92 |
| `ftpuser` | 81 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 54 |
| `deploy` | 51 |
| `Asalem` | 51 |
| `postgres` | 50 |
| `git` | 49 |
| `Caps` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 614 |
| `345gs5662d34` | 613 |
| `123456` | 442 |
| `123` | 264 |
| `1234` | 223 |
| `admin` | 144 |
| `12345678` | 144 |
| `12345` | 124 |
| `1` | 121 |
| `password` | 103 |
| `000000` | 87 |
| `123456789` | 78 |
| `admin123` | 78 |
| `P@ssw0rd` | 77 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 835 |
| `echo` | 717 |
| `lscpu` | 703 |
| `cd` | 703 |
| `crontab` | 702 |
| `cat` | 701 |
| `ls` | 632 |
| `top` | 631 |
| `df` | 630 |
| `free` | 630 |
| `whoami` | 629 |
| `w` | 628 |
| `INFO` | 232 |
| `PING` | 154 |
| `canary_env` | 153 |


_Generated from first-party honeypot capture. CC BY 4.0._
