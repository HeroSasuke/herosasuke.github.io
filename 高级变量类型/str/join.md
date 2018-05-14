# join

|语法|用法|描述|
|:|:|:|
|join|mystr.join(str)|mystr 中每个元素后面插入str,构造出一个新的字符串|

实例:

```python
In [45]: str = " "

In [46]: li = ["my", "name", "is", "python"]

In [47]: str.join(li)
Out[47]: 'my name is python'

In [48]: str = "_"

In [49]: str.join(li)
Out[49]: 'my_name_is_python'
```
