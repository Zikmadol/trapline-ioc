# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**14 attackers** · **7,167 hostile actions** · covering 2 day(s) through 2026-09-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 3 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 10 |
| `ssh-exploit` | 3 |
| `canary-aws-key` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 9 |
| `root` | 5 |
| `administrator` | 4 |
| `Asalem` | 3 |
| `Caps` | 3 |
| `a` | 3 |
| `aaa` | 3 |
| `abigail` | 3 |
| `admin1` | 3 |
| `admin1234` | 3 |
| `admin2` | 3 |
| `admins` | 3 |
| `adminuser` | 3 |
| `agent` | 3 |
| `ai` | 3 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 5 |
| `12345678` | 4 |
| `admin` | 4 |
| `0` | 4 |
| `000000` | 4 |
| `111111` | 4 |
| `!1@2` | 3 |
| `!@` | 3 |
| `!Q2w3e4r` | 3 |
| `!Q@W3e4r` | 3 |
| `!QAZ2wsx` | 3 |
| `!QAZ2wsx3edc` | 3 |
| `0000` | 3 |
| `00000000` | 3 |
| `00008888` | 3 |

### Top commands run

| command | times |
|---|---|
| `uname` | 4 |
| `uptime` | 4 |
| `export` | 2 |
| `/bin/./uname` | 1 |
| `lspci` | 1 |
| `nvidia-smi` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
