# BioCompute Object dot Org (biocomputeobject.org) 

This repo hosts the source code for a Hugo-based prototype of [biocomputeobject.org](https://www.biocomputeobject.org/).

Deployed prototype: https://condescending-leakey-26b782.netlify.app/

Source code: https://github.com/biocompute-objects/bco-public-website

Notes:

Source
- All Markdown files are under /contents

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

Action items if we decide to eventually migrate:

 1) Fix some expired links in the content
 2) Migrate other additional artifacts from the original site (if any)
 3) Move the source code to a GitHub repo under the account @biocompute-objects
 4) Set up the new site on the hosting provider of choice
 5) Update the DNS name record and point to the hosting provider
 6) Retire the original server
