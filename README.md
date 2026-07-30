## Phillip Beazley

The higher the mountain, the higher I climb.

I build local-first developer tools and self-hosted applications, mostly in TypeScript on Bun, and mostly for a fleet of my own projects that keeps them honest.

[beazley.org](https://beazley.org) &middot; [field notes RSS](https://beazley.org/feed.xml) &middot; [phillip@beazley.org](mailto:phillip@beazley.org)

---

### What I'm building

| Project                                                            | What it is                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**aidd**](https://github.com/NomadicDaddy/aidd)                   | Local control panel for AI coding work. Drives a plan → code → audit → review loop across every project on your machine, against backends you already use (Claude Code, codex, Cline, opencode, kilocode, Ollama, LM Studio, any OpenAI-compatible API). No accounts, no cloud, no telemetry. |
| [**spernakit**](https://github.com/NomadicDaddy/spernakit)         | Self-hosted full-stack application template. Auth, RBAC, workspaces, audit logging, notifications, uploads, scheduled tasks, health monitoring, and the admin UI for all of it. Bun, Elysia, Drizzle, React 19, shadcn/ui, SQLite or Postgres. MIT.                                           |
| [**htmx-debugger**](https://github.com/NomadicDaddy/htmx-debugger) | Chrome and Firefox extension for debugging htmx applications. My most-used piece of work by other people.                                                                                                                                                                                     |
| [**podex**](https://github.com/NomadicDaddy/podex)                 | PowerShell/Pode + htmx framework for building web applications. Hypermedia without a build step.                                                                                                                                                                                              |
| [**agentwatch**](https://github.com/NomadicDaddy/agentwatch)       | Audits what your AI agents can actually reach: endpoints, permissions, credential paths, dynamic tools.                                                                                                                                                                                       |
| [**starsync**](https://github.com/NomadicDaddy/starsync)           | Clones or updates every repository you have starred, before any of them disappear.                                                                                                                                                                                                            |

Smaller things: [semts](https://github.com/NomadicDaddy/semts) (encoding SemVer into artifact
timestamps), [wopr-decryptor](https://github.com/NomadicDaddy/wopr-decryptor),
[fifi](https://github.com/NomadicDaddy/fifi), and a
[SQL](https://github.com/NomadicDaddy/eskew-ale) /
[data-dictionary](https://github.com/NomadicDaddy/CodeWrangler) archive from a longer stretch
of database work. A few repositories are still here from 2002-2004 and are staying that way.

![My GitHub Stats](https://github-readme-stats.vercel.app/api?username=NomadicDaddy&show_icons=true&theme=radium)
![GitHub Streak](https://streak-stats.demolab.com/?user=NomadicDaddy&theme=dark)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=NomadicDaddy&layout=compact&theme=vision-friendly-dark)

### How I work

- **Local-first by default.** No accounts, no hosted service, no telemetry leaving the machine. If it needs a cloud to function, I would rather it not exist.
- **Gates over intentions.** Typecheck, lint, format, and a smoke pass have to be green before anything is called finished. A documentation policy that depends on me remembering it is not a policy.
- **One toolchain, thirty-plus repositories.** Bun, TypeScript with no `any`, ES modules, exact dependency pins. Standards change in one place and propagate outward.
- **Wired end to end or not merged.** No endpoints without callers, no abstractions for a future that has not arrived.
- **I dogfood the agent tooling on the agent tooling.** aidd builds aidd, and the [receipts](https://github.com/NomadicDaddy/aidd-build-proofs) are public.

### Elsewhere

I write [field notes](https://beazley.org) most weeks about what actually shipped and what broke doing it. No newsletter, no course, no cohort.
