# Run a multi-dimension editorial review

Findings only. The prompt reviews a draft on seven dimensions and does not change the text. Workflow 06 in the AI Docs Playbook.

```text
Review the document below (or the file I name) against the dimensions listed.
Do not rewrite or modify the source text. Do not invent product behavior.
Findings only.

## Review dimensions

Evaluate each dimension independently. Only flag genuine problems.

### Concision
Sentences using more words than necessary. Setup phrases, hedging language,
and redundant qualifiers are the common culprits. Test: can the sentence be
shortened without losing meaning?

### Information density
Sentences or paragraphs delivering little or no new information: restatements
of what a heading already says, throat-clearing introductions, transition
sentences describing what the next paragraph will say.

### Scanability
* Paragraphs longer than 5 sentences that could be lists
* Sections with no visual break between dense prose blocks
* Missing or weak lead sentences that do not orient the reader

### Progressive disclosure
Information that appears before the reader needs it. Background and context
follow actionable content, not precede it.

### Action clarity
For procedural sections: instructions that are ambiguous, incomplete, or
missing an explicit outcome.

### AI-sounding phrasing
"delve into", "it's worth noting", "comprehensive", "robust", "leverage",
"seamlessly", "empower", "streamline", "unlock", "harness", "moreover",
"furthermore", "take advantage of", "this allows you to", "this enables you to".

### Style compliance
No em dashes. No semicolons. No bare demonstrative pronouns. Sentence case for
all headings. Consistent list marker style.

## Output format

### Summary
One paragraph: what the doc covers, whether it meets its goals.

### Findings table

| Severity | Location | Issue | Dimension | Fix |
|---|---|---|---|---|
| Critical/Major/Minor | heading or phrase | description | dimension name | one-line fix |

Severity:
* Critical: must fix. Broken instruction or factual risk.
* Major: should fix. Significantly hurts clarity.
* Minor: writer's discretion.

### Top 3 changes for biggest impact
Format: Outcome → Action.

### Open questions
Clarifying questions about gaps or ambiguous content.

Content:
<paste text, or name the file>
```
