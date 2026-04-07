---
title: Regional Internet Registries (RIRs)
type: institution
tags: [rirs, ip-addresses, internet-governance, nro, aso, icann, afrinic, apnic, arin, lacnic, ripe-ncc, technical-community]
created: 2026-04-06
sources:
  - raw/webpages/wikipedia-rirs.md
related:
  - icann
  - isoc
  - internet-governance
  - multistakeholder-model
  - internet-governance-forum
  - wsis-phase-i-geneva-2003
---

# Regional Internet Registries (RIRs)

## Overview
Regional Internet Registries (RIRs) are the five organisations responsible for allocating and registering Internet number resources — including IPv4 addresses, IPv6 addresses, and autonomous system (AS) numbers — within defined geographic regions. Together, the five RIRs form the Internet Number Registry System: the authoritative, distributed mechanism through which every IP address on the Internet is assigned.

The RIRs operate as non-profit, membership-based organisations governed by their regional internet communities. They receive address space from the Internet Assigned Numbers Authority (IANA), administered by [[icann]], and distribute it to Internet Service Providers (ISPs), enterprises, academic institutions, and government bodies within their regions. Each RIR develops its own regional address policies through open, bottom-up, community-driven processes.

The five RIRs united in 2003 to form the Number Resource Organization (NRO), which serves as their coordinating body and liaison to [[icann]] through the Address Supporting Organization (ASO). The RIRs, alongside [[isoc]] and IETF, are considered part of the "technical community" stakeholder group in the WSIS [[multistakeholder-model]].

## Key Facts
- **Number of RIRs:** Five (AFRINIC, APNIC, ARIN, LACNIC, RIPE NCC)
- **Function:** Allocate and register IP addresses and AS numbers within geographic regions
- **Resource source:** Receive address blocks from IANA (administered by [[icann]])
- **Governance model:** Member-run, non-profit; community-driven policy development
- **Coordinating body:** Number Resource Organization (NRO), established October 24, 2003
- **ICANN link:** NRO affiliates with ICANN through the Address Supporting Organization (ASO)
- **Standard reference:** IETF RFC 7020 describes the Internet Number Registry System
- **First RIR:** RIPE NCC (began address distribution 1992; formally founded 1992)

## Detail

### The Five RIRs

| Registry | Founded | Headquarters | Region Served |
|----------|---------|--------------|---------------|
| **AFRINIC** | 2004 | Ebene, Mauritius | Africa |
| **APNIC** | 1993 | Brisbane, Australia | East Asia, South Asia, Southeast Asia, Oceania |
| **ARIN** | 1997 | Chantilly, Virginia, USA | United States, Canada, Antarctica, Caribbean |
| **LACNIC** | 1999 | Montevideo, Uruguay | Latin America, some Caribbean nations |
| **RIPE NCC** | 1992 | Amsterdam, Netherlands | Europe, Russia, Central Asia, West Asia |

### Historical Development

The Regional Internet Registry system evolved gradually from informal address management at the U.S. ARPANET era:

- **1992:** RIPE NCC begins distributing IP addresses in Europe, becoming the first RIR
- **1993:** APNIC founded to serve the Asia-Pacific region
- **1997:** ARIN established to serve North America (taking over from the InterNIC)
- **1999:** LACNIC created to serve Latin America and the Caribbean
- **2003:** All four existing RIRs sign a memorandum of understanding forming the NRO (October 24, 2003)
- **2004:** AFRINIC founded to serve Africa; AFRINIC joins NRO in April 2005
- **2004:** NRO and ICANN sign the ASO MOU, establishing the address policy relationship

### Number Resource Organization (NRO)

The NRO was established October 24, 2003, uniting the four existing RIRs through a memorandum of understanding (AFRINIC joined April 2005). The NRO's primary objectives:

1. **Protecting the unallocated IP number resource pool** — coordinating to prevent address space fragmentation or unequal depletion
2. **Supporting bottom-up Internet policy development** — all five RIRs operate community-driven policy processes open to any stakeholder
3. **Serving as a focal point for community input on RIR operations** — NRO coordinates external relations and joint positions

The NRO holds the Executive Secretariat function on a rotating basis among the five RIRs.

### Address Supporting Organization (ASO) and ICANN

The NRO's primary governance relationship is with [[icann]] through the Address Supporting Organization (ASO):

- The ASO advises the ICANN Board on Internet Protocol addressing policy
- The ASO nominates **two ICANN Board members** — giving the technical community direct representation on ICANN's governance structure
- All ICANN-level IP address policy must go through ASO consultation processes

This relationship embeds the RIRs into the broader [[icann]] multistakeholder governance system while preserving their regional autonomy on address allocation policies.

### Local Internet Registries (LIRs)

Below the RIRs in the hierarchy are Local Internet Registries (LIRs):
- LIRs are organisations (typically ISPs, national registries, or large enterprises) that receive IP address blocks from RIRs
- LIRs then assign portions to their customers
- In some regions, there are also National Internet Registries (NIRs) as an intermediate layer

### IPv4 Exhaustion

A major challenge that affected all RIRs from 2011–2019 was IPv4 address exhaustion:
- IANA exhausted its free IPv4 pool in February 2011
- APNIC reached exhaustion in April 2011; RIPE NCC in September 2012; LACNIC in June 2014; ARIN in September 2015; AFRINIC maintained reserves through the 2010s
- IPv6 deployment (128-bit addresses, providing ~3.4 × 10^38 addresses) is the long-term solution; all RIRs actively promote IPv6 adoption
- IPv4 address markets have emerged, with addresses trading commercially — a development not originally envisioned in the resource allocation model

### RIRs and WSIS

The RIRs are not directly featured in WSIS outcome documents but play a foundational role in WSIS implementation:

- They are core components of the internet infrastructure addressed by **WSIS Action Line C2** (Information and Communication Infrastructure — see [[wsis-action-lines]])
- The question of whether the IP address allocation system should be under intergovernmental oversight (rather than technical community governance) was one of the issues debated at [[wsis-phase-i-geneva-2003]] and studied by [[wgig]]
- The NRO and ARIN co-signed the **Montevideo Statement** (October 7, 2013) calling for accelerated globalisation of ICANN/IANA functions and opposing internet fragmentation
- RIRs participate in [[internet-governance-forum]] (IGF) workshops on addressing, routing security, and infrastructure policy

## Connections
- [[icann]] — IANA delegates IP address space to RIRs; NRO/ASO gives RIRs representation on ICANN Board
- [[isoc]] — ISOC's Deploy360 programme promotes IPv6 and routing security (MANRS), working alongside RIRs
- [[internet-governance]] — RIRs embody the technical community pillar of internet governance; their bottom-up policy model is a core example of multistakeholder governance
- [[multistakeholder-model]] — RIRs and NRO are part of the "technical and academic community" stakeholder group in WSIS
- [[wgig]] — IP address governance was one of the WGIG's scope items; no change to RIR structure resulted
- [[wsis-action-lines]] — C2 (Infrastructure) encompasses the work of RIRs in IP address management

## Open Questions
- With IPv4 markets creating private value from public address space, do RIRs need to adapt their allocation models and governance structures?
- AFRINIC has faced governance crises (disputed elections, legal challenges) — what do these reveal about the challenges of running a regional internet registry in contexts with weaker institutional norms?
- How should RIRs relate to government cybersecurity and surveillance requirements that conflict with their principle of technical neutrality?

## Sources
- raw/webpages/wikipedia-rirs.md (Wikipedia/Regional Internet Registry, fetched 2026-04-06)
