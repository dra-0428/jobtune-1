
# JobTune Render公開版

## 起動手順（ローカル）

### フロントエンド
```
cd frontend
npm install
npm run dev
```

### バックエンド
```
cd backend
pip install fastapi uvicorn
uvicorn main:app --reload
```

## Render用メモ
- frontend, backend を個別に2つのWeb Serviceとして作成
- バックエンドは FastAPI を使用
- 環境変数として OPENAI_API_KEY を設定
