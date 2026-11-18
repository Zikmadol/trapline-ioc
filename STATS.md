# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5645 attackers** · **1,210,207 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 310 |
| Used a planted canary credential | 231 |
| Seen on more than one sensor | 470 |
| Stage-2 hosts named in payloads | 63 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11485 |
| `ssh-bruteforce` | 1807 |
| `ssh-exploit` | 1433 |
| `redis-exploit` | 1009 |
| `mcp-abuse` | 317 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 172 |
| `ollama-abuse` | 152 |
| `llamacpp-abuse` | 131 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3387 |
| `redis` | 1041 |
| `mcp` | 546 |
| `llamacpp` | 446 |
| `vllm` | 343 |
| `litellm` | 339 |
| `docker` | 305 |
| `jupyter` | 282 |
| `ollama` | 273 |
| `hfhub` | 226 |
| `php` | 161 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1845 |
| `345gs5662d34` | 1103 |
| `admin` | 907 |
| `ubuntu` | 423 |
| `guest` | 223 |
| `ftpuser` | 218 |
| `user` | 217 |
| `test` | 174 |
| `ftp` | 132 |
| `git` | 123 |
| `deploy` | 120 |
| `config` | 113 |
| `postgres` | 112 |
| `support` | 111 |
| `administrator` | 109 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 994 |
| `123` | 613 |
| `1234` | 486 |
| `12345678` | 390 |
| `admin` | 384 |
| `12345` | 317 |
| `1` | 282 |
| `P@ssw0rd` | 238 |
| `admin123` | 236 |
| `password` | 175 |
| `123456789` | 145 |
| `000000` | 138 |
| `1111` | 131 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1551 |
| `cat` | 1334 |
| `cd` | 1328 |
| `echo` | 1308 |
| `crontab` | 1275 |
| `lscpu` | 1270 |
| `ls` | 1161 |
| `whoami` | 1156 |
| `free` | 1155 |
| `df` | 1153 |
| `top` | 1151 |
| `w` | 1151 |
| `INFO` | 714 |
| `PING` | 547 |
| `canary_env` | 445 |


_Generated from first-party honeypot capture. CC BY 4.0._
