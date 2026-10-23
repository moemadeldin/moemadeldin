# Mohamed Emad Eldin

Backend developer focused on Laravel, building multi-tenant SaaS, real-time systems, and AI-integrated APIs. Open source contributor.

---

## Open Source

**[spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary)** (51M+ installs · 6.1k ★)
- Fixed a URL encoding bug affecting filenames with special characters, [PR #3930](https://github.com/spatie/laravel-medialibrary/pull/3930)
- Fixed the resulting S3 double-encoding regression by detecting the disk driver at runtime, [PR #3934](https://github.com/spatie/laravel-medialibrary/pull/3934)
- Fixed a case-sensitivity bug that silently re-encoded images with uppercase file extensions as JPEG, [PR #3964](https://github.com/spatie/laravel-medialibrary/pull/3964)

**[rap2hpoutre/fast-excel](https://github.com/rap2hpoutre/fast-excel)** (29M+ installs · 2.4k ★)
- Added right-to-left sheet export support via OpenSpout's SheetView, with multi-sheet support, [PR #421](https://github.com/rap2hpoutre/fast-excel/pull/421), shipped in v5.15.0
- Fixed a fatal export crash when callbacks returned null or false to skip a row, plus empty generator rows, with PHPUnit tests, [PR #424](https://github.com/rap2hpoutre/fast-excel/pull/424)
- Fixed `limitRows()` being silently ignored on export, which wrote full datasets despite row limits, [PR #426](https://github.com/rap2hpoutre/fast-excel/pull/426)

---

## Projects

### [AI Code Review SaaS](https://github.com/moemadeldin/reviewiq)
Multi-tenant GitHub App that runs AI code review on pull requests. The webhook pipeline validates HMAC signatures, deduplicates by delivery ID, extracts PR diffs, builds prompts, and posts reviews as GitHub comments using GitHub App JWT auth.

`DiffLineMapper` validates every flagged issue against the parsed diff, so hallucinated line numbers never reach a PR. Reviews stream live via **Laravel Reverb + Echo** to a React and TypeScript frontend, with GitHub OAuth2 sign-in.

`Laravel` `React` `TypeScript` `PostgreSQL` `Redis` `Reverb` `OpenRouter API` `Inertia.js` `Tailwind CSS` `Docker` `AWS EC2` `Pest`

### [Job Matching Engine](https://github.com/moemadeldin/ApplyAI)
Resume-to-job compatibility scoring via Gemini, with auto-generated interview questions for candidates scoring above 70%, processed async via Laravel queues.

Google OAuth2 sign-in, Cloudflare Turnstile and rate limiting on public endpoints, Redis caching to cut repeat AI calls, PDF parsing, and 12+ REST endpoints with FormRequest validation. **130+ Pest tests**, Dockerized and deployed to AWS EC2 via GitHub Actions.

`Laravel` `React` `TypeScript` `PostgreSQL` `Redis` `Gemini API` `Sanctum` `Docker` `AWS EC2` `GitHub Actions` `Pest`

### [Real-time Monitoring](https://github.com/moemadeldin/heartbeat-lab)
Health check system tracking HTTP status and response times across **1,000+ daily pings**. Results are stored in PostgreSQL with Redis for history tracking, real-time failure alerts via Reverb, and a Filament admin panel with RBAC.

`Laravel` `Livewire` `PostgreSQL` `Redis` `Reverb` `Filament` `Alpine.js`

---

## Stack

**Languages:** PHP, TypeScript, JavaScript, Python
**Backend:** Laravel, REST APIs, Laravel Reverb, Queues, Sanctum, OAuth2, JWT
**Databases:** PostgreSQL, MySQL, Redis
**Frontend:** React, Vue.js, Inertia.js, Livewire, Alpine.js, Tailwind CSS
**DevOps:** Docker, GitHub Actions, AWS EC2, AWS S3
**Testing:** Pest, PHPUnit
**Integrations:** GitHub API, Gemini, OpenRouter, Laravel Echo, OpenCV

---

## Contact

[LinkedIn](https://linkedin.com/in/moemadeldin) · [Email](mailto:moemadeldin.dev@gmail.com)
