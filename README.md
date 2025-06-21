## forked from narimiran/nim-basics
## nim-basics-chs

### 介绍
自用中文版nim-basics机翻文档。在线预览：[Nim basics 中文文档](https://sakuraflows.github.io/nim-basics-chs/)
<br/>
翻译模型：深度求索 DeepSeek-V3-0324

### 使用教程
windows下推荐使用Linux子系统wsl2构建本文档
<br/>
依次运行如下指令（适用于Ubuntu），安装依赖
```
sudo apt install make ruby-full  安装make和ruby
sudo gem install asciidoctor asciidoctor-epub3 rouge   安装asciidoctor相关依赖
```


构建文档
<br/>
`make`
<br/>
可用的选项：`make clean`

If you just want to see the changes, while working on a significant refactoring, you can just build web version, as it is much faster:
<br/>
`make web`
<br/>

## 其它注意事项

##### 关于可视化编辑
你可以使用vscode + AsciiDoc扩展实现对本项目文档的便捷编辑。

我们也正在考虑将本项目的文档转换为更为流行的Markdown格式。

<br/>

Nim是一门正在快速迭代的新兴程序语言，因此本文档中的内容不免存在过时情况，请根据自己的实际情况按需阅读和学习。 

本文档的所有内容均为机翻，如您有勘误及补充，欢迎在 issues 提出！

##### 关于epub view
推荐使用calibre浏览及阅读文档构建生成的pdf文件，使用其它软件阅读可能导致乱码。

<br/>

### 原文档项目地址及网站

[narimiran/nim-basics](https://github.com/narimiran/nim-basics)

[Nim basics](https://narimiran.github.io/nim-basics/) 

### license
[MIT License](LICENSE.txt)
