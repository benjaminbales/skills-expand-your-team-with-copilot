# Issue Templates Guide

This repository uses issue templates to help teachers and administrators submit well-defined change requests that can be easily handled by GitHub Copilot coding agent.

## Available Templates

### 🚀 Feature Request
Use this template when you want to add new functionality to the High School Management System.

**Best for:**
- Adding new views or pages (e.g., calendar view, reports)
- New features for activities management
- Student management enhancements
- Filtering, sorting, or grouping improvements

**Required information:**
- Clear problem description
- Proposed solution
- Acceptance criteria (specific, testable requirements)

**Example:** "Add a calendar view to visualize activity schedules by week"

---

### 🐛 Bug Report
Use this template when something isn't working correctly.

**Best for:**
- Functionality that's broken or not working as expected
- Error messages or crashes
- Data not displaying correctly
- Registration or sign-up issues

**Required information:**
- Bug description
- Steps to reproduce
- Expected vs. actual behavior
- Error messages (if any)

**Example:** "Sign-up button doesn't work for Basketball activity"

---

### 🎨 UI/Visual Change
Use this template for changes to how the application looks.

**Best for:**
- Color scheme changes (branding, school colors)
- Layout or design improvements
- Adding images, logos, or mascots
- Font or typography changes
- Visual effects or animations

**Required information:**
- Current visual state
- Desired changes with specific details (colors, images, etc.)
- Acceptance criteria for visual elements

**Example:** "Change website colors to match school colors (white and lime green)"

---

### 📊 Activity Data Update
Use this template to add, modify, or remove activity data.

**Best for:**
- Adding new activities to the system
- Updating activity schedules, times, or locations
- Changing activity details (instructor, max enrollment, etc.)
- Removing activities that are no longer offered

**Required information:**
- Complete activity details (name, category, time, location, etc.)
- What should change (for modifications)
- Data validation requirements

**Example:** "Add Robotics Club on Thursdays from 3:30-5:00 PM in Room 204"

---

### 📝 Documentation Update
Use this template to improve documentation or help text.

**Best for:**
- Updating README or setup instructions
- Adding user guides or help documentation
- Improving code documentation
- Fixing outdated information

**Required information:**
- What's wrong with current documentation
- What should be documented instead
- Which files need updating

**Example:** "Add setup instructions to README for new teachers"

---

## Tips for Writing Good Issues

### Be Specific
❌ Bad: "Make the website better"  
✅ Good: "Add a filter to show only sports activities"

### Include Acceptance Criteria
Use checklists to define what "done" means:
- [ ] Feature X is visible on the page
- [ ] Users can click button Y
- [ ] Data is saved correctly

### Provide Context
- Why is this change needed?
- Who will use it?
- Are there any constraints or limitations?

### Add Technical Hints (If You Know)
- Suggest which files might need changes
- Mention similar features that already exist
- Link to relevant documentation or examples

### Include Examples
- Screenshots of what you want
- Links to similar features on other sites
- Mockups or drawings (even hand-drawn!)

---

## How GitHub Copilot Uses These Templates

When you fill out an issue template completely, GitHub Copilot coding agent can:

1. **Understand the problem** from your clear description
2. **Know what to build** from your acceptance criteria
3. **Get started quickly** using your technical hints
4. **Avoid mistakes** by following your constraints

The more detail you provide, the better Copilot can help!

---

## Need Help?

- Not sure which template to use? Start with **Feature Request** or **Bug Report**
- Questions about the system? Use the [Discussions](../../discussions) tab
- Urgent issues? Tag your issue with `urgent` label

---

## Examples of Well-Defined Issues

### Good Feature Request
```
Problem: Students can't see which activities meet on the same day
Proposed Solution: Add a filter to show activities by day of week
Acceptance Criteria:
- [ ] Dropdown filter with days of week (Monday-Friday)
- [ ] Activities list updates when day is selected
- [ ] "All Days" option shows everything
```

### Good Bug Report
```
Bug: Sign-up button returns error for Drama Club
Steps to Reproduce:
1. Go to activities page
2. Find Drama Club
3. Click "Sign Up" button
4. See error: "Activity not found"

Expected: Student is registered
Actual: Error message appears
```

### Good UI Change
```
Current: Website uses blue color scheme
Desired: Change to school colors
- Primary: #32CD32 (lime green)
- Background: white
- Add school mascot in header from octodex.github.com

Acceptance Criteria:
- [ ] All buttons are lime green
- [ ] Background is white
- [ ] Mascot image appears in header
```

---

*For more information, see [GitHub's Issue Template Documentation](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)*
