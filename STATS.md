# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2335 attackers** · **461,422 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 156 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 167 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 949 |
| `ssh-bruteforce` | 539 |
| `redis-exploit` | 440 |
| `canary-aws-key` | 356 |
| `mcp-abuse` | 185 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1539 |
| `redis` | 453 |
| `mcp` | 255 |
| `llamacpp` | 142 |
| `vllm` | 90 |
| `jupyter` | 89 |
| `litellm` | 83 |
| `hfhub` | 71 |
| `docker` | 63 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 883 |
| `345gs5662d34` | 757 |
| `admin` | 514 |
| `ubuntu` | 249 |
| `user` | 122 |
| `test` | 115 |
| `ftpuser` | 115 |
| `postgres` | 79 |
| `administrator` | 79 |
| `git` | 78 |
| `guest` | 71 |
| `deploy` | 70 |
| `oracle` | 60 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 756 |
| `3245gs5662d34` | 753 |
| `123456` | 586 |
| `123` | 373 |
| `1234` | 288 |
| `12345678` | 197 |
| `admin` | 185 |
| `12345` | 179 |
| `1` | 164 |
| `password` | 128 |
| `P@ssw0rd` | 119 |
| `admin123` | 111 |
| `000000` | 100 |
| `123456789` | 98 |
| `!QAZ2wsx` | 88 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1038 |
| `cd` | 886 |
| `echo` | 885 |
| `cat` | 884 |
| `crontab` | 866 |
| `lscpu` | 865 |
| `ls` | 778 |
| `free` | 777 |
| `top` | 776 |
| `df` | 775 |
| `w` | 774 |
| `whoami` | 774 |
| `INFO` | 295 |
| `canary_env` | 221 |
| `PING` | 197 |


_Generated from first-party honeypot capture. CC BY 4.0._
