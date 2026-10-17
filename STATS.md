# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2569 attackers** · **500,032 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 183 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1028 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 598 |
| `redis-exploit` | 488 |
| `mcp-abuse` | 199 |
| `llamacpp-abuse` | 62 |
| `litellm-key-replay` | 41 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1680 |
| `redis` | 501 |
| `mcp` | 280 |
| `llamacpp` | 169 |
| `vllm` | 106 |
| `jupyter` | 100 |
| `litellm` | 96 |
| `hfhub` | 81 |
| `docker` | 70 |
| `ollama` | 49 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 968 |
| `345gs5662d34` | 823 |
| `admin` | 562 |
| `ubuntu` | 269 |
| `user` | 144 |
| `ftpuser` | 132 |
| `test` | 123 |
| `git` | 87 |
| `deploy` | 87 |
| `postgres` | 85 |
| `guest` | 80 |
| `administrator` | 80 |
| `oracle` | 63 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 821 |
| `3245gs5662d34` | 817 |
| `123456` | 661 |
| `123` | 426 |
| `1234` | 318 |
| `12345678` | 230 |
| `admin` | 211 |
| `12345` | 197 |
| `1` | 187 |
| `password` | 142 |
| `P@ssw0rd` | 139 |
| `admin123` | 127 |
| `000000` | 107 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1134 |
| `echo` | 965 |
| `cat` | 962 |
| `cd` | 962 |
| `crontab` | 945 |
| `lscpu` | 944 |
| `ls` | 847 |
| `free` | 846 |
| `df` | 844 |
| `top` | 844 |
| `whoami` | 843 |
| `w` | 842 |
| `INFO` | 324 |
| `canary_env` | 241 |
| `PING` | 219 |


_Generated from first-party honeypot capture. CC BY 4.0._
