# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2277 attackers** · **455,708 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 13 |
| Seen on more than one sensor | 162 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 931 |
| `ssh-bruteforce` | 527 |
| `redis-exploit` | 425 |
| `canary-aws-key` | 190 |
| `mcp-abuse` | 179 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 33 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1504 |
| `redis` | 438 |
| `mcp` | 246 |
| `llamacpp` | 138 |
| `vllm` | 87 |
| `jupyter` | 86 |
| `litellm` | 77 |
| `hfhub` | 69 |
| `docker` | 59 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 860 |
| `345gs5662d34` | 742 |
| `admin` | 494 |
| `ubuntu` | 241 |
| `user` | 123 |
| `ftpuser` | 112 |
| `test` | 108 |
| `administrator` | 79 |
| `git` | 77 |
| `postgres` | 75 |
| `guest` | 69 |
| `deploy` | 68 |
| `admin1` | 59 |
| `oracle` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 741 |
| `3245gs5662d34` | 738 |
| `123456` | 567 |
| `123` | 362 |
| `1234` | 282 |
| `12345678` | 185 |
| `admin` | 182 |
| `12345` | 178 |
| `1` | 160 |
| `password` | 119 |
| `P@ssw0rd` | 113 |
| `admin123` | 108 |
| `000000` | 98 |
| `123456789` | 95 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1017 |
| `echo` | 868 |
| `cd` | 866 |
| `cat` | 865 |
| `crontab` | 849 |
| `lscpu` | 849 |
| `ls` | 762 |
| `free` | 761 |
| `top` | 761 |
| `df` | 760 |
| `whoami` | 759 |
| `w` | 758 |
| `INFO` | 285 |
| `canary_env` | 215 |
| `PING` | 192 |


_Generated from first-party honeypot capture. CC BY 4.0._
