# 🧩 Portfolio Showcase  

> 💡 For reviewers: Each project below links to its GitHub repository.

## 🎓 Personal Statement — My Learning Journey as a Developer

When I first began studying software engineering, my projects were small and experimental — a simple online chat system, a few games, without any database.  
Over time, I found myself increasingly fascinated by how structured design and clean architecture could turn scattered ideas into maintainable systems. Each project became a milestone that reflected my growth in both programming logic and problem-solving ability.

Starting from the **Online Chat** project, I learned how network communication and multithreading really work under the hood.  
In the **RacingCar Demo**, I explored real-time physics and basic AI pathfinding — my first taste of performance tuning and system integration.  
Through the **Club Management System**, I discovered the power of database design, transaction control, and backend security.  
Finally, in **Memory Bottle**, I applied everything I had learned to build a full-stack web application from scratch — with a clear architecture, permission control, and a user-centered design aimed at preserving family memories.

Although I often followed online resources or consulted AI tools for syntax and best practices, every decision — from directory structure to REST API design — was made, tested, and refined by myself.  
I consider *Memory Bottle* can be the culmination of my undergraduate journey: a proof that I can design, build, and iterate a real application on my own.

This portfolio is therefore not only a showcase of projects, but also a reflection of my learning process — how I moved from curiosity to understanding, and from understanding to creation.
Above all, these projects remind me that learning to build software is also learning to think — systematically, patiently, and creatively.

