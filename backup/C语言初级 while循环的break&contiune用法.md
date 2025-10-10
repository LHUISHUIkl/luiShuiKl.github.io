while循环中的break用法
 break的作用是永久终止循环语句。
int main()
{
	int a = 91;
	while (a <= 1919) // 去掉分号，保证while后是代码块
	{
		if (a == 1145)
			break; // 补全分号

		printf("%d\n", a);
		a++; // 补全分号
	}
	return 0;
}
GitHub Copilot 好用

while循环中contiune的用法
 continue的作用是跳过本次循环，继续下一次循环。

int main()
{
	int a = 91;
	while (a <= 114514)
	{
		if (a == 1145)
			continue;

		printf("%d\n", a);
		a++;
		
	}

	return 0;
}