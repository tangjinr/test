#初始上传项目步骤

Web端：

1、新建仓库Repository


客户端：

1、鼠标右键项目选择Git Hash Here

2、初始化：git init

3.1、添加远程服务器：git remote add origin https://github.com/yourNmae/yourRepo.git

3.2、直接复制一个远程仓库到本地：git clone https://github.com/yourNmae/yourRepo.git

3.3、若远程仓库创建了README.md，相当于已经有过更改，则只需要拉下来：git pull https://github.com/yourNmae/yourRepo.git

4、将改动添加到暂存区：git add . 或者git add ./xx.jsp

5、提交：git commit -m "提交说明"

6、将本地更改推送到远程master分支：git push -u origin master


#再次上传提交

0、远程仓库有更改：git pull https://github.com/yourNmae/yourRepo.git

1、git add . 或者git add ./xx.jsp

2、git commit -m "提交说明"

3、git push origin master


大标题  
===================================  
  大标题一般显示工程名,类似html的\<h1\>
  
  你只要在标题下面跟上=====即可  
  
  
中标题  
-----------------------------------  
  中标题一般显示重点项,类似html的\<h2\>
  
  你只要在标题下面输入------即可  
  
  
### 小标题  
  小标题类似html的\<h3\>
  
  小标题的格式如下 ### 小标题
  
  注意#和标题字符中间要有空格  
  
### 单行文本框  
    这是一个单行的文本框,只要两个Tab再输入文字即可

### 多行文本框    
    这是一个有多行的文本框  
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可  
    这里你可以输入一段代码  
  
### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧  
    public class HelloWorld {
      public static void main(String[] args) {
        System.out.println("HelloWorld!");
      }
    }

### 链接  
1.[点击这里你可以链接到我的GitHub](https://github.com/tangjinr)

2.[点击这里你可以链接到百度](https://www.baidu.com)
  
### 文字被些字符包围  
> 文字被些字符包围  
>  
> 只要再文字前面加上>空格即可  
>  
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字  
> 但> 只能放在行首才有效  
  
### 文字被些字符包围,多重包围  
> 文字被些字符包围开始  
>  
> > 只要再文字前面加上>空格即可  
>  
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字  
>  
> > > > 但> 只能放在行首才有效  
  
### 特殊字符处理  
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可

你想换行的话其实可以直接用html标签\


# README.cd文件详细教程
[详细教程](http://blog.csdn.net/kaitiren/article/details/38513715 "点击进入")
