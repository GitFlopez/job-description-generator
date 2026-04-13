# Prompt: Offer Letter Template Generator

## Purpose
Generate a professional, legally sound offer letter template with compensation table, benefits summary, contingencies, and acceptance deadline. Customizable for any role, level, or location.

---

## The Prompt

```
You are an HR operations specialist who has written hundreds of offer letters across tech, finance, and healthcare companies. Write a complete offer letter for the role below.

INPUTS:
- Candidate name: [FULL_NAME]
- Job title: [JOB_TITLE]
- Department: [DEPARTMENT]
- Reports to: [MANAGER NAME, TITLE]
- Start date: [DATE or "to be mutually agreed"]
- Employment type: [full-time / part-time / contract]
- Location: [on-site city/state | remote | hybrid]
- Base salary: [$X/year or $X/hour]
- Pay frequency: [bi-weekly / semi-monthly / monthly]
- Variable comp (if any): [bonus %, commission structure, or "none"]
- Equity (if any): [X options / X RSUs vesting over Y years, or "none"]
- Benefits start date: [first day / 30 days / 60 days]
- Benefits highlights: [health, dental, vision, 401k match, PTO days, etc.]
- Signing bonus (if any): [$X with Y-month clawback, or "none"]
- Contingencies: [background check / drug screen / reference check / I-9 / other]
- Acceptance deadline: [DATE — typically 3-5 business days from offer date]
- Company legal name: [LEGAL_ENTITY_NAME]
- Company address: [ADDRESS]
- HR signatory name and title: [NAME, TITLE]

OUTPUT FORMAT — professional business letter:

[Company Letterhead Block]
[Date]

[Candidate Name]
[Candidate Address — leave as placeholder if unknown]

Dear [Candidate First Name],

**Opening paragraph:** Warm, direct offer statement. Reference the role, department, and start date. Convey genuine excitement without being over-the-top. 2-3 sentences.

**Compensation Section:**
Present as a formatted table:

| Component | Details |
|-----------|---------|
| Base Salary | $X per year / $X per hour |
| Pay Schedule | Bi-weekly (26 pays/year) |
| Target Bonus | X% of base, paid [frequency], based on [criteria] |
| Equity | X RSUs vesting over 4 years (1-year cliff) |
| Signing Bonus | $X (subject to 12-month clawback if voluntary resignation) |

**Benefits Overview:**
Bullet list (6-8 items). Be specific: "20 days PTO + 10 company holidays + your birthday" not "generous PTO policy." Include:
- Health/dental/vision (include company contribution %)
- 401(k) with match details
- PTO and holiday policy
- Parental leave (if any)
- Remote/equipment stipend (if any)
- Any standout perks

**Employment Conditions:**
Paragraph covering:
- At-will employment statement (adjust if not applicable)
- Contingencies that must be satisfied before first day
- Any required agreements (NDA, IP assignment, non-compete — flag these clearly for candidate to review with counsel)

**Acceptance Instructions:**
Clear instructions: sign and return by [DATE]. Provide two options: physical signature or e-signature. Include who to return to and how (email address or DocuSign placeholder).

**Closing paragraph:** Genuine, human close. Express confidence in what they'll bring. Mention first-day logistics or onboarding contact. 2-3 sentences.

Sincerely,

[HR Signatory Name]
[Title]
[Company Legal Name]
[Email]
[Phone]

---
**Attachment note:** "By signing below, you acknowledge this offer and confirm your acceptance of the terms described herein. This offer letter does not constitute a contract of employment."

[Signature line]
[Date line]

STYLE RULES:
- Professional but warm — not robotic
- No legal jargon a layperson can't parse
- Flag any clause the candidate should review with counsel (non-compete, IP assignment, clawback) with: ⚠️ REVIEW WITH COUNSEL
- Total length: 500-700 words (not counting compensation table)
- Leave [PLACEHOLDER] brackets for any field I didn't provide
```

---

## Usage Notes

- **Always have legal review** the final offer letter before sending — especially non-compete and IP assignment clauses
- Salary range disclosure: CA, CO, IL, NY, WA require salary ranges in job postings; offer letters must match
- Clawback language on signing bonuses: specify the trigger (voluntary resignation only vs. any separation)
- For remote employees: specify which state's law governs the employment relationship
- E-signature: DocuSign, HelloSign, or PandaDoc all work — don't email a PDF expecting a wet signature in 2026

---

## Offer Acceptance Rate Tips

- Include a 48-hour expiration for competitive markets (creates urgency without being pushy)
- Send on Tuesday or Wednesday morning — Monday offers feel like an afterthought; Thursday/Friday risk weekend ghosting
- Call before you send — candidate should never be surprised by a written offer
- Counter-offer protocol: if candidate counter-offers, respond within 24 hours
