# setdefault

| 语法    | 用法     | 描述|
| :------------- | :------------- |:------------- |
|setdefault|dict.setdefault(key,value) |如果key存在，不会修改数据;如果key不存在，新建键值对|


实例:
```python
In [43]: infos = {"name": "zhangsan", "age": 18, "gender": "男"}

In [44]: infos.setdefault("name", "WangWu")
Out[44]: 'zhangsan'

In [45]: infos
Out[45]: {'age': 18, 'gender': '男', 'name': 'zhangsan'}

In [46]: infos.setdefault("classes", "顺义Python8期")
Out[46]: '顺义Python8期'

In [47]: infos
Out[47]: {'age': 18, 'classes': '顺义Python8期', 'gender': '男', 'name': 'zhangsan'}
```
