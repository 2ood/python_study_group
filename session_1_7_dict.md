# Dictionary
> 요소와 키가 매치되어 있는 것. JSON과 비슷.

```python
a = {"name" : "computer", "age" : 24}
a["name"] # computer
```

요소 추가하려면 하나 더 명시해주면 된다. 
```python
a["height"] = 170
a # {"name" : "computer", "age" : 24, "height": 170}
```

삭제하려면 del 명령어. 모두 지워 비우려면 clear 함수.
```python
del a["height"]

a.clear()
```

키 값만, value 값만, 쌍으로 가져오기
```python
a.keys()
a.values()
a.items()
```