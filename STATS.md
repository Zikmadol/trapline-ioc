# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2395 attackers** · **470,247 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 160 |
| Used a planted canary credential | 17 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 970 |
| `canary-aws-key` | 748 |
| `ssh-bruteforce` | 552 |
| `redis-exploit` | 459 |
| `mcp-abuse` | 187 |
| `llamacpp-abuse` | 51 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1574 |
| `redis` | 472 |
| `mcp` | 262 |
| `llamacpp` | 152 |
| `vllm` | 97 |
| `jupyter` | 93 |
| `litellm` | 85 |
| `hfhub` | 74 |
| `docker` | 65 |
| `ollama` | 47 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 904 |
| `345gs5662d34` | 771 |
| `admin` | 527 |
| `ubuntu` | 253 |
| `user` | 129 |
| `ftpuser` | 119 |
| `test` | 114 |
| `administrator` | 82 |
| `git` | 80 |
| `postgres` | 79 |
| `deploy` | 74 |
| `guest` | 73 |
| `oracle` | 62 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 770 |
| `3245gs5662d34` | 767 |
| `123456` | 606 |
| `123` | 383 |
| `1234` | 293 |
| `12345678` | 201 |
| `admin` | 190 |
| `12345` | 183 |
| `1` | 171 |
| `password` | 130 |
| `P@ssw0rd` | 123 |
| `admin123` | 116 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1063 |
| `cd` | 907 |
| `cat` | 905 |
| `echo` | 903 |
| `crontab` | 884 |
| `lscpu` | 883 |
| `ls` | 793 |
| `free` | 792 |
| `top` | 791 |
| `df` | 790 |
| `w` | 789 |
| `whoami` | 789 |
| `INFO` | 306 |
| `canary_env` | 223 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
