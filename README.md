# 🏆 poet-ident-RUBert-LSTM

### Сlassification of poetic texts using 2 approaches: pre-trained RuBERT (fine-tuning) and LSTM architecture. PyTorch implementation includes comparison of transformer vs RNN approaches for classification task.
<div align="center">

[![Stars](https://img.shields.io/github/stars/VeronikaKolimova/poet-ident-RUBert-LSTM?style=social)](https://github.com/VeronikaKolimova/poet-ident-RUBert-LSTM/stargazers/)

</div>

<div align="center">

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)](https://pytorch.org)
[![HuggingFace](https://img.shields.io/badge/🤗-Transformers-ffcc00.svg)](https://huggingface.co)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-orange)](https://scikit-learn.org/)
[![RuBERT](https://img.shields.io/badge/RuBERT-base--cased-red)](https://huggingface.co/DeepPavlov/rubert-base-cased)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
[![Status Completed](https://img.shields.io/badge/status-completed-brightgreen.svg)]()

</div>

# 🌹 Классификация авторства русских стихотворений / Russian Poetry Authorship Classification


## Открыть ноутбук (рекомендуется):
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VeronikaKolimova/poet-ident-RUBert-LSTM/blob/main/L_07.ipynb)

## 🌍 Описание / Description
**RU**: Классификация авторства стихотворений (Бунин, Есенин, Маяковский, Цветаева) с применением нейросетей: простые модели LSTM/BiLSTM и дообученная модель RuBERT (DeepPavlov). Сравнение архитектур, визуализация метрик, анализ ошибок. Точность RuBERT: **96.83%**.

**EN**: Authorship classification of Russian poems using neural networks: custom LSTM/BiLSTM and fine-tuned RuBERT (DeepPavlov). Model comparison, metrics visualization, error analysis. RuBERT accuracy: **96.83%**.

## 📊 Key Results
| Model | Epochs | Val Accuracy | Val Loss |
|-------|--------|--------------|----------|
| Frozen BERT | 10 | **63.65%** | 1.0997 |
| Fine-tuned | **5** | **96.88%** | **0.1449** |

**Dataset**: 420 Russian poems, 4 authors (294 train / 63 val / 63 test)

## 🚀 Quick Start
```bash
pip install -r requirements.txt
jupyter notebook L_07.ipynb
```

## 💾 Dataset & Model
dataset.csv
RuBERT checkpoint: DeepPavlov/rubert-base-cased[file:62]


## 📈 Results Visualization
![Training Curves](https://raw.githubusercontent.com/VeronikaKolimova/poet-ident-RUBert-LSTM/main/images/bert_training_curves.png)
![Confusion Matrix](https://raw.githubusercontent.com/VeronikaKolimova/poet-ident-RUBert-LSTM/main/images/_lstm_cm.png)





