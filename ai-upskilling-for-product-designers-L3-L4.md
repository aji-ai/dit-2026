# Moving from SAE L3 → SAE L4

## Before you start: the L3 → L4 readiness test

You’re ready to move up when all three are true:

1. **Your IDE workflows are repeatable** (not heroic).
2. **You can name your failure modes** (and what catches them).
3. **You already use protocols to plug context + tools in** (not just “chat in editor”). 

---

## SAE L3 mastery path (E-P-I-A-S) that leads into L4

### ❶ L3 Explorer → ❷ L3 Practitioner

**Goal:** Make multi-step runs reliable *in the IDE*.

What to master:

* A stable “run loop”: **plan → generate → review → revise**
* Consistent context injection (rules, constraints, repo references)
* Lightweight evals (lint/tests/checklists) as default

Concrete upgrades:

* Standard run template (same steps every time)
* “Stop & review” gates at predictable points
* Use MCP-style tools/resources to make context/tool access explicit rather than implicit

Signal you’ve mastered this step:

> “If I give this workflow to another designer in the same repo, they can reproduce the result.”

---

### ❷ L3 Practitioner → ❸ L3 Integrator

**Goal:** Decide *what* AI runs vs *what* humans approve—predictably.

What to master:

* Clear ownership boundaries (AI executes; human approves)
* Failure mode taxonomy (the top 10 ways it breaks)
* Escalation triggers (“if X, stop and ask”)

Concrete upgrades:

* “Approval gates” in the workflow (diff review, spec check, UI pass)
* Documented failure modes + fixes
* Stronger evals than checklists: structured checks, deterministic tests, or acceptance criteria

Signal:

> “I trust the workflow unless it hits a known exception class.”

---

### ❸ L3 Integrator → ❹ L3 Architect

**Goal:** Build shared workflows others can run—still IDE-centric.

What to master:

* Modular context libraries (brand voice, design system rules, constraints)
* Reusable Skills/MCP tools
* Reusable eval templates and runbooks

Concrete upgrades:

* A team “workflow pack” (prompt + context + tool wiring + evals)
* Shared MCP servers/tools to standardize tool access and reduce bespoke integrations 
* Shared workflow agents inside IDE sessions (multi-step orchestration patterns) 

Signal:

> “Teammates run my workflows and get comparable quality without me coaching live.”

---

### ❹ L3 Architect → ❺ L3 Steward

**Goal:** Standardize IDE-based agentic work safely.

What to master:

* Org norms for safety, quality, traceability
* Governance for tool access (especially MCP/tooling permissions)
* Coaching judgment, not tricks

Concrete upgrades:

* “Allowed tools / disallowed tools” policy for agents
* Review norms (what must be inspected; what can be trusted)
* Security posture awareness for tool-extended agents (tool access increases risk surface) 

Signal:

> “People trust IDE-agent work here because expectations and review gates are explicit.”

---

# The Transition: L3 → L4 (The Infrastructure Shift)

At L3, the IDE is the workspace.
At L4, the **harness becomes the workspace**.

**What changes at L4:**

* Work is triggered by events (ticket, PR, schedule), not by you typing in the IDE
* The system runs **eval → retry → escalate** on its own
* You focus on **harness design**, not step-by-step execution 

Mental shift:

> From “run this workflow with me” → “run this workflow without me, and alert me only when needed”

---

## How to move from L3 → L4 in practical steps

### Step 1: Extract your “best L3 workflow” into a runnable spec

Pick one workflow you already trust (e.g., “generate component + tests + docs”).

Turn it into:

* Inputs (requirements, constraints)
* Steps (the run sequence)
* Gates (approval points)
* Outputs (artifacts produced)

**Why:** L4 requires the workflow to exist independently of your presence.

---

### Step 2: Add eval gates that decide “pass / retry / escalate”

This is the heart of L4 harness behavior.

Minimum viable gate set:

* **Structure gate** (did it produce the right artifacts?)
* **Quality gate** (tests/lint/a11y/basic heuristics)
* **Regression gate** (diff sanity, snapshot checks)

This maps to the “agentic coding harness” idea: developer becomes supervisor; system logs, diffs, and rollback traces matter 

---

### Step 3: Implement automatic retries with corrective prompts

L4 means the system does the boring part:

* If gate fails → apply corrective instruction → retry
* If repeated failure → escalate with a crisp report

Key change vs L3:

* In L3, *you* notice and fix.
* In L4, the harness notices and fixes until it can’t.

---

### Step 4: Introduce “background execution” + auditability

Your harness should be able to run:

* While you’re in meetings
* Overnight
* As part of CI-like automation

But it must leave:

* Logs
* Diffs
* Decision traces
* Rollback plan

This is where “agentic IDEs” stop being enough and “systems” begin. ([SoftwareSeni][7])

---

### Step 5: Make it operable by others (and by the org)

L4 is not personal power—it’s shared infrastructure.

To graduate:

* Others can trigger runs
* Others can interpret failures
* The harness is maintained like a product

Tooling patterns that often show up here:

* Workflow orchestration (graphs, pipelines)
* Evaluation observability
* Shared tool servers (MCP) for consistent tool access 

---

## L3 vs L4 “tell”

* **L3:** *If you close your laptop, the system stops.*
* **L4:** *Work completes while you’re away; you only handle exceptions.*