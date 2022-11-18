# JS 과제입니다.

## JavaScript의 자료형과 JavaScript만의 특성은 무엇일까 ? 

- 느슨한 타입(loosely typed)의 동적(dynamic) 언어

- JavaScript 형변환

- ==, ===

- 느슨한 타입(loosely typed)의 동적(dynamic) 언어의 문제점은 무엇이고 보완할 수 있는 방법에는 무엇이 있을지 생각해보세요.

- undefined와 null의 미세한 차이들을 비교해보세요.

## JavaScript 객체와 불변성이란 ? 

- 기본형 데이터와 참조형 데이터

- JavaScript 형변환

- 불변 객체를 만드는 방법

- 얕은 복사와 깊은 복사

## 호이스팅과 TDZ는 무엇일까 ?

- 스코프, 호이스팅, TDZ

- 함수 선언문과 함수 표현식에서 호이스팅 방식의 차이

- 여러분이 많이 작성해온 let, const, var, function 이 어떤 원리로 실행되는지 알 수 있어요.

- 실행 컨텍스트와 콜 스택

- 스코프 체인, 변수 은닉화

## 실습 과제

- 콘솔에 찍힐 b 값을 예상해보고, 어디에서 선언된 “b”가 몇번째 라인에서 호출한 console.log에 찍혔는지, 왜 그런지 설명해보세요.
주석을 풀어보고 오류가 난다면 왜 오류가 나는 지 설명하고 오류를 수정해보세요.

```javascript
let b = 1;

function hi () {

const a = 1;

let b = 100;

b++;

console.log(a,b);

}

//console.log(a);

console.log(b);

hi();

console.log(b);
```

- 두 값이 다른 이유를 설명해보세요.

```javascript
1 == "1";
1 === "1";
```
