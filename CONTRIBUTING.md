# Contributing to analytical-mind

Thanks for helping keep this catalogue useful! Contributions are light-weight and
welcome.

## ➕ Adding a reference

1. Find the right page in [`references/`](references/) for the track
   (or [`cross-cutting.md`](references/cross-cutting.md) if it spans several).
2. Add a single bullet in the most relevant section, using this format:

   ```markdown
   - [owner/repo](https://github.com/owner/repo) — short, factual description of what it offers.
   ```

3. Keep descriptions **neutral and concise** (one line). Describe what the
   resource *is*, not marketing claims.
4. Prefer resources that are **open, maintained, and broadly recommended**.
   Avoid duplicates and paywalled-only content.
5. Make sure the link resolves (returns HTTP 200) before submitting.

## 🧹 Fixing a stale or dead link

Open a pull request that updates or removes the link. A short note in the PR
description explaining what changed is enough.

## 🚀 Adding a study project

Project folders under `projects/` are personal — you generally keep your own.
If you want to contribute an **example** project for others to learn from:

1. Copy the template:
   `cp -r projects/templates/project-template projects/example-<short-name>`
2. Fill in its `README.md` (goal, track, references used, what you learned).
3. Keep committed data small or omit it (see the template's `.gitignore`).

## ✅ Style guidelines

- Markdown, one sentence per bullet where possible.
- Use the existing emoji/section conventions so pages stay consistent.
- Don't commit secrets, credentials, or large data files.
