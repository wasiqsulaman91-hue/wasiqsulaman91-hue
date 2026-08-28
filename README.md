<div align="center">

<!-- SPIDERMAN THEMED GLOWING HEADER SVG BANNER -->
<svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Gradient -->
    <radialGradient id="spiderBg" cx="50%" cy="50%" r="75%" fx="50%" fy="50%">
      <stop offset="0%" stop-color="#1b0307" />
      <stop offset="50%" stop-color="#090a14" />
      <stop offset="100%" stop-color="#030305" />
    </radialGradient>

    <!-- Crimson Spider Glow -->
    <radialGradient id="redGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </radialGradient>

    <!-- Blue Spider Glow -->
    <radialGradient id="blueGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00d2ff" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#00d2ff" stop-opacity="0"/>
    </radialGradient>

    <!-- Linear Gradient for Text Glow -->
    <linearGradient id="spideyTextGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff1e43">
        <animate attributeName="stop-color" values="#ff1e43; #00d2ff; #ff1e43" dur="6s" repeatCount="indefinite" />
      </stop>
      <stop offset="50%" stop-color="#ffffff">
        <animate attributeName="stop-color" values="#ffffff; #ff0055; #ffffff" dur="6s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#0088ff">
        <animate attributeName="stop-color" values="#0088ff; #ff1e43; #0088ff" dur="6s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <!-- Spider Web Pattern -->
    <pattern id="webPattern" width="80" height="80" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 40 80 M 0 40 L 80 40 M 0 0 L 80 80 M 0 80 L 80 0" stroke="#ff003c" stroke-width="0.6" stroke-opacity="0.15" />
      <circle cx="40" cy="40" r="15" fill="none" stroke="#00d2ff" stroke-width="0.5" stroke-opacity="0.2"/>
      <circle cx="40" cy="40" r="30" fill="none" stroke="#ff003c" stroke-width="0.5" stroke-opacity="0.15"/>
    </pattern>

    <!-- Glowing Filter -->
    <filter id="neonGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="blur1" />
      <feGaussianBlur stdDeviation="20" result="blur2" />
      <feMerge>
        <feMergeNode in="blur2" />
        <feMergeNode in="blur1" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>

    <filter id="subtleGlow">
      <feGaussianBlur stdDeviation="3" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
  </defs>

  <!-- Base Card -->
  <rect width="800" height="220" rx="16" fill="url(#spiderBg)" stroke="#2a0812" stroke-width="2"/>
  <rect width="800" height="220" rx="16" fill="url(#webPattern)"/>

  <!-- Animated Glowing Orbs (Live Wallpaper Vibe) -->
  <circle cx="150" cy="110" r="120" fill="url(#redGlow)">
    <animate attributeName="cx" values="100; 250; 100" dur="8s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.5; 0.9; 0.5" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="650" cy="110" r="140" fill="url(#blueGlow)">
    <animate attributeName="cx" values="700; 550; 700" dur="9s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.6; 1; 0.6" dur="5s" repeatCount="indefinite" />
  </circle>

  <!-- Animated Web Lines -->
  <path d="M 0,0 Q 400,180 800,0" fill="none" stroke="#ff0044" stroke-width="1.5" stroke-opacity="0.4" filter="url(#subtleGlow)">
    <animate attributeName="stroke-opacity" values="0.2; 0.8; 0.2" dur="3s" repeatCount="indefinite" />
  </path>
  <path d="M 0,220 Q 400,40 800,220" fill="none" stroke="#00aaff" stroke-width="1.5" stroke-opacity="0.4" filter="url(#subtleGlow)">
    <animate attributeName="stroke-opacity" values="0.8; 0.2; 0.8" dur="3s" repeatCount="indefinite" />
  </path>

  <!-- Spiderman Emblem SVG Centered -->
  <g transform="translate(376, 30) scale(0.7" filter="url(#neonGlow)">
    <!-- Spider Logo Silhouette -->
    <path d="M24 0 C22 10 16 18 0 22 C16 26 22 34 24 48 C26 34 32 26 48 22 C32 18 26 10 24 0 Z" fill="#ff003c" />
  </g>

  <!-- Glowing Title -->
  <text x="400" y="115" text-anchor="middle" font-family="'Segoe UI', Roboto, Helvetica, sans-serif" font-weight="900" font-size="42" fill="url(#spideyTextGrad)" filter="url(#neonGlow)" letter-spacing="3">
    WASIQ SULAMAN
  </text>
  
  <text x="400" y="150" text-anchor="middle" font-family="'Segoe UI', Roboto, sans-serif" font-weight="600" font-size="16" fill="#00d2ff" letter-spacing="4" filter="url(#subtleGlow)">
    COMPUTER ENGINEER · AGENTIC AI ARCHITECT
  </text>

  <text x="400" y="182" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#ff4d6d" opacity="0.9">
    "WITH GREAT POWER COMES GREAT CODE" 🕸️
  </text>
