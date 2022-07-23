# EDU-Platform
这里是武科大生产实习项目。

<br>

## 开发中使用的工具

1. IDEA 2017
2. Navicat
3. Visual Studio Code
4. Github Desktop

<br>

GitHub仓库

![image](https://img2022.cnblogs.com/blog/2402449/202207/2402449-20220722200230515-2056657368.png)

<br>

## Github Desktop初步使用

![image](https://img2022.cnblogs.com/blog/2402449/202207/2402449-20220722200847947-1939960836.png)

我们在对仓库中的文件进行修改后，就可以打开GitHub Desktop，先输入“提交描述”——这是说明你这次的修改的原因和目的，然后“Commit to main”，再“Push Origin”。

当然了，没有“Commit to main”前，右上角那个区域是“Fetch Origin”，它的功能是从远处仓库拉取所有修改。

“Push Origin”和“Fetch Origin”的使用顺序应该没有影响。

当然了，安装Git环境是更好的选择，学习git，无论对学习还是工作都有很大的益处，大家不要畏麻烦。

安装了Git，我们就可以使用vs code或者idea的源代码管理功能，实现快速上传修改。

## GitHub访问慢的解决

进入”C:\Windows\System32\drivers\etc“路径下的`hosts文件，

修改GitHub相关域名解析，添加如下行

```
140.82.113.3 github.com
185.199.108.153 assets-cdn.github.com
```

上面的IP是通过 https://www.ipaddress.com/ 这个网站得到的

最后，cmd执行

`ipconfig/flushdns`

`ping github.com`

==这种方式，有时依然很慢甚至打不开==。

这时就需要`科学上网`了。大家应该都了解吧。

我用的igg谷歌助手插件，**会员**能翻出去。

需要插件地址的跟我说一下。

## 分组的问题

暂时不知。

项目有四个页面要做，可以分为两人小组，每组一个页面的前后端开发，

==记得自己新写的方法、变量等等都需加注释，不然别的小伙伴不知道==。

## 开发记录

启动Redis

`redis-server.exe redis.windows.conf`

![image](https://img2022.cnblogs.com/blog/2402449/202207/2402449-20220722150638633-1866454098.png)

<br>

`npm i`报错：Cannot read properties of null (reading 'pickAlgorithm')

npm cache clear --force

## Element UI

[布局](https://element.eleme.cn/#/zh-CN/component/layout)

[下拉菜单-DropDown](https://element.eleme.cn/#/zh-CN/component/dropdown)

[步骤条-Steps](https://element.eleme.cn/#/zh-CN/component/steps)

[对话框-Dialog](https://element.eleme.cn/#/zh-CN/component/dialog)

[文字提示-ToolTip](https://element.eleme.cn/#/zh-CN/component/tooltip)

[弹出框-Popover](https://element.eleme.cn/#/zh-CN/component/popover)

[气泡确认框-Popconfirm](https://element.eleme.cn/#/zh-CN/component/popconfirm)

[折叠面板-Collapse](https://element.eleme.cn/#/zh-CN/component/collapse)

[图标-icon](https://element.eleme.cn/#/zh-CN/component/icon)

## Vue.js

