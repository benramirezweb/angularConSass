# Angular with SASS project

## AngularConSass

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.

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

## Create Angular project with SASS

To create a new Angular project, that uses SASS to generate use the follow command:

`ng new my-sassy-app --style=scss`

You also can use this commands to use SCSS or LESS:

`ng new my-sassy-app --style=scss`
`ng new my-sassy-app --style=less`

## Changes in .angular-cli.json

The `.angular-cli.json` file has been changed in this line:

`"styles": ["sass/styles.sass"],`

To update the SASS file path.

## SASS files architecture

There is a sass folder that contains the main SASS file called `styles.sass`.

This file import the others two SASS files called `_variables.sass` and `_mixins.sass` that contains all the dinamic values to create the styles of the project.