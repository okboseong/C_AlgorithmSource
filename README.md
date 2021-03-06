## 알고리즘이란?

**정의** : 1. 문제를 해결하거나 함수를 계산하기 위한 모호함이 없는 간단한 명령들로 구성된 일련의 순서적 단계.

 (정의는 사이트 마다 전부다 다른 것 같다.)

​		  2. 튜링 기계에 의해 수행 가능한 프로시저. 

**유형** : 수열, 수학, 배열, 자료구조, 응용

**요건** : 1. 외부에서 0개 이상의 입력을 받아, 하나 이상의 출력을 생성

```
	  2. 각 단계가 단순하고 모호하지 않아야 한다.
```

3. 한정된 수의 작업후에는 반드시 끝나야 한다.
   4. 모든 명령이 수행 가능해야 한다.
      5. 효율적이어야 한다.

**알고리즘과 순서도**

알고리즘을 표현하기 위한 방법으로 순서도를 가장 많이 사용한다.

순서도를 이용하면 알고리즘의 구조를 한눈에 파악하기 편리하다.

------

## 순서도

**개념** : 미리 정해진 기호를 이용하여 그려지는 그림으로, 논리적인 절차를 표현하는 방법중 하나이다.

순서도를 이용하면 전체적인 구조가 한눈에 들어오므로 프로그래밍을 구현하기 이전 단계인 논리적절차를 위한 알고리즘을 표현하기 위한 방법으로 순서도를 가장 많이 사용한다. 

**작성법** : 위에서 아래로 START 기호로부터 END기호로 작성한다. 

순서도는 직선구조, 분기구조(조건문), 반복구조로 나뉜다. 

기호와 기호사이에는 흐름선(↓)을 사용한다.

값을 보관하고자 하는 경우변수를 이용한다. 

------

## 프로그래밍이란.

**개념** : 프로그래밍이란 논리의 전개. 문제를 해결하고자하는 논리들을 질서 있게 나열한 문장들, 처음부터 순서대로 물 흐르듯 명령들을 수행한다. 프로그램을 작성한다는 것은 이러한 순서를 나열하는 것이다. 

**변수**: 절차적 프로그래밍 언어에서 프로그램의 값을 움직이는 주체적 역할을 하고, **변하는 값**을 가지게 되는 저장공의 이름. 프로그램에서는 변수라는 이름으로 불리게 되지만 메모리에 할당된 후로는 메모리주소 몇 번지에서 몇 번지까지의 이름으로 바뀌게 될 것 이다. 

**상수** : 항상 똑같은 값을 갖는 수로써 숫자, 문자 등을 의미한다.

**데이터 타입(자료형, data type)** : 프로그래밍을 하기 위해서는 데이터를 컴퓨터 내부로 읽어들여 표현해야 하는데, 데이터의 종류에 따라 크게 문자, 숫자 등으로 나뉘게 된다. 컴퓨터적으로 표현하는 방법에 따라서 자료들이 형(type)을 갖는다는 의미 

**치환** : 컴퓨터 프로그래밍에서는 값을 변수에 배정하는 것을 치환한다라고 하고 기호는 **=** 를 사용한다. 

**예약어** : 프로그램 내에는 반드시 정해진 규칙으로 사용해야하는 용어와 아닌 용어가 있는데 전자는 **예약어** 라고 하고 후자는 **식별자** 라고 한다.  

**주석문** : 프로그램의 실행과는 관계없이 프로그램 코드 내 기록할 문자들을 주석문이라고 한다. 주로 해설할때 사용. 

------

## 디버깅

**정의** : De(없애다, 떼어내다) + Bug(벌레)  프로그램 안에 있는 벌레, 오류(에러)를 없애는 작업을 의미한다.

작성한 순서도가 맞는지 검증하는 단계.

직접 하나 값을 대입하며 본인이 만든 순서도를 실제 컴퓨터가 실행 하듯 확인하는 단계이다. 

