<div align="center">
    <img src="./imgs/logo.png">
    <h1>
        Hulun Papers
    </h1>
</div>

个人近期论文阅读囫囵吞枣式极简笔记，用于备忘与快速查阅



## 1. Transformers

- Transformer不适合NER任务及其解决方案，[pdf](./papers/Transformer/TENER：Adapting_Transformer_Encoder_for_Named_Entity_Recognition.pdf)，[arXiv](https://arxiv.org/abs/1911.04474)，[知乎](https://zhuanlan.zhihu.com/p/137315695)
- FastFormer，一个Transformer加速方案(GPU&CPU)，[pdf](./papers/Transformer/FastFormers：Highly_Efficient_Transformer_Models_for_Natural_Language_Understanding.pdf)，[arXiv](https://arxiv.org/abs/2010.13382)，[知乎](https://zhuanlan.zhihu.com/p/275659092)
- Performer，Google提出的一种新的Transformer架构，提升推理与训练速度和内存利用率，[pdf]()，[arXiv]()，[知乎](https://zhuanlan.zhihu.com/p/269751265)，[github](https://github.com/google-research/google-research/tree/master/performer)



## 2. 模型剪枝

- LayerDrop，对每一层进行随机mask，提升模型每一层的鲁棒性，最终可以根据mask概率直接修剪模型，[pdf](./papers/Pruning/Reducing_Transformer_Depth_on_Demand_with_Structured_Dropout.pdf)，[arXiv](https://arxiv.org/pdf/1909.11556.pdf)，[知乎](https://zhuanlan.zhihu.com/p/93207254)



## 3. Dialogue Management

- 对话管理综述(2021)，[pdf](./papers/Dialogue/DialogueManagement/A_Survey_on_Dialog_Management：Recent_Advances_and_Challenges.pdf)



## 4. 多模态

- data2vec，一个适用于视觉、语音、文本的自监督学习框架，[pdf](./papers/MultimodelFrame/data2vec：A_General_Framework_for_Self-supervised_Learning_in_Speech，Vision_and_Language.pdf)，[paper](https://scontent-nrt1-1.xx.fbcdn.net/v/t39.8562-6/271974914_483120576492438_4239522333319653600_n.pdf?_nc_cat=107&ccb=1-5&_nc_sid=ae5e01&_nc_ohc=4-cMR5tUq4QAX8dVp4v&_nc_ht=scontent-nrt1-1.xx&oh=00_AT8Zy56yb0ihUA9DMJnJpw4qb3xjC1Q4UbGwP3k1Lq_Baw&oe=61F3F7D1)，[夕小瑶](https://mp.weixin.qq.com/s/pJqKtqM8WQBm8FbgaxGmpQ)



## 5. 对比学习

- CPC，对比学习的基础模型，[pdf](./papers/ContrastiveLearning/Representation_Learning_with_Contrastive_Predictive_Coding.pdf)，[arXiv](https://arxiv.org/abs/1807.03748)，[github](https://github.com/davidtellez/contrastive-predictive-coding)



## 6. ASR

- wav2vec2.0，一个强大的语音预训练模型，使用了对比学习模式，[pdf](./papers/ASR/wav2vec2.0：A_Framework_for_Self-Supervised_Learning_of_Speech_Representations.pdf)，[wav2vec1.0 pdf](./papers/wav2vec：Unsupervised_Pre-training_for_Speech_Recognition.pdf)，[github](https://github.com/pytorch/fairseq/tree/main/examples/wav2vec)



## *. 其他

- LSTM+CRF学习率不一致，[苏神博客：你的CRF层学习率可能不够大](https://spaces.ac.cn/archives/7196)

