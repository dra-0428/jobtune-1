
# JobTune 完成版（統合機能付き）

## 機能
- Big Five + Grit に基づく診断
- GPT職種提案
- PDF出力（/download/report.pdf）
- SNS共有リンク（準備済）
- 龍マスコット案内あり（チューン）

## 起動手順

### フロントエンド
```
cd frontend
npm install
npm run dev
```

### バックエンド
```
cd backend
pip install fastapi uvicorn weasyprint
uvicorn main:app --reload
```

## 環境変数設定
```
OPENAI_API_KEY=your_openai_api_key_here
```
