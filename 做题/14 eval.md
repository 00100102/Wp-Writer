![image-20240918210425067](./assets/image-20240918210425067.png)



题目是一个php题目

![image-20240918210439974](./assets/image-20240918210439974.png)

这说明hello可以传入远程命令

我们构造payload，使用

http://114.67.175.224:18705/?hello=system(“cat flag.php")

不能够正常打印，于是我们尝试使用tac （反向打印这个文件内容）

于是得到flag



![image-20240918210624703](./assets/image-20240918210624703.png)
