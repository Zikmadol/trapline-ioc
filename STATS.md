# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**246 attackers** · **64,986 hostile actions** · covering 7 day(s) through 2026-09-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 24 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 4 |
| Stage-2 hosts named in payloads | 12 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 121 |
| `redis-exploit` | 43 |
| `ssh-exploit` | 29 |
| `mcp-abuse` | 26 |
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
| `ssh` | 151 |
| `redis` | 44 |
| `mcp` | 29 |
| `llamacpp` | 14 |
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
| `root` | 67 |
| `admin` | 66 |
| `administrator` | 22 |
| `admin1` | 21 |
| `aaa` | 18 |
| `admin123` | 18 |
| `admin2` | 18 |
| `AdminGPON` | 17 |
| `a` | 17 |
| `adminuser` | 17 |
| `ai` | 17 |
| `actian` | 16 |
| `admin1234` | 16 |
| `Asalem` | 15 |
| `Caps` | 15 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 33 |
| `admin` | 31 |
| `12345678` | 27 |
| `123456789` | 27 |
| `1234` | 26 |
| `000000` | 25 |
| `12345` | 21 |
| `!QAZ2wsx` | 21 |
| `111111` | 19 |
| `123` | 19 |
| `0000` | 19 |
| `0` | 18 |
| `051178` | 18 |
| `123123` | 17 |
| `00000000` | 17 |

### Top commands run

| command | times |
|---|---|
| `uname` | 38 |
| `canary_env` | 32 |
| `INFO` | 32 |
| `uptime` | 20 |
| `CONFIG` | 19 |
| `SET` | 17 |
| `SAVE` | 16 |
| `COMMAND` | 15 |
| `FLUSHALL` | 15 |
| `export` | 14 |
| `echo` | 11 |
| `PING` | 10 |
| `nvidia-smi` | 10 |
| `lspci` | 9 |
| `lscpu` | 8 |


_Generated from first-party honeypot capture. CC BY 4.0._
