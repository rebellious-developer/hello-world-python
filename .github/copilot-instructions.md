# Copilot Instructions for hello-world-python

## Project Overview

This is a minimal Python training project created to demonstrate Git workflow fundamentals for Future Connect certification. The project is intentionally simple and serves as a foundational template.

## Project Structure

Currently minimal structure:
- `README.md` - Primary documentation covering Git setup and repository creation workflow
- No Python code files yet (this is a starting point for Python exercises)

## Development Environment

### System Configuration
- **OS**: Ubuntu LTS
- **Version Control**: Git (latest via PPA)
- **SSH**: ed25519 key authentication for GitHub
- **CLI Tools**: GitHub CLI (gh) for repository management

### Git Configuration
- **Default branch**: `main`
- **Line endings**: LF (Unix-style) - configured globally with `core.eol lf`
- **Global ignore**: Uses `~/.git` ignore file for system-wide exclusions
- **Remote**: origin → `git@github.com:rebellious-developer/hello-world-python.git`

## Key Workflows

### Creating New Python Files
When adding Python code to this project:
1. Create `.py` files in the root directory (no complex structure needed for training exercises)
2. Follow standard Python conventions (PEP 8)
3. Add executable permissions if creating scripts: `chmod +x filename.py`

### Git Workflow
Standard workflow used in this project:
```bash
git add <files>
git commit -m "descriptive message"
git push origin main
```

For new features, the project owner uses GitHub CLI for repo operations.

## Project Context

This is a **training/certification project** under the Future Connect organization:
- Focus on demonstrating Git competency, not complex Python development
- Additions should be educational and incrementally build skills
- Document learning steps in README.md when appropriate
- Keep structure simple and beginner-friendly

## Python Guidelines

When adding Python code:
- Start with simple console applications (`print()` statements are fine)
- No frameworks or complex dependencies initially
- Add `requirements.txt` only when external packages are needed
- Use descriptive filenames that indicate the exercise purpose (e.g., `01_hello_world.py`, `02_variables.py`)

## Testing Approach

No formal testing framework currently configured. When adding tests:
- Use Python's built-in `unittest` or `pytest` for simplicity
- Create a `tests/` directory when needed
- Document test execution in README.md
