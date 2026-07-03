# Contributing to Helios Pro

Thanks for helping improve Helios Pro.

## Good First Contributions

- Fix responsive layout bugs.
- Improve accessibility labels and keyboard states.
- Add missing loading, empty, or error states.
- Improve TypeScript types.
- Add clean examples for dashboard pages.
- Improve documentation and setup notes.

## Local Setup

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Pull Request Checklist

- Keep the existing visual style consistent.
- Do not add unrelated dependencies.
- Run `npm run lint` before submitting.
- Run `npm run build` for larger changes.
- Keep PRs focused and easy to review.

## Code Style

- Use TypeScript for new files.
- Prefer existing components and utilities before creating new abstractions.
- Keep Tailwind classes readable and consistent with nearby code.
- Avoid hard-coded secrets, private URLs, or credentials.
