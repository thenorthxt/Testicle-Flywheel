<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/428b608a-61ab-4d99-819e-f3075036e7be" />


# Testicle-Flywheel
A memetic flywheel experiment where visibility compounds into liquidity and momentum.

# Testicle Flywheel

Testicle Flywheel is a community-driven memecoin experiment built around one thesis:

**Visibility compounds into liquidity. Liquidity sustains momentum. Momentum feeds visibility.**

This repository is a home for:
- simulations & dashboards
- token mechanic drafts
- community tooling
- narrative primitives

## The Flywheel

Testicle aims to model a loop:

1) Fees generate a budget  
2) Budget funds exposure (distribution, content, listings, tools)  
3) Exposure drives attention  
4) Attention drives demand  
5) Demand reinforces liquidity & buy pressure (optional buybacks)  
6) Momentum increases visibility again  

**Not pumps. Systems that compound.**

## Repository Structure

- `docs/` — narrative, mechanics, contribution docs
- `scripts/` — simulations and reporting tools
- `programs/` — future on-chain / automation engines
- `apps/` — dashboards and community UI
- `packages/` — reusable primitives

## Quickstart

### Python (simulation)
```bash
python scripts/simulate_flywheel.py --days 180 --seed 42
