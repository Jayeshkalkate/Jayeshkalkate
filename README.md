<div align="center">

# Hi, I'm Jayesh Kalkate 👋

### Python Backend Developer | Django | PostgreSQL | REST APIs

**Backend Development · Database Design · API Integrations · Application Security · Automated Testing**

B.Tech Computer Engineering Graduate (2026) · DBATU · Maharashtra, India

I build, test and deploy database-driven web applications, with a primary focus on Python and Django.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Website-5b8cff?style=for-the-badge&logo=netlify&logoColor=white)](https://devjayesh-portfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayesh-kalkate-31a250242/)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kalkatejayesh@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-View%20PDF-2dd4bf?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://devjayesh-portfolio.netlify.app/assets/docs/Jayesh_Kalkate_Resume.pdf)

**Open to:** Python Developer · Django Developer · Backend Developer · Junior .NET opportunities

</div>

---

## About Me

I'm a fresher Backend Developer and 2026 B.Tech Computer Engineering graduate with hands-on experience building and deploying web applications using **Python, Django and PostgreSQL**.

My strongest areas are backend development, relational data modelling, authentication and authorization, REST API integrations, payment workflows, application security and automated testing. I enjoy taking a feature from its requirements and data model through implementation, testing and deployment.

**Testing snapshot:** The four project suites listed below report **193 automated tests** across KhataLink (77), Matoshree (14), Lavkush Furniture (29) and LokSetu (73).

### What I Work On

- **Backend engineering:** Django, Django ORM, database-backed workflows and REST API integrations.
- **Databases and performance:** PostgreSQL, SQLite, Redis caching, schema design and query optimization.
- **Security:** Email OTP authentication, role-based access control (RBAC), rate limiting, input validation, audit logging and encryption.
- **Payments:** Razorpay checkout, signature verification, HMAC-validated webhooks and safer inventory updates.
- **AI integrations:** Google Gemini for document understanding and natural-language search.
- **Testing and delivery:** Django automated tests, GitHub Actions CI, Docker and application deployment.

### How I Develop

I use AI-assisted tools such as ChatGPT, Claude and DeepSeek for problem-solving, debugging and exploring implementation approaches. I define requirements, guide the implementation, review generated code, run the application, test its behaviour and take responsibility for the final integration. I use these tools to support engineering work, not as a substitute for understanding and verification.

---

## Featured Projects

The projects below are ordered to highlight my backend, AI-integration and cross-stack work first.

### 1. KhataLink — Multi-Shop Digital Khata Network

**Stack:** Django · PostgreSQL (Neon) · Redis · Cloudinary · ReportLab

A consent-based digital ledger that connects shops and customers, allowing customers to track dues across linked shops.

- Designed a multi-tenant data model with shop-level query scoping for tenant isolation.
- Implemented an append-only ledger: entries are voided or corrected rather than deleted, with audit logging and idempotency keys.
- Built email OTP login with per-account and per-IP throttling.
- Implemented role-based access for customers, shop owners, managers, cashiers, administrators and platform owners.
- Added dispute threads, UPI payment links, due-date reminders, expiring share links and PDF statements.
- Developed **77 automated tests**.

**Links:** [Live Demo](https://khatalink.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/KhataLink)

### 2. Ask Me — AI-Powered Document Assistant

**Stack:** Django · PostgreSQL · Google Gemini API · PWA · IndexedDB · Fernet

An AI document assistant that extracts structured information from identity-document images and PDFs and provides answers grounded in a user's own documents.

- Integrated Gemini Vision for schema-constrained extraction from identity and certificate documents, including Aadhaar, PAN, passport and driving licence documents.
- Added fuzzy field matching and a chatbot grounded in the user's uploaded documents.
- Encrypted extracted data at rest using Fernet.
- Added expiring share links and reminders for documents nearing expiry.
- Built an installable, offline-capable Progressive Web App using a service worker and IndexedDB.

**Links:** [Live Demo](https://ask-me-smart-document-assistant.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/ask_me)

### 3. Matoshree — Government Services and CSC Portal

**Stack:** Django · PostgreSQL · Razorpay · BeautifulSoup · Cloudinary · ReportLab

A Common Service Centre portal for service applications, document handling, verification and appointment booking.

- Built service application workflows with document uploads and verification states.
- Implemented appointment booking with double-booking prevention.
- Added manual UPI/cash payment verification, optional Razorpay checkout and PDF receipts.
- Built a job and government-scheme scraper with retry logic and caching.
- Created an admin dashboard using aggregate queries.
- Developed **14 automated tests**.

**Links:** [Live Demo](https://matoshree-cyber.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/Matoshree-Cyber)

### 4. MoviesHub — Movie, TV and Anime Discovery Platform

**Stack:** Django · PostgreSQL · Redis · Google Gemini · Telegram Bot API · AWS S3 integration

A discovery platform for movies, television series and anime, combining multiple metadata sources with AI-assisted search.

- Integrated TMDB, TVMaze, Jikan and AniList APIs.
- Implemented Gemini-assisted natural-language search and recommendations.
- Built a metadata layer and auto-linking workflow to group titles into cinematic universes and watch orders.
- Used Redis caching to reduce repeated external API requests.
- Integrated a Telegram bot through webhooks, with a Telethon backfill command.

**Deployment note:** The live application is deployed on Render; AWS S3 storage is currently disabled in the deployment.

**Links:** [Live Demo](https://movies-hub-6dhp.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/Movies-Hub)

### 5. SceneSeek — Movie, Series and Anime Finder

**Stack:** ASP.NET Core (C#) · Python · Next.js · PostgreSQL (Neon) · Docker · GitHub Actions

A cross-stack project that attempts to identify movies, series or anime from a screenshot or short clip. I developed it while learning .NET (C#) fundamentals and working across a .NET API, Python processing worker and Next.js frontend.

- Built an ASP.NET Core API and a Python worker for OCR and frame extraction.
- Developed the web interface with Next.js.
- Used AI-assisted development tools while learning the .NET stack; I run, review and test the application myself.
- Set up Docker Compose deployment and a GitHub Actions CI workflow.

**Links:** [Live Demo](https://sceneseek-web.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/SceneSeek)

### 6. Lavkush Furniture — E-Commerce Platform

**Stack:** Django · PostgreSQL · Razorpay · Cloudinary · ReportLab · Docker

A full-stack e-commerce application with shopping, order management, payment processing and inventory workflows.

- Developed product search and filters, guest-cart merging on login, wishlists, order history, returns and PDF receipts.
- Integrated Razorpay with server-side order creation and payment-signature verification.
- Implemented an HMAC-validated payment webhook.
- Used database row locks for inventory updates and handled stock-related payment failures with automatic refunds.
- Added validated bulk CSV/XLSX product imports.
- Developed **29 automated tests** and a GitHub Actions CI workflow.

**Links:** [Live Demo](https://lavkushfurniture.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/Lavkush_Furniture)

### 7. LokSetu — Civic Complaint Management Platform

**Stack:** Django · PostgreSQL · GitHub Actions

A civic complaint platform that helps citizens submit complaints and track their progress.

- Implemented complaint submission with evidence uploads and tracking IDs.
- Added automatic department routing and role-scoped dashboards.
- Included request throttling and audit entries.
- Developed **73 automated tests** and a GitHub Actions pipeline for deployment and migration checks.

**Links:** [Live Demo](https://lok-setu.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/loksetu)

### 8. VIndia — Vehicles of India Discovery Platform

**Stack:** HTML5 · CSS3 · Bootstrap 5 · JavaScript

A responsive vehicle-discovery website featuring:

- **350+ vehicle models** across **42+ brands**.
- Live search and cascading Type → Brand → Model filters.
- Side-by-side vehicle comparison.
- JSON-based vehicle data and a responsive interface.

**Links:** [Live Demo](https://vehicles-of-india-vindia.netlify.app/) · [GitHub Repository](https://github.com/Jayeshkalkate/VIndia)

### 9. NumTrick — Number Guessing Game

**Stack:** HTML · CSS · JavaScript

An interactive browser-based number-guessing game.

**Link:** [Live Demo](https://numtrick.netlify.app/)

> **Hosting note:** Render free-tier applications may take a short time to wake up after periods of inactivity.

---

## Technical Skills

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,django,postgres,sqlite,redis,js,html,css,bootstrap,docker,git,github,githubactions,linux,cs,dotnet&perline=8" alt="Python, Django, PostgreSQL, SQLite, Redis, JavaScript, HTML, CSS, Bootstrap, Docker, Git, GitHub, GitHub Actions, Linux, C sharp and .NET" />
</p>

| Area | Technologies and concepts |
|---|---|
| **Core languages** | Python, JavaScript, SQL |
| **Learning / fundamentals** | C# and ASP.NET Core; Java basics |
| **Backend development** | Django, Django ORM, migrations, management commands, session authentication, REST API integration, webhooks |
| **Databases and caching** | PostgreSQL (Neon), SQLite, Redis (Upstash), schema design, query optimization |
| **Authentication and security** | Email OTP, RBAC, rate limiting, CSRF protection, input validation, audit logging, Fernet encryption, HMAC signature verification |
| **Frontend** | HTML5, CSS3, Bootstrap 5, JavaScript, Progressive Web Apps (PWA) |
| **Integrations** | Razorpay, Google Gemini API, Telegram Bot API, TMDB, TVMaze, Jikan, AniList, Cloudinary, Brevo |
| **Testing and collaboration** | Django Test Framework, automated testing, Git, GitHub, GitHub Actions CI |
| **Deployment and infrastructure** | Render, Netlify, Gunicorn, WhiteNoise, Docker, Linux |
| **Additional tools** | ReportLab, BeautifulSoup |
| **Training / exposure** | Jenkins, Ansible, Bash scripting and AWS fundamentals |

---

## Experience

**Python Programming Intern — Prasunet**  
*Remote · March 2025 – April 2025*

- Worked on Python programming, scripting and file handling.
- Practised functions, modular programming and problem-solving.

**Full Stack Developer Intern — Vaishnav Technologies**  
*Remote · February 2025 – March 2025*

- Developed web applications using Django, HTML, CSS, JavaScript and Bootstrap.
- Worked with Cloudinary for media management.
- Deployed applications on Render and followed Git/GitHub workflows.

**Data Entry Intern — Rural Field Survey Program**  
*May 2022 – June 2022*

- Participated in survey data collection and validation.
- Managed structured information using Microsoft Excel.

---

## Education

**Bachelor of Technology (B.Tech) in Computer Engineering**  
Godavari College of Engineering, Jalgaon · Dr. Babasaheb Ambedkar Technological University (DBATU)  
*2022 – 2026 · CGPA: 7.2/10*

---

## Certifications and Training

- **Red Hat:** RH124 (System Administration I), RH104 (Linux Fundamentals), DO101 (Introduction to OpenShift Applications).
- **Simplilearn SkillUp:** Python 3.x, SQL for Data Analysis, Web Scraping with BeautifulSoup.
- **NSDC / Skill India:** Web Design and Development.
- **IIT Bombay Spoken Tutorial:** Python and Java.
- **DevOps Bootcamp:** Training in Jenkins, Docker, Linux, AWS, Ansible and Bash scripting.
- **Python Programming Workshop:** Six-day workshop.
- **Smart India Hackathon:** 2024.

[View certificates](https://drive.google.com/drive/folders/1Iwxvmfb4jzhRlW1Vq3ToGJekdggKDhWM?usp=drive_link)

---

## Leadership and Activities

- Served as team lead and developer on two academic projects, coordinating the team and handling implementation.
- Participated in two college-level hackathons and was selected for the next round of the Avishkar Research Competition as part of a team.

---

## Current Focus

- Deepening my Python, Django and PostgreSQL skills.
- Improving backend architecture, database design, query performance and application security.
- Learning .NET (C#) and building cross-stack applications with ASP.NET Core.
- Strengthening my experience with Docker, CI/CD and cloud fundamentals.
- Writing maintainable code and reliable automated tests.

I'm looking for an opportunity as a **Python / Django / Backend Developer**, where I can contribute to a development team, learn from experienced engineers and grow through real-world software projects. I'm also open to suitable junior .NET opportunities.

---

## GitHub Statistics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Jayeshkalkate&show_icons=true&theme=tokyonight&hide_border=true" alt="Jayesh's GitHub statistics" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jayeshkalkate&layout=compact&theme=tokyonight&hide_border=true" alt="Most-used languages in Jayesh's public repositories" />
</p>

---

<div align="center">

## Let's Connect

I'm happy to connect with developers, recruiters and teams working on backend and full-stack software.

[![Portfolio](https://img.shields.io/badge/Portfolio-Website-5b8cff?style=for-the-badge&logo=netlify&logoColor=white)](https://devjayesh-portfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jayesh%20Kalkate-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayesh-kalkate-31a250242/)
[![Email](https://img.shields.io/badge/Email-kalkatejayesh%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kalkatejayesh@gmail.com)

*Building, learning and improving — one project at a time.*

</div>
