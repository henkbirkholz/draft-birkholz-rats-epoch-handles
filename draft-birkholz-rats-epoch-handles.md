---
title: Epoch Handles
abbrev: TRT
docname: draft-birkholz-rats-epoch-handles-latest
stand_alone: true
ipr: trust200902
area: Security
wg: SACM Working Group
kw: Internet-Draft
cat: std
pi:
  toc: yes
  sortrefs: yes
  symrefs: yes

author:
- ins: H. Birkholz
  name: Henk Birkholz
  org: Fraunhofer SIT
  abbrev: Fraunhofer SIT
  email: henk.birkholz@sit.fraunhofer.de
  street: Rheinstrasse 75
  code: '64295'
  city: Darmstadt
  country: Germany
- ins: C. Bormann
  name: Carsten Bormann
  org: Universitaet Bremen TZI
  street: Bibliothekstr. 1
  city: Bremen
  code: D-28359
  country: Germany
  phone: +49-421-218-63921
  email: cabo@tzi.org

normative:
  RFC2119:

informative:

--- abstract

Abstract Text

--- middle

# Introduction

Systems that rely on trustworthy relationships between their components often require a synchronized time keeping mechanism allowing them to assert the freshness of incoming messages. While various reliable mechanisms exist that allow for time synchronization on a global timescale, these are not always applicable in constrained or large-scaled usage scenarios. Components with relative clocks, no clocks, or no bi-directional communication channel between them benefit from a simpler mechanism that enables an assertion of freshness. Epoch Handles constitute a versatile, and concise message format for centrally orchestrated time-keeping messages in a given domain. The reception of an Epoch Handle marks the beginning of a new epoch with respect to freshness. This time-keeping principle can be facilitated by different types of handle content or hybrids thereof, most prominently counters, nonces, and timestamps.

## Usage Scenarios

Streamed remote Attestation

## Requirements Notation

{::boilerplate bcp14}

# Handle Layout

# Handle Content Types

## Timestamps

## Opaque Data

as Nonces

--- back
