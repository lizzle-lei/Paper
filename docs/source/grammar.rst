.. Lumache documentation master file, created by
   sphinx-quickstart on Mon Mar 14 23:01:51 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

reStructured 语法
===================================

.. toctree::
   :maxdepth: 2
   
===========
章节标题
===========
Book Title
############

*********************
Chapter 1
*********************

1.2 Section
=======================

1.2.3 Subsection
^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.3.4 Paragraph
''''''''''''''''''''''

粗体
**Bold**

斜体
*Italic*

内联代码
``inline code``

链接

`Jinkan <http:://jinkan.org>`_

段落里面包含 `Jinken`_.

.. _Jinken: https://jinkan.org/

段落里包含 `a link`_.

.. _a link: http://example.com/


脚注

| Lorem ipsum dolor sit amet, consectetur adipiscing elit.
| Pellentesque dignissim Libero quis ipsumsagittis, vel dapibus justo dignissim [1]_.
| Quisque scelerisque dictum sapien sit amet blandit.
| Maecenas scelerisque feugiat urna in egestas.

.. [1] this is a footnote

代码块

.. code-block:: python

    import numpy



注解

.. note:: 
    lorem upsum

天地有\ **大美**\ 而不言，四时有明法而不议，万物\ [2]_\ 有成理不说。圣人者，原天地之美而达万物之理。是故至人无为，大圣不作，观于天地之谓也。

.. [2] 这是一个脚注


列表

1. 这是一个列表
2. 这是另一个
3. C 
   
.. note::

    | #,及上划线表示部分
    | *,及上划线表示章节
    | =,小章节
    | -,子章节
    | ^,子章节的子章节
    | ",段落

| 这些行
| 在源文件里
| 被分隔的一模一样.