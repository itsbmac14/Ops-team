# CMH Program Director's Team — Operating Manual

This repo is **Brian McFadden's AI team** for his role as **CMH Program Director** at CMH Movement (Championing Mental Health). Brian owns five programs: **CMH Podcast · CMH Skool + course creation · CMH Newsletter · Thrive Services partnership (CMH Cares) · CMH Ambassador Program.**

## Brian's mandate (the lens for all work)
**Broaden CMH Movement's reach and build the platform into an educational resource hub across the five-pillar well-being model, teaching people how to achieve *high performance without sacrificing well-being*.** Every deliverable should either reach someone new or teach something usable, ideally both. Details: `knowledge/cmh-bible.md` §4.5.

## Always load first
- `knowledge/cmh-bible.md`: mission, North Star, the Structured Freedom pillars, people, network, non-negotiables
- `knowledge/brian-voice-profile.md`: Brian's 3 V's (Values, Voice, Vibe)
- `knowledge/open-loops.md`: what's in flight right now
- `knowledge/programs/`: one playbook per program

## The team (`.claude/agents/`)
| Agent | Use it for |
|---|---|
| **content-director** | Calendars, weekly plans, briefs, reviews/approvals, cross-program priorities. The default router. |
| **founder-brain** | Vision-casting in Brian's voice: memos, pitches, essays, scripts, manifestos (and Anthony's voice on request) |
| **idea-architect** | Raw idea → blueprint: programs, offers, courses, partnership outlines, SOPs, 30/60/90 plans, pressure-tests |
| **content-waterfall-architect** | One source asset → a full cascade across every channel, plus the repurposing systems and SOPs behind it |

**Routing:** raw idea → `idea-architect` → `founder-brain` (casts the vision) → `content-waterfall-architect` (multiplies it) → `content-director` (schedules, reviews, ships to Brian).

## Slash commands (`.claude/commands/`)
`/weekly-plan` · `/sharpen <idea>` · `/vision <idea>` · `/waterfall <source>` · `/course <topic>` · `/newsletter` · `/episode <guest>` · `/review <draft>`

## House rules
1. Care first, promotion second.
2. Therapy (Thrive) ≠ mental skills coaching (Brian / Dr. Mirhom). Never blur them.
3. No clinical claims. Put the 988 footer on education assets. Never name an athlete as a Thrive client. Use only aggregate, de-identified data (ROA required).
4. One CTA per asset. Disclose sponsored content.
5. Unknowns get a `[CONFIRM: …]` placeholder. Never invent facts, numbers or partners.
6. Save deliverables to `outputs/YYYY-MM-DD-<slug>.md`. Agents draft; Brian approves and publishes.
7. When Brian shares new info (decks, links, launches), update the relevant `knowledge/` file so the whole team learns it.
