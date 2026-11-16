# AI Docs Playbook prompts

This folder contains the prompts from the [AI Docs Playbook](https://zaycodes.com/resources#ai-docs-playbook). Each one is a copy-paste prompt for a chat assistant such as ChatGPT, Claude, or Gemini. They also work in an AI coding agent.

The Playbook explains when to use each prompt and shows a worked example. This folder holds the full prompts, so you can copy them without reformatting.

## The prompts

| File | Workflow | What it does |
|---|---|---|
| `prompts/01-docs-assistant-briefing.md` | 01 | Briefs the AI on your readers, docs, and style before any task |
| `prompts/02-support-conversation-to-doc-ticket.md` | 02 | Turns a support conversation into a documentation ticket |
| `prompts/03-document-a-feature-from-a-screenshot.md` | 03 | Drafts a how-to page from a screenshot, marking what needs verification |
| `prompts/04-page-templates-and-restructure.md` | 04 | Two page templates, and a prompt that restructures a page into one |
| `prompts/05-house-style-copy-edit-pass.md` | 05 | Checks a draft against your house style and applies safe fixes |
| `prompts/05-starter-house-style.md` | 01, 05 | A starter set of house style rules to adapt |
| `prompts/06-multi-dimension-editorial-review.md` | 06 | Reviews a draft on seven dimensions, findings only |
| `prompts/06-density-check.md` | 06 | Flags sentences that add no new information |
| `prompts/07-terminology-audit.md` | 07 | Finds the same concept called by different names |

## How to use them

1. Start with `01-docs-assistant-briefing.md`. Fill in its placeholders and paste it as the first message of a new chat, or save it as a project or custom instruction.
1. Open the prompt for the task you need, copy the text inside the code block, and replace the placeholders in angle brackets, such as `<paste text, or name the file>`.
1. Review the output. The prompts ask the AI to mark anything it could not confirm with `VERIFY`, so check those first.

## License

MIT. See [LICENSE](../LICENSE).
