## 🎯 Kaggle Predict Future Sales - 初提出成功！

### ✅ 実施内容
- ラグ特徴量（1ヶ月・2ヶ月）
- 集計特徴量（平均売上など）
- カテゴリ・店舗・売上特徴量
- LightGBM モデルによる学習（early_stoppingあり）
- `sample_submission.csv`ベースで提出用ファイル作成
- ✅ 初スコア提出：Private 1.23658 / Public 1.25011

### 😵 苦戦ポイント
- メモリ不足によるクラッシュ → 月数を制限して対応
- LightGBMのバージョン差異（early_stoppingの書き方違い）
- 提出ファイルの列ミス（ID以外の余計な列含む）

### 🙌 得られた学び
- `merge → lag → 再分割` の時系列系パターンの強さ
- 提出形式は `sample_submission.csv` ベースが安定
- チューニング前でも十分戦えるベースラインが完成！
