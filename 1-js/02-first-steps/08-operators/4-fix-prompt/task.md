importance: 5

---

# 덧셈 고치기

아래 코드는 사용자에게 숫자 2개를 입력받은 다음 그 합을 보여줍니다.

그런데 의도한 대로 예시가 동작하지 않습니다. 프롬프트 창에 세팅한 기본값을 수정하지 않은 경우 덧셈의 결과는 `12`가 됩니다.

왜 그럴까요? 예시가 제대로 동작하도록 코드를 수정해 보세요. 결과는 `3`이 되어야 합니다.

```js run
let a = prompt("덧셈할 첫 번째 숫자를 입력해주세요.", 1);
let b = prompt("덧셈할 두 번째 숫자를 입력해주세요.", 2);

alert(a + b); // 12
```