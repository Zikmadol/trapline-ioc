# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2560 attackers** · **498,939 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 182 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1026 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 595 |
| `redis-exploit` | 487 |
| `mcp-abuse` | 198 |
| `llamacpp-abuse` | 61 |
| `litellm-key-replay` | 40 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1675 |
| `redis` | 500 |
| `mcp` | 279 |
| `llamacpp` | 168 |
| `vllm` | 105 |
| `jupyter` | 99 |
| `litellm` | 95 |
| `hfhub` | 81 |
| `docker` | 70 |
| `ollama` | 49 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 966 |
| `345gs5662d34` | 821 |
| `admin` | 561 |
| `ubuntu` | 269 |
| `user` | 144 |
| `ftpuser` | 132 |
| `test` | 122 |
| `deploy` | 87 |
| `git` | 86 |
| `postgres` | 83 |
| `guest` | 80 |
| `administrator` | 80 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 819 |
| `3245gs5662d34` | 815 |
| `123456` | 659 |
| `123` | 424 |
| `1234` | 318 |
| `12345678` | 230 |
| `admin` | 209 |
| `12345` | 196 |
| `1` | 187 |
| `password` | 142 |
| `P@ssw0rd` | 139 |
| `admin123` | 127 |
| `000000` | 107 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1132 |
| `echo` | 963 |
| `cat` | 960 |
| `cd` | 960 |
| `crontab` | 943 |
| `lscpu` | 942 |
| `ls` | 845 |
| `free` | 844 |
| `df` | 842 |
| `top` | 842 |
| `whoami` | 841 |
| `w` | 840 |
| `INFO` | 323 |
| `canary_env` | 240 |
| `PING` | 218 |


_Generated from first-party honeypot capture. CC BY 4.0._
