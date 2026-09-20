# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**259 attackers** · **69,618 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 24 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 13 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 122 |
| `redis-exploit` | 48 |
| `ssh-exploit` | 32 |
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
| `ssh` | 155 |
| `redis` | 49 |
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
| `root` | 71 |
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
| `123456` | 33 |
| `admin` | 30 |
| `123456789` | 27 |
| `000000` | 26 |
| `1234` | 26 |
| `12345678` | 26 |
| `12345` | 21 |
| `!QAZ2wsx` | 21 |
| `0000` | 20 |
| `123` | 19 |
| `0` | 19 |
| `111111` | 18 |
| `00000000` | 18 |
| `051178` | 18 |
| `!@` | 17 |

### Top commands run

| command | times |
|---|---|
| `uname` | 41 |
| `INFO` | 36 |
| `canary_env` | 35 |
| `CONFIG` | 21 |
| `uptime` | 20 |
| `SET` | 19 |
| `SAVE` | 18 |
| `FLUSHALL` | 17 |
| `COMMAND` | 16 |
| `export` | 14 |
| `echo` | 14 |
| `lscpu` | 11 |
| `crontab` | 11 |
| `PING` | 10 |
| `nvidia-smi` | 10 |


_Generated from first-party honeypot capture. CC BY 4.0._
