# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**889 attackers** · **180,616 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 346 |
| `ssh-bruteforce` | 231 |
| `redis-exploit` | 184 |
| `mcp-abuse` | 62 |
| `llamacpp-abuse` | 19 |
| `ollama-abuse` | 9 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 593 |
| `redis` | 190 |
| `mcp` | 83 |
| `llamacpp` | 56 |
| `vllm` | 29 |
| `jupyter` | 26 |
| `hfhub` | 20 |
| `docker` | 18 |
| `ollama` | 11 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 323 |
| `345gs5662d34` | 276 |
| `admin` | 178 |
| `administrator` | 53 |
| `ubuntu` | 45 |
| `admin1` | 42 |
| `aaa` | 36 |
| `admin2` | 35 |
| `AdminGPON` | 34 |
| `a` | 34 |
| `adminuser` | 34 |
| `ai` | 34 |
| `Asalem` | 32 |
| `admin123` | 32 |
| `Caps` | 31 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 276 |
| `3245gs5662d34` | 275 |
| `123456` | 158 |
| `123` | 96 |
| `1234` | 78 |
| `admin` | 61 |
| `12345678` | 46 |
| `000000` | 44 |
| `12345` | 40 |
| `123456789` | 40 |
| `!QAZ2wsx` | 38 |
| `password` | 37 |
| `0000` | 37 |
| `1` | 36 |
| `0` | 35 |

### Top commands run

| command | times |
|---|---|
| `uname` | 353 |
| `echo` | 317 |
| `lscpu` | 309 |
| `crontab` | 306 |
| `cd` | 306 |
| `cat` | 306 |
| `top` | 285 |
| `ls` | 284 |
| `df` | 284 |
| `free` | 284 |
| `whoami` | 283 |
| `w` | 282 |
| `INFO` | 126 |
| `canary_env` | 78 |
| `PING` | 67 |


_Generated from first-party honeypot capture. CC BY 4.0._
