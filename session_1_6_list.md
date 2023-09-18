# Session 1_6 Tuple
```python
list = [1,2.5,"hello",[True,False]]
```

* 요소는 같은 형식일 필요 없다.
* 요소로는 아무거나 다 들어간다. 

## indexing
* indexing 도 가능하다. 0부터. 
* 부분 indexing 은 colon 으로. `a[{start_index} :{end_index+1}]`
```python
a= [1,2,3]
a[0:3] # [1,2]
```

## Comprehension 방식

```python
a = [x*2 for x in range(6)]
a #[0,2,4,6,8,10]
```
안의 내용을 판독해서 해석해 저장한다.
