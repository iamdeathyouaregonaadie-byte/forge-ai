# FORGE AI — Autonomous Engineering & Creation Platform

> Transform natural language ideas into fully functional applications, games, websites, and AI systems.

## Vision

FORGE is a **multitasking AI system** that takes your idea and transforms it through a rigorous 18-step engineering pipeline into a **real, testable, deployable product**.

### Core Philosophy

```
IDEA → PLAN → GENERATE → BUILD → TEST → DEBUG → IMPROVE → DELIVER
```

- **AI-generated does not mean AI-looking.** Output is professional, coherent, and original.
- **Hardware-flexible.** Runs on your laptop, scales to cloud when needed.
- **Custom models.** We train our own specialized AI rather than relying on external APIs.
- **Error-driven development.** When something fails, the system learns and fixes it automatically.

---

## Project Structure

```
forge-ai/
├── android/                 # Android APK (Chat UI + Workspace)
├── backend/                 # Python FastAPI (Engineering Engine)
├── ai_model/                # Custom AI Model Training
├── docs/                    # Documentation & Tutorials
└── README.md
```

---

## Quick Start

### Prerequisites
- Python 3.11+
- Android Studio (for building APK)
- 16GB RAM minimum (Dell laptop is fine for Phase 1)

### Backend Setup (Your Laptop)

```bash
cd backend
pip install -r requirements.txt
python main.py
```

Backend will start on `http://localhost:8000`

### Android Setup

```bash
cd android
./gradlew build
./gradlew installDebug
```

---

## The 18-Step FORGE Pipeline

Every project goes through this cycle:

1. **Understand Request** - Parse user's natural language description
2. **Identify Ambiguity** - Flag unclear requirements
3. **Establish Requirements** - Create specification document
4. **Break into Systems** - Decompose into manageable pieces
5. **Create Architecture** - Design file structure & APIs
6. **Create Development Plan** - Task list & dependencies
7. **Implement Foundation** - Basic scaffolding & structure
8. **Build Project** - Implement all features
9. **Test It** - Automated test suite
10. **Inspect Failures** - Analyze what broke
11. **Fix Failures** - Error-driven debugging
12. **Rebuild** - Recompile with fixes
13. **Test Again** - Regression testing
14. **Review UX & Quality** - Visual & usability audit
15. **Optimize** - Performance tuning
16. **Regression Testing** - Ensure nothing broke
17. **Package Result** - Prepare for deployment
18. **Report Results** - Summary of what was built

---

## Quality Standard Matrix

Before declaring a project complete, FORGE evaluates:

- ✅ **Functionality** - Does it work?
- ✅ **Usability** - Can a human use it easily?
- ✅ **Design** - Does it have visual identity?
- ✅ **Performance** - Runs efficiently?
- ✅ **Reliability** - Handles errors gracefully?
- ✅ **Maintainability** - Can be modified later?
- ✅ **Security** - No obvious vulnerabilities?
- ✅ **Originality** - Reflects your actual vision?

---

## Multi-Agent System

FORGE coordinates specialized AI agents:

- **Planner** - Project scope & dependencies
- **Software Engineer** - Architecture & APIs
- **Android Engineer** - Mobile-specific concerns
- **Game Engineer** - Gameplay & physics
- **AI/ML Engineer** - Model integration
- **UI/UX Designer** - Visual design & interaction
- **Testing Engineer** - Quality assurance
- **Performance Engineer** - Speed & memory optimization
- **Security Engineer** - Vulnerability detection
- ... and more

Each agent is responsible for their domain, then they coordinate.

---

## Roadmap

### Phase 1: Foundation (Weeks 1-4)
- [ ] Android APK with chat interface
- [ ] FastAPI backend
- [ ] Rule-based code generator (placeholder)
- [ ] Project workspace & file management

### Phase 2: Custom AI Model Training (Weeks 5-10)
- [ ] Dataset collection & preparation
- [ ] Train Tier 1: Fast Classifier (~100M params)
- [ ] Train Tier 2: Architecture Designer (~700M params)
- [ ] Train Tier 3: Code Generator (~3-7B params)
- [ ] Train Tier 4: Error Fixer (~700M params)

### Phase 3: Integration (Weeks 11-14)
- [ ] Integrate trained models into backend
- [ ] Build generation pipeline
- [ ] Iterative improvement loop
- [ ] MVP release

---

## Learning Path

If you're new to coding, start here:

1. **Python Basics** (1 week) - Variables, functions, classes
2. **APIs & FastAPI** (1 week) - How backend and frontend communicate
3. **Kotlin & Android** (2 weeks) - Building mobile apps
4. **Neural Networks** (2 weeks) - Understanding AI models
5. **FORGE Architecture** (ongoing) - Understanding this project

See `docs/learning-path.md` for detailed tutorials.

---

## Contributing

This is a solo project for now, but structured so it can scale to a team.

---

## License

MIT License - Use freely, modify as needed.

---

## Questions?

Ask your brother! He can help explain coding concepts as you learn.
