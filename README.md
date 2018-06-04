# angular-cli-electron
An Angular CLI project that supports Electron integration.

The way this project is structured, it is first an Angular project and second an Electron application. What this means is basically that the project has been setup initially using the Angular CLI and holds a child folder for Electron. Each of these folders contains a separate package.json and node_modules folder. The Angular project is built and output to "Electron/app" where Electron picks it up and serves it. To accomplish this requires the use of two terminals. 

Terminal one should point to the root directory of this project and run the command "npm run electron:start" to compile the Angular portion of the application. 

Terminal two should point to "root/electron" and should run the command "npm run start" (or "electron ."). 

## Standard Angular CLI commands are supported from the root directory as follows

### AngularCliBase
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.4.

### Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding
Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

### Running unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests
Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help
To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
