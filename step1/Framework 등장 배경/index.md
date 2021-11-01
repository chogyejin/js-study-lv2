# Javascript Framework 등장 배경

- 과거 웹사이트는 MPA(Multiple Page Application) 형태로 동작해 페이지 내에 있는 요소에 대한 반응으로 완전한 페이지를 만들어 서버에서 전송했었다.

- 한 페이지에 대한 용량의 증가로 인해 SPA(Single Page Application)이 등장했다.

  - SPA : 페이지 하나에서 필요한 요소들에 대해서만 부분적으로 로딩을 하게 되고 페이지 이동 간에 깜빡거림이 없어서 UX 간섭을 줄인다. 개발의 측면에선 코드 재사용과 생산성 향상이 있다.

- Virtual DOM을 이용하여 SPA를 쉽고 확장성 있게 구현하도록 돕는 Javascript Framework로 Vue, React, Angular 등이 등장하게 되었다.

  - Virtual DOM : 실제 DOM에 적용되기 전에 Virtual DOM에 적용시키고, 결과를 비교 후 전달한다. 이를 통해 연산의 양을 줄여 성능을 높인다.

- SPA는 주로 CSR(Client Side Rendering)로 동작하는데, 초기 렌더링 속도, 검색 엔진 최적화와 같은 단점을 해결하기 위해 CSR과 SSR(Server Side Rendering)의 장점을 섞어 쉽게 이용할 수 있는 Framework로 Vue의 Nuxt.js, React의 Next.js가 있다.
