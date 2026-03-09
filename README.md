## 內容說明

### 1. `Final_Project_簡報.pdf`
期末簡報投影片

### 2. `mario-bros/`（Super Mario Bros）
- `Mario_Final.ipynb`：Mario 訓練與測試 Notebook（含 custom reward / SkipFrame / 訓練策略等）  
- `mario_balanced_best.pth`：最佳模型權重（用於測試與錄影）  
- `mario_train/`：訓練過程錄影（依 episode 保存）  
- `mario_test/`：載入權重後的測試錄影（展示距離/分數表現）  
- `training_curve.png`, `test_score.png`：訓練曲線與測試分數圖表

### 3. `lunar-lander/`（LunarLander-v2）
- `LunarLander.ipynb`：LunarLander 訓練與測試 Notebook  
- `lunar_final.pth`：訓練完成模型權重  
- `lunar_lander_train/`：訓練過程錄影（依 episode 保存）  
- `lunar_lander_test/`：測試錄影（多回合結果）  
- `training_curve.png`, `train_score_*.png`, `test_score.png`：訓練/測試曲線與分數統計圖  
- `prev_test_land_8_score_136.mp4`：額外的測試示例錄影（補充展示）

---

## 如何查看成果
1. 或在資料夾內開啟 `mario_test/`、`lunar_lander_test/` 的 mp4 觀看測試結果
2. 若需重現流程，可開啟對應的 `.ipynb`（Mario_Final.ipynb / LunarLander.ipynb），記得裡面內容執行，執行 cell 1 得重啟工作階段繼續執行下方 cell