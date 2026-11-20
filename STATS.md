# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5819 attackers** · **1,272,206 hostile actions** · covering 69 day(s) through 2026-11-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 319 |
| Used a planted canary credential | 242 |
| Seen on more than one sensor | 483 |
| Stage-2 hosts named in payloads | 66 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13504 |
| `ssh-bruteforce` | 1874 |
| `ssh-exploit` | 1451 |
| `redis-exploit` | 1042 |
| `mcp-abuse` | 326 |
| `docker-abuse` | 187 |
| `litellm-key-replay` | 185 |
| `ollama-abuse` | 157 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 25 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3476 |
| `redis` | 1074 |
| `mcp` | 566 |
| `llamacpp` | 463 |
| `litellm` | 357 |
| `vllm` | 355 |
| `docker` | 324 |
| `jupyter` | 290 |
| `ollama` | 281 |
| `hfhub` | 236 |
| `php` | 168 |
| `ray` | 54 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1889 |
| `345gs5662d34` | 1105 |
| `admin` | 922 |
| `ubuntu` | 425 |
| `guest` | 230 |
| `ftpuser` | 224 |
| `user` | 219 |
| `test` | 173 |
| `ftp` | 138 |
| `deploy` | 126 |
| `git` | 124 |
| `config` | 123 |
| `postgres` | 114 |
| `support` | 114 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1102 |
| `3245gs5662d34` | 1094 |
| `123456` | 1018 |
| `123` | 618 |
| `1234` | 504 |
| `12345678` | 399 |
| `admin` | 395 |
| `12345` | 335 |
| `1` | 291 |
| `P@ssw0rd` | 245 |
| `admin123` | 242 |
| `password` | 173 |
| `123456789` | 147 |
| `000000` | 142 |
| `1111` | 142 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1580 |
| `cat` | 1358 |
| `cd` | 1352 |
| `echo` | 1333 |
| `crontab` | 1299 |
| `lscpu` | 1293 |
| `ls` | 1184 |
| `free` | 1178 |
| `whoami` | 1178 |
| `df` | 1175 |
| `top` | 1174 |
| `w` | 1174 |
| `INFO` | 737 |
| `PING` | 565 |
| `canary_env` | 457 |


_Generated from first-party honeypot capture. CC BY 4.0._
