# CCF 试题《小明上学》
网上的代码借鉴 自己理解后修改了极少部分
以作参考：
```
#include<iostream>
using namespace std;
int main()
{
	int r,y,g;
	cin>>r>>y>>g;
	int n;
	cin>>n;
	int input[n][2];
	int k,t;
	int result=0;
	for(int i=0;i<n;i++)//负责输入 
	{
	cin>>k>>t;
	input[i][0]=k;
	input[i][1]=t;	
	}
	for(int i=0;i<n;i++)//负责计算用时 
	{
		if(input[i][0]==0)//通过道路
		{
		result=result+input[i][1];
		}
		else if(input[i][0] == 1)//碰到绿灯，碰到黄灯等待时间之后再加上红灯的总共时长，碰到红灯加上时长
		{
        result = result + input[i][1];
        }
		else if(input[i][0]==2)
		{
		result=result+input[i][1]+r;
		}	
		else if(input[i][0]==3)
		{
		result=result; 
		}
			
	}
	cout<<result<<endl;
	return 0;
} 
```
