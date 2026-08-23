# Workflow: Research → Structured Report

Trigger: user gives a topic and asks for research/a report on it (plain conversation — no fixed command needed).

## Step 1 — Clarifying questions (always ask first)
Use AskUserQuestion, single batch, before doing any research:
- **Scope/angle** — technical overview, market landscape, comparison, historical background, etc.?
- **Depth** — quick brief / standard report / deep-dive?
- **Audience/purpose** — personal learning, decision-making, sharing with others? (tunes tone/detail)
- **Time sensitivity** — needs latest/current info, or evergreen is fine?

Skip questions (or ask only the missing ones) if the user already gave enough context in their request.

## Step 2 — Research
- Use web search to gather multiple credible sources.
- Cross-check key facts across at least 2 sources where possible.
- Track each source's title + URL as you go.

## Step 3 — Organize
- Group findings by theme/sub-topic, not chronological dump.
- Consolidate redundant info; flag conflicting info explicitly.

## Step 4 — Report structure (default: standard)
Markdown file with:
1. Title + date
2. **Executive Summary** — 3-5 bullets, top-level takeaways
3. **Key Findings** — grouped by sub-topic, bullet points (not paragraphs)
4. **Details** — deeper explanation per section, still concise
5. **Sources** — numbered list (title + URL), cited inline as [1], [2]...
6. **Open Questions / Gaps** (optional) — ambiguity or conflicting info found during research

Adjust length/detail based on the depth answer from Step 1 (quick brief = trim to Summary + Key Findings + Sources; deep-dive = expand Details with more sub-sections/comparisons).

## Step 5 — Save output
- Save the report to `/output/<topic-slug>-<YYYY-MM-DD>.md`
- Save a sources file to `/resource/<topic-slug>-sources.md` listing every reference used (numbered list matching the report's citations: title + URL, one line each)
- Confirm both saved file paths to the user.
