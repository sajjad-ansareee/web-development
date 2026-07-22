---
name: html-expert
description: Use when creating, editing, reviewing, or optimizing HTML. Produces semantic, accessible, responsive, production-ready HTML.
---

# HTML Expert

## Objectives

- Write clean, semantic HTML5.
- Prioritize accessibility, SEO, maintainability, and performance.
- Produce production-ready code.

## Follow

- Use HTML5.
- Include `<!DOCTYPE html>`.
- Set `lang` on `<html>`.
- Include UTF-8 charset.
- Include viewport meta tag.
- Use meaningful `<title>`.
- Add meta description when appropriate.

## Structure

- Use a logical document hierarchy.
- Follow a consistent page structure.
- Prefer semantic elements.
- Keep DOM shallow.
- Avoid unnecessary wrappers.
- Use logical document structure.
- Use one `<main>`.

## Semantic Elements

- Prefer `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`.
- Use `figure` and `figcaption` when appropriate.
- Use `div` only when no semantic element fits.

## Semantic Usage

- Use `<section>` only for thematically grouped content.
- Use `<article>` for independent, reusable content.
- Use `<div>` only when no semantic element fits.
- Do not wrap every block in a `<section>`.
- Do not use semantic elements purely for styling.
- Choose the most meaningful element for the content.

## Accessibility

- One `<h1>` per page.
- Maintain heading hierarchy.
- Every input has a label.
- Every image has an `alt`.
- Buttons use `<button>`.
- Use ARIA only when necessary.
- Preserve keyboard accessibility.

## Forms

- Every control has `id` and `name`.
- Use appropriate input types.
- Specify button `type`.
- Use autocomplete when applicable.
- Use `required` only when appropriate.

## Images

- Include `alt`.
- Include dimensions when known.
- Use `loading="lazy"` for non-critical images.

## Links

- Use descriptive link text.
- Use the suited hyperlink instead of generic anchor tag.
- External links:
  - `target="_blank"`
  - `rel="noopener noreferrer"`

## Tables

- Use only for tabular data.
- Include `thead` and `tbody`.
- Use `th` with `scope`.
- Add `caption` when appropriate.

## Code Style

- Two-space indentation.
- Double quotes.
- Lowercase tags and attributes.
- Consistent formatting.
- Meaningful class names.
- Descriptive IDs.

## Avoid

- Deprecated tags.
- Inline CSS unless requested.
- Inline JavaScript unless requested.
- Layout tables.
- Empty links.
- Empty buttons.
- Duplicate IDs.
- Nested forms.
- Invalid HTML.
- Excessive `div` nesting.
- Placeholder content unless requested.

## If CSS is requested

- Keep HTML and CSS separate.

## If JavaScript is requested

- Keep HTML, CSS, and JavaScript separate.

## Before Responding

- Semantic HTML.
- Valid HTML5.
- Accessible.
- Responsive-ready.
- SEO-friendly.
- Clean formatting.
- No unnecessary markup.
- No validation errors.
- Ready for production.