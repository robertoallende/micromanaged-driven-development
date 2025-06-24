# Project Plan and Dev Log

This project creates and documents the Micromanaged Driven Development (MDD) development guidelines and templates for AI-assisted software development. The development process itself follows MDD principles to demonstrate their practical application.

## Structure

This project follows MDD structure principles. Each unit represents a major development phase, with optional subunits for discrete tasks following the naming convention: `<sequence>_<unitname>[_subunit].md`

For complete MDD structure guidelines and templates, see [00_mdd.md](00_mdd.md#structure).

---

## About the Project

### What This Is

A GitHub repository that defines and demonstrates Micromanaged Driven Development (MDD) - development guidelines for controlling AI-assisted software development through systematic documentation, granular task breakdown, and chronological tracking.

### Architecture

**Documentation Structure:**
- MDD principles definition ([`00_mdd.md`](00_mdd.md))
- Self-referential project plan ([`00_main.md`](00_main.md))
- Chronological development units in `dev_log/`
- Reusable templates in `templates/`
- Example implementations in `examples/`

### Technical Stack

- **Documentation**: Markdown files
- **Version Control**: Git/GitHub
- **AI Tools**: Claude for content generation and refinement
- **Structure**: MDD organizational principles

### Core Requirements

- Clear, actionable MDD principles
- Self-demonstrating repository structure
- Reusable templates for other projects
- Comprehensive documentation of the development process
- Version tracking of MDD evolution

### Development Environment

**Setup:**
```bash
git clone https://github.com/[username]/micromanaged-driven-development
cd micromanaged-driven-development
```

**Structure Validation:**
```bash
# Verify file organization follows MDD principles
ls -la dev_log/
cat dev_log/[00_mdd.md](00_mdd.md)
```

## Project Status

### Overall Completion

~70% (Core principles defined, templates created, content improvements complete)

### Completed Features

**MDD Framework:**
- Core principles and structure definition
- File organization conventions
- Template structures for projects, units, and subunits

**Documentation:**
- Repository README.md with clear navigation
- Complete MDD principles guide ([00_mdd.md](00_mdd.md))
- Project plan following MDD structure ([00_main.md](00_main.md))

**Templates:**
- Project plan template for new MDD projects
- Unit and subunit file templates

## Units Implemented

### Completed Units

* **00**: MDD Principles Definition - Core framework and structural guidelines
* **01**: Repository Structure and Templates - Template creation and basic structure
* **02**: Content Terminology and Documentation - Content improvements and consistency fixes

### Units In Progress

*(None currently active)*

## Planned Units

### Next Steps

* **03**: Templates and Adoption Support - Template directory creation and usage guidance
* **04**: Adoption Guide and How-Tos - AI interaction best practices and troubleshooting

### Future Considerations

* Additional units may be added based on community feedback and real-world usage patterns