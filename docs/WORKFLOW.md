# Collaboration workflow

1. Describe the task and acceptance criteria in ChatGPT.
2. Create or update a project folder in this repository.
3. Hermes Agent works locally on the cloned repository, in a separate feature branch.
4. Hermes opens a pull request for review.
5. ChatGPT can inspect the repository changes and recommend or implement fixes.
6. Merge only after reviewing code and testing.

## Boundaries
- The repository is file storage and version history, **not** a hosted Hermes runtime.
- ChatGPT's GitHub connector and Hermes's local git access are distinct authorizations.
- A direct HTTP/API-to-ChatGPT connection is **not configured** by these files.
- Never expose the local Hermes API publicly without strong authentication and transport security.
- Keep secrets out of source control; use a secret manager or private local environment.
