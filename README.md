# git_howto
User manual of GIT


vi.git/config
解决git push错误
The requested URL returned error:403 Forbidden while accessing

 

答案：私有项目，没有权限，输入用户名密码，后者远程地址采用这种类型：vi.git/config


将 


［Premote ＂origin＂］

       url=https://github.com/用户名/仓库名.git

修改为


［Premote ＂origin＂］

       url=https://用户名：密码@github.com/用户名/仓库名.git
--------------------- 
作者：Banana_D 
来源：CSDN 
原文：https://blog.csdn.net/qq1515312832/article/details/81185516 
版权声明：本文为博主原创文章，转载请附上博文链接！
