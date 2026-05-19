---
name: academic-grant-writer
description: Transform Markdown notes (ideas, outlines, meeting notes, etc.) into a polished academic grant proposal in LaTeX with a corresponding BibTeX file.
version: 2.1
---

# Skill: Academic Grant Writing from Notes

## Purpose

Transform one or more Markdown inputs containing ideas, outlines, meeting notes, rough drafts, and reference fragments into a polished academic grant proposal written in LaTeX, with a matching BibTeX file.

---

## Input Format

The input directory may contain any of the following Markdown files:

- `ideas.md`
- `outline.md`
- `meeting-notes.md`
- `references.md`
- `draft.md`
- other `.md` files containing relevant project material

These files may be incomplete, repetitive, messy, or contradictory. Your job is to synthesize them into a coherent grant application.

---

## Output Format

Produce:

- `grant.tex` — the main LaTeX document
- `references.bib` — BibTeX entries for all cited sources

The main output should be a clean, compile-ready LaTeX manuscript.

---

## Core Task

Use the Markdown notes to draft a grant proposal with the following qualities:

- clear research vision following the Problem → Gap → Aim → Impact narrative arc
- strong motivation and significance, grounded in facts and evidence (not opinions)
- feasible, well-structured work plan with SMART objectives
- explicit expected outputs, outcomes, and impact — including a theory of change
- a lay summary that is clear and compelling to a non-specialist audience
- academically polished language throughout
- consistent terminology across all sections

---

## Preferred Grant Structure

Unless the user specifies otherwise, use this structure:

1. Title
2. Lay Summary
3. Vision (Background, Aims, and Impact)
4. Research Questions / Aims and SMART Objectives
5. Methodology / Work Packages
6. Outcomes, Impact, and Translation Plan
7. Workplan and Timeline (Gantt chart described in prose or tabular form)
8. Applicant and Team Capability
9. Ethics and Responsible Research Innovation (RRI)
10. Risks and Mitigation
11. Resources and Cost Justification
12. References

If the notes suggest a different funding format (e.g. UKRI, Horizon Europe, ERC, Wellcome, Gates), adapt the structure accordingly.

---

## Understanding the Review Process

When drafting, always write with the actual reviewer audience in mind. Proposals pass through multiple stages:

- **Eligibility ("Admin"):** confirms applicants are eligible, documents are complete, and the topic is in scope. Write the lay summary and opening sections so scope is immediately obvious.
- **Expert Peer Reviewers ("Specialists"):** 2–5 domain experts who score and summarise the proposal independently. These reviewers are technically expert but not necessarily expert in every part of the proposal. Methods must be specific and justifiable, but not so technical that a neighbouring-field expert cannot evaluate them.
- **Committee ("Non-Specialists"):** the panel that makes the final funding decision. They read expert summaries and the proposal itself, and are less expert than the peer reviewers. The vision section and lay summary must carry the argument for this audience.

Write each section with its primary reader in mind.

---

## Vision Section

The Vision section is the narrative heart of the proposal. It must build a coherent story arc:

**Problem → Gap → Aim → Why solving it matters**

Structure it across seven elements in this order:

1. **The big picture** — why this research matters; present key facts and evidence (statistics, citations) that establish the problem at scale. Tailor to the funder's priorities and the expected scale of impact (e.g. a £500K proposal reads differently from a £5M one).
2. **What others have done** — a selective review establishing that serious prior work exists but that a gap remains.
3. **The gap in knowledge** — the single most important missing piece. Be explicit: this is what you will address.
4. **Your aim and research questions** — signposted clearly: "This project aims to…" followed by specific research questions.
5. **Novelty and timeliness** — why now, why this approach, what makes it different from prior work.
6. **Expected outcomes and impacts** — what changes in the short and long term; address academic, societal, economic, and/or environmental impact as appropriate.
7. **Who will benefit and how** — close the loop by connecting beneficiaries back to the problem described at the start. Do not say "researchers" — be specific (e.g. "clinicians working in early cancer diagnostics", "rural teachers without access to digital infrastructure").

Ensure the Vision section does not merely describe — it must persuade. Back every claim with a citation or a statistic.

---

## SMART Objectives

Each objective must be **Specific, Measurable, Achievable, Realistic/Relevant, and Time-Bound**.

Format each objective as:

```
O[N]. [Short title]: To [action verb] [specific target] in [context/location] [timeframe; lead institution or person]
```

Example:
> O1. Soil microorganism survey: To characterise microbial abundance and population diversity in working farm fields in the UK treated with paper pulp waste [Y1Q1–2; UoX lead]

Include an overarching **Aim** (one high-level goal) followed by 3–5 SMART objectives. Each objective should map directly to a Work Package.

---

