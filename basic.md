# JavaScript 기초 연습문제

두 수를 입력받아 큰 수를 반환하는 함수를 작성하세요.

---

세 수를 입력받아 그 곱이 양수이면 `true`, 음수이면 `false`, 둘 다 아니면 에러를 발생시키는 함수를 작성하세요.

---

세 수를 입력받아 큰 것부터 차례대로 출력하는 함수를 작성하세요.

---

어떤 수가 짝수인지 홀수인지 출력하는 함수를 작성하세요. 이를 이용해서, 1부터 20까지의 수가 각각 짝수인지 홀수인지 출력하는 함수를 작성하세요.

---

1부터 100까지의 수를 차례대로 출력하되, 자릿수에 3, 6, 9중 하나라도 포함되어 있으면 '짝!'을 대신 출력하는 함수를 작성하세요.

---

양의 정수를 입력받아, 다음과 같은 패턴의 출력을 하는 함수를 작성하세요.

1을 입력받은 경우:
```
*
```

3을 입력받은 경우:
```
*
* *
* * *
```

5를 입력받은 경우:
```
*
* *
* * *
* * * *
* * * * *
```

---

양의 정수를 입력받아, 다음과 같은 패턴의 출력을 하는 함수를 작성하세요.

1를 입력받은 경우:
```
*
```

3를 입력받은 경우:
```
  *
 * *
* * *
 * *
  *
```

5를 입력받은 경우:
```
    *
   * *
  * * *
 * * * *
* * * * *
 * * * *
  * * *
   * *
    *
```

---

