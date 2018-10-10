# DockerAngularDemo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.5.

## How to deploy to AWS elastic beanstalk as docker image?
- $ ng build --prod --aot // will create a dist/ folder under output folder
- zip the content of the output/ folder as 'output.zip'
- go to your AWS elastic beanstalk and create a new application
- choose docker and upload the zip file
- once done, you app will be running in AWS elastic beanstalk as a docker container

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
