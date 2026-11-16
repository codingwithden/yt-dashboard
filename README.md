# YT Dashboard

A dashboard for YouTube and lifestyle creators. Three small tools that each take something messy and hand back something ready to use.

**Status:** clickable prototype and full product blueprint. Open the files in `/docs` in any browser.

## The problem

Creators spend hours on the work around the video: ideas live in notes apps, thumbnails get picked on gut feeling, and footage folders turn into `IMG_4471.mov` chaos. None of that is the creative part, but it eats the time that should go to it.

## The three tools

| Tool | You give it | You get back |
| --- | --- | --- |
| **Idea Organizer** | A messy brain dump | Video cards with a title, hook and format, on a board from Idea to Published |
| **Thumbnail Tester** | 2 to 6 thumbnail options | A score for each, plain reasons why one wins, plus colorblind and small-size previews |
| **File Organizer** | A folder of raw footage | Clean file names and sorted folders, with an undo button |

## Product decisions I made

- **One action per screen.** Every screen has one main button, so a busy creator always knows the next step.
- **Footage never leaves the laptop.** Only small frame samples get analyzed, which keeps it private and keeps costs low.
- **Free previews, paid scoring.** Colorblind and blur views run free in the browser. AI scoring is the paid part, with usage shown next to every paid button so nobody gets surprised by a limit.
- **Priced from real costs.** I estimated the cost of every AI action (about 5 cents per idea dump, 1 cent per thumbnail) before setting the plans: Free, Creator at $25 and Pro at $40.
- **Mobile where it makes sense.** Ideas and thumbnails work on a phone. File sorting is desktop only, and says so.

## What is in this repo

- `docs/prototype.html`: the clickable prototype, with demo data you can reset
- `docs/wireframe.html`: the blueprint with screens, data model, AI flow, plans, build order and risks

## Next

Build the MVP starting with the File Organizer, then test with a small group of creators before opening paid plans.
