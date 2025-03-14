# Contributing to Model Configurator

We welcome contributions from the community! Whether you're fixing bugs, adding new features, or improving documentation, your help makes this project better for everyone.

## How to Contribute

### 1. Reporting Issues
- **Bug Reports**: 
  - Include: OS version, Python version, steps to reproduce, error logs
  - Add `bug` label
  
- **Feature Requests**:
  - Explain the problem you're solving
  - Add `enhancement` label

### 2. Development Workflow

1. **Fork** the repository
2. Create a **feature branch**:
   ```bash
   git checkout -b feat/your-feature-name
   # or
   git checkout -b fix/issue-number-short-desc
   ```
3. Follow our coding standards:
   - PEP8 style guide
   - Type hints for all functions
   - Docstrings following Google-style format
4. Update documentation if needed
5. **Push** to your fork
6. Create a **Pull Request**

### 3. Architecture
  - Keep core logic in `configurator.py`
  - Base classes in `config.py`

## Development Setup
1. Use our pre-commit hooks:
   - Auto-formatting (black)
   - Linting (flake8)
   - Type checking (mypy)

## Recognition

All significant contributions will be:
- Highlighted in release notes
- Added to contributors list

Let's build better deployment tools together! 🛠️🚀
