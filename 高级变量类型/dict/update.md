# update

| 语法    | 用法     | 描述|
| :------------- | :------------- |:------------- |
|update|dict1.update(dict2)|将字典2的数据合并到字典1|

实例:

```python
In [53]: dict1 = {"name":"zhangsan", "age": 19}

In [54]: dict2 = {"gender": "男", "classes": "顺义Python8期"}

In [55]: dict1.update(dict2)

In [56]: dict1
Out[56]: {'age': 19, 'classes': '顺义Python8期', 'gender': '男', 'name': 'zhangsan'}

```
