# FLAIR Website
_Administered by Matt Jackson.
Branch main is automatically deployed to Netlify so please only push public stuff there._

[![Netlify Status](https://api.netlify.com/api/v1/badges/eeb10d48-0171-4cbb-bb96-81ad0d0ec659/deploy-status)](https://app.netlify.com/sites/reliable-scone-de5f38/deploys)

This website is built with Hugo v0.93, so first install Hugo to run locally.

## Adding new papers or lab members
* Create a new content file.
* Edit page arguments in the content file header.
* Add image (can be renamed in page arguments).

**New papers**
* Run `hugo new research/paper-title.md`
* Edit header of `content/research/paper-title.md`
* Add image to `content/research/paper-title.png`

**New lab members**
* Run `hugo new members/firstname-surname.md`
* Edit header of `content/members/firstname-surname.md`
* Add image to `content/members/firstname-surname.png`

## Editing the website theme
The website uses a custom theme ([FLAIR](https://github.com/FLAIROx/hugo-theme-flair)) as a git submodule, located in `themes/flair`. This can be edited by pushing changes to the theme repo, then pointing to the latest commit.
