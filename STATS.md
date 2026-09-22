# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**582 attackers** · **131,671 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 8 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 202 |
| `ssh-bruteforce` | 189 |
| `redis-exploit` | 106 |
| `mcp-abuse` | 39 |
| `llamacpp-abuse` | 13 |
| `docker-abuse` | 6 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 397 |
| `redis` | 109 |
| `mcp` | 46 |
| `llamacpp` | 28 |
| `vllm` | 16 |
| `jupyter` | 11 |
| `docker` | 9 |
| `hfhub` | 8 |
| `ray` | 4 |
| `litellm` | 3 |
| `ollama` | 3 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 206 |
| `345gs5662d34` | 158 |
| `admin` | 133 |
| `administrator` | 35 |
| `admin1` | 31 |
| `admin2` | 29 |
| `ubuntu` | 28 |
| `AdminGPON` | 27 |
| `a` | 27 |
| `adminuser` | 27 |
| `ai` | 27 |
| `aaa` | 26 |
| `admin123` | 26 |
| `Caps` | 25 |
| `actian` | 25 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 158 |
| `3245gs5662d34` | 156 |
| `123456` | 106 |
| `123` | 55 |
| `1234` | 55 |
| `admin` | 44 |
| `000000` | 38 |
| `12345678` | 36 |
| `12345` | 32 |
| `0000` | 30 |
| `!QAZ2wsx` | 30 |
| `123456789` | 29 |
| `0` | 29 |
| `00000000` | 27 |
| `051178` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 213 |
| `echo` | 184 |
| `lscpu` | 180 |
| `crontab` | 178 |
| `cat` | 171 |
| `cd` | 169 |
| `ls` | 164 |
| `top` | 164 |
| `df` | 163 |
| `whoami` | 163 |
| `free` | 162 |
| `w` | 162 |
| `INFO` | 79 |
| `canary_env` | 49 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
