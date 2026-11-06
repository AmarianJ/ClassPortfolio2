# Accessibility Audit

## Initial Findings
- **Tool used:** Google PageSpeed Insights (Mobile)
- **Initial Accessibility Score:** 93
- **Issues Found:** Links rely on color to be distinguishable (Contrast issue).

## Fixes Applied
- **Issue Fix:** Removed `text-decoration: none` from the global `<a>` tag in the CSS and replaced it with `text-decoration: underline` (along with a `text-underline-offset: 3px` for visual polish). This ensures links in the body text are identifiable by more than just color, satisfying WCAG guidelines.

## Final Score
- **Final Accessibility Score:** 100

