# voter-app
the app verifies whether a voter is registered

## Deployment

This is a static HTML app. The entry point is [index.html](index.html), so configure the host to publish the repository root.

For GitHub Pages, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. Changes can take a few minutes to appear.

The current build is a preview: voter and admin data is held only in browser memory, and sign-in does not provide real authentication or persistence.
