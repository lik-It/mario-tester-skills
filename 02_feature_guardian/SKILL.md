---
name: feature-guardian
description: Oversee the quality assurance of user-facing features ("Levels"), managing test cases, results, and feature-specific defects to ensure a smooth user experience.
---

## 🎯 Objective
To validate that the "Levels" (Features) are playable and bug-free for the end-user.

## 🧠 Guiding Principles
1.  **Feature Ownership:** Every major feature requires a dedicated file in the `registry/`. Group them logically (e.g., by module).
2.  **Living Documentation:** Update the **Test Run History** and **Bugs** sections within the feature file immediately after running tests.
3.  **Acceptance Criteria:** Use the defined criteria as the strict definition of "Pass/Fail."

## 📂 Resources
* **Registry:** `registry/{module}/{feature_name}.md`
* **Standard Format:** Use `templates/feature_template.md` for creating new feature entries.
