# Micromanaged Driven Development (MMDD) - version 2

These development guidelines use systematic documentation to control AI-assisted software development through granular task breakdown and chronological tracking.

## Structure

A **unit** represents a major phase or component in the development process. Each unit may contain one or more **subunits**, which capture discrete build moments such as design decisions, iterations, or integrations.

Each unit/subunit is recorded in a markdown file within `dev_log/`, following the naming convention:

```
<sequence>_<unitname>[_subunit<number|name>].md
```

The `subunit` part is optional. Files are ordered using numeric prefixes to allow flexible sequencing.

## File Organization

```
project/
├── README.md            # Main project description
├── dev_log/             # Chronological development units
│   ├── 00_mdd.md        # MMDD Description and MMDD version 
│   ├── 00_main.md       # Main project status and unit index
│   └── 01_first_unit.md # First Unit of your project, rename this file according to it
└── src/                 # Source code
```

## [01_main.md](01_main.md) Template

```markdown
# Project Plan and Dev Log

Brief project description and development approach.

## Structure
[Explain unit/subunit organization and naming convention]

## About the Project
### What This Is
[Project purpose and scope]

### Architecture
[High-level system design]

### Technical Stack
[Technologies and tools]

## Project Status
### Overall Completion
[Percentage or status]

### Completed Features
[Implementation summary with metrics]

## Units Implemented
### Completed Units
* **01**: Unit Name - Brief description

### Units In Progress
#### 02. Current Unit Name
**Status:** [What's done, what's pending]

## Planned Units
* **03**: Future Unit - Description
```

## Unit File Template

```markdown
# Unit [N]: [Unit Name]

## Objective
[What this unit accomplishes]

## Implementation
[Technical approach and key decisions]

## AI Interactions
[How AI was used, effective prompts, iterations]

## Files Modified
[Source files created or changed]

## Status: [Complete/In Progress]
[Completion notes and metrics]
```

## Subunit File Template

```markdown
# Unit [N]: [Unit Name] - Subunit: [Subunit Name]

## Objective
[Specific subunit goal within the larger unit]

## Implementation
[Technical details and approach]

## AI Interactions
[Specific AI usage for this subunit]

## Status: [Complete/In Progress]
[Integration notes and next steps]
```

## Usage

1. **Setup**: Create [01_main.md](01_main.md) and dev_log/ directory
2. **Plan Units**: Define 3-5 initial development phases
3. **Work Systematically**: Complete units sequentially, document AI interactions
4. **Track Progress**: Update [01_main.md](01_main.md) status regularly
5. **Provide Context**: Reference unit files when working with AI tools