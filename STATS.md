# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**235 attackers** · **62,799 hostile actions** · covering 7 day(s) through 2026-09-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 22 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 3 |
| Stage-2 hosts named in payloads | 11 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 119 |
| `redis-exploit` | 41 |
| `mcp-abuse` | 25 |
| `ssh-exploit` | 24 |
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
| `ssh` | 144 |
| `redis` | 42 |
| `mcp` | 28 |
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
| `root` | 63 |
| `administrator` | 22 |
| `admin1` | 19 |
| `AdminGPON` | 17 |
| `a` | 17 |
| `aaa` | 17 |
| `admin123` | 17 |
| `admin2` | 17 |
| `adminuser` | 17 |
| `ai` | 17 |
| `Asalem` | 15 |
| `Caps` | 15 |
| `abigail` | 15 |
| `actian` | 15 |

### Top passwords tried

| password | tries |
|---|---|
| `admin` | 30 |
| `123456` | 29 |
| `000000` | 25 |
| `123456789` | 25 |
| `1234` | 24 |
| `12345678` | 24 |
| `12345` | 19 |
| `!QAZ2wsx` | 19 |
| `0000` | 18 |
| `0` | 18 |
| `111111` | 17 |
| `123` | 17 |
| `00000000` | 17 |
| `051178` | 17 |
| `123123` | 16 |

### Top commands run

| command | times |
|---|---|
| `uname` | 33 |
| `canary_env` | 31 |
| `INFO` | 30 |
| `CONFIG` | 18 |
| `uptime` | 18 |
| `SET` | 16 |
| `COMMAND` | 15 |
| `FLUSHALL` | 15 |
| `SAVE` | 15 |
| `export` | 14 |
| `PING` | 9 |
| `nvidia-smi` | 8 |
| `lspci` | 7 |
| `echo` | 7 |
| `nproc` | 6 |


_Generated from first-party honeypot capture. CC BY 4.0._
