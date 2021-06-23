
종종 들리는 오픈소스 블로그들의 테마가 바뀌었길래 찾아보았다.

대표적으로 kevin 님의 https://sbt-devoops.kevinly.dev/ 사이트여서 느꼈는데, docusaurus 를 사용하였더라. 

한번 사용해보려고 하니, 이 정적 웹사이트 생성기는 facebook의 리액트 기반이었다.

리액트에 대해 조금 거부감이 있는데 (jsx 와 같은), 소개  페이지에서 경쟁사를 소개하는 챕터에서 vue 기반의 다른 툴을 찾을수있었따. https://docusaurus.io/docs#comparison-with-other-tools

찾아낸 것은 vuepress 라고 하는 wordpress 의 아류작 느낌의 툴인데, 이를 한번 써보는 프로젝트이다.

## Project Quick Guide

https://vuepress.vuejs.org/guide/getting-started.html#quick-start 의 문서를 기반으로 시작한다.

프로젝트 workspace 로 이동한다.

> cd docs

디펜던시 인스톨 

> npm i

> npm install -D vuepress

로컬 서버 실행

> npm run dev

브라우저에서 접근

> http://localhost:8080


## 후기

여러가지 장점이 있었다

- vue 프레임워크 공식 문서와 동일한 깔끔한 테마

그리고 단점도 있었다

- 네비게이션 구성을 직접 손으로 구성해주어야 한다. config.js 참고

