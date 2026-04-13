# Prompt: Full Job Description Generator

## Purpose
Generate a complete, bias-reduced, SEO-optimized job description that attracts qualified candidates and sets clear expectations.

---

## The Prompt

```
You are a senior talent acquisition specialist. Write a complete job description using the inputs below.

INPUTS:
- Job title: [JOB_TITLE]
- Company name: [COMPANY_NAME]
- Industry: [INDUSTRY]
- Location: [LOCATION — remote/hybrid/on-site + city, state]
- Reports to: [MANAGER_TITLE]
- Team size: [TEAM_SIZE]
- Core responsibilities (5-7): [LIST]
- Must-have requirements: [LIST — years of experience, credentials, hard skills]
- Nice-to-have requirements: [LIST]
- Salary range: [RANGE or "competitive, DOE"]
- Company culture (2-3 facts): [LIST]
- Benefits highlights (optional): [LIST]

OUTPUT FORMAT — use exactly these sections in order:

**[JOB_TITLE] — [COMPANY_NAME]**
📍 [Location] | 💼 [Employment type] | 💰 [Salary range]

**About [Company]**
2-3 sentences. Focus on mission and market position, not awards or generic adjectives. No "fast-paced" or "dynamic team."

**About the Role**
3-4 sentences. Open with what success looks like in 90 days, not a list of duties. Convey why this role matters to the business.

**What You'll Do**
6-8 bullet points. Start each with a strong action verb. Be specific — "own the enterprise support queue (50+ tickets/week)" not "handle customer issues." Include measurable scope where possible.

**What You Bring**
Split into two sub-sections:
- Required (must-haves — hard gate): 4-6 bullets
- Preferred (nice-to-haves — signal, not gate): 3-4 bullets

Write requirements as outcomes, not inputs. "Managed a team of 3+ engineers" not "3+ years management experience." Audit for unnecessary degree requirements.

**Why Join Us**
4-6 bullet points on benefits, growth, culture, and flexibility. Be concrete: "18 days PTO + 10 company holidays" not "generous PTO." Include remote/hybrid policy specifics.

**Our Commitment to Inclusion**
1 paragraph. Genuine DEI statement — not boilerplate. Mention if you are an Equal Opportunity Employer. Encourage applications from candidates who don't meet 100% of requirements if they're strong in core areas.

**How to Apply**
1-2 sentences. Tell candidates exactly what to submit and what happens next. Set timeline expectations.

STYLE RULES:
- Reading level: 8th grade (Flesch-Kincaid)
- No jargon unless it's industry-standard and candidates will search for it
- No gendered language ("he/she" → "they", "manpower" → "staff")
- No exclusionary adjectives ("rockstar", "ninja", "culture fit")
- Total length: 400-600 words
- SEO: include job title in H1 and first 50 words; include city/state for local roles
```

---

## Usage Notes

- Paste the prompt into Claude with your inputs filled in
- The DEI section auto-generates — customize the tone to match your company voice
- For remote roles, still include the company's HQ city for SEO indexing
- Add `[URGENT — IMMEDIATE START]` to the title line if timeline is critical

---

## Bias-Reduction Checklist (review before publishing)

- [ ] No degree requirements unless legally mandated for the role
- [ ] Years-of-experience requirements set at minimum viable, not maximum desired
- [ ] No culture-fit language (subjective, legally risky)
- [ ] Benefits section includes parental leave, not just "medical/dental/vision"
- [ ] Salary range included (required by law in CA, CO, NY, WA; best practice everywhere)
