# chap10-board-and-tools
11장 bundler(webpack) 적용

webpack 번들러를 적용하여 개발 서버를 띄우고 빌드하는 방법을 알아보는 단계입니다.

> 편의를 위해 모든 예제에서 개발 IDE는 VS Code를 사용한다고 가정합니다.

## 실행 방법

### 의존성 설치
```sh
npm ci
// or
npm install
```
### 개발 서버 실행

```sh
npm run serve
```

### 빌드
1. 개발 모드 빌드
```sh
build:dev
```
2. 프로덕션 모드 빌드
```sh
build:prod
```