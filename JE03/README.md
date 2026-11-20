**multimodal_text_tabular.ipynb**

このJupyterノートブックは、AutoGluonのMultiModalPredictorを使って、テキストデータと表形式データ（数値・カテゴリ）を組み合わせて本の価格を予測するクイックスタートのチュートリアルです。

MachineHackの「Book Price Prediction Hackathon」から提供される書籍価格予測用のデータセット（Data.zip 内の Data_Train.xlsx）です。著者、あらすじ（概要）、評価（星評価・レビュー数）などの特徴量から本の価格（Price）を予測するために使われます。ノートブックでは前処理として文字列の評価やレビュー数を数値化し、価格を対数変換したうえで、デモ用に学習1,500件・テスト5件へサブサンプリングしています。

This Jupyter notebook is a quick-start tutorial showing how to use AutoGluon's MultiModalPredictor to predict book prices by combining text data with tabular data (numerical and categorical features).

This is the book price prediction dataset (Data_Train.xlsx inside Data.zip) from the MachineHack Book Price Prediction Hackathon, used to predict a book's Price from features such as author, abstract, and ratings. In the notebook, rating and review strings are converted to numeric values, Price is log-transformed, and the data is subsampled (1,500 training rows and 5 test rows) for a quick demo.

---
