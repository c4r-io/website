# C4R website

[![Netlify Status](https://api.netlify.com/api/v1/badges/feaf3de2-e269-40ef-8d89-cf43b4c6fdfd/deploy-status)](https://app.netlify.com/sites/c4r-dev/deploys)

Contains the source for the [`c4r.io`](https://c4r.io) website. 

# Editing the website

The website is built through [jupyterbook](https://jupyterbook.org/en/stable/intro.html). This is a standard install with the furo theme and the quizdown extension enabled. 

## Small changes

To fix typos, you can directly edit the website source through github. After committing, the site will be rebuilt and redeployed through netlify. It takes about 60 seconds to go from PR accepted to site redeployed.

## Larger changes

To make more substantial changes locally, clone this repo. To build:

```
jupyter-book build .
```

Load `_build/html/index.html` into your browser to preview your changes. Once you're satisfied with changes, send a PR. No need to push files in _build/html. 

Once the PR is in, the site will be rebuilt and redeployed through netlify. It takes about 60 seconds to go from PR accepted to site redeployed.
