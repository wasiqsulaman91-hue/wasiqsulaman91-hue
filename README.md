<div align="center">

# Hey, I'm Wasiq Sulaman 👋

**Computer Engineering Student · 4th Semester · Pakistan**

*Exploring the intersection of Artificial Intelligence, Database Systems & Algorithms*

</div>

---

## About Me

I'm a second-year Computer Engineering student with a fervent curiosity for how data is **structured, stored, and retrieved** at scale. My academic journey currently revolves around two pillars:

- 🗄️ **Database Systems** — Relational design, normalization, SQL, and transaction management
- 🧠 **Data Structures & Algorithms** — Building efficient, well-reasoned solutions in C++ and Python
- 🤖 **Artificial Intelligence** — Actively exploring the AI landscape, with hands-on experience in **Agentic AI** and **LLM API integration**

I believe the best way to learn is to **build things that work** — so every concept I study finds its way into a project.

---

## 🛠️ Tech Stack

| Domain | Technologies |
|---|---|
| **Languages** | Python · C++ · Java · SQL |
| **Database** | MySQL · Relational Schema Design |
| **GUI / Frontend** | Tkinter · JavaFX · SFML |
| **AI / APIs** | Groq API · LLM Integration · Agentic AI |
| **Tools** | Git · GitHub · PyCharm · VS Code · CLion |
| **Concepts** | DSA · DBMS · OOP · Normalization · Agentic Workflows |

---

## 📂 Projects

---

### 1. 💼 Vertex — Job Portal Database Management System
> `Python` · `MySQL` · `Tkinter` · `Database Systems`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Job-Portal-Database-Management-System-Python-Based-)**

A full-featured, desktop-based Job Portal built as a 4th Semester **Database Systems (DBS)** project. Simulates a complete hiring pipeline with two distinct user roles — **Admin** and **Applicant** — each with their own dashboard.

**What it does:** Admins post job listings, review applications, update statuses, and manage an employee workforce. Applicants browse positions, submit applications with cover letters, and receive real-time in-app notifications when their status changes.

**Technical depth:** The database (`job_portal_db`) spans **5 relational tables** and **1 SQL view**, demonstrating schema normalization (3NF), ENUM types, composite UNIQUE constraints, a `CREATE OR REPLACE VIEW` to abstract complex JOINs, SHA-256 password hashing, parameterized queries (SQL injection prevention), and explicit `commit/rollback` transaction management.

---

### 2. 🐍 Snake Game — DSA Edition
> `C++17` · `SFML` · `Data Structures & Algorithms`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Snake-Game)**

A classic Snake Game in C++ built specifically to understand how the right data structure impacts both correctness and performance in a real, interactive program.

**What it does:** A fully functional Snake experience with gradient visuals, pulsing food, speed ramp-up per food eaten, persistent high score, and input buffering — all running at 60 FPS via SFML.

**Technical depth:** The snake body is modelled as a **Doubly Linked List** (`push_front` / `pop_back` O(1)), direction inputs are buffered in a **Circular Queue**, and collision detection uses a **2D Grid array** for O(1) occupancy lookups — every structure is hand-crafted, no STL wrappers.

---

### 3. 📚 Library Management System
> `Java 21` · `JavaFX` · `Object-Oriented Programming`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Library-Management-System)**

A desktop Library Management System in Java demonstrating OOP design patterns applied to a real administrative workflow, with a dark-themed JavaFX interface.

**What it does:** Librarians manage a book catalogue, approve or reject student borrow requests (via a live notification bell), and monitor inventory. Students browse books, submit borrow requests, and return books directly from their dashboard.

**Technical depth:** Built on a **Singleton** data store, **Inheritance/Polymorphism** (`User → Student, Librarian`), **MVC** (FXML + Controllers), and **JavaFX Observable Properties** that auto-refresh `TableView` nodes on any data change. Book and user lookups use `HashMap<String, T>` for O(1) access.

---

### 4. 🌐 Social Network Suggestion System
> `C++17` · `SFML 3` · `Data Structures & Algorithms`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Snake-Game)**

An interactive, visually-rendered Social Network Analyzer that computes **"People You May Know"** recommendations in real time — built entirely with hand-crafted data structures; no STL containers used for core logic.

**What it does:** Users are vertices in an undirected graph rendered on a live SFML canvas. Click any node to select it — the sidebar instantly shows their friends list and ranked suggestions. Nodes are color-coded: 🔵 active user, 🟢 direct friends, 🟡 suggested users, ⚪ unrelated.

**Technical depth:** The graph is represented as a **master linked list of UserNodes**, each with a **singly linked adjacency list** of FriendNodes. The suggestion engine runs a **2-level BFS-bounded traversal** — for each direct friend, it walks their friend list, filters out existing connections, and increments a mutual-count array (O(1) lookup). Results are ranked with **Selection Sort** (descending by mutual count). A **custom FIFO Queue** (built from scratch with `QueueNode*` front/rear pointers) drives the BFS layer.

---

### 5. 🤖 Personal AI Bot — Powered by Groq API
> `Python` · `Groq API` · `LLM Integration` · `Agentic AI`

A conversational AI bot that acts as an intelligent, interactive version of me — powered by the **Groq API**. Instead of a static "About Me" page, visitors can ask it anything and get dynamic, contextually relevant answers about my background, skills, and projects.

**What it does:** Primed with a detailed system prompt encapsulating my academic profile and experience, the bot answers questions like *"What has Wasiq built?"* or *"Is he open to collaboration?"* with coherent, human-like responses at Groq's ultra-fast inference speeds.

**Technical depth:** Integrates with the **Groq Cloud API** (Llama 3 / Mixtral), uses **system prompt engineering** to ground the model's persona, manages **conversation history** for multi-turn coherence, and explores **Agentic AI** patterns — the model reasons about each question, determines what context is relevant, and formulates a response, simulating lightweight agentic decision-making.

---

## 🧠 Agentic AI — What I've Explored

Agentic AI refers to systems where a language model **reasons, plans, and takes sequential actions** to accomplish a goal. My exploration includes:

- The **ReAct (Reason + Act)** pattern — alternating between thinking and taking tool-based actions
- Building LLM pipelines where the model **calls tools**, processes outputs, and decides next steps autonomously
- Working with **Groq's inference API** as the backbone for fast, low-latency agentic loops
- Experimenting with **prompt chaining** and **context management** to maintain coherent state across multi-step interactions

---

## 🚀 Currently Working On

- Deepening my understanding of **query optimization** and **indexing strategies** in relational databases
- Strengthening algorithmic problem-solving through competitive programming practice
- Advancing **Agentic AI** experiments — building more sophisticated tool-calling pipelines with Groq
- Exploring **AI/ML fundamentals** to understand where engineering meets intelligence at a deeper level

---

## 📬 Let's Connect

[![GitHub](https://img.shields.io/badge/GitHub-wasiqsulaman91--hue-181717?style=flat-square&logo=github)](https://github.com/wasiqsulaman91-hue)
