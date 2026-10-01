<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1120,40:0f4c81,80:0284c7,100:00f2fe&height=220&section=header&text=Mohamed%20Khaled&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=Software%20Engineer%20%E2%80%A2%20Backend%20Architect%20%E2%80%A2%20Competitive%20Programmer&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

  <!-- TYPING ANIMATION -->
  <a href="https://github.com/MohamedKhaled217">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=00F2FE&center=true&vCenter=true&width=800&lines=Engineering+low-latency+backends;Crafting+real-time+distributed+platforms+with+Next.js%2C+SignalR+%26+Redis;Architecting+clean%2C+maintainable+domains+and+modular+APIs;1%2C000%2B+algorithmic+challenges+mastered+on+LeetCode+%26+Codeforces;" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="https://linkedin.com/in/mohamedkhaled21" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    &nbsp;
    <a href="https://leetcode.com/u/MohamedKhaleddd" target="_blank">
      <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
    </a>
    &nbsp;
    <a href="mailto:mohamedkhaleed217@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
    &nbsp;
    <a href="https://github.com/MohamedKhaled217">
      <img src="https://komarev.com/ghpvc/?username=MohamedKhaled217&label=Profile%20Views&color=00f2fe&style=for-the-badge" alt="Profile views"/>
    </a>
  </p>
</div>

---

### ⚡ Professional Summary

```csharp
public sealed record SoftwareEngineer
{
    public string Name             => "Mohamed Khaled";
    public string Degree           => "B.Eng. in Computer Engineering (Honors) — Port Said Univ. '26";
    public string[] CoreStack      => [".NET 8 / ASP.NET Core", "NodeJs","Next.js 14 / TypeScript", "PostgreSQL", "Redis"];
    public string[] Specialization => ["Clean Architecture", "Distributed Caching", "Real-Time / SignalR", "RESTful APIs"];
    public string ProblemSolving   => "1,000+ Algorithmic Solutions on Codeforces & LeetCode";
}
```

> 💡 **Core Engineering Tenet:**  
> *“Software excellence is the union of mathematical rigour, sub-millisecond execution, and unyielding architectural discipline.”*  
> Specializing in high-throughput backend services, real-time event-driven applications, and resilient domain-centric architectures.

---

### 🏛️ Engineering Competencies

<table>
<tr>
<td valign="top" width="33%">

