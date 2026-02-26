# .gitignore Templates Collection

This repository mirrors GitHub’s official `.gitignore` templates and makes it easy to copy ready-to-use ignore rules for different languages, frameworks, and tools.
- Official source: https://github.com/github/gitignore

## Why use this repository?

- Save time when starting new projects
- Use community-maintained ignore patterns
- Avoid committing generated files, dependencies, secrets, and local artifacts

## Quick start

Use `curl` to download a template directly into your project as `.gitignore`.

### From this mirror

```bash
curl -o .gitignore https://raw.githubusercontent.com/SafalNarsingh/gitignore/main/<TemplateName>.gitignore
```

### From GitHub official repository

```bash
curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/main/<TemplateName>.gitignore
```

## Examples

```bash
# Python project
curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/main/Python.gitignore

# Node.js project
curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/main/Node.gitignore

# Java project
curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/main/Java.gitignore

# Unity project
curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/main/Unity.gitignore
```

## How to choose a template

1. Find the language/framework you are using (for example `Python.gitignore`, `Node.gitignore`, `Go.gitignore`).
2. Download it as `.gitignore` to your project root.
3. If needed, append project-specific rules at the bottom.

## Notes

- Some projects may need multiple templates combined.
- Always review ignore rules before using them in production repositories.
