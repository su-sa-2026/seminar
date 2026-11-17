AutoGluon Predictors: https://auto.gluon.ai/0.3.1/api/autogluon.predictor.html#

AutoGluon (v0.3.1) の Predictors（予測器）のAPI仕様書です。表データ、画像、テキストなどを、わずか数行のコード（fit()関数など）で自動的に高精度に学習・予測できる主要クラス群（TabularPredictor, ImagePredictor など）の仕組みやパラメータを解説しています。

API documentation for AutoGluon (v0.3.1) Predictors. It outlines the high-level predictor classes (such as TabularPredictor, ImagePredictor, etc.) that enable training and evaluating high-performance machine learning models on tabular, image, or text data with just a few lines of code (fit()).

---
Tabular-Text Transformer (TTT): https://github.com/thomas-bonnier/TabularTextTransformer

TabularTextTransformer (TTT) は、数値・カテゴリとテキストが混在する表形式データ（金融リスクや医療診断など）を高精度に予測・分析するためのマルチモーダル Transformer です。

TabularTextTransformer (TTT) is a multimodal Transformer architecture for tabular data containing text fields (e.g., for medical diagnosis or financial risk).

---
テキスト特徴量抽出手法の比較 / Comparison of Text Feature Extraction Methods

<img width="1632" height="784" alt="image" src="https://github.com/user-attachments/assets/6389b198-b5c9-4d5b-969a-e78dcae3dce3" />

---
代表的なテキスト特徴量抽出手法の比較 / Comparison of typical text feature extraction methods

<img width="1278" height="1108" alt="image" src="https://github.com/user-attachments/assets/116a40d9-c787-4936-be58-08be84b5e0cf" />

---
数値データ
 前処理・標準化 → 数値エンコーダ（MLP）→ 数値エンベディング

テキストデータ
 前処理・トークン化 → テキストエンコーダ（BERTなど）→ テキストエンベディング

統合処理
 共通次元へ変換 → **Fusion（連結・ゲート・Attention）** → 分類／回帰 → 予測結果

Numerical data
 Preprocessing and scaling → Numerical encoder (MLP) → Numerical embedding

Text data
 Preprocessing and tokenization → Text encoder (e.g., BERT) → Text embedding

Fusion process
 Projection into a common dimension → **Fusion (concatenation, gating, or attention)** → Classification/regression → Prediction output

 ---
 

