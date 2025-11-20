このプロジェクトは **Django (Backend)** と **React (Frontend)** で構成されています。
開発を始める際は、以下の手順で環境をセットアップしてください。

## 🛠 前提条件

- Python (3.x 系) がインストールされていること
- Node.js (v18 以上推奨) がインストールされていること

---

## 🚀 環境構築手順 (初回のみ)

リポジトリをクローンした後、ターミナルを 2 つ開いて、それぞれで以下の作業を行ってください。

### 1. Backend (Django) のセットアップ

**ターミナル A** で実行:

```Bash
cd backend

# 仮想環境の作成

python -m venv venv

# 仮想環境の有効化 (Mac/Git Bash)

source venv/bin/activate

# 仮想環境の有効化 (Windows PowerShell)

# .\venv\Scripts\activate

# ライブラリのインストール

pip install -r requirements.txt

# データベースの初期セットアップ

python manage.py migrate
```

### 2. Frontend (React) のセットアップ

**ターミナル B**で実行:

```Bash

cd frontend

# 依存パッケージのインストール

npm install
```
