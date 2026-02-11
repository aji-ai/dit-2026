# AI Upskilling for Product Designers: The SAE × E-P-I-A-S Framework

I made this system after being asked for one. And I know that by the time I publish it, it's not going to be perfectly correct. That said, something is better than nothing right now, so here it is.

I'm presenting this as part of the [Design in Tech Report 2026: From UX to AX](https://schedule.sxsw.com/2026/events/PP1148536) at SXSW, but I wanted to open source it sooner rather than later. If you're a product designer trying to figure out where you stand with AI, or a design leader trying to upskill your team, I hope this gives you a useful frame.

This will be subject to more than a few changes this year. I know that for sure ;-). —JM

---

## How to Use This

This framework has two axes:

**E-P-I-A-S** describes how deeply you've internalized a skill, from Explorer (trying things out) to Steward (setting standards for others).

| ❶ E: Explorer | ❷ P: Practitioner | ❸ I: Integrator | ❹ A: Architect | ❺ S: Steward |
| --- | --- | --- | --- | --- |
| Trying things; learning basics | Building consistent habits | Making it part of workflow | Building systems others use | Setting standards; teaching others |

You naturally progress ❶ E → ❷ P → ❸ I → ❹ A → ❺ S.

**SAE Level** describes how much responsibility AI holds in your workflow. It's adapted from the automotive industry's levels of driving automation.

