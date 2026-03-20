# Tool Input Examples — Selection Guidance

## Purpose

Improve tool selection accuracy by providing concrete input examples for the most-used tools. When choosing which tool to use, reference these examples to match the current task to the correct tool.

## Tool Examples

### git — Version Control
Use for repository state, history, and branch management.
- **Check changes:** `git diff --stat` — file-level summary of uncommitted changes
- **Recent history:** `git log --oneline -10` — last 10 commits with conventional messages
- **Branch comparison:** `git diff main...HEAD --stat` — all changes since branching from main

### github-cli — GitHub Operations
Use for PRs, issues, and repository management.
- **Create PR:** `gh pr create --title 'feat: ...' --body '## Summary...'`
- **List issues:** `gh issue list --state open --label bug`
- **PR status:** `gh pr view 123 --json reviews,statusCheckRollup`

### npm — Package Management
Use for dependency management, scripts, and project lifecycle.
- **Install deps:** `npm install` — install all project dependencies
- **Run script:** `npm run dev` — start development server
- **Add package:** `npm install axios --save` — add production dependency
- **Dev dependency:** `npm install jest --save-dev` — add test framework
- **Run tests:** `npm test` — execute test suite
- **Audit:** `npm audit` — check for known vulnerabilities

### node — Runtime Execution
Use for running scripts, REPL operations, and debugging.
- **Run script:** `node scripts/setup.js` — execute a setup script
- **Evaluate expression:** `node -e "console.log(process.version)"` — quick evaluation
- **Check version:** `node --version` — verify Node.js version
- **Run with env:** `NODE_ENV=production node server.js` — run with environment variable
