# Global preferences

## Way of working
- Always go step by step, scrum style: start with a draft/minimal version, then refine it over successive iterations toward a complete version.
- For each main step:
  1. State the goal and what "done" means.
  2. Build the smallest increment that meets it.
  3. Test it.
  4. Summarise what was done and suggest the next step.
- Keep the project working between steps.

## Code quality
- Main concerns: readability, maintainability, and safety/security.
- Safety relies on strong type safety: explicit, precise type definitions (interfaces, types, enums) for data, function signatures and boundaries. No loose or untyped values (e.g. no `any`); validate and narrow external input instead.
- Decouple code into multiple, well-organised files. Use (reusable) components whenever possible.
- Code must be self-explanatory through clear naming and structure, without relying on comments.
- Only use doc comments (Javadoc/JSDoc/docstring style) to describe what a class is, or what a method/function does: its inputs (parameters), output (return value) and the errors it throws.

## Testing
- At each main step, write and run unit tests and end-to-end tests.
- Don't move on while tests are failing, and report the results.

## Manual checks
- If a feature can't be tested automatically or needs human judgment (e.g. a UI change), ask me to check it manually.
- Give me a short checklist (what to open, what to do, what I should see) and wait for my feedback before calling the step done.

## Language
- For technical projects, always write file names, variable names, function names, code comments and documentation (README, docs) in English, so the project stays standardized and other people can contribute. Commit messages and pull request titles/descriptions are in English too.
- Only UI text and anything the end user will see may be in French or English.
