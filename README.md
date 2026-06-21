# ✈️ 2015 Aviation Performance Dashboard

An Interactive Operational Performance Framework for U.S. Domestic Flight Analytics and Strategic Network Planning.

---

## 📌 Project Overview
This Power BI solution transforms a massive dataset of over **5.8 million domestic flight records** from 2015 into an interactive Decision Support System (DSS). Designed for Airline Operations Managers, Airport Authorities, and Strategic Planners, this dashboard optimizes fleet deployment, monitors airport congestion, and uncovers carrier market positioning.

### 👥 Authors & Contributors
* **Ahmed Fawzy** (221006497)
* **Omar Khaled** (221006175)
* **Omar Tamer** (221006127)

*Presented to: Dr. Aseel Dhafer*

---

## 🛠️ Key Features & Architecture

### 1. Airline Performance & Fleet Management
* Benchmarks carrier market shares and identifies industry leaders (e.g., Southwest Airlines' massive regional presence).
* Analyzes operational efficiencies and individual carrier delays.
* Mobile-optimized layouts included for on-the-go operational tracking.

### 2. Airport Network Mapping & Geospatial Analysis
* Features an **Airport Network Map** acting as the geospatial anchor.
* Uses dynamic bubble sizing tied to flight volume to instantly separate thin regional routes from high-density trunk lines.
* Crucial for network expansion, code-share strategic planning, and identifying infrastructure bottlenecks.

### 3. Operational Reliability & Delay Attribution
* Analyzes correlation factors between high-volume stations and arrival/departure delays.
* Aggregates and categorizes cancellation metrics using standardized industry codes.

---

## 💡 Strategic Insights Discovered

* **Operational Success Rate:** The network maintained a robust overall "Ops Success Rate" of **97.44%**, proving strong systemic resilience despite day-to-day fluctuations.
* **Controllability Focus:** A notable percentage of flight disruptions were traced back to Security (Code D) and Airline/Technical factors (Code A) rather than weather. This signals that management can directly mitigate disruptions through localized process refinements.
* **Temporal Volatility:** Data revealed a sharp **25% drop in volume during holidays** (e.g., July 4th), uncovering a critical need for elastic resource and labor shifting.
* **Concentration Risk:** Certain hubs feature a single-carrier market share dominance of over **58%**, making airport throughput heavily susceptible to individual airline operational health.

---

## 📂 Repository Structure
```text
├── Data/                 # Data documentation or links to the raw 2015 Flight Performance dataset
├── Reports/              # Power BI (.pbix) files and mobile layout mockups
├── Presentation/         # Project slide deck and overview documentation
└── README.md             # Project documentation
