# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1623 attackers** · **350,608 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 111 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 114 |
| Stage-2 hosts named in payloads | 27 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 685 |
| `ssh-bruteforce` | 385 |
| `redis-exploit` | 307 |
| `mcp-abuse` | 104 |
| `llamacpp-abuse` | 30 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `llamacpp-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1101 |
| `redis` | 316 |
| `mcp` | 146 |
| `llamacpp` | 94 |
| `vllm` | 57 |
| `jupyter` | 51 |
| `litellm` | 50 |
| `hfhub` | 46 |
| `docker` | 35 |
| `ollama` | 28 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 652 |
| `345gs5662d34` | 551 |
| `admin` | 346 |
| `ubuntu` | 153 |
| `administrator` | 82 |
| `user` | 78 |
| `test` | 74 |
| `ftpuser` | 68 |
| `admin1` | 61 |
| `AdminGPON` | 55 |
| `a` | 55 |
| `admin2` | 52 |
| `adminuser` | 52 |
| `Asalem` | 51 |
| `Caps` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 552 |
| `345gs5662d34` | 550 |
| `123456` | 383 |
| `123` | 229 |
| `1234` | 195 |
| `admin` | 120 |
| `12345678` | 120 |
| `1` | 104 |
| `12345` | 94 |
| `password` | 92 |
| `000000` | 79 |
| `123456789` | 66 |
| `P@ssw0rd` | 64 |
| `!QAZ2wsx` | 64 |
| `0` | 62 |

### Top commands run

| command | times |
|---|---|
| `uname` | 724 |
| `echo` | 638 |
| `lscpu` | 625 |
| `crontab` | 624 |
| `cat` | 618 |
| `cd` | 617 |
| `ls` | 569 |
| `top` | 568 |
| `df` | 567 |
| `free` | 567 |
| `whoami` | 566 |
| `w` | 565 |
| `INFO` | 203 |
| `PING` | 132 |
| `canary_env` | 131 |


_Generated from first-party honeypot capture. CC BY 4.0._
