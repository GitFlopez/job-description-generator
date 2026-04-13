# Prompt: Interview Scorecard & Evaluation Rubric

## Purpose
Generate a structured interview scorecard aligned to the job description. Reduces bias, improves consistency, and creates a defensible paper trail for hiring decisions.

---

## The Prompt

```
You are an HR business partner who designs structured hiring processes. Create a complete interview scorecard for the role below.

INPUTS:
- Job title: [JOB_TITLE]
- Must-have requirements: [PASTE FROM JD]
- Core responsibilities: [PASTE FROM JD]
- Interview stages planned: [e.g., phone screen, technical, panel, exec]
- Number of interviewers: [NUMBER]
- Decision criteria priority order: [e.g., 1. technical skills, 2. communication, 3. leadership]

OUTPUT FORMAT:

## Interview Scorecard: [JOB_TITLE]

### Rating Scale (use consistently across all criteria)
| Score | Label | Definition |
|-------|-------|------------|
| 4 | Strong Yes | Exceeds bar; would be top 10% of candidates |
| 3 | Yes | Meets bar; confident hire |
| 2 | Lean No | Below bar; significant gaps |
| 1 | Strong No | Does not meet minimum requirements |

### Stage 1: Phone Screen (30 min)
Evaluate: [3-4 criteria relevant to this stage]
For each criterion include:
- **Criterion name** (weight: X%)
- What "4" looks like (specific, behavioral)
- What "1" looks like (specific, behavioral)
- 2 suggested interview questions

### Stage 2: [Next stage name] ([duration])
[Same format — criteria matched to this interview stage]

### Stage 3: [Next stage] (if applicable)
[Same format]

### Scoring Matrix
Table with:
- Columns: Criterion | Weight | Stage | Score (1-4) | Notes
- Rows: one per criterion
- Bottom row: Weighted Total | 100% | — | [formula] | —

### Hiring Decision Guide
| Weighted Score | Recommendation |
|---------------|----------------|
| 3.5 - 4.0 | Strong hire — move fast, risk of losing to competing offers |
| 3.0 - 3.4 | Hire — standard offer process |
| 2.5 - 2.9 | Hold — gather more data or discuss as panel |
| Below 2.5 | No hire — document specific gaps for candidate feedback |

### Red Flag Indicators (auto-disqualify regardless of score)
List 4-5 specific behaviors or answers that override a high score:
- Example: Candidate cannot articulate a specific example of [core responsibility]
- Example: Candidate asks no questions about role or team in any stage

### Interview Notes Template
Provide a copy-paste-ready notes block each interviewer fills out:
- Candidate name / Date / Interviewer
- Stage
- Score per criterion with brief rationale
- Overall recommendation + one sentence justification

RULES:
- All criteria must trace back to the JD's must-have requirements or core responsibilities
- No criteria for "culture fit", "personality", "vibe" — these introduce bias and legal risk
- Each question must be behavioral (STAR format) or situational — no hypotheticals like "where do you see yourself in 5 years"
- Weight the criteria to sum to 100%
```

---

## Usage Notes

- Run this prompt immediately after generating the JD — inputs copy directly
- Share the scorecard with all interviewers before the first interview, not after
- Each interviewer fills out their own copy — never score as a group in real time
- Archive completed scorecards per candidate (legal requirement in some states)

---

## Legal Note

Structured scorecards are your best defense against discrimination claims. Document the criteria before you meet any candidate. Never add criteria after the process starts.
