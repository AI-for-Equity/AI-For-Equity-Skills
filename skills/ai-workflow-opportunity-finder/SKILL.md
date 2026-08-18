---
name: ai-workflow-opportunity-finder
description: Identify, score, and scope practical AI workflow improvements. Use when a professional needs to find recurring work suited to AI assistance, automation, or agents; assess whether a workflow is a good candidate to offload or keep human-led; determine whether a coding harness or chatbot is the right environment; or choose an appropriate build path such as a reusable prompt, skill, agent, or automation.
---

# AI Workflow Opportunity Finder

## Purpose

Help a professional turn a real work problem into a right-sized AI build. First identify workflows where AI can add meaningful value. Then learn the person's available AI environment and recommend an approach that fits their access, skill level, data constraints, and appetite for maintenance.

Do not treat every repetitive task as an automation opportunity. A useful outcome may be a reusable prompt or a clarified manual process.

## 1. Inventory recurring workflows

Ask the person to name a recurring task, bottleneck, or decision they would like to improve. If they do not have one, help them inventory work across these categories:

- Summarizing, extracting, drafting, or transforming information
- Searching across documents, data, or systems
- Preparing recurring communications, reports, meeting materials, or follow-ups
- Routing, triaging, checking, or monitoring work
- Repeating a judgment process with clear inputs and review criteria

For each candidate, ask only for the context needed to score it:

1. What triggers the work, and how often does it happen?
2. What are the inputs and expected output?
3. Where is time or quality currently lost?
4. What systems, data, approvals, or people are involved?

## 2. Score agent and automation fit

Score each workflow from 0 to 2 on each dimension. Explain the score briefly; do not treat the total as a substitute for judgment.

| Dimension | 0 | 1 | 2 |
|---|---|---|---|
| **Worth it** | Rare, low-effort, or low-value task | Moderate frequency or benefit | Frequent, painful, or valuable enough to justify setup |
| **Teachable** | Heavily tacit, inconsistent, or hard to explain | Partly teachable with examples and review | Can be taught through clear instructions, examples, screen shares, or a short deep dive |
| **Easy to check** | Quality is subjective or errors are hard to detect | Review is possible but requires substantial expertise | Accuracy can be checked quickly using clear criteria or a human review step |
| **Stakes** | Errors could cause serious, irreversible, or high-stakes harm | Consequences are meaningful but recoverable with review | Low stakes or easily reversible; safe to test and supervise |
| **Individual matters** | Requires a particular person's judgment, voice, relationship, or human touch | Human perspective remains important in some moments | The work does not depend materially on a particular person's involvement |

Add the five scores for a total out of 10.

| Total | Recommendation |
|---|---|
| **7–10** | Strong candidate for an agent, automation, or other more independent AI workflow—subject to access, policy, and a small pilot. |
| **4–6** | Best suited to human-and-AI collaboration. Keep a person actively involved while using AI for preparation, drafting, analysis, or routine substeps. |
| **0–3** | Keep the work primarily human-led. AI may still help in a narrow supporting role, but do not prioritize offloading it. |

Flag caution when a score hides a non-negotiable constraint, such as sensitive data, policy restrictions, unavailable system access, or an approval requirement. Recommend the best one or two candidates and give each a short opportunity brief: score, likely benefit, required inputs, human role, main risk, and a small first test.

## 3. Map available AI access

Interview the person about their actual AI environment. Ask which description best matches it:

1. **Coding harness:** They can use a tool such as Claude Code or Codex, with access to files, code, and possibly tools or integrations. Clarify that this does **not** mean they need to write code themselves: they can describe the task in plain language and let the harness create or run code when appropriate.
2. **Chatbot:** They mainly use ChatGPT, Claude, or Gemini in a chat interface. Ask which one.
3. **Both or another environment:** Ask what the environment can access and whether it can save reusable instructions, work with files, run code, or connect to other systems.

For any environment, confirm whether the person can work with files, save reusable instructions or a configured assistant (for example, a Gem), create or upload a `SKILL.md` skill, use approved connectors, or run code. ChatGPT and Claude may support creating or uploading reusable Skills outside a coding harness, subject to the person's plan and workspace permissions. Do not assume that a product tier, organization, or account has a particular feature.

Also ask whether organizational policy permits the relevant data and tools to be used. Do not ask them to share sensitive data.

## 4. Recommend the right build path

Choose the smallest durable solution that fits the opportunity and access.

| Environment and task shape | Recommended build path |
|---|---|
| Chatbot such as Gemini, Claude, or ChatGPT; occasional or changing task | Reusable prompt, checklist, or conversation template |
| Chatbot; stable repeatable judgment or drafting workflow | Saved instructions, a configured assistant or Gem when available, plus a clear human review step |
| ChatGPT or Claude with Skills creation or upload enabled; stable repeatable workflow | Markdown-based `SKILL.md` skill, created or uploaded in the chatbot environment; add scripts only if the environment supports and needs them |
| Coding harness; repeatable multi-step workflow | Skill with a clear `SKILL.md` workflow and optional references or templates |
| Coding harness; deterministic transformation or validation | Small script or tool, with a human review step; the user can direct the harness in plain language rather than writing the code |
| Coding harness with approved system access; event-driven or high-volume workflow | Agent or automation, beginning with a narrowly scoped pilot |

Explain why the recommendation matches the person's environment. Do not recommend an agent or automation merely because it is technically possible.

## 5. Scope and build the first version

For the selected opportunity, define a minimum useful version:

- User and use case
- Trigger and inputs
- Proposed AI role
- Required human review or approval
- Output or action
- Data, access, and policy constraints
- Success measure
- First test using a safe, representative example

After agreeing on the scope, ask whether the person wants to build the first version now. If yes, create the complete, ready-to-use artifact that fits their environment—not merely an outline.

- **Markdown Skill:** Produce a finished `SKILL.md` with frontmatter, workflow, inputs, outputs, guardrails, and an example prompt. Include setup and upload instructions appropriate to the person's environment.
- **Configured assistant or Gem:** Produce complete, copy-ready instructions, a name, a description, and three conversation starters. Include any recommended knowledge files or settings, but do not claim a feature exists unless the person has confirmed it.
- **Reusable prompt:** Produce a complete, copy-ready prompt with input placeholders, workflow instructions, output format, and a test example.
- **Coding-harness implementation:** Produce a concise build plan, then build the first safe version when the environment and user authorize it. Include a human review step and a representative test.

If the person does not want to build immediately, provide the scoped build brief and the single next action needed to continue. Keep the recommendation proportional to the expected value and the person's available access.

End with a concrete next action that can be completed in one working session. Keep the recommendation proportional to the expected value and the person's available access.
