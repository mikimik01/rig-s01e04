# rig

Keeps a lane's lights on while nobody is in it: a heartbeat every minute, a status board, and
(next) a morning digest of what ran overnight.

```sh
cp .env.example .env   # set LANE_MARKER
pnpm install
pnpm dev               # http://localhost:8787
```

Working on it with an agent: start at [AGENTS.md](AGENTS.md).

GitHub Copilot loads `plan-to-issues` through `.github/skills/plan-to-issues`, a symlink to
the shared source in `.agents/skills/`. Edit the shared source, not a separate copy.
