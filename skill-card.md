---
name: declutter-pilot
description: Physics-based decluttering — volume-first sorties, bag math, decision rules, disposition manifests.
version: 1.0.0
author: Denis Voronin
license: MIT
tags: [decluttering, organization, moving, minimalism, cleaning]
---

# Declutter Pilot

**Do the physics first, decide second.**

Item registry with volumes, greedy 20-minute sorties ranked by liters-freed
per decision-difficulty (easy bulky wins first, sentiment last), container
math (bags/boxes/car-loads/$-per-year storage), five decision tests with
cost-of-keeping, and sell/donate/recycle/trash manifests. 100% local.

## Quick Start
```bash
python3 scripts/declutter.py item add "Broken chair" --room office --volume 80 --difficulty 1 --decision toss
python3 scripts/declutter.py plan
python3 scripts/declutter.py sortie start
python3 scripts/declutter.py sortie done --bags 3
python3 scripts/declutter.py manifest
```

For clutter, not hoarding disorder — that's a clinical situation needing
professional support.