---
## 📘 Table of Contents  
- [Overview](#-overview)  
- [Research Interests](#-research-interests)  
- [Project 1: Memory Bottle (Full-Stack Memory Archiving System)](#project-1)
- [Project 2: Java Instant Messaging System (Online-Chat)](#project-2)
- [Project 3: Club Management System (Database Application)](#project-3)
- [Project 4: RacingCar Simulation Game (Unity 3D + AI Pathfinding)](#project-4)
- [Integrated Skills & Future Direction](#-integrated-skills--future-direction)  

---

## 🎯 Overview  

This portfolio presents a collection of software engineering projects that I independently designed and implemented during my undergraduate studies.  
The works cover **full-stack web system design, network communication, database application development, and 3D simulation** —  
demonstrating my integrated abilities in **software architecture, object-oriented programming, data management, and system optimization**,  
as well as my ongoing effort to connect technology with real-world social value.  


### 🧩 Technical Summary  

| Project | Domain | Core Technologies | Focus |
|----------|---------|------------------|--------|
| **Memory Bottle** | Full-Stack Web System | Spring Boot, MySQL, React, RESTful API | End-to-end system design & emotional computing |
| **Online Chat** | Network Programming | Java, TCP/IP, Multi-threading, Swing | Concurrent communication system |
| **Club Manage** | Database Application | SQL Server, JDBC, Power Designer | Transaction & security control |
| **RacingCar Game** | Graphics & Simulation | Unity, C#, Bézier AI Pathfinding | Real-time physics & AI simulation |

---

## 🧠 Research Interests  

My academic interests lie in:  
- **Backend architecture and data persistence design**  
- **Human–computer interaction and frontend usability**  
- **Applications of artificial intelligence and affective computing in human-centered contexts**  

Throughout multiple independent and team projects, I have aimed to use technology to address real human needs.  
This philosophy is best embodied in my flagship project, **Memory Bottle**, a digital memory-preserving platform designed for families affected by memory loss.  

---
<a id="project-1"></a>
## 🌟 Project 1: Memory Bottle (Full-Stack Memory Archiving System)

📸 **Project Screenshot**  
![Memory Bottle Timeline](https://github.com/YXCS-cya/memory-bottle-frontend/blob/main/docs/media/timeline.png)

🔗 **Repositories**  
- [Backend Repository – Spring Boot + MySQL](https://github.com/YXCS-cya/memory-bottle)  
- [Frontend Repository – React + Vite](https://github.com/YXCS-cya/memory-bottle-frontend)

---

### Project Description  
**Memory Bottle** is a digital archiving and emotional-support platform designed for elderly users and families experiencing memory decline or Alzheimer’s.  
It enables users to record, revisit, and interact with personal memories through text and multimedia timelines.  
The backend is built with **Spring Boot + MySQL**, and the frontend with **React + Vite**, forming a complete full-stack system supporting timeline display, media upload, and comment interaction.  
> The full-stack functionality (frontend + backend) was successfully verified locally via API and UI integration.

### System Architecture  
The backend follows a layered structure (Controller / Service / Repository) and exposes RESTful APIs verified via Apifox.  
The frontend operates as a single-page application (SPA) using **Axios** and **Tailwind CSS**, providing an accessible and lightweight interface.  
Core modules include user identity management, permission control, file storage, and timeline data aggregation.  

### Technical Highlights  
- Unified API response model (`Result<T>`) for consistent communication  
- Frontend–backend separation and modular deployment  
- DTO/VO mapping for clean data flow and maintainability  
- Human-centered design addressing emotional well-being and memory preservation  

### Personal Contribution  
I independently designed and implemented the entire system, from architecture and database schema to REST API development and frontend UI logic.  
This project demonstrates my strength in **full-stack development, system integration, and user-experience design**.  

---
<a id="project-2"></a>
## 💬 Project 2: Java Instant Messaging System (Online-Chat)

📸 **Project Screenshot**  
![Online Chat Screenshot](https://github.com/YXCS-cya/Online-Chat/blob/main/docs/friends.png)

🔗 **Repository**  
- [Repository – Java TCP/IP + Multi-threading](https://github.com/YXCS-cya/Online-Chat)

---

### Project Description  
This project implements a multi-threaded instant messaging system using **Java TCP/IP Socket programming**.  
It features a client–server architecture supporting user login, real-time messaging, and local chat history storage.  

### System Architecture  
- **Socket / ServerSocket**-based communication over TCP protocol  
- Independent threads handling multiple clients concurrently  
- Custom message structure (`Message`, `MessageType`) for extensible data packets  
- **Swing** GUI for login, friend list, and chat windows  
- Persistent storage for chat history in local files  

### Technical Highlights  
- Real-time, thread-safe message transmission and routing  
- Object serialization for efficient data exchange  
- Modularized design separating UI, logic, and networking layers  

### Personal Contribution  
I independently built the communication framework, concurrency management, and custom protocol layer.  
The system reflects my understanding of **network programming fundamentals and concurrent system design**.  

---
<a id="project-3"></a>
## 🧩 Project 3: Club Management System (Database Application)

📸 **Project Screenshot**  
![Club Manage Screenshot](https://github.com/YXCS-cya/Club-Manage/blob/main/docs/er-diagram.png)

🔗 **Repository**  
- [Repository – Java + SQL Server + JDBC](https://github.com/YXCS-cya/Club-Manage)

---

### Project Description  
Developed as part of a database systems course, this project implements a **Java + SQL Server**-based management system for student clubs.  
The design strictly follows the **Third Normal Form (3NF)** and emphasizes data integrity and secure transactions.  

### System Architecture  
- Database modeling with **Power Designer**  
- Access via **JDBC** with parameterized queries  
- SQL views, transactions, and index optimization  
- Explicit transaction templates for multi-table operations  

### Technical Highlights  
- View encapsulation for sensitive data protection  
- Parameterized queries preventing SQL injection  
- Indexing and batch processing for performance improvement  
- Deep integration of theoretical database principles and practical engineering  

### Personal Contribution  
I was responsible for database schema design, transaction logic, and query optimization.  
The project showcases my competence in **data modeling, database security, and performance tuning**.  

---
<a id="project-4"></a>
## 🏎️ Project 4: RacingCar Simulation Game (Unity 3D + AI Pathfinding)

📸 **Project Screenshot**  
![Racing Car Demo](https://github.com/user-attachments/assets/4b35ca07-8256-424c-91c6-8615f222be0b)

🔗 **Repository**  
- [Repository – Unity 2022.3 + C# + AI Pathfinding](https://github.com/YXCS-cya/RacingCar-GameDemo)

---

### Project Description  
This Unity-based racing simulation integrates **AI pathfinding** and **physics simulation** to create dynamic 3D driving environments.  
As project manager and core developer, I implemented all control scripts, AI logic, and system debugging.  

### Technical Implementation  
- Vehicle physics using **WheelCollider** and suspension tuning  
- **Cubic Bézier curves** for AI route generation  
- Decoupled update cycles with `FixedUpdate()` (physics) and `LateUpdate()` (camera)  
- Multiple camera perspectives: third-person, side, and aerial views  

### Technical Highlights  
- Application of curve algorithms to AI path tracking  
- Performance optimization through model and collider adjustments  
- Combination of graphics, physics, and AI logic in one simulation system  

### Personal Contribution  
I independently developed the AI tracking and physics modules while coordinating model integration.  
The project reflects my skills in **computer graphics, game mechanics, and real-time system optimization**.  

---

## 🧭 Integrated Skills & Future Direction  

Through these projects, I have cultivated a foundation centered on **system architecture and full-stack development**,  
while exploring the intersection of **AI technologies and human-oriented applications**.  

In my postgraduate studies,  
I aim to further investigate **artificial intelligence, data systems, and human–computer interaction**,  
and to apply computing technologies to enhance human well-being — particularly in the preservation of memory, emotion, and connection.  

<br>

---

> Technology’s true value lies not only in innovation but in empathy and understanding.  
> I aspire to continue bridging technology with humanity through meaningful, socially impactful computing.

Looking back on those projects above, I feel truly grateful for my entire journey from learning to practice.   
Thanks to this period: 2024.4 – Online Chat → 2024.11 – RacingCar → 2024.12 – Club Manage → 2025 – Memory Bottle

> *This portfolio is not just a showcase of projects, but a record of how I learned to build, to think, and to persist.  
> Technology and AI guided me along the way, but it was my curiosity and effort that turned guidance into creation.*

<br>

**More on [@YXCS-cya](https://github.com/YXCS-cya)**  
Contact  chenyaoan26@163.com

