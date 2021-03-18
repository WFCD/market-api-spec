# DEPRECATION
---

This repo won't be updated anymore, as Warframe.Market... finally published their own! [See here](https://warframe.market/api_docs)


# Warframe.Market OpenAPI Specification
[![Build Status](https://travis-ci.com/wfcd/market-api-spec.svg?branch=master)](https://travis-ci.com/wfcd/market-api-spec)

## Links

- [Reference Documentation (ReDoc)](https://wfcd.github.io/market-api-spec/)
- [SwaggerUI](https://wfcd.github.io/market-api-spec/swagger-ui/)
- OpenAPI Raw Files: [JSON](https://wfcd.github.io/market-api-spec/openapi.json) [YAML](https://wfcd.github.io/market-api-spec/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
