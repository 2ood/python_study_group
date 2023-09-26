# Function

> 파이썬에선 function 도 객체이다!

## 함수를 정의하기
```python
def addFunction(a,b) :
    return a+b
``` 

키워드 `def`를 쓴다. 함수의 모든 내용은 들여쓴다. 

## 입력변수 자유자재로 늘리기
`*`를 `args` 앞에 붙인다. 어떤 데이터형이든 넣을 수 있다. 튜플 형식으로 입력된다.
```python
def newFunc(*args):
    print(args)

newFunc(1,2,3,4,5,[1,2,3]) # (1,2,3,4,5,[1,2,3])
```

`**`를 붙여서 명시적으로 하나씩 넣을 수도 있다. 딕셔너리 형식으로 입력된다. 
```python
def newFunc(**kwargs):
    print(kwargs)

setStudent(number="64",grade=3,name="홍길동") # {'a':1,'b':2,'c':3}
```

Q. 변수 shallow, **hard?** 
```python
a = 1

def add1(a):
    return a+1

a=add1(a)
print(a)
```
