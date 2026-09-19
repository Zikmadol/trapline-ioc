# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**221 attackers** · **57,772 hostile actions** · covering 7 day(s) through 2026-09-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 20 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 1 |
| Stage-2 hosts named in payloads | 11 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 115 |
| `redis-exploit` | 36 |
| `mcp-abuse` | 22 |
| `ssh-exploit` | 22 |
| `llamacpp-abuse` | 5 |
| `canary-aws-key` | 3 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 137 |
| `redis` | 36 |
| `mcp` | 24 |
| `llamacpp` | 11 |
| `vllm` | 7 |
| `jupyter` | 5 |
| `litellm` | 3 |
| `ray` | 2 |
| `docker` | 2 |
| `hfhub` | 1 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 63 |
| `root` | 61 |
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
| `admin` | 29 |
| `123456` | 28 |
| `123456789` | 25 |
| `1234` | 24 |
| `12345678` | 24 |
| `000000` | 24 |
| `12345` | 19 |
| `!QAZ2wsx` | 18 |
| `123` | 17 |
| `0` | 17 |
| `0000` | 17 |
| `111111` | 17 |
| `00000000` | 16 |
| `051178` | 16 |
| `123123` | 16 |

### Top commands run

| command | times |
|---|---|
| `uname` | 31 |
| `canary_env` | 27 |
| `INFO` | 26 |
| `uptime` | 17 |
| `CONFIG` | 15 |
| `export` | 14 |
| `COMMAND` | 13 |
| `SET` | 13 |
| `FLUSHALL` | 12 |
| `SAVE` | 12 |
| `PING` | 7 |
| `nvidia-smi` | 6 |
| `echo` | 6 |
| `GET` | 5 |
| `lspci` | 5 |


_Generated from first-party honeypot capture. CC BY 4.0._
