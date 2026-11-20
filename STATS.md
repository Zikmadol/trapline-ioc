# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5801 attackers** · **1,265,093 hostile actions** · covering 69 day(s) through 2026-11-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 316 |
| Used a planted canary credential | 242 |
| Seen on more than one sensor | 482 |
| Stage-2 hosts named in payloads | 66 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13497 |
| `ssh-bruteforce` | 1866 |
| `ssh-exploit` | 1450 |
| `redis-exploit` | 1037 |
| `mcp-abuse` | 325 |
| `docker-abuse` | 186 |
| `litellm-key-replay` | 184 |
| `ollama-abuse` | 156 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 25 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3467 |
| `redis` | 1069 |
| `mcp` | 564 |
| `llamacpp` | 461 |
| `litellm` | 356 |
| `vllm` | 354 |
| `docker` | 322 |
| `jupyter` | 289 |
| `ollama` | 279 |
| `hfhub` | 236 |
| `php` | 168 |
| `ray` | 54 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1886 |
| `345gs5662d34` | 1105 |
| `admin` | 919 |
| `ubuntu` | 424 |
| `guest` | 229 |
| `ftpuser` | 223 |
| `user` | 218 |
| `test` | 174 |
| `ftp` | 137 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 122 |
| `support` | 114 |
| `postgres` | 112 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1102 |
| `3245gs5662d34` | 1094 |
| `123456` | 1013 |
| `123` | 617 |
| `1234` | 502 |
| `12345678` | 396 |
| `admin` | 394 |
| `12345` | 333 |
| `1` | 289 |
| `P@ssw0rd` | 244 |
| `admin123` | 241 |
| `password` | 173 |
| `123456789` | 146 |
| `000000` | 142 |
| `1111` | 141 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1575 |
| `cat` | 1355 |
| `cd` | 1348 |
| `echo` | 1330 |
| `crontab` | 1296 |
| `lscpu` | 1291 |
| `ls` | 1181 |
| `whoami` | 1176 |
| `free` | 1175 |
| `df` | 1173 |
| `top` | 1171 |
| `w` | 1171 |
| `INFO` | 732 |
| `PING` | 563 |
| `canary_env` | 456 |


_Generated from first-party honeypot capture. CC BY 4.0._
