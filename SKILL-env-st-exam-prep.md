---
name: env-st-exam-prep
description: Environmental Studies final exam prep for Ch 19-21 (water, climate, air). Use for quizzes, drills, mocks, diagram practice, mastery tracking, and gap audits.
---

# env-st-exam-prep

## When to use
- Student studies for Env St **final exam** (Spring 2026)
- Requests: quiz, drill, mock, flashcards, diagram, weak spots, readiness check
- Chapters 19, 20, 21 — subjective and MCQ

## Session protocol
1. Read `prep/state/session-log.md`, `mastery.json`, `srs-queue.json`
2. Cite `prep/knowledge/` and `prep/question-bank/master-question-bank.md` only
3. Closed-book recall before revealing answers
4. Update state files after every session

## Workflows

### learn
Prime → encode (list/mnemonic) → light recall → update mastery

### drill
SRS `due_today` → 5–10 flashcards from `prep/flashcards/flashcards.md` → update mastery

### diagram
Pick from `prep/diagrams/exam-diagrams.md` → student draws → grade labels **(L)**

### chapter-test
20 Q from one chapter; mix MCQ + subjective; strict grading

### mock-exam
Timed; all chapters; report % and weak concept IDs

### weak-spot
All mastery scores 0–2 from `mastery.json`; drill until 3+

### zero-gap-audit
Walk `prep/coverage/clo4-mastery-grid.md` M-tier rows; flag any not at 4+

## Deliverable map
| Need | File |
|------|------|
| Concepts | `prep/knowledge/ch19-*.md`, `ch20-*.md`, `ch21-*.md` |
| Grid | `prep/coverage/clo4-mastery-grid.md` |
| Questions | `prep/question-bank/master-question-bank.md` |
| Diagrams | `prep/diagrams/exam-diagrams.md` |
| Flashcards | `prep/flashcards/flashcards.md` |
| State | `prep/state/mastery.json`, `srs-queue.json`, `session-log.md` |
| Scope | `AGENTS.md` |
| Build status | `prep/audit/PHASE-2-SIGNOFF.md` |

## SRS intervals (days)
1 → 3 → 7 → 14 when promoting toward score 5

## CLO map
- Ch 19, 21 → CLO#3
- Ch 20 → CLO#4
