# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**33 attackers** · **14,261 hostile actions** · covering 2 day(s) through 2026-09-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 8 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 20 |
| `ssh-exploit` | 7 |
| `canary-aws-key` | 3 |
| `llamacpp-abuse` | 2 |
| `jupyter-key-replay` | 1 |
| `llamacpp-key-replay` | 1 |
| `vllm-abuse` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 27 |
| `llamacpp` | 4 |
| `vllm` | 2 |
| `jupyter` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 15 |
| `root` | 11 |
| `administrator` | 8 |
| `admin1` | 7 |
| `a` | 6 |
| `aaa` | 6 |
| `admin123` | 6 |
| `admin2` | 6 |
| `adminuser` | 6 |
| `ai` | 6 |
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
| `123` | 8 |
| `12345` | 8 |
| `123456789` | 8 |
| `0` | 7 |
| `000000` | 7 |
| `!QAZ2wsx` | 6 |
| `0000` | 6 |
| `00000000` | 6 |
| `051178` | 6 |
| `111111` | 6 |
| `admin` | 5 |
| `1234567` | 5 |

### Top commands run

| command | times |
|---|---|
| `uname` | 10 |
| `uptime` | 6 |
| `export` | 6 |
| `chat` | 2 |
| `/bin/./uname` | 2 |
| `lspci` | 2 |
| `nvidia-smi` | 2 |
| `canary_env` | 1 |
| `completions` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
