# Thomas Frank Materials → Book (Claude)

## Goal
- Create a new book project based on the source archive **Thomasfrank.tar**.
- Store raw materials under `material/`.
- Write the book manuscript under `book/`.
- Use **Claude** (sub-agent) for all writing.

## Assumptions (until confirmed)
- Output language: Chinese (can switch to English if you prefer).
- Deliverable: a single consolidated manuscript file + per-chapter files if needed.

## Phases

### Phase 0 — Project Setup (complete)
- [x] Create project directory structure (`material/`, `book/`)
- [x] Locate `Thomasfrank.tar` in workspace; place into `material/`
- [x] Extract archive; inventory contents (256 main .srt files + macOS metadata copies)

### Phase 1 — Material Analysis (complete)
- [x] Summarize what’s inside (topics, formats, key themes)
- [x] Decide book positioning, audience, and table of contents

### Phase 2 — Writing Plan (complete)
- [x] Create `book/OUTLINE.md` with chapters, key points, and constraints
- [x] Define style guide (voice, examples, citations rules)

### Phase 3 — Draft Manuscript with Claude (pending)
- [ ] Draft chapters (Claude)
- [ ] Assemble full manuscript

### Phase 4 — Editorial Pass & Packaging (pending)
- [ ] Consistency checks (terminology, structure)
- [ ] Final polish

## Decisions Log
- 2026-02-28: Start new project `thomasfrank-book` in `/root/clawd/github/active/` (aligned with feelgood).

## Risks / Watchouts
- Archive may contain copyrighted content; we will transform and summarize rather than copy verbatim where necessary.
- Large files may require chunked reading and staged summarization.

## Errors Encountered
| Time | Error | Attempt | Resolution |
|---|---|---:|---|
| | | | |
