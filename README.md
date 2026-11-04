# Caretaker Chiron

**Understand your system. Explore beneath the surface. Stay in control.**

Caretaker Chiron is an open-source, AI-powered system exploration platform designed to make the inner workings of your computer understandable, observable, and accessible.

Inspired by tools such as Process Hacker and x64dbg, Caretaker Chiron aims to bring powerful system inspection capabilities to everyday users without hiding the technical depth that advanced users need.

> Make the complex understandable without making the underlying technology less powerful.

---

## The vision

Modern operating systems expose enormous amounts of information about processes, memory, **CPU** usage, storage, services, and system activity. Much of this information is difficult for ordinary users to interpret, while existing advanced tools can be intimidating to newcomers.

Caretaker Chiron aims to bridge that gap.

It is being designed to help users:

- Understand what is happening inside their computers.
- Explore running processes and system activity.
- Investigate unusual resource consumption.
- Understand technical system information through clear explanations.
- Move from simple overviews to deeper technical inspection.
- Use AI assistance grounded in observable system evidence.

## Core principles

**1. Clarity without oversimplification**

Make complex system information understandable while preserving the details and controls that advanced users expect.

**2. Evidence before explanations**

AI-generated explanations should be grounded in collected system information, with clear references to the evidence behind them.

**3. Local-first and privacy-conscious**

System inspection should prioritize local processing and transparent data handling. Cloud-assisted features should be optional.

**4. User control and safety**

Inspection must be transparent. Privileged operations must be explicit and carefully scoped. AI must not silently execute arbitrary system commands.

**5. Open source and extensibility**

The project should be modular, documented, and welcoming to contributors.

## Planned capabilities

| Area | Direction |
|---|---|
| Process exploration | Browse, search, sort, and inspect running processes |
| System monitoring | CPU, memory, storage, and other resource metrics |
| System intelligence | Explain system activity in understandable language |
| AI assistance | Evidence-grounded investigation and explanations |
| Advanced inspection | Deeper technical views for experienced users |
| Cross-platform support | Windows, Linux, and macOS |

These are project goals, not claims that every capability is already implemented.

## Technology

The initial architecture is planned around:

- **Rust** — system-facing core and platform integrations.
- **Tauri 2** — lightweight desktop application framework.
- **React** — user interface.
- **TypeScript** — frontend type safety.
- **Vite** — frontend development and build tooling.
- **pnpm** — JavaScript package management.
- **SQLite** — planned local persistence.
- **Hybrid AI architecture** — planned local and optional cloud intelligence.

The architecture will use a modular monolith initially, with clear boundaries between the platform-independent core, operating-system adapters, desktop application, and user interface.

## Platform strategy

The initial target platforms are:

- Windows
- Linux
- macOS

Windows is the first complete implementation target. Linux and macOS compatibility will be considered early in the architecture rather than treated as afterthoughts.

## Development roadmap

### Phase 1 — Foundation

- [x] Define initial product direction and architecture.
- [ ] Establish the public repository.
- [ ] Create the Rust and Tauri application foundation.
- [ ] Establish frontend and backend communication.
- [ ] Add platform detection and development documentation.

### Phase 2 — Native system intelligence

- [ ] Enumerate running processes.
- [ ] Inspect process details.
- [ ] Add **CPU** and memory monitoring.
- [ ] Implement search, sorting, and filtering.
- [ ] Establish cross-platform collector interfaces.

### Phase 3 — Investigation experience

- [ ] Build evidence-based system explanations.
- [ ] Add investigation workflows.
- [ ] Improve system visualization and navigation.
- [ ] Introduce safe, explicit privileged inspection where necessary.

### Phase 4 — AI assistance

- [ ] Design the AI explanation interface.
- [ ] Add evidence references and validation.
- [ ] Explore local model integration.
- [ ] Add optional cloud-assisted capabilities.

### Phase 5 — Cross-platform maturity

- [ ] Improve Linux support.
- [ ] Improve macOS support.
- [ ] Add automated testing and release workflows.
- [ ] Prepare public preview releases.

Roadmap items may change as development and testing reveal better approaches.

## Project status

<**Early development** />

Caretaker Chiron is at the foundation stage. Architecture, repository structure, platform interfaces, and the initial desktop experience are being established.

This project is not yet production-ready. APIs, architecture, features, and user interfaces may change substantially.

## Contributing

Contributions, ideas, bug reports, and technical discussions are welcome.

Before contributing:

## Read [CONTRIBUTING.md](CONTRIBUTING.md).

## Review the project's architecture and development documentation. ## Check existing issues before starting major work. ## Open an issue to discuss substantial changes.

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before participating.

## Security

If you discover a security vulnerability, please follow the instructions in [**SECURITY**.md](**SECURITY**.md). Avoid publishing sensitive vulnerability details in public issues.

## License

Caretaker Chiron is intended to be distributed under the **Apache License 2.0**. See [**LICENSE**](**LICENSE**) for details.

---

**Caretaker Chiron** — making system exploration understandable, powerful, and accessible.

*The project is open source. The possibilities are open-ended.*
