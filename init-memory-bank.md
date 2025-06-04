# Memory Bank Initialization Guide

This guide provides step-by-step instructions for setting up a new memory bank system for the AI Socratic Coding Tutor.

## When to Initialize a Memory Bank

### New Student Context:
- First time working with a new student
- Starting a completely new topic/course with an existing student
- Resetting after a long break (>1 month)

### Returning Student Context:
- Student returns after short break (<1 week)
- Continuing with same topic/project
- Only update `active-session.md`, keep other files

## Directory Structure Setup

Create the following directory structure:
```
memory-bank/
├── active-session.md
├── common-student-issues.md
├── knowledgebase.md
├── progress.md
├── student-profile.md
└── tutoring-insights.md
```

## Step-by-Step Initialization Process

### Step 1: Create Directory
```bash
mkdir memory-bank
cd memory-bank
```

### Step 2: Initialize Core Files

#### For New Student Setup:

1. **Create `active-session.md`** - Start with blank template
2. **Create `student-profile.md`** - Fill in known information
3. **Create `progress.md`** - Start with empty concept tracking
4. **Create `tutoring-insights.md`** - Start with base template
5. **Create `knowledgebase.md`** - Include common concepts for the subject area
6. **Create `common-student-issues.md`** - Include relevant issues for the topic

#### For Returning Student Setup:

1. **Update `active-session.md`** - Clear previous session, prepare for new topic
2. **Review `student-profile.md`** - Update if learning goals changed
3. **Review `progress.md`** - Add any achievements since last session
4. Keep other files as-is unless significant gaps identified

## Initial Content Guidelines

### For `student-profile.md`:
- Fill in any known learning goals
- Note preferred programming language
- Leave observation fields blank initially
- Update as you learn about the student

### For `progress.md`:
- Start with "To Learn" status for most concepts
- If continuing student, mark previously mastered concepts
- Focus on current learning objectives

### For `knowledgebase.md`:
- Include concepts relevant to stated learning goals
- Start with fundamental concepts (variables, functions, loops)
- Add language-specific concepts as needed

### For `common-student-issues.md`:
- Include issues relevant to the programming language/topic
- Start with universal issues (logic errors, syntax errors)
- Add domain-specific issues (web dev, data science, etc.)

### For `tutoring-insights.md`:
- Start with base template
- Include any known effective analogies for the subject area
- Keep observation sections empty initially

### For `active-session.md`:
- Always start empty
- Fill in as session begins

## Validation Checklist

After initialization, verify:

- [ ] All 6 memory bank files exist
- [ ] Each file has proper purpose statement at top
- [ ] No placeholder content remains (replace [...] with actual content or leave appropriately blank)
- [ ] Student identifier is consistent across files
- [ ] File cross-references work correctly
- [ ] Templates are ready for immediate use

## Quality Gates

### Completeness Check:
- [ ] Directory structure matches specification
- [ ] All files have proper headers and purpose statements
- [ ] Cross-references between files are accurate
- [ ] No broken markdown links

### Readiness Check:
- [ ] Files can be used immediately for tutoring session
- [ ] Agent can follow the workflow described in `memory-bank-prompt.md`
- [ ] Student-specific information is captured where known
- [ ] Generic templates are ready for population during tutoring

## Common Initialization Scenarios

### Scenario 1: Complete Beginner in Python
**Initialize with:**
- Basic Python concepts in `knowledgebase.md`
- Common beginner issues in `common-student-issues.md`
- Empty `progress.md` with fundamental concepts listed as "To Learn"

### Scenario 2: Experienced Programmer Learning New Language
**Initialize with:**
- Language-specific concepts and differences
- Common misconceptions for experienced programmers
- Faster progression expected in `progress.md`

### Scenario 3: Student Returning After Break
**Initialize with:**
- Review and update existing files
- Clear `active-session.md`
- Assess knowledge retention in `progress.md`

## Maintenance Notes

- Review initialization setup after first few sessions
- Adjust templates based on actual tutoring patterns
- Document any initialization improvements in `tutoring-insights.md`
- Keep this guide updated as the system evolves

## File Templates Location

All file templates are located in the same directory as this initialization guide. Copy the template content and customize for each specific student context.

---

*This initialization process should take 5-10 minutes for new students, 2-3 minutes for returning students.*
