# GS Transfer API OpenAPI Specification

[![Build Status](https://travis-ci.org/grey-systems/gs-mtc-transfer-gateway-doc.svg?branch=master)](https://travis-ci.org/grey-systems/gs-mtc-transfer-gateway-doc)

## Links

- Documentation(ReDoc): https://grey-systems.github.io/gs-mtc-transfer-gateway-doc
- SwaggerUI: https://grey-systems.github.io/gs-mtc-transfer-gateway-doc/swagger-ui
- Look full spec:
  - JSON https://grey-systems.github.io/gs-mtc-transfer-gateway-doc/swagger.json
  - YAML https://grey-systems.github.io/gs-mtc-transfer-gateway-doc/swagger.yaml
- Preview spec version for branch `[branch]`: https://grey-systems.github.io/gs-mtc-transfer-gateway-doc/preview/[branch]

## Working on specification

### Install

1.  Install [Node JS](https://nodejs.org/) v10.x.x (or use a version manager for NodeJS like [NVM](https://github.com/nvm-sh/nvm))
2.  Clone repo and `cd`
    - Run `npm install` (or `npm ci` if prefer a clean install, without update `package-lock.json` dependencies)

### Usage

1.  Run `npm start`
2.  Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://grey-systems.github.io/gs-mtc-transfer-gateway-doc/ with url from the message: `Server started <url>`
3.  Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4.  All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
    **TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
    **TIP2:**: You can manually add changes modifying the `./spec/swagger.yaml`. Keep in mind that manual changes might break the swagger specification.
5.  Once you finish with the changes you can run tests using: `npm test`
6.  Share you changes with the rest of the world by pushing to GitHub :smile:
