# 医疗实体识别系统

本系统可以从文本中挖掘出疾病名、药品名。

## 仓库说明

### train

- 训练语料
train_file(CRF++输入格式)
subtask1_training_afterrevise.txt(原始数据文件)
- 训练出的模型
model_file(二进制文件)
model_file.txt(文本文件)

### evaluation

- 评测语料
疾病名评测语料.txt
- 评测工具
conlleval.pl
- 评测结果
dd_result.txt

### CRF++

- Windows包 CRF++-0.58.zip
- Linux包 CRF++-0.58.tar.gz

### sklearn-crfsuite示例

- skleaern-crfsuite.ipynb使用示例笔记
