---
portfolio: v1
project: "ai-psychology-syllabus"
group: lecture
source_of_truth: "index.html"
status: distributed
one_line: "The syllabus for Elad's elective course 605009, 'Using Artificial Intelligence in Psychology: Research and Clinical Applications' (BIU Psychology, semester B of academic year 2026/27, Mondays 14:00-16:00) - one self-contained HTML page on GitHub Pages, and AS OF 2026-09-15 IT HAS GONE OUT TO THE STUDENTS."
next_action: "Nothing. The document is distributed. Any future edit is an edit to something students have already received - see 'Editing rules now that it is distributed' below."
waiting_on: []
deadline: null
last_updated: 2026-09-15
live_signals:
  - {type: "url", check: "https://elad-refoua.github.io/ai-psychology-syllabus/"}
  - {type: "file", path: "C:\\Users\\user\\Desktop\\ai-psychology-syllabus\\index.html"}
---

# AI in Psychology - course syllabus site - PROJECT_TIMELINE

## Where this stands right now (2026-09-15)

| | |
|---|---|
| Live page | https://elad-refoua.github.io/ai-psychology-syllabus/ - HTTP 200, 72,764 bytes |
| Repository | https://github.com/elad-refoua/ai-psychology-syllabus.git, branch `main`, HEAD `e0324aa` |
| Working copy | `C:\Users\user\Desktop\ai-psychology-syllabus\` - `index.html`, `README.md`, `.nojekyll`, this file |
| Sync | Clean. 0 unpushed, 0 unpulled, local HEAD == `origin/main`, and `index.html` on disk is byte-identical to what GitHub Pages serves (SHA-256 `ffa84ce43f53197c7b5b7ea4b399325c82baaff24dc45105afa485abb0338f45` on both) |
| Course | **605009** - "שימוש בבינה מלאכותית בפסיכולוגיה: יישומים מחקריים וקליניים" / *Using Artificial Intelligence in Psychology: Research and Clinical Applications* |
| Slot | סמסטר ב׳ תשפ״ז · יום שני 14:00-16:00 · 2 נ״ז · המחלקה לפסיכולוגיה · taught in Hebrew |
| Audience | Undergraduate and graduate, elective, no prerequisites |
| Shape | 13 sessions in three parts, every session with a hands-on exercise |
| Assessment | Product-based, **no exam** (מבוסס־תוצרים · ללא מבחן) |
| Built with | Quark (Elad's own tooling), 2026-09-15 |
| Bibliography | 11 items, no placeholders. Session 2's reading was filled on 2026-09-15 (Shanahan 2024) and four Torous papers added; every citation from Crossref, every open-access badge from Unpaywall |
| Open | One thing: the identity of the Quark artifact against this repository was reported and not independently checked. (Separately, four links are unverifiable by an automated checker because the publishers block bots - they are not broken; see the verification section) |

**The number and the slot agree with the department.** Dubi Moskovitch confirmed on 2026-08-09
that the course is 60-5009-01, semester B, Mondays 14:00-16:00. The page carries the same course
as **605009** - the same number written without the department prefix and the section suffix.
These are one course and one row, not two.

**The three frameworks are the course's shared language.** Each has its own page on the companion
site and each is linked to its paper.
1. **״לחשוב עם מכונה״ (Thinking With a Machine)** - the spine. Its core principle is that every
   prompt carries three things: קונטקסט, מגבלות, יעד (context, constraints, goal). It also brings
   ten prompt-engineering principles and a six-step decision framework.
2. **SMART** - five graduated levels of responsible AI integration in therapy: S Supporting,
   M Mentoring, A Assisting, R Reflecting, T Transforming. The higher the level, the more is
   delegated to the machine, and the more responsibility falls on the therapist.
3. **CARE** - the bounds of AI emotional capability: C Capturing, A Arranging, R Resonating,
   E Embodied.

**The CARE framework is Elad's own published work.** The bibliography's SAGE DOI
`10.1177/15248380261425937` resolves in Crossref to "Algorithmic Witnessing: A Narrative Review
and the AI CARE Framework for Trauma Testimony", *Trauma, Violence & Abuse*, 2026, by Hadar
Shoval, Haber, Refoua, Elyoseph and Yirmiya. The course teaches a framework from a paper he
co-authored.

---

## What it is

A single self-contained `index.html`. No build step, no dependencies, no framework. `.nojekyll`
stops GitHub Pages from running the folder through Jekyll. A separate print stylesheet turns the
page into a formal syllabus document when printed or saved as PDF. Dark mode and phone layouts
are supported.

Content is edited directly in the HTML. A session is an `<article class="session">`; a
bibliography item is an `<li class="ref">` inside an `<ol class="refs">`. This is written in
`README.md` too, and it is the whole editing model - there is no content source behind the HTML.

### The 13 sessions, in three parts

| Part | Sessions | Theme |
|---|---|---|
| 1 | 1-4 | יסודות ותשתית חשיבה - foundations and thinking infrastructure |
| 2 | 5-8 | AI במחקר פסיכולוגי - AI in psychological research |
| 3 | 9-12 | AI בקליניקה - AI in the clinic |
| - | 13 | פרויקטים מסכמים - final projects |

The page states its own character plainly: this is a hands-on, applied course
(חוויתי־יישומי), not a theoretical course about technology. Learning outcomes are split into
three groups - A ידע (knowledge), B מיומנויות (skills), C תפיסות וערכים (attitudes and values).

### Companion site

`thinking-with-machine.base44.app`, with pages: SmartModel, CareModel, Decision, Principles,
Glossary, PracticalUses, ResearchProcess, Tools, Workshop, ThinkingWithMachine. The syllabus
links into it rather than repeating it.

---

## Source of truth and derived surfaces

`index.html` in this repository is the source of truth. There is exactly one derived surface: the
live GitHub Pages site, which is a straight copy of the file. There is no generator and no build,
so "the source is live" is verified by comparing the two byte for byte, which is what the SHA-256
line in the state table above is.

---

## Chronological record

**2026-08-09 - the course gets a number and a slot.** Dubi Moskovitch confirms 60-5009-01,
semester B, Mondays 14:00-16:00. Recorded in the second-brain vault (`areas/teaching-lectures.md`)
and, on 2026-09-07, as item 99 of the task map.

**2026-09-07 - the vault records that no syllabus work exists.** Map item 99
(`second-brain/briefs/map_2026-09-07/merged.json`) carries the sentence "נרשם כי בשום מקום לא
מופיעה התחלה של סילבוס או תכנון" - nowhere does a start of a syllabus or a plan appear. That was
an accurate statement about the records at the time.

**2026-09-15 - the syllabus is built, and published.** Elad builds it with Quark. Seven commits
between 12:02 and 12:45 Israel time (09:02-09:45 UTC in the git log) take the page from creation
to its current state:

| Commit | What it did |
|---|---|
| `d6d2cbe` | Add course syllabus page |
| `d47ec77` | Remove MENTI and publications-tracking links |
| `e8bd310` | Drop external tool links throughout |
| `f03e88c` | Add course number, confirm credits, fix empty grid cell |
| `8aee209` | Add meeting slot and location to the syllabus header |
| `ff91332` | Link the SMART preprint alongside the model page |
| `e0324aa` | Link the CLPsych paper for Thinking With a Machine |

**2026-09-15, later - the second brain finds out it exists.** Asked that morning where the
syllabus stood, it answered that there was none and that nothing had been started. Elad sent the
link. This file, a lesson in the second brain's own memory, and a vault capture were written the
same day, and map item 99 was closed against the evidence above. The failure and what it teaches
are recorded in
`C:\Users\user\.claude\agent-memory\second-brain\lesson_2026-09-15_the-syllabus-existed-and-i-said-it-did-not.md`.

**2026-09-15, later still - the bibliography's one placeholder is filled, and four Torous papers
join it.** Item 07 was not a source: it was a note saying an introductory source on how language
models work and where their limits are was still missing, with the "Thinking with a Machine"
glossary standing in for session 2 - the one session whose entire subject is how the thing works.
It became **Shanahan (2024), Talking about large language models**, *Communications of the ACM*
67(2), 68-79, open access. Elad then asked for recent work by John Torous, and the honest finding
was that **Torous does not write about model mechanics** - 63 Crossref records, and his subject is
clinical evaluation, safety and research priorities. The four added on his instruction are
Flathers et al. (2026) in *Psychotherapy and Psychosomatics*, a primer for mental health
professionals on benchmarking; Galatzer-Levy et al. (2026) in *World Psychiatry* 25(2);
Birk et al. (2026) in *JMIR Mental Health* 13; and Kleinman, Torous & Danilewitz (2026) in
*Annals of Internal Medicine* 179(4). Every citation was taken from Crossref rather than typed
from memory, and each item's open-access status was checked against Unpaywall per DOI rather than
assumed: the first three are open, the *Annals* piece is not and carries a
`גישה דרך הספרייה` badge instead of a false open-access label. Session 2 gained the paper chip it
never had. The footer sentence promising that items marked `להשלמה` would be updated before the
semester was removed, because no item is marked that way any more and it would have sent a reader
looking for a marker that is not there. Commit `0773478`, pushed; the served page is byte-identical
to the working copy (`af5a234f...951c0d`), 11 bibliography items, zero pending badges, no console
errors, no horizontal overflow at phone width.

**2026-09-15 - the syllabus goes out to the students.** Elad: *"הסילבוס עבר לסטודנטים"*. That
changes what this repository is. Until now it was a page being built; from here it is a document a
cohort has received, and the project's status field says `distributed` rather than `active`.

---

## Editing rules now that it is distributed

These are consequences of the line above, not preferences.

1. **The URL is the deliverable and must not move.** Students hold
   `https://elad-refoua.github.io/ai-psychology-syllabus/`. Do not rename the repository, do not
   change the Pages source, do not move the folder (see the note below about `Desktop\projects\` -
   that tidying is now off the table), and do not delete `.nojekyll`.
2. **An edit now is an edit to something people have already read.** Correcting an error is right;
   silently restructuring sessions, renumbering the bibliography, or changing dates and the meeting
   slot is not, because a reader who printed the page will not see it and will not know to look.
   Anything that changes what a student must DO is Elad's call and needs telling them, not just
   editing.
3. **ANSWERED 2026-09-15 - they hold the LINK.** Elad: *"קישור שלחתי אל תדאג"*. So today's
   bibliography completion reached them the moment it was pushed; nobody is holding a snapshot with
   the `להשלמה` placeholder, and no re-distribution is owed. **Do not re-raise this.**
   But it cuts the other way too, and that is the part worth keeping: **because they hold a link,
   anything edited here changes what students see, silently and immediately.** There is no
   publication step left to act as a checkpoint. That makes rule 2 stricter rather than looser - a
   change to a reading, a date, or an assignment is a change to a live document a cohort is working
   from, and it needs Elad's word and theirs, not just a commit.
4. **Session 2's reading changed today.** Item 07 stopped being a placeholder and became Shanahan
   (2024); four Torous papers were added as 08-11. Anyone reconciling a student's copy against the
   live page should expect exactly that difference and no other.

---

## Verification performed on 2026-09-15

**Sync, measured three ways, and one false alarm worth keeping.** The first reading of
`git rev-list --count @{u}..HEAD` reported **6 unpushed commits**. That was wrong: the
remote-tracking reference was stale. After `git fetch origin` the same command reported 0
unpushed and 0 unpulled, and `git rev-parse HEAD origin/main` returned the same hash twice. The
third check is the byte comparison of the local file against the served page. A sync claim from a
repository that has not fetched is a claim about local memory, not about the remote.

**Link check - 26 external links, all healthy.** Four looked like failures and none is:

- `fonts.googleapis.com` and `fonts.gstatic.com` return 404 as bare hosts because they are
  `preconnect` hints, not links. Nothing is broken.
- `unesdoc.unesco.org` returns HTTP 403 to a bot. The same UNESCO guidance is served at
  `https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research` (HTTP 200).
- The SAGE DOI `10.1177/15248380261425937` returns HTTP 403 to a bot and resolves correctly in
  Crossref, the registry itself.

**A method note for whoever runs the next link check.** The first run reported 26 of 26 links
broken. Both causes were in the checker, not in the page: `curl` inside a `while read` loop
consumes the loop's standard input, and the URL list had been written on Windows with CRLF line
endings, so every URL carried a trailing carriage return and was invalid. When a checker reports
mass failure, check the checker first.

---

## Open items

**1. The Quark artifact version 7 was reported identical to this repository, and that was not
independently checked.** Elad relayed Quark's own statement. It is recorded here as his report of
another tool's claim, attributed, and it is not evidence. If it matters later, the check is to
open the artifact and diff it against `index.html`.

**2. Two bibliography links will fail any future automated link check** - the UNESCO document and
the SAGE DOI - because those two publishers block bots, not because the links are bad. Anyone
adding a link-check gate here should encode that, or the gate will cry wolf on every run. Both
were verified reachable by other routes on 2026-09-15 (see above).

**3. This project sits at `C:\Users\user\Desktop\`, not under `C:\Users\user\Desktop\projects\`.**
The second brain's portfolio index scans `Desktop\projects` and the Dropbox dissertation tree, so
a project in the Desktop root is invisible to it no matter how good its timeline is. On 2026-09-15
this path was added to the generator's `FIXED_DOCS` list
(`second-brain/tools/build_portfolio_index.py`), the same fix used for the SMART and AI-TOM
workspaces on 2026-09-07. Moving the folder under `Desktop\projects\` would be the tidier fix and
is Elad's call, not a machine's.

---

## Where the evidence lives

- The page itself: `index.html` in this folder, and the live URL above.
- How to edit it: `README.md` in this folder.
- Second-brain capture: `C:\Users\user\Desktop\projects\second-brain\inbox\2026-09.md`, entry
  dated 2026-09-15.
- Second-brain project page:
  `C:\Users\user\Desktop\projects\second-brain\projects\ai-psychology-syllabus.md`.
- The closed map item: `second-brain/briefs/map_2026-09-07/merged.json`, item 99, now in
  `closed_items` with its closing evidence.
