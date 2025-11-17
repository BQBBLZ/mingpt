# minGPT（MindSpore）训练/微调示例

本仓库包含基于**MindSpore**的minGPT训练/微调示例。

## 环境要求
- **Python** ≥ 3.9  
- **MindSpore (ms)** ≥ 2.6.0  
- **CANN** ≥ 8.1.RC1（仅 Ascend 场景必需；请确保驱动/CANN/固件版本与 MindSpore 匹配）

> MindSpore 的安装命令请参考官方指引：  
> https://www.mindspore.cn/install/

## 运行mingpt_fintune_lora.ipynb

在运行文件之前，建议先在终端安装依赖：
```bash
pip install -r requirements.txt
```
如果在Notebook内安装，请将下列指令放在文件最前面并先执行：
```python
!pip install -r requirements.txt
```

## 目录结构
```
.
├─ metrics/
│  ├─ __init__.py
│  ├─ perplexity.py
│  └─ rouge.py
├─ mingpt/
│  ├─ __init__.py
│  ├─ bpe.py
│  ├─ lora_inject.py
│  ├─ model.py
│  ├─ trainer.py
│  └─ utils.py
├─ mingpt_fintune_lora.ipynb
└─ README.md
```
