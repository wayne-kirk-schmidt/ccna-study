# Networking Foundations
How to Think About Networks

This repository is a learner-oriented networking knowledge system.
Its purpose is to teach **how to think about networks**, not what to memorize.

The focus is on:
- reasoning about failures
- making design and trade-off decisions
- choosing tools intentionally
- explaining technical thinking clearly

If you can reason well, commands, tools, and vendors follow naturally.

---

## Core Philosophy

### How to Think, Not What to Think

This repository intentionally avoids:
- answer keys
- rote memorization
- command dumps
- vendor-specific walkthroughs

Instead, it emphasizes:
- mental models
- decision paths
- reasoning frameworks
- common traps and failure modes

The goal is clarity of thought under uncertainty.

---

## Repository Structure

The repository has **two layers**:

1. **Core subject modules** (existing files)
2. **Thinking frameworks** (directories with their own READMEs)

Start with the core subjects, then use the directories to deepen reasoning.

---

## Core Networking Subjects

These files introduce the foundational technical domains.

1. **IPv4 Addressing & Subnetting**  
   [01_ipv4_subnetting.md](01_ipv4_subnetting.md)

2. **OSI & TCP/IP Models**  
   [02_osi_tcpip.md](02_osi_tcpip.md)

3. **Switching & VLANs**  
   [03_switching_vlans.md](03_switching_vlans.md)

4. **Inter-VLAN Routing**  
   [04_intervlan_routing.md](04_intervlan_routing.md)

5. **Routing Fundamentals**  
   [05_routing_fundamentals.md](05_routing_fundamentals.md)

6. **NAT & IP Services**  
   [06_nat_ip_services.md](06_nat_ip_services.md)

7. **ACLs & Network Security Basics**  
   [07_acls_security.md](07_acls_security.md)

8. **Wireless Fundamentals**  
   [08_wireless.md](08_wireless.md)

9. **Automation & Programmability**  
   [09_automation.md](09_automation.md)

These files describe *what exists*.  
The directories below teach **how to reason about them**.

---

## Thinking & Reasoning Frameworks

Each directory has its own `README.md`.  
Start with the directory README, not individual files.

---

### OSI Model & Troubleshooting (The Spine)

The OSI model is used as a **thinking and troubleshooting framework**, not as theory.

It helps answer:
- What layer am I reasoning about?
- What identifier matters here (signal, MAC, IP, port, name)?
- What is the next dependency?

Start here before everything else.

Link:  
[osi/README.md](osi/README.md)

---

### Questions & Thinking Drills

This section trains reasoning, not recall.

Questions are designed to practice:
- diagnostic thinking
- explanation skills
- design reasoning
- interview communication

These are thinking drills, not quizzes.

Link:  
[questions/README.md](questions/README.md)

---

### Strategy & Decision-Making

Strategy focuses on **choices and trade-offs** before tools or configuration.

It helps answer:
- What problem are we solving?
- What failures are acceptable?
- What decisions will be hard to undo later?

Link:  
[strategy/README.md](strategy/README.md)

---

### RFCs & Standards

RFCs are treated as **problem → standard → behavior**, not trivia.

You are not expected to memorize RFC numbers.
You are expected to understand why they exist and what behavior they define.

Link:  
[rfc/README.md](rfc/README.md)

---

### Terms & Concept Anchors

Terms are **thinking anchors**, not dictionary definitions.

They exist to:
- reduce ambiguity
- support reasoning
- anchor discussion to OSI layers and identifiers

Link:  
[terms/README.md](terms/README.md)

---

### Tools & Observation

Tools are framed as **ways to answer questions**, not fixes.

This section focuses on:
- when to use a tool
- what question it answers
- what assumptions it validates

Link:  
[tools/README.md](tools/README.md)

---

## How to Use This Repository

A recommended learning loop:

1. Study a core subject file
2. Anchor the concept using OSI
3. Clarify language using Terms
4. Practice reasoning with Questions
5. Apply Strategy before acting
6. Use Tools to observe and validate
7. Reference RFCs to deepen understanding

This mirrors how experienced engineers actually work.

---

## Scope and Growth

This repository is:
- vendor-neutral
- learner-first
- compatible with CCNA-level learning, but not limited to it

It is designed to scale toward:
- real-world operations
- architecture discussions
- interviews
- systems thinking beyond networking

---

License
=======

Copyright 2026 

* Wayne Kirk Schmidt (wayne.kirk.schmidt@gmail.com)

Licensed under the Apache 2.0 License (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    license-name   Apache 2.0 
    license-url    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Support
=======

Feel free to e-mail me with issues to: 

+   wayne.kirk.schmidt@gmail.com

I will provide "best effort" fixes and extend the scripts.
## Status

Structure: Stable  
Philosophy: Locked  
Content: Designed to extend without refactoring
