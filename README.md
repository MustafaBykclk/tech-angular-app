## Angular & Typescript
[Angular GitHub](https://github.com/MustafaBykclk/tech-angular-app)



## Git kurulumu
https://git-scm.com/downloads/win
git config --global user.name "MustafaBykclk"
git config --global user.email "mustafabykclk95@gmail.com"

-- 

## Node JS 
https://nodejs.org/en/download/package-manager

--

## Version
git -v 
npm -v 

## Npm Komutları
npm init
npm init -y
npm list 
npm list -g
npm list -g --depth=0

npm root
npm root -g

npm config list-l

--

## Angular Kurulum 
npm install -g typescript 
npm install -g @angular/cli 
npm uninstall -g @angular/cli 
ng version
ng v 
ng --help 

--

## Angular Başlat
ng new tech-angular-app
cd tech-angular-app 
ng serve
ng serve --open 
ng serve --port 999 --open 
http://localhost:9999
curl localhost:9999 

--

## Angular CLI Hazır Bileşenler
ng generate component loginComponent
ng g v login
ng g pipe loginPipeline
ng g service loginService
ng g module loginModule
ng g directive loginDirective
ng g interface loginInterface
ng g enum loginEnum

## 3.Parti Uygulamalar Ekle

### Bootstrap
"styles": [
              "src/styles.css",
              "node_modules/font-awesome/css/font-awesome.css",
              "node_modules/bootstrap/dist/css/bootstrap.min.css"
            ],
            "scripts": [

              "node_modules/bootstrap/dist/js/bootstrap.min.js",
              "node_modules/jquery/dist/css/jquery.min.js"
            ],

### jQuerry
'''sh
Terminal => npm i jquery
angular.json =>  ,
            "scripts": [
              "node_modules/jquery/dist/css/jquery.min.js"
            ], 
    <div class="alert alert-primary" role="alert"> Bootstrap Çalıştı </div>

    
            


'''










# TechAngularApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.9.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
