# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

Marketing site for **Grant Comer Produce**, a Phoenix-area produce and dry-goods supplier serving restaurants. The repo currently contains only `README.md` and `CNAME` — there is no application code, build pipeline, or test suite. The README itself is the canonical source of business copy (services, product list, contact details).

## Hosting

- Served as a GitHub Pages site for the custom domain in `CNAME` (`grantsproduce.com`). Pushing to the default branch on `github.com:clintus/grants-produce` is the deploy.
- Do not delete or rename `CNAME` — removing it breaks the custom-domain mapping.

## Working in this repo

- There are no `npm`, build, lint, or test commands. Treat edits as content edits unless you are explicitly scaffolding a site.
- Contact details in the README (email `info@grantsproduce.com`, phone `602.254.2901`, text `602.577.4959`) and the service area (greater Phoenix metro) are real business info — preserve them verbatim unless the user asks otherwise.
- If a task requires introducing a static-site generator or framework (Jekyll, Astro, Next, etc.), confirm with the user first; the current setup is plain GitHub Pages with no Jekyll config.
