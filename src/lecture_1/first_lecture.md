# Day1

## 교재(?)
* [점프 투 자바](https://wikidocs.net/9112)

## 참고하면 좋은 책들
* [자바의 정석](https://book.naver.com/bookdb/book_detail.nhn?bid=15091458)
* [이것이 자바다](https://book.naver.com/bookdb/book_detail.nhn?bid=15091458)

## 객체지향 프로그래밍 언어 - 자바의 특징
* 간단하다 (Simple)  
  자바는 C++에 가깝지만 훨씬 간단하다. 자바는 고급 언어들에 들어 있는 여러 가지 요소들 중에서 반드시 필요하지 않다고 생각된 부분들은 모두 제거했다.

* 객체 지향적이다 (Object-oriented)  
  자바는 숫자(int, float, long 등)나 논리값(true, false)을 제외한 거의 모든 것이 객체로 구성되어 있다. 실제로 자바는 Object 클래스에서 모든 클래스를 파생한다.  
  자바는 이러한 이유로 int, float, long, true, flase 등을 원시 자료형(primitive type)이라고 한다.

* 객체란 무엇인가?
    * 우리가 추상화해야할 대상을 정의하여 표기하는 것 (자동차/사람/비행기 등등)
        * 객체는 속성과 행동을 가진다.
        * 객체는 다른 객체와 상호작용한다.

* 인터프리터 언어이다 (Interpreted)  - [참고링크](https://eunjinii.tistory.com/4)<br/>
 자바는 정확하게 말하면 컴파일 언어인 동시에 인터프리터 언어이다. 자바는 먼저 텍스트 소스를 컴파일하여 2진 파일(클래스 파일)로 만든 다음 자바 런타임이 클래스 파일을 인터프리트하면서 실행한다.   
먼저 시스템에 무관한 2진 파일을 만듬으로써 자바는 컴파일 언어에 가까운 속도와 시스템 독립성을 동시에 얻을 수 있었다.

* 안전하다 (Secured)  
  자바는 프로그램 작성 시 자료형 타입에 굉장히 민감하다. 이것은 마치 코딩할 때 잔소리꾼이 끊임없이 따라다니며 잘못된 코드를 작성하지 않게끔 도와주는 역할을 한다. 그래서 자바는 일단 컴파일만 되면 실행 시 오류가 발생하는 경우가 다른 언어에 비해 현저히 낮다. 파이썬과 같은 동적 언어에 익숙한 프로그래머라면 자바의 이렇듯 유연성이 없는 고지식한 면을 싫어 할수도 있다. 하지만 자바의 이런 족쇄같은 타입체크는 코드를 매우 명확하게 만들어주는 힘이 있다. 컴파일이 되었다면 코드에 결정적인 문제는 없는 것이다.

* 플랫폼 독립적이다 (Platform independent)  
  자바의 실행 파일은 이진 코드(클래스) 파일이다. 따라서 자바 런타임이 설치된 시스템에서는 어디서나 자바 프로그램을 실행할 수 있다.

자바에는 많은 특징이 있지만 가장 큰 특징이라면 한번 작성한 프로그램은 OS(Operating System)에 상관없이 어디서든 돌려볼 수 있다는 점일 것이다. 이것은 자바 프로그램이 가상머신(Virtual Machine)에 의해서 실행되기 때문이다. 처음에 이 방식은 자바 가상 머신을 실행시켜서 프로그램을 돌려야 하기 때문에 좀 느리고 부담스러웠다. 하지만 지금은 하드웨어의 눈부신 발전과 여러 기술들의 개발로 이러한 단점들이 대부분 사라져버린 상태이다.

* 멀티 쓰레딩을 지원한다 (Multithreaded)  
  멀티 쓰레드를 지원할 경우 하나의 프로그램 단위가 동일한 쓰레드를 동시에 수행할 수 있다. 특히 자바는 멀티 프로세서 하드웨어를 지원하도록 설계되었으므로 멀티 CPU 시스템에서 높은 효율을 낼 수 있다.

* 동적이다 (Dynamic)  
  자바 인터페이스를 이용하면 하나의 모듈을 갱신할 때 다른 모듈을 모두 갱신할 필요가 없다. 이것은 인터페이스가 모든 인스턴스 변수와 도구의 실행문을 배제한 채 객체 간의 상호 작용을 정의하기 때문이다.

## JVM (Java Virtual Machine)
* [링크1](https://maenco.tistory.com/entry/JVM-Java-Virtual-Machine%EC%9D%98-%EC%9D%B4%ED%95%B4)
* [링크2](https://huelet.tistory.com/entry/JVM-%EB%A9%94%EB%AA%A8%EB%A6%AC%EA%B5%AC%EC%A1%B0)

## 개발환경구축
* [공식홈페이지](https://www.oracle.com/java/technologies/javase-downloads.html)
* [윈도우설치](https://languagestory.tistory.com/11#:~:text=%EC%A0%81%EC%9A%A9,for%20Developers%EB%A5%BC%20%ED%81%B4%EB%A6%AD%ED%95%9C%EB%8B%A4.&text=%E2%91%A1%20%EB%8B%A4%EC%9A%B4%20%EB%B0%9B%EC%9D%80%20%ED%8C%8C%EC%9D%BC%EC%9D%84,%E2%91%A2%20%EC%84%A4%EC%B9%98%EB%A5%BC%20%EC%8B%9C%EC%9E%91%ED%95%9C%EB%8B%A4.)
* [맥설치](https://jsikim1.tistory.com/191)


