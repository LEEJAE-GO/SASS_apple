### 조건문

* 조건에 따른 결과를 true/false 로 나눠 처리 합니다.
* 우리가 아는 조건문과 비슷하게 사용합니다. (`@if, @else`)

```scss
// radius 가 true, false 인 경우 조건문
@if $radius {
  border-radius: $h / 2;
} @else {
  border: 1px solid red;
}

// 응용
@if $x == 50% and $y == 50% {
  transform: translate(-$x, -$y);
} @else if $x == 50% {
  transform: translateX(-$x);
} @else {
  transform: translateY(-$y);
}
```