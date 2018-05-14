# del

<table>
    <tr>
      <td><b>语法</b></td>
      <td><b>用法</b></td>
      <td><b>描述</b></td>
   </tr>
   <tr>
     <td>del</td>
     <td>del 列表[index] </td>
     <td>删除指定索引的数据</td>
  </tr>
</table>

实例:
```python
namelist = ["zhangsan", "lisi", "wangwu", "zhaoliu"]

del namelist[0]

print(namelist)
```

运行结果:
```
['lisi', 'wangwu', 'zhaoliu']
```
