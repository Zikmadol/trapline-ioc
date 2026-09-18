# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**113 attackers** · **40,343 hostile actions** · covering 6 day(s) through 2026-09-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 16 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 0 |
| Stage-2 hosts named in payloads | 1 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 84 |
| `ssh-exploit` | 17 |
| `llamacpp-abuse` | 4 |
| `canary-aws-key` | 3 |
| `vllm-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `llamacpp-key-replay` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 101 |
| `llamacpp` | 6 |
| `vllm` | 5 |
| `jupyter` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 53 |
| `admin` | 44 |
| `administrator` | 19 |
| `admin1` | 16 |
| `AdminGPON` | 14 |
| `a` | 14 |
| `aaa` | 14 |
| `admin123` | 14 |
| `admin2` | 14 |
| `adminuser` | 14 |
| `ai` | 14 |
| `Asalem` | 12 |
| `Caps` | 12 |
| `abigail` | 12 |
| `actian` | 12 |

### Top passwords tried

| password | tries |
|---|---|
| `123456` | 26 |
| `admin` | 25 |
| `12345678` | 22 |
| `000000` | 21 |
| `1234` | 20 |
| `123456789` | 18 |
| `12345` | 17 |
| `123` | 15 |
| `!QAZ2wsx` | 15 |
| `0` | 15 |
| `0000` | 15 |
| `111111` | 15 |
| `123123` | 15 |
| `00000000` | 14 |
| `051178` | 14 |

### Top commands run

| command | times |
|---|---|
| `uname` | 22 |
| `uptime` | 14 |
| `export` | 14 |
| `canary_env` | 5 |
| `echo` | 4 |
| `chat` | 2 |
| `/bin/./uname` | 2 |
| `lspci` | 2 |
| `nvidia-smi` | 2 |
| `#!/bin/sh` | 2 |
| `ls` | 2 |
| `completions` | 1 |
| `.` | 1 |
| `ps` | 1 |
| `id` | 1 |


_Generated from first-party honeypot capture. CC BY 4.0._
