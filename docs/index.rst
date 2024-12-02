.. DeepLink Doc documentation master file, created by
   sphinx-quickstart on Thu May 11 14:46:13 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
.. role:: red

.. role:: blue


DeepLink Research Group
==============================================
上海人工智能实验室的编译计算与国产化团队由裴芝林老师领导，专门开发用于深度学习模型训练和部署的高效系统和架构。我们创建内部和开源系统，以在数千个 AI 芯片上高效训练大型语言模型和多模态模型。

团队的研究已在 DAC, SC, COLM, ECCV 等领先会议上获得认可，彰显了我们对创新的承诺。

编译计算与国产化团队隶属于由林达华教授和张行程领导的系统平台中心。

我们一直在寻找充满热情的个人，包括全职研究工程师和实习生，加入我们的团队。如果您有兴趣为编译器、高性能计算等的前沿研究做出贡献，请通过 deeplink@pjlab.org.cn 与我们联系。

导师简讯
~~~~~~~~~~~~~~~~~~~~

+------------+-----------+-----------+-----------------------------------------+
| Image 1    | Name      | Title     |  Field                                  |
+============+===========+===========+=========================================+
| |image1|   | |s1_name| | |s1_ti|   | |s1_field|                              |
+------------+-----------+-----------+-----------------------------------------+
| |image2|   | |s2_name| | |s2_ti|   |  |s2_field|                             |
+------------+-----------+-----------+-----------------------------------------+
| |image1|   | |s3_name| | |s2_ti|   |  |s3_field|                             |
+------------+-----------+-----------+-----------------------------------------+

.. |image2| image:: _static/image/pic_moban.jpeg 
   :width: 100px
.. |image1| image:: _static/image/pic_moban2.jpeg 
   :width: 100px
.. |s1_name| replace:: 裴芝林
.. |s1_ti| replace:: Leader
.. |s1_field| replace:: 计算编译：针对国产硬件架构特点，利用编译器技术，采用图模式和算 子模式相结合，完成融合算子调用和生成，图捕获，图编辑提高算子计 算效率。
.. |s2_name| replace:: Dr.Fu Rong(付蓉)
.. |s2_ti| replace:: Supervisor
.. |s2_field| replace:: 自动化：基于函数式编程中的不可变变量（Immutable Variable）和传统编译器中的静态单赋值技术（SSA），对带有控制流的命令式张量程序中的 View 语义进行优化。 对检测网络的后处理、递归神经网络、LSTM 等场景，相比于深度学习编译器 TorchDynamo、TorchScript 有最高1.8x优化。（被顶会DAC接收）
.. |s3_name| replace:: 袁晟
.. |s3_ti| replace:: Supervisor
.. |s3_field| replace:: 探索基于triton的高性能训练技术，通过多种现代编译加速技术，使用编译子图划分、编译融合等方式，提升国产计算体系的整体效能。

联合培养博士项目
~~~~~~~~~~~~~~~~~~~~

网络与分布式系统研究组（NDS）现招收与上海交通大学或复旦大学联合培养的博士研究生。研究方向主要集中在大规模人工智能模型训练系统的性能优化与能耗优化。研究组内科研氛围浓厚，提供充足的算力资源和生活补助，并与国内外知名系统研究团队保持密切合作，每年都有高质量的研究成果产出。

对NDS组感兴趣的同学请将简历发送至导师孙鹏的邮箱：sunpeng@pjlab.org.cn。

（2025年入学）（名额已满） 上海人工智能实验室2025年高校联合培养博士研究生项目现已启动，欢迎2025年毕业的（具有保研资格）本科生积极参与。具体情况请参考招生简介。


最新资讯
~~~~~~~~~~~~~~~~~~~~

.. csv-table:: Frozen Delights!
    :header: "会议/期刊", "论文", "摘要"
    :widths: 10, 15, 30

    "DAC 2024", "A Holistic Functionalization Approach to Optimizing Imperative Tensor Programs in Deep Learning", "A Holistic Functionalization Approach to Optimizing Imperative Tensor Programs in Deep Learning, 2023 年 11 月投稿，2024 年 6 月录用，其中，主要完成单位是：上海人工智能实验室，北京大学，上海交通大学，商汤，香港中文大学，第1作者麻津铭是项目参与人员。基于函数式编程中的不可变变量（Immutable Variable）和传统编译器中的静态单赋值技术（SSA），对带有控制流的命令式张量程序中的 View 语义进行优化。实验表明，工作对多个深度学习任务相比于主流的深度学习编译器有最高 1.8x 的优化。"
    "SC 2024", "Achieving Energetic Superiority Through System-Level Circuit Simulation", "Achieving Energetic Superiority Through System-Level Quantum Circuit Simulation，2024年4月投稿，2024年6月录用。针对生成不相关的随机量子电路样本挑战，利用大规模系统技术，研究了如何突破内存限制和提高计算效率，提出了一种在全局、节点和设备层面进行优化的创新方法，实验表明该方法能够处理高达数十太字节的大规模张量网络，在速度和能效方面均优于Google的Sycamore量子处理器，为课题开展高性能、高扩展的三维并行融合调度训练系统在系统设计、性能优化等多个方面提供了理论支撑。"
    "COLM 2024", "SKVQ: Sliding-window Key and Value Cache Quantization for Large Language Models", "本工作提出了 SKVQ（滑动窗口 KV 缓存量化）来量化LLM推理过程中产生的 KV Cache。SKVQ 通过利用注意力模块的性质大幅提高KV缓存量化精度。实验评估表明，SKVQ 优于以前的量化方法，可以将 KV 缓存量化为 2-bit Key和 1.5-bit Value，只带来很小精度损失。这一改进允许在 80GB GPU 上为 7B 参数模型处理高达 1M 个令牌的上下文长度，理论解码速度提高 7 倍。"
    "ECCV workshop 2024","Fisheye-GS: Lightweight and Extensible Gaussian Splatting Module for Fisheye Cameras","提出了鱼眼高斯，通过重新计算鱼眼相机的投影变换及其梯度，解决了3D高斯喷洒（3DGS）在不同相机模型，特别是鱼眼镜头上的适应性问题，显著提升了视觉质量，并展示了其模块化设计的轻量级和可扩展性。"
    "ECCV workshop 2024","PackMamba: Efficient Processing of Variable-Length Sequences in Mamba Training","提出了 PackMamba，通过优化 Mamba 架构中的瓶颈算子，实现了对可变长度序列的高效处理，显著提升了 NVIDIA A100 GPU 上的吞吐量，分别在 1.4B 和 2.8B 模型上实现了 3.06 倍和 2.62 倍的加速。"

索引
====================

.. toctree::
   :maxdepth: 1
   :caption: 团队介绍
   :includehidden:

   doc/team/triton
   doc/team/hpc
   doc/team/compile


.. toctree::
   :maxdepth: 1
   :caption: 团队论文
   :includehidden:

   doc/paperlist.md

.. toctree::
   :maxdepth: 1
   :caption: Blog
   :includehidden:

   doc/blog.md
 
