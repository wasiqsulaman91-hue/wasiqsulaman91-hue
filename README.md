<div align="center">

# Hey, I'm Wasiq 👋

**Computer Engineering Student · 5th Semester · Pakistan**

*Exploring Artificial Intelligence · AI Agents · N8N · Scalable Systems*

---

[![GitHub followers](https://img.shields.io/github/followers/wasiqsulaman91-hue?style=for-the-badge&logo=github&color=181717)](https://github.com/wasiqsulaman91-hue)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com)
<!-- [![Portfolio](https://img.shields.io/badge/Portfolio-Explore-8E44AD?style=for-the-badge&logo=react)](https://github.com/wasiqsulaman91-hue) -->

---

</div>

## 📌 About Me

I'm a Computer Engineering student driven by a core question: **How do we build software that is fast, scalable, and intelligent?** 

My journey spans low-level data structures, relational database architectures, and cutting-edge **Agentic AI** systems. I focus heavily on project-based learning—translating core computer science fundamentals directly into production-ready code.

* 🗄️ **Database Systems** — Relational schema design, 3NF normalization, transactions, and SQL optimization.
* 🧠 **Data Structures & Algorithms** — Hand-crafted O(1)/O(log N) algorithms in C++ and Python without relying strictly on standard libraries.
* 🎙️ **Agentic & Voice AI** — Designing real-time, interactive AI agents with custom tools, low-latency pipelines, and function calling.

---

## 🛠️ Tech Stack

<div align="center">

| Domain | Tools & Technologies |
| :--- | :--- |
| **Languages** | `Python` · `C++17` · `Java 21` · `SQL` |
| **AI & Voice** | `LiveKit` · `Groq API` · `LLM Integration` · `Function Calling` · `Sentence Transformers` |
| **Databases** | `MySQL` · `Relational Schema Design` · `3NF Normalization` |
| **GUI & Frontend** | `Tkinter` · `JavaFX` · `SFML 3` · `HTML/CSS` |
| **Dev Tools** | `Git` · `GitHub` · `VS Code` · `CLION` · `PyCharm` · `N8N` · `Livekit` |
| **Core Concepts** | `DSA` · `DBMS` · `OOP` · `Agentic Workflows` · `System Architecture` |

</div>

---

## 📂 Featured Projects

### 1. 🍔 Hardee's AI Voice Ordering & Reservation Agent
> `Python` · `LiveKit` · `Groq API` · `Agentic AI` · `Web GUI`

**[→ View Repository](https://github.com/wasiqsulaman91-hue)**

A real-time, bidirectional conversational AI voice agent customized for Hardee's drive-thru/ordering and table reservation system, integrated with a local web dashboard interface.

* **What it does:** The agent greets callers, handles complex food orders, places reservations, answers menu queries dynamically, and updates order states on a local interactive web interface in real time.
* **Technical Depth:** Built on top of **LiveKit's WebRTC framework** for ultra-low latency voice pipelines. Leverages **Groq API** inference, custom function-calling tools (order updates, price calculations, reservation checks), and sentence-transformers for fast contextual retrieval.

---

### 2. 💼 Vertex — Job Portal Database Management System
> `Python` · `MySQL` · `Tkinter` · `Database Systems`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Job-Portal-Database-Management-System-Python-Based-)**

A full-featured desktop application designed to simulate an end-to-end recruitment pipeline with dedicated **Admin** and **Applicant** workflows.

* **What it does:** Admins publish job postings, track applicant pipelines, and manage employees. Applicants browse roles, upload cover letters, and track application statuses via real-time notifications.
* **Technical Depth:** Spans **5 normalized tables (3NF)** and abstract SQL views. Implements SHA-256 password hashing, parameterized queries to prevent SQL injections, and explicit explicit `COMMIT`/`ROLLBACK` transaction safety.

---

### 3. 🐍 Snake Game — DSA Edition
> `C++17` · `SFML` · `Data Structures & Algorithms`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Snake-Game)**

A performance-focused classic Snake Game implemented entirely using hand-crafted data structures to guarantee smooth 60 FPS gameplay.

* **What it does:** Features custom visual gradients, dynamic speed scaling, persistent high-score tracking, and input buffering.
* **Technical Depth:** Body movement is backed by a **Doubly Linked List** ($O(1)$ head/tail operations), input buffering uses a custom **Circular Queue**, and collision detection is driven by a **2D Grid Array** ($O(1)$ lookups). Zero STL wrappers used for core logic.

---

### 4. 🌐 Social Network Suggestion System
> `C++17` · `SFML 3` · `Data Structures & Algorithms`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Snake-Game)**

An interactive, visual graph analyzer that computes **"People You May Know"** recommendations on a live SFML canvas.

* **What it does:** Renders users as graph nodes in real time. Clicking a user highlights immediate connections and ranks potential friend suggestions based on mutual connections.
* **Technical Depth:** Custom **Adjacency List** graph representation. Implements a bounded **2-level Breadth-First Search (BFS)** driven by a custom FIFO Queue, with ranked outputs powered by Selection Sort.

---

### 5. 📚 Library Management System
> `Java 21` · `JavaFX` · `Object-Oriented Programming`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Library-Management-System)**

A clean, dark-themed administrative dashboard applying core Object-Oriented Design Patterns.

* **What it does:** Manages catalog inventories, tracks student requests in real-time through notification bells, and handles book issues/returns.
* **Technical Depth:** Leverages the **Singleton Pattern** for data persistence, **Polymorphism** (`User -> Student/Librarian`), **MVC Architecture**, and `HashMap` lookups ($O(1)$ access) bound to reactive JavaFX `TableView` elements.

---

### 6. 🤖 Personal AI Interactive Persona
> `Python` · `Groq API` · `LLM Integration`

A conversational AI assistant trained on my academic background, projects, and skill set to answer visitor questions dynamically.

* **What it does:** Serves as an interactive, real-time "About Me" resume bot capable of handling multi-turn queries about my work.
* **Technical Depth:** Powered by Groq's high-speed Llama/Mixtral endpoints, system prompt engineering, and conversational state management.

---

## 🧠 Agentic AI Exploration

I am heavily interested in autonomous AI workflows where models reason, plan, and call tools. Key areas I experiment with:

> 🔄 **ReAct Framework** — Structuring prompts for systematic Reasoning + Acting cycles.  
> 🛠️ **Function Calling** — Enabling LLMs to execute Python functions, query local databases, and update external UI endpoints.  
> ⚡ **Voice AI Pipelines** — Combining STT, fast LLM inference (Groq), and TTS via WebRTC (LiveKit) for real-time human-agent interaction.  
> 🔗 **Workflow Automation** — Building multi-node agentic pipelines using **N8N** and custom APIs.

---

## 📈 Activity & Stats

<div align="center">

<!-- ![Wasiq's GitHub Stats](https://github-readme-stats.vercel.app/api?username=wasiqsulaman91-hue&show_icons=true&theme=tokyonight&hide_border=true) -->
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=wasiqsulaman91-hue&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

### 🤝 Let's Connect & Build!

**[GitHub](https://github.com/wasiqsulaman91-hue)** · **[Email](mailto:wasiqsulaman@gmail.com)**

</div>
