# 📚 Infrastructure Documentation Generator

Generate comprehensive infrastructure documentation automatically from your systems.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Ollama](https://img.shields.io/badge/Ollama-Compatible-green.svg)](https://ollama.com)
[![Gemma 3](https://img.shields.io/badge/Gemma-3-orange.svg)](https://ollama.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Privacy First](https://img.shields.io/badge/Privacy-First-red.svg)](#why-local)

## What It Does

- **Auto-generates infrastructure documentation** from your systems and configs
- **Architecture diagrams** in Mermaid format (rendered in GitHub)
- **Component descriptions** with Gemma 3 intelligence
- **Runbooks and procedures** for common operational tasks

## Tech Stack

- **Python 3.8+** — Documentation generation engine
- **Gemma 3** (via Ollama) — Technical writing and architecture analysis
- **Markdown** — Documentation format
- **Mermaid** — Diagram generation

## Quick Start

`ash
# Clone the repository
git clone https://github.com/kennedyraju55/infra-doc-generator.git
cd infra-doc-generator

# Install dependencies
pip install -r requirements.txt

# Pull Gemma 3 model locally
ollama pull gemma3:4b

# Generate infrastructure documentation
python generator.py --config infrastructure.yaml --output docs/
`

## Architecture

`
infra config + system metadata
    ↓
[Gemma 3 LLM Analysis] ← offline, local
    ↓
descriptions + diagrams + runbooks
    ↓
Markdown documentation
`

## Why Local?

- **Security**: Your infrastructure topology stays private and on-premises
- **Privacy**: No exposure of system architecture or configuration details
- **Control**: Generate documentation that matches your organization's standards
- **Compliance**: Keep sensitive infrastructure information within your organization

## Contributing

Contributions welcome! Please fork, create a feature branch, and submit a pull request.

## License

MIT License — see [LICENSE](LICENSE) for details.

---

*Part of 114+ privacy-first AI tools by Nrk Raju*