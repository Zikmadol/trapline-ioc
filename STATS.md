# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**881 attackers** · **180,309 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 344 |
| `ssh-bruteforce` | 229 |
| `redis-exploit` | 184 |
| `mcp-abuse` | 60 |
| `llamacpp-abuse` | 18 |
| `ollama-abuse` | 9 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 589 |
| `redis` | 190 |
| `mcp` | 81 |
| `llamacpp` | 55 |
| `vllm` | 28 |
| `jupyter` | 26 |
| `hfhub` | 20 |
| `docker` | 18 |
| `ollama` | 11 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 319 |
| `345gs5662d34` | 273 |
| `admin` | 177 |
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
| `345gs5662d34` | 273 |
| `3245gs5662d34` | 272 |
| `123456` | 158 |
| `123` | 96 |
| `1234` | 77 |
| `admin` | 60 |
| `12345678` | 46 |
| `000000` | 44 |
| `12345` | 40 |
| `123456789` | 38 |
| `!QAZ2wsx` | 38 |
| `password` | 37 |
| `0000` | 37 |
| `1` | 35 |
| `0` | 35 |

### Top commands run

| command | times |
|---|---|
| `uname` | 351 |
| `echo` | 315 |
| `lscpu` | 307 |
| `crontab` | 304 |
| `cat` | 304 |
| `cd` | 303 |
| `top` | 283 |
| `ls` | 282 |
| `df` | 282 |
| `free` | 282 |
| `whoami` | 281 |
| `w` | 280 |
| `INFO` | 126 |
| `canary_env` | 74 |
| `PING` | 67 |


_Generated from first-party honeypot capture. CC BY 4.0._
