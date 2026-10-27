# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3562 attackers** · **698,425 hostile actions** · covering 45 day(s) through 2026-10-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 194 |
| Used a planted canary credential | 41 |
| Seen on more than one sensor | 258 |
| Stage-2 hosts named in payloads | 45 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3738 |
| `ssh-exploit` | 1266 |
| `ssh-bruteforce` | 983 |
| `redis-exploit` | 630 |
| `mcp-abuse` | 250 |
| `llamacpp-abuse` | 83 |
| `ollama-abuse` | 70 |
| `litellm-key-replay` | 62 |
| `docker-abuse` | 45 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2330 |
| `redis` | 646 |
| `mcp` | 373 |
| `llamacpp` | 242 |
| `jupyter` | 158 |
| `vllm` | 154 |
| `litellm` | 142 |
| `ollama` | 115 |
| `docker` | 114 |
| `hfhub` | 113 |
| `php` | 51 |
| `ray` | 28 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1432 |
| `345gs5662d34` | 1020 |
| `admin` | 704 |
| `ubuntu` | 343 |
| `user` | 174 |
| `ftpuser` | 171 |
| `test` | 139 |
| `deploy` | 112 |
| `git` | 111 |
| `guest` | 110 |
| `postgres` | 105 |
| `administrator` | 96 |
| `ftp` | 85 |
| `oracle` | 77 |
| `AdminGPON` | 70 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1018 |
| `3245gs5662d34` | 1010 |
| `123456` | 829 |
| `123` | 520 |
| `1234` | 393 |
| `12345678` | 308 |
| `admin` | 270 |
| `1` | 248 |
| `12345` | 245 |
| `P@ssw0rd` | 180 |
| `admin123` | 164 |
| `password` | 151 |
| `123456789` | 124 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1383 |
| `cd` | 1193 |
| `cat` | 1192 |
| `echo` | 1179 |
| `crontab` | 1153 |
| `lscpu` | 1151 |
| `ls` | 1048 |
| `free` | 1046 |
| `df` | 1043 |
| `top` | 1043 |
| `w` | 1042 |
| `whoami` | 1042 |
| `INFO` | 425 |
| `canary_env` | 316 |
| `PING` | 298 |


_Generated from first-party honeypot capture. CC BY 4.0._
