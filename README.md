# 異世界設定データ管理システム

このアプリは、異世界転移小説のための世界観・キャラクター・設定などを整理・管理するためのStreamlitアプリです。

📁 構成
data/ - YAMLファイルを保存する各カテゴリごとのディレクトリ

app.py - メインアプリケーション

requirements.txt - 必要なPythonライブラリ

🧙‍♂️ 機能
世界観、キャラ、投稿などをカテゴリ分けして編集・保存

YAMLファイル形式でデータ管理

専用フォームによる簡単編集機能付き

## 🔧 インストール方法

```bash
git clone https://github.com/あなたのユーザー名/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
streamlit run app.py
