---
layout: page
title: 프로그래밍과 문제해결
subtitle: 정수
---

> 바보는 궁금해하고, 현명한 사람은 물어본다.  
> The fool wonders, the wise man asks.  
> --- Benjamin Disraeli

### 훈련 임무

학생 교안을 클릭한다. 선생님은 학생들이 교안을 채워넣도록 도와 준다.

- [학생 교안](http://www.codeskulptor.org/#user40_cgApbpcHnwcsJtO.py)
- [선생님 교안](http://www.codeskulptor.org/#user40_0kra14IoJNK03eD.py)

**고급([교안](http://www.codeskulptor.org/#user40_SsV0yMn77uVA2KI.py))**:
문자열과 정수는 매우 다른 자료형이다; 문자열을 사용해서 텍스트를 생성하는 반면에, 정수를 사용해서 세거나, 수학문제를 푼다. 다음과 같은 것을 작업하는 것은 의미가 없다:

~~~ {.python}
result = "hello" + 5
~~~
종종, 정수를 포함하는 문자열을 수학 계산을 하려고 정수로 변환하거나, 반대로 숫자를 문자열로 변환한다. `str()` 과 `int()` 함수를 사용해서 자료형을 다른 자료형으로 변환할 수 있다, 즉, `str()` 함수는 무언가를 문자령로 `int()` 함수는 무언가를 정수형으로 변환한다. 따라서, 다음은 작동하지 않는 예제다.

~~~ {.python}
result = 5 + "10"                  # 정수와 문자열을 더하면 작동하지 않는다.
msg = "I am " + 10 + " years old"  # 붙이기 기능은 문자열만 작동한다.
~~~

하지만, 다음은 작동한다:

~~~ {.python}
result = 5 + int("10")                  # int("10") 값은 정수 10이 된다.
msg = "I am " + str(10) + " years old"  # str(10)  값은 문자열 "10" 이 된다.
~~~

### 3학년 - 파이썬으로 하는 산수

[학습 교안](http://www.codeskulptor.org/#user40_4enAUHHcmVRoc24.py)

파이썬은 수학에 무척 능하다; 파이썬에게 1자리 숫자를 더하는 계산보다 10자리 숫자를 더하는 계산이라고 더 어려운 것은 아니다; 동일한 계산이 뺄셈, 곱셈, 나눗셈에도 적용된다. 따라서, 파이썬이 숙제를 검사하는 프로그램을 작성한다.

프로그램 시작부분에 두 숫자를 두 변수에 집어넣는다. 예를 들어, `number_1`, `number_2`.

~~~ {.python}
number_1 = 5
number_2 = 3
~~~

그리고 나서, 프로그램이 다음을 출력하게 한다:

~~~ {.python}
5 + 3 = 8
5 - 3 = 2
3 - 5 = -2
5 * 3 = 15
~~~

<img src="fig/numbers-738068_640-300x169" width="45%" />

해답: [보여주기](http://www.codeskulptor.org/#user40_hgc1fHOzrLZhZRE.py)

### 4학년 - 이빨 요청 [^1]

[^1]: 이빨 요정(tooth fairy) - 어린 아이의 침대 머리맡에 자기전에 빠진 이를 놓아두면,이빨을 가져가고 대신에 동전을 놓고 간다는 요정

[학습 교안](http://www.codeskulptor.org/#user40_Lns5UBKZUCA6JqC.py)

이빨 요정은 아이들 이빨이 빠지면 선물을 놓고 간다; 종종 선물로 아이 베개 밑에 돈을 놓아 둔다. 만약 이빨 하나당 $2 달러로, 이빨이 20개 있다면, 이빨 요정에서 아이가 얼마나 받을 수 있는지 알려주는 프로그램을 작성한다.

프로그램 시작부분에 변수로 이빨 갯수와 선물 금액을 지정한다. 그리고, 결과를 출력하는 프로그램을 작성한다:

~~~ {.python}
teeth = 20
present = $2
total = $40
~~~

이제 어려운 문제로 가자: 일생동안 [일부 상어는 이빨이 50,000 개](http://wonderopolis.org/wonder/how-many-teeth-do-sharks-have/)가 빠진다. 여러분이 만일 이빨 50,000 개가 빠진다면 이빨요정은 얼마의 돈을 놓고 갈지 알아내시오. 만약 이빨 하나당 $2 달러 대신에 $5 달러라면 얼마의 돈을 놓고 갈까?

<img src="fig/shark-47634_640" width="30%" />

정답: [보여주기](http://www.codeskulptor.org/#user40_wR2qHk7aabEujiR.py)


### 5 학년 : 던젼 앤드 드래곤(Dungeons and Dragons)

[학습 교안](http://www.codeskulptor.org/#user40_ico0wo4NCJS1kR8.py)

`던젼 앤드 드래곤`은 인간, 요정, 난장이 역할을 맡아 모험을 떠나는 게임이다. 흡혈귀로 가득찬 버려진 유적, 혹은 용이 지키고 있는 보물동굴을 탐험해 나간다.




