# Antoine Leflon

I work in cybersecurity: governance, risk and compliance (NIS2, ISO 27001),
vulnerability management, and cyber and IT project management. I run ATL, my
freelance practice, and from November 2026 I will be working remotely from Taiwan.

Most of what I build runs in my own home lab. This page is a short tour.

## ATL-Lab

My home lab, run the way I would want a small company's infrastructure to be
run: Proxmox, a segmented network with a default-deny firewall, a single
reverse proxy as the public entry point, and separate dev, preview and
production environments.

Claude Code and Codex help with day-to-day administration, under strict
limits. A read-only agent called Observer checks the state of every machine,
so that "it's fixed" always gets verified.

→ [Architecture, security model and AI agents](https://github.com/Antoine-DOT/atl-lab) ·
[write-up on my site](https://antoineleflon.com/en/projects/atl-lab)

## Projects

| Project | What it is | |
| --- | --- | --- |
| **Malun** | Mandarin learning app (flashcards, TOCFL and HSK levels). Django, self-hosted in ATL-Lab, with SSO through Keycloak. The code is private. | [app](https://mandarin.antoineleflon.com) · [showcase](https://github.com/Antoine-DOT/malun) |
| **atl-preview-controller** | The lab's private staging platform: isolated Docker Compose deployments, health-checked before any traffic moves, deployed through forced-command SSH accounts. Python, with tests. | [source](https://github.com/Antoine-DOT/atl-preview-controller) |
| **second-brain** | The shared memory between me and my AI agents: an Obsidian vault with a strict schema, a dashboard script and session hooks. | [source](https://github.com/Antoine-DOT/second-brain) |
| **antoineleflon.com** | My personal site. Static React, deployed to the lab through a restricted SSH account. | [source](https://github.com/Antoine-DOT/antoineleflon.com) |

## How I work

I keep a second brain in Obsidian, inspired by Andrej Karpathy's "LLM wiki"
idea. My AI agents read it at the start of a session and update it at the end:
projects, decisions, infrastructure, what is left to do. It is the shared memory
between me and the tools I work with.

→ [The structure, scripts and hooks](https://github.com/Antoine-DOT/second-brain), without my own notes

It replaced ATL Projects, an earlier attempt of mine: a small web app in the
lab that kept tasks, ideas and decisions in versioned YAML, with scripts the
agents called at each step. It was an interesting experiment, and its core
rules survived (ideas are not actions, git and the live system come first),
but it had turned into a Rube Goldberg machine: one more server to run, back
up and firewall, and a view of technical work only. A plain Markdown vault
that I and the agents read and write directly does the same job with far less
machinery. The project is archived.

## Contact

[antoineleflon.com](https://antoineleflon.com) ·
[LinkedIn](https://www.linkedin.com/in/aleflon-cybersec/) ·
[Malt](https://www.malt.fr/profile/antoineleflon1)
