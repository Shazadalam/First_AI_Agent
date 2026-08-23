# First AI Agent

A personal workspace for research, software development, and productivity workflows — built around a structured, repeatable process for turning a topic into a well-organized, sourced report.

## Project Structure

```
.
├── workflow/   # Process definitions — how tasks like research get executed
├── output/     # Finished deliverables (reports, docs)
├── resource/   # Reference material and cited sources
└── claude.md   # Project context and working rules
```

## Research Workflow

Given a topic, the project follows a defined process (see [workflow/research-report.md](workflow/research-report.md)):

1. **Clarify** — scope, depth, purpose, and time-sensitivity are confirmed before research starts
2. **Research** — information gathered from multiple sources, cross-checked where possible
3. **Organize** — findings grouped by theme rather than presented as a raw dump
4. **Report** — structured Markdown output: executive summary, key findings, details, sources, open questions
5. **Save** — the report goes to `/output`, and every source used is logged to `/resource`

## Example Output

- [`output/ai-agents-2026-2026-08-23.md`](output/ai-agents-2026-2026-08-23.md) — a research report on the current state of AI agents in 2026
- [`resource/ai-agents-2026-sources.md`](resource/ai-agents-2026-sources.md) — the sources cited in that report

## Working Rules

- Concise, bullet-point output over long paragraphs
- Clarifying questions before starting on complex or ambiguous tasks
- All research is sourced and cited
