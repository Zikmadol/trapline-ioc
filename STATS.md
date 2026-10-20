# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2851 attackers** · **561,438 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 180 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 199 |
| Stage-2 hosts named in payloads | 38 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2314 |
| `ssh-exploit` | 1121 |
| `ssh-bruteforce` | 648 |
| `redis-exploit` | 534 |
| `mcp-abuse` | 224 |
| `llamacpp-abuse` | 73 |
| `litellm-key-replay` | 46 |
| `ollama-abuse` | 44 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 31 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1838 |
| `redis` | 548 |
| `mcp` | 317 |
| `llamacpp` | 193 |
| `jupyter` | 126 |
| `vllm` | 118 |
| `litellm` | 111 |
| `hfhub` | 94 |
| `docker` | 82 |
| `ollama` | 76 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1044 |
| `345gs5662d34` | 891 |
| `admin` | 639 |
| `ubuntu` | 302 |
| `user` | 153 |
| `ftpuser` | 152 |
| `test` | 126 |
| `postgres` | 102 |
| `git` | 102 |
| `deploy` | 97 |
| `guest` | 91 |
| `administrator` | 89 |
| `oracle` | 72 |
| `ftp` | 66 |
| `dev` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 889 |
| `3245gs5662d34` | 886 |
| `123456` | 739 |
| `123` | 489 |
| `1234` | 347 |
| `12345678` | 272 |
| `admin` | 229 |
| `12345` | 223 |
| `1` | 215 |
| `P@ssw0rd` | 158 |
| `password` | 153 |
| `admin123` | 144 |
| `000000` | 114 |
| `123456789` | 110 |
| `!QAZ2wsx` | 99 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1233 |
| `cat` | 1055 |
| `cd` | 1055 |
| `echo` | 1040 |
| `crontab` | 1018 |
| `lscpu` | 1016 |
| `ls` | 917 |
| `free` | 916 |
| `df` | 914 |
| `top` | 914 |
| `whoami` | 913 |
| `w` | 912 |
| `INFO` | 359 |
| `canary_env` | 272 |
| `PING` | 246 |


_Generated from first-party honeypot capture. CC BY 4.0._
