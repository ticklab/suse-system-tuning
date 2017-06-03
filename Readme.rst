Readme
===============================

该仓库是 opensuse 系统分析和优化文档 的中文翻译。原文请参考 `System Analysis and Tuning Guide`_ 。

构建依赖
-------------------------------

* sphinx
* make
* sphinx_py3doc_enhanced_theme

构建方法
--------------------------------

.. code-block:: shell

   make html
   
在上述命令完成之后，将会在 build/html 中生成所有的静态页面。

PDF 文件生成方法：

.. code-block:: shell

   make xelatexpdf

构建清理
--------------------------------

.. code-block:: shell

   make clean
   

.. _System Analysis and Tuning Guide: https://doc.opensuse.org/documentation/leap/tuning/html/book.sle.tuning/book.sle.tuning.html