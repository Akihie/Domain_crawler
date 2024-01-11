# Hello, folks! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">
## 这段时间喜欢上了玩博客，在注册域名的时候发现一个个查找比较慢，不好找到自己满意的域名，就想做个脚本来批量查询检索。但是自己也是个小趴菜，源码还有bug。希望也有大佬完善一下。
### 1.文件
#### 1.1 domain_a.py
  这个代码是使用万网的查询接口来实现的查询域名。
#### 1.2 domain_w.py
  这个代码是使用的py的whios库来实现的查询域名。
#### 1.3 random_y.py
  这个代码是生成域名的文件，随意更改后缀，前缀，位数，组成字母数字。
#### 1.4 2com.txt
  自己生成的一个2位纯字母后缀为.com的文件。可放心食用。
### 2.部署
  py文件跟txt文件放一个文件夹下就行。自己电脑运行，服务器，还是定时任务平台都可以。
### 3.问题
  domain_a.py文件运行的时候可能出现报错"API请求失败，返回码: None",无能为力解决。
  domain_w.py文件运行的时候可能出现报错"Error trying to connect to socket: closing socket - [Errno -3] Try again",也无能为力解决。

