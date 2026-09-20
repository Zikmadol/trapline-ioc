# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**264 attackers** · **69,796 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 25 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 13 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 121 |
| `redis-exploit` | 52 |
| `ssh-exploit` | 34 |
| `mcp-abuse` | 29 |
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
| `ssh` | 156 |
| `redis` | 53 |
| `mcp` | 32 |
| `llamacpp` | 14 |
| `vllm` | 9 |
| `jupyter` | 7 |
| `docker` | 4 |
| `litellm` | 4 |
| `ray` | 4 |
| `hfhub` | 3 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 72 |
| `admin` | 67 |
| `administrator` | 24 |
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
| `123456` | 34 |
| `admin` | 30 |
| `12345678` | 28 |
| `123456789` | 28 |
| `1234` | 27 |
| `000000` | 26 |
| `12345` | 22 |
| `!QAZ2wsx` | 21 |
| `123` | 20 |
| `0000` | 20 |
| `111111` | 19 |
| `0` | 19 |
| `00000000` | 18 |
| `051178` | 18 |
| `123123` | 17 |

### Top commands run

| command | times |
|---|---|
| `uname` | 42 |
| `INFO` | 38 |
| `canary_env` | 35 |
| `CONFIG` | 22 |
| `uptime` | 20 |
| `SET` | 19 |
| `SAVE` | 18 |
| `FLUSHALL` | 17 |
| `COMMAND` | 16 |
| `export` | 15 |
| `echo` | 15 |
| `PING` | 12 |
| `lscpu` | 12 |
| `crontab` | 12 |
| `nvidia-smi` | 10 |


_Generated from first-party honeypot capture. CC BY 4.0._
