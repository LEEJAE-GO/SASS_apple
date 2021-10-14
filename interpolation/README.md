### Interpolation(보간법)

* `#{}` 형태로 사용한다.
* 가장 기본적인 내용으로, 꼭 알아둬야 할 내용입니다.
* 변수를 통해 클래스 적용 `@mixin` 등의 문법을 사용할 때 주로 사용합니다.

#### 예시

```scss
$test: main;

.#{ $test } {
  border: 1px solid black;
}
```