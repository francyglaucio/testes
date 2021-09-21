# Calculadora

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.2.

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






sonar-scanner.bat -D"sonar.projectKey=local" -D"sonar.sources=." -D"sonar.host.url=http://localhost:9000" -D"sonar.login=fd7f870a4d5bb2af6f0f491644423d6a786b93a1" -D"sonar.typescript.lcov.reportPaths=./coverage/lcov.info" -D"sonar.exclusions=**/*.stories.ts, **/*.spec.ts, **/dtos/**/*, **/dto/**/*, **/entity/**/*, **/__mock__/**/*, **/__mocks__/**/*, **/cypress/**/*, **/e2e/**/*, **/environments/**/*, **/*.routing.module.ts, **/*.module.ts, **/main.ts, **/*.js" -D"sonar.typescript.tslint.configPath=./tslint.json"
