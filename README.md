# 🚀 Credit Risk Classification Pipeline
**Production ML: XGBoost 88.5% recall ($1.27M bad loans saved)**

## 📊 Results Table
| Model | Recall | F1 | ROC-AUC |
|-------|--------|----|---------|
| **XGBoost** | **88.5%** | 87.2% | 91.2% |
| Random Forest | 83.5% | 82.1% | 86.7% |

**Impact**: 83/94 bad loans caught → **$1.27M annual savings**

## 📓 Live Colab Notebooks
- [01_EDA_Preprocessing](https://colab.research.google.com/drive/12fFXxI-8-pjdlcmLGNl7-UZ1G1lFVc32)
- [02_Model_Development](https://colab.research.google.com/drive/1LeysnDxsUroEanYPmGG3CG7xKJO6hvQj)
- [03_Evaluation](https://colab.research.google.com/drive/15JybYS6sVf8P8lQsluqAHcWOS7bL5x3d)

## 🚀 Production API Ready
```bash
pip install -r requirements.txt
uvicorn api.main:app --reload
