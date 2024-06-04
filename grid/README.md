# Grid

Grid는 그리드 레이아웃을 만들기 위한 2차원 시스템이다. 이를 통해 웹 페이지의 레이아웃을 쉽게 구성할 수 있다.

## 사용 방법

- `display: grid;`를 사용하여 그리드 레이아웃 선언

```css
.container {
  display: grid;
}
```

- `grid-template-columns`와 `grid-template-rows`를 사용하여 그리드의 행과 열을 정의

```css
.container {
  display: grid;
  grid-template-columns: 100px 100px 100px;
  grid-template-rows: 100px 100px 100px;
}
```

- `grid-column`과 `grid-row`를 사용하여 그리드 아이템의 위치를 지정

```css
.container {
  grid-column: 1 / 3;
  grid-row: 1 / 3;
}
```
