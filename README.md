# [ECMAScript](https://github.com/tc39/ecma262) proposals

# Finished Proposals

Finished proposals are proposals that have reached stage 4, and are included in the [latest draft](https://tc39.es/ecma262/) of the specification.

| Proposal                                                                 | ES Version | Description (한글) |
| ------------------------------------------------------------------------ | ----------- | ------------------ |
| [[`RegExp.escape`]](https://github.com/tc39/proposal-regexp-escape)                                                | ES2025      | 정규식 내 특수 문자를 이스케이프하여 리터럴 문자열로 취급하는 정적 메서드 `RegExp.escape()`를 추가합니다. |
| [Float16 on TypedArrays, DataView, `Math.f16round`](https://github.com/tc39/proposal-float16)            | ES2025      | `TypedArray`, `DataView`에서 16비트 부동소수점(half-precision) 형식을 지원하고, 가장 가까운 16비트 부동소수점 값으로 반올림하는 `Math.f16round()` 함수를 추가합니다. |
| [[`Promise.try`]](https://github.com/tc39/proposal-promise-try)                                                     | ES2025      | 동기/비동기 함수 실행을 `try...catch`처럼 감싸 즉시 Promise를 반환하는 `Promise.try()` 정적 메서드를 추가합니다. |
| [Sync Iterator helpers](https://github.com/tc39/proposal-iterator-helpers)                                | ES2025      | 동기 이터레이터에 `map`, `filter`, `take`, `drop`, `flatMap`, `reduce`, `toArray`, `forEach`, `some`, `every`, `find`와 같은 헬퍼 메서드를 추가합니다. |
| [JSON Modules](https://github.com/tc39/proposal-json-modules)                                             | ES2025      | `import` 문을 사용하여 JSON 파일을 모듈처럼 직접 가져올 수 있도록 지원합니다. |
| [Import Attributes](https://github.com/tc39/proposal-import-attributes)                                   | ES2025      | `import` 문에 추가적인 속성(예: `type`)을 명시하여 모듈 로딩 방식을 제어합니다 (이전 'Import Assertions'). |
| [RegExp Modifiers](https://github.com/tc39/proposal-regexp-modifiers)                                     | ES2025      | 정규식 리터럴 내에서 `(?i:)`와 같이 특정 부분에만 플래그(i, m, s)를 적용하거나 해제할 수 있는 문법을 추가합니다. |
| [New Set methods](https://github.com/tc39/proposal-set-methods)                                           | ES2025      | `Set` 객체에 교집합(`intersection`), 합집합(`union`), 차집합(`difference`), 대칭차집합(`symmetricDifference`), 부분집합 여부(`isSubsetOf`), 상위집합 여부(`isSupersetOf`), 서로소 여부(`isDisjointFrom`) 등의 새로운 메서드를 추가합니다. |
| [Duplicate named capture groups](https://github.com/tc39/proposal-duplicate-named-capturing-groups)                   | ES2025      | 정규식에서 동일한 이름의 캡처 그룹을 여러 번 사용할 수 있도록 허용합니다. |
| [ArrayBuffer transfer](https://github.com/tc39/proposal-arraybuffer-transfer)                             | ES2024      | `ArrayBuffer`의 소유권을 다른 컨텍스트로 효율적으로 이전(transfer)하거나, 현재 버퍼를 유지하면서 복사본을 이전하는 기능을 추가합니다. (`transfer()`, `transferToFixedLength()`) |
| [[`Promise.withResolvers`]](https://github.com/tc39/proposal-promise-with-resolvers)                                 | ES2024      | Promise 객체와 그 Promise를 제어하는 `resolve` 및 `reject` 함수를 함께 반환하는 `Promise.withResolvers()` 정적 메서드를 추가합니다. |
| [Array Grouping](https://github.com/tc39/proposal-array-grouping)                                         | ES2024      | 배열의 요소를 주어진 콜백 함수가 반환하는 값을 기준으로 그룹화하여 객체 또는 `Map`으로 반환하는 `Object.groupBy()` 및 `Map.groupBy()` 메서드를 추가합니다. |
| [Resizable and growable ArrayBuffers](https://github.com/tc39/proposal-resizable-arraybuffer)                         | ES2024      | 생성 시 `maxByteLength`를 지정하여 런타임에 크기를 조절할 수 있는 `ArrayBuffer` 및 `SharedArrayBuffer`를 지원합니다. |
| [RegExp v flag with set notation + properties of strings](https://github.com/tc39/proposal-regexp-v-flag) | ES2024      | 정규식에 유니코드 집합 연산(차집합, 교집합 등) 및 문자열의 유니코드 속성 지원을 강화하는 `v` 플래그를 추가합니다. |
| [[`Atomics.waitAsync`]](https://github.com/tc39/proposal-atomics-wait-async)                                       | ES2024      | `SharedArrayBuffer`의 특정 위치 값이 변경될 때까지 비동기적으로 대기하는 `Atomics.waitAsync()` 메서드를 추가합니다. |
| [Well-Formed Unicode Strings](https://github.com/tc39/proposal-well-formed-unicode-strings)                                | ES2024      | 문자열이 잘 구성된 유니코드인지 확인하는 `isWellFormed()` 메서드와, 잘 구성된 유니코드로 변환하는 `toWellFormed()` 메서드를 `String.prototype`에 추가합니다. |
| [Change Array by Copy](https://github.com/tc39/proposal-change-array-by-copy)                             | ES2023      | 원본 배열을 변경하지 않고 변경된 복사본을 반환하는 배열 메서드들(`toReversed()`, `toSorted()`, `toSpliced()`, `with()`)을 추가합니다. |
| [Symbols as WeakMap keys](https://github.com/tc39/proposal-symbols-as-weakmap-keys)                               | ES2023      | 고유하고 가비지 컬렉션 대상이 될 수 있는 `Symbol`을 `WeakMap`의 키로 사용할 수 있도록 허용합니다. |
| [Hashbang Grammar](https://github.com/tc39/proposal-hashbang)                                     | ES2023      | JavaScript 스크립트 파일 시작 부분의 해시뱅/셔뱅 (`#!`) 주석을 표준 문법으로 공식 인정하여, 실행 환경이 이를 올바르게 해석할 수 있도록 합니다. |
| [Array find from last](https://github.com/tc39/proposal-array-find-from-last)                                        | ES2023      | 배열의 끝에서부터 조건을 만족하는 요소를 찾는 `findLast()` 및 해당 요소의 인덱스를 찾는 `findLastIndex()` 메서드를 추가합니다. |
| [Error Cause](https://github.com/tc39/proposal-error-cause)                                               | ES2022      | `Error` 객체를 생성할 때 에러의 원인이 된 다른 에러를 명시할 수 있는 `cause` 옵션을 `Error` 생성자에 추가합니다. |
| [Class Static Block](https://github.com/tc39/proposal-class-static-block)                                      | ES2022      | 클래스 정의 내에서 정적 멤버를 초기화하거나 복잡한 정적 로직을 수행할 수 있는 `static {}` 블록을 도입합니다. |
| [Accessible `Object.prototype.hasOwnProperty`](https://github.com/tc39/proposal-accessible-object-hasownproperty)               | ES2022      | `Object.prototype.hasOwnProperty.call(obj, prop)` 대신 사용할 수 있는 더 안전하고 간결한 `Object.hasOwn(obj, prop)` 정적 메서드를 추가합니다. |
| [[`.at()`]](https://github.com/tc39/proposal-array-at)                                                            | ES2022      | 배열, 문자열, TypedArray 등 인덱싱 가능한 객체에서 음수 인덱스를 사용하여 끝에서부터 요소에 접근할 수 있는 `.at()` 메서드를 추가합니다. |
| [Ergonomic brand checks for Private Fields](https://github.com/tc39/proposal-private-fields-in-in)        | ES2022      | `in` 연산자를 사용하여 클래스 외부에서도 객체가 특정 프라이빗 필드를 가지고 있는지 여부를 안전하게 확인할 수 있게 합니다. |
| [Top-level `await`](https://github.com/tc39/proposal-top-level-await)                                               | ES2022      | ES 모듈의 최상위 레벨에서 `async` 함수 외부에서도 `await` 키워드를 사용하여 비동기 작업을 처리할 수 있도록 합니다. |
| [RegExp Match Indices](https://github.com/tc39/proposal-regexp-match-indices)                              | ES2022      | 정규식 일치 결과 객체에 각 캡처 그룹의 시작 및 끝 인덱스 정보를 제공하는 `indices` 속성을 추가합니다 (정규식에 `d` 플래그 사용 시). |
| [Class Fields (Private instance methods and accessors, Class Public Instance Fields & Private Instance Fields, Static class fields and private static methods)](https://github.com/tc39/proposal-class-fields) | ES2022      | 클래스에 public/private 인스턴스 필드, public/private static 필드, private 인스턴스 메서드/접근자, private static 메서드/접근자를 선언하는 기능을 제공합니다. |
| [Numeric separators](https://github.com/tc39/proposal-numeric-separator)                                 | ES2021      | 숫자 리터럴(예: `1_000_000`) 내에 밑줄(`_`)을 사용하여 가독성을 향상시키는 기능을 추가합니다. |
| [Logical Assignment Operators](https://github.com/tc39/proposal-logical-assignment)                       | ES2021      | 논리 연산자(`&&`, `||`, `??`)와 할당을 결합한 연산자(`&&=`, `||=`, `??=`)를 추가하여 코드를 간결하게 만듭니다. |
| [WeakRefs](https://github.com/tc39/proposal-weakrefs)                                                     | ES2021      | 객체에 대한 약한 참조(`WeakRef`)를 생성하여, 해당 객체가 가비지 컬렉션 대상이 되는 것을 막지 않으면서 참조할 수 있게 합니다. `FinalizationRegistry`도 함께 도입됩니다. |
| [[`Promise.any`]](https://github.com/tc39/proposal-promise-any)                                             | ES2021      | 여러 `Promise` 중 가장 먼저 성공(fulfilled)하는 `Promise`의 결과를 반환합니다. 모든 `Promise`가 실패하면 `AggregateError`를 반환합니다. |
| [[`String.prototype.replaceAll`]](https://github.com/tc39/proposal-string-replaceall)                             | ES2021      | 문자열 내에서 특정 부분 문자열의 모든 발생을 다른 문자열로 교체하는 `replaceAll()` 메서드를 추가합니다. |
| [[`import.meta`]](https://github.com/tc39/proposal-import-meta)                                             | ES2020      | ES 모듈 내에서 현재 모듈에 대한 컨텍스트 특정 메타데이터(예: 모듈 URL)를 담고 있는 `import.meta` 객체를 제공합니다. |
| [Nullish coalescing Operator](https://github.com/tc39/proposal-nullish-coalescing)                        | ES2020      | `??` 연산자로, 왼쪽 피연산자가 `null` 또는 `undefined`일 경우 오른쪽 피연산자를 반환하고, 그렇지 않으면 왼쪽 피연산자를 반환합니다. |
| [Optional Chaining](https://github.com/tc39/proposal-optional-chaining)                                            | ES2020      | `?.` 연산자로, 체인의 참조가 `null` 또는 `undefined`일 가능성이 있을 때 에러 발생 없이 프로퍼티나 함수 호출을 시도하고, 해당 값이 없으면 `undefined`를 반환합니다. |
| [[`for-in` mechanics]](https://github.com/tc39/proposal-for-in-order)                                   | ES2020      | `for...in` 루프가 객체 속성을 열거하는 순서에 대한 명세를 명확히 하여 구현 간 일관성을 높입니다. |
| [[`globalThis`]](https://github.com/tc39/proposal-global)                                               | ES2020      | 다양한 JavaScript 환경(브라우저의 `window`, Node.js의 `global` 등)에서 전역 `this` 값을 일관되게 참조할 수 있는 `globalThis` 키워드를 제공합니다. |
| [[`Promise.allSettled`]](https://github.com/tc39/proposal-promise-allSettled)                                       | ES2020      | 여러 `Promise`가 모두 이행(settled: 성공 또는 실패)될 때까지 기다린 후, 각 `Promise`의 상태와 결과(또는 이유)를 담은 객체의 배열을 반환합니다. |
| [[`BigInt`]](https://github.com/tc39/proposal-bigint)                                                       | ES2020      | `Number`의 최대 안전 정수보다 큰 정수를 표현할 수 있는 새로운 숫자 원시 타입 `BigInt`를 도입합니다. |
| [[`import()`]](https://github.com/tc39/proposal-dynamic-import)                                             | ES2020      | 필요할 때 모듈을 동적으로 로드할 수 있는 함수 형태의 `import()` 문법을 제공합니다. `Promise`를 반환합니다. |
| [[`String.prototype.matchAll`]](https://github.com/tc39/proposal-string-matchall)                                  | ES2020      | 정규식과 일치하는 모든 결과를 포함하는 이터레이터를 반환하는 `matchAll()` 메서드를 `String.prototype`에 추가합니다. |
| [[`Array.prototype.{flat,flatMap}`]](https://github.com/tc39/proposal-array-flat-map)                                 | ES2019      | 중첩된 배열을 지정된 깊이까지 평탄화하는 `flat()` 메서드와, 배열의 각 요소에 매핑 함수를 적용한 후 결과를 평탄화하는 `flatMap()` 메서드를 추가합니다. |
| [[`String.prototype.{trimStart,trimEnd}`]](https://github.com/tc39/proposal-string-trim-start-end)                          | ES2019      | 문자열의 시작 부분 공백을 제거하는 `trimStart()` (또는 `trimLeft`)와 끝 부분 공백을 제거하는 `trimEnd()` (또는 `trimRight`) 메서드를 추가합니다. |
| [Well-formed `JSON.stringify`](https://github.com/tc39/proposal-well-formed-stringify)                    | ES2019      | `JSON.stringify()`가 잘못된 유니코드 문자(예: lone surrogates)를 유효한 유니코드 이스케이프 시퀀스로 변환하여 반환하도록 수정합니다. |
| [[`Object.fromEntries`]](https://github.com/tc39/proposal-object-from-entries)                              | ES2019      | `[key, value]` 쌍의 배열이나 이터러블 객체를 받아 새로운 객체로 변환하는 `Object.fromEntries()` 정적 메서드를 추가합니다. (`Object.entries()`의 반대 기능) |
| [[`Function.prototype.toString` revision]](https://github.com/tc39/proposal-function-prototype-tostring-revision)             | ES2019      | `Function.prototype.toString()`이 함수 소스 코드를 반환할 때 주석과 공백을 포함하여 원본에 더 가깝게 반환하도록 명세를 개정합니다. |
| [[`Symbol.prototype.description`]](https://github.com/tc39/proposal-symbol-description)                     | ES2019      | `Symbol` 객체를 생성할 때 전달된 설명을 반환하는 읽기 전용 속성 `description`을 `Symbol.prototype`에 추가합니다. |
| [JSON superset](https://github.com/tc39/proposal-json-superset)                                           | ES2019      | ECMAScript 문자열 리터럴이 모든 JSON 문자열 리터럴을 포함하도록 하여, U+2028 (줄 구분자) 및 U+2029 (단락 구분자) 문자가 문자열 리터럴에 직접 포함될 수 있도록 합니다. |
| [Optional `catch` binding](https://github.com/tc39/proposal-optional-catch-binding)                               | ES2019      | `try...catch` 문에서 `catch` 블록의 예외 객체 바인딩(매개변수)을 사용하지 않을 경우 생략할 수 있도록 허용합니다 (예: `try {...} catch {...}`). |
| [Asynchronous Iteration](https://github.com/tc39/proposal-async-iteration)                                | ES2018      | 비동기적으로 데이터를 생성하는 이터레이터(Async Iterators)와 이를 소비하는 `for-await...of` 루프 문법을 도입합니다. |
| [[`Promise.prototype.finally`]](https://github.com/tc39/proposal-promise-finally)                                   | ES2018      | `Promise`가 성공(fulfilled)하든 실패(rejected)하든 관계없이 특정 콜백 함수를 실행하도록 하는 `finally()` 메서드를 `Promise.prototype`에 추가합니다. |
| [RegExp Unicode Property Escapes](https://github.com/tc39/proposal-regexp-unicode-property-escapes)                       | ES2018      | 정규식에서 유니코드 속성(예: Script, General_Category)을 사용하여 문자를 매칭할 수 있는 `\p{...}` 및 `\P{...}` 이스케이프 시퀀스를 지원합니다 (정규식에 `u` 플래그 필요). |
| [RegExp Lookbehind Assertions](https://github.com/tc39/proposal-regexp-lookbehind)                               | ES2018      | 정규식에서 현재 위치 이전의 텍스트를 조건으로 매칭하는 긍정형 후방탐색(`(?<=...)`) 및 부정형 후방탐색(`(?<!...)`)을 지원합니다. |
| [Rest/Spread Properties](https://github.com/tc39/proposal-object-rest-spread)                             | ES2018      | 객체 리터럴에서 나머지 속성을 모으는 Rest Properties (`...rest`)와 객체의 속성을 펼치는 Spread Properties (`...obj`)를 지원합니다. |
| [RegExp named capture groups](https://github.com/tc39/proposal-regexp-named-groups)                              | ES2018      | 정규식의 캡처 그룹에 이름을 지정하고 (`(?<name>...)`), 이름으로 참조할 수 있는 기능을 추가합니다. |
| [`s` (`dotAll`) flag for regular expressions](https://github.com/tc39/proposal-regexp-dotall-flag)                   | ES2018      | 정규식의 `.` 메타문자가 개행 문자(예: `\n`)를 포함한 모든 문자와 일치하도록 하는 `s` (dotAll) 플래그를 추가합니다. |
| [Lifting template literal restriction](https://github.com/tc39/proposal-template-literal-revision)            | ES2018      | 태그된 템플릿 리터럴에서 잘못된 이스케이프 시퀀스가 포함된 문자열을 사용할 수 없었던 제한을 완화합니다. `cooked` 문자열이 `undefined`일 경우 `raw` 문자열을 사용합니다. |
| [Shared memory and atomics](https://github.com/tc39/proposal-shared-memory-and-atomics)                                     | ES2017      | 여러 워커(스레드) 간에 메모리를 공유할 수 있는 `SharedArrayBuffer`와, 공유 메모리에서의 동시성 문제를 해결하기 위한 `Atomics` 객체를 도입하여 병렬 프로그래밍을 지원합니다. |
| [Async functions](https://github.com/tc39/proposal-async-await)                                           | ES2017      | `async` 키워드로 비동기 함수를 선언하고, `await` 키워드로 `Promise`가 완료될 때까지 함수의 실행을 일시 중지하여 비동기 코드를 동기식처럼 작성할 수 있게 합니다. |
| [Trailing commas in function parameter lists and calls](https://github.com/tc39/proposal-trailing-function-commas) | ES2017      | 함수 매개변수 목록 및 함수 호출 시 마지막 매개변수 뒤에 쉼표(trailing comma)를 허용하여 코드 수정 및 버전 관리 용이성을 높입니다. |
| [[`Object.getOwnPropertyDescriptors`]](https://github.com/tc39/proposal-object-getownpropertydescriptors)                       | ES2017      | 객체의 모든 자체 속성(상속된 속성 제외)에 대한 속성 기술자(property descriptor)들을 담은 객체를 반환하는 `Object.getOwnPropertyDescriptors()` 정적 메서드를 추가합니다. |
| [String padding](https://github.com/tc39/proposal-string-pad-start-end)                                         | ES2017      | 문자열의 시작 부분(`padStart()`) 또는 끝 부분(`padEnd()`)을 주어진 문자로 채워 지정된 길이의 새로운 문자열을 생성하는 메서드를 추가합니다. |
| [[`Object.values`/`Object.entries`]](https://github.com/tc39/proposal-object-values-entries)                | ES2017      | 객체의 자체 열거 가능한 속성 값들의 배열을 반환하는 `Object.values()`와, `[key, value]` 쌍의 배열을 반환하는 `Object.entries()` 정적 메서드를 추가합니다. |
| [Exponentiation operator](https://github.com/tc39/proposal-exponentiation-operator)                                | ES2016      | 거듭제곱 연산을 수행하는 중위 연산자 `**` (예: `2 ** 3`은 8)를 추가합니다. `Math.pow()`와 유사합니다. |
| [[`Array.prototype.includes`]](https://github.com/tc39/proposal-array-includes)                             | ES2016      | 배열이 특정 요소를 포함하고 있는지 여부를 불리언 값으로 반환하는 `includes()` 메서드를 `Array.prototype`에 추가합니다. `NaN`도 정확히 찾을 수 있습니다. |
| [Lexical Declarations (`let`, `const`)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let)                                   | ES2015      | 블록 스코프를 가지는 변수 선언 키워드 `let`과 상수 선언 키워드 `const`를 도입합니다. |
| [Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)                                                          | ES2015      | `function` 키워드 대신 화살표(`=>`)를 사용하여 함수를 간결하게 정의하며, 자체 `this` 바인딩을 갖지 않습니다. |
| [Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)                                                                  | ES2015      | 프로토타입 기반 상속을 더 명확하고 쉽게 사용할 수 있도록 하는 클래스 문법(`class`, `constructor`, `extends`, `super`, `static`)을 도입합니다. |
| [Enhanced Object Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer#New_notations_in_ECMAScript_2015)                                                 | ES2015      | 객체 리터럴 정의 시 속성 축약 표현, 계산된 속성 이름, 메서드 정의 축약 표현 등을 지원합니다. |
| [Template Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)                                                        | ES2015      | 백틱(\` \`)으로 감싸는 문자열로, 내부에 표현식을 삽입(${expression})하거나 여러 줄 문자열을 쉽게 작성할 수 있습니다. |
| [Destructuring Assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)                                                 | ES2015      | 배열이나 객체의 값을 추출하여 개별 변수에 할당하는 간편한 문법을 제공합니다. |
| [Default Parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)                                                      | ES2015      | 함수 매개변수에 기본값을 지정하여, 해당 인수가 전달되지 않거나 `undefined`일 경우 기본값을 사용하도록 합니다. |
| [Rest Parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)                                                         | ES2015      | 함수 매개변수 목록의 마지막에 `...`을 사용하여 나머지 인수들을 배열로 모을 수 있게 합니다. |
| [Spread Syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)                                                            | ES2015      | 배열이나 이터러블 객체를 개별 요소로 펼치거나, 객체를 다른 객체 리터럴에 펼칠 수 있게 합니다 (`...`). |
| [Iterators and `for...of` loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of)                                            | ES2015      | 이터레이션 프로토콜을 정의하고, 이터러블 객체(배열, 문자열, Map, Set 등)의 값을 순회하는 `for...of` 루프를 도입합니다. |
| [Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)                                                               | ES2015      | 실행을 중간에 멈추고 재개할 수 있는 특별한 함수(제너레이터 함수, `function*`)와 이터레이터를 생성하는 기능을 제공합니다. |
| [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)                                                                 | ES2015      | 비동기 작업의 최종 완료 또는 실패를 나타내는 객체와 그 결과를 다루는 표준화된 방법을 제공합니다. |
| [Modules (ESM: `import`/`export`)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)                                         | ES2015      | 코드를 모듈 단위로 구성하고, `import`와 `export` 키워드를 사용하여 모듈 간 의존성을 관리하는 표준 모듈 시스템을 도입합니다. |
| [`Map`, `Set`, `WeakMap`, `WeakSet`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)                                       | ES2015      | 키-값 쌍을 저장하는 `Map`, 고유한 값을 저장하는 `Set`, 그리고 키에 대한 약한 참조를 가지는 `WeakMap` 및 `WeakSet` 컬렉션 객체를 도입합니다. |
| [`Symbol` primitive type](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)                                                  | ES2015      | 고유하고 변경 불가능한 원시 값인 `Symbol` 타입을 도입하여, 객체 속성 키 충돌을 방지하는 데 사용될 수 있습니다. |
| [`Proxy` and `Reflect` APIs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy)                                               | ES2015      | 객체에 대한 기본적인 동작(속성 접근, 할당, 열거, 함수 호출 등)을 가로채고 재정의할 수 있는 `Proxy` 객체와, 이러한 동작을 위한 기본 메서드를 제공하는 `Reflect` API를 도입합니다. |
| [[`Object.assign`]](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)                                                          | ES2015      | 하나 이상의 출처 객체로부터 모든 열거 가능한 자체 속성을 대상 객체로 복사하는 `Object.assign()` 정적 메서드를 추가합니다. |
| [New `String` methods (e.g., `startsWith`, `endsWith`, `includes`, `repeat`)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String#New_methods_in_ECMAScript_2015) | ES2015      | 문자열 처리를 위한 다양한 새 메서드들(`startsWith`, `endsWith`, `includes`, `repeat` 등)을 `String.prototype`에 추가합니다. |
| [New `Array` methods (e.g., `Array.from`, `Array.of`, `find`, `findIndex`, `fill`, `copyWithin`)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array#New_methods_in_ECMAScript_2015) | ES2015      | 배열 조작 및 생성을 위한 다양한 새 메서드들(`Array.from`, `Array.of`, `find`, `findIndex`, `fill`, `copyWithin` 등)을 `Array` 객체 및 `Array.prototype`에 추가합니다. |
| [Typed Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Typed_arrays)                                                             | ES2015      | 원시 이진 데이터를 다루기 위한 배열 유사 객체들(예: `Int8Array`, `Float32Array`)과 `ArrayBuffer`를 제공합니다. |
| [Binary and Octal Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#Numeric_literals)                                                | ES2015      | 2진수(`0b` 또는 `0B` 접두사) 및 8진수(`0o` 또는 `0O` 접두사) 숫자 리터럴 표기법을 지원합니다. |
| [`__proto__` in object literals (standardized)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/proto)                            | ES2015      | 객체 리터럴 내에서 `__proto__` 속성을 사용하여 프로토타입을 설정하는 기능을 표준화합니다. (권장되지는 않음) |
| [[`Object.is`]](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/is)                                                              | ES2015      | 두 값이 같은 값인지 비교하는 `Object.is()` 정적 메서드를 추가합니다. (`===` 보다 `NaN`과 `+0`, `-0` 처리에 있어 더 정확함) |
| [`Number` properties and methods (e.g., `Number.isFinite`, `Number.isNaN`, `Number.EPSILON`)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number#New_methods_in_ECMAScript_2015) | ES2015      | 숫자 관련 유틸리티 상수(`EPSILON`, `MAX_SAFE_INTEGER` 등) 및 메서드(`isFinite`, `isNaN`, `isInteger`, `isSafeInteger` 등)를 `Number` 객체에 추가합니다. |
| [`Math` methods (e.g., `Math.trunc`, `Math.sign`, `Math.cbrt`, `Math.hypot`)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math#New_methods_in_ECMAScript_2015) | ES2015      | 수학 연산을 위한 다양한 새 정적 메서드들(`trunc`, `sign`, `cbrt`, `log10`, `hypot` 등)을 `Math` 객체에 추가합니다. |
| [Unicode regular expression (`u`) flag improvements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/unicode)                       | ES2015      | 정규식 `u` 플래그 사용 시 유니코드 코드 포인트 단위로 매칭하고, 유니코드 이스케이프 시퀀스(`\u{...}`)를 지원하는 등 유니코드 처리를 개선합니다. |
| [Sticky (`y`) flag for regular expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/sticky)                                | ES2015      | 정규식 `y` (sticky) 플래그를 추가하여, `lastIndex` 속성으로 지정된 위치에서만 일치하는지 확인하고, 일치하면 `lastIndex`를 갱신합니다. |


### Stage 3

| Proposal                                                                       | Description (한글) |
| ------------------------------------------------------------------------------ | ------------------ |
| [Legacy RegExp features in JavaScript][regexp-legacy]                          | 구형 브라우저에서 지원되던 비표준 정규식 기능(예: 특정 상황에서의 캡처 그룹 동작)을 명세에 포함하여 웹 호환성을 높입니다. |
| [Temporal][temporal]                                                           | 날짜 및 시간 처리를 위한 현대적이고 사용하기 쉬운 `Temporal` 전역 객체와 관련 API를 도입합니다. (기존 `Date` 객체의 단점 개선) |
| [Decorators][decorators]                                                       | 클래스와 클래스 멤버(메서드, 필드, 접근자)에 메타프로그래밍 기능을 추가할 수 있는 데코레이터 문법을 도입합니다. |
| [JSON.parse source text access][json-parse-source]                             | `JSON.parse`가 파싱한 값과 함께 원본 JSON 문자열의 해당 부분을 가져올 수 있는 기능을 추가합니다 (예: `reviver` 함수에서). |
| [`Array.fromAsync`][from-async]                                                | 비동기 이터러블이나 `Promise`를 반환하는 이터러블로부터 배열을 생성하는 `Array.fromAsync()` 정적 메서드를 추가합니다. |
| [Explicit Resource Management][resource-management]                            | 파일 핸들, 네트워크 연결 등 사용 후 명시적으로 해제해야 하는 리소스를 `using` 및 `await using` 구문을 통해 안전하게 관리하는 기능을 도입합니다. |
| [Decorator Metadata][decorator-metadata]                                       | 데코레이터가 클래스 및 멤버에 메타데이터를 연결하고 접근할 수 있도록 하는 표준적인 방법을 제공합니다. |
| [Source Phase Imports][source-phase-imports]                                   | 모듈 그래프를 분석하는 단계(소스 단계)에서만 필요한 모듈을 가져올 수 있도록 하여, 런타임에는 해당 모듈이 로드되지 않게 합니다. (주로 빌드 도구나 린터용) |
| [Time Zone Canonicalization][time-zone-canon]                                  | `Temporal` API에서 사용되는 시간대 식별자를 정규화(canonicalize)하는 방식을 명확히 합니다. |
| [Uint8Array to/from Base64][uint8array-base64]                                 | `Uint8Array`와 Base64 문자열 간의 효율적인 변환을 위한 메서드를 추가합니다. |
| [Dynamic Code Brand Checks][dynamic-code-brand-checks]                         | `eval`이나 `new Function` 등으로 생성된 동적 코드인지 여부를 안전하게 확인할 수 있는 방법을 제공합니다. |
| [Redeclarable global `eval`-introduced `var`s][redeclarable-global-eval-vars]  | 전역 스코프에서 `eval`을 통해 선언된 `var` 변수가 특정 조건 하에 재선언될 수 있도록 하는 동작을 명확히 합니다. |
| [`Atomics.pause`][atomics-pause]                                               | 스핀락(spin lock)과 같은 바쁜 대기(busy-waiting) 루프에서 CPU 사용량을 줄이고 성능을 개선하기 위해 짧은 시간 동안 실행을 일시 중지하는 `Atomics.pause()` 메서드를 추가합니다. |
| [`Error.isError`][is-error]                                                    | 주어진 값이 `Error` 객체인지 여부를 안정적으로 확인하는 `Error.isError()` 정적 메서드를 추가합니다. |
| [Deferring Module Evaluation][lazy-import]                                     | 모듈을 가져올 때 즉시 평가하지 않고, 실제 사용될 때까지 평가를 지연시키는 기능을 도입합니다. (성능 최적화) |
| [`Math.sumPrecise`][math-sum]                                                  | 부동소수점 숫자의 배열 합계를 계산할 때 정밀도 손실을 최소화하는 `Math.sumPrecise()` 메서드를 추가합니다. |






* [Stage 1 Proposals](stage-1-proposals.md)
* [Stage 0 Proposals](stage-0-proposals.md)
* [Finished Proposals](finished-proposals.md)
* [Inactive Proposals](inactive-proposals.md)

[ECMAScript Internationalization API Specification](ecma402/README.md) proposals

[Contributing to proposals](#contributing-to-proposals)

## Active proposals

Proposals follow [this process document](https://tc39.es/process-document/).
This list contains only stage 2 proposals and higher that have not yet been withdrawn/rejected, or become finished.
Stage 2 indicates that the committee expects these features to be developed and eventually included in the standard.



### Stage 2.7

| Proposal                                                                       | Author                                                                  | Champion                                                                | <sub>Test262 Feature Flag</sub>                                     | <sub>Last Presented</sub>                                  |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------------- |
| [ShadowRealm][shadowrealm]                                                     | Caridy Patiño<br />Jean-Francois Paradis   | Dave Herman<br />Mark Miller<br />Caridy Patiño<br />Leo Balter<br />Rick Waldron<br />Chengzhong Wu | <sub>[ShadowRealm][realms-tests]</sub>                              | <sub>[February&nbsp;2024][realms-notes]</sub>              |
| [Joint Iteration][joint]                                                       | Michael Ficarra                                                         | Michael Ficarra                                                         | <sub>[Testing plan][joint-testplan]</sub>                           | <sub>[June&nbsp;2024][joint-notes]</sub>                   |
| [Iterator Sequencing][sequencing]                                              | Michael Ficarra                                                         | Michael Ficarra                                                         | :question:                                                          | <sub>[October&nbsp;2024][sequencing-notes]</sub>           |
| [ESM Phase Imports][esm-phase]                                                 | Luca Casonato<br />Guy Bedford                                          | Luca Casonato<br />Guy Bedford                                          | :question:                                                          | <sub>[December&nbsp;2024][esm-phase-notes]</sub>           |
| [Immutable ArrayBuffers][immutable-abs]                                        | Mark Miller<br />Peter Hoddie<br />Richard Gibson<br />Jack Works | Mark Miller<br />Peter Hoddie<br />Richard Gibson<br />Jack Works             | :question:                                                          | <sub>[February&nbsp;2025][immutable-abs-notes]</sub>       |
| [Non-extensible Applies to Private][nonext-private]                            | Mark Miller<br />Shu-yu Guo<br />Chip Morningstar<br />Erik Marks | Mark Miller<br />Shu-yu Guo<br />Chip Morningstar<br />Erik Marks             | :question:                                                          | <sub>April&nbsp; 2025</sub>                                |
| [`Upsert`][upsert]                                                             | Daniel Minor, Lauritz Thoresen Angeltveit, Jonas Haukenes, Sune Lianes, Vetle Larsen, Mathias Hop Ness | Daniel Minor                             | <sub>[Testing plan][upsert-testing-plan]</sub>                      | <sub>April&nbsp; 2025</sub>                                |


### Stage 2

| Proposal                                                                       | Author                                                | Champion                                                                          | Stage 2.7 reviewers                        | <sub>Last Presented</sub>                                             |
| ------------------------------------------------------------------------------ | ----------------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------ | --------------------------------------------------------------------- |
| [`function.sent` metaproperty][function-sent]                                  | Allen Wirfs-Brock                                     | HE Shi-Jun                                                                        |                                            | <sub>[July&nbsp;2019][function-sent-notes]</sub>                      |
| [`throw` expressions][throw-expressions]                                       | Ron Buckton                                           | Ron Buckton                                                                       |                                            | <sub>[February&nbsp;2024][throw-expressions-notes]</sub>              |
| [Function implementation hiding][censorship]                                   | Domenic Denicola<br />Michael Ficarra                 | Michael Ficarra                                                                   |                                            | <sub>[June&nbsp;2020][censorship-notes]</sub>                         |
| [collection normalization][collection-rekey]                                   | Bradley Farias                                        | Bradley Farias                                                                    |                                            | <sub>[January&nbsp;2019][richer-keys-notes]</sub>                     |
| [isTemplateObject][isTemplateObject]                                           | Mike Samuel, Krzysztof Kotowicz                       | Daniel Ehrenberg<br />Jordan Harband                                              |                                            | <sub>[April&nbsp;2024][isTemplateObject-notes]</sub>                  |
| [Dynamic Import Host Adjustment][]                                             | Mike Samuel, Krzysztof Kotowicz                       | Krzysztof Kotowicz                                                                |                                            | <sub>[December&nbsp;2019][Dynamic Import Host Adjustment notes]</sub> |
| [Module Expressions][module-expressions]                                       | Surma<br />Daniel Ehrenberg<br />Nicolò Ribaudo       | Surma<br />Nicolò Ribaudo                                                         |                                            | <sub>[November&nbsp;2022][module-expressions-notes]</sub>             |
| [Pipeline Operator][pipeline]                                                  | J. S. Choi<br />James DiGioia<br />Ron Buckton<br />Tab Atkins | J. S. Choi<br />Ron Buckton<br />Tab Atkins                              |                                            | <sub>[August&nbsp;2021][pipe-notes]</sub>                             |
| [Destructure Private Fields][destructure-private]                              | Justin Ridgewell                                      | Justin Ridgewell                                                                  |                                            | <sub>[December&nbsp;2021][destructure-private-notes]</sub>            |
| [RegExp Buffer Boundaries (`\A`, `\z`, `\Z`)][regexp-buffer-boundaries]        | Ron Buckton                                           | Ron Buckton                                                                       |                                            | <sub>[December&nbsp;2021][regexp-buffer-boundaries-notes]</sub>       |
| [String.dedent][string.dedent]                                                 | Misha Kaletsky<br />Hemanth HM<br />Justin Ridgewell  | Hemanth HM<br />Justin Ridgewell                                                  |                                            | <sub>[June&nbsp;2022][string.dedent-notes]</sub>                      |
| [JSON.parseImmutable][json-parse-immutable]                                    | Robin Ricard<br />Richard Button<br />Nicolò Ribaudo<br />Ashley Claymore | Robin Ricard<br />Richard Button<br />Nicolò Ribaudo<br />Ashley Claymore |                                | <sub>[July&nbsp;2022][json-parse-source-notes]</sub>                  |
| [Module Declarations][module-declarations]                                     | Daniel Ehrenberg<br />Nicolò Ribaudo                  | Daniel Ehrenberg<br />Mark Miller<br />Nicolò Ribaudo                             |                                            | <sub>[November&nbsp;2022][module-declarations-notes]</sub>            |
| [Symbol Predicates][symbol-predicates]                                         | Robin Ricard<br />Jordan Harband                      | Ashley Claymore<br />Jordan Harband                                               |                                            | <sub>[May&nbsp;2023][symbol-predicates-notes]</sub>                   |
| [Async Iterator helpers][async-iterator-helpers]                               | Gus Caplan                                            | Michael Ficarra<br />Jonathan Keslin<br />Kevin Gibbons                           |                                            | <sub>[June&nbsp;2024][async-it-helper-notes]</sub>                    |
| [Iterator.range][iterator-range]                                               | Jack Works                                            | Jack Works                                                                        |                                            | <sub>[April&nbsp;2024][iterator-range-notes]</sub>                    |
| [Async Context][async-context]                                                 | Chengzhong Wu                                         | Andreu Botella<br />Chengzhong Wu<br />Justin Ridgewell                           | James M Snell<br />Mark S. Miller          | <sub>[April&nbsp;2024][async-context-notes]</sub>                     |
| ["Discard" (`void`) Bindings][discards]                                        | Ron Buckton                                           | Ron Buckton                                                                       |                                            | <sub>[June&nbsp;2024][discards-notes]</sub>                           |
| [Propagate active ScriptOrModule with JobCallback Record][scriptormodule]      | Chengzhong Wu                                         | Chengzhong Wu                                                                     |                                            | <sub>[July&nbsp;2024][scriptormodule-notes]</sub>                     |
| [Structs: Fixed Layout Objects and Some Synchronization Primitives][structs]   | Shu-yu Guo                                            | Shu-yu Guo                                          | Mark Miller<br />Waldemar Horwat<br />Yulia Startsev<br />Nicolò Ribaudo | <sub>[October&nbsp;2024][structs-notes]</sub>                         |
| [Extractors][extractors]                                                       | Ron Buckton                                           | Ron Buckton                                                                       | Jordan Harband<br />Justin Ridgewell       | <sub>[October&nbsp;2024][extractors-notes]</sub>                      |
| [iterator chunking][chunking]                                                  | Michael Ficarra                                       | Michael Ficarra                                                         | Ashley Claymore<br />Jordan Harband<br />Jesse Alama | <sub>[October&nbsp;2024][chunking-notes]</sub>                        |
| [Error Stack Accessor][stack-accessor]                                         | Jordan Harband                                        | Jordan Harband<br />Mark Miller                                                   | Nicolò Ribaudo<br />Michael Ficarra        | <sub>[February&nbsp;2025][stack-accessor-notes]</sub>                 |
| [Deferred Re-exports][deferred-reexport]                                       | Nicolò Ribaudo                                        | Nicolò Ribaudo                                                                    | Chengzhong Wu<br />Ashley Claymore         | <sub>April&nbsp;2025</sub>                                            |

The test262 feature flag links to a code search of tests using that feature flag, which may constitute complete or partial coverage.
The :question: means there is no feature flag for tests yet.

## Contributing to proposals

See [Contributing to ECMAScript](https://github.com/tc39/ecma262/blob/HEAD/CONTRIBUTING.md) and [How We Work](https://github.com/tc39/how-we-work/blob/main/README.md#proposals) for the most up-to-date information on contributing to proposals to TC39 standards and how proposals advance.

### Onboarding proposals

Proposals that are Stage 1 and above must be transferred to [the TC39 GitHub organization](https://github.com/tc39) for discoverability and archival purposes. To onboard a proposal:

1. Transfer your repository to the [@tc39-transfer](http://github.com/tc39-transfer) organization
   * if you are a TC39 delegate, but not a member of that organization, please contact [@LJHarb](https://github.com/ljharb)
2. The Github Administrator, or one of the chairs, will transfer your repository to the TC39 organization the next chance they get.

Note that as part of the onboarding process your repository name may be normalized. Don't worry, repo redirects will continue to work **as long as** you never create a fork, or a new repository, with the same name - although Github Pages redirects will be broken (please update your links!).

[regexp-legacy]: https://github.com/tc39/proposal-regexp-legacy-features
[regexp-legacy-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2017-05/may-25.md#15ia-regexp-legacy-features-for-stage-3
[tests-regexp-legacy]: https://github.com/tc39/test262/search?l=JavaScript&q=legacy-regexp
[function-sent]: https://github.com/tc39/proposal-function.sent
[function-sent-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-07/july-23.md#making-functionsent-inactive
[decorators]: https://github.com/tc39/proposal-decorators
[decorators-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-03/mar-28.md#decorators-for-stage-3
[decorators-tests]: https://github.com/tc39/test262/search?l=JavaScript&q=decorators
[decorators-testplan]: https://github.com/tc39/test262/issues/4042
[shadowrealm]: https://github.com/tc39/proposal-shadowrealm
[realms-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-02/feb-7.md#shadowrealms-update
[realms-tests]: https://github.com/tc39/test262/search?l=JavaScript&q=ShadowRealm
[temporal]: https://github.com/tc39/proposal-temporal
[temporal-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-07/july-30.md#temporal-update--bug-fixes
[temporal-tests]: https://github.com/tc39/test262/search?l=JavaScript&q=Temporal
[temporal-testplan]: https://github.com/tc39/test262/issues/3002
[throw-expressions]: https://github.com/tc39/proposal-throw-expressions
[throw-expressions-notes]: https://github.com/tc39/notes/blob/main/meetings/2024-02/feb-8.md#throw-expressions-update-or-stage-27
[censorship]: https://github.com/tc39/proposal-function-implementation-hiding
[censorship-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2020-06/june-2.md#function-implementation-hiding-for-stage-3
[richer-keys]: https://github.com/tc39/proposal-richer-keys
[richer-keys-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-01/jan-30.md#richer-keys-for-stage-2
[resource-management]: https://github.com/tc39/proposal-explicit-resource-management
[resource-management-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/dec-01.md#explicit-resource-management-for-stage-3
[resource-management-tests]: https://github.com/tc39/test262/search?l=JavaScript&q=explicit-resource-management
[async-resource-management]: https://github.com/tc39/proposal-async-explicit-resource-management
[standard-library]: https://github.com/tc39/proposal-javascript-standard-library
[standard-library-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2018-07/july-26.md#javascript-standard-library
[collection-rekey]: https://github.com/tc39/proposal-collection-normalization
[async-iterator-helpers]: https://github.com/tc39/proposal-async-iterator-helpers
[async-iterator-helpers-notes]: https://github.com/tc39/notes/blob/main/meetings/2023-01/jan-31.md#parallel-async-iterators-via-a-tweak-to-iterator-helpers
[private-declarations]: https://github.com/tc39/proposal-private-declarations
[isTemplateObject]: https://github.com/tc39/proposal-array-is-template-object
[isTemplateObject-notes]: https://github.com/tc39/notes/blob/main/meetings/2024-04/april-10.md#arrayistemplateobject-next-steps
[upsert]: https://github.com/tc39/proposal-upsert
[upsert-notes]: https://github.com/tc39/notes/blob/main/meetings/2024-12/december-02.md#upsert-formerly-mapemplace-update-and-request-for-stage-2-reviewers
[upsert-testing-plan]: https://github.com/tc39/test262/issues/4470
[Dynamic Import Host Adjustment]: https://github.com/tc39/proposal-dynamic-import-host-adjustment
[Dynamic Import Host Adjustment notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-12/december-5.md#dynamic-import-host-adjustment-for-stage-2
[json-parse-source]: https://github.com/tc39/proposal-json-parse-with-source
[json-parse-source-notes]: https://github.com/tc39/notes/blob/main/meetings/2022-07/jul-19.md#conclusiondecision-2
[json-parse-source-tests]: https://github.com/tc39/test262/search?l=JavaScript&q=json-parse-with-source
[json-parse-testplan]: https://github.com/tc39/test262/issues/4096
[module-expressions]: https://github.com/tc39/proposal-module-expressions
[module-expressions-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/dec-01.md#module-expressions
[pipeline]: https://github.com/tc39/proposal-pipeline-operator
[pipe-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-08/aug-31.md#pipeline-operator-for-stage-2
[destructure-private]: https://github.com/tc39/proposal-destructuring-private
[destructure-private-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-12/dec-14.md#destructuring-private-fields
[from-async]: https://github.com/tc39/proposal-array-from-async
[from-async-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-09/sep-14.md#arrayfromasync-for-stage-3
[from-async-tests]: https://github.com/tc39/test262/search?l=JavaScript&q=Array.fromAsync
[regexp-buffer-boundaries]: https://github.com/tc39/proposal-regexp-buffer-boundaries
[regexp-buffer-boundaries-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-12/dec-15.md#regexp-buffer-boundaries-for-stage-2
[decorator-metadata]: https://github.com/tc39/proposal-decorator-metadata
[decorator-metadata-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2023-05/may-18.md#decorator-metadata-final-spec-text-review-for-stage-3
[decorator-metadata-tests]: https://github.com/tc39/test262/pull/3971
[named-groups-tests]: https://github.com/tc39/test262/search?l=JavaScript&q=regexp-duplicate-named-groups
[string.dedent]: https://github.com/tc39/proposal-string-dedent
[string.dedent-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-06/jun-07.md#stringdedent
[source-phase-imports]: https://github.com/tc39/proposal-source-phase-imports
[source-phase-imports-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2023-07/july-12.md#source-phase-imports-for-stage-3
[source-phase-imports-tests]: https://github.com/tc39/test262/pull/3980
[json-parse-immutable]: https://github.com/tc39/proposal-json-parseimmutable
[module-declarations]: https://github.com/tc39/proposal-module-declarations
[module-declarations-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/dec-01.md#module-declarations
[symbol-predicates]: https://github.com/tc39/proposal-symbol-predicates
[symbol-predicates-notes]: https://github.com/tc39/notes/blob/4c253a989e8da200bc8c351f1e0a557e2a5d73e4/meetings/2023-05/may-15.md?plain=1#L385
[iterator-range]: https://github.com/tc39/proposal-iterator.range
[iterator-range-notes]: https://github.com/tc39/notes/blob/main/meetings/2024-04/april-09.md#iteratorrange-for-stage-27
[async-context]: https://github.com/tc39/proposal-async-context
[async-context-notes]: https://github.com/tc39/notes/blob/main/meetings/2024-04/april-09.md#asynccontext-stage-2-updates
[time-zone-canon]: https://github.com/tc39/proposal-canonical-tz#readme
[time-zone-canon-notes]: https://github.com/tc39/notes/blob/main/meetings/2023-07/july-12.md#time-zone-canonicalization-for-stage-3
[time-zone-canon-tests]: https://github.com/tc39/test262/pull/3837
[lazy-import]: https://github.com/tc39/proposal-defer-import-eval
[lazy-import-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2025-02/february-18.md#import-defer-for-stage-3
[lazy-import-testplan]: https://github.com/tc39/test262/issues/4111
[uint8array-base64]: https://github.com/tc39/proposal-arraybuffer-base64
[uint8array-base64-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-02/feb-7.md#uint8array-base64-for-stages-27-and-3
[uint8array-base64-tests]: https://github.com/tc39/test262/pull/3994
[joint]: https://github.com/tc39/proposal-joint-iteration
[joint-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-06/june-12.md#joint-iteration-for-stage-27
[joint-testplan]: https://github.com/tc39/test262/issues/4112
[redeclarable-global-eval-vars]: https://github.com/tc39/proposal-redeclarable-global-eval-vars
[redeclarable-global-eval-vars-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-04/april-08.md#make-eval-introduced-global-vars-redeclarable-for-stage-27
[redeclarable-global-eval-vars-testplan]: https://github.com/tc39/test262/issues/4223
[math-sum]: https://github.com/tc39/proposal-math-sum
[math-sum-notes]: https://github.com/tc39/notes/blob/main/meetings/2024-10/october-09.md#mathsumprecise-for-stage-3--last-chance-to-suggest-other-names
[math-sum-tests]: https://github.com/tc39/test262/pull/4049
[math-sum-testplan]: https://github.com/tc39/test262/issues/4054
[dynamic-code-brand-checks]: https://github.com/tc39/proposal-dynamic-code-brand-checks
[dynamic-code-brand-checks-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-12/december-5.md#dynamic-code-brand-checks-for-stage-2
[is-error]: https://github.com/tc39/proposal-is-error
[is-error-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-12/december-02.md#erroriserror-to-stage-3
[error-iserror-tests]: https://github.com/tc39/test262/pull/4266
[sequencing]: https://github.com/tc39/proposal-iterator-sequencing
[sequencing-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-10/october-08.md#iterator-sequencing-for-stage-27
[esm-phase]: https://github.com/tc39/proposal-esm-phase-imports
[esm-phase-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-12/december-04.md#esm-phase-imports-for-stage-27
[discards]: https://github.com/tc39/proposal-discard-binding
[discards-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-06/june-13.md#discard-bindings-update-or-stage-2
[scriptormodule]: https://github.com/tc39/proposal-jobcallback-module
[scriptormodule-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-07/july-31.md#continuation-propagate-active-scriptormodule-with-jobcallback-record
[async-it-helper-notes]: https://github.com/tc39/notes/blob/main/meetings/2024-06/june-11.md#async-iterators-update
[atomics-pause-notes]: https://github.com/tc39/notes/blob/main/meetings/2024-10/october-09.md#atomicspause-for-stage-3
[atomics-pause]: https://github.com/tc39/proposal-atomics-microwait
[atomics-pause-tests]: https://github.com/tc39/test262/pull/4147
[structs]: https://github.com/tc39/proposal-structs
[structs-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-10/october-08.md#structs-and-shared-structs-for-stage-2
[extractors]: https://github.com/tc39/proposal-extractors
[extractors-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-10/october-09.md#extractors-for-stage-2
[chunking]: https://github.com/tc39/proposal-iterator-chunking
[chunking-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2024-10/october-09.md#iterator-chunking-for-stage-2
[immutable-abs]: https://github.com/tc39/proposal-immutable-arraybuffer
[immutable-abs-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2025-02/february-18.md#immutable-arraybuffer
[stack-accessor]: https://github.com/tc39/proposal-error-stack-accessor
[stack-accessor-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2025-02/february-19.md#error-stack-accessor
[nonext-private]: https://github.com/syg/proposal-nonextensible-applies-to-private
[deferred-reexport]: https://github.com/tc39/proposal-deferred-reexports
