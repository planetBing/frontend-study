# 3.1장 (2024.06.05(수))

## 문제

1. useImperativeHandle에 대해 설명
2. useLayoutEffect에 대해 설명
3. 훅에는 규칙이 존재한다.

- 최상위에서만 훅을 호출해야한다, 반복문 조건문, 중첩된 함수 내에서 훅을 실행할 수 없다.
- 훅을 호출할 수 있는 것은 리액트 함수 컴포넌트, 사용자 정의 훅 두가지 뿐이다.
- 이 중 첫번째 규칙의 이유는?