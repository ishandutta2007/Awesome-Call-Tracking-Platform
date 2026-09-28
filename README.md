# Awesome-Call-Tracking-Platform

## Top Call Tracking Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Marketing Call Attribution, Dynamic Number Insertion, Call Analytics, Conversation Intelligence & Lead Source Tracking*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Call Tracking**. These systems attribute phone calls to marketing sources, provide dynamic number insertion (DNI), record and analyze conversations, and connect call data to CRM and advertising platforms.



**Examples** include CallRail, Invoca, WhatConverts, CallTrackingMetrics, Marchex, Infinity Call Tracking, Ringba, Convirza, ResponseTap, and DialogTech (the category leaders).



**Open-source emphasis**: Purpose-built marketing call tracking with DNI, attribution, and conversation intelligence is almost entirely commercial. Open options focus on telephony engines (**Asterisk**, **FreeSWITCH**), CDR analytics (**CDR-Stats**), and custom builds on top of open VoIP stacks. This section expands those building blocks and is realistic about the commercial gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[CallRail](https://www.callrail.com/)**  

  Leading SMB and mid-market call tracking platform with dynamic number insertion, attribution, recording, form tracking, and conversation intelligence integrations.



- **[Invoca](https://www.invoca.com/)**  

  Enterprise call tracking and AI conversation analytics platform for marketing attribution and contact-center optimization at scale.



- **[WhatConverts](https://www.whatconverts.com/)**  

  Lead tracking and attribution platform that treats phone calls as one lead type alongside forms and other conversions.



- **[CallTrackingMetrics](https://www.calltrackingmetrics.com/)**  

  Call tracking and marketing analytics platform popular with agencies and multi-client environments.



- **[Marchex](https://www.marchex.com/)**  

  Call analytics and conversation intelligence platform often used by multi-location and franchise businesses.



- **[Infinity Call Tracking](https://www.infinitycloud.com/)**  

  Call tracking and analytics solution for measuring offline response to marketing campaigns.



- **[Ringba](https://www.ringba.com/)**  

  Call tracking and pay-per-call platform focused on publishers, networks, and performance marketing.



- **[Convirza](https://www.convirza.com/)**  

  Call tracking and conversation analytics platform for marketing and sales performance insights.



- **[ResponseTap](https://www.responsetap.com/)**  

  Visitor-level call tracking and attribution platform for digital marketing measurement.



- **[DialogTech and related call analytics platforms](https://www.example.com/)**  

  Additional enterprise call tracking and conversation intelligence solutions used for attribution and optimization.



## Open-Source GitHub Projects

- **[Asterisk](https://github.com/asterisk/asterisk)**  

  Foundational open-source telephony framework used to build custom PBX, call routing, and tracking solutions.



- **[FreeSWITCH](https://github.com/signalwire/freeswitch)**  

  Scalable open-source softswitch and media server widely used as the telephony engine for custom call handling and analytics platforms.



- **[CDR-Stats](https://github.com/cdr-stats/cdr-stats)**  

  Open-source CDR (Call Detail Record) mediation, rating, analysis, and reporting application for FreeSWITCH, Asterisk, and other VoIP switches.



- **[Kamailio](https://github.com/kamailio/kamailio)**  

  High-performance open-source SIP proxy and router often placed in front of media servers for large-scale call routing.



- **[OpenACD](https://github.com/OpenACD/OpenACD)**  

  Open-source automated contact distribution system built on Erlang and FreeSWITCH for call center-style routing and CDRs.



- **[Custom DNI and tracking open scripts](https://github.com/)**  

  Community approaches to dynamic number insertion and session-to-call correlation using open web and telephony stacks.



- **[Call recording and transcription open pipelines](https://github.com/)**  

  Open tools for recording, storing, and optionally transcribing calls when building in-house analytics.



- **[Twilio-style open telephony APIs and CPaaS experiments](https://github.com/)**  

  Projects that expose programmable voice APIs on top of Asterisk/FreeSWITCH for custom attribution flows.



- **[Analytics and dashboard open stacks for CDRs](https://github.com/)**  

  Grafana, Metabase, or similar tools connected to CDR databases for call volume and performance reporting.



- **[Documentation and DIY call-tracking open playbooks](https://github.com/)**  

  Guides for building basic call attribution on open telephony engines for internal or low-volume use cases.



### Additional Strong Open-Source Options

- Building a custom stack with **FreeSWITCH or Asterisk + CDR-Stats** for call logging, rating, and basic reporting.

- Using open SIP proxies and media servers when full control of the telephony path is required.

- Accepting that marketing-grade dynamic number insertion, visitor-level attribution, Google Ads/CRM integrations, AI conversation intelligence, and multi-number management still require commercial platforms (CallRail, Invoca, WhatConverts, CallTrackingMetrics, etc.).

- Focusing open-source efforts on cost control, data ownership, and specialized telephony for engineering-led teams.



**Frameworks for building custom systems**: Provision numbers via a carrier/CPaaS → route through FreeSWITCH/Asterisk → capture CDRs and recordings → attribute via custom session logic → report in open analytics tools. Suitable for technical teams with telephony expertise. Most marketers and agencies rely on commercial call tracking platforms for speed and integrations.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Call tracking involves telephony, recording, and personal data subject to consent and privacy laws (e.g., TCPA, GDPR). Open-source deployments require legal and compliance review. This list is not legal or marketing advice.



---

**Made for marketers, growth teams, and open-source telephony advocates.**

Let's keep call attribution accurate, transparent, and as open as practical.
