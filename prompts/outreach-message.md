# Prompt: Passive Candidate Outreach Message

## Purpose
Generate personalized recruiter outreach for passive candidates on LinkedIn and via email. Two variants each — one short (LinkedIn character limit), one full (email).

---

## The Prompt

```
You are a top-performing technical recruiter known for response rates 3x the industry average. Write personalized outreach messages for passive candidate recruiting.

INPUTS:
- Job title: [JOB_TITLE]
- Company name: [COMPANY_NAME]
- Key selling points of the role (3): [LIST — compensation, growth, tech, mission, etc.]
- Candidate's current role/company (from their profile): [CURRENT_ROLE at CURRENT_COMPANY]
- One specific thing from their background that made you reach out: [SPECIFIC DETAIL — a project, publication, skill, shared connection, etc.]
- One thing that makes this company special (not generic): [SPECIFIC FACT]
- Urgency level: [low / medium / high — high = actively closing, medium = building pipeline, low = exploratory]

OUTPUT: Generate all 4 messages below.

---

**MESSAGE 1: LinkedIn Connection Request Note** (max 300 characters)
- Lead with the specific thing you noticed about them
- State what you're reaching out about in one clause
- No hard sell — curiosity, not pitch
- End with a low-commitment question or observation

---

**MESSAGE 2: LinkedIn InMail** (max 400 words)
Structure:
- Line 1: The hook — reference their specific background detail, not their job title
- Lines 2-3: Why this role is different from the 20 other recruiter messages they got this week
- Lines 4-5: The 3 selling points (brief — 1 sentence each)
- Line 6: Soft ask — "worth 15 minutes?" not "are you open to new opportunities?"
- Sign off: name, title, company, one contact method

Tone: peer-to-peer, not salesy. Write like a person, not a recruiter template.

---

**MESSAGE 3: Cold Email — Subject Line (3 variants)**
Rules: under 50 characters, personalized, no spam trigger words ("opportunity", "exciting", "synergy")
Write 3 options ranked by predicted open rate, with one-line rationale for each.

---

**MESSAGE 4: Cold Email Body** (150-200 words)
- Subject line: [use best option from Message 3]
- Opening: Reference the specific background detail in sentence 1
- Paragraph 1 (2-3 sentences): What the role is + why it's worth their time
- Paragraph 2 (2-3 sentences): What makes the company different — be specific
- CTA: One clear ask. Offer a specific time slot or a Calendly link placeholder
- P.S. line: Add a human touch — reference something current about their company or industry

RULES FOR ALL 4 MESSAGES:
- Never use: "I came across your profile", "exciting opportunity", "competitive salary", "fast-paced", "we're looking for a rockstar"
- Assume the candidate is happy where they are and needs a reason to engage
- Every message must pass the "would I respond to this?" test
- No attachments, no JD links in first contact — earn the reply first
```

---

## Usage Notes

- Fill in the "specific detail" field from 5 minutes of actual research — this is what separates 5% response rates from 35%
- LinkedIn connection note is for cold outreach to 1st/2nd degree connections
- InMail is for 3rd degree or out-of-network
- Run variants: change the hook to match different candidate backgrounds for same role
- Follow-up: wait 5 business days, then send a 3-sentence follow-up referencing your first message
