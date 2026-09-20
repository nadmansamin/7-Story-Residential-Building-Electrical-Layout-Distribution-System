7-Story-Residential-Building-Electrical-Layout-Distribution-System
Electrical Services Design for a 7-Story Residential Building

📌 Project Overview

This project presents a complete electrical services design for a 7-story residential building, designed using **AutoCAD**. The design strictly adheres to standard Bangladesh National Building Code (BNBC) and IEEE safety guidelines, covering room-by-room illumination calculations, feeder cable sizing, circuit protection, and substation/generator sizing.

**Software Tools:** AutoCAD 2027

---

## 🏛️ Building Specifications

* **Structure:** Ground Floor (Garage/Services) + 6 Residential Floors + Rooftop
* **Residential Units:** 4 identical units per floor (24 total residential units)
* **Layout Symmetry:** Bilateral symmetry across horizontal and vertical axes
* **Unit Composition:** 4 Bedrooms, 3 Toilets, 1 Kitchen, 1 Living & Dining Space, 2 Balconies

---

## ⚡ Technical Summary & System Design

### 1. Electrical Load Parameters
| Symbol | Description | Power Rating |
| :--- | :--- | :--- |
| **F** | Ceiling Fan | 100 W |
| **L** | Bracket Light | 20 W |
| **CL** | Ceiling Light | 20 W |
| **2-Pin** | Convenience Socket | 100 W |
| **3-Pin (Q)** | Heavy Duty Power Socket | 4000 W |
| **Lift** | Elevator Motor Load | 5000 W |

### 2. Main Distribution Board (MDB) & Substation
* **Total Connected Load (MDB):** `159.245 kW`
* **Calculated Current:** `344.7 A` (Three-Phase)
* **Main Circuit Breaker:** `425A` Three-Pole MCCB
* **Main Feeder Cable:** $4 \times 300\text{ mm}^2$ NYY + $150\text{ mm}^2$ BYA ECC
* **Substation Requirement:** Dedicated **250 kVA Transformer** ($11/0.415\text{ kV}$, $50\text{ Hz}$)

### 3. Emergency System (EMDB) & Backup Power
* **Emergency Connected Load:** `15.18 kW` (Lobby/Rooftop lighting, emergency fans, and $5\text{ kW}$ lift at 0.3 UF)
* **Calculated Current:** `32.9 A`
* **Emergency Breaker:** `40A` Three-Pole MCCB
* **Emergency Cable:** $4 \times 16\text{ mm}^2$ NYY + $16\text{ mm}^2$ BYA ECC
* **Standby Generator:** **25 kW Generator** with Automatic Transfer Switch (ATS)

---

## 📊 Building Equipment Summary

| Appliance / Equipment | Total Quantity | Cable & Conduit Specification |
| :--- | :---: | :--- |
| **Ceiling Fans** | 195 | $2 \times 1.5\text{ mm}^2$ BYM (C1) |
| **Bracket Lights** | 389 | $2 \times 1.5\text{ mm}^2$ BYM (C1) |
| **Ceiling Lights** | 195 | $2 \times 1.5\text{ mm}^2$ BYM (C1) |
| **2-Pin Sockets (100W)** | 161 | $2 \times 1.5\text{ mm}^2$ BYM (C1) |
| **3-Pin Power Sockets (4000W)** | 120 | $2 \times 10\text{ mm}^2$ BYM + $10\text{ mm}^2$ BYA ECC (C9) |
| **Doorbells** | 24 | $2 \times 1.5\text{ mm}^2$ BYM (C1) |

---

## 🔑 Engineering Highlights & Design Decisions

1. **Illumination Sizing:** Fixture counts were calculated based on lumen method requirements per unit area. Single ceiling fans were chosen for $13'\times13'$ bedrooms to maintain proper physical clearance while satisfying air turnover demands.
2. **Heavy Load Handling:** Provisioned five 4000W 3-pin power sockets per residential unit to support heavy appliances (ACs, geysers, induction cooktops), driving the requirement for a transformer-backed utility connection.
3. **Custom Conduit Sizing:** Created custom conduit designations (`C11`, `C12`) for high-density wire pathways exceeding standard 12-wire limits.

---

## 📁 Repository Structure
