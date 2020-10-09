# first-repository
这是c-语言学习的仓库
#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
////关键字
//int main()
//{
//	register int a=10;//把a定义成寄存器变量，访问的时候会变快
//	//int 等价于signed int;int定义的变量是有符号的
//	//struct--结构体关键字
//	//自己定义的变量名字不可以是关键字
//
//	printf("%d\n",a);
//	return 0;
//}

//int main()
//{
//	//typedef -类型定义--类型重定义
//	//张三--小三--
//	typedef unsigned int u_int;//把unsigned int重新定义为u_int
//	unsigned int num=20;
//	u_int num2=20;//和num类型一样
//	return 0;
//}

////1、static 修饰局部变量
////局部变量的生命周期变长，再次调用不销毁
////2、static 修饰全局变量
//改变了变量的作用域-让静态的全局变量只能在自己所在的源文件内部使用
//出了源文件就无法再使用了
//3、static 修饰函数
//也是改变了函数的作用域--表达不够准确
//static 修饰函数改变了函数的连接属性
//int 外部链接属性-》static int内部链接属性

//void test()
//{
//	/*int a=1;*/
//	static int a=1;//a是一个静态的局部变量
//	a++;
//	printf("a=%d\n",a);
//}
//int main()
//{
//	int i=0;
//	while (i<5)
//	{
//		test();
//		i++;
//	}
//	return 0;
//}
//int main()
//{
//	//extern --声明外部符号的
//	extern int g_val;//g_val 的值在另外的源文件add.c中定义了
//	printf("%d\n",g_val);
//	
//	return 0;
//}

//extern int ADD(int,int);
//int main()
//{
//	int a=20;
//	int	b=10;
//	int sum=ADD(a,b);
//	printf("sum=%d\n",sum);
//	return 0;
//}


////定义标识符常量
////#define Max 100
////可以定义宏-带参数
//
////函数的实现
//int Max(int x,int y)
//{
//	if(x>y)
//		return x;
//	else
//		return y;
//
//}
////宏的实现
//#define MAX(X,Y)(X>Y?X:Y)
//int main()
//{
//	/*int a=Max;*/
//	int a=10;
//	int b=16;
//	//函数
//	int max=Max(a,b);
//	printf("max=%d\n",max);
//	//宏的方式
//	max=MAX(a,b);
//	//max=(a>b?a:b);
//	printf("%d\n",max);
//	return 0;
//}

