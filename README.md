# Azure Static Web Apps with Custom Functions

Take advantage of the flexibility of Azure Functions and leverage the ease-of-use of Azure Static Web Apps.

This demo app shows how to link an Azure Static Web App to an existing Azure Functions app. To run the application, you need to run the [API app](https://github.com/craigshoemaker/static-web-apps-custom-functions-api) before attempting the below steps to run this front-end application.

## Prerequisites

- [Azure Static Web Apps CLI](https://github.com/Azure/static-web-apps-cli)
- [Azure Functions VS Code extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions)
- [Azure Static Web Apps VS Code extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestaticwebapps)
- [Sample API project](https://github.com/craigshoemaker/static-web-apps-custom-functions-api)

## Get started

1. Clone the repository:

    `git clone https://github.com/craigshoemaker/static-web-apps-custom-functions`

1. Change folders:

    `cd static-web-apps-custom-functions`

1. Install dependencies:

    `npm install`

1. Install Static Web Apps CLI:

    `npm install -g @azure/static-web-apps-cli`

1. Start the app:

    `swa start`