# React란?

- UI(사용자가 보기 위한 화면)를 building하기 위한 자바스크립트 라이브러리
- SPA 기반의 프론트엔드 개발 프레임워크로, 컴포넌트 단위의 독립적인 블록을 이용한 개발방법을 사용.
- 비슷한 프레임워크 : AngularJS, VueJS

## SPA(Single Page Application) 아키텍쳐

- 하나의 페이지로 이루어진 애플리케이션으로, MPA와는 상반된 개념
- MPA의 문제점 </br>

  1. 좋아요 눌러도 웹사이트가 재로딩되는 문제 발생
  2. 리랜더링이 되어야 하는 상황이 많아지므로 유저 불편도 급증</br>
     => 하나의 페이지 내부에서 독립적으로 수정이 가능해야함!

- SPA의 특징 및 장점 </br>

  1. 딱 하나의 페이지로 구성
  2. 서버에 1회 리소스 요청
  3. 그 이후에는 필요시에만 데이터를 받아와 기존 페이지를 수정해주는 방식 사용 </br>
     => 자연스러운 UX 구현이 가능해짐!

- SPA의 단점 </br>

  1. SEO에 취약하다! </br>
     => 이를 보완해주는 것으로 최근 next.js 많이 사용함!

- SPA 프레임워크의 종류 </br>

  1. ReactJS </br>

     1. 페이스북이 만들고 유지보수 중
     2. 선발주자이기 때문에 막강한 커뮤니티와 자료 보유 중

  2. VueJS </br>

     1. 아직 성장하고 있음
     2. 후발주자라 마켓쉐어 중임

  3. AngularJS </br>
     1. 안정적인 프레임워크
     2. 배우기도 어렵고 무겁다! 그래서 나온지 오래되었지만 점유율이 낮은 편.

## React

- 장점 </br>
  1. NPM trands에서 꾸준히 사용량 상위를 차지
  2. React Native와의 상생, VR에서도 활용이 가능함!
  3. 잘 갖추어진 커뮤니티
  4. 어떤 웹 사이트에 변경이 일어나도 벽돌처럼 쌓는 형식으로 구조를 짜기 때문에 컴포넌트 단위로 변경사항 반영
