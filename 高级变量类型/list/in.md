# in

<table>
    <tr>
        <td><b>语法</b></td>
        <td><b>用法</b></td>
        <td><b>描述</b></td>
   </tr>
   <tr>
      <td>in</td>
      <td>if x in list</td>
      <td>in（存在）,如果存在那么结果为true，否则为false</td>
   </tr>
</table>

实例:
```python
namelist = ["zhangsan", "lisi", "wangwu", "zhaoliu"]

name = input("请输入要查询的名字:")

if name in namelist:
    print("姓名：%s 存在列表当中" % name)
else:
    print("要查找的姓名：%s 不存在列表当中" % name)
```
运行结果:

![](../images/in.gif)
