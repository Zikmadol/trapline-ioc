# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3344 attackers** · **658,552 hostile actions** · covering 43 day(s) through 2026-10-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 190 |
| Used a planted canary credential | 39 |
| Seen on more than one sensor | 245 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3313 |
| `ssh-exploit` | 1238 |
| `ssh-bruteforce` | 851 |
| `redis-exploit` | 606 |
| `mcp-abuse` | 242 |
| `llamacpp-abuse` | 83 |
| `ollama-abuse` | 65 |
| `litellm-key-replay` | 57 |
| `docker-abuse` | 42 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2166 |
| `redis` | 621 |
| `mcp` | 357 |
| `llamacpp` | 233 |
| `jupyter` | 150 |
| `vllm` | 138 |
| `litellm` | 132 |
| `ollama` | 108 |
| `hfhub` | 107 |
| `docker` | 106 |
| `php` | 36 |
| `ray` | 24 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1304 |
| `345gs5662d34` | 994 |
| `admin` | 686 |
| `ubuntu` | 330 |
| `ftpuser` | 165 |
| `user` | 164 |
| `test` | 136 |
| `git` | 109 |
| `deploy` | 109 |
| `postgres` | 104 |
| `guest` | 103 |
| `administrator` | 94 |
| `ftp` | 78 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 992 |
| `3245gs5662d34` | 984 |
| `123456` | 801 |
| `123` | 514 |
| `1234` | 383 |
| `12345678` | 301 |
| `admin` | 259 |
| `12345` | 239 |
| `1` | 235 |
| `P@ssw0rd` | 174 |
| `admin123` | 161 |
| `password` | 154 |
| `000000` | 121 |
| `123456789` | 120 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1352 |
| `cd` | 1165 |
| `cat` | 1164 |
| `echo` | 1148 |
| `crontab` | 1124 |
| `lscpu` | 1122 |
| `ls` | 1020 |
| `free` | 1019 |
| `df` | 1017 |
| `top` | 1017 |
| `whoami` | 1016 |
| `w` | 1015 |
| `INFO` | 407 |
| `canary_env` | 304 |
| `PING` | 282 |


_Generated from first-party honeypot capture. CC BY 4.0._
