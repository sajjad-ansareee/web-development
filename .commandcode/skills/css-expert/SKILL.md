---
name: css-expert
description: Use when creating, editing, reviewing, or optimizing CSS. Produces clean, maintainable, responsive, production-ready CSS without frameworks.
---

# CSS Expert

## Objectives

- Write clean, maintainable CSS.
- Prioritize readability, scalability, responsiveness, accessibility, and performance.
- Produce production-ready styles.
- Use only vanilla CSS unless instructed otherwise.

## Follow

- Write modular CSS.
- Keep styles organized.
- Follow a consistent coding style.
- Minimize selector complexity.
- Use modern CSS features where supported.

## Organization

- Group related styles together.
- Keep a logical file structure.
- Order declarations consistently.
- Separate layout, components, and utilities.
- Comment major sections only.

## Selectors

- Prefer class selectors.
- Keep specificity low.
- Avoid unnecessary nesting.
- Avoid ID selectors for styling.
- Avoid element selectors unless appropriate.
- Never use `!important` unless explicitly required.

## Naming

- Use descriptive class names.
- Keep naming consistent.
- Prefer component-based naming.
- Avoid vague names.
- Avoid numbered class names.

## Layout

- Prefer Flexbox for one-dimensional layouts.
- Prefer Grid for two-dimensional layouts.
- Use logical spacing.
- Avoid layout hacks.
- Avoid unnecessary positioning.
- Use `gap` instead of margin spacing where appropriate.

## Sizing

- Use relative units where appropriate.
- Use `rem` for typography.
- Use `%`, `fr`, `vw`, `vh` appropriately.
- Minimize fixed dimensions.
- Respect container boundaries.

## Spacing

- Use consistent spacing scale.
- Prefer margin for separation.
- Prefer padding for internal spacing.
- Avoid magic numbers.
- Maintain visual rhythm.

## Typography

- Use readable font sizes.
- Maintain consistent line height.
- Limit font families.
- Use responsive typography.
- Avoid extremely small text.

## Colors

- Use CSS variables.
- Maintain accessible contrast.
- Keep color palette consistent.
- Avoid hardcoded repeated colors.

## CSS Variables

- Store colors.
- Store spacing.
- Store typography values.
- Store border radius.
- Store shadows.
- Store transitions.
- Reuse variables whenever possible.

## Responsive Design

- Mobile-first.
- Use media queries only when needed.
- Design for multiple screen sizes.
- Avoid fixed layouts.
- Test common breakpoints.
- Maintain consistent spacing across devices.

## Images

- Prevent distortion.
- Maintain aspect ratio.
- Optimize backgrounds.
- Use responsive image sizing.

## Animations

- Keep animations subtle.
- Use transforms instead of layout changes.
- Animate opacity and transform when possible.
- Avoid expensive animations.
- Respect reduced-motion preferences.

## Transitions

- Keep durations consistent.
- Transition only necessary properties.
- Avoid long animations.

## Performance

- Keep selectors efficient.
- Avoid unnecessary overrides.
- Avoid deep selector chains.
- Reduce duplicated styles.
- Reuse utility patterns when appropriate.
- Minimize repaint and reflow.

## Accessibility

- Preserve focus indicators.
- Ensure sufficient contrast.
- Respect prefers-reduced-motion.
- Do not disable text selection without reason.
- Do not prevent browser zoom.
- Ensure interactive states are visible.

## States

- Style:
  - hover
  - focus
  - focus-visible
  - active
  - disabled
  - visited (when applicable)

## Modern CSS

- Use Flexbox.
- Use Grid.
- Use `clamp()` where appropriate.
- Use `min()`, `max()`, and `calc()` when beneficial.
- Use logical properties when appropriate.
- Prefer `aspect-ratio` over hacks.

## Avoid

- `!important`
- Inline styles.
- Deep selector nesting.
- Duplicate rules.
- Duplicate properties.
- Redundant declarations.
- Overqualified selectors.
- Fixed heights unless required.
- Magic numbers.
- Large z-index values without reason.
- Unused styles.
- Vendor prefixes unless necessary.

## Code Style

- Two-space indentation.
- One declaration per line.
- Consistent property ordering.
- Blank line between rule groups.
- Lowercase property names.
- Consistent formatting.

## Property Order

- Positioning
- Display
- Flex/Grid
- Box Model
- Dimensions
- Overflow
- Typography
- Background
- Borders
- Effects
- Transform
- Transition
- Animation
- Miscellaneous

## Before Responding

- Clean architecture.
- Low specificity.
- Responsive.
- Accessible.
- Mobile-first.
- No unnecessary code.
- No duplicated styles.
- Consistent spacing.
- Consistent typography.
- Uses CSS variables.
- Optimized performance.
- Ready for production.

## Consistency

- Reuse existing classes before creating new ones.
- Do not duplicate existing styles.
- Extend existing components whenever possible.
- Keep spacing consistent with the existing design system.
- Keep typography consistent across pages.
- Keep border radius, shadows, and transitions consistent.
- Do not introduce new colors unless requested.
