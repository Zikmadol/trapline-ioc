# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**227 attackers** · **58,724 hostile actions** · covering 7 day(s) through 2026-09-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 22 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 3 |
| Stage-2 hosts named in payloads | 11 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 116 |
| `redis-exploit` | 38 |
| `ssh-exploit` | 24 |
| `mcp-abuse` | 23 |
| `llamacpp-abuse` | 6 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |
| `docker-abuse` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 141 |
| `redis` | 39 |
| `mcp` | 26 |
| `llamacpp` | 13 |
| `vllm` | 9 |
| `jupyter` | 7 |
| `litellm` | 4 |
| `docker` | 3 |
| `ray` | 3 |
| `hfhub` | 2 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 64 |
| `root` | 62 |
| `administrator` | 21 |
| `admin1` | 18 |
| `a` | 17 |
| `adminuser` | 17 |
| `AdminGPON` | 16 |
| `aaa` | 16 |
| `admin123` | 16 |
| `admin2` | 16 |
| `ai` | 16 |
| `abigail` | 15 |
| `Asalem` | 14 |
| `Caps` | 14 |
| `actian` | 14 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 30 |
| `admin` | 29 |
| `123456789` | 26 |
| `1234` | 25 |
| `12345678` | 25 |
| `000000` | 24 |
| `12345` | 20 |
| `!QAZ2wsx` | 19 |
| `111111` | 18 |
| `123` | 18 |
| `0000` | 18 |
| `123123` | 17 |
| `0` | 17 |
| `00000000` | 17 |
| `!Q2w3e4r` | 16 |

### Top commands run

| command | times |
|---|---|
| `uname` | 33 |
| `canary_env` | 29 |
| `INFO` | 28 |
| `uptime` | 18 |
| `CONFIG` | 16 |
| `COMMAND` | 14 |
| `SET` | 14 |
| `export` | 14 |
| `FLUSHALL` | 13 |
| `SAVE` | 13 |
| `PING` | 8 |
| `nvidia-smi` | 8 |
| `lspci` | 7 |
| `echo` | 7 |
| `nproc` | 6 |


_Generated from first-party honeypot capture. CC BY 4.0._
