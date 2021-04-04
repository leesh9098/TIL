### JavaScript
- - -
```javascript
//클릭 시 드롭다운 JS 코드
//HTML에서 사용하고자 하는 부분에 onclick="함수이름()" 속성 사용
function 함수이름() {
  document.getElementById("적용할 ID값").classList.toggle("show");
}

window.onclick = function(event) {
  if (!event.target.matches('.드롭다운버튼의 클래스이름')) {
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
- [슬라이드 쇼 JS](slider.js)
- [materilize.min.js](materilize.min.js)
- [jquery](jquery.js)
```javascript
//슬라이드 쇼 JS코드
$(document).ready(function() {
  $('.적용할요소의 클래스 이름').slider();
});
```
