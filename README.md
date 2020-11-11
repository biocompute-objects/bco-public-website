# BioCompute Object dot Org (biocomputeobject.org) 

[![Netlify Status](https://api.netlify.com/api/v1/badges/e549beca-340b-4022-bbca-6ece5196728c/deploy-status)](https://app.netlify.com/sites/condescending-leakey-26b782/deploys)

This repo hosts the source code for a Hugo-based prototype of [biocomputeobject.org](https://www.biocomputeobject.org/).

Notes:
- Netlify site: https://condescending-leakey-26b782.netlify.app/

Source
- All Markdown files are under [/contents](/contents)
- All images are in [/static/images](/static/images)
- All documents and attachments are under [/static/docs](/static/docs)

Hosting
- The current static website hosting solution is Netlify.
- New Git commits pushed to the repo will trigger Netlify to build and publish a new version. This means a purely Git-based publishing workflow: simply edit the Markdown files on GitHub.

Theming
- Created a responsive Hugo theme named hugo-biocompute with Bootstrap 4, mimicking the original design, under /themes
- The main font is switched to Public Sans

Content
- The content and layout are mostly migrated as-is, including google tag manager code
- The news section in the previous about page now has it own page to make it easier to navigate and stand out
- The contact form is replaced by Netlify Forms to avoid local servers

URL
- Changed to the RESTful style. Old urls with the .html extension will be automatically redirected
