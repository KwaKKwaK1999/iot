## HW1

### 예제 1-1 
변수 `a`를 선언했지만 초기화하지 않아 `undefined` 값을 가진다.

### 예제 1-2
변수 `a`를 선언하고 `'abc'`를 할당하거나, 선언과 동시에 할당할 수 있다.

### 예제 1-3
변수 `a`는 `'abc'`에 `'def'`를 더한 값으로 재할당되며, 변수 `b`와 `c`는 초기값이 동일하지만, 이후 `b`는 `7`로 재할당된다.

### 예제 1-4
객체 `obj1`을 선언하고, 프로퍼티 `a`에 `1`, `b`에 `'bbb'`를 할당한다.

### 예제 1-5
객체 `obj1`을 선언하고, 프로퍼티 `a`에 `1`, `b`에 `'bbb'`를 할당한 후, 프로퍼티 `a`를 `2`로 재할당한다.

### 예제 1-6
객체 `obj`를 선언하고, 프로퍼티 `x`에 `3`, `arr`에 `[3, 4, 5]` 배열을 할당한다.

### 예제 1-7
기본 타입 변수 `a`의 값을 `b`에 복사하고, 객체 `obj1`을 선언하여 `obj2`가 같은 객체를 참조하도록 할당한다.

### 예제 1-8
기본 타입 변수의 값을 변경하면 독립적으로 변하고, 객체 내 프로퍼티의 값을 변경하면 참조된 다른 변수에도 영향을 미친다.

### 예제 1-9
기본 타입 변수의 값을 변경하면 독립적으로 변하고, 객체 변수에 새로운 객체를 할당하면 원래 참조하던 객체와의 연결이 끊긴다.

### 예제 1-10
함수 내에서 객체를 변경하더라도 원본 객체와 함수 내의 객체는 같은 것을 가리키므로, 객체 변수 간의 비교는 동등하지만 식별자는 다르다.

### 예제 1-11
새로운 객체를 반환하여 원본 객체와의 연결을 끊으므로, 객체 변수 간의 비교는 동등하지 않다.

### 예제 1-12
`copyObject` 함수는 주어진 객체를 복사하여 새로운 객체를 반환한다.

### 예제 1-13
`copyObject` 함수를 사용하여 `user` 객체를 복사한 후, 새로운 객체인 `user2`에 변경사항을 적용하였다. 따라서, `user`와 `user2`는 서로 다른 객체를 참조하게 되며, `user2`의 변경은 `user`에 영향을 주지 않는다.

### 예제 1-14
`copyObject` 함수를 사용하여 `user` 객체를 복사한 후, `user`와 `user2` 객체의 일부 속성을 변경하였다.

### 예제 1-15
`copyObject` 함수를 사용하여 `user` 객체를 복사한 후, `user.urls` 객체도 복사하여 `user2`에 새로운 객체를 할당했다.

### 예제 1-16
`copyObjectDeep` 함수는 주어진 객체를 깊은 복사하여 반환한다.

### 예제 1-17
`copyObjectDeep` 함수는 깊은 복사를 수행한다. 따라서 원본 객체의 변경이 복사된 객체에 영향을 주지 않는다.

### 예제 1-18
`copyObjectViaJSON` 함수는 객체를 JSON 문자열로 변환한 후 다시 JSON 파싱하여 복사본을 생성한다. 이 방법은 일반적으로 깊은 복사를 수행하지만, 함수나 프로토타입 체인과 같은 특수한 속성들은 복사되지 않는다.

### 예제 1-19
`a`는 값이 없어 `undefined`, `obj.a`는 `1`, `obj.b`와 `b`는 `undefined`, `func()`는 반환값이 없어 `undefined`이다.

### 예제 1-20
`arr1`은 길이가 3인 빈 배열이고, `arr2`는 요소가 없는 길이가 3인 배열이며, `arr3`은 요소가 모두 undefined인 배열이다.

