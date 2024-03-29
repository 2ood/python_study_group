# Session 1_1

## Session 1 Agenda
* python 의 작성 특징
* python 의 자료형
* python 의 연산자
* python 에서 변수를 다루는 방법, 내부 구조

# Session 1-1
Python에 대해 알아보자

## Python의 특징
> 장점
> 1. 인터프리터 언어
> 2. 쉽고 간단. (별명이 executable pseudo code)
> 3. 플랫폼 독립적. (어느 환경이든 같은 코드로 실행가능)
> 4. 큰 사용자 풀. (커뮤니티가 크다)

> 단점
> 1. 실행속도가 느리다.
> 2. 배포가 복잡하다.

인터프리터 언어란, 
* 한 줄씩 실행해가는 형식의 프로그래밍 언어. 
* 정확히는, 한문장 단위씩 변환해가는 언어.
* python의 경우 한문장씩 그에 상응하는 c 언어 문장으로 바꿔서 실행한다. 

python 의 interpreter 는 그래서
* (interpreter) C언어로 변환도 하고
* (compiler) 그 C언어 파일을 실행파일로 컴파일, 실행도 한다.  

쉽고 직관적이어서, 코드 그 자체를 영어 문장 읽듯이 읽을 수 있다. pseudocode란 명령문들을 코드 문법형식으로 쓰기 전 우리가 생각한 대로 줄글로 쓰는 것을 말하는데, python은 별명 만큼 코드 문법형식으로 쓴 내용도 잘 읽힌다. 같은 내용을 구현하는 다음 java 와 python 문장을 비교해보자.

```java
for(int i=0;i<10;i++) {
    System.out.println(i);
}
```
```python
for i in range(10) :
    print(i)
```
python은 플랫폼 독립적이어서, (인터프리터가 지원되는) 모든 환경에서 같은 코드로 실행할 수 있다. 예를 들어, 휴대폰에서 절전모드를 만드는 것과 에어컨에서 절전모드를 만드는 것을 같은 코드로 구현할 수 있다는 것이다. 

python의 가장 큰 장점은 사용자가 많다는 것이다. 따라서 막힌 부분을 검색하면 이미 그 질문을 한 사람이 있을 가능성이 높다. 언어를 사용하다 보면 엄청난 장점이라는 것을 알게 된다. 

다만, python은 한번 변환해서 실행하기 때문에 아무래도 실행 시간이 더 걸린다. 인간이 느낄 정도는 아니지만, 최적화 면에서는 구현 후 다른 언어로 바꾸는 것이 낫다. 

배포가 복잡하다고 한다. 안해봐서 모름.


# 참고문헌
* [파이썬 - 나무위키](https://namu.wiki/w/Python)
* [파이썬 자습서 - 파이썬 공식문서](https://docs.python.org/ko/3/tutorial/index.html)
* [파이썬 인터프리터(python interpreter)란? - tistory](https://gusdnr69.tistory.com/55) 
