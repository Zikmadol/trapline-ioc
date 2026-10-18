# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2674 attackers** · **517,247 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 190 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1261 |
| `ssh-exploit` | 1064 |
| `ssh-bruteforce` | 622 |
| `redis-exploit` | 501 |
| `mcp-abuse` | 212 |
| `llamacpp-abuse` | 65 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 31 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1746 |
| `redis` | 515 |
| `mcp` | 297 |
| `llamacpp` | 176 |
| `vllm` | 107 |
| `jupyter` | 102 |
| `litellm` | 100 |
| `hfhub` | 84 |
| `docker` | 76 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 994 |
| `345gs5662d34` | 845 |
| `admin` | 594 |
| `ubuntu` | 285 |
| `user` | 148 |
| `ftpuser` | 138 |
| `test` | 122 |
| `deploy` | 92 |
| `postgres` | 90 |
| `git` | 89 |
| `guest` | 83 |
| `administrator` | 82 |
| `oracle` | 69 |
| `ftp` | 61 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 843 |
| `3245gs5662d34` | 840 |
| `123456` | 696 |
| `123` | 446 |
| `1234` | 330 |
| `12345678` | 244 |
| `admin` | 220 |
| `12345` | 204 |
| `1` | 199 |
| `password` | 144 |
| `P@ssw0rd` | 142 |
| `admin123` | 137 |
| `000000` | 110 |
| `123456789` | 105 |
| `!QAZ2wsx` | 96 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1173 |
| `cd` | 999 |
| `cat` | 998 |
| `echo` | 989 |
| `crontab` | 968 |
| `lscpu` | 967 |
| `ls` | 869 |
| `free` | 868 |
| `df` | 866 |
| `top` | 866 |
| `whoami` | 865 |
| `w` | 864 |
| `INFO` | 333 |
| `canary_env` | 255 |
| `PING` | 226 |


_Generated from first-party honeypot capture. CC BY 4.0._
