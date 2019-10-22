# Markdown-Misc

## VS Code中从Markdown文件生成PDF
- 在vs code中安装markdown pdf插件
- 安装完成后，在左侧栏看到markdown pdf，点击它的齿轮，然后找到Markdown-pdf:Styles的选项，点击"在settings.json中编辑"
- 在settings.json中，最后加入一行：`"markdown-pdf.styles": ["{path to folder}\\**markdown_vs_code_完美生成pdf.css**"]`
- 安装完成后，键入ctrl+p，输入">"
- 用pdf关键字来搜索到markdown pdf export
- 点击它即可在md文件所在的文件夹里面生成pdf文件
