# Awesome Agent Skills

> Curated registry of agent skills for [ASK](https://github.com/yeasy/ask) — the package manager for AI agent skills.

Install once, works with Claude, Cursor, Codex, Copilot, Windsurf, and 12+ more agents.

## Quick Start

```bash
# Install ASK
go install github.com/yeasy/ask@latest

# Initialize your project
ask init

# Search for skills
ask search pdf

# Install a skill
ask install pdf
```

## Skill Collections

Pre-configured packs for common use cases:

| Pack | Skills | Use Case |
|------|--------|----------|
| [Essential Skills](collections/starter-pack.yaml) | 5 | Document handling (PDF, Word, Excel, PowerPoint) + file organization |
| [Developer Pack](collections/developer.yaml) | 8 | Web development, MCP servers, deployment, testing |
| [Creative Pack](collections/creative.yaml) | 6 | Design, generative art, themes, content creation |

## Skills Directory

### Productivity

| Skill | Source | Description | Install |
|-------|--------|-------------|---------|
| pdf | anthropics | Read, create, and manipulate PDF documents | `ask install anthropics/skills/skills/pdf` |
| docx | anthropics | Create, read, and edit Word documents | `ask install anthropics/skills/skills/docx` |
| xlsx | anthropics | Create and manipulate Excel spreadsheets | `ask install anthropics/skills/skills/xlsx` |
| pptx | anthropics | Create and edit PowerPoint presentations | `ask install anthropics/skills/skills/pptx` |
| doc-coauthoring | anthropics | Co-author documentation through structured workflows | `ask install anthropics/skills/skills/doc-coauthoring` |
| internal-comms | anthropics | Draft internal communications and announcements | `ask install anthropics/skills/skills/internal-comms` |
| file-organizer | composio | Organize files by type, date, or custom rules | `ask install ComposioHQ/awesome-claude-skills/file-organizer` |
| tailored-resume-generator | composio | Generate tailored resumes for job applications | `ask install ComposioHQ/awesome-claude-skills/tailored-resume-generator` |
| meeting-insights-analyzer | composio | Analyze meeting transcripts and extract insights | `ask install ComposioHQ/awesome-claude-skills/meeting-insights-analyzer` |

### Development

| Skill | Source | Description | Install |
|-------|--------|-------------|---------|
| web-artifacts-builder | anthropics | Build HTML artifacts with React and Tailwind CSS | `ask install anthropics/skills/skills/web-artifacts-builder` |
| mcp-builder | anthropics | Build Model Context Protocol servers and tools | `ask install anthropics/skills/skills/mcp-builder` |
| skill-creator | anthropics | Create, modify, and test agent skills | `ask install anthropics/skills/skills/skill-creator` |
| claude-api | anthropics | Interact with the Claude API programmatically | `ask install anthropics/skills/skills/claude-api` |
| frontend-design | anthropics | Design and build frontend interfaces | `ask install anthropics/skills/skills/frontend-design` |
| webapp-testing | anthropics | Test web applications with automated workflows | `ask install anthropics/skills/skills/webapp-testing` |
| deploy-to-vercel | vercel | Deploy applications to Vercel platform | `ask install vercel-labs/agent-skills/skills/deploy-to-vercel` |
| react-best-practices | vercel | Apply React best practices and patterns | `ask install vercel-labs/agent-skills/skills/react-best-practices` |
| web-design-guidelines | vercel | Follow web design guidelines and best practices | `ask install vercel-labs/agent-skills/skills/web-design-guidelines` |
| react-native-skills | vercel | Build React Native mobile applications | `ask install vercel-labs/agent-skills/skills/react-native-skills` |
| changelog-generator | composio | Generate changelogs from git history | `ask install ComposioHQ/awesome-claude-skills/changelog-generator` |

### Creative

| Skill | Source | Description | Install |
|-------|--------|-------------|---------|
| canvas-design | anthropics | Create beautiful visual designs and posters | `ask install anthropics/skills/skills/canvas-design` |
| algorithmic-art | anthropics | Create generative art with p5.js | `ask install anthropics/skills/skills/algorithmic-art` |
| theme-factory | anthropics | Style artifacts with pre-set or custom themes | `ask install anthropics/skills/skills/theme-factory` |
| brand-guidelines | anthropics | Apply brand guidelines to content and designs | `ask install anthropics/skills/skills/brand-guidelines` |
| slack-gif-creator | anthropics | Create animated GIFs for Slack | `ask install anthropics/skills/skills/slack-gif-creator` |
| content-research-writer | composio | Research topics and write content | `ask install ComposioHQ/awesome-claude-skills/content-research-writer` |

### Business

| Skill | Source | Description | Install |
|-------|--------|-------------|---------|
| lead-research-assistant | composio | Research and qualify sales leads | `ask install ComposioHQ/awesome-claude-skills/lead-research-assistant` |
| invoice-organizer | composio | Organize and manage invoices | `ask install ComposioHQ/awesome-claude-skills/invoice-organizer` |

### Media

| Skill | Source | Description | Install |
|-------|--------|-------------|---------|
| video-downloader | composio | Download videos from various platforms | `ask install ComposioHQ/awesome-claude-skills/video-downloader` |
| image-enhancer | composio | Enhance and process images | `ask install ComposioHQ/awesome-claude-skills/image-enhancer` |

## Contributing

Want to add your skill to the registry?

1. Ensure your skill has a valid `SKILL.md` file
2. Run `ask check` to verify it passes security scanning
3. Submit a PR adding your skill to `registry/index.json`
4. CI will automatically validate format and security

## Security

All skills in this registry are scanned by [ASK Security Check](https://github.com/yeasy/ask). Look for the "Scanned by ASK" badge.

## License

MIT
