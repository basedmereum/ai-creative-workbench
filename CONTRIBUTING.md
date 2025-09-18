# Contributing

Thanks for helping expand the AI Creative Tools Hub! Thoughtful contributions keep the list useful for artists, studios, and educators.

## Ground Rules
- Focus on tools that meaningfully support creative work (visual, audio, narrative, or collaborative) and are actively maintained.
- Keep writeups vendor-neutral: highlight strengths and guardrails without marketing fluff.
- Stick to ASCII characters unless a tool name requires otherwise.
- Prefer primary sources for links (official site, GitHub repo, or documentation).

## Adding or Updating a Tool
1. Pick the correct category in `categories/`. If none fits, mention a proposal for a new category in your PR description.
2. Copy the category's markdown template block (shown near the top of each file).
3. Alphabetize entries by tool name within the file.
4. Fill out every field:
   - **Website:** official homepage or canonical repo
   - **Tags:** 3-5 comma-separated keywords (`open-source`, `workflow`, `text-to-video`, etc.)
   - **License:** SPDX identifier for open-source or "Proprietary" with plan details if relevant
   - **Overview:** single sentence capturing what makes the tool valuable to creatives
   - **Use Cases:** at least two bullet examples of how creatives leverage the tool
   - **Update Pulse:** optional but encouraged. Note release cadence, GitHub activity, or changelog frequency with a date if you have one
5. Preview the markdown to ensure anchors (`## Tool Name`) match any README references.

## Removing or Deprecating a Tool
- Briefly explain why the tool is being removed (e.g., shut down, abandoned, misleading claims).
- Add a note to the PR template checklist confirming that you searched for replacements.

## Style & Formatting
- Use sentence case for headings (e.g., `## ComfyUI`).
- Keep descriptions concise—two sentences max before the bullet list.
- When citing metrics (users, funding, etc.), include a source link.

## Submitting Pull Requests
- Create a feature branch and commit your changes.
- Run any scripts or checks you add; remove temporary tooling before opening the PR.
- Fill out `.github/pull_request_template.md` so reviewers can quickly validate scope, tags, and licensing.

## Reviews & Maintenance
- Reviewers verify category fit, metadata accuracy, and tone consistency.
- Feel free to suggest small edits inline; maintainers will edit for grammar or clarity as needed.
- Major reorganizations should be discussed in an issue or draft PR before implementation.

Questions or unsure whether a tool fits? Open an issue with the tool name, category, and why you think it belongs here.
