---
name: jtbd:copy
description: Rewrite UI copy through a JTBD lens. Use with specific copy text, a file to audit, or in context of current work.
arguments:
  - name: input
    description: Copy text to rewrite, or file path to audit
    required: false
---

Use the dcode:jtbd-copy skill.

**Quick reference:**

| Usage | What it does |
|-------|--------------|
| `/jtbd:copy "Submit"` | Rewrite copy through JTBD lens |
| `/jtbd:copy src/components/Form.tsx` | Audit a file's copy for JTBD alignment |
| `/jtbd:copy` | Review copy in current context |

Input: $ARGUMENTS
