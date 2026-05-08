
# 10x Human Capability
## A Blueprint for Student-Led, AI-Augmented Consulting

This repository documents how I used AI-assisted workflows, consulting-style reasoning, and human judgment to turn community-facing project work into professional deliverables, reusable systems, and a practical student blueprint. It reflects a portfolio of work centered on structured analysis, report design, skill refinement, and responsible AI use in real-world problem solving through tools such as Claude Code, Codex, and custom consulting skills.

The project was built around a simple idea: students can create meaningful community impact when AI is used to expand capability rather than replace judgment. In this case, AI helped accelerate research synthesis, improve report structure, sharpen strategic thinking, and turn a large body of notes and analysis into concise, actionable outputs.

## What This Repository Represents

- A student-led effort to translate community problems into structured action plans
- An example of how AI can help move work from theory into decision-ready execution
- A demonstration of how consulting workflows can be adapted into accessible tools for students
- A record of how professional deliverables can emerge from disciplined iteration, not just one-off prompting

## What I Built

- An executive-style report designed to communicate the core story in 5-10 minutes
- A technical appendix designed to preserve supporting logic, methods, and deeper analytical detail
- A student blueprint for learning how to use AI skills responsibly in consulting-style work
- A system/PRD-style document for making the workflow repeatable across future student engagements

## Core Workflow

1. Curated notes, lessons, and project insights gathered across the semester
2. Refined a skill based on what worked, what failed, and what needed to improve for our personal project
3. Iterated across multiple LLMs to improve structure, tone, and analytical clarity of the skill.
4. Interacted  with two skills in Claude Code to condense a much longer research base into two distinct client-facing formats: a concise core narrative and a deeper technical companion
5. Used Claude Code, Codex, and McKinsey-style consulting workflows to turn the reporting process into a reusable blueprint for student teams

## Skills and Methods

- `consulting-analysis` for structuring research, shaping deliverables, and organizing consulting-grade narratives
- `mckinsey-consultant` for hypothesis-driven analysis, MECE problem decomposition, storyline logic, and implementation planning
- Human-in-the-loop review for expert feedback, refinement, and final approval at key checkpoints
- Privacy-first AI use to keep sensitive information out of general-purpose models and preserve ethical standards

## The End-to-End Workflow

The most important lesson from this project is that good AI-assisted work does not start with "write my report." It starts with structure.

### Phase 1. Curate the raw material

Start by gathering:

- meeting notes,
- research notes,
- charts and spreadsheets,
- prior drafts,
- observations from teammates,
- and any lessons learned from earlier project stages.

Your goal here is not polish. It is consolidation.

What students should produce:

- one clean notes file,
- one evidence list,
- one list of open questions,
- and one sentence describing the core problem.

### Phase 2. Define the problem before drafting

This is where `mckinsey-consultant` becomes valuable. Use it to define:

- what the problem is,
- what it is not,
- who the audience is,
- what decision the report needs to support,
- and what deliverables you are actually building.

Do not skip this step. A weak scope creates a weak report, even if the writing sounds polished.

Example prompt:

```text
Help me define this project like a consulting engagement. Start with the problem boundary only.
I need an Is / Isn't definition, a decision question, the audience, what is in scope,
what is out of scope, and the deliverables I should produce.
```

What students should save:

- `Is / Isn't` scope definition
- decision question
- intended audience
- output package

### Phase 3. Build an issue tree and working hypotheses

Once the scope is clear, use `mckinsey-consultant` to break the problem into parts.

This is where students stop thinking in paragraphs and start thinking in logic:

- What are the major branches of the problem?
- Which drivers belong together?
- What evidence would prove or disprove each claim?

Example prompt:

```text
Using the scope we defined, build a 2-3 level MECE issue tree.
Then convert the main branches into testable hypotheses.
For each hypothesis, tell me what evidence I need and what kind of source would support it.
```

What students should save:

- issue tree
- hypothesis list
- first-pass evidence plan

### Phase 4. Design the report before writing it

One of the biggest mistakes students make is writing too early.

Before drafting, decide what the final package should look like. In this project, the work became much stronger once I stopped treating the output as one long report and instead split it into:

- a main executive report,
- and a technical appendix.

This separation creates clarity:

- the main report is the argument,
- the appendix is the proof.

Use `consulting-analysis` and `mckinsey-consultant` to decide:

- what belongs in the main narrative,
- what belongs in backup materials,
- what figures or tables prove each major claim,
- and what order the story should follow.

Example prompt:

```text
Design the structure for a two-document package: an executive report and a technical appendix.
For each major hypothesis, tell me what belongs in the main report, what belongs in the appendix,
and what chart, table, or proof asset best supports the claim.
```

What students should save:

- report architecture
- section outline
- exhibit plan
- appendix asset list

### Phase 5. Build a source-disciplined evidence base

This is where students need discipline. Not all evidence is the same.

Separate your sources into clear buckets such as:

- internal project materials,
- public research,
- benchmark or comparison data,
- survey findings,
- qualitative observations,
- and implementation assumptions.

If two sources use different definitions, label that difference. Do not blend them because the story looks cleaner. Clean storytelling with weak source logic is still bad analysis.

Example prompt:

```text
Help me build an evidence checklist for each section of the report.
Separate internal data, benchmark data, qualitative materials, and public context.
Flag any source-definition risks and tell me what should be labeled clearly.
```

What students should save:

