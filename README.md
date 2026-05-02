# Rwanda Energy Calculator

A fast, fully static web app for calculating electricity costs based on [Rwanda Energy Group (REG)](https://www.reg.rw/) tariffs. No server, no build step, no dependencies — pure HTML, CSS, and JavaScript.

> **Original calculator logic** by [Ian Akotey](https://github.com/ianakotey) · **UI** by [Richard Djarbeng (RDjarbeng)](https://github.com/RDjarbeng)

## Related

- 🐍 **Python version:** [rwanda\_energy\_calculator](https://github.com/RDjarbeng/rwanda_energy_calculator) — the original FastHTML/Python implementation this JS version is based on

---

## Features

### ⚡ Calculator
- **Amount → Units** — enter how much you're paying (RWF) and see exactly how many kWh you'll receive
- **Top-up mode** — enter a previous balance to account for tier-offset pricing (units are cheaper at the start of the month)
- **Units → Cost** — enter units consumed (kWh) and get the full cost breakdown
- Full per-tier breakdown showing Tier 1, Tier 2, and Tier 3 usage and cost
- VAT (18%) shown separately

### 🏠 Household Estimator
- Select appliances from a preset list and set quantities
- Estimates monthly and daily kWh consumption and bill
- Consumption breakdown shows which appliances use the most power
- Adjust wattage and hours/day per appliance for accurate results
- Add custom appliances with a name, icon, wattage, and daily usage

### General
- Toggle between **October 2025 tariffs** (current) and **2020–2025 tariffs**
- Fully responsive — works on desktop and mobile
- Real-time calculations — results update as you type or adjust quantities

---

## Tariff Structure

### October 2025 (current)
| Tier | Consumption | Rate |
|------|------------|------|
| Tier 1 | 0 – 20 kWh/month | 89 RWF/kWh |
| Tier 2 | 21 – 50 kWh/month | 310 RWF/kWh |
| Tier 3 | 51+ kWh/month | 369 RWF/kWh |

### 2020 – 2025
| Tier | Consumption | Rate |
|------|------------|------|
| Tier 1 | 0 – 15 kWh/month | 89 RWF/kWh |
| Tier 2 | 16 – 50 kWh/month | 212 RWF/kWh |
| Tier 3 | 51+ kWh/month | 249 RWF/kWh |

VAT of 18% applies to all tiers.

**Sources:** [REG official tariffs](https://www.reg.rw/customer-service/tariffs/) · [RURA October 2025 announcement](https://rdjarbeng.com/rura-announces-revised-electricity-end-user-tariffs-effective-october-2025/)

---

## Tech

Single `index.html` file — no frameworks, no bundler, no runtime dependencies.
