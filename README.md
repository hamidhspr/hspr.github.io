# GitHub Pages starter

This repository contains a minimal static website for GitHub Pages.

How to deploy
1. If you want a *user site* (username.github.io), name the repo `hamidhspr.github.io`. Push `index.html` to the default branch (`main`).
2. For a *project site*, create any repo and push files to `main` (or build to `gh-pages`).
3. In the repository Settings → Pages:
   - Source: choose the branch (e.g., `main`) and folder (`/ (root)`).
   - Save — your site will be published at `https://<owner>.github.io/<repo>/` for project pages or `https://<username>.github.io/` for user pages.

Options I can set up for you
- Quick static HTML (what I prepared) — simplest.
- Jekyll site (GitHub Pages supports Jekyll natively) — I can scaffold `_config.yml`, a theme, and basic layouts.
- Hugo or other SSG — I can create a GitHub Action that builds and deploys to `gh-pages`.
- Custom domain — I can add a `CNAME` file and instructions for DNS configuration.

Tell me
- Do you want a user site or a project site?
- Repository owner/name (exact string) so I can create/push files for you.
- Do you want plain HTML, Jekyll, or Hugo?
- Do you have a custom domain (yes/no and the domain name)?

If you want me to push these files for you, reply with:
- The repository in owner/name format (for example: `hamidhspr/hamidhspr.github.io`)
- Whether to create the repository if it doesn't exist
- Which branch to publish from (`main` recommended) and site type (user/project)
I will then create the repo (if you ask) and push the starter files and enable Pages configuration for you.