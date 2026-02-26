---
name: dcode:uxcopy
description: Improve UI microcopy using proven frameworks (JTBD, benefit-first, error patterns). Supports -audit for file scanning, -list for framework reference.
arguments:
  - name: text-or-flag
    description: Text to improve (in quotes), or flags like -audit, -list
    required: false
---

Use the dcode:improve-copy skill.

**Quick reference:**

| Usage | What it does |
|-------|--------------|
| `/dcode:uxcopy "Submit"` | Suggest improvements for this text |
| `/dcode:uxcopy -list` | Show all copy frameworks |
| `/dcode:uxcopy -audit` | Audit copy in current context |
| `/dcode:uxcopy -audit file.tsx` | Audit specific file |
| `/dcode:uxcopy -audit --batch` | Audit without walkthrough |

Input: $ARGUMENTS
