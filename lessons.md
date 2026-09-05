# Lessons

What I have learned about my English, grouped by kind. Each entry is a rule with
a made-up example — short enough to reread in full.

## Articles

### A singular countable noun needs an article

Korean has no articles, so they are the easiest thing to drop. Almost every
singular countable noun needs `a`, `an`, `the`, or a possessive in front of it.

- ✗ Send me report before meeting.
- ✓ Send me the report before the meeting.

Use `the` when the listener can identify which one — because it is the only one,
or was already mentioned, or is fixed by the context. Use `a`/`an` when it is one
of several and it does not matter which.

- ✗ Redis is default cache.
- ✓ Redis is the default cache. — the only default there is
- ✗ Pick different font.
- ✓ Pick a different font. — any one will do

Plurals and uncountable nouns are the exception: *Send me the reports* or
*Send me reports* are both fine.

## Verb forms

### Third person singular takes `-s`

The `-s` goes on the verb when the subject is `he`, `she`, `it`, or any single
thing — even when a long phrase separates them.

- ✗ The script run every hour, and the cache expire after a day.
- ✓ The script runs every hour, and the cache expires after a day.
- ✗ The list of failed jobs get longer every day.
- ✓ The list of failed jobs gets longer every day. — the subject is *list*, not *jobs*

### Intransitive verbs have no passive

Some verbs describe something the subject simply does, with nothing done to it.
They cannot take `be` + past participle, however natural the passive feels.

- ✗ The coupon has been expired.
- ✓ The coupon has expired.
- ✗ An error was occurred during the upload.
- ✓ An error occurred during the upload.

The common ones: `expire`, `occur`, `happen`, `arrive`, `appear`, `disappear`,
`remain`, `rise`, `result`, `consist`.

### Noun and verb forms are different words

English often changes the spelling between the noun and the verb, and using the
noun where a verb belongs is a grammar error, not a typo.

- ✗ Please response by Friday.
- ✓ Please respond by Friday. — the noun is *a response*

The pairs worth memorizing: advice / advise, belief / believe, choice / choose,
loss / lose, proof / prove, success / succeed, breath / breathe.

### Some verbs take a person as their object, not a thing

`guide`, `tell`, `inform`, `advise`, `remind`, and `teach` act on a person. What
that person receives goes in a second slot, or in a `that`-clause.

- ✗ I followed all you guided.
- ✓ I followed all your guidance.
- ✓ I did everything you told me to.
- ✗ He informed the deadline.
- ✓ He informed me of the deadline.

## Tense

### The present perfect means it is still true

`has been` describes a state that reaches the present moment. For a state that
has already ended, use the simple past — or the past perfect if you are placing
it before some other past point.

- ✗ The server has been down. I restarted it a minute ago.
- ✓ The server was down. I restarted it a minute ago. — it is up now
- ✓ The server has been down since this morning. — it is still down

`had been` is for a state that ended before another past event: *the server had
been down for an hour before anyone noticed*.

For the same reason the present perfect refuses a definite past time. `yesterday`,
`at three`, `last week`, and the question word `when` all point at a finished
moment, so the verb must be simple past.

- ✗ When has the policy changed?
- ✓ When did the policy change?
- ✗ The build has failed yesterday.
- ✓ The build failed yesterday.
- ✓ The build has failed three times this week. — the week is not over

### `used to` says the habit has stopped

`used to` marks a past habit that is over. Using it for something still true, or
for a single recent inconsistency, says the opposite of what is meant.

- ✗ He used to review my pull requests. — implies he no longer does
- ✓ He always reviews my pull requests. — the habit continues
- ✓ He used to review my pull requests, but now someone else does.

For a habit that is still in force, use the simple present with `always`,
`usually`, or `normally`. To point at one departure from it, name the departure:
*you normally do X — why not this time?*

## Word order and modifiers

### A superlative goes in front of the whole noun phrase

`latest`, `newest`, `best` modify the head noun, so they come before the other
words that describe it — not immediately before the head.

- ✗ Install the Python latest version.
- ✓ Install the latest Python version.
- ✓ Install the latest version of Python. — clearest when the modifiers pile up

### Hyphenate a compound modifier before a noun

