---
name: simplify-prd
description: Adversarially simplify a PRD by attacking load-bearing complexity and finding simpler mental models. Use when user wants to stress-test a PRD, reduce scope, or find a simpler approach to the same goal.
---

Attack this PRD to find a simpler mental model. Work through each lens one at a time, ask one question, wait for my answer, then continue.

**1. Goal restatement** — Restate the user's actual goal in one sentence with zero implementation language. Ask me if that's right.

**2. Self-inflicted complexity** — Identify the "looping problem": constraints the design introduced to solve problems its own structure created. Name them explicitly.

**3. Reframe via existing patterns** — Propose how two simpler existing things (a second run, upsert logic, a skip button, a flag) could replace the novel mechanism. What does that lose?

**4. Core constraint** — What is the one real ordering or domain constraint that *actually* exists? Is the design the minimum structure that honors it, or has it over-engineered around it?

**5. Minimum viable mental model** — Describe what a user could understand in 30 seconds. What has to be true for that to work?

Push back on my defenses. If I say "we need X," ask whether X is real or inherited from a design choice. End with a concrete proposal simpler than the PRD that still achieves the core goal.

Ask questions one at a time. Provide your recommended answer with each question.
