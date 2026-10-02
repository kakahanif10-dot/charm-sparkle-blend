# Merge the three requested pages

## Outcome
- Keep the Sparky landing page unchanged at `/`.
- Keep the Sparky login page unchanged at `/login`.
- Replace Sparky's third page with the AI Dash Bloom workspace at `/workspace`.
- Preserve each source project's existing styling, imagery, copy, and interactions.

## Implementation
- Use the Sparky project as the base so its landing-to-login flow remains intact.
- Bring in only the Bloom workspace files, image, and generation function needed for page three.
- Point successful login and landing calls-to-action to the Bloom workspace.
- Retain the existing TanStack app structure and only install dependencies required by the copied pages.
- Verify all three pages render at desktop and mobile widths and check the current build status.

## Scope boundary
No redesign, copy rewrite, or extra features will be added.
