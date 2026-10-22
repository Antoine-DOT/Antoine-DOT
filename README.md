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

→ [Write-up on my site](https://antoineleflon.com/en/projects/atl-lab)

## Projects

| Project | What it is | |
| --- | --- | --- |
| **Malun** | Mandarin learning app (flashcards, TOCFL levels). Django, self-hosted in ATL-Lab, with SSO through Keycloak. The code is private. | [mandarin.antoineleflon.com](https://mandarin.antoineleflon.com) |
| **antoineleflon.com** | My personal site. Static React, deployed to the lab through a restricted SSH account. | [source](https://github.com/Antoine-DOT/antoineleflon.com) |
| **Subli** | A small tool for the game Wakfu: find which sublimations fit a piece of gear. | [source](https://github.com/Antoine-DOT/subli) |

## How I work

I keep a second brain in Obsidian, inspired by Andrej Karpathy's "LLM wiki"
idea. My AI agents read it at the start of a session and update it at the end:
projects, decisions, infrastructure, what is left to do. It is the shared memory
between me and the tools I work with.

→ [The structure, scripts and hooks](https://github.com/Antoine-DOT/second-brain), without my own notes

## Contact

[antoineleflon.com](https://antoineleflon.com) ·
[LinkedIn](https://www.linkedin.com/in/aleflon-cybersec/) ·
[Malt](https://www.malt.fr/profile/antoineleflon1)
