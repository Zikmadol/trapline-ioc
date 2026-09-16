# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**29 attackers** · **12,783 hostile actions** · covering 2 day(s) through 2026-09-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 8 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 19 |
| `ssh-exploit` | 7 |
| `canary-aws-key` | 3 |
| `llamacpp-abuse` | 1 |
| `jupyter-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 26 |
| `llamacpp` | 2 |
| `jupyter` | 1 |
| `vllm` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 13 |
| `root` | 11 |
| `administrator` | 7 |
| `admin1` | 6 |
| `a` | 5 |
| `aaa` | 5 |
| `admin123` | 5 |
| `admin2` | 5 |
| `adminuser` | 5 |
| `ai` | 5 |
| `AdminGPON` | 4 |
| `Asalem` | 4 |
| `Caps` | 4 |
| `abigail` | 4 |
| `actian` | 4 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 11 |
| `1234` | 9 |
| `12345678` | 9 |
| `12345` | 8 |
| `123` | 7 |
| `123456789` | 7 |
| `0` | 6 |
| `000000` | 6 |
| `!QAZ2wsx` | 5 |
| `0000` | 5 |
| `00000000` | 5 |
| `051178` | 5 |
| `111111` | 5 |
| `1234567` | 5 |
| `1q2w3e4r` | 5 |

### Top commands run

| command | times |
|---|---|
| `uname` | 9 |
| `uptime` | 6 |
| `export` | 6 |
| `/bin/./uname` | 2 |
| `lspci` | 2 |
| `nvidia-smi` | 2 |
| `canary_env` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
