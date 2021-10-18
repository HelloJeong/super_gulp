# Super Gulp

Learn Gulp by building an awesome development environment

## gulpfile.js

- `gulpfile.js` 에서는 import가 먹히지 않기 때문에 `gulpfile.babel.js`로 변경

## Pug Task(`gulp-pug, del`)

- .pipe()를 통해 연결해갈 수 있음
- del()을 통해 폴더 및 파일의 삭제를 할 수 있음
- series() 속에 series 변수를 넣을 수 있음(배열로)

## Webserver Task(`gulp-webserver`)

- 동시에 실행하고 싶다면 parallel()

## Image Task(`gulp-image`)

- 용량이 크다면 매번 시간이 걸릴 수 있으니 상황에 맞춰서 watch.

## SCSS Task(`node-sass, gulp-sass, gulp-autoprefixer, gulp-csso`)

- import 방식이 안되므로 `const sass = require("gulp-sass")(require("node-sass"));`

- 버전에 따라 `browsers: ["last 2 versions"]`를 autop({...}) 또는 package.json에 넣어야 한다.

## JS Task(`gulp-bro, babelify uglifyify`)

## deploy(`gulp-gh-pages`)