## Work Package Methods and Outputs

Each Work Package (WP) corresponds to one objective. Each WP entry must include:

```
WP[N]: [Title] [Month range, e.g. M1–M12]
Lead: [Name (role, institution)]
Background: [One to two sentences on the specific problem this WP addresses]
Activities:
  - [Activity name]: Practical details and justification
  - [Activity name]: Practical details and justification
Risk and mitigation: [Specific risk and how it will be reduced]
Key deliverables:
  - D[N.1] [Description — e.g. open-access dataset submitted to repository X]
  - D[N.2] [Description — e.g. paper submitted to target journal Y]
```

Keep a clear 1-to-1 mapping: Objective N → WP N.

When writing methods:

- Show that the work has been **thought through** — justify choice of methods (quantitative, qualitative, computational, etc.), detail datasets, replicates, or case studies, and explain how outputs will be analysed and shared.
- Show that the work is **practically feasible** — mention ethical/legal approvals, access to facilities or data, and equipment availability.
- Show **good project management** — assign responsibilities, identify risks, mention advisory boards, and address EDI, research integrity, open research, and environmental policies.

Reviewers rarely complain about too much methodological detail; they frequently criticise proposals that are too vague or that show a disconnect between aims and approach.

---

## Outputs, Outcomes, and Impact

Distinguish clearly between:

- **Outputs/deliverables:** tangible, measurable things produced (papers, datasets, tools, reports, workshops, patents, policy briefs).
- **Outcomes:** direct, short-term changes arising from use of outputs (changes in behaviour, policy, practice, or knowledge uptake by specific users).
- **Impact:** longer-term, wider-reaching effects on society, the economy, the environment, or culture — often indirect and occurring well after project end.

Outputs are more than just papers. They include methodologies, prototypes, trainings, exhibitions, business plans, policy frameworks, new collaborations, monographs, and websites.

### Translation of Outputs into Outcomes and Impact

After the work packages, include a dedicated section titled **"Translation of outputs into outcomes and impact"** with three parts:

1. **Output clusters:** group related outputs by theme or stakeholder and write 1–2 sentences per cluster describing what users will do differently as a result. Example: "The open-access benchmarking dataset and accompanying workshop will enable clinical NLP researchers to evaluate models against real-world minority language patient queries for the first time."

2. **Outcome-to-impact mapping:** trace each cluster to its broader impact. Be specific about who benefits. Example: "Clinicians in regions with large Sylheti-speaking populations will have access to validated triage tools, reducing diagnostic delays and improving patient safety."

3. **Funder alignment:** 2–3 sentences explicitly connecting the project's impacts to the funder's stated strategic priorities. Use phrases like "will inform", "is expected to", or "could lead to" to balance ambition with realism.

**Theory of Change:** Consider presenting a Theory of Change table:

| Level | Content |
|---|---|
| Inputs | Funding, facilities, time, team expertise |
| Activities | Experiments, modelling, community co-design |
| Outputs | Open datasets, trained models, workshops, papers |
| Outcomes | Adoption of tools by clinicians; policy uptake |
| Impact | Reduced health inequity; improved patient outcomes |

---

## Lay Summary

The lay summary is read by committee reviewers who are non-specialists, not just by members of the public. It is often the first thing read and sets the tone for everything that follows. If the reviewer is not excited after reading it, the opportunity is lost.

Structure a 150–500 word lay summary as follows (budget roughly 10 sentences for a 200-word version):

1–3. The problem/need (facts, scale, urgency)
4. The research aim
5–6. Simplified methods
7–9. Expected benefits and impact (close the loop to the problem)
10. How this addresses the funder's objectives

**Rules for lay writing:**

- Use short sentences — one thought per sentence, ~15–17 words maximum on average.
- Use simple words and avoid acronyms. Replace technical terms with plain-language equivalents (e.g. "subduction zone" → "where one of the earth's plates slides under another").
- Cut unnecessary words. Avoid passive verbs ("results were found to be in agreement with" → "results agreed with").
- Write as if speaking — read aloud and listen for awkward phrasing.
- Add context to statistics: "130 deaths per day" is more powerful than "0.015% of the population per year".

Most of the lay summary text should draw from the Vision section, not the detailed methodology.

---

## Narrative CV Guidance

When drafting researcher statements, use the R4RI (Resume for Research and Innovation) four-module format:

**Module 1: Contributions to the generation of new ideas, tools, methodologies, or knowledge (outputs)**
For each contribution state: (a) the personal contribution, and (b) the significance in the field context.

**Module 2: Contributions to the development of others and effective working relationships**
Includes: supervision, line management, mentoring, teaching, collaborations, strategic leadership.

