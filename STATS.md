# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**195 attackers** · **56,785 hostile actions** · covering 7 day(s) through 2026-09-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 20 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 8 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 111 |
| `redis-exploit` | 24 |
| `ssh-exploit` | 22 |
| `mcp-abuse` | 16 |
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
| `ssh` | 133 |
| `redis` | 24 |
| `mcp` | 17 |
| `llamacpp` | 10 |
| `vllm` | 6 |
| `jupyter` | 4 |
| `litellm` | 2 |
| `ray` | 1 |
| `ollama` | 1 |
| `docker` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 62 |
| `root` | 60 |
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
| `123456` | 28 |
| `admin` | 27 |
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
| `canary_env` | 21 |
| `INFO` | 19 |
| `uptime` | 17 |
| `export` | 14 |
| `CONFIG` | 11 |
| `COMMAND` | 10 |
| `SET` | 10 |
| `FLUSHALL` | 9 |
| `SAVE` | 9 |
| `PING` | 6 |
| `nvidia-smi` | 6 |
| `echo` | 6 |
| `lspci` | 5 |
| `nproc` | 4 |


_Generated from first-party honeypot capture. CC BY 4.0._
