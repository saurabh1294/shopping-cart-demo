# Angular shopping cart demo
A simple shopping cart module using angular

# Known issues
Code quality can be improved by usage of services and getting product data from
a service instead of specifying static product list and quantity in the beginning. 


Add/Remove functionality and unit tests pending due to shortage of time.


Reactive forms and RxJS can be used for more robust design. 


The responsive design (HTML markup) can be reused by tweaking it and using bootstrap 4
reorder classes for mobile view, instead of replicating the markup for mobile view.

# What works

The desktop and mobile responsive view as given in the problem statement

When a product quantity is changed, it changes all over the UI and also
the subtotal as well as final total gets updated accordingly.




## To start the application
Clone this repo and within the shopping-cart-demo directory, run npm install to install
node dependencies. Run npm start to get the application up and running at 
http://localhost:4200.


** Below are auto-generated README content **
# ShoppingCartApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.0.

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
