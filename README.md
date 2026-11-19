<div align="center">

# Hi, I'm Jayesh Kalkate 👋

### Python · Django · Backend Development · PostgreSQL

**B.Tech Computer Engineering (2026) | Maharashtra, India**

I build practical, database-driven web applications by starting with a real problem, planning a solution, and developing the features needed to make it useful.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-5b8cff?style=for-the-badge&logo=netlify&logoColor=white)](https://devjayesh-portfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayesh-kalkate-31a250242/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kalkatejayesh@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-View-2dd4bf?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://devjayesh-portfolio.netlify.app/assets/docs/Jayesh_Kalkate_Resume.pdf)

**Open to opportunities:** Python Developer · Django Developer · Backend Developer · Junior Full-Stack Developer

</div>

---

## About me

I'm a Computer Engineering graduate (2026) focused on **Python, Django and backend development**. Most of my learning has come from building applications around problems I have seen in everyday life, college, and my community—not simply reproducing tutorial projects.

My usual process is to understand the problem, map out a solution, plan the features, design the data model, build and integrate the application, then run it and deploy it. I enjoy working across the backend, database, APIs, authentication, and the parts of the frontend needed to make a complete product.

I also use AI tools such as ChatGPT, Claude and DeepSeek to explore approaches, understand unfamiliar code, and debug. I write the requirements and prompts, review the generated changes, run the application, and take responsibility for the final implementation and deployment.

### What I work with

- **Backend:** Python, Django, Django ORM, REST API integration, webhooks
- **Databases and caching:** PostgreSQL, SQLite, Redis
- **Security:** Email OTP, role-based access control, rate limiting, CSRF protection, input validation, audit logging, Fernet encryption, HMAC verification
- **Integrations:** Razorpay, Google Gemini, Telegram Bot API, TMDB, TVMaze, Jikan, AniList, Cloudinary, Brevo
- **Frontend:** HTML, CSS, Bootstrap, JavaScript, Progressive Web Apps
- **Tools and deployment:** Git, GitHub, GitHub Actions, Docker, Linux, Render, Netlify
- **Currently learning:** C# and ASP.NET Core; continuing to strengthen cloud and DevOps fundamentals

---

## Projects

Each project began with a different problem or idea. These are working applications and active builds, not just classroom write-ups. Project availability and feature scope can vary by deployment; see each repository for the current source.

### 1. KhataLink — Multi-Shop Digital Khata Network

**The problem:** Shopkeepers and customers often rely on handwritten udhaar records or scattered messages. It can be difficult to keep records consistent, check balances across shops, or resolve a disagreement about an entry or payment.

**The solution:** KhataLink is a consent-based digital ledger connecting customers with multiple shops. Each shop manages its own records, while customers can see dues from the shops they have connected to.

**Key features**
- Multi-tenant data model with shop-scoped queries to keep each shop's records separate
- Append-only ledger: entries can be voided or corrected rather than silently deleted
- Email OTP authentication, role-based access for customers, shop owners, managers, cashiers and administrators
- Audit logging and idempotency keys to help prevent duplicate submissions
- Dispute conversations, UPI payment links, due-date reminders, expiring share links and PDF statements

**Tech stack:** Python, Django, PostgreSQL (Neon), Redis, Cloudinary, ReportLab, Brevo

[Live Demo](https://khatalink.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/KhataLink)

---

### 2. Lavkush Furniture — E-Commerce and Business Management Platform

**The problem:** In our family furniture shop, sharing product photos and explaining prices, materials, and product details individually took time. I saw an opportunity to build a platform that could make product discovery and shop operations easier.

**The solution:** I started by learning Python and Django, then developed an online furniture catalogue and store. The project grew to include customer shopping features and a business dashboard for managing day-to-day operations.

**Key features**
- Product gallery with single and bulk uploads, furniture catalogue, search and filters
- Shopping cart, wishlist, order history, returns flow and PDF receipts
- Business dashboard for sales, orders, payments, customers, coupons, products, categories, reviews and team management
- Razorpay checkout with server-side order creation and payment-signature verification
- HMAC-validated payment webhook and row-locked inventory updates, with refund handling for stock-related payment failures
- Validated bulk CSV/XLSX product import

**Tech stack:** Python, Django, PostgreSQL, SMTP, Razorpay, Cloudinary, ReportLab, Docker

[Live Demo](https://lavkushfurniture.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/Lavkush_Furniture)

---

### 3. Ask Me — Secure AI Document Assistant

**The problem:** At college, we were often asked for details such as student IDs and university registration numbers. Finding the correct document photo or PDF each time—or searching through physical files when a copy was unavailable—was inconvenient.

**The solution:** Ask Me lets users store identity and certificate documents, extract useful fields, review the extracted information, and ask questions based on their own saved documents.

**Key features**
- Upload support for PDF, JPG, PNG and TIFF files, with predefined document types including Aadhaar, PAN, passport and driving licence
- OCR and Gemini-assisted extraction, followed by structured field matching
- Users can review, edit, add or remove extracted fields before saving
- Fuzzy field matching and a chatbot grounded in the user's own documents
- Extracted data encrypted at rest using Fernet
- Installable, offline-capable PWA using a service worker and IndexedDB; previously saved information can be accessed offline
- Expiring share links and document-expiry reminders

**Tech stack:** Python, Django, PostgreSQL, Google Gemini API, OCR, JavaScript, IndexedDB, Fernet, PWA, Cloudinary

[Live Demo](https://ask-me-smart-document-assistant.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/ask_me)

---

### 4. MoviesHub — Movies, Series and Anime Discovery Platform

**The problem:** My friends and I shared recommendations and content in a Telegram group. Finding a title by its name, getting reliable metadata or a trailer, and following a story across a cinematic universe often meant searching across several websites and messages.

**The solution:** MoviesHub brings discovery information together in one place. It combines metadata from multiple services, helps users search in natural language, groups related titles into universes, and connects the platform with a Telegram bot.

**Key features**
- Metadata integration with TMDB, TVMaze, Jikan and AniList
- Gemini-assisted natural-language search and recommendations
- Featured and recently shared content, trailer links, and title search
- Automatic linking of related titles into cinematic universes and watch orders
- User content requests and Telegram bot integration through webhooks, with a Telethon backfill command
- Owner dashboard for managing titles, categories, users and other content
- Redis caching to reduce repeated external API calls

**Tech stack:** Python, Django, PostgreSQL (Neon), Redis, Google Gemini, TMDB, TVMaze, Jikan, AniList, Telegram Bot API

*Note: AWS S3 storage is integrated in the project but is currently disabled in the live deployment.*

[Live Demo](https://movies-hub-6dhp.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/Movies-Hub)

---

### 5. Matoshree — Common Service Centre (CSC) Portal

**The problem:** Applying for a service such as an income certificate can involve finding the required documents, collecting copies, visiting a service centre, and later trying to find out the application's status. The process can be confusing when information is spread across different places.

**The solution:** Matoshree brings service information and application steps into one portal, connecting applicants with the service centre's staff and management workflows.

**Key features**
- Service listings, required-document information, service charges and downloadable forms
- Online service applications with document uploads and verification statuses
- Appointment booking with double-booking prevention
- Application tracking, announcements, reviews and job/scheme updates
- Job and government-scheme information gathered through web scraping, with caching
- User, owner and admin dashboards for managing the relevant records
- Manual UPI/cash payment verification, optional Razorpay checkout and PDF receipts

**Tech stack:** Python, Django, PostgreSQL, Redis, Razorpay, BeautifulSoup, Cloudinary, ReportLab

[Live Demo](https://matoshree-cyber.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/Matoshree-Cyber)

---

### 6. SceneSeek — Screenshot-Based Movie, Series and Anime Finder

**The problem:** Sometimes you remember a scene or have a screenshot or short clip, but do not know the title of the movie, series or anime it came from. Searching by title is not helpful when the title itself is unknown.

**The solution:** SceneSeek is a cross-stack project that accepts a screenshot, image, short video clip or video URL and attempts to find matching screen content. It is connected with MoviesHub to link discovery with the wider catalogue.

**Key features**
- ASP.NET Core API built with C#
- Python worker for OCR and video-frame extraction
- Next.js web interface
- Input through screenshots, images, short clips and video URLs
- Connection with MoviesHub for related content discovery

**Tech stack:** C#, ASP.NET Core, Python, Next.js, PostgreSQL (Neon), Docker, GitHub Actions

*This is also my hands-on project for learning .NET and ASP.NET Core alongside my Django work. Recognition is an ongoing area of development.*

[Live Demo](https://sceneseek-web.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/SceneSeek)

---

### 7. VIndia — Vehicles of India Discovery Platform

**The problem:** When I wanted to compare vehicles, I found it difficult to view different models and their features together in one place. This became the idea for my first website, which I built during my third year.

**The solution:** I learned HTML, CSS and JavaScript by creating a vehicle discovery site. I collected and organised vehicle information into JSON data and built filters and comparison views around it.

**Key features**
- Information covering 350+ vehicle models from 42+ brands
- Live search and cascading Type → Brand → Model filters
- Side-by-side vehicle comparison
- Responsive static website hosted on Netlify

**Tech stack:** HTML5, CSS3, Bootstrap 5, JavaScript, JSON, Netlify

[Live Demo](https://vehicles-of-india-vindia.netlify.app/) · [GitHub Repository](https://github.com/Jayeshkalkate/VIndia)

---

### 8. LokSetu — Civic Complaint and Transparency Platform

**The problem:** In smaller towns and local areas, citizens may find it difficult to submit a complaint to the right department and follow what happens next. My broader idea is to make public-service activity easier to understand and improve transparency around local issues and public work.

**The current build:** LokSetu is a civic complaint platform where citizens can submit complaints with evidence and track them, while departments work through role-scoped dashboards. The larger vision—including dependable public information and fund-use transparency—needs verified official data and further development.

**Implemented areas**
- Complaint submission with evidence uploads and unique tracking IDs
- Automatic department routing and role-scoped dashboards
- Login throttling, file validation and audit entries
- GitHub Actions pipeline for deployment and migration checks

**Tech stack:** Python, Django, PostgreSQL (Neon), GitHub Actions

*Status: In development; the wider public-data and transparency vision is not yet fully implemented.*

[Live Demo](https://lok-setu.onrender.com) · [GitHub Repository](https://github.com/Jayeshkalkate/loksetu)

---

## Technical skills

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,django,postgres,sqlite,redis,js,html,css,bootstrap,docker,git,github,githubactions,linux,cs,dotnet&perline=8" alt="Python, Django, PostgreSQL, SQLite, Redis, JavaScript, HTML, CSS, Bootstrap, Docker, Git, GitHub, GitHub Actions, Linux, C sharp and .NET" />
</p>

| Area | Technologies |
|---|---|
| Languages | Python, JavaScript, SQL; C# (learning) |
| Backend | Django, Django ORM, migrations, management commands, REST API integration, webhooks; ASP.NET Core fundamentals |
| Databases and caching | PostgreSQL (Neon), SQLite, Redis (Upstash), schema design, query optimization |
| Authentication and security | Email OTP, role-based access control, rate limiting, CSRF protection, input validation, audit logging, Fernet encryption, HMAC verification |
| Frontend | HTML5, CSS3, Bootstrap 5, JavaScript, Progressive Web Apps |
| APIs and services | Razorpay, Google Gemini, Telegram Bot API, TMDB, TVMaze, Jikan, AniList, Cloudinary, Brevo |
| DevOps and deployment | Git, GitHub Actions, Docker, Linux, Render, Netlify, Gunicorn, WhiteNoise |
| Additional exposure | Jenkins, Ansible, Bash, AWS fundamentals, ReportLab, BeautifulSoup |

---

## Experience

**Python Programming Intern — Prasunet** · Remote · March 2025 – April 2025  
Worked on Python scripting, file handling, functions and modular programming.

**Full Stack Developer Intern — Vaishnav Technologies** · Remote · February 2025 – March 2025  
Worked on web applications with Django, HTML, CSS, JavaScript and Bootstrap; managed media with Cloudinary and deployed applications on Render using Git and GitHub workflows.

**Data Entry Intern — Rural Field Survey Program** · May 2022 – June 2022  
Supported survey data collection and validation, and organised information using Microsoft Excel.

---

## Education

**B.Tech in Computer Engineering**  
Godavari College of Engineering, Jalgaon (DBATU) · 2022–2026 · CGPA: 7.2/10

---

## Certifications and training

- **Red Hat:** System Administration I (RH124), Linux Fundamentals (RH104), Introduction to OpenShift Applications (DO101)
- **Simplilearn SkillUp:** Python 3.x, SQL for Data Analysis, Web Scraping with BeautifulSoup
- **NSDC / Skill India:** Web Design and Development
- **IIT Bombay Spoken Tutorial:** Python and Java
- **DevOps Bootcamp:** Jenkins, Docker, Linux, AWS, Ansible and Bash scripting
- **Other:** Smart India Hackathon 2024; six-day Python programming workshop

[View certificates](https://drive.google.com/drive/folders/1Iwxvmfb4jzhRlW1Vq3ToGJekdggKDhWM?usp=drive_link)

---

## Currently learning and exploring

- Strengthening Django, PostgreSQL, database design and application security
- Improving Docker, CI/CD and cloud deployment fundamentals
- Learning C# and ASP.NET Core through SceneSeek

I'm looking for an opportunity as a **Python / Django / Backend Developer** where I can contribute to real products, learn from an experienced team and continue growing as an engineer.

---

<div align="center">

### Let's connect

[Portfolio](https://devjayesh-portfolio.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/jayesh-kalkate-31a250242/) · [Email](mailto:kalkatejayesh@gmail.com) · [GitHub](https://github.com/Jayeshkalkate)

*Building practical solutions, one problem at a time.*

</div>
