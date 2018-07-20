# SKHUCODE 2주차

------

2018-07-20 / 1 PM - 3 PM  / SKHU 1406

출석자 : 최인혁, 김지은, 김지혜, 최태훈

지각자 (-500): 최태훈

결석자 (-1000): 이예지, 이혜지



#### 1. 과제 내용

- code.plus `프로그래밍 대회에서 사용하는 java` chapter  3~4 문제 풀이(Sort, BigInteger)
- code.plus `알고리즘 기초` 알고리즘과 입/출력 문제 풀이
- 자바 개인적으로 공부하기



#### 2. 활동 내용

* 강의 후기

  - **정렬**

    > * Comparator과 Comparable 차이
    > * Collections.reverserOrder()
    > * Arrays.parallelSort()메소드 : 멀티스레드 활용으로 병렬처리 시간 빠름.
    >   * ForkJoinFrameword - https://blog.naver.com/2feelus/220732310413

    > 이승진교수님 강의자료 참고하여 간결하게 구현!
    >
    > @Override
    >
    > public int compareTo(Point that){
    >
    > ​	int r = this.r - that.r;
    >
    > ​       if(r!=0) return r;
    >
    > ​	return this.y-that.y;
    >
    > }

  

  - **BigInteger**

    > * BigDecimal 클래스에서 toPlainString() 메소드 : 어떤 경우에도 다른 기호없이 숫자로만 표현.
    > * BigDecimal 클래스에서 toString()은 필요하면 지수형태로 표현할 수도 있다.
    > * Integer와 같이 Wrapper클래스를 쓰는이유는 Collection에 사용하기 위해서이다.
    > * Collections 는 기본자료형이 안되기 때문이다. 그 이유는 더 알아보도록 하자.**..**

  - **알고리즘과 입/출력**

    > * scanner.nextLine() : 이 메소드는 끝에있는 행 구분자를 제외한 나머지 현재 행을 리턴합니다. 위치는 다음 행의 시작 부분으로 설정됩니다(java api 공식문서)



#### 3. 다음주 계획

- 원래 계획했던 문제는 필수로 풀기! 
- 강의노트에 추가로 제시되는 문제는 본인 선택. => 관련 궁금증이나 논의거리 모임 때 나누기 :)

7/23 (월) 저녁 6시 OR 7/27 (금)  오후 1시 (점심 먹고오기!)

자료구조1(스택, 큐, 덱, 문자열) + 다이나믹프로그래밍1(다이나믹 프로그래밍1)



