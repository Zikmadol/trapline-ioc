# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**248 attackers** · **69,139 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 24 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 12 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 121 |
| `redis-exploit` | 43 |
| `ssh-exploit` | 29 |
| `mcp-abuse` | 28 |
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
| `mcp` | 31 |
| `llamacpp` | 14 |
| `vllm` | 9 |
| `jupyter` | 7 |
| `docker` | 4 |
| `litellm` | 4 |
| `ray` | 3 |
| `hfhub` | 2 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 67 |
| `admin` | 66 |
| `administrator` | 23 |
| `admin1` | 21 |
| `admin2` | 19 |
| `AdminGPON` | 18 |
| `a` | 18 |
| `aaa` | 18 |
| `admin123` | 18 |
| `adminuser` | 18 |
| `ai` | 18 |
| `Asalem` | 16 |
| `Caps` | 16 |
| `abigail` | 16 |
| `actian` | 16 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 32 |
| `admin` | 30 |
| `123456789` | 27 |
| `000000` | 26 |
| `12345678` | 26 |
| `1234` | 25 |
| `!QAZ2wsx` | 21 |
| `12345` | 20 |
| `0000` | 20 |
| `0` | 19 |
| `111111` | 18 |
| `123` | 18 |
| `00000000` | 18 |
| `051178` | 18 |
| `!@` | 17 |

### Top commands run

| command | times |
|---|---|
| `uname` | 38 |
| `canary_env` | 34 |
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
