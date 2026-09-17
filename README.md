<p align="center">
  <img src="./github-header-image.png" alt="Maksim - Fullstack & Backend Engineer" width="100%" />
</p>

<p align="center">
  <a href="https://t.me/mrktox"><img src="https://img.shields.io/badge/Telegram-@mrktox-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <img src="https://img.shields.io/badge/Available_for_Freelance-Open_to_Projects-success?style=for-the-badge&logo=codeforces&logoColor=white" alt="Freelance Available" />
  <img src="https://img.shields.io/badge/Remote-Worldwide-009688?style=for-the-badge&logo=google-earth&logoColor=white" alt="Remote" />
</p>

---

# Hey there, I'm Maksim 👋
### 🚀 Fullstack & Backend Engineer | Python & Vue.js | Telegram Mini Apps & Distributed Systems

I build production-ready web platforms, high-converting **Telegram Mini Apps (TMA)**, and resilient **distributed backend architectures**. Whether you need a turnkey MVP launched with automated payment processing, a corporate platform with fine-grained access control, or a high-throughput event processing pipeline with real-time analytics — I deliver clean, well-tested, and maintainable software that drives business outcomes.

---

### 💼 What I Bring to Your Project

- 📱 **Turnkey Telegram Mini Apps (TMA):** End-to-end development — Telegram-native mobile UX (Vue 3 / Quasar), cryptographic `initData` verification, automated payment webhooks, and background worker daemons.
- 🏛️ **Clean & Scalable Backend Architecture:** Production systems designed with strict layer separation (Clean / Onion Architecture, Repository & Service patterns), async databases (`asyncpg` + SQLAlchemy 2.0), and automated migrations (`Alembic`).
- ⚡ **High-Throughput Streaming & Real-Time ML:** Message-driven pipelines using **Apache Kafka (KRaft)**, in-memory streaming machine learning anomaly detection ($O(1)$ memory/latency), and **Vector** log transformation.
- 🔒 **Enterprise-Grade Security & Automation:** Zero-trust network segmentation, automated PKI/mTLS certificate lifecycles, and network infrastructure orchestration with transactional safety.
- 🤝 **Client-Centric Process:** Transparent communication, clear delivery milestones, Dockerized containerization for painless deployment, and post-launch support.

---

### 🌟 Featured Production Projects

<table>
  <tr>
    <td width="50%">
      <h3 align="center">🛡️ Multi-Agent SIEM & SOAR System</h3>
      <p align="center">
        <a href="https://github.com/KrayMakso68/edge-routed-siem"><b>View Repository (edge-routed-siem) ➔</b></a>
      </p>
      <p>
        Next-generation distributed SIEM/SOAR platform featuring edge network sensors, zero-trust mTLS isolation, and <b>in-memory streaming machine learning anomaly detection</b> before disk indexing.
      </p>
      <ul>
        <li><b>Streaming ML in RAM:</b> Unsupervised Half-Space Trees (River ML) scoring alerts in amortized $O(1)$ time inside the Kafka pipeline.</li>
        <li><b>Proven Performance:</b> Mathematically modeled ($M/M/1/\infty/\text{FIFO}$) and benchmarked on CICIDS-2017: <b>&gt;2x alert latency reduction</b> ($K_{\text{op}} = 2.05$).</li>
        <li><b>Edge Telemetry:</b> Suricata 7 (NIDS), Zeek 6 (NTA), and Vector (Rust) transforming multi-source logs to Elastic Common Schema (ECS).</li>
        <li><b>Single-Pane-of-Glass Console:</b> Clean Architecture backend on <b>FastAPI</b> + reactive <b>Vue 3</b> SOC dashboard with automated PKI & IDS rule orchestration.</li>
      </ul>
      <p>
        <code>FastAPI</code> • <code>Vue 3</code> • <code>Apache Kafka</code> • <code>River ML</code> • <code>Vector (VRL)</code> • <code>Elasticsearch</code> • <code>Docker</code>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">📱 Telegram Mini App VPN Ecosystem</h3>
      <p align="center">
        <a href="https://github.com/KrayMakso68/TelegramMiniAppBot"><b>View Repository (TelegramMiniAppBot) ➔</b></a>
      </p>
      <p>
        Commercial self-hosted VPN management ecosystem engineered specifically for Telegram, automating user onboarding, subscription billing, and node provisioning.
      </p>
      <ul>
        <li><b>Zero-Trust WebApp Auth:</b> Native Telegram Mini App (Vue 3 + Quasar + TypeScript) with HMAC-SHA256 <code>initData</code> validation and browser isolation.</li>
        <li><b>Automated Billing:</b> YooMoney IPN webhook processing with SHA-1 signature verification and instant order fulfillment.</li>
        <li><b>Instant Node Provisioning:</b> Automated synchronization with remote <b>3X-UI</b> panels for VLESS/Xray credential generation.</li>
        <li><b>Proactive Alerts:</b> Background <b>Aiogram 3</b> daemon handling multi-tier subscription expiration warnings.</li>
      </ul>
      <p>
        <code>FastAPI</code> • <code>Vue 3 / Quasar</code> • <code>TypeScript</code> • <code>Aiogram 3</code> • <code>SQLAlchemy 2.0</code> • <code>PostgreSQL</code> • <code>YooMoney</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">🏢 Enterprise Workforce & Discipline System</h3>
      <p align="center">
        <a href="https://github.com/KrayMakso68/disciplinary_practice_31_courses"><b>View Repository ➔</b></a>
      </p>
      <p>
        Scalable corporate platform designed for multi-tier enterprises to track workforce performance, commendations, penalties, and compliance metrics.
      </p>
      <ul>
        <li><b>Recursive Tree Hierarchy:</b> Modified Preorder Tree Traversal (<b>django-mptt</b>) enabling instant $O(1)$ descendant tree querying across complex corporate branches.</li>
        <li><b>Hierarchical RBAC:</b> Granular permission gates (<code>UserPassesTestMixin</code>) isolating visibility strictly to authorized organizational subunits.</li>
        <li><b>Automated Reporting:</b> Server-side dynamic <code>.docx</code> document generation (<code>docxtpl</code>) with headless <b>Matplotlib/Seaborn</b> chart rendering.</li>
        <li><b>Interactive Dashboards:</b> Dynamic AJAX date-range filtering and client-side Chart.js visual analytics.</li>
      </ul>
      <p>
        <code>Python</code> • <code>Django</code> • <code>django-mptt</code> • <code>Bootstrap 5</code> • <code>docxtpl</code> • <code>Matplotlib / Seaborn</code>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">⚙️ Network Infrastructure Automation</h3>
      <p align="center">
        <a href="https://github.com/KrayMakso68/conf_net_equipment"><b>View Repository ➔</b></a>
      </p>
      <p>
        Multi-threaded desktop automation utility for remote configuration provisioning, factory resets, and batch script deployment across Eltex enterprise hardware.
      </p>
      <ul>
        <li><b>SSHv2 Automation:</b> Multi-vendor driver abstraction via <b>Netmiko</b> with interactive prompt handling for ESR routers and MES switches.</li>
        <li><b>Transactional Safety:</b> Two-phase commit verification (<code>commit</code> / <code>confirm</code>) preventing configuration loss and remote administrative lockout.</li>
        <li><b>Responsive Multi-Threading:</b> Asynchronous network I/O preventing UI freezing, with real-time streaming CLI terminal output.</li>
        <li><b>Defensive Engineering:</b> Strict IPv4 regex octet boundary validation and granular socket exception handling.</li>
      </ul>
      <p>
        <code>Python</code> • <code>Netmiko</code> • <code>Tkinter (Multi-threaded)</code> • <code>SSHv2</code> • <code>Eltex Hardware</code>
      </p>
    </td>
  </tr>
