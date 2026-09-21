# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**435 attackers** · **95,134 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 28 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 146 |
| `ssh-exploit` | 141 |
| `redis-exploit` | 77 |
| `mcp-abuse` | 35 |
| `llamacpp-abuse` | 10 |
| `docker-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 290 |
| `redis` | 79 |
| `mcp` | 38 |
| `llamacpp` | 20 |
| `vllm` | 11 |
| `jupyter` | 7 |
| `docker` | 6 |
| `ray` | 4 |
| `hfhub` | 3 |
| `litellm` | 3 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 159 |
| `345gs5662d34` | 110 |
| `admin` | 86 |
| `administrator` | 29 |
| `admin1` | 25 |
| `admin2` | 24 |
| `AdminGPON` | 22 |
| `a` | 22 |
| `aaa` | 22 |
| `admin123` | 22 |
| `adminuser` | 22 |
| `ai` | 22 |
| `Asalem` | 20 |
| `Caps` | 20 |
| `abigail` | 20 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 110 |
| `3245gs5662d34` | 109 |
| `123456` | 82 |
| `123` | 44 |
| `1234` | 40 |
| `admin` | 38 |
| `000000` | 33 |
| `12345678` | 33 |
| `12345` | 30 |
| `123456789` | 28 |
| `!QAZ2wsx` | 25 |
| `0000` | 24 |
| `0` | 24 |
| `00000000` | 22 |
| `051178` | 22 |

### Top commands run

| command | times |
|---|---|
| `uname` | 152 |
| `echo` | 127 |
| `lscpu` | 124 |
| `crontab` | 122 |
| `ls` | 114 |
| `cd` | 114 |
| `cat` | 114 |
| `top` | 114 |
| `df` | 113 |
| `w` | 113 |
| `whoami` | 113 |
| `free` | 112 |
| `INFO` | 56 |
| `canary_env` | 43 |
| `CONFIG` | 32 |


_Generated from first-party honeypot capture. CC BY 4.0._
