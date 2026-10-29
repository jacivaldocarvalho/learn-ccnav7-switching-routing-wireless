# CCNAv7: Switching, Routing, and Wireless Essentials (SRWE)

![Cisco](https://img.shields.io/badge/Cisco-CCNAv7-049FD9?logo=cisco&logoColor=white)

**Provider:** NIC.br / Cisco Networking Academy  
**Status:** Module 01 study, review, and seven practical labs completed; Module 02 is next  
**Purpose:** Professional knowledge refresh, hands-on networking, and reproducible technical reference.

## Table of Contents

- [CCNAv7: Switching, Routing, and Wireless Essentials (SRWE)](#ccnav7-switching-routing-and-wireless-essentials-srwe)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Repository Structure](#repository-structure)
    - [Current Progress](#current-progress)
  - [Confirmed Modules](#confirmed-modules)
  - [Assessments](#assessments)
  - [Labs and Evidence](#labs-and-evidence)
  - [Practical Insights: Shell and Python for Network Engineering](#practical-insights-shell-and-python-for-network-engineering)
  - [References and Disclaimer](#references-and-disclaimer)

## Overview

This is an independent English-language study repository aligned with the learner-provided Portuguese course outline. Technical explanations during tutoring are provided in Brazilian Portuguese. Notes are original summaries, not reproductions of proprietary course content.

## Repository Structure

```text
learn-ccnav7-switching-routing-wireless/
├── README.md
├── modules/          # 16 core modules and one supplemental module
├── exams/            # Assessment inventory; detailed reviews pending
├── labs/
│   └── 01-basic-device-configuration/  # Seven completed Packet Tracer labs
└── assets/           # Shared diagrams and supporting assets
```

### Current Progress

| Activity | Status |
|---|---|
| Module 01 study and review | Completed |
| Module 01 practical labs | Completed — 7 documented labs with screenshots and supporting artifacts |
| Checkpoint exams | Completion previously recorded; detailed reviews pending |
| Module 02 — Switching Concepts | Next — not started |

Module 01 now covers exploration of Packet Tracer workspaces, basic switch and router configuration, SSH, IPv4/IPv6 interfaces, directly connected networks, and implementation of a small network. The next study stage is Module 02 — Switching Concepts.

## Confirmed Modules

| No. | Module | Status |
|---|---|---|
| 01 | [Basic Device Configuration](modules/01-basic-device-configuration/README.md) | Completed — study, review, and labs |
| 02 | [Switching Concepts](modules/02-switching-concepts/README.md) | Not started |
| 03 | [VLANs](modules/03-vlans/README.md) | Not started |
| 04 | [Inter-VLAN Routing](modules/04-inter-vlan-routing/README.md) | Not started |
| 05 | [STP Concepts](modules/05-stp-concepts/README.md) | Not started |
| 06 | [EtherChannel](modules/06-etherchannel/README.md) | Not started |
| 07 | [DHCPv4](modules/07-dhcpv4/README.md) | Not started |
| 08 | [SLAAC and DHCPv6](modules/08-slaac-and-dhcpv6/README.md) | Not started |
| 09 | [FHRP Concepts](modules/09-fhrp-concepts/README.md) | Not started |
| 10 | [LAN Security Concepts](modules/10-lan-security-concepts/README.md) | Not started |
| 11 | [Switch Security Configuration](modules/11-switch-security-configuration/README.md) | Not started |
| 12 | [WLAN Concepts](modules/12-wlan-concepts/README.md) | Not started |
| 13 | [WLAN Configuration](modules/13-wlan-configuration/README.md) | Not started |
| 14 | [Routing Concepts](modules/14-routing-concepts/README.md) | Not started |
| 15 | [IP Static Routing](modules/15-ip-static-routing/README.md) | Not started |
| 16 | [Troubleshoot Static and Default Routes](modules/16-troubleshoot-static-and-default-routes/README.md) | Not started |
| 17 | [CCNA 200-301 v1.1 Supplemental Module](modules/17-ccna-200-301-v1-1-supplemental/README.md) | Not started |

## Assessments

The CCNAv7 SRWE course includes five checkpoint exams, an initial knowledge check, three practice Packet Tracer assessments, a practice
final exam, a course final exam, and a final Packet Tracer assessment.

Checkpoint exam completion was recorded in the project progress table. The [assessment inventory](exams/README.md) still contains no detailed reviews, scores, or individual outcomes; those records remain to be added. Lab completion is tracked separately in the reports below.

## Labs and Evidence

All seven Module 01 labs are completed and documented under [`labs/01-basic-device-configuration/`](labs/01-basic-device-configuration/). Each report includes the activity context, procedures, observed results, and screenshots; configuration and verification files are included where available.

| Lab | Report | Main topics |
|---|---|---|
| 1.0.5 | [Logical and Physical Mode Exploration](labs/01-basic-device-configuration/1.0.5-packet-tracer-logical-and-physical-mode-exploration/README.md) | Workspaces, cabling, console access, device names |
| 1.1.7 | [Basic Switch Configuration (Physical Mode)](labs/01-basic-device-configuration/1.1.7-packet-tracer-basic-switch-configuration-physical-mode/README.md) | Switch setup, management VLAN, dual-stack connectivity |
| 1.3.6 | [Configure SSH](labs/01-basic-device-configuration/1.3.6-packet-tracer-configure-ssh/README.md) | Local authentication, RSA keys, SSH-only management |
| 1.4.7 | [Configure Router Interfaces](labs/01-basic-device-configuration/1.4.7-packet-tracer-configure-router-interfaces/README.md) | IPv4/IPv6 interfaces, gateways, connectivity |
| 1.5.10 | [Verify Directly Connected Networks](labs/01-basic-device-configuration/1.5.10-packet-tracer-verify-directly-connected-networks/README.md) | Routing tables, interface troubleshooting, reachability |
| 1.6.1 | [Implement a Small Network](labs/01-basic-device-configuration/1.6.1-packet-tracer-implement-a-small-network/README.md) | Two routed LANs, switch management, ping and traceroute |
| 1.6.2 | [Configure Basic Router Settings (Physical Mode)](labs/01-basic-device-configuration/1.6.2-packet-tracer-configure-basic-router-settings-physical/README.md) | Router security, SSH over IPv4/IPv6, loopback, SLAAC |

The reports distinguish captured results from configuration instructions and note any missing assessment evidence. Completion reflects the learner's confirmed progress; available screenshots and artifacts establish the documented technical results.

## Practical Insights: Shell and Python for Network Engineering

Module 01 already includes [Shell and Python examples](modules/01-basic-device-configuration/README.md#7-practical-insights--shell-and-python) for host-side checks and IPv4 management-plan validation. Later modules will add relevant tasks as their technical notes are developed. These examples are independent educational and professional extensions; each report identifies illustrative examples and observed results.

## References and Disclaimer

- NIC.br / Cisco Networking Academy — learner-provided SRWE course outline.
- Module notes and lab reports include Cisco IOS and Packet Tracer references relevant to their documented topics.

This independent educational repository is not an official Cisco or NIC.br publication. No certification or course completion is claimed.
