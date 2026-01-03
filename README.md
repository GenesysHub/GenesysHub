## What I'm Building

I'm building a modular ecosystem designed to create, manage, and orchestrate tools, workflows, and applications—whether for the web or local environments. The platform is structured to be composable, extensible, and user-friendly, with a strong focus on flexibility and user ownership.

Users have full control over their stack: the entire system is designed to run independently, without requiring reliance on any specific third-party infrastructure. Whether users choose to self-host models and services or integrate third-party APIs like OpenAI, the decision is entirely theirs. Nothing in the core platform enforces external dependencies or locks users into proprietary backends.

### Core Components

**Frontend - App Hub**
A Next.js-based interface that serves as an app hub, where users can launch and interact with modular apps. These apps can be custom-built or community-driven, and some are already integrated by default:

* **System App** – for managing diagrams, layout components, and core framework settings
* **Server App** – for interacting with backend logic: managing tools, running workflows, accessing data, etc.

**Backend - Execution & Orchestration**
A flexible backend runtime that handles the logic and execution layer:

* Create, run, and retrieve data from tools, presets, and agents
* Expose dynamic server endpoints for frontend access
* Automatically map available tools, presets, and resources for easy integration
* Support scalable orchestration across distributed environments

A key component within this layer is the **MCP Factory** package, which streamlines the creation and deployment of Model Context Protocol (MCP) instances. These MCPs provide a standardized context interface, fully compatible with AI agents. The factory can run within the backend server or on separate infrastructure, enabling distributed and modular AI agent systems tailored to each user's environment.

**Packages & Architecture**
The system is orchestrated through a series of modular packages. While some components are currently closed-source during development, the long-term goal is to open-source the entire stack. Each package is designed to be clean, reusable, and easy to build on, supporting both internal extensibility and external contributions.

Importantly, the entire ecosystem is free to use and does not impose infrastructure lock-in. Users are empowered to run everything locally or on their own servers, and integrate only the external services they choose.

### The Broader Vision

This project is not just a tool, a framework, or a UI. it's an ecosystem built to empower creators, developers, and teams. The platform is designed as a base layer that makes it easy to build applications and workflows in a testable, deployable, and extensible way, without needing to rely on third-party platforms or proprietary systems.

The goal is to create a space where users can work independently:

* Build tools, apps, and workflows through an intuitive interface
* Share or reuse components through a growing library of open-source modules
* Extend functionality using third-party APIs and services
* Enable businesses to foster developer communities that contribute apps and workflows, accelerating onboarding and internal innovation

By lowering the barrier to build and orchestrate systems, this platform aims to become a foundation for open, developer-driven business logic, supporting both individual creators and teams looking to scale custom internal tools or public-facing apps.
