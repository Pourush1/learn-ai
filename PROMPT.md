# Prompt Templates

This document contains helpful prompt templates for working with AI and improving productivity.

## Resources

- [Helpful Prompts](https://prompts.chat/) - A comprehensive collection of prompt templates for various use cases


# [Below are the prompt from this article](https://substack.com/home/post/p-164288010)
# AI Coding Assistant Prompt Templates

## 🔧 Debugging Templates

### Basic Bug Fixing Template
```
I have a [LANGUAGE] function that should [EXPECTED_BEHAVIOR], but it's [ACTUAL_BEHAVIOR]. 

**Code:**
```[language]
[YOUR_CODE_HERE]
```

**Error Message:** [EXACT_ERROR_MESSAGE]
**Expected Output:** [EXPECTED_RESULT] 
**Actual Output:** [ACTUAL_RESULT]
**Input Used:** [SAMPLE_INPUT]

What could be causing this bug and how can I fix it?
```

### Step-by-Step Debugging Template
```
Walk through this [LANGUAGE] function line by line and track the value of [VARIABLE_NAME] at each step. It's not [EXPECTED_BEHAVIOR] - where does the logic go wrong?

```[language]
[YOUR_CODE_HERE]
```

Expected behavior: [DESCRIPTION]
Current issue: [PROBLEM_DESCRIPTION]
```

### React Hook Dependencies Template
```
I have a React component that [DESCRIPTION_OF_ISSUE]. Here's my code:

```jsx
[COMPONENT_CODE]
```

**Expected behavior:** [WHAT_SHOULD_HAPPEN]
**Actual behavior:** [WHAT_IS_HAPPENING] 
**Error in console:** [ERROR_MESSAGE]

What's causing this [infinite loop/dependency issue/etc] and how do I fix the dependency array?
```

### Minimal Reproducible Example Template
```
Here's a minimal example that reproduces the [ERROR_TYPE]:

```[language]
[MINIMAL_CODE_SNIPPET]
```

This triggers: [ERROR_MESSAGE]
Expected: [EXPECTED_RESULT]
Why does this error occur and how can I fix it?
```

## 🔄 Refactoring Templates

### Goal-Oriented Refactoring Template
```
Refactor the following [LANGUAGE] [function/component/class] to [SPECIFIC_GOALS]. 

**Specific requirements:**
1. [REQUIREMENT_1] (e.g., eliminate duplicate code)
2. [REQUIREMENT_2] (e.g., improve performance) 
3. [REQUIREMENT_3] (e.g., maintain error handling)
4. [REQUIREMENT_4] (e.g., use modern syntax)

```[language]
[CODE_TO_REFACTOR]
```

Please provide the refactored code with comments explaining the changes.
```

### Performance Optimization Template
```
Optimize this [LANGUAGE] [function/algorithm] for [PERFORMANCE_METRIC]. 

**Current issues:**
- [PERFORMANCE_ISSUE_1]
- [PERFORMANCE_ISSUE_2]

**Constraints:**
- [CONSTRAINT_1] (e.g., must handle 10k+ items)
- [CONSTRAINT_2] (e.g., memory usage should be minimal)

```[language]
[CODE_TO_OPTIMIZE]
```

How can I improve the [runtime/memory/etc] performance?
```

### Code Review Style Template
```
Act as a senior [TECHNOLOGY] developer and review this code for potential issues:

```[language]
[CODE_TO_REVIEW]
```

Focus on:
- [FOCUS_AREA_1] (e.g., potential bugs)
- [FOCUS_AREA_2] (e.g., security issues)
- [FOCUS_AREA_3] (e.g., best practices)
- [FOCUS_AREA_4] (e.g., performance)

Provide specific recommendations for improvement.
```

## 🏗️ Feature Implementation Templates

### New Feature Planning Template
```
I want to add a [FEATURE_DESCRIPTION] to my [TECHNOLOGY_STACK] application.

**Requirements:**
- [REQUIREMENT_1]
- [REQUIREMENT_2]
- [REQUIREMENT_3]

**Technical Context:**
- Framework: [FRAMEWORK_VERSION]
- Current architecture: [ARCHITECTURE_PATTERN]
- Existing similar features: [REFERENCE_FEATURES]

Please outline a step-by-step implementation plan, then we'll tackle each step.
```

### Component Creation Template
```
Create a [FRAMEWORK] [component/module] called [NAME] that [FUNCTIONALITY].

**Specifications:**
- Props/Parameters: [INPUT_DESCRIPTION]
- Expected output: [OUTPUT_DESCRIPTION]
- Example usage: [USAGE_EXAMPLE]
- Style requirements: [STYLING_CONSTRAINTS]

**Technical requirements:**
- [TECH_REQ_1] (e.g., TypeScript with strict mode)
- [TECH_REQ_2] (e.g., responsive design)
- [TECH_REQ_3] (e.g., accessibility compliant)

Here's how similar components are structured in our project:
```[language]
[REFERENCE_CODE]
```
```

### API Endpoint Template
```
Implement a [HTTP_METHOD] endpoint `/[ROUTE]` in [FRAMEWORK] that [FUNCTIONALITY].

**Requirements:**
- Input: [REQUEST_FORMAT]
- Output: [RESPONSE_FORMAT]
- Validation: [VALIDATION_RULES]
- Error handling: [ERROR_SCENARIOS]

**Example:**
Request: [SAMPLE_REQUEST]
Response: [SAMPLE_RESPONSE]

Follow our existing patterns shown in this similar endpoint:
```[language]
[REFERENCE_ENDPOINT]
```
```

## 🏛️ Architecture Templates

### State Management Architecture Template
```
I'm building a [PROJECT_TYPE] using [TECH_STACK] and need to design the state management architecture.

**Requirements:**
- [COMPONENT_1] needs: [STATE_NEEDS_1]
- [COMPONENT_2] needs: [STATE_NEEDS_2]
- [COMPONENT_3] needs: [STATE_NEEDS_3]

**Technical constraints:**
- [CONSTRAINT_1]
- [CONSTRAINT_2]
- [CONSTRAINT_3]

**Questions:**
Should I use [OPTION_1] vs [OPTION_2] vs [OPTION_3]?

Please provide a recommended architecture with code examples showing how to structure stores and integrate with [SPECIFIC_FRAMEWORK_PATTERNS].
```

### System Design Template
```
Design the architecture for a [SYSTEM_TYPE] that needs to:

**Core Features:**
- [FEATURE_1]
- [FEATURE_2] 
- [FEATURE_3]

**Non-functional Requirements:**
- Scale: [SCALE_REQUIREMENTS]
- Performance: [PERFORMANCE_REQUIREMENTS]
- Reliability: [RELIABILITY_REQUIREMENTS]

**Constraints:**
- Technology: [TECH_CONSTRAINTS]
- Budget: [BUDGET_CONSTRAINTS]
- Timeline: [TIME_CONSTRAINTS]

Please suggest an architecture with:
1. High-level system design
2. Technology stack recommendations
3. Database design considerations
4. Potential bottlenecks and solutions
```

## 🎯 Role-Based Prompt Templates

### Expert Consultant Template
```
Act as a [EXPERT_TYPE] with 10+ years of experience. I need help with [PROBLEM_DESCRIPTION].

**Context:** [DETAILED_CONTEXT]
**Current approach:** [CURRENT_SOLUTION]
**Challenges:** [SPECIFIC_CHALLENGES]

As an expert, what would you recommend? Please explain your reasoning and provide alternative approaches if applicable.
```

### Code Mentor Template
```
Act as an experienced [TECHNOLOGY] mentor helping a [SKILL_LEVEL] developer. 

**Student's code:**
```[language]
[CODE_TO_REVIEW]
```

**Student's question:** [SPECIFIC_QUESTION]

Please provide:
1. Feedback on the current approach
2. Suggestions for improvement
3. Explanations of why these changes are better
4. Additional resources or concepts to learn
```

### Security Auditor Template
```
Act as a cybersecurity expert reviewing this [LANGUAGE] code for security vulnerabilities:

```[language]
[CODE_TO_AUDIT]
```

Focus on:
- [SECURITY_CONCERN_1] (e.g., input validation)
- [SECURITY_CONCERN_2] (e.g., authentication)
- [SECURITY_CONCERN_3] (e.g., data exposure)

Please identify potential vulnerabilities and provide secure alternatives.
```

## 📝 Documentation & Learning Templates

### Code Explanation Template
```
Explain this [LANGUAGE] code in detail, as if teaching a [SKILL_LEVEL] developer:

```[language]
[CODE_TO_EXPLAIN]
```

Please cover:
- What the code does overall
- How each part works
- Why certain approaches were chosen
- Any patterns or best practices demonstrated
```

### Test Generation Template
```
Generate comprehensive unit tests for this [LANGUAGE] function:

```[language]
[FUNCTION_TO_TEST]
```

Please include tests for:
- Happy path scenarios
- Edge cases
- Error conditions
- Boundary values

Use [TESTING_FRAMEWORK] and follow [TESTING_PATTERNS].
```

### Documentation Template
```
Create technical documentation for this [CODE_TYPE]:

```[language]
[CODE_TO_DOCUMENT]
```

Include:
- Purpose and overview
- Parameters/inputs and outputs
- Usage examples
- Error handling
- Dependencies
- Performance considerations
```

## ⚡ Quick Reference Templates

### Quick Bug Fix
```
Bug: [BRIEF_DESCRIPTION]
Code: [CODE_SNIPPET]
Error: [ERROR_MESSAGE]
Fix this quickly.
```

### Quick Optimization
```
Make this [LANGUAGE] code faster:
```[language]
[CODE_TO_OPTIMIZE]
```
Focus on [SPECIFIC_BOTTLENECK].
```

### Quick Explanation
```
What does this code do?
```[language]
[CODE_TO_EXPLAIN]
```
Explain in simple terms.
```

## 🚫 Anti-Patterns to Avoid

### ❌ Too Vague
```
"My code doesn't work"
"Fix this function"
"Make this better"
```

### ❌ Too Overloaded
```
"Fix these 5 bugs, add 3 features, refactor for performance, 
add tests, update documentation, and deploy to production"
```

### ❌ Missing Context
```
"Here's my code: [code]"  // No question or goal specified
```

### ❌ No Success Criteria
```
"Optimize this code"  // Optimize for what? Speed? Memory? Readability?
```

## 💡 Pro Tips

1. **Always provide context**: Language, framework, expected vs actual behavior
2. **Be specific about goals**: What does "better" mean in your situation?
3. **Include examples**: Show expected input/output when possible
4. **Use role-playing**: "Act as a senior developer reviewing this code"
5. **Iterate and refine**: Start broad, then get specific in follow-ups
6. **Break down complex tasks**: One feature at a time
7. **Ask for explanations**: Understanding the "why" helps you learn

## 🔗 Template Usage Examples

### Debugging a React Hook
```
I have a React component that's causing infinite re-renders. Here's my code:

```jsx
const UserProfile = ({ userId }) => {
  const [user, setUser] = useState(null);
  const [loading, setLoading] = useState(true);
  
  useEffect(() => {
    fetchUser(userId).then(setUser).finally(() => setLoading(false));
  }, [userId, setUser, setLoading]);
  
  return loading ? <div>Loading...</div> : <div>{user?.name}</div>;
};
```

**Expected behavior:** Should fetch user data once when userId changes
**Actual behavior:** Component re-renders infinitely  
**Error in console:** "Warning: Maximum update depth exceeded"

What's causing this infinite loop and how do I fix the dependency array?
```

### Refactoring for Performance
```
Refactor this JavaScript function to eliminate duplicate code and improve performance.

**Specific requirements:**
1. Avoid repeating the fetch logic for users and orders
2. Fetch both lists in parallel if possible  
3. Keep separate error handling (we want to know which call failed)
4. Improve the combination logic using a more efficient lookup structure

```javascript
async function getCombinedData(apiClient) {
  // Current implementation with duplication...
}
```

Please provide the refactored code with comments explaining the improvements.
```

---

*Use these templates as starting points and customize them for your specific needs. The key is providing rich context and being specific about your goals.*