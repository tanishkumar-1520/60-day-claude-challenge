# Day 48 — Sourced Data Report

## Project

**The Verdict Engine — Compare & Decide Builder**

## Purpose

This report documents the sources and research methodology used for the laptop comparison decision model.

The target audience is **college students**, and the comparison criteria are:

1. Price
2. Performance
3. Battery Life
4. Display Quality
5. RAM / Storage
6. Weight / Portability

---

## 1. Source Policy

The research model uses a combination of:

* Official manufacturer specifications
* Official product/store listings
* Independent review and measurement sources where appropriate

Manufacturer specifications are preferred for factual hardware characteristics such as weight, display resolution, battery capacity, RAM and storage options.

Independent testing is useful for characteristics such as real-world battery endurance and performance because manufacturer claims may use controlled testing conditions.

---

# 2. Apple — MacBook Air

### Source

**Apple India — MacBook Air Technical Specifications**

[Apple MacBook Air Technical Specifications](https://www.apple.com/in/macbook-air/specs/?utm_source=chatgpt.com)

### Verified information

Apple's current MacBook Air specifications page lists a 15.3-inch Liquid Retina display with a 2880 × 1864 native resolution and 500-nit brightness. It also lists up to 18 hours of video streaming and up to 15 hours of wireless web use for the 15-inch model. The listed weight is 1.51 kg.

### RAM / Storage

The specifications page lists 16GB unified memory configurations and configurable memory options up to 24GB or 32GB depending on configuration. Storage configurations include 512GB, 1TB, 2TB and 4TB options depending on model/configuration.

### Data status

**Status: Sourced fact**

The values above come directly from Apple's official technical specifications.

---

# 3. Lenovo — ThinkPad E14

### Source

**Lenovo India — ThinkPad E14 Product Listing**

[Lenovo ThinkPad E14 India Product Listing](https://store.lenovo.com/in/en/thinkpad-e14-35-56cms-black-20tas0aj00-1967.html?utm_source=chatgpt.com)

### Verified information

The referenced Lenovo India listing specifies an Intel Core i5-1135G7 processor, 8GB DDR4 memory and 512GB SSD. It lists a 14-inch Full HD 1920 × 1080 IPS anti-glare display, 1.6 kg weight, a 45Wh three-cell battery and up to 8 hours of battery life. The listing showed a price of ₹72,990 when retrieved.

### Data status

**Status: Sourced fact for the specific listed configuration**

The figures apply to the particular configuration shown by Lenovo and should not automatically be generalized to every ThinkPad E14 configuration.

### Important limitation

Laptop families can have multiple processor, memory, storage and display configurations. Therefore, comparisons should match equivalent configurations wherever possible.

---

# 4. Dell — Inspiron 14

### Source

**Dell India — Inspiron 14 Product Information**

[Dell India Inspiron 14](https://www.dell.com/en-in/shop/laptops/inspiron-14/spd/inspiron-14-5441-laptop?utm_source=chatgpt.com)

### Verified information

Dell's current Inspiron 14 product information lists a maximum weight of 1.53 kg for the referenced configuration and a 54Wh three-cell battery. The page also lists configuration-dependent processors, ports and other hardware characteristics.

Another current Dell India Inspiron 14 listing identifies starting weights around 1.54–1.56 kg depending on chassis configuration.

### Data status

**Status: Sourced fact**

### Important limitation

Dell explicitly notes that specifications and weight can vary according to configuration. Therefore, a specific configuration should be identified before using the data for a purchasing decision.

---

# 5. HP — Pavilion / HP 14

### Source

**HP Support — HP 14-inch Laptop PC Specifications**

[HP 14-inch Laptop PC Specifications](https://support.hp.com/in-en/document/ish_7421478-7421545-16?utm_source=chatgpt.com)

The HP specification page lists a starting weight of 1.4 kg for the referenced HP 14 series and a 41Wh three-cell lithium-ion polymer battery. It also states that weight varies according to configuration and components.

### Additional HP Pavilion source

**HP Support — Pavilion 14-dv0075TX Product Specifications**

[HP Pavilion 14-dv0075TX Specifications](https://support.hp.com/us-en/document/c07029981?utm_source=chatgpt.com)

The referenced Pavilion 14 configuration lists:

* Intel Core i7-1165G7 processor
* 8GB DDR4 memory
* 512GB PCIe NVMe SSD
* 14-inch Full HD IPS display
* 1920 × 1080 resolution
* 250-nit brightness
* Starting weight of 1.41 kg
* 43Wh battery
* Up to 8 hours 15 minutes mixed-use battery life

These specifications apply to that specific Pavilion configuration.

### Data status

**Status: Sourced fact for the referenced configurations**

---

# 6. Independent Research Sources

## Notebookcheck

[Notebookcheck](https://www.notebookcheck.net/?utm_source=chatgpt.com)

Notebookcheck can be used for independent laptop reviews, performance measurements, display measurements and battery testing.

Independent measurements are especially useful when manufacturer specifications do not directly provide comparable real-world results.

## PCMag

[PCMag](https://www.pcmag.com/?utm_source=chatgpt.com)

PCMag provides independent laptop reviews and testing information that can supplement manufacturer specifications.

---

# 7. Criterion Research Method

## Price

Price should be taken from a dated retailer or manufacturer listing for a clearly specified configuration.

### Important limitation

Laptop prices can change because of:

* Region
* Promotions
* Discounts
* Configuration
* Retailer
* Date

Therefore, a price should always be treated as time-sensitive.

---

## Performance

Performance should ideally be compared using the same benchmark methodology and equivalent configurations.

Manufacturer CPU names alone should not be converted into an invented numerical performance score.

### Data status

**Requires benchmark-based normalization for production use.**

---

## Battery Life

Battery information can come from:

1. Manufacturer battery-life claims
2. Independent real-world testing

These values should not automatically be treated as equivalent.

Manufacturer testing can use controlled conditions, while independent reviewers may use different workloads, brightness settings and power profiles.

---

## Display Quality

Display comparison should consider measurable specifications such as:

* Resolution
* Brightness
* Panel technology
* Refresh rate where relevant
* Color coverage where available

A display-quality score should only be calculated from documented measurements or a clearly explained normalization methodology.

---

## RAM / Storage

RAM and storage should be taken directly from the exact product configuration being compared.

Different configurations of the same laptop family can have different memory and storage capacities.

---

## Weight

Weight should be taken from the manufacturer's specification for the specific configuration whenever possible.

Weight can vary between configurations, chassis materials and components.

---

# 8. Source Conflicts and Resolution

## Conflict 1 — Manufacturer Battery Claims vs Independent Testing

Manufacturer battery-life figures and independent test results may differ.

### Resolution

Both should be kept as separate measurements rather than silently replacing one with the other.

For a decision model, the methodology should clearly state which measurement is being used.

---

## Conflict 2 — Product Family vs Exact Configuration

A laptop family can contain multiple CPUs, RAM configurations, storage options and displays.

### Resolution

The exact configuration should be recorded alongside each data point.

A product-family specification should not be presented as if it describes every configuration.

---

## Conflict 3 — Current Price vs Historical Price

Laptop prices can change frequently.

### Resolution

Prices should be stored with:

* Currency
* Date checked
* Retailer/manufacturer
* Exact configuration

Historical prices should not be presented as current prices.

---

# 9. Synthetic Demonstration Scores

The current `verdict-engine.html` contains normalized values such as:

```text
Price: 0–100
Performance: 0–100
Battery: 0–100
Display: 0–100
Storage: 0–100
Weight: 0–100
```

These values are explicitly labeled in the application as:

**Synthetic demonstration**

They are included to demonstrate the weighted-ranking engine and are **not claimed to be verified product scores**.

No synthetic score should be interpreted as an independently measured benchmark.

---

# 10. Production Data Requirements

Before using this application for a real purchasing decision, the demonstration dataset should be replaced with:

* Exact laptop model numbers
* Exact configurations
* Current prices
* Date-stamped source information
* Verified RAM and storage
* Manufacturer battery specifications
* Independent battery measurements where available
* Display measurements
* Consistent performance benchmarks
* Exact product weights

Each numerical value should retain a source reference.

---

# 11. Research Transparency

The purpose of the Sources panel and **"How this was researched"** panel is to make the decision process inspectable.

The application should allow users to distinguish between:

**Sourced fact**

and

**Synthetic / estimated value**

This distinction is important because a weighted calculation can appear precise even when the underlying inputs are uncertain.

---

# 12. Final Data Status

| Criterion       | Source Availability                        | Status                                 |
| --------------- | ------------------------------------------ | -------------------------------------- |
| Price           | Manufacturer / retailer listings           | Time-sensitive sourced data            |
| Performance     | Independent benchmark sources required     | Requires matched benchmark methodology |
| Battery Life    | Manufacturer + independent testing         | Source-dependent                       |
| Display Quality | Manufacturer specifications + measurements | Configuration-dependent                |
| RAM / Storage   | Manufacturer specifications                | Configuration-specific                 |
| Weight          | Manufacturer specifications                | Configuration-specific                 |

## Conclusion

The research demonstrates how official specifications and independent testing can be combined to create a transparent laptop comparison workflow.

The current application is a **decision-engine demonstration**. Its synthetic normalized scores must be replaced with verified, configuration-specific and date-stamped research before the tool is used to make an actual purchasing decision.

## Primary Sources

* Apple — MacBook Air Technical Specifications
* Lenovo India — ThinkPad E14 listing
* Dell India — Inspiron 14 product information
* HP Support — HP 14 specifications
* HP Support — Pavilion 14 specifications
* Notebookcheck — Independent laptop testing
* PCMag — Independent laptop reviews
