## Typescript 설치

$ npm install -g typescript

## Typescript 버전 확인

$ npx tsc -v

## Typescript init

$ npx tsc --init

## package.json 생성

$ npm init -y

## 필수 패키지 설치

$ npm install --save-dev ts-node
$ npm i express typescript @types/express
$ npm i -D nodemon ts-node

## package.json script 설정

```
"scripts": {
    "start": "nodemon app",
    "start:dev": "nodemon --watch \"*.ts\" --exec \"ts-node\" app.ts",
    "build": "tsc --build",
    "clean": "tsc --build --clean",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```
