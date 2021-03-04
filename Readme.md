# 思源主题: mixture(dark)
![preview](preview.png)
本主题主要基于[Atom One Dark](https://github.com/zqhjl/Siyuan-Atom-OneDark)，并借鉴了Pure Dark和Lavender等其他主题进行修改，本主题主颜色为青色，主字体为阿里巴巴普惠体，代码字体为Fira Code，亮色主题见[Mixture Light](https://github.com/Achuan-2/siyuan-themes-mixture-light)

## v0.1.7/2021-3-4
概括：更追求主题的统一性了，算是一个大改进，不像之前总是追求花里胡哨，其实蛮伤眼的也不易读的📣
- 改进行内代码的css代码，避免其影响代码块编辑区
- 对代码块编辑区样式进行修改，之前是行内代码的样式有点突兀
- 对行内公式编辑样式进行修改
- 减淡引用块背景颜色，去掉背景，更有沉浸感，个人很喜欢
- 又双叒叕更改h2标题颜色，变淡了一点
## v0.1.6/2021-3-4
- 修正行内公式块有多余的代码，把CSS的`.vditor-reset code:not(.hljs){...}`改为`.vditor-reset code:not(.hljs):not([data-type="math-inline"]) {...}`
- 对已完成代办事项中的加粗、斜体、删除线、超链接进行优化，事项中含有的图片透明度设置为60%，鉴于原先默认设置的删除线可能不方便查看，暂时决定取消，可以自行添加删除(Ctrl+D)，或者自行修改主题,搜索"完成的代办事项下划线",`/* text-decoration: line-through; */`取消注释
- 更改h3标题与上下文的间距
  
## v0.1.5/2021-3-3
- 修复从edge复制的超链接，形如[思源笔记更新日志(ld246.com)](https://ld246.com/tag/siyuan-announcement)，分多块hover高亮的问题
  
## v0.1.4
- 仿照Lavender设置界面动效，更改设置的关闭按钮颜色和hover背景
- 仿照Passion设置选中项的圆角
- 更改弹出菜单样式
## v0.1.3
- 更改字体：主字体为阿里巴巴普惠体，代码字体为Fira Code
- 更改标题，统一色系为天蓝色
- 更改引用块样式
- 更改标签页样式，去除标签页前的文件图标样式
- 更改超链接hover颜色
- 更改块引用样式
- 添加图片阴影
## v0.1.2
- theme.css 初步整理
- 标题样式修改,h3标题增加左边框，h4-h6颜色为白色
- 对flowchart、graphviz、plantuml渲染块背景进行优化
- 更改超链接颜色
- 复选框勾选增加动效

## v0.1.0
- 标题样式更改
- 超链接样式更改
- 复选框样式更改
- 代码块更改
- 行内代码样式更改
- 分割线样式更改
- 标签样式更改
- list focus样式更改