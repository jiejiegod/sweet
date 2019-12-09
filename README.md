## 大家好我叫任杰 
### 这是我的网页
[NO.1](http://jiege.xyz/vue/1.html)
[NO.2](https://jiege.xyz/vue/2.html)
[NO.3](https://jiege.xyz/vue/3.html)

#基本入学教程
##前置基本能力
>作为一名合格的**程序员**在学习任何编程语言前都必要熟练掌握两个基本技能：
- 一是基本的熟练键盘盲打，这是基本代码输入能力，打字速度太慢，代码输入效率就会太低。
* 打字速度提升可以通过金山打字通的每天坚持练习来提高。[金山打字通下载地址](https://www.51dzt.com/)
- 二是对英语的有一定的掌握程度，不一定是要能达到英语4-6级能力，但起码对常见的编程方面的用到的单词要熟练掌握。
* 英语水平的提高需要时间的积累，并非短期可以提高，靠谱的学习方法在于每天坚持学习一点点，慢慢提升单词量（每天把自己遇到的不认识单纯抄下来，通过金山词霸等类似学习软件学习读音和词意）和语感。
#常用基础编程工具类软件
##Visual Studio Code 入门
>VS Code是微软推出的新一代**免费开源**的现代化**轻量级**代码编辑器，支持几乎所有主流的开发语言的语法高亮、智能代码补全、自定义快捷键、括号匹配和颜色区分、代码片段、代码对比 Diff、GIT命令 等特性，支持插件扩展，并针对网页开发和云端应用开发做了优化。**VS Code**跨平台支持 Win、Mac 以及 Linux，运行流畅，可以算得上是微软的难得良心之作。
- VS Code 官方网址 [https://code.visualstudio.com/](https://code.visualstudio.com/)
![title](img/1.jpg)
##VS Code 基本功能介绍
![title](img/1.png)
##常用快捷键
Ctrl + Shift + E 资源管理器
Ctrl + Shift + F 搜索
Ctrl + Shift + G 源代码管理器
Ctrl + Shift + D 调试
Ctrl + Shift + X 插件扩展
F1 或 Ctrl+ Shift + p 打开命令面板
Shift + Alt + F 代码格式化
Ctrl+ F 查找
Ctrl+ H 查找替换
Ctrl+ N 新建文件
Ctrl+ S 保存
Alt + ↑ 或 Alt + ↓ 上下移动一行
Shift + Alt + ↑ 或 Shift + Alt + ↓ 向上向下复制一行
![title](img/2.jpg)
##扩展插件入门
![扩展插件的查找与安装：](img/2.png)
###常用的插件
- 中文语言包 Chinese (Simplified) Language Pack for Visual Studio Code
- MarkDown预览增强 Markdown Preview Enhanced
- 代码拼写检查器 Code Spell Checker
- 浏览器预览增强 open in browser
- 检查英文语句中的中文符号 sneak mark
- VS Code图标 vscode-icons
- 格式化代码工具 beautify
- HTML代码提示器 HTML Snippets
- CSS样式提升器 HTML CSS Support
- 各种皮肤主题 例如：One Dark Pro，Bimbo，Atom One Dark Theme
##MarkDown 入门
>**Markdown**是一种可以使用普通文本编辑器编写的比HTML更加简单易学的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式，同时MarkDown又能转换成HTML,PDF等多种格式。
##MarkDown基础语法
>以下是MarkDown的一些比较基础的语法，不同的MarkDown工具有更多更强大的语法功能实现。**在日常编写MarkDown文档过程中需要特别注意的是==中文符号和空格。==**
- 标题
>Markown的标题标记能显示出文章的结构。行首插入1-6个 # ，每增加一个 # 表示更深入层次的内容，对应到标题的深度由 1-6 阶。

#一级标题
##二级标题
###三级标题
####四级标题
#####五级标题
######六级标题
~~~  markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
~~~
- 文本加粗
##文本加粗
~~~ markdown
**文本加粗**
~~~
- 斜体
*斜体*
~~~ markdown
*斜体*
~~~
- 下划线
<u>下划线</u>
~~~ markdown
<u>下划线</u>
~~~
- 删除线
~~删除线~~
~~~ mark down
~~删除线~~ 
~~~
- 分割线
下面是一条分割线
***
~~~ markdown
下面是一条分割线
***
~~~
- 引用文本
>这是介绍MarkDown引用文本语法的文字。
~~~ markdown
>这是介绍MarkDown引用文本语法的文字。
~~~
- 符号列表或者数字列表
* 圆点符号列表
1.数字序号列表
2.数字序号列表
~~~ markdown
* 圆点符号列表
1.数字序号列表
2.数字序号列表
~~~
- 高亮
==文本的高亮==
~~~ markdown
 ==文本的高亮==
 ~~~
 - 代办事项
 ~~谁是最好的语言~~
 * [ ] JavaScript
 * [ ] Java
 * [ ] C + +
 * [x] Markdown
 ~~~ markdown
 * [ ] JavaScript
 * [ ] Java
 * [ ] C + +
 * [x] Markdown
~~~
- 插入连接
[MarkDown百度百科](https://baike.baidu.com/item/markdown/3245829?fr=aladdin)
~~~ markdown
[MarkDown百度百科](https://baike.baidu.com/item/markdown/3245829?fr=aladdin)
~~~
- 插入图片
>Markdown支持嵌入网络图片或者直接拖入本地图片，其中本地图片格式支持 jpg、png 和 gif。
![](http://is4-ssl.mzstatic.com/image/thumb/Purple118/v4/f6/a3/f3/f6a3f3b8-8243-05ad-41f2-2fe69ae9d0d5/source/512x512bb.jpg)
~~~ markdown
![](http://is4-ssl.mzstatic.com/image/thumb/Purple118/v4/f6/a3/f3/f6a3f3b8-8243-05ad-41f2-2fe69ae9d0d5/source/512x512bb.jpg)
~~~
- 插入表格
|帐户类型|免费帐户|标准帐户|高级帐户|
|---|---|---|---|
|帐户流量|60M|1GB|10GB|
|设备数目|2台|无限制|无限制|
|当前价格|免费|￥8.17/月|￥12.33/月|
~~~ markdown
|帐户类型|免费帐户|标准帐户|高级帐户|
|---|---|---|---|
|帐户流量|60M|1GB|10GB|
|设备数目|2台|无限制|无限制|
|当前价格|免费|￥8.17/月|￥12.33/月|
~~~
- 插入源代码
>插入源代码功能是为程序员量身定做的。用 ```上下包裹一段代码，并指定一种语言（指定语言可以显示语法高亮）。
~~~ markdonw
  ``` html
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <meta http-equiv="X-UA-Compatible" content="ie=edge">
            <title>Document</title>
        </head>
        <body>     

        </body>
        </html>

    ```
~~~
##MarkDown编辑工具推荐
>可以去使用不同风格的MarkDown工具，最后选择一款自己的喜欢的MarkDown软件。
[VSCode](https://code.visualstudio.com/)
[Typore](https://www.typora.io/)
[印象笔记](https://help.yinxiang.com/hc/)
[Cmd MarkDown 作业部落](https://www.zybuluo.com/cmd/)
