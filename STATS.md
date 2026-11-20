# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5813 attackers** · **1,271,570 hostile actions** · covering 69 day(s) through 2026-11-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 317 |
| Used a planted canary credential | 242 |
| Seen on more than one sensor | 482 |
| Stage-2 hosts named in payloads | 66 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13502 |
| `ssh-bruteforce` | 1870 |
| `ssh-exploit` | 1450 |
| `redis-exploit` | 1042 |
| `mcp-abuse` | 326 |
| `docker-abuse` | 186 |
| `litellm-key-replay` | 185 |
| `ollama-abuse` | 157 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 25 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3471 |
| `redis` | 1074 |
| `mcp` | 566 |
| `llamacpp` | 462 |
| `litellm` | 357 |
| `vllm` | 354 |
| `docker` | 322 |
| `jupyter` | 289 |
| `ollama` | 281 |
| `hfhub` | 236 |
| `php` | 168 |
| `ray` | 54 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1887 |
| `345gs5662d34` | 1105 |
| `admin` | 920 |
| `ubuntu` | 426 |
| `guest` | 229 |
| `ftpuser` | 223 |
| `user` | 220 |
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
| `123456` | 1016 |
| `123` | 618 |
| `1234` | 503 |
| `12345678` | 397 |
| `admin` | 394 |
| `12345` | 333 |
| `1` | 290 |
| `P@ssw0rd` | 244 |
| `admin123` | 241 |
| `password` | 172 |
| `123456789` | 147 |
| `000000` | 142 |
| `1111` | 141 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1578 |
| `cat` | 1357 |
| `cd` | 1350 |
| `echo` | 1332 |
| `crontab` | 1298 |
| `lscpu` | 1293 |
| `ls` | 1183 |
| `whoami` | 1178 |
| `free` | 1177 |
| `df` | 1175 |
| `top` | 1173 |
| `w` | 1173 |
| `INFO` | 737 |
| `PING` | 565 |
| `canary_env` | 457 |


_Generated from first-party honeypot capture. CC BY 4.0._
