<div align="center">

# Hi, I'm Jayesh Kalkate 👋

### Python · Django · PostgreSQL · REST APIs

**Backend Developer & Full Stack Developer (Fresher) · B.Tech Computer Engineering, 2026 · Maharashtra, India**

I build, test and deploy database-driven web applications, from the data model to payments, security and CI.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-5b8cff?style=for-the-badge&logo=netlify&logoColor=white)](https://devjayesh-portfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayesh-kalkate-31a250242/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kalkatejayesh@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-PDF-2dd4bf?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://devjayesh-portfolio.netlify.app/assets/docs/Jayesh_Kalkate_Resume.pdf)

**Open to:** Python Developer · Django Developer · Backend Developer · Full Stack Developer · Junior DevOps / Cloud · Junior .NET

</div>

---

## About

I'm a 2026 B.Tech Computer Engineering graduate who has built and deployed several web applications with **Python, Django and PostgreSQL**. I like owning a feature end to end: requirements, data model, implementation, tests and deployment.

**At a glance**

- 🧪 **193 automated tests** across four projects: KhataLink (77), LokSetu (73), Lavkush Furniture (29), Matoshree (14)
- 💳 Payments: Razorpay checkout, signature verification, HMAC-validated webhooks
- 🔐 Security: email OTP, role-based access control, rate limiting, audit logging, Fernet encryption
- 🤖 AI integration: Google Gemini for document extraction and natural-language search
- 🚀 Delivery: GitHub Actions CI, Docker, Render

**How I work with AI tools:** I use ChatGPT, Claude and DeepSeek for debugging and exploring approaches. I define the requirements, review the generated code, run and test the application, and take responsibility for the final result.

---

## Featured Projects

> Live demos on Render's free tier may take a short while to wake up after inactivity.

### 1. KhataLink: Multi-Shop Digital Khata Network
**Django · PostgreSQL (Neon) · Redis · Cloudinary · ReportLab**
A consent-based digital ledger linking shops and customers so customers can track dues across shops.
- Multi-tenant data model with shop-level query scoping
- Append-only ledger (void/correct instead of delete) with audit logging and idempotency keys
- Email OTP login with per-account and per-IP throttling; roles for customers, owners, managers, cashiers and admins
- Dispute threads, UPI payment links, due-date reminders, expiring share links, PDF statements
- 77 automated tests

[Live Demo](https://khatalink.onrender.com) · [Code](https://github.com/Jayeshkalkate/KhataLink)

### 2. Ask Me: AI Document Assistant
**Django · PostgreSQL · Google Gemini · PWA · IndexedDB · Fernet**
Extracts structured data from identity-document images and PDFs and answers questions grounded in the user's own documents.
- Gemini Vision with schema-constrained extraction (Aadhaar, PAN, passport, driving licence)
- Fuzzy field matching and a document-grounded chatbot
- Extracted data encrypted at rest with Fernet; expiring share links; expiry reminders
- Installable, offline-capable PWA (service worker + IndexedDB)

[Live Demo](https://ask-me-smart-document-assistant.onrender.com) · [Code](https://github.com/Jayeshkalkate/ask_me)

### 3. Lavkush Furniture: E-Commerce Platform
**Django · PostgreSQL · Razorpay · Cloudinary · ReportLab · Docker**
- Search and filters, guest-cart merge on login, wishlists, order history, returns, PDF receipts
- Server-side Razorpay order creation, payment-signature verification and an HMAC-validated webhook
- Row-level locks for inventory updates; automatic refunds on stock-related payment failures
- Validated bulk CSV/XLSX product import
- 29 automated tests and GitHub Actions CI

[Live Demo](https://lavkushfurniture.onrender.com) · [Code](https://github.com/Jayeshkalkate/Lavkush_Furniture)

### 4. LokSetu: Civic Complaint Management
**Django · PostgreSQL · GitHub Actions**
- Complaint submission with evidence uploads and tracking IDs
- Automatic department routing and role-scoped dashboards
- Request throttling and audit entries
- 73 automated tests; CI pipeline with deployment and migration checks

[Live Demo](https://lok-setu.onrender.com) · [Code](https://github.com/Jayeshkalkate/loksetu)

### 5. Matoshree: CSC / Government Services Portal
**Django · PostgreSQL · Razorpay · BeautifulSoup · Cloudinary · ReportLab**
- Service applications with document uploads and verification states
- Appointment booking with double-booking prevention
- Manual UPI/cash verification, optional Razorpay checkout, PDF receipts
- Job and government-scheme scraper with retry logic and caching; aggregate-query admin dashboard
- 14 automated tests

[Live Demo](https://matoshree-cyber.onrender.com) · [Code](https://github.com/Jayeshkalkate/Matoshree-Cyber)

### 6. MoviesHub: Movie, TV and Anime Discovery
**Django · PostgreSQL · Redis · Google Gemini · Telegram Bot API**
- Combines TMDB, TVMaze, Jikan and AniList metadata
- Gemini-assisted natural-language search and recommendations
- Auto-linking to group titles into cinematic universes and watch orders
- Redis caching to cut repeated external API calls; Telegram bot via webhooks with a Telethon backfill command
- *Note: AWS S3 storage is integrated but currently disabled in the live deployment.*

[Live Demo](https://movies-hub-6dhp.onrender.com) · [Code](https://github.com/Jayeshkalkate/Movies-Hub)

### More Projects

| Project | What it is | Stack | Links |
|---|---|---|---|
| **SceneSeek** | Tries to identify a movie, series or anime from a screenshot or short clip. Built while learning .NET. | ASP.NET Core, Python worker (OCR, frame extraction), Next.js, PostgreSQL, Docker, GitHub Actions | [Demo](https://sceneseek-web.onrender.com) · [Code](https://github.com/Jayeshkalkate/SceneSeek) |
| **VIndia** | Vehicle discovery site: 350+ models, 42+ brands, live search, cascading filters, side-by-side comparison | HTML, CSS, Bootstrap 5, JavaScript | [Demo](https://vehicles-of-india-vindia.netlify.app/) · [Code](https://github.com/Jayeshkalkate/VIndia) |
| **NumTrick** | Browser number-guessing game | HTML, CSS, JavaScript | [Demo](https://numtrick.netlify.app/) |

---

## Technical Skills

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,django,postgres,sqlite,redis,js,html,css,bootstrap,docker,git,github,githubactions,linux,cs,dotnet&perline=8" alt="Python, Django, PostgreSQL, SQLite, Redis, JavaScript, HTML, CSS, Bootstrap, Docker, Git, GitHub, GitHub Actions, Linux, C#, .NET" />
</p>

| Area | Technologies |
|---|---|
| **Languages** | Python, JavaScript, SQL; learning C# |
| **Backend** | Django, Django ORM, migrations, management commands, REST API integration, webhooks |
| **Data** | PostgreSQL (Neon), SQLite, Redis (Upstash), schema design, query optimization |
| **Security** | Email OTP, RBAC, rate limiting, CSRF protection, input validation, audit logging, Fernet, HMAC |
| **Frontend** | HTML5, CSS3, Bootstrap 5, JavaScript, PWA |
| **Integrations** | Razorpay, Google Gemini, Telegram Bot API, TMDB, TVMaze, Jikan, AniList, Cloudinary, Brevo |
| **Testing & CI** | Django test framework, Git, GitHub, GitHub Actions |
| **Deployment** | Render, Netlify, Gunicorn, WhiteNoise, Docker, Linux |
| **Training / exposure** | Jenkins, Ansible, Bash, AWS fundamentals, ASP.NET Core basics |

---

## Experience

**Python Programming Intern, Prasunet** · Remote · Mar 2025 – Apr 2025
Python scripting, file handling, functions and modular programming.

**Full Stack Developer Intern, Vaishnav Technologies** · Remote · Feb 2025 – Mar 2025
Built web apps with Django, HTML, CSS, JavaScript and Bootstrap; managed media with Cloudinary; deployed on Render using Git/GitHub workflows.

**Data Entry Intern, Rural Field Survey Program** · May 2022 – Jun 2022
Survey data collection and validation; organised data in Microsoft Excel.

## Education

**B.Tech, Computer Engineering** · Godavari College of Engineering, Jalgaon (DBATU)
2022 – 2026 · CGPA 7.2 / 10

## Certifications & Training

- **Red Hat:** RH124 (System Administration I), RH104 (Linux Fundamentals), DO101 (Intro to OpenShift Applications)
- **Simplilearn SkillUp:** Python 3.x, SQL for Data Analysis, Web Scraping with BeautifulSoup
- **NSDC / Skill India:** Web Design and Development
- **IIT Bombay Spoken Tutorial:** Python, Java
- **DevOps Bootcamp:** Jenkins, Docker, Linux, AWS, Ansible, Bash
- **Smart India Hackathon 2024**; six-day Python programming workshop

[View certificates](https://drive.google.com/drive/folders/1Iwxvmfb4jzhRlW1Vq3ToGJekdggKDhWM?usp=drive_link)

## Leadership

- Team lead and developer on two academic projects
- Took part in two college-level hackathons; selected for the next round of the Avishkar Research Competition (team)

---

## Currently

- Deepening Django, PostgreSQL, query performance and application security
- Growing my Docker, CI/CD and cloud fundamentals
- Learning C# and ASP.NET Core through a cross-stack project

I'm looking for a **Python / Django / Backend / Full Stack** role where I can contribute to a team and learn from experienced engineers.

---

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Jayeshkalkate&show_icons=true&theme=tokyonight&hide_border=true" alt="Jayesh's GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jayeshkalkate&layout=compact&theme=tokyonight&hide_border=true" alt="Most-used languages" />
</p>

<div align="center">

**Let's connect:** [Portfolio](https://devjayesh-portfolio.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/jayesh-kalkate-31a250242/) · [kalkatejayesh@gmail.com](mailto:kalkatejayesh@gmail.com)

*Building, learning and improving, one project at a time.*

</div>
