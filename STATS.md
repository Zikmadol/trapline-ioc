# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**240 attackers** · **64,031 hostile actions** · covering 7 day(s) through 2026-09-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 23 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 3 |
| Stage-2 hosts named in payloads | 12 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 121 |
| `redis-exploit` | 42 |
| `mcp-abuse` | 25 |
| `ssh-exploit` | 25 |
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
| `ssh` | 147 |
| `redis` | 43 |
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
| `root` | 65 |
| `admin` | 65 |
| `administrator` | 22 |
| `admin1` | 20 |
| `admin2` | 18 |
| `AdminGPON` | 17 |
| `a` | 17 |
| `aaa` | 17 |
| `admin123` | 17 |
| `adminuser` | 17 |
| `ai` | 17 |
| `admin1234` | 16 |
| `Asalem` | 15 |
| `Caps` | 15 |
| `abigail` | 15 |

### Top passwords tried

| password | tries |
|---|---|
| `admin` | 31 |
| `123456` | 30 |
| `123456789` | 27 |
| `000000` | 25 |
| `1234` | 25 |
| `12345678` | 25 |
| `12345` | 20 |
| `!QAZ2wsx` | 20 |
| `0000` | 19 |
| `111111` | 18 |
| `123` | 18 |
| `0` | 18 |
| `00000000` | 17 |
| `051178` | 17 |
| `123123` | 16 |

### Top commands run

| command | times |
|---|---|
| `uname` | 35 |
| `canary_env` | 31 |
| `INFO` | 31 |
| `CONFIG` | 19 |
| `uptime` | 19 |
| `SET` | 17 |
| `SAVE` | 16 |
| `COMMAND` | 15 |
| `FLUSHALL` | 15 |
| `export` | 14 |
| `PING` | 9 |
| `nvidia-smi` | 9 |
| `lspci` | 8 |
| `echo` | 8 |
| `nproc` | 7 |


_Generated from first-party honeypot capture. CC BY 4.0._
