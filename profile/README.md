# 🌱 Project-Be-Better

> A developer’s journey to grow, explore, and share — one project at a time.

Welcome to **Project-Be-Better**, a living collection of self-driven learning challenges, technical experiments, and real-world practice apps. This space reflects my belief that consistent, intentional effort can help us grow not just as developers — but as thinkers, builders, and collaborators.



## 🎯 Mission

To become a better developer by:

- **Learning new technologies** through hands-on projects
- **Documenting everything** to solidify knowledge and help others
- **Building openly** with purpose, reflection, and continuous iteration


## 📁 Projects By Theme

| Theme/Skill Area         | Sample Repositories                                                                                              |
|--------------------------|------------------------------------------------------------------------------------------------------------------|
| 🚀 Full-Stack Projects    | `project-genie-fullstack-app`, `project-triver-in`, `project-adam-1`                                              |
| 🎯 DevOps & CI/CD         | `learning-jenkins`, `learning-swe5006-cicd-walkthrough`, `learning-docker`                                        |
| 🛠️ Frontend Frameworks    | `learning-react`, `learning-nextjs`, `learning-html`                                                             |
| 🧠 Machine Learning & AI  | `learning-ml`, `project-lutap.ai`, `project-gen-ai`                                                               |
| 🔧 C++ & Systems          | `100-days-of-cpp`, `learning-cpp`, `project-teletrack-sim`                                                        |
| 🧩 Secure Coding & Agile  | `learning-swe5006-essential-practices-for-agile-teams`                                                            |
| ⚙️ Backend/API Skills      | `learning-fastapi`, `learning-backend`, `learning-python`, `learning-java`                                        |
| 📐 Design & Architecture  | `project-baselinemanager`, `learning-iac`, `learning-farm`                                                        |



## 💡 Why “Project-Be-Better”?

Because getting better is not about being perfect.

It’s about:

- Starting before you're ready.
- Asking questions, building anyway.
- Reflecting. Refactoring. Restarting.
- Never settling.



## 🚀 100 Days of C++ Challenge

A focused, day-by-day journey to master modern C++ (C++11/14/17/20) using **roadmap.sh** as our guide.

Each day includes:
1. **Roadmap Topic** — a key concept or skill from the C++ Developer Roadmap
2. **Hands-on Exercise** — ~30 minutes of coding practice or mini-project work
3. **README Module** — an exercise-specific README explaining the concepts, code samples, and GoogleTest unit tests
4. **UML Diagrams** — PlantUML class or sequence diagrams illustrating design decisions
5. **Dev Setup** — CMake, Conan, GoogleTest, and helper scripts (e.g. `run-tests.sh`) to bootstrap each exercise

**Start:** Day 1 covers basic I/O and build setup. Follow [roadmap-cpp.pdf](/mnt/data/roadmap-cpp.pdf) to progress from beginner to advanced topics.

**Repos:**
- [`100-days-of-cpp`](https://github.com/project-be-better/100-days-of-cpp)
- [`learning-cpp`](https://github.com/project-be-better/learning-cpp)
- [`project-teletrack-sim`](https://github.com/project-be-better/project-teletrack-sim)





## 🔥 Current Focus: TeleTrack Sim

We’re actively building the **[project-teletrack-sim](https://github.com/project-be-better/project-teletrack-sim)** — a complete vehicle telemetry platform demonstrating an end-to-end IoT pipeline. 

**What We’re Building:**
- **Simulator (C++):** `teletrack_sim` publishes GNSS, engine, and speed data via Paho MQTT to a local broker.
- **Messaging (MQTT Broker):** Mosquitto (Docker) relays telemetry topics.
- **Backend (Express.js):** Subscribes to `teletrack/#`, processes incoming messages, persists to DB (MongoDB/Postgres), and exposes REST APIs.
- **Frontend (Next.js):** Real-time dashboard fetching REST endpoints (and optionally using WebSockets) to visualize vehicle data and maps.

**Key Tech Stack:**
- **C++ (Paho MQTT),** **JavaScript (Node.js/Express),** **Next.js + Tailwind CSS**
- **Messaging:** Eclipse Mosquitto
- **Database:** MongoDB or PostgreSQL
- **Build & CI:** CMake, Conan, GoogleTest for C++ ; npm scripts and Docker Compose for services

**Architecture Overview:**
```
TeleTrack Sim (C++) MQTT Publisher
        ↓
    Mosquitto Broker
        ↓
Express.js Backend → Database → REST API
        ↓
   Next.js Frontend Dashboard
```

Follow the [repo docs](https://github.com/project-be-better/project-teletrack-sim) for detailed folder structure, phase-based roadmap, and PlantUML diagrams for data flow and module design.



## 🤝 Open to Ideas & Collaboration

Have suggestions? See something you’d like to reuse or contribute to?

Feel free to fork, star, or open a discussion — growth is better together.

> ✨ Let’s all keep learning, building, and striving to **be better**.

