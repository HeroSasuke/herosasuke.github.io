# in

|运算符|Python 表达式|结果|描述|支持的数据类型|
| :--| :--| :--|:--|:--|
|in	|3 in (1, 2, 3)|	True	|元素是否存在	|字符串、列表、元组、字典|


<font color='red'><b>注意，in在对字典操作时，判断的是字典的键</b></font>
<br>


实例：

```python
In [14]: "h" in "hello"
Out[14]: True

In [15]: "x" in "hello"
Out[15]: False

In [16]: 1 in [1, 2, 3, 4]
Out[16]: True

In [17]: 5 in [1, 2, 3, 4]
Out[17]: False

In [18]: 1 in (1, 2, 3, 4)
Out[18]: True

In [19]: 5 in (1, 2, 3, 4)
Out[19]: False

In [20]: "name" in {"name": "zhangsan", "age": 18}
Out[20]: True

In [21]: "gender" in {"name": "zhangsan", "age": 18}
Out[21]: False
```
