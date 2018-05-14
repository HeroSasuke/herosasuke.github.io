# index

<table>
    <tr>
        <td><b>语法</b></td>
        <td><b>用法</b></td>
        <td><b>描述</b></td>
   </tr>
    <tr>
        <td rowspan="2">index</td>    
        <td >list.index(object)</td>  
        <td>首次出现该数据时对应数据的索引</td>
    </tr>
    <tr>
        <td >list.index(object, start, stop)</td>  
        <td >start和stop都是设置索引，范围是[start, stop)</td>
    </tr>
</table>

### list.index(object)
- 首次出现该数据时对应数据的索引

- 实例:
  ```python
  namelist = ["zhangsan", "lisi", "wangwu", "zhaoliu"]

  index = namelist.index("lisi")

  print(index)
  ```
- 运行结果:
  ```
  1
  ```

### list.index(object, start, stop)
- start和stop都是设置索引，范围是[start, stop)
- 实例:
  ```python
  namelist = ["zhangsan", "lisi", "wangwu", "zhaoliu"]

  index = namelist.index("lisi", 0, 2)

  print(index)
  ```
- 运行结果:

  ```
  1
  ```
