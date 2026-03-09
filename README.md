# py-memory-optimizer

![Audit](https://img.shields.io/badge/audit%3A%20PASS-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![OpenClaw](https://img.shields.io/badge/OpenClaw-skill-orange)

> Automatically analyzes Python code and suggests memory usage optimizations for improved performance

## Features

- **Static Code Analysis**: Parses Python source files using the AST module to analyze code structure without execution
- **Pattern Detection**: Identifies common memory-intensive patterns (large list comprehensions, unnecessary object creation, improper generator usage)
- **Leak Detection**: Finds potential memory leaks from circular references, unclosed resources, and global variable accumulation
- **Optimization Suggestions**: Provides specific, actionable recommendations with estimated memory impact
- **Framework Support**: Handles Python 3.8+ and common frameworks (Django, Flask, FastAPI patterns)
- **CLI Interface**: Command-line tool for integration into development workflows
- **Report Generation**: Creates detailed analysis reports in multiple formats (JSON, markdown, plain text)

## Quick Start
## Installation

```bash
npm install --global openclaw-skill-py-memory-optimizer
```

The skill will automatically install Python dependencies on first run.

## GitHub

Source code: [github.com/NeoSkillFactory/py-memory-optimizer](https://github.com/NeoSkillFactory/py-memory-optimizer)

**Price suggestion:** $19.99 USD

## License

MIT © NeoSkillFactory
