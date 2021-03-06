# SOLID 원칙 실습
예제로 학습하는 SOLID 객체 지향 디자인 원칙

## SOLID 원칙
### SRP (Single Responsibility Principle) 단일 책임의 원칙
> 클래스 설계할때 단 한개의 기능만 수행하도록 해야 하며, 그 기능에 집중해야한다.

* 기능이 한 개만 있으므로 책임영역이 확실하며, 코드 가독성이 좋고, 유지보수에 유리함

### OCP (Open Close Principle) 개방 폐쇄의 원칙
> 소프트웨어 구성요소 (컴포넌트, 클래스, 모듈, 함수)는 기능 확장은 가능하지만, 수정은 하지 않아야 한다.

* 변경에 의한 비용은 줄이고, 확장을 위한 비용은 극대화 해야 한다.
* 추가 요구사항이 있어도 기존 구성요소의 수정은 없도록 하며, 기존요소를 확장하여 재사용 할 수 있어야 한다.
* OCP가 가능하려면 추상화 다형성이 필요하며, 재사용 코드를 만드는 기반이 된다.

### LSP (Liskov Substitution) 리스코브 치환의 원칙
> 부모 클래스로 동작하던 프로그램이 속성의 변경 없이 자식 클래스로 치환되었을 때 동작해야 한다.

* 부모 클래스와 자식 클래스 사이의 기능은 일관성이 있어야 한다는 의미
* 상위 클래스는 공통속성이나 추상화된 기능만을 가지고 있어야 함

### ISP (Interface Segregation Principle) 인터페이스 분리의 원칙
> 한 클래스는 자신이 사용하지 않는 인터페이스는 구현하지 말아야 한다.

* 어떤 클래스가 다른 클래스에 종속될때 가능한 최소한의 인터페이스만 사용해야 함
* 인터페이스 분리를 통해 시스템 내부의 의존성이 약화되며, 리팩토링 및 수정 배포가 쉬워짐

### DIP (Dependency Inversion Principle) 의존성역전의 원칙
> High Level 모듈은 Low Level 모듈에 의존하면 안되며, 추상화된 것은 구체적인 것에 의존하면 안된다.

* 모듈간의 직접적인 의존을 끊고, 상위 레벨 모듈에서 정의한 추상을 하위레벨 모듈이 구현하게 하는 원칙

## 실습 1단계
5개의 예제가 어떤 SOLID 원칙에 해당하는지, 이유와 함께 서술하시오.

### 실습 템플릿
#### 01_bird_type
* 적용 가능 원칙: 
* 이유: 
* 리팩토링 전략:

#### 02_house_type
* 적용 가능 원칙: 
* 이유: 
* 리팩토링 전략:

#### 03_weather_tracker
* 적용 가능 원칙: 
* 이유: 
* 리팩토링 전략:

#### 04_board
* 적용 가능 원칙: 
* 이유: 
* 리팩토링 전략:
  
#### 05_greeter
* 적용 가능 원칙: 
* 이유: 
* 리팩토링 전략:


## 실습 2단계
1단계의 전략을 기반으로한 리팩토링
