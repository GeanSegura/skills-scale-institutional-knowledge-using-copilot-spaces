# Acceptance Criteria Template

Use this template to define clear, testable acceptance criteria for backlog items.

---

## Feature/Story Title
[Brief title describing the feature or user story]

---

## User Story (Optional)
**As a** [persona/role]  
**I want** [capability]  
**So that** [benefit/value]

---

## Acceptance Criteria

### Scenario 1: [Description]
**Given** [initial context or preconditions]  
**When** [action or event occurs]  
**Then** [expected outcome or result]

**And** [additional outcome, if applicable]

### Scenario 2: [Description]
**Given** [initial context or preconditions]  
**When** [action or event occurs]  
**Then** [expected outcome or result]

### Scenario 3: [Edge Case or Error Scenario]
**Given** [initial context or preconditions]  
**When** [action or event occurs]  
**Then** [expected outcome or result]

---

## Success Metrics
How will we measure if this feature is successful?

- **Metric 1:** [e.g., User engagement increases by 10%]
- **Metric 2:** [e.g., Error rate decreases to <1%]
- **Metric 3:** [e.g., Feature adoption reaches 50% within 2 weeks]

---

## Test Steps
High-level steps to validate the acceptance criteria:

1. [Test step 1 - Setup/precondition]
2. [Test step 2 - Execute action]
3. [Test step 3 - Verify expected result]
4. [Test step 4 - Test edge cases]
5. [Test step 5 - Validate metrics or analytics]

---

## Definition of Done
Checklist to confirm the feature is ready for release:

- [ ] All acceptance criteria scenarios pass
- [ ] Unit tests written and passing
- [ ] Integration tests written and passing (if applicable)
- [ ] Code reviewed and approved
- [ ] Documentation updated (user-facing and/or technical)
- [ ] Accessibility requirements met (WCAG 2.1 Level AA)
- [ ] Performance benchmarks met
- [ ] Security review completed (if applicable)
- [ ] Design review completed and approved
- [ ] QA sign-off received
- [ ] Deployed to staging and validated
- [ ] Release notes drafted
- [ ] Monitoring and alerting configured (if applicable)

---

## Notes & Dependencies
- [Note any dependencies on other teams, features, or external services]
- [Highlight risks or assumptions]
- [Link to related design docs, specs, or tickets]

---

## Example Usage

### Feature/Story Title
User Login with Email and Password

### User Story
**As a** new user  
**I want** to log in using my email and password  
**So that** I can securely access my account

### Acceptance Criteria

#### Scenario 1: Successful Login
**Given** I am on the login page  
**When** I enter a valid email and password  
**Then** I am redirected to my dashboard  
**And** I see a welcome message with my name

#### Scenario 2: Invalid Password
**Given** I am on the login page  
**When** I enter a valid email but an incorrect password  
**Then** I see an error message "Invalid email or password"  
**And** I remain on the login page

#### Scenario 3: Account Locked After Failed Attempts
**Given** I have failed to log in 5 times  
**When** I attempt to log in again  
**Then** I see an error message "Account temporarily locked. Try again in 15 minutes."

### Success Metrics
- Login success rate > 95%
- Average login time < 2 seconds
- Account lockout false positive rate < 0.5%

### Test Steps
1. Create test user accounts with known credentials
2. Test successful login with valid credentials
3. Test login failure with incorrect password
4. Test account lockout after 5 failed attempts
5. Verify analytics tracking for login events

### Definition of Done
- [x] All acceptance criteria scenarios pass
- [x] Unit tests for authentication logic written and passing
- [x] Login flow tested on Chrome, Firefox, Safari
- [x] Security review completed (password hashing, rate limiting)
- [x] Documentation updated with login instructions
- [x] QA sign-off received
