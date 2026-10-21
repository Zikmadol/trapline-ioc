# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2905 attackers** · **577,614 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 182 |
| Used a planted canary credential | 28 |
| Seen on more than one sensor | 205 |
| Stage-2 hosts named in payloads | 39 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2473 |
| `ssh-exploit` | 1138 |
| `ssh-bruteforce` | 656 |
| `redis-exploit` | 541 |
| `mcp-abuse` | 227 |
| `llamacpp-abuse` | 74 |
| `ollama-abuse` | 53 |
| `litellm-key-replay` | 47 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1866 |
| `redis` | 555 |
| `mcp` | 325 |
| `llamacpp` | 198 |
| `jupyter` | 128 |
| `vllm` | 123 |
| `litellm` | 112 |
| `hfhub` | 95 |
| `ollama` | 87 |
| `docker` | 82 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1063 |
| `345gs5662d34` | 906 |
| `admin` | 644 |
| `ubuntu` | 303 |
| `user` | 156 |
| `ftpuser` | 152 |
| `test` | 126 |
| `git` | 105 |
| `postgres` | 103 |
| `deploy` | 100 |
| `guest` | 92 |
| `administrator` | 90 |
| `oracle` | 72 |
| `ftp` | 67 |
| `dev` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 904 |
| `3245gs5662d34` | 900 |
| `123456` | 743 |
| `123` | 494 |
| `1234` | 353 |
| `12345678` | 273 |
| `admin` | 230 |
| `12345` | 224 |
| `1` | 215 |
| `P@ssw0rd` | 159 |
| `password` | 155 |
| `admin123` | 144 |
| `000000` | 115 |
| `123456789` | 111 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1251 |
| `cat` | 1071 |
| `cd` | 1071 |
| `echo` | 1057 |
| `crontab` | 1035 |
| `lscpu` | 1033 |
| `ls` | 933 |
| `free` | 932 |
| `df` | 930 |
| `top` | 930 |
| `whoami` | 929 |
| `w` | 928 |
| `INFO` | 365 |
| `canary_env` | 276 |
| `PING` | 249 |


_Generated from first-party honeypot capture. CC BY 4.0._
