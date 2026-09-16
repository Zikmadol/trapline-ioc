# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**15 attackers** · **9,446 hostile actions** · covering 2 day(s) through 2026-09-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 3 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 12 |
| `canary-aws-key` | 3 |
| `ssh-exploit` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 10 |
| `administrator` | 5 |
| `root` | 4 |
| `AdminGPON` | 4 |
| `Asalem` | 4 |
| `abigail` | 4 |
| `admin1` | 4 |
| `admin123` | 4 |
| `admin1234` | 4 |
| `admin2` | 4 |
| `admins` | 4 |
| `ai` | 4 |
| `Caps` | 3 |
| `a` | 3 |
| `aaa` | 3 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 5 |
| `0` | 5 |
| `12345678` | 4 |
| `admin` | 4 |
| `!1@2` | 4 |
| `!@` | 4 |
| `!QAZ2wsx` | 4 |
| `!qaz@WSX` | 4 |
| `.` | 4 |
| `0000` | 4 |
| `000000` | 4 |
| `00000000` | 4 |
| `00000000000` | 4 |
| `0104` | 4 |
| `04041987` | 4 |

### Top commands run

| command | times |
|---|---|
| `uname` | 5 |
| `uptime` | 5 |
| `export` | 2 |
| `/bin/./uname` | 1 |
| `lspci` | 1 |
| `nvidia-smi` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
