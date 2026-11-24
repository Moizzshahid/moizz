# Maintenance Guide

## Before editing

1. Identify which HTML page owns the element being changed.
2. Search for references to any asset or class that will be renamed.
3. Keep a copy of the current working version before large visual changes.

## While editing

- Prefer small, focused changes.
- Keep asset names descriptive and consistent.
- Avoid committing credentials, private data, or production secrets.
- Do not present a decorative sign-in control as real authentication.

## Before publishing

- Follow the manual checks in [the testing checklist](TESTING_CHECKLIST.md).
- Preview at desktop and mobile widths.
- Check all internal links and image paths.
- Review the final diff so unrelated design changes are not included.

## Future improvements

- Extract repeated styles into shared CSS if the pages begin to share components.
- Add automated checks when the project grows beyond a few static pages.
- Introduce a backend only if real user accounts or persistent data are required.
