# vue-practice

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup
package.json 정보 로드(gradle, maven 업데이트와 유사)
```sh
npm install
```

### Compile and Hot-Reload for Development
프론트 개발 서버 실행 명령
```sh
npm run dev
```

### Compile and Minify for Production
운영 파일 빌드 명령
```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)
ESLint 변경시 실행 필요
```sh
npm run lint
```

### Test db server load
mock api 를 위한 서버 실행 명령
```sh
npm run db
```

### VScode extension 설치
```sh
ESLint
HTML CSS Support
HTML to CSS autocompletion
Live Server, Prettier
Vue Language Features (Volar)
Vue VSCode Snippets
```

### VScode ESLint 설정하기

- vscode에서 'Ctrl' + ',' 눌러서 탭을 띄웁니다.
- 탭에서 '확장>ESLint>settings.json' 을 클릭
- settings.json에 아래 항목을 추가하고 npm run lint를 실행합니다

```json
    "eslint.validate": [


        "javascript",
        "javascriptreact",
        "typescript",
        "typescriptreact",
        "html",
        "vue",
        "markdown"
    ],
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "editor.tabSize": 2,
```
