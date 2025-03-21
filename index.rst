.. ZJB-Docs documentation master file, created by
   sphinx-quickstart on Wed Nov 22 13:12:42 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

OpenDTB documentation
==============================

OpenDTB是由中国科学院自动化研究所脑网络组开发的灵活, 高效, 易扩展, 用户友好的数字孪生脑仿真平台, 为基于数字孪生脑的脑科学研究范式提供支持. 平台支持构建由不同脑图谱, 不同动力学模型和多模态信息约束的数字孪生脑, 并能够对构建的数字孪生脑模型进行高效地仿真和参数空间探索, 对仿真结果进行多样的分析. 用户可以容易地实现自定义动力学模型, 仿真参数和分析方法等. OpenDTB-GUI库为以上功能提供了用户友好的图形界面.

- 文档: https://OpenDTB-docs.readthedocs.io
- 资源: https://github.com/OpenDTB/OpenDTB-Assets
- 源代码:
    - Python库: https://github.com/OpenDTB/OpenDTB-MAIN
    - GUI应用: https://github.com/OpenDTB/OpenDTB-GUI
- 错误报告:
    - Python库: https://github.com/OpenDTB/OpenDTB-MAIN/issues
    - GUI应用: https://github.com/OpenDTB/OpenDTB-GUI/issues

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: GUI应用:

   gui/ZJB-GUI-document.md

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Python库:

   main/create_dtb.md
   main/stimulus.md
   main/examples.rst

.. toctree::
   :hidden:
   :maxdepth: 2
   :caption: 参考:

   api.rst


.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`