</svg>

<br/>

<!-- SPIDER-SUIT BADGES & SOCIAL LINKS -->
<a href="https://linkedin.com">
  <img src="https://img.shields.io/badge/LinkedIn-CONNECT-005A9C?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117&color=0077b5" alt="LinkedIn"/>
</a>
<a href="https://github.com/wasiqsulaman91-hue">
  <img src="https://img.shields.io/badge/GitHub-PROFILE-E62429?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117&color=e62429" alt="GitHub"/>
</a>
<a href="mailto:wasiqsulaman@gmail.com">
  <img src="https://img.shields.io/badge/Email-CONTACT-FF003C?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117&color=ff003c" alt="Email"/>
</a>

</div>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=FF003C&center=true&vCenter=true&width=650&lines=Building+Fast%2C+Scalable+%26+Intelligent+AI+Agents...;Crafting+O(1)+Data+Structures+%26+3NF+Databases...;WebRTC+Voice+Pipelines+%2B+Groq+LLM+Inference;Welcome+to+the+Spider-Verse+of+Engineering!+🕸️" alt="Typing SVG" />
</p>

---

## 🕷️ About The Web Slinger

```
  ┌──────────────────────────────────────────────────────────────────────────┐
  │  Identity     :: Wasiq Sulaman                                           │
  │  Origin       :: Pakistan (Computer Engineering · 5th Semester)           │
  │  Core Motto   :: "With Great Computation Power Comes Great Code Structure"│
  │  Specialty    :: Agentic Voice AI, System Performance & Relational DBMS  │
  └──────────────────────────────────────────────────────────────────────────┘
```

I'm a **Computer Engineering Student** driven by a core objective: **How do we engineer software that is ultra-fast, scalable, and genuinely autonomous?**

My journey swings between low-level fundamentals—such as hand-crafted data structures and 3NF database design—and cutting-edge **Agentic & Voice AI Systems**. I translate core computer science theory directly into production-ready code.

* 🧠 **Agentic & Voice AI** — Designing real-time, low-latency conversational agents with custom function-calling pipelines, WebRTC integration, and local GUI synchronization.
* 🗄️ **Database Systems** — Architecting relational schemas normalized to 3NF, managing ACID transaction safety, and optimizing high-speed SQL queries.
* ⚡ **Data Structures & Algorithms** — Handcrafting $O(1)$ and $O(\log N)$ algorithms in C++ without relying strictly on standard library wrappers.

---

## ⚡ Web-Tech Arsenal (Tech Stack)

<div align="center">

| Core Domain | Technologies & Frameworks |
| :--- | :--- |
| **<font color="#ff003c">🔴 Languages</font>** | `Python` · `C++17` · `Java 21` · `SQL` |
| **<font color="#00d2ff">🔵 AI & Voice AI</font>** | `LiveKit` · `Groq API` · `LLM Integration` · `Function Calling` · `Sentence Transformers` |
| **<font color="#ff003c">🔴 Data & Architecture</font>** | `MySQL` · `Relational Schema Design` · `3NF Normalization` · `ACID Transactions` |
| **<font color="#00d2ff">🔵 GUI & Frontend</font>** | `Tkinter` · `JavaFX` · `SFML 3` · `HTML5 / CSS3` |
| **<font color="#ff003c">🔴 Developer Tools</font>** | `Git` · `GitHub` · `VS Code` · `CLion` · `PyCharm` · `N8N` |
| **<font color="#00d2ff">🔵 Engineering Concepts</font>** | `DSA` · `DBMS` · `OOP` · `Agentic Workflows` · `System Architecture` |

</div>

---

## 🕸️ Featured Spider-Projects

