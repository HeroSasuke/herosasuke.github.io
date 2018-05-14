# not in

|运算符|Python 表达式|结果|描述|支持的数据类型|
| :--| :--| :--|:--|:--|
|not in	|4 not in (1, 2, 3)|	True|	元素是否不存在	|字符串、列表、元组、字典|

实例：

```python
In [25]: "h" not in "hello"
Out[25]: False

In [26]: "x" not in "hello"
Out[26]: True

In [27]: 1 not in [1, 2, 3, 4]
Out[27]: False

In [28]: 5 not in [1, 2, 3, 4]
Out[28]: True

In [29]: 1 not in (1, 2, 3, 4)
Out[29]: False

In [30]: 5 not in (1, 2, 3, 4)
Out[30]: True

In [31]: "name" not in {"name": "zhangsan", "age": 18}
Out[31]: False

In [32]: "gender" not in {"name": "zhangsan", "age": 18}
Out[32]: True
```
