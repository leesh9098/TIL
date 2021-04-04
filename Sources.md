### JavaScript
- - -
```javascript
//클릭 시 드롭다운 JS 코드
//HTML에서 사용하고자 하는 부분에 onclick="함수이름()" 속성 사용
function 함수이름() {
  document.getElementById("적용할 ID값").classList.toggle("show");
}

window.onclick = function(event) {
  if (!event.target.matches('.드롭다운 버튼의 클래스 이름')) {
    let dropdowns = document.getElementsByClassName("드롭다운 했을 때 나타날 부분의 클래스 이름");
    let i;
    for (i=0; i<dropdowns.length; i++) {
      let openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
```
- - -
- [slider](JS/slider.js)
- [materilize.min.js](JS/materilize.min.js)
- [jquery](JS/jquery.js)
- [slideshow](JS/slideshow.js)
```javascript
//slideshow.js 코드
$(document).ready(function() {
  $('.html에서 적용할 요소의 클래스 이름').slider();
});

//html에서 materilize.min.js, jquery.js, slideshow.js를 호출한다.
//slider.js에는 indicator, indicator-item이라는 클래스가 있기 때문에 CSS에서 이 클래스들의 스타일을 지정해주어야 한다.
//활성화 된 indicator-item에는 active 클래스가 적용되기때문에 그에대한 스타일도 지정해주어야 한다.
```
