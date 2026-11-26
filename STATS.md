# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6255 attackers** · **1,365,385 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 342 |
| Used a planted canary credential | 269 |
| Seen on more than one sensor | 514 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13585 |
| `ssh-bruteforce` | 1944 |
| `ssh-exploit` | 1469 |
| `redis-exploit` | 1136 |
| `mcp-abuse` | 349 |
| `docker-abuse` | 222 |
| `llamacpp-abuse` | 219 |
| `litellm-key-replay` | 203 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 32 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3577 |
| `redis` | 1168 |
| `mcp` | 691 |
| `llamacpp` | 615 |
| `vllm` | 483 |
| `litellm` | 428 |
| `docker` | 373 |
| `jupyter` | 326 |
| `ollama` | 301 |
| `hfhub` | 264 |
| `php` | 196 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1936 |
| `345gs5662d34` | 1107 |
| `admin` | 954 |
| `ubuntu` | 440 |
| `guest` | 240 |
| `ftpuser` | 233 |
| `user` | 221 |
| `test` | 174 |
| `ftp` | 148 |
| `config` | 133 |
| `deploy` | 129 |
| `git` | 125 |
| `administrator` | 117 |
| `bin` | 117 |
| `george` | 115 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1096 |
| `123456` | 1041 |
| `123` | 634 |
| `1234` | 527 |
| `admin` | 417 |
| `12345678` | 409 |
| `12345` | 354 |
| `1` | 303 |
| `admin123` | 263 |
| `P@ssw0rd` | 255 |
| `password` | 174 |
| `1111` | 152 |
| `123456789` | 151 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1606 |
| `cat` | 1377 |
| `cd` | 1372 |
| `echo` | 1345 |
| `crontab` | 1312 |
| `lscpu` | 1305 |
| `ls` | 1194 |
| `free` | 1188 |
| `whoami` | 1188 |
| `df` | 1185 |
| `top` | 1184 |
| `w` | 1184 |
| `INFO` | 801 |
| `PING` | 625 |
| `canary_env` | 586 |


_Generated from first-party honeypot capture. CC BY 4.0._
