## 클로저
1. 다음 중 클로저라고 하지 않는 경우를 모두 선택하고, 클로저라고 할 수 있도록 수정하세요.
```
ㄱ. 상위 스코프의 어떤 식별자도 참조하지 않는다.

ㄴ. 외부 함수보다 생명 주기가 짧다.

ㄷ. 상위 스크프의 2개 이상의 식별자 중에서 하나만 참조한다.
```


2. 다음 설명에 맞는 단어를 쓰시오.
```
외부에 공개할 필요가 없는 구현의 일부를 외부에 공개되지 않도록 감추어 
적절치 못한 접근으로부터 객체의 상태가 변경되는 것을 방지해 정보를 보호하고,
결합도를 낮추는 효과가 있다.
```


3. 다음 코드의 결과가 `0, 1, 2` 가 나오도록 수정하시오.
```js
var funcs = [];

for (var i = 0; i < 3; i++) {
    funcs[i] = function () {return i;};
}

for (var j = 0; j < funcs.length; j++) {
    console.log(funcs[j]());
}
```
