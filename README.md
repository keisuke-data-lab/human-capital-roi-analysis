# Human Capital ROI Analysis (人的資本ROI分析)

## 📌 Project Overview
従業員のパフォーマンスデータを用いた「教育投資対効果（ROI）」の分析プロジェクトです。
架空の人事データを使用し、研修時間やコストが従業員の成果（パフォーマンススコア）に与える影響を統計的に検証しました。

## 🎯 Objectives
- **投資対効果の可視化**: 研修時間とパフォーマンスの相関関係を明らかにする。
- **ハイパフォーマー分析**: ロジスティック回帰分析を用い、高評価を得るための決定的な要因を特定する。

## 🛠 Tools & Libraries
- **Language**: Python 3.12
- **Data Manipulation**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn (Logistic Regression)
- **Business Intelligence**: Power BI (Dashboarding)

## 📊 Key Findings
1. **研修のROI**: 研修時間（Training Hours）とパフォーマンスには正の相関が確認され、教育投資が成果に結びついていることが示唆されました。
2. **成功要因**: 要因分析の結果、ハイパフォーマンス人材になる確率を高める最も強い要因は「研修時間」であることが統計的に証明されました。

## 📈 Executive Dashboard (Power BI)
経営層向けの人的資本ROIモニタリングダッシュボード。
投資対効果 (ROHCI) をリアルタイムで可視化し、施策ごとの予算配分最適化を支援します。

![HR ROI Dashboard](images/dashboard_roi.png)

### 💡 Dashboard Insights
* **High ROI**: 全社ROHCIは **188.01%** を達成し、投資額の約3倍の削減効果を創出。
* **Best Practice**: 施策別では「専門スキル認定」と「オンボーディング強化」が最も高い投資対効果を示した。
* **Action**: 営業部は投資額・削減額ともに最大であり、施策の恩恵を最も受けているため、他部署への横展開を検討。

## 📂 Directory Structure
```text
├── data/      # Analysis data (CSV)
├── images/    # Dashboard screenshots & charts
├── notebooks/ # Jupyter Notebooks for analysis
├── outputs/   # Exported charts and reports
└── src/       # Python source scripts
