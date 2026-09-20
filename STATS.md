# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**284 attackers** · **78,175 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 123 |
| `redis-exploit` | 53 |
| `ssh-exploit` | 48 |
| `mcp-abuse` | 30 |
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
| `ssh` | 172 |
| `redis` | 54 |
| `mcp` | 33 |
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
| `root` | 84 |
| `admin` | 71 |
| `administrator` | 26 |
| `admin1` | 23 |
| `admin2` | 22 |
| `AdminGPON` | 20 |
| `a` | 20 |
| `aaa` | 20 |
| `admin123` | 20 |
| `adminuser` | 20 |
| `ai` | 20 |
| `Caps` | 18 |
| `abigail` | 18 |
| `adm1n` | 18 |
| `admin1234` | 18 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 37 |
| `1234` | 33 |
| `admin` | 32 |
| `12345678` | 30 |
| `123456789` | 28 |
| `000000` | 27 |
| `12345` | 23 |
| `!QAZ2wsx` | 23 |
| `0000` | 22 |
| `123` | 21 |
| `0` | 21 |
| `00000000` | 20 |
| `111111` | 19 |
| `!@` | 19 |
| `!Q2w3e4r` | 19 |

### Top commands run

| command | times |
|---|---|
| `uname` | 56 |
| `INFO` | 39 |
| `canary_env` | 36 |
| `echo` | 29 |
| `lscpu` | 26 |
| `crontab` | 26 |
| `CONFIG` | 23 |
| `uptime` | 22 |
| `cat` | 20 |
| `SET` | 20 |
| `ls` | 20 |
| `df` | 19 |
| `whoami` | 19 |
| `SAVE` | 19 |
| `cd` | 19 |


_Generated from first-party honeypot capture. CC BY 4.0._
