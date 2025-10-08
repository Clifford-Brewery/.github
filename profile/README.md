# Clifford Brewery • Civic Mesh Home

Welcome! This is the lightweight workspace we’re using to coordinate
day-to-day publishing (events & promos) and our public-trust pilot
(attestations). It’s meant to be friendly and low-overhead.

---

## Where to start

**1) Accept your invitations**
- You’ll see invites to three GitHub organizations:
  - **Clifford-Brewery** (this page): Clifford’s own workspace
  - **Nashdale-Civic-Mesh**: our neighborhood commons
  - **Civic-Mesh-Network**: the federation (shared templates/standards)

**2) Two things you can do right away**
- **Add an event or promo** (staff-only): _Publisher_  
  → `http://10.0.0.223/cl/media/publisher/` (on the Clifford laptop “Bunky”)
- **See what’s public** (pilot): Attestations index  
  → https://github.com/Clifford-Brewery/clifford-attestations-public

If you’d like a walkthrough, ping Chris (QuietWire) and we’ll hop on a call.

---

## What lives where

**Clifford-Brewery (private unless noted)**
- `qw-ui-clifford` – the internal website (“Bunky”) including the Publisher
- `clifford-events` – agendas & event assets (run-of-show, staffing)
- `clifford-process` – policies & checklists (consent, publishing, ops)
- `clifford-network` – ISP/router/VLANs & remote-access plan
- `clifford-civic-node` – host build & “heartbeat” (mesh pulse) scripts
- `clifford-attestations` – working folder for attestations (private)
- `clifford-attestations-public` – **public** attestation index

**Nashdale-Civic-Mesh (neighborhood)**
- `entities` – businesses/orgs (cards)
- `projects` – active work streams
- `zones` – boundaries/overlays (GeoJSON)
- `mesh-map` – the neighborhood map

**Civic-Mesh-Network (federation)**
- `templates` – ready-to-copy cards & repo scaffolds
- `schema` – shared data shapes (entities, personas, projects, zones)
- `playbooks` – outreach, RF/LoS planning, safety, governance

---

## How publishing works (2 paths)

**A) Routine updates (fast path)**
1. Staff enter **Event/Promotion** in Publisher (Bunky).
2. It writes simple JSON that the site reads (and can sync to WordPress later).
3. Optional: set “needs review” if you want a second set of eyes.

**B) Public-trust items (attestations)**
1. When a claim matters (e.g., “all-ages show”, “accessible seating”), add a
   small **attestation** file that says _who/what/when_ and links to evidence.
2. Public index lives here: `clifford-attestations-public`
3. Private drafts/assets live in `clifford-attestations` until approved.

---

## Privacy & guardrails (short version)

- **Consent first**: only publish what people agree to share.
- **Proportionate**: attest only what’s relevant to the public.
- **Open & portable**: plain files (JSON/Markdown); easy to move to other sites.
- **Review when needed**: “Needs review” keeps a human-in-the-loop.

---

## Need help?

- **Darlene** – Clifford leadership & approvals  
- **Ian / taproom team** – events & promotions  
- **QuietWire (Chris / Lumina)** – setup, support, federation links  
  → chris@quietwire.ai

_© 2025 QuietWire • Clifford Civic AI Pilot_