#### ⚙️ Distributed & Backend Systems
- **ASP.NET Core & .NET 8 (C#)**: High-throughput async Web APIs, middleware pipelines, and background workers.
- **Clean Architecture & DDD**: Strict layer separation, Unit of Work, Repository Pattern, and FluentValidation.
- **Real-Time Streaming**: SignalR WebSockets for bi-directional, sub-100ms client-server state synchronization.
- **Microservices & Messaging**: Event-driven patterns, pub/sub queues, and distributed cache topologies.

</td>
<td valign="top" width="33%">

#### 🌐 Modern Full-Stack & Mobile
- **Next.js & React (TypeScript)**: Server-side rendering (SSR), static site generation, and optimized client hydrates.
- **Cross-Platform Mobile (Flutter / Dart)**: Reactive architecture, state management (Provider), and native bridges.
- **Python & Django Framework**: Secure authentication pipelines, ORM optimization, and REST API development.
- **Node.js & Express**: High-concurrency event-loop services, custom rate-limiting, and security filters.

</td>
<td valign="top" width="33%">

#### 🗄️ Database & Cloud Infrastructure
- **Relational Databases (PostgreSQL / SQL)**: Query optimization, index strategies, transaction isolation, and EF Core.
- **In-Memory Datastores (Redis)**: Low-latency caching, session orchestration, and distributed locks.
- **NoSQL Datastores (MongoDB)**: Aggregation pipelines, sharding principles, and document-level locking.
- **Cloud & Tooling**: Cloudflare R2 object storage, Git CI workflows, Linux CLI, and container foundations.

</td>
</tr>
</table>

---

### 🚀 Featured Engineering Projects

<table>
  <!-- Row 1: Checkiski & E-Platform -->
  <tr>
    <td width="50%" valign="top">
      <h3>♟️ Checkiski — High-Performance Multiplayer Chess</h3>
      <p><i>Sub-100ms low-latency online chess platform driven by an original, zero-dependency C# chess engine.</i></p>
      <ul>
        <li><b>Engineered Custom Chess Engine:</b> Built 100% of game-state evaluation from scratch in C#, handling move generation, pinned piece detection, checkmate/stalemate scenarios, en-passant, and castling without external libraries.</li>
        <li><b>Real-Time Event Architecture:</b> Integrated ASP.NET Core SignalR with Redis pub/sub matchmaking, achieving &lt;100ms sync latency and slashing database query contention by 40%.</li>
        <li><b>Enterprise Security:</b> Secured with stateless JWT authorization and distributed rate-limiting, tested for 1,000+ concurrent players.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=signal&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🎓 E-Platform — Distributed Educational Ecosystem</h3>
      <p><i>Scalable educational infrastructure centralizing digital courses, asynchronous exams, and media streaming.</i></p>
      <ul>
        <li><b>Direct Media Delivery Pipeline:</b> Implemented Cloudflare R2 presigned direct-to-bucket uploads with server-side processing, completely bypassing API server bandwidth bottlenecks.</li>
        <li><b>High-Throughput Backing Services:</b> Developed modular .NET backend workflows coupled with PostgreSQL query optimizations and multi-layer Redis caching.</li>
        <li><b>Role-Based Access Governance:</b> Comprehensive RBAC architecture governing students, instructors, and system administrators with auditable transaction histories.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      </p>
    </td>
  </tr>

  <!-- Row 2: Kemora & Student Hub -->
  <tr>
    <td width="50%" valign="top">
      <h3>📱 Kemora — Cross-Platform Clean Architecture Platform</h3>
      <p><i>Full-stack mobile solution engineered with strict Domain-Driven Design (DDD) principles.</i></p>
      <ul>
        <li><b>Domain Decoupling:</b> Implemented Clean Architecture in .NET Core utilizing Entity Framework Core, Repository & Unit-of-Work patterns, and FluentValidation error boundaries.</li>
        <li><b>Reactive Client Engine:</b> Developed a responsive Flutter mobile client utilizing Provider for state predictability and robust functional error handling.</li>
        <li><b>Infrastructure Automation:</b> Scripted automated SQL and PowerShell tooling for seamless deterministic database seeding and migrations.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
        <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/>
        <img src="https://img.shields.io/badge/.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
        <img src="https://img.shields.io/badge/Clean_Architecture-009688?style=flat-square&logo=diagram&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ Student Hub — Academic Networking & Moderation Hub</h3>
      <p><i>High-concurrency academic community platform featuring automated content moderation middleware.</i></p>
      <ul>
        <li><b>Automated Inspection Pipeline:</b> Built custom Express.js middleware using dynamic string tokenization to enforce content moderation and banned-word filtering with 99% accuracy.</li>
        <li><b>Resilient Session Engine:</b> Managed 500+ simultaneous user sessions reliably through optimized Node.js connection pools and MongoDB clustering.</li>
        <li><b>Administrative Dashboard:</b> Real-time analytics portal providing instant audit logs, user governance, and automated policy enforcement.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white"/>
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      </p>
    </td>
  </tr>
</table>

---

### 🧩 Algorithmic Mastery & Problem Solving

<div align="center">
  <p>
    <img src="https://img.shields.io/badge/Problems_Solved-1000%2B-00f2fe?style=for-the-badge&logo=codeforces&logoColor=black" alt="1000+ Solved"/>
    <img src="https://img.shields.io/badge/Specialty-Data_Structures_%26_Algorithms-0284c7?style=for-the-badge" alt="DSA"/>
    <img src="https://img.shields.io/badge/Platforms-LeetCode_%7C_Codeforces-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="Platforms"/>
  </p>
  <p>
    <i>Proficient in: Graph Theory (Dijkstra, MST, BFS/DFS) • Dynamic Programming • Segment Trees & BIT • Greedy Paradigms • Complex State Evaluation • Time & Space Asymptotic Optimization</i>
  </p>
</div>

---

### 🛠️ Comprehensive Tech Stack

<div align="left">

**Languages & Core Systems**  
<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

**Frameworks, Libraries & Protocols**  
<p>
  <img src="https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js_14-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/SignalR-512BD4?style=for-the-badge&logo=signal&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
</p>

**Databases, Caching & Cloud Infrastructure**  
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cloudflare_R2-F38020?style=for-the-badge&logo=cloudflare&logoColor=white"/>
</p>

**Engineering Tools & Environments**  
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

</div>

---

### 📊 Performance & Analytics

<div align="center">
  <table border="0">
    <tr>
      <td width="50%" align="center">
        <img height="185" src="https://github-readme-stats-ecru-two-16.vercel.app/api?username=MohamedKhaled217&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&title_color=00f2fe&icon_color=00f2fe" alt="GitHub Stats"/>
      </td>
      <td width="50%" align="center">
        <img height="185" src="https://leetcard.jacoblin.cool/MohamedKhaleddd?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode Card"/>
      </td>
    </tr>
  </table>

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MohamedKhaled217&theme=tokyo-night&hide_border=true&color=00f2fe" width="100%" alt="Contribution Graph"/>
</div>

---

### 💼 Professional Journey & Impact

```
├── 🎓 Port Said University | Port Said, Egypt (Expected June 2026)
│   └── Bachelor of Computer Engineering — Very Good with Honors
│       └── Rigorous Core: Data Structures & Algorithms, OOP, Operating Systems, Networks, DBMS
│
├── 👨‍🏫 iSchool | Coding Instructor — Remote (Jun 2024 – Sep 2025)
│   ├── Mentored 500+ students in algorithmic problem-solving & clean software craftsmanship
│   ├── Improved overall cohort technical competence by 40% through structured diagnostic feedback
│   └── Guided 20 student capstones across the full SDLC, ensuring scalable architectural patterns
│
└── 🌐 Information Technology Institute (ITI) | Full-Stack Trainee — Remote (Aug 2024 – Sep 2024)
    ├── Architected and shipped 3 dynamic applications using Python, Django ORM, and RESTful APIs
    ├── Handled 500+ daily requests with robust authentication and structured error boundaries
    └── Accelerated frontend delivery by 25% within an Agile, cross-functional delivery team
```

---

<div align="center">
  <h3>Let's Build Scalable Systems Together</h3>
  <p>Open for Software Engineering opportunities, backend architecture challenges, and impactful collaborations.</p>

  <p>
    <a href="https://linkedin.com/in/mohamedkhaled21" target="_blank">
      <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    &nbsp;&nbsp;
    <a href="mailto:mohamedkhaleed217@gmail.com">
      <img src="https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
    &nbsp;&nbsp;
    <a href="https://leetcode.com/u/MohamedKhaleddd" target="_blank">
      <img src="https://img.shields.io/badge/View_LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
    </a>
  </p>

  <br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f2fe,50:0f4c81,100:0b1120&height=120&section=footer" width="100%"/>
</div>
