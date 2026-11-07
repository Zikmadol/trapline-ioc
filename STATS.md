# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4378 attackers** · **918,036 hostile actions** · covering 56 day(s) through 2026-11-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 221 |
| Used a planted canary credential | 148 |
| Seen on more than one sensor | 331 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7081 |
| `ssh-exploit` | 1376 |
| `ssh-bruteforce` | 1174 |
| `redis-exploit` | 786 |
| `mcp-abuse` | 284 |
| `litellm-key-replay` | 149 |
| `ollama-abuse` | 109 |
| `llamacpp-abuse` | 103 |
| `docker-abuse` | 60 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 17 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2655 |
| `redis` | 812 |
| `mcp` | 465 |
| `llamacpp` | 339 |
| `litellm` | 269 |
| `jupyter` | 222 |
| `vllm` | 219 |
| `ollama` | 186 |
| `hfhub` | 166 |
| `docker` | 161 |
| `php` | 97 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1635 |
| `345gs5662d34` | 1098 |
| `admin` | 796 |
| `ubuntu` | 402 |
| `ftpuser` | 194 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 136 |
| `git` | 117 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 107 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 82 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 919 |
| `123` | 593 |
| `1234` | 425 |
| `12345678` | 349 |
| `admin` | 321 |
| `12345` | 270 |
| `1` | 269 |
| `P@ssw0rd` | 203 |
| `admin123` | 199 |
| `password` | 160 |
| `123456789` | 133 |
| `000000` | 132 |
| `!QAZ2wsx` | 115 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1494 |
| `cd` | 1291 |
| `cat` | 1289 |
| `echo` | 1268 |
| `crontab` | 1241 |
| `lscpu` | 1238 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 544 |
| `PING` | 394 |
| `canary_env` | 384 |


_Generated from first-party honeypot capture. CC BY 4.0._
