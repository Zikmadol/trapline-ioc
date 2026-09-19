# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**222 attackers** · **57,875 hostile actions** · covering 7 day(s) through 2026-09-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 21 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 3 |
| Stage-2 hosts named in payloads | 11 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 115 |
| `redis-exploit` | 37 |
| `ssh-exploit` | 23 |
| `mcp-abuse` | 22 |
| `llamacpp-abuse` | 5 |
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
| `ssh` | 139 |
| `redis` | 38 |
| `mcp` | 25 |
| `llamacpp` | 12 |
| `vllm` | 8 |
| `jupyter` | 7 |
| `litellm` | 4 |
| `docker` | 3 |
| `ray` | 3 |
| `hfhub` | 2 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 63 |
| `root` | 62 |
| `administrator` | 21 |
| `admin1` | 18 |
| `AdminGPON` | 16 |
| `a` | 16 |
| `aaa` | 16 |
| `admin123` | 16 |
| `admin2` | 16 |
| `adminuser` | 16 |
| `ai` | 16 |
| `Asalem` | 14 |
| `Caps` | 14 |
| `abigail` | 14 |
| `actian` | 14 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 29 |
| `admin` | 29 |
| `123456789` | 25 |
| `000000` | 24 |
| `1234` | 24 |
| `12345678` | 24 |
| `12345` | 19 |
| `!QAZ2wsx` | 18 |
| `111111` | 17 |
| `123` | 17 |
| `0000` | 17 |
| `0` | 17 |
| `123123` | 16 |
| `00000000` | 16 |
| `051178` | 16 |

### Top commands run

| command | times |
|---|---|
| `uname` | 32 |
| `canary_env` | 28 |
| `INFO` | 27 |
| `uptime` | 17 |
| `CONFIG` | 15 |
| `export` | 14 |
| `COMMAND` | 13 |
| `SET` | 13 |
| `FLUSHALL` | 12 |
| `SAVE` | 12 |
| `PING` | 8 |
| `nvidia-smi` | 7 |
| `lspci` | 6 |
| `GET` | 6 |
| `echo` | 6 |


_Generated from first-party honeypot capture. CC BY 4.0._
