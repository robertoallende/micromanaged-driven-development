# Unit 7: Workflow Documentation

## Objective

Add comprehensive workflow guidance to the MMDD methodology, providing practical step-by-step instructions for applying MMDD principles to both initial project setup and ongoing unit development.

## Implementation

Added a new "Workflow" section to `00_mmdd.md` (lines 106-171) that defines a systematic 5-step cycle:

1. **Create Context** - Establish shared understanding before planning
   - For the project: Discuss domain, goals, constraints
   - For each unit: Verify AI understands objectives and dependencies
   - Key question: "Do we both understand what we're trying to accomplish and why?"

2. **Plan and Define** - Formalize the approach in markdown
   - Project: Draft `00_main.md` with architecture and unit breakdown (3-5 units recommended)
   - Units: Create unit files with objectives and implementation approach
   - Developer action: Review and approve before proceeding

3. **Implementation** - Execute in small chunks
   - Decide on subunit structure (combined vs. separate tests)
   - For code units: Choose between separate implementation/test subunits or combined approach
   - For non-code units: Break down into logical subunits as needed
   - Best practice: Implement incrementally with validation

4. **Test and Validate** - Verify objectives are met
   - AI helps execute tests and provide summaries
   - Developer confirms integration and objective achievement

5. **Commit** - Finalize with structured git commits
   - Standardized commit message formats:
     - Project setup: `Complete Project Plan`
     - Units: `Complete Unit XX: [Unit Name]`
     - Subunits: `Complete Unit XX: [Unit Name] - [Subunit Name]`
   - Update markdown status before committing

### Workflow Tips Added

- Reference relevant units for context maintenance
- Document deviations from original plans
- Keep iterations visible through subunits
- "Context is cheap, confusion is expensive" - prioritize Step 1 clarity

## AI Interactions

AI (Claude) provided analysis and summary of the Workflow section additions after reading the updated `00_mmdd.md` file, confirming the structure and key points of the new workflow guidance.

## Files Modified

- `dev_log/00_mmdd.md` - Added Workflow section (lines 106-171)
- `dev_log/07_workflow.md` - Created this unit documentation

## Status: Complete

The Workflow section successfully bridges the gap between MMDD's structural templates and practical application, providing clear guidance for both developers and AI assistants on how to systematically approach software development using the MMDD methodology.
