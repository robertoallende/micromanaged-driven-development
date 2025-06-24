# Project Plan and Dev Log

This project creates and documents the Micromanaged Driven Development (MDD) guiding principles and templates for AI-assisted software development. The development process itself follows MDD principles to demonstrate their practical application.

## Structure

A **unit** represents a major phase or component in the development process. Each unit may contain one or more **subunits**, which capture discrete build moments such as design decisions, iterations, or integrations.

Each unit/subunit is recorded in a markdown file within `dev_log/`, following the naming convention:

```
<sequence>_<unitname>[_subunit<number|name>].md
```

The `subunit` part is optional. Files are ordered using numeric prefixes to allow flexible sequencing.

---

## About the Project

### What This Is

A GitHub repository that defines and demonstrates Micromanaged Driven Development (MDD) - guiding principles for controlling AI-assisted software development through systematic documentation, granular task breakdown, and chronological tracking.

### Architecture

**Documentation Structure:**
- MDD principles definition (`00_mdd.md`)
- Self-referential project plan (`00_main.md`)
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
cat dev_log/00_mdd.md
```

## Project Status

### Overall Completion

~75% (Core principles defined, templates created, documentation in progress)

### Completed Features

**MDD Framework:**
- Core principles and structure definition
- File organization conventions
- Template structures for projects, units, and subunits

**Documentation:**
- Repository README.md with clear navigation
- Complete MDD principles guide (00_mdd.md)
- Project plan following MDD structure (00_main.md)

**Templates:**
- Project plan template for new MDD projects
- Unit and subunit file templates

## Units Implemented

### Completed Units

* **00**: MDD Principles Definition - Core framework and structural guidelines

### Units In Progress

#### 01. Repository Structure and Templates

**Template Creation:**
* Project plan template for reuse
* Unit file template with standard sections
* Subunit template for detailed tracking

**Documentation:**
* README.md for repository introduction
* Usage examples and best practices

**Status:** Templates complete, documentation refinement in progress

### Units In Progress

#### 02. Content Refinement and Examples

**Documentation Polish:**
* Refine MDD principles based on practical usage
* Improve template clarity and completeness
* Add troubleshooting and common patterns

**Example Projects:**
* Create sample MDD implementation
* Document real-world usage patterns

**Status:** Planned, pending completion of Unit 01

## Planned Units

* **03**: Community Guidelines and Contribution Framework
* **04**: Tooling and Automation Support
* **05**: Advanced MDD Patterns and Variations