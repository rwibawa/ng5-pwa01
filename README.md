# Ng5Pwa01
Learn [Angular Service Workers](https://angular.io/guide/service-worker-getting-started).

## 1. Setup
```sh
$ npm i -g @angular/cli@latest
$ ng v

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/


Angular CLI: 6.0.1
Node: 8.9.4
OS: win32 x64
Angular:
...

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.6.1
@angular-devkit/core         0.6.1
@angular-devkit/schematics   0.6.1
@schematics/angular          0.6.1
@schematics/update           0.6.1
rxjs                         6.1.0
typescript                   2.7.2


$ ng new ng5-pwa01
$ cd ng5-pwa01
$ ng add --help
$ ng add @angular/pwa --project ng5-pwa01
Installing packages for tooling via npm.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.3 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ @angular/pwa@0.6.1
added 2 packages in 20.578s
Installed packages for tooling via npm.
CREATE ngsw-config.json (392 bytes)
CREATE src/assets/icons/icon-128x128.png (1253 bytes)
CREATE src/assets/icons/icon-144x144.png (1394 bytes)
CREATE src/assets/icons/icon-152x152.png (1427 bytes)
CREATE src/assets/icons/icon-192x192.png (1790 bytes)
CREATE src/assets/icons/icon-384x384.png (3557 bytes)
CREATE src/assets/icons/icon-512x512.png (5008 bytes)
CREATE src/assets/icons/icon-72x72.png (792 bytes)
CREATE src/assets/icons/icon-96x96.png (958 bytes)
CREATE src/manifest.json (1075 bytes)
UPDATE angular.json (3535 bytes)
UPDATE package.json (1384 bytes)
UPDATE src/app/app.module.ts (526 bytes)
UPDATE src/index.html (386 bytes)

$ ng build --prod
$ cd dist/ng5-pwa01
$ http-server -p 8092
```

Open [http://localhost:8092](http://localhost:8092).

## Initialization
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.1.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
