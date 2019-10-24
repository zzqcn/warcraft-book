# 魔兽争霸中文小说合集

这里搜集整理了**魔兽争霸**相关中文小说. 所有小说使用`restructuredText <http://docutils.sourceforge.net/rst.html>`_ 写成, 可以使用 `sphinx-doc <https://www.sphinx-doc.org/>`_ 编译为 HTML 或 PDF 等格式.

## 准备工作

1. 安装 Sphinx
2. 安装 XeLaTex (编译为 PDF 时需要)

## 编译为HTML网页

1. 进入 source 目录
2. 运行 `make html`

编译后的文件在 `source/_build/html` 中. 如:

.. image:: built_html.png

## 编译为PDF

1. 进入 source 目录
2. 运行两次 `make latexpdf`

编译后的文件在 `source/_build/latex/warcraft-books.pdf`. 如:

.. image:: built_pdf.png