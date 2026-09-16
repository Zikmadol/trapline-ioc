# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**26 attackers** · **12,357 hostile actions** · covering 2 day(s) through 2026-09-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 6 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 18 |
| `ssh-exploit` | 5 |
| `canary-aws-key` | 3 |
| `llamacpp-abuse` | 1 |
| `jupyter-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 23 |
| `llamacpp` | 2 |
| `jupyter` | 1 |
| `vllm` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 12 |
| `root` | 9 |
| `administrator` | 6 |
| `a` | 5 |
| `aaa` | 5 |
| `admin1` | 5 |
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
| `123456` | 9 |
| `1234` | 7 |
| `12345678` | 7 |
| `12345` | 6 |
| `0` | 6 |
| `000000` | 6 |
| `123` | 6 |
| `123456789` | 6 |
| `!QAZ2wsx` | 5 |
| `0000` | 5 |
| `00000000` | 5 |
| `051178` | 5 |
| `admin` | 4 |
| `!1@2` | 4 |
| `!@` | 4 |

### Top commands run

| command | times |
|---|---|
| `uname` | 9 |
| `uptime` | 6 |
| `export` | 4 |
| `/bin/./uname` | 2 |
| `lspci` | 2 |
| `nvidia-smi` | 2 |
| `canary_env` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
