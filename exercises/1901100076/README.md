# helloworld
#this is anne' 2nd day learning sharing
*notice 中英文字符的转换，中文字符会报错
#<<<<<<< master
#Day 3 计算器学习
Item 1 变量命名规则
    1.1 在使用标识符时，需要注意如下规则：
    标识符可以由字母、数字、下画线（_）组成，其中数字不能打头。
    标识符不能是 Python 关键字，但可以包含关键字。
    标识符不能包含空格。

    例如下面变量，有些是合法的，有些是不合法的：
    abc_xyz：合法。
    HelloWorld：合法。
    abc：合法。
    xyz#abc：不合法，标识符中不允许出现“#”号。
    abc1：合法。
    1abc：不合法，标识符不允许数字开头。
Item 2 else 语句
    2.1 每个else语句结束之后需要有：来结束，标准的语句
Item 3 字符串转换成数字
     3.1 输入的为字符串，进行运算需要转换成数字
#Day 4
Item 1 break用法
 break 用于完全结束一个循环，跳出循环体。
 
 1.1 while True:

    break
 当循环条件为真时，那么就停止，所以这个指令不返回任何东西。
 1.2 
 num = 0

 while num <= 10:

    if num == 5:

        break

    else:

        print(num)

        num += 1

 在if条件里面，当达到某个条件的时候，就进行停止。
Item 2  程序的逻辑性
  2.1 循环嵌套
   有循环嵌套，例如while ，for 才会进行循环的执行
   同时对于作用的范围非常重要，很强调逻辑性


