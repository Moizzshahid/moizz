# Local Preview

The current project is made of static web pages, so a framework installation is not needed to inspect the UI.

## Option 1: Open directly

1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html`.

Some browser features behave more consistently when pages are served over HTTP rather than opened with a `file://` URL.

## Option 2: Use a local static server

If Python is installed, open a terminal in the repository folder and run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

Stop the server with `Ctrl+C`.

## Troubleshooting

- If an image is missing, check its relative path and filename casing.
- If a page looks unstyled, check the browser console for missing resources.
- If a change does not appear, refresh the page and check whether the browser cached an asset.
