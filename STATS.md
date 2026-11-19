# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5750 attackers** · **1,237,746 hostile actions** · covering 68 day(s) through 2026-11-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 316 |
| Used a planted canary credential | 238 |
| Seen on more than one sensor | 477 |
| Stage-2 hosts named in payloads | 65 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 12865 |
| `ssh-bruteforce` | 1849 |
| `ssh-exploit` | 1446 |
| `redis-exploit` | 1023 |
| `mcp-abuse` | 321 |
| `litellm-key-replay` | 184 |
| `docker-abuse` | 184 |
| `ollama-abuse` | 154 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3445 |
| `redis` | 1055 |
| `mcp` | 556 |
| `llamacpp` | 457 |
| `litellm` | 351 |
| `vllm` | 347 |
| `docker` | 317 |
| `jupyter` | 286 |
| `ollama` | 278 |
| `hfhub` | 233 |
| `php` | 166 |
| `ray` | 54 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1872 |
| `345gs5662d34` | 1104 |
| `admin` | 917 |
| `ubuntu` | 424 |
| `guest` | 226 |
| `ftpuser` | 221 |
| `user` | 218 |
| `test` | 174 |
| `ftp` | 135 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 120 |
| `support` | 113 |
| `postgres` | 112 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 1007 |
| `123` | 615 |
| `1234` | 497 |
| `12345678` | 393 |
| `admin` | 388 |
| `12345` | 331 |
| `1` | 287 |
| `P@ssw0rd` | 242 |
| `admin123` | 238 |
| `password` | 174 |
| `123456789` | 146 |
| `000000` | 139 |
| `1111` | 138 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1570 |
| `cat` | 1349 |
| `cd` | 1343 |
| `echo` | 1324 |
| `crontab` | 1291 |
| `lscpu` | 1286 |
| `ls` | 1176 |
| `whoami` | 1171 |
| `free` | 1170 |
| `df` | 1168 |
| `top` | 1166 |
| `w` | 1166 |
| `INFO` | 720 |
| `PING` | 555 |
| `canary_env` | 451 |


_Generated from first-party honeypot capture. CC BY 4.0._
