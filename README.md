# AI Rules for Next.js 15+ / Tailwind v4 / Supabase

Free starter pack for teams who want better default output from Cursor and Claude Code on this stack.

## Included

```text
github.com/tonhandle/ai-rules-nextjs-supabase/
|-- cursor/
|   `-- .cursorrules
|-- claude-code/
|   `-- nextjs-supabase/
|       `-- SKILL.md
|-- README.md
`-- LICENSE
```

## What the lite version covers

- Server Components by default
- Async `params` / `searchParams` for Next.js 15+
- App Router structure and route groups
- Tailwind CSS v4 basics with `@theme`
- Supabase server vs browser client split
- Zod validation, `getUser()`, and typed route handlers

## Install

### Cursor

Copy [`cursor/.cursorrules`](cursor/.cursorrules) to the root of your project.

### Claude Code

Copy [`claude-code/nextjs-supabase/SKILL.md`](claude-code/nextjs-supabase/SKILL.md) into:

```text
~/.codex/skills/nextjs-supabase/SKILL.md
```

## Why use it

Without stack-specific rules, AI editors often:

- use `useEffect` for first-load data fetching
- forget that Next.js 15 params are async
- use `getSession()` instead of `getUser()`
- fall back to `select('*')`
- mix Tailwind v3 patterns into Tailwind v4 projects

## Get the full pack ->

The commercial pack adds:

- the full Cursor ruleset
- a richer Claude Code skill package
- extra references, prompts, and before/after examples
- packaging for direct team distribution

Replace this CTA with your product link:

```text
https://gumroad.com/l/your-full-pack
```
