# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**19 attackers** · **11,480 hostile actions** · covering 2 day(s) through 2026-09-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 4 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 15 |
| `ssh-exploit` | 3 |
| `canary-aws-key` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 18 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 12 |
| `root` | 6 |
| `administrator` | 6 |
| `a` | 5 |
| `aaa` | 5 |
| `admin1` | 5 |
| `adminuser` | 5 |
| `ai` | 5 |
| `airflow` | 5 |
| `AdminGPON` | 4 |
| `Asalem` | 4 |
| `Caps` | 4 |
| `abigail` | 4 |
| `actian` | 4 |
| `adm1n` | 4 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 7 |
| `12345678` | 6 |
| `000000` | 6 |
| `12345` | 5 |
| `!QAZ2wsx` | 5 |
| `0` | 5 |
| `0000` | 5 |
| `123` | 5 |
| `1234` | 5 |
| `admin` | 4 |
| `!1@2` | 4 |
| `!@` | 4 |
| `!Q2w3e4r` | 4 |
| `!Q@W3e4r` | 4 |
| `!QAZ2wsx3edc` | 4 |

### Top commands run

| command | times |
|---|---|
| `uname` | 7 |
| `uptime` | 5 |
| `export` | 3 |
| `/bin/./uname` | 1 |
| `lspci` | 1 |
| `nvidia-smi` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
