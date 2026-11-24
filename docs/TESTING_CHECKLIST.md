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

## Recent terminal improvements

- [ ] Start a terminal session with `start`, then confirm `help` lists available commands.
- [ ] Use `math` and `calc` with addition, subtraction, multiplication, division, parentheses, and decimals.
- [ ] Confirm invalid expressions and division by zero show a safe error instead of executing JavaScript.
- [ ] Press ArrowUp and ArrowDown in the command field to browse command history.
- [ ] Confirm terminal output displays typed text literally and does not interpret it as HTML.
- [ ] Check the terminal layout at narrow mobile widths.
- [ ] Check portfolio links and controls with a keyboard, and verify reduced-motion settings are respected.
- [ ] Verify contact links open the intended email address and the footer year is current.