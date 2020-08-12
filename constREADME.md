# first-repository
这是c-语言学习的仓库
#define _CRT_SECURE_NO_WARNINGS 1//源文件第一行，添加方式在https://www.bilibili.com/video/BV1qv411i7YS?p=3，p3-20分钟。

#include<stdio.h>

//常量
//int main()
//{
//	////const-常属性
//	//const int n=10;//n是变量，但是又有常属性，所以我们说n是常变量。
//	//int arr[n]={0};
//	//int arr[10]={0};
//
//
//	////const 修饰的常变量
//	//const int num=4;
//	////int num=4;
//	//printf("%d\n",num);
//	// num=0;//前面是const int就不允许改了
//	//printf("%d\n",num);
//	//字面常量
//	//3,100,3.14
//
//	return 0;
//}

//# define MAX 10 //#define 定义的标识符常量
//int main()
//{
//	int arr[MAX]={0};
//	printf("%d\n",arr[9]);
//	printf("%d\n",MAX);
//	return 0;
//}

//枚举常量
//枚举=一一列举
//例如，性别：男、女、保密；三原色：红、黄、蓝

//枚举关键-enum
enum sex
{
	male,
	female,
	secret
};
//male,female,secret-枚举常量
int main()
{
	enum sex s=male;
	printf("%d\n",s);//0
	printf("%d\n",male);//0
	printf("%d\n",female);//1
	printf("%d\n",secret);//2
	return 0;
}//