Two or more words acting as one adjective are joined with a hyphen when they sit
in front of the noun, so the reader knows they belong together.

- ✗ a logged in session, a two hour delay, a well known author
- ✓ a logged-in session, a two-hour delay, a well-known author

After the noun the hyphen disappears, because there is nothing to disambiguate:
*the session is logged in*, *the author is well known*.

### `again` already contains "this time"

`again` means the thing has happened one more time, so pairing it with `this
time` says the same thing twice. Drop one of them.

- ✗ Why did the build fail this time again?
- ✓ Why did the build fail again?

`this time too` is a different statement — it groups this case with others rather
than counting a repeat — and is worth using only when that grouping is the point:
*the first two builds failed, and this one failed too*.

### Keep an adverb next to the verb it modifies

An adverb pushed to the end of the sentence, past a phrase it has nothing to do
with, attaches itself to whatever it now sits beside. Put it before the trailing
phrase instead.

- ✗ Can the service restart after a crash automatically?
- ✓ Can the service restart automatically after a crash?

The first reads as though the crash is the automatic part. English binds a modifier
to the nearest candidate, so distance from the verb changes the meaning rather than
merely sounding odd.

## Prepositions

### Things are `on` a screen, not `in` it

Use `on` for a surface or a device: *on the screen*, *on a phone*, *on a laptop*,
*on a touch screen*, *on a server*. Use `in` for something enclosing: *in a
browser*, *in an app*, *in the terminal*.

- ✗ Make it work in a touch screen.
- ✓ Make it work on a touch screen.

### Do not chain the same preposition

Repeating `from` (or `of`, or `in`) down a chain makes each one look like it
attaches to the same thing. Use `in` for the containing relationship and keep
`from` for the actual source.

- ✗ Remove the logs from every server from every region.
- ✓ Remove the logs from every server in every region.
- ✗ Read every note from every folder from every account.
- ✓ Read every note in every folder in every account.

### `by` names the doer only in the passive

In an active clause the subject is already the doer, so a trailing `by X` has
nothing left to mark and gets read as "by means of X". When X is the party
giving the order, say so with `at the direction of`, `as instructed by`, or
`under`, or turn the clause passive.

- ✗ The agent deletes old files by the scheduler.
- ✓ Old files are deleted by the scheduler. — passive, so `by` marks the doer
- ✓ The agent deletes old files as instructed by the scheduler. — active, so name the relation

The same applies to a relative clause: *sites that it blocks by the server* has
to become *sites it blocks on the server's orders*.

### An occasion takes `on` or `in`, not `with`

`with` names an instrument or a companion. A run, an attempt, a build, or a
release is an occasion — *when* something happened, not what it happened by means
of — so it takes `on` or `in`.

- ✗ The retry didn't help with the second attempt.
- ✓ The retry didn't help on the second attempt.
- ✗ Caching was still off with last night's build.
- ✓ Caching was still off in last night's build.

`with` returns as soon as the noun really is the means: *fix it with a retry*.

### A platform hosts the work `on`, not `as`

`as` gives a thing a role or a form — *publish it as a PDF*, *ship it as a
plugin*. The service it is hosted on is a place, not a form, so it takes `on`,
or `to` for the act of sending it there.

- ✗ Deploy the docs as Netlify.
- ✓ Deploy the docs to Netlify.
- ✓ Host the docs on Netlify.

Keep `as` for the shape the work takes: *release it as a single-page site*
describes what it is, *release it on Netlify* names where it lives.

### A relative clause keeps the verb's preposition

When the object of a preposition becomes the head of a relative clause, the
preposition does not disappear with it — it stays behind at the end of the
clause. `work on a branch` still needs its `on` in *the branch you worked on*.

- ✗ Show me the branch you were working.
- ✓ Show me the branch you were working on.
- ✗ The library he depends is unmaintained.
- ✓ The library he depends on is unmaintained.

Formal writing may move the preposition to the front instead — *the library on
which he depends* — but it has to appear in one place or the other. Dropping it
leaves the verb looking transitive and the sentence reads as unfinished.

## Sentence patterns

### `Why not` takes a bare verb, not `-ing`

`Why not …?` is a suggestion and is followed by the plain form of the verb.

