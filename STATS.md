# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2669 attackers** · **516,120 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 189 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1180 |
| `ssh-exploit` | 1061 |
| `ssh-bruteforce` | 621 |
| `redis-exploit` | 500 |
| `mcp-abuse` | 212 |
| `llamacpp-abuse` | 65 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 31 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1741 |
| `redis` | 514 |
| `mcp` | 297 |
| `llamacpp` | 176 |
| `vllm` | 107 |
| `jupyter` | 102 |
| `litellm` | 100 |
| `hfhub` | 84 |
| `docker` | 76 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 991 |
| `345gs5662d34` | 842 |
| `admin` | 590 |
| `ubuntu` | 283 |
| `user` | 148 |
| `ftpuser` | 138 |
| `test` | 123 |
| `deploy` | 91 |
| `postgres` | 90 |
| `git` | 89 |
| `guest` | 82 |
| `administrator` | 82 |
| `oracle` | 67 |
| `ftp` | 61 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 840 |
| `3245gs5662d34` | 837 |
| `123456` | 692 |
| `123` | 443 |
| `1234` | 327 |
| `12345678` | 241 |
| `admin` | 218 |
| `12345` | 204 |
| `1` | 198 |
| `password` | 144 |
| `P@ssw0rd` | 142 |
| `admin123` | 137 |
| `000000` | 109 |
| `123456789` | 105 |
| `!QAZ2wsx` | 96 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1170 |
| `cd` | 996 |
| `cat` | 995 |
| `echo` | 986 |
| `crontab` | 965 |
| `lscpu` | 964 |
| `ls` | 866 |
| `free` | 865 |
| `df` | 863 |
| `top` | 863 |
| `whoami` | 862 |
| `w` | 861 |
| `INFO` | 332 |
| `canary_env` | 255 |
| `PING` | 225 |


_Generated from first-party honeypot capture. CC BY 4.0._
