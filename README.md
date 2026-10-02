# NCHU Machine Learning

國立中興大學「機器學習」課程（大四上）的作業與課堂實作紀錄。

## 我的作業 — [`assignments/`](assignments/)

### Ex1：SVM 分類與迴歸 — [`4112056048_ex1.ipynb`](assignments/4112056048_ex1.ipynb)

**Part 1：用 SVM 預測使用者是否購買**
- 以 Pandas 讀入使用者資料（400 筆），選用 `age`、`estimated_salary` 作為特徵
- 以 75/25 切分訓練／測試集，並用 `StandardScaler` 標準化
- 訓練 RBF kernel 的 `SVC`，**測試集準確率 93%**
- 以網格預測繪製決策邊界，視覺化訓練集與測試集的分類結果

**Part 2：Support Vector Regression**
- 以 `make_regression` 產生 1000 筆、3 個特徵的資料（noise = 5.0）
- 標準化後訓練 linear kernel 的 `SVR`
- 分析支持向量數量、比較預測值與真實值，**MSE ≈ 27.4**

## 課堂教材與實作 — [`course-materials/`](course-materials/)

課堂上跟著操作的 notebook 與講義，內容參考 Aurélien Géron《Hands-On Machine Learning》。

| 主題 | Notebook | 講義 |
|---|---|---|
| End-to-end ML 專案 | [c1_end-to-end_ML_project.ipynb](course-materials/c1_end-to-end_ML_project.ipynb) | — |
| 分類 | [c1_classification.ipynb](course-materials/c1_classification.ipynb) | [PDF](course-materials/c1_classification.pdf) |
| 迴歸 | [c2_regression.ipynb](course-materials/c2_regression.ipynb) | [PDF](course-materials/c2_regression.pdf) |
| 支持向量機 | [c3_svm.ipynb](course-materials/c3_svm.ipynb) | [PDF](course-materials/c3_svm.pdf) |

## 使用工具

Python · NumPy · Pandas · scikit-learn · Matplotlib · Jupyter
