# modelo-latex-fork automation branch

This branch exists to host the GitHub Actions workflow that synchronizes all upstream branches and tags from:

- `https://gitlab.com/ccsl-usp/modelo-latex.git`

Operational note:

- The sync workflow preserves this `automation-sync` branch so scheduled automation remains available.
- Upstream branches and tags are force-synced daily and can also be triggered manually via **Actions**.
