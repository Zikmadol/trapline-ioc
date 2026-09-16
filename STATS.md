# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**12 attackers** · **4,887 hostile actions** · covering 2 day(s) through 2026-09-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 2 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 0 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 9 |
| `ssh-exploit` | 2 |
| `canary-aws-key` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 11 |

### Top usernames tried

| username | tries |
|---|---|
| `admin` | 7 |
| `root` | 4 |
| `Caps` | 3 |
| `abigail` | 3 |
| `admin2` | 3 |
| `administrator` | 3 |
| `AdminGPON` | 2 |
| `Asalem` | 2 |
| `a` | 2 |
| `aaa` | 2 |
| `actian` | 2 |
| `adm1n` | 2 |
| `admin1` | 2 |
| `admin123` | 2 |
| `admin1234` | 2 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 5 |
| `12345678` | 3 |
| `!1@2` | 3 |
| `!QAZ2wsx` | 3 |
| `!QAZ2wsx3edc` | 3 |
| `000000` | 3 |
| `123` | 3 |
| `1234` | 3 |
| `12345` | 3 |
| `1q2w3e4r` | 3 |
| `admin` | 2 |
| `!@` | 2 |
| `!Q2w3e4r` | 2 |
| `!Q@W3e4r` | 2 |
| `******` | 2 |

### Top commands run

| command | times |
|---|---|
| `uname` | 4 |
| `uptime` | 3 |
| `export` | 2 |


_Generated from first-party honeypot capture. CC BY 4.0._
