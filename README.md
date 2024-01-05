# project_2_1_personal
SSAFY 2학기 관통 프로젝트 개인 기록용 저장소 

**vue.js-framework-development-setting**
---
vue.js 프레임워크 프론트엔드 개발 가이드

**목적**
---
관통 프로젝트 과정에서 프론트엔드 개발 환경 설정을 통일해 프로젝트 품질을 높이기 위한 가이드

**개발환경설정**
---

[Public Documents](https://married-spot-253.notion.site/5fef18bbcd4b467fb8c7ed819250e1e8?v=d7d02b0f89684f7e8e5650572eb693e2)

* Visual Studio Code(IDE) ⚡️
    * [VsCode 설치 + python extension + jupyter ](https://married-spot-253.notion.site/VSCode-28f6593036214f48b21c96c1e521c097)

* Git ⚡️
    * [Git 설치](https://married-spot-253.notion.site/Git-26f16cff585a4aa783e9f938969427f7)

* VSCode Git bash 연결 설정 ⚡️
    * [VSCode with Git bash](https://married-spot-253.notion.site/VSCode-with-Git-bash-3b0748e8df4a4b52b80851b9bc9b195f)

* WEB 사전 준비 ⚡️
    * [VSCode extention](https://married-spot-253.notion.site/Web-6173461751e34f8598f83e307f6b887d)

* Vue.js 사전 준비 ⚡️
    * [extention, chrome tool 설치](https://married-spot-253.notion.site/Vue-js-026a610188c347a980224a848fa63bf0)

* Node.js 설치(14.17.0) ⚡️
    - ~~20.10.0~~
    - 최신 LTS 버전으로 실행시 라이브러리 호환 오류 발생해서 14.17.0 버전으로 재설치해야 될 것 같습니다.
    - https://nodejs.org/download/release/v14.17.0/  `[node-v14.17.0-x64.msi](https://nodejs.org/download/release/v14.17.0/node-v14.17.0-x64.msi)` 설치``
    - [https://married-spot-253.notion.site/Node-js-1925d5119f4f4cf3b5c17002025c05d7](https://www.notion.so/1925d5119f4f4cf3b5c17002025c05d7?pvs=21)
    
    - **명세 기준은 14.17.0**
    ([https://codezone.tistory.com/entry/electon-03-NodeJs-개발에-유용한-nvm-간단히-알아보고-갑시다](https://codezone.tistory.com/entry/electon-03-NodeJs-%EA%B0%9C%EB%B0%9C%EC%97%90-%EC%9C%A0%EC%9A%A9%ED%95%9C-nvm-%EA%B0%84%EB%8B%A8%ED%9E%88-%EC%95%8C%EC%95%84%EB%B3%B4%EA%B3%A0-%EA%B0%91%EC%8B%9C%EB%8B%A4))
    → **nvm 컨트롤러**로 node.js 버전 여러개를 설치해놓고 돌려가면서 사용할 수 있습니다

* Python 설치(3.9.13) ⚡️
    * [Python 다운로드](https://married-spot-253.notion.site/Python-e23d9e3b9ce9411c87adeae095a7ad19)

* Github 설정 변경 ⚡️
    * [master 브랜치 설정](https://married-spot-253.notion.site/Github-3c44da8bd65344a684db03d5c7aa1bef)

* project/lab ssafy 계정 설정 ⚡️
    * [project/lab ssafy](https://married-spot-253.notion.site/project-lab-ssafy-e491530361454fee8b4bcd8b9220dcaf)

* 기획
    * [기획의 중요성](https://married-spot-253.notion.site/5fef18bbcd4b467fb8c7ed819250e1e8?v=a733fb954f0f4845b1ef97b92ddab480&p=3495e25e79334199b5ea139c22c673ff&pm=s)

* 프로젝트
    * [참고사이트](https://married-spot-253.notion.site/5fef18bbcd4b467fb8c7ed819250e1e8?v=a733fb954f0f4845b1ef97b92ddab480&p=aaf370a743d34b968df3d10e816c2089&pm=s)

* 배포
    * [서버(Django)배포](https://married-spot-253.notion.site/5fef18bbcd4b467fb8c7ed819250e1e8?v=a733fb954f0f4845b1ef97b92ddab480&p=e87256d14a8d42819b0ee339484e279d&pm=s)
    * [클라이언트(Vue)배포](https://married-spot-253.notion.site/5fef18bbcd4b467fb8c7ed819250e1e8?v=a733fb954f0f4845b1ef97b92ddab480&p=d0afd9bd038140fc90e335cb4ea3a522&pm=s)

* Jupyter Notebook 설치 안함
    * [단축키](https://married-spot-253.notion.site/5fef18bbcd4b467fb8c7ed819250e1e8?v=5c2082730c34488f940bcbd8be0db1b9&p=59a8aa6559e74b418bc48897e8701645&pm=s)
    * [설치](https://married-spot-253.notion.site/5fef18bbcd4b467fb8c7ed819250e1e8?v=cfce45284a274ef2a3a14a01a4074988&p=63999a09c2874ce096e2e125e2b77c84&pm=s)

    
**개발환경**
---
* 프론트엔드 개발 IDE : Visual Studio Code
    * extension 설치 용이
    * spring boot 테스트/개발 가능
* Node.js
    * NPM(Node Package Manager) 통해 모듈 세팅
* Chrome Vue.js devtools 
    * Chrome 브라우저 Vue 개발자 도구


**웹기술: WebRTC 화상회의 서비스(음성/영상/P2P 서비스)**
---

**스켈레톤 코드**
- 반응형 웹 서비스
- Vue.js
- Spring

**배경** 
- 비대면 서비스의 필요성이 대두됨으로 인해 각종 행사와 그룹 커뮤니케이션이 온라인 화상으로 이루어지는 경우가 많아지고 있다. 그룹으로 화상을 공유하는 기술은 다양한 쓰임새를 갖는다. 

**정의**
- "WebRTC 화상 회의" 는 그룹 커뮤니케이션을 위한 그룹 화상과 그룹 채팅 등의 기능이 있는 서비스를 말힌다. 
- Web Real-Time Communication의 약자로 웹에서 별다른 소프트웨어 없이 카메라, 마이크 등을 활용해서 실시간 커뮤니케이션을 제공해주는 기술이다.
- 화상통화, 화상공유 구현할 수 있는 오픈소스
- 비디오, 음성, 일반 데이터가 **P2P 방식**으로 피어간에 전송되도록 지원
- JavaScript API로 제공
    * [WebRTC API 공식문서](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)
- [출처](https://gh402.tistory.com/38)
- 장점: Latency가 짧다, 별도 플러그인/미디어 송출 관련 소프트웨어를 설치할 필요가 없다
- 단점: Cross-browsing problem(Internet Explorer 지원 안됨, 호환성 문제),
STUN/TURN 서버 필요(P2P 통신을 위해서는 사용자의 IP 주소를 알아야 된다. 하지만 대부분 사용자는 방화벽을 사용하고 다른 네트워크상에서 연결이 이루어지기 위해서는 STUN/TURN 서버가 꼭 필요) 
- data streams, STUN/TURN servers, signaling, JSEP, ICE, SIP, SDP, NAT, UDP/TCP, network socket 등
- [용어정리](https://gh402.tistory.com/45)

- **data streams** : 연결지향통신에서 연속적으로 흘러나오는 데이터들의 흐름, 데이터의 양이 한정되어 있지 않고 끊임없이 생성되고 변하는 데이터의 흐름
- **NAT(Network Address Translation) : 
- WebRTC의 통신원리 : Peer to Peer 통신
    - **P2P**: 클라이언트/서버의 개념 없이 동등한 노드로 구성되어 데이터를 주고받는 통신 형태
