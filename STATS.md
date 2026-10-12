# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2238 attackers** · **451,779 hostile actions** · covering 30 day(s) through 2026-10-12

| signal | count |
|---|---|
| GPU / AI-hardware probing | 154 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 158 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 923 |
| `ssh-bruteforce` | 520 |
| `redis-exploit` | 419 |
| `mcp-abuse` | 170 |
| `llamacpp-abuse` | 47 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 19 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1489 |
| `redis` | 431 |
| `mcp` | 235 |
| `llamacpp` | 133 |
| `vllm` | 87 |
| `jupyter` | 83 |
| `litellm` | 73 |
| `hfhub` | 69 |
| `docker` | 54 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 851 |
| `345gs5662d34` | 732 |
| `admin` | 490 |
| `ubuntu` | 237 |
| `user` | 123 |
| `ftpuser` | 110 |
| `test` | 108 |
| `administrator` | 77 |
| `git` | 74 |
| `postgres` | 73 |
| `guest` | 68 |
| `deploy` | 67 |
| `admin1` | 59 |
| `oracle` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 731 |
| `3245gs5662d34` | 728 |
| `123456` | 557 |
| `123` | 355 |
| `1234` | 278 |
| `12345678` | 184 |
| `admin` | 179 |
| `12345` | 174 |
| `1` | 154 |
| `password` | 119 |
| `P@ssw0rd` | 111 |
| `admin123` | 107 |
| `000000` | 98 |
| `123456789` | 89 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1006 |
| `echo` | 856 |
| `cd` | 856 |
| `cat` | 855 |
| `crontab` | 838 |
| `lscpu` | 838 |
| `ls` | 752 |
| `free` | 751 |
| `top` | 751 |
| `df` | 750 |
| `whoami` | 749 |
| `w` | 748 |
| `INFO` | 278 |
| `canary_env` | 205 |
| `PING` | 190 |


_Generated from first-party honeypot capture. CC BY 4.0._
