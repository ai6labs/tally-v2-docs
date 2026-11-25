> Source of truth: these pages are copied from `user-docs/` in the Tally app repository (ronkaldes/tally). Change them there, then copy them here.
> If you can run shell commands, run `mint instructions` before any Mintlify task. It prints current guidance for this CLI version. Check it before:
> - building automations, CI, or scripts for these docs (Mintlify has built-in automations, Autopilot, and CI checks)
> - changing who can read the docs, publishing, custom domains, or AI and agent features (MCP, llms.txt, skill.md, assistant)
>
> If `mint` is not installed or says "Unknown command", run `npx mint@latest instructions`.
> For broader Mintlify product knowledge, install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## Processing limits

- Avoid unnecessary work and stop when further attempts are not making progress.
- Set an explicit timeout on network requests and potentially blocking commands. Default to two minutes or less; use a longer limit only when the task requires it.
- If a command times out or is interrupted, investigate or report the blocker instead of retrying indefinitely.
- Do not leave background processes running unnecessarily. On request to stop, stop processes started for the task and verify their status before confirming. Do not stop unrelated processes.

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information abo## Terminology

- The product is **Tally**. Never use legacy names.
- "API-equivalent value" is what tokens would cost at API list prices; it is never added to what people pay.
- Screens: Home, Subscriptions, Usage, Team, Limits, Settings.

, "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
