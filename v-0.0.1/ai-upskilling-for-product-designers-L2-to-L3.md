# Moving from SAE L2 → SAE L3

This is the **most important transition** for product designers right now.

* **L2** = AI helps you *build chunks*
* **L3** = AI helps you *run workflows*

The shift is not “more AI,” it’s **more structure, judgment, and repeatability**.

---

## SAE L2: 🚗🧠 Partially Automated

*AI builds bounded chunks; you integrate and validate*

At L2, designers are still very much “hands on the wheel,” but AI is doing **meaningful production work**.

### What L2 looks like in practice

* You generate screens, components, flows, or copy blocks
* You *manually* stitch outputs together
* QA is mostly visual + intuition
* Success depends on how clearly you prompt

### Typical L2 tools designers already use

* App & UI generators: Bolt, Lovable, Framer, v0
* Visual generators: Figma Make, Midjourney, Firefly
* General LLMs: ChatGPT, Claude, Gemini (chat mode)

---

## SAE L2 × E-P-I-A-S Growth Path

### ❶ Explorer → ❷ Practitioner (the first real win)

**Goal:** Stop “trying stuff.” Start getting *repeatable results.*

What to learn:

* Write **explicit instructions**, not vibes
* Separate *input* (requirements) from *output* (what AI returns)
* Capture what works

Concrete upgrades:

* Save prompts (even in Notes or Figma)
* Define “done” for a generated component
* Use the same prompt more than once

Signal you’ve leveled up:

> “I can reliably generate *this kind of component* with predictable quality.”

---

### ❷ Practitioner → ❸ Integrator (where maturity shows)

**Goal:** Make AI output traceable and safe to integrate.

What to learn:

* Break work into **bounded chunks** on purpose
* Add **manual QA checklists** (accessibility, hierarchy, tone)
* Document what the AI was *asked* vs what it produced

Concrete upgrades:

* Prompt templates with sections: context / constraints / output
* Explicit handoff notes: “This was AI-generated, reviewed for X, Y, Z”
* Repeatable integration patterns (where AI output fits, where it doesn’t)

Signal you’ve leveled up:

> “I can explain *why* this output is trustworthy.”

---

### ❸ Integrator → ❹ Architect (L2’s ceiling)

**Goal:** Other designers can reuse your L2 workflows.

What to learn:

* Turn good prompts into **reusable templates**
* Decide *which chunks* are worth automating
* Design guardrails, not just prompts

Concrete upgrades:

* Component-specific generators (forms, navs, empty states)
* Prompt + QA bundles (“generate → check → refine”)
* Shared libraries (Notion, Figma, repo, internal wiki)

Signal you’ve leveled up:

> “People ask to use *my* AI workflows.”

---

### ❹ Architect → ❺ Steward (org-level L2)

**Goal:** Set standards for *partial automation*.

What to learn:

* When automation helps vs hurts design quality
* Risk areas (hallucinated UX patterns, accessibility misses)
* Governance without killing speed

Concrete upgrades:

* Team guidance: “Automate these chunks, not those”
* Review standards for AI-generated UI
* Mentorship on safe integration

---

# The Transition: L2 → L3 (The Inflection Point)

This is where many designers stall.

**What changes at L3:**

* You stop thinking in *screens*
* You start thinking in *runs*

The key mental shift:

> From “generate this” → “run this workflow”

---

## SAE L3: 🚗😴 Guided Automation

*AI runs multi-step workflows; you supervise and intervene*

At L3, AI doesn’t just produce outputs — it follows **process**.

### What L3 looks like in practice

* You work inside an IDE or structured environment
* You pass **context**, not just prompts
* AI runs multiple steps in sequence
* You add checkpoints and evaluations

### Common L3 tools designers encounter

* IDEs: VS Code, Cursor
* Copilots & agents: GitHub Copilot, Claude in IDE
* Workflow tools: LangChain, n8n, Foundry, simple scripts
* Eval tools (lightweight at first): checklists, comparisons, diffs

---

## SAE L3 × E-P-I-A-S Growth Path

### ❶ Explorer → ❷ Practitioner (most designers here today)

**Goal:** Make multi-step runs reliable.

What to learn:

* Basic **context engineering** (rules, constraints, inputs)
* Sequencing tasks (“first do X, then Y”)
* Manual checkpoints

Concrete upgrades:

* Move from chat to IDE-based workflows
* Use system prompts / instruction blocks
* Add explicit “stop and review” moments

Signal you’ve leveled up:

> “My workflows don’t fall apart every other run.”

---

### ❷ Practitioner → ❸ Integrator (true L3 maturity)

**Goal:** Know when AI runs — and when humans step in.

What to learn:

* Decision framing (“AI does this unless…”)
* Lightweight evals (pass/fail, comparisons, constraints)
* Exception handling

Concrete upgrades:

* Simple eval checks (structure, length, criteria)
* Clear ownership: AI generates, human approves
* Documented failure modes

Signal you’ve leveled up:

> “I trust this workflow *until* it triggers a known exception.”

---

### ❸ Integrator → ❹ Architect (L3 power users)

**Goal:** Others can run your workflows without you.

What to learn:

* Modular context (inputs, rules, examples separated)
* Reusable Skills or agent tasks
* Shared eval patterns

Concrete upgrades:

* Reusable workflow scripts
* Context libraries (design rules, brand voice, constraints)
* Tooling others can invoke safely

Signal you’ve leveled up:

> “My system runs even when I’m not there.”

---

### ❹ Architect → ❺ Steward (org-level L3)

**Goal:** Make guided automation normal and safe.

What to learn:

* Organizational risk and reliability
* Training others on judgment, not tools
* Maintaining shared infrastructure

Concrete upgrades:

* Standards for IDE + AI usage
* Mentorship on context engineering
* Shared Skills, MCP tools, or workflow libraries

---

# The Big Takeaway for Designers

* **L2** is about *what* AI makes
* **L3** is about *how* work flows

Most designers should:

1. Go deep to **Architect or Steward at L2**
2. Then move *carefully* into **L3 Practitioner**
3. Build judgment *before* autonomy

Or said simply:

> Don’t race to automation.
> Design reliability first.