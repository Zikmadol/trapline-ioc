# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**278 attackers** · **73,387 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 122 |
| `redis-exploit` | 53 |
| `ssh-exploit` | 44 |
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
| `ssh` | 167 |
| `redis` | 54 |
| `mcp` | 32 |
| `llamacpp` | 15 |
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
| `root` | 80 |
| `admin` | 70 |
| `administrator` | 25 |
| `admin1` | 23 |
| `admin2` | 21 |
| `a` | 19 |
| `aaa` | 19 |
| `admin123` | 19 |
| `adminuser` | 19 |
| `ai` | 19 |
| `AdminGPON` | 18 |
| `Asalem` | 17 |
| `Caps` | 17 |
| `admin1234` | 17 |
| `admins` | 17 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 37 |
| `1234` | 32 |
| `admin` | 31 |
| `12345678` | 31 |
| `123456789` | 29 |
| `000000` | 26 |
| `12345` | 23 |
| `!QAZ2wsx` | 23 |
| `123` | 22 |
| `0000` | 22 |
| `111111` | 21 |
| `0` | 19 |
| `!@` | 19 |
| `00000000` | 19 |
| `123123` | 18 |

### Top commands run

| command | times |
|---|---|
| `uname` | 52 |
| `INFO` | 39 |
| `canary_env` | 35 |
| `echo` | 25 |
| `CONFIG` | 23 |
| `lscpu` | 22 |
| `uptime` | 22 |
| `crontab` | 22 |
| `SET` | 20 |
| `SAVE` | 19 |
| `FLUSHALL` | 18 |
| `COMMAND` | 17 |
| `cat` | 16 |
| `ls` | 16 |
| `df` | 15 |


_Generated from first-party honeypot capture. CC BY 4.0._
