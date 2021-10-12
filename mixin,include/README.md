### SASS(SCSS) @mixin, @include

* 가장 많이 사용되는 기능 중 하나, 재사용, DRY(반복하지 않는) 컴포넌트의 핵심.
* 무언가를 만드는데, 반복적인 옵션이 들어가는 경우 사용합니다.
* 선언 시 `@mixin`, 적용 시 `@include`를 사용한다.
* 매개 변수를 받아서 사용할 수 있습니다. (함수처럼..)

### 예시

```scss
@mixin test {
  width: 100px; height: 100px; border: 1px solid red;
}
// 인수가 없을시에는 test 라고만 써두댐.
div { @include test(); }
```

### 정리

이렇게 생각하면 편할 거 같음. <br/>
`$: 변수, mixin: 함수, include: 함수 호출`