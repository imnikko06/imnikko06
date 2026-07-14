<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:339933&height=220&section=header&text=Adri%C3%A1n%20Petkov&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Developer%20%7C%20Full%20Stack%20when%20needed&descAlignY=55&descSize=18" width="100%"/>

<a href="https://www.linkedin.com/in/adri%C3%A1n-petkov-08251928a/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:nikodrian2006@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/📍_Logroño,_Spain-555555?style=for-the-badge" />
<img src="https://img.shields.io/badge/🌍_Relocating_to_Warsaw_2026-4C1?style=for-the-badge" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=339933&center=true&vCenter=true&width=650&lines=Building+APIs+with+Node.js+%2B+Express+%2B+TypeScript;PostgreSQL+%26+Prisma+ORM+specialist;Solo+Developer+%40+YGRA;AWS+Certified+Developer+Associate+(in+progress)" alt="Typing SVG" />

</div>

<br/>

## 👨‍💻 About Me

I'm a **full stack developer with a backend focus**. I enjoy diving deep into data architecture, API design, and everything related to making a system scale without turning into chaos.

Right now, at **YGRA**, I'm the **Solo Developer** responsible for the company's internal software: from gathering requirements directly with stakeholders, to designing the infrastructure, to building the backend from scratch (Node.js + Express) — which I'm now migrating to **TypeScript** — along with the frontend in **Vue.js**, using **Prisma ORM** for database access. I also work directly with the **A3 ERP** database and use **PHP** to modify its non-obfuscated code where needed, alongside our own internal database. I've designed access control systems including **RBAC** and **module-based access control (MBAC)**. In parallel, I'm advancing my **AWS** skills to strengthen the deployment and cloud side of things.

```yaml
role:        Solo Developer @ YGRA
focus:       Backend Architecture · APIs · Data Modeling
currently:   Migrating backend to TypeScript + building Vue.js frontend
learning:    AWS Certified Developer Associate
relocating:  Warsaw, Poland — 2026
fun_fact:    "Went from SAP ERPs & IT support to full ownership of a codebase"
```

<br/>

## 🛠️ Tech Stack

<div align="center">

**Backend & Languages**

<img src="https://skillicons.dev/icons?i=nodejs,express,ts,js,php,python" />

**Databases**

<img src="https://skillicons.dev/icons?i=postgres,prisma,redis,mysql" />

**Frontend**

<img src="https://skillicons.dev/icons?i=vue,tailwind" />

**Cloud, DevOps & Tools**

<img src="https://skillicons.dev/icons?i=aws,docker,vercel,git,github" />

**Enterprise & Systems**

<img src="https://img.shields.io/badge/SAP_B1-0FAAFF?style=flat-square&logo=sap&logoColor=white" />
<img src="https://img.shields.io/badge/SAP_HANA-0FAAFF?style=flat-square&logo=sap&logoColor=white" />
<img src="https://img.shields.io/badge/A3_ERP-1A1A1A?style=flat-square" />
<img src="https://img.shields.io/badge/RBAC-2D3748?style=flat-square" />
<img src="https://img.shields.io/badge/MBAC-2D3748?style=flat-square" />
<img src="https://img.shields.io/badge/BullMQ-C41E3A?style=flat-square" />
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
<img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/Active_Directory-0078D6?style=flat-square&logo=microsoft&logoColor=white" />

</div>

<br/>

## 🚀 Featured Project

<div align="center">

### 💰 MY Money
**PWA for shared expense management with intelligent OCR receipt scanning**

<img src="https://skillicons.dev/icons?i=vue,ts,nodejs,express,postgres,prisma,redis,aws,vercel,tailwind" />

</div>

| Layer | Technologies |
|---|---|
| 🎨 **Frontend** | Vue.js + TypeScript, Tailwind CSS, **PWA** (Progressive Web App), Cropper.js + OpenCV for receipt corner detection, i18n (multi-language), Driver.js for guided onboarding |
| ⚙️ **Backend** | Node.js + Express + TypeScript, Zod for schema validation, Bcrypt + Google Passport for authentication, Multer for file uploads, Cron for scheduled jobs, PM2 for process management |
| 🤖 **Smart OCR** | **PaddleOCR** for ticket/receipt reading — migrated from Tesseract.js after accuracy issues — processed asynchronously via **Redis + BullMQ** workers to handle load |
| 🗄️ **Data** | PostgreSQL + Prisma ORM, using **Prisma transactions** to guarantee consistency on simultaneous payments |
| ☁️ **Cloud** | AWS (S3 with IAM roles + signed URLs for secure image storage, EC2) and Vercel for deployment |

