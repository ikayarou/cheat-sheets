# Case 1

```
1 2
```

```python
// str
a, b = input().split()
// int
a, b = map(int, input().split())
// list + int
l = list(map(int, input().split()))
```

# Case 2
```
3
1
2
3
```

```python
N = int(input())
l = [int(input()) for _ in range(N)]
```

# Case 3

```
1
2
3
...
```

```
import sys

l = []
for i in sys.stdin:
    l.append(int(i))
```