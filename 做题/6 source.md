这是一道.git泄露的题目

![image-20240917224149925](C:\Users\29443\AppData\Roaming\Typora\typora-user-images\image-20240917224149925.png)



1. 目录扫描寻找到 .git （明显是git泄露）

    使用wegt 克隆git到本地

​        wget -r http://114.67.246.176:17920/.git

发现文件夹

![image-20240917223717734](C:\Users\29443\AppData\Roaming\Typora\typora-user-images\image-20240917223717734.png)

3.  使用git reflog 查看（如上图所示）
4.  对以上更改进行查看git show  【前面编号】

![image-20240917224318268](C:\Users\29443\AppData\Roaming\Typora\typora-user-images\image-20240917224318268.png)

完成任务

随后会进行整理对于git的使用方法