![](https://users.ece.cmu.edu/~koopman/j3016/J3016_table.jpg)

via [CMU](https://users.ece.cmu.edu/~koopman/j3016/#overview)

Together they form a matrix. Here's how to navigate it:

1. **Situate your E-P-I-A-S maturity stage, which will vary depending on the level you are pursuing.** Are you just experimenting (Explorer)? Running consistent workflows (Practitioner)? Building systems others rely on (Architect)? Your maturity at your current level matters more than which level you're at.

2. **Find your SAE Level(s) that you are pursuing in this AI revolution.** Use the self-assessment to identify where your current AI usage falls, from L0 (fully manual) to L4 (mostly automated). Be honest. Most product designers in early 2026 are somewhere between L1 and L2.

3. **Use the SAE matrix to plan your growth.** You can grow in two directions: deeper (E→S within your current SAE level) or wider (moving up an SAE level). Both are valuable. Going deeper at L1 before jumping to L3 is often the smarter path, because the judgment and habits you build carry forward.

**BONUS:** If you're a design leader, use this to map your team. You'll likely find people spread across multiple SAE levels and maturity stages. That's normal and healthy. The framework helps you have concrete conversations about where people are and where they want to go, without it becoming a race to the highest SAE number.

One important thing to internalize: **an S-Steward at SAE L1 (someone who's built organizational standards for ChatGPT/Microsoft Copilot usage) is more mature and more valuable than an E-Explorer at SAE L4 (someone fumbling with advanced toolchains).** Depth of judgment beats breadth of tooling every time.

---

# Step 1: Get Familiar With E-P-I-A-S Learning Stages

We start with a generic maturity progression for a learner. HT Monty Hammontree for his advice on this instrument that I changed a teense to create the catchy acronym E-P-I-A-S.

## Learner Maturity Stages As E-P-I-A-S

| ❶ E: Explorer | ❷ P: Practitioner | ❸ I: Integrator | ❹ A: Architect | ❺ S: Steward |
| --- | --- | --- | --- | --- |
| Trying things; learning basics | Building consistent habits | Making it part of workflow | Building systems others use | Setting standards; teaching others |

You naturally progress ❶ E → ❷ P → ❸ I → ❹ A → ❺ S. Let's apply this to the conventional non-AI product designer's progression in skillsets.

## Non-AI Product Designer Skillset Progression

| ❶ E: Explorer | ❷ P: Practitioner | ❸ I: Integrator | ❹ A: Architect | ❺ S: Steward |
| --- | --- | --- | --- | --- |
| Learning design fundamentals; quality varies, needs guidance | Consistent design process; repeatable methods and quality checks | Design embedded end-to-end in product development; clear rationale and validation | Building design systems, processes, and frameworks that others adopt | Setting organizational design standards; mentoring designers; maintaining shared systems |

This bears a parallel to the career progression "ladder" in product design today.

## Conventional Product Design Career Progression

| ❶ E: Explorer | ❷ P: Practitioner | ❸ I: Integrator | ❹ A: Architect | ❺ S: Steward |
| --- | --- | --- | --- | --- |
| Junior Designer | Designer/Mid-level | Senior Designer | Staff/Principal Designer | Director/Design Lead |

Keep in mind that a director or lead can still behave like an "Explorer" by having a beginner's mind. Right? They truly need to have that right now in the age of AI.

Do you get the idea of E-P-I-A-S? Awesome! Now locate your SAE level of operating in the AI era, and situate the stage you might be in right now.

---

# Step 2: Find Your SAE Level

## SAE Levels of Driving Automation (SAEJ3016 est 2014)

Let's take learnings for how AI's progression is being tracked best: the automotive industry. The official SAE (Society of Automotive Engineers) levels of driving automation describe who is responsible for driving (the human or the vehicle) across perception, decision-making, and control.

| SAE Level | Name | Who Drives / Is Responsible | Plain-English Explanation | Everyday Examples |
| --- | --- | --- | --- | --- |
| SAE L0 <br/>🚗💨 | No Automation | Human does everything | No driving automation; the system may warn but never controls the car | Basic alerts, lane-departure warnings |
| SAE L1 <br/>🚗➕ | Driver Assistance | Human drives; system assists one function | The car can help *either* steering *or* speed, but not both at once | Adaptive cruise control, lane keeping assist |
| SAE L2 <br/>🚗🧠 | Partial Automation | Human supervises; system controls steering *and* speed | The car can steer and control speed together, but *you must watch and intervene* | Tesla Autopilot, GM Super Cruise (hands-on variants) |
| SAE L3 <br/>🚗😴 | Conditional Automation | System drives *within conditions*; human is fallback | The car drives itself *sometimes*, but may ask you to take over | Traffic-jam pilots, limited highway autonomy |
| SAE L4 <br/>🚕🤖 | High Automation | System drives; no human needed *within defined areas* | The car drives itself in specific places or conditions; no driver attention required | Robotaxis in geofenced cities |
| SAE L5 <br/>🚗✨ | Full Automation | System drives everywhere | No steering wheel required; the car can drive anywhere a human can | Fully autonomous vehicles (not yet real) |

Key clarifications (why confusion happens):

- L2 ≠ self-driving. The *human* is still legally responsible.
- The big legal shift happens between L2 and L3 (who must pay attention).
- L4 works today, but only in constrained environments.
- L5 is theoretical and does not currently exist in production.

---

## Tools Don't Define Levels. Responsibility Does.

One of the biggest misconceptions designers have is:

> "Advanced tools = higher maturity."

That's not how SAE works. **The level is defined by who holds responsibility over time**, not which tool you're using.

That said, tools *do* matter. They shape where work happens and what kinds of responsibility transfers become possible. Think in terms of **environments**:

* **Assistive Environments** Short-lived AI help. Context resets easily. Humans stay continuously involved. Examples: Chat tools, visual generators, canvas AI, even IDE chat panels. 

> These environments dominate at L1–L2 because responsibility never leaves you.

* **Workspace Environments (IDE)** Where workflows persist over time: files, history, diffs, checkpoints. IDEs become important at L3 not because they're "advanced" but because _your work spans time and must survive interruptions_. If you close your laptop at L3, the work pauses but doesn't vanish. 

> *Why this matters now:* Today, the real differentiation for a product designer is whether they can make a real PR by themselves. That requires being close to code. Cursor, VS Code + Copilot, and similar tools aren't just "advanced." They're where the responsibility shift to L3 actually happens. This may change as web app builders evolve, but right now the IDE is the threshold.

* **Autonomous Environments (ADE / State-Of-The-Art (SOTA) "Harnesses")** Execution continues without constant human presence: background agents, harnesses, eval-driven pipelines. Refer to the Anthropic [piece](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) on harnesses and "long-running" agents to learn more.

> These define L4 because responsibility shifts from steps to rules. You're not reviewing work-in-progress; you're reviewing outcomes.

Confusing? Probably. Just keep in mind that the core shift as you go across levels feels like:

```
Assistive  → Workspace  → Autonomous
"moment"     "workflow"   "rules"
```

Or said differently:

```
L0     L1        L2        L3         L4         L5
do → direct → assemble → approve → constrain → govern

L0 — You own everything (no AI).
L1 — You own every AI moment.
L2 — You own every AI's integration.
L3 — You own the AI's checkpoints.
L4 — You own the AI's rules.
L5 — You own the AI's goals.
```

---

## Self-Assess Your Current SAE Level

| SAE Level | What Your Work Looks Like | Where This Work Typically Happens |
| --- | --- | --- |
| **SAE L0** <br/>Manual <br/>🚗💨 | "I do my design work without AI; I'm open to using the latest tool, but in general I prefer doing things as manually as possible." | Figma, Sketch (old skool), pen and paper (OG old skool), manual paper prototyping (OG IDEO skool) |
| **SAE L1** <br/>AI-Assisted <br/>🚗➕ | "I use AI to generate ideas, copy, or visuals, but I direct each step and manually verify and refine everything." | ChatGPT, Microsoft Copilot, Midjourney, Microsoft Copilot, Figma Make, Krea, Adobe Firefly, Canva, DALL-E, Replicate, … |
| **SAE L2** <br/>Partially Automated <br/>🚗🧠 | "I use AI app-builders and hybrid design↔code canvases to generate bounded chunks (screens, components, flows, or small apps) from clear instructions, then I manually integrate and QA the results." | Lovable, Bolt.new, MagicPath, Pencil.dev (canvas mode), Vercel v0, Framer AI, Replit, GitHub Spark, … |
| **SAE L3** <br/>Guided Automation <br/>🚗😴 | "In my IDE, I run orchestrated, multi-step workflows with context engineering, using subagents/skills/MCP tools to generate large pieces of work, with human-led QA and eval checkpoints." | VS Code (w/ GitHub Copilot), Cursor, Codex, Claude in IDE, API playgrounds with persistence, … |
| **SAE L4** <br/>Mostly Automated <br/>🚕🤖 | "In my IDE/ADE/CLI, I operate advanced context, tuned harnesses, and eval suites, using subagents/skills/MCP tools to generate, refine, and QA features end-to-end, with humans handling exceptions rather than execution." | Claude Code CLI, Conductor, GitHub Copilot CLI, LangSmith, LangGraph, Braintrust, Weights & Biases, … |
| **SAE L5** <br/>Full Autonomy <br/>🚗✨ | "AI runs most of the workflow by default and self-corrects; I set the goals, constraints, quality bar, and approval gates, then review outcomes and exceptions." | Aspirational, not yet real |

Note: L2, L3, and L4 tooling is getting blurrier every day as systems vertically absorb each other's capabilities. The boundaries are about responsibility, not features. Hybrid design↔code canvas tools typically live at SAE L2, and only enter SAE L3 when embedded into persistent IDE workflows (e.g., Pencil.dev driving Claude Code inside a repo, Cursor visual editor modifying real code, etc.).

---

# Step 3: Determine Your E-P-I-A-S Stage Within Any SAE Level

The goal of AI as embedded in product design work mirrors the evolution of the automotive industry and its levels of automation. SAE L0 is simply "manual" mode for product designers. The goal isn't necessarily to move up automation levels; it depends upon the kind of work you're tasked to do. That said, it's always useful to see what kind of work is done at "higher" levels up the food chain.

---

## E-P-I-A-S at Each SAE Level

### SAE L0: 🚗💨 Manual

*Human-only execution*

> You do the work. Tools don't decide or generate.

**Environment:** Traditional design tools (Figma, Sketch, etc.)

| E: Explorer ❶→ | P: Practitioner ❷→ | I: Integrator ❸→ | A: Architect ❹→ | S: Steward →❺ |
| --- | --- | --- | --- | --- |
| Exploring craft fundamentals; learning manual techniques with inconsistent results | Consistent manual practice with developed habits and repeatable techniques | Manual workflow fully integrated with validation steps, traceability, and clear decision documentation | Built reusable manual systems, templates, and processes that others on team adopt | Set organizational standards for craft quality; mentor others in manual techniques; maintain shared design systems |

**Architect bonus:** Design systems and templates so clear that engineers and PMs can make basic design decisions without a designer in the room.

---

### SAE L1: 🚗➕ AI-Assisted

*AI suggests; human decides*

> AI helps you think and draft, but never owns outcomes.

**Environment:** Assistive (chat, generators, canvas AI)

**Responsibility:** You own every moment. AI reduces cognitive load, not responsibility.

| E: Explorer ❶→ | P: Practitioner ❷→ | I: Integrator ❸→ | A: Architect ❹→ | S: Steward →❺ |
| --- | --- | --- | --- | --- |
| Trying ChatGPT, Microsoft Copilot, Midjourney, Firefly for ideas or drafts; outputs are hit-or-miss and heavily rewritten | Using AI daily with saved prompts; consistent structure, tone, and basic quality checks before use | AI embedded across a full task (research → ideation → draft → refine) with sources noted, decisions explained, and manual validation | Shared prompt libraries, review checklists, and example outputs teammates can reuse and trust | Team standards for AI-assisted work (what's allowed, how it's reviewed); mentors others on prompting and judgment; governs usage |

**Architect bonus:** Prompt libraries and examples that let PMs, writers, or engineers produce design-quality drafts that only need light review.

**How you know AI is helping at L1:**
- Reduces time-to-first-draft
- Expands ideation breadth
- Catches things you'd miss
- But: you still rewrite most outputs

---

### SAE L2: 🚗🧠 Partially Automated

*AI builds bounded chunks; human integrates*

> AI produces usable pieces, but you assemble and verify.

New hybrid design↔code canvas tools (Lovable, MagicPath,  Pencil.dev, v0, Bolt, [YC startups](https://www.ycombinator.com/companies/industry/design-tools), etc.) live primarily at L2. They generate larger, more integrated UI chunks — sometimes full apps — but responsibility for integration, correctness, and shipping still sits with the human.

**Environment:** Assistive + early Workspace (app-builders, component generators)

**Responsibility:** You own every integration. You spend more time integrating than fixing.

| E: Explorer ❶→ | P: Practitioner ❷→ | I: Integrator ❸→ | A: Architect ❹→ | S: Steward →❺ |
| --- | --- | --- | --- | --- |
| Trying app-builders (Bolt/Lovable/v0/Framer) to generate screens/components; lots of manual stitching and rework | Getting repeatable components from clear specs; using a simple "definition of done" checklist before integrating | Outputs fit a known integration pattern (tokens/layout/a11y); prompts + inputs are traceable from request → result → final | Reusable component/flow templates + prompt packs that teammates can run and get consistent results | Team norms for what to automate at L2 (safe chunks vs risky ones); mentors others on integration + QA; governs usage and review expectations |

**Architect bonus:** Component specs and prompt packs that let non-designers generate on-brand UI that passes design review.

**How you know AI is helping at L2:**
- Generated components ship with minimal rework
- You have repeatable specs that produce consistent results
- Integration time drops as you develop patterns
- But: you still manually connect everything

---

### SAE L3: 🚗😴 Guided Automation

*IDE-centric, human-in-the-loop execution*

> If you close your laptop, the system pauses, but the work persists.

**Environment:** Workspace (IDE with persistence, history, checkpoints)

**Responsibility:** You own the checkpoints. Work spans time, not just prompts.

**Why the IDE matters now:** This is where designers cross the threshold into being able to ship real PRs. The IDE isn't just "advanced tooling." It's where context persists across sessions, where you can run multi-step workflows, and where the code actually lives. Today, Cursor/VS Code + GitHub Copilot are the environments where this responsibility shift happens. This may evolve as app-builders mature, but right now the IDE is the gate.

| E: Explorer ❶→ | P: Practitioner ❷→ | I: Integrator ❸→ | A: Architect ❹→ | S: Steward →❺ |
| --- | --- | --- | --- | --- |
| Moving work into an IDE (VS Code/Cursor); learning basic context rules; multi-step runs are inconsistent and fragile | Running reliable multi-step workflows *inside the IDE* with explicit checkpoints (plan → generate → review → revise); lightweight evals by default | Clear decision framing for IDE-run workflows: what AI executes, what humans approve, and when to intervene; failure modes documented | Shared IDE-invoked workflows: Skills/MCP tools, context libraries (brand, design system, constraints), and reusable eval templates teammates can run | Org standards for IDE-based AI work (safety, quality, traceability); mentorship on context engineering; maintains shared Skills/MCP used from IDEs |

**Architect BONUS:** Created a "mini" version of production codebase for PMs and designers to experiment with their ideas.

**How you know AI is helping at L3:**
- You can leave and come back without losing context
- Multi-step workflows complete without constant intervention
- You review at checkpoints, not every step
- You can ship PRs that you couldn't have written manually
- But: you still supervise every workflow run

---

### SAE L4: 🚕🤖 Mostly Automated

*Harness-centric, system-run execution*

> Work completes while you're asleep, and you trust the results unless alerted.

**Environment:** System (ADE, CLI, harnesses, eval pipelines)

**Responsibility:** You own the rules. You review outcomes, not steps.

| E: Explorer ❶→ | P: Practitioner ❷→ | I: Integrator ❸→ | A: Architect ❹→ | S: Steward →❺ |
| --- | --- | --- | --- | --- |
| Experimenting with autonomous harnesses and agent pipelines; results require heavy validation and manual debugging | Operating harnesses with repeatable execution patterns; evals, retries, and escalation paths are consistently applied | End-to-end workflows run autonomously; comprehensive eval suites validate outputs; exception classes and recovery paths documented | Built production-grade agent infrastructure others operate: self-improving harnesses, shared skill libraries, eval-driven pipelines | Governance for autonomous systems at scale; defines risk thresholds, approval gates, and accountability; maintains org-level eval and autonomy infrastructure |

**Architect bonus:** Built interfaces where PMs and designers can trigger agent workflows, monitor progress, and approve outputs—without ever opening a terminal.

**How you know AI is helping at L4:**
- Systems run without your attention
- You're alerted to exceptions, not asked for approvals
- Eval suites catch problems before you do
- But: you still define what "good" means

---

### SAE L5: 🚗✨ Fully Automated

*Science-fiction, might happen some day*

> This is the AGI dream.

**Environment:** Theoretical

| E: Explorer ❶→ | P: Practitioner ❷→ | I: Integrator ❸→ | A: Architect ❹→ | S: Steward →❺ |
| --- | --- | --- | --- | --- |
| Exploring goal-setting interfaces for autonomous AI; exception handling is unclear | Setting approval gates and quality bars consistently; routine review of autonomous outputs | Autonomous workflows validated with exception handling systems; clear escalation paths documented | Designed goal-setting and approval systems that others trust; reusable governance frameworks | Enterprise governance for fully autonomous AI; set approval frameworks; organizational AI risk and trust standards |

**Architect bonus:** Governance frameworks where cross-functional teams can set AI goals and constraints together, not just at the engineering level.

---

# How Designers Know AI Is Actually Helping

Across all levels, AI is helping if it:

- **Reduces cognitive load:** you think about fewer things at once
- **Reduces cycle time:** you ship faster
- **Reduces rework:** outputs need less fixing
- **Improves consistency:** quality varies less
- **Improves handoff clarity:** others understand your work better

If none of those improve, you're exploring, not progressing. That's fine! Exploring is stage one. But don't confuse tool novelty with workflow improvement.

---

# The Big Takeaway

SAE maturity is not about using more advanced tools. It's about who holds responsibility over time.

Right now, the jump to L3 and L4 usually means working closer to code. That's not arbitrary. Code is where context persists, where workflows can be versioned and resumed, and where you can actually ship a PR that changes production. IDEs and ADEs aren't "advanced tools" so much as environments where the responsibility transfer to AI becomes structurally possible. But this is a snapshot of 2026, not a permanent truth. As app-builders get smarter, as agents get better at maintaining state, and as the boundaries between "design tool" and "development environment" keep blurring, the specific tooling that defines each level will shift. What won't change is the underlying question: who owns the work at any given moment? The tools are just where that ownership gets enacted.

```
Without AI:
L0 — craft fundamentals (and they still matter)

With AI:
L1 — better thinking (and first drafts in minutes)
L2 — reusable outputs (and non-production prototypes in hours)
L3 — persistent workflows (and real production PRs)
L4 — autonomous execution (your work done while you sleep)
L5 — goal-setting only (and we're not there yet)
```

Designers don't need to race toward L4. They need to go deep wherever they are.

An S-Steward at L1 who's built organizational standards and repeatable habits for responsible AI-assisted design is more valuable than an E-Explorer fumbling with agent harnesses they don't understand. Even if that Explorer looks cooler at the demo. ;-)

Go deep before you go wide.

---

# Congratulations!

Do you feel a little better now? I hope so! I spent three weekends working on this ... but also have spent the last few decades on this problem, too. I don't expect to fully solve it before I kick the bucket, but I'll keep on trying to improve this system!

---

*This framework is part of the [Design in Tech Report 2026](https://schedule.sxsw.com/2026/events/PP1148536). It will be presented at SXSW 2026. Feedback and contributions welcome.*

---

# Appendix: Gameboard Version

**How to use this board**

Draw a continuous line through the squares that represent your real journey. Move right (maturity) or up/down (autonomy). There is no single correct path.

### SAE L0: Craft fundamentals (and they still matter)

| SAE Level   | Explorer ❶                                 | Practitioner ❷                                  | Integrator ❸                                   | Architect ❹                                        | Steward ❺                                           |
| ----------- | ------------------------------------------ | ----------------------------------------------- | ---------------------------------------------- | -------------------------------------------------- | --------------------------------------------------- |
| **🚗💨 L0** | ⬜<br><br>Learning craft basics<br><br><br> | ⬜<br><br>Consistent manual workflow<br><br><br> | ⬜<br><br>Decisions documented + QA<br><br><br> | ⬜<br><br>Reusable templates others use<br><br><br> | ⬜<br><br>Sets craft standards + mentors<br><br><br> |

### SAE L1: Better thinking (and first drafts in minutes)

| SAE Level  | Explorer ❶                                       | Practitioner ❷                                       | Integrator ❸                                  | Architect ❹                                  | Steward ❺                                        |
| ---------- | ------------------------------------------------ | ---------------------------------------------------- | --------------------------------------------- | -------------------------------------------- | ------------------------------------------------ |
| **🚗➕ L1** | ⬜<br><br>Trying prompts + generators<br><br><br> | ⬜<br><br>Daily AI usage w/ saved prompts<br><br><br> | ⬜<br><br>AI across full task flow<br><br><br> | ⬜<br><br>Shared prompt libraries<br><br><br> | ⬜<br><br>Defines team AI usage rules<br><br><br> |

### SAE L2: Reusable outputs (and non-production prototypes in hours)

| SAE Level   | Explorer ❶                                | Practitioner ❷                                    | Integrator ❸                                        | Architect ❹                                             | Steward ❺                                               |
| ----------- | ----------------------------------------- | ------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| **🚗🧠 L2** | ⬜<br><br>Testing app builders<br><br><br> | ⬜<br><br>Repeatable component outputs<br><br><br> | ⬜<br><br>Outputs fit tokens/layout/a11y<br><br><br> | ⬜<br><br>Prompt packs + component templates<br><br><br> | ⬜<br><br>Defines safe automation boundaries<br><br><br> |

### SAE L3: Persistent workflows (and real production PRs)

| SAE Level   | Explorer ❶                                        | Practitioner ❷                                      | Integrator ❸                                 | Architect ❹                                       | Steward ❺                                               |
| ----------- | ------------------------------------------------- | --------------------------------------------------- | -------------------------------------------- | ------------------------------------------------- | ------------------------------------------------------- |
| **🚗😴 L3** | ⬜<br><br>Learning IDE + context rules<br><br><br> | ⬜<br><br>Multi-step runs w/ checkpoints<br><br><br> | ⬜<br><br>Human-AI approval model<br><br><br> | ⬜<br><br>Shared IDE workflows + evals<br><br><br> | ⬜<br><br>Org standards for context + safety<br><br><br> |

### SAE L4: Autonomous execution (your work done while you sleep)

| SAE Level   | Explorer ❶                                   | Practitioner ❷                                      | Integrator ❸                                          | Architect ❹                                          | Steward ❺                                        |
| ----------- | -------------------------------------------- | --------------------------------------------------- | ----------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------ |
| **🚕🤖 L4** | ⬜<br><br>Testing agent pipelines<br><br><br> | ⬜<br><br>Reliable eval + retry patterns<br><br><br> | ⬜<br><br>Autonomous workflows w/ recovery<br><br><br> | ⬜<br><br>Production agent infrastructure<br><br><br> | ⬜<br><br>Defines autonomy governance<br><br><br> |

### SAE L5 — 🚗✨ Fully Automated (Future)

| SAE Level  | Explorer ❶                                   | Practitioner ❷                                 | Integrator ❸                                   | Architect ❹                                       | Steward ❺                                   |
| ---------- | -------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ------------------------------------------------- | ------------------------------------------- |
| **🚗✨ L5** | ⬜<br><br>Exploring goal-based AI<br><br><br> | ⬜<br><br>Consistent approval gates<br><br><br> | ⬜<br><br>Exception-driven autonomy<br><br><br> | ⬜<br><br>Goal frameworks others trust<br><br><br> | ⬜<br><br>Org-wide AI governance<br><br><br> |

---
