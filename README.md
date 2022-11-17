# Presentation Slide 演示文档模板

**请尽可能使用最新版本进行文章撰写，我们的代码仓库是：https://github.com/BITNP/BIThesis 。**

## 特性

- 内容和样式分离，所有的配置可以集中管理。
- 由社区驱动，在积极地吸纳新功能、修复现有问题。
- 在你的学术报告演示文档中使用参考文献。

## 项目结构

```sh
.
├── README.md
├── bithesis.pdf # bithesis 使用手册
├── images
│   └── bit.png
├── main.tex
└── ref.bib
```

## 编译方式

方式一（推荐）：
```
latexmk
```

方式二：
```
-> xelatex
-> biber
-> xelatex
-> xelatex
```

- *不推荐使用 pdflatex 进行编译*

## 其他链接

- 项目地址：https://github.com/BITNP/BIThesis
- Bug report 与 Feature Request：https://github.com/BITNP/BIThesis/issues
- QQ 交流群：737548118
