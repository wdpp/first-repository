# first-repository
这是c-语言学习的仓库
#define _CRT_SECURE_NO_WARNINGS 1//源文件第一行，添加方式在https://www.bilibili.com/video/BV1qv411i7YS?p=3，p3-20分钟。

#include<stdio.h>
#include<string.h>
//字符串类型
//int main()
//{
//	//数据在计算机上存储的时候，存储的是二进制
//	//#$%^&
//	//ASCII 编码
//	//ASCII 码值
//
//	//"";//空字符串，""之间的东西叫字符串
//	char arr1[]={97,'b','c',0};
//	char arr3[]={'a','b','c','\0'};
//	char arr2[]="abc";//数组
//	//"abc"---'a' 'b' 'c' '\0',--'\0'字符串的结束标志
//	//'a'-97;'b'-98;'c'-99
//	printf("%s\n",arr1);
//	printf("%s\n",arr2);
//	printf("%s\n",arr3);
//
//	return 0;
//}

//int main()
//{
//	char arr1[]={'a','b','c'};//长度是个随机值
//	char arr3[]={'a','b','c','\0'};//\0-转义字符-是个停止标志，不算在字符长度内
//	char arr2[]="abc";
//	printf("%d\n",strlen(arr1));//strlen--string length--计算字符串长度的
//	printf("%d\n",strlen(arr2));
//	printf("%d\n",strlen(arr3));
//	return 0;
//}

//转义字符-转变原来的意思
//int main()
//{
//	printf("abcn");
//	printf("abc\n");
//	return 0;
//}

//int main()
//{
//	//printf("c:\test\start_c...test.c\n");//假设路径为c:\test\start_c...test.c
//	////\t--水平制表符--类似table键
//	//printf("c:\\test\\start_c...test.c");//\转义原来的\
//
//	/*printf("%c\n",''');*/
//    printf("%c\n",'\'');
//	return 0;
//}

int main()
{
	printf("%d\n",strlen("c:\test\32\test.c"));//c-:-\t-e-s-t-\32-\t-e-s-t-.-c=13
	printf("c:\test\32\test.c");
	//\32--32是2个8进制数字
	//\32--32作为8进制代表的那个十进制数字，作为ASCII码值，对应的字符
	//\32--32--十进制-26-作为ASCII码值代表的字符
	return 0;
}
//\x+数字，数字转化成16进制
//\+数字，数字转化成8进制
