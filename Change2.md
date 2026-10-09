# Design Refinement

This change has three design and accessibility goals:

1. **Improve typography and spacing**
   - Keep text line lengths readable at about 65–75 characters.
   - Use consistent vertical spacing between sections.
   - Establish a clear heading hierarchy.

2. **Highlight the current page in navigation**
   - Use Jekyll, without JavaScript, to identify the current page.
   - Mark the active navigation link with `aria-current="page"`.
   - Add an accessible visual indicator beyond color alone, such as an underline.

3. **Style Projects entries as cards**
   - Give each project entry a subtle card style with a light border.
   - Use consistent padding and spacing between cards.
