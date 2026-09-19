# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**183 attackers** · **43,406 hostile actions** · covering 6 day(s) through 2026-09-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 18 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 7 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 110 |
| `ssh-exploit` | 20 |
| `redis-exploit` | 18 |
| `mcp-abuse` | 15 |
| `llamacpp-abuse` | 5 |
| `canary-aws-key` | 3 |
| `vllm-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `llamacpp-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 130 |
| `redis` | 18 |
| `mcp` | 15 |
| `llamacpp` | 10 |
| `vllm` | 5 |
| `jupyter` | 3 |
| `litellm` | 1 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 60 |
| `root` | 60 |
| `administrator` | 19 |
| `admin1` | 16 |
| `AdminGPON` | 14 |
| `a` | 14 |
| `aaa` | 14 |
| `admin123` | 14 |
| `admin2` | 14 |
| `adminuser` | 14 |
| `ai` | 14 |
| `Asalem` | 12 |
| `Caps` | 12 |
| `abigail` | 12 |
| `actian` | 12 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 28 |
| `admin` | 28 |
| `123456789` | 24 |
| `1234` | 23 |
| `12345678` | 23 |
| `000000` | 22 |
| `12345` | 18 |
| `123` | 17 |
| `!QAZ2wsx` | 16 |
| `111111` | 16 |
| `0` | 15 |
| `0000` | 15 |
| `123123` | 15 |
| `00000000` | 14 |
| `051178` | 14 |

### Top commands run

| command | times |
|---|---|
| `uname` | 29 |
| `canary_env` | 20 |
| `INFO` | 15 |
| `uptime` | 15 |
| `export` | 14 |
| `COMMAND` | 9 |
| `CONFIG` | 9 |
| `FLUSHALL` | 8 |
| `SAVE` | 8 |
| `SET` | 8 |
| `nvidia-smi` | 4 |
| `echo` | 4 |
| `PING` | 3 |
| `chat` | 3 |
| `lspci` | 3 |


_Generated from first-party honeypot capture. CC BY 4.0._
