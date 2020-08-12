# first-repository
这是c-语言学习的仓库
#include<stdio.h>

////变量
//int num2=20;//全局变量-定义在代码块（{}）之外的变量；
//int num1=100;
//
//int main()
//{
//	int num1=10;//局部变量-定义在代码块（{}）之内的变量；
//	//局部变量和全局变量名字建议不要相同-容易误会产生BUG；
//	//局部变量和全局变量名字相同的时候局部变量优先；
//	printf("%d\n",num1);
//	return 0;
//}

//注意
//int main()
//{
//	{
//		int a=10;
//	}
//	printf("%d\n",a);//a是局部变量，不能再{}外使用。
//	return 0;
//}

//int main()
//{
//	//计算两个数的和；
//	int num1=0;//局部变量num1的作用域，它所在的代码块内；
//	int num2=0;
//	int sum=0;
//	//输入数据-使用输入函数scanf
//	scanf("%d%d",&num1,&num2);//取地址符号&
//	/*int sum=0;*///c语言语法规定，变量定义要在当前代码块最前面
//	sum=num1+num2;
//	printf("sum=%d\n",sum);
//
//	return 0;
//}
//int global=520;//全局变量的作用域是整个工程；
//void test()
//{
//	printf("test--%d\n",global);
//}
//int main()
//{
//	test();
//	printf("%d\n",global);
//	return 0;
//}

//两个文件
int main()
{
	//未声明的标识符
	//声明extern外部符号的
	extern int yangshaomin;//在define源文件里面定义的全局变量--全局变量的作用域是整个工程
	printf("杨绍敏年龄=%d\n",yangshaomin);
	return 0;
}
//局部变量的生命周期是：进入作用域生命周期开始，出作用域生命周期结束
//全局变量的生命周期是：整个程序的生命周期；
