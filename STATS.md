# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**453 attackers** · **95,887 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 28 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 150 |
| `ssh-exploit` | 150 |
| `redis-exploit` | 81 |
| `mcp-abuse` | 36 |
| `llamacpp-abuse` | 10 |
| `docker-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 303 |
| `redis` | 83 |
| `mcp` | 39 |
| `llamacpp` | 20 |
| `vllm` | 11 |
| `jupyter` | 8 |
| `docker` | 6 |
| `ray` | 4 |
| `hfhub` | 3 |
| `litellm` | 3 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 168 |
| `345gs5662d34` | 119 |
| `admin` | 88 |
| `administrator` | 29 |
| `admin1` | 26 |
| `admin2` | 24 |
| `AdminGPON` | 22 |
| `a` | 22 |
| `aaa` | 22 |
| `admin123` | 22 |
| `adminuser` | 22 |
| `ai` | 22 |
| `Asalem` | 20 |
| `Caps` | 20 |
| `abigail` | 20 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 119 |
| `3245gs5662d34` | 118 |
| `123456` | 87 |
| `123` | 45 |
| `1234` | 43 |
| `admin` | 40 |
| `12345678` | 34 |
| `000000` | 33 |
| `12345` | 31 |
| `123456789` | 29 |
| `!QAZ2wsx` | 25 |
| `0000` | 24 |
| `0` | 24 |
| `00000000` | 22 |
| `051178` | 22 |

### Top commands run

| command | times |
|---|---|
| `uname` | 161 |
| `echo` | 136 |
| `lscpu` | 133 |
| `crontab` | 131 |
| `ls` | 123 |
| `cd` | 123 |
| `cat` | 123 |
| `top` | 123 |
| `df` | 122 |
| `w` | 122 |
| `whoami` | 122 |
| `free` | 121 |
| `INFO` | 59 |
| `canary_env` | 44 |
| `CONFIG` | 33 |


_Generated from first-party honeypot capture. CC BY 4.0._