### 예제 1-21
배열 메서드를 사용하여 두 배열을 조작하고 결과를 비교했을 때, 결과가 서로 다르게 나타났다.

### 예제 1-22
null 변수의 타입은 "object"이며, undefined와 null을 비교했을 때, 둘 다 동등하다고 나타났지만 일치는 하지 않는다.

### 예제 2-1
함수 `outer` 내부에서 함수 `inner`를 호출하고, `inner` 함수 내에서 변수 `a`를 선언하고 출력했을 때, 먼저 함수 내의 지역 변수가 우선순위를 갖고 출력된 후, 함수 `outer`에서 변수 `a`가 출력됐다. 함수 외부에서 변수 `a`를 출력하면 전역 변수가 출력된다.

### 예제 2-2
함수 내에서 변수 및 매개변수는 호이스팅되며, 초기화되지 않은 변수는 `undefined`로 간주된다.

### 예제 2-3
함수 내에서 변수는 호이스팅되며, 중복 선언되어도 초기화는 한 번만 이루어진다.

### 예제 2-4
함수 내에서 변수는 호이스팅되며, 중복 선언되어도 초기화는 한 번만 이루어지며, 중복된 변수들은 마지막 값으로 할당된다.

### 예제 2-5
함수 내에서 변수와 함수 모두 호이스팅되지만, 변수와 함수의 이름이 중복될 때 함수 선언이 변수 선언을 덮어쓴다.

### 예제 2-6
함수 내부에서 변수와 함수 선언이 모두 호이스팅되지만, 함수 선언이 변수 선언을 덮어쓴다.

### 예제 2-7
함수 `a` 내에서 변수 `b`를 먼저 선언하고, 그 다음에 함수 `b`를 할당했을 때, 변수와 함수 선언이 호이스팅되지만, 변수 할당은 호이스팅되지 않는다.

### 예제 2-8
함수 표현식에서 기명 함수를 사용하면, 함수 내부에서만 함수명을 사용할 수 있고 외부에서는 사용할 수 없다.

### 예제 2-9
함수 선언문 `sum`은 호이스팅되어 함수가 호출되기 전에 사용될 수 있지만, 변수 할당된 함수 표현식 `multiply`는 호이스팅되지 않아 호출되기 전에는 사용할 수 없다.

### 예제 2-10
함수 선언문은 전체가 호이스팅되지만, 변수는 선언부만 호이스팅된다.

### 예제 2-11
함수 `sum`은 두 번 선언되었지만, 호출 시에는 나중에 정의된 함수가 사용된다.

### 예제 2-12
함수 `sum`은 두 번 정의되었고, 첫 번째 정의가 변수 `sum`에 할당된 함수를 덮어씌웠다. 첫 번째 호출 시에는 함수가 정의되지 않았기 때문에 에러가 발생했고, 두 번째 호출은 문자열을 반환하는 함수가 사용되었다.

### 예제 2-13
함수 `outer` 내에서 함수 `inner`를 호출하고, 그 안에서 변수 `a`를 선언하고 출력했을 때, 먼저 함수 내의 지역 변수가 우선순위를 갖고 출력된 후, 함수 `outer`에서 변수 `a`가 출력됐다. 함수 외부에서 변수 `a`를 출력하면 전역 변수가 출력된다.

### 예제 2-14
함수 `outer` 내에서 함수 `inner`를 정의하고 호출하며, `inner` 함수 내에서는 함수 자체를 콘솔에 출력한다.

### 예제 2-15
함수 `outer` 내에서 함수 `inner`를 정의하고 호출하며, `inner` 함수 내에서는 외부 함수 `outer`의 지역 변수 `b`를 출력하고 함수 자체를 콘솔에 출력한다.

### 예제 2-16
함수 `outer` 내에서 함수 `inner`를 정의하고 호출하며, `inner` 함수 내에서는 외부 함수 `outer`의 지역 변수 `b`를 출력하고 디버거를 호출한다.

### 예제 3-1
브라우저 환경에서 `this`와 `window`가 같은 전역 객체를 참조함을 확인했다.

