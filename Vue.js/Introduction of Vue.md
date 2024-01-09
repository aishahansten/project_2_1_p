# Client side frameworks
- 클라이언트 측에서 UI와 상호작용을 개발하기 위해 사용되는 JS 기반 프레임워크
- 백엔드 - data
- 프론트엔드 - 화면 구성(HTML, CSS, Ajax, JS)
- cdn 으로 하다가 Vite로 구성
- Vanilla JS 로만 하면 복잡하니까 기본적으로 기능을 해주는 프레임워크 (Angular, Vue.js, React)
- 동적인 대화형 웹 애플리키에션 구축
- Native App(모바일, 플랫폼 종속적), Web App(브라우저에서 실행), Hybrid App
- 웹에서 하는 일이 많아지고(보는 것 - 하는 곳) , 다루는 데이터가 많아지며 상태 변경마다 UI업데이트해야 됨 Client-side framework가 필요하다

# SPA
- Single Page Application 
- 선언적 렌더링 : 틀을 만들어두고 쏘아주는 데이터를 화면에 나타나게 함 . 화면이 변함.
- 가장 처음에 JS를 서버에서 클라이언트로 로드해야 됨.  
- 동작을 하면 서버에서 REST API로 Ajax(비동기적 방식) 통신하면 JSON 으로 data가 넘어옴
- 틀에 data를 뿌림

- 틀을 모두 다르게 하려면 router와 module 사용해서 /list url 입력 시 list.js 가 나타나게 함.
- Client side rendering

# Vue
[Vue3공식문서](https://ko.vuejs.org/guide/introduction)

1. CDN , Application Instance 생성
- const {createApp} = Vue;  
  - vue 가 가진 인스턴스를 생성 
  - Vue 는 cdn 의 .js 파일의 객체이다, const 는 상수, {}는 구조분해할당(destructure), createApp 은 .js 파일의 객체인데 ...args spread operator 여러 인자를 가져갈 수 있음
  .js에서 export 넘겨줌 - 우리는 import 로 모듈로 사용함

  

