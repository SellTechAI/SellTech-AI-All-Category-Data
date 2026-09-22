<div align="center">

# SellTech AI — All Category Data

### The structured data layer behind SellTech AI.

A centralized remote database containing curated technology product data used by the SellTech AI recommendation system.

</div>

---

## About

This repository contains the remote product database used by SellTech AI.

The database is organized by category and designed to provide structured, decision-relevant product information for recommendation, comparison, filtering, and future update workflows.

The data layer is maintained separately from the Android application so that product information can evolve independently from the APK.

---

## Current Database

**Database Version:** `v3.1.0`

**Total Records:** `1675`

**Categories:** `13`

---

## Categories

- Graphics Card
- Processor
- Motherboard
- RAM
- Storage
- Cooling
- Power Supply
- Computer Case
- Laptop
- Smartphone
- Tablet
- Game Console
- Desktop PC

---

## Data Philosophy

SellTech AI does not aim to collect every specification available.

Instead, the database focuses on information that is useful for:

- product discovery
- compatibility checks
- filtering
- recommendation logic
- comparison
- user decision-making

Where possible, the database relies on source-supported values and avoids inventing unsupported specifications.

---

## Repository Structure

Each category is maintained independently and may contain:

- category dataset
- version information
- update metadata
- source-supported product fields
- normalized values used by SellTech AI

Example structure:

```text
SellTech-AI-All-Category-Data/
│
├── graphics-cards/
├── processors/
├── motherboards/
├── ram/
├── storage/
├── cooling/
├── power-supplies/
├── computer-cases/
├── laptops/
├── smartphones/
├── tablets/
├── game-consoles/
└── desktop-pcs/
```

---

## Remote Update System

SellTech AI can use this repository as a remote data source.

This allows category data to be updated without rebuilding the entire Android application, while the application can still maintain bundled local data for reliability and offline fallback.

---

## Versioning

Database updates are versioned so the application can determine when newer remote data is available.

The current bundled database target is:

`v3.1.0`

Future updates should preserve category structure and compatibility with the SellTech AI data layer.

---

## Important

This repository contains product data only.

The main Android application and Top Picks image assets are maintained separately.

---

<div align="center">

### SellTech AI

**POWERED BY INTELLIGENCE**

</div>