**Module 3: Contributions to the wider research and innovation community**
Includes: organising workshops/conferences, peer reviewing, invited talks, EDI contributions, positions of responsibility.

**Module 4: Contributions to broader audiences and societal benefit (outcomes/impact)**
For each example state: (a) how target beneficiaries were engaged, and (b) short- and long-term changes resulting.

The researcher statement section must be **persuasive — not modest**. Every claim must be supported by concrete evidence with specific outcomes (e.g. "17% improvement in early diagnosis", "£5,000 secured", "100 survey responses"). Favour fewer, richer examples over many superficial items.

For a group CV, organise by output themes aligned to the proposal rather than listing by person.

---

## Workplan / Gantt Chart

Describe or present a Gantt chart that maps:

- Work packages and their tasks
- Key deliverables (marked with milestone markers)
- Team member responsibilities (using initials)
- Project management activities (kick-off, progress updates, final meeting)
- Conferences or dissemination events

The WP names and task titles in the Gantt must match exactly those used in the written methodology.

---

## Writing Rules

- Preserve the user's intent and domain-specific terminology.
- Turn fragments into full academic prose using narrative synthesis.
- Do not invent claims, results, or citations.
- Flag uncertainty where the notes are ambiguous.
- Prefer precise, formal, grant-style language.
- Remove redundancy and combine repeated ideas.
- Verify all references — ensure they genuinely exist before including them.
- Keep the proposal internally consistent (names, acronyms, terminology, section order).
- Make the narrative persuasive but not overstated.
- Prefer full sentences over bullet lists.
- No endashes.

---

## Citation Rules

- Any factual claim that depends on external literature should be supported by a BibTeX entry.
- If a reference is mentioned in the notes but incomplete, either infer the likely citation only if highly confident, or mark it clearly as `TODO` in the BibTeX file.
- Never fabricate publication details.
- Ensure every in-text citation key used in `grant.tex` exists in `references.bib`.

---

## LaTeX Rules

- Use standard, minimal LaTeX packages unless the grant format requires otherwise.
- Keep the document compile-ready.
- Prefer semantic structure: `\section{}`, `\subsection{}`, `\paragraph{}`.
- Use `\cite{}` for references and the `natbib` package.
- Avoid overcomplicated macros unless useful.
- Include equations, tables, or figures only when supported by the notes.

---

## BibTeX Rules

- Extract all explicit references from the notes.
- Consolidate duplicate citations into one canonical entry.
- Use consistent BibTeX keys (e.g. `smith2022robustness`, `doe2021multiagent`).
- If a citation is known only partially, keep the entry and mark it clearly for later completion.

---

## Workflow

1. Read all Markdown inputs.
2. Identify: project goal, research problem, contributions, methods, required references, missing information.
3. Reconstruct the review pipeline in mind: eligibility check → expert peer review → committee review. Draft each section for its primary audience.
4. Draft the Vision section using the seven-element structure.
5. Write SMART objectives and map each to a Work Package.
6. Draft work packages with activities, risks, and deliverables.
7. Write the outcomes/impact section including output clusters, outcome-to-impact mapping, and funder alignment.
8. Write the lay summary last, drawing from the Vision.
9. Convert all bibliographic mentions into BibTeX entries.
10. Write the final LaTeX and BibTeX outputs.
11. Check consistency: names, acronyms, citations, section ordering, terminology.
12. Ensure the output compiles cleanly.

---

## Style Guidance

Write in a tone that is professional, precise, credible, concise, and academically persuasive.

Avoid: hype, vague language, unsupported promises, repetitive phrasing, overlong sentences, endashes, passive constructions where active is possible.

---

## Handling Incomplete Notes

When the notes are incomplete:

- infer structure from context
- keep placeholders for unknown details
- make assumptions explicit only when necessary
- prefer conservative, defensible wording over guesswork

Acceptable placeholders: `[FUNDING SCHEME]`, `[PROJECT DURATION]`, `[NAME OF HOST INSTITUTION]`, `[REFERENCE NEEDED]`

---

## Author Details

- Name: Soumya Banerjee
- Position: Senior Lecturer, Department of Computer Science, University of York, UK
- Email: soumya.banerjee@york.ac.uk

---

## Quality Checklist

Before finishing, verify:

- the proposal has a clear Problem → Gap → Aim → Impact argument
- the Vision section follows all seven elements in order
- all objectives are SMART and map 1-to-1 to Work Packages
- the lay summary is accessible to a non-specialist and covers all five required elements
- the outcomes section includes output clusters, outcome-to-impact mapping, and funder alignment
- citations match bibliography entries and references are genuine
- the LaTeX is syntactically valid
- no unsupported claims were added
- no endashes appear in the text
- researcher statements are evidence-based and persuasive
- the Gantt chart task names match the written methodology exactly