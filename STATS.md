# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1010 attackers** · **222,887 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 57 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 57 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 392 |
| `ssh-bruteforce` | 249 |
| `redis-exploit` | 214 |
| `mcp-abuse` | 71 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `litellm-key-replay` | 6 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 660 |
| `redis` | 222 |
| `mcp` | 100 |
| `llamacpp` | 66 |
| `vllm` | 38 |
| `jupyter` | 36 |
| `hfhub` | 33 |
| `docker` | 22 |
| `litellm` | 21 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 367 |
| `345gs5662d34` | 311 |
| `admin` | 201 |
| `administrator` | 62 |
| `ubuntu` | 54 |
| `admin1` | 48 |
| `aaa` | 42 |
| `AdminGPON` | 41 |
| `a` | 41 |
| `admin2` | 41 |
| `adminuser` | 41 |
| `ai` | 40 |
| `admin123` | 39 |
| `Asalem` | 38 |
| `Caps` | 38 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 311 |
| `345gs5662d34` | 311 |
| `123456` | 179 |
| `123` | 110 |
| `1234` | 90 |
| `admin` | 63 |
| `12345678` | 52 |
| `000000` | 51 |
| `12345` | 45 |
| `!QAZ2wsx` | 45 |
| `1` | 42 |
| `0000` | 42 |
| `0` | 42 |
| `password` | 41 |
| `123456789` | 41 |

### Top commands run

| command | times |
|---|---|
| `uname` | 401 |
| `echo` | 359 |
| `lscpu` | 351 |
| `crontab` | 348 |
| `cd` | 346 |
| `cat` | 346 |
| `top` | 322 |
| `ls` | 321 |
| `df` | 321 |
| `free` | 321 |
| `whoami` | 320 |
| `w` | 319 |
| `INFO` | 145 |
| `canary_env` | 90 |
| `PING` | 82 |


_Generated from first-party honeypot capture. CC BY 4.0._
