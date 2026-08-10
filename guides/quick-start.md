# Quick-Start Guide

Go from download to your first documented SOP in one sitting. This should take 30-45 minutes.

---

## Step 1: Choose Your First SOP (5 minutes)

Don't try to document everything at once. Pick **one process** using this priority framework:

| Priority | Criteria | Example |
|----------|----------|---------|
| **Document first** | Only one person knows how to do it | "Only Sarah handles refunds" |
| **Document second** | Mistakes keep happening | "We keep sending the wrong invoice template" |
| **Document third** | It runs frequently | "We onboard 3-5 clients per month" |
| **Document later** | It's stable and rarely causes issues | Annual tax filing with your accountant |

**Pick the process that scores highest on the first two criteria.** That's your starting SOP.

---

## Step 2: Pick a Template (2 minutes)

Match your process to a template:

| If your process is about... | Use this template |
|----------------------------|-------------------|
| Bringing on new clients | `02-client-onboarding.md` |
| Hiring and training new employees | `03-employee-onboarding.md` |
| Creating and publishing content | `04-content-publishing.md` |
| Reviewing work before it ships | `05-quality-assurance.md` |
| Anything else | `01-general-sop.md` |

---

## Step 3: Generate Your SOP with AI (15-20 minutes)

This is where the AI prompts save you hours.

### Option A: You have rough notes or a checklist

1. Open `prompts/sop-generator.md`
2. Copy **Prompt 7** (Convert an Existing Checklist into a Full SOP)
3. Paste it into ChatGPT, Claude, or your preferred AI tool
4. Paste your existing notes/checklist where indicated
5. Review the output and ask follow-up questions to refine it

### Option B: The process is in your head

1. Open `prompts/sop-generator.md`
2. Copy **Prompt 4** (Generate an SOP from "How I Do It" Brain Dump)
3. Paste it into your AI tool
4. Just start talking/typing about how you do the thing — don't worry about formatting
5. Review the output and refine

### Option C: You're starting from scratch

1. Open `prompts/sop-generator.md`
2. Copy **Prompt 1** (Generate a Full SOP from a Process Description)
3. Paste it into your AI tool
4. Describe the process as best you can
5. Review and refine

**Pro tip:** After generating, run the output through **Prompt 1 from `prompts/industry-customizer.md`** to add industry-specific details.

---

## Step 4: Import into Notion (5-10 minutes)

### Method 1: Copy-Paste (Fastest)

1. Open Notion
2. Create a new page (or create a page inside a "SOPs" database)
3. Copy the entire SOP content from the AI output
4. Paste into Notion — it auto-formats markdown headings, tables, and checkboxes

### Method 2: Import Markdown File

1. In Notion, click **"..."** menu on any page
2. Select **"Import"**
3. Choose **"Text & Markdown"**
4. Upload the `.md` file
5. Notion will create a new page with the content formatted

### Method 3: Use Notion Templates Directly

1. Create a new Notion database called **"SOPs"**
2. Add properties:
   - **Status** (Select: Draft / In Review / Active / Archived)
   - **Owner** (Person)
   - **Department** (Select: Operations / Sales / Marketing / etc.)
   - **Last Reviewed** (Date)
   - **Version** (Number)
3. Each SOP becomes a page in this database
4. Paste or import your SOP content into each page

### Recommended Notion SOP Database Structure

```
SOPs (Database)
├── Properties: Status, Owner, Department, Last Reviewed, Version
├── Views:
│   ├── All SOPs (Table view, sorted by department)
│   ├── Needs Review (Filtered: Last Reviewed > 90 days ago)
│   └── By Department (Board view, grouped by department)
└── Pages:
    ├── Client Onboarding SOP
    ├── Employee Onboarding SOP
    └── [Your SOPs here]
```

---

## Step 5: Validate (5 minutes)

Before calling it done:

- [ ] Read through the SOP as if you've never done this process before
- [ ] Check: would a new hire be able to follow this without asking you questions?
- [ ] Verify all tool names, links, and access info are correct
- [ ] If possible, have someone else read it and tell you where they'd get stuck

---

## What to Do Next

### This week:
- [ ] Share the SOP with anyone who does this process
- [ ] Ask them to follow it next time and note any gaps

### This month:
- [ ] Document 2-3 more processes using the same workflow
- [ ] Run the **Process Auditor** prompts on your most important process

### Every quarter:
- [ ] Review all active SOPs — are they still accurate?
- [ ] Use **Process Auditor Prompt 6** (Quarterly Process Review)
- [ ] Update version numbers and revision history

---

## Troubleshooting

**"The AI output doesn't match my business."**
Add more context to the prompt. Include your industry, team size, tools you use, and specific pain points. The more detail you give, the more specific the output.

**"The SOP is too long / too detailed."**
Tell the AI: "Simplify this SOP to the essential steps only. Remove any step that wouldn't cause a problem if skipped."

**"The SOP is too generic."**
Run it through the Industry Customizer prompts. Or add to the original prompt: "Be specific to [your industry]. Use the terminology a [your role] would actually use."

**"My team won't read a long document."**
Ask the AI: "Create a one-page cheat sheet version of this SOP — just the steps, no explanations." Pin the cheat sheet next to the full SOP in Notion.

**"I have processes that span multiple departments."**
Create a separate SOP for each department's piece, then create a "Master Process" page in Notion that links them in order.

---

## Getting Help

- **Open an issue** on the [GitHub repo](https://github.com/RnBBnBOrg/sop-builder-kit) if you have questions
- **Share your feedback** — we're constantly adding new templates and prompts based on what users need
