# Data Center Power Infrastructure Design & Monitoring

![Critical Power](https://img.shields.io/badge/Domain-Critical%20Power%20Systems-red)
![UPS Systems](https://img.shields.io/badge/Focus-UPS%20%26%20Switchgear-orange)
![Uptime Institute](https://img.shields.io/badge/Standard-Uptime%20Institute%20Tiers-blue)
![Grafana](https://img.shields.io/badge/Monitoring-Grafana-orange)
![NFPA 70E](https://img.shields.io/badge/Safety-NFPA%2070E-red)
![Schneider DCCA](https://img.shields.io/badge/Cert-Schneider%20DCCA-green)

---

## Project Overview

This project documents a complete data center power infrastructure design including UPS architecture, PDU layout, switchgear protection schemes, redundancy configurations, and real-time power monitoring — aligned with Uptime Institute Tier standards and NFPA 70E electrical safety requirements.

Built to demonstrate operational readiness for:
- ✅ Critical Infrastructure Engineer roles
- ✅ Data Center Operations Engineer roles
- ✅ Facilities Engineer roles
- ✅ Data Center Design Engineer roles

---

## Real World Foundation

This documentation is informed by hands-on operational experience managing:

- **Production UPS systems** protecting mission-critical server infrastructure
- **Power distribution** across rack environments supporting nationwide operations
- **Electrical safety procedures** in high-voltage industrial environments
- **Real-time power monitoring** using operational dashboards and SCADA systems

---

## Repository Structure
---

## Power Architecture Overview
---

## UPS Sizing Guide

### Calculation Methodology
### Example Calculation

### Redundancy Configurations

| Configuration | Description | Availability |
|---|---|---|
| N | No redundancy — single UPS | 99.671% |
| N+1 | One extra UPS module | 99.741% |
| 2N | Full redundancy — dual UPS | 99.982% |
| 2N+1 | Dual UPS plus extra module | 99.999% |

---

## Power Monitoring Dashboard

### Key Metrics Monitored

| Metric | Normal Range | Warning | Critical |
|---|---|---|---|
| UPS Input Voltage | 208–240V | ±10% | ±15% |
| UPS Output Voltage | 208–240V | ±5% | ±10% |
| UPS Load % | Below 70% | 70–80% | Above 80% |
| Battery Charge | Above 95% | 80–95% | Below 80% |
| Battery Temperature | 20–25°C | 25–30°C | Above 30°C |
| PDU Load % | Below 70% | 70–80% | Above 80% |
| Generator Fuel Level | Above 75% | 50–75% | Below 50% |

---

## Power Load Calculations

### Per Rack Power Density

| Rack Type | Power Density | Cooling Required |
|---|---|---|
| Standard Compute | 5–10 kW/rack | CRAC air cooling |
| High Density | 10–20 kW/rack | In-row cooling |
| GPU/AI Compute | 20–100 kW/rack | Liquid cooling |
| Hyperscale | 100kW+/rack | Direct liquid cooling |

### Data Center Power Flow
---

## PDU Layout Design

### Rack PDU Configuration

| Position | PDU Type | Circuit | Breaker |
|---|---|---|---|
| Left side | Primary PDU A | 20A circuit | 20A breaker |
| Right side | Secondary PDU B | 20A circuit | 20A breaker |
| Top of rack | Monitoring PDU | Metered | Per outlet |

### PDU Naming Convention

---

## Electrical Safety — NFPA 70E Compliance

### Arc Flash Safety Requirements

| Voltage Level | PPE Category | Minimum PPE |
|---|---|---|
| Up to 240V | Category 1 | Arc rated shirt and pants |
| 240V–600V | Category 2 | Arc rated clothing 8 cal/cm² |
| 600V–15kV | Category 3 | Arc rated suit 25 cal/cm² |
| Above 15kV | Category 4 | Arc rated suit 40 cal/cm² |

### Lockout/Tagout Procedure
1. Notify all affected personnel
2. Identify all energy sources
3. Shut down equipment using normal procedures
4. Isolate all energy sources
5. Apply lockout/tagout devices
6. Release or restrain stored energy
7. Verify isolation with test equipment
8. Perform work safely
9. Remove lockout/tagout devices
10. Restore energy and verify normal operation

---

##  PUE Tracking & Optimisation

### PUE Targets by Tier

| Data Center Type | Target PUE | World Class |
|---|---|---|
| Legacy Facility | Below 2.0 | Below 1.8 |
| Modern Facility | Below 1.5 | Below 1.3 |
| Hyperscale | Below 1.3 | Below 1.1 |
| Edge Data Center | Below 1.5 | Below 1.3 |

### PUE Improvement Strategies

| Strategy | PUE Improvement | Implementation |
|---|---|---|
| Hot/Cold aisle containment | 0.1–0.2 | Physical containment |
| Economizer cooling | 0.2–0.4 | Free cooling when ambient allows |
| UPS efficiency mode | 0.05–0.1 | ECO mode operation |
| Variable speed drives | 0.05–0.1 | Fan and pump optimisation |
| LED lighting | 0.01–0.02 | Lighting replacement |
| Higher inlet temperatures | 0.05–0.1 | ASHRAE A2 compliance |

---

## Standards & Frameworks Referenced

- **Uptime Institute Tier Standards** — I through IV availability classifications
- **NFPA 70E** — Electrical Safety in the Workplace
- **IEEE 3006** — Recommended Practices for Industrial Power Systems
- **IEC 62040** — UPS Systems Standards
- **ASHRAE TC 9.9** — Thermal Guidelines
- **ANSI/TIA-942** — Data Center Infrastructure Standards
- **The Green Grid** — PUE measurement methodology

---

## Tools & Technologies

![Grafana](https://img.shields.io/badge/Grafana-Power%20Monitoring-orange)
![Prometheus](https://img.shields.io/badge/Prometheus-Metrics-orange)
![DCIM](https://img.shields.io/badge/DCIM-Power%20Management-blue)
![Schneider](https://img.shields.io/badge/Schneider-EcoStruxure-green)
![NFPA](https://img.shields.io/badge/NFPA%2070E-Electrical%20Safety-red)
![Uptime](https://img.shields.io/badge/Uptime%20Institute-Tier%20Standards-blue)

---

## Author

**George Amankwaa Sarpong**
Critical Infrastructure Engineer | Data Center Power Systems
📍 Accra, Ghana
🔗 [LinkedIn](https://linkedin.com/in/georgesarpong)
🌐 [GitHub Portfolio](https://github.com/GeorgeSarpong)

---

*This project is part of a broader portfolio demonstrating readiness for Critical Infrastructure Engineer and Data Center Operations roles in the US and global market.*
