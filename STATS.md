# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2680 attackers** · **517,600 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 191 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1301 |
| `ssh-exploit` | 1067 |
| `ssh-bruteforce` | 622 |
| `redis-exploit` | 504 |
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
| `ssh` | 1750 |
| `redis` | 518 |
| `mcp` | 299 |
| `llamacpp` | 177 |
| `vllm` | 108 |
| `jupyter` | 103 |
| `litellm` | 101 |
| `hfhub` | 85 |
| `docker` | 77 |
| `ollama` | 59 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 996 |
| `345gs5662d34` | 847 |
| `admin` | 595 |
| `ubuntu` | 285 |
| `user` | 149 |
| `ftpuser` | 138 |
| `test` | 123 |
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
| `345gs5662d34` | 845 |
| `3245gs5662d34` | 843 |
| `123456` | 700 |
| `123` | 447 |
| `1234` | 330 |
| `12345678` | 244 |
| `admin` | 220 |
| `12345` | 204 |
| `1` | 200 |
| `password` | 144 |
| `P@ssw0rd` | 143 |
| `admin123` | 137 |
| `000000` | 110 |
| `123456789` | 105 |
| `!QAZ2wsx` | 96 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1176 |
| `cd` | 1002 |
| `cat` | 1001 |
| `echo` | 992 |
| `crontab` | 971 |
| `lscpu` | 970 |
| `ls` | 872 |
| `free` | 871 |
| `df` | 869 |
| `top` | 869 |
| `whoami` | 868 |
| `w` | 867 |
| `INFO` | 336 |
| `canary_env` | 255 |
| `PING` | 229 |


_Generated from first-party honeypot capture. CC BY 4.0._
