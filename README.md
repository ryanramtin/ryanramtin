# Ryan Ramtin

I build small, sharp tools for people who run a lot of AI agents.

Once you're running Claude Code, Codex, opencode and an orchestrator at the same time, the usual assumptions break: nobody agrees on what shipped, nothing saves the work you didn't commit, and every agent forgets how you like to work. These are the fixes I actually use.

### [shiplog](https://github.com/ryanramtin/shiplog)

One ship log for every agent and CLI. One line per shipped change — what shipped, what tests passed, where it landed — in a local database that mirrors to git. `shipped`, `held` and `failed` are all real entries.

### [parachute](https://github.com/ryanramtin/parachute)

Crash-proof autosave for uncommitted work. Snapshots the dirty and untracked files of every repo and worktree, and pushes them to `backup/*` branches on your private remote. A flight recorder for your working tree.

### [claude-skills](https://github.com/ryanramtin/claude-skills)

The Claude Code skills I use every day — a status line that shows your rate limits and context left, a deploy verifier that diffs live against local, and a few that just make the output readable.

---

Everything public here is MIT, and works with the agents you already have. → [ryanramtin.com](https://ryanramtin.com)
