# music-studio-ops

**A Claude AI skill for operations managers at small to mid-size audio production and music studios.**

Built to international standards. Region-aware. Production-ready out of the box.

---

## What This Skill Does

`music-studio-ops` gives Claude the operational knowledge of a senior studio ops manager. Once installed, Claude can help you:

- Manage projects across five production categories with category-specific workflows
- Draft client communications calibrated to regional and cultural norms
- Handle revision requests, scope creep, and change orders professionally
- Coordinate composers, voice talent, session musicians, and sound designers
- Onboard and manage freelance contractors
- Build delivery checklists, file naming conventions, and Dolby Atmos specs
- Structure proposals and sonic branding pitches
- Map stakeholders and manage approval chains on complex projects

---

## Production Categories Covered

| # | Category |
|---|---|
| 1 | Commercial Music Production |
| 2 | Documentary Music Production |
| 3 | Feature Film & Independent Movie Scores |
| 4 | Mixing & Mastering Only |
| 5 | Sonic Branding |

Each category has its own intake checklist, timeline norms, revision protocol, deliverable set, and common friction points.

---

## Region-Aware Communication

Built-in tone guidance for:
- 🇺🇸 North America
- 🇬🇧 🇩🇪 🇫🇷 Western Europe
- 🇸🇦 🇦🇪 Middle East & GCC
- 🇯🇵 🇰🇷 🇨🇳 East Asia
- 🇧🇷 🇲🇽 Latin America

---

## Domains

1. Project Lifecycle Management
2. Client Communication (with regional tone guide)
3. Talent & Session Coordination
4. Vendor & Freelancer Ops
5. Delivery Pipeline & File Management
6. Proposals & Sonic Branding Ops
7. Stakeholder Management

---

## Templates (11)

Trigger any template by asking Claude using the phrase listed:

| Template | Trigger Phrase |
|---|---|
| Project Intake Brief (per category) | *"intake brief for [category]"* |
| Project Status Update | *"write a status update for [project]"* |
| Revision Request Handler | *"help me respond to this revision"* |
| Session Brief | *"write a session brief for [talent/role]"* |
| Composer Brief (Film Score) | *"composer brief for [film name]"* |
| Delivery Checklist (per category) | *"delivery checklist for [category]"* |
| Dolby Atmos Delivery Checklist | *"Atmos delivery checklist"* |
| Vendor Scope Agreement | *"vendor scope for [contractor name]"* |
| Sonic Branding Proposal | *"sonic branding proposal for [client name]"* |
| Universal Project Proposal | *"project proposal for [client name]"* |
| Project Closure Summary | *"project closure for [project name]"* |

---

## Installation

### Claude.ai (Pro, Max, Team, Enterprise)
1. Download `music-studio-ops.skill`
2. Go to **Settings → Skills → Upload Skill**
3. Upload the file
4. The skill activates automatically when relevant

### Claude Code
```bash
# Clone the repo
git clone https://github.com/bedouhammad/music-studio-ops.git

# Copy skill to Claude skills directory
cp -r music-studio-ops ~/.claude/skills/
```

### Via npx
```bash
npx ai-agent-skills install bedouhammad/music-studio-ops
```

---

## How It Works

Claude scans all available skills at the start of each session using only the skill name and description (~100 tokens). When your message matches the skill's scope — a project brief, a revision request, a delivery question — Claude loads the full `SKILL.md` and applies its frameworks to your task.

You don't need to say "use the skill." Just describe what you're working on and Claude activates it automatically.

---

## Adapting This Skill

This skill is a **starting point**, not a rigid system. Fork it and customize:

- Add your studio's specific client types or markets
- Replace generic examples with your actual project naming conventions
- Add new production categories relevant to your work (podcast production, live event sound, etc.)
- Extend the region guide with markets you operate in
- Add internal rate cards, budget tiers, or pricing frameworks to the proposals domain

See [agentskills.io](https://agentskills.io) for the full skill-building standard and documentation.

---

## Compatibility

Works with any tool that supports the [Agent Skills standard](https://agentskills.io):

- Claude.ai (Pro, Max, Team, Enterprise)
- Claude Code
- Cursor
- GitHub Copilot (workspace context)
- Gemini CLI
- OpenAI Codex
- Windsurf
- Aider

---

## License

MIT License — free to use, adapt, and redistribute with attribution.

---

## Author

**Abdelrahman Hammad**  
Generative AI Media Strategist & Audio Operations Specialist  
[abdelrahmanhammad.lovable.app](https://abdelrahmanhammad.lovable.app)  
GitHub: [@bedouhammad](https://github.com/bedouhammad)

---

## Contributing

Contributions welcome. If you work in a studio market or production category not covered here, open a PR with your additions. The goal is to make this the most practical, internationally useful studio ops skill available.

---

*Built from real studio operations experience. Designed to be adapted, not followed blindly.*
