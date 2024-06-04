# Flex

Flex는 요소들을 정렬하기 위한 방법 중 하나입니다. Flex는 요소들을 부모 요소 안에서 정렬할 수 있게 해주는 CSS3의 속성입니다.

## 사용방법

- 부모 요소에 `display: flex;`를 적용합니다.

```css
.container {
  display: flex;
}
```

## Flex 속성

- flex-direction: row | row-reverse | column | column-reverse;

- flex-wrap: wrap | nowrap

- justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly

- align-items: stretch | flex-start | flex-end | center | baseline

### Flex items 속성

- flex-grow: 0 | 1 | <number> : 기본값은 0, 1로 설정하면 남은 공간을 모두 차지합니다.

- flex-shrink: 0 | 1 | <number>: 기본값은 1, 0으로 설정하면 요소가 줄어들지 않습니다.

- flex-basis: auto | <length>: 기본값은 auto, flex-grow와 flex-shrink를 계산하기 위한 기본 크기를 지정합니다.

- order: <integer>

- align-self: start | center | end | stretch