- source register
- evidence checklist
- interpretation guardrails

### Phase 6. Draft the executive story

Only after the logic and evidence are in place should you draft the main report.

Here the skill should help you:

- write answer-first section titles,
- keep paragraphs decision-oriented,
- reduce unnecessary detail,
- and clarify why each finding matters.

This was one of the biggest gains in my own process. I used multiple LLM iterations to learn how to transform a much longer report into a tighter executive narrative that could be understood quickly without losing strategic value.

Example prompt:

```text
Draft the main report in an executive style.
Use answer-first section titles, compact paragraphs, and explicit implications.
Do not overload the main report with backup proof that belongs in the appendix.
```

What students should save:

- main report draft
- answer-first section titles
- recommendation summary

### Phase 7. Draft the technical appendix

The appendix is not a dumping ground. It is the proof system behind the main report.

Use it to preserve:

- definitions,
- data caveats,
- backup charts,
- structured tables,
- implementation templates,
- and source traceability.

The appendix makes the work more credible, more teachable, and more reusable for future teams.

Example prompt:

```text
Help me build a technical appendix that supports the main report.
For each major claim, suggest the right backup exhibit, table, note, definition, or template.
Keep it detailed, but organized for reuse by future student teams.
```

What students should save:

- appendix outline
- backup exhibits
- definitions and caveats
- reusable templates

### Phase 8. Use HITL to improve quality

Human-in-the-loop review is not optional if the work matters.

In this project, HITL added value by improving:

- accuracy,
- tone,
- client readiness,
- structure,
- and practical usefulness.

A strong HITL loop looks like this:

1. Draft with the skill.
2. Review the logic yourself.
3. Ask an expert, mentor, or teammate to critique the structure, assumptions, and clarity.
4. Revise the prompts or workflow, not just the wording.
5. Repeat until the output is both accurate and useful.

The goal is not to ask a human to approve AI writing blindly. The goal is to use expert review to improve the thinking system behind the output.

### Phase 9. Turn the project into a reusable system

One of the most valuable outcomes of this project was not the report itself. It was the systemization of the workflow.

After the reporting process was working, I used Codex and the consulting skills to build:

- a blueprint for student teams,
- a PRD-style implementation plan,
- and a more repeatable method for future engagements.

This is where students can create long-term value. Instead of finishing one project and starting from zero on the next one, they can preserve:

- prompts,
- checklists,
- templates,
- review gates,
- and report structures.

That turns experience into infrastructure.

## How To Use These Skills Well

Students often get disappointing results from strong tools because they use them too vaguely. The skill matters, but the workflow matters more.

### Best practices

- Start with a narrow task, not a giant request
- Ask the skill to do one stage at a time
- Save outputs at each stage before moving on
- Use the skill to structure analysis before generating prose
- Separate brainstorming from final drafting
- Revise the prompt when the logic is weak instead of endlessly revising the wording
- Use multiple model passes when you need different strengths such as structure, tone, or compression

### Common mistakes

- Asking for the whole report before defining the problem
- Mixing executive narrative and technical backup in the same document
- Letting the model invent certainty where the evidence is weak
- Failing to label source differences
- Treating AI output as final instead of as a draft or analytical partner
- Forgetting to preserve what worked for future teams

## A Practical Prompt Sequence Students Can Reuse

These are generic prompt shapes that students can adapt to their own projects.

### 1. Problem framing

```text
Help me frame this as a consulting problem.
Define the decision question, the audience, the scope, the exclusions, and the deliverables.
Do not draft the report yet.
```

### 2. Issue tree

```text
Build a MECE issue tree for this problem.
Keep it practical for a student team and explain why each branch matters.
```

### 3. Hypothesis design

```text
Turn the issue tree into testable hypotheses.
For each one, tell me what evidence would support it and what might weaken it.
```

### 4. Evidence planning

```text
Create an evidence plan for each hypothesis.
Separate internal sources, public sources, benchmark sources, and qualitative material.
Flag definition risks and evidence gaps.
```

### 5. Story architecture

```text
Design a two-document deliverable package:
an executive report and a technical appendix.
Tell me what belongs in each and what proof asset each major claim needs.
```

### 6. Executive drafting

```text
Draft the executive report with answer-first section titles, concise paragraphs, and clear implications.
Keep the tone professional and actionable.
```

### 7. Appendix drafting

```text
Draft the technical appendix so it supports the report without repeating it.
Preserve definitions, backup exhibits, and reusable tools.
```

### 8. QA and revision

```text
Review this package like a senior consultant.
Find weak logic, missing proof, unclear definitions, and places where the recommendation is not fully supported.
```


## Outcomes

- Board-ready recommendations
- Professional deliverables for executive and technical audiences
- Student capability expansion through structured AI collaboration
- A reusable model for turning community challenges into actionable plans

## Repository Structure

- `docs/` contains blueprint and system-design materials for student report workflows
- `scripts/` contains supporting utilities used to build and format report outputs
- `output/` contains generated deliverables and supporting assets

## Privacy and Responsible Use

This README is intentionally written for public sharing. It does not disclose confidential client data, private records, or sensitive project-specific details. The goal is to document methodology, workflow design, and learning outcomes while preserving privacy and professional responsibility.

Any public-facing version of this work should keep that same standard by sharing frameworks, prompts, redacted outputs, and process lessons rather than confidential source materials.

## Author

Eliezer Gonzalez
