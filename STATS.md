# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4400 attackers** · **944,127 hostile actions** · covering 56 day(s) through 2026-11-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 221 |
| Used a planted canary credential | 149 |
| Seen on more than one sensor | 334 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7253 |
| `ssh-exploit` | 1377 |
| `ssh-bruteforce` | 1175 |
| `redis-exploit` | 796 |
| `mcp-abuse` | 285 |
| `litellm-key-replay` | 151 |
| `ollama-abuse` | 113 |
| `llamacpp-abuse` | 103 |
| `docker-abuse` | 61 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2659 |
| `redis` | 822 |
| `mcp` | 468 |
| `llamacpp` | 342 |
| `litellm` | 273 |
| `jupyter` | 225 |
| `vllm` | 223 |
| `ollama` | 191 |
| `hfhub` | 169 |
| `docker` | 162 |
| `php` | 99 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1637 |
| `345gs5662d34` | 1098 |
| `admin` | 798 |
| `ubuntu` | 404 |
| `ftpuser` | 195 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 137 |
| `git` | 117 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 108 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 83 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 921 |
| `123` | 594 |
| `1234` | 425 |
| `12345678` | 350 |
| `admin` | 322 |
| `12345` | 270 |
| `1` | 269 |
| `P@ssw0rd` | 204 |
| `admin123` | 201 |
| `password` | 160 |
| `123456789` | 132 |
| `000000` | 132 |
| `!QAZ2wsx` | 116 |

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
| `INFO` | 553 |
| `PING` | 403 |
| `canary_env` | 385 |


_Generated from first-party honeypot capture. CC BY 4.0._
