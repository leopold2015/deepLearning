# deepLearning
本仓库将实现深度学习的基础原理

#### 注意力提示
非自主性提示和自主性提示
自主性的与非自主性的注意力提示解释了人类的注意力的方式，
- 非自主性提示是基于环境中物体的突出性和易见性。
- 受到了认知和意识的控制， 因此注意力在基于自主性提示去辅助选择时将更为谨慎。

#### 查询、键和值
在注意力机制的背景下，自主性提示被称为查询（query）。 
给定任何查询，注意力机制通过注意力汇聚（attention pooling）将选择引导至感官输入（sensory inputs，例如中间特征表示）。
在注意力机制中，这些感官输入被称为值（value）。 更通俗的解释，每个值都与一个键（key）配对， 这可以想象为感官输入的非自主提示。 

键：代表非意志线索，即非自主性提示
值：感觉输入
查询：意志线索，即自主性提示


