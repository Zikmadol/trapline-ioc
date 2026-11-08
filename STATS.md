# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4450 attackers** · **990,504 hostile actions** · covering 57 day(s) through 2026-11-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 222 |
| Used a planted canary credential | 150 |
| Seen on more than one sensor | 339 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7542 |
| `ssh-exploit` | 1387 |
| `ssh-bruteforce` | 1177 |
| `redis-exploit` | 824 |
| `mcp-abuse` | 285 |
| `litellm-key-replay` | 153 |
| `ollama-abuse` | 117 |
| `llamacpp-abuse` | 104 |
| `docker-abuse` | 63 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `php-abuse` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2673 |
| `redis` | 850 |
| `mcp` | 473 |
| `llamacpp` | 348 |
| `litellm` | 278 |
| `jupyter` | 231 |
| `vllm` | 228 |
| `ollama` | 198 |
| `hfhub` | 173 |
| `docker` | 164 |
| `php` | 103 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1640 |
| `345gs5662d34` | 1098 |
| `admin` | 804 |
| `ubuntu` | 408 |
| `ftpuser` | 197 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 139 |
| `git` | 117 |
| `deploy` | 113 |
| `ftp` | 110 |
| `postgres` | 108 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 85 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 925 |
| `123` | 596 |
| `1234` | 428 |
| `12345678` | 356 |
| `admin` | 325 |
| `12345` | 272 |
| `1` | 268 |
| `admin123` | 206 |
| `P@ssw0rd` | 206 |
| `password` | 160 |
| `000000` | 133 |
| `123456789` | 132 |
| `!QAZ2wsx` | 119 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1502 |
| `cd` | 1298 |
| `cat` | 1296 |
| `echo` | 1268 |
| `crontab` | 1241 |
| `lscpu` | 1238 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 577 |
| `PING` | 423 |
| `canary_env` | 385 |


_Generated from first-party honeypot capture. CC BY 4.0._
