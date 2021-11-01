# Vue vs React 비교

## 1. 문법과 자유도

- React는 기존 자바스크립트 코드 외에 jsx라는 문법을 이용해 html을 표현할 수도 있어 자바스크립트를 알고 있다면 Vue보다 더 편리하다. Vue는 과거의 웹 스크립트 작성 방식과 유사한 templete을 사용하며 Vue 문법(v-if, v-for 등)을 익혀야 한다.

## 2. Size

- React는 라우팅과 같은 특정 기능을 구현하기 위해서 서드파티 라이브러리가 필요하고 Vue는 standard한 기능이 포함된 프로젝트로 React에 비해 조금 더 가볍다. 하지만 둘 다 충분히 작기 때문에 소규모 개발에도 상관이 없다.

## 3. 성능

- React와 Vue 모두 Virtual DOM을 사용하지만, Vue의 Virtual DOM이 더 좋은 성능과 안정성을 가졌다. 그럼에도 전체적으로 보면 둘의 성능 차이는 몇 밀리 초에 불과해 유사하다고 할 수 있다.

## 4. 웹과 모바일

- React는 React Native라는 프레임워크를 이용하여 기본 iOS와 안드로이드 앱을 작성할 수 있지만, Vue는 Alibaba Group에서 만든 Weex를 이용해야 하는데 이는 React Native에 비해 덜 성숙하고 개발단계에 있다.

## 5. 생태계(Community Support)

- Github의 start 수는 Vue가 10k 정도 앞서지만, 실사용률을 비교할 수 있는 npm 다운로드 수를 보면 React가 Vue에 비해 약 4배정도 높고, 스택오버플로우 개발자 Survey에서도 React 35.9% vs Vue 17.3%로 React가 더 인기 있는 것으로 조사됐다.
