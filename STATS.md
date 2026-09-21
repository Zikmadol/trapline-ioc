# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**502 attackers** · **114,491 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 32 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 7 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 173 |
| `ssh-bruteforce` | 162 |
| `redis-exploit` | 89 |
| `mcp-abuse` | 37 |
| `llamacpp-abuse` | 12 |
| `docker-abuse` | 4 |
| `vllm-abuse` | 3 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |
| `ollama-abuse` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 340 |
| `redis` | 91 |
| `mcp` | 43 |
| `llamacpp` | 24 |
| `vllm` | 14 |
| `jupyter` | 10 |
| `docker` | 7 |
| `hfhub` | 5 |
| `ray` | 4 |
| `litellm` | 3 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 188 |
| `345gs5662d34` | 139 |
| `admin` | 98 |
| `administrator` | 33 |
| `admin1` | 30 |
| `admin2` | 27 |
| `AdminGPON` | 26 |
| `a` | 26 |
| `aaa` | 26 |
| `admin123` | 26 |
| `adminuser` | 25 |
| `ai` | 25 |
| `Asalem` | 24 |
| `abigail` | 24 |
| `actian` | 24 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 139 |
| `3245gs5662d34` | 138 |
| `123456` | 97 |
| `123` | 50 |
| `1234` | 48 |
| `admin` | 40 |
| `000000` | 37 |
| `12345678` | 35 |
| `12345` | 32 |
| `123456789` | 29 |
| `!QAZ2wsx` | 29 |
| `0000` | 28 |
| `0` | 27 |
| `00000000` | 26 |
| `051178` | 26 |

### Top commands run

| command | times |
|---|---|
| `uname` | 185 |
| `echo` | 160 |
| `lscpu` | 157 |
| `crontab` | 155 |
| `ls` | 143 |
| `cd` | 143 |
| `cat` | 143 |
| `top` | 143 |
| `df` | 142 |
| `w` | 142 |
| `whoami` | 142 |
| `free` | 141 |
| `INFO` | 66 |
| `canary_env` | 46 |
| `CONFIG` | 37 |


_Generated from first-party honeypot capture. CC BY 4.0._
