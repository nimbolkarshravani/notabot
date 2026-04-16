# notabot

A Chrome extension for people who hate Workday.

Fills out job applications automatically, then double-checks its own work
because the ATS parser definitely got your phone number wrong.

**Status:** Building in public. Not functional yet.

---

## The problem

You upload your resume. The form "parses" it. Your name is now spelled
wrong, your phone number has a random country code, your university is
"Univeristy of Mumbai," and you still have to fill 14 more fields
manually. Then you hit "Next" and there's another page. Then another.

Every job application. Every time.

## What notabot does (or will, once it works)

- Fill job application forms on **Workday** and **Greenhouse** from a
  profile you set up once.
- **Verify the form after filling** and fix fields the ATS parser
  messed up. This is the part nobody else does.
- Upload your resume automatically.
- Handle account creation (email + one stored password).
- Auto-advance through multi-step forms, stop before submit so you can
  review.

## What notabot will not do

- Search for jobs.
- Apply to hundreds of jobs in one click. This is a tool for humans
  applying thoughtfully, not a spam cannon.
- Work on anything other than Chrome.
- Send your data anywhere. Everything lives in your browser.

## Planned for v1

- [ ] Profile vault and onboarding
- [ ] Resume upload and storage
- [ ] Greenhouse adapter
- [ ] Workday adapter
- [ ] Verification pass (empty fields + sanity checks)
- [ ] Account creation flow
- [ ] Stop-before-submit overlay

## Install

Not yet. Check back when v1 ships.

## Privacy

Everything stays local in your browser's storage. No backend, no
analytics, no telemetry. The extension has permissions only for the
job sites it supports — not every page you visit.

## License

MIT
