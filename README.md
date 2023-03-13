# Enviroment

primeiro copia o environment.ts e dá um nome para ele:  enviroment.name_environment.ts
vai em angular.json e em "configurations" cola:

    "name_environment": {
        "fileReplacements": [
            {
                "replace": "src/environments/environment.ts",
                "with": "src/environments/environment.name_environment.ts"
            }
        ]
    }

em "serve" adicionar em "configurations":
    "nome_de_inicialização": { //pode ser o proprio nome da pasta
      "browserTarget": "nome-do-projeto:build:name_enviroment"
    }
    
por fim dar o seguinte comando:

`ng serve --configuration=name_environment` -> muda o environment;


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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
# environment
