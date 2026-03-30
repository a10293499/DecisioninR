# 心臟病發作風險預測：決策樹優化分析 (R Language)

[cite_start]本專案利用心臟病數據集，透過 R 語言建立並優化決策樹模型。核心目標是平衡「預測精準度」與「臨床解釋性」 [cite: 7, 8]。

## 專案亮點
* [cite_start]**手動剪枝**：透過手動剪枝 (Pruning) 策略，將測試集準確率從系統建議的 **73% 顯著提升至 82%** [cite: 246]。
* [cite_start]**模型決策**：捨棄過於簡化的模型，保留 **cp (胸痛類型)**、**caa (血管數量)**、**exng (運動誘導心絞痛)** 作為核心決策路徑 [cite: 206, 247]。
* [cite_start]**嚴謹驗證**：執行 **5-Fold 交叉驗證**，確保模型在面對新數據時具備良好的穩定性 [cite: 221, 239]。

## 使用技術
* [cite_start]**建模工具**：`rpart`, `rpart.plot` [cite: 60, 62]
* [cite_start]**效能驗證**：`caret` (K-Fold CV) [cite: 224, 226]
* [cite_start]**資料處理**：`dplyr`, `skimr` [cite: 13, 23]
* [cite_start]**報告呈現**：Quarto (HTML 互動報告) [cite: 2, 3]

## 線上瀏覽報告
 [點此查看完整分析網頁](https://a10293499.github.io/DecisioninR/)
