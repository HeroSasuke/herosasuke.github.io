# extend

|语法|用法|描述|
|:|:|:|
|extend|list1.extend(list2)|通过extend可以将另一个集合中的元素逐一添加到列表中|

实例:

```python
In [62]: name_list = ["zhangsan", "lisi"]

In [63]: age_list = [18, 19]

In [64]: name_list.extend(age_list)

In [65]: name_list
Out[65]: ['zhangsan', 'lisi', 18, 19]
```
