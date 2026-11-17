# Team toolshed

The skills your team shares with each other in Claude. Every skill in the `skills` folder reaches everyone in your Claude organisation.

This repository was made from the AI Momentum Guild toolshed template. Keep it **private**.

## Setting it up

Follow the setup page you were given. In short:

1. Install the Claude GitHub App on your GitHub organisation, for this repository only.
2. In Claude admin settings, open Plugins & skills and choose Sync from GitHub with this repository.
3. Set the toolshed to Installed by default.
4. Start a new chat and say "run the toolshed check".

Give your colleagues `USERS-GUIDE.md`: one page on using the toolshed. Builders who use Claude Code with AI Dev Foundations also run the `toolshed-connect` skill once, which adds the config file those skills need.

## Rules for this repository

- One folder per skill in `skills`, each with a `SKILL.md`
- No passwords, keys or customer data in any skill
- Every change moves the version in `.claude-plugin/plugin.json` up (1.0.4 to 1.0.5). Claude only picks up a change when the version moves
- A chat that is already open does not pick up a new skill; start a new chat
