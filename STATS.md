# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3241 attackers** · **649,093 hostile actions** · covering 43 day(s) through 2026-10-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 189 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 235 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3178 |
| `ssh-exploit` | 1232 |
| `ssh-bruteforce` | 782 |
| `redis-exploit` | 587 |
| `mcp-abuse` | 240 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 64 |
| `litellm-key-replay` | 55 |
| `docker-abuse` | 40 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2091 |
| `redis` | 602 |
| `mcp` | 353 |
| `llamacpp` | 230 |
| `jupyter` | 144 |
| `vllm` | 137 |
| `litellm` | 128 |
| `ollama` | 106 |
| `hfhub` | 104 |
| `docker` | 99 |
| `php` | 32 |
| `ray` | 23 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1235 |
| `345gs5662d34` | 986 |
| `admin` | 677 |
| `ubuntu` | 323 |
| `ftpuser` | 163 |
| `user` | 163 |
| `test` | 132 |
| `git` | 109 |
| `deploy` | 108 |
| `postgres` | 104 |
| `guest` | 101 |
| `administrator` | 93 |
| `ftp` | 76 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 984 |
| `3245gs5662d34` | 978 |
| `123456` | 793 |
| `123` | 512 |
| `1234` | 375 |
| `12345678` | 292 |
| `admin` | 252 |
| `12345` | 236 |
| `1` | 232 |
| `P@ssw0rd` | 171 |
| `admin123` | 157 |
| `password` | 155 |
| `000000` | 119 |
| `123456789` | 118 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1340 |
| `cd` | 1156 |
| `cat` | 1155 |
| `echo` | 1140 |
| `crontab` | 1117 |
| `lscpu` | 1115 |
| `ls` | 1013 |
| `free` | 1012 |
| `df` | 1010 |
| `top` | 1010 |
| `whoami` | 1009 |
| `w` | 1008 |
| `INFO` | 394 |
| `canary_env` | 299 |
| `PING` | 271 |


_Generated from first-party honeypot capture. CC BY 4.0._
