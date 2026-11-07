# Hermes + ChatGPT workspace

Shared workspace for Hermes Agent (Nous Research) and ChatGPT.

## What lives here
- `docs/`: setup and collaboration instructions.
- `projects/`: source code and project documentation.
- `config/`: non-secret configuration templates.

**Important:** GitHub stores code and files; it does not run Hermes continuously. Install and run Hermes Agent on your Mac or a server. ChatGPT and Hermes can collaborate through commits, branches and pull requests. A direct API connection requires a separately configured, secured integration.

## First-time setup on macOS
1. Review the current official Hermes Agent installation instructions: https://github.com/NousResearch/hermes-agent
2. Install and configure Hermes locally.
3. Install Git and authenticate with GitHub (prefer SSH or GitHub CLI).
4. Clone this repository:
   ```bash
   git clone https://github.com/dolidzeyana88-spec/hermes.git
   cd hermes
   ```
5. Work in a feature branch, commit code, then open a pull request.

## Security
This repository was detected as **public** on initial setup. Never commit API keys, tokens, passwords, client records, or personal information. Keep secrets in local environment files excluded by `.gitignore`. For confidential company projects, change visibility to Private in GitHub settings before uploading them.

See [docs/WORKFLOW.md](docs/WORKFLOW.md).
