# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2703 attackers** · **520,577 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 191 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1458 |
| `ssh-exploit` | 1080 |
| `ssh-bruteforce` | 628 |
| `redis-exploit` | 506 |
| `mcp-abuse` | 213 |
| `llamacpp-abuse` | 66 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 31 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1770 |
| `redis` | 520 |
| `mcp` | 300 |
| `llamacpp` | 179 |
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
| `root` | 1006 |
| `345gs5662d34` | 855 |
| `admin` | 612 |
| `ubuntu` | 291 |
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
| `345gs5662d34` | 853 |
| `3245gs5662d34` | 852 |
| `123456` | 706 |
| `123` | 457 |
| `1234` | 335 |
| `12345678` | 251 |
| `admin` | 222 |
| `12345` | 211 |
| `1` | 202 |
| `password` | 151 |
| `P@ssw0rd` | 146 |
| `admin123` | 139 |
| `000000` | 110 |
| `123456789` | 105 |
| `!QAZ2wsx` | 96 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1190 |
| `cd` | 1015 |
| `cat` | 1014 |
| `echo` | 1002 |
| `crontab` | 980 |
| `lscpu` | 979 |
| `ls` | 881 |
| `free` | 880 |
| `df` | 878 |
| `top` | 878 |
| `whoami` | 877 |
| `w` | 876 |
| `INFO` | 338 |
| `canary_env` | 256 |
| `PING` | 230 |


_Generated from first-party honeypot capture. CC BY 4.0._
