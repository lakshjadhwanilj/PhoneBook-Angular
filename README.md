# PhoneBook

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.1.1.

## Steps Involved
Steps to create an Angular Project - 

1. ng new Phone-Book
2. Add fontawesome to index.html
3. Clear the app.component.html file and write Hello World for now
4. Add CDN of BootStrap in index.html OR Install BootStrap & add styles and scripts to Angular.json <br>
   Bootstrap import => npm install --save bootstrap <br>
   jQuery import    => npm install --save jquery@latest
5. Add json commands => npm install json-server || json-server --watch db.json
6. Create component => (home, addContact) => ng g c <componentName>
7. Create service => Contact => ng g s Contact
8. In service => import HttpClient => add get methods
9. Add imports to app.module.ts => HttpClientModule, FormsModule, ReactiveFormsModule
10. Work on home component => ts and html files
11. Add this in tsconfig.json => "strictPropertyInitialization": false,
12. Add routes in app-routing.module.ts. Check if routes are working.
13. Add Delete Function
14. Added editContact component and routes
15. Added Sorting code
16. Added Search box, install => npm i ng2-search-filter AND npm i ng2-filter-pipe
17. In app.module.ts => import Ng2SearchPipeModule

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
