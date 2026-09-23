衛星データを用いた真珠浜揚げ量予測の流れ

1. データ収集（JAXA G-Portal）   
▶jaxa-earth ライブラリを使用し、JAXAの地球観測プラットフォーム「G-Portal」から衛星データを取得
▶英虞湾周辺（2018–2025年）における、真珠の生育に影響を与える3つの環境指標（海面水温・クロロフィルa・降水量）の月平均データを収集
2. 前処理・統合   
▶取得した衛星データを解析可能な配列データ（NumPy）へ変換・整形して統合   
3. 解析・予測   
▶水質環境と浜揚げ量の相関を分析し、予測モデルを構築して収穫量を予測

---
Workflow for predicting pearl production using satellite data

1. Data collection（JAXA G-Portal）   
▶Retrieve satellite data from JAXA's Earth observation platform "G-Portal" using the jaxa-earth library.
▶Collect monthly average data for three environmental indicators affecting pearl growth (Sea Surface Temperature, Chlorophyll-a, and Precipitation) around Agu Bay from 2018 to 2025.
2. Preprocessing and integration   
▶Convert and format the acquired satellite data into analysis-ready array data (NumPy) and integrate them.   
3. Analysis and prediction   
▶Analyze the correlation between water environment factors and pearl production volume, then build a predictive model to forecast harvest quantities.

---
