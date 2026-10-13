# ART test marketplace

A tiny test to check that sharing skills through a private GitHub repo works.

## Contents
- 1 plugin: `standup-tools` (version 1.0.0)
- 1 skill: `standup-formatter`

## Try it
1. Push this folder to a new **private** GitHub repo (e.g. `your-name/art-test-marketplace`).
2. In Claude: Customize > Plugins > Add marketplace > enter `your-name/art-test-marketplace` > Sync.
3. Install `standup-tools`.
4. In a new chat or Cowork task, paste:
   > make this a standup: finished the recon report, sent invoice to Thredd, today I'll review the PragmaGO UI, still waiting on API keys from client
5. You should see Yesterday / Today / Blockers and the footer `Formatted by standup-formatter v1.0.0`.

## Test versioning
1. Change `1.0.0` to `1.1.0` in BOTH `plugin.json` and the footer line in `SKILL.md`.
2. Push to GitHub.
3. In Claude, click "Check for updates" on the marketplace.
4. Run the same prompt. The footer should now say v1.1.0.
