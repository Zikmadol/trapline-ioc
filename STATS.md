# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4427 attackers** · **977,745 hostile actions** · covering 57 day(s) through 2026-11-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 222 |
| Used a planted canary credential | 149 |
| Seen on more than one sensor | 335 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7416 |
| `ssh-exploit` | 1383 |
| `ssh-bruteforce` | 1175 |
| `redis-exploit` | 812 |
| `mcp-abuse` | 285 |
| `litellm-key-replay` | 151 |
| `ollama-abuse` | 116 |
| `llamacpp-abuse` | 103 |
| `docker-abuse` | 63 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2665 |
| `redis` | 838 |
| `mcp` | 472 |
| `llamacpp` | 344 |
| `litellm` | 275 |
| `jupyter` | 228 |
| `vllm` | 225 |
| `ollama` | 195 |
| `hfhub` | 171 |
| `docker` | 164 |
| `php` | 99 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1638 |
| `345gs5662d34` | 1098 |
| `admin` | 801 |
| `ubuntu` | 406 |
| `ftpuser` | 196 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 138 |
| `git` | 117 |
| `deploy` | 113 |
| `ftp` | 109 |
| `postgres` | 108 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 85 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 924 |
| `123` | 595 |
| `1234` | 426 |
| `12345678` | 353 |
| `admin` | 324 |
| `12345` | 271 |
| `1` | 269 |
| `P@ssw0rd` | 205 |
| `admin123` | 203 |
| `password` | 160 |
| `000000` | 133 |
| `123456789` | 132 |
| `!QAZ2wsx` | 118 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1498 |
| `cd` | 1294 |
| `cat` | 1292 |
| `echo` | 1268 |
| `crontab` | 1241 |
| `lscpu` | 1238 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 569 |
| `PING` | 415 |
| `canary_env` | 385 |


_Generated from first-party honeypot capture. CC BY 4.0._
