# study-english

This repository is for English practice. The deliverable is prose, not code — do
not scaffold projects, add build tooling, or set up tests here unless asked.

## Logging corrections

Every correction made in a session must be logged. Do this as part of the reply
that contains the correction, not at the end of the session — a session can be
interrupted, and an unlogged correction is a lost one.

1. **Append to `sessions/YYYY-MM-DD.md`** (Korean calendar day). Create the file
   with an `# YYYY-MM-DD` heading if it does not exist. One entry per correction:

   ```markdown
   ## <short label for the mistake>

   - **Wrote:** <the original text, verbatim>
   - **Better:** <the corrected version>
   - **Why:** <the rule, in one or two sentences>
   ```

   Quote the original verbatim. A cleaned-up version of the mistake is useless
   for spotting a pattern later.

2. **Promote to `patterns.md` on the second occurrence.** Grep the `sessions/`
   files before writing. If the same underlying rule has already been logged on
   another day, add it to `patterns.md` under the right heading, with both dates
   cited. Do not promote on the first occurrence — `patterns.md` is only useful
   while it is short.

3. **Log the rule, not the sentence.** "Article missing before a singular count
   noun" is a pattern; "forgot 'the' in that one email" is not.

## What does not go here

Facts that hold regardless of this repository — general engineering knowledge —
belong in the knowledge base at `../knowledge-base`, not in these files.
