# AngularReddit

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.5.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## In this project i used Semantic library and to install it follow:

-npm install ng2-semantic-ui --save

Next include the Semantic UI CSS file in your index.html (you can include a manually compiled one if you use themes):
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.2.13/semantic.min.css">

Once installed you need to import the main module:
import {SuiModule} from 'ng2-semantic-ui';

Finally import the main module into your application module:
import {SuiModule} from 'ng2-semantic-ui';

Note if you're using SystemJS, add the following to your systemjs.config.js file:
var config = {
    ...
    map: {
        ...
        'ng2-semantic-ui': 'npm:ng2-semantic-ui/bundles/ng2-semantic-ui.umd.min.js'
    }
}

Now you're good to go! Good luck coding :)