</table>

---

### 🛠 Tech Stack & Core Competencies

<div align="center">

| Area | Technologies & Tools |
| :--- | :--- |
| **Backend & APIs** | `Python 3.11+` • `FastAPI` • `Django / DRF` • `AsyncIO` • `SQLAlchemy 2.0 (Async)` • `Alembic` • `Pydantic v2` • `Aiogram 3` • `Netmiko` |
| **Frontend & TMA** | `Vue.js (Vue 3, Composition API)` • `TypeScript` • `Quasar Framework` • `Telegram WebApp API (vue-tg)` • `Tailwind CSS` • `Vite` • `Pinia` • `HTML5 / CSS3` |
| **Data, Streaming & ML** | `Apache Kafka (KRaft)` • `River ML (Streaming Half-Space Trees)` • `Vector (VRL / ECS)` • `Elasticsearch & Kibana` • `PostgreSQL (asyncpg)` • `Redis` |
| **DevOps & Infrastructure** | `Docker & Docker Compose` • `Nginx (Reverse Proxy & SSL)` • `Linux (Ubuntu, Debian, Astra Linux)` • `OpenVPN / mTLS / PKI` • `Git / GitHub Actions` |
| **Architectural Patterns** | `Clean / Onion Architecture` • `Repository & Service Patterns` • `Zero-Trust Network Segmentation` • `Event-Driven Architecture` • `Hierarchical RBAC` |

</div>

---

### 🤝 How We Can Work Together (Services for Clients)

- **📱 Telegram Mini Apps & Ecosystems:** From wireframes to production-ready TMA with payment gateway integration (YooMoney, Crypto, Telegram Stars), user state management, and push notification bots.
- **🌐 Fullstack Web Apps & SaaS MVPs:** Fast, high-quality development of MVPs, internal admin panels, customer portals, and corporate platforms with clean architecture and responsive UI.
- **⚡ High-Performance APIs & Integrations:** Building scalable RESTful APIs, background task queues, webhook handlers, and third-party system integrations (payment providers, CRM, external APIs).
- **📊 Business Process Automation & Reporting:** Automated generation of executive reports (DOCX/PDF with dynamically generated charts), scheduled data sync, and hardware/network scripting.

---

### 📬 Let's Discuss Your Project!

Have an idea for a Telegram Mini App, web service, or backend platform? Let's connect and discuss how to bring it to life with clean code and reliable architecture.

<p align="center">
  <a href="https://t.me/mrktox">
    <img src="https://img.shields.io/badge/Chat_on_Telegram-@mrktox-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Chat on Telegram" height="40" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/KrayMakso68">
    <img src="https://img.shields.io/badge/GitHub_Profile-KrayMakso68-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile" height="40" />
  </a>
</p>
