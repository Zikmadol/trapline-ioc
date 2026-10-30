# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3862 attackers** · **746,499 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 207 |
| Used a planted canary credential | 53 |
| Seen on more than one sensor | 275 |
| Stage-2 hosts named in payloads | 51 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4830 |
| `ssh-exploit` | 1326 |
| `ssh-bruteforce` | 1101 |
| `redis-exploit` | 668 |
| `mcp-abuse` | 264 |
| `litellm-key-replay` | 90 |
| `llamacpp-abuse` | 87 |
| `ollama-abuse` | 77 |
| `docker-abuse` | 51 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2515 |
| `redis` | 687 |
| `mcp` | 398 |
| `llamacpp` | 262 |
| `litellm` | 181 |
| `vllm` | 169 |
| `jupyter` | 168 |
| `docker` | 130 |
| `ollama` | 128 |
| `hfhub` | 124 |
| `php` | 62 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1565 |
| `345gs5662d34` | 1075 |
| `admin` | 736 |
| `ubuntu` | 360 |
| `user` | 183 |
| `ftpuser` | 178 |
| `test` | 140 |
| `guest` | 116 |
| `git` | 114 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 98 |
| `ftp` | 92 |
| `oracle` | 83 |
| `debian` | 76 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1073 |
| `3245gs5662d34` | 1065 |
| `123456` | 869 |
| `123` | 551 |
| `1234` | 405 |
| `12345678` | 321 |
| `admin` | 283 |
| `1` | 257 |
| `12345` | 255 |
| `P@ssw0rd` | 186 |
| `admin123` | 175 |
| `password` | 157 |
| `123456789` | 126 |
| `000000` | 125 |
| `!QAZ2wsx` | 109 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1444 |
| `cd` | 1251 |
| `cat` | 1250 |
| `echo` | 1238 |
| `crontab` | 1212 |
| `lscpu` | 1210 |
| `ls` | 1105 |
| `free` | 1103 |
| `df` | 1100 |
| `top` | 1100 |
| `w` | 1099 |
| `whoami` | 1099 |
| `INFO` | 453 |
| `canary_env` | 337 |
| `PING` | 321 |


_Generated from first-party honeypot capture. CC BY 4.0._
