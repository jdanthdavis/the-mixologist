# Mixology Order Advisor

A lightweight single-page app for Mastering Mixology order optimization.

## Local preview

```bash
cd the-mixologist
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Render deployment

This project is a static HTML app, so it can be hosted on Render as a Static Web Service.

Recommended Render setup:

1. Push this repo to GitHub.
2. In Render, create a new Static Site.
3. Connect the GitHub repo.
4. Set the branch to `main`.
5. Keep the publish directory as `.`.
6. Create the service and wait for Render to deploy.

The included [render.yaml](render.yaml) is ready to use with Render when the repo is connected.

## Notes

- No backend is required.
- The app runs entirely in the browser.
- It works on desktop and mobile without extra dependencies.
