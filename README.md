武汉大学硕士论文LaTaX模版
========================

本模版基于黄正华老师(http://aff.whu.edu.cn/huangzh/) 模版修改而成，特此感谢。
在黄正华老师模版基础上，做了一些更加符合论文习惯的修改，并重新整理了目录结构。


注意事项
--------

* 采用XeLaTeX进行编译，默认所有文本文件使用utf8编码格式
* 模版默认使用Adobe系列中文字体，字体可以在黄正华老师模版包(http://aff.whu.edu.cn/huangzh/) 中找到，也可以自行下载。


编译顺序
--------

论文最终发布时，推荐按照如下顺序进行编译

     xelatex main
     bibtex main
     xelatex main
     xelatex main


文件结构
--------

* README.md -- 本说明文档
* data/backmatter.tex -- 致谢、授权协议书
* data/chapter01.tex -- 正文第一章
* data/chapter02.tex -- 正文第二章
* data/chapter03.tex
* data/chapter04.tex
* data/chapter05.tex
* data/frontmatter.tex -- 英文封面、郑重声明
* data/midmatter.tex -- 中英文摘要
* figures/whu.eps
* figures/whulogo.eps
* figures/whulogo.pdf
* main.tex -- 主文档
* ref/reference.bib -- 参考文献管理
* whuthesis.cls
