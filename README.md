# Angular 웹 애플리케이션

Angular 프레임워크를 사용하여 간단한 웹 애플리케이션을 구현하고, 로컬 서버(http://localhost:5000/data)에서 데이터를 가져오는 방법을 설명하겠습니다. 이 예제에서는 Angular의 HTTP 클라이언트 모듈을 사용하여 비동기적으로 데이터를 가져오고, 이를 표시하는 방법을 다룹니다.

# Angular 프로젝트 설정

## Angular CLI 설치 : 

Angular 프로젝트를 빠르게 시작하기 위해 Angular CLI(Command Line Interface)를 설치합니다.

> npm install -g @angular/cli

## 새 프로젝트 생성 : 

my-angular-app이라는 이름의 새 프로젝트를 생성합니다.

> ng new my-angular-app

이 과정에서 라우팅 사용 여부와 스타일 시트 형식에 대한 질문을 받을 수 있습니다. 간단한 예제를 위해 라우팅은 'No', 스타일 시트는 'CSS'를 선택하세요.

## 프로젝트 디렉토리로 이동:

> cd my-angular-app

------------------

# MyAngularApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.6.

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
