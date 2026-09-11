<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=200&section=header&text=Lee%20Yun%20Chang&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Full%20Stack%20Developer%20%40%20SeoulSoft&descAlignY=58&descSize=20" width="100%" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=24&pause=1000&color=6C7CF7&center=true&vCenter=true&width=500&lines=Hi+there!+I'm+Lee+Yun+Chang+%F0%9F%91%8B;Full+Stack+Developer+%40+SeoulSoft;Growing+one+commit+at+a+time" alt="Typing SVG" />

</div>

## 🙋‍♂️ About Me

- 🏢 Full Stack Developer at **SeoulSoft**
- 📍 Based in Chungju-si, South Korea
- 🧩 Building the **EG-ERP** product suite — packaged ERP solutions for solo founders & small businesses
- 🌱 From **Java 21 / Jakarta EE** backends to **Vanilla JS** frontends, and GCP deployment
- 💪 **1,000+ contributions** in the last year — consistency is my superpower
- 📫 Reach me at [yunch0315@gmail.com](mailto:yunch0315@gmail.com)

## 🛠 Tech Stack

<div align="center">

**Backend**

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Jakarta%20EE-FF6C37?style=for-the-badge&logo=jakartaee&logoColor=white" />
<img src="https://img.shields.io/badge/JSP%20%2F%20Servlet-F89820?style=for-the-badge&logo=coffeescript&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />

**Database & Infra**

<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" />
<img src="https://img.shields.io/badge/Apache%20Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" />
<img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />

**Frontend**

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />

**Tools**

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" />

</div>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api?username=yunch0315&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" />

<img src="https://streak-stats.demolab.com?user=yunch0315&theme=tokyonight&hide_border=true" />

</div>

## 🚀 EG-ERP Suite

> **EG-** (Engineering Group) is my packaged ERP product line —
> *"Don't fit your business to the system. An ERP built to fit the way you actually work."*
>
> ⚠️ The source repositories are **private**. Please use the live services below to take a look.

| Product | What it is | Live |
| --- | --- | --- |
| 🚀 **EG-ERP** | Official portal & service hub for the whole suite | **[eg-erp.com](https://eg-erp.com)** |
| 💧 **EG-aqua** | Multi-tenant ERP for water purifier & home appliance rental businesses | **[aqua.eg-erp.com](https://aqua.eg-erp.com)** |
| 🏍️ **EG-bike** | Store ERP for motorcycle / personal mobility repair & sales | *in development* |

---

### 🚀 EG-ERP — Portal & Service Hub

The front door of the suite. A 5-chapter storytelling landing page in an Apple Vision Pro–style
pure-black minimal design, acting as a gateway into every EG product plus custom ERP inquiries.

- **Stack**: Vanilla HTML5 / CSS3 / ES6+ — zero bundler overhead, instant first paint
- **Features**: smooth-scroll narrative sections, glassmorphism sticky sub-nav, inquiry modal wired to the service DB, `/admin` inquiry dashboard
- **Ops**: one-click `deploy.sh` pipeline to a GCP VM, served over HTTPS
- 🔗 <https://eg-erp.com>

### 💧 EG-aqua — Water Purifier Rental ERP

A multi-tenant web ERP for rental & care businesses, designed clean-room from standard rental
business rules rather than ported from legacy code.

- **Stack**: Java 21 LTS · Jakarta EE 10 (Tomcat 10.1+) · Pure MVC (Servlet + JSP/JSTL + JDBC DAO) · MySQL 8 · HikariCP · Flyway · jBCrypt
- **Multi-tenancy**: logical tenant isolation inside a single DB (`BIGSERIAL` PK + `tenant_id` composite unique)
- **Domain**:
  - Tiered rental billing — per-installment monthly fees, VAT & installment auto-calculation
  - Payment allocation & receivables — oldest unpaid invoice first, overpayment handling, year-by-year arrears tracking
  - Filter lifecycle & field service — up to 9 independent filter slots per customer with next-replacement tracking
  - 5-axis sales commission settlement (sales · team · area · support · management)
  - Role-based access control with per-menu permissions, CSRF protection, admin/staff separation
- **Why no framework**: tuned for low-spec cloud VMs — RSS stays in the 150–250MB range, cutting hosting cost
- 🔗 <https://aqua.eg-erp.com>

### 🏍️ EG-bike — Mobility Care & Store ERP

Customer-facing storefront + back-office ERP for motorcycle and personal mobility shops.
Currently in development, not yet publicly deployed.

- **Stack**: Java 21 LTS · Jakarta EE 10 · Pure MVC · MySQL 8 · HikariCP · Flyway · jBCrypt/CSRF filter
- **Storefront**: interactive landing page, product catalog with dynamic filtering, 4-step one-stop repair booking with Ajax slot lookup (double-booking blocked by both a DB unique constraint and app-level validation), guest/member reservation lookup, community & review boards
- **Back office**: live dashboard, reservation → repair work-order conversion, 5-stage repair workflow (`RECEIVED → DIAGNOSING → WORKING → DONE → DELIVERED`) that auto-generates sales entries on completion, parts inventory ledger with safety-stock alerts, sales/expense books, net-profit settlement with margin analysis and CSV export, customer CRM, staff account & permission management

---

## 🧪 Other Projects

| Project | Description |
| --- | --- |
| [AstroVerse](https://github.com/yunch0315/AstroVerse) | Personal project |
| [Java-C-team-CareMatch](https://github.com/test052517/Java-C-team-CareMatch) | Java team project — CareMatch |
| [JSP-B-team-Newsrrect](https://github.com/test052517/JSP-B-team-Newsrrect) | JSP team project — Newsrrect |

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=120&section=footer" width="100%" />

</div>
