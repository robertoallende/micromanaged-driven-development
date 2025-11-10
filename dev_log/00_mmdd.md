# Micromanaged Driven Development (MMDD) - version 3

This development methodology uses systematic documentation to control AI-assisted software development through granular task breakdown and chronological tracking.

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

## [00_main.md](00_main.md) Template

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
## Workflow

MMDD follows a 5-step cycle that applies both to initial project setup and to each individual unit. This systematic approach ensures clarity and mutual understanding between the developer and AI assistant.

### The 5-Step Cycle

#### 1. Create Context
Establish shared understanding before any planning or implementation.

**For the project:** Discuss the problem domain, overall goals, technical constraints, and available tools.

**For each unit:** Verify the AI understands the specific objective, how it fits into the larger project, relevant technical details, and any dependencies on previous units.

**Key question:** "Do we both understand what we're trying to accomplish and why?"

#### 2. Plan and Define
With context established, formalize the approach in markdown.

**For the project:** The AI drafts `00_main.md` with project description, architecture, technical stack, and initial unit breakdown (3-5 units recommended).

**For each unit:** The AI creates the unit file (e.g., `02_authentication.md`) with clear objectives, implementation approach, and success criteria.

**Developer action:** Review the plan and approve before proceeding, or iterate until the plan is solid.

#### 3. Implementation
Execute the plan in small, manageable chunks.

**For code units:** Decide whether to combine or separate implementation and tests:
- Ask: "Should I create separate subunits for implementation and tests, or combine them?"
- If separate: Create `0X_unitname_subunit_implementation.md` and `0X_unitname_subunit_tests.md`
- If combined: Include testing approach in the main unit file

**For non-code units:** Break down into logical subunits as needed (design, integration, configuration, etc.)

**Best practice:** Implement incrementally, validating each piece before moving forward.

#### 4. Test and Validate
Verify the implementation meets the unit's objectives.

**AI's role:** 
- Help execute tests (manual or automated)
- Provide a concise summary of what was implemented
- List the main validation points to check

**Developer action:** Confirm the unit achieves its stated objectives and integrates properly with existing work.

#### 5. Commit
Finalize the unit with a structured git commit.

**Commit message format:**

Title line (first line):
- For project setup: `Complete Project Plan`
- For units: `Complete Unit XX: [Unit Name]`
- For subunits: `Complete Unit XX: [Unit Name] - [Subunit Name]`

Body (after blank line):
- Provide a concise description of what was implemented or changed
- List key files modified or features added
- Keep it focused on the "what" and "why" rather than detailed "how"

Example:
```
Complete Unit 07: Workflow Documentation

Added comprehensive Workflow section to 00_mmdd.md defining a 5-step cycle
for MMDD application: Create Context, Plan and Define, Implementation,
Test and Validate, and Commit. Includes practical tips for maintaining
context and documenting iterations.

Updated 00_main.md to reflect Unit 7 completion and increased project
completion to ~90%.
```

**Before committing:** Ensure the unit's markdown file status is updated to "Complete" and `00_main.md` reflects the current project state.

### Workflow Tips

**Reference relevant units:** When starting a new unit, provide the AI with `00_main.md` and any directly related unit files to maintain context.

**Document deviations:** If implementation diverges from the plan, update the unit file to reflect what actually happened and why.

**Keep iterations visible:** When a unit requires multiple attempts or significant refactoring, consider creating subunits to capture each iteration's learning.

**Context is cheap, confusion is expensive:** When in doubt, spend extra time on Step 1. Five minutes of clarification prevents hours of rework.

## Usage

1. **Setup**: Create [00_main.md](00_main.md) and dev_log/ directory
2. **Plan Units**: Define 3-5 initial development phases
3. **Work Systematically**: Complete units sequentially, document AI interactions
4. **Track Progress**: Update [00_main.md](00_main.md) status regularly
5. **Provide Context**: Reference unit files when working with AI tools

