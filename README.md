# Steps to create the project
* yarn create nx-workspace jb-sample --preset=empty --cli=angular
* yarn ng add @nrwl/angular --defaults
* yarn ng generate @nrwl/angular:app jb-example --style=scss
* yarn ng generate @nrwl/angular:lib material-lib
* add material libs by hand, since nrwl nx does not support ng add
* yarn add @angular/material@10.2.3 @angular/cdk@10.2.3 @angular/animations@10.2.3 hammerjs
