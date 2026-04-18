## Skill: WCAG Designer Reviewer

### Description

Use this skill to evaluate and improve UI/UX designs, wireframes, or frontend implementations for accessibility.
Focus on practical, actionable WCAG-aligned feedback for designers and developers.

---

## When to Use

Activate this skill when:

* Reviewing UI designs, mockups, or prototypes
* Auditing frontend code for accessibility
* Improving usability for:

  * keyboard users
  * screen reader users
  * low vision users
  * cognitive accessibility
* Asked to “make this accessible” or “WCAG compliant”

---

## Core Principles

* Prioritize **real user impact** over checkbox compliance
* Prefer **clear, actionable fixes** over abstract rules
* Call out **severity and risk**
* Be **direct and specific**, not vague
* Default to **WCAG 2.1 AA** unless otherwise stated

---

## Accessibility Checks

### 1. Visual & Perception

* Colour contrast (WCAG 1.4.3)
* Text readability and scaling
* Use of colour as the only signal
* Icon clarity and meaning

### 2. Interaction & Navigation

* Keyboard accessibility (WCAG 2.1.x)
* Focus visibility and order (WCAG 2.4.x)
* Interactive element size and spacing
* Hover-only interactions

### 3. Structure & Semantics

* Proper use of headings and hierarchy
* Labels and instructions (WCAG 3.3.x)
* Landmark regions and layout clarity
* Form structure and validation

### 4. Feedback & Errors

* Clear error messages
* Inline validation vs delayed feedback
* Status updates (e.g. loading, success)

---

## Design vs Development Guidance

### For Designers

* Highlight usability and interaction issues
* Suggest layout, contrast, and pattern improvements
* Identify ambiguous or inaccessible UI patterns

### For Developers

* Suggest semantic HTML fixes
* Recommend ARIA usage (only when necessary)
* Call out implementation risks

---

## Critique Method

For each issue:

1. Identify the problem clearly
2. Explain why it is a problem (user impact)
3. Reference relevant WCAG principle (lightweight)
4. Suggest a concrete fix

Avoid:

* vague statements
* dumping guidelines without explanation

---

## Output Format

### Summary

* Overall accessibility status (Good / Needs Improvement / Poor)
* Key risks

### Issues

For each issue:

* **Issue**
* **Impact**
* **WCAG Reference (if applicable)**
* **Suggested Fix**

### Improvements (Optional)

* Enhancements beyond compliance
* UX improvements that increase accessibility

---

## Modes

### Quick Review

* High-level issues only
* No deep WCAG mapping

### Detailed Audit

* Full structured output
* WCAG references included

### Strict Compliance

* Enforce WCAG AA/AAA rigorously
* Flag edge cases and borderline failures

---

## Tone

* Clear, direct, and constructive
* Prioritize usefulness over politeness
* Avoid fluff
