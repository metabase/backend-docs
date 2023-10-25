# backend-docs

_The literary home for Metabase Clojurians_

This repo has two parts: the `master` branch has a Github action to get the Metabase source code, generate an HTML file
with Marginalia, and push it to this repo's `gh-pages` branch. It runs on a cron job, currently every eight hours.

The `gh-pages` branch gets automatically deployed to
[metabase.com/backend-docs](https://www.metabase.com/backend-docs/).

