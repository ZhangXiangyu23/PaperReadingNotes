### A Survey on Knowledge Graphs:Representation, Acquisition and Applications

#### 整体结构：

1.第一节：文章总体介绍

2.第二节：知识图的概述，包括历史，符号，定义和分类

3.第三节：从四个方面讨论了KRL

4.第四节：回顾了知识获取和时间知识图的任务

5.第五节：回顾了知识获取和时间知识图的任务

6.第六节：介绍了下游应用

7.第七节：讨论了未来的研究方向，并在最后进行了总结

#### 一、背景介绍

相关概念：

知识图作为一种结构化的人类知识形式，近年来受到学术界和产业界的广泛关注。知识图是事实的结构化表示，包括实体、关系和语义描述。实体可以是真实世界的对象和抽象概念，关系表示实体之间的关系，实体及其关系的语义描述包含定义良好的含义的类型和属性。



#### 二、创新之处以及改进

Full-view categorization and new taxonomies.

提出了知识图研究的全视角分类方法，并提供了新的细粒度分类方法。在高层中，我们从三个方面回顾了知识图:KRL、知识获取和知识感知应用。对于KRL方法，我们进一步提出了细粒度分类法，分为四个视图，包括表示空间、评分函数、编码模型和辅助信息。在知识获取方面，KGC分为基于嵌入的排序、关系路径推理、逻辑规则推理和元关系学习;实体关系获取任务分为实体识别、类型化、消歧和对齐;



#### 三、相关介绍

##### 从四个方面讨论KRL：

Representation Space

Scoring Function

Encoding Models

Embedding with Auxiliary Information

知识表示学习是知识图研究领域的重要内容。本节回顾了KRL的四次折叠。总的来说，开发一个新的KRL模型是要回答以下四个问题:

1)选择哪个表示空间;2)如何度量特定空间中三元组的似然性;3)如何编码模型来建模关系交互;4)是否利用辅助信息。

最常用的表示空间是欧几里德点基空间，通过在向量空间中嵌入实体，并通过向量、矩阵或张量建模交互。研究了其它表示空间，包括复向量空间、高斯分布、流形空间和群。流形空间相对于点的欧几里得空间有一个优势，那就是放松了点的嵌入。高斯嵌入能够表达实体和关系的不确定性以及多重关系语义。嵌入复杂向量空间可以有效地建模不同的关系连接模式，尤其是对称/反对称模式。表示空间在编码实体语义信息和获取关系属性方面起着重要作用。在构建表示学习模型时，应仔细选择和设计合适的表示空间，以匹配编码方法的性质，平衡表达性和计算复杂性。基于距离度量的评分函数采用翻译原理，而语义匹配评分函数采用复合算子。编码模型，尤其是神经网络，在实体和关系的交互建模中起着至关重要的作用。双线性模型也受到了广泛的关注，一些张量因子分解也可以看作是这一类。其他方法包含了文本描述、关系/实体类型和实体图像等辅助信息。



##### 知识图完成

1.Knowledge Graph Completion

（1）Embedding-based Models

（2）Relation Path Reasoning

（3）RL-based Path Finding

（4）Rule-based Reasoning

（5）Meta Relational Learning

（6）T riple Classification

2.Entity Discovery

将基于实体的知识获取分为实体识别、实体消歧、实体分类和实体对齐等多个细分任务。我们称它们为实体发现，因为它们都在不同的背景下探索实体相关的知识。

（1） Entity Recognition

（2）Entity T yping

（3）Entity Disambiguation

（4）Entity Alignment

3.Relation Extraction

（1）Neural Relation Extraction

（2）Attention Mechanism

（3）Graph Convolutional Networks

（4）Adversarial T raining

（5）Reinforcement Learning



#####  TEMPORAL KNOWLEDGE  GRAPH

1.Temporal Information Embedding

2.Entity Dynamics

3.Temporal Relational Dependency

4.Temporal Logical Reasoning

#### 四、应用

1.Natural Language Understanding

2.Question Answering

3.Recommender Systems



#### 五、总结

知识图作为人类知识的集合，随着知识表示学习、知识获取方法以及各种知识感知应用的出现，越来越受到人们的关注。本文对以下四个方面进行了全面的研究:

1)知识图嵌入，从嵌入空间、评分指标、编码模型、外部信息嵌入和培训策略等方面进行了全面系统的综述;

2)从嵌入学习、关系路径推理和逻辑规则推理三个角度，实现实体发现、关系抽取和图补全的知识获取;

3)时态知识图表示学习与补全;

4)在自然语言理解、推荐系统、问题回答和其他杂项应用上的现实世界的知识感知应用。此外，还介绍了一些有用的数据集和开源图书馆资源，并对未来的研究方向进行了讨论。知识图谱拥有一个庞大的研究社区，并拥有广泛的方法论和应用。