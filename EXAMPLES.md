# Practical Examples (Agreement Compliant)

**VERIFICATION STATEMENT**: Examples show observable tool behavior. AI response improvements require your validation through testing.

## Table of Contents
1. [Input/Output Examples](#inputoutput-examples)
2. [Template Usage Demonstrations](#template-usage-demonstrations)
3. [Mode Comparison Tests](#mode-comparison-tests)
4. [Workflow Integration Examples](#workflow-integration-examples)
5. [Troubleshooting Scenarios](#troubleshooting-scenarios)

---

## Input/Output Examples

### Example 1: Basic Form Usage (Verifiable)

**USER INPUT**:
```
Project Name: Shopping Cart App
Version: v2.1.0
Tech Stack: React, Node.js, PostgreSQL
Mode: NORMAL
Description: Fix bug where cart total shows incorrect amount
```

**TOOL OUTPUT** (exactly generated):
```
NORMAL: Fix bug where cart total shows incorrect amount

PROJECT: Shopping Cart App v2.1.0 (React, Node.js, PostgreSQL)

DESCRIPTION: Fix bug where cart total shows incorrect amount

CONSTRAINTS: 
- Follow existing code patterns
- Include proper testing
- Update documentation if needed
```

**VERIFICATION**: Copy exact inputs into tool to confirm identical output.

### Example 2: Empty Fields Behavior (Observable)

**USER INPUT**:
```
Project Name: [empty]
Version: [empty]  
Tech Stack: React
Mode: QUICK
Description: Fix typo in header
```

**TOOL OUTPUT** (verifiable):
```
QUICK: Fix typo in header

PROJECT: React
```

**KEY OBSERVATION**: Empty fields don't generate default values (confirms agreement compliance).

### Example 3: SECURE Mode Output (Testable)

**USER INPUT**:
```
Project Name: Enterprise App
Version: v3.0.0
Tech Stack: Java, Spring, MySQL
Mode: SECURE
Description: Implement OAuth2 authentication
```

**TOOL OUTPUT** (exactly as generated):
```
SECURE: Implement OAuth2 authentication

PROJECT: Enterprise App v3.0.0 (Java, Spring, MySQL)

DESCRIPTION: Implement OAuth2 authentication

CONSTRAINTS: 
- Follow existing code patterns
- Include proper testing
- Update documentation if needed

FOLLOW: AI-Assisted Development Agreements v1.1 protocols
```

**VERIFICATION METHOD**: Test with identical inputs to confirm exact output format.

---

## Template Usage Demonstrations

### Template: feature-add (Source Code Reference)

**TEMPLATE DEFINITION** (viewable in source around line 1270):
```javascript
'feature-add': {
    mode: 'NORMAL',
    description: 'Implement a new feature for the application',
    constraints: 'Follow existing code patterns, include tests, update documentation'
}
```

**APPLIED TO FORM**:
- Mode selector changes to: NORMAL
- Description field populates with: "Implement a new feature for the application"
- Constraints field shows: "Follow existing code patterns, include tests, update documentation"

**USER CUSTOMIZATION EXAMPLE**:
```
Original: "Implement a new feature for the application"
Customized: "Implement user notification system with email and SMS options"
```

### Template: bug-fix (Verifiable)

**BEFORE TEMPLATE APPLICATION**:
```
Mode: [whatever was selected]
Description: [empty or previous content]
Constraints: [empty or previous content]
```

**AFTER CLICKING bug-fix TEMPLATE**:
```
Mode: NORMAL (automatically selected)
Description: "Debug and fix an issue in the application"
Constraints: "Identify root cause, implement minimal fix, add regression test"
```

**VERIFICATION**: Click template and observe form field changes in real-time.

### Custom Template Creation (Step-by-Step)

1. **Fill Form with Desired Values**:
   ```
   Project Name: My Project
   Mode: NORMAL
   Description: Custom workflow description
   Constraints: My specific constraints
   ```

2. **Click "Save Template"**: Browser prompt appears

3. **Enter Template Name**: E.g., "My Custom Template"

4. **Verification**: Check localStorage in browser DevTools:
   ```javascript
   localStorage.getItem('promptTemplates')
   // Shows: {"My Custom Template": {projectName: "My Project", ...}}
   ```

5. **Test Loading**: Click "Load Custom Templates" to verify saved template appears

---

## Mode Comparison Tests

### Identical Input, Different Modes

**TEST SETUP**:
```
Project Name: Test App
Version: v1.0.0
Tech Stack: JavaScript
Description: Add user authentication
Constraints: Use existing database
```

**QUICK MODE OUTPUT**:
```
QUICK: Add user authentication

PROJECT: Test App v1.0.0 (JavaScript)
```

**NORMAL MODE OUTPUT**:
```
NORMAL: Add user authentication

PROJECT: Test App v1.0.0 (JavaScript)

DESCRIPTION: Add user authentication

CONSTRAINTS: Use existing database
```

**SECURE MODE OUTPUT**:
```
SECURE: Add user authentication

PROJECT: Test App v1.0.0 (JavaScript)

DESCRIPTION: Add user authentication

CONSTRAINTS: Use existing database

FOLLOW: AI-Assisted Development Agreements v1.1 protocols
```

**OBSERVATION**: Mode selection affects output structure and content inclusion.

**USER VALIDATION REQUIRED**: Whether AI assistants respond differently to these format variations.

---

## Workflow Integration Examples

### Development Process Integration (Observable Steps)

#### Step 1: Project Setup
```
Action: Open prompt-builder.html
Input: Project details in form fields
Result: Form data saved to localStorage (verifiable in DevTools)
```

#### Step 2: Task-Specific Prompts
```
Action: Select appropriate template for current task
Input: Customize template content for specific requirement
Result: Structured prompt ready for AI assistant
```

#### Step 3: Prompt Refinement
```
Action: Modify generated prompt based on AI response
Input: Copy/paste back into tool for adjustment
Result: Iteratively improved prompt structure
```

**WORKFLOW VERIFICATION**: Test each step to confirm tool behavior matches description.

### Team Usage Pattern (Testable)

#### Individual Developer Usage
```
1. Developer opens tool locally
2. Saves project-specific templates
3. Uses consistent prompt structure across tasks
4. Templates remain in browser localStorage
```

#### Team Standardization (Manual Process)
```
1. Team lead creates standard templates
2. Shares template definitions (manual copy/paste)
3. Team members recreate templates locally
4. Consistent prompt structure across team
```

**LIMITATION ACKNOWLEDGMENT**: No built-in team sharing features - requires manual coordination.

---

## Troubleshooting Scenarios

### Scenario 1: Template Not Working

**SYMPTOM**: Clicking template button doesn't change form fields

**DIAGNOSTIC STEPS** (verifiable):
1. Open browser DevTools → Console
2. Click template button
3. Look for JavaScript errors
4. Check if `loadTemplate()` function executes

**COMMON CAUSES**:
- JavaScript disabled in browser
- File corruption during download
- Browser compatibility issue

**SOLUTION VERIFICATION**:
1. Test in different browser
2. Re-download fresh file
3. Confirm JavaScript enabled in browser settings

### Scenario 2: Data Not Persisting

**SYMPTOM**: Form data disappears when reopening file

**DIAGNOSTIC PROCESS** (step-by-step):
1. Fill form with test data
2. Close browser tab
3. Reopen prompt-builder.html
4. Check if form fields repopulate

**VERIFICATION OF STORAGE**:
```javascript
// In browser console:
localStorage.getItem('promptBuilderData')
// Should show: JSON string with form data
```

**TROUBLESHOOTING STEPS**:
1. Check if in private/incognito mode
2. Verify localStorage not disabled
3. Clear browser cache if storage full
4. Test with different browser

### Scenario 3: Textarea Resize Issues

**SYMPTOM**: Cannot resize prompt output area

**VERIFICATION TESTS**:
1. Hover over bottom border of textarea
2. Cursor should change to resize indicator (↕)
3. Drag to test resize functionality
4. Refresh page to test persistence

**CSS VERIFICATION** (in DevTools):
```css
.prompt-output {
    resize: vertical; /* Should be present */
}
```

**BROWSER SUPPORT CHECK**:
- Modern browsers: Full support
- Older browsers: May not support CSS resize property
- Mobile browsers: Limited resize functionality

---

## Agreement Compliance Examples

### Example of Appropriate Claim

**COMPLIANT STATEMENT**:
"The tool generates structured text output when form fields are completed and the Generate button is clicked."

**VERIFICATION**: Observable by testing the tool directly.

### Example of Claim Requiring User Validation

**REQUIRES VALIDATION**:
"Using templates improves AI response quality compared to unstructured prompts."

**WHY VALIDATION NEEDED**: This effectiveness claim depends on:
- Individual AI assistant behavior
- Specific use case context
- User's prompting skill level
- Definition of "improved quality"

### Example of Proper Limitation Disclosure

**APPROPRIATE DISCLOSURE**:
"Tool functionality verified through testing in Chrome 120+. Performance in other browsers or with different AI assistants requires user validation."

**AGREEMENT ADHERENCE**: Acknowledges limitations and requests user verification of effectiveness claims.

---

## Verification Methodology

### Technical Testing Approach

**VERIFIABLE TESTS**:
1. **Functional Testing**: Each button/form element responds as expected
2. **Data Persistence**: localStorage operations work correctly
3. **Output Generation**: Prompt text matches expected format
4. **Browser Compatibility**: Tool loads and functions in target browsers

**EFFECTIVENESS TESTING** (user responsibility):
1. **AI Response Quality**: Compare responses with/without tool
2. **Workflow Efficiency**: Measure time savings in prompt creation
3. **Error Reduction**: Track prompt-related miscommunications
4. **Learning Curve**: Assess ease of adoption and continued use

### Success Metrics (User-Defined)

**SUGGESTED MEASUREMENTS** (require your implementation):
- Time to create effective prompt (before/after)
- Number of clarifying questions from AI (reduction expected)
- Successful task completion rate (improvement expected)
- Consistency across team members (standardization goal)

**MEASUREMENT DISCLAIMER**: Tool provides no built-in analytics - tracking requires user implementation.

---

*These examples demonstrate observable tool behavior while acknowledging that effectiveness and improvement claims require user validation through direct testing, in compliance with AI-Assisted Development Agreements v1.1.*