# hhu-thesis-bachelor
河海大学本科毕业论文LaTeX模板（理工科）

## 简介
本项目最早由曹文翰老师（[hhuthesis](https://github.com/caowenhan/hhuthesis)）编写，因为对于本科生部分有些许欠缺，经（[bhqhz0209](https://github.com/davyxx3/hhu-thesis-bachelor)）重新编写后对本科生部分进行了优化。可能是发布时间比较久了，有些部分已经和现在的本科生论文规范不一致了，故在我写毕业论文时对该项目进行了一定程度的改写。

## 预备知识
- $\LaTeX$ 基础语法
- $\LaTeX$ 公式编写能力，或者使用公式编辑器
- bib文件系统
- Zotero文献管理软件

## 推荐写法
使用 $\LaTeX$ 模板可以节约大部分的时间，但是这不意味着可以什么也不管，一些写法可能会因为你的论文写作的内容的不一样而不一样，在此，我仅展示我写作时使用的一些写法。具体内容见[main.pdf](./main.pdf)。

### 文献管理
本人使用的文献管理软件是[zotero](https://www.zotero.org/)。

相较于其他软件的优势是开源，有很多的开发者为其开发了众多插件，功能很强大；同时也是免费的。

推荐的bib文件存放位置：使用做zotero，同时安装插件[zotero-better-bibtex](https://github.com/retorquere/zotero-better-bibtex)，把文献库以“Better BibTex”格式导出到你电脑的固定位置，同时勾选保持更新选项。在每次应用zotero时直接引入该文件即可。

### 公式编辑器
本人使用的公式编辑器是[axmath](https://www.amyxun.com/)。

学校是没有为我们提供公式编辑器的，mathtype作为一个老牌的公式编辑器，其价格比较高，虽然其兼容性较强，但是没有必要。我使用的axmath也是付费的，在淘宝可以购买激活码，价格在30元左右。当然也可以使用在线的工具[LaTeX公式编辑器](https://www.latexlive.com/##),其完全免费。


### 公式识别软件
本人使用的公式识别软件是[mathpix](https://mathpix.com/)。

对于某些需要引用但是极其复杂的公式来说，使用latex输入的时间非常长的（有些同学直接就截图粘贴了，我并不推荐这样做），使用一个公式识别软件就显得极为便捷，使用该软件可以OCR出公式的latex源码，很方便。


## 本模板改进部分
- 考虑到有些老师需要把论文翻译稿一并附上的问题，增加了pdf附录插入
- 提供了一些符号的示范
- 把根据规范要求，把奇数页改为章标题，把偶数页改为“河海大学本科论文”
- 把图表编号改为二级形式
- 添加评阅人选项
- 替换河海大学图标，解决背景泛黄问题
- 对齐样式调整
- 取消插图清单以及附表清单

对于我没有发现的问题，欢迎大家联系我。

## 运行环境
  |||
  |-|-|
  |操作系统|Win10|
  |编译器|Tex Live 2022|
  |文本编辑器|vscode|
  

对于文本编辑器部分，我其实更推荐你使用[Tex Studio](https://www.texstudio.org/)，因为vscode有些时候报错了不会直接显示错误到底在哪里，同时需要配置latex环境；而Tex Studio则可以安装后就使用，同时报错信息很详细。

## 文件说明
|||
|-|-|
|[./chapters/](./chapters)|每章节文件夹|
|[./code/](./code)|代码文件夹|
|[,/figures/](./figures)|图片文件夹|
|[./translate/](./translate)|翻译文件文件夹|
|[./hhutheis.cls](./hhuthesis.cls)|模板文件|
|[./REDME.md](./REDME.md)|项目说明|
|[./hhuthesis.pdf](./hhuthesis.pdf)|原曹文翰老师的说明书|
|[./main.pdf](./main.pdf)|编译完成的文稿|




## 本模板参照标准
本模板参照的标准是学校于2023-05-09发布的[河海大学本科毕业设计（论文）基本规范(修订)](https://bylw.hhu.edu.cn/UpLoadFile/83cd5f1169974a0db06d865c7ee11af4.pdf),也就是本项目中的[河海大学本科毕业设计（论文）基本规范(修订](./specification/%E6%B2%B3%E6%B5%B7%E5%A4%A7%E5%AD%A6%E6%9C%AC%E7%A7%91%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%88%E8%AE%BA%E6%96%87%EF%BC%89%E5%9F%BA%E6%9C%AC%E8%A7%84%E8%8C%83(%E4%BF%AE%E8%AE%A2).pdf)。
