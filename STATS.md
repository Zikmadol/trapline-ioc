# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2715 attackers** · **521,063 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 192 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1586 |
| `ssh-exploit` | 1083 |
| `ssh-bruteforce` | 629 |
| `redis-exploit` | 509 |
| `mcp-abuse` | 215 |
| `llamacpp-abuse` | 66 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 36 |
| `docker-abuse` | 31 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1775 |
| `redis` | 523 |
| `mcp` | 302 |
| `llamacpp` | 179 |
| `vllm` | 108 |
| `jupyter` | 104 |
| `litellm` | 101 |
| `hfhub` | 86 |
| `docker` | 78 |
| `ollama` | 62 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1010 |
| `345gs5662d34` | 857 |
| `admin` | 612 |
| `ubuntu` | 292 |
| `user` | 152 |
| `ftpuser` | 139 |
| `test` | 125 |
| `postgres` | 93 |
| `git` | 93 |
| `deploy` | 92 |
| `guest` | 84 |
| `administrator` | 82 |
| `oracle` | 69 |
| `ftp` | 62 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 855 |
| `3245gs5662d34` | 854 |
| `123456` | 708 |
| `123` | 457 |
| `1234` | 335 |
| `12345678` | 252 |
| `admin` | 222 |
| `12345` | 211 |
| `1` | 202 |
| `password` | 151 |
| `P@ssw0rd` | 148 |
| `admin123` | 139 |
| `000000` | 110 |
| `123456789` | 105 |
| `!QAZ2wsx` | 96 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1192 |
| `cat` | 1017 |
| `cd` | 1017 |
| `echo` | 1005 |
| `crontab` | 982 |
| `lscpu` | 981 |
| `ls` | 883 |
| `free` | 882 |
| `df` | 880 |
| `top` | 880 |
| `whoami` | 879 |
| `w` | 878 |
| `INFO` | 340 |
| `canary_env` | 258 |
| `PING` | 232 |


_Generated from first-party honeypot capture. CC BY 4.0._