두 수를 입력받아서, 두 수의 최대공약수를 반환하는 함수를 작성하세요. ([유클리드 호제법](https://ko.wikipedia.org/wiki/%EC%9C%A0%ED%81%B4%EB%A6%AC%EB%93%9C_%ED%98%B8%EC%A0%9C%EB%B2%95)을 참고하세요.)

---

100 이하의 자연수 중 3과 5의 공배수를 모두 출력하는 프로그램을 작성하세요.

---

양수를 입력받아 이 수를 반지름으로 하는 원의 넓이를 반환하는 함수를 작성하세요.

---

수 타입의 값만 들어있는 배열을 입력받아, 해당 배열을 오름차순 정렬하는 함수를 작성하세요. (`Array.prototype.sort`를 사용하지 않고 작성해보세요. [선택 정렬](https://ko.wikipedia.org/wiki/%EC%84%A0%ED%83%9D_%EC%A0%95%EB%A0%AC)을 참고하세요.)

---

문자열을 입력받아, 그 문자열의 모든 '부분 문자열'로 이루어진 배열을 반환하는 함수를 작성하세요.

예:

```
subString('햄버거');
// 결과: ['햄', '햄버', '햄버거', '버', '버거', '거']
```

---

문자열을 입력받아 그 문자열이 회문(palindrome)인지 판별하는 함수를 작성하세요. (회문이란, '토마토', 'Never odd or even'과 같이 뒤에서부터 읽어도 똑같이 읽히는 문자열을 말합니다.)

---

문자열을 입력받아, 각 단어의 첫 글자를 대문자로 바꾼 결과를 반환하는 함수를 작성하세요.

---

문자열을 입력받아, 대문자는 소문자로, 소문자는 대문자로 바꾼 결과를 반환하는 함수를 작성하세요.

---

문자열을 입력받아, 문자열 안에 들어있는 단어 중 가장 긴 단어를 반환하는 함수를 작성하세요.

---

문자열을 입력받아, 문자열 안에 들어있는 모든 모음(a, e, i, o, u)의 갯수를 반환하는 함수를 작성하세요.

---

양수를 입력받아, 그 수의 모든 약수를 출력하는 함수를 작성하세요.

---

양수를 입력받아, 그 수가 소수인지 아닌지를 판별하는 함수를 작성하세요.

---

'금액'과 '동전의 종류가 들어있는 배열'를 입력받아, 최소한의 동전을 사용해서 금액을 맞출 수 있는 방법을 출력하는 함수를 작성하세요.

예:

```
coins(163, [100, 50, 10, 5, 1]);
// 출력
100
50
10
1
1
1
```

---

문자열을 입력받아, 해당 문자열에서 중복된 문자가 제거된 새로운 문자열을 반환하는 함수를 작성하세요.

예:
```
remoteDuplicates('tomato'); -> 'toma'
remoteDuplicates('bartender'); -> 'bartend'
```

---

문자열을 입력받아, 해당 문자열에 포함된 문자의 종류와 갯수를 나타내는 객체를 반환하는 함수를 작성하세요.

예:

```
countChar('tomato'); -> {t: 2, o: 2, m: 1, a: 1}
```

---

양수를 입력받아, 그 수만큼의 길이를 갖는 임의의 문자열을 반환하는 함수를 작성하세요.

---

배열을 입력받아, 배열의 요소 중 두 개를 선택하는 조합을 모두 포함하는 배열을 작성하세요.

예:

```
combination([1, 2, 3]); -> [[1, 2], [1, 3], [2, 3]]
```
---

숫자로만 이루어진 문자열을 입력받아, 연속된 두 짝수 사이에 하이픈(-)을 끼워넣은 문자열을 반환하는 함수를 작성하세요.

예:
insertHyphen('437027423'); -> '4370-274-23'

---

수 타입의 값으로만 이루어진 배열을 입력받아, 그 값들의 합을 구하는 함수를 작성하세요.

---

수 타입의 값으로만 이루어진 배열을 입력받아, 그 값들의 표준편차를 구하는 함수를 작성하세요.

---

배열을 입력받아, 중복된 요소가 제거된 새 배열을 반환하는 함수를 작성하세요.

---

배열을 입력받아, 요소들의 순서를 뒤섞은 새 배열을 반환하는 함수를 작성하세요.

---

수 타입의 값으로만 이루어진 두 배열을 입력받아, 다음과 같이 동작하는 함수를 작성하세요.
- 두 배열의 같은 자리에 있는 요소를 더한 결과가 새 배열의 요소가 됩니다.
- 만약 입력받은 두 배열의 길이가 갖지 않다면, 긴 배열에 있는 요소를 새 배열의 같은 위치에 포함시키세요.

예:
```
addArray([1, 2, 3], [4, 5, 6, 7]) -> [5, 7, 9, 7]
```

---

배열을 입력받아, falsy인 요소가 제거된 새 배열을 반환하는 함수를 작성하세요.

---

두 정수 `start`, `end`를 입력받아, `start`부터 `end`까지의 모든 정수를 배열로 반환하는 함수를 작성하세요.

예:
```
range(3, 6); -> [3, 4, 5, 6]
```

---

두 정수를 입력받아, 두 정수 사이의 임의의 정수를 반환하는 함수를 작성하세요.

---

2진수를 표현하는 문자열을 입력받아, 그 문자열이 나타내는 수 타입의 값을 반환하는 함수를 작성하세요. (`parseInt`를 사용하지 말고 작성해보세요.)

예:
```
convertBinary('1101'); -> 13
```
---

정수를 입력받아, 5 단위로 올림한 수를 반환하는 함수를 작성하세요.

예:
```
ceilBy5(32); -> 35
ceilBy5(37); -> 40
```

---

세 수 `min`, `max`, `input`을 입력받아, 다음과 같이 동작하는 함수를 작성하세요.
- `min`보다 `input`이 작으면, `min`을 반환합니다.
- `max`보다 `input`이 크면, `max`를 반환합니다.
- 아니면 `input`을 반환합니다.

예:
```
limit(3, 7, 5); -> 5
limit(3, 7, 11); -> 7
limit(3, 7, 0); -> 0
```

---

임의의 HTML 색상 코드를 반환하는 함수를 작성하세요.

---

자연수 `n`을 입력받아, `n`번째 피보나치 수를 반환하는 함수를 작성하세요.

---

`String.prototype.split`과 똑같이 동작하는 함수를 작성하세요.

예:
```
split('Hello World'); -> ['Hello', 'World']
split('let,const,var', ',') -> ['let', 'const', 'var']
```
---

자연수 `n`과 문자열 `s`를 입력받아, `s`의 첫 `n`개의 문자만으로 이루어진 새 문자열을 반환하는 함수를 작성하세요.

---

이메일 주소를 입력받아, 아이디 부분을 별표(`*`)로 가린 새 문자열을 반환하는 함수를 작성하세요.

---

Camel case의 문자열을 입력받아, snake case로 바꾸어주는 함수를 작성하세요.

---

Snake case의 문자열을 입력받아, camel case로 바꾸어주는 함수를 작성하세요.

---

문자열 `s`와 자연수 `n`을 입력받아, 만약 `s`의 길이가 `n`보다 작으면 `s`의 왼쪽에 공백으로 추가해서 길이가 `n`이 되게 만든 후 반환하고, 아니면 `s`를 그대로 반환하는 함수를 작성해보세요.

예:
```
leftPad('hello', 8); -> '   hello'
leftPad('hello', 3); -> 'hello'
```

---

두 문자열을 입력받아, 대소문자를 구분하지 않고(case insensitive) 두 문자열이 동일한지를 반환하는 함수를 작성하세요.

예:
```
insensitiveEqual('hello', 'hello'); -> true
insensitiveEqual('hello', 'Hello'); -> true
insensitiveEqual('hello', 'world'); -> false
```