# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2534 attackers** · **489,571 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 168 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 179 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1016 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 586 |
| `redis-exploit` | 482 |
| `mcp-abuse` | 197 |
| `llamacpp-abuse` | 59 |
| `litellm-key-replay` | 40 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1655 |
| `redis` | 496 |
| `mcp` | 276 |
| `llamacpp` | 166 |
| `vllm` | 104 |
| `jupyter` | 97 |
| `litellm` | 95 |
| `hfhub` | 81 |
| `docker` | 69 |
| `ollama` | 48 |
| `ray` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 957 |
| `345gs5662d34` | 815 |
| `admin` | 555 |
| `ubuntu` | 266 |
| `user` | 143 |
| `ftpuser` | 128 |
| `test` | 123 |
| `git` | 85 |
| `deploy` | 85 |
| `postgres` | 82 |
| `administrator` | 80 |
| `guest` | 79 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 814 |
| `3245gs5662d34` | 809 |
| `123456` | 651 |
| `123` | 416 |
| `1234` | 315 |
| `12345678` | 224 |
| `admin` | 208 |
| `12345` | 195 |
| `1` | 184 |
| `password` | 140 |
| `P@ssw0rd` | 134 |
| `admin123` | 127 |
| `000000` | 103 |
| `123456789` | 100 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1121 |
| `echo` | 955 |
| `cd` | 953 |
| `cat` | 952 |
| `crontab` | 935 |
| `lscpu` | 934 |
| `ls` | 838 |
| `free` | 837 |
| `df` | 835 |
| `top` | 835 |
| `whoami` | 834 |
| `w` | 833 |
| `INFO` | 320 |
| `canary_env` | 238 |
| `PING` | 215 |


_Generated from first-party honeypot capture. CC BY 4.0._
