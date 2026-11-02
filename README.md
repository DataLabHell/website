# DataLabHell Website

Source of [datalabhell.ac.at](https://datalabhell.ac.at), a static site (plain HTML, CSS and JS, no build step).

## Deployment

The site is deployed with **Cloudflare Pages** through the Cloudflare GitHub app.

- Pushes to `main` deploy to production.
- Every pull request gets its own preview deployment. The Cloudflare bot posts a comment on the PR with the preview URL and a branch preview URL. See [PR #5](https://github.com/DataLabHell/website/pull/5#issuecomment-6577403437) for an example.
- Project settings, deployments and logs: [Cloudflare dashboard](https://dash.cloudflare.com/fedc95a2b5fd0975da72ffacea11c57e/pages/view/datalabhell-ac-at)

## Blog

The blog lives in its own repository, [DataLabHell/blog](https://github.com/DataLabHell/blog), and is served at [blog.datalabhell.ac.at](https://blog.datalabhell.ac.at). This site only links to it from the navigation (see `components.js`).
