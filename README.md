# Micromanaged Driven Development (MMDD)

A set of development guidelines for AI-assisted software development that emphasizes granular control and systematic documentation of the development process.

*Yes, we said micromanaged - and this time makes sense.*

## Quick Start

**Start here**: Read [`dev_log/00_mdd.md`](dev_log/00_mdd.md) for the complete MMDD principles and implementation guide.

## What is MMDD?

MMDD is a collection of practical development guidelines for building software with AI assistance. Instead of giving broad, vague prompts like "build me a web app," MMDD focuses on breaking development into specific, well-defined tasks with systematic documentation of the entire process.

Key principles include granular task breakdown, controlled AI direction, and maintaining a chronological audit trail of how your system evolved.

## Repository Structure

This repository demonstrates MMDD by using MMDD to build itself:

```
├── README.md                # This introduction file
└── dev_log/                 # Chronological development units
    ├── 00_mdd.md            # MMDD development guidelines
    ├── 00_main.md           # This project's development plan
    ├── 01_repository.md     # Repository structure and templates unit
    ├── 02_content.md        # Content terminology and documentation unit
    ├── 02_content_analysis.md    # Content analysis subunit
    ├── 02_content_planning.md    # Content planning subunit
    ├── 02_content_replacement.md # Content implementation subunit
    ├── 03_templates.md      # Templates and adoption support unit
    └── 04_adoption.md       # Adoption guide and how-tos unit
```

## How to Use

1. **Learn the Principles**: Read [`dev_log/00_mdd.md`](dev_log/00_mdd.md)
2. **See it in Action**: Check [`dev_log/00_main.md`](dev_log/00_main.md) to see how this repository was planned using MMDD
3. **Copy the MMDD Files**: Copy [`dev_log/00_mdd.md`](dev_log/00_mdd.md) into your project's `dev_log/` directory
4. **Generate Your Plan**: Use this prompt with your AI: "Using the template and guidelines in [`dev_log/00_mdd.md`](dev_log/00_mdd.md), generate a [`00_main.md`](dev_log/00_main.md) file for my project that [describe your project]"

## Why MMDD?

MMDD provides several key benefits for AI-assisted development:

- **🎯 Predictable AI Results**: Granular control leads to more reliable outputs
- **🔧 Maintainable Code**: Systematic approach produces cleaner, understandable systems
- **📚 Knowledge Transfer**: Detailed logs help other developers (and future you) understand the codebase
- **✅ Quality Assurance**: Regular validation points catch issues early

## Contributing

These principles evolve through real-world usage. Share your experiences, improve templates, or contribute examples of MMDD in action.

## License

MIT License - Use freely in your own projects.

---

*Want to see MMDD in practice? This entire repository was built using these principles - explore the `dev_log/` directory to see how.*