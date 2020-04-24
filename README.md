# Simple Example using Cypress E2E tests
PageObject in `../support/pages/..`
Tests in `../integration`

## Clone Project
`git clone https://github.com/Sayoan/cypress_example.git`
## Installing the Cypress first time (only in the first time)
[![npm version](https://camo.githubusercontent.com/eeac3804665f2c05dfaf1d18dff2722db530cde0/68747470733a2f2f62616467652e667572792e696f2f6a732f637970726573732e737667)](https://badge.fury.io/js/cypress)
Install Cypress for Mac, Linux, or Windows, then  [get started](https://docs.cypress.io/guides/getting-started/installing-cypress.html).

`npm install cypress --save-dev`

## Prepare the dependencies
install all dependencies from the root directory
`npm install`

## Opening Cypress GUI
to open the cypress and run tests
`npm run cypress:open` 
if u want customize u need access `.../package.json`

## Running from the CLI
`npm run cypress:run`
running switching browser
`npm run cypress:run -- --browser chrome`
sends test results, videos, screenshots to Cypress dashboard
`npm run cypress:run -- --record`
