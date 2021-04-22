```css
/* animation 속성 */

/*애니메이션이 바뀌는 지점 설정*/
@keyframes <animation-name 속성에 들어갈 이름> {
  from {
    /* 애니메이션 시작 시점의 스타일 */
  }
  
  to {
    /* 애니메이션 끝 시점의 스타일 */
  }
}


/* 애니메이션 이름 지정 */
animation-name: <@keyprames name> | none;


/* 애니메이션 실행 시간 설정 */
animation-duration: <시간>


/* 애니메이션 방향 지정 */
animation-direction: normal | alternate;
/* normal: 애니메이션이 끝나면 원래 위치로 돌아감.(기본 값) */
/* alternate: 애니메이션이 끝나면 왔던 방향으로 되돌아가면서 에니메이션을 실행 */


/* 반복 횟수 지정 */
animation-iteration-count: <숫자> | infinite;
/* <숫자>: 입력한 숫자만큼 반복. 기본 값은 1 */
/* infinite: 무한 반복. */
```
