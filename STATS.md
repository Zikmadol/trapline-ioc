# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**38 attackers** · **15,692 hostile actions** · covering 3 day(s) through 2026-09-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 10 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 23 |
| `ssh-exploit` | 9 |
| `canary-aws-key` | 3 |
| `llamacpp-abuse` | 2 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 32 |
| `llamacpp` | 4 |
| `vllm` | 3 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 17 |
| `root` | 12 |
| `administrator` | 10 |
| `admin1` | 8 |
| `aaa` | 7 |
| `admin123` | 7 |
| `admin2` | 7 |
| `ai` | 7 |
| `a` | 6 |
| `adminuser` | 6 |
| `AdminGPON` | 5 |
| `abigail` | 5 |
| `adm1n` | 5 |
| `admin1234` | 5 |
| `airflow` | 5 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 12 |
| `1234` | 10 |
| `12345678` | 10 |
| `123` | 9 |
| `12345` | 8 |
| `admin` | 8 |
| `0` | 8 |
| `123456789` | 8 |
| `!QAZ2wsx` | 7 |
| `0000` | 7 |
| `000000` | 7 |
| `00000000` | 7 |
| `111111` | 7 |
| `051178` | 6 |
| `!@` | 5 |

### Top commands run

| command | times |
|---|---|
| `uname` | 11 |
| `export` | 8 |
| `uptime` | 7 |
| `chat` | 2 |
| `/bin/./uname` | 2 |
| `lspci` | 2 |
| `nvidia-smi` | 2 |
| `canary_env` | 1 |
| `completions` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
