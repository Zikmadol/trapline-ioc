# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2866 attackers** · **570,921 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 180 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 200 |
| Stage-2 hosts named in payloads | 39 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2359 |
| `ssh-exploit` | 1125 |
| `ssh-bruteforce` | 653 |
| `redis-exploit` | 537 |
| `mcp-abuse` | 224 |
| `llamacpp-abuse` | 73 |
| `litellm-key-replay` | 47 |
| `ollama-abuse` | 45 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 31 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1847 |
| `redis` | 551 |
| `mcp` | 318 |
| `llamacpp` | 195 |
| `jupyter` | 126 |
| `vllm` | 122 |
| `litellm` | 112 |
| `hfhub` | 94 |
| `docker` | 82 |
| `ollama` | 77 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1051 |
| `345gs5662d34` | 896 |
| `admin` | 640 |
| `ubuntu` | 302 |
| `user` | 155 |
| `ftpuser` | 152 |
| `test` | 126 |
| `git` | 104 |
| `postgres` | 102 |
| `deploy` | 99 |
| `guest` | 92 |
| `administrator` | 89 |
| `oracle` | 72 |
| `ftp` | 66 |
| `dev` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 894 |
| `3245gs5662d34` | 891 |
| `123456` | 739 |
| `123` | 491 |
| `1234` | 348 |
| `12345678` | 272 |
| `admin` | 229 |
| `12345` | 223 |
| `1` | 214 |
| `P@ssw0rd` | 159 |
| `password` | 154 |
| `admin123` | 144 |
| `000000` | 114 |
| `123456789` | 111 |
| `!QAZ2wsx` | 99 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1238 |
| `cat` | 1060 |
| `cd` | 1060 |
| `echo` | 1045 |
| `crontab` | 1023 |
| `lscpu` | 1021 |
| `ls` | 922 |
| `free` | 921 |
| `df` | 919 |
| `top` | 919 |
| `whoami` | 918 |
| `w` | 917 |
| `INFO` | 361 |
| `canary_env` | 272 |
| `PING` | 247 |


_Generated from first-party honeypot capture. CC BY 4.0._
