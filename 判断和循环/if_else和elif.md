# if_else和elif

## if_else

 想一想：在使用if的时候，它只能做到满足条件时要做的事情。那万一需要在不满足条件的时候，做某些事，该怎么办呢？

 答案: <font color='red'>if...if_else</font>

 ### if_else的使用格式:

  ```
  if 条件:
       满足条件时要做的事情1
       满足条件时要做的事情2
       满足条件时要做的事情3
       ...(省略)...
   else:
       不满足条件时要做的事情1
       不满足条件时要做的事情2
       不满足条件时要做的事情3
       ...(省略)...
  ```
- Demo:

  ```Python
  chePiao = 1 # 用1代表有车票，0代表没有车票
  if chePiao == 1:
      print("有车票，可以上火车")
      print("终于可以见到Ta了，美滋滋~~~")
  else:
      print("没有车票，不能上车")
      print("亲爱的，那就下次见了"）
  ```

  结果1：有车票的情况
  ```
  有车票，可以上火车
  终于可以见到Ta了，美滋滋~~~
  ```

  结果2：没有车票的情况
  ```
  没有车票，不能上车
  亲爱的，那就下次见了
  ```

### 练习题
要求：从键盘输入身高，如果身高没有超过150cm，则进动物园不用买票，否则需要买票。

分析:  
  - 从键盘输入身高,使用input函数，注意类型的转换
  - 判断身高是否超过150里面
  - 超过150买票
  - 不超过免费

答案:

  ```Python
  height = int(input("请输入您的身高:"))

  if height > 150:
      print("需要购票")
  else:
      print("不需要购票，请尽情的观赏吧")
  ```

结果1: 身高超过150cm

  ![](images/jie1.gif)

结果2: 身高没有超过150cm

  ![](images/jie2.gif)


## elif

问题:

if能完成当xxx时做事情

if-else能完成当xxx时做事情1，否则做事情2

如果有这样一种情况：当xxx1满足时做事情1；当xxx1不满足、xxx2满足时做事情2；当xxx2不满足、xxx3满足时做事情3，那该怎么实现呢？

答案: <font color='red'>elif</font>

### elif格式:

  ```
  if xxx1:
      事情1
  elif xxx2:
      事情2
  elif xxx3:
      事情3
  ```

说明:

- 当xxx1满足时，执行事情1，然后整个if结束

- 当xxx1不满足时，那么判断xxx2，如果xxx2满足，则执行事情2，然后整个if结束

- 当xxx1不满足时，xxx2也不满足，如果xxx3满足，则执行事情3，然后整个if结束

Demo：

  ```Python
  score = 77

  if score>=90 and score<=100:
      print('本次考试，等级为A')
  elif score>=80 and score<90:
      print('本次考试，等级为B')
  elif score>=70 and score<80:
      print('本次考试，等级为C')
  elif score>=60 and score<70:
      print('本次考试，等级为D')
  elif score>=0 and score<60:
      print('本次考试，等级为E')
  ```

### 注意点

-  <font color='red'>可以和``else``一起使用</font>

  ```
  if 性别为男性:
       输出男性的体重
       ...
  elif 性别为女性:
     输出女性的体重
       ...
  else:
     第三种性别的体重
       ...
  ```

  说明:
  - 当 “性别为男性” 满足时，执行 “输出男性的体重”的相关代码

  - 当 “性别为男性” 不满足时，如果 “性别为女性”满足，则执行 “输出女性的体重”的相关代码

  - 当 “性别为男性” 不满足，“性别为女性”也不满足，那么久默认执行else后面的代码，即 “第三种性别的体重”相关代码

- <font color='red'>elif必须和if一起使用，否则出错</font>

- <font color='red'>else 一般用在最后，即所有条件都不满足时使用</font>
