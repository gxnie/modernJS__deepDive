# 📚 데이터 타입(data type)

## 📝 자바스크립트 원시타입과 객체타입

<img src="data%20type.png">

<br/>

## 📝 숫자 타입

자바스크립트는 `하나의 숫자 타입만 존재`

- ECMAScript 사양에 따르면, 숫자 타입은 `배정밀도 64비트 부동소수점 형식` 을 따른다. 즉 `모든 수를 실수(float)로 처리`한다.
- 숫자 타입은 추가적으로 세 가지 특별한 값도 표현할 수 있다.
  - `Infinity` : 양의 무한대
  - `-Infinity` : 음의 무한대
  - `NaN` : Not-a-Number, 산술 연산 불가

```javascript
// 숫자 타입의 세 가지 특별한 값
console.log(10 / 0); // Infinity
console.log(10 / -0); // -Infinity
console.log(1 * "String"); // NaN
```

<br/>

## 📝 문자열 타입

`문자열`은 텍스트 데이터를 나타내는데 사용한다.

- `작은따옴표('')`, `큰따옴표("")`, ` 백틱(``) `으로 택스트를 감싼다.
  - 가장 기본은 작은 따옴표 사용

<br/>

## 📝 템플릿 리터럴

### 💡 표현식 삽입

문자열은 문자열 연산자 `+`를 사용해 연결할 수 있다. 하지만 `템플릿 리터럴` 내에서는 `표현식 삽입`을 통해 간단히 문자열 삽입할 수 있다.

```javascript
var first = "Genie";
var last = "H";

// ES5: 문자열 연결
console.log("My name is " + first + " " + last + "."); // My name is Genie H.

// ES6: 표현식 삽입
console.log(`My name is ${first} ${last}.`);
```

<br/>

## 📝 불리언 타입

`불리언(boolean)`타입의 값은 논리적 참, 거짓을 나타내는 true와 false뿐이다.

```javascript
var foo = true;
console.log(foo); // ture

foo = false;
console.log(foo); // false
```

<br/>

## 📝 undefined 타입

<br/>

## 📝 null 타입

<br/>

## 📝 심벌 타입

<br/>

## 📝 객체 타입

자바스크립트는 `객체 기반의 언어`이며, 자바스크립트를 이루고 있는 거의 `모든 것이 객체`다.

> 객체 관련 내용은 이 후 챕터에서 다룰 예정
> <br/>

## 📝 데이터 타입 필요성

<br/>

## 📝 동적 타이핑

<br/>
