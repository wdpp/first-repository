# first-repository
这是c-语言学习的仓库
//数据类型的学习；

//包含一个stdio.h的文件
//std-标准；standard-input-output
#include "stdio.h"

//%d-打印整型
//%c-打印字符
//%f-打印浮点数字-打小数
//%p-以地址的方式打印
//%x-打印16进制数字
//int main()
//{
//	//char-字符类型
//	//char ch ='A';//char向内存申请空间ch
//	//printf("%c\n",ch);//%c打印字符格式的数据
//	//
//	//两种类型不能同时存在？？？
//	
//	//short int-短整型
//	//int-整型
//	//long int 长整型
//	//long long int 长长整型
//	//int age = 20;
//	//printf("%d\n",age);//%d-打印整型十进制数据
//
//	float f=5.0;
//	printf("%f\n",f);
//
//	/*double d=3.14;
//	printf("%lf\n",d);*/
//
//	return 0;
//}
//
//int main()
//{
//	//每个类型的大小
//	//计算机的单位：bit-比特位--一个比特位存放一个二进制位
//
//	printf("%d\n",sizeof(short));//2字节--可表示2的16次方的（状态）范围，1字节=8比特；最小是0；最大值：2^16-1=65535
//	printf("%d\n",sizeof(int));//4
//	printf("%d\n",sizeof(long));//4or8--c语言标准sizeof（long）>=sizeof（int）
//	printf("%d\n",sizeof(long long));//8
//	printf("%d\n",sizeof(char));//1
//	printf("%d\n",sizeof(float));//4
//	printf("%d\n",sizeof(double));//8
//
//	return 0;
//}

int main()
{
	//年龄20岁
	short age=20;//向内存申请2个字节=16bit位，用来存放20；

	return 0;
}
