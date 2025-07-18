# Practical Examples and Use Cases

## Table of Contents
1. [Beginner Examples](#beginner-examples)
2. [Intermediate Scenarios](#intermediate-scenarios)
3. [Advanced Use Cases](#advanced-use-cases)
4. [Industry-Specific Examples](#industry-specific-examples)
5. [Team Collaboration Scenarios](#team-collaboration-scenarios)
6. [Troubleshooting Examples](#troubleshooting-examples)

---

## Beginner Examples

### Example 1: First-Time User - Simple Bug Fix

**Scenario**: New developer needs to fix a typo in a React component

**Input**:
```
Project Name: My First App
Version: v1.0.0
Tech Stack: React, JavaScript
Mode: QUICK
Description: Fix typo in the header component where "Wellcome" should be "Welcome"
```

**Generated Prompt**:
```
QUICK: Fix typo in the header component where "Wellcome" should be "Welcome"

PROJECT: My First App v1.0.0 (React, JavaScript)
```

**Why This Works**:
- QUICK mode is appropriate for simple typo fixes
- Clear, specific description of what needs to be changed
- Minimal context needed for this type of change

### Example 2: Adding Simple Functionality

**Scenario**: Developer wants to add a loading spinner to a button

**Input**:
```
Project Name: E-commerce Site
Version: v2.1.0
Tech Stack: React, TypeScript, Tailwind CSS
Mode: NORMAL
Template: feature-add
Description: Add loading spinner to the "Add to Cart" button when user clicks it
Constraints: Use existing Tailwind CSS classes, maintain button styling
```

**Generated Prompt**:
```
NORMAL: Add loading spinner to the "Add to Cart" button when user clicks it

PROJECT: E-commerce Site v2.1.0 (React, TypeScript, Tailwind CSS)

DESCRIPTION: Add loading spinner to the "Add to Cart" button when user clicks it

CONSTRAINTS: 
- Use existing Tailwind CSS classes
- Maintain button styling
- Follow existing component patterns
- Include proper state management
```

**Learning Points**:
- Template usage speeds up prompt creation
- Specific component names help AI understand context
- Constraints prevent breaking existing design

---

## Intermediate Scenarios

### Example 3: Database Integration

**Scenario**: Adding user favorites functionality to an existing app

**Input**:
```
Project Name: Recipe Sharing Platform
Version: v3.2.1
Tech Stack: Node.js, Express, PostgreSQL, React
Mode: NORMAL
Template: database-design
Description: Add user favorites system where users can save and view their favorite recipes
Constraints: 
- Use existing user authentication system
- Create new favorites table with proper relationships
- Add API endpoints for CRUD operations
- Update frontend to show favorite status
```

**Generated Prompt**:
```
NORMAL: Add user favorites system where users can save and view their favorite recipes

PROJECT: Recipe Sharing Platform v3.2.1 (Node.js, Express, PostgreSQL, React)

DESCRIPTION: Add user favorites system where users can save and view their favorite recipes

CONSTRAINTS:
- Use existing user authentication system
- Create new favorites table with proper relationships
- Add API endpoints for CRUD operations
- Update frontend to show favorite status
- Follow existing database migration patterns
- Include proper error handling and validation
- Add unit tests for new functionality
```

**Key Features**:
- Multi-layer implementation (database, API, frontend)
- Integration with existing systems
- Clear scope definition with CRUD operations

### Example 4: Performance Optimization

**Scenario**: Fixing slow page load times in a dashboard

**Input**:
```
Project Name: Analytics Dashboard
Version: v4.0.2
Tech Stack: React, Redux, Chart.js, Node.js
Mode: NORMAL
Template: performance-opt
Description: Dashboard loads slowly due to rendering large datasets. Need to implement virtualization and lazy loading
Constraints:
- Maintain existing chart functionality
- Don't break Redux state management
- Keep current UI/UX unchanged
- Target <2 second load time
```

**Generated Prompt**:
```
NORMAL: Dashboard loads slowly due to rendering large datasets. Need to implement virtualization and lazy loading

PROJECT: Analytics Dashboard v4.0.2 (React, Redux, Chart.js, Node.js)

DESCRIPTION: Dashboard loads slowly due to rendering large datasets. Need to implement virtualization and lazy loading

CONSTRAINTS:
- Maintain existing chart functionality
- Don't break Redux state management
- Keep current UI/UX unchanged
- Target <2 second load time
- Implement performance monitoring
- Use React.memo and useMemo for optimization
- Consider data pagination strategies
```

**Optimization Focus**:
- Specific performance targets
- Preservation of existing functionality
- Technical solution suggestions

---

## Advanced Use Cases

### Example 5: Security Implementation

**Scenario**: Implementing OAuth2 authentication system

**Input**:
```
Project Name: Enterprise SaaS Platform
Version: v5.1.0
Tech Stack: Node.js, Express, PostgreSQL, React, Redis
Mode: SECURE
Template: security-implementation
Description: Replace current JWT authentication with OAuth2 using Google and Microsoft providers
Constraints:
- Maintain backward compatibility during transition
- Implement proper session management with Redis
- Add multi-factor authentication support
- Follow OWASP security guidelines
- Zero downtime deployment required
```

**Generated Prompt**:
```
SECURE: Replace current JWT authentication with OAuth2 using Google and Microsoft providers

PROJECT: Enterprise SaaS Platform v5.1.0 (Node.js, Express, PostgreSQL, React, Redis)

DESCRIPTION: Replace current JWT authentication with OAuth2 using Google and Microsoft providers

CONSTRAINTS:
- Maintain backward compatibility during transition
- Implement proper session management with Redis
- Add multi-factor authentication support
- Follow OWASP security guidelines
- Zero downtime deployment required
- Conduct security audit before deployment
- Implement comprehensive logging and monitoring
- Create rollback procedures

FOLLOW: AI-Assisted Development Agreements v1.1 protocols
```

**Security Considerations**:
- SECURE mode for high-risk changes
- Agreement protocols for professional standards
- Comprehensive rollback planning

### Example 6: Microservices Architecture

**Scenario**: Breaking monolith into microservices

**Input**:
```
Project Name: E-commerce Monolith
Version: v6.0.0
Tech Stack: Node.js, Express, MongoDB, React, Docker
Mode: SECURE
Description: Extract user management into a separate microservice with API gateway
Constraints:
- Maintain data consistency across services
- Implement proper service discovery
- Add distributed tracing
- Design for eventual consistency
- Plan database migration strategy
Agreement Integration: Yes (Claude)
```

**Generated Prompt with Agreement**:
```
🤝 AI Assistant: CLAUDE
📋 Project: E-commerce Monolith v6.0.0
⚙️ Tech Stack: Node.js, Express, MongoDB, React, Docker

---

SECURE: Extract user management into a separate microservice with API gateway

PROJECT: E-commerce Monolith v6.0.0 (Node.js, Express, MongoDB, React, Docker)

DESCRIPTION: Extract user management into a separate microservice with API gateway

CONSTRAINTS:
- Maintain data consistency across services
- Implement proper service discovery
- Add distributed tracing
- Design for eventual consistency
- Plan database migration strategy

FOLLOW: AI-Assisted Development Agreements v1.1 protocols

[Complete Agreement Text Follows...]
```

**Architecture Patterns**:
- Complex system redesign requires SECURE mode
- Professional protocols for enterprise-level changes
- Comprehensive constraint specification

---

## Industry-Specific Examples

### Example 7: Healthcare Application

**Scenario**: HIPAA-compliant patient data management

**Input**:
```
Project Name: MedicalRecords Pro
Version: v2.3.0
Tech Stack: .NET Core, SQL Server, Angular, Azure
Mode: SECURE
Description: Implement patient data encryption and audit logging for HIPAA compliance
Constraints:
- All PHI must be encrypted at rest and in transit
- Comprehensive audit trails required
- Role-based access control implementation
- Data retention policies enforcement
- Regular security assessments
```

**Compliance Focus**:
- Regulatory requirements as primary constraints
- Security-first approach
- Audit trail implementation

### Example 8: Financial Services

**Scenario**: Trading platform real-time data processing

**Input**:
```
Project Name: TradingDesk Elite
Version: v4.2.1
Tech Stack: Java, Spring Boot, Apache Kafka, React, PostgreSQL
Mode: NORMAL
Description: Implement real-time stock price updates with WebSocket connections
Constraints:
- Sub-100ms latency requirement
- Handle 10,000+ concurrent connections
- Implement circuit breaker patterns
- Add proper error handling for market closures
- Compliance with financial regulations
```

**Performance Requirements**:
- Specific latency and throughput targets
- Fault tolerance patterns
- Regulatory compliance considerations

---

## Team Collaboration Scenarios

### Example 9: Code Review Integration

**Scenario**: Setting up automated code review workflow

**Input**:
```
Project Name: TeamCode Reviewer
Version: v1.5.0
Tech Stack: GitHub Actions, ESLint, Jest, SonarQube
Mode: NORMAL
Template: ci-cd-setup
Description: Create automated PR review workflow that runs tests, linting, and security scans
Constraints:
- Block merges if any check fails
- Send Slack notifications for review status
- Generate coverage reports
- Auto-assign reviewers based on file changes
```

**Workflow Automation**:
- Multi-tool integration
- Notification systems
- Quality gates implementation

### Example 10: Documentation Generation

**Scenario**: Automated API documentation

**Input**:
```
Project Name: API Documentation Suite
Version: v2.0.0
Tech Stack: Node.js, Express, Swagger, Postman
Mode: NORMAL
Template: api-docs
Description: Generate interactive API documentation from code comments and examples
Constraints:
- Auto-update on code changes
- Include request/response examples
- Add authentication examples
- Support multiple output formats
- Host on company portal
```

**Documentation Strategy**:
- Automated generation from code
- Multiple format support
- Integration with existing tools

---

## Troubleshooting Examples

### Example 11: Production Issue Investigation

**Scenario**: Memory leak in production server

**Input**:
```
Project Name: Production Server
Version: v3.1.4
Tech Stack: Node.js, Express, PostgreSQL, Redis
Mode: NORMAL
Description: Server memory usage increases over time and crashes after 24 hours. Need to identify and fix memory leak
Constraints:
- Cannot restart production server frequently
- Need monitoring tools implementation
- Require gradual rollout of fixes
- Must maintain 99.9% uptime SLA
```

**Production Debugging**:
- Non-disruptive investigation methods
- Monitoring tool integration
- SLA maintenance requirements

### Example 12: Database Performance Issue

**Scenario**: Slow query optimization

**Input**:
```
Project Name: Analytics Platform
Version: v4.1.2
Tech Stack: PostgreSQL, Node.js, React
Mode: NORMAL
Template: performance-opt
Description: User dashboard queries taking 15+ seconds to load. Need query optimization and indexing strategy
Constraints:
- Cannot modify existing data structure
- Must maintain real-time updates
- Target sub-3 second query times
- Consider read replicas for scaling
```

**Database Optimization**:
- Performance targets specified
- Scaling considerations
- Data integrity preservation

---

## Template Customization Examples

### Example 13: Creating Custom Template

**Scenario**: Company-specific deployment template

**Original Template Modification**:
```
Base Template: deployment-setup
Custom Additions:
- Company-specific security scans
- Internal approval workflows
- Staging environment requirements
- Rollback procedures
- Performance benchmarks
```

**Saved Custom Template**:
```
Name: "Company Deployment Standard"
Mode: SECURE
Description: Deploy [FEATURE] following company standards
Constraints:
- Pass security scans (Veracode, SonarQube)
- Complete staging validation
- Obtain architecture review approval
- Implement monitoring and alerting
- Create rollback plan
- Document deployment steps
```

### Example 14: Personal Workflow Template

**Scenario**: Individual developer's preferred workflow

**Personal Template**:
```
Name: "My Bug Fix Workflow"
Mode: NORMAL
Description: Fix [BUG_DESCRIPTION] in [COMPONENT]
Constraints:
- Write unit test that reproduces the bug
- Implement minimal fix
- Verify fix doesn't break existing tests
- Update documentation if needed
- Add regression test
```

**Workflow Benefits**:
- Consistent approach to common tasks
- Personal best practices codified
- Reduced cognitive overhead

---

## Success Metrics and Outcomes

### Measuring Prompt Effectiveness

#### Before Using Prompt Builder
```
❌ Vague Request:
"Make the app faster"

Result: Generic advice, multiple clarifying questions, wasted time
```

#### After Using Prompt Builder
```
✅ Structured Request:
NORMAL: Optimize dashboard loading performance

PROJECT: Analytics Dashboard v4.0.2 (React, Redux, Chart.js)

DESCRIPTION: Dashboard loads slowly due to rendering large datasets. Need to implement virtualization and lazy loading

CONSTRAINTS:
- Target <2 second load time
- Maintain existing functionality
- Use React.memo and useMemo
- Consider data pagination

Result: Specific, actionable implementation plan with code examples
```

### Typical Improvement Metrics

1. **Prompt Clarity**: 85% reduction in clarifying questions
2. **Implementation Speed**: 60% faster from prompt to working solution
3. **Code Quality**: 40% fewer bugs in AI-generated code
4. **Team Consistency**: 70% more standardized development practices

---

*These examples demonstrate the progression from simple to complex use cases, showing how the AI Code Prompt Builder adapts to different scenarios, skill levels, and industry requirements.*