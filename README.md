# github-contribution-log

# Contribution [#]: [Issue Title]

**Contribution Number:** 1  
**Student:** Zayd Tawam  
**Issue:** https://github.com/SwitchbackTech/compass/issues/1326
**Status:** Phase I Completed

---

## Why I Chose This Issue

Compass is a React/TypeScript calendar app which made it a good fit for my current goal of wanting to refresh and further develop my React and TypeScript skills. This issue asks for keyboard navigation using TAB, SHIFT+TAB, SPACE, and ENTER. The issue requires working with more advanced React concepts like event handling rather than just simple style changes. I prefered this over simple one-line fixes. I also wanted to work on something with clear, testable acceptance criteria and explicit guidance on how to approach it. 

---

## Understanding the Issue

### Problem Description

When a user edits a recurring event in Compass, a popup appears asking them to choose the scope of the change: "This Event", "This and Following Events", "All Events", or cancel. Currently, keyboard users cannot interact with this at all — pressing TAB, ENTER, SPACE, or SHIFT+TAB does nothing. There are also no visible focus styles to indicate which option is currently selected or focused, making the popup completely inaccessible to keyboard users.

### Expected Behavior

When the recurrence scope modal appears, the user should be able to navigate between the options using TAB and SHIFT+TAB, select an option using SPACE or ENTER, and see a visible focus indicator on whichever option is currently focused. This should also apply to the Cancel and Save buttons in the modal.

### Current Behavior

Keyboard input is ignored entirely. No options become focused, no selection is made, and no focus styles appear. The modal can only be interacted with using a mouse.

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

The recurrence scope selection modal component and its associated event handlers. Based on the maintainer's context notes, the fix will likely involve the modal's keyboard event handling, focus management (using floating-ui's built-in accessibility features), and Tailwind focus styles consistent with the day view. Tests will also need to be added or modified.

### Steps to Reproduce


### Reproduction Evidence


---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
