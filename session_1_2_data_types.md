# Session 1-2

파이썬의 데이터타입.

데이터 타입, 즉 자료형은 자료가 어떤 종류에 속하는지 종류를 붙여준 것이다. 정수, 실수, 문자 와 같은 개념이다. 

## 파이썬은 primitive type이 없다. 
파이썬에서 모든 데이터는 **객체로 다룬다**. 

primitive type은 **없지만** 그에 상응하는 built-in 객체가 있다.

|종류|자료형|예|비고|
|---|---|---|---|
|정수|`int`|`a=3`||
|실수|`float`|`b=1.5`||
|문자열|`str`|c="hello", c='world' , c="""hello""" ||
|리스트|`list`|`d=[10,20,"a"]`||
|튜플|`tuple`|`e=(10,20,30)`||
|집합| `set`|`a={10,20,30}`||
|딕셔너리| `dict`|a=[1:'키',2:'몸무게']||  

타입을 확인하려면 `type(변수명)` 함수를 쓰면 된다. 

## 파이썬은 데이터형을 명시하지 않는다. 
c나 java 같이 `int, String`을 앞에 명시하지 않는다.
```python
a = 3
type(a) # <class 'int'>
```

## 파이썬은 자동 형변환을 지원하지 않는다. 
다른 종류의 객체들은 상호 연산이 되지 않는다. 직접 함수로 변환해줘야 한다. 
``` python
print("2+3은"+(2+3)) # 에러.
print("2+3은 "+str(2+3)) # 2+3은 5
```


* python 의 작성 특징
* python 의 자료형
* python 의 연산자
* python 에서 변수를 다루는 방법, 내부 구조


## 참고문헌
* [자료형 정리 - tistory](https://bigdaheta.tistory.com/5)
* [자료형 - 한곳에서 끝내는 파이썬](https://sdc-james.gitbook.io/onebook/3./3.4.)