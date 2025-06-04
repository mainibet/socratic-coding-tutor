<!-- Memory Bank File: Programming Concepts Knowledge Base -->
<!-- Purpose: Repository of programming concepts with Socratic questioning strategies -->
<!-- Update Frequency: When new concepts are needed or question strategies are refined -->
<!-- Cross-references: Links to common-student-issues.md and progress.md -->

# Programming Concepts Knowledge Base

## How to Use This File:
- Add new concepts as needed during tutoring
- Reference concept-specific questions during sessions
- Use analogies to help explain abstract concepts
- Keep code snippets simple and illustrative

---

## Template for Adding New Concepts:

### Concept: [Concept Name]

**Core Explanation (For Tutor's Understanding):**
- [Concise definition of the concept]
- [Key properties and behaviors]
- [When and why this concept is used]

**Helpful Analogies:**
- [Real-world analogy that helps explain the concept]
- [Alternative analogy for different learning styles]

**Key Socratic Questions for This Concept:**
- "What problem does [concept] typically solve?"
- "What are the essential parts of a [concept]?"
- "How does [concept] differ from [related_concept]?"
- "Can you think of a situation where using [concept] would be beneficial/detrimental?"
- "What happens if we remove/change [specific part] of this [concept]?"

**Common Student Misconceptions:**
- [Typical misunderstanding students have]
- [Another common confusion point]

**Diagnostic Questions for Misconceptions:**
- "What do you think [specific part] does here?"
- "How would you explain [concept] to someone who's never seen it before?"

**Simple Illustrative Code Snippets (For Tutor Reference Only):**
```[language]
// Basic example showing the concept
[simple code example]
```

```[language]
// Common mistake or edge case
[example of common error]
```

**Prerequisites:** [What concepts student should understand first]
**Leads to:** [What concepts this enables understanding of next]

---

## Example Concept Entry:

### Concept: Variables

**Core Explanation (For Tutor's Understanding):**
- Named storage locations that hold values
- Values can be changed (mutable) or fixed (immutable)
- Have scope (where they can be accessed) and lifetime

**Helpful Analogies:**
- Labeled boxes where you can store and retrieve items
- Name tags that point to specific values in memory

**Key Socratic Questions for This Concept:**
- "What problem do variables solve in programming?"
- "What happens when you try to use a variable before giving it a value?"
- "How is creating a variable different from using a variable?"
- "Why might you want to change a variable's value?"

**Common Student Misconceptions:**
- Thinking the variable "is" the value rather than "holds" the value
- Confusion about when variables are created vs when they're used

**Diagnostic Questions for Misconceptions:**
- "What do you think happens in memory when you create a variable?"
- "If I change this variable here, what happens to other places that use it?"

**Simple Illustrative Code Snippets (For Tutor Reference Only):**
```python
# Basic variable usage
name = "Alice"
age = 25
```

```python
# Common mistake - using before defining
print(greeting)  # NameError
greeting = "Hello"
```

**Prerequisites:** Basic understanding of data types
**Leads to:** Functions, scope, data structures

---

*Add new concepts below following the template structure above.*

**Cross-References:**
- **← tutoring-insights.md**: Sources proven questioning strategies and successful analogies
- **→ common-student-issues.md**: Links concept misconceptions to diagnostic approaches
- **← progress.md**: Reference student's current concept mastery level when selecting questions
- **→ active-session.md**: Provides concept-specific Socratic questions for current tutoring focus
