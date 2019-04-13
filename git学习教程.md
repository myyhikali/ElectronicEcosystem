# git学习教程
>git的来源

Git 是由 Linux 之父 Linus Tovalds 为了更好地管理linux内核开发而创立的分布式版本控制／**软件配置管理软件**。

>mac+vscode+git

1. 建立属于自己GitHub的密钥

    命令：ssh-keygen -t rsa -C 31601136@stu.zucc.edu.cn
    
    -C后面是自己GitHub的邮箱
2. 将SSH key贴到GitHub上
    
    当前我设置的ssh key放在/Users/mac/.ssh下的id_rsa
    
    拷贝 id_rsa.pub中的内容 
    
    在GitHub中的‘SSH and GPG keys’上新建一个NEW SSH key 并复制刚才的内容
    
    这样就在GitHub上创建好了一个SSH KEY
3. 测试是否连接上GitHub
    
    命令：ssh -T git@github.com

    出现You've successfully authenticated, but GitHub does not provide shell access.就表示已经连接成功了，**为自己的小成就鼓个掌**
4. 在本地配置GitHub

    命令1：git config --global user.name myyhikali
    其中myyhikali是我GitHub上的用户名

    命令2:config --global user.email 31601136@stu.zucc.edu.cn
    邮箱是注册GitHub时的邮箱

5. 创建一个GitHub仓库

    Create a new repository
6. 克隆Github远程仓库
    拷贝'Clone or download'中的SSH地址

    命令：git clone git@github.com:myyhikali/ElectronicEcosystem.git
7. 本地仓库上传Github

    在vscode上尝试上传文件至GitHub
    在vscode的TERMINAL中进入你在本地克隆好的仓库中

    ![picture](/Users/mac/Desktop/学科/跨平台脚本开发/电子生态系统/图片/ter.png)

    *将需要上传或修改的文件放在本地仓库上*

    ![picture](/Users/mac/Desktop/学科/跨平台脚本开发/电子生态系统/图片/po.png)

8. 结果展示

    ![picture](/Users/mac/Desktop/学科/跨平台脚本开发/电子生态系统/图片/show.png)

>参考文献

https://blog.csdn.net/qq_37747262/article/details/81750417 Mac+VS Code+Git+Github

https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000 Git教程
    
