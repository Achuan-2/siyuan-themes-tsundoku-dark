<h1 align="center">🌙Tsundoku(dark): A Theme for SiYuan Note</h1>

<p align="center">          
           <a title="Hits" target="_blank" href="https://github.com/Achuan-2/siyuan-themes-tsundoku"><img src="https://hits.b3log.org/Achuan-2/siyuan-themes-tsundoku.svg" ></a>
            <a href="https://gitmoji.dev">
             <img src="https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg?style=flat-square" alt="Gitmoji">
           </a>
           <a href="https://github.com/Achuan-2/siyuan-themes-tsundoku/releases">
                      <https://img.shields.io/github/release/Achuan-2/siyuan-themes-tsundoku.svg" alt="Release">
           </a>
           <img src="https://img.shields.io/github/stars/Achuan-2/siyuan-themes-tsundoku" alt="stars">
           <img src="https://img.shields.io/github/issues-raw/Achuan-2/siyuan-themes-tsundoku" alt="open-issues">
           <img src="https://img.shields.io/github/issues-closed-raw/Achuan-2/siyuan-themes-tsundoku" alt="closed-issues">
          <img src="https://img.shields.io/github/last-commit/Achuan-2/siyuan-themes-tsundoku" alt="GitHub last commit">
</p>

<p align="center">English |<a href="https://www.yuque.com/achuan-2/siyuan/fqew9h"> 中文介绍</a></p>

[SiYuan](https://github.com/siyuan-note/siyuan) is a local-first personal knowledge management system, supports fine-grained block-level reference, and Markdown WYSIWYG. This is a theme for it.  
![preview](preview.png)

> 🎠 This may not be the most aesthetically pleasing theme for you, but perhaps it will be one of the most sought-after themes for the ultimate experience！
> 
> Others Themes:🌞[Tsundoku Light](https://github.com/Achuan-2/siyuan-themes-tsundoku-light) | 🧇[Tsundoku Texture ](https://github.com/Achuan-2/siyuan-themes-tsundoku-texture) | 🥗[Tsundoku Green](https://github.com/Achuan-2/siyuan-themes-tsundoku-green)


## 💌 Origin

Tsundoku “積 ん 読” , a Japanese word，explained in Wikipedia as “Tsundoku is acquiring reading materials but letting them pile up in one's home without reading them. It is also used to refer to books ready for reading later when they are on a bookshelf.”

> Any PKM approach that doesn’t tie into execution tools is destined to languish on the back burner forever.

I use this name to wake myself up and hope that SiYuan will help me make gradual progress and  get things done better, instead of becoming another dustbin for relieving intellectual anxiety and satisfying my digital hoarding disorder.


## ✨Features

* **Optimized  style of each level title**
![](assets/Readme_2021-09-27-17-23-05.png)
* **Added hyperlink icon**  to distinguish local protocol of different softwares from web links,to learn all supported links, see [more info](https://www.yuque.com/achuan-2/siyuan/gar358)  
![](assets/Readme_2021-09-27-17-22-00.png)
* **Rich dynamic effects**：hovering over the button icon with a magnification effect, etc. to enhance the user experience when writing and reading.
* **Optimized style of completed Task list**：A lot of optimization has been done to the task list effect, when the task list is checked, the normal text will change color with strikethrough, and the style of each line and block in the completed task list has been handled in some way, for example, the opacity of the images and code blocks in the completed task list will be reduced.
![](assets/Readme_2021-09-27-17-22-51.png)
* **Unified emoji style for Win and Android**：Modify the default emoji on Android to Win 10 emoji--Segoe UI Emoji to ensure the uniformity of emoji style.
* **MAC's code block style** 
![](assets/Readme_2021-09-27-17-22-22.png)
* **Optimized  text color and background color popup**  
![](assets/Readme_2021-09-17-09-57-38.png)



## 💥Impotant Changes

1. This theme temporarily set highlighting <kbd>Ctrl+E</kbd>, to a hide effect: the highlighted text is shown only when mouse hovering, and the default text is hidden.

   * If you need to cancel this effect, please search for the `.protyle-wysiwyg mark` keyword in the theme css, and delete the suggested code 
   ![](assets/Readme_2021-09-27-17-21-43.png)
2. Added custom block attribute styles

   * Attributes key are set to `function` or `f` (abbreviated)
   * value can be

     * **zy/important**: add "❗❗❗" the end of this block;
     * **ing** : add "ing" the end of this block;
     * **done/100**: add "done" the end of this block;
     * **10/20/30.../90**: add 10%/20%/.../90% at the end of this block;
     * **kaiti**：The font-family of this block will be set to Kaiti;
     * **hide/挖空**：This block will be automatically hided;
     * **quote**: 📌quote style;
     * **yellow/黄**：This block will
     *  have a yellow background color;
     * **blue蓝**：This block will
     *  have a blue background color;
     * **red/红**：This block will
     *  have a  red background color;
   * How to use:  use <kbd>Shift+Click</kbd> to  click the block icon to open the attribute list, click <kbd>add</kbd >, enter the attribute name  `function` or `f`, and enter the corresponding attribute value (such as "hide")
   * preview image：![](assets/Readme_2021-09-17-10-04-05.png)
3.  Customized text color and background color

      dark theme：

      | Condition   | Color Scheme                                                                                        |
      | ------ | ----------------------------------------------------------------------------------------------- |
      | Before |![](assets/Readme_2021-09-27-17-23-37.png) |
      | After |![](assets/Readme_2021-09-27-17-23-47.png) |


## ☎️Feedback


If there is a problem with the style of the theme, welcome to raise an issue in this repo or contact me via email (achuan-2@outlook.com). Before raising an issue, it is recommended to switch to the default theme to make sure it is a problem specific to this theme.

## 🚀Change Log

See [CHANGE_LOGS](CHANGE_LOGS.md)