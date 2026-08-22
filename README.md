## scaffold - 루비온레일즈 프로젝트를 시작할 때 폴더 구조나 기본 코드 등 기초 뼈대를 자동으로 만들어주는 기능

```bash
rails generate scaffold Post title:string content:text
```

### Run local server

```bash
./bin/dev
```

http://127.0.0.1:3000/

## 전역 ERB 포멧팅 - prettier

```bash
gem install htmlbeautifier
```

전역으로 세팅 및 setting.json에 관련 코드를 추가해서 vs code에서 전역으로
사용할 수 있음.

```json
 "[erb]": {
    "editor.defaultFormatter": "aliariff.vscode-erb-beautify",
    "editor.formatOnSave": true
  }
```
