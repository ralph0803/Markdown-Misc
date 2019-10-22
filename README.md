# Markdown-Misc

## VS Code中从Markdown文件生成PDF
- 在vs code中安装markdown pdf插件
- 安装完成后，在左侧栏看到markdown pdf，点击它的齿轮，然后找到Markdown-pdf:Styles的选项，点击"在settings.json中编辑"
- 在settings.json中，最后加入一行：`"markdown-pdf.styles": ["{path to folder}\\**markdown_vs_code_完美生成pdf.css**"]`
> 从`https://blog.csdn.net/luckybaimao/article/details/81140597`借荐过来，原创作者的css并不好用，还是他介绍的那个`markdown_2.css`好用，也就是现在这个`markdown_vs_code_完美生成pdf.css`
- 安装完成后，键入ctrl+p，输入">"
- 用pdf关键字来搜索到markdown pdf export
- 点击它即可在md文件所在的文件夹里面生成pdf文件

## Markdown在浏览器的显示
- 在chrome或者chrome内核的浏览器中安装markdown view plus这个插件，蓝底黑色M字样
- 在它的选项内，把"允许本地文件URL"这一个选项开启，才可以正常显示本地的md文件
- **Clearness**最好用，可以正常**显示语法高亮**
- 其它的李笑来、少数派的css，在不涉及代码的情况下，还是比较美观的
