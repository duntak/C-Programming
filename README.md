### 2014年秋 中科大C语言课 上机练习代码  

**课程信息**  
- 授课老师：郑重  
- 教材：  
  - 计算机程序设计(C语言版)　贾伯琪　顾为兵　苏仕华　张四海　何克东@编著 （课本）  
  - 计算机程序设计 学习指导与实践  贾伯琪@编著 （上机指导）  
- 开课时间：2014.9.9-2014.12.19  
- 上课形式：每周2次，4节C语言概念课，10.8开始每周一个晚上上机。  
- 作业考试：主要为上机作业，只有一次期末考是笔试(2014.12.28)  


**按照上机日期建立文件夹**  

日期    |               题目              |           内容
--------|---------------------------------|-----------------------------------  
141008　| 课本84页的习题1,2,3,5           | 数据类型、算术表达式的值  
141015  | 课本85页的习题4,6,9             | 逻辑表达式  
141021  | 课本112页的习题2,5,7及其他      | 选择结构、循环结构，switch,for,if  
141029  | 其他题目                        | 冒泡排序(及改进),选择排序,矩阵相乘,矩阵转置  
141105  | 上机指导109页7,8                | 字符串处理,二分法求根,最大公约数,最小公倍数,牛顿迭代法  
141112  | 课本165页17,194页6              | 字符串处理,约瑟夫环,伪随机数,字符串比大小  
141118  | 课本194页8,195页13,204页4       | 函数,指针,带参宏  
141126  | 课本256页5,7                    | 行指针,指针数组  
141203  | 课本257页习题13,14,17,279页1    | 函数指针,结构体  
141210  | 其他题目                        | 链表的建立（头插法和尾插法）,链表的插入和删除  
141217  | 其他题目                        | 文件的读入读出,文件的拷贝  
141228  | 上机指导235 综合测试题一,四     | 字符串处理,函数,结构体数组,链表,文件    


**部分代码的题目说明**  
- 141228  
  - **exam1_1.c** 求矩阵对角线元素的和，将矩阵转置  
  - **exam1_2.c** 结构体数组数据的输入、输出和排序  
  - **exam4_1.c** 求解数据的平均值、方差、均方差  
  - **exam4_2.c** 统计给定文本中特定单词的个数  
  - **exam4_3.c** 用尾插法建立链表，把链表的信息输出到文件中  
- 141217  
  - **file1.c** 从input1.txt文件中读入数据，头插法建立链表，并输出到output1.txt文件中  
  - **file2.c** 从键盘输入数据，尾插法建立链表，写入couple2.out，再从文件输出到显示屏  
  - **filecopy3.c** 用带参main函数复制文件，用fgetc,fputc实现文本复制部分  
  - **filecopy4.c** 用带参main函数复制文件，用fgets,fputs实现文本复制部分  
- 141210  
  - **createcpll1.c** 头插法建立链表，从键盘读入数据，并链表的数据输出到显示屏      
  - **createcpll2.c** 尾插法建立链表，从键盘读入数据，并链表的数据输出到显示屏   
  - **deletell.c** 可连续删除链表中的元素，在createcpll2.c中加一个删除的函数。  
  - **insertll.c** 向已排序好的链表中插入元素，在createcpll1.c中加入一个插入函数，并默认输入的是有序数据。  
- 141203  
  - **matrix_5x5.c** 课本257/13，用指针将5x5矩阵元素按要求进行处理  
  - **SelectSort.c** 选择排序，在matrix_5x5.c中作为 #include "SelectSort.c" 被引用  
  - **SortStr.c** 课本257/15，用指针实现“输入5个字符串，按从小到大顺序输出”  
  - **fun_pointer.c** 课本257/17，用指向函数的指针求几个函数的定积分  
  - **struct_book.c** 课本279/1，声明一个图书相关的结构体，并输入输出信息  
- 141126 
  - 略    
- 141118  
  - **reverse_str.c** 课本194/8，函数实现字符串反序输出  
  - **score.c** 课本195/13，不同的函数实现数据处理，如求平均数、方差  
  - **macros_with_arguments.c** 课本204/4，定义一个带参宏，实现参数值互换  
  - **char_pointer.c** 字符指针与行指针的学习  
  - **int_pointer.c** 行指针 (*p)[N] 的学习  
- 141112  
  - **Josephus.c** 课本165/17，约瑟夫问题：http://en.wikipedia.org/wiki/Josephus_problem  
  - **atof.c** 课本194/6，函数实现“将数字字符串转换成等价的双精度浮点数”  
  - **strcompare.c** 输入两个字符串，比大小。输出为"a > b"的格式  
  - **strcompare#.c** 比较scanf,getchar,gets在输入字符串上面的不同，功能与strcompare.c相同  
  - **pseudorandomness.c** 写一个随机数生成函数，并把生成的随机数组排序输出。  
- 141105  
  - **Bisection.c** 用二分法求解方程 2x^3+4x^2+3x-6 = 0 的近似解  
  - **Newton.c** 用牛顿法求解方程 2x^3+4x^2+3x-6 = 0 的近似解  
  - **LCMandHCD.c** 输入两个自然数，求它们的最大公因数和最小公倍数  
  - **WordNum.c** 输入语句，判断单词的个数：用了字符数组以及很麻烦的方法。  
  - **WordNum#.c** 输入语句，判断单词的个数：引入ischar函数，巧妙的解法。  
- 141029  
  - **BubbleSort.c** 冒泡排序  
  - **BubbleSort#.c** 优化版的冒泡排序（指优化了一点点= =）  
  - **SelectionSort.c** 选择排序  
  - **BinarySearch.c** 选择排序后，用二分搜索  
  - **MatrixMul.c** 输入两个矩阵，实现矩阵乘法，并输出结果  
  - **Transpose.c** 输入矩阵，输出它的转置矩阵  
  - **Transpose#.c** 输入矩阵，求出它的转置矩阵，并输出  
- 141021
  - **9x9talbe.c** 课本112/5，用for循环结构，输出九九乘法表  
  - **calcularPI.c** 课本112/7，根据已知公式，求PI近似值  
  - **PIT.c** 课本112/2，用switch语句，求不同情况下的个人所得税金额  
  - **FindRoot.c** 计算一元二次方差在复数域上的根  
- 141015 
  - **Fahrenheit2Celsius.c** 华氏温度到摄氏温度的转换小程序  
- 141008  
  - 课本习题，略

   
**友情链接 & 特别感谢**  
课程评价和相册：可以看[这里](http://home.ustc.edu.cn/~jenny42/c-programming.html)。
感谢助教赵聪：https://github.com/zhaocong89  
我们可以到这里看~alkaid的代码：http://home.ustc.edu.cn/~alkaid/  
也可以看boj的代码：https://github.com/bojieli  
还有cuihao的代码：http://cuihaopy.appspot.com/?p=105001  


**发现错误**  
如果你发现任何错误，不管是代码错误、注释错误、信息错误，都欢迎告诉我
<!--
这份markdown大概花了整整两个半天的时间来写，顺便也把自己的上机代码大体看了一遍。  
发现之前很多文件命名不合理，如用特殊字符，  
然后注释里有很多英文语法错误...哭晕  
-->
