ndix C: accessibility-audit.md
# Accessibility Audit Report
## Tool used
- Google Lighthouse / WAVE
## Page tested
- Student Activity Management Portal (`labexpt1.html`)
## Audit results
| Check | Result | Evidence |
|---|---|---|
| Page language specified | Pass | `<html lang="en">` |
| Unique page title | Pass | `<title>Student Activity Management Portal | University Events</title>` |
| Heading hierarchy | Pass | One `h1`, followed by `h2` and `h3` headings |
| Landmark regions | Pass | `header`, `nav`, `main`, `aside`, and `footer` used |
| Skip link | Pass | “Skip to main content” link focuses `#main-content` |
| Form labels | Pass | Every form control has an associated `<label>` |
| Field grouping | Pass | Radio buttons and checkboxes use `fieldset` and `legend` |
| Required-field identification | Pass | `required`, `aria-required`, and visible asterisks used |
| Keyboard navigation | Pass | Native links, inputs, selects, buttons, radio buttons, and checkboxes are keyboard accessible |
| Color contrast | Pass | Dark blue text on light background meets contrast requirements |
| Images | Not applicable | No images used in the initial implementation |
## Issues identified
- No critical accessibility issues were identified after testing.
- The form uses browser-native validation; JavaScript-based custom error messages can be added in a later experiment.
## WCAG criteria addressed
- 1.3.1 Info and Relationships
- 2.4.1 Bypass Blocks
- 2.4.6 Headings and Labels
- 3.3.2 Labels or Instructions
- 4.1.2 Name, Role, Value