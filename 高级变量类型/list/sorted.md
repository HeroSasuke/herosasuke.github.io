# sorted

<table>
    <tr>
        <td><b>语法</b></td>
        <td><b>用法</b></td>
        <td><b>描述</b></td>
   </tr>
    <tr>
        <td>sorted()</td>
        <td>sorted(list)</td>
        <td>返回一个新的进行了排序的列表，原来的列表不变</td>
    </tr>    
</table>

实例:
  ```python
  namelist = [4, 2, 1, 5, 10, 9, 8, 6]

  new_list = sorted(namelist)

  print(namelist)
  print(new_list)
  ```
运行结果:

  ```python
  [4, 2, 1, 5, 10, 9, 8, 6]
  [1, 2, 4, 5, 6, 8, 9, 10]
  ```
