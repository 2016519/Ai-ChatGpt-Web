# ChatGpt-Web
AI智能提示前台

## Install
```shell
npm install
```
## Run
```shell
npm run serve
```
## Build
### Build for Production
```shell
npm run build
```
### Build for Staging
```shell
npm run build:staging
```
## Run Eslint
### Run without Fixing

- This operation will also run before git-commit.
```shell
npm run lint
```
### Run with Fixing
```shell
npm run lint:fix
```
## .env Description

- This project exposes environment variables on `process.env` object.
- Different modes (development/staging/production) correspond to different environment files (.env.*).
- .env file is always included, duplicate variables are overwritten by the specific mode file (.env.*).
