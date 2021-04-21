```css
/* transition 속성 */

transition-property:
/*
transition을 적용할 속성을 지정
- all: 요소의 모든 속성에 적용(기본값)
- none: 적용시키지 않음
- 속성이름(ex. width, height): 지정한 요소의 속성에만 transition을 적용
*/


transition-duration:
/*
transition의 진행 시간을 지정
요소들에 각각 진행 시간을 지정할 수 있다. 진행 시간을 한 개만 입력하면 지정한 모든 요소에 동일한 진행 시간이 지정된다.
*/


transition-timing-function:
/*
transition 속도 곡선을 지정
- linear: 처음부터 끝까지 같은 속도로 진행
- ease: 천천히 → 점점 빠르게 → 천천히(기본값)
- ease-in: 처음만 천천히
- ease-out: 끝날때 천천히
- ease-in-out: 천천히 → 보통 → 천천히
- cubic-bezier(n,n,n,n): 베지에 함수를 직접 정의. n은 0~1사이의 값(하단 링크 참조)
*/


transition-delay:
/*
transition의 시작 지연 시간을 지정
*/


transition:
/*
transition의 모든 속성을 한번에 표기하는 방식
*/
```
cubic-bezier속성 미리보기 링크
https://cubic-bezier.com/#.17,.67,.83,.67
