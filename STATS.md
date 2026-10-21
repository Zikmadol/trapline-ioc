# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2968 attackers** · **585,564 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 183 |
| Used a planted canary credential | 29 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2584 |
| `ssh-exploit` | 1171 |
| `ssh-bruteforce` | 664 |
| `redis-exploit` | 547 |
| `mcp-abuse` | 231 |
| `llamacpp-abuse` | 76 |
| `ollama-abuse` | 55 |
| `litellm-key-replay` | 48 |
| `docker-abuse` | 35 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1909 |
| `redis` | 561 |
| `mcp` | 330 |
| `llamacpp` | 204 |
| `jupyter` | 130 |
| `vllm` | 125 |
| `litellm` | 117 |
| `hfhub` | 97 |
| `ollama` | 92 |
| `docker` | 85 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1090 |
| `345gs5662d34` | 936 |
| `admin` | 651 |
| `ubuntu` | 306 |
| `user` | 158 |
| `ftpuser` | 155 |
| `test` | 129 |
| `git` | 107 |
| `postgres` | 105 |
| `deploy` | 103 |
| `guest` | 95 |
| `administrator` | 91 |
| `oracle` | 72 |
| `ftp` | 69 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 934 |
| `3245gs5662d34` | 929 |
| `123456` | 763 |
| `123` | 503 |
| `1234` | 362 |
| `12345678` | 278 |
| `admin` | 234 |
| `12345` | 228 |
| `1` | 220 |
| `P@ssw0rd` | 162 |
| `password` | 158 |
| `admin123` | 146 |
| `000000` | 116 |
| `123456789` | 112 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1282 |
| `cat` | 1102 |
| `cd` | 1102 |
| `echo` | 1087 |
| `crontab` | 1065 |
| `lscpu` | 1063 |
| `ls` | 963 |
| `free` | 962 |
| `df` | 960 |
| `top` | 960 |
| `whoami` | 959 |
| `w` | 958 |
| `INFO` | 369 |
| `canary_env` | 284 |
| `PING` | 252 |


_Generated from first-party honeypot capture. CC BY 4.0._
