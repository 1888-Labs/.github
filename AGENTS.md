# AGENTS.md

Guidance for AI coding agents working in this repository.

## What this repo is

This is the `.github` repository for the [1888 Labs](https://github.com/1888-Labs) GitHub organization. It holds the public org profile and org-wide GitHub defaults. It contains no application code.

## Layout

- `profile/README.md`: the org profile shown at github.com/1888-Labs. This is the main file in the repo.
- `AGENTS.md`: this file.

Do not add a top-level `README.md`. GitHub only renders `profile/README.md` on the org page, and a second README causes confusion.

## Editing the profile

- Keep it simple, plain Markdown, and text-first. No logos, badges, or banners unless asked.
- Match the existing voice: calm, technical, and direct. Avoid hype and marketing language.
- Keep the section order: intro, What We Work On, How We Build, Projects, Research Interests, Principles, Contributing, Connect.
- When adding a project, follow the existing format: a `###` heading with the project name, then a one- or two-sentence description. Link to the repo only once it exists under the `1888-Labs` org.
- Do not invent projects, links, contact details, or claims about the lab.

## Commits

- Use one-line [Conventional Commits](https://www.conventionalcommits.org/) messages, for example `docs: add ProofStream to projects`.
- No commit body.
- Do not push without the maintainer's approval.
