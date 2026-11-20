# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5805 attackers** · **1,265,615 hostile actions** · covering 69 day(s) through 2026-11-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 316 |
| Used a planted canary credential | 242 |
| Seen on more than one sensor | 482 |
| Stage-2 hosts named in payloads | 66 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13501 |
| `ssh-bruteforce` | 1867 |
| `ssh-exploit` | 1450 |
| `redis-exploit` | 1040 |
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
| `ssh` | 3468 |
| `redis` | 1072 |
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
| `ubuntu` | 425 |
| `guest` | 229 |
| `ftpuser` | 223 |
| `user` | 218 |
| `test` | 173 |
| `ftp` | 137 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 122 |
| `support` | 114 |
| `postgres` | 113 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1102 |
| `3245gs5662d34` | 1094 |
| `123456` | 1013 |
| `123` | 618 |
| `1234` | 502 |
| `12345678` | 397 |
| `admin` | 394 |
| `12345` | 333 |
| `1` | 289 |
| `P@ssw0rd` | 244 |
| `admin123` | 241 |
| `password` | 172 |
| `123456789` | 146 |
| `000000` | 142 |
| `1111` | 141 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1576 |
| `cat` | 1356 |
| `cd` | 1349 |
| `echo` | 1331 |
| `crontab` | 1297 |
| `lscpu` | 1292 |
| `ls` | 1182 |
| `whoami` | 1177 |
| `free` | 1176 |
| `df` | 1174 |
| `top` | 1172 |
| `w` | 1172 |
| `INFO` | 734 |
| `PING` | 564 |
| `canary_env` | 456 |


_Generated from first-party honeypot capture. CC BY 4.0._
