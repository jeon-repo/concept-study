개념
====
표기법
------
### 1. 파스칼 표기법
- 모든 단어에서 첫 번째 문자는 대문자이며, 나머지 문자는 소문자로 표기하는 방법   
(ex: PascalCase)

### 2. 카멜 표기법
- 최초에 사용된 단어를 제회안 첫 번째 문자가 대문자이며, 나머지 문자는 소문자로 표기하는 방법   
(ex: camelCase)

### 3. 헝가리안 표기법
- 최초에 사용된 단어는 데이터의 타입을 나타내며, 두 번째 단어부터 첫 번째 문자가 대문자이고, 나머지 문자는 소문자로 표기하는 방법   
(ex: intHungarianCase)

### 4. 스네이크 표기법
- 단어간 띄어쓰기 대신 언더바(_)로 표기하는 방법   
(ex: snake_case)

### 5. 케밥 표기법
- 단어간 띄어쓰기 대신 하이픈(-)으로 표기하는 방법   
(ex: kebab-case)

- - -
용어 정리
---------
### FDD(Feature Driven Development)
- 개발을 상품이나 서비스 단위가 아니라 신규 기능(=함수) 단위로 하는 개발 방법론

### TDD(Test Driven Development)
- 요구사항을 검증하는 자동화 테스트 케이스를 작성한 후에,
그 테스트 케이스를 통과하기 위한 최소한의 코드를 생성하는 개발 방법론,   
마지막으로 작성한 코드를 표준에 맞도록 리팩토링

### 리팩토링(Refactoring)
- 기능을 유지하면서 가독성과 유지보수성을 개선하기 위해서 소스코드를 재작성하는 행위를 말함
- 코드의 기능은 그대로, 구조만 변경
- S/W의 디자인을 개선시키기 위해 사용

### 클래스(Class)
- 객체 지향 프로그래밍(OOP)에서 특정 객체를 생성하기 위해 변수와 메소드를 정의하는 일종의 틀(설계도)
- 객체를 정의하기 위한 멤버 변수(상태)와 메서드(멤버 함수)로 구성

### 객체(Object)
- 클래스를 통해 구현할 모든 대상을 정의한 개념
- 객체는 클래스와 인스턴스를 포함한 개념
- 클래스로 규정된 인스턴스로서, 변수 대신 실제값을 가짐

### 인스턴스(Instance)
- 객체 지향 프로그래밍에서 클래스의 구조로 컴퓨터 저장공간에서 할당된 실체를 의미
- 객체가 메모리에 실제로 할당 되었을 때, 인스턴스라고 함
- - -
    클래스, 객체, 인스턴스
    클래스는 집의 설계도(객체를 생성하는 틀),   
    객체는 설계도로 지은 모든 집(클래스의 인스턴스),   
    인스턴스는 주어진 집(메모리에 실제 할당된 객체)
- - -

### 멤버 변수(Member variable)
- 객체 지향 프로그래밍에서 멤버 변수는 특정 객체와 연결된 변수의 하나이며, 모든 메소드(멤버 함수)에 접근이 가능

### 메서드(Method)
- 객체 지향 프로그래밍에서 클래스 안에서 정의되어 클래스의 인스턴스에만 적용될 수 있는 함수를 메소드라고 함

### 인자(Parameter)
- 함수 정의에 사용되는 변수
- - -
    def function1(parameter):
        return 0
해당식에서 사용된 변수 parameter를 인자 or 파라미터라고 함   
ex) "function1에서 parameter를 인자로 받았다" 처럼 사용
- - -
### 인수(Argument)
- 함수 호출에 사용되는 변수
- - -
    def function2():
        num = 10
        result = function1(num)
        return result
해당식에서 사용된 변수 num을 인수 or 아규먼트라고 함   
ex) "function1에 num을 인수로 넘겼다" 처럼 사용
- - -
- 틀린부분 혹은 문의: <jano.jeon@gmail.com>