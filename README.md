# Young-s-International-Bank
ATM self-service system of Chongqing University of Technology Branch
void loading()//虚假的加载界面
{
	int k=1;
	for(;k<3;k++)
	{
		system("cls");
		printf("|        请稍等.                                                     | \n");
		printf("|        加载中:   --                                                | \n");
		Sleep(200);system("cls");
		printf("|        请稍等..                                                    | \n");
		printf("|        加载中:   \\                                                | \n");
		Sleep(200);system("cls");
		printf("|        请稍等...                                                   | \n");
		printf("|        加载中:   ||                                                | \n");
		Sleep(200);system("cls");
		printf("|        请稍等....                                                  | \n");
		printf("|        加载中:   //                                                | \n");
		Sleep(200);system("cls");
		printf("|        请稍等.....                                                 | \n");
		printf("|        加载中:   --                                                | \n");
		Sleep(200);system("cls");
		printf("|        请稍等......                                                | \n");
		printf("|        加载中:   \\                                                | \n");
		Sleep(200);system("cls");
		printf("|        请稍等......                                                | \n");
		printf("|        加载中:   ||                                                | \n");
		Sleep(200);system("cls");
		printf("|        请稍等......                                                | \n");
		printf("|        加载中:   //                                                | \n");
		Sleep(200);system("cls");
	}
}
void show01()//登陆界面
{
	system("color 0c");
	printf("|****************************************************************************************| \n");Sleep(50);
	printf(" _________________________________________________________________________________________\n");Sleep(50);
	printf("|                     欢迎使用杨氏国际银行重工分行ATM自助存取款系统                      | \n");Sleep(50);
	printf("|");printf("  ");system("date/t");
	printf("|");printf("  ");system("time/t");
}
void show002()//输入账号界面
{
	printf("|请输入您的账户：                                                    | \n");Sleep(50);
	printf("|                                                                    | \n");Sleep(50);
}
void show02()//输入密码界面
{
	printf("|请输入您的密码：                                                    | \n");Sleep(50);
	printf("|                                                                    | \n");Sleep(50);
}
void show03()//管理员执行操作界面
{
	printf("|           管理员信息录入及操作                                     |\n");Sleep(50);
	printf("|欢迎：                                                              | \n");Sleep(50);
	printf("|    Administrator/管理员                                            | \n");Sleep(50);
	printf("|   请选择要执行的操作：                                             | \n");Sleep(50);
	printf("|   【1】添加账户                                                    | \n");Sleep(50);
	printf("|   【2】注销账户                                                        | \n");Sleep(50);
	printf("|   【3】冻结或解冻账户                                              | \n");Sleep(50);
	printf("|   【4】退出                                                               | \n");Sleep(50);
	printf("|   【0】关闭ATM机                                                    | \n");Sleep(50);
	printf("|   【10】查看所有用户情况                                           | \n");Sleep(50);

}
void show04()//用户执行操作界面
{
	printf("|欢迎：                                                                    | \n");Sleep(50);
	printf("|     Admin/用户                                                      | \n");Sleep(50);
	printf("|    请选择要执行的操作：                                        | \n");Sleep(50);
	printf("|    【1】修改密码                                                   | \n");Sleep(50);
	printf("|    【2】余额查询                                                   | \n");Sleep(50);
	printf("|    【3】存款                                                          | \n");Sleep(50);
	printf("|    【4】取款                                                          | \n");Sleep(50);
	printf("|    【5】转账                                                          |\n");Sleep(50);
	printf("|    【6】交易记录查询                                             |\n");Sleep(50);
	printf("|    【7】退卡                                                          | \n");Sleep(50);
	printf("|    【0】关闭ATM机                                                | \n");Sleep(50);
}
