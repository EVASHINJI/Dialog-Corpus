# 开源模型

- Seq2Seq
  - 单轮对话、微博等数据都可以用
  - 链接
    - https://github.com/tensorflow/nmt 
    - https://github.com/google/seq2seq 
    - 最朴素的S2S，相关链接比较多，别的开源还有基于transformer实现的版本可以参考

- SeqGAN
  - 单轮对话、微博等数据都可以用
  - 开源链接 
    - https://github.com/LantaoYu/SeqGAN
    - 相关的实现也比较多，也可以参考其他的实现
  - 论文 [Link](https://arxiv.org/pdf/1609.05473.pdf)
- SMN - Sequential Match Network
  - 多轮对话
  - 使用的数据集  [Douban_Conversation_Corpus](../datasets/Douban_Conversation_Corpus.md)
  - 开源链接 https://github.com/MarkWuNLP/MultiTurnResponseSelection
  - 论文 [Link](https://pdfs.semanticscholar.org/a6ee/c00f10346ce27d4f69f9e38f5665fffe8056.pdf)
- ESIM - Enhanced Sequential Inference Model 
  - 阿里开源、多轮对话
  - 使用的数据集 [Ubuntu Dataset](Ubuntu_Dialogue_Corpus_v2.md) / [E-commerce_Dataset](../datasets/E-commerce_Dialogue_Corpus.md)
  - 开源链接 https://github.com/alibaba/esim-response-selection
  - 论文 [Link](https://arxiv.org/pdf/1901.02609.pdf)