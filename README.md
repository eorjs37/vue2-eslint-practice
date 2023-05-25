# vue2-eslint-practice

# vscode에서 eslint 사용하기
## settings.json에서 아래 코드 추가
```javascript
{
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "html",
        "typescriptreact",
        "vue"
    ],
    "editor.formatOnSave": true,
}
```