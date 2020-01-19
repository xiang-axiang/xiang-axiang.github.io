## 欢迎来到菜狗高启翔的个人博客

You can use the [editor on GitHub](https://github.com/xiang-axiang/xiang-axiang.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

#近期任务完成情况
 -http协议学完了，主要还是有个别专业名词不懂，不过正在查找资料，周天下午就能完成
 -MySQL数据库正在B站听课，买的《MySQL必知必会》也到了，只不过我在官网下载MySQL很奇怪，下载速度会越来越慢，不知道为什么。
 -那个。。。我是真的不会调主题了，你的主题真的nice，我在网上找的教程我试了不少，总是卡在用hexo和git建立新主题文件夹的时候。

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
喵喵喵？
我似乎把学习进度写到不该写的地方了......
不过问题不大，把它留着，做一个警示吧

#### 一个闲的没事儿干整的代码，应该能简化好多
```markdown
#include<stdio.h>
#include<stdlib.h>
#include<time.h>

void plus();
void sub();
void mul();
void temp();

void menu()
{
	printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n");
	printf("欢迎小朋友和我一起学习算数，细心作答，你是最棒的。加油哦!");
	printf("\n");                                                  
	printf("1.加法\n");
	printf("2.减法\n");
	printf("3.乘法\n");
	printf("4.除法\n");
	printf("0.退出\n");
    printf("\n");
    printf("赶快选择你要学习的内容吧!其中,每类按难易程度均有三个关卡");
	printf("\n");
	printf("$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$-$\n");
}
void plus1()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第一关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{
		printf("%d",m=rand()%10);
		printf("+");
		printf("%d",n=rand()%10);
		printf("=");
		total=m+n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void plus2()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第二关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{
	do{
		m=rand()%100;
	    n=rand()%10;
	}
	while(m<10);
		printf("%d",m);
		printf("+");
		printf("%d",n);
		printf("=");
		total=m+n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void plus3()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第三关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{
	do{
		m=rand()%100;
	    n=rand()%100;
	}
	while(m<=n||m<10||n<10);
		printf("%d",m);
		printf("+");
		printf("%d",n);
		printf("=");
		total=m+n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void plus()
{
	int i;
	plus1();
	printf("是否继续挑战?Y(1)/N(0):");
	scanf("%d",&i);
	if(i==1)
		plus2();
	else
		return;
	i=0;
	printf("是否继续挑战?Y(1)/N(0)");
	scanf("%d",&i);
	if(i==1)
		plus3();
	else
		return;
}
void sub1()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第一关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k){
	do
	{
		m=rand()%10;
	    n=rand()%10;
	}
	while(m<=n);
		printf("%d",m);
		printf("-");
		printf("%d",n);
		printf("=");
		total=m-n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
  			  printf("恭喜通关!继续努力哦!\n");
    }
}
void sub2()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第二关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{
	do{
		m=rand()%100;
	    n=rand()%10;
	}
	while(m<10);
		printf("%d",m);
		printf("-");
		printf("%d",n);
		printf("=");
		total=m-n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void sub3()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第三关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{do{
		m=rand()%100;
	    n=rand()%100;
	}while(m<=n||m<10||n<10);
		printf("%d",m);
		printf("-");
		printf("%d",n);
		printf("=");
		total=m-n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void sub()
{
	int i;
    sub1();
	printf("是否继续挑战?Y(1)/N(0):");
	scanf("%d",&i);
	if(i==1)
		sub2();
	else
		return;
	i=0;
	printf("是否继续挑战?Y(1)/N(0)");
	scanf("%d",&i);
	if(i==1)
		sub3();
	else
		return;
}
void mul1()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第一关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{
		printf("%d",m=rand()%10);
		printf("*");
		printf("%d",n=rand()%10);
		printf("=");
		total=m*n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void mul2()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第二关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{do{
		m=rand()%100;
	    n=rand()%10;
	}while(m<10);
		printf("%d",m);
		printf("*");
		printf("%d",n);
		printf("=");
		total=m*n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void mul3()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第三关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{do{
		m=rand()%100;
	    n=rand()%100;
	}while(m<=n||m<10||n<10);
		printf("%d",m);
		printf("*");
		printf("%d",n);
		printf("=");
		total=m*n;
        loopa:scanf("%d,&s");
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void mul()
{
    int i;
	mul1();
	printf("是否继续挑战:Y(1)/N(0)");
	scanf("%d",&i);
	if(i==1)
		mul2();
	else
		return;
	i=0;
	printf("是否继续挑战?Y(1)/N(0)");
	scanf("%d",&i);
	if(i==1)
		mul3();
	else
		return;
}
void temp1()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第一关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d,&k");
	while(count<0.9*k)
	{do{
		m=rand()%10;
		n=rand()%10;
	}while(n==0||m%n!=0);
		printf("%d,m=rand()%10");
		printf("/");
		printf("%d,n=rand()%10");
		printf("=");
		total=m/n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void temp2()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第二关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d,&k");
	while(count<0.9*k)
	{
	do{
		m=rand()%100;
	    n=rand()%10;
	}
	while(n==0||m<10||m%n!=0);
		printf("%d",m);
		printf("/");
		printf("%d",n);
		printf("=");
		total=m/n;
        loopa:scanf("%d",&s);
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void temp3()
{
	int count=0,m,n,s=0,total,k=0;
	printf("欢迎你来到第三关!\n");
	printf("请先设定本关题目的数量:");
	scanf("%d",&k);
	while(count<0.9*k)
	{do{
		m=rand()%100;
	    n=rand()%100;
	}while(n==0||n<10||m<10||m%n!=0);
		printf("%d",m);
		printf("/");
		printf("%d",n);
		printf("=");
		total=m/n;
        loopa:scanf("%d,&s");
			  if(s==total)
			  {
				  printf("答对了,你真聪明!\n");
				  count++;
			  }
			  else 
			  {
				  printf("呜呜呜，答错了,再仔细算一遍吧\n");
				  goto
					  loopa;
			  }
			  printf("恭喜通关!继续努力哦!\n");
	}
}
void temp()
{
	int i;
    temp1();
	printf("是否继续挑战?Y(1)/N(0):");
	scanf("%d",&i);
	if(i==1)
		temp2();
	else
		return;
	i=0;
	printf("是否继续挑战?Y(1)/N(0)");
	scanf("%d",&i);
	if(i==1)
		temp3();
	else
		return;
};
int main()
{
	void menu();
	int i;
	do{
		menu();
		printf("请输入:");
	    scanf("%d",&i);
	    switch(i)
		{
		case 1:plus();break;
		case 2:sub();break;
		case 3:mul();break;
		case 4:temp();break;
		case 0:break;
		}
		printf("\n");	
	}
	while(i!=0);
	printf("\n");
	return 0;
}
```


# 近期任务完成情况（一）
### 一
 -http协议学完了，主要还是有个别专业名词不懂，不过正在查找资料，周天下午就能完成
### 二
 -MySQL数据库正在B站听课，买的《MySQL必知必会》也到了，只不过我在官网下载MySQL很奇怪，下载速度会越来越慢，不知道为什么。
### 三
 -会写博客了....这个应该也算是进度吧...【乖巧.jpg】
### 四
 -那个。。。我是真的不会调主题了，你的主题真的nice，我在网上找的教程我试了不少，总是卡在用hexo和git建立新主题文件夹的时候。
### 五
 -虽然你没要求，但是放假前你让我自学一下ps和xd，ps我跟着软件里的教程，还剩几个，应该算是入门了吧。xd不算太难，我在B站上看了些视频，实际操作了一下，
感觉凑合，目前水平应该跟用c写hello world一个层次吧.......【对不起！我丢脸了！最近研究GitHub和MySQL比较多】

# 近期任务完成情况（二）
##### （emmmmm，这周似乎并没有什么特别的进度）
### 一
 -胡佬你给我发的代码确实需要时间消化，目前正在B站听小甲鱼的课，不知道听完后能不能懂python和网站搭建的关系...
### 二
 -我在想需不需要学习spl...于是我从这周3开始看spl...然后我意识到自己似乎同时学的有点多，然后停下了spl...

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/xiang-axiang/xiang-axiang.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
