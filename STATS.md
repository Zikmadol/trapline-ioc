# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2811 attackers** · **542,355 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 176 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 198 |
| Stage-2 hosts named in payloads | 38 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2168 |
| `ssh-exploit` | 1112 |
| `ssh-bruteforce` | 645 |
| `redis-exploit` | 525 |
| `mcp-abuse` | 220 |
| `llamacpp-abuse` | 73 |
| `litellm-key-replay` | 45 |
| `ollama-abuse` | 42 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 23 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1824 |
| `redis` | 539 |
| `mcp` | 312 |
| `llamacpp` | 192 |
| `jupyter` | 117 |
| `vllm` | 110 |
| `litellm` | 108 |
| `hfhub` | 91 |
| `docker` | 82 |
| `ollama` | 70 |
| `ray` | 15 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1039 |
| `345gs5662d34` | 884 |
| `admin` | 631 |
| `ubuntu` | 302 |
| `user` | 155 |
| `ftpuser` | 146 |
| `test` | 128 |
| `postgres` | 102 |
| `git` | 99 |
| `deploy` | 95 |
| `guest` | 88 |
| `administrator` | 87 |
| `oracle` | 72 |
| `dev` | 65 |
| `ftp` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 882 |
| `3245gs5662d34` | 880 |
| `123456` | 730 |
| `123` | 482 |
| `1234` | 346 |
| `12345678` | 270 |
| `admin` | 227 |
| `12345` | 222 |
| `1` | 212 |
| `P@ssw0rd` | 157 |
| `password` | 152 |
| `admin123` | 143 |
| `000000` | 112 |
| `123456789` | 109 |
| `!QAZ2wsx` | 98 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1225 |
| `cat` | 1048 |
| `cd` | 1048 |
| `echo` | 1032 |
| `crontab` | 1010 |
| `lscpu` | 1008 |
| `ls` | 910 |
| `free` | 909 |
| `df` | 907 |
| `top` | 907 |
| `whoami` | 906 |
| `w` | 905 |
| `INFO` | 353 |
| `canary_env` | 268 |
| `PING` | 240 |


_Generated from first-party honeypot capture. CC BY 4.0._
