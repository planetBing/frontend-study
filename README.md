# 코드스쿼드 2024 웹 프론트엔드 스터디

## 스터디 진행방식
- 각자 매주 수요일까지 스터디 범위에 해당하는 책의 내용을 읽어옵니다.
- 스터디 범위 안에서 4~5개의 퀴즈를 만들고, 그에 대한 퀴즈의 답변을 준비합니다.
- 준비한 문제와 답변을 각자의 원격 저장소에 저장 후 스터디 시간 한시간 전까지 **Pull Request** 요청을 합니다.
- 2명씩 짝지어 각자 준비해온 퀴즈를 풀어본 뒤, 다 같이 이야기해 볼만한 퀴즈를 모아서 스터디 참여인원 전원이 해당 퀴즈에 대해 토론하고 이야기합니다.

## Pull Request 진행방식
1. 해당 프로젝트를 `fork` 합니다.
2. `fork`한 원격 저장소에 새로운 브랜치를 생성합니다.
3. 생성한 브랜치에 아래 폴더구조를 참고하여 문제와 답변을 저장합니다.
4. 매주 문제와 답변을 저장하고 `Pull Request`를 요청합니다.
5. 요청한 `Pull Request`를 모두 merge 한 후, 스터디를 진행합니다.

* `Pull Request` 를 요청하는 방법은 [링크](https://github.com/woowacourse/woowacourse-docs/tree/main/precourse#7-%EB%B3%B8%EC%9D%B8-%EC%9B%90%EA%B2%A9-%EC%A0%80%EC%9E%A5%EC%86%8C%EC%97%90-%EC%98%AC%EB%A6%AC%EA%B8%B0)를 참고합니다.

## 폴더구조
```
${topic}/${nickname}/${week_name}/
```

- 문제 저장 예시) `javascript/schnee/week1/questions.md`
- 답변 저장 예시) `javascript/schnee/week1/solutions.md`

## Git Commit 컨벤션

| 태그 | 설명 |
| ------------- |:-------------:|
| docs | 문서 내용 변경 |

<!-- 예제 코드가 필요한 경우가 생기면 추후에 추가 
| feat | 새로운 기능 추가 |
| fix | 버그 수정 |
| docs | 문서 내용 변경 |
| style | 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 등 |
| refactor | 코드 리팩토링 |
| test | 테스트 코드 작성 |
| chore | 빌드, 패키지 매니저 설정 등 |
-->

각자의 원격 저장소에 저장을 할 때, 위 Git Commit 컨벤션을 참고하여 커밋을 작성합니다.

## 주제

