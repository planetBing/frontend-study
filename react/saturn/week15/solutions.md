1.

- UI: 상호작용이 가능한 모든 요소의 현재 값. 다크/라이트 모드, input 등
- URL: 예시로 https://www.airbnb.co.kr/rooms/34113796?adults=2
  → roomId=34113796, adults=2 가 상태
- 폼: 로딩 중, 제출됐는지, 접근 불가능한지, 값이 유효한지
- 서버에서 가져온 값

2.

- 단점: 코드의 양이 많아지고 수고로워짐
- 장점: 데이터의 흐름은 모두 액션이라는 한 방향으로 줄어들기 때문에 데이터 흐름을 추적하기 쉽고 코드 이해가 쉬워짐

3.

- Redux: 글로벌 상태 객체
- React-query: HTTP 요청에 특화된 상태 관리 라이브러리
- Recoil: 전역 상태 관리 패러다임에서 벗어나 개발자가 원하는 만큼의 상태를 지역적으로 관리하는 것을 가능하게 만들었음