#define _CRT_SECURE_NO_WARNINGS 1

#include<stdio.h>
#include <string.h>
//int main(){

	//int num1 = 0;
	//int num2 = 0;
	//int num = 0;
	//scanf("%d%d", &num1, &num2);
	//num = num1 + num2;
	//printf("%d", num);
	//int input = 0;
	//printf("你要好好学习吗？");
	//printf("1/0\n");
	//scanf("%d", &input);
	//if (input == 1)
		//printf("拿到好offer");


	//else
		//printf("回家种田");
	//int arr[10] = { 1,2,3,4,5,6,7,8,9,10 };
	//int i = 0;
	//while (arr[i] < 10)
	//{
	//	printf("%d ", arr[i]);
	//		i++;
	//}

	//return 0;
//}
	//int main() {
		//int a = 0;
		//int b =~a;//b是符号的整形

		//~--按（2进制）位取反
		//00000000000000000000000000000000
		//11111111111111111111111111111111
		//原码、反码、补码
		//负数在内存中储存的时候，储存的是二进制的补码
		// -2
		//10000000000000000000000000000010-原码
		//11111111111111111111111111111101-反码（负数不动）
		//11111111111111111111111111111110-补码（加1)
		//printf("%d\n", b);
	//	int a = 10;
	//	int arr[] = { 1,2,3,4,5,6 };
	//	printf("%d\n",sizeof(a));//4
	//	printf("%d\n",sizeof(int));//4
	//	printf("%d\n", sizeof(arr));//24
	//	printf("%d\n", sizeof(arr) / sizeof(int));//6
	//return 0;
	//}
//int main()
//{
//	int a = 10;
//	int b = ++a;//前置++,先使用，后++
//	int b = a++;//后置++,先++,后使用
//	printf("a=%d b=%d\n", a, b);
//		return 0;
//}
//int main()
//{
//	//真-非0
//	//假-0
//	//&&-逻辑与
//	//||-逻辑或
//	int a = 0;
//	int b = 5;
//	int c = a || b;
//	printf("c=%d\n", c);
//	return 0;
//
//	 }
//int main()
//{
//	int a = 10;
//	int b = -20;
//	int max=0;
//	max = (a > b ? a : b);
//	if (a > b)
//		max = a;
//	else
//		max = b;
//	return 0;
//
//
//}
//int add(int x, int y)
//{
//	int z = 0;
//	z = x + y;
//	return z;
//}
//int main()
//{
//
//	//int arr[10] = 0;
//	//arr[4];//[]-下标引用操作符
//	int a = 10;
//	int b = 20;
//	int sum = ADD(a, b);
//	return 0;
//} 
//int main()
//{
//	     int a = 10;//局部变量-自动变量（auto）
//		return 0;
//		}
//int main()
//{
//	//register int a = 10;//建议把a定义成寄存器变量
//	
//	unsigned int num = 20;
//	//struct - 结构体关键字
//	//union - 联合体//共用体
//	//typedef -类型定义-类型重定义
//	typedef unsigned int u_int;
//	unsigned int num = 20;
//	u_int num2 = 20;
//	return 0  ;
//}
//static 修饰局部变量
//局部变量的生命周期变长
//static修饰全局变量
//改变了变量的作用域—让静态的全局变量只能在自己所在的源文件内部使用
//出了源文件就没法在使用
//static修饰函数改变了函数链接属性
//外部链接属性—>内部链接属性
//声明外部函数
//extern int Add(int, int);
//int main()
//{
//	int a = 10;
//	int b = 20;
//	int sum = Add(a, b);
//	print("sum = %d\n", sum);
//	return 0;
//}
//int main()
//{
//	//extern - 声明外部符号的
//	extern int g_val;
//	printf("g_val=%d\n", g_val);
//	return 0;
//}
//void test()
//{
//	static int a = 1;//a是一个静态的局部变量
//	a++;
//	printf("a=%d\n", a);//2,3,4,5,6
//}
//int main()
//{
//	int i = 0;
//	while (i < 5) {
//		test();
//		i++;
//	}
//	return 0;
//		 
//}

//定义标识常量
//#define MAX 100
//#define 可以定义宏-带参数
//Max(int x, int y)
//{
//	if (x > y)
//		return x;
//	else
//		return y;
//}
//宏的定义
//#define MAX(X,Y)(X>Y?X:Y) 
//int main()
//{
//	//int a = MAX;
//	int a = 10;
//	int b = 20;
//	int max = Max(a, b);
//	printf("max=%d\n", max);
//	//宏的方式
//	max = MAX(a, b);
//	printf("max=%d",max);
//	return 0;
//}
//int main()
//{
//	int a = 10;
//	int*p = &a;//取地址
//	printf("%p\n", p);
//	*p = 20;//解引用操作符
//	printf("a=%d\n",a);
//	//有一种变量是用来存放地址的指针变量
//	//printf("%d\n", &a);
//	return 0;
//}
//int main()
//{
//	char ch = 'w';
//	char* pc = &ch;
//	printf("%d\n",sizeof(pc));
//	//*pc = 'a';
//	//printf("%c\n", ch);
//	return 0;
//}
//int main()
//{
////	int a = 10;//申请了四个字节的空间
////	//printf(" % p\n", &a);
////	int*p = &a;//p是一个变量-指针变量
////	//printf("%p\n", p);
////	*p = 20;//解引用操作符/间接访问操作符
////	printf("a=%d\n", a);
//	double d = 3.14;
//	double * pd = &d;
//	printf("%d\n", sizeof(pd));//32-4 64-8
//	/**pd = 5.5;
//	printf("%lf\n",d);
//	printf("%lf\n",*pd);*/
//	return 0; 
//	    
//}
//结构体
//char int double
//人=3.14
//'w'
//书-复杂对象
//名字+身高+年龄+身份证号码+...
//复杂对象--结构体--我们自己创造的类型

//创建一个结构体类型
struct Book
{
	char name[20];//C语言程序设计
	short price;//55

};
int main()
{

	//利用结构体1类型-创建一个该类型结构体变量
	struct Book b1 = { "C语言程序设计",55 };
	//strcpy(b1.name, "C++");//strcpy-string copy-字符串拷贝-库函数-string.h
	//printf("%s\n", b1.name);
	strcpy(b1.name, "1231");
	printf("%s\n", b1.name);
	//struct Book *pb = &b1;

	//利用pb打印出我的书名和价格 
	//. 结构体变量.成员
	//-> 结构体指针->
	//printf("%s\n", pb->name);
	//printf("%d\n", pb->price);
	//printf("%s\n", (*pb).name);
	//printf("%d\n", (*pb).price);
	//printf("书名：%s\n", b1.name);S
	//printf("价格：%d元\n", b1.price);
	//b1.price = 15;
	//printf("修改后的价格：%d元\n", b1.price);
	return 0;
}
