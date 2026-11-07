# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4385 attackers** · **919,103 hostile actions** · covering 56 day(s) through 2026-11-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 221 |
| Used a planted canary credential | 149 |
| Seen on more than one sensor | 333 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7151 |
| `ssh-exploit` | 1376 |
| `ssh-bruteforce` | 1176 |
| `redis-exploit` | 788 |
| `mcp-abuse` | 285 |
| `litellm-key-replay` | 149 |
| `ollama-abuse` | 110 |
| `llamacpp-abuse` | 103 |
| `docker-abuse` | 60 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2659 |
| `redis` | 814 |
| `mcp` | 467 |
| `llamacpp` | 340 |
| `litellm` | 269 |
| `jupyter` | 222 |
| `vllm` | 221 |
| `ollama` | 188 |
| `hfhub` | 167 |
| `docker` | 161 |
| `php` | 98 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1637 |
| `345gs5662d34` | 1098 |
| `admin` | 797 |
| `ubuntu` | 402 |
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
| `AdminGPON` | 82 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 920 |
| `123` | 593 |
| `1234` | 426 |
| `12345678` | 350 |
| `admin` | 322 |
| `12345` | 271 |
| `1` | 269 |
| `P@ssw0rd` | 204 |
| `admin123` | 200 |
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
| `INFO` | 546 |
| `PING` | 395 |
| `canary_env` | 385 |


_Generated from first-party honeypot capture. CC BY 4.0._
