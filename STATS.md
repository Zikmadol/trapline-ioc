# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**443 attackers** · **95,648 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 28 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 147 |
| `ssh-exploit` | 146 |
| `redis-exploit` | 79 |
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
| `ssh` | 296 |
| `redis` | 81 |
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
| `root` | 163 |
| `345gs5662d34` | 115 |
| `admin` | 86 |
| `administrator` | 29 |
| `admin1` | 26 |
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
| `345gs5662d34` | 115 |
| `3245gs5662d34` | 114 |
| `123456` | 85 |
| `123` | 45 |
| `1234` | 41 |
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
| `uname` | 157 |
| `echo` | 132 |
| `lscpu` | 129 |
| `crontab` | 127 |
| `ls` | 119 |
| `cd` | 119 |
| `cat` | 119 |
| `top` | 119 |
| `df` | 118 |
| `w` | 118 |
| `whoami` | 118 |
| `free` | 117 |
| `INFO` | 58 |
| `canary_env` | 43 |
| `CONFIG` | 33 |


_Generated from first-party honeypot capture. CC BY 4.0._
