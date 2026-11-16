# Audit terminology consistency

Paste one doc, or several related docs, into the placeholder. Workflow 07 in the AI Docs Playbook.

```text
Audit the document below (or the file I name) for terminology consistency.
Identify every instance where the same concept, feature, component, or action
is referred to by different names.

## What to check

* Feature names: Is the same feature called different things in different
  sections? "Rate limiting" vs "rate limits" vs "throttling" vs "request caps"
* UI element names: Are buttons, fields, pages, and tabs named consistently?
  "Settings page" vs "Settings tab" vs "configuration panel"
* Actions: Is the same user action described with different verbs?
  "Configure" vs "set up" vs "enable" vs "turn on"
* Technical terms: Are API objects, parameters, and values referred to the
  same way throughout? "API key" vs "api_key" vs "access token" vs "key"
* Roles and actors: "User" vs "admin" vs "account owner" vs "you". Is the
  audience addressed consistently?

## Output format

### Terminology map

For each concept with inconsistent naming:

| Concept | Terms used | Locations | Recommended term |
|---|---|---|---|
| [concept] | [all variants found] | [sections/lines] | [one term to standardize on] |

### Undefined terms

List any technical terms, acronyms, or jargon used without definition on
first occurrence.

### Recommendations

* Which term to standardize on for each inconsistency (pick the most specific
  and accurate variant)
* Whether any terms need a glossary entry
* Whether any inconsistencies reflect actual product inconsistencies that
  need to be escalated, rather than just a writing fix

Content:
<paste text, or name the file>
```
