ex04 : 어플리케이션 번들링

1. webpack은 작게 분리된 많은 모듈(js, css, images) 들의 의존성을 분석해서 하나의 js파일로 묶어주는 도구
2. 하나의 js파일을 번들이라하고 묶는 작업을 번들링이라고 한다.
3. 번들링은 단순히 모듈들을 하나의 파일로 묶는 작업만을 의미하지는 않는다. -> 빌드작업도 한다.
4. 빌드작업
    - linting (ESLing, 문법체크) 작업
    - 도큐먼트 작업
    - 테스트 (Mocha, Jest) 작업
    - 난독화 / 압축 (uglyfy) 작업
5. JS뿐만 아니라 다양한 에셋 (css, images, font) 들도 모듈로 취급한다.
6. 설치
   $ npm i -D webpack webpack-cli
   $ npm .\node_modules\.bin\webpack --version
   $ npx webpack --version 