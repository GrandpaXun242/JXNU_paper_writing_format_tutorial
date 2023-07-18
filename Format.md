> 此处只包含公式的自动编号
>
> 章节、图片和表格等自动编号请看[自动编号](./Chapter.md)

## 公式自动编号及对齐

[公式识别 (simpletex.cn)](https://www.simpletex.cn/ai/latex_ocr) 

```shell
MathType可以直接复制Latex代码生成数学公式。
```



### 准备工作

> 事先要记录`Mathtype`的安装路径

1. 安装`Mathtype`

   > 内附安装教程

   下载链接:[BaiduDisk](https://pan.baidu.com/s/1TzySjNcx42QH-1p-yuar9g ) PassWord:4zu3

2. WPS安装`VBS`插件

   > 内附安装教程

   下载链接:[BaiduDisk](https://pan.baidu.com/s/1A9USjBV7sGV3q16PS0z2oQ ) Password:vps7

3. WPS之中安装`MathType`插件

   > 2个教程都可以，记得替换文件之后要重启WPS

   [教程1](https://zhuanlan.zhihu.com/p/492369639) 

   [教程2 附带找目录教程](https://blog.csdn.net/Bkhole/article/details/124477679) 

4. 成功页面

  <img src="./assets/1689296519985.png" width="600">



### 公式自动编号

> 注意: 此处的公式都会独占一行。

1. 选择你要插入的公式编号位置。这里以右编号为例：

   操作:`MathType`$\rightarrow$`右编号`$\rightarrow$输入公式$\rightarrow$删除公式$\rightarrow$再次插入公式

   > 默认点击`OK`即可
   >
   > <img src="./assets/1689297566101.png" width="600">
   >
   > 删除第一次插入的公式，文件第一次插入公式会出现章节分割符号`Equation Chapter 2 Section 1`字样，这个需要我们自己手动创建。
   >
   > <img src="./assets/1689297826571.png" width="600">
   >
   > 再次插入一次公式
   >
   > <img src="./assets/1689297866774.png" width="600">
   >
   > 流程操作图:
   >
   > <img src="./assets/1689297254105.png" width="600">

2. 创建`章&节`分割符。只有创建这个才能保证是你自己想要的编号，否则编号是固定从`(1.1)`开始标号的。

   - 编辑公式格式![1689298664695](./assets/1689298664695.png)

   - 直接使用`Advanced Format`设置公式格式,设置为`(#C1-#E1)`。
      <img src="./assets/1689298808363.png" width="600">

   - 插入分割符。`章&节`$\rightarrow$`插入分割符`。出现如下页面:
      <img src=".\assets\1689427855169.png" width="600">

   - 输入章节5,效果图如下:
      <img src="./assets/1689428103633.png" width="600">

3. 删除红色`Equation Chapter 5 Section 1`字样步骤.      

   - 按下`alt`+`F9`，出现如图字样
      <img src="./assets/1689428385502.png" width="600">