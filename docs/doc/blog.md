# 技术博客



<table>
  <tr>
    <th>领域</th>
    <th>时间</th>
    <th>论文</th>
    <th>摘要</th>
  </tr>
  <tr>
    <td><button>Triton</button></td>
    <td>2024/09/27</td>
    <td><a url="https://zhuanlan.zhihu.com/p/730534981">如何用 Triton实现一个更高效的topk_gating kernel？——算子合并技术</a></td>
    <td>在当前的代码架构下，MoE的gating网络面临一个亟待解决的问题：其内部充斥着众多小kernel，这些小kernel的频繁启动显著增加了计算开销，对模型训练的整体效率产生了不可忽视的负面影响。因此，想要实现更高效的topk_gating kernel，将这些分散的小kernel整合为一个大kernel，以此减少kernel启动的开销，是一种非常直接的思路。在本文中，我们首先观察了topk_gating算子的内部工作机制，并据此设计并尝试了三种不同的优化策略：利用Cuda Graph进行流程优化、采用torch.compile进行自动优化，以及实施Kernel fusion进行手动或自动的kernel整合。经过详细的比较验证后，我们最终确定了基Triton实现的Kernel fusion为最优选择，它在整体性能提升方面表现最为出色。以下将详细阐述每种优化策略的基本原理、实施细节以及它们各自在提升模型训练效率方面的具体成效。</td>
  </tr>
  <tr>
    <td><button>HPC</button></td>
    <td>2024/09/27</td>
    <td><a url="https://zhuanlan.zhihu.com/p/714231501">支持变长序列的Mamba-1训练</a></td>
    <td>Mamba 是一种专为处理长序列设计的新型架构，其相对于传统的 Transformer 架构能够显著提高超长序列文本的处理速度。在训练过程中，我们通常通过增加批次大小来提升训练效率。然而，实际应用中，数据序列长度往往分布不均，简单地通过填充（padding）来调整至固定长度可能会引入大量冗余数据，导致拖慢训练速度。为了解决这一问题，我们在 Mamba 框架中引入了一种新的序列处理机制。该机制能够打包（Pack）不同长度的序列，动态地识别和处理不同序列的上下文，避免上下文混淆，保证处理的一致性。这种方法能够减少冗余数据，显著提高训练速度。实验结果表明，在 NVIDIA A100 GPU 上使用 Mamba-1.4B 模型进行预训练时，与传统的单序列处理方案相比，加速比达到了 3.06 倍。这一改进不仅有效解决了变长序列处理的问题，还大幅提高了整体的训练和推理速度，使得模型在各种硬件上都能达到预期的训练效率。

</td>
  </tr>
  <!-- 更多行和单元格 -->
</table>


<script>
json:table{
    "caption" : "表格标题",
    "fields" : [
        {"key": "a", "label": "AA", "sortable": true},
        {"key": "b", "label": "BB", "sortable": true},
        {"key": "c", "label": "CC", "sortable": true}
    ],
    "items" : [
      {"a": "11", "b": "22", "c": "33"},
      {"a": "34", "b": "65", "c": "33"},
      {"a": "56", "b": "32", "c": "54"},
      {"a": "211", "b": "222", "c": "233"}
    ],
    "filter": true
}
</script>
