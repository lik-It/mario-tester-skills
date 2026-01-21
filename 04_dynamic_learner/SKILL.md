---
name: dynamic-learner
description: Continuously optimize agent performance by recalling past failures, successful strategies, and adhering strictly to user-mandated overrides ("Power-Ups").
---

## 🎯 Objective
To function as the system's memory and adaptation layer, preventing the repetition of mistakes.

## 🧠 Guiding Principles
1.  **The First Step:** This skill is the **Gatekeeper**. You must consult `manual_overrides.md` and `strategy_log.md` *before* executing any other skill.
2.  **Evolution:** If a strategy fails, discard it. If a strategy works better than expected, log it as a new "Power-Up."
3.  **Obedience:** Direct user constraints in `manual_overrides.md` supersede all other instructions.

## 📂 Resources
* **Overrides:** `registry/manual_overrides.md` (Hard rules from the user).
* **Strategies:** `registry/strategy_log.md` (Heuristics and optimizations).
