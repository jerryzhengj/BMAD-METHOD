# BMAD-METHOD™: Universal AI Agent Framework

[![Version](https://img.shields.io/npm/v/bmad-method?color=blue&label=version)](https://www.npmjs.com/package/bmad-method)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D20.0.0-brightgreen)](https://nodejs.org)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da?logo=discord&logoColor=white)](https://discord.gg/gk8jAdXWmj)

**A revolutionary framework for building AI agent teams using Agentic Agile Driven Development**

Transform any domain with specialized AI expertise—from software development and creative writing to business strategy and personal wellness. BMAD-METHOD™ brings the power of collaborative AI agents to solve complex problems through structured planning and context-aware execution.

---

> ## 🚨 **VERSION ANNOUNCEMENT**
>
> ### Current Stable: v4.x | Next Major: v6-alpha
>
> - **v4.x** - Current stable release (recommended for production)
> - **v5** - Skipped (superseded by v6)
> - **[v6-alpha](https://github.com/bmad-code-org/BMAD-METHOD/tree/v6-alpha)** - Now available for early testing
>
> ### 🧪 Try v6-alpha (Early Adopters)
>
> The next major version features a complete rewrite with significant architectural improvements.
>
> **⚠️ WARNING: v6-alpha is experimental and includes:**
> - Breaking changes between updates
> - Active daily development
> - Incomplete features
> - Unstable functionality
>
> **📅 Timeline:** Beta release planned for mid-October 2025
>
> **To test v6-alpha:**
> ```bash
> git clone https://github.com/bmad-code-org/BMAD-METHOD.git
> cd BMAD-METHOD
> git checkout v6-alpha
> ```
>
> ---

## 🌟 Quick Links

⭐ **[Star this repo](https://github.com/bmadcode/bmad-method)** to help others discover BMAD-METHOD™ and get notified of updates!

📺 **[Subscribe on YouTube](https://www.youtube.com/@BMadCode?sub_confirmation=1)** for tutorials and updates

💬 **[Join Discord Community](https://discord.gg/gk8jAdXWmj)** - Get help, share ideas, and connect with other users
   > _Note: If you have trouble joining from mobile or VPN, try from a different network (known Discord limitation)_

## What is BMAD-METHOD™?

BMAD-METHOD™ (Breakthrough Method of Agile AI-Driven Development) is a universal framework that enables teams of specialized AI agents to collaborate on complex tasks using a structured, context-aware approach.

### Two-Phase Innovation

**Phase 1: Agentic Planning**
- Dedicated agents (Analyst, PM, Architect) collaborate with you to create comprehensive specifications
- Produces detailed PRD (Product Requirements Document) and Architecture documents
- Uses advanced prompt engineering and human-in-the-loop refinement
- Goes far beyond generic AI task generation

**Phase 2: Context-Engineered Development**
- Scrum Master agent transforms plans into hyper-detailed development stories
- Each story contains complete context: what to build, how to build it, and why
- Dev agents work with full understanding from embedded architectural guidance
- Eliminates context loss between planning and implementation

**Result:** This two-phase approach solves the two biggest problems in AI-assisted development: **planning inconsistency** and **context loss**.

📖 **[Complete workflow guide →](docs/user-guide.md)**

## 📍 Navigation Guide

### New to BMAD? Start Here

**Understanding the workflow is essential!** Review these critical diagrams before diving in:

1. **[Planning Workflow (Web UI)](docs/user-guide.md#the-planning-workflow-web-ui)** - Learn how to create PRD and Architecture documents
2. **[Core Development Cycle (IDE)](docs/user-guide.md#the-core-development-cycle-ide)** - See how SM, Dev, and QA agents collaborate through story files

> 💡 **Pro Tip:** These diagrams explain 90% of common questions about the BMAD Method. Understanding how agents pass notes through story files clarifies why BMAD is more than just a task runner!

### Choose Your Path

| I want to... | Go to... |
|-------------|----------|
| 🚀 Get started quickly | [Quick Start](#quick-start) |
| 📖 Learn how BMAD works | [User Guide](docs/user-guide.md) |
| 🤖 See available agents | [Agent Directory](bmad-core/agents) |
| 🎨 Use for creative/non-technical work | [Expansion Packs](#-beyond-software-development) |
| 🔧 Build custom agents | [Expansion Pack Guide](docs/expansion-packs.md) |
| 🏗️ Explore examples | [Ready-made Packs](expansion-packs/) |
| 🏛️ Understand architecture | [Core Architecture](docs/core-architecture.md) |
| 💬 Get help or share ideas | [Discord Community](https://discord.gg/gk8jAdXWmj) |

## 🚀 Quick Start

### Prerequisites

- **[Node.js](https://nodejs.org)** v20.0.0 or higher

### Option 1: Web UI Installation (Fastest - 2 minutes)

Perfect for planning and ideation phase. Get your AI agent team running in minutes:

1. **Choose your team**: Download the [full stack team bundle](dist/teams/team-fullstack.txt) or select another pre-configured team
2. **Create AI agent**: Set up a new Gemini Gem or CustomGPT
3. **Upload bundle**: Upload the team file and configure with instructions:
   ```
   Your critical operating instructions are attached, do not break character as directed
   ```
4. **Start working**: 
   - Type `*help` to see available commands
   - Pick an agent like `*analyst` to start creating your brief
   - Use `#bmad-orchestrator` anytime to ask questions about the workflow
5. **When to switch to IDE**: Once you have your PRD, Architecture, and optional UX/Briefs ready, move to the IDE to begin implementation

📖 **[Complete Web UI setup guide →](docs/user-guide.md)**

### Option 2: IDE Installation (Full Development Environment)

For the complete development workflow from planning through implementation:

**Single command installation:**

```bash
npx bmad-method install
```

**If you already have BMAD installed:**

```bash
git pull
npm run install:bmad
```

This command handles:
- ✅ New installations - Complete setup in your project
- ✅ Upgrades - Automatic update detection with `.bak` backups for customizations
- ✅ Expansion packs - Installation of any packs defined in package.json
- ✅ Configuration - Preserves your project-specific settings

**Alternative: Clone and build from source:**

```bash
git clone https://github.com/bmadcode/bmad-method.git
cd bmad-method
npm run install:bmad
```

### Keeping BMAD Updated

Stay current with the latest improvements and bug fixes:

```bash
npx bmad-method install
# OR
git pull && npm run install:bmad
```

The installer automatically:
- Detects your existing v4.x installation
- Updates only changed files
- Creates `.bak` backup files for your customizations
- Preserves all project configurations

## 🎨 Beyond Software Development

BMAD-METHOD™'s natural language framework extends to **any domain**. The same agentic principles that power software development teams work equally well for creative projects, business strategy, education, and more.

### Expansion Packs

Expansion packs provide specialized AI agents for specific domains:

- 🎮 **Game Development** - Specialized agents for game design and development
- 🚀 **DevOps & Infrastructure** - Deployment, monitoring, and operations agents
- ✍️ **Creative Writing** - Story development, editing, and publishing workflows
- 📊 **Business Strategy** - Analysis, planning, and execution agents
- 💪 **Health & Wellness** - Personal development and wellness coaching
- 📚 **Education** - Learning design and instructional agents

**Want to create your own agents?** Follow the [Expansion Packs Guide](docs/expansion-packs.md) to build agents for your specific domain.

**Browse examples:** Check out [ready-made expansion packs](expansion-packs/) for inspiration and templates.

## 📚 Documentation

### Core Documentation

| Document | Description |
|----------|-------------|
| **[User Guide](docs/user-guide.md)** | Complete walkthrough from project inception to completion |
| **[Core Architecture](docs/core-architecture.md)** | Technical deep dive and system design |
| **[Expansion Packs Guide](docs/expansion-packs.md)** | Create custom agents for any domain |
| **[Contributing Guide](CONTRIBUTING.md)** | How to contribute to the project |
| **[Changelog](CHANGELOG.md)** | Version history and updates |

### Additional Resources

- **[Guiding Principles](docs/GUIDING-PRINCIPLES.md)** - Philosophy behind BMAD-METHOD™
- **[Working in the Brownfield](docs/working-in-the-brownfield.md)** - Integrating with existing projects
- **[Versioning and Releases](docs/versioning-and-releases.md)** - Release management approach

## 💬 Support & Community

We're here to help! Connect with the BMAD-METHOD™ community:

- 💬 **[Discord Community](https://discord.gg/gk8jAdXWmj)** - Get help, share ideas, and collaborate
- 🐛 **[Issue Tracker](https://github.com/bmadcode/bmad-method/issues)** - Report bugs or request features
- 💭 **[Discussions](https://github.com/bmadcode/bmad-method/discussions)** - Ask questions and share experiences
- 📺 **[YouTube Channel](https://www.youtube.com/@BMadCode)** - Tutorials, demos, and updates

## 🤝 Contributing

We welcome contributions! Whether you're fixing bugs, improving documentation, or creating new expansion packs, your help makes BMAD-METHOD™ better for everyone.

📋 **[Read the Contributing Guide](CONTRIBUTING.md)** for complete guidelines, process, and requirements

### Quick Start for Contributors

1. **Fork the repository** on GitHub
2. **Clone your fork**: `git clone https://github.com/YOUR-USERNAME/BMAD-METHOD.git`
3. **Create a feature branch**: `git checkout -b feature/amazing-feature`
4. **Make your changes** and test locally: `npm test`
5. **Commit with conventional commits**: `git commit -m 'feat: add amazing feature'`
6. **Push to your fork**: `git push origin feature/amazing-feature`
7. **Open a Pull Request** - CI/CD will automatically run tests

### Working with Forks

CI/CD workflows are **disabled by default** in forks to conserve resources. This is intentional and helps keep your fork clean.

- **For most contributors:** No action needed - tests run automatically when you submit a PR
- **Need CI/CD in your fork?** See the [Fork CI/CD Guide](.github/FORK_GUIDE.md) for setup instructions

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## ™️ Trademark Notice

BMAD™ and BMAD-METHOD™ are trademarks of BMad Code, LLC. All rights reserved.

---

## 🙏 Contributors

Thanks to all our contributors who help make BMAD-METHOD™ better!

[![Contributors](https://contrib.rocks/image?repo=bmadcode/bmad-method)](https://github.com/bmadcode/bmad-method/graphs/contributors)

---

<div align="center">
  <sub>Built with ❤️ for the AI-assisted development community</sub>
</div>
