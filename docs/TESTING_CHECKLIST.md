# Manual UI Testing Checklist

Use this checklist when changing a page or its assets.

## Layout

- [ ] Open each HTML page in a current desktop browser.
- [ ] Check the page at a narrow mobile viewport.
- [ ] Confirm content remains readable without horizontal scrolling.
- [ ] Confirm images load and preserve their intended proportions.

## Interaction

- [ ] Click every visible button and link.
- [ ] Check form fields can receive keyboard focus.
- [ ] Check modal open and close behavior where present.
- [ ] Check hover effects do not hide important information.
- [ ] Confirm browser back navigation behaves as expected.

## Regression

- [ ] Check the browser console for errors.
- [ ] Verify relative asset paths after moving or renaming files.
- [ ] Revisit all pages after shared CSS or JavaScript changes.

This is a manual checklist; it does not imply automated tests are configured.
