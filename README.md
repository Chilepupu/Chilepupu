- 👋 Hi, I’m @Chilepupu
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
int main()
{
	//a b c d e是接收名次的变量
	int a = 0;
	int b = 0;
	int c = 0;
	int d = 0;
	int e = 0;
	for (a = 1; a <= 5; a++)
	{
		for (b = 1; b <= 5; b++)
		{
			for (c = 1; c <= 5; c++)
			{
				for (d = 1; d <= 5; d++)
				{
					for (e = 1; e <= 5; e++)
					{
						//因为五位选手中只有半句话是真的，所以0+1=1表示半句是真的
						if (
							((b == 2) + (a == 3) == 1) &&
							((b == 2) + (e == 4) == 1) &&
							((c == 1) + (d == 2) == 1) &&
							((c == 5) + (d == 3) == 1) &&
							((e == 4) + (a == 1) == 1)
							)
							{
								//a*b*c*d*e=120是确保五个名次每个人都得到
						    	//如果用abcde不能相同的判断方法，那么就会编写15种!=没有效率
								if (a * b * c * d * e == 120)
									printf("A=%d B=%d C=%d D=%d E=d%\n", a, b, c, d, e);
							}
					}
				}
			}
		}
	}
	return 0;
}

<!---
Chilepupu/Chilepupu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
