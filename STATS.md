# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2909 attackers** · **577,835 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 182 |
| Used a planted canary credential | 28 |
| Seen on more than one sensor | 205 |
| Stage-2 hosts named in payloads | 39 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2488 |
| `ssh-exploit` | 1139 |
| `ssh-bruteforce` | 657 |
| `redis-exploit` | 542 |
| `mcp-abuse` | 227 |
| `llamacpp-abuse` | 74 |
| `ollama-abuse` | 53 |
| `litellm-key-replay` | 47 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1868 |
| `redis` | 556 |
| `mcp` | 326 |
| `llamacpp` | 199 |
| `jupyter` | 128 |
| `vllm` | 124 |
| `litellm` | 113 |
| `hfhub` | 95 |
| `ollama` | 88 |
| `docker` | 82 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1064 |
| `345gs5662d34` | 907 |
| `admin` | 645 |
| `ubuntu` | 303 |
| `user` | 156 |
| `ftpuser` | 152 |
| `test` | 126 |
| `git` | 105 |
| `postgres` | 103 |
| `deploy` | 101 |
| `guest` | 92 |
| `administrator` | 90 |
| `oracle` | 72 |
| `ftp` | 67 |
| `dev` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 905 |
| `3245gs5662d34` | 901 |
| `123456` | 744 |
| `123` | 494 |
| `1234` | 354 |
| `12345678` | 273 |
| `admin` | 231 |
| `12345` | 224 |
| `1` | 215 |
| `P@ssw0rd` | 159 |
| `password` | 155 |
| `admin123` | 144 |
| `000000` | 115 |
| `123456789` | 111 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1252 |
| `cat` | 1072 |
| `cd` | 1072 |
| `echo` | 1058 |
| `crontab` | 1036 |
| `lscpu` | 1034 |
| `ls` | 934 |
| `free` | 933 |
| `df` | 931 |
| `top` | 931 |
| `whoami` | 930 |
| `w` | 929 |
| `INFO` | 365 |
| `canary_env` | 276 |
| `PING` | 250 |


_Generated from first-party honeypot capture. CC BY 4.0._
