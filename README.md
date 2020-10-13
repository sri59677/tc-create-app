[![Netlify Status](https://api.netlify.com/api/v1/badges/b1463957-7c2f-4297-b5f0-afb4f985a2fc/deploy-status)](https://app.netlify.com/sites/tc-create-app/deploys)
[![Custom badge](https://img.shields.io/endpoint?color=%2374b9ff&url=https%3A%2F%2Fraw.githubusercontent.com%2FunfoldingWord%2Ftc-create-app%2Fmaster%2Fcoverage%2Fshields.json)]()
![Coveralls github](https://img.shields.io/coveralls/github/unfoldingWord/tc-create-app?label=Unit%20Tests)
![ ](https://github.com/unfoldingWord/tc-create-app/workflows/Install%2C%20Build%20%26%20Run%20Cypress/badge.svg?branch=master)

https://create.translationcore.com

# Development and Deployment Process 2

## Changes completed: 
- Github: `develop` branch created and made default on `tc-create-app` repo.
- Netlify branch deploys enabled for `develop` branch: https://develop--tc-create-app.netlify.com

## Workflow: 
- PRs will automatically be created against `develop` branch from here.
- PRs will build and deploy on Netlify for previews.
- Merges to `develop` branch will build and deploy here: https://develop--tc-create-app.netlify.com
- QA and others can verify `develop` before merging to `master`.
- When `master` is updated, production will be deployed: https://tc-create-app.netlify.com
