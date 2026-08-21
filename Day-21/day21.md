# Day 21: Digital Privacy & Footprint Dashboard

## Overview
This repository contains the Day 21 project for analyzing and visualizing a user's digital footprint and privacy exposure based on a reported dataset of 15 services. The interactive dashboard evaluates digital footprint metrics, risk levels, data asset values, ecosystem concentration, and privacy improvement paths.

---

## Sample User Dataset (Facts)
The analysis was performed on the following 15 reported services:
* **Social & Messaging:** Instagram, Snapchat, TikTok, WhatsApp, iMessage, Discord
* **Media & Entertainment:** YouTube, Spotify
* **Gaming:** Roblox, PUBG Mobile
* **Commerce & Finance:** Amazon, Meesho, Google Pay
* **Cloud & Search:** Google Search, Google Photos

---

## Summary of Findings & Metrics

### Key Metrics Summary
| Metric | Result | Interpretation |
| :--- | :--- | :--- |
| **Digital Footprint Score** | **84 / 100** | 🔴 **Extensive** (High volume and breadth across payments, location, biometrics, and messaging) |
| **Initial Privacy Score** | **28 / 100** | 🔴 **Weak** (Unrestricted permissions across core platforms) |
| **Total Services Used** | **15** | Fact |
| **Parent Companies** | **8** | Alphabet Inc., Meta Platforms, ByteDance, Tencent, Snap Inc., Apple Inc., Amazon Inc., Fashnear Tech |
| **Ecosystem Concentration** | **73%** | High dominance by Alphabet Inc. and Meta Platforms |

---

## Detailed Section Analyses

### 1. Ecosystem Concentration & Parent Company Exposure
* **Alphabet Inc.** (Google Search, Google Pay, Google Photos, YouTube): Highest single points of risk. Tracks geolocation, financial transactions, facial data, search intent, and video watch patterns.
* **Meta Platforms** (Instagram, WhatsApp): Tracks social connection graphs, private direct messages metadata, and media uploads.
* **ByteDance & Tencent** (TikTok, PUBG Mobile): High behavioral engagement and device telemetry collection.

### 2. Exposure Heatmap Summary
* **Critical / High Exposure:** Precise Real-Time Geolocation, Contact Graphs, Biometric/Photo Metadata, Financial Transaction Logs.
* **Medium Exposure:** Search History, Browsing Data, In-App Purchase Records, Audio Patterns.

### 3. Digital Twin Profile (Estimates)
> **Note on Methodology:** All behavioral, lifestyle, and demographic inferences are labeled as **Estimates**. No private databases or certainty claimed.

* **Archetype:** Highly Connected Urban Gamer / Active Content Consumer
* **Lifestyle Trait:** Heavy short-form video consumption (TikTok, YouTube) paired with multiplayer social gaming (Roblox, PUBG Mobile).
* **Financial Behavior:** Digitally native shopper using UPI payments (Google Pay) and cross-border/value e-commerce (Amazon, Meesho).
* **Communication Pattern:** Multi-tiered social communication across encrypted channels (WhatsApp, iMessage) and open community hubs (Discord).

### 4. Most Valuable Data Assets
1. **Real-time Geolocation:** Highest value for local ad targeting and pattern analysis.
2. **Financial & Purchase Records:** High commercial value for transaction modeling and credit scoring.
3. **Facial & Photo Metadata:** Biometric training and visual preference modeling.
4. **Behavioral Graph:** High value for recommendation engine optimization.

---

## Interactive Privacy Improvement Simulator

The included `dashboard.html` features an interactive simulator allowing users to test privacy remediation actions:

| Action Item | Score Impact | Resulting Privacy Rating |
| :--- | :---: | :---: |
| **Initial Baseline** | +0 | **28 / 100 (Weak)** |
| Revoke Precise Location on Social Platforms | +15 | **43 / 100 (Fair)** |
| Enable Auto-Delete for Google Activity History | +20 | **63 / 100 (Good)** |
| Enable App Tracking Transparency / Opt-Out of Personalized Ads | +18 | **81 / 100 (Strong)** |

---

## Final Verdict
The user's overall digital footprint is **Extensive (84/100)** due to heavy concentration within major tech ecosystems (Alphabet & Meta). However, applying high-impact privacy controls (location restriction, activity auto-deletion, ad-tracking opt-outs) raises the Privacy Score from **28 (Weak)** to **81 (Strong)** without requiring the deletion of any service accounts.

---

## Dashboard Screenshots & Files
- `dashboard.html` — Interactive Single-File HTML Privacy Dashboard.
- Open `dashboard.html` in any browser to explore heatmaps, risk matrix, and live simulator.
