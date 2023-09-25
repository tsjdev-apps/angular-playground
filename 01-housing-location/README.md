# 01 - Housing Location

## Description

The lessons in this tutorial create an Angular app that lists houses for rent and shows the details of individual houses. This app uses features that are common to many Angular apps.

## Screenshot

![](docs/sample.png)

## Usage

### Install the correct version of node.js for Angular
If you do not have a version of `node.js`` installed, please follow the directions for [installation on nodejs.org](https://nodejs.org/en/download/)

### Install Angular CLI
With `node.js` and `npm` installed, the next step is to install the [Angular CLI](https://angular.io/cli) which provides tooling for effective Angular development.

### Install `json-server`

Install `json-server` from `npm` by using the following command: `npm install -g json-server`


### Install integrated development environment (IDE)

You are free to use any tool you prefer to build apps with Angular. We recommend the following:

- [Visual Studio Code](https://code.visualstudio.com/)
- As an optional, but recommended step you can further improve your developer experience by installing the [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

### Clone the repository

```bash
git clone https://github.com/tsjdev-apps/angular-playground.git
cd angular-playground/01-housing-location
```

### Install dependencies

```bash
npm install
```

### Run the `json-server`

```bash
json-server --watch db.json
```

### Run the application

```bash
ng serve
```

You should now be able to view the app in your browser at http://localhost:4200.