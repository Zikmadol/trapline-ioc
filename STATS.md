# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2518 attackers** · **487,559 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 167 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 178 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1012 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 586 |
| `redis-exploit` | 478 |
| `mcp-abuse` | 194 |
| `llamacpp-abuse` | 57 |
| `litellm-key-replay` | 38 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1651 |
| `redis` | 492 |
| `mcp` | 273 |
| `llamacpp` | 163 |
| `vllm` | 103 |
| `jupyter` | 96 |
| `litellm` | 92 |
| `hfhub` | 79 |
| `docker` | 69 |
| `ollama` | 48 |
| `ray` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 956 |
| `345gs5662d34` | 812 |
| `admin` | 552 |
| `ubuntu` | 265 |
| `user` | 143 |
| `ftpuser` | 127 |
| `test` | 122 |
| `git` | 85 |
| `deploy` | 84 |
| `postgres` | 81 |
| `administrator` | 80 |
| `guest` | 78 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 811 |
| `3245gs5662d34` | 806 |
| `123456` | 648 |
| `123` | 413 |
| `1234` | 312 |
| `12345678` | 221 |
| `admin` | 207 |
| `12345` | 194 |
| `1` | 184 |
| `password` | 139 |
| `P@ssw0rd` | 132 |
| `admin123` | 126 |
| `000000` | 103 |
| `123456789` | 100 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1117 |
| `echo` | 951 |
| `cd` | 950 |
| `cat` | 949 |
| `crontab` | 931 |
| `lscpu` | 930 |
| `ls` | 835 |
| `free` | 834 |
| `df` | 832 |
| `top` | 832 |
| `whoami` | 831 |
| `w` | 830 |
| `INFO` | 317 |
| `canary_env` | 233 |
| `PING` | 213 |


_Generated from first-party honeypot capture. CC BY 4.0._
