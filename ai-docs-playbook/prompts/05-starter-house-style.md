# Starter house style

If you do not have a documented house style yet, start with these rules and adapt them. Add your product terminology, remove rules that do not apply, and tighten the rest. Use it with workflows 01 and 05 in the AI Docs Playbook.

```text
HOUSE STYLE RULES — these override any general grammar guide.

Voice and tone:
- Use active voice. The subject performs the action.
- Address the reader as "you." Never say "the user" or "one."
- Put conditions before instructions: "To delete X, click Delete." Not: "Click Delete to delete X."
- No hedging: remove "should," "might," "could" when stating product behavior.

Prohibited terms and phrases:
- Never use: utilize, leverage, seamlessly, robust, comprehensive, cutting-edge,
  empower, streamline, unlock, harness, delve, moreover, furthermore.
- Never use: "it's worth noting," "please note that," "in order to," "due to
  the fact that," "enables you to," "allows you to," "take advantage of."
- Replace "utilize" with "use." Replace "leverage" with "use."
- Replace "allows you to" / "enables you to" with direct action language.

Formatting:
- Sentence case for all headings. Capitalize only the first word and proper nouns.
- Unordered lists: use * for every item, never -.
- Ordered lists: use 1. for every item, not sequential numbers (1, 2, 3...).
- UI labels in bold: **Settings**, **Save**, **Delete**.
- Code and parameter names in backticks: `api_key`, `timeout_ms`.

Punctuation:
- No em dashes (—). Use a colon, a period, or restructure.
- No semicolons. Split into two sentences.
- No smart quotes. Use straight ASCII quotes only.
- Periods go inside closing quotation marks.

Demonstrative pronouns:
- Never leave "This," "These," "That," or "Those" bare. Always follow with a noun.
  Write "This value prevents..." not "This prevents..."
  Write "These settings control..." not "These control..."

Links:
- Never invent a URL. If you need to link somewhere and do not have the URL,
  write [VERIFY: link to X page] instead.
- Link text describes the destination. Never use "click here" or "here."

When uncertain:
- If behavior is unclear, write [VERIFY: describe what needs confirmation].
- If information is missing, write [GAP: describe what is needed].
- Never guess at product behavior, default values, or parameter names.
```
