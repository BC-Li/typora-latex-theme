![cover](./Supplemental/cover.png)
# Typora 伪装 LaTeX 中文样式主题

[预览](#预览) | [安装与使用](#安装与使用) | [下载](https://github.com/Keldos-Li/typora-latex-theme/releases) | [个性化设置](#个性化设置) | [面向高级用户](#面向高级用户) | [常见问题](#常见问题) | [已知 bug](#已知-bug) | [反馈与贡献](#反馈与贡献)  

本项目的初衷是为了简化中国大陆本科生**小型通识课论文**（或**小型实验报告**）撰写的负担。这里基本采用了浙江大学要求的格式（字体较小，页边距较小），但大部分同学都可以自行在 CSS 中修改适合自己学校的格式。  

Markdown 的轻量化特性，使您可以专注于论文内容而不用担心格式。书写时仅通过简单的标记，并通过替换样例模板中的个人信息，您就可以输出媲美卷王由 LaTeX 排版的精美论文与报告。本项目支持 Windows, macOS 和 Linux 三大平台的 Typora.  

If you are not studying in China, please DO NOT use this theme. Instead, you could check another theme: [Paper – A typora theme using latex fonts to be used in academic work](https://theme.typora.io/theme/paper/).

<a href="https://github.com/Keldos-Li/typora-latex-theme/releases">![GitHub downloads](https://img.shields.io/github/downloads/Keldos-Li/typora-latex-theme/total?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAVCAYAAACg/AXsAAAAAXNSR0IArs4c6QAAAX1JREFUOE/llLEuBGEUhb+zIaHR8gYapUQUig1RaEg0Wo3GC4hOoaDXKVQ6UXgAoVGIaBRGYiMSXkBDMEf+mdmZf3bWegBTTe5/77nnnnv+Xwz4bE8AF5ImB+XpD5Ap4OQ/gtjeABaA4aCRgUKsb2Ab2CujxWEK7y04lnQm2zuYtW5VLnQJcydp1XYSI0c5IXE3gFwDY7XiikoFUq7RGMU9b+XUSYhEI8T/OUickyXG2XSU2kkeizv8Pk6FUeZ0ZKdJRc98o60h6dT2jeGp1dUEXiW1be8Dy5FJA4iTumuzDvPAC3AqacX2laRZ27PAUY/L+4xTjbuIeFYuAP70HEMcVsfF+CZn0l9U84GWRqRH28FDB801Z5w6xXZqavdYhXNMu9xgv+00jBRvqlnQ26Bg0hW2UVCwi+MNwpkumSb3YMUu/Buv5trHAHIJjAfPxn4pr2CPmn3MdhVA1oGtX5Sv34fmM/gFbGY33vZ0CjMtGB30XMZnKby14FzSww+Jf/H06Zp5zAAAAABJRU5ErkJggg==)</a>
<a href="https://github.com/Keldos-Li/typora-latex-theme/releases/latest">![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/Keldos-Li/typora-latex-theme?include_prereleases&color=green&logo=hack-the-box)</a>
<a href="https://github.com/Keldos-Li/typora-latex-theme/stargazers">![GitHub Repo stars](https://img.shields.io/github/stars/Keldos-Li/typora-latex-theme?style=flat&logo=github&color=yellow)</a>
<a target="_blank" href="https://qm.qq.com/cgi-bin/qm/qr?k=IB2QSpQSSOQIDZfN74ujqx1aVtQtdtXF&jump_from=webapi">
![QQ群](https://img.shields.io/badge/QQ群-643187070-89AED1?logo=Tencent-QQ)</a>

## 预览

较完整的论文预览见这里: [点我😀](https://blog.keldos.me/2021/05/md-latex-template/)；如果 GitHub 中的图像加载不出来，您也可以查看[我博客上的说明](https://blog.keldos.me/2021/05/typora-latex-css/)。

### 封面，摘要和关键词

| ![sample-essay_1](https://gitee.com/Keldos-Li/picture/raw/master/img/sample-essay_1.png)|![sample-essay_2](https://gitee.com/Keldos-Li/picture/raw/master/img/sample-essay_2.png)|
| :----: | :----: |

### 预览与编写

| ![preview-l](https://gitee.com/Keldos-Li/picture/raw/master/img/preview-l.png)|![preview-d](https://gitee.com/Keldos-Li/picture/raw/master/img/preview-d.png)|
| :----: | :----: |
| ![edit-l](https://gitee.com/Keldos-Li/picture/raw/master/img/edit-l.png)|![edit-d](https://gitee.com/Keldos-Li/picture/raw/master/img/edit-d.png)|

#### 层级标题 

|![heading-l](https://gitee.com/Keldos-Li/picture/raw/master/img/heading-l.png)|![](https://gitee.com/Keldos-Li/picture/raw/master/img/heading-d.png)|
| :----: | :----: |

#### 表格 
|![table-l](https://gitee.com/Keldos-Li/picture/raw/master/img/table-l.png)|![table-d](https://gitee.com/Keldos-Li/picture/raw/master/img/table-d.png)|
| :----: | :----: |

```markdown
表格：

<center><strong>表 2  全球/中国桌面操作系统市场份额占比（%）</strong></center>

| OS   | Windows | macOS | Unknown | Linux | Chrome OS | 其他 |
| ---- | ------- | ----- | ------- | ----- | --------- | ---- |
| 全球 | 76.56   | 17.1  | 2.68    | 1.93  | 1.72      | 0.01 |
| 中国 | 87.55   | 5.44  | 6.24    | 0.75  | 0.01      | 0.01 |
```

#### 项目列表
|![item-l](https://gitee.com/Keldos-Li/picture/raw/master/img/item-l.png)|![item-d](https://gitee.com/Keldos-Li/picture/raw/master/img/item-d.png)|
| :----: | :----: |

#### 代码块 
|![code-l](https://gitee.com/Keldos-Li/picture/raw/master/img/code-l.png)|![code-d](https://gitee.com/Keldos-Li/picture/raw/master/img/code-d.png)|
| :----: | :----: |

#### Mermaid
|![mermaid-l](https://gitee.com/Keldos-Li/picture/raw/master/img/mermaid-l.png)|![mermaid-d](https://gitee.com/Keldos-Li/picture/raw/master/img/mermaid-d.png)|
| :----: | :----: |

```markdown
mermaid 图形：

​```mermaid
graph LR
A(开始) -->
input[/输入a,b/] --> if{a%b=0 ?}
if --->|yes| f1[GCD = b] --> B(结束)
if --->|no| f2["a, b = b, a % b "]-->if
​```
```

#### 公式

|![equation-l](https://gitee.com/Keldos-Li/picture/raw/master/img/equation-l.png)|![equation-d](https://gitee.com/Keldos-Li/picture/raw/master/img/equation-d.png)|
| :----: | :----: |

```latex
公式：

$$
\iint\limits_{x^2 + y^2 \leq R^2} f(x,y)\,\mathrm{d}x\,\mathrm{d}y = \int_{\theta=0}^{2\pi} \mathrm{d}\theta\int_{r=0}^R f(r\cos\theta,r\sin\theta) r\,\mathrm{d}r\, \tag{1}
$$
```

## 安装与使用

**请完整阅读以下安装过程，以确保一切符合预期。**  

1. 安装本主题前，**请确保您已经安装 Typora**. 如果您不清楚 Typora 是什么，这里有[一段介绍](#什么是-typora)。如果您对 markdown 的语法还不了解，您可以从这里[获得帮助](#什么是-markdown)。

2. 前往本项目的 [release](https://github.com/Keldos-Li/typora-latex-theme/releases) 页面，然后下载适合您操作系统的最新版本压缩包。比如，如果您在使用 Windows 操作系统，您就应该下载 `latex-theme-windows.zip`. 

3. 解压缩这个文件，并进入解压缩后的文件夹。在这个文件夹中，用 Typora 打开 `README.md`，并按照其中的描述完成剩余步骤。该文件的在线预览版本在[此处](./src/README.md)。简单而言，需要进行如下几步：
    - 进行手动或自动主题安装
    - 若遇到字体问题，则下载所需的字体
    

### 使用封面

*   `Supplemental` 文件夹中的 `essay-template.md` 和 `essay-template.pdf` 展示了一篇小论文在该主题下的效果（其中文字来源于我本人的课程作业以及一些拼凑，请不要在意过多细节），其中论文封面（也单独放置在 `cover-template.md` 文件中）、摘要、关键词和其他一些特别的元素使用 HTML 代码来编写。您可以自行取用修改它们的文字内容部分和代码部分来完成您的课程论文。
*   如果您看不懂 HTML 代码，请先自行百度/谷歌/必应，然后尝试联系您在计算机系的同学。

### 取消额外行距

*   如果您不希望论文有段后的额外行距，可以在 Typora 的`偏好设置` – `Markdown` 中选取`保留连续的空格与单个换行`。

## 个性化设置

在完成安装后，您可以选择[按照学校的要求进行个性化设置](#为什么要个性化设置)。在 CSS 文件中，您可以根据代码中的注释提示修改变量取值，轻松地更换正文、标题等不同元素的字体、字号、行距、页边距等：  

```css
  /* 代码字体（代码中的中文会调用ui-font） */
  --code-font: "Latin Modern Mono", "Latin Modern Mono 10";  /* 您可以修改这里的值 */
  /* 侧边栏字体 */
  --ui-font: "阿里巴巴普惠体 2.0";  /* 您可以修改这里的值 */
  /* source mode 字体 */
  --sourceMode-font: "SF Mono", "阿里巴巴普惠体 2.0";  /* 您可以修改这里的值 */
```

进行个性化设置有两种方案：  
1. 您可以直接在您下载的安装包中进行修改。**在完成修改后，请重新执行与您操作系统相匹配的脚本（`install.ps1` 或 `install.sh`），并重新启动 Typora，以应用您的更改**。  
2. 您也可以直接更改 Typora 主题文件夹下的文件，[点击此处了解主题文件夹所在的位置](#主题文件夹)。进入这个文件夹后，与本主题相关的两个文件分别是 `latex.css` 和 `latex-dark.css`，请您按需修改。**在完成修改后，请重新启动 Typora，以应用您的更改**。  

如果您在打开 CSS 文件时遇到了困难，请考虑使用 *记事本*（Windows）或*文本编辑*（macOS）打开它。**绝对不要用 Microsoft Word 打开它！！！就算它可以！**  

如果您有更多的修改需求，请直接在 `latex.css` 和 `latex-dark.css` 中修改。  
如果您看不懂注释，或不知道修改代码会造成什么效果，请先自行百度/谷歌/必应，然后尝试联系我。  

以下是一些个性化设置的具体内容：  

* **页边距**：
  
  若要修改页边距，您首先需要打开您想要修改的 CSS 文件。您需要在这个 CSS 文件中，分别找到两段类似这样的代码：  
  
  ```css
   /* == 页面设置 == */
   /* 打印页边距 */
   --set-margin: 1.8cm 2cm 1.2cm 2cm !important;
  ```
  
  ```css
  @media print {
      @page {
          /* size: A4;  强制A4大小 */
           margin: 1.8cm 2cm 1.2cm 2cm !important;
           /* 按次序为 上 右 下 左 的页边距 */
  ```
  
  真实的代码内容可能与以上描述不完全相同，但是嵌套关系一定是相同的。推荐您搜索`页边距`这个关键词，从而快速找到这两段代码。  
  以上的第一处的设置调整了 Typora 预览界面包括导出 HTML 时的页面边距，第二处调整了 Typora 导出 PDF 时的页边距。
  
  在 Windows 中，您在两个 CSS 文件中同时修改页边距后即可导出正确的页面。
  
  **但对于 macOS 用户，因为 [Typora 本身的问题](https://github.com/typora/typora-issues/issues/998)，第二处设置无效**。也就是说，第一处设置能够保证编辑预览时的页面边距正确，但直接导出时的页面边距无法精确修改。只能通过以下的办法：
  
  *   在 Typora 的导出设置里自定义页边距。
  *   先导出为 HTML  ，然后在 Chrome 中打开打印。请注意，**不能用 Safari**！Safari 会自行设置它认为的最小边距，这会导致您无法精确控制页边距；另一方面，在某次更新后 Safari 取消了对 CSS 本地字体读取的支持（理由是隐私问题），会导致您无法显示很多字体！
  *   直接用 pandoc 的命令行导出。
  
*   **超链接**：

    显然，我们不希望打印的论文存在蓝色的超链接（？），我在 CSS 中修改了部分代码，使得在页面编辑和导出 HTML 预览中可以得到正常的超链接样式，但打印时会取消颜色和下划线（仍可以点击链接）。

    不知道大家是否有这个需求，如果有更合适的方法可以联系我。

*   **多级列表**：

    因为我的技术原因，请暂时不要在**二级有序列表**之后**混用** *有序列表* 和 *无序列表* 以及*核对清单*，会出现一些 bug。（虽然感觉会这么干的人应该不多。）如果您有解决方案，请联系我。

*   **页眉和页脚**：

    目前似乎不能直接定义，请在 Typora 的导出设置里设置好您需要的页眉和页脚文字，导出后在 PDF 编辑器中调整您喜欢的样式风格。

*   **引用参考文献**

    目前没有更好的方式，请您主动编号……（或许小型课程论文不需要大量参考文献。）

    或者我之后可能考虑把 markdown 注释样式改一下。

*   **专注模式**和**打字机模式**：

    还没写这部分的代码。本主题样式初衷不在于此，如果您有需求，可以提交 issue 或进入讨论区讨论，我视需求和精力再进行开发。
    
## 面向高级用户

若您仅希望使用本主题，而不在意本主题的实现细节，请跳过本章节，因为**本章节涉及与主题相关的进阶用法**，您很有可能无需关心这些内容。

- Typora 是一个专有软件。在测试阶段，Typora 会保持免费；但在正式版中，其可能需要付费才能使用。
- Typora 通过开源项目 Pandoc 将 markdown 转换为 HTML，每一个 markdown 元素都会带有特定的 HTML 标签。本主题的本质就是撰写一些 CSS 规则，从而规定超文本的样式。这意味着，本主题不但支持 Pandoc，还支持其他依赖 Pandoc 的 markdown 文本编辑器。
- Typora 自身用户界面的样式也受本主题的影响。因此，在您阅读本项目的源代码时，需要留意，您看到的 CSS 规则不止影响了输出结果，还影响了 Typora UI。
- 若要在本地构建本项目，请确保您安装了 sass. 然后，执行 `src` 目录下的 `build.sh`，即可完成构建。请注意，这里的构建结果不包含字体文件。

### 构建过程

位于 `src` 目录下的文件有三种： SCSS 文件， Makefile 和自动安装脚本。运行以下指令，即可构建项目：  

```shell
# 我们默认您当前位于仓库的根目录
cd src
make
```

在 `make` 指令执行的过程中，发生了以下步骤：  
1. 创建一个 `build` 目录，以存储中间结果。  
2. 将操作系统信息、主题信息和 SCSS 文件字面地拼接在一起，形成某个特定操作系统和主题的 SCSS 文件。  
3. 这些 `SCSS` 文件被转译为 `CSS` 文件，并被存储在 `latex-theme/${os_name}/target` 目录下。  
4. 操作系统对应的自动安装脚本被复制到 `latex-theme/${os_name}` 目录下。  
5. 所有 `latex-theme/${os_name}` 目录都会被分别打成 zip 包，包内保持原先的文件结构。  

GitHub Actions 会把上述 zip 包发布。  

### 主题文件夹

各操作系统的 Typora 主题文件夹路径如下：

| 操作系统 | 主题文件夹路径 |
| :----: | :---- |
| Windows | `%APPDATA%\Typora\themes` |
| macOS | `~/Library/Application Support/abnerworks.Typora/themes` |
| Linux | `~/.config/Typora/themes` |  


## 常见问题

### 什么是 **Typora**？

[Typora](https://typora.io/) 是一个超级好用的实时预览 markdown 编辑器。

### 什么是 **markdown**？

[markdown](https://daringfireball.net/projects/markdown/) 是一种轻量级标记语言，用于使用纯文本创建格式化文本。
约翰·格鲁伯和亚伦·斯沃茨于2004年创建了 Markdown，作为一种以源代码形式吸引人类读者的标记语言。
Markdown 排版语法简洁，让人们更多地关注内容本身而非排版。它可与 HTML 混编，可导出 HTML、PDF 以及本身的 .md 格式等文件。
Markdown 广泛用于博客、即时消息、在线论坛、协作软件、文档页面和阅读文件。

参考：

*    [Markdown中文语法简介](https://markdown.com.cn/)
*    [Typora使用的markdown语法参考](https://support.typora.io/Markdown-Reference/)

### 该主题都包含了哪些字体？

字体文件都存放在 [Keldos-Li/typora-latex-theme-fonts](https://github.com/Keldos-Li/typora-latex-theme-fonts) 仓库，详情请参阅[字体帮助](https://github.com/Keldos-Li/typora-latex-theme-fonts/blob/main/README.md)。**所有的字体文件请自行获取授权**，本人不对您使用字体造成的法律纠纷负责。

### 为什么要个性化设置？

每个学校所要求的格式略有不同。另外，尽管老师不会肉眼查看您的格式是否符合要求，但或许您为了自己的需要仍需要稍作修改，例如加大字体、行间距和页边距使得论文显得更长。

### 该主题不能满足我的需求？

该样式只能作为**轻量级**排版输出，如果您需要更复杂的排版，请使用 LaTeX 或 Word 进行排版。

*   如果您是 ZJUer：[指南](https://github.com/TheNetAdmin/zjuthesis)
*   如果您是 TJUer：
    *   [基于本项目二次开发的适配](https://github.com/KuangjuX/TJU-typora-latex-theme)
    *   [LaTeX指南](https://github.com/twtstudio/TJUThesisLatexTemplate)

### macOS 如何打开终端？

打开[启动台](https://support.apple.com/zh-cn/HT202635)；在启动台顶部的搜索栏里，搜索“终端”，然后点击搜索结果中的终端图标。

## 已知 bug

*   在 Windows 下将 Typora 设置为“一体化”后，darkmode 的 CSS 暂时无法对设置页面进行背景修改。

- 无编号项目列表有很大的bug！！在二级项目之后，你不能混用有序列表和无序列表！因为全都是重新定义的content，我不能理解它为什么会对子项目产生影响！！可恶！
- 当行间代码太长跨页的时候好像也会有点问题，到时候再改……
- mermaid字体无法修改，我找遍了mermaid的最新文档和Typora的其他样式资源都没找到这个应该怎么在 CSS 样式表里修改……呜呜呜。

话说论文封面的学校徽标是不是做得太大了（？）你们觉得不合适自己改改就好，就调一个`width`的事。

>   虽然是都开源项目，但这个项目似乎经过三手每个人都重新做了仓库而不是fork😂，不过确实每经一次手都有很多深化和改进orz，感觉目前代码已经没有办法merge了，害。感觉不是很符合开源精神。有点对不起原作者的感觉🥲（虽然我们谈过话）。  

## 反馈与贡献

如果您在使用过程中遇到任何问题，或想为本项目做出任何贡献，请优先考虑：  
*   前往 GitHub Discussions [发起讨论](https://github.com/Keldos-Li/typora-latex-theme/discussions/new)
*   前往 GitHub Issues [报告故障](https://github.com/Keldos-Li/typora-latex-theme/issues/new?labels=bug)
*   前往 GitHub Issues [请求新功能](https://github.com/Keldos-Li/typora-latex-theme/issues/new?labels=Feature+Request)
*   如果您希望在本地修改这个项目的代码，推荐您在 fork 后使用 `git clone ${target} --depth 1` 进行克隆。这是因为，本仓库的历史中有大量二进制文件，而这些二进制文件对当前开发并无作用，可以舍弃。设置较浅的克隆深度可帮助您更快地获取到此项目的最新代码。在完成您的修改后，**请向我们的 `develop` 分支提出拉取请求**。  

如果以上方法都行不通，您也可以考虑：  
*   联系[我本人](mailto:i@keldos.me)
*   <a target="_blank" href="https://qm.qq.com/cgi-bin/qm/qr?k=8Vy0m_9-phExgORJKwVTZ2Hix19yScCn&jump_from=webapi"><img border="0" src="//pub.idqqimg.com/wpa/images/group.png" alt="加入交流反馈QQ群" title="Typora伪LaTeX交流反馈"></a>之后和大家一起讨论

## 鸣谢

本项目是在下面两人工作的基础上完成的。括号内链接为两人的项目地址：

[@让幻想飞](https://zhuanlan.zhihu.com/p/357096043)（[yfzhao20](https://github.com/yfzhao20/Typora-markdown)）

> * 适配LaTeX的字体。选用像LaTeX的字体是装“哔”的重要手段。
> * 更改标题、目录和大纲的编号样式。改成1. ，1.1 ， 1.1.1 ，……这样的编号更有一种浓厚的论文感觉。
> * 二级及以下标题全部靠左，适应文章样式。后面加上大空白，适配LaTeX样式

[@LAN DU](https://zhuanlan.zhihu.com/p/158767474)（[du33169](https://github.com/du33169/typora-theme-essay_cn)）

> 一个简单的、为中文课程论文排版设计的[Typora](https://typora.io/)主题。
>
> 1.  各级标题选取合适字体，更加美观
> 2.  标题自动编号，又有了不必打开Word的理由
> 3.  图表下方自动编号，专业严谨（图片编号暂无法导出）
> 4.  表格采用三线表，简洁清晰
> 5.  目录样式覆盖，规范大气
> 6.  A4页面设定，编辑器内所见即所得
> 7.  提供.md格式的封面模板，写作->导出PDF全过程一处进行

↑ 这个样式似乎更适合文科生。回头我看看也再加一个CSS。
