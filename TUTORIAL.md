# AI Code Prompt Builder - Complete Tutorial

## Table of Contents
1. [Getting Started](#getting-started)
2. [Understanding the Interface](#understanding-the-interface)
3. [Development Modes Explained](#development-modes-explained)
4. [Template System Guide](#template-system-guide)
5. [Agreement Integration Tutorial](#agreement-integration-tutorial)
6. [Advanced Features](#advanced-features)
7. [Best Practices](#best-practices)
8. [Troubleshooting](#troubleshooting)

---

## Getting Started

### What is the AI Code Prompt Builder?

The AI Code Prompt Builder is a professional tool designed to help developers and non-technical professionals create structured, effective prompts for AI-assisted development. It transforms your project requirements into clear, actionable prompts that AI assistants can understand and execute efficiently.

### Why Use This Tool?

- **Consistency**: Creates standardized prompts across all your AI interactions
- **Efficiency**: Reduces time spent crafting prompts from scratch
- **Best Practices**: Incorporates proven prompt engineering techniques
- **Professional Standards**: Includes development agreements and protocols
- **Template Library**: Access to 40+ pre-built templates for common scenarios

### Quick Setup

1. **Download**: Save `prompt-builder.html` to your computer
2. **Open**: Double-click the file or open it in any modern web browser
3. **Start Building**: No installation, no dependencies, works offline

---

## Understanding the Interface

### Main Sections

#### 1. Project Information Panel
```
┌─ Project Details ────────────────────────┐
│ Project Name: [Your Project Name]        │
│ Version: [e.g., v2.1.0]                 │
│ Tech Stack: [e.g., React, Node.js]      │
└──────────────────────────────────────────┘
```

**Purpose**: Provides context to the AI about your specific project
**Best Practice**: Be specific about your tech stack for better AI suggestions

#### 2. Development Mode Selection
```
○ QUICK     ○ NORMAL     ○ SECURE
```

**QUICK Mode**: For simple, safe changes
- Typos and formatting fixes
- Minor documentation updates
- Simple refactoring

**NORMAL Mode**: For standard development work
- Feature implementations
- Bug fixes
- Code reviews
- Performance optimizations

**SECURE Mode**: For complex, risky changes
- Architecture modifications
- Security implementations
- Database schema changes
- Breaking changes

#### 3. Request Description
```
┌─ What do you need help with? ────────────┐
│                                          │
│ [Describe your specific task here]       │
│                                          │
└──────────────────────────────────────────┘
```

**Tips**:
- Be specific about what you want to achieve
- Include relevant file paths or components
- Mention any constraints or requirements

#### 4. Templates and Constraints
```
┌─ Quick Templates ─┐  ┌─ Additional Constraints ─┐
│ [Template List]   │  │ [Custom constraints]      │
└───────────────────┘  └───────────────────────────┘
```

---

## Development Modes Explained

### QUICK Mode - Lightning Fast Changes

**When to Use**:
- Fixing typos in code or comments
- Adjusting formatting or styling
- Adding simple comments or documentation
- Minor variable renaming

**Example Prompt Generated**:
```
QUICK: Fix typo in user authentication function

PROJECT: MyApp v1.2.0 (React, Express.js)
```

**Characteristics**:
- No approval required from AI
- Immediate execution expected
- Low risk of breaking functionality
- Minimal testing needed

### NORMAL Mode - Standard Development

**When to Use**:
- Implementing new features
- Bug fixes and debugging
- Code refactoring and optimization
- Adding tests or documentation

**Example Prompt Generated**:
```
NORMAL: Add user profile editing functionality

PROJECT: MyApp v1.2.0 (React, Express.js)

DESCRIPTION: Create a user profile page where users can update their personal information including name, email, and avatar. Include form validation and API integration.

CONSTRAINTS: 
- Use existing authentication middleware
- Follow current component structure
- Include unit tests
```

**Characteristics**:
- Standard development workflow
- May require discussion and planning
- Moderate complexity and risk
- Testing and review recommended

### SECURE Mode - Critical Changes

**When to Use**:
- Modifying authentication or authorization
- Database schema changes
- Adding new dependencies
- Architecture modifications
- Security-related implementations

**Example Prompt Generated**:
```
SECURE: Implement OAuth2 authentication system

PROJECT: MyApp v1.2.0 (React, Express.js)

DESCRIPTION: Replace current JWT authentication with OAuth2 using Google and GitHub providers. Maintain backward compatibility during transition.

CONSTRAINTS:
- Preserve existing user data
- Implement proper session management
- Follow security best practices
- Require explicit approval for each step

FOLLOW: AI-Assisted Development Agreements v1.1 protocols
```

**Characteristics**:
- Requires explicit approval at each step
- High complexity and risk
- Comprehensive testing required
- Professional review recommended

---

## Template System Guide

### Understanding Templates

Templates are pre-written prompt structures for common development scenarios. They save time and ensure you include all necessary information.

### Template Categories

#### 🚀 Project Lifecycle
```
project-init          → Initialize new project structure
project-setup         → Configure development environment
feature-planning      → Plan new feature implementation
architecture-review   → Review and improve architecture
```

#### 🛠️ Development Tasks
```
feature-add           → Add new functionality
bug-fix              → Debug and fix issues
code-review          → Review code quality
performance-opt      → Optimize performance
refactor             → Refactor existing code
```

#### 🔧 Technical Operations
```
database-design      → Design database schema
api-development      → Create REST/GraphQL APIs
testing-setup        → Set up testing framework
ci-cd-setup         → Configure CI/CD pipeline
```

#### 📚 Documentation
```
readme-update        → Update project README
api-docs            → Generate API documentation
user-guide          → Create user documentation
tech-docs           → Write technical documentation
```

### Using Templates

1. **Select Template**: Click on any template button
2. **Auto-Fill**: Form fields populate automatically
3. **Customize**: Modify the generated content as needed
4. **Generate**: Create your customized prompt

### Example: Feature Development Template

**Template**: `feature-add`

**Auto-Generated Content**:
```
Mode: NORMAL
Description: Implement a new feature for the application
Constraints: Follow existing code patterns, include tests, update documentation
```

**Customization Example**:
```
Mode: NORMAL
Description: Implement user notification system with email and in-app notifications
Constraints: 
- Use existing email service integration
- Include push notification support
- Add notification preferences to user settings
- Include comprehensive unit and integration tests
```

---

## Agreement Integration Tutorial

### What is Agreement Integration?

The Agreement Integration feature includes the complete AI-Assisted Development Agreements v1.1 in your prompts, establishing professional development protocols.

### When to Use Agreement Integration

- **Client Work**: When working on projects for external clients
- **Team Collaboration**: When multiple developers work with AI assistance
- **Professional Standards**: When maintaining high-quality code standards
- **Complex Projects**: When working on critical or large-scale applications

### How to Use Agreement Integration

1. **Click "Inject Agreement"**: Button appears below the generate button
2. **Select AI Environment**: Choose your AI assistant (Claude, ChatGPT, etc.)
3. **Automatic Injection**: Agreement is added to your prompt with specific headers

### Agreement Structure

```
🤝 AI Assistant: CLAUDE
📋 Project: MyApp v1.2.0
⚙️ Tech Stack: React, Node.js, PostgreSQL

---

## FULL AI-ASSISTED DEVELOPMENT AGREEMENTS v1.1
[Complete agreement text follows...]
```

### Benefits of Using Agreements

- **Clear Expectations**: Establishes what the AI should and shouldn't do
- **Quality Assurance**: Ensures consistent development practices
- **Risk Management**: Provides guidelines for handling complex scenarios
- **Professional Workflow**: Creates structured development processes

---

## Advanced Features

### Persistent Settings

The tool automatically saves your preferences:

- **Form Data**: Project details and settings persist between sessions
- **Textarea Height**: Resize the output area and it remembers your preference
- **Template History**: Recently used templates are prioritized

### Vertical Resizing

**How to Resize**:
1. Hover over the bottom edge of the prompt output area
2. Look for the resize cursor (usually ↕)
3. Drag up or down to adjust height
4. Release - your new size is automatically saved

**Performance Optimization**:
- Smooth resizing without lag
- Debounced saving prevents excessive storage writes
- Optimized transitions for better user experience

### Template Management

**Save Custom Templates**:
1. Fill out your form with desired values
2. Click "Save Template"
3. Enter a name for your template
4. Template is saved to local storage

**Load Saved Templates**:
1. Click "Load Custom Templates"
2. Select from your saved templates
3. Form auto-populates with saved values

### Keyboard Shortcuts

- **Ctrl/Cmd + Enter**: Generate prompt
- **Ctrl/Cmd + C**: Copy prompt (when output is selected)
- **Tab**: Navigate between form fields

---

## Best Practices

### Writing Effective Descriptions

#### ✅ Good Examples

**Specific and Actionable**:
```
"Add user authentication to the login page using JWT tokens. Include form validation for email format and password strength. Handle login errors with appropriate user feedback."
```

**Context-Rich**:
```
"Fix the memory leak in the dashboard component that occurs when users navigate between tabs. The issue appears to be related to event listeners not being properly cleaned up."
```

**Clear Constraints**:
```
"Implement dark mode toggle, but maintain compatibility with existing CSS custom properties and don't break the current responsive design."
```

#### ❌ Avoid These

**Too Vague**:
```
"Fix the app" or "Make it better"
```

**Missing Context**:
```
"Add a button" (What should the button do? Where should it go?)
```

**No Constraints**:
```
"Implement user profiles" (No guidance on requirements or limitations)
```

### Choosing the Right Mode

#### QUICK Mode Checklist
- [ ] Change affects only 1-2 lines of code
- [ ] No logic changes required
- [ ] No new dependencies needed
- [ ] Cannot break existing functionality

#### NORMAL Mode Checklist
- [ ] Involves implementing new functionality
- [ ] Requires understanding of existing codebase
- [ ] May need testing and documentation
- [ ] Standard development complexity

#### SECURE Mode Checklist
- [ ] Affects authentication or authorization
- [ ] Modifies database schema or structure
- [ ] Changes core application architecture
- [ ] Involves security-sensitive operations
- [ ] Could break existing functionality if done incorrectly

### Template Selection Strategy

1. **Start Broad**: Begin with a general template category
2. **Narrow Down**: Look for the most specific template that matches your need
3. **Customize**: Always modify the template to fit your exact requirements
4. **Save Patterns**: If you repeatedly customize a template the same way, save a custom version

---

## Troubleshooting

### Common Issues and Solutions

#### Issue: "Prompt output is too small"
**Solution**: 
- Resize the textarea by dragging the bottom edge
- The new size will be automatically saved

#### Issue: "My custom templates aren't saving"
**Causes**:
- Browser in private/incognito mode
- LocalStorage disabled
- Browser storage full

**Solutions**:
- Use normal browsing mode
- Check browser privacy settings
- Clear some browser data to free up storage

#### Issue: "Templates aren't loading correctly"
**Solution**:
- Refresh the page
- Check if JavaScript is enabled
- Try a different browser

#### Issue: "Generated prompts are too generic"
**Solutions**:
- Add more specific project details
- Include file paths and component names
- Use the constraints field for additional requirements
- Choose a more specific template

#### Issue: "AI doesn't follow the prompt structure"
**Solutions**:
- Use SECURE mode for complex requests
- Include the Agreement Integration
- Be more specific about expected outcomes
- Break large requests into smaller, focused prompts

### Browser Compatibility

**Fully Supported**:
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

**Limited Support**:
- Internet Explorer (not recommended)
- Very old mobile browsers

### Performance Tips

1. **Large Projects**: For projects with many files, be specific about which files/components you want to modify
2. **Complex Prompts**: Break large requests into multiple smaller prompts
3. **Template Loading**: If templates load slowly, check your browser's JavaScript performance settings

---

## Frequently Asked Questions

### General Usage

**Q: Can I use this tool offline?**
A: Yes! The tool is a standalone HTML file that works completely offline.

**Q: Is my data sent anywhere?**
A: No. All data stays in your browser's local storage. Nothing is transmitted.

**Q: Can I customize the templates?**
A: Yes. You can modify any template and save custom versions.

### Technical Questions

**Q: What browsers are supported?**
A: All modern browsers. See the compatibility section above.

**Q: How much storage does it use?**
A: Very minimal - only your saved templates and preferences (typically <1MB).

**Q: Can I export my templates?**
A: Currently templates are stored in browser localStorage. Manual backup involves browser developer tools.

### Integration Questions

**Q: Which AI assistants work best with this tool?**
A: The tool is optimized for Claude, ChatGPT, GitHub Copilot, and other major AI coding assistants.

**Q: Should I always use the agreement integration?**
A: Use it for professional projects, client work, or when you need structured development protocols.

**Q: Can teams share templates?**
A: Templates are stored locally. Teams can share the customized prompts or manually recreate templates.

---

## Version History and Updates

### Current Version: 1.0
- Initial release with full feature set
- 40+ built-in templates
- Agreement integration
- Persistent settings and resizing
- Professional UI/UX

### Planned Features
- Template import/export functionality
- Team collaboration features
- Integration with popular IDEs
- Advanced prompt customization options

---

*This tutorial covers all aspects of the AI Code Prompt Builder. For additional support or feature requests, please refer to the project repository.*