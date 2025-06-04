# Product Requirements Document (PRD)
## Memory Bank System for AI Socratic Coding Tutor - MVP

### Project Overview
Create a coherent, functional memory system for an AI agent that performs as a Socratic coding tutor. The system consists of structured markdown files that maintain context, student progress, and tutoring insights across interactions.

---

## Current State Analysis

### Issues Identified:
1. **Redundancy**: Multiple files contain overlapping content and duplicate sections
2. **Inconsistent File Structure**: Files have mixed formats, incomplete templates, and conflicting information
3. **Unclear File Boundaries**: Overlapping responsibilities between `memory-bank-prompt.md` and `system-prompt.md`
4. **Language Confusion**: `system-prompt.md` mentions C-specific tutoring while `memory-bank-prompt.md` is language-agnostic
5. **Incomplete Boilerplates**: Memory bank files are not ready-to-use templates
6. **Missing Initialization Process**: No clear process for setting up a new memory bank
7. **File Naming Issues**: `active-sesion.md` has a typo in filename

---

## Implementation Tasks Checklist

### Task 1: Documentation Review and Analysis ✅
- [x] Review `memory-bank-prompt.md` for core system architecture
- [x] Review `system-prompt.md` for agent identity and behavior
- [x] Analyze all memory bank files for content and structure
- [x] Identify redundancies, conflicts, and missing elements
- [x] Document current state and issues

### Task 2: Remove Redundancy from All Files ✅
- [x] **2.1** Remove duplicate content from `tutoring-insights.md` (has 3 different sections with similar content)
- [x] **2.2** Eliminate overlapping information between `student-profile.md` and `progress.md`
- [x] **2.3** Consolidate duplicate examples and templates within individual files
- [x] **2.4** Remove conflicting file references and broken markdown links
- [x] **2.5** Clean up inconsistent formatting and structure across files

### Task 3: Create Ready-to-Use Boilerplate Templates ✅
- [x] **3.1** Transform `active-session.md` (fix typo: `active-sesion.md` → `active-session.md`)
  - Clear, structured template for session tracking
  - Remove example content, keep structure only
  - Add proper placeholders and instructions
- [x] **3.2** Standardize `student-profile.md`
  - Remove duplicate sections
  - Create clear template with placeholder fields
  - Define when and how to update this file
- [x] **3.3** Restructure `progress.md`
  - Remove duplicate content
  - Create consistent tracking format
  - Remove broken markdown links
- [x] **3.4** Refactor `knowledgebase.md`
  - Create proper template structure for adding concepts
  - Remove placeholder content and add clear instructions
- [x] **3.5** Clean up `common-student-issues.md`
  - Standardize issue template format
  - Add more comprehensive examples
  - Remove markdown link references that don't work
- [x] **3.6** Consolidate `tutoring-insights.md`
  - Remove duplicate sections
  - Create single, clear structure
  - Focus on actionable insights only

### Task 4: Define Memory Bank Initialization Routine ✅
- [x] **4.1** Create `init-memory-bank.md` with step-by-step setup instructions
- [x] **4.2** Define directory structure creation process
- [x] **4.3** Specify initial content for each file
- [x] **4.4** Create validation checklist for properly initialized memory bank
- [x] **4.5** Document the difference between "new student" vs "returning student" initialization

### Task 5: Establish Clear Coherence Between Core Files ✅
- [x] **5.1** Define `system-prompt.md` scope:
  - Core agent identity and behavior
  - Universal Socratic tutoring principles
  - General interaction guidelines
  - Language-agnostic tutoring approach
- [x] **5.2** Define `memory-bank-prompt.md` scope:
  - Memory system architecture and workflow
  - File usage instructions and relationships
  - Memory maintenance processes
  - Session management protocols
- [x] **5.3** Remove language-specific content from `system-prompt.md` (C-specific references)
- [x] **5.4** Ensure `memory-bank-prompt.md` focuses purely on memory system operations
- [x] **5.5** Create clear integration points between the two files
- [x] **5.6** Document when to reference each file and for what purpose

### Task 6: Ensure System Coherence and Alignment ✅
- [x] **6.1** Validate that all files support the core mission: Socratic coding tutoring
- [x] **6.2** Ensure consistent terminology across all files
- [x] **6.3** Align file update workflows with practical tutoring scenarios
- [x] **6.4** Verify that memory persistence strategy actually works for intended use cases
- [x] **6.5** Test file interdependencies and references
- [x] **6.6** Ensure scalability for multiple students and long-term use

### Task 7: Eliminate Function Overlap Between Files ✅
- [x] **7.1** Map current functions of each file
- [x] **7.2** Identify overlapping responsibilities
- [x] **7.3** Reassign functions to appropriate files based on logical boundaries:
  - **active-session.md**: Current conversation state only
  - **progress.md**: Long-term learning progression only
  - **student-profile.md**: Static student characteristics only
  - **tutoring-insights.md**: Generalizable tutoring patterns only
  - **knowledgebase.md**: Concept-specific information only
  - **common-student-issues.md**: Error patterns and diagnostic questions only
- [x] **7.4** Update cross-references between files
- [x] **7.5** Remove duplicate functionality

---

## Success Criteria

### MVP Definition:
A functional memory bank system where:
1. Each file has a single, clear purpose with no overlap
2. All files are ready-to-use templates (no placeholder content)
3. The system can be initialized for new tutoring contexts
4. `system-prompt.md` and `memory-bank-prompt.md` have distinct, complementary roles
5. The workflow supports practical Socratic tutoring scenarios
6. Files maintain coherent cross-references and relationships

### Quality Gates:
- [ ] **Completeness**: All 6 memory bank files are functional boilerplates
- [ ] **Consistency**: Uniform formatting, terminology, and structure
- [ ] **Clarity**: Each file's purpose is immediately obvious
- [ ] **Usability**: System can be set up and used without additional documentation
- [ ] **Maintainability**: Clear update workflows for each file type
- [ ] **Scalability**: System works for multiple students and extended use

---

## File Specifications

### Core Architecture Files:
1. **`system-prompt.md`**: Agent identity, Socratic principles, general behavior
2. **`memory-bank-prompt.md`**: Memory system workflow, file relationships, usage instructions

### Memory Bank Files:
1. **`active-session.md`**: Real-time session state and immediate context
2. **`student-profile.md`**: Long-term student characteristics and learning preferences
3. **`progress.md`**: Learning journey tracking and concept mastery
4. **`tutoring-insights.md`**: Accumulated tutoring wisdom and effective patterns
5. **`knowledgebase.md`**: Programming concepts with Socratic question templates
6. **`common-student-issues.md`**: Error patterns with diagnostic approaches

### Utility Files:
1. **`init-memory-bank.md`**: Setup instructions and initialization process

---

## Implementation Priority:
1. **High Priority**: Tasks 2, 3, 5 (remove redundancy, create boilerplates, establish coherence)
2. **Medium Priority**: Tasks 4, 7 (initialization routine, eliminate overlap)
3. **Low Priority**: Task 6 (system coherence validation)

**Estimated Completion**: 4-6 hours of focused work

---

## Notes for Implementation:
- Maintain backward compatibility where possible
- Focus on practical usability over theoretical perfection
- Test the system with realistic tutoring scenarios
- Keep the student's learning experience as the primary focus
- Ensure the agent can actually follow the prescribed workflows
