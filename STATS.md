# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2565 attackers** · **499,777 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 183 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1027 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 597 |
| `redis-exploit` | 487 |
| `mcp-abuse` | 199 |
| `llamacpp-abuse` | 61 |
| `litellm-key-replay` | 41 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1678 |
| `redis` | 500 |
| `mcp` | 280 |
| `llamacpp` | 168 |
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
| `root` | 967 |
| `345gs5662d34` | 822 |
| `admin` | 562 |
| `ubuntu` | 269 |
| `user` | 144 |
| `ftpuser` | 132 |
| `test` | 122 |
| `deploy` | 87 |
| `git` | 86 |
| `postgres` | 85 |
| `guest` | 80 |
| `administrator` | 80 |
| `oracle` | 63 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 820 |
| `3245gs5662d34` | 816 |
| `123456` | 660 |
| `123` | 424 |
| `1234` | 318 |
| `12345678` | 230 |
| `admin` | 211 |
| `12345` | 196 |
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
| `uname` | 1133 |
| `echo` | 964 |
| `cat` | 961 |
| `cd` | 961 |
| `crontab` | 944 |
| `lscpu` | 943 |
| `ls` | 846 |
| `free` | 845 |
| `df` | 843 |
| `top` | 843 |
| `whoami` | 842 |
| `w` | 841 |
| `INFO` | 323 |
| `canary_env` | 241 |
| `PING` | 218 |


_Generated from first-party honeypot capture. CC BY 4.0._
