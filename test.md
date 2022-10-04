<!-- # Hello
## HI
### 소제목
#### 작은 제목

---

- 목록 1
- 목록 2

1. 숫자목록1
2. 숫자목록2 -->

## transform

요소에 변형을 준다.

---

<!-- 코드블록 -->

```html
<h1>Hello HTML!</h1>
```

`translate` : 요소를 x축,y축,z축 방향으로 이동시킨다.

```css
.box {
  width: 100px;
  height: 100px;

  /* 
        요소를 x축방향으로 50px이동시킨다.
        음수일 경우 왼쪽으로 이동한다.
    */
  transform: translate(50px);
}
```

| 값           | 설명                       |
| ------------ | -------------------------- |
| translate()  | x,y축 방향으로 이동시킨다. |
| translateX() | x축 방향으로 이동시킨다.   |

**볼드**