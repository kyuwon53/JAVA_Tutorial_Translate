## 자바 기술에 대해서
자바 기술은 프로그래밍 언어이면서 플랫폼이다. 

### 자바 프로그래밍 언어

자바 언어는 다음의 단어들로 특징지을 수 있는 고급 언어다. 

- 단순함
- 객체 지향
- 분산
- 다중 스레드( 다중 처리 )
- 동적
- 중립적인 아키텍쳐
- 이식성
- 고성능
- 구조적으로 튼튼
- 보안 

앞의 각 단어들은 James Gosling와 Henry McGilton이 작성한  [The Java Language Environment](https://www.oracle.com/java/technologies/language-environment.html)에 설명되어있다. 

자바의 모든 소스 코드는 먼저 `.java` 확장자로 끝나는 텍스트 파일로 작성된다. 
그 다음 이 소스 파일들은 `.class`파일로 `javac` 컴파일러가 컴파일한다. `.class` 파일에는 프로세서 고유  코드를 포함하지 않는다. 대신에 *바이트 코드*가 포함되어 있다. 즉, ` Java Virtual Machine1 (Java VM)`의 기계어이다. 자바 실행 도구가 JVM의 인스턴스로 애플리케이션을 실행한다. 

<br>
<div style="text-align:center">

![소프트웨어 개발 과정](https://docs.oracle.com/javase/tutorial/figures/getStarted/getStarted-compiler.gif) 
</div>


Java VM은 다양한 운영 시스템에 사용가능하므로, 같은 `.class` 파일을 Microsoft windows, Solaris™ Operating System (Solaris OS), Linux, or Mac OS 에서 실행할 수 있다. [Java SE HotSpot at a Glance](https://www.oracle.com/java/technologies/javase/javase-core-technologies-apis.html)와 같은 일부 가상 머신은 런타임에 추가 기능을 수행해 기능을 향상시킨다. 여기에 성능 병목 형상 찾기와 자주 사용하는 코드 섹션 리컴파일(네이티브 코드로) 와 같은 다양한 작업들이 포함된다.

<br>
<div style="text-align:center">

![예시2](https://docs.oracle.com/javase/tutorial/figures/getStarted/helloWorld.gif)

 (Java VM을 통해 동일한 애플리케이션을 여러 플랫폼에서 실행할 수 있다.) </div>

### 자바 플랫폼

플랫폼은 프로그램이 실행되는 하드웨어 또는 소프트웨어 환경이다. 우리는 이미 Microsoft Windows, Linux, Solaris OS, and Mac OS 같은 인기 있는 플랫폼을 말했어. 대부분 플랫폼은 운영 시스템과 기본 하드웨어의 조합으로 설명할 수 있다. 자바 플랫폼은 다른 하드웨어 기반 플랫폼 위에서 실행되는 소프트웨어 전용 플랫폼라는 점에서 대부분의 다른 플랫폼들과 다르다. 

자바 플랫폼은 두 가지 컴포넌트가 있다:
  - 자바 가상 머신 
  - 자바 애플리케이션 프로그래밍 인터페이스 (API)

당신은 이미 자바 가상 머신을 소개받았다. 자바 플랫폼 기반이고 다양한 하드웨어 기반 플랫폼에 이식된다.

API는 많은 유용한 기능을 제공하는 기성 소프트웨어 구성요소의 거대한 모음이다. 그것은 연관된 클래스와 인터페이스들의 라이브러리로 그룹화된다. 이러한 라이브러리는 패키지라고 한다. 다음 섹션인 [자바 기술은 무엇을 할 수 있는가?](https://docs.oracle.com/javase/tutorial/getStarted/intro/cando.html) API에서 제공하는 일부 기능을 강조 한다.

<br>
<div style="text-align:center">

![예시3](https://docs.oracle.com/javase/tutorial/figures/getStarted/getStarted-jvm.gif)

API와 자바 가상머신은 기본 하드웨어로부터 프로그램을 격리한다.
</div>

독립적인 구성 환경으로, 자바 플랫폼은 네이티브 코드보다 약간 느릴수 있다. 하지만, 컴파일러와 가상 머신 기술의 발전으로 위협적인 이식성 없이 네이티브 코드와 가까운 성능을 가져온다.

<u>`자바 가상 머신` 및 `JVM` 은 자바 플랫폼을 위한 가상 머신을 의미한다.</u>
