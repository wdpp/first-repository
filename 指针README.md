# first-repository
这是c-语言学习的仓库
#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>

////指针
//int main()
//{
//	int a=10;
//	//&a;取地址
//	int* p=&a;//把a的地址存放在p
//	printf("%p\n",p);
//	printf("%p\n",&a);//%p打印地址
//	*p=20;//*-解引用操作符
//	printf("%d\n",a);
//	//有一种变量是用来存放地址的--指针变量
//
//
//	return 0;
//}

int main()
{
	char ch='W';
	char* pc=&ch;
	*pc='a';
	printf("%c\n",ch);
	printf("%d\n",sizeof(pc));//指针大小，单位字节，--32位平台，32bite--4字节，64位-8字节
	return 0;
}
