---
title: "TODO - Your title"
abbrev: "TODO - Abbreviation"
category: info

docname: draft-voyer-srv6ops-test-latest
submissiontype: IETF # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "Operations and Management"
workgroup: "SRv6 Operations"
keyword:
  - next generation
  - unicorn
  - sparkling distributed ledger
venue:
  group: "SRv6 Operations"
  type: "Working Group"
  mail: "srv6ops@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/srv6ops/"
  github: "voyed/Draft-test-davoyer"
  latest: "https://voyed.github.io/Draft-test-davoyer/draft-voyer-srv6ops-test.html"

author:
  - fullname: Dan Voyer
    organization: Personal
    email: "danvoyer@gmail.com"

normative:

informative:
...

--- abstract

   This document provides operational guidelines for designing Segment
   Routing over IPv6 (SRv6) addressing plans in Internet‑service‑provider
   backbones of up to 50 000 nodes.  It specifies a compressed Segment
   Identifier (C‑SID) locator structure (F3216) that encodes Flex‑Algo,
   Region‑ID, Site‑ID and Node‑ID inside a fixed /48 locator while
   leaving space for Local and Global C‑SIDs.  An “ultra‑scale” profile
   (~300 000 nodes) using End.LBS locator‑block swap is also defined.
   The aim is to accelerate brown‑field SRv6 migrations by offering
   deterministic field carving, summarisation rules and actionable
   operational guidance.

--- middle

# Introduction

TODO Introduction

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Security Considerations

TODO Security

# IANA Considerations

testing 1234

--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
