# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**511 attackers** · **116,954 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 32 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 7 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 180 |
| `ssh-bruteforce` | 161 |
| `redis-exploit` | 92 |
| `mcp-abuse` | 37 |
| `llamacpp-abuse` | 12 |
| `docker-abuse` | 4 |
| `vllm-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 346 |
| `redis` | 94 |
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
| `root` | 192 |
| `345gs5662d34` | 144 |
| `admin` | 100 |
| `administrator` | 33 |
| `admin1` | 30 |
| `admin2` | 28 |
| `AdminGPON` | 26 |
| `a` | 26 |
| `aaa` | 26 |
| `admin123` | 26 |
| `adminuser` | 26 |
| `ai` | 26 |
| `Asalem` | 24 |
| `Caps` | 24 |
| `abigail` | 24 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 144 |
| `3245gs5662d34` | 143 |
| `123456` | 101 |
| `123` | 51 |
| `1234` | 50 |
| `admin` | 40 |
| `000000` | 37 |
| `12345678` | 35 |
| `12345` | 32 |
| `123456789` | 29 |
| `0000` | 29 |
| `!QAZ2wsx` | 29 |
| `0` | 28 |
| `00000000` | 26 |
| `051178` | 26 |

### Top commands run

| command | times |
|---|---|
| `uname` | 191 |
| `echo` | 167 |
| `lscpu` | 163 |
| `crontab` | 161 |
| `cat` | 150 |
| `ls` | 149 |
| `cd` | 149 |
| `top` | 149 |
| `df` | 148 |
| `w` | 148 |
| `whoami` | 148 |
| `free` | 147 |
| `INFO` | 69 |
| `canary_env` | 46 |
| `CONFIG` | 39 |


_Generated from first-party honeypot capture. CC BY 4.0._
