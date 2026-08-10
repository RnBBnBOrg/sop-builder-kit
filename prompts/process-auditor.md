# Process Auditor — AI Prompt Pack

Use these prompts to analyze your existing processes, find inefficiencies, and identify what's missing before it becomes a problem.

---

## Prompt 1: Full Process Audit

```
You are an operations consultant performing a process audit for a small business. I'm going to describe a process we currently follow. Analyze it and provide:

1. **Process Health Score** (1-10) with justification
2. **Bottlenecks** — where does this process slow down or break?
3. **Single Points of Failure** — what happens if one person is unavailable?
4. **Missing Steps** — what's implied but not documented?
5. **Redundancies** — are we doing anything twice or unnecessarily?
6. **Risk Assessment** — what could go wrong and how likely is it?
7. **Quick Wins** — 3 things we could fix this week to improve the process
8. **Long-Term Improvements** — bigger changes to consider over the next quarter

Be direct and specific. Don't sugarcoat problems.

Our process:

[DESCRIBE YOUR CURRENT PROCESS — HOW IT ACTUALLY WORKS, NOT HOW IT'S SUPPOSED TO WORK]
```

---

## Prompt 2: Compare Actual vs. Documented Process

```
I have a documented SOP and I'm going to describe how the process actually works in practice. Compare the two and identify:

1. **Gaps** — steps in the SOP that nobody actually follows
2. **Undocumented steps** — things people do that aren't in the SOP
3. **Workarounds** — places where people have created informal shortcuts
4. **Drift reasons** — why you think the process drifted from the documentation
5. **Recommendation** — should we update the SOP to match reality, or retrain on the original SOP?

Documented SOP:

[PASTE YOUR EXISTING SOP]

How it actually works:

[DESCRIBE WHAT REALLY HAPPENS]
```

---

## Prompt 3: Identify Processes That Need SOPs

```
I run a small business and I want to figure out which processes I should document first. Here's information about my business:

- Industry: [YOUR INDUSTRY]
- Number of employees: [NUMBER]
- Main services/products: [WHAT YOU SELL]
- Biggest operational headaches: [WHAT KEEPS GOING WRONG]
- Tools we use: [LIST YOUR TOOLS]
- What happens when someone is sick or quits: [HOW DEPENDENT ARE YOU ON SPECIFIC PEOPLE]

Based on this, give me a prioritized list of the 10 most important SOPs I need, ranked by:
- Impact (how much it would help)
- Risk (what happens if this process fails)
- Frequency (how often this runs)

For each one, give me a one-sentence description and estimate how long it would take to document.
```

---

## Prompt 4: Process Efficiency Analysis

```
Analyze this process for efficiency. I want to know:

1. **Time spent** — estimate how long each step takes and the total process time
2. **Value vs. waste** — which steps directly create value, and which are overhead?
3. **Automation opportunities** — which steps could be automated with existing tools?
4. **Delegation opportunities** — which steps could be done by someone less experienced?
5. **Elimination candidates** — which steps might not be necessary at all?

Give me a table with each step, its estimated time, whether it's value-add or overhead, and your recommendation (keep, automate, delegate, or eliminate).

The process:

[DESCRIBE YOUR PROCESS WITH AS MUCH DETAIL AS POSSIBLE]
```

---

## Prompt 5: "Bus Factor" Assessment

```
The "bus factor" is how many people would need to be unavailable before a process completely stops. I want you to assess the bus factor for my team's key processes.

For each process I describe, tell me:
- Current bus factor (how many people can do this)
- Risk level (critical / high / medium / low)
- What breaks first if the key person is unavailable
- What to do about it (cross-train, document, automate, or accept the risk)

My team and what they do:

[DESCRIBE YOUR TEAM MEMBERS AND THEIR RESPONSIBILITIES]
```

---

## Prompt 6: Quarterly Process Review

```
It's time for our quarterly process review. I'm going to share our SOPs and any issues we've experienced in the last 90 days. For each SOP, tell me:

1. Is this SOP still accurate? (based on the issues reported)
2. What should be updated?
3. Are there new processes we should document based on the issues?
4. Are there processes we should retire or merge?

SOPs we currently have:

[LIST YOUR SOP TITLES AND A ONE-LINE DESCRIPTION OF EACH]

Issues / incidents in the last 90 days:

[LIST PROBLEMS THAT CAME UP — MISTAKES, DELAYS, CLIENT COMPLAINTS, ETC.]
```

---

## Prompt 7: Client Feedback to Process Improvement

```
I'm going to share client feedback (complaints, praise, and suggestions). Analyze it and tell me:

1. Which internal processes are causing the complaints?
2. Which processes are driving the praise (so we protect them)?
3. What process changes would address the top 3 complaints?
4. Draft an updated SOP section for each recommended change.

Client feedback:

[PASTE CLIENT FEEDBACK — REVIEWS, SURVEY RESPONSES, EMAILS, CALL NOTES]
```

---

## Tips for Best Results

1. **Be honest about how things actually work.** The AI can only audit what you tell it. If you describe the ideal instead of the reality, the audit is useless.
2. **Include failure examples.** "Last month we missed a deadline because..." gives the AI concrete problems to solve.
3. **Run these quarterly.** Set a calendar reminder. Processes drift — a quarterly check keeps them aligned.
4. **Share the results with your team.** The audit findings aren't just for you — the people doing the work often have the best ideas for fixing problems.
5. **Start with the process that causes the most pain.** Don't try to audit everything at once.
