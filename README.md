```console
sai@kgrcet MINGW64 ~ (main)
$ whoami
Aluguri Sai Vaibhav · AI Engineer | Full-Stack Engineer
CS undergrad @ KG Reddy College of Engineering and Technology, Hyderabad · CGPA 9.03
```

I build production-style AI applications and full-stack systems: LLM agents, embeddings and vector search, FastAPI and Node.js backends, React/TypeScript frontends, and Flutter apps.

**→ Portfolio: [saivaibhav.vercel.app](https://saivaibhav.vercel.app)** (it's a terminal, try `sudo hire-me`) · **[Resume (PDF)](https://saivaibhav.vercel.app/resume.pdf)**

```console
$ neofetch --short
  role       AI Software Developer Intern @ KGRCET
  hackathon  1st of 120+ teams, NASSCOM GenAI Forge (Feb 2026)
  shipped    kgrikarus.com (live tech fest platform)
  stack      React · FastAPI · Node.js · Supabase · pgvector
  speaks     English, Telugu
  into       Formula 1, AI, web dev, tech communities
```

---

## $ git log --oneline

```
a3d7f10  Jul 2026  feat:     joined KGRCET as AI Software Developer Intern
6c4e2b8  May 2026  chore:    became Social Impact Secretary, KGRCET Student Council
e41c9a7  2026      feat:     shipped IKARUS 2026 live at kgrikarus.com
9b2f06d  2026      feat:     joined AutoKryx Technologies as Flutter & Supabase Developer
5d7e13c  2026      feat:     built RE-TO AI (pgvector token reduction)
c08a4f2  Feb 2026  release:  1st place at NASSCOM GenAI Forge (CodeLens)
7f3b5e9  2025      chore:    became Operations Head, App/Web Dev Club
2a6d8b1  2025      feat:     Smart AI Recruitment System, FoodShare Connect
0e1f4c3            init:     started B.Tech CSE at KGRCET
```

---

## $ experience

### AI Software Developer Intern · KG Reddy College of Engineering and Technology
*Hyderabad (on-site) · Jul 2026 – present*
- Works across full-stack development, quality assurance, testing, deployment, automation and DevOps for components of the platform.
- Develops and executes functional, integration and regression test cases; documents defects and collaborates on troubleshooting and resolution.
- Hands-on with Git/GitHub workflows, CI/CD pipelines, application deployment and monitoring to improve system reliability and stability.
- Builds, integrates, tests and deploys real-world features following incremental SDLC practices.

### Flutter & Supabase Developer · AutoKryx Technologies
*Hyderabad · 2026*
- Engineered and deployed a cross-platform Community Portal in Flutter from a single codebase for mobile and web.
- Architected the Supabase backend: real-time relational database, user authentication and asset storage.
- Resolved UI rendering and asset-delivery bottlenecks, improving page speed and interaction latency.

---

## $ ls projects --all

### ★ Featured

#### 01 · [CodeLens: AI-Powered Code Review Agent](https://github.com/jashanth/CodeLens)
> 🏆 **1st Place, NASSCOM GenAI Forge (Feb 2026), out of 120+ teams** · *team project*

`FastAPI` `Python` `Groq (Llama 3.3 70B)` `Prompt engineering`
- Multi-language LLM code review flagging bugs, security vulnerabilities, performance bottlenecks and best-practice violations, classified by severity with explained fixes.
- Rewrite engine producing optimized, commented code in a side-by-side diff view, served by an async FastAPI backend.
- Co-designed the architecture, prompt-engineered the LLM and built the developer UX.

#### 02 · [IKARUS 2026: Tech Fest Website & Registration Platform](https://www.kgrikarus.com) · 🟢 LIVE

`React` `TypeScript` `Vite` `Node.js` `SQLite` `Supabase` `Cloudflare` `Render` `Nodemailer` `Spline` `Framer Motion`
- Official site for KGRCET's annual tech fest: 29 events from 9 clubs over two days, on a custom domain behind Cloudflare.
- Individual and team registration, UPI payments via auto-generated QR codes, encrypted payment-proof uploads.
- Node.js REST backend with SQLite and Supabase sync; role-based admin console for payment verification, filters, and Excel/CSV/Google Sheets export.
- Automated e-tickets and cancellation emails; hashed-password admin auth, rate limiting, login lockouts, Cloudflare Turnstile, strict security headers.
- SEO (structured event data, sitemap, Search Console); Spline 3D robot intro, light/dark theme, gallery, mobile layout.

#### 03 · [RE-TO AI (Reduce Tokens): LLM Token Reduction via Vector Search](https://github.com/SaiVaibhav06/RE-TO-AI)

`FastAPI` `Python` `React` `PostgreSQL + pgvector` `Google OAuth 2.0` `Docker Compose` `pgAdmin`
- Cuts LLM token usage by embedding user prompts (384-dim vectors) and storing them in PostgreSQL + pgvector for similarity search and reuse of prior queries.
- Designed the embeddings schema (query text, model, timestamp), FastAPI REST APIs, Google OAuth sign-in and a React playground with query/embedding visualization.
- Containerized the backend, Postgres and pgAdmin with Docker Compose for reproducible setup.

#### 04 · PhishSlayer: Real-Time Cyber Threat Detection & Analysis Platform
<!-- TODO: link https://github.com/SaiVaibhav06/PHISHSLAYER once the repo is public -->

`React` `Vite` `Tailwind` `Zustand` `FastAPI` `AsyncIO` `WebSockets` `Recharts`
- Packet monitoring plus a multi-label threat classifier (Phishing, Malware, Social Engineering, Financial Fraud, Suspicious Traffic) with risk scoring.
- URL analyzer (fake domains, suspicious TLDs, shortened/insecure links), Geo-IP source tracking, incident timeline.
- Real-time WebSocket alerts, an AI explanation assistant for remediation, and a response simulator (IP block, firewall rules), on a layered API–Service–Core architecture.

#### 05 · Smart AI Recruitment System · *2025 – present*

`React` `TypeScript` `Vite` `Tailwind` `Headless UI` `Gemini 2.5 Pro/Flash` `PDF.js`
- Gemini-powered semantic matching of job descriptions to resumes, multi-criteria suitability scoring and ranking, PDF resume upload, shortlist management, AI-personalized emails.

### More projects

<details>
<summary><b>Click to expand: 5 more projects</b></summary>

<br/>

| project | what it does | stack |
|---|---|---|
| [**Digital Prescription & Pharmacy Tracking System**](https://github.com/SaiVaibhav06/Digital-Pharmacy-System) | OOP medicine hierarchy, custom dosage exceptions, multithreaded prescription processing, real-time inventory, PDF prescriptions, demo and MySQL modes | React · Vite · Java · REST · JDBC · MySQL |
| **F1 Monaco 2025 Telemetry & Analytics Dashboard** <!-- TODO: link https://github.com/SaiVaibhav06/f1monacodashboard once public --> | Telemetry/lap/pit-stop pipeline into MySQL, EDA on race strategy, interactive dashboard; caching cut load time by ~35% | Python · FastF1 · Pandas · SQLAlchemy · MySQL · Plotly Dash |
| **FoodShare Connect** | Role-based food redistribution SPA (donors, receivers, drivers, cold-storage admins) with AI storage tips | React · TypeScript · Tailwind · Gemini API |
| **N-Queens Constraint Satisfaction & DNF Visualizer** | Backtracking/CSP solutions with an interactive visualizer of Boolean DNF representations and a complexity analysis | C · Python |
| **AI Voice To-Do App** | Speech-to-text task capture with NLU-based parsing and categorization | JavaScript · Python · Speech Recognition APIs |

</details>

---

## $ skills

```
ai / ml          LLM integration · prompt engineering · AI agents · embeddings · vector search (pgvector)
                 Groq (Llama 3.3) · Google Gemini API · generative AI · Pandas · data analytics
languages        Python · JavaScript (ES6+) · TypeScript · Java · Dart · C · SQL · HTML5 · CSS3
frontend         React · Next.js · Vite · Tailwind CSS · Framer Motion · Spline · Zustand · Headless UI
                 Flutter · Plotly Dash
backend & data   Node.js · FastAPI · REST APIs · WebSockets · AsyncIO · Google OAuth 2.0
                 PostgreSQL · MySQL · SQLite · Supabase · JDBC · SQLAlchemy
devops & tools   Docker · Docker Compose · Git · GitHub · Cloudflare · Render · Nodemailer · pgAdmin
                 GA4 · Google Tag Manager · Search Console · SEO · web security
cs fundamentals  data structures · algorithms · constraint satisfaction · DBMS · computer networks
```

---

## $ leadership

- **Social Impact Secretary**, Student Council, KGRCET · *May 2026 – present (AY 2026–27)*
  Leads student-driven social impact initiatives across NSS, Engineers Without Borders (EWB), KGR Cares and Street Cause: coordinates volunteers, works with student teams and faculty, and organizes outreach.
- **Operations Head & Core Member**, App/Web Development Club (CSI KGRCET)
  Runs workshops on responsive web, HTML/CSS and Git; helps members with debugging and performance.

## $ education

**B.Tech in Computer Science**, KG Reddy College of Engineering and Technology, Hyderabad · CGPA **9.03/10** · *currently pursuing*
Coursework: Data Structures · Algorithm Analysis & Design · DBMS · Computer Networks · Web Development · Cyber Security

<details>
<summary><b>$ certs</b></summary>

<br/>

- **SAP & Edunet Foundation:** Python, OOP, Data Analytics, DBMS, DSA, Competitive Coding
- **Simplilearn (Google Cloud):** Introduction to Generative AI Studio; Getting Python Interview Ready
- **HP LIFE:** Data Science Analytics; AI for Beginners
- **GUVI & HCL:** Full Stack Skills for Product-Based Companies

</details>

---

## $ contact

[**Portfolio**](https://saivaibhav.vercel.app) · [**LinkedIn**](https://www.linkedin.com/in/sai-vaibhav-aluguri-93a034326/) · [**Email**](mailto:saivaibhavaluguri@gmail.com) · [**Resume**](https://saivaibhav.vercel.app/resume.pdf)

```console
$ exit
nice try. you can't leave the matrix that easily
```
