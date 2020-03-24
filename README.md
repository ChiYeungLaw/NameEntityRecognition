# 中文命名实体识别

利用Pytorch实现了BiLSTM和BiLSTM-CRF命名实体识别模型

将测试集20%的数据划分为验证集，将所有命名实体识别为'O'作为Baseline模型。

|   Model    | Test Set Accuracy |
| :--------: | :---------------: |
|  Baseline  |      85.872%      |
|   BiLSTM   |      92.049%      |
| BiLSTM-CRF |      91.587%      |

