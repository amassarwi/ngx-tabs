# NGX-TABS - Angular6 tabs app

This project generated by `angular-cli` - angular version: `6.0.3`

## Instruction

* Please install [angular cli](https://github.com/angular/angular-cli) globally to be able to run the app locally
  * Both the CLI and generated project have dependencies that require Node 8.9 or higher, together with NPM 5.5.1 or higher.
* Run `npm install`
* Run `ng serve` to serve the app on `http://localhost:4200`

## What's in the box

* Angular6.x app, running with angular/cli.
* Added .scss support.
* Added angular/material library.
* Using Rxjs library, faking a server calls to get data.

## Randomly select default tab

There are 3 tabs, one of the requirment is:
* Random tab selection on every page load
To achieve this I used: `return (new Date()).getTime() % 3;` - which returns the current timestamp % 3 (which is always 0, 1 or 2)

----------

# NgxTabs - NG-CLI DEFAULT README FILE

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).



