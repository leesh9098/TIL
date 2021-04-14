```javascript
// array.prototype.concat();
// array에서 concat과 push의 차이

//push: 기존 배열에 값을 추가해서 원본을 변경
const animal = ["lion", "tiger"];
const animalpush = animal;
animalpush.push("cat", "dog");
// animal.push(["cat", "dog"]); // 이렇게 하면 Item이 아닌 Array가 들어가므로 주의
console.log(animal); // ["lion", "tiger", "cat", "dog"]
console.log(animalpush); // ["lion", "tiger", "cat", "dog"]
console.log(Object.is(animal, animalpush)); // true

//concat: 기존 배열은 유지되고 새로운 배열에 값을 추가해서 새로운 배열을 리턴
const animal = ["lion", "tiger"];
const animalconcat = animal.concat("cat", "dog"); // Combines two or more arrays.
console.log(animal); // ["lion", "tiger"]
console.log(animalconcat); // ["lion", "tiger", "cat", "dog"]
console.log(Object.is(animal, animalconcat)); // false
```
