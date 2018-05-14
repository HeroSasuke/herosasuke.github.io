# 集合(set)

```
集合是无序的，集合中的元素是唯一的，集合一般用于元组或者列表中的元素去重。
```

### 定义一个空的集合
```python
set1 = set()
```

### 添加元素
- add

  ```python
  In [30]: set1 = {1,2,3,4}

  In [31]: set1.add(5)

  In [32]: set1
  Out[32]: {1, 2, 3, 4, 5}
  ```
- update

  ```python
  In [34]: set1 = {1,2,3,4}

  #是把要传入的元素拆分，做为个体传入到集合中
  In [35]: set1.update("abcd")

  In [36]: set1
  Out[36]: {1, 2, 3, 4, 'b', 'c', 'd', 'a'}
  ```

### 删除元素

- remove

  ```python
  In [38]: set1 = {1,2,3,4}

  In [39]: set1.remove(1)

  In [40]: set1
  Out[40]: {2, 3, 4}
  # 使用remove删除集合中的元素 如果有 直接删除 如果没有 程序报错
  In [41]: set1.remove(11)
  ---------------------------------------------------------------------------
  KeyError                                  Traceback (most recent call last)
  <ipython-input-41-d7b1e6a36eb0> in <module>()
  ----> 1 set1.remove(11)

  KeyError: 11
  ```

- pop

  ```python
  In [43]: set1 = {1,2,3,4}
  # 使用pop删除是随机删除集合中的元素 如果set1没有元素讲程序报错
  In [44]: set1.pop()
  Out[44]: 1

  In [45]: set1
  Out[45]: {2, 3, 4}
  ```
- discard

  ```python
  In [47]: set1 = {1,2,3,4}
  # 使用discard删除 如果元素存在 直接删除 如果元素不存在 不做任何操作
  In [48]: set1.discard(2)

  In [49]: set1
  Out[49]: {1, 3, 4}

  ```

### 删除重复的元素

- 删除字符串中的元素

  ```python
  In [2]: set1 = set("hello")

  In [3]: set1
  Out[3]: {'e', 'h', 'l', 'o'}

  In [4]: set2 = set("google")

  In [5]: set2
  Out[5]: {'e', 'g', 'l', 'o'}
  ```

- <font color='red'><b>面试题:删除列表中的重复元素</b></font>

  ```python
  In [6]: list1 = [1, 2, 2, 3, 4, 1, 6, 3]

  In [7]: set(list1)
  Out[7]: {1, 2, 3, 4, 6}
  ```

### 交集、并集和差集

- 交集

  ```python
  In [9]: set1 = {1, 2, 3, 4}

  In [10]: set2 = {3, 4, 5, 6}

  In [11]: set1 & set2
  Out[11]: {3, 4}
  ```
- 并集

  ```python
  In [13]: set1 = {1, 2, 3, 4}

  In [14]: set2 = {3, 4, 5, 6}

  In [15]: set1 | set2
  Out[15]: {1, 2, 3, 4, 5, 6}
  ```
- 差集

  ```python
  In [17]: set1 = {1, 2, 3, 4}

  In [18]: set2 = {3, 4, 5, 6}

  In [19]: set1 - set2
  Out[19]: {1, 2}
  ```
