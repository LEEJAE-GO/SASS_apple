# SASS_apple

### SASS(SCSS)

* CSS 전처리기 입니다. (CSS가 동작하기 전에 사용하는 기능으로, CSS의 확장입니다.)
* 웹에서는 CSS만 동작합니다.
* 전처리기로는 직접 동작시킬 수 없기 때문에, 우선 전처리기로 코딩 후 CSS로 다시 컴파일해서 동작시키는 것 입니다. (컴파일 하기 위해서는 컴파일러가 필요함.)

### 컴파일러

Extensions: `Live Sass Compiler` 

설치 후, `scss` 코드 추가 후 `Watch Sass` 클릭. Watching 이 돌아갈 때는 저장시 자동 컴파일

### 컴파일러 사용시 불편사항
1. 불필요한 map 파일이 생성됨.
2. css 파일이 강제 expanded 됨.

### 컴파일러 불편사항 해결방법
1. Settings 에 들어가서 `Live Sass Compiler` 로 들어가서 `Generate Map` 의 settings.json 으로 들어가서 `"liveSassCompile.settings.generateMap": false` 이 내용을 추가해줍니다. 기존에 있을시 값을 바꾸거나 새로 재저장. (map 파일이 생기지 않음.)

2. `Formats` 으로 들어가서 `"format": "compact"` 을 추가해줍니다. 기존에는 `expanded` 로 되어있을 것임.

### 설치

`npm install sass -g`