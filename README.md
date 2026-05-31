ICM Protocol

The ICM Protocol is the open, role‑adaptive standard that powers identity‑driven, spatially rendered product experiences across the ICM ecosystem. It defines how a single physical scan (QR, NFC, RFID, optical glyph) resolves into a role‑specific digital reality, using a combination of:


• ICM Handles
• Harmonic Hex Strings
• Identity Resolution
• Role‑Based Permissions
• Scene Manifests
• Data Vectors
• Webhook/Event Contracts

This repository serves as the canonical specification for how clients, services, and enterprise systems interact with ICM‑native products.
It is public by design to support interoperability, transparency, and ecosystem growth

✨ What the ICM Protocol Enables

Role‑Adaptive Rendering

A single physical product scan can produce completely different digital experiences depending on the viewer’s identity:

• Consumers → narrative 3D “Awakened Product”
• Auditors → compliance control room
• Manufacturers → batch‑level production data
• Regulators → certification and recycling proofs


The protocol defines how these branches occur.
Secure Multi‑Layer Identity

The protocol standardizes:

• Web3 identity
• Enterprise SSO
• Device trust scoring
• Role assignment
• Scope‑based permissions


This ensures sensitive supply chain data is only accessible to authorized parties.

Scene Manifest Generation

The harmonic hex string expands into a Scene Manifest, which tells the client:

• What to render
• What data vectors to fetch
• What permissions apply
• What UI layout profile to use
• What runtime constraints to follow

This is the core of ICM’s “one scan, multiple realities” architecture.

Data Vector Access

The protocol defines the structure and permissions for all data vectors, including:

• Identity summaries
• Material composition
• Sustainability metrics
• Supply chain nodes
• Transport logs
• Customs documents
• Factory certifications
• Recycling proofs
• Anomaly maps


Each vector is permission‑gated and role‑scoped.

AI Companion Integration

The protocol includes the contract for attaching an AI Companion to any scene, enabling:

• Product Q&A
• Care instructions
• Authenticity verification
• Compliance assistance
• Workflow automation


This bridges consumer experience and enterprise intelligence.

Telemetry & Webhooks

The protocol defines how clients send:

• Scene events
• Interaction logs
• Audit actions


And how servers emit:

• Compliance anomalies
• Ledger inconsistencies
• Role‑elevation requests

📁 Repository Structure

/
├── README.md
├── api/
│   ├── rest/
│   └── graphql/
├── models/
├── examples/
│   ├── consumer_flow/
│   └── auditor_flow/
├── webhooks/
└── CHANGELOG.md


Each folder contains specification‑level definitions only — no implementation code.

📜 Versioning

The ICM Protocol follows semantic versioning (semver):

• MAJOR — breaking changes
• MINOR — new fields, vectors, or flows
• PATCH — corrections or clarifications


See the versioning guide for details.

---

🧩 Who This Repo Is For

• Brands implementing ICM‑native product experiences
• Manufacturers integrating supply chain data
• Auditors and compliance platforms
• Developers building ICM‑compatible clients
• Researchers and standards bodies
• Third‑party ecosystem contributors
