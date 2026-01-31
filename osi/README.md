# OSI Model & Troubleshooting

⬅️ Back to [Main README](../README.md)

## Purpose
The OSI model is a **conceptual framework with seven layers** used to reason about how data moves
through a network and, more importantly, **where things break**.

This directory uses OSI as a *thinking tool*, not a configuration guide.

---

## The OSI Layers (Canonical Anchor)

| OSI Layer | Number | Name           | Key Identifier(s)                  | Primary Question |
|----------:|--------|----------------|------------------------------------|------------------|
| Application | 7 | Application    | URLs, APIs, App data               | Is the application behaving correctly? |
| Presentation | 6 | Presentation  | Encoding, Encryption, Certificates | Is the data formatted and secure? |
| Session | 5 | Session        | Session IDs, Tokens, Timeouts      | Is the conversation staying alive? |
| Transport | 4 | Transport      | **Port numbers**, TCP/UDP          | Is end-to-end delivery working? |
| Network | 3 | Network        | **IP addresses**                   | Can packets reach the destination? |
| Data Link | 2 | Data Link      | **MAC addresses**, VLAN IDs        | Can frames reach the next hop? |
| Physical | 1 | Physical       | Signal, voltage, light             | Is there a signal at all? |

> This table is **canonical**. All troubleshooting, questions, and strategies map back to it.

---

## How to Use This Directory
1. Start with the **OSI Troubleshooting Matrix**
2. Dive into individual layers as needed
3. Always validate lower layers before assuming higher-layer issues

---

## Files
- [OSI Troubleshooting Matrix](osi_troubleshooting_matrix.md)
- [Layer 1 – Physical](osi_layer1_physical.md)
- [Layer 2 – Data Link](osi_layer2_datalink.md)
- [Layer 3 – Network](osi_layer3_network.md)
- [Layer 4 – Transport](osi_layer4_transport.md)
- [Layer 5–7 – Application](osi_layer5_7_application.md)
