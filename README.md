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
| **GUI / Frontend** | Tkinter |
| **AI / APIs** | Groq API · LLM Integration · Agentic AI |
| **Tools** | Git · GitHub · PyCharm · VS Code |
| **Concepts** | DSA · DBMS · OOP · Normalization · Agentic Workflows |

---

## 📂 Projects

### 1. 💼 Vertex — Job Portal Database Management System
> `Python` · `MySQL` · `Tkinter` · `Database Systems`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Job-Portal-Database-Management-System-Python-Based-)**

A full-featured, desktop-based Job Portal built as a 4th Semester **Database Systems (DBS)** project. This is the most comprehensive project in the portfolio — it demonstrates real-world application of relational database design wired to a polished graphical interface.

**What it does:**

The system simulates a complete hiring pipeline with two distinct user roles. **Admins** can post job listings, review incoming applications, update applicant statuses, and manage an employee workforce — including hiring and firing. **Applicants** can browse open positions, submit applications with cover letters, and receive real-time in-app notifications when their status changes.

**Technical depth:**

The database (`job_portal_db`) is built across **5 relational tables** and **1 SQL view**, demonstrating:
- Schema normalization up to **3NF** with primary and foreign key constraints
- **ENUM types** to restrict status fields to valid domain values
- **Composite UNIQUE constraints** to prevent duplicate applications
- A `CREATE OR REPLACE VIEW` (`vw_employees`) to abstract complex JOIN queries
- **SHA-256 password hashing** for secure credential storage
- **Parameterized queries** to prevent SQL injection
- **Transaction management** with explicit `commit/rollback` cycles

The Python codebase is cleanly layered — the Data Access Layer (`databasecode.py`), connection config (`databaseconnection.py`), and reusable UI components (`widgets.py`) are all separated from the dashboard logic, reflecting good software architecture principles.

---

### 2. 🐍 Snake Game — DSA-Based C++ Project
> `C++` · `Data Structures & Algorithms`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Snake-Game)**

A classic Snake Game implemented in C++ as a hands-on exercise in **Data Structures & Algorithms**. The project was built specifically to understand the practical application of fundamental data structures in a real, interactive program.

**What it does:**

The game runs a fully functional Snake experience in the terminal — the snake grows as it consumes food, navigates the grid, and the game ends upon collision. More importantly, the project was designed as a *learning artifact*: each data structure used was chosen deliberately to demonstrate how the right structure impacts both correctness and performance.

**Technical depth:**

- Uses **linked list / queue** semantics to model the snake's body — each new segment is appended, and the tail is removed on movement, making it a natural fit for queue-based thinking
- Demonstrates **collision detection** logic using coordinate tracking
- Explores **game loop architecture** and state management in a low-level, non-framework environment
- Written in C++ to reinforce memory management awareness and pointer-based thinking

This project is a testament to the principle that **DSA is not just theory** — even something as simple as a snake game becomes a vehicle for understanding why queues, stacks, and linked lists exist.

---

### 3. 📚 Library Management System
> `Java` · `Object-Oriented Programming`

**[→ View Repository](https://github.com/wasiqsulaman91-hue/Library-Management-System)**

A Library Management System built in **Java**, demonstrating object-oriented design principles applied to a real administrative problem. The system handles the core operations of a library — managing books, borrowers, and transactions.

**What it does:**

The system allows librarians to manage a catalogue of books, register members, issue and return books, and track the overall state of the library's inventory. It models the domain cleanly using classes and objects, reflecting the entities that naturally exist in a real library setting.

**Technical depth:**

- Designed around **OOP principles** — encapsulation, inheritance, and abstraction are applied to model Books, Members, and Transactions as distinct, interacting entities
- Demonstrates **CRUD operations** (Create, Read, Update, Delete) on in-memory data structures
- Reinforces Java fundamentals including collections, exception handling, and class design
- Serves as a bridge project between academic OOP coursework and applied system design

---

### 4. 🤖 Personal AI Bot — Powered by Groq API
> `Python` · `Groq API` · `LLM Integration` · `Agentic AI`

A conversational AI bot built using the **Groq API** that acts as an intelligent, interactive version of me. Instead of the usual static "About Me" page, this bot lets anyone ask questions and get dynamic, contextually relevant answers about my background, skills, projects, and interests — all powered by a large language model running at Groq's ultra-fast inference speeds.

**What it does:**

The bot is primed with a detailed system prompt that encapsulates my academic profile, technical skills, project experience, and personality. A visitor can ask it anything — *"What has Wasiq built?"*, *"What programming languages does he know?"*, *"Is he open to collaboration?"* — and receive coherent, accurate, human-like responses in real time.

**Technical depth:**

- Integrates with the **Groq Cloud API**, leveraging models like `llama3` or `mixtral` for blazing-fast inference with minimal latency
- Uses a **system prompt engineering** approach to ground the model's persona — a practical demonstration of how context windows and role-based prompting shape LLM behaviour
- Explores **Agentic AI** patterns: the model doesn't just answer in isolation — it reasons about the question, determines what information is relevant from its context, and formulates a coherent response, simulating lightweight agentic decision-making
- Demonstrates understanding of the **LLM API request/response lifecycle** — constructing messages, managing conversation history, and handling streaming responses

This project sits at the frontier of what I'm currently building — bridging traditional software engineering with the emerging paradigm of **AI-native applications**.

---

## 🧠 Agentic AI — What I've Explored

Agentic AI refers to systems where a language model doesn't merely respond to a single prompt, but **reasons, plans, and takes sequential actions** to accomplish a goal. My exploration in this space includes:

- Understanding the **ReAct (Reason + Act)** pattern — where the model alternates between thinking and taking actions
- Building LLM pipelines where the model can **call tools**, process their outputs, and decide next steps autonomously
- Working with **Groq's inference API** as the backbone for fast, low-latency agentic loops
- Experimenting with **prompt chaining** and **context management** to maintain coherent state across multi-step interactions

This is an evolving area of my skillset — and one I'm deeply invested in as AI engineering becomes a core discipline in software development.

---

## 📊 GitHub Stats

<div align="center">

![Wasiq's GitHub Stats](https://github-readme-stats.vercel.app/api?username=wasiqsulaman91-hue&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=wasiqsulaman91-hue&layout=compact&theme=github_dark&hide_border=true)

</div>

---

## 🚀 Currently Working On

- Deepening my understanding of **query optimization** and **indexing strategies** in relational databases
- Strengthening algorithmic problem-solving through competitive programming practice
- Advancing my **Agentic AI** experiments — building more sophisticated tool-calling pipelines with Groq
- Exploring **AI/ML fundamentals** to understand where engineering meets intelligence at a deeper level

---

## 📬 Let's Connect

I'm always open to connecting with fellow students, developers, and anyone passionate about technology.

[![GitHub](https://img.shields.io/badge/GitHub-wasiqsulaman91--hue-181717?style=flat-square&logo=github)](https://github.com/wasiqsulaman91-hue)

---

<div align="center">

*"First, solve the problem. Then, write the code."* — John Johnson

</div>
