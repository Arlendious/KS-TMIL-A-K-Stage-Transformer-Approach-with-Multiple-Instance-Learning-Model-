# KS-TMIL: K-Stage Transformer with Multiple Instance Learning for WSI Classification

This repository contains the official implementation of the paper:

**KS-TMIL: K-Stage Transformer with Multiple Instance Learning for WSI Classification**

> We propose a novel K-Stage Transformer-based Multiple Instance Learning framework (KS-TMIL) designed to capture spatial and morphological dependencies across patches in Whole Slide Images (WSIs). Unlike traditional MIL approaches that treat patches as independent instances, our approach uses a multi-stage transformer architecture with an Inception-Based Position Encoding Generator (IBPEG) block to model patch relationships more effectively. Evaluations on the UBC Ovarian Cancer Subtype Classification dataset show an AUC of **99%** and a balanced accuracy of **93.3%**.

---

## 🔍 Overview

Existing Multiple Instance Learning (MIL) methods often ignore spatial relationships among image patches in WSIs. KS-TMIL addresses this limitation using:

- **K-Stage Transformer**: Captures inter-patch relationships at multiple abstraction levels.
- **IBPEG Module**: Enhances spatial encoding via inception-style processing.
- **Flexible architecture**: Supports variants with different numbers of transformer layers.

---

## 📊 Dataset

We use the **UBC Ovarian Cancer Subtype Classification and Outlier Detection** dataset, publicly available on Kaggle:

🔗 [UBC Ovarian Cancer Dataset on Kaggle](https://www.kaggle.com/competitions/ubc-ooc-subtype-classification)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ks-tmil.git
cd ks-tmil
