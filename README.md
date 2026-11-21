# College Portal — MITS AMS, rebuilt better

A complete college portal that replaces the MITS Gwalior AMS
(academic management system) — built as a single self-contained
static site with zero external dependencies.

## What it is

- **Student portal** — dashboard with live attendance, exam countdown
  and low-attendance alerts; all 10 courses with monthly attendance
  calendars, session tables, marks vs class average, materials,
  lecture plan, class schedule, quizzes and a working AI Notes
  Notebook; bunk predictor; timed auto-graded quizzes with answer
  review and a quiz creator; weekly timetable; assignments tracker;
  study planner; CGPA calculator; mentoring with meeting log;
  downloads; academic calendar; campus events; schemes & syllabus
  library; forms; notices with expiry and unread tracking;
  Campus Pulse articles; digital ID card; global search; light/dark
  themes.
- **Faculty console** — mark attendance per session, create and
  publish quizzes, post notices, add course materials, publish
  results. Everything faculty enter shows up in the student view
  immediately.
- **Sign-in front door** — AMS-style login with institute-email
  routing (`@mitsgwl.ac.in` students / `@mitsgwalior.in` faculty)
  and one-tap demo accounts.

Everything a user adds is saved in their own browser, and a reset
restores the original snapshot.

## Run it

Just open `index.html` in a browser — no build step, no server.

## Deploy

- **Vercel:** import this repo at vercel.com/new — it deploys as a
  static site, no configuration needed.
- **GitHub Pages:** Settings → Pages → deploy from the `main` branch.

## Data

Seeded with a real snapshot of the MITS AMS (student profile,
courses, attendance, quizzes, notices) as the demo account.
Demo Campus Pulse stories are labelled "Demo story".
