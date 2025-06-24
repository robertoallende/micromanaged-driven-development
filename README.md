# Micromanaged Driven Development (MDD)

A set of guiding principles for AI-assisted software development that emphasizes granular control and systematic documentation of the development process.

## Quick Start

**Start here**: Read [`dev_log/00_mdd.md`](dev_log/00_mdd.md) for the complete MDD principles and implementation guide.

## What is MDD?

MDD is a collection of practical principles for building software with AI assistance. Instead of giving broad, vague prompts like "build me a web app," MDD focuses on breaking development into specific, well-defined tasks with systematic documentation of the entire process.

Key principles include granular task breakdown, controlled AI direction, and maintaining a chronological audit trail of how your system evolved.

## Repository Structure

This repository demonstrates MDD by using MDD to build itself:

```
├── README.md                # This introduction file
└── dev_log/                 # Chronological development units
    ├── 00_mdd.md            # MDD principles and guide
    ├── 00_main.md           # This project's development plan
    ├── 01_template_creation.md
    └── 02_documentation_writing.md
```

## How to Use

1. **Learn the Principles**: Read [`dev_log/00_mdd.md`](dev_log/00_mdd.md)
2. **See it in Action**: Check [`dev_log/00_main.md`](dev_log/00_main.md) to see how this repository was planned using MDD
3. **Copy the MDD Files**: Copy `dev_log/00_mdd.md` into your project's `dev_log/` directory
4. **Generate Your Plan**: Use this prompt with your AI: "Using the template and guidelines in `dev_log/00_mdd.md`, generate a `00_main.md` file for my project that [describe your project]"

## Why MDD?

- **Predictable AI Results**: Granular control leads to more reliable outputs
- **Maintainable Code**: Systematic approach produces cleaner, understandable systems
- **Knowledge Transfer**: Detailed logs help other developers (and future you) understand the codebase
- **Quality Assurance**: Regular validation points catch issues early

## Contributing

These principles evolve through real-world usage. Share your experiences, improve templates, or contribute examples of MDD in action.

## License

MIT License - Use freely in your own projects.

---

*Want to see MDD in practice? This entire repository was built using these principles - explore the `dev_log/` directory to see how.*