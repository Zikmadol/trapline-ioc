# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**938 attackers** · **194,936 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 51 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 39 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 368 |
| `ssh-bruteforce` | 237 |
| `redis-exploit` | 199 |
| `mcp-abuse` | 64 |
| `llamacpp-abuse` | 19 |
| `ollama-abuse` | 10 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 621 |
| `redis` | 205 |
| `mcp` | 88 |
| `llamacpp` | 59 |
| `vllm` | 33 |
| `jupyter` | 29 |
| `hfhub` | 24 |
| `docker` | 18 |
| `ollama` | 12 |
| `litellm` | 10 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 340 |
| `345gs5662d34` | 291 |
| `admin` | 186 |
| `administrator` | 58 |
| `ubuntu` | 52 |
| `admin1` | 45 |
| `aaa` | 39 |
| `admin2` | 38 |
| `a` | 37 |
| `adminuser` | 37 |
| `ai` | 37 |
| `AdminGPON` | 36 |
| `Asalem` | 34 |
| `Caps` | 34 |
| `actian` | 34 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 291 |
| `3245gs5662d34` | 290 |
| `123456` | 165 |
| `123` | 102 |
| `1234` | 85 |
| `admin` | 62 |
| `12345678` | 48 |
| `000000` | 46 |
| `12345` | 42 |
| `!QAZ2wsx` | 41 |
| `123456789` | 40 |
| `0000` | 40 |
| `password` | 39 |
| `1` | 38 |
| `0` | 38 |

### Top commands run

| command | times |
|---|---|
| `uname` | 376 |
| `echo` | 336 |
| `lscpu` | 328 |
| `crontab` | 325 |
| `cat` | 325 |
| `cd` | 324 |
| `top` | 301 |
| `ls` | 300 |
| `df` | 300 |
| `free` | 300 |
| `whoami` | 299 |
| `w` | 298 |
| `INFO` | 136 |
| `canary_env` | 80 |
| `PING` | 73 |


_Generated from first-party honeypot capture. CC BY 4.0._
