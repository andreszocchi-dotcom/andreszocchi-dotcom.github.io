# Change 1: Add a Projects page

## Goal

Add a Projects page to the portfolio that presents the user's past projects, including websites and other work.

## Scope

- Add a Projects link to the main navigation.
- Add a Projects page at `/projects/`.
- Store project entries in `_data/projects.yml` so new projects can be added without editing page markup.
- Render project entries through a reusable Jekyll include.
- Show each project's title, short description, and a link when one is supplied; do not include a role field.
- Use only project details supplied by the user or verified from the published apps. Mark missing descriptions or links as placeholders; do not invent projects, features, or results.
- Keep the existing design, single-column layout, and accessibility standards, and verify the page at 375px and 1280px.
- Do not change existing pages except to add the navigation link.

## Confirmed project content

- Include Countdown APP, Trivia App, and Expense Tracker. The user supplied the titles and links and confirmed all three were built for an Intro to Coding Class.
- Base short descriptions on each published app's visible content; do not add unverified features or results.
- Do not request or display project-role details.
