# 👋 Hi, I'm MohammadSaeid Karbaschian

**Odoo Developer | Python | Django | React | ERP Implementation & Migration**

Developer based in Vaughan, Ontario (Greater Toronto Area) with 4+ years of hands-on **Odoo** experience — end-to-end implementations, custom module development, version and data migrations, and long-term support for small and mid-sized businesses — plus web applications built with **Python/Django**, **Django REST Framework** and **React + TypeScript**. Background in technical support and QA for production web platforms.

I care about production-grade patterns: atomic transactions, concurrency safety, background jobs, testing (pytest), linting (Ruff), Docker, and CI/CD. Currently deepening my **AWS** skills (ECS Fargate, RDS, ECR).

🇨🇦 Authorized to work in Canada · Open to Odoo, Python / Django and full-stack (React) developer roles in the GTA or remote.

---

## 🛠️ Tech Stack

| Category | Technologies |
| --- | --- |
| **Languages** | Python, TypeScript, JavaScript, SQL, HTML, CSS, XML |
| **Backend** | Django, Django REST Framework, Celery, JWT, Odoo (ORM, QWeb) |
| **Frontend** | React, Vite, React Router, Recharts |
| **Data & Cache** | PostgreSQL, Redis |
| **DevOps** | Docker, Docker Compose, GitHub Actions (CI/CD), Git, Linux, AWS (learning) |
| **Quality** | pytest, Ruff, pre-commit, Swagger/OpenAPI |

---

## 🚀 Featured Project

### [StockFlow](https://github.com/msaeiid/stockflow) — Inventory & Order Management System
Full-stack app that helps small businesses manage products, warehouses, suppliers, and customer orders. Built end-to-end and deployed to production (backend on Render, frontend on Vercel).

- **Atomic multi-item stock deduction** — all items deduct inside one DB transaction; any shortage rolls back the whole order (no partial orders, no negative stock).
- **Concurrency-safe** using `select_for_update()` row locking.
- **Async low-stock alerts** as Celery tasks dispatched via `transaction.on_commit`, with graceful fallback to in-memory cache when Redis is unavailable.
- **JWT auth** with role-based access (admin / manager / staff).
- **CI pipeline** on GitHub Actions: pytest against a PostgreSQL service container + Ruff linting.

**Stack:** Python, Django, DRF, PostgreSQL, Celery, Redis, React, TypeScript, Vite, Docker, GitHub Actions
🔗 **Live demo:** demo / demo12345

---

## 💼 Experience

- **Odoo Developer — Ati Parvaz Tour & Travel agency** (Dec 2024 – Present · contract, remote) — Implemented Odoo from scratch for a travel agency and modelled the company's existing business flows inside the system; provide ongoing remote support, fixes and enhancements.
- **Software Engineer — Self-employed** (Jun 2023 – Present · freelance) — Short-term, full-time contract engagements with Odoo, Python / Django and React; clients included MPA, Alvan Parand Shimi, Azin Did Faraz Novin and Akam.
  - Odoo setup, deployment, customization and post-go-live support — including an optic product pricing matrix in sale orders (cut order-entry clicks ~25–30%), receivable/payable smart buttons for a finance team, and HR/payroll and approvals-to-inventory modules.
  - Django / DRF back ends and React + TypeScript front ends for paid client projects, including a portfolio & content-management website for a sculptor and set designer.
  - Volunteer: planned, built and deployed a bilingual (English / Persian) membership, attendance, course and certificate platform for a non-profit educational organization (Django 5, DRF, Celery, PostgreSQL, Redis, React 18 + TypeScript; QR-code check-in, PDF certificates with public verification, 2FA, 950+ backend tests).
- **Odoo Developer — ABG (Aria Beniz Group)** (Feb 2022 – Oct 2022 · contract) — Led the migration of company data and custom modules from Odoo v8 to v14, rebuilding the project from the ground up; developed new custom modules; retained afterwards for project-based support.
- **Technical Support & QA Specialist — Fanavaran Etelaat Pishkhan Iranian** (May 2018 – Nov 2021 · contract) — Supported production websites, including national digital-signature and e-Prescription platforms: feature testing, bug reproduction and API verification, ticket triage, a searchable FAQ / knowledge base, and Python scripts to automate support and reporting.
- **Freelance Developer — Self-employed** (Oct 2010 – May 2018) — Freelance development and project work alongside full-time studies, including survey / data-collection forms for a client company.

## 📂 More Projects

- **[Portfolio website for a sculptor & set designer](https://www.hasankakavand.com/en/)** (client project, Nov 2024 – Aug 2026) — Django REST API, customized Django admin (galleries, blog, services, reviews), CKEditor 5, multilingual React + TypeScript + Vite front end with Tailwind CSS.
- **Survey & field-interview web app for Agah** (client project, Jul – Aug 2021) — Django 3.2, DRF, jQuery and Bootstrap; interviewers ran multi-step surveys, answer sheets were auto-scored into socio-economic classes, Persian (RTL) interface with Jalali dates.

---

## 🎓 Education

- **Bachelor's degree, Computer Software Engineering Technology** — Shamsipour Technical and Vocational College (2017) · WES: equivalent to a Canadian four-year bachelor's degree
- **Associate's degree, Computer Networks** — University of Applied Science and Technology (2015) · WES: equivalent to a Canadian two-year college diploma

---

## 📫 Let's Connect

- 📍 **Location:** Vaughan, Ontario, Canada (Greater Toronto Area)
- 📧 **Email:** [mskarbaschian@gmail.com](mailto:mskarbaschian@gmail.com)
- 🔗 **LinkedIn:** [linkedin.com/in/msaeedk](https://www.linkedin.com/in/msaeedk/)
