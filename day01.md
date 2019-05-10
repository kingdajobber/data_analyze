# Numpy基础
---
## 1. ndarray数组
### 示例
```javascript
import numpy as np

ary = np.array([1,2,3,4,5])
print(ary,type(ary))

print(ary + ary)

print(ary * ary)

print(ary > 3)
```
**输出**
```javascript
[1 2 3 4 5] <class 'numpy.ndarray'>
[ 2  4  6  8 10]
[ 1  4  9 16 25]
[False False False  True  True]
```
