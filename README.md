 # TensorFlow - AI问答
基于 TensoFlow 构建 SeqSeq 模型，并加入 Attention 机制，encoder 和 decoder 为 3 层的 RNN 网络。  
由于初步实现，效果并不是十分理想，只能进行简单的对答，训练数据也有很大关系。

## 开发环境
- 开发语言：Python
- 框架：TensorFlow

## 代码结构
- `generate_chat.py` - 清洗数据、提取 ask 数据和 answer 数据、提取词典、为每个字生成唯一的数字 ID、ask 和 answer 用数字 ID 表示；
- `seq2seq.py`、`seq2seq_model.py` - TensorFlow 中 Translate Demo稍微改动；
- `train_chat.py` - 训练 SeqSeq 模型；
- `predict_chat.py` - 进行聊天。

## 使用指南
目录中包含的训练好的模型，可以直接使用：
>python predict_chat.py 

自己训练的话：
>python train_chat.py



 
