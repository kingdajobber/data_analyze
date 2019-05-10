# Numpy基础
---
## 1.ndarray数组
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
## 2.内存中的 ndrray
---
### 元数据
存储对目标数组的描述信息
> dtype, data, 等

### 实际数据
完整的数组数据
> 将实际数据与元数据分开存放,一方面提高了内存的控件使用效率,另一方面减少对实际数据的访问频率,提高性能

## 3.创建ndarry对象
```javascript
import numpy as np

# 创建对象的几种方法
np.array([1,2,3,4,5])

np.arange(1,10,1)  # 从0到9,步长为1的整数数组

np.zeros(10)  # 10个0的数组

np.ones(10)  #  10个1的数组

np.zeros_like(ary)  # 全0的数组,数据格式同ary
```
