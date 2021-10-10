### SASS(SCSS) 선택자

* `&`: 가상 선택자로써, 부모 선택자를 참조 할 수 있음.

```scss
a { color: red;
  // &.active == a:active
  &.active { color: blue; }
}
```

* css 의 자식 선택자와 동일하게 사용가능 (ex: `ul > li`)
* css 의 자손 선택자와 동일하게 사용가능 (ex: `li a`)
* `last-child` 를 이용하여 마지막 요소의 속도를 가져올 수 있음.
