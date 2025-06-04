<!-- Memory Bank File: Common Student Issues Catalog -->
<!-- Purpose: Catalog of common errors and Socratic diagnostic approaches -->
<!-- Update Frequency: When new error patterns emerge during tutoring -->
<!-- Cross-references: →knowledgebase.md (concept explanations), →tutoring-insights.md (effective patterns) -->

# Common Student Issues & Socratic Guidance

## How to Use This File:
- Reference when students encounter errors or show confusion
- Use diagnostic questions to help students self-identify issues
- Add new patterns as they emerge during tutoring sessions
- Guide students toward understanding rather than giving direct solutions

---

## Template for Adding New Issues:

### Issue: [Issue Name]
**Symptoms:** [How the problem manifests - error messages, unexpected behavior, etc.]
**Likely Misconceptions:** [What students typically misunderstand that leads to this]
**Socratic Diagnostic Questions:**
- "[Question to help student identify the problem]"
- "[Question to explore their understanding]"
- "[Question to guide toward solution]"
**Guidance Strategies (NOT solutions):**
- [Strategy to help them discover the fix]
- [Alternative approach if first doesn't work]
- [Reference to related concepts in knowledgebase.md]

---

## Common Issues Catalog:

### Issue: Off-by-One Error
**Symptoms:** Loop runs one too many/few times; Array index out of bounds near loop termination.
**Likely Misconceptions:** Confusion about zero-based indexing; Incorrect loop condition (e.g., `<` vs `<=`).
**Socratic Diagnostic Questions:**
- "What range of numbers/items were you expecting the loop to cover?"
- "How many iterations do you expect? How many is it actually doing?"
- "Can you walk through the first (or last) iteration manually with the values?"
- "What does your loop condition mean in plain English?"
**Guidance Strategies (NOT solutions):**
- Suggest printing variable values at each iteration
- Suggest simplifying the problematic code section
- Point towards reviewing knowledgebase.md for related concepts
- Ask them to trace through with specific small examples

### Issue: Function Definition vs Function Call Confusion
**Symptoms:** Student treats function definition as execution; confusion about when code runs.
**Likely Misconceptions:** Not understanding that defining a function doesn't execute it.
**Socratic Diagnostic Questions:**
- "What do you think happens when Python reads this function definition?"
- "When do you think the code inside the function actually runs?"
- "What's the difference between writing a recipe and cooking a meal?"
**Guidance Strategies (NOT solutions):**
- Use the recipe analogy (writing vs cooking)
- Have them trace through code execution step by step
- Ask them to predict what gets printed before running code

### Issue: Variable Scope Confusion
**Symptoms:** UnboundLocalError, unexpected None values, variables not updating as expected.
**Likely Misconceptions:** Not understanding where variables can be accessed; confusion about local vs global.
**Socratic Diagnostic Questions:**
- "Where do you think this variable was created?"
- "From this point in the code, which variables can you access?"
- "What's the 'lifetime' of this variable?"
**Guidance Strategies (NOT solutions):**
- Use box/container analogies for different scopes
- Have them draw variable scope diagrams
- Ask them to trace variable creation and destruction

### Issue: Indentation Errors (Python-specific)
**Symptoms:** IndentationError, unexpected indent, unindent does not match.
**Likely Misconceptions:** Not understanding that indentation defines code structure in Python.
**Socratic Diagnostic Questions:**
- "What do you think the indentation is telling Python about your code structure?"
- "Which lines should be 'inside' the function/loop/if statement?"
- "How does Python know where one block ends and another begins?"
**Guidance Strategies (NOT solutions):**
- Have them identify which lines belong together
- Ask them to explain the code structure in words first
- Suggest using consistent indentation (tabs vs spaces)

### Issue: Infinite Loops
**Symptoms:** Program hangs, doesn't terminate, needs to be force-stopped.
**Likely Misconceptions:** Not ensuring loop condition eventually becomes false.
**Socratic Diagnostic Questions:**
- "What needs to change inside the loop for it to eventually stop?"
- "How does the loop condition change with each iteration?"
- "What would make this condition become false?"
**Guidance Strategies (NOT solutions):**
- Have them trace through several iterations
- Ask them to identify what should change each time
- Suggest adding print statements to see variable changes

---

*Add new common issues below using the template structure above.*

**Cross-References:**
- **→ knowledgebase.md**: Links to related concept definitions and core explanations
- **← tutoring-insights.md**: Sources proven guidance strategies and successful approaches
- **→ active-session.md**: Provides diagnostic questions for current student difficulties
- **← progress.md**: Reference student's learning journey to contextualize current issues
