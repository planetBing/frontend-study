# 5.2 리액트 훅으로 시작하는 상태관리 ~ 5.2.2

1. 리렌더링이 일어나기 위한 작업을 설명해주세요.

_답_

```
useState, useReducer의 반환값 중 두번째 인수가 호출된다.
부모 컴포넌트가 리렌더링되거나 해당 컴포넌트가 다시 실행되어야 한다.
```

2. useState로 컴포넌트의 리렌더링을 실행해 최신값을 가져오는 방법은 해당 컴포넌트 자체에서만 유효한 전략이다.
   렌더링이 자연스럽게 일어나려면 필요한 조건을 설명해주세요.

_답_

```
컴포넌트 외부 어딘가에 상태를 두고 여러 컴포넌트가 같이 쓸 수 있어야한다.

외부에 있는 상태를 사용하는 컴포넌트는 상태의 변화를 알아챌 수 있어야 하고, 상태가 변화될 때마다 리렌더링이 일어나서 컴포넌트를 최신 상태값 기준으로 렌더링해야한다. 이 상태 감지는 상태를 참조하는 모든 컴포넌트에서 동일하게 작동해야 한다.

상태가 원시값이 아닌 객체인 경우에 그 객체에 내가 감지하지 않는 값이 변한다 하더라도 리렌더링이 발생해서는 안된다. 단순히 값을 참조하는 컴포넌트에서는 리렌더링을 일으켜서는 안된다는 뜻이다.
```

3. useSubscription 훅에 대해 설명해주세요.

_답_

````
외부에서 관리되는 값에 대한 변경을 추적, 사용하고, 리렌더링까지 수행되게 한다.
```
````