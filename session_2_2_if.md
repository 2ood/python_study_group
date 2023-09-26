# if statement

* {}를 사용하지 않는다. 들여쓰기로 내부 문장을 표현한다.

## if, elif, else
* else if 는 `elif` 이라는 키워드로 쓴다. 

```python
a = 10
if a < 8 :
    print("A")
elif a < 11 :   
    print("B")
else :
    print("C")
# B
```

# for loop
* sequence 가 뒤에 온다. 
* iteration 을 주로 `range()` 함수로 한다. `range(10)` 함수는 0~9 까지 iteration 한다. 

```python
for(int i=0 ; i++ ;i<10)
for i in range(10):
    print(i)
```

* iterable object 로도 iteration할 수 있다. 튜플, 리스트 를 비구조화해서 사용가능하다.

```python
words = [(‘apple’,’good’), (‘banana’, ‘bad’),
               (‘orange’, ‘excellent’)]

for (word1, word2) in words:
    print(word1)
    print(word2)
#결과
(‘apple’, ‘good’)
(‘banana’, ‘bad’)
(‘orange’, ‘excellent’)
```


# while loop
```python
i=0
while i < 6:
    i += 1
    print(i) 
```


Q. 비구조화 