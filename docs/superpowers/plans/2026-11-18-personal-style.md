# Personal Style implementation plan

> **For agentic workers:** Use superpowers:executing-plans for inline execution and one independent whole-branch review. The owner's standing workflow governs integration without another approval request.

**Goal:** Publish the approved source-aware clothing and hair knowledge base.

**Architecture:** Plain Markdown with English and Chinese entry points, Chinese topic notes, stable source IDs and blank templates. Personal data remains outside Git.

**Tech stack:** Markdown, Git and GitHub CLI; no application runtime.

**Spec:** [Approved design](../specs/2026-11-18-personal-style-design.md)

## Global constraints

- Public repository; no private records or unlicensed attachments.
- English README and Chinese entry point; initial topic notes in Chinese.
- Catalog verification is distinct from reading a book or checking a claim.
- Keep ancestry separate from individual styling decisions.

## Review focus

- Broken relative paths and stable source fragments.
- Unverified bibliographic details presented as facts.
- Styling proposals presented as scientific or personal results.
- Private information or copied materials in public history.
- Inconsistent language navigation or scope between entry points.

## Task 1 — Sources and original notes

Files: `README*`, `hair/`, `fashion/`, `references/`, `docs/start-here.zh-CN.md`, `docs/method.zh-CN.md`.

- [x] Check official source descriptions and one paper abstract; preserve unresolved leads.
- [x] Write original notes and two concise entry points; connect claims to their scope.
- [x] Check links and fragments, read the notes and inspect source wording.

## Task 2 — Practice and public boundaries

Files: `templates/`, `experiments/`, `docs/privacy*`, `CONTRIBUTING*`, `AGENTS.md`, `.gitignore`.

- [x] Add blank research, haircut, outfit and wardrobe templates.
- [x] Document private storage and contribution boundaries without embedding machine paths.
- [x] Verify template reachability, language parity and absence of completed personal records.

## Task 3 — Review and delivery

- [x] Run `git diff --check` and a local relative-link/fragment scan; review staged content.
- [ ] Commit with the account's public noreply identity; request independent review and fix material findings.
- [ ] Create the public repository, push the task branch and open a PR against its current `main`.
- [ ] Check the current combined result and repository controls, merge under standing authorization, verify remote `main`, fast-forward the clean primary checkout and clean up task-only branches/worktree.

No software behavior is introduced. Application tests and deployment are not applicable; documentation checks and content review are the relevant validation.
