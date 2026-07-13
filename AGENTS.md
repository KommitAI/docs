<!-- BEGIN KOMMIT AGENT POLICY v1 -->
## KommitAI shared agent policy

- Default to one agent and one writer. Delegate only independent, read-heavy work that materially reduces elapsed time.
- Use at most two direct children, keep them read-only unless explicitly designated otherwise, and never recursively delegate.
- Search exact symbols and paths before opening broad documentation trees or large groups of files.
- Run focused validation while iterating; run broad validation at most once near the requested delivery boundary.
- Treat Ultra reasoning and provider Fast mode as explicit, task-local escalations, never as defaults combined with fan-out.
- Respect the requested lifecycle boundary. Do not continue into review, deployment, merging, or follow-up work unless asked.
- Preserve repository-specific guidance outside this managed block.
<!-- END KOMMIT AGENT POLICY v1 -->

> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

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