**Key engineering decisions:**
- Solved OCR request overload by queuing jobs through BullMQ + Redis workers instead of processing synchronously.
- Replaced Tesseract.js with PaddleOCR after finding its accuracy insufficient for real-world receipts.
- Secured server-side images with Multer + S3 + IAM + private signed URLs instead of public storage.
- Prevented duplicate/inconsistent payments in group expenses using Prisma database transactions.

> 🔗 *Add the repository link here once it's public*

<br/>

## 💼 Experience

<details open>
<summary><b>🟢 Software Engineer (Solo Developer) · YGRA</b> — <i>Jul 2025 – Present</i></summary>
<br/>

- Sole developer of the company's internal software, owning everything end to end: gathering requirements directly with stakeholders, designing the infrastructure, and building the system from scratch.
- Built the original backend and I'm currently migrating it to **TypeScript** (Node.js + Express), together with the frontend in **Vue.js**.
- Work across multiple data sources: the **A3 ERP** database and the internal database, using **PHP** to modify A3's non-obfuscated code and **Prisma ORM** for type-safe access on the internal side.
- Designed and implemented access control systems, including **RBAC** and **module-based access control (MBAC)**.
- Full technical ownership and decision-making over the roadmap, architecture, and tooling.

</details>

<details>
<summary><b>🔵 Software Engineer Intern · Globant</b> — <i>Jan 2026 – May 2026</i></summary>
<br/>

- Designed and built a full-stack **expense management system** as a final degree project, with a robust backend architecture using **Node.js, Express.js, and TypeScript**.
- Implemented asynchronous task processing and background jobs with **Redis and BullMQ** for system responsiveness under load.
- Designed a full **RBAC (Role-Based Access Control)** system for secure authorization, and managed complex data relations with **PostgreSQL and Prisma ORM**.
- Handled end-to-end cloud infrastructure and application deployment on **AWS**, ensuring environment stability and scalability.
- Integrated AI-based OCR microservices for automated data extraction.
- Completed advanced specializations in **TypeScript for Developers** and **AWS Cloud Services**, applying industry-standard practices to the project.

</details>

<details>
<summary><b>🟣 Software Engineer Intern · SDi (Novotic)</b> — <i>Mar 2025 – Jun 2025</i></summary>
<br/>

- Gained hands-on experience in enterprise software environments working directly with **SAP B1, SAP HANA, and Microsoft SQL Server**.
- Developed and consumed APIs using **Node.js and SAP's ServiceLayer**, integrating enterprise systems and handling complex **XML and JSON** data structures.
- Proactively identified automation opportunities and built utility projects in **Python and JavaScript** to streamline internal operations.

</details>

<details>
<summary><b>⚪ IT Support Technician Intern · Standard Profil Group</b> — <i>Mar 2024 – Jun 2024</i></summary>
<br/>

- Managed deployment, configuration, and physical installation of IT workstations and network equipment across the facility.
- Troubleshot network connectivity and operating system issues.
- Completed a 220-hour technical specialization in **Windows Server 2022, Hyper-V virtualization, and Active Directory (AD)**, validated through a final technical assessment by senior administrators.

</details>

<br/>

## 🎓 Education & Certifications

- **Web Application Development** — Sagrado Corazón Jesuitas (2024 – 2026)
- **Microcomputer Systems and Networks** — Sagrado Corazón Jesuitas (2022 – 2024)
- TypeScript for Developers · AWS Serverless APIs & Apps · AWS Certified Developer Associate *(in progress)*

<br/>

<div align="center">

### 📫 Let's talk!

<a href="mailto:nikodrian2006@gmail.com">
  <img src="https://img.shields.io/badge/Email_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/adri%C3%A1npetkov-08251928a">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:339933,100:0A66C2&height=100&section=footer" width="100%"/>

</div>
