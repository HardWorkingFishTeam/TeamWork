# TeamWork
我在这里简单介绍一下git操作。

#### 1.安装GitHub桌面版

<img src="https://i.loli.net/2020/05/03/PBi8shH3LfOgR6n.png" alt="image-20200503170213595.png" style="zoom: 25%;" />

* [GitHub桌面版下载](https://desktop.github.com/)

* 一路next安装

* 在桌面新建TeamWork文件夹
* 打开GitHub桌面版

#### 2.克隆远程仓库

<img src="https://i.loli.net/2020/05/03/KIHChEZ8n5JDvFQ.png" alt="image-20200503193926091.png" style="zoom: 33%;" />

* Clone repository
* 选择团队项目

![image.png](https://i.loli.net/2020/05/03/5wVq7z4oWIunvkc.png)

* 等待

#### 新建自己的分支

<img src="https://i.loli.net/2020/05/03/NRj2XuPylKxGcv9.png" alt="image-20200503194230039.png" style="zoom:33%;" />

* 然后就在自己的分支中完成代码

#### 代码提交

* 红色部分为工作区

![image-20200503194508801.png](https://i.loli.net/2020/05/03/j3FbKioSE9ufCl6.png)

* 完成部分功能后对自己的工作内容进行注解，并提交到暂存区

![image-20200503194838557.png](https://i.loli.net/2020/05/03/N3BDZy9msiWCLvd.png)

```
注意:如果要推送到自己的分支，要注意上方master的按钮，将其修改为自己的分支
```

* 然后就可以发现有更新提示

![image-20200503194938895.png](https://i.loli.net/2020/05/03/DVk1HsYciaJfuNF.png)

```
push:将暂存区的内容推送到远程仓库
```

* 然后我们点击提交，完成后如下图所示。到此代码已经成功提交到我们自己的分支了

![image-20200503195032590.png](https://i.loli.net/2020/05/03/FEwQ1g8W4zpydo3.png)

```
Fetch:将远程仓库抓取到本地，也可以理解为将远程仓库的代码更新到本地
当前无可提交的内容，所以此按钮变成Fetch
```

#### 提交错误

![1588517618_1_.jpg](https://i.loli.net/2020/05/03/PrxBq2M4AvDoEet.png)

* 错误原因

```
提交的分支为master主分支，修改为原来的分支即可
```

#### 合并请求

* 提交后到自己的分支中发送推送合并请求

![微信截图_20200503231250.png](https://i.loli.net/2020/05/03/np4zuX6yZLGOkcl.png)

* 之后填写合并信息

![微信截图_20200503231753.png](https://i.loli.net/2020/05/03/4rMRC5HwuaWdhZ6.png)

* 之后等待管理员审核代码并解决冲突后即可