| Week                 | JavaScript (Woody)                                                                                                 | 주제 (JavaScript)                                                                                   | React (Woody)                                                                                              | 주제 (React)                                                                                                                                                                                                                                                                                                        |
| -------------------- | ------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Week 1 (2024/03/06)  | [Week 1 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week1/questions.md) | ▣ 4장: 변수와 상수 <br> ▣ 6장: 데이터 타입                                                          |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 2 (2024/03/13)  | [Week 2 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week2/questions.md) | ▣ 23장: 실행 컨텍스트                                                                               |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 3 (2024/03/19)  | [Week 3 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week3/questions.md) | ▣ 24장: 클로저                                                                                      |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 4 (2024/03/26)  | [Week 4 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week4/questions.md) | ▣ 12장: 함수                                                                                        |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 5 (2024/04/02)  | [Week 5 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week5/questions.md) | ▣ 22장: this                                                                                        |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 6 (2024/04/09)  | [Week 6 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week6/questions.md) | ▣ 40장: event                                                                                       |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 7 (2024/04/16)  | [Week 7 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week7/questions.md) | ▣ 45장: 프로미스                                                                                    |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 8 (2024/04/23)  | [Week 8 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week8/questions.md) | ▣ 38장: 브라우저의 렌더링 과정 <br> ▣ 42장: 비동기 프로그래밍 <br> ▣ 46장: 제너레이터와 async/await |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 9 (2024/04/30)  | [Week 9 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week9/questions.md) | ▣ 41장: 타이머 <br> ▣ 43장: Ajax <br> ▣ 44장: REST API                                              |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 10 (2024/05/08) |                                                                                                                    |                                                                                                     | [Week 10 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week10/questions.md) | ▣ 2.3장: 클래스 컴포넌트와 함수 컴포넌트 <br> ▣ 2.4장: 렌더링은 어떻게 일어나는가?                                                                                                                                                                                                                                  |
| Week 11 (2024/05/16) |                                                                                                                    |                                                                                                     | [Week 11 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week11/questions.md) | ▣ 2.2장: 가상 DOM과 리액트 파이버                                                                                                                                                                                                                                                                                   |
| Week 12 (2024/05/22) |                                                                                                                    |                                                                                                     | [Week 12 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week12/questions.md) | ▣ 3.1장: 리액트의 모든 훅 파헤치기 - 1                                                                                                                                                                                                                                                                              |
| Week 13 (2024/06/05) |                                                                                                                    |                                                                                                     | [Week 13 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week13/questions.md) | ▣ 3.1장: 리액트의 모든 훅 파헤치기 - 2                                                                                                                                                                                                                                                                              |
| Week 14 (2024/06/12) |                                                                                                                    |                                                                                                     | [Week 14 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week14/questions.md) | ▣ 3.2장: 사용자 정의 훅과 고차 컴포넌트                                                                                                                                                                                                                                                                             |
| Week 15 (2024/06/19) |                                                                                                                    |                                                                                                     | [Week 15 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week15/questions.md) | ▣ 5.1장: 상태 관리는 왜 필요한가?                                                                                                                                                                                                                                                                                   |
| Week 16 (2024/06/26) |                                                                                                                    |                                                                                                     | [Week 16 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week16/questions.md) | ▣ 5.2장: 리액트 훅으로 시작하는 상태 관리 <br> ▣ 5.2.1장: 가장 기본적인 방법: useState와 useReducer <br> ▣ 5.2.2장: 지역 상태의 한계를 벗어나보자: useState 의 상태를 바깥으로 분리하기                                                                                                                             |
| Week 17 (2024/07/03) | [Week 17 - JavaScript](https://github.com/minjeongHEO/frontend-study/blob/main/javascript/Woody/week17/summary.md) | ▣ 19.8장: 오버라이딩과 프로퍼티 섀도잉 <br> ▣ 19.9장: 프로토타입의 교체                             |                                                                                                            |                                                                                                                                                                                                                                                                                                                     |
| Week 18 (2024/07/10) |                                                                                                                    |                                                                                                     | [Week 18 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week18/questions.md) | ▣ 5.2.3장: useState와 Context동시에 사용해 보기 <br> ▣ 5.2.4장: 상태 관리 라이브러리 Recoil, Jotai, Zustand 살펴보기                                                                                                                                                                                                |
| Week 19 (2024/07/17) |                                                                                                                    |                                                                                                     | [Week 19 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week19/questions.md) | ▣ [State: 컴포넌트의 기억 저장소](https://ko.react.dev/learn/state-a-components-memory) <br> ▣ [렌더링 그리고 커밋](https://ko.react.dev/learn/render-and-commit) <br> ▣ [스냅샷으로서의 State](https://ko.react.dev/learn/state-as-a-snapshot)                                                                     |
| Week 20 (2024/07/26) |                                                                                                                    |                                                                                                     | [Week 20 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week20/questions.md) | ▣ [state 업데이트 큐](https://ko.react.dev/learn/queueing-a-series-of-state-updates) <br> ▣ [객체 State 업데이트하기](https://ko.react.dev/learn/updating-objects-in-state) <br> ▣ [배열 State 업데이트하기](https://ko.react.dev/learn/updating-arrays-in-state)                                                   |
| Week 21 (2024/07/31) |                                                                                                                    |                                                                                                     | [Week 21 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week21/questions.md) | ▣ [State를 사용해 Input 다루기](https://ko.react.dev/learn/reacting-to-input-with-state) <br> ▣ [State 구조 선택하기](https://ko.react.dev/learn/choosing-the-state-structure#don-t-mirror-props-in-state) <br> ▣ [컴포넌트 간 State 공유하기](https://ko.react.dev/learn/sharing-state-between-components)         |
| Week 22 (2024/08/05) |                                                                                                                    |                                                                                                     | [Week 22 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week22/questions.md) | ▣ [State를 보존하고 초기화하기](https://ko.react.dev/learn/preserving-and-resetting-state) <br> ▣ [state 로직을 reducer로 작성하기](https://ko.react.dev/learn/extracting-state-logic-into-a-reducer) <br> ▣ [Context를 사용해 데이터를 깊게 전달하기](https://ko.react.dev/learn/passing-data-deeply-with-context) |
| Week 23 (2024/08/15) |                                                                                                                    |                                                                                                     | [Week 23 - React](https://github.com/minjeongHEO/frontend-study/blob/main/react/Woody/week23/questions.md) | ▣ [Reducer와 Context로 앱 확장하기](https://ko.react.dev/learn/scaling-up-with-reducer-and-context) <br> ▣ [Ref로 값 참조하기](https://ko.react.dev/learn/referencing-values-with-refs) <br> ▣ [Ref로 DOM 조작하기](https://ko.react.dev/learn/manipulating-the-dom-with-refs) |

