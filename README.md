axios                       : Promise 기반 웹 요청 클라이언트
classnames                  : CSS Module 과 조건부 className 을 설정 하는 것을 도와주는 라이브러리
sass-loader, node-sass      : 프로젝트에서 Sass 를 사용하기 위하여 필요한 도구
include-media, open-color   : Sass 라이브러리 (반응형 디자인, 색상 팔레트)
better-react-spinkit        : 로딩 시 보여줄 컴포넌트
react-icons                 : SVG 형태의 리액트 컴포넌트 모음 라이브러리
moemnt                      : 날짜 관련 라이브러리

* 컴퍼넌트 구조
ComponentName.js
ComponentName.scss
index.js    
: 컴퍼넌트를 불러올때 src/components/ComponentName/ComponentName 이런 방식이 아닌 src/components/ComponentName 형식으로 불러올 수 있도록 컴퍼넌트를 불러와 바로 내보내주는 파일
ex) export { default } from './CompoenetName';

*****
https://velopert.com/3503
