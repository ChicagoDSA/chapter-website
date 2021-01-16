# Chapter website

This site uses the [Haymarket](https://github.com/ChicagoDSA/haymarket) theme.

## Contributing & branching info

The two primary branches in this repo are `prod` and `staging`. When making contributions, always branch off of and merge back into staging first. The staging branch is [deployed here](https://cdsa-staging.netlify.app/) via Netlify, and after merging your changes, they will automatically deploy to that link. Once changes are verified and stable, `staging` can then be merged into `prod` which is deployed via GitHub pages. For access to the staging instance on Netlify, reach out to @nickharriscodes here on Github or in the CDSA slack. 

## Updating content

The homepage can be edited by opening `_homepage/en/index.md` and clicking on the `Edit this file` button.
- It's written in Markdown.
- [Here's a 2-page PDF that contains syntax examples](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf).

Pages within a collection, such as **Defund CPD**, live in their own folders.
- `_campaigns` contains the Markdown files that generate individual campaign pages.
- Generated URL: `my-website.org/collection-name-without-underscore/page-name/`

Single pages, such as **New members**, live in the `_pages` folder.
- Generated URL: `my-website.org/page-name/`

## Updating events

Events are managed on [teamup](https://www.teamup.com/). Instructions for adding new events to the calendar are [here](https://docs.google.com/document/d/1uzYh-cazDNuoNRhTttrvU-iuDkyXXDf7thJbU5oBWIg).
