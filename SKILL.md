---
name: gr-legal-mcp-skill
description: Official Greece (GR) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Greece Legal Research & Multi-Tier Case Law Skill (`gr-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Greece (GR)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `ECLI:EL:AREIOSPAGOS:2024:100 or ΦΕΚ A 10/2024`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Ειρηνοδικεία, Πρωτοδικεία (Courts of First Instance) & Διοικητικά Πρωτοδικεία
   - **Second Instance (Cantonal / Regional / Appellate):** 19 Εφετεία (Courts of Appeal: Athens, Thessaloniki, Piraeus, Patras, Larissa, Crete, Aegean, etc.) & Διοικητικά Εφετεία
   - **Supreme & Constitutional Instance:** Άρειος Πάγος (Supreme Civil & Criminal Court), Συμβούλιο της Επικρατείας (Council of State) & Ελεγκτικό Συνέδριο
   - **Primary Tiered Database:** OSDDY-PP / Adjustice.gr & AreiosPagos.gr National Judicial Portals (`https://www.areiospagos.gr`)
