int main()
{
	int a = 0;
	scanf_s("%d", &a);
	switch (a)//switch后面不能有分号,这个括号里面只能是整型或者字符型
	{
	case 1:	
	case 2:
	case 3:
	case 4:
	case 5:
	{
		printf("非周末\n");
		break;
	}
	
		
	case 6:
	case 7:
	{

		printf("周末\n");
		break;
	}

	default:
	
	printf("输入错误\n");
	break;






	  
	}




	return 0;
}