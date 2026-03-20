# Contributing to aios-god-mode-template

## Development Setup

```bash
git clone https://github.com/gutomec/aios-god-mode-template.git
cd aios-god-mode-template
```

No dependencies to install — this is a pure template repository.

## Making Changes

### Template files

All installable files live under `template/`. When adding or modifying files:

1. Make your changes in `template/`
2. Recalculate checksums: `find template -type f | sort | while read f; do echo "\"$f\": \"$(sha256sum "$f" | cut -d' ' -f1)\""; done`
3. Update `template.json` with the new checksums
4. If adding a new top-level category, add it to `template.json` → `files`

### Checksums

The `template.json` checksums ensure file integrity during installation. **Every PR that modifies template files must update checksums.**

CI will fail if checksums don't match.

### Skill files

Skills must have YAML frontmatter with at minimum:

```yaml
---
name: skill-name
description: What the skill does
---
```

## GitHub Actions Secrets

This repository uses the following secrets:

| Secret | Required | Purpose |
|--------|----------|---------|
| `GITHUB_TOKEN` | Auto-provided | CI checks, release creation |

No additional secrets are required. The CI workflow uses only Node.js built-in modules.

## Release Process

1. Update `template.json` → `version` to the new version
2. Commit: `git commit -m "chore: bump version to X.Y.Z"`
3. Tag: `git tag vX.Y.Z`
4. Push: `git push origin main --tags`
5. GitHub Actions creates the release automatically

## Quality Checks

The CI pipeline validates:

- `template.json` structure and required fields
- All checksummed files exist
- SHA256 checksums match
- YAML files are valid
- SKILL.md frontmatter is complete
- `settings.json` schema is correct
- Internal links in README are not broken

## Code Review

This repository uses [CodeRabbit](https://coderabbit.ai/) for automated PR review. Configuration is in `.coderabbit.yaml`.
