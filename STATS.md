# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6502 attackers** · **1,400,336 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 351 |
| Used a planted canary credential | 277 |
| Seen on more than one sensor | 529 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13609 |
| `ssh-bruteforce` | 2011 |
| `ssh-exploit` | 1488 |
| `redis-exploit` | 1208 |
| `mcp-abuse` | 365 |
| `docker-abuse` | 233 |
| `litellm-key-replay` | 229 |
| `llamacpp-abuse` | 228 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3667 |
| `redis` | 1241 |
| `mcp` | 719 |
| `llamacpp` | 638 |
| `vllm` | 506 |
| `litellm` | 460 |
| `docker` | 393 |
| `jupyter` | 342 |
| `ollama` | 312 |
| `hfhub` | 271 |
| `php` | 209 |
| `ray` | 79 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 2003 |
| `345gs5662d34` | 1108 |
| `admin` | 967 |
| `ubuntu` | 440 |
| `guest` | 246 |
| `ftpuser` | 241 |
| `user` | 226 |
| `test` | 178 |
| `ftp` | 155 |
| `config` | 139 |
| `deploy` | 132 |
| `git` | 127 |
| `bin` | 122 |
| `administrator` | 120 |
| `george` | 120 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1098 |
| `123456` | 1059 |
| `123` | 645 |
| `1234` | 545 |
| `admin` | 425 |
| `12345678` | 417 |
| `12345` | 361 |
| `1` | 303 |
| `admin123` | 268 |
| `P@ssw0rd` | 261 |
| `password` | 177 |
| `1111` | 156 |
| `123456789` | 152 |
| `000000` | 149 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1637 |
| `cat` | 1407 |
| `cd` | 1400 |
| `echo` | 1373 |
| `crontab` | 1340 |
| `lscpu` | 1332 |
| `ls` | 1222 |
| `free` | 1215 |
| `whoami` | 1215 |
| `df` | 1212 |
| `top` | 1211 |
| `w` | 1211 |
| `INFO` | 866 |
| `PING` | 689 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