- ✗ Why not using a cache?
- ✓ Why not use a cache?

To ask for the reason behind something that already happened or is happening,
use a full question instead — the two mean different things:

- ✓ Why aren't you using a cache? — you are not, and I want to know why
- ✓ Why didn't you use a cache? — you did not, and I want to know why

### A passive needs a subject the verb can actually act on

Turning a sentence passive moves the object into the subject slot. Put a noun
there that the verb does not act on and the sentence describes something that
never happens — usually because a different verb is the one that takes that noun.

- ✗ The next chapter shouldn't be advanced until the quiz is passed.
- ✓ The next chapter shouldn't open until the quiz is passed. — the chapter opens
- ✓ You shouldn't move on to the next chapter until you pass the quiz. — you advance

`advance` carries a person through the stages; a stage itself `opens` or
`unlocks`. When a passive feels forced, the fix is usually a different verb
rather than a different arrangement of the same one.

### Negative purpose is not `not to`

To say *in order that something does not happen*, `not to` alone does not work.

- ✗ Save the file not to lose the changes.
- ✓ Save the file so you don't lose the changes.
- ✓ Save the file so as not to lose the changes. — more formal

Bare `not to` is correct only as the object of verbs like `tell`, `ask`, or
`decide`: *I told him not to wait*.

### A shortened time clause borrows the main clause's subject

`after`, `once`, `until`, `before`, `when`, and `while` can drop the subject in
front of a participle — but the missing subject is then whatever the main clause
already has. If that is not what was meant, the sentence quietly attaches the
participle to the wrong thing, and in an imperative that wrong thing is *you*.

- ✗ After finished, send me the summary. — reads as "after you are finished"
- ✓ Once it's finished, send me the summary.
- ✓ After finishing it, send me the summary.

An `-ing` participle behaves the same way, and mismatches there are easier to
miss because the phrase sounds complete on its own:

- ✗ The door stays shut until being unlocked. — nothing names what is unlocked
- ✓ The door stays shut until it is unlocked.

The short form is fine when the subjects genuinely match: *once merged, the branch
can be deleted* works, because the branch is the thing merged.

## Countable and uncountable nouns

### `practice` takes no plural in the "training" sense

`practice` meaning repeated exercise to improve a skill is uncountable, so it
never becomes `practices`.

- ✗ The team needs more practices before the tournament.
- ✓ The team needs more practice before the tournament.

A plural `practices` does exist, but it is effectively a different word meaning
"customary ways of doing things": *safety practices*, *hiring practices*,
*best practices*. Quantify the uncountable sense with a measure word instead —
*two hours of practice*, *a lot of practice*.

### `difficulty` is uncountable when it means "how hard"

In the sense of the level of challenge something presents, `difficulty` takes no
plural. The plural `difficulties` means *troubles, obstacles that were run into*
— a different sense — so pluralizing it changes the request.

- ✗ Compare the two exams and rate their difficulties.
- ✓ Compare the two exams and rate their difficulty.
- ✓ We ran into difficulties migrating the database. — actual troubles

The same split hits `experience` (know-how vs. individual episodes) and `damage`
(harm vs. legal damages).

## Word choice

### An `-ally` adverb says "with respect to X", not "in an X way"

Adverbs built from a noun of quality — `structurally`, `categorically`,
`logically` — name the dimension a claim is limited to. They do not describe the
manner the action should take, so they cannot ask for the quality itself.

- ✗ Please summarize the meeting structurally.
- ✓ Please summarize the meeting in a structured way.
- ✓ Please give the summary a clear structure.

The adverb is right when the point really is to restrict a claim to one
dimension: *the bridge is structurally sound* means sound as far as its structure
goes, and leaves everything else open.

### School years do not translate by number

`1st grade`, `2nd grade` count from the start of elementary school in English, so
a Korean-style "high school 1st grade" lands six years off. Name the stage
instead, or use the continuous US grade number.

- ✗ a problem set for high school 1st grade students
- ✓ a problem set for first-year high school students
- ✓ a problem set for 10th graders

`freshman`, `sophomore`, `junior`, `senior` also work for the four high-school
years, but they are US-specific and are used for university years too.
