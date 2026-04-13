# Mohamed Emad Eldin

Backend developer focused on Laravel — building multi-tenant SaaS, real-time systems, and AI-integrated APIs.  
---

## Stack

**Primary:** PHP, Laravel, PostgreSQL, Redis, MySQL  
**Frontend:** React, Vue.js, Inertia.js, Livewire, Alpine.js, Tailwind CSS  
**Tooling:** Laravel Reverb, Queues, Horizon, Sanctum, Filament, PHPUnit, Pest  
**Integrations:** GitHub API, OpenAI, Groq, Stripe, DomPDF, Laravel Echo  

---

## Projects

### [AI Code Review SaaS](https://github.com/moemadeldin/reviewiq)
Multi-tenant platform where teams connect GitHub repos and receive AI-generated PR reviews.  
Webhook pipeline validates HMAC signatures → extracts PR diffs → builds prompts → posts reviews as GitHub comments.  
Reviews stream in real-time via **Laravel Reverb + Echo**, rendered step-by-step on the React frontend.  
`Laravel` `React` `PostgreSQL` `Redis` `Reverb` `Groq API` `Inertia.js` `Pest`

### [Job Matching Engine](https://github.com/moemadeldin/jobpilot)
Resume-to-job compatibility scoring via Groq AI (llama-3.3-70b), with auto-generated interview questions for candidates scoring above 70% — processed async via Laravel Queues.  
PDF parsing, 12+ REST endpoints with FormRequest validation, **130+ Pest tests at 100% coverage**.  
`Laravel` `React` `MySQL` `Groq API` `Sanctum` `Pest`

### [Real-time Monitoring](https://github.com/moemadeldin/heartbeat-lab)
Health check system tracking HTTP status and response times across **1,000+ daily pings**.  
Results stored in PostgreSQL with Redis for history tracking, real-time failure alerts via Reverb, and a Filament admin panel with RBAC.  
`Laravel` `Livewire` `PostgreSQL` `Redis` `Reverb` `Filament` `Alpine.js`

### [Billing Platform SaaS](https://github.com/moemadeldin/invosync)
Multi-tenant billing system with invoice management, multi-method payment tracking, and a sales return approval workflow.  
Exposes an external provisioning API for syncing invoices from third-party apps via token-based auth.  
`Laravel` `MySQL` `Blade` `Tailwind CSS`

### [MindByte LMS](https://github.com/moemadeldin/mindbyte)
Learning management system with free/paid courses, Stripe integration, shopping cart, and role-based access for admins, teachers, and students.  
Connected to SyncInvoice via a REST API bridge that auto-syncs student payments on enrollment. **60% reduction in courses page load** via query optimization and DTOs.  
`Laravel` `MySQL` `Blade` `Stripe` `Tailwind CSS`

### [Travel Booking Platform](https://github.com/moemadeldin/travel-booking)
Full-stack booking platform with Sanctum auth, OTP verification, and RBAC for three roles.  
Service + repository architecture with DTOs and interfaces for tour search, cart persistence, and order lifecycle.  
Stripe Checkout integration with auto-generated PDF tickets delivered via email.  
`Laravel` `React` `MySQL` `Stripe` `DomPDF` `Tailwind CSS`


## Contact

[LinkedIn](https://linkedin.com/in/mohamedemadeldinn) · [Email](mailto:mohamedemadeldinnn2@gmail.com)
