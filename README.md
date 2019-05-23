# t_test算法



# 遇到的问题 
1 窗口闪退问题的解决方案：https://blog.csdn.net/weixin_39278265/article/details/81865362  
2 c语言头文件转换成c++头文件  
改编成c++的头文件运行出错： error C2065: “M_PI”: 未声明的标识符  
解决方法：https://blog.csdn.net/liu_feng_zi_/article/details/84816763  
```
/* c语言的头文件
#include <stdio.h>
#define _USE_MATH_DEFINES
#include <math.h>
#define square(x) (x*x)
*/

// c++的头文件 
#include <iostream>
using namespace std;
#define _USE_MATH_DEFINES
#include <math.h>
#define square(x) (x*x)
```
3 读取TXT文件里的数据并赋值到数组https://zhidao.baidu.com/question/498754296.html  
4 double类型数据的输入和输出https://blog.csdn.net/u011415955/article/details/37322587  
