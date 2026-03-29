# claude-skills

Custom skills for [Claude Code](https://claude.com/claude-code).

## Skills

| Skill | Description |
|-------|-------------|
| [au-buyer-agent](./au-buyer-agent) | Australian real estate buyer's agent. Share a property address or listing and get a due diligence report with a **BUY / INVESTIGATE / PASS** verdict — covers price, schools, demographics, infrastructure, crime, flood/bushfire risk, and rental yield. |


## Installation (Claude Desktop — Cowork)

1. Download the `.skill` file from this repo (e.g. `au-buyer-agent/au-buyer-agent.skill`)
2. Open the **Claude Desktop** app and switch to the **Cowork** tab
3. Click **Customize** in the left sidebar
4. Click **Browse plugins**, then upload the `.skill` file

The skill is saved locally to your machine and ready to use.

### Claude Code (CLI)

```bash
claude install-skill https://github.com/mathieukempe/claude-skills/<skill-folder>
```


## License

MIT
