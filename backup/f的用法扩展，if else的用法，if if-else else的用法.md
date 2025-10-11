lf的用法扩展，if else的用法，if if-else else的用法


int main()
{
	int a = 0;
	scanf_s("%d", &a);
	if (a <= 10)
		printf("小于等于10\n");
	else if (a > 10 && a <= 20)
		printf("大于10小于等于20\n");
	else if (a > 20 && a <= 30)
		printf("大于20小于等于30\n");
	else if (a > 30 && a <= 40)
		printf("大于30小于等于40\n");
	else
		printf("大于40\n");

	return 0;
}


将 scanf 替换为 scanf_s，这是 Visual Studio 推荐的安全输入函数，可以避免缓冲区溢出等安全问题。6666
