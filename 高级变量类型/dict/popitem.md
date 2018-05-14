# popitem

| 语法    | 用法     | 描述|
| :------------- | :------------- |:------------- |
|popitem|dict.popitem()|随机删除一个键值对，返回删除的键值对|

实例:
```python
In [69]: infos = {"name": "zhangsan", "age": 18, "gender": "男"}

In [70]: infos.popitem()
Out[70]: ('gender', '男')

In [71]: infos
Out[71]: {'age': 18, 'name': 'zhangsan'}
```
