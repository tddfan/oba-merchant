# ObaMerchant

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).




---- Starting setup ----

sudo npm install -g @angular/cli@1.6.8 
ng v
new new oba-merchant
cd oba-merchant
npm install --save @angular/cdk@1.6.8  --(For angular 5)
npm install --save @angular/cdk@5.2.0
npm install --save @angular/animations@5.2.0
npm install --save hammerjs
npm install --save bootstrap

Add in angular-cli.json
       "../node_modules/bootstrap/dist/css/bootstrap-reboot.css",
        "../node_modules/bootstrap/dist/css/bootstrap-grid.css"

Add styles.css
@import "~@angular/material/prebuilt-themes/indigo-pink.css";