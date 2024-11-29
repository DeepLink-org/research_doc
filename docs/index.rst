.. DeepLink Doc documentation master file, created by
   sphinx-quickstart on Thu May 11 14:46:13 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
.. role:: red

.. role:: blue


DeepLink Research Group
==============================================
上海人工智能实验室的编译计算与国产化团队由裴芝林老师领导，专门开发用于深度学习模型训练和部署的高效系统和架构。我们创建内部和开源系统，以在数千个 AI 芯片上高效训练大型语言模型和多模态模型。

团队的研究已在 OSDI、NSDI 和 ASPLOS 等领先会议上获得认可，彰显了我们对创新的承诺。我们获得了 ASPLOS 2024 最佳论文奖和 ASPLOS 2023 杰出论文奖。

编译计算与国产化团队隶属于由林达华教授和张行程领导的系统平台中心。

我们一直在寻找充满热情的个人，包括全职研究工程师和实习生，加入我们的团队。如果您有兴趣为机器学习系统的前沿研究做出贡献，请通过 sunpeng@pjlab.org.cn 与我们联系。


联合培养博士项目
~~~~~~~~~~~~~~~~~~~~

网络与分布式系统研究组（NDS）现招收与上海交通大学或复旦大学联合培养的博士研究生。研究方向主要集中在大规模人工智能模型训练系统的性能优化与能耗优化。研究组内科研氛围浓厚，提供充足的算力资源和生活补助，并与国内外知名系统研究团队保持密切合作，每年都有高质量的研究成果产出。

对NDS组感兴趣的同学请将简历发送至导师孙鹏的邮箱：sunpeng@pjlab.org.cn。

（2025年入学）（名额已满） 上海人工智能实验室2025年高校联合培养博士研究生项目现已启动，欢迎2025年毕业的（具有保研资格）本科生积极参与。具体情况请参考招生简介。

新闻短讯
~~~~~~~~~~~~~~~~~~~~

===============  ==================================================================================================  =========
时间              Paper                                                                                               A and B
===============  ==================================================================================================  =========
Jun 29, 2024     A Holistic Functionalization Approach to Optimizing Imperative Tensor Programs in Deep Learning     DAC 2024   
True   False  False
False  True   False
True   True   True
===============  ==================================================================================================  =========



精选论文
~~~~~~~~~~~~~~~~~~~~

+--------------------+-----------------------------------------------------------+---------------------------+-----------------------------------------------------------+
|        Date        |                            Paper                          |        Confernece         |                                                           |
+====================+===========================================================+===========================+===========================================================+
|     Jun 29, 2024   | A Holistic Functionalization Approach to Optimizing       | was accepted by DAC 2024  |A Holistic Functionalization Approach to Optimizing        |
|                    | Imperative Tensor Programs in Deep Learning               |                           |Imperative Tensor Programs in Deep Learning,               |
|                    |                                                           |                           |2023 年 11 月投稿，2024 年 6 月录用，其中,                     |
|                    |                                                           |                           |主要完成单位是:上海人工智能实验室, 北京大学, 上海交通大学商汤, 香港  |
|                    |                                                           |                           |于函数式编程中的不可变变量（Immutable Variable）和传统编译器中的静 |
|                    |                                                           |                           |态单赋值技术（SSA），对带有控制流的命令式张量程序中的 View 语义进行优|
|                    |                                                           |                           |化。实验表明,工作对多个深度学习任务相比于主流的深度学习编译器有最高   |
|                    |                                                           |                           |1.8x 的优化。                                               |
+--------------------+-----------------------------------------------------------+---------------------------+-----------------------------------------------------------+
|     Jun 29, 2024   | Achieving Energetic Superiority Through System-Level      | was accepted by SC 2024   |                                                           |
|                    | Circuit Simulation                                        |                           |                                                           |
+--------------------+-----------------------------------------------------------+---------------------------+-----------------------------------------------------------+



索引
====================

.. toctree::
   :maxdepth: 1
   :caption: 高性能
   :includehidden:

   doc/homepage

.. toctree::
   :maxdepth: 1
   :caption: 编译
   :includehidden:

   doc/homepage
   

.. image:: _static/image/pic_moban.jpeg 

.. image:: image_path1
   :align: left

+------------+------------+
| Image 1    | Image 2    |
+============+============+
| |image1|   | |image2|   |
+------------+------------+

.. |image1| image:: _static/image/pic_moban.jpeg 
.. |image2| image:: _static/image/pic_moban2.jpeg 

.. |long_text| replace:: This is a very long text that should be wrapped across multiple lines in the table. It will be automatically wrapped because we are using a grid table.

+---------------+-------------------------------+
| Column 1      | Column 2                     |
+===============+===============================+
| Short text    | |long_text|                  |
+---------------+-------------------------------+
| Another line  | More long text that should be |
|               | wrapped in the table.         |
+---------------+-------------------------------+