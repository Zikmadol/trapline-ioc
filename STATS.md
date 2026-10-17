# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2608 attackers** · **504,608 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 186 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1041 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 606 |
| `redis-exploit` | 493 |
| `mcp-abuse` | 204 |
| `llamacpp-abuse` | 63 |
| `litellm-key-replay` | 42 |
| `ollama-abuse` | 29 |
| `docker-abuse` | 28 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1704 |
| `redis` | 507 |
| `mcp` | 287 |
| `llamacpp` | 170 |
| `vllm` | 106 |
| `jupyter` | 101 |
| `litellm` | 97 |
| `hfhub` | 81 |
| `docker` | 72 |
| `ollama` | 54 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 975 |
| `345gs5662d34` | 825 |
| `admin` | 572 |
| `ubuntu` | 276 |
| `user` | 147 |
| `ftpuser` | 135 |
| `test` | 122 |
| `git` | 88 |
| `deploy` | 87 |
| `postgres` | 85 |
| `guest` | 81 |
| `administrator` | 80 |
| `oracle` | 66 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 823 |
| `3245gs5662d34` | 819 |
| `123456` | 673 |
| `123` | 436 |
| `1234` | 322 |
| `12345678` | 235 |
| `admin` | 213 |
| `12345` | 199 |
| `1` | 190 |
| `password` | 143 |
| `P@ssw0rd` | 140 |
| `admin123` | 133 |
| `000000` | 108 |
| `123456789` | 102 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1147 |
| `cd` | 974 |
| `cat` | 973 |
| `echo` | 967 |
| `crontab` | 947 |
| `lscpu` | 946 |
| `ls` | 849 |
| `free` | 848 |
| `df` | 846 |
| `top` | 846 |
| `whoami` | 845 |
| `w` | 844 |
| `INFO` | 328 |
| `canary_env` | 247 |
| `PING` | 222 |


_Generated from first-party honeypot capture. CC BY 4.0._