### 예제 3-2
Node.js 환경에서 `this`와 `global`이 같은 전역 객체를 참조함을 확인했다.

### 예제 3-3
브라우저 환경에서 선언된 변수 `a`가 전역 객체 `window`와 `this`에 속해 있음을 확인했다.

### 예제 3-4
브라우저 환경에서 전역 객체 `window`와 `this`의 프로퍼티로 변수 `a`와 `b`가 접근 및 수정되었음을 확인했다.

### 예제 3-5
브라우저 환경에서 `var`로 선언된 전역 변수는 `delete`로 삭제할 수 없으나, 직접 `window` 객체에 할당된 프로퍼티는 삭제할 수 있음을 확인했다.

### 예제 3-6
함수가 일반적으로 호출될 때는 전역 객체를 `this`로 참조하고, 객체의 메소드로 호출될 때는 해당 객체를 `this`로 참조함을 확인했다.

### 예제 3-7
객체 내부에서 메소드가 직접 호출되거나 대괄호 표기법으로 호출될 때, `this`는 해당 객체를 참조함을 확인했다.

### 예제 3-8
객체의 메소드가 직접 호출되거나 대괄호 표기법으로 호출될 때, `this`는 메소드가 정의된 현재 객체를 참조함을 확인했다.

### 예제 3-9
함수 내에서 정의된 내부 함수는 기본적으로 전역 객체를 `this`로 참조하지만, 다른 객체에 할당되어 메소드로 호출될 경우 그 객체를 `this`로 참조하게 된다.

### 예제 3-10
객체 메소드에서 일반 함수로 호출된 내부 함수는 전역 객체를 `this`로 참조하며, 'self' 변수를 사용하여 내부 함수에서 외부 함수의 `this`를 참조할 수 있음을 확인했다.

### 예제 3-11
객체의 메소드에서 화살표 함수로 정의된 내부 함수는 외부 함수와 같은 `this` 즉, 호출한 객체를 참조함을 확인했다.

### 예제 3-12
브라우저 환경에서 `setTimeout`과 배열의 `forEach` 메소드 내의 일반 함수는 전역 객체 `window`를 `this`로 참조하며, 이벤트 핸들러 함수에서는 해당 핸들러가 부착된 요소를 `this`로 참조함을 확인했다.

### 예제 3-13
생성자 함수 `Cat`을 사용하여 `choco`와 `nabi` 두 객체를 생성하고, 각 객체는 고유의 이름과 나이 속성을 가지며 공통적으로 '야옹'이라는 출력함을 확인했다.

### 예제 3-14
일반적으로 호출된 함수는 전역 객체를 `this`로 참조하며, `call` 메소드를 사용하여 호출된 함수는 지정된 객체 `{ x: 1 }`를 `this`로 참조하고 인자를 순서대로 전달받음을 확인했다.

### 예제 3-15
객체의 메소드가 직접 호출될 때는 해당 객체의 프로퍼티 `a`를 참조하며, `call` 메소드를 사용하여 다른 객체로 `this`를 지정할 경우 지정된 객체의 프로퍼티 `a`와 주어진 인자들을 사용함을 확인했다.

### 예제 3-16
apply 메소드를 사용하여 함수나 메소드를 호출할 때, 첫 번째 인자로 전달한 객체가 this로 설정되며, 두 번째 인자로 전달한 배열은 함수나 메소드의 매개변수로 전달됨을 확인했다.

### 예제 3-17
객체에 push 메소드를 호출하여 배열처럼 동작하도록 설정하고, 이후 slice 메소드를 사용하여 객체를 배열로 변환함을 확인했다.

### 예제 3-18
함수 `a`는 가변 인자를 배열로 변환하여 각 인자를 출력하고, DOM 요소들을 선택하여 배열로 변환한 후 각 요소를 출력함을 확인했다.

