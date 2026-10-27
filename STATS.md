# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3579 attackers** · **699,929 hostile actions** · covering 45 day(s) through 2026-10-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 195 |
| Used a planted canary credential | 41 |
| Seen on more than one sensor | 260 |
| Stage-2 hosts named in payloads | 45 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3811 |
| `ssh-exploit` | 1265 |
| `ssh-bruteforce` | 994 |
| `redis-exploit` | 633 |
| `mcp-abuse` | 251 |
| `llamacpp-abuse` | 84 |
| `ollama-abuse` | 71 |
| `litellm-key-replay` | 63 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2342 |
| `redis` | 649 |
| `mcp` | 374 |
| `llamacpp` | 243 |
| `jupyter` | 158 |
| `vllm` | 154 |
| `litellm` | 143 |
| `ollama` | 116 |
| `docker` | 116 |
| `hfhub` | 113 |
| `php` | 54 |
| `ray` | 28 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1444 |
| `345gs5662d34` | 1020 |
| `admin` | 707 |
| `ubuntu` | 344 |
| `user` | 174 |
| `ftpuser` | 172 |
| `test` | 140 |
| `deploy` | 112 |
| `git` | 111 |
| `guest` | 110 |
| `postgres` | 106 |
| `administrator` | 96 |
| `ftp` | 85 |
| `oracle` | 77 |
| `dev` | 71 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1018 |
| `3245gs5662d34` | 1010 |
| `123456` | 830 |
| `123` | 520 |
| `1234` | 393 |
| `12345678` | 308 |
| `admin` | 270 |
| `1` | 248 |
| `12345` | 245 |
| `P@ssw0rd` | 180 |
| `admin123` | 165 |
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
| `INFO` | 428 |
| `canary_env` | 317 |
| `PING` | 300 |


_Generated from first-party honeypot capture. CC BY 4.0._
