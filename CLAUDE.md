# study-english

This repository is for English practice. The deliverable is prose, not code — do
not scaffold projects, add build tooling, or set up tests here unless asked.

## Where lessons come from

Any prompt I have written, in any session, in any project — not just the ones in
this repository. Correcting my English is a standing instruction everywhere, so
this file is the one place the results accumulate.

Past sessions are on disk as JSONL at `~/.claude/projects/*/*.jsonl`. In those
files, a line of `"type": "user"` is usually a tool result rather than something
I wrote; the ones I actually typed carry `"origin": {"kind": "human"}`. Filter on
that, strip `<system-reminder>` and `<command-*>` wrappers, and skip the
`<scheduled-task>` blocks — those are prompts you wrote, not me. A full sweep is
a few hundred prompts, so re-reading the history is cheap and the dedup rule
below makes it safe to repeat.

## Logging lessons

`lessons.md` holds what has been learned about my English, and nothing else.

**Never log prompts, messages, or session narrative.** This repository is public,
and the prompt history it draws on is not. A transcript of raw prompts is both an
exposure and worse material to reread than a rule is. No per-session or per-date
files.

**Add a lesson only when it is new.** Read `lessons.md` first. If the rule behind
a correction is already there, change nothing and say so in the reply — a repeat
of a known mistake is not a new lesson. When a new case shows an existing entry
was too narrow, sharpen that entry rather than adding a second one.

**Write the rule, not the incident.** "Uncountable nouns take no plural" is a
lesson. "Got `practices` wrong on Tuesday" is not. No dates, no "today I wrote".

**Invent the examples.** When an entry needs an example sentence, write a fresh
one that isolates the rule. Never quote my messages, corrected or otherwise — a
made-up example is clearer anyway, because it can be built to show one thing.

**Log in the same reply as the correction**, not at session end. A session can be
interrupted, and an unlogged lesson is a lost one.

## What does not go here

Facts that hold regardless of this repository — general engineering knowledge —
belong in the knowledge base at `../knowledge-base`, not in these files.
