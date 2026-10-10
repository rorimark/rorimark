### Mark Storchovyi

Frontend developer working in **React, Next.js and TypeScript**. Wrocław, Poland, open to remote.

I build web products end to end: the interface, the data model behind it, the tests, and the release. My most recent work is a booking platform that a studio in Toronto runs on every day.

[Portfolio](https://mark-storchovyi.com) · [LinkedIn](https://linkedin.com/in/mark-storchovyi) · [markstorchovyi@gmail.com](mailto:markstorchovyi@gmail.com)

---

#### iBraid Studio: website, online booking and studio panel

[ibraid-studio.com](https://www.ibraid-studio.com) · [Case study](https://mark-storchovyi.com/#case-study) · client project, code is private

Sole developer on a production system for a braiding studio in Toronto with two stylists, December 2025 to September 2026. About 50 clients a month book through it.

- A 7-step booking flow for 53 services: live price total, address suggestions, only the start times that fit the service, validation with Zod.
- A $30 deposit through Stripe Connect that goes straight to the account of the stylist doing the appointment.
- A studio panel for the day: inbox, weekly calendar, payments, analytics, and prices and hours the studio edits itself.
- Requests confirmed from a Telegram card in one tap, with email and SMS updates sent to clients.
- 28 pages and 73 React components, mobile-first, light and dark themes, keyboard and screen reader support.
- PostgreSQL on Supabase: 26 tables, 42 migrations, row level security and a database constraint against double booking.
- 700+ automated tests running in CI on every push.

`Next.js` `TypeScript` `React` `Tailwind CSS` `PostgreSQL` `Supabase` `Stripe Connect` `Vercel`

#### LioraLang: spaced-repetition flashcards for web and desktop

[liora-lang.vercel.app](https://liora-lang.vercel.app) · [Source](https://github.com/rorimark/LioraLang) · [Desktop releases](https://github.com/rorimark/LioraLang/releases)

One React codebase that runs in the browser as an installable app and on Windows and macOS through Electron.

- Local first: decks and review history live on the device (IndexedDB on the web, SQLite on desktop) and study works without a connection. Signing in syncs devices through Supabase.
- Scheduling on FSRS-5, checked against the reference implementation.
- Cards shaped by subject: languages, programming with code panes, mathematics with rendered formulas, and history.
- Optional AI card suggestions through a Supabase Edge Function with a daily allowance.
- A hub of shared decks, an interface in 12 languages, and 500+ tests with Vitest.

`React` `JavaScript` `Vite` `Electron` `IndexedDB` `SQLite` `Supabase`

#### Portfolio

[mark-storchovyi.com](https://mark-storchovyi.com): case studies in English, Polish, Ukrainian and Russian, built with Next.js and TypeScript.

---

**Stack:** TypeScript, JavaScript, React, Next.js, Tailwind CSS, Vite, Zod, Electron · Node.js, PostgreSQL, Supabase, Stripe · Vitest, React Testing Library, GitHub Actions, Vercel

**Languages:** Ukrainian (native), Russian (C2), Polish (C1), English (B2)
