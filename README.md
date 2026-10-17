
# I build the things I wish existed.

**Product Builder and Designer - Software engineer. Occasional architect of my own problems.**

I design, build, test, and ship software. Sometimes it's a commercial product. Sometimes it's an experiment. Sometimes it's an application I created because I got tired of doing something the hard way.

My background spans software engineering, technical product management, enterprise platforms, test automation, DevOps, and applied AI. I've spent years working on complex systems and leading product delivery, but I'm equally comfortable getting into the code and figuring out why something broke.

I don't believe every problem needs the same framework, architecture, or technology stack.

I believe in understanding the problem, choosing the appropriate tools, and building something that actually works.

> **Repository access:** Some projects listed below are maintained in private repositories. If a repository requires authorization, feel free to [contact me on LinkedIn](https://www.linkedin.com/in/soren-essen-776593157/) to discuss access. Access is granted selectively, subject to project confidentiality and development status.

---

## What I'm building

These projects range from developer utilities and cross-platform applications to simulation engines, multiplayer systems, security tools, and experimental AI.

They're different kinds of software, but they share a common philosophy: solve interesting problems, understand the underlying systems, and build useful things.

### 🌎 Est

<h1 align="center">=== EST ===</h1>

<p align="center">
  <img width="1216" height="466" alt="Screenshot 2026-09-12 at 12 04 45 AM" src="https://github.com/user-attachments/assets/1a5425fe-1427-4e2c-818f-7a11fa8d0ae2" />
</p>

## A living planetary simulation.

## In-world development progress
<p align="center">
  <img width="250" height="120" alt="mount-rainier-night-terrain" src="https://github.com/user-attachments/assets/3f3123e0-af0e-41c9-94b3-ac2966fc7d5c" />
  <img width="250" height="120" alt="Screenshot 2026-09-12 at 12 08 40 AM" src="https://github.com/user-attachments/assets/b1a3c767-a876-4bf4-ade0-0e979c52458e" />
  <img width="250" height="120" alt="Screenshot 2026-09-12 at 12 07 52 AM" src="https://github.com/user-attachments/assets/acbe955c-f79f-436d-be10-cb4aa3daef6e" />
</p>

### [Visit Live Est Observatory](https://calypso-labs.com/est/)

[Explore Est repositories](https://github.com/sorenessen?tab=repositories&q=Est)


Est is an ambitious simulation project exploring how an interconnected virtual world can develop and evolve over time.

Rather than scripting every event, the goal is to build systems that interact through shared rules, environmental conditions, resources, and changing world state.

The project explores:

- Persistent world simulation and historical state
- Planetary environments and interconnected systems
- Population and ecosystem modeling
- Simulation clocks and event processing
- Browser-based 3D visualization
- Human behavior, movement, and interaction systems

Est is part software engineering challenge, part research playground, and part exercise in discovering just how complicated a simulated world can become.

**Technical focus:** Simulation architecture, TypeScript/JavaScript, Babylon.js, 3D rendering, state persistence, and systems modeling.

*Status: Research and active development.*

---

### 🎨 Griddle
**Screen annotation, presentation, and recording software**

[View Griddle repository](https://github.com/sorenessen/Griddle)

Griddle began with a straightforward idea: communicating something on a screen should be easier than it usually is.

It has grown into a cross-platform application combining screen annotation, drawing tools, camera presentation, recording, and interactive presentation workflows.

Development includes:

- Freehand drawing, shapes, text, and callouts
- Multi-display annotation and presentation
- Screen recording and camera integration
- Shared rendering and editing components
- Native macOS and Windows functionality
- iOS and iPadOS development
- Platform-specific integrations and device testing

One of the more interesting challenges has been sharing behavior and rendering logic across platforms without sacrificing the native capabilities of each.

**Technical focus:** C#, .NET, Avalonia, iOS, native APIs, graphics, screen capture, and cross-platform architecture.

*Status: Active development and platform validation.*

---

### 🐦 Sparrow
**A development workspace that remembers how you work**

[Explore Sparrow repositories](https://github.com/sorenessen?tab=repositories&q=Sparrow)

I work across several projects with very different development environments.

Eventually, I got tired of remembering which terminal commands, services, scripts, and working directories belonged to which application.

So I built Sparrow.

Sparrow is a macOS developer workspace that combines a persistent terminal with reusable, project-specific commands and workspace organization.

It includes three connected components:

- **Pilar:** Organize projects into collections and navigate between workspaces.
- **Hatchery:** Create and maintain reusable commands and tasks.
- **Sparrow:** Run development workflows within a persistent terminal environment.

Depending on the project, those workflows can invoke development servers, Docker containers, databases, API services, build commands, test suites, editors, or custom scripts.

The objective isn't to replace the developer's existing tools.

It's to make them easier to work with.

**Built with:** Rust, Tauri, TypeScript, and macOS platform integration.

*Status: Active development.*

---

### ♠️ Mainfloor
**A multiplayer poker platform and game engine**

[Explore Mainfloor repositories](https://github.com/sorenessen?tab=repositories&q=mainfloor)

Mainfloor is a multiplayer Texas Hold'em development project centered on game rules, shared state, and the complexity of coordinating players in real time.

What looks like a relatively simple card game becomes a much more interesting engineering problem when you have to account for concurrent users, authoritative state, timers, disconnects, reconnections, and every possible transition between hands.

Current engineering areas include:

- Texas Hold'em game logic and hand progression
- Multiplayer table and player-state management
- Server-authoritative gameplay
- Real-time player presence and reconnection
- Decision clocks, time banks, and timeout behavior
- Cash-game lifecycle and automatic dealing
- HTTP-based player interactions
- Automated testing and acceptance validation

The project emphasizes deterministic behavior, explicit state transitions, and repeatable testing of multiplayer scenarios.

It's also a reminder that the rules of poker are considerably easier to explain than they are to implement correctly.

**Technical focus:** TypeScript, Node.js, state machines, multiplayer architecture, API development, and automated testing.

*Status: Active development.*

---

### 🧪 CATE
**An automated HTTP and API testing engine**

[Explore CATE repositories](https://github.com/sorenessen?tab=repositories&q=CATE)

CATE is a command-line testing engine designed to make HTTP and API validation more repeatable and easier to automate.

The project focuses on executing configurable requests and flows, inspecting application behavior, and generating structured test evidence.

Capabilities and development areas include:

- HTTP request testing and validation
- Configurable multi-request flows
- Command-line execution
- Repeatable test scenarios
- Structured JSONL, Markdown, and HTML reporting
- API behavior and reliability analysis

CATE grew out of years spent working with software testing, QA automation, and enterprise application delivery.

The philosophy is simple: tests should produce meaningful evidence, not just a green checkmark.

**Technical focus:** HTTP, API testing, command-line tooling, workflow configuration, test automation, and reporting.

*Status: Iterative development.*

---

### 🔍 CopyCat
**Experimental AI text integrity analysis**

[Explore CopyCat repositories](https://github.com/sorenessen?tab=repositories&q=CopyCat)

CopyCat explores the difficult problem of evaluating whether written content exhibits characteristics associated with machine-generated text.

Rather than treating detection as an infallible binary classification, the project investigates multiple signals, interpretable measurements, calibration, and uncertainty.

Research and development areas include:

- Linguistic and stylistic analysis
- Language-model-based measurements
- Multiple signal evaluation
- Explainable scoring and reporting
- Confidence and uncertainty handling
- Desktop application packaging
- Local model inference

The project is also an ongoing lesson in the limitations of AI detection and the importance of communicating what an analytical system can and cannot establish.

**Technical focus:** Python, FastAPI, Transformers, language models, stylometry, model evaluation, and explainable AI.

*Status: Experimental product and ongoing research.*

---

### 👻 GhostLine
**Bot detection and suspicious traffic analysis**

[Explore GhostLine repositories](https://github.com/sorenessen?tab=repositories&q=GhostLine)

GhostLine is a bot detection tool designed to identify suspicious automated activity on websites and web applications.

Its purpose is to help distinguish legitimate visitors from automated clients, fake users, and potentially unwanted crawlers interacting with web pages.

The project focuses on examining visitor activity for patterns that may indicate automation rather than assuming every request represents a genuine human user.

Key areas of focus include:

- Detecting suspicious automated website activity
- Identifying potential bots and fake visitors
- Analyzing web traffic and visitor behavior
- Recognizing activity patterns associated with crawling and automation
- Supporting investigation of potentially unwanted traffic
- Improving visibility into application traffic integrity

GhostLine explores an increasingly relevant problem: not every visitor to a website is a person, and not every automated visitor identifies itself as a bot.

**Technical focus:** Bot detection, behavioral analysis, web application security, traffic analysis, and automation detection.

*Status: Experimental development.*

---

## My engineering background

I've worked across the software delivery lifecycle, from early requirements and architecture through implementation, validation, deployment, and ongoing improvement.

My experience includes:

- **Software engineering:** Designing and developing applications, services, APIs, and automation.
- **Technical product leadership:** Translating complex requirements into product strategies, roadmaps, and deliverable software.
- **Architecture:** Designing system boundaries, integration patterns, data flows, and platform components.
- **Quality engineering:** Building automated tests and validating behavior across application layers.
- **DevOps and infrastructure:** CI/CD, cloud services, Linux administration, containers, and deployment workflows.
- **Security and compliance:** Experience supporting STIG remediation, authorization processes, and security-conscious enterprise delivery.
- **Applied AI:** Experimenting with language models, analytical systems, evaluation methods, and AI-assisted applications.

I've worked on large enterprise systems and small independent products.

Both have a way of teaching you things you didn't know you needed to learn.

---

## Technologies I work with

I choose technologies based on the problem, the platform, and the constraints involved.

| Area | Technologies & experience |
|---|---|
| Languages | Python, C#, Java, TypeScript, JavaScript, Rust, SQL |
| Application development | .NET, Avalonia, Tauri, FastAPI, web applications |
| Platforms | macOS, Windows, Linux, iOS |
| Cloud & infrastructure | AWS, Azure, Docker, CI/CD, Linux administration |
| Data & APIs | PostgreSQL, Redis, REST, GraphQL |
| Testing | Selenium, JUnit, Vitest, API testing, integration testing |
| Developer tooling | Git, GitHub Actions, Bitbucket Pipelines, shell scripting |
| Product delivery | Agile, Scrum, architecture, roadmaps, technical product management |

Some of these are tools I've used professionally for years.

Others are technologies I've picked up because something I wanted to build required them.

I don't confuse having used a technology with having mastered every corner of it.

---

## How I approach building software

**Understand the problem first.**

A sophisticated solution to the wrong problem is still the wrong solution.

**Keep architecture practical.**

Design for what the system needs to accomplish, while leaving room for it to evolve.

**Stay close to implementation.**

I enjoy architecture and product strategy, but I also want to understand what happens when the application runs.

**Treat testing as engineering.**

A successful build is a starting point, not proof that the software works.

**Experiment without pretending every experiment is a product.**

Some projects become useful applications. Others become valuable lessons.

**Keep learning.**

The day software development becomes completely predictable will probably be the day I find another profession.

---

## About Calypso Labs

[Calypso Labs](https://www.calypso-labs.com/) is my independent software research and development company.

It's where I explore ideas and build products across:

- Developer productivity and workflow automation
- Cross-platform applications
- API testing and software reliability
- Applied artificial intelligence
- Digital integrity and authenticity
- Bot detection and web traffic integrity
- Experimental software and simulation systems

The goal is to combine technical curiosity with practical engineering and product thinking.

Not everything needs to become a startup.

But if an idea is worth exploring, it's worth building thoughtfully.

---

## Let's connect

I'm interested in software engineering, architecture, technical product leadership, developer tools, applied AI, and opportunities to help build challenging products.

I'm happy to connect with engineers, technical leaders, recruiters, and people working on interesting problems.

**Links**

- [GitHub](https://github.com/sorenessen)
- [LinkedIn](https://www.linkedin.com/in/soren-essen-776593157/)
- [Calypso Labs](https://www.calypso-labs.com/)
- [Calypso Labs on LinkedIn](https://www.linkedin.com/company/calypso-labs/)

If you're interested in a private project, reach out with a little context about what you'd like to explore. Access can be considered on a project-by-project basis.

---

*Still building. Still learning. Still occasionally wondering why the thing that worked yesterday doesn't work today.*
