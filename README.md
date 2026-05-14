# Mohamed Emad Eldin
Backend developer focused on Laravel — building multi-tenant SaaS, 
real-time systems, and AI-integrated APIs.

---

## Open Source
**[spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary)** (6.1k ★)
- Fixed URL encoding bug affecting filenames with special characters — PR #3930
- Fixed S3 double-encoding regression by detecting disk driver at runtime — PR #3934

---

## Projects

### [AI Code Review SaaS](https://github.com/moemadeldin/reviewiq)
Multi-tenant platform where teams connect GitHub repos and receive 
AI-generated PR reviews.
Webhook pipeline validates HMAC signatures → extracts PR diffs → 
builds prompts → posts reviews as GitHub comments.
Reviews stream in real-time via **Laravel Reverb + Echo**, rendered 
step-by-step on the React frontend.
`Laravel` `React` `PostgreSQL` `Redis` `Reverb` `Groq API` `Inertia.js` `Pest`

### [Job Matching Engine](https://github.com/moemadeldin/jobpilot)
Resume-to-job compatibility scoring via Groq AI (llama-3.3-70b), 
with auto-generated interview questions for candidates scoring above 
70% — processed async via Laravel Queues.
PDF parsing, 12+ REST endpoints with FormRequest validation, 
**130+ Pest tests at 100% coverage**.
`Laravel` `React` `MySQL` `Groq API` `Sanctum` `Pest`

### [Real-time Monitoring](https://github.com/moemadeldin/heartbeat-lab)
Health check system tracking HTTP status and response times across 
**1,000+ daily pings**.
Results stored in PostgreSQL with Redis for history tracking, 
real-time failure alerts via Reverb, and a Filament admin panel with RBAC.
`Laravel` `Livewire` `PostgreSQL` `Redis` `Reverb` `Filament` `Alpine.js`

---

## Stack
**Primary:** PHP, Laravel, PostgreSQL, Redis, MySQL
**Frontend:** React, Vue.js, Inertia.js, Livewire, Alpine.js, Tailwind CSS
**Tooling:** Laravel Reverb, Queues, Horizon, Sanctum, Filament, Pest
**Integrations:** GitHub API, Groq, Stripe, DomPDF, Laravel Echo

---

## Contact
[LinkedIn](https://linkedin.com/in/mohamedemadeldinn) · 
[Email](mailto:mohamedemadeldinnn2@gmail.com)
