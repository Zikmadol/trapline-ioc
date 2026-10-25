# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3263 attackers** · **650,014 hostile actions** · covering 43 day(s) through 2026-10-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 190 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 237 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3220 |
| `ssh-exploit` | 1229 |
| `ssh-bruteforce` | 801 |
| `redis-exploit` | 590 |
| `mcp-abuse` | 241 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 65 |
| `litellm-key-replay` | 55 |
| `docker-abuse` | 41 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2107 |
| `redis` | 605 |
| `mcp` | 355 |
| `llamacpp` | 230 |
| `jupyter` | 146 |
| `vllm` | 137 |
| `litellm` | 128 |
| `ollama` | 107 |
| `hfhub` | 105 |
| `docker` | 100 |
| `php` | 33 |
| `ray` | 23 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1249 |
| `345gs5662d34` | 986 |
| `admin` | 679 |
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
| `1234` | 376 |
| `12345678` | 294 |
| `admin` | 254 |
| `12345` | 236 |
| `1` | 232 |
| `P@ssw0rd` | 171 |
| `admin123` | 157 |
| `password` | 155 |
| `123456789` | 119 |
| `000000` | 119 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1342 |
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
| `INFO` | 397 |
| `canary_env` | 300 |
| `PING` | 274 |


_Generated from first-party honeypot capture. CC BY 4.0._
