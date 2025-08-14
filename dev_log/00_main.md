# Project Plan and Dev Log

This project creates and documents the Micromanaged Driven Development (MMDD) development methodology and templates for AI-assisted software development. The development process itself follows MMDD principles to demonstrate their practical application.

## Structure

This project follows MMDD structure principles. Each unit represents a major development phase, with optional subunits for discrete tasks following the naming convention: `<sequence>_<unitname>[_subunit].md`

For complete MMDD structure guidelines and templates, see [00_mdd.md](00_mdd.md#structure).

---

## About the Project

### What This Is

A GitHub repository that defines and demonstrates Micromanaged Driven Development (MMDD) - development methodology for controlling AI-assisted software development through systematic documentation, granular task breakdown, and chronological tracking.

### Architecture

**Documentation Structure:**
- MMDD principles definition ([`00_mdd.md`](00_mdd.md))
- Self-referential project plan ([`00_main.md`](00_main.md))
- Chronological development units in `dev_log/`
- Reusable templates in `templates/`
- Example implementations in `examples/`

### Technical Stack

- **Documentation**: Markdown files
- **Version Control**: Git/GitHub
- **AI Tools**: Claude for content generation and refinement
- **Structure**: MMDD organizational principles

### Core Requirements

- Clear, actionable MMDD principles
- Self-demonstrating repository structure
- Reusable templates for other projects
- Comprehensive documentation of the development process
- Version tracking of MMDD evolution

### Development Environment

**Setup:**
```bash
git clone https://github.com/[username]/micromanaged-driven-development
cd micromanaged-driven-development
```

**Structure Validation:**
```bash
# Verify file organization follows MMDD principles
ls -la dev_log/
cat dev_log/[00_mdd.md](00_mdd.md)
```

## Project Status

### Overall Completion

~85% (Core principles defined, templates created, content improvements and abbreviation update complete, small organizational changes in progress)

### Completed Features

**MMDD Methodology:**
- Core principles and structure definition
- File organization conventions
- Template structures for projects, units, and subunits

**Documentation:**
- Repository README.md with clear navigation
- Complete MMDD principles guide ([00_mdd.md](00_mdd.md))
- Project plan following MMDD structure ([00_main.md](00_main.md))

**Templates:**
- Project plan template for new MMDD projects
- Unit and subunit file templates

## Units Implemented

### Completed Units

* **00**: MMDD Principles Definition - Core methodology and structural principles
* **[01](01_repository.md)**: Repository Structure and Templates - Template creation and basic structure
* **[02](02_content.md)**: Content Terminology and Documentation - Content improvements and consistency fixes
* **[05](05_mmdd.md)**: Abbreviation Change - MDD to MMDD - Updated all abbreviations throughout project
* **[06](06_smallchanges.md)**: Small Changes - File renaming, reference updates, and project cleanup

### Units In Progress

*(None currently active)*

## Planned Units

### Next Steps

*(No active units currently planned)*

### Future Considerations

* Additional units may be added based on community feedback and real-world usage patterns