### 예제 3-19
문자열을 배열 메소드를 사용하여 조작할 때, push 메소드는 길이를 변경할 수 없는 읽기 전용 속성에 할당할 수 없다는 오류가 발생하며, concat 메소드는 새로운 배열을 반환하고, every 메소드는 문자열 전체가 주어진 조건을 만족하지 않음을 확인했으며, some 메소드는 문자열 중 일부가 주어진 조건을 만족함을 확인했다. map 메소드는 각 문자에 대해 '!'를 추가한 새로운 배열을 반환하고, reduce 메소드는 문자열을 누적하여 새로운 문자열을 생성함을 확인했다.

### 예제 3-20
객체를 배열로 변환할 때 Array.from 메소드를 사용하여 각 프로퍼티 값을 배열 요소로 가져왔음을 확인했다.

### 예제 3-21
`Student`와 `Employee` 생성자 내에서 `Person` 생성자를 호출할 때 `call` 및 `apply` 메서드를 활용한다. 이를 통해 `Person`의 프로퍼티와 메서드를 상속받고, 각각의 객체에 새로운 속성을 추가한다. 최종적으로 `Student`와 `Employee` 객체를 생성하는 것을 확인했다.

### 예제 3-22
주어진 배열에서 최댓값과 최솟값을 찾아 출력함을 확인했다.

### 예제 3-23
객체를 배열로 변환할 때 Array.from 메소드를 사용하여 각 프로퍼티 값을 배열 요소로 가져왔음을 확인했다.

### 예제 3-24
주어진 배열에서 가장 큰 수와 가장 작은 수를 각각 찾아내어 출력함을 확인했다. 전개 구문을 사용하여 Math 객체의 max 및 min 메서드를 간결하게 적용했다.

### 예제 3-25
함수 `func`를 생성한 후, `bind` 메소드를 사용하여 다른 객체와 바인딩된 새로운 함수를 생성하고 호출하였다. bind 메소드를 사용하여 함수에 추가적으로 인자를 전달하면 해당 인자가 바인딩된 함수의 매개변수로 사용된다.

### 예제 3-26
bind 메소드로 생성된 새로운 함수의 name 속성은 원본 함수의 이름을 유지한다.

### 예제 3-27
객체의 메소드 내에서 내부 함수를 호출할 때, call 메소드를 사용하여 외부 함수의 this를 전달하거나, 내부 함수를 생성할 때 bind 메소드를 사용하여 외부 함수의 this를 유지함을 확인했다.

### 예제 3-28
setTimeout 함수 내에서 메소드를 호출할 때, 바로 호출한 경우와 bind 메소드를 사용하여 호출한 경우에는 this의 참조가 다르게 되어 결과가 달라짐을 확인했다.

### 예제 3-29
화살표 함수 내에서 this는 상위 스코프의 this를 유지함을 확인했다.

### 예제 3-30
메소드 `add`를 사용하여 sum과 count를 업데이트하고, average 메소드를 사용하여 sum을 count로 나눈 평균을 계산함을 확인했다.

### 예제 3-31
여러 메소드에서 자주 사용되는 배열 및 집합과 관련된 메소드들이다.


## HW2

### 예제 4-1
‘setInterval’의 매개변수로 익명 함수와 숫자가 전달되어 일정 간격으로 실행됩니다.

### 예제 4-2
‘setInterval’에 콜백 함수와 숫자를 매개변수로 전달하여 일정 간격으로 함수가 실행됩니다.

### 예제 4-3
`map` 메서드는 배열의 각 요소에 대해 콜백 함수를 실행하여 새로운 배열을 생성합니다.

### 예제 4-4
`map` 메서드의 콜백 함수에서 매개변수 순서가 잘못되어 첫 번째 매개변수가 인덱스가 되고, 두 번째 매개변수가 현재 값이 됩니다.

### 예제 4-5
map 메서드를 재정의하여 배열의 각 요소에 대해 콜백 함수를 실행하고, 그 결과로 새로운 배열을 반환합니다.

### 예제 4-6
`setTimeout`과 `forEach` 내에서 `this`는 전역 객체를 가리키며, 이벤트 리스너 내의 `this`는 이벤트가 발생한 요소를 가리킵니다.

### 예제 4-7
`logValues` 메서드를 직접 호출하면 `this`는 `obj`를 가리키고, `forEach` 내에서 메서드를 호출하면 `this`는 전역 객체를 가리킵니다.

### 예제 4-8
내부 함수에서 `self` 변수를 사용하여 `this`를 참조함으로써, 콜백 함수가 원래 객체 `obj1`의 `name`을 출력할 수 있도록 합니다.

### 예제 4-9
`setTimeout` 내에서 메서드를 호출하면 `this`는 전역 객체를 가리키므로, `obj1.func` 내에서 직접 `obj1.name`을 참조하여 `name`을 출력합니다.

### 예제 4-10
`obj2`의 `func` 메서드는 `obj1`의 `func` 메서드를 참조하고, `obj1.func.call(obj3)`는 `obj3`의 `name`을 출력하도록 `this`를 설정하여 호출됩니다.

### 예제 4-11
`setTimeout` 내에서 `bind` 메서드를 사용하여 `this`를 고정시키므로, `obj1.func`는 1초 후 `obj1`의 `name`을 출력하고, `obj1.func`는 1.5초 후 `obj2`의 `name`을 출력합니다.

### 예제 4-12
중첩된 `setTimeout`을 사용하여 500밀리초 간격으로 `coffeeList`에 커피 종류를 추가하고 출력합니다.

### 예제 4-13
각각의 커피 종류를 500밀리초 간격으로 순차적으로 `coffeeList`에 추가하고 출력하는 함수들이 체인 형태로 호출됩니다.

### 예제 4-14
Promise를 체인으로 연결하여 500밀리초 간격으로 커피 종류를 순차적으로 추가하고 출력합니다.

### 예제 4-15
`addCoffee` 함수는 이름을 받아 새로운 커피 이름을 추가하는 Promise를 반환하고, 이를 체인으로 연결하여 500밀리초 간격으로 순차적으로 커피 이름을 출력합니다.

### 예제 4-16
제너레이터와 `setTimeout`을 사용하여 500밀리초 간격으로 커피 이름을 순차적으로 생성하고 출력합니다.

### 예제 4-17
`async`와 `await`를 사용하여 500밀리초 간격으로 커피 이름을 순차적으로 추가하고, `coffeeList`를 출력합니다.

### 예제 5-1
내부 함수 `inner`는 외부 함수 `outer`의 변수 `a`에 접근하여 값을 증가시키고 출력합니다.

### 예제 5-2
외부 함수 `outer`는 내부 함수 `inner`를 호출하여 변수 `a`를 증가시키고 그 값을 반환하며, `outer2`는 증가된 값을 출력합니다.

### 예제 5-3
외부 함수 `outer`는 내부 함수 `inner`를 반환하고, `outer2`는 `inner`를 참조하여 호출될 때마다 변수 `a`를 증가시켜 그 값을 출력합니다.

### 예제 5-4
즉시 실행 함수 내에서 클로저를 사용하여 `setInterval`과 버튼 클릭 이벤트 핸들러에서 각각 변수 `a`와 `count`를 증가시키고 출력합니다.

### 예제 5-5
클로저를 사용하여 내부 상태를 관리하며, 각 실행 문맥에서 변수를 증가시키고 조건에 따라 참조를 해제합니다.

### 예제 5-6
클로저를 사용하여 각 리스트 아이템 클릭 시 해당 과일 이름을 알림으로 표시합니다.

### 예제 5-7
리스트 아이템을 클릭하면 클로저를 사용하여 각 과일 이름을 알림으로 표시하며, `alertFruit` 함수를 직접 호출하여 특정 과일을 알림으로 표시합니다.

### 예제 5-8 
`bind` 메서드를 사용하여 클릭 이벤트 핸들러에서 각 과일 이름을 알림으로 표시하도록 클로저를 생성합니다.

### 예제 5-9
클로저를 반환하는 `alertFruitBuilder` 함수를 사용하여 클릭 이벤트 핸들러에서 각 과일 이름을 알림으로 표시합니다.

### 예제 5-10
`car` 객체는 연료량, 출력, 이동 거리 속성을 가지고 있으며, `run` 메서드를 사용하여 임의의 거리를 이동하고 연료를 소비하며, 연료가 부족하면 이동 불가 메시지를 출력합니다.

### 예제 5-11
`createCar` 함수는 클로저를 사용하여 연료량, 출력, 이동 거리 속성을 캡슐화하고, `run` 메서드를 통해 임의의 거리를 이동하며 연료를 소비하고, 이동 불가 시 메시지를 출력하는 `car` 객체를 생성합니다.

### 예제 5-12
`createCar` 함수는 클로저를 사용하여 연료량, 출력, 이동 거리 속성을 캡슐화하고, `Object.freeze`를 통해 반환된 객체의 변경을 막으며, `run` 메서드를 통해 임의의 거리를 이동하고 연료를 소비하는 `car` 객체를 생성합니다.

### 예제 5-13
`add` 함수는 모든 인수의 합을 반환하며, `add.bind(null, 1, 2, 3, 4, 5)`는 부분 적용을 통해 초기 인수로 1, 2, 3, 4, 5를 고정하고, 추가 인수로 6, 7, 8, 9, 10을 받아 전체 합을 계산하여 출력합니다.

### 예제 5-14
`partial` 함수는 부분 적용 함수로, 초기 인수와 추가 인수를 결합하여 원래 함수를 호출합니다. 이를 통해 `addPartial`은 초기 인수 1, 2, 3, 4, 5와 추가 인수 6, 7, 8, 9, 10을 합산하며, `dog.greet`는 `dog` 객체의 `name` 속성을 사용하여 문자열을 반환합니다.

### 예제 5-15
`partial2` 함수는 `_`를 사용하여 자리 표시자를 처리하는 부분 적용 함수로, 부분 인수에서 `_`를 만나면 이후 인수로 대체합니다. 이를 통해 `addPartial`은 지정된 위치에 새로운 값을 삽입하여 전체 합을 계산하며, `dog.greet`는 자리 표시자를 사용하여 문자열을 반환합니다.

### 예제 5-16
`debounce` 함수는 이벤트 발생 후 지정된 시간 동안 추가 이벤트가 발생하지 않을 때만 실행되는 함수를 반환하여, `mousemove`와 `mousewheel` 이벤트에 대해 지정된 지연 시간 후에 각각 `moveHandler`와 `wheelHandler`를 호출합니다.

### 예제 5-17
`curry3` 함수는 인수를 하나씩 받아 최종적으로 두 인수를 가진 함수를 반환합니다. 이를 통해 `getMaxWith10`은 10과 주어진 인수 중 큰 값을 반환하고, `getMinWith10`은 10과 주어진 인수 중 작은 값을 반환합니다.

### 예제 5-18
`curry5` 함수는 인수를 하나씩 받아 최종적으로 다섯 인수를 가진 함수를 반환합니다. 이를 통해 `getMax`는 다섯 인수를 받아 그 중 가장 큰 값을 반환합니다.

## HW3

### 예제 6-1
`name`을 인자로 받아 `_name` 프로퍼티에 저장하고, `getName` 메서드를 프로토타입에 추가하여 `_name` 값을 반환합니다.

### 예제 6-2
`Constructor`는 `name`을 인자로 받아 객체를 생성하는 생성자 함수입니다. 이 함수의 프로토타입에 `method1` 메서드와 `property1` 속성이 추가되어 있습니다. `instance`는 `Constructor`를 통해 생성된 객체이며, 생성자 함수의 프로토타입을 상속받습니다.

### 예제 6-3
배열의 프로토타입을 사용하여 새로운 배열을 생성합니다.

