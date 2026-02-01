# 🏆 poet-ident-RUBert-LSTM

### Сlassification of poetic texts using 2 approaches: pre-trained RuBERT (fine-tuning) and LSTM architecture. PyTorch implementation includes comparison of transformer vs RNN approaches for classification task.
<div align="center">


[![Stars](https://img.shields.io/github/stars/yourusername/rubert-poetry-classifier?style=social)](https://github.com/VeronikaKolimova/poet-ident-RUBert-LSTM/stargazers/)

</div>

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0-orange)](https://pytorch.org/)
[![Transformers](https://img.shields.io/badge/Transformers-4.30-blueviolet)](https://huggingface.co/docs/transformers/index)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-orange)](https://scikit-learn.org/)
[![RuBERT](https://img.shields.io/badge/RuBERT-base-cased-red)](https://huggingface.co/DeepPavlov/rubert-base-cased)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)

</div>

# 🌹 Классификация авторства русских стихотворений / Russian Poetry Authorship Classification

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)](https://pytorch.org)
[![HuggingFace](https://img.shields.io/badge/🤗-Transformers-ffcc00.svg)](https://huggingface.co)
[![License MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status Completed](https://img.shields.io/badge/status-completed-brightgreen.svg)]()

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/repo/blob/main/L_07.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yourusername/repo/HEAD)

## 🌍 Описание / Description
**RU**: Классификация авторства стихотворений (Бунин, Есенин, Маяковский, Цветаева) с применением нейросетей: простые модели LSTM/BiLSTM и дообученная модель RuBERT (DeepPavlov). Сравнение архитектур, визуализация метрик, анализ ошибок. Точность RuBERT: **96.83%**.

**EN**: Authorship classification of Russian poems using neural networks: custom LSTM/BiLSTM and fine-tuned RuBERT (DeepPavlov). Model comparison, metrics visualization, error analysis. RuBERT accuracy: **96.83%**.

## 🚀 Быстрый старт
```bash
pip install -r requirements.txt
python train.py  # или запустите L_07.ipynb в Jupyter
