## tk9-hub

This repository is the shared home for OpenWork/OpenCode project automation assets:

- `skills/` - reusable skills (workflows + scripts)
- `agents/` - agent definitions
- `commands/` - custom commands
- `plugins/` - optional project plugins

It is intentionally not wrapped in a `.opencode/` folder so it can be vendored into other repos in whatever layout you prefer.

### Vendoring into a project that uses `.opencode/`

If you want to use these assets in a repo that expects `.opencode/skills`, `.opencode/agents`, etc:

```bash
mkdir -p .opencode
cp -R skills .opencode/skills
cp -R agents .opencode/agents
cp -R commands .opencode/commands
cp -R plugins .opencode/plugins
```
