# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2720 attackers** · **521,876 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 192 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1731 |
| `ssh-exploit` | 1085 |
| `ssh-bruteforce` | 630 |
| `redis-exploit` | 509 |
| `mcp-abuse` | 216 |
| `llamacpp-abuse` | 66 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 36 |
| `docker-abuse` | 32 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1778 |
| `redis` | 523 |
| `mcp` | 303 |
| `llamacpp` | 179 |
| `vllm` | 108 |
| `jupyter` | 104 |
| `litellm` | 101 |
| `hfhub` | 86 |
| `docker` | 79 |
| `ollama` | 62 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1012 |
| `345gs5662d34` | 859 |
| `admin` | 613 |
| `ubuntu` | 292 |
| `user` | 153 |
| `ftpuser` | 140 |
| `test` | 125 |
| `deploy` | 94 |
| `postgres` | 93 |
| `git` | 93 |
| `guest` | 85 |
| `administrator` | 82 |
| `oracle` | 70 |
| `ftp` | 63 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 857 |
| `3245gs5662d34` | 856 |
| `123456` | 709 |
| `123` | 460 |
| `1234` | 337 |
| `12345678` | 253 |
| `admin` | 223 |
| `12345` | 214 |
| `1` | 203 |
| `password` | 151 |
| `P@ssw0rd` | 149 |
| `admin123` | 140 |
| `000000` | 110 |
| `123456789` | 105 |
| `!QAZ2wsx` | 96 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1194 |
| `cat` | 1019 |
| `cd` | 1019 |
| `echo` | 1007 |
| `crontab` | 984 |
| `lscpu` | 983 |
| `ls` | 885 |
| `free` | 884 |
| `df` | 882 |
| `top` | 882 |
| `whoami` | 881 |
| `w` | 880 |
| `INFO` | 340 |
| `canary_env` | 259 |
| `PING` | 232 |


_Generated from first-party honeypot capture. CC BY 4.0._
