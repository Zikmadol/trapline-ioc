# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**27 attackers** · **12,637 hostile actions** · covering 2 day(s) through 2026-09-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 7 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 18 |
| `ssh-exploit` | 6 |
| `canary-aws-key` | 3 |
| `llamacpp-abuse` | 1 |
| `jupyter-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 24 |
| `llamacpp` | 2 |
| `jupyter` | 1 |
| `vllm` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 13 |
| `root` | 10 |
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
| `123456` | 10 |
| `1234` | 8 |
| `12345` | 7 |
| `12345678` | 7 |
| `123` | 7 |
| `0` | 6 |
| `000000` | 6 |
| `123456789` | 6 |
| `!QAZ2wsx` | 5 |
| `0000` | 5 |
| `00000000` | 5 |
| `051178` | 5 |
| `1234567` | 5 |
| `admin` | 4 |
| `!1@2` | 4 |

### Top commands run

| command | times |
|---|---|
| `uname` | 9 |
| `uptime` | 6 |
| `export` | 5 |
| `/bin/./uname` | 2 |
| `lspci` | 2 |
| `nvidia-smi` | 2 |
| `canary_env` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
