# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4435 attackers** · **980,431 hostile actions** · covering 57 day(s) through 2026-11-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 222 |
| Used a planted canary credential | 149 |
| Seen on more than one sensor | 336 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7475 |
| `ssh-exploit` | 1385 |
| `ssh-bruteforce` | 1176 |
| `redis-exploit` | 816 |
| `mcp-abuse` | 285 |
| `litellm-key-replay` | 151 |
| `ollama-abuse` | 117 |
| `llamacpp-abuse` | 103 |
| `docker-abuse` | 63 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2669 |
| `redis` | 842 |
| `mcp` | 473 |
| `llamacpp` | 344 |
| `litellm` | 275 |
| `jupyter` | 229 |
| `vllm` | 225 |
| `ollama` | 196 |
| `hfhub` | 172 |
| `docker` | 164 |
| `php` | 99 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1639 |
| `345gs5662d34` | 1098 |
| `admin` | 803 |
| `ubuntu` | 407 |
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
| `123` | 595 |
| `1234` | 427 |
| `12345678` | 355 |
| `admin` | 325 |
| `12345` | 272 |
| `1` | 269 |
| `P@ssw0rd` | 206 |
| `admin123` | 205 |
| `password` | 160 |
| `000000` | 133 |
| `123456789` | 132 |
| `!QAZ2wsx` | 118 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1500 |
| `cd` | 1296 |
| `cat` | 1294 |
| `echo` | 1268 |
| `crontab` | 1241 |
| `lscpu` | 1238 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 572 |
| `PING` | 417 |
| `canary_env` | 385 |


_Generated from first-party honeypot capture. CC BY 4.0._
