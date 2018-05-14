# values

| 语法    | 用法     | 描述|
| :------------- | :------------- |:------------- |
|values|dict.values()|返回一个包含字典所有value的列表|

实例:

```python
In [20]: infos = {"name": "zhangsan", "age": 18, "gender": "男"}

In [21]: infos.values()
Out[21]: dict_values(['zhangsan', 18, '男'])

In [22]: valuelist = infos.values()

In [23]: valuelist
Out[23]: dict_values(['zhangsan', 18, '男'])
```