### 예제 6-4
다양한 데이터 유형의 생성자를 변경합니다.

### 예제 6-5
프로토타입과 생성자를 사용하여 다양한 방식으로 Person 인스턴스를 생성합니다.

### 예제 6-6
`iu` 객체의 `getName` 메서드를 재정의하여 '바로 지금'을 반환합니다.

### 예제 6-7
배열 `arr`에 `push` 메서드를 사용하여 `3`을 추가하고, `hasOwnProperty` 메서드를 사용하여 인덱스 `2`에 해당하는 요소가 존재하는지 확인합니다.

### 예제 6-8
배열 'arr'의 'toString' 메서드를 다양한 방식으로 호출하고, 재정의하여 다른 형식으로 출력합니다.

### 예제 6-9
'getEntries' 메서드를 추가하여 객체의 소유 속성을 키-값 쌍으로 반환합니다.

### 예제 6-10
'Grade' 생성자 함수는 전달된 인수를 배열처럼 인스턴스에 할당하고, 'length' 속성을 설정합니다.

### 예제 7-1
'Rectangle' 생성자는 넓이를 계산하는 메서드와 인스턴스를 확인하는 정적 메서드를 제공합니다.

### 예제 7-2
'Grade' 생성자는 인수를 배열처럼 인스턴스에 할당하고, 프로토타입을 배열로 설정하여 배열 기능을 제공합니다.

### 예제 7-3
'Grade' 생성자는 배열처럼 동작하며, 배열 메서드를 통해 요소를 추가하고, 'length' 속성의 삭제 후 재설정을 보여줍니다.

### 예제 7-4
'Grade' 생성자는 배열처럼 동작하며, 'length' 삭제 후 배열 프로토타입의 'length'가 적용됨을 보여줍니다.

### 예제 7-5
'Rectangle'과 'Square' 생성자는 각각 넓이를 계산하는 'getArea' 메서드를 제공하는 객체를 생성합니다.

### 예제 7-6
'Rectangle'과 'Square' 생성자는 각각 직사각형과 정사각형의 넓이를 계산하는 'getArea' 메서드를 제공합니다.

### 예제 7-7
'Square'는 'Rectangle'을 상속하여 정사각형의 넓이를 계산하는 'getArea' 메서드를 사용합니다.

### 예제 7-8
'extendClass1' 함수는 상속을 구현하여 'Square'가 'Rectangle'의 'getArea' 메서드를 상속받도록 설정합니다.

### 예제 7-9
'extendClass2' 함수는 프로토타입 체인을 설정하여 'Square'가 'Rectangle'의 'getArea' 메서드를 상속받도록 합니다.

### 예제 7-10
'Square'는 'Rectangle'을 상속받아 넓이를 계산하는 'getArea' 메서드를 사용하며, 프로토타입을 동결합니다.

### 예제 7-11
'extendClass1' 함수는 상속을 구현하고, 'constructor'를 재설정하며, 선택적으로 메서드를 추가하고 프로토타입을 동결합니다.

### 예제 7-12
'extendClass2' 함수는 프로토타입 체인을 설정하고, 'constructor'를 재설정하며, 선택적으로 메서드를 추가하고 프로토타입을 동결합니다.

### 예제 7-13
'extendClass3' 함수는 'Object.create'를 통해 상속을 설정하고, 선택적으로 메서드를 추가하며, 프로토타입을 동결합니다.

### 예제 7-14
'extendClass' 함수는 상속을 설정하고, 'super' 메서드를 추가하여 부모 클래스의 메서드를 호출할 수 있도록 하며, 선택적으로 메서드를 추가하고 프로토타입을 동결합니다.

### 예제 7-15
ES5와 ES6 스타일로 클래스를 정의하여 인스턴스 메서드와 정적 메서드를 호출합니다.

### 예제 7-16
'Rectangle'와 'Square'는 ES6 클래스를 사용하여 정의되며, 'Square'는 'Rectangle'을 상속받아 정사각형의 넓이를 계산합니다.