<table border="0">
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🍔 1. Hardee's AI Voice Ordering & Reservation Agent</h3>
      <p><code>Python</code> · <code>LiveKit</code> · <code>Groq API</code> · <code>Agentic AI</code> · <code>Web GUI</code></p>
      <p>A real-time, bidirectional conversational AI voice agent customized for Hardee's drive-thru ordering and reservation system, synced with a live web dashboard.</p>
      <ul>
        <li><b>Low Latency Voice Pipeline:</b> Powered by LiveKit's WebRTC infrastructure.</li>
        <li><b>Groq LLM & Tools:</b> Ultra-fast inference with dynamic function calling (price computation, reservation validation, UI state updates).</li>
      </ul>
      <p><a href="https://github.com/wasiqsulaman91-hue"><b>→ View Repository</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">💼 2. Vertex — Job Portal Management System</h3>
      <p><code>Python</code> · <code>MySQL</code> · <code>Tkinter</code> · <code>DBMS</code></p>
      <p>A full-featured recruitment desktop application simulating complete hiring pipelines across dedicated Admin and Applicant roles.</p>
      <ul>
        <li><b>Database Architecture:</b> 5 normalized tables in 3NF with abstract views.</li>
        <li><b>Security & Integrity:</b> Parameterized queries preventing SQL injection, SHA-256 password hashing, and explicit <code>COMMIT</code>/<code>ROLLBACK</code> transactions.</li>
      </ul>
      <p><a href="https://github.com/wasiqsulaman91-hue/Job-Portal-Database-Management-System-Python-Based-"><b>→ View Repository</b></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🐍 3. Snake Game — Custom DSA Edition</h3>
      <p><code>C++17</code> · <code>SFML</code> · <code>Data Structures</code></p>
      <p>A performance-focused classic Snake Game implemented entirely using hand-crafted data structures without standard library wrappers for core logic.</p>
      <ul>
        <li><b>$O(1)$ Linked List:</b> Body movement backed by a custom Doubly Linked List.</li>
        <li><b>Grid Lookup:</b> Input buffering via Circular Queue and 2D Array collision matrix guarantee 60 FPS gameplay.</li>
      </ul>
      <p><a href="https://github.com/wasiqsulaman91-hue/Snake-Game"><b>→ View Repository</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🌐 4. Social Network Suggestion Engine</h3>
      <p><code>C++17</code> · <code>SFML 3</code> · <code>Graph Theory</code></p>
      <p>An interactive, visual graph analyzer that computes real-time "People You May Know" recommendations on an SFML canvas.</p>
      <ul>
        <li><b>Graph Data Structure:</b> Custom Adjacency List representing user networks.</li>
        <li><b>2-Level BFS Search:</b> Bounded Breadth-First Search using a custom FIFO Queue and dynamic Selection Sort ranking.</li>
      </ul>
      <p><a href="https://github.com/wasiqsulaman91-hue/Snake-Game"><b>→ View Repository</b></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">📚 5. Library Management System</h3>
      <p><code>Java 21</code> · <code>JavaFX</code> · <code>OOP Patterns</code></p>
      <p>A clean, dark-themed administrative dashboard applying robust Object-Oriented Design Patterns.</p>
      <ul>
        <li><b>Design Patterns:</b> Singleton Pattern for state management and Polymorphism (<code>User -> Student/Librarian</code>).</li>
        <li><b>$O(1)$ Hash Lookups:</b> Bound directly to reactive JavaFX TableView displays.</li>
      </ul>
      <p><a href="https://github.com/wasiqsulaman91-hue/Library-Management-System"><b>→ View Repository</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🤖 6. Personal AI Interactive Persona</h3>
      <p><code>Python</code> · <code>Groq API</code> · <code>Prompt Engineering</code></p>
      <p>A conversational AI assistant trained on my academic background, projects, and skill set to answer visitor questions dynamically.</p>
      <ul>
        <li><b>Multi-Turn Context:</b> High-speed Groq Llama/Mixtral endpoints with custom memory buffer handling.</li>
        <li><b>Interactive Resume Bot:</b> Real-time answers to technical recruiter queries.</li>
      </ul>
      <p><a href="https://github.com/wasiqsulaman91-hue"><b>→ View Repository</b></a></p>
    </td>
  </tr>
</table>

---

## 🌀 Agentic AI Neural Web

```
      🕷️ SPIDER-AGENTIC ARCHITECTURE
      
      ┌────────────────┐      (WebRTC / LiveKit)      ┌──────────────────┐
      │  Voice Input   │  ─────────────────────────►  │  Groq LLM Engine │
      └───────┬────────┘                              └────────┬─────────┘
              │                                                │
              │ (STT Streaming)                                │ (Function Call)
              ▼                                                ▼
      ┌────────────────┐                              ┌──────────────────┐
      │ ReAct Reasoning│  ──────── (Execute Tool) ──► │ Python / MySQL   │
      │   Loop (N8N)   │                              │ UI State Update  │
      └────────────────┘                              └──────────────────┘
```

* **🔄 ReAct Loop & Planning:** Structuring systematic Reasoning + Action execution loops.
* **🛠️ Dynamic Function Calling:** Direct Python tool binding with local databases & UI endpoints.
* **⚡ Low-Latency Voice Pipelines:** WebRTC audio streaming coupled with Groq sub-second inference.
* **🔗 Workflow Orchestration:** Autonomous multi-node workflows built with N8N and custom APIs.

---

## 📈 Spider-Verse Activity & Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=wasiqsulaman91-hue&show_icons=true&theme=tokyonight&hide_border=true&title_color=ff003c&icon_color=00d2ff&text_color=ffffff&bg_color=0d1117" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=wasiqsulaman91-hue&layout=compact&theme=tokyonight&hide_border=true&title_color=ff003c&text_color=ffffff&bg_color=0d1117" width="48%" />

</div>

---

<div align="center">

### 🕸️ "With Great Power Comes Great Code" 🕸️

**[LinkedIn](https://linkedin.com)** · **[GitHub](https://github.com/wasiqsulaman91-hue)** · **[Email](mailto:wasiqsulaman@gmail.com)**

</div>
