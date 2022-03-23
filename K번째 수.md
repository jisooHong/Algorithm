https://programmers.co.kr/learn/courses/30/lessons/42748

```python3
import copy
def solution(array, commands):
    answer = []

    for command in commands:
        new_array = copy.deepcopy(array)
        new_array = new_array[command[0]-1:command[1]]
        new_array.sort()
        answer.append(new_array[command[2]-1])
    return answer
```
