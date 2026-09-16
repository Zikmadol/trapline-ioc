---
name: False positive / removal request
about: Report an IP you believe is listed in error, or a scanner range to allowlist
title: "[FP] "
labels: false-positive
---

**IP address or CIDR**
<!-- e.g. 203.0.113.4, or 198.51.100.0/24 -->

**Which list is it in?**
<!-- ips.txt / active.txt / feeds/ai-infra.txt / feeds/llmjacking.txt / feeds/all-observed.txt -->

**Why do you believe it's a false positive?**
<!-- Pick what applies:
- I operate this address (shared NAT, VPN egress, corporate proxy, home connection)
- It's a benign research scanner (Censys/Shadowserver/Shodan/etc.) — please allowlist the range
- The IP was reassigned / is now used by someone else
- Other (explain) -->

**Evidence, if any**
<!-- rDNS, ASN/owner, a scanning-operator opt-out/registration page, WHOIS — anything that
helps verify. For scanner ranges, a link to the operator's published scanning IPs is ideal. -->

---
Attacker IPs are first-party observations: each was seen taking a hostile action against a
decoy that hosts nothing legitimate. We still review every report, and confirmed benign
scanners are added to `allowlist.txt